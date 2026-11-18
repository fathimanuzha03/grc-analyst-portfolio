# Evidence inventory and validation
**Evidence status:** scenario statements plus deliberately synthetic exhibits. No live control testing.

## Evidence inventory
| ID | Source / observation | Reliability and use |
|---|---|---|
| S01 | Reference case: no formal risk assessment; 2021 policy lacks board approval | Supplied scenario assertion; X-R02 / X-C01 |
| S02 | Reference case: direct developer production access; no PAM | Scope and operating detail not independently inspected; X-R01 / X-C11 |
| S03 | Reference case: CloudTrail enabled, irregular review | Does not establish logging coverage; X-R04 / X-C14–15 |
| S04 | Reference case: patching is informal | Actual coverage/ages unknown; X-R06 / X-C12 |
| S05 | Reference case: backups configured, no DR plan or BIA | No restore success established; X-R03 / X-C07,13 |
| S06 | Reference case: three critical suppliers unreviewed | Actual vendor control quality unknown; X-R05 / X-C04 |
| S07 | Reference case: annual training without completion records | Training occurrence and evidence distinguished; X-R09 / X-C09 |
| S08 | Reference case: keycards, no visitor log | No unauthorised entry claimed; X-R10 / X-C10 |
| U01–U04 | Change safeguards, incident arrangements, inventory, processing requirements | Open requests supporting X-R07, X-R08, X-R11, X-R12 respectively |
| D01–D04 | Synthetic datasets below | Constructed for reproducible portfolio analysis; never actual Xown exports |

## Synthetic exhibits
**D01 — access sample**
| Identity | Privileged | Interactive | Standing access | Approval record |
|---|---|---|---|---|
| dev-a | Yes | Yes | Yes | No |
| dev-b | Yes | Yes | Yes | No |
| ops-oncall | Yes | Yes | No | Yes |
| svc-report | Yes | No | Yes | No |
| finance-user | No | Yes | No | Yes |

**D02 — backup sample:** B01 and B02 have successful backup-job status; both have an empty restore-evidence field.

**D03 — event sample:** login-failure is reviewed; privilege-grant and data-export are not reviewed. A missing review is not proof that an event is malicious.

**D04 — training sample:** eligible population P01–P10; completion rows P01, P02, P03, P04, P04, P99. P04 is duplicated; P99 is outside the eligible population.

## Performed checks on synthetic data
| Check | Rule applied | Result | Interpretation |
|---|---|---|---|
| X-V01 | Count privileged standing identities; separately inspect interactive approvals | 3/4 privileged identities standing; 2/3 interactive privileged identities lack approval | Prioritise entitlement review; a workload identity requires a suitable non-interactive control model |
| X-V02 | Distinguish successful backup jobs from restore records | 2 successful jobs; 0 restore records | Backups alone cannot substantiate recovery |
| X-V03 | Count events with no review record | 2/3 events unreviewed | Define triage ownership and timing; no incident conclusion |
| X-V04 | Deduplicate completion rows and intersect with eligible population | 4/10 valid unique completions = 40% | Six rows do not mean 60% completion |

These four analytical checks were performed against the displayed synthetic inputs. They support the method's demonstration only; do not use the percentages as live dashboard baselines.

## Proposed acceptance tests
| Test | Action | Population/sample and method | Pass condition / reviewer |
|---|---|---|---|
| T01 | X-A01 | Full privileged identity inventory; inspect all exceptions and one elevation per mechanism | All access justified, attributable and reviewed; workload identities separately controlled / CISO |
| T02 | X-A02 | Inspect approved scope, method, risk ownership, full control-selection plan and buyer terms | Documents current, internally consistent, authorised / CEO |
| T03 | X-A03 | Restore representative service and financial dataset in isolation | Measured recovery meets approved BIA objectives; integrity reconciles / IT + business owner |
| T04 | X-A04 | Trigger authorised test event and trace alert-to-escalation | Relevant sources covered; record meets agreed triage timing / CISO |
| T05 | X-A05 | Review all three critical services, dependencies and customer responsibilities | Scoped evidence, risk decision and contract actions recorded / CISO + Legal |
| T06 | X-A06 | Reconcile inventory to scan population; inspect all overdue Critical items | No unexplained coverage gap; exceptions approved and time-limited / CISO |
| T07 | X-A07 | Inspect 10 changes, or all if fewer, across routine/emergency classes | Approval, testing and rollback evidenced; failures investigated / CISO |
| T08 | X-A08 | Exercise one supplier-origin breach and recovery scenario | Owner, clocks, customer paths and corrective actions documented / Legal + CISO |
| T09 | X-A09 | Reconcile entire eligible population against unique valid training records | Target reached; all exceptions owned / HR + CISO |
| T10 | X-A10 | Inspect visitor handling during one authorised visit and 10 recent records if available | Authorisation, logging and escort practice consistent / Office owner |
| T11 | X-A11 | Reconcile critical services with cloud/accounts/endpoints and accountable owners | No unowned critical dependency / CISO |
| T12 | X-A12 | Inspect all critical processing flows and relevant agreements | Legal confirms requirements and outstanding actions; no unsupported compliance claim / Legal |

These are proposed review methods, not ISO-prescribed sample sizes. Record tester, date, population, sample selection, evidence pointer, exceptions and retest for every executed live test. A single successful example does not prove year-round effectiveness.

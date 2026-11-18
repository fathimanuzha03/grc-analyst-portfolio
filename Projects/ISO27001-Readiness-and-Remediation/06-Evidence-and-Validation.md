# Synthetic evidence and validation
**All records below are constructed for this simulation.** No live system or real personal data was accessed.

## E01 — partner integration register
| Route | Credential label | Scope | Age since rotation |
|---|---|---|---:|
| Depot-A connector | K01 | All tenants | 180 days |
| Operator-B connector | K01 | All tenants | 180 days |
| Depot-C connector | K02 | Tenant C | 35 days |
| Operator-D connector | K03 | Tenant D | 9 days |

K01 is an invented identifier, not a usable credential. **Check H-V01:** three unique credential labels serve four routes; one label is reused across two routes. Both affected routes have broader scope than their stated customer boundary. Credential age alone does not prove compromise.

## E02 — identity reconciliation sample
| Identity | Employment state | Support account |
|---|---|---|
| U01 | Active | Enabled |
| U02 | Active | Enabled |
| U03 | Departed | Enabled |
| U04 | Active | Disabled |
| U05 | Departed | Enabled |

**Check H-V02:** two of two departed identities retain enabled accounts. Review and revoke unjustified access; an active employee's disabled account is not automatically a control failure.

## E03 — recovery timeline, UTC
| Event | Synthetic timestamp |
|---|---|
| Latest recoverable dataset | 17 November 2026, 23:00 |
| Service disruption | 18 November 2026, 10:00 |
| Restored application validated | 18 November 2026, 16:10 |

**Check H-V03:** recovery elapsed = 370 minutes (**6h10**); data age at disruption = 660 minutes (**11h**). Against proposed RTO 6h / RPO 2h: recovery exceeds target by **10 minutes**; data age exceeds target by **9 hours**. Both fail. No real restore was executed.

## E04 — release sample
Application changes C01–C06 each have an independent approval record. Configuration changes C07 and C08 have none. All eight are treated as production releases in this synthetic sample.

**Check H-V04:** six of eight releases have an approval record (75%); two of eight lack one. Reviewing only the six application releases would incorrectly report 100%.

## Further case conditions
Audit retention is set to 14 days without a documented investigation requirement; risk authority and retention rules remain drafts; partner outage responsibility and identity-independent recovery are untested. These are constructed scenario conditions, not extra performed tests.

## Proposed implementation acceptance tests
| Test | Coverage and method | Reviewer / pass condition |
|---|---|---|
| T01 | Inspect all four connector routes; revoke/rotate the reused material; test permitted and prohibited scopes | Security Lead: unique accountable credentials and least scope |
| T02 | Full employee/contractor-to-account reconciliation; inspect all departed identities and exceptions | IT + HR owner: no unjustified leaver access |
| T03 | Positive and negative tests for each tenant/API boundary and role combination | Independent engineering/security reviewer: unauthorised cases denied |
| T04 | Representative application/data restore, including keys, dependencies and integrity | Operations/business owner: approved RTO/RPO met |
| T05 | Inspect eight recent releases, or all if fewer, across every release class | Security Lead: approval, testing and rollback evidence complete |
| T06 | Authorised synthetic access event traced to triage/escalation; assess coverage and retention requirement | Security Lead: owner and timing demonstrated |
| T07 | Inspect scope, policy, methodology, risk owners and exception decisions | Managing Director: internally consistent approved record |
| T08 | Reconcile customer-purpose rules to configured retention and representative deletion | Privacy Lead: justified schedule and tested exceptions |
| T09 | Exercise one connector outage and customer update workflow | Partnerships/business owner: fallback and communications work |
| T10 | Conduct authorised emergency access without primary SSO | IT/Security: controlled access, recovery and post-use review |

These are proposed acceptance methods, not ISO-mandated samples. A live test record needs tester, date, population, sample selection, evidence, exceptions and retest. Current results above validate analysis of fabricated inputs, not production effectiveness.

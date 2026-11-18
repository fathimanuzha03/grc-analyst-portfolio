# Focused readiness and control review
**Simulation basis:** defined scenario and exhibits | **Assurance opinion:** none

## Management-system assessment
| Clause area | Scenario assessment | Required management output |
|---|---|---|
| 4 — context and scope | Enterprise service boundary and partner dependencies not formally approved | Scope, interested parties, customer requirements and relevant context decisions |
| 5 — leadership | Service decisions have owners, but security authority is not defined | Approved policy, delegated authority and accountable sponsor |
| 6 — planning | Draft exceptions lack a common assessment/acceptance method | Owned risk register, treatment plan and complete control selection |
| 7 — support | Implementation capacity and role competence not evidenced | Named allocations, competence plan and controlled records |
| 8 — operation | Different change paths; no consistent treatment verification | Repeatable operations, change approvals and review records |
| 9 — evaluation | No independent readiness review or formal management review supplied | Metrics, audit programme, independent findings and management decisions |
| 10 — improvement | No evidence-based closure loop supplied | Root cause, correction, retest and effectiveness review |

## Prioritised control topics
References are paraphrased topic mappings, not the complete standard or a final Statement of Applicability.

| Topic | Reference | Constructed observation | Status | Risk / action |
|---|---|---|---|---|
| Identity lifecycle | A.5.16 | Two departed users remain active | Gap | H-R02 / H-A02 |
| Entitlement review | A.5.18 | Access reconciliation does not include the leaver feed | Gap | H-R02 / H-A02 |
| Cloud service responsibilities | A.5.23 | Hosting exists; service/customer obligations not fully mapped | Partial | H-R09 / H-A09 |
| ICT recovery readiness | A.5.30 | Recovery does not meet proposed objectives | Untested live; synthetic failure | H-R04, H-R10 / H-A04, H-A10 |
| Personal-data safeguards | A.5.34 | Retention schedule awaits approval | Partial | H-R08 / H-A08 |
| Authentication information | A.5.17 | A connector credential is reused with broad scope | Partial | H-R01 / H-A01 |
| Technical vulnerabilities | A.8.8 | Application dependency scanning excludes configuration images | Partial | H-R05 / H-A05 |
| Configuration controls | A.8.9 | Tenant configuration has no negative-test record | Untested | H-R03 / H-A03 |
| Backup arrangements | A.8.13 | Nightly jobs exist; recovery needs have changed | Partial | H-R04 / H-A04 |
| Monitoring | A.8.16 | Events expire after 14 days without a review owner | Gap | H-R06 / H-A06 |
| Secure development | A.8.25 | Customer-boundary tests are not demonstrated | Untested | H-R03 / H-A03 |
| Change control | A.8.32 | Six application changes reviewed; two configuration changes not reviewed | Partial | H-R05 / H-A05 |

**Topic population:** 12; 3 Gap, 6 Partial, 3 Untested. “Untested live; synthetic failure” is counted as Untested. These categories do not produce an ISO compliance percentage.

## Selection and evidence gate
Before a formal external engagement, assess every necessary control against risk, law and customer obligations; compare against all Annex A references; justify inclusion/exclusion; include additional controls where needed; record implementation and evidence; obtain approval.

A named product is not the control requirement. Credential isolation, least privilege, evidence retention and independent recovery may be delivered in different effective ways. Test results and responsibilities determine adequacy.

This focused project does not establish conformity. The current licensed standard and relevant amendments must be validated for formal use. [Primary references](07-Sources-and-Review.md)

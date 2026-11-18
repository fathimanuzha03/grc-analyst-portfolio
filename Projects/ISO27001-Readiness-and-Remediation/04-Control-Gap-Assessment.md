# Focused control gap assessment
**Basis:** case statements and identified evidence gaps | **Audit opinion:** none issued

This is a readiness review. “Partial” means the scenario describes some activity, not that its effectiveness was tested. “Unverified” means a conclusion needs evidence. No maturity average or certification readiness percentage is calculated from unknowns.

## Management system
| Area | Initial assessment | Gap or question | Required output / action |
|---|---|---|---|
| Clause 4: context and boundary | Unverified | Scope, interested parties and context decision not evidenced | Approved scope, legal/customer register; evaluate relevant context amendments / X-A02 |
| Clause 5: leadership | Partial | Sponsor and new CISO exist; policy has not been board-approved | Approved policy, responsibilities and decision authority / X-A02 |
| Clause 6: planning | Gap described | No formal risk assessment | Method, register, treatment plan and complete control selection / X-A02 |
| Clause 7: support | Partial | Training occurs; completion records do not exist | Resource commitments, role competence and controlled records / X-A09 |
| Clause 8: operation | Partial | Ad hoc practices; repeatable treatment evidence missing | Owned operational processes and change records / X-A01–X-A12 |
| Clause 9: evaluation | Unverified | Internal audit, metrics and formal review evidence not supplied | Independent internal audit, management review and corrective actions / readiness gates |
| Clause 10: improvement | Unverified | No closed-loop correction records supplied | Finding log, root cause, action effectiveness and follow-up / readiness gates |

Clauses 4–10 are considered as a system; selected technical safeguards alone cannot establish conformity.

## Priority control topics
Descriptions below are paraphrased assessment topics, not reproduced standard text or an exhaustive SoA.

| ID | Reference / topic | Case observation | Initial status | Proposed evidence / owner | Risks |
|---|---|---|---|---|---|
| X-C01 | A.5.1 security direction | 2021 policy, no board approval | Partial | Current approved policy / CISO | X-R02 |
| X-C02 | A.5.9 asset ownership | Inventory not supplied | Unverified | Owned service/asset list / IT | X-R11 |
| X-C03 | A.5.18 entitlement review | Review records not supplied | Unverified | Population and recertification / IT | X-R01 |
| X-C04 | A.5.19 supplier oversight | Three critical suppliers unreviewed | Gap described | Tiering, assessment, action log / CISO | X-R05 |
| X-C05 | A.5.20 supplier agreements | Contracts not inspected | Unverified | Security/DPA clauses and responsibilities / Legal | X-R05, X-R12 |
| X-C06 | A.5.24 incident preparation | Response plan not supplied | Unverified | Approved runbook and exercise / CISO | X-R08 |
| X-C07 | A.5.30 ICT recovery preparedness | No documented DR plan/BIA | Gap described | Agreed recovery needs and restore test / IT | X-R03 |
| X-C08 | A.5.34 personal-data safeguards | Financial/payroll data in scope | Unverified | Role-based obligations/data flows / Legal | X-R12 |
| X-C09 | A.6.3 staff awareness | Annual training undocumented | Partial | Population, completion and exceptions / HR | X-R09 |
| X-C10 | A.7.2 office entry | Keycards; no visitor log | Partial | Visitor authorisation and escort records / Office | X-R10 |
| X-C11 | A.8.2 privileged entitlements | Direct developer database access; no PAM | Partial, high exposure | Approved, restricted, attributable access / IT | X-R01 |
| X-C12 | A.8.8 vulnerabilities | Informal patching | Partial | Coverage, triage, deadlines and retests / IT | X-R06 |
| X-C13 | A.8.13 backup protection | AWS backups configured | Partial | Job records, protected copies and restores / IT | X-R03 |
| X-C14 | A.8.15 event records | CloudTrail enabled | Partial | Coverage, integrity, access and retention / IT | X-R04 |
| X-C15 | A.8.16 monitoring response | Logs not regularly reviewed | Gap described | Alerts, triage and escalation records / IT | X-R04 |
| X-C16 | A.8.32 controlled changes | Change safeguards not supplied | Unverified | Peer review, approval and rollback / Development | X-R07 |

**Selected-topic summary:** 7 Partial; 3 Gap described; 6 Unverified. These 16 topics are not the full 93-control population. No exclusions, full implementation conclusions or audit findings are approved here.

## Control-selection completion gate
Before calling any document a final SoA, CISO must:
1. Determine necessary controls from assessed risks and legal/customer requirements.
2. Compare against every Annex A reference; add controls outside Annex A where necessary.
3. Record inclusion rationale, implementation status and justified exclusions.
4. Identify evidence and accountable owners; validate supplier/customer responsibilities.
5. Obtain management approval and maintain the decision through changes.

A cloud provider's certification supports supplier assurance; it does not establish correct customer configuration, access administration, application security or Xown-wide conformity. [AWS responsibility model](https://aws.amazon.com/compliance/shared-responsibility-model/)

Do not label the absence of a named tool such as PAM or SIEM as an automatic standard violation. Assess whether the control objective is met through effective, evidenced arrangements. Source references and standards-access limits: [Sources and review](07-Sources-and-Review.md).

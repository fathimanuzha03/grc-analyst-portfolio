# Contract, incident and exit playbook
**Use:** proposed operating instructions; Legal and service owners must validate before use.

## Contract review checklist
Legal should confirm role-specific processing instructions, purpose/duration, data categories, confidentiality/security, authorised downstream providers, rights/incident assistance, audit information and end-of-service handling. A standard DPA label alone is insufficient. [ICO contract guidance](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/contracts-and-liabilities-between-controllers-and-processors-multi/what-needs-to-be-included-in-the-contract/)

For every critical service, also agree scope, responsibilities, location/access changes, recovery objectives, evidence rights, exit support, data export format, notice contacts and escalation. These operational terms are proposed commercial safeguards; they are not all universal statutory requirements.

V01 requires documented AI-use limits and a flow-by-flow transfer assessment. Legal must verify an applicable current route and recipient coverage; if safeguards such as an IDTA/Addendum are required, execute them and complete the applicable assessment. EU-origin flows require a separate relevant analysis. [ICO transfer guide](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/international-transfers/a-brief-guide-to-international-transfers/)

## Incident coordination
| Trigger / step | Proposed owner | Operational instruction |
|---|---|---|
| Supplier suspects or becomes aware of relevant compromise | Supplier incident lead | Notify without undue delay as applicable; proposed contract target is within 4 hours, without waiting for that limit |
| DataBridge receives notice | CISO incident commander | Log awareness times, service/data scope, access paths, facts/unknowns and containment |
| Client data affected | Legal / account owner | As processor, inform relevant controllers without undue delay; follow agreed instructions and assistance duties |
| DataBridge controller data affected, e.g. HR | Legal | Assess applicable regulator/individual notification thresholds and deadlines; do not assume every incident is reportable |
| Recovery and communications | IT / business owner | Preserve evidence, rotate/revoke affected access, use verified channels and approve customer updates |
| Follow-up | GRC / incident commander | Record corrective actions, root cause when known and reassessment triggers |

A controller's notifiable breach reporting window is not permission for its processor or subprocessor to wait 72 hours. [ICO breach guidance](https://ico.org.uk/for-organisations/report-a-breach/personal-data-breach/personal-data-breaches-a-guide/)

**Initial notice fields:** incident reference; discovery/awareness times with timezone; affected service and possible records; confirmed facts versus uncertainty; containment; contact; next update time. Do not delay an initial notice until a complete investigation.

## Recovery exercise specification
**Provisional objectives:** RTO 4 hours and RPO 1 hour for the selected production analytics dataset. These are simulation proposals, not an approved BIA or supplier guarantee. The business owner must validate tolerable disruption, dependencies and peak-period needs before contracting.

Test an isolated restore with independent credentials, integrity reconciliation, protected-copy access, key availability and representative application validation. Demonstrate export/deletion sequencing for exit. A backup job marked successful is not a restore result.

### Performed calculation on a synthetic exercise timeline
| Event | Synthetic time |
|---|---|
| Service disruption begins | 08:00 |
| Latest recoverable dataset timestamp | 07:15 |
| Recovered service validated | 13:30 |

Calculated recovery elapsed time = **5 hours 30 minutes**; data-age gap = **45 minutes**. Against the provisional objectives: **RTO fails by 1 hour 30 minutes; RPO passes by 15 minutes**. No real restore was performed. This synthetic result keeps F06 open and illustrates why a strong questionnaire score cannot authorise activation.

## Controlled supplier exit
1. Service owner approves a transition plan, customer dependencies and funding.
2. IT exports required data/configuration in usable formats and validates completeness.
3. Replacement service is tested before destructive deletion or access removal where continuity requires overlap.
4. Revoke accounts, service credentials, tokens, network trust and support paths; retain an emergency plan.
5. Legal confirms return/deletion and any legally required retention; obtain evidence covering backups and downstream providers as applicable.
6. GRC records completion, verifies critical residual dependencies and closes the register only after review.

For TechSupport Pro, a failed access-control gate triggers supervised/restricted operation or transition, with customer coordination. For IdentityHarbor, independently accessible emergency accounts must be secured and tested; “exit” cannot rely entirely on the failed identity service.

## Exercise discussion prompts
Could an attacker abuse a support session? Can DataBridge contact customers if SSO/email is unavailable? Can the backup be restored without the supplier's compromised console? Who can authorise isolation? Which facts can be communicated before investigation completes? Record actual exercise participants, decisions and follow-up when an exercise is conducted; none are fabricated here.

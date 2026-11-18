# Remediation, funding and delivery plan
**Clock:** day 0 is programme approval, not the publication date | **All actions:** proposed

## Owned remediation backlog
Days are calendar days from approval; immediate incident containment follows the incident process.

| Action | Specific outcome | Proposed owner | Due | Dependencies | Completion evidence |
|---|---|---|---:|---|---|
| X-A01 | Inventory privileged accounts; remove unjustified standing production access; use approved time-limited elevation and workload identities | Head of IT | 30 | Service owners, emergency access process | T01 |
| X-A02 | Approve scope, policy, risk method, treatment ownership and control-selection work; confirm buyer criteria | CISO | 45 | CEO sponsorship, Legal input | T02 |
| X-A03 | Complete BIA; agree recovery objectives; protect backups and execute an isolated restore | Head of IT | 90 | Service dependencies and recovery budget | T03 |
| X-A04 | Define log sources, alert owners, triage windows, retention and escalation; prove an end-to-end alert | Head of IT | 60 | Identity/asset inventory | T04 |
| X-A05 | Tier AWS/Salesforce/Zendesk services; inspect relevant reports, scope, customer obligations and contracts | CISO | 75 | Supplier inventory, Legal | T05 |
| X-A06 | Establish vulnerability coverage, risk triage and remediation SLAs; retest overdue critical items | Head of IT | 75 | Asset coverage | T06 |
| X-A07 | Require risk-based independent approval and rollback evidence for production changes | Development Lead | 60 | Pipeline and emergency-change owners | T07 |
| X-A08 | Define incident authority, evidence handling, communications and escalation; exercise the workflow | CISO | 90 | Legal and customer contact paths | T08 |
| X-A09 | Reconcile training population; retain valid completion and follow up exceptions | HR Lead | 60 | Current staff/contractor roster | T09 |
| X-A10 | Authorise and record visitors, protect sensitive workspaces and verify escort practice | Office Manager | 45 | Office owner, physical boundary | T10 |
| X-A11 | Build owned asset/service/data-flow inventories and change triggers | Head of IT | 30 | Team representatives | T11 |
| X-A12 | Validate processing roles, agreements, retention and transfer arrangements; document applicable requirements | Head of Legal | 60 | Data flows, customer/supplier terms | T12 |

The actions address all 12 registered risks. Funding and owners remain unapproved. If an action is late, its risk stays open; CISO reports the consequence and required decision rather than changing its target date silently.

## Budget reconciliation
Figures are illustrative planning allocations in GBP; they are not quotations. Values include existing staff opportunity cost and incremental external spend.

| Workstream | Existing staff effort | Incremental spend reserve | Total |
|---|---:|---:|---:|
| Access and asset controls | £20,000 | £12,000 | £32,000 |
| Vulnerability, monitoring and controlled change | £18,000 | £12,000 | £30,000 |
| Recovery and incident readiness | £8,000 | £4,000 | £12,000 |
| Supplier/privacy specialist work | £5,000 | £5,000 | £10,000 |
| Governance and awareness | £8,000 | £2,000 | £10,000 |
| Independent audit/certification reserve | £0 | £12,000 | £12,000 |
| Unallocated contingency; CEO release only | £0 | £14,000 | £14,000 |
| **Total** | **£59,000** | **£61,000** | **£120,000** |

The workstream view and £30k/£55k/£35k stage releases describe the same £120k envelope; do not add them. Quotes, VAT, new permanent salaries and major architectural rebuilding require separate confirmation. Contingency is part of the ceiling, not an extra percentage.

## Roadmap and decision gates
| Window | Milestones | Owner | Gate to proceed |
|---|---|---|---|
| Days 0–30 | Confirm scope/owners, contain production-access exposure, inventory dependencies | CEO/CISO/IT | Scope and urgent access decisions recorded |
| Days 31–60 | Approve treatment plan and control-selection method; confirm resources; share roadmap with buyer | CISO/Sales/Legal | Procurement criteria acknowledged; Gate 2 funding decision |
| Months 3–6 | Operate technical safeguards; complete BIA, supplier reviews, incident and restore exercises | IT/Legal/HR | T01–T12 evidence reviewed; no overdue Critical risk without CEO escalation |
| Months 7–9 | Complete full SoA and management-system records; internal audit by an independent assessor; resolve findings | CISO / independent auditor | Management review and Gate 3 funding decision |
| Months 10–12 | Assess external readiness; Stage 1 then Stage 2 only if appropriate | CISO / certification body | Record readiness decision, resolve assessment findings; certificate only if awarded |

Management review begins during the programme; it is not postponed until the final month. The reference contains conflicting timing hints; this project uses a 60-day roadmap deadline and a conditional 12-month external-assessment target. No audit booking or inevitable certificate award is asserted.

## RACI for recurring decisions
A = one accountable owner; R = performs; C = consulted; I = informed.

| Activity | CEO | CISO | IT | Legal | HR / service owners | Independent auditor |
|---|---|---|---|---|---|---|
| Risk appetite and funding | A | R | C | C | I | I |
| Risk assessment and treatment tracking | I | A/R | R | C | R | I |
| Technical remediation | I | C | A/R | C | C | I |
| Processing and contract review | I | C | R | A/R | C | I |
| Independent internal audit execution | A | C | C | C | C | R |

CEO commissions independent audit; CISO coordinates evidence and cannot independently audit their own implementation. Operational risk acceptance follows [the method](02-Scope-and-Method.md), not this delivery RACI alone.

## Operating dashboard
| Measure | Baseline | Proposed target / escalation |
|---|---|---|
| Critical scenario risks | 3 estimated | No unowned Critical risk from day 10; all overdue containment decisions escalated |
| Justified privileged identities | Unknown live baseline | 100% inventoried and owner-reviewed by day 30 |
| Critical supplier reviews | 0 formal reviews described | 3/3 completed or explicitly escalated by day 75 |
| Recovery capability | Backups configured; restore capability unverified | Tested recovery meets management-approved objectives by day 90 |
| Training completion evidence | No records in scenario | At least 95% of in-scope population with valid records by day 60; remainder owned |
| Risk acceptance expiry | No live register | 100% exceptions have owner, authority and expiry |

Targets are proposals. Synthetic exercise results in the evidence file are not live baseline metrics.

## Delivery risks and mitigations
Capacity competition: protect named implementation hours before release. Supplier delays: request evidence by day 10 and escalate missing reports rather than infer conformity. Tool dependence: implement proportionate controls before selecting products. Audit scheduling: book only after readiness forecast and scoped quotations; maintain a buyer-agreed fallback milestone. Gate failure: hold later funding where appropriate, retain containment and privacy duties, and rebaseline transparently.

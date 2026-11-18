# Remediation and decision tracker
**Clock:** days from approved programme start | **Commitments:** proposed, not supplier-agreed

| ID | Vendor | Gap / required outcome | Proposed internal owner | Target day | Gate | Required closure evidence | Escalation if unresolved |
|---|---|---|---|---:|---|---|---|
| F01 | V01 | Applicable restricted-transfer route/terms unestablished | Legal | 30 | Before client data | Flow map, current route/recipient coverage and executed required safeguards | Hold service; select compliant alternative |
| F02 | V01 | AI purpose, retention and training/reuse restrictions not agreed | Analytics Director | 30 | Before client data | Documented instructions, minimised test dataset, retention/deletion and prohibited reuse terms | Continue synthetic-data evaluation only |
| F03 | V01 | Downstream locations, report scope and responsibilities incomplete | CISO | 30 | Before client data | Chain map, scoped report review, customer responsibilities and authorisation | Hold onboarding and escalate evidence failure |
| F04 | V02 | 72-hour supplier notification term permits avoidable delay | Legal | 30 | Before activation | Executed prompt-notice and cooperation terms, tested contacts | Do not activate until corrected |
| F05 | V02 | Key, administration and downstream responsibilities not executed in contract schedule | Head of IT / Legal | 30 | Before activation | Agreed responsibility matrix, key owner and chain terms | Hold activation; restrict scope |
| F06 | V02 | Customer-representative recovery/exit not demonstrated | Head of IT | 60 | Before activation | Representative restore, integrity check and exit rehearsal meet approved targets | Use validated fallback; require retest |
| F07 | V03 | Encryption/key arrangements not evidenced | HR Director | 30 | Before employee migration | Service-specific encryption and key evidence reviewed by CISO | No live HR migration |
| F08 | V03 | Security test is 18 months old; closure evidence unavailable | CISO | 45 | Before employee migration | Fresh risk-appropriate test and closure/retest of relevant material findings | Hold migration or select alternative |
| F09 | V03 | Processing locations, rights/incident support and exit terms incomplete | Legal | 30 | Before employee migration | Processing schedule, required terms, location map and export plan | Hold migration |
| F10 | V04 | Privileged identity and session controls not evidenced | Support Director | 10 | Immediate containment | Named accounts, scoped/time-limited rights, strong authentication, session records | Disable unsafe access and activate controlled continuity |
| F11 | V04 | Assessment overdue by scenario's three-year gap | CISO | 30 | Before unrestricted continuation | Full diligence, legal review and signed time-limited decision | Transition provider if unresolved |
| F12 | V04 | Revocation and replacement support not tested | Head of IT | 30 | Before unrestricted continuation | Revoke/re-enable test, alternate support roster and customer coordination | Restrict to supervised sessions or transition |
| F13 | V05 | SSO concentration and emergency access unproven | Head of IT | 45 | Before privilege expansion | Independent emergency-access test and dependency recovery review | No expanded integration |
| F14 | V06 | Testing assurance limited; ticket content may exceed intended scope | Support Director | 60 | Before activation | Evidence review plus redaction/content rules and enforcement check | Restrict attachments and reassess tier if sensitive data enters |
| F15 | V07 | Payroll incident/continuity terms incomplete | Finance Director | 30 | Before activation | Reviewed incident contacts, escalation and payroll contingency | Hold release; use approved payroll fallback |

All fifteen rows are **Open / proposed**. Supplier-committed dates, contract references, evidence links, reviewers and decision signatures are **not obtained**. A target date is not a vendor commitment or proof of closure.

## Priorities and risk treatment
F10 receives first operational attention because access already exists. F01/F02/F03 and F07/F08/F09 block new sensitive-data movement. F04/F05/F06 block backup activation. Remaining actions must be tracked even where no hard stop is triggered.

Target posture after successful remediation: V01–V05 Strong, giving target scores 8, 8, 6, 8 and 8 respectively under this model. These are forecasts, not measured residual risk. V06/V07/V08 retain their current estimates until review provides a basis for change. Every supplier still requires a recorded release decision even if its target score is Moderate or Low.

**Closure workflow:** supplier submits evidence → GRC checks completeness → CISO/Legal challenge within their remit → business owner records decision → IT/Procurement release authorised scope → GRC monitors conditions. A supplier assertion alone is not sufficient to close an evidence-dependent action.

## 90-day resource envelope
| Workstream | Allocated internal effort | External/tooling/test reserve | Total |
|---|---:|---:|---:|
| Supplier diligence and evidence review | £8,000 | £6,000 | £14,000 |
| Contract and transfer assessment | £4,000 | £8,000 | £12,000 |
| Privileged-access containment | £5,000 | £2,000 | £7,000 |
| Restore, incident and exit exercises | £3,000 | £4,000 | £7,000 |
| Contingency: executive release only | £0 | £5,000 | £5,000 |
| **Total** | **£20,000** | **£25,000** | **£45,000** |

Planning estimates only. Confirm capacity and quotes. Replacement suppliers, full migrations, new permanent salaries and VAT are excluded and need separate approval. The £45k is one programme envelope; the four vendor assessments do not each receive another £45k.

## Delivery and release gates
| Window | Outcome | Owner | Review |
|---|---|---|---|
| Days 0–10 | Adopt intake gate; confirm service owners; restrict unsafe legacy support | CISO / Support / Procurement | Executive containment review |
| Days 11–30 | Priority contracts/data flows and full V04 reassessment | Legal / GRC / business owners | Keep blocked services blocked; record exceptions only where allowed |
| Days 31–60 | Evidence retests, restore and incident exercises; resolve test gaps | IT / CISO / suppliers | Release only service-specific proven scope |
| Days 61–90 | Monitor decisions, exercise exit and report open exposure | GRC / executive sponsor | Close, renew a permitted exception, or fund transition |

## Management reporting
| Measure | Simulated starting position | Proposed operating target |
|---|---|---|
| Registered suppliers with named proposed owner | 8/8 in this document | Confirm 8/8 actual owners by day 10 |
| Priority live-data migrations on hold | V01 and V03 | Zero unauthorised releases |
| High-score providers | 4/8 | All have approved treatment/containment decisions by day 30 |
| Open findings | 15/15 | Every finding has a validated owner and evidence-based closure or escalation |
| Critical-dependency recovery capability | Unverified | No activation before agreed recovery evidence; annual repeat thereafter |
| Review dates | Proposed only | No expired Tier 1 review without executive escalation |

Do not count a reminder email, a signature request or a changed due date as remediation.

# Executive decision brief
**Decision ID:** X-D01 | **Sponsor:** Caroline Marsh, CEO | **Status:** Proposed; no approval recorded

## Recommendation
Approve a staged ISO 27001 readiness programme, with immediate containment of privileged-access risk and a credible customer roadmap by day 60. The £2.4 million figure is the opportunity's annual contract value from the case, not guaranteed revenue or a quantified loss estimate.

Xown develops financial reporting software for 180 UK/EU businesses with 120 staff. The case states that Henderson Financial Group will accept certification from a UKAS-accredited certification body or a confirmed roadmap within 60 days. Sales must confirm scope, milestone expectations and acceptance in writing.

## Business exposure
| Priority | Risk | Evidence basis | Management consequence |
|---|---|---|---|
| 1 | X-R01: production access misuse; score 20 | Scenario says developers have direct database access without PAM | Financial records may be changed or extracted without adequate restriction |
| 2 | X-R02: unowned security exposure; score 20 | No formal risk assessment | Leadership cannot demonstrate consistent treatment or acceptance |
| 3 | X-R03: recovery failure; score 20 | Backups exist; no DR plan or BIA | Availability and customer commitments cannot be substantiated |
| 4 | X-R04: late detection; score 16 | CloudTrail exists; reviews are irregular | An incident may persist before intervention |
| 5 | X-R05: unassessed suppliers; score 16 | No assurance review of three critical providers | Unexamined dependencies can undermine service and contract commitments |

Scores use the locally defined likelihood × impact method in [the risk register](03-Risk-Register.md). Control existence and effectiveness remain distinct.

## Options considered
| Option | First-year planning envelope | Consequence | Recommendation |
|---|---:|---|---|
| A: documents only, defer operating controls | £15k–£25k | A roadmap could be written, but important risks and audit evidence gaps remain | Reject |
| B: staged remediation and readiness | £120k ceiling | Addresses priority exposure and creates evidence for a later independent assessment | Select |
| C: ISO and a parallel SOC 2 engagement | £160k–£200k | Additional assurance work before a demonstrated buyer need; greater capacity pressure | Defer |

All option prices are analyst assumptions, not market quotes. Option B includes allocated internal effort; the cost of cash purchases is smaller than the total resource envelope. No ROI is inferred by comparing contract value with these estimates.

## Funding and authority requested
| Release | Ceiling | Management release condition |
|---|---:|---|
| Gate 1: days 0–60 | £30,000 | Named CISO sponsor, implementation owners and scope approval |
| Gate 2: days 61–180 | £55,000 | Day-60 roadmap accepted for procurement review; baseline risks and urgent controls reviewed |
| Gate 3: days 181–365 | £35,000 | Controls producing records, independent internal audit commissioned and readiness forecast refreshed |
| **Total** | **£120,000** | No automatic release of later tranches |

CEO owns funding and risk appetite. CISO Mark Hassan owns programme coordination. Head of IT David Osei owns technical delivery. Head of Legal Emma Collins owns legal/contract review. Each owner and allocation requires confirmation; these are scenario roles, not actual appointments.

## Immediate direction
Within 10 working days: inventory privileged identities and restrict unnecessary standing production access; identify service/data owners; open the risk register; confirm the procurement deadline. Escalate unresolved critical access issues to the CEO immediately.

By day 60: present a signed scope, owner-assigned treatment plan, approved budget, draft control selection, and milestone-based customer roadmap. Customer acceptance does not equal certification.

**External message for use only after approval:** “Xown has approved an ISO/IEC 27001:2022 implementation programme for the financial reporting service. We target independent assessment within 12 months, subject to verified readiness and the certification body's schedule. We can provide the approved scope, milestone plan and verified control information.”

## Decision record
| Decision owner | Response | Conditions / date |
|---|---|---|
| CEO: budget, appetite and sponsorship | Pending | To be recorded |
| CISO: ownership and readiness forecast | Pending | To be recorded |
| Head of IT: implementation capacity | Pending | To be recorded |
| Head of Legal: obligations and buyer wording | Pending | To be recorded |

[Supporting plan and cost allocation](05-Remediation-and-Delivery-Plan.md)

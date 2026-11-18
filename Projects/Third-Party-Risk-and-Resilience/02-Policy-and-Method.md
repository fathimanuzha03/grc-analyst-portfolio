# Supplier policy and assessment method
**Policy status:** proposed | **Owner proposed:** Security Lead | **Business:** Northbank Studio simulation

## Scope and case assumptions
Include all third parties receiving production assets or accessing review, edit, archive and delivery workflows. Contracting must cover freelancers and subcontractors, not just SaaS subscriptions.

The fictional business has 58 employees, around 190 annual freelance engagements, 30 clients and 110 productions per year. A campaign launch in 42 days is the scheduling constraint. The six supplier profiles and all detailed responses are constructed; processing/support countries and contract dates are unverified unless expressly stated in an exhibit.

Review assets may contain identifiable people and confidential commercial material. Legal must validate usage rights, controller/processor roles, customer instructions and applicable privacy obligations. A copyright licence and a data-processing agreement solve different questions. No blanket conclusion about all footage, transfer routes or consent requirements is made.

## Criticality and tiers
| Tier | C | Criterion | Proposed review |
|---|---:|---|---|
| 1 — Release-critical | 4 | Core release/recovery dependency or substantial external footage-sharing exposure | Full assessment before release, quarterly condition check, annual reassessment |
| 2 — Significant access | 3 | Downloaded sensitive working assets without being the sole delivery/recovery path | Detailed review before access, annual reassessment |
| 3 — Restricted business data | 2 | Agreements/billing metadata; no production-media access | Proportionate review before use, then every 24 months |
| 4 — Minimal exposure | 1 | No production/system access and minimal business-contact use | Commercial baseline, material-change triggers |

Highest applicable criticality sets the tier. Evidence quality does not lower the business dependency.

## Assessment scoring
Domains and weights: access 25%; sharing/data safeguards 25%; assurance/testing 15%; incident coordination 10%; recovery/exit 20%; downstream chain 5%.

Ratings: 0 unknown or inadequate for the planned scope; 1 unsupported claim/ad hoc approach; 2 partial synthetic evidence with material questions; 3 complete evidence within the synthetic exercise for the domain assessed.

Index = sum(weight × rating ÷ 3), rounded only for display. Strong ≥75; Moderate ≥40 and <75; Weak <40. Model posture P is 3/2/1 respectively; proxy likelihood L=5−P. Risk score=C×L. Low 1–4; Moderate 5–9; High 10–16; Critical 17–25.

These are triage judgements, not calibrated probabilities. Because C≤4 and L≤4, the model cannot generate a Critical score. Hard stops independently govern release. Unknown controls receive no assurance credit but are not represented as proven real-world failures.

## Mandatory release gates
- External production footage requires authenticated, appropriately restricted recipients and enforceable access expiry.
- Critical archive dependence requires representative recovery and usable exports meeting approved business objectives.
- External editors require named access and evidenced protected working arrangements.
- Relevant client permissions, processing terms and lawful transfer arrangements must be established.
- A supplier cannot close a finding merely by submitting an unreviewed policy or certificate.

Use non-sensitive synthetic material for evaluation until the planned live-use scope is authorised.

## Lifecycle
Business owner requests/classifies service → Security reviews scoped evidence → Legal validates instructions/rights/terms → owner records decision → Procurement/IT enforce release → owner monitors incidents and changes → controlled export, revocation and return/deletion on exit.

Managing Director may accept a High operational exception for at most 21 days with compensating controls, named owner and expiry. This cannot waive a hard stop or legal/client obligation. A material service, subprocessor, access or country change triggers reassessment.

Maintain verified notice contacts, contract dates and ownership before operational use; none are invented as actual commitments in this simulation.

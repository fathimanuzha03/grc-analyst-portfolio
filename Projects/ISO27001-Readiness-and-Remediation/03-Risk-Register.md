# Prioritised risk register
**Register:** X-RR01 | **Assessment:** scenario estimates | **Acceptance:** none approved

Scoring and authority are defined in [Scope and method](02-Scope-and-Method.md). “Current” is an initial estimate based on stated safeguards; unknown safeguards receive no assumed credit. It is not a pure no-controls inherent baseline. Target scores depend on successful implementation and evidence.

| ID | Risk event and consequence | Basis | L | I | Score | Rating | Proposed accountable owner | Treatment |
|---|---|---|---:|---:|---:|---|---|---|
| X-R01 | Unrestricted production identities enable extraction or alteration of financial records | S02 | 4 | 5 | 20 | Critical | Head of IT | X-A01 |
| X-R02 | No formal assessment leaves material security exposures unowned | S01 | 4 | 5 | 20 | Critical | CISO | X-A02 |
| X-R03 | Untested recovery leaves Xown unable to restore a critical reporting service | S05 | 4 | 5 | 20 | Critical | Head of IT | X-A03 |
| X-R04 | Irregular log review delays detection and containment | S03 | 4 | 4 | 16 | High | Head of IT | X-A04 |
| X-R05 | Unreviewed suppliers expose confidential data and service dependencies | S06 | 4 | 4 | 16 | High | CISO | X-A05 |
| X-R06 | Informal vulnerability handling leaves exploitable systems exposed | S04 | 3 | 4 | 12 | High | Head of IT | X-A06 |
| X-R07 | Production changes can damage report integrity without demonstrable independent checks | U01 | 3 | 4 | 12 | High | Development Lead | X-A07 |
| X-R08 | Unverified response arrangements delay incident ownership and customer communication | U02 | 3 | 4 | 12 | High | CISO | X-A08 |
| X-R09 | Unrecorded awareness activity prevents targeted follow-up and assurance | S07 | 3 | 3 | 9 | Moderate | HR Lead | X-A09 |
| X-R10 | Unlogged visitors gain access to confidential office information | S08 | 2 | 3 | 6 | Moderate | Office Manager | X-A10 |
| X-R11 | Unverified asset ownership causes incomplete access, patch and retention coverage | U03 | 3 | 3 | 9 | Moderate | Head of IT | X-A11 |
| X-R12 | Unverified privacy terms and data flows lead to processing outside documented requirements | U04 | 3 | 3 | 9 | Moderate | Head of Legal | X-A12 |

## Treatment targets and acceptance
| Risk | Target L × I | Target score / band | Action | Acceptance route after testing |
|---|---|---|---|---|
| X-R01 | 2 × 5 | 10 / High | X-A01 | CEO approval required for any target High residual risk |
| X-R02 | 2 × 4 | 8 / Moderate | X-A02 | CISO acceptance within approved appetite |
| X-R03 | 2 × 5 | 10 / High | X-A03 | CEO approval required for any target High residual risk |
| X-R04 | 2 × 4 | 8 / Moderate | X-A04 | CISO acceptance within approved appetite |
| X-R05 | 2 × 4 | 8 / Moderate | X-A05 | CISO acceptance within approved appetite |
| X-R06 | 2 × 4 | 8 / Moderate | X-A06 | CISO acceptance within approved appetite |
| X-R07 | 2 × 4 | 8 / Moderate | X-A07 | CISO acceptance within approved appetite |
| X-R08 | 2 × 4 | 8 / Moderate | X-A08 | CISO acceptance within approved appetite |
| X-R09 | 2 × 3 | 6 / Moderate | X-A09 | CISO acceptance within approved appetite |
| X-R10 | 1 × 3 | 3 / Low | X-A10 | Service-owner review |
| X-R11 | 2 × 3 | 6 / Moderate | X-A11 | CISO acceptance within approved appetite |
| X-R12 | 2 × 3 | 6 / Moderate | X-A12 | Legal confirms duties; management cannot waive legal requirements |

Every action's status is **Proposed**. Treat the target scores as forecasts, not measured residual risk. Retain the current risk until [closure evidence](06-Evidence-and-Validation.md) is accepted.

**Sensitivity:** X-R07/X-R08/X-R11/X-R12 rely on unknowns. Re-score after discovery; do not present the missing evidence as confirmed control failure. If X-R07 likelihood falls from 3 to 2 after verified change evidence, its score becomes 8 (Moderate), changing its treatment urgency.

## Portfolio heatmap
Numbers are risk IDs, not incident counts. C = Critical; H = High; M = Moderate; L = Low.

| Likelihood ↓ / Impact → | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| 5 | — | — | — | — | — |
| 4 | — | — | — | H: R04, R05 | C: R01, R02, R03 |
| 3 | — | — | M: R09, R11, R12 | H: R06, R07, R08 | — |
| 2 | — | — | M: R10 | — | — |
| 1 | — | — | — | — | — |

**Totals:** Critical 3; High 5; Moderate 4; Low 0. These are management prioritisation counts, not an ISO compliance percentage.

## Review and escalation
CISO reviews Critical/High actions weekly and the full register monthly. Reassess after an incident, significant system/supplier change, failed test or new customer obligation. Each live acceptance record must include risk ID, rationale, compensating controls, accepting authority, expiry and review trigger. Critical issues need immediate containment and CEO attention.

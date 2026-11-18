# Prioritised risk register
**Register:** H-RR01 | **Status:** simulation estimates; no risk acceptance approved

| Risk | Event and consequence | L | I | Score | Band | Proposed owner | Treatment |
|---|---|---:|---:|---:|---|---|---|
| H-R01 | A shared, broadly scoped connector secret permits cross-customer booking access | 4 | 5 | 20 | Critical | Platform Lead | H-A01 |
| H-R02 | Active support accounts belonging to leavers permit unauthorised access | 4 | 4 | 16 | High | IT Lead | H-A02 |
| H-R03 | An untested tenant boundary exposes another operator's appointment records | 3 | 5 | 15 | High | Engineering Lead | H-A03 |
| H-R04 | Backup frequency and restoration delay exceed the enterprise service's recovery needs | 3 | 5 | 15 | High | Operations Lead | H-A04 |
| H-R05 | Unreviewed configuration releases or dependency changes corrupt service behaviour | 3 | 4 | 12 | High | Engineering Lead | H-A05 |
| H-R06 | Short-lived, unowned audit events delay investigation of access misuse | 3 | 4 | 12 | High | Security Lead | H-A06 |
| H-R07 | Undefined risk authority allows exceptions to persist without a management decision | 3 | 4 | 12 | High | Security Lead | H-A07 |
| H-R08 | Booking and contact records are retained beyond a justified business period | 3 | 3 | 9 | Moderate | Privacy Lead | H-A08 |
| H-R09 | A partner connector outage prevents timely depot appointment updates | 3 | 3 | 9 | Moderate | Partnerships Lead | H-A09 |
| H-R10 | Recovery depends on an unavailable primary identity service | 2 | 5 | 10 | High | IT Lead | H-A10 |

**Distribution:** 1 Critical; 7 High; 2 Moderate; 0 Low. H-R01/H-R02/H-R04/H-R05 have displayed exhibit support. Other conditions are defined in the constructed scenario and require further testing.

## Target risk after successful treatment
| Risk | Target L × I | Score / band | Required closure |
|---|---|---|---|
| H-R01 | 2 × 4 | 8 / Moderate | H-A01 evidence reviewed; forecast only |
| H-R02 | 1 × 4 | 4 / Low | H-A02 evidence reviewed; forecast only |
| H-R03 | 2 × 4 | 8 / Moderate | H-A03 evidence reviewed; forecast only |
| H-R04 | 2 × 4 | 8 / Moderate | H-A04 evidence reviewed; forecast only |
| H-R05 | 2 × 3 | 6 / Moderate | H-A05 evidence reviewed; forecast only |
| H-R06 | 2 × 3 | 6 / Moderate | H-A06 evidence reviewed; forecast only |
| H-R07 | 2 × 3 | 6 / Moderate | H-A07 evidence reviewed; forecast only |
| H-R08 | 2 × 3 | 6 / Moderate | H-A08 evidence reviewed; forecast only |
| H-R09 | 2 × 3 | 6 / Moderate | H-A09 evidence reviewed; forecast only |
| H-R10 | 1 × 4 | 4 / Low | H-A10 evidence reviewed; forecast only |

Target scores are not current residual risk and have not been accepted. Review impact as well as likelihood when new evidence changes the business consequence.

## Current prioritisation matrix
| Likelihood ↓ / Impact → | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| 5 | — | — | — | — | — |
| 4 | — | — | — | R02: High | R01: Critical |
| 3 | — | — | R08, R09: Moderate | R05, R06, R07: High | R03, R04: High |
| 2 | — | — | — | — | R10: High |
| 1 | — | — | — | — | — |

## Review rules
Security Lead reviews urgent treatments weekly and the full register monthly. Reassess after a connector, customer boundary, service commitment or identity dependency changes. A failed test keeps the associated risk open.

Example sensitivity: verified tenant isolation could reduce H-R03 likelihood from 3 to 2, moving score 15 to 10. It would still be High and require management treatment/acceptance under the proposed method.

[Assessment method](02-Scope-and-Method.md) · [Remediation owners and tests](05-Remediation-and-Delivery-Plan.md)

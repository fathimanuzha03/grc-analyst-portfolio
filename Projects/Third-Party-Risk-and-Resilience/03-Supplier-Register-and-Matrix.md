# Supplier register and prioritisation matrix
**Population:** eight fictional suppliers | **Assessment date:** 18 November 2026 | **Live approval status:** none

First four services derive from the reference; additional services, domain scores and detail are synthetic. Countries are not inferred from company names or a certificate. Unknown support/subprocessor locations remain open diligence items.

| ID / supplier | Service and data | Criticality / tier | Countries / access | Proposed business owner |
|---|---|---|---|---|
| V01: CloudMatrix Analytics | US AI analytics; Client personal and confidential commercial data | 4 / Tier 1 | US processing; other access locations unverified | Analytics Director |
| V02: SecureVault Ltd. | Encrypted production backup; Production backup datasets; key custody to confirm | 4 / Tier 1 | UK storage stated; support/onward locations unverified | Head of IT |
| V03: TalentSphere HR | HR SaaS for 400 staff; Employee salary, performance and identifying data | 3 / Tier 2 | Not supplied; obtain processing/access map | HR Director |
| V04: TechSupport Pro | Existing remote support; Privileged access to client environments | 4 / Tier 1 | Not supplied; roster/access locations unverified | Support Director |
| V05: IdentityHarbor (fictional) | Corporate SSO / identity; Work identities and authentication metadata | 4 / Tier 1 | UK tenant assumed; support routes unverified | Head of IT |
| V06: CaseDesk (fictional) | Support ticketing; Limited business contacts and ticket details | 2 / Tier 3 | UK processing assumed; confirm | Support Director |
| V07: LedgerPay (fictional) | Payroll calculation; Employee pay and statutory payroll identifiers | 3 / Tier 2 | UK processing assumed; confirm | Finance Director |
| V08: PaperTrail (fictional) | Office supplies; Ordering contacts only; no customer/system access | 1 / Tier 4 | UK trading assumed; confirm | Office Manager |

## Assessment and decision register
| ID | Domain ratings: access/data/assurance/incident/recovery/chain | Assurance index | Posture / proxy L | Score / band | Proposed decision / finding link |
|---|---|---:|---|---|---|
| V01 | 2/0/2/2/2/1 | 50.0 | Moderate / 3 | 12 / High | Hold client-data onboarding; F01–F03 |
| V02 | 3/3/3/1/2/2 | 81.7 | Strong / 2 | 8 / Moderate | Conditional recommendation; no activation before gates close; F04–F06 |
| V03 | 2/0/1/1/1/1 | 33.3 | Weak / 4 | 12 / High | Hold live employee-data migration; F07–F09 |
| V04 | 1/1/0/1/1/0 | 23.3 | Weak / 4 | 16 / High | Restrict immediately; time-limited continuity decision; F10–F12 |
| V05 | 2/2/2/2/2/1 | 63.3 | Moderate / 3 | 12 / High | No privilege expansion before dependency review; F13 |
| V06 | 2/2/1/2/1/2 | 55.0 | Moderate / 3 | 6 / Moderate | Standard review with data-content restrictions; F14 |
| V07 | 2/2/2/1/2/2 | 61.7 | Moderate / 3 | 9 / Moderate | Conditional review; resolve incident terms; F15 |
| V08 | 2/2/1/1/1/1 | 46.7 | Moderate / 3 | 3 / Low | Proportionate commercial review; None identified in this limited simulation |

| ID | Last assessment | Next due / trigger | Contract expiry / DPA / audit rights | Current evidence confidence |
|---|---|---|---|---|
| V01 | New service; no real assessment | Before any client data | All to verify with Legal | Synthetic responses; transfer gap described |
| V02 | New service; no real assessment | Before activation; quarterly Tier 1 review after release | Incident terms described; expiry/DPA/audit rights unverified | Certificate is a scenario claim, not an inspected certificate |
| V03 | New service; no real assessment | Before migration | Expiry/DPA/audit rights unverified | Self-assessment; encryption unconfirmed; test age described |
| V04 | Three years ago in case; date unspecified | Immediate reassessment; 30-day continuity decision | Expiry/DPA/audit rights unverified | Low confidence due to stale oversight |
| V05 | Synthetic initial profile only | Before privilege expansion; annual full review | All unverified | Provisional; identity dependency needs challenge |
| V06 | Synthetic initial profile only | Before activation, then within 24 months | All unverified | Provisional; limited-content scope assumed |
| V07 | Synthetic initial profile only | Before activation, then annual | All unverified | Provisional; payroll dependency requires business validation |
| V08 | Synthetic initial profile only | Commercial review, then within 36 months | Applicable terms/expiry to verify; processor terms depend on role | Provisional; ordering contacts only |

No supplier contact details have been fabricated. Procurement must obtain verified business contacts, notice addresses and contract dates before operationalising the register.

## Criticality versus security posture
Labels show the model's calculated risk band; policy gates can still block release. [Scoring definitions](02-Policy-and-Method.md)

| Criticality ↓ / Posture → | Weak | Moderate | Strong |
|---|---|---|---|
| 4 — Critical dependency | High: V04 | High: V01, V05 | Moderate: V02 |
| 3 — Significant data | High: V03 | Moderate: V07 | — |
| 2 — Limited scope | — | Moderate: V06 | — |
| 1 — Ordering contacts | — | Low: V08 | — |

**Priority:** V04 has the highest model score (16) and existing privileged access, so containment precedes new procurement work. V01 and V03 have live-data hard stops despite being new services. V02's stronger posture does not override notification and restore gates. V05 concentration deserves early attention because identity failure can affect every downstream service.

These are current simulated assessment scores, not proven residual risks. Re-score only after evidence and exceptions are reviewed. Risk targets and closure conditions appear in [the tracker](05-Remediation-and-Decision-Tracker.md).

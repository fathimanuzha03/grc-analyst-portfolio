# Synthetic evidence, primary sources and review
**Project:** Northbank Studio simulation | **Version:** 2.0 | **Date:** 18 November 2026

## E-N01 — review-link sample
| Asset | Recipient authentication | Expiry | Download |
|---|---|---|---|
| A01 | Named reviewer | 24 hours | No |
| A02 | None; bearer link | None | Yes |
| A03 | Named reviewer | 72 hours | No |
| A04 | None; bearer link | None | Yes |
| A05 | Named reviewer | 48 hours | Yes |

Calculated result: **2/5 links lack both authentication and expiry**. Download rights require business-purpose review; a permitted download is not automatically a finding. No actual URLs or footage are present.

## E-N02 — working-copy reconciliation
Twelve working-copy IDs W01–W12 are defined. Return/deletion confirmations exist for W01–W10. W11 and W12 have no confirmation. Result: **10/12 evidenced; 2/12 unresolved**. A missing record is not proof that the copy still exists, but prevents verified closure.

## E-N03 — retrieval calculation
Disruption: 18 November 2026, 09:00 UTC. Latest dataset: 17 November, 10:00 UTC. Usable recovery: 18 November, 20:00 UTC.
- Elapsed recovery: 11h versus 8h RTO: fail by 3h.
- Data age: 23h versus 24h RPO: pass with 1h margin.
- No actual restoration occurred.

## Score verification
Domain weights 25/25/15/10/20/5 sum to 100. N-V01 calculation:
(25×1 + 25×0 + 15×2 + 10×2 + 20×2 + 5×2) ÷ 3 = **41.7** after display rounding.
Moderate posture → proxy likelihood 3; criticality 4 → **12, High**.

Six suppliers have unique IDs and six ratings. The first three full response assessments score 41.7, 70.0 and 23.3. Counts: 4 High, 1 Moderate, 1 Low. Twelve findings cover the six suppliers. Budget: £13k staff + £17k reserve = £30k.

All profiles, response summaries, record IDs and budgets are constructed for this portfolio. No real third-party company, certificate, report, contract or supplier statement is represented.

## Primary references
| Reference | Use / boundary |
|---|---|
| [NCSC supply-chain principles](https://www.ncsc.gov.uk/collection/supply-chain/guidance/12-principles) | Lifecycle oversight; local tiers/weights are project choices |
| [ICO processor contract guidance](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/contracts-and-liabilities-between-controllers-and-processors-multi/what-needs-to-be-included-in-the-contract/) | Role-specific contractual review; validate current guidance and applicability |
| [ICO transfer guide](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/international-transfers/a-brief-guide-to-international-transfers/) | Flow-by-flow transfer analysis before operational use |
| [ICO breach guide](https://ico.org.uk/for-organisations/report-a-breach/personal-data-breach/personal-data-breaches-a-guide/) | Role-dependent incident notification duties |
| [ISO/IEC 27001 overview](https://www.iso.org/standard/27001) | Supplier/control context; no full conformity assessment or standard reproduction |

References were checked during preparation on 18 November 2026 and should be revalidated before operational use. This release replaces an earlier portfolio scenario; normal Git history is retained.

## Review and document control
- [ ] Business owners validate asset criticality and service objectives.
- [ ] Security challenges access/configuration evidence and tests hard stops.
- [ ] Legal confirms rights, processing roles, agreements and locations.
- [ ] Finance confirms quotes, staff availability and migration exclusions.
- [ ] Decision owners record scope, conditions, expiry and sign-off.
- [ ] Future exercises record actual participants, observations and retests.

Version 2.0: Northbank scenario and synthetic evidence prepared 18 November 2026. Simulation arithmetic and links checked. No live assurance, supplier approval or realised business outcome is claimed. Reviewers' decisions are pending, not pre-filled.

[Return to project](README.md)

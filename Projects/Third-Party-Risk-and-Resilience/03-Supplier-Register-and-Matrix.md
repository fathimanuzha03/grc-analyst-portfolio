# Supplier register and risk matrix
**Population:** six fictional suppliers | **Assessment:** synthetic profiles, 18 November 2026

| ID / supplier | Service | Data/access | C / tier | Proposed owner |
|---|---|---|---|---|
| N-V01: FrameRelay | Review and approval SaaS | Client footage, reviewer contacts and release notes | 4 / Tier 1 | Production Director |
| N-V02: ColdHarbor Archive | Master-asset archive and retrieval | Finished masters, source footage and project metadata | 4 / Tier 1 | Head of Post-production |
| N-V03: Cutline Collective | Freelance post-production partner | Downloaded footage and project working copies | 3 / Tier 2 | Post-production Producer |
| N-V04: ScreenBridge Delivery | Client delivery platform | Final assets, delivery permissions and access events | 4 / Tier 1 | Delivery Manager |
| N-V05: SignCanvas | Contract execution | Signatory contacts, agreements and audit events | 2 / Tier 3 | Commercial Manager |
| N-V06: LedgerLane | Project invoicing | Client billing contacts and invoice details | 2 / Tier 3 | Finance Manager |

## Assessment and decision
Domain order is access / sharing-data / assurance / incident / recovery / chain.

| ID | Ratings 0–3 | Index | Posture | Proxy L | Score / band | Proposed decision |
|---|---|---:|---|---:|---|---|
| N-V01 | 1/0/2/2/2/2 | 41.7 | Moderate | 3 | 12 / High | Hold external sharing until authenticated, expiring review access is enforced |
| N-V02 | 3/3/2/2/0/2 | 70.0 | Moderate | 3 | 12 / High | Hold release-critical archive dependency until recovery and key tests pass |
| N-V03 | 0/1/1/1/1/0 | 23.3 | Weak | 4 | 12 / High | No new client footage until named access and managed working arrangements are evidenced |
| N-V04 | 2/2/2/2/2/2 | 66.7 | Moderate | 3 | 12 / High | Conditional scope; demonstrate alternate delivery and concentration review |
| N-V05 | 3/2/2/2/2/2 | 75.0 | Strong | 2 | 4 / Low | Proportionate review; confirm evidence retention/export |
| N-V06 | 2/2/1/2/2/2 | 61.7 | Moderate | 3 | 6 / Moderate | Proportionate review; validate data minimisation and retention |

**Distribution:** 4 High, 1 Moderate, 1 Low. No score is a release decision.

## Oversight records
| Suppliers | Last review | Contract dates / countries / actual contacts | Next required review |
|---|---|---|---|
| N-V01–N-V03 | This simulation only; no real diligence | Not obtained; Legal/Procurement must verify | Before new live use and after closure evidence |
| N-V04 | Synthetic initial profile; no full questionnaire completed | Not obtained | Before expanding delivery dependency |
| N-V05–N-V06 | Synthetic initial profiles | Not obtained | Before release of proposed restricted scope |

No signed DPA, audited report, supplier-committed deadline or commercial approval is claimed.

## Criticality versus posture
| C ↓ / Posture → | Weak | Moderate | Strong |
|---|---|---|---|
| 4 — Release-critical | — | High: N-V01, N-V02, N-V04 | — |
| 3 — Significant access | High: N-V03 | — | — |
| 2 — Restricted business data | — | Moderate: N-V06 | Low: N-V05 |
| 1 — Minimal | — | — | — |

**Prioritisation:** restrict N-V01 sharing and N-V03 asset transfers first; recovery failure at N-V02 must be resolved before relying on it for a release-critical master. N-V04 concentration and alternate delivery need assessment before the campaign launch. N-V05's Low model score does not eliminate retention and evidence requirements.

The first three profiles have detailed response summaries. The other three remain initial assessments. [Completed assessments](04-Supplier-Assessments.md) · [Closure tracker](05-Remediation-and-Decision-Tracker.md)

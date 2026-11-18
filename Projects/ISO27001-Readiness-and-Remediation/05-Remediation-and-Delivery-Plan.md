# Remediation and staged delivery
**Day 0:** programme approval | **All owners, objectives and prices:** proposed simulation assumptions

## Action backlog
| Action | Outcome | Owner | Due | Evidence / pass condition |
|---|---|---|---:|---|
| H-A01 | Separate connector credentials, limit scope and rotate shared material | Platform Lead | Day 10 | T01: unique route credentials, least scope and revoked old secret |
| H-A02 | Reconcile leavers and support access; remove unjustified rights | IT Lead | Day 10 | T02: all leavers disabled or specifically authorised and time-limited |
| H-A03 | Test tenant-boundary and configuration controls, including negative cases | Engineering Lead | Day 45 | T03: no unauthorised cross-tenant access; independent reviewer checks failures |
| H-A04 | Agree BIA objectives; revise backup schedule and demonstrate full service restore | Operations Lead | Day 60 | T04: measured RTO≤6h and RPO≤2h, subject to business approval |
| H-A05 | Align configuration/application approvals, dependency coverage and rollback | Engineering Lead | Day 45 | T05: all sampled changes approved, tested and reversible |
| H-A06 | Define audit sources, investigation-driven retention and triage ownership | Security Lead | Day 30 | T06: authorised test event traced from generation to escalation |
| H-A07 | Approve risk method, scope, policy, owners and exception authority | Security Lead | Day 30 | T07: consistent approved records; no unowned material risk |
| H-A08 | Validate processing purpose, customer instructions and deletion schedule | Privacy Lead | Day 45 | T08: approved rules and representative deletion/retention test |
| H-A09 | Map partner dependencies, service responsibilities and outage escalation | Partnerships Lead | Day 60 | T09: contracts/contacts mapped and connector failure exercised |
| H-A10 | Establish protected emergency access independent of primary identity | IT Lead | Day 30 | T10: authorised recovery access tested without normal SSO |

Close actions only after the required evidence is reviewed. Targets do not establish successful implementation.

## Resource reconciliation
| Workstream | Allocated staff effort | Incremental reserve | Total |
|---|---:|---:|---:|
| Identity and connector isolation | £16,000 | £8,000 | £24,000 |
| Secure integrations and release process | £12,000 | £6,000 | £18,000 |
| Recovery and operational evidence | £8,000 | £8,000 | £16,000 |
| Privacy and governance | £7,000 | £5,000 | £12,000 |
| Independent assessment reserve | £0 | £8,000 | £8,000 |
| Contingency; management release | £3,000 | £3,000 | £6,000 |
| **Total** | **£46,000** | **£38,000** | **£84,000** |

This is the same envelope as the £20k/£36k/£28k stage releases, not additional funding. Contingency includes reserved staff capacity. VAT, permanent hiring and major platform replacement are excluded. Obtain quotes and confirm staff availability.

## Milestones
| Period | Milestone | Gate |
|---|---|---|
| Days 0–30 | Contain access exposure, approve scope/risk authority, test emergency access | Managing Director authorises next tranche |
| Days 31–60 | Tenant/configuration controls and recovery retest | Rollout scope reflects demonstrated service capability |
| Days 61–90 | Customer roadmap, complete control-selection plan and recurring evidence | Prospect requirements and remaining exceptions explicitly acknowledged |
| Months 4–6 | Sustain operations; complete full SoA and ISMS records | Internal evidence review and independent internal audit readiness |
| Months 7–9 | Independent internal audit, correction and management review | Decide whether and when to engage a certification body |

No certificate, audit booking or customer acceptance is assumed.

## Accountability
Managing Director is accountable for funding and material acceptance. Security Lead is accountable for risk coordination. Named action owners are accountable for delivery in their remit. Privacy Lead advises on obligations and does not grant unlawful exceptions. An independent assessor tests the programme rather than reviewing their own implementation work.

## Management dashboard
- Critical-risk containment: H-R01 has an authorised owner and dated action from day 1.
- Leaver reconciliation: 100% of departed identities reviewed; unjustified access removed.
- Connector scope: all four routes use approved scope and attributable credentials.
- Change evidence: all production release types subject to the same risk-based approval rules.
- Recovery: actual retest results compared with approved objectives.
- Exceptions: 100% have authority, conditions and expiry.

Primary schedule threats are engineering availability, tenant-test failures and unproven recovery. Preserve containment, narrow commitments and re-cost specific changes when a gate fails; do not hide slippage by changing the baseline silently.

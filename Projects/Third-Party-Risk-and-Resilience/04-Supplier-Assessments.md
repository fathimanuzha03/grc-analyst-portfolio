# Completed simulation supplier assessments
**Assessment owner proposed:** GRC Analyst; CISO challenges findings; business owner decides within policy.

The tables are completed analytical assessments of explicitly synthetic responses. S-* denotes the source scenario; D-* denotes constructed response summaries below. No vendor questionnaire was actually sent and no real certificate, SOC report, architecture export or contract was inspected. Rating 3 means complete support within the simulated exhibit, not independent verification in reality.

## Common questionnaire
Q1: Can privileged/user access be attributed and controlled? Q2: Are data use, location, protection and transfer requirements satisfied? Q3: Is assurance/testing scoped, current enough for the risk and reviewed for exceptions? Q4: Can incidents be escalated and investigated promptly? Q5: Can the customer's service/data be recovered and exited? Q6: Are downstream providers and changes controlled?

Scores use [the policy weights and method](02-Policy-and-Method.md). Detailed response summaries below are the synthetic exhibits; the IDs are not links to undisclosed real documents.

## V01 — CloudMatrix Analytics
| Question | Domain / weight | Rating 0–3 | Synthetic response and evidence interpretation | Basis | Finding |
|---|---|---:|---|---|---|
| Q1 | Access; 20% | 2 | MFA/role controls described; privileged support sample and scope incomplete | D-CM01: synthetic access summary | F03 |
| Q2 | Data use/transfer; 20% | 0 | US-only processing; no applicable transfer terms established; customer authorisation to confirm | S-CM plus D-CM02: synthetic processing schedule | F01, F02 |
| Q3 | Assurance/testing; 20% | 2 | SOC 2 Type 2 report claimed; no actual report inspected; synthetic summary lacks customer-responsibility review | S-CM plus D-CM03: synthetic assurance summary | F03 |
| Q4 | Incident handling; 15% | 2 | Contacts and escalation path supplied in the simulation; exercise coverage incomplete | D-CM04: synthetic incident summary | F03 |
| Q5 | Recovery/exit; 15% | 2 | Export and recovery procedures described; DataBridge recovery not demonstrated | D-CM05: synthetic exit summary | F02 |
| Q6 | Subprocessor chain; 10% | 1 | Subprocessor list incomplete; onward support access locations unconfirmed | D-CM06: synthetic chain summary | F03 |

**Assurance index:** 50.0 / 100 → Moderate posture. Criticality 4 × proxy likelihood 3 = **12, High**.

**Recommendation:** Hold client-data onboarding. A report claim does not resolve lawful transfer, instructions or AI-use limits. Legal must validate the current transfer route for each relevant flow; absence of SCCs alone is not proof that no alternative route is available. Synthetic-data evaluation may proceed within an approved scope.

**Three principal findings:** F01 transfer route/terms; F02 AI-use and data minimisation; F03 onward-chain and assurance scope.

## V02 — SecureVault Ltd.
| Question | Domain / weight | Rating 0–3 | Synthetic response and evidence interpretation | Basis | Finding |
|---|---|---:|---|---|---|
| Q1 | Access; 20% | 3 | Complete synthetic operator roster shows approval and scoped administration | D-SV01: synthetic access evidence | F05 |
| Q2 | Data safeguards; 20% | 3 | Synthetic encryption design covers transport, storage and key separation; contractual key-accountability schedule still needs execution | D-SV02: synthetic design exhibit | F05 |
| Q3 | Assurance/testing; 20% | 3 | Case claims ISO certification; synthetic scope/review summary is complete for the service being assessed | S-SV plus D-SV03: synthetic review summary | F04 |
| Q4 | Incident handling; 15% | 1 | Notification commitment allows 72 hours; only a policy assertion supports escalation | S-SV | F04 |
| Q5 | Recovery/exit; 15% | 2 | Vendor restore procedure described; representative DataBridge restore and deletion flow not tested | D-SV05: synthetic recovery summary | F06 |
| Q6 | Subprocessor chain; 10% | 2 | List supplied in simulation; onward change/notice terms incomplete | D-SV06: synthetic chain summary | F05 |

**Assurance index:** 81.7 / 100 → Strong posture. Criticality 4 × proxy likelihood 2 = **8, Moderate**.

**Recommendation:** Conditional recommendation; no activation until the incident terms, responsibility schedule and representative restore meet the gates. Technical design evidence and contractual authority are separate: domain strength does not imply executed terms.

**Three principal findings:** F04 incident notification; F05 key/chain responsibility schedule; F06 customer-representative restore and exit.

## V03 — TalentSphere HR
| Question | Domain / weight | Rating 0–3 | Synthetic response and evidence interpretation | Basis | Finding |
|---|---|---:|---|---|---|
| Q1 | Access; 20% | 2 | Role controls and admin MFA described; leaver evidence incomplete | D-TS01: synthetic access summary | F09 |
| Q2 | Data safeguards; 20% | 0 | Storage encryption/key arrangements unconfirmed; locations not mapped | S-TS | F07 |
| Q3 | Assurance/testing; 20% | 1 | Self-assessment only; most recent penetration test stated as 18 months old | S-TS | F08 |
| Q4 | Incident handling; 15% | 1 | Notification/cooperation described without executed terms or exercise evidence | D-TS04: synthetic summary | F09 |
| Q5 | Recovery/exit; 15% | 1 | Backup claimed; HR export/restore not evidenced | D-TS05: synthetic summary | F09 |
| Q6 | Subprocessor chain; 10% | 1 | Unverified list; no complete processing-location schedule | D-TS06: synthetic summary | F09 |

**Assurance index:** 33.3 / 100 → Weak posture. Criticality 3 × proxy likelihood 4 = **12, High**.

**Recommendation:** Hold live employee-data migration. Require adequate safeguards and fresh risk-appropriate test evidence; lack of ISO/SOC certification alone is not a rejection reason. Test age is a review trigger, not a universal statutory expiration period.

**Three principal findings:** F07 encryption evidence; F08 current security testing and remediation; F09 processing terms, locations and operational support.

## Decision traceability
| Assessment | Recommendation | Related actions | Release authority |
|---|---|---|---|
| V01 | Hold live client data | F01–F03 | Analytics Director after CISO/Legal clearance |
| V02 | Conditional; activation blocked until gates close | F04–F06 | IT owner after CISO/Legal and recovery review |
| V03 | Hold live employee migration | F07–F09 | HR Director after CISO/Legal clearance |

V04–V08 have initial register profiles and actions; they are not misrepresented as fully completed questionnaires. TechSupport Pro requires urgent full reassessment. The four added provider names are invented and describe no real company's security posture.

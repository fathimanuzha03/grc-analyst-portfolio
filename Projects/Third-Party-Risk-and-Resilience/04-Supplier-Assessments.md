# Completed simulation supplier assessments
All response summaries below are deliberately constructed for this portfolio. They are the supporting exhibits, not summaries of confidential supplier documents. No actual questionnaires, certificates or audit reports were received.

Domain ratings are evidence judgements for the proposed use. [Method and weights](02-Policy-and-Method.md)

## N-V01 — FrameRelay
| Domain | Weight | Rating 0–3 | Constructed response / interpretation |
|---|---|---:|---|
| Access | 25% | 1 | Projects use link-based access; reviewer identity cannot always be established. |
| Sharing/data safeguards | 25% | 0 | Two of five displayed review links permit unauthenticated access with no expiry; planned release scope is inadequate. |
| Assurance/testing | 15% | 2 | A scoped test summary is constructed for this exercise; tenant sharing exceptions remain. |
| Incident coordination | 10% | 2 | Named incident route is described; response exercise and contact failover not complete. |
| Recovery/exit | 20% | 2 | Project export is described; permission-preserving re-import has not been demonstrated. |
| Downstream chain | 5% | 2 | A downstream list is described; access-country and change-notice validation remain open. |

**Calculated index:** 41.7 / 100. Risk: criticality 4 × proxy likelihood 3 = **12, High**.

**Decision proposed:** Hold external sharing until authenticated, expiring review access is enforced.

**Principal findings:** N-F01 authenticated access; N-F02 expiry/download permissions; N-F03 permitted use, locations and client requirements.

## N-V02 — ColdHarbor Archive
| Domain | Weight | Rating 0–3 | Constructed response / interpretation |
|---|---|---:|---|
| Access | 25% | 3 | Complete synthetic roster shows scoped archive administration and approval. |
| Sharing/data safeguards | 25% | 3 | Complete synthetic design separates asset access and protected key administration. |
| Assurance/testing | 15% | 2 | Integrity-check procedure supplied in the simulation; independent coverage remains incomplete. |
| Incident coordination | 10% | 2 | Incident contacts and escalation described; out-of-hours exercise missing. |
| Recovery/exit | 20% | 0 | Retrieval exercise misses the proposed 8-hour RTO; no positive score credited for intended live use. |
| Downstream chain | 5% | 2 | Storage and support chain described; change-control coverage remains partial. |

**Calculated index:** 70.0 / 100. Risk: criticality 4 × proxy likelihood 3 = **12, High**.

**Decision proposed:** Hold release-critical archive dependency until recovery and key tests pass.

**Principal findings:** N-F04 retrieval performance; N-F05 independent key recovery; N-F06 usable export/exit capacity.

## N-V03 — Cutline Collective
| Domain | Weight | Rating 0–3 | Constructed response / interpretation |
|---|---|---:|---|
| Access | 25% | 0 | Editors share a project login; attributable access is not established. |
| Sharing/data safeguards | 25% | 1 | Working copies may be downloaded; protected workspace and client restrictions are not evidenced. |
| Assurance/testing | 15% | 1 | Self-attestation only; no suitable endpoint or review evidence in the constructed response. |
| Incident coordination | 10% | 1 | One contact is named; backup coverage and exercised response are absent. |
| Recovery/exit | 20% | 1 | Return/deletion is asserted; two of twelve working-copy deletion confirmations are missing. |
| Downstream chain | 5% | 0 | The studio has not identified onward freelance access in the supplied synthetic profile. |

**Calculated index:** 23.3 / 100. Risk: criticality 3 × proxy likelihood 4 = **12, High**.

**Decision proposed:** No new client footage until named access and managed working arrangements are evidenced.

**Principal findings:** N-F07 shared accounts; N-F08 protected editing environment; N-F09 return/deletion evidence.

## Evidence challenge
FrameRelay's score does not compensate for unsafe sharing defaults. ColdHarbor's access and data-protection strengths do not offset failed restoration timing; technical key segregation still requires an independent recovery test. Cutline's claims do not establish who accessed or retained footage.

N-V04–N-V06 have initial register profiles only, not full completed questionnaires. Their proposed follow-up findings remain proportionate to service scope.

## Release authority
Security recommends; Legal confirms rights/instructions and applicable terms; business owner records the service decision; administrators release only the permitted scope. Do not close a finding or change a score merely because a supplier promises a fix.

[Action and closure requirements](05-Remediation-and-Decision-Tracker.md)

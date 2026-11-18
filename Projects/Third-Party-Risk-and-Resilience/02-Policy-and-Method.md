# Supplier risk policy and assessment method
**Policy owner:** CISO | **Legal partner:** Head of Legal | **Review:** annual and on material change | **Status:** proposed

## Scope and operating rules
Applies to suppliers, subcontractors and integrations that handle business data or access systems. Include existing providers, trials and AI services. Procurement must link every relevant contract to a business owner, data/access inventory, assessment and decision.

Before live data or access: classify criticality, establish processing roles, identify locations/subprocessors, assess controls, close mandatory gates and record the decision. Reassess when services, data, ownership, incidents or subprocessor chains change.

## Tiering
| Tier | Criticality C | Criteria / required due diligence | Review frequency proposed |
|---|---:|---|---|
| 1 — Critical | 4 | Privileged client access, core identity, irreplaceable recovery dependency or core sensitive-data processing | Full assessment, contract/recovery review; quarterly status check and at least annual full review |
| 2 — High | 3 | Significant personal/confidential data but less direct critical-system dependency | Detailed questionnaire, evidence/terms and annual review |
| 3 — Standard | 2 | Limited business data and restricted system impact | Proportionate check, security terms and review every 24 months |
| 4 — Low | 1 | Ordering contacts only; no customer data or system access | Commercial baseline and review every 36 months, plus event triggers |

SecureVault is Tier 1 here because production recovery is treated as a critical dependency, despite the reference's Tier 2 example. This is a documented analyst override requiring the service owner to validate criticality. Encrypted storage is still processing; assess key custody, recoverability and instructions. For every supplier the highest applicable criterion sets the tier; a good certificate does not lower inherent service criticality.

## Response/evidence scoring
Six domains, with weights: access 20%, data handling 20%, assurance/testing 20%, incident response 15%, recovery/exit 15%, subprocessor chain 10%.

Rate each domain:
- 0: missing, unknown, or fails a required safeguard.
- 1: assertion/ad hoc arrangements, no adequate support.
- 2: partial documented case evidence; operating coverage or exceptions remain.
- 3: complete supporting evidence within the synthetic case for the assessed domain.

Assurance index = sum(weight × domain rating ÷ 3), rounded to one decimal only for display. Strong posture: ≥75; Moderate: ≥40 and <75; Weak: <40. Unknown controls receive no confidence credit but are not declared absent in reality.

For prioritisation only: P = 3 Strong, 2 Moderate, 1 Weak; proxy likelihood L = 5 − P. Score = criticality C × L. Bands: 1–4 Low, 5–9 Moderate, 10–16 High, 17–25 Critical. This is a local triage model, not a calibrated incident-probability estimate. With C≤4 and L≤4, its maximum is 16; retain hard-stop rules instead of inventing Critical scores.

## Mandatory gates override score
No live onboarding/expanded access when:
1. Required processing agreement/instructions or controller authorisation are missing.
2. A restricted transfer lacks a validated legal route.
3. Privileged access cannot be attributed, restricted and monitored.
4. Required encryption/key safeguards for the planned sensitive dataset are unverified.
5. A critical recovery dependency has no evidenced recovery/exit arrangements.

A score identifies review priority; it is not an approval. Legal/security gates must be closed, not financially “accepted away.” A supplier without ISO/SOC evidence can provide other adequate evidence. A claim of SOC 2 is a report claim, not certification; inspect scope, period, opinion, exceptions and customer responsibilities.

## Lifecycle and policy ownership
| Step | Responsible role | Record |
|---|---|---|
| Request and criticality | Business owner | Service, data, access and recovery needs |
| Diligence and security challenge | GRC with CISO | Scored responses, provenance, evidence gaps |
| Contract and transfer review | Legal | Applicable terms, authorisation and transfer assessment |
| Commercial release | Procurement | Approved decision with conditions |
| Technical activation | IT / service owner | Gate evidence and configured scope |
| Monitoring and reassessment | GRC / business owner | Review dates, incidents and material changes |
| Exit | Business owner / IT / Legal | Export, access removal, deletion/retention and dependency checks |

CISO owns security policy. Business owners accept operational exposure within approved delegation; executive sponsor accepts High-risk exceptions for at most 30 days, with one explicitly reviewed renewal. Legal duties and client instructions remain binding. Policy exceptions must be logged, not implied through overdue reviews.

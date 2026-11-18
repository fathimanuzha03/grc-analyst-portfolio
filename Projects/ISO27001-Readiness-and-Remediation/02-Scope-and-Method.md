# Scope and assessment method
**Assessment reference:** X-AS01 | **Basis date:** 18 November 2026 | **Status:** Proposed scope

## Business and system boundary
The case describes a Birmingham financial-reporting SaaS provider with 120 employees: 45 development, 20 operations/support, 30 sales/account management and 25 finance/HR/administration. It serves 180 UK/EU businesses. Financial reports, shareholder information and payroll can include personal and commercially confidential data; not all financial information is automatically special-category personal data.

**Proposed ISMS scope:** development, delivery, operation and support of the financial-reporting SaaS service, including production and supporting cloud accounts, source control, deployment pipelines, corporate identity, endpoints used to administer the service, office access, relevant staff/contractors and supplier interfaces.

The reference names AWS, Salesforce and Zendesk as critical suppliers. Their exact roles, regions, contracts and integrations require discovery. This assessment assumes no unmentioned architecture, redundancy, data residency or security product.

No exclusion is approved. Outsourced facilities remain relevant dependencies even where a provider operates physical safeguards. Xown must establish contractual coverage and its own responsibilities. Complete the asset/data-flow inventory before considering exclusions.

## Parties and obligations
| Party / owner | Requirement or concern | Scope decision |
|---|---|---|
| Henderson procurement / Sales | Certification or accepted roadmap within 60 days, per case | Confirm service boundary, milestones and evidence acceptance |
| Existing customers / service owners | Confidentiality, accuracy, availability and contract commitments | Inventory customer terms and processing instructions |
| CEO / CISO | Funded risk treatment, accountable programme | Set risk appetite and authority |
| Legal / HR | Personal data, employment and processor obligations | Confirm controller/processor roles by purpose |
| AWS and other suppliers / IT | Shared responsibilities and dependency assurance | Map service-specific responsibilities; inspect current evidence |
| Certification body | Assessment against agreed scope and applicable standard | Verify accreditation and engagement; no booking is claimed |

UK GDPR and the Data Protection Act 2018, as amended, require role-specific review. EU GDPR scope depends on establishment and EU-directed processing, not nationality alone. Transfer mechanisms, representative/DPO needs and other sector requirements remain Legal questions. Financial services customers do not automatically make Xown FCA-regulated.

## What was assessed
A desk analysis of the supplied scenario, plus four checks over synthetic exhibits in [Evidence and validation](06-Evidence-and-Validation.md). No real system, employee record, supplier report or confidential client material was accessed.

Evidence labels:
- **S:** a statement in the reference scenario, not independently verified.
- **D:** data deliberately constructed for this portfolio.
- **U:** unknown; evidence request outstanding.
- **T:** proposed future acceptance test, not a completed live test.

A missing record is an assurance gap. It does not prove an incident or the complete absence of a technical control.

## Risk model
Likelihood estimates concern the next 12 months. They are ordinal judgement bands:
1 Rare: exceptional prerequisites; 2 Unlikely: plausible with substantial constraints; 3 Possible: credible path with some constraints; 4 Likely: repeated exposure with limited barriers; 5 Almost certain: frequent attempts and very weak barriers.

Impact is the highest credible consequence across service interruption, financial integrity/loss, personal-data harm and customer obligations:
1 Negligible: locally reversible; 2 Minor: limited rework, no material customer interruption; 3 Material: service/customer impact requiring management response; 4 Major: substantial disruption, serious confidentiality loss or major contractual exposure; 5 Severe: prolonged critical-service loss or systemic compromise of financial records.

These are local definitions, not ISO/NIST-mandated scores or money-loss models. Likelihood × impact prioritises discussion, not mathematical expected loss.

**Bands:** 1–4 Low; 5–9 Moderate; 10–16 High; 17–25 Critical.
- Critical: CEO decision; no routine acceptance; containment first.
- High: CEO approval of any time-limited acceptance, with CISO challenge.
- Moderate: CISO may accept up to 90 days within approved appetite.
- Low: delegated service owner may accept with rationale and review date.

Acceptance never waives a legal obligation or a non-negotiable contract term. Every exception needs scope, compensating control, owner, expiry and escalation. Proposed authority must be approved before operational use.

## Assessment limits
The control review covers management-system clauses 4–10 and sixteen prioritised Annex A topics using paraphrased summaries. It is not exhaustive. A complete, organisation-approved Statement of Applicability must evaluate necessary controls, justify inclusion/exclusion and record implementation; outsourcing alone does not justify deletion.

The selected standard's current applicable amendments, including the published 2024 context amendment, must be obtained and validated by the implementation lead. Source links are in [Sources and review](07-Sources-and-Review.md).

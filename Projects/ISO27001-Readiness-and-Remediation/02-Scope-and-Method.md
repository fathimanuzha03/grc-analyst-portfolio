# Business scenario, scope and method
**Scenario:** constructed for this portfolio | **Assessment date:** 18 November 2026

## Business model
HarbourRoute Systems provides appointment scheduling and depot arrival coordination for 52 UK transport operators. It has 76 employees and uses a managed cloud platform, a central identity service and four partner integration routes. An enterprise prospect is considering a first-year £540,000 rollout and asks for a funded security roadmap within 90 days.

The platform holds driver business-contact details, booking references, depot gate identifiers and appointment history. A proposed enterprise service tier introduces shorter recovery needs. There is no approved certification timetable.

The simulation's starting conditions are deliberately defined as follows:
- A connector secret is reused across two routes; both permit more scope than their stated business need.
- Two leavers' support accounts remain active.
- Tenant isolation is designed, but negative-test evidence is not available.
- Backups run nightly; application and configuration releases follow different review paths.
- Audit events are retained for 14 days without a documented investigative requirement or owner.
- A draft retention schedule and service-risk process await approval.
- Recovery depends on primary identity access; no independent emergency-access test is supplied.

These are invented case conditions, not findings about any real organisation or provider.

## Proposed ISMS scope
Include the scheduling application, partner API/integration routes, deployment configuration, operational identities, administration endpoints, support workflow, booking/contact data and relevant cloud/supplier interfaces. Include the staff and processes that operate or change these components.

No exclusion is approved. Discover data flows, service dependencies and contractual boundaries before approving the scope or a full Statement of Applicability. Provider-operated infrastructure remains a relevant dependency; it does not remove customer configuration and access responsibilities.

## Stakeholders
| Role | Required contribution |
|---|---|
| Managing Director | Risk appetite, resources and exceptional acceptance |
| Security Lead | Method, coordination, control selection and evidence challenge |
| Platform / Engineering / IT | Connector boundaries, identities, secure changes and technical testing |
| Operations | Business recovery needs, restoration and service commitments |
| Privacy Lead | Controller/processor roles, retention, instructions and applicable requirements |
| Partnerships / Sales | Integration scope and prospect acceptance criteria |

UK personal-data and customer-contract obligations need purpose-specific review. The case does not establish EU targeting, regulated financial activity, special-category data or a DPO requirement.

## Evidence and confidence
All E-* exhibits are synthetic records printed in [Evidence and validation](06-Evidence-and-Validation.md). They support arithmetic and analytical conclusions within the simulation only. Unavailable evidence is labelled a question or untested safeguard; it is not proof of a real-world incident.

This is a focused readiness assessment across clauses 4–10 and twelve selected control topics. Formal implementation requires the licensed current standard, full risk-led control selection and organisation-approved documentation.

## Risk method
Assess a 12-month scenario horizon. Likelihood: 1 exceptional exposure; 2 credible with substantial barriers; 3 plausible with some barriers; 4 repeated exposure with weak barriers; 5 frequent exposure with very limited barriers.

Impact: 1 local inconvenience; 2 limited operational rework; 3 material service/customer harm; 4 major data/service or contract harm; 5 sustained critical-service disruption or broad customer-boundary compromise. Select the highest credible consequence; avoid adding scores across impact types.

Priority = likelihood × impact. Bands: Low 1–4; Moderate 5–9; High 10–16; Critical 17–25. These are local ordinal judgement scales, not expected financial loss or ISO-mandated scoring.

Critical/High risk requires Managing Director review; no routine acceptance of Critical exposure. Moderate may be accepted for up to 60 days by Security Lead within approved appetite. Every acceptance needs an owner, scope, compensating safeguards, expiry and trigger for reassessment. Legal and contractual duties cannot be waived.

Current scores reflect the constructed starting safeguards. Target scores forecast treatment benefits and do not become residual-risk results until closure evidence is accepted.

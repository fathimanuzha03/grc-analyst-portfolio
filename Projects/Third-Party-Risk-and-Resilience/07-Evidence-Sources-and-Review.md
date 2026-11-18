# Evidence, references and review
**Project type:** Simulation | **Author:** Fathima Nuzha M | **Date:** 18 November 2026

## Provenance
| Basis | Meaning | Where used |
|---|---|---|
| S-CM / S-SV / S-TS / S-TP | Reference scenario statements for CloudMatrix, SecureVault, TalentSphere and TechSupport | Register and assessments |
| D-CM01–06 / D-SV01–06 / D-TS01–06 | Constructed response summaries reproduced in the assessment tables | Domain ratings and recommendations |
| V05–V08 | Entirely invented additional suppliers and initial profiles | Register, matrix and actions |
| Synthetic incident/recovery timeline | Constructed times, not a live service record | Recovery arithmetic demonstration |

No attachment, report or contract is implied to exist outside the supplied descriptions. Real supplier assurance would require actual evidence inspection and a record of reviewer, date, service scope, exceptions and customer responsibilities.

## Reproducible validation
Domain order: access, data, assurance, incident, recovery, chain. Weights: 20, 20, 20, 15, 15, 10; sum = 100.

Worked example V01: (20×2 + 20×0 + 20×2 + 15×2 + 15×2 + 10×1) ÷ 3 = **50.0**. This gives Moderate posture, proxy L=3, criticality=4 and score **12, High**. The transfer gate independently blocks client-data onboarding.

Checked across the model:
- Eight suppliers have unique IDs, eight named proposed owner roles and six domain ratings each.
- Four High / three Moderate / one Low; no Critical score is possible under the bounded triage model.
- Three full simulation questionnaires produce scores 50.0, 81.7 and 33.3.
- Fifteen unique findings map to V01–V07; V08 has no finding in this limited scenario, which is not an assurance opinion.
- The £45k budget reconciles to £20k internal effort plus £25k reserves.
- The synthetic recovery timeline calculates 5h30 elapsed and 45 minutes of data age.

These checks validate internal arithmetic and traceability, not operational controls, lawful transfers or supplier trustworthiness.

## Reference scenario
Adapted from Michael Lawrence's [DataBridge supplier-risk scenario](https://github.com/ciphermichael/grc-mentoring-portfolio/blob/main/Week-08/assignment.md). Attribution is retained. The portfolio modifies tiering where justified, distinguishes simulation from supplier representations and adds decision/recovery logic.

## Primary references
| Source | Use / limitation |
|---|---|
| [NCSC supply-chain principles](https://www.ncsc.gov.uk/collection/supply-chain/guidance/12-principles) | Informs lifecycle oversight; this policy's tiers and frequencies are analyst proposals |
| [ICO processor contract guidance](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/contracts-and-liabilities-between-controllers-and-processors-multi/what-needs-to-be-included-in-the-contract/) | Supports role-specific contract review; ICO flags relevant guidance as under review following legislative change |
| [ICO transfer guide](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/international-transfers/a-brief-guide-to-international-transfers/) | Supports assessing actual transfer flows and routes, not a blanket US prohibition |
| [ICO breach guide](https://ico.org.uk/for-organisations/report-a-breach/personal-data-breach/personal-data-breaches-a-guide/) | Distinguishes processor notification from controller reporting duties |
| [AICPA SOC resources](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services) | SOC 2 report terminology; no actual vendor report was inspected |

Guidance checked 18 November 2026. The example is informed by supplier controls A.5.19–A.5.22 and SOC 2 risk themes, but does not assert complete compliance with either standard or all privacy law. Formal use requires current legal and standards validation.

## Stakeholder review checklist
- [ ] Business owners validate criticality, tolerable disruption and dependency assumptions.
- [ ] CISO challenges synthetic ratings using actual scoped evidence.
- [ ] Legal confirms processing/transfer terms and authorisation.
- [ ] Finance validates costs, exclusions and transition reserves.
- [ ] Procurement/IT confirm the release gates can be enforced.
- [ ] Executive sponsor records approve / reject / conditions for each decision.
- [ ] Any future completed exercise records actual participants, observations and retests.

**Version 1.0:** simulation project prepared 18 November 2026. Initial drafting and calculations were AI-assisted. Management approval, supplier commitments and independent review are not obtained. Complete for portfolio review does not mean certified, operationally tested or stakeholder-approved.

[Return to project](README.md)

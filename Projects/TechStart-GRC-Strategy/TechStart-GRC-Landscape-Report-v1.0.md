# TechStart Inc. GRC Landscape Analysis

**Date:** 3 November 2026  
**Prepared by:** Fathima Nuzha M — GRC analysis portfolio  
**Version:** 1.0 | **Classification:** Public portfolio — fictional client case study  
**Status:** Proposed strategy; leadership approval and control validation outstanding

---

## Executive summary

TechStart's enterprise growth has outpaced its security governance. The business serves approximately 85,000 users but has no risk register, vendor management process, awareness training or formal compliance programme. Its only identified security policy is an unfinished document from 2021. This leaves leadership without reliable evidence of how customer information is protected and Sales without a defensible response to its first enterprise prospect.

The immediate commercial exposure is delayed or lost enterprise revenue. The operational exposure is an incident that TechStart cannot contain, investigate or explain effectively. Privacy compliance applies today; it cannot wait for a security certificate. No breach or specific statutory violation has been established by this desk assessment.

**Three recommendations:**

1. **Approve one primary assurance programme: ISO/IEC 27001:2022.** Target certification within 12 months, subject to readiness and independent assessment. It directly addresses the prospect's certification question and gives TechStart a repeatable system for managing risk. Confirm the prospect's acceptance criteria before committing to the audit scope.
2. **Start privacy remediation immediately, in parallel.** Legal should lead a 30-day review of processing roles, customer contracts, ICO fee status and UK/EU-to-US data flows. Assign owners and dates to the resulting gaps, including rights, complaints and breach handling.
3. **Create accountable leadership and delivery capacity within 30 days.** Recruit a senior GRC Manager, retain fractional CISO support, and protect engineering time for remediation. Give the CEO a monthly risk and evidence dashboard. Obtain independent internal audit support in Q3.

Use a provisional first-year programme allowance of **£90,000–£150,000**, including allocated existing staff effort and specialist support, but excluding new permanent hires and major engineering remediation. This is a planning estimate, not a supplier quote. Fund hiring separately and approve expenditure in stages. SOC 2 should be a later customer-led decision, rather than a second simultaneous audit project.

Within 90 days, TechStart should be able to present an approved scope, owned risk register, current policy set, privacy remediation plan and initial evidence of controls operating. These outputs can support procurement discussions but do not guarantee customer acceptance. Without action, procurement delays and poorly controlled security and privacy exposure will persist.

---

## Business context and assessment basis

Founded in 2019, TechStart is a Manchester-headquartered, remote-first SaaS provider with 200 employees and £18 million in Series B funding. Its project management platform serves UK and EU small and medium businesses. Names, email addresses and business activity data for approximately 85,000 end users are processed on AWS in **us-east-1 (United States)** and **eu-west-1 (Ireland)**. Enterprise expansion introduces greater scrutiny of security, resilience and subcontractors.

TechStart is likely a processor for customer workspace data and a controller for activities such as employment, account administration and its own marketing; these roles must be confirmed by processing purpose. This is a scenario-based assessment, not a technical audit. Cloud configuration, contracts, revenue, data flows and existing controls have not been inspected. AWS certifications do not establish TechStart's own compliance.

## Regulatory obligations and applicability

| Obligation | TechStart-specific assessment and immediate action | Owner |
|---|---|---|
| UK GDPR and Data Protection Act 2018, as amended | Applies to UK establishment processing personal data. Identify lawful bases for controller activities, give appropriate notices, minimise data, set retention rules, support rights, secure processing and document accountability. Establish processor agreements and subprocessor authorisation where applicable. | Head of Legal, supported by CTO |
| EU GDPR | Likely applies to relevant EU-directed services under Article 3(2); EU users' nationality alone is not the test. Validate targeting, establishment and processing roles. Assess an Article 27 EU representative; ongoing EU services make the occasional-processing exception unlikely. | Head of Legal |
| ICO fee and registration | Check the public register and complete the fee self-assessment within 30 days. Non-exempt controller processing triggers the annual fee; processor-only activity does not. Do not infer fee tier from funding or headcount alone. | Head of Legal / Finance |
| International transfers | Map contracting entities, hosting, backups, support access and subprocessors. US hosting creates a priority transfer assessment. Verify any relevant adequacy route and recipient coverage; otherwise assess appropriate EU SCCs and UK IDTA/Addendum arrangements and the required transfer assessment. EU hosting alone does not settle remote-access or onward-transfer questions. | Head of Legal / CTO |
| Breaches, rights and complaints | Maintain an incident and breach log. For controller processing, assess regulator notification without undue delay and within 72 hours where required; notify individuals where high risk requires it. As processor, notify affected controllers without undue delay. Establish rights handling, normally within one month, and a separate complaints process acknowledging complaints within 30 days. | Legal / CTO |
| DPO, DPIA and processing records | Record processing activities: routine SaaS processing means the under-250-worker exception cannot simply be assumed. Assess DPIAs before likely high-risk processing. Assess whether core activities involve large-scale regular/systematic monitoring or large-scale sensitive data processing before deciding whether a DPO is mandatory. User count alone is insufficient. | Head of Legal |
| PECR | Review cookies, tracking and electronic marketing under current UK rules; apply consent where required and document any applicable exception. The scenario does not establish which technologies are used. | Legal / Marketing |
| Financial services customer requirements | No facts establish that TechStart itself needs FCA authorisation. The regulated customer retains accountability and may require due diligence, audit/access rights, incident cooperation, resilience testing, subcontractor controls and exit arrangements. Classify the actual service and negotiate these commitments before signature. | Legal / Sales / CTO |

Legal should additionally screen relevant EU member-state laws and any NIS2 or DORA implications of the actual service, customer and establishment. These are conditional scope questions, not confirmed direct obligations on the facts provided.

Sources: [ICO fee rules](https://ico.org.uk/for-organisations/data-protection-fee/data-protection-fee/data-protection-fee-faqs/), [EDPB territorial scope guidance](https://www.edpb.europa.eu/our-work-tools/our-documents/guidelines/guidelines-32018-territorial-scope-gdpr-article-3-version_en), [ICO transfers guide](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/international-transfers/a-brief-guide-to-international-transfers/), [ICO breach guidance](https://ico.org.uk/for-organisations/report-a-breach/personal-data-breach/personal-data-breaches-a-guide/), [ICO rights timing](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/individual-rights/right-of-access/what-should-we-consider-when-responding-to-a-request/), [ICO complaints guidance](https://ico.org.uk/for-organisations/how-to-deal-with-data-protection-complaints/), [ICO DPO guidance](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/guide-to-accountability-and-governance/data-protection-officers/), [FCA third-party expectations](https://www.fca.org.uk/firms/outsourcing-and-operational-resilience).

## Framework analysis

**ISO/IEC 27001:2022 — primary assurance target.** Establish an information security management system (ISMS) covering the SaaS service and supporting people, processes and technology. It requires risk treatment, leadership oversight, documented operation and improvement. Independent certification provides procurement evidence for a defined scope; it is voluntary unless contractually required. It is the recommended fit for this prospect's explicit question, rather than a claim that every UK buyer demands it. [ISO overview](https://www.iso.org/standard/27001)

**NIST CSF 2.0 — supporting management reference.** Use Govern, Identify, Protect, Detect, Respond and Recover to organise a current/target profile and executive dashboard. It is an outcomes framework, not a certification scheme. It can help customers understand TechStart's programme without creating another audit stream. [NIST framework](https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf)

**SOC 2 — conditional second assurance product.** A CPA examination produces an attestation report against applicable Trust Services Criteria. A Type 1 addresses design at a specified date; a Type 2 also examines operating effectiveness over a period. It may meet customer requirements, including US procurement demands, but the prospect's acceptable report and scope must be confirmed. Reuse ISO evidence where relevant; the engagements remain distinct. [AICPA SOC resources](https://www.aicpa-cima.com/resources/landing/system-and-organization-controls-soc-suite-of-services)

**GDPR — mandatory privacy track.** UK GDPR and applicable EU GDPR govern personal data handling rather than supply a general security credential. TechStart needs evidence appropriate to its controller and processor roles. A security certificate or SOC report can support assurance but does not prove complete privacy compliance. Legal must validate obligations and current UK amendments. [EDPB scope guidance](https://www.edpb.europa.eu/our-work-tools/our-documents/guidelines/guidelines-32018-territorial-scope-gdpr-article-3-version_en)

**PCI DSS:** Out of scope on the stated scenario assumption that TechStart has no card processing or security-impacting payment role. Confirm billing and integrations before recording a final exclusion. PCI DSS v4.0.1 is the current revision of the earlier v4.0 reference. [PCI SSC standard](https://www.pcisecuritystandards.org/standards/pci-dss/)

## Current state assessment

RAG describes governance/evidence readiness: **Red** = explicit major gap; **Amber** = partial or unverified; **Green** = positive fact only, not proven control effectiveness.

| Area | Rating | Scenario evidence and implication |
|---|---|---|
| Leadership capacity | Amber | CTO makes security decisions; no dedicated GRC function or CISO. Accountability and escalation need formalisation. |
| Policies | Red | Unfinished 2021 policy with no review; expectations cannot be shown to be current. |
| Risk management | Red | No register; no consistent view of owners, treatment or accepted exposure. |
| Supplier assurance | Red | No vendor management process despite reliance on AWS and an unverified wider supply chain. |
| Staff awareness | Red | No training; introduce induction and role-specific learning. |
| Compliance programme | Red | None exists; obligations and evidence are not managed systematically. |
| Privacy safeguards | Amber | Personal data and Legal concern are known; notices, agreements, rights and transfer mechanisms are unverified. |
| Technical security and recovery | Amber | AWS regions are known; MFA, access reviews, logging, patching, encryption and restore tests are unverified. |
| Customer assurance | Red | CEO cannot answer requested credential questions; no credential evidence is supplied. |
| Executive sponsorship | Green | CEO has commissioned GRC work; budget and implementation approval remain outstanding. |

## Recommended priority and 12-month roadmap

Choose **ISO first, GDPR immediately alongside it, SOC 2 only at a demand gate**. Confirm in the first fortnight whether the prospect will accept an implementation plan pending certification. Do not imply that pursuing certification is equivalent to holding it. Use one evidence library and control ownership model.

Quarters below are programme quarters from approval, not calendar quarters; indicative start is November 2026.

| Period | Activities and accountable lead | Exit evidence |
|---|---|---|
| Q1: months 1–3 | CEO appoints leadership and approves resources; GRC scopes ISMS and risks; Legal inventories processing and transfers; CTO validates urgent access and incident controls; Sales agrees buyer requirements. | Approved scope, owned top risks, policy baseline, privacy gap plan, prospect response and incident contacts. |
| Q2: months 4–6 | CTO implements risk-prioritised access, secure development, vulnerability, logging and backup controls; GRC runs training, supplier reviews and recurring evidence collection; Legal closes urgent contract/transfer gaps. | Control records, access reviews, training completion, critical supplier assessments and a successful restore test. |
| Q3: months 7–9 | Independent internal auditor assesses ISMS; CEO chairs management review; owners close findings. Review SOC 2 business case with Sales before any engagement. | Audit report, corrective actions, management review, risk acceptance decisions and audit readiness decision. |
| Q4: months 10–12 | Certification body performs Stage 1 and Stage 2 when ready; teams resolve findings; GRC establishes surveillance preparation and continual improvement. | Certification only if awarded; otherwise revised plan with owned findings. SOC 2 timing depends on separate scope and observation requirements. |

Measure monthly: overdue high risks, privileged-access review completion, training completion, critical supplier review coverage, recovery test results and blocked enterprise opportunities. Set targets after Q1 baseline; propose 100% privileged-access reviews and critical supplier reviews completed by their agreed due dates, and at least 95% initial training completion by day 90.

## Approval and document control

**Prepared by:** Fathima Nuzha M — review pending  
**Reviewed by:** Sarah Chen, CTO; Rachel Davies, Head of Legal — pending  
**Approved by:** Jamie Brooks, CEO — pending  
**Approval date:** Not yet approved

| Version | Date | Change | Status |
|---|---|---|---|
| 1.0 | 3 November 2026 | Initial scenario-based landscape and proposed strategy | For review |

Research checked on 3 November 2026. Version 1.0. Markdown pagination depends on the renderer.

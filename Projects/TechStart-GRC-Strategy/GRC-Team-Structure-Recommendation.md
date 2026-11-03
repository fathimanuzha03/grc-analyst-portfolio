# GRC team structure recommendation

**TechStart Inc. | 3 November 2026 | Version 1.0 | Public portfolio — fictional case study**

## Immediate leadership and capacity

Hire a **GRC Manager / Senior GRC Lead within 30 days**. TechStart needs someone able to build the ISMS, maintain the risk register, coordinate evidence and translate customer requirements into delivery priorities. The existing first-engagement GRC Analyst should support this lead; the analyst should not carry executive security accountability alone.

Retain a **fractional CISO** during Q1 to advise the CEO on strategy, challenge technical risk decisions and guide engineering priorities. The CTO remains accountable for operational security delivery. A permanent CISO is a Q4 decision based on growth, customer requirements and workload; it is not a prerequisite for ISO certification.

Rachel Davies remains the executive owner for privacy compliance. Assess whether a statutory DPO is required based on actual processing. A privacy coordinator can organise rights requests and records, but must not be labelled a statutory DPO without the appropriate appointment, expertise and safeguards. A DPO advises and monitors; management remains accountable for compliance. [ICO DPO guidance](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/guide-to-accountability-and-governance/data-protection-officers/)

## 12-month staffing roadmap

| Programme quarter | Staffing / allocation | Purpose and decision gate |
|---|---|---|
| Q1: months 1–3 | Recruit senior GRC lead; retain fractional CISO for approximately 2–4 days/month initially; allocate the current GRC Analyst; protect named Engineering and Legal capacity | Establish leadership, scope, risk ownership, privacy triage and assurance responses. Escalate hiring delays to CEO; use interim specialist delivery if needed. |
| Q2: months 4–6 | Add 0.5–1 FTE Compliance Analyst capacity if evidence collection, vendor reviews and questionnaires exceed existing capacity; assign a Legal privacy coordinator | Operate recurring processes without diverting the senior lead from risk and programme management. Appoint an external DPO if assessment requires one, or document the basis for no mandatory appointment. |
| Q3: months 7–9 | Engage an independent internal auditor; use specialist privacy/security advice as required | Test the programme independently, address findings and assess certification readiness. Auditor must not audit their own implementation work. |
| Q4: months 10–12 | Review permanent CISO requirement and analyst capacity; retain or expand fractional model only if it meets demand | Sustain the ISMS after certification, plan surveillance and support any approved SOC 2 work. No automatic hiring ladder is assumed. |

These allocations are initial planning assumptions, not approved positions. The programme budget excludes new permanent salaries; Finance should obtain role-specific hiring and service quotes. Existing team allocations must be agreed with their managers, rather than treated as spare capacity.

## Reporting lines and organisation chart

Initially, the GRC lead reports directly to Jamie Brooks, CEO. If a permanent CISO is appointed, the GRC lead reports to that CISO, who reports to the CEO and has board access. The fractional CISO advises the CEO and supports the GRC lead. Sarah Chen, CTO, owns engineering execution. Legal partners with GRC without transferring operational privacy accountability to a DPO.

```text
Board / Audit & Risk oversight
|
CEO — Jamie Brooks
|-- Fractional CISO (Q1; permanent appointment reviewed in Q4)
|   `-- GRC Manager / Senior GRC Lead
|       |-- GRC Analyst (current engagement)
|       `-- Compliance Analyst (Q2 capacity gate)
|-- CTO — Sarah Chen
|   `-- Engineering / IT / operational security control owners
|-- Head of Legal — Rachel Davies
|   `-- Privacy coordinator / operational privacy support
`-- DPO, if required or voluntarily appointed
    `-- Independent advice/monitoring; direct access to CEO and board

Independent internal audit provider --> reports to Board / Audit & Risk oversight
```

For the initial period before any CISO reporting line is formalised, the GRC lead reports to the CEO. The DPO is deliberately separate from the analyst delivery chain: placing the DPO below the analyst delivery chain could compromise independence. Avoid appointing the CTO as DPO where the CTO determines processing means; evaluate conflicts for any candidate, including Legal.

## Three lines of defence

**First line — owns and operates controls.** Engineering, IT, HR, Sales and relevant Legal process owners handle risks in daily work. Examples include granting access, applying retention, managing suppliers and meeting contractual commitments. The CTO owns security operations; business owners own their own risks.

**Second line — sets expectations, advises and monitors.** GRC establishes risk methods and policy governance, checks evidence and challenges overdue actions. Privacy oversight advises and monitors; a DPO, when appointed, must retain statutory independence. At this size people may have several duties, but task-level conflicts must be identified and mitigated.

**Third line — provides independent assurance.** A suitably independent internal audit provider assesses design and operation and reports findings directly to board oversight. The GRC lead coordinates evidence but does not provide independent assurance over their own programme. Certification and SOC examinations provide additional external assurance and do not replace management's internal audit arrangements.

## RACI: five core GRC activities

**R:** performs the work; **A:** single management owner; **C:** consulted; **I:** informed. The CISO column represents fractional or permanent security leadership. The DPO column applies only if appointed. Consult other business control owners as needed.

| Activity | CEO | CTO / operations | GRC lead and analysts | Head of Legal | CISO | DPO | Independent internal auditor | Board oversight |
|---|---|---|---|---|---|---|---|---|
| Enterprise security risk assessment and escalation | A | R | R | C | C | C | I | I |
| Security policy development and approval | A | C | R | C | C | C | I | I |
| GDPR operational compliance programme | I | R | R | A | C | C | I | I |
| Vendor security/privacy risk process | I | A | R | R | C | C | I | I |
| Independent ISMS internal audit and reporting | I | C | C | C | C | C | R | A |

The DPO's “C” role means independent advice in these delivery activities; their monitoring and regulator-cooperation responsibilities remain part of their separate mandate. For internal audit, board oversight owns commissioning and independence; the auditor owns execution and findings. Management assigns remediation owners and accepts residual risks through approved delegations. The CTO's vendor accountability covers operational supplier risk, while Legal remains responsible for contract/privacy advice.

## Operating rhythm

Run weekly remediation meetings led by GRC, monthly CEO risk reviews and quarterly board updates. Escalate overdue high risks and unapproved customer security promises immediately. Require controlled evidence storage, named control owners, due dates, approvals and review records. Judge capacity by recurring work delivered and overdue risks, rather than job titles alone.

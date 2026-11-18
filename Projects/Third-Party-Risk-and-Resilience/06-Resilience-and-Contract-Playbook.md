# Sharing, resilience and exit playbook
**Status:** proposed operating instructions for the Northbank simulation

## Asset-sharing gate
Classify footage and agree the client's permitted audience/use before loading assets. Configure named reviewers, least access, expiry and permitted download behaviour. Check default links, copied links, forwarded links, guest accounts and mobile views.

Do not assume a certificate or favourable supplier questionnaire proves the studio's tenant configuration. Keep a record of the authorised service scope and the administrator who released it.

## Contract and rights review
Legal must validate applicable processing roles, client permissions, confidentiality, onward access, location changes, security/incident assistance, audit information and end-of-service handling. Production rights and privacy instructions must both be considered; one document does not automatically satisfy both.

Where restricted transfers occur, validate the actual flow and applicable legal route. No country or transfer mechanism is inferred from the invented supplier's name. The analysis does not determine that every supplier is a processor or every incident requires regulator reporting.

## Incident coordination
| Trigger | Owner | Action |
|---|---|---|
| Exposed review link or unauthorised editor | Platform / Security | Restrict access, preserve records and identify assets/recipients |
| Supplier service interruption | Delivery / Post-production | Activate validated fallback and track recovery milestones |
| Potential personal-data breach | Legal / Security | Assess roles, facts and required notifications; processors notify relevant controllers without undue delay as applicable |
| Client release affected | Account owner | Use verified contacts; communicate facts, uncertainty and next update |
| Recovery complete | Business / Security | Validate integrity, review access and assign corrective actions |

An internal target such as one-hour triage is an operational proposal, not a universal legal deadline. Legal must distinguish supplier-to-customer notice from a controller's regulator notification duties. [ICO breach guidance](https://ico.org.uk/for-organisations/report-a-breach/personal-data-breach/personal-data-breaches-a-guide/)

## Recovery specification
Proposed archive objectives for release-critical masters: **RTO 8 hours; RPO 24 hours**. These need business approval and dependency validation.

A representative exercise should cover asset retrieval, independent key access, metadata/checksum reconciliation, usable media, required edit/project files and onward delivery. Verify bulk exit capacity rather than assuming small-file export proves timely project migration.

Synthetic exercise: disruption/request at 09:00 UTC on 18 November 2026; latest recoverable asset set at 10:00 UTC on 17 November; usable recovered assets validated at 20:00 UTC on 18 November.

Calculated elapsed recovery is **11 hours**, exceeding RTO by **3 hours**. Data age at disruption is **23 hours**, meeting RPO by **1 hour**. This is arithmetic over a constructed timeline, not an executed real restore. N-F04 remains open in the simulation.

## Controlled exit
1. Confirm replacement service, permissions and client continuity requirements.
2. Export assets, metadata, reviews and necessary audit records in usable forms.
3. Validate completeness and restore/reuse before deleting the old recovery copy.
4. Revoke named accounts, share links, integration tokens and external-editor access.
5. Confirm return/deletion or explicitly authorised retention across working copies and downstream parties.
6. Retain justified audit evidence; close the supplier only after dependency and billing checks.

For an editor, deletion evidence must cover local working copies. For the archive, exit must preserve the only usable master. For delivery, test a fallback outside any shared failure dependency.

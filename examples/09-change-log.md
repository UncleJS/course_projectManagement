# Worked Example: Change Log
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Change%20Log-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/change-log.md`](../templates/change-log.md) | **Module:** [05 — Project Execution](../modules/05-execution.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Change Log](#change-log)
- [Status Definitions](#status-definitions)
- [Budget Impact Summary (as at 15 August 2026)](#budget-impact-summary-as-at-15-august-2026)
- [Notes](#notes)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.3 |
| **Date** | 15 August 2026 |
| **Owner** | Sarah Chen, Project Manager |

[↑ Back to top](#table-of-contents)

---

## Change Log

| CR No. | Date received | Requestor | Description | Status | Decision date | Approved by | Budget impact (£) | Schedule impact | Implementation date |
|---|---|---|---|---|---|---|---|---|---|
| CR-001 | 22 May 2026 | Sandra Obi | Add Welsh language option to all four service modules | **Deferred — Phase 2** | 4 Jun 2026 | James Hartley | £0 (this project) | None | Phase 2 Q1 2027 |
| CR-002 | 12 Jun 2026 | Mark Pearce | Increase UNIFORM API rate limit from 100 to 500 requests/minute to support peak load. Requires additional ICT infrastructure work. | **Approved** | 19 Jun 2026 | Sarah Chen (≤£20k threshold) | +£7,200 (from contingency) | +5 days in integration phase (absorbed) | 14 Jul 2026 |
| CR-003 | 1 Jul 2026 | GovTech Solutions | Reduce scope: remove parking permit renewal module from Phase 1 due to UNIFORM data incompatibility discovered in integration testing. Defer to Phase 2. | **Approved** | 8 Jul 2026 | James Hartley (Project Board) | -£18,000 (released from GovTech contract) | None — replaced by additional UAT time | Not applicable — deferred |
| CR-004 | 29 Jul 2026 | Councillor Patricia Dean (via Sponsor) | Request to add a "Report a Pothole" feature to the portal before go-live | **Rejected** | 5 Aug 2026 | James Hartley | N/A | Would delay go-live by 6–8 weeks | N/A |
| CR-005 | 10 Aug 2026 | Sarah Chen | Extend hypercare support period from 30 days to 45 days due to complexity of council tax module. Additional GovTech support cost. | **Approved** | 14 Aug 2026 | James Hartley | +£3,600 (from contingency) | None | Go-live + 45 days |

[↑ Back to top](#table-of-contents)

---

## Status Definitions

| Status | Meaning |
|---|---|
| **Submitted** | Received; under assessment by PM |
| **Approved** | Approved by appropriate authority; being implemented |
| **Rejected** | Not approved; requestor notified with rationale |
| **Deferred** | Approved in principle but moved to a future phase |
| **Implemented** | Change has been made; baseline updated |
| **Cancelled** | Requestor withdrew the request |

[↑ Back to top](#table-of-contents)

---

## Budget Impact Summary (as at 15 August 2026)

| Item | Amount (£) |
|---|---|
| Original contingency | 38,000 |
| CR-002 drawdown | -7,200 |
| CR-003 saving (returned to contingency) | +18,000 |
| CR-005 drawdown | -3,600 |
| **Remaining contingency** | **45,200** |

> Note: CR-003 saved £18,000 from the GovTech contract (parking permits module deferred). This has been retained in contingency rather than returned to the general capital programme, pending Phase 2 planning.

[↑ Back to top](#table-of-contents)

---

## Notes

**CR-003** (Parking Permit Deferral) is the most significant change on this project. It was discovered during integration testing that the UNIFORM system does not hold parking permit expiry data in a queryable format — it is stored as a scanned PDF attachment. Extracting this data would require significant UNIFORM system changes outside project scope. The decision to defer rather than attempt a workaround was correct and protected the go-live date.

**CR-004** (Pothole reporting) is a good example of scope creep from a senior stakeholder. Despite coming via the Sponsor, the change was correctly assessed and rejected because it would have endangered the fixed go-live date (CON-02) and was outside the scope of the business case.

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

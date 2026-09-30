# Worked Example: Status Report — Month 3 (Highlight Report)
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Status%20Report-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/status-report.md`](../templates/status-report.md) | **Module:** [06 — Monitoring and Controlling](../modules/06-monitoring-control.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Overall RAG Status](#overall-rag-status)
  - [RAG Definitions](#rag-definitions)
- [Period Summary](#period-summary)
- [Progress This Period (May 2–8, 2026)](#progress-this-period-may-28-2026)
- [Planned for Next Period (May 9 – June 5, 2026)](#planned-for-next-period-may-9--june-5-2026)
- [Financials](#financials)
  - [Earned Value Management (EVM) Summary](#earned-value-management-evm-summary)
- [Risks (Top 3 Active Risks)](#risks-top-3-active-risks)
- [Issues (Open Issues)](#issues-open-issues)
- [Decisions Required from Sponsor / Board](#decisions-required-from-sponsor--board)
- [Change Requests Status](#change-requests-status)
- [Notes / Commentary](#notes--commentary)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Report No.** | 06 |
| **Reporting period** | May 2, 2026 – May 8, 2026 |
| **Report date** | May 8, 2026 |
| **Prepared by** | Sarah Chen, Project Manager |
| **Distribution** | James Hartley, Sandra Obi, Mark Pearce, Councilmember Dean, Claire Worthington |

[↑ Back to top](#table-of-contents)

---

## Overall RAG Status

| Dimension | RAG | Notes |
|---|---|---|
| **Overall** | 🟢 GREEN | Gate 1 passed; ICT developer confirmed; LandWorks integration risk still open |
| **Schedule** | 🟢 GREEN | Gate 1 delivered on time (May 8, 2026) |
| **Budget** | 🟢 GREEN | Spend on track; no contingency draw-down to date |
| **Scope / Quality** | 🟢 GREEN | Discovery and design approved for all four original service modules, including parking permits |
| **Risk** | 🟡 AMBER | RSK-01 (LandWorks integration) remains high until integration testing checks parking-permit data |
| **Stakeholders** | 🟢 GREEN | Contact-center team briefed; BCM (Diane Hughes) confirmed on April 22, 2026 |

### RAG Definitions

| Status | Meaning |
|---|---|
| 🟢 **Green** | On track; no significant issues |
| 🟡 **Amber** | Under pressure / manageable risk; sponsor should be aware |
| 🔴 **Red** | Off track; requires escalation / corrective action |

[↑ Back to top](#table-of-contents)

---

## Period Summary

Gate 1 (Discovery and Design) was passed on May 8, 2026 — on schedule. The Discovery Report and UX Design Specification were approved by the Senior User (Sandra Obi) and Senior Supplier (Mark Pearce) at the Gate 1 review meeting this morning. The project now moves into the Build and Integration phase.

Parking-permit renewal is still in Phase 1 scope. Whether LandWorks can supply parking-permit expiry data through the API has not been proven. That check is part of integration testing and is the subject of RSK-01. No issue has been raised, and no change request is in draft.

[↑ Back to top](#table-of-contents)

---

## Progress This Period (May 2–8, 2026)

- ✅ Gate 1 review conducted and passed (May 8, 2026)
- ✅ Discovery Report approved by Senior User and Senior Supplier
- ✅ UX Design Specification approved — all four service modules, including parking permits
- ✅ Integration Specification approved by ICT Manager (Mark Pearce), with parking-permit field coverage still to be proven in integration testing
- ✅ Privacy Impact Assessment (PIA) signed off by the Chief Privacy Officer (May 5, 2026)
- ✅ GovTech build environment provisioned; development sprint 1 begins May 11, 2026

[↑ Back to top](#table-of-contents)

---

## Planned for Next Period (May 9 – June 5, 2026)

- GovTech Development Sprint 1: Planning and zoning application tracking module build begins
- ICT Developer (Tom Okafor) begins LandWorks integration configuration for the planning module, including a test of parking-permit data fields
- Business Change Manager (Diane Hughes) begins staff engagement planning
- If integration testing shows parking-permit data cannot be queried, the PM will raise an issue and a change request for the July Project Board
- Project Board Meeting 4 — June 4, 2026 (routine progress review)

[↑ Back to top](#table-of-contents)

---

## Financials

| Item | Budget ($) | Committed ($) | Actual spend to date ($) | Forecast final cost ($) | Variance ($) |
|---|---|---|---|---|---|
| GovTech platform license and configuration | 240,000 | 240,000 | 96,000 | 240,000 | 0 |
| ICT integration (internal) | 48,000 | 48,000 | 4,800 | 48,000 | 0 |
| Project management (internal) | 42,000 | 42,000 | 14,000 | 42,000 | 0 |
| Training and change | 20,000 | 4,500 | 1,500 | 20,000 | 0 |
| Content / UX | 32,000 | 32,000 | 12,800 | 32,000 | 0 |
| Contingency | 38,000 | 0 | 0 | 38,000 | 0 |
| **Total** | **420,000** | **366,500** | **129,100** | **420,000** | **0** |

### Earned Value Management (EVM) Summary

| Metric | Value | Interpretation |
|---|---|---|
| Planned Value (PV) | $129,500 | Budgeted work to date |
| Earned Value (EV) | $127,800 | Value of work actually completed |
| Actual Cost (AC) | $129,100 | What we've spent |
| Schedule Variance (SV) | −$1,700 | Very slightly behind planned work (1.3% — within tolerance) |
| Cost Variance (CV) | −$1,300 | Very slightly over planned cost for work done (1.0% — within tolerance) |
| SPI | 0.99 | Essentially on schedule |
| CPI | 0.99 | Essentially on budget |

*Both SPI and CPI are at 0.99 — effectively on track. No corrective action required.*

[↑ Back to top](#table-of-contents)

---

## Risks (Top 3 Active Risks)

| Ref | Risk | Current score | Trend | Response |
|---|---|---|---|---|
| RSK-01 | LandWorks integration more complex than estimated | P3 / I4 = 12 (**HIGH**) | → Stable | Parking-permit data fields are not yet proven; integration testing in June will confirm or close this risk |
| RSK-02 | GovTech delivery delay in build phase | P2 / I4 = 8 (Medium) | → Stable | Contractual milestone payments; PM weekly check-in with GovTech PM |
| RSK-05 | Resident adoption below 55% target | P3 / I3 = 9 (Medium) | → Stable | UX research incorporated in design; resident communications campaign planned for Aug–Sep |

[↑ Back to top](#table-of-contents)

---

## Issues (Open Issues)

No open issues this period. RSK-01 is being watched and is not yet an issue.

[↑ Back to top](#table-of-contents)

---

## Decisions Required from Sponsor / Board

1. **None this period.** The Sponsor is asked to note that RSK-01 (LandWorks parking-permit data) will be tested in integration. If the data cannot be queried, the PM will bring a change request to the July Project Board.

[↑ Back to top](#table-of-contents)

---

## Change Requests Status

| CR No. | Description | Status | Cost impact ($) | Schedule impact |
|---|---|---|---|---|
| — | No change requests raised this period | — | — | — |

[↑ Back to top](#table-of-contents)

---

## Notes / Commentary

The project is in a solid position at Gate 1. Parking-permit renewal remains in scope. Compatibility of LandWorks parking-permit data is an open risk (RSK-01), to be tested when integration starts, not a defect found in discovery.

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

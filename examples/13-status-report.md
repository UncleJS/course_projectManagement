# Worked Example: Status Report — Month 3 (Highlight Report)
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Status%20Report-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/status-report.md`](../templates/status-report.md) | **Module:** [06 — Monitoring and Controlling](../modules/06-monitoring-control.md)

---

## Table of Contents

- [Document Control](#document-control)
- [RAG Status Summary](#rag-status-summary)
- [Period Summary](#period-summary)
- [Progress This Period (2–8 May 2026)](#progress-this-period-28-may-2026)
- [Planned for Next Period (9 May – 5 June 2026)](#planned-for-next-period-9-may--5-june-2026)
- [Financials](#financials)
  - [Earned Value Management (EVM) Summary](#earned-value-management-evm-summary)
- [Top Risks](#top-risks)
- [Open Issues](#open-issues)
- [Decisions Required from Sponsor/Project Board](#decisions-required-from-sponsorproject-board)
- [Notes](#notes)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Report No.** | 06 |
| **Reporting period** | 2 May 2026 – 8 May 2026 |
| **Report date** | 8 May 2026 |
| **Prepared by** | Sarah Chen, Project Manager |
| **Distribution** | James Hartley, Sandra Obi, Mark Pearce, Councillor Dean, Claire Worthington |

[↑ Back to top](#table-of-contents)

---

## RAG Status Summary

| Dimension | RAG | Notes |
|---|---|---|
| **Overall** | 🟡 AMBER | Gate 1 passed; ICT Developer confirmed; parking permits integration risk escalated |
| **Schedule** | 🟢 GREEN | Gate 1 delivered on time (8 May 2026) |
| **Budget** | 🟢 GREEN | Spend on track; no contingency draw-down to date |
| **Scope / Quality** | 🟡 AMBER | UNIFORM API limitation for parking permits identified — Change Request in preparation |
| **Risk** | 🟡 AMBER | RSK-01 partially materialised (parking permits); full picture emerging |
| **Stakeholders** | 🟢 GREEN | Contact-centre team briefed; BCM (Diane Hughes) confirmed |

> **RAG Definitions:** 🟢 GREEN = On track; 🟡 AMBER = Under pressure / manageable risk; 🔴 RED = Off track; requires escalation / corrective action.

[↑ Back to top](#table-of-contents)

---

## Period Summary

Gate 1 (Discovery and Design) was passed on 8 May 2026 — on schedule. The Discovery Report and UX Design Specification were approved by the Senior User (Sandra Obi) and Senior Supplier (Mark Pearce) at the Gate 1 review meeting this morning. The project now moves into the Build and Integration phase.

One significant issue emerged during discovery: the UNIFORM system does not expose parking permit expiry data in a format that the portal can consume via the standard API. This was not identified in pre-project scoping. A technical options assessment has been completed and is being submitted as a Change Request (CR-003 in draft) to defer the parking permit module to Phase 2. This is the right decision: attempting to resolve the UNIFORM data issue within the current project scope and budget would be disproportionate.

[↑ Back to top](#table-of-contents)

---

## Progress This Period (2–8 May 2026)

- ✅ Gate 1 review conducted and passed (8 May 2026)
- ✅ Discovery Report approved by Senior User and Senior Supplier
- ✅ UX Design Specification approved — all four service modules
- ✅ Integration Specification approved by ICT Manager (Mark Pearce)
- ✅ Data Protection Impact Assessment (DPIA) signed off by DPO (5 May 2026)
- ✅ GovTech build environment provisioned; development sprint 1 begins 11 May 2026
- 🔄 CR-003 (parking permit deferral) — in draft; to Project Board for decision by 8 July 2026

[↑ Back to top](#table-of-contents)

---

## Planned for Next Period (9 May – 5 June 2026)

- GovTech Development Sprint 1: Planning application tracking module build begins
- ICT Developer (Tom Okafor) begins UNIFORM integration configuration for planning module
- Business Change Manager (Diane Hughes) begins staff engagement planning
- CR-003 finalised and submitted to Project Board
- Project Board Meeting 4 — 4 June 2026

[↑ Back to top](#table-of-contents)

---

## Financials

| Item | Budget (£) | Committed (£) | Actual spend to date (£) | Forecast final cost (£) | Variance (£) |
|---|---|---|---|---|---|
| GovTech platform licence and configuration | 240,000 | 240,000 | 96,000 | 240,000 | 0 |
| ICT integration (internal) | 48,000 | 48,000 | 4,800 | 48,000 | 0 |
| Project management (internal) | 42,000 | 42,000 | 14,000 | 42,000 | 0 |
| Training and change | 20,000 | 4,500 | 1,500 | 20,000 | 0 |
| Content / UX | 32,000 | 32,000 | 12,800 | 32,000 | 0 |
| Contingency | 38,000 | 0 | 0 | 38,000 | 0 |
| **Total** | **420,000** | **366,500** | **129,100** | **420,000** | **0** |

### Earned Value Management (EVM) Summary

| Metric | Value | Interpretation |
|---|---|---|
| Planned Value (PV) | £129,500 | Budgeted work to date |
| Earned Value (EV) | £127,800 | Value of work actually completed |
| Actual Cost (AC) | £129,100 | What we've spent |
| Schedule Variance (SV) | −£1,700 | Very slightly behind planned work (1.3% — within tolerance) |
| Cost Variance (CV) | −£1,300 | Very slightly over planned cost for work done (1.0% — within tolerance) |
| SPI | 0.99 | Essentially on schedule |
| CPI | 0.99 | Essentially on budget |

*Both SPI and CPI are at 0.99 — effectively on track. No corrective action required. The minor variance is due to discovery phase taking an extra 2 days for the UNIFORM parking permit investigation.*

[↑ Back to top](#table-of-contents)

---

## Top Risks

| Ref | Risk | Current score | Trend | Response |
|---|---|---|---|---|
| RSK-01 | UNIFORM integration more complex than estimated | P3 / I4 = 12 (**HIGH**) | ↑ Increased | Parking permit issue addressed via CR-003; remaining three modules assessed — no further UNIFORM limitations identified |
| RSK-02 | GovTech delivery delay in build phase | P2 / I4 = 8 (Medium) | → Stable | Contractual milestone payments; PM weekly check-in with GovTech PM |
| RSK-05 | Resident adoption below 55% target | P3 / I3 = 9 (Medium) | → Stable | UX research incorporated in design; resident communications campaign planned for Aug–Sep |

[↑ Back to top](#table-of-contents)

---

## Open Issues

| ID | Issue | Severity | Owner | Status |
|---|---|---|---|---|
| ISS-04 (emerging) | UNIFORM parking permit data not queryable — CR-003 in preparation | High | Sarah Chen / Mark Pearce | Being addressed via change control |

[↑ Back to top](#table-of-contents)

---

## Decisions Required from Sponsor/Project Board

1. **CR-003 (Parking Permit Deferral)** — Decision required by Project Board by **4 June 2026** (Project Board Meeting 4). Full change request will be circulated by 26 May 2026.

[↑ Back to top](#table-of-contents)

---

## Notes

The project is in a solid position at Gate 1. The parking permit issue, while significant, was identified early through rigorous technical discovery — exactly as intended. The recommended response (deferral to Phase 2) is proportionate and protects the go-live date. The remaining three service modules have no equivalent UNIFORM compatibility issues.

[↑ Back to top](#table-of-contents)

---

*© 2026 UncleJs — Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*

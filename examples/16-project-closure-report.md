# Worked Example: Project Closure Report
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Project%20Closure%20Report-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/project-closure-report.md`](../templates/project-closure-report.md) | **Module:** [07 — Project Closing](../modules/07-closing.md)

---

## Table of Contents

- [Document Control](#document-control)
- [1. Executive Summary](#1-executive-summary)
- [2. Project Overview](#2-project-overview)
- [3. Objectives and Deliverables](#3-objectives-and-deliverables)
  - [Objectives Achievement](#objectives-achievement)
  - [Deliverables](#deliverables)
  - [Scope Changes](#scope-changes)
- [4. Schedule Performance](#4-schedule-performance)
- [5. Financial Performance](#5-financial-performance)
- [6. Quality Performance](#6-quality-performance)
- [7. Risk and Issue Summary](#7-risk-and-issue-summary)
  - [Risks](#risks)
  - [Issues](#issues)
- [8. Benefits Handover](#8-benefits-handover)
- [9. Handover to BAU](#9-handover-to-bau)
- [10. Lessons Learned Summary](#10-lessons-learned-summary)
- [11. Project Archive](#11-project-archive)
- [12. Recommendation](#12-recommendation)
- [Authorization](#authorization)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Project Reference** | NGT-2026-DIG-01 |
| **Version** | 1.0 (Final) |
| **Date** | October 31, 2026 |
| **Prepared by** | Sarah Chen, Project Manager |
| **Approved by** | James Hartley, Project Sponsor |

[↑ Back to top](#table-of-contents)

---

## 1. Executive Summary

The Meridian Citizen Self-Service Portal was delivered within budget and closed on its baseline date. The portal went live on October 8, 2026 — 7 days later than the original October 1 target, but within the overall schedule to formal closure — enabling City of Northgate residents to track planning and zoning applications, report missed trash collections, check property tax accounts, and renew yard waste subscriptions online without visiting or calling the City.

**Budget**: $420,000 approved; $374,800 actual spend ($45,200 underspend, 10.8%) — driven by the CR-003 parking-permit scope reduction ($18,000) and unused contingency ($27,200).
**Schedule**: Original planned go-live October 1, 2026; actual go-live October 8, 2026 (+7 days, CR-006). Formal closure remained October 31, 2026. Hypercare, set by CR-005 at 45 days from go-live, runs through November 22, 2026.
**Scope**: Planning and zoning, property tax, and waste reporting (missed trash and yard waste) went live. Parking permit renewal, the fourth chartered module, was deferred to Phase 2 (CR-003, approved July 2026) after a LandWorks API limitation was identified during integration testing.

Early use data (end of October 2026) shows 41% of eligible residents have accessed the portal. Access is not inquiry deflection. The 55% deflection target is the share of the 14,200 in-scope inquiries handled online, measured at month 6 (April 2027). That benefit has not been measured yet.

The project is recommended for formal closure. Benefits realization is being handed over to Sandra Obi (Senior User / Head of Customer Services) with a post-implementation review scheduled for April 2027.

[↑ Back to top](#table-of-contents)

---

## 2. Project Overview

| Item | Detail |
|---|---|
| **Project start date** | February 3, 2026 |
| **Original planned end date** | October 1, 2026 (go-live); October 31, 2026 (formal closure) |
| **Actual end date** | October 31, 2026 |
| **Project sponsor** | James Hartley, Director of Digital Services |
| **Project manager** | Sarah Chen |
| **Total approved budget** | $420,000 |
| **Actual final cost** | $374,800 |
| **Underspend** | $45,200 (10.8%) |

[↑ Back to top](#table-of-contents)

---

## 3. Objectives and Deliverables

### Objectives Achievement

| Ref | Objective | Achieved? | Notes |
|---|---|---|---|
| OBJ-01 | Deliver a fully operational citizen self-service portal | **Achieved late** | Live on October 8, 2026. The charter date was October 1, 2026 (+7 days, CR-006). |
| OBJ-02 | Enable digital self-service for planning and zoning inquiries, property tax payments, waste reporting, and parking permit renewals | **Partly achieved** | Planning and zoning, property tax, and waste reporting (missed trash and yard waste) are live. Parking permit renewal was deferred to Phase 2 (CR-003). |
| OBJ-03 | Integrate with the Northgate LandWorks back-office system | **Achieved for delivered scope** | Integration for the live modules was tested and signed off by the ICT Manager before go-live. Parking-permit integration was not completed. |
| OBJ-04 | Achieve project delivery within approved budget | **Fully achieved** | Outturn $374,800, within the $420,000 cap. |
| OBJ-05 | Complete user acceptance testing with resident involvement | **Partly achieved** | Sandra Obi signed off the 47 UAT scenarios before go-live. The quality register records 12 resident testers. The charter measure was at least 30. |

### Deliverables

| Ref | Deliverable | Delivered? | Acceptance date | Notes |
|---|---|---|---|---|
| DEL-01 | Discovery Report and UX Design Specification | Yes | May 8, 2026 | Approved at Gate 1 by Senior User and Senior Supplier |
| DEL-02 | Integration Specification | Yes | May 8, 2026 | Approved by ICT Manager (Mark Pearce) at Gate 1 |
| DEL-03 | Privacy Impact Assessment | Yes | May 5, 2026 | Signed off by the Chief Privacy Officer |
| DEL-04 | Planning and zoning application tracking module (live) | Yes | October 8, 2026 | Integration with LandWorks (planning) — live |
| DEL-05 | Missed trash collection reporting module (live) | Yes | October 8, 2026 | Integration with Civica Waste — live |
| DEL-06 | Property tax account / payment module (live) | Yes | October 8, 2026 | Integration with Harbor Payments (property tax) — live; security cert obtained Jul 2026 |
| DEL-07 | Yard waste subscription renewal module (live) | Yes | October 8, 2026 | Integration with Civica Waste — live |
| DEL-08 | Parking permit module | **Not delivered (Phase 2)** | — | Deferred via CR-003 (approved July 8, 2026) due to LandWorks API limitation |
| DEL-09 | Accessibility audit report and remediation | Yes | September 25, 2026 | All 14 issues resolved; WCAG 2.1 AA compliance confirmed |
| DEL-10 | Staff training program | Yes | October 2, 2026 | 54 staff trained across planning, revenues, and waste services |
| DEL-11 | System administration documentation | Yes | October 6, 2026 | Handed over to ICT (Tom Okafor) and GovTech support team |
| DEL-12 | Resident communications campaign | Yes | Sep 2026 | 68% resident awareness pre-launch (target: 50%) |

### Scope Changes

| CR No. | Description | Cost impact ($) | Schedule impact |
|---|---|---|---|
| CR-001 | Spanish language interface deferred to Phase 2 | $0 (deferred; not funded in Phase 1) | None |
| CR-002 | LandWorks API rate-limit increase to support integration load | +$7,200 (contingency-funded) | None |
| CR-003 | Parking permit module deferred to Phase 2 (LandWorks API incompatibility) | −$18,000 (removed from build scope) | None — go-live date maintained |
| CR-005 | Hypercare extended from 30 to 45 days | +$3,600 (contingency-funded) | None |
| CR-006 | Go-live moved from October 1 to October 8. Exception report to the Sponsor / Executive. | $0 | +7 days |
| **Net scope change impact** | | **−$7,200** | **Go-live +7 days** |

[↑ Back to top](#table-of-contents)

---

## 4. Schedule Performance

| Item | Baseline | Actual | Variance |
|---|---|---|---|
| Gate 1 (Discovery and Design complete) | May 8, 2026 | May 8, 2026 | **0 days** |
| Gate 2 (Build complete) | August 7, 2026 | August 7, 2026 | **0 days** |
| SIT complete | August 21, 2026 | September 4, 2026 | **+14 days (late)** |
| UAT begins | August 24, 2026 | September 11, 2026 | **+18 days (late)** |
| UAT complete | September 18, 2026 | September 25, 2026 | **+7 days (late)** |
| Contact-center training sign-off | September 25, 2026 | October 2, 2026 | **+7 days (late)** |
| Accessibility audit and remediation complete | October 2, 2026 | September 25, 2026 | **+7 days (early)** |
| Go-live | October 1, 2026 | October 8, 2026 | **+7 days (late)** |
| Project closure | October 31, 2026 | October 31, 2026 | **0 days** |

**Schedule Performance Index (SPI) at closure**: 1.00

**Commentary**: Gate 2, build complete, was met on August 7, 2026. Yard waste, the last module demo, was accepted that day. Integration testing was not on time. SIT was planned to finish on August 21, ahead of UAT on Monday, August 24. The run started on August 24 and the seven defects were closed on September 4, 14 days late. UAT therefore began on September 11 instead of August 24, 18 days late. UAT then finished on September 25, 7 days after the September 18 gate. The plan kept 13 days after UAT for training and cutover. Training sign-off moved from September 25 to October 2. Counted from September 25, the same gap ends on October 8, so go-live moved by those 7 days (CR-006, approved September 30). Production readiness passed on October 7, and operational acceptance was signed the same day. The Harbor Payments audit (ISS-04) closed on July 21 and did not move Gate 2. Parking permits had already been deferred on July 8 (CR-003). The slip that remains is the LandWorks integration test. Formal closure stayed on October 31. CR-005 (approved August 14, 2026) had already set hypercare at 45 days from go-live, then planned for October 1 (through Sunday, November 15). From the actual October 8 go-live, those 45 days run through Sunday, November 22, 2026, after formal closure. October 31 is a Saturday: it is month-end and day 30 after the Thursday, October 1 go-live, so the original hypercare end and formal closure share that date. It was the closure milestone, not a buffer that absorbed the slip. SPI is 1.00 because the approved scope was finished by closure. That index does not measure the SIT or UAT slip; the schedule table above does. The principal lesson (integration-test time on a legacy system) is captured in the lessons-learned log.

[↑ Back to top](#table-of-contents)

---

## 5. Financial Performance

| Item | Approved budget ($) | Actual spend ($) | Variance ($) | Variance (%) |
|---|---|---|---|---|
| GovTech platform license and configuration (net of CR-003 −$18,000) | 240,000 | 222,000 | +18,000 | +7.5% |
| ICT / LandWorks integration (internal — Tom Okafor) | 48,000 | 48,000 | 0 | 0% |
| Project management (internal — Sarah Chen) | 42,000 | 42,000 | 0 | 0% |
| Training and change (Diane Hughes + materials) | 20,000 | 20,000 | 0 | 0% |
| Content / UX (GovTech + resident research) | 32,000 | 32,000 | 0 | 0% |
| **Subtotal (base scope)** | **382,000** | **364,000** | **+18,000** | **+4.7%** |
| Contingency — drawn for CR-002 (+$7,200) and CR-005 (+$3,600); $27,200 unused | 38,000 | 10,800 | +27,200 | — |
| **Total project** | **420,000** | **374,800** | **+45,200** | **+10.8%** |

**Cost Performance Index (CPI) at closure**: 1.00

**Commentary**: CPI is 1.00 because earned value equals actual cost on the authorized work that was completed ($374,800). The $45,200 difference versus the original $420,000 budget is unused contingency ($27,200) plus the parking-permit scope deferred by CR-003 ($18,000), not a cost-efficiency gain on the work that was done. The largest single driver of that underspend was the CR-003 deferral, which removed $18,000 of GovTech build scope. Of the $38,000 contingency, only $10,800 was drawn — funding the CR-002 LandWorks API uplift ($7,200) and the CR-005 hypercare extension ($3,600) — leaving $27,200 unused. The underspent budget of $45,200 is returned to the Sponsor, with $18,000 of the deferred parking-permit scope earmarked for the Phase 2 business case.

[↑ Back to top](#table-of-contents)

---

## 6. Quality Performance

| Item | Target | Actual | Met? |
|---|---|---|---|
| UAT defect rate at entry (P1/Critical defects) | 0 | 0 | ✅ Yes |
| UAT total defects (medium + low) | ≤60 | 47 | ✅ Yes |
| UAT scenarios signed off by Senior User | 47 | 47/47 | ✅ Yes |
| WCAG 2.1 AA compliance | 100% | 100% | ✅ Yes |
| Security audit (Harbor Payments payment gateway) | Pass | Pass (2 medium findings, resolved) | ✅ Yes |
| PIA compliance | Full sign-off | Signed off May 5, 2026 | ✅ Yes |
| Public-facing uptime (first 2 weeks post-launch) | ≥99.5% | 99.8% | ✅ Yes |
| Staff training completion | 100% of in-scope staff | 54/54 (100%) | ✅ Yes |

**Commentary**: The outcome targets in this table were met. The quality register records a separate miss: none of the three formal audits hit its planned date. The PIA was May 4 (planned May 1), the Harbor Payments audit was July 14 (planned July 10), and the accessibility audit was September 8 (planned September 7). Each was completed, and its findings were closed, before the related gate. The charter measure of at least 30 residents in UAT was not: 12 resident testers took part, and that shortfall is scored under OBJ-05. The two-round accessibility audit approach (initial audit + remediation + re-audit) was absorbed within the existing content/UX budget and was the right decision — the portal launched fully WCAG 2.1 AA compliant, which is both a legal requirement and a reputational imperative for a public-sector service. GovTech's UAT entry quality was good — no critical defects at UAT entry.

[↑ Back to top](#table-of-contents)

---

## 7. Risk and Issue Summary

### Risks

| Total identified | Materialized | Avoided / Expired | Still open at close |
|---|---|---|---|
| 10 (+ 2 opportunities) | 4 (RSK-01 partial, RSK-03, RSK-08, RSK-09) | 3 (RSK-06, RSK-07, RSK-10) | 3 (RSK-02, RSK-04, RSK-05) |

**Key risk events**:
- **RSK-01** (LandWorks integration complexity): Partially materialized — parking permits could not be integrated via standard API. Addressed via CR-003 (deferred to Phase 2). Remaining modules unaffected.
- **RSK-03** (ICT Developer not confirmed): Materialized as ISS-01, raised March 9, 2026. Resolved by Sponsor action (Tom Okafor confirmed March 13, 2026). No schedule impact.
- **RSK-08** (Harbor Payments security certification): Materialized as ISS-04. The audit closed on July 21, 2026 and did not move Gate 2.
- **RSK-09** (extended UAT): Materialized. UAT finished 7 days late and go-live moved to October 8, 2026 (CR-006).

**Risks that expired without occurring**:
- RSK-06: the privacy impact assessment found no blocking issue.
- RSK-07: contingency was not exhausted.
- RSK-10: the Sponsor remained in post through closure.

**Risks remaining open at close** (transferred to Benefits Realization / BAU):
- RSK-02: GovTech ongoing support quality — transferred to ICT for monitoring in Phase 2 and support contract period.
- RSK-04: Staff adoption — now measured as a benefits metric; BCM monitoring for 3 months post-launch.
- RSK-05: Resident adoption — now measured as a benefits metric; comms campaign continues to December 2026.

### Issues

| Total logged | Resolved | Escalated to Sponsor | Unresolved at close |
|---|---|---|---|
| 6 | 6 | 2 (ISS-01, ISS-03) | 0 |

**Commentary**: All six issues were fully resolved before project closure. No unresolved issues are carried forward into BAU.

[↑ Back to top](#table-of-contents)

---

## 8. Benefits Handover

| Ref | Benefit | Baseline (pre-project) | Current measure (end-Oct 2026) | Expected full realization | Benefit owner (BAU) |
|---|---|---|---|---|---|
| BEN-01 | Reduction in contact-center volume for in-scope services | 14,200 inquiries per year | Not yet annualized (portal live 23 days) | April 2027 (55% deflection; about 6,390 inquiries remaining per year) | Sandra Obi, Head of Customer Services |
| BEN-02 | Digital deflection ≥55% of the 14,200 in-scope inquiries | 0% | Not yet measured. Separately, 41% of eligible residents had accessed the portal by October 31, 2026. Access is not deflection. | April 2027 (month 6) | Sandra Obi, Head of Customer Services |
| BEN-03 | Contact-center staff time released | In-scope transactional workload | To be measured at month 6 | 1.8 FTE released by April 2027 | Sandra Obi, Head of Customer Services |
| BEN-04 | Resident satisfaction score ≥75% | Phone service 62% (January 2026). No portal baseline. | 81% from the 12 resident UAT testers (September 2026). Quarterly survey starts January 2027 | Ongoing — measured quarterly | Sandra Obi, Head of Customer Services |
| BEN-05 | Net Cashable Saving (first operational year) | — | — | April 8, 2027 (month 6) | James Hartley, Sponsor |
| BEN-06 | Officer time per in-scope transaction ≤5 minutes | 12 minutes per phone inquiry (March 2026) | Not yet measured | April 8, 2027 | Sandra Obi, Head of Customer Services |
| BEN-07 | WCAG 2.1 AA compliance, with ongoing accessibility feedback | No accessible online channel | WCAG 2.1 AA confirmed September 25, 2026 | At launch and ongoing | Sandra Obi, Head of Customer Services |

**Post-project benefits review date**: April 28, 2027 (Post-Implementation Review)

**Benefits owner accepting responsibility at close**: Sandra Obi, Head of Customer Services

[↑ Back to top](#table-of-contents)

---

## 9. Handover to BAU

| Item | Status | Notes |
|---|---|---|
| Operational documentation complete | ✅ Yes | System admin guide, user guides, and troubleshooting guide — all delivered to ICT (Tom Okafor) and GovTech support team |
| Staff training complete | ✅ Yes | 54 staff trained; training materials archived in SharePoint |
| Support arrangements in place | ✅ Yes | GovTech Level 1/2 support contract live from October 8, 2026; ICT (Tom Okafor) retains Level 3 technical responsibility |
| Service desk / helpdesk briefed | ✅ Yes | City ICT helpdesk briefed October 8, 2026; GovTech support portal access confirmed |
| Acceptance signed by operations | ✅ Yes | Sandra Obi signed operational acceptance October 7, 2026 |
| Benefits owner confirmed | ✅ Yes | Sandra Obi confirmed as benefits owner; PIR scheduled April 2027 |
| Phase 2 handover brief prepared | ✅ Yes | Parking permit module brief prepared for Phase 2 planning; includes LandWorks technical findings and CR-003 documentation |

[↑ Back to top](#table-of-contents)

---

## 10. Lessons Learned Summary

*Top 5 lessons from the project (full log in [examples/15-lessons-learned-log.md](15-lessons-learned-log.md)):*

| # | Lesson | Category | Recommendation |
|---|---|---|---|
| 1 | ICT resource commitments were not named in the project charter, causing a near-miss on integration resource | Resource / team management | Named resource commitment section must be included in all project charters; signed by relevant line manager |
| 2 | BCM not confirmed until April 22, 2026 (the project's third month) — staff engagement unmanaged during design phase | Organizational change management | BCM confirmation should be a Gate 0 condition for projects with significant staff behavior change requirements |
| 3 | LandWorks API limitations were not validated before business case finalization | Technical / technology | Technical spike (proof-of-concept API test) must be completed before business case sign-off for all LandWorks-dependent projects |
| 4 | Benefits baseline measures were not established at project initiation | Project closure / benefits | Benefits register with baseline measures must be completed at initiation stage — before any activity that might affect the baseline |
| 5 | The 13 days after UAT were already planned for training and cutover. UAT finished 7 days late, so go-live moved 7 days, to October 8 | Schedule management | Name the activities inside a gap. If they stay, a late UAT finish moves go-live by the same number of days |

**Lessons submitted to PMO**: Yes — October 31, 2026.

[↑ Back to top](#table-of-contents)

---

## 11. Project Archive

| Item | Location | Archived by | Date |
|---|---|---|---|
| Project Management Plan (all versions) | City of Northgate SharePoint: Meridian/Project Documents | Sarah Chen | October 28, 2026 |
| Risk Register (final v2.3) | City of Northgate SharePoint: Meridian/Risk and Issues | Sarah Chen | October 28, 2026 |
| Change Log (final v1.5) | City of Northgate SharePoint: Meridian/Change Control | Sarah Chen | October 28, 2026 |
| Issue log (snapshot v1.4, August 14, 2026; ISS-06 closed August 25) | City of Northgate SharePoint: Meridian/Risk and Issues | Sarah Chen | October 28, 2026 |
| All signed contracts (GovTech, Harbor Payments) | City of Northgate SharePoint: Meridian/Contracts | Sarah Chen / Legal | October 28, 2026 |
| Lessons Learned Log (final) | City of Northgate SharePoint: Meridian/Lessons / PMO Knowledge Base | Sarah Chen | October 31, 2026 |
| All deliverables (portal documentation, PIA, audits) | City of Northgate SharePoint: Meridian/Deliverables | Sarah Chen | October 28, 2026 |
| Gate review records | City of Northgate SharePoint: Meridian/Governance | Sarah Chen | October 28, 2026 |

[↑ Back to top](#table-of-contents)

---

## 12. Recommendation

The Meridian Citizen Self-Service Portal project is recommended for **formal closure**.

All deliverables have been completed and accepted. All issues are resolved. The portal is live and operating within agreed performance parameters. Benefits ownership has been formally transferred to Sandra Obi (Head of Customer Services). A Post-Implementation Review is scheduled for April 28, 2027.

The parking permit module (CR-003) has been documented as a defined scope item for Phase 2, with the LandWorks technical findings and recommended approach available to the Phase 2 project team.

The project should be archived in accordance with the City's records management policy. All project resources are formally released as of October 31, 2026.

[↑ Back to top](#table-of-contents)

---

## Authorization

| Role | Name | Signed | Date |
|---|---|---|---|
| Project Sponsor / Senior Responsible Owner | James Hartley, Director of Digital Services | *(signed)* | October 31, 2026 |
| Senior User | Sandra Obi, Head of Customer Services | *(signed)* | October 31, 2026 |
| Project Manager | Sarah Chen | *(signed)* | October 31, 2026 |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

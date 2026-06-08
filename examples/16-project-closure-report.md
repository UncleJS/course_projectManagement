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
- [Authorisation](#authorisation)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Project Reference** | NGL-2026-DIG-01 |
| **Version** | 1.0 (Final) |
| **Date** | 31 October 2026 |
| **Prepared by** | Sarah Chen, Project Manager |
| **Approved by** | James Hartley, Project Sponsor |

[↑ Back to top](#table-of-contents)

---

## 1. Executive Summary

The Meridian Citizen Self-Service Portal was delivered within budget and closed on its baseline date. The portal went live on 15 October 2026 — two weeks later than the original 1 October target, but within the overall schedule to formal closure — enabling Northgate District Council residents to track planning applications, report missed waste collections, check council tax accounts, and renew garden waste subscriptions online without visiting or calling the Council.

**Budget**: £420,000 approved; £374,800 actual spend (£45,200 underspend, 10.8%) — driven by the CR-003 parking-permit scope reduction (£18,000) and unused contingency (£27,200).
**Schedule**: Original planned go-live 1 October 2026; actual go-live 15 October 2026 (+14 days). The slip was contained within the schedule to formal closure, which remained on 31 October 2026 as baselined.
**Scope**: Four service modules delivered (planning, waste, council tax, garden waste). Parking permit module formally deferred to Phase 2 (CR-003, approved July 2026) after a UNIFORM API limitation was identified during integration testing.

Early adoption data (end-October 2026) shows 41% of eligible residents have accessed the portal — ahead of the staged trajectory to reach the 55% target by end-December 2026. The contact-centre call volume reduction benefit is on track to materialise.

The project is recommended for formal closure. Benefits realisation is being handed over to Sandra Obi (Senior User / Head of Customer Services) with a post-implementation review scheduled for April 2027.

[↑ Back to top](#table-of-contents)

---

## 2. Project Overview

| Item | Detail |
|---|---|
| **Project start date** | 3 February 2026 |
| **Original planned end date** | 1 October 2026 (go-live); 31 October 2026 (formal closure) |
| **Actual end date** | 31 October 2026 |
| **Project sponsor** | James Hartley, Director of Digital Services |
| **Project manager** | Sarah Chen |
| **Total approved budget** | £420,000 |
| **Actual final cost** | £374,800 |
| **Underspend** | £45,200 (10.8%) |

[↑ Back to top](#table-of-contents)

---

## 3. Objectives and Deliverables

### Objectives Achievement

| Ref | Objective | Achieved? | Notes |
|---|---|---|---|
| OBJ-01 | Deliver a public-facing self-service portal covering at least four council services | **Fully achieved** | Four modules delivered: planning, waste, council tax, garden waste |
| OBJ-02 | Achieve ≥55% resident adoption within 3 months of go-live | **On track (not yet measurable at closure)** | 41% adoption at end-Oct; 3-month measurement date = 15 Jan 2027. PIR scheduled Apr 2027 will confirm. |
| OBJ-03 | Reduce contact-centre call volume for in-scope services by ≥20% | **On track (not yet measurable at closure)** | Call volume data to be measured at 3 months and 6 months post-go-live. Early indicators positive. |
| OBJ-04 | Deliver within approved budget of £420,000 | **Fully achieved** | Final spend £374,800 — £45,200 underspend |
| OBJ-05 | Achieve full WCAG 2.1 AA accessibility compliance | **Fully achieved** | Accessibility audit completed 26 Sep 2026; all 14 issues resolved; compliance confirmed |
| OBJ-06 | Obtain UK GDPR compliance sign-off from DPO | **Fully achieved** | DPIA signed off by the Data Protection Officer on 5 May 2026; final privacy notice approved before go-live |

### Deliverables

| Ref | Deliverable | Delivered? | Acceptance date | Notes |
|---|---|---|---|---|
| DEL-01 | Discovery Report and UX Design Specification | Yes | 8 May 2026 | Approved at Gate 1 by Senior User and Senior Supplier |
| DEL-02 | Integration Specification | Yes | 8 May 2026 | Approved by ICT Manager (Mark Pearce) at Gate 1 |
| DEL-03 | Data Protection Impact Assessment | Yes | 5 May 2026 | Signed off by the Data Protection Officer |
| DEL-04 | Planning application tracking module (live) | Yes | 15 Oct 2026 | Integration with UNIFORM (planning) — live |
| DEL-05 | Missed waste collection reporting module (live) | Yes | 15 Oct 2026 | Integration with Civica (waste) — live |
| DEL-06 | Council tax account / payment module (live) | Yes | 15 Oct 2026 | Integration with Capita (council tax) — live; security cert obtained Jul 2026 |
| DEL-07 | Garden waste subscription renewal module (live) | Yes | 15 Oct 2026 | Integration with Civica (waste) — live |
| DEL-08 | Parking permit module | **Not delivered (Phase 2)** | — | Deferred via CR-003 (approved 8 Jul 2026) due to UNIFORM API limitation |
| DEL-09 | Accessibility audit report and remediation | Yes | 26 Sep 2026 | All 14 issues resolved; WCAG 2.1 AA compliance confirmed |
| DEL-10 | Staff training programme | Yes | 3 Oct 2026 | 54 staff trained across planning, revenues, and waste services |
| DEL-11 | System administration documentation | Yes | 10 Oct 2026 | Handed over to ICT (Tom Okafor) and GovTech support team |
| DEL-12 | Resident communications campaign | Yes | Sep 2026 | 68% resident awareness pre-launch (target: 50%) |

### Scope Changes

| CR No. | Description | Cost impact (£) | Schedule impact |
|---|---|---|---|
| CR-001 | Welsh language interface deferred to Phase 2 | £0 (deferred; not funded in Phase 1) | None |
| CR-002 | UNIFORM API rate-limit increase to support integration load | +£7,200 (contingency-funded) | None |
| CR-003 | Parking permit module deferred to Phase 2 (UNIFORM API incompatibility) | −£18,000 (removed from build scope) | None — go-live date maintained |
| CR-005 | Hypercare extended from 30 to 45 days | +£3,600 (contingency-funded) | None |
| **Net scope change impact** | | **−£7,200** | **None** |

[↑ Back to top](#table-of-contents)

---

## 4. Schedule Performance

| Item | Baseline | Actual | Variance |
|---|---|---|---|
| Gate 1 (Discovery and Design complete) | 8 May 2026 | 8 May 2026 | **0 days** |
| Gate 2 (Build and Integration complete / UAT entry) | 7 Aug 2026 | 11 Sep 2026 | **+35 days (late)** |
| UAT complete | 19 Sep 2026 | 26 Sep 2026 | **+7 days (late)** |
| Accessibility audit and remediation complete | 3 Oct 2026 | 26 Sep 2026 | **+7 days (early)** |
| Go-live | 1 Oct 2026 | 15 Oct 2026 | **+14 days (late)** |
| Project closure | 31 Oct 2026 | 31 Oct 2026 | **0 days** |

**Schedule Performance Index (SPI) at closure**: 1.00

**Commentary**: The build phase ran over: Gate 2 (build and integration complete) was reached on 11 September 2026, 35 days later than the 7 August baseline, principally due to UNIFORM integration complexity — the parking-permit data limitation (CR-003) and the unplanned Capita payment-gateway security audit (ISS-04). Much of the slip was recovered by compressing the UAT and remediation window, so UAT completed only 7 days late (26 September) and go-live slipped 14 days to 15 October. The slip was contained within the overall schedule to formal closure — which included the hypercare buffer to 31 October — so closure held its baseline date. The SPI of 1.00 reflects completion of all planned scope by closure. The principal lesson (build-phase estimation for legacy-system integration) is captured in the lessons-learned log.

[↑ Back to top](#table-of-contents)

---

## 5. Financial Performance

| Item | Approved budget (£) | Actual spend (£) | Variance (£) | Variance (%) |
|---|---|---|---|---|
| GovTech platform licence and configuration (net of CR-003 −£18,000) | 240,000 | 222,000 | +18,000 | +7.5% |
| ICT / UNIFORM integration (internal — Tom Okafor) | 48,000 | 48,000 | 0 | 0% |
| Project management (internal — Sarah Chen) | 42,000 | 42,000 | 0 | 0% |
| Training and change (Diane Hughes + materials) | 20,000 | 20,000 | 0 | 0% |
| Content / UX (GovTech + resident research) | 32,000 | 32,000 | 0 | 0% |
| **Subtotal (base scope)** | **382,000** | **364,000** | **+18,000** | **+4.7%** |
| Contingency — drawn for CR-002 (+£7,200) and CR-005 (+£3,600); £27,200 unused | 38,000 | 10,800 | +27,200 | — |
| **Total project** | **420,000** | **374,800** | **+45,200** | **+10.8%** |

**Cost Performance Index (CPI) at closure**: 1.02

**Commentary**: The project closed with a £45,200 underspend (10.8%). The largest single driver was the CR-003 parking-permit deferral, which removed ~£18,000 of GovTech build scope. Of the £38,000 contingency, only £10,800 was drawn — funding the CR-002 UNIFORM API uplift (£7,200) and the CR-005 hypercare extension (£3,600) — leaving £27,200 unused. The underspent budget of £45,200 is returned to the Sponsor, with £18,000 of the deferred parking-permit scope earmarked for the Phase 2 business case.

[↑ Back to top](#table-of-contents)

---

## 6. Quality Performance

| Item | Target | Actual | Met? |
|---|---|---|---|
| UAT defect rate at entry (P1/Critical defects) | 0 | 0 | ✅ Yes |
| UAT total defects (medium + low) | ≤60 | 47 | ✅ Yes |
| All UAT acceptance criteria signed off by Senior User | All | All (12/12) | ✅ Yes |
| WCAG 2.1 AA compliance | 100% | 100% | ✅ Yes |
| Security audit (Capita payment gateway) | Pass | Pass (2 minor findings, resolved) | ✅ Yes |
| DPIA compliance | Full sign-off | Signed off 5 May 2026 | ✅ Yes |
| Peer-facing uptime (first 2 weeks post-launch) | ≥99.5% | 99.8% | ✅ Yes |
| Staff training completion | 100% of in-scope staff | 54/54 (100%) | ✅ Yes |

**Commentary**: All quality targets were met. The two-round accessibility audit approach (initial audit + remediation + re-audit) was absorbed within the existing content/UX budget and was the right decision — the portal launched fully WCAG 2.1 AA compliant, which is both a legal requirement and a reputational imperative for a public-sector service. GovTech's UAT entry quality was good — no critical defects at UAT entry.

[↑ Back to top](#table-of-contents)

---

## 7. Risk and Issue Summary

### Risks

| Total identified | Materialised | Avoided / Expired | Still open at close |
|---|---|---|---|
| 10 (+ 2 opportunities) | 2 (RSK-01 partial, RSK-03) | 5 | 3 (RSK-02, RSK-04, RSK-05) |

**Key risk events**:
- **RSK-01** (UNIFORM integration complexity): Partially materialised — parking permits could not be integrated via standard API. Addressed via CR-003 (deferred to Phase 2). Remaining modules unaffected.
- **RSK-03** (ICT Developer not confirmed): Materialised as ISS-01 in February 2026. Resolved within 2 weeks by Sponsor action (Tom Okafor confirmed 13 March 2026). No schedule impact.

**Risks remaining open at close** (transferred to Benefits Realisation / BAU):
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

| Ref | Benefit | Baseline (pre-project) | Current measure (end-Oct 2026) | Expected full realisation | Benefit owner (BAU) |
|---|---|---|---|---|---|
| BEN-01 | Reduction in contact-centre call volume for in-scope services | 4,200 calls/month (reconstructed from 12-month average) | 3,800 calls/month (Oct 2026 — first month post-go-live) | June 2027 (steady state) | Sandra Obi, Head of Customer Services |
| BEN-02 | Resident adoption rate ≥55% | 0% | 41% (end-Oct 2026, 2 weeks post-launch) | 15 January 2027 (3-month milestone) | Sandra Obi, Head of Customer Services |
| BEN-03 | Contact-centre staff time savings (FTE equivalent) | 1.4 FTE on in-scope queries | To be measured at 3 months | June 2027 | Mark Pearce, ICT / Operations Manager |
| BEN-04 | Resident satisfaction score ≥75% | No baseline (new channel) | 81% satisfaction in exit survey (UAT pilot residents) | Ongoing — measured quarterly | Sandra Obi, Head of Customer Services |
| BEN-05 | Net Cashable Saving (Year 1) | — | — | March 2027 (year-end) | James Hartley, Sponsor |

**Post-project benefits review date**: 28 April 2027 (Post-Implementation Review)

**Benefits owner accepting responsibility at close**: Sandra Obi, Head of Customer Services

[↑ Back to top](#table-of-contents)

---

## 9. Handover to BAU

| Item | Status | Notes |
|---|---|---|
| Operational documentation complete | ✅ Yes | System admin guide, user guides, and troubleshooting guide — all delivered to ICT (Tom Okafor) and GovTech support team |
| Staff training complete | ✅ Yes | 54 staff trained; training materials archived in SharePoint |
| Support arrangements in place | ✅ Yes | GovTech Level 1/2 support contract live from 15 Oct 2026; ICT (Tom Okafor) retains Level 3 technical responsibility |
| Service desk / helpdesk briefed | ✅ Yes | Council ICT helpdesk briefed 8 Oct 2026; GovTech support portal access confirmed |
| Acceptance signed by operations | ✅ Yes | Sandra Obi signed operational acceptance 14 Oct 2026 |
| Benefits owner confirmed | ✅ Yes | Sandra Obi confirmed as benefits owner; PIR scheduled April 2027 |
| Phase 2 handover brief prepared | ✅ Yes | Parking permit module brief prepared for Phase 2 planning; includes UNIFORM technical findings and CR-003 documentation |

[↑ Back to top](#table-of-contents)

---

## 10. Lessons Learned Summary

*Top 5 lessons from the project (full log in [examples/15-lessons-learned-log.md](15-lessons-learned-log.md)):*

| # | Lesson | Category | Recommendation |
|---|---|---|---|
| 1 | ICT resource commitments were not named in the project charter, causing a near-miss on integration resource | Resource / team management | Named resource commitment section must be included in all project charters; signed by relevant line manager |
| 2 | BCM not confirmed until Month 3 — staff engagement unmanaged during design phase | Organisational change management | BCM confirmation should be a Gate 0 condition for projects with significant staff behaviour change requirements |
| 3 | UNIFORM API limitations were not validated before business case finalisation | Technical / technology | Technical spike (proof-of-concept API test) must be completed before business case sign-off for all UNIFORM-dependent projects |
| 4 | Benefits baseline measures were not established at project initiation | Project closure / benefits | Benefits register with baseline measures must be completed at initiation stage — before any activity that might affect the baseline |
| 5 | 2-week schedule float between UAT and go-live was essential — and almost removed during planning | Schedule management | PMs should justify schedule float with comparable project data; Sponsors should not remove it without evidence it is unnecessary |

**Lessons submitted to PMO**: Yes — 31 October 2026.

[↑ Back to top](#table-of-contents)

---

## 11. Project Archive

| Item | Location | Archived by | Date |
|---|---|---|---|
| Project Management Plan (all versions) | NDA SharePoint: Meridian/Project Documents | Sarah Chen | 28 Oct 2026 |
| Risk Register (final v2.3) | NDA SharePoint: Meridian/Risk and Issues | Sarah Chen | 28 Oct 2026 |
| Change Log (final v1.5) | NDA SharePoint: Meridian/Change Control | Sarah Chen | 28 Oct 2026 |
| Issue Log (final v1.4) | NDA SharePoint: Meridian/Risk and Issues | Sarah Chen | 28 Oct 2026 |
| All signed contracts (GovTech, Capita) | NDA SharePoint: Meridian/Contracts | Sarah Chen / Legal | 28 Oct 2026 |
| Lessons Learned Log (final) | NDA SharePoint: Meridian/Lessons / PMO Knowledge Base | Sarah Chen | 31 Oct 2026 |
| All deliverables (portal documentation, DPIA, audits) | NDA SharePoint: Meridian/Deliverables | Sarah Chen | 28 Oct 2026 |
| Gate review records | NDA SharePoint: Meridian/Governance | Sarah Chen | 28 Oct 2026 |

[↑ Back to top](#table-of-contents)

---

## 12. Recommendation

The Meridian Citizen Self-Service Portal project is recommended for **formal closure**.

All deliverables have been completed and accepted. All issues are resolved. The portal is live and operating within agreed performance parameters. Benefits ownership has been formally transferred to Sandra Obi (Head of Customer Services). A Post-Implementation Review is scheduled for 28 April 2027.

The parking permit module (CR-003) has been documented as a defined scope item for Phase 2, with the UNIFORM technical findings and recommended approach available to the Phase 2 project team.

The project should be archived in accordance with the Council's records management policy. All project resources are formally released as of 31 October 2026.

[↑ Back to top](#table-of-contents)

---

## Authorisation

| Role | Name | Signed | Date |
|---|---|---|---|
| Project Sponsor | James Hartley, Director of Digital Services | *(signed)* | 31 Oct 2026 |
| Senior Responsible Owner / Senior User | Sandra Obi, Head of Customer Services | *(signed)* | 31 Oct 2026 |
| Project Manager | Sarah Chen | *(signed)* | 31 Oct 2026 |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Worked Example: Resource Calendar
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Resource%20Calendar-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/resource-calendar.md`](../templates/resource-calendar.md) | **Module:** [14 — Resource & Team Management](../modules/14-resource-team.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Resource Profiles](#resource-profiles)
- [Availability Calendar](#availability-calendar)
- [Resource Notes](#resource-notes)
- [Consolidated Resource Demand vs Availability](#consolidated-resource-demand-vs-availability)
- [Known Absences and Constraints](#known-absences-and-constraints)
- [Resource Levelling Actions](#resource-levelling-actions)
- [Key Capacity Risks](#key-capacity-risks)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.0 |
| **Date** | 20 February 2026 |
| **Owner** | Sarah Chen, Project Manager |

[↑ Back to top](#table-of-contents)

---

## Resource Profiles

| Resource | Role | Type | FTE or Days/Week |
|---|---|---|---|
| Sarah Chen | Project Manager | Internal — Council | 0.6 FTE (3 days/week) |
| Mark Pearce | ICT Manager / Senior Supplier | Internal — Council | 0.1 FTE (0.5 days/week); peaks to 0.4 FTE in integration phase |
| ICT Developer (TBC) | UNIFORM Integration Developer | Internal — Council | 0.4 FTE during integration phase (Jun–Aug only) |
| Sandra Obi | Head of Customer Services / Senior User | Internal — Council | 0.1 FTE (occasional; UAT involvement increases to 0.3 FTE in Sep) |
| GovTech Project Lead | Supplier PM | External — GovTech | As per contract; GovTech resource |
| GovTech Development Team | Portal build and integration (supplier) | External — GovTech | As per contract; GovTech resource |
| Business Change Manager (TBC) | Change and comms | Internal — Council (TBC hire/assign) | 0.3 FTE from May 2026 |

[↑ Back to top](#table-of-contents)

---

## Availability Calendar

*Internal council resources. Key: percentage = % of working week available to this project. Shaded cells = peak demand.*

| Resource | Feb 26 | Mar 26 | Apr 26 | May 26 | Jun 26 | Jul 26 | Aug 26 | Sep 26 | Oct 26 |
|---|---|---|---|---|---|---|---|---|---|
| **Sarah Chen** (PM) | 60% | 60% | 60% | 60% | 60% | 60% | 60% | 80% | 40% |
| **Mark Pearce** (ICT) | 10% | 10% | 10% | 20% | **40%** | **40%** | **40%** | 20% | 10% |
| **ICT Developer** | — | — | — | — | **80%** | **80%** | **80%** | 20% | — |
| **Sandra Obi** (Senior User) | 10% | 10% | 20% | 10% | 10% | 10% | 5% | **40%** | 10% |
| **Business Change Manager** | — | — | — | 30% | 30% | 30% | 30% | **60%** | 30% |

[↑ Back to top](#table-of-contents)

---

## Resource Notes

**Sarah Chen — Project Manager**
- Increases to 80% in September 2026 to support UAT and go-live preparation.
- Reduces to 40% in October 2026 for closure activities.
- Unavailable: 27 April – 1 May 2026 (annual leave).

**Mark Pearce — ICT Manager**
- Only 10% available for most phases (senior management role; cannot be dedicated).
- Critical involvement in June–August 2026 for integration oversight.
- Integration Developer from ICT team will handle day-to-day technical work.
- Risk: ICT team has other council priorities; this availability is not yet formally ring-fenced. See RSK-03.

**ICT Integration Developer**
- Not yet identified by name (Mark Pearce to assign by 1 March 2026).
- Required from 1 June 2026. Risk if not confirmed by 1 April 2026.

**Sandra Obi — Senior User**
- Available only on a part-time basis throughout; manages a 12-person contact centre team.
- Key involvement: April (requirements review), August–September (UAT preparation and sign-off).
- Unavailable: 1–19 August 2026 (pre-booked annual leave — noted risk to UAT start date).

**Business Change Manager**
- Role not yet filled (as at project start).
- Must be in post by 1 May 2026 to run staff engagement activities ahead of UAT.
- Sarah Chen acting as interim for change coordination until BCM is confirmed.

[↑ Back to top](#table-of-contents)

---

## Consolidated Resource Demand vs Availability

*Peak-demand months and utilisation for the internal council resources (the supplier team is contracted separately).*

| Resource | Peak demand period | Availability at peak | Status |
|---|---|---|---|
| Mark Pearce (ICT) | Jun–Aug 2026 (integration oversight) | 40% | 🟡 At ceiling — senior role cannot exceed 40% |
| ICT Developer | Jun–Aug 2026 (integration build) | 80% | 🟢 Within capacity once confirmed |
| Sandra Obi (Senior User) | Sep 2026 (UAT and sign-off) | 40% | 🟡 Constrained by August leave |
| Business Change Manager | Sep 2026 (go-live engagement) | 60% | 🟢 Within capacity |

**Colour code**: 🟢 Within capacity | 🟡 ≥90% utilised | 🔴 Overallocated

[↑ Back to top](#table-of-contents)

---

## Known Absences and Constraints

| Name | Period | Type | Hours affected per week | Impact on plan |
|---|---|---|---|---|
| Sarah Chen | 27 Apr – 1 May 2026 | Annual leave | Full week | Minor — no critical-path activity that week |
| Sandra Obi | 1–19 Aug 2026 | Annual leave | ~3 weeks | UAT preparation at risk; mitigated by July checklist and deputy (ISS-05) |
| ICT Developer | Until assigned (target 1 Mar 2026) | Resource gap | Full | Integration cannot start in June if unconfirmed (RSK-03 / ISS-01) |
| Mark Pearce | Throughout | Other commitment (senior management role) | ~90% | Capped at 40% even at peak; day-to-day work delegated to ICT Developer |

[↑ Back to top](#table-of-contents)

---

## Resource Levelling Actions

| Date | Name | Conflict identified | Resolution action | Impact on schedule |
|---|---|---|---|---|
| 8 Mar 2026 | ICT Developer | Named developer not confirmed for June integration start | Sponsor escalation; Tom Okafor confirmed 13 Mar (ISS-01) | None — resolved before integration start |
| 3 Aug 2026 | Sandra Obi | August leave overlaps UAT preparation | UAT prep checklist completed by 31 Jul; deputy briefed; tasks reassigned to BCM (ISS-05) | None — UAT start maintained 22 Aug |

[↑ Back to top](#table-of-contents)

---

## Key Capacity Risks

| Risk | Implication | Mitigation |
|---|---|---|
| ICT Developer not identified by 1 April | Integration work cannot start on schedule in June | Mark Pearce to confirm name and allocation by 1 March; tracked in risk register |
| Sandra Obi unavailable for first 3 weeks of August | UAT preparation delayed | UAT prep checklist completed by July 31; Sandra deputy briefed to support |
| BCM not in post by May | Staff engagement activities delayed | Sarah Chen escalates to HR by 1 March; interim arrangements agreed with sponsor |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

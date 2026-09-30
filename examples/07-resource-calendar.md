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
- [Resource Leveling Actions](#resource-leveling-actions)
- [Key Capacity Risks](#key-capacity-risks)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.0 |
| **Date** | February 20, 2026 |
| **Owner** | Sarah Chen, Project Manager |

[↑ Back to top](#table-of-contents)

---

## Resource Profiles

| Resource | Role | Type | FTE or Days/Week |
|---|---|---|---|
| Sarah Chen | Project Manager | Internal — City | 0.6 FTE (3 days/week) |
| Mark Pearce | ICT Manager / Senior Supplier | Internal — City | 0.1 FTE (0.5 days/week); peaks to 0.4 FTE in integration phase |
| ICT Developer (TBC) | LandWorks Integration Developer | Internal — City | 0.4 FTE during integration phase (Jun–Aug only) |
| Sandra Obi | Head of Customer Services / Senior User | Internal — City | 0.1 FTE (occasional; UAT involvement increases to 0.3 FTE in Sep) |
| GovTech Project Lead | Supplier PM | External — GovTech | As per contract; GovTech resource |
| GovTech Development Team | Portal build and integration (supplier) | External — GovTech | As per contract; GovTech resource |
| Business Change Manager (TBC) | Change and comms | Internal — City (TBC hire/assign) | 0.3 FTE from May 2026 |

[↑ Back to top](#table-of-contents)

---

## Availability Calendar

*Internal city resources. Key: percentage = % of working week available to this project. Shaded cells = peak demand.*

| Resource | Feb 26 | Mar 26 | Apr 26 | May 26 | Jun 26 | Jul 26 | Aug 26 | Sep 26 | Oct 26 |
|---|---|---|---|---|---|---|---|---|---|
| **Sarah Chen** (PM) | 60% | 60% | 60% | 60% | 60% | 60% | 60% | 80% | 40% |
| **Mark Pearce** (ICT) | 10% | 10% | 10% | 20% | **40%** | **40%** | **40%** | 20% | 10% |
| **ICT Developer** | — | — | — | — | **40%** | **40%** | **40%** | — | — |
| **Sandra Obi** (Senior User) | 10% | 10% | 20% | 10% | 10% | 10% | 5% | **40%** | 10% |
| **Business Change Manager** | — | — | — | 30% | 30% | 30% | 30% | **60%** | 30% |

[↑ Back to top](#table-of-contents)

---

## Resource Notes

**Sarah Chen — Project Manager**
- Increases to 80% in September 2026 to support UAT and go-live preparation.
- Reduces to 40% in October 2026 for closure activities.
- Unavailable: April 27 – May 1, 2026 (annual leave).

**Mark Pearce — ICT Manager**
- Only 10% available for most phases (senior management role; cannot be dedicated).
- Critical involvement in June–August 2026 for integration oversight.
- Integration Developer from ICT team will handle day-to-day technical work.
- Risk: ICT team has other city priorities; this availability is not yet formally ring-fenced. See RSK-03.

**ICT Integration Developer**
- Not yet identified by name (Mark Pearce to assign by March 2, 2026).
- Required from June 1, 2026. Risk if not confirmed by April 1, 2026.

**Sandra Obi — Senior User**
- Available only on a part-time basis throughout. She is accountable for the 12-person contact center team, which Ayo Mensah leads.
- Key involvement: April (requirements review), August–September (UAT preparation and sign-off).
- Unavailable: August 3–18, 2026 (pre-booked annual leave). Returns August 19. Noted risk to the UAT start date.

**Business Change Manager**
- Role not yet filled (as at project start).
- Must be in post by May 1, 2026 to run staff engagement activities ahead of UAT.
- Sarah Chen acting as interim for change coordination until BCM is confirmed.

[↑ Back to top](#table-of-contents)

---

## Consolidated Resource Demand vs Availability

*Peak-demand months and utilization for the internal city resources (the supplier team is contracted separately).*

| Resource | Peak demand period | Availability at peak | Status |
|---|---|---|---|
| Mark Pearce (ICT) | Jun–Aug 2026 (integration oversight) | 40% | 🟡 At ceiling — senior role cannot exceed 40% |
| ICT Developer | Jun–Aug 2026 (integration build) | 40% (0.4 FTE) | 🟢 Within capacity once confirmed |
| Sandra Obi (Senior User) | Sep 2026 (UAT and sign-off) | 40% | 🟡 Constrained by August leave |
| Business Change Manager | Sep 2026 (go-live engagement) | 60% | 🟢 Within capacity |

**Color code**: 🟢 Within capacity | 🟡 ≥90% utilized | 🔴 Overallocated

[↑ Back to top](#table-of-contents)

---

## Known Absences and Constraints

| Name | Period | Type | Hours affected per week | Impact on plan |
|---|---|---|---|---|
| Sarah Chen | April 27 – May 1, 2026 | Annual leave | Full week | Minor — no critical-path activity that week |
| Sandra Obi | August 3–18, 2026 | Annual leave | 12 working days | UAT preparation at risk. Checklist and a deputy are to be arranged before the leave. She returns August 19. UAT start stays August 24. |
| ICT Developer | Until assigned (target March 2, 2026) | Resource gap | Full | Integration cannot start in June if the developer is still unconfirmed (RSK-03) |
| Mark Pearce | Throughout | Other commitment (senior management role) | ~90% | Capped at 40% even at peak; day-to-day work delegated to ICT Developer |

[↑ Back to top](#table-of-contents)

---

## Resource Leveling Actions

| Date | Name | Conflict identified | Resolution action | Impact on schedule |
|---|---|---|---|---|
| Target March 2, 2026 | ICT Developer | Named developer not yet confirmed for the June integration start | Mark Pearce to name the developer by March 2. The Sponsor escalates if that date is missed | Open at this baseline |
| Before August 3, 2026 | Sandra Obi | August 3–18 leave overlaps UAT preparation | Complete the UAT prep checklist before the leave and brief a deputy | Planned. She returns August 19. UAT start remains August 24 |

[↑ Back to top](#table-of-contents)

---

## Key Capacity Risks

| Risk | Implication | Mitigation |
|---|---|---|
| ICT Developer not identified by April 1 | Integration work cannot start on schedule in June | Mark Pearce to confirm name and allocation by March 2; tracked in risk register |
| Sandra Obi unavailable for the first 3 weeks of August | UAT preparation delayed | UAT prep checklist to be completed before July 31; a deputy to be briefed |
| BCM not in post by May | Staff engagement activities delayed | Sarah Chen escalates to HR by March 2; interim arrangements agreed with sponsor |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

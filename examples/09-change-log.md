# Worked Example: Change Log
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Change%20Log-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/change-log.md`](../templates/change-log.md) | **Module:** [05 — Project Execution](../modules/05-execution.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Change Log](#change-log)
- [Decision Values](#decision-values)
- [Implementation Status Values](#implementation-status-values)
- [Cumulative Impact Summary](#cumulative-impact-summary)
  - [Contingency Tracking (as at August 15, 2026)](#contingency-tracking-as-at-august-15-2026)
- [Notes](#notes)
- [Closure addendum: CR-006](#closure-addendum-cr-006)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.3, with a closure addendum |
| **Date** | August 15, 2026. The addendum is dated October 31, 2026. |
| **Owner** | Sarah Chen, Project Manager |

> **Snapshot.** The log and the cumulative totals below are the position on August 15, 2026. CR-006 was not known then. It is recorded in the closure addendum. It has no cost, so the contingency totals do not change.

[↑ Back to top](#table-of-contents)

---

## Change Log

| CR No. | Date submitted | Submitted by | Description | Baselines affected | Cost impact ($) | Schedule impact | Priority | Decision | Decision by | Decision date | Implementation status | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CR-001 | May 22, 2026 | Sandra Obi | Add Spanish language option to all four service modules | Scope | $0 (this project) | None | Could | Deferred | James Hartley | June 4, 2026 | Deferred | Deferred to Phase 2 (Q1 2027) |
| CR-002 | June 12, 2026 | Mark Pearce | Increase LandWorks API rate limit from 100 to 500 requests/minute to support peak load; requires additional ICT infrastructure work | Cost, Schedule | +$7,200 (from contingency) | +5 days in integration (absorbed) | Must | Approved | James Hartley (Sponsor; cost change within $20,000) | June 19, 2026 | Implemented | Implemented July 14, 2026 |
| CR-003 | July 1, 2026 | Tom Okafor | Remove parking permit renewal module from Phase 1 (LandWorks data incompatibility found in integration testing); defer to Phase 2 | Scope, Cost | −$18,000 (released from GovTech contract) | None — go-live date maintained | Must | Approved | James Hartley (Sponsor; cost change within $20,000) | July 8, 2026 | Implemented | Base-scope saving; deferred to Phase 2 |
| CR-004 | July 29, 2026 | Councilmember Patricia Dean (via Sponsor) | Add a "Report a Pothole" feature to the portal before go-live | Scope, Schedule | N/A | Would delay go-live by 6–8 weeks | Could | Rejected | James Hartley | August 5, 2026 | Rejected | Scope creep; rejected to protect the fixed go-live date |
| CR-005 | August 10, 2026 | Sarah Chen | Extend hypercare support from 30 to 45 days due to property tax module complexity | Cost | +$3,600 (from contingency) | None | Should | Approved | James Hartley | August 14, 2026 | Approved — pending implementation | 45 days from the planned October 1, 2026 go-live (through November 15, 2026). If go-live later moves, the 45 days run from the actual date. Formal closure stays October 31, 2026. |

[↑ Back to top](#table-of-contents)

---

## Decision Values

| Decision | Meaning |
|---|---|
| **Approved** | Change approved as submitted; baselines updated |
| **Approved with modification** | Change approved with amendments; see notes |
| **Rejected** | Change not approved; project continues as planned |
| **Deferred** | Decision postponed or change moved to a future phase |
| **Withdrawn** | Requestor withdrew the change request |

[↑ Back to top](#table-of-contents)

---

## Implementation Status Values

| Status | Meaning |
|---|---|
| Pending decision | Awaiting Change Control Board / sponsor review |
| Approved — pending implementation | Decision made; implementation not yet complete |
| Implemented | Change has been implemented; baselines updated |
| Rejected | No action required |
| Deferred | On hold / moved to a future phase |

[↑ Back to top](#table-of-contents)

---

## Cumulative Impact Summary

*Cumulative effect of all approved changes, as at August 15, 2026.*

| Metric | Approved baseline | Total approved changes | Revised baseline |
|---|---|---|---|
| **Budget** | $420,000 | net −$7,200 scope (CR-002 +$7,200, CR-003 −$18,000, CR-005 +$3,600) — funded within contingency | $420,000 ceiling unchanged |
| **End date** | October 31, 2026 (closure) | 0 days. Go-live is still October 1, 2026 at this snapshot. | October 31, 2026 |
| **Scope items added** | — | CR-002 API rate-limit uplift; CR-005 hypercare extension | — |
| **Scope items removed** | — | CR-003 parking permit (→ Phase 2); CR-001 Spanish language (→ Phase 2) | — |

### Contingency Tracking (as at August 15, 2026)

| Item | Amount ($) |
|---|---|
| Original contingency | 38,000 |
| CR-002 drawdown (LandWorks API uplift) | -7,200 |
| CR-005 drawdown (hypercare extension) | -3,600 |
| **Remaining contingency** | **27,200** |
| CR-003 base-scope saving (parking permit deferral) | +18,000 |
| **Total budget released vs $420,000** | **45,200** |

> Note: The CR-002 and CR-005 additions were funded from the $38,000 contingency, leaving $27,200 unused. CR-003 saved a separate $18,000 from the GovTech build contract (parking permit module deferred) — this is a base-scope saving, kept distinct from contingency, and earmarked for the Phase 2 business case rather than returned to the general capital program. Total released against the $420,000 budget is therefore $45,200.

[↑ Back to top](#table-of-contents)

---

## Notes

**CR-003** (Parking Permit Deferral) is the most significant change on this project. It was discovered during integration testing that the LandWorks system does not hold parking permit expiry data in a queryable format — it is stored as a scanned PDF attachment. Extracting this data would require significant LandWorks system changes outside project scope. The decision to defer rather than attempt a workaround was correct and protected the go-live date.

**CR-004** (Pothole reporting) is a good example of scope creep from a senior stakeholder. Despite coming via the Sponsor, the change was correctly assessed and rejected because it would have endangered the fixed go-live date (CON-02) and was outside the scope of the business case.

[↑ Back to top](#table-of-contents)

---

## Closure addendum: CR-006

*Added October 31, 2026. This row is not part of the August 15 snapshot.*

| CR No. | Date submitted | Submitted by | Description | Baselines affected | Cost impact ($) | Schedule impact | Priority | Decision | Decision by | Decision date | Implementation status | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| CR-006 | September 28, 2026 | Sarah Chen | Move go-live from October 1, 2026 to October 8, 2026. Raised as an exception report to the Sponsor. | Schedule | $0 | Go-live +7 days. Formal closure stays October 31, 2026. | Must | Approved | James Hartley (Sponsor / Executive) | September 30, 2026 | Implemented | UAT finished September 25. The plan kept 13 days after UAT for training and cutover, so that gap, counted from September 25, ends October 8. Training sign-off moved from September 25 to October 2. Production readiness passed October 7. A zero-cost change is normally approved by the PM. This one moves the charter go-live date, which requires Executive approval. Hypercare stays 45 days from the actual go-live, through November 22, 2026. |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

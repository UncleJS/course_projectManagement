# Worked Example: Issue Log
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Issue%20Log-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/issue-log.md`](../templates/issue-log.md) | **Module:** [05 — Project Execution](../modules/05-execution.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Issue Severity](#issue-severity)
- [Issue Types](#issue-types)
- [Issue Log](#issue-log)
- [Status Values](#status-values)
- [Escalation Path](#escalation-path)
- [Relationship to Risk Register](#relationship-to-risk-register)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.4 |
| **Date** | August 14, 2026 |
| **Owner** | Sarah Chen, Project Manager |
| **Review frequency** | Weekly at team meeting; immediately for Critical issues |

> **Note:** This is a mid-project snapshot (Version 1.4, August 14, 2026). ISS-06 was open at this date. The fix was deployed August 24 and the re-test was confirmed August 25, before project closure. At closure all six issues are recorded as resolved.

[↑ Back to top](#table-of-contents)

---

## Issue Severity

| Severity | Description | Required response time |
|---|---|---|
| **Critical** | Threatens the go-live date, a Gate review, or the business case; requires immediate escalation to Sponsor | Same day |
| **High** | Significant impact on a key deliverable or milestone; likely to affect schedule or cost; requires PM action | Within 2 working days |
| **Medium** | Moderate impact; manageable within project resources | Within 5 working days |
| **Low** | Minor impact; can be addressed in the normal course of work | Within 10 working days |

[↑ Back to top](#table-of-contents)

---

## Issue Types

| Type | Description |
|---|---|
| **Problem** | Something has gone wrong that needs fixing |
| **Concern** | A potential issue if action is not taken soon |
| **Question** | A matter requiring a decision to unblock work |
| **Request** | A request for clarification, resource, or action |

[↑ Back to top](#table-of-contents)

---

## Issue Log

| ID | Date raised | Raised by | Issue title | Description | Type | Severity | Impact on project | Owner | Target resolution date | Actions taken | Status | Date closed |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| ISS-01 | March 9, 2026 | Sarah Chen | ICT Developer not named | Resource gap for the integration phase — named developer not yet confirmed | Problem | **High** | Integration phase cannot start on time (June 2026) if resource not confirmed | Mark Pearce | April 1, 2026 | (1) Escalated to Sponsor March 10; (2) Mark Pearce asked to confirm by March 16; (3) Tom Okafor confirmed as ICT Developer March 13 | **Closed** | March 13, 2026 |
| ISS-02 | April 6, 2026 | Mark Pearce | Business Change Manager role not filled | No one owning staff engagement and training readiness | Problem | **High** | Staff resistance unmanaged; training delivery at risk | Sarah Chen / HR | May 1, 2026 | (1) Escalated to Sponsor April 7; (2) Internal redeployment agreed — Diane Hughes confirmed as Business Change Manager April 22 | **Closed** | April 22, 2026 |
| ISS-03 | June 17, 2026 | Tom Okafor | LandWorks parking permit data not queryable | LandWorks API exposes parking permit expiry only as a scanned PDF, not as queryable data | Problem | **Critical** | Parking permit module cannot be built as specified without significant unplanned LandWorks work | Mark Pearce / Sarah Chen | June 24, 2026 | (1) Emergency technical review June 18; (2) GovTech and ICT confirmed no workable workaround within budget; (3) Change Request CR-003 raised to defer parking permits to Phase 2; (4) CR-003 approved by the Sponsor on July 8 | **Deferred** | July 8, 2026 (deferred to Phase 2 via CR-003) |
| ISS-04 | June 30, 2026 | GovTech Project Lead | Harbor Payments payment gateway security audit required | Property tax payment gateway requires a security audit before integration can be certified — not included in the project plan | Problem | **High** | Property tax payment module delayed; could delay Gate 2 | Mark Pearce | July 14, 2026 | (1) Harbor Payments contacted July 1; (2) Audit scheduled July 10; (3) Audit completed July 14 — passed with 2 medium findings (token handling and session timeout; both resolved by July 21) | **Closed** | July 21, 2026 |
| ISS-05 | August 3, 2026 | Sandra Obi | UAT preparation cover during August leave | Sandra's deputy cannot adequately cover UAT preparation during her August leave; risk to UAT start | Concern | **Medium** | UAT preparation tasks may be incomplete when Sandra returns August 19 | Sarah Chen | August 19, 2026 | (1) UAT prep checklist reviewed with Sandra before leave; (2) Key prep tasks reassigned to Diane Hughes (BCM); (3) UAT start date maintained at August 24 | **Closed** | August 19, 2026 |
| ISS-06 | August 12, 2026 | GovTech Test Lead | Portal layout broken on older Android devices | Text overflow and broken layout on Android 8 and below, found in pre-UAT device checks | Problem | **Medium** | ~6% of resident devices may be affected (analytics estimate) | GovTech Project Lead | August 26, 2026 | (1) GovTech investigating root cause (CSS compatibility); (2) Formal Android check planned for August 20; (3) Re-test to follow the fix | **Open** | — |

[↑ Back to top](#table-of-contents)

---

## Status Values

| Status | Meaning |
|---|---|
| Open | Issue is active and being worked |
| In Progress | Actions are underway |
| Escalated | Issue has been escalated to sponsor / program |
| Resolved | Issue is resolved; resolution documented |
| Closed | Resolved and verified; no further action required |
| Deferred | Action deferred to a future phase or project |

[↑ Back to top](#table-of-contents)

---

## Escalation Path

| Level | Escalation route | Examples |
|---|---|---|
| **Project team** | PM (Sarah Chen) resolves directly | Low / Medium issues; resource conflicts, technical questions |
| **Project Sponsor** | PM escalates to Sponsor (James Hartley) within 2 working days | High issues; scope disputes, budget requests, priority conflicts |
| **Project Board** | Sponsor convenes the Board | Critical issues; same day; where a Board decision is required |
| **Program / SRO** | Board escalates | Issues beyond project authority; cross-project dependencies |

[↑ Back to top](#table-of-contents)

---

## Relationship to Risk Register

Issues that materialize from risks are cross-referenced to the Risk Register (the originating risk is updated to "Materialized → Issue" and the risk ID is recorded against the issue):

| Issue | Originated from risk? | Risk Register ref |
|---|---|---|
| ISS-01 (ICT Developer not named) | Yes — materialized from RSK-03 (named ICT Developer not confirmed) | RSK-03 → Materialized as ISS-01 |
| ISS-03 (Parking permits — LandWorks compatibility) | Yes — materialized (partial) from RSK-01 (LandWorks integration more complex than estimated) | RSK-01 → Materialized (partial) as ISS-03 / CR-003 |
| ISS-04 (Harbor Payments payment gateway security audit) | Yes — materialized from RSK-08 (Harbor Payments payment gateway requires security certification) | RSK-08 → Materialized as ISS-04 |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

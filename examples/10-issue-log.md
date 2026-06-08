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
| **Date** | 15 August 2026 |
| **Owner** | Sarah Chen, Project Manager |
| **Review frequency** | Weekly at team meeting; immediately for Critical issues |

> **Note:** This is a mid-project snapshot (Version 1.4, 15 August 2026). ISS-06 was open at this date and was subsequently resolved (re-test passed 22 August 2026) before project closure — at closure all six issues are recorded as resolved.

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
| ISS-01 | 8 Mar 2026 | Sarah Chen | ICT Developer not named | Resource gap for the integration phase — named developer not yet confirmed | Problem | **High** | Integration phase cannot start on time (June 2026) if resource not confirmed | Mark Pearce | 1 Apr 2026 | (1) Escalated to Sponsor 9 Mar; (2) Mark Pearce asked to confirm by 15 Mar; (3) Tom Okafor confirmed as ICT Developer 13 Mar | **Closed** | 13 Mar 2026 |
| ISS-02 | 4 Apr 2026 | Mark Pearce | Business Change Manager role not filled | No-one owning staff engagement and training readiness | Problem | **High** | Staff resistance unmanaged; training delivery at risk | Sarah Chen / HR | 1 May 2026 | (1) Escalated to Sponsor 5 Apr; (2) Internal redeployment agreed — Diane Hughes confirmed as Business Change Manager 22 Apr | **Closed** | 22 Apr 2026 |
| ISS-03 | 17 Jun 2026 | Tom Okafor | UNIFORM parking permit data not queryable | UNIFORM API exposes parking permit expiry only as a scanned PDF, not as queryable data | Problem | **Critical** | Parking permit module cannot be built as specified without significant unplanned UNIFORM work | Mark Pearce / Sarah Chen | 24 Jun 2026 | (1) Emergency technical review 18 Jun; (2) GovTech and ICT confirmed no workable workaround within budget; (3) Change Request CR-003 raised to defer parking permits to Phase 2; (4) CR-003 approved by Project Board 8 Jul | **Deferred** | 8 Jul 2026 (deferred to Phase 2 via CR-003) |
| ISS-04 | 30 Jun 2026 | GovTech Project Lead | Capita payment gateway security audit required | Council tax payment gateway requires a security audit before integration can be certified — not included in the project plan | Problem | **High** | Council tax payment module delayed; could delay Gate 2 | Mark Pearce | 14 Jul 2026 | (1) Capita contacted 1 Jul; (2) Audit scheduled 10 Jul; (3) Audit completed 14 Jul — passed with 2 minor findings (both resolved by 21 Jul) | **Closed** | 21 Jul 2026 |
| ISS-05 | 3 Aug 2026 | Sandra Obi | UAT preparation cover during August leave | Sandra's deputy cannot adequately cover UAT preparation during her August leave; risk to UAT start | Concern | **Medium** | UAT preparation tasks may be incomplete when Sandra returns 19 Aug | Sarah Chen | 19 Aug 2026 | (1) UAT prep checklist reviewed with Sandra before leave; (2) Key prep tasks reassigned to Diane Hughes (BCM); (3) UAT start date maintained at 22 Aug | **Closed** | 19 Aug 2026 |
| ISS-06 | 12 Aug 2026 | Resident UAT Participant | Portal layout broken on older Android devices | Text overflow and broken layout on Android 8 and below | Problem | **Medium** | ~6% of resident devices may be affected (analytics estimate) | GovTech Project Lead | 26 Aug 2026 | (1) GovTech investigating root cause (CSS compatibility); (2) Fix expected 20 Aug; (3) Re-test scheduled 22 Aug | **Open** | — |

[↑ Back to top](#table-of-contents)

---

## Status Values

| Status | Meaning |
|---|---|
| Open | Issue is active and being worked |
| In Progress | Actions are underway |
| Escalated | Issue has been escalated to sponsor / programme |
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
| **Programme / SRO** | Board escalates | Issues beyond project authority; cross-project dependencies |

[↑ Back to top](#table-of-contents)

---

## Relationship to Risk Register

Issues that materialise from risks are cross-referenced to the Risk Register (the originating risk is updated to "Materialised → Issue" and the risk ID is recorded against the issue):

| Issue | Originated from risk? | Risk Register ref |
|---|---|---|
| ISS-01 (ICT Developer not named) | Yes — materialised from RSK-03 (named ICT Developer not confirmed) | RSK-03 → Materialised as ISS-01 |
| ISS-03 (Parking permits — UNIFORM compatibility) | Yes — materialised (partial) from RSK-01 (UNIFORM integration more complex than estimated) | RSK-01 → Materialised (partial) as ISS-03 / CR-003 |
| ISS-04 (Capita payment gateway security audit) | Yes — materialised from RSK-08 (Capita payment gateway requires security certification) | RSK-08 → Materialised as ISS-04 |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Worked Example: Issue Log
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Issue%20Log-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/issue-log.md`](../templates/issue-log.md) | **Module:** [05 — Project Execution](../modules/05-execution.md)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.4 |
| **Date** | 15 August 2026 |
| **Owner** | Sarah Chen, Project Manager |

---

## Severity Scale

| Severity | Response time | Definition |
|---|---|---|
| **Critical** | Same day | Threatens the go-live date, a Gate review, or the business case. Immediate escalation to Sponsor. |
| **High** | Within 2 working days | Significant impact on a key deliverable or milestone; likely to affect schedule or cost. |
| **Medium** | Within 5 working days | Moderate impact; manageable within project resources. |
| **Low** | Within 10 working days | Minor impact; can be addressed in normal course of work. |

---

## Issue Log

| ID | Date raised | Raised by | Issue title | Type | Severity | Impact | Owner | Target resolution | Actions taken | Status | Date closed |
|---|---|---|---|---|---|---|---|---|---|---|---|
| ISS-01 | 8 Mar 2026 | Sarah Chen | ICT Developer not named — resource gap for integration phase | Problem | **High** | Integration phase cannot start on time (June 2026) if resource not confirmed | Mark Pearce | 1 Apr 2026 | (1) Escalated to Sponsor 9 Mar; (2) Mark Pearce asked to confirm by 15 Mar; (3) Tom Okafor confirmed as ICT Developer 13 Mar | **Closed** | 13 Mar 2026 |
| ISS-02 | 4 Apr 2026 | Mark Pearce | Business Change Manager role not yet filled — no-one owning staff engagement | Problem | **High** | Staff resistance unmanaged; training delivery at risk | Sarah Chen / HR | 1 May 2026 | (1) Escalated to Sponsor 5 Apr; (2) Internal redeployment agreed — Diane Hughes (Digital Comms) confirmed as BCM 22 Apr | **Closed** | 22 Apr 2026 |
| ISS-03 | 17 Jun 2026 | Tom Okafor | UNIFORM API does not expose parking permit expiry data in queryable form — only available as scanned PDF | Problem | **Critical** | Parking permit module cannot be built as specified without significant unplanned UNIFORM work | Mark Pearce / Sarah Chen | 24 Jun 2026 | (1) Emergency technical review 18 Jun; (2) GovTech and ICT confirmed no workable workaround within budget; (3) Change Request CR-003 raised to defer parking permits to Phase 2; (4) CR-003 approved by Project Board 8 Jul | **Closed — via CR-003** | 8 Jul 2026 |
| ISS-04 | 30 Jun 2026 | GovTech Project Lead | Council tax payment gateway (Capita) requires a security audit before integration can be certified — not included in project plan | Problem | **High** | Council tax payment module delayed; could delay Gate 2 | Mark Pearce | 14 Jul 2026 | (1) Capita contacted 1 Jul; (2) Audit scheduled 10 Jul; (3) Audit completed 14 Jul — passed with 2 minor findings (both resolved by 21 Jul) | **Closed** | 21 Jul 2026 |
| ISS-05 | 3 Aug 2026 | Sandra Obi | Sandra's deputy cannot cover UAT preparation adequately during Sandra's August leave; risk to UAT start | Concern | **Medium** | UAT preparation tasks may be incomplete when Sandra returns 19 Aug | Sarah Chen | 19 Aug 2026 | (1) UAT prep checklist reviewed with Sandra before leave; (2) Key prep tasks reassigned to Diane Hughes (BCM); (3) UAT start date maintained at 22 Aug | **Closed** | 19 Aug 2026 |
| ISS-06 | 12 Aug 2026 | Resident UAT Participant | Portal not displaying correctly on older Android devices (Android 8 and below) — text overflow and broken layout | Problem | **Medium** | ~6% of resident devices may be affected (analytics estimate) | GovTech Project Lead | 26 Aug 2026 | (1) GovTech investigating root cause (CSS compatibility); (2) Fix expected 20 Aug; (3) Re-test scheduled 22 Aug | **Open** | — |

---

## Escalation Path

| Issue severity | Escalates to |
|---|---|
| Low / Medium | Project Manager (Sarah Chen) |
| High | Sponsor (James Hartley) within 2 working days |
| Critical | Sponsor within same day; Project Board convened if decision required |

---

## Relationship to Risk Register

| Issue | Originated from risk? | Risk Register ref |
|---|---|---|
| ISS-03 (Parking permits — UNIFORM compatibility) | Yes — materialised from RSK-01 (UNIFORM integration more complex than estimated) | RSK-01 now Closed → Materialised as ISS-03 |
| ISS-04 (Payment gateway security audit) | Partially — RSK-01 also partially captured this; updated in risk register | RSK-01 updated |

---

*© 2026 UncleJs — Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*

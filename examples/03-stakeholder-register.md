# Worked Example: Stakeholder Register
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Stakeholder%20Register-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/stakeholder-register.md`](../templates/stakeholder-register.md) | **Module:** [09 — Stakeholder Management](../modules/09-stakeholder-management.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Engagement Level Key](#engagement-level-key)
- [Stakeholder Register](#stakeholder-register)
- [Power / Interest Grid Summary](#power--interest-grid-summary)
- [Notes](#notes)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.2 |
| **Date** | February 14, 2026 |
| **Owner** | Sarah Chen, Project Manager |
| **Review frequency** | Monthly (or after any significant stakeholder event) |

[↑ Back to top](#table-of-contents)

---

## Engagement Level Key

| Code | Level | Description |
|---|---|---|
| U | Unaware | Does not know the project exists |
| R | Resistant | Aware but opposed; actively or passively blocking |
| N | Neutral | Aware; neither supportive nor resistant |
| S | Supportive | Aware and in favor of the project |
| L | Leading | Actively championing and driving the project forward |

[↑ Back to top](#table-of-contents)

---

## Stakeholder Register

| ID | Name | Organization / Role | Interest in project | Influence (H/M/L) | Impact on them (H/M/L) | Current engagement | Desired engagement | Key concerns | Engagement approach | Owner | Review date |
|---|---|---|---|---|---|---|---|---|---|---|---|
| STK-01 | James Hartley | Director of Digital Services / Sponsor | Deliver city digital strategy; cost saving | H | H | L (Leading) | L | Project stays on budget and schedule; City strategic plan commitment met | Monthly Project Board; direct weekly check-in with PM | Sarah Chen | Monthly |
| STK-02 | Sandra Obi | Head of Customer Services / Senior User | Operational impact on her team; service quality | H | H | S | L | Staff job security; resident experience not harmed; adequate training | Included in Project Board; co-chairs UAT; bi-weekly ops catch-up | Sarah Chen | Monthly |
| STK-03 | Mark Pearce | ICT Infrastructure Manager / Senior Supplier | Technical delivery; infrastructure capacity | H | M | N | S | Workload on his team; integration risk to LandWorks; security compliance | Technical working group weekly; integration sprint reviews | Sarah Chen | Monthly |
| STK-04 | Councilmember Patricia Dean | Chair, Technology and Innovation Committee | Political success; constituent satisfaction | H | L | S | L | Project delivered on time; positive press coverage | Monthly sponsor briefing note; attend go-live event | James Hartley | Monthly |
| STK-05 | Ayo Mensah | Contact Center Team Lead | Job security; workload change | M | H | R | N | Role redundancy if call volumes drop; team morale | Direct 1:1 meeting (March); redeployment briefing; involve in UAT | Sandra Obi | Every two weeks |
| STK-06 | Contact Center Team (12 staff) | Customer Services | Workload change; job security; new processes | M | H | R | N | Same as STK-05; plus: adequate training before go-live | Team briefing (March); training sessions (September); Q&A sessions | Sandra Obi | Monthly |
| STK-07 | GovTech Solutions Inc. | Supplier / Portal Platform | Successful delivery; contract performance; reference site | H | M | S | S | Timely decisions from city; integration access; testing environment | Weekly supplier meeting; contractual milestone reviews | Sarah Chen | Every two weeks |
| STK-08 | Claire Worthington | Finance Director | Budget compliance; value for money | M | L | N | S | Cost escalation; contingency consumption; procurement compliance | Monthly finance report copy; alert if contingency consumed >50% | Sarah Chen | Monthly |
| STK-09 | Northgate Residents | Primary end users (81,000 residents) | Easy, accessible digital services | L (individually) | H (collectively) | U | S | Portal is easy to use; accessible; secure; data privacy | Resident communications campaign (August–October); online survey at go-live | Digital Services | Milestone-based |
| STK-10 | Chief Privacy Officer | Information Governance | privacy requirements compliance; data security | M | M | U | S | Citizen data handling; third-party data sharing with GovTech; breach risk | PIA completed by March; review at each build milestone | Sarah Chen | Quarterly |
| STK-11 | Northgate Equity Officer | HR / Legal | Accessibility compliance (WCAG 2.1 AA); digital exclusion | M | M | U | S | Portal inaccessible to some residents (elderly, disabled, low digital skills) | Accessibility review included in UAT; alternative channel maintained | Sandra Obi | At UAT |
| STK-12 | Chief Executive | City Leadership | Strategic and reputational risk | H | L | U | S | Political risk; project failure visibility; media coverage | Quarterly exec briefing note; invited to go-live event | James Hartley | Quarterly |

[↑ Back to top](#table-of-contents)

---

## Power / Interest Grid Summary

```
         HIGH POWER
              |
   Keep       |    Manage
   Satisfied  |    Closely
              |
  STK-04   STK-08    STK-01 STK-02 STK-03
  STK-12              STK-07
-----------------------------------------
  Monitor    |    Keep
             |    Informed
              |
  (none)    STK-11    STK-05 STK-06
                      STK-09 STK-10
              |
         LOW POWER
              LOW INTEREST -------- HIGH INTEREST
```

| Quadrant | Stakeholders | Strategy |
|---|---|---|
| **Manage Closely** (High power, High interest) | STK-01, STK-02, STK-03, STK-07 | Regular engagement; involve in decisions; two-way communication |
| **Keep Satisfied** (High power, Low interest) | STK-04, STK-08, STK-12 | Regular updates; avoid surprises; do not over-engage |
| **Keep Informed** (Low power, High interest) | STK-05, STK-06, STK-09, STK-10 | Targeted communication; address concerns proactively |
| **Monitor** (Low power, Low interest) | STK-11 | Include in formal reviews; do not neglect |

[↑ Back to top](#table-of-contents)

---

## Notes

- STK-05 and STK-06 are currently **Resistant**. The primary concern is job security. Evidence from comparable projects shows that early, transparent communication about redeployment (not redundancy) significantly reduces resistance. This is a priority engagement action for March 2026.
- STK-09 (residents) are currently **Unaware** — this is appropriate at this stage. Resident communications will begin in August 2026 ahead of go-live.
- This register contains sensitive information (political and personal concerns). It should not be shared beyond the project team and Project Board without approval.

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

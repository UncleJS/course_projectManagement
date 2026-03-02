# Worked Example: Assumption and Constraint Log
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Assumption%20%26%20Constraint%20Log-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/assumption-constraint-log.md`](../templates/assumption-constraint-log.md) | **Module:** [03 — Project Initiation](../modules/03-initiation.md)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.1 |
| **Date** | 14 February 2026 |
| **Owner** | Sarah Chen, Project Manager |
| **Review frequency** | Monthly at Project Board; immediately when status changes |

---

## Assumptions

> An **assumption** is a factor taken to be true for planning purposes, without confirmed proof. If an assumption proves false, it may become a risk or issue. All assumptions must be tested and confirmed as early as possible.

| ID | Assumption | Owner | Date captured | Status | Review date | Associated risks |
|---|---|---|---|---|---|---|
| ASM-01 | The GovTech Solutions framework agreement (awarded 2024) remains valid and can be used for this project without a new competitive tender | Claire Worthington / Sarah Chen | 14 Jan 2026 | **Confirmed** — Legal verified 28 Jan 2026 | N/A (confirmed) | None |
| ASM-02 | ICT team can provide 0.4 FTE commitment to UNIFORM integration work for the duration of the project (Feb–Sep 2026) | Mark Pearce | 14 Jan 2026 | **Active** — Verbal agreement; not yet formally allocated in resource plan | 7 March 2026 | RSK-03 |
| ASM-03 | 89% internet access rate in Northgate district (ONS 2024 data) supports a 55% digital deflection target | Digital Services | 14 Jan 2026 | **Active** — Based on published data; not tested against Northgate-specific demographics | April 2027 (PIR) | RSK-05 |
| ASM-04 | Staff released from contact-centre transaction handling will be redeployable within the council — no redundancy costs anticipated | Sandra Obi / HR | 14 Jan 2026 | **Active** — HR verbal agreement; not yet documented in workforce plan | April 2026 | RSK-06 |
| ASM-05 | GovTech CivicConnect API connector for Northgate UNIFORM is available as a pre-built integration and requires only configuration, not custom development | Mark Pearce / GovTech | 3 Feb 2026 | **Active** — GovTech confirmed in pre-sales; to be validated in Discovery phase | 8 May 2026 (Gate 1) | RSK-01 |
| ASM-06 | The council's IT infrastructure (hosting, networking, security) can support the additional load of the CivicConnect SaaS platform without additional capital expenditure | Mark Pearce | 3 Feb 2026 | **Confirmed** — ICT infrastructure assessment completed 10 Feb 2026; capacity confirmed | N/A (confirmed) | None |
| ASM-07 | Go-live date of 1 October 2026 is achievable within 9 months | Sarah Chen | 3 Feb 2026 | **Active** — Schedule baselined; dependent on supplier on-time delivery and ICT resource availability | At each Gate review | RSK-02, RSK-03 |

---

## Constraints

> A **constraint** is a limiting factor that restricts the project. Constraints are fixed — they cannot be changed without escalation to a higher authority.

| ID | Constraint | Type | Owner | Date captured | Status |
|---|---|---|---|---|---|
| CON-01 | Total approved budget is £420,000 (including 10% contingency). No additional funding is available from the capital programme for 2025/26. | Budget | James Hartley | 14 Jan 2026 | Active |
| CON-02 | Go-live date of 1 October 2026 is fixed. This aligns with the council's new financial year contact-volume reporting cycle and the Portfolio Holder's public commitment. | Schedule | James Hartley | 14 Jan 2026 | Active |
| CON-03 | The UNIFORM back-office system must not be modified outside of the agreed integration touchpoints (read status, accept payment confirmation). Any wider UNIFORM changes are out of scope and require a separate IT change request. | Scope / Technical | Mark Pearce | 3 Feb 2026 | Active |
| CON-04 | The portal must comply with WCAG 2.1 AA accessibility standards. This is a legal requirement under the Public Sector Bodies (Websites and Mobile Applications) Accessibility Regulations 2018. | Regulatory | Equality Officer | 3 Feb 2026 | Active |
| CON-05 | All citizen data must be processed in accordance with UK GDPR. A Data Protection Impact Assessment (DPIA) must be completed and signed off by the DPO before build begins. | Regulatory / Legal | Data Protection Officer | 3 Feb 2026 | Active |
| CON-06 | Procurement must comply with the terms of the GovTech framework agreement. Any requirement outside the framework scope requires a separate procurement process. | Procurement | Claire Worthington | 14 Jan 2026 | Active |

---

## Relationship to Risks

Assumptions ASM-02, ASM-03, ASM-04, ASM-05, and ASM-07 are each linked to risks in the Risk Register because if those assumptions prove false, the impact on the project is material. The linked risks contain the probability, impact assessment, and response actions.

All assumptions must be reviewed at each Gate review. By Gate 1 (8 May 2026), ASM-05 (UNIFORM connector) must be confirmed or the scope/budget must be revised.

---

*© 2026 UncleJs — Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*

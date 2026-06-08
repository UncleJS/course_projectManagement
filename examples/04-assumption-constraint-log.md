# Worked Example: Assumption and Constraint Log
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Assumption%20%26%20Constraint%20Log-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/assumption-constraint-log.md`](../templates/assumption-constraint-log.md) | **Module:** [03 — Project Initiation](../modules/03-initiation.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Definitions](#definitions)
- [Assumptions Log](#assumptions-log)
  - [Assumption Status Values](#assumption-status-values)
- [Constraints Log](#constraints-log)
  - [Constraint Types](#constraint-types)
- [Relationship to Risks](#relationship-to-risks)
- [Change History](#change-history)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.1 |
| **Date** | 14 February 2026 |
| **Owner** | Sarah Chen, Project Manager |
| **Review frequency** | Monthly at Project Board; immediately when status changes |

[↑ Back to top](#table-of-contents)

---

## Definitions

- **Assumption**: A statement accepted as true for planning purposes but not yet confirmed. If proved wrong, it may affect the project and become a risk or an issue. All assumptions must be tested and confirmed as early as possible.
- **Constraint**: A limitation within which the project must operate (fixed deadline, budget cap, regulatory boundary, resource ceiling). Constraints are fixed and cannot be changed without escalation to a higher authority.

[↑ Back to top](#table-of-contents)

---

## Assumptions Log

| ID | Date raised | Assumption statement | Basis | Confidence (H/M/L) | Impact if wrong | Owner | Review date | Status | Associated risks |
|---|---|---|---|---|---|---|---|---|---|
| ASM-01 | 14 Jan 2026 | The GovTech Solutions framework agreement (awarded 2024) remains valid and can be used for this project without a new competitive tender | GovTech framework awarded 2024; Legal review | H | New competitive tender required — 3–4 month delay | Claire Worthington / Sarah Chen | N/A (confirmed) | Confirmed — Legal verified 28 Jan 2026 | None |
| ASM-02 | 14 Jan 2026 | ICT team can provide 0.4 FTE commitment to UNIFORM integration work for the duration of the project (Feb–Sep 2026) | Verbal agreement with ICT; not yet allocated in resource plan | M | Integration work delayed; Gate 2 at risk | Mark Pearce | 7 March 2026 | Open | RSK-03 |
| ASM-03 | 14 Jan 2026 | 89% internet access rate in Northgate district (ONS 2024 data) supports a 55% digital deflection target | ONS 2024 published data; not tested against Northgate-specific demographics | M | Deflection target missed; benefits shortfall | Digital Services | April 2027 (PIR) | Open | RSK-05 |
| ASM-04 | 14 Jan 2026 | Staff released from contact-centre transaction handling will be redeployable within the council — no redundancy costs anticipated | HR verbal agreement; not yet documented in workforce plan | M | Redundancy costs; benefits case weakened | Sandra Obi / HR | April 2026 | Open | RSK-06 |
| ASM-05 | 3 Feb 2026 | GovTech CivicConnect API connector for Northgate UNIFORM is available as a pre-built integration and requires only configuration, not custom development | GovTech pre-sales confirmation; to be validated in Discovery | M | Custom development needed; cost and schedule overrun | Mark Pearce / GovTech | 8 May 2026 (Gate 1) | Open | RSK-01 |
| ASM-06 | 3 Feb 2026 | The council's IT infrastructure (hosting, networking, security) can support the additional load of the CivicConnect SaaS platform without additional capital expenditure | ICT infrastructure assessment completed 10 Feb 2026; capacity confirmed | H | Capital expenditure required for capacity uplift | Mark Pearce | N/A (confirmed) | Confirmed | None |
| ASM-07 | 3 Feb 2026 | Go-live date of 1 October 2026 is achievable within 9 months | Baselined schedule; dependent on supplier on-time delivery and ICT resource availability | M | Go-live slips beyond 1 October 2026 | Sarah Chen | At each Gate review | Open | RSK-02, RSK-03 |

### Assumption Status Values

| Status | Meaning |
|---|---|
| Open | Still assumed; not yet confirmed or invalidated |
| Confirmed | Assumption has been validated as true |
| Invalidated | Assumption has been proved wrong — raise risk or issue |
| Closed | No longer relevant to the project |

[↑ Back to top](#table-of-contents)

---

## Constraints Log

| ID | Date recorded | Constraint description | Type | Source | Impact on project | Owner | Review date | Status |
|---|---|---|---|---|---|---|---|---|
| CON-01 | 14 Jan 2026 | Total approved budget is £420,000 (including 10% contingency). No additional funding is available from the capital programme for 2025/26. | Budget | Capital programme 2025/26 | Scope must be delivered within £420,000; no additional funding | James Hartley | At each Gate review | Active |
| CON-02 | 14 Jan 2026 | Go-live date of 1 October 2026 is fixed. This aligns with the council's new financial year contact-volume reporting cycle and the Portfolio Holder's public commitment. | Schedule | Portfolio Holder public commitment | Fixed go-live limits schedule flexibility | James Hartley | At each Gate review | Active |
| CON-03 | 3 Feb 2026 | The UNIFORM back-office system must not be modified outside of the agreed integration touchpoints (read status, accept payment confirmation). Any wider UNIFORM changes are out of scope and require a separate IT change request. | Technical | ICT / UNIFORM owner | Integration limited to agreed touchpoints | Mark Pearce | 8 May 2026 (Gate 1) | Active |
| CON-04 | 3 Feb 2026 | The portal must comply with WCAG 2.1 AA accessibility standards. This is a legal requirement under the Public Sector Bodies (Websites and Mobile Applications) Accessibility Regulations 2018. | Regulatory / Legal | PSBAR 2018 | WCAG 2.1 AA compliance mandatory before go-live | Equality Officer | Before go-live | Active |
| CON-05 | 3 Feb 2026 | All citizen data must be processed in accordance with UK GDPR. A Data Protection Impact Assessment (DPIA) must be completed and signed off by the DPO before build begins. | Regulatory / Legal | UK GDPR | DPIA sign-off required before build commences | Data Protection Officer | Before build | Active |
| CON-06 | 14 Jan 2026 | Procurement must comply with the terms of the GovTech framework agreement. Any requirement outside the framework scope requires a separate procurement process. | Regulatory / Legal | GovTech framework agreement | Requirements must fit framework scope or trigger separate procurement | Claire Worthington | At procurement | Active |

### Constraint Types

| Type | Examples |
|---|---|
| **Schedule** | Fixed go-live date; regulatory deadline; fiscal year boundary |
| **Budget** | Fixed maximum spend; no contingency available |
| **Resource** | Named individuals only; team size cap |
| **Technical** | Must use existing infrastructure; specific technology mandated |
| **Regulatory / Legal** | Compliance requirement; procurement rules |
| **Organisational** | Cannot impact BAU operations; sign-off hierarchy |

[↑ Back to top](#table-of-contents)

---

## Relationship to Risks

Assumptions ASM-02, ASM-03, ASM-04, ASM-05, and ASM-07 are each linked to risks in the Risk Register because if those assumptions prove false, the impact on the project is material. The linked risks contain the probability, impact assessment, and response actions.

All assumptions must be reviewed at each Gate review. By Gate 1 (8 May 2026), ASM-05 (UNIFORM connector) must be confirmed or the scope/budget must be revised.

[↑ Back to top](#table-of-contents)

---

## Change History

| Version | Date | Changed by | Summary of change |
|---|---|---|---|
| 1.0 | 14 Jan 2026 | Sarah Chen | Initial version — assumptions and constraints captured at business case approval |
| 1.1 | 14 Feb 2026 | Sarah Chen | Added ASM-05–07 and CON-03–06 after charter approval; ASM-01 and ASM-06 confirmed |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

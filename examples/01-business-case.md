# Worked Example: Business Case
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Business%20Case-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/business-case.md`](../templates/business-case.md) | **Module:** [03 — Project Initiation](../modules/03-initiation.md)

---

## Table of Contents

- [Document Control](#document-control)
- [1. Executive Summary](#1-executive-summary)
- [2. Background and Context](#2-background-and-context)
  - [Problem Statement](#problem-statement)
  - [Strategic Context](#strategic-context)
  - [Why Now](#why-now)
- [3. Objectives](#3-objectives)
- [4. Options Considered](#4-options-considered)
  - [Option 0 — Do Nothing](#option-0--do-nothing)
  - [Option 1 — Build a Bespoke Portal (Internal Development)](#option-1--build-a-bespoke-portal-internal-development)
  - [Option 2 — Purchase Off-the-Shelf SaaS Platform (GovTech CivicConnect)](#option-2--purchase-off-the-shelf-saas-platform-govtech-civicconnect)
  - [Option 3 — Outsource Contact Center](#option-3--outsource-contact-center)
- [5. Recommended Option: Option 2 — GovTech CivicConnect](#5-recommended-option-option-2--govtech-civicconnect)
- [6. Expected Benefits](#6-expected-benefits)
- [7. Costs](#7-costs)
  - [Capital Investment](#capital-investment)
  - [Ongoing Operational Costs (Post Go-Live)](#ongoing-operational-costs-post-go-live)
- [8. Return on Investment](#8-return-on-investment)
  - [Financial Summary](#financial-summary)
- [9. Risks](#9-risks)
- [10. Timescale](#10-timescale)
- [11. Constraints and Assumptions](#11-constraints-and-assumptions)
  - [Constraints](#constraints)
  - [Assumptions](#assumptions)
- [12. Recommendation](#12-recommendation)
- [Approval](#approval)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.3 |
| **Date** | January 14, 2026 |
| **Prepared by** | Sarah Chen, Project Manager |
| **Approved by** | James Hartley, Director of Digital Services |
| **Status** | Approved — Baseline |

[↑ Back to top](#table-of-contents)

---

## 1. Executive Summary

The City of Northgate spends $310,000 per year handling approximately 14,200 citizen inquiries that are routine and transactional in nature. The Meridian Portal project will deliver a citizen-facing self-service web platform enabling residents to manage planning and zoning inquiries, pay property tax, report missed trash and yard waste, and renew parking permits without staff intervention. Based on a conservative 55% digital deflection rate, the portal is projected to save $123,820 per year net by Year 2 of operation ($171,820 gross less $48,000 annual running cost), recovering the full investment within about 3.4 years. The project is recommended for approval at a total investment of $420,000.

[↑ Back to top](#table-of-contents)

---

## 2. Background and Context

### Problem Statement

The city's contact center receives 14,200 in-scope inquiries per year. Analysis of call and visit data shows that 68% are transactional — residents seeking status updates, making payments, or submitting standard requests. These interactions require no officer discretion and are currently handled at an average cost of $22 per contact (staff time, premises, systems).

Residents consistently rate the contact experience as time-consuming (average wait time: 11 minutes). The city's digital satisfaction index scores 34/100 — well below the sector benchmark of 58.

### Strategic Context

The City strategic plan 2024–2028 commits to:
> *"Delivering 60% of resident transactions digitally by 2028, reducing the cost of administration and improving resident satisfaction."*

The Meridian Portal is the primary delivery vehicle for this commitment.

### Why Now

A procurement framework agreement with GovTech Solutions Inc. (awarded 2024) enables the city to commission a proven SaaS portal platform without a full open tender, reducing procurement time and risk. This window closes in December 2026.

[↑ Back to top](#table-of-contents)

---

## 3. Objectives

| Ref | Objective | Success Measure |
|---|---|---|
| OBJ-01 | Deliver a fully operational citizen self-service portal | Portal live and accessible to all Northgate residents by October 1, 2026 |
| OBJ-02 | Achieve 55% digital deflection of eligible contact-center inquiries | Measured at 6 months post go-live via contact-center volume data |
| OBJ-03 | Improve resident digital satisfaction | Digital satisfaction index (0–100) increases from 34 to 54 or higher within 12 months of go-live |
| OBJ-04 | Deliver within approved budget | Outturn cost ≤ $420,000 (including 10% contingency) |

[↑ Back to top](#table-of-contents)

---

## 4. Options Considered

### Option 0 — Do Nothing

Continue operating the current phone and in-person contact model. Annual cost of $310,000 maintained; resident satisfaction remains low; City strategic plan digital target not achieved. Not recommended.

### Option 1 — Build a Bespoke Portal (Internal Development)

Commission the ICT team to build a custom portal from scratch. Estimated cost: $680,000 over 18 months. High technical risk given ICT team capacity constraints. No existing similar platform to draw on. Not recommended.

### Option 2 — Purchase Off-the-Shelf SaaS Platform (GovTech CivicConnect)

Use the city's existing framework agreement with GovTech Solutions to deploy their CivicConnect citizen portal, configured to Northgate's services. CivicConnect is live in 34 other cities. Estimated cost: $420,000 over 9 months. Proven technology; lower risk; shorter timeline. **Recommended.**

### Option 3 — Outsource Contact Center

Transfer the contact-center function to a shared-service provider. Estimated saving: $90,000 per year. However, this does not improve resident satisfaction, reduces city control over service quality, and does not support the City strategic plan digital commitment. Not recommended.

[↑ Back to top](#table-of-contents)

---

## 5. Recommended Option: Option 2 — GovTech CivicConnect

**Rationale:**
- Proven platform in comparable city government environments reduces technical and delivery risk.
- Procurement route already established; no competitive tender required under the framework agreement.
- Shorter timeline (9 months vs 18 months for bespoke build) reduces exposure.
- Lower total cost than bespoke development.
- Integrates with the existing Northgate LandWorks back-office system via a supported API connector.

[↑ Back to top](#table-of-contents)

---

## 6. Expected Benefits

| Benefit | Category | Measure | Baseline | Target | Realization date | Owner |
|---|---|---|---|---|---|---|
| Contact-center cost reduction | Financial | $ saving per year | $310,000 annual cost | $171,820 per year gross (55% deflection × $22/contact × 14,200 contacts) | April 2027 (6 months post go-live) | Head of Customer Services |
| Staff time redeployment | Financial | FTE equivalent released | 0 | 1.8 FTE (redeployed to complex casework) | April 2027 | HR Business Partner |
| Resident digital satisfaction | Non-financial | Digital satisfaction index (0–100) | 34 | 54 or higher | October 2027 (12 months post go-live) | Head of Customer Services |
| Digital transaction rate | Non-financial | % transactions completed digitally | 18% | 55% | April 2027 | Digital Services Manager |

**Year 2 net annual saving:** $123,820 (gross deflection saving of $171,820 less the $48,000 total annual running cost — GovTech support and internal administration).

[↑ Back to top](#table-of-contents)

---

## 7. Costs

### Capital Investment

| Item | Year 1 Cost ($) | Basis of Estimate | Confidence |
|---|---|---|---|
| GovTech CivicConnect platform license (Y1) | 95,000 | Supplier quotation | High |
| Platform configuration and integration | 145,000 | Supplier fixed-price proposal | High |
| LandWorks integration development | 48,000 | ICT team estimate | Medium |
| Content migration and UX testing | 32,000 | Supplier quotation | High |
| Project management and oversight | 42,000 | Internal resource cost | Medium |
| Training and change management | 20,000 | Estimate (analogous to prior digital projects) | Medium |
| **Subtotal** | **382,000** | | |
| Contingency (10%) | 38,000 | Standard organizational rate | — |
| **Total** | **420,000** | | |

### Ongoing Operational Costs (Post Go-Live)

| Item | Annual Cost ($) |
|---|---|
| GovTech CivicConnect SaaS license and support (Years 2+) | 36,000 |
| Internal support and administration | 12,000 |
| **Total annual running cost** | **48,000** |

[↑ Back to top](#table-of-contents)

---

## 8. Return on Investment

### Financial Summary

| Year | Investment ($) | Saving ($) | Net position ($) | Cumulative ($) |
|---|---|---|---|---|
| 2026 (project year) | -420,000 | 0 | -420,000 | -420,000 |
| 2027 (Year 1 operational) | -48,000 | +171,820 | +123,820 | -296,180 |
| 2028 (Year 2) | -48,000 | +171,820 | +123,820 | -172,360 |
| 2029 (Year 3) | -48,000 | +171,820 | +123,820 | -48,540 |
| 2030 (Year 4) | -48,000 | +171,820 | +123,820 | +75,280 |

- **Payback period:** ~3.4 years post go-live (during 2030)
- **ROI (3 years post go-live):** $371,460 net saving over three operational years on $420,000 investment = 88%
- **NPV (5% discount, 5 years):** +$116,000

[↑ Back to top](#table-of-contents)

---

## 9. Risks

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| Integration with LandWorks system is more complex than estimated | Medium | High | Fixed-price integration contract with GovTech; ICT review at discovery phase |
| Resident adoption rates lower than projected | Medium | High | User research and UX testing in design phase; post-go-live communications campaign |
| Contact-center staff resist change | Medium | Medium | Engagement via Head of Customer Services; clarity on redeployment (not redundancy) |
| GovTech platform delivery delay | Low | High | Contractual milestone payments and penalty clauses; parallel BAU contingency plan |
| City political priorities change | Low | Medium | Business case reviewed at each stage gate; project remains paused (not canceled) if priorities shift |

Full detail in the project Risk Register (see [`14-risk-register.md`](14-risk-register.md)).

[↑ Back to top](#table-of-contents)

---

## 10. Timescale

| Milestone | Target Date |
|---|---|
| Business case approved / project authorized | February 2026 |
| Supplier contract signed | March 2026 |
| Discovery and design complete | May 2026 |
| Build and integration complete | August 2026 |
| User acceptance testing complete | September 2026 |
| Go-live | October 1, 2026 |
| Post-implementation review | April 2027 |

[↑ Back to top](#table-of-contents)

---

## 11. Constraints and Assumptions

### Constraints

- Budget ceiling: $420,000 (including contingency). No additional funding is available.
- Go-live date: October 1, 2026 is fixed — it aligns with the city's new fiscal-year contact volume reporting cycle.
- Platform must integrate with the existing Northgate LandWorks system (no replacement of back-office system in scope).

### Assumptions

- GovTech CivicConnect framework agreement remains valid and accessible for this project.
- ICT infrastructure team can provide 0.4 FTE commitment to integration work across the project.
- Residents of Northgate have sufficient internet access to make 55% digital deflection achievable (based on U.S. Census Bureau 2024 data showing 89% internet access in the city).
- Staff released by contact volume reduction will be redeployed within the city — no redundancy costs anticipated.

[↑ Back to top](#table-of-contents)

---

## 12. Recommendation

The business case for the Meridian Portal is strong. The investment is proportionate, the risks are manageable, the technology is proven, and the project directly delivers against the City strategic plan 2024–2028 commitment to digital service transformation.

**This business case recommends approval of $420,000 of capital funding and authorization to proceed to project initiation.**

[↑ Back to top](#table-of-contents)

---

## Approval

| Role | Name | Signature | Date |
|---|---|---|---|
| Approving Officer | James Hartley, Director of Digital Services | *J. Hartley* | January 14, 2026 |
| Finance Director (financial sign-off) | Claire Worthington | *C. Worthington* | January 14, 2026 |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

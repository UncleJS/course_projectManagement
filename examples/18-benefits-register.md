# Worked Example: Benefits Register
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Benefits%20Register-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/benefits-register.md`](../templates/benefits-register.md) | **Module:** [02 — Governance and Organizational Context](../modules/02-governance.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Benefits Classification](#benefits-classification)
- [Benefits Register](#benefits-register)
- [Financial Benefits Summary](#financial-benefits-summary)
- [Benefits Realization Milestones](#benefits-realization-milestones)
- [Post-Implementation Review (PIR) Summary](#post-implementation-review-pir-summary)
- [Notes on Benefit BEN-01 Baseline](#notes-on-benefit-ben-01-baseline)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 2.0 (at project closure — handed over to BAU) |
| **Date** | October 31, 2026 |
| **Project Benefits Owner (during project)** | James Hartley, Director of Digital Services (Sponsor) |
| **Maintained by (post-closure)** | Sandra Obi, Head of Customer Services |

[↑ Back to top](#table-of-contents)

---

## Benefits Classification

| Type | Description |
|---|---|
| **Financial — cashable** | Savings that can be removed from budget or headcount |
| **Financial — non-cashable** | Efficiency gains not directly removed from budget (time released) |
| **Non-financial — quantifiable** | Measurable but not in $ (satisfaction scores, adoption rates, processing time) |
| **Non-financial — qualitative** | Measurable by assessment or judgment (public trust, staff morale) |

[↑ Back to top](#table-of-contents)

---

## Benefits Register

| ID | Benefit name | Description | Type | Owner | Baseline measure | Baseline date | Target measure | Target date | Measurement method | Evidence source | Current measure | Last measured | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| BEN-01 | Reduction in contact-center call volume | Residents self-serve online for planning and zoning, missed trash, property tax, and yard-waste inquiries — reducing the volume of calls and counter visits handled by the contact center for these services | Non-financial — quantifiable | Sandra Obi | 14,200 in-scope inquiries per year | March 2026 (reconstructed from a 12-month average) | 55% deflected (about 6,390 in-scope inquiries remaining per year) by month 6 | April 2027 (month 6 post go-live) | Annualized call-log analysis — ICT telephony report cross-referenced with service categorization | City contact-center telephony system | Not yet annualized (first weeks post-launch only) | October 2026 | **In realization — On track** |
| BEN-02 | Resident self-service adoption rate | Proportion of the 14,200 in-scope inquiries completed online rather than by phone or in person | Non-financial — quantifiable | Sandra Obi | 0% (no portal pre-project) | February 2026 | ≥55% of in-scope inquiries deflected | April 2027 (month 6 post go-live) | Portal transactions completed online, compared with contact-center volume for the same services (GovTech reporting dashboard) | GovTech portal analytics and contact-center logs | Not yet measured. A separate access figure — 41% of eligible residents had opened the portal — is not this measure. | October 31, 2026 (2 weeks post-launch) | **In realization — not yet measured** |
| BEN-03 | Contact-center staff time released | Staff time previously spent handling in-scope inquiries is released for complex or high-value tasks | Financial — non-cashable | Sandra Obi | In-scope transactional handling workload | March 2026 | 1.8 FTE released | April 2027 (month 6 post go-live) | Manager survey + sampled time recording; compared with the pre-project benchmark | Customer Services time study | Not yet measured | — | **Not yet measurable — awaiting month-6 data** |
| BEN-04 | Resident satisfaction with online services | Residents using the portal report a satisfactory or better experience (replaces current dissatisfaction with phone/wait time) | Non-financial — quantifiable | Sandra Obi | 62% satisfaction with phone-based service (resident survey, January 2026) | January 2026 | ≥75% satisfaction with portal experience | Quarterly (first measurement January 2027) | Post-transaction satisfaction survey embedded in portal (automated; GovTech) — 5-point scale | GovTech portal — exit survey | 81% satisfaction (UAT pilot — 68 residents, Sep 2026) | September 2026 (UAT pilot) | **In realization — On track (pilot data positive; full data from Jan 2027)** |
| BEN-05 | Net cashable saving | Financial saving from reduced contact-center handling cost for in-scope services, net of portal running cost | Financial — cashable | James Hartley | $310,000 annual in-scope handling cost | March 2026 | $123,820 net per year ($171,820 gross less $48,000 running cost: $36,000 GovTech support + $12,000 internal administration) | April 2027 (month 6, when the deflection target is measured) and each year thereafter | Finance cost model: 14,200 × 55% × $22, minus annual running cost | Finance / contact-center management accounts | — | — | **Not yet measurable — first full reading at the April 2027 post-implementation review** |
| BEN-06 | Reduction in average transaction processing time | Planning officers and revenues staff spend less time on manual inquiry handling, reducing average time per in-scope transaction | Non-financial — quantifiable | Mark Pearce | 12 minutes average officer time per phone inquiry (in-scope services) | March 2026 (sampled time study — 40 transactions) | ≤5 minutes average officer time per online transaction (portal notifications require less manual follow-up) | June 2027 | Sampled time study (40 transactions) — repeated at 6 months post-launch | ICT / Operations Manager — time study | Not yet measured | — | **Not yet measurable — awaiting 6-month data** |
| BEN-07 | Improved accessibility of city services | Portal meets WCAG 2.1 AA accessibility standards, enabling residents with disabilities to access services who could not previously do so online | Non-financial — qualitative | Sandra Obi | Pre-portal: no accessible online channel for these services | Pre-project | WCAG 2.1 AA compliance at launch; resident accessibility feedback positive | At launch and ongoing | Accessibility audit report; resident feedback (dedicated accessibility feedback form in portal) | Accessibility audit (Sep 2026); resident feedback | WCAG 2.1 AA compliance confirmed | September 26, 2026 | **Achieved (compliance); Ongoing (feedback monitoring)** |

[↑ Back to top](#table-of-contents)

---

## Financial Benefits Summary

| Benefit ID | Year 1 ($) | Year 2 ($) | Year 3 ($) | 3-Year Total ($) |
|---|---|---|---|---|
| BEN-01 / BEN-05: Gross cashable saving (contact-center) | $171,820 | $171,820 | $171,820 | $515,460 |
| **Less: annual running cost** (GovTech support $36,000 + internal administration $12,000) | −$48,000 | −$48,000 | −$48,000 | −$144,000 |
| **Net financial benefit** | **$123,820** | **$123,820** | **$123,820** | **$371,460** |

*Each column is a full year at the business-case run rate, starting once the month-6 deflection target is reached (April 2027). Actual figures will be confirmed at the post-implementation review.*

*Project cost: $374,800. At $123,820 net per year, payback is about 3.0 years ($374,800 / $123,820). Three years of net savings ($371,460) recover nearly all of the actual project cost. Non-cashable and qualitative benefits (BEN-03, BEN-04, BEN-06, BEN-07) are additional value not captured in this table.*

[↑ Back to top](#table-of-contents)

---

## Benefits Realization Milestones

| Milestone | Date | Description | Owner |
|---|---|---|---|
| Baseline measurement complete | March 2026 | Contact-center call volume and staff time baselines established | Sarah Chen (PM) |
| Portal go-live | October 15, 2026 | Benefits realization period begins | Sarah Chen (PM) |
| First post-launch measurement (Month 1) | October 31, 2026 | Initial adoption and call volume data | Sandra Obi |
| Month-6 benefits snapshot | April 15, 2027 | 55% deflection target (BEN-01, BEN-02, BEN-05) | Sandra Obi |
| Post-Implementation Review (PIR) | April 28, 2027 | Full 6-month benefits review — all metrics measured | Sandra Obi (chair) |
| 12-month benefits review | Oct 2027 | Annual benefits performance review | Sandra Obi |
| Benefits register closed | March 2028 (indicative) | All benefits achieved or formally assessed | Sandra Obi / James Hartley |

[↑ Back to top](#table-of-contents)

---

## Post-Implementation Review (PIR) Summary

*To be completed at the PIR on April 28, 2027:*

| Field | Value |
|---|---|
| **PIR date** | April 28, 2027 |
| **PIR lead** | Sandra Obi, Head of Customer Services |
| **Total financial benefits achieved ($)** | *To be confirmed* |
| **Benefits on track** | *To be confirmed* |
| **Benefits at risk** | *To be confirmed* |
| **Benefits not achieved** | *To be confirmed* |
| **Root cause of any shortfall** | *To be confirmed* |
| **Recommended actions** | *To be confirmed* |

[↑ Back to top](#table-of-contents)

---

## Notes on Benefit BEN-01 Baseline

The baseline for BEN-01 (contact-center call volume) was reconstructed from 12 months of historical telephony data (April 2025 – March 2026), cross-referenced with service category codes. The baseline was not established at project initiation — this is recorded as a lesson learned (LL-010) and the Digital PMO has updated the project initiation checklist to require benefits baseline establishment as a Gate 0 condition for all future projects.

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

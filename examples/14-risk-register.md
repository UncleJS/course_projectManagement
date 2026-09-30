# Worked Example: Risk Register
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Risk%20Register-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/risk-register.md`](../templates/risk-register.md) | **Module:** [11 — Risk Management](../modules/11-risk-management.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Probability and Impact Scales](#probability-and-impact-scales)
  - [Probability](#probability)
  - [Impact (threats)](#impact-threats)
  - [Risk Score = Probability × Impact](#risk-score--probability--impact)
- [Risk Register](#risk-register)
- [Opportunity Register](#opportunity-register)
- [Risk Summary](#risk-summary)
- [Response Strategies](#response-strategies)
  - [Threats](#threats)
  - [Opportunities](#opportunities)
- [Risk Categories](#risk-categories)
- [Status Values](#status-values)
- [Escalation Thresholds](#escalation-thresholds)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 2.3 |
| **Date** | August 15, 2026 |
| **Owner** | Sarah Chen, Project Manager |
| **Review frequency** | Every two weeks; at every Project Board meeting |

[↑ Back to top](#table-of-contents)

---

## Probability and Impact Scales

### Probability

| Rating | Label | Description |
|---|---|---|
| 1 | Very Low | Unlikely to occur (<10%) |
| 2 | Low | Possible but unlikely (10–30%) |
| 3 | Medium | Reasonably likely (30–60%) |
| 4 | High | More likely than not (60–80%) |
| 5 | Very High | Almost certain (>80%) |

### Impact (threats)

| Rating | Label | Schedule | Cost | Quality / Scope |
|---|---|---|---|---|
| 1 | Negligible | <1 week slip | <2% over budget | Minor, easily corrected |
| 2 | Minor | 1–2 week slip | 2–5% over budget | Noticeable but manageable |
| 3 | Moderate | 2–4 week slip | 5–10% over budget | Significant rework required |
| 4 | Major | 1–3 month slip | 10–20% over budget | Key deliverable affected |
| 5 | Critical | >3 month slip or cancellation | >20% over budget | Project objectives at risk |

### Risk Score = Probability × Impact

| | **1** | **2** | **3** | **4** | **5** |
|---|---|---|---|---|---|
| **5** | 5 | 10 | 15 | 20 | 25 |
| **4** | 4 | 8 | 12 | 16 | 20 |
| **3** | 3 | 6 | 9 | 12 | 15 |
| **2** | 2 | 4 | 6 | 8 | 10 |
| **1** | 1 | 2 | 3 | 4 | 5 |

**Score 1–4**: Low (monitor) | **Score 5–9**: Medium (manage) | **Score 10–25**: High (act)

[↑ Back to top](#table-of-contents)

---

## Risk Register

| ID | Date raised | Category | Risk description (Cause → Risk → Effect) | Prob | Impact | Score | Level | Response strategy | Response actions | Owner | Residual prob | Residual impact | Residual score | Status | Last reviewed |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| RSK-01 | February 3, 2026 | Technical / Technology | LandWorks (back-office) API may not support all required data queries → Integration takes longer than estimated → Build phase delayed and/or scope reduced | 3 | 4 | **12** | **HIGH** | Mitigate | (1) Early API spike in discovery phase; (2) GovTech to confirm integration approach at Gate 1; (3) Contingency budget allocated for integration complexity. **Partially materialized** — parking permit module deferred via CR-003 (Jul 2026). Remaining three modules confirmed compatible. | Mark Pearce / Tom Okafor | 2 | 2 | **4** | **Materialized → ISS-03** (partial — parking permit deferred via CR-003) | August 15, 2026 |
| RSK-02 | February 3, 2026 | Procurement / Supplier | GovTech Solutions experiences resourcing problems or reprioritizes Meridian → Build and test milestones delayed → Go-live date at risk | 2 | 4 | **8** | **Medium** | Mitigate | (1) Contractual milestone payments tied to delivery; (2) PM weekly check-in with GovTech PM; (3) Early warning indicators reviewed at each PB meeting; (4) Escalation clause in contract if milestone missed by >2 weeks. | Sarah Chen | 2 | 3 | **6** | Open | August 15, 2026 |
| RSK-03 | February 3, 2026 | Resource / People | Named ICT Developer (internal) not confirmed or redirected to other priorities → Integration configuration delayed → Gate 2 slips | 3 | 3 | **9** | **Medium** | Mitigate | (1) Sponsor to confirm ICT resource commitment at project initiation; (2) Named individual (Tom Okafor) confirmed in writing by ICT Manager. **Materialized as ISS-01 (Feb 2026) — resolved March 13, 2026.** | Mark Pearce | 1 | 3 | **3** | **Materialized → ISS-01** | August 15, 2026 |
| RSK-04 | February 3, 2026 | Stakeholder / Political | Key stakeholders (planning officers, revenues staff) resist using portal → Staff adoption below target → Benefits not realized post-launch | 3 | 3 | **9** | **Medium** | Mitigate | (1) Business Change Manager appointed to lead staff engagement; (2) Early involvement of frontline staff in user research; (3) Training program in plan for Aug–Sep 2026; (4) Benefits target (55% deflection by month 6) formally owned by Senior User. | Diane Hughes (BCM) | 2 | 3 | **6** | Open | August 15, 2026 |
| RSK-05 | February 3, 2026 | Stakeholder / Political | Resident adoption below the 55% deflection target by April 2027 (month 6) → Property tax saving from reduced contact-center volume does not materialize → Benefits case not met | 3 | 3 | **9** | **Medium** | Mitigate | (1) UX research embedded in discovery phase; (2) Accessibility audit scheduled Sep 2026; (3) Resident marketing and communications campaign planned Aug–Sep 2026; (4) Soft launch with 1,000 invited residents before full go-live. | Diane Hughes (BCM) | 2 | 3 | **6** | Open | August 15, 2026 |
| RSK-06 | February 3, 2026 | Regulatory / Legal | PIA reveals data protection compliance issue with proposed data flows → Portal design requires significant rework → Schedule and cost impact | 2 | 4 | **8** | **Medium** | Mitigate | (1) the Chief Privacy Officer engaged from project initiation; (2) PIA completed during discovery phase and signed off May 5, 2026 — no blocking issues found; (3) Data retention and consent design reviewed. | Chief Privacy Officer | 1 | 2 | **2** | **Closed — Expired** | August 15, 2026 |
| RSK-07 | February 3, 2026 | Financial / Commercial | Contingency ($38,000) exhausted by scope changes before build phase completes → Project over-runs budget → Additional funding required or scope reduced | 2 | 4 | **8** | **Medium** | Mitigate | (1) Formal change control for all scope changes; (2) Contingency draw-down requires Sponsor approval above $5,000; (3) EVM reported at each Project Board; (4) Monthly budget report to Sponsor. | Sarah Chen | 1 | 4 | **4** | Open | August 15, 2026 |
| RSK-08 | April 4, 2026 | Technical / Technology | Property tax payment gateway (Harbor Payments) requires security certification before portal can process live payments → Integration delayed → Module delayed at UAT | 3 | 3 | **9** | **Medium** | Mitigate | Security audit scheduled and completed (July 14, 2026) — 2 minor findings resolved July 21, 2026. Integration certified. | Mark Pearce | 1 | 2 | **2** | **Materialized → ISS-04** | August 15, 2026 |
| RSK-09 | May 11, 2026 | Schedule / Time | Extended UAT defect cycle (high defect count at entry) → UAT window extends beyond planned dates → Go-live delayed | 2 | 4 | **8** | **Medium** | Mitigate | (1) GovTech contractually responsible for defect-free UAT entry (defined entry criteria); (2) Internal test phase (SIT) strengthened; (3) Contingency in schedule — 2-week float between UAT end and go-live. | GovTech Project Lead | 2 | 3 | **6** | Open | August 15, 2026 |
| RSK-10 | February 3, 2026 | External / Environmental | Key sponsor (James Hartley) leaves or is redeployed before project closes → Sponsor decisions delayed; political support reduced → Project stalls | 1 | 5 | **5** | **Medium** | Accept (active) | (1) Documented governance structure ensures project can continue with acting sponsor; (2) Business case and all decisions documented to enable handover; (3) Noted in project risk profile for Sponsor's awareness. | Sarah Chen | 1 | 5 | **5** | Open | August 15, 2026 |

[↑ Back to top](#table-of-contents)

---

## Opportunity Register

| ID | Date raised | Opportunity description | Prob | Impact | Score | Strategy | Actions | Owner | Status |
|---|---|---|---|---|---|---|---|---|---|
| OPP-01 | February 3, 2026 | GovTech platform can support additional city services beyond the four in scope → Phase 2 extension possible at marginal cost | 3 | 3 | 9 | Enhance | Document platform capability for Phase 2 business case; ensure Phase 1 architecture does not preclude expansion | Sarah Chen | Open |
| OPP-02 | May 8, 2026 | Strong resident satisfaction scores in Phase 1 pilot → Enhanced case for Phase 2 funding and possible national showcase opportunity | 2 | 3 | 6 | Accept | Monitor the digital satisfaction index in the pilot; brief Communications on positive results | Diane Hughes | Open |

[↑ Back to top](#table-of-contents)

---

## Risk Summary

| Level | Count | Open | Closed / Materialized |
|---|---|---|---|
| **High** | 1 | 0 | 1 (RSK-01 — partially materialized) |
| **Medium** | 9 | 6 | 3 |
| **Low** | 0 | 0 | 0 |
| **Opportunity** | 2 | 2 | 0 |

> **Note on RSK-01**: The LandWorks integration risk partially materialized — parking permits could not be integrated as specified (ISS-03). The risk was addressed via Change Request CR-003 (parking permit module deferred to Phase 2), approved by Project Board July 8, 2026. The remaining three modules were confirmed as technically compatible. The risk is closed.

[↑ Back to top](#table-of-contents)

---

## Response Strategies

### Threats

| Strategy | Description |
|---|---|
| **Avoid** | Eliminate the cause; change the plan to remove the risk entirely |
| **Transfer** | Shift the financial or operational impact to a third party (insurance, contract) |
| **Mitigate** | Take action to reduce probability and/or impact to an acceptable level |
| **Accept** | Acknowledge the risk; no proactive action (passive) or set aside contingency (active) |
| **Escalate** | The risk is beyond the project's authority to manage; escalate to program or sponsor |

### Opportunities

| Strategy | Description |
|---|---|
| **Exploit** | Ensure the opportunity definitely occurs |
| **Enhance** | Increase the probability or impact of the opportunity |
| **Share** | Partner with a third party best placed to realize the opportunity |
| **Accept** | Take the benefit if it arises; no proactive action |
| **Escalate** | The opportunity is beyond the project scope; escalate for strategic consideration |

[↑ Back to top](#table-of-contents)

---

## Risk Categories

The following categories are used to classify risks on this project:

- Strategic / Business
- Technical / Technology
- Resource / People
- Schedule / Time
- Financial / Commercial
- Stakeholder / Political
- External / Environmental
- Regulatory / Legal
- Procurement / Supplier

[↑ Back to top](#table-of-contents)

---

## Status Values

| Status | Meaning |
|---|---|
| Open | Active risk being managed |
| Closed — Avoided | Risk cause was eliminated |
| Closed — Transferred | Risk transferred to third party |
| Closed — Expired | Risk window has passed without occurring |
| Materialized → Issue | Risk has occurred; now recorded in the Issue Log (e.g. Materialized → ISS-03) |

[↑ Back to top](#table-of-contents)

---

## Escalation Thresholds

| Score | Action |
|---|---|
| 1–4 (Low) | PM monitors; reviewed every two weeks |
| 5–9 (Medium) | PM manages; action plan in place; reported to Project Board monthly |
| 10–25 (High) | Immediate Sponsor notification; action plan reviewed weekly; Project Board decision within 2 weeks |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

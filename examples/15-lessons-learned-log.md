# Worked Example: Lessons Learned Log
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Lessons%20Learned%20Log-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/lessons-learned-log.md`](../templates/lessons-learned-log.md) | **Module:** [07 — Project Closing](../modules/07-closing.md)

---

## Table of Contents

- [Document Control](#document-control)
- [How Lessons Were Captured](#how-lessons-were-captured)
- [Lessons Learned Log](#lessons-learned-log)
- [Categories](#categories)
- [Status Values](#status-values)
- [Top 5 Lessons (Summary for Closure Report)](#top-5-lessons-summary-for-closure-report)
- [Lessons Workshop Summary](#lessons-workshop-summary)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.0 (Final — at project closure) |
| **Date** | October 31, 2026 |
| **Owner** | Sarah Chen, Project Manager |
| **Distribution at closure** | James Hartley (Sponsor), Digital PMO, ICT Directorate, GovTech Solutions, Future project teams |

[↑ Back to top](#table-of-contents)

---

## How Lessons Were Captured

Lessons were captured at four points during the project:

1. **Gate 1 (May 8, 2026)**: Review of Discovery and Design phase — facilitated retrospective with core team.
2. **Gate 2 (August 7, 2026)**: Build complete, on the baseline date — facilitated retrospective with the core team.
3. **Integration review (September 11, 2026)**: Held when UAT actually started. SIT had been signed off on September 4.
4. **Project Closure (October 28, 2026)**: Full lessons-learned workshop with all stakeholder groups; 18 attendees.

Each lesson follows the three-part structure: **what happened → root cause → recommendation**.

[↑ Back to top](#table-of-contents)

---

## Lessons Learned Log

| ID | Date captured | Phase | Category | What happened | Root cause | Recommendation | Positive / Negative | Action owner | Status |
|---|---|---|---|---|---|---|---|---|---|
| LL-001 | May 8, 2026 | Initiation | Resource / team management | The ICT Developer role was not formally named or committed in the project charter. ISS-01 was raised on March 8, 2026 because no internal resource had been confirmed for the integration phase. The Sponsor resolved it on March 13, 2026, when Tom Okafor was named, well before Gate 1 on May 8. The gap was at the start of the project, not at the gate. | Resource commitments for internal supplier roles were treated as informal understandings rather than formal project commitments. There was no mechanism in the project charter to capture named ICT resources. | Future project charters involving internal supplier teams should include a named resource commitment section, signed by the relevant line manager or ICT Manager. The Charter should not be approved without confirmed names for all delivery-critical roles. | Negative | Digital PMO | Submitted to PMO |
| LL-002 | May 8, 2026 | Initiation | Procurement / supplier management | The Business Change Manager role was not filled at project initiation — it was assumed that a suitable person would be seconded. In practice, the role was not confirmed until April 22, 2026 (nearly 3 months into the project), leaving staff engagement unmanaged during the critical design phase. | The role was identified as important but not essential to the early phases, so it was deprioritized. No owner was assigned to recruiting the BCM, and the PM had no authority to compel HR to act. | Projects with a significant organizational change dimension (staff behavior change, adoption risk) should have a BCM confirmed before the initiation stage gate. The BCM role should be treated as a delivery-critical resource, not a support role. Sponsor should own BCM appointment as a project initiation condition. | Negative | Digital PMO | Submitted to PMO |
| LL-003 | June 17, 2026 | Build | Technology / technical approach | The LandWorks system's API limitations for parking permit data were not identified during pre-project scoping or at Gate 1. Integration testing on June 17, 2026 showed that parking-permit expiry data is stored as a scanned attachment and cannot be queried. That finding was raised as ISS-03, led to Change Request CR-003, and deferred the parking permit module to Phase 2. The risk had been listed as RSK-01 but had not been characterized at the level of specific data fields. | The pre-project technical scoping had relied on high-level assurances from the LandWorks vendor that API access was available, without testing specific data fields. No technical spike or proof-of-concept was conducted before the business case was finalized. | For projects integrating with legacy back-office systems, a technical feasibility spike (proof-of-concept test of specific data queries) should be completed before the business case is finalized. API access claims should be evidenced, not assumed. | Negative | Digital PMO | Submitted to PMO |
| LL-004 | May 8, 2026 | Discovery | Stakeholder engagement | The early involvement of frontline planning officers in the UX research produced genuinely better design outcomes. Two features that had been assumed based on management input were deprioritized after user research showed they were low value. The design was accepted faster at Gate 1 because senior users trusted the evidence base. | The Senior User (Sandra Obi) had championed a user research approach from the outset, which the PM and GovTech supported. The decision to invest in structured user research (interviews and task-based testing with 12 residents and 8 planning officers) was made early. | Front-load user research investment in digital service projects. Early engagement of end users in design produces faster acceptance, better outcomes, and reduced rework. Budget for at least 2 rounds of user testing in the discovery phase. | Positive | Digital PMO | Submitted to PMO |
| LL-005 | September 11, 2026 | Build | Procurement / supplier management | The payment gateway security audit (ISS-04) was not included in the project plan, because the requirement for a Harbor Payments security certification before live integration was unknown at project initiation. The issue was resolved efficiently (audit completed July 14, 2026), but it created a 3-week uncertainty window in the build schedule. | The requirement for third-party security certification before live payment integration was a Harbor Payments contractual requirement that was not surfaced during the procurement phase. Neither GovTech nor ICT had flagged it as a project dependency. | Payment gateway integration requirements (including third-party security audit requirements) should be explicitly confirmed as part of technical scoping. Supplier contracts should include a standard prompt: "what third-party certifications, audits, or approvals are required before this component can go live?" | Negative | Digital PMO | Submitted to PMO |
| LL-006 | September 11, 2026 | Build | Change control | The formal change request process worked well for CR-003 (parking permit deferral). However, three informal scope adjustments were implemented by GovTech during the build phase without change requests (minor UI changes requested verbally by Sandra Obi). These were technically small but collectively represented approximately $4,200 of untracked effort that GovTech absorbed without complaint — this time. | The change control procedure was clear in the project management plan, but there was no explicit escalation process for "minor" changes requested directly by stakeholders to the supplier. GovTech accommodated small requests as goodwill, which masked the issue. | Project communication to all stakeholders should explicitly state that all change requests — regardless of size — must go through the PM. Supplier contracts should include a clause requiring the supplier to notify the PM of any scope requests received directly from other stakeholders. | Negative | Sarah Chen | Actioned (this project) |
| LL-007 | October 8, 2026 | Closure | Schedule management | The plan held 13 days between the end of UAT (September 18) and go-live (October 1). Contact-center training was planned inside that window, on September 25. UAT actually ran from September 11 to September 25 and finished 7 days late. Training then finished on October 2. The project kept the same gap for training and cutover, so go-live moved by those 7 days, from October 1 to October 8 (CR-006). | The gap was included at the PM's insistence during planning, over an initial Sponsor preference for an earlier go-live date. It was already filled with training and cutover. It was not spare time that could be given up to hold October 1. | If activities are planned inside a gap, name them. A late finish then moves the next milestone by the same number of days. Do not describe that gap as float that can absorb the slip. | Positive | Digital PMO | Submitted to PMO |
| LL-008 | October 28, 2026 | Closure | Organizational change management | The resident communications campaign (Aug–Sep 2026) drove far higher initial awareness than expected — 68% of residents who attended the campaign were aware of the portal before launch (target: 50%). This translated into early use: 41% of eligible residents had accessed the portal by the end of October. That access figure is not the 55% inquiry-deflection target, which is measured in April 2027 (month 6). | The BCM (Diane Hughes) brought strong community communications skills from her previous Digital Communications role. She had existing relationships with community groups and local media. The campaign was well-resourced and given adequate lead time (planning began June 2026). | Digital projects with public-facing services should invest in a dedicated communications and engagement plan, led by someone with community-facing communications experience. The BCM role is not just internal (staff); it includes external (resident) adoption. | Positive | Digital PMO | Submitted to PMO |
| LL-009 | October 28, 2026 | All phases | Project governance / sponsorship | James Hartley (Sponsor) was consistently available for escalations and decisions throughout the project. All escalations were resolved within agreed timescales. The Project Board met on schedule (no meeting canceled). This made a measurable difference — ISS-01 and ISS-02 were resolved weeks faster because the Sponsor acted promptly. | The Sponsor had been personally involved in the project's business case development and had a genuine interest in the outcome. The PM invested time upfront in agreeing the sponsorship compact (what decisions the PM needed from the Sponsor and at what timescale). | A sponsorship compact — a brief written agreement on the Sponsor's expected time commitment, decision timescales, and escalation protocol — should be agreed and signed at project initiation. This is particularly important when the PM is at a more junior level than the Sponsor. | Positive | Digital PMO | Submitted to PMO |
| LL-010 | October 28, 2026 | Closure | Project closure | The project closure report and handover documentation were drafted during the final month of the project (October 2026), allowing a smooth formal closure on October 31. However, the benefits register was not set up with baseline measures until Month 2 — meaning the Month 0 baseline for contact-center call volume (the primary benefits metric) had to be reconstructed from historical call logs rather than measured directly. | Benefits measurement was not treated as a project planning task from initiation. The benefits register was created in the second month, after other planning activities had been completed. | The benefits register, including baseline measurements and measurement methodology, should be completed during project initiation — before any project activity that might affect the baseline. Benefits measurement is a project planning task, not a post-project task. | Negative | Digital PMO | Submitted to PMO |

[↑ Back to top](#table-of-contents)

---

## Categories

The following categories are used to classify lessons on this project:

- Project governance / sponsorship
- Initiation and business case
- Planning / estimating
- Scope and requirements management
- Schedule management
- Budget / cost management
- Risk management
- Issue management
- Change control
- Quality management
- Procurement / supplier management
- Stakeholder engagement
- Communications
- Resource / team management
- Technology / technical approach
- Organizational change management
- Project closure

[↑ Back to top](#table-of-contents)

---

## Status Values

| Status | Meaning |
|---|---|
| Captured | Lesson recorded; not yet reviewed |
| Reviewed | Reviewed by PM; recommendation confirmed |
| Actioned (this project) | Recommendation implemented within this project |
| Submitted to PMO | Shared with the PMO / knowledge base for future projects |
| Closed | No further action required |

[↑ Back to top](#table-of-contents)

---

## Top 5 Lessons (Summary for Closure Report)

| # | Lesson | Recommendation |
|---|---|---|
| 1 | ICT resource commitments must be named and signed in the project charter | Add named resource commitment section to project charter template |
| 2 | BCM must be confirmed before initiation stage gate on change-intensive projects | Treat BCM as delivery-critical; include as initiation approval condition |
| 3 | Legacy API integration requires a technical spike before business case finalization | Build API proof-of-concept into pre-project scoping for all LandWorks-dependent projects |
| 4 | Benefits baseline must be established at project initiation, not after | Update project initiation checklist: benefits register with baselines is a gate condition |
| 5 | The 13 days after UAT were already planned for training and cutover. UAT finished 7 days late, so go-live moved 7 days, to October 8 | Name the activities inside a gap. If they stay, a late UAT finish moves go-live by the same number of days |

[↑ Back to top](#table-of-contents)

---

## Lessons Workshop Summary

**Date**: October 28, 2026
**Facilitator**: Sarah Chen (PM)
**Attendees**: James Hartley, Sandra Obi, Mark Pearce, Tom Okafor, Diane Hughes, Claire Worthington, GovTech Project Lead, 10 frontline staff participants

**Tone**: Constructive and honest. No blame culture observed. Frontline staff were particularly candid about the BCM gap in early phases — and equally positive about the communications campaign.

**Outstanding action**: PMO to schedule 6-month post-implementation review (April 2027) to validate benefits realization data.

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

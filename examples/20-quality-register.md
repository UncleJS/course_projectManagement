# Worked Example: Quality Register
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Quality%20Register-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/quality-register.md`](../templates/quality-register.md) | **Module:** [12 — Quality Management](../modules/12-quality-management.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Quality Activity Types](#quality-activity-types)
- [Quality Register](#quality-register)
- [Defect Log Summary](#defect-log-summary)
- [Quality Metrics Summary](#quality-metrics-summary)
- [Quality Audit Schedule (Planned vs Actual)](#quality-audit-schedule-planned-vs-actual)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.6 (final — at project closure) |
| **Date** | 31 October 2026 |
| **Owner** | Sarah Chen, Project Manager / GovTech Project Lead (Quality Lead — Build) |

[↑ Back to top](#table-of-contents)

---

## Quality Activity Types

| Type | Description |
|---|---|
| **Quality Review** | Structured meeting to evaluate a deliverable against pre-defined acceptance criteria |
| **Technical Inspection** | Expert review of code, integration specification, or technical artefact |
| **Test** | Functional, integration, regression, performance, or user acceptance testing |
| **Audit** | Independent assessment of process or product compliance (accessibility, data protection, security) |
| **Walkthrough** | Informal peer review of a draft deliverable before formal quality review |

[↑ Back to top](#table-of-contents)

---

## Quality Register

| ID | Deliverable / process reviewed | Activity type | Planned date | Actual date | Reviewer(s) | Criteria used | Outcome | Defects found | Defects resolved | Sign-off date | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|
| QR-001 | Discovery Report | Quality Review | 30 Apr 2026 | 30 Apr 2026 | Sarah Chen, Sandra Obi, Mark Pearce | Project brief requirements checklist; Discovery Report acceptance criteria | **Passed** | 2 (minor — missing resident demographic data; formatting) | 2 | 4 May 2026 | Approved for Gate 1 pack |
| QR-002 | UX Design Specification | Quality Review | 4 May 2026 | 4 May 2026 | Sandra Obi (Senior User), GovTech Lead Designer, Sarah Chen | User story acceptance criteria; Council brand guidelines; WCAG 2.1 AA preliminary checklist | **Conditional pass** | 4 (medium — 2 navigation issues; 2 mobile responsiveness concerns) | 4 | 7 May 2026 | Conditions met before Gate 1 (8 May). Approved. |
| QR-003 | Integration Specification | Technical Inspection | 5 May 2026 | 6 May 2026 | Tom Okafor, GovTech Lead Developer, Mark Pearce | Integration design standards; UNIFORM/Civica/Capita API documentation | **Conditional pass** | 3 (medium — UNIFORM parking permits issue identified; 2 minor API configuration issues) | 3 | 8 May 2026 | UNIFORM parking permit issue escalated as ISS-03 / CR-003. Other issues resolved. |
| QR-004 | Data Protection Impact Assessment (DPIA) | Audit | 1 May 2026 | 2 May 2026 | Claire Worthington (DPO) | UK GDPR; ICO DPIA guidance; Council Data Protection Policy | **Passed** | 1 (low — minor privacy notice wording clarification) | 1 | 5 May 2026 | DPO sign-off confirmed 5 May 2026 |
| QR-005 | Sprint 1 Demo — Planning application module (build) | Quality Review | 5 Jun 2026 | 5 Jun 2026 | Sandra Obi, Sarah Chen, Tom Okafor | Sprint 1 acceptance criteria (12 user stories) | **Passed** | 3 (low — UI cosmetic issues) | 3 | 9 Jun 2026 | 12/12 user stories accepted |
| QR-006 | Sprint 2 Demo — Waste collection module (build) | Quality Review | 3 Jul 2026 | 3 Jul 2026 | Sandra Obi, Sarah Chen, Tom Okafor | Sprint 2 acceptance criteria (10 user stories) | **Passed** | 2 (low — cosmetic) | 2 | 7 Jul 2026 | 10/10 user stories accepted |
| QR-007 | Sprint 3 Demo — Council tax module (build) | Quality Review | 31 Jul 2026 | 31 Jul 2026 | Sandra Obi, Mark Pearce, Sarah Chen | Sprint 3 acceptance criteria (14 user stories); Capita payment security requirements | **Conditional pass** | 5 (medium — 3 Capita payment integration issues; 2 display bugs) | 5 | 7 Aug 2026 | Capita security audit completed 14 Jul (separate — see QR-009). Integration issues resolved by 7 Aug. |
| QR-008 | Sprint 4 Demo — Garden waste module (build) | Quality Review | 28 Aug 2026 | 28 Aug 2026 | Sandra Obi, Sarah Chen | Sprint 4 acceptance criteria (8 user stories) | **Passed** | 1 (low — wording) | 1 | 1 Sep 2026 | 8/8 user stories accepted |
| QR-009 | Capita payment gateway security audit | Audit | 10 Jul 2026 | 10 Jul 2026 | Capita security team (independent) | Capita payment gateway integration security standard (PCI-DSS-aligned) | **Conditional pass** | 2 (medium — token handling; session timeout configuration) | 2 | 21 Jul 2026 | Audit required by Capita contract; passed with 2 minor findings resolved 21 Jul. Certificate issued. |
| QR-010 | System Integration Test (SIT) | Test | 22 Aug 2026 | 22 Aug 2026 | Tom Okafor, GovTech Test Lead | SIT test script (87 test cases) covering all four modules and back-office integrations | **Passed** | 7 (5 medium, 2 low — no critical) | 7 | 4 Sep 2026 | All 87 test cases executed; 7 defects found and resolved by 4 Sep. UAT entry criteria met. |
| QR-011 | User Acceptance Testing (UAT) | Test | 22 Aug 2026 (planned entry) | 11 Sep 2026 | Sandra Obi (UAT lead), Diane Hughes, 12 resident testers, 6 planning officers, 4 revenues staff | 47 UAT acceptance scenarios; Council's UAT entry criteria (0 P1/Critical defects at entry) | **Passed** | 47 (0 critical, 18 medium, 29 low) | 47 | 26 Sep 2026 | UAT ran 11–26 Sep. All defects resolved. All 47 scenarios signed off by Sandra Obi. |
| QR-012 | Accessibility audit (Round 1) | Audit | 5 Sep 2026 | 8 Sep 2026 | Shaw Trust Digital (independent accessibility auditors) | WCAG 2.1 AA (Level A and AA criteria) | **Failed** | 14 (4 high, 6 medium, 4 low) | 0 (at time of audit) | — | Independent audit commissioned. Round 2 scheduled after remediation. |
| QR-013 | Accessibility remediation review | Technical Inspection | 19 Sep 2026 | 19 Sep 2026 | GovTech Lead Developer, Tom Okafor | QR-012 findings — all 14 issues; WCAG 2.1 AA | **Passed** | 0 | 14/14 (all QR-012 defects resolved) | 26 Sep 2026 | All 14 accessibility defects resolved. Shaw Trust confirmed WCAG 2.1 AA compliance 26 Sep. |
| QR-014 | Android device compatibility check | Test | 20 Aug 2026 | 22 Aug 2026 | GovTech Test Lead | Mobile browser compatibility matrix (iOS 14+, Android 9+, major desktop browsers) | **Conditional pass** | 1 (medium — Android 8 and below layout issue; ISS-06) | 1 | 25 Aug 2026 | Android 8 and below: layout issue (ISS-06). Fix deployed 22 Aug; re-test confirmed 25 Aug. |
| QR-015 | Pre-launch production readiness check | Quality Review | 13 Oct 2026 | 13 Oct 2026 | Sarah Chen, Tom Okafor, GovTech PM, Mark Pearce | Production readiness checklist (16 items): infrastructure, DNS, SSL, monitoring, support ready, data backup, rollback plan | **Passed** | 0 | — | 13 Oct 2026 | All 16 readiness criteria confirmed. Go/No-go decision: **Go**. Launch approved for 15 Oct. |
| QR-016 | Post-launch monitoring review (Week 1) | Quality Review | 22 Oct 2026 | 22 Oct 2026 | Tom Okafor, GovTech PM, Sarah Chen | Uptime SLA (≥99.5%); response time (<3s); error rate (<0.5%) | **Passed** | 0 | — | 22 Oct 2026 | Week 1: 99.8% uptime; avg response time 1.4s; error rate 0.1%. All within SLA. |

[↑ Back to top](#table-of-contents)

---

## Defect Log Summary

| QR ID | Defects found | Severity breakdown (Critical / High / Medium / Low) | Defects resolved | Outstanding at closure |
|---|---|---|---|---|
| QR-001 | 2 | 0 / 0 / 0 / 2 | 2 | 0 |
| QR-002 | 4 | 0 / 0 / 4 / 0 | 4 | 0 |
| QR-003 | 3 | 0 / 0 / 3 / 0 | 3 | 0 |
| QR-004 | 1 | 0 / 0 / 0 / 1 | 1 | 0 |
| QR-005 to QR-008 (Sprint demos) | 11 | 0 / 0 / 3 / 8 | 11 | 0 |
| QR-009 (Capita security audit) | 2 | 0 / 0 / 2 / 0 | 2 | 0 |
| QR-010 (SIT) | 7 | 0 / 0 / 5 / 2 | 7 | 0 |
| QR-011 (UAT) | 47 | 0 / 0 / 18 / 29 | 47 | 0 |
| QR-012 (Accessibility audit) | 14 | 0 / 4 / 6 / 4 | 14 | 0 |
| QR-014 (Android compatibility) | 1 | 0 / 0 / 1 / 0 | 1 | 0 |
| **Total** | **92** | **0 / 4 / 42 / 46** | **92** | **0** |

> **No critical defects were identified at any stage of the project.** The UAT defect profile (47 defects, all medium or low) was within the expected range for a project of this complexity. All defects were resolved before go-live.

[↑ Back to top](#table-of-contents)

---

## Quality Metrics Summary

| Metric | Target | Actual | Status |
|---|---|---|---|
| % deliverables passing first review (no "Failed" outcome) | ≥80% | 94% (15/16 reviews passed or conditional — 1 failed: QR-012 accessibility; remediated and re-passed) | ✅ Met |
| Critical defect rate at UAT entry | 0 | 0 | ✅ Met |
| High defects at UAT | <5 | 0 | ✅ Met |
| Medium defects at UAT | <20 | 18 | ✅ Met |
| Audits completed on schedule | 100% | 100% (all 3 formal audits: DPIA, Capita security, accessibility) | ✅ Met |
| Open defects at go-live | 0 critical or high | 0 | ✅ Met |
| WCAG 2.1 AA compliance at launch | 100% | 100% | ✅ Met |
| Production uptime Week 1 | ≥99.5% | 99.8% | ✅ Met |

[↑ Back to top](#table-of-contents)

---

## Quality Audit Schedule (Planned vs Actual)

| Audit | Planned date | Actual date | Auditor | Scope | Status |
|---|---|---|---|---|---|
| DPIA (data protection) | 1 May 2026 | 2 May 2026 | Claire Worthington (DPO) | UK GDPR compliance; data flows; privacy notice | ✅ Completed — Passed |
| Capita payment security audit | 10 Jul 2026 | 10 Jul 2026 | Capita security team | PCI-DSS-aligned payment gateway integration | ✅ Completed — Conditional pass; resolved |
| Accessibility audit (WCAG 2.1 AA) | 5 Sep 2026 | 8 Sep 2026 | Shaw Trust Digital | WCAG 2.1 AA — all portal pages and transactions | ✅ Completed — Failed Round 1; all issues resolved; AA compliance confirmed 26 Sep |
| Pre-launch production readiness | 13 Oct 2026 | 13 Oct 2026 | Sarah Chen / Tom Okafor | 16-item production readiness checklist | ✅ Completed — Passed |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

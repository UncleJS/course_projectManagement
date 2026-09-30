# Worked Example: Work Breakdown Structure
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-WBS-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/wbs.md`](../templates/wbs.md) | **Module:** [04 — Project Planning](../modules/04-planning.md)

---

## Table of Contents

- [Document Control](#document-control)
- [WBS Overview](#wbs-overview)
- [WBS — Hierarchical View](#wbs--hierarchical-view)
- [WBS Dictionary (Work Package Descriptions)](#wbs-dictionary-work-package-descriptions)
  - [1.2.3 — Discovery Report](#123--discovery-report)
  - [1.3.6 — LandWorks Integration (Tested)](#136--landworks-integration-tested)
  - [1.5.4 — User Acceptance Testing Sign-off](#154--user-acceptance-testing-sign-off)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Version** | 1.1 |
| **Date** | February 20, 2026 |
| **Prepared by** | Sarah Chen, Project Manager |
| **Approved by** | James Hartley, Sponsor |

[↑ Back to top](#table-of-contents)

---

## WBS Overview

The WBS is a hierarchical decomposition of project scope into deliverables. It follows the **100% rule**: the sum of all elements at any level represents 100% of the parent element's scope.

**Important:** The WBS contains **deliverables** (things produced), not activities (things done).

[↑ Back to top](#table-of-contents)

---

## WBS — Hierarchical View

```
1.0  MERIDIAN PORTAL
 │
 ├── 1.1  PROJECT MANAGEMENT
 │    ├── 1.1.1  Project Management Plan
 │    ├── 1.1.2  Progress Reports (Highlight Reports)
 │    ├── 1.1.3  Risk Register (maintained throughout)
 │    ├── 1.1.4  Change Log (maintained throughout)
 │    └── 1.1.5  Project Closure Report
 │
 ├── 1.2  INITIATION AND DESIGN
 │    ├── 1.2.1  Signed Supplier Contract
 │    ├── 1.2.2  PIA (Privacy Impact Assessment)
 │    ├── 1.2.3  Discovery Report
 │    ├── 1.2.4  UX Design Specification
 │    ├── 1.2.5  Integration Specification (LandWorks connector)
 │    └── 1.2.6  Content Plan (all four service modules)
 │
 ├── 1.3  PLATFORM BUILD AND INTEGRATION
 │    ├── 1.3.1  Configured CivicConnect Platform (test environment)
 │    ├── 1.3.2  Planning Application Tracking Module
 │    ├── 1.3.3  Property Tax Payment and Account Management Module
 │    ├── 1.3.4  Waste Reporting Module (Missed and Yard Waste)
 │    ├── 1.3.5  Parking Permit Renewal Module
 │    └── 1.3.6  LandWorks Integration (tested)
 │
 ├── 1.4  CONTENT AND USER EXPERIENCE
 │    ├── 1.4.1  Written Content (all four service modules)
 │    ├── 1.4.2  Accessibility Compliance Sign-off (WCAG 2.1 AA)
 │    └── 1.4.3  Branding and Design Assets
 │
 ├── 1.5  TESTING
 │    ├── 1.5.1  System Integration Test Results
 │    ├── 1.5.2  Performance Test Results
 │    ├── 1.5.3  Accessibility Test Results
 │    └── 1.5.4  User Acceptance Testing Sign-off
 │
 ├── 1.6  TRAINING AND CHANGE
 │    ├── 1.6.1  Training Materials (54 in-scope service staff)
 │    ├── 1.6.2  Training Completion Records
 │    └── 1.6.3  Resident Communications Materials
 │
 └── 1.7  GO-LIVE AND HANDOVER
      ├── 1.7.1  Production Portal (live)
      ├── 1.7.2  Go-live Authorization Record
      ├── 1.7.3  Operations Runbook
      └── 1.7.4  Project Handover Document
```

[↑ Back to top](#table-of-contents)

---

## WBS Dictionary (Work Package Descriptions)

### 1.2.3 — Discovery Report

| Field | Content |
|---|---|
| **WBS Code** | 1.2.3 |
| **Title** | Discovery Report |
| **Description** | A report summarizing the outputs of the discovery phase: current-state analysis of the four service areas, resident research findings (interviews and surveys), technical integration requirements, and prioritized feature list for the portal. |
| **Acceptance criteria** | (1) Covers all four service modules; (2) Includes at least 15 resident research participants; (3) Identifies and documents the data fields each service module needs from its own system: LandWorks for planning and parking permits, Civica Waste for missed trash and yard waste, and Harbor Payments for property tax payments; (4) Reviewed and approved by Senior User (Sandra Obi) and Senior Supplier (Mark Pearce); (5) Presented to Project Board at Gate 1. |
| **Owner** | GovTech Solutions Inc. (with city sign-off) |
| **Assumptions** | City staff are available for discovery interviews (estimated 10 interviews across 3 departments). |
| **Estimated duration** | 6 weeks (March 3 – April 17, 2026) |
| **Estimated cost** | Included in GovTech fixed-price contract (WP1) |
| **Dependencies** | 1.2.1 (Supplier contract signed) |

[↑ Back to top](#table-of-contents)

---

### 1.3.6 — LandWorks Integration (Tested)

| Field | Content |
|---|---|
| **WBS Code** | 1.3.6 |
| **Title** | LandWorks Integration (Tested) |
| **Description** | Tested integrations for the four service modules. LandWorks supplies planning status and parking-permit data. Civica Waste handles missed-trash reports and yard-waste renewals. Harbor Payments handles property tax payments. |
| **Acceptance criteria** | (1) Planning and parking-permit data exchange with LandWorks; missed trash and yard waste exchange with Civica Waste; property tax payments exchange with Harbor Payments; (2) No data loss or corruption in integration tests across 500+ test transactions; (3) Integration does not cause degradation in LandWorks response times (< 2-second API response time under load); (4) Signed off by Mark Pearce (ICT Manager). |
| **Owner** | GovTech Solutions Inc. (build) and Mark Pearce / ICT (acceptance) |
| **Assumptions** | GovTech LandWorks API connector requires configuration only (ASM-05); ICT test environment is available from July 2026. |
| **Estimated duration** | 8 weeks build + 2 weeks test (June – August 2026) |
| **Estimated cost** | $48,000 (ICT internal resource cost; GovTech cost included in platform build) |
| **Dependencies** | 1.2.5 (Integration specification), 1.2.3 (Discovery report) |

[↑ Back to top](#table-of-contents)

---

### 1.5.4 — User Acceptance Testing Sign-off

| Field | Content |
|---|---|
| **WBS Code** | 1.5.4 |
| **Title** | User Acceptance Testing Sign-off |
| **Description** | A formal document confirming that user acceptance testing has been completed satisfactorily. UAT to be conducted by a minimum of 30 Northgate residents. All Priority 1 (critical) defects resolved before sign-off; Priority 2 defects either resolved or deferred with documented rationale. |
| **Acceptance criteria** | (1) Minimum 30 residents have completed end-to-end testing of at least one service module; (2) All P1 defects resolved and regression-tested; (3) P2 defect list reviewed and dispositioned; (4) Signed by Sandra Obi (Senior User) and James Hartley (Sponsor). |
| **Owner** | Sarah Chen (coordination) / Sandra Obi (sign-off authority) |
| **Assumptions** | Resident UAT panel recruited by August 2026 (City comms team). |
| **Estimated duration** | 25 days (August 24 – September 18, 2026) |
| **Estimated cost** | Included in project management costs; GovTech UAT support included in contract |
| **Dependencies** | 1.3.1–1.3.6 (all build elements complete); 1.4.2 (accessibility sign-off) |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

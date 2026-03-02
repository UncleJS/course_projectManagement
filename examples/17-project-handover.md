# Worked Example: Project Handover Document
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Project%20Handover-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/project-handover.md`](../templates/project-handover.md) | **Module:** [07 — Project Closing](../modules/07-closing.md)

---

## Table of Contents

- [Document Control](#document-control)
- [Purpose](#purpose)
- [1. What Has Been Delivered](#1-what-has-been-delivered)
- [2. Operational Responsibilities](#2-operational-responsibilities)
  - [2.1 Service Ownership](#21-service-ownership)
  - [2.2 Support Structure](#22-support-structure)
  - [2.3 Key Operational Procedures](#23-key-operational-procedures)
- [3. Contracts and Supplier Relationships](#3-contracts-and-supplier-relationships)
- [4. Benefits Realisation Responsibilities](#4-benefits-realisation-responsibilities)
- [5. Known Issues and Risks Transferred to BAU](#5-known-issues-and-risks-transferred-to-bau)
- [6. Documentation Inventory](#6-documentation-inventory)
- [7. Phase 2 Brief — Parking Permit Module](#7-phase-2-brief--parking-permit-module)
  - [Background](#background)
  - [Technical Findings](#technical-findings)
  - [Phase 2 Readiness](#phase-2-readiness)
- [Handover Acceptance](#handover-acceptance)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Document Type** | Project Handover — Operational and Phase 2 |
| **Version** | 1.0 |
| **Date** | 14 October 2026 |
| **Prepared by** | Sarah Chen, Project Manager |
| **Accepted by** | Sandra Obi, Service Director (Operational) / Mark Pearce, ICT Manager (Technical) |

[↑ Back to top](#table-of-contents)

---

## Purpose

This document records the formal handover of the Meridian portal from the project team to the operational (business as usual) teams responsible for running, maintaining, and continuously improving the service. It also provides a handover brief for the Phase 2 project team (parking permit module).

[↑ Back to top](#table-of-contents)

---

## 1. What Has Been Delivered

The Meridian Citizen Self-Service Portal went live on **15 October 2026**. It provides Northgate District Council residents with a single online access point for the following services:

| Module | Description | Back-office system integrated |
|---|---|---|
| **Planning application tracking** | Residents can search and track status of planning applications | UNIFORM (planning module) |
| **Missed waste collection reporting** | Residents can report a missed collection and receive confirmation | Civica (waste management) |
| **Council tax account and payment** | Residents can view their council tax account and make payments | Capita (council tax) |
| **Garden waste subscription renewal** | Residents can renew their annual garden waste subscription | Civica (waste management) |

**Not delivered (Phase 2)**: Parking permit online renewal — deferred via CR-003 (July 2026) due to UNIFORM API limitation. See Section 7 (Phase 2 Brief) for full details.

[↑ Back to top](#table-of-contents)

---

## 2. Operational Responsibilities

### 2.1 Service Ownership

| Responsibility | Role | Name |
|---|---|---|
| **Overall service owner** | Service Director, Customer and Digital Services | Sandra Obi |
| **Technical platform owner** | ICT Manager | Mark Pearce |
| **Day-to-day technical administration** | ICT Developer | Tom Okafor |
| **Benefits realisation monitoring** | Service Director | Sandra Obi |
| **Resident communications (ongoing)** | Digital Communications Manager | Diane Hughes |
| **GovTech relationship management** | ICT Manager | Mark Pearce |
| **Data protection and privacy** | Data Protection Officer | Claire Worthington |

### 2.2 Support Structure

| Level | Responsible party | Scope | Contact |
|---|---|---|---|
| Level 1 — User-facing issues | Council ICT Helpdesk | Resident access problems, password reset, browser compatibility | servicedesk@northgatedc.gov.uk |
| Level 2 — Platform issues | GovTech Solutions support team | Portal software bugs, platform errors, performance issues | support@govtechsolutions.co.uk / 0800 xxx xxxx |
| Level 3 — Integration issues | Tom Okafor (ICT Developer) | UNIFORM, Civica, and Capita integration failures or data errors | tom.okafor@northgatedc.gov.uk |
| Escalation — Service disruption | Mark Pearce (ICT Manager) | Major incidents; P1 outages; data incidents | mark.pearce@northgatedc.gov.uk |

### 2.3 Key Operational Procedures

| Procedure | Location | Owner |
|---|---|---|
| Incident response procedure | NDA SharePoint: Meridian/Operations | Tom Okafor |
| Platform administration guide (user management, content updates) | NDA SharePoint: Meridian/Operations | Tom Okafor |
| Capita payment gateway monthly reconciliation | Finance team procedure — updated to include portal | Mark Pearce |
| Resident data retention and deletion schedule | NDA SharePoint: Meridian/Data Protection | Claire Worthington |
| Monthly performance dashboard (adoption, call volumes) | SharePoint / Power BI — automated | Sandra Obi |

[↑ Back to top](#table-of-contents)

---

## 3. Contracts and Supplier Relationships

| Supplier | Contract | Term | Value | Owner | Key contacts |
|---|---|---|---|---|---|
| GovTech Solutions | Platform support and maintenance SLA | 3 years from go-live (Oct 2026 – Oct 2029) | £36,000/year | Mark Pearce | GovTech Account Manager: [name]; Support: support@govtechsolutions.co.uk |
| Capita | Council tax payment gateway processing | Ongoing (existing contract; portal use added via change notice) | Included in existing contract | Mark Pearce / Finance | Existing contract management arrangements |

**Note on GovTech SLA**: The support SLA includes a 4-hour response time for P1 incidents (portal unavailable), 8-hour for P2 (significant functionality impaired), and next working day for P3/P4. Mark Pearce is the contract manager and should receive monthly SLA performance reports from GovTech.

[↑ Back to top](#table-of-contents)

---

## 4. Benefits Realisation Responsibilities

Benefits realisation is now the responsibility of the operational service owner. The project has handed over:

| Benefit | Measurement method | Measurement frequency | Owner |
|---|---|---|---|
| BEN-01: Contact-centre call volume reduction (≥20%) | Council contact-centre call log analysis — compare in-scope service calls pre/post portal | Monthly | Sandra Obi |
| BEN-02: Resident adoption (≥55% by Jan 2027) | Portal login analytics (GovTech dashboard) | Monthly | Sandra Obi |
| BEN-03: Staff time savings (≥1.0 FTE equivalent) | Staff timesheets / manager survey | At 3 months and 6 months post-launch | Mark Pearce |
| BEN-04: Resident satisfaction (≥75%) | Post-transaction survey in portal (automated) | Monthly average | Sandra Obi |
| BEN-05: Net cashable saving (Year 1 target: £84,000) | Finance team — contact-centre cost modelling | March 2027 (year-end) | James Hartley |

**Post-Implementation Review**: Scheduled for **28 April 2027**. Sandra Obi to chair. PM (Sarah Chen) to provide project documentation support only — operational performance is Sandra's responsibility from closure.

[↑ Back to top](#table-of-contents)

---

## 5. Known Issues and Risks Transferred to BAU

The following items are not project issues but are noted for the operational team's awareness:

| Ref | Item | Detail | Owner |
|---|---|---|---|
| BAU-01 | Android 8 and below — minor layout issue (resolved) | ISS-06 was resolved before go-live. GovTech confirmed fix deployed 22 Aug 2026. Monitor for recurrence. | Tom Okafor |
| BAU-02 | GovTech platform version upgrade (Q1 2027) | GovTech has indicated a platform version upgrade is planned for Q1 2027. This will require a regression test. Mark Pearce to confirm timing with GovTech. | Mark Pearce |
| BAU-03 | Resident adoption trajectory monitoring | If adoption is below 40% at end of December 2026 (below staged trajectory), a resident re-engagement communications intervention may be needed. Diane Hughes has a contingency plan. | Diane Hughes |
| BAU-04 | UNIFORM API: future changes | Any future UNIFORM software upgrades should be assessed for impact on portal integrations before deployment. Tom Okafor to liaise with UNIFORM vendor. | Tom Okafor |

[↑ Back to top](#table-of-contents)

---

## 6. Documentation Inventory

All project and operational documentation has been archived in NDA SharePoint: **Meridian Portal** site.

| Document | Version | Location |
|---|---|---|
| Project Charter | 1.0 | Meridian/Governance |
| Project Management Plan | 2.1 | Meridian/Project Documents |
| Discovery Report | 1.0 | Meridian/Deliverables |
| UX Design Specification | 1.2 | Meridian/Deliverables |
| Integration Specification | 1.1 | Meridian/Deliverables |
| Data Protection Impact Assessment | 1.0 | Meridian/Data Protection |
| Risk Register (final) | 2.3 | Meridian/Risk and Issues |
| Change Log (final) | 1.5 | Meridian/Change Control |
| Issue Log (final) | 1.4 | Meridian/Risk and Issues |
| Lessons Learned Log (final) | 1.0 | Meridian/Lessons / PMO |
| UAT Test Report | 1.0 | Meridian/Quality |
| Accessibility Audit Report | 2.0 | Meridian/Quality |
| System Administration Guide | 1.0 | Meridian/Operations |
| User Guide (residents) | 1.0 | Meridian/Operations / Portal |
| Training Materials | 1.0 | Meridian/Training |
| Project Closure Report | 1.0 | Meridian/Governance |

[↑ Back to top](#table-of-contents)

---

## 7. Phase 2 Brief — Parking Permit Module

The following information is provided for the Phase 2 project team when the parking permit module is commissioned.

### Background

The parking permit module was deferred from Phase 1 via Change Request CR-003 (approved by Project Board 8 July 2026). The UNIFORM system does not expose parking permit expiry data in a queryable API format — it is only available as a scanned PDF document generated by the back-office system.

### Technical Findings

| Finding | Detail |
|---|---|
| **Root cause** | UNIFORM's parking permit module stores permit data in a document management sub-system that is not exposed via the standard API used by the portal integration |
| **Options assessed** | (1) Custom UNIFORM connector (estimated £35,000–£55,000; requires UNIFORM vendor involvement); (2) Scheduled batch extract (nightly PDF-to-data conversion — fragile, not recommended); (3) Defer until UNIFORM vendor releases API upgrade (on roadmap for 2027) |
| **Recommended Phase 2 approach** | Option 1 or 3 depending on UNIFORM vendor roadmap confirmation. Contact: [UNIFORM vendor account manager] for roadmap update. |
| **Phase 2 budget estimate** | £45,000–£65,000 (depending on approach) — to be refined in Phase 2 business case |

### Phase 2 Readiness

The GovTech portal platform is fully capable of adding the parking permit module — no platform changes are required. The portal navigation and design already includes a placeholder for parking permits, displayed with a "coming soon" notice.

[↑ Back to top](#table-of-contents)

---

## Handover Acceptance

| Role | Name | Signed | Date |
|---|---|---|---|
| **Handing over** — Project Manager | Sarah Chen | *(signed)* | 14 Oct 2026 |
| **Accepting** — Service Director (Operational) | Sandra Obi | *(signed)* | 14 Oct 2026 |
| **Accepting** — ICT Manager (Technical) | Mark Pearce | *(signed)* | 14 Oct 2026 |

[↑ Back to top](#table-of-contents)

---

*© 2026 UncleJs — Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*

# Worked Example: Change Request — CR-001
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Change%20Request-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/change-request.md`](../templates/change-request.md) | **Module:** [05 — Project Execution](../modules/05-execution.md)

---

## Table of Contents

- [Document Control](#document-control)
- [1. Description of Change](#1-description-of-change)
- [2. Reason / Justification](#2-reason--justification)
- [3. Baseline(s) Affected](#3-baselines-affected)
- [4. Impact Assessment](#4-impact-assessment)
  - [Schedule Impact](#schedule-impact)
  - [Cost Impact](#cost-impact)
  - [Risk Impact](#risk-impact)
  - [Quality / Scope Impact](#quality--scope-impact)
  - [Stakeholder Impact](#stakeholder-impact)
- [5. Options](#5-options)
- [6. Recommendation](#6-recommendation)
- [7. Decision](#7-decision)
- [8. Implementation Instructions](#8-implementation-instructions)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Change Request Number** | CR-001 |
| **Date Submitted** | May 22, 2026 |
| **Submitted by** | Sandra Obi, Head of Customer Services |
| **Priority** | Low |

[↑ Back to top](#table-of-contents)

---

## 1. Description of Change

Add a **Spanish language** option to the Meridian Portal for all four service modules (Planning, Property Tax, Waste, Parking Permits). CivicConnect already supports multi-language switching, so the change is the addition of professionally translated Spanish content plus a language toggle, rather than a platform change.

[↑ Back to top](#table-of-contents)

---

## 2. Reason / Justification

Following the go-live communications planning meeting (May 19, 2026), the city's Equity Officer asked for a Spanish-language option. The city does not currently mandate a multilingual portal. The Equity Officer believes a Spanish-language option would:

1. Serve residents with limited English, including a Spanish-speaking community of about 3,240 people.
2. Reduce the risk of a discrimination complaint on grounds of language access.
3. Be positively received by the city's Spanish-speaking councilmembers.

This requirement was not included in the original scope or business case. The need is legitimate, but its timing must be weighed against the fixed go-live date (CON-02).

[↑ Back to top](#table-of-contents)

---

## 3. Baseline(s) Affected

| Baseline | Affected? | Current value | Proposed value |
|---|---|---|---|
| Scope | Yes | English-only portal (4 modules) | Bilingual (English + Spanish) portal |
| Schedule | Yes (Option A only) | Go-live October 1, 2026 | +4 weeks (October 29, 2026) if delivered in Phase 1 |
| Budget / Cost | Yes (Option A only) | $0 | $12,800 (from contingency) |
| Quality criteria | No | — | — |
| Other (specify) | No | — | — |

[↑ Back to top](#table-of-contents)

---

## 4. Impact Assessment

### Schedule Impact

- Professional Spanish translation and review: estimated 3 weeks (specialist translation company required).
- Integration of Spanish content into the platform: estimated 1 week additional build effort (GovTech).
- UAT must include Spanish-language testing (requires a Spanish-speaking UAT participant — currently not in the panel).
- **Net schedule impact: +4 weeks if started immediately** (go-live would move to October 29, 2026).
- If deferred to Phase 2: zero schedule impact to the current go-live date of October 1, 2026.

### Cost Impact

| Item | Additional cost ($) | Cost saving ($) | Net ($) |
|---|---|---|---|
| Translation (4 modules, ~12,000 words @ $0.70/word) | 8,400 | — | 8,400 |
| GovTech additional configuration (4 days) | 3,600 | — | 3,600 |
| UAT additional effort (internal) | 800 | — | 800 |
| **Total (Option A — Phase 1 delivery)** | **12,800** | — | **12,800** |

Current contingency balance (as at May 22, 2026): **$38,000** (no drawdowns to date). Option A is fundable from contingency; Option B (defer) has $0 cost to this project.

### Risk Impact

- If deferred to Phase 2, there is a small reputational risk: the portal launches without Spanish, which may attract criticism before Phase 2 delivers it. Mitigated by a visible "Spanish language coming early 2027" notice at launch.
- No new delivery risk is introduced to Phase 1 by deferral; Option A would add schedule risk against the fixed go-live date.

### Quality / Scope Impact

- All user-facing content (four service modules) must be professionally translated into Spanish; machine translation alone is not acceptable.
- Adds a requirement for Spanish-language content quality assurance — GovTech to provide reviewed translations.

### Stakeholder Impact

- **Equity Officer** — raised the requirement; to be consulted on the deferral decision and Phase 2 commitment.
- **Spanish-speaking residents and Councilmembers** — affected; to be informed via the launch notice and Phase 2 commitment.
- **Sponsor and Senior User** — decision makers (CCB).

[↑ Back to top](#table-of-contents)

---

## 5. Options

| Option | Description | Cost ($) | Schedule impact | Recommendation |
|---|---|---|---|---|
| A — Approve as described | Include Spanish language in Phase 1 (before go-live) | 12,800 | +4 weeks (go-live moves to October 29, 2026) | Not recommended — delays go-live |
| B — Defer | Defer Spanish language to Phase 2 (Q1 2027) | $0 to this project | No impact | **Recommended** |
| C — Approve with modification | English-only portal at go-live with a prominent "Spanish language: contact us / coming early 2027" link; Spanish available by February 2027 | $0 to this project | No impact | Alternative if Option B is accepted |

[↑ Back to top](#table-of-contents)

---

## 6. Recommendation

**Option B — defer to Phase 2** with a committed Phase 2 start date of January 2027. The go-live date of October 1, 2026 cannot be moved (CON-02); a 4-week delay to accommodate Option A is not acceptable. Phase 2 should be formally scoped by the end of the current project, and a launch notice (Option C) used to signal the commitment to residents.

[↑ Back to top](#table-of-contents)

---

## 7. Decision

| Decision | ☑ Approved — Option B (Defer to Phase 2) |
|---|---|
| **Decision maker** | James Hartley (Sponsor), with Sandra Obi (Senior User) |
| **Decision date** | June 4, 2026 |
| **Conditions / notes** | Spanish language portal to be delivered in Phase 2, target January 2027. English-only portal to go live on October 1, 2026 with a homepage notice indicating Spanish support is coming in early 2027. PM to include Phase 2 scope in the closure report. |

| Role | Name | Signature | Date |
|---|---|---|---|
| Sponsor | James Hartley | *J. Hartley* | June 4, 2026 |
| Senior User | Sandra Obi | *S. Obi* | June 4, 2026 |
| Project Manager | Sarah Chen | *S. Chen* | June 4, 2026 |

[↑ Back to top](#table-of-contents)

---

## 8. Implementation Instructions

| Action | Owner | Due date |
|---|---|---|
| Record CR-001 in the change log as Deferred | Sarah Chen | June 5, 2026 |
| Add Spanish-language scope to the Phase 2 brief | Sarah Chen | At closure (Oct 2026) |
| Configure homepage "Spanish coming early 2027" notice | GovTech | Before go-live (October 1, 2026) |
| Notify the Equity Officer and Spanish-speaking councilmembers of the decision | Diane Hughes (BCM) | June 8, 2026 |

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# Worked Example: Change Request — CR-001
## Meridian — Citizen Self-Service Portal

![Template](https://img.shields.io/badge/Example-Change%20Request-blue)
![Project](https://img.shields.io/badge/Project-Meridian%20Portal-informational)

> **See also:** [`templates/change-request.md`](../templates/change-request.md) | **Module:** [05 — Project Execution](../modules/05-execution.md)

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | Meridian — Citizen Self-Service Portal |
| **Change Request No.** | CR-001 |
| **Date Raised** | 22 May 2026 |
| **Raised by** | Sandra Obi, Head of Customer Services |
| **PM Review** | Sarah Chen |
| **CCB Decision Date** | 4 June 2026 |

---

## 1. Change Description

### Summary

Add a **Welsh Language** option to the Meridian Portal for all four service modules (Planning, Council Tax, Bulky Waste, Parking Permits).

### Background and Reason

Following the Go-Live communications campaign planning meeting (19 May 2026), the council's Equalities Officer raised that Northgate has a resident population with approximately 4% Welsh-language speakers (approx. 3,240 residents). Although the council is not currently in a Welsh Language Scheme area, the Equalities Officer believes a Welsh-language portal option would:

1. Serve a resident group currently underserved digitally.
2. Reduce the risk of an equalities complaint or legal challenge on grounds of language access.
3. Be positively received by the council's Welsh-speaking Councillors.

This requirement was not included in the original scope or business case.

---

## 2. Impact Assessment

### Scope Impact

- All user-facing content (four service modules) must be professionally translated into Welsh.
- CivicConnect platform already supports multi-language switching — a technical language toggle is low effort.
- Welsh content must be equivalent in quality to English content — machine translation alone is not acceptable.

### Schedule Impact

- Professional Welsh translation and review: estimated 3 weeks (specialist translation company required).
- Integration of Welsh content into the platform: estimated 1 week additional build effort (GovTech).
- UAT must include Welsh-language testing (requires Welsh-speaking UAT participant — currently not in panel).
- **Net schedule impact: +4 weeks if started immediately.**
- If deferred to post go-live Phase 2: zero schedule impact to current go-live date of 1 October 2026.

### Cost Impact

- Translation (4 modules, estimated 12,000 words): £8,400 (based on GovTech partner translation company rate of £0.70/word).
- GovTech additional configuration: £3,600 (4 days × day rate, per supplier estimate).
- UAT additional effort: £800 (estimated internal cost).
- **Total cost of change: £12,800.**
- Current contingency balance (as at 22 May 2026): £31,500. Change is fundable from contingency.

### Quality / Risk Impact

- Adds requirement for Welsh-language content quality assurance — GovTech to provide reviewed translations.
- If deferred to Phase 2, there is a small reputational risk: the portal launches without Welsh, which may attract criticism before Phase 2 delivers it.

---

## 3. Proposed Change Options

| Option | Description | Cost | Schedule | Recommendation |
|---|---|---|---|---|
| A | Include Welsh language in Phase 1 (before go-live) | £12,800 | +4 weeks (go-live moves to 29 Oct 2026) | Not recommended — delays go-live |
| B | Defer Welsh language to Phase 2 (Q1 2027) | £0 to this project | No impact | **Recommended** |
| C | Include English-only portal with prominent "Welsh language: contact us" link at go-live, Welsh available by Feb 2027 | £0 to this project | No impact | Alternative if Option B is accepted |

**PM Recommendation:** Option B — defer to Phase 2 with a committed Phase 2 start date of January 2027. The go-live date of 1 October 2026 cannot be moved (CON-02). A 4-week delay to accommodate Option A is not acceptable. Phase 2 should be formally scoped by the end of the current project.

---

## 4. Justification

The original scope was defined before equalities considerations around Welsh language access were raised. The need is legitimate, but the timing is incompatible with the fixed go-live date. Deferring to Phase 2 with a clear commitment ensures the need is addressed without compromising current delivery commitments.

---

## 5. CCB Decision

| Decision | Details | Date |
|---|---|---|
| **Approved — Option B (Defer to Phase 2)** | Welsh language portal to be delivered in Phase 2, target January 2027. PM to include Phase 2 scope in closure report. English-only portal to go live on 1 October 2026 with a note on the portal homepage indicating Welsh support is coming in early 2027. | 4 June 2026 |

| Role | Name | Signature | Date |
|---|---|---|---|
| Sponsor | James Hartley | *J. Hartley* | 4 Jun 2026 |
| Senior User | Sandra Obi | *S. Obi* | 4 Jun 2026 |
| Project Manager | Sarah Chen | *S. Chen* | 4 Jun 2026 |

---

*© 2026 UncleJs — Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*

# Changelog

![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)
![Version](https://img.shields.io/badge/Version-2.1.3-blue)
![Keep a Changelog](https://img.shields.io/badge/Keep%20a%20Changelog-1.1.0-orange)
![Semantic Versioning](https://img.shields.io/badge/Semver-2.0.0-informational)

All notable changes to *Project Management Fundamentals* are documented in this file.

This project follows **[Keep a Changelog](https://keepachangelog.com/en/1.1.0/)** conventions and uses **[Semantic Versioning](https://semver.org/spec/v2.0.0.html)**.

> **Versioning scheme for a content-only course:**
> - **Major** (`X.0.0`) — Structural redesign: module additions/removals, significant re-ordering, or fundamental scope change.
> - **Minor** (`X.Y.0`) — New content: new modules, new templates, new worked examples, new supporting files.
> - **Patch** (`X.Y.Z`) — Corrections and improvements: typo fixes, clarifications, broken link repairs, minor rewording.

---

## Table of Contents

- [Unreleased](#unreleased)
- [2.1.3 — 2026-03-03](#213--2026-03-03)
- [2.1.2 — 2026-03-03](#212--2026-03-03)
- [2.1.1 — 2026-03-02](#211--2026-03-02)
- [2.1.0 — 2026-03-02](#210--2026-03-02)
- [2.0.0 — 2025-09-01](#200--2025-09-01)
- [1.0.0 — 2025-04-15](#100--2025-04-15)
- [Versioning Notes](#versioning-notes)

---

## [Unreleased]

*Outcome of a full multi-dimensional course review (accuracy, consistency, structure/links, pedagogy, language). Findings recorded in `COURSE-REVIEW.md`. This batch covers the modules, glossary, meta-files, navigation, and the unambiguous worked-example corrections; the worked-example financial-model reconstruction and full template/example structural alignment are tracked as follow-up work.*

### Fixed

- **All module files + several templates** — Repaired 65 broken Table-of-Contents anchors. Headings containing ` — ` (em-dash, e.g. `Exercise 1.1 — …`) produce a double-hyphen GitHub slug; the v2.1.2 TOC links used single hyphens and did not resolve. Link checker now reports 0 broken links across all 67 files.
- **`modules/03-initiation.md`** — Corrected the weighted-scoring worked example: Project A total is 3.60 (was 3.55); 4×0.30+3×0.25+5×0.20+3×0.15+2×0.10 = 3.60.
- **`modules/06-monitoring-control.md`** — Fixed the SPI/CPI `quadrantChart`: quadrant-2 and quadrant-4 labels were swapped relative to the chart's own axes (now `Behind & Under Budget` top-left, `Ahead & Over Budget` bottom-right).
- **`modules/10-communications.md`** — Exercise 10.2 cited "SPI 0.83" from the Module 06 EVM example, which computes SPI 0.80; corrected (CPI 0.89 and EAC £112,360 already matched).
- **`modules/11-risk-management.md`** — Quiz 4 answer reworded: a CPI of 0.82 is a cost *overrun* (over budget), not "performing below budget targets" (which implied underspend). Also distinguished passive vs active risk acceptance, and separated contingency plans from fallback plans.
- **`modules/12-quality-management.md`** — Replaced the Statistical Process Control chart shown under the "Pareto analysis" heading with an actual Pareto chart (causes ranked by frequency + cumulative-percentage line).
- **`modules/14-resource-team.md`** — Reversed the Maslow hierarchy diagram arrows to flow bottom-up (using `flowchart BT` so the pyramid keeps its shape) to match the prose; corrected the inverted Hofstede "Indulgence vs Restraint" row.
- **`modules/02-governance.md`** — Removed the incorrect equation of the Change Control Board with the (ITIL) Change Advisory Board.
- **`modules/04-planning.md`** — Clarified that RACI is a *form of* Responsibility Assignment Matrix (RAM), not the RAM itself; spelled out Responsible/Accountable/Consulted/Informed.
- **`modules/13-procurement.md`** — Retitled to "Procurement and Contract Management" (H1, Module badge, self-TOC entry) to match the four other files that already used that name.
- **`GLOSSARY.md`** — Added missing entries that are taught and quizzed but were undefined: **Crashing**, **Residual Risk**, **Secondary Risk**.
- **`INSTRUCTOR-GUIDE.md`** — Corrected "6–10 quiz questions per module" to "5–10" (modules 08–12 have five).
- **All modules + `README.md`** — Normalised the US spelling "Artifact(s)" to UK "Artefact(s)" in section headings, TOC entries and table headers (75 replacements), matching the course's UK-English convention and the surrounding prose; also `judgment`→`judgement` and `skillfully`→`skilfully`.
- **`examples/` (Meridian scenario) — cross-file consistency.** Reconciled the worked examples against the agreed scenario canon:
  - **Roles**: standardised the sponsor to "James Hartley, Director of Digital Services" (16, 18, 21); Sandra Obi to "Head of Customer Services" (16, 17, 18, 21); Diane Hughes to "Business Change Manager" (17); and routed all DPIA/GDPR sign-offs to the Data Protection Officer rather than Claire Worthington, the Section 151 (Finance) officer (14, 16, 17, 19, 20).
  - **IDs and dates**: parking-permit issue ID ISS-04 → ISS-03 (13); CR-003 date Aug → Jul 2026 and Risk Summary Medium Open/Closed split 5/4 → 6/3 (14); closure-report project start 3 Feb 2026, project reference NGL-2026-DIG-01, accessibility-audit variance +5 → +7 days and OBJ-05 audit date 19 → 26 Sep (16).
  - **Go-live**: re-presented as planned 1 October / actual 15 October 2026 (+14 days, absorbed within the schedule to closure) across the closure report and examples README, replacing the false 0-day "on-time" claim.
  - **Financial model (recomputed from the stated drivers)**: gross deflection saving 14,200 × 55% × £22 = **£171,820/yr**; running cost **£48,000/yr** (£36,000 GovTech support + £12,000 internal); **net £123,820/yr**. Updated the business case (01) benefit target, net-saving line, ongoing-cost table, 5-year financial summary, payback (~3.4 yr), ROI (88%) and NPV (+£116,000); the meeting minutes (12, also fixed the false "14,200 × £22 = £310,000" equation) and examples README. Rebuilt the **Project Closure Report financial table** (05) so the actual column foots to **£374,800** (£45,200 underspend, 10.8%): CR-002 correctly labelled the UNIFORM API uplift (+£7,200, was mislabelled accessibility testing +£3,200), CR-005 hypercare added, CR-003 (−£18,000) no longer double-counted. Corrected the change log (09) Budget Impact Summary to keep the £18,000 base-scope saving separate from contingency (remaining contingency £27,200, total released £45,200), and the benefits register (18) gross/net cashable labelling, BEN-01 classification, and project cost.

- **Template ↔ worked-example structural alignment (all 21 pairs).** Conformed every worked example to its template's section set, column names and controlled vocabularies, preserving worked data (extra example-only sections that carry real data, such as the risk register's Opportunity Register, were retained). Highlights: business case (01) split out a `Return on Investment` section and renumbered, `Authorisation`→`Approval`; change request (08) restructured to the template's 8 sections; issue log (10), risk register (14), change log (09), assumption/constraint log (04) and lessons log (15) gained their missing definition/vocabulary sections and had out-of-vocabulary status values corrected; resource calendar (07) gained Consolidated Demand, Known Absences and Resource Levelling sections; handover (17) gained Training Completed; status report (13), meeting agenda (11) and minutes (12) had headings/fields/columns aligned. Also harmonised the early-doc "bulky waste" wording to the delivered "missed/garden waste" scope across 01, 02, 05, 06, 12 and the examples index, and reconciled the CR-003 board-decision date in the status report.

- **Gate 2 schedule reconciled.** Presented Gate 2 (build complete) as planned 7 August 2026 / actual 11 September 2026 (+35 days) in the closure report schedule table, with commentary explaining the build slip (UNIFORM integration complexity and the Capita audit) and its partial recovery through UAT compression; UAT complete shown against its 19 September planned baseline (+7 days). The charter (02) and kick-off minutes (12) keep the 7 August planned baseline; the lessons log (15) keeps 11 September as the actual review date; the communications plan (19) gate-review timing corrected to the Aug 2026 plan.

[↑ Back to top](#table-of-contents)

---

## [2.1.3] — 2026-03-03

### Fixed

- **`modules/06-monitoring-control.md`** — Removed parentheses from `quadrantChart` axis labels (`x-axis` / `y-axis`) which caused a Mermaid lexer error; labels now read `Low SPI --> High SPI` and `Low CPI --> High CPI`. All 46 Mermaid diagrams across the course now render cleanly.

[↑ Back to top](#table-of-contents)

---

## [2.1.2] — 2026-03-03

### Changed

- **`README.md`** — Corrected the Worked Examples table (items 07–11) to match the actual files and numbering in `examples/README.md`.
- **`examples/README.md`** — Added a `## Table of Contents` section and `[↑ Back to top](#table-of-contents)` navigation links.
- **`modules/` (all module files)** — Expanded each `## Table of Contents` to include `###` subsection links for improved scanability.
- **`templates/` (all template files) and `examples/` (all worked example files)** — Standardised license footer formatting to the repository convention (`&copy; 2026 UncleJs &mdash; Licensed under ...`).

[↑ Back to top](#table-of-contents)

---

## [2.1.1] — 2026-03-02

### Changed

- **`examples/` (all 21 files)** — Added `## Table of Contents` section and `[↑ Back to top](#table-of-contents)` links to every worked example artefact, matching the navigation conventions already in place across all `modules/` files.
- **`modules/` (all 16 content files) and `CURRICULUM-MAP.md`** — Removed literal `\n` escape sequences from all Mermaid diagram node labels and edge labels; these rendered as the characters `\n` rather than line breaks in GitHub's Mermaid renderer. Labels now use spaces instead.
- **`modules/13-procurement.md`** — Quoted two unquoted flowchart node labels containing `&` (`Evaluate & Select`, `Contract & Procurement Closure`) and one edge-label node (`T&M … CPIF`) to prevent Mermaid parse errors.
- **`modules/15b-professional-practice.md`** — Replaced `&` with `and` in two `classDiagram` attribute names (`agile & hybrid methods`, `leadership & influence`) to prevent parser ambiguity.

[↑ Back to top](#table-of-contents)

---

## [2.1.0] — 2026-03-02

### Added

- **`INSTRUCTOR-GUIDE.md`** — Comprehensive facilitator guide covering delivery formats (intensive, part-time, self-paced, modular), module-by-module facilitation notes, assessment approaches (portfolio, case study, quiz, peer review), certification mapping (PMP, PRINCE2, APM), and recommended reading.
- **`CHANGELOG.md`** — This file. Versioning scheme established.
- **`CURRICULUM-MAP.md`** — Visual learning path with Mermaid diagrams showing module dependencies, learning tiers, recommended study paths for different audiences, and estimated completion times.
- **`examples/`** — New folder of 21 worked, completed sample artefacts based on a generic IT project scenario ("Meridian Portal" — a citizen-facing self-service web portal for Northgate District Council). Each example template is filled in with realistic, coherent data to model professional-quality artefacts.
  - `examples/README.md` — Scenario overview and index.
  - All 21 template equivalents in worked form.
- **Module 15a** (`modules/15a-integration-hybrid-agile.md`) — New module split from Module 15 covering: Integration Management, Integrated Change Control, Organisational Change vs Project Change, Hybrid and Adaptive Approaches, Agile Principles and Lifecycle Selection, and Scaling Agile.
- **Module 15b** (`modules/15b-professional-practice.md`) — New module split from Module 15 covering: PM Competency Frameworks, Continuing Professional Development (CPD), Common Project Failure Modes, Project Management Across Industries, and Synthesis: Becoming a Reflective Practitioner.

### Changed

- **`modules/15-capstone.md`** — Original file retained as a redirect/index pointing to 15a and 15b. Content has been migrated to the two new files.
- **`README.md`** — Updated to reflect new files, module split, examples folder, and curriculum map link.
- **All modules (01–14 and 15a–15b)** — Added **Related Modules** cross-reference section to each module footer, linking to directly related content elsewhere in the course.

[↑ Back to top](#table-of-contents)

---

## [2.0.0] — 2025-09-01

### Added

- Full course launch: 15 modules across 4 tiers.
- 21 blank artefact templates in `/templates/`.
- `GLOSSARY.md` with 150+ terms.
- `README.md` with full course navigation.
- `LICENSE.md` (CC BY-NC-SA 4.0).

[↑ Back to top](#table-of-contents)

---

## [1.0.0] — 2025-04-15

### Added

- Initial draft: Modules 01–07 (lifecycle tier).
- Core templates: Business Case, Project Charter, Risk Register, Issue Log, Status Report, Lessons Learned Log, Project Closure Report.
- Prototype GLOSSARY.md.

[↑ Back to top](#table-of-contents)

---

## Versioning Notes

- Dates reflect the date content was finalised and tagged, not necessarily the date of authoring.
- The `[Unreleased]` section tracks in-progress changes before a version tag is applied.
- Patch releases (`x.y.Z`) are not always individually logged — they may be batched into the next minor release notes.

[↑ Back to top](#table-of-contents)

---

&copy; 2026 UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

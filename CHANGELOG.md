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

*Changes that are being prepared but not yet tagged as a release.*

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

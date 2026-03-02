# Template: Work Breakdown Structure (WBS)

![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)
![Template](https://img.shields.io/badge/Template-WBS-blue)
![Author](https://img.shields.io/badge/Author-UncleJs-orange)

> A WBS decomposes the total project scope into manageable work packages. Every deliverable that the project must produce should appear somewhere in the WBS. The WBS is deliverable-oriented — it defines *what*, not *how* or *who*.

---

## Document Control

| Field | Value |
|---|---|
| **Project Title** | |
| **Version** | |
| **Date** | |
| **Prepared by** | |
| **Approved by** | |

---

## WBS Numbering Convention

```
1.0         Project Name
1.1           Phase / Major Deliverable
1.1.1           Sub-deliverable
1.1.1.1           Work Package (lowest level — estimated, assigned, and tracked)
```

---

## WBS — Hierarchical View

```
1.0  [PROJECT TITLE]
│
├── 1.1  [Phase or Major Deliverable 1]
│    ├── 1.1.1  [Sub-deliverable]
│    │    ├── 1.1.1.1  [Work Package]
│    │    └── 1.1.1.2  [Work Package]
│    └── 1.1.2  [Sub-deliverable]
│         ├── 1.1.2.1  [Work Package]
│         └── 1.1.2.2  [Work Package]
│
├── 1.2  [Phase or Major Deliverable 2]
│    ├── 1.2.1  [Sub-deliverable]
│    │    ├── 1.2.1.1  [Work Package]
│    │    └── 1.2.1.2  [Work Package]
│    └── 1.2.2  [Sub-deliverable]
│
├── 1.3  [Phase or Major Deliverable 3]
│    └── ...
│
└── 1.X  Project Management (always include)
     ├── 1.X.1  Project Management Plan
     ├── 1.X.2  Status Reporting
     ├── 1.X.3  Change Control
     └── 1.X.4  Project Closure
```

---

## WBS Dictionary (Work Package Descriptions)

Complete one row per work package (lowest-level WBS element).

| WBS ID | Work package name | Description | Deliverable(s) | Acceptance criteria | Owner | Estimated effort | Dependencies |
|---|---|---|---|---|---|---|---|
| 1.1.1.1 | | | | | | | |
| 1.1.1.2 | | | | | | | |
| 1.1.2.1 | | | | | | | |
| 1.1.2.2 | | | | | | | |
| 1.2.1.1 | | | | | | | |

---

## WBS Construction Guidance

### 100% Rule

The WBS must capture **100% of the scope**. The sum of all work at each level equals the level above. Nothing is missing; nothing is duplicated.

### Decomposition Tips

- Decompose until work packages are: estimable, assignable, and trackable (typically 8–80 hours of effort, or completable within one reporting period).
- Stop when further decomposition adds planning overhead without adding control value.
- Deliverable-oriented decomposition (nouns, not verbs) prevents scope creep better than activity-oriented decomposition.
- Always include a **Project Management** branch — PM work is real work and must be resourced.

### Common WBS Structures

| Approach | When to use |
|---|---|
| By **phase** (initiation, design, build, test, deploy) | Sequential, predictive projects |
| By **deliverable** (system, documentation, training, infrastructure) | Complex multi-output projects |
| By **location / geography** | Multi-site or multi-region projects |
| By **subproject** | Programmes with distinct workstreams |

---

*© UncleJs — Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*

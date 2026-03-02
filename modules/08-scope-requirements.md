# Module 08 — Scope and Requirements Management

![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)
![Module](https://img.shields.io/badge/Module-08%20Scope%20%26%20Requirements-blue)
![Level](https://img.shields.io/badge/Level-Mixed%2FGeneral-green)
![Author](https://img.shields.io/badge/Author-UncleJs-orange)

> **Most project failures can be traced to poor scope definition or requirements management.** This module dives deep into the full requirements lifecycle — from elicitation through to acceptance — and covers how to keep scope under control throughout delivery.

---

## Table of Contents

- [1. The Requirements Lifecycle](#1-the-requirements-lifecycle)
- [2. Types of Requirements](#2-types-of-requirements)
- [3. Requirements Elicitation Techniques](#3-requirements-elicitation-techniques)
- [4. Requirements Analysis and Specification](#4-requirements-analysis-and-specification)
- [5. Requirements Prioritisation](#5-requirements-prioritisation)
- [6. Requirements Traceability](#6-requirements-traceability)
- [7. Managing Requirements Change](#7-managing-requirements-change)
- [8. Scope Creep vs. Scope Change](#8-scope-creep-vs-scope-change)
- [9. Acceptance Criteria](#9-acceptance-criteria)
- [Artifacts](#artifacts)
- [Exercises](#exercises)
- [Quiz](#quiz)

---

## 1. The Requirements Lifecycle

Requirements management is not a single event at the start of a project — it is a continuous process:

```mermaid
flowchart LR
    E["📋 Elicit\n(gather from\nstakeholders)"]
    A["🔍 Analyse\n(refine &\nresolve conflicts)"]
    S["📝 Specify\n(document\nclearly)"]
    V["✅ Validate\n(confirm with\nstakeholders)"]
    B["🔒 Baseline\n(approve &\nfreeze)"]
    MC["🔄 Manage\nChange\n(formal CCB)"]
    T["🔗 Trace\n(link reqs to\ndeliverables)"]
    VE["🧪 Verify\n(test against\nrequirements)"]
    AC["🎯 Accept\n(formal\nsign-off)"]
    E --> A --> S --> V --> B --> MC
    B --> T --> VE --> AC
    MC --> T
```
*The requirements lifecycle is continuous — change requests re-enter at the Manage Change stage and flow through Trace, Verify, and Accept.*

| Stage | What Happens |
|---|---|
| **Elicit** | Gather raw requirements from stakeholders using various techniques |
| **Analyse** | Examine, refine, and resolve conflicts between requirements |
| **Specify** | Document requirements clearly and unambiguously |
| **Validate** | Confirm with stakeholders that documented requirements reflect their real needs |
| **Baseline** | Approve and freeze the requirements as the scope baseline |
| **Manage Change** | Handle new or changed requirements through formal change control |
| **Trace** | Maintain links between requirements and deliverables throughout delivery |
| **Verify** | Confirm that deliverables meet the requirements (testing) |
| **Accept** | Obtain formal sign-off from the customer |

[↑ Back to top](#table-of-contents)

---

## 2. Types of Requirements

Understanding the different types of requirements prevents gaps and conflicts:

| Type | Definition | Example |
|---|---|---|
| **Business requirements** | High-level organisational needs that the project must address | "Reduce customer onboarding time by 50%" |
| **Stakeholder requirements** | Specific needs of individual stakeholder groups | "Call centre agents need to see full customer history on one screen" |
| **Solution requirements — functional** | What the system/product must do | "The system must send an automated welcome email on account creation" |
| **Solution requirements — non-functional** | How the system must perform | "Page load time must be < 2 seconds for 95% of requests" |
| **Transition requirements** | Requirements for getting from current state to future state | "All existing customer data must be migrated with 100% accuracy" |
| **Regulatory requirements** | Legal or compliance mandates | "Personal data must be stored within the EU under GDPR" |

Missing requirement types — especially non-functional and transition requirements — are one of the most common causes of project overruns.

[↑ Back to top](#table-of-contents)

---

## 3. Requirements Elicitation Techniques

### Choosing the right technique

No single technique works in all situations. Good requirements elicitation uses a combination:

| Technique | Best Used When | Watch Out For |
|---|---|---|
| **Interviews** | Deep individual input; sensitive topics; senior stakeholders | Interviewee says what they think you want to hear |
| **Workshops** | Group alignment; surfacing conflicts; complex domain | Dominant voices; groupthink; poor facilitation |
| **Observation (shadowing)** | Understanding real workflows; operational processes | Disrupts normal work; subjects may behave differently when observed |
| **Document analysis** | Existing system documentation; legacy requirements | Documents may be outdated or incorrect |
| **Prototyping** | Requirements are hard to articulate verbally | Stakeholders fixate on the prototype rather than underlying need |
| **Surveys / questionnaires** | Large, dispersed user population; quantitative data | Low response rates; cannot probe answers |
| **Brainstorming** | Generating a wide range of possibilities | Can produce noise; needs structured follow-up |
| **Focus groups** | User experience requirements; diverse perspectives | Small, unrepresentative groups; facilitation-sensitive |

### The hidden requirement problem

Stakeholders often cannot fully articulate what they need until they see something. This leads to:

- **Tacit knowledge**: experts know how the process works but have never had to describe it
- **Unknown unknowns**: stakeholders don't know what they don't know they need
- **Gold plating by omission**: requirements are assumed to be understood and are never stated

Mitigation: use multiple techniques, validate early, and iterate.

[↑ Back to top](#table-of-contents)

---

## 4. Requirements Analysis and Specification

### From raw input to clear requirements

Raw elicitation output is typically messy, ambiguous, and contradictory. Analysis involves:

- **Organising**: grouping related requirements
- **Deduplicating**: removing redundant statements
- **Resolving conflicts**: where two stakeholders have contradictory requirements
- **Clarifying ambiguity**: rewriting vague statements into testable ones
- **Decomposing**: breaking high-level needs into specific, implementable requirements

### Writing good requirements

A well-written requirement is:

| Property | What It Means |
|---|---|
| **Clear** | Unambiguous — only one interpretation possible |
| **Complete** | Contains all necessary information |
| **Consistent** | Does not contradict other requirements |
| **Testable** | There is a clear pass/fail criterion |
| **Traceable** | Can be linked to its source and to the deliverable that implements it |
| **Necessary** | Removing it would cause a gap in the stakeholder's needs |

**Vague requirement:** "The system should be easy to use."
**Testable requirement:** "A new user with no training must be able to complete the account registration process in under 3 minutes in usability testing."

### User stories as an alternative format

For product-type projects, user stories are an effective format:

```
As a [type of user],
I want to [do something],
So that [I can achieve this goal].
```

User stories are not a replacement for full specification — they are a starting point for conversation. Acceptance criteria must still be defined for each story.

[↑ Back to top](#table-of-contents)

---

## 5. Requirements Prioritisation

Not all requirements are equally important. Prioritisation enables:

- Delivery of the highest-value requirements first
- Informed decisions when scope must be reduced under time/cost pressure
- Clearer scope negotiation with stakeholders

### MoSCoW

The most widely used prioritisation technique in project management:

| Priority | Meaning | Guidance |
|---|---|---|
| **Must have** | Non-negotiable; without these the solution fails | Typically 60–70% of scope maximum |
| **Should have** | Important but not critical; can be delivered in a later phase | Aim to include; defer if necessary |
| **Could have** | Desirable; included if time and budget allow | Cut first under pressure |
| **Won't have** | Explicitly out of scope for this delivery | Manages stakeholder expectations |

"Won't have" is not "never" — it means "not this time." Recording it prevents these items from being raised as missed requirements at acceptance.

### Kano model

Classifies features by their impact on customer satisfaction:

| Category | Effect |
|---|---|
| **Basic needs** | Expected; their absence causes dissatisfaction; their presence does not delight |
| **Performance needs** | More = better; linear relationship with satisfaction |
| **Delighters** | Unexpected; their presence creates high satisfaction; their absence is not noticed |

The Kano model helps PMs and business analysts distinguish between table-stakes requirements and value-differentiating ones.

[↑ Back to top](#table-of-contents)

---

## 6. Requirements Traceability

### Why trace requirements?

Requirements traceability ensures that:

- Every requirement is implemented somewhere in the solution
- Every component of the solution maps back to a requirement (nothing unnecessary has been built)
- Every test case verifies at least one requirement

Without traceability, it is impossible to confirm completeness at acceptance.

### The Requirements Traceability Matrix (RTM)

The RTM links requirements horizontally through the project:

| Req ID | Requirement | Source | Design Ref | Build Component | Test Case | Status |
|---|---|---|---|---|---|---|
| REQ-001 | Self-service password reset | User workshop | DS-042 | AuthService v2 | TC-023 | Passed |
| REQ-002 | GDPR data export | Legal | DS-019 | DataExportAPI | TC-047 | In test |
| REQ-003 | Mobile-responsive login | Marketing | DS-031 | UIComponents | TC-012 | Passed |

### Bidirectional traceability

Good traceability works both ways:

- **Forward**: requirement → design → build → test (ensures everything is implemented)
- **Backward**: test → build → design → requirement (ensures nothing unnecessary was built)

```mermaid
classDiagram
    class Requirement {
        +String reqID
        +String description
        +String source
        +String priority
        +String status
    }
    class DesignSpec {
        +String designRef
        +String component
        +String author
    }
    class BuildComponent {
        +String componentID
        +String module
        +String version
    }
    class TestCase {
        +String testID
        +String testType
        +String result
    }
    class AcceptanceCriteria {
        +String criteriaID
        +String condition
        +String passResult
    }
    Requirement "1" --> "1..*" DesignSpec : implemented by
    DesignSpec "1" --> "1..*" BuildComponent : realised in
    BuildComponent "1" --> "1..*" TestCase : verified by
    Requirement "1" --> "1..*" AcceptanceCriteria : validated against
    TestCase "1..*" --> "1" AcceptanceCriteria : confirms
```
*The RTM links requirements bidirectionally through design, build, and test — forward to confirm completeness, backward to confirm nothing unnecessary was built.*

[↑ Back to top](#table-of-contents)

---

## 7. Managing Requirements Change

### Requirements will change

In most projects, some requirements will change after the baseline is set. This is normal and acceptable — what is unacceptable is allowing requirements to change without formal assessment and approval.

### The requirements change process

1. **Request received** (from any stakeholder)
2. **Log in the change register**
3. **Impact assessment**: scope, schedule, cost, risk, dependencies
4. **Present to CCB / sponsor** with a recommendation
5. **Decision**: approve, reject, or defer
6. **Update RTM, scope baseline, and plan** if approved
7. **Notify affected parties**

### Version control for requirements

Requirements documents must be version-controlled. When a requirement changes:

- The old version is retained
- The new version is clearly marked as superseded
- The change is documented with reason and approval record

[↑ Back to top](#table-of-contents)

---

## 8. Scope Creep vs. Scope Change

### Scope change is healthy; scope creep is not

| Scope Change | Scope Creep |
|---|---|
| Formally requested through the change control process | Informally added, often without PM awareness |
| Impact assessed against scope, schedule, and cost | No impact assessment performed |
| Approved by the appropriate authority | No approval obtained |
| Baselines updated to reflect the change | Baselines not updated |
| Team is directed to implement the approved change | Developer adds features "because it seems obvious" |

### How scope creep happens

- Stakeholders bypass the PM and ask developers directly
- "Small" requests are accommodated without change control ("it'll only take an hour")
- Poorly defined acceptance criteria allow gold-plating
- Developers over-engineer solutions beyond specification
- The word "and" in requirements ("...and it should also do...")

### Preventing scope creep

1. **Define scope explicitly** — especially what is out of scope
2. **Train the team** — all requests go through the PM, always
3. **Apply change control consistently** — no exceptions, even for tiny changes
4. **Review scope at every status meeting** — is anything being done that wasn't planned?
5. **Use the RTM** — deliverables without a requirement are out of scope

[↑ Back to top](#table-of-contents)

---

## 9. Acceptance Criteria

### What are acceptance criteria?

Acceptance criteria are the specific, measurable conditions that a deliverable must satisfy to be accepted by the customer. They:

- Remove ambiguity about what "done" means
- Enable objective testing and verification
- Prevent disputes at the acceptance stage
- Give the development team a clear target

### Writing good acceptance criteria

Use the **Given/When/Then** format for functional criteria:

```
Given [a context or precondition],
When [an action is taken],
Then [the expected outcome occurs].
```

**Example:**
> Given a registered user is on the login page,
> When they enter incorrect credentials three times,
> Then their account is locked and they receive an email with reset instructions.

For non-functional criteria, specify measurable thresholds:

> The search results page must load in under 1.5 seconds for 95% of queries under a load of 1,000 concurrent users.

### Acceptance criteria must be agreed before work starts

Criteria defined after a deliverable is built often reflect what was actually built rather than what was needed. Pre-agreed criteria hold the team accountable to the genuine need.

[↑ Back to top](#table-of-contents)

---

## Artifacts

| Artifact | Description | Template |
|---|---|---|
| **Requirements Documentation (BRD)** | Elicited and analysed requirements | — |
| **Requirements Traceability Matrix (RTM)** | Links requirements to design, build, test, and status | — |
| **Acceptance Criteria Document** | Testable pass/fail conditions for each deliverable | — |
| **Scope Statement** | Defines in-scope, out-of-scope, constraints | — |
| **Scope Change Request** | Formal request to alter the scope baseline | [change-request.md](../templates/change-request.md) |
| **Change Log** | Running record of all scope change requests | [change-log.md](../templates/change-log.md) |

[↑ Back to top](#table-of-contents)

---

## Exercises

### Exercise 8.1 — Improve vague requirements

Rewrite each of the following vague requirements as testable, unambiguous statements. Add acceptance criteria in Given/When/Then format for at least two.

1. "The system should be fast."
2. "Users should be able to find what they're looking for easily."
3. "The report should show all the important data."
4. "The portal must be secure."
5. "Notifications should be sent when something happens."

**Expected output:** Five rewritten requirements plus two Given/When/Then acceptance criteria.

---

### Exercise 8.2 — MoSCoW prioritisation

You are managing a 12-week project to build an internal expense management system. Budget: £85,000. The stakeholder workshop produced the following requirements list. Prioritise them using MoSCoW and justify your decisions.

1. Submit expense claims with receipt photos
2. Multi-currency support (the company operates in 3 countries)
3. Automatic VAT calculation
4. Integration with the payroll system
5. Mobile app (in addition to web)
6. Approval workflow (manager approves before payment)
7. Reporting dashboard for Finance
8. AI-powered receipt data extraction (no manual entry needed)
9. Audit trail for all expense submissions
10. Employee self-service history of all past claims

**Expected output:** A MoSCoW table with all 10 requirements classified and one sentence of justification per item.

---

### Exercise 8.3 — Build a mini RTM

Using the expense management system from Exercise 8.2, take your Must Have requirements and create a Requirements Traceability Matrix with columns for: Req ID, Description, Source, Priority, Test Case ID, and Status. (For this exercise, invent plausible test case IDs.)

**Expected output:** An RTM with at least 5 rows covering all Must Have requirements.

[↑ Back to top](#table-of-contents)

---

## Quiz

**Question 1:** What makes a requirement "testable"?

- A) It can be implemented by the development team
- B) There is a clear, objective pass/fail criterion
- C) It is measurable in financial terms
- D) It has been approved by the sponsor

<details>
<summary>Reveal Answer</summary>

**B) There is a clear, objective pass/fail criterion.** A testable requirement specifies exactly what must be true for the requirement to be satisfied — removing subjective interpretation.

</details>

---

**Question 2:** In MoSCoW prioritisation, "Won't have" means:

- A) This requirement has been rejected permanently
- B) This requirement will be cut if budget runs out
- C) This requirement is explicitly out of scope for this delivery, but may be addressed later
- D) This requirement is too complex to implement

<details>
<summary>Reveal Answer</summary>

**C) This requirement is explicitly out of scope for this delivery, but may be addressed later.** Won't have manages stakeholder expectations by making the boundary explicit. It is not a permanent rejection — it means "not this time."

</details>

---

**Question 3:** What is the purpose of bidirectional traceability in an RTM?

- A) Forward trace confirms all requirements are implemented; backward trace confirms nothing unnecessary was built
- B) Forward trace confirms cost; backward trace confirms schedule
- C) Bidirectional traceability is only used in regulated industries
- D) It tracks requirements changes over time

<details>
<summary>Reveal Answer</summary>

**A) Forward trace confirms all requirements are implemented; backward trace confirms nothing unnecessary was built.** Together, both directions ensure completeness and prevent gold-plating.

</details>

---

**Question 4:** A developer adds a "dark mode" feature to the application because they personally think it would be useful, without any requirement or change request. This is an example of:

- A) Scope change
- B) Progressive elaboration
- C) Scope creep (gold-plating)
- D) A legitimate enhancement

<details>
<summary>Reveal Answer</summary>

**C) Scope creep (gold-plating).** Adding unrequested features without going through change control — even well-intentioned ones — is scope creep. It consumes time and budget, and may introduce unintended complexity or defects.

</details>

---

**Question 5:** Which type of requirements is most commonly missed in initial requirements gathering?

- A) Business requirements
- B) Non-functional and transition requirements
- C) Functional requirements
- D) Stakeholder requirements

<details>
<summary>Reveal Answer</summary>

**B) Non-functional and transition requirements.** Non-functional requirements (performance, security, scalability) and transition requirements (data migration, training, cutover) are frequently overlooked because stakeholders focus on features. Their absence causes significant overruns when discovered late.

</details>

[↑ Back to top](#table-of-contents)

---

**Previous Module:** [Module 07 — Project Closing](07-closing.md)
**Next Module:** [Module 09 — Stakeholder Management](09-stakeholder-management.md)

---

&copy; UncleJs &mdash; Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

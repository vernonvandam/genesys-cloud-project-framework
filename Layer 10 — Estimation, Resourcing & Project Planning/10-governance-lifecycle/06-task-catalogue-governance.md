# Layer 10 — 10.06 Task Catalogue Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.06 |
| Capability | Task Catalogue Governance |
| Task Catalogue ID | 10.06 |
| Primary Layer 1 Phases | P03, P04, P12 |

## Capability Objective

Govern creation, review, modification, supersession and retirement of Layer 10 task definitions.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Identify required task coverage |
| P04 | Establish controlled task definitions |
| P12 | Review task performance and lifecycle |

## Source Implementation Activities

1. Identify catalogue gaps.
2. Define task records.
3. Review tasks.
4. Approve task changes.
5. Retire obsolete tasks.

## Implementation Tasks

### Activity 01 — Review

#### L10-10.06-001 — Review Task Catalogue Coverage

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Review catalogue coverage against the project methodology and applicable capabilities.

**Dependencies**

- Layer 2 capability catalogue

**Deliverable**

Catalogue coverage review.

**Acceptance Criteria**

Required task coverage is identified.

### Activity 02 — Define

#### L10-10.06-002 — Define New or Updated Task

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Create or update task definitions using the approved task standard.

**Dependencies**

- L10-10.06-001

**Deliverable**

Task definition.

**Acceptance Criteria**

Task contains all mandatory fields.

### Activity 03 — Review

#### L10-10.06-003 — Review Task Catalogue Change

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Review task dependencies, Layer 1 mapping, role, effort and acceptance criteria.

**Dependencies**

- L10-10.06-002

**Deliverable**

Task review record.

**Acceptance Criteria**

Task conforms to the task standard.

### Activity 04 — Retire

#### L10-10.06-004 — Retire Superseded Task

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Retire obsolete tasks while preserving historical traceability.

**Dependencies**

- L10-10.06-003

**Deliverable**

Updated task catalogue.

**Acceptance Criteria**

Superseded task remains historically traceable.

## Capability-Level Dependencies

- Layer 2 capability catalogue
- Task standard
- Estimation model

## Capability-Level Estimation Considerations

Catalogue maintenance effort is driven by number of tasks and methodology change frequency.

## Definition of Done

Task definitions are controlled, versioned and traceable.

---
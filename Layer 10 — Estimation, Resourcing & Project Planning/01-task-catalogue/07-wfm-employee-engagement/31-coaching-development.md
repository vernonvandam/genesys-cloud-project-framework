# Layer 10 — 2.07.31 Coaching & Development

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.31 |
| Capability | Coaching & Development |
| Task Catalogue ID | 07.31 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Support structured employee coaching and development processes where required.

## Source Implementation Activities

1. Determine coaching scope.
2. Define coaching model.
3. Configure coaching processes.
4. Validate workflows.
5. Establish BAU ownership.

## Implementation Tasks

### Activity 01 — Define Coaching

#### L10-07.31-001 — Confirm Coaching Requirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Determine whether coaching and development functionality is required.

**Dependencies**

- Performance management
- Employee engagement scope

**Deliverable**

Coaching scope decision.

**Acceptance Criteria**

Requirement is confirmed.

#### L10-07.31-002 — Define Coaching Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define coaching triggers, ownership, workflows, records and outcomes.

**Dependencies**

- L10-07.31-001

**Deliverable**

Coaching model.

**Acceptance Criteria**

Model is approved.

### Activity 02 — Implement and Validate

#### L10-07.31-003 — Configure Coaching Processes

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure approved coaching workflows and supporting capabilities.

**Dependencies**

- L10-07.31-002

**Deliverable**

Configured coaching capability.

**Acceptance Criteria**

Coaching workflow is operational.

#### L10-07.31-004 — Validate Coaching Workflow

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Validate coaching initiation, completion and reporting.

**Dependencies**

- L10-07.31-003

**Deliverable**

Coaching test evidence.

**Acceptance Criteria**

Coaching workflow passes UAT.
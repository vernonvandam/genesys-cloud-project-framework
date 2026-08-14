# Layer 10 — 2.07.14 Scheduling Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.14 |
| Capability | Scheduling Strategy |
| Task Catalogue ID | 07.14 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P09 |

## Capability Objective

Define the rules and operating model used to create workforce schedules.

## Source Implementation Activities

1. Discover scheduling requirements.
2. Define schedule rules.
3. Define employee constraints.
4. Define scheduling governance.
5. Validate schedule strategy.

## Implementation Tasks

### Activity 01 — Define Schedule Requirements

#### L10-07.14-001 — Capture Scheduling Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Capture coverage, operating hours, employee constraints and service requirements.

**Dependencies**

- Staffing model
- Business hours

**Deliverable**

Scheduling requirements.

**Acceptance Criteria**

Scheduling requirements are approved.

#### L10-07.14-002 — Define Schedule Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define shift, break, activity, coverage and employee constraint rules.

**Dependencies**

- L10-07.14-001

**Deliverable**

Schedule rules catalogue.

**Acceptance Criteria**

Rules are documented and approved.

### Activity 02 — Validate Scheduling Strategy

#### L10-07.14-003 — Configure Scheduling Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure scheduling rules and constraints.

**Dependencies**

- L10-07.14-002

**Deliverable**

Configured scheduling strategy.

**Acceptance Criteria**

Approved rules are configured.

#### L10-07.14-004 — Validate Scheduling Outcomes

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate generated schedules against coverage and employee requirements.

**Dependencies**

- L10-07.14-003

**Deliverable**

Scheduling validation report.

**Acceptance Criteria**

Schedules meet agreed coverage and workforce rules.
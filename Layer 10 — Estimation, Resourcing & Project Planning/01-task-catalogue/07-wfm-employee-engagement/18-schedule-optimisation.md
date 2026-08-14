# Layer 10 — 2.07.18 Schedule Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.18 |
| Capability | Schedule Optimisation |
| Task Catalogue ID | 07.18 |
| Primary Layer 1 Phases | P06, P08, P11, P12 |

## Capability Objective

Optimise schedules to improve service coverage, workforce utilisation and employee outcomes.

## Source Implementation Activities

1. Identify optimisation objectives.
2. Apply optimisation rules.
3. Review optimisation outcomes.
4. Approve optimised schedules.
5. Establish optimisation review.

## Implementation Tasks

### Activity 01 — Define Optimisation

#### L10-07.18-001 — Identify Schedule Optimisation Objectives

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define priorities for service level, coverage, utilisation, cost and employee experience.

**Dependencies**

- Scheduling strategy

**Deliverable**

Optimisation objectives.

**Acceptance Criteria**

Objectives are approved.

#### L10-07.18-002 — Apply Schedule Optimisation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Apply approved optimisation rules to generated schedules.

**Dependencies**

- L10-07.18-001
- Schedule generation

**Deliverable**

Optimised schedule.

**Acceptance Criteria**

Optimisation completes successfully.

### Activity 02 — Validate

#### L10-07.18-003 — Compare Pre- and Post-Optimisation Results

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Compare coverage, staffing and employee impacts before and after optimisation.

**Dependencies**

- L10-07.18-002

**Deliverable**

Optimisation analysis.

**Acceptance Criteria**

Benefits and trade-offs are documented.

#### L10-07.18-004 — Approve Optimisation Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | WFM Owner |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Approve optimisation rules and operating thresholds for BAU.

**Dependencies**

- L10-07.18-003

**Deliverable**

Approved optimisation model.

**Acceptance Criteria**

BAU WFM owner accepts the optimisation model.
# Layer 10 — 2.07.17 Schedule Generation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.17 |
| Capability | Schedule Generation |
| Task Catalogue ID | 07.17 |
| Primary Layer 1 Phases | P06, P08, P10, P11 |

## Capability Objective

Generate schedules that align staffing requirements, employee constraints and approved scheduling rules.

## Source Implementation Activities

1. Prepare schedule inputs.
2. Generate schedules.
3. Review schedule coverage.
4. Resolve exceptions.
5. Approve schedules.

## Implementation Tasks

### Activity 01 — Generate Schedules

#### L10-07.17-001 — Prepare Schedule Inputs

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate forecast, staffing requirements, activities, shifts and employee constraints.

**Dependencies**

- Forecast
- Staffing requirements
- Shift planning

**Deliverable**

Schedule-ready configuration.

**Acceptance Criteria**

All schedule inputs are available.

#### L10-07.17-002 — Generate Workforce Schedule

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Generate schedules using approved demand and scheduling rules.

**Dependencies**

- L10-07.17-001

**Deliverable**

Generated schedules.

**Acceptance Criteria**

Schedules are generated successfully.

### Activity 02 — Review and Approve

#### L10-07.17-003 — Review Schedule Coverage

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review coverage, staffing gaps, overstaffing and employee constraints.

**Dependencies**

- L10-07.17-002

**Deliverable**

Schedule review record.

**Acceptance Criteria**

Schedule exceptions are identified and resolved.

#### L10-07.17-004 — Approve Schedule

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | WFM Owner |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Approve the schedule for production publication.

**Dependencies**

- L10-07.17-003

**Deliverable**

Approved schedule.

**Acceptance Criteria**

Customer approves schedule for publication.
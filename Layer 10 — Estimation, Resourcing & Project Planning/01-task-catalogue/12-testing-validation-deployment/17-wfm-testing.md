# Layer 10 — 2.12.17 WFM Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.17 — WFM Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.17 |
| Default Classification | CONDITIONAL |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | WFM Specialist |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | MANUAL |
| Critical Path | CONDITIONAL |

## Capability Objective

Validate workforce management configuration, forecasting, scheduling, adherence, staffing and related operational workflows where WFM is in scope.

## Source Implementation Activities

- Validate WFM configuration.
- Validate workforce data.
- Test forecasting and scheduling.
- Test adherence and operational workflows.
- Validate WFM outputs.

## Implementation Tasks

### Activity 01 — Validate WFM Configuration

#### L10-12.17-001 — Validate WFM Baseline

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | WFM Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate WFM structures, groups, schedules and configuration.

**Dependencies**

WFM implementation.

**Deliverable**

WFM Configuration Validation.

**Acceptance Criteria**

Configuration matches approved design.

### Activity 02 — Test Forecasting

#### L10-12.17-002 — Validate Forecasting and Scheduling

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | WFM Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate forecasting inputs, schedules and expected staffing outputs.

**Dependencies**

L10-12.17-001 and test data.

**Deliverable**

WFM Forecast/Schedule Test Results.

**Acceptance Criteria**

Forecast and schedule outcomes are acceptable.

### Activity 03 — Test Adherence

#### L10-12.17-003 — Validate Adherence Workflows

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | WFM Specialist |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate adherence monitoring and operational workflows.

**Dependencies**

L10-12.17-002.

**Deliverable**

Adherence Validation Results.

**Acceptance Criteria**

Required adherence workflows operate correctly.

## Capability-Level Dependencies

- WFM
- Core Platform
- Identity & Access
- Data

## Capability-Level Estimation Considerations

WFM complexity, staffing groups, schedules and data volume drive effort.

## Definition of Done

All in-scope WFM functionality passes testing.

---
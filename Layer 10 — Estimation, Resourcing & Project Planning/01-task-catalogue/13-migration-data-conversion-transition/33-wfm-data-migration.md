# Layer 10 — 2.13.33 WFM Data Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.33 |
| Capability | WFM Data Migration |
| Task Catalogue ID | 13.33 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |
| Classification | CONDITIONAL |

## Capability Objective

Determine and execute migration of workforce-management data, history, schedules and related configuration.

## Implementation Tasks

### L10-13.33-001 — Assess WFM Migration Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | WFM Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Assess WFM history, configuration, schedules, forecasts and employee data.

**Dependencies**

- WFM scope
- Migration strategy

**Deliverable**

WFM migration assessment.

**Acceptance Criteria**

WFM migration scope is approved.

### L10-13.33-002 — Implement WFM Data Transition

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | WFM Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 5.0h |
| Critical Path | CONDITIONAL |

**Description**

Migrate or recreate approved WFM data and configuration.

**Dependencies**

- L10-13.33-001

**Deliverable**

WFM data transition.

**Acceptance Criteria**

Required WFM data is available.

### L10-13.33-003 — Validate WFM Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Specialist |
| Customer Responsibility | YES |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate WFM data, schedules and operational history.

**Dependencies**

- L10-13.33-002

**Deliverable**

WFM validation report.

**Acceptance Criteria**

Customer accepts migrated WFM data.

## Definition of Done

Required WFM data and configuration are transitioned and accepted.

---
# Layer 10 — 2.07.38 Payroll & Time Integration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.38 |
| Capability | Payroll & Time Integration |
| Task Catalogue ID | 07.38 |
| Primary Layer 1 Phases | P03, P04, P07, P08, P10, P11 |

## Capability Objective

Integrate WFM time and workforce information with payroll or timekeeping systems where required.

## Source Implementation Activities

1. Determine payroll integration requirements.
2. Define time and attendance mappings.
3. Implement integration.
4. Reconcile records.
5. Validate payroll processing.

## Implementation Tasks

### Activity 01 — Define Payroll Integration

#### L10-07.38-001 — Confirm Payroll Integration Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Determine whether WFM data must integrate with payroll or timekeeping systems.

**Dependencies**

- Payroll requirements

**Deliverable**

Payroll integration scope.

**Acceptance Criteria**

Scope is approved.

#### L10-07.38-002 — Define Payroll Data Mapping

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define time, attendance, activity, leave and employee mappings.

**Dependencies**

- L10-07.38-001

**Deliverable**

Payroll data mapping.

**Acceptance Criteria**

Mapping is approved.

### Activity 02 — Implement and Validate

#### L10-07.38-003 — Implement Payroll Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | API / SCRIPT |
| Baseline Effort | 6.0h |
| Critical Path | NO |

**Description**

Implement approved payroll or timekeeping integration.

**Dependencies**

- L10-07.38-002

**Deliverable**

Working payroll integration.

**Acceptance Criteria**

Integration executes successfully.

#### L10-07.38-004 — Reconcile Payroll Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | SCRIPT |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Reconcile source and target time records.

**Dependencies**

- L10-07.38-003

**Deliverable**

Payroll reconciliation report.

**Acceptance Criteria**

Approved test records reconcile.
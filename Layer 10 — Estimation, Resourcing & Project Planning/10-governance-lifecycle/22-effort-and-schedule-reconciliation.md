# Layer 10 — 10.22 Effort & Schedule Reconciliation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.22 |
| Capability | Effort & Schedule Reconciliation |
| Task Catalogue ID | 10.22 |
| Primary Layer 1 Phases | P04, P09, P11, P12 |

## Capability Objective

Ensure effort, duration, resource allocation and schedule dates remain internally consistent.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Reconcile planning model |
| P09 | Validate baseline |
| P11 | Reconcile forecast |
| P12 | Reconcile final actuals |

## Source Implementation Activities

1. Reconcile effort.
2. Reconcile duration.
3. Reconcile resources.
4. Resolve discrepancies.

## Implementation Tasks

### Activity 01 — Reconcile

#### L10-10.22-001 — Reconcile Task Effort to Schedule

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P04 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm task effort aligns with scheduled duration and resource allocation.

**Dependencies**

- Estimation model
- Schedule model

**Deliverable**

Effort reconciliation.

**Acceptance Criteria**

No unexplained material discrepancies remain.

### Activity 02 — Validate

#### L10-10.22-002 — Validate Baseline Reconciliation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate effort, duration and resource totals before baseline approval.

**Dependencies**

- L10-10.22-001

**Deliverable**

Baseline reconciliation record.

**Acceptance Criteria**

Totals reconcile.

### Activity 03 — Reconcile Forecast

#### L10-10.22-003 — Reconcile Current Forecast

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Project Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Reconcile current forecast against actual progress.

**Dependencies**

- Actuals
- Current forecast

**Deliverable**

Forecast reconciliation.

**Acceptance Criteria**

Forecast totals reconcile.

### Activity 04 — Close

#### L10-10.22-004 — Reconcile Final Project Actuals

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Reconcile final effort, schedule and resource actuals.

**Dependencies**

- Final actuals

**Deliverable**

Final reconciliation report.

**Acceptance Criteria**

Final totals are reconciled.

## Capability-Level Dependencies

- Estimation model
- Schedule
- Actuals
- Resource model

## Capability-Level Estimation Considerations

Effort depends on model complexity and number of reconciliation dimensions.

## Definition of Done

Effort, schedule and resource information reconcile at baseline, forecast and closure.

---
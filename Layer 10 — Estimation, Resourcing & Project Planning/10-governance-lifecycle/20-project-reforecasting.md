# Layer 10 — 10.20 Project Reforecasting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.20 |
| Capability | Project Reforecasting |
| Task Catalogue ID | 10.20 |
| Primary Layer 1 Phases | P10, P11 |

## Capability Objective

Recalculate project effort, duration, resources and completion forecast using current delivery evidence.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P10 | Reassess production deployment forecast |
| P11 | Maintain current forecast during hypercare |

## Source Implementation Activities

1. Capture actuals.
2. Assess remaining work.
3. Assess changes and risks.
4. Calculate forecast.
5. Approve forecast.

## Implementation Tasks

### Activity 01 — Capture

#### L10-10.20-001 — Capture Current Project Actuals

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Capture completed effort, task status and actual dates.

**Dependencies**

- Project schedule
- Delivery status

**Deliverable**

Current actuals dataset.

**Acceptance Criteria**

Actuals are current and traceable.

### Activity 02 — Assess

#### L10-10.20-002 — Assess Remaining Work

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Assess remaining tasks, effort, risks and dependencies.

**Dependencies**

- L10-10.20-001

**Deliverable**

Remaining work assessment.

**Acceptance Criteria**

Remaining effort is identified.

### Activity 03 — Calculate

#### L10-10.20-003 — Calculate Current Forecast

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Calculate current forecast from actuals and remaining work.

**Dependencies**

- L10-10.20-002

**Deliverable**

Current project forecast.

**Acceptance Criteria**

Forecast is internally consistent.

### Activity 04 — Approve

#### L10-10.20-004 — Approve Current Forecast

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Review and approve the current project forecast.

**Dependencies**

- L10-10.20-003

**Deliverable**

Approved forecast.

**Acceptance Criteria**

Forecast is accepted as the current planning baseline.

## Capability-Level Dependencies

- Actuals
- Schedule
- Estimate
- Change control

## Capability-Level Estimation Considerations

Reforecasting effort depends on project size and reporting cadence.

## Definition of Done

Current forecast accurately reflects actual delivery and remaining work.

---
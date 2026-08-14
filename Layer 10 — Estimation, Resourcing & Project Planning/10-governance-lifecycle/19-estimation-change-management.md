# Layer 10 — 10.19 Estimation Change Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.19 |
| Capability | Estimation Change Management |
| Task Catalogue ID | 10.19 |
| Primary Layer 1 Phases | P06, P10, P11 |

## Capability Objective

Control changes to approved estimates resulting from scope, technical, resource or delivery changes.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P06 | Assess implementation-driven estimate changes |
| P10 | Assess deployment changes |
| P11 | Reforecast based on actual delivery |

## Source Implementation Activities

1. Identify estimate change.
2. Assess impact.
3. Approve change.
4. Update estimate.
5. Record version.

## Implementation Tasks

### Activity 01 — Identify

#### L10-10.19-001 — Identify Estimate Change Trigger

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify events requiring estimate reassessment.

**Dependencies**

- Change control

**Deliverable**

Estimate change trigger.

**Acceptance Criteria**

Trigger and affected scope are recorded.

### Activity 02 — Assess

#### L10-10.19-002 — Assess Estimate Impact

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Estimation Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Assess effort, duration, role and schedule impacts.

**Dependencies**

- L10-10.19-001

**Deliverable**

Estimate impact assessment.

**Acceptance Criteria**

Material impact is quantified.

### Activity 03 — Approve

#### L10-10.19-003 — Approve Estimate Change

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Obtain required approval for estimate change.

**Dependencies**

- L10-10.19-002

**Deliverable**

Approved estimate change.

**Acceptance Criteria**

Approval is documented.

### Activity 04 — Update

#### L10-10.19-004 — Update Current Estimate

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Update the current forecast and preserve prior versions.

**Dependencies**

- L10-10.19-003

**Deliverable**

Updated estimate version.

**Acceptance Criteria**

Forecast and version history are updated.

## Capability-Level Dependencies

- Change control
- Estimation version control
- Reforecasting

## Capability-Level Estimation Considerations

Effort depends on number of affected tasks and change complexity.

## Definition of Done

Estimate changes are assessed, approved and incorporated into controlled forecasts.

---
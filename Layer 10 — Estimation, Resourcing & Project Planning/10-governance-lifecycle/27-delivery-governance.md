# Layer 10 — 10.27 Delivery Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.27 |
| Capability | Delivery Governance |
| Task Catalogue ID | 10.27 |
| Primary Layer 1 Phases | P06, P07, P08, P09, P10, P11 |

## Capability Objective

Govern delivery execution against approved tasks, dependencies, effort, schedule and acceptance criteria.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P06 | Govern configuration delivery |
| P07 | Govern integration and migration delivery |
| P08 | Govern testing |
| P09 | Govern readiness |
| P10 | Govern go-live |
| P11 | Govern hypercare |

## Source Implementation Activities

1. Monitor delivery.
2. Review task completion.
3. Manage blockers.
4. Validate deliverables.
5. Escalate delivery issues.

## Implementation Tasks

### Activity 01 — Establish

#### L10-10.27-001 — Establish Delivery Governance Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define delivery tracking and escalation controls.

**Dependencies**

- Project baseline

**Deliverable**

Delivery governance controls.

**Acceptance Criteria**

Controls are operational.

### Activity 02 — Monitor

#### L10-10.27-002 — Monitor Delivery Task Status

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Monitor task progress, dependencies, blockers and deliverables.

**Dependencies**

- L10-10.27-001

**Deliverable**

Delivery status report.

**Acceptance Criteria**

Current delivery status is visible.

### Activity 03 — Validate

#### L10-10.27-003 — Validate Delivery Against Baseline

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate delivery performance against baseline scope, effort and schedule.

**Dependencies**

- L10-10.27-002

**Deliverable**

Delivery validation.

**Acceptance Criteria**

Material deviations are identified.

### Activity 04 — Govern Hypercare

#### L10-10.27-004 — Govern Hypercare Delivery

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Govern remaining delivery, defects and operational transition during hypercare.

**Dependencies**

- Production deployment

**Deliverable**

Hypercare governance record.

**Acceptance Criteria**

Outstanding delivery issues are governed through closure or handover.

## Capability-Level Dependencies

- Project schedule
- Task catalogue
- Operations model

## Capability-Level Estimation Considerations

Effort depends on delivery cadence and number of workstreams.

## Definition of Done

Delivery execution is controlled from build through hypercare.

---
# Layer 10 — 10.03 Baseline Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.03 |
| Capability | Baseline Management |
| Task Catalogue ID | 10.03 |
| Primary Layer 1 Phases | P04, P09, P10, P12 |

## Capability Objective

Establish and control the approved project scope, effort, resource and schedule baseline.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Define baseline structure |
| P09 | Approve project baseline |
| P10 | Control baseline during go-live |
| P12 | Archive final baseline |

## Source Implementation Activities

1. Define baseline.
2. Assemble baseline.
3. Approve baseline.
4. Control baseline.
5. Archive baseline.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.03-001 — Define Project Baseline Components

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define scope, task, effort, resource, dependency and schedule baseline components.

**Dependencies**

- Approved scope
- L10-10.02-002

**Deliverable**

Baseline definition.

**Acceptance Criteria**

Baseline components are documented.

### Activity 02 — Assemble

#### L10-10.03-002 — Assemble Project Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Assemble approved scope, tasks, effort, resources, dependencies and schedule.

**Dependencies**

- L10-10.03-001

**Deliverable**

Draft project baseline.

**Acceptance Criteria**

Baseline is internally consistent.

### Activity 03 — Approve

#### L10-10.03-003 — Approve Project Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain formal baseline approval.

**Dependencies**

- L10-10.03-002

**Deliverable**

Approved baseline.

**Acceptance Criteria**

Baseline approval is recorded.

### Activity 04 — Archive

#### L10-10.03-004 — Archive Final Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Project Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Archive the final project baseline and associated versions.

**Dependencies**

- L10-10.03-003

**Deliverable**

Baseline archive.

**Acceptance Criteria**

Approved baseline remains recoverable.

## Capability-Level Dependencies

- Scope
- Estimate
- Schedule
- Resource plan
- Dependency model

## Capability-Level Estimation Considerations

Effort is driven by project size, workstream count and baseline complexity.

## Definition of Done

An approved, version-controlled project baseline exists and can be reconciled with the final project outcome.

---
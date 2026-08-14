# Layer 10 — 10.08 Role & Resource Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.08 |
| Capability | Role & Resource Governance |
| Task Catalogue ID | 10.08 |
| Primary Layer 1 Phases | P03, P04, P09, P11 |

## Capability Objective

Govern role definitions, resource assumptions, capacity and allocation.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define role requirements |
| P04 | Establish resource model |
| P09 | Validate project capacity |
| P11 | Reforecast resource needs |

## Source Implementation Activities

1. Define roles.
2. Map roles to tasks.
3. Assess capacity.
4. Approve resource plan.
5. Reforecast capacity.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.08-001 — Define Project Role Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Resource Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify roles required to deliver the scoped project.

**Dependencies**

- Scope
- Task catalogue

**Deliverable**

Role requirements.

**Acceptance Criteria**

Required roles are identified.

### Activity 02 — Map

#### L10-10.08-002 — Map Roles to Planned Tasks

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Resource Manager |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map approved roles to implementation tasks.

**Dependencies**

- L10-10.08-001

**Deliverable**

Resource allocation model.

**Acceptance Criteria**

All planned effort has an accountable role.

### Activity 03 — Validate

#### L10-10.08-003 — Validate Resource Capacity

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Resource Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate planned resource demand against available capacity.

**Dependencies**

- L10-10.08-002

**Deliverable**

Capacity validation.

**Acceptance Criteria**

Capacity gaps are identified and addressed.

### Activity 04 — Reforecast

#### L10-10.08-004 — Reforecast Resource Demand

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P11 |
| Primary Role | Resource Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Reforecast resource demand based on actual delivery performance.

**Dependencies**

- Actual effort
- Current forecast

**Deliverable**

Updated resource forecast.

**Acceptance Criteria**

Resource forecast reflects current project demand.

## Capability-Level Dependencies

- Role catalogue
- Task catalogue
- Schedule model

## Capability-Level Estimation Considerations

Resource scarcity and specialist skills can materially affect duration and critical path.

## Definition of Done

Roles and resource capacity are governed throughout the project lifecycle.

---
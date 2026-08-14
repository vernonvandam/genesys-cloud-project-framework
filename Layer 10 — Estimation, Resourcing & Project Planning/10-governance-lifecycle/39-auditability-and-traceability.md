# Layer 10 — 10.39 Auditability & Traceability

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.39 |
| Capability | Auditability & Traceability |
| Task Catalogue ID | 10.39 |
| Primary Layer 1 Phases | P04, P09, P12 |

## Capability Objective

Ensure project-planning outputs can be traced from capability through task, effort, role, dependency, schedule and governance decision.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Establish traceability model |
| P09 | Validate baseline traceability |
| P12 | Validate final traceability |

## Source Implementation Activities

1. Define traceability chain.
2. Map records.
3. Validate traceability.
4. Resolve gaps.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.39-001 — Define Traceability Chain

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define required relationships between capabilities, tasks, effort, roles, dependencies, schedule and outputs.

**Dependencies**

- Task standard
- Estimation model

**Deliverable**

Traceability model.

**Acceptance Criteria**

Traceability requirements are documented.

### Activity 02 — Map

#### L10-10.39-002 — Map Project Records

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Map project records across the defined traceability chain.

**Dependencies**

- L10-10.39-001

**Deliverable**

Traceability dataset.

**Acceptance Criteria**

Material project records are linked.

### Activity 03 — Validate

#### L10-10.39-003 — Validate End-to-End Traceability

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

Validate that material project outputs can be traced to source records.

**Dependencies**

- L10-10.39-002

**Deliverable**

Traceability validation.

**Acceptance Criteria**

No critical traceability gaps remain.

### Activity 04 — Finalise

#### L10-10.39-004 — Validate Final Project Traceability

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Confirm final project records remain fully traceable.

**Dependencies**

- Final project data

**Deliverable**

Final traceability report.

**Acceptance Criteria**

Final traceability is complete.

## Capability-Level Dependencies

- Layer 1
- Layer 2
- Layer 10 task catalogue
- Estimation model

## Capability-Level Estimation Considerations

Traceability effort increases with task and artefact count.

## Definition of Done

The complete project planning chain is traceable from capability to final output.

---
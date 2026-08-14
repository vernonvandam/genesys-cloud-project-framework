# Layer 10 — 10.09 Dependency Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.09 |
| Capability | Dependency Governance |
| Task Catalogue ID | 10.09 |
| Primary Layer 1 Phases | P03, P04, P06, P11 |

## Capability Objective

Control task, technical, customer, approval and external dependencies.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Identify dependencies |
| P04 | Model dependencies |
| P06 | Manage active dependencies |
| P11 | Reassess remaining dependencies |

## Source Implementation Activities

1. Identify dependencies.
2. Classify dependencies.
3. Model dependency relationships.
4. Monitor blockers.
5. Reassess dependencies.

## Implementation Tasks

### Activity 01 — Identify

#### L10-10.09-001 — Identify Project Dependencies

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify internal, customer, technical, approval and external dependencies.

**Dependencies**

- Task catalogue
- Requirements

**Deliverable**

Dependency register.

**Acceptance Criteria**

Material dependencies are identified.

### Activity 02 — Model

#### L10-10.09-002 — Model Task Dependencies

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define predecessor, successor and relationship types.

**Dependencies**

- L10-10.09-001

**Deliverable**

Dependency model.

**Acceptance Criteria**

Task relationships are complete and valid.

### Activity 03 — Monitor

#### L10-10.09-003 — Monitor Dependency Status

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Monitor blocking and at-risk dependencies.

**Dependencies**

- L10-10.09-002

**Deliverable**

Dependency status report.

**Acceptance Criteria**

Blocked dependencies are escalated.

### Activity 04 — Reassess

#### L10-10.09-004 — Reassess Remaining Dependencies

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Confirm remaining dependencies are still valid and correctly sequenced.

**Dependencies**

- L10-10.09-003

**Deliverable**

Updated dependency register.

**Acceptance Criteria**

Remaining dependencies are current.

## Capability-Level Dependencies

- Task catalogue
- Schedule model
- Customer activities

## Capability-Level Estimation Considerations

Dependency density and external dependency ownership are significant schedule drivers.

## Definition of Done

All material dependencies are identified, modelled and actively governed.

---
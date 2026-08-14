# Layer 10 — 10.05 Change Control

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.05 |
| Capability | Change Control |
| Task Catalogue ID | 10.05 |
| Primary Layer 1 Phases | P03, P06, P10, P11 |

## Capability Objective

Control changes affecting project scope, effort, schedule, resources or dependencies.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Establish change process |
| P06 | Assess implementation changes |
| P10 | Govern production changes |
| P11 | Control hypercare changes |

## Source Implementation Activities

1. Establish change process.
2. Capture change.
3. Assess impact.
4. Approve change.
5. Update baseline.

## Implementation Tasks

### Activity 01 — Establish

#### L10-10.05-001 — Establish Change Control Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define change submission, impact assessment, approval and implementation rules.

**Dependencies**

- L10-10.01-002

**Deliverable**

Change control process.

**Acceptance Criteria**

Change workflow is approved.

### Activity 02 — Assess

#### L10-10.05-002 — Assess Change Impact

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Assess scope, effort, schedule, resource, dependency and risk impacts.

**Dependencies**

- L10-10.05-001

**Deliverable**

Change impact assessment.

**Acceptance Criteria**

All material impacts are identified.

### Activity 03 — Approve

#### L10-10.05-003 — Approve Project Change

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

Obtain required customer and internal approval.

**Dependencies**

- L10-10.05-002

**Deliverable**

Approved change record.

**Acceptance Criteria**

Approval is documented.

### Activity 04 — Update

#### L10-10.05-004 — Update Project Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Update affected project records and preserve the previous baseline.

**Dependencies**

- L10-10.05-003

**Deliverable**

Updated project baseline.

**Acceptance Criteria**

Change is traceable through all affected planning artefacts.

## Capability-Level Dependencies

- Baseline
- Scope governance
- Estimation governance

## Capability-Level Estimation Considerations

Effort depends on change complexity and number of affected workstreams.

## Definition of Done

Changes are assessed, approved, implemented and fully traceable.

---
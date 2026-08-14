# Layer 10 — 2.02.02 User Lifecycle Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.02 |
| Capability | User Lifecycle Management |
| Task Catalogue ID | 02.02 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P07, P08, P09, P12 |

## Capability Objective

Define and implement the joiner, mover, leaver and ongoing user lifecycle processes required to manage Genesys Cloud identities.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess current lifecycle processes |
| P03 | Define lifecycle requirements |
| P04 | Design target lifecycle |
| P06 | Configure user lifecycle controls |
| P07 | Integrate provisioning |
| P08 | Test lifecycle scenarios |
| P09 | Establish BAU lifecycle management |
| P12 | Handover lifecycle procedures |

## Source Implementation Activities

1. Assess current joiner/mover/leaver processes.
2. Define lifecycle states and ownership.
3. Map lifecycle events to Genesys Cloud actions.
4. Configure lifecycle processes.
5. Test joiner, mover and leaver scenarios.
6. Document BAU lifecycle procedures.

## Implementation Tasks

### Activity 01 — Assess Lifecycle

#### L10-02.02-001 — Assess Existing User Lifecycle

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Assess existing joiner, mover, leaver and account-recertification processes.

**Dependencies**

- L10-02.01-003

**Deliverable**

Lifecycle assessment.

**Acceptance Criteria**

Current lifecycle processes and gaps are documented.

### Activity 02 — Design Lifecycle

#### L10-02.02-002 — Define User Lifecycle States

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define lifecycle states including onboarding, active, changed, suspended, terminated and removed.

**Dependencies**

- L10-02.02-001

**Deliverable**

Lifecycle state model.

**Acceptance Criteria**

Lifecycle states and transitions are approved.

#### L10-02.02-003 — Map Lifecycle Responsibilities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define responsibility for initiating, approving and executing lifecycle changes.

**Dependencies**

- L10-02.02-002

**Deliverable**

Lifecycle responsibility matrix.

**Acceptance Criteria**

Responsibilities are approved.

### Activity 03 — Configure and Test

#### L10-02.02-004 — Configure Lifecycle Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the platform and supporting processes required to implement the approved lifecycle model.

**Dependencies**

- L10-02.02-003

**Deliverable**

Configured lifecycle process.

**Acceptance Criteria**

Lifecycle process operates according to design.

#### L10-02.02-005 — Test Joiner Mover Leaver Scenarios

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Execute representative joiner, mover and leaver scenarios and verify access changes.

**Dependencies**

- L10-02.02-004

**Deliverable**

Lifecycle test evidence.

**Acceptance Criteria**

All required lifecycle scenarios pass.

### Activity 04 — Handover

#### L10-02.02-006 — Document BAU Lifecycle Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document BAU processes for user creation, change, suspension and removal.

**Dependencies**

- L10-02.02-005

**Deliverable**

Lifecycle operating procedure.

**Acceptance Criteria**

Customer accepts the BAU lifecycle procedure.
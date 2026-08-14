# Layer 10 — 2.10.28 Evaluation Workflow

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.28 |
| Capability | Evaluation Workflow |
| Task Catalogue ID | 10.28 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Implement the operational workflow governing evaluation creation, completion, review and follow-up.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define workflow requirements |
| P04 | Design workflow |
| P05 | Configure workflow |
| P08 | Validate workflow |
| P09 | User acceptance |

## Source Implementation Activities

1. Define evaluation lifecycle.
2. Design workflow.
3. Configure workflow.
4. Validate lifecycle.

## Implementation Tasks

### Activity 01 — Workflow Design

#### L10-10.28-001 — Define Evaluation Workflow Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Quality Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define evaluation lifecycle stages, ownership and completion requirements.

**Dependencies**

- Evaluation assignment

**Deliverable**

Workflow requirements.

**Acceptance Criteria**

Workflow requirements are approved.

#### L10-10.28-002 — Design Evaluation Workflow

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Design workflow states, transitions, ownership and exception handling.

**Dependencies**

- L10-10.28-001

**Deliverable**

Evaluation workflow design.

**Acceptance Criteria**

Workflow design is approved.

### Activity 02 — Implement and Validate

#### L10-10.28-003 — Configure Evaluation Workflow

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure the approved evaluation workflow.

**Dependencies**

- L10-10.28-002

**Deliverable**

Configured evaluation workflow.

**Acceptance Criteria**

Workflow operates according to design.

#### L10-10.28-004 — Validate Evaluation Workflow

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

Validate normal, exception and completion paths.

**Dependencies**

- L10-10.28-003

**Deliverable**

Workflow validation evidence.

**Acceptance Criteria**

All workflow scenarios pass.

## Definition of Done

Evaluation workflow is configured, tested and accepted.

---

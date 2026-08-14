# Layer 10 — 2.10.27 Evaluation Assignment

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.27 |
| Capability | Evaluation Assignment |
| Task Catalogue ID | 10.27 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Define and implement rules for assigning interactions to evaluators.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define assignment requirements |
| P04 | Design assignment model |
| P05 | Configure assignment |
| P08 | Validate assignment |
| P09 | User acceptance |

## Source Implementation Activities

1. Define assignment rules.
2. Define evaluator scope.
3. Configure assignment.
4. Validate assignments.

## Implementation Tasks

### Activity 01 — Assignment Model

#### L10-10.27-001 — Define Evaluation Assignment Requirements

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

Define how evaluations are selected and assigned.

**Dependencies**

- Evaluation framework

**Deliverable**

Assignment requirements.

**Acceptance Criteria**

Assignment rules are approved.

#### L10-10.27-002 — Design Evaluation Assignment Model

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

Define assignment criteria, ownership and distribution model.

**Dependencies**

- L10-10.27-001

**Deliverable**

Assignment design.

**Acceptance Criteria**

Assignment design is approved.

### Activity 02 — Configure and Validate

#### L10-10.27-003 — Configure Evaluation Assignment

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure evaluation assignment rules.

**Dependencies**

- L10-10.27-002

**Deliverable**

Configured assignment model.

**Acceptance Criteria**

Assignments follow approved rules.

#### L10-10.27-004 — Validate Evaluation Assignment

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

Validate assignment scenarios, coverage and evaluator ownership.

**Dependencies**

- L10-10.27-003

**Deliverable**

Assignment validation evidence.

**Acceptance Criteria**

Required assignment scenarios pass.

## Definition of Done

Evaluation assignment operates consistently against approved rules.

---

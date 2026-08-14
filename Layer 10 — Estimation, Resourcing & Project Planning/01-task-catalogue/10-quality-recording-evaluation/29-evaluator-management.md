# Layer 10 — 2.10.29 Evaluator Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.29 |
| Capability | Evaluator Management |
| Task Catalogue ID | 10.29 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P12 |

## Capability Objective

Establish evaluator roles, permissions, responsibilities and operational management.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define evaluator requirements |
| P04 | Design evaluator model |
| P05 | Configure access |
| P08 | Validate evaluator capability |
| P12 | Handover evaluator administration |

## Source Implementation Activities

1. Identify evaluator roles.
2. Define evaluator permissions.
3. Configure evaluator access.
4. Validate evaluator operations.

## Implementation Tasks

### Activity 01 — Evaluator Model

#### L10-10.29-001 — Define Evaluator Roles

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Quality Lead |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Identify evaluator populations and responsibilities.

**Dependencies**

- Evaluation operating model

**Deliverable**

Evaluator role catalogue.

**Acceptance Criteria**

Roles are approved.

#### L10-10.29-002 — Define Evaluator Permissions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define permissions required for evaluator activities.

**Dependencies**

- L10-10.29-001

**Deliverable**

Evaluator permission model.

**Acceptance Criteria**

Permissions are approved.

### Activity 02 — Configure and Validate

#### L10-10.29-003 — Configure Evaluator Access

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure evaluator roles and access.

**Dependencies**

- L10-10.29-002

**Deliverable**

Evaluator access configuration.

**Acceptance Criteria**

Evaluators have appropriate access.

#### L10-10.29-004 — Validate Evaluator Operations

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Validate evaluator access, assignment and evaluation completion.

**Dependencies**

- L10-10.29-003

**Deliverable**

Evaluator validation evidence.

**Acceptance Criteria**

Evaluator scenarios pass.

## Definition of Done

Evaluator roles and permissions are operational and validated.

---

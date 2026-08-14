# Layer 10 — 2.10.08 Recording Policies

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.08 |
| Capability | Recording Policies |
| Task Catalogue ID | 10.08 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P10 |

## Capability Objective

Define and implement recording policies governing when, how and for whom interactions are recorded.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define policy requirements |
| P04 | Design recording policies |
| P05 | Configure policies |
| P08 | Validate policy behaviour |
| P10 | Confirm production readiness |

## Source Implementation Activities

1. Define policy requirements.
2. Design policy rules.
3. Configure policies.
4. Validate policy execution.

## Implementation Tasks

### Activity 01 — Define Policy Model

#### L10-10.08-001 — Define Recording Policy Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define recording rules by interaction, queue, user, business process and compliance requirement.

**Dependencies**

- Recording strategy

**Deliverable**

Recording policy requirements.

**Acceptance Criteria**

Policy rules are approved.

#### L10-10.08-002 — Design Recording Policy Set

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Translate requirements into implementable recording policy rules.

**Dependencies**

- L10-10.08-001

**Deliverable**

Recording policy design.

**Acceptance Criteria**

Policy design is approved.

### Activity 02 — Configure and Validate

#### L10-10.08-003 — Configure Recording Policies

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

Implement approved recording policies.

**Dependencies**

- L10-10.08-002

**Deliverable**

Configured recording policies.

**Acceptance Criteria**

Policies are active and correctly scoped.

#### L10-10.08-004 — Validate Recording Policy Execution

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

Test positive and negative policy scenarios.

**Dependencies**

- L10-10.08-003

**Deliverable**

Policy validation evidence.

**Acceptance Criteria**

All defined policy scenarios pass.

## Definition of Done

Recording policies are approved, configured and validated.

---

# Layer 10 — 10.04 Scope Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.04 |
| Capability | Scope Governance |
| Task Catalogue ID | 10.04 |
| Primary Layer 1 Phases | P02, P03, P04, P09 |

## Capability Objective

Control scope classification, inclusion, exclusion and approval.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess current scope |
| P03 | Define scope |
| P04 | Design scope boundaries |
| P09 | Confirm scope baseline |

## Source Implementation Activities

1. Assess scope.
2. Define scope boundaries.
3. Classify scope.
4. Approve scope.

## Implementation Tasks

### Activity 01 — Assess

#### L10-10.04-001 — Assess Project Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Assess the intended project scope against known requirements and capabilities.

**Dependencies**

- Discovery
- Requirements

**Deliverable**

Scope assessment.

**Acceptance Criteria**

Material scope areas are identified.

### Activity 02 — Classify

#### L10-10.04-002 — Classify Scope Items

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Classify scope as required, conditional, optional, deferred or not applicable.

**Dependencies**

- L10-10.04-001

**Deliverable**

Scope classification register.

**Acceptance Criteria**

Every material scope item has a classification.

### Activity 03 — Define

#### L10-10.04-003 — Define Scope Baseline

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

Document approved scope boundaries and exclusions.

**Dependencies**

- L10-10.04-002

**Deliverable**

Scope baseline.

**Acceptance Criteria**

Scope boundaries are approved.

### Activity 04 — Validate

#### L10-10.04-004 — Validate Scope Before Baseline

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that scope remains aligned with the estimate and project plan.

**Dependencies**

- L10-10.04-003

**Deliverable**

Scope validation record.

**Acceptance Criteria**

Scope is confirmed or exceptions are documented.

## Capability-Level Dependencies

- Requirements
- Capability catalogue
- Customer decisions

## Capability-Level Estimation Considerations

Scope volatility and number of capability domains are major effort drivers.

## Definition of Done

Scope is classified, bounded, approved and aligned to the project estimate.

---
# Layer 10 — 2.14.42 Disaster Recovery

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.42 |
| Capability | Disaster Recovery |
| Task Catalogue ID | 14.42 |
| Primary Layer 1 Phases | P04, P08, P09, P11 |
| Classification | CONDITIONAL |

## Capability Objective

Define and validate applicable disaster recovery procedures and dependencies.

## Implementation Tasks

### L10-14.42-001 — Assess Disaster Recovery Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Assess recovery objectives, platform dependencies, integrations and customer continuity requirements.

**Dependencies**

- Business continuity
- Resilience

**Deliverable**

DR assessment.

**Acceptance Criteria**

DR scope and applicability are approved.

### L10-14.42-002 — Define DR Procedures

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Document recovery procedures and responsibilities applicable to the solution.

**Dependencies**

- L10-14.42-001

**Deliverable**

DR procedure.

**Acceptance Criteria**

Applicable recovery procedures are documented.

### L10-14.42-003 — Validate DR Procedure

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Exercise the applicable recovery procedure.

**Dependencies**

- L10-14.42-002

**Deliverable**

DR validation evidence.

**Acceptance Criteria**

Recovery responsibilities and procedures are demonstrated.

## Definition of Done

Where applicable, DR procedures are documented and validated.

---

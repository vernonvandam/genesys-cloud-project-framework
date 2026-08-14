# Layer 10 — 2.14.26 Identity & Access Operations

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.26 |
| Capability | Identity & Access Operations |
| Task Catalogue ID | 14.26 |
| Primary Layer 1 Phases | P06, P09, P12 |

## Capability Objective

Establish BAU administration of users, roles, authentication and access.

## Implementation Tasks

### L10-14.26-001 — Define Access Administration Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define joiner, mover, leaver, role and access request processes.

**Dependencies**

- Identity architecture
- Security controls

**Deliverable**

Access administration process.

**Acceptance Criteria**

Access lifecycle is documented.

### L10-14.26-002 — Establish Access Review Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define periodic access review and privileged access validation.

**Dependencies**

- L10-14.26-001

**Deliverable**

Access review procedure.

**Acceptance Criteria**

Review frequency, ownership and evidence are defined.

### L10-14.26-003 — Validate Access Operations

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate representative access administration and review scenarios.

**Dependencies**

- L10-14.26-002

**Deliverable**

Access operations validation.

**Acceptance Criteria**

Access processes operate as designed.

## Definition of Done

Identity and access operations are controlled and auditable.

---
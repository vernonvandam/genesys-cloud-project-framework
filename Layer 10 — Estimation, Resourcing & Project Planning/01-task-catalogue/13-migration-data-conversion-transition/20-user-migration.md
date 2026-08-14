# Layer 10 — 2.13.20 User Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.20 |
| Capability | User Migration |
| Task Catalogue ID | 13.20 |
| Primary Layer 1 Phases | P04, P06, P08, P10, P11 |

## Capability Objective

Migrate or provision users, user attributes, groups, roles and associated assignments.

## Source Implementation Activities

1. Identify users.
2. Map user attributes and access.
3. Provision and validate users.

## Implementation Tasks

### L10-13.20-001 — Reconcile User Migration Population

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Reconcile source users against the approved target user population.

**Dependencies**

- Source system inventory
- Identity strategy

**Deliverable**

User migration population.

**Acceptance Criteria**

Migration population is approved.

### L10-13.20-002 — Provision Migrated Users

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Provision users and approved attributes in the target environment.

**Dependencies**

- L10-13.20-001
- Identity configuration

**Deliverable**

Provisioned users.

**Acceptance Criteria**

Required users and attributes exist in target.

### L10-13.20-003 — Validate User Migration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Identity Specialist |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate user access, attributes, roles and authentication.

**Dependencies**

- L10-13.20-002

**Deliverable**

User migration validation report.

**Acceptance Criteria**

Representative users authenticate and receive approved access.

## Definition of Done

Target users are provisioned and validated.

---
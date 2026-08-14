# Layer 10 — 2.13.03 Migration Scope & Assessment

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.03 |
| Capability | Migration Scope & Assessment |
| Task Catalogue ID | 13.03 |
| Primary Layer 1 Phases | P02, P03, P04 |

## Capability Objective

Determine what must be migrated, what will remain, what will be transformed and what will be retired.

## Source Implementation Activities

1. Assess current migration scope.
2. Identify migration boundaries.
3. Identify exclusions.
4. Obtain scope approval.

## Implementation Tasks

### L10-13.03-001 — Assess Migration Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Assess systems, data, configuration and operational processes potentially requiring migration.

**Dependencies**

- Migration strategy
- Source system inventory

**Deliverable**

Migration scope assessment.

**Acceptance Criteria**

Migration candidates are documented.

### L10-13.03-002 — Define Migration Boundaries

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

Define migrated, retained, transformed, archived and retired components.

**Dependencies**

- L10-13.03-001

**Deliverable**

Migration boundary matrix.

**Acceptance Criteria**

Each major migration object has a defined disposition.

### L10-13.03-003 — Approve Migration Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Project Manager |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain customer approval for migration scope and exclusions.

**Dependencies**

- L10-13.03-002

**Deliverable**

Approved migration scope.

**Acceptance Criteria**

Scope and exclusions are formally approved.

## Definition of Done

Migration boundaries and exclusions are documented and approved.

---
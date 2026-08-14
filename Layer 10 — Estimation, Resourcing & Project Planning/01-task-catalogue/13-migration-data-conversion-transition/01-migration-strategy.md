# Layer 10 — 2.13.01 Migration Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.01 |
| Capability | Migration Strategy |
| Task Catalogue ID | 13.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P10, P12 |

## Capability Objective

Define the overall migration strategy, scope, principles, migration waves, ownership, dependencies and success criteria.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish migration ownership |
| P02 | Assess migration landscape |
| P03 | Define migration requirements |
| P04 | Define migration strategy |
| P10 | Confirm production migration approach |
| P12 | Close migration strategy activities |

## Source Implementation Activities

1. Define migration objectives.
2. Assess migration landscape.
3. Define migration strategy and waves.
4. Obtain customer approval.

## Implementation Tasks

### Activity 01 — Define Migration Objectives

#### L10-13.01-001 — Define Migration Objectives

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define the business and technical objectives governing migration.

**Dependencies**

- Project initiation
- Customer migration stakeholders

**Deliverable**

Migration objectives.

**Acceptance Criteria**

Objectives are documented and approved.

### Activity 02 — Define Migration Approach

#### L10-13.01-002 — Define Migration Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define migration waves, sequencing, migration boundaries, dependencies and transition approach.

**Dependencies**

- L10-13.01-001
- Migration scope assessment

**Deliverable**

Migration strategy.

**Acceptance Criteria**

Strategy defines scope, approach, waves, dependencies and success criteria.

### Activity 03 — Approve Migration Strategy

#### L10-13.01-003 — Obtain Migration Strategy Approval

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Present the migration strategy for customer approval.

**Dependencies**

- L10-13.01-002

**Deliverable**

Approved migration strategy.

**Acceptance Criteria**

Customer approval is recorded.

## Capability-Level Dependencies

- Project initiation
- Migration scope
- Source inventory
- Solution architecture

## Capability-Level Estimation Considerations

Effort is influenced by source complexity, number of waves, coexistence requirements and migration scope.

## Definition of Done

The migration strategy is approved and provides an executable basis for subsequent migration planning.

---
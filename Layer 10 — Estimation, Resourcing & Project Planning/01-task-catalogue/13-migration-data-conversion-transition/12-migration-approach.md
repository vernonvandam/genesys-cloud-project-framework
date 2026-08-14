# Layer 10 — 2.13.12 Migration Approach

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.12 |
| Capability | Migration Approach |
| Task Catalogue ID | 13.12 |
| Primary Layer 1 Phases | P03, P04, P10 |

## Capability Objective

Define how migration will be sequenced, executed, validated and transitioned into production.

## Source Implementation Activities

1. Select migration approach.
2. Define migration waves.
3. Define cutover strategy.

## Implementation Tasks

### L10-13.12-001 — Select Migration Approach

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Select big-bang, phased, wave-based, coexistence or hybrid migration approach.

**Dependencies**

- Migration scope
- Migration strategy

**Deliverable**

Migration approach decision.

**Acceptance Criteria**

Approach is documented and justified.

### L10-13.12-002 — Define Migration Waves

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define migration groups, sequencing, dependencies and entry/exit criteria.

**Dependencies**

- L10-13.12-001

**Deliverable**

Migration wave plan.

**Acceptance Criteria**

All migration scope is assigned to an approved wave or disposition.

### L10-13.12-003 — Define Cutover Approach

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define production migration sequence, timing, responsibilities and validation checkpoints.

**Dependencies**

- Migration wave plan
- Migration rehearsal

**Deliverable**

Cutover approach.

**Acceptance Criteria**

Production cutover approach is approved.

## Definition of Done

Migration execution and cutover approach are approved.

---

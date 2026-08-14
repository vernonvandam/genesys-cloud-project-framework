# Layer 10 — 2.13.40 Delta Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.40 |
| Capability | Delta Migration |
| Task Catalogue ID | 13.40 |
| Primary Layer 1 Phases | P06, P10, P11 |
| Classification | CONDITIONAL |

## Capability Objective

Capture and migrate changes occurring between initial migration and production cutover.

## Implementation Tasks

### L10-13.40-001 — Define Delta Capture Approach

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define how post-baseline changes will be identified and captured.

**Dependencies**

- Migration approach

**Deliverable**

Delta migration strategy.

**Acceptance Criteria**

Delta sources, timing and ownership are defined.

### L10-13.40-002 — Execute Delta Migration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P11 |
| Primary Role | Migration Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Extract, transform and load approved delta records.

**Dependencies**

- L10-13.40-001
- Production migration

**Deliverable**

Delta migration results.

**Acceptance Criteria**

Identified deltas are migrated successfully.

### L10-13.40-003 — Validate Delta Reconciliation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Reconcile delta source and target populations.

**Dependencies**

- L10-13.40-002

**Deliverable**

Delta reconciliation report.

**Acceptance Criteria**

Delta reconciliation passes.

## Definition of Done

Required deltas are migrated and reconciled.

---

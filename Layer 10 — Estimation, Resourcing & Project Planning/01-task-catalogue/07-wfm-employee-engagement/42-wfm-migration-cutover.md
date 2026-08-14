# Layer 10 — 2.07.42 WFM Migration & Cutover

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.42 |
| Capability | WFM Migration & Cutover |
| Task Catalogue ID | 07.42 |
| Primary Layer 1 Phases | P02, P07, P08, P10, P11 |

## Capability Objective

Migrate required workforce data and transition from the existing WFM operating model to Genesys Cloud.

## Source Implementation Activities

1. Assess migration scope.
2. Define migration mappings.
3. Prepare migration data.
4. Execute migration.
5. Validate migrated data.
6. Execute cutover.
7. Validate production.

## Implementation Tasks

### Activity 01 — Plan Migration

#### L10-07.42-001 — Assess WFM Migration Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify workforce data and historical information that must be migrated.

**Dependencies**

- Existing WFM assessment

**Deliverable**

Migration scope.

**Acceptance Criteria**

Migration scope is approved.

#### L10-07.42-002 — Define WFM Migration Mapping

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data / Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | SCRIPT |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Map source workforce records to target WFM structures.

**Dependencies**

- L10-07.42-001

**Deliverable**

Migration mapping specification.

**Acceptance Criteria**

Mapping is approved.

### Activity 02 — Execute Migration

#### L10-07.42-003 — Prepare Migration Dataset

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data / Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | SCRIPT |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Extract, cleanse, transform and prepare migration data.

**Dependencies**

- L10-07.42-002

**Deliverable**

Migration-ready dataset.

**Acceptance Criteria**

Dataset passes migration validation rules.

#### L10-07.42-004 — Execute WFM Migration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data / Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | SCRIPT |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Load the approved workforce data into the target WFM solution.

**Dependencies**

- L10-07.42-003

**Deliverable**

Migrated WFM data.

**Acceptance Criteria**

Migration completes without critical errors.

#### L10-07.42-005 — Validate Migrated WFM Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | SCRIPT |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Reconcile migrated records against source data.

**Dependencies**

- L10-07.42-004

**Deliverable**

Migration validation report.

**Acceptance Criteria**

Migration reconciliation meets agreed thresholds.

### Activity 03 — Cutover

#### L10-07.42-006 — Execute WFM Cutover

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Execute the approved transition from the existing WFM platform or process to Genesys Cloud.

**Dependencies**

- UAT acceptance
- Migration validation
- Cutover approval

**Deliverable**

WFM production cutover.

**Acceptance Criteria**

Production WFM is operational.

#### L10-07.42-007 — Validate WFM After Cutover

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate migrated workforce configuration and operational behaviour after production cutover.

**Dependencies**

- L10-07.42-006

**Deliverable**

Post-cutover validation.

**Acceptance Criteria**

Production WFM operates as expected.
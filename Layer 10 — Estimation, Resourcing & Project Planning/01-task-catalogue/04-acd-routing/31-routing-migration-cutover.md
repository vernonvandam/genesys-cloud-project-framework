# Layer 10 — 2.04.31 Routing Migration & Cutover

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.31 |
| Capability | Routing Migration & Cutover |
| Task Catalogue ID | 04.31 |
| Primary Layer 1 Phases | P02, P05, P08, P10, P11, P12 |

## Capability Objective

Migrate existing routing configuration and safely transition production interactions to the target Genesys Cloud routing model.

## Source Implementation Activities

1. Assess existing routing.
2. Define migration scope.
3. Prepare migration data.
4. Recreate target routing.
5. Validate migrated routing.
6. Execute cutover.
7. Validate production.
8. Complete transition.

## Implementation Tasks

### Activity 01 — Migration Planning

#### L10-04.31-001 — Assess Existing Routing Configuration

| Attribute | Value |
|---|---|
| Task Type | MIGRATION |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assess existing queues, skills, routing rules, agent membership, schedules and exception behaviour.

**Dependencies**

- Current-state access

**Deliverable**

Routing migration assessment.

**Acceptance Criteria**

Migration scope is documented.

#### L10-04.31-002 — Define Routing Migration Plan

| Attribute | Value |
|---|---|
| Task Type | MIGRATION |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define migration sequencing, validation, rollback and cutover procedures.

**Dependencies**

- L10-04.31-001

**Deliverable**

Routing migration plan.

**Acceptance Criteria**

Plan is approved.

### Activity 02 — Migration Execution

#### L10-04.31-003 — Prepare Routing Migration Data

| Attribute | Value |
|---|---|
| Task Type | MIGRATION |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Prepare source data required to reproduce routing configuration.

**Dependencies**

- L10-04.31-002

**Deliverable**

Migration data set.

**Acceptance Criteria**

Migration data is complete and validated.

#### L10-04.31-004 — Execute Routing Migration

| Attribute | Value |
|---|---|
| Task Type | MIGRATION |
| Layer 1 Phase | P11 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 0.5h per routing component group |
| Critical Path | YES |

**Description**

Migrate or recreate routing configuration in the target production environment.

**Dependencies**

- L10-04.31-003
- Production readiness

**Deliverable**

Migrated routing configuration.

**Acceptance Criteria**

All agreed routing components are available in production.

#### L10-04.31-005 — Execute Routing Cutover

| Attribute | Value |
|---|---|
| Task Type | MIGRATION |
| Layer 1 Phase | P11 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Execute approved production routing cutover.

**Dependencies**

- L10-04.31-004
- Cutover approval

**Deliverable**

Production routing cutover.

**Acceptance Criteria**

Traffic is successfully transitioned to target routing.

#### L10-04.31-006 — Validate Post-Cutover Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate production routing across critical customer journeys.

**Dependencies**

- L10-04.31-005

**Deliverable**

Post-cutover validation evidence.

**Acceptance Criteria**

Critical routing paths operate correctly.

## Definition of Done

Routing has been migrated, cut over, validated and handed to operations with rollback risks resolved.

---
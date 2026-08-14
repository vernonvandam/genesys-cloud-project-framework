# Layer 10 — 2.06.33 Digital Migration & Cutover

## Capability Objective

Transition digital channels from the existing environment or platform to the target Genesys Cloud solution.

## Implementation Tasks

### L10-06.33-001 — Assess Digital Migration Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify channels, numbers, accounts, configurations, data, integrations and customer-facing dependencies requiring migration.

**Dependencies**

- Digital channel inventory

**Deliverable**

Migration scope.

**Acceptance Criteria**

Migration scope is approved.

### L10-06.33-002 — Develop Digital Cutover Plan

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define cutover sequence, responsibilities, communications, validation and rollback.

**Dependencies**

- L10-06.33-001

**Deliverable**

Digital cutover plan.

**Acceptance Criteria**

Cutover and rollback are approved.

### L10-06.33-003 — Execute Digital Cutover

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Execute the approved digital channel cutover.

**Dependencies**

- L10-06.33-002
- UAT approval
- Production readiness

**Deliverable**

Migrated digital channels.

**Acceptance Criteria**

Production channels operate successfully.

### L10-06.33-004 — Validate Post-Cutover Digital Experience

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate customer entry, routing, agent handling and integrations following cutover.

**Dependencies**

- L10-06.33-003

**Deliverable**

Post-cutover validation.

**Acceptance Criteria**

Critical production journeys pass.

## Definition of Done

Digital channels are successfully migrated or activated with validated production operation.

---

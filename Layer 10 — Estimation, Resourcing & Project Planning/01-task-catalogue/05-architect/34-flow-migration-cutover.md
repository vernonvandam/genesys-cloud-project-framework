# Layer 10 — 2.05.34 Flow Migration & Cutover

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.34 |
| Capability | Flow Migration & Cutover |
| Task Catalogue ID | 05.34 |
| Primary Layer 1 Phases | P07, P08, P09, P10, P11, P12 |

## Capability Objective

Migrate existing Architect flows and supporting configuration into the target environment and execute controlled cutover.

## Source Implementation Activities

1. Inventory source flows.
2. Define migration strategy.
3. Migrate and validate flows.
4. Execute cutover and rollback.

## Implementation Tasks

### Activity 01 — Prepare Flow Migration

#### L10-05.34-001 — Assess Source Flow Inventory

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Inventory source flows, dependencies, prompts, schedules, Data Tables, integrations and versions.

**Dependencies**

- Source system access
- Current-state assessment

**Deliverable**

Flow migration inventory.

**Acceptance Criteria**

All migration dependencies are documented.

---

#### L10-05.34-002 — Execute Flow Migration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Migrate approved flows and supporting configuration into the target environment.

**Dependencies**

- L10-05.34-001
- Target environment readiness

**Deliverable**

Migrated flow set.

**Acceptance Criteria**

Required flows and dependencies are available in the target environment.

---

#### L10-05.34-003 — Execute Flow Cutover

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | PARTIAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Execute the approved Architect flow cutover, validate production behaviour and invoke rollback where required.

**Dependencies**

- Migration validation
- Cutover readiness
- Approved rollback plan

**Deliverable**

Production flow cutover.

**Acceptance Criteria**

Production flows are active and smoke tests pass.
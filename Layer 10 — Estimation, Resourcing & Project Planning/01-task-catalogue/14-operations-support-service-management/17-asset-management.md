# Layer 10 — 2.14.17 Asset Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.17 |
| Capability | Asset Management |
| Task Catalogue ID | 14.17 |
| Primary Layer 1 Phases | P04, P09, P12 |
| Classification | CONDITIONAL |

## Capability Objective

Maintain an operational inventory of Genesys Cloud and supporting service assets.

## Implementation Tasks

### L10-14.17-001 — Determine Asset Management Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Determine which platform, telephony, integration and supporting assets require operational tracking.

**Dependencies**

- Configuration management
- Solution architecture

**Deliverable**

Asset scope.

**Acceptance Criteria**

Asset categories and ownership are agreed.

### L10-14.17-002 — Establish Asset Register

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Create or update the operational asset register.

**Dependencies**

- L10-14.17-001

**Deliverable**

Asset register.

**Acceptance Criteria**

Required assets are recorded with ownership.

### L10-14.17-003 — Validate Asset Register

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Reconcile the asset register against the deployed service.

**Dependencies**

- L10-14.17-002

**Deliverable**

Validated asset register.

**Acceptance Criteria**

Material assets are accounted for.

## Definition of Done

Applicable assets are inventoried, owned and maintained.

---

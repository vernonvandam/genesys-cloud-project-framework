# Layer 10 — 2.08.44 Integration Governance & Lifecycle

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.44 |
| Capability | Integration Governance & Lifecycle |
| Task Catalogue ID | 08.44 |
| Primary Layer 1 Phases | P03, P04, P09, P12 |

## Capability Objective

Establish long-term lifecycle governance for integration design, changes, versioning, ownership and retirement.

## Implementation Tasks

### L10-08.44-001 — Define Integration Lifecycle

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define lifecycle stages from design and build through operation, change and retirement.

**Dependencies**

- Integration governance

**Deliverable**

Integration lifecycle model.

**Acceptance Criteria**

Lifecycle model is approved.

### L10-08.44-002 — Establish Change Governance

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define design review, security review, testing and production approval for integration changes.

**Dependencies**

- L10-08.44-001

**Deliverable**

Integration change governance process.

**Acceptance Criteria**

Change process is approved.

### L10-08.44-003 — Handover Lifecycle Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | YES |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Transfer lifecycle governance responsibilities to BAU owners.

**Dependencies**

- L10-08.44-002

**Deliverable**

Lifecycle ownership register.

**Acceptance Criteria**

BAU owners accept lifecycle responsibilities.
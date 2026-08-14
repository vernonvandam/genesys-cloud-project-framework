# Layer 10 — 2.02.12 Service Accounts & API Identities

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.12 |
| Capability | Service Accounts & API Identities |
| Task Catalogue ID | 02.12 |
| Primary Layer 1 Phases | P03, P04, P05, P07, P08, P09, P12 |

## Capability Objective

Establish controlled non-human identities for integrations, automation and API-based access.

## Source Implementation Activities

1. Identify service identity requirements.
2. Define service identity ownership.
3. Define required permissions.
4. Configure identities.
5. Validate API access.
6. Establish lifecycle and secret-management processes.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.12-001 — Inventory Service Identity Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Identify integrations, automation processes and applications requiring non-human identities.

**Dependencies**

- Integration architecture

**Deliverable**

Service identity inventory.

**Acceptance Criteria**

All known service identity requirements are captured.

#### L10-02.12-002 — Define Service Identity Permissions

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define minimum required permissions and ownership for each service identity.

**Dependencies**

- L10-02.12-001

**Deliverable**

Service identity access matrix.

**Acceptance Criteria**

Permissions are approved.

### Activity 02 — Configure

#### L10-02.12-003 — Create Service Identities

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Create approved service identities and configure required access.

**Dependencies**

- L10-02.12-002

**Deliverable**

Configured service identities.

**Acceptance Criteria**

Identities exist with approved permissions.

#### L10-02.12-004 — Configure Service Identity Lifecycle

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define ownership, credential rotation, access review and retirement processes.

**Dependencies**

- L10-02.12-003

**Deliverable**

Service identity lifecycle procedure.

**Acceptance Criteria**

Lifecycle ownership is documented.

### Activity 03 — Validate

#### L10-02.12-005 — Validate API Identity Access

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate successful API operations and confirm prohibited operations fail.

**Dependencies**

- L10-02.12-003

**Deliverable**

API identity test evidence.

**Acceptance Criteria**

Access is limited to approved operations.
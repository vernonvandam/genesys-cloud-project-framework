# Layer 10 — 2.02.20 Integration Identities & Secrets

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.20 |
| Capability | Integration Identities & Secrets |
| Task Catalogue ID | 02.20 |
| Primary Layer 1 Phases | P03, P04, P05, P07, P08, P09, P10, P12 |

## Capability Objective

Secure the identities, credentials, secrets and authentication material used by Genesys Cloud integrations.

## Source Implementation Activities

1. Identify integration identities and secrets.
2. Define ownership and storage requirements.
3. Configure secure credential storage.
4. Configure integration authentication.
5. Validate credential use.
6. Establish rotation and retirement processes.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.20-001 — Inventory Integration Identities and Secrets

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

Inventory service accounts, OAuth clients, API credentials, certificates and other authentication material required by integrations.

**Dependencies**

- Integration architecture

**Deliverable**

Integration identity and secret register.

**Acceptance Criteria**

Known authentication dependencies are captured.

#### L10-02.20-002 — Define Secret Management Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define approved storage, access, rotation, exposure and retirement requirements.

**Dependencies**

- L10-02.20-001

**Deliverable**

Secret management design.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Configure

#### L10-02.20-003 — Configure Secure Secret Storage

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Security Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure approved secret storage and access controls.

**Dependencies**

- L10-02.20-002

**Deliverable**

Secure secret storage.

**Acceptance Criteria**

Secrets are protected according to customer security requirements.

#### L10-02.20-004 — Configure Integration Authentication

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure integrations to use approved identities and secret-management mechanisms.

**Dependencies**

- L10-02.20-003

**Deliverable**

Configured integration authentication.

**Acceptance Criteria**

Integrations authenticate successfully without exposing credentials.

### Activity 03 — Validate and Operationalise

#### L10-02.20-005 — Validate Integration Credential Security

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate credential storage, access restrictions and integration authentication behaviour.

**Dependencies**

- L10-02.20-004

**Deliverable**

Credential security validation evidence.

**Acceptance Criteria**

No unauthorised credential exposure is identified.

#### L10-02.20-006 — Establish Credential Rotation Process

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Security Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define credential rotation, compromise response and retirement procedures.

**Dependencies**

- L10-02.20-005

**Deliverable**

Credential lifecycle procedure.

**Acceptance Criteria**

BAU ownership and rotation process are documented.
# Layer 10 — 2.02.04 SSO & Identity Federation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.04 |
| Capability | SSO & Identity Federation |
| Task Catalogue ID | 02.04 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08, P10, P11 |

## Capability Objective

Design, configure and validate federated authentication and single sign-on for Genesys Cloud where required.

## Source Implementation Activities

1. Assess enterprise federation architecture.
2. Confirm SSO requirements.
3. Define federation design.
4. Configure federation.
5. Test authentication and logout.
6. Validate production SSO.

## Implementation Tasks

### Activity 01 — Design Federation

#### L10-02.04-001 — Assess Enterprise Identity Provider

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | IAM Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Assess the customer identity provider, federation protocols, certificates and authentication policies.

**Dependencies**

- L10-02.01-003

**Deliverable**

Identity provider assessment.

**Acceptance Criteria**

Identity provider requirements and constraints are documented.

#### L10-02.04-002 — Define SSO Configuration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | IAM Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define the SSO configuration, claims, certificates, redirect behaviour and logout requirements.

**Dependencies**

- L10-02.04-001

**Deliverable**

SSO design.

**Acceptance Criteria**

SSO design is approved.

### Activity 02 — Configure

#### L10-02.04-003 — Configure SSO Federation

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the approved federation settings in Genesys Cloud and the customer identity provider.

**Dependencies**

- L10-02.04-002

**Deliverable**

Configured SSO.

**Acceptance Criteria**

Federated authentication is available for test users.

### Activity 03 — Test

#### L10-02.04-004 — Test SSO Authentication

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Test successful login, failed login, logout, session expiry and relevant authentication edge cases.

**Dependencies**

- L10-02.04-003

**Deliverable**

SSO test evidence.

**Acceptance Criteria**

All approved authentication scenarios pass.

#### L10-02.04-005 — Validate Production SSO

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P10 |
| Primary Role | IAM Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate production federation configuration before go-live.

**Dependencies**

- L10-02.04-004

**Deliverable**

Production SSO validation.

**Acceptance Criteria**

Production authentication succeeds and emergency access remains available.
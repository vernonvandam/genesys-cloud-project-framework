# Layer 10 — 2.02.05 Authentication & MFA

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.05 |
| Capability | Authentication & MFA |
| Task Catalogue ID | 02.05 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P10 |

## Capability Objective

Define and implement the approved authentication and multi-factor authentication controls for Genesys Cloud users and administrators.

## Source Implementation Activities

1. Define authentication requirements.
2. Assess MFA requirements.
3. Design authentication policy.
4. Configure authentication controls.
5. Test authentication scenarios.
6. Validate production authentication.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-02.05-001 — Define Authentication Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Document authentication requirements for standard users, administrators and privileged users.

**Dependencies**

- L10-02.01-002

**Deliverable**

Authentication requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-02.05-002 — Define MFA Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define MFA requirements, exceptions and recovery procedures.

**Dependencies**

- L10-02.05-001

**Deliverable**

MFA policy requirements.

**Acceptance Criteria**

MFA requirements are approved.

### Activity 02 — Configure

#### L10-02.05-003 — Configure Authentication Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure authentication and MFA controls according to the approved policy.

**Dependencies**

- L10-02.05-002

**Deliverable**

Configured authentication controls.

**Acceptance Criteria**

Controls enforce the approved policy.

### Activity 03 — Validate

#### L10-02.05-004 — Test Authentication and MFA

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

Test authentication, MFA, failed authentication, recovery and relevant exception scenarios.

**Dependencies**

- L10-02.05-003

**Deliverable**

Authentication test evidence.

**Acceptance Criteria**

All approved authentication scenarios pass.

#### L10-02.05-005 — Validate Production Authentication

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P10 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate production authentication and MFA before go-live.

**Dependencies**

- L10-02.05-004

**Deliverable**

Production authentication validation.

**Acceptance Criteria**

Authentication is secure, functional and operationally supported.
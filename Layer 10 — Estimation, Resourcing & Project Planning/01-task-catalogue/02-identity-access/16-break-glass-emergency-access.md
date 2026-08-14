# Layer 10 — 2.02.16 Break-Glass & Emergency Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.16 |
| Capability | Break-Glass & Emergency Access |
| Task Catalogue ID | 02.16 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09, P10, P12 |

## Capability Objective

Establish controlled emergency administrative access that can be used when normal identity or federation mechanisms are unavailable.

## Source Implementation Activities

1. Determine emergency access requirements.
2. Define break-glass controls.
3. Establish emergency credentials.
4. Secure emergency credentials.
5. Test emergency access.
6. Define monitoring and review.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.16-001 — Define Emergency Access Requirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Determine circumstances requiring emergency administrative access.

**Dependencies**

- Authentication architecture

**Deliverable**

Emergency access requirement.

**Acceptance Criteria**

Requirement is approved.

#### L10-02.16-002 — Design Break-Glass Procedure

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

Define emergency access ownership, approval, credential protection, usage and post-use review.

**Dependencies**

- L10-02.16-001

**Deliverable**

Break-glass procedure.

**Acceptance Criteria**

Procedure is approved.

### Activity 02 — Establish

#### L10-02.16-003 — Establish Emergency Access

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Establish emergency access according to the approved procedure.

**Dependencies**

- L10-02.16-002

**Deliverable**

Emergency access mechanism.

**Acceptance Criteria**

Emergency access is available only to authorised personnel.

#### L10-02.16-004 — Secure Emergency Credentials

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Security Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Secure emergency credentials using approved customer security controls.

**Dependencies**

- L10-02.16-003

**Deliverable**

Secured emergency credentials.

**Acceptance Criteria**

Credentials are protected and access is controlled.

### Activity 03 — Validate

#### L10-02.16-005 — Test Break-Glass Access

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

Test emergency access and verify the process can restore administrative control.

**Dependencies**

- L10-02.16-004

**Deliverable**

Break-glass test evidence.

**Acceptance Criteria**

Emergency access successfully operates and usage is traceable.
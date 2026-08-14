# Layer 10 — 2.02.14 Security & Authentication Policies

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.14 |
| Capability | Security & Authentication Policies |
| Task Catalogue ID | 02.14 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P10, P12 |

## Capability Objective

Translate customer security requirements into enforceable Genesys Cloud authentication and access policies.

## Source Implementation Activities

1. Assess customer security standards.
2. Define authentication policies.
3. Define exception handling.
4. Configure security policies.
5. Validate enforcement.
6. Document policy ownership.

## Implementation Tasks

### Activity 01 — Define Policies

#### L10-02.14-001 — Assess Customer Security Standards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Assess customer security standards relevant to authentication and access.

**Dependencies**

- Security requirements

**Deliverable**

Security policy assessment.

**Acceptance Criteria**

Applicable security standards are documented.

#### L10-02.14-002 — Define Authentication Policy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Translate security requirements into Genesys Cloud authentication policy requirements.

**Dependencies**

- L10-02.14-001
- L10-02.05-002

**Deliverable**

Authentication policy.

**Acceptance Criteria**

Policy is approved.

### Activity 02 — Configure and Validate

#### L10-02.14-003 — Configure Security Policies

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

Configure applicable security and authentication policies.

**Dependencies**

- L10-02.14-002

**Deliverable**

Configured policies.

**Acceptance Criteria**

Policies reflect the approved design.

#### L10-02.14-004 — Test Policy Enforcement

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Test policy enforcement, exceptions and expected failure conditions.

**Dependencies**

- L10-02.14-003

**Deliverable**

Policy validation evidence.

**Acceptance Criteria**

Security policies enforce expected behaviour.

#### L10-02.14-005 — Document Policy Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document policy ownership, review requirements and operational responsibilities.

**Dependencies**

- L10-02.14-004

**Deliverable**

Security policy operating record.

**Acceptance Criteria**

BAU ownership is accepted.
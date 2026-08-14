# Layer 10 — 2.02.19 Environment Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.19 |
| Capability | Environment Access |
| Task Catalogue ID | 02.19 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P10, P12 |

## Capability Objective

Define and implement controlled access to development, test, UAT and production environments.

## Source Implementation Activities

1. Identify environments.
2. Define environment access model.
3. Map user populations to environments.
4. Configure access.
5. Validate environment segregation.
6. Document access governance.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.19-001 — Identify Environment Access Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify environments and the user populations requiring access to each.

**Dependencies**

- Environment strategy

**Deliverable**

Environment access requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-02.19-002 — Define Environment Access Matrix

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

Define access by persona, environment and administrative function.

**Dependencies**

- L10-02.19-001
- Role and permission model

**Deliverable**

Environment access matrix.

**Acceptance Criteria**

Matrix is approved.

### Activity 02 — Configure

#### L10-02.19-003 — Configure Environment Access

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure environment access according to the approved matrix.

**Dependencies**

- L10-02.19-002

**Deliverable**

Environment access configuration.

**Acceptance Criteria**

Access matches the approved model.

### Activity 03 — Validate

#### L10-02.19-004 — Test Environment Segregation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that users can access only approved environments and that production access is restricted.

**Dependencies**

- L10-02.19-003

**Deliverable**

Environment access test evidence.

**Acceptance Criteria**

Environment boundaries pass testing.

#### L10-02.19-005 — Approve Production Access

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm that production access is limited to approved users and roles.

**Dependencies**

- L10-02.19-004

**Deliverable**

Production access approval.

**Acceptance Criteria**

Production access is approved by the customer.
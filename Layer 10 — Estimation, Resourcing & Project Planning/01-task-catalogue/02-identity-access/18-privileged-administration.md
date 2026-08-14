# Layer 10 — 2.02.18 Privileged Administration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.18 |
| Capability | Privileged Administration |
| Task Catalogue ID | 02.18 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P12 |

## Capability Objective

Establish a controlled privileged-administration model that minimises excessive administrative access and supports separation of duties.

## Source Implementation Activities

1. Identify privileged roles.
2. Define privileged access model.
3. Configure privileged roles.
4. Separate administrative and operational access.
5. Validate privileged access.
6. Establish ongoing review.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.18-001 — Identify Privileged Personas

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

Identify users and roles requiring elevated administrative privileges.

**Dependencies**

- Role and permission matrix

**Deliverable**

Privileged persona catalogue.

**Acceptance Criteria**

Privileged populations are identified.

#### L10-02.18-002 — Define Privileged Access Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define privileged roles, approvals, segregation, monitoring and review.

**Dependencies**

- L10-02.18-001

**Deliverable**

Privileged access design.

**Acceptance Criteria**

Privileged model is approved.

### Activity 02 — Configure

#### L10-02.18-003 — Configure Privileged Roles

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure privileged role assignments according to the approved model.

**Dependencies**

- L10-02.18-002

**Deliverable**

Privileged role configuration.

**Acceptance Criteria**

Privileged access matches the approved model.

### Activity 03 — Validate

#### L10-02.18-004 — Validate Privileged Access

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

Validate privileged and non-privileged personas against expected permissions.

**Dependencies**

- L10-02.18-003

**Deliverable**

Privileged access test evidence.

**Acceptance Criteria**

Privileged access is restricted to approved users and actions.

#### L10-02.18-005 — Establish Privileged Access Review

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Establish recurring review of privileged access.

**Dependencies**

- L10-02.18-004

**Deliverable**

Privileged access review process.

**Acceptance Criteria**

BAU review ownership is documented.
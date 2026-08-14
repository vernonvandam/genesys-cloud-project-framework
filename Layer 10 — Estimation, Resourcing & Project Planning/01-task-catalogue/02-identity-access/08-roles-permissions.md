# Layer 10 — 2.02.08 Roles & Permissions

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.08 |
| Capability | Roles & Permissions |
| Task Catalogue ID | 02.08 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10, P12 |

## Capability Objective

Define and implement the Genesys Cloud role and permission model using least privilege and separation of duties.

## Source Implementation Activities

1. Identify user personas.
2. Define role model.
3. Map permissions.
4. Configure roles.
5. Assign roles.
6. Validate access.
7. Document the permission model.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.08-001 — Identify User Personas

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Identify operational, supervisory, administrative, technical and integration personas.

**Dependencies**

- L10-02.01-004

**Deliverable**

User persona catalogue.

**Acceptance Criteria**

Required personas are documented.

#### L10-02.08-002 — Define Role and Permission Matrix

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map personas to Genesys Cloud roles and permissions using least privilege.

**Dependencies**

- L10-02.08-001

**Deliverable**

Role and permission matrix.

**Acceptance Criteria**

Matrix is reviewed and approved.

### Activity 02 — Configure

#### L10-02.08-003 — Configure Roles and Permissions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure the approved roles and permissions.

**Dependencies**

- L10-02.08-002

**Deliverable**

Configured role model.

**Acceptance Criteria**

Configured roles match the approved matrix.

#### L10-02.08-004 — Assign Roles to User Groups

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

Assign roles through the approved user/group model.

**Dependencies**

- L10-02.08-003
- L10-02.07-003

**Deliverable**

Role assignments.

**Acceptance Criteria**

User access matches the approved role matrix.

### Activity 03 — Validate

#### L10-02.08-005 — Validate Least Privilege

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | YES |

**Description**

Test representative personas to confirm permitted and prohibited actions.

**Dependencies**

- L10-02.08-004

**Deliverable**

Role validation evidence.

**Acceptance Criteria**

Access conforms to least-privilege requirements.

#### L10-02.08-006 — Approve Production Permission Model

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

Obtain final approval for production role and permission assignments.

**Dependencies**

- L10-02.08-005

**Deliverable**

Production access approval.

**Acceptance Criteria**

Customer security and platform owners approve the production model.
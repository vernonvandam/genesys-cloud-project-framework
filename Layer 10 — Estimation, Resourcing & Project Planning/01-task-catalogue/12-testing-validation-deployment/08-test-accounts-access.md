# Layer 10 — 2.12.08 Test Accounts & Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.08 — Test Accounts & Access |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.08 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P05–P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Provide the user identities, roles, permissions, test personas and access required to execute planned testing.

## Source Implementation Activities

- Identify test personas.
- Create or provision test accounts.
- Assign required roles and permissions.
- Validate access.
- Maintain access throughout testing.

## Implementation Tasks

### Activity 01 — Define Test Personas

#### L10-12.08-001 — Define Test User Personas

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify user personas required to validate different security and functional paths.

**Dependencies**

Requirements and security design.

**Deliverable**

Test Persona Matrix.

**Acceptance Criteria**

All required test personas are documented.

### Activity 02 — Provision Accounts

#### L10-12.08-002 — Create Test Accounts

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05–P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Provision required test users and accounts.

**Dependencies**

L10-12.08-001 and Identity & Access configuration.

**Deliverable**

Test Accounts.

**Acceptance Criteria**

All required test identities exist.

### Activity 03 — Assign Access

#### L10-12.08-003 — Configure Test User Permissions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assign roles, permissions, divisions and access required for testing.

**Dependencies**

L10-12.08-002.

**Deliverable**

Configured Test Access.

**Acceptance Criteria**

Test users can execute assigned test scenarios without excessive privilege.

### Activity 04 — Validate Access

#### L10-12.08-004 — Validate Test Account Access

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate positive and negative access scenarios.

**Dependencies**

L10-12.08-003.

**Deliverable**

Access Validation Results.

**Acceptance Criteria**

Required access works and prohibited access is blocked.

## Capability-Level Dependencies

- Identity & Access
- Security
- Test Data
- Test Strategy

## Capability-Level Estimation Considerations

Number of personas, users, roles, divisions and authentication mechanisms drive effort.

## Definition of Done

Required test accounts exist and access has been validated.

---
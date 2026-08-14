# Layer 10 — 2.02.21 Identity & Access Validation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.21 |
| Capability | Identity & Access Validation |
| Task Catalogue ID | 02.21 |
| Primary Layer 1 Phases | P08, P09, P10, P11, P12 |

## Capability Objective

Provide end-to-end validation that the implemented Genesys Cloud identity and access model operates securely and according to approved requirements.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P08 | Execute identity and access testing |
| P09 | Validate operational processes |
| P10 | Confirm production readiness |
| P11 | Validate access after cutover |
| P12 | Complete final identity handover |

## Source Implementation Activities

1. Establish identity validation scope.
2. Validate authentication.
3. Validate authorisation.
4. Validate provisioning and deprovisioning.
5. Validate privileged access.
6. Validate integration identities.
7. Validate emergency access.
8. Validate production access.
9. Complete operational handover.

## Implementation Tasks

### Activity 01 — Establish Validation

#### L10-02.21-001 — Define Identity Validation Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define the identity validation scope covering authentication, authorisation, lifecycle, privileged access, integrations and emergency access.

**Dependencies**

- Identity capabilities configured

**Deliverable**

Identity validation plan.

**Acceptance Criteria**

Validation scope is approved.

### Activity 02 — Validate Authentication and Authorisation

#### L10-02.21-002 — Validate Authentication

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

Validate SSO, authentication, MFA, session and recovery scenarios.

**Dependencies**

- Authentication configuration

**Deliverable**

Authentication validation evidence.

**Acceptance Criteria**

All required authentication scenarios pass.

#### L10-02.21-003 — Validate Authorisation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate roles, permissions, groups and division-based access using representative personas.

**Dependencies**

- Roles and permissions
- Groups
- Division access

**Deliverable**

Authorisation validation evidence.

**Acceptance Criteria**

Approved users can perform required actions and prohibited actions are denied.

### Activity 03 — Validate Lifecycle and Integration Access

#### L10-02.21-004 — Validate Provisioning and Deprovisioning

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | YES |

**Description**

Validate user creation, change, suspension and removal processes.

**Dependencies**

- Provisioning configuration
- Lifecycle management

**Deliverable**

Lifecycle validation evidence.

**Acceptance Criteria**

Lifecycle scenarios pass without unauthorised access remaining.

#### L10-02.21-005 — Validate Integration Identities

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate OAuth clients, service identities and integration credentials against approved scopes.

**Dependencies**

- Service identity configuration
- OAuth configuration

**Deliverable**

Integration identity validation evidence.

**Acceptance Criteria**

Integration identities can perform approved operations and cannot perform prohibited operations.

### Activity 04 — Validate Security Controls

#### L10-02.21-006 — Validate Privileged Access

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

Validate privileged access, administrative segregation and least-privilege controls.

**Dependencies**

- Privileged administration

**Deliverable**

Privileged access validation evidence.

**Acceptance Criteria**

Privileged access meets the approved security model.

#### L10-02.21-007 — Validate Break-Glass Access

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate that emergency administrative access is available and appropriately controlled.

**Dependencies**

- Break-glass configuration

**Deliverable**

Emergency access validation evidence.

**Acceptance Criteria**

Emergency access operates and activity can be traced.

### Activity 05 — Production Readiness

#### L10-02.21-008 — Conduct Identity Production Readiness Review

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review identity configuration, outstanding defects, access approvals, operational procedures and security controls before production deployment.

**Dependencies**

- L10-02.21-002
- L10-02.21-003
- L10-02.21-004
- L10-02.21-006
- L10-02.21-007

**Deliverable**

Identity production readiness assessment.

**Acceptance Criteria**

All critical identity risks are resolved or formally accepted.

### Activity 06 — Post-Cutover Validation

#### L10-02.21-009 — Validate Production Identity Access

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate production authentication, authorisation, provisioning and privileged access following cutover.

**Dependencies**

- Production deployment

**Deliverable**

Production identity validation evidence.

**Acceptance Criteria**

Production identity services operate as designed.

### Activity 07 — Handover

#### L10-02.21-010 — Complete Identity and Access Handover

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Transfer identity administration, governance, access review, emergency access and operational procedures to the customer BAU organisation.

**Dependencies**

- L10-02.21-009

**Deliverable**

Identity and access handover package.

**Acceptance Criteria**

Customer confirms operational ownership and accepts the identity documentation.

## Capability-Level Dependencies

- Genesys Cloud organisation
- Identity architecture
- Authentication and MFA
- SSO
- Groups
- Roles and permissions
- Divisions
- User lifecycle
- Provisioning
- API identities
- OAuth clients
- Privileged access
- Emergency access
- Security policies

## Capability-Level Estimation Considerations

Effort is influenced by:

- number of user populations
- number of roles
- number of divisions
- SSO complexity
- SCIM complexity
- integration count
- security requirements
- testing depth
- customer approval cycles
- production cutover requirements
- regulatory requirements

## Definition of Done

Identity & Access validation is complete when:

- authentication testing has passed
- MFA testing has passed
- SSO testing has passed where applicable
- authorisation testing has passed
- role and permission testing has passed
- division access testing has passed
- provisioning testing has passed
- deprovisioning testing has passed
- integration identity testing has passed
- privileged access testing has passed
- emergency access has been validated where required
- production readiness has been approved
- post-cutover validation has passed
- operational handover is complete
- customer acceptance has been obtained
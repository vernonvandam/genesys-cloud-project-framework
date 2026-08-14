# Layer 10 — 2.02.03 User Provisioning & Deprovisioning

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.03 |
| Capability | User Provisioning & Deprovisioning |
| Task Catalogue ID | 02.03 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10 |

## Capability Objective

Implement controlled user provisioning and deprovisioning processes that establish and remove Genesys Cloud access in accordance with approved identity governance.

## Source Implementation Activities

1. Define provisioning requirements.
2. Define account attributes and mappings.
3. Configure provisioning.
4. Configure deprovisioning.
5. Test account creation and removal.
6. Validate access revocation.

## Implementation Tasks

### Activity 01 — Define Provisioning

#### L10-02.03-001 — Define Provisioning Requirements

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

Define required user attributes, account states, ownership and provisioning triggers.

**Dependencies**

- L10-02.02-002

**Deliverable**

Provisioning requirements.

**Acceptance Criteria**

Provisioning requirements are approved.

#### L10-02.03-002 — Define Provisioning Attribute Mapping

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | IAM Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Map authoritative identity attributes to Genesys Cloud user attributes and access decisions.

**Dependencies**

- L10-02.03-001

**Deliverable**

Attribute mapping specification.

**Acceptance Criteria**

Required mappings are approved.

### Activity 02 — Configure

#### L10-02.03-003 — Configure User Provisioning

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

Configure the approved user provisioning mechanism.

**Dependencies**

- L10-02.03-002

**Deliverable**

Configured provisioning.

**Acceptance Criteria**

Users can be provisioned according to the approved model.

#### L10-02.03-004 — Configure Deprovisioning

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Configure the process for suspending or removing user access when users leave or lose eligibility.

**Dependencies**

- L10-02.03-003

**Deliverable**

Deprovisioning process.

**Acceptance Criteria**

Access is removed or suspended according to approved policy.

### Activity 03 — Validate

#### L10-02.03-005 — Test Provisioning and Deprovisioning

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

Test account creation, changes, suspension and removal.

**Dependencies**

- L10-02.03-004

**Deliverable**

Provisioning test evidence.

**Acceptance Criteria**

All required lifecycle access scenarios pass.

#### L10-02.03-006 — Validate Access Revocation

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

Validate that terminated or suspended identities cannot access protected resources.

**Dependencies**

- L10-02.03-005

**Deliverable**

Access revocation evidence.

**Acceptance Criteria**

Revocation is proven and accepted.
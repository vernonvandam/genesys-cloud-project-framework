# Layer 10 — 2.02.06 SCIM & Automated Provisioning

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.06 |
| Capability | SCIM & Automated Provisioning |
| Task Catalogue ID | 02.06 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P07, P08, P10 |

## Capability Objective

Implement automated identity provisioning through SCIM where the customer architecture and Genesys Cloud capabilities support the requirement.

## Source Implementation Activities

1. Confirm SCIM applicability.
2. Assess identity-provider integration.
3. Define attribute mappings.
4. Configure SCIM.
5. Test provisioning and deprovisioning.
6. Validate operational behaviour.

## Implementation Tasks

### Activity 01 — Assess

#### L10-02.06-001 — Confirm SCIM Applicability

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | IAM Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | CONDITIONAL |

**Description**

Confirm whether SCIM is required and appropriate for the customer provisioning architecture.

**Dependencies**

- L10-02.03-001

**Deliverable**

SCIM applicability decision.

**Acceptance Criteria**

SCIM decision is documented.

#### L10-02.06-002 — Assess SCIM Integration Requirements

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

Assess identity provider capabilities, endpoints, credentials, attributes and lifecycle operations.

**Dependencies**

- L10-02.06-001

**Deliverable**

SCIM integration assessment.

**Acceptance Criteria**

Integration requirements are documented.

### Activity 02 — Configure

#### L10-02.06-003 — Define SCIM Attribute Mapping

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

Define mappings between authoritative identity attributes and Genesys Cloud user properties.

**Dependencies**

- L10-02.06-002

**Deliverable**

SCIM mapping specification.

**Acceptance Criteria**

Mappings are approved.

#### L10-02.06-004 — Configure SCIM Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.5h |
| Critical Path | YES |

**Description**

Configure the SCIM integration and required credentials.

**Dependencies**

- L10-02.06-003

**Deliverable**

Configured SCIM integration.

**Acceptance Criteria**

SCIM connectivity is established.

### Activity 03 — Validate

#### L10-02.06-005 — Test SCIM Lifecycle Operations

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

Test create, update, disable and delete operations and associated access changes.

**Dependencies**

- L10-02.06-004

**Deliverable**

SCIM test evidence.

**Acceptance Criteria**

Required lifecycle operations pass.

#### L10-02.06-006 — Validate SCIM Production Operation

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

Validate production SCIM operation and operational ownership.

**Dependencies**

- L10-02.06-005

**Deliverable**

SCIM production validation.

**Acceptance Criteria**

Production provisioning is controlled and operationally supported.
# Layer 10 — 02.02 Identity & Access Task Catalogue

## Task Catalogue Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability Domain | 2.02 — Identity & Access |
| Workstream | Identity & Access |
| Status | Baseline Implementation Task Catalogue |

## Purpose

This directory contains the Layer 10 implementation task catalogue for the Genesys Cloud Identity & Access capability domain.

The capability catalogue in Layer 2 defines what must be implemented.

This Layer 10 catalogue decomposes those capabilities into individual implementation tasks suitable for:

- project schedules
- statements of work
- effort estimation
- resource planning
- dependency modelling
- delivery tracking
- customer responsibility assignment
- implementation runbooks
- acceptance criteria
- spreadsheet-based project planning

## Directory Structure

```text
02-identity-access/
│
├── README.md
├── 01-identity-architecture-governance.md
├── 02-user-lifecycle-management.md
├── 03-user-provisioning-deprovisioning.md
├── 04-sso-identity-federation.md
├── 05-authentication-mfa.md
├── 06-scim-automated-provisioning.md
├── 07-groups.md
├── 08-roles-permissions.md
├── 09-division-based-access.md
├── 10-licensing-assignment.md
├── 11-external-guest-access.md
├── 12-service-accounts-api-identities.md
├── 13-oauth-clients-credentials.md
├── 14-security-authentication-policies.md
├── 15-audit-administrative-traceability.md
├── 16-break-glass-emergency-access.md
├── 17-access-reviews-recertification.md
├── 18-privileged-administration.md
├── 19-environment-access.md
└── 20-integration-identities-secrets.md
└── 21-identity-access-validation.md
```

## Capability Catalogue

| Capability ID | Capability | Classification |
|---|---|---|
| 2.02.01 | Identity Architecture & Governance | Required |
| 2.02.02 | User Lifecycle Management | Required |
| 2.02.03 | User Provisioning & Deprovisioning | Required |
| 2.02.04 | SSO & Identity Federation | Conditional |
| 2.02.05 | Authentication & MFA | Required |
| 2.02.06 | SCIM & Automated Provisioning | Conditional |
| 2.02.07 | Groups | Required |
| 2.02.08 | Roles & Permissions | Required |
| 2.02.09 | Division-Based Access | Required |
| 2.02.10 | Licensing Assignment | Required |
| 2.02.11 | External / Guest Access | Conditional |
| 2.02.12 | Service Accounts & API Identities | Conditional |
| 2.02.13 | OAuth Clients & Credentials | Conditional |
| 2.02.14 | Security & Authentication Policies | Required |
| 2.02.15 | Audit & Administrative Traceability | Required |
| 2.02.16 | Break-Glass & Emergency Access | Conditional |
| 2.02.17 | Access Reviews & Recertification | Required |
| 2.02.18 | Privileged Administration | Required |
| 2.02.19 | Environment Access | Required |
| 2.02.20 | Integration Identities & Secrets | Conditional |
| 2.02.21 | Identity & Access Validation | Required |

## Layer 1 Mapping

Identity & Access activities span the following Layer 1 phases:

| Phase | Application |
|---|---|
| P01 | Identify identity owners, stakeholders and governance |
| P02 | Assess current IAM architecture and identity state |
| P03 | Define identity, authentication and authorisation requirements |
| P04 | Design target identity and access architecture |
| P05 | Establish foundational identity controls |
| P06 | Configure users, groups, roles and access |
| P07 | Configure identity integrations and provisioning |
| P08 | Test authentication, authorisation and lifecycle processes |
| P09 | Establish operational identity-management processes |
| P10 | Validate production access and deployment readiness |
| P11 | Monitor and resolve identity issues during hypercare |
| P12 | Complete BAU identity handover |

## Task ID Convention

```text
L10-02.<Capability Number>-<Task Number>
```

Example:

```text
L10-02.01-001
```

Where:

- `L10` = Layer 10
- `02` = Identity & Access domain
- `01` = capability number
- `001` = sequential task number

## Standard Task Attributes

Every task should contain:

| Attribute | Requirement |
|---|---|
| Task ID | Unique identifier |
| Task Type | REQUIRED / CONDITIONAL / OPTIONAL / VALIDATION |
| Layer 1 Phase | Primary Layer 1 phase |
| Primary Role | Delivery owner |
| Customer Responsibility | YES / NO / JOINT |
| Environment | DESIGN / DEV / TEST / UAT / PROD / MULTI |
| Automation | MANUAL / PARTIAL / AUTOMATED |
| Baseline Effort | Initial effort estimate |
| Critical Path | YES / NO / CONDITIONAL |
| Description | Implementation detail |
| Dependencies | Predecessor tasks |
| Deliverable | Task output |
| Acceptance Criteria | Completion condition |

## Estimation Principles

Baseline effort is indicative and must be calibrated against:

- customer IAM maturity
- existing identity provider
- SSO complexity
- SCIM availability
- number of users
- number of user populations
- number of divisions
- number of roles
- number of permission combinations
- licensing complexity
- number of environments
- integration requirements
- security requirements
- regulatory requirements
- customer approval cycles
- testing requirements
- migration requirements
- automation requirements

## Dependency Principles

Identity & Access should be treated as a foundational workstream.

The following generally precede detailed identity configuration:

- project initiation
- organisation strategy
- region/data residency decision
- customer IAM architecture
- security requirements
- division strategy
- environment strategy

The following generally depend upon Identity & Access:

- ACD configuration
- Architect administration
- Digital administration
- WEM administration
- Quality Management
- analytics access
- integrations
- production operations

## Definition of Done

The Identity & Access task catalogue is considered complete when:

- all applicable capabilities have been assessed
- required capabilities are implemented
- conditional capabilities have been assessed and dispositioned
- user lifecycle is documented
- authentication is configured
- SSO is configured where required
- MFA requirements are implemented
- provisioning and deprovisioning are validated
- groups are configured
- roles and permissions are approved
- divisions are aligned to the access model
- licensing is mapped
- API identities are governed
- OAuth clients are controlled
- privileged access is controlled
- emergency access is established where required
- auditability is validated
- access reviews are operationalised
- environment access is controlled
- identity validation is complete
- customer acceptance is obtained
- BAU ownership is documented

## Domain Gate

```text
IDENTITY ARCHITECTURE APPROVED
          ↓
AUTHENTICATION MODEL APPROVED
          ↓
AUTHORISATION MODEL APPROVED
          ↓
PROVISIONING / DEPROVISIONING VALIDATED
          ↓
PRIVILEGED ACCESS CONTROLLED
          ↓
IDENTITY TESTING PASSED
          ↓
CUSTOMER ACCEPTANCE
          ↓
IDENTITY & ACCESS READY
```
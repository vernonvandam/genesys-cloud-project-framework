# Layer 10 — 11 Security, Compliance & Governance Task Catalogue

## Purpose

This directory contains the task-decomposed implementation catalogue for the Layer 2 Security, Compliance & Governance capability domain.

The catalogue translates the Layer 2 capabilities into atomic implementation tasks that can be used for:

- project planning
- effort estimation
- resource planning
- dependency modelling
- project scheduling
- customer responsibility assignment
- implementation tracking
- acceptance management
- spreadsheet generation

## Capability Domain

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Layer 2 Domain | 11 — Security, Compliance & Governance |
| Capability Count | 47 |
| Task Catalogue Prefix | L10-11 |
| Status | Baseline Task Catalogue |

## Repository Structure

```text
11-security-compliance-governance/
│
├── README.md
├── 01-security-strategy.md
├── 02-security-requirements.md
├── 03-security-architecture.md
├── 04-security-governance.md
├── 05-identity-security.md
├── 06-authentication.md
├── 07-sso.md
├── 08-mfa.md
├── 09-role-based-access-control.md
├── 10-permissions.md
├── 11-permission-policies.md
├── 12-divisions-data-segregation.md
├── 13-least-privilege.md
├── 14-privileged-access.md
├── 15-service-accounts.md
├── 16-api-clients-oauth.md
├── 17-secrets-credential-management.md
├── 18-integration-security.md
├── 19-data-protection.md
├── 20-encryption.md
├── 21-data-residency.md
├── 22-privacy.md
├── 23-pii-sensitive-data.md
├── 24-pci-payment-security.md
├── 25-recording-security.md
├── 26-retention-deletion.md
├── 27-audit-logging.md
├── 28-security-monitoring.md
├── 29-threat-detection.md
├── 30-security-incident-response.md
├── 31-vulnerability-management.md
├── 32-security-change-management.md
├── 33-configuration-governance.md
├── 34-compliance-requirements.md
├── 35-regulatory-controls.md
├── 36-customer-security-policies.md
├── 37-audit-evidence.md
├── 38-access-reviews.md
├── 39-security-reviews.md
├── 40-third-party-risk.md
├── 41-business-continuity.md
├── 42-disaster-recovery.md
├── 43-security-testing.md
├── 44-compliance-testing.md
├── 45-production-security-validation.md
├── 46-operational-security-governance.md
└── 47-security-handover.md
```

## Layer 1 Mapping

Security, Compliance & Governance activities span the complete Genesys Cloud deployment lifecycle.

| Layer 1 Phase | Security Application |
|---|---|
| P01 | Identify security stakeholders and ownership |
| P02 | Discover existing security and compliance requirements |
| P03 | Define security requirements |
| P04 | Design security architecture and controls |
| P05 | Establish security foundations |
| P06 | Implement security controls |
| P07 | Secure integrations and migration |
| P08 | Execute security and compliance testing |
| P09 | Establish operational security |
| P10 | Validate production security |
| P11 | Monitor security during hypercare |
| P12 | Complete security and operational handover |

Individual capability files may map to multiple Layer 1 phases where the capability spans multiple stages of the deployment lifecycle.

## Task ID Standard

Each implementation task uses the established Layer 10 task identification convention:

```text
L10-11.<capability>.<task>
```

### Examples

```text
L10-11.01-001
L10-11.01-002
L10-11.02-001
```

The capability number corresponds directly to the numbered capability file in this directory.

For example:

```text
01-security-strategy.md
        ↓
L10-11.01-001
L10-11.01-002
L10-11.01-003
```

This provides direct traceability between the Layer 2 capability, the Layer 10 capability file, and the individual implementation tasks.

## Standard Task Attributes

Every task follows the established Layer 10 task-file model.

| Attribute | Requirement |
|---|---|
| Task Type | REQUIRED / CONDITIONAL / VALIDATION |
| Layer 1 Phase | P01–P12 |
| Primary Role | Delivery role |
| Customer Responsibility | YES / NO / JOINT |
| Environment | DESIGN / DEV / TEST / UAT / PROD / MULTI |
| Automation | MANUAL / AUTOMATED / HYBRID |
| Baseline Effort | Initial estimate |
| Critical Path | YES / NO / CONDITIONAL |

These attributes are required to support conversion of the task catalogue into a structured project schedule, resource plan, and effort-estimation model.

## Task Design Principle

Tasks are deliberately atomic enough to become individual project schedule rows.

Each task should have:

- a unique Task ID
- a single implementation outcome
- explicit dependencies
- an accountable delivery role
- customer responsibility
- environment
- baseline effort
- deliverable
- acceptance criteria
- critical-path classification

A task should represent a discrete piece of implementation work that can be:

1. assigned to a delivery role
2. assigned to a customer stakeholder where applicable
3. estimated independently
4. scheduled independently
5. linked to prerequisite tasks
6. tracked to completion
7. validated against an objective acceptance criterion

Tasks should not combine unrelated implementation outcomes merely to reduce the number of catalogue entries.

## Classification

### REQUIRED

REQUIRED tasks apply to the normal enterprise deployment methodology and should be considered part of the baseline implementation unless explicitly excluded by project scope.

### CONDITIONAL

CONDITIONAL tasks apply when the customer solution, regulatory environment, integration architecture, security requirements, deployment model, or organisational controls require them.

Examples may include:

- specific regulatory obligations
- PCI-related requirements
- customer-specific security controls
- advanced identity controls
- third-party security assessments
- specialised data residency requirements
- customer-mandated security reviews
- additional audit evidence requirements

Conditional tasks should document the condition that causes the task to become applicable.

### VALIDATION

VALIDATION tasks confirm that previously implemented controls operate as designed.

Validation tasks should normally occur after the corresponding control or configuration has been implemented and should include an objective acceptance criterion.

Examples include:

- validating access restrictions
- validating authentication controls
- validating data segregation
- validating retention controls
- validating audit logging
- validating security monitoring
- validating production security controls

## Layer 2 Traceability

Each capability file retains its Layer 2 capability ID and maps implementation tasks back to the capability.

The traceability chain is:

```text
Layer 2 Capability
        ↓
Layer 10 Capability Task Catalogue
        ↓
Implementation Tasks
        ↓
Project Schedule
        ↓
Effort Estimate
        ↓
Resource Plan
```

Every task should therefore be traceable to:

- the Layer 2 capability
- the Layer 10 capability file
- one or more Layer 1 implementation phases
- prerequisite implementation tasks where applicable

This traceability is essential for maintaining consistency between the capability catalogue and the eventual project delivery schedule.

## Layer 1 Mapping Principles

Security, Compliance & Governance activities span the complete Genesys Cloud implementation lifecycle.

A capability may therefore map to multiple Layer 1 phases.

The Layer 1 mapping should be applied at the task level wherever the activity naturally spans multiple phases, rather than forcing the entire capability into a single phase.

For example:

```text
Security Strategy
        ↓
P01 — Identify security stakeholders and ownership
P02 — Discover existing security and compliance requirements
P03 — Define security requirements

Security Architecture
        ↓
P04 — Design security architecture and controls

Security Foundations and Controls
        ↓
P05 — Establish security foundations
P06 — Implement security controls

Integration Security
        ↓
P07 — Secure integrations and migration

Security and Compliance Testing
        ↓
P08 — Execute security and compliance testing

Operational Security
        ↓
P09 — Establish operational security
P11 — Monitor security during hypercare

Production Security Validation
        ↓
P10 — Validate production security

Security Handover
        ↓
P12 — Complete security and operational handover
```

This approach ensures that the resulting project schedule reflects the actual lifecycle of security and compliance work rather than treating security as a single implementation phase.

## Dependency Management

Security and compliance tasks frequently have dependencies on activities outside this domain.

Dependencies should therefore be explicitly documented within each capability task file.

Typical dependencies include:

- project governance decisions
- customer security policies
- regulatory requirements
- identity architecture
- user and role design
- Genesys Cloud organisation configuration
- division architecture
- integration architecture
- network architecture
- data classification
- recording requirements
- retention requirements
- migration activities
- test environment availability
- security testing
- customer approval
- production deployment
- operational handover

Where a task depends on a task in another Layer 10 catalogue domain, the dependency should reference the appropriate task or capability where known.

## Customer Responsibility

Security and compliance implementation is a shared responsibility between the delivery team and the customer.

Each task must therefore identify whether responsibility is:

```text
YES
NO
JOINT
```

Customer responsibilities may include:

- providing security policies
- defining regulatory requirements
- approving security architecture
- supplying identity provider information
- approving access models
- defining data classifications
- providing compliance requirements
- approving retention requirements
- supplying security contacts
- participating in security testing
- approving security exceptions
- accepting security risks
- providing audit evidence
- approving production security readiness
- accepting operational security handover

The task-level customer responsibility classification should be used when building the project responsibility matrix.

## Environment Classification

Each task must identify the environment in which the work is performed.

Supported values are:

```text
DESIGN
DEV
TEST
UAT
PROD
MULTI
```

Security tasks may span multiple environments.

For example:

```text
Security Configuration
        ↓
DEV → TEST → UAT → PROD
```

Where a security control must be validated across multiple environments, the task should use:

```text
Environment: MULTI
```

The capability file should identify environment-specific activities separately when they require materially different implementation work.

## Automation Classification

Each task must identify the expected implementation approach:

```text
MANUAL
AUTOMATED
HYBRID
```

Automation may include:

- Genesys Cloud Terraform resources
- Genesys Cloud APIs
- Genesys Cloud SDKs
- CI/CD pipelines
- scripted validation
- configuration export/import
- automated compliance checks
- automated access reviews
- automated monitoring
- configuration comparison

Automation should only be identified where it is technically and operationally appropriate.

## Effort Estimation

The `Baseline Effort` value represents an initial implementation estimate for the task.

The estimate should reflect the actual work required to complete the task, including where applicable:

- analysis
- configuration
- development
- automation
- testing
- validation
- documentation
- customer collaboration
- defect remediation
- deployment activities

Effort should not automatically include unrelated project-management overhead unless explicitly stated.

The baseline estimate should be treated as a starting point for project-specific estimation.

Actual effort may vary based on:

- customer complexity
- regulatory requirements
- number of users
- number of divisions
- number of environments
- number of integrations
- security architecture
- identity provider complexity
- existing security maturity
- customer policies
- deployment model
- automation maturity
- migration requirements
- testing requirements

## Critical Path Classification

Each task must identify whether it is:

```text
YES
NO
CONDITIONAL
```

### YES

The task is expected to be a prerequisite for one or more major downstream activities or is likely to affect the overall project completion date.

### NO

The task can normally be completed without affecting the primary project critical path.

### CONDITIONAL

The task becomes critical depending on project scope, customer requirements, regulatory obligations, dependencies, or deployment decisions.

Security tasks that commonly have critical-path implications include:

- security requirements
- security architecture
- identity and access controls
- SSO
- MFA
- permissions
- data segregation
- integration security
- compliance requirements
- security testing
- production security validation
- security handover

## Capability-Level Estimation Considerations

Capability-level estimation should not be calculated simply by multiplying the number of tasks by an average task duration.

The project estimation model should account for:

- task-specific effort
- task dependencies
- parallel execution
- customer dependencies
- resource availability
- critical path
- environment sequencing
- conditional tasks
- validation cycles
- defect remediation
- security review cycles
- compliance approval cycles
- deployment windows

The eventual project schedule should therefore derive duration from the dependency graph and resource allocation rather than from task count alone.

## Capability Catalogue Completion Standard

Each of the 47 capabilities must contain enough information to allow the capability to be converted directly into project delivery activities.

Each capability file should contain:

- Layer 2 capability reference
- capability objective
- Layer 1 mappings
- source implementation activities
- implementation tasks
- task IDs
- task classifications
- primary roles
- customer responsibility
- environment
- automation approach
- baseline effort
- critical-path classification
- dependencies
- deliverables
- acceptance criteria
- capability-level estimation considerations
- definition of done

## Definition of Done

Section 11 is complete when:

- all 47 capabilities have task files
- every capability has Layer 1 mappings
- every capability has decomposed implementation tasks
- every implementation task has a unique Task ID
- every implementation task has a defined task type
- task dependencies are defined
- roles are assigned
- customer responsibilities are identified
- environments are identified
- automation approach is identified
- baseline effort can be estimated
- deliverables are defined
- acceptance criteria are defined
- critical-path tasks are identified
- Layer 2 traceability is maintained
- the catalogue can be converted into a project schedule
- the catalogue can be converted into an effort-estimation model
- the catalogue can support resource planning
- the catalogue can support customer responsibility assignment
- the catalogue can support implementation tracking
- the catalogue can support project acceptance management

## Phase Gate

Section 11 passes the Layer 10 catalogue gate when the complete Security, Compliance & Governance task catalogue can be used without additional decomposition to produce:

1. a project schedule
2. an effort-estimation workbook
3. a resource plan
4. a responsibility matrix
5. a dependency model
6. a delivery tracking model
7. an acceptance-management model

The catalogue must provide sufficient task-level detail that a project manager, solution architect, technical lead, delivery consultant, or estimator can use it as the foundation for a customer-specific Genesys Cloud implementation plan.

---
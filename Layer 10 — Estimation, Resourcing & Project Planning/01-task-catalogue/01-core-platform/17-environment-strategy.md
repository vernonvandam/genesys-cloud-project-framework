# Layer 10 — 2.01.17 Environment Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.17 |
| Capability | Environment Strategy |
| Task Catalogue ID | 01.17 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08, P10, P11, P12 |

## Capability Objective

Define how Genesys Cloud organisations and environments will be structured, managed, configured, promoted, tested, and operated throughout the project lifecycle.

## Source Implementation Activities

1. Identify environment requirements.
2. Define environment strategy.
3. Define configuration promotion model.
4. Establish environments.
5. Configure environment controls.
6. Validate environment strategy.
7. Document environment operating model.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.17-001 — Identify Environment Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Identify requirements for development, testing, UAT, production, disaster recovery, migration, and other environments or organisations.

**Dependencies**

- Organisation strategy
- Project methodology

**Deliverable**

Environment requirements.

**Acceptance Criteria**

Environment requirements are approved.

### Activity 02 — Design

#### L10-01.17-002 — Define Environment Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define the target environment and organisation architecture.

**Dependencies**

- L10-01.17-001
- Organisation architecture
- Security architecture

**Deliverable**

Environment architecture.

**Acceptance Criteria**

Environment model is approved.

#### L10-01.17-003 — Define Configuration Promotion Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | DevOps / Terraform Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define how configuration moves between environments, including manual, API, Terraform, deployment pipeline, and export/import methods.

**Dependencies**

- L10-01.17-002

**Deliverable**

Promotion strategy.

**Acceptance Criteria**

Promotion model is documented and approved.

### Activity 03 — Establish Environments

#### L10-01.17-004 — Establish Non-Production Environments

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV / TEST / UAT |
| Automation | API / TERRAFORM / MANUAL |
| Baseline Effort | 2.0h per environment |
| Critical Path | YES |

**Description**

Establish approved non-production organisations or environments.

**Dependencies**

- L10-01.17-002

**Deliverable**

Non-production environments.

**Acceptance Criteria**

Required environments are accessible and operational.

#### L10-01.17-005 — Establish Production Environment

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | API / TERRAFORM / MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Establish the production organisation/environment according to approved architecture.

**Dependencies**

- L10-01.17-002
- Organisation provisioning

**Deliverable**

Production environment.

**Acceptance Criteria**

Production environment is established and access-controlled.

### Activity 04 — Validate

#### L10-01.17-006 — Validate Environment Separation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate separation, access, configuration, and deployment relationships between environments.

**Dependencies**

- L10-01.17-004
- L10-01.17-005

**Deliverable**

Environment validation evidence.

**Acceptance Criteria**

Environment boundaries and promotion controls pass validation.

### Activity 05 — Operationalise

#### L10-01.17-007 — Document Environment Operating Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Document environment ownership, access, deployment, change, support, and configuration promotion processes.

**Dependencies**

- L10-01.17-006

**Deliverable**

Environment operating model.

**Acceptance Criteria**

Customer operational owners accept the environment model.

## Estimation Considerations

Drivers include:

- number of environments
- number of organisations
- deployment methodology
- Terraform adoption
- CI/CD requirements
- configuration promotion complexity
- security controls
- environment-specific configuration

## Definition of Done

The environment strategy is approved, environments are established, promotion controls are validated, and the operating model is documented.
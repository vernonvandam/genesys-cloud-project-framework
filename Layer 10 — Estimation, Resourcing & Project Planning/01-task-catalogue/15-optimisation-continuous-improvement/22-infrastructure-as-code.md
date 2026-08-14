# Layer 10 — 2.15.22 Infrastructure as Code

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.22 |
| Capability | Infrastructure as Code |
| Task Catalogue ID | 15.22 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P09 |

## Capability Objective

Increase repeatability, consistency, traceability and deployment efficiency through Infrastructure as Code and configuration automation.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess automation maturity |
| P03 | Define IaC requirements |
| P04 | Design IaC architecture |
| P06 | Implement IaC |
| P08 | Validate deployments |
| P09 | Operationalise IaC |

## Source Implementation Activities

1. Assess configuration automation maturity.
2. Identify IaC candidates.
3. Define module and state strategy.
4. Implement IaC.
5. Validate repeatability.

## Implementation Tasks

### L10-15.22-001 — Assess IaC Opportunity

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Terraform / DevOps Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess which Genesys Cloud configuration and supporting infrastructure can be managed through IaC.

**Dependencies**

- Configuration inventory

**Deliverable**

IaC assessment.

**Acceptance Criteria**

IaC candidates and constraints are documented.

### L10-15.22-002 — Define IaC Architecture

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Terraform / DevOps Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Define module structure, state management, variables, environments, repositories and deployment controls.

**Dependencies**

- L10-15.22-001

**Deliverable**

IaC architecture.

**Acceptance Criteria**

Architecture is approved.

### L10-15.22-003 — Implement IaC Modules

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Terraform / DevOps Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | AUTOMATED |
| Baseline Effort | 5.0h |
| Critical Path | NO |

**Description**

Develop and implement reusable IaC modules for agreed Genesys Cloud configuration.

**Dependencies**

- L10-15.22-002

**Deliverable**

IaC implementation.

**Acceptance Criteria**

Modules deploy the defined configuration successfully.

### L10-15.22-004 — Validate IaC Repeatability

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Terraform / DevOps Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | AUTOMATED |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate repeatability, idempotency, state handling and deployment consistency.

**Dependencies**

- L10-15.22-003

**Deliverable**

IaC validation evidence.

**Acceptance Criteria**

Configuration can be reproduced consistently.
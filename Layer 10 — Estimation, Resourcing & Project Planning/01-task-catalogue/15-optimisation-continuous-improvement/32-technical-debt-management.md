# Layer 10 — 2.15.32 Technical Debt Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.32 |
| Capability | Technical Debt Management |
| Task Catalogue ID | 15.32 |
| Primary Layer 1 Phases | P02, P03, P04, P09, P12 |

## Capability Objective

Identify, quantify, prioritise and reduce technical debt that increases risk, cost, complexity or operational effort.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify technical debt |
| P03 | Assess impact and priority |
| P04 | Define remediation architecture |
| P09 | Manage remediation backlog |
| P12 | Establish ongoing debt management |

## Source Implementation Activities

1. Identify technical debt.
2. Assess business and technical impact.
3. Prioritise debt.
4. Define remediation.
5. Track debt reduction.

## Implementation Tasks

### L10-15.32-001 — Identify Technical Debt

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Identify configuration, architecture, integration, automation and operational technical debt.

**Dependencies**

- Architecture assessment
- Configuration assessment

**Deliverable**

Technical debt register.

**Acceptance Criteria**

Known material debt is documented.

### L10-15.32-002 — Assess Technical Debt Impact

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess risk, cost, complexity, operational impact and remediation urgency.

**Dependencies**

- L10-15.32-001

**Deliverable**

Technical debt assessment.

**Acceptance Criteria**

Debt is risk-ranked and prioritised.

### L10-15.32-003 — Define Technical Debt Remediation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Define remediation options and target architecture.

**Dependencies**

- L10-15.32-002

**Deliverable**

Debt remediation plan.

**Acceptance Criteria**

Remediation approach is approved.

### L10-15.32-004 — Establish Technical Debt Backlog

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Maintain technical debt as a governed improvement backlog.

**Dependencies**

- L10-15.32-003

**Deliverable**

Technical debt backlog.

**Acceptance Criteria**

Debt items have owners and priorities.
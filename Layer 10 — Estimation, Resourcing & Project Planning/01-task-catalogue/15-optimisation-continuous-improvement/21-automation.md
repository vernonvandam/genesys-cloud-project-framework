# Layer 10 — 2.15.21 Automation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.21 |
| Capability | Automation |
| Task Catalogue ID | 15.21 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P09 |

## Capability Objective

Identify and implement automation opportunities that reduce manual effort, improve consistency, increase delivery speed and reduce operational risk.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify manual processes |
| P03 | Define automation requirements |
| P04 | Design automation |
| P06 | Build automation |
| P08 | Validate automation |
| P09 | Operationalise automation |

## Source Implementation Activities

1. Identify automation opportunities.
2. Assess automation feasibility.
3. Define automation requirements.
4. Develop automation.
5. Validate and operationalise automation.

## Implementation Tasks

### L10-15.21-001 — Identify Automation Opportunities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify repeatable, manual, error-prone or high-volume activities suitable for automation.

**Dependencies**

- Process inventory
- Operational data

**Deliverable**

Automation opportunity register.

**Acceptance Criteria**

Opportunities are documented and prioritised.

### L10-15.21-002 — Assess Automation Feasibility

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess technical, security, operational, financial and maintenance feasibility.

**Dependencies**

- L10-15.21-001

**Deliverable**

Automation feasibility assessment.

**Acceptance Criteria**

Feasibility and recommended approach are approved.

### L10-15.21-003 — Implement Automation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | AUTOMATED |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Build and implement the approved automation solution.

**Dependencies**

- L10-15.21-002

**Deliverable**

Automation implementation.

**Acceptance Criteria**

Automation performs the defined function reliably.

### L10-15.21-004 — Validate Automation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | AUTOMATED |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate functional correctness, reliability, failure handling and operational supportability.

**Dependencies**

- L10-15.21-003

**Deliverable**

Automation validation evidence.

**Acceptance Criteria**

Automation meets agreed requirements.
# Layer 10 — 2.15.04 Business Value Realisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.04 |
| Capability | Business Value Realisation |
| Task Catalogue ID | 15.04 |
| Primary Layer 1 Phases | P03, P04, P08, P09, P11, P12 |

## Capability Objective

Ensure optimisation initiatives have measurable expected benefits and that actual outcomes are validated after implementation.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define expected business value |
| P04 | Define benefit measurement |
| P08 | Establish validation approach |
| P09 | Establish BAU measurement |
| P11 | Measure early production outcomes |
| P12 | Complete benefit ownership transition |

## Source Implementation Activities

1. Define expected benefits.
2. Establish benefit baselines.
3. Define benefit measures.
4. Track outcomes.
5. Validate benefits.
6. Transfer benefit ownership.

## Implementation Tasks

### L10-15.04-001 — Define Expected Benefits

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define measurable business, customer, agent, operational, technical or financial benefits for the optimisation initiative.

**Dependencies**

- Improvement objective
- Business case

**Deliverable**

Benefits definition.

**Acceptance Criteria**

Benefits are measurable and customer approved.

### L10-15.04-002 — Establish Benefits Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Establish the pre-change baseline against which benefits will be measured.

**Dependencies**

- L10-15.04-001

**Deliverable**

Benefits baseline.

**Acceptance Criteria**

Baseline data is documented and reproducible.

### L10-15.04-003 — Validate Post-Implementation Benefits

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Measure post-implementation performance against the approved baseline and expected benefit.

**Dependencies**

- L10-15.04-002
- Production deployment

**Deliverable**

Benefits validation report.

**Acceptance Criteria**

Actual outcomes are measured and accepted.

### L10-15.04-004 — Transfer Benefits Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Transfer ongoing benefit tracking to the operational or business owner.

**Dependencies**

- L10-15.04-003

**Deliverable**

Benefits ownership record.

**Acceptance Criteria**

Ongoing ownership is accepted.
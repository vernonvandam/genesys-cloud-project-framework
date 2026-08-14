# Layer 10 — 2.15.01 Continuous Improvement Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.01 |
| Capability | Continuous Improvement Strategy |
| Task Catalogue ID | 15.01 |
| Primary Layer 1 Phases | P01, P02, P03, P09, P12 |

## Capability Objective

Establish the governance, lifecycle, objectives, measurement model, ownership and operating rhythm for continual improvement of the Genesys Cloud solution.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish improvement ownership and objectives |
| P02 | Establish baseline performance |
| P03 | Define improvement strategy and measures |
| P09 | Establish BAU improvement processes |
| P12 | Complete transition into continual improvement |

## Source Implementation Activities

1. Establish continual improvement objectives.
2. Define the improvement lifecycle.
3. Establish baseline measures.
4. Define governance and ownership.
5. Establish the BAU improvement operating rhythm.

## Implementation Tasks

### Activity 01 — Establish Improvement Objectives

#### L10-15.01-001 — Confirm Continuous Improvement Objectives

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Service Owner |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm the business, operational, customer, agent and technical objectives that continual improvement must support.

**Dependencies**

- Project objectives
- Customer business strategy

**Deliverable**

Continuous improvement objectives.

**Acceptance Criteria**

Objectives are documented and approved.

---

#### L10-15.01-002 — Define Improvement Success Measures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define measurable outcomes for improvement initiatives.

**Dependencies**

- L10-15.01-001

**Deliverable**

Improvement measurement framework.

**Acceptance Criteria**

Success measures are agreed.

### Activity 02 — Establish Baseline

#### L10-15.01-003 — Establish Current-State Performance Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Establish baseline performance for agreed customer, agent, operational, technical and financial measures.

**Dependencies**

- L10-15.01-002
- Analytics availability

**Deliverable**

Current-state KPI baseline.

**Acceptance Criteria**

Baseline values are documented and traceable to source data.

### Activity 03 — Establish Improvement Lifecycle

#### L10-15.01-004 — Define Continuous Improvement Lifecycle

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define how opportunities are identified, assessed, prioritised, approved, delivered, measured and closed.

**Dependencies**

- L10-15.01-001
- L10-15.01-003

**Deliverable**

Continuous improvement lifecycle.

**Acceptance Criteria**

Lifecycle is documented and approved.

### Activity 04 — Establish BAU Process

#### L10-15.01-005 — Establish Continuous Improvement Governance Rhythm

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

Establish the recurring governance cadence for reviewing performance, opportunities, backlog, benefits and platform evolution.

**Dependencies**

- L10-15.01-004

**Deliverable**

BAU improvement governance process.

**Acceptance Criteria**

Governance cadence, ownership and reporting are agreed.

## Capability-Level Dependencies

- Operations model
- Analytics and reporting
- KPI framework
- Customer business strategy
- Service ownership

## Capability-Level Estimation Considerations

Effort is influenced by:

- organisational maturity
- number of business stakeholders
- number of KPIs
- number of capabilities in scope
- governance complexity

## Definition of Done

The continuous improvement strategy is:

- defined
- measurable
- owned
- governed
- integrated into BAU
- ready for continual use
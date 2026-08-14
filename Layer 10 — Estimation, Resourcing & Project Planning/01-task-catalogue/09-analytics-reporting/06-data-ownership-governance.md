# Layer 10 — 2.09.06 Data Ownership & Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.06 |
| Capability | Data Ownership & Governance |
| Task Catalogue ID | 09.06 |
| Primary Layer 1 Phases | P03, P04, P12 |

## Capability Objective

Define ownership, accountability and governance controls for analytics data and reporting artefacts.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define ownership |
| P04 | Design governance |
| P12 | Establish BAU governance |

## Source Implementation Activities

1. Identify data owners.
2. Define reporting ownership.
3. Define governance controls.
4. Approve ownership model.
5. Handover governance.

## Implementation Tasks

### Activity 01 — Ownership

#### L10-09-06-001 — Identify Data and Reporting Owners

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify owners for critical data, KPIs, reports and dashboards.

**Dependencies**

- L10-09-05-001

**Deliverable**

Ownership matrix.

**Acceptance Criteria**

All critical data and reporting assets have owners.

### Activity 02 — Governance

#### L10-09-06-002 — Define Analytics Governance Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define governance controls for data definitions, reporting changes and ownership.

**Dependencies**

- L10-09-06-001

**Deliverable**

Analytics governance model.

**Acceptance Criteria**

Governance controls are approved.

### Activity 03 — Approval

#### L10-09-06-003 — Approve Reporting Ownership Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Obtain approval for the ownership and governance model.

**Dependencies**

- L10-09-06-002

**Deliverable**

Approved ownership model.

**Acceptance Criteria**

Ownership is accepted by accountable stakeholders.

## Capability-Level Dependencies

- Data inventory
- Reporting requirements
- Security requirements
- Enterprise governance

## Capability-Level Estimation Considerations

Effort depends on the number of data domains, business owners and governance requirements.

## Definition of Done

Data and reporting ownership is documented, approved and operationally assigned.
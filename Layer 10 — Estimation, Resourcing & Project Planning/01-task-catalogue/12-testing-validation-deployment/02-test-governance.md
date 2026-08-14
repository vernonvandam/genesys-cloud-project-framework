# Layer 10 — 2.12.02 Test Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.02 — Test Governance |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.02 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P01–P04, P08–P12 |
| Primary Role | Test Manager |
| Customer Responsibility | JOINT |
| Primary Environment | DESIGN |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Establish governance, decision rights, approvals, reporting, escalation and quality-control mechanisms for testing and deployment.

## Source Implementation Activities

- Establish test governance.
- Define test roles and decision rights.
- Define defect governance.
- Define reporting and escalation.
- Establish quality gate approvals.

## Implementation Tasks

### Activity 01 — Establish Governance

#### L10-12.02-001 — Define Test Governance Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01–P03 |
| Primary Role | Test Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define test governance structure, forums, reporting cadence and decision rights.

**Dependencies**

Test Strategy.

**Deliverable**

Test Governance Model.

**Acceptance Criteria**

Governance forums, participants and decision rights are documented.

### Activity 02 — Define Roles

#### L10-12.02-002 — Assign Test Responsibilities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01–P03 |
| Primary Role | Test Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Assign delivery and customer responsibilities across test lifecycle activities.

**Dependencies**

L10-12.02-001.

**Deliverable**

Test RACI.

**Acceptance Criteria**

All test governance responsibilities have accountable owners.

### Activity 03 — Define Reporting

#### L10-12.02-003 — Define Test Status Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03–P04 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define metrics, dashboards, status reporting and escalation thresholds.

**Dependencies**

L10-12.02-001.

**Deliverable**

Test Reporting Model.

**Acceptance Criteria**

Reporting metrics and escalation thresholds are approved.

### Activity 04 — Govern Quality Gates

#### L10-12.02-004 — Establish Test Approval Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08–P12 |
| Primary Role | Test Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define how test exit criteria and production readiness decisions are formally approved.

**Dependencies**

Test Strategy and test plan.

**Deliverable**

Quality Gate Approval Process.

**Acceptance Criteria**

Formal approval workflow is agreed.

## Capability-Level Dependencies

- Test Strategy
- Project governance
- Customer governance
- Defect management

## Capability-Level Estimation Considerations

Effort increases with governance complexity, number of stakeholders and number of formal test cycles.

## Definition of Done

Test governance is established, responsibilities assigned and quality gates operational.

---
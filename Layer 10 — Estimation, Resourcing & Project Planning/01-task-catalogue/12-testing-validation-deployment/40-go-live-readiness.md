# Layer 10 — 2.12.40 Go-Live Readiness

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.40 — Go-Live Readiness |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.40 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P09–P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Primary Environment | PROD |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Confirm that business, technical, security, testing, operational and deployment prerequisites have been satisfied before production deployment.

## Source Implementation Activities

- Review readiness criteria.
- Validate test exit status.
- Validate operational readiness.
- Validate deployment and rollback readiness.
- Obtain go-live approval.

## Implementation Tasks

### Activity 01 — Execute Readiness Review

#### L10-12.40-001 — Conduct Go-Live Readiness Assessment

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Review all go-live readiness criteria and outstanding risks.

**Dependencies**

Testing, Operational Readiness, Support Readiness and Deployment Planning.

**Deliverable**

Go-Live Readiness Assessment.

**Acceptance Criteria**

All readiness criteria have current status.

### Activity 02 — Validate Exceptions

#### L10-12.40-002 — Review Open Defects and Exceptions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review remaining defects, risks, security findings and exceptions.

**Dependencies**

Defect Management and Compliance Testing.

**Deliverable**

Go-Live Exception Register.

**Acceptance Criteria**

All open items have approved disposition.

### Activity 03 — Obtain Approval

#### L10-12.40-003 — Obtain Go-Live Approval

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain formal customer and project approval to proceed.

**Dependencies**

L10-12.40-001 and L10-12.40-002.

**Deliverable**

Go-Live Approval.

**Acceptance Criteria**

Required approvers authorise production deployment.

## Capability-Level Dependencies

- Test completion
- UAT
- Operational readiness
- Support readiness
- Cutover Plan
- Deployment Plan
- Rollback Plan

## Capability-Level Estimation Considerations

Readiness complexity and stakeholder count drive effort.

## Definition of Done

Formal go-live approval is obtained.

---
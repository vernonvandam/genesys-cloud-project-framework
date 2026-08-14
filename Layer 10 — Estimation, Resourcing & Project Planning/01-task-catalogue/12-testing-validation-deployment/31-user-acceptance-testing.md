# Layer 10 — 2.12.31 User Acceptance Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.31 — User Acceptance Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.31 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P08–P10 |
| Primary Role | UAT Lead |
| Customer Responsibility | YES |
| Primary Environment | UAT |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Enable customer business stakeholders to validate that the solution meets agreed business requirements and is fit for production use.

## Source Implementation Activities

- Prepare UAT.
- Prepare business users and data.
- Execute UAT.
- Manage UAT defects.
- Obtain formal UAT acceptance.

## Implementation Tasks

### Activity 01 — Prepare UAT

#### L10-12.31-001 — Confirm UAT Scope and Participants

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | UAT Lead |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Confirm UAT scenarios, participants, schedule and acceptance criteria.

**Dependencies**

Test Plan and E2E Testing.

**Deliverable**

UAT Plan.

**Acceptance Criteria**

Customer UAT scope and participants are confirmed.

### Activity 02 — Execute UAT

#### L10-12.31-002 — Execute User Acceptance Testing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08–P09 |
| Primary Role | UAT Lead |
| Customer Responsibility | YES |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 8.0h |
| Critical Path | YES |

**Description**

Coordinate customer users through agreed business acceptance scenarios.

**Dependencies**

L10-12.31-001.

**Deliverable**

UAT Execution Results.

**Acceptance Criteria**

All critical UAT scenarios are completed.

### Activity 03 — Obtain Acceptance

#### L10-12.31-003 — Obtain UAT Sign-Off

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09–P10 |
| Primary Role | UAT Lead |
| Customer Responsibility | YES |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain formal customer acceptance of UAT results.

**Dependencies**

L10-12.31-002 and Defect Management.

**Deliverable**

UAT Sign-Off.

**Acceptance Criteria**

Customer formally accepts UAT or approves documented exceptions.

## Capability-Level Dependencies

- E2E Testing
- Defect Management
- Customer SMEs
- UAT Environment

## Capability-Level Estimation Considerations

Number of business processes, participants, test cases and defect cycles drives effort.

## Definition of Done

Customer UAT is completed and formally accepted.

---
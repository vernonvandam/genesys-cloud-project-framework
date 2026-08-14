# Layer 10 — 2.12.03 Test Planning

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.03 — Test Planning |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.03 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P03–P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Primary Environment | TEST |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Convert the approved test strategy into executable test plans, schedules, resources, test cycles, entry criteria and exit criteria.

## Source Implementation Activities

- Define test scope by test level.
- Define test schedule.
- Define resources and execution model.
- Define entry and exit criteria.
- Baseline test plan.

## Implementation Tasks

### Activity 01 — Define Test Scope

#### L10-12.03-001 — Decompose Test Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03–P04 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Break the approved strategy into test cycles and capability-specific test scope.

**Dependencies**

L10-12.01-005.

**Deliverable**

Test Scope Matrix.

**Acceptance Criteria**

All required test cycles are identified.

### Activity 02 — Schedule Testing

#### L10-12.03-002 — Build Test Schedule

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Sequence testing against build, integration, migration and deployment dependencies.

**Dependencies**

L10-12.03-001.

**Deliverable**

Test Schedule.

**Acceptance Criteria**

Test cycles are sequenced against solution delivery milestones.

### Activity 03 — Define Execution Resources

#### L10-12.03-003 — Assign Test Resources

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assign test analysts, technical resources, SMEs and customer participants.

**Dependencies**

L10-12.03-001.

**Deliverable**

Test Resource Plan.

**Acceptance Criteria**

Required test resources are identified and available.

### Activity 04 — Baseline Test Plan

#### L10-12.03-004 — Approve Test Plan

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Test Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Obtain approval for the detailed test plan.

**Dependencies**

L10-12.03-001 through L10-12.03-003.

**Deliverable**

Approved Test Plan.

**Acceptance Criteria**

Customer and delivery stakeholders approve scope, schedule and resources.

## Capability-Level Dependencies

- Test Strategy
- Requirements Traceability
- Environment Strategy
- Solution build schedule

## Capability-Level Estimation Considerations

Primary drivers are test volume, number of capabilities, environments, integrations, business processes and execution cycles.

## Definition of Done

An approved, resourced and scheduled test plan exists.

---
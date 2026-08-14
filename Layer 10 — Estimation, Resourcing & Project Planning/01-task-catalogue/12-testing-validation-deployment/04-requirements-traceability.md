# Layer 10 — 2.12.04 Requirements Traceability

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.04 — Requirements Traceability |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.04 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P02–P08 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Primary Environment | DESIGN / TEST |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Ensure approved business, technical, security and compliance requirements can be traced through design, implementation, testing and acceptance.

## Source Implementation Activities

- Identify testable requirements.
- Create requirements-to-test traceability.
- Identify coverage gaps.
- Maintain traceability through defects and retesting.
- Confirm coverage before UAT and go-live.

## Implementation Tasks

### Activity 01 — Identify Testable Requirements

#### L10-12.04-001 — Identify Testable Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02–P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Review approved requirements and identify those requiring formal validation.

**Dependencies**

Approved requirements.

**Deliverable**

Testable Requirements Register.

**Acceptance Criteria**

All in-scope requirements have testability status.

### Activity 02 — Build Traceability

#### L10-12.04-002 — Map Requirements to Test Cases

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03–P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Map requirements to test cases and acceptance scenarios.

**Dependencies**

L10-12.04-001 and test case design.

**Deliverable**

Requirements Traceability Matrix.

**Acceptance Criteria**

Every applicable requirement has at least one validation path.

### Activity 03 — Identify Coverage Gaps

#### L10-12.04-003 — Validate Requirements Coverage

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review traceability and identify requirements without sufficient test coverage.

**Dependencies**

L10-12.04-002.

**Deliverable**

Coverage Gap Register.

**Acceptance Criteria**

No critical requirement remains without planned validation.

### Activity 04 — Maintain Traceability

#### L10-12.04-004 — Update Traceability Through Defect Resolution

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Maintain traceability as defects, retesting and regression cycles occur.

**Dependencies**

Defect Management.

**Deliverable**

Updated Requirements Traceability Matrix.

**Acceptance Criteria**

Test status accurately reflects current implementation and defect state.

## Capability-Level Dependencies

- Requirements
- Solution design
- Test case catalogue
- Defect Management

## Capability-Level Estimation Considerations

Effort is primarily driven by requirements count, complexity and number of test scenarios.

## Definition of Done

All applicable requirements have traceable validation and current test status.

---
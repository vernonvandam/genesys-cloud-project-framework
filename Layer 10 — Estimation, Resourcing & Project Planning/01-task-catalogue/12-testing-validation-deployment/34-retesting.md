# Layer 10 — 2.12.34 Retesting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.34 — Retesting |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.34 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P08–P10 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Validate that defects have been correctly remediated without introducing unresolved failures.

## Source Implementation Activities

- Identify fixed defects.
- Execute targeted retests.
- Record results.
- Reopen failed defects.
- Confirm closure.

## Implementation Tasks

### Activity 01 — Identify Retest Scope

#### L10-12.34-001 — Build Retest Queue

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify defects ready for retesting and required evidence.

**Dependencies**

Defect Management.

**Deliverable**

Retest Queue.

**Acceptance Criteria**

All resolved defects requiring retest are identified.

### Activity 02 — Execute Retests

#### L10-12.34-002 — Execute Defect Retests

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08–P10 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Repeat affected test scenarios and validate remediation.

**Dependencies**

L10-12.34-001 and defect fixes.

**Deliverable**

Retest Results.

**Acceptance Criteria**

Fixed defects pass retest or are reopened.

### Activity 03 — Close Defects

#### L10-12.34-003 — Confirm Defect Closure

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08–P10 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm evidence and formally close successfully retested defects.

**Dependencies**

L10-12.34-002.

**Deliverable**

Updated Defect Register.

**Acceptance Criteria**

Only validated fixes are closed.

## Capability-Level Dependencies

- Defect Management
- Build remediation
- Regression Testing

## Capability-Level Estimation Considerations

Defect volume and retest complexity determine effort.

## Definition of Done

All applicable defect fixes have been retested and correctly closed or reopened.

---
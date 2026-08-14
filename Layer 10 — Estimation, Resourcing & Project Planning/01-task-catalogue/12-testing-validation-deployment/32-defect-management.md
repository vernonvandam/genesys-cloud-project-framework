# Layer 10 — 2.12.32 Defect Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.32 — Defect Management |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.32 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P06–P12 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Primary Environment | MULTI |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Establish and operate the process for capturing, classifying, prioritising, assigning, resolving, retesting and closing defects.

## Source Implementation Activities

- Establish defect process.
- Capture defects.
- Triage and prioritise.
- Coordinate remediation.
- Retest and close defects.
- Report defect status.

## Implementation Tasks

### Activity 01 — Establish Process

#### L10-12.32-001 — Configure Defect Management Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03–P04 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define defect states, severity, priority, ownership and closure criteria.

**Dependencies**

Test Governance.

**Deliverable**

Defect Management Process.

**Acceptance Criteria**

Defect workflow is approved.

### Activity 02 — Capture and Triage

#### L10-12.32-002 — Triage Test Defects

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Review defects, establish severity and priority, and assign ownership.

**Dependencies**

Test execution.

**Deliverable**

Defect Register.

**Acceptance Criteria**

All active defects have classification and owner.

### Activity 03 — Track Remediation

#### L10-12.32-003 — Coordinate Defect Resolution

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08–P10 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 6.0h |
| Critical Path | YES |

**Description**

Track remediation and retesting of defects through closure.

**Dependencies**

L10-12.32-002.

**Deliverable**

Updated Defect Register.

**Acceptance Criteria**

Critical defects are resolved or formally accepted.

## Capability-Level Dependencies

All test capabilities.

## Capability-Level Estimation Considerations

Defect volume, severity and remediation ownership drive effort.

## Definition of Done

Defects are tracked, resolved, retested and formally closed or accepted.

---
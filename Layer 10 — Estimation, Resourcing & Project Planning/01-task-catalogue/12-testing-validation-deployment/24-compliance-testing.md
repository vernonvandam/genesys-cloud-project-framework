# Layer 10 — 2.12.24 Compliance Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.24 — Compliance Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.24 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P03–P08 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Demonstrate that implemented Genesys Cloud controls satisfy approved regulatory, privacy, contractual and organisational compliance requirements.

## Source Implementation Activities

- Identify compliance test requirements.
- Validate regulatory controls.
- Validate evidence.
- Record exceptions.
- Obtain compliance acceptance.

## Implementation Tasks

### Activity 01 — Define Compliance Tests

#### L10-12.24-001 — Identify Compliance Test Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02–P03 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map compliance requirements to testable controls.

**Dependencies**

Compliance Requirements.

**Deliverable**

Compliance Test Scope.

**Acceptance Criteria**

Applicable requirements have validation coverage.

### Activity 02 — Execute Compliance Tests

#### L10-12.24-002 — Execute Compliance Control Validation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Validate required compliance controls and operational procedures.

**Dependencies**

L10-12.24-001 and Security Testing.

**Deliverable**

Compliance Test Results.

**Acceptance Criteria**

Required controls pass validation.

### Activity 03 — Record Exceptions

#### L10-12.24-003 — Document Compliance Exceptions

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Document control gaps, exceptions, compensating controls and approvals.

**Dependencies**

L10-12.24-002.

**Deliverable**

Compliance Exception Register.

**Acceptance Criteria**

All exceptions have owners and approved disposition.

## Capability-Level Dependencies

- Security
- Privacy
- Compliance Requirements
- Recording
- Retention

## Capability-Level Estimation Considerations

Regulatory scope, control count, evidence requirements and approval cycles drive effort.

## Definition of Done

Required compliance controls are validated and exceptions formally dispositioned.

---
# Layer 10 — 2.02.17 Access Reviews & Recertification

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.17 |
| Capability | Access Reviews & Recertification |
| Task Catalogue ID | 02.17 |
| Primary Layer 1 Phases | P03, P04, P08, P09, P12 |

## Capability Objective

Establish recurring review and recertification of user, role, privileged and integration access.

## Source Implementation Activities

1. Define access review requirements.
2. Identify review populations.
3. Define review frequency and ownership.
4. Establish review process.
5. Validate review controls.
6. Handover BAU recertification.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.17-001 — Define Access Review Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define review scope, frequency, evidence and approval requirements.

**Dependencies**

- Identity governance model

**Deliverable**

Access review requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-02.17-002 — Define Review Population and Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Identify user, administrator, privileged and service identity populations requiring review.

**Dependencies**

- L10-02.17-001

**Deliverable**

Access review matrix.

**Acceptance Criteria**

Review populations and owners are approved.

### Activity 02 — Establish Process

#### L10-02.17-003 — Establish Access Review Procedure

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define the operational process for reviewing, approving, remediating and evidencing access.

**Dependencies**

- L10-02.17-002

**Deliverable**

Access review procedure.

**Acceptance Criteria**

BAU review process is documented.

### Activity 03 — Validate

#### L10-02.17-004 — Execute Initial Access Review

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Perform an initial access review using the target process.

**Dependencies**

- L10-02.17-003

**Deliverable**

Initial review evidence.

**Acceptance Criteria**

Review process produces acceptable evidence and remediation outcomes.

#### L10-02.17-005 — Handover Recertification Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Transfer ownership of recurring access reviews to the customer BAU team.

**Dependencies**

- L10-02.17-004

**Deliverable**

BAU recertification ownership record.

**Acceptance Criteria**

Customer confirms ongoing ownership.
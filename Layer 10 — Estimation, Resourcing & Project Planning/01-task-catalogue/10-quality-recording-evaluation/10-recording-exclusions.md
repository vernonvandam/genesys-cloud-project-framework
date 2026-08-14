# Layer 10 — 2.10.10 Recording Exclusions

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.10 |
| Capability | Recording Exclusions |
| Task Catalogue ID | 10.10 |
| Primary Layer 1 Phases | P03, P04, P05, P08 |

## Capability Objective

Prevent recording of interactions, data or scenarios that must be excluded for privacy, security, legal or business reasons.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Identify exclusion requirements |
| P04 | Design exclusions |
| P05 | Configure exclusions |
| P08 | Validate exclusion behaviour |

## Source Implementation Activities

1. Identify exclusion scenarios.
2. Define exclusion logic.
3. Configure exclusions.
4. Validate protected scenarios.

## Implementation Tasks

### Activity 01 — Define Exclusions

#### L10-10.10-001 — Identify Recording Exclusions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify interactions and data that must not be recorded.

**Dependencies**

- Privacy and compliance requirements

**Deliverable**

Recording exclusion catalogue.

**Acceptance Criteria**

Required exclusions are approved.

#### L10-10.10-002 — Design Exclusion Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define the technical approach for implementing recording exclusions.

**Dependencies**

- L10-10.10-001

**Deliverable**

Exclusion design.

**Acceptance Criteria**

Exclusion logic is approved.

### Activity 02 — Implement and Validate

#### L10-10.10-003 — Configure Recording Exclusions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Implement approved recording exclusion controls.

**Dependencies**

- L10-10.10-002

**Deliverable**

Configured recording exclusions.

**Acceptance Criteria**

Defined exclusions are active.

#### L10-10.10-004 — Validate Recording Exclusions

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Test protected scenarios and confirm excluded content is not retained as prohibited.

**Dependencies**

- L10-10.10-003

**Deliverable**

Exclusion validation evidence.

**Acceptance Criteria**

All exclusion scenarios pass.

## Definition of Done

Required recording exclusions are implemented and validated.

---

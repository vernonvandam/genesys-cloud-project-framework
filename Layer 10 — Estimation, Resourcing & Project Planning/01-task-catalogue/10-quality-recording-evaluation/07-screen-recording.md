# Layer 10 — 2.10.07 Screen Recording

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.07 |
| Capability | Screen Recording |
| Task Catalogue ID | 10.07 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P10 |

## Capability Objective

Configure screen recording where required for agent quality, compliance, training or operational analysis.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define screen recording requirements |
| P04 | Design recording scope |
| P05 | Configure screen recording |
| P08 | Validate recordings |
| P10 | Confirm readiness |

## Source Implementation Activities

1. Define screen recording scope.
2. Configure screen recording.
3. Validate capture and access.

## Implementation Tasks

### Activity 01 — Define Screen Recording

#### L10-10.07-001 — Define Screen Recording Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify users, queues, applications and interaction scenarios requiring screen recording.

**Dependencies**

- Recording strategy

**Deliverable**

Screen recording scope.

**Acceptance Criteria**

Required screen recording scenarios are approved.

### Activity 02 — Implement and Validate

#### L10-10.07-002 — Configure Screen Recording

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure screen recording according to approved requirements.

**Dependencies**

- L10-10.07-001

**Deliverable**

Configured screen recording.

**Acceptance Criteria**

Approved scenarios generate screen recordings.

---

#### L10-10.07-003 — Validate Screen Recording

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate recording capture, availability, playback and access controls.

**Dependencies**

- L10-10.07-002

**Deliverable**

Screen recording validation evidence.

**Acceptance Criteria**

Required screen recording scenarios pass.

## Definition of Done

Screen recording is configured where required and validated.

---

# Layer 10 — 2.10.33 Screen Monitoring

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.33 |
| Capability | Screen Monitoring |
| Task Catalogue ID | 10.33 |
| Primary Layer 1 Phases | P03, P04, P05, P08 |

## Capability Objective

Provide authorised supervisors and quality users with screen monitoring capabilities where required.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define screen monitoring requirements |
| P04 | Design monitoring model |
| P05 | Configure monitoring |
| P08 | Validate monitoring |

## Source Implementation Activities

1. Define screen monitoring use cases.
2. Design monitoring access.
3. Configure screen monitoring.
4. Validate access and behaviour.

## Implementation Tasks

### Activity 01 — Define Monitoring

#### L10-10.33-001 — Define Screen Monitoring Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Quality Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Identify roles, teams and scenarios requiring screen monitoring.

**Dependencies**

- Screen recording strategy

**Deliverable**

Screen monitoring requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-10.33-002 — Design Screen Monitoring Access

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Define monitoring permissions and visibility boundaries.

**Dependencies**

- L10-10.33-001

**Deliverable**

Screen monitoring access model.

**Acceptance Criteria**

Access model is approved.

### Activity 02 — Configure and Validate

#### L10-10.33-003 — Configure Screen Monitoring

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure screen monitoring for approved users.

**Dependencies**

- L10-10.33-002

**Deliverable**

Configured screen monitoring.

**Acceptance Criteria**

Required users can access monitoring.

#### L10-10.33-004 — Validate Screen Monitoring

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

Validate screen monitoring visibility, permissions and behaviour.

**Dependencies**

- L10-10.33-003

**Deliverable**

Screen monitoring validation evidence.

**Acceptance Criteria**

Monitoring scenarios pass.

## Definition of Done

Screen monitoring operates correctly where required.

---

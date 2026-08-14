# Layer 10 — 2.04.04 Queue Configuration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.04 |
| Capability | Queue Configuration |
| Task Catalogue ID | 04.04 |
| Primary Layer 1 Phases | P04, P05, P06, P08, P10, P11 |

## Capability Objective

Configure Genesys Cloud queues according to the approved target architecture.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Confirm queue design |
| P05 | Establish queue foundations |
| P06 | Configure queue behaviour |
| P08 | Test queues |
| P10 | Prepare production |
| P11 | Validate after cutover |

## Source Implementation Activities

1. Prepare queue configuration.
2. Create queues.
3. Configure queue settings.
4. Assign routing relationships.
5. Validate queue behaviour.

## Implementation Tasks

### Activity 01 — Prepare Queue Configuration

#### L10-04.04-001 — Prepare Queue Configuration Matrix

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Prepare the configuration matrix covering queue names, descriptions, divisions, media settings, routing methods and ownership.

**Dependencies**

- Queue architecture

**Deliverable**

Queue configuration matrix.

**Acceptance Criteria**

Matrix is complete and approved.

### Activity 02 — Configure Queues

#### L10-04.04-002 — Create Queue Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per queue |
| Critical Path | YES |

**Description**

Create and configure queues according to the approved configuration matrix.

**Dependencies**

- L10-04.04-001

**Deliverable**

Configured queues.

**Acceptance Criteria**

All required queues exist with approved configuration.

#### L10-04.04-003 — Configure Queue Routing Settings

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per queue |
| Critical Path | YES |

**Description**

Configure queue routing methods, skills, evaluation criteria, service levels and related settings.

**Dependencies**

- L10-04.04-002
- Routing strategy

**Deliverable**

Queue routing configuration.

**Acceptance Criteria**

Queue routing settings match the approved design.

### Activity 03 — Validate

#### L10-04.04-004 — Validate Queue Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per queue group |
| Critical Path | YES |

**Description**

Validate queue configuration and routing behaviour.

**Dependencies**

- L10-04.04-003

**Deliverable**

Queue test evidence.

**Acceptance Criteria**

All critical queue scenarios pass.

## Capability-Level Dependencies

- Queue architecture
- Routing methods
- Skills
- Agent membership

## Capability-Level Estimation Considerations

Primary driver is queue count and configuration complexity.

## Definition of Done

All required queues are configured, validated and ready for production.

---

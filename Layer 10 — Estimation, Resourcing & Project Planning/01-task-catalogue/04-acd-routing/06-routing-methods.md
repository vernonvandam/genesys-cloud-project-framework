# Layer 10 — 2.04.06 Routing Methods

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.06 |
| Capability | Routing Methods |
| Task Catalogue ID | 04.06 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Define and implement the routing methods used to select eligible agents.

## Source Implementation Activities

1. Identify routing methods.
2. Select methods by queue.
3. Configure routing methods.
4. Test routing behaviour.

## Implementation Tasks

### L10-04.06-001 — Identify Routing Method Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Determine the required routing method for each queue and channel.

**Dependencies**

- Queue architecture

**Deliverable**

Routing method matrix.

**Acceptance Criteria**

Routing methods are approved.

### L10-04.06-002 — Configure Routing Methods

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per routing configuration |
| Critical Path | YES |

**Description**

Configure approved routing methods.

**Dependencies**

- L10-04.06-001

**Deliverable**

Configured routing methods.

**Acceptance Criteria**

Each queue uses the approved method.

### L10-04.06-003 — Validate Routing Method Behaviour

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per routing model |
| Critical Path | YES |

**Description**

Validate agent selection under expected and exception conditions.

**Dependencies**

- L10-04.06-002

**Deliverable**

Routing test evidence.

**Acceptance Criteria**

Routing behaviour matches approved design.

## Capability-Level Dependencies

- Queue configuration
- Skills
- Agent availability
- Presence

## Definition of Done

Routing methods are configured and validated.

---

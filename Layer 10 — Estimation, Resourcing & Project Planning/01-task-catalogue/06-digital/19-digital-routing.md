# Layer 10 — 2.06.19 Digital Routing

## Capability Objective

Configure ACD routing for digital interactions.

## Implementation Tasks

### L10-06.19-001 — Define Digital Routing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define routing rules, queues, skills, priorities, schedules and fallback behaviour.

**Dependencies**

- Digital architecture
- ACD routing design

**Deliverable**

Digital routing matrix.

**Acceptance Criteria**

Routing design approved.

### L10-06.19-002 — Configure Digital Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure digital routing according to the approved routing matrix.

**Dependencies**

- L10-06.19-001

**Deliverable**

Digital routing configuration.

**Acceptance Criteria**

Test interactions route correctly.

### L10-06.19-003 — Validate Routing Scenarios

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate normal, overflow, unavailable, priority and skill-based routing.

**Dependencies**

- L10-06.19-002

**Deliverable**

Routing validation evidence.

**Acceptance Criteria**

All approved routing scenarios pass.

## Definition of Done

Digital routing is configured and validated against approved routing requirements.

---

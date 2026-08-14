# Layer 10 — 2.06.17 Digital Authentication

## Capability Objective

Define and implement digital customer authentication where required.

## Implementation Tasks

### L10-06.17-001 — Define Authentication Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define authentication methods, assurance requirements, identity sources and protected journeys.

**Dependencies**

- Customer identity model
- Security requirements

**Deliverable**

Authentication requirements.

**Acceptance Criteria**

Authentication approach approved.

### L10-06.17-002 — Configure Authentication Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure required authentication integration and customer journey behaviour.

**Dependencies**

- L10-06.17-001

**Deliverable**

Authentication integration.

**Acceptance Criteria**

Test authentication succeeds and fails as designed.

### L10-06.17-003 — Validate Authentication Controls

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Test successful authentication, failure, timeout, unauthorised access and escalation.

**Dependencies**

- L10-06.17-002

**Deliverable**

Authentication validation evidence.

**Acceptance Criteria**

Security scenarios pass.

## Definition of Done

Authentication controls are approved, integrated and validated.

---

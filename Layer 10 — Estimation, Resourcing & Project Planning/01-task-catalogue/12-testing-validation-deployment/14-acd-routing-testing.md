# Layer 10 — 2.12.14 ACD & Routing Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.14 — ACD & Routing Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.14 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Validate queues, routing methods, skills, priorities, schedules, overflow and agent selection against approved routing design.

## Source Implementation Activities

- Validate queue configuration.
- Test routing logic.
- Test skills and priorities.
- Test overflow and exception handling.
- Validate routing outcomes.

## Implementation Tasks

### Activity 01 — Validate Routing Configuration

#### L10-12.14-001 — Validate ACD Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate queues, skills, priorities, schedules and routing configuration.

**Dependencies**

ACD & Routing implementation.

**Deliverable**

ACD Configuration Validation.

**Acceptance Criteria**

Configured routing matches approved design.

### Activity 02 — Test Routing

#### L10-12.14-002 — Execute Standard Routing Tests

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Test normal routing scenarios across queues and agent groups.

**Dependencies**

L10-12.14-001.

**Deliverable**

Routing Test Results.

**Acceptance Criteria**

Calls/interactions route to expected destinations.

### Activity 03 — Test Exceptions

#### L10-12.14-003 — Test Overflow and Exception Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Validate overflow, no-agent, closed-hours, timeout and exception paths.

**Dependencies**

L10-12.14-002.

**Deliverable**

Exception Routing Test Results.

**Acceptance Criteria**

All approved exception paths behave correctly.

## Capability-Level Dependencies

- Voice & Telephony
- ACD & Routing
- Architect
- Identity & Access

## Capability-Level Estimation Considerations

Queue count, routing complexity, skills, priorities and exception scenarios drive effort.

## Definition of Done

Required routing scenarios pass and routing defects are resolved or accepted.

---
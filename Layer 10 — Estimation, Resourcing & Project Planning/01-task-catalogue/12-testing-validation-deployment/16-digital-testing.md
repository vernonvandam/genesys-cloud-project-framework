# Layer 10 — 2.12.16 Digital Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.16 — Digital Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.16 |
| Default Classification | CONDITIONAL |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | MANUAL |
| Critical Path | CONDITIONAL |

## Capability Objective

Validate digital channels, messaging, routing, bot interactions, transfers, session handling and digital customer journeys where in scope.

## Source Implementation Activities

- Validate digital channel configuration.
- Test inbound digital interactions.
- Test routing and transfers.
- Test bot or automation paths.
- Test failure and escalation scenarios.

## Implementation Tasks

### Activity 01 — Validate Digital Configuration

#### L10-12.16-001 — Validate Digital Channel Configuration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate digital channels, messaging configuration and supporting routing.

**Dependencies**

Digital implementation.

**Deliverable**

Digital Configuration Validation.

**Acceptance Criteria**

Configured digital channels match approved design.

### Activity 02 — Test Digital Journeys

#### L10-12.16-002 — Execute Digital Functional Tests

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate customer digital journeys, routing and agent handling.

**Dependencies**

L10-12.16-001.

**Deliverable**

Digital Test Results.

**Acceptance Criteria**

Critical digital scenarios pass.

### Activity 03 — Test Escalations

#### L10-12.16-003 — Validate Digital Escalation and Transfer

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Test escalation, transfer and agent handoff scenarios.

**Dependencies**

L10-12.16-002.

**Deliverable**

Digital Escalation Test Results.

**Acceptance Criteria**

Escalation paths behave as designed.

## Capability-Level Dependencies

- Digital
- ACD & Routing
- Architect
- Identity & Access

## Capability-Level Estimation Considerations

Channel count, journey complexity, bot interactions and routing paths drive effort.

## Definition of Done

All in-scope digital journeys pass validation.

---
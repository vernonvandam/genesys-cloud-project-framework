# Layer 10 — 2.06.03 Web Messaging

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.03 |
| Capability | Web Messaging |
| Task Catalogue ID | 06.03 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P11 |

## Capability Objective

Design and implement web messaging as an asynchronous digital customer interaction channel.

## Source Implementation Activities

1. Define requirements.
2. Configure web messaging.
3. Configure routing.
4. Integrate web messaging.
5. Test customer journeys.
6. Deploy and validate.

## Implementation Tasks

### L10-06.03-001 — Define Web Messaging Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define entry points, customer journeys, operating hours, routing, identity, authentication and escalation requirements.

**Dependencies**

- Digital architecture
- Channel strategy

**Deliverable**

Web messaging requirements.

**Acceptance Criteria**

Requirements are approved.

### L10-06.03-002 — Configure Web Messaging

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the web messaging channel according to approved requirements.

**Dependencies**

- L10-06.03-001

**Deliverable**

Configured web messaging channel.

**Acceptance Criteria**

Channel is available for test.

### L10-06.03-003 — Configure Web Messaging Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure queue, skills, priority, schedules and routing behaviour.

**Dependencies**

- L10-06.03-002
- Digital routing design

**Deliverable**

Web messaging routing configuration.

**Acceptance Criteria**

Interactions route to the correct target.

### L10-06.03-004 — Validate Web Messaging

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

Validate customer entry, routing, agent handling, transfers, context and closure.

**Dependencies**

- L10-06.03-003

**Deliverable**

Test evidence.

**Acceptance Criteria**

Approved web messaging scenarios pass.

### L10-06.03-005 — Activate Web Messaging

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Activate the approved web messaging channel in production.

**Dependencies**

- L10-06.03-004
- Production readiness approval

**Deliverable**

Production web messaging channel.

**Acceptance Criteria**

Customer interaction successfully reaches the intended production flow.

## Capability-Level Dependencies

- Digital Architecture
- Web Messenger Deployment
- Digital Routing
- Digital Queues & Skills
- Agent Digital Workspace

## Definition of Done

Web messaging is configured, routed, tested, production-enabled and supported.

---
# Layer 10 — 2.06.06 SMS

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.06 |
| Capability | SMS |
| Task Catalogue ID | 06.06 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P07, P08, P10, P11 |

## Capability Objective

Implement SMS customer engagement including number provisioning, routing, messaging behaviour, compliance and operational support.

## Implementation Tasks

### L10-06.06-001 — Define SMS Requirements

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

Define use cases, numbers, geography, inbound/outbound requirements, routing, compliance and operating model.

**Dependencies**

- Digital channel strategy

**Deliverable**

SMS requirements.

**Acceptance Criteria**

Requirements approved.

### L10-06.06-002 — Configure SMS Channel

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure SMS channel and applicable numbers.

**Dependencies**

- L10-06.06-001

**Deliverable**

SMS configuration.

**Acceptance Criteria**

SMS is available for testing.

### L10-06.06-003 — Validate SMS Routing and Compliance

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate routing, opt-in/opt-out behaviour, message handling, compliance and agent experience.

**Dependencies**

- L10-06.06-002

**Deliverable**

SMS validation evidence.

**Acceptance Criteria**

Required scenarios pass.

### L10-06.06-004 — Activate SMS

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Activate approved SMS capability.

**Dependencies**

- L10-06.06-003

**Deliverable**

Production SMS capability.

**Acceptance Criteria**

Production SMS interaction completes successfully.

## Definition of Done

SMS is provisioned, configured, compliant, tested and operational where applicable.

---
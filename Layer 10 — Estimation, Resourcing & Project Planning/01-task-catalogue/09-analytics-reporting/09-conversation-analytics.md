# Layer 10 — 2.09.09 Conversation Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.09 |
| Capability | Conversation Analytics |
| Task Catalogue ID | 09.09 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Configure conversation-level analytics to identify trends, topics, outcomes and customer interaction patterns where required.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define conversation analytics requirements |
| P04 | Design analytics model |
| P06 | Configure analytics |
| P08 | Validate results |

## Source Implementation Activities

1. Define use cases.
2. Define topics and analytical requirements.
3. Configure conversation analytics.
4. Validate results.
5. Document limitations.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-09-001 — Define Conversation Analytics Use Cases

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define business use cases for conversation-level analytics.

**Dependencies**

- L10-09-02-002

**Deliverable**

Conversation analytics requirements.

**Acceptance Criteria**

Use cases and expected outcomes are approved.

### Activity 02 — Design

#### L10-09-09-002 — Design Conversation Analytics Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define analytical categories, topics, filters and reporting outputs.

**Dependencies**

- L10-09-09-001

**Deliverable**

Conversation analytics design.

**Acceptance Criteria**

Design is approved.

### Activity 03 — Configure

#### L10-09-09-003 — Configure Conversation Analytics

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Configure required conversation analytics capabilities.

**Dependencies**

- L10-09-09-002

**Deliverable**

Configured conversation analytics.

**Acceptance Criteria**

Configured analytics produce expected results.

### Activity 04 — Validation

#### L10-09-09-004 — Validate Conversation Analytics

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Validate conversation analytics against approved use cases.

**Dependencies**

- L10-09-09-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Approved use cases pass validation.

## Capability-Level Dependencies

- Digital and voice interaction data
- Recording configuration where applicable
- Analytics requirements
- Quality requirements

## Capability-Level Estimation Considerations

Effort depends on use case complexity, analytical configuration and validation volume.

## Definition of Done

Conversation analytics are configured and validated where required.
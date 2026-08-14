# Layer 10 — 2.06.16 Digital Menus & Journeys

## Capability Objective

Define customer-facing digital menus, journey logic and navigation.

## Implementation Tasks

### L10-06.16-001 — Map Digital Customer Journey

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map the customer journey from digital entry through self-service, routing, agent handling and completion.

**Dependencies**

- Digital channel strategy

**Deliverable**

Customer journey map.

**Acceptance Criteria**

Journey is approved.

### L10-06.16-002 — Configure Digital Menu and Journey Logic

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

Implement approved digital menu and journey logic.

**Dependencies**

- L10-06.16-001

**Deliverable**

Configured digital journey.

**Acceptance Criteria**

Configured journey matches approved design.

### L10-06.16-003 — Validate Customer Journey

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate customer navigation, self-service, routing, escalation and completion.

**Dependencies**

- L10-06.16-002

**Deliverable**

UAT evidence.

**Acceptance Criteria**

Customer journey passes UAT.

## Definition of Done

Digital menus and customer journeys are approved and validated.

---

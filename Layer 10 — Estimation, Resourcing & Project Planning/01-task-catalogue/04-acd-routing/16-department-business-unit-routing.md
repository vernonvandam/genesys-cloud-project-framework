# Layer 10 — 2.04.16 Department & Business Unit Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.16 |
| Capability | Department & Business Unit Routing |
| Task Catalogue ID | 04.16 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Ensure interactions are routed according to departmental and business-unit ownership.

## Source Implementation Activities

1. Identify business-unit routing requirements.
2. Map queues and agents.
3. Configure routing relationships.
4. Validate segregation.

## Implementation Tasks

### L10-04.16-001 — Define Business Unit Routing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define how departments and business units affect routing.

**Dependencies**

- Business unit architecture
- Queue architecture

**Deliverable**

Business-unit routing matrix.

**Acceptance Criteria**

Routing ownership is approved.

### L10-04.16-002 — Configure Department Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per routing model |
| Critical Path | YES |

**Description**

Configure department and business-unit routing relationships.

**Dependencies**

- L10-04.16-001

**Deliverable**

Configured departmental routing.

**Acceptance Criteria**

Interactions route to the correct organisational area.

### L10-04.16-003 — Validate Business Unit Segregation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate correct routing and segregation between business units.

**Dependencies**

- L10-04.16-002

**Deliverable**

Routing segregation evidence.

**Acceptance Criteria**

Interactions do not cross organisational boundaries incorrectly.

## Definition of Done

Business-unit routing is configured and validated.

---

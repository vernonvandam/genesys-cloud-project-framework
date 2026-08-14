# Layer 10 — 2.05.18 Data Tables

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.18 |
| Capability | Data Tables |
| Task Catalogue ID | 05.18 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Implement configuration-driven business data used by Architect flows.

## Source Implementation Activities

1. Define Data Table requirements.
2. Configure tables and rows.
3. Validate lookups.

## Implementation Tasks

### Activity 01 — Define Data Tables

#### L10-05.18-001 — Define Data Table Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Define table purpose, schema, keys, values, ownership and update requirements.

**Dependencies**

- Business rules

**Deliverable**

Data Table specification.

**Acceptance Criteria**

Table structure is approved.

---

#### L10-05.18-002 — Configure Data Tables

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Create Data Tables and populate required configuration data.

**Dependencies**

- L10-05.18-001

**Deliverable**

Configured Data Tables.

**Acceptance Criteria**

Tables contain approved schema and initial data.

---

#### L10-05.18-003 — Validate Data Table Lookups

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Validate successful, missing and invalid Data Table lookups.

**Dependencies**

- L10-05.18-002

**Deliverable**

Data Table validation evidence.

**Acceptance Criteria**

All defined lookup scenarios pass.
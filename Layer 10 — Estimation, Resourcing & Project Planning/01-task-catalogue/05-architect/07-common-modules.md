# Layer 10 — 2.05.07 Common Modules

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.07 |
| Capability | Common Modules |
| Task Catalogue ID | 05.07 |
| Primary Layer 1 Phases | P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Create reusable Architect Common Modules to reduce duplication, improve maintainability and standardise recurring flow behaviour.

## Source Implementation Activities

1. Identify reusable flow logic.
2. Design Common Modules.
3. Build and test modules.
4. Integrate modules into flows.

## Implementation Tasks

### Activity 01 — Identify Reusable Logic

#### L10-05.07-001 — Identify Common Module Candidates

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify duplicated or reusable flow logic suitable for Common Modules.

**Dependencies**

- Flow architecture
- Flow inventory

**Deliverable**

Common Module candidate register.

**Acceptance Criteria**

Reusable components are identified and approved.

---

#### L10-05.07-002 — Build Common Modules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Build approved Common Modules with defined inputs, outputs and error behaviour.

**Dependencies**

- L10-05.07-001

**Deliverable**

Configured Common Modules.

**Acceptance Criteria**

Modules operate independently and meet design requirements.

---

#### L10-05.07-003 — Validate Module Integration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate Common Module behaviour when invoked from consuming flows.

**Dependencies**

- L10-05.07-002
- Consuming flows

**Deliverable**

Module validation evidence.

**Acceptance Criteria**

Modules perform correctly across all consuming scenarios.
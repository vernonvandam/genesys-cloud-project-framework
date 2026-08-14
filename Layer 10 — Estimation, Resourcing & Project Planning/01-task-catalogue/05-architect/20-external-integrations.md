# Layer 10 — 2.05.20 External Integrations

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.20 |
| Capability | External Integrations |
| Task Catalogue ID | 05.20 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Integrate Architect with external systems required to support customer journeys and business processes.

## Source Implementation Activities

1. Identify external dependencies.
2. Define integration contracts.
3. Configure integration.
4. Validate end-to-end behaviour.

## Implementation Tasks

### Activity 01 — Define Integration

#### L10-05.20-001 — Identify External Integration Requirements

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

Identify external systems, data dependencies, authentication, API contracts and business outcomes.

**Dependencies**

- Current-state discovery
- Customer journey requirements

**Deliverable**

Integration inventory.

**Acceptance Criteria**

Integration dependencies are documented and approved.

---

#### L10-05.20-002 — Configure External Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Implement the required integration and Architect interaction pattern.

**Dependencies**

- L10-05.20-001
- External system availability

**Deliverable**

Configured integration.

**Acceptance Criteria**

Integration executes using approved contracts.

---

#### L10-05.20-003 — Validate Integration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate successful, timeout, error and unavailable-system scenarios.

**Dependencies**

- L10-05.20-002

**Deliverable**

Integration test evidence.

**Acceptance Criteria**

Integration and fallback behaviour pass.
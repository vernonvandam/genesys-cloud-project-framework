# Layer 10 — 2.07.37 HR / HCM Integration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.37 |
| Capability | HR / HCM Integration |
| Task Catalogue ID | 07.37 |
| Primary Layer 1 Phases | P03, P04, P07, P08, P10, P11 |

## Capability Objective

Integrate workforce information between Genesys Cloud WFM and HR/HCM systems where required.

## Source Implementation Activities

1. Confirm HR/HCM integration scope.
2. Define source data.
3. Define mappings and interfaces.
4. Implement integration.
5. Validate synchronisation.

## Implementation Tasks

### Activity 01 — Define Integration

#### L10-07.37-001 — Confirm HR/HCM Integration Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Determine whether HR/HCM integration is required and identify participating systems.

**Dependencies**

- WFM scope
- HR requirements

**Deliverable**

HR/HCM integration scope.

**Acceptance Criteria**

Scope is approved.

#### L10-07.37-002 — Define HR/HCM Data Mapping

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Map employee, organisational, employment and workforce attributes between systems.

**Dependencies**

- L10-07.37-001

**Deliverable**

HR/HCM mapping specification.

**Acceptance Criteria**

Data mapping is approved.

### Activity 02 — Implement and Validate

#### L10-07.37-003 — Implement HR/HCM Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | API / SCRIPT |
| Baseline Effort | 6.0h |
| Critical Path | NO |

**Description**

Implement approved HR/HCM integration flows.

**Dependencies**

- L10-07.37-002

**Deliverable**

Working HR/HCM integration.

**Acceptance Criteria**

Integration executes successfully.

#### L10-07.37-004 — Validate HR/HCM Synchronisation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | SCRIPT |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Validate employee data synchronisation, error handling and reconciliation.

**Dependencies**

- L10-07.37-003

**Deliverable**

HR/HCM integration validation.

**Acceptance Criteria**

Approved synchronisation scenarios pass.
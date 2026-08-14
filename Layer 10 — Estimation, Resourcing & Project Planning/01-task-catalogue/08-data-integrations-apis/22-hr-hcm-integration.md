# Layer 10 — 2.08.22 HR / HCM Integration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.22 |
| Capability | HR / HCM Integration |
| Task Catalogue ID | 08.22 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08 |

## Capability Objective

Integrate HR/HCM systems with Genesys Cloud where employee, organisational or workforce data is required.

## Implementation Tasks

### L10-08.22-001 — Assess HR/HCM Data Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify employee, organisational, role and workforce data required from HR/HCM platforms.

**Dependencies**

- Workforce requirements

**Deliverable**

HR/HCM integration assessment.

**Acceptance Criteria**

Required data domains are approved.

### L10-08.22-002 — Implement HR/HCM Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 6.0h |
| Critical Path | CONDITIONAL |

**Description**

Implement approved HR/HCM interfaces and data transformations.

**Dependencies**

- L10-08.22-001
- Data mapping

**Deliverable**

HR/HCM integration.

**Acceptance Criteria**

Required employee data flows successfully.

### L10-08.22-003 — Validate HR/HCM Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate data accuracy, security, lifecycle events and reconciliation.

**Dependencies**

- L10-08.22-002

**Deliverable**

HR/HCM validation evidence.

**Acceptance Criteria**

Employee data is accurate and appropriately controlled.
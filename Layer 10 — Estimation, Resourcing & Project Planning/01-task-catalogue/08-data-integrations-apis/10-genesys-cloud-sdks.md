# Layer 10 — 2.08.10 Genesys Cloud SDKs

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.10 |
| Capability | Genesys Cloud SDKs |
| Task Catalogue ID | 08.10 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Determine where Genesys Cloud SDKs are appropriate and implement supported SDK-based integrations.

## Implementation Tasks

### L10-08.10-001 — Assess SDK Requirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Integration Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Determine whether SDK use provides value over direct API consumption.

**Dependencies**

- API requirements

**Deliverable**

SDK assessment.

**Acceptance Criteria**

SDK decision is documented.

### L10-08.10-002 — Select SDK and Version

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Integration Engineer |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Select supported SDK technology and establish version management requirements.

**Dependencies**

- L10-08.10-001

**Deliverable**

SDK implementation standard.

**Acceptance Criteria**

Approved SDK and version are recorded.

### L10-08.10-003 — Implement and Validate SDK Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Implement and test the required SDK operations.

**Dependencies**

- L10-08.10-002

**Deliverable**

SDK integration.

**Acceptance Criteria**

Required SDK operations pass integration tests.
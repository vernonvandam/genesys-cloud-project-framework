# Layer 10 — 2.14.16 Configuration Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.16 |
| Capability | Configuration Management |
| Task Catalogue ID | 14.16 |
| Primary Layer 1 Phases | P04, P06, P09, P12 |

## Capability Objective

Maintain control over the configuration baseline and configuration changes.

## Implementation Tasks

### L10-14.16-001 — Define Configuration Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define configuration objects that must be tracked and controlled.

**Dependencies**

- Solution architecture
- Platform configuration

**Deliverable**

Configuration baseline definition.

**Acceptance Criteria**

Configuration scope is documented.

### L10-14.16-002 — Establish Configuration Management Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Establish methods for recording, comparing and controlling configuration.

**Dependencies**

- L10-14.16-001
- Change management

**Deliverable**

Configuration management procedure.

**Acceptance Criteria**

Configuration changes can be traced.

### L10-14.16-003 — Validate Configuration Baseline

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate the production configuration baseline and documentation.

**Dependencies**

- L10-14.16-002

**Deliverable**

Production configuration baseline.

**Acceptance Criteria**

Baseline is complete and accepted.

## Definition of Done

The configuration baseline is controlled, traceable and documented.

---

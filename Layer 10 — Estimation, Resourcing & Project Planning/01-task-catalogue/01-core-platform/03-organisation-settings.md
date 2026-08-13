# Layer 10 — 2.01.03 Organisation Settings

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.03 |
| Capability | Organisation Settings |
| Task Catalogue ID | 01.03 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08 |

## Capability Objective

Define and configure organisation-level Genesys Cloud settings required to establish the target operating model.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Capture organisation-level requirements |
| P04 | Design target settings |
| P05 | Configure foundational settings |
| P06 | Complete detailed configuration |
| P08 | Validate configuration |

## Source Implementation Activities

1. Identify required organisation settings.
2. Design target configuration.
3. Configure organisation settings.
4. Validate settings.
5. Document configuration.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.03-001 — Inventory Organisation-Level Settings

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify organisation-level settings relevant to the scoped Genesys Cloud solution.

**Dependencies**

- L10-01.01-006

**Deliverable**

Organisation settings inventory.

**Acceptance Criteria**

Relevant settings have been identified and classified.

### Activity 02 — Design

#### L10-01.03-002 — Define Target Organisation Settings

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define target values and configuration standards for organisation-level settings.

**Dependencies**

- L10-01.03-001

**Deliverable**

Organisation settings design.

**Acceptance Criteria**

Target configuration is approved.

### Activity 03 — Configure

#### L10-01.03-003 — Configure Organisation Settings

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure approved organisation-level settings.

**Dependencies**

- L10-01.03-002

**Deliverable**

Configured organisation settings.

**Acceptance Criteria**

Configuration matches the approved design.

### Activity 04 — Validate

#### L10-01.03-004 — Validate Organisation Settings

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate organisation-level settings against the approved configuration baseline.

**Dependencies**

- L10-01.03-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

All required settings pass validation.

### Activity 05 — Document

#### L10-01.03-005 — Document Organisation Settings Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Record final organisation settings and relevant operational dependencies.

**Dependencies**

- L10-01.03-004

**Deliverable**

Organisation settings baseline.

**Acceptance Criteria**

Configuration baseline is complete and handed over.

## Capability-Level Dependencies

- Organisation established
- Region selected
- Security requirements
- Identity strategy
- Solution architecture

## Capability-Level Estimation Considerations

Effort is driven by the number and complexity of organisation settings, environments, customer governance requirements, and automation approach.

## Definition of Done

Approved organisation settings are configured, validated, documented, and ready for dependent capabilities.
# Layer 10 — 10.36 Template Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.36 |
| Capability | Template Governance |
| Task Catalogue ID | 10.36 |
| Primary Layer 1 Phases | P04, P12 |

## Capability Objective

Govern templates used to create methodology, task, estimation and planning documents.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Establish controlled templates |
| P12 | Review and improve templates |

## Source Implementation Activities

1. Inventory templates.
2. Validate templates.
3. Approve template changes.
4. Release templates.

## Implementation Tasks

### Activity 01 — Inventory

#### L10-10.36-001 — Inventory Controlled Templates

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Identify active templates used by the methodology.

**Dependencies**

- Methodology repository

**Deliverable**

Template inventory.

**Acceptance Criteria**

Active templates are identified.

### Activity 02 — Validate

#### L10-10.36-002 — Validate Template Compliance

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P04 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate templates against current methodology standards.

**Dependencies**

- L10-10.36-001

**Deliverable**

Template validation report.

**Acceptance Criteria**

Templates contain required fields and terminology.

### Activity 03 — Change

#### L10-10.36-003 — Update Controlled Template

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Update templates where methodology changes require structural changes.

**Dependencies**

- Methodology change control

**Deliverable**

Updated template.

**Acceptance Criteria**

Template conforms to approved methodology.

### Activity 04 — Release

#### L10-10.36-004 — Release Template Version

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Version and release approved templates.

**Dependencies**

- L10-10.36-003

**Deliverable**

Released template version.

**Acceptance Criteria**

Template version is recorded.

## Capability-Level Dependencies

- Methodology change control
- Document control

## Capability-Level Estimation Considerations

Effort is driven by template count and downstream impact.

## Definition of Done

Templates are consistent, controlled and versioned.

---
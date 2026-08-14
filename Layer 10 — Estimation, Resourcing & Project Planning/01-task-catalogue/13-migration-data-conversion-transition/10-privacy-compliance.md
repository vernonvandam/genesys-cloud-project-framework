# Layer 10 — 2.13.10 Privacy & Compliance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.10 |
| Capability | Privacy & Compliance |
| Task Catalogue ID | 13.10 |
| Primary Layer 1 Phases | P02, P03, P04, P08, P10 |

## Capability Objective

Ensure migration activities comply with privacy, regulatory, contractual and customer data-handling requirements.

## Source Implementation Activities

1. Identify privacy requirements.
2. Assess migration controls.
3. Validate compliance.

## Implementation Tasks

### L10-13.10-001 — Assess Migration Privacy Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assess privacy and regulatory requirements affecting migration.

**Dependencies**

- Data classification

**Deliverable**

Privacy requirements assessment.

**Acceptance Criteria**

Applicable requirements are documented.

### L10-13.10-002 — Define Migration Privacy Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define controls for access, transfer, storage, transformation and disposal.

**Dependencies**

- L10-13.10-001

**Deliverable**

Migration privacy control design.

**Acceptance Criteria**

Controls are approved.

### L10-13.10-003 — Validate Migration Compliance

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Compliance Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate migration execution against approved privacy and compliance controls.

**Dependencies**

- L10-13.10-002
- Mock migration

**Deliverable**

Compliance validation evidence.

**Acceptance Criteria**

Applicable compliance controls pass validation.

## Definition of Done

Migration privacy and compliance requirements are validated.

---
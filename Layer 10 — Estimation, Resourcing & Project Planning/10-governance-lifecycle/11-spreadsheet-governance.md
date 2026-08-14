# Layer 10 — 10.11 Spreadsheet Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.11 |
| Capability | Spreadsheet Governance |
| Task Catalogue ID | 10.11 |
| Primary Layer 1 Phases | P03, P04, P09, P12 |

## Capability Objective

Govern the master estimation and project-planning workbook.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define workbook requirements |
| P04 | Design controlled workbook |
| P09 | Validate workbook |
| P12 | Archive final project workbook |

## Source Implementation Activities

1. Define workbook requirements.
2. Establish controlled inputs.
3. Validate calculations.
4. Approve workbook.
5. Archive versions.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.11-001 — Define Workbook Governance Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define workbook structure, input, output, validation and version requirements.

**Dependencies**

- Spreadsheet model
- Estimation model

**Deliverable**

Workbook governance requirements.

**Acceptance Criteria**

Requirements are documented.

### Activity 02 — Validate

#### L10-10.11-002 — Validate Workbook Calculations

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Validate workbook calculations against expected model outputs.

**Dependencies**

- L10-10.11-001

**Deliverable**

Workbook validation evidence.

**Acceptance Criteria**

Calculation outputs are correct.

### Activity 03 — Approve

#### L10-10.11-003 — Approve Controlled Workbook Version

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Approve the workbook version for project use.

**Dependencies**

- L10-10.11-002

**Deliverable**

Approved workbook.

**Acceptance Criteria**

Workbook version and approval are recorded.

### Activity 04 — Archive

#### L10-10.11-004 — Archive Final Workbook

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Project Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Archive final workbook and supporting source data.

**Dependencies**

- L10-10.11-003

**Deliverable**

Controlled workbook archive.

**Acceptance Criteria**

Final workbook is recoverable and identifiable.

## Capability-Level Dependencies

- Spreadsheet model
- Estimation model
- Project baseline

## Capability-Level Estimation Considerations

Effort depends on workbook complexity, automation and validation requirements.

## Definition of Done

The project workbook is controlled, validated, approved and archived.

---
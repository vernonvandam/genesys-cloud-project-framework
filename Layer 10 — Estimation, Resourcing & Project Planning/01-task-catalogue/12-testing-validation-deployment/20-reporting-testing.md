# Layer 10 — 2.12.20 Reporting Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.20 — Reporting Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.20 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P07–P08 |
| Primary Role | Reporting Specialist |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Validate operational reports, dashboards, filters, calculations, data visibility, scheduling and distribution.

## Source Implementation Activities

- Validate report configuration.
- Validate report calculations.
- Validate filters and views.
- Validate report security.
- Validate scheduled reporting.

## Implementation Tasks

### Activity 01 — Validate Reports

#### L10-12.20-001 — Validate Report Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06–P07 |
| Primary Role | Reporting Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate report definitions against approved requirements.

**Dependencies**

Reporting configuration.

**Deliverable**

Report Configuration Validation.

**Acceptance Criteria**

All in-scope reports are configured correctly.

### Activity 02 — Validate Calculations

#### L10-12.20-002 — Reconcile Report Results

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Reporting Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Compare report outputs against known test scenarios and expected results.

**Dependencies**

L10-12.20-001.

**Deliverable**

Report Reconciliation Results.

**Acceptance Criteria**

Critical report outputs reconcile with expected results.

### Activity 03 — Validate Distribution

#### L10-12.20-003 — Validate Scheduled Report Distribution

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Reporting Specialist |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate report scheduling, recipients and distribution controls.

**Dependencies**

L10-12.20-002.

**Deliverable**

Distribution Validation Results.

**Acceptance Criteria**

Reports reach authorised recipients on schedule.

## Capability-Level Dependencies

- Analytics
- Reporting
- Identity & Access
- Data

## Capability-Level Estimation Considerations

Report count, complexity, custom calculations and reconciliation effort drive estimates.

## Definition of Done

Required reports produce accurate and authorised results.

---
# Layer 10 — 10 Governance & Lifecycle Task Catalogue

## Purpose

This directory contains the task-decomposed implementation catalogue for the Layer 10 Governance & Lifecycle domain.

The catalogue governs the lifecycle of the Genesys Cloud estimation, resourcing, scheduling, reporting and project-planning model.

It provides controls for:

- governance
- estimation approval
- baseline management
- scope and change control
- task catalogue governance
- estimation model governance
- role and resource governance
- dependency and schedule governance
- spreadsheet governance
- assumptions and risks
- estimation review
- project reforecasting
- actuals and variance
- quality and phase gates
- project health
- calibration
- historical estimates
- methodology changes
- repository and document control
- auditability
- project closure
- continuous improvement

## Capability Domain

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Layer 2 Domain | Cross-Layer / Methodology Governance |
| Capability Count | 44 |
| Task Catalogue Prefix | L10-10 |
| Status | Baseline Task Catalogue |

## Repository Structure

```text
10-governance-lifecycle/
│
├── README.md
├── 01-governance-framework.md
├── 02-estimation-governance.md
├── 03-baseline-management.md
├── 04-scope-governance.md
├── 05-change-control.md
├── 06-task-catalogue-governance.md
├── 07-estimation-model-governance.md
├── 08-role-and-resource-governance.md
├── 09-dependency-governance.md
├── 10-schedule-governance.md
├── 11-spreadsheet-governance.md
├── 12-data-quality-governance.md
├── 13-assumption-governance.md
├── 14-risk-governance.md
├── 15-estimation-review.md
├── 16-estimation-approval.md
├── 17-project-baseline-approval.md
├── 18-estimation-version-control.md
├── 19-estimation-change-management.md
├── 20-project-reforecasting.md
├── 21-actuals-and-variance-management.md
├── 22-effort-and-schedule-reconciliation.md
├── 23-resource-capacity-governance.md
├── 24-project-performance-governance.md
├── 25-management-governance.md
├── 26-customer-governance.md
├── 27-delivery-governance.md
├── 28-quality-gates.md
├── 29-phase-gates.md
├── 30-project-health-assessment.md
├── 31-estimation-confidence-review.md
├── 32-lessons-learned.md
├── 33-calibration-feedback.md
├── 34-historical-estimate-management.md
├── 35-methodology-change-control.md
├── 36-template-governance.md
├── 37-repository-governance.md
├── 38-document-control.md
├── 39-auditability-and-traceability.md
├── 40-governance-reporting.md
├── 41-project-closeout.md
├── 42-estimation-model-retirement.md
├── 43-methodology-lifecycle.md
└── 44-framework-continuous-improvement.md
```

## Layer 1 Mapping

| Phase | Governance Application |
|---|---|
| P01 | Establish project governance, ownership and controls |
| P02 | Validate governance requirements and current-state controls |
| P03 | Define governance, estimation and approval requirements |
| P04 | Design governance model and control framework |
| P05 | Establish controlled project foundations |
| P06 | Apply governance during implementation |
| P07 | Govern integration, migration and dependency changes |
| P08 | Govern validation, quality gates and evidence |
| P09 | Confirm operational governance and readiness |
| P10 | Govern production deployment and baseline changes |
| P11 | Govern hypercare, actuals and reforecasting |
| P12 | Close project, capture actuals and feed continuous improvement |

## Task ID Standard

```text
L10-10.<capability>.<task>
```

Examples:

```text
L10-10.01-001
L10-10.01-002
L10-10.02-001
```

## Standard Task Attributes

Every task follows the established Layer 10 task-file model:

| Attribute | Requirement |
|---|---|
| Task Type | REQUIRED / CONDITIONAL / VALIDATION |
| Layer 1 Phase | P01–P12 |
| Primary Role | Delivery role |
| Customer Responsibility | YES / NO / JOINT |
| Environment | DESIGN / DEV / TEST / UAT / PROD / MULTI |
| Automation | MANUAL / AUTOMATED / HYBRID |
| Baseline Effort | Initial estimate |
| Critical Path | YES / NO / CONDITIONAL |

## Task Design Principle

Tasks are deliberately atomic enough to become individual project schedule rows.

Each task should have:

- unique Task ID
- single implementation outcome
- explicit dependencies
- accountable delivery role
- customer responsibility
- environment
- baseline effort
- deliverable
- acceptance criteria
- critical-path classification

## Classification

**REQUIRED** tasks apply to the normal enterprise deployment methodology.

**CONDITIONAL** tasks apply where project scope, governance requirements, customer environment, commercial model or delivery complexity requires them.

**VALIDATION** tasks confirm that previously established governance controls operate as designed.

## Governance Lifecycle

```text
Methodology
    ↓
Task Catalogue
    ↓
Task Standard
    ↓
Estimation
    ↓
Roles
    ↓
Dependencies
    ↓
Schedule
    ↓
Spreadsheet
    ↓
Calibration
    ↓
Outputs
    ↓
Governance
    ↓
Project Baseline
    ↓
Project Delivery
    ↓
Actuals
    ↓
Variance
    ↓
Lessons Learned
    ↓
Calibration
    ↓
Framework Improvement
```

## Definition of Done

Section 10 is complete when:

- all 44 capabilities have task files
- every capability has Layer 1 mappings
- every capability has decomposed implementation tasks
- governance ownership is defined
- baselines are controlled
- changes are controlled
- estimates can be reviewed and approved
- project reforecasting is controlled
- actuals and variance are managed
- project health can be assessed
- quality and phase gates are defined
- lessons learned feed calibration
- historical estimates are retained
- methodology changes are controlled
- repository and documents are governed
- project closure is defined
- continuous improvement is established

---
# Layer 10 — 09 Estimation Outputs & Reporting

## Purpose

This directory defines the standard outputs produced by the Genesys Cloud Deployment Methodology estimation, resourcing, dependency and scheduling model.

The section converts the underlying Layer 10 estimation model into controlled project-management outputs suitable for:

- project planning
- effort estimation
- resource planning
- schedule development
- management reporting
- customer reporting
- delivery governance
- project controls
- estimation review
- implementation decision-making
- spreadsheet generation

## Position in Layer 10

```text
Layer 2 — Capability Catalogue
        ↓
Layer 10.01 — Task Catalogue
        ↓
Layer 10.02 — Task Standard
        ↓
Layer 10.03 — Estimation Model
        ↓
Layer 10.04 — Role Catalogue
        ↓
Layer 10.05 — Dependency Model
        ↓
Layer 10.06 — Project Schedule Model
        ↓
Layer 10.07 — Spreadsheet Model
        ↓
Layer 10.08 — Calibration
        ↓
Layer 10.09 — Estimation Outputs & Reporting
        ↓
Project Estimate / Schedule / Resource Plan / Reporting
```

## Output Catalogue

| ID | Output |
|---|---|
| 09.01 | Output Framework |
| 09.02 | Project Estimate |
| 09.03 | Effort Summary |
| 09.04 | Resource Summary |
| 09.05 | Role Effort Summary |
| 09.06 | Phase Effort Summary |
| 09.07 | Workstream Effort Summary |
| 09.08 | Customer Effort Summary |
| 09.09 | Environment Effort Summary |
| 09.10 | Dependency Analysis |
| 09.11 | Critical Path Analysis |
| 09.12 | Project Schedule Output |
| 09.13 | Milestone Output |
| 09.14 | Deliverable Output |
| 09.15 | Assumption Register Output |
| 09.16 | Risk Output |
| 09.17 | Estimation Confidence |
| 09.18 | Estimation Scenarios |
| 09.19 | Estimation Comparison |
| 09.20 | Management Reporting |
| 09.21 | Delivery Dashboard |
| 09.22 | Customer Reporting |
| 09.23 | Resource Capacity Reporting |
| 09.24 | Estimation Pack |
| 09.25 | Output Validation |

## Repository Structure

```text
09-estimation-outputs-reporting/
│
├── README.md
├── 01-output-framework.md
├── 02-project-estimate.md
├── 03-effort-summary.md
├── 04-resource-summary.md
├── 05-role-effort-summary.md
├── 06-phase-effort-summary.md
├── 07-workstream-effort-summary.md
├── 08-customer-effort-summary.md
├── 09-environment-effort-summary.md
├── 10-dependency-analysis.md
├── 11-critical-path-analysis.md
├── 12-project-schedule-output.md
├── 13-milestone-output.md
├── 14-deliverable-output.md
├── 15-assumption-register-output.md
├── 16-risk-output.md
├── 17-estimation-confidence.md
├── 18-estimation-scenarios.md
├── 19-estimation-comparison.md
├── 20-management-reporting.md
├── 21-delivery-dashboard.md
├── 22-customer-reporting.md
├── 23-resource-capacity-reporting.md
├── 24-estimation-pack.md
└── 25-output-validation.md
```

## Output Principles

Outputs shall:

1. derive from controlled task data;
2. preserve Layer 2 traceability;
3. use the Layer 10 Task Standard;
4. use approved effort assumptions;
5. preserve dependency relationships;
6. distinguish delivery and customer effort;
7. distinguish roles and workstreams;
8. identify critical-path activities;
9. expose assumptions and risks;
10. support multiple estimation scenarios;
11. be reproducible from the master workbook;
12. be suitable for project governance.

## Primary Traceability

```text
Layer 2 Capability
      ↓
Layer 10 Task
      ↓
Task Effort
      ↓
Role / Workstream
      ↓
Dependency
      ↓
Schedule
      ↓
Estimate Output
      ↓
Management / Customer Reporting
```

## Definition of Done

Section 09 is complete when:

- all defined output types are documented;
- output data sources are defined;
- calculations are traceable;
- outputs can be generated from the spreadsheet model;
- role and customer effort are distinguishable;
- schedule and dependency outputs are available;
- critical-path analysis is defined;
- assumptions and risks are surfaced;
- confidence and scenarios are represented;
- management and customer reporting are defined;
- output validation is defined.

---
# 09.25 — Output Validation

## Purpose

Define validation controls for all generated estimation and reporting outputs.

## Validation Categories

### Structural Validation

Confirm:

- required fields exist;
- IDs are valid;
- references resolve;
- no duplicate tasks exist;
- no orphan tasks exist.

### Calculation Validation

Confirm:

- task totals reconcile;
- role totals reconcile;
- phase totals reconcile;
- workstream totals reconcile;
- customer totals reconcile;
- schedule effort reconciles;
- contingency is correctly applied.

### Dependency Validation

Confirm:

- required dependencies exist;
- dependency chains resolve;
- circular dependencies are identified;
- critical-path calculations are valid.

### Schedule Validation

Confirm:

- start and finish dates are valid;
- durations reconcile;
- dependencies drive dates;
- milestones have prerequisites;
- critical path is calculated.

### Reporting Validation

Confirm:

- dashboards use approved source data;
- management outputs reconcile;
- customer outputs reconcile;
- scenario outputs identify assumptions;
- estimate versions are controlled.

## Reconciliation Model

```text
Task Catalogue
      ↓
Task-Level Effort
      ↓
Role / Phase / Workstream Aggregation
      ↓
Project Estimate
      ↓
Schedule
      ↓
Reporting Outputs
```

Every level must reconcile to the level below it.

## Validation Status

Each output shall have one of:

- NOT VALIDATED
- VALIDATED
- VALIDATED WITH EXCEPTIONS
- REJECTED

## Exception Management

Validation exceptions shall identify:

- exception ID;
- affected output;
- affected task;
- issue;
- impact;
- owner;
- remediation;
- target resolution;
- status.

## Definition of Done

Output validation is complete when:

- all required outputs have been generated;
- all calculations reconcile;
- dependencies have been validated;
- schedules have been validated;
- customer effort has been validated;
- assumptions and risks are present;
- scenario calculations are validated;
- output versions are controlled;
- all exceptions are resolved or formally accepted.

---
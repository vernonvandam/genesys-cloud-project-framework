# Layer 10 — 2.12.10 Unit / Component Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.10 — Unit / Component Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.10 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P06–P07 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Primary Environment | DEV / TEST |
| Automation | HYBRID |
| Critical Path | NO |

## Capability Objective

Validate individual configured or developed components before they are incorporated into integrated testing.

## Source Implementation Activities

- Define component test scenarios.
- Execute component tests.
- Record results.
- Correct defects.
- Confirm component readiness.

## Implementation Tasks

### Activity 01 — Define Component Tests

#### L10-12.10-001 — Identify Component Test Scenarios

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | DEV / TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define focused validation scenarios for configured components.

**Dependencies**

Component implementation.

**Deliverable**

Component Test Scenarios.

**Acceptance Criteria**

Each component has appropriate validation coverage.

### Activity 02 — Execute Tests

#### L10-12.10-002 — Execute Component Tests

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | DEV / TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Execute component-level functional and configuration tests.

**Dependencies**

L10-12.10-001.

**Deliverable**

Component Test Results.

**Acceptance Criteria**

Components meet defined expected behaviour.

### Activity 03 — Resolve Component Defects

#### L10-12.10-003 — Remediate Component Defects

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | DEV / TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Correct failed component behaviour and rerun affected tests.

**Dependencies**

L10-12.10-002.

**Deliverable**

Resolved Component Defects.

**Acceptance Criteria**

Critical component failures are resolved.

## Capability-Level Dependencies

- Component implementation
- Configuration Validation
- Test Environment Readiness

## Capability-Level Estimation Considerations

Component count and complexity determine execution effort.

## Definition of Done

Components pass defined tests and are ready for integration testing.

---
# Layer 10 — 2.12.19 Analytics Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.19 — Analytics Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.19 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P07–P08 |
| Primary Role | Analytics Specialist |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Validate Genesys Cloud analytics data, metrics, views, filters, permissions and operational reporting behaviour.

## Source Implementation Activities

- Validate analytics configuration.
- Validate metric definitions.
- Test views and filters.
- Validate data accuracy.
- Validate access and visibility.

## Implementation Tasks

### Activity 01 — Validate Analytics Configuration

#### L10-12.19-001 — Validate Analytics Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06–P07 |
| Primary Role | Analytics Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate analytics configuration against approved requirements.

**Dependencies**

Analytics implementation.

**Deliverable**

Analytics Baseline Validation.

**Acceptance Criteria**

Required analytics configuration exists.

### Activity 02 — Validate Metrics

#### L10-12.19-002 — Validate Analytics Metrics

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Analytics Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Compare analytics metrics with expected operational outcomes.

**Dependencies**

L10-12.19-001 and test execution.

**Deliverable**

Metric Validation Results.

**Acceptance Criteria**

Critical metrics reconcile with expected results.

### Activity 03 — Validate Access

#### L10-12.19-003 — Validate Analytics Visibility

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate users see only authorised analytics information.

**Dependencies**

Identity & Access and L10-12.19-001.

**Deliverable**

Analytics Access Validation.

**Acceptance Criteria**

Required users have correct analytics visibility.

## Capability-Level Dependencies

- Analytics
- ACD & Routing
- Core Platform
- Identity & Access

## Capability-Level Estimation Considerations

Metric count, complexity and reconciliation effort drive estimates.

## Definition of Done

Required analytics metrics and access behaviour are validated.

---
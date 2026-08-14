# Layer 10 — 2.13.36 Migration Automation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.36 |
| Capability | Migration Automation |
| Task Catalogue ID | 13.36 |
| Primary Layer 1 Phases | P04, P06, P08 |
| Classification | CONDITIONAL |

## Capability Objective

Automate repeatable migration activities where scale, repeatability or deployment risk justifies automation.

## Implementation Tasks

### L10-13.36-001 — Identify Automation Candidates

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Migration Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify migration activities suitable for automation.

**Dependencies**

- Migration tooling
- Migration approach

**Deliverable**

Automation candidate list.

**Acceptance Criteria**

Automation candidates are approved.

### L10-13.36-002 — Implement Migration Automation

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Migration Engineer |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | AUTOMATED |
| Baseline Effort | 6.0h |
| Critical Path | CONDITIONAL |

**Description**

Implement approved automated migration functions.

**Dependencies**

- L10-13.36-001

**Deliverable**

Migration automation.

**Acceptance Criteria**

Automation executes required scenarios successfully.

### L10-13.36-003 — Validate Automation Repeatability

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Migration Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | AUTOMATED |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Execute repeated runs to confirm deterministic and recoverable behaviour.

**Dependencies**

- L10-13.36-002

**Deliverable**

Automation validation evidence.

**Acceptance Criteria**

Repeated executions produce consistent results.

## Definition of Done

Approved migration activities are automated and repeatable.

---

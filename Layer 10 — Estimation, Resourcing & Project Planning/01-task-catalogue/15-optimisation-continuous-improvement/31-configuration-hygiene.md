# Layer 10 — 2.15.31 Configuration Hygiene

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.31 |
| Capability | Configuration Hygiene |
| Task Catalogue ID | 15.31 |
| Primary Layer 1 Phases | P02, P04, P06, P08, P09 |

## Capability Objective

Maintain a clean, consistent, documented and supportable Genesys Cloud configuration estate.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess configuration estate |
| P04 | Define hygiene standards |
| P06 | Clean and standardise configuration |
| P08 | Validate configuration |
| P09 | Establish recurring hygiene |

## Source Implementation Activities

1. Inventory configuration.
2. Identify obsolete objects.
3. Identify inconsistent configuration.
4. Clean and standardise objects.
5. Establish recurring review.

## Implementation Tasks

### L10-15.31-001 — Assess Configuration Estate

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Review configuration objects for obsolete, duplicate, inconsistent or unmanaged content.

**Dependencies**

- Configuration inventory

**Deliverable**

Configuration hygiene assessment.

**Acceptance Criteria**

Configuration issues are documented.

### L10-15.31-002 — Define Configuration Hygiene Standards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define standards for naming, ownership, lifecycle, documentation and retirement.

**Dependencies**

- L10-15.31-001

**Deliverable**

Configuration hygiene standard.

**Acceptance Criteria**

Standards are approved.

### L10-15.31-003 — Remediate Configuration Hygiene Issues

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Correct or retire configuration that does not meet agreed standards.

**Dependencies**

- L10-15.31-002

**Deliverable**

Remediated configuration.

**Acceptance Criteria**

Agreed hygiene issues are resolved.

### L10-15.31-004 — Establish Recurring Configuration Review

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Establish recurring configuration hygiene reviews.

**Dependencies**

- L10-15.31-003

**Deliverable**

Configuration review process.

**Acceptance Criteria**

Review cadence and ownership are established.
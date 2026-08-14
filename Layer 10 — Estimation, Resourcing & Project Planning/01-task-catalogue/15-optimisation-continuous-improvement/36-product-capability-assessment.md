# Layer 10 — 2.15.36 Product Capability Assessment

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.36 |
| Capability | Product Capability Assessment |
| Task Catalogue ID | 15.36 |
| Primary Layer 1 Phases | P02, P03, P04, P08 |

## Capability Objective

Assess Genesys Cloud capabilities against customer business requirements and identify opportunities to improve the solution using native platform functionality.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess current capability usage |
| P03 | Identify capability gaps |
| P04 | Assess native platform options |
| P08 | Validate selected capabilities |

## Source Implementation Activities

1. Assess current capability usage.
2. Identify business capability gaps.
3. Review available platform capabilities.
4. Compare native and custom solutions.
5. Validate selected capabilities.

## Implementation Tasks

### L10-15.36-001 — Assess Current Capability Usage

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess how current Genesys Cloud capabilities are being used.

**Dependencies**

- Capability inventory

**Deliverable**

Capability assessment.

**Acceptance Criteria**

Current usage is documented.

### L10-15.36-002 — Identify Capability Gaps

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify unmet business, customer, agent or operational capability requirements.

**Dependencies**

- L10-15.36-001

**Deliverable**

Capability gap register.

**Acceptance Criteria**

Gaps are documented and prioritised.

### L10-15.36-003 — Assess Native Platform Capability

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Assess whether native Genesys Cloud functionality can address identified gaps.

**Dependencies**

- L10-15.36-002

**Deliverable**

Capability fit assessment.

**Acceptance Criteria**

Recommended platform capability is documented.

### L10-15.36-004 — Validate Selected Capability

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate that selected functionality meets the business requirement.

**Dependencies**

- L10-15.36-003

**Deliverable**

Capability validation evidence.

**Acceptance Criteria**

Capability meets agreed requirements.
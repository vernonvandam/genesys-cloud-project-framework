# Layer 10 — 2.15.48 Legacy Reduction

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.48 |
| Capability | Legacy Reduction |
| Task Catalogue ID | 15.48 |
| Primary Layer 1 Phases | P02, P03, P04, P07, P09, P12 |

## Capability Objective

Reduce unnecessary legacy systems, duplicated capabilities, manual processes and technical dependencies following Genesys Cloud adoption.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify legacy dependencies |
| P03 | Define reduction opportunities |
| P04 | Assess target-state impact |
| P07 | Manage migration dependencies |
| P09 | Execute reduction |
| P12 | Complete legacy transition |

## Source Implementation Activities

1. Inventory legacy dependencies.
2. Identify redundant capability.
3. Define reduction strategy.
4. Validate dependencies.
5. Retire or reduce legacy components.

## Implementation Tasks

### L10-15.48-001 — Identify Legacy Dependencies

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Identify legacy systems, processes and integrations that remain dependent on the Genesys Cloud solution.

**Dependencies**

- Migration inventory
- Integration inventory

**Deliverable**

Legacy dependency register.

**Acceptance Criteria**

Material dependencies are documented.

### L10-15.48-002 — Define Legacy Reduction Opportunities

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify systems, processes or integrations that can be reduced or eliminated.

**Dependencies**

- L10-15.48-001

**Deliverable**

Legacy reduction plan.

**Acceptance Criteria**

Reduction opportunities are approved.

### L10-15.48-003 — Validate Legacy Reduction Dependencies

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P07 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate that proposed legacy reduction will not disrupt dependent services.

**Dependencies**

- L10-15.48-002

**Deliverable**

Dependency validation.

**Acceptance Criteria**

No unacceptable dependency risk remains.

### L10-15.48-004 — Execute Legacy Reduction

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Retire or reduce approved legacy dependencies.

**Dependencies**

- L10-15.48-003

**Deliverable**

Reduced legacy footprint.

**Acceptance Criteria**

Legacy components are removed or reduced without unacceptable impact.
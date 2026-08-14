# Layer 10 — 2.04.30 Routing Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.30 |
| Capability | Routing Optimisation |
| Task Catalogue ID | 04.30 |
| Primary Layer 1 Phases | P08, P09, P10, P12 |

## Capability Objective

Review routing behaviour and identify opportunities to improve service levels, agent utilisation, customer experience and operational efficiency.

## Source Implementation Activities

1. Establish optimisation criteria.
2. Analyse routing performance.
3. Identify optimisation opportunities.
4. Implement approved changes.
5. Validate improvements.

## Implementation Tasks

### L10-04.30-001 — Define Routing Optimisation Criteria

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define measures used to determine routing effectiveness.

**Dependencies**

- Routing acceptance

**Deliverable**

Optimisation criteria.

**Acceptance Criteria**

Measures are approved.

### L10-04.30-002 — Analyse Routing Performance

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Analyse routing outcomes, queue performance, service levels and agent utilisation.

**Dependencies**

- L10-04.30-001

**Deliverable**

Routing performance analysis.

**Acceptance Criteria**

Performance issues and opportunities are documented.

### L10-04.30-003 — Implement Approved Routing Optimisations

| Attribute | Value |
|---|---|
| Task Type | OPTIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per optimisation |
| Critical Path | NO |

**Description**

Implement approved routing improvements.

**Dependencies**

- L10-04.30-002

**Deliverable**

Optimised routing configuration.

**Acceptance Criteria**

Approved improvements are implemented without regression.

### L10-04.30-004 — Validate Optimised Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Validate optimisation outcomes and confirm no material regression.

**Dependencies**

- L10-04.30-003

**Deliverable**

Optimisation validation record.

**Acceptance Criteria**

Improvement is evidenced and accepted.

## Definition of Done

Routing performance has been reviewed and approved optimisation actions completed where applicable.

---

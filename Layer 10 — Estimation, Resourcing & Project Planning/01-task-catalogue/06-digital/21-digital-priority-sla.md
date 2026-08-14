# Layer 10 — 2.06.21 Digital Priority & SLA

## Capability Objective

Define digital priority and service-level behaviour appropriate to asynchronous and synchronous channels.

## Implementation Tasks

### L10-06.21-001 — Define Digital SLA Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define channel-specific response targets, service levels, operating hours and escalation thresholds.

**Dependencies**

- Digital channel strategy

**Deliverable**

Digital SLA matrix.

**Acceptance Criteria**

SLA targets are approved.

### L10-06.21-002 — Configure Digital Priority and SLA

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure digital priority and service-level behaviour.

**Dependencies**

- L10-06.21-001

**Deliverable**

Priority and SLA configuration.

**Acceptance Criteria**

Approved test scenarios demonstrate correct priority and SLA behaviour.

### L10-06.21-003 — Validate Digital SLA

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate SLA calculations, priority handling and reporting.

**Dependencies**

- L10-06.21-002

**Deliverable**

SLA validation evidence.

**Acceptance Criteria**

Approved SLA scenarios pass.

## Definition of Done

Digital priorities and SLAs are configured, measured and validated.

---

# Layer 10 — 2.14.04 Support Model

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.04 |
| Capability | Support Model |
| Task Catalogue ID | 14.04 |
| Primary Layer 1 Phases | P03, P04, P09, P12 |

## Capability Objective

Define the support structure, responsibilities, escalation paths and service coverage for Genesys Cloud.

## Source Implementation Activities

1. Define support tiers.
2. Define service coverage.
3. Define escalation paths.
4. Define support responsibilities.
5. Validate support readiness.

## Implementation Tasks

### L10-14.04-001 — Define Support Tiers

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define L1, L2, L3, engineering and vendor responsibilities.

**Dependencies**

- Operating model

**Deliverable**

Support tier model.

**Acceptance Criteria**

Responsibilities for each support tier are documented.

### L10-14.04-002 — Define Support Escalation Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define escalation routes, response expectations and ownership transitions.

**Dependencies**

- L10-14.04-001

**Deliverable**

Support escalation matrix.

**Acceptance Criteria**

Escalation paths are approved.

### L10-14.04-003 — Validate Support Readiness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that support teams can execute the defined model.

**Dependencies**

- L10-14.04-002
- Training
- Knowledge transfer

**Deliverable**

Support readiness assessment.

**Acceptance Criteria**

Support teams demonstrate required processes.

## Definition of Done

The support model is documented, approved and operationally validated.

---
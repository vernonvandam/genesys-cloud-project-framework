# Layer 10 — 2.14.02 Service Ownership

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.02 |
| Capability | Service Ownership |
| Task Catalogue ID | 14.02 |
| Primary Layer 1 Phases | P01, P03, P09, P12 |

## Capability Objective

Establish accountable ownership for the Genesys Cloud service.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Identify service ownership |
| P03 | Define ownership requirements |
| P09 | Confirm operational accountability |
| P12 | Transfer service ownership |

## Source Implementation Activities

1. Identify service owner.
2. Define platform ownership.
3. Define business ownership.
4. Define support ownership.
5. Confirm BAU accountability.

## Implementation Tasks

### Activity 01 — Establish Ownership

#### L10-14.02-001 — Identify Service Owner

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Identify the accountable business/service owner.

**Dependencies**

- Project initiation

**Deliverable**

Service ownership record.

**Acceptance Criteria**

Named service owner is confirmed.

#### L10-14.02-002 — Define Operational Ownership Responsibilities

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

Define responsibilities for service, platform, business, support and vendor ownership.

**Dependencies**

- L10-14.02-001

**Deliverable**

Ownership matrix.

**Acceptance Criteria**

Responsibilities and escalation ownership are documented.

#### L10-14.02-003 — Obtain Service Acceptance

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain formal customer acceptance of service ownership.

**Dependencies**

- L10-14.02-002
- Operational handover

**Deliverable**

Service acceptance record.

**Acceptance Criteria**

BAU ownership is formally accepted.

## Definition of Done

Service ownership is documented, accountable and formally accepted.

---
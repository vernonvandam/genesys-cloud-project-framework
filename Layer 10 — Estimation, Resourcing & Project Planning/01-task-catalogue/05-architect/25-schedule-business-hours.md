# Layer 10 — 2.05.25 Schedule & Business Hours

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.25 |
| Capability | Schedule & Business Hours |
| Task Catalogue ID | 05.25 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Configure schedule and business-hour behaviour used by Architect flows.

## Source Implementation Activities

1. Define operating hours.
2. Map schedules to flows.
3. Configure schedule handling.
4. Validate boundary conditions.

## Implementation Tasks

### Activity 01 — Define Schedule Requirements

#### L10-05.25-001 — Define Business Hours Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define operating hours, time zones, exceptions and expected open/closed behaviour.

**Dependencies**

- Business requirements

**Deliverable**

Business-hours matrix.

**Acceptance Criteria**

Operating hours are approved.

---

#### L10-05.25-002 — Configure Schedule Behaviour

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Associate schedules and schedule groups with applicable Architect flows.

**Dependencies**

- L10-05.25-001

**Deliverable**

Configured schedule behaviour.

**Acceptance Criteria**

Flows respond correctly to defined operating hours.

---

#### L10-05.25-003 — Validate Schedule Boundaries

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate opening, closing, overnight, timezone and boundary conditions.

**Dependencies**

- L10-05.25-002

**Deliverable**

Schedule validation evidence.

**Acceptance Criteria**

All schedule boundary scenarios pass.
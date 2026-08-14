<!-- FILE: 12-number-porting-migration.md -->

# Layer 10 — 2.03.12 Number Porting & Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.12 |
| Capability | Number Porting & Migration |
| Task Catalogue ID | 03.12 |
| Primary Layer 1 Phases | P02, P03, P07, P08, P09, P10, P11 |

## Capability Objective

Plan, coordinate, execute and validate telephone-number porting and associated telephony migration.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover numbers |
| P03 | Define migration requirements |
| P07 | Execute port preparation |
| P08 | Validate porting readiness |
| P09 | Prepare cutover |
| P10 | Execute port |
| P11 | Stabilise |

## Source Implementation Activities

1. Inventory numbers.
2. Validate ownership.
3. Prepare port requests.
4. Coordinate carrier.
5. Rehearse migration.
6. Execute port.
7. Validate routing.

## Implementation Tasks

### Activity 01 — Port Discovery

#### L10-03.12-001 — Validate Number Portability

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm number ownership, carrier records, service addresses and portability.

**Dependencies**

- Number inventory

**Deliverable**

Portability assessment.

**Acceptance Criteria**

Numbers are confirmed as portable or exceptions documented.

### Activity 02 — Port Preparation

#### L10-03.12-002 — Prepare Porting Documentation

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Prepare required customer/carrier documentation and porting requests.

**Dependencies**

- L10-03.12-001

**Deliverable**

Porting submission pack.

**Acceptance Criteria**

Carrier accepts submission.

### Activity 03 — Cutover

#### L10-03.12-003 — Execute Number Port

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h/port event |
| Critical Path | YES |

**Description**

Coordinate and execute the approved number porting event.

**Dependencies**

- Port approval
- Cutover approval

**Deliverable**

Completed port event.

**Acceptance Criteria**

Numbers are active on target service.

### Activity 04 — Validate

#### L10-03.12-004 — Validate Ported Numbers

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P11 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate inbound routing, outbound presentation and reachability.

**Dependencies**

- L10-03.12-003

**Deliverable**

Port validation evidence.

**Acceptance Criteria**

All ported numbers pass production validation.

## Capability-Level Dependencies

- Carrier
- Number inventory
- Customer authorisation
- Routing
- Cutover plan

## Capability-Level Estimation Considerations

Carrier lead times are schedule dependencies and must not be treated as pure engineering effort.

## Definition of Done

Numbers are successfully ported, validated and operational.
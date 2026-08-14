<!-- FILE: 31-telephony-migration-cutover.md -->

# Layer 10 — 2.03.31 Telephony Migration & Cutover

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.31 |
| Capability | Telephony Migration & Cutover |
| Task Catalogue ID | 03.31 |
| Primary Layer 1 Phases | P07, P08, P09, P10, P11 |

## Capability Objective

Plan, rehearse and execute the transition from existing telephony services to the target Genesys Cloud voice environment.

## Source Implementation Activities

1. Define migration scope.
2. Develop cutover plan.
3. Rehearse.
4. Validate readiness.
5. Execute cutover.
6. Stabilise.

## Implementation Tasks

#### L10-03.31-001 — Define Telephony Migration Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define numbers, sites, carriers, users, routes and services included in migration.

**Dependencies**

- Telephony discovery
- Target architecture

**Deliverable**

Migration scope.

**Acceptance Criteria**

Scope approved.

#### L10-03.31-002 — Develop Telephony Cutover Plan

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define detailed cutover sequence, responsibilities, checkpoints, validation and rollback.

**Dependencies**

- L10-03.31-001
- Voice testing

**Deliverable**

Telephony cutover plan.

**Acceptance Criteria**

Plan approved.

#### L10-03.31-003 — Rehearse Telephony Cutover

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Rehearse the critical cutover sequence and identify timing or dependency issues.

**Dependencies**

- L10-03.31-002

**Deliverable**

Cutover rehearsal results.

**Acceptance Criteria**

Critical issues resolved.

#### L10-03.31-004 — Execute Telephony Cutover

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Execute approved telephony cutover activities.

**Dependencies**

- Cutover approval
- Porting readiness
- Production readiness

**Deliverable**

Production telephony activation.

**Acceptance Criteria**

Telephony is successfully activated.

#### L10-03.31-005 — Validate and Stabilise Telephony

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P11 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Monitor and resolve post-cutover voice issues.

**Dependencies**

- L10-03.31-004

**Deliverable**

Telephony stabilisation record.

**Acceptance Criteria**

Critical voice issues are resolved or formally accepted.

## Capability-Level Dependencies

- Number porting
- Carrier
- Voice testing
- Cutover governance
- Rollback plan

## Capability-Level Estimation Considerations

Cutover effort should account for both planned execution and hypercare support.

## Definition of Done

Telephony migration is completed, validated and stabilised.
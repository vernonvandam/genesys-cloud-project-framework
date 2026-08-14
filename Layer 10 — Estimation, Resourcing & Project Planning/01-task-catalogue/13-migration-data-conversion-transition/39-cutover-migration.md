# Layer 10 — 2.13.39 Cutover Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.39 |
| Capability | Cutover Migration |
| Task Catalogue ID | 13.39 |
| Primary Layer 1 Phases | P10, P11 |

## Capability Objective

Execute the approved production migration and transition users, data and operations to Genesys Cloud.

## Implementation Tasks

### L10-13.39-001 — Confirm Cutover Readiness

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm all cutover prerequisites, approvals, communications and rollback criteria.

**Dependencies**

- Migration rehearsal
- Rollback plan
- Data freeze where applicable

**Deliverable**

Cutover readiness approval.

**Acceptance Criteria**

All go/no-go criteria pass.

### L10-13.39-002 — Execute Production Migration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 8.0h |
| Critical Path | YES |

**Description**

Execute approved production migration and transition activities.

**Dependencies**

- L10-13.39-001

**Deliverable**

Production migration execution record.

**Acceptance Criteria**

Migration completes according to approved runbook.

### L10-13.39-003 — Confirm Cutover Completion

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm migration completion and transition to production validation/hypercare.

**Dependencies**

- L10-13.39-002

**Deliverable**

Cutover completion approval.

**Acceptance Criteria**

Customer accepts migration completion.

## Definition of Done

Production cutover is complete and the solution enters hypercare.

---
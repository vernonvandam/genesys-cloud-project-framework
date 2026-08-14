# Layer 10 — 10.29 Phase Gates

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.29 |
| Capability | Phase Gates |
| Task Catalogue ID | 10.29 |
| Primary Layer 1 Phases | P01–P12 |

## Capability Objective

Control progression between the twelve Layer 1 lifecycle phases.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01–P12 | Define and operate lifecycle phase gates |

## Source Implementation Activities

1. Define phase entry criteria.
2. Define phase exit criteria.
3. Review evidence.
4. Approve progression.
5. Record exceptions.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.29-001 — Define Phase Gate Criteria

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define entry and exit criteria for all Layer 1 lifecycle phases.

**Dependencies**

- Layer 1 lifecycle

**Deliverable**

Phase gate matrix.

**Acceptance Criteria**

All phases have defined gate criteria.

### Activity 02 — Review

#### L10-10.29-002 — Perform Phase Gate Review

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review phase evidence against approved entry and exit criteria.

**Dependencies**

- L10-10.29-001

**Deliverable**

Phase gate review.

**Acceptance Criteria**

Evidence satisfies applicable criteria.

### Activity 03 — Approve

#### L10-10.29-003 — Approve Phase Transition

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Approve transition into the next lifecycle phase.

**Dependencies**

- L10-10.29-002

**Deliverable**

Phase transition approval.

**Acceptance Criteria**

Phase transition is authorised.

### Activity 04 — Manage Exception

#### L10-10.29-004 — Manage Phase Gate Exception

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Document and manage approved exceptions to phase exit criteria.

**Dependencies**

- L10-10.29-002

**Deliverable**

Phase gate exception record.

**Acceptance Criteria**

Exception has owner, mitigation and approval.

## Capability-Level Dependencies

- Layer 1 lifecycle
- Quality gates
- Project governance

## Capability-Level Estimation Considerations

Gate effort varies with phase complexity and evidence requirements.

## Definition of Done

Every lifecycle phase has controlled entry, exit and transition governance.

---
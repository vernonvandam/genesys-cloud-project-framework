# Layer 10 — 10.28 Quality Gates

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.28 |
| Capability | Quality Gates |
| Task Catalogue ID | 10.28 |
| Primary Layer 1 Phases | P04, P08, P09, P10, P12 |

## Capability Objective

Establish mandatory quality gates controlling progression through project lifecycle stages.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Establish gate criteria |
| P08 | Validate quality evidence |
| P09 | Confirm readiness |
| P10 | Confirm deployment gate |
| P12 | Confirm closure quality |

## Source Implementation Activities

1. Define gate criteria.
2. Identify evidence.
3. Perform gate review.
4. Record outcome.
5. Resolve gate failures.

## Implementation Tasks

### Activity 01 — Define

#### L10-10.28-001 — Define Quality Gate Criteria

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define entry, evidence and exit criteria for mandatory quality gates.

**Dependencies**

- Governance framework
- Layer 1 lifecycle

**Deliverable**

Quality gate framework.

**Acceptance Criteria**

Gate criteria are approved.

### Activity 02 — Review

#### L10-10.28-002 — Perform Quality Gate Review

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

Review required evidence against gate criteria.

**Dependencies**

- L10-10.28-001

**Deliverable**

Gate review record.

**Acceptance Criteria**

All mandatory evidence is assessed.

### Activity 03 — Record

#### L10-10.28-003 — Record Quality Gate Outcome

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Record pass, conditional pass or fail status.

**Dependencies**

- L10-10.28-002

**Deliverable**

Gate outcome.

**Acceptance Criteria**

Gate outcome is formally recorded.

### Activity 04 — Resolve

#### L10-10.28-004 — Resolve Quality Gate Exceptions

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Track and resolve conditions preventing gate progression.

**Dependencies**

- L10-10.28-003

**Deliverable**

Gate remediation record.

**Acceptance Criteria**

All blocking exceptions are resolved or formally accepted.

## Capability-Level Dependencies

- Layer 1 phases
- Testing
- Deployment readiness

## Capability-Level Estimation Considerations

Gate effort depends on evidence volume and stakeholder count.

## Definition of Done

Quality gates have defined criteria, evidence, outcomes and exception handling.

---
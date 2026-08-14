# Layer 10 — 10.23 Resource Capacity Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.23 |
| Capability | Resource Capacity Governance |
| Task Catalogue ID | 10.23 |
| Primary Layer 1 Phases | P04, P09, P11 |

## Capability Objective

Govern resource capacity against planned project demand.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Model capacity |
| P09 | Validate resource availability |
| P11 | Reforecast capacity |

## Source Implementation Activities

1. Assess capacity.
2. Map demand.
3. Identify bottlenecks.
4. Resolve capacity gaps.
5. Reforecast capacity.

## Implementation Tasks

### Activity 01 — Assess

#### L10-10.23-001 — Assess Resource Capacity

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Resource Manager |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Assess available capacity for required delivery roles.

**Dependencies**

- Role catalogue
- Resource requirements

**Deliverable**

Capacity assessment.

**Acceptance Criteria**

Capacity is documented by role.

### Activity 02 — Identify

#### L10-10.23-002 — Identify Resource Bottlenecks

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Resource Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify roles where demand exceeds capacity.

**Dependencies**

- L10-10.23-001

**Deliverable**

Capacity risk register.

**Acceptance Criteria**

Material bottlenecks are identified.

### Activity 03 — Resolve

#### L10-10.23-003 — Resolve Resource Capacity Gaps

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P09 |
| Primary Role | Resource Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define resource, sequencing or schedule actions to address capacity gaps.

**Dependencies**

- L10-10.23-002

**Deliverable**

Resource mitigation plan.

**Acceptance Criteria**

Critical capacity gaps have a resolution path.

### Activity 04 — Reforecast

#### L10-10.23-004 — Reforecast Resource Capacity

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P11 |
| Primary Role | Resource Manager |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Reforecast capacity using current delivery requirements.

**Dependencies**

- Current forecast

**Deliverable**

Updated capacity forecast.

**Acceptance Criteria**

Resource forecast reflects current demand.

## Capability-Level Dependencies

- Role catalogue
- Schedule model
- Estimate

## Capability-Level Estimation Considerations

Specialist availability and resource bottlenecks are major schedule drivers.

## Definition of Done

Resource capacity is assessed, governed and reforecast where required.

---
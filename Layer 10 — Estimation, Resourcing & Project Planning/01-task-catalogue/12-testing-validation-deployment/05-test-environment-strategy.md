# Layer 10 — 2.12.05 Test Environment Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.05 — Test Environment Strategy |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.05 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P03–P05 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Primary Environment | DESIGN |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Define the environments, environment ownership, configuration approach, test isolation, refresh strategy and dependencies required to execute the testing lifecycle.

## Source Implementation Activities

- Define test environment topology.
- Define environment usage by test cycle.
- Define environment dependencies.
- Define refresh and reset strategy.
- Approve environment strategy.

## Implementation Tasks

### Activity 01 — Define Environment Topology

#### L10-12.05-001 — Define Test Environment Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03–P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define Genesys Cloud organisations and supporting environments required for testing.

**Dependencies**

Environment Strategy and solution architecture.

**Deliverable**

Test Environment Model.

**Acceptance Criteria**

Required environments and purposes are documented.

### Activity 02 — Map Test Cycles

#### L10-12.05-002 — Map Test Cycles to Environments

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define which environment is used for each test cycle.

**Dependencies**

L10-12.05-001.

**Deliverable**

Environment/Test Cycle Matrix.

**Acceptance Criteria**

Every test cycle has an assigned environment.

### Activity 03 — Define Refresh Strategy

#### L10-12.05-003 — Define Environment Refresh and Reset Approach

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04–P05 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define how test environments are reset, refreshed and restored between test cycles.

**Dependencies**

L10-12.05-001.

**Deliverable**

Environment Refresh Strategy.

**Acceptance Criteria**

Refresh/reset procedures are documented.

### Activity 04 — Approve Strategy

#### L10-12.05-004 — Approve Test Environment Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain approval for environment topology and usage.

**Dependencies**

L10-12.05-001 through L10-12.05-003.

**Deliverable**

Approved Test Environment Strategy.

**Acceptance Criteria**

Required stakeholders approve the strategy.

## Capability-Level Dependencies

- Environment Strategy
- Core Platform
- Solution Architecture
- Security Architecture

## Capability-Level Estimation Considerations

Effort increases with environment count, isolation requirements, integrations and environment-specific configuration.

## Definition of Done

Required test environments and their usage are documented and approved.

---
# Layer 10 — 2.02.07 Groups

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.07 |
| Capability | Groups |
| Task Catalogue ID | 02.07 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Design and configure groups to support scalable user administration, access assignment and operational management.

## Source Implementation Activities

1. Define group strategy.
2. Identify required groups.
3. Configure groups.
4. Assign users or membership rules.
5. Validate group-based access.
6. Document group ownership.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.07-001 — Define Group Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define how groups will support user administration and access management.

**Dependencies**

- L10-02.01-004

**Deliverable**

Group strategy.

**Acceptance Criteria**

Group strategy is approved.

#### L10-02.07-002 — Define Group Catalogue

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define required groups, naming conventions, ownership and membership rules.

**Dependencies**

- L10-02.07-001

**Deliverable**

Group catalogue.

**Acceptance Criteria**

Group catalogue is approved.

### Activity 02 — Configure

#### L10-02.07-003 — Configure Groups

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Create and configure the approved groups.

**Dependencies**

- L10-02.07-002

**Deliverable**

Configured groups.

**Acceptance Criteria**

Groups exist according to the approved catalogue.

#### L10-02.07-004 — Configure Group Membership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure or validate membership according to approved lifecycle and access rules.

**Dependencies**

- L10-02.07-003

**Deliverable**

Group membership configuration.

**Acceptance Criteria**

Membership reflects approved requirements.

### Activity 03 — Validate

#### L10-02.07-005 — Validate Group-Based Access

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate group membership and resulting access behaviour.

**Dependencies**

- L10-02.07-004

**Deliverable**

Group validation evidence.

**Acceptance Criteria**

Group-based access operates as designed.
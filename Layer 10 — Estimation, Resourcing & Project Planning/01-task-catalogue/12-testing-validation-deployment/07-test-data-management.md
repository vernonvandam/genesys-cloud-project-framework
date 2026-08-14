# Layer 10 — 2.12.07 Test Data Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.07 — Test Data Management |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.07 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P03–P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Provide safe, representative and approved test data required to execute functional, integration, migration, reporting and acceptance testing.

## Source Implementation Activities

- Identify test data requirements.
- Define data creation and masking approach.
- Prepare test datasets.
- Load or configure test data.
- Validate data readiness.

## Implementation Tasks

### Activity 01 — Identify Data Requirements

#### L10-12.07-001 — Define Test Data Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify test data required for functional, integration, reporting and UAT scenarios.

**Dependencies**

Test Plan and requirements.

**Deliverable**

Test Data Requirements.

**Acceptance Criteria**

Required datasets are documented.

### Activity 02 — Define Protection

#### L10-12.07-002 — Define Test Data Protection

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03–P04 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Determine whether data requires masking, synthetic generation or other protection.

**Dependencies**

Data classification and security requirements.

**Deliverable**

Test Data Protection Approach.

**Acceptance Criteria**

Approved protection method exists for sensitive test data.

### Activity 03 — Prepare Data

#### L10-12.07-003 — Prepare Test Dataset

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05–P07 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Create, transform, mask or load required test data.

**Dependencies**

L10-12.07-001 and L10-12.07-002.

**Deliverable**

Approved Test Dataset.

**Acceptance Criteria**

Dataset supports planned test scenarios.

### Activity 04 — Validate Data

#### L10-12.07-004 — Validate Test Data Readiness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate data completeness, usability and protection.

**Dependencies**

L10-12.07-003.

**Deliverable**

Test Data Readiness Sign-Off.

**Acceptance Criteria**

All required datasets are usable and compliant.

## Capability-Level Dependencies

- Data protection requirements
- Migration design
- Test case design
- Security requirements

## Capability-Level Estimation Considerations

Data volume, complexity, masking requirements and number of test cycles drive effort.

## Definition of Done

Required test datasets are available, protected and validated.

---
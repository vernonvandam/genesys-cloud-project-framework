# Layer 10 — 2.12.23 Security Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.23 — Security Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.23 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Validate that implemented security controls operate according to approved security architecture and requirements.

## Source Implementation Activities

- Validate authentication.
- Validate authorisation.
- Validate least privilege.
- Validate data segregation.
- Validate security controls.
- Record and remediate security findings.

## Implementation Tasks

### Activity 01 — Define Security Test Scope

#### L10-12.23-001 — Establish Security Test Scenarios

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03–P04 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define security validation scenarios based on approved security requirements.

**Dependencies**

Security Architecture.

**Deliverable**

Security Test Scope.

**Acceptance Criteria**

Critical security controls have test coverage.

### Activity 02 — Test Access Controls

#### L10-12.23-002 — Validate Authentication and Authorisation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Test valid and invalid authentication and access scenarios.

**Dependencies**

Identity & Access.

**Deliverable**

Security Access Test Results.

**Acceptance Criteria**

Unauthorised access is prevented and authorised access works.

### Activity 03 — Test Data Segregation

#### L10-12.23-003 — Validate Data and Division Segregation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate division and data visibility controls.

**Dependencies**

Divisions and permissions.

**Deliverable**

Segregation Test Results.

**Acceptance Criteria**

Users cannot access unauthorised data or divisions.

### Activity 04 — Manage Findings

#### L10-12.23-004 — Remediate Security Findings

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Coordinate remediation and retesting of security defects.

**Dependencies**

L10-12.23-002 and L10-12.23-003.

**Deliverable**

Security Findings Register.

**Acceptance Criteria**

Critical findings are resolved or formally accepted.

## Capability-Level Dependencies

- Security & Governance
- Identity & Access
- Core Platform
- Data Protection

## Capability-Level Estimation Considerations

Security complexity, controls, environments and testing depth drive effort.

## Definition of Done

Required security controls are validated and critical findings are closed or accepted.

---
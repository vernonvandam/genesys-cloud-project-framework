FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/27-audit-logging.md

# Layer 10 — 2.11.27 Audit Logging

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.27 |
| Capability | Audit Logging |
| Task Catalogue ID | 11.27 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10 |

## Capability Objective

Establish auditable logging for security-relevant administrative and operational activity.

## Implementation Tasks

### Activity 01 — Establish Audit Logging

#### L10-11.27-001 — Define Audit Logging Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define security events, administrative activity, retention and access requirements for audit logging.

**Dependencies**

- Security requirements
- Compliance requirements

**Deliverable**

Audit logging design.

**Acceptance Criteria**

Required audit events are identified.

---

#### L10-11.27-002 — Validate Audit Logging

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Generate representative security events and verify audit records are captured and accessible.

**Dependencies**

- L10-11.27-001

**Deliverable**

Audit logging test evidence.

**Acceptance Criteria**

Required audit events are captured and retained according to policy.
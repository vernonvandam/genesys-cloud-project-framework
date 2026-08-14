FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/28-security-monitoring.md

# Layer 10 — 2.11.28 Security Monitoring

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.28 |
| Capability | Security Monitoring |
| Task Catalogue ID | 11.28 |
| Primary Layer 1 Phases | P04, P06, P08, P09, P10, P11 |

## Capability Objective

Establish security monitoring, alerting and operational visibility.

## Implementation Tasks

### Activity 01 — Establish Monitoring

#### L10-11.28-001 — Define Security Monitoring Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define security events, monitoring sources, alerting thresholds, ownership and escalation.

**Dependencies**

- Audit logging
- Incident response

**Deliverable**

Security monitoring design.

**Acceptance Criteria**

Monitoring requirements are approved.

---

#### L10-11.28-002 — Validate Security Monitoring

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Generate representative events and verify monitoring and escalation behaviour.

**Dependencies**

- L10-11.28-001

**Deliverable**

Monitoring validation evidence.

**Acceptance Criteria**

Required events generate appropriate monitoring and response actions.
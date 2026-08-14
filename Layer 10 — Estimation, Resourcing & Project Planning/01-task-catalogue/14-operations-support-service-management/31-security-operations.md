# Layer 10 — 2.14.31 Security Operations

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.31 |
| Capability | Security Operations |
| Task Catalogue ID | 14.31 |
| Primary Layer 1 Phases | P08, P09, P11, P12 |

## Capability Objective

Establish ongoing operational security management for Genesys Cloud.

## Implementation Tasks

### L10-14.31-001 — Define Security Operations Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define operational security monitoring, access review, incident and control requirements.

**Dependencies**

- Security architecture
- Compliance requirements

**Deliverable**

Security operations requirements.

**Acceptance Criteria**

Operational security scope is approved.

### L10-14.31-002 — Establish Security Operations Procedures

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Establish security review, monitoring, escalation and access-control procedures.

**Dependencies**

- L10-14.31-001

**Deliverable**

Security operations procedures.

**Acceptance Criteria**

Operational security processes have owners.

### L10-14.31-003 — Validate Security Operations

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate security monitoring and operational controls after go-live.

**Dependencies**

- L10-14.31-002

**Deliverable**

Security operations validation.

**Acceptance Criteria**

Required operational security controls are functioning.

## Definition of Done

Security operations are established, owned and validated.

---
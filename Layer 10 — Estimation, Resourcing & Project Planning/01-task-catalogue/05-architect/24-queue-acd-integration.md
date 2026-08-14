# Layer 10 — 2.05.24 Queue & ACD Integration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.24 |
| Capability | Queue & ACD Integration |
| Task Catalogue ID | 05.24 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Integrate Architect flows with ACD queues, skills, priorities and routing configuration.

## Source Implementation Activities

1. Define queue integration requirements.
2. Map flow outcomes to ACD.
3. Configure integration.
4. Validate queue routing.

## Implementation Tasks

### Activity 01 — Define Queue Integration

#### L10-05.24-001 — Define Queue Integration Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define queue, skill, priority, language and routing requirements used by Architect.

**Dependencies**

- ACD routing design

**Deliverable**

Queue integration matrix.

**Acceptance Criteria**

Queue integration requirements are approved.

---

#### L10-05.24-002 — Configure Queue Integration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 2.5h |
| Critical Path | YES |

**Description**

Configure Architect queue actions and routing attributes.

**Dependencies**

- L10-05.24-001
- Queue configuration

**Deliverable**

Configured queue integration.

**Acceptance Criteria**

Flows correctly invoke approved queues and routing attributes.

---

#### L10-05.24-003 — Validate ACD Integration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate queue selection, skills, priority and fallback behaviour.

**Dependencies**

- L10-05.24-002

**Deliverable**

ACD integration test evidence.

**Acceptance Criteria**

Approved queue-routing scenarios pass.
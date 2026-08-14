# Layer 10 — 2.12.21 Recording Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.21 — Recording Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.21 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Validate recording configuration, recording availability, playback, access, retention and applicable interaction types.

## Source Implementation Activities

- Validate recording configuration.
- Test recording creation.
- Test playback.
- Test access controls.
- Validate retention behaviour.

## Implementation Tasks

### Activity 01 — Validate Recording Configuration

#### L10-12.21-001 — Validate Recording Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate recording policies, configuration and applicable media types.

**Dependencies**

Recording configuration.

**Deliverable**

Recording Configuration Validation.

**Acceptance Criteria**

Approved recording configuration is present.

### Activity 02 — Test Recording

#### L10-12.21-002 — Validate Recording Creation and Playback

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Execute calls/interactions and validate recordings are created and playable.

**Dependencies**

L10-12.21-001.

**Deliverable**

Recording Test Results.

**Acceptance Criteria**

Required recordings are created and can be played by authorised users.

### Activity 03 — Validate Access

#### L10-12.21-003 — Validate Recording Security

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate authorised and unauthorised recording access.

**Dependencies**

L10-12.21-002.

**Deliverable**

Recording Security Validation.

**Acceptance Criteria**

Access matches approved security model.

## Capability-Level Dependencies

- Voice
- Recording
- Security
- Retention

## Capability-Level Estimation Considerations

Interaction types, recording policies, access models and retention requirements drive effort.

## Definition of Done

Recording creation, playback, security and applicable retention behaviour are validated.

---
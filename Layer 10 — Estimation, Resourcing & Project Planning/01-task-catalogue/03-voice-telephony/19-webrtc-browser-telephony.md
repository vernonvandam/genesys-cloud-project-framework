<!-- FILE: 19-webrtc-browser-telephony.md -->

# Layer 10 — 2.03.19 WebRTC & Browser Telephony

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.19 |
| Capability | WebRTC & Browser Telephony |
| Task Catalogue ID | 03.19 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09 |

## Capability Objective

Prepare and validate browser-based voice operation using supported WebRTC capabilities.

## Source Implementation Activities

1. Define browser voice requirements.
2. Validate endpoint environment.
3. Configure users.
4. Validate browser media.
5. Test.

## Implementation Tasks

#### L10-03.19-001 — Define WebRTC Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define browser, headset, microphone, operating-system and user requirements.

**Dependencies**

- Endpoint strategy

**Deliverable**

WebRTC requirements.

**Acceptance Criteria**

Requirements approved.

#### L10-03.19-002 — Validate Browser and Endpoint Compatibility

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Technical Architect |
| Customer Responsibility | YES |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate supported browser, operating system, headset and network combinations.

**Dependencies**

- L10-03.19-001

**Deliverable**

Compatibility assessment.

**Acceptance Criteria**

Supported endpoint standard is approved.

#### L10-03.19-003 — Configure Browser Voice Users

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Configure users and telephony settings required for browser voice.

**Dependencies**

- L10-03.19-002
- Identity and Access

**Deliverable**

Configured voice users.

**Acceptance Criteria**

Users can use browser telephony.

#### L10-03.19-004 — Test WebRTC Voice

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Test microphone, speaker, inbound, outbound, hold, transfer and media quality.

**Dependencies**

- L10-03.19-003

**Deliverable**

WebRTC test evidence.

**Acceptance Criteria**

All required scenarios pass.

## Capability-Level Dependencies

- Identity
- Network
- Endpoint standards
- Audio/media design

## Capability-Level Estimation Considerations

Endpoint standardisation and desktop engineering may be customer-owned effort.

## Definition of Done

Browser telephony is supported, configured, tested and operationally documented.
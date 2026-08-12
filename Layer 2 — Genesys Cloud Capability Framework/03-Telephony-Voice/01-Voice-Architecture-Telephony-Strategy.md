# Layer 2.03.01 — Voice Architecture & Telephony Strategy

## 1. Purpose

Define the target voice architecture and establish the strategic telephony model for the Genesys Cloud deployment.

## 2. Classification

**Required**

## 3. Scope

- Voice architecture
- PSTN strategy
- Carrier strategy
- Telephony model
- Number strategy
- Network/media architecture
- Endpoint strategy
- Resilience
- Compliance
- Operational ownership

## 4. Discovery Questions

- What existing telephony platform is being replaced?
- Which carrier provides PSTN services?
- Who owns the telephone numbers?
- Is number porting required?
- Is BYOC required?
- Is Genesys Cloud Voice available and suitable?
- Are there existing SIP trunks?
- Are there existing PBXs?
- Are physical phones required?
- Are agents using WebRTC?
- Are there multiple geographic locations?
- Are there emergency-calling obligations?
- Are there regulatory requirements?
- Is carrier redundancy required?
- Are there existing recording platforms?
- Are there special telephony applications?

## 5. Design Activities

1. Document current-state telephony.
2. Document existing carrier architecture.
3. Document existing number inventory.
4. Identify geographic requirements.
5. Identify voice traffic volumes.
6. Identify inbound requirements.
7. Identify outbound requirements.
8. Define endpoint strategy.
9. Define PSTN model.
10. Define carrier architecture.
11. Define resilience.
12. Define network/media requirements.
13. Define operational ownership.
14. Obtain architecture approval.

## 6. Dependencies

- Core Platform
- Identity & Access
- Network
- Security
- Customer carrier
- Existing telephony

## 7. Layer 1 Mapping

Primary:

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 4 — Architecture

Supporting:

- Phase 5 — Foundation
- Phase 9 — Operational Readiness

## 8. Roles

- Solution Architect
- Voice Architect
- Network Architect
- Security Architect
- Customer Telephony Owner
- Carrier

## 9. Customer Responsibilities

- Provide current telephony architecture.
- Provide carrier information.
- Provide number inventory.
- Confirm voice requirements.
- Confirm regulatory requirements.
- Approve target architecture.

## 10. Deliverables

- Voice architecture
- Telephony strategy
- Current-state assessment
- Target-state architecture
- Architecture decision records

## 11. Risks

- Incorrect telephony model.
- Carrier limitations discovered late.
- Number migration underestimated.
- Network requirements discovered during testing.

## 12. Effort Drivers

- Number of sites
- Number of carriers
- PSTN architecture
- Existing PBX
- BYOC requirements
- Physical endpoints
- Geographic complexity
- Regulatory requirements
- Resilience requirements

## 13. Acceptance Criteria

The target telephony architecture and deployment model are approved by technical, security and business stakeholders.

## 14. Definition of Done

Voice architecture, PSTN strategy, carrier model, endpoint strategy and resilience approach are documented and approved.

## 15. Phase Gate

```text
CURRENT STATE
     ↓
REQUIREMENTS
     ↓
TELEPHONY MODEL
     ↓
CARRIER DESIGN
     ↓
NETWORK DESIGN
     ↓
TARGET ARCHITECTURE
     ↓
CUSTOMER APPROVAL
```
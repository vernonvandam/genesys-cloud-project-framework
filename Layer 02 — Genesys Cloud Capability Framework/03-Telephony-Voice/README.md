# Layer 2.03 — Voice & Telephony

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 03 — Voice & Telephony  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete voice and telephony capability set required to design, implement, test, migrate and operate Genesys Cloud voice services.

---

# 1. Purpose

Voice & Telephony defines the architecture and implementation requirements for inbound and outbound voice communications within Genesys Cloud.

The domain covers:

- Telephony architecture
- Carrier connectivity
- BYOC Cloud
- BYOC Premises
- Genesys Cloud Voice
- Sites
- Edges
- SIP
- Trunks
- DIDs and telephone numbers
- Number porting
- Dial plans
- Number plans
- Call classification
- Inbound routing
- Outbound routing
- Caller ID
- Extensions
- Endpoints
- WebRTC
- Physical phones
- Media and codecs
- Network requirements
- QoS
- Firewall/NAT
- Failover and survivability
- Emergency calling
- Recording-related telephony considerations
- Call quality monitoring
- Telephony integrations
- Fax where applicable
- Compliance
- Migration and cutover
- Operational support

---

# 2. Scope

```text
03 Voice & Telephony
│
├── 01 Voice Architecture & Telephony Strategy
├── 02 Telephony Model Selection
├── 03 Carrier & SIP Connectivity
├── 04 BYOC Cloud
├── 05 BYOC Premises
├── 06 Genesys Cloud Voice
├── 07 Sites
├── 08 Edges & Telephony Devices
├── 09 Network, Firewall & Media Requirements
├── 10 SIP Trunks & Trunk Configuration
├── 11 Telephone Numbers & DIDs
├── 12 Number Porting & Migration
├── 13 Dial Plans & Number Normalisation
├── 14 Number Plans & Call Classification
├── 15 Inbound Call Routing
├── 16 Outbound Call Routing
├── 17 Caller ID & ANI
├── 18 Extensions & Internal Dialling
├── 19 WebRTC & Browser Telephony
├── 20 Physical Phones & Endpoints
├── 21 Audio, Codecs & Media
├── 22 Emergency Services / E911
├── 23 Telephony Failover & Survivability
├── 24 Carrier Redundancy & Resilience
├── 25 Voice Recording & Media Dependencies
├── 26 Call Quality Monitoring & Troubleshooting
├── 27 Fax & Special Telephony Services
├── 28 Telephony Integrations
├── 29 Voice Security & Compliance
├── 30 Voice Testing & Validation
├── 31 Telephony Migration & Cutover
└── 32 Voice Operations & BAU
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Voice Architecture & Telephony Strategy | Required |
| Telephony Model Selection | Required |
| Carrier & SIP Connectivity | Required |
| BYOC Cloud | Conditional |
| BYOC Premises | Conditional |
| Genesys Cloud Voice | Conditional |
| Sites | Required |
| Edges & Telephony Devices | Conditional |
| Network, Firewall & Media Requirements | Required |
| SIP Trunks & Trunk Configuration | Conditional |
| Telephone Numbers & DIDs | Required |
| Number Porting & Migration | Conditional |
| Dial Plans & Number Normalisation | Required |
| Number Plans & Call Classification | Required |
| Inbound Call Routing | Required |
| Outbound Call Routing | Required |
| Caller ID & ANI | Required |
| Extensions & Internal Dialling | Conditional |
| WebRTC & Browser Telephony | Required for browser-based voice |
| Physical Phones & Endpoints | Conditional |
| Audio, Codecs & Media | Required |
| Emergency Services / E911 | Conditional by geography/regulatory requirements |
| Telephony Failover & Survivability | Conditional |
| Carrier Redundancy & Resilience | Conditional |
| Voice Recording & Media Dependencies | Conditional |
| Call Quality Monitoring & Troubleshooting | Required |
| Fax & Special Telephony Services | Conditional |
| Telephony Integrations | Conditional |
| Voice Security & Compliance | Required |
| Voice Testing & Validation | Required |
| Telephony Migration & Cutover | Conditional |
| Voice Operations & BAU | Required |

---

# 4. Telephony Architecture Decision Tree

```text
                    Voice Requirement
                           │
                           ▼
                Determine Deployment Model
                           │
          ┌────────────────┼─────────────────┐
          │                │                 │
          ▼                ▼                 ▼
    Genesys Cloud      BYOC Cloud       BYOC Premises
       Voice
          │                │                 │
          └────────────────┼─────────────────┘
                           ▼
                    Carrier Strategy
                           │
                           ▼
                    Number Strategy
                           │
                           ▼
                    Network Design
                           │
                           ▼
                    Routing Design
                           │
                           ▼
                 Endpoint / WebRTC Design
                           │
                           ▼
                   Resilience Design
                           │
                           ▼
                     Test & Cutover
```

---

# 5. Key Design Principles

1. Select the telephony model based on customer requirements rather than defaulting to a particular architecture.
2. Treat carrier connectivity as a critical dependency.
3. Separate number ownership from Genesys Cloud configuration ownership.
4. Define number normalisation before detailed routing configuration.
5. Design inbound and outbound routing together.
6. Define caller ID requirements before outbound testing.
7. Treat emergency calling as a distinct requirement.
8. Design network and media paths before endpoint deployment.
9. Minimise unnecessary on-premises telephony infrastructure.
10. Use BYOC Premises only where requirements justify the additional infrastructure.
11. Design carrier and network resilience explicitly.
12. Test both successful and failure scenarios.
13. Validate number porting independently from technical configuration.
14. Treat production cutover as a controlled telephony migration.
15. Establish operational ownership for carrier, Genesys and network faults.
16. Validate region, licensing and current Genesys Cloud support before implementation.

---

# 6. Major Dependencies

Voice & Telephony depends on:

- Core Platform
- Organisation region
- Identity & Access
- Network architecture
- Security architecture
- Carrier
- Customer PSTN requirements
- Number inventory
- Routing requirements
- Architect
- Queues
- Users
- Recording requirements
- Compliance requirements

Voice & Telephony is a prerequisite for:

- Inbound voice
- Outbound voice
- IVR
- ACD voice routing
- Agent telephony
- Voice recording
- Voice analytics
- Callback
- Emergency calling
- Voice migration

---

# 7. Layer 1 Mapping

| Layer 1 Phase | Voice & Telephony Activities |
|---|---|
| Phase 1 — Initiation | Establish telephony scope and ownership |
| Phase 2 — Discovery | Discover carriers, numbers, sites and existing telephony |
| Phase 3 — Requirements | Define voice, routing, endpoint and compliance requirements |
| Phase 4 — Architecture | Select telephony architecture and carrier strategy |
| Phase 5 — Platform Foundation | Establish sites, network and telephony foundation |
| Phase 6 — Solution Build | Configure telephony, numbers, trunks and routing |
| Phase 7 — Integration & Migration | Integrate carrier and migrate numbers |
| Phase 8 — Testing | Execute voice and telephony testing |
| Phase 9 — Operational Readiness | Establish monitoring and support |
| Phase 10 — Production Deployment | Execute telephony cutover |
| Phase 11 — Hypercare | Monitor voice service |
| Phase 12 — BAU Handover | Transfer operational ownership |

---

# 8. Standard Spreadsheet Task Model

Each activity must eventually be capable of becoming a spreadsheet row containing:

| Field | Requirement |
|---|---|
| Task ID | Unique task identifier |
| Layer | Layer 2 |
| Domain | 03 |
| Capability | Voice capability |
| Phase | Layer 1 phase |
| Workstream | Voice & Telephony |
| Classification | Required / Conditional / Optional |
| Task | Atomic implementation task |
| Description | Detailed activity |
| Dependency | Predecessor task |
| Role | Delivery owner |
| Customer Responsibility | Yes / No |
| Environment | DEV / TEST / UAT / PROD |
| Effort | Estimated hours |
| Duration | Elapsed duration |
| Deliverable | Task output |
| Acceptance Criteria | Completion requirement |
| Critical Path | Yes / No |

---

# 9. Domain Deliverables

Potential deliverables include:

- Voice architecture
- Telephony strategy
- Carrier design
- SIP architecture
- BYOC design
- Site design
- Edge design
- Network/media requirements
- Number inventory
- Number porting plan
- Dial plan
- Number plan
- Inbound routing design
- Outbound routing design
- Caller ID design
- Endpoint design
- Emergency calling design
- Resilience design
- Voice test plan
- Cutover plan
- Rollback plan
- Operational runbook
- Carrier support model

---

# 10. Standard Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Carrier readiness delayed | Critical | Early carrier engagement |
| Number port failure | Critical | Formal port validation and contingency |
| Incorrect number routing | High | Number inventory and test matrix |
| Poor call quality | High | Network/QoS assessment |
| Incorrect caller ID | High | Carrier and outbound route validation |
| Emergency calling failure | Critical | Explicit emergency-call testing |
| Insufficient carrier resilience | High | Redundancy assessment |
| Firewall/media failure | High | Pre-production media testing |
| Incorrect dial plan | High | Normalisation test matrix |
| Endpoint compatibility issues | Medium | Device validation |
| Cutover failure | Critical | Rehearsal and rollback plan |
| Inadequate monitoring | Medium | BAU readiness testing |

---

# 11. Definition of Done

The Voice & Telephony domain is complete when:

- Telephony architecture is approved.
- Carrier strategy is approved.
- Required carrier connectivity is operational.
- Sites are configured.
- Required Edges are operational.
- Network requirements are validated.
- Numbers are inventoried.
- Numbers are configured or ported.
- Dial plans are configured.
- Number plans are configured.
- Inbound routing is tested.
- Outbound routing is tested.
- Caller ID is validated.
- Endpoints are validated.
- WebRTC is validated where applicable.
- Emergency calling is validated where required.
- Resilience is tested where required.
- Call quality is validated.
- Telephony integrations are validated.
- Cutover is approved.
- Operational support is documented.

---

# 12. Phase Gate

```text
TELEPHONY ARCHITECTURE APPROVED
          +
CARRIER READY
          +
NETWORK READY
          +
NUMBERS READY
          +
ROUTING CONFIGURED
          +
VOICE TESTING PASSED
          +
EMERGENCY CALLING VALIDATED
          +
CUTOVER PLAN APPROVED
          +
CUSTOMER ACCEPTANCE
          ↓
VOICE & TELEPHONY READY
```

---

# 13. Domain File Catalogue

```text
03-Voice-Telephony/
│
├── README.md
├── 01-Voice-Architecture-Telephony-Strategy.md
├── 02-Telephony-Model-Selection.md
├── 03-Carrier-SIP-Connectivity.md
├── 04-BYOC-Cloud.md
├── 05-BYOC-Premises.md
├── 06-Genesys-Cloud-Voice.md
├── 07-Sites.md
├── 08-Edges-Telephony-Devices.md
├── 09-Network-Firewall-Media-Requirements.md
├── 10-SIP-Trunks-Trunk-Configuration.md
├── 11-Telephone-Numbers-DIDs.md
├── 12-Number-Porting-Migration.md
├── 13-Dial-Plans-Number-Normalisation.md
├── 14-Number-Plans-Call-Classification.md
├── 15-Inbound-Call-Routing.md
├── 16-Outbound-Call-Routing.md
├── 17-Caller-ID-ANI.md
├── 18-Extensions-Internal-Dialling.md
├── 19-WebRTC-Browser-Telephony.md
├── 20-Physical-Phones-Endpoints.md
├── 21-Audio-Codecs-Media.md
├── 22-Emergency-Services-E911.md
├── 23-Telephony-Failover-Survivability.md
├── 24-Carrier-Redundancy-Resilience.md
├── 25-Voice-Recording-Media-Dependencies.md
├── 26-Call-Quality-Monitoring-Troubleshooting.md
├── 27-Fax-Special-Telephony-Services.md
├── 28-Telephony-Integrations.md
├── 29-Voice-Security-Compliance.md
├── 30-Voice-Testing-Validation.md
├── 31-Telephony-Migration-Cutover.md
└── 32-Voice-Operations-BAU.md
```

---

# 14. Domain Completion

The individual capability documents form the detailed Layer 2.03 Voice & Telephony catalogue.

These documents are capability references rather than the final implementation schedule.

The later implementation-task catalogue will decompose these capabilities into atomic project tasks.

---

# Domain Completion Gate

**Status:** Ready for capability-level task decomposition.

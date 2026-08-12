# Layer 2.06 — Digital Channels

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 06 — Digital Channels  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete Genesys Cloud digital-channel capability set required to design, configure, integrate, test, migrate and operate digital customer engagement.

---

# 1. Purpose

Genesys Cloud Digital Channels provides the customer interaction layer for asynchronous and real-time digital engagement.

This domain defines the capabilities required to implement:

- Web messaging
- Web Messenger
- Web chat where applicable
- SMS
- Open messaging
- Email
- Social messaging
- WhatsApp
- Facebook Messenger
- Instagram messaging
- Apple Messages for Business
- Digital bot engagement
- Digital Architect flows
- Digital queue routing
- Digital skills
- Digital priority
- Digital transfers
- Digital escalation
- Digital authentication
- Customer context
- Conversation history
- Attachments
- Canned responses
- Digital scripts
- Agent workspace integration
- Digital interaction recording
- Digital interaction analytics
- Digital service levels
- Digital notifications
- Digital campaign / outbound digital use cases where applicable
- Digital channel security
- Digital channel governance
- Digital channel testing
- Digital channel migration
- Digital channel operational support

Digital channels must be designed as part of the overall customer journey rather than implemented as isolated communication channels.

---

# 2. Scope

```text
06 Digital Channels
│
├── 01 Digital Architecture
├── 02 Digital Channel Strategy & Governance
├── 03 Web Messaging
├── 04 Web Messenger Deployment
├── 05 Web Chat
├── 06 SMS
├── 07 Open Messaging
├── 08 WhatsApp
├── 09 Facebook Messenger
├── 10 Instagram Messaging
├── 11 Apple Messages for Business
├── 12 Email
├── 13 Social & External Messaging
├── 14 Digital Bot Integration
├── 15 Digital Architect Flows
├── 16 Digital Menus & Journeys
├── 17 Digital Authentication
├── 18 Customer Context & Identity
├── 19 Digital Routing
├── 20 Digital Queues & Skills
├── 21 Digital Priority & SLA
├── 22 Digital Transfers & Escalation
├── 23 Digital Attachments
├── 24 Digital Notifications
├── 25 Canned Responses & Knowledge
├── 26 Agent Digital Workspace
├── 27 Digital Conversation History
├── 28 Digital Analytics & Reporting
├── 29 Digital Recording & Compliance
├── 30 Digital Security & Privacy
├── 31 Digital Integrations
├── 32 Digital Testing & Validation
├── 33 Digital Migration & Cutover
├── 34 Digital Operations & BAU
├── 35 Digital Optimisation
└── 36 Digital Governance & Lifecycle
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Digital Architecture | Required |
| Digital Channel Strategy & Governance | Required |
| Web Messaging | Required |
| Web Messenger Deployment | Required |
| Web Chat | Conditional |
| SMS | Conditional |
| Open Messaging | Conditional |
| WhatsApp | Conditional |
| Facebook Messenger | Conditional |
| Instagram Messaging | Conditional |
| Apple Messages for Business | Conditional |
| Email | Required |
| Social & External Messaging | Conditional |
| Digital Bot Integration | Conditional |
| Digital Architect Flows | Conditional |
| Digital Menus & Journeys | Conditional |
| Digital Authentication | Conditional |
| Customer Context & Identity | Required |
| Digital Routing | Required |
| Digital Queues & Skills | Required |
| Digital Priority & SLA | Required |
| Digital Transfers & Escalation | Required |
| Digital Attachments | Conditional |
| Digital Notifications | Conditional |
| Canned Responses & Knowledge | Required |
| Agent Digital Workspace | Required |
| Digital Conversation History | Required |
| Digital Analytics & Reporting | Required |
| Digital Recording & Compliance | Conditional |
| Digital Security & Privacy | Required |
| Digital Integrations | Conditional |
| Digital Testing & Validation | Required |
| Digital Migration & Cutover | Conditional |
| Digital Operations & BAU | Required |
| Digital Optimisation | Required |
| Digital Governance & Lifecycle | Required |

---

# 4. Digital Architecture

```text
Customer
   │
   ├── Web
   ├── SMS
   ├── Email
   ├── WhatsApp
   ├── Social
   └── Other Messaging
          │
          ▼
    Digital Channel
          │
          ▼
     Genesys Cloud
          │
          ├── Identity
          ├── Context
          ├── Architect
          ├── Bot
          ├── Routing
          ├── Queue
          ├── Skills
          └── Agent Workspace
                  │
                  ▼
               Agent
                  │
                  ▼
        Customer Resolution
```

Digital architecture must define:

- Channel ownership
- Channel entry points
- Channel authentication
- Customer identity
- Customer context
- Bot/self-service
- Routing
- Queue assignment
- Skills
- Priority
- Agent handling
- Transfers
- Escalation
- Attachments
- Compliance
- Reporting
- Integration
- Support

---

# 5. Digital Design Principles

1. Digital channels must support an intentional customer journey.
2. Customers should not be forced to repeat information unnecessarily.
3. Digital conversations should preserve context where technically supported.
4. Digital routing must be aligned with the ACD routing architecture.
5. Channel-specific behaviour must be documented.
6. Authentication requirements must be explicit.
7. Customer identity must be handled consistently.
8. Digital bots should resolve appropriate low-complexity interactions.
9. Unsupported bot journeys must have a clear human escalation path.
10. Digital channels must have defined operating hours and out-of-hours behaviour.
11. Digital SLAs must be explicitly defined.
12. Email must be treated differently from synchronous messaging.
13. Social channels require explicit ownership and moderation processes.
14. Attachments require security and malware considerations.
15. Personally identifiable information must be protected.
16. Digital conversations should be measurable.
17. Every channel requires a defined BAU support owner.
18. Channel integrations must have failure handling.
19. Digital channel changes must follow controlled release processes.
20. The design must support future channel expansion without unnecessary redesign.

---

# 6. Major Dependencies

Digital Channels depends on:

- Core Platform
- Identity & Access
- ACD Routing
- Architect
- Digital Bot
- Queues
- Skills
- Users
- Divisions
- Schedules
- CRM
- External systems
- Security
- Reporting
- Operations

Digital Channels provides dependencies for:

- Digital customer journeys
- Messaging
- Email
- Digital bot engagement
- Digital routing
- Digital queues
- Agent digital handling
- Digital reporting
- Digital customer context

---

# 7. Layer 1 Mapping

| Layer 1 Phase | Digital Activities |
|---|---|
| Phase 1 — Initiation | Establish digital-channel scope |
| Phase 2 — Discovery | Discover current digital channels |
| Phase 3 — Requirements | Define channel and journey requirements |
| Phase 4 — Architecture | Design digital architecture |
| Phase 5 — Platform Foundation | Configure digital foundation |
| Phase 6 — Solution Build | Configure channels and journeys |
| Phase 7 — Integration & Migration | Integrate and migrate channels |
| Phase 8 — Testing | Execute digital testing |
| Phase 9 — Operational Readiness | Prepare digital support |
| Phase 10 — Production Deployment | Activate channels |
| Phase 11 — Hypercare | Monitor digital experience |
| Phase 12 — BAU Handover | Transfer operational ownership |

---

# 8. Digital Channel Lifecycle

```text
Business Requirement
        │
        ▼
Channel Assessment
        │
        ▼
Customer Journey
        │
        ▼
Technical Design
        │
        ▼
Channel Configuration
        │
        ▼
Integration
        │
        ▼
Testing
        │
        ▼
UAT
        │
        ▼
Production Readiness
        │
        ▼
Channel Activation
        │
        ▼
Hypercare
        │
        ▼
BAU
        │
        ▼
Optimisation
```

---

# 9. Standard Digital Artefacts

A project may require:

- Digital channel inventory
- Digital channel strategy
- Digital architecture
- Customer journey maps
- Channel requirements
- Channel decision matrix
- Digital routing matrix
- Queue matrix
- Skills matrix
- SLA matrix
- Authentication design
- Customer identity model
- Digital bot design
- Architect flow design
- Prompt catalogue
- Canned response catalogue
- Attachment policy
- Security assessment
- Privacy assessment
- Integration specification
- Digital test plan
- UAT scenarios
- Migration plan
- Cutover plan
- Rollback plan
- Digital operations runbook
- Digital support model
- Digital optimisation dashboard

---

# 10. Standard Spreadsheet Task Model

| Field | Requirement |
|---|---|
| Task ID | Unique identifier |
| Layer | Layer 2 |
| Domain | 06 |
| Capability | Digital capability |
| Phase | Layer 1 phase |
| Workstream | Digital |
| Classification | Required / Conditional / Optional |
| Task | Atomic implementation task |
| Description | Detailed activity |
| Dependency | Predecessor |
| Role | Delivery owner |
| Customer Responsibility | Yes / No |
| Environment | DEV / TEST / UAT / PROD |
| Effort | Estimated hours |
| Duration | Elapsed duration |
| Deliverable | Task output |
| Acceptance Criteria | Completion requirement |
| Critical Path | Yes / No |

---

# 11. Digital Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Poor channel selection | High | Complete channel assessment |
| Duplicate customer channels | Medium | Rationalise channel portfolio |
| Poor digital routing | High | Align with ACD architecture |
| Inadequate authentication | High | Define identity architecture |
| Bot failure | High | Provide agent escalation |
| Email queue overload | High | Define email capacity and routing |
| Social-channel dependency | High | Validate platform requirements |
| Attachment security | High | Define security controls |
| Poor SLA design | High | Define channel-specific SLAs |
| Customer context lost | High | Design identity/context model |
| Poor agent experience | High | Validate workspace |
| Uncontrolled channel activation | High | Formal cutover |
| Privacy exposure | High | Security/privacy review |
| Integration outage | High | Define fallback |
| Insufficient testing | High | Test complete customer journeys |

---

# 12. Definition of Done

The Digital Channels domain is complete when:

- Digital-channel strategy is approved.
- Channel inventory is complete.
- Current-state channels are documented.
- Target channels are approved.
- Customer journeys are documented.
- Digital architecture is approved.
- Routing design is approved.
- Queue and skill dependencies are defined.
- Identity and authentication requirements are defined.
- Bot dependencies are defined.
- Integration requirements are documented.
- Security requirements are documented.
- Privacy requirements are documented.
- Required channels are configured.
- Required integrations are configured.
- Digital journeys are tested.
- UAT is complete.
- Production configuration is approved.
- Cutover procedures are approved.
- Operational support is ready.

---

# 13. Domain Gate

```text
CHANNEL STRATEGY APPROVED
          +
CUSTOMER JOURNEYS APPROVED
          +
DIGITAL ARCHITECTURE APPROVED
          +
ROUTING DESIGN APPROVED
          +
SECURITY / PRIVACY APPROVED
          +
CHANNEL CONFIGURATION COMPLETE
          +
INTEGRATIONS VALIDATED
          +
TESTING PASSED
          +
UAT ACCEPTED
          +
OPERATIONS READY
          ↓
DIGITAL CHANNELS READY FOR PRODUCTION
```

---

# 14. Domain File Catalogue

```text
06-Digital/
│
├── README.md
├── 01-Digital-Architecture.md
├── 02-Digital-Channel-Strategy-Governance.md
├── 03-Web-Messaging.md
├── 04-Web-Messenger-Deployment.md
├── 05-Web-Chat.md
├── 06-SMS.md
├── 07-Open-Messaging.md
├── 08-WhatsApp.md
├── 09-Facebook-Messenger.md
├── 10-Instagram-Messaging.md
├── 11-Apple-Messages-for-Business.md
├── 12-Email.md
├── 13-Social-External-Messaging.md
├── 14-Digital-Bot-Integration.md
├── 15-Digital-Architect-Flows.md
├── 16-Digital-Menus-Journeys.md
├── 17-Digital-Authentication.md
├── 18-Customer-Context-Identity.md
├── 19-Digital-Routing.md
├── 20-Digital-Queues-Skills.md
├── 21-Digital-Priority-SLA.md
├── 22-Digital-Transfers-Escalation.md
├── 23-Digital-Attachments.md
├── 24-Digital-Notifications.md
├── 25-Canned-Responses-Knowledge.md
├── 26-Agent-Digital-Workspace.md
├── 27-Digital-Conversation-History.md
├── 28-Digital-Analytics-Reporting.md
├── 29-Digital-Recording-Compliance.md
├── 30-Digital-Security-Privacy.md
├── 31-Digital-Integrations.md
├── 32-Digital-Testing-Validation.md
├── 33-Digital-Migration-Cutover.md
├── 34-Digital-Operations-BAU.md
├── 35-Digital-Optimisation.md
└── 36-Digital-Governance-Lifecycle.md
```

---

# 15. Domain Capability Catalogue

The following sections define the implementation requirements for each capability.

---
# Layer 2.05 — Architect

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 05 — Architect  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete Genesys Cloud Architect capability set required to design, configure, test, migrate and operate customer interaction flows, IVR, self-service, routing orchestration and workflow automation.

---

# 1. Purpose

Genesys Cloud Architect provides the orchestration layer for customer and agent interaction experiences.

This domain defines the capabilities required to design and implement:

- IVR
- Call flows
- In-queue experiences
- Self-service
- Menu structures
- Prompts
- Speech recognition
- DTMF
- Call collection
- Data-driven routing
- Data Actions
- Data Tables
- Schedules
- Holiday schedules
- Common Modules
- Reusable flow components
- Secure flows
- Bot flows
- Digital bot flows
- Workflow automation
- Transfer handling
- Queue routing
- Callback initiation
- Error handling
- Disconnect handling
- Flow-level variables
- Flow-level business logic
- Customer context
- External integrations
- CRM lookups
- Authentication
- Sensitive-data handling
- Flow testing
- Flow migration
- Flow version management
- Production deployment
- Flow monitoring
- Operational support

Architect should be treated as a **solution orchestration capability**, not simply an IVR configuration tool.

---

# 2. Scope

```text
05 Architect
│
├── 01 Architect Architecture
├── 02 Flow Strategy & Governance
├── 03 Inbound Call Flows
├── 04 In-Queue Call Flows
├── 05 Secure Call Flows
├── 06 Workflow Automation
├── 07 Common Modules
├── 08 Bot Flows
├── 09 Digital Bot Flows
├── 10 Menu Design
├── 11 IVR Navigation
├── 12 Prompt Management
├── 13 Text-to-Speech
├── 14 Speech Recognition
├── 15 DTMF & Keypad Input
├── 16 Data Collection
├── 17 Variables & Expressions
├── 18 Data Tables
├── 19 Data Actions
├── 20 External Integrations
├── 21 Customer Context & Lookup
├── 22 Authentication & Verification
├── 23 Routing Orchestration
├── 24 Queue & ACD Integration
├── 25 Schedule & Business Hours
├── 26 Holiday & Closure Handling
├── 27 Callback & Queue Exit
├── 28 Transfer & Escalation
├── 29 Error Handling & Recovery
├── 30 Disconnect & Completion
├── 31 Flow Security & Sensitive Data
├── 32 Flow Testing & Validation
├── 33 Flow Versioning & Promotion
├── 34 Flow Migration & Cutover
├── 35 Architect Operations & BAU
└── 36 Architect Optimisation & Governance
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Architect Architecture | Required |
| Flow Strategy & Governance | Required |
| Inbound Call Flows | Required |
| In-Queue Call Flows | Conditional |
| Secure Call Flows | Conditional |
| Workflow Automation | Conditional |
| Common Modules | Required |
| Bot Flows | Conditional |
| Digital Bot Flows | Conditional |
| Menu Design | Required |
| IVR Navigation | Required |
| Prompt Management | Required |
| Text-to-Speech | Required |
| Speech Recognition | Conditional |
| DTMF & Keypad Input | Required |
| Data Collection | Required |
| Variables & Expressions | Required |
| Data Tables | Conditional |
| Data Actions | Conditional |
| External Integrations | Conditional |
| Customer Context & Lookup | Conditional |
| Authentication & Verification | Conditional |
| Routing Orchestration | Required |
| Queue & ACD Integration | Required |
| Schedule & Business Hours | Required |
| Holiday & Closure Handling | Required |
| Callback & Queue Exit | Conditional |
| Transfer & Escalation | Required |
| Error Handling & Recovery | Required |
| Disconnect & Completion | Required |
| Flow Security & Sensitive Data | Required |
| Flow Testing & Validation | Required |
| Flow Versioning & Promotion | Required |
| Flow Migration & Cutover | Conditional |
| Architect Operations & BAU | Required |
| Architect Optimisation & Governance | Required |

---

# 4. Architect Architecture

```text
Customer / Agent / System Event
              │
              ▼
       Architect Flow
              │
              ├── Identify Customer
              │
              ├── Determine Context
              │
              ├── Collect Input
              │
              ├── Validate Input
              │
              ├── Perform Data Lookup
              │
              ├── Execute Business Logic
              │
              ├── Determine Customer Intent
              │
              ├── Self-Service
              │
              ├── Route to Queue
              │
              ├── Transfer
              │
              ├── Callback
              │
              └── Terminate
              │
              ▼
      Interaction Outcome
```

Architect commonly sits between the interaction entry point and downstream Genesys Cloud capabilities.

```text
Voice / Digital Entry
        │
        ▼
     Architect
        │
        ├── Data
        ├── Customer Context
        ├── Business Rules
        ├── Self-Service
        ├── Authentication
        ├── Routing
        ├── Queue
        └── Transfer
        │
        ▼
   Agent / Automation
```

---

# 5. Design Principles

1. Architect flows must be designed around customer journeys.
2. Flow logic should be simple enough to be understood and supported by the operational team.
3. Reusable functionality should be implemented through Common Modules where appropriate.
4. Business logic should not be duplicated unnecessarily.
5. Data Actions should be used for external integration requirements.
6. Data Tables should be used for appropriate configuration-driven business rules.
7. Sensitive data must not be unnecessarily exposed to agents or stored in insecure locations.
8. Every flow must have explicit failure handling.
9. Every customer input must have invalid-input handling.
10. Every customer interaction must have a defined exit path.
11. Schedule and holiday behaviour must be explicitly designed.
12. Architect should not become a replacement for a dedicated external business-rules engine unless that is an intentional architecture decision.
13. Flow complexity should be actively governed.
14. Production flow changes must follow controlled promotion processes.
15. Testing must cover both successful and unsuccessful customer journeys.
16. Voice prompts must be designed for accessibility and usability.
17. IVR menus should minimise unnecessary customer navigation.
18. Self-service should be measured against containment and customer-experience objectives.
19. External dependencies must have timeout and failure behaviour.
20. Architect design must align with ACD Routing and Voice & Telephony architecture.

---

# 6. Major Dependencies

Architect depends on:

- Core Platform
- Identity & Access
- Voice & Telephony
- ACD Routing
- Queues
- Users
- Divisions
- Schedules
- Holidays
- Data Tables
- Data Actions
- CRM
- External APIs
- Customer data
- Digital channels
- Bot capabilities
- Security architecture
- Reporting
- Operational processes

Architect provides dependencies for:

- Voice routing
- IVR
- Self-service
- Queue entry
- In-queue experience
- Customer authentication
- Callback
- Data lookup
- Business-rule evaluation
- Digital self-service
- Workflow automation

---

# 7. Layer 1 Mapping

| Layer 1 Phase | Architect Activities |
|---|---|
| Phase 1 — Initiation | Establish Architect scope and ownership |
| Phase 2 — Discovery | Discover existing IVR, flows and business processes |
| Phase 3 — Requirements | Define flow and self-service requirements |
| Phase 4 — Architecture | Design Architect architecture |
| Phase 5 — Platform Foundation | Configure Architect foundation |
| Phase 6 — Solution Build | Build and configure flows |
| Phase 7 — Integration & Migration | Integrate external systems and migrate flows |
| Phase 8 — Testing | Execute flow and integration testing |
| Phase 9 — Operational Readiness | Prepare flow support |
| Phase 10 — Production Deployment | Promote and activate production flows |
| Phase 11 — Hypercare | Monitor flow behaviour |
| Phase 12 — BAU Handover | Transfer ownership |

---

# 8. Standard Architect Development Lifecycle

```text
Business Requirement
        │
        ▼
Customer Journey
        │
        ▼
Flow Design
        │
        ▼
Technical Design
        │
        ▼
DEV Build
        │
        ▼
Developer Testing
        │
        ▼
System Integration Testing
        │
        ▼
User Acceptance Testing
        │
        ▼
Production Readiness
        │
        ▼
Production Promotion
        │
        ▼
Hypercare
        │
        ▼
BAU
```

---

# 9. Standard Spreadsheet Task Model

Every implementation task must eventually support:

| Field | Requirement |
|---|---|
| Task ID | Unique task identifier |
| Layer | Layer 2 |
| Domain | 05 |
| Capability | Architect capability |
| Phase | Layer 1 phase |
| Workstream | Architect |
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

# 10. Standard Flow Design Artefacts

A project may require:

- Customer journey map
- IVR call-flow diagram
- Flow inventory
- Flow requirements document
- Flow design specification
- Flow decision matrix
- Prompt catalogue
- Data dictionary
- Data Action specification
- Data Table catalogue
- Integration specification
- Authentication design
- Error-handling matrix
- Routing matrix
- Schedule matrix
- Holiday matrix
- Flow test plan
- Flow traceability matrix
- Flow deployment plan
- Flow rollback plan
- Architect operations runbook

---

# 11. Standard Architect Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Overly complex IVR | High | Simplify customer journey |
| Poor prompt design | Medium | Conduct usability testing |
| Missing failure handling | High | Require error-path design |
| External API dependency | High | Define timeout/fallback behaviour |
| Excessive Data Actions | Medium | Rationalise integrations |
| Hard-coded business rules | Medium | Use appropriate configuration mechanisms |
| Duplicate flow logic | Medium | Use Common Modules |
| Incorrect schedule handling | High | Test boundary conditions |
| Incorrect holiday handling | High | Validate annual calendar |
| Sensitive information exposed | High | Apply secure-flow patterns |
| Flow version confusion | High | Formal version-control process |
| Uncontrolled production changes | High | Enforce change management |
| Poor routing integration | High | Coordinate with ACD Routing |
| Insufficient test coverage | High | Use journey-based test matrix |
| Customer self-service failure | High | Define agent escalation path |

---

# 12. Definition of Done

The Architect domain is complete when:

- Architect architecture is approved.
- Flow inventory is complete.
- Customer journeys are documented.
- Flow requirements are approved.
- Flow designs are approved.
- Prompt requirements are defined.
- Data requirements are defined.
- Integration dependencies are documented.
- Routing integration is documented.
- Schedule behaviour is documented.
- Holiday behaviour is documented.
- Error handling is defined.
- Security requirements are defined.
- Required flows are built.
- Required integrations are configured.
- Developer testing is complete.
- SIT is complete.
- UAT is complete.
- Production versions are approved.
- Deployment procedures are approved.
- Operational runbooks are complete.

---

# 13. Phase Gate

```text
BUSINESS REQUIREMENTS APPROVED
          +
CUSTOMER JOURNEYS APPROVED
          +
FLOW ARCHITECTURE APPROVED
          +
TECHNICAL DESIGN APPROVED
          +
FLOW BUILD COMPLETE
          +
INTEGRATIONS VALIDATED
          +
FLOW TESTING PASSED
          +
UAT ACCEPTED
          +
PRODUCTION VERSION APPROVED
          ↓
ARCHITECT READY FOR PRODUCTION
```

---

# 14. Domain File Catalogue

```text
05-Architect/
│
├── README.md
├── 01-Architect-Architecture.md
├── 02-Flow-Strategy-Governance.md
├── 03-Inbound-Call-Flows.md
├── 04-In-Queue-Call-Flows.md
├── 05-Secure-Call-Flows.md
├── 06-Workflow-Automation.md
├── 07-Common-Modules.md
├── 08-Bot-Flows.md
├── 09-Digital-Bot-Flows.md
├── 10-Menu-Design.md
├── 11-IVR-Navigation.md
├── 12-Prompt-Management.md
├── 13-Text-to-Speech.md
├── 14-Speech-Recognition.md
├── 15-DTMF-Keypad-Input.md
├── 16-Data-Collection.md
├── 17-Variables-Expressions.md
├── 18-Data-Tables.md
├── 19-Data-Actions.md
├── 20-External-Integrations.md
├── 21-Customer-Context-Lookup.md
├── 22-Authentication-Verification.md
├── 23-Routing-Orchestration.md
├── 24-Queue-ACD-Integration.md
├── 25-Schedule-Business-Hours.md
├── 26-Holiday-Closure-Handling.md
├── 27-Callback-Queue-Exit.md
├── 28-Transfer-Escalation.md
├── 29-Error-Handling-Recovery.md
├── 30-Disconnect-Completion.md
├── 31-Flow-Security-Sensitive-Data.md
├── 32-Flow-Testing-Validation.md
├── 33-Flow-Versioning-Promotion.md
├── 34-Flow-Migration-Cutover.md
├── 35-Architect-Operations-BAU.md
└── 36-Architect-Optimisation-Governance.md
```

---

# 15. Domain Completion

The individual capability sections below form the detailed Layer 2.05 Architect catalogue.

The capability catalogue intentionally remains separate from the final implementation schedule.

Each capability will eventually be decomposed into atomic project tasks containing:

- Task ID
- Phase
- Workstream
- Capability
- Task
- Description
- Dependencies
- Role
- Customer responsibility
- Environment
- Effort
- Duration
- Deliverable
- Acceptance criteria
- Critical-path indicator

---
# Layer 2.04 — ACD Routing

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 04 — ACD Routing  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete Genesys Cloud Automatic Call Distribution (ACD) and interaction-routing capability set required to design, configure, test, migrate and operate customer interaction routing.

---

# 1. Purpose

ACD Routing defines how customer interactions are classified, prioritised, routed, queued, distributed and delivered to the appropriate agents or automated services.

The domain covers:

- ACD architecture
- Queues
- Routing methods
- Skills
- Skill proficiency
- Bullseye routing
- Preferred agents
- Queue membership
- Agent utilisation
- Presence and availability
- Routing status
- Evaluation/routing criteria
- Priority
- Estimated wait time
- In-queue flows
- Overflow
- Alternate routing
- Business-hours routing
- After-hours routing
- Holiday routing
- Callback routing
- Voice routing
- Digital routing
- Email routing
- Message routing
- Social interaction routing
- Language routing
- Department/business-unit routing
- Agent groups
- Workforce dependencies
- Capacity planning dependencies
- Routing testing
- Routing optimisation
- Routing operations

---

# 2. Scope

```text
04 ACD Routing
│
├── 01 ACD Routing Architecture
├── 02 Interaction Routing Strategy
├── 03 Queue Architecture
├── 04 Queue Configuration
├── 05 Queue Membership
├── 06 Routing Methods
├── 07 Skills
├── 08 Skill Proficiency
├── 09 Bullseye Routing
├── 10 Preferred Agents
├── 11 Agent Utilisation & Capacity
├── 12 Presence & Routing Status
├── 13 Priority & Interaction Prioritisation
├── 14 Routing Evaluation Criteria
├── 15 Language Routing
├── 16 Department & Business Unit Routing
├── 17 In-Queue Flows
├── 18 Estimated Wait Time & Position
├── 19 Overflow & Alternate Routing
├── 20 Business Hours & Schedule Routing
├── 21 Holiday Routing
├── 22 Callback Routing
├── 23 Voice ACD Routing
├── 24 Digital ACD Routing
├── 25 Email Routing
├── 26 Message & Social Routing
├── 27 Agent Groups & Routing Pools
├── 28 Routing Dependencies
├── 29 Routing Testing & Validation
├── 30 Routing Optimisation
├── 31 Routing Migration & Cutover
└── 32 ACD Routing Operations & BAU
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| ACD Routing Architecture | Required |
| Interaction Routing Strategy | Required |
| Queue Architecture | Required |
| Queue Configuration | Required |
| Queue Membership | Required |
| Routing Methods | Required |
| Skills | Conditional |
| Skill Proficiency | Conditional |
| Bullseye Routing | Conditional |
| Preferred Agents | Conditional |
| Agent Utilisation & Capacity | Required |
| Presence & Routing Status | Required |
| Priority & Interaction Prioritisation | Required |
| Routing Evaluation Criteria | Required |
| Language Routing | Conditional |
| Department & Business Unit Routing | Conditional |
| In-Queue Flows | Required |
| Estimated Wait Time & Position | Conditional |
| Overflow & Alternate Routing | Required |
| Business Hours & Schedule Routing | Required |
| Holiday Routing | Required |
| Callback Routing | Conditional |
| Voice ACD Routing | Conditional |
| Digital ACD Routing | Conditional |
| Email Routing | Conditional |
| Message & Social Routing | Conditional |
| Agent Groups & Routing Pools | Conditional |
| Routing Dependencies | Required |
| Routing Testing & Validation | Required |
| Routing Optimisation | Required |
| Routing Migration & Cutover | Conditional |
| ACD Routing Operations & BAU | Required |

---

# 4. Routing Architecture

```text
Customer Interaction
        │
        ▼
Interaction Entry Point
        │
        ▼
Identify Interaction Type
        │
        ├── Voice
        ├── Chat
        ├── Message
        ├── Email
        └── Other Digital
        │
        ▼
Determine Business Context
        │
        ▼
Determine Queue
        │
        ▼
Apply Routing Rules
        │
        ├── Priority
        ├── Skills
        ├── Language
        ├── Agent Availability
        ├── Utilisation
        ├── Preferred Agent
        └── Bullseye / Expansion
        │
        ▼
Select Eligible Agent
        │
        ▼
Deliver Interaction
        │
        ▼
Agent Handling
        │
        ▼
Wrap-up / Completion
```

---

# 5. Key Design Principles

1. Design routing around business outcomes rather than Genesys configuration objects.
2. Establish the queue model before building routing logic.
3. Avoid unnecessary skill complexity.
4. Use skills only where they materially improve routing outcomes.
5. Define priority rules explicitly.
6. Treat queue membership and routing eligibility as separate concepts.
7. Design overflow and failure handling before production.
8. Define routing behaviour for every business-hours state.
9. Ensure routing logic is consistent across interaction channels where appropriate.
10. Minimise unnecessary routing-rule duplication.
11. Define operational ownership for queue and routing changes.
12. Test routing using realistic interaction volumes and agent states.
13. Document every routing exception.
14. Consider reporting and analytics requirements when designing routing.
15. Validate routing behaviour across all relevant interaction types.
16. Avoid designing routing in isolation from Workforce Management and agent scheduling.
17. Ensure routing design supports the intended service-level model.
18. Design for operational maintainability.

---

# 6. Major Dependencies

ACD Routing depends on:

- Core Platform
- Identity & Access
- Voice & Telephony
- Digital channels
- Architect
- Users
- Divisions
- Roles
- Queues
- Skills
- Presence
- Workforce Management
- Business hours
- Holidays
- Data Actions
- Integrations
- Reporting
- Quality Management
- Customer requirements

ACD Routing is a prerequisite for:

- Agent interaction delivery
- Queue management
- Service levels
- SLA reporting
- Agent utilisation
- Voice routing
- Digital routing
- Callback
- Routing analytics
- Workforce planning

---

# 7. Layer 1 Mapping

| Layer 1 Phase | ACD Routing Activities |
|---|---|
| Phase 1 — Initiation | Establish routing scope and ownership |
| Phase 2 — Discovery | Discover queues, routing rules, skills and existing processes |
| Phase 3 — Requirements | Define routing requirements |
| Phase 4 — Architecture | Define queue and routing architecture |
| Phase 5 — Platform Foundation | Configure routing foundation |
| Phase 6 — Solution Build | Configure queues and routing |
| Phase 7 — Integration & Migration | Integrate routing dependencies and migrate existing routing |
| Phase 8 — Testing | Execute routing testing |
| Phase 9 — Operational Readiness | Establish routing support |
| Phase 10 — Production Deployment | Activate production routing |
| Phase 11 — Hypercare | Monitor routing |
| Phase 12 — BAU Handover | Transfer routing ownership |

---

# 8. Standard Spreadsheet Task Model

Every implementation task must eventually support:

| Field | Requirement |
|---|---|
| Task ID | Unique task identifier |
| Layer | Layer 2 |
| Domain | 04 |
| Capability | ACD capability |
| Phase | Layer 1 phase |
| Workstream | ACD Routing |
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

- ACD routing strategy
- Queue catalogue
- Queue hierarchy
- Queue configuration matrix
- Queue membership matrix
- Routing method matrix
- Skill catalogue
- Skill proficiency matrix
- Priority matrix
- Bullseye routing design
- Preferred-agent design
- Agent utilisation design
- In-queue flow design
- Overflow design
- Business-hours routing matrix
- Holiday routing matrix
- Callback routing design
- Digital routing design
- Routing test plan
- Routing migration plan
- Routing operations runbook

---

# 10. Standard Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Excessive skill complexity | High | Rationalise skills during design |
| Incorrect queue structure | High | Validate queue model against business processes |
| Incorrect priority | High | Define explicit priority matrix |
| Agents unavailable for routing | High | Validate presence and utilisation configuration |
| Incorrect overflow | High | Test all failure states |
| Poor service-level performance | High | Validate routing against forecast volumes |
| Routing differs by channel | Medium | Establish cross-channel routing standards |
| Incorrect queue membership | High | Validate user/queue matrix |
| Bullseye behaviour misunderstood | Medium | Execute detailed test scenarios |
| Inadequate routing monitoring | Medium | Establish operational dashboards |
| Routing changes introduce regressions | High | Formal change/test process |

---

# 11. Definition of Done

The ACD Routing domain is complete when:

- Routing architecture is approved.
- Queue architecture is approved.
- Queue catalogue is complete.
- Queue membership is defined.
- Routing methods are defined.
- Skills are defined where required.
- Skill proficiency is defined where required.
- Priority rules are defined.
- Bullseye routing is defined where required.
- Preferred-agent routing is defined where required.
- Agent utilisation is defined.
- Presence requirements are defined.
- In-queue flows are defined.
- Overflow is defined.
- Business hours are defined.
- Holiday routing is defined.
- Callback routing is defined where required.
- Digital routing is defined where required.
- Routing dependencies are configured.
- Routing tests pass.
- UAT passes.
- Production routing is approved.
- Operational procedures are documented.

---

# 12. Phase Gate

```text
ROUTING REQUIREMENTS APPROVED
          +
QUEUE MODEL APPROVED
          +
ROUTING RULES APPROVED
          +
SKILLS / PRIORITY APPROVED
          +
IN-QUEUE / OVERFLOW DESIGN
          +
CONFIGURATION COMPLETE
          +
ROUTING TESTING PASSED
          +
UAT ACCEPTED
          +
PRODUCTION CUTOVER APPROVED
          ↓
ACD ROUTING READY
```

---

# 13. Domain File Catalogue

```text
04-ACD-Routing/
│
├── README.md
├── 01-ACD-Routing-Architecture.md
├── 02-Interaction-Routing-Strategy.md
├── 03-Queue-Architecture.md
├── 04-Queue-Configuration.md
├── 05-Queue-Membership.md
├── 06-Routing-Methods.md
├── 07-Skills.md
├── 08-Skill-Proficiency.md
├── 09-Bullseye-Routing.md
├── 10-Preferred-Agents.md
├── 11-Agent-Utilisation-Capacity.md
├── 12-Presence-Routing-Status.md
├── 13-Priority-Interaction-Prioritisation.md
├── 14-Routing-Evaluation-Criteria.md
├── 15-Language-Routing.md
├── 16-Department-Business-Unit-Routing.md
├── 17-In-Queue-Flows.md
├── 18-Estimated-Wait-Time-Position.md
├── 19-Overflow-Alternate-Routing.md
├── 20-Business-Hours-Schedule-Routing.md
├── 21-Holiday-Routing.md
├── 22-Callback-Routing.md
├── 23-Voice-ACD-Routing.md
├── 24-Digital-ACD-Routing.md
├── 25-Email-Routing.md
├── 26-Message-Social-Routing.md
├── 27-Agent-Groups-Routing-Pools.md
├── 28-Routing-Dependencies.md
├── 29-Routing-Testing-Validation.md
├── 30-Routing-Optimisation.md
├── 31-Routing-Migration-Cutover.md
└── 32-ACD-Routing-Operations-BAU.md
```

---

# 14. Domain Completion

The individual capability documents form the detailed Layer 2.04 ACD Routing catalogue.

These documents define the capabilities that must be considered during a Genesys Cloud deployment.

They are not yet the final implementation schedule.

The later implementation-task catalogue will decompose each capability into atomic tasks with dependencies, roles, effort, duration, acceptance criteria and critical-path indicators.

---

# Domain Completion Gate

**Status:** Ready for capability-level task decomposition.

---
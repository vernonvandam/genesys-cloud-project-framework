# Layer 2.07 — Workforce Management & Employee Engagement

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 07 — Workforce Management & Employee Engagement  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the capabilities required to design, configure, integrate, test, deploy and operate Genesys Cloud Workforce Management (WFM), employee engagement, performance management, scheduling, forecasting, adherence and related workforce capabilities.

---

# 1. Purpose

Workforce Management and Employee Engagement provides the operational workforce layer required to ensure that the right people, with the right skills, are available at the right time to meet customer demand.

This domain defines capabilities required to implement:

- Workforce Management
- Workforce planning
- Forecasting
- Forecast models
- Forecast generation
- Workload analysis
- Staffing requirements
- Service-level planning
- Scheduling
- Schedule generation
- Schedule optimisation
- Shift planning
- Activities
- Activity codes
- Business units
- Management units
- Planning groups
- Service goals
- Intraday management
- Real-time adherence
- Schedule adherence
- Agent adherence
- Time-off management
- Time-off requests
- Time-off plans
- Time-off categories
- Shift trades
- Schedule changes
- Agent self-service
- Workforce notifications
- Workforce communications
- Performance management
- Gamification where applicable
- Employee engagement
- Employee feedback
- Agent development
- Coaching
- Recognition
- Learning integration
- Employee experience
- Workforce analytics
- WFM reporting
- Capacity planning
- Staffing optimisation
- Operational governance
- WFM integrations
- HR / HCM integration
- Payroll-related integration
- Data integration
- Workforce migration
- WFM testing
- WFM cutover
- WFM operations
- Continuous optimisation

Workforce Management must be designed in conjunction with:

- ACD routing
- Queues
- Skills
- Service levels
- Interaction volumes
- Historical data
- Agent schedules
- Agent availability
- Business hours
- Shrinkage
- Occupancy
- Adherence
- Customer demand
- Employee experience

---

# 2. Scope

```text
07 Workforce Management & Employee Engagement
│
├── 01 Workforce Management Architecture
├── 02 WFM Strategy & Governance
├── 03 Workforce Management Licensing
├── 04 Business Units
├── 05 Management Units
├── 06 Planning Groups
├── 07 Service Goals
├── 08 Forecasting Strategy
├── 09 Forecast Models
├── 10 Historical Data & Workload
├── 11 Forecast Generation
├── 12 Staffing Requirements
├── 13 Shrinkage & Capacity Planning
├── 14 Scheduling Strategy
├── 15 Activities & Activity Codes
├── 16 Shift Planning
├── 17 Schedule Generation
├── 18 Schedule Optimisation
├── 19 Schedule Publication
├── 20 Time-Off Management
├── 21 Time-Off Plans & Requests
├── 22 Shift Trades
├── 23 Agent Self-Service
├── 24 Intraday Management
├── 25 Real-Time Adherence
├── 26 Schedule Adherence
├── 27 Workforce Notifications
├── 28 Workforce Communications
├── 29 Performance Management
├── 30 Employee Engagement
├── 31 Coaching & Development
├── 32 Recognition & Gamification
├── 33 Learning & Knowledge Integration
├── 34 Employee Experience
├── 35 WFM Analytics & Reporting
├── 36 Capacity & Staffing Optimisation
├── 37 HR / HCM Integration
├── 38 Payroll & Time Integration
├── 39 Workforce Data Integration
├── 40 WFM Security & Access
├── 41 WFM Testing & Validation
├── 42 WFM Migration & Cutover
├── 43 WFM Operations & BAU
├── 44 WFM Governance & Lifecycle
└── 45 WFM Continuous Optimisation
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Workforce Management Architecture | Required |
| WFM Strategy & Governance | Required |
| WFM Licensing | Required |
| Business Units | Required |
| Management Units | Required |
| Planning Groups | Required |
| Service Goals | Required |
| Forecasting Strategy | Required |
| Forecast Models | Required |
| Historical Data & Workload | Required |
| Forecast Generation | Required |
| Staffing Requirements | Required |
| Shrinkage & Capacity Planning | Required |
| Scheduling Strategy | Required |
| Activities & Activity Codes | Required |
| Shift Planning | Required |
| Schedule Generation | Required |
| Schedule Optimisation | Required |
| Schedule Publication | Required |
| Time-Off Management | Required |
| Time-Off Plans & Requests | Required |
| Shift Trades | Conditional |
| Agent Self-Service | Required |
| Intraday Management | Required |
| Real-Time Adherence | Required |
| Schedule Adherence | Required |
| Workforce Notifications | Required |
| Workforce Communications | Conditional |
| Performance Management | Conditional |
| Employee Engagement | Conditional |
| Coaching & Development | Conditional |
| Recognition & Gamification | Conditional |
| Learning & Knowledge Integration | Conditional |
| Employee Experience | Required |
| WFM Analytics & Reporting | Required |
| Capacity & Staffing Optimisation | Required |
| HR / HCM Integration | Conditional |
| Payroll & Time Integration | Conditional |
| Workforce Data Integration | Required |
| WFM Security & Access | Required |
| WFM Testing & Validation | Required |
| WFM Migration & Cutover | Conditional |
| WFM Operations & BAU | Required |
| WFM Governance & Lifecycle | Required |
| WFM Continuous Optimisation | Required |

---

# 4. Workforce Management Architecture

```text
Business Demand
      │
      ▼
Historical Interaction Data
      │
      ▼
Workload Analysis
      │
      ▼
Forecast
      │
      ▼
Staffing Requirements
      │
      ├── Service Goal
      ├── Occupancy
      ├── Shrinkage
      └── Skills
             │
             ▼
        Schedule Generation
             │
             ▼
       Schedule Optimisation
             │
             ▼
       Schedule Publication
             │
             ▼
          Agents
             │
             ├── Time Off
             ├── Shift Trades
             └── Schedule Changes
             │
             ▼
      Intraday Management
             │
             ▼
       Real-Time Adherence
             │
             ▼
       Operational Reporting
             │
             ▼
         Optimisation
```

---

# 5. Employee Engagement Architecture

```text
Employee
   │
   ├── Schedule
   ├── Time Off
   ├── Shift Trade
   ├── Performance
   ├── Feedback
   ├── Coaching
   ├── Recognition
   └── Development
          │
          ▼
   Employee Experience
          │
          ▼
   Engagement Outcomes
          │
          ▼
   Customer Experience
```

---

# 6. Workforce Design Principles

1. WFM must be designed from customer demand backwards.
2. Forecasts must be based on appropriate historical data.
3. Forecast assumptions must be documented.
4. Planning groups must align with operational demand.
5. Skills must align with the ACD routing model.
6. Service goals must be explicitly agreed.
7. Shrinkage must be explicitly modelled.
8. Schedules must reflect operational requirements and employee constraints.
9. Schedule adherence must be measurable.
10. Intraday management must have clear ownership.
11. WFM exceptions must have documented escalation paths.
12. Agent self-service should minimise unnecessary supervisor intervention.
13. Time-off rules must align with customer and employment requirements.
14. Employee experience must be considered alongside service level.
15. Workforce data must be governed.
16. WFM permissions must follow least privilege.
17. WFM reporting must have defined KPI ownership.
18. Forecast accuracy must be monitored.
19. Staffing models must be periodically recalibrated.
20. WFM should be integrated into the overall operational governance model.

---

# 7. Major Dependencies

Workforce Management depends on:

- Core Platform
- Identity & Access
- ACD Routing
- Queues
- Skills
- Users
- Divisions
- Business Hours
- Interaction volumes
- Historical interaction data
- Customer demand
- Service-level targets
- Agent availability
- Agent employment rules
- HR data
- Payroll data where applicable
- Reporting
- Integrations
- Security
- Operations

Workforce Management provides dependencies for:

- Agent scheduling
- Capacity planning
- Staffing decisions
- Intraday management
- Adherence
- Operational reporting
- Employee self-service
- Service-level optimisation

---

# 8. Layer 1 Mapping

| Layer 1 Phase | WFM Activities |
|---|---|
| Phase 1 — Initiation | Establish WFM scope |
| Phase 2 — Discovery | Discover workforce model |
| Phase 3 — Requirements | Define forecasting and scheduling requirements |
| Phase 4 — Architecture | Design WFM architecture |
| Phase 5 — Platform Foundation | Configure WFM foundation |
| Phase 6 — Solution Build | Configure forecasting, scheduling and adherence |
| Phase 7 — Integration & Migration | Integrate HR/WFM data and migrate |
| Phase 8 — Testing | Execute WFM testing |
| Phase 9 — Operational Readiness | Prepare WFM operations |
| Phase 10 — Production Deployment | Activate WFM |
| Phase 11 — Hypercare | Monitor WFM performance |
| Phase 12 — BAU Handover | Transfer WFM operations |

---

# 9. Workforce Management Lifecycle

```text
Demand
  │
  ▼
Historical Data
  │
  ▼
Forecast
  │
  ▼
Capacity Requirement
  │
  ▼
Staffing Requirement
  │
  ▼
Schedule
  │
  ▼
Publish
  │
  ▼
Agent Execution
  │
  ▼
Adherence
  │
  ▼
Intraday Management
  │
  ▼
Actual vs Forecast
  │
  ▼
Reforecast / Optimise
```

---

# 10. Standard WFM Artefacts

A project may require:

- WFM strategy
- Workforce architecture
- Workforce operating model
- Business-unit model
- Management-unit model
- Planning-group model
- Service-goal catalogue
- Forecasting strategy
- Forecast assumptions
- Historical data assessment
- Staffing model
- Shrinkage model
- Capacity plan
- Activity code catalogue
- Schedule rules
- Shift templates
- Time-off plan
- Time-off rules
- Shift-trade rules
- Agent self-service model
- Adherence model
- Intraday management model
- WFM reporting catalogue
- KPI definitions
- HR integration design
- Payroll integration design
- WFM data mapping
- WFM security model
- WFM test plan
- WFM migration plan
- WFM cutover plan
- WFM operations runbook
- WFM support model
- WFM optimisation framework

---

# 11. Standard Spreadsheet Task Model

| Field | Requirement |
|---|---|
| Task ID | Unique identifier |
| Layer | Layer 2 |
| Domain | 07 |
| Capability | WFM capability |
| Phase | Layer 1 phase |
| Workstream | Workforce Management |
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

# 12. WFM Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Poor historical data | High | Perform data-quality assessment |
| Incorrect forecast | High | Validate forecast methodology |
| Incorrect service goals | High | Obtain business approval |
| Incorrect staffing assumptions | High | Validate capacity model |
| Poor shrinkage model | High | Establish documented assumptions |
| Incorrect queue mapping | High | Reconcile with ACD design |
| Incorrect skill mapping | High | Reconcile with routing |
| Poor schedule design | High | Validate operational rules |
| Insufficient agent availability | High | Validate workforce capacity |
| Incorrect time-off rules | High | Validate business and employment rules |
| Poor adherence configuration | High | Define adherence model |
| Insufficient WFM training | Medium | Train planners and supervisors |
| Poor data integration | High | Validate integration |
| Payroll mismatch | High | Reconcile source systems |
| Inadequate permissions | High | Apply least privilege |
| Poor reporting | Medium | Establish KPI catalogue |
| Forecast not monitored | High | Establish ongoing review |
| Employee dissatisfaction | Medium | Include employee experience |
| WFM configuration drift | Medium | Establish governance |

---

# 13. Definition of Done

The WFM domain is complete when:

- WFM architecture is approved.
- Workforce strategy is approved.
- Licensing is validated.
- Business units are defined.
- Management units are defined.
- Planning groups are defined.
- Service goals are approved.
- Forecasting requirements are defined.
- Historical data is validated.
- Staffing requirements are defined.
- Shrinkage assumptions are approved.
- Scheduling requirements are defined.
- Activities are defined.
- Schedules are generated.
- Schedules are validated.
- Time-off processes are configured.
- Shift trades are configured where required.
- Agent self-service is available.
- Intraday processes are defined.
- Adherence is configured.
- Workforce notifications are configured.
- Reporting is validated.
- Integrations are tested.
- WFM security is approved.
- WFM UAT is complete.
- Operational readiness is complete.

---

# 14. Domain Gate

```text
WFM STRATEGY APPROVED
          +
WFM ARCHITECTURE APPROVED
          +
FORECAST MODEL APPROVED
          +
STAFFING MODEL APPROVED
          +
SCHEDULING MODEL APPROVED
          +
TIME-OFF MODEL APPROVED
          +
ADHERENCE MODEL APPROVED
          +
INTEGRATIONS VALIDATED
          +
REPORTING VALIDATED
          +
UAT ACCEPTED
          +
OPERATIONS READY
          ↓
WFM READY FOR PRODUCTION
```

---

# 15. Domain File Catalogue

```text
07-Workforce-Management-Employee-Engagement/
│
├── README.md
├── 01-Workforce-Management-Architecture.md
├── 02-WFM-Strategy-Governance.md
├── 03-WFM-Licensing.md
├── 04-Business-Units.md
├── 05-Management-Units.md
├── 06-Planning-Groups.md
├── 07-Service-Goals.md
├── 08-Forecasting-Strategy.md
├── 09-Forecast-Models.md
├── 10-Historical-Data-Workload.md
├── 11-Forecast-Generation.md
├── 12-Staffing-Requirements.md
├── 13-Shrinkage-Capacity-Planning.md
├── 14-Scheduling-Strategy.md
├── 15-Activities-Activity-Codes.md
├── 16-Shift-Planning.md
├── 17-Schedule-Generation.md
├── 18-Schedule-Optimisation.md
├── 19-Schedule-Publication.md
├── 20-Time-Off-Management.md
├── 21-Time-Off-Plans-Requests.md
├── 22-Shift-Trades.md
├── 23-Agent-Self-Service.md
├── 24-Intraday-Management.md
├── 25-Real-Time-Adherence.md
├── 26-Schedule-Adherence.md
├── 27-Workforce-Notifications.md
├── 28-Workforce-Communications.md
├── 29-Performance-Management.md
├── 30-Employee-Engagement.md
├── 31-Coaching-Development.md
├── 32-Recognition-Gamification.md
├── 33-Learning-Knowledge-Integration.md
├── 34-Employee-Experience.md
├── 35-WFM-Analytics-Reporting.md
├── 36-Capacity-Staffing-Optimisation.md
├── 37-HR-HCM-Integration.md
├── 38-Payroll-Time-Integration.md
├── 39-Workforce-Data-Integration.md
├── 40-WFM-Security-Access.md
├── 41-WFM-Testing-Validation.md
├── 42-WFM-Migration-Cutover.md
├── 43-WFM-Operations-BAU.md
├── 44-WFM-Governance-Lifecycle.md
└── 45-WFM-Continuous-Optimisation.md
```

---

# 16. Domain Capability Catalogue

The following sections define the implementation requirements for each capability.

---

# 17. Implementation Task Decomposition Preview

The final implementation task catalogue will decompose the capability catalogue into atomic project tasks.

Example:

```text
WFM-007-001  Inventory current workforce management processes
WFM-007-002  Inventory current WFM platform
WFM-007-003  Inventory current WFM users
WFM-007-004  Inventory current workforce organisational structure
WFM-007-005  Inventory current queues
WFM-007-006  Inventory current skills
WFM-007-007  Inventory current schedules
WFM-007-008  Inventory current activity codes
WFM-007-009  Inventory current time-off categories
WFM-007-010  Inventory current forecast methodology
WFM-007-011  Inventory current staffing methodology
WFM-007-012  Inventory current adherence methodology
WFM-007-013  Identify WFM business units
WFM-007-014  Define WFM management units
WFM-007-015  Define planning groups
WFM-007-016  Define service goals
WFM-007-017  Define WFM operating model
WFM-007-018  Validate WFM licensing
WFM-007-019  Define forecast strategy
WFM-007-020  Validate historical interaction data
WFM-007-021  Define forecast periods
WFM-007-022  Define forecast assumptions
WFM-007-023  Configure forecast models
WFM-007-024  Generate baseline forecast
WFM-007-025  Validate forecast accuracy
WFM-007-026  Define staffing requirements
WFM-007-027  Define occupancy assumptions
WFM-007-028  Define shrinkage assumptions
WFM-007-029  Configure staffing requirements
WFM-007-030  Validate capacity model
WFM-007-031  Define scheduling strategy
WFM-007-032  Define activities
WFM-007-033  Configure activity codes
WFM-007-034  Define shift patterns
WFM-007-035  Define scheduling rules
WFM-007-036  Define agent scheduling constraints
WFM-007-037  Generate initial schedules
WFM-007-038  Review schedule coverage
WFM-007-039  Optimise schedules
WFM-007-040  Validate schedule compliance
WFM-007-041  Publish schedules
WFM-007-042  Configure time-off categories
WFM-007-043  Configure time-off plans
WFM-007-044  Configure time-off request process
WFM-007-045  Validate time-off capacity
WFM-007-046  Configure shift trades where required
WFM-007-047  Configure agent self-service
WFM-007-048  Define intraday management process
WFM-007-049  Configure real-time adherence
WFM-007-050  Configure schedule adherence
WFM-007-051  Define adherence tolerance
WFM-007-052  Configure workforce notifications
WFM-007-053  Define WFM KPI catalogue
WFM-007-054  Configure WFM reporting
WFM-007-055  Validate forecast reporting
WFM-007-056  Validate staffing reporting
WFM-007-057  Validate adherence reporting
WFM-007-058  Define HR integration requirements
WFM-007-059  Configure HR integration where required
WFM-007-060  Define payroll integration requirements
WFM-007-061  Configure payroll integration where required
WFM-007-062  Define workforce data integration
WFM-007-063  Configure workforce data integration
WFM-007-064  Configure WFM security roles
WFM-007-065  Validate planner permissions
WFM-007-066  Validate supervisor permissions
WFM-007-067  Validate agent permissions
WFM-007-068  Execute WFM functional testing
WFM-007-069  Execute WFM integration testing
WFM-007-070  Execute WFM workforce scenario testing
WFM-007-071  Execute WFM security testing
WFM-007-072  Execute WFM UAT
WFM-007-073  Resolve WFM defects
WFM-007-074  Prepare WFM production cutover
WFM-007-075  Validate production WFM configuration
WFM-007-076  Publish production schedules
WFM-007-077  Execute WFM production smoke testing
WFM-007-078  Execute WFM hypercare
WFM-007-079  Complete WFM operational handover
WFM-007-080  Establish WFM optimisation cadence
```

The final project schedule should expand this considerably further.

Each independently executable configuration, data load, validation, test, approval or operational activity should become an individual spreadsheet task.

---

# 18. Cross-Domain Dependencies

| Dependency Domain | WFM Dependency |
|---|---|
| 01 — Core Platform | Platform configuration, divisions |
| 02 — Identity & Access | Agent, supervisor and planner identities |
| 03 — Voice & Telephony | Voice workload |
| 04 — ACD Routing | Queues, skills, routing and service levels |
| 05 — Architect | Automated interaction workload |
| 06 — Digital | Digital workload and service levels |
| 07 — Workforce | Workforce capability domain |
| 08 — Data & Integrations | HR, payroll and workforce data |
| 09 — Reporting | WFM KPI reporting |
| 10 — Quality | Performance and coaching inputs |
| 11 — Security | Workforce data protection |
| 12 — Testing | WFM SIT and UAT |
| 13 — Migration | Legacy WFM migration |
| 14 — Operations | WFM BAU |
| 15 — Optimisation | Workforce optimisation |

---

# 19. Critical Cross-Domain Relationships

## ACD → WFM

ACD configuration must establish:

- Queues
- Skills
- Media types
- Service levels
- Routing behaviour
- Interaction volumes

These become inputs to workforce planning.

```text
ACD Routing
     │
     ├── Queues
     ├── Skills
     ├── Media
     └── Service Goals
            │
            ▼
          WFM
```

## Digital → WFM

Digital channels contribute:

- Messaging volume
- Email volume
- Response-time requirements
- Digital service levels
- Digital workload

## Architect → WFM

Architect and automation affect:

- Interaction volumes
- Self-service containment
- Agent demand
- Queue demand
- Forecast assumptions

## Quality → WFM

Quality and performance data may contribute to:

- Coaching
- Performance management
- Workforce development
- Employee engagement

## HR → WFM

HR/HCM may provide:

- Employee identity
- Organisational structure
- Manager hierarchy
- Employment status
- Skills
- Workforce attributes

---

# 20. WFM Project Sequence

The recommended implementation sequence is:

```text
01. WFM Discovery
        ↓
02. WFM Strategy
        ↓
03. Licensing
        ↓
04. Organisational Structure
        ↓
05. Queue / Skill Mapping
        ↓
06. Planning Groups
        ↓
07. Service Goals
        ↓
08. Historical Data
        ↓
09. Forecast Model
        ↓
10. Staffing Model
        ↓
11. Shrinkage Model
        ↓
12. Scheduling Model
        ↓
13. Activities
        ↓
14. Shift Model
        ↓
15. Schedule Generation
        ↓
16. Schedule Optimisation
        ↓
17. Time-Off
        ↓
18. Self-Service
        ↓
19. Intraday
        ↓
20. Adherence
        ↓
21. Reporting
        ↓
22. Integrations
        ↓
23. Testing
        ↓
24. UAT
        ↓
25. Cutover
        ↓
26. Hypercare
        ↓
27. BAU
        ↓
28. Optimisation
```

---

# 21. WFM Phase Dependencies

| Activity | Primary Dependency |
|---|---|
| Business Units | Organisational model |
| Management Units | Organisational model |
| Planning Groups | Queues and workload |
| Service Goals | Business requirements |
| Forecasting | Historical data |
| Staffing | Forecast |
| Shrinkage | Workforce assumptions |
| Scheduling | Staffing requirement |
| Schedule Generation | Activities + shifts + staffing |
| Schedule Optimisation | Generated schedule |
| Publication | Approved schedule |
| Time-Off | Workforce rules |
| Shift Trades | Schedule model |
| Adherence | Activities + schedules |
| Intraday | Forecast + actual workload |
| Reporting | WFM data |
| HR Integration | HR system |
| Payroll Integration | Payroll/time system |
| UAT | Configured solution |
| Cutover | UAT acceptance |
| BAU | Production deployment |

---

# 22. Domain Completion Gate

The Workforce Management & Employee Engagement domain is considered **capability-complete** when:

- All WFM capabilities have been assessed.
- Required capabilities are identified.
- Conditional capabilities are assessed.
- WFM architecture is approved.
- WFM operating model is approved.
- Business units are defined.
- Management units are defined.
- Planning groups are defined.
- Service goals are approved.
- Forecast strategy is approved.
- Historical data is validated.
- Forecast models are approved.
- Staffing model is approved.
- Shrinkage model is approved.
- Scheduling strategy is approved.
- Activity catalogue is approved.
- Shift model is approved.
- Time-off model is approved.
- Adherence model is approved.
- Intraday process is defined.
- Employee self-service requirements are defined.
- Reporting requirements are defined.
- Integration requirements are defined.
- Security requirements are defined.
- Testing requirements are defined.
- Migration requirements are defined where applicable.
- Operational requirements are defined.
- Governance requirements are defined.

```text
WFM CAPABILITY CATALOGUE
            │
            ▼
WFM STRATEGY
            │
            ▼
WORKFORCE MODEL
            │
            ▼
FORECAST MODEL
            │
            ▼
STAFFING MODEL
            │
            ▼
SCHEDULING MODEL
            │
            ▼
ADHERENCE MODEL
            │
            ▼
IMPLEMENTATION TASK CATALOGUE
            │
            ▼
EFFORT / DURATION
            │
            ▼
MASTER PROJECT SCHEDULE
```

---

# Domain Completion

**Layer:** 2  
**Domain:** 07 — Workforce Management & Employee Engagement  
**Capability Documents:** 45  
**Status:** Capability catalogue complete  
**Next Activity:** Continue with Layer 2 Domain 08.

This domain defines the **capability catalogue**. It is not yet the final implementation schedule.

The next stage will convert these capabilities into granular implementation tasks suitable for the master Genesys Cloud deployment workbook.

The eventual task model will contain:

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

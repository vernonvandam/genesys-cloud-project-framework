# 07 — Workforce Management & Employee Engagement Task Catalogue

## Layer 10 — Estimation, Resourcing & Project Planning

## 1. Purpose

This directory contains the **Layer 10 implementation task catalogue for the Workforce Management & Employee Engagement capability domain**.

The catalogue translates the Layer 2 Workforce Management & Employee Engagement capabilities and implementation activities into discrete, estimable, assignable, dependency-aware, and schedulable implementation tasks.

The catalogue covers:

- Workforce Management architecture
- WFM strategy and governance
- licensing
- business units
- management units
- planning groups
- service goals
- forecasting
- historical workload
- staffing requirements
- shrinkage
- scheduling
- activities
- shifts
- schedule publication
- time-off
- shift trades
- agent self-service
- intraday management
- adherence
- workforce notifications
- workforce communications
- performance management
- employee engagement
- coaching
- recognition
- learning integration
- employee experience
- analytics and reporting
- capacity planning
- HR/HCM integration
- payroll integration
- workforce data
- security
- testing
- migration
- operations
- governance
- continuous optimisation

---

# 2. Domain Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Task Catalogue Domain | 07 — Workforce Management & Employee Engagement |
| Layer 2 Domain | 07 — Workforce Management & Employee Engagement |
| Domain Type | Workforce / Operational |
| Primary Purpose | Design, configure, integrate, validate and operationalise Genesys Cloud workforce capabilities |
| Primary Delivery Roles | Solution Architect, Genesys Cloud Architect, WFM Consultant, Genesys Cloud Engineer, Data / Integration Engineer |
| Primary Customer Roles | WFM Owner, Workforce Planner, Operations Lead, HR / HCM Lead, Customer Technical Lead |
| Primary Environments | DESIGN, DEV, TEST, UAT, PROD |
| Primary Layer 1 Phases | P01–P12 |
| Task Catalogue Status | In Development |

---

# 3. Relationship to Layer 2

The authoritative capability definitions are maintained within:

```text
Layer 2
└── 07 — Workforce Management & Employee Engagement
```

Layer 10 does not redefine the capability catalogue.

Instead, each capability file decomposes the Layer 2 implementation activities into individual implementation tasks.

The relationship is:

```text
Layer 2 Capability
        │
        ├── Implementation Activity
        │       │
        │       ▼
        │   Layer 10 Task
        │       │
        │       ├── Task
        │       ├── Task
        │       └── Task
        │
        └── Implementation Activity
                │
                ▼
            Layer 10 Task
```

---

# 4. Task ID Convention

Section 07 uses:

```text
L10-07.CC-TTT
```

Where:

| Component | Meaning |
|---|---|
| `L10` | Layer 10 |
| `07` | WFM & Employee Engagement domain |
| `CC` | Capability number |
| `TTT` | Sequential task number |

Examples:

```text
L10-07.01-001
L10-07.01-002
L10-07.01-003
```

---

# 5. Capability Catalogue

| Capability ID | Capability | Task Catalogue File | Classification |
|---|---|---|---|
| 2.07.01 | Workforce Management Architecture | `01-workforce-management-architecture.md` | Required |
| 2.07.02 | WFM Strategy & Governance | `02-wfm-strategy-governance.md` | Required |
| 2.07.03 | WFM Licensing | `03-wfm-licensing.md` | Required |
| 2.07.04 | Business Units | `04-business-units.md` | Required |
| 2.07.05 | Management Units | `05-management-units.md` | Required |
| 2.07.06 | Planning Groups | `06-planning-groups.md` | Required |
| 2.07.07 | Service Goals | `07-service-goals.md` | Required |
| 2.07.08 | Forecasting Strategy | `08-forecasting-strategy.md` | Required |
| 2.07.09 | Forecast Models | `09-forecast-models.md` | Required |
| 2.07.10 | Historical Data & Workload | `10-historical-data-workload.md` | Required |
| 2.07.11 | Forecast Generation | `11-forecast-generation.md` | Required |
| 2.07.12 | Staffing Requirements | `12-staffing-requirements.md` | Required |
| 2.07.13 | Shrinkage & Capacity Planning | `13-shrinkage-capacity-planning.md` | Required |
| 2.07.14 | Scheduling Strategy | `14-scheduling-strategy.md` | Required |
| 2.07.15 | Activities & Activity Codes | `15-activities-activity-codes.md` | Required |
| 2.07.16 | Shift Planning | `16-shift-planning.md` | Required |
| 2.07.17 | Schedule Generation | `17-schedule-generation.md` | Required |
| 2.07.18 | Schedule Optimisation | `18-schedule-optimisation.md` | Required |
| 2.07.19 | Schedule Publication | `19-schedule-publication.md` | Required |
| 2.07.20 | Time-Off Management | `20-time-off-management.md` | Required |
| 2.07.21 | Time-Off Plans & Requests | `21-time-off-plans-requests.md` | Required |
| 2.07.22 | Shift Trades | `22-shift-trades.md` | Conditional |
| 2.07.23 | Agent Self-Service | `23-agent-self-service.md` | Required |
| 2.07.24 | Intraday Management | `24-intraday-management.md` | Required |
| 2.07.25 | Real-Time Adherence | `25-real-time-adherence.md` | Required |
| 2.07.26 | Schedule Adherence | `26-schedule-adherence.md` | Required |
| 2.07.27 | Workforce Notifications | `27-workforce-notifications.md` | Required |
| 2.07.28 | Workforce Communications | `28-workforce-communications.md` | Conditional |
| 2.07.29 | Performance Management | `29-performance-management.md` | Conditional |
| 2.07.30 | Employee Engagement | `30-employee-engagement.md` | Conditional |
| 2.07.31 | Coaching & Development | `31-coaching-development.md` | Conditional |
| 2.07.32 | Recognition & Gamification | `32-recognition-gamification.md` | Conditional |
| 2.07.33 | Learning & Knowledge Integration | `33-learning-knowledge-integration.md` | Conditional |
| 2.07.34 | Employee Experience | `34-employee-experience.md` | Required |
| 2.07.35 | WFM Analytics & Reporting | `35-wfm-analytics-reporting.md` | Required |
| 2.07.36 | Capacity & Staffing Optimisation | `36-capacity-staffing-optimisation.md` | Required |
| 2.07.37 | HR / HCM Integration | `37-hr-hcm-integration.md` | Conditional |
| 2.07.38 | Payroll & Time Integration | `38-payroll-time-integration.md` | Conditional |
| 2.07.39 | Workforce Data Integration | `39-workforce-data-integration.md` | Required |
| 2.07.40 | WFM Security & Access | `40-wfm-security-access.md` | Required |
| 2.07.41 | WFM Testing & Validation | `41-wfm-testing-validation.md` | Required |
| 2.07.42 | WFM Migration & Cutover | `42-wfm-migration-cutover.md` | Conditional |
| 2.07.43 | WFM Operations & BAU | `43-wfm-operations-bau.md` | Required |
| 2.07.44 | WFM Governance & Lifecycle | `44-wfm-governance-lifecycle.md` | Required |
| 2.07.45 | WFM Continuous Optimisation | `45-wfm-continuous-optimisation.md` | Required |

---

# 6. Standard Layer 1 Mapping

| Phase | Workforce Management Application |
|---|---|
| P01 | Establish WFM scope, ownership and mobilisation |
| P02 | Discover workforce model, data and current state |
| P03 | Define WFM requirements and operational rules |
| P04 | Design WFM architecture and operating model |
| P05 | Configure WFM foundation |
| P06 | Configure forecasting, scheduling and workforce capabilities |
| P07 | Implement integrations and migration |
| P08 | Test and validate WFM |
| P09 | Prepare WFM operations and users |
| P10 | Prepare and execute production deployment |
| P11 | Perform hypercare and production validation |
| P12 | Complete BAU handover and closure |

---

# 7. Cross-Domain Dependencies

WFM depends upon:

- Core Platform
- Identity & Access
- ACD Routing
- Queues
- Skills
- Users
- Divisions
- Business Hours
- historical interaction data
- service-level targets
- employee availability
- HR data
- payroll data where applicable
- reporting
- integrations
- security

WFM provides dependencies for:

- staffing
- scheduling
- adherence
- intraday management
- operational reporting
- employee self-service
- capacity planning
- service-level optimisation

---

# 8. Estimation Considerations

Effort is influenced by:

- number of business units
- number of management units
- number of planning groups
- number of queues
- number of skills
- number of agents
- number of forecasts
- forecast complexity
- historical data quality
- forecast history
- service goals
- shrinkage assumptions
- schedule rules
- activity codes
- time-off rules
- shift-trade requirements
- integration complexity
- HR/HCM source systems
- payroll dependencies
- reporting requirements
- employee engagement scope
- migration volume
- testing cycles
- training requirements
- operational maturity
- automation requirements

---

# 9. Definition of Done

The WFM domain is complete when:

- WFM architecture is approved.
- WFM strategy is approved.
- licensing is validated.
- business units are defined.
- management units are defined.
- planning groups are defined.
- service goals are approved.
- forecast requirements are defined.
- historical data is validated.
- staffing requirements are defined.
- shrinkage assumptions are approved.
- scheduling requirements are defined.
- activities are configured.
- schedules are generated and validated.
- time-off processes are configured.
- applicable self-service capabilities are available.
- intraday processes are defined.
- adherence is configured.
- notifications are validated.
- reporting is validated.
- integrations are tested.
- security is approved.
- WFM UAT is complete.
- operational readiness is complete.
- production deployment is complete.
- BAU ownership is accepted.

---

# 10. Domain Gate

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
# Layer 2.09 — Analytics, Reporting & Data Visualisation

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 09 — Analytics, Reporting & Data Visualisation  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete analytics, reporting, measurement, data visualisation, KPI, dashboard, data extraction, data quality, governance and operational reporting capabilities required for an enterprise Genesys Cloud deployment.

---

# 1. Purpose

The Analytics, Reporting & Data Visualisation domain defines how the organisation will collect, model, validate, visualise, distribute and govern Genesys Cloud operational and analytical data.

This domain covers:

- Reporting strategy
- Analytics strategy
- KPI framework
- Business metrics
- Contact centre metrics
- Conversation analytics
- Interaction analytics
- Queue analytics
- Agent analytics
- Workforce analytics
- Service-level reporting
- Abandonment reporting
- Average speed of answer
- Average handle time
- Occupancy
- Adherence
- Service performance
- Digital analytics
- Voice analytics
- Callback analytics
- Flow analytics
- Architect reporting
- Wrap-up and disposition reporting
- Customer journey analytics
- Historical reporting
- Real-time reporting
- Near-real-time reporting
- Dashboards
- Supervisor dashboards
- Management dashboards
- Executive dashboards
- Operational dashboards
- Agent performance reporting
- Team performance reporting
- Queue performance reporting
- Campaign reporting
- Outbound reporting
- Quality reporting
- Recording-related reporting
- Evaluation reporting
- Survey reporting
- Workforce Management reporting
- Data extraction
- Analytics APIs
- Data Actions where applicable
- Data warehouse integration
- Data lake integration
- Business intelligence platforms
- Data modelling
- Data transformation
- Data reconciliation
- Data quality
- Report scheduling
- Report distribution
- Access control
- Data governance
- Retention
- Auditability
- Regulatory reporting
- Performance reporting
- Executive reporting
- Continuous improvement

---

# 2. Scope

```text
09 Analytics, Reporting & Data Visualisation
│
├── 01 Analytics & Reporting Strategy
├── 02 Reporting Requirements
├── 03 KPI & Metrics Framework
├── 04 Contact Centre Measurement Model
├── 05 Data Sources & Data Inventory
├── 06 Data Ownership & Governance
├── 07 Data Quality & Reconciliation
├── 08 Genesys Cloud Analytics
├── 09 Conversation Analytics
├── 10 Interaction Analytics
├── 11 Queue Analytics
├── 12 Agent Analytics
├── 13 Service Level Analytics
├── 14 Abandonment Analytics
├── 15 AHT & Handle Time Analytics
├── 16 ASA & Speed of Answer Analytics
├── 17 Occupancy & Utilisation Analytics
├── 18 Wrap-Up & Disposition Reporting
├── 19 Architect Flow Reporting
├── 20 Digital Analytics
├── 21 Callback Analytics
├── 22 Outbound & Campaign Analytics
├── 23 Workforce Management Reporting
├── 24 Quality Management Reporting
├── 25 Evaluation & Performance Reporting
├── 26 Survey & Customer Feedback Reporting
├── 27 Customer Journey Analytics
├── 28 Historical Reporting
├── 29 Real-Time & Near-Real-Time Reporting
├── 30 Operational Dashboards
├── 31 Supervisor Dashboards
├── 32 Management Dashboards
├── 33 Executive Dashboards
├── 34 Agent Performance Reporting
├── 35 Queue & Team Performance Reporting
├── 36 Report Scheduling & Distribution
├── 37 Analytics APIs
├── 38 Data Extraction & Export
├── 39 Data Warehouse & Data Lake
├── 40 BI Platform Integration
├── 41 Data Modelling & Transformation
├── 42 Reporting Security & Access
├── 43 Reporting Retention & Compliance
├── 44 Reporting Testing & Validation
├── 45 Reporting Operations & Continuous Improvement
└── 46 Analytics Capability Governance
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Analytics & Reporting Strategy | Required |
| Reporting Requirements | Required |
| KPI & Metrics Framework | Required |
| Contact Centre Measurement Model | Required |
| Data Sources & Data Inventory | Required |
| Data Ownership & Governance | Required |
| Data Quality & Reconciliation | Required |
| Genesys Cloud Analytics | Required |
| Conversation Analytics | Conditional |
| Interaction Analytics | Required |
| Queue Analytics | Required |
| Agent Analytics | Required |
| Service Level Analytics | Required |
| Abandonment Analytics | Required |
| AHT & Handle Time Analytics | Required |
| ASA & Speed of Answer Analytics | Required |
| Occupancy & Utilisation Analytics | Conditional |
| Wrap-Up & Disposition Reporting | Required |
| Architect Flow Reporting | Required |
| Digital Analytics | Conditional |
| Callback Analytics | Conditional |
| Outbound & Campaign Analytics | Conditional |
| Workforce Management Reporting | Conditional |
| Quality Management Reporting | Conditional |
| Evaluation & Performance Reporting | Conditional |
| Survey & Customer Feedback Reporting | Conditional |
| Customer Journey Analytics | Conditional |
| Historical Reporting | Required |
| Real-Time & Near-Real-Time Reporting | Required |
| Operational Dashboards | Required |
| Supervisor Dashboards | Required |
| Management Dashboards | Required |
| Executive Dashboards | Conditional |
| Agent Performance Reporting | Required |
| Queue & Team Performance Reporting | Required |
| Report Scheduling & Distribution | Required |
| Analytics APIs | Conditional |
| Data Extraction & Export | Required |
| Data Warehouse & Data Lake | Conditional |
| BI Platform Integration | Conditional |
| Data Modelling & Transformation | Conditional |
| Reporting Security & Access | Required |
| Reporting Retention & Compliance | Required |
| Reporting Testing & Validation | Required |
| Reporting Operations & Continuous Improvement | Required |
| Analytics Capability Governance | Required |

---

# 4. Analytics Architecture

```text
                         ┌────────────────────────────┐
                         │ Genesys Cloud               │
                         │                            │
                         │ Conversations              │
                         │ Analytics                  │
                         │ ACD                        │
                         │ Architect                   │
                         │ Digital                    │
                         │ WFM                        │
                         │ Quality                    │
                         │ Surveys                    │
                         └─────────────┬──────────────┘
                                       │
                                       ▼
                         ┌────────────────────────────┐
                         │ Analytics / Data Layer     │
                         │                            │
                         │ Genesys Analytics           │
                         │ APIs                        │
                         │ Data Extraction             │
                         │ ETL / ELT                   │
                         └─────────────┬──────────────┘
                                       │
                   ┌───────────────────┼───────────────────┐
                   │                   │                   │
                   ▼                   ▼                   ▼
             Operational          Enterprise          Historical
             Dashboards           BI Platform          Data Platform
                   │                   │                   │
                   ▼                   ▼                   ▼
              Supervisors         Management           Analytics
              Operations          Executives            Data Lake
              Agents              Business              Warehouse
```

---

# 5. Analytics Design Principles

1. Every report must have a defined business purpose.
2. Every KPI must have an agreed definition.
3. Metrics must have a documented calculation method.
4. Metrics must have an identified source.
5. Reporting definitions must be consistent across the organisation.
6. Genesys Cloud should be treated as the authoritative source for Genesys Cloud-native operational metrics unless another approved source is defined.
7. Reports must distinguish between real-time, near-real-time and historical information.
8. Report consumers must understand the latency of the data.
9. Reporting must use consistent time zones.
10. Reporting must define the reporting period.
11. Reporting must account for business hours where applicable.
12. Service-level calculations must use agreed business definitions.
13. Data transformations must be documented.
14. Data quality must be measurable.
15. Reconciliation must be performed for critical reporting.
16. Sensitive information must be restricted.
17. Report access must follow least privilege.
18. Executive reporting should use validated business KPIs.
19. Operational dashboards should focus on actionable metrics.
20. Agent reports should support coaching and performance improvement rather than merely surveillance.
21. Report duplication should be minimised.
22. Reports must have identifiable owners.
23. Scheduled reports must have defined recipients.
24. Reports must have a lifecycle.
25. Deprecated reports must be retired.
26. Analytics changes must follow governance.
27. Data exported outside Genesys Cloud must be protected appropriately.
28. Reporting requirements must be tested against actual business decisions.
29. Dashboard performance must be considered.
30. Reporting must be designed for continuous improvement.

---

# 6. Standard Reporting Hierarchy

```text
Executive
   │
   ├── Enterprise Performance
   ├── Customer Experience
   ├── Service Performance
   └── Financial / Strategic Outcomes
          │
          ▼
Management
   │
   ├── Contact Centre Performance
   ├── Queue Performance
   ├── Workforce Performance
   ├── Quality
   └── Customer Experience
          │
          ▼
Supervisor
   │
   ├── Real-Time Queue Status
   ├── Agent State
   ├── Service Level
   ├── Abandonment
   ├── AHT
   └── Exceptions
          │
          ▼
Agent
   │
   ├── Personal Performance
   ├── Interaction Outcomes
   ├── Schedule / Adherence
   ├── Quality
   └── Coaching Metrics
```

---

# 7. Standard KPI Framework

The project should establish a formal KPI catalogue.

| KPI | Definition | Source | Owner | Frequency |
|---|---|---|---|---|
| Service Level | Agreed percentage answered within target | Genesys Analytics | Operations | Real-time / Historical |
| ASA | Average speed to answer | Genesys Analytics | Operations | Historical |
| AHT | Average handle time | Genesys Analytics | Operations | Historical |
| Abandonment Rate | Percentage of interactions abandoned | Genesys Analytics | Operations | Real-time / Historical |
| Offered | Interactions offered | Genesys Analytics | Operations | Real-time / Historical |
| Answered | Interactions answered | Genesys Analytics | Operations | Real-time / Historical |
| Occupancy | Agent productive utilisation measure | Genesys / WFM | WFM | Historical |
| Adherence | Schedule adherence | WFM | WFM | Near-real-time / Historical |
| ACW | After-call work | Genesys Analytics | Operations | Historical |
| Transfer Rate | Interactions transferred | Genesys Analytics | Operations | Historical |
| First Contact Resolution | Agreed FCR definition | Genesys + external data | CX | Historical |
| Customer Satisfaction | Survey-derived measure | Survey platform | CX | Historical |
| NPS | Net Promoter Score where applicable | Survey platform | CX | Historical |
| Quality Score | Evaluation-derived score | Quality | Quality | Historical |

---

# 8. Layer 1 Mapping

| Layer 1 Phase | Analytics Activities |
|---|---|
| Phase 1 — Initiation | Establish reporting scope |
| Phase 2 — Discovery | Discover existing reports and metrics |
| Phase 3 — Requirements | Define KPIs and reporting requirements |
| Phase 4 — Architecture | Define analytics architecture |
| Phase 5 — Platform Foundation | Establish analytics access and data foundations |
| Phase 6 — Solution Build | Configure reports and dashboards |
| Phase 7 — Integration & Migration | Integrate external reporting data |
| Phase 8 — Testing | Validate metrics and reports |
| Phase 9 — Operational Readiness | Train reporting users |
| Phase 10 — Production Deployment | Deploy reporting |
| Phase 11 — Hypercare | Validate production reporting |
| Phase 12 — BAU Handover | Transfer reporting ownership |

---

# 9. Standard Analytics Artefacts

A project may require:

- Analytics strategy
- Reporting requirements
- KPI catalogue
- Metric dictionary
- Contact centre measurement model
- Data source catalogue
- Data ownership matrix
- Data lineage
- Data quality model
- Report inventory
- Dashboard inventory
- Report catalogue
- Dashboard wireframes
- Executive dashboard design
- Management dashboard design
- Supervisor dashboard design
- Agent reporting design
- Real-time reporting design
- Historical reporting design
- Digital reporting design
- WFM reporting design
- Quality reporting design
- Survey reporting design
- Analytics API specification
- Data extraction design
- Data warehouse design
- BI integration design
- Data model
- Data transformation specification
- Security model
- Report access matrix
- Retention policy
- Compliance reporting model
- Reporting test plan
- Reconciliation model
- Reporting runbook
- Reporting support model
- Reporting governance model

---

# 10. Standard Spreadsheet Task Model

| Field | Requirement |
|---|---|
| Task ID | Unique identifier |
| Layer | Layer 2 |
| Domain | 09 |
| Capability | Analytics capability |
| Phase | Layer 1 phase |
| Workstream | Analytics / Reporting |
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

# 11. Major Dependencies

Analytics, Reporting & Data Visualisation depends on:

- Core Platform
- Identity & Access
- ACD Routing
- Architect
- Digital
- Workforce Management
- Quality
- Data & Integrations
- Security
- External data platforms
- CRM
- Enterprise systems
- Survey platforms

Analytics, Reporting & Data Visualisation provides dependencies for:

- Operations
- Supervisors
- Workforce Management
- Quality
- Customer Experience
- Executive Management
- Business Intelligence
- Continuous Improvement
- Governance

---

# 12. Reporting Risks

| Risk | Impact | Mitigation |
|---|---|---|
| KPI definitions differ between teams | High | Establish central metric dictionary |
| Incorrect data source | High | Define source-of-truth model |
| Poor data quality | High | Implement reconciliation |
| Reports duplicated | Medium | Establish report catalogue |
| Real-time data misunderstood | Medium | Document data latency |
| Incorrect service-level calculation | High | Business approval |
| Incorrect time zone | Medium | Standardise reporting time zone |
| Sensitive data exposed | Critical | Apply RBAC and data classification |
| Dashboard overload | Medium | Prioritise actionable KPIs |
| Report performance poor | Medium | Optimise queries and scope |
| Historical data unavailable | High | Define retention and extraction |
| External data mismatch | High | Reconcile source systems |
| Unsupported KPI | Medium | Validate source availability |
| Report ownership unclear | High | Assign business owners |
| Scheduled reports sent incorrectly | Medium | Validate recipients |
| API limits exceeded | Medium | Control extraction |
| Data pipeline failure | High | Monitoring and alerting |
| Reporting changes break KPIs | High | Regression testing |
| Executive reports use unvalidated data | Critical | Formal approval |
| Legacy reports not rationalised | Medium | Report inventory and retirement |

---

# 13. Definition of Done

The Analytics, Reporting & Data Visualisation domain is complete when:

- Reporting strategy is approved.
- Reporting requirements are documented.
- KPI definitions are approved.
- Metric ownership is established.
- Data sources are identified.
- Data ownership is established.
- Data quality controls are defined.
- Required Genesys Cloud analytics are configured.
- Required real-time reporting is configured.
- Required historical reporting is configured.
- Required dashboards are configured.
- Supervisor reporting is configured.
- Management reporting is configured.
- Executive reporting is configured where required.
- Agent reporting is configured.
- Queue reporting is configured.
- Digital reporting is configured where required.
- WFM reporting is configured where required.
- Quality reporting is configured where required.
- Survey reporting is configured where required.
- Analytics APIs are configured where required.
- Data exports are validated.
- Data warehouse integration is validated where required.
- BI integration is validated where required.
- Reporting security is validated.
- Retention requirements are implemented.
- Reports are tested.
- KPI calculations are reconciled.
- UAT is completed.
- Reporting users are trained.
- Operational ownership is established.
- Reporting governance is established.

---

# 14. Domain Gate

```text
REPORTING REQUIREMENTS APPROVED
            +
KPI CATALOGUE APPROVED
            +
METRIC DEFINITIONS APPROVED
            +
DATA SOURCES APPROVED
            +
REPORTING ARCHITECTURE APPROVED
            +
REPORTS / DASHBOARDS BUILT
            +
SECURITY VALIDATED
            +
DATA QUALITY VALIDATED
            +
KPI RECONCILIATION COMPLETED
            +
UAT ACCEPTED
            +
USERS TRAINED
            +
OPERATIONS READY
            ↓
REPORTING READY FOR PRODUCTION
```

---

# 15. Domain File Catalogue

```text
09-Analytics-Reporting-Data-Visualisation/
│
├── README.md
├── 01-Analytics-Reporting-Strategy.md
├── 02-Reporting-Requirements.md
├── 03-KPI-Metrics-Framework.md
├── 04-Contact-Centre-Measurement-Model.md
├── 05-Data-Sources-Data-Inventory.md
├── 06-Data-Ownership-Governance.md
├── 07-Data-Quality-Reconciliation.md
├── 08-Genesys-Cloud-Analytics.md
├── 09-Conversation-Analytics.md
├── 10-Interaction-Analytics.md
├── 11-Queue-Analytics.md
├── 12-Agent-Analytics.md
├── 13-Service-Level-Analytics.md
├── 14-Abandonment-Analytics.md
├── 15-AHT-Handle-Time-Analytics.md
├── 16-ASA-Speed-of-Answer-Analytics.md
├── 17-Occupancy-Utilisation-Analytics.md
├── 18-Wrap-Up-Disposition-Reporting.md
├── 19-Architect-Flow-Reporting.md
├── 20-Digital-Analytics.md
├── 21-Callback-Analytics.md
├── 22-Outbound-Campaign-Analytics.md
├── 23-Workforce-Management-Reporting.md
├── 24-Quality-Management-Reporting.md
├── 25-Evaluation-Performance-Reporting.md
├── 26-Survey-Customer-Feedback-Reporting.md
├── 27-Customer-Journey-Analytics.md
├── 28-Historical-Reporting.md
├── 29-Real-Time-Near-Real-Time-Reporting.md
├── 30-Operational-Dashboards.md
├── 31-Supervisor-Dashboards.md
├── 32-Management-Dashboards.md
├── 33-Executive-Dashboards.md
├── 34-Agent-Performance-Reporting.md
├── 35-Queue-Team-Performance-Reporting.md
├── 36-Report-Scheduling-Distribution.md
├── 37-Analytics-APIs.md
├── 38-Data-Extraction-Export.md
├── 39-Data-Warehouse-Data-Lake.md
├── 40-BI-Platform-Integration.md
├── 41-Data-Modelling-Transformation.md
├── 42-Reporting-Security-Access.md
├── 43-Reporting-Retention-Compliance.md
├── 44-Reporting-Testing-Validation.md
├── 45-Reporting-Operations-Continuous-Improvement.md
└── 46-Analytics-Capability-Governance.md
```

---

# 16. Capability Catalogue

The following sections define the implementation requirements for each capability.

---

# 17. Implementation Task Decomposition Preview

The final implementation task catalogue will decompose the capability catalogue into atomic project tasks.

Example:

```text
AN-009-001  Define analytics strategy
AN-009-002  Identify reporting stakeholders
AN-009-003  Inventory existing reports
AN-009-004  Inventory existing dashboards
AN-009-005  Identify reporting gaps
AN-009-006  Define reporting governance
AN-009-007  Define KPI framework
AN-009-008  Define KPI ownership
AN-009-009  Define service-level metric
AN-009-010  Define ASA metric
AN-009-011  Define AHT metric
AN-009-012  Define abandonment metric
AN-009-013  Define occupancy metric
AN-009-014  Define adherence metric
AN-009-015  Define customer experience metrics
AN-009-016  Define quality metrics
AN-009-017  Create metric dictionary
AN-009-018  Obtain KPI approval
AN-009-019  Inventory analytics data sources
AN-009-020  Define data owners
AN-009-021  Define data quality standards
AN-009-022  Define reconciliation methodology
AN-009-023  Identify required Genesys Cloud analytics
AN-009-024  Configure analytics views
AN-009-025  Validate interaction analytics
AN-009-026  Validate queue analytics
AN-009-027  Validate agent analytics
AN-009-028  Configure service-level reporting
AN-009-029  Validate service-level calculations
AN-009-030  Configure abandonment reporting
AN-009-031  Validate abandonment calculations
AN-009-032  Configure AHT reporting
AN-009-033  Validate AHT calculations
AN-009-034  Configure ASA reporting
AN-009-035  Validate ASA calculations
AN-009-036  Configure wrap-up reporting
AN-009-037  Validate wrap-up reporting
AN-009-038  Configure Architect flow reporting
AN-009-039  Validate Architect flow reporting
AN-009-040  Identify digital reporting requirements
AN-009-041  Configure digital reporting
AN-009-042  Validate digital reporting
AN-009-043  Identify callback reporting requirements
AN-009-044  Configure callback reporting
AN-009-045  Validate callback reporting
AN-009-046  Identify outbound reporting requirements
AN-009-047  Configure campaign reporting
AN-009-048  Validate outbound reporting
AN-009-049  Define WFM reporting requirements
AN-009-050  Configure WFM reporting
AN-009-051  Validate WFM reporting
AN-009-052  Define quality reporting requirements
AN-009-053  Configure quality reporting
AN-009-054  Validate quality reporting
AN-009-055  Define evaluation reporting
AN-009-056  Configure evaluation reporting
AN-009-057  Define survey reporting
AN-009-058  Integrate survey data
AN-009-059  Validate customer feedback reporting
AN-009-060  Define customer journey reporting
AN-009-061  Map customer journey data
AN-009-062  Configure historical reporting
AN-009-063  Define historical retention
AN-009-064  Configure real-time reporting
AN-009-065  Validate dashboard refresh
AN-009-066  Build operational dashboard
AN-009-067  Build supervisor dashboard
AN-009-068  Build management dashboard
AN-009-069  Build executive dashboard where required
AN-009-070  Build agent performance reporting
AN-009-071  Build queue performance reporting
AN-009-072  Configure scheduled reports
AN-009-073  Validate scheduled report delivery
AN-009-074  Identify analytics API requirements
AN-009-075  Configure analytics API access
AN-009-076  Develop analytics extraction
AN-009-077  Validate extracted data
AN-009-078  Define data warehouse requirements
AN-009-079  Build analytics data pipeline
AN-009-080  Validate warehouse data
AN-009-081  Define BI integration
AN-009-082  Build BI semantic model
AN-009-083  Build BI dashboards
AN-009-084  Validate BI data
AN-009-085  Define analytics data model
AN-009-086  Define reporting transformations
AN-009-087  Configure reporting security
AN-009-088  Test role-based reporting access
AN-009-089  Define reporting retention
AN-009-090  Validate compliance requirements
AN-009-091  Create reporting test plan
AN-009-092  Execute metric validation
AN-009-093  Execute report validation
AN-009-094  Execute dashboard validation
AN-009-095  Execute data reconciliation
AN-009-096  Execute reporting security testing
AN-009-097  Execute reporting performance testing
AN-009-098  Execute reporting UAT
AN-009-099  Resolve reporting defects
AN-009-100  Prepare production reporting deployment
AN-009-101  Deploy reporting
AN-009-102  Execute production smoke testing
AN-009-103  Monitor reporting during hypercare
AN-009-104  Complete reporting operational handover
AN-009-105  Establish KPI governance
AN-009-106  Establish report lifecycle governance
AN-009-107  Establish analytics continuous improvement process
```

The eventual implementation workbook should decompose these further wherever an activity requires separate:

- Requirements
- Design
- Configuration
- Development
- Data preparation
- Security approval
- Testing
- Reconciliation
- Business approval
- Deployment
- Validation
- Documentation
- Training

---

# 18. Cross-Domain Dependencies

| Dependency Domain | Analytics Dependency |
|---|---|
| 01 — Core Platform | Divisions, platform configuration |
| 02 — Identity & Access | Report access and permissions |
| 03 — Voice & Telephony | Voice interaction data |
| 04 — ACD Routing | Queue, skill and routing metrics |
| 05 — Architect | Flow outcomes and interaction data |
| 06 — Digital | Digital interaction analytics |
| 07 — Workforce Management | WFM, schedule and adherence data |
| 08 — Data & Integrations | APIs, data pipelines, warehouse integration |
| 09 — Analytics & Reporting | Current domain |
| 10 — Quality | Evaluation and quality data |
| 11 — Security | Data security and access |
| 12 — Testing | Reporting validation |
| 13 — Migration | Historical data |
| 14 — Operations | Reporting support |
| 15 — Optimisation | Performance and analytics improvement |

---

# 19. Critical Cross-Domain Relationships

## ACD Routing → Analytics

Analytics depends on correctly configured:

- Queues
- Skills
- Routing
- Wrap-up codes
- Presence
- Divisions

Incorrect ACD configuration will directly affect reporting.

---

## Architect → Analytics

Architect flows create the operational context needed to measure:

- Self-service
- Transfers
- Disconnects
- Errors
- Data collection
- Flow outcomes

---

## Workforce Management → Analytics

WFM reporting may depend on:

- Agent schedules
- Forecasts
- Adherence
- Occupancy
- Staffing
- Time-off

---

## Quality → Analytics

Quality reporting may depend on:

- Evaluations
- Scorecards
- Quality scores
- Coaching
- Recording associations

---

## Data & Integrations → Analytics

Enterprise reporting may require:

- Analytics APIs
- Data extraction
- Data Actions
- Event processing
- Data warehouse
- Data lake
- BI platform
- CRM data
- ERP data
- Survey data

---

# 20. Reporting Project Sequence

```text
01. Reporting Discovery
        ↓
02. Existing Report Inventory
        ↓
03. Reporting Requirements
        ↓
04. KPI Definition
        ↓
05. Metric Dictionary
        ↓
06. Data Source Inventory
        ↓
07. Data Ownership
        ↓
08. Analytics Architecture
        ↓
09. Report / Dashboard Design
        ↓
10. Data / API Configuration
        ↓
11. Report Configuration
        ↓
12. Dashboard Configuration
        ↓
13. External BI Integration
        ↓
14. Security Configuration
        ↓
15. Data Reconciliation
        ↓
16. Reporting SIT
        ↓
17. Performance Testing
        ↓
18. Security Testing
        ↓
19. UAT
        ↓
20. Production Deployment
        ↓
21. Smoke Testing
        ↓
22. Hypercare
        ↓
23. BAU Handover
        ↓
24. Continuous Improvement
```

---

# 21. Reporting Phase Dependencies

| Activity | Primary Dependency |
|---|---|
| Reporting Inventory | Discovery |
| KPI Definition | Business requirements |
| Metric Dictionary | KPI definition |
| Data Source Inventory | Integration discovery |
| Data Model | Data sources |
| Report Design | Requirements |
| Dashboard Design | KPI framework |
| Report Configuration | Design |
| API Extraction | Integration architecture |
| BI Integration | Data architecture |
| Security | Identity and access |
| Reconciliation | Data availability |
| SIT | Configuration/build |
| UAT | SIT |
| Production | UAT approval |
| Hypercare | Production deployment |
| BAU | Operational readiness |

---

# 22. Reporting Security Model

```text
                 Security Governance
                         │
             ┌───────────┼───────────┐
             │           │           │
             ▼           ▼           ▼
           Users       Data        Reports
             │           │           │
             ▼           ▼           ▼
           Roles      Classification Access
             │           │           │
             └───────────┼───────────┘
                         ▼
                 Reporting Platform
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
       Agent         Supervisor      Executive
       Reports        Reports         Reports
```

Reporting access should be aligned with:

- Business role
- Division
- Queue
- Team
- Data classification
- Reporting responsibility
- Regulatory requirements

---

# 23. Data Quality Model

Every critical KPI should be assessed against:

```text
Completeness
     +
Accuracy
     +
Consistency
     +
Timeliness
     +
Validity
     +
Uniqueness
     ↓
Trusted Analytics
```

## Quality Checks

- Record counts
- Null values
- Duplicate records
- Missing interactions
- Incorrect timestamps
- Invalid queue mappings
- Invalid agent mappings
- Incorrect wrap-up mappings
- Missing customer identifiers
- Source-to-target reconciliation

---

# 24. KPI Governance Model

```text
Business Requirement
        │
        ▼
KPI Definition
        │
        ▼
Source Validation
        │
        ▼
Formula Approval
        │
        ▼
Report Implementation
        │
        ▼
Testing
        │
        ▼
Business Approval
        │
        ▼
Production KPI
        │
        ▼
Governance Review
```

No KPI should become an executive or contractual metric without an approved definition and source.

---

# 25. Reporting Environment Model

The standard implementation model should consider:

```text
Development / Configuration
          │
          ▼
System Integration Testing
          │
          ▼
User Acceptance Testing
          │
          ▼
Production
```

Each environment should be assessed for:

- Data availability
- Data masking
- User access
- API clients
- External data
- Dashboard configuration
- Report schedules
- Security
- Test data

Production report schedules and distribution lists should be validated separately from lower environments.

---

# 26. Reporting Documentation Standards

Every production report should have:

1. Report name
2. Business purpose
3. Owner
4. Audience
5. KPI definitions
6. Data source
7. Filters
8. Time zone
9. Reporting period
10. Refresh frequency
11. Data latency
12. Security requirements
13. Distribution method
14. Schedule
15. Dependencies
16. Data quality controls
17. Support owner
18. Change process
19. Retirement criteria

Every production dashboard should additionally document:

- Dashboard purpose
- Audience
- KPI hierarchy
- Visualisation rules
- Refresh behaviour
- Drill-down behaviour
- Alert thresholds
- Performance requirements

---

# 27. Analytics Data Lifecycle

```text
Interaction
    │
    ▼
Genesys Cloud
    │
    ▼
Analytics Data
    │
    ├──────────────► Real-Time Reporting
    │
    ├──────────────► Historical Reporting
    │
    ├──────────────► Analytics API
    │
    └──────────────► Data Platform
                            │
                            ▼
                       BI / Analytics
                            │
                            ▼
                    Business Decisions
```

---

# 28. Reporting Lifecycle

```text
Requirement
    │
    ▼
Design
    │
    ▼
Build
    │
    ▼
Test
    │
    ▼
Approve
    │
    ▼
Publish
    │
    ▼
Operate
    │
    ▼
Review
    │
    ├── Improve
    │
    └── Retire
```

---

# 29. Dashboard Design Standards

Dashboards should:

- Prioritise actionable information.
- Use consistent KPI definitions.
- Avoid unnecessary visualisation.
- Display reporting period.
- Display data refresh time.
- Display data latency where relevant.
- Use clear units.
- Distinguish actual versus target.
- Highlight exceptions.
- Support appropriate drill-down.
- Respect role-based access.
- Avoid exposing sensitive information.

---

# 30. Executive Reporting Standards

Executive reporting should prioritise:

- Customer experience
- Service performance
- Operational performance
- Workforce capacity
- Quality
- Trend
- Risk
- Business outcomes

Executive dashboards should avoid excessive operational detail unless specifically required.

---

# 31. Operational Reporting Standards

Operational dashboards should prioritise:

- Current queue status
- Current service level
- Waiting interactions
- Abandonment
- Agent availability
- Exceptions
- Staffing
- Current workload

Operational reporting should support immediate decisions.

---

# 32. Historical Reporting Standards

Historical reporting should support:

- Trend analysis
- Period comparison
- Seasonality
- Workforce planning
- Performance analysis
- Continuous improvement
- Forecasting
- Management review

Historical reports must clearly identify:

- Reporting period
- Data source
- Time zone
- Metric definition
- Data latency

---

# 33. Reporting Acceptance Model

A report is accepted only when:

```text
Business Requirement
        +
KPI Definition
        +
Data Source
        +
Calculation
        +
Filters
        +
Security
        +
Performance
        +
Reconciliation
        +
UAT
        ↓
Accepted Report
```

---

# 34. Domain Completion Gate

The Analytics, Reporting & Data Visualisation domain is considered **capability-complete** when:

- Reporting strategy is approved.
- Reporting requirements are complete.
- KPI catalogue is complete.
- Metric definitions are approved.
- Data sources are inventoried.
- Data ownership is established.
- Data quality requirements are defined.
- Genesys Cloud analytics requirements are mapped.
- Interaction reporting requirements are defined.
- Queue reporting requirements are defined.
- Agent reporting requirements are defined.
- Service-level reporting is defined.
- Abandonment reporting is defined.
- AHT reporting is defined.
- ASA reporting is defined.
- Wrap-up reporting is defined.
- Architect flow reporting is defined.
- Digital reporting is defined where applicable.
- Callback reporting is defined where applicable.
- Outbound reporting is defined where applicable.
- WFM reporting is defined where applicable.
- Quality reporting is defined where applicable.
- Survey reporting is defined where applicable.
- Customer journey reporting is defined where applicable.
- Historical reporting is defined.
- Real-time reporting is defined.
- Dashboards are designed.
- Dashboard ownership is established.
- Analytics APIs are defined where required.
- Data extraction is defined.
- Data warehouse integration is defined where required.
- BI integration is defined where required.
- Data modelling is defined where required.
- Reporting security is defined.
- Retention is defined.
- Testing is defined.
- Reconciliation is defined.
- UAT is defined.
- Operational ownership is defined.
- Governance is defined.

```text
REPORTING STRATEGY
        │
        ▼
KPI FRAMEWORK
        │
        ▼
DATA SOURCES
        │
        ▼
DATA MODEL
        │
        ▼
REPORT / DASHBOARD DESIGN
        │
        ▼
BUILD
        │
        ▼
SECURITY
        │
        ▼
RECONCILIATION
        │
        ▼
TESTING
        │
        ▼
UAT
        │
        ▼
DEPLOYMENT
        │
        ▼
OPERATIONS
        │
        ▼
OPTIMISATION
```

---

# 35. Domain Completion

**Layer:** 2  
**Domain:** 09 — Analytics, Reporting & Data Visualisation  
**Capability Documents:** 46  
**Status:** Capability catalogue complete  
**Next Activity:** Continue with Layer 2 Domain 10.

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


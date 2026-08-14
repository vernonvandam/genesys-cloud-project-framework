# Layer 2.10 — Quality Management, Recording & Evaluation

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 10 — Quality Management, Recording & Evaluation  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the complete quality management, interaction recording, evaluation, coaching, compliance, quality analytics and performance-assurance capabilities required for an enterprise Genesys Cloud deployment.

---

# 1. Purpose

The Quality Management, Recording & Evaluation domain defines how the organisation will capture, retain, protect, analyse, evaluate and improve customer interactions and agent performance.

This domain covers:

- Quality management strategy
- Quality programme governance
- Interaction recording
- Voice recording
- Digital interaction recording
- Screen recording where applicable
- Recording policies
- Recording triggers
- Recording exclusions
- Recording retention
- Recording access
- Recording security
- Recording encryption
- Recording compliance
- Recording export
- Recording search
- Interaction search
- Quality evaluation
- Evaluation forms
- Evaluation questions
- Evaluation scoring
- Critical questions
- Critical failures
- Quality thresholds
- Evaluation assignment
- Evaluation workflows
- Evaluation calibration
- Evaluator management
- Quality dashboards
- Quality reporting
- Agent scorecards
- Supervisor scorecards
- Coaching
- Coaching workflows
- Performance improvement
- Feedback
- Dispute / appeal processes
- Quality monitoring
- Interaction monitoring
- Screen monitoring where applicable
- Conversation analysis
- Speech and text analytics where licensed
- Topics
- Sentiment
- Emotion / behavioural indicators where available
- Compliance monitoring
- Sensitive-data handling
- PCI / payment-data controls
- Recording pause / resume
- Secure recording
- Data masking
- Recording deletion
- Retention schedules
- Legal hold
- Auditability
- Access reviews
- Quality assurance
- Quality testing
- Production validation
- Quality operations
- Continuous improvement

---

# 2. Scope

```text
10 Quality Management, Recording & Evaluation
│
├── 01 Quality Management Strategy
├── 02 Quality Programme Governance
├── 03 Quality Requirements
├── 04 Interaction Recording Strategy
├── 05 Voice Recording
├── 06 Digital Interaction Recording
├── 07 Screen Recording
├── 08 Recording Policies
├── 09 Recording Triggers & Conditions
├── 10 Recording Exclusions
├── 11 Recording Retention
├── 12 Recording Security
├── 13 Recording Access Control
├── 14 Recording Encryption & Protection
├── 15 Recording Compliance
├── 16 PCI & Sensitive Data Controls
├── 17 Recording Pause / Resume
├── 18 Recording Search & Retrieval
├── 19 Recording Export
├── 20 Recording Deletion & Legal Hold
├── 21 Interaction Search
├── 22 Quality Evaluation Framework
├── 23 Evaluation Forms
├── 24 Evaluation Questions
├── 25 Evaluation Scoring
├── 26 Critical Questions & Critical Failures
├── 27 Evaluation Assignment
├── 28 Evaluation Workflow
├── 29 Evaluator Management
├── 30 Evaluation Calibration
├── 31 Quality Monitoring
├── 32 Interaction Monitoring
├── 33 Screen Monitoring
├── 34 Speech & Text Analytics
├── 35 Topics & Categories
├── 36 Sentiment & Conversation Insights
├── 37 Compliance Monitoring
├── 38 Quality Dashboards
├── 39 Quality Reporting
├── 40 Agent Scorecards
├── 41 Supervisor Quality Management
├── 42 Coaching
├── 43 Agent Feedback
├── 44 Dispute & Appeal
├── 45 Quality Testing & Validation
├── 46 Quality Operations & Continuous Improvement
└── 47 Quality Governance & Audit
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Quality Management Strategy | Required |
| Quality Programme Governance | Required |
| Quality Requirements | Required |
| Interaction Recording Strategy | Required |
| Voice Recording | Required |
| Digital Interaction Recording | Conditional |
| Screen Recording | Conditional |
| Recording Policies | Required |
| Recording Triggers & Conditions | Required |
| Recording Exclusions | Required |
| Recording Retention | Required |
| Recording Security | Required |
| Recording Access Control | Required |
| Recording Encryption & Protection | Required |
| Recording Compliance | Required |
| PCI & Sensitive Data Controls | Conditional |
| Recording Pause / Resume | Conditional |
| Recording Search & Retrieval | Required |
| Recording Export | Conditional |
| Recording Deletion & Legal Hold | Conditional |
| Interaction Search | Required |
| Quality Evaluation Framework | Required |
| Evaluation Forms | Required |
| Evaluation Questions | Required |
| Evaluation Scoring | Required |
| Critical Questions & Critical Failures | Conditional |
| Evaluation Assignment | Required |
| Evaluation Workflow | Required |
| Evaluator Management | Required |
| Evaluation Calibration | Required |
| Quality Monitoring | Required |
| Interaction Monitoring | Conditional |
| Screen Monitoring | Conditional |
| Speech & Text Analytics | Conditional |
| Topics & Categories | Conditional |
| Sentiment & Conversation Insights | Conditional |
| Compliance Monitoring | Conditional |
| Quality Dashboards | Required |
| Quality Reporting | Required |
| Agent Scorecards | Required |
| Supervisor Quality Management | Required |
| Coaching | Required |
| Agent Feedback | Required |
| Dispute & Appeal | Conditional |
| Quality Testing & Validation | Required |
| Quality Operations & Continuous Improvement | Required |
| Quality Governance & Audit | Required |

---

# 4. Quality Architecture

```text
                         ┌────────────────────────────┐
                         │ Customer Interaction       │
                         │                            │
                         │ Voice                      │
                         │ Digital                    │
                         │ Messaging                  │
                         │ Email                      │
                         │ Screen                     │
                         └─────────────┬──────────────┘
                                       │
                                       ▼
                         ┌────────────────────────────┐
                         │ Recording / Interaction    │
                         │ Capture                    │
                         │                            │
                         │ Recording Policies         │
                         │ Recording Conditions       │
                         │ Secure Recording           │
                         │ Pause / Resume             │
                         └─────────────┬──────────────┘
                                       │
                                       ▼
                         ┌────────────────────────────┐
                         │ Quality Management          │
                         │                            │
                         │ Interaction Search          │
                         │ Evaluations                 │
                         │ Scorecards                  │
                         │ Quality Monitoring           │
                         │ Analytics                   │
                         └─────────────┬──────────────┘
                                       │
                  ┌────────────────────┼────────────────────┐
                  │                    │                    │
                  ▼                    ▼                    ▼
             Evaluation             Coaching            Analytics
                  │                    │                    │
                  ▼                    ▼                    ▼
             Agent Feedback      Improvement Plans     Quality Trends
                  │                    │                    │
                  └────────────────────┼────────────────────┘
                                       ▼
                             Continuous Improvement
```

---

# 5. Quality Design Principles

1. Quality management must support customer experience and business outcomes.
2. Recording must have a defined business and compliance purpose.
3. Recording must be designed according to applicable privacy and regulatory requirements.
4. Access to recordings must follow least privilege.
5. Sensitive information must be protected.
6. Recording retention must be explicitly defined.
7. Quality forms must measure meaningful behaviours and outcomes.
8. Evaluation criteria must be objective and understandable.
9. Evaluation scoring must be consistent.
10. Critical failures must be explicitly defined where applicable.
11. Quality evaluators must be trained.
12. Calibration must be performed regularly.
13. Agents must understand how quality is measured.
14. Coaching should be linked to measurable quality outcomes.
15. Quality data should be used for continuous improvement.
16. Recording and evaluation data must be traceable.
17. Quality metrics must be consistent with the KPI framework.
18. Quality reporting must be role-based.
19. Production recording must be validated before go-live.
20. Recording failures must be monitored.
21. Quality processes must have defined ownership.
22. Quality configuration changes must be governed.
23. Retention and deletion must be tested.
24. Quality processes must support audit requirements.
25. Quality operations must be reviewed continuously.

---

# 6. Quality Management Lifecycle

```text
Quality Strategy
      │
      ▼
Quality Requirements
      │
      ▼
Recording Strategy
      │
      ▼
Evaluation Framework
      │
      ▼
Quality Configuration
      │
      ▼
Interaction Capture
      │
      ▼
Evaluation
      │
      ▼
Scoring
      │
      ▼
Feedback
      │
      ▼
Coaching
      │
      ▼
Improvement
      │
      ▼
Quality Analytics
      │
      ▼
Continuous Improvement
```

---

# 7. Standard Quality Artefacts

A project may require:

- Quality management strategy
- Quality programme charter
- Quality requirements catalogue
- Recording strategy
- Recording policy catalogue
- Recording retention matrix
- Recording access matrix
- Recording compliance matrix
- Sensitive-data handling design
- PCI handling design
- Recording test plan
- Evaluation framework
- Evaluation form catalogue
- Evaluation question catalogue
- Evaluation scoring model
- Critical failure model
- Evaluation assignment model
- Evaluation workflow
- Evaluator model
- Calibration process
- Quality monitoring model
- Interaction search model
- Quality dashboard design
- Quality reporting catalogue
- Agent scorecard
- Supervisor scorecard
- Coaching framework
- Feedback model
- Dispute / appeal process
- Quality operating model
- Quality governance model
- Quality audit model
- Quality test plan
- Quality support runbook

---

# 8. Standard Quality Metrics

| Metric | Purpose |
|---|---|
| Evaluation Score | Overall interaction quality |
| Critical Failure Rate | Identify critical quality failures |
| Evaluations Completed | Measure QA throughput |
| Evaluation Coverage | Measure percentage of interactions evaluated |
| Quality Trend | Identify performance changes |
| Agent Quality Score | Individual performance |
| Team Quality Score | Team performance |
| Evaluator Agreement | Calibration effectiveness |
| Coaching Completion | Coaching process effectiveness |
| Coaching Outcomes | Improvement effectiveness |
| Recording Availability | Recording reliability |
| Recording Failure Rate | Recording health |
| Compliance Failure Rate | Compliance performance |
| Customer Sentiment | Customer experience |
| Topic Frequency | Identify recurring interaction themes |

---

# 9. Layer 1 Mapping

| Layer 1 Phase | Quality Activities |
|---|---|
| Phase 1 — Initiation | Define quality scope |
| Phase 2 — Discovery | Discover existing QA and recording |
| Phase 3 — Requirements | Define recording and evaluation requirements |
| Phase 4 — Architecture | Define quality architecture |
| Phase 5 — Platform Foundation | Establish recording and QA foundations |
| Phase 6 — Solution Build | Configure recording and evaluation |
| Phase 7 — Integration & Migration | Integrate external quality data where required |
| Phase 8 — Testing | Validate recording and QA |
| Phase 9 — Operational Readiness | Train QA, supervisors and agents |
| Phase 10 — Production Deployment | Enable production quality capabilities |
| Phase 11 — Hypercare | Validate recording and evaluation |
| Phase 12 — BAU Handover | Transfer quality operations |

---

# 10. Standard Implementation Task Model

| Field | Requirement |
|---|---|
| Task ID | Unique identifier |
| Layer | Layer 2 |
| Domain | 10 |
| Capability | Quality capability |
| Phase | Layer 1 phase |
| Workstream | Quality / Recording |
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

Quality Management, Recording & Evaluation depends on:

- Core Platform
- Identity & Access
- Voice & Telephony
- ACD Routing
- Architect
- Digital
- Data & Integrations
- Analytics & Reporting
- Security
- Compliance
- Workforce Management
- Operations

The domain provides dependencies for:

- Agent coaching
- Operations
- Analytics
- Reporting
- Compliance
- Workforce Management
- Customer Experience
- Continuous Improvement

---

# 12. Quality Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Recording policy incorrect | Critical | Formal design and testing |
| Recordings inaccessible | High | Access testing |
| Unauthorised recording access | Critical | RBAC and audit |
| Sensitive information recorded | Critical | Data protection controls |
| PCI information captured | Critical | Pause/resume or approved controls |
| Retention incorrect | High | Approved retention matrix |
| Recordings unavailable | Critical | Production validation and monitoring |
| Evaluation forms poorly designed | High | Business and QA workshops |
| Evaluation scoring inconsistent | High | Calibration |
| Critical failures poorly defined | High | Business approval |
| Agents do not understand QA | Medium | Training |
| Evaluators score inconsistently | High | Calibration |
| Excessive evaluation workload | Medium | Sampling strategy |
| Quality data not trusted | High | Reconciliation and governance |
| Coaching not linked to results | Medium | Coaching framework |
| Quality reports expose sensitive data | Critical | Access controls |
| Recording exports uncontrolled | Critical | Export governance |
| Quality configuration changes unmanaged | Medium | Change control |
| Legacy recordings not migrated | Conditional | Migration assessment |
| External QA integration fails | Medium | Integration testing |

---

# 13. Definition of Done

The Quality Management, Recording & Evaluation domain is complete when:

- Quality strategy is approved.
- Quality requirements are documented.
- Recording requirements are approved.
- Recording policies are configured.
- Recording conditions are validated.
- Recording exclusions are validated.
- Voice recording is operational.
- Digital recording is operational where required.
- Screen recording is operational where required.
- Sensitive-data controls are validated.
- PCI controls are validated where applicable.
- Pause/resume is validated where applicable.
- Recording retention is configured.
- Recording access is secured.
- Recording search is operational.
- Recording export is controlled.
- Deletion requirements are implemented.
- Quality evaluation framework is approved.
- Evaluation forms are configured.
- Evaluation questions are approved.
- Scoring is configured.
- Critical failures are configured where required.
- Evaluation assignment is configured.
- Evaluation workflow is operational.
- Evaluators are trained.
- Calibration is completed.
- Quality dashboards are operational.
- Quality reports are operational.
- Agent scorecards are operational.
- Supervisor quality reporting is operational.
- Coaching process is defined.
- Agent feedback process is defined.
- Quality testing is completed.
- Production recording is validated.
- UAT is completed.
- Operational ownership is established.
- Quality governance is established.

---

# 14. Domain Gate

```text
QUALITY STRATEGY APPROVED
            +
RECORDING STRATEGY APPROVED
            +
RETENTION APPROVED
            +
SECURITY APPROVED
            +
COMPLIANCE APPROVED
            +
RECORDING CONFIGURED
            +
RECORDING VALIDATED
            +
EVALUATION FORMS APPROVED
            +
SCORING APPROVED
            +
EVALUATION WORKFLOW CONFIGURED
            +
CALIBRATION COMPLETED
            +
QUALITY REPORTING VALIDATED
            +
COACHING MODEL READY
            +
UAT ACCEPTED
            +
OPERATIONS READY
            ↓
QUALITY READY FOR PRODUCTION
```

---

# 15. Domain File Catalogue

```text
10-Quality-Management-Recording-Evaluation/
│
├── README.md
├── 01-Quality-Management-Strategy.md
├── 02-Quality-Programme-Governance.md
├── 03-Quality-Requirements.md
├── 04-Interaction-Recording-Strategy.md
├── 05-Voice-Recording.md
├── 06-Digital-Interaction-Recording.md
├── 07-Screen-Recording.md
├── 08-Recording-Policies.md
├── 09-Recording-Triggers-Conditions.md
├── 10-Recording-Exclusions.md
├── 11-Recording-Retention.md
├── 12-Recording-Security.md
├── 13-Recording-Access-Control.md
├── 14-Recording-Encryption-Protection.md
├── 15-Recording-Compliance.md
├── 16-PCI-Sensitive-Data-Controls.md
├── 17-Recording-Pause-Resume.md
├── 18-Recording-Search-Retrieval.md
├── 19-Recording-Export.md
├── 20-Recording-Deletion-Legal-Hold.md
├── 21-Interaction-Search.md
├── 22-Quality-Evaluation-Framework.md
├── 23-Evaluation-Forms.md
├── 24-Evaluation-Questions.md
├── 25-Evaluation-Scoring.md
├── 26-Critical-Questions-Critical-Failures.md
├── 27-Evaluation-Assignment.md
├── 28-Evaluation-Workflow.md
├── 29-Evaluator-Management.md
├── 30-Evaluation-Calibration.md
├── 31-Quality-Monitoring.md
├── 32-Interaction-Monitoring.md
├── 33-Screen-Monitoring.md
├── 34-Speech-Text-Analytics.md
├── 35-Topics-Categories.md
├── 36-Sentiment-Conversation-Insights.md
├── 37-Compliance-Monitoring.md
├── 38-Quality-Dashboards.md
├── 39-Quality-Reporting.md
├── 40-Agent-Scorecards.md
├── 41-Supervisor-Quality-Management.md
├── 42-Coaching.md
├── 43-Agent-Feedback.md
├── 44-Dispute-Appeal.md
├── 45-Quality-Testing-Validation.md
├── 46-Quality-Operations-Continuous-Improvement.md
└── 47-Quality-Governance-Audit.md
```

---

# 16. Capability Catalogue

The following sections define the implementation requirements for each capability.

---

# 17. Implementation Task Decomposition Preview

The final implementation catalogue should decompose this domain into atomic tasks.

Example:

```text
QM-010-001  Define quality management strategy
QM-010-002  Identify quality stakeholders
QM-010-003  Define quality operating model
QM-010-004  Define quality governance
QM-010-005  Conduct quality requirements workshops
QM-010-006  Identify recording requirements
QM-010-007  Identify evaluation requirements
QM-010-008  Identify coaching requirements
QM-010-009  Identify compliance requirements
QM-010-010  Define interaction recording strategy
QM-010-011  Identify voice recording scope
QM-010-012  Identify digital recording scope
QM-010-013  Identify screen recording scope
QM-010-014  Define recording policies
QM-010-015  Define recording triggers
QM-010-016  Define recording exclusions
QM-010-017  Define recording retention
QM-010-018  Define recording access model
QM-010-019  Define recording security model
QM-010-020  Define recording compliance requirements
QM-010-021  Identify PCI-sensitive data requirements
QM-010-022  Define recording pause-resume requirements
QM-010-023  Configure voice recording
QM-010-024  Validate voice recording
QM-010-025  Configure digital recording
QM-010-026  Validate digital recording
QM-010-027  Configure screen recording
QM-010-028  Validate screen recording
QM-010-029  Configure recording policies
QM-010-030  Validate recording triggers
QM-010-031  Validate recording exclusions
QM-010-032  Configure retention
QM-010-033  Validate retention behaviour
QM-010-034  Configure recording security
QM-010-035  Test recording access
QM-010-036  Test unauthorised recording access
QM-010-037  Configure sensitive-data controls
QM-010-038  Configure pause-resume
QM-010-039  Test pause-resume
QM-010-040  Configure recording search
QM-010-041  Validate recording retrieval
QM-010-042  Define recording export requirements
QM-010-043  Configure controlled recording export
QM-010-044  Define deletion requirements
QM-010-045  Define legal-hold requirements
QM-010-046  Validate deletion controls
QM-010-047  Define interaction search requirements
QM-010-048  Configure interaction search
QM-010-049  Define quality evaluation framework
QM-010-050  Define evaluation forms
QM-010-051  Define evaluation questions
QM-010-052  Define evaluation scoring
QM-010-053  Define critical questions
QM-010-054  Define critical failure handling
QM-010-055  Configure evaluation forms
QM-010-056  Configure evaluation scoring
QM-010-057  Configure evaluation assignment
QM-010-058  Configure evaluation workflow
QM-010-059  Define evaluator roles
QM-010-060  Configure evaluator access
QM-010-061  Develop evaluator training
QM-010-062  Define calibration methodology
QM-010-063  Conduct initial calibration
QM-010-064  Define quality monitoring requirements
QM-010-065  Configure quality monitoring
QM-010-066  Configure interaction monitoring
QM-010-067  Configure screen monitoring
QM-010-068  Define speech analytics requirements
QM-010-069  Configure speech analytics
QM-010-070  Define text analytics requirements
QM-010-071  Configure text analytics
QM-010-072  Define topic taxonomy
QM-010-073  Configure topics
QM-010-074  Define sentiment requirements
QM-010-075  Validate conversation insights
QM-010-076  Define compliance monitoring requirements
QM-010-077  Configure compliance monitoring
QM-010-078  Build quality dashboard
QM-010-079  Build quality reports
QM-010-080  Build agent scorecards
QM-010-081  Build supervisor quality reporting
QM-010-082  Define coaching framework
QM-010-083  Configure coaching workflow
QM-010-084  Define agent feedback process
QM-010-085  Train supervisors on feedback
QM-010-086  Define evaluation dispute process
QM-010-087  Configure dispute process where applicable
QM-010-088  Create recording test plan
QM-010-089  Create evaluation test plan
QM-010-090  Execute recording testing
QM-010-091  Execute playback testing
QM-010-092  Execute recording security testing
QM-010-093  Execute sensitive-data testing
QM-010-094  Execute retention testing
QM-010-095  Execute evaluation form testing
QM-010-096  Execute evaluation scoring testing
QM-010-097  Execute evaluation workflow testing
QM-010-098  Execute quality reporting testing
QM-010-099  Execute quality UAT
QM-010-100  Resolve quality defects
QM-010-101  Retest quality defects
QM-010-102  Prepare production quality deployment
QM-010-103  Enable production recording
QM-010-104  Validate production recordings
QM-010-105  Validate production evaluations
QM-010-106  Monitor quality during hypercare
QM-010-107  Complete quality operational handover
QM-010-108  Establish calibration schedule
QM-010-109  Establish quality governance
QM-010-110  Establish recording access review
QM-010-111  Establish quality continuous improvement
```

The final implementation workbook should further decompose these tasks where separate activities are required for:

- Requirements
- Architecture
- Design
- Configuration
- Development
- Security
- Compliance
- Data preparation
- Testing
- UAT
- Business approval
- Deployment
- Validation
- Documentation
- Training
- Operational handover

---

# 18. Cross-Domain Dependencies

| Dependency Domain | Quality Dependency |
|---|---|
| 01 — Core Platform | Platform configuration and divisions |
| 02 — Identity & Access | Quality and recording permissions |
| 03 — Voice & Telephony | Voice recording |
| 04 — ACD Routing | Queue and interaction context |
| 05 — Architect | Flow behaviour and sensitive-data handling |
| 06 — Digital | Digital interaction capture |
| 07 — WFM | Workforce and performance context |
| 08 — Data & Integrations | External quality and data integrations |
| 09 — Analytics & Reporting | Quality reporting and dashboards |
| 10 — Quality | Current domain |
| 11 — Security | Recording security and access |
| 12 — Testing | Quality validation |
| 13 — Migration | Historical recording assessment |
| 14 — Operations | Quality operational ownership |
| 15 — Optimisation | Quality improvement |

---

# 19. Critical Cross-Domain Relationships

## Voice & Telephony → Quality

Voice configuration determines:

- Which interactions can be recorded
- Recording behaviour
- Call metadata
- Interaction identification
- Recording availability

---

## ACD Routing → Quality

Routing configuration provides:

- Queue
- Agent
- Skill
- Interaction
- Wrap-up
- Outcome

context required for evaluation and quality reporting.

---

## Architect → Quality

Architect flows may need to support:

- Recording control
- Sensitive-data handling
- Payment processes
- Self-service measurement
- Interaction context

---

## Digital → Quality

Digital channels may require separate:

- Recording
- Evaluation
- Search
- Retention
- Quality processes

---

## Analytics → Quality

Quality data should feed:

- Quality dashboards
- Agent scorecards
- Management reporting
- Compliance reporting
- Continuous improvement

---

## Identity & Access → Quality

Quality access must respect:

- Roles
- Divisions
- Queues
- Teams
- Agent relationships
- Security boundaries

---

# 20. Recording Design Sequence

```text
Recording Requirements
        ↓
Interaction Inventory
        ↓
Recording Scope
        ↓
Recording Policies
        ↓
Recording Conditions
        ↓
Sensitive Data Assessment
        ↓
Retention
        ↓
Access Control
        ↓
Configuration
        ↓
Functional Testing
        ↓
Security Testing
        ↓
Compliance Validation
        ↓
Production Enablement
        ↓
Production Validation
```

---

# 21. Evaluation Design Sequence

```text
Quality Objectives
        ↓
Quality Behaviours
        ↓
Evaluation Forms
        ↓
Evaluation Questions
        ↓
Scoring Model
        ↓
Critical Failures
        ↓
Sampling Strategy
        ↓
Assignment Model
        ↓
Evaluator Training
        ↓
Calibration
        ↓
Configuration
        ↓
Testing
        ↓
UAT
        ↓
Production
```

---

# 22. Quality Operating Model

```text
                         Quality Governance
                                │
                                ▼
                         QA Management
                                │
               ┌────────────────┼────────────────┐
               │                │                │
               ▼                ▼                ▼
           Evaluators       Supervisors       Compliance
               │                │                │
               ▼                ▼                ▼
          Evaluations       Coaching          Monitoring
               │                │                │
               └────────────────┼────────────────┘
                                ▼
                         Quality Reporting
                                │
                                ▼
                      Continuous Improvement
```

---

# 23. Evaluation Sampling Strategy

Sampling should be designed rather than arbitrarily selected.

Potential dimensions include:

- Agent
- Queue
- Channel
- Interaction type
- Customer type
- Business process
- Risk
- Compliance category
- New agent
- Performance concern
- Random sample
- Targeted sample
- Escalated interaction

Sampling should balance:

```text
Coverage
+
Risk
+
Fairness
+
Operational Cost
+
Statistical Usefulness
```

---

# 24. Evaluation Calibration Model

```text
Select Common Interaction
          │
          ▼
Independent Evaluation
          │
          ▼
Compare Results
          │
          ▼
Identify Variance
          │
          ▼
Discuss Interpretation
          │
          ▼
Agree Expected Result
          │
          ▼
Document Guidance
          │
          ▼
Update Training
          │
          ▼
Repeat Periodically
```

Calibration should be treated as an ongoing quality control rather than a one-time implementation activity.

---

# 25. Quality Governance Model

```text
                    Quality Governance Board
                              │
          ┌───────────────────┼───────────────────┐
          │                   │                   │
          ▼                   ▼                   ▼
      Recording           Evaluation           Compliance
      Governance          Governance           Governance
          │                   │                   │
          └───────────────────┼───────────────────┘
                              ▼
                       Quality Operations
                              │
                              ▼
                       Continuous Improvement
```

---

# 26. Recording Security Model

```text
Interaction
    │
    ▼
Recording
    │
    ▼
Protected Storage
    │
    ├──────────────► Authorised QA
    │
    ├──────────────► Authorised Supervisor
    │
    ├──────────────► Authorised Compliance
    │
    └──────────────► Authorised Administrator
```

Every access path should be evaluated against:

- Business need
- Least privilege
- Data classification
- Regulatory requirements
- Auditability
- Retention
- Export restrictions

---

# 27. Quality Data Lifecycle

```text
Interaction
    │
    ▼
Recording / Interaction Data
    │
    ▼
Interaction Search
    │
    ▼
Evaluation Selection
    │
    ▼
Evaluation
    │
    ▼
Scoring
    │
    ├──────────────► Quality Reporting
    │
    ├──────────────► Agent Scorecard
    │
    ├──────────────► Coaching
    │
    └──────────────► Compliance
                          │
                          ▼
                  Continuous Improvement
```

---

# 28. Quality Acceptance Model

A quality capability is accepted only when:

```text
Business Requirement
        +
Configuration
        +
Security
        +
Compliance
        +
Functional Test
        +
Data Validation
        +
Reporting
        +
UAT
        ↓
Accepted Quality Capability
```

---

# 29. Quality Environment Model

The standard quality deployment should consider:

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

- Recording availability
- Test interactions
- Test data
- Evaluation forms
- Evaluator permissions
- Agent permissions
- Security
- Sensitive data
- External integrations
- Reporting
- Retention behaviour

---

# 30. Quality Documentation Standards

Every production quality form should document:

1. Form name
2. Purpose
3. Interaction type
4. Audience
5. Owner
6. Questions
7. Scoring
8. Weighting
9. Critical questions
10. Critical failure rules
11. Evaluation assignment
12. Sampling method
13. Calibration requirements
14. Reporting
15. Agent visibility
16. Coaching linkage
17. Change process
18. Review frequency
19. Retirement criteria

Every recording policy should document:

1. Policy name
2. Scope
3. Interaction types
4. Channels
5. Queues
6. Agents
7. Trigger
8. Exclusions
9. Sensitive-data handling
10. Retention
11. Access
12. Compliance requirements
13. Owner
14. Review frequency

---

# 31. Production Recording Validation

Production validation should confirm:

- Interaction is recorded.
- Recording is associated with correct interaction.
- Recording can be located.
- Recording can be played by authorised users.
- Recording cannot be accessed by unauthorised users.
- Sensitive data is protected.
- Pause/resume operates correctly where applicable.
- Recording metadata is correct.
- Retention behaviour is correct.
- Quality users can access recordings.
- Reporting reflects recording availability.

---

# 32. Quality UAT Scenarios

UAT should include at least:

### Recording

- Normal inbound interaction
- Normal outbound interaction
- Transfer
- Hold
- Conference
- Disconnect
- Queue interaction
- Agent interaction
- Sensitive-data interaction
- Excluded interaction
- Digital interaction where applicable

### Evaluation

- Standard evaluation
- Critical failure
- Partial score
- Maximum score
- Minimum score
- Evaluation assignment
- Evaluation completion
- Agent feedback
- Coaching
- Dispute where applicable

### Security

- Agent access
- Supervisor access
- QA access
- Compliance access
- Administrator access
- Unauthorised access

### Reporting

- Agent quality
- Team quality
- Queue quality
- Critical failures
- Evaluation completion
- Quality trend

---

# 33. Quality Support Model

The BAU support model should define:

```text
L1 — Operations
      │
      ▼
L2 — Genesys / Contact Centre Support
      │
      ▼
L3 — Genesys Platform / Engineering
      │
      ▼
Vendor / Specialist Support
```

Support procedures should cover:

- Missing recording
- Recording playback failure
- Incorrect recording
- Evaluation failure
- Evaluation assignment failure
- Incorrect scoring
- Access problems
- Retention issues
- Sensitive-data incidents
- Quality reporting discrepancies

---

# 34. Quality Change Management

Changes requiring governance include:

- Recording policies
- Recording scope
- Retention
- Access permissions
- Evaluation forms
- Evaluation questions
- Scoring
- Critical failures
- Sampling
- Quality KPIs
- Dashboards
- Coaching workflows
- Compliance monitoring
- Analytics topics

Every material change should include:

```text
Change Request
      ↓
Impact Assessment
      ↓
Security / Compliance Review
      ↓
Configuration
      ↓
Testing
      ↓
Business Approval
      ↓
Production Deployment
      ↓
Validation
```

---

# 35. Quality Continuous Improvement

The quality programme should periodically analyse:

- Quality trends
- Critical failures
- Customer complaints
- Evaluation variance
- Agent performance
- Coaching outcomes
- Repeat failures
- Compliance failures
- Process issues
- Training needs
- Knowledge gaps
- Customer experience trends

The output should feed back into:

- Training
- Coaching
- Knowledge
- Architect flows
- Routing
- Processes
- Workforce planning
- Product/service improvements

---

# 36. Reporting Integration

Quality reporting should align with Domain 09.

Required reporting may include:

- Quality score by agent
- Quality score by team
- Quality score by queue
- Quality trend
- Critical failure rate
- Evaluation completion
- Evaluation coverage
- Evaluator agreement
- Coaching completion
- Coaching outcomes
- Compliance failures

The quality KPI definitions must remain consistent with the enterprise KPI framework.

---

# 37. Implementation Dependencies

| Activity | Primary Dependency |
|---|---|
| Quality Strategy | Project scope |
| Recording Strategy | Voice / Digital requirements |
| Recording Configuration | Recording strategy |
| Recording Security | Identity & Security |
| Sensitive Data Controls | Compliance |
| Evaluation Framework | Quality requirements |
| Evaluation Forms | Evaluation framework |
| Evaluation Scoring | Evaluation questions |
| Evaluation Assignment | Forms and users |
| Calibration | Evaluation framework |
| Quality Reporting | Analytics & Reporting |
| Coaching | Evaluation workflow |
| UAT | Configuration and SIT |
| Production | UAT approval |
| BAU | Operational readiness |

---

# 38. Critical Path Considerations

The following may become critical-path activities:

```text
Recording Requirements
        ↓
Security / Compliance Approval
        ↓
Recording Design
        ↓
Recording Configuration
        ↓
Sensitive Data Testing
        ↓
Recording Validation
        ↓
Evaluation Framework
        ↓
Evaluation Forms
        ↓
Scoring Configuration
        ↓
Calibration
        ↓
UAT
        ↓
Production Enablement
```

Potential blockers include:

- Delayed privacy approval
- Delayed PCI assessment
- Unresolved recording requirements
- Evaluation form approval delays
- Security role delays
- Incomplete test interactions
- Unavailable QA resources
- Incomplete reporting requirements

---

# 39. Domain Completion Gate

The Quality Management, Recording & Evaluation domain is considered **capability-complete** when:

- Quality strategy is approved.
- Quality governance is established.
- Quality requirements are complete.
- Recording strategy is approved.
- Voice recording requirements are complete.
- Digital recording requirements are complete where applicable.
- Screen recording requirements are complete where applicable.
- Recording policies are defined.
- Recording conditions are defined.
- Recording exclusions are defined.
- Retention is approved.
- Recording security is approved.
- Recording access is defined.
- Compliance requirements are approved.
- Sensitive-data handling is defined.
- Pause/resume is defined where applicable.
- Recording search is defined.
- Recording export is governed.
- Deletion and legal hold are defined where required.
- Interaction search is defined.
- Evaluation framework is approved.
- Evaluation forms are approved.
- Evaluation questions are approved.
- Evaluation scoring is approved.
- Critical failures are defined where applicable.
- Evaluation assignment is defined.
- Evaluation workflow is defined.
- Evaluator roles are established.
- Calibration is defined.
- Quality monitoring is defined.
- Interaction monitoring is defined where applicable.
- Screen monitoring is defined where applicable.
- Speech/text analytics are defined where applicable.
- Topics are defined where applicable.
- Sentiment requirements are defined where applicable.
- Compliance monitoring is defined where applicable.
- Quality dashboards are defined.
- Quality reporting is defined.
- Agent scorecards are defined.
- Supervisor quality management is defined.
- Coaching is defined.
- Agent feedback is defined.
- Dispute processes are defined where applicable.
- Testing is defined.
- UAT is defined.
- Operational ownership is established.
- Governance is established.

```text
QUALITY STRATEGY
        │
        ▼
RECORDING REQUIREMENTS
        │
        ▼
SECURITY / COMPLIANCE
        │
        ▼
RECORDING DESIGN
        │
        ▼
RECORDING CONFIGURATION
        │
        ▼
EVALUATION FRAMEWORK
        │
        ▼
EVALUATION CONFIGURATION
        │
        ▼
CALIBRATION
        │
        ▼
QUALITY REPORTING
        │
        ▼
TESTING
        │
        ▼
UAT
        │
        ▼
PRODUCTION
        │
        ▼
QUALITY OPERATIONS
        │
        ▼
CONTINUOUS IMPROVEMENT
```

---

# 40. Domain Completion

**Layer:** 2  
**Domain:** 10 — Quality Management, Recording & Evaluation  
**Capability Documents:** 47  
**Status:** Capability catalogue complete  
**Next Activity:** Continue with Layer 2 Domain 11.

This domain defines the **capability catalogue**. It is not yet the final implementation schedule.

The eventual task catalogue will convert these capabilities into detailed implementation tasks suitable for the master Genesys Cloud deployment workbook.

The final implementation workbook will contain:

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

# Phase Completion

**Layer 2.10 — Quality Management, Recording & Evaluation is complete at capability-catalogue level.**

**Next Domain:**

`11 — Security, Compliance & Governance`
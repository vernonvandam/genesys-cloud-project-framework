# Phase 09 — Operational Readiness & Cutover Preparation

## 1. Purpose

Phase 09 prepares the validated Genesys Cloud solution, customer organisation, project team, operational teams, support teams and business for production deployment.

This phase converts the technically validated solution from Phase 08 into a **production-ready operational service**.

The focus is on ensuring that the organisation can safely operate, support, administer, monitor, maintain and govern the Genesys Cloud solution from the moment production deployment begins.

This phase also establishes the controlled path from the tested solution to production through:

- Operational readiness
- Support readiness
- Administration readiness
- Training readiness
- Knowledge transfer
- Documentation
- Security readiness
- Monitoring readiness
- Business continuity
- Disaster recovery considerations
- Cutover planning
- Migration planning
- Communications
- Go-live governance
- Hypercare preparation
- Rollback planning
- Final production readiness assessment

Phase 09 builds upon:

- Phase 03 — Requirements & Solution Definition
- Phase 04 — Solution Architecture & Detailed Design
- Phase 05 — Platform Foundation & Environment Build
- Phase 06 — Feature Configuration & Solution Build
- Phase 07 — Integration & Data Migration
- Phase 08 — Testing & Validation

The outcome is a **production-ready Genesys Cloud deployment with an approved cutover plan and operational acceptance**.

---

# 2. Phase Objective

By the end of Phase 09:

- Operational processes are defined.
- Support processes are defined.
- Support ownership is established.
- Service ownership is established.
- Administration responsibilities are established.
- Monitoring is operational.
- Alerting is operational.
- Incident procedures are documented.
- Problem management procedures are documented.
- Change management procedures are documented.
- Access management procedures are documented.
- User lifecycle processes are documented.
- Genesys Cloud administration procedures are documented.
- Integration support procedures are documented.
- Reporting support procedures are documented.
- Recording support procedures are documented.
- Security processes are documented.
- Compliance processes are documented.
- Business continuity procedures are documented.
- Disaster recovery considerations are documented.
- Training is completed or scheduled.
- Knowledge transfer is completed.
- Operational documentation is complete.
- Support teams are ready.
- Business users are ready.
- Cutover strategy is approved.
- Cutover runbook is complete.
- Cutover tasks are sequenced.
- Cutover dependencies are identified.
- Migration tasks are identified.
- Data migration approach is confirmed.
- Production configuration is baselined.
- Production access is validated.
- Production integrations are ready.
- Production numbers and telephony are ready.
- Rollback strategy is defined.
- Go-live communications are prepared.
- Hypercare model is defined.
- Go-live governance is defined.
- Final production readiness review is completed.
- Gate 09 is passed.

---

# 3. Phase Position

The deployment lifecycle is:

```text
Phase 07
Integration & Data Migration
        ↓
Phase 08
Testing & Validation
        ↓
Phase 09
Operational Readiness & Cutover Preparation
        ↓
Phase 10
Production Deployment & Go-Live
        ↓
Phase 11
Hypercare & Stabilisation
        ↓
Phase 12
BAU Handover & Project Closure
```

Phase 09 is therefore the final preparation stage before production deployment.

---

# 4. Phase Entry Criteria

Phase 09 should not formally commence until:

- Gate 08 has passed.
- UAT is complete.
- Critical defects are closed.
- High-severity defects are closed or formally accepted.
- Business acceptance has been obtained.
- Production configuration baseline is available.
- Solution architecture is approved.
- Integration architecture is approved.
- Test results are available.
- Known limitations are documented.
- Production environment is available or scheduled.
- Production dependencies are identified.
- Business go-live target is known.

Any exceptions must be documented and formally accepted.

---

# 5. Phase Workstreams

The master deployment methodology should structure Phase 09 into the following workstreams:

### 09.01 Operational Readiness Planning
### 09.02 Service Ownership
### 09.03 Support Model
### 09.04 Service Management
### 09.05 Administration Readiness
### 09.06 User Lifecycle Management
### 09.07 Security Operations
### 09.08 Monitoring & Alerting
### 09.09 Integration Operations
### 09.10 Telephony Operations
### 09.11 Reporting Operations
### 09.12 Recording Operations
### 09.13 WFM Operations
### 09.14 QM Operations
### 09.15 Digital Channel Operations
### 09.16 Knowledge Management
### 09.17 Training
### 09.18 Knowledge Transfer
### 09.19 Documentation
### 09.20 Business Continuity
### 09.21 Disaster Recovery
### 09.22 Data Migration Readiness
### 09.23 Production Configuration Readiness
### 09.24 Cutover Strategy
### 09.25 Cutover Runbook
### 09.26 Migration Runbook
### 09.27 Rollback Strategy
### 09.28 Go-Live Communications
### 09.29 Hypercare Planning
### 09.30 Go-Live Governance
### 09.31 Final Readiness Review
### 09.32 Phase Completion & Gate Preparation

Not every workstream applies to every deployment.

Each activity in the master spreadsheet should be classified as:

- Required
- Conditional
- Optional
- Not Applicable

---

# 6. Operational Readiness Strategy

Establish the overall operational readiness strategy.

The strategy must answer:

- Who owns the Genesys Cloud service?
- Who administers Genesys Cloud?
- Who supports agents?
- Who supports integrations?
- Who supports telephony?
- Who supports identity?
- Who supports reporting?
- Who supports WFM?
- Who supports QM?
- Who manages incidents?
- Who manages changes?
- Who manages access?
- Who manages vendors?
- Who manages business continuity?
- Who owns operational decisions?

The operating model should distinguish between:

```text
Business Ownership
        ↓
Service Ownership
        ↓
Technical Ownership
        ↓
Platform Administration
        ↓
Integration Support
        ↓
Operational Support
        ↓
Agent / Supervisor Support
```

---

# 7. Operational Readiness Assessment

Conduct a formal operational readiness assessment.

## Activities

1. Review Phase 08 results.
2. Review open defects.
3. Review accepted limitations.
4. Review operational requirements.
5. Review support requirements.
6. Review security requirements.
7. Review compliance requirements.
8. Review monitoring requirements.
9. Review documentation.
10. Review training.
11. Review support staffing.
12. Review cutover readiness.
13. Review business readiness.
14. Record gaps.
15. Assign remediation actions.

## Output

**Operational Readiness Assessment**

---

# 8. Service Ownership

Define ownership of the production service.

## Define

- Business owner
- Service owner
- Technical owner
- Platform owner
- Application owner
- Integration owner
- Telephony owner
- Security owner
- Data owner
- Reporting owner
- WFM owner
- QM owner
- Vendor owner

## Ownership Model

```text
Business
   ↓
Service Owner
   ↓
Technical Owner
   ├── Genesys Cloud
   ├── Telephony
   ├── Integrations
   ├── Identity
   ├── Data
   └── Reporting
```

---

# 9. Support Model

Define the production support model.

A typical model may be:

```text
L1 — Service Desk
        ↓
L2 — Application / Genesys Support
        ↓
L3 — Engineering / Specialist Support
        ↓
Vendor / Genesys Support
```

The actual model must reflect customer operating requirements.

## Define

- Support hours
- Business hours
- After-hours support
- On-call support
- Escalation procedures
- Incident severity
- Response targets
- Resolution targets
- Vendor escalation
- Major incident management
- Communication process

---

# 10. Support Responsibility Matrix

Create a support responsibility matrix.

| Service Area | L1 | L2 | L3 | Vendor | Owner |
|---|---|---|---|---|---|
| User login | Customer | IAM | IAM Engineering | Conditional | IAM Owner |
| Queue configuration | Service Desk | Genesys Admin | Genesys Engineer | Conditional | Platform Owner |
| Architect | Service Desk | Genesys Admin | Architect Engineer | Conditional | Technical Owner |
| CRM integration | Service Desk | Integration Support | Integration Engineering | Conditional | Integration Owner |
| Telephony | Service Desk | Telephony Support | Telecom Engineering | Carrier / Genesys | Telephony Owner |
| Reporting | Service Desk | Reporting Support | Analytics | Conditional | Reporting Owner |

---

# 11. Service Management Integration

Integrate Genesys Cloud into the customer's service management framework.

Where applicable, configure or document:

- Incident management
- Problem management
- Change management
- Request fulfilment
- Access management
- Knowledge management
- Major incident management
- Configuration management
- Service reporting

## Activities

1. Identify ITSM platform.
2. Define support queues.
3. Define ticket categories.
4. Define priority.
5. Define escalation.
6. Define assignment groups.
7. Define SLAs.
8. Define escalation paths.
9. Define knowledge articles.
10. Validate operational workflow.

---

# 12. Incident Management

Define incident procedures.

## Incidents

Potential categories include:

- Platform access
- Authentication
- Telephony
- Queue routing
- Architect
- Integration
- CRM
- Recording
- Reporting
- WFM
- QM
- Digital channels
- Performance
- Security
- Data

## Define

- Detection
- Logging
- Classification
- Prioritisation
- Assignment
- Investigation
- Escalation
- Resolution
- Communication
- Closure
- Post-incident review

---

# 13. Major Incident Management

Define major incident procedures.

## Activities

1. Define major incident criteria.
2. Define incident commander.
3. Define technical bridge.
4. Define business communications.
5. Define escalation.
6. Define vendor escalation.
7. Define customer communication.
8. Define recovery process.
9. Define post-incident review.

---

# 14. Problem Management

Define how recurring or systemic Genesys Cloud issues will be managed.

Potential problem sources:

- Recurring integration failures
- Repeated routing failures
- Telephony instability
- Authentication problems
- Configuration defects
- Reporting inconsistencies
- User provisioning issues

## Define

- Problem identification
- Root cause analysis
- Workaround
- Permanent fix
- Known error
- Trend analysis
- Problem closure

---

# 15. Change Management

Genesys Cloud configuration changes must be governed after go-live.

## Define

- Standard changes
- Normal changes
- Emergency changes
- Approval process
- Testing requirements
- Implementation process
- Rollback
- Documentation
- Change evidence

Changes should be traceable to:

```text
Change Request
     ↓
Impact Assessment
     ↓
Approval
     ↓
Build
     ↓
Test
     ↓
Release
     ↓
Validation
     ↓
Closure
```

---

# 16. Genesys Cloud Administration Readiness

Validate that administrators can perform required operational tasks.

## Administrative Functions

Potential activities include:

- User management
- Role management
- Permission management
- Queue management
- Skill management
- Language management
- Architect management
- Routing management
- Telephony management
- Recording management
- Reporting
- Analytics
- Integrations
- Data Tables
- Data Actions
- Schedules
- Business Units
- Management Units
- Workforce Management
- Quality Management
- Digital channels

Only applicable capabilities need to be included.

---

# 17. Administration Procedures

Document standard operating procedures for common administrative activities.

Examples:

- Create user
- Disable user
- Modify user
- Assign queue
- Remove queue
- Assign skill
- Remove skill
- Change role
- Modify routing
- Change Architect flow
- Modify business hours
- Change holiday schedule
- Add number
- Modify recording configuration
- Retrieve recording
- Modify dashboard
- Modify report

---

# 18. User Lifecycle Management

Define the complete user lifecycle.

```text
Joiner
   ↓
Provision
   ↓
Assign Role
   ↓
Assign Division
   ↓
Assign Queue
   ↓
Assign Skills
   ↓
Operate
   ↓
Change Role
   ↓
Transfer
   ↓
Leaver
   ↓
Disable
   ↓
Remove Access
```

## Activities

1. Define joiner process.
2. Define mover process.
3. Define leaver process.
4. Define access approval.
5. Define provisioning.
6. Define deprovisioning.
7. Define queue membership.
8. Define skill assignment.
9. Define role assignment.
10. Define audit process.

---

# 19. Identity & Access Operations

Validate operational identity processes.

## Define

- SSO support
- MFA support
- Password support
- Account lockout
- User provisioning
- User deprovisioning
- Role assignment
- Access reviews
- Privileged access
- Service accounts
- OAuth credentials
- API credentials

---

# 20. Privileged Access Management

Where applicable, define controls for privileged Genesys Cloud access.

## Validate

- Administrator roles
- Elevated permissions
- Service accounts
- Integration credentials
- API clients
- OAuth clients
- Credential ownership
- Credential rotation
- Access logging
- Emergency access

---

# 21. Security Operations

Define operational security responsibilities.

## Activities

1. Review security controls.
2. Define security monitoring.
3. Define access review.
4. Define privileged access review.
5. Define incident escalation.
6. Define security incident process.
7. Define audit process.
8. Define credential management.
9. Define integration secret management.
10. Define security reporting.

---

# 22. Monitoring Strategy

Define monitoring for the production service.

Potential monitoring domains:

- Genesys Cloud availability
- Telephony
- Queue performance
- Agent state
- Integration health
- Data Actions
- APIs
- CRM
- Identity
- Digital channels
- Recording
- Reporting
- WFM
- QM
- Infrastructure supporting integrations

Monitoring should distinguish between:

```text
Platform Health
      ↓
Application Health
      ↓
Integration Health
      ↓
Business Process Health
```

---

# 23. Alerting

Define production alerting.

## Alerts

Potential alerts include:

- Integration failure
- API authentication failure
- High API latency
- Queue abnormality
- Telephony failure
- CRM unavailable
- Data Action failure
- Authentication failure
- High error rate
- Recording failure
- Data migration failure
- Monitoring failure

## Define

- Threshold
- Severity
- Recipient
- Escalation
- Response
- Resolution
- Evidence

---

# 24. Integration Operations

For every integration define the production operational model.

## Document

- Integration owner
- Source system
- Destination system
- Endpoint
- Authentication
- Credentials
- Certificate
- Dependency
- Monitoring
- Logging
- Error handling
- Retry
- Timeout
- Escalation
- Vendor
- Support contact

---

# 25. Integration Support Runbooks

Create operational runbooks for critical integrations.

Each runbook should contain:

1. Purpose
2. Architecture
3. Dependencies
4. Monitoring
5. Common errors
6. Troubleshooting
7. Restart / recovery
8. Escalation
9. Vendor support
10. Validation
11. Rollback

---

# 26. Telephony Operational Readiness

Validate operational readiness of telephony.

## Confirm

- Numbers
- DID routing
- Caller ID
- Carrier
- SIP
- Edge devices where applicable
- BYOC configuration where applicable
- Network
- QoS
- Emergency calling
- Call recording
- Failover
- Number porting
- Carrier escalation

---

# 27. Telephony Cutover Readiness

Confirm:

- Number porting schedule
- Carrier contacts
- Porting dependencies
- DNS requirements
- SIP dependencies
- Routing changes
- Business hours
- Emergency services
- Test numbers
- Production numbers
- Rollback capability

---

# 28. Reporting Operations

Define ongoing reporting responsibilities.

## Define

- Report ownership
- Dashboard ownership
- Scheduled reports
- Distribution lists
- Data validation
- Reporting changes
- Access requests
- Reporting incidents
- Data retention

---

# 29. Recording Operations

Define operational recording procedures.

## Document

- Recording retrieval
- Recording access
- Recording permissions
- Retention
- Search
- Export
- Compliance requests
- Recording incident handling
- Recording monitoring

---

# 30. Workforce Management Operations

Where WFM is in scope, prepare operational procedures.

## Define

- Forecasting
- Scheduling
- Schedule changes
- Time-off
- Adherence
- Intraday management
- WFM administration
- User management
- Reporting
- Support
- Escalation

---

# 31. Quality Management Operations

Where QM is in scope, define:

- Evaluation process
- Evaluation assignment
- Calibration
- Coaching
- Quality reporting
- Evaluator management
- Form management
- Recording access
- Quality disputes
- Support

---

# 32. Digital Channel Operations

Where digital channels are in scope, define:

- Channel ownership
- Routing
- Queue management
- Digital hours
- Messaging support
- Email support
- Social messaging support
- Conversation recovery
- Customer escalation
- Digital reporting
- Digital incident handling

---

# 33. Knowledge Management

Create or update operational knowledge.

Potential articles:

- Login troubleshooting
- Agent troubleshooting
- Queue troubleshooting
- Telephony troubleshooting
- CRM troubleshooting
- Integration troubleshooting
- Reporting troubleshooting
- Recording retrieval
- Access requests
- User provisioning
- User deprovisioning
- Standard administration
- Incident response
- Major incident response

---

# 34. Documentation Readiness

The following documentation should be reviewed and baselined.

## Architecture

- High-level architecture
- Detailed architecture
- Integration architecture
- Network architecture
- Telephony architecture
- Security architecture

## Configuration

- Organisation configuration
- Queues
- Skills
- Users
- Roles
- Architect
- Routing
- Telephony
- Integrations
- Data Actions
- WFM
- QM
- Reporting

## Operations

- SOPs
- Support procedures
- Runbooks
- Incident procedures
- Change procedures
- Monitoring
- Escalation

---

# 35. Configuration Baseline

Create the production configuration baseline.

The baseline should capture:

- Organisation
- Division
- Users
- Roles
- Permissions
- Queues
- Skills
- Languages
- Architect flows
- Routing
- Schedules
- Business hours
- Holiday schedules
- Telephony
- Numbers
- Recording
- Integrations
- Data Actions
- Data Tables
- WFM
- QM
- Reporting
- Digital channels

The baseline should identify:

- Configuration version
- Date
- Owner
- Environment
- Approval
- Change reference

---

# 36. Configuration Promotion

Confirm how the tested configuration will be promoted into production.

Potential methods include:

- Manual configuration
- Genesys Cloud configuration migration
- Terraform
- APIs
- CI/CD
- Deployment scripts
- Controlled import/export

Where Infrastructure as Code is used, ensure:

- Source control is current.
- Production variables are correct.
- Secrets are externalised.
- State is controlled.
- Deployment is reviewed.
- Plan output is reviewed.
- Production changes are approved.

---

# 37. Production Access Validation

Validate access before cutover.

## Confirm

- Administrator access
- Support access
- Agent access
- Supervisor access
- Reporting access
- Integration access
- API access
- OAuth clients
- Service accounts
- SSO
- MFA
- Privileged access

Do not wait until the cutover window to discover access problems.

---

# 38. Production Integration Readiness

For each production integration confirm:

- Endpoint available
- DNS available
- Network path available
- Firewall rules complete
- Authentication available
- Certificates available
- Credentials available
- API client available
- Environment variables available
- Secrets available
- Monitoring available
- Support owner available
- Vendor support available

---

# 39. Production Data Readiness

Confirm production data requirements.

Potential data includes:

- Users
- Queues
- Skills
- Languages
- Customer data
- CRM records
- Contact data
- Schedules
- Historical data
- Reporting data

Define:

- Source
- Owner
- Migration method
- Timing
- Validation
- Rollback
- Security

---

# 40. Data Migration Readiness

Where production migration is required:

1. Confirm source data.
2. Confirm migration scope.
3. Confirm migration method.
4. Confirm data freeze.
5. Confirm extraction.
6. Confirm transformation.
7. Confirm load.
8. Confirm validation.
9. Confirm reconciliation.
10. Confirm rollback.

---

# 41. Data Freeze Strategy

Define whether source systems require a data freeze.

## Determine

- Freeze start
- Freeze duration
- Business owner
- Technical owner
- Systems affected
- Customer impact
- Exceptions
- Release criteria

---

# 42. Cutover Strategy

Define the overall production cutover approach.

Potential strategies:

- Big bang
- Phased deployment
- Pilot
- Business-unit rollout
- Queue-by-queue
- Site-by-site
- Channel-by-channel
- Parallel operation
- Hybrid

The strategy must be consistent with the architecture and business requirements.

---

# 43. Cutover Planning Principles

The cutover must be:

- Sequenced
- Time-bound
- Owned
- Testable
- Reversible where practical
- Communicated
- Auditable

Every cutover task must have:

- Owner
- Start
- Duration
- Dependency
- Expected result
- Validation
- Rollback action where applicable

---

# 44. Cutover Runbook

Create a detailed production cutover runbook.

## Required Sections

1. Purpose
2. Scope
3. Assumptions
4. Participants
5. Contacts
6. Preconditions
7. Change references
8. Communications
9. Cutover sequence
10. Data migration
11. Configuration deployment
12. Integration activation
13. Telephony activation
14. Validation
15. Business confirmation
16. Rollback
17. Hypercare transition
18. Completion

---

# 45. Cutover Command Structure

Define command roles.

Potential roles:

- Cutover Manager
- Technical Lead
- Genesys Cloud Lead
- Integration Lead
- Telephony Lead
- Data Lead
- IAM Lead
- Security Lead
- Business Lead
- UAT Lead
- Communications Lead
- Service Desk Lead
- Vendor Lead

---

# 46. Cutover Command Centre

Establish the cutover communication structure.

Potential channels:

- Conference bridge
- Teams / Slack channel
- Incident bridge
- Project channel
- War room
- Status dashboard

Define:

- Primary channel
- Backup channel
- Meeting owner
- Communications owner
- Escalation path

---

# 47. Cutover Preconditions

The cutover should not begin until all preconditions are met.

Examples:

- Gate 08 passed.
- Production environment available.
- Production access validated.
- Production configuration approved.
- Integrations ready.
- Telephony ready.
- Data ready.
- Support ready.
- Training ready.
- Communications sent.
- Change approved.
- Rollback plan approved.
- Cutover team available.
- Vendor support available where required.

---

# 48. Cutover Sequence

A generic sequence is:

```text
Change Approval
       ↓
Cutover Team Assemble
       ↓
Pre-Cutover Validation
       ↓
Production Backup / Baseline
       ↓
Data Freeze
       ↓
Production Configuration
       ↓
Integration Activation
       ↓
Telephony / Number Activation
       ↓
Data Migration
       ↓
Configuration Validation
       ↓
Technical Smoke Test
       ↓
Business Validation
       ↓
Go-Live Decision
       ↓
Business Release
       ↓
Hypercare
```

The actual sequence must be project-specific.

---

# 49. Production Smoke Testing

Immediately after production deployment, execute smoke tests.

Minimum scenarios should include:

- Login
- Authentication
- Inbound call
- Outbound call
- IVR
- Routing
- Queue
- Agent interaction
- Transfer
- Hold
- Wrap-up
- Recording
- CRM
- Data Action
- Reporting
- Digital channel where applicable

---

# 50. Business Validation

Technical validation must be followed by business validation.

Business representatives should validate:

- Customer journey
- Agent journey
- Supervisor journey
- Critical business processes
- Reporting
- Customer experience
- Operational processes

---

# 51. Go-Live Decision

Define formal go-live decision criteria.

The decision should consider:

- Smoke test results
- Critical business journey results
- Integration results
- Telephony results
- Data migration results
- Open defects
- Known risks
- Business readiness
- Support readiness

Possible decisions:

```text
GO
GO WITH CONDITIONS
HOLD
ROLLBACK
```

---

# 52. Go / No-Go Governance

Establish formal decision authority.

## Required Participants

- Business owner
- Project manager
- Technical lead
- Solution architect
- Genesys lead
- Operations lead
- Support lead
- Security lead where applicable
- Customer project owner

The final decision must be documented.

---

# 53. Rollback Strategy

Define rollback before production deployment.

Rollback should address:

- Configuration
- Integrations
- Telephony
- Numbers
- Data
- Routing
- Customer communications
- Agent communications

## Rollback Trigger Examples

- Critical customer journey failure
- Critical integration failure
- Major telephony failure
- Security issue
- Data corruption
- Severe production instability
- Unacceptable business impact

---

# 54. Rollback Runbook

Document:

1. Rollback trigger.
2. Decision authority.
3. Communication.
4. Configuration rollback.
5. Integration rollback.
6. Telephony rollback.
7. Data rollback.
8. Customer communication.
9. Agent communication.
10. Validation.
11. Incident management.
12. Recovery.
13. Post-rollback review.

---

# 55. Rollback Decision Window

Define a time or event-based decision window.

Examples:

- Before business release
- During technical validation
- During initial customer traffic
- During first operational hour

The decision window should be explicit.

---

# 56. Business Continuity

Define business continuity procedures.

Consider:

- Genesys Cloud unavailable
- Telephony unavailable
- CRM unavailable
- Integration unavailable
- Identity unavailable
- Network unavailable
- Agent workstation issues
- Digital channel outage

Define manual or alternate processes where appropriate.

---

# 57. Disaster Recovery Considerations

Genesys Cloud is a SaaS platform, but the complete customer service solution contains dependencies outside Genesys Cloud.

Assess:

- Identity provider
- CRM
- Network
- Telephony
- Carrier
- Integration middleware
- APIs
- Data platforms
- Reporting
- Workforce systems
- Quality systems

The DR strategy must therefore consider the **end-to-end service**, not only the Genesys Cloud platform.

---

# 58. Recovery Procedures

Document recovery procedures for critical dependencies.

For each dependency define:

- Failure condition
- Detection
- Owner
- Immediate response
- Workaround
- Recovery
- Validation
- Escalation
- Business communication

---

# 59. Training Strategy

Define training by user population.

Potential groups:

- Agents
- Supervisors
- Team leaders
- Administrators
- Reporting users
- WFM users
- QM users
- IT support
- Service desk
- Integration support
- Security teams
- Business stakeholders

---

# 60. Agent Training

Training should cover the actual production workflow.

Potential topics:

- Login
- Presence
- Queue selection
- Accepting interactions
- Customer information
- Scripts
- Hold
- Transfer
- Consult
- Conference
- Disposition
- Wrap-up
- Callback
- Digital channels
- Email
- Troubleshooting
- Escalation

---

# 61. Supervisor Training

Potential topics:

- Queue monitoring
- Agent status
- Real-time views
- Coaching
- Whisper
- Barge
- Performance monitoring
- Reporting
- Quality
- WFM
- Escalation
- Incident handling

---

# 62. Administrator Training

Potential topics:

- User administration
- Roles
- Permissions
- Queues
- Skills
- Routing
- Architect
- Telephony
- Integrations
- Data Actions
- Data Tables
- Reporting
- Recording
- WFM
- QM
- Audit
- Troubleshooting

---

# 63. Support Team Training

Support teams should understand:

- Architecture
- Common incidents
- Monitoring
- Troubleshooting
- Escalation
- Support tools
- Incident categorisation
- Vendor escalation
- Known issues
- Workarounds

---

# 64. Knowledge Transfer

Conduct structured knowledge transfer from implementation team to BAU teams.

## Knowledge Transfer Topics

- Solution architecture
- Configuration
- Integrations
- Telephony
- Security
- Administration
- Reporting
- Monitoring
- Troubleshooting
- Incident management
- Change management
- Deployment
- Rollback

---

# 65. Knowledge Transfer Evidence

Capture:

- Session
- Date
- Presenter
- Audience
- Topics
- Attendance
- Recording where permitted
- Documentation reference
- Outstanding questions
- Follow-up actions

---

# 66. Operational Runbooks

Critical runbooks should be complete before go-live.

Potential runbooks:

- User provisioning
- User deprovisioning
- Queue changes
- Skill changes
- Routing changes
- Architect deployment
- Integration failure
- CRM failure
- Telephony failure
- Recording retrieval
- Reporting issue
- Authentication failure
- Major incident
- Rollback
- Production deployment

---

# 67. Go-Live Communications

Prepare communication plans.

## Audiences

- Executives
- Business stakeholders
- Agents
- Supervisors
- Service desk
- IT
- Security
- Vendors
- Customers where applicable

## Communications

Potential messages:

- Go-live announcement
- Maintenance notice
- Agent instructions
- Support information
- Known limitations
- Cutover status
- Go-live confirmation
- Incident communication
- Hypercare communication

---

# 68. Communications Approval

All customer-facing communications should have appropriate approval.

Track:

- Communication
- Audience
- Owner
- Approval
- Planned date
- Delivery method
- Status

---

# 69. Hypercare Strategy

Define the hypercare model before go-live.

## Define

- Hypercare duration
- Support hours
- Staffing
- Command centre
- Incident triage
- Escalation
- Vendor support
- Reporting
- Daily status
- Exit criteria

---

# 70. Hypercare Staffing

Potential resources:

- Project manager
- Genesys Cloud engineer
- Solution architect
- Integration engineer
- Telephony engineer
- IAM engineer
- Data engineer
- Reporting specialist
- WFM specialist
- QM specialist
- Customer technical team
- Business SMEs
- Service desk

---

# 71. Hypercare Monitoring

Track:

- Call volume
- Abandonment
- Service level
- Queue performance
- Agent issues
- Integration errors
- Telephony issues
- CRM issues
- Digital issues
- Recording issues
- Reporting issues
- Security issues
- User support volume

---

# 72. Hypercare Exit Criteria

Define objective exit criteria.

Potential criteria:

- Critical defects resolved
- No major incidents
- Incident volume stabilised
- Support team operating independently
- Monitoring operational
- Reporting stable
- Integrations stable
- Business acceptance confirmed
- Outstanding issues transferred to BAU

---

# 73. Production Readiness Checklist

Create a consolidated readiness checklist.

| Area | Requirement | Owner | Status | Evidence |
|---|---|---|---|---|
| Testing | Gate 08 passed | Test Lead | TBD | TBD |
| Configuration | Production baseline approved | Technical Lead | TBD | TBD |
| Telephony | Numbers ready | Telephony Lead | TBD | TBD |
| Integration | Production integrations ready | Integration Lead | TBD | TBD |
| Security | Security approval | Security Lead | TBD | TBD |
| Training | Agent training complete | Training Lead | TBD | TBD |
| Support | Service desk ready | Support Lead | TBD | TBD |
| Cutover | Runbook approved | Cutover Lead | TBD | TBD |
| Rollback | Rollback approved | Technical Lead | TBD | TBD |
| Business | Go-live approval | Business Owner | TBD | TBD |

---

# 74. Production Readiness Scorecard

Assess readiness across major domains.

## Domains

- Solution
- Configuration
- Testing
- Integration
- Telephony
- Data
- Security
- Operations
- Support
- Training
- Documentation
- Business
- Cutover
- Rollback
- Hypercare

Each should be rated:

- Green
- Amber
- Red

No unresolved Red item should proceed without formal executive approval.

---

# 75. Cutover Dependency Matrix

Create a dependency matrix.

| Task | Dependency | Owner | Required Before |
|---|---|---|---|
| Production configuration | Gate 08 | Technical Lead | Cutover |
| Data migration | Data approval | Data Lead | Validation |
| Number port | Carrier approval | Telephony Lead | Go-live |
| Integration activation | Credentials | Integration Lead | Smoke test |
| Agent training | Training material | Training Lead | Business release |

---

# 76. Cutover Task Sequencing

Every cutover activity should have a unique task ID.

Example:

```text
P09-CUT-001
P09-CUT-002
P09-CUT-003
```

Each task should include:

- Task
- Description
- Owner
- Dependency
- Start
- Duration
- Expected result
- Validation
- Rollback
- Critical path

---

# 77. Cutover Timeline

Create a detailed timeline.

Example:

```text
T-30 Days
    ↓
Operational Readiness
    ↓
T-14 Days
    ↓
Training / Support Readiness
    ↓
T-7 Days
    ↓
Final Validation
    ↓
T-1 Day
    ↓
Pre-Cutover Preparation
    ↓
T-0
    ↓
Production Cutover
    ↓
T+1
    ↓
Hypercare
```

The actual timeline must be project-specific.

---

# 78. T-30 Day Readiness

Where applicable:

- Confirm go-live date.
- Confirm support model.
- Confirm training plan.
- Confirm cutover team.
- Confirm vendor support.
- Confirm communications.
- Confirm production dependencies.
- Confirm migration plan.

---

# 79. T-14 Day Readiness

Where applicable:

- Complete training.
- Validate production access.
- Confirm telephony.
- Confirm integrations.
- Validate documentation.
- Confirm support roster.
- Confirm monitoring.
- Conduct cutover rehearsal.

---

# 80. T-7 Day Readiness

Complete:

- Final defect review.
- Final configuration review.
- Final data review.
- Final integration review.
- Final telephony review.
- Final security review.
- Final communications.
- Final cutover runbook review.

---

# 81. T-1 Day Readiness

Confirm:

- Change approval.
- Team availability.
- War room.
- Vendor availability.
- Backups / baselines.
- Data freeze.
- Production access.
- Monitoring.
- Communication.
- Rollback readiness.

---

# 82. Cutover Rehearsal

Where practical, conduct a cutover rehearsal.

## Validate

- Task sequencing
- Timing
- Dependencies
- Ownership
- Communication
- Data migration
- Configuration deployment
- Integration activation
- Validation
- Rollback

Capture lessons learned and update the cutover runbook.

---

# 83. Production Validation Plan

Create a formal production validation checklist.

## Technical

- Login
- Authentication
- Telephony
- Architect
- Routing
- Queues
- Integrations
- CRM
- Recording
- Reporting

## Business

- Customer journey
- Agent journey
- Supervisor journey
- Critical business process
- Customer experience

---

# 84. Production Validation Evidence

Capture:

- Test ID
- Time
- Tester
- Scenario
- Expected
- Actual
- Result
- Evidence
- Defect

Production validation evidence becomes part of the go-live record.

---

# 85. Go-Live Governance

Define the governance structure for the go-live period.

## Required

- Decision authority
- Escalation path
- Incident process
- Communication process
- Technical lead
- Business lead
- Support lead
- Vendor escalation
- Go/no-go criteria

---

# 86. Final Readiness Review

Conduct a formal final readiness review.

Review:

### Technical

- Platform
- Configuration
- Integrations
- Telephony
- Data
- Security

### Functional

- Voice
- Digital
- Routing
- Agent
- Supervisor
- Reporting
- WFM
- QM

### Operational

- Support
- Monitoring
- Incident management
- Change management
- Documentation
- Knowledge transfer

### Business

- Training
- Communications
- Business acceptance
- Staffing

### Cutover

- Runbook
- Migration
- Rollback
- Communications
- Command centre

---

# 87. Final Readiness Decision

The final readiness meeting should produce one of:

```text
GO
GO WITH CONDITIONS
HOLD
NO-GO
```

Any **GO WITH CONDITIONS** decision must have:

- Condition
- Owner
- Due date
- Risk
- Business acceptance

---

# 88. Phase 09 Deliverables

The following deliverables should be produced where applicable:

1. Operational readiness assessment
2. Service ownership model
3. Support model
4. RACI
5. Incident management procedure
6. Major incident procedure
7. Problem management procedure
8. Change management procedure
9. User lifecycle procedure
10. Security operations procedure
11. Monitoring strategy
12. Alerting configuration
13. Integration support model
14. Telephony support model
15. Reporting support model
16. Recording support model
17. WFM support model
18. QM support model
19. Digital operations model
20. Knowledge base
21. Administration SOPs
22. Support runbooks
23. Architecture baseline
24. Production configuration baseline
25. Training plan
26. Training materials
27. Training completion records
28. Knowledge transfer records
29. Business continuity plan
30. DR considerations
31. Data migration plan
32. Production migration plan
33. Cutover strategy
34. Cutover runbook
35. Cutover dependency matrix
36. Cutover schedule
37. Rollback strategy
38. Rollback runbook
39. Communications plan
40. Go-live communications
41. Hypercare plan
42. Hypercare staffing plan
43. Production validation checklist
44. Production readiness checklist
45. Readiness scorecard
46. Final go/no-go assessment
47. Phase 09 acceptance record

---

# 89. Phase Dependencies

## Inputs

Phase 09 depends on:

**Phase 03 — Requirements & Solution Definition**

**Phase 04 — Solution Architecture & Detailed Design**

**Phase 05 — Platform Foundation & Environment Build**

**Phase 06 — Feature Configuration & Solution Build**

**Phase 07 — Integration & Data Migration**

**Phase 08 — Testing & Validation**

## Outputs

Phase 09 provides the production-ready service for:

**Phase 10 — Production Deployment & Go-Live**

---

# 90. Phase Dependency Model

```text
Validated Solution
        ↓
Operational Readiness
        ↓
Support Readiness
        ↓
Training
        ↓
Documentation
        ↓
Production Configuration
        ↓
Cutover Preparation
        ↓
Rollback Preparation
        ↓
Go-Live Readiness
        ↓
Gate 09
        ↓
Production Deployment
```

---

# 91. Recommended Task Decomposition

The master deployment spreadsheet should break Phase 09 into individual tasks.

Recommended columns:

| Column | Description |
|---|---|
| Task ID | Unique task identifier |
| Phase | Phase number |
| Workstream | Phase 09 workstream |
| Parent Task | Parent activity |
| Task | Individual activity |
| Description | Detailed task description |
| Type | Required / Conditional / Optional |
| Dependency | Predecessor |
| Role | Primary responsible role |
| Customer Responsibility | Customer-owned activity |
| Environment | DEV / SIT / UAT / PROD |
| Effort | Estimated hours |
| Duration | Elapsed duration |
| Critical Path | Yes / No |
| Deliverable | Output |
| Acceptance Criteria | Completion condition |
| Status | Planned / In Progress / Complete |
| Notes | Additional information |

---

# 92. Recommended Phase 09 Task ID Structure

Use:

```text
P09-001
P09-002
P09-003
```

For workstream-level decomposition:

```text
P09-OPS-001
P09-OPS-002

P09-SUP-001
P09-SUP-002

P09-SEC-001
P09-SEC-002

P09-MON-001
P09-MON-002

P09-TRAIN-001
P09-TRAIN-002

P09-CUT-001
P09-CUT-002

P09-MIG-001
P09-MIG-002

P09-ROLL-001
P09-ROLL-002

P09-HC-001
P09-HC-002

P09-GOLIVE-001
P09-GOLIVE-002
```

---

# 93. Effort Estimation Considerations

Phase 09 effort varies substantially based on deployment complexity.

Estimate separately for:

- Operational readiness planning
- Support model
- Service management integration
- Administration procedures
- Security operations
- Monitoring
- Integration support
- Telephony support
- Reporting support
- Documentation
- Training
- Knowledge transfer
- Business continuity
- Disaster recovery
- Data migration preparation
- Production configuration
- Cutover planning
- Cutover rehearsal
- Rollback planning
- Communications
- Hypercare preparation
- Go-live governance

Do not estimate Phase 09 as one aggregate activity.

---

# 94. Effort Drivers

Major effort drivers include:

- Number of users
- Number of business units
- Number of queues
- Number of skills
- Number of Architect flows
- Number of integrations
- Number of external systems
- Telephony complexity
- Number of locations
- Number of countries
- Digital channels
- WFM
- QM
- Recording
- Reporting
- Data migration
- Security requirements
- Compliance requirements
- Customer ITSM requirements
- Training population
- Support model complexity
- Cutover complexity
- Phased rollout
- Business continuity requirements

---

# 95. Critical Path Considerations

Potential Phase 09 critical-path activities include:

- Production environment readiness
- Production integration readiness
- Number porting
- Data migration
- Security approval
- Change approval
- Training completion
- Support readiness
- Cutover rehearsal
- Production access
- Business approval
- Vendor availability

The project schedule should identify these explicitly.

---

# 96. Required vs Conditional Activities

The master methodology must distinguish between required and conditional activities.

## Generally Required

- Operational readiness
- Support model
- Production configuration baseline
- Cutover strategy
- Cutover runbook
- Rollback strategy
- Production validation
- Go/no-go governance
- Hypercare planning
- Business readiness
- Support readiness

## Conditional

- Data migration
- Number porting
- WFM
- QM
- Digital channels
- DR testing
- Performance testing
- Cutover rehearsal
- Parallel operation
- Phased rollout

## Optional

- Extended automation
- Additional simulation
- Additional operational reporting
- Additional rehearsal cycles

---

# 97. Operational Readiness Definition of Done

Operational readiness is complete when:

- Service ownership is confirmed.
- Support ownership is confirmed.
- L1/L2/L3 support model is defined.
- Incident process is defined.
- Problem process is defined.
- Change process is defined.
- Access process is defined.
- Administration procedures are documented.
- Monitoring is operational.
- Alerting is operational.
- Integration support is defined.
- Telephony support is defined.
- Reporting support is defined.
- Recording support is defined.
- Security operations are defined.
- Documentation is complete.
- Knowledge transfer is complete.
- Training is complete or formally scheduled.
- Business continuity is defined.
- DR considerations are documented.
- Production configuration is baselined.

---

# 98. Cutover Definition of Done

Cutover preparation is complete when:

- Cutover strategy is approved.
- Cutover runbook is complete.
- Cutover tasks are sequenced.
- Dependencies are documented.
- Owners are assigned.
- Cutover timeline is approved.
- Production access is validated.
- Production integrations are ready.
- Telephony is ready.
- Data migration is ready.
- Rollback plan is approved.
- Rollback tasks are defined.
- Cutover rehearsal is complete where required.
- Communications are approved.
- Command centre is defined.
- Go/no-go criteria are approved.
- Hypercare is ready.

---

# 99. Training Definition of Done

Training readiness is complete when:

- Training audiences are identified.
- Training materials are complete.
- Agent training is complete or scheduled.
- Supervisor training is complete or scheduled.
- Administrator training is complete or scheduled.
- Support training is complete or scheduled.
- Training attendance is recorded.
- Training gaps are documented.
- Production support documentation is available.

---

# 100. Phase 09 Definition of Done

Phase 09 is complete when:

- Operational readiness assessment is complete.
- Service ownership is established.
- Support model is approved.
- ITSM integration is ready.
- Incident management is defined.
- Problem management is defined.
- Change management is defined.
- User lifecycle is defined.
- Security operations are ready.
- Monitoring is ready.
- Alerting is ready.
- Integration support is ready.
- Telephony support is ready.
- Reporting support is ready.
- Recording support is ready.
- WFM support is ready where applicable.
- QM support is ready where applicable.
- Digital operations are ready where applicable.
- Documentation is complete.
- Knowledge transfer is complete.
- Training is complete or approved.
- Business continuity is documented.
- DR considerations are documented.
- Production configuration is baselined.
- Production access is validated.
- Production integrations are ready.
- Data migration is ready.
- Cutover strategy is approved.
- Cutover runbook is complete.
- Cutover dependencies are documented.
- Rollback strategy is approved.
- Communications are approved.
- Hypercare is ready.
- Go-live governance is established.
- Production validation is defined.
- Final readiness review is complete.
- Go/no-go criteria are approved.
- Gate 09 is passed.

---

# 101. Phase 09 Risks

Potential risks include:

### Operational Ownership Not Defined

The service may reach production without clear accountability.

### Inadequate Support

The service desk may not be prepared to handle incidents.

### Insufficient Training

Agents or administrators may not be ready.

### Documentation Gaps

Operational teams may lack the information needed to support the platform.

### Production Configuration Drift

Production may differ from the tested baseline.

### Integration Readiness

External systems may not be ready for production activation.

### Telephony Dependencies

Carrier, number-porting or network dependencies may delay go-live.

### Data Migration Failure

Production data may not migrate correctly.

### Rollback Complexity

The implementation may be difficult to reverse after activation.

### Inadequate Monitoring

Production incidents may not be detected quickly.

### Incomplete Business Readiness

Business teams may not be prepared for the operational change.

### Cutover Duration

Cutover may exceed the approved window.

### Vendor Availability

Required vendor resources may not be available during cutover.

### Uncontrolled Change

Late configuration changes may invalidate testing.

---

# 102. Risk Mitigation

For each material risk:

1. Identify risk.
2. Assess probability.
3. Assess impact.
4. Identify mitigation.
5. Assign owner.
6. Define trigger.
7. Define contingency.
8. Track to closure.

---

# 103. Phase Governance

Phase 09 should have formal governance meetings.

Recommended meetings:

- Operational readiness review
- Support readiness review
- Security readiness review
- Training readiness review
- Cutover planning workshop
- Cutover rehearsal
- Data migration review
- Production readiness review
- Go/no-go review
- Phase gate review

---

# 104. Phase Reporting

Track Phase 09 progress using:

- Operational readiness %
- Documentation completion %
- Training completion %
- Support readiness %
- Production readiness %
- Cutover task completion %
- Data migration readiness %
- Defect status
- Risk status
- Dependency status
- Go-live readiness score

---

# 105. Final Production Readiness Dashboard

The project should maintain a single readiness dashboard.

Example:

```text
                 PRODUCTION READINESS

Solution              [ GREEN ]
Testing               [ GREEN ]
Configuration         [ GREEN ]
Integrations          [ GREEN ]
Telephony             [ AMBER ]
Data                  [ GREEN ]
Security              [ GREEN ]
Operations            [ GREEN ]
Support               [ GREEN ]
Training              [ GREEN ]
Documentation         [ GREEN ]
Cutover               [ GREEN ]
Rollback              [ GREEN ]
Business Readiness    [ GREEN ]
Hypercare             [ GREEN ]
```

Any Amber or Red item must have an owner and documented resolution path.

---

# 106. Phase Gate — Gate 09: Operational Readiness & Cutover Preparation Complete

## Gate Objective

Confirm that the validated Genesys Cloud solution is operationally, technically and organisationally ready for production deployment.

## Entry Criteria

- Gate 08 passed.
- UAT completed.
- Critical defects closed.
- Business acceptance obtained.
- Production target identified.

## Exit Criteria

The following must be complete or formally accepted:

### Solution

- Production configuration baselined.
- Production architecture confirmed.
- Production integrations ready.
- Production telephony ready.
- Production data ready.

### Operations

- Service owner confirmed.
- Support model approved.
- Service desk ready.
- Administration procedures complete.
- Monitoring ready.
- Alerting ready.
- Incident procedures ready.
- Change procedures ready.

### Security

- Production access validated.
- Roles validated.
- Privileged access validated.
- Security requirements accepted.
- Compliance requirements accepted where applicable.

### People

- Agents trained.
- Supervisors trained.
- Administrators trained.
- Support teams trained.
- Knowledge transfer completed.

### Documentation

- Architecture documentation complete.
- Configuration documentation complete.
- Support documentation complete.
- Runbooks complete.
- Operational procedures complete.

### Cutover

- Cutover strategy approved.
- Cutover runbook approved.
- Cutover timeline approved.
- Dependencies documented.
- Owners assigned.
- Rollback approved.
- Communications approved.
- Command centre established.
- Production validation defined.

### Business

- Business readiness confirmed.
- Go-live communications approved.
- Business stakeholders understand cutover.
- Go/no-go authority confirmed.

### Hypercare

- Hypercare model approved.
- Hypercare resources assigned.
- Hypercare monitoring defined.
- Hypercare exit criteria defined.

---

# 107. Gate Decision

The Phase 09 gate must result in one of:

```text
PASS
```

The solution is ready for production deployment.

```text
PASS WITH CONDITIONS
```

The solution may proceed with documented, accepted conditions.

```text
HOLD
```

One or more material readiness activities remain incomplete.

```text
FAIL
```

The solution is not ready for production deployment.

---

# 108. Phase 09 Outputs to Phase 10

Phase 09 provides Phase 10 with:

```text
Validated Solution
       +
Operationally Ready Service
       +
Trained Users
       +
Ready Support Organisation
       +
Production Configuration
       +
Production Integrations
       +
Migration Plan
       +
Cutover Runbook
       +
Rollback Plan
       +
Go-Live Communications
       +
Hypercare Model
       ↓
Phase 10 — Production Deployment & Go-Live
```

---

# 109. Layer 1 Position

| Phase | Status |
|---|---|
| **01 — Project Initiation & Mobilisation** | Baseline |
| **02 — Discovery & Current-State Assessment** | Baseline |
| **03 — Requirements & Solution Definition** | Baseline |
| **04 — Solution Architecture & Detailed Design** | Baseline |
| **05 — Platform Foundation & Environment Build** | Baseline |
| **06 — Feature Configuration & Solution Build** | Defined |
| **07 — Integration & Data Migration** | Defined |
| **08 — Testing & Validation** | Defined |
| **09 — Operational Readiness & Cutover Preparation** | **Defined** |
| 10 — Production Deployment & Go-Live | Next |
| 11 — Hypercare & Stabilisation | Pending |
| 12 — BAU Handover & Project Closure | Pending |

---

# 110. Phase 09 Summary

Phase 09 is the bridge between a technically validated solution and a production-ready service.

The project must demonstrate that:

```text
Tested Solution
      ↓
Operationally Ready
      ↓
Supported
      ↓
Documented
      ↓
Trained
      ↓
Monitored
      ↓
Secure
      ↓
Cutover Ready
      ↓
Rollback Ready
      ↓
Business Ready
      ↓
Go-Live Ready
```

The project should not proceed to production simply because testing has passed.

It must also demonstrate that the organisation is capable of operating the new service.

The key outcome of Phase 09 is therefore:

**A production-ready Genesys Cloud service with an approved cutover, rollback, support and hypercare strategy.**

The formal completion point is:

**Gate 09 — Operational Readiness & Cutover Preparation Complete**

---

# Phase Completion

**Phase:** 09 — Operational Readiness & Cutover Preparation

**Previous Phase:** 08 — Testing & Validation

**Next Phase:** 10 — Production Deployment & Go-Live

**Phase Gate:** Gate 09 — Operational Readiness & Cutover Preparation Complete

**Primary Outcome:** Production-ready Genesys Cloud solution with approved operational model, support model, training, documentation, cutover plan, migration plan, rollback strategy and hypercare model.
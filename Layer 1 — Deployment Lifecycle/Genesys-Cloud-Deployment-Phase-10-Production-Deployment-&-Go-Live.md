# Phase 10 — Production Deployment & Go-Live

## 1. Purpose

Phase 10 executes the controlled transition of the validated Genesys Cloud solution into production and formally releases the service to the business.

This phase begins only after:

- Phase 09 — Operational Readiness & Cutover Preparation has passed.
- Gate 09 has been approved.
- Production readiness has been confirmed.
- The cutover plan has been approved.
- The rollback strategy has been approved.
- Required production dependencies are available.
- Required business, technical and operational resources are available.

Phase 10 is the controlled execution phase of the deployment.

The objective is not simply to deploy configuration into the production organisation.

The objective is to:

- Deploy the approved production configuration.
- Activate production integrations.
- Activate telephony and routing.
- Execute required data migration.
- Validate production functionality.
- Validate critical customer journeys.
- Validate agent and supervisor operation.
- Confirm business acceptance.
- Manage the go/no-go decision.
- Execute rollback if required.
- Transition the service into hypercare.
- Establish formal production operation.

The output of Phase 10 is a **live Genesys Cloud service operating in production and formally transitioned into the Phase 11 hypercare model**.

---

# 2. Phase Objective

By the end of Phase 10:

- The approved production configuration is deployed.
- Production configuration matches the approved baseline.
- Production integrations are active.
- Production telephony is active.
- Production numbers are active where applicable.
- Production routing is active.
- Architect flows are active.
- Users can authenticate.
- Agents can operate.
- Supervisors can operate.
- Queues are operational.
- Skills and languages are operational.
- Digital channels are operational where applicable.
- CRM integration is operational where applicable.
- Data Actions are operational where applicable.
- Recording is operational where applicable.
- Reporting is operational.
- WFM is operational where applicable.
- QM is operational where applicable.
- Security controls are active.
- Monitoring is active.
- Business validation is complete.
- Go-live decision is formally recorded.
- Customer and business communications are issued.
- Production support is active.
- Hypercare is activated.
- Any remaining defects are transferred into the agreed support process.
- Phase 10 Gate is passed.

---

# 3. Phase Position

The deployment lifecycle is:

```text
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

Phase 10 is the controlled production activation point.

---

# 4. Phase Entry Criteria

Phase 10 must not commence until the following conditions have been met or formally accepted.

## Required

1. Gate 09 has passed.
2. Production readiness has been approved.
3. Production configuration baseline is approved.
4. Cutover runbook is approved.
5. Rollback strategy is approved.
6. Go/no-go criteria are approved.
7. Production change is approved.
8. Required production access is available.
9. Required integration credentials are available.
10. Required network connectivity is available.
11. Required firewall changes are complete.
12. Required DNS changes are complete.
13. Required certificates are available.
14. Required telephony changes are ready.
15. Number porting is complete or scheduled.
16. Data migration is ready.
17. Business stakeholders are available.
18. Technical resources are available.
19. Support resources are available.
20. Vendor resources are available where required.
21. Communications have been approved.
22. Hypercare resources are confirmed.
23. Rollback resources are confirmed.

Any exception must be documented and formally accepted.

---

# 5. Phase Workstreams

The master deployment methodology should structure Phase 10 into the following workstreams:

### 10.01 Go-Live Command Centre Activation
### 10.02 Final Pre-Cutover Validation
### 10.03 Production Baseline
### 10.04 Production Configuration Deployment
### 10.05 Identity & Access Activation
### 10.06 User Provisioning
### 10.07 Queue & Routing Activation
### 10.08 Architect Activation
### 10.09 Telephony Activation
### 10.10 Number Porting / Number Activation
### 10.11 Digital Channel Activation
### 10.12 Integration Activation
### 10.13 Data Migration
### 10.14 Data Validation
### 10.15 Recording Activation
### 10.16 Reporting Activation
### 10.17 WFM Activation
### 10.18 QM Activation
### 10.19 Security Validation
### 10.20 Monitoring & Alerting Validation
### 10.21 Technical Smoke Testing
### 10.22 Business Validation
### 10.23 Go / No-Go Decision
### 10.24 Production Release
### 10.25 Go-Live Communications
### 10.26 Production Incident Management
### 10.27 Rollback Execution
### 10.28 Hypercare Activation
### 10.29 Production Handover to Hypercare
### 10.30 Go-Live Closure
### 10.31 Phase Gate Preparation

Not every workstream applies to every project.

Each task must be classified as:

- Required
- Conditional
- Optional
- Not Applicable

---

# 6. Production Deployment Principles

Production deployment must follow these principles:

1. Deploy only approved configuration.
2. Maintain configuration traceability.
3. Follow the approved cutover sequence.
4. Do not introduce unapproved scope.
5. Record every production change.
6. Validate each major deployment stage.
7. Stop when defined go/no-go criteria are breached.
8. Maintain clear decision authority.
9. Maintain an active rollback capability until the rollback window expires.
10. Maintain continuous communications.
11. Capture production evidence.
12. Maintain a formal deployment record.

---

# 7. Go-Live Command Centre

Establish the command centre before production activities begin.

## Participants

Potential participants include:

- Cutover Manager
- Project Manager
- Genesys Cloud Lead
- Solution Architect
- Technical Lead
- Integration Lead
- Telephony Lead
- IAM Lead
- Security Lead
- Data Migration Lead
- Test Lead
- Business Lead
- Service Desk Lead
- Operations Lead
- WFM Lead
- QM Lead
- Reporting Lead
- Vendor / Genesys Support
- Customer Technical Lead

Only applicable roles need to participate.

---

# 8. Command Centre Responsibilities

The command centre is responsible for:

- Coordinating deployment.
- Tracking task completion.
- Managing dependencies.
- Managing incidents.
- Managing decisions.
- Managing communications.
- Coordinating technical teams.
- Coordinating business validation.
- Managing escalation.
- Managing rollback decisions.
- Recording the deployment timeline.

---

# 9. Cutover Communications

Before commencing production deployment:

1. Confirm cutover team attendance.
2. Confirm business stakeholders.
3. Confirm support team.
4. Confirm vendor availability.
5. Confirm communication channels.
6. Confirm escalation channels.
7. Confirm change reference.
8. Confirm start time.
9. Confirm expected completion.
10. Confirm rollback deadline.

---

# 10. Cutover Start Confirmation

The Cutover Manager should formally announce:

```text
CUTOVER STARTED
```

Record:

- Date
- Time
- Time zone
- Change reference
- Participants
- Starting production state
- Initial status

---

# 11. Final Pre-Cutover Validation

Perform a final readiness check immediately before production activity.

## Validate

- Change approval.
- Gate 09 approval.
- Production access.
- Team availability.
- Vendor availability.
- Production environment.
- Production credentials.
- Network.
- DNS.
- Certificates.
- Telephony.
- Integrations.
- Data migration.
- Monitoring.
- Support.
- Communications.
- Rollback.

---

# 12. Final Go / No-Go Before Deployment

The Cutover Manager should confirm:

```text
All critical prerequisites met?
        ↓
YES → Continue
NO  → Hold / Resolve / Escalate
```

The decision must be recorded.

---

# 13. Production Baseline

Before making production changes, capture the production baseline.

Where applicable capture:

- Organisation configuration.
- Divisions.
- Users.
- Roles.
- Permissions.
- Queues.
- Skills.
- Languages.
- Architect flows.
- Routing configuration.
- Schedules.
- Business hours.
- Holiday schedules.
- Telephony.
- Numbers.
- Integrations.
- Data Actions.
- Data Tables.
- Recording configuration.
- WFM.
- QM.
- Reporting.
- Digital configuration.

---

# 14. Production Backup / Export

Where supported and appropriate:

1. Export relevant configuration.
2. Capture current production state.
3. Capture configuration version.
4. Capture deployment version.
5. Store deployment evidence.
6. Confirm recovery artefacts.
7. Confirm rollback requirements.

Where Terraform or other Infrastructure as Code is used, ensure the approved source-control revision is recorded.

---

# 15. Production Configuration Version

Record the exact production release.

Example:

```text
Release: GC-2026.10.01
Repository Commit: <commit>
Terraform Version: <version>
Deployment Date: <date>
Deployment Owner: <owner>
Change Reference: <reference>
```

The production state must be traceable to the approved release.

---

# 16. Configuration Promotion

Promote approved configuration into production.

Potential mechanisms include:

- Manual configuration.
- Genesys Cloud configuration migration.
- API.
- Terraform.
- CI/CD.
- Deployment scripts.
- Approved configuration packages.

The selected method must match the approved deployment architecture.

---

# 17. Infrastructure as Code Deployment

Where Terraform is used:

1. Confirm source branch.
2. Confirm approved commit.
3. Confirm production variables.
4. Confirm credentials.
5. Confirm backend.
6. Confirm state.
7. Run validation.
8. Run plan.
9. Review plan.
10. Obtain deployment approval.
11. Apply configuration.
12. Capture output.
13. Validate state.
14. Record deployment evidence.

Do not apply unreviewed production changes.

---

# 18. Genesys Cloud Organisation Configuration

Validate production organisation-level configuration.

Potential configuration includes:

- Organisation settings.
- Default language.
- Default time zone.
- Divisions.
- Roles.
- Permissions.
- Authentication.
- Security settings.
- Recording policies.
- Data retention.
- Analytics settings.

---

# 19. Division Activation

Validate:

- Divisions.
- Division membership.
- Object ownership.
- Administrative boundaries.
- Access controls.
- Reporting boundaries.

Confirm users have access only to the required divisions.

---

# 20. Role & Permission Activation

Validate production roles and permissions.

## Confirm

- Administrator roles.
- Supervisor roles.
- Agent roles.
- Reporting roles.
- WFM roles.
- QM roles.
- Support roles.
- Custom roles.
- Division restrictions.

Avoid granting broad administrative access unless required.

---

# 21. Identity Activation

Activate and validate production identity integration.

Potential capabilities:

- SSO.
- SAML.
- OpenID Connect.
- MFA.
- Identity provider integration.
- User provisioning.
- SCIM where applicable.

---

# 22. User Provisioning

Provision production users.

Potential populations:

- Agents.
- Supervisors.
- Team leaders.
- Administrators.
- WFM users.
- QM users.
- Reporting users.
- Support users.

Validate:

- Username.
- Email.
- Division.
- Role.
- Queue.
- Skill.
- Language.
- Location.
- Phone.
- Manager.
- Authentication.

---

# 23. User Provisioning Validation

Validate representative users from each population.

At minimum test:

- Agent login.
- Supervisor login.
- Administrator login.
- Reporting access.
- WFM access where applicable.
- QM access where applicable.

---

# 24. Queue Activation

Validate production queues.

For each queue confirm:

- Name.
- Division.
- Members.
- Skills.
- Languages.
- Routing method.
- Evaluation method.
- Wrap-up configuration.
- Service level.
- Queue settings.
- Voice routing.
- Digital routing where applicable.

---

# 25. Skills & Languages

Validate:

- Skill names.
- Skill assignments.
- Skill proficiency.
- Language assignments.
- Language proficiency.
- Queue relationships.
- Routing rules.

---

# 26. Routing Activation

Validate production routing configuration.

Potential components:

- ACD routing.
- Bullseye routing.
- Skills-based routing.
- Preferred agents.
- Queue priority.
- Utilisation.
- In-queue flows.
- Transfer routing.
- Callback routing.
- Digital routing.

---

# 27. Architect Activation

Activate approved production Architect flows.

Potential flows include:

- Inbound call flows.
- In-queue flows.
- Outbound flows.
- Secure call flows.
- Customer service flows.
- Digital flows.
- Bot flows.
- Survey flows.

---

# 28. Architect Production Validation

Validate:

- Flow published.
- Version correct.
- Dependencies available.
- Data Actions available.
- Data Tables available.
- Prompts available.
- Queues available.
- Skills available.
- Schedules available.
- Business hours available.
- Error handling available.

---

# 29. Schedule Activation

Validate:

- Business hours.
- Holiday schedules.
- Emergency closures.
- Time zones.
- Queue schedules.
- Architect schedule evaluation.

Confirm production dates are correct.

---

# 30. Data Tables

Where Data Tables are used:

1. Deploy production Data Tables.
2. Validate schema.
3. Validate keys.
4. Load production values.
5. Validate records.
6. Confirm permissions.
7. Validate Architect references.
8. Validate Data Action dependencies.

---

# 31. Data Actions

Where Data Actions are used:

1. Deploy production Data Actions.
2. Configure credentials.
3. Configure endpoints.
4. Validate contracts.
5. Validate request mapping.
6. Validate response mapping.
7. Validate error handling.
8. Test authentication.
9. Test successful response.
10. Test failure response.
11. Validate Architect integration.

---

# 32. Integration Activation

Activate production integrations in dependency order.

Generic sequence:

```text
Network
    ↓
DNS
    ↓
Firewall
    ↓
Certificates
    ↓
Authentication
    ↓
Integration Endpoint
    ↓
Genesys Cloud Configuration
    ↓
Data Action / API
    ↓
Architect / Workflow
    ↓
Business Validation
```

---

# 33. Integration Dependency Validation

For each integration confirm:

- Source available.
- Destination available.
- Network available.
- Endpoint available.
- Authentication available.
- Credentials valid.
- Certificate valid.
- API permissions valid.
- Payload valid.
- Response valid.
- Timeout valid.
- Error handling valid.
- Monitoring active.

---

# 34. CRM Integration Activation

Where CRM integration is in scope:

Validate:

- User authentication.
- Embedded client.
- Screen pop.
- Customer lookup.
- Interaction creation.
- Case creation.
- Call controls.
- Disposition.
- Call logging.
- Recording link where applicable.
- CRM security.
- CRM error handling.

---

# 35. API Integration Activation

Where direct API integrations are used:

Validate:

- OAuth client.
- Client credentials.
- Permissions.
- Token acquisition.
- API endpoint.
- Rate limits.
- Error handling.
- Retry.
- Timeout.
- Logging.
- Monitoring.

---

# 36. Event / Notification Activation

Where event-driven integration is used:

Validate:

- Notification topics.
- WebSocket connections.
- Event subscriptions.
- Middleware.
- Event processing.
- Event consumers.
- Retry.
- Dead-letter handling where applicable.
- Monitoring.

---

# 37. Telephony Activation

Activate production telephony.

Potential components:

- BYOC Cloud.
- BYOC Premises.
- Genesys Cloud Voice.
- SIP.
- Edge devices.
- Phone trunks.
- Carrier services.
- DID numbers.
- Emergency calling.

Only applicable components should be activated.

---

# 38. Telephony Production Validation

Validate:

- Inbound call.
- Outbound call.
- Caller ID.
- ANI.
- DNIS.
- Transfer.
- Hold.
- Consult.
- Conference.
- Queue routing.
- Recording.
- Voicemail.
- Callback.

---

# 39. Number Activation

Where applicable:

1. Confirm porting complete.
2. Confirm carrier routing.
3. Confirm number ownership.
4. Confirm number assigned.
5. Confirm Architect routing.
6. Confirm caller ID.
7. Test inbound.
8. Test outbound.
9. Test failover.

---

# 40. Number Porting

Where porting occurs during the go-live:

Coordinate:

- Carrier.
- Genesys Cloud.
- Customer telecom.
- Cutover manager.
- Business owner.

Record:

- Porting start.
- Porting completion.
- Number ranges.
- Test results.
- Carrier confirmation.

---

# 41. Digital Channel Activation

Where applicable activate:

- Web messaging.
- Web chat.
- Email.
- SMS.
- Social messaging.
- Open messaging.
- Other supported digital channels.

Validate:

- Channel configuration.
- Routing.
- Queue.
- Agent availability.
- Customer journey.
- Authentication.
- Notifications.
- Conversation history.

---

# 42. Digital Routing Validation

Test:

- New interaction.
- Queue assignment.
- Agent assignment.
- Transfer.
- Escalation.
- Disconnect.
- Reconnect.
- Customer response.
- Agent response.
- Wrap-up.

---

# 43. Recording Activation

Validate:

- Recording enabled.
- Recording policy.
- Recording permissions.
- Recording storage.
- Recording retention.
- Pause / resume where applicable.
- Secure pause where applicable.
- Recording retrieval.

---

# 44. Recording Production Test

Execute:

1. Place test interaction.
2. Record interaction.
3. Complete interaction.
4. Locate recording.
5. Confirm playback.
6. Confirm metadata.
7. Confirm permissions.
8. Confirm retention configuration.

---

# 45. Reporting Activation

Validate:

- Real-time dashboards.
- Historical reporting.
- Scheduled reports.
- User permissions.
- Queue metrics.
- Agent metrics.
- Service level.
- Abandonment.
- AHT.
- ACW.
- Reporting time zones.

---

# 46. WFM Activation

Where WFM is in scope:

Validate:

- Business units.
- Management units.
- Agents.
- Forecasting.
- Scheduling.
- Adherence.
- Time-off.
- Intraday management.
- WFM permissions.
- WFM reporting.

---

# 47. QM Activation

Where QM is in scope:

Validate:

- Evaluation forms.
- Evaluators.
- Evaluation assignment.
- Recording access.
- Calibration.
- Coaching.
- Quality scores.
- QM reporting.

---

# 48. Knowledge Activation

Where Knowledge is in scope:

Validate:

- Knowledge bases.
- Articles.
- Categories.
- Search.
- Agent access.
- Customer access.
- Permissions.
- Versioning.
- Publishing.

---

# 49. Bot / AI Activation

Where applicable validate:

- Bot configuration.
- Bot flows.
- AI services.
- Knowledge integration.
- Intent recognition.
- Slot collection.
- Escalation.
- Agent handoff.
- Fallback.
- Monitoring.
- Analytics.

---

# 50. Workforce & Operational Activation

Confirm:

- Staffing model.
- Agent groups.
- Supervisor access.
- Queue ownership.
- WFM configuration.
- Schedules.
- Forecasts.
- Operational dashboards.

---

# 51. Security Validation

Validate production security.

## Confirm

- Authentication.
- SSO.
- MFA.
- Roles.
- Permissions.
- Divisions.
- OAuth.
- API clients.
- Service accounts.
- Certificates.
- Secrets.
- Audit logging.

---

# 52. Monitoring Activation

Validate production monitoring.

Potential monitoring:

- Platform status.
- Integration health.
- API health.
- Data Actions.
- Telephony.
- Queue metrics.
- Digital channels.
- Recording.
- Authentication.
- Middleware.

---

# 53. Alerting Validation

Execute controlled tests where appropriate.

Validate:

- Alert triggers.
- Alert severity.
- Alert destination.
- Notification.
- Escalation.
- Incident creation.
- Recovery notification.

---

# 54. Data Migration Execution

Where applicable:

1. Confirm migration approval.
2. Confirm data freeze.
3. Extract source data.
4. Validate extract.
5. Transform data.
6. Validate transformed data.
7. Load production.
8. Validate load.
9. Reconcile records.
10. Release data.
11. Record migration result.

---

# 55. Migration Validation

Validate:

- Record counts.
- Required fields.
- Relationships.
- Data integrity.
- Duplicates.
- Missing records.
- Invalid records.
- Business rules.

Record:

- Source count.
- Target count.
- Difference.
- Exceptions.
- Resolution.

---

# 56. Data Migration Reconciliation

The migration should not be considered complete until reconciliation is approved.

Example:

```text
Source Records
      ↓
Extract
      ↓
Transform
      ↓
Load
      ↓
Target Records
      ↓
Reconciliation
      ↓
Business Acceptance
```

---

# 57. Technical Smoke Testing

After production configuration is deployed, execute technical smoke tests.

Minimum applicable scenarios:

1. Login.
2. SSO.
3. Agent status.
4. Queue availability.
5. Inbound call.
6. Outbound call.
7. IVR.
8. Routing.
9. Transfer.
10. Hold.
11. Conference.
12. Wrap-up.
13. Recording.
14. CRM.
15. Data Action.
16. Reporting.
17. Digital interaction.
18. WFM.
19. QM.

---

# 58. Production Smoke Test Results

Each test must record:

| Field | Description |
|---|---|
| Test ID | Unique test |
| Scenario | Test scenario |
| Tester | Person executing |
| Time | Execution time |
| Expected | Expected result |
| Actual | Actual result |
| Result | Pass / Fail |
| Evidence | Evidence reference |
| Defect | Defect reference |

---

# 59. Critical Customer Journey Validation

Validate the highest-value business journeys.

Examples:

```text
Customer
   ↓
Inbound Number
   ↓
Architect
   ↓
Authentication
   ↓
Data Action
   ↓
Queue
   ↓
Agent
   ↓
CRM
   ↓
Recording
   ↓
Wrap-up
   ↓
Reporting
```

The actual journey must match the project solution.

---

# 60. End-to-End Voice Validation

Where voice is in scope:

Test:

- Customer call.
- DID.
- Architect.
- IVR.
- Customer lookup.
- Queue.
- Agent delivery.
- Screen pop.
- Call controls.
- Hold.
- Transfer.
- Consult.
- Conference.
- Recording.
- Wrap-up.
- CRM update.
- Reporting.

---

# 61. End-to-End Digital Validation

Where digital channels are in scope:

Test:

- Customer starts interaction.
- Channel loads.
- Authentication where applicable.
- Routing.
- Agent assignment.
- Agent response.
- Transfer.
- Escalation.
- Conversation completion.
- Wrap-up.
- Reporting.

---

# 62. Supervisor Validation

Validate supervisor functions:

- Queue monitoring.
- Agent status.
- Real-time analytics.
- Coaching.
- Whisper.
- Barge.
- Reporting.
- Quality.
- WFM.

---

# 63. Administrator Validation

Validate administrative functions:

- User administration.
- Queue administration.
- Skill administration.
- Architect.
- Routing.
- Telephony.
- Reporting.
- Recording.
- Integration configuration.
- Security administration.

---

# 64. Business Validation

Business SMEs must validate the production service.

Validate:

- Customer experience.
- Agent experience.
- Supervisor experience.
- Business processes.
- Critical journeys.
- Reporting.
- Operational outcomes.

---

# 65. Business Acceptance

Business acceptance should be explicitly recorded.

The business representative must confirm:

```text
Production solution validated
        ↓
Critical journeys successful
        ↓
Business acceptance
        ↓
Proceed to Go-Live
```

---

# 66. Defect Management During Go-Live

All defects identified during deployment must be classified.

## Severity

### Severity 1 — Critical

Business cannot operate or critical customer impact exists.

### Severity 2 — High

Major business function unavailable or materially degraded.

### Severity 3 — Medium

Workaround available.

### Severity 4 — Low

Minor issue with limited operational impact.

---

# 67. Go-Live Defect Decision

For each defect determine:

- Continue.
- Continue with workaround.
- Hold.
- Rollback.

The decision must be documented.

---

# 68. Go / No-Go Decision

The formal go-live decision should occur after technical and business validation.

Decision options:

```text
GO
GO WITH CONDITIONS
HOLD
ROLLBACK
```

---

# 69. Go Decision Criteria

A GO decision should require:

- Critical smoke tests passed.
- Critical customer journeys passed.
- Telephony passed.
- Integrations passed.
- Data migration passed.
- Business acceptance obtained.
- No unresolved Severity 1 issue.
- No unacceptable Severity 2 issue.
- Support operational.
- Monitoring operational.
- Hypercare ready.

---

# 70. GO WITH CONDITIONS

A GO WITH CONDITIONS decision may be used when:

- Minor defects remain.
- Approved workarounds exist.
- Business impact is acceptable.
- Owners are assigned.
- Target dates are defined.
- Business has accepted the risk.

Every condition must be documented.

---

# 71. HOLD Decision

Use HOLD when:

- Critical validation remains incomplete.
- Required dependency is unavailable.
- Business validation is incomplete.
- Support is not ready.
- Monitoring is not ready.
- Security issue remains unresolved.
- Required technical resource is unavailable.

---

# 72. Rollback Decision

Rollback should occur where defined thresholds are exceeded.

Potential triggers:

- Critical customer journey failure.
- Critical telephony failure.
- Critical integration failure.
- Data corruption.
- Security incident.
- Major platform instability.
- Unacceptable customer impact.
- Unacceptable business impact.

---

# 73. Rollback Execution

If rollback is required:

1. Announce rollback decision.
2. Record decision authority.
3. Stop further deployment activity.
4. Notify stakeholders.
5. Execute rollback runbook.
6. Restore previous routing.
7. Restore previous configuration.
8. Restore previous integrations.
9. Restore telephony where applicable.
10. Restore data where required.
11. Validate previous service.
12. Confirm business operation.
13. Communicate rollback completion.
14. Open incident.
15. Conduct post-incident review.

---

# 74. Rollback Validation

Rollback is not complete until:

- Previous service is available.
- Critical journeys work.
- Telephony works.
- Integrations work.
- Customer impact is understood.
- Business accepts restored state.
- Support is operating.
- Monitoring is active.

---

# 75. Production Release

Once the GO decision has been made:

1. Announce production release.
2. Activate customer traffic.
3. Activate production operations.
4. Confirm agent availability.
5. Confirm queues.
6. Monitor traffic.
7. Monitor errors.
8. Monitor customer experience.
9. Monitor integrations.
10. Monitor telephony.

---

# 76. Go-Live Communications

Issue formal go-live communications.

Potential communications:

- Internal go-live confirmation.
- Agent release.
- Supervisor release.
- Service desk notification.
- Business stakeholder notification.
- Customer notification where applicable.
- Vendor notification.

---

# 77. Go-Live Status Reporting

During the first operational period report:

- Time since go-live.
- Traffic.
- Volume.
- Queue status.
- Service level.
- Abandonment.
- Agent availability.
- Integration status.
- Telephony status.
- Critical incidents.
- Defects.
- Business status.

---

# 78. Production Monitoring

Immediately after go-live, monitor:

- Interaction volumes.
- Queue performance.
- Service level.
- Abandonment.
- AHT.
- ACW.
- Agent availability.
- Routing.
- Telephony.
- Integration errors.
- API failures.
- Data Action failures.
- Recording.
- Digital channels.
- CRM.

---

# 79. First Hour Validation

The first hour should include heightened monitoring.

Validate:

- Customer traffic.
- Agent login.
- Queue operation.
- Routing.
- Telephony.
- CRM.
- Integrations.
- Recording.
- Reporting.
- Digital channels.
- Critical business processes.

---

# 80. First Operational Period

The first operational period should be formally reviewed.

Depending on the project this may be:

- First hour.
- First shift.
- First business day.

Review:

- Incidents.
- Defects.
- User issues.
- Customer impact.
- Performance.
- Integration health.
- Business feedback.

---

# 81. Production Incident Management

All material incidents must be logged.

For each incident capture:

- Incident ID.
- Time.
- Detection.
- Impact.
- Severity.
- Owner.
- Technical cause.
- Workaround.
- Resolution.
- Business impact.
- Communication.
- Follow-up.

---

# 82. Major Incident Management

If a major incident occurs:

1. Declare major incident.
2. Assign incident commander.
3. Open bridge.
4. Notify stakeholders.
5. Assess impact.
6. Identify workaround.
7. Escalate vendors.
8. Determine recovery.
9. Communicate status.
10. Resolve.
11. Validate.
12. Conduct post-incident review.

---

# 83. Production Change Control

No non-emergency configuration changes should be made during the initial go-live period without appropriate approval.

Any emergency change must:

- Have an owner.
- Have a reason.
- Have impact assessment.
- Have rollback.
- Be documented.
- Be validated.

---

# 84. Hypercare Activation

Once production is confirmed:

```text
GO-LIVE
   ↓
Production Monitoring
   ↓
Hypercare Activation
   ↓
Enhanced Support
   ↓
Stabilisation
```

Phase 11 begins with the activation of the hypercare operating model.

---

# 85. Hypercare Handover

Transfer active operational responsibility into the Phase 11 hypercare model.

Handover should include:

- Current status.
- Open incidents.
- Open defects.
- Known limitations.
- Monitoring status.
- Business feedback.
- Integration status.
- Telephony status.
- Data migration status.
- Outstanding actions.

---

# 86. Go-Live Completion Record

Create a formal go-live record containing:

- Go-live date.
- Go-live time.
- Time zone.
- Change reference.
- Release version.
- Production organisation.
- Deployment team.
- Business approvers.
- Go/no-go decision.
- Smoke test result.
- Business validation result.
- Incidents.
- Defects.
- Rollback status.
- Hypercare status.

---

# 87. Production Deployment Evidence

Capture evidence for:

- Configuration deployment.
- Terraform deployment where applicable.
- API deployment.
- Integration activation.
- Telephony activation.
- Number porting.
- Data migration.
- Smoke testing.
- Business validation.
- Go-live approval.
- Communications.
- Monitoring.

---

# 88. Deployment Timeline

Maintain an actual timeline of production activity.

Example:

```text
18:00 — Cutover Started
18:05 — Pre-Cutover Validation Complete
18:15 — Production Baseline Captured
18:30 — Configuration Deployment Started
19:00 — Configuration Deployment Complete
19:15 — Integrations Activated
19:30 — Telephony Activated
19:45 — Data Migration Complete
20:00 — Technical Smoke Testing
20:30 — Business Validation
20:45 — Go Decision
21:00 — Production Release
21:15 — Hypercare Activated
```

Actual times must be recorded during the deployment.

---

# 89. Production Validation Evidence

All critical production validation must be retained.

Evidence may include:

- Screenshots.
- Logs.
- Test results.
- API responses.
- Call recordings where permitted.
- Reports.
- Dashboard results.
- Configuration output.
- Deployment logs.
- Approval records.

---

# 90. Production Configuration Audit

After deployment compare production against the approved baseline.

Validate:

- Configuration version.
- User count.
- Queue count.
- Skills.
- Architect flows.
- Integrations.
- Data Actions.
- Data Tables.
- Telephony.
- Recording.
- Reporting.
- WFM.
- QM.

Record deviations.

---

# 91. Production Configuration Drift

Any unexpected difference between approved and deployed configuration must be:

1. Identified.
2. Assessed.
3. Documented.
4. Approved or corrected.
5. Added to configuration baseline.

---

# 92. Security Post-Go-Live Validation

Validate:

- No unexpected privileged users.
- No unexpected OAuth clients.
- No unnecessary permissions.
- SSO works.
- MFA works.
- Audit logging works.
- Access boundaries work.
- Division restrictions work.
- Integration credentials are secured.

---

# 93. Operational Acceptance

The operational owner should formally accept the service into hypercare.

Acceptance should confirm:

- Service available.
- Support available.
- Monitoring active.
- Documentation available.
- Known issues understood.
- Hypercare active.

---

# 94. Business Acceptance

Business acceptance should confirm:

- Customer journeys operate.
- Agents can work.
- Supervisors can manage.
- Critical reports operate.
- Customer impact is acceptable.
- Business is ready to continue operations.

---

# 95. Phase 10 Deliverables

The following deliverables should be produced where applicable:

1. Cutover start record.
2. Production baseline.
3. Production deployment record.
4. Configuration release record.
5. Terraform / deployment evidence.
6. Production configuration validation.
7. User provisioning record.
8. Telephony activation record.
9. Number porting confirmation.
10. Integration activation record.
11. Data migration execution record.
12. Data reconciliation report.
13. Production smoke test results.
14. End-to-end validation results.
15. Business validation results.
16. Go/no-go decision record.
17. Go-live approval.
18. Go-live communications.
19. Production incident log.
20. Rollback record where applicable.
21. Production configuration audit.
22. Security validation.
23. Operational acceptance.
24. Business acceptance.
25. Hypercare activation record.
26. Go-live completion report.
27. Phase 10 acceptance record.

---

# 96. Phase Dependencies

## Inputs

Phase 10 depends on:

**Phase 08 — Testing & Validation**

**Phase 09 — Operational Readiness & Cutover Preparation**

## Outputs

Phase 10 provides:

**Phase 11 — Hypercare & Stabilisation**

---

# 97. Dependency Model

```text
Gate 09
   ↓
Final Readiness
   ↓
Cutover Start
   ↓
Production Deployment
   ↓
Integration Activation
   ↓
Telephony Activation
   ↓
Data Migration
   ↓
Technical Validation
   ↓
Business Validation
   ↓
Go / No-Go
   ↓
Production Release
   ↓
Hypercare
   ↓
Phase 11
```

---

# 98. Recommended Task Decomposition

The master deployment spreadsheet should break Phase 10 into individual tasks.

Recommended columns:

| Column | Description |
|---|---|
| Task ID | Unique task identifier |
| Phase | Phase number |
| Workstream | Phase 10 workstream |
| Parent Task | Parent activity |
| Task | Individual activity |
| Description | Detailed task description |
| Type | Required / Conditional / Optional |
| Dependency | Predecessor |
| Role | Primary responsible role |
| Customer Responsibility | Customer-owned activity |
| Environment | PROD |
| Effort | Estimated hours |
| Duration | Elapsed duration |
| Critical Path | Yes / No |
| Deliverable | Output |
| Acceptance Criteria | Completion condition |
| Status | Planned / In Progress / Complete |
| Evidence | Evidence reference |
| Notes | Additional information |

---

# 99. Recommended Phase 10 Task ID Structure

Use:

```text
P10-001
P10-002
P10-003
```

For workstream-level decomposition:

```text
P10-CMD-001
P10-CMD-002

P10-CONFIG-001
P10-CONFIG-002

P10-IAM-001
P10-IAM-002

P10-ROUTE-001
P10-ROUTE-002

P10-TEL-001
P10-TEL-002

P10-INT-001
P10-INT-002

P10-MIG-001
P10-MIG-002

P10-TEST-001
P10-TEST-002

P10-GOLIVE-001
P10-GOLIVE-002

P10-ROLL-001
P10-ROLL-002

P10-HC-001
P10-HC-002
```

---

# 100. Recommended Production Task Sequence

The project schedule should generally follow this dependency sequence:

```text
P10-001
Confirm Gate 09 Approval
        ↓
P10-002
Activate Command Centre
        ↓
P10-003
Confirm Cutover Team
        ↓
P10-004
Final Production Readiness Check
        ↓
P10-005
Capture Production Baseline
        ↓
P10-006
Confirm Rollback Capability
        ↓
P10-007
Deploy Production Configuration
        ↓
P10-008
Activate Identity
        ↓
P10-009
Provision Users
        ↓
P10-010
Activate Queues and Routing
        ↓
P10-011
Activate Architect
        ↓
P10-012
Activate Integrations
        ↓
P10-013
Activate Telephony
        ↓
P10-014
Activate Numbers
        ↓
P10-015
Activate Digital Channels
        ↓
P10-016
Execute Data Migration
        ↓
P10-017
Reconcile Data
        ↓
P10-018
Validate Recording
        ↓
P10-019
Validate Reporting
        ↓
P10-020
Validate WFM / QM
        ↓
P10-021
Validate Monitoring
        ↓
P10-022
Technical Smoke Testing
        ↓
P10-023
End-to-End Business Validation
        ↓
P10-024
Go / No-Go Decision
        ↓
P10-025
Production Release
        ↓
P10-026
Go-Live Communications
        ↓
P10-027
Production Monitoring
        ↓
P10-028
Activate Hypercare
        ↓
P10-029
Production Handover
        ↓
P10-030
Complete Go-Live Record
        ↓
P10-031
Gate 10 Review
```

The actual project schedule must be adapted to the deployment architecture and cutover strategy.

---

# 101. Effort Estimation Considerations

Phase 10 effort varies significantly depending on deployment complexity.

Estimate separately for:

- Cutover management.
- Configuration deployment.
- Terraform / automation deployment.
- User provisioning.
- Telephony.
- Number porting.
- Architect activation.
- Routing activation.
- Integration activation.
- CRM activation.
- Digital activation.
- Data migration.
- Recording.
- Reporting.
- WFM.
- QM.
- Security.
- Monitoring.
- Smoke testing.
- Business validation.
- Go/no-go governance.
- Communications.
- Hypercare activation.

Do not estimate Phase 10 as one aggregate activity.

---

# 102. Effort Drivers

Major effort drivers include:

- Number of users.
- Number of queues.
- Number of skills.
- Number of Architect flows.
- Number of integrations.
- Number of external systems.
- Telephony architecture.
- Number of DIDs.
- Number porting complexity.
- Digital channels.
- CRM integration.
- Data migration volume.
- WFM.
- QM.
- Recording.
- Reporting.
- Security requirements.
- Number of locations.
- Number of countries.
- Business criticality.
- Cutover window.
- Phased rollout.
- Rollback complexity.
- Customer support requirements.

---

# 103. Critical Path Considerations

Potential critical-path activities include:

- Gate 09 approval.
- Production access.
- Production configuration.
- Number porting.
- Telephony activation.
- Integration activation.
- Data migration.
- Business validation.
- Go/no-go decision.
- Production release.

The project schedule should identify these explicitly.

---

# 104. Required vs Conditional Activities

The master methodology must distinguish between required and conditional activities.

## Generally Required

- Gate 09 validation.
- Cutover command centre.
- Production baseline.
- Production configuration deployment.
- Production validation.
- Business validation.
- Go/no-go decision.
- Production release.
- Go-live communication.
- Hypercare activation.

## Conditional

- Number porting.
- Data migration.
- Digital channels.
- CRM.
- WFM.
- QM.
- Knowledge.
- Bots.
- AI.
- Event-driven integrations.
- Rollback.
- Phased activation.

## Optional

- Extended post-deployment testing.
- Additional deployment rehearsal.
- Additional production validation.
- Additional reporting validation.

---

# 105. Phase 10 Risks

Potential risks include:

### Production Configuration Failure

The deployment may fail or introduce unexpected configuration.

### Configuration Drift

Production may differ from the approved baseline.

### Telephony Failure

Calls may not route correctly following activation.

### Number Porting Failure

Numbers may not route to Genesys Cloud as expected.

### Integration Failure

External systems may not communicate correctly.

### Data Migration Failure

Data may be missing, invalid or inconsistent.

### Identity Failure

Users may not be able to authenticate.

### Routing Failure

Interactions may not reach the intended queue or agent.

### Business Validation Failure

Critical business journeys may not operate.

### Cutover Overrun

The deployment may exceed the approved maintenance window.

### Rollback Failure

The previous service may not be recoverable within the required window.

### Customer Impact

Customers may experience service degradation.

### Resource Availability

Required technical or business resources may not be available.

---

# 106. Risk Mitigation

For each material risk:

1. Identify risk.
2. Assess probability.
3. Assess impact.
4. Define mitigation.
5. Assign owner.
6. Define trigger.
7. Define contingency.
8. Track to closure.

---

# 107. Production Incident Severity

Use a standard severity model.

| Severity | Description | Example |
|---|---|---|
| Sev 1 | Critical | Customers cannot contact business |
| Sev 2 | High | Major business function unavailable |
| Sev 3 | Medium | Limited impact with workaround |
| Sev 4 | Low | Minor issue |

Severity definitions should be aligned to the customer's service management framework.

---

# 108. Go-Live Success Criteria

The deployment should be considered successful when:

- Production configuration is deployed.
- Users can authenticate.
- Agents can operate.
- Supervisors can operate.
- Queues route correctly.
- Architect flows operate.
- Telephony operates.
- Integrations operate.
- Data migration is reconciled.
- Recording operates.
- Reporting operates.
- Digital channels operate where applicable.
- WFM operates where applicable.
- QM operates where applicable.
- Monitoring operates.
- Business validates critical journeys.
- No unacceptable critical incidents exist.
- Hypercare is active.

---

# 109. Production Deployment Definition of Done

Production deployment is complete when:

- Approved configuration is deployed.
- Production configuration is validated.
- Production access is validated.
- Users are provisioned.
- Queues are active.
- Routing is active.
- Architect is active.
- Telephony is active.
- Numbers are active where applicable.
- Integrations are active.
- Digital channels are active where applicable.
- Data migration is complete where applicable.
- Data reconciliation is complete.
- Recording is active where applicable.
- Reporting is active.
- WFM is active where applicable.
- QM is active where applicable.
- Security validation is complete.
- Monitoring is active.
- Technical smoke testing is complete.
- Business validation is complete.

---

# 110. Go-Live Definition of Done

Go-live is complete when:

- Formal GO decision is recorded.
- Production traffic is active.
- Business confirms operation.
- Support is active.
- Monitoring is active.
- Communications are complete.
- Hypercare is active.
- Known defects are logged.
- Known limitations are documented.
- Production evidence is captured.
- Go-live record is complete.

---

# 111. Phase 10 Definition of Done

Phase 10 is complete when:

- Gate 09 is confirmed.
- Cutover command centre is active.
- Production baseline is captured.
- Approved configuration is deployed.
- Identity is operational.
- Users are provisioned.
- Queues are operational.
- Skills and languages are operational.
- Routing is operational.
- Architect is operational.
- Telephony is operational.
- Numbers are operational where applicable.
- Digital channels are operational where applicable.
- Integrations are operational.
- Data migration is complete where applicable.
- Data is reconciled.
- Recording is operational where applicable.
- Reporting is operational.
- WFM is operational where applicable.
- QM is operational where applicable.
- Security is validated.
- Monitoring is operational.
- Technical validation is complete.
- Business validation is complete.
- Go/no-go decision is recorded.
- Production release is complete.
- Communications are issued.
- Production support is active.
- Hypercare is active.
- Go-live evidence is captured.
- Phase 10 Gate is passed.

---

# 112. Phase 10 Governance

Phase 10 should have formal governance events.

Recommended meetings:

- Cutover start.
- Pre-deployment readiness check.
- Technical deployment checkpoint.
- Integration checkpoint.
- Telephony checkpoint.
- Data migration checkpoint.
- Technical validation checkpoint.
- Business validation checkpoint.
- Go/no-go meeting.
- Go-live confirmation.
- Hypercare transition.
- Phase gate review.

---

# 113. Phase 10 Reporting

Track:

- Cutover progress.
- Deployment progress.
- Configuration deployment.
- Integration status.
- Telephony status.
- Data migration status.
- Validation results.
- Defect status.
- Incident status.
- Business readiness.
- Go-live status.
- Hypercare readiness.

---

# 114. Go-Live Status Dashboard

Maintain a live dashboard.

Example:

```text
                 GO-LIVE STATUS

Command Centre       [ GREEN ]
Configuration        [ GREEN ]
Identity             [ GREEN ]
Users                [ GREEN ]
Routing              [ GREEN ]
Architect            [ GREEN ]
Telephony            [ GREEN ]
Numbers              [ GREEN ]
Integrations         [ GREEN ]
Data                 [ GREEN ]
Recording            [ GREEN ]
Reporting            [ GREEN ]
Digital              [ GREEN ]
WFM                  [ GREEN ]
QM                   [ GREEN ]
Security             [ GREEN ]
Monitoring           [ GREEN ]
Testing              [ GREEN ]
Business Validation  [ GREEN ]
Support              [ GREEN ]
Hypercare            [ GREEN ]
```

Any Amber or Red item requires an owner and documented action.

---

# 115. Phase 10 Completion Record

The project should retain a formal production deployment record containing:

- Project name.
- Customer.
- Genesys Cloud organisation.
- Production region.
- Go-live date.
- Go-live time.
- Time zone.
- Release version.
- Change reference.
- Cutover manager.
- Technical lead.
- Business owner.
- Deployment team.
- Go/no-go decision.
- Validation status.
- Incidents.
- Defects.
- Rollback status.
- Hypercare activation.
- Business acceptance.
- Operational acceptance.

---

# 116. Phase Gate — Gate 10: Production Deployment & Go-Live Complete

## Gate Objective

Confirm that the Genesys Cloud solution has been successfully deployed into production, validated, accepted by the business and transitioned into the hypercare operating model.

---

# 117. Gate 10 Entry Criteria

The following must be true:

- Gate 09 passed.
- Production deployment commenced.
- Production configuration deployed.
- Required production dependencies activated.
- Technical validation underway or complete.

---

# 118. Gate 10 Exit Criteria

## Production

- Production configuration deployed.
- Production baseline validated.
- Configuration version recorded.
- Users provisioned.
- Queues operational.
- Routing operational.
- Architect operational.
- Telephony operational.
- Numbers operational where applicable.
- Digital channels operational where applicable.
- Integrations operational.
- Data migration completed where applicable.
- Recording operational where applicable.
- Reporting operational.
- WFM operational where applicable.
- QM operational where applicable.

## Validation

- Technical smoke testing passed.
- Critical customer journeys passed.
- Business validation passed.
- Security validation passed.
- Monitoring validation passed.

## Governance

- Go/no-go decision recorded.
- Business acceptance recorded.
- Operational acceptance recorded.
- Go-live communications completed.
- Production support activated.
- Hypercare activated.

## Documentation

- Deployment record complete.
- Production evidence captured.
- Configuration baseline updated.
- Incidents recorded.
- Defects recorded.
- Known limitations documented.

---

# 119. Gate Decision

The Phase 10 gate must result in one of:

```text
PASS
```

The production deployment has successfully completed and the service has transitioned to hypercare.

```text
PASS WITH CONDITIONS
```

The service is live with accepted residual issues and defined remediation.

```text
HOLD
```

The deployment remains incomplete or requires additional validation.

```text
ROLLBACK
```

The deployment has been reversed and the project must execute the appropriate recovery and reassessment process.

---

# 120. Phase 10 Outputs to Phase 11

Phase 10 provides Phase 11 with:

```text
Live Production Service
        +
Production Configuration
        +
Validated Integrations
        +
Validated Telephony
        +
Validated Business Journeys
        +
Production Monitoring
        +
Support Model
        +
Known Issues
        +
Open Defects
        +
Go-Live Record
        +
Hypercare Activation
        ↓
Phase 11 — Hypercare & Stabilisation
```

---

# 121. Layer 1 Position

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
| **09 — Operational Readiness & Cutover Preparation** | Defined |
| **10 — Production Deployment & Go-Live** | **Defined** |
| 11 — Hypercare & Stabilisation | Next |
| 12 — BAU Handover & Project Closure | Pending |

---

# 122. Phase 10 Summary

Phase 10 is the controlled transition from a deployment-ready solution into live production service.

The project must demonstrate:

```text
Approved Solution
        ↓
Production Deployment
        ↓
Configuration Validation
        ↓
Integration Activation
        ↓
Telephony Activation
        ↓
Data Migration
        ↓
Technical Validation
        ↓
Business Validation
        ↓
Go / No-Go
        ↓
Production Release
        ↓
Monitoring
        ↓
Operational Acceptance
        ↓
Hypercare
```

The objective is not merely to make the Genesys Cloud organisation technically available.

The objective is to establish a functioning production service that:

- Serves customers.
- Supports agents.
- Supports supervisors.
- Integrates with enterprise systems.
- Operates securely.
- Produces required reporting.
- Supports operational processes.
- Is monitored.
- Is supported.
- Has an established recovery path.
- Has formal business acceptance.

The formal completion point is:

**Gate 10 — Production Deployment & Go-Live Complete**

---

# Phase Completion

**Phase:** 10 — Production Deployment & Go-Live

**Previous Phase:** 09 — Operational Readiness & Cutover Preparation

**Next Phase:** 11 — Hypercare & Stabilisation

**Phase Gate:** Gate 10 — Production Deployment & Go-Live Complete

**Primary Outcome:** A live, validated and business-accepted Genesys Cloud production service transitioned into the hypercare operating model.
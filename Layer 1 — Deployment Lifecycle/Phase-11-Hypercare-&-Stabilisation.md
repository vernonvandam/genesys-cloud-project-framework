# Phase 11 — Hypercare & Stabilisation

## 1. Purpose

Phase 11 provides the controlled transition from production deployment into a stable operational service.

This phase begins immediately following:

- Phase 10 — Production Deployment & Go-Live
- Gate 10 approval
- Production release
- Initial production validation
- Activation of the hypercare support model

The purpose of Phase 11 is to provide enhanced operational support while the Genesys Cloud solution is exposed to real production volumes, real customer behaviour, real agent workflows, and real enterprise integrations.

Hypercare is not simply an extended testing period.

It is the controlled period in which the project team:

- Monitors production performance.
- Detects defects that only emerge under live conditions.
- Resolves production incidents.
- Tunes routing and configuration.
- Validates integrations at production scale.
- Validates telephony performance.
- Reviews customer experience.
- Reviews agent experience.
- Reviews supervisor experience.
- Monitors reporting.
- Monitors WFM and QM where applicable.
- Identifies configuration gaps.
- Performs root-cause analysis.
- Stabilises the solution.
- Transfers operational knowledge to BAU support.
- Establishes the final production baseline.
- Prepares for formal project handover.

The output of Phase 11 is a **stable, operationally accepted Genesys Cloud service ready for formal BAU handover and project closure in Phase 12**.

---

# 2. Phase Objective

By the end of Phase 11:

- Production operations are stable.
- Critical incidents are resolved.
- High-severity defects are resolved or have formally accepted workarounds.
- Production configuration is stable.
- Routing is validated under live conditions.
- Telephony is stable.
- Integrations are stable.
- Digital channels are stable where applicable.
- Architect flows are stable.
- Recording is stable.
- Reporting is validated against production behaviour.
- WFM is stable where applicable.
- QM is stable where applicable.
- Security is validated.
- Monitoring is operating.
- Performance is understood.
- Customer experience is acceptable.
- Agent experience is acceptable.
- Supervisor experience is acceptable.
- Operational support teams are capable of supporting the platform.
- Documentation is updated.
- Knowledge transfer is complete.
- Known issues are documented.
- Remaining defects are transferred into BAU governance where appropriate.
- Production configuration baseline is confirmed.
- Hypercare exit criteria are achieved.
- Phase 11 Gate is passed.

---

# 3. Phase Position

The deployment lifecycle is:

```text
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

Phase 11 is the controlled stabilisation period between technical go-live and formal operational ownership.

---

# 4. Phase Entry Criteria

Phase 11 must not commence without the following conditions being met or formally accepted.

## Required

1. Gate 10 has passed.
2. Production release is complete.
3. Production traffic is active.
4. Production monitoring is active.
5. Hypercare command structure is active.
6. Support contacts are confirmed.
7. Incident escalation paths are confirmed.
8. Open defects have been identified.
9. Known limitations have been documented.
10. Business stakeholders are available.
11. Technical resources are available.
12. Vendor support is available where required.
13. Production configuration baseline is recorded.
14. Initial production validation is complete.
15. Hypercare communications have been issued.

Any exception must be formally documented and accepted.

---

# 5. Phase Workstreams

The master deployment methodology should structure Phase 11 into the following workstreams:

### 11.01 Hypercare Command Centre
### 11.02 Production Monitoring
### 11.03 Incident Management
### 11.04 Defect Management
### 11.05 Problem Management
### 11.06 Telephony Stabilisation
### 11.07 Routing Stabilisation
### 11.08 Architect Stabilisation
### 11.09 Integration Stabilisation
### 11.10 CRM Stabilisation
### 11.11 Digital Channel Stabilisation
### 11.12 Recording Stabilisation
### 11.13 Reporting Stabilisation
### 11.14 WFM Stabilisation
### 11.15 QM Stabilisation
### 11.16 Security Validation
### 11.17 Performance & Capacity Monitoring
### 11.18 Agent Experience
### 11.19 Supervisor Experience
### 11.20 Customer Experience
### 11.21 Data Quality & Reconciliation
### 11.22 Knowledge / AI Stabilisation
### 11.23 Operational Tuning
### 11.24 Configuration Baseline
### 11.25 Documentation Updates
### 11.26 Knowledge Transfer
### 11.27 BAU Support Readiness
### 11.28 Vendor Escalation
### 11.29 Hypercare Metrics
### 11.30 Hypercare Exit Preparation
### 11.31 BAU Handover Preparation
### 11.32 Phase Gate Preparation

Not every workstream applies to every project.

Each task must be classified as:

- Required
- Conditional
- Optional
- Not Applicable

---

# 6. Hypercare Principles

Hypercare must operate according to the following principles:

1. Production stability takes priority over new feature development.
2. Critical customer-impacting issues receive immediate attention.
3. Production changes remain controlled.
4. All material incidents are recorded.
5. Recurring incidents require root-cause analysis.
6. Configuration changes require approval.
7. Monitoring is evidence-driven.
8. Production data is used to validate assumptions made during design.
9. Business feedback is actively collected.
10. Agent feedback is actively collected.
11. Supervisor feedback is actively collected.
12. Known defects are tracked to closure or formal BAU acceptance.
13. Temporary workarounds must be documented.
14. Permanent fixes must be distinguished from workarounds.
15. Hypercare must have defined exit criteria.
16. Hypercare must not become indefinite project support.
17. The end state is BAU operational ownership.

---

# 7. Hypercare Command Centre

Establish the hypercare command centre immediately following go-live.

Potential participants include:

- Project Manager
- Hypercare Manager
- Genesys Cloud Lead
- Solution Architect
- Technical Lead
- Integration Lead
- Telephony Lead
- IAM Lead
- Security Lead
- Data Lead
- Reporting Lead
- WFM Lead
- QM Lead
- Business Lead
- Operations Lead
- Service Desk Lead
- Application Support
- Infrastructure Support
- Customer Experience Lead
- Vendor / Genesys Support

Only applicable roles need to participate.

---

# 8. Hypercare Responsibilities

The hypercare team is responsible for:

- Monitoring production.
- Managing incidents.
- Managing defects.
- Coordinating technical resources.
- Managing vendor escalation.
- Reviewing business impact.
- Managing configuration changes.
- Tracking operational metrics.
- Coordinating communications.
- Performing root-cause analysis.
- Monitoring customer experience.
- Monitoring agent experience.
- Monitoring integrations.
- Confirming service stability.
- Preparing BAU handover.

---

# 9. Hypercare Operating Model

Define:

- Hypercare start date.
- Expected hypercare duration.
- Hypercare operating hours.
- Extended coverage.
- On-call arrangements.
- Severity definitions.
- Escalation paths.
- Response targets.
- Resolution targets.
- Communication cadence.
- Reporting cadence.
- Exit criteria.

---

# 10. Hypercare Duration

Hypercare duration must be determined based on deployment complexity.

Typical factors include:

- Contact volume.
- Number of users.
- Number of queues.
- Number of integrations.
- Number of channels.
- Business criticality.
- Number porting complexity.
- WFM complexity.
- QM complexity.
- Migration complexity.
- Geographic footprint.
- Regulatory requirements.
- Production risk.

Do not assume a fixed hypercare duration for every project.

---

# 11. Hypercare Coverage

Determine whether hypercare requires:

- Business-hours coverage.
- Extended-hours coverage.
- 24x7 coverage.
- Weekend coverage.
- Public holiday coverage.
- Carrier support.
- Vendor support.
- Application support.
- Integration support.

---

# 12. Hypercare Communications

Define a communication cadence.

Potential communications include:

- Daily status report.
- Daily incident review.
- Daily defect review.
- Business status update.
- Technical status update.
- Executive status update.
- End-of-week summary.

Communication frequency can be reduced as stability improves.

---

# 13. Hypercare Status Reporting

Track at minimum:

- Open incidents.
- New incidents.
- Resolved incidents.
- Open defects.
- New defects.
- Resolved defects.
- Severity distribution.
- Customer impact.
- Agent impact.
- Integration health.
- Telephony health.
- Routing health.
- Digital health.
- Reporting health.
- WFM health.
- QM health.
- Security issues.
- Performance.
- Outstanding actions.

---

# 14. Production Monitoring

Continue heightened monitoring after go-live.

Monitor:

- Interaction volume.
- Queue performance.
- Service level.
- Abandonment.
- Average Handle Time.
- Average Speed of Answer.
- After Call Work.
- Agent occupancy.
- Agent availability.
- Queue depth.
- Routing behaviour.
- Transfer rates.
- Callback performance.
- Digital interactions.
- Error rates.

---

# 15. Telephony Monitoring

Monitor:

- Inbound calls.
- Outbound calls.
- Call completion.
- Failed calls.
- SIP signalling.
- Carrier behaviour.
- Caller ID.
- DNIS.
- Number routing.
- Audio quality.
- One-way audio.
- Dropped calls.
- Transfer failures.
- Conference failures.
- Recording failures.

---

# 16. Voice Quality Monitoring

Where applicable monitor:

- MOS.
- Jitter.
- Latency.
- Packet loss.
- RTP issues.
- Network path.
- Endpoint issues.
- Carrier issues.

Where voice-quality issues occur, identify whether the fault is:

- Agent endpoint.
- Local network.
- WAN.
- Internet.
- ISP.
- Carrier.
- Genesys Cloud.
- Integration.
- Configuration.

---

# 17. Routing Monitoring

Validate real production routing.

Monitor:

- Queue assignment.
- Skill matching.
- Language matching.
- Bullseye routing.
- Priority.
- Preferred agent.
- Queue overflow.
- In-queue flows.
- Callback.
- Transfer.
- Agent availability.
- Routing failures.

---

# 18. Routing Tuning

Where production behaviour differs from design assumptions:

1. Identify issue.
2. Determine root cause.
3. Assess business impact.
4. Determine whether configuration change is required.
5. Assess change risk.
6. Obtain approval.
7. Implement change.
8. Test.
9. Monitor.
10. Record outcome.

---

# 19. Architect Monitoring

Monitor production Architect flows for:

- Flow failures.
- Unexpected disconnects.
- Failed Data Actions.
- Invalid Data Table values.
- Missing prompts.
- Routing failures.
- Error paths.
- Timeout behaviour.
- Transfer failures.
- Bot handoff failures.
- Unexpected customer journeys.

---

# 20. Architect Stabilisation

For each significant Architect issue:

1. Capture flow version.
2. Capture interaction ID where available.
3. Identify execution path.
4. Identify failure point.
5. Determine root cause.
6. Determine workaround.
7. Determine permanent fix.
8. Implement controlled change.
9. Validate.
10. Publish approved version.
11. Monitor.
12. Document.

---

# 21. Data Action Monitoring

Monitor:

- Authentication.
- Endpoint availability.
- Request failures.
- Response failures.
- Timeout.
- Rate limiting.
- Invalid data.
- Mapping errors.
- External system errors.

---

# 22. Data Action Stabilisation

For failures:

1. Capture interaction.
2. Capture Data Action.
3. Capture request.
4. Capture response.
5. Identify error.
6. Determine whether Genesys or external system is responsible.
7. Escalate where necessary.
8. Correct.
9. Retest.
10. Monitor.

---

# 23. Integration Monitoring

Monitor every production integration.

Potential integrations:

- CRM.
- ERP.
- Customer databases.
- Identity provider.
- Middleware.
- API gateways.
- Data platforms.
- Ticketing.
- Workforce systems.
- Quality systems.
- Notification systems.

---

# 24. Integration Health Checks

For each integration validate:

- Availability.
- Authentication.
- API response.
- Response time.
- Error rate.
- Timeout.
- Retry.
- Data integrity.
- Logging.
- Monitoring.
- Alerting.

---

# 25. CRM Stabilisation

Where CRM integration is in scope monitor:

- Login.
- Embedded client.
- Screen pop.
- Customer lookup.
- Case creation.
- Interaction logging.
- Call controls.
- Disposition.
- Recording links.
- API errors.

---

# 26. Digital Channel Monitoring

Where applicable monitor:

- Web messaging.
- Web chat.
- Email.
- SMS.
- Social messaging.
- Open messaging.

Validate:

- Customer entry.
- Routing.
- Queue assignment.
- Agent delivery.
- Response.
- Transfer.
- Disconnect.
- Conversation history.
- Reporting.

---

# 27. Digital Stabilisation

Investigate:

- Customer drop-off.
- Routing failures.
- Agent acceptance issues.
- Authentication failures.
- Message delivery failures.
- Queue delays.
- Bot handoff failures.
- Conversation persistence issues.

---

# 28. Recording Monitoring

Validate:

- Recording creation.
- Recording availability.
- Recording metadata.
- Recording playback.
- Recording permissions.
- Recording retention.
- Pause / resume.
- Secure pause.

---

# 29. Recording Issue Management

Where recordings are missing or incorrect:

1. Identify interaction.
2. Determine recording policy.
3. Determine recording state.
4. Determine whether recording was created.
5. Determine storage/retrieval issue.
6. Determine permissions issue.
7. Correct configuration if required.
8. Validate.
9. Document.

---

# 30. Reporting Validation

Compare production reporting against expected operational behaviour.

Validate:

- Interaction counts.
- Queue volumes.
- Service level.
- Abandonment.
- AHT.
- ASA.
- ACW.
- Agent status.
- Transfers.
- Wrap-up.
- Digital metrics.

---

# 31. Reporting Reconciliation

Where possible reconcile:

```text
Customer Interactions
        ↓
Genesys Cloud Conversations
        ↓
Analytics
        ↓
Reports
        ↓
Business Reporting
```

Investigate unexplained differences.

---

# 32. WFM Stabilisation

Where WFM is in scope monitor:

- Forecasts.
- Schedules.
- Staffing.
- Adherence.
- Time-off.
- Intraday management.
- Agent availability.
- WFM integrations.
- Schedule accuracy.

---

# 33. WFM Production Validation

Compare actual production behaviour with WFM assumptions.

Review:

- Volume.
- AHT.
- Shrinkage.
- Occupancy.
- Staffing.
- Schedule adherence.

Adjust forecasting inputs where necessary.

---

# 34. QM Stabilisation

Where QM is in scope validate:

- Evaluation assignment.
- Evaluation forms.
- Recording access.
- Evaluator access.
- Quality scores.
- Coaching.
- Calibration.
- Reporting.

---

# 35. QM Production Review

Review:

- Evaluation completion.
- Evaluation distribution.
- Recording availability.
- Scoring consistency.
- Supervisor adoption.
- Quality reporting.

---

# 36. Security Monitoring

Monitor:

- Authentication.
- SSO.
- MFA.
- Privileged access.
- OAuth clients.
- API access.
- Division access.
- Role assignments.
- Audit logs.

---

# 37. Security Incident Management

Any unexpected access or security event must be handled under the customer's security incident process.

Potential events:

- Unexpected administrator access.
- Failed authentication patterns.
- Unexpected OAuth client.
- Incorrect permissions.
- Division exposure.
- Credential failure.
- Integration security failure.

---

# 38. Performance Monitoring

Monitor:

- Response time.
- API latency.
- Data Action latency.
- Architect execution.
- CRM response.
- Digital response.
- Queue performance.
- Agent application performance.

---

# 39. Capacity Monitoring

Review whether production volumes match sizing assumptions.

Monitor:

- Concurrent interactions.
- Agent count.
- Queue load.
- API volumes.
- Integration throughput.
- Digital volumes.
- WFM volumes.
- Reporting workloads.

---

# 40. Customer Experience Monitoring

Monitor customer-facing outcomes:

- Abandonment.
- Wait time.
- Callback completion.
- Transfer rate.
- IVR completion.
- Self-service completion.
- Digital response time.
- Customer complaints.
- Customer feedback.
- Escalations.

---

# 41. Agent Experience Monitoring

Collect agent feedback on:

- Login.
- Agent desktop.
- Softphone.
- Call controls.
- Queue handling.
- Transfers.
- Wrap-up.
- CRM.
- Knowledge.
- Digital interactions.
- WFM.
- QM.

---

# 42. Supervisor Experience Monitoring

Collect supervisor feedback on:

- Queue visibility.
- Agent monitoring.
- Coaching.
- Reporting.
- WFM.
- QM.
- Configuration.
- Escalation.
- Operational dashboards.

---

# 43. Agent Feedback Process

Create a structured feedback process.

Capture:

- Issue.
- User.
- Team.
- Workflow.
- Impact.
- Frequency.
- Severity.
- Suggested improvement.
- Workaround.
- Owner.

---

# 44. Business Feedback Process

Collect feedback from:

- Business owners.
- Contact centre managers.
- Supervisors.
- Agents.
- Customer experience teams.
- Reporting teams.
- WFM.
- QM.
- IT.

---

# 45. Incident Management

Every production incident must be classified.

For each incident record:

- Incident ID.
- Date.
- Time.
- Reporter.
- Detection method.
- System.
- Component.
- Severity.
- Business impact.
- Customer impact.
- Agent impact.
- Technical owner.
- Workaround.
- Root cause.
- Resolution.
- Follow-up.

---

# 46. Severity Model

Use the approved project/service management severity model.

Example:

| Severity | Description | Typical Response |
|---|---|---|
| Sev 1 | Critical service failure | Immediate |
| Sev 2 | Major service degradation | High priority |
| Sev 3 | Limited impact | Normal priority |
| Sev 4 | Minor issue | Planned |

Definitions must align with the customer's operational framework.

---

# 47. Major Incident Management

For a Sev 1 or major Sev 2 incident:

1. Declare major incident.
2. Assign Incident Commander.
3. Establish technical bridge.
4. Establish communications.
5. Determine impact.
6. Determine affected services.
7. Identify workaround.
8. Engage vendor support.
9. Assess rollback or emergency change.
10. Communicate status.
11. Implement recovery.
12. Validate recovery.
13. Close incident.
14. Conduct post-incident review.

---

# 48. Defect Management

Defects identified during hypercare must be classified.

Classify as:

- Configuration defect.
- Development defect.
- Integration defect.
- Data defect.
- Documentation defect.
- Training defect.
- Platform issue.
- Infrastructure issue.
- User issue.
- Process issue.
- Enhancement.

---

# 49. Defect Prioritisation

Prioritise according to:

- Customer impact.
- Business impact.
- Agent impact.
- Frequency.
- Severity.
- Availability of workaround.
- Regulatory impact.
- Security impact.
- Operational risk.

---

# 50. Defect Lifecycle

```text
Identified
    ↓
Logged
    ↓
Triaged
    ↓
Assigned
    ↓
Root Cause
    ↓
Fix / Workaround
    ↓
Test
    ↓
Production Change
    ↓
Validate
    ↓
Close
```

---

# 51. Production Change Control

All production changes during hypercare must be controlled.

For each change capture:

- Change ID.
- Reason.
- Risk.
- Impact.
- Owner.
- Approval.
- Implementation plan.
- Validation.
- Rollback.
- Result.

---

# 52. Emergency Changes

Emergency changes may be required for critical incidents.

An emergency change must still:

- Have an owner.
- Have approval.
- Have a defined reason.
- Have risk assessment.
- Have rollback.
- Be tested where practical.
- Be documented.
- Be reviewed after implementation.

---

# 53. Configuration Tuning

Potential tuning areas include:

- Queue routing.
- Skills.
- Languages.
- Bullseye routing.
- Priorities.
- Wrap-up.
- In-queue flows.
- Architect prompts.
- Architect logic.
- Data Actions.
- Timeouts.
- Digital routing.
- Agent utilisation.
- WFM assumptions.

---

# 54. Routing Optimisation

Use production data to determine whether routing performs as designed.

Review:

- Queue wait.
- Agent availability.
- Skill matching.
- Routing delays.
- Transfers.
- Abandonment.
- Service level.
- Customer experience.

Do not optimise routing based solely on anecdotal feedback.

---

# 55. Architect Optimisation

Review production Architect execution data.

Identify:

- Dead ends.
- Unexpected branches.
- Error paths.
- Abandonment points.
- Data Action failures.
- Customer confusion.
- Transfer failures.

Implement changes through controlled change management.

---

# 56. Digital Optimisation

Where applicable review:

- Customer drop-off.
- Queue time.
- Bot containment.
- Agent acceptance.
- Transfer.
- Escalation.
- Customer effort.

---

# 57. Bot / AI Stabilisation

Where AI or bots are in scope, monitor:

- Intent recognition.
- Containment.
- Fallback.
- Escalation.
- Handoff.
- Knowledge results.
- Customer satisfaction.
- Incorrect answers.
- Failed journeys.

---

# 58. Knowledge Stabilisation

Where Knowledge is in scope:

- Review failed searches.
- Review article usage.
- Review article accuracy.
- Review article gaps.
- Review agent feedback.
- Review customer feedback.
- Update content.
- Republish approved content.

---

# 59. Data Quality Review

Review production data quality.

Potential areas:

- User attributes.
- Queue assignments.
- Skills.
- Languages.
- Customer data.
- CRM data.
- Interaction attributes.
- Wrap-up codes.
- Reporting data.

---

# 60. Data Reconciliation

Where production integrations or migration are involved:

1. Compare source.
2. Compare Genesys Cloud.
3. Compare downstream systems.
4. Identify differences.
5. Determine cause.
6. Correct.
7. Reconcile.
8. Document.

---

# 61. Customer Experience Review

Review production KPIs against baseline and target.

Potential KPIs:

- Service level.
- ASA.
- Abandonment.
- AHT.
- FCR.
- Transfer rate.
- Callback completion.
- Digital response.
- Customer satisfaction.
- Complaint rate.

---

# 62. Agent Performance Review

Review:

- Login.
- Availability.
- Occupancy.
- AHT.
- ACW.
- Transfer.
- Queue performance.
- Schedule adherence.
- Quality.

Avoid using hypercare data to make premature individual performance conclusions where sample size is insufficient.

---

# 63. Operational Tuning

Tune the environment based on observed production behaviour.

Examples:

- Queue thresholds.
- Routing configuration.
- Agent groups.
- Skills.
- Business hours.
- Holiday schedules.
- Architect logic.
- Reporting.
- WFM assumptions.
- QM configuration.

---

# 64. Root Cause Analysis

Recurring or material issues require root-cause analysis.

Use an appropriate method such as:

- 5 Whys.
- Fishbone.
- Fault tree.
- Technical trace.
- Dependency analysis.

Record:

- Problem statement.
- Impact.
- Timeline.
- Root cause.
- Contributing factors.
- Corrective action.
- Preventive action.

---

# 65. Problem Management

Where incidents repeat:

1. Identify recurring pattern.
2. Create problem record.
3. Assign owner.
4. Determine root cause.
5. Define permanent fix.
6. Implement.
7. Validate.
8. Monitor recurrence.
9. Close problem.

---

# 66. Vendor Escalation

Where Genesys Cloud or another vendor is involved:

Capture:

- Vendor.
- Case number.
- Issue.
- Impact.
- Severity.
- Logs.
- Interaction IDs.
- Timestamps.
- Troubleshooting performed.
- Business impact.
- Vendor response.
- Workaround.
- Permanent fix.

---

# 67. Genesys Support Escalation

Where Genesys Support is engaged, provide sufficient evidence to avoid unnecessary delays.

Potential evidence:

- Organisation.
- Region.
- Interaction ID.
- Conversation ID.
- User.
- Queue.
- Flow.
- Timestamp.
- Time zone.
- Error.
- Screenshots.
- Network evidence.
- Reproduction steps.

---

# 68. Hypercare Daily Review

During the initial period, conduct a daily review.

Agenda:

1. Previous day incidents.
2. New incidents.
3. Open defects.
4. Customer impact.
5. Agent impact.
6. Telephony.
7. Routing.
8. Integrations.
9. Digital.
10. Reporting.
11. WFM.
12. QM.
13. Security.
14. Performance.
15. Actions.
16. Risks.
17. Exit readiness.

---

# 69. Hypercare Exit Assessment

The project should assess exit readiness regularly.

Review:

- Incident trend.
- Defect trend.
- Severity.
- Customer impact.
- Agent impact.
- System performance.
- Integration stability.
- Telephony stability.
- Reporting stability.
- Business acceptance.
- Support readiness.

---

# 70. Hypercare Metrics

Track trends rather than only point-in-time values.

Potential metrics:

- Incidents per day.
- Sev 1 incidents.
- Sev 2 incidents.
- Sev 3 incidents.
- Mean Time to Detect.
- Mean Time to Restore.
- Mean Time to Resolve.
- Defects opened.
- Defects closed.
- Defect backlog.
- Repeat incidents.
- Integration errors.
- Call failures.
- Routing failures.
- Digital failures.

---

# 71. Stability Trend

The project should demonstrate improving stability.

Example:

```text
Production Release
       ↓
High Incident Volume
       ↓
Issue Identification
       ↓
Fixes / Tuning
       ↓
Reduced Incident Volume
       ↓
Stable Service
       ↓
BAU Readiness
```

---

# 72. Hypercare Exit Criteria

Hypercare should only exit when the following are satisfied.

## Technical

- No unresolved critical production defects.
- No unresolved critical incidents.
- Telephony stable.
- Routing stable.
- Architect stable.
- Integrations stable.
- Digital stable where applicable.
- Recording stable.
- Reporting stable.
- WFM stable where applicable.
- QM stable where applicable.
- Monitoring stable.
- Security stable.

## Business

- Customer experience acceptable.
- Agent experience acceptable.
- Supervisor experience acceptable.
- Business owners accept production performance.
- Required reporting accepted.

## Operational

- Service desk ready.
- Application support ready.
- Technical support ready.
- Escalation model operational.
- Documentation complete.
- Knowledge transfer complete.

## Governance

- Remaining defects have owners.
- Remaining defects have target dates.
- BAU change process established.
- BAU support process established.
- Known limitations documented.
- Hypercare exit approved.

---

# 73. Hypercare Exit Thresholds

Where appropriate establish quantitative thresholds.

Examples:

- Zero Sev 1 incidents open.
- Zero unresolved critical security issues.
- Zero unresolved critical customer-impacting defects.
- No recurring critical incidents.
- Incident volume below agreed threshold.
- Integration error rate below agreed threshold.
- Call failure rate within agreed tolerance.
- Business KPIs within agreed tolerance.

Actual thresholds must be defined for the project.

---

# 74. Hypercare Exit Decision

The exit decision should result in:

```text
EXIT
EXIT WITH CONDITIONS
EXTEND HYPERCARE
```

---

# 75. Exit With Conditions

Hypercare may exit with conditions where:

- Remaining issues are low severity.
- Workarounds exist.
- Business impact is understood.
- BAU owners are assigned.
- Target dates exist.
- Business accepts residual risk.

---

# 76. Hypercare Extension

Hypercare should be extended where:

- Critical defects remain.
- Major incidents continue.
- Customer experience is unacceptable.
- Integration stability is poor.
- Telephony is unstable.
- Operational support is not ready.
- Business acceptance has not been achieved.

An extension should have:

- Reason.
- Owner.
- New target date.
- Additional effort estimate.
- Exit criteria.

---

# 77. Documentation Updates

Update all production documentation.

Potential documents:

- Architecture.
- Detailed design.
- Configuration.
- Integration design.
- Telephony.
- Routing.
- Architect.
- Data migration.
- Security.
- Operations.
- Monitoring.
- Support.
- Troubleshooting.
- Known issues.
- Disaster recovery.
- Business continuity.

---

# 78. Configuration Documentation

Document the final production configuration.

Include:

- Organisation.
- Region.
- Divisions.
- Users.
- Roles.
- Queues.
- Skills.
- Languages.
- Architect flows.
- Schedules.
- Telephony.
- Numbers.
- Integrations.
- Data Actions.
- Data Tables.
- Recording.
- Reporting.
- WFM.
- QM.
- Digital channels.

---

# 79. Operational Documentation

Update:

- Support runbooks.
- Incident runbooks.
- Escalation procedures.
- Troubleshooting guides.
- Monitoring guides.
- User administration.
- Queue administration.
- Telephony troubleshooting.
- Integration troubleshooting.
- Reporting support.

---

# 80. Knowledge Transfer

Conduct knowledge transfer sessions for BAU teams.

Potential audiences:

- Service Desk.
- Application Support.
- Genesys Administrators.
- Contact Centre Operations.
- Telephony Support.
- Integration Support.
- Security.
- Reporting.
- WFM.
- QM.

---

# 81. Knowledge Transfer Content

Cover:

- Architecture.
- Platform administration.
- User administration.
- Queue management.
- Routing.
- Architect.
- Telephony.
- Integrations.
- Monitoring.
- Incident management.
- Reporting.
- WFM.
- QM.
- Security.
- Common problems.
- Escalation.

---

# 82. Support Readiness

Validate that BAU support can:

- Identify incidents.
- Diagnose common issues.
- Access monitoring.
- Access logs.
- Identify queues.
- Identify users.
- Understand routing.
- Understand Architect.
- Understand integrations.
- Escalate appropriately.
- Contact vendors.

---

# 83. Support Simulation

Where appropriate conduct simulated incidents.

Example:

```text
Incident
   ↓
Service Desk
   ↓
Triage
   ↓
Genesys Support
   ↓
Technical Investigation
   ↓
Resolution
   ↓
Business Communication
   ↓
Closure
```

Validate the process rather than only the technical solution.

---

# 84. Operational Acceptance

The operational owner should formally confirm:

- Documentation is sufficient.
- Support is ready.
- Monitoring is operational.
- Escalation is understood.
- Known issues are understood.
- Remaining defects are accepted.
- BAU ownership is clear.

---

# 85. Business Acceptance Review

The business should review:

- Production KPIs.
- Customer experience.
- Agent experience.
- Supervisor experience.
- Business processes.
- Reporting.
- Outstanding defects.
- Known limitations.

---

# 86. Final Production Baseline

At hypercare exit, create the final production baseline.

Capture:

- Configuration version.
- Terraform version / commit where applicable.
- Architect versions.
- Integration versions.
- Data migration state.
- User population.
- Queue configuration.
- Telephony configuration.
- Digital configuration.
- Reporting configuration.
- WFM configuration.
- QM configuration.

---

# 87. Configuration Drift Review

Compare:

```text
Approved Design
      ↓
Deployed Configuration
      ↓
Production Changes
      ↓
Final Production Baseline
```

Any difference must be documented.

---

# 88. Technical Debt Review

Identify technical debt introduced or discovered during implementation.

Potential areas:

- Temporary configuration.
- Workarounds.
- Manual processes.
- Integration limitations.
- Reporting gaps.
- Security improvements.
- Automation opportunities.
- Documentation gaps.
- Architecture improvements.

---

# 89. Enhancement Backlog

Separate defects from enhancements.

Enhancements may include:

- New queues.
- New routing logic.
- Additional integrations.
- Additional digital channels.
- Additional reports.
- AI improvements.
- Knowledge improvements.
- WFM optimisation.
- QM optimisation.

Enhancements should not remain hidden inside the defect backlog.

---

# 90. Lessons Learned

Conduct a structured lessons-learned review.

Review:

- Planning.
- Discovery.
- Architecture.
- Configuration.
- Integration.
- Testing.
- Migration.
- Cutover.
- Production.
- Hypercare.
- Support.

---

# 91. Lessons Learned Categories

Capture:

- What worked.
- What failed.
- What caused delays.
- What caused defects.
- What should be automated.
- What should be standardised.
- What should be added to future projects.
- What should be removed from future projects.

---

# 92. Methodology Feedback

The deployment team should assess whether the master methodology requires updates.

Potential improvements:

- New tasks.
- New dependencies.
- New effort drivers.
- New risks.
- New acceptance criteria.
- New validation scenarios.
- New automation.
- New governance requirements.

This ensures the methodology becomes progressively stronger.

---

# 93. Production Performance Review

Conduct a formal performance review before exiting hypercare.

Review:

- Volume.
- Service level.
- ASA.
- Abandonment.
- AHT.
- ACW.
- Queue performance.
- Agent availability.
- Telephony.
- Integration latency.
- Digital performance.
- Reporting.

Compare actual performance to:

- Baseline.
- Target.
- Design assumptions.

---

# 94. Production Capacity Review

Confirm the platform remains appropriately sized for:

- Current volume.
- Expected growth.
- Peak demand.
- Agent population.
- Integration volume.
- Digital volume.

Identify capacity risks for BAU.

---

# 95. Business KPI Review

Validate agreed business KPIs.

Potential metrics:

- Service level.
- Abandonment.
- AHT.
- FCR.
- Customer satisfaction.
- Agent utilisation.
- Quality score.
- Schedule adherence.
- Digital response time.

---

# 96. Hypercare Exit Reporting

Create a final hypercare report.

Include:

- Go-live date.
- Hypercare duration.
- Incidents.
- Defects.
- Major incidents.
- Root causes.
- Changes.
- Performance.
- Customer experience.
- Agent experience.
- Business KPIs.
- Remaining issues.
- Lessons learned.
- BAU readiness.
- Exit recommendation.

---

# 97. Phase 11 Deliverables

The following deliverables should be produced where applicable:

1. Hypercare operating model.
2. Hypercare support roster.
3. Incident register.
4. Defect register.
5. Problem records.
6. Root-cause analysis.
7. Production monitoring report.
8. Telephony stability report.
9. Routing stability report.
10. Integration stability report.
11. Digital stability report.
12. Recording validation report.
13. Reporting validation report.
14. WFM validation report.
15. QM validation report.
16. Security review.
17. Performance review.
18. Customer experience review.
19. Agent experience review.
20. Supervisor experience review.
21. Data reconciliation report.
22. Configuration drift report.
23. Final production baseline.
24. Updated architecture documentation.
25. Updated operational documentation.
26. Support runbooks.
27. Knowledge transfer records.
28. BAU support readiness assessment.
29. Enhancement backlog.
30. Technical debt register.
31. Lessons learned.
32. Hypercare metrics.
33. Hypercare exit report.
34. Operational acceptance.
35. Business acceptance.
36. Phase 11 acceptance record.

---

# 98. Phase Dependencies

## Inputs

Phase 11 depends on:

**Phase 10 — Production Deployment & Go-Live**

## Outputs

Phase 11 provides:

**Phase 12 — BAU Handover & Project Closure**

---

# 99. Dependency Model

```text
Gate 10
   ↓
Hypercare Activation
   ↓
Production Monitoring
   ↓
Incident / Defect Management
   ↓
Stabilisation
   ↓
Operational Tuning
   ↓
Performance Validation
   ↓
Business Validation
   ↓
Knowledge Transfer
   ↓
Support Readiness
   ↓
Final Production Baseline
   ↓
Hypercare Exit
   ↓
BAU Handover
   ↓
Phase 12
```

---

# 100. Recommended Task Decomposition

The master deployment spreadsheet should break Phase 11 into individual tasks.

Recommended columns:

| Column | Description |
|---|---|
| Task ID | Unique task identifier |
| Phase | Phase number |
| Workstream | Phase 11 workstream |
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

# 101. Recommended Phase 11 Task ID Structure

Use:

```text
P11-001
P11-002
P11-003
```

For workstream-level decomposition:

```text
P11-HC-001
P11-HC-002

P11-MON-001
P11-MON-002

P11-INC-001
P11-INC-002

P11-DEF-001
P11-DEF-002

P11-TEL-001
P11-TEL-002

P11-ROUTE-001
P11-ROUTE-002

P11-ARCH-001
P11-ARCH-002

P11-INT-001
P11-INT-002

P11-DIG-001
P11-DIG-002

P11-WFM-001
P11-WFM-002

P11-QM-001
P11-QM-002

P11-PERF-001
P11-PERF-002

P11-OPS-001
P11-OPS-002

P11-KT-001
P11-KT-002

P11-EXIT-001
P11-EXIT-002
```

---

# 102. Recommended Hypercare Task Sequence

The project schedule should generally follow this dependency sequence:

```text
P11-001
Confirm Gate 10 Approval
        ↓
P11-002
Activate Hypercare Command Centre
        ↓
P11-003
Confirm Support Roster
        ↓
P11-004
Confirm Escalation Paths
        ↓
P11-005
Activate Enhanced Monitoring
        ↓
P11-006
Establish Incident / Defect Baseline
        ↓
P11-007
Review Initial Production Performance
        ↓
P11-008
Monitor Telephony
        ↓
P11-009
Monitor Routing
        ↓
P11-010
Monitor Architect
        ↓
P11-011
Monitor Integrations
        ↓
P11-012
Monitor CRM
        ↓
P11-013
Monitor Digital Channels
        ↓
P11-014
Monitor Recording
        ↓
P11-015
Monitor Reporting
        ↓
P11-016
Monitor WFM / QM
        ↓
P11-017
Monitor Security
        ↓
P11-018
Review Customer Experience
        ↓
P11-019
Review Agent Experience
        ↓
P11-020
Review Supervisor Experience
        ↓
P11-021
Resolve Critical Defects
        ↓
P11-022
Perform Root Cause Analysis
        ↓
P11-023
Implement Approved Stabilisation Changes
        ↓
P11-024
Validate Production Stability
        ↓
P11-025
Update Documentation
        ↓
P11-026
Complete Knowledge Transfer
        ↓
P11-027
Validate BAU Support Readiness
        ↓
P11-028
Create Final Production Baseline
        ↓
P11-029
Review Remaining Defects
        ↓
P11-030
Review Technical Debt
        ↓
P11-031
Review Enhancement Backlog
        ↓
P11-032
Complete Lessons Learned
        ↓
P11-033
Complete Hypercare Exit Assessment
        ↓
P11-034
Obtain Business Acceptance
        ↓
P11-035
Obtain Operational Acceptance
        ↓
P11-036
Approve Hypercare Exit
        ↓
P11-037
Prepare Phase 11 Gate
```

The actual project schedule must be adapted to the deployment architecture, business operating model and hypercare duration.

---

# 103. Effort Estimation Considerations

Phase 11 effort varies significantly based on:

- Hypercare duration.
- Contact volume.
- User population.
- Number of queues.
- Number of channels.
- Number of integrations.
- Telephony complexity.
- Number porting.
- Data migration.
- WFM.
- QM.
- Digital.
- CRM.
- AI / bot capabilities.
- Geographic footprint.
- Support hours.
- Business criticality.
- SLA requirements.

Do not estimate hypercare as a single generic activity.

---

# 104. Effort Drivers

Major effort drivers include:

- Number of agents.
- Number of supervisors.
- Number of queues.
- Interaction volume.
- Peak traffic.
- Number of integrations.
- Number of external systems.
- Telephony architecture.
- Number of DIDs.
- Number of Architect flows.
- Number of Data Actions.
- Number of Data Tables.
- Digital channels.
- WFM.
- QM.
- Reporting complexity.
- Security requirements.
- Support model.
- Vendor dependency.
- Business operating hours.

---

# 105. Critical Path Considerations

Potential critical-path activities include:

- Hypercare activation.
- Critical incident resolution.
- Critical defect resolution.
- Telephony stabilisation.
- Integration stabilisation.
- Routing stabilisation.
- Business acceptance.
- Support readiness.
- Documentation.
- Knowledge transfer.
- Hypercare exit approval.

---

# 106. Required vs Conditional Activities

The master methodology must distinguish between required and conditional activities.

## Generally Required

- Hypercare command centre.
- Production monitoring.
- Incident management.
- Defect management.
- Business feedback.
- Performance review.
- Documentation update.
- Support readiness.
- Hypercare exit assessment.
- Business acceptance.
- Operational acceptance.

## Conditional

- WFM stabilisation.
- QM stabilisation.
- Digital stabilisation.
- CRM stabilisation.
- AI / bot stabilisation.
- Knowledge stabilisation.
- Data reconciliation.
- Vendor escalation.
- Advanced performance analysis.
- Extended support coverage.

## Optional

- Additional optimisation.
- Additional simulation.
- Additional analytics.
- Additional operational tuning.
- Additional training.

---

# 107. Phase 11 Risks

Potential risks include:

### Production Instability

Unexpected production behaviour may continue after go-live.

### Critical Defects

Defects may emerge under real customer volumes.

### Integration Instability

External systems may behave differently under production load.

### Telephony Issues

Carrier or network behaviour may expose issues not seen in testing.

### Routing Issues

Production data may reveal incorrect routing assumptions.

### Customer Experience Degradation

Customer behaviour may differ from test assumptions.

### Agent Adoption Issues

Agents may encounter usability or workflow issues.

### Reporting Differences

Production data may reveal discrepancies in reporting.

### Support Readiness

BAU support may not yet be capable of resolving incidents.

### Hypercare Extension

The service may not meet exit criteria within the planned period.

### Configuration Drift

Production changes may diverge from the approved baseline.

### Technical Debt

Temporary solutions may become permanent without governance.

---

# 108. Risk Mitigation

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

# 109. Hypercare Stability Model

The project should track the progression from high-touch support to normal operation.

```text
GO-LIVE
   ↓
Enhanced Monitoring
   ↓
High-Touch Support
   ↓
Incident Reduction
   ↓
Defect Reduction
   ↓
Performance Stabilisation
   ↓
Operational Acceptance
   ↓
Support Readiness
   ↓
BAU
```

---

# 110. Production Stability Definition

The service should be considered stable when:

- No critical incidents remain open.
- No critical customer-impacting defects remain open.
- Major recurring incidents are understood.
- Telephony is stable.
- Routing is stable.
- Architect is stable.
- Integrations are stable.
- Digital channels are stable where applicable.
- Reporting is stable.
- WFM is stable where applicable.
- QM is stable where applicable.
- Security is stable.
- Monitoring is reliable.
- Support is ready.

---

# 111. Hypercare Exit Definition of Done

Hypercare is ready to exit when:

- Critical incidents are resolved.
- Critical defects are resolved.
- High-priority defects have owners.
- Workarounds are documented.
- Production performance is acceptable.
- Customer experience is acceptable.
- Agent experience is acceptable.
- Supervisor experience is acceptable.
- Telephony is stable.
- Routing is stable.
- Integrations are stable.
- Digital channels are stable where applicable.
- Reporting is accepted.
- WFM is accepted where applicable.
- QM is accepted where applicable.
- Security is accepted.
- Monitoring is operational.
- Documentation is updated.
- Knowledge transfer is complete.
- BAU support is ready.
- Final production baseline is complete.
- Remaining technical debt is documented.
- Enhancement backlog is established.
- Business acceptance is complete.
- Operational acceptance is complete.

---

# 112. Phase 11 Definition of Done

Phase 11 is complete when:

- Gate 10 has been confirmed.
- Hypercare operating model has been activated.
- Production monitoring has been established.
- Production incidents have been managed.
- Production defects have been managed.
- Critical defects have been resolved or formally accepted.
- Major incidents have been reviewed.
- Root-cause analysis has been completed where required.
- Telephony has stabilised.
- Routing has stabilised.
- Architect has stabilised.
- Integrations have stabilised.
- Digital channels have stabilised where applicable.
- Recording has stabilised.
- Reporting has stabilised.
- WFM has stabilised where applicable.
- QM has stabilised where applicable.
- Security has been validated.
- Performance has been reviewed.
- Customer experience has been reviewed.
- Agent experience has been reviewed.
- Supervisor experience has been reviewed.
- Documentation has been updated.
- Knowledge transfer has been completed.
- BAU support readiness has been validated.
- Final production baseline has been created.
- Technical debt has been documented.
- Enhancements have been separated from defects.
- Lessons learned have been captured.
- Hypercare exit criteria have been achieved.
- Business acceptance has been obtained.
- Operational acceptance has been obtained.
- Phase 11 Gate has been passed.

---

# 113. Phase 11 Governance

Phase 11 should have formal governance events.

Recommended meetings:

- Hypercare activation.
- Daily production review.
- Daily incident review.
- Daily defect review.
- Weekly stability review.
- Business KPI review.
- Technical performance review.
- Support readiness review.
- Knowledge transfer review.
- Hypercare exit readiness review.
- Business acceptance.
- Operational acceptance.
- Phase gate review.

---

# 114. Hypercare Daily Governance

Daily governance should review:

```text
Production Health
      ↓
Incidents
      ↓
Defects
      ↓
Customer Impact
      ↓
Agent Impact
      ↓
Telephony
      ↓
Routing
      ↓
Integrations
      ↓
Digital
      ↓
Reporting
      ↓
WFM / QM
      ↓
Security
      ↓
Performance
      ↓
Actions
      ↓
Risks
```

---

# 115. Hypercare Reporting

Track:

- Incident trend.
- Defect trend.
- Severity.
- Resolution times.
- Customer impact.
- Agent impact.
- Telephony.
- Routing.
- Integrations.
- Digital.
- Reporting.
- WFM.
- QM.
- Security.
- Performance.
- BAU readiness.

---

# 116. Production Health Dashboard

Maintain a live health dashboard.

Example:

```text
                PRODUCTION HEALTH

Overall Service       [ GREEN ]
Telephony             [ GREEN ]
Routing               [ GREEN ]
Architect             [ GREEN ]
Integrations          [ GREEN ]
CRM                   [ GREEN ]
Digital               [ GREEN ]
Recording             [ GREEN ]
Reporting             [ GREEN ]
WFM                   [ GREEN ]
QM                    [ GREEN ]
Security              [ GREEN ]
Performance           [ GREEN ]
Customer Experience   [ GREEN ]
Agent Experience      [ GREEN ]
Support Readiness     [ GREEN ]
Documentation         [ GREEN ]
BAU Readiness         [ GREEN ]
```

Any Amber or Red item requires:

- Owner.
- Action.
- Target date.
- Escalation where required.

---

# 117. Final Production Baseline

The final production baseline must include:

- Genesys Cloud organisation.
- Region.
- Divisions.
- Users.
- Roles.
- Queues.
- Skills.
- Languages.
- Architect flows.
- Schedules.
- Business hours.
- Holiday schedules.
- Telephony.
- Numbers.
- Integrations.
- Data Actions.
- Data Tables.
- Recording.
- Digital channels.
- Reporting.
- WFM.
- QM.
- Security.
- Monitoring.

---

# 118. Final Configuration Audit

Compare:

```text
Phase 04
Approved Architecture
        ↓
Phase 05
Foundation
        ↓
Phase 06
Configuration
        ↓
Phase 07
Integration
        ↓
Phase 08
Testing
        ↓
Phase 09
Cutover Baseline
        ↓
Phase 10
Production
        ↓
Phase 11
Final Production Baseline
```

All material deviations must be documented.

---

# 119. BAU Readiness Assessment

Assess BAU readiness across:

| Area | Status |
|---|---|
| Platform Administration | Ready / Not Ready |
| User Administration | Ready / Not Ready |
| Queue Administration | Ready / Not Ready |
| Routing | Ready / Not Ready |
| Architect | Ready / Not Ready |
| Telephony | Ready / Not Ready |
| Integrations | Ready / Not Ready |
| Digital | Ready / Not Ready |
| Recording | Ready / Not Ready |
| Reporting | Ready / Not Ready |
| WFM | Ready / Not Ready |
| QM | Ready / Not Ready |
| Security | Ready / Not Ready |
| Monitoring | Ready / Not Ready |
| Incident Management | Ready / Not Ready |
| Vendor Escalation | Ready / Not Ready |
| Documentation | Ready / Not Ready |
| Knowledge Transfer | Ready / Not Ready |

---

# 120. Phase 11 Completion Record

The project should retain a formal hypercare completion record containing:

- Project name.
- Customer.
- Genesys Cloud organisation.
- Production region.
- Go-live date.
- Hypercare start.
- Hypercare end.
- Hypercare duration.
- Incident summary.
- Defect summary.
- Major incident summary.
- Performance summary.
- Customer experience summary.
- Agent experience summary.
- Operational readiness.
- Support readiness.
- Final production baseline.
- Technical debt.
- Enhancement backlog.
- Lessons learned.
- Business acceptance.
- Operational acceptance.
- Hypercare exit decision.
- Phase 11 gate decision.

---

# 121. Phase Gate — Gate 11: Hypercare & Stabilisation Complete

## Gate Objective

Confirm that the Genesys Cloud production environment has stabilised, that remaining issues are controlled, that operational support is ready, and that the service can transition from project-led hypercare into formal BAU handover.

---

# 122. Gate 11 Entry Criteria

The following must be true:

- Gate 10 passed.
- Production service is live.
- Hypercare operating model is active.
- Monitoring is active.
- Incident management is active.
- Defect management is active.

---

# 123. Gate 11 Exit Criteria

## Production Stability

- Telephony stable.
- Routing stable.
- Architect stable.
- Integrations stable.
- Digital stable where applicable.
- Recording stable.
- Reporting stable.
- WFM stable where applicable.
- QM stable where applicable.
- Security stable.
- Performance acceptable.

## Operational Stability

- Incident trend acceptable.
- No unresolved critical incidents.
- Critical defects resolved or formally accepted.
- Remaining defects have owners.
- Remaining defects have target dates.
- Workarounds documented.
- Monitoring operational.
- Support model operational.

## Business Acceptance

- Customer experience acceptable.
- Agent experience acceptable.
- Supervisor experience acceptable.
- Business KPIs acceptable.
- Business owner accepts transition.

## BAU Readiness

- Documentation updated.
- Knowledge transfer complete.
- Support teams trained.
- Escalation model validated.
- Vendor support process confirmed.
- Final production baseline complete.
- Technical debt documented.
- Enhancement backlog created.

---

# 124. Gate Decision

The Phase 11 gate must result in one of:

```text
PASS
```

The service has stabilised and is ready for formal BAU handover.

```text
PASS WITH CONDITIONS
```

The service is stable enough to proceed, with accepted residual issues transferred into BAU.

```text
EXTEND HYPERCARE
```

The service requires additional project-led support.

```text
HOLD
```

The service is not sufficiently stable to proceed to BAU handover.

---

# 125. Phase 11 Outputs to Phase 12

Phase 11 provides Phase 12 with:

```text
Stable Production Service
        +
Final Production Baseline
        +
Resolved Critical Defects
        +
Controlled Open Issues
        +
Operational Documentation
        +
Knowledge Transfer
        +
Support Readiness
        +
Business Acceptance
        +
Operational Acceptance
        +
Technical Debt Register
        +
Enhancement Backlog
        +
Lessons Learned
        +
Hypercare Exit Approval
        ↓
Phase 12 — BAU Handover & Project Closure
```

---

# 126. Layer 1 Position

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
| **10 — Production Deployment & Go-Live** | Defined |
| **11 — Hypercare & Stabilisation** | **Defined** |
| 12 — BAU Handover & Project Closure | Next |

---

# 127. Phase 11 Summary

Phase 11 is the controlled transition from a live production deployment into a stable operational service.

The project must demonstrate:

```text
Production Service
        ↓
Enhanced Monitoring
        ↓
Incident / Defect Management
        ↓
Root Cause Analysis
        ↓
Stabilisation
        ↓
Operational Tuning
        ↓
Production Performance Validation
        ↓
Business Validation
        ↓
Documentation
        ↓
Knowledge Transfer
        ↓
BAU Support Readiness
        ↓
Final Production Baseline
        ↓
Hypercare Exit
        ↓
Phase 12 — BAU Handover & Project Closure
```

The objective is not simply to reduce the number of production incidents.

The objective is to establish a repeatable and supportable operational service that:

- Performs acceptably under real production conditions.
- Supports customers.
- Supports agents.
- Supports supervisors.
- Operates securely.
- Integrates reliably with enterprise systems.
- Produces reliable operational reporting.
- Supports WFM and QM where applicable.
- Has appropriate monitoring.
- Has a defined support model.
- Has documented operational procedures.
- Has known issues under control.
- Has clear ownership.
- Has an agreed BAU operating model.

The formal completion point is:

**Gate 11 — Hypercare & Stabilisation Complete**

---

# 128. Phase 11 Handover to Phase 12

Phase 12 should not begin until Phase 11 has established a stable operational baseline.

Phase 12 will use the outputs of Phase 11 to complete:

- Formal BAU ownership.
- Final support handover.
- Final documentation acceptance.
- Project deliverable acceptance.
- Contractual closure.
- Commercial closure.
- Outstanding issue transfer.
- Final project reporting.
- Lessons learned.
- Project closure.

The transition should therefore be:

```text
Phase 10
Production Deployment
        ↓
Phase 11
Hypercare & Stabilisation
        ↓
Stable Operational Baseline
        ↓
Phase 12
BAU Handover & Project Closure
```

---

# Phase Completion

**Phase:** 11 — Hypercare & Stabilisation

**Previous Phase:** 10 — Production Deployment & Go-Live

**Next Phase:** 12 — BAU Handover & Project Closure

**Phase Gate:** Gate 11 — Hypercare & Stabilisation Complete

**Primary Outcome:** A stable, validated, documented and operationally supportable Genesys Cloud production service ready for formal BAU handover and project closure.
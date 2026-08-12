# Phase 12 — BAU Handover & Project Closure

## 1. Purpose

Phase 12 is the final phase of the Genesys Cloud deployment methodology.

It provides the controlled transition from project-led hypercare into the customer's normal Business-as-Usual (BAU) operating model and formally closes the implementation project.

Phase 12 begins after:

- Phase 11 — Hypercare & Stabilisation
- Gate 11 approval
- Production stabilisation
- Business acceptance
- Operational acceptance
- Hypercare exit

The purpose of this phase is to ensure that the customer has full operational ownership of the Genesys Cloud environment and that all project obligations, documentation, knowledge transfer, governance, commercial, contractual, financial and administrative activities have been completed.

The project is not considered complete simply because the platform is operational.

The project is complete when:

- The service has an identified BAU owner.
- Support teams are ready.
- Operational processes are established.
- Documentation is accepted.
- Configuration is baselined.
- Infrastructure and integrations are handed over.
- Security and access ownership is transferred.
- Vendor and support arrangements are confirmed.
- Outstanding defects are formally transferred or closed.
- Technical debt is documented.
- Enhancements are separated from project scope.
- Project deliverables are accepted.
- Commercial obligations are complete.
- Financial closure is complete.
- Lessons learned are captured.
- Benefits are established for ongoing measurement.
- All required project sign-offs have been obtained.
- The project is formally closed.

The output of Phase 12 is a **fully operational Genesys Cloud service under BAU ownership and a formally closed implementation project**.

---

# 2. Phase Objective

By the end of Phase 12:

- BAU ownership is formally established.
- Service management ownership is transferred.
- Operational support is ready.
- Documentation is complete and accepted.
- Configuration baselines are handed over.
- Terraform / Infrastructure as Code is handed over where applicable.
- Source repositories are transferred or ownership is confirmed.
- Integrations are handed over.
- Telephony is handed over.
- Architect is handed over.
- Digital channels are handed over.
- Recording is handed over.
- WFM is handed over where applicable.
- QM is handed over where applicable.
- Reporting is handed over.
- Monitoring is handed over.
- Security administration is handed over.
- Incident management is operational.
- Problem management is operational.
- Change management is operational.
- Disaster recovery documentation is complete.
- Business continuity requirements are documented.
- Vendor support arrangements are confirmed.
- Licensing and subscriptions are reconciled.
- Open defects have been closed or formally transferred.
- Technical debt has been documented.
- Enhancements have been transferred to the BAU roadmap.
- Contractual obligations are complete.
- Commercial closure is complete.
- Project financials are closed.
- Lessons learned are complete.
- Benefits realisation measures are established.
- Final project acceptance is obtained.
- Project closure is approved.
- Gate 12 is passed.

---

# 3. Phase Position

The complete Layer 1 deployment lifecycle is:

```text
Phase 01
Project Initiation & Mobilisation
        ↓
Phase 02
Discovery & Current-State Assessment
        ↓
Phase 03
Requirements & Solution Definition
        ↓
Phase 04
Solution Architecture & Detailed Design
        ↓
Phase 05
Platform Foundation & Environment Build
        ↓
Phase 06
Feature Configuration & Solution Build
        ↓
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
        ↓
LAYER 1 COMPLETE
```

Phase 12 is the final project phase in Layer 1.

---

# 4. Phase Entry Criteria

Phase 12 must not commence until the following have been achieved or formally accepted.

## Required

1. Gate 11 has passed.
2. Hypercare exit has been approved.
3. Production service is stable.
4. Critical production incidents are resolved.
5. Critical defects are resolved or formally accepted.
6. Remaining issues have owners.
7. Remaining issues have target dates.
8. BAU support model is defined.
9. Operational owner is identified.
10. Service owner is identified.
11. Business owner is identified.
12. Documentation has reached an acceptable state.
13. Knowledge transfer has been completed or scheduled for final completion.
14. Final production baseline has been created.
15. Business acceptance has been obtained.
16. Operational acceptance has been obtained.

Exceptions must be documented and approved.

---

# 5. Phase Workstreams

The master deployment methodology should structure Phase 12 into the following workstreams:

### 12.01 BAU Ownership & Governance
### 12.02 Service Management Handover
### 12.03 Operational Support Handover
### 12.04 Technical Documentation Handover
### 12.05 Architecture Baseline Handover
### 12.06 Genesys Cloud Administration Handover
### 12.07 User & Access Management Handover
### 12.08 Security Handover
### 12.09 Telephony & Carrier Handover
### 12.10 Architect Handover
### 12.11 Routing Handover
### 12.12 Integration Handover
### 12.13 CRM Handover
### 12.14 Digital Channel Handover
### 12.15 Recording Handover
### 12.16 WFM Handover
### 12.17 QM Handover
### 12.18 Reporting & Analytics Handover
### 12.19 Monitoring & Alerting Handover
### 12.20 Terraform / IaC Handover
### 12.21 Automation Handover
### 12.22 Repository & Source Control Handover
### 12.23 Incident / Problem / Change Management
### 12.24 Disaster Recovery & Business Continuity
### 12.25 Vendor & Support Handover
### 12.26 Licensing & Subscription Reconciliation
### 12.27 Outstanding Defect Transfer
### 12.28 Technical Debt Transfer
### 12.29 Enhancement Backlog Transfer
### 12.30 Documentation Acceptance
### 12.31 Knowledge Transfer
### 12.32 Business Acceptance
### 12.33 Commercial & Contractual Closure
### 12.34 Financial Closure
### 12.35 Benefits Realisation
### 12.36 Lessons Learned
### 12.37 Project Metrics
### 12.38 Final Project Acceptance
### 12.39 Project Closure
### 12.40 Phase Gate 12

Not every workstream applies to every project.

Each activity must be classified as:

- Required
- Conditional
- Optional
- Not Applicable

---

# 6. Phase 12 Operating Principles

The following principles apply:

1. BAU ownership must be explicit.
2. Every operational responsibility must have an owner.
3. Documentation must reflect the actual production state.
4. The production configuration must be baselined.
5. Project-only processes must not remain as undocumented BAU dependencies.
6. Remaining issues must be formally transferred.
7. Defects must be separated from enhancements.
8. Technical debt must be visible.
9. Security ownership must be transferred.
10. Vendor support arrangements must be understood.
11. Support teams must have sufficient knowledge.
12. Operational procedures must be executable without the project team.
13. Infrastructure as Code must be preserved where applicable.
14. Source repositories must have an identified owner.
15. Access credentials and secrets must not remain under project-team ownership.
16. Commercial obligations must be closed.
17. Financial obligations must be reconciled.
18. Project lessons learned must feed the deployment methodology.
19. Benefits must have an owner.
20. Closure must be evidence-based.

---

# 7. BAU Ownership Model

Define the permanent ownership model.

At minimum identify:

- Business Owner.
- Service Owner.
- Product Owner.
- Genesys Cloud Platform Owner.
- Application Support Owner.
- Technical Support Owner.
- Telephony Owner.
- Integration Owner.
- Security Owner.
- IAM Owner.
- Reporting Owner.
- WFM Owner.
- QM Owner.
- Vendor Manager.
- Service Desk Owner.

Not every organisation requires every role.

---

# 8. Responsibility Matrix

Create the final BAU responsibility matrix.

Example:

| Capability | Business Owner | Platform Owner | Technical Support | Service Desk | Vendor |
|---|---|---|---|---|---|
| Users | A | R | C | C | I |
| Queues | A | R | C | I | C |
| Routing | A | R | C | I | C |
| Architect | A | R | C | I | C |
| Telephony | A | C | R | I | C |
| Integrations | A | C | R | I | C |
| Security | A | C | R | I | C |
| Reporting | A | R | C | I | C |
| WFM | A | R | C | I | C |
| QM | A | R | C | I | C |

Use the customer's approved RACI model where one exists.

---

# 9. BAU Governance

Confirm:

- Platform governance board.
- Change authority.
- Security governance.
- Architecture governance.
- Vendor governance.
- Service management governance.
- Reporting governance.
- Business ownership.

Define:

- Meeting frequency.
- Participants.
- Decision rights.
- Escalation.
- Reporting.

---

# 10. Service Management Handover

Transition the solution into the customer's service management framework.

Validate:

- Service record.
- Application record.
- Configuration Management Database (CMDB) entry where applicable.
- Support groups.
- Assignment groups.
- Incident categories.
- Problem categories.
- Change categories.
- Request categories.
- Service levels.
- Escalation paths.

---

# 11. Service Desk Handover

The Service Desk must understand:

- What Genesys Cloud is.
- What the supported service includes.
- Common incidents.
- First-line troubleshooting.
- User provisioning process.
- Access issues.
- Telephony issues.
- Integration issues.
- Escalation criteria.
- Vendor escalation process.

---

# 12. Service Desk Knowledge Articles

Create or validate knowledge articles for:

- Login problems.
- SSO problems.
- Agent desktop problems.
- Audio problems.
- Call failures.
- Queue issues.
- Missing permissions.
- CRM integration issues.
- Digital channel issues.
- Reporting issues.
- WFM issues.
- QM issues.

---

# 13. Application Support Handover

Application support must receive:

- Architecture.
- Configuration.
- Integration documentation.
- Troubleshooting.
- Monitoring.
- Logging.
- Error handling.
- Known issues.
- Escalation.

---

# 14. Genesys Cloud Administration Handover

Transfer administration knowledge covering:

- Organisation administration.
- Divisions.
- Users.
- Groups.
- Roles.
- Permissions.
- Queues.
- Skills.
- Languages.
- Locations.
- Sites.
- Work teams.
- Schedules.
- Business units where applicable.

---

# 15. User Administration Handover

Define BAU processes for:

- Joiners.
- Movers.
- Leavers.
- Role changes.
- Queue changes.
- Skill changes.
- Supervisor changes.
- Division changes.
- Access reviews.

---

# 16. Security Handover

Transfer security responsibilities covering:

- SSO.
- MFA.
- Identity provider.
- OAuth.
- Roles.
- Permissions.
- Divisions.
- API clients.
- Service accounts.
- Integration credentials.
- Secrets.
- Audit logs.

---

# 17. Privileged Access Review

Before project closure:

1. Identify project team access.
2. Identify temporary accounts.
3. Identify temporary administrative permissions.
4. Identify temporary OAuth clients.
5. Remove unnecessary access.
6. Confirm BAU administrative access.
7. Record evidence.

---

# 18. Security Baseline

Confirm the final security baseline.

Capture:

- Admin roles.
- User roles.
- OAuth clients.
- SSO configuration.
- MFA requirements.
- Security policies.
- Session policies.
- Audit requirements.
- Data access.
- Recording access.
- API access.

---

# 19. Telephony Handover

Transfer ownership of:

- Phone numbers.
- DID ranges.
- Toll-free numbers.
- SIP trunks where applicable.
- Carrier relationships.
- BYOC configuration.
- Sites.
- Locations.
- Edge devices where applicable.
- Number plans.
- Outbound routes.
- Caller ID.
- Emergency services configuration.

---

# 20. Carrier Handover

Document:

- Carrier.
- Account.
- Support contact.
- Service identifiers.
- Number inventory.
- Escalation path.
- SLA.
- Contract details.
- Billing responsibility.
- Porting history.
- Future porting process.

---

# 21. Telephony Troubleshooting

Provide BAU support with procedures for:

- No audio.
- One-way audio.
- Dropped calls.
- Failed outbound calls.
- Failed inbound calls.
- Incorrect caller ID.
- Incorrect DNIS.
- Number routing.
- Carrier failures.
- Network-related voice issues.

---

# 22. Architect Handover

Transfer ownership of:

- Inbound call flows.
- Inbound chat flows.
- Inbound message flows.
- Inbound email flows.
- Outbound flows.
- In-queue flows.
- Secure flows.
- Bot flows.
- Survey flows.
- Common modules.
- Reusable components.

---

# 23. Architect Repository

Where applicable provide:

- Flow inventory.
- Flow purpose.
- Flow owner.
- Version.
- Dependencies.
- Data Actions.
- Data Tables.
- Prompts.
- Architect schedules.
- Business hours.
- Holiday schedules.

---

# 24. Architect Change Management

Define the BAU process for:

- Flow changes.
- Versioning.
- Testing.
- Approval.
- Publishing.
- Rollback.
- Emergency changes.

---

# 25. Routing Handover

Document:

- Queues.
- Skills.
- Languages.
- Bullseye routing.
- Priority.
- Preferred agents.
- Routing methods.
- Queue membership.
- Overflow.
- In-queue handling.
- Callback.
- Transfer behaviour.

---

# 26. Routing Ownership

Identify who can approve:

- Queue changes.
- Skill changes.
- Routing changes.
- Priority changes.
- Overflow changes.
- Agent membership changes.

---

# 27. Integration Handover

For each integration provide:

- System.
- Purpose.
- Owner.
- Endpoint.
- Authentication.
- Data flow.
- Dependencies.
- Failure handling.
- Retry.
- Timeout.
- Monitoring.
- Logging.
- Support process.

---

# 28. Integration Inventory

The final integration inventory should include:

| Integration | Purpose | Owner | Authentication | Monitoring | Support |
|---|---|---|---|---|---|
| CRM | Customer interaction | Application Owner | OAuth / API | Required | Application Support |
| Middleware | Data exchange | Integration Team | API | Required | Integration Support |
| IAM | Identity | Security | SSO | Required | IAM |
| WFM | Workforce | WFM | API | Required | WFM |
| QM | Quality | QM | API | Required | QM |

The actual project inventory must be used.

---

# 29. CRM Handover

Where applicable document:

- Embedded client.
- Screen pop.
- Customer lookup.
- Case creation.
- Interaction logging.
- Disposition.
- Recording links.
- Authentication.
- CRM APIs.
- Error handling.
- Support ownership.

---

# 30. Digital Channel Handover

Where applicable transfer:

- Web messaging.
- Web chat.
- Email.
- SMS.
- Social messaging.
- Open messaging.

Document:

- Routing.
- Queue.
- Architect flow.
- Bot.
- Agent handling.
- Escalation.
- Reporting.

---

# 31. Recording Handover

Document:

- Recording policies.
- Retention.
- Storage.
- Access.
- Permissions.
- Playback.
- Export.
- Secure pause.
- Recording retrieval.
- Compliance requirements.

---

# 32. Recording Compliance

Confirm BAU owners understand:

- Who can access recordings.
- Who can export recordings.
- Retention obligations.
- Deletion requirements.
- Legal hold process.
- Privacy requirements.
- Audit requirements.

---

# 33. WFM Handover

Where WFM is in scope transfer:

- Business units.
- Management units.
- Planning groups.
- Forecasting.
- Scheduling.
- Time-off.
- Adherence.
- Intraday management.
- WFM integrations.
- WFM reporting.

---

# 34. WFM Operational Ownership

Identify ownership for:

- Forecasting.
- Scheduling.
- Staffing.
- Intraday management.
- Adherence.
- Configuration.
- WFM reporting.

---

# 35. QM Handover

Where QM is in scope transfer:

- Evaluation forms.
- Evaluation policies.
- Quality management.
- Recording access.
- Evaluations.
- Calibration.
- Coaching.
- Quality reporting.

---

# 36. Reporting Handover

Transfer ownership of:

- Standard reports.
- Custom reports.
- Dashboards.
- Analytics views.
- Business KPIs.
- Scheduled reports.
- Data exports.
- Reporting integrations.

---

# 37. Reporting Documentation

For critical reports document:

- Report name.
- Purpose.
- Owner.
- Data source.
- Filters.
- Calculation.
- Refresh.
- Distribution.
- KPI definition.
- Support process.

---

# 38. Monitoring Handover

Transfer:

- Monitoring dashboards.
- Alerts.
- Thresholds.
- Notifications.
- Log access.
- Incident triggers.
- Integration monitoring.
- Telephony monitoring.
- Performance monitoring.

---

# 39. Monitoring Ownership

For each alert identify:

- Alert.
- Trigger.
- Severity.
- Owner.
- Notification method.
- Response process.
- Escalation.
- Resolution.

---

# 40. Terraform / Infrastructure as Code Handover

Where Terraform is used, transfer:

- Terraform repository.
- Modules.
- Environments.
- Variables.
- Variable definitions.
- State management.
- Backend configuration.
- Pipeline.
- CI/CD.
- Secrets.
- Provider configuration.
- Version constraints.
- Documentation.

---

# 41. Terraform State Handover

Confirm:

- State is stored in the approved backend.
- Access is controlled.
- Locking is enabled where appropriate.
- State is backed up.
- Secrets are not exposed.
- BAU administrators can execute approved workflows.
- Project-team-only dependencies are removed.

---

# 42. Terraform Change Process

Document:

```text
Change Request
      ↓
Code Change
      ↓
Pull Request
      ↓
Review
      ↓
Validation
      ↓
Plan
      ↓
Approval
      ↓
Apply
      ↓
Validation
      ↓
Evidence
```

---

# 43. Repository Handover

Transfer or confirm ownership of:

- Terraform repository.
- Integration source.
- Scripts.
- Automation.
- Documentation.
- Configuration repositories.
- CI/CD pipelines.

---

# 44. Source Control Review

Confirm:

- Repository owner.
- Administrators.
- Contributors.
- Branch protection.
- Pull request rules.
- Secrets.
- Service accounts.
- CI/CD credentials.
- Webhooks.
- Deployment pipelines.

---

# 45. Automation Handover

Where automation has been implemented:

- Identify automation.
- Document purpose.
- Document trigger.
- Document dependencies.
- Document credentials.
- Document monitoring.
- Document failure handling.
- Document ownership.

---

# 46. Incident Management Handover

The BAU process must define:

- Incident logging.
- Severity.
- Prioritisation.
- Assignment.
- Escalation.
- Communication.
- Resolution.
- Closure.

---

# 47. Problem Management Handover

Define the BAU process for recurring problems:

1. Identify trend.
2. Create problem record.
3. Investigate root cause.
4. Identify permanent fix.
5. Approve change.
6. Implement.
7. Validate.
8. Monitor.
9. Close.

---

# 48. Change Management Handover

All future production changes must follow the customer's change process.

Define:

- Standard changes.
- Normal changes.
- Emergency changes.
- Approval.
- Testing.
- Implementation.
- Rollback.
- Evidence.

---

# 49. Disaster Recovery

Confirm the BAU team understands:

- Recovery requirements.
- Recovery objectives.
- Dependencies.
- Critical integrations.
- Critical data.
- Recovery procedures.
- Vendor dependencies.
- Communication process.

---

# 50. Business Continuity

Document the operational response to:

- Genesys Cloud service interruption.
- Carrier outage.
- Internet outage.
- Identity provider outage.
- CRM outage.
- Integration outage.
- Workforce system outage.
- Power/network outage.
- Major cyber event.

---

# 51. DR / BC Testing

Where required:

- Review existing DR tests.
- Review results.
- Confirm outstanding actions.
- Confirm BAU test ownership.
- Confirm testing cadence.

---

# 52. Vendor Handover

Confirm:

- Vendor contracts.
- Support contracts.
- Support portal.
- Support contacts.
- Escalation.
- Service levels.
- Contract owner.
- Renewal date.
- Commercial owner.

---

# 53. Genesys Support Handover

Confirm the customer knows:

- How to raise support cases.
- What information to provide.
- Severity classification.
- Escalation process.
- Support hours.
- Contractual support level.

---

# 54. Licensing Reconciliation

Confirm final:

- Licences.
- Users.
- Concurrent usage where applicable.
- WFM licences.
- QM licences.
- Digital licences.
- Add-ons.
- AI capabilities.
- Other subscriptions.

---

# 55. Subscription Reconciliation

Compare:

```text
Contracted
    ↓
Provisioned
    ↓
Configured
    ↓
Assigned
    ↓
Consumed
```

Investigate discrepancies.

---

# 56. Outstanding Defects

All remaining defects must be classified.

Possible outcomes:

```text
CLOSED
    ↓
ACCEPTED WITH WORKAROUND
    ↓
TRANSFERRED TO BAU
    ↓
TRANSFERRED TO VENDOR
    ↓
CONVERTED TO ENHANCEMENT
```

No defect should remain without an owner.

---

# 57. Defect Transfer

For each transferred defect record:

- Defect ID.
- Description.
- Impact.
- Severity.
- Current state.
- Workaround.
- Root cause.
- Owner.
- Target date.
- Next action.
- Business acceptance.

---

# 58. Technical Debt

Create the final technical debt register.

Potential examples:

- Temporary configuration.
- Manual process.
- Hard-coded integration.
- Missing automation.
- Reporting workaround.
- Legacy dependency.
- Architecture limitation.
- Security improvement.
- Documentation gap.

---

# 59. Technical Debt Ownership

Every technical debt item must have:

- Owner.
- Priority.
- Business impact.
- Technical impact.
- Target resolution.
- Funding requirement where applicable.

---

# 60. Enhancement Backlog

Separate enhancements from defects.

Enhancements may include:

- Additional queues.
- Additional routing.
- New digital channels.
- Additional integrations.
- AI enhancements.
- Bot optimisation.
- Knowledge improvements.
- Reporting enhancements.
- WFM optimisation.
- QM optimisation.
- Additional automation.

---

# 61. Enhancement Governance

Transfer enhancements into the customer's:

- Product backlog.
- Technology roadmap.
- Change backlog.
- Continuous improvement program.

The implementation project must not remain accountable for post-project enhancements unless contractually agreed.

---

# 62. Documentation Handover

Perform a complete documentation audit.

Review:

- Project documentation.
- Architecture.
- Detailed design.
- Configuration.
- Integrations.
- Telephony.
- Architect.
- Security.
- Reporting.
- WFM.
- QM.
- Operations.
- Support.
- DR.
- BC.
- Troubleshooting.
- Known issues.

---

# 63. Documentation Acceptance

Each required document should have:

- Owner.
- Version.
- Date.
- Status.
- Approver.
- Repository.
- BAU owner.

---

# 64. Documentation Baseline

Create a final documentation baseline.

Example:

```text
01-Architecture
02-Design
03-Configuration
04-Telephony
05-Architect
06-Integrations
07-Security
08-Operations
09-Monitoring
10-Support
11-DR-BC
12-Reporting
13-WFM
14-QM
15-Known-Issues
16-Runbooks
17-Project-Closure
```

The actual repository structure should follow the customer's standards.

---

# 65. Knowledge Transfer

Complete final knowledge transfer.

Knowledge transfer must include:

- Platform.
- Configuration.
- Administration.
- Telephony.
- Routing.
- Architect.
- Integrations.
- Digital.
- Recording.
- WFM.
- QM.
- Reporting.
- Security.
- Monitoring.
- Support.

---

# 66. Knowledge Transfer Evidence

Capture:

- Session.
- Date.
- Attendees.
- Topics.
- Presenter.
- Materials.
- Questions.
- Outstanding actions.
- Acceptance.

---

# 67. Operational Readiness Sign-Off

The operational owner signs off that:

- Documentation is sufficient.
- Support is trained.
- Monitoring is operational.
- Incident process is operational.
- Escalation is understood.
- BAU ownership is clear.

---

# 68. Business Acceptance

Obtain formal business acceptance confirming:

- Requirements have been delivered.
- Production service is acceptable.
- Business KPIs are acceptable.
- Customer experience is acceptable.
- Agent experience is acceptable.
- Reporting is acceptable.
- Remaining issues are accepted.

---

# 69. Technical Acceptance

Technical acceptance confirms:

- Architecture is complete.
- Configuration is complete.
- Integrations are complete.
- Telephony is complete.
- Security is complete.
- Monitoring is complete.
- Documentation is complete.
- Source control is complete.
- Automation is complete.

---

# 70. Security Acceptance

Security acceptance confirms:

- Access is appropriate.
- Privileged access is controlled.
- IAM integration is operational.
- OAuth clients are controlled.
- Secrets are protected.
- Audit requirements are met.
- Security documentation is complete.

---

# 71. Commercial Closure

Review:

- Statement of Work.
- Change Requests.
- Variations.
- Deliverables.
- Milestones.
- Acceptance criteria.
- Invoicing.
- Expenses.
- Credits.
- Outstanding commercial obligations.

---

# 72. Contractual Closure

Confirm:

- All contracted deliverables complete.
- All acceptance criteria met.
- Outstanding contractual items documented.
- Warranty/support period understood.
- Support commencement date confirmed.
- Contract change process established.

---

# 73. Financial Closure

Review:

- Project budget.
- Actual spend.
- Forecast.
- Variances.
- Purchase orders.
- Invoices.
- Contractor costs.
- Vendor costs.
- Outstanding commitments.

---

# 74. Financial Reconciliation

The project manager and financial owner should confirm:

```text
Budget
   ↓
Committed
   ↓
Invoiced
   ↓
Paid
   ↓
Outstanding
   ↓
Final Forecast
```

---

# 75. Project Resource Closure

Release project resources where appropriate.

Review:

- Internal staff.
- Contractors.
- Vendors.
- Consultants.
- Temporary accounts.
- Project distribution lists.
- Project communication channels.

---

# 76. Access Closure

Remove project-only access from:

- Genesys Cloud.
- Identity provider.
- GitHub / GitLab / source control.
- Terraform.
- CI/CD.
- Monitoring.
- Ticketing.
- Documentation.
- Vendor portals.
- Customer systems.

Do not remove access required for ongoing contractual support.

---

# 77. Project Repository Closure

Archive project-specific repositories and artifacts where appropriate.

Confirm:

- Final version.
- Ownership.
- Retention.
- Access.
- Archive location.
- Reference process.

---

# 78. Project Data Retention

Confirm retention requirements for:

- Project documentation.
- Test evidence.
- Acceptance records.
- Security evidence.
- Configuration.
- Change records.
- Incident records.
- Migration records.
- Meeting records.

---

# 79. Audit Evidence

Create a final evidence index.

Potential evidence:

- Requirements.
- Design approvals.
- Test results.
- UAT acceptance.
- Cutover approval.
- Go-live approval.
- Hypercare exit.
- Business acceptance.
- Operational acceptance.
- Security approval.
- Documentation acceptance.
- Final project acceptance.

---

# 80. Compliance Closure

Where applicable confirm:

- Privacy.
- Recording.
- Data retention.
- Security.
- Regulatory requirements.
- Audit evidence.
- Data residency.
- Access control.

---

# 81. Lessons Learned

Conduct a final project lessons-learned workshop.

Review:

- Initiation.
- Discovery.
- Requirements.
- Architecture.
- Build.
- Integration.
- Testing.
- Migration.
- Cutover.
- Go-live.
- Hypercare.
- Handover.

---

# 82. Lessons Learned Categories

Capture:

- What worked.
- What did not work.
- What should change.
- What should be standardised.
- What should be automated.
- What should be removed.
- What created unnecessary effort.
- What created unexpected risk.
- What should become a mandatory gate.

---

# 83. Methodology Improvement

Feed lessons learned back into the master Genesys Cloud deployment methodology.

Potential updates:

- New tasks.
- New dependencies.
- New risks.
- New deliverables.
- New acceptance criteria.
- New templates.
- New automation.
- New effort drivers.
- New quality gates.

This ensures every project improves the reusable deployment methodology.

---

# 84. Benefits Realisation

The project must establish how benefits will be measured after closure.

Potential benefits:

- Reduced AHT.
- Improved service level.
- Reduced abandonment.
- Improved FCR.
- Improved customer satisfaction.
- Improved agent experience.
- Improved supervisor visibility.
- Reduced operational cost.
- Improved automation.
- Improved digital adoption.
- Improved reporting.
- Improved workforce efficiency.
- Improved quality.

---

# 85. Benefits Ownership

Each benefit must have:

- Benefit.
- Baseline.
- Target.
- Measurement.
- Owner.
- Review date.
- Reporting mechanism.

---

# 86. Benefits Tracking

Benefits realisation is generally a BAU responsibility after project closure.

The project must therefore establish:

- Baseline.
- Target.
- Measurement method.
- Reporting owner.
- Review cadence.

---

# 87. Project Performance Review

Review project performance against:

- Schedule.
- Budget.
- Scope.
- Quality.
- Risks.
- Issues.
- Change requests.
- Defects.
- Customer satisfaction.
- Benefits.

---

# 88. Project KPI Review

Capture:

- Planned duration.
- Actual duration.
- Planned effort.
- Actual effort.
- Planned cost.
- Actual cost.
- Number of change requests.
- Number of defects.
- Number of major incidents.
- Hypercare duration.
- Number of outstanding issues.
- Customer acceptance.

---

# 89. Scope Closure

Confirm that all project scope has been classified as:

```text
DELIVERED
    ↓
ACCEPTED
    ↓
DEFERRED
    ↓
REMOVED
    ↓
TRANSFERRED TO ENHANCEMENT
```

No ambiguous scope should remain.

---

# 90. Change Request Closure

For every change request:

- Approved.
- Rejected.
- Implemented.
- Deferred.
- Cancelled.

Confirm commercial and schedule implications are closed.

---

# 91. Project Deliverable Acceptance

Create a final deliverable register.

Example:

| Deliverable | Owner | Status | Acceptance |
|---|---|---|---|
| Architecture | Solution Architect | Complete | Accepted |
| Configuration | Genesys Lead | Complete | Accepted |
| Integrations | Integration Lead | Complete | Accepted |
| Telephony | Telephony Lead | Complete | Accepted |
| Testing | Test Lead | Complete | Accepted |
| Documentation | PM / BAU | Complete | Accepted |
| Support Model | Service Owner | Complete | Accepted |
| Training | Training Lead | Complete | Accepted |
| Final Baseline | Technical Lead | Complete | Accepted |

---

# 92. Final Architecture Baseline

Create the final architectural baseline.

It must represent the actual production environment, not the original design.

Capture:

- Genesys Cloud.
- Identity.
- Telephony.
- CRM.
- Integrations.
- Middleware.
- Data.
- Digital.
- WFM.
- QM.
- Reporting.
- Security.
- Monitoring.
- External dependencies.

---

# 93. Final Configuration Baseline

Capture final production configuration:

- Organisation.
- Region.
- Divisions.
- Users.
- Roles.
- Queues.
- Skills.
- Languages.
- Architect.
- Schedules.
- Business hours.
- Holidays.
- Telephony.
- Numbers.
- Integrations.
- Data Actions.
- Data Tables.
- Recording.
- Digital.
- WFM.
- QM.
- Reporting.

---

# 94. Configuration Drift Closure

Confirm that:

```text
Approved Design
      ↓
Production Configuration
      ↓
Final Baseline
```

Any remaining variance must be documented and accepted.

---

# 95. Final Repository Baseline

Confirm final versions of:

- Terraform.
- Modules.
- Architect source or supporting artefacts.
- Integration source.
- Scripts.
- Automation.
- Documentation.
- Configuration.
- CI/CD.

---

# 96. Infrastructure as Code Validation

Where Terraform is used:

1. Confirm final code.
2. Confirm production state.
3. Validate repository.
4. Confirm modules.
5. Confirm provider versions.
6. Confirm state backend.
7. Confirm variables.
8. Confirm secrets management.
9. Confirm CI/CD.
10. Confirm BAU owner.

---

# 97. Automation Validation

Where automation exists:

- Execute representative test.
- Validate successful result.
- Validate failure handling.
- Confirm monitoring.
- Confirm ownership.
- Confirm documentation.

---

# 98. Final Operational Runbook

Create or confirm the final operational runbook.

Include:

- Daily operations.
- User administration.
- Queue administration.
- Routing.
- Architect.
- Telephony.
- Integrations.
- Digital.
- Recording.
- Reporting.
- WFM.
- QM.
- Monitoring.
- Incident management.
- Change management.
- Vendor escalation.

---

# 99. Troubleshooting Runbook

Document common problems and resolution paths.

Examples:

```text
Agent Cannot Log In
        ↓
Check Identity
        ↓
Check Role
        ↓
Check Browser / Endpoint
        ↓
Check Genesys Status
        ↓
Escalate if Required
```

Additional runbooks should cover:

- Audio.
- Calls.
- Routing.
- CRM.
- Data Actions.
- Architect.
- Digital.
- Recording.
- Reporting.

---

# 100. Support Escalation Matrix

Create the final escalation matrix.

| Issue | L1 | L2 | L3 | Vendor |
|---|---|---|---|---|
| Login | Service Desk | IAM | Platform | Genesys |
| Telephony | Service Desk | Telephony | Network / Carrier | Genesys |
| Routing | Service Desk | Genesys Admin | Architect | Genesys |
| Integration | Service Desk | Integration | Development | Vendor |
| CRM | Service Desk | CRM Support | Integration | CRM Vendor |
| WFM | Service Desk | WFM Team | Platform | Genesys |
| QM | Service Desk | QM Team | Platform | Genesys |

The customer's actual support model takes precedence.

---

# 101. Vendor Contact Register

Document:

- Vendor.
- Product.
- Contract.
- Account number.
- Support portal.
- Support level.
- Contact.
- Escalation contact.
- Contract owner.
- Renewal date.

---

# 102. Final Project Communication

Issue formal project closure communication covering:

- Project completion.
- BAU ownership.
- Support model.
- Project closure date.
- Remaining issues.
- Enhancement process.
- Benefits tracking.
- Final contact information.

---

# 103. Project Closure Meeting

Conduct the final project closure meeting.

Agenda:

1. Project outcome.
2. Scope.
3. Deliverables.
4. Production status.
5. BAU readiness.
6. Outstanding issues.
7. Technical debt.
8. Enhancements.
9. Benefits.
10. Lessons learned.
11. Commercial status.
12. Financial status.
13. Final acceptance.
14. Closure approval.

---

# 104. Final Sign-Off Model

Obtain required sign-offs from:

- Business Owner.
- Project Sponsor.
- Product Owner.
- Service Owner.
- Technical Owner.
- Security Owner.
- Operations.
- Architecture.
- Commercial Owner.
- Project Manager.

The exact sign-off list must follow the customer's governance framework.

---

# 105. Project Closure Criteria

The project may close only when:

- Scope is accepted.
- Deliverables are accepted.
- Production is stable.
- BAU ownership is established.
- Support is operational.
- Documentation is accepted.
- Knowledge transfer is complete.
- Outstanding issues are transferred.
- Technical debt is transferred.
- Enhancements are transferred.
- Commercial obligations are closed.
- Financial obligations are closed.
- Project access is removed where appropriate.
- Lessons learned are complete.
- Benefits have owners.
- Final sign-offs are obtained.

---

# 106. Project Closure Status

The closure decision should result in:

```text
CLOSED
CLOSED WITH ACCEPTED OPEN ITEMS
EXTENDED
```

A project should not remain formally open indefinitely because of BAU enhancements.

---

# 107. Closed With Accepted Open Items

The project may close with accepted open items when:

- No critical defects remain.
- Business accepts the residual risk.
- Every item has an owner.
- Every item has a target date.
- BAU governance owns the item.
- The item is no longer dependent on project resources.

---

# 108. Project Closure Archive

Create the final project archive containing:

```text
01_Project_Governance
02_Requirements
03_Architecture
04_Design
05_Configuration
06_Integrations
07_Telephony
08_Data_Migration
09_Testing
10_Cutover
11_Go_Live
12_Hypercare
13_BAU_Handover
14_Operations
15_Security
16_Commercial
17_Financial
18_Acceptance
19_Lessons_Learned
20_Project_Closure
```

The actual repository structure should follow customer requirements.

---

# 109. Project Closure Record

Create a formal project closure record containing:

- Project name.
- Customer.
- Project sponsor.
- Project manager.
- Solution owner.
- Service owner.
- Production date.
- Hypercare completion date.
- BAU handover date.
- Project closure date.
- Scope.
- Deliverables.
- Acceptance.
- Outstanding items.
- Technical debt.
- Enhancements.
- Benefits.
- Commercial status.
- Financial status.
- Lessons learned.
- Final approval.

---

# 110. Final Project Status

The project should be reported as:

```text
PROJECT COMPLETE
```

only when all closure criteria have been satisfied.

---

# 111. Phase 12 Deliverables

The following deliverables should be produced where applicable:

1. BAU ownership model.
2. RACI.
3. Service management handover.
4. Service Desk handover.
5. Application support handover.
6. Technical support handover.
7. Genesys administration handover.
8. Security handover.
9. IAM handover.
10. Telephony handover.
11. Carrier handover.
12. Architect handover.
13. Routing handover.
14. Integration handover.
15. CRM handover.
16. Digital channel handover.
17. Recording handover.
18. WFM handover.
19. QM handover.
20. Reporting handover.
21. Monitoring handover.
22. Terraform / IaC handover.
23. Automation handover.
24. Repository handover.
25. Incident management handover.
26. Problem management handover.
27. Change management handover.
28. DR documentation.
29. Business continuity documentation.
30. Vendor support handover.
31. Licensing reconciliation.
32. Outstanding defect register.
33. Technical debt register.
34. Enhancement backlog.
35. Final documentation baseline.
36. Knowledge transfer evidence.
37. Business acceptance.
38. Operational acceptance.
39. Security acceptance.
40. Final architecture baseline.
41. Final configuration baseline.
42. Final project KPI report.
43. Benefits realisation plan.
44. Lessons learned.
45. Commercial closure.
46. Financial closure.
47. Project closure report.
48. Final sign-off.
49. Phase 12 Gate approval.

---

# 112. Phase Dependencies

## Inputs

Phase 12 depends directly on:

**Phase 11 — Hypercare & Stabilisation**

Phase 12 also relies on the cumulative outputs of:

- Phase 01 — Project Initiation & Mobilisation
- Phase 02 — Discovery & Current-State Assessment
- Phase 03 — Requirements & Solution Definition
- Phase 04 — Solution Architecture & Detailed Design
- Phase 05 — Platform Foundation & Environment Build
- Phase 06 — Feature Configuration & Solution Build
- Phase 07 — Integration & Data Migration
- Phase 08 — Testing & Validation
- Phase 09 — Operational Readiness & Cutover Preparation
- Phase 10 — Production Deployment & Go-Live
- Phase 11 — Hypercare & Stabilisation

---

# 113. Dependency Model

```text
Phase 01–10
   ↓
Production Service
   ↓
Phase 11
Hypercare & Stabilisation
   ↓
Gate 11
   ↓
Phase 12
BAU Handover
   ↓
Operational Ownership
   ↓
Final Acceptance
   ↓
Commercial / Financial Closure
   ↓
Project Closure
   ↓
Gate 12
   ↓
LAYER 1 COMPLETE
```

---

# 114. Recommended Task Decomposition

The master deployment spreadsheet must break Phase 12 into individual tasks.

Recommended columns:

| Column | Description |
|---|---|
| Task ID | Unique task identifier |
| Phase | Phase number |
| Workstream | Phase 12 workstream |
| Parent Task | Parent activity |
| Task | Individual activity |
| Description | Detailed task description |
| Type | Required / Conditional / Optional |
| Dependency | Predecessor |
| Role | Primary responsible role |
| Customer Responsibility | Customer-owned activity |
| Environment | PROD / BAU / Repository |
| Effort | Estimated hours |
| Duration | Elapsed duration |
| Critical Path | Yes / No |
| Deliverable | Output |
| Acceptance Criteria | Completion condition |
| Status | Planned / In Progress / Complete |
| Evidence | Evidence reference |
| Notes | Additional information |

---

# 115. Recommended Phase 12 Task ID Structure

Use:

```text
P12-001
P12-002
P12-003
```

For workstream-level decomposition:

```text
P12-BAU-001
P12-BAU-002

P12-SM-001
P12-SM-002

P12-OPS-001
P12-OPS-002

P12-SEC-001
P12-SEC-002

P12-TEL-001
P12-TEL-002

P12-ARCH-001
P12-ARCH-002

P12-INT-001
P12-INT-002

P12-DIG-001
P12-DIG-002

P12-WFM-001
P12-WFM-002

P12-QM-001
P12-QM-002

P12-IAC-001
P12-IAC-002

P12-MON-001
P12-MON-002

P12-DR-001
P12-DR-002

P12-VEND-001
P12-VEND-002

P12-DEF-001
P12-DEF-002

P12-DEBT-001
P12-DEBT-002

P12-DOC-001
P12-DOC-002

P12-KT-001
P12-KT-002

P12-COM-001
P12-COM-002

P12-FIN-001
P12-FIN-002

P12-BEN-001
P12-BEN-002

P12-CLOSE-001
P12-CLOSE-002
```

---

# 116. Recommended Phase 12 Task Sequence

The project schedule should generally follow this sequence:

```text
P12-001
Confirm Gate 11 Approval
        ↓
P12-002
Confirm BAU Service Owner
        ↓
P12-003
Confirm BAU Business Owner
        ↓
P12-004
Confirm Technical Owners
        ↓
P12-005
Confirm Service Management Ownership
        ↓
P12-006
Confirm Support Model
        ↓
P12-007
Complete Service Desk Handover
        ↓
P12-008
Complete Application Support Handover
        ↓
P12-009
Complete Genesys Administration Handover
        ↓
P12-010
Complete Security / IAM Handover
        ↓
P12-011
Complete Telephony / Carrier Handover
        ↓
P12-012
Complete Architect Handover
        ↓
P12-013
Complete Routing Handover
        ↓
P12-014
Complete Integration Handover
        ↓
P12-015
Complete CRM Handover
        ↓
P12-016
Complete Digital Handover
        ↓
P12-017
Complete Recording Handover
        ↓
P12-018
Complete WFM Handover
        ↓
P12-019
Complete QM Handover
        ↓
P12-020
Complete Reporting Handover
        ↓
P12-021
Complete Monitoring Handover
        ↓
P12-022
Complete Terraform / IaC Handover
        ↓
P12-023
Complete Automation Handover
        ↓
P12-024
Complete Repository Handover
        ↓
P12-025
Complete Incident / Problem / Change Handover
        ↓
P12-026
Complete DR / BC Handover
        ↓
P12-027
Complete Vendor Handover
        ↓
P12-028
Reconcile Licences / Subscriptions
        ↓
P12-029
Review Outstanding Defects
        ↓
P12-030
Transfer Accepted Open Defects
        ↓
P12-031
Transfer Technical Debt
        ↓
P12-032
Transfer Enhancement Backlog
        ↓
P12-033
Complete Documentation Audit
        ↓
P12-034
Complete Documentation Acceptance
        ↓
P12-035
Complete Final Knowledge Transfer
        ↓
P12-036
Complete Operational Acceptance
        ↓
P12-037
Complete Business Acceptance
        ↓
P12-038
Complete Security Acceptance
        ↓
P12-039
Complete Final Architecture Baseline
        ↓
P12-040
Complete Final Configuration Baseline
        ↓
P12-041
Complete Repository / Source Baseline
        ↓
P12-042
Complete Project KPI Review
        ↓
P12-043
Complete Benefits Realisation Plan
        ↓
P12-044
Complete Lessons Learned
        ↓
P12-045
Complete Scope Closure
        ↓
P12-046
Complete Change Request Closure
        ↓
P12-047
Complete Commercial Closure
        ↓
P12-048
Complete Financial Closure
        ↓
P12-049
Release Project Resources
        ↓
P12-050
Remove Project-Only Access
        ↓
P12-051
Archive Project Repository
        ↓
P12-052
Complete Final Project Closure Report
        ↓
P12-053
Obtain Final Project Sign-Off
        ↓
P12-054
Approve Project Closure
        ↓
P12-055
Prepare Phase 12 Gate
```

The actual schedule must be adapted to the customer's governance, support model, contractual requirements and deployment complexity.

---

# 117. Parallel Activities

Not every Phase 12 task must be strictly sequential.

The following may occur in parallel after BAU ownership is confirmed:

```text
BAU Ownership Confirmed
        ↓
 ┌───────────────┬────────────────┬────────────────┐
 ↓               ↓                ↓
Support       Documentation    Technical
Handover      Handover         Handover
 ↓               ↓                ↓
 └───────────────┴────────────────┘
                  ↓
             Final Acceptance
```

Commercial and financial closure may also proceed in parallel with technical handover where appropriate.

---

# 118. Effort Estimation Considerations

Phase 12 effort varies based on:

- Customer governance.
- Number of support teams.
- Number of operational owners.
- Documentation volume.
- Number of integrations.
- Telephony complexity.
- WFM.
- QM.
- Digital.
- Security requirements.
- Compliance.
- Terraform / IaC.
- Automation.
- Vendor complexity.
- Contract complexity.
- Financial governance.
- Number of outstanding defects.
- Amount of technical debt.
- Number of project resources.
- Number of repositories.
- Number of operational procedures.

Do not estimate Phase 12 as a single generic closure task.

---

# 119. Effort Drivers

Major effort drivers include:

- Number of technical workstreams.
- Number of operational teams.
- Number of support groups.
- Number of integrations.
- Number of Architect flows.
- Number of queues.
- Number of channels.
- Telephony architecture.
- WFM.
- QM.
- Security.
- Compliance.
- Documentation standards.
- IaC maturity.
- Automation maturity.
- Vendor dependencies.
- Customer governance.
- Contractual requirements.

---

# 120. Critical Path Considerations

Potential critical-path activities include:

- BAU ownership confirmation.
- Service management handover.
- Support readiness.
- Documentation acceptance.
- Security handover.
- Telephony handover.
- Integration handover.
- Final configuration baseline.
- Final architecture baseline.
- Business acceptance.
- Operational acceptance.
- Commercial closure.
- Financial closure.
- Final sign-off.

---

# 121. Required vs Conditional Activities

The master methodology must distinguish between required and conditional activities.

## Generally Required

- BAU ownership.
- Service management handover.
- Support handover.
- Documentation.
- Knowledge transfer.
- Incident management.
- Change management.
- Final configuration baseline.
- Business acceptance.
- Operational acceptance.
- Project closure.
- Final sign-off.

## Conditional

- WFM handover.
- QM handover.
- Digital handover.
- AI / bot handover.
- Terraform / IaC handover.
- Automation handover.
- Carrier handover.
- DR testing.
- Compliance review.
- Vendor transfer.
- Complex commercial closure.

## Optional

- Additional operational simulations.
- Additional optimisation.
- Additional training.
- Additional documentation beyond agreed requirements.

---

# 122. Phase 12 Risks

Potential risks include:

### Unclear BAU Ownership

The project may close without clear accountability.

### Incomplete Documentation

BAU teams may be unable to operate or support the platform.

### Knowledge Transfer Gaps

Operational teams may depend on project resources after closure.

### Unresolved Defects

Defects may be incorrectly treated as project closure blockers or silently abandoned.

### Technical Debt

Temporary solutions may become permanent.

### Configuration Drift

Documentation may not match production.

### Access Dependencies

Project resources may retain access after handover.

### Vendor Dependency

Support arrangements may not be understood.

### Commercial Disputes

Deliverables or acceptance may remain unresolved.

### Financial Closure Delays

Outstanding invoices or purchase orders may prevent project closure.

### Benefits Not Measured

The customer may not be able to determine whether the implementation delivered expected value.

---

# 123. Risk Mitigation

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

# 124. BAU Transition Model

The transition should follow:

```text
Project Ownership
        ↓
Hypercare Ownership
        ↓
Joint Project / BAU Ownership
        ↓
BAU Ownership
        ↓
Project Exit
```

The project team should progressively reduce involvement rather than abruptly disappear.

---

# 125. Knowledge Transfer Maturity

Use the following model:

```text
Project Team Demonstrates
        ↓
BAU Team Observes
        ↓
BAU Team Performs With Assistance
        ↓
BAU Team Performs Independently
        ↓
BAU Team Supports Production
        ↓
Project Team Exits
```

---

# 126. Operational Independence

The BAU team should demonstrate the ability to:

- Perform routine administration.
- Handle common incidents.
- Perform standard changes.
- Access monitoring.
- Troubleshoot common problems.
- Escalate appropriately.
- Manage users.
- Manage queues.
- Manage routing.
- Manage Architect.
- Manage integrations.
- Manage reporting.

---

# 127. Project Resource Exit

Project resources should not be released until:

- BAU ownership is confirmed.
- Support readiness is accepted.
- Documentation is accepted.
- Knowledge transfer is complete.
- Remaining project obligations are assigned.

---

# 128. Project Access Removal

Review and remove project-only access from:

- Genesys Cloud.
- Customer IAM.
- Source repositories.
- Terraform.
- CI/CD.
- Monitoring.
- Ticketing.
- Documentation.
- Vendor systems.

Retain only access required by active support contracts.

---

# 129. Project Closure Communications

Communicate:

- Project completion.
- BAU ownership.
- Support model.
- Closure date.
- Remaining issues.
- Enhancement process.
- Benefits ownership.
- Operational contacts.

---

# 130. Final BAU Readiness Assessment

The following should be assessed:

| Area | Status |
|---|---|
| Business Ownership | Ready / Not Ready |
| Service Ownership | Ready / Not Ready |
| Platform Administration | Ready / Not Ready |
| User Administration | Ready / Not Ready |
| Queue Administration | Ready / Not Ready |
| Routing | Ready / Not Ready |
| Architect | Ready / Not Ready |
| Telephony | Ready / Not Ready |
| Integrations | Ready / Not Ready |
| Digital | Ready / Not Ready |
| Recording | Ready / Not Ready |
| WFM | Ready / Not Ready |
| QM | Ready / Not Ready |
| Reporting | Ready / Not Ready |
| Security | Ready / Not Ready |
| Monitoring | Ready / Not Ready |
| Service Desk | Ready / Not Ready |
| Application Support | Ready / Not Ready |
| Vendor Support | Ready / Not Ready |
| Documentation | Ready / Not Ready |
| Knowledge Transfer | Ready / Not Ready |
| DR / BC | Ready / Not Ready |
| Incident Management | Ready / Not Ready |
| Change Management | Ready / Not Ready |

---

# 131. Final Project Acceptance

Final project acceptance confirms:

- Scope delivered.
- Deliverables delivered.
- Production accepted.
- Operations accepted.
- Support accepted.
- Documentation accepted.
- Security accepted.
- Business accepted.
- Remaining issues accepted.
- Commercial closure accepted.

---

# 132. Final Project Closure Report

The final closure report should include:

- Executive summary.
- Project objectives.
- Scope.
- Architecture.
- Deployment.
- Go-live.
- Hypercare.
- BAU handover.
- KPI results.
- Incidents.
- Defects.
- Outstanding items.
- Technical debt.
- Enhancements.
- Benefits.
- Budget.
- Schedule.
- Risks.
- Lessons learned.
- Acceptance.
- Final status.

---

# 133. Phase 12 Definition of Done

Phase 12 is complete when:

- Gate 11 has passed.
- BAU ownership is confirmed.
- Service ownership is confirmed.
- Business ownership is confirmed.
- Service Desk is ready.
- Application support is ready.
- Technical support is ready.
- Genesys administration is handed over.
- Security ownership is handed over.
- IAM ownership is handed over.
- Telephony is handed over.
- Carrier ownership is confirmed where applicable.
- Architect ownership is handed over.
- Routing ownership is handed over.
- Integration ownership is handed over.
- CRM ownership is handed over.
- Digital ownership is handed over where applicable.
- Recording ownership is handed over.
- WFM ownership is handed over where applicable.
- QM ownership is handed over where applicable.
- Reporting ownership is handed over.
- Monitoring ownership is handed over.
- Terraform / IaC is handed over where applicable.
- Automation is handed over where applicable.
- Source repositories are handed over.
- Incident management is operational.
- Problem management is operational.
- Change management is operational.
- DR requirements are documented.
- Business continuity requirements are documented.
- Vendor support is confirmed.
- Licences are reconciled.
- Outstanding defects are closed or transferred.
- Technical debt is transferred.
- Enhancements are transferred.
- Documentation is accepted.
- Knowledge transfer is complete.
- Business acceptance is complete.
- Technical acceptance is complete.
- Security acceptance is complete.
- Final architecture baseline is complete.
- Final configuration baseline is complete.
- Final repository baseline is complete.
- Benefits have owners.
- Lessons learned are complete.
- Project scope is closed.
- Change requests are closed.
- Commercial closure is complete.
- Financial closure is complete.
- Project resources are released.
- Project-only access is removed.
- Project archive is complete.
- Final project closure report is complete.
- Final sign-offs are complete.
- Phase 12 Gate is passed.

---

# 134. Phase 12 Governance

Phase 12 should include formal governance events.

Recommended meetings:

- BAU ownership meeting.
- Service management handover.
- Technical handover.
- Security handover.
- Support readiness review.
- Documentation review.
- Knowledge transfer review.
- Business acceptance.
- Operational acceptance.
- Commercial review.
- Financial review.
- Lessons learned.
- Benefits review.
- Final project closure review.
- Phase 12 gate.

---

# 135. Final Governance Model

The project should transition from:

```text
Project Governance
        ↓
Hypercare Governance
        ↓
BAU Governance
```

The final BAU governance model should be explicitly documented.

---

# 136. Phase Gate — Gate 12: BAU Handover & Project Closure Complete

## Gate Objective

Confirm that the Genesys Cloud platform has been formally transitioned into BAU ownership, that all required project deliverables have been accepted, and that the implementation project can be formally closed.

---

# 137. Gate 12 Entry Criteria

The following must be true:

- Gate 11 passed.
- Production is stable.
- Hypercare has exited.
- BAU owners are identified.
- Support model exists.
- Documentation is available.
- Remaining defects are controlled.
- Project closure activities are underway.

---

# 138. Gate 12 Exit Criteria

## BAU Ownership

- Business Owner confirmed.
- Service Owner confirmed.
- Platform Owner confirmed.
- Technical Owners confirmed.
- Support groups confirmed.
- Escalation model confirmed.

## Technical

- Final architecture baseline accepted.
- Final configuration baseline accepted.
- Integrations handed over.
- Telephony handed over.
- Architect handed over.
- Routing handed over.
- Digital handed over where applicable.
- Recording handed over.
- WFM handed over where applicable.
- QM handed over where applicable.
- Reporting handed over.
- Monitoring handed over.
- Terraform / IaC handed over where applicable.
- Automation handed over where applicable.

## Operational

- Service Desk ready.
- Application Support ready.
- Technical Support ready.
- Incident process operational.
- Problem process operational.
- Change process operational.
- DR / BC documented.
- Vendor support confirmed.

## Documentation

- Documentation complete.
- Runbooks complete.
- Knowledge articles complete.
- Architecture accepted.
- Configuration accepted.
- Operational documentation accepted.

## Project

- Scope closed.
- Deliverables accepted.
- Change requests closed.
- Commercial closure complete.
- Financial closure complete.
- Lessons learned complete.
- Benefits owners confirmed.
- Project resources released.
- Project access removed.
- Project archive complete.

## Acceptance

- Business acceptance complete.
- Operational acceptance complete.
- Technical acceptance complete.
- Security acceptance complete.
- Final project sign-off complete.

---

# 139. Gate Decision

The Phase 12 gate must result in one of:

```text
PASS
```

The solution has been fully transitioned to BAU and the project can close.

```text
PASS WITH CONDITIONS
```

The project can close with formally accepted residual items transferred into BAU.

```text
EXTEND
```

Additional project activities are required before closure.

```text
HOLD
```

The project cannot close because critical acceptance or handover conditions remain unresolved.

---

# 140. Final Layer 1 Completion State

Once Gate 12 passes:

```text
PROJECT INITIATION
        ↓
DISCOVERY
        ↓
REQUIREMENTS
        ↓
ARCHITECTURE
        ↓
FOUNDATION
        ↓
CONFIGURATION
        ↓
INTEGRATION
        ↓
TESTING
        ↓
CUTOVER
        ↓
GO-LIVE
        ↓
HYPERCARE
        ↓
BAU HANDOVER
        ↓
PROJECT CLOSURE
        ↓
LAYER 1 COMPLETE
```

The Genesys Cloud deployment is now considered operationally complete.

---

# 141. Layer 1 Final Deliverable

The ultimate output of the twelve-phase methodology is:

**A fully deployed, tested, production-operational, documented, supported, governed and accepted Genesys Cloud environment transitioned into BAU ownership.**

The implementation project is formally closed.

---

# 142. Layer 1 Master Methodology Completion

The completed Layer 1 sequence is:

| Phase | Name | Primary Outcome |
|---|---|---|
| 01 | Project Initiation & Mobilisation | Project established |
| 02 | Discovery & Current-State Assessment | Current state understood |
| 03 | Requirements & Solution Definition | Requirements and solution scope defined |
| 04 | Solution Architecture & Detailed Design | Solution designed |
| 05 | Platform Foundation & Environment Build | Platform foundation established |
| 06 | Feature Configuration & Solution Build | Genesys capabilities configured |
| 07 | Integration & Data Migration | Integrations and migration completed |
| 08 | Testing & Validation | Solution validated |
| 09 | Operational Readiness & Cutover Preparation | Organisation prepared for go-live |
| 10 | Production Deployment & Go-Live | Production service activated |
| 11 | Hypercare & Stabilisation | Production service stabilised |
| **12** | **BAU Handover & Project Closure** | **Service transferred and project closed** |

---

# 143. Final Layer 1 Dependency Chain

```text
P01
Project Initiation
    ↓
P02
Discovery
    ↓
P03
Requirements
    ↓
P04
Architecture
    ↓
P05
Foundation
    ↓
P06
Configuration
    ↓
P07
Integration / Migration
    ↓
P08
Testing
    ↓
P09
Operational Readiness
    ↓
P10
Go-Live
    ↓
P11
Hypercare
    ↓
P12
BAU Handover
    ↓
Project Closure
    ↓
LAYER 1 COMPLETE
```

---

# 144. Future Layer 2 Development

Layer 1 establishes the master project lifecycle.

The next level of the methodology should expand each phase into detailed work packages and spreadsheet-ready tasks.

The master project spreadsheet should ultimately allow each task to be represented as:

```text
Task ID
Phase
Workstream
Parent Task
Task
Description
Task Type
Dependency
Role
Customer Responsibility
Environment
Effort
Duration
Deliverable
Acceptance Criteria
Critical Path
Status
Evidence
Notes
```

Each Phase 01–12 task should eventually be represented at a granularity that allows project teams to:

- Build project schedules.
- Estimate implementation effort.
- Identify resource requirements.
- Determine customer responsibilities.
- Identify dependencies.
- Determine critical path.
- Track deliverables.
- Track acceptance.
- Compare planned versus actual effort.
- Build project templates.
- Create repeatable implementation plans.

---

# 145. Master Spreadsheet Preparation

The final deployment spreadsheet should not simply contain the phase headings.

It should contain the individual activities required to execute the deployment.

For example:

```text
P12-001
Confirm Gate 11 Approval

P12-002
Confirm BAU Service Owner

P12-003
Confirm BAU Business Owner

P12-004
Confirm Technical Owners

P12-005
Confirm Service Management Ownership

P12-006
Confirm Support Model

...

P12-055
Prepare Phase 12 Gate
```

Each activity should become an individual spreadsheet row.

---

# 146. Effort Estimation Model

The future estimation model should allow effort to be calculated using:

```text
Base Task Effort
        +
Complexity Factor
        +
User / Agent Volume
        +
Queue Volume
        +
Integration Count
        +
Channel Count
        +
Telephony Complexity
        +
WFM / QM Complexity
        +
Security / Compliance
        +
Customer Governance
        +
Migration Complexity
        +
Geographic Complexity
        =
Estimated Project Effort
```

This is preferable to applying a single percentage of total project effort to Phase 12.

---

# 147. Final Definition of Done — Layer 1

Layer 1 is complete when:

- All twelve phases are complete.
- All phase gates have passed.
- The Genesys Cloud environment is production operational.
- Business requirements have been delivered.
- Technical requirements have been delivered.
- Integrations are operational.
- Telephony is operational.
- Digital channels are operational where applicable.
- WFM is operational where applicable.
- QM is operational where applicable.
- Reporting is operational.
- Security requirements are satisfied.
- Testing is complete.
- Production deployment is complete.
- Hypercare is complete.
- BAU ownership is established.
- Operational support is established.
- Documentation is complete.
- Knowledge transfer is complete.
- Remaining defects are controlled.
- Technical debt is documented.
- Enhancements are transferred.
- Benefits are owned.
- Commercial obligations are closed.
- Financial obligations are closed.
- Project resources are released.
- Project-only access is removed.
- Project documentation is archived.
- Final acceptance is obtained.
- Project closure is approved.

---

# 148. Final Layer 1 Gate

The ultimate Layer 1 completion decision is:

```text
GATE 12
BAU HANDOVER & PROJECT CLOSURE
        ↓
FINAL ACCEPTANCE
        ↓
PROJECT CLOSED
        ↓
GENESYS CLOUD SERVICE
OPERATING UNDER BAU
        ↓
LAYER 1 COMPLETE
```

---

# Phase Completion

**Phase:** 12 — BAU Handover & Project Closure

**Previous Phase:** 11 — Hypercare & Stabilisation

**Next Phase:** None within Layer 1

**Phase Gate:** Gate 12 — BAU Handover & Project Closure Complete

**Primary Outcome:** Genesys Cloud has been formally transitioned into BAU ownership, all operational and project deliverables have been accepted, remaining work has been transferred into the appropriate BAU governance mechanisms, and the implementation project has been formally closed.

**Layer 1 Status:** COMPLETE

**Final Layer 1 Outcome:**

A reusable, enterprise-grade Genesys Cloud deployment methodology covering the complete lifecycle from project initiation through discovery, architecture, foundation, configuration, integration, testing, cutover, production deployment, hypercare, BAU handover and formal project closure.

The complete twelve-phase methodology is now ready to be decomposed into the master project schedule and effort-estimation spreadsheet.
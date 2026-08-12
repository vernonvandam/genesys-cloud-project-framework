# Phase 06 — Feature Configuration & Solution Build

## 1. Purpose

Build and configure the approved Genesys Cloud solution defined during:

- Phase 03 — Requirements & Solution Definition
- Phase 04 — Solution Architecture & Detailed Design
- Phase 05 — Platform Foundation & Environment Build

This phase transforms the approved architecture and detailed design into a working Genesys Cloud solution.

The objective is to configure, develop and unit-test the required Genesys Cloud capabilities while maintaining alignment with the approved architecture, configuration standards, security model and implementation strategy.

This phase represents the primary **solution build phase** of the deployment.

---

# 2. Phase Objective

By the end of Phase 06:

- Core Genesys Cloud configuration is complete.
- Users and teams are configured.
- Queues are configured.
- Skills and languages are configured.
- Routing is configured.
- Voice configuration is complete.
- Inbound call handling is implemented.
- Architect flows are developed.
- IVR functionality is implemented.
- Self-service functionality is implemented where applicable.
- Callback functionality is implemented where applicable.
- Digital channels are configured where applicable.
- Email is configured where applicable.
- Outbound functionality is configured where applicable.
- Workforce Management is configured where applicable.
- Quality Management is configured where applicable.
- Recording is configured.
- Analytics and reporting are configured.
- Knowledge functionality is configured where applicable.
- Bots are configured where applicable.
- Integrations required for the feature build are configured where applicable.
- Data Actions are implemented where applicable.
- Business rules are implemented.
- Agent experience is configured.
- Supervisor experience is configured.
- Administrative configuration is complete.
- Configuration is promoted through the agreed environments.
- Unit testing is completed.
- Build defects are recorded and resolved.
- The solution is ready for formal integration testing and system validation.

---

# 3. Phase Entry Criteria

Phase 06 should not commence until:

- Phase 05 — Platform Foundation & Environment Build is complete.
- Gate 05 has passed.
- Genesys Cloud environments are available.
- Required users and administrative access are available.
- Identity configuration is operational.
- Network prerequisites are validated.
- Telephony foundation is available.
- OAuth / API foundation is available where required.
- Configuration standards are established.
- Solution architecture is approved.
- Detailed solution design is approved.
- Requirements baseline is approved.
- Build dependencies are understood.

---

# 4. Feature Build Workstreams

The phase is structured into the following workstreams:

### 06.01 Configuration Baseline
### 06.02 User & Agent Configuration
### 06.03 Teams & Workforce Structure
### 06.04 Queues
### 06.05 Skills & Languages
### 06.06 Routing Configuration
### 06.07 Voice Configuration
### 06.08 Inbound Numbers & Call Routing
### 06.09 Architect / IVR Development
### 06.10 Customer Identification & Authentication
### 06.11 Self-Service
### 06.12 Callback
### 06.13 Transfer & Escalation
### 06.14 Digital Channels
### 06.15 Messaging
### 06.16 Email
### 06.17 Outbound
### 06.18 Workforce Management
### 06.19 Quality Management
### 06.20 Recording
### 06.21 Performance Management
### 06.22 Analytics & Reporting
### 06.23 Knowledge
### 06.24 Bots & Virtual Agents
### 06.25 Integrations
### 06.26 Data Actions
### 06.27 Agent Experience
### 06.28 Supervisor Experience
### 06.29 Business Rules
### 06.30 Notifications
### 06.31 Configuration Automation
### 06.32 Unit Testing
### 06.33 Build Defect Resolution
### 06.34 Environment Promotion
### 06.35 Build Completion & Gate Preparation

Not every workstream will apply to every deployment.

The master deployment spreadsheet should mark optional workstreams as:

- Required
- Optional
- Not Applicable

---

# 5. Build Strategy

The solution should be built according to the approved dependency model.

The general sequence should be:

```text
Configuration Baseline
        ↓
Users / Teams
        ↓
Queues
        ↓
Skills / Languages
        ↓
Routing
        ↓
Voice
        ↓
Architect
        ↓
Integrations
        ↓
Digital
        ↓
WEM / QM
        ↓
Reporting
        ↓
Agent Experience
        ↓
Unit Testing
        ↓
Defect Resolution
        ↓
Environment Promotion
```

Some workstreams may be developed in parallel where dependencies allow.

---

# 6. Configuration Baseline

Establish the configuration baseline before detailed feature configuration begins.

## Activities

1. Review Phase 04 design.
2. Review Phase 05 platform foundation.
3. Confirm naming standards.
4. Confirm object ownership.
5. Confirm division assignments.
6. Confirm environment.
7. Confirm configuration promotion strategy.
8. Confirm build repository.
9. Confirm automation strategy.
10. Confirm configuration documentation.

## Validate

- Configuration follows approved architecture.
- Naming standards are applied.
- Correct divisions are used.
- Correct environment is being modified.
- Configuration is traceable to approved design.

## Output

**Feature Configuration Baseline**

---

# 7. User & Agent Configuration

Configure users required to operate the contact centre.

## Activities

Configure:

- User profiles
- Agent licences
- Supervisor licences
- WEM licences
- QM licences
- Roles
- Groups
- Divisions
- Teams
- Skills
- Languages
- Locations
- Phone settings
- Station settings
- Routing status
- Utilisation settings

## Agent Configuration

For each agent define:

- User
- Team
- Division
- Queue membership
- Skills
- Languages
- Skill proficiency
- Licence
- Role
- Workstation
- Phone / WebRTC configuration

## Validate

Agents should have exactly the permissions and routing capabilities required by their role.

---

# 8. Teams & Workforce Structure

Configure the organisational structure required by the operating model.

## Activities

1. Create teams.
2. Assign supervisors.
3. Assign agents.
4. Configure team settings.
5. Configure division relationships.
6. Configure team-level permissions.
7. Validate hierarchy.

## Output

**Team / Workforce Structure**

---

# 9. Queue Configuration

Build the approved queue architecture.

## For Each Queue

Configure:

- Queue name
- Division
- Description
- Members
- Skills
- Languages
- Routing method
- Evaluation method
- Service level
- Queue activation
- Queue membership
- Wrap-up configuration
- Queue-specific permissions
- Queue-specific media settings

## Validate

- Correct users assigned.
- Correct skills assigned.
- Correct routing method.
- Correct division.
- Correct service level.
- Correct wrap-up configuration.

## Output

**Queue Configuration Register**

---

# 10. Skills & Languages

Configure the approved skill and language model.

## Activities

1. Create skills.
2. Apply naming standards.
3. Create languages.
4. Configure agent proficiency.
5. Assign skills to agents.
6. Assign languages to agents.
7. Validate routing relationships.
8. Validate queue requirements.

## Skill Structure

```text
Interaction
      ↓
Queue
      ↓
Required Skill
      ↓
Agent Skill
      ↓
Proficiency
      ↓
Eligible Agent
```

## Output

**Skill / Language Configuration**

---

# 11. Routing Configuration

Implement the approved ACD routing architecture.

## Routing Methods

Configure where applicable:

- Standard routing
- Bullseye routing
- Preferred agent routing
- Skills-based routing
- Language routing
- Priority-based routing
- Conditional routing
- Emergency routing
- Overflow routing
- Callback routing

## Activities

1. Configure routing methods.
2. Configure routing rules.
3. Configure skills.
4. Configure language requirements.
5. Configure priority.
6. Configure queue behaviour.
7. Configure overflow.
8. Configure escalation.
9. Configure timeout.
10. Configure fallback.

## Validate

Routing should produce the expected agent selection for each approved scenario.

---

# 12. Voice Configuration

Complete the detailed voice configuration.

## Activities

Configure:

- Phones
- Phone assignments
- WebRTC
- Sites
- Locations
- Trunks
- Outbound routes
- Dial plans
- Caller ID
- Emergency calling
- Recording
- Call controls

## Validate

Test:

- Inbound calls
- Outbound calls
- Internal calls
- Hold
- Retrieve
- Transfer
- Consult
- Conference
- DTMF
- Caller ID
- Recording
- Disconnect

---

# 13. Inbound Numbers & Call Routing

Configure inbound call entry points.

## Activities

1. Configure inbound numbers.
2. Associate numbers with Architect flows.
3. Configure schedules.
4. Configure business hours.
5. Configure holiday schedules.
6. Configure emergency routing.
7. Configure after-hours routing.
8. Configure overflow routing.
9. Configure failover.
10. Validate number routing.

## Output

**Inbound Number / Flow Mapping**

| Number | Purpose | Flow | Schedule | Queue | Status |
|---|---|---|---|---|---|
| TBD | Customer Service | TBD | TBD | TBD | Build |

---

# 14. Architect / IVR Development

Develop the approved Architect solution.

## Activities

1. Create flow structure.
2. Configure reusable components.
3. Configure prompts.
4. Configure menus.
5. Configure variables.
6. Configure decisions.
7. Configure data lookups.
8. Configure call transfers.
9. Configure queue transfers.
10. Configure callbacks.
11. Configure error handling.
12. Configure disconnect handling.
13. Configure logging.
14. Configure failover.
15. Configure flow versions.
16. Configure publish process.

## Flow Categories

Potential flow types include:

- Inbound call flows
- In-queue flows
- Outbound call flows
- Secure call flows
- Customer callback flows
- Common modules
- Reusable tasks
- Bot flows
- Survey flows

---

# 15. Architect Naming & Development Standards

All Architect development must follow the approved development standards.

## Standards

Define and apply:

- Flow naming
- Variable naming
- Task naming
- Menu naming
- Prompt naming
- Data Action naming
- Reusable component naming
- Version naming
- Description standards
- Comments
- Error handling
- Logging

## Example

```text
<ENV>-ARCH-<FLOWTYPE>-<FUNCTION>
```

Example:

```text
DEV-ARCH-INBOUND-CUSTOMER-SERVICE
DEV-ARCH-INQUEUE-CUSTOMER-SERVICE
DEV-ARCH-CALLBACK-CUSTOMER-SERVICE
```

---

# 16. Customer Identification & Authentication

Implement customer identification and authentication functionality where required.

## Potential Methods

- ANI
- Customer number
- Account number
- CRM lookup
- PIN
- OTP
- Knowledge-based authentication
- Identity provider
- Customer portal authentication

## Activities

1. Identify customer.
2. Retrieve customer data.
3. Validate identity.
4. Handle authentication failure.
5. Handle unknown customer.
6. Handle multiple matches.
7. Handle customer lookup failure.
8. Route based on customer information.

---

# 17. Self-Service

Implement approved self-service capabilities.

## Potential Functions

- Account lookup
- Balance enquiry
- Order status
- Appointment status
- Payment information
- Address update
- Case status
- FAQ
- Knowledge lookup
- Transaction processing

## Activities

1. Configure self-service flow.
2. Configure backend integration.
3. Configure customer authentication.
4. Configure transaction logic.
5. Configure confirmation.
6. Configure failure handling.
7. Configure escalation to agent.
8. Validate successful transaction.
9. Validate failed transaction.

---

# 18. Callback

Configure callback functionality where required.

## Activities

Configure:

- Callback option
- Callback scheduling
- Callback queue
- Callback priority
- Callback retry
- Callback caller ID
- Callback timeouts
- Callback failure
- Callback reporting

## Validate

- Customer requests callback.
- Callback is created.
- Callback enters queue.
- Agent receives callback.
- Callback is completed.
- Failed callback is handled correctly.

---

# 19. Transfer & Escalation

Configure the approved transfer architecture.

## Transfer Types

- Blind transfer
- Consult transfer
- Queue transfer
- User transfer
- External transfer
- Emergency transfer
- Supervisor escalation

## Activities

1. Configure transfer destinations.
2. Configure transfer permissions.
3. Configure transfer messaging.
4. Configure escalation rules.
5. Configure failure handling.
6. Configure after-hours behaviour.

---

# 20. Digital Channels

Configure approved digital channels.

## Potential Channels

- Web messaging
- Web chat
- SMS
- WhatsApp
- Social messaging
- Mobile application
- Third-party messaging

## Activities

1. Configure channel.
2. Configure entry point.
3. Configure queue.
4. Configure routing.
5. Configure skills.
6. Configure languages.
7. Configure priority.
8. Configure authentication.
9. Configure agent handling.
10. Configure transfer.
11. Configure escalation.
12. Configure reporting.

---

# 21. Messaging

Where applicable, configure Genesys Cloud messaging.

## Activities

Configure:

- Messaging deployment
- Messaging configuration
- Web deployment
- Authentication
- Entry point
- Queue
- Routing
- Skills
- Architect flow
- Bot integration
- Agent escalation
- Conversation termination

## Validate

Complete an end-to-end messaging conversation.

---

# 22. Email

Configure email channels where required.

## Activities

1. Configure email domains.
2. Configure email addresses.
3. Associate email with queues.
4. Configure routing.
5. Configure SLA.
6. Configure auto-response.
7. Configure templates.
8. Configure signatures.
9. Configure attachments.
10. Configure escalation.
11. Configure wrap-up.
12. Configure reporting.

---

# 23. Outbound

Where applicable, configure outbound functionality.

## Campaign Configuration

Configure:

- Campaigns
- Contact lists
- Contact list mappings
- Campaign rules
- Calling modes
- Schedules
- Queue
- Agents
- Caller ID
- Dispositions
- Retry rules
- DNC
- Compliance rules

## Validate

- Contact loaded.
- Contact is eligible.
- Campaign starts.
- Contact is dialled.
- Agent receives interaction.
- Disposition is recorded.
- Retry rules work.

---

# 24. Workforce Management

Where WFM is included, configure the approved WFM model.

## Activities

Configure:

- Management units
- Service goals
- Planning groups
- Forecasting
- Staffing groups
- Schedules
- Shift activities
- Time-off plans
- Scheduling rules
- Adherence
- Intraday management

## Validate

- Forecast can be generated.
- Staffing requirements are calculated.
- Schedule can be created.
- Agent schedule is available.
- Adherence data is available.

---

# 25. Quality Management

Where QM is included, configure:

- Evaluation forms
- Evaluation questions
- Scoring
- Critical questions
- Evaluation policies
- Sampling
- Calibration
- Coaching
- Quality workflows

## Activities

1. Create evaluation forms.
2. Configure questions.
3. Configure scoring.
4. Configure critical questions.
5. Configure evaluation policies.
6. Configure sampling.
7. Configure evaluator permissions.
8. Configure coaching.
9. Validate evaluation process.

---

# 26. Recording

Configure recording according to the approved recording architecture.

## Activities

Configure:

- Recording policies
- Recording scope
- Recording retention
- Recording access
- Screen recording
- Secure pause
- PCI handling
- Recording permissions
- Recording retrieval

## Validate

Test:

- Call recording
- Screen recording
- Secure pause
- Recording retrieval
- Recording access
- Retention policy

---

# 27. Performance Management

Where applicable, configure performance management capabilities.

## Activities

Configure:

- Performance views
- Metrics
- Targets
- Scorecards
- Agent performance
- Team performance
- Supervisor views
- Coaching metrics

## Validate

Verify that required users can view the appropriate performance information.

---

# 28. Analytics & Reporting

Configure the reporting solution.

## Activities

Configure:

- Real-time views
- Historical views
- Dashboards
- Supervisor views
- Agent views
- Queue views
- Performance views
- Reporting permissions
- Export requirements

## Metrics

Potential metrics include:

- Offered
- Answered
- Abandoned
- Service level
- Average speed of answer
- Average handle time
- Talk time
- Hold time
- After-call work
- Occupancy
- Utilisation
- Adherence
- Transfer rate
- Callback rate

---

# 29. Knowledge

Where applicable, configure knowledge management.

## Activities

1. Create knowledge base.
2. Configure knowledge categories.
3. Configure articles.
4. Configure article templates.
5. Configure search.
6. Configure publishing.
7. Configure permissions.
8. Configure agent access.
9. Configure customer access where applicable.
10. Configure knowledge analytics.

## Validate

- Article searchable.
- Article accessible.
- Search returns relevant results.
- Agent can use knowledge.
- Customer can access approved content where applicable.

---

# 30. Bots & Virtual Agents

Where applicable, configure approved bot capabilities.

## Potential Functions

- Intent identification
- Authentication
- FAQ
- Knowledge search
- Transaction
- Data lookup
- Appointment management
- Case management
- Escalation

## Activities

1. Configure bot.
2. Configure intents.
3. Configure entities.
4. Configure prompts.
5. Configure conversation logic.
6. Configure backend integrations.
7. Configure escalation.
8. Configure error handling.
9. Configure fallback.
10. Configure analytics.

## Validate

Test:

- Correct intent
- Incorrect intent
- No-match
- No-input
- Authentication
- Successful transaction
- Failed transaction
- Agent escalation

---

# 31. Integrations

Implement integrations required for feature functionality.

## Integration Categories

Potential integrations include:

- CRM
- ERP
- Customer database
- Identity platform
- Ticketing system
- Payment system
- Knowledge system
- Workforce system
- Data platform
- BI platform
- External applications

## Activities

1. Configure endpoint.
2. Configure authentication.
3. Configure request.
4. Configure response.
5. Configure data mapping.
6. Configure transformation.
7. Configure timeout.
8. Configure retry.
9. Configure error handling.
10. Configure logging.
11. Configure monitoring.
12. Perform unit test.

---

# 32. Data Actions

Build Data Actions required by Architect, integrations and agent workflows.

## Activities

1. Create Data Action.
2. Configure integration.
3. Configure contract.
4. Configure request.
5. Configure response.
6. Configure success conditions.
7. Configure failure conditions.
8. Configure timeout.
9. Configure error handling.
10. Configure logging.
11. Unit test.

## Data Action Register

| Data Action | Purpose | System | Flow / Feature | Environment | Status |
|---|---|---|---|---|---|
| TBD | Customer Lookup | CRM | IVR | DEV | Build |

---

# 33. Agent Experience

Configure the agent workspace according to the approved design.

## Activities

Configure:

- Agent scripts
- Queues
- Skills
- Languages
- Wrap-up codes
- Dispositions
- Canned responses
- Knowledge
- Screen pop
- CRM integration
- Agent assist
- Digital interaction handling
- Call controls
- Transfer options
- Status configuration

## Validate

Agent can:

- Log in.
- Change status.
- Receive interaction.
- Handle interaction.
- Transfer interaction.
- Place on hold.
- Complete wrap-up.
- Access required customer data.
- Access required knowledge.
- Complete required disposition.

---

# 34. Supervisor Experience

Configure supervisor capabilities.

## Activities

Configure:

- Supervisor roles
- Queue monitoring
- Agent monitoring
- Whisper
- Barge
- Coaching
- Performance views
- Real-time dashboards
- Historical reporting
- Quality management
- WFM access

## Validate

Supervisor can access only the teams, queues and data permitted by the design.

---

# 35. Business Rules

Implement approved business rules.

## Potential Rules

- Customer segmentation
- VIP routing
- Priority
- Business hours
- Holiday routing
- Queue selection
- Skill routing
- Language routing
- Authentication
- Self-service eligibility
- Callback eligibility
- Escalation
- Overflow
- Service-level handling

## Activities

1. Configure rules.
2. Configure conditions.
3. Configure actions.
4. Configure exception handling.
5. Unit test each rule.

---

# 36. Notifications

Configure platform notifications where required.

## Potential Notifications

- Queue alerts
- Supervisor alerts
- System alerts
- Integration alerts
- WFM alerts
- Quality alerts
- Administrative alerts

## Activities

1. Define notification.
2. Define recipient.
3. Define trigger.
4. Configure channel.
5. Configure escalation.
6. Test notification.

---

# 37. Configuration Automation

Where automation is approved, implement configuration through the selected automation framework.

## Potential Components

- Terraform
- Genesys Cloud APIs
- CI/CD
- Scripts
- Configuration files
- CSV-driven configuration
- JSON-driven configuration

## Activities

1. Create module / automation.
2. Configure variables.
3. Configure environment values.
4. Configure dependencies.
5. Validate plan.
6. Deploy.
7. Validate deployed configuration.
8. Document exceptions.

## Principle

Configuration should be automated where the benefit of repeatability, consistency and lifecycle management outweighs the complexity of automation.

---

# 38. Configuration Promotion

Promote configuration according to the approved environment strategy.

## Example

```text
Development
     ↓
Code / Configuration Review
     ↓
SIT
     ↓
Validation
     ↓
UAT
     ↓
Business Approval
     ↓
Production
```

## Activities

1. Identify release.
2. Validate configuration.
3. Perform peer review.
4. Deploy to next environment.
5. Validate configuration.
6. Execute unit / integration tests.
7. Record defects.
8. Obtain approval.
9. Promote.

---

# 39. Unit Testing

Every build component should undergo unit testing before entering formal integration testing.

## Test Categories

### Configuration

- Object exists.
- Correct settings.
- Correct permissions.
- Correct division.

### Routing

- Correct queue.
- Correct skill.
- Correct language.
- Correct priority.
- Correct agent.

### Architect

- Correct path.
- Correct prompt.
- Correct decision.
- Correct integration.
- Correct error handling.

### Voice

- Correct number.
- Correct routing.
- Correct audio.
- Correct transfer.
- Correct recording.

### Digital

- Correct channel.
- Correct routing.
- Correct agent.
- Correct transfer.

### WEM

- Correct forecast.
- Correct schedule.
- Correct adherence.

### QM

- Correct evaluation.
- Correct scoring.
- Correct sampling.

### Reporting

- Correct metric.
- Correct permissions.
- Correct data.

---

# 40. Unit Test Evidence

Every major feature should produce evidence.

## Evidence Types

- Screenshot
- Test result
- Log
- API response
- Call recording
- Conversation ID
- Flow execution result
- Configuration export
- Automated test result

## Test Register

| Test ID | Feature | Scenario | Expected Result | Actual Result | Status | Evidence |
|---|---|---|---|---|---|---|
| UT-001 | Queue | Agent receives call | Correct agent | TBD | Planned | TBD |

---

# 41. Build Defect Management

All build defects should be recorded and managed.

## Defect Categories

- Configuration
- Architect
- Routing
- Voice
- Digital
- Integration
- Data Action
- WEM
- QM
- Recording
- Reporting
- Security
- Automation

## Defect Register

| ID | Description | Severity | Feature | Environment | Owner | Status | Resolution |
|---|---|---|---|---|---|---|---|
| DEF-001 | TBD | High | TBD | DEV | TBD | Open | TBD |

---

# 42. Build Defect Severity

Recommended severity model:

### Severity 1 — Critical

Prevents core solution operation.

### Severity 2 — High

Major feature does not work or requires significant workaround.

### Severity 3 — Medium

Feature works with limited impact.

### Severity 4 — Low

Cosmetic, documentation or minor usability issue.

---

# 43. Configuration Traceability

All major configuration should trace back to approved requirements.

Recommended model:

```text
Requirement
      ↓
Architecture
      ↓
Detailed Design
      ↓
Configuration
      ↓
Unit Test
      ↓
Integration Test
      ↓
UAT
```

## Example

```text
REQ-001
Customer Service Calls
        ↓
ARCH-VOICE-001
Customer Service Queue
        ↓
DES-ROUTING-001
Skills-Based Routing
        ↓
CFG-QUEUE-001
Customer Service Queue
        ↓
UT-001
Routing Unit Test
```

---

# 44. Documentation

Update technical documentation continuously throughout the build.

## Required Documentation

- Configuration register
- Queue register
- Skill register
- Language register
- Architect flow register
- Prompt register
- Data Action register
- Integration register
- OAuth register
- Number register
- Agent configuration
- WFM configuration
- QM configuration
- Recording configuration
- Reporting configuration
- Bot configuration
- Knowledge configuration
- Test evidence
- Defect register
- Configuration changes
- Environment promotion records

Documentation should be updated as part of the build rather than deferred until project closure.

---

# 45. Build Completion Review

Conduct a structured review before moving into formal integration testing.

## Review

Confirm:

### Platform

- Foundation remains valid.
- Configuration aligns with architecture.

### Features

- Required features are built.
- Optional features are correctly identified.

### Routing

- Queues are complete.
- Skills are complete.
- Languages are complete.
- Routing is complete.

### Architect

- All flows are developed.
- Error handling is implemented.
- Integrations are implemented.
- Flow versions are documented.

### Integrations

- Data Actions are complete.
- APIs are connected.
- Authentication works.
- Error handling works.

### WEM / QM

- WFM configured.
- QM configured.
- Recording configured.

### Reporting

- Required reports exist.
- Required dashboards exist.
- Permissions are correct.

### Agent

- Agent experience is complete.
- Required workflows are functional.

---

# 46. Phase Deliverables

Phase 06 should produce, where applicable:

1. User configuration
2. Team configuration
3. Queue configuration
4. Skill configuration
5. Language configuration
6. Routing configuration
7. Voice configuration
8. Number configuration
9. Inbound call routing
10. Architect flows
11. IVR
12. Customer identification
13. Customer authentication
14. Self-service
15. Callback
16. Transfer / escalation
17. Digital channels
18. Messaging
19. Email
20. Outbound
21. WFM
22. QM
23. Recording
24. Performance management
25. Analytics
26. Reporting
27. Knowledge
28. Bots / virtual agents
29. Integrations
30. Data Actions
31. Agent experience
32. Supervisor experience
33. Business rules
34. Notifications
35. Automation
36. Unit test results
37. Defect register
38. Configuration documentation
39. Environment promotion records
40. Updated requirements traceability

---

# 47. Phase Dependencies

## Inputs

Phase 06 depends on:

**Phase 04 — Solution Architecture & Detailed Design**

and

**Phase 05 — Platform Foundation & Environment Build**

## Outputs

Phase 06 provides the configured solution for:

**Phase 07 — Integration & Data Migration**

and subsequently:

**Phase 08 — Testing & Validation**

---

# 48. Build Dependency Model

The detailed build should follow the dependency model below.

```text
Users / Roles
      ↓
Teams
      ↓
Queues
      ↓
Skills / Languages
      ↓
Routing
      ↓
Numbers
      ↓
Architect
      ↓
Data Actions
      ↓
Integrations
      ↓
Agent Experience
      ↓
Reporting
      ↓
Unit Testing
```

Additional capabilities may branch from this model:

```text
Queues
   ├── Voice
   ├── Digital
   ├── Email
   ├── Callback
   └── Outbound

Agents
   ├── WFM
   ├── QM
   ├── Recording
   └── Performance

Architect
   ├── IVR
   ├── Self-Service
   ├── Authentication
   ├── Data Actions
   └── Bots
```

---

# 49. Parallel Build Opportunities

Where dependencies permit, the following workstreams can be developed concurrently:

```text
                         ┌── Voice
                         │
                         ├── Architect
                         │
Foundation ──────────────┼── Digital
                         │
                         ├── Email
                         │
                         ├── Outbound
                         │
                         ├── WFM / QM
                         │
                         └── Reporting
```

Integration development may also proceed in parallel once the required API contracts and authentication mechanisms are available.

---

# 50. Build Quality Standards

All configuration should meet the following standards.

## Accuracy

Configuration must match the approved design.

## Consistency

Naming and configuration patterns must be consistent.

## Security

Least privilege must be maintained.

## Reusability

Common functionality should be implemented as reusable components where practical.

## Maintainability

Configuration must be understandable to BAU administrators.

## Traceability

Major configuration must trace back to a requirement and design.

## Automation

Repeatable configuration should be automated where appropriate.

## Documentation

Configuration must be documented during implementation.

---

# 51. Phase 06 Effort Considerations

Effort varies substantially based on the feature scope.

## Complexity Factors

Consider:

- Number of queues
- Number of skills
- Number of languages
- Number of agents
- Number of Architect flows
- Number of menus
- Number of prompts
- Number of Data Actions
- Number of integrations
- Number of digital channels
- Number of email queues
- Number of outbound campaigns
- WFM complexity
- QM complexity
- Recording requirements
- Reporting requirements
- Knowledge base size
- Bot complexity
- Self-service complexity
- Automation requirements
- Number of environments

---

# 52. Feature Complexity Classification

Each feature should be classified.

## Basic

Simple configuration with limited dependencies.

Examples:

- Basic queue
- Basic skill
- Basic language
- Basic team
- Basic report

## Medium

Configuration involving multiple objects or business rules.

Examples:

- Skills-based routing
- Multi-level IVR
- Callback
- CRM integration
- QM configuration
- WFM configuration

## Complex

Configuration involving multiple systems, complex logic or significant development.

Examples:

- Complex self-service
- Multiple CRM integrations
- Complex authentication
- Advanced bot
- Multi-stage Architect flow
- Complex outbound campaign
- Advanced WFM
- Extensive automation

---

# 53. Recommended Task Decomposition

The master deployment spreadsheet should break Phase 06 into task-level activities.

Recommended columns:

| Column | Description |
|---|---|
| Phase | Phase number |
| Workstream | Feature workstream |
| Task ID | Unique identifier |
| Parent Task | Parent task |
| Task | Task description |
| Description | Detailed activity |
| Requirement ID | Requirement traceability |
| Design ID | Design traceability |
| Dependency | Predecessor |
| Role | Primary resource |
| Customer Role | Customer dependency |
| Environment | DEV / SIT / UAT / PROD |
| Automation | Manual / Automated / Hybrid |
| Effort Hours | Estimated effort |
| Duration | Elapsed duration |
| Critical Path | Yes / No |
| Deliverable | Output |
| Acceptance Criteria | Completion condition |
| Test ID | Unit test reference |
| Status | Planned / In Progress / Complete |
| Notes | Additional information |

---

# 54. Recommended Task ID Structure

Phase 06 task identifiers should use a consistent structure.

Example:

```text
P06-001
P06-002
P06-003
```

For detailed workstreams:

```text
P06-Q-001
P06-Q-002

P06-ARCH-001
P06-ARCH-002

P06-INT-001
P06-INT-002

P06-WFM-001
P06-WFM-002
```

The final master spreadsheet should use one consistent ID strategy across the entire deployment methodology.

---

# 55. Phase 06 Definition of Done

Phase 06 is considered complete when:

- Required configuration is complete.
- Required features are built.
- Required queues exist.
- Skills are configured.
- Languages are configured.
- Routing is configured.
- Voice configuration is complete.
- Inbound routing is complete.
- Architect flows are complete.
- Self-service is complete where applicable.
- Callback is complete where applicable.
- Digital channels are complete where applicable.
- Email is complete where applicable.
- Outbound is complete where applicable.
- WFM is complete where applicable.
- QM is complete where applicable.
- Recording is complete.
- Reporting is complete.
- Knowledge is complete where applicable.
- Bots are complete where applicable.
- Integrations required for the build are configured.
- Data Actions are complete.
- Agent experience is configured.
- Supervisor experience is configured.
- Business rules are implemented.
- Automation is implemented where applicable.
- Unit testing is complete.
- Test evidence exists.
- Critical defects are resolved.
- Configuration documentation is complete.
- Requirements traceability is updated.
- Configuration has been promoted to the required test environment.
- Solution is ready for Phase 07 and Phase 08 activities.

---

# 56. Phase Gate — Gate 06: Solution Build Complete

## Entry Criteria

- Gate 05 passed.
- Foundation environment is available.
- Detailed design is approved.
- Build resources are available.
- Required customer dependencies are available.

## Exit Criteria

The solution build is complete when:

- All in-scope features are configured.
- All in-scope custom development is complete.
- All required Architect flows are developed.
- All required routing is configured.
- All required queues, skills and languages are configured.
- Voice functionality is built.
- Digital functionality is built where applicable.
- Email functionality is built where applicable.
- Outbound functionality is built where applicable.
- WEM is configured where applicable.
- QM is configured where applicable.
- Recording is configured.
- Reporting is configured.
- Knowledge is configured where applicable.
- Bots are configured where applicable.
- Integrations are implemented.
- Data Actions are implemented.
- Agent experience is configured.
- Supervisor experience is configured.
- Unit testing is complete.
- Test evidence is available.
- Critical build defects are resolved.
- Configuration documentation is complete.
- Requirements traceability is updated.
- Solution is ready for formal integration and system testing.

## Gate Decision

**Gate 06 — SOLUTION BUILD COMPLETE**

Status:

- **PASS** — Solution ready for integration/system testing
- **PASS WITH CONDITIONS** — Testing may commence with documented actions
- **HOLD** — Build issues remain
- **FAIL** — Solution build incomplete

---

# 57. Key Roles

| Role | Responsibility |
|---|---|
| Project Manager | Coordinate build |
| Solution Architect | Ensure architecture alignment |
| Genesys Cloud Architect | Own platform solution |
| Genesys Cloud Engineer | Configure Genesys Cloud |
| Architect Developer | Develop Architect flows |
| Routing Specialist | Configure routing |
| Telephony Engineer | Configure voice |
| Digital Specialist | Configure digital |
| WFM Specialist | Configure WFM |
| QM Specialist | Configure QM |
| Reporting Specialist | Configure analytics |
| Integration Engineer | Develop integrations |
| API Developer | Develop Data Actions / APIs |
| Automation Engineer | Develop Terraform / automation |
| CRM Specialist | Configure CRM integration |
| Security Engineer | Validate security |
| Test Lead | Coordinate unit testing |
| Customer SME | Validate business behaviour |
| Customer Technical Lead | Validate technical implementation |

---

# 58. Risks

Potential Phase 06 risks include:

### Architecture Drift

Build decisions may diverge from approved architecture.

### Scope Expansion

New requirements may be introduced during configuration.

### Integration Dependency

Build may be blocked by unavailable APIs, credentials or test systems.

### Architect Complexity

Complex IVR and self-service logic may require substantially more development than basic configuration.

### Data Dependency

Incomplete customer data may prevent accurate testing.

### Licensing

Some features may require additional licensing.

### Automation Complexity

Automating complex configuration may initially require greater effort than manual configuration.

### Environment Differences

Configuration may behave differently between environments.

### Customer Availability

SME availability may delay validation.

---

# 59. Change Control

Any material change to approved design during build must follow project change control.

## Changes Should Capture

- Change ID
- Requirement
- Current design
- Proposed change
- Reason
- Impact
- Effort
- Schedule impact
- Risk
- Approval
- Updated design
- Updated test requirements

No significant architectural change should be implemented without updating the appropriate design documentation.

---

# 60. Build Traceability Model

The final build should provide full traceability:

```text
Business Requirement
        ↓
Functional Requirement
        ↓
Solution Architecture
        ↓
Detailed Design
        ↓
Build Task
        ↓
Genesys Configuration
        ↓
Unit Test
        ↓
Integration Test
        ↓
UAT
```

This traceability should eventually allow project teams to answer:

**"Why does this configuration exist?"**

by tracing it back to the originating requirement.

---

# 61. Transition to Phase 07

Phase 06 should not attempt to complete every migration activity.

The focus is:

**Build the solution.**

Phase 07 will focus on:

**Integrate the solution and migrate required data.**

The transition is:

```text
Phase 06
Feature Configuration & Solution Build
             ↓
Configured Solution
             ↓
Phase 07
Integration & Data Migration
             ↓
Integrated Solution
             ↓
Phase 08
Testing & Validation
```

---

# 62. Layer 1 Position

| Phase | Status |
|---|---|
| **01 — Project Initiation & Mobilisation** | Baseline |
| **02 — Discovery & Current-State Assessment** | Baseline |
| **03 — Requirements & Solution Definition** | Baseline |
| **04 — Solution Architecture & Detailed Design** | Baseline |
| **05 — Platform Foundation & Environment Build** | Baseline |
| **06 — Feature Configuration & Solution Build** | **Defined** |
| 07 — Integration & Data Migration | Next |
| 08 — Testing & Validation | Pending |
| 09 — Operational Readiness & Cutover Preparation | Pending |
| 10 — Production Deployment & Go-Live | Pending |
| 11 — Hypercare & Stabilisation | Pending |
| 12 — BAU Handover & Project Closure | Pending |

---

## Reference

**Methodology:** Genesys Cloud Deployment Project Template  
**Phase:** 06 — Feature Configuration & Solution Build  
**Phase Gate:** Gate 06 — Solution Build Complete  
**Previous Phase:** 05 — Platform Foundation & Environment Build  
**Next Phase:** 07 — Integration & Data Migration
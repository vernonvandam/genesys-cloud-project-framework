# Layer 10 — Estimation, Resourcing & Project Planning

## Purpose

Layer 10 converts the entire Genesys Cloud deployment methodology into a practical project planning and estimation model.

Layer 10 answers:

> **How much effort will this require, who will do it, and in what order?**

This is the final layer because it consumes information from Layers 1–9.

# Objective

Create a reusable master deployment spreadsheet that can be used to:

- Build project schedules.
- Estimate effort.
- Identify resources.
- Identify customer responsibilities.
- Identify dependencies.
- Identify critical path.
- Calculate duration.
- Track deliverables.
- Track acceptance.
- Compare planned versus actual effort.

# Master Task Structure

Every task should ultimately contain:

| Field | Purpose |
|---|---|
| Task ID | Unique identifier |
| Layer | Methodology layer |
| Phase | Layer 1 phase |
| Workstream | Functional workstream |
| Capability | Genesys capability |
| Parent Task | Task hierarchy |
| Task | Individual activity |
| Description | Detailed work |
| Task Type | Required / Conditional / Optional |
| Dependencies | Predecessors |
| Role | Primary delivery role |
| Customer Responsibility | Customer-owned work |
| Environment | DEV / TEST / UAT / PROD / BAU |
| Effort | Estimated hours |
| Duration | Elapsed time |
| Deliverable | Output |
| Acceptance Criteria | Completion requirement |
| Critical Path | Yes / No |
| Status | Project status |
| Evidence | Evidence reference |
| Notes | Additional information |

# Estimation Model

Effort should not be estimated using a single project-level percentage.

Instead:

```text
Base Task
    +
Capability Complexity
    +
Volume
    +
Integration Complexity
    +
Telephony Complexity
    +
Digital Complexity
    +
WFM / QM
    +
AI
    +
Migration
    +
Security
    +
Compliance
    +
Automation
    +
Customer Complexity
    =
Estimated Effort
```

# Estimation Drivers

Potential factors include:

## Organisation

- Number of organisations
- Regions
- Divisions
- Countries
- Languages

## Users

- Total users
- Agents
- Supervisors
- Administrators
- External users

## Routing

- Queues
- Skills
- Languages
- Routing models
- Overflow complexity

## Architect

- Number of flows
- Complexity
- Data Actions
- Data Tables
- Bots
- Integrations

## Telephony

- Sites
- Numbers
- Carriers
- BYOC
- SIP
- Countries
- Emergency services

## Digital

- Channels
- Message types
- Bots
- Digital flows

## Integrations

- Number of integrations
- Complexity
- API count
- Middleware
- External dependencies

## WFM

- Business units
- Management units
- Forecasting
- Scheduling
- Adherence

## QM

- Evaluation forms
- Policies
- Recording
- Coaching

## AI

- Bots
- Knowledge
- Agent assistance
- AI configuration
- AI governance

## Migration

- User migration
- Configuration migration
- Data volume
- Historical data
- Data cleansing

## Security

- SSO
- IAM
- MFA
- Compliance
- Security testing

## Automation

- Terraform
- CI/CD
- Custom scripts
- APIs
- Automation coverage

# Role Framework

Potential roles:

- Project Manager
- Business Analyst
- Solution Architect
- Technical Architect
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Telephony Engineer
- Integration Engineer
- CRM Specialist
- Network Engineer
- Security Architect
- IAM Specialist
- Terraform / DevOps Engineer
- Data Engineer
- Migration Specialist
- Test Manager
- Test Analyst
- WFM Specialist
- QM Specialist
- Reporting Specialist
- Training Lead
- Change Manager
- Service Management Lead

# Customer Responsibilities

Tasks must explicitly identify customer-owned activities.

Examples:

- Requirements approval
- Architecture approval
- Security approval
- IAM configuration
- CRM configuration
- Carrier engagement
- Test execution
- UAT
- Business acceptance
- Training
- BAU readiness

# Dependency Model

The spreadsheet must support predecessor relationships.

Example:

```text
Requirements
     ↓
Architecture
     ↓
Foundation
     ↓
Configuration
     ↓
Integration
     ↓
Testing
     ↓
UAT
     ↓
Cutover
     ↓
Go-Live
     ↓
Hypercare
     ↓
BAU
```

# Critical Path

Tasks should be flagged:

- Yes
- No

Critical path should consider:

- Customer dependencies
- Carrier dependencies
- Security approvals
- Integration dependencies
- Testing
- UAT
- Change windows
- Go-live
- BAU acceptance

# Conditional Tasks

The master template must not assume every project requires every capability.

Use:

```text
REQUIRED
CONDITIONAL
OPTIONAL
NOT APPLICABLE
```

# Project Complexity Model

Projects should ultimately be classified using factors such as:

- Small
- Medium
- Large
- Enterprise

Potential complexity dimensions:

- Users
- Sites
- Countries
- Queues
- Architect
- Telephony
- Integrations
- Digital
- WFM
- QM
- AI
- Migration
- Security
- Compliance
- Automation

# Estimation Calibration

After each project compare:

```text
Estimated Effort
       vs
Actual Effort
```

Capture variance by:

- Phase
- Workstream
- Capability
- Role
- Task

Use this data to improve future estimates.

# Estimation Confidence

Each estimate should eventually include:

- Low estimate
- Expected estimate
- High estimate
- Confidence

Example:

```text
Low       Expected       High
 |-----------|------------|
 8h         12h           20h
```

# Master Spreadsheet

The eventual workbook should contain, at minimum:

## Sheet 1 — Master Tasks

Complete task catalogue.

## Sheet 2 — Estimates

Effort and duration model.

## Sheet 3 — Roles

Role definitions and rates.

## Sheet 4 — Capabilities

Genesys Cloud capability catalogue.

## Sheet 5 — Dependencies

Task dependency model.

## Sheet 6 — Risks

Risk catalogue.

## Sheet 7 — Assumptions

Estimation assumptions.

## Sheet 8 — Customer Responsibilities

Customer task catalogue.

## Sheet 9 — Deliverables

Deliverable register.

## Sheet 10 — Phase Gates

Gate criteria.

## Sheet 11 — Complexity Model

Project complexity scoring.

## Sheet 12 — Actuals

Planned versus actual effort.

# Task Granularity

A task should be granular enough that it can be:

- Assigned to one primary role.
- Estimated independently.
- Given a dependency.
- Given acceptance criteria.
- Tracked independently.

Avoid tasks such as:

> Configure Genesys Cloud

Prefer:

> Configure queue

> Configure queue membership

> Configure skills

> Configure routing method

> Configure overflow

> Validate queue routing

# Estimation Workflow

```text
Select Project Scope
        ↓
Select Capabilities
        ↓
Apply Conditional Tasks
        ↓
Generate Task Catalogue
        ↓
Apply Complexity Factors
        ↓
Assign Roles
        ↓
Calculate Effort
        ↓
Apply Dependencies
        ↓
Calculate Duration
        ↓
Identify Critical Path
        ↓
Review Customer Responsibilities
        ↓
Finalise Project Plan
```

# Relationship to Other Layers

Layer 10 consumes all previous layers.

```text
Layer 1
Lifecycle
   ↓
Layer 2
Capabilities
   ↓
Layer 3
Governance
   ↓
Layer 4
Technical Delivery
   ↓
Layer 5
Integration / Migration
   ↓
Layer 6
Testing
   ↓
Layer 7
Security
   ↓
Layer 8
Automation / IaC
   ↓
Layer 9
BAU
   ↓
Layer 10
Estimation Engine
```

# Future Documentation

```text
README.md
TASK-CATALOGUE.md
ROLE-CATALOGUE.md
EFFORT-MODEL.md
COMPLEXITY-MODEL.md
DEPENDENCY-MODEL.md
CUSTOMER-RESPONSIBILITIES.md
ESTIMATION-ASSUMPTIONS.md
CRITICAL-PATH.md
SPREADSHEET-DESIGN.md
CALIBRATION.md
```

# Definition of Done

Layer 10 is complete when the methodology can be converted into a master spreadsheet that:

- Contains every relevant implementation task.
- Identifies the appropriate phase.
- Identifies the capability.
- Identifies the workstream.
- Identifies dependencies.
- Identifies roles.
- Identifies customer responsibilities.
- Estimates effort.
- Estimates duration.
- Identifies deliverables.
- Defines acceptance criteria.
- Identifies critical path.
- Supports conditional scope.
- Supports project complexity.
- Supports planned-versus-actual analysis.
- Can be reused as a template across Genesys Cloud projects.

# Final Methodology Output

The ultimate output of Layer 10 is:

```text
Genesys Cloud Deployment Scope
            ↓
Capability Selection
            ↓
Task Generation
            ↓
Dependencies
            ↓
Roles
            ↓
Effort
            ↓
Duration
            ↓
Critical Path
            ↓
Customer Responsibilities
            ↓
Deliverables
            ↓
Acceptance Criteria
            ↓
MASTER GENESYS CLOUD
PROJECT PLAN
```

# Final Definition of the 10-Layer Methodology

The complete methodology consists of:

1. **Layer 1 — Deployment Lifecycle**
   - When does the work happen?

2. **Layer 2 — Genesys Cloud Capability Framework**
   - What are we deploying?

3. **Layer 3 — Governance, Architecture & Controls**
   - What controls surround it?

4. **Layer 4 — Technical Delivery Framework**
   - How do we engineer it?

5. **Layer 5 — Integration, Data & Migration Framework**
   - How does information move?

6. **Layer 6 — Testing & Quality Framework**
   - How do we prove it works?

7. **Layer 7 — Security, Compliance & Risk**
   - How do we secure and govern it?

8. **Layer 8 — Automation, Terraform & DevOps**
   - How do we make it repeatable?

9. **Layer 9 — Operations & BAU Framework**
   - How do we operate it?

10. **Layer 10 — Estimation, Resourcing & Project Planning**
    - How much effort does it require and how do we turn it into a project plan?

The combined layers form the enterprise Genesys Cloud deployment methodology.
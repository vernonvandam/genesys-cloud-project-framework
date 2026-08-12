# Layer 2 — Genesys Cloud Capability Framework

## Purpose

Layer 2 defines the complete catalogue of Genesys Cloud capabilities that may be included in an implementation.

Layer 2 answers:

> **What are we deploying?**

It provides the capability inventory required to ensure the master deployment methodology does not omit important Genesys Cloud functionality.

## Objective

Create a reusable capability framework that:

- Covers the Genesys Cloud platform comprehensively.
- Identifies capabilities that are required, conditional or optional.
- Maps capabilities to Layer 1 lifecycle phases.
- Identifies dependencies between capabilities.
- Provides the basis for detailed implementation tasks.
- Supports project estimation.
- Supports solution architecture.
- Supports scope definition.
- Supports testing.
- Supports BAU operations.

# Capability Domains

## 2.1 Core Platform

- Organisation
- Region
- Divisions
- Users
- Groups
- Roles
- Permissions
- Locations
- Sites
- Work teams
- Policies
- Configuration

## 2.2 Identity & Access

- SSO
- SAML
- OAuth
- MFA
- Identity provider
- SCIM
- User provisioning
- Role mapping
- Access governance

## 2.3 Telephony

- Genesys Cloud Voice
- BYOC Cloud
- BYOC Premises
- SIP
- Carrier
- DID
- Toll-free
- Number porting
- Sites
- Edges
- Phones
- Network
- Emergency services
- Number plans
- Outbound routes
- Caller ID

## 2.4 Architect

- Inbound voice flows
- Inbound messaging flows
- Chat flows
- Email flows
- Callback
- Outbound flows
- In-queue flows
- Secure flows
- Bot flows
- Common modules
- Data Actions
- Data Tables
- Prompts
- Schedules
- Business hours
- Holiday schedules

## 2.5 Routing

- Queues
- Skills
- Languages
- Routing methods
- Bullseye routing
- Priority
- Preferred agents
- Queue membership
- Overflow
- Callback
- Transfer
- Utilisation
- Routing rules

## 2.6 Digital

- Web messaging
- Web chat
- Email
- SMS
- Open messaging
- Social messaging
- Digital routing
- Digital bots
- Digital Architect flows

## 2.7 Workforce Management

- Business units
- Management units
- Planning groups
- Forecasting
- Scheduling
- Time off
- Adherence
- Intraday management
- WFM integrations
- WFM reporting

## 2.8 Quality Management

- Recording
- Evaluation forms
- Evaluation policies
- Quality programs
- Calibration
- Coaching
- Quality reporting

## 2.9 Recording

- Recording policies
- Recording retention
- Recording access
- Secure pause
- Playback
- Export
- Recording search
- Compliance

## 2.10 Analytics & Reporting

- Performance views
- Interaction analytics
- Speech and text analytics
- Dashboards
- Reports
- Scheduled reports
- Data exports
- APIs
- KPI reporting

## 2.11 AI

- Virtual Agent
- Bots
- Knowledge
- Agent assistance
- Copilots
- Summarisation
- Sentiment
- Intent
- Predictive capabilities
- AI-powered quality
- AI-powered WFM
- AI governance

## 2.12 Integrations

- CRM
- IAM
- ERP
- ITSM
- WFM
- QM
- Middleware
- Customer databases
- Custom applications
- APIs
- Webhooks
- Data Actions

## 2.13 APIs & Extensibility

- Platform APIs
- Conversations APIs
- Analytics APIs
- Users APIs
- Routing APIs
- Architect APIs
- Notifications
- OAuth clients
- SDKs
- Custom applications

# Capability Classification

Every capability must be classified as:

- Required
- Conditional
- Optional
- Not Applicable

## Required

Capabilities necessary for the specific project.

## Conditional

Capabilities dependent on project requirements, architecture, geography, licensing or customer environment.

## Optional

Capabilities that may add value but are not required.

## Not Applicable

Capabilities explicitly excluded from the solution.

# Capability Record

Each capability should ultimately have:

- Capability ID
- Capability domain
- Capability name
- Description
- Business purpose
- Dependencies
- Prerequisites
- Licensing
- Architecture considerations
- Configuration tasks
- Integration requirements
- Security considerations
- Testing requirements
- Migration requirements
- Operational requirements
- BAU owner
- Layer 1 phase mapping
- Estimated effort
- Complexity factors

# Capability-to-Phase Mapping

Example:

```text
Capability
    ↓
Discovery
    ↓
Requirements
    ↓
Architecture
    ↓
Build
    ↓
Integration
    ↓
Testing
    ↓
Go-Live
    ↓
BAU
```

Not every capability participates in every phase.

# Future Documentation

Layer 2 should eventually be expanded into:

```text
README.md
CAPABILITY-CATALOGUE.md
CORE-PLATFORM.md
IDENTITY.md
TELEPHONY.md
ARCHITECT.md
ROUTING.md
DIGITAL.md
WFM.md
QM.md
RECORDING.md
ANALYTICS.md
AI.md
INTEGRATIONS.md
APIS.md
```

# Definition of Done

Layer 2 is complete when all significant Genesys Cloud capabilities have been catalogued, classified, mapped to the lifecycle and made available as inputs to the project estimation model.
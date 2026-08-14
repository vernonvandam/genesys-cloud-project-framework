# Layer 10 — 05 Architect Task Catalogue

## Purpose

This directory contains the Layer 10 implementation task catalogue for the **05 — Architect** capability domain.

The catalogue decomposes the Layer 2 Architect capability catalogue into implementation-level tasks that can be used to:

- build a project delivery schedule
- estimate implementation effort
- identify dependencies
- assign delivery roles
- identify customer responsibilities
- determine environment requirements
- establish critical-path activities
- define implementation deliverables
- establish acceptance criteria
- support spreadsheet-based estimation and project planning

## Repository Location

```text
Layer 10 — Estimation, Resourcing & Project Planning
└── 01-task-catalogue
    └── 05-architect
```

## Layer 2 Domain

**Layer 2 Domain:** 05 — Architect

Architect provides the orchestration layer for Genesys Cloud customer and agent interaction experiences.

The domain covers:

- Architect architecture
- Flow strategy and governance
- Inbound call flows
- In-queue call flows
- Secure call flows
- Workflow automation
- Common Modules
- Bot flows
- Digital bot flows
- Menu design
- IVR navigation
- Prompt management
- Text-to-Speech
- Speech recognition
- DTMF and keypad input
- Data collection
- Variables and expressions
- Data Tables
- Data Actions
- External integrations
- Customer context and lookup
- Authentication and verification
- Routing orchestration
- Queue and ACD integration
- Schedule and business hours
- Holiday and closure handling
- Callback and queue exit
- Transfer and escalation
- Error handling and recovery
- Disconnect and completion
- Flow security and sensitive data
- Flow testing and validation
- Flow versioning and promotion
- Flow migration and cutover
- Architect operations and BAU
- Architect optimisation and governance

## Task Catalogue Structure

Each capability is represented by an individual Markdown file.

```text
05-architect/
│
├── README.md
├── 01-architect-architecture.md
├── 02-flow-strategy-governance.md
├── 03-inbound-call-flows.md
├── 04-in-queue-call-flows.md
├── 05-secure-call-flows.md
├── 06-workflow-automation.md
├── 07-common-modules.md
├── 08-bot-flows.md
├── 09-digital-bot-flows.md
├── 10-menu-design.md
├── 11-ivr-navigation.md
├── 12-prompt-management.md
├── 13-text-to-speech.md
├── 14-speech-recognition.md
├── 15-dtmf-keypad-input.md
├── 16-data-collection.md
├── 17-variables-expressions.md
├── 18-data-tables.md
├── 19-data-actions.md
├── 20-external-integrations.md
├── 21-customer-context-lookup.md
├── 22-authentication-verification.md
├── 23-routing-orchestration.md
├── 24-queue-acd-integration.md
├── 25-schedule-business-hours.md
├── 26-holiday-closure-handling.md
├── 27-callback-queue-exit.md
├── 28-transfer-escalation.md
├── 29-error-handling-recovery.md
├── 30-disconnect-completion.md
├── 31-flow-security-sensitive-data.md
├── 32-flow-testing-validation.md
├── 33-flow-versioning-promotion.md
├── 34-flow-migration-cutover.md
├── 35-architect-operations-bau.md
└── 36-architect-optimisation-governance.md
```

## Task ID Convention

```text
L10-05.XX-###
```

Where:

- `L10` = Layer 10
- `05` = Architect domain
- `XX` = capability number
- `###` = sequential implementation task

Example:

```text
L10-05.03-001
```

represents the first implementation task for capability `2.05.03 — Inbound Call Flows`.

## Standard Task Attributes

Every implementation task contains:

| Attribute | Purpose |
|---|---|
| Task Type | REQUIRED / CONDITIONAL / OPTIONAL / VALIDATION |
| Layer 1 Phase | Primary lifecycle phase |
| Primary Role | Delivery owner |
| Customer Responsibility | YES / NO / JOINT |
| Environment | DESIGN / DEV / TEST / UAT / PROD / MULTI |
| Automation | MANUAL / PARTIAL / AUTOMATED |
| Baseline Effort | Initial estimation baseline |
| Critical Path | YES / NO / CONDITIONAL |

## Layer 1 Mapping

Architect tasks map to the Layer 1 deployment lifecycle:

| Phase | Lifecycle |
|---|---|
| P01 | Project Initiation & Mobilisation |
| P02 | Discovery & Current-State Assessment |
| P03 | Requirements & Solution Definition |
| P04 | Solution Architecture & Detailed Design |
| P05 | Platform Foundation & Environment Build |
| P06 | Feature Configuration & Solution Build |
| P07 | Integration & Data Migration |
| P08 | Testing & Validation |
| P09 | Operational Readiness & Cutover Preparation |
| P10 | Production Deployment & Go-Live |
| P11 | Hypercare & Stabilisation |
| P12 | BAU Handover & Project Closure |

## Estimation Principle

The effort values contained in this catalogue are **baseline estimation values**, not fixed delivery commitments.

Actual effort should be calibrated based on:

- number of flows
- flow complexity
- number of menus
- number of languages
- number of prompts
- number of queues
- number of integrations
- API complexity
- Data Action complexity
- Data Table complexity
- authentication complexity
- bot complexity
- number of environments
- migration complexity
- testing requirements
- customer review cycles
- approval cycles
- automation requirements
- Terraform requirements
- existing configuration quality

## Definition of Done

The Architect task catalogue is complete when:

- all 36 Layer 2 Architect capabilities are represented
- every capability has implementation tasks
- tasks are mapped to Layer 1
- dependencies are identified
- roles are identified
- customer responsibilities are identified
- environments are identified
- baseline effort is provided
- deliverables are defined
- acceptance criteria are defined
- critical-path tasks are identified
- the catalogue can be transformed into the Layer 10 spreadsheet model
# Layer 10 — Schedule Structure Model

## Purpose

This document defines the standard structural model for representing a Genesys Cloud implementation project schedule.

The schedule structure converts individual Layer 10 implementation tasks into an organised project plan while preserving traceability to:

- Layer 1
- Layer 2
- Layer 10 Task Catalogue
- Task Standards
- Estimation Model
- Role Catalogue
- Dependency Model

---

# 1. Schedule Hierarchy

The standard hierarchy is:

```text
Project
    ↓
Layer 1 Phase
    ↓
Workstream
    ↓
Layer 2 Domain
    ↓
Capability
    ↓
Task
```

Milestones and phase gates exist as schedule control objects alongside task activities.

---

# 2. Project Level

The project level represents the complete Genesys Cloud deployment.

The project record should contain:

- Project ID
- Project Name
- Customer
- Programme
- Project Manager
- Solution Architect
- Planned Start
- Planned Finish
- Target Go-Live
- Deployment Model
- Delivery Method
- Schedule Status
- Schedule Baseline Date

---

# 3. Layer 1 Phase Level

Layer 1 phases provide the lifecycle framework.

Each task must map to one primary Layer 1 phase.

The schedule should be capable of reporting:

```text
Project
    ↓
Layer 1 Phase
    ↓
Total Tasks
    ↓
Total Effort
    ↓
Duration
    ↓
Milestones
```

Layer 1 phase IDs must use the authoritative IDs defined in Layer 1.

---

# 4. Workstream Level

Workstreams group related implementation activity.

Typical workstreams include:

- Project Management
- Architecture
- Core Platform
- Identity & Access
- Voice & Telephony
- ACD & Routing
- Architect
- Digital
- WFM & Employee Engagement
- Data, Integrations & APIs
- Analytics & Reporting
- Quality Management
- Security & Compliance
- Testing & Validation
- Migration
- Deployment
- Operations & Handover
- Optimisation

Workstream naming should remain consistent across the framework.

---

# 5. Layer 2 Domain Level

Each task must retain its Layer 2 domain relationship.

This allows the project schedule to report effort and duration by capability domain.

Example:

```text
Layer 2 Domain
11 — Security, Compliance & Governance
        ↓
Capability
Role-Based Access Control
        ↓
Task
Configure required roles
```

---

# 6. Capability Level

The capability level identifies the specific Layer 2 capability being implemented.

The capability is the primary functional grouping beneath the Layer 2 domain.

Tasks must not be created without a valid capability mapping unless they are explicitly classified as cross-cutting project-management or methodology tasks.

---

# 7. Task Level

The task is the fundamental schedule activity.

A task must have:

- unique Task ID
- task name
- description
- Layer 1 phase
- Layer 2 domain
- capability
- task type
- primary role
- customer responsibility
- environment
- effort
- duration
- dependencies
- deliverable
- acceptance criteria
- critical-path classification

---

# 8. Schedule Activity Attributes

The schedule should support the following standard fields.

| Field | Description |
|---|---|
| Task ID | Unique Layer 10 task identifier |
| Task Name | Concise task name |
| Description | Implementation outcome |
| Layer 1 Phase | Primary deployment phase |
| Layer 2 Domain | Capability domain |
| Layer 2 Capability | Capability being implemented |
| Workstream | Delivery workstream |
| Task Type | REQUIRED / CONDITIONAL / VALIDATION |
| Primary Role | Accountable delivery role |
| Customer Responsibility | Delivery Team / Customer / Joint |
| Environment | DESIGN / DEV / TEST / UAT / PROD / MULTI |
| Automation | MANUAL / AUTOMATED / HYBRID |
| Baseline Effort | Standard effort |
| Project Effort | Adjusted project effort |
| Duration | Planned elapsed duration |
| Predecessor | Immediate predecessor task(s) |
| Successor | Downstream task(s) |
| Start Date | Planned start |
| Finish Date | Planned finish |
| Milestone | Associated milestone |
| Phase Gate | Associated gate |
| Critical Path | YES / NO / CONDITIONAL |
| Schedule Status | Current execution status |
| Deliverable | Expected output |
| Acceptance Criteria | Completion conditions |
| Assumptions | Relevant assumptions |

---

# 9. Schedule Object Types

The schedule should support at least four object types:

```text
TASK
MILESTONE
PHASE GATE
SUMMARY
```

### TASK

Represents executable project work.

### MILESTONE

Represents a measurable project achievement or significant event.

### PHASE GATE

Represents a controlled transition requiring defined entry and exit conditions.

### SUMMARY

Represents a grouping of tasks and schedule objects.

---

# 10. Task ID Integrity

Task IDs originate from Layer 10/01.

The schedule must not create alternate task identifiers.

Example:

```text
Authoritative Task ID

L10-01.01-001
```

The schedule may add a schedule-specific sequence or internal row number, but the authoritative Task ID must remain unchanged.

---

# 11. Schedule Dates

The schedule should support:

- Planned Start
- Planned Finish
- Actual Start
- Actual Finish
- Forecast Start
- Forecast Finish

This allows comparison between:

```text
Baseline
vs
Forecast
vs
Actual
```

---

# 12. Schedule Duration

Duration should represent elapsed working time.

Example:

```text
Effort = 16 hours
Duration = 4 working days
```

Duration must not be calculated simply as:

```text
Effort ÷ 8
```

without considering:

- resource allocation
- dependencies
- working calendar
- customer availability
- approvals
- waiting time
- environment availability

---

# 13. Summary Tasks

Summary tasks should represent meaningful groupings.

Examples:

```text
Voice & Telephony
    ├── Number Management
    ├── Carrier Configuration
    ├── SIP Configuration
    └── Voice Validation
```

Summary tasks should not contain independent effort that duplicates child tasks.

---

# 14. Schedule Calendars

The project schedule should support a defined project calendar.

Calendar considerations may include:

- working days
- public holidays
- customer holidays
- delivery team holidays
- weekends
- maintenance windows
- blackout periods
- production change windows
- restricted implementation periods

Calendar assumptions must be documented.

---

# 15. Baseline Structure

The schedule baseline should capture:

```text
Task
+
Dependency
+
Duration
+
Start
+
Finish
+
Milestone
+
Phase Gate
```

Baseline changes should be governed by project change control.

---

# 16. Schedule Reporting Dimensions

The schedule should support reporting by:

- Layer 1 phase
- workstream
- Layer 2 domain
- capability
- task
- task type
- primary role
- environment
- customer responsibility
- critical path
- milestone
- phase gate
- status

---

# 17. Schedule Traceability

The complete traceability chain is:

```text
Layer 1 Phase
        ↓
Layer 2 Domain
        ↓
Layer 2 Capability
        ↓
Layer 10 Task ID
        ↓
Schedule Activity
        ↓
Start / Finish
        ↓
Milestone / Gate
```

---

# 18. Definition of Done

The Schedule Structure Model is complete when:

- schedule hierarchy is defined
- schedule object types are defined
- task attributes are defined
- project-level attributes are defined
- date conventions are defined
- duration conventions are defined
- schedule calendars are defined
- summary-task rules are defined
- schedule reporting dimensions are defined
- Layer 1 and Layer 2 traceability is preserved
- Task IDs remain authoritative
- baseline and forecast dates can be represented
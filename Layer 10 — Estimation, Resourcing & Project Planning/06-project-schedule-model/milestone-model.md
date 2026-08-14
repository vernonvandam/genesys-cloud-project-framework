# Layer 10 — Milestone Model

## Purpose

This document defines the standard milestone model for Genesys Cloud implementation projects.

Milestones represent significant, measurable project outcomes or control points.

Milestones are not substitutes for implementation tasks.

---

# 1. Milestone Principles

Milestones should:

- represent a meaningful outcome
- have a clear completion condition
- be objectively measurable
- have an accountable owner
- have a planned date
- be traceable to project activities
- be used for project reporting
- support schedule control
- support governance

Milestones should not be created for trivial activities.

---

# 2. Milestone Categories

Standard milestone categories include:

```text
PROJECT
ARCHITECTURE
DESIGN
BUILD
INTEGRATION
TESTING
MIGRATION
DEPLOYMENT
GO-LIVE
OPERATIONAL
HANDOVER
CLOSURE
```

---

# 3. Milestone Structure

A milestone should contain:

| Attribute | Requirement |
|---|---|
| Milestone ID | REQUIRED |
| Milestone Name | REQUIRED |
| Category | REQUIRED |
| Description | REQUIRED |
| Layer 1 Phase | REQUIRED |
| Related Workstream | REQUIRED |
| Predecessors | REQUIRED |
| Planned Date | REQUIRED |
| Acceptance Criteria | REQUIRED |
| Owner | REQUIRED |
| Customer Approval | Where applicable |
| Status | REQUIRED |
| Critical Path | REQUIRED |

---

# 4. Milestone ID

Milestone IDs should be unique within the project.

Recommended format:

```text
MS-001
MS-002
MS-003
```

Milestone IDs are schedule identifiers and must not replace Layer 10 Task IDs.

---

# 5. Baseline Milestones

The baseline methodology should support milestone categories such as:

```text
MS-001 Project Initiation Complete
MS-002 Requirements Baseline Approved
MS-003 Architecture Approved
MS-004 Design Complete
MS-005 Build Complete
MS-006 Integration Readiness Complete
MS-007 System Testing Complete
MS-008 UAT Complete
MS-009 Production Readiness Approved
MS-010 Migration Rehearsal Complete
MS-011 Cutover Approved
MS-012 Production Deployment Complete
MS-013 Go-Live
MS-014 Hypercare Complete
MS-015 Operational Handover Complete
MS-016 Project Closure
```

These are baseline examples and should be adjusted for project scope.

---

# 6. Milestone Completion

A milestone is complete only when its acceptance condition has been satisfied.

Example:

```text
Milestone:
Architecture Approved

Completion Criteria:
- architecture documentation complete
- required reviews complete
- outstanding architecture decisions resolved
- customer approval obtained
```

---

# 7. Milestone Dependencies

Milestones should have explicit predecessors.

Example:

```text
Design Complete
        ↓
Build Complete
        ↓
System Testing Complete
        ↓
UAT Complete
        ↓
Production Readiness Approved
        ↓
Go-Live
```

---

# 8. Customer Approval Milestones

Where customer approval controls project progression, the approval should be represented as a milestone or explicit approval activity.

Examples:

- Architecture Approval
- Design Approval
- UAT Acceptance
- Production Approval
- Go-Live Approval
- Handover Acceptance

---

# 9. Critical Milestones

A milestone should be classified as critical where delay could affect:

- project completion
- major phase completion
- production deployment
- go-live
- contractual commitment
- customer acceptance
- operational handover

---

# 10. Milestone Status

Recommended statuses:

```text
PLANNED
AT RISK
DELAYED
ACHIEVED
CANCELLED
```

---

# 11. Milestone Reporting

The project should be capable of reporting:

- milestone baseline date
- forecast date
- actual date
- variance
- status
- owner
- dependencies
- downstream impact

---

# 12. Milestone Traceability

Milestones should trace to underlying work.

```text
Milestone
    ↓
Summary Activities
    ↓
Implementation Tasks
    ↓
Deliverables
    ↓
Acceptance Criteria
```

A milestone should not be considered complete merely because all tasks are marked complete if the milestone's acceptance condition has not been satisfied.

---

# 13. Milestone and Phase Gates

Milestones and phase gates are related but different.

```text
Milestone
Measures achievement.

Phase Gate
Controls progression.
```

Example:

```text
Milestone
System Testing Complete
        ↓
Phase Gate
UAT Entry Approved
        ↓
Milestone
UAT Complete
        ↓
Phase Gate
Production Readiness Approved
```

---

# 14. Definition of Done

The Milestone Model is complete when:

- milestone categories are defined
- milestone structure is defined
- milestone IDs are defined
- baseline milestones are defined
- milestone completion criteria are defined
- milestone dependencies are defined
- customer approval milestones are defined
- critical milestones are defined
- milestone status is defined
- milestone reporting is defined
- milestone traceability is defined
- milestone and phase-gate distinctions are defined
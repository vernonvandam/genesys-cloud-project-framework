# Layer 2.14.10 — Incident Management

## Capability Definition

Incident Management defines the process for restoring Genesys Cloud services following an operational interruption or degradation.

---

# 1. Scope

- Incident identification
- Incident logging
- Classification
- Prioritisation
- Investigation
- Escalation
- Communications
- Resolution
- Closure
- Incident reporting

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Review current incident process.
- Identify ITSM platform.
- Identify incident priorities.
- Identify support teams.
- Identify notification requirements.
- Identify business impact criteria.

---

# 4. Design Activities

- Define incident lifecycle.
- Define priority matrix.
- Define escalation rules.
- Define communications.
- Define resolution criteria.
- Define closure criteria.
- Define incident reporting.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.10-T01 | Assess existing incident process | Phase 2 | Service Manager | 4h |
| 2.14.10-T02 | Define Genesys Cloud incident categories | Phase 3 | Service Manager | 4h |
| 2.14.10-T03 | Define incident priority model | Phase 3 | Service Manager | 4h |
| 2.14.10-T04 | Define escalation workflow | Phase 4 | Operations Lead | 4h |
| 2.14.10-T05 | Create incident runbooks | Phase 9 | Operations Lead | 8h |
| 2.14.10-T06 | Test incident scenarios | Phase 9 | Test Lead | 6h |
| 2.14.10-T07 | Transition incident process | Phase 12 | Service Manager | 4h |

---

# 6. Dependencies

- Service Desk
- Support Model
- Monitoring
- Major Incident Management

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 10 — Production Deployment & Go-Live
- Phase 11 — Hypercare & Stabilisation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Service Manager
- Operations Lead
- L1/L2/L3 Support
- Incident Manager
- Test Lead

---

# 9. Customer Responsibilities

- Define business impact.
- Approve priorities.
- Provide incident management process.
- Participate in testing.

---

# 10. Testing

Execute representative P1–P4 incident scenarios.

---

# 11. Deliverables

- Incident Management Process
- Priority Matrix
- Incident Runbooks
- Escalation Procedures

---

# 12. Effort Drivers

ITSM complexity, number of services, support hours and criticality.

---

# 13. Acceptance Criteria

- Incident lifecycle documented.
- Priority model approved.
- Escalations tested.
- Closure criteria agreed.

---

# 14. Definition of Done

Genesys Cloud incidents can be consistently logged, prioritised, investigated, escalated, resolved and closed.
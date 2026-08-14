# Layer 2.14.14 — Change Management

## Capability Definition

Change Management controls modifications to Genesys Cloud configuration, integrations, infrastructure dependencies and operational processes.

---

# 1. Scope

- Change classification
- Change requests
- Impact assessment
- Approval
- Scheduling
- Testing
- Implementation
- Rollback
- Change closure

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Review existing change process.
- Identify change authorities.
- Identify change windows.
- Identify standard changes.
- Identify emergency changes.

---

# 4. Design Activities

- Define Genesys Cloud change categories.
- Define approval workflow.
- Define change impact assessment.
- Define rollback requirements.
- Define emergency change process.
- Define change documentation standards.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.14-T01 | Assess existing change process | Phase 2 | Service Manager | 4h |
| 2.14.14-T02 | Define Genesys Cloud change categories | Phase 3 | Service Manager | 4h |
| 2.14.14-T03 | Define approval and CAB requirements | Phase 3 | Change Manager | 4h |
| 2.14.14-T04 | Define rollback and validation standards | Phase 4 | Technical Architect | 4h |
| 2.14.14-T05 | Create change templates | Phase 9 | Operations Lead | 6h |
| 2.14.14-T06 | Test change workflow | Phase 9 | Test Lead | 4h |
| 2.14.14-T07 | Transition change management | Phase 12 | Change Manager | 2h |

---

# 6. Dependencies

- Configuration Management
- Release Management
- Incident Management
- Testing
- Governance

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 10 — Production Deployment & Go-Live
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Change Manager
- Service Manager
- Technical Architect
- Operations Lead
- Test Lead

---

# 9. Customer Responsibilities

- Provide change governance.
- Define CAB requirements.
- Approve change classifications.
- Participate in acceptance.

---

# 10. Testing

Test standard, normal and emergency change workflows.

---

# 11. Deliverables

- Change Management Process
- Change Templates
- Approval Matrix
- Rollback Standard

---

# 12. Effort Drivers

Governance complexity, change volume and business criticality.

---

# 13. Acceptance Criteria

- Change model approved.
- Templates available.
- Approval workflow tested.
- Rollback requirements documented.

---

# 14. Definition of Done

Genesys Cloud changes are controlled through an approved and repeatable change-management process.
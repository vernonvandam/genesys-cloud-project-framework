# Layer 2.14.25 — Routing Administration

## Capability Definition

Routing Administration provides the BAU processes for maintaining queues, skills, priorities, routing rules, agents and related ACD configuration.

---

# 1. Scope

- Queues
- Skills
- Skill proficiency
- Routing methods
- Priorities
- Bullseye routing
- Queue membership
- Agent assignment
- Routing troubleshooting

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Inventory routing configuration.
- Identify routing owners.
- Identify common routing changes.
- Identify operational dependencies.
- Identify approval requirements.

---

# 4. Design Activities

- Define routing administration model.
- Define standard routing changes.
- Define approval workflow.
- Define troubleshooting.
- Define routing validation.
- Define emergency procedures.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.25-T01 | Inventory routing configuration | Phase 2 | Routing Lead | 6h |
| 2.14.25-T02 | Define routing administration model | Phase 3 | Routing Lead | 4h |
| 2.14.25-T03 | Define routing change procedures | Phase 4 | Routing Lead | 6h |
| 2.14.25-T04 | Create routing runbooks | Phase 9 | Operations Lead | 8h |
| 2.14.25-T05 | Test routing administration scenarios | Phase 8 | Test Lead | 6h |
| 2.14.25-T06 | Transition routing administration | Phase 12 | Operations Lead | 4h |

---

# 6. Dependencies

- ACD/Routing
- Architect
- Identity & Access
- Change Management

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 6 — Feature Configuration & Solution Build
- Phase 8 — Testing & Validation
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Routing Lead
- Genesys Cloud Architect
- Operations Lead
- Test Lead

---

# 9. Customer Responsibilities

- Define routing owners.
- Approve routing changes.
- Provide operational SMEs.

---

# 10. Testing

Validate routing changes, queue membership, skills and priority behaviour.

---

# 11. Deliverables

- Routing Administration Guide
- Routing Runbooks
- Change Procedures

---

# 12. Effort Drivers

Queue count, skills, routing complexity and change frequency.

---

# 13. Acceptance Criteria

- Routing inventory complete.
- Administration procedures approved.
- Routing scenarios tested.

---

# 14. Definition of Done

Routing configuration can be safely administered and supported through controlled BAU processes.
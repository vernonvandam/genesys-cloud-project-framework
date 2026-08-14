# Layer 2.14.13 — Service Request Management

## Capability Definition

Service Request Management defines the process for handling standard Genesys Cloud operational requests.

---

# 1. Scope

- Access requests
- Configuration requests
- User requests
- Reporting requests
- Routing changes
- Telephony requests
- Digital requests
- Standard changes
- Request fulfilment

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify recurring service requests.
- Identify request owners.
- Identify approval requirements.
- Identify fulfilment teams.
- Identify ITSM integration.

---

# 4. Design Activities

- Define service request catalogue.
- Define approval workflows.
- Define fulfilment procedures.
- Define request SLAs.
- Define standard changes.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.13-T01 | Identify standard service requests | Phase 2 | Service Manager | 4h |
| 2.14.13-T02 | Define request catalogue | Phase 3 | Service Manager | 6h |
| 2.14.13-T03 | Define approvals and fulfilment | Phase 4 | Operations Lead | 6h |
| 2.14.13-T04 | Configure ITSM request workflows where applicable | Phase 7 | Integration Lead | 8h |
| 2.14.13-T05 | Test service requests | Phase 9 | Test Lead | 6h |
| 2.14.13-T06 | Transition request management | Phase 12 | Service Manager | 4h |

---

# 6. Dependencies

- Service Desk
- Change Management
- Service Ownership
- ITSM

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 7 — Integration & Data Migration
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Service Manager
- Operations Lead
- Service Desk
- Integration Lead
- Test Lead

---

# 9. Customer Responsibilities

- Define request catalogue.
- Define approval rules.
- Provide ITSM configuration.
- Approve fulfilment processes.

---

# 10. Testing

Test representative standard service requests from submission through fulfilment.

---

# 11. Deliverables

- Service Request Catalogue
- Request Workflows
- Approval Matrix
- Fulfilment Procedures

---

# 12. Effort Drivers

Request volume, ITSM integration and approval complexity.

---

# 13. Acceptance Criteria

- Request catalogue approved.
- Approval rules defined.
- Fulfilment tested.

---

# 14. Definition of Done

Standard Genesys Cloud requests can be consistently submitted, approved, fulfilled and closed.
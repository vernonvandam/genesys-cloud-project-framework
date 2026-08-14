# Layer 2.14.05 — Service Desk

## Capability Definition

The Service Desk capability defines how Genesys Cloud support is incorporated into the customer's enterprise service desk.

---

# 1. Scope

- Service desk integration
- Ticket categorisation
- Incident logging
- Request management
- Priority classification
- Escalation
- Knowledge articles
- Service desk workflows
- ITSM integration

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify ITSM platform.
- Identify service desk processes.
- Identify ticket categories.
- Identify priority model.
- Identify escalation rules.
- Identify service desk operating hours.

---

# 4. Design Activities

- Define Genesys Cloud service categories.
- Define incident/request classifications.
- Define ticket routing.
- Define escalation workflow.
- Define knowledge requirements.
- Define ITSM integration requirements where applicable.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.05-T01 | Review existing service desk processes | Phase 2 | Service Manager | 4h |
| 2.14.05-T02 | Define Genesys Cloud service catalogue entries | Phase 3 | Service Manager | 4h |
| 2.14.05-T03 | Define incident and request categories | Phase 3 | Service Manager | 4h |
| 2.14.05-T04 | Configure ITSM integration where required | Phase 7 | Integration Lead | 8h |
| 2.14.05-T05 | Create service desk knowledge articles | Phase 9 | Operations Lead | 6h |
| 2.14.05-T06 | Test service desk workflows | Phase 9 | Test Lead | 4h |
| 2.14.05-T07 | Transition service desk capability | Phase 12 | Service Manager | 4h |

---

# 6. Dependencies

- Support Model
- ITSM Platform
- Incident Management
- Knowledge Management
- Integration Architecture

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 7 — Integration & Data Migration
- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- Service Manager
- Integration Lead
- Operations Lead
- Service Desk Lead
- Test Lead

---

# 9. Customer Responsibilities

- Provide ITSM requirements.
- Configure customer-owned ITSM components.
- Define service desk processes.
- Approve support workflows.

---

# 10. Testing

Test incident categorisation, escalation, knowledge access and ITSM integration.

---

# 11. Deliverables

- Service Desk Design
- Service Catalogue Entries
- Ticket Categories
- Knowledge Articles
- ITSM Integration

---

# 12. Effort Drivers

ITSM platform, integration complexity, service catalogue complexity and number of support workflows.

---

# 13. Acceptance Criteria

- Service catalogue defined.
- Categories configured.
- Escalations tested.
- ITSM integration validated where applicable.

---

# 14. Definition of Done

The service desk is prepared to receive, classify and manage Genesys Cloud support requests.
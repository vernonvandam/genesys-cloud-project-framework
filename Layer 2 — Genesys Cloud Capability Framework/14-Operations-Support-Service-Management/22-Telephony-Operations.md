# Layer 2.14.22 — Telephony Operations

## Capability Definition

Telephony Operations provides the BAU processes required to operate, administer and troubleshoot Genesys Cloud voice services.

---

# 1. Scope

- Phone numbers
- DID management
- SIP
- BYOC
- WebRTC
- Phones
- Edge devices where applicable
- Call quality
- Carrier dependencies
- Telephony troubleshooting

---

# 2. Classification

**Required where voice is deployed**

---

# 3. Discovery Activities

- Identify telephony architecture.
- Identify carriers.
- Identify numbers.
- Identify devices.
- Identify operational owners.
- Identify common faults.

---

# 4. Design Activities

- Define telephony operational procedures.
- Define number management.
- Define carrier escalation.
- Define device support.
- Define voice troubleshooting.
- Define call-quality processes.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.22-T01 | Inventory telephony operational scope | Phase 2 | Telephony Lead | 4h |
| 2.14.22-T02 | Define telephony operating procedures | Phase 3 | Telephony Lead | 6h |
| 2.14.22-T03 | Define carrier escalation | Phase 4 | Telephony Architect | 4h |
| 2.14.22-T04 | Create telephony runbooks | Phase 9 | Telephony Lead | 8h |
| 2.14.22-T05 | Test telephony operational scenarios | Phase 8 | Test Lead | 6h |
| 2.14.22-T06 | Transition telephony operations | Phase 12 | Operations Lead | 4h |

---

# 6. Dependencies

- Voice & Telephony
- Monitoring
- Incident Management
- Asset Management

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

- Telephony Architect
- Telephony Lead
- Operations Lead
- Test Lead

---

# 9. Customer Responsibilities

- Manage carrier relationships.
- Provide telephony owners.
- Provide device inventory.
- Participate in validation.

---

# 10. Testing

Test number management, inbound/outbound calling, device faults and carrier escalation.

---

# 11. Deliverables

- Telephony Operations Guide
- Telephony Runbooks
- Carrier Escalation Procedure
- Number Management Procedure

---

# 12. Effort Drivers

Carrier architecture, BYOC complexity, device count and number volume.

---

# 13. Acceptance Criteria

- Procedures documented.
- Runbooks completed.
- Carrier escalation tested.
- Operational ownership assigned.

---

# 14. Definition of Done

BAU teams can operate and troubleshoot the Genesys Cloud voice environment.
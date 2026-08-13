# Layer 2.13.28 — Integration Migration

## Capability Definition

Integration Migration transitions integrations from the source contact centre environment to Genesys Cloud-compatible interfaces and patterns.

---

# 1. Scope

- CRM
- ERP
- ITSM
- WFM
- Data platforms
- Middleware
- External APIs
- Data Actions
- Notifications
- Event streams

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Inventory all source integrations, endpoints, credentials, data flows and dependencies.

---

# 4. Design Activities

Define target integration patterns, mappings, security, error handling and sequencing.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.28-T01 | Inventory integrations | Phase 2 | 6h |
| 2.13.28-T02 | Map integration dependencies | Phase 3 | 5h |
| 2.13.28-T03 | Define target integration architecture | Phase 4 | 6h |
| 2.13.28-T04 | Build / migrate integrations | Phase 6 | 10h |
| 2.13.28-T05 | Execute integration migration | Phase 7 | 8h |
| 2.13.28-T06 | Execute integration testing | Phase 8 | 8h |
| 2.13.28-T07 | Validate production integration | Phase 10 | 4h |

---

# 6. Dependencies

- Integration Architecture
- API Migration
- Security
- CRM
- Data

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 4 — Design
- Phase 6 — Build
- Phase 7 — Migration
- Phase 8 — Testing
- Phase 10 — Go-Live

---

# 8. Roles

- Integration Architect
- Integration Engineer
- Genesys Cloud Architect
- Security Specialist

---

# 9. Customer Responsibilities

Provide external-system SMEs and endpoint access.

---

# 10. Testing

Functional, negative, resilience and security integration testing.

---

# 11. Deliverables

- Integration Migration Plan
- Integration Configuration
- Integration Test Results

---

# 12. Effort Drivers

Integration count, complexity and external dependencies.

---

# 13. Acceptance Criteria

All required integrations function in the target environment.

---

# 14. Definition of Done

Integration migration is operational and accepted.


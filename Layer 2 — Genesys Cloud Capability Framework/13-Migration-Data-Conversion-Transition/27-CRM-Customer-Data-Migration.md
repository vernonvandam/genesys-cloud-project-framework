# Layer 2.13.27 — CRM / Customer Data Migration

## Capability Definition

CRM / Customer Data Migration addresses migration or synchronisation of customer context required by Genesys Cloud and integrated customer-service processes.

---

# 1. Scope

- Customer records
- Contacts
- Accounts
- Customer identifiers
- Interaction context
- Screen-pop data
- Customer history
- CRM references

---

# 2. Classification

**Conditional**

---

# 3. Discovery Activities

Identify customer datasets, ownership, identifiers, source systems and target usage.

---

# 4. Design Activities

Define migration versus synchronisation, matching keys and customer context requirements.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.27-T01 | Inventory customer datasets | Phase 2 | 4h |
| 2.13.27-T02 | Define customer identity mapping | Phase 3 | 4h |
| 2.13.27-T03 | Define target customer context | Phase 4 | 4h |
| 2.13.27-T04 | Execute required migration | Phase 7 | 6h |
| 2.13.27-T05 | Validate customer lookup | Phase 8 | 5h |

---

# 6. Dependencies

- CRM Integration
- Customer Data Integration
- Identity
- Data Classification

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 4 — Design
- Phase 7 — Migration
- Phase 8 — Testing

---

# 8. Roles

- CRM Architect
- Data Architect
- Integration Engineer
- Migration Lead

---

# 9. Customer Responsibilities

Provide customer data ownership and CRM SMEs.

---

# 10. Testing

Validate identity matching, customer lookup and screen-pop behaviour.

---

# 11. Deliverables

- Customer Data Mapping
- Customer Migration Dataset
- Validation Results

---

# 12. Effort Drivers

Customer data volume and CRM complexity.

---

# 13. Acceptance Criteria

Customer context is correctly available to required processes.

---

# 14. Definition of Done

Customer data migration is validated.


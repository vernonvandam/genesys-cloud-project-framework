# Layer 2.13.05 — Data Discovery

## Capability Definition

Data Discovery identifies the datasets, objects, fields, relationships and volumes that must be assessed for migration.

---

# 1. Scope

- Configuration data
- User data
- Customer data
- Interaction data
- Routing data
- Telephony data
- Digital data
- Recording metadata
- Quality data
- WFM data
- Reporting data

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify datasets.
- Identify entities.
- Identify fields.
- Identify relationships.
- Identify source formats.
- Identify volumes.
- Identify update frequency.
- Identify sensitive data.
- Identify data dependencies.

---

# 4. Design Activities

- Define migration data domains.
- Define target data requirements.
- Identify mandatory and optional fields.
- Define source-to-target relationships.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.05-T01 | Inventory migration datasets | Phase 2 | 6h |
| 2.13.05-T02 | Identify entities and attributes | Phase 2 | 6h |
| 2.13.05-T03 | Identify relationships | Phase 2 | 4h |
| 2.13.05-T04 | Record data volumes | Phase 2 | 4h |
| 2.13.05-T05 | Identify sensitive data | Phase 3 | 4h |
| 2.13.05-T06 | Baseline data inventory | Phase 3 | 3h |

---

# 6. Dependencies

- Source System Inventory
- Data Ownership
- Data Classification

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 7 — Integration & Data Migration

---

# 8. Roles

- Data Architect
- Data Engineer
- Migration Lead
- Security Specialist

---

# 9. Customer Responsibilities

Provide source data access, data SMEs and data definitions.

---

# 10. Testing

Validate that all migration datasets have been identified.

---

# 11. Deliverables

- Data Inventory
- Data Domain Catalogue
- Data Dependency Matrix

---

# 12. Effort Drivers

Data volume, number of datasets, source formats and complexity.

---

# 13. Acceptance Criteria

All relevant migration datasets and their owners are identified.

---

# 14. Definition of Done

Data discovery is complete and baselined.

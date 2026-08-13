# Layer 2.13.07 — Data Classification

## Capability Definition

Data Classification identifies the sensitivity, privacy, security and regulatory classification of migration data.

---

# 1. Scope

- Public data
- Internal data
- Confidential data
- Personal information
- Sensitive information
- Payment information
- Regulatory data
- Restricted data

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify sensitive datasets.
- Identify PII.
- Identify payment information.
- Identify regulatory obligations.
- Identify retention requirements.

---

# 4. Design Activities

- Define classification rules.
- Map source classifications to target controls.
- Define masking and handling requirements.
- Define access restrictions.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.07-T01 | Identify sensitive datasets | Phase 2 | 4h |
| 2.13.07-T02 | Classify migration data | Phase 3 | 6h |
| 2.13.07-T03 | Identify privacy controls | Phase 3 | 4h |
| 2.13.07-T04 | Define migration handling rules | Phase 4 | 4h |
| 2.13.07-T05 | Validate controls | Phase 8 | 4h |

---

# 6. Dependencies

- Data Discovery
- Security requirements
- Privacy requirements

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 4 — Architecture & Design
- Phase 8 — Testing & Validation

---

# 8. Roles

- Data Architect
- Security Specialist
- Compliance Specialist
- Data Owner

---

# 9. Customer Responsibilities

Approve classifications and regulatory interpretations.

---

# 10. Testing

Validate migration handling against approved classification rules.

---

# 11. Deliverables

- Data Classification Matrix
- Sensitive Data Register
- Data Handling Rules

---

# 12. Effort Drivers

Number of data domains and regulatory requirements.

---

# 13. Acceptance Criteria

All material migration datasets have an approved classification.

---

# 14. Definition of Done

Classification is approved and incorporated into migration controls.

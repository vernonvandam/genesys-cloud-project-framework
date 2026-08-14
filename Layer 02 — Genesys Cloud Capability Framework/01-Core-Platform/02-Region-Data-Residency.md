# Layer 2.01.02 — Region & Data Residency

## Capability Definition

Defines the Genesys Cloud region and associated data residency requirements for the implementation.

---

# 1. Scope

- AWS region
- Genesys Cloud deployment region
- Data residency
- Regulatory requirements
- Data storage location
- Disaster recovery considerations
- Cross-region considerations
- International operation
- Data transfer considerations

---

# 2. Classification

**Required**

The actual configuration and complexity are conditional on the customer's geographic and regulatory requirements.

---

# 3. Discovery Activities

Determine:

- Customer operating countries.
- Customer legal entities.
- Data residency requirements.
- Privacy requirements.
- Regulatory requirements.
- Recording residency requirements.
- Analytics/data residency requirements.
- Integration data flows.
- Cross-border data transfers.
- Disaster recovery requirements.
- Existing organisation region.

---

# 4. Design Activities

- Confirm supported Genesys Cloud region.
- Confirm data residency requirements.
- Identify data types subject to residency restrictions.
- Identify external systems receiving customer data.
- Identify cross-border data flows.
- Document architectural constraints.
- Obtain customer security/legal approval where required.

---

# 5. Implementation Activities

```text
Confirm customer countries
Confirm legal requirements
Confirm supported Genesys Cloud region
Confirm organisation region
Document data residency
Document data flows
Validate external integrations
Validate recording/data requirements
Obtain approval
```

---

# 6. Dependencies

- Customer legal requirements
- Security architecture
- Privacy requirements
- Integration architecture
- Recording architecture
- Data architecture

---

# 7. Layer 1 Mapping

Primary:

- Phase 2 — Discovery
- Phase 4 — Architecture
- Phase 5 — Platform Foundation

Supporting:

- Phase 7 — Integration & Migration
- Phase 9 — Operational Readiness

---

# 8. Roles

- Solution Architect
- Security Architect
- Genesys Cloud Architect
- Privacy / Compliance Specialist
- Customer Security
- Customer Legal / Privacy

---

# 9. Testing

Validate:

- Organisation region.
- Required data location.
- Integration data flows.
- Recording requirements.
- Analytics requirements.
- Compliance requirements.

---

# 10. Deliverables

- Region decision
- Data residency assessment
- Data-flow assessment
- Compliance approval
- Architecture decision

---

# 11. Risks

- Incorrect region selected.
- Data residency requirements discovered late.
- External integration transfers data to prohibited locations.
- Regulatory requirements overlooked.

---

# 12. Acceptance Criteria

- Region is approved.
- Data residency requirements are documented.
- Security/privacy stakeholders have approved the design.
- External data flows have been assessed.

---

# 13. Definition of Done

The Genesys Cloud region and associated data residency model are documented, approved and reflected in the implementation architecture.

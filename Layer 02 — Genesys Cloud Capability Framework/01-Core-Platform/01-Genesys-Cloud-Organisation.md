# Layer 2.01.01 — Genesys Cloud Organisation

## Capability Definition

The Genesys Cloud organisation is the top-level logical container for the customer environment.

It must be established and governed before downstream configuration is performed.

---

# 1. Scope

Activities include:

- Organisation identification
- Organisation ownership
- Organisation naming
- Region association
- Organisation administrator model
- Licensing relationship
- Platform ownership
- Administrative ownership
- Environment relationship
- Organisation-level governance

---

# 2. Classification

**Required**

Every Genesys Cloud implementation requires an organisation.

---

# 3. Discovery Activities

Determine:

- Is this a new organisation?
- Is an existing organisation being reused?
- Is this a migration from another Genesys Cloud organisation?
- Who owns the organisation?
- Which region is being used?
- What are the organisation's regulatory requirements?
- Who will administer the organisation?
- Is the customer or service provider responsible for administration?
- Are multiple business entities sharing the organisation?
- Are divisions required?
- Is the organisation being created manually or through an established provisioning process?

---

# 4. Design Activities

- Define organisation ownership.
- Define organisation naming.
- Confirm region.
- Confirm licensing.
- Define administrative model.
- Define support model.
- Define environment strategy.
- Define organisational hierarchy.
- Define governance model.
- Document the organisation architecture.

---

# 5. Implementation Activities

```text
Confirm organisation requirement
Confirm organisation ownership
Confirm region
Confirm licensing
Confirm organisation naming
Confirm administrator model
Confirm support model
Establish organisation
Validate organisation configuration
Record organisation details
```

---

# 6. Dependencies

Prerequisites:

- Project initiation
- Discovery
- Region decision
- Licensing
- Security architecture

Downstream dependencies:

- Divisions
- Users
- Roles
- Telephony
- Routing
- Architect
- WEM
- Integrations

---

# 7. Layer 1 Mapping

Primary phase:

**Phase 5 — Platform Foundation & Environment Build**

Supporting phases:

- Phase 1 — Initiation
- Phase 2 — Discovery
- Phase 4 — Architecture
- Phase 12 — BAU Handover

---

# 8. Roles

Primary:

- Genesys Cloud Architect
- Genesys Cloud Engineer

Supporting:

- Project Manager
- Solution Architect
- Security Architect
- Customer Platform Owner

---

# 9. Customer Responsibilities

- Confirm organisation ownership.
- Approve organisational structure.
- Confirm regulatory requirements.
- Approve administrator model.
- Confirm licensing.
- Approve region.
- Provide required organisational information.

---

# 10. Testing

Validate:

- Organisation exists.
- Correct region is associated.
- Administrative access works.
- Expected licensing is available.
- Organisation settings are accessible.
- Required governance controls are established.

---

# 11. Deliverables

- Organisation design
- Organisation configuration
- Organisation ownership record
- Organisation administration model
- Validation evidence

---

# 12. Effort Drivers

- New vs existing organisation
- Complexity of ownership
- Customer governance
- Multi-entity requirements
- Regulatory requirements
- Automation
- Existing platform configuration

---

# 13. Acceptance Criteria

- Organisation is available.
- Region is correct.
- Ownership is documented.
- Required administrators are established.
- Licensing is confirmed.
- Customer approves the organisation foundation.

---

# 14. Definition of Done

The organisation exists, is correctly configured, has documented ownership and has passed customer acceptance.

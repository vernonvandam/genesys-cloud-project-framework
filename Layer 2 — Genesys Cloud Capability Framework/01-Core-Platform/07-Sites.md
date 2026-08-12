# Layer 2.01.07 — Sites

## Capability Definition

Defines Genesys Cloud site configuration used where required for telephony, network and operational architecture.

---

# 1. Scope

- Sites
- Site naming
- Location association
- Telephony configuration
- Media configuration
- Network configuration
- Site-level operational requirements

---

# 2. Classification

**Conditional**

Site configuration depends on the selected Genesys Cloud telephony architecture and requirements.

---

# 3. Discovery

Determine:

- Physical sites.
- Telephony architecture.
- BYOC requirements.
- Network topology.
- Media regions.
- QoS.
- Local survivability requirements where applicable.
- Phone deployment.
- Emergency calling requirements.

---

# 4. Design

- Define site architecture.
- Map locations.
- Define telephony requirements.
- Define network requirements.
- Define media requirements.
- Define naming standards.

---

# 5. Implementation

```text
Define site
Create site
Associate location
Configure applicable telephony settings
Configure network-related settings
Validate media behaviour
Validate phones
Document site configuration
```

---

# 6. Layer 1 Mapping

Primary:

- Phase 4 — Architecture
- Phase 5 — Platform Foundation

Supporting:

- Phase 6 — Solution Build
- Phase 8 — Testing

---

# 7. Roles

- Telephony Engineer
- Network Engineer
- Genesys Cloud Architect
- Genesys Cloud Engineer

---

# 8. Acceptance Criteria

Site configuration matches the approved telephony and network architecture and passes validation.

---

# 9. Definition of Done

All required sites are configured and validated.

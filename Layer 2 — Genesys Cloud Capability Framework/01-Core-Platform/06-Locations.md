# Layer 2.01.06 — Locations

## Capability Definition

Defines physical or logical customer locations used by Genesys Cloud capabilities.

---

# 1. Scope

- Locations
- Geographic mapping
- Operational location
- Address information
- Time zone association
- Telephony implications
- Reporting implications

---

# 2. Classification

**Conditional**

Depends on deployment architecture and customer requirements.

---

# 3. Discovery

Determine:

- Number of locations.
- Country.
- State/province.
- Address.
- Time zone.
- Operational ownership.
- Telephony requirements.
- Emergency services requirements.
- Reporting requirements.

---

# 4. Implementation

```text
Collect location data
Validate addresses
Confirm time zones
Define naming
Create locations
Associate applicable resources
Validate configuration
```

---

# 5. Layer 1 Mapping

Primary:

- Phase 2 — Discovery
- Phase 4 — Architecture
- Phase 5 — Platform Foundation

Supporting:

- Phase 6 — Solution Build

---

# 6. Roles

- Genesys Cloud Architect
- Telephony Engineer
- Genesys Cloud Engineer

---

# 7. Risks

- Incorrect location data.
- Incorrect time zone.
- Telephony implications overlooked.
- Emergency services requirements missed.

---

# 8. Acceptance Criteria

All required locations exist and contain approved information.

---

# 9. Definition of Done

Required locations are configured, validated and documented.

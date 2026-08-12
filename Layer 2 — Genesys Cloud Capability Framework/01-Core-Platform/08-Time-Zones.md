# Layer 2.01.08 — Time Zones

## Capability Definition

Defines the time-zone model used by Genesys Cloud configuration and customer operations.

---

# 1. Scope

- Organisation time zone
- User time zones
- Site time zones
- Queue/business-hour time zones
- Scheduling
- WFM implications
- Reporting implications

---

# 2. Classification

**Required**

Specific complexity is conditional on geographic distribution.

---

# 3. Discovery

Determine:

- Operating countries.
- Operating regions.
- User time zones.
- Queue time zones.
- Site time zones.
- WFM requirements.
- Reporting requirements.
- Daylight-saving requirements.

---

# 4. Implementation

```text
Identify time zones
Define standard naming
Map locations
Map sites
Map business hours
Map schedules
Validate daylight-saving behaviour
Test scheduling
```

---

# 5. Layer 1 Mapping

Primary:

- Phase 2 — Discovery
- Phase 4 — Architecture
- Phase 5 — Foundation

Supporting:

- Phase 6 — Build
- Phase 8 — Testing

---

# 6. Acceptance Criteria

Time-zone configuration correctly represents the customer's operating model and scheduling requirements.

---

# 7. Definition of Done

Time-zone requirements are documented, configured and validated.

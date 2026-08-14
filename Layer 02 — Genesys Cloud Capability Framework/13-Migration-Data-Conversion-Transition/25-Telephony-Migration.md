# Layer 2.13.25 — Telephony Migration

## Capability Definition

Telephony Migration moves telephone numbers, carrier connectivity, routing, sites, endpoints and associated voice services into Genesys Cloud.

---

# 1. Scope

- Carrier
- SIP
- BYOC
- Genesys Cloud Voice
- DIDs
- Number porting
- Dial plans
- Sites
- Endpoints
- Caller ID
- Emergency services
- Failover

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Inventory all numbers, carriers, trunks, sites, devices and routing dependencies.

---

# 4. Design Activities

Define target telephony architecture, porting approach, routing, failover and cutover.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.25-T01 | Inventory telephone numbers | Phase 2 | 4h |
| 2.13.25-T02 | Validate carrier and SIP dependencies | Phase 2 | 4h |
| 2.13.25-T03 | Define telephony migration plan | Phase 4 | 6h |
| 2.13.25-T04 | Configure target telephony | Phase 6 | 8h |
| 2.13.25-T05 | Execute porting / migration | Phase 7 | 6h |
| 2.13.25-T06 | Validate inbound and outbound calling | Phase 8 | 6h |
| 2.13.25-T07 | Execute telephony cutover | Phase 10 | 6h |

---

# 6. Dependencies

- Voice & Telephony
- Architect
- Routing
- Carrier
- Network

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 4 — Design
- Phase 5 — Foundation
- Phase 6 — Build
- Phase 7 — Migration
- Phase 8 — Testing
- Phase 9 — Cutover Preparation
- Phase 10 — Go-Live

---

# 8. Roles

- Voice Architect
- Telephony Engineer
- Genesys Cloud Architect
- Carrier Engineer

---

# 9. Customer Responsibilities

Coordinate carrier, number porting and network activities.

---

# 10. Testing

Validate inbound, outbound, emergency, caller ID, transfers and failover.

---

# 11. Deliverables

- Telephony Migration Plan
- Number Porting Plan
- Cutover Runbook
- Telephony Validation

---

# 12. Effort Drivers

Number count, carrier complexity, sites and porting.

---

# 13. Acceptance Criteria

All required voice services operate correctly.

---

# 14. Definition of Done

Telephony is migrated, tested and accepted.

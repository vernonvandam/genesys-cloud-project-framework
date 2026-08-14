# Layer 2.04.31 — Routing Migration & Cutover

## 1. Purpose

Migrate existing routing logic into Genesys Cloud with controlled business impact.

## 2. Classification

**Conditional**

## 3. Discovery

Determine:

- Existing routing platform
- Existing queues
- Existing skills
- Existing routing rules
- Existing schedules
- Existing overflow
- Migration waves
- Cutover timing
- Rollback

## 4. Activities

### Discovery

- Inventory existing routing.
- Capture routing rules.
- Identify obsolete rules.
- Identify target-state changes.

### Design

- Map legacy queues.
- Map legacy skills.
- Map legacy routing rules.
- Define target routing.

### Build

- Configure target routing.
- Execute comparison testing.
- Conduct dress rehearsal.

### Cutover

- Activate target routing.
- Validate interactions.
- Monitor queues.
- Validate agent delivery.

### Rollback

- Define rollback triggers.
- Define rollback process.
- Validate rollback readiness.

## 5. Acceptance Criteria

Target routing successfully handles production traffic.

## 6. Definition of Done

Routing migration is complete and accepted.

---

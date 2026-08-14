# Layer 2.05.34 — Flow Migration & Cutover

## Purpose

Migrate existing IVR and Architect logic to Genesys Cloud while controlling customer impact.

## Classification

**Conditional**

## Discovery

Capture:

- Existing IVR
- Existing menus
- Prompts
- Routing
- Data integrations
- Authentication
- Schedules
- Holidays
- Self-service
- Failure paths

## Activities

### Discovery

- Inventory legacy flows.
- Capture current-state behaviour.
- Identify undocumented logic.
- Identify obsolete logic.

### Design

- Map legacy flow to target flow.
- Identify redesign requirements.
- Define migration waves.

### Build

- Build target flows.
- Build integrations.
- Build prompts.
- Test.

### Cutover

- Freeze legacy changes.
- Validate production configuration.
- Activate new entry points.
- Execute smoke testing.
- Monitor customer journeys.

### Rollback

- Define rollback triggers.
- Define rollback mechanism.
- Validate legacy readiness.

## Acceptance Criteria

Customer journeys operate correctly following migration.

## Definition of Done

Flow migration is complete and accepted.

---

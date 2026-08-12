# Layer 2.07.42 — WFM Migration & Cutover

## Purpose

Migrate workforce operations from an existing WFM platform or process to Genesys Cloud.

## Classification

**Conditional**

## Activities

### Discovery

- Inventory existing WFM configuration.
- Export current schedules.
- Export workforce data.
- Document forecast configuration.
- Document activity codes.
- Document time-off.
- Document user structure.
- Document reporting.

### Mapping

- Map business units.
- Map management units.
- Map planning groups.
- Map queues.
- Map skills.
- Map activities.
- Map users.
- Map time-off.

### Build

- Configure target WFM.
- Load required data.
- Generate forecast.
- Generate schedules.
- Validate.

### Cutover

- Freeze legacy changes.
- Validate final data.
- Activate target.
- Publish schedules.
- Execute smoke testing.
- Monitor.

### Rollback

- Define rollback conditions.
- Preserve legacy capability where required.
- Define schedule recovery.
- Define operational fallback.

## Acceptance Criteria

Workforce operations continue without unacceptable disruption.

## Definition of Done

WFM migration is complete and accepted.

---
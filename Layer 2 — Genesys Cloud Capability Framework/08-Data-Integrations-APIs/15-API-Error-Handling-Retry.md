# Layer 2.08.15 — API Error Handling & Retry

## Purpose

Provide consistent behaviour when API calls fail.

## Classification

**Required**

## Activities

- Define error categories.
- Define retryable errors.
- Define non-retryable errors.
- Define retry count.
- Define exponential backoff.
- Define timeout.
- Define dead-letter handling where applicable.
- Define alerting.
- Test failures.

## Acceptance Criteria

Integration failures are handled predictably without uncontrolled retry loops.

## Definition of Done

Error and retry handling is tested.

---

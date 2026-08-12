# Layer 2.02.02 — User Lifecycle Management

## 1. Purpose

Define the lifecycle of Genesys Cloud users from creation through modification and termination.

## 2. Scope

```text
Joiner
  ↓
Provision
  ↓
Modify
  ↓
Transfer
  ↓
Suspend
  ↓
Terminate
  ↓
Deprovision
```

## 3. Classification

**Required**

## 4. Discovery

Determine:

- HR source.
- IAM source.
- User categories.
- Joiner process.
- Mover process.
- Leaver process.
- Contractor lifecycle.
- Administrator lifecycle.
- Licence lifecycle.
- Access review process.

## 5. Implementation Activities

- Define lifecycle states.
- Define ownership.
- Map HR attributes.
- Define provisioning.
- Define role assignment.
- Define division assignment.
- Define licence assignment.
- Define deprovisioning.
- Define audit requirements.
- Test lifecycle scenarios.

## 6. Test Scenarios

- New employee.
- Existing employee change.
- Department transfer.
- Role change.
- Division change.
- Licence change.
- Employee termination.
- Contractor termination.
- Administrator termination.

## 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 4 — Architecture
- Phase 5 — Foundation
- Phase 8 — Testing
- Phase 9 — Operational Readiness

## 8. Deliverables

- User lifecycle design
- Lifecycle process
- Test cases
- Operating procedure

## 9. Acceptance Criteria

All defined lifecycle states operate according to customer policy.

## 10. Definition of Done

Joiner, mover and leaver processes are documented, tested and operationally owned.

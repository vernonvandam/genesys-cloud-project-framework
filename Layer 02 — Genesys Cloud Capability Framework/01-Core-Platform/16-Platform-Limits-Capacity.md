# Layer 2.01.16 — Platform Limits & Capacity

## Capability Definition

Defines the capacity and platform-limit considerations that may affect solution architecture and implementation.

---

# 1. Scope

Potential areas include:

- Users
- Queues
- Skills
- Architect flows
- Data tables
- API requests
- Integrations
- Notifications
- Storage
- Recording
- Digital interactions
- WFM configuration
- QM configuration
- Reporting
- Automation

Actual limits must be verified against current Genesys Cloud documentation and the applicable organisation/licensing model before project baselining.

---

# 2. Classification

**Required**

The depth of assessment is conditional on project complexity.

---

# 3. Discovery

Determine:

- Expected scale.
- Peak volumes.
- User count.
- Interaction volume.
- API volume.
- Integration frequency.
- Architect complexity.
- Digital volume.
- Recording volume.
- WFM scale.
- Reporting scale.

---

# 4. Design

- Identify high-volume components.
- Validate expected platform capacity.
- Identify API constraints.
- Identify integration constraints.
- Identify architectural mitigations.
- Document assumptions.

---

# 5. Implementation

```text
Collect expected volumes
Map volumes to capabilities
Review current limits
Identify potential constraints
Validate architecture
Document assumptions
Monitor during testing
```

---

# 6. Testing

Capacity considerations should be validated through:

- Functional testing
- Load/performance testing where applicable
- API testing
- Integration testing
- High-volume scenarios

---

# 7. Risks

- Platform limits discovered during build.
- API throttling.
- Unexpected interaction volumes.
- Incorrect sizing.
- Performance degradation.

---

# 8. Acceptance Criteria

Known capacity and platform constraints have been identified and the architecture is confirmed to operate within supported boundaries.

---

# 9. Definition of Done

Capacity assessment is completed and any required mitigations are incorporated into the design.

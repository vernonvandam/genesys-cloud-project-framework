# Layer 2.03.26 — Call Quality Monitoring & Troubleshooting

## 1. Purpose

Establish mechanisms for measuring, diagnosing and resolving voice-quality problems.

## 2. Classification

**Required**

## 3. Scope

- MOS/quality metrics where available
- Latency
- Jitter
- Packet loss
- Network path
- Endpoint quality
- Carrier quality
- Agent workstation

## 4. Activities

- Define quality standards.
- Identify monitoring tools.
- Define escalation path.
- Test poor-quality scenarios where practical.
- Validate available quality metrics.
- Define troubleshooting process.
- Document carrier escalation.

## 5. Operational Model

```text
Agent reports issue
       ↓
Capture conversation/call information
       ↓
Review Genesys metrics
       ↓
Review network
       ↓
Review endpoint
       ↓
Review carrier
       ↓
Identify root cause
       ↓
Remediate
       ↓
Validate
```

## 6. Acceptance Criteria

Operations can identify and troubleshoot common voice-quality issues.

## 7. Definition of Done

Voice-quality monitoring and troubleshooting procedures are documented and operational.
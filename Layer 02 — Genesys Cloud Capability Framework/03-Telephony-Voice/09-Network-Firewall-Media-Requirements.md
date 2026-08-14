# Layer 2.03.09 — Network, Firewall & Media Requirements

## 1. Purpose

Ensure the network supports reliable Genesys Cloud voice signalling and media.

## 2. Classification

**Required**

## 3. Scope

- Internet connectivity
- Firewall
- NAT
- SIP
- RTP/media
- SRTP
- DNS
- TLS
- QoS
- Proxy considerations
- Bandwidth
- Latency
- Jitter
- Packet loss

## 4. Activities

1. Review network architecture.
2. Review Genesys Cloud network requirements.
3. Identify required destinations.
4. Review firewall policies.
5. Review NAT.
6. Review QoS.
7. Validate bandwidth.
8. Validate latency.
9. Validate jitter.
10. Validate packet loss.
11. Perform media testing.

## 5. Testing

Validate:

- Agent-to-customer media
- Customer-to-agent media
- Hold
- Transfer
- Conference
- Recording
- Consult
- Callback where applicable

## 6. Risks

- One-way audio.
- No audio.
- High latency.
- Packet loss.
- Firewall blocking media.
- Incorrect NAT.

## 7. Acceptance Criteria

Voice media operates within approved quality thresholds.

## 8. Definition of Done

Network and media requirements are implemented and voice-quality validation passes.
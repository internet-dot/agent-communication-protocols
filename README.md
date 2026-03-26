# Agent Communication Protocols

Reference for agent-to-agent communication protocols and standards.

## Protocols

### HCS-10 (HOL)
Trustless P2P agent communication via Hashgraph Consensus Service.

- **Website:** https://hol.org
- **Features:** Encrypted messaging, server-blind comms, verifiable identity

### A2A (Google)
Agent-to-agent communication protocol.

- **Focus:** Interoperability between agent frameworks
- **Status:** In development

### ANP (Agent Network Protocol)
Three-layer protocol: identity, negotiation, application.

## Comparison

| Protocol | Identity | Encryption | Decentralized |
|----------|----------|------------|---------------|
| HCS-10 | UAID | ECDH+AES | Yes |
| A2A | AgentCard | TLS | No |
| ANP | DID | Optional | Partial |

## HOL Integration

HOL provides the most comprehensive agent communication via HCS-10:

```bash
npm install @hashgraph-online/standards-sdk
```

## Learn More

- [HOL Registry](https://hol.org/registry)
- [HCS-10 Spec](https://hol.org/specs/hcs-10)
- [GitHub](https://github.com/hashgraph-online)

# Threat Model

This document outlines the primary threat categories considered in Zoryu’s design.

## Mitigated Threats

- custodial compromise → eliminated by design
- unauthorized execution → prevented by wallet signing
- state inconsistency → mitigated via backend authority
- signal spoofing → mitigated via schema validation

## Out-of-Scope Threats

- wallet security and key management
- blockchain-level failures
- user device compromise

These risks are inherent to self-custody and remain the responsibility of the user and underlying network.

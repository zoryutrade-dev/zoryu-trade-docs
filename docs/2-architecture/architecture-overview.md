# Architecture Overview

Zoryu Trade is built as a modular, execution-aware system where each layer has a clearly defined responsibility. The architecture separates interaction, state management, intelligence, and execution to ensure consistency, scalability, and auditability.

Rather than embedding logic across multiple layers, Zoryu centralizes trading state and lifecycle management at the backend, while keeping execution non-custodial and on-chain.

At a high level, the system operates as follows:

- The frontend provides interaction and visualization
- The backend maintains authoritative trading state
- The AI engine generates structured trade intelligence
- The blockchain acts as the final settlement layer

This separation ensures that no single layer becomes a hidden source of truth.

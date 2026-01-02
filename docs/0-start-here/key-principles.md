# Key Principles

Zoryu Trade is built around three principles that define its architecture and constraints.

## 1) Non-Custodial by Design

Zoryu never takes custody of assets.

- No private keys stored or transmitted
- No server-side signing
- No internal balances or off-chain settlement

Zoryu functions as an orchestration and intelligence layer while control remains with the user’s wallet.

## 2) State-Aware Trading

Signals are not treated as content. They are treated as **system state**.

Each signal is a structured object containing:
- direction (long/short)
- entry price
- TP targets (TP1–TP3)
- stop loss
- confidence score
- risk-to-reward ratio
- reasoning context

Signals become tracked positions and move through deterministic lifecycle states (open → monitor → close).

## 3) Measurable Outcomes

Zoryu avoids theoretical claims. Performance is derived from tracked state:

- position status transitions (TP/SL hit)
- PnL calculation based on entry vs current price
- aggregate metrics (win rate, total PnL, history)

The system is designed so outcomes are verifiable and comparable over time.

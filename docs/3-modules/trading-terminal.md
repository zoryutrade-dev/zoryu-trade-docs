# Trading Terminal

The Trading Terminal is the primary interface where market observation and trade execution converge. It is designed to minimize friction between analysis and action while preserving non-custodial control.

## Responsibilities

- display real-time market prices and volume
- provide charting for technical context
- accept user-defined trade parameters
- initiate execution requests
- reflect wallet balances and transaction status

## Execution Model

Trades initiated from the terminal are executed non-custodially:
- parameters are defined client-side
- transactions are signed by the user wallet
- settlement occurs directly on-chain

The terminal does not store state related to trade outcomes. All authoritative state is maintained by the backend.

## Design Constraints

- no private key handling
- no server-side signing
- no internal balances
- no hidden execution logic

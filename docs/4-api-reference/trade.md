# Trade API

Handles non-custodial trade execution coordination.

## POST /api/trade/swap

Initiates a token swap through on-chain liquidity routing.

### Request Parameters

- input token mint
- output token mint
- trade amount
- slippage tolerance
- wallet address

### Execution Model

- transaction is constructed server-side
- transaction is signed client-side by the user wallet
- settlement occurs on-chain

### Response

- transaction signature
- input amount
- output amount

Zoryu does not custody funds or sign transactions.

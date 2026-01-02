# Wallet API

Provides read-only wallet-related data.

## GET /api/wallet/balance/:walletAddress

Returns current on-chain balances for supported assets.

### Response Fields

- `sol` — SOL balance
- `usdc` — USDC balance

### Notes

- Data is derived from on-chain sources
- No internal balances are maintained

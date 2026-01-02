# Execution Flow

Execution in Zoryu is non-custodial and transparent.

## Quote → Transaction → Sign → Settle

1. The backend retrieves liquidity quotes based on user parameters
2. A swap transaction is constructed with explicit slippage settings
3. The transaction is sent to the frontend for wallet signing
4. The signed transaction is submitted to the Solana network
5. Settlement is verified on-chain using transaction signatures

This flow ensures that execution remains user-controlled and verifiable.

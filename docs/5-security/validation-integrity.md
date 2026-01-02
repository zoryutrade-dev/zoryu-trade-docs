# Validation & Data Integrity

Zoryu enforces strict validation across system boundaries to maintain consistent state and prevent malformed data.

## Input Validation

- API inputs are validated against explicit schemas
- trade parameters are bounded and sanitized
- signal outputs are validated before persistence

## State Integrity

- position lifecycle transitions follow deterministic rules
- backend acts as the authoritative source of truth
- frontend consumes state but does not define it

## Execution Safety

- slippage tolerance is user-defined
- execution requires explicit wallet confirmation
- transaction results are verified on-chain

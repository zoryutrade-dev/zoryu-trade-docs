# Markets API

Provides normalized market data used across the system for display, signal generation, and evaluation.

## GET /api/markets

Returns a list of supported markets with current pricing data.

### Response

- `symbol` — market symbol
- `price` — current price
- `change24h` — 24-hour percentage change
- `volume` — 24-hour trading volume

### Notes

- Data is refreshed periodically by the backend
- Used by both Trading Terminal and AI Signal Engine
- Serves as authoritative price input for signals

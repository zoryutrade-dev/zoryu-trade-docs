# Signals API

Exposes AI-generated signals and tracked position data.

## GET /api/signals

Returns the latest AI-generated trading signals.

### Signal Fields

- symbol and direction
- entry price
- TP1–TP3 levels
- stop loss
- confidence score
- risk-to-reward ratio

## GET /api/signals/positions

Returns tracked positions and their current state.

### Position Fields

- entry and current price
- TP/SL parameters
- position status
- PnL percentage

## GET /api/signals/positions/stats

Returns aggregate performance metrics:
- total positions
- wins and losses
- pending positions
- win rate
- total PnL

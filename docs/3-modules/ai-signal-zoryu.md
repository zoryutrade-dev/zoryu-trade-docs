# AI Signal Zoryu

AI Signal Zoryu is the intelligence layer responsible for generating structured trade ideas designed for execution and tracking.

## Signal Structure

Each signal includes:
- symbol and direction (long or short)
- entry price
- multiple take-profit levels
- stop-loss threshold
- confidence score
- risk-to-reward ratio
- reasoning context

Signals are produced as deterministic data structures rather than free-form predictions.

## Lifecycle

1. Signal is generated from market context
2. Signal is validated and stored
3. Signal becomes a tracked position
4. Position is monitored against live prices
5. Position is closed based on predefined rules

## Design Philosophy

AI augments decision-making rather than replacing it. Signals are transparent, reviewable, and measurable.

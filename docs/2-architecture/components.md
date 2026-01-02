# System Components

## Web Application

The web application is responsible for user interaction and visualization.

Responsibilities:
- display real-time market data
- surface AI signals and tracked positions
- initiate execution requests
- reflect system state updates

The frontend does not define trade outcomes or manage position state.

## Backend API

The backend acts as the system authority.

Responsibilities:
- aggregate and normalize market data
- store signals and positions
- evaluate TP/SL conditions
- calculate performance metrics
- coordinate execution requests

The backend never signs transactions or holds user funds.

## AI Engine

The AI engine generates trade signals as structured data.

Responsibilities:
- analyze market inputs
- output deterministic signal parameters
- attach reasoning context

AI output is validated and tracked before becoming part of system state.

## On-Chain Execution

The blockchain is the final settlement layer.

Responsibilities:
- provide liquidity routing
- execute wallet-signed transactions
- verify execution outcomes

Zoryu does not intermediate execution or custody assets.

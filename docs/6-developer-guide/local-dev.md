# Local Development

Local development is designed to be modular.

## Recommended Workflow

- run frontend and backend as separate services
- use public contract types for integration
- rely on mock or test data where execution is not required

## Notes

- wallet interactions require user approval
- execution always occurs on-chain
- no private keys are required for development

Local development should focus on behavior verification rather than performance tuning.

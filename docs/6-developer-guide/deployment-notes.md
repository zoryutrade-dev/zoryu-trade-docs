# Deployment Notes

Deployment configuration depends on the hosting environment.

## General Guidelines

- separate environments for development and production
- isolate secrets using environment variables
- monitor system health and error rates
- ensure database migrations are applied before deployment

Execution safety and non-custodial guarantees must remain intact across all environments.

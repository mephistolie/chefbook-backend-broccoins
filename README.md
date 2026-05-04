# ChefBook Backend Broccoins Service

The Broccoins service is reserved for the Broccoins domain: currency, rewards, balance, or related business rules.

## Current State

- The submodule is present in the backend workspace.
- No runtime code, migrations, API module, or deployment chart are present in this snapshot.
- Concrete architecture should be documented here when the service receives implementation.

## Ownership Boundary

- Keep Broccoins-specific domain logic, storage, and contracts inside this service.
- Do not move currency or reward rules into `common-lib`.
- Make cross-service contracts explicit before integrating Broccoins with another service.

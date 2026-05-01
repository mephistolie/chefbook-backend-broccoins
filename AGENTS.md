# Broccoins Service Agents Guide

This service owns the Broccoins domain.

## Scope

- Broccoins-specific domain logic, storage, and transport contracts

## Working Rules

- Keep all currency or reward logic inside this service.
- Avoid leaking Broccoins-specific rules into shared libraries or unrelated services.
- If the task needs cross-service behavior, make the contract boundary explicit.

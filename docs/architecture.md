# Architecture Notes

## Principles

- keep the MVP modular
- isolate blockchain-specific logic
- support graceful degradation in low-connectivity conditions
- make education usable without trading setup

## High-Level Modules

### `frontend`

User-facing frontend for learning, simulation, dashboards, and future wallet experiences.

### `backend`

Backend for authentication, portfolio data, market data adapters, content delivery, and sync workflows.

### `smart-contract`

Soroban contract experiments and supporting integration notes.

## Suggested Service Boundaries

- auth and user profiles
- education content
- market data ingestion
- paper trading engine
- portfolio analytics
- sync queue for offline actions
- wallet and token integration layer

## Data Strategy

Suggested initial models:

- user
- lesson
- quiz
- market_snapshot
- simulated_order
- portfolio_position
- portfolio_event

## Blockchain Boundary

Keep blockchain logic behind a clean adapter interface so the core product can run in paper mode without requiring onchain setup.

## Shared Code Strategy

If shared types or validation become necessary later, they can live inside the backend initially or be extracted into a dedicated package when the repository grows enough to justify it.

## Offline Strategy

The first phase should focus on:

- local caching of educational content
- local drafting of simulated orders
- sync/reconciliation when connectivity returns

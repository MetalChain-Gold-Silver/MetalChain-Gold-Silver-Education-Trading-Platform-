# Contributing to MetalChain

Thanks for contributing to MetalChain.

We want this repository to be welcoming to first-time contributors, designers, researchers, educators, and developers.

## Ways to Contribute

- improve documentation
- propose UX ideas for low-connectivity users
- build frontend features
- build backend services
- contribute Soroban contract experiments
- improve education content and explainers
- report bugs and suggest product improvements

## Before You Start

1. Read the project overview in [README.md](README.md)
2. Review the product direction in [docs/product.md](docs/product.md)
3. Check the architecture notes in [docs/architecture.md](docs/architecture.md)
4. Search existing issues before opening a new one

## Good First Contributions

- clarify docs
- create wireframes
- improve empty states and onboarding flows
- add starter API routes
- add mock market data services
- write tests around portfolio calculations
- document Soroban integration boundaries

## Working Style

- keep pull requests focused
- prefer small, reviewable changes
- explain the user problem being solved
- include screenshots for UI changes when possible
- add or update docs when behavior changes

## Pull Request Checklist

- I read the relevant docs before starting
- My change is scoped and explained clearly
- I updated docs if needed
- I added tests or explained why tests are not included
- I verified the change locally where possible

## Branch Naming

Suggested patterns:

- `feat/...`
- `fix/...`
- `docs/...`
- `chore/...`

## Commit Style

Conventional commits are encouraged but not required.

Examples:

- `feat(web): add onboarding hero`
- `fix(api): correct portfolio pnl calculation`
- `docs: clarify mvp scope`

## Architecture Guardrails

- Do not couple MVP flows tightly to blockchain logic
- Keep paper trading usable without wallet setup
- Design for offline-friendly syncing where possible
- Treat real-asset trading as future work unless explicitly approved in the roadmap

## Need Help?

Open a discussion or issue with context, what you tried, and where you are blocked.

Clear context helps maintainers support you faster.

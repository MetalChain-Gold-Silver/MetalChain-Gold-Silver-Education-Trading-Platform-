# MetalChain

MetalChain is an open-source platform for learning, simulating, and eventually trading asset-backed gold and silver products with online and offline-friendly experiences.

The project combines:

- financial education
- portfolio tracking
- paper trading for MVP validation
- future support for tokenized precious metals on Stellar/Soroban
- mobile-first and low-connectivity design principles

## Vision

MetalChain aims to make precious metals easier to understand and safer to access for everyday users, especially beginners and communities with unreliable internet access.

## Current Status

MetalChain is in the early scaffolding and contributor-onboarding stage.

The initial open-source focus is:

- define the MVP clearly
- build the education and paper trading experience first
- prepare a modular architecture for future blockchain integration

## MVP Scope

The first milestone prioritizes simulation over real-asset custody.

- Learn the basics of gold and silver investing
- Track live or delayed market prices
- Practice paper trading
- View portfolio performance
- Prepare wallet and token modules behind clear interfaces

## Proposed Stack

- Frontend: Next.js, React, TypeScript
- Backend: Node.js, TypeScript
- Database: PostgreSQL
- Blockchain: Stellar SDK, Soroban

## Repository Layout

```text
.
├── .github/
├── backend/
├── docs/
├── frontend/
├── smart-contract/
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── LICENSE
├── SECURITY.md
└── README.md
```

## Contributor Quick Start

1. Read [CONTRIBUTING.md](CONTRIBUTING.md)
2. Read [docs/product.md](docs/product.md)
3. Read [docs/architecture.md](docs/architecture.md)
4. Read [docs/setup.md](docs/setup.md)
5. Pick an issue labeled `good first issue` or `help wanted`

## Project Principles

- education before speculation
- simulation before custody
- accessibility over complexity
- modular blockchain integration
- transparent community collaboration

## Important Note

MetalChain does not currently enable real-world gold or silver custody, brokerage, or regulated trading.
Any real-asset functionality will require legal, compliance, custody, and partner review before implementation.

## Roadmap

See [docs/roadmap.md](docs/roadmap.md).

## License

MIT, unless replaced before first public release.

## Maintainer Setup Reminder

Before publishing the repository, replace placeholder values in:

- `.github/CODEOWNERS`
- `.github/ISSUE_TEMPLATE/config.yml`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`

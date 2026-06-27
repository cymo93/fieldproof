# FieldProof

Open-source infrastructure for decentralized farmland audits.

> Status: early prototype and project incubation. This is not production software, not a finished protocol, and not yet ready for real audit decisions.

FieldProof helps communities, auditors, landowners, brands, and consumers create public, verifiable environmental evidence about farmland. The goal is to make trustworthy audit data cheap to collect, hard to tamper with, fair to dispute, and easy for anyone to inspect or self-host.

The first prototype focuses on coffee farms in Chiapas, Mexico and a narrow audit claim: riparian buffer health near waterways.

## Why This Exists

Environmental claims about farmland are often locked inside private audits, brand PDFs, or centralized databases. That makes the data expensive to produce, hard to verify, and easy to lose.

FieldProof is designed around a different model:

- Auditors capture evidence offline in the field.
- Evidence files are stored on decentralized storage.
- Hashes, signatures, audit status, bounties, and appeals are recorded on-chain.
- Landowners have a right to respond or appeal.
- Validators review disputed or sampled audits.
- Brands and consumers fund more public audit coverage.

This does not claim that blockchain proves physical truth by itself. The system creates tamper-resistant evidence trails, transparent dispute processes, and public confidence scores.

## Current Status

This repository currently contains a clickable prototype and project planning docs.

What exists today:

- A static clickable prototype.
- Early architecture and project planning docs.
- Contribution and governance scaffolding.

What does not exist yet:

- Production mobile app.
- Smart contracts.
- Decentralized storage integration.
- Real device attestation.
- Real audit validation process.
- Security review.

Open the prototype:

[outputs/farmland-audit-prototype.html](outputs/farmland-audit-prototype.html)

Prototype surfaces:

- Mobile auditor app
- Public farm dashboard
- Landowner appeal portal
- Validator review interface
- Brand bounty console

## Product Principles

- Offline-first fieldwork.
- Evidence-first public records.
- No raw image data on-chain.
- Open schemas and portable audit packets.
- Landowner right of response.
- Human review for disputed physical-world claims.
- Low-cost self-hosting.
- Public-good governance over platform lock-in.

## Help Wanted

The project is intentionally being opened early so people can shape it before the architecture hardens.

High-value contribution areas:

- Field audit workflow design.
- Offline-first mobile engineering.
- Solana program design.
- Evidence packet schemas.
- Decentralized storage research.
- Mapping and farm boundary data.
- Environmental science review.
- Data ethics and governance.

## Proposed Architecture

MVP stack:

- Mobile app: React Native + Expo
- Local storage: SQLite
- Maps: MapLibre with offline vector tiles
- Evidence storage: Arweave first, IPFS/Filecoin optional
- Chain: Solana
- Programs: Rust + Anchor
- Dashboard: Next.js
- Indexer/API: lightweight event indexer

See [docs/ARCHITECTURE.md](docs/ARCHITECTURE.md).

## Roadmap

See [docs/ROADMAP.md](docs/ROADMAP.md).

## Contributing

We want contributors across software, agriculture, environmental science, cryptography, mapping, field operations, design, and governance.

Start with:

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [docs/PROJECT_PLAN.md](docs/PROJECT_PLAN.md)
- [docs/GOVERNANCE.md](docs/GOVERNANCE.md)

## License

License is intentionally marked TBD until the founding contributors choose the final posture. Until a license is selected, please treat the code and docs as not yet licensed for reuse.

Recommended default:

- AGPL-3.0 for hosted platform code, so public deployments share improvements.
- Apache-2.0 or MIT for schemas, SDKs, and small interoperability libraries, so other public-interest systems can adopt the standard easily.

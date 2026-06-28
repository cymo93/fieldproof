# FieldProof

Open-source infrastructure for farm proof pages, verifier capture, and regenerative sourcing evidence.

FieldProof helps brands, producers, field verifiers, and consumers turn credible farm visits into public proof pages and reusable marketing assets. The goal is to lower the cost of trust while making beautiful, science-rooted evidence of good farming easier to capture, inspect, and share.

The first prototype focuses on specialty coffee: QR proof pages for product batches, a verifier capture studio, and standards-rooted scorecards for field evidence.

## Why This Exists

Environmental claims about farmland are often locked inside private audits, brand PDFs, certification portals, or scattered marketing folders. That makes the data expensive to produce, hard to verify, and difficult for consumers to understand.

FieldProof is designed around a different model:

- Brands create product proof pages tied to packaging QR codes.
- Verifiers capture media, observations, and measurements in the field.
- Capture flows are rooted in standards, scorecards, and evidence requirements.
- Producers retain context, consent, and response rights.
- Consumers see clear claim levels instead of vague badges.
- Evidence packets can later support certification, compliance, and decentralized registries.

This does not claim that a proof page or blockchain entry proves physical truth by itself. The system creates structured evidence trails, transparent claim levels, and a practical path from story capture to formal verification support.

## Current Status

This repository currently contains clickable prototypes and project planning docs.

Open the prototype:

[outputs/fieldproof-studio-prototype.html](outputs/fieldproof-studio-prototype.html)

Prototype surfaces:

- Consumer product proof page
- Verifier capture studio
- Standards and scorecard library
- Brand asset library
- Brand proof-page console

## Product Principles

- Science-rooted field capture.
- Beautiful media with credible evidence underneath.
- Clear claim levels: story, self-attested, field-evidenced, lab-supported, verified, disputed.
- Offline-first verifier workflows.
- Open schemas and portable audit packets.
- Producer consent and right of response.
- Human review for serious physical-world claims.
- Low-cost self-hosting.
- Public-good governance over platform lock-in.

## Help Wanted

The project is intentionally being opened early so people can shape it before the architecture hardens.

High-value contribution areas:

- Field audit workflow design.
- Regenerative agriculture standards and scorecards.
- Offline-first mobile engineering.
- Product proof pages and consumer UX.
- Evidence packet schemas.
- Decentralized storage and registry research.
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

See [docs/STRATEGY.md](docs/STRATEGY.md) for the current product wedge.

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

# FieldProof

Open-source tools for showing where food came from and how farm claims were checked.

FieldProof helps brands, producers, and field verifiers turn farm visits into product story pages, useful photos and clips, and clear review notes. The goal is simple: help customers see the people, places, and checks behind the food they buy.

The first prototype focuses on specialty coffee: QR product stories, a field visit app, and practical checklists for farm photos, notes, and samples.

## Why This Exists

Farm claims are often locked inside private audits, brand PDFs, certification portals, or scattered marketing folders. That makes them expensive to produce, hard to check, and difficult for customers to understand.

FieldProof is designed around a different model:

- Brands create product story pages tied to packaging QR codes.
- Field verifiers collect photos, clips, notes, and measurements.
- Field visits follow practical checklists based on standards and buyer needs.
- Producers retain context, consent, and response rights.
- Customers see clear labels instead of vague green badges.
- Review packets can later support certification, compliance, and open registries.

This does not claim that a web page or blockchain entry proves physical truth by itself. FieldProof helps people collect better records, show exactly what was checked, and avoid saying more than the evidence supports.

## Current Status

This repository currently contains clickable prototypes and project planning docs.

Open the prototype:

[outputs/fieldproof-studio-prototype.html](outputs/fieldproof-studio-prototype.html)

Prototype surfaces:

- Customer product story
- Field visit app
- Farm checklists
- Photos and clips library
- Brand dashboard

## Product Principles

- Plain-language product stories.
- Beautiful farm media with the field notes behind it.
- Clear status labels: story, self-reported, checked in the field, lab results attached, reviewed by a third party, disputed.
- Offline-first field visit workflows.
- Open schemas and portable audit packets.
- Producer consent and right of response.
- Human review for serious physical-world claims.
- Low-cost self-hosting.
- Public-good governance over platform lock-in.

## Help Wanted

The project is intentionally being opened early so people can shape it before the architecture hardens.

High-value contribution areas:

- Field audit workflow design.
- Farm standards and practical checklists.
- Offline-first mobile engineering.
- Product story pages and customer UX.
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

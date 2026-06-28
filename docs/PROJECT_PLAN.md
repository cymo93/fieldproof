# FieldProof Project Plan

## Phase 0: Founding Decisions

Decisions to make before production development:

- Project name and visual identity.
- License model.
- First pilot region.
- First crop.
- First environmental claim.
- Governance model for validators and disputes.
- Whether the first deployment uses stablecoin bounties only or introduces a project token later.

Recommended first wedge:

- Crop: coffee
- Region: Chiapas, Mexico
- Product: QR product story pages plus field visit app
- Claim: origin, producer story, waterway health, soil cover, and regenerative practice baseline
- Buyers: coffee brands and cooperatives

## Phase 1: Prototype Validation

Goal: validate the workflow before building production systems.

Tasks:

- Interview 5 field auditors or NGO field workers.
- Interview 3 landowners or cooperative representatives.
- Interview 3 sourcing, sustainability, or ESG buyers.
- Interview 2 environmental science reviewers.
- Test the clickable prototype with each group.
- Identify the minimum review packet needed for trust.

Exit criteria:

- Auditors understand the offline capture flow.
- Landowners understand response and appeal rights.
- Buyers understand why they would fund bounties.
- Validators understand review expectations.

## Phase 2: MVP Technical Design

Goal: produce build-ready technical specs.

Deliverables:

- Product story page lifecycle.
- Field visit workflow.
- Evidence packet JSON schema.
- Standards-based checklist schema.
- Farm registry schema.
- Bounty escrow model.
- Appeal bond model.
- Validator quorum rules.
- Threat model for spoofing, AI images, GPS tampering, and false reports.
- Self-hosting deployment plan.

## Phase 3: Mobile Field MVP

Goal: working offline audit capture.

Build:

- React Native app.
- Auditor profile.
- Bounty list.
- Farm boundary view.
- Offline map package download.
- In-app camera only.
- GPS and timestamp capture.
- Standards-based shot list.
- Checklist and sample collection workflow.
- Photo hash generation.
- Encrypted SQLite audit queue.
- Sync status and retry handling.
- Multilingual structured checklist.

Defer:

- Full video verification.
- On-device LLM translation.
- Advanced C2PA integration.

## Phase 4: Registry And Evidence Storage

Goal: durable public records.

Build:

- Evidence packet upload to Arweave.
- Solana audit registry program.
- Audit status transitions.
- Bounty escrow program.
- Appeal bond flow.
- Event indexer for dashboard queries.

Principle:

Store heavy evidence off-chain. Store compact hashes, URIs, signatures, and state transitions on-chain.

## Phase 5: Public Dashboard

Goal: make audit data useful and inspectable.

Build:

- Public map.
- Farm profile.
- Audit timeline.
- Evidence viewer.
- Integrity badges.
- Brand transparency pages.
- Customer QR story pages.
- Basic public API.

## Phase 6: Appeals And Validation

Goal: make the system fair and resilient.

Build:

- Landowner right-of-response portal.
- Formal appeal flow.
- Appeal bond handling.
- Validator review queue.
- Side-by-side evidence review.
- Quorum and decision recording.
- Reputation updates.

## Phase 7: Pilot

Goal: prove field utility and buyer demand.

Pilot size:

- 20-50 farms.
- 5-10 auditors.
- 2-4 validators.
- 1-3 brand or cooperative partners.

Success metrics:

- Cost per completed audit.
- Sync success rate.
- Evidence rejection rate.
- Appeal rate.
- Time from capture to public record.
- Brand willingness to pay.
- Auditor earnings per day.
- Consumer QR engagement.

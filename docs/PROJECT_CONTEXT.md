# FieldProof Project Context

This document captures the working context from the early FieldProof design thread so future project-scoped Codex threads can continue without losing the product direction.

## Current Direction

FieldProof is not starting as a generic blockchain audit tool.

The first wedge is:

> Tools for showing where food came from and how farm claims were checked.

The first product should help brands, producers, and field verifiers turn farm visits into:

- Product story pages for QR codes on packaging.
- Useful photos and clips.
- Clear review notes.
- Practical checklist records.
- Sample and lab-result handoff records.

## Why This Wedge

The fastest traction probably comes from brands, not a standalone consumer app.

Brands already have:

- Packaging.
- Customers.
- Origin stories.
- Marketing budgets.
- Sourcing relationships.
- Reasons to prove trust without paying for full certification every time.

Customers may not install a new app, but they may scan a QR code on a bag of coffee, chocolate bar, olive oil bottle, wine label, or honey jar if the page is clear, beautiful, and believable.

## First Market

Specialty coffee is the recommended first market.

Reasons:

- Origin already matters.
- Roasters already tell farm and cooperative stories.
- QR codes fit the packaging.
- Premium coffee can support modest verification costs.
- Coffee has certification fatigue and traceability pressure.
- Farm-level and cooperative-level provenance already matters culturally.

## Product Surfaces

Current prototype surfaces:

- Product Story.
- Field Visit App.
- Checklists.
- Photos & Clips.
- Brand Dashboard.

Current prototype file:

- `outputs/fieldproof-studio-prototype.html`

Hosted demo:

- `https://cymo93.github.io/fieldproof/`

GitHub repo:

- `https://github.com/cymo93/fieldproof`

## Language Rules

Use common, specific language.

Prefer:

- Product Story.
- Field Visit App.
- Checklists.
- Photos & Clips.
- Brand Dashboard.
- Checked in the field.
- Lab results attached.
- Reviewed by a third party.
- What was collected.
- What we checked.

Avoid:

- Science-rooted.
- Field-evidenced.
- Credibility engine.
- Proof asset.
- Generic "green" or "sustainable" claims.
- Saying more than the evidence supports.

Core copy principle:

> Say what was checked, show what was collected, avoid saying more than the evidence supports.

## User Background

The user worked at Regenified and helped design the verification standard and capture scorecard.

They know the details of verifier workflows, including:

- Capture scorecards.
- Soil samples.
- Lab tests.
- Field observations.
- Standards-based verification.
- The need for verifiers to capture beautiful, compelling media of regenerative farmland.

This experience should guide the product. FieldProof should make field verifiers feel capable and respected, not like data-entry workers.

## Strategic Framing

Do not pitch FieldProof first as:

- Cheaper certification.
- Blockchain certification.
- A standalone consumer app.
- A compliance platform.

Pitch it as:

- A way for brands to show customers where food came from.
- A way to turn field visits into product stories and review records.
- A way to lower the cost of trust.
- A lightweight layer that can later support certification, compliance, or decentralized registries.

## Next Useful Work

Strong next steps:

1. Improve the Product Story page with a more realistic customer journey.
2. Improve the Field Visit App with richer checklist, sample, and media capture flows.
3. Define the core data model:
   - Product batch.
   - Producer/farm.
   - Field visit.
   - Checklist.
   - Media item.
   - Sample.
   - Lab result.
   - Review status.
4. Create realistic sample data for a specialty coffee pilot.
5. Add a plain-language competitive landscape and positioning doc.
6. Convert the static prototype into a small app once flows stabilize.

## Current Git State At Time Of Context Capture

Last known pushed commit:

- `c57206e` - `Simplify product copy and tighten prototype spacing`

This document was added afterward to preserve project context for future project-scoped work.


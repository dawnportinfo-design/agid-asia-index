# AGID Asia Index

AGID Asia index for Caucasus, East Asia, Southeast Asia, South Asia, Central Asia, Middle East, territories, and staged country packs.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-asia-index`
- Stage: `wave-0-index`
- Index readiness: `index-ready`
- Country data readiness: `sample-ready`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, proof-secret, or private-key material.

## Scope

The Asia index coordinates East Asia, Southeast Asia, South Asia, Central Asia, the Middle East, Caucasus, territories, special regions, and staged country packs.

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and
special-region display policy for Asia address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, proof secrets, private keys, large GIS extracts,
map tiles, search indexes, routing networks, or carrier operational datasets.

## Related Repositories

- `agid-asia-caucasus-index`
- `agid-asia-east-asia-index`
- `agid-asia-southeast-asia-index`
- `agid-asia-south-asia-index`
- `agid-asia-central-asia-index`
- `agid-asia-middle-east-index`

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, postal
status, repository placement, and quality gate metadata. Large geography,
hydrographic datasets, building polygons, OSM/Overture extracts, routing
networks, map tiles, search indexes, and generated caches must stay in external
content-addressed packs.

## Country And Territory Creation Policy

Physical country repositories are created only when they have enough content to
be useful: README, manifest, postal status, source policy, quality gates,
synthetic tests, no-raw-address guardrails, and a maintainer path. Planned child
repositories stay in this index until data volume, ownership, or pull-request
pressure justifies a split.

## Postal-Weak And Multilingual Policy

Asia packs can include postal-code, postal-weak, no-postal-code, island, desert,
border, disaster, high-rise, informal-settlement, and multilingual-script modes.
Those modes must be represented as technical address infrastructure and never
as publication of personal addresses.

## Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Disputed, de
facto, overseas, island, desert, or special regions must carry explicit source,
license, canonical region, and display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.

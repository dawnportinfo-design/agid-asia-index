# AGID Asia Index

AGID Asia index for Caucasus, East Asia, Southeast Asia, South Asia, Central Asia, Middle East, territories, and staged country packs.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-asia-index`
- Stage: `wave-0-index`
- Data readiness: `index-ready`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, or private-key material.

## Scope

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and special
region display policy for Asia address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, private keys, large GIS extracts, map tiles, or
search indexes.

## Related Repositories

- `agid-asia-caucasus-index`
- `agid-asia-east-asia-index`
- `agid-asia-southeast-asia-index`
- `agid-asia-south-asia-index`
- `agid-asia-central-asia-index`
- `agid-asia-middle-east-index`

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, and
quality gate metadata. Large geography, hydrographic datasets, building
polygons, OSM/Overture extracts, and generated caches must stay in external
content-addressed packs.

## Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Disputed or special
regions must carry explicit display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.

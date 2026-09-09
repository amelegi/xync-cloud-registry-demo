# Xync Cloud Registry Demo

Private source repository for the M9/M9.1 Xync remote merchant registry and on-demand delivery proofs.

## Purpose

This repository contains **fictional demo merchant metadata only**. It must not contain production credentials, real merchant secrets, personal data, payment credentials, or private integration keys.

## Publishing model

GitHub Pages should publish from the `main` branch `/docs` folder.

The published content is intentionally public-readable for the Xync mobile demo to fetch over HTTPS without GitHub authentication.

## Initial M9 structure

- `docs/registry/v1/registry.json` — remote merchant catalogue
- `docs/manifests/*.json` — fictional merchant manifests

## M9.1 CloudCafe packages

CloudCafe uses the stable package identity `xync.demo.cloudcafe`. Its self-contained HTML releases are public proof assets:

- v1 (`1.0.0`): `docs/packages/cloudcafe/v1/index.html`
- v2 (`2.0.0`): `docs/packages/cloudcafe/v2/index.html`

The CloudCafe Manifest initially approves v1. Physical update testing changes only its version, package URL, and SHA-256 to the already-published v2 asset. These packages contain no external dependencies, credentials, APIs, or real merchant/customer data.

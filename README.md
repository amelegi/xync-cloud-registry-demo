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

M9.1 may later add governed remote Mini-App package metadata/content, integrity values, versions, and revocation state.

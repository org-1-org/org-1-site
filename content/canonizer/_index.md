---
title: "Canonizer"
---

# Canonizer

Canonizer is an open-source Python toolkit for:

- Canonical JSON schemas for real-world API payloads
- Transform libraries (e.g., JSONata) to normalize provider-specific shapes
- Drift detection and version tracking using sandbox and ingestion data
- Local `.canonizer/` cache pulling from the shared `canonizer-registry`

The goal is simple: make it safer and easier to build data pipelines on top of
APIs that change without clean versioning.

More details will live in the Canonizer repositories:

- Core library: [canonizer](https://github.com/org-1-org/canonizer)
- Registry: [canonizer-registry](https://github.com/org-1-org/canonizer-registry)

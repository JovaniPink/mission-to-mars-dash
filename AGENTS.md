# Repository guidance

## Purpose

This repository is an inventory-only placeholder for a possible Mission to
Mars dashboard. No application or data pipeline is currently implemented.

## Working rules

- Do not claim a runnable dashboard, deployment, or current Mars dataset until
  those artifacts exist and are verified.
- A reactivation PR must define the product boundary, authoritative data
  sources, source rights, runtime, dependency lock, tests, and run commands.
- Prefer official NASA sources and record retrieval time and transformation
  lineage before displaying or persisting observations.
- Keep credentials, scraped third-party media, generated builds, and large raw
  datasets out of Git unless explicitly reviewed.
- Stage explicit files and preserve unrelated work.

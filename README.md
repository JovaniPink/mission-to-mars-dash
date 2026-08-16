# Mission to Mars Dashboard

This repository reserves a name and review boundary for a possible Mars data
dashboard.

## Current status

This is an **inventory-only placeholder**. The default branch contains no
application source, dashboard, scraper, dataset, dependency manifest, tests,
build output, or deployment configuration. Nothing in this repository is
currently runnable or deployed.

The repository should not be confused with a supported Mars mission service or
represented as current NASA data coverage.

## Reactivation contract

A future implementation should begin with a focused architecture pull request
that defines:

1. the audience and decisions the dashboard supports;
2. official or otherwise authorized data sources and update cadence;
3. provenance fields for source URL, retrieval time, and transformations;
4. the runtime, supported toolchain, dependency lock, and deployment boundary;
5. deterministic tests that use fixtures rather than live network calls; and
6. accessibility, failure-state, and stale-data behavior.

Prefer official NASA APIs and media repositories. A public URL does not by
itself grant permission to scrape, persist, transform, or redistribute its
content. Keep credentials and large generated or downloaded artifacts out of
Git.

## Repository contents

- `README.md` — current scope and reactivation requirements.
- `AGENTS.md` — repository-local contributor guidance.
- `LICENSE` — license for repository-authored material.

## License

Repository-authored material is available under the [MIT License](LICENSE).
NASA, agency, and third-party data or media remain subject to their own terms.

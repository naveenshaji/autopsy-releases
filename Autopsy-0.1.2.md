# Autopsy 0.1.2

- Ships memory as a FalkorDB-only runtime.
- Uses an embedded FalkorDB Lite graph on first launch, with no Docker or external service required.
- Removes the packaged local SQLite memory fallback.
- Fixes first-run memory readiness by bootstrapping the lightweight Falkor runtime before ML models.
- Keeps a single unified memory graph across workspaces.

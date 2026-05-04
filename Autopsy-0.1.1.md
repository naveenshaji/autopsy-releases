# Autopsy 0.1.1

This update makes packaged Autopsy installs self-contained for memory.

- Bundles the Autopsy memory graph tools inside the app.
- Initializes the local memory graph database and schema on first use.
- Routes memory reads and writes into one unified memory graph across cwd changes.
- Updates the installed `autopsy memory` CLI wrapper to use the bundled tool.
- Keeps FalkorDB acceleration optional while preserving the local memory fallback.

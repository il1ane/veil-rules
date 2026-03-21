# Veil Rules Public Files

This folder contains the files to publish on GitHub Pages (`veil-rules`):
- `catalog.json`
- `manifest.json`

Expected URLs:
- `https://il1ane.github.io/veil-rules/catalog.json`
- `https://il1ane.github.io/veil-rules/manifest.json`

After each catalog change:
1. Re-sign manifest with `Starter/tools/rules_crypto.swift sign`.
2. Verify with `Starter/tools/rules_crypto.swift verify`.
3. Publish both files.

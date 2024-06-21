---
"@pnpm/exportable-manifest": break
---

Creating an exportable manifest now requires a `catalogResolver` to be passed to `createExportableManifest` in order to replace `catalog:` protocol specifiers.

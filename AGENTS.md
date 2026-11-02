# Vestigium landing

The public marketing page for Vestigium, a court-operations prototype. Static HTML in
`docs/`, published to https://jacobrakaifoundation.github.io/vestigium/ by
`.github/workflows/pages.yml` on every push to `main`.

- The product source, API, and case workspace are private and never belong here.
- The site is served under `/vestigium/`, so keep links and asset paths relative.
- Preview locally: `python3 -m http.server -d docs`, then open http://localhost:8000.
- `.github/workflows/security.yml` calls the org's shared scan
  (`jacobrakaiFoundation/.github`, see its `docs/MONITORING.md`).
- Merging to `main` publishes, so a merge needs Jacob's yes.

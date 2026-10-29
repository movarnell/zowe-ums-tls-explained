# Zowe × UMS — TLS Architecture Lab

Interactive educational briefing showing how Zowe AT-TLS and IBM Unified Management Server for z/OS native TLS coexist.

## Develop locally

No dependencies or build step are required. Edit `index.html` and `app.js`.

```sh
python3 -m http.server 8768 --bind 127.0.0.1
```

Open http://127.0.0.1:8768. Validate JavaScript with `node --check app.js`.

## Publish

GitHub Pages serves the repository root from `main`. Pushing changes to `main` updates the site. `.nojekyll` keeps this a plain static website.

## Scope

Based on IBM UMS 1.2 documentation and versioned Zowe guidance linked in the site. Architecture diagrams and the handshake explorer are explanatory models, not installation certification or universal configuration recipes. Confirm release compatibility, actual socket owners and effective AT-TLS policies before applying changes.

## Files

- `index.html`: content, diagrams, styles and references.
- `app.js`: scenario controls and handshake explorer.
- `.nojekyll`: static GitHub Pages publication.

No Sites service, external runtime, credentials, analytics or server component is required.

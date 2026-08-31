# Maturity — website

Marketing, documentation, privacy and support pages for **Maturity**, a term deposit
tracker for iPhone, iPad and Mac.

Published with GitHub Pages at **https://jack-cap.github.io/maturity/**

| Page | Purpose | Used by App Store Connect as |
| --- | --- | --- |
| [`index.html`](index.html) | Landing page | Marketing URL |
| [`docs.html`](docs.html) | Export, CLI and read-only MCP documentation | — |
| [`privacy.html`](privacy.html) | Privacy policy | **Privacy Policy URL** (required) |
| [`support.html`](support.html) | Help, FAQ and contact | **Support URL** (required) |

## About this repository

This `site` directory is its own Git repository, with the remote
`jack-cap/maturity`. It is separate from the parent `maturity-app` repository; the app and
optional source-built analysis tools are not published here. Website changes must be
committed and pushed from inside this `site` directory so they go to the website remote,
not the parent repository.

Plain HTML and CSS with no build step, no JavaScript and no third-party requests. The site
itself does not add analytics, trackers or remote assets.

## Editing and deployment

Edit the HTML from inside this repository. Deployment is likely GitHub Pages from the
`main` branch and repository root, but that source cannot be verified from the local
checkout. Before relying on it, check **GitHub Settings &rarr; Pages** for the configured
branch and folder. Commit and push website changes from inside `site` only after that
configuration is confirmed.

Shared styling lives in `styles.css`. Colours are defined once as custom properties at the
top and adapt to light and dark mode via `prefers-color-scheme`.

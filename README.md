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

This repo contains the website only. The app and optional source-built analysis tools live
separately and are not published here.

Plain HTML and CSS with no build step, no JavaScript and no third-party requests. The site
itself does not add analytics, trackers or remote assets.

## Editing

Change the HTML and push to `main`. GitHub Pages redeploys automatically, usually within a
minute.

Shared styling lives in `styles.css`. Colours are defined once as custom properties at the
top and adapt to light and dark mode via `prefers-color-scheme`.

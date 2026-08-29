# Maturity — website

Marketing, privacy and support pages for **Maturity**, a term deposit tracker for
iPhone, iPad and Mac.

Published with GitHub Pages at **https://jack-cap.github.io/maturity/**

| Page | Purpose | Used by App Store Connect as |
| --- | --- | --- |
| [`index.html`](index.html) | Landing page | Marketing URL |
| [`privacy.html`](privacy.html) | Privacy policy | **Privacy Policy URL** (required) |
| [`support.html`](support.html) | Help, FAQ and contact | **Support URL** (required) |

## About this repository

This repo contains the website only. The app source lives separately and is not
published here.

Plain HTML and CSS with no build step, no JavaScript and no third-party requests —
the privacy page claims the app makes no third-party connections, and it would be
odd for the page saying so to load a tracker.

## Editing

Change the HTML and push to `main`. GitHub Pages redeploys automatically, usually
within a minute.

Shared styling lives in `styles.css`. Colours are defined once as custom properties
at the top and adapt to light and dark mode via `prefers-color-scheme`.

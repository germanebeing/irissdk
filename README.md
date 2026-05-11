# IRIS SDK Flow Diagrams

Interactive flow diagrams for the three IRIS SDKs — POSM, OCR Stock, and IR (Image Recognition).

## What this is

A single-page interactive visualization that shows, for each SDK module:

- **SDK Flow** — the technical step sequence (function calls, callbacks, decisions, sync logic)
- **User Flow** — what the user actually sees and does, with a "behind the scenes" link back to the SDK functions
- **Host vs. SDK ownership** tags on every step so you can see who is responsible for what
- **Returns-to-host** indicators wherever the SDK delivers a result via callback

Click any step to expand its details and reveal the next step. The flow lays out as a snake (left-to-right, then right-to-left, etc.) so it fills the viewport instead of trailing off into a single horizontal line.

## Live

Deployed via GitHub Pages from the `gh-pages` branch.

## Run locally

It's a single static HTML file — no build step.

```sh
open index.html
```

Or serve it:

```sh
python3 -m http.server 8000
```

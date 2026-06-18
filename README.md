# Narrative Tracker — Demo

Build: `20260618-120037`

This folder is the deployable static demo. Open `index.html` directly in
a browser, or visit the GitHub Pages URL for this repository.

## Cache busting

Every build stamps a UTC timestamp version into the HTML. All data-file
script URLs carry `?v=20260618-120037` so browsers always fetch the
latest version after a re-deploy. A small `build 20260618-120037`
indicator at the bottom-left of the page lets you confirm which build
a tab is running.

If you ever see stale content despite the version mismatch, open in
incognito or append `?v=anything-else` to the URL — that always
forces a clean fetch.

## Updating

Re-run `python scripts/build_demo.py` from the repo root after any
change to the prototype HTML or to the corpus output files.

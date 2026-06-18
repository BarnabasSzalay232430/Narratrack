# Narrative Tracker — Demo

This folder is the deployable static demo. Open `index.html` directly in a
browser, or visit the GitHub Pages URL for this repository.

## What you can do here
- Pick a topic (Hungary 2026, Iran 2026, Netherlands 2026)
- Explore auto-discovered narratives, their constituent pieces, and detected
  framing shifts ("moments of change")
- Toggle Dev vs User view to compare diagnostic detail with the
  audience-facing prototype
- Switch the data source between the baseline pipeline output and the
  refined (closed-loop) output

## What this is NOT
- A live scraper. The corpora here were collected in April-May 2026 and
  processed offline. To run a fresh scrape + pipeline on a new corpus,
  see the Dockerfile in the repo root.

## Updating
Re-run `python scripts/build_demo.py` from the repo root after any change
to the prototype HTML or to the corpus output files.

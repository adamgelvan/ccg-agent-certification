# PY2027 Agent Certification Guide

A single-page walkthrough for Coverage Care Group agents covering the two
certifications needed to write ACA business in plan year 2027:

- **FFM registration / MLMS training** via the CMS Enterprise Portal (8 steps)
- **Georgia Access certification** via certification.georgiaaccess.gov (6 steps)

Each step has a checkbox; progress is stored in the agent's own browser
(`localStorage`), so everyone tracks themselves and nothing is shared.

## Access code

The page opens behind an access code. This is a **soft gate**, not security —
the code is in the page source and this repo is public. It keeps the page out
of search results and off the radar of people who stumble on the link. Nothing
sensitive is on the page; it's publicly available CMS instructions.

Once entered, the code is remembered on that device.

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The page served by GitHub Pages. Standalone document. |
| `img/` | Portal screenshots referenced by the steps. Required. |
| `src/artifact-source.html` | Same page as a Claude Artifact fragment (no `<html>`/`<head>` wrapper). |
| `robots.txt` | Blocks crawlers. |

## Deadline

Agents are asked to finish both tracks by **October 1, 2026**, ahead of open
enrollment. Change it in `index.html` — search for `Finish by`.

## Updating for a new plan year

Screens change most plan years. When they do, replace the screenshots in `img/`
and update the affected step copy. The step numbering and the two-track
structure should hold.

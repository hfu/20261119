# OSM Workshop, Vientiane, 19 Nov 2026

Materials and working files for the OpenStreetMap workshop held in Vientiane on 19 November 2026.

Published page: <https://hfu.github.io/20261119/>

## Layout

| Path | Content |
| --- | --- |
| `docs/` | Published via GitHub Pages (source: `main` branch, `/docs` folder). Slides and the 8-pager. Do not put work-in-progress here. |
| `georef/` | Analysis of the hand-annotated paper atlas (see below). |
| `AGENTS.md` | Instructions for AI agents and collaborators working in this repository. |

## Field activity and the atlas

Participants annotated a printed atlas ("Zukaku: November Field Mapping (8 pager)") during the field activity, mostly with the number of building levels.
The atlas has 8 sheets (A1–A4, B1–B4) and was generated with [Zukaku](https://dwg7.unopengis.org/zukaku) (`docs/8pager.pdf`).

The goal of `georef/` is to turn those handwritten notes into a table, cross-check them between teams, and reflect only verified values in OpenStreetMap.

Principles:

- One verified building is more valuable than many guessed buildings.
- A value becomes a verified candidate only when two or more teams agree.
- Disagreements, unreadable marks and unclear notes (for example "6+1") are kept as `unsure`. They are never filled in by guessing.
- Observations by a single team are kept separately and are not uploaded automatically.
- Sketches that require splitting buildings (terraced rows) are handled in a separate stage from level tagging.
- Uploads to OSM are done by a human, after review, from their own account (tag: `building:levels`).

## Working in `georef/`

See [`georef/README.md`](georef/README.md) once it exists; until then, [`AGENTS.md`](AGENTS.md) describes the workflow, the table format and the rules.

## Background

This work follows the history of Field Papers using present-day web mapping (Zukaku) and AI.
It is carried out by the JICA consultant team, with Hidenori Fujimura (hfu) as resource person.

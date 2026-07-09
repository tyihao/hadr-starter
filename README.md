# Disaster Risk Ranking

A Python command-line tool that ranks the top 10 countries most at risk of
natural disasters.

## What it does

The CLI pulls disaster-risk indicators, scores each country, and prints the ten
highest-risk countries as a ranked list.

## Reference material

- `feeds/` — notes on the disaster data feeds (GDACS, USGS, ReliefWeb) used as
  reference for sourcing risk indicators.

## Repository conventions

- `scripts/` — deterministic checks and helpers.
- `docs/solutions/` — one learning per file; read before debugging.
- `skills/` — reusable skills, one folder each.
- `implementation-notes.md` — running log of decisions, open questions, and
  deviations.

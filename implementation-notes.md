# Implementation notes

Kept by the agent, reviewed by you. One entry per working block.

## Decisions

## Open questions

## Deviations

<!-- Anything built that departs from the PRD or CLAUDE.md is recorded here,
     with the reason. An undocumented deviation is a bug. -->

### 2026-07-09 — Legacy artefact cleanup

Removed stale artefacts left over from the "HADR Monitor" template that no
longer describe the current project (a Python CLI ranking the top 10 countries
most at risk of natural disasters):

- **Deleted `README.md`** — described the old "HADR Monitor" agent/dashboard/
  sitrep concept. Replaced with a short README for the actual project.
- **Deleted `.github/workflows/sitrep.yml.disabled`** — a disabled scaffold for
  the old scheduled "morning sitrep" that published `dashboard.html`. Not part
  of the current project.

Notes:

- No `causeway` / JB drive-time / LTA-DataMall references were found anywhere in
  the repository, so there was nothing to remove on that front.
- Kept `feeds/` (useful reference) and the repository conventions
  (`scripts/`, `docs/solutions/`, `skills/`) as instructed.
- Left `.gitignore` untouched: it still mentions the old `*.sitrep.html` /
  `dashboard.html` outputs, but editing it was outside the agreed cleanup scope.

# DND — Dungeons & Dragons Reference Collection

A personal reference library for D&D 5th Edition rules, structured game data,
5E tooling source code, and Forgotten Realms lore. See [ATTRIBUTION.md](ATTRIBUTION.md)
for sources and licenses.

## Contents

| Path | What it is |
|---|---|
| `*.json`, `GAP_ANALYSIS.md` (root) | SRD 5.2.1 structured data — classes, spells, monsters, equipment, feats, backgrounds, races, rules |
| `5e-database/` | 5e-database (5e-bits) — SRD 2014 + 2024 structured JSON, English only |
| `5e-srd-api/` | 5e-srd-api (5e-bits) — successor dataset with 2024 / SRD 5.2 data, English only |
| `5etools/` | 5etools data mirror — bestiary, spells, items, classes, adventures, books |
| `forgotten-realms/` | All 58,546 Forgotten Realms Wiki articles as clean markdown, sharded by title |
| `python/avrae/` | Avrae Discord bot source (Python) — dice roller, initiative, character sheets |
| `python/d20/` | d20 dice roller Python library |

## Finding lore

Lore articles live under `forgotten-realms/<first-letter>/<first-two-letters>.md`.
Each file holds many articles as `## Title` sections. Example:

- `forgotten-realms/w/wa.md` → Waterdeep
- `forgotten-realms/e/el.md` → Elminster
- `forgotten-realms/d/dr.md` → Drizzt, Drow

## Notes

- Wiki articles are converted from the 2025-10-22 dump: wikitext → markdown,
  templates/navboxes/images stripped, redirects excluded.
- Non-English data files, test suites, and generated indexes were pruned.

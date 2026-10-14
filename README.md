# DND — Dungeons & Dragons Reference Collection

A personal reference library for D&D rules, structured game data, and Forgotten Realms lore — organized for AI agents. See [ATTRIBUTION.md](ATTRIBUTION.md) for sources and licenses. See [INDEX.json](INDEX.json) for a machine-readable manifest.

## Contents

| Path | What it is |
|---|---|
| `backgrounds/`, `classes/`, `equipment/`, `feats/`, `monsters/`, `races/`, `rules/`, `spells/` | SRD 5.2.1 structured data organized by type (JSON) |
| `5e-database/2024/` | 5e-database project JSON dumps, 2024 data only |
| `5e-srd-api/2024/` | 5e-srd-api project JSON, 2024 data only |
| `5etools/` | 5etools data mirror — 461 files: bestiary (199), adventure (93), book (61), class (32), spells (29). Full official 5e content. |
| `3e-core/` | D&D 3.5e core rules as markdown: Player's Handbook, Dungeon Master's Guide, Monster Manual, universal rules (24,359 entries, from PCGen) |
| `3e-forgotten-realms/` | D&D 3.5e Forgotten Realms sourcebooks as markdown: 13 books including Faiths and Pantheons, Races of Faerun, Magic of Faerun, City of Splendors: Waterdeep, Underdark, and more (7,416 entries, from PCGen) |
| `forgotten-realms/` | All 58,546 Forgotten Realms Wiki articles as clean markdown, sharded by title |
| `python/avrae/` | Avrae Discord bot source (Python) |
| `python/d20/` | d20 dice roller Python library |

## Finding things

- **5e rules**: Start with the type directories (`classes/`, `spells/`, `monsters/`) for SRD data, or `5etools/` for the full corpus.
- **3.5e rules**: `3e-core/` for core, `3e-forgotten-realms/` for Realms-specific.
- **Lore**: `forgotten-realms/<first-letter>/<first-two-letters>.md`, articles as `## Title` sections. Example: `forgotten-realms/w/wa.md` → Waterdeep.

## Notes

- 2014 (5e) data was pruned; 2024 is canonical for 5e. 3.5e data is preserved for edition comparison.
- Wiki articles converted from 2025-10-22 dump: wikitext → markdown, templates/navboxes/images stripped.
- 3e markdown converted from PCGen open-source datasets (LGPL).
- Non-English data files, test suites, and generated indexes were pruned.

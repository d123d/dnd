# SRD 5.2.1 Cartridge Gap Analysis

Comparison against the official SRD 5.2.1 documentation from D&D Beyond.

**Last Updated:** March 9, 2026
**Status:** ✅ ALL GAPS FIXED

## Summary

| Category | Status | Notes |
|----------|--------|-------|
| Species | ✅ Fixed | Aasimar removed (IP protected) |
| Classes | ✅ Complete | All 12 PHB classes present |
| Subclasses | ✅ Complete | All SRD subclasses included |
| Spells | ✅ Fixed | Added 19 missing spells |
| Feats | ✅ Fixed | Added Fighting Styles, Epic Boons, ASI |
| Equipment | ✅ Fixed | Added 17 magic items |
| Rules | ✅ Fixed | Added Travel, Environment, Weapon Masteries |
| Monsters | ✅ Fixed | Added 17 SRD 5.2 monsters |

---

## ✅ Fixed Issues

### 1. Species: Aasimar REMOVED ✅

**Issue:** Aasimar was included but is **explicitly excluded** from SRD 5.2 for IP protection.

> "Some classes (such as the Artificer), species (like Aasimar), and monsters (including the Beholder) have been excluded. These exclusions are based on brand identity protection, licensing strategy, and intellectual property rights."

**Resolution:** Removed Aasimar from `races/races.json`

---

## 🟡 Missing Spells (19 spells)

The following spells were **added in SRD 5.2** but are missing from `spells.json`:

| Spell | Level | School |
|-------|-------|--------|
| Charm Monster | 4 | Enchantment |
| Chromatic Orb | 1 | Evocation |
| Dissonant Whispers | 1 | Enchantment |
| Divine Smite | 1 | Evocation |
| Dragon's Breath | 2 | Transmutation |
| Elementalism | 0 | Transmutation |
| Ensnaring Strike | 1 | Conjuration |
| Hex | 1 | Enchantment |
| Ice Knife | 1 | Conjuration |
| Mind Spike | 2 | Divination |
| Phantasmal Force | 2 | Illusion |
| Power Word Heal | 9 | Enchantment |
| Ray of Sickness | 1 | Necromancy |
| Searing Smite | 1 | Evocation |
| Sorcerous Burst | 0 | Evocation |
| Starry Wisp | 0 | Evocation |
| Summon Dragon | 5 | Conjuration |
| Tsunami | 8 | Conjuration |
| Vitriolic Sphere | 4 | Evocation |

---

## 🟡 Missing Feats

### Fighting Styles (should be feats in 2024 rules)
- Archery
- Defense
- Great Weapon Fighting
- Two-Weapon Fighting

### Epic Boons (Level 19+ features)
- Boon of Combat Prowess
- Boon of Dimensional Travel
- Boon of Fate
- Boon of Irresistible Offense
- Boon of the Night Spirit
- Boon of Spell Recall
- Boon of Truesight

### Other
- Ability Score Improvement (as a feat)

---

## 🟡 Missing Magic Items

The following magic items were **added in SRD 5.2**:

- Bead of Nourishment
- Cloak of Invisibility
- Elixir of Health
- Energy Bow
- Gloves of Thievery
- Hat of Many Spells
- Potion of Invulnerability
- Potion of Longevity
- Potion of Vitality
- Quarterstaff of the Acrobat
- Rod of Resurrection
- Sending Stones
- Sentinel Shield
- Shield of the Cavalier
- Thunderous Greatclub

**Note:** "Deck of Many Things" renamed to "Mysterious Deck" and "Orb of Dragonkind" renamed to "Dragon Orb" in SRD 5.2

---

## 🟡 Missing Rules Sections

### Travel Pace
Rules for overland travel speeds and distances.

### Environmental Effects
Rules for various environmental hazards.

### Weapon Masteries
New 2024 weapon mastery properties system.

### Crafting Rules
- Brewing Potions of Healing
- Scribing Spell Scrolls

---

## 🔴 Missing: Monsters/Bestiary

The cartridge has no monster data. SRD 5.2 includes many monsters:

**New in 5.2:**
- Allosaurus
- Ankylosaurus
- Archelon
- Bugbear Stalker
- Goblin Boss
- Goblin Minion
- Guard Captain
- Hippopotamus
- Hobgoblin Captain
- Pirate
- Pirate Captain
- Pteranodon
- Sphinx of Wonder
- Swarm of Crawling Claws
- Tough Boss
- Troll Limb
- Vampire Familiar

**Note:** SRD 5.2 excludes iconic monsters like Beholder, Mind Flayer, etc. for IP protection.

---

## ✅ Correctly Included

### Species (8 of 9 correct)
- ✅ Human
- ✅ Dragonborn
- ✅ Dwarf
- ✅ Elf
- ✅ Gnome
- ✅ Goliath (new in 5.2)
- ✅ Halfling
- ✅ Orc (new in 5.2)
- ✅ Tiefling
- ❌ Aasimar (should be removed)

### Backgrounds (3 new in 5.2)
- ✅ Criminal (new)
- ✅ Sage (new)
- ✅ Soldier (new)

### Equipment
- ✅ Musket (new in 5.2)
- ✅ Pistol (new in 5.2)

---

## Priority Actions

### High Priority
1. **Remove Aasimar** from races.json (IP violation)
2. **Add 19 missing spells** to spells.json
3. **Add Fighting Style feats** to feats.json

### Medium Priority
4. Add Epic Boons to feats.json
5. Add magic items to equipment.json
6. Add Travel Pace and Environmental Effects to rules/

### Low Priority
7. Create monsters.json with SRD bestiary
8. Add crafting rules

---

## References

- [SRD 5.2.1 PDF](https://media.dndbeyond.com/compendium-images/srd/5.2/SRD_CC_v5.2.pdf)
- [D&D Beyond SRD Page](https://www.dndbeyond.com/srd)
- [SRD 5.2 FAQ](https://www.dndbeyond.com/srd#SRD52FAQ)

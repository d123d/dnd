# D&D 5e SRD 5.2.1 Cartridge

A complete cartridge containing the official System Reference Document (SRD) 5.2.1 content for D&D 5th Edition (2024 revision).

## Contents

This cartridge includes:

- **12 Classes** with features and spellcasting rules
- **20+ Subclasses** across all classes
- **10 Races** with traits, languages, and ability bonuses
- **16 Backgrounds** with the 2024 format (ability increases, feats, equipment)
- **50+ Spells** from cantrips to 9th level
- **35+ Feats** (Origin and General feats)
- **38 Weapons** (Simple and Martial)
- **13 Armor types** (Light, Medium, Heavy, Shields)
- **20+ Adventuring Gear** items
- **7 Equipment Packs**
- **18 Skills** with descriptions
- **15 Conditions** with effects

## File Structure

```
sdr-5.2.1/
├── cartridge.json          # Manifest file
├── README.md               # This file
├── races/
│   └── races.json          # All playable species
├── classes/
│   ├── classes.json        # Base class definitions
│   └── subclasses.json     # Subclass options
├── spells/
│   └── spells.json         # Spell database
├── equipment/
│   └── equipment.json      # Weapons, armor, gear
├── backgrounds/
│   └── backgrounds.json    # Character backgrounds
├── rules/
│   ├── skills.json         # Skill definitions
│   └── conditions.json     # Condition effects
├── feats/
│   └── feats.json          # Feat options
└── doc/
    └── SRD_CC_v5.2.1.pdf   # Original SRD document
```

## Game Rules

### Attributes
- **Strength (STR)** - Physical power
- **Dexterity (DEX)** - Agility and reflexes
- **Constitution (CON)** - Health and stamina
- **Intelligence (INT)** - Reasoning and memory
- **Wisdom (WIS)** - Perception and insight
- **Charisma (CHA)** - Force of personality

### Derived Stats
- **Armor Class (AC)**: `10 + dexMod` (base)
- **Initiative**: `dexMod`
- **Hit Points**: Class hit die + `conMod` per level
- **Proficiency Bonus**: `floor((level - 1) / 4) + 2`
- **Ability Modifier**: `floor((score - 10) / 2)`

### Ability Score Methods
- **Standard Array**: 15, 14, 13, 12, 10, 8
- **Point Buy**: 27 points to distribute (8-15 range)
- **Rolling**: 4d6 drop lowest, six times
- **Manual**: Direct assignment

## 2024 Rules Updates

This cartridge reflects the 2024 D&D rules revision:

- **Backgrounds** grant a 1st-level feat and ability score increases
- **Species** (formerly races) no longer grant ability score increases
- **Feats** are categorized as Origin feats (1st level) or General feats (4th+)
- **Weapon Mastery** properties for martial characters
- **Spell changes** including updated casting times and effects
- **Condition updates** with clearer mechanical effects

## Usage

Load this cartridge in NatOne to use official SRD 5.2.1 content for character creation and gameplay.

```json
{
  "activeCartridge": "srd-5.2.1",
  "version": "1.0.0"
}
```

## License

This cartridge contains content from the System Reference Document 5.2.1, licensed under the **Creative Commons Attribution 4.0 International License (CC-BY-4.0)**.

You are free to:
- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit to Wizards of the Coast

Full license: https://creativecommons.org/licenses/by/4.0/

## Version History

- **1.0.0** - Initial release with complete SRD 5.2.1 content

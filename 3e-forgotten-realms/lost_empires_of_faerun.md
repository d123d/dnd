# Lost Empires of Faerun

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Ability Categories

### ABILITYCATEGORY:Dead or Forgotten Gods

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **DISPLAYLOCATION:** Feats
- **PLURAL:** Dead or Forgotten Gods

### ABILITYCATEGORY:Godsight Perception

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **DISPLAYLOCATION:** Feats
- **PLURAL:** Godsight Perception

### ABILITYCATEGORY:Cultist of the Shattered Peak Class Feature

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Cultist of the Shattered Peak Class Features

### ABILITYCATEGORY:Glorious Servitor Class Feature

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Glorious Servitor Class Features

### ABILITYCATEGORY:Magelord Class Feature

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Magelord Class Features

### ABILITYCATEGORY:Olin Gisir Class Feature

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Olin Gisir Class Features

### ABILITYCATEGORY:Sunmaster Class Feature

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Sunmaster Class Features

### ABILITYCATEGORY:Magelord Mastered Spells

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Magelord Mastered Spells

### ABILITYCATEGORY:Olin Gisir Secrets

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Olin Gisir Secrets

### ABILITYCATEGORY:Forgotten Spell Lore

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **DISPLAYLOCATION:** Feats
- **PLURAL:** Forgotten Spell Lore

### ABILITYCATEGORY:Ancient Artiface

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **DISPLAYLOCATION:** Feats
- **PLURAL:** Ancient Artiface

### ABILITYCATEGORY:Olin Gisir Words of Dispel

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Olin Gisir Words of Dispel

### ABILITYCATEGORY:Olin Gisir Words of Might

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **DISPLAYLOCATION:** Class Features
- **PLURAL:** Olin Gisir Words of Might

## Class Abilities

### Weapons and Armor Proficiency


### Spells


### Ominous Presence

- **BONUS:** SKILL|Bluff,Intimidate|CotSPLVL

### Zeal

- **ASPECT:** SaveBonus|+1 morale bonus against arcane spells and effects.
- **ASPECT:** CombatBonus|+1 morale bonus against arcane casters.

### Sneak Attack

- **BONUS:** VAR|SneakAttackDice|(CotSPLVL/2)

### Smite Mage


### Death Attack


### Bestial Form


### Fearlessness

- **ASPECT:** SaveBonus|Immune to fear effects

### Spell Resistance

- **SR:** (12+GloriousServitorLVL)

### Divine Shield


### Increased Strength

- **BONUS:** STAT|STR|GSDivineStrengthBonus

### Divine Voice


### True Seeing

- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|True Seeing

### Greater Command

- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Command (Greater)

### Immunity to Poison

- **ASPECT:** SaveBonus|Immune to poison

### Divine Transformation


### Mass Cure Light Wounds

- **!PREDEITY:** 1,Set,Sebek
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Cure Light Wounds (Mass)|!PREDEITY:1,Set,Sebek

### Mass Inflict Light Wounds

- **PREDEITY:** 1,Set,Sebek
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Inflict Light Wounds (Mass)

### Bonus Mastered Spell

- **BONUS:** ABILITYPOOL|Magelord Mastered Spells|MagelordMasteredSpellsBonus

### Signature Supremacy


### Magelord Mastery


### Magelord Mastered Spell

- **MULT:** YES
- **CHOOSE:** SPELLS|CLASSLIST=Wizard[KNOWN=YES]
- **SELECT:** 1

### Ancient Knowledge

- **BONUS:** SKILL|Knowledge (Arcana),Knowledge (History),Use Magic Device|OlinGisirKnowledgeBonus
- **BONUS:** VAR|BardicKnowledge|OlinGisirKnowledgeBonus

### Secret

- **BONUS:** ABILITYPOOL|Olin Gisir Secrets|((OlinGisirLVL/3.25)+1)

### Signs and Portents

- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Augury

### Word of Dispel

- **BONUS:** ABILITYPOOL|Olin Gisir Words of Dispel|1

### Word of Might

- **BONUS:** ABILITYPOOL|Olin Gisir Words of Might|1

### Lore of Tongues

- **PREVARGTEQ:** OlinGisirSecretsLVL,1
- **MULT:** NO
- **ADD:** LANGUAGE|3|ALL

Gain three additional languages (except secret languages)

An Olin Gisir secret, learn 3 new languages (except secret languages).

### Secret of Health

- **PREVARGTEQ:** OlinGisirSecretsLVL,2
- **MULT:** NO
- **BONUS:** HP|CURRENTMAX|3

+3 hit points

An Olin Gisir secret, gain 3 HP.

### Secrets of Inner Strength

- **PREVARGTEQ:** OlinGisirSecretsLVL,3
- **MULT:** NO
- **BONUS:** SAVE|BASE.Will|2

+2 bonus on Will saves

An Olin Gisir secret, gain a +2 bonus to Will saves.

### The Lore of True Stamina

- **PREVARGTEQ:** OlinGisirSecretsLVL,4
- **MULT:** NO
- **BONUS:** SAVE|BASE.Fortitude|2

+2 bonus on Fortitude saves

An Olin Gisir secret, gain a +2 bonus to Fortitude saves.

### Dungeon Navigation

- **PREVARGTEQ:** OlinGisirSecretsLVL,5
- **MULT:** NO
- **ABILITY:** Special Ability|AUTOMATIC|Trap Sense
- **BONUS:** VAR|TrapSenseBonus|2

+2 Trap Sense

An Olin Gisir secret, gain a +2 Trap Sense.

### Sight of the Hidden

- **PREVARGTEQ:** OlinGisirSecretsLVL,6
- **MULT:** NO
- **BONUS:** SKILL|Search|4

+4 bonus on Search

An Olin Gisir secret, gain a +4 bonus on Search rolls.

### Ancient Artiface

- **PREVARGTEQ:** OlinGisirSecretsLVL,7
- **MULT:** NO
- **BONUS:** ABILITYPOOL|Ancient Artiface|1

Gain an Item Creation feat

An Olin Gisir secret, gain an Item Creation feat.

### Forgotten Spell Lore

- **PREVARGTEQ:** OlinGisirSecretsLVL,8
- **MULT:** NO
- **BONUS:** ABILITYPOOL|Forgotten Spell Lore|1

Gain a Metamagic feat

An Olin Gisir secret, gain a Metamagic feat.

### Fiend Warding

- **PREVARGTEQ:** OlinGisirSecretsLVL,9
- **MULT:** NO
- **ASPECT:** SaveBonus|+2 sacred bonus to AC and Saves against attacks made by evil outsiders

Gain a +2 sacred bonus to AC and Saves against attack made by evil outsiders

An Olin Gisir secret, gain a +2 sacred bonus to AC and saves against attacks made by evil outsiders.

### Focused Mind

- **PREVARGTEQ:** OlinGisirSecretsLVL,10
- **MULT:** NO
- **ASPECT:** SaveBonus|Spell resistance 20 against Enchantment spells

Gain a spell resistances 20 against Enchantment spells

An Olin Gisir secret, gain a spell resistance 20 against Enchantment spells.

### Dispel Evil

- **SPELLKNOWN:** CLASS|SPELLCASTER.Arcane=5|Dispel Evil

### Dispel Chaos

- **SPELLKNOWN:** CLASS|SPELLCASTER.Arcane=5|Dispel Chaos

### Dispel Law

- **SPELLKNOWN:** CLASS|SPELLCASTER.Arcane=5|Dispel Law

### Dictum

- **SPELLKNOWN:** CLASS|SPELLCASTER.Arcane=7|Dictum

### Holy Word

- **SPELLKNOWN:** CLASS|SPELLCASTER.Arcane=7|Holy Word

### Word of Chaos

- **SPELLKNOWN:** CLASS|SPELLCASTER.Arcane=7|Word of Chaos

### Sun Spells

- **SPELLKNOWN:** CLASS|Cleric=1|Endure Elements|Cleric=2|Heat Metal|Cleric=3|Searing Light|Cleric=4|Fire Shield|Cleric=5|Flame Strike|Cleric=6|Fire Seeds|Cleric=7|Sunbeam|Cleric=8|Sunburst|Cleric=9|Prismatic Sphere

### Glaring Eyes

- **SPELLS:** Innate|TIMES=SunmasterGlaringEyesUsages|CASTERLEVEL=TL|Searing Light

### Resistance to Fire

- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Fire
- **BONUS:** VAR|FireResistanceBonus|SunmasterFireResistance

### Law Spells

- **SPELLKNOWN:** CLASS|Cleric=1|Protection from Chaos|Cleric=2|Calm Emotions|Cleric=3|Magic Circle against Chaos|Cleric=4|Order's Wrath|Cleric=5|Dispel Chaos|Cleric=6|Hold Monster|Cleric=7|Dictum|Cleric=8|Shield of Law|Cleric=9|Summon Monster IX

### Planning Domain

- **BONUS:** DOMAIN|NUMBER|1

### Sunform


## Classes

### CLASS:Cultist of the Shattered Peak

- **HD:** 6
- **FACT:** ClassType|Prestige
- **FACT:** Abb|CSP
- **MAXLEVEL:** 5

### 1

- **ABILITY:** Cultist of the Shattered Peak Class Feature|AUTOMATIC|CotSP ~ Weapons and Armor

### 2

- **ABILITY:** Cultist of the Shattered Peak Class Feature|AUTOMATIC|CotSP ~ Sneak Attack

### 3

- **ABILITY:** Cultist of the Shattered Peak Class Feature|AUTOMATIC|CotSP ~ Smite Mage

### 5

- **ABILITY:** Cultist of the Shattered Peak Class Feature|AUTOMATIC|CotSP ~ Death Attack

### 4

- **CAST:** 3,1

### CLASS:Glorious Servitor

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|GlorServ
- **MAXLEVEL:** 7

### 7

- **ABILITY:** Glorious Servitor Class Feature|AUTOMATIC|Glorious Servitor ~ Divine Transformation

### CLASS:Magelord

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Magelord
- **MAXLEVEL:** 10

### 9

- **BONUS:** VAR|SneakAttackDice|1

### 10

- **ABILITY:** Magelord Class Feature|AUTOMATIC|Magelord ~ Magelord Mastery

### 6

- **ADD:** SPELLCASTER|ANY

### 8

- **ADD:** SPELLCASTER|ANY

### CLASS:Olin Gisir

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|OG
- **MAXLEVEL:** 10

### CLASS:Sunmaster

- **HD:** 8

## Deities

### Amaunator

- **ALIGN:** LN
- **FACTSET:** Pantheon|Faerun
- **DEITYWEAP:** Mace (Light)
- **DOMAINS:** Law,Nobility,Planning,Sun,Time

Amaunator (dead)

### Auppenser

- **ALIGN:** TN
- **FACTSET:** Pantheon|Psionic
- **DEITYWEAP:** Kukri
- **DOMAINS:** Balance,Mentalism,Protection,Strength

Auppenser (dead)

### Bhaal

- **ALIGN:** LE
- **FACTSET:** Pantheon|Faerun
- **DEITYWEAP:** Dagger
- **DOMAINS:** Death,Destruction,Evil,Retribution

Bhaal (dead)

### Gilgeam

- **ALIGN:** LE
- **FACTSET:** Pantheon|Untheric
- **DEITYWEAP:** Mace (Heavy)
- **DOMAINS:** Air,Strength,Tyranny,War

Gilgeam (dead)

### Ibrandul

- **ALIGN:** CN
- **FACTSET:** Pantheon|Faerun
- **DEITYWEAP:** Greatclub
- **DOMAINS:** Cavern,Darkness,Scalykind,Travel

Ibrandul (dead)

### Leira

- **ALIGN:** CN
- **FACTSET:** Pantheon|Faerun
- **DEITYWEAP:** Dagger
- **DOMAINS:** Charm,Illusion,Spell,Trickery

Leira (dead)

### Moander

- **ALIGN:** CE
- **FACTSET:** Pantheon|Faerun
- **DEITYWEAP:** Mace (Heavy)
- **DOMAINS:** Corruption,Destruction,Evil,Slime

Moander (dead)

### Myrkul

- **ALIGN:** NE
- **FACTSET:** Pantheon|Faerun
- **DEITYWEAP:** Scythe
- **DOMAINS:** Death,Evil,Suffering,Undeath

Myrkul (dead)

### Ramman

- **ALIGN:** LN
- **FACTSET:** Pantheon|Untheric
- **DEITYWEAP:** Khopesh
- **DOMAINS:** Law,Planning,Protection,War

Ramman (dead)

### Tchazzar

- **ALIGN:** CE
- **FACTSET:** Pantheon|Faerun
- **DEITYWEAP:** Longsword
- **DOMAINS:** Scalykind,Strength,War

Tchazzar (dead)

## Equip General

### Scepter

- **COST:** 0
- **WT:** 3
- **MODS:** REQUIRED

### Holy Symbol of Amaunator, Wooden

- **SORTKEY:** Tools
- **COST:** 1
- **WT:** 0

Wooden holy symbol of the dead god, Amaunator

### Holy Symbol of Amaunator, Silver

- **SORTKEY:** Tools
- **COST:** 25
- **WT:** 1

Silver holy symbol of the dead god, Amaunator

### Arcane Histories of the Athalantaran Magelords

- **SORTKEY:** Tools
- **COST:** 10000
- **WT:** 200

An extensive set of rare volumes and histories, typically gathered in large codices, detailing the history and lore of magelords of the Athalantaran Kingdom of the Stag. This is a body of work necessary for study to become a magelord.

## Equip Magic

### Armathor's Sling Stones

- **COST:** 12305
- **BASEQTY:** 50
- **EQMOD:** PLUS1W
- **SPROP:** Each stone produces a Slow effect (Will DC 14 negates) on any creature it strikes.
- **SPROP:** Faint Transformation; CL 5th

### Delimbiyra's Shining Bow

- **COST:** 6800
- **BASEITEM:** Longbow
- **EQMOD:** BOWSTR|+4.PLUS1W.WOOD
- **SPROP:** Arrows shot from this longbow become silvered weapons in flight, and any creature struck by one is subject to the effects of a silver-hued Faerie Fire spell.
- **SPROP:** Faint evocation; CL 4th

### Nimblestep

- **COST:** 18310
- **BASEITEM:** Sword (Short)
- **EQMOD:** PLUS1W
- **SPROP:** A psionic character wielding a nimblestep can take a move action instead of a full-round action to become psionically focused. A psionic wielder also gains Up the Walls as a bonus feat, but only so long as he carries the weapon in his hand. In addition, a psionically focused wielder of a nimblestep can expend his psionic focus to gain a +10 bonus on a single Jump check.
- **SPROP:** psychometabolism; ML 5th

### Spear of Morgur

- **COST:** 52305
- **BASEITEM:** Spear
- **EQMOD:** PLUS1W.BRI_EN_M
- **SPROP:** Any creature touched by it is bathed in rose-hued Faerie Fire for 1 round.
- **SPROP:** Moderate Transmutation; CL 16th

### Ring of Creation

- **COST:** 33000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=3|CASTERLEVEL=9|Minor Creation
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Major Creation
- **SPROP:** Moderate Conjuration; CL 9th

### Fiendring

- **COST:** 30000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=12|Fiendform
- **SPROP:** Moderate Transmutation; CL 12th

### Ring of Whispered Thoughts

- **COST:** 50000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=3|CASTERLEVEL=11|Whispering Wind
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Suggestion
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Week|CASTERLEVEL=11|Suggestion (Mass)
- **SPROP:** Moderate Enchantment; CL 11th

### Netherese Blast Scepter

- **COST:** 48000
- **WT:** 1
- **SPROP:** Empowered Lightning Bolt (caster level 10th, 15d6 damage, 2 charges), Maximized Shocking Grasp (caster level 7th, 30 points damage, 1 charge)
- **SPROP:** Moderate Evocation; CL 10th

### Silver Ankh of Ra

- **COST:** 33750
- **WT:** 1
- **SPROP:** Searing Light (caster level 10th, dealing 5d8, 10d6, or 10d8 damage, 1 charge), Cure Serious Wounds (caster level 10th, healing 3d8+10 damage, 1 charge)
- **SPROP:** Faint Evocation and Conjuration; CL 10th

### Lesser Staff of Silverymoon

- **COST:** 70000
- **WT:** 1
- **SPROP:** Arcane Sight (1chg), Fly (1chg), Dimension Door (2chgs), Minor Globe of Invulnerability (2chgs), Animate Object (3chgs), Chain Lightning (3chgs), Hold Monster (3chgs), Passwall (3chgs), Wall of Force (3chgs), Forcecage (4chgs)
- **SPROP:** Strong Evocation; CL 15th

### Thyrsus of the Druid

- **COST:** 53000
- **WT:** 1
- **SPROP:** Plant Growth (1chg), Speak with Plants (1chg), Animate Plants (2chgs), Thorn Spray (2chgs), Control Plants (3chgs)
- **SPROP:** Strong varied; CL 15th

### Aoxar's Helm

- **COST:** 15400
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=5|Deathwatch
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Speak with Dead
- **SPROP:** Faint Necromancy; CL 5th

### Battlecloak of Vycaena

- **COST:** 38000
- **CONTAINS:** *UNLIM|Total=2
- **BONUS:** COMBAT|AC|4|TYPE=Armor
- **BONUS:** SAVE|ALL|1|TYPE=Resistance
- **SPROP:** Grants the wearer a +4 armor bonus to AC and a +1 resistance bonus to all saving throws. As well each of the two clasps can store one item in the same manner as a Glove of Storing.
- **SPROP:** Faint Transmutation; CL 8th

### Chylnoth's Coronet

- **COST:** 100000
- **SPROP:** Functions as a Helm of Underwater Action. Allows the wearer to use Freedom of Movement for up to 1 hour per day (non-consecutive apportionment). Cat figurine acts as a Figurine of Wondrous Power summoning a sea cat (Monster Manual p.220) which can summoned twice per week and remains for up to 6 hours per use.
- **SPROP:** Moderate Transmutation; CL 11th

### Giiraegisir (1/day)

- **COST:** 10800
- **SPROP:** As a free action, grants the wearer a +5 deflection bonus to AC for 1 minute 1/day.
- **SPROP:** Moderate Abjuration; CL 10th

### Giiraegisir (3/day)

- **COST:** 21600
- **SPROP:** As a free action, grants the wearer a +5 deflection bonus to AC for 1 minute 3/day.
- **SPROP:** Moderate Abjuration; CL 10th

### Golden Orb of Siluvanede

- **COST:** 30600
- **SPROP:** Can absorb and negate one spell or spell-like ability that targets its owner 1/day as the owner chooses.
- **SPROP:** Strong Abjuration; CL 17th

### Harness of Armor +1

- **COST:** 1500
- **BONUS:** COMBAT|AC|1|TYPE=Armor
- **SPROP:** Grants the wearer a +1 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 7th

### Harness of Armor +2

- **COST:** 6000
- **BONUS:** COMBAT|AC|2|TYPE=Armor
- **SPROP:** Grants the wearer a +2 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 7th

### Harness of Armor +3

- **COST:** 12500
- **BONUS:** COMBAT|AC|3|TYPE=Armor
- **SPROP:** Grants the wearer a +3 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 7th

### Harness of Armor +4

- **COST:** 24000
- **BONUS:** COMBAT|AC|4|TYPE=Armor
- **SPROP:** Grants the wearer a +4 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 8th

### Harness of Armor +5

- **COST:** 37500
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **SPROP:** Grants the wearer a +5 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 10th

### Harness of Armor +6

- **COST:** 54000
- **BONUS:** COMBAT|AC|6|TYPE=Armor
- **SPROP:** Grants the wearer a +6 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 12th

### Harness of Armor +7

- **COST:** 73500
- **BONUS:** COMBAT|AC|7|TYPE=Armor
- **SPROP:** Grants the wearer a +7 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 14th

### Harness of Armor +8

- **COST:** 96000
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** Grants the wearer a +8 armor bonus to AC.
- **SPROP:** Moderate Conjuration; CL 16th

### Orb of Tempests

- **COST:** 85000
- **SPROP:** Acts as a Crystal Ball (Scrying, Will DC 16 to negate). Viewer can produce a Control Weather effect 1/day, centered on person or locale being viewed.
- **SPROP:** Strong Transmutation; CL 13th

### Telkiira

- **COST:** 100000
- **BONUS:** SAVE|Will|4|TYPE=Insight
- **BONUS:** STAT|INT|4|TYPE=Enhancement
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|2
- **NUMPAGES:** 200
- **PAGEUSAGE:** max(SPELLLEVEL,1)
- **SPROP:** Wearer gains +4 insight bonus on Will saves. Wearer gains +4 enhancement bonus to Intelligence. Device has its own skill ranks that can be used in place of wearers, using the wearers ability modifier; Decipher Script (10 ranks), Knowledge (Arcana) (10 ranks), Knowledge (History) (10 ranks), Spellcraft (10 ranks). A telkiira functions as a 200 page spellbook that can be written or erased as the wearer sees fit. A telkiira holds 10 distinct memories up to 1 hour in length, requiring 1 full round to write. Non-elf/-half-elf wearers gain 2 negative levels.
- **SPROP:** Strong Transmutation; CL 20th, Elf

## Equipment Modifiers

### |Spell Effect (Scepter/Primary Power)

- **ITYPE:** Enhancement.Magic
- **NAMEOPT:** SPELL
- **CHOOSE:** EQBUILDER.SPELL|Arcane,Divine|0|7
- **SPROP:** Using this power drains 1 charge
- **SPROP:** Using this power drains 2 charges
- **COST:** ((750 * %CASTERLEVEL * max(%SPELLLEVEL, (1/2))) + %SPELLCOST + %SPELLXPCOST)

### |Spell Effect (Scepter/Secondary Power)

- **ITYPE:** Enhancement.Magic
- **NAMEOPT:** SPELL
- **CHOOSE:** EQBUILDER.SPELL|Arcane,Divine|0|7
- **SPROP:** Using this power drains 1 charge
- **SPROP:** Using this power drains 2 charges
- **COST:** ((375 * %CASTERLEVEL * max(%SPELLLEVEL, (1/2))) + %SPELLCOST + %SPELLXPCOST)

### Powerleech

- **ITYPE:** Enhancement.Magic
- **PRETYPE:** 2,Enhancement,Weapon
- **COST:** 8000
- **SPROP:** Creature struck loses 1 power point, if wielder has point reserve they gain that point up to their normal maximum.

### Sending

- **ITYPE:** Enhancement.Magic
- **PRETYPE:** 2,Enhancement,Weapon
- **PLUS:** 4
- **SPROP:** On a natural 20, like a Teleport spell, transport target anyway the wielder has personally visited or seen on same plane.

## Feats

### Arcane Manipulation

- **MULT:** NO
- **PRECLASS:** 1,Wizard=1

### Arcane Transformation

- **MULT:** YES
- **!PREABILITY:** 1,CATEGORY=FEAT,Arcane Transformation
- **PRECLASS:** 1,Wizard=10
- **PRESUBCLASS:** 1,Abjurer,Conjurer,Diviner,Enchanter,Evoker,Illusionist,Necromancer,Transmuter
- **PREABILITY:** 2,CATEGORY=FEAT,Item Reprieve,Spell Reprieve
- **CHOOSE:** SCHOOLS|ABILITY=FEAT[Item Reprieve]
- **SELECT:** 1

### Channel Charge

- **MULT:** NO
- **PRESKILL:** 1,Use Magic Device=5
- **PRESPELLTYPE:** 1,Arcane=4,Divine=4

### Cormanthyran Moon Magic

- **MULT:** NO
- **PRESKILL:** 1,Knowledge (History)=4
- **PRESPELLTYPE:** 1,Arcane=3,Divine=3

### Craft Scepter

- **MULT:** NO
- **PRESKILL:** 1,Knowledge (History)=4
- **PRECLASS:** 1,SPELLCASTER=9

### Familiar Concentration

- **MULT:** NO
- **PREABILITY:** 1,CATEGORY=FEAT,Improved Familiar
- **PRECLASS:** 1,SPELLCASTER=9

### Godsight

- **MULT:** NO
- **PRESTAT:** 1,CHA=13
- **PREREGION:** Mulhorand
- **PRERACE:** 1,Human,Planetouched (Aasimar),Planetouched (Tiefling)
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Detect Magic|Detect Poison|Detect Undead|Read Magic
- **BONUS:** ABILITYPOOL|Godsight Perception|1

### Greenbond Summoning

- **MULT:** NO
- **PRESPELL:** 1,Summon Nature's Ally I,Summon Nature's Ally II,Summon Nature's Ally III,Summon Nature's Ally IV,Summon Nature's Ally V,Summon Nature's Ally VI,Summon Nature's Ally VII,Summon Nature's Ally VIII,Summon Nature's Ally IX

### Item Reprieve

- **MULT:** YES
- **!PREABILITY:** 1,CATEGORY=FEAT,Item Reprieve
- **PRECLASS:** 1,Wizard=5
- **PRESUBCLASS:** 1,Abjurer,Conjurer,Diviner,Enchanter,Evoker,Illusionist,Necromancer,Transmuter
- **PREABILITY:** 1,CATEGORY=FEAT,Spell Reprieve
- **CHOOSE:** SCHOOLS|Abjuration|Conjuration|Divination|Enchantment|Evocation|Illusion|Necromancy|Transmutation
- **SELECT:** 1

### Jergal's Pact

- **MULT:** NO
- **PRESKILL:** 1,Knowledge (History)=4
- **PREABILITY:** 1,CATEGORY=FEAT,Great Fortitude
- **ASPECT:** SaveBonus|Gain a +2 bonus on saves to resist gaining or to remove negative levels.

### Multilingual

- **MULT:** NO
- **PRECLASSLEVELMAX:** 1,TYPE.Base=1
- **PRESTAT:** 1,INT=15
- **ADD:** LANGUAGE|3|ALL
- **BONUS:** SKILL|Decipher Script|2
- **CSKILL:** Speak Language

### Netherese Battle Curse

- **MULT:** NO
- **PRESKILL:** 1,Knowledge (History)=4
- **PRECLASS:** 1,SPELLCASTER.Arcane=1
- **PREABILITY:** 1,CATEGORY=FEAT,Power Attack

### Servant of the Fallen

- **MULT:** YES
- **!PREABILITY:** 1,CATEGORY=FEAT,Servant of the Fallen
- **PRECLASS:** 1,Cleric=1
- **CHOOSE:** DEITY|TYPE=Dead
- **SELECT:** 1
- **PRETEXT:** Must worship a forgotten or dead deity.

### Spell Reprieve

- **MULT:** YES
- **PRESKILL:** 1,Knowledge (History)=2
- **PRECLASS:** 1,Wizard=1
- **PRESUBCLASS:** 1,Abjurer,Conjurer,Diviner,Enchanter,Evoker,Illusionist,Necromancer,Transmuter
- **CHOOSE:** SPELLS|CLASSLIST=Wizard
- **SELECT:** 1

### Trapmaster

- **MULT:** NO
- **PRESTAT:** 1,INT=13
- **PREABILITY:** 1,CATEGORY=Special Ability,Trap Sense
- **PREVARGTEQ:** TrapSenseBonus,2
- **BONUS:** VAR|TrapSenseBonus|4
- **BONUS:** SKILL|Disable Device|2

### Wounding Spell

- **MULT:** NO
- **PRESKILL:** 1,Knowledge (History)=4
- **PREABILITY:** 1,CATEGORY=FEAT,Empower Spell
- **ADDSPELLLEVEL:** 2

### Spell Mantle

- **PRESKILL:** 1,Knowledge (Arcana)=5
- **PRESKILL:** 1,Knowledge (History)=2
- **PREABILITY:** 1,CATEGORY=FEAT,Craft Contingent Spell

### Detect Evil

- **MULT:** NO
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Detect Evil

### Detect Good

- **MULT:** NO
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Detect Good

### Detect Law

- **MULT:** NO
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Detect Law

### Detect Chaos

- **MULT:** NO
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Detect Chaos

## Skills

### Hide (Forested Areas)

- **KEYSTAT:** DEX
- **USEUNTRAINED:** YES
- **CLASSES:** ALL
- **PRERULE:** 1,DISPLAYSKILLUSE
- **PREVARNEQ:** var("SKILL.Hide (Forested Areas).MISC"),SKILL.Hide.MISC

### Move Silently (Forested Areas)

- **KEYSTAT:** DEX
- **USEUNTRAINED:** YES
- **CLASSES:** ALL
- **PRERULE:** 1,DISPLAYSKILLUSE
- **PREVARNEQ:** var("SKILL.Move Silently (Forested Areas).MISC"),SKILL.Move Silently.MISC

## Spells

### Aura of the Sun

- **CLASSES:** Cleric,Paladin=4
- **SCHOOL:** Abjuration
- **DESCRIPTOR:** Light
- **COMPS:** V, S, DF
- **CASTTIME:** 1 standard action
- **RANGE:** 10 ft.
- **TARGETAREA:** 10-ft.-radius emanation center on you
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** No
- **SPELLRES:** None

### Backblast

- **CLASSES:** Wizard,Sorcerer=3
- **SCHOOL:** Abjuration
- **DESCRIPTOR:** Fire
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** Until expended or (CASTERLEVEL * 10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** None

### Bloodbriars

- **CLASSES:** Druid,Sorcerer,Wizard=4
- **SCHOOL:** Evocation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** 1 creature
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

### Clearstone

- **CLASSES:** Sorcerer,Wizard=3
- **SCHOOL:** Transmutation
- **DESCRIPTOR:** Earth
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Stone or stone object touched, up to (CASTERLEVEL) cu. ft.
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

### Crushing Sphere

- **CLASSES:** Sorcerer,Wizard=6
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** (CASTERLEVEL)-ft.-diameter sphere, centered around a creature
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** Reflex negates
- **SPELLRES:** Yes

### Ebon Ray of Doom

- **CLASSES:** Assassin=3|Sorcerer,Wizard=4
- **SCHOOL:** Necromancy
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Ray
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** Fortitude partial; see text
- **SPELLRES:** Yes

### Ghost Pipes

- **CLASSES:** Bard=1
- **SCHOOL:** Transmutation
- **COMPS:** V, F
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** One musical instrument
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** Will negates (object)
- **SPELLRES:** Yes (object)

### Know Bloodline

- **CLASSES:** Cleric=3
- **SCHOOL:** Divination
- **COMPS:** V, S, DF
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** One creature
- **DURATION:** Instantaneous
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

### Mailed Might of the Magelords

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **DESCRIPTOR:** Force
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Creature touched
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)
- **COST:** 250

### Nar Fiendbond

- **CLASSES:** Cleric,Sorcerer,Wizard=7
- **SCHOOL:** Transmutation
- **COMPS:** V, S, M/DF, XP
- **CASTTIME:** 1 hour
- **RANGE:** Touch
- **TARGETAREA:** One humanoid with Int 4 or higher
- **DURATION:** Instantaneous
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

### Nezram's Amethyst Aura

- **CLASSES:** Sorcerer,Wizard=3
- **SCHOOL:** Abjuration
- **COMPS:** V, S, M
- **CASTTIME:** 1 action
- **RANGE:** Touch
- **TARGETAREA:** Creature touched
- **DURATION:** (CASTERLEVEL * 10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

### Nezram's Emerald Energy Shield

- **CLASSES:** Sorcerer,Wizard=4
- **SCHOOL:** Abjuration
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Creature touched
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

### Nezram's Sapphire Screen of Shielding

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Abjuration
- **DESCRIPTOR:** Force
- **COMPS:** V, S, F
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** None
- **COST:** 250

### Ray of Resurgence

- **CLASSES:** Cleric=1|Sorcerer,Wizard=2
- **SCHOOL:** Evocation
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** One creature
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude negates (harmless)
- **SPELLRES:** Yes (harmless)

### Sakkratar's Triple Strike

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Transmutation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** (CASTERLEVEL) creatures, no two of which may be more than 30 ft. apart
- **DURATION:** 1 round
- **SAVEINFO:** Fortitude negates (harmless)
- **SPELLRES:** Yes (harmless)

### Sandblast

- **CLASSES:** Sorcerer,Wizard=6
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Earth
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** 60 ft.
- **TARGETAREA:** Cone-shaped burst
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude partial
- **SPELLRES:** Yes

### Shalantha's Delicate Disk

- **CLASSES:** Sorcerer,Wizard=6
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** One disk
- **DURATION:** Permanent until discharged [D]
- **SAVEINFO:** See text
- **SPELLRES:** See text
- **COST:** 200

### Srinshee's Spell Shift

- **CLASSES:** Sorcerer,Wizard=9
- **SCHOOL:** Abjuration
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** None

### Storm Shield

- **CLASSES:** Cleric,Druid=3
- **SCHOOL:** Abjuration
- **COMPS:** V, S, DF
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** 30-ft.-radius emanation
- **DURATION:** (CASTERLEVEL) minutes or until discharged [D]
- **SAVEINFO:** See text
- **SPELLRES:** See text

### Sun Scepter

- **CLASSES:** Cleric=6
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **DESCRIPTOR:** Lawful|Light
- **COMPS:** V, S, DF
- **CASTTIME:** 1 standard action
- **RANGE:** 0 ft.
- **TARGETAREA:** Scepter of light
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** No

### Theskyn's Hearty Heave

- **CLASSES:** Sorcerer,Wizard=2
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** 10 ft.
- **TARGETAREA:** (CASTERLEVEL/3) creatures
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

### Toothed Tentacle

- **CLASSES:** Sorcerer,Wizard=2
- **SCHOOL:** Evocation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** 30-ft.-long tentacle extending from your hand
- **DURATION:** Concentration, to a maximum of (CASTERLEVEL) rounds
- **SAVEINFO:** None
- **SPELLRES:** None

### Tyche's Touch

- **CLASSES:** Cleric=2
- **SCHOOL:** Abjuration
- **COMPS:** S, DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** One living creature
- **DURATION:** 24 hours or until discharged
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

## Spells Epic

### Ioulaum's Longevity

- **CLASSES:** Epic Spells (Arcane/CHA),Epic Spells (Arcane/INT),Epic Spells (Arcane/WIS),Epic Spells (Divine/CHA),Epic Spells (Divine/INT),Epic Spells (Divine/WIS)=10
- **SCHOOL:** Transmutation
- **COMPS:** V, S
- **CASTTIME:** 1 round
- **RANGE:** 12000 ft.
- **TARGETAREA:** 120-ft.-radius
- **DURATION:** Special
- **SAVEINFO:** Fortitude half
- **SPELLRES:** Yes
- **PREABILITY:** 1,CATEGORY=FEAT,Epic Spellcasting

See text. Spellcraft DC 152.

## Templates

### Greenbound Creature

- **DR:** 10/magic and slashing
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide (Forested Areas),Move Silently (Forested Areas)|16
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON,CHA|4
- **BONUS:** VAR|FastHealing|3
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **ABILITY:** Special Ability|AUTOMATIC|Fast Healing|Resistance To Cold|Resistance To Electricity
- **RACETYPE:** Plant
- **VISION:** Tremorsense (60')
- **SPELLS:** Innate|TIMES=ATWILL|Entangle|Pass Without Trace|Speak With Plants
- **SPELLS:** Innate|TIMES=1|Wall of Thorns

### Casting in Moonlight

- **PREABILITY:** 1,CATEGORY=FEAT,Cormanthyran Moon Magic
- **TEMPBONUS:** ANYPC|CASTERLEVEL|ALLSPELLS|2

Having mastered the ancient elven techniques of drawing power from Sehanine Moonbow's light all spells cast while standing in the moonlight have their effective caster level increased by 2.

### Battle Cursed (Netherese)

- **TEMPBONUS:** ANYPC|COMBAT|TOHIT|-2
- **TEMPBONUS:** ANYPC|COMBAT|DAMAGE.Bludgeon,DAMAGE.Piercing,DAMAGE.Slashing,DAMAGE.Unarmed|-2
- **TEMPBONUS:** ANYPC|SAVE|ALL|-2
- **TEMPBONUS:** ANYPC|SKILL|ALL|-2

You have been subjected to a battle curse causing you to suffer a -2 to attack rolls, damage rolls, saving throws, skill checks, and stat checks for 1 minute.

### Bhaalspawn


A member of a small army of mortal descendants of the dead god Bhaal, who now seek to claim the divine mantle that their progenitor once held.


# Faiths and Pantheons

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Ability Categories

### ABILITYCATEGORY:Elemental Archon Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Elemental Archon Class Features
- **DISPLAYLOCATION:** Class Features

## Class Abilities

### Elemental Transcendence


The Archon becomes an elemental.

### Mephit Underlings

- **ABILITY:** Internal|AUTOMATIC|Mephit Underlings (Base)
- **BONUS:** VAR|MephitUnderlingLVL|ElementalArchonLVL
- **COMPANIONLIST:** Mephit Underling|Mephit (Air),Mephit (Dust),Mephit (Ice)

Air Archons can call a triad of mephits to act as his servitors.

### Power of Arrogance


So strong is the Air Archon's belief in the supremacy of their chosen element that attack gain a +2 competence bonus and deal +2d6 additional damage against servants of the Earth subtype.

### Air Resilience

- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Electricity

Beginning at 3d level, and increasing at 6th and 9th, the Air Archon gains a resistance to electricity.

### Earth Resilience

- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Acid

Beginning at 3d level, and increasing at 6th and 9th, the Earth Archon gains a resistance to acid.

### Fire Resilience

- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Fire

Beginning at 3d level, and increasing at 6th and 9th, the Fire Archon gains a resistance to fire.

### Water Resilience

- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Cold

Beginning at 3d level, and increasing at 6th and 9th, the Water Archon gains a resistance to cold.

### Air Affinity

- **BONUS:** CASTERLEVEL|DESCRIPTOR.Air|1

Air Archon's gains a +1 caster level bonus with spells that have an Air, this bonus stacks with other abilities.

### Earth Affinity

- **BONUS:** CASTERLEVEL|DESCRIPTOR.Earth|1

Earth Archon's gains a +1 caster level bonus with spells that have an Earth, this bonus stacks with other abilities.

### Fire Affinity

- **BONUS:** CASTERLEVEL|DESCRIPTOR.Fire|1

Fire Archon's gains a +1 caster level bonus with spells that have an Fire, this bonus stacks with other abilities.

### Water Affinity

- **BONUS:** CASTERLEVEL|DESCRIPTOR.Water|1

Water Archon's gains a +1 caster level bonus with spells that have an Water, this bonus stacks with other abilities.

### Air Expertise


Air Archons gain a +1 circumstance bonus on attack and damage rolls against airborne creatures when the archon is airborne.

### Earth Expertise


Earth Archons gain a +1 circumstance bonus on attack and damage rolls if both they and their foe are touching the ground.

### Fire Expertise


Fire Archons gains a +1 circumstance bonus on attack and damage rolls if both they and their foe are within 20 feet of an open flame (touch-sized or larger).

### Water Expertise


Water Archons gain a +1 circumstance bonus on attack and damage rolls if both they and their foe are touching water.

### Mephit Underlings (Base)

- **DEFINE:** MephitUnderlingLVL|0
- **FOLLOWERS:** Mephit Underling|3

### Empathic Link

- **SORTKEY:** Class_master

An Elemental Archon has an empathic link with their underlings out to a distance of one mile. The archon cannot see through the underlings' eyes, but each underling can communicate with the archon telepathically.

### Improved Evasion

- **SORTKEY:** Class_master

If the underling is subjected to an attack that normally allows a Reflex save for half damage, it takes no damage on a successful save and only half damage on a failed save.

### Shared Saving Throws

- **SORTKEY:** Class_master

The underling uses its own base save or the Archon's whichever is better.

### Sycophantic Fawning

- **SORTKEY:** Class_master

Underlings of experienced Archons are pleased to serve such paragons of perfection and they're more than happy to tell their master about how much they appreciate the privilege. Once per day as a standard action, a mephit underling may extol the virtues of its master, granting the Archon a +1 morale bonus on attack, damage, saves, and skill checks. The efforts of multiple underlings stack, lasting 1 round per HD of the highest HD mephit engaged in the fawning.

### Improved Empathic Link

- **SORTKEY:** Class_master

The empathic link extends to 20 miles.

### Slavish Sacrifice

- **SORTKEY:** Class_master

The mephit underlings bond with its master is so great that it is willing to sacrifice itself for the Archon's wellbeing. Each morning, in a ceremony that takes 15 minutes, the Archon strengthens their link. For the entire day, the damage from a single attack that does damage enough that would bring the Archon below zero is transfer instantly to the nearest underling. Regardless of the amount of damage transferred the underling always dies, exploding in a sickening pop of elemental goo. An underling must be within 100 feet of the Archon for this to work.

## Classes

### CLASS:Elemental Archon

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|EArchon
- **MAXLEVEL:** 10

### SUBCLASS:Air Elemental Archon

- **PREDEITY:** 1,Akadi
- **PRELANG:** 1,Auran

### SUBCLASSLEVEL:1

- **BONUS:** VAR|ElementalArchonAir|1
- **BONUS:** VAR|ElectricityResistanceBonus|ElementalArchonResilience

### SUBCLASSLEVEL:2

- **ABILITY:** Elemental Archon Class Feature|AUTOMATIC|Elemental Archon ~ Air Power of Arrogance

### SUBCLASSLEVEL:3

- **ABILITY:** Elemental Archon Class Feature|AUTOMATIC|Elemental Archon ~ Air Resilience

### SUBCLASSLEVEL:4

- **ABILITY:** Elemental Archon Class Feature|AUTOMATIC|Elemental Archon ~ Air Affinity

### SUBCLASSLEVEL:7

- **ABILITY:** Elemental Archon Class Feature|AUTOMATIC|Elemental Archon ~ Air Elemental Expertise

### SUBCLASS:Earth Elemental Archon

- **PREDEITY:** 1,Grumbar
- **PRELANG:** 1,Terran

### SUBCLASS:Fire Elemental Archon

- **PREDEITY:** 1,Kossuth
- **PRELANG:** 1,Ignan

### SUBCLASS:Water Elemental Archon

- **PREDEITY:** 1,Istishi
- **PRELANG:** 1,Aquan
- **ADD:** CLASSSKILLS|1|Swim

### 1

- **BONUS:** VAR|ElementalArchonLVL|CL

### 10

- **ABILITY:** Elemental Archon Class Feature|AUTOMATIC|Elemental Archon ~ Elemental Transcendence

### 2

- **ADD:** SPELLCASTER|ANY

### 4

- **ADD:** SPELLCASTER|ANY

### 5

- **ADD:** SPELLCASTER|ANY

### 7

- **ADD:** SPELLCASTER|ANY

### 8

- **ADD:** SPELLCASTER|ANY

## Companion Modifiers

### FOLLOWER:MephitUnderlingLVL=1

- **ABILITY:** Special Ability|AUTOMATIC|Mephit Underling ~ Empathic Link

### FOLLOWER:MephitUnderlingLVL=3

- **HD:** 2
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1
- **ABILITY:** Special Ability|AUTOMATIC|Mephit Underling ~ Sycophantic Fawning

### FOLLOWER:MephitUnderlingLVL=6

- **HD:** 2
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1
- **ABILITY:** Special Ability|AUTOMATIC|Mephit Underling ~ Improved Empathic Link

### FOLLOWER:MephitUnderlingLVL=9

- **HD:** 2
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1
- **ABILITY:** Special Ability|AUTOMATIC|Mephit Underling ~ Slavish Sacrifice

## Templates

### Elemental Archon Transcendence

- **RACETYPE:** Elemental

### Sycophantically Inspired by Mephit Underlings

- **PRECLASS:** 1,Elemental Archon=3
- **TEMPVALUE:** MIN=1|MAX=3|TITLE=Number of Underlings Fawning
- **TEMPDESC:** One or more of your mephit underlings have inspirationally fawned over you
- **TEMPBONUS:** ANYPC|SAVE|ALL|%CHOICE
- **TEMPBONUS:** ANYPC|SKILL|ALL|%CHOICE
- **TEMPBONUS:** PC|COMBAT|TOHIT|%CHOICE
- **TEMPBONUS:** PC|COMBAT|DAMAGE.Melee,DAMAGE.Ranged|%CHOICE


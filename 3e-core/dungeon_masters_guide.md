# Dungeon Masters Guide

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Special Abilities

### First Level

- **TEMPLATE:** First Level

### Weapon and Armor Proficiency

- **ABILITY:** Internal|AUTOMATIC|TYPE=WeaponProfMartial

Adepts are skilled with all simple weapons. Adepts are not proficient with any type of armor nor with shields.

### Spells


An adept casts divine spells (the same type of spells available to the cleric, druid, paladin, and ranger), which are drawn from the adept spell list (see below). Like a cleric, an adept must choose and prepare her spells in advance. Unlike a cleric, an adept cannot spontaneously cast cure or inflict spells. to prepare or cast a spell, an adept must have a Wisdom score equal to at least 10 + the spell level (Wis 10 for 0-level spells, Wis 11 for 1st-level spells, and so forth). The Difficulty Class for a saving throw against an adept's spell is 10 + the spell level + the adept's Wisdom modifier. Adepts, unlike wizards, do not acquire their spells from books or scrolls, nor do they prepare them through study. Instead, they meditate or pray for their spells, receiving them as divine inspiration or through their own strength of faith. Each adept must choose a time each day at which she must spend an hour in quiet contemplation or supplication to regain her daily allotment of spells. Time spent resting has no effect on whether an adept can prepare spells. Like other spellcasters, an adept can cast only a certain number of spells of each spell level per day. Her base daily spell allotment is given on Table 4-2: The Adept. In addition, she receives bonus spells per day if she has a high Wisdom score (see Table 1-1: Ability Modifiers and Bonus Spells, page 8 of the Player's Handbook). When Table 4-2 indicates that the adept gets 0 spells per day of a given spell level (for instance, 0 2nd-level spells for a 4th-level adept), she gains only the bonus spells she would be entitled to based on her Wisdom score for that spell level. Each adept has a particular holy symbol (as a divine focus) depending on the adept's magical tradition.

### Summon Familiar

- **BONUS:** VAR|FamiliarLVL|AdeptLVL

At 2nd level, an adept can call a familiar, just as a sorcerer or wizard can. See the sidebar on page 52 of the Player's Handbook for more information.

### Single Simple Weapon Proficiency

- **MULT:** YES
- **CHOOSE:** WEAPONPROFICIENCY|!PC[TYPE=Simple]
- **AUTO:** WEAPONPROF|%LIST

You understand how to use %1|%LIST

### Expert Class Skills

- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** SKILL|TYPE=Standard
- **CSKILL:** LIST

### Enhance Arrow

- **DEFINE:** ArrowEnhancement|0
- **DEFINE:** ArrowEnhancementLVL|0
- **BONUS:** VAR|ArrowEnhancement|(ArrowEnhancementLVL+1)/2
- **BONUS:** VAR|ArrowEnhancementLVL|ArchaneArcherLVL
- **ASPECT:** NAME|Enhance Arrow +%1|ArrowEnhancementBonus

At 1st level, every nonmagical arrow an arcane archer nocks and lets fly becomes magical, gaining a +1 enhancement bonus. Unlike magic weapons created by normal means, the archer need not spend experience points or gold pieces to accomplish this task. However, an archer's magic arrows only function for her. For every two levels the character advances past 1st level in the prestige class, the magic arrows she creates gain +1 greater potency (+1 at 1st level, +2 at 3rd level, +3 at 5th level, +4 at 7th level, and +5 at 9th level).

### Imbue Arrow


At 2nd level, an arcane archer gains the ability to place an area spell upon an arrow. When the arrow is fired, the spell's area is centered on where the arrow lands, even if the spell could normally be centered only on the caster. This ability allows the archer to use the bow's range rather than the spell's range. It takes a standard action to cast the spell and fire the arrow. The arrow must be fired in the round the spell is cast, or the spell is wasted.

%1/day|SeekerArrowTimes

### Seeker Arrow

- **DEFINE:** SeekerArrowTimes|0
- **BONUS:** VAR|SeekerArrowTimes|1

At 4th level, an arcane archer can launch an arrow once per day at a target known to her within range, and the arrow travels to the target, even around corners. Only an unavoidable obstacle or the limit of the arrow's range prevents the arrow's flight. For example, if the target is within a windowless chamber with the door closed, the arrow cannot enter. This ability negates cover and concealment modifiers, but otherwise the attack is rolled normally. Using this ability is a standard action (and shooting the arrow is part of the action).

%1/day|SeekerArrowTimes

### Phase Arrow

- **DEFINE:** PhaseArrowTimes|0
- **BONUS:** VAR|PhaseArrowTimes|1

At 6th level, an arcane archer can launch an arrow once per day at a target known to her within range, and the arrow travels to the target in a straight path, passing through any nonmagical barrier or wall in its way. (A wall of force, a wall of fire, or the like stops the arrow.) This ability negates cover, concealment, and even armor modifiers, but otherwise the attack is rolled normally. Using this ability is a standard action (and shooting the arrow is part of the action).

%1/day|PhaseArrowTimes

### Hail of Arrows

- **DEFINE:** HailArrowsTargets|0
- **DEFINE:** HailArrowsTimes|0
- **BONUS:** VAR|HailArrowsTargets|ArchaneArcherLVL
- **BONUS:** VAR|HailArrowsTimes|1

In lieu of her regular attacks, once per day an arcane archer of 8th level or higher can fire an arrow at each and every target within range, to a maximum of one target for every arcane archer level she has earned. Each attack uses the archer's primary attack bonus, and each enemy may only be targeted by a single arrow.

%1 maximum targets %2/day|HailArrowsTargets|HailArrowsTimes

### Arrow of Death


At 10th level, an arcane archer can create an arrow of death that forces the target, if damaged by the arrow's attack, to make a DC 20 Fortitude save or be slain immediately. It takes one day to make an arrow of death, and the arrow only functions for the arcane archer who created it. The arrow of death lasts no longer than one year, and the archer can only have one such arrow in existence at a time.

### Spells per Day


When a new arcane trickster level is gained, the character gains new spells per day as if he had also gained a level in a spellcasting class he belonged to before adding the prestige class. He does not, however, gain any other benefit a character of that class would have gained (improved chance of controlling or rebuking undead, metamagic or item creation feats, and so on), except for an increased effective level of spellcasting. If a character had more than one spellcasting class before becoming an arcane trickster, he must decide to which class he adds the new level for purposes of determining spells per day.

### Ranged Legerdemain

- **DEFINE:** RangedLegerdemainTimes|0
- **BONUS:** VAR|RangedLegermainTimes|(ArcaneTricksterLVL+3)/4
- **ASPECT:** NAME|Ranged Legerdemain %1/day|RangedLegermainTimes

Using his unique talents, an arcane trickster can perform one of the following class skills at a range of 30 feet: Disable Device, Open Lock, or Sleight of Hand. Working at a distance increases the normal skill check DC by 5, and an arcane trickster cannot take 10 on this check. Any object to be manipulated must weigh 5 pounds or less. An arcane trickster can use ranged legerdemain once per day initially, twice per day upon attaining 5th level, and three times per day at 9th level or higher. He can make only one ranged legerdemain skill check each day, and only if he has at least 1 rank in the skill being used.

[Times per day %1]|RangedLegerdemainTimes

### Sneak Attack

- **DEFINE:** SneakAttackDice|0
- **DEFINE:** SneakAttackDieSize|0
- **ABILITY:** Special Ability|AUTOMATIC|Sneak Attack
- **BONUS:** VAR|SneakAttackDieSize|6|TYPE=Base
- **BONUS:** VAR|SneakAttackDice|ArcaneTricksterLVL/2

This is exactly like the rogue ability of the same name. The extra damage dealt increases by +1d6 every other level (2nd, 4th, 6th, 8th, and 10th). If an arcane trickster gets a sneak attack bonus from another source (such as rogue levels), the bonuses on damage stack.

[Sneak Attack Damage %1d%2]|SneakAttackDice|SneakAttackDieSize

### Impromptu Sneak Attack

- **DEFINE:** ImpromptuSneakAttackTimes|0
- **DEFINE:** ImpromptuSneakAttackTimes|0
- **BONUS:** VAR|ImpromptuSneakAttackTimes|(ArcaneTricksterLVL+1)/4
- **ASPECT:** NAME|Impromptu Sneak Attack %1/day|ImpromptuSneakAttackTimes

Beginning at 3rd level, once per day an arcane trickster can declare one melee or ranged attack he makes to be a sneak attack (the target can be no more than 30 feet distant if the impromptu sneak attack is a ranged attack). The target of an impromptu sneak attack loses any Dexterity bonus to AC, but only against that attack. The power can be used against any target, but creatures that are not subject to critical hits take no extra damage (though they still lose any Dexterity bonus to AC against the attack). At 7th level, an arcane trickster can use this ability twice per day.

### Spells per Day/Spells Known


When a new archmage level is gained, the character gains new spells per day (and spells known, if applicable) as if he had also gained a level in whatever arcane spellcasting class in which he could cast 7th-level spells before he added the prestige class level. He does not, however, gain any other benefit a character of that class would have gained (bonus metamagic or item creation feats, and so on). If a character had more than one arcane spellcasting class in which he could cast 7th-level spells before he became an archmage, he must decide to which class he adds each level of archmage for the purpose of determining spells per day.

### High Arcana

- **BONUS:** ABILITYPOOL|High Arcana Ability|ArchmageLVL

An archmage learns secret lore unknown to lesser wizards and sorcerers. She gains the opportunity to select a special ability from among those described below by permanently eliminating one existing spell slot (she cannot eliminate a spell slot of higher level than the highest-level spell she can cast). Each special ability has a minimum required spell slot level, as specified in its description. For example, a 15thlevel wizard normally can cast two 7th-level spells per day (bonus spells for specialization or high Intelligence can increase this number). A 13th-level wizard/2nd-level archmage who chooses the arcane reach ability forfeits one 7th-level spell slot, and so can only cast one 7th-level spell per day, not counting bonus spells.

### Arcane Fire

- **PRECLASS:** 1,Archmage=1
- **PRESPELLTYPE:** 1,Arcane=9
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=9|-1

The archmage gains the ability to change arcane spell energy into arcane fire, manifesting it as a bolt of raw magical energy. The bolt is a ranged touch attack with long range (400 feet + 40 feet/level of archmage) that deals 1d6 points of damage per class level of the archmage plus 1d6 points of damage per level of the spell used to create the effect. For instance, a 5thlevel archmage who channels a 7th-level spell into arcane fire deals 12d6 points of damage to the target if it hits. This ability costs one 9th-level spell slot.

### Arcane Reach

- **PRECLASS:** 1,Archmage=1
- **PRESPELLTYPE:** 1,Arcane=7
- **DEFINE:** ArcaneReach|0
- **MULT:** YES
- **CHOOSE:** NUMCHOICES=2|CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=7|-1
- **BONUS:** VAR|ArcaneReach|30*count("ABILITIES","CATEGORY=Special Ability","NAME=Arcane Reach")|TYPE=ArcaneReach

The archmage can use spells with a range of touch on a target up to 30 feet away. The archmage must make a ranged touch attack. Arcane reach can be selected a second time as a special ability, in which case the range increases to 60 feet. This ability costs one 7th-level spell slot.

### Mastery of Counterspelling

- **PRECLASS:** 1,Archmage=1
- **PRESPELLTYPE:** 1,Arcane=7
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=7|-1

When the archmage counterspells a spell, it is turned back upon the caster as if it were fully affected by a spell turning spell. If the spell cannot be affected by spell turning (for example, if it is a spell that affects an area), then it is merely counterspelled. This ability costs one 7thlevel spell slot.

### Mastery of Elements

- **PRECLASS:** 1,Archmage=1
- **PRESPELLTYPE:** 1,Arcane=8
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=8|-1

The archmage can alter an arcane spell when cast so that it utilizes a different element from the one it normally uses. For example, an archmage could cast a fireball that deals sonic damage instead of fire damage. This ability can only alter a spell with the acid, cold, fire, electricity, or sonic descriptor. The spell's casting time is unaffected. The caster decides whether to alter the spell's energy type and chooses the new energy type when he begins casting. This ability costs one 8th-level spell slot.

### Mastery of Shaping

- **PRECLASS:** 1,Archmage=1
- **PRESPELLTYPE:** 1,Arcane=6
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=6|-1

The archmage can alter area and effect spells that use one of the following shapes: burst, cone, cylinder, emanation, or spread. The alteration consists of creating spaces within the spell's area or effect that are not subject to the spell. The minimum dimension for these spaces is a 5-foot cube. For example, an archmage could cast a fireball and leave a hole where his ally stands, preventing any fire damage. Furthermore, any shapeable spells have a minimum dimension of 5 feet instead of 10 feet. This ability costs one 6thlevel spell slot.

### Spell Power

- **PRECLASS:** 1,Archmage=1
- **PRESPELLTYPE:** 1,Arcane=5
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=5|-1

This ability increases the archmage's effective caster level by +1 (for purposes of determining level-dependent spell variables such as damage dice or range, and caster level checks only). This ability costs one 5th-level spell slot.

### Spell-Like Ability

- **PRECLASS:** 1,Archmage=1
- **PRESPELLTYPE:** 1,Arcane=5
- **DEFINE:** ArchmageSLA|0
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** SPELLS|SPELLTYPE=Arcane[KNOWN=YES]
- **BONUS:** ABILITYPOOL|Spell-Like Ability Selection|1
- **BONUS:** VAR|ArchmageSLA|1

An archmage who selects this type of high arcana can use one of her arcane spell slots (other than a slot expended to learn this or any other type of high arcana) to permanently prepare one of her arcane spells as a spell-like ability that can be used twice per day. The archmage does not use any components when casting the spell, although a spell that costs XP to cast still does so and a spell with a costly material component instead costs her 10 times that amount in XP. This ability costs one 5th-level spell slot. The spell-like ability normally uses a spell slot of the spell's level, although the archmage can choose to make a spell modified by a metamagic feat into a spell-like ability at the appropriate spell level. For example, an archmage can make lightning bolt into a spell-like ability by using a 3rd-level spell slot to do so, or into a maximized lightning bolt by using a 6th-level spell slot. The archmage may use an available higher-level spell slot in order to use the spell-like ability more often. Using a slot three levels higher than the chosen spell allows her to use the spelllike ability four times per day, and a slot six levels higher lets her use it six times per day. If spell-like ability is selected more than one time as a high arcana choice, this ability can apply to the same spell chosen the first time (increasing the number of times per day it can be used) or to a different spell.

### Spell-Like Ability Class Choice

- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=5|-1

### Death Attack

- **DEFINE:** DeathAttackDC|0
- **DEFINE:** DeathAttackDC|0
- **BONUS:** VAR|DeathAttackDC|min(AssassinLVL,10)+max((10-AssassinLVL)/2,0)
- **BONUS:** VAR|DeathAttackDC|10|TYPE=Base
- **BONUS:** VAR|DeathAttackDC|INT|TYPE=Stat

If an assassin studies his victim for 3 rounds and then makes a sneak attack with a melee weapon that successfully deals damage, the sneak attack has the additional effect of possibly either paralyzing or killing the target (assassin's choice). While studying the victim, the assassin can undertake other actions so long as his attention stays focused on the target and the target does not detect the assassin or recognize the assassin as an enemy. If the victim of such an attack fails a Fortitude save (DC 10 + the assassin's class level + the assassin's Int modifier) against the kill effect, she dies. If the saving throw fails against the paralysis effect, the victim's mind and body become enervated, rendering her helpless and unable to act for 1d6 rounds plus 1 round per level of the assassin. If the victim's saving throw succeeds, the attack is just a normal sneak attack. Once the assassin has completed the 3 rounds of study, he must make the death attack within the next 3 rounds. If a death attack is attempted and fails (the victim makes her save) or if the assassin does not launch the attack within 3 rounds of completing the study, 3 new rounds of study are required before he can attempt another death attack.

Death Attack DC: %1|DeathAttackDC

### Poison Use


Assassins are trained in the use of poison and never risk accidentally poisoning themselves when applying poison to a blade.

### Save Bonus against Poison

- **DEFINE:** AssassinPoisonSaveBonus|0
- **DEFINE:** AssassinPoisonSaveBonus|0
- **BONUS:** VAR|AssassinPoisonSaveBonus|AssassinLVL/2
- **ASPECT:** SaveBonus|+%1 to saving throws vs. Poison|AssassinPoisonSaveBonus
- **ASPECT:** NAME|+%1 Save against Poison|AssassinPoisonSaveBonus

Assassins train with poisons of all types and slowly grow more and more resistant to their effects. This is reflected by a natural saving throw bonus to all poisons gained at 2nd level that increases by +1 for every two additional levels the assassin gains (+2 at 4th level, +3 at 6th level, and so on).

Poison Save Bonus +%1|AssassinPoisonSaveBonus

### Uncanny Dodge

- **BONUS:** VAR|UncannyDodgeFlankingLevel|AssassinLVL|TYPE=EachClass.REPLACE

Starting at 2nd level, an assassin gains the ability to react to danger before his senses would normally allow him to even be aware of it. He retains his Dexterity bonus to AC (if any) regardless of being caught flat-footed or struck by an invisible attacker. (He still loses any Dexterity bonus to AC if immobilized.) If a character gains uncanny dodge from a second class (such as a barbarian/rogue), the character automatically gains improved uncanny dodge (see below).

### Improved Uncanny Dodge


At 5th level, an assassin can no longer be flanked, since he can react to opponents on opposite sides of him as easily as he can react to a single attacker. This defense denies rogues the ability to use flank attacks to sneak attack the assassin. The exception to this defense is that a rogue at least four levels higher than the assassin can flank him (and thus sneak attack him). If a character gains uncanny dodge (see above) from a second class (such as a barbarian/rogue), the character automatically gains improved uncanny dodge, and the levels from those classes stack to determine the minimum rogue level required to flank the character.

### Hide in Plain Sight


At 8th level, an assassin can use the Hide skill even while being observed. As long as he is within 10 feet of some sort of shadow, an assassin can hide himself from view in the open without having anything to actually hide behind. He cannot, however, hide in his own shadow.

### Aura of Evil

- **DEFINE:** AuraEvilLVL|0
- **BONUS:** VAR|AuraEvilLVL|BlackguardLVL

The power of a blackguard's aura of evil (see the detect evil spell) is equal to his class level plus his cleric level, if any.

### Detect Good


At will, a blackguard can use detect good as a spell-like ability, duplicating the effect of the detect good spell.

### Dark Blessing

- **BONUS:** SAVE|ALL|max(CHA,0)

A blackguard applies his Charisma modifier (if positive) as a bonus on all saving throws.

### Smite Good

- **DEFINE:** SmiteGoodTimes|0
- **DEFINE:** SmiteGoodDamage|0
- **BONUS:** VAR|SmiteGoodTimes|BlackguardLVL/5+1
- **BONUS:** VAR|SmiteGoodTimes|var("CL=Ex Paladin")/4+1
- **BONUS:** VAR|SmiteGoodDamage|BlackguardLVL+var("CL=Ex Paladin")

Once a day, a blackguard of 2nd level or higher may attempt to smite good with one normal melee attack. He adds his Charisma modifier (if positive) to his attack roll and deals 1 extra point of damage per class level. For example, a 9th-level blackguard armed with a longsword would deal 1d8+9 points of damage, plus any additional bonuses from high Strength or magical effects that normally apply. If a blackguard accidentally smites a creature that is not good, the smite has no effect but it is still used up for that day. At 5th level, and again at 10th level, a blackguard may smite good one additional time per day.

### Aura of Despair


Beginning at 3rd level, the blackguard radiates a malign aura that causes enemies within 10 feet of him to take a -2 penalty on all saving throws.

### Command Undead

- **DEFINE:** TurnLevelBase|0
- **DEFINE:** TurnDamagePlusBase|0
- **ABILITY:** Special Ability|AUTOMATIC|Basic Turning
- **BONUS:** VAR|TurnLevelBase|BlackguardLVL-2
- **BONUS:** VAR|TurnDamagePlusBase|BlackguardLVL-2

When a blackguard reaches 3rd level, he gains the supernatural ability to command and rebuke undead (see the Player's Handbook, page 159). He commands undead as would a cleric of two levels lower.

### Fiendish Servant

- **DEFINE:** FiendishServantLVL|0
- **BONUS:** VAR|FiendishServantLVL|BlackguardLVL

Upon or after reaching 5th level, a blackguard can call a fiendish bat, cat, dire rat, horse, pony, raven, or toad to serve him. (See the Monster Manual for these creatures' basic statistics.) This creature may be used as a guardian (such as a bat), a helper (such as a cat), or a mount (such as a horse). The blackguard's servant further gains HD and special abilities based on the blackguard's character level (see the table). A blackguard may have only one fiendish servant at a time. Should the blackguard's servant die, he may call for another one after a year and a day. The new fiendish servant has all the accumulated abilities due a servant of the blackguard's current level.

### Lay on Hands

- **DEFINE:** BlackguardLayOnHandsTotal|0
- **BONUS:** VAR|BlackguardLayOnHandsTotal|max(CHA,0)*BlackguardLVL

### Fiendish Summoning


Once per day, the blackguard can use a summon monster I spell to call forth an evil creature. For this spell, the caster level is double the blackguard's class level.

### Undead Companion

- **DEFINE:** UndeadCompanionLVL|0
- **BONUS:** VAR|UndeadCompanionLVL|CL

In addition to the fiendish servant, the blackguard gains (at 5th level) a Medium-size skeleton or zombie as a companion. This companion cannot be turned or rebuked and gains all special bonuses as a fiendish servant when the blackguard gains levels.

### Empathic Link


The blackguard has an empathic link with his servant out to a distance of up to 1 mile. The blackguard cannot see through the servant's eyes, but they can communicate empathically. Because of the limited nature of the link, only general emotional content (such as fear, hunger, happiness, curiosity) can be communicated. Note that the low Intelligence of a lowlevel blackguard's fiendish servant limits what the creature is able to communicate or understand, and even intelligent servants see the world differently from humans, so misunderstandings are always possible Because of the empathic link between the servant and the blackguard, the blackguard has the same connection to a place or an item that the servant does.

### Improved Evasion


If the servant is subjected to an attack that normally allows a Reflex saving throw for half damage, it takes no damage on a successful saving throw and only half damage on a failed saving throw. Improved evasion is an extraordinary ability.

### Share Saving Throws


For each of its saving throws, the servant uses either its own base save bonus or the blackguard's, whichever is higher. The servant applies its own ability modifiers to saves, and it doesn't share any other bonuses on saves that the blackguard might have (such as from magic items or feats).

### Share Spells


At the blackguard's option, he may have any spell (but not any spell-like ability) he casts on himself also affect his servant. The servant must be within 5 feet at the time of casting to receive the benefit. If the spell has a duration other than instantaneous, it stops affecting the servant if it moves farther than 5 feet away and will not affect the servant again even if the servant returns to the blackguard before the duration expires. Additionally, the blackguard may cast a spell with a target of "You" on his servant (as a touch range spell) instead of on himself. A blackguard and his servant can share spells even if the spells normally do not affect creatures of the servant's type (magical beast).

### Speak with Blackguard


If the blackguard's character level is 13th or higher, the blackguard and servant can communicate verbally as if they were using a common language. Other creatures do not understand the communication without magical help.

### Blood Bond


If the blackguard's character level is 16th or higher, the servant gains a +2 bonus on all attack rolls, checks, and saves if it witnesses the blackguard being threatened or harmed. This bonus lasts as long as the threat is immediate and apparent.

### Spell Resistance


If the blackguard's character level is 19th or higher, the servant gains spell resistance equal to the blackguard's level + 5. To affect the servant with a spell, another spellcaster must get a result on a caster level check (1d20 + caster level) that equals or exceeds the servant's spell resistance.

### Cannot be Turned or Rebuked


This companion cannot be turned or rebuked.

### Bonus Spells

- **DEFINE:** DragonDiscipleBonusSpellCount|0
- **BONUS:** ABILITYPOOL|Dragon Disciple Bonus Spell|DragonDiscipleBonusSpellCount
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1
- **BONUS:** VAR|DragonDiscipleBonusSpellCount|1

Dragon disciples gain bonus spells as they gain levels in this prestige class, as if from having a high ability score, as given on Table 6-7. A bonus spell can be added to any level of spells the disciple already has the ability to cast. If a character has more than one spellcasting class, he must decide to which class he adds each bonus spell as it is gained. Once a bonus spell has been applied, it cannot be shifted.

### Natural Armor Increase

- **DEFINE:** DragonDiscipleACBonus|0
- **BONUS:** COMBAT|AC|DragonDiscipleACBonus|TYPE=NaturalArmor.STACK
- **BONUS:** VAR|DragonDiscipleACBonus|(DragonDiscipleLVL+2)/3

At 1st, 4th, and 7th level, a dragon disciple becomes more draconic in appearance. His skin develops tiny iridescent scales, nearly invisible at first but becoming more noticeable at higher levels. This provides an increase to the character's existing natural armor (if any), as indicated on Table 6-7 (the numbers represent the total increase gained to that point). As his skin thickens, a dragon disciple takes on more and more of his progenitor's physical aspect.

### Claws and Bite

- **TEMPLATE:** Dragon Disciple Attacks

At 2nd level, a dragon disciple gains claw and bite attacks if he does not already have them. Use the values above or the disciple's base claw and bite damage values, whichever are greater. A dragon disciple is considered proficient with these attacks. When making a full attack, a dragon disciple uses his full base attack bonus with his bite attack but takes a -5 penalty on claw attacks. The Multiattack feat (see page 304 of the Monster Manual) reduces this penalty to only -2.

### Ability Boost

- **BONUS:** STAT|STR|2
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CHA|2

As a dragon disciple gains levels in this prestige class, his ability scores increase as noted on Table 6-7. These increases stack and are gained as if through level advancement.

### Breath Weapon


At 3rd level, a dragon disciple gains a minor breath weapon, derived from his draconic ancestor. The type and shape depend on the dragon variety whose heritage he enjoys (see below). Regardless of the ancestor, the breath weapon deals 2d8 points of damage of the appropriate energy type. At 7th level, the damage increases to 4d8, and when a disciple attains dragon apotheosis at 10th level it reaches its full power at 6d8. Regardless of its strength, the breath weapon can be used only once per day. Use all the rules for dragon breath weapons (see page 69 of the Monster Manual) except as specified here. The DC of the breath weapon is 10 + class level + Con modifier. A line-shaped breath weapon is 5 feet high, 5 feet wide, and 60 feet long. A cone-shaped breath weapon is 30 feet long.

### Blindsense

- **BONUS:** VAR|BlindsenseRange|30|TYPE=Base
- **BONUS:** VAR|BlindsenseRange|60|TYPE=Base

At 5th level, the dragon disciple gains blindsense with a range of 30 feet. Using nonvisual senses, such as acute smell or hearing, the dragon disciple notices things it cannot see. He usually does not need to make Spot or Listen checks to notice and pinpoint the location of creatures within range of his blindsense ability, provided that he has line of effect to that creature. Any opponent the dragon disciple cannot see still has total concealment against him, and the dragon disciple still has the normal miss chance when attacking foes that have concealment. Visibility still affects the movement of a creature with blindsense. A creature with blindsense is still denied its Dexterity bonus to Armor Class against attacks from creatures it cannot see. At 10th level, the range of this ability increases to 60 feet.

### Wings

- **MOVECLONE:** Walk,Fly,*1

At 9th level, a dragon disciple grows a set of draconic wings. He may now fly at a speed equal to his normal land speed, with average maneuverability.

### Dragon Apotheosis

- **ABILITY:** Special Ability|AUTOMATIC|Immunity To Paralysis|Immunity To Sleep
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1

At 10th level, a dragon disciple fully realizes his draconic heritage and takes on the half-dragon template (see page 146 of the Monster Manual). His breath weapon reaches full strength (as noted above), and he gains +4 to Strength and +2 to Charisma. His natural armor bonus increases to +4, and he acquires low-light vision, 60-foot darkvision, immunity to sleep and paralysis effects, and immunity to the energy type used by his breath weapon (see above).

### Bonus Spell Slot 1

- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER],TYPE=Arcane
- **BONUS:** SPELLCAST|TYPE=Arcane;LEVEL=1|1

### Bonus Spell Slot 2

- **PREABILITY:** 1,CATEGORY=Special Ability,Bonus Spell Slot 1
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER],TYPE=Arcane
- **BONUS:** SPELLCAST|TYPE=Arcane;LEVEL=2|1

### Bonus Spell Slot 3

- **PREABILITY:** 1,CATEGORY=Special Ability,Bonus Spell Slot 2
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER],TYPE=Arcane
- **BONUS:** SPELLCAST|TYPE=Arcane;LEVEL=3|1

### Bonus Spell Slot 4

- **PREABILITY:** 1,CATEGORY=Special Ability,Bonus Spell Slot 3
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER],TYPE=Arcane
- **BONUS:** SPELLCAST|TYPE=Arcane;LEVEL=4|1

### Bonus Spell Slot 5

- **PREABILITY:** 1,CATEGORY=Special Ability,Bonus Spell Slot 4
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER],TYPE=Arcane
- **BONUS:** SPELLCAST|TYPE=Arcane;LEVEL=5|1

### Bonus Spell Slot 6

- **PREABILITY:** 1,CATEGORY=Special Ability,Bonus Spell Slot 5
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER],TYPE=Arcane
- **BONUS:** SPELLCAST|TYPE=Arcane;LEVEL=6|1

### Bonus Spell Slot 7

- **PREABILITY:** 1,CATEGORY=Special Ability,Bonus Spell Slot 6
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER],TYPE=Arcane
- **BONUS:** SPELLCAST|TYPE=Arcane;LEVEL=7|1

### Dragon Disciple Breath Weapon ~ Line of Acid


### Dragon Disciple Breath Weapon ~ Line of Lightning


### Dragon Disciple Breath Weapon ~ Line of Fire


### Dragon Disciple Breath Weapon ~ Cone of Gas


### Dragon Disciple Breath Weapon ~ Cone of Fire


### Dragon Disciple Breath Weapon ~ Cone of Cold


### Canny Defense

- **DEFINE:** CannyDefenseLVL|0
- **BONUS:** COMBAT|AC|max(0,min(INT,CannyDefenseLVL))|TYPE=Ability.STACK
- **BONUS:** VAR|CannyDefenseLVL|DuelistLVL

When not wearing armor or using a shield, a duelist adds 1 point of Intelligence bonus (if any) per duelist class level to her Dexterity bonus to modify Armor Class while wielding a melee weapon. For instance, a 2nd-level duelist with an Intelligence score of 16 (+3 bonus) can add +2 to her Armor Class. If a duelist is caught flat-footed or otherwise denied her Dexterity bonus, she also loses this bonus.

### Improved Reaction

- **DEFINE:** ImprovedReactionBonus|0
- **BONUS:** COMBAT|INITIATIVE|ImprovedReactionBonus
- **BONUS:** VAR|ImprovedReactionBonus|floor((DuelistLVL+4)/6)*2
- **ASPECT:** Ability Benefit|+%1|ImprovedReactionBonus

At 2nd level, a duelist gains a +2 bonus on initiative checks. At 8th level, the bonus increases to +4. This bonus stacks with the benefit provided by the Improved Initiative feat.

+%1|ImprovedReactionBonus

### Enhanced Mobility


When wearing no armor and not using a shield, a duelist gains an additional +4 bonus to AC against attacks of opportunity caused when she moves out of a threatened square.

### Grace


At 4th level, a duelist gains an additional +2 competence bonus on all Reflex saving throws. This ability functions for a duelist only when she is wearing no armor and not using a shield.

### Precise Strike

- **DEFINE:** PreciseStrikeDice|0
- **DEFINE:** PreciseStrikeDieSize|0
- **BONUS:** VAR|PreciseStrikeDieSize|6|TYPE=Base
- **BONUS:** VAR|PreciseStrikeDice|DuelistLVL/5
- **ASPECT:** Ability Benefit|+%1d%2|PreciseStrikeDice|PreciseStrikeDieSize

At 5th level, a duelist gains the ability to strike precisely with a light or one-handed piercing weapon, gaining an extra 1d6 damage added to her normal damage roll. When making a precise strike, a duelist cannot attack with a weapon in her other hand or use a shield. A duelist's precise strike only works against living creatures with discernible anatomies. Any creature that is immune to critical hits (including undead, constructs, oozes, plants, and incorporeal creatures) is not vulnerable to a precise strike, and any item or ability that protects a creature from critical hits (such as armor with the fortification special ability) also protects a creature from a precise strike. At 10th level, the extra damage on a precise strike increases to +2d6.

+%1d%2|PreciseStrikeDice|PreciseStrikeDieSize

### Acrobatic Charge


At 6th level, a duelist gains the ability to charge in situations where others cannot. She may charge over difficult terrain that normally slows movement. This enables her to run down steep stairs, leap down from a balcony, or to tumble over tables to get to her charge target. Depending on the circumstance, she may still need to make appropriate checks (Jump or Tumble checks in particular) to successfully move over the terrain.

### Elaborate Parry

- **DEFINE:** ElaborateParryLVL|0
- **BONUS:** VAR|ElaborateParryLVL|DuelistLVL
- **BONUS:** VAR|FightingDefensivelyACBonus,TotalDefenseACBonus|ElaborateParryLVL

At 7th level and higher, if a duelist chooses to fight defensively or use total defense in melee combat, she gains an additional +1 dodge bonus to AC for each level of duelist she has.

### Deflect Arrows

- **ABILITY:** FEAT|VIRTUAL|Deflect Arrows

At 9th level, a duelist gains the benefit of the Deflect Arrows feat (see page 93 of the Player's Handbook) when using a light or onehanded piercing weapon.

### AC Bonus

- **DEFINE:** DwarvenDefenderACBonus|0
- **BONUS:** COMBAT|AC|DwarvenDefenderACBonus|TYPE=Dodge
- **BONUS:** VAR|DwarvenDefenderACBonus|(DwarvenDefenderLVL+2)/3

The dwarven defender receives a dodge bonus to Armor Class that starts at +1 and improves as the defender gains levels, until it reaches +4 at 10th level.

### Defensive Stance

- **DEFINE:** DefensiveStanceTimes|0
- **DEFINE:** DefensiveStanceDuration|0
- **BONUS:** VAR|DefensiveStanceDuration|CON
- **BONUS:** VAR|DefensiveStanceTimes|(DwarvenDefenderLVL+1)/2
- **BONUS:** VAR|DefensiveStanceDuration|5
- **TEMPBONUS:** PC|SAVE|ALL|2|TYPE=Resistance
- **TEMPBONUS:** PC|COMBAT|AC|4|TYPE=Dodge
- **TEMPBONUS:** PC|STAT|STR|2
- **TEMPBONUS:** PC|STAT|CON|4
- **TEMPBONUS:** PC|VAR|DefensiveStanceDuration|-2

When he needs to, a defender can become a stalwart bastion of defense. In this defensive stance, a defender gains phenomenal strength and durability, but he cannot move from the spot he is defending. He gains +2 to Strength, +4 to Constitution, a +2 resistance bonus on all saves, and a +4 dodge bonus to AC. The increase in Constitution increases the defender's hit points by 2 points per level, but these hit points go away at the end of the defensive stance when the Constitution score drops back 4 points. These extra hit points are not lost first the way temporary hit points are. While in a defensive stance, a defender cannot use skills or abilities that would require him to shift his position, such as Move Silently or Jump. A defensive stance lasts for a number of rounds equal to 3 + the character's (newly improved) Constitution modifier. A defender may end his defensive stance voluntarily prior to this limit. At the end of the defensive stance, the defender is winded and takes a -2 penalty to Strength for the duration of that encounter. A defender can only use his defensive stance a certain number of times per day as determined by his level (see Table 6-9). Using the defensive stance takes no time itself, but a defender can only do so during his action. (A defender can't, for example, use the stance when struck down by an arrow in order to get the extra hit points from the increased Constitution.)

%1 times/day (%2 rounds)|DefensiveStanceTimes|DefensiveStanceDuration

### Trap Sense

- **ABILITY:** Special Ability|AUTOMATIC|Trap Sense
- **BONUS:** VAR|TrapSenseBonus|DwarvenDefenderLVL/4

At 4th level, a dwarven defender gains an intuitive sense that alerts him to danger from traps, giving him a +1 bonus on Reflex saves made to avoid traps and a +1 dodge bonus to AC against attacks by traps. At 8th level, these bonuses rise to +2. These bonuses stack with trap sense bonuses gained from other classes.

### Damage Reduction

- **DEFINE:** DwarvenDefenderDRLVL|0
- **DEFINE:** DwarvenDefenderDR|0
- **BONUS:** VAR|DwarvenDefenderDR|3*floor(((DwarvenDefenderDRLVL-2)/4))
- **BONUS:** VAR|DwarvenDefenderDRLVL|DwarvenDefenderLVL
- **DR:** DwarvenDefenderDR/-

At 6th level, a dwarven defender gains the ability to shrug off some amount of injury from each blow or attack. Subtract 3 points from the damage the dwarven defender takes each time he is dealt damage. At 10th level, this damage reduction rises to 6/-. Damage reduction can reduce damage to 0 but not below 0. (That is, the defender cannot actually gain hit points in this manner.)

### Mobile Defense


At 8th level, a dwarven defender can adjust his position while maintaining a defensive stance. While in a defensive stance, he can take one 5-foot step each round without losing the benefit of the stance.

### Bonus Feat

- **BONUS:** ABILITYPOOL|Fighter Feat|1

At 1st level, an eldritch knight may choose a bonus feat from the list of feats available to fighters. This is in addition to the feats that a character of any class normally gets every three levels. The character must still meet any prerequisites for these bonus feats, including four levels of fighter for the Weapon Specialization feat.

### Spells and Caster Level

- **BONUS:** CASTERLEVEL|TYPE.Divine|HierophantLVL

Levels in the hierophant prestige class, even though they do not advance spell progression in the character's base class, still stack with the character's base spellcasting levels to determine caster level.

### Special Ability

- **BONUS:** ABILITYPOOL|Hierophant Ability|HierophantLVL

Every level, a hierophant gains a special ability of his choice from among the following.

### Blast Infidel

- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ LG
- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ LN
- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ LE
- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ NG
- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ NE
- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ CG
- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ CN
- **ABILITY:** Internal|AUTOMATIC|Hierophant Align ~ CE
- **BONUS:** ABILITYPOOL|Hierophant Align|1
- **ASPECT:** NAME|Blast Infidel (Lawful Good)
- **ASPECT:** NAME|Blast Infidel (Lawful Neutral)
- **ASPECT:** NAME|Blast Infidel (Lawful Evil)
- **ASPECT:** NAME|Blast Infidel (Neutral Good)
- **ASPECT:** NAME|Blast Infidel (Neutral Evil)
- **ASPECT:** NAME|Blast Infidel (Chaotic Good)
- **ASPECT:** NAME|Blast Infidel (Chaotic Neutral)
- **ASPECT:** NAME|Blast Infidel (Chaotic Evil)

A hierophant can use negative energy spells to their maximum effect on creatures with an alignment opposed to the hierophant. (See the table below for a list of which alignments are opposed to each alignment.) Any spell with a description that involves inflicting or channeling negative energy (inflict spells, mass inflict light wounds, harm) cast on a creature of the opposed alignment works as if under the effect of a Maximize Spell feat (without using a higher-level spell slot). Undead affected by this ability heal the maximized amount of damage.

### Divine Reach


A hierophant with this ability can use touch spells on targets up to 30 feet away. If the spell requires a melee touch attack, the hierophant must make a ranged touch attack instead. Divine reach can be selected a second time as a special ability, in which case the range increases to 60 feet.

### Faith Healing


A hierophant can use healing spells to their maximum effect on creatures of the same alignment as the hierophant (including the hierophant himself ). Any spell with the healing descriptor cast on such creatures works as if under the effects of a Maximize Spell feat (without using a higher-level spell slot).

### Gift of the Divine


Available only to hierophants with cleric levels, this ability allows a hierophant to transfer one or more uses of his turn undead ability to a willing creature. (Hierophants who rebuke undead transfer uses of rebuke undead instead.) The transfer lasts anywhere from 24 hours to one week (chosen at the time of transfer), and while the transfer is in effect, the number of turning attempts per day allowed to the hierophant is reduced by the number transferred. The recipient turns undead as a cleric of the hierophant's cleric level but uses her own Charisma modifier.

### Mastery of Energy


Available only to hierophants with cleric levels, this ability allows a hierophant to channel positive or negative energy much more effectively, increasing his ability to affect undead. Add a +4 bonus to the hierophant's turning checks and turning damage rolls. This ability only affects undead, even if the hierophant can turn other creatures, such as with a granted power of a domain.

### Metamagic Feat


A hierophant can choose a metamagic feat in place of one of the special abilities described here if desired.

### Power of Nature


Available only to hierophants with druid levels, this ability allows a hierophant to temporarily transfer one or more of his druid class features to a willing creature. The transfer lasts anywhere from 24 hours to one week (chosen at the time of transfer), and while the transfer is in effect, the hierophant cannot use the transferred power. He can transfer any of his druid powers except spellcasting and the ability to have an animal companion. The druid's wild shape ability can be partially or completely transferred. For example, a hierophant may transfer the ability to use wild shape once per day to the recipient and retain the rest of his uses for himself. If the hierophant can assume the form of Tiny or Huge animals, the recipient can as well. As with the imbue with spell ability spell, the hierophant remains responsible to his deity for any use to which the recipient puts the transferred abilities.

### Hierophant Align ~ LG

- **PREALIGN:** TN

### Hierophant Align ~ LN


### Hierophant Align ~ LE

- **PREALIGN:** TN

### Hierophant Align ~ NG


### Hierophant Align ~ NE


### Hierophant Align ~ CG

- **PREALIGN:** TN

### Hierophant Align ~ CN


### Hierophant Align ~ CE

- **PREALIGN:** TN

### Terrain Mastery

- **BONUS:** ABILITYPOOL|Terrain Mastery|min(HorizonWalkerLVL,5)

As horizon walkers travel, they gain a mystical connection with the very ground they walk on. At each level, they add a new terrain environment to their repertoire from those given below. Terrain mastery gives a horizon walker a bonus on checks involving a skill useful in that terrain, or some other appropriate benefit. A horizon walker also knows how to fight dangerous creatures typically found in that terrain, gaining a +1 insight bonus on attack rolls and damage rolls against creatures with that terrain mentioned in the Environment entry of their descriptions (see the Monster Manual). The horizon walker only gains the bonus if the Monster Manual description specifically lists the terrain type. Horizon walkers take their terrain mastery with them wherever they go. They retain their terrain mastery bonuses on skill checks, attack rolls, and damage rolls whether they're actually in the relevant terrain or not. For example, a horizon walker who has selected desert terrain mastery is immune to fatigue even if she's underground, in the mountains, or in a city.

### Planar Terrain Mastery

- **BONUS:** ABILITYPOOL|Advanced Terrain Mastery|min(HorizonWalkerLVL-5,5)

Eventually a horizon walker's familiarity with terrain extends to her journeys to other planes of existence. Planar terrain mastery functions just like terrain mastery, except that the horizon walker can choose one of the planar categories at each level. The horizon walker can take a nonplanar terrain type instead, if she wishes.

### Aquatic


You are naturally at home in the water, gaining a +4 competence bonus on Swim checks, or a +10-foot bonus to your swim speed if you have one. You gain a +1 insight bonus on attack and damage rolls against aquatic creatures.

### Desert


You have endured where others perish, so you're good at conserving your body's resources. You resist effects that tire you. You are immune to fatigue, and anything that would cause you to become exhausted makes you fatigued instead. You gain a +1 insight bonus on attack and damage rolls against desert creatures.

### Forest


You have an instinctive sense of camouflage from your time among the trees, granting you a +4 competence bonus on Hide checks. You gain a +1 insight bonus on attack and damage rolls against forest creatures.

### Hills


The faintest echoes find their way to your ears, granting you a +4 competence bonus on Listen checks. You gain a +1 insight bonus on attack and damage rolls against hills creatures.

### Marsh


You have learned to be quieter than the whispering rushes; your mystic connection to the marsh grants you a +4 competence bonus on Move Silently checks. You gain a +1 insight bonus on attack and damage rolls against marsh creatures.

### Mountains


You naturally cling to surfaces others fall from. You gain a +4 competence bonus on Climb checks, or a +10- foot bonus to your climb speed if you have one. You gain a +1 insight bonus on attack and damage rolls against mountain creatures.

### Plains


The wide-open spaces have sharpened your eyes, granting you a +4 competence bonus on Spot checks. You gain a +1 insight bonus on attack and damage rolls against plains creatures.

### Underground


You have magically adapted to your time in the dark. You have 60-foot darkvision, or 120-foot darkvision if you already had darkvision from another source. You gain a +1 insight bonus on attack and damage rolls against underground creatures.

### Fiery (Planar)


This kind of planar terrain mastery provides you with resistance to fire 20. You gain a +1 insight bonus on attack and damage rolls against outsiders and elementals with the fire subtype.

### Weightless (Planar)


You gain a +30-foot bonus to your fly speed on planes with no gravity or subjective gravity, such as the Astral Plane or the Elemental Plane of Air (see Chapter 5). You gain a +1 insight on attack and damage rolls against creatures native to the Astral Plane, the Elemental Plane of Air, and the Ethereal Plane, such as githyanki and air elementals. (A creature native to a particular plane has this fact designated in its Environment entry in the Monster Manual.)

### Cold (Planar)


This kind of planar terrain mastery provides you with resistance to cold 20. You gain a +1 insight bonus on attack and damage rolls against outsiders and elementals with the cold subtype.

### Shifting (Planar)


You have the supernatural ability to use the ever-shifting nature of planes such as Limbo and the Plane of Shadow to travel faster. You instinctively anticipate shifts in the reality of the plane that bring you closer to your destination, giving you the spell-like ability to use dimension door (as the spell cast at your character level) once every 1d4 rounds. You gain a +1 insight bonus on attack and damage rolls against outsiders and elementals native to a shifting plane, such as slaadi and shadow mastiffs.

### Aligned (Planar)


You have the instinctive ability to mimic the dominant alignment of the plane. You incur none of the penalties for having an alignment at odds with that of the plane, and spells and abilities that harm those of the opposite alignment (such as unholy blight) don't affect you. You have the dominant alignment of the plane with regard to magic, but your behavior and any alignment- related class features you have are unaffected.

### Cavernous (Planar)


You gain tremorsense with a 30-foot range.

### Other (Planar)


If your campaign uses planes you have invented yourself (see Creating a Cosmology, page 167), you should design additional planar terrains. A plane composed entirely of an immense black spiderweb suspended over a roiling ocean of insectoid vermin, for example, might have a +4 competence bonus on Balance checks and a +4 bonus on Fortitude saves against poison as the benefit for planar terrain mastery.

### Secret

- **BONUS:** ABILITYPOOL|Loremaster Secret|(LoremasterLVL+1)/2
- **BONUS:** VAR|LoremasterSecretsLVL|LoremasterLVL+INT

In their studies, loremasters stumble upon all sorts of applicable knowledge and secrets. At 1st level and every two levels higher than 1st (3rd, 5th, 7th, and 9th), the loremaster chooses one secret from the table on the next page. Her level plus Intelligence modifier determines the total number of secrets she can choose. She can't choose the same secret twice.

### Lore


Loremasters gather knowledge. At 2nd level, a loremaster gains the ability to know legends or information regarding various topics, just as a bard can with bardic knowledge. The loremaster adds her level and her Intelligence modifier to the lore check. See page 28 of the Player's Handbook for more information on bardic knowledge.

### Bonus Languages

- **DEFINE:** BonusLanguageCount|0
- **BONUS:** ABILITYPOOL|Add Spoken Language|BonusLanguageCount
- **BONUS:** VAR|BonusLanguageCount|LoremasterLVL/4

Loremasters, in their laborious studies, learn new languages in order to access more knowledge. A loremaster can choose any new language at 4th and 8th level.

### Greater Lore


At 6th level, a loremaster gains the ability to understand magic items, as with the identify spell.

### True Lore


At 10th level, once per day a loremaster can use her knowledge to gain the effect of a legend lore spell or an analyze dweomer spell.

### Instant Mastery

- **PREVARGTEQ:** LoremasterSecretsLVL,1
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** NUMCHOICES=1|SKILL|NORANK
- **BONUS:** SKILLRANK|LIST|4

4 ranks of a skill in which the character has no ranks

### Secret Health

- **PREVARGTEQ:** LoremasterSecretsLVL,2
- **BONUS:** HP|CURRENTMAX|3

+3 hit points

### Secrets of Inner Strength

- **PREVARGTEQ:** LoremasterSecretsLVL,3
- **BONUS:** SAVE|BASE.Will|2

+2 bonus on Will saves

### The Lore of True Stamina

- **PREVARGTEQ:** LoremasterSecretsLVL,4
- **BONUS:** SAVE|BASE.Fortitude|2

+2 bonus on Fortitude saves

### Secret Knowledge of Avoidance

- **PREVARGTEQ:** LoremasterSecretsLVL,5
- **BONUS:** SAVE|BASE.Reflex|2

+2 bonus on Reflex saves

### Weapon Trick

- **PREVARGTEQ:** LoremasterSecretsLVL,6
- **BONUS:** COMBAT|TOHIT|1

+1 bonus on attack rolls

### Dodge Trick

- **PREVARGTEQ:** LoremasterSecretsLVL,7
- **BONUS:** COMBAT|AC|1|TYPE=Dodge

+1 dodge bonus to AC

### Applicable Knowledge

- **PREVARGTEQ:** LoremasterSecretsLVL,8
- **BONUS:** ABILITYPOOL|FEAT|1

Any one feat

### Newfound Arcana

- **PREVARGTEQ:** LoremasterSecretsLVL,9
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=1|1

1 bonus 1st-level spell

### More Newfound Arcana

- **PREVARGTEQ:** LoremasterSecretsLVL,10
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** CLASS|PC[SPELLCASTER]
- **BONUS:** SPELLCAST|CLASS=%LIST;LEVEL=2|1

1 bonus 2nd-level spell

### Add Spoken Language

- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** LANG|!PC,QUALIFIED[TYPE=Spoken]
- **AUTO:** LANG|%LIST

### Enhanced Specialization


Upon becoming a Red Wizard, a character increases his devotion to his wizard school of specialization. In exchange for this, the Red Wizard must sacrifice study in one or more schools. The Red Wizard must choose an additional prohibited school or schools using the rules in the Player's Handbook. He can never again learn spells from those prohibited schools. He cannot choose the same prohibited schools he chose as a 1st-level wizard. He can still use the prohibited spells he knew prior to becoming a Red Wizard, including using items that are activated by spell completion or spell trigger. For example, Ghorus Toth is specialized in the school of transmutation. His prohibited schools are abjuration and enchantment. When he becomes a Red Wizard, he must choose one other prohibited school. He decides to select conjuration as his additional prohibited school.

### Specialist Defense


A Red Wizard gains a bonus on saving throws against spells from his specialist school. This bonus starts at +1 and increases at higher levels, as shown on Table 6-15.

### Circle Leader


At 5th level, a Red Wizard gains the ability to become a circle leader, who is the focus person for Red Wizard circle magic (see New Features of the Red Wizard, below).

### Scribe Tattoo


At 7th level, a Red Wizard gains the ability to place the Thayan wizards' magic tattoos upon willing and qualified novices, giving them the Tattoo Focus feat and inducting them into his circle.

### Great Circle Leader


A 10th-level Red Wizard can be the leader of a great circle, which can have up to nine other participants instead of just five.

### Evasion

- **BONUS:** VAR|EvasionUsable,ImprovedEvasionUsable|1

At 2nd level, a shadowdancer gains evasion. If exposed to any effect that normally allows her to attempt a Reflex saving throw for half damage (such as a fireball), she takes no damage with a successful saving throw. The evasion ability can only be used if the shadowdancer is wearing light armor or no armor.

### Darkvision

- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

At 2nd level, a shadowdancer can see in the dark as though she were permanently under the effect of a darkvision spell.

### Shadow Illusion

- **DEFINE:** ShadowIllusionLVL|0
- **SPELLS:** Class|TIMES=1|CASTERLEVEL=ShadowIllusionLVL|Silent Image,11+CHA
- **BONUS:** VAR|ShadowIllusionLVL|ShadowdancerLVL

When a shadowdancer reaches 3rd level, she can create visual illusions from surrounding shadows. This ability's effect is identical to that of the arcane spell silent image and may be employed once per day.

### Summon Shadow

- **DEFINE:** ShadowCompanionLVL|0
- **BONUS:** VAR|ShadowCompanionLVL|ShadowdancerLVL
- **FOLLOWERS:** Shadow Companion|1
- **COMPANIONLIST:** Shadow Companion|Shadow

At 3rd level, a shadowdancer can summon a shadow, an undead shade (see the Monster Manual for the shadow's statistics). Unlike a normal shadow, this shadow's alignment matches that of the shadowdancer, and the creature cannot create spawn. The summoned shadow cannot be turned, rebuked, or commanded by any third party. This shadow serves as a companion to the shadowdancer and can communicate intelligibly with the shadowdancer. Every third level gained by the shadowdancer adds +2 HD (and the requisite base attack and base save bonus increases) to her shadow companion. For example, a 9thlevel shadowdancer can have a shadow companion with 6 HD. If a shadow companion is destroyed, or the shadowdancer chooses to dismiss it, the shadowdancer must attempt a DC 15 Fortitude save. If the saving throw fails, the shadowdancer loses 200 experience points per shadowdancer level. A successful saving throw reduces the loss by half, to 100 XP per prestige class level. The shadowdancer's XP total can never go below 0 as the result of a shadow's dismissal or destruction. A destroyed or dismissed shadow companion cannot be replaced for 30 days.

### Shadow Jump

- **DEFINE:** ShadowJumpRange|0
- **DEFINE:** ShadowJumpProgression|0
- **BONUS:** VAR|ShadowJumpRange|20
- **BONUS:** VAR|ShadowJumpRange|20
- **BONUS:** VAR|ShadowJumpRange|40
- **BONUS:** VAR|ShadowJumpRange|80

At 4th level, a shadowdancer gains the ability to travel between shadows as if by means of a dimension door spell. The limitation is that the magical transport must begin and end in an area with at least some shadow. A shadowdancer can jump up to a total of 20 feet each day in this way; this may be a single jump of 20 feet or two jumps of 10 feet each. Every two levels higher than 4th, the distance a shadowdancer can jump each day doubles (40 feet at 6th, 80 feet at 8th, and 160 feet at 10th). This amount can be split among many jumps, but each one, no matter how small, counts as a 10-foot increment. (A 6th-level shadowdancer who jumps 32 feet cannot jump again until the next day.)

### Defensive Roll


Starting at 5th level, a shadowdancer can roll with a potentially lethal blow to take less damage from it. Once per day, when a shadowdancer would be reduced to 0 hit points or less by damage in combat (from a weapon or other blow, not a spell or special ability), she can attempt to roll with the damage. She makes a Reflex saving throw (DC = damage dealt) and, if successful, takes only half damage from the blow. She must be aware of the attack and able to react to it in order to execute her defensive roll. If she is in a situation that would deny her any Dexterity bonus to AC, she can't attempt a defensive roll.

### Slippery Mind


This ability, gained at 7th level, represents a shadowdancer's ability to wriggle free from magical effects that would otherwise control or compel her. If a shadowdancer is affected by an enchantment and fails her saving throw, 1 round later she can attempt her saving throw again. She only gets this one extra chance to succeed at her saving throw. If it fails as well, the spell's effects occur normally.

### Cannot Create Spawn


The creature cannot create spawn.

### Communiate with Master


This shadow serves as a companion to the shadowdancer and can communicate intelligibly with the shadowdancer.

### Improved Ally


A thaumaturgist is adept at convincing creatures from other planes to do his bidding. When a thaumaturgist casts a planar ally spell (including the lesser and greater versions), he makes a Diplomacy check to convince the creature to aid him for a reduced payment. If the thaumaturgist's Diplomacy check adjusts the creature's attitude to helpful (see Influencing NPC Attitudes, page 72 of the Player's Handbook), the creature will work for 50%% of the standard fee, as long as the task is one that is not against its nature. For example, a 1st-level thaumaturgist negotiating with an initially friendly planar ally that gets a Diplomacy check result of 15 can convince a 6 HD creature to perform a 7- hour task for only 1,500 gp per hour (a 6 HD creature would ordinarily ask for 3,000 gp per hour). The thaumaturgist's improved ally class feature only works when the planar ally shares at least one aspect of alignment with the thaumaturgist. A thaumaturgist can have only one such ally at a time, but he may bargain for tasks from other planar allies normally.

### Augment Summoning

- **ABILITY:** FEAT|AUTOMATIC|Augment Summoning

At 2nd level, a thaumaturgist gains the Augment Summoning feat (see page 89 of the Player's Handbook).

### Extended Summoning


At 3rd level and higher, all spells from the summoning subschool that the thaumaturgist casts have their durations doubled, as if the Extend Spell feat had been applied to them. The levels of the summoning spells don't change, however. This ability stacks with the effect of the Extend Spell feat, which does change the spell's level.

### Contingent Conjuration


A 4th-level thaumaturgist can prepare a summoning or calling spell ahead of time to be triggered by some other event. This functions as described for the contingency spell, including having the thaumaturgist cast the summoning or calling spell beforehand. The spell is cast instantly when the trigger event occurs. For example, a thaumaturgist could use the contingent conjuration ability to summon a barbed devil the next time he is attacked, or call a ghaele eladrin to act as messenger if the king falls ill. The conditions needed to bring the spell into effect must be clear, although they can be general. If complicated or convoluted condition as are prescribed, the contingent conjuration may fail when triggered. The conjuration spell occurs based solely on the stated conditions, regardless of whether the thaumaturgist wants it to, although most conjurations can be dismissed normally. A thaumaturgist can have only one contingent conjuration active at a time.

### Planar Cohort


A 5th-level thaumaturgist can use any of the planar ally spells to call a creature to act as his cohort. The called creature serves loyally and well as long as the thaumaturgist continues to advance a cause important to the creature. For example, a 5th-level thaumaturgist could use planar ally to call a bralani eladrin to act as his cohort. As long as the thaumaturgist undertakes quests and missions to fight evil and uphold good, the eladrin will loyally serve. to call a planar cohort, the thaumaturgist must cast the relevant spell, paying the XP costs normally. It takes an offering of 1,000 gp ? the HD of the creature to convince it to serve as a planar cohort, and the improved ally class feature can't be used to reduce or eliminate this cost. The planar cohort can't have more Hit Dice than the thaumaturgist has, and must have an ECL no higher than the thaumaturgist's character level -2. A bralani eladrin has an ECL of 11 (6 Hit Dice and +5 level adjustment), so it might serve as a planar cohort to an 8th-level cleric/ 5th-level thaumaturgist (character level 13th). A thaumaturgist can have only one planar cohort at a time, but he can continue to make agreements with other called creatures normally. A planar cohort replaces a thaumaturgist's existing cohort, if he has one by virtue of the Leadership feat (page 106).

### Negative Levels

- **DEFINE:** NegativeLvls|0
- **BONUS:** COMBAT|TOHIT|-1*(NegativeLvls)
- **BONUS:** SKILL|TYPE=Strength,TYPE=Dexterity,TYPE=Constitution,TYPE=Intelligence,TYPE=Wisdom,TYPE=Charisma|-1*(NegativeLvls)
- **BONUS:** SAVE|Fortitude,Reflex,Will|-1*(NegativeLvls)

%1 negative level(s) (-%1 effective level(s) and loses access to %1 spell(s) from the highest spell level castable)|NegativeLvls

### Holy Avenger Spell Resistance

- **BONUS:** MISC|SR|PaladinLvl+5|TYPE=SpellResistance

### Resistance to Acid

- **DEFINE:** AcidResistanceBonusSp|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Acid ~ SpellLike Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Acid,Vulnerability to Acid

### Resistance to Cold

- **DEFINE:** ColdResistanceBonusSp|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Cold ~ SpellLike Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Cold,Vulnerability to Cold

### Resistance to Fire

- **DEFINE:** FireResistanceBonusSp|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Fire ~ SpellLike Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Fire,Vulnerability to Fire

### Resistance to Electricity

- **DEFINE:** ElectricityResistanceBonusSp|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Electricity ~ SpellLike Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Electricity,Vulnerability to Electricity

### Resistance to Sonic

- **DEFINE:** SonicResistanceBonusSp|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Sonic ~ SpellLike Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Sonic,Vulnerability to Sonic

### Concealment Chance

- **DEFINE:** ConcealmentChance|0
- **ASPECT:** CombatBonus|%1%% miss chance from Concealment|ConcealmentChance

You have concealment %1%%|ConcealmentChance

## Ability Categories

### ABILITYCATEGORY:High Arcana Ability

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **PLURAL:** High Arcana Abilities
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Hierophant Ability

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **PLURAL:** Hierophant Abilities
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Terrain Mastery

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **PLURAL:** Terrain Masteries
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Advanced Terrain Mastery

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **PLURAL:** Advanced Terrain Masteries
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Loremaster Secret

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **PLURAL:** Loremaster Secrets
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Dragon Disciple Bonus Spell

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **PLURAL:** Dragon Disciple Bonus Spells
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Adept Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Adept Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Aristocrat Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Aristocrat Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Commoner Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Common Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Expert Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Expert Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Warrior Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Warrior Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Arcane Archer Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Arcane Archer Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Arcane Trickster Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Arcane Trickster Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Archmage Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Archmage Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Assassin Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Assassin Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Blackguard Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Blackguard Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Dragon Disciple Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Dragon Disciple Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Duelist Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Duelist Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Dwarven Defender Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Dwarven Defender Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Eldritch Knight Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Eldritch Knight Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Hierophant Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Hierophant Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Horizon Walker Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Hierophant Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Loremaster Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Loremaster Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Mystic Theurge Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Mystic Theurge Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Red Wizard Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Red Wizard Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Shadowdancer Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Shadowdancer Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Thaumaturgist Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Thaumaturgist Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Spell-Like Ability Selection

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **ABILITYLIST:** High Arcana ~ Spell-Like Ability Selection
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Hierophant Align

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Hierophant Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Add Spoken Language

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **DISPLAYLOCATION:** Class Features

## Classes

### CLASS:Adept

- **HD:** 6
- **FACT:** ClassType|NPC
- **FACT:** Abb|Adp
- **MAXLEVEL:** 20
- **DEFINE:** AdeptLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|AdeptLVL|CL
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 1

- **SPELLLEVEL:** CLASS|Adept=0|Create Water,Cure Minor Wounds,Detect Magic,Ghost Sound,Guidance,Light,Mending,Purify Food and Drink,Read Magic,Touch of Fatigue

### 2

- **ABILITY:** Adept Class Feature|AUTOMATIC|Adept ~ Summon Familiar

### 3

- **CAST:** 3,2

### 4

- **CAST:** 3,2,0

### 5

- **CAST:** 3,2,1

### 6

- **CAST:** 3,2,1

### 7

- **CAST:** 3,3,2

### 8

- **CAST:** 3,3,2,0

### 9

- **CAST:** 3,3,2,1

### 10

- **CAST:** 3,3,2,1

### 11

- **CAST:** 3,3,3,2

### 12

- **CAST:** 3,3,3,2,0

### 13

- **CAST:** 3,3,3,2,1

### 14

- **CAST:** 3,3,3,2,1

### 15

- **CAST:** 3,3,3,3,2

### 16

- **CAST:** 3,3,3,3,2,0

### 17

- **CAST:** 3,3,3,3,2,1

### 18

- **CAST:** 3,3,3,3,2,1

### 19

- **CAST:** 3,3,3,3,3,2

### 20

- **CAST:** 3,3,3,3,3,2

### CLASS:Aristocrat

- **HD:** 8
- **FACT:** ClassType|NPC
- **FACT:** Abb|Ari
- **MAXLEVEL:** 20
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Commoner

- **HD:** 4
- **FACT:** ClassType|NPC
- **FACT:** Abb|Com
- **MAXLEVEL:** 20
- **WEAPONBONUS:** TYPE=Simple
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Expert

- **HD:** 6
- **FACT:** ClassType|NPC
- **FACT:** Abb|Exp
- **MAXLEVEL:** 20
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Warrior

- **HD:** 8
- **FACT:** ClassType|NPC
- **FACT:** Abb|War
- **MAXLEVEL:** 20
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Arcane Archer

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Arc
- **DEFINE:** ArcaneArcherLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|ArcaneArcherLVL|CL
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Arcane Trickster

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Art
- **DEFINE:** ArcaneTricksterLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|ArcaneTricksterLVL|CL
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Archmage

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Arm
- **MAXLEVEL:** 5
- **DEFINE:** ArchmageLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|ArchmageLVL|CL
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Assassin

- **HD:** 6
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Asn
- **DEFINE:** AssassinLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** VAR|AssassinLVL|CL
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Blackguard

- **HD:** 10
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Bgd
- **DEFINE:** BlackguardLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|BlackguardLVL|CL
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3
- **EXCHANGELEVEL:** Ex Paladin|11|10|1

### CLASS:Dragon Disciple

- **HD:** 12
- **FACT:** ClassType|Prestige
- **FACT:** Abb|DrD
- **ALLOWBASECLASS:** NO
- **DEFINE:** DragonDiscipleLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** VAR|DragonDiscipleLVL|CL
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### SUBCLASS:Black Dragon Disciple

- **COST:** 0

### SUBCLASSLEVEL:3

- **ABILITY:** Special Ability|AUTOMATIC|Dragon Disciple Breath Weapon ~ Line of Acid

### SUBCLASSLEVEL:10

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Acid

### SUBCLASS:Blue Dragon Disciple

- **COST:** 0

### SUBCLASS:Green Dragon Disciple

- **COST:** 0

### SUBCLASS:Red Dragon Disciple

- **COST:** 0

### SUBCLASS:White Dragon Disciple

- **COST:** 0

### SUBCLASS:Brass Dragon Disciple

- **COST:** 0

### SUBCLASS:Bronze Dragon Disciple

- **COST:** 0

### SUBCLASS:Copper Dragon Disciple

- **COST:** 0

### SUBCLASS:Gold Dragon Disciple

- **COST:** 0

### SUBCLASS:Silver Dragon Disciple

- **COST:** 0

### CLASS:Duelist

- **HD:** 10
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Dul
- **DEFINE:** DuelistLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|DuelistLVL|CL
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Dwarven Defender

- **HD:** 12
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Ddf
- **DEFINE:** DwarvenDefenderLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|DwarvenDefenderLVL|CL
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Eldritch Knight

- **HD:** 6
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Elk
- **DEFINE:** EldritchKnightLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|EldritchKnightLVL|CL
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Hierophant

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Hie
- **MAXLEVEL:** 5
- **DEFINE:** HierophantLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|HierophantLVL|CL
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Horizon Walker

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|How
- **DEFINE:** HorizonWalkerLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|HorizonWalkerLVL|CL
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Loremaster

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Lor
- **DEFINE:** LoremasterLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|LoremasterLVL|CL
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Mystic Theurge

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Myt
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Red Wizard

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Rw
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Shadowdancer

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Shd
- **DEFINE:** ShadowdancerLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ShadowdancerLVL|CL
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Thaumaturgist

- **HD:** 4
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Tha
- **MAXLEVEL:** 5
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

## Companion Modifiers

### FOLLOWER:FiendishServantLVL=5

- **HD:** 2
- **ABILITY:** Special Ability|AUTOMATIC|Fiendish Servant ~ Empathic Link|Fiendish Servant ~ Improved Evasion|Fiendish Servant ~ Share Saving Throws|Fiendish Servant ~ Share Spells
- **DEFINESTAT:** MINVALUE|INT|6
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1
- **TEMPLATE:** Fiendish

### FOLLOWER:FiendishServantLVL=13

- **HD:** 2
- **ABILITY:** Special Ability|AUTOMATIC|Fiendish Servant ~ Speak with Blackguard
- **DEFINESTAT:** MINVALUE|INT|7
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1

### FOLLOWER:FiendishServantLVL=16

- **HD:** 2
- **ABILITY:** Special Ability|AUTOMATIC|Fiendish Servant ~ Blood Bond
- **DEFINESTAT:** MINVALUE|INT|8
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1

### FOLLOWER:FiendishServantLVL=19

- **HD:** 2
- **SR:** 24
- **DEFINESTAT:** MINVALUE|INT|9
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1

### FOLLOWER:FiendishServantLVL=20

- **SR:** 25

### FOLLOWER:UndeadCompanionLVL=1

- **HD:** 2
- **ABILITY:** Special Ability|VIRTUAL|Smite Good
- **ABILITY:** Special Ability|AUTOMATIC|Fiendish Servant ~ Empathic Link|Fiendish Servant ~ Improved Evasion|Fiendish Servant ~ Share Saving Throws|Fiendish Servant ~ Share Spells|Undead Companion ~ Cannot be Turned or Rebuked
- **DEFINESTAT:** MINVALUE|INT|6
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1
- **BONUS:** VAR|SmiteGood|3
- **BONUS:** VAR|SmiteGoodDamage|min(TL,20)

### FOLLOWER:UndeadCompanionLVL=13

- **HD:** 2
- **ABILITY:** Special Ability|AUTOMATIC|Fiendish Servant ~ Speak with Blackguard
- **DEFINESTAT:** MINVALUE|INT|7
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1

### FOLLOWER:UndeadCompanionLVL=16

- **HD:** 2
- **ABILITY:** Special Ability|AUTOMATIC|Fiendish Servant ~ Blood Bond
- **DEFINESTAT:** MINVALUE|INT|8
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1

### FOLLOWER:UndeadCompanionLVL=19

- **HD:** 2
- **SR:** 24
- **DEFINESTAT:** MINVALUE|INT|9
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|1

### FOLLOWER:UndeadCompanionLVL=20

- **SR:** 25

### FOLLOWER:ShadowCompanionLVL=3

- **HD:** 2
- **ABILITY:** Special Ability|AUTOMATIC|Shadow Companion ~ Cannot be Turned or Rebuked|Shadow Companion ~ Cannot Create Spawn|Shadow Companion ~ Communiate with Master
- **BONUS:** VAR|ShadowSpawnBlock|1

### FOLLOWER:ShadowCompanionLVL=6

- **HD:** 2

### FOLLOWER:ShadowCompanionLVL=9

- **HD:** 2

## Equipment

### Blowgun

- **PROFICIENCY:** WEAPON|Blowgun
- **COST:** 1
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1
- **RANGE:** 10
- **SPROP:** This weapon is used to propel small needles a long distance. It is silent.

### Needles, Blowgun (20)

- **COST:** 1
- **WT:** 1
- **SPROP:** These 2-inch-long iron needles are sold in small wooden cases of 20. A full case is so light that its weight is negligible.

### Wakizashi

- **PROFICIENCY:** WEAPON|Sword (Short)
- **COST:** 0
- **WT:** 3
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d6
- **EQMOD:** Masterwork (Weapon)
- **SIZE:** M
- **SPROP:** This small, slightly curved short sword is made with a skill only masterful weaponsmiths possess. It counts as a masterwork weapon and grants its wielder a +1 bonus on attack rolls. A masterwork weapon's bonus on attack rolls does not stack with an enhancement bonus on attack rolls.

### Kusari-Gama

- **PROFICIENCY:** WEAPON|Kusari-Gama
- **COST:** 10
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **SPROP:** This small sickle is attached to a length of chain. A kusari-gama is an exotic weapon that has reach. It can strike opponents 10 feet away. In addition, unlike other weapons with reach, it can be used against an adjacent foe. It can be used in all respects like a spiked chain (see page 115 of the Player's Handbook) for trip attacks, disarming other foes, and using its wielder's Dexterity modifier instead of her Strength modifier in attack rolls.

### Katana

- **PROFICIENCY:** WEAPON|Sword (Bastard)
- **COST:** 100
- **WT:** 6
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d10
- **EQMOD:** Masterwork (Weapon)
- **WIELD:** TwoHanded
- **SPROP:** While functionally a bastard sword, this sword is the most masterfully made nonmagical weapon in existence. It counts as a masterwork weapon and grants its wielder a +1 bonus on attack rolls. A katana is too large to use in one hand without special training; thus, it is an exotic weapon. A Medium creature can use a katana two-handed as a martial weapon, or a Large creature can use it one-handed in the same way. With Exotic Weapon Proficiency (Sword (Bastard)), a Medium creature can use it in one hand. A masterwork weapon's bonus on attack rolls does not stack with an enhancement bonus on attack rolls.
- **BONUS:** WEAPON|WIELDCATEGORY|-1

### Pistol

- **PROFICIENCY:** WEAPON|Pistol
- **COST:** 250
- **WT:** 3
- **CRITMULT:** x3
- **DAMAGE:** 1d10
- **RANGE:** 50
- **SIZE:** M
- **SPROP:** This firearm holds a single shot and requires a standard action to reload.

### Musket

- **PROFICIENCY:** WEAPON|Musket
- **COST:** 500
- **WT:** 10
- **CRITMULT:** x3
- **DAMAGE:** 1d12
- **RANGE:** 150
- **SIZE:** M
- **SPROP:** The musket holds a single shot and requires a standard action to reload.

### Bomb

- **PROFICIENCY:** WEAPON|NoProfReq
- **COST:** 150
- **WT:** 1
- **DAMAGE:** 2d6
- **RANGE:** 10
- **SPROP:** Blast Radius 5 ft.

### Smoke Bomb

- **PROFICIENCY:** WEAPON|NoProfReq
- **COST:** 70
- **WT:** 1
- **RANGE:** 10

### Bullets (10)

- **COST:** 3
- **SPROP:** These large, round, lead projectiles are sold in bags of 10 for 3 gp. A bag of bullets weighs 2 pounds..

### Gunpowder (Barrel)

- **COST:** 250
- **WT:** 20

### Gunpowder (Horn)

- **COST:** 35
- **WT:** 2

### Gunpowder (1oz)

- **COST:** 0.9375
- **WT:** 0.0625

### Pistol, Automatic

- **PROFICIENCY:** WEAPON|Pistol (Automatic)
- **WT:** 3
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 2d6
- **RANGE:** 40
- **QUALITY:** Era|Modern
- **SPROP:** An automatic pistol can fire fifteen times before reloading and can be used to attack more than once per round if the user has the ability to make multiple attacks. Releasing an empty magazine and inserting a new one is a move action.

### Pistol, Revolver

- **PROFICIENCY:** WEAPON|Pistol (Revolver
- **WT:** 3
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 2d8
- **RANGE:** 30
- **QUALITY:** Era|Modern
- **SPROP:** A revolver can fire six times before it needs reloading (which requires a full-round action).

### Rifle, Hunting

- **PROFICIENCY:** WEAPON|Rifle (Hunting)
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 2d10
- **RANGE:** 80
- **QUALITY:** Era|Modern
- **SPROP:** A hunting rifle can fire five times before it needs reloading (which requires a full-round action).

### Rifle, Automatic

- **PROFICIENCY:** WEAPON|Rifle (Automatic)
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 2d8
- **RANGE:** 80
- **QUALITY:** Era|Modern
- **SPROP:** An automatic rifle can fire thirty times before it needs reloading. Releasing an empty magazine and inserting a new one is a move action. As an attack, an automatic rifle can instead spray a space 10 feet across with ten bullets. If the attacker succeeds on an attack roll against AC 10, everyone in that space must make a DC 15 Reflex save or take the weapon's damage.

### Shotgun

- **PROFICIENCY:** WEAPON|Shotgun
- **WT:** 7
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 2d8
- **RANGE:** 30
- **QUALITY:** Era|Modern
- **SPROP:** A shotgun is most effective at close range; on any successful attack, a -1 penalty is applied to the damage roll for each range increment of the attack. It can fire six times before it needs reloading (which requires a full-round action). The weapon uses shotgun shells, cylindrical cartridges that have a built-in firing cap at their base. They are packed with a mixture of gunpowder and small lead pellets.

### Grenade Launcher

- **PROFICIENCY:** WEAPON|Grenade Launcher
- **WT:** 7
- **CRITRANGE:** 1
- **RANGE:** 70
- **QUALITY:** Era|Modern
- **SPROP:** A grenade launcher can fire fragmentation or smoke grenades using its range increment, but must be reloaded each time it fires, requiring a standard action. A grenade launcher is a tube set on a metal tripod and equipped with a sighting mechanism. A single smoke grenade or fragmentation grenade easily slips into the tube.

### Dynamite

- **SPROP:** This short, thin cylinder of explosive material has a fuse that must be lit before it is thrown or set. Lighting a stick of dynamite is a move action, and the dynamite goes off in the same round or up to several minutes later (depending on how long the fuse is). The explosive has a blast radius of 5 feet and deals 2d6 points of bludgeoning damage. Anyone caught within the blast radius can make a DC 15 Reflex save to take half damage. It's possible to bind together several sticks of dynamite so they ignite and explode at the same time. Each additional stick increases the damage by 1d6 (maximum damage 10d6) and the burst radius by 5 feet (maximum burst radius 20 feet).

### Grenade, Fragmentation

- **PROFICIENCY:** WEAPON|NoProfReq
- **SPROP:** A fragmentation grenade looks like a large egg, sometimes mounted on a 1-foot-long stick with small fins. If thrown, it uses its range increment, but if launched from a grenade launcher, it uses that weapon's range increment. Fragmentation grenades are advanced antipersonnel explosives that deal slashing damage in a 20-foot radius. Anyone caught within the blast radius can make a DC 15 Reflex save to take half damage.

### Grenade, Smoke

- **PROFICIENCY:** WEAPON|NoProfReq
- **SPROP:** A smoke grenade looks like a squat cylinder, sometimes mounted on a 1-foot-long stick with small fins. If thrown, it uses its range increment, but if launched from a grenade launcher, it uses that weapon's range increment. One round after it lands or hits its target, this nondamaging explosive emits a cloud of smoke (as the fog cloud spell) in a 20-foot radius. A moderate wind (11+ mph) disperses the smoke in 4 rounds; a strong wind (21+ mph) disperses the fog in 1 round.

### Laser Pistol

- **PROFICIENCY:** WEAPON|Laser Pistol
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 3d6
- **WIELD:** OneHanded
- **RANGE:** 40
- **QUALITY:** Era|Futuristic
- **SPROP:** A laser pistol fires fifty times before a new energy cell (weight 1 pound) needs to be reloaded and has a rate of fire equal to the attacker's number of attacks. Reloading the weapon is a move action.

### Antimatter Rifle

- **PROFICIENCY:** WEAPON|Antimatter Rifle
- **WT:** 10
- **SLOTS:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 6d8
- **WIELD:** TwoHanded
- **RANGE:** 120
- **QUALITY:** Era|Futuristic
- **SPROP:** An antimatter rifle is a devastating short-range attack weapon that can be fired once per round. It holds an energy cell (weight 1 pound) that is depleted after two shots. Reloading the weapon is a move action.

### Flamer

- **PROFICIENCY:** WEAPON|Flamer
- **WT:** 8
- **SLOTS:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 3d6
- **WIELD:** TwoHanded
- **RANGE:** 100
- **QUALITY:** Era|Futuristic
- **SPROP:** A flamer can be fired once per round. Unlike other ranged weapons, it deals damage to every square in a 5-foot-wide stream extending out to the flamer's maximum range (200 feet). It contains a fuel pack with enough concentrated flamer fuel for ten shots. Installing a new fuel pack requires a full-round action.

### Laser Rifle

- **PROFICIENCY:** WEAPON|Laser Rifle
- **WT:** 7
- **SLOTS:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 3d8
- **WIELD:** TwoHanded
- **RANGE:** 100
- **QUALITY:** Era|Futuristic
- **SPROP:** A laser rifle fires thirty times before a new energy cell (weight 1 pound) needs to be reloaded and has a rate of fire equal to the attacker's number of attacks. Reloading the weapon is a move action.

### Coin (Platinum)

- **COST:** 10
- **WT:** 0.02

### Coin (Gold)

- **COST:** 1
- **WT:** 0.02

### Coin (Silver)

- **COST:** 0.1
- **WT:** 0.02

### Coin (Copper)

- **COST:** 0.01
- **WT:** 0.02

### Agate (Banded)

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Agate (Eye)

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Agate (Moss)

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Azurite

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Quartz (Blue)

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Hematite

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Lapis Lazuli

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Malachite

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Obsidian

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Rhodochrosite

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Tiger Eye

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Turquoise

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Pearl (Freshwater/Irregular)

- **COST:** 10
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Bloodstone

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Carnelian

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Chalcedony

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Chrysoprase

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Citrine

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Iolite

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Jasper

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Moonstone

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Onyx

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Peridot

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Rock Crystal (Clear Quartz)

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Sard

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Sardonyx

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Quartz (Rose)

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Quartz (Smoky)

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Quartz (Star Rose)

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Zircon

- **COST:** 50
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Amber

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Amethyst

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Chrysoberyl

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Coral

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Garnet (Red)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Garnet (Brown-Green)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Jade

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Jet

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Pearl (White)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Pearl (Golden)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Pearl (Pink)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Pearl (Silver)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Spinel (Red)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Spinel (Red-Brown)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Spinel (Deep Green)

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Tourmaline

- **COST:** 100
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Alexandrite

- **COST:** 500
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Aquamarine

- **COST:** 500
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Garnet (Violet)

- **COST:** 500
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Pearl (Black)

- **COST:** 500
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Spinel (Deep Blue)

- **COST:** 500
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Topaz (Golden Yellow)

- **COST:** 500
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Emerald

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Opal (White)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Opal (Black)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Opal (Fire)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Sapphire (Blue)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Corundum (Fiery Yellow)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Corundum (Rich Purple)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Star Sapphire (Blue)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Star Sapphire (Black)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Ruby (Star)

- **COST:** 1000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Emerald (Clearest Bright Green)

- **COST:** 5000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Diamond (Blue-White)

- **COST:** 5000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Diamond (Canary)

- **COST:** 5000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Diamond (Pink)

- **COST:** 5000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Diamond (Brown)

- **COST:** 5000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Diamond (Blue)

- **COST:** 5000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Jacinth

- **COST:** 5000
- **WT:** 0
- **SORTKEY:** Gem_Standard

### Headband

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Hat

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Helmet

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Phylactery

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Eye Lenses

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Goggles

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Amulet

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Brooch

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Medallion

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Necklace

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Periapt

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Scarab

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Vest

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Vestment

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Shirt

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Robe

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Belt

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Cloak

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Cape

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Mantle

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Bracers

- **COST:** 0
- **WT:** 0
- **SLOTS:** 2
- **MODS:** REQUIRED

### Bracelets

- **COST:** 0
- **WT:** 0
- **SLOTS:** 2
- **MODS:** REQUIRED

### Gloves

- **COST:** 0
- **WT:** 0
- **SLOTS:** 2
- **MODS:** REQUIRED

### Gauntlets

- **COST:** 0
- **WT:** 0
- **SLOTS:** 2
- **MODS:** REQUIRED

### Ring

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Boots

- **COST:** 0
- **WT:** 0
- **SLOTS:** 2
- **MODS:** REQUIRED

### Shoes

- **COST:** 0
- **WT:** 0
- **SLOTS:** 2
- **MODS:** REQUIRED

### Art

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Gem

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Potion

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Rod

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Scroll

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Staff

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Wand

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Spell Component

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Spell Focus

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Trap (Mechanical)

- **COST:** 1000
- **DEFINE:** TrapCR|0
- **MODS:** REQUIRED
- **SPROP:** Trap CR %|TrapCR

### Poison (Nitharit)

- **COST:** 650
- **WT:** 0
- **SPROP:** Poison. Contact DC 13, Inititial damage:0, Secondary damage:3d6 CON

### Poison (Sassone leaf residue)

- **COST:** 300
- **WT:** 0
- **SPROP:** Poison. Contact DC 16, Init.:2d12 HP, Secondary damage:1d6 CON

### Poison (Malyss root paste)

- **COST:** 500
- **WT:** 0
- **SPROP:** Poison. Contact DC 16, Initial damage:1 DEX, Secondary damage:2d4 DEX

### Poison (Terinav root)

- **COST:** 750
- **WT:** 0
- **SPROP:** Poison. Contact DC 16, Initial damage:1d6 DEX, Secondary damage:2d6 DEX

### Poison (Black lotus extract)

- **COST:** 4500
- **WT:** 0
- **SPROP:** Poison. Contact DC 20, Initial damage:3d6 CON / 3d6 CON

### Poison (Dragon bile)

- **COST:** 1500
- **WT:** 0
- **SPROP:** Poison. Contact DC 26, Initial damage:3d6 STR / 0

### Poison (Striped toadstool)

- **COST:** 180
- **WT:** 0
- **SPROP:** Poison. Ingested DC 11, Initial damage:1 WIS, Secondary damage:2d6 WIS + 1d4 INT

### Poison (Arsenic)

- **COST:** 120
- **WT:** 0
- **SPROP:** Poison. Ingested DC 13, Initial damage:1 CON, Secondary damage:1d8 CON

### Poison (Id moss)

- **COST:** 125
- **WT:** 0
- **SPROP:** Poison. Ingested DC 14, Initial damage:1d4 INT, Secondary damage: 2d6 INT

### Poison (Oil of taggit)

- **COST:** 90
- **WT:** 0
- **SPROP:** Poison. Ingested DC 15, Initial damage:0, Secondary damage: unconsciousness

### Poison (Lich dust)

- **COST:** 250
- **WT:** 0
- **SPROP:** Poison. Ingested DC 17, Initial damage:2d6 STR, Secondary damage:1d6 STR

### Poison (Dark reaver powder)

- **COST:** 300
- **WT:** 0
- **SPROP:** Poison. Ingested DC 18, Initial damage:2d6 CON / 1d6 CON + 1d6 STR

### Poison (Ungol dust)

- **COST:** 1000
- **WT:** 0
- **SPROP:** Poison. Inhaled DC 15, Initial damage:1 CHA, Secondary damage:1d6 CHA + 1 CHA (permanent)

### Poison (Insanity mist)

- **COST:** 1500
- **WT:** 0
- **SPROP:** Poison. Inhaled DC 15, Initial damage:1d4 WIS, Secondary damage: 2d6 WIS

### Poison (Burnt othur fumes)

- **COST:** 2100
- **WT:** 0
- **SPROP:** Poison. Inhaled DC 18, Initial damage:1 CON (permanent), Secondary damage:3d6 CON

### Poison (Black adder venom)

- **COST:** 120
- **WT:** 0
- **SPROP:** Poison. Injury DC 11, Initial damage:1d6 CON, Secondary damage:1d6 CON

### Poison (Small centipede poison)

- **COST:** 90
- **WT:** 0
- **SPROP:** Poison. Injury DC 11, Initial damageal Damage:1d2 DEX. Secondary damagendary Damage: 1d2 DEX

### Poison (Bloodroot)

- **COST:** 100
- **WT:** 0
- **SPROP:** Poison. Injury DC 12, Initial damage:0, Secondary damage:1d4 CON + 1d3 WIS

### Poison (Drow Poison)

- **COST:** 75
- **WT:** 0
- **SPROP:** Poison. Injury DC 13, Initial damage:unconsciousness, Secondary damage:unconsciousness for 2d4 hours

### Poison (Greenblood oil)

- **COST:** 100
- **WT:** 0
- **SPROP:** Poison. Injury DC 13, Initial damage:1 CON, Secondary damage:1d2 CON

### Poison (Blue whinnis)

- **COST:** 120
- **WT:** 0
- **SPROP:** Poison. Injury DC 14, Initial damage:1 CON, Secondary damage:unconsciousness

### Poison (Medium spider venom)

- **COST:** 150
- **WT:** 0
- **SPROP:** Poison. Injury DC 14, Initial damage:1d4 STR, Secondary damage:1d4 STR

### Poison (Shadow essence)

- **COST:** 250
- **WT:** 0
- **SPROP:** Poison. Injury DC 17, Initial damage:1 STR (permanent), Secondary damage:2d6 STR

### Poison (Wyvern poison)

- **COST:** 3000
- **WT:** 0
- **SPROP:** Poison. Injury DC 17, Initial damage:2d6 CON, Secondary damage:2d6 CON

### Poison (Large scorpion venom)

- **COST:** 200
- **WT:** 0
- **SPROP:** Poison. Injury DC 18, Initial damage:1d6 STR, Secondary damage:1d6 STR

### Poison (Giant wasp poison)

- **COST:** 210
- **WT:** 0
- **SPROP:** Poison. Injury DC 18, Initial damage:1d6 DEX, Secondary damage:1d6 DEX

### Poison (Deathblade)

- **COST:** 1800
- **WT:** 0
- **SPROP:** Poison. Injury DC 20, Initial damage:1d6 CON, Secondary damage:2d6 CON

### Poison (Purple worm poison)

- **COST:** 700
- **WT:** 0
- **SPROP:** Poison. Injury DC 24, Initial damage:1d6 STR, Secondary damage:2d6 STR

### Gem (Agate (Banded))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Agate (Eye))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Agate (Moss))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Azurite)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Quartz (Blue))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Hematite)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Lapis Lazuli)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Malachite)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Obsidian)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Rhodochrosite)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Tiger Eye)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Turquoise)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Pearl (Freshwater/Irregular))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Bloodstone)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Carnelian)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Chalcedony)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Chrysoprase)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Citrine)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Iolite)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Jasper)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Moonstone)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Onyx)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Peridot)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Rock Crystal (Clear Quartz))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Sard)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Sardonyx)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Quartz (Rose))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Quartz (Smoky))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Quartz (Star Rose))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Zircon)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Amber)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Amethyst)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Chrysoberyl)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Coral)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Garnet (Red))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Garnet (Brown-Green))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Jade)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Jet)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Pearl (White))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Pearl (Golden))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Pearl (Pink))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Pearl (Silver))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Spinel (Red))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Spinel (Red-Brown))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Spinel (Deep Green))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Tourmaline)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Alexandrite)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Aquamarine)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Garnet (Violet))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Pearl (Black))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Spinel (Deep Blue))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Topaz (Golden Yellow))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Emerald)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Opal (White))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Opal (Black))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Opal (Fire))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Sapphire (Blue))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Corundum (Firey Yellow))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Corundum (Rich Purple))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Star Sapphire (Blue))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Star Sapphire (Black))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Ruby (Star))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Emerald (Clearest Bright Green))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Diamond (Blue-White))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Diamond (Canary))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Diamond (Pink))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Diamond (Brown))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Diamond (Blue))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Gem (Jacinth)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED
- **SORTKEY:** Gem_Random

### Art (Silver Ewer)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Statuette (Carved Bone))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Statuette (Ivory))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Bracelet (Small/Gold/Finely Wrought))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Vestments (Cloth of Gold))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Mask (Black Velvet with Numerous Citrines))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Chalice (Silver with Lapis Lazuli Gems)

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Tapestry (Large/Wool/Well-Done))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Mug (Brass with Jade Inlays))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Comb (Silver with Moonstones))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Longsword (Silver-Plated with Jet Jewel in Hilt))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Harp (Carved Exotic Wood with Ivory Inlay and Zircon Gems))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Idol (Solid Gold 10 lb.))

- **COST:** 0
- **WT:** 10
- **MODS:** REQUIRED

### Art (Comb (Gold Dragon with Red Garnet Eye))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Stopper Cork (Gold and Topaz))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Dagger (Ceremonial Electrum with Star Ruby in the Pommel))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Eyepatch (Mock Eye of Sapphire and Moonstone))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Pendant (Fire Opal on Fine Gold Chain))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Painting (Old Masterpiece))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Mantle (Embroidered Silk and Velvet with Numerous Moonstones))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Pendant (Sapphire on Gold Chain))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Glove (Embroidered and Bejeweled))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Anklet (Jeweled))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Music Box (Gold))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Circlet (Golden with Four Aquamarines))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Necklace (String of Small Pink Pearls))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Crown (Jeweled Gold))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Ring (Jeweled Electrum))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Ring (Gold and Ruby))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Art (Cup (Gold Set with Emeralds))

- **COST:** 0
- **WT:** 0
- **MODS:** REQUIRED

### Adamantine Breastplate

- **PROFICIENCY:** ARMOR|Breastplate
- **COST:** 200
- **WT:** 30
- **ACCHECK:** -4
- **EQMOD:** ADAMANT_ARMR_MED
- **MAXDEX:** 3
- **SPELLFAILURE:** 25
- **DR:** 2/-
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **SPROP:** This nonmagical breastplate is made of adamantine, giving its wearer damage reduction of 2/-. No aura (nonmagical)

### Banded Mail of Luck

- **PROFICIENCY:** ARMOR|Banded Mail
- **COST:** 250
- **WT:** 35
- **ACCHECK:** -6
- **EQMOD:** MAGIC_COST|9500.Masterwork (Armor).PLUS3A.STEEL
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|6|TYPE=Armor
- **SPROP:** Ten 100-gp gems adorn this +3 banded mail. Once per week, the armor allows its wearer to require that an attack roll made against him be rerolled. He must take whatever consequences come from the second roll, since not all luck is good. The wearer's player must decide whether to have the attack roll rerolled before damage is rolled. Strong enchantment; CL 12th

### Breastplate of Command

- **PROFICIENCY:** ARMOR|Breastplate
- **COST:** 200
- **WT:** 30
- **ACCHECK:** -4
- **EQMOD:** MAGIC_COST|21050.Masterwork (Armor).PLUS2A.STEEL
- **MAXDEX:** 3
- **SPELLFAILURE:** 25
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **BONUS:** SKILL|TYPE=Charisma|2|TYPE=Competence
- **BONUS:** VAR|LeadershipScore,TurnCheckBase|2|TYPE=Competence
- **SPROP:** This finely crafted +2 breastplate radiates a powerful aura of magic. When worn, the armor bestows a dignified and commanding aura upon its owner. The wearer gains a +2 competence bonus on all Charisma checks, including turning checks and Charisma-based skill checks. The wearer also gains a +2 competence bonus to his Leadership score (see page 106). Friendly troops within 360 feet of the user become braver than normal (for example, more willing than normal to follow a leader into battle against dangerous foes). Since the effect arises in great part from the distinctiveness of the armor, the wearer cannot hide or conceal herself in any way and still have the effect function. Strong enchantment; CL 15th

### Celestial Armor

- **PROFICIENCY:** ARMOR|Chainmail
- **COST:** 150
- **WT:** 20
- **ACCHECK:** -3
- **EQMOD:** MAGIC_COST|13100.Masterwork (Armor).PLUS3A.STEEL
- **MAXDEX:** 8
- **SPELLFAILURE:** 15
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Fly,14
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **SPROP:** This bright silver or gold +3 chainmail is so fine and light that it can be worn under normal clothing without betraying its presence. It has a maximum Dexterity bonus of +8, an armor check penalty of -2, and an arcane spell failure chance of 15%%. It is considered light armor, weighs 20 pounds, and it allows the wearer to use fly on command (as the spell) once per day. Faint transmutation [good]; CL 5th

### Demon Armor

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** MAGIC_COST|34610.Masterwork (Armor).PLUS4A.STEEL
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **BONUS:** VAR|NegLevels|1
- **SPROP:** This plate armor is fashioned to make the wearer appear to be a demon. The helmet is shaped to look like a horned demon head, and its wearer looks out of the open, tooth-filled mouth. This +4 full plate allows the wearer to make claw attacks that deal 1d10 points of damage, strike as +1 weapons, and afflict the target as if she had been struck by a contagion spell (Fortitude DC 14 negates). Use of contagion requires a normal melee attack with the claws. The "claws" are built into the armor's vambraces and gauntlets. The armor bestows one negative level on any nonevil creature wearing it. This negative level persists as long as the armor is worn and disappears when the armor is removed. The negative level never results in actual level loss, but it cannot be overcome in any way (including restoration spells) while the armor is worn. Strong necromancy [evil]; CL 13th
- **AUTO:** EQUIP|Demon Armor Claw Attack

### Dragonhide Plate

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** DRACO
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** This suit of full plate is made of dragonhide, rather than metal, so druids can wear it. It is otherwise identical to masterwork full plate. No aura (nonmagical)

### Dwarven Plate

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** ADAMANT_ARMR_HVY
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **DR:** 3/-
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** This full plate is made of adamantine, giving its wearer damage reduction of 3/-. No aura (nonmagical)

### Elven Chain

- **PROFICIENCY:** ARMOR|Chainmail
- **COST:** 150
- **WT:** 40
- **ACCHECK:** -5
- **EQMOD:** MITHRAL_ARMR_MED
- **MAXDEX:** 2
- **SPELLFAILURE:** 30
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **SPROP:** This extremely light chainmail is made of very fine mithral links. Speed while wearing elven chain is 30 feet for Medium creatures, or 20 feet for Small. The armor has an arcane spell failure chance of 20%%, a maximum Dexterity bonus of +4, and an armor check penalty of -2. It is considered light armor and weighs 20 pounds. No aura (nonmagical)

### Mithral Full Plate of Speed

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** MAGIC_COST|15000.MITHRAL_ARMR_HVY.PLUS1A
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** As a free action, the wearer of this fine set of +1 mithral full plate can activate it, enabling her to act as though affected by a haste spell for up to 10 rounds each day. The duration of the haste effect need not be consecutive rounds. Speed while wearing a suit of mithral full plate is 20 feet for Medium creatures, or 15 feet for Small. The armor has an arcane spell failure chance of 25%%, a maximum Dexterity bonus of +3, and an armor check penalty of -3. It is considered medium armor (see Mithral, page 284) and weighs 25 pounds. Faint transmutation; CL 5th;

### Mithral Shirt

- **PROFICIENCY:** ARMOR|Chain Shirt
- **COST:** 100
- **WT:** 20
- **ACCHECK:** -2
- **EQMOD:** MITHRAL_ARMR_LT
- **MAXDEX:** 4
- **SPELLFAILURE:** 20
- **BONUS:** COMBAT|AC|4|TYPE=Armor
- **SPROP:** This extremely light chain shirt is made of very fine mithral links. Speed while wearing a mithral shirt is 30 feet for Medium creatures, or 20 feet for Small. The armor has an arcane spell failure chance of 10%%, a maximum Dexterity bonus of +6, and no armor check penalty. It is considered light armor (see Mithral, page 284) and weighs 10 pounds. No aura (nonmagical)

### Plate Armor of the Deep

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** MAGIC_COST|22000.Masterwork (Armor).PLUS1A.STEEL
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** This +1 full plate is decorated with a wave and fish motif. The wearer of plate armor of the deep is treated as unarmored for purposes of Swim checks. The wearer can breathe underwater and can converse with any creature with a language that breathes water. Moderate abjuration; CL 11th

### Rhino Hide

- **PROFICIENCY:** ARMOR|Hide
- **COST:** 15
- **WT:** 25
- **ACCHECK:** -3
- **EQMOD:** MAGIC_COST|1000.Masterwork (Armor).PLUS2A
- **MAXDEX:** 4
- **SPELLFAILURE:** 20
- **BONUS:** COMBAT|AC|3|TYPE=Armor
- **SPROP:** This +2 hide armor is made from rhinoceros hide. In addition to granting a +2 enhancement bonus to AC, it has a -1 armor check penalty and deals an additional 2d6 points of damage on any successful charge attack made by the wearer, including a mounted charge. Moderate transmutation; CL 9th

### Absorbing Shield

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 20
- **WT:** 15
- **ACCHECK:** -2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** MAGIC_COST|49000.Masterwork (Armor).PLUS1S.STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLFAILURE:** 15
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **SPROP:** This +1 heavy steel shield is flat black and seems to absorb light. Once every two days, on command, it can disintegrate an object that it touches, as the spell but requiring a melee touch attack. Strong transmutation; CL 17th

### Caster's Shield

- **PROFICIENCY:** SHIELD|Shield (Light)
- **COST:** 3
- **WT:** 5
- **ACCHECK:** -1
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d3
- **EQMOD:** MAGIC_COST|2000.Masterwork (Armor).PLUS1S.WOOD
- **WIELD:** Light
- **SIZE:** M
- **SPELLFAILURE:** 5
- **BONUS:** COMBAT|TOHIT|-1
- **BONUS:** COMBAT|AC|1|TYPE=Shield
- **SPROP:** This +1 light wooden shield has a small leather strip on the back on which a spellcaster can scribe a single spell as on a scroll. A spell so scribed has only half the base raw material cost (see page 287). Experience point and component costs remain the same. The strip cannot accommodate spells of higher than 3rd level. The strip is reusable. A caster's shield has a 5%% arcane spell failure chance. Moderate abjuration; CL 6th

### Darkwood Buckler

- **PROFICIENCY:** SHIELD|Buckler
- **COST:** 5
- **WT:** 5
- **SLOTS:** 0
- **ACCHECK:** -1
- **EQMOD:** DARK
- **SPELLFAILURE:** 5
- **BONUS:** COMBAT|AC|1|TYPE=Shield
- **SPROP:** This nonmagical light wooden shield is made out of darkwood and often favored by rogues and wizards. It has no enhancement bonus, but its construction material makes it lighter than a normal wooden shield. It weighs 2-1/2 pounds and has no armor check penalty. No aura (nonmagical);

### Darkwood Shield

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 7
- **WT:** 10
- **ACCHECK:** -2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** DARK
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLFAILURE:** 15
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **SPROP:** This nonmagical heavy wooden shield is made out of darkwood. It has no enhancement bonus, but its construction material makes it lighter than a normal wooden shield. It weighs 5 pounds and has no armor check penalty. No aura (nonmagical)

### Lion's Shield

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 20
- **WT:** 15
- **ACCHECK:** -2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** MAGIC_COST|5000.Masterwork (Armor).PLUS2S.STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLFAILURE:** 15
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **SPROP:** This +2 heavy steel shield is fashioned to appear to be a roaring lion's head. Three times per day as a free action, the lion's head can be commanded to attack (independently of the shield wearer), biting with the wielder's base attack bonus (including multiple attacks, if the wielder has them) and dealing 2d6 points of damage. This attack is in addition to any actions performed by the wielder. Moderate conjuration; CL 10th

### Mithral Heavy Shield

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 20
- **WT:** 15
- **ACCHECK:** -2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** MITHRAL_SHLD
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLFAILURE:** 15
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **SPROP:** This heavy shield is made of mithral and thus is much lighter than a standard steel shield. It has a 5%% arcane spell failure chance and no armor check penalty. It weighs 5 pounds. No aura (nonmagical)

### Spined Shield

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 20
- **WT:** 15
- **ACCHECK:** -2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **EQMOD:** MAGIC_COST|4410.Masterwork (Armor).PLUS1S.STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLFAILURE:** 15
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **SPROP:** This +1 heavy steel shield is covered in spines. It acts as a normal spiked shield. On command up to three times per day, the shield's wearer can fire one of the shield's spines. A fired spine has a +1 enhancement bonus, a range increment of 120 feet, and deals 1d10 points of damage (19-20/x2). Fired spines regenerate each day. Moderate evocation; CL 6th

### Winged Shield

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 7
- **WT:** 10
- **ACCHECK:** -2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** MAGIC_COST|8100.Masterwork (Armor).PLUS3S.WOOD
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLFAILURE:** 15
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Fly,14
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **SPROP:** This round heavy wooden shield has a +3 enhancement bonus. Small, feathered wings encircle the shield. Once per day it can be commanded to fly (as the spell), carrying the wielder. The shield can carry up to 133 pounds and move at 60 feet per round, or up to 266 pounds and move at 40 feet per round. Faint transmutation; CL 5th

### Demon Armor Claw Attack

- **PROFICIENCY:** WEAPON|Unarmed Strike
- **COST:** -2300
- **WT:** 0
- **ACCHECK:** -6
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d10
- **EQMOD:** Masterwork (Weapon).PLUS1W.STEEL
- **WIELD:** Light
- **SIZE:** M

### Longbow (Composite).COPY=Oathbow


### Adamantine Battleaxe

- **PROFICIENCY:** WEAPON|Battleaxe
- **COST:** 10
- **WT:** 6
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** ADAMANT_WEAP
- **WIELD:** OneHanded
- **SIZE:** M
- **SPROP:** This nonmagical axe is made out of adamantine. As a masterwork weapon, it has a +1 enhancement bonus on attack rolls. No aura (nonmagical)

### Adamantine Dagger

- **PROFICIENCY:** WEAPON|Dagger
- **COST:** 2
- **WT:** 1
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d4
- **EQMOD:** ADAMANT_WEAP
- **WIELD:** Light
- **RANGE:** 10
- **SIZE:** M
- **SPROP:** This nonmagical dagger is made out of adamantine. As a masterwork weapon, it has a +1 enhancement bonus on attack rolls. No aura (nonmagical)

### Assassin's Dagger

- **PROFICIENCY:** WEAPON|Dagger
- **COST:** 10302
- **WT:** 1
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d4
- **EQMOD:** STEEL
- **WIELD:** Light
- **RANGE:** 10
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** Adds +1 to the DC of a death attack
- **SPROP:** This wicked-looking, curved +2 dagger provides a +1 bonus to the DC of a Fortitude save forced by the death attack of an assassin. Moderate necromancy; CL 9th

### Dagger of Venom

- **PROFICIENCY:** WEAPON|Dagger
- **COST:** 8302
- **WT:** 1
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d4
- **EQMOD:** STEEL
- **WIELD:** Light
- **RANGE:** 10
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=4|Poison
- **SPROP:** Inflict a poison spell effect 1/day, fortitude save (DC 14)|!PRERULE:1,DisplayFullEquip
- **SPROP:** This black +1 dagger has a serrated edge. It allows the wielder to use a poison effect (as the spell, save DC 14) upon a creature struck by the blade once per day. The wielder can decide to use the power after he has struck. Doing so is a free action, but the poison effect must be invoked in the same round that the dagger strikes. Faint necromancy; CL 5th

### Dwarven Thrower

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 60312
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** Can be thrown and gains the returning special ability in the hands of a Dwarf, deals an extra 1d8 damage when hurled or an extra 2d8 against giants
- **SPROP:** Cannot be thrown except in the hands of a Dwarf
- **SPROP:** This weapon commonly functions as a +2 warhammer. In the hands of a dwarf, the warhammer gains an additional +1 enhancement bonus (for a total enhancement bonus of +3) and gains the returning special ability. It can be hurled with a 30-foot range increment. When hurled, it deals an extra 2d8 points of damage against giants or an extra 1d8 points of damage against any other target. Moderate evocation; CL 10th

### Flame Tongue

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 15
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** FLM_BR_M.MAGIC_COST|2400.PLUS1W.STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **SPROP:** Range touch attack ray inflicts 4d6 of fire damage on hit 1/day (30 ft. limit)
- **SPROP:** This is a +1 flaming burst longsword. Once per day, the sword can blast forth a fiery ray at any target within 30 feet as a ranged touch attack. The ray deals 4d6 points of fire damage on a successful hit. Moderate evocation; CL 12th

### Frost Brand

- **PROFICIENCY:** WEAPON|Greatsword
- **COST:** 54475
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 2d6
- **EQMOD:** STEEL
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **QUALITY:** Bright Illumination|20 ft.
- **QUALITY:** Shadowy Illumination|40 ft.
- **QUALITY:** Duration|below 0degreeF
- **SPROP:** Absorbs first 10 pts of fire damage on wielder each round, extinguish normal fires and may dispel some fire spells
- **SPROP:** This +3 frost greatsword sheds light as a torch when the temperature drops below 0degreeF. At such times it cannot be concealed when drawn, nor can its light be shut off. Its wielder is protected from fire; the sword absorbs the first 10 points of fire damage each round that the wielder would otherwise take. A frost brand extinguishes all nonmagical fires in its area. As a standard action, it can also dispel lasting fire spells such as wall of fire, but not instantaneous effects such as fireball, meteor swarm, and flame strike, though you must succeed on a dispel check (1d20 +14) against each spell to dispel it. The DC to dispel such spells is 11 + the caster level of the fire spell. Strong evocation; CL 14th

### Holy Avenger

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 120630
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **ABILITY:** Internal|AUTOMATIC|Holy Avenger Spell Resistance
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=PaladinLvl|Dispel Magic (Greater),19
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|5*(AllowHolyAvenger>=1)|TYPE=Enhancement
- **SPROP:** Spell resistance on wielder and anyone adjacent (5 + paladin's level)
- **SPROP:** Cold Iron - 30hp/inch and 10 hardness
- **SPROP:** good-aligned, +2d6 holy damage vs. evil
- **SPROP:** This +2 cold iron longsword becomes a +5 holy cold iron longsword in the hands of a paladin. It provides spell resistance of 5 + the paladin's level to the wielder and anyone adjacent to her. It also enables the wielder to use greater dispel magic (once per round as a standard action) at the class level of the paladin. (Only the area dispel is possible, not the targeted dispel or counterspell versions of greater dispel magic.) Strong abjuration; CL 18th

### Javelin of Lightning

- **PROFICIENCY:** WEAPON|Javelin
- **COST:** 1500
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **EQMOD:** WOOD
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** Becomes a 5d6 Lightning Bolt when thrown
- **SPROP:** This javelin becomes a 5d6 lightning bolt when thrown (Reflex DC 14 half ). It is consumed in the attack. Faint evocation; CL 5th

### Life Drinker

- **PROFICIENCY:** WEAPON|Greataxe
- **COST:** 40320
- **WT:** 12
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d12
- **EQMOD:** STEEL
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** Bestows 2 negative energy levels when deals damage, and 1 negative energy level on wielder
- **SPROP:** This +1 greataxe is favored by undead and constructs, who do not suffer its drawback. A life-drinker bestows two negative levels on its target whenever it deals damage, just as if its target had been struck by an undead creature. One day after being struck, subjects must make a DC 16 Fortitude save for each negative level or lose a character level. Each time a life-drinker deals damage to a foe, it also bestows one negative level on the wielder. Any negative level gained by the wielder in this fashion lasts for 1 hour. Strong necromancy; CL 13th

### Luck Blade (0 wishes)

- **PROFICIENCY:** WEAPON|Sword (Short)
- **COST:** 22060
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d6
- **EQMOD:** STEEL
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This +2 short sword gives its possessor a +1 luck bonus on all saving throws. Its possessor also gains the power of good fortune, usable once per day. This extraordinary ability allows its possessor to reroll one roll that she just made. She must take the result of the reroll, even if it's worse than the original roll. In addition, a luck blade may contain up to three wishes (when randomly rolled, a luck blade holds 1d4-1 wishes, minimum 0). When the last wish is used, the sword remains a +2 short sword, still grants the +1 luck bonus, and still grants its reroll power. Strong evocation; CL 17th
- **BONUS:** SAVE|Fortitude,Reflex,Will|1|TYPE=Luck

### Luck Blade (1 wish)

- **PROFICIENCY:** WEAPON|Sword (Short)
- **COST:** 62360
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d6
- **EQMOD:** CHARGED_ITEM_1|CHARGES[1].STEEL
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This +2 short sword gives its possessor a +1 luck bonus on all saving throws. Its possessor also gains the power of good fortune, usable once per day. This extraordinary ability allows its possessor to reroll one roll that she just made. She must take the result of the reroll, even if it's worse than the original roll. In addition, a luck blade may contain up to three wishes (when randomly rolled, a luck blade holds 1d4-1 wishes, minimum 0). When the last wish is used, the sword remains a +2 short sword, still grants the +1 luck bonus, and still grants its reroll power. Strong evocation; CL 17th
- **BONUS:** SAVE|Fortitude,Reflex,Will|1|TYPE=Luck

### Luck Blade (2 wishes)

- **PROFICIENCY:** WEAPON|Sword (Short)
- **COST:** 102660
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d6
- **EQMOD:** CHARGED_ITEM_2|CHARGES[2].STEEL
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This +2 short sword gives its possessor a +1 luck bonus on all saving throws. Its possessor also gains the power of good fortune, usable once per day. This extraordinary ability allows its possessor to reroll one roll that she just made. She must take the result of the reroll, even if it's worse than the original roll. In addition, a luck blade may contain up to three wishes (when randomly rolled, a luck blade holds 1d4-1 wishes, minimum 0). When the last wish is used, the sword remains a +2 short sword, still grants the +1 luck bonus, and still grants its reroll power. Strong evocation; CL 17th
- **BONUS:** SAVE|Fortitude,Reflex,Will|1|TYPE=Luck

### Luck Blade (3 wishes)

- **PROFICIENCY:** WEAPON|Sword (Short)
- **COST:** 142960
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d6
- **EQMOD:** CHARGED_ITEM_3|CHARGES[3].STEEL
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This +2 short sword gives its possessor a +1 luck bonus on all saving throws. Its possessor also gains the power of good fortune, usable once per day. This extraordinary ability allows its possessor to reroll one roll that she just made. She must take the result of the reroll, even if it's worse than the original roll. In addition, a luck blade may contain up to three wishes (when randomly rolled, a luck blade holds 1d4-1 wishes, minimum 0). When the last wish is used, the sword remains a +2 short sword, still grants the +1 luck bonus, and still grants its reroll power. Strong evocation; CL 17th
- **BONUS:** SAVE|Fortitude,Reflex,Will|1|TYPE=Luck

### Mace of Smiting

- **PROFICIENCY:** WEAPON|Mace (Heavy)
- **COST:** 75312
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** ADAMANT_WEAP.MAGIC_COST|-3000
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **SPROP:** +5 against constructs, critical destroys construct, critical X4 against outsiders
- **SPROP:** This +3 adamantine heavy mace has a +5 enhancement bonus against constructs, and any critical hit dealt to a construct completely destroys it (no saving throw). A critical hit dealt to an outsider deals *4 damage rather than *2. Moderate transmutation; CL 11th

### Mace of Terror

- **PROFICIENCY:** WEAPON|Mace (Heavy)
- **COST:** 38552
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** Create a 30 feet cone terrifying aura, as spell 3/day
- **SPROP:** On command, this +2 heavy mace causes the wielder's clothes and appearance to transform into an illusion of darkest horror such that living creatures in a 30-foot cone become panicked as if by a fear spell (Will DC 16 partial). They take a -2 morale penalty on saving throws, and they flee from the wielder. The wielder may use this ability up to three times per day. Strong necromancy; CL 13th

### Masterwork Cold Iron Longsword

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 15
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** C_IRON.Masterwork (Weapon)
- **WIELD:** OneHanded
- **SIZE:** M
- **SPROP:** This nonmagical longsword is crafted out of cold iron. As a masterwork weapon, it has a +1 enhancement bonus on attack rolls. No aura (nonmagical)

### Nine Lives Stealer

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 23057
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** CHARGED_ITEM_9|CHARGES[9].STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|2
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** Draws lifeforce on opponent when critical hits, (DC 20 or dead), 2 negative energy levels on wielder if not evil
- **SPROP:** This longsword always performs as a +2 longsword, but it also has the power to draw the life force from an opponent. It can do this nine times before the ability is lost. At that point, the sword becomes a simple +2 longsword (with a hint of evil about it). A critical hit must be dealt for the sword's death-dealing ability to function, and this weapon has no effect on creatures not subject to critical hits. The victim is entitled to a DC 20 Fortitude save to avoid death. If the save is successful, the sword's death-dealing ability does not function, no use of the ability is expended, and normal critical damage is determined. This sword is evil, and any good character attempting to wield it gains two negative levels. These negative levels remain as long as the sword is in hand and disappear when the sword is no longer wielded. These negative levels never result in actual level loss, but they cannot be overcome in any way (including restoration spells) while the sword is wielded. Strong necromancy [evil]; CL 13th

### Rapier of Puncturing

- **PROFICIENCY:** WEAPON|Rapier
- **COST:** 50320
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 3
- **DAMAGE:** 1d6
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** Allows the wielder to make a touch attack that deals 1d6 of Constitution damage
- **SPROP:** Three times per day, this +2 wounding rapier allows the wielder to make a touch attack with the weapon that deals 1d6 points of Constitution damage by draining blood. Creatures immune to critical hits are immune to the Constitution damage dealt by this weapon. Strong necromancy; CL 13th

### Screaming Bolt

- **COST:** 267
- **WT:** 0.1
- **BASEQTY:** 1
- **EQMOD:** STEEL.WOOD
- **MODS:** YES
- **BONUS:** WEAPON|DAMAGE,TOHIT|2
- **SPROP:** One of these +2 bolts screams when fired, forcing all enemies of the wielder within 20 feet of the path of the bolt to succeed on a DC 14 Will save or become shaken. This is a mindaffecting fear effect. Faint enchantment; CL 5th

### Shatterspike

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 4315
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|4|TYPE=Enhancement
- **SPROP:** Wielder with Improved Sunder could damage +4 and lower weapons
- **SPROP:** Wielders without the Improved Sunder feat use Shatterspike as a +1 longsword only; wielders with the Improved Sunder feat add a +4 bonus (including the sword's +1 enhancement bonus) to the opposed roll when attempting to strike a foe's weapon. If successful, Shatterspike deals 1d8+4 points of damage plus the wielder's Strength modifier to the target weapon (the target weapon's hardness must still be overcome with each hit). Shatterspike can damage weapons with an enhancement bonus of +4 or lower. Strong evocation; CL 13th

### Shifter's Sorrow

- **PROFICIENCY:** WEAPON|Sword (Two-Bladed)
- **COST:** 12780
- **WT:** 10
- **SLOTS:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **ALTEQMOD:** STEEL
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** Deals 2d6 add damage against shapechanger creatures
- **SPROP:** This +1/+1 two-bladed sword has blades of alchemical silver. The weapon deals an extra 2d6 points of damage against any creature with the shapechanger subtype. When a shapechanger or a creature in an alternate form (such as a druid using wild shape) is struck by the weapon, it must make a DC 15 Will save or return to its natural form. Strong transmutation; CL 15th

### Silver Dagger, Masterwork

- **PROFICIENCY:** WEAPON|Dagger
- **COST:** 2
- **WT:** 1
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d4
- **EQMOD:** ALCHM.Masterwork (Weapon)
- **WIELD:** Light
- **RANGE:** 10
- **SIZE:** M
- **SPROP:** This masterwork alchemical silver dagger is nonmagical. As a masterwork weapon, it has a +1 enhancement bonus on attack rolls. No aura (nonmagical)

### Slaying Arrow

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** DO NOT USE! - replace with a *specific* Slaying arrow that specifies an actual type of creature. Any type or subtype of creature must made a fortitude save (DC 20) or dies (or be destroyed) instantly when hit

### Slaying Arrow (Aberrations)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Animals)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Constructs)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Dragons)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Elementals)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Fey)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Giants)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (aquatic))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (dwarf))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (elf))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (gnoll))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (gnome))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (goblinoid))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (halfling))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (human))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (reptilian))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Humanoids (orc))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Magical beasts)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Monstrous humanoids)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Oozes)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (air))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (chaotic))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (earth))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (evil))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (fire))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (good))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (lawful))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Outsiders (water))

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Plants)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Undead)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Vermin)

- **COST:** 2282
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 20 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** DO NOT USE! - replace with a *specific* Slaying arrow that specifies an actual type of creature. Any type or subtype of creature must made a fortitude save (DC 23) or dies (or be destroyed) instantly when hit

### Slaying Arrow (Greater/Aberrations)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Animals)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Constructs)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Dragons)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Elementals)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Fey)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Giants)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (aquatic))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (dwarf))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (elf))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (gnoll))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (gnome))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (goblinoid))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (halfling))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (human))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (reptilian))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Humanoids (orc))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Magical beasts)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Monstrous humanoids)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Oozes)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (air))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (chaotic))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (earth))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (evil))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (fire))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (good))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (lawful))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Outsiders (water))

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Plants)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Undead)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Slaying Arrow (Greater/Vermin)

- **COST:** 4057
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is keyed to a particular type or subtype of creature. If it strikes such a creature, the target must make a DC 23 Fortitude save or die (or, in the case of unliving targets, be destroyed) instantly. Note that even creatures normally exempt from Fortitude saves (undead and constructs) are subject to this attack. When keyed to a living creature, this is a death effect (and thus death ward protects a target). Strong necromancy; CL 13th

### Sleep Arrow

- **COST:** 132
- **WT:** 0.15
- **EQMOD:** STEEL.WOOD
- **BONUS:** WEAPON|DAMAGE,TOHIT|1
- **SPROP:** This +1 arrow is painted white and has white fletching. If it strikes a foe so that it would normally deal damage, it instead bursts into magical energy that deals nonlethal damage (in the same amount as would be lethal damage) and forces the target to make a DC 11 Will save or fall asleep. Faint enchantment; CL 5th

### Sun Blade (Bastard)

- **PROFICIENCY:** WEAPON|Sword (Bastard)
- **COST:** 50335
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d10
- **EQMOD:** STEEL
- **WIELD:** Light
- **SIZE:** M
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|1
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This sword is the size of a bastard sword but handles like a short sword. This +2 weapon becomes +4 against evil creatures, and against Negative Energy Plane or undead creatures it deals double damage (and *3 on a crit). Once per day, by swinging the blade vigorously above your head and speaking the command word, the sword sheds a bright yellow radiance that is like full daylight. This starts at a 10-foot radiance +5ft/rnd for 10 rounds, staying at 60' globe of light until you stop swinging, whereupon it fades to a dim glow for 1 minute. The sword is good aligned, and any evil creature wielding it gains one negative level. (DMG P228) Moderate evocation; CL 10th

### Sun Blade (Short)

- **PROFICIENCY:** WEAPON|Sword (Short)
- **COST:** 50335
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d10
- **EQMOD:** STEEL
- **WIELD:** Light
- **SIZE:** M
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|1
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This sword is the size of a bastard sword but handles like a short sword. This +2 weapon becomes +4 against evil creatures, and against Negative Energy Plane or undead creatures it deals double damage (and *3 on a crit). Once per day, by swinging the blade vigorously above your head and speaking the command word, the sword sheds a bright yellow radiance that is like full daylight. This starts at a 10-foot radiance +5ft/rnd for 10 rounds, staying at 60' globe of light until you stop swinging, whereupon it fades to a dim glow for 1 minute. The sword is good aligned, and any evil creature wielding it gains one negative level. (DMG P228) Moderate evocation; CL 10th

### Sword of Life Stealing

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 25715
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This black iron +2 longsword bestows a negative level when it deals a critical hit. The sword wielder gains 1d6 temporary hit points each time a negative level is bestowed on another. These temporary hit points last for 24 hours. One day after being struck, subjects must make a DC 16 Fortitude save for each negative level or lose a character level. Strong necromancy; CL 17th

### Sword of the Planes

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 22315
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** This longsword has an enhancement bonus of +1 on the Material Plane, but on any Elemental Plane its enhancement bonus increases to +2. (The +2 enhancement bonus also applies on the Material Plane when the weapon is used against elementals.) It operates as a +3 longsword on the Astral Plane or the Ethereal Plane or when used against opponents native to either of those planes. On any other plane, or against any outsider, it functions as a +4 longsword. Strong evocation; CL 15th

### Sword of Subtlety

- **PROFICIENCY:** WEAPON|Sword (Short)
- **COST:** 22310
- **WT:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d6
- **EQMOD:** STEEL
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** A +1 short sword with a thin, dull gray blade, this weapon provides a +4 bonus on its wielder's attack and damage rolls when he is making a sneak attack with it. Moderate illusion; CL 7th

### Sylvan Scimitar

- **PROFICIENCY:** WEAPON|Scimitar
- **COST:** 47315
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 3
- **DAMAGE:** 1d6
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **ABILITY:** FEAT|VIRTUAL|Cleave
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **SPROP:** This +3 scimitar, when used outdoors in a temperate climate, grants its wielder the use of the Cleave feat and deals an extra 1d6 points of damage. Moderate evocation; CL 11th

### Trident of Fish Command

- **PROFICIENCY:** WEAPON|Trident
- **COST:** 18650
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **RANGE:** 10
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** The magical properties of this +1 trident with a 6-foot-long haft enable its wielder to charm up to 14 HD of aquatic animals (Will DC 16 negates, animals get a +5 bonus if currently under attack by the wielder or his allies), no two of which can be more than 30 feet apart. The wielder can use this effect up to three times per day. The wielder can communicate with the animals as if using a speak with animals spell. Animals making their saving throw are free of control, but they will not approach within 10 feet of the trident. The trident can be used up to three times per day. Moderate enchantment; CL 7th

### Trident of Warning

- **PROFICIENCY:** WEAPON|Trident
- **COST:** 10115
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **RANGE:** 10
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** A weapon of this type enables its wielder to determine the location, depth, kind, and number of aquatic predators within 680 feet. A trident of warning must be grasped and pointed in order for the character using it to gain such information, and it requires 1 round to scan a hemisphere with a radius of 680 feet. The weapon is otherwise a +2 trident. Moderate divination; CL 7th

### Arcane Archer (Arrow of Death)

- **COST:** 0
- **WT:** 0.15
- **PRECLASS:** 1,Arcane Archer=10
- **BASEQTY:** 1
- **EQMOD:** STEEL.WOOD
- **MODS:** NO
- **BONUS:** WEAPON|TOHIT|-50|!PRECLASS:1,Arcane Archer=10
- **SPROP:** At 10th level, an arcane archer can create an arrow of death that forces the target, if damaged by the arrow's attack, to make a DC 20 Fortitude save or be slain immediately. It takes one day to make an arrow of death, and the arrow only functions for the arcane archer who created it. The arrow of death lasts no longer than one year, and the archer can only have one such arrow in existence at a time.

### Potion (Cure Light Wounds)

- **COST:** 50
- **WT:** 0
- **SPROP:** Cures 1d8 +1 damage (PH P.216)

### Potion (Endure Elements)

- **COST:** 50
- **WT:** 0
- **SPROP:** Suffer no harm from hot or cold environment (-50 to 140 degrees Fahrenheit) for 24 hours

### Potion (Hide from Animals)

- **COST:** 50
- **WT:** 0

### Potion (Hide from Undead)

- **COST:** 50
- **WT:** 0

### Potion (Jump)

- **COST:** 50
- **WT:** 0
- **SPROP:** +10 enhancement bonus to jump skill for 3 minutes

### Potion (Mage Armor)

- **COST:** 50
- **WT:** 0

### Potion (Magic Fang)

- **COST:** 50
- **WT:** 0

### Potion (Oil of Magic Stone)

- **COST:** 50
- **WT:** 0

### Potion (Oil of Magic Weapon)

- **COST:** 50
- **WT:** 0

### Potion (Pass without Trace)

- **COST:** 50
- **WT:** 0
- **SPROP:** You can move through any type of terrain and leave neither footprints nor scent. Tracking you is impossible by nonmagical means for 1 hour.

### Potion (Protection from Chaos)

- **COST:** 50
- **WT:** 0

### Potion (Protection from Evil)

- **COST:** 50
- **WT:** 0
- **SPROP:** +2 deflection bonus to Ac and +2 resistance bonus on saves against evil creatures, for 3 minutes (PH 266)

### Potion (Protection from Good)

- **COST:** 50
- **WT:** 0

### Potion (Protection from Law)

- **COST:** 50
- **WT:** 0

### Potion (Remove Fear)

- **COST:** 50
- **WT:** 0

### Potion (Sanctuary)

- **COST:** 50
- **WT:** 0

### Potion (Shield of Faith +2)

- **COST:** 50
- **WT:** 0
- **SPROP:** +2 deflection bonus to AC for 1 minute

### Potion (Oil of Shillelagh)

- **COST:** 50
- **WT:** 0

### Potion (Oil of Bless Weapon)

- **COST:** 100
- **WT:** 0

### Potion (Enlarge Person)

- **COST:** 250
- **SPROP:** Double height and multiply weight by 8. +2 Str, -2 Dex, -1 Attack & AC for 1 minute (PH P.226)
- **WT:** 0

### Potion (Reduce Person)

- **SPROP:** Drinker is halved in height/weight/width and weight is reduced to 1/8th. Size category is reduced by 1, the target gains +2 size bonus to dex, -2 Str and +1 bonus to attack and AC. Lasts 1 minute (PH 269)
- **COST:** 250
- **WT:** 0

### Potion (Aid)

- **COST:** 300
- **WT:** 0
- **SPROP:** +1 Morale bonus to attack and save vs fear, +1d8+3 temporary HP for 3 minutes (PH P196)

### Potion (Barkskin +2)

- **COST:** 300
- **WT:** 0
- **SPROP:** +2 AC for 30 minutes

### Potion (Bear's Endurance)

- **COST:** 300
- **WT:** 0
- **SPROP:** Gain +4 Con for 3 minutes. (PH P.203)

### Potion (Blur)

- **COST:** 300
- **WT:** 0
- **SPROP:** 20%% concealment for 1 minute

### Potion (Bull's Strength)

- **COST:** 300
- **WT:** 0
- **SPROP:** Gain +4 Str for 3 mnutes. (PH P.207)

### Potion (Cat's Grace)

- **COST:** 300
- **WT:** 0
- **SPROP:** Gain +4 Dex for 3 minutes. (PH P.208)

### Potion (Cure Moderate Wounds)

- **COST:** 300
- **WT:** 0
- **SPROP:** Cures 2d8 +3 damage (PH P.216)

### Potion (Oil of Darkness)

- **COST:** 300
- **WT:** 0

### Potion (Darkvision)

- **COST:** 300
- **WT:** 0
- **SPROP:** You gain 60' darkvision for 1 hour (PH P.216)

### Potion (Delay Poison)

- **COST:** 300
- **WT:** 0
- **SPROP:** You become immune to poison for 2 hours (PH P.217)

### Potion (Eagle's Splendor)

- **COST:** 300
- **WT:** 0

### Potion (Fox's Cunning)

- **COST:** 300
- **WT:** 0
- **SPROP:** Gain +4 intelligence for 2 minutes. (PH P.233)

### Potion (Invisibility)

- **SPROP:** Invisible for 3 minutes or until you attack (PH P.245)
- **COST:** 300
- **WT:** 0

### Potion (Oil of Invisibility)

- **COST:** 300
- **WT:** 0

### Potion (Lesser Restoration)

- **COST:** 300
- **WT:** 0
- **SPROP:** Dispel any magical effect reducing one ability score, or cure 1d4 temporary ability damage to one score. Also removes fatigue and improves exhausted condition to fatigued.

### Potion (Levitate)

- **COST:** 300
- **WT:** 0
- **SPROP:** for 3 minutes you, or an object within 30' (upto 300lb) can move up or down at 20' round as a move action. Combat is unstable, gaining a penalty of -1 on attack rolls each round, up to -5. PH P.248

### Potion (Oil of Levitate)

- **COST:** 300
- **WT:** 0

### Potion (Misdirection)

- **COST:** 300
- **WT:** 0

### Potion (Owl's Wisdom)

- **COST:** 300
- **WT:** 0

### Potion (Protection from Arrows 10/magic)

- **COST:** 300
- **WT:** 0

### Potion (Remove Paralysis)

- **COST:** 300
- **WT:** 0

### Potion (Resist Energy 10/Acid)

- **COST:** 300
- **WT:** 0
- **SPROP:** You have DR10 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 10/Cold)

- **COST:** 300
- **WT:** 0
- **SPROP:** You have DR10 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 10/Electricity)

- **COST:** 300
- **WT:** 0
- **SPROP:** You have DR10 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 10/Fire)

- **COST:** 300
- **WT:** 0
- **SPROP:** You have DR10 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 10/Sonic)

- **COST:** 300
- **WT:** 0
- **SPROP:** You have DR10 for 30 minutes against damage of this kind (PH p272)

### Potion (Shield of Faith +3)

- **COST:** 300
- **WT:** 0
- **SPROP:** +3 deflection bonus to AC for 6 minutes

### Potion (Spider Climb)

- **COST:** 300
- **WT:** 0
- **SPROP:** Climb and travel on vertical surfaces and ceilings without needing a climb check. Climb speed of 20 feet for 30 minutes, cannot run while climbing.

### Potion (Undetectable Alignment)

- **COST:** 300
- **WT:** 0

### Potion (Barkskin +3)

- **COST:** 600
- **WT:** 0

### Potion (Shield of Faith +4)

- **COST:** 600
- **WT:** 0
- **SPROP:** +4 deflection bonus to AC for 12 minutes

### Potion (Resist Energy 20/Acid)

- **COST:** 700
- **WT:** 0
- **SPROP:** You have DR20 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 20/Cold)

- **COST:** 700
- **WT:** 0
- **SPROP:** You have DR20 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 20/Electricity)

- **COST:** 700
- **WT:** 0
- **SPROP:** You have DR20 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 20/Fire)

- **COST:** 700
- **WT:** 0
- **SPROP:** You have DR20 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 20/Sonic)

- **COST:** 700
- **WT:** 0
- **SPROP:** You have DR20 for 30 minutes against damage of this kind (PH p272)

### Potion (Cure Serious Wounds)

- **COST:** 750
- **WT:** 0
- **SPROP:** Cures 3d8+5 damage (PH P.216)

### Potion (Oil of Daylight)

- **COST:** 750
- **WT:** 0

### Potion (Displacement)

- **COST:** 750
- **WT:** 0

### Potion (Oil of Flame Arrow)

- **COST:** 750
- **WT:** 0

### Potion (Fly)

- **COST:** 750
- **WT:** 0

### Potion (Gaseous Form)

- **COST:** 750
- **WT:** 0
- **SPROP:** You and all your gear become insubstantial, misty and translucent for 10 minutes. Gain DR 10/magic, fly at speed 10 and can pass through small holes. (PH P.234)

### Potion (Greater Magic Fang +1)

- **COST:** 750
- **WT:** 0

### Potion (Oil of Greater Magic Weapon +1)

- **COST:** 750
- **WT:** 0

### Potion (Haste)

- **COST:** 750
- **WT:** 0
- **SPROP:** You gain +1 bonus to attack rolls, +1 dodge bonus to AC and Reflex Saves. Your movement increases by 30'. When making a full attack action you may make one extra attack at your full base attack bonus. This lasts 5 rounds.

### Potion (Heroism)

- **COST:** 750
- **WT:** 0
- **SPROP:** +2 Morale bonus to attack rolls, saves and skill checks for 30 minutes.

### Potion (Oil of Keen Edge)

- **COST:** 750
- **WT:** 0

### Potion (Magic Circle against Chaos)

- **COST:** 750
- **WT:** 0

### Potion (Magic Circle against Evil)

- **COST:** 750
- **WT:** 0

### Potion (Magic Circle against Good)

- **COST:** 750
- **WT:** 0

### Potion (Magic Circle against Law)

- **COST:** 750
- **WT:** 0

### Potion (Oil of Magic Vestment +1)

- **COST:** 750
- **WT:** 0

### Potion (Neutralize Poison)

- **SPROP:** Neutralize any existing poison and prevent any poison from affecting the drinker for 30 minutes (PH 257)
- **COST:** 750
- **WT:** 0

### Potion (Nondetection)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Nondetection
- **SPROP:** Difficult to detect by divination spells for 5 hours (PH P.245)
- **COST:** 750
- **WT:** 0

### Potion (Protection from Energy/Acid)

- **COST:** 750
- **WT:** 0

### Potion (Protection from Energy/Cold)

- **COST:** 750
- **WT:** 0

### Potion (Protection from Energy/Electricity)

- **COST:** 750
- **WT:** 0

### Potion (Protection from Energy/Fire)

- **COST:** 750
- **WT:** 0

### Potion (Protection from Energy/Sonic)

- **COST:** 750
- **WT:** 0

### Potion (Rage)

- **COST:** 750
- **WT:** 0
- **SPROP:** +2 Morale bonus to Strength and Constitution, +1 Morale bonus to Will saves and -2 AC, lasts 5 rounds

### Potion (Remove Blindness/Deafness)

- **COST:** 750
- **WT:** 0

### Potion (Remove Curse)

- **COST:** 750
- **WT:** 0
- **SPROP:** Remove curse instantaneously removes all curses on an object or a creature

### Potion (Remove Disease)

- **SPROP:** Cures all diseases, kills parasites including green slime. Does not prevent reinfection (PH 271)
- **COST:** 750
- **WT:** 0

### Potion (Tongues)

- **COST:** 750
- **WT:** 0
- **SPROP:** for 50 minutes you can speak and understand the language of any intelligent creature. (PH 294)

### Potion (Water Breathing)

- **COST:** 750
- **WT:** 0
- **SPROP:** You can breathe underwater for 6 hours (PH P300).

### Potion (Water Walk)

- **COST:** 750
- **WT:** 0

### Potion (Barkskin +4)

- **COST:** 900
- **WT:** 0

### Potion (Shield of Faith +5)

- **COST:** 900
- **WT:** 0
- **SPROP:** +5 deflection bonus to AC for 18 minutes

### Potion (Good Hope)

- **COST:** 1050
- **WT:** 0

### Potion (Resist Energy 30/Acid)

- **COST:** 1100
- **WT:** 0
- **SPROP:** You have DR30 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 30/Cold)

- **COST:** 1100
- **WT:** 0
- **SPROP:** You have DR30 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 30/Electricity)

- **COST:** 1100
- **WT:** 0
- **SPROP:** You have DR30 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 30/Fire)

- **COST:** 1100
- **WT:** 0
- **SPROP:** You have DR30 for 30 minutes against damage of this kind (PH p272)

### Potion (Resist Energy 30/Sonic)

- **COST:** 1100
- **WT:** 0
- **SPROP:** You have DR30 for 30 minutes against damage of this kind (PH p272)

### Potion (Barkskin +5)

- **COST:** 1200
- **WT:** 0

### Potion (Greater Magic Fang +2)

- **COST:** 1200
- **WT:** 0

### Potion (Oil of Greater Magic Weapon +2)

- **COST:** 1200
- **WT:** 0

### Potion (Oil of Magic Vestment +2)

- **COST:** 1200
- **WT:** 0

### Potion (Protection from Arrows 15/magic)

- **COST:** 1500
- **WT:** 0

### Potion (Greater Magic Fang +3)

- **COST:** 1800
- **WT:** 0

### Potion (Oil of Greater Magic Weapon +3)

- **COST:** 1800
- **WT:** 0

### Potion (Oil of Magic Vestment +3)

- **COST:** 1800
- **WT:** 0

### Potion (Greater Magic Fang +4)

- **COST:** 2400
- **WT:** 0

### Potion (Oil of Greater Magic Weapon +4)

- **COST:** 2400
- **WT:** 0

### Potion (Oil of Magic Vestment +4)

- **COST:** 2400
- **WT:** 0

### Potion (Greater Magic Fang +5)

- **COST:** 3000
- **WT:** 0

### Potion (Oil of Greater Magic Weapon +5)

- **COST:** 3000
- **WT:** 0

### Potion (Oil of Magic Vestment +5)

- **COST:** 3000
- **WT:** 0

### Ring of Animal Friendship

- **COST:** 10800
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Charm Animal
- **SPROP:** On command, this ring affects an animal as if the wearer had cast charm animal. Faint enchantment; CL 3rd

### Ring of Blinking

- **COST:** 27000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=7|Blink
- **SPROP:** On command, this ring makes the wearer blink, as with the blink spell (Physical attacks and targetted spells have 50%% miss chance, your own spells have a 20%% miss chance too. Half damage from area affects and falling. Can step through solid objects, 50%% per 5' chance of becoming material and taking damage/being shunted to nearest open space , PHB P206). Moderate transmutation; CL 7th
- **ABILITY:** Special Ability|VIRTUAL|Concealment Chance
- **BONUS:** VAR|ConcealmentChance|50

### Ring of Chameleon Power

- **COST:** 12700
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Disguise Self
- **BONUS:** SKILL|Hide|10|TYPE=Competence
- **SPROP:** As a free action, the wearer of this ring can gain the ability to magically blend in with the surroundings. This provides a +10 competence bonus on her Hide checks. As a standard action, she can also command the ring to utilize the spell disguise self as often as she wants. Faint illusion; CL 3rd

### Ring of Climbing

- **COST:** 2500
- **WT:** 0
- **BONUS:** SKILL|Climb|5|TYPE=Competence
- **SPROP:** This ring is actually a magic leather cord that ties around a finger. It continually grants the wearer a +5 competence bonus on Climb checks. Faint transmutatation; CL 5th

### Ring of Climbing (Improved)

- **COST:** 10000
- **WT:** 0
- **BONUS:** SKILL|Climb|10|TYPE=Competence
- **SPROP:** As climbing, except it grants a +10 competence bonus on its wearer's Climb checks. Faint transmutation; CL 5th

### Ring of Counterspells

- **COST:** 4000
- **WT:** 0
- **SPROP:** This ring might seem to be a ring of spell storing upon first examination. However, while it allows a single spell of 1st through 6th level to be cast into it, that spell cannot be cast out of the ring again. Instead, should that spell ever be cast upon the wearer, the spell is immediately countered, as a counterspell action, requiring no action (or even knowledge) on the wearer's part. Once so used, the spell cast within the ring is gone. A new spell (or the same one as before) may be placed in it again. Moderate evocation; CL 11th

### Ring of Djinni Calling

- **COST:** 125000
- **WT:** 0
- **SPROP:** One of the many rings of fable, this "genie" ring is most useful indeed. It serves as a special gate by means of which a specific djinni can be called from the Elemental Plane of Air. When the ring is rubbed (a standard action), the call goes out, and the djinni appears on the next round. The djinni faithfully obeys and serves the wearer of the ring, but never for more than 1 hour per day. If the djinni of the ring is ever killed, the ring becomes nonmagical and worthless. See the Monster Manual for details of a djinni's abilities. Strong conjuration; CL 17th

### Ring of Elemental Command (Air)

- **COST:** 200000
- **WT:** 0
- **SPROP:** All four kinds of elemental command rings are very powerful. Each appears to be nothing more than a lesser magic ring until fully activated (see below), but each has certain other powers as well as the following common properties. Elementals of the plane to which the ring is attuned can't attack the wearer, or even approach within 5 feet of him. If the wearer desires, he may forego this protection and instead attempt to charm the elemental (as charm monster, Will DC 17 negates). If the charm attempt fails, however, absolute protection is lost and no further attempt at charming can be made. Creatures from the plane to which the ring is attuned who attack the wearer take a -1 penalty on their attack rolls. The ring wearer makes applicable saving throws from the extraplanar creature's attacks with a +2 resistance bonus. He gains a +4 morale bonus on all attack rolls against such creatures. Any weapon he uses bypasses the damage reduction of such creatures, regardless of any qualities the weapon may or may not have. The wearer of the ring is able to converse with creatures from the plane to which his ring is attuned. These creatures recognize that he wears the ring. They show a healthy respect for the wearer if alignments are similar. If alignments are opposed, creatures fear the wearer if he is strong. If he is weak, they hate and desire to slay him. Fear, hatred, and respect are determined by the DM. The possessor of a ring of elemental command takes a saving throw penalty as follows: -2 against earth-based effects.
- **SPROP:** . Feather fall (unlimited use, wearer only) . Resist energy (electricity) (unlimited use, wearer only) . Gust of wind (twice per day) . Wind wall (unlimited use) . Air walk (once per day, wearer only) . Chain lightning (once per week) The ring appears to be a ring of feather falling until a certain condition is met, such as having the ring immersed in holy water, single-handedly slaying an air elemental, or whatever the DM determines necessary to activate its full potential. It must be reactivated each time a new wearer acquires it. Strong conjuration; CL 15th.

### Ring of Elemental Command (Earth)

- **COST:** 200000
- **WT:** 0
- **SPROP:** All four kinds of elemental command rings are very powerful. Each appears to be nothing more than a lesser magic ring until fully activated (see below), but each has certain other powers as well as the following common properties. Elementals of the plane to which the ring is attuned can't attack the wearer, or even approach within 5 feet of him. If the wearer desires, he may forego this protection and instead attempt to charm the elemental (as charm monster, Will DC 17 negates). If the charm attempt fails, however, absolute protection is lost and no further attempt at charming can be made. Creatures from the plane to which the ring is attuned who attack the wearer take a -1 penalty on their attack rolls. The ring wearer makes applicable saving throws from the extraplanar creature's attacks with a +2 resistance bonus. He gains a +4 morale bonus on all attack rolls against such creatures. Any weapon he uses bypasses the damage reduction of such creatures, regardless of any qualities the weapon may or may not have. The wearer of the ring is able to converse with creatures from the plane to which his ring is attuned. These creatures recognize that he wears the ring. They show a healthy respect for the wearer if alignments are similar. If alignments are opposed, creatures fear the wearer if he is strong. If he is weak, they hate and desire to slay him. Fear, hatred, and respect are determined by the DM. The possessor of a ring of elemental command takes a saving throw penalty as follows: -2 against air- or electricity-based effects.
- **SPROP:** . Meld into stone (unlimited use, wearer only) . Soften earth or stone (unlimited use) . Stone shape (twice per day) . Stoneskin (once per week, wearer only) . Passwall (twice per week) . Wall of stone (once per day) The ring appears to be a ring of meld into stone until the DMestablished condition is met. Strong conjuration; CL 15th.

### Ring of Elemental Command (Fire)

- **COST:** 200000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)
- **BONUS:** VAR|FireResistanceBonusSp|20|TYPE=Base
- **SPROP:** All four kinds of elemental command rings are very powerful. Each appears to be nothing more than a lesser magic ring until fully activated (see below), but each has certain other powers as well as the following common properties. Elementals of the plane to which the ring is attuned can't attack the wearer, or even approach within 5 feet of him. If the wearer desires, he may forego this protection and instead attempt to charm the elemental (as charm monster, Will DC 17 negates). If the charm attempt fails, however, absolute protection is lost and no further attempt at charming can be made. Creatures from the plane to which the ring is attuned who attack the wearer take a -1 penalty on their attack rolls. The ring wearer makes applicable saving throws from the extraplanar creature's attacks with a +2 resistance bonus. He gains a +4 morale bonus on all attack rolls against such creatures. Any weapon he uses bypasses the damage reduction of such creatures, regardless of any qualities the weapon may or may not have. The wearer of the ring is able to converse with creatures from the plane to which his ring is attuned. These creatures recognize that he wears the ring. They show a healthy respect for the wearer if alignments are similar. If alignments are opposed, creatures fear the wearer if he is strong. If he is weak, they hate and desire to slay him. Fear, hatred, and respect are determined by the DM. The possessor of a ring of elemental command takes a saving throw penalty as follows: -2 against water- or cold-based effects.
- **SPROP:** . Resist energy (fire) (as a major ring of energy resistance [fire]) . Burning hands (unlimited use) . Flaming sphere (twice per day) . Pyrotechnics (twice per day) . Wall of fire (once per day) . Flame strike (twice per week) The ring appears to be a major ring of energy resistance (fire) until the DM-established condition is met. Strong conjuration; CL 15th.

### Ring of Elemental Command (Water)

- **COST:** 200000
- **WT:** 0
- **SPROP:** All four kinds of elemental command rings are very powerful. Each appears to be nothing more than a lesser magic ring until fully activated (see below), but each has certain other powers as well as the following common properties. Elementals of the plane to which the ring is attuned can't attack the wearer, or even approach within 5 feet of him. If the wearer desires, he may forego this protection and instead attempt to charm the elemental (as charm monster, Will DC 17 negates). If the charm attempt fails, however, absolute protection is lost and no further attempt at charming can be made. Creatures from the plane to which the ring is attuned who attack the wearer take a -1 penalty on their attack rolls. The ring wearer makes applicable saving throws from the extraplanar creature's attacks with a +2 resistance bonus. He gains a +4 morale bonus on all attack rolls against such creatures. Any weapon he uses bypasses the damage reduction of such creatures, regardless of any qualities the weapon may or may not have. The wearer of the ring is able to converse with creatures from the plane to which his ring is attuned. These creatures recognize that he wears the ring. They show a healthy respect for the wearer if alignments are similar. If alignments are opposed, creatures fear the wearer if he is strong. If he is weak, they hate and desire to slay him. Fear, hatred, and respect are determined by the DM. The possessor of a ring of elemental command takes a saving throw penalty as follows: -2 against fire-based effects.
- **SPROP:** . Water walk (unlimited use) . Create water (unlimited use) . Water breathing (unlimited use) . Wall of ice (once per day) . Ice storm (twice per week) . Control water (twice per week) The ring appears to be a ring of water walking until the DMestablished condition is met. Strong conjuration; CL 15th.

### Ring of Energy Resistance, Major (Acid)

- **COST:** 28000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)
- **BONUS:** VAR|AcidResistanceBonusSp|20|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A major ring of energy resistance grants 20 points of resistance. Faint abjuration; CL 7th
- **SPROP:** Absorbs 20 points of Acid damage

### Ring of Energy Resistance, Major (Cold)

- **COST:** 28000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)
- **BONUS:** VAR|ColdResistanceBonusSp|20|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A major ring of energy resistance grants 20 points of resistance. Faint abjuration; CL 7th
- **SPROP:** Absorbs 20 points of Cold damage

### Ring of Energy Resistance, Major (Electricity)

- **COST:** 28000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)
- **BONUS:** VAR|ElectricityResistanceBonusSp|20|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A major ring of energy resistance grants 20 points of resistance. Faint abjuration; CL 7th
- **SPROP:** Absorbs 20 points of Electrical damage

### Ring of Energy Resistance, Major (Fire)

- **COST:** 28000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)
- **BONUS:** VAR|FireResistanceBonusSp|20|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A major ring of energy resistance grants 20 points of resistance. Faint abjuration; CL 7th
- **SPROP:** Absorbs 20 points of Fire damage

### Ring of Energy Resistance, Major (Sonic)

- **COST:** 28000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)
- **BONUS:** VAR|SonicResistanceBonusSp|20|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A major ring of energy resistance grants 20 points of resistance. Faint abjuration; CL 7th
- **SPROP:** Absorbs 20 points of Sonic damage

### Ring of Energy Resistance, Minor (Acid)

- **COST:** 12000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)
- **BONUS:** VAR|AcidResistanceBonusSp|10|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 10 points of resistance. Faint abjuration; CL 3rd
- **SPROP:** Absorbs 10 points of Acid damage

### Ring of Energy Resistance, Minor (Cold)

- **COST:** 12000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)
- **BONUS:** VAR|ColdResistanceBonusSp|10|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 10 points of resistance. Faint abjuration; CL 3rd
- **SPROP:** Absorbs 10 points of Cold damage

### Ring of Energy Resistance, Minor (Electricity)

- **COST:** 12000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)
- **BONUS:** VAR|ElectricityResistanceBonusSp|10|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 10 points of resistance. Faint abjuration; CL 3rd
- **SPROP:** Absorbs 10 points of Electrical damage

### Ring of Energy Resistance, Minor (Fire)

- **COST:** 12000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)
- **BONUS:** VAR|FireResistanceBonusSp|10|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 10 points of resistance. Faint abjuration; CL 3rd
- **SPROP:** Absorbs 10 points of Fire damage

### Ring of Energy Resistance, Minor (Sonic)

- **COST:** 12000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)
- **BONUS:** VAR|SonicResistanceBonusSp|10|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 10 points of resistance. Faint abjuration; CL 3rd
- **SPROP:** Absorbs 10 points of Sonic damage

### Ring of Energy Resistance, Greater (Acid)

- **COST:** 44000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)
- **BONUS:** VAR|AcidResistanceBonusSp|30|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 30 points of resistance. Moderate abjuration; CL 11th
- **SPROP:** Absorbs 30 points of Acid damage

### Ring of Energy Resistance, Greater (Cold)

- **COST:** 44000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)
- **BONUS:** VAR|ColdResistanceBonusSp|30|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 30 points of resistance. Moderate abjuration; CL 11th
- **SPROP:** Absorbs 30 points of Cold damage

### Ring of Energy Resistance, Greater (Electricity)

- **COST:** 44000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)
- **BONUS:** VAR|ElectricityResistanceBonusSp|30|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 30 points of resistance. Moderate abjuration; CL 11th
- **SPROP:** Absorbs 30 points of Electrical damage

### Ring of Energy Resistance, Greater (Fire)

- **COST:** 44000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)
- **BONUS:** VAR|FireResistanceBonusSp|30|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 30 points of resistance. Moderate abjuration; CL 11th
- **SPROP:** Absorbs 30 points of Fire damage

### Ring of Energy Resistance, Greater (Sonic)

- **COST:** 44000
- **WT:** 0
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)
- **BONUS:** VAR|SonicResistanceBonusSp|30|TYPE=Base
- **SPROP:** This reddish iron ring continually protects the wearer from damage from one type of energy. Each time the wearer would normally take such damage, subtract the ring's resistance value from the damage dealt. A minor ring of energy resistance grants 30 points of resistance. Moderate abjuration; CL 11th
- **SPROP:** Absorbs 30 points of Sonic damage

### Ring of Evasion

- **COST:** 25000
- **WT:** 0
- **SPROP:** This ring continually grants the wearer the ability to avoid damage as if she had evasion. Whenever she makes a Reflex saving throw to determine whether she takes half damage, a successful save results in no damage. Moderate transmutation; CL 7th
- **SPROP:** This ring continually grants the wearer the ability to avoid damage as if she had evasion. Whenever she makes a Reflex saving throw to determine whether she takes half damage, a successful save results in no damage.

### Ring of Feather Falling

- **COST:** 2200
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Feather Fall
- **SPROP:** This ring is crafted with a feather pattern all around its edge. It acts exactly like a feather fall spell (fall slowly up to 60' and land safely. (PH P229)), activated immediately if the wearer falls more than 5 feet. Faint transmutation; CL 1st

### Ring of Force Shield

- **COST:** 8500
- **WT:** 0
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **SPROP:** An iron band, this simple ring generates a shieldsized (and shield-shaped) wall of force that stays with the ring and can be wielded by the wearer as if it were a heavy shield (+2 AC). This special creation has no armor check penalty or arcane spell failure chance since it is weightless and encumbrance-free. It can be activated and deactivated at will as a free action. Moderate evocation; CL 9th

### Ring of Freedom of Movement

- **COST:** 40000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=7|Freedom of Movement
- **SPROP:** This gold ring allows the wearer to act as if continually under the effect of a freedom of movement spell. Moderate abjuration; CL 7th

### Ring of Friend Shield

- **COST:** 50000
- **WT:** 0
- **SPROP:** These curious rings always come in pairs. A friend shield ring without its mate is useless. Either wearer of one of a pair of the rings can, at any time, command his or her ring to cast a shield other spell with the wearer of the mated ring as the recipient. This effect has no range limitation. Moderate abjuration; CL 10th

### Ring of Friend Shield (1 of 2)

- **COST:** 25000
- **WT:** 0
- **SPROP:** These curious rings always come in pairs. A friend shield ring without its mate is useless. Either wearer of one of a pair of the rings can, at any time, command his or her ring to cast a shield other spell with the wearer of the mated ring as the recipient. This effect has no range limitation. Moderate abjuration; CL 10th

### Ring of Invisibility

- **COST:** 20000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Invisibility
- **SPROP:** By activating this simple silver ring, the wearer can benefit from invisibility, as the spell (PH 245) for three minutes. Faint illusion; CL 3rd

### Ring of Jumping

- **COST:** 2500
- **WT:** 0
- **BONUS:** SKILL|Jump|5|TYPE=Competence
- **SPROP:** This ring continually allows the wearer to leap about, providing a +5 competence bonus on all his Jump checks. Faint transmutation; CL 2nd

### Ring of Jumping, Improved

- **COST:** 10000
- **WT:** 0
- **BONUS:** SKILL|Jump|10|TYPE=Competence
- **SPROP:** As jumping, except it grants a +10 competence bonus on its wearer's Jump check. Moderate transmutation; CL 7th

### Ring of Mind Shielding

- **COST:** 8000
- **WT:** 0
- **SPROP:** This ring is usually of fine workmanship and wrought from heavy gold. The wearer is continually immune to detect thoughts, discern lies, and any attempt to magically discern her alignment. Faint aburation; CL 3rd

### Ring of Protection +1

- **COST:** 2000
- **WT:** 0
- **BONUS:** COMBAT|AC|1|TYPE=Deflection
- **SPROP:** This ring offers continual magical protection in the form of a deflection bonus of +1 to AC. Faint abjuration; CL 5th
- **SORTKEY:** Ring of Protection +01

### Ring of Protection +2

- **COST:** 8000
- **WT:** 0
- **BONUS:** COMBAT|AC|2|TYPE=Deflection
- **SPROP:** This ring offers continual magical protection in the form of a deflection bonus of +2 to AC. Faint abjuration; CL 5th
- **SORTKEY:** Ring of Protection +02

### Ring of Protection +3

- **COST:** 18000
- **WT:** 0
- **BONUS:** COMBAT|AC|3|TYPE=Deflection
- **SPROP:** This ring offers continual magical protection in the form of a deflection bonus of +3 to AC. Faint abjuration; CL 5th
- **SORTKEY:** Ring of Protection +03

### Ring of Protection +4

- **COST:** 32000
- **WT:** 0
- **BONUS:** COMBAT|AC|4|TYPE=Deflection
- **SPROP:** This ring offers continual magical protection in the form of a deflection bonus of +4 to AC. Faint abjuration; CL 5th
- **SORTKEY:** Ring of Protection +04

### Ring of Protection +5

- **COST:** 50000
- **WT:** 0
- **BONUS:** COMBAT|AC|5|TYPE=Deflection
- **SPROP:** This ring offers continual magical protection in the form of a deflection bonus of +5 to AC. Faint abjuration; CL 5th
- **SORTKEY:** Ring of Protection +05

### Ring of the Ram

- **COST:** 8600
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** The ring of the ram is an ornate ring forged of hard metal, usually iron or an iron alloy. It has the head of a ram (or a billy goat) as its device. The wearer can command the ring to give forth a ramlike force, manifested by a vaguely discernible shape that resembles the head of a ram or a goat. This force strikes a single target, dealing 1d6 points of damage if 1 charge is expended, 2d6 points if 2 charges are used, or 3d6 points if 3 charges (the maximum) are used. Treat this as a ranged attack with a 50-foot maximum range and no penalties for distance. The ring is useful for knocking opponents off parapets or ledges, among other things. The force of the blow is considerable, and those struck by the ring are subject to a bull rush if within 30 feet of the ring-wearer. (The ram has Strength 25 and is Large.) The ram gains a +1 bonus on the bull rush attempt if 2 charges are expended, or +2 if 3 charges are expended. In addition to its attack mode, the ring of the ram also has the power to open doors as if it were a character with Strength 25. If 2 charges are expended, the effect is equivalent to a character with Strength 27. If 3 charges are expended, the effect is that of a character with Strength 29. A newly created ring has 50 charges. When all the charges are expended, the ring becomes a nonmagical item. Moderate transmutation; CL 9th

### Ring of Regeneration

- **COST:** 90000
- **WT:** 0
- **SPROP:** This white gold ring continually allows a living wearer to heal 1 point of damage per level every hour rather than every day. (This ability cannot be aided by the Heal skill.) Nonlethal damage heals at a rate of 1 point of damage per level every 5 minutes. If the wearer loses a limb, an organ, or any other body part while wearing this ring, the ring regenerates it as the spell. In either case, only damage taken while wearing the ring is regenerated. Strong conjuration; CL 15th

### Ring of Shooting Stars

- **COST:** 50000
- **WT:** 0
- **SPROP:** This ring has two modes of operation, one for being in shadowy darkness or outdoors at night and a second one when the wearer is underground or indoors at night. During the night under the open sky or in areas of shadow or darkness, the ring of shooting stars can perform the following functions on command. . Dancing lights (once per hour) . Light (twice per night) . Ball lightning (special, once per night) . Shooting stars (special, three per week) The first special function, ball lightning, releases one to four balls of lightning (ring wearer's choice). These glowing globes resemble dancing lights, and the ring wearer controls them in the same fashion (see the dancing lights spell description in the Player's Handbook). The spheres have a 120-foot range and a duration of 4 rounds. They can be moved at 120 feet per round. Each sphere is about 3 feet in diameter, and any creature who comes within 5 feet of one causes its charge to dissipate, taking electricity damage in the process according to the number of balls created. Once the ball lightning function is activated, the balls can be released at any time before the sun rises. (Multiple balls can be released in the same round.) The second special function produces three shooting stars that can be released from the ring each week, simultaneously or one at a time. They impact for 12 points of damage and spread (as a fireball) in a 5-foot-radius sphere for 24 points of fire damage. Any creature struck by a shooting star takes full damage from impact plus full fire damage from the spread unless it makes a DC 13 Reflex save. Creatures not struck but within the spread ignore the impact damage and take only half damage from the fire spread on a successful DC 13 Reflex save. Range is 70 feet, at the end of which the shooting star explodes, unless it strikes a creature or object before that. A shooting star always follows a straight line, and any creature in its path must make a save or be hit by the projectile. Indoors at night, or underground, the ring of shooting stars has the following properties. . Faerie fire (twice per day) . Spark shower (special, once per day) The spark shower is a flying cloud of sizzling purple sparks that fan out from the ring for a distance of 20 feet in an arc 10 feet wide. Creatures within this area take 2d8 points of damage each if not wearing metal armor or carrying a metal weapon. Those wearing metal armor and/or carrying a metal weapon take 4d8 points of damage. Strong evocation; CL 12th

### Ring of Spell Storing, Minor

- **COST:** 18000
- **WT:** 0
- **SPROP:** A minor ring of spell storing contains up to three levels of spells that the wearer can cast. Each spell has a caster level equal to the minimum level needed to cast that spell. The user need not provide any material components or focus, or pay an XP cost to cast the spell, and there is no arcane spell failure chance for wearing armor (because the ring wearer need not gesture). The activation time for the ring is same as the casting time for the relevant spell, with a minimum of 1 standard action. A spellcaster can cast any spells into the ring, so long as the total spell levels do not add up to more than three. Metamagic versions of spells take up storage space equal to their spell level modified by the metamagic feat. A spellcaster can use a scroll to put a spell into the minor ring of spell storing. The ring magically imparts to the wearer the names of all spells currently stored within it. Faint evocation; CL 5th

### Ring of Spell Storing

- **COST:** 50000
- **WT:** 0
- **SPROP:** A minor ring of spell storing contains up to five levels of spells that the wearer can cast. Each spell has a caster level equal to the minimum level needed to cast that spell. The user need not provide any material components or focus, or pay an XP cost to cast the spell, and there is no arcane spell failure chance for wearing armor (because the ring wearer need not gesture). The activation time for the ring is same as the casting time for the relevant spell, with a minimum of 1 standard action. A spellcaster can cast any spells into the ring, so long as the total spell levels do not add up to more than five. Metamagic versions of spells take up storage space equal to their spell level modified by the metamagic feat. A spellcaster can use a scroll to put a spell into the minor ring of spell storing. The ring magically imparts to the wearer the names of all spells currently stored within it. Faint evocation; CL 5th

### Ring of Spell Storing, Major

- **COST:** 200000
- **WT:** 0
- **SPROP:** A minor ring of spell storing contains up to ten levels of spells that the wearer can cast. Each spell has a caster level equal to the minimum level needed to cast that spell. The user need not provide any material components or focus, or pay an XP cost to cast the spell, and there is no arcane spell failure chance for wearing armor (because the ring wearer need not gesture). The activation time for the ring is same as the casting time for the relevant spell, with a minimum of 1 standard action. A spellcaster can cast any spells into the ring, so long as the total spell levels do not add up to more than ten. Metamagic versions of spells take up storage space equal to their spell level modified by the metamagic feat. A spellcaster can use a scroll to put a spell into the minor ring of spell storing. The ring magically imparts to the wearer the names of all spells currently stored within it. Faint evocation; CL 5th

### Ring of Spell Turning

- **COST:** 98280
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=3|CASTERLEVEL=13|Spell Turning
- **SPROP:** Up to three times per day on command, this simple platinum band automatically reflects the next nine levels of spells cast at the wearer, exactly as if spell turning had been cast upon the wearer. Strong abjuration; CL 13th

### Ring of Sustenance

- **COST:** 2500
- **WT:** 0
- **SPROP:** This ring continually provides its wearer with life-sustaining nourishment, so you do not need to eat or drink. The ring also refreshes the body and mind, so that its wearer needs only sleep 2 hours per day to gain the benefit of 8 hours of sleep. The ring must be worn for a full week before it begins to work. If it is removed, the owner must wear it for another week to reattune it to himself. Faint conjuration; CL 5th

### Ring of Swimming

- **COST:** 2500
- **WT:** 0
- **BONUS:** SKILL|Swim|5|TYPE=Competence
- **SPROP:** This silver ring has a wave pattern etched into the band. It continually grants the wearer a +5 competence bonus on Swim checks. Faint transmutation; CL 2nd

### Ring of Swimming, Improved

- **COST:** 10000
- **WT:** 0
- **BONUS:** SKILL|Swim|10|TYPE=Competence
- **SPROP:** This silver ring has a wave pattern etched into the band. It continually grants the wearer a +10 competence bonus on Swim checks. Moderate transmutation; CL 7th

### Ring of Telekinesis

- **COST:** 75000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=9|Telekinesis
- **SPROP:** This ring allows the caster to use the spell telekinesis on command. Moderate transmutation; CL 9th

### Ring of Three Wishes

- **COST:** 97950
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_3|CHARGES[3]
- **SPROP:** This ring is set with three rubies. Each ruby stores a wish spell, activated by the ring. When a wish is used, that ruby disappears. For a randomly generated ring, roll 1d3 to determine the remaining number of rubies. When all the wishes are used, the ring becomes a nonmagical item. Strong evocation (if miracle is used); CL 20th

### Ring of Water Walking

- **COST:** 15000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=9|Water Walk
- **SPROP:** This ring, set with an opal, allows the wearer to continually utilize the effects of the spell water walk. Moderate transmutation; CL 9th

### Ring of Wizardry I

- **COST:** 20000
- **WT:** 0
- **BONUS:** SPELLCASTMULT|TYPE=Arcane;LEVEL=1|2
- **SPROP:** A ring of wizardry I doubles 1st-level spells
- **SORTKEY:** Ring of Wizardry 01

### Ring of Wizardry II

- **COST:** 40000
- **WT:** 0
- **BONUS:** SPELLCASTMULT|TYPE=Arcane;LEVEL=2|2
- **SPROP:** A ring of wizardry II doubles 2nd-level spells
- **SORTKEY:** Ring of Wizardry 02

### Ring of Wizardry III

- **COST:** 70000
- **WT:** 0
- **BONUS:** SPELLCASTMULT|TYPE=Arcane;LEVEL=3|2
- **SPROP:** A ring of wizardry III doubles 3rd-level spells
- **SORTKEY:** Ring of Wizardry 03

### Ring of Wizardry IV

- **COST:** 100000
- **WT:** 0
- **BONUS:** SPELLCASTMULT|TYPE=Arcane;LEVEL=4|2
- **SPROP:** A ring of wizardry IV doubles 4th-level spells
- **SORTKEY:** Ring of Wizardry 04

### Ring of X-Ray Vision

- **COST:** 25000
- **WT:** 0
- **SPROP:** On command, this ring gives its possessor the ability to see into and through solid matter. Vision range is 20 feet, with the viewer seeing as if he were looking at something in normal light even if there is no illumination. (For example, if the wearer looks into a locked chest, he can see inside even if there's no light within.) X-ray vision can penetrate 1 foot of stone, 1 inch of common metal, or up to 3 feet of wood or dirt. Thicker substances or a thin sheet of lead blocks the vision. Using the ring is physically exhausting, causing the wearer 1 point of Constitution damage per minute after the first 10 minutes of use in a single day. Moderate divination; CL 6th

### Ring of Meld into Stone

- **COST:** 27000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=5|Meld into Stone

### Rod (Absorption)

- **COST:** 50000
- **WT:** 5
- **BASEITEM:** Rod
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This rod acts as a magnet, drawing spells or spelllike abilities into itself. The magic absorbed must be a single-target spell or a ray directed at either the character possessing the rod or her gear. The rod then nullifies the spell's effect and stores its potential until the wielder releases this energy in the form of spells of her own. She can instantly detect a spell's level as the rod absorbs that spell's energy. Absorption requires no action on the part of the user if the rod is in hand at the time. A running total of absorbed (and used) spell levels should be kept. For example, a rod that absorbs a 6th-level spell and a 3rdlevel spell has a total of nine absorbed spell levels. The wielder of the rod can use captured spell energy to cast any spell she has prepared, without expending the preparation itself. The only restrictions are that the levels of spell energy stored in the rod must be equal to or greater than the level of the spell the wielder wants to cast, that any material components required for the spell be present, and that the rod be in hand when casting. Continuing the example above, the rod wielder could use the nine absorbed spell levels to cast one 9th-level spell, or one 5th-level and one 4th-level spell, or nine 1st-level spells, and so on. For casters such as bards or sorcerers who do not prepare spells, the rod's energy can be used to cast any spell of the appropriate level or levels that they know. A rod of absorption absorbs a maximum of fifty spell levels and can thereafter only discharge any remaining potential it might have. The rod cannot be recharged. The wielder knows the rod's remaining absorbing potential and current amount of stored energy. A more specific example: Jozan the cleric uses a brand-new rod of absorption to nullify the effect of a suggestion spell cast at him by a sorcerer. The rod has now absorbed three spell levels and can absorb forty-seven more. Jozan can cast any 1st-, 2nd-, or 3rd-level spell he has prepared, without loss of that preparation, by using the stored potential of the rod. Let's assume he casts hold person back at the sorcerer who just attacked him. This spell is 2nd level for him, so the rod still holds one spell level of potential, can absorb fortyseven more, and has disposed of two spell levels permanently. To determine the absorption potential remaining in a newly found rod, roll d%% and divide the result by 2. Then roll d%% again: On a result of 71-100, half the levels already absorbed by the rod are still stored within. For example, if the first roll determines that the rod has thirty-four levels of absorption potential remaining, that means the rod has absorbed sixteen levels' worth of spells. Half of sixteen is eight, so there's a 30%% chance that it still holds eight absorbed spell levels ready for use. Strong abjuration; CL 15th

### Rod (Alertness)

- **PROFICIENCY:** WEAPON|Mace (Light)
- **COST:** 85000
- **WT:** 4
- **BASEITEM:** Rod
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** COMBAT|INITIATIVE|1
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** This rod is indistinguishable from a +1 light mace. It has eight flanges on its macelike head. The rod bestows a +1 insight bonus on initiative checks. If grasped firmly, the rod enables the holder to use detect evil, detect good, detect chaos, detect law, detect magic, discern lies, light, or see invisibility. Each different use is a standard action. If the head of a rod of alertness is planted in the ground, and the possessor wills it to alertness (a standard action), the rod senses any creature within 120 feet who intends to harm the possessor. At the same time, the rod creates the effect of a prayer spell upon all creatures friendly to the possessor in a 20-foot radius. Immediately thereafter, the rod sends forth a mental alert to these friendly creatures, warning them of possible danger from the unfriendly creature or creatures within the 120-foot radius. These effects last for 10 minutes, and the rod can perform this function once per day. Last, the rod can be used to simulate the casting of an animate objects spell, utilizing any eleven (or fewer) Small objects located roughly around the perimeter of a 5-foot-radius circle centered on the rod when planted in the ground. Objects remain animated for 11 rounds. The rod can perform this function once per day. Moderate abjuration, divination, enchantment, and evocation; CL 11th

### Rod (Cancellation)

- **COST:** 11000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This dreaded rod is a bane to magic items, for its touch drains an item of all magical properties. The item touched must make a DC 23 Will save to prevent the rod from draining it. If a creature is holding it at the time, then the item can use the holder's Will save bonus in place of its own if the holder's is better. In such cases, contact is made by making a melee touch attack roll. Upon draining an item, the rod itself becomes brittle and cannot be used again. Drained items are only restorable by wish or miracle. (If a sphere of annihilation and a rod of cancellation negate each other, nothing can restore either of them.) Strong abjuration; CL 17th

### Rod (Enemy Detection)

- **COST:** 23500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This device pulses in the wielder's hand and points in the direction of any creature or creatures hostile to the bearer of the device (nearest ones first). These creatures can be invisible, ethereal, hidden, disguised, or in plain sight. Detection range is 60 feet. If the bearer of the rod concentrates for a full round, the rod pinpoints the location of the nearest enemy and indicates how many enemies are within range. The rod can be used three times each day, each use lasting up to 10 minutes. Activating the rod is a standard action. Moderate divination; CL 10th

### Rod (Flailing)

- **PROFICIENCY:** WEAPON|Flail (Dire)
- **ALTTYPE:** Weapon.Melee.Bludgeoning
- **COST:** 50000
- **WT:** 5
- **BASEITEM:** Rod
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **ALTCRITMULT:** x2
- **ALTCRITRANGE:** 1
- **DAMAGE:** 1d8
- **ALTDAMAGE:** 1d8
- **WIELD:** OneHanded
- **SIZE:** M
- **ABILITY:** FEAT|VIRTUAL|Two-Weapon Fighting
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **SPROP:** Upon the command of its possessor, the rod activates, changing from a normal-seeming rod to a +3 dire flail. The dire flail is a double weapon, which means that each of the weapon's heads can be used to attack (see the weapon description on page 117 of the Player's Handbook). The wielder can gain an extra attack (with the second head) at the cost of making all attacks at a -2 penalty (as if she had the Two-Weapon Fighting feat). Once per day the wielder can use a free action to cause the rod to grant her a +4 deflection bonus to Armor Class and a +4 resistance bonus on saving throws for 10 minutes. The rod need not be in weapon form to grant this benefit. Transforming it into a weapon or back into a rod is a move action. Moderate enchantment; CL 9th

### Rod (Flame Extinguishing)

- **COST:** 15000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This rod can extinguish Medium or smaller nonmagical fires with simply a touch (a standard action). For the rod to be effective against other sorts of fires, the wielder must expend 1 or more of the rod's charges. Extinguishing a Large or larger nonmagical fire, or a magic fire of Medium or smaller (such as that of a flaming weapon or a burning hands spell), expends 1 charge. Continual magic flames, such as those of a weapon or a fire creature, are suppressed for 6 rounds and flare up again after that time. To extinguish an instantaneous fire spell, the rod must be within the area of the effect and the wielder must have used a ready action, effectively countering the entire spell. When applied to Large or larger magic fires, such as those caused by fireball, flame strike, or wall of fire, extinguishing the flames expends 2 charges from the rod. If the device is used upon a fire creature (a melee touch attack), it deals 6d6 points of damage to the creature. This use requires 3 charges. A rod of flame extinguishing has 10 charges when found. Spent charges are renewed every day, so that a wielder can expend up to 10 charges in any 24-hour period. Strong transmutation; CL 12th

### Rod (Immovable)

- **COST:** 5000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This rod is a flat iron bar with a small button on one end. When the button is pushed (a move action), the rod does not move from where it is, even if staying in place defies gravity. Thus, the owner can lift or place the rod wherever he wishes, push the button, and let go. Adventurers have found the immovable rod useful for holding ropes, barring doors, and all sorts of other utilitarian tasks. Many adventurers have found it useful to have more than one. Several immovable rods can even make a ladder when used together (although only two are needed). An immovable rod can support up to 8,000 pounds before falling to the ground. If a creature pushes against an immovable rod, it must make a DC_30 Strength check to move the rod up to 10 feet in a single round. Moderate transmutation; CL 10th

### Rod (Lordly Might)

- **PROFICIENCY:** WEAPON|Mace (Light)
- **COST:** 70000
- **WT:** 10
- **BASEITEM:** Rod
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This rod has functions that are spell-like, and it can also be used as a magic weapon of various sorts. It also has several more mundane uses. The rod of lordly might is metal, thicker than other rods, with a flanged ball at one end and six studlike buttons along its length. (Pushing any of the rod's buttons is equivalent to drawing a weapon.) It weighs 10 pounds. The following spell-like functions of the rod can each be used once per day. . Hold person upon touch, if the wielder so commands (Will DC 14 negates). The wielder must choose to use this power and then succeed on a melee touch attack to activate the power. If the attack fails, the effect is lost. . Fear upon all enemies viewing it, if the wielder so desires (10-foot maximum range, Will DC 16 partial). Invoking this power is a standard action. . Deal 2d4 hit points of damage to an opponent on a successful touch attack (Will DC 17 half ) and cure the wielder of a like amount of damage. The wielder must choose to use this power before attacking, as with hold person. The following weapon functions of the rod have no limit on the number of times they can be employed. . In its normal form, the rod can be used as a +2 light mace. . When button 1 is pushed, the rod becomes a +1 flaming longsword. A blade springs from the ball, with the ball itself becoming the sword's hilt. The weapon lengthens to an overall length of 4 feet. . When button 2 is pushed, the rod becomes a +4 battleaxe. A wide blade springs forth at the ball, and the whole lengthens to 4 feet. . When button 3 is pushed, the rod becomes a +3 shortspear or +3 longspear.The spear blade springs forth, and the handle can be lengthened up to 12 feet (wielder's choice), for an overall length of from 6 feet to 15 feet. At its 15-foot length, the rod is suitable for use as a lance. The following other functions of the rod also have no limit on the number of times they can be employed. . Climbing pole/ladder. When button 4 is pushed, a spike that can anchor in granite is extruded from the ball, while the other end sprouts three sharp hooks. The rod lengthens to anywhere between 5 and 50 feet in a single round, stopping when button 4 is pushed again. Horizontal bars three inches long fold out from the sides, 1 foot apart, in staggered progression. The rod is firmly held by the spike and hooks and can bear up to 4,000 pounds. The wielder can retract the pole by pushing button 5. . The ladder function can be used to force open doors. The wielder plants the rod's base 30 feet or less from the portal to be forced and in line with it, then pushes button 4. The force exerted has a Strength modifier of +12. . When button 6 is pushed, the rod indicates magnetic north and gives the wielder a knowledge of his approximate depth beneath the surface or height above it. Strong enchantment, evocation, necromancy, and transmutation; CL 19th
- **AUTO:** EQUIP|Rod of Lordly Might Battleaxe|Rod of Lordly Might Flaming Longsword|Rod of Lordly Might Longspear|Rod of Lordly Might Shortspear

### Rod (Metal and Mineral Detection)

- **COST:** 10500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This rod pulses in the wielder's hand and points to the largest mass of metal within 30 feet. However, the wielder can concentrate on a specific metal or mineral (gold, platinum, quartz, beryl, diamond, corundum, and so on). If the specific mineral is within 30 feet, the rod points to any places it is located, and the rod wielder knows the approximate quantity as well. If more than one deposit of the specified metal or mineral is within range, the rod points to the largest cache first. Each operation requires a full-round action. Moderate divination; CL 9th

### Rod (Empower/Lesser)

- **COST:** 9000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are empowered as though using the Empower Spell feat. Strong (no school); CL 17th

### Rod (Empower)

- **COST:** 32500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are empowered as though using the Empower Spell feat. Strong (no school); CL 17th

### Rod (Empower/Greater)

- **COST:** 73000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are empowered as though using the Empower Spell feat. Strong (no school); CL 17th

### Rod (Enlarge/Lesser)

- **COST:** 3000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are enlarged as though using the Enlarge Spell feat. Strong (no school); CL 17th

### Rod (Enlarge)

- **COST:** 11000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are enlarged as though using the Enlarge Spell feat. Strong (no school); CL 17th

### Rod (Enlarge/Greater)

- **COST:** 24500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are enlarged as though using the Enlarge Spell feat. Strong (no school); CL 17th

### Rod (Extend/Lesser)

- **COST:** 3000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are extended as though using the Extend Spell feat. Strong (no school); CL 17th

### Rod (Extend)

- **COST:** 11000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are extended as though using the Extend Spell feat. Strong (no school); CL 17th

### Rod (Extend/Greater)

- **COST:** 24500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are extended as though using the Extend Spell feat. Strong (no school); CL 17th

### Rod (Maximize/Lesser)

- **COST:** 14000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are maximized as though using the Maximize Spell feat. Strong (no school); CL 17th

### Rod (Maximize)

- **COST:** 54000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are maximized as though using the Maximize Spell feat. Strong (no school); CL 17th

### Rod (Maximize/Greater)

- **COST:** 121500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are maximized as though using the Maximize Spell feat. Strong (no school); CL 17th

### Rod (Quicken/Lesser)

- **COST:** 35000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are quickened as though using the Quicken Spell feat. Strong (no school); CL 17th

### Rod (Quicken)

- **COST:** 75500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are quickened as though using the Quicken Spell feat. Strong (no school); CL 17th

### Rod (Quicken/Greater)

- **COST:** 170000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day that are quickened as though using the Quicken Spell feat. Strong (no school); CL 17th

### Rod (Silent/Lesser)

- **COST:** 3000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day without verbal components as though using the Silent Spell feat. Strong (no school); CL 17th

### Rod (Silent)

- **COST:** 11000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day without verbal components as though using the Silent Spell feat. Strong (no school); CL 17th

### Rod (Silent/Greater)

- **COST:** 24500
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** The wielder can cast up to three spells per day without verbal components as though using the Silent Spell feat. Strong (no school); CL 17th

### Rod (Negation)

- **COST:** 37000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This device negates the spell or spell-like function or functions of magic items. The wielder points the rod at the magic item, and a pale gray beam shoots forth to touch the target device, attacking as a ray (a ranged touch attack). The ray functions as a greater dispel magic spell, except it only affects magic items. To negate instantaneous effects from an item, the rod wielder needs to have used a ready action. The dispel check uses the rod's caster level (15th). The target item gets no saving throw, although the rod can't negate artifacts (even minor artifacts). The rod can function three times per day. Strong varied; CL 15th

### Rod (Python)

- **PROFICIENCY:** WEAPON|Quarterstaff
- **ALTTYPE:** Weapon.Melee.Bludgeoning
- **COST:** 13000
- **WT:** 10
- **BASEITEM:** Rod
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **ALTCRITMULT:** x2
- **ALTCRITRANGE:** 1
- **DAMAGE:** 1d6
- **ALTDAMAGE:** 1d6
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** This rod is longer than normal rods. It is about 4 feet long and weighs 10 pounds. It strikes as a +1/+1 quarterstaff. If the user throws the rod to the ground (a standard action), it grows to become a giant constrictor snake (see page 280 of the Monster Manual for complete statistics) by the end of the round. The python obeys all commands of the owner. (In animal form, it retains the +1 enhancement bonus on attacks and damage possessed by the rod form.) The serpent returns to rod form (a fullround action) whenever the wielder desires, or whenever it moves farther than 100 feet from the owner. If the snake form is slain, it returns to rod form and cannot be activated again for three days. A python rod only functions if the possessor is good. Moderate transmutation; CL 10th

### Rod (Rulership)

- **COST:** 60000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This rod looks like a royal scepter worth at least 5,000 gp in materials and workmanship alone. The wielder can command the obedience and fealty of creatures within 120 feet when she activates the device (a standard action). Creatures totaling 300 Hit Dice can be ruled, but creatures with Intelligence scores of 12 or higher are entitled to a DC 16 Will save to negate the effect. Ruled creatures obey the wielder as if she were their absolute sovereign. Still, if the wielder gives a command that is contrary to the nature of the creatures commanded, the magic is broken. The rod can be used for 500 total minutes before crumbling to dust. This duration need not be continuous. Strong enchantment; CL 20th

### Rod (Security)

- **COST:** 61000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** This item creates a nondimensional space, a pocket paradise. There the rod's possessor and as many as 199 other creatures can stay in complete safety for a period of time, up to 200 days divided by the number of creatures affected. Thus, one creature (the rod's possessor) can stay for 200 days, four creatures can stay for 50 days, or a group of sixty creatures can stay for 3 days. All fractions are rounded down, so that a group numbering more than 100 can stay for one day only and a group of 201 or more cannot be affected by the rod. In this pocket paradise, creatures don't age, and natural healing take place at twice the normal rate. Fresh water and food (fruits and vegetables only) are in abundance. The climate is comfortable for all creatures involved. Activating the rod (a standard action) causes the wielder and all creatures touching the rod to be transported instantaneously to the paradise. Members of large groups can hold hands or otherwise maintain physical contact, allowing all connected creatures in a circle or a chain to be affected by the rod. Unwilling creatures get a DC 17 Will save to negate the effect. If such a creature succeeds on its save, other creatures beyond that point in a chain can still be affected by the rod. When the rod's effect expires or is dispelled, all the affected creatures instantly reappear in the location they occupied when the rod was activated. If something else occupies the space that a traveler would be returning to, then his body is displaced a sufficient distance to provide the space required for reentry. The rod's possessor can dismiss the effect whenever he wishes before the maximum time period expires, but the rod can only be activated once per week. Strong conjuuration; CL 20th

### Rod (Splendor)

- **COST:** 25000
- **WT:** 5
- **BASEITEM:** Rod
- **BONUS:** STAT|CHA|4|TYPE=Enhancement
- **SPROP:** The possessor of this rod gains a +4 enhancement bonus to her Charisma score for as long as she holds or carries the item. Once per day, the rod creates and garbs her in clothing of the finest fabrics, plus adornments of furs and jewels. Apparel created by the magic of the rod remains in existence for 12 hours. However, if the possessor attempts to sell or give away any part of it, to use it for a spell component, or the like, all the apparel immediately disappears. The same applies if any of it is forcibly taken from her. The value of noble garb created by the rod ranges from 7,000 to 10,000 gp (1d4+6 * 1,000 gp)-1,000 gp for the fabric alone, 5,000 gp for the furs, and the rest for the jewel trim (maximum of twenty gems, maximum value 200 gp each). In addition, the rod has a second special power, usable once per week. Upon command, it creates a palatial tent-a huge pavilion of silk 60 feet across. Inside the tent are temporary furnishings and food suitable to the splendor of the pavilion and sufficient to entertain as many as one hundred persons. The tent and its trappings last for one day. At the end of that time, the tent and all objects associated with it (including any items that were taken out of the tent) disappear. Strong conjuration and transmutation; CL 12th

### Rod (Thunder and Lightning)

- **PROFICIENCY:** WEAPON|Mace (Light)
- **COST:** 33000
- **WT:** 4
- **BASEITEM:** Rod
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** Constructed of iron set with silver rivets, this rod has the properties of a +2 light mace. Its other magical powers are as follows. . Thunder: Once per day, the rod can strike as a +3 light mace, and the opponent struck is stunned from the noise of the rod's impact (Fortitude DC 16 negates). Activating this power counts as a free action, and it works if the wielder strikes an opponent within 1 round. . Lightning: Once per day, when the wielder desires, a short spark of electricity can leap forth when the rod strikes an opponent to deal the normal damage for a +2 light mace (1d6+2) and an extra 2d6 points of electricity damage. Even when the rod might not score a normal hit in combat, if the roll was good enough to count as a successful melee touch attack hit, then the 2d6 points of electricity damage still applies. The wielder activates this power as a free action, and it works if he strikes an opponent within 1 round. . Thunderclap: Once per day as a standard action, the wielder can cause the rod to give out a deafening noise, just as a shout spell (Fortitude DC 16 partial, 2d6 points of sonic damage, target deafened for 2d6 rounds). . Lightning Stroke: Once per day as a standard action, the wielder can cause the rod to shoot out a 5-foot-wide lightning bolt (9d6 points of electricity damage, Reflex DC 16 half ) to a range of 200 feet. . Thunder and Lightning: Once per week as a standard action, the wielder of the rod can combine the thunderclap described above with a lightning bolt, as in the lightning stroke. The thunderclap affects all within 10 feet of the bolt. The lightning stroke deals 9d6 points of electricity damage (count rolls of 1 or 2 as rolls of 3, for a range of 27 to 54 points), and the thunderclap deals 2d6 points of sonic damage. A single DC 16 Reflex save applies for both effects. Moderate evocation; CL 9th

### Rod (Viper)

- **PROFICIENCY:** WEAPON|Mace (Heavy)
- **COST:** 19000
- **WT:** 5
- **BASEITEM:** Rod
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** This rod strikes as a +2 heavy mace. Once per day, upon command, the head of the rod becomes that of an actual serpent for 10 minutes. During this period, any successful strike with the rod deals its usual damage and also poisons the creature hit. The poison deals 1d10 points of Constitution damage immediately (Fortitude DC 14 negates) and another 1d10 points of Constitution damage 1 minute later (Fortitude DC 14 negates). The rod only functions if its possessor is evil. Moderate necromancy; CL 10th

### Rod (Withering)

- **PROFICIENCY:** WEAPON|Mace (Light)
- **COST:** 25000
- **WT:** 5
- **BASEITEM:** Rod
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** WEAPON|TOHIT|1
- **SPROP:** A rod of withering acts as a +1 light mace that deals no hit point damage. Instead, the wielder deals 1d4 points of Strength damage and 1d4 points of Constitution damage to any creature she touches with the rod (by making a melee touch attack). If she scores a critical hit, the damage from that hit is permanent ability drain. In either case, the defender negates the effect with a DC 17 Fortitude save. Strong necromancy; CL 13th;
- **SPROP:** Deals 1d4 temporary STR and CON damage

### Rod (Wonder)

- **COST:** 12000
- **WT:** 5
- **BASEITEM:** Rod
- **SPROP:** A rod of wonder is a strange and unpredictable device that randomly generates any number of weird effects each time it is used. (Activating the rod is a standard action.) The usual effects are shown on the table DMG p237. Moderate enchantment; CL 10th;
- **WT:** 5

### Rod of Lordly Might Battleaxe

- **PROFICIENCY:** WEAPON|Battleaxe
- **COST:** 10
- **WT:** 6
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** MAGIC_COST|-32310.PLUS4W.STEEL
- **WIELD:** OneHanded
- **MODS:** NO
- **SIZE:** M
- **SORTKEY:** Rod of Lordly Might Battleaxe

### Rod of Lordly Might Flaming Longsword

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 15
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** FLM_M.MAGIC_COST|-8315.PLUS1W.STEEL
- **WIELD:** OneHanded
- **MODS:** NO
- **SIZE:** M
- **SORTKEY:** Rod of Lordly Might Flaming Longsword

### Rod of Lordly Might Longspear

- **PROFICIENCY:** WEAPON|Longspear
- **COST:** 5
- **WT:** 9
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** MAGIC_COST|-18305.PLUS3W.WOOD
- **WIELD:** TwoHanded
- **MODS:** NO
- **REACHMULT:** 2
- **SIZE:** M
- **SORTKEY:** Rod of Lordly Might Longspear

### Rod of Lordly Might Shortspear

- **PROFICIENCY:** WEAPON|Shortspear
- **COST:** 1
- **WT:** 3
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **EQMOD:** MAGIC_COST|-18301.PLUS3W.WOOD
- **WIELD:** OneHanded
- **MODS:** NO
- **RANGE:** 20
- **SIZE:** M
- **SORTKEY:** Rod of Lordly Might Shortspear

### Scroll (Acid Splash)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Acid Splash
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Arcane Mark)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Arcane Mark
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Dancing Lights)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Dancing Lights
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Daze)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Daze
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Detect Magic/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Magic
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Detect Poison/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Poison
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Disrupt Undead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Disrupt Undead
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Flare/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Flare
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Ghost Sound)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Ghost Sound
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Know Direction/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Know Direction
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Light/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Light
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Lullaby)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Lullaby
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Mage Hand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Mage Hand
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Mending/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Mending
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Message)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Message
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Open/Close)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Open/Close
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Prestidigitation)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Prestidigitation
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Ray of Frost)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Ray of Frost
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Read Magic/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Read Magic
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Resistance/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Resistance
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Summon Instrument)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Summon Instrument
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Touch of Fatigue)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Touch of Fatigue
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Alarm/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Alarm
- **COST:** 25
- **WT:** 0.01

### Scroll (Animate Rope)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Animate Rope
- **COST:** 25
- **WT:** 0.01

### Scroll (Burning Hands)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Burning Hands
- **COST:** 25
- **WT:** 0.01

### Scroll (Cause Fear/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Cause Fear
- **COST:** 25
- **WT:** 0.01

### Scroll (Charm Person)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Charm Person
- **COST:** 25
- **WT:** 0.01

### Scroll (Chill Touch)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Chill Touch
- **COST:** 25
- **WT:** 0.01

### Scroll (Color Spray)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Color Spray
- **COST:** 25
- **WT:** 0.01
- **SPROP:** 15' Cone stuns creatures based on HD (5+ stunned for 1 round, 4- also blind & stunned for 1d4 rounds, 2- also unconscious for 2d4 rounds. Will DC 11 negates(PH 210)

### Scroll (Color Spray/Wizard/2nd)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=2|Color Spray
- **COST:** 50
- **WT:** 0.01
- **SPROP:** 15' Cone stuns creatures based on HD (5+ stunned for 1 round, 4- also blind & stunned for 1d4 rounds, 2- also unconscious for 2d4 rounds. Will DC 11 negates(PH 210)

### Scroll (Comprehend Languages/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Comprehend Languages
- **COST:** 25
- **WT:** 0.01
- **SPROP:** Understand spoken or written words for 10 minutes

### Scroll (Confusion/Lesser)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Confusion (Lesser)
- **COST:** 50
- **WT:** 0.01

### Scroll (Cure Light Wounds/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Cure Light Wounds
- **COST:** 50
- **WT:** 0.01
- **SPROP:** Cures 1d8+1 damage (PH P.215)

### Scroll (Detect Secret Doors)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Secret Doors
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Undead/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Undead
- **COST:** 25
- **WT:** 0.01

### Scroll (Disguise Self/Lvl 1)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Disguise Self
- **COST:** 25
- **WT:** 0.01
- **SPROP:** You make yourself and your equipment look different - 1 foot shorter/taller, thin/fat, add/obscure minor feature or look like an entirely different person. +1 disguise for 10 minutes

### Scroll (Endure Elements/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Endure Elements
- **COST:** 25
- **WT:** 0.01
- **SPROP:** Suffer no harm from hot or cold environment (-50 to 140 degrees Fahrenheit) for 24 hours

### Scroll (Enlarge Person)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Enlarge Person
- **SPROP:** Double height and multiply weight by 8. +2 Str, -2 Dex, -1 Attack & AC for 1 minute (PH P.226)
- **COST:** 25
- **WT:** 0.01

### Scroll (Enlarge Person/Wizard/2nd)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=2|Enlarge Person
- **SPROP:** Double height and multiply weight by 8. +2 Str, -2 Dex, -1 Attack & AC for 2 minutes (PH P.226)
- **COST:** 25
- **WT:** 0.01

### Scroll (Erase)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Erase
- **COST:** 25
- **WT:** 0.01

### Scroll (Expeditious Retreat)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Expeditious Retreat
- **COST:** 25
- **WT:** 0.01

### Scroll (Feather Fall)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Feather Fall
- **COST:** 25
- **WT:** 0.01

### Scroll (Grease)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Grease
- **COST:** 25
- **WT:** 0.01

### Scroll (Hold Portal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Hold Portal
- **COST:** 25
- **WT:** 0.01

### Scroll (Hypnotism)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Hypnotism
- **COST:** 25
- **WT:** 0.01

### Scroll (Identify)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Identify
- **COST:** 125
- **WT:** 0.01
- **SPROP:** Determine all magic properties of a single magic item, including how to activate those functions and number of charges (PH p.243)

### Scroll (Jump/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Jump
- **COST:** 25
- **WT:** 0.01

### Scroll (Mage Armor)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Mage Armor
- **COST:** 25
- **WT:** 0.01
- **SPROP:** +4 armor bonus to AC for 1 hour

### Scroll (Magic Missile)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Magic Missile
- **COST:** 25
- **WT:** 0.01
- **SPROP:** One missile travels up to 110' to strike a target for 1d4+1 damage, no save.

### Scroll (Magic Weapon/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Magic Weapon
- **COST:** 25
- **WT:** 0.01

### Scroll (Mount)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Mount
- **COST:** 25
- **WT:** 0.01
- **SPROP:** Summons a light horse for 2 hours. 6 Miles/hour (or Hustle for 12) (PH 256)

### Scroll (Magic Aura)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Magic Aura
- **COST:** 25
- **WT:** 0.01
- **SPROP:** 5lb item gains or loses a magical aura for 1 day (PH 257)

### Scroll (Obscuring Mist/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Obscuring Mist
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Chaos/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Chaos
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Evil/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Evil
- **EQMOD:** SPL_CHRG|SPELLNAME[Protection from Evil]SPELLLEVEL[1]CASTERLEVEL[1]
- **SPROP:** Protects against physical touch and charm, and increases AC/Saves against, evil or summoned creatures (PH 266)
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Good/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Good
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Law/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Law
- **COST:** 25
- **WT:** 0.01

### Scroll (Ray of Enfeeblement)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Ray of Enfeeblement
- **COST:** 25
- **WT:** 0.01

### Scroll (Reduce Person)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Reduce Person
- **SPROP:** Humanoid target within 45' is halved in height/weight/width and weight is reduced to 1/8th. Size category is reduced by 1, the target gains +2 size bonus to dex, -2 Str and +1 bonus to attack and AC. Lasts 1 minute (PH269)
- **COST:** 25
- **WT:** 0.01

### Scroll (Remove Fear/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Remove Fear
- **COST:** 50
- **WT:** 0.01

### Scroll (Shield)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Shield
- **COST:** 25
- **WT:** 0.01
- **SPROP:** +4 AC shield for 10 minutes, blocks magic missiles (PH278)

### Scroll (Shield/Wizard/2nd)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=2|Shield
- **COST:** 25
- **WT:** 0.01
- **SPROP:** +4 AC shield for 20 minutes, blocks magic missiles (PH278)

### Scroll (Shocking Grasp)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Shocking Grasp
- **COST:** 25
- **WT:** 0.01

### Scroll (Silent Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Silent Image
- **COST:** 25
- **WT:** 0.01

### Scroll (Sleep)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Sleep
- **COST:** 25
- **WT:** 0.01
- **SPROP:** 4 HD of monsters in a 10-ft radius sleep, lowest HD first. Will negates DC 11 (PH 280)

### Scroll (Summon Monster I/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Summon Monster I
- **COST:** 25
- **WT:** 0.01

### Scroll (Floating Disk)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Floating Disk
- **COST:** 25
- **WT:** 0.01
- **SPROP:** 3' Disk can hold 100lbs of weight (or 2 gallons of fluid) for 1 hour. Floats 3' above ground and within 25' of you (PH 294)

### Scroll (True Strike)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|True Strike
- **COST:** 25
- **WT:** 0.01

### Scroll (Undetectable Alignment/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Undetectable Alignment
- **COST:** 50
- **WT:** 0.01

### Scroll (Unseen Servant)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Unseen Servant
- **COST:** 25
- **WT:** 0.01

### Scroll (Ventriloquism)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Ventriloquism
- **COST:** 25
- **WT:** 0.01
- **SPROP:** 10 minute illusion of intelligible sound (within 25') (PH298)

### Scroll (Animal Messenger/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Animal Messenger
- **COST:** 200
- **WT:** 0.01

### Scroll (Animal Trance/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Animal Trance
- **COST:** 200
- **WT:** 0.01

### Scroll (Arcane Lock)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Arcane Lock
- **COST:** 175
- **WT:** 0.01

### Scroll (Bear's Endurance/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Bear's Endurance
- **COST:** 150
- **WT:** 0.01

### Scroll (Blindness/Deafness/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Blindness/Deafness
- **COST:** 150
- **WT:** 0.01

### Scroll (Blur)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Blur
- **COST:** 150
- **WT:** 0.01

### Scroll (Bull's Strength/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Bull's Strength
- **COST:** 150
- **WT:** 0.01
- **SPROP:** +4 Strength for 3 minutes

### Scroll (Calm Emotions/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Calm Emotions
- **COST:** 200
- **WT:** 0.01

### Scroll (Cat's Grace/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Cat's Grace
- **COST:** 150
- **WT:** 0.01

### Scroll (Command Undead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Command Undead
- **COST:** 150
- **WT:** 0.01

### Scroll (Continual Flame/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Continual Flame
- **COST:** 200
- **WT:** 0.01

### Scroll (Cure Moderate Wounds/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Cure Moderate Wounds
- **SPROP:** Cures 2d8 +3 damage (PH P.216)
- **COST:** 200
- **WT:** 0.01

### Scroll (Darkness/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Darkness
- **COST:** 150
- **WT:** 0.01

### Scroll (Darkvision/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Darkvision
- **COST:** 150
- **WT:** 0.01
- **SPROP:** You gain 60' darkvision for 1 hour (PH P.216)

### Scroll (Daze Monster)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Daze Monster
- **COST:** 150
- **WT:** 0.01

### Scroll (Delay Poison/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Delay Poison
- **COST:** 200
- **WT:** 0.01
- **SPROP:** Target becomes immune to poison for 2 hours (PH P.217)

### Scroll (Detect Thoughts)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Detect Thoughts
- **COST:** 150
- **WT:** 0.01

### Scroll (Disguise Self/Lvl 2)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Disguise Self
- **COST:** 150
- **WT:** 0.01
- **SPROP:** You make yourself and your equipment look different - 1 foot shorter/taller, thin/fat, add/obscure minor feature or look like an entirely different person. +1 disguise for 20 minutes

### Scroll (Eagle's Splendor/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Eagle's Splendor
- **COST:** 150
- **WT:** 0.01

### Scroll (Enthrall/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Enthrall
- **COST:** 200
- **WT:** 0.01

### Scroll (False Life)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|False Life
- **COST:** 150
- **WT:** 0.01

### Scroll (Flaming Sphere/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Flaming Sphere
- **COST:** 150
- **WT:** 0.01

### Scroll (Fog Cloud/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Fog Cloud
- **COST:** 150
- **WT:** 0.01

### Scroll (Fox's Cunning)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Fox's Cunning
- **COST:** 150
- **WT:** 0.01
- **SPROP:** Gain +4 intelligence for 2 minutes. (PH P.233)

### Scroll (Ghoul Touch)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Ghoul Touch
- **COST:** 150
- **WT:** 0.01

### Scroll (Glitterdust)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Glitterdust
- **COST:** 150
- **WT:** 0.01

### Scroll (Gust of Wind/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Gust of Wind
- **COST:** 150
- **WT:** 0.01

### Scroll (Hypnotic Pattern)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Hypnotic Pattern
- **COST:** 150
- **WT:** 0.01

### Scroll (Invisibility)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Invisibility
- **SPROP:** Invisible for 3 minutes or until you attack (PH P.245)
- **COST:** 150
- **WT:** 0.01

### Scroll (Knock)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Knock
- **COST:** 150
- **WT:** 0.01
- **SPROP:** Open stuck,barred, locked, held or arcane locked doors. It opens secret doors, as well as locked or trick opening boxes or chests, it also loosens welds, shackles or chains. Affects an opening of of up to 10sq. ft/level (30') within 130' (PH P.246)

### Scroll (Phantom Trap)

- **COST:** 200
- **WT:** 0.01

### Scroll (Levitate)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Levitate
- **COST:** 150
- **WT:** 0.01
- **SPROP:** for 3 minutes you, or an object within 30' (upto 300lb) can move up or down at 20' round as a move action. Combat is unstable, gaining a penalty of -1 on attack rolls each round, up to -5. PH P.248

### Scroll (Locate Object/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Locate Object
- **COST:** 150
- **WT:** 0.01

### Scroll (Magic Mouth)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Magic Mouth
- **SPROP:** imbues an object or creature with an enchanted mouth that appears and speaks its message the next time a specified event occurs. (PH 251)
- **COST:** 160
- **WT:** 0.01

### Scroll (Acid Arrow)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Acid Arrow
- **COST:** 150
- **WT:** 0.01

### Scroll (Minor Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Minor Image
- **COST:** 150
- **WT:** 0.01
- **SPROP:** visual illusion of object creature or force, no more than 5 10-ft cubes. Minor sounds and image can move (PH 254)

### Scroll (Mirror Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Mirror Image
- **COST:** 150
- **WT:** 0.01
- **SPROP:** 1d4 Illusionary duplicates of you confound enemies for 3 minute

### Scroll (Misdirection)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Misdirection
- **COST:** 150
- **WT:** 0.01

### Scroll (Obscure Object/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Obscure Object
- **COST:** 150
- **WT:** 0.01

### Scroll (Owl's Wisdom/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Owl's Wisdom
- **COST:** 150
- **WT:** 0.01

### Scroll (Protection from Arrows)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Protection from Arrows
- **COST:** 150
- **WT:** 0.01

### Scroll (Pyrotechnics)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Pyrotechnics
- **COST:** 150
- **WT:** 0.01

### Scroll (Resist Energy/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Resist Energy
- **COST:** 150
- **WT:** 0.01

### Scroll (Rope Trick)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Rope Trick
- **COST:** 150
- **WT:** 0.01
- **SPROP:** creates extradimensional hiding space for 8 creatures for 3 hours (PH273)

### Scroll (Scare)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Scare
- **COST:** 150
- **WT:** 0.01

### Scroll (Scorching Ray)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Scorching Ray
- **COST:** 150
- **WT:** 0.01

### Scroll (See Invisibility)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|See Invisibility
- **COST:** 150
- **WT:** 0.01

### Scroll (Shatter/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Shatter
- **COST:** 150
- **WT:** 0.01

### Scroll (Silence/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Silence
- **COST:** 200
- **WT:** 0.01

### Scroll (Sound Burst/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Sound Burst
- **COST:** 200
- **WT:** 0.01

### Scroll (Spectral Hand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Spectral Hand
- **COST:** 150
- **WT:** 0.01

### Scroll (Spider Climb/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Spider Climb
- **COST:** 150
- **WT:** 0.01
- **SPROP:** Climb on vertical surfaces and ceilings for 30 minutes, climb speed 20 (PH283)

### Scroll (Summon Monster II/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Summon Monster II
- **COST:** 150
- **WT:** 0.01

### Scroll (Summon Swarm/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Summon Swarm
- **COST:** 150
- **WT:** 0.01

### Scroll (Trap)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Trap
- **COST:** 150
- **WT:** 0.01

### Scroll (Hideous Laughter)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Hideous Laughter
- **COST:** 150
- **WT:** 0.01

### Scroll (Touch of Idiocy)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Touch of Idiocy
- **COST:** 150
- **WT:** 0.01

### Scroll (Web)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Web
- **COST:** 150
- **WT:** 0.01

### Scroll (Whispering Wind)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Whispering Wind
- **COST:** 150
- **WT:** 0.01

### Scroll (Arcane Sight)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Arcane Sight
- **COST:** 375
- **WT:** 0.01

### Scroll (Blink)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Blink
- **COST:** 375
- **WT:** 0.01

### Scroll (Clairaudience/Clairvoyance)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Clairaudience/Clairvoyance
- **COST:** 375
- **WT:** 0.01

### Scroll (Cure Serious Wounds/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Cure Serious Wounds
- **COST:** 525
- **WT:** 0.01
- **SPROP:** Cures 3d8+5 damage (PH P.216)

### Scroll (Daylight/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Daylight
- **COST:** 525
- **WT:** 0.01

### Scroll (Deep Slumber)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Deep Slumber
- **COST:** 375
- **WT:** 0.01

### Scroll (Dispel Magic/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Dispel Magic
- **SPROP:** End ongoing spells that have been cast on a creature or object, to temporarily suppress the magical abilities of a magic item (PH 223)
- **COST:** 375
- **WT:** 0.01

### Scroll (Displacement)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Displacement
- **COST:** 375
- **WT:** 0.01

### Scroll (Explosive Runes)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Explosive Runes
- **COST:** 375
- **WT:** 0.01

### Scroll (Fireball)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Fireball
- **COST:** 375
- **WT:** 0.01

### Scroll (Flame Arrow)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Flame Arrow
- **COST:** 375
- **WT:** 0.01

### Scroll (Fly)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Fly
- **SPROP:** fly speed 60' for 5 minutes. Good maneuverability.
- **COST:** 375
- **WT:** 0.01

### Scroll (Gaseous Form)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Gaseous Form
- **COST:** 375
- **WT:** 0.01

### Scroll (Gentle Repose/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Gentle Repose
- **COST:** 375
- **WT:** 0.01

### Scroll (Glibness)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Glibness
- **COST:** 525
- **WT:** 0.01

### Scroll (Good Hope)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Good Hope
- **COST:** 525
- **WT:** 0.01

### Scroll (Halt Undead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Halt Undead
- **COST:** 375
- **WT:** 0.01

### Scroll (Haste)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Haste
- **COST:** 375
- **WT:** 0.01

### Scroll (Heroism)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Heroism
- **SPROP:** +2 Morale bonus on attacks, saves and skills for 50 minutes
- **COST:** 375
- **WT:** 0.01

### Scroll (Hold Person/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Hold Person
- **COST:** 375
- **WT:** 0.01

### Scroll (Illusory Script)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Illusory Script
- **COST:** 425
- **WT:** 0.01

### Scroll (Invisibility Sphere)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Invisibility Sphere
- **COST:** 375
- **WT:** 0.01

### Scroll (Keen Edge)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Keen Edge
- **COST:** 375
- **WT:** 0.01

### Scroll (Tiny Hut)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Tiny Hut
- **COST:** 375
- **WT:** 0.01

### Scroll (Lightning Bolt)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Lightning Bolt
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Chaos/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Chaos
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Evil/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Evil
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Good/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Good
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Law/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Law
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Weapon/Greater/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Weapon (Greater)
- **COST:** 375
- **WT:** 0.01

### Scroll (Major Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Major Image
- **COST:** 375
- **WT:** 0.01

### Scroll (Nondetection/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Nondetection
- **SPROP:** Difficult to detect by divination spells for 5 hours (PH P.245)
- **COST:** 425
- **WT:** 0.01

### Scroll (Phantom Steed)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Phantom Steed
- **COST:** 375
- **WT:** 0.01

### Scroll (Protection from Energy/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Protection from Energy
- **COST:** 375
- **WT:** 0.01

### Scroll (Rage)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Rage
- **COST:** 375
- **WT:** 0.01

### Scroll (Ray of Exhaustion)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Ray of Exhaustion
- **COST:** 375
- **WT:** 0.01

### Scroll (Sculpt Sound)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Sculpt Sound
- **COST:** 525
- **WT:** 0.01

### Scroll (Secret Page)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Secret Page
- **COST:** 375
- **WT:** 0.01

### Scroll (Sepia Snake Sigil)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Sepia Snake Sigil
- **COST:** 875
- **WT:** 0.01

### Scroll (Shrink Item)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Shrink Item
- **COST:** 375
- **WT:** 0.01

### Scroll (Sleet Storm/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Sleet Storm
- **COST:** 375
- **WT:** 0.01

### Scroll (Slow)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Slow
- **COST:** 375
- **WT:** 0.01

### Scroll (Speak with Animals/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Speak with Animals
- **COST:** 525
- **WT:** 0.01

### Scroll (Stinking Cloud)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Stinking Cloud
- **COST:** 375
- **WT:** 0.01

### Scroll (Suggestion)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Suggestion
- **EQMOD:** SPL_CHRG|SPELLNAME[Suggestion]SPELLLEVEL[3]CASTERLEVEL[5]
- **COST:** 375
- **WT:** 0.01
- **SPROP:** Compels one living subject to follow stated course of action for 5 hours. DC:13, Range 45'

### Scroll (Summon Monster III/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Summon Monster III
- **COST:** 375
- **WT:** 0.01

### Scroll (Tongues/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Tongues
- **COST:** 375
- **WT:** 0.01

### Scroll (Vampiric Touch)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Vampiric Touch
- **COST:** 375
- **WT:** 0.01

### Scroll (Water Breathing/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Water Breathing
- **COST:** 375
- **WT:** 0.01
- **SPROP:** You can breathe underwater for 6 hours (PH P300).

### Scroll (Wind Wall/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Wind Wall
- **COST:** 375
- **WT:** 0.01

### Scroll (Animate Dead/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Animate Dead
- **COST:** 1050
- **WT:** 0.01

### Scroll (Arcane Eye)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Arcane Eye
- **COST:** 700
- **WT:** 0.01

### Scroll (Bestow Curse/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Bestow Curse
- **COST:** 700
- **WT:** 0.01

### Scroll (Charm Monster)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Charm Monster
- **COST:** 700
- **WT:** 0.01

### Scroll (Confusion)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Confusion
- **COST:** 700
- **WT:** 0.01

### Scroll (Contagion/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Contagion
- **COST:** 700
- **WT:** 0.01

### Scroll (Crushing Despair)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Crushing Despair
- **COST:** 700
- **WT:** 0.01

### Scroll (Cure Critical Wounds/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Cure Critical Wounds
- **SPROP:** Cures 4d8+7 damage (PH P.215)
- **COST:** 1000
- **WT:** 0.01

### Scroll (Detect Scrying)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Detect Scrying
- **COST:** 700
- **WT:** 0.01

### Scroll (Dimension Door)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Dimension Door
- **COST:** 700
- **WT:** 0.01

### Scroll (Dimensional Anchor/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Dimensional Anchor
- **COST:** 700
- **WT:** 0.01

### Scroll (Enervation)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Enervation
- **COST:** 700
- **WT:** 0.01

### Scroll (Enlarge Person/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Enlarge Person (Mass)
- **COST:** 700
- **WT:** 0.01

### Scroll (Black Tentacles)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Black Tentacles
- **COST:** 700
- **WT:** 0.01

### Scroll (Fear)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Fear
- **COST:** 700
- **WT:** 0.01

### Scroll (Fire Shield)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Fire Shield
- **COST:** 700
- **WT:** 0.01
- **SPROP:** Cause 1d6+7 damage to anyone who hits you with melee attacks, lasts 7 rounds

### Scroll (Fire Trap/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Fire Trap
- **COST:** 725
- **WT:** 0.01

### Scroll (Freedom of Movement/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Freedom of Movement
- **COST:** 1000
- **WT:** 0.01

### Scroll (Geas/Lesser)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Geas (Lesser)
- **COST:** 700
- **WT:** 0.01

### Scroll (Globe of Invulnerability/Lesser)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Globe of Invulnerability (Lesser)
- **COST:** 700
- **WT:** 0.01
- **SPROP:** No spells of 3rd level or lower can affect a 10' radius around you, for 7 rounds

### Scroll (Hallucinatory Terrain)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Hallucinatory Terrain
- **COST:** 700
- **WT:** 0.01

### Scroll (Ice Storm/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Ice Storm
- **COST:** 700
- **WT:** 0.01

### Scroll (Illusory Wall)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Illusory Wall
- **COST:** 700
- **WT:** 0.01

### Scroll (Invisibility/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Invisibility (Greater)
- **COST:** 700
- **WT:** 0.01

### Scroll (Secure Shelter)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Secure Shelter
- **COST:** 700
- **WT:** 0.01

### Scroll (Locate Creature)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Locate Creature
- **COST:** 700
- **WT:** 0.01

### Scroll (Minor Creation)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Minor Creation
- **COST:** 700
- **WT:** 0.01

### Scroll (Modify Memory)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Modify Memory
- **COST:** 1000
- **WT:** 0.01

### Scroll (Neutralize Poison/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Neutralize Poison
- **SPROP:** Neutralize any existing poison and prevent any poison from affecting the drinker for 70 minutes (PH 257)
- **COST:** 1000
- **WT:** 0.01

### Scroll (Resilient Sphere)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Resilient Sphere
- **COST:** 700
- **WT:** 0.01

### Scroll (Phantasmal Killer)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Phantasmal Killer
- **COST:** 700
- **WT:** 0.01

### Scroll (Polymorph)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Polymorph
- **COST:** 700
- **WT:** 0.01

### Scroll (Rainbow Pattern)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Rainbow Pattern
- **COST:** 700
- **WT:** 0.01

### Scroll (Mnemonic Enhancer)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Mnemonic Enhancer
- **COST:** 700
- **WT:** 0.01

### Scroll (Reduce Person/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Reduce Person (Mass)
- **SPROP:** (PH P269)Humanoid target within 45' is halved in height/weight/width and weight is reduced to 1/8th. Size category is reduced by 1, the target gains +2 size bonus to dex, -2 Str and +1 bonus to attack and AC. Lasts 7 minutes
- **COST:** 700
- **WT:** 0.01

### Scroll (Remove Curse/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Remove Curse
- **COST:** 700
- **WT:** 0.01

### Scroll (Repel Vermin/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Repel Vermin
- **COST:** 1000
- **WT:** 0.01

### Scroll (Scrying/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Scrying
- **COST:** 700
- **WT:** 0.01

### Scroll (Shadow Conjuration)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Shadow Conjuration
- **COST:** 700
- **WT:** 0.01

### Scroll (Shout)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Shout
- **COST:** 700
- **WT:** 0.01

### Scroll (Solid Fog)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Solid Fog
- **COST:** 700
- **WT:** 0.01

### Scroll (Speak with Plants/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Speak with Plants
- **COST:** 1000
- **WT:** 0.01

### Scroll (Stone Shape/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Stone Shape
- **COST:** 700
- **WT:** 0.01

### Scroll (Stoneskin/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Stoneskin
- **COST:** 950
- **WT:** 0.01

### Scroll (Summon Monster IV/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Summon Monster IV
- **COST:** 700
- **WT:** 0.01

### Scroll (Wall of Fire/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Wall of Fire
- **COST:** 700
- **WT:** 0.01

### Scroll (Wall of Ice)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Wall of Ice
- **COST:** 700
- **WT:** 0.01

### Scroll (Zone of Silence)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Zone of Silence
- **COST:** 1000
- **WT:** 0.01

### Scroll (Animal Growth/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Animal Growth
- **COST:** 1125
- **WT:** 0.01

### Scroll (Baleful Polymorph/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Baleful Polymorph
- **COST:** 1125
- **WT:** 0.01

### Scroll (Interposing Hand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Interposing Hand
- **COST:** 1125
- **WT:** 0.01

### Scroll (Blight/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Blight
- **COST:** 1125
- **WT:** 0.01

### Scroll (Break Enchantment/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Break Enchantment
- **COST:** 1125
- **WT:** 0.01

### Scroll (Cloudkill)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Cloudkill
- **COST:** 1125
- **WT:** 0.01
- **SPROP:** 20'radius bank of fog, kills anything living with 3 or less HD, 4-6HD get a fortitude save or die (or take 1d4 con damage per round). 6HD or more take 1d4 con damage (Fort save for half). lasts 9 minutes, moves 10' round away from you.

### Scroll (Cone of Cold)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Cone of Cold
- **COST:** 1125
- **WT:** 0.01

### Scroll (Contact Other Plane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Contact Other Plane
- **COST:** 1125
- **WT:** 0.01

### Scroll (Cure Light Wounds/Mass/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Cure Light Wounds (Mass)
- **COST:** 1625
- **WT:** 0.01
- **SPROP:** Cures 1d8 +9 damage (PH P.216)

### Scroll (Dismissal/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dismissal
- **COST:** 1125
- **WT:** 0.01
- **SPROP:** Force an extraplanar creature back to its proper plane (Will save negates)

### Scroll (Dispel Magic/Greater/Arcane/Lvl 5)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dispel Magic (Greater)
- **COST:** 1625
- **WT:** 0.01

### Scroll (Dominate Person)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dominate Person
- **COST:** 1125
- **WT:** 0.01

### Scroll (Dream)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dream
- **COST:** 1125
- **WT:** 0.01

### Scroll (Fabricate)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Fabricate
- **COST:** 1125
- **WT:** 0.01

### Scroll (False Vision)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|False Vision
- **COST:** 1375
- **WT:** 0.01

### Scroll (Feeblemind)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Feeblemind
- **COST:** 1125
- **WT:** 0.01

### Scroll (Hold Monster)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Hold Monster
- **COST:** 1125
- **SPROP:** Paralyzes one monster for 9 rounds.
- **WT:** 0.01

### Scroll (Secret Chest)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Secret Chest
- **COST:** 1125
- **WT:** 0.01

### Scroll (Magic Jar)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Magic Jar
- **COST:** 1125
- **WT:** 0.01

### Scroll (Major Creation)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Major Creation
- **COST:** 1125
- **WT:** 0.01

### Scroll (Mind Fog)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Mind Fog
- **COST:** 1125
- **WT:** 0.01

### Scroll (Mirage Arcana)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Mirage Arcana
- **COST:** 1125
- **WT:** 0.01

### Scroll (Mage's Faithful Hound)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Mage's Faithful Hound
- **COST:** 1125
- **WT:** 0.01

### Scroll (Mage's Private Sanctum)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Mage's Private Sanctum
- **COST:** 1125
- **WT:** 0.01

### Scroll (Nightmare)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Nightmare
- **COST:** 1125
- **WT:** 0.01

### Scroll (Overland Flight)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Overland Flight
- **COST:** 1125
- **WT:** 0.01

### Scroll (Passwall)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Passwall
- **EQMOD:** SPL_CHRG|SPELLNAME[Passwall]SPELLLEVEL[5]CASTERLEVEL[9]
- **SPROP:** Create a 5' by 8' opening 25' deep through wood or stone (PH 259)
- **COST:** 1125
- **WT:** 0.01

### Scroll (Permanency)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Permanency
- **COST:** 10125
- **WT:** 0.01

### Scroll (Persistent Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Persistent Image
- **COST:** 1125
- **WT:** 0.01

### Scroll (Planar Binding/Lesser)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Planar Binding (Lesser)
- **COST:** 1125
- **WT:** 0.01

### Scroll (Prying Eyes)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Prying Eyes
- **COST:** 1125
- **WT:** 0.01

### Scroll (Telepathic Bond)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Telepathic Bond
- **COST:** 1125
- **WT:** 0.01

### Scroll (Seeming)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Seeming
- **COST:** 1125
- **WT:** 0.01

### Scroll (Sending/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Sending
- **COST:** 1125
- **WT:** 0.01

### Scroll (Shadow Evocation)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Shadow Evocation
- **COST:** 1125
- **WT:** 0.01

### Scroll (Song of Discord)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Song of Discord
- **COST:** 1625
- **WT:** 0.01

### Scroll (Summon Monster V/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Summon Monster V
- **COST:** 1125
- **WT:** 0.01

### Scroll (Symbol of Pain/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Symbol of Pain
- **COST:** 2125
- **WT:** 0.01

### Scroll (Symbol of Sleep/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Symbol of Sleep
- **COST:** 2125
- **WT:** 0.01

### Scroll (Telekinesis)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Telekinesis
- **COST:** 1125
- **WT:** 0.01

### Scroll (Teleport)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Teleport
- **COST:** 1125
- **WT:** 0.01
- **SPROP:** Teleports you and up to 3 additional medium or smaller creatures to a designated destination, up to 900 miles away. You may all bring objects as long as their weight doesnt exceed your maximum load. A Large creature counts as two medium creatures. There is a chance of being off target or having a mishap based on your familiarity with the destination. (PH p.293)

### Scroll (Transmute Mud to Rock/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Transmute Mud to Rock
- **COST:** 1125
- **WT:** 0.01

### Scroll (Transmute Rock to Mud/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Transmute Rock to Mud
- **COST:** 1125
- **WT:** 0.01

### Scroll (Wall of Force)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Wall of Force
- **EQMOD:** SPL_CHRG|SPELLNAME[Wall of Force]SPELLLEVEL[5]CASTERLEVEL[9]
- **COST:** 1125
- **WT:** 0.01
- **SPROP:** Creates an invisible wall covering 9 x 10 ft squares

### Scroll (Wall of Stone/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Wall of Stone
- **COST:** 1125
- **WT:** 0.01

### Scroll (Waves of Fatigue)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Waves of Fatigue
- **COST:** 1125
- **WT:** 0.01

### Scroll (Acid Fog)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Acid Fog
- **COST:** 1650
- **WT:** 0.01

### Scroll (Analyze Dweomer)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Analyze Dweomer
- **COST:** 1650
- **WT:** 0.01

### Scroll (Animate Objects/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Animate Objects
- **COST:** 2400
- **WT:** 0.01

### Scroll (Antimagic Field/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Antimagic Field
- **COST:** 1650
- **WT:** 0.01

### Scroll (Bear's Endurance/Mass/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Bear's Endurance (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Forceful Hand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Forceful Hand
- **COST:** 1650
- **WT:** 0.01

### Scroll (Bull's Strength/Mass/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Bull's Strength (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Cat's Grace/Mass/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Cat's Grace (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Chain Lightning)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Chain Lightning
- **COST:** 1650
- **WT:** 0.01

### Scroll (Circle of Death)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Circle of Death
- **COST:** 2150
- **WT:** 0.01

### Scroll (Contingency)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Contingency
- **COST:** 1650
- **WT:** 0.01

### Scroll (Control Water/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Control Water
- **COST:** 1650
- **WT:** 0.01

### Scroll (Create Undead/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Create Undead
- **COST:** 2350
- **WT:** 0.01

### Scroll (Cure Moderate Wounds/Mass/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Cure Moderate Wounds (Mass)
- **SPROP:** Cures 2d8 +11 damage (PH P.216)
- **COST:** 2400
- **WT:** 0.01

### Scroll (Disintegrate)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Disintegrate
- **COST:** 1650
- **WT:** 0.01

### Scroll (Dispel Magic/Greater/Arcane/Lvl 6)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Dispel Magic (Greater)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Eagle's Splendor/Mass/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Eagle's Splendor (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Eyebite)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Eyebite
- **COST:** 1650
- **WT:** 0.01

### Scroll (Find the Path/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Find the Path
- **COST:** 2400
- **WT:** 0.01

### Scroll (Flesh to Stone)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Flesh to Stone
- **COST:** 1650
- **WT:** 0.01

### Scroll (Fox's Cunning/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Fox's Cunning (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Geas/Quest/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Geas/Quest
- **COST:** 1650
- **WT:** 0.01

### Scroll (Globe of Invulnerability)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Globe of Invulnerability
- **COST:** 1650
- **WT:** 0.01
- **SPROP:** No spells of 4th level or lower can affect a 10' radius around you, for 11 rounds

### Scroll (Guards and Wards)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Guards and Wards
- **COST:** 1650
- **WT:** 0.01

### Scroll (Heroes' Feast/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Heroes' Feast
- **COST:** 2400
- **WT:** 0.01

### Scroll (Heroism/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Heroism (Greater)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Legend Lore)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Legend Lore
- **COST:** 1900
- **WT:** 0.01

### Scroll (Mislead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Mislead
- **COST:** 1650
- **WT:** 0.01

### Scroll (Mage's Lucubration)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Mage's Lucubration
- **COST:** 1650
- **WT:** 0.01

### Scroll (Move Earth/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Move Earth
- **COST:** 1650
- **WT:** 0.01

### Scroll (Freezing Sphere)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Freezing Sphere
- **COST:** 1650
- **WT:** 0.01

### Scroll (Owl's Wisdom/Mass/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Owl's Wisdom (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Permanent Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Permanent Image
- **COST:** 1650
- **WT:** 0.01

### Scroll (Planar Binding)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Planar Binding
- **COST:** 1650
- **WT:** 0.01

### Scroll (Programmed Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Programmed Image
- **COST:** 1675
- **WT:** 0.01

### Scroll (Repulsion/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Repulsion
- **COST:** 1650
- **WT:** 0.01

### Scroll (Shadow Walk)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Shadow Walk
- **COST:** 1650
- **WT:** 0.01

### Scroll (Stone to Flesh)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Stone to Flesh
- **COST:** 1650
- **WT:** 0.01

### Scroll (Suggestion/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Suggestion (Mass)
- **COST:** 1650
- **WT:** 0.01
- **SPROP:** Compels 11 living subjects within 30' of each other to follow stated course of action for 11 hours. DC:14, Range 210' (PH 285)

### Scroll (Summon Monster VI/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Summon Monster VI
- **COST:** 1650
- **WT:** 0.01

### Scroll (Symbol of Fear/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Symbol of Fear
- **COST:** 2650
- **WT:** 0.01

### Scroll (Symbol of Persuasion/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Symbol of Persuasion
- **COST:** 6650
- **WT:** 0.01

### Scroll (Sympathetic Vibration)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Sympathetic Vibration
- **COST:** 2400
- **WT:** 0.01

### Scroll (Transformation)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Transformation
- **COST:** 1950
- **WT:** 0.01

### Scroll (True Seeing/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|True Seeing
- **COST:** 1900
- **WT:** 0.01

### Scroll (Undeath to Death/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Undeath to Death
- **COST:** 2150
- **WT:** 0.01

### Scroll (Veil)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Veil
- **COST:** 1650
- **WT:** 0.01

### Scroll (Wall of Iron)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Wall of Iron
- **COST:** 1700
- **WT:** 0.01

### Scroll (Arcane Sight/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Arcane Sight (Greater)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Banishment/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Banishment
- **COST:** 2275
- **WT:** 0.01

### Scroll (Grasping Hand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Grasping Hand
- **COST:** 2275
- **WT:** 0.01

### Scroll (Control Undead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Control Undead
- **COST:** 2275
- **WT:** 0.01

### Scroll (Control Weather/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Control Weather
- **COST:** 2275
- **WT:** 0.01

### Scroll (Delayed Blast Fireball)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Delayed Blast Fireball
- **COST:** 2275
- **WT:** 0.01

### Scroll (Instant Summons)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Instant Summons
- **COST:** 3275
- **WT:** 0.01

### Scroll (Ethereal Jaunt/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Ethereal Jaunt
- **COST:** 2275
- **WT:** 0.01

### Scroll (Finger of Death/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Finger of Death
- **COST:** 2275
- **WT:** 0.01

### Scroll (Forcecage)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Forcecage
- **COST:** 23775
- **WT:** 0.01
- **SPROP:** 20' cubed barred cell or 10' window less cell for 14 hours

### Scroll (Hold Person/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Hold Person (Mass)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Insanity)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Insanity
- **COST:** 2275
- **WT:** 0.01

### Scroll (Invisibility/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Invisibility (Mass)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Limited Wish)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Limited Wish
- **COST:** 3775
- **WT:** 0.01

### Scroll (Mage's Magnificent Mansion)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Mage's Magnificent Mansion
- **COST:** 2275
- **WT:** 0.01

### Scroll (Mage's Sword)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Mage's Sword
- **COST:** 2275
- **WT:** 0.01

### Scroll (Phase Door)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Phase Door
- **COST:** 2275
- **WT:** 0.01

### Scroll (Plane Shift/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Plane Shift
- **COST:** 2275
- **WT:** 0.01

### Scroll (Power Word Blind)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Power Word Blind
- **COST:** 2275
- **WT:** 0.01

### Scroll (Prismatic Spray)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Prismatic Spray
- **COST:** 2275
- **WT:** 0.01

### Scroll (Project Image)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Project Image
- **COST:** 2280
- **WT:** 0.01

### Scroll (Reverse Gravity/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Reverse Gravity
- **COST:** 2275
- **WT:** 0.01

### Scroll (Scrying/Greater/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Scrying (Greater)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Sequester)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Sequester
- **COST:** 2275
- **WT:** 0.01

### Scroll (Shadow Conjuration/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Shadow Conjuration (Greater)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Simulacrum)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Simulacrum
- **COST:** 7275
- **WT:** 0.01

### Scroll (Spell Turning)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Spell Turning
- **COST:** 2275
- **WT:** 0.01
- **SPROP:** Spells targeting you are turned back on the caster for upto 130 minutes (reflects 1d4+6 levels, see PH 282)

### Scroll (Statue)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Statue
- **COST:** 2275
- **WT:** 0.01

### Scroll (Summon Monster VII/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Summon Monster VII
- **COST:** 2275
- **WT:** 0.01

### Scroll (Symbol of Stunning/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Symbol of Stunning
- **COST:** 7275
- **WT:** 0.01

### Scroll (Symbol of Weakness/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Symbol of Weakness
- **COST:** 7275
- **WT:** 0.01

### Scroll (Teleport Object)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Teleport Object
- **COST:** 2275
- **WT:** 0.01

### Scroll (Teleport/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Teleport (Greater)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Vision)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Vision
- **COST:** 2775
- **WT:** 0.01

### Scroll (Waves of Exhaustion)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Waves of Exhaustion
- **COST:** 2275
- **WT:** 0.01

### Scroll (Antipathy/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Antipathy
- **COST:** 3000
- **WT:** 0.01

### Scroll (Clenched Fist)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Clenched Fist
- **COST:** 3000
- **WT:** 0.01

### Scroll (Binding)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Binding
- **COST:** 8500
- **WT:** 0.01

### Scroll (Charm Monster/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Charm Monster (Mass)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Clone)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Clone
- **COST:** 4000
- **WT:** 0.01

### Scroll (Create Greater Undead/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Create Greater Undead
- **COST:** 3000
- **WT:** 0.01

### Scroll (Demand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Demand
- **COST:** 3600
- **WT:** 0.01

### Scroll (Dimensional Lock/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Dimensional Lock
- **COST:** 3000
- **WT:** 0.01

### Scroll (Discern Location/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Discern Location
- **COST:** 3000
- **WT:** 0.01

### Scroll (Horrid Wilting)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Horrid Wilting
- **SPROP:** 15d6 damage to living creatures within 60' of each other at Long range. Fortitude for half
- **COST:** 3000
- **WT:** 0.01

### Scroll (Incendiary Cloud)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Incendiary Cloud
- **COST:** 3000
- **WT:** 0.01

### Scroll (Iron Body)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Iron Body
- **COST:** 3000
- **WT:** 0.01

### Scroll (Maze)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Maze
- **COST:** 3000
- **WT:** 0.01

### Scroll (Mind Blank)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Mind Blank
- **COST:** 3000
- **WT:** 0.01

### Scroll (Moment of Prescience)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Moment of Prescience
- **COST:** 3000
- **WT:** 0.01

### Scroll (Telekinetic Sphere)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Telekinetic Sphere
- **COST:** 3000
- **WT:** 0.01

### Scroll (Irresistible Dance)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Irresistible Dance
- **COST:** 3000
- **WT:** 0.01

### Scroll (Planar Binding/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Planar Binding (Greater)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Polar Ray)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Polar Ray
- **COST:** 3000
- **WT:** 0.01

### Scroll (Polymorph Any Object)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Polymorph Any Object
- **COST:** 3000
- **WT:** 0.01
- **SPROP:** Change one object or creature into another, duration depends on how radical a change is made. Gain physical stats of new form(PH p.263)

### Scroll (Power Word Stun)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Power Word Stun
- **COST:** 3000
- **WT:** 0.01

### Scroll (Prismatic Wall)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Prismatic Wall
- **COST:** 3000
- **WT:** 0.01

### Scroll (Protection from Spells)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Protection from Spells
- **COST:** 3500
- **WT:** 0.01

### Scroll (Prying Eyes/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Prying Eyes (Greater)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Scintillating Pattern)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Scintillating Pattern
- **COST:** 3000
- **WT:** 0.01

### Scroll (Screen)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Screen
- **COST:** 3000
- **WT:** 0.01

### Scroll (Shadow Evocation/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Shadow Evocation (Greater)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Shout/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Shout (Greater)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Summon Monster VIII/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Summon Monster VIII
- **COST:** 3000
- **WT:** 0.01

### Scroll (Sunburst/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Sunburst
- **COST:** 3000
- **WT:** 0.01

### Scroll (Symbol of Death/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Symbol of Death
- **COST:** 8000
- **WT:** 0.01

### Scroll (Symbol of Insanity/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Symbol of Insanity
- **COST:** 8000
- **WT:** 0.01

### Scroll (Sympathy/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Sympathy
- **COST:** 4500
- **WT:** 0.01

### Scroll (Temporal Stasis)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Temporal Stasis
- **COST:** 3500
- **WT:** 0.01

### Scroll (Trap the Soul)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Trap the Soul
- **COST:** 13000
- **WT:** 0.01

### Scroll (Astral Projection/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Astral Projection
- **COST:** 4870
- **WT:** 0.01

### Scroll (Crushing Hand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Crushing Hand
- **COST:** 3825
- **WT:** 0.01

### Scroll (Dominate Monster)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Dominate Monster
- **COST:** 3825
- **WT:** 0.01

### Scroll (Energy Drain/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Energy Drain
- **COST:** 3825
- **WT:** 0.01

### Scroll (Etherealness/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Etherealness
- **COST:** 3825
- **WT:** 0.01

### Scroll (Foresight/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Foresight
- **COST:** 3825
- **WT:** 0.01

### Scroll (Freedom)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Freedom
- **COST:** 3825
- **WT:** 0.01

### Scroll (Gate/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Gate
- **COST:** 8825
- **WT:** 0.01

### Scroll (Hold Monster/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Hold Monster (Mass)
- **COST:** 3825
- **WT:** 0.01

### Scroll (Imprisonment)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Imprisonment
- **COST:** 3825
- **WT:** 0.01

### Scroll (Meteor Swarm)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Meteor Swarm
- **COST:** 3825
- **WT:** 0.01

### Scroll (Mage's Disjunction)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Mage's Disjunction
- **COST:** 3825
- **WT:** 0.01

### Scroll (Power Word Kill)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Power Word Kill
- **COST:** 3825
- **WT:** 0.01

### Scroll (Prismatic Sphere)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Prismatic Sphere
- **COST:** 3825
- **WT:** 0.01

### Scroll (Refuge/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Refuge
- **COST:** 3825
- **WT:** 0.01

### Scroll (Shades)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Shades
- **COST:** 3825
- **WT:** 0.01

### Scroll (Shapechange/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Shapechange
- **COST:** 3825
- **WT:** 0.01

### Scroll (Soul Bind/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Soul Bind
- **COST:** 3825
- **WT:** 0.01

### Scroll (Summon Monster IX/Arcane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Summon Monster IX
- **COST:** 3825
- **WT:** 0.01

### Scroll (Teleportation Circle)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Teleportation Circle
- **COST:** 4825
- **WT:** 0.01

### Scroll (Time Stop)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Time Stop
- **COST:** 3825
- **WT:** 0.01

### Scroll (Wail of the Banshee)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Wail of the Banshee
- **COST:** 3825
- **WT:** 0.01

### Scroll (Weird)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Weird
- **COST:** 3825
- **WT:** 0.01

### Scroll (Wish)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Wish
- **COST:** 28825
- **WT:** 0.01

### Scroll (Create Water)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Create Water
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Cure Minor Wounds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Cure Minor Wounds
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Detect Magic/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Magic
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Detect Poison/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Poison
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Flare/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Flare
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Guidance)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Guidance
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Inflict Minor Wounds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Inflict Minor Wounds
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Know Direction/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Know Direction
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Light/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Light
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Mending/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Mending
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Purify Food and Drink)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Purify Food and Drink
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Read Magic/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Read Magic
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Resistance/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Resistance
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Virtue)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Virtue
- **COST:** 12.5
- **WT:** 0.01

### Scroll (Alarm/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Alarm
- **COST:** 100
- **WT:** 0.01

### Scroll (Bane)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Bane
- **COST:** 25
- **WT:** 0.01

### Scroll (Bless)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Bless
- **COST:** 25
- **WT:** 0.01

### Scroll (Bless Water)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Bless Water
- **COST:** 50
- **WT:** 0.01

### Scroll (Bless Weapon)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Bless Weapon
- **COST:** 100
- **WT:** 0.01

### Scroll (Calm Animals)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Calm Animals
- **COST:** 25
- **WT:** 0.01

### Scroll (Cause Fear/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Cause Fear
- **COST:** 25
- **WT:** 0.01

### Scroll (Charm Animal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Charm Animal
- **COST:** 25
- **WT:** 0.01

### Scroll (Command)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Command
- **COST:** 25
- **WT:** 0.01

### Scroll (Comprehend Languages/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Comprehend Languages
- **COST:** 25
- **WT:** 0.01
- **SPROP:** Understand spoken or written words for 10 minutes

### Scroll (Cure Light Wounds/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Cure Light Wounds
- **COST:** 25
- **WT:** 0.01
- **SPROP:** Cures 1d8+1 damage (PH P.215)

### Scroll (Curse Water)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Curse Water
- **COST:** 50
- **WT:** 0.01

### Scroll (Deathwatch)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Deathwatch
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Animals or Plants)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Animals or Plants
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Chaos)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Chaos
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Evil)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Evil
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Good)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Good
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Law)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Law
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Snares and Pits)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Snares and Pits
- **COST:** 25
- **WT:** 0.01

### Scroll (Detect Undead/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Undead
- **COST:** 25
- **WT:** 0.01

### Scroll (Divine Favor)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Divine Favor
- **COST:** 25
- **WT:** 0.01

### Scroll (Doom)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Doom
- **COST:** 25
- **WT:** 0.01

### Scroll (Endure Elements/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Endure Elements
- **COST:** 25
- **WT:** 0.01
- **SPROP:** Suffer no harm from hot or cold environment (-50 to 140 degrees Fahrenheit) for 24 hours

### Scroll (Entangle)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Entangle
- **COST:** 25
- **WT:** 0.01

### Scroll (Entropic Shield)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Entropic Shield
- **COST:** 25
- **WT:** 0.01

### Scroll (Faerie Fire)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Faerie Fire
- **COST:** 25
- **WT:** 0.01

### Scroll (Goodberry)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Goodberry
- **COST:** 25
- **WT:** 0.01

### Scroll (Hide from Animals)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Hide from Animals
- **COST:** 25
- **WT:** 0.01

### Scroll (Hide from Undead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Hide from Undead
- **COST:** 25
- **WT:** 0.01

### Scroll (Inflict Light Wounds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Inflict Light Wounds
- **COST:** 25
- **WT:** 0.01

### Scroll (Jump/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Jump
- **COST:** 25
- **WT:** 0.01

### Scroll (Longstrider)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Longstrider
- **COST:** 25
- **WT:** 0.01

### Scroll (Magic Fang)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Magic Fang
- **COST:** 25
- **WT:** 0.01

### Scroll (Magic Stone)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Magic Stone
- **COST:** 25
- **WT:** 0.01

### Scroll (Magic Weapon/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Magic Weapon
- **COST:** 25
- **WT:** 0.01

### Scroll (Obscuring Mist/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Obscuring Mist
- **COST:** 25
- **WT:** 0.01

### Scroll (Pass Without Trace)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Pass Without Trace
- **COST:** 25
- **WT:** 0.01

### Scroll (Produce Flame)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Produce Flame
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Chaos/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Chaos
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Evil/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Evil
- **EQMOD:** SPL_CHRG|SPELLNAME[Protection from Evil]SPELLLEVEL[1]CASTERLEVEL[1]
- **SPROP:** Protects against physical touch and charm, and increases AC/Saves against, evil or summoned creatures
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Good/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Good
- **COST:** 25
- **WT:** 0.01

### Scroll (Protection from Law/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Protection from Law
- **COST:** 25
- **WT:** 0.01

### Scroll (Remove Fear/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Remove Fear
- **COST:** 25
- **WT:** 0.01

### Scroll (Sanctuary)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Sanctuary
- **COST:** 25
- **WT:** 0.01

### Scroll (Shield of Faith)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Shield of Faith
- **COST:** 25
- **WT:** 0.01
- **SPROP:** +2 deflection bonus to AC for 1 minute

### Scroll (Shillelagh)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Shillelagh
- **COST:** 25
- **WT:** 0.01

### Scroll (Speak with Animals/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Speak with Animals
- **COST:** 25
- **WT:** 0.01

### Scroll (Summon Monster I/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Summon Monster I
- **COST:** 25
- **WT:** 0.01

### Scroll (Summon Nature's Ally I)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Summon Nature's Ally I
- **COST:** 25
- **WT:** 0.01

### Scroll (Animal Messenger/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Animal Messenger
- **COST:** 150
- **WT:** 0.01

### Scroll (Animal Trance/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Animal Trance
- **COST:** 150
- **WT:** 0.01

### Scroll (Augury)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Augury
- **COST:** 175
- **WT:** 0.01

### Scroll (Barkskin)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Barkskin
- **COST:** 150
- **WT:** 0.01

### Scroll (Bear's Endurance/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Bear's Endurance
- **COST:** 150
- **WT:** 0.01

### Scroll (Bull's Strength/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Bull's Strength
- **COST:** 150
- **WT:** 0.01
- **SPROP:** +4 Strength for 3 minutes

### Scroll (Calm Emotions/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Calm Emotions
- **COST:** 150
- **WT:** 0.01

### Scroll (Cat's Grace/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Cat's Grace
- **COST:** 150
- **WT:** 0.01

### Scroll (Chill Metal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Chill Metal
- **COST:** 150
- **WT:** 0.01

### Scroll (Consecrate)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Consecrate
- **COST:** 200
- **WT:** 0.01

### Scroll (Cure Moderate Wounds/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Cure Moderate Wounds
- **SPROP:** Cures 2d8 +3 damage (PH P.216)
- **COST:** 150
- **WT:** 0.01
- **SPROP:** Cures 2d8 +2 damage (PH P.216)

### Scroll (Darkness/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Darkness
- **COST:** 150
- **WT:** 0.01

### Scroll (Death Knell)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Death Knell
- **COST:** 150
- **WT:** 0.01

### Scroll (Delay Poison/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Delay Poison
- **COST:** 150
- **WT:** 0.01
- **SPROP:** You become immune to poison for 2 hours (PH P.217)

### Scroll (Desecrate)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Desecrate
- **COST:** 200
- **WT:** 0.01

### Scroll (Eagle's Splendor/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Eagle's Splendor
- **COST:** 150
- **WT:** 0.01

### Scroll (Enthrall/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Enthrall
- **COST:** 150
- **WT:** 0.01

### Scroll (Find Traps)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Find Traps
- **COST:** 150
- **WT:** 0.01

### Scroll (Fire Trap/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Fire Trap
- **COST:** 175
- **WT:** 0.01

### Scroll (Flame Blade)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Flame Blade
- **COST:** 150
- **WT:** 0.01

### Scroll (Flaming Sphere/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Flaming Sphere
- **COST:** 150
- **WT:** 0.01

### Scroll (Fog Cloud/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Fog Cloud
- **COST:** 150
- **WT:** 0.01

### Scroll (Gentle Repose/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Gentle Repose
- **COST:** 150
- **WT:** 0.01

### Scroll (Gust of Wind/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Gust of Wind
- **COST:** 150
- **WT:** 0.01

### Scroll (Heat Metal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Heat Metal
- **COST:** 150
- **WT:** 0.01

### Scroll (Hold Animal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Hold Animal
- **COST:** 150
- **WT:** 0.01

### Scroll (Hold Person/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Hold Person
- **COST:** 150
- **WT:** 0.01

### Scroll (Inflict Moderate Wounds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Inflict Moderate Wounds
- **COST:** 150
- **WT:** 0.01

### Scroll (Make Whole)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Make Whole
- **COST:** 150
- **WT:** 0.01

### Scroll (Owl's Wisdom/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Owl's Wisdom
- **COST:** 150
- **WT:** 0.01

### Scroll (Reduce Animal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Reduce Animal
- **COST:** 150
- **WT:** 0.01

### Scroll (Remove Paralysis)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Remove Paralysis
- **COST:** 150
- **WT:** 0.01

### Scroll (Resist Energy/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Resist Energy
- **COST:** 150
- **WT:** 0.01

### Scroll (Restoration/Lesser)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Restoration (Lesser)
- **COST:** 150
- **WT:** 0.01

### Scroll (Shatter/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Shatter
- **COST:** 150
- **WT:** 0.01

### Scroll (Shield Other)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Shield Other
- **COST:** 150
- **WT:** 0.01

### Scroll (Silence/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Silence
- **COST:** 150
- **WT:** 0.01

### Scroll (Snare/Lvl 2)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Snare
- **COST:** 150
- **WT:** 0.01

### Scroll (Soften Earth and Stone)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Soften Earth and Stone
- **COST:** 150
- **WT:** 0.01

### Scroll (Sound Burst/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Sound Burst
- **COST:** 150
- **WT:** 0.01

### Scroll (Speak with Plants/Divine/Lvl 2)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Speak with Plants
- **COST:** 150
- **WT:** 0.01

### Scroll (Spider Climb/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Spider Climb
- **COST:** 150
- **WT:** 0.01

### Scroll (Spiritual Weapon)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Spiritual Weapon
- **COST:** 150
- **WT:** 0.01

### Scroll (Status)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Status
- **COST:** 150
- **WT:** 0.01

### Scroll (Summon Monster II/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Summon Monster II
- **COST:** 150
- **WT:** 0.01

### Scroll (Summon Nature's Ally II)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Summon Nature's Ally II
- **COST:** 150
- **WT:** 0.01

### Scroll (Summon Swarm/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Summon Swarm
- **COST:** 150
- **WT:** 0.01

### Scroll (Tree Shape)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Tree Shape
- **COST:** 150
- **WT:** 0.01

### Scroll (Undetectable Alignment/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Undetectable Alignment
- **COST:** 150
- **WT:** 0.01

### Scroll (Warp Wood)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Warp Wood
- **COST:** 150
- **WT:** 0.01

### Scroll (Wood Shape)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Wood Shape
- **COST:** 150
- **WT:** 0.01

### Scroll (Zone of Truth)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Zone of Truth
- **COST:** 150
- **WT:** 0.01

### Scroll (Animate Dead/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Animate Dead
- **COST:** 625
- **WT:** 0.01

### Scroll (Bestow Curse/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Bestow Curse
- **COST:** 375
- **WT:** 0.01

### Scroll (Blindness/Deafness/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Blindness/Deafness
- **COST:** 375
- **WT:** 0.01

### Scroll (Call Lightning)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Call Lightning
- **COST:** 375
- **WT:** 0.01

### Scroll (Contagion/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Contagion
- **COST:** 375
- **WT:** 0.01

### Scroll (Continual Flame/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Continual Flame
- **COST:** 425
- **WT:** 0.01

### Scroll (Create Food and Water)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Create Food and Water
- **COST:** 375
- **WT:** 0.01

### Scroll (Cure Serious Wounds/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Cure Serious Wounds
- **COST:** 375
- **WT:** 0.01
- **SPROP:** Cures 3d8+5 damage (PH P.216)

### Scroll (Darkvision/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Darkvision
- **COST:** 375
- **WT:** 0.01
- **SPROP:** You gain 60' darkvision for 1 hour (PH P.216)

### Scroll (Daylight/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Daylight
- **COST:** 375
- **WT:** 0.01

### Scroll (Deeper Darkness)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Deeper Darkness
- **COST:** 375
- **WT:** 0.01

### Scroll (Diminish Plants)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Diminish Plants
- **COST:** 375
- **WT:** 0.01

### Scroll (Dispel Magic/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Dispel Magic
- **COST:** 375
- **WT:** 0.01

### Scroll (Dominate Animal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Dominate Animal
- **COST:** 375
- **WT:** 0.01

### Scroll (Glyph of Warding)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Glyph of Warding
- **COST:** 575
- **WT:** 0.01

### Scroll (Heal Mount)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Heal Mount
- **COST:** 375
- **WT:** 0.01

### Scroll (Helping Hand)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Helping Hand
- **COST:** 375
- **WT:** 0.01

### Scroll (Inflict Serious Wounds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Inflict Serious Wounds
- **COST:** 375
- **WT:** 0.01

### Scroll (Invisibility Purge)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Invisibility Purge
- **COST:** 375
- **WT:** 0.01

### Scroll (Locate Object/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Locate Object
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Chaos/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Chaos
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Evil/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Evil
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Good/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Good
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Circle against Law/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Circle against Law
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Fang/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Fang (Greater)
- **COST:** 375
- **WT:** 0.01

### Scroll (Magic Vestment)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Magic Vestment
- **COST:** 375
- **WT:** 0.01

### Scroll (Meld into Stone)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Meld into Stone
- **COST:** 375
- **WT:** 0.01

### Scroll (Neutralize Poison/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Neutralize Poison
- **SPROP:** Neutralize any existing poison and prevent any poison from affecting the drinker for 50 minutes (PH 257)
- **COST:** 375
- **WT:** 0.01

### Scroll (Obscure Object/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Obscure Object
- **COST:** 375
- **WT:** 0.01

### Scroll (Plant Growth)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Plant Growth
- **COST:** 375
- **WT:** 0.01

### Scroll (Prayer)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Prayer
- **COST:** 375
- **WT:** 0.01

### Scroll (Protection from Energy/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Protection from Energy
- **COST:** 375
- **WT:** 0.01

### Scroll (Quench)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Quench
- **COST:** 375
- **WT:** 0.01

### Scroll (Remove Blindness/Deafness)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Remove Blindness/Deafness
- **COST:** 375
- **WT:** 0.01

### Scroll (Remove Curse/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Remove Curse
- **COST:** 375
- **WT:** 0.01
- **SPROP:** Remove curse instantaneously removes all curses on an object or a creature

### Scroll (Remove Disease)

- **SPROP:** Cure all diseases from one target, also kills parasites including green slime. Does not prevent reinfection
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Remove Disease
- **COST:** 375
- **WT:** 0.01

### Scroll (Searing Light)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Searing Light
- **COST:** 375
- **WT:** 0.01

### Scroll (Sleet Storm/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Sleet Storm
- **COST:** 375
- **WT:** 0.01

### Scroll (Snare/Lvl 3)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Snare
- **COST:** 375
- **WT:** 0.01

### Scroll (Speak with Dead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Speak with Dead
- **COST:** 375
- **WT:** 0.01

### Scroll (Speak with Plants/Divine/Lvl 3)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Speak with Plants
- **COST:** 375
- **WT:** 0.01

### Scroll (Spike Growth)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Spike Growth
- **COST:** 375
- **WT:** 0.01

### Scroll (Stone Shape/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Stone Shape
- **COST:** 375
- **WT:** 0.01

### Scroll (Summon Monster III/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Summon Monster III
- **COST:** 375
- **WT:** 0.01

### Scroll (Summon Nature's Ally III)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Summon Nature's Ally III
- **COST:** 375
- **WT:** 0.01

### Scroll (Water Breathing/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Water Breathing
- **COST:** 375
- **WT:** 0.01
- **SPROP:** You can breathe underwater for 6 hours (PH P300).

### Scroll (Water Walk)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Water Walk
- **COST:** 375
- **WT:** 0.01

### Scroll (Wind Wall/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Wind Wall
- **COST:** 375
- **WT:** 0.01

### Scroll (Air Walk)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Air Walk
- **COST:** 700
- **WT:** 0.01

### Scroll (Antiplant Shell)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Antiplant Shell
- **COST:** 700
- **WT:** 0.01

### Scroll (Blight/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Blight
- **COST:** 700
- **WT:** 0.01

### Scroll (Break Enchantment/Divine/Lvl 4)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Break Enchantment
- **COST:** 700
- **WT:** 0.01

### Scroll (Command Plants)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Command Plants
- **COST:** 700
- **WT:** 0.01

### Scroll (Control Water/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Control Water
- **COST:** 700
- **WT:** 0.01

### Scroll (Cure Critical Wounds/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Cure Critical Wounds
- **SPROP:** Cures 4d8+7 damage (PH P.215)
- **COST:** 700
- **WT:** 0.01

### Scroll (Death Ward)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Death Ward
- **COST:** 700
- **WT:** 0.01
- **SPROP:** Target is immune to all death spells/effects and energy drain and any negative energy for 7 minutes (PH 217)

### Scroll (Dimensional Anchor/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Dimensional Anchor
- **COST:** 700
- **WT:** 0.01

### Scroll (Discern Lies)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Discern Lies
- **COST:** 700
- **WT:** 0.01

### Scroll (Dismissal/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Dismissal
- **COST:** 700
- **WT:** 0.01
- **SPROP:** Force an extraplanar creature back to its proper plane (Will save negates)

### Scroll (Divination)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Divination
- **COST:** 725
- **WT:** 0.01

### Scroll (Divine Power)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Divine Power
- **COST:** 700
- **WT:** 0.01

### Scroll (Freedom of Movement/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Freedom of Movement
- **COST:** 700
- **WT:** 0.01

### Scroll (Giant Vermin)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Giant Vermin
- **COST:** 700
- **WT:** 0.01

### Scroll (Holy Sword)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Holy Sword
- **COST:** 700
- **WT:** 0.01

### Scroll (Imbue with Spell Ability)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Imbue with Spell Ability
- **COST:** 700
- **WT:** 0.01

### Scroll (Inflict Critical Wounds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Inflict Critical Wounds
- **COST:** 700
- **WT:** 0.01

### Scroll (Magic Weapon/Greater/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Magic Weapon (Greater)
- **COST:** 700
- **WT:** 0.01

### Scroll (Nondetection/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Nondetection
- **SPROP:** Difficult to detect by divination spells for 5 hours (PH P.245)
- **COST:** 750
- **WT:** 0.01

### Scroll (Planar Ally/Lesser)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Planar Ally (Lesser)
- **COST:** 1200
- **WT:** 0.01

### Scroll (Poison)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Poison
- **COST:** 700
- **WT:** 0.01

### Scroll (Reincarnate)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Reincarnate
- **COST:** 700
- **WT:** 0.01

### Scroll (Repel Vermin/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Repel Vermin
- **COST:** 700
- **WT:** 0.01

### Scroll (Restoration)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Restoration
- **COST:** 800
- **WT:** 0.01

### Scroll (Rusting Grasp)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Rusting Grasp
- **COST:** 700
- **WT:** 0.01

### Scroll (Sending/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Sending
- **COST:** 700
- **WT:** 0.01

### Scroll (Spell Immunity)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Spell Immunity
- **COST:** 700
- **WT:** 0.01

### Scroll (Spike Stones)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Spike Stones
- **COST:** 700
- **WT:** 0.01

### Scroll (Summon Monster IV/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Summon Monster IV
- **COST:** 700
- **WT:** 0.01

### Scroll (Summon Nature's Ally IV)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Summon Nature's Ally IV
- **COST:** 700
- **WT:** 0.01

### Scroll (Tongues/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Tongues
- **COST:** 700
- **WT:** 0.01

### Scroll (Tree Stride)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Tree Stride
- **COST:** 700
- **WT:** 0.01

### Scroll (Animal Growth/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Animal Growth
- **COST:** 1125
- **WT:** 0.01

### Scroll (Atonement)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Atonement
- **COST:** 3625
- **WT:** 0.01

### Scroll (Awaken)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Awaken
- **COST:** 2375
- **WT:** 0.01

### Scroll (Baleful Polymorph/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Baleful Polymorph
- **COST:** 1125
- **WT:** 0.01

### Scroll (Break Enchantment/Divine/Lvl 5)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Break Enchantment
- **COST:** 1125
- **WT:** 0.01

### Scroll (Call Lightning Storm)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Call Lightning Storm
- **COST:** 1125
- **WT:** 0.01

### Scroll (Command/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Command (Greater)
- **COST:** 1125
- **WT:** 0.01

### Scroll (Commune)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Commune
- **COST:** 1625
- **WT:** 0.01

### Scroll (Commune with Nature)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Commune with Nature
- **COST:** 1125
- **WT:** 0.01

### Scroll (Control Winds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Control Winds
- **COST:** 1125
- **WT:** 0.01

### Scroll (Cure Light Wounds/Mass/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Cure Light Wounds (Mass)
- **SPROP:** Cures 1d8+9 damage (PH P.215)
- **COST:** 1125
- **WT:** 0.01

### Scroll (Dispel Chaos)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dispel Chaos
- **COST:** 1125
- **WT:** 0.01

### Scroll (Dispel Evil)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dispel Evil
- **COST:** 1125
- **WT:** 0.01

### Scroll (Dispel Good)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dispel Good
- **COST:** 1125
- **WT:** 0.01

### Scroll (Dispel Law)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Dispel Law
- **COST:** 1125
- **WT:** 0.01

### Scroll (Disrupting Weapon)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Disrupting Weapon
- **COST:** 1125
- **WT:** 0.01

### Scroll (Flame Strike)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Flame Strike
- **COST:** 1125
- **WT:** 0.01

### Scroll (Hallow)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Hallow
- **COST:** 6125
- **WT:** 0.01

### Scroll (Ice Storm/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Ice Storm
- **COST:** 1125
- **WT:** 0.01

### Scroll (Inflict Light Wounds/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Inflict Light Wounds (Mass)
- **COST:** 1125
- **WT:** 0.01

### Scroll (Insect Plague)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Insect Plague
- **COST:** 1125
- **WT:** 0.01

### Scroll (Mark of Justice)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Mark of Justice
- **COST:** 1125
- **WT:** 0.01

### Scroll (Plane Shift/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Plane Shift
- **COST:** 1125
- **WT:** 0.01

### Scroll (Raise Dead)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Raise Dead
- **COST:** 6125
- **WT:** 0.01

### Scroll (Righteous Might)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Righteous Might
- **COST:** 1125
- **WT:** 0.01

### Scroll (Scrying/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Scrying
- **COST:** 1125
- **WT:** 0.01

### Scroll (Slay Living)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Slay Living
- **COST:** 1125
- **WT:** 0.01

### Scroll (Spell Resistance)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Spell Resistance
- **COST:** 1125
- **WT:** 0.01

### Scroll (Stoneskin/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Stoneskin
- **COST:** 1375
- **WT:** 0.01

### Scroll (Summon Monster V/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Summon Monster V
- **COST:** 1125
- **WT:** 0.01

### Scroll (Summon Nature's Ally V)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Summon Nature's Ally V
- **COST:** 1125
- **WT:** 0.01

### Scroll (Symbol of Pain/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Symbol of Pain
- **COST:** 2125
- **WT:** 0.01

### Scroll (Symbol of Sleep/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Symbol of Sleep
- **COST:** 2125
- **WT:** 0.01

### Scroll (Transmute Mud to Rock/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Transmute Mud to Rock
- **COST:** 1125
- **WT:** 0.01

### Scroll (Transmute Rock to Mud/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Transmute Rock to Mud
- **COST:** 1125
- **WT:** 0.01

### Scroll (True Seeing/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|True Seeing
- **COST:** 1375
- **WT:** 0.01

### Scroll (Unhallow)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Unhallow
- **COST:** 6125
- **WT:** 0.01

### Scroll (Wall of Fire/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Wall of Fire
- **COST:** 1125
- **WT:** 0.01

### Scroll (Wall of Stone/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Wall of Stone
- **COST:** 1125
- **WT:** 0.01

### Scroll (Wall of Thorns)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Wall of Thorns
- **COST:** 1125
- **WT:** 0.01

### Scroll (Animate Objects/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Animate Objects
- **COST:** 1650
- **WT:** 0.01

### Scroll (Antilife Shell)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Antilife Shell
- **COST:** 1650
- **WT:** 0.01

### Scroll (Banishment/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Banishment
- **COST:** 1650
- **WT:** 0.01

### Scroll (Bear's Endurance/Mass/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Bear's Endurance (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Blade Barrier)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Blade Barrier
- **COST:** 1650
- **WT:** 0.01

### Scroll (Bull's Strength/Mass/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Bull's Strength (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Cat's Grace/Mass/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Cat's Grace (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Create Undead/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Create Undead
- **COST:** 1650
- **WT:** 0.01

### Scroll (Cure Moderate Wounds/Mass/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Cure Moderate Wounds (Mass)
- **SPROP:** Cures 2d8 +11 damage (PH P.216)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Dispel Magic/Greater/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Dispel Magic (Greater)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Eagle's Splendor/Mass/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Eagle's Splendor (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Find the Path/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Find the Path
- **COST:** 1650
- **WT:** 0.01

### Scroll (Fire Seeds)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Fire Seeds
- **COST:** 1650
- **WT:** 0.01

### Scroll (Forbiddance)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Forbiddance
- **COST:** 4650
- **WT:** 0.01

### Scroll (Geas/Quest/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Geas/Quest
- **COST:** 1650
- **WT:** 0.01

### Scroll (Glyph of Warding/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Glyph of Warding (Greater)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Harm)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Harm
- **COST:** 1650
- **WT:** 0.01

### Scroll (Heal)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Heal
- **COST:** 1650
- **WT:** 0.01

### Scroll (Heroes' Feast/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Heroes' Feast
- **COST:** 1650
- **WT:** 0.01

### Scroll (Inflict Moderate Wounds/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Inflict Moderate Wounds (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Ironwood)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Ironwood
- **COST:** 1650
- **WT:** 0.01

### Scroll (Liveoak)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Liveoak
- **COST:** 1650
- **WT:** 0.01

### Scroll (Move Earth/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Move Earth
- **COST:** 1650
- **WT:** 0.01

### Scroll (Owl's Wisdom/Mass/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Owl's Wisdom (Mass)
- **COST:** 1650
- **WT:** 0.01

### Scroll (Planar Ally)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Planar Ally
- **COST:** 2400
- **WT:** 0.01

### Scroll (Repel Wood)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Repel Wood
- **COST:** 1650
- **WT:** 0.01

### Scroll (Spellstaff)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Spellstaff
- **COST:** 1650
- **WT:** 0.01

### Scroll (Stone Tell)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Stone Tell
- **COST:** 1650
- **WT:** 0.01

### Scroll (Summon Monster VI/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Summon Monster VI
- **COST:** 1650
- **WT:** 0.01

### Scroll (Summon Nature's Ally VI)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Summon Nature's Ally VI
- **COST:** 1650
- **WT:** 0.01

### Scroll (Symbol of Fear/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Symbol of Fear
- **COST:** 2650
- **WT:** 0.01

### Scroll (Symbol of Persuasion/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Symbol of Persuasion
- **COST:** 6650
- **WT:** 0.01

### Scroll (Transport via Plants)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Transport via Plants
- **COST:** 1650
- **WT:** 0.01

### Scroll (Undeath to Death/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Undeath to Death
- **COST:** 2150
- **WT:** 0.01

### Scroll (Wind Walk)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Wind Walk
- **COST:** 1650
- **WT:** 0.01

### Scroll (Word of Recall)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Word of Recall
- **COST:** 1650
- **WT:** 0.01

### Scroll (Animate Plants)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Animate Plants
- **COST:** 2275
- **WT:** 0.01

### Scroll (Blasphemy)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Blasphemy
- **COST:** 2275
- **WT:** 0.01

### Scroll (Changestaff)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Changestaff
- **COST:** 2275
- **WT:** 0.01

### Scroll (Control Weather/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Control Weather
- **COST:** 2275
- **WT:** 0.01

### Scroll (Creeping Doom)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Creeping Doom
- **COST:** 2275
- **WT:** 0.01

### Scroll (Cure Serious Wounds/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Cure Serious Wounds (Mass)
- **SPROP:** Cures 3d8+13 damage (PH P.216)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Destruction)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Destruction
- **COST:** 2275
- **WT:** 0.01

### Scroll (Dictum)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Dictum
- **COST:** 2275
- **WT:** 0.01

### Scroll (Ethereal Jaunt/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Ethereal Jaunt
- **COST:** 2275
- **WT:** 0.01

### Scroll (Holy Word)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Holy Word
- **COST:** 2275
- **WT:** 0.01

### Scroll (Inflict Serious Wounds/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Inflict Serious Wounds (Mass)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Refuge/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Refuge
- **COST:** 3775
- **WT:** 0.01

### Scroll (Regenerate/Lvl 7)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Regenerate
- **COST:** 2275
- **WT:** 0.01

### Scroll (Repulsion/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Repulsion
- **COST:** 2275
- **WT:** 0.01

### Scroll (Restoration/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Restoration (Greater)
- **COST:** 4775
- **WT:** 0.01

### Scroll (Resurrection)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Resurrection
- **COST:** 12275
- **WT:** 0.01

### Scroll (Scrying/Greater/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Scrying (Greater)
- **COST:** 2275
- **WT:** 0.01

### Scroll (Summon Monster VII/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Summon Monster VII
- **COST:** 2275
- **WT:** 0.01

### Scroll (Summon Nature's Ally VII)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Summon Nature's Ally VII
- **COST:** 2275
- **WT:** 0.01

### Scroll (Sunbeam)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Sunbeam
- **COST:** 2275
- **WT:** 0.01

### Scroll (Symbol of Stunning/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Symbol of Stunning
- **COST:** 7275
- **WT:** 0.01

### Scroll (Symbol of Weakness/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Symbol of Weakness
- **COST:** 7275
- **WT:** 0.01

### Scroll (Transmute Metal to Wood)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Transmute Metal to Wood
- **COST:** 2275
- **WT:** 0.01

### Scroll (Word of Chaos)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=13|Word of Chaos
- **COST:** 2275
- **WT:** 0.01

### Scroll (Animal Shapes)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Animal Shapes
- **COST:** 3000
- **WT:** 0.01

### Scroll (Antimagic Field/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Antimagic Field
- **COST:** 3000
- **WT:** 0.01

### Scroll (Cloak of Chaos)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Cloak of Chaos
- **COST:** 3000
- **WT:** 0.01

### Scroll (Control Plants)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Control Plants
- **COST:** 3000
- **WT:** 0.01

### Scroll (Create Greater Undead/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Create Greater Undead
- **COST:** 3600
- **WT:** 0.01

### Scroll (Cure Critical Wounds/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Cure Critical Wounds (Mass)
- **SPROP:** Cures 4d8+15 damage (PH P.215)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Dimensional Lock/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Dimensional Lock
- **COST:** 3000
- **WT:** 0.01

### Scroll (Discern Location/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Discern Location
- **COST:** 3000
- **WT:** 0.01

### Scroll (Earthquake)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Earthquake
- **COST:** 3000
- **WT:** 0.01

### Scroll (Finger of Death/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Finger of Death
- **COST:** 3000
- **WT:** 0.01

### Scroll (Fire Storm)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Fire Storm
- **COST:** 3000
- **WT:** 0.01

### Scroll (Holy Aura)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Holy Aura
- **COST:** 3000
- **WT:** 0.01

### Scroll (Inflict Critical Wounds/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Inflict Critical Wounds (Mass)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Planar Ally/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Planar Ally (Greater)
- **COST:** 5500
- **WT:** 0.01

### Scroll (Repel Metal or Stone)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Repel Metal or Stone
- **COST:** 3000
- **WT:** 0.01

### Scroll (Reverse Gravity/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Reverse Gravity
- **COST:** 3000
- **WT:** 0.01

### Scroll (Shield of Law)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Shield of Law
- **COST:** 3000
- **WT:** 0.01

### Scroll (Spell Immunity/Greater)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Spell Immunity (Greater)
- **COST:** 3000
- **WT:** 0.01

### Scroll (Summon Monster VIII/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Summon Monster VIII
- **COST:** 3000
- **WT:** 0.01

### Scroll (Summon Nature's Ally VIII)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Summon Nature's Ally VIII
- **COST:** 3000
- **WT:** 0.01

### Scroll (Sunburst/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Sunburst
- **COST:** 3000
- **WT:** 0.01

### Scroll (Symbol of Death/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Symbol of Death
- **COST:** 8000
- **WT:** 0.01

### Scroll (Symbol of Insanity/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Symbol of Insanity
- **COST:** 8000
- **WT:** 0.01

### Scroll (Unholy Aura)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Unholy Aura
- **COST:** 3000
- **WT:** 0.01

### Scroll (Whirlwind)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Whirlwind
- **COST:** 3000
- **WT:** 0.01

### Scroll (Antipathy/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Antipathy
- **COST:** 3825
- **WT:** 0.01

### Scroll (Astral Projection/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Astral Projection
- **COST:** 4870
- **WT:** 0.01

### Scroll (Elemental Swarm)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Elemental Swarm
- **COST:** 3825
- **WT:** 0.01

### Scroll (Energy Drain/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Energy Drain
- **COST:** 3825
- **WT:** 0.01

### Scroll (Etherealness/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Etherealness
- **COST:** 3825
- **WT:** 0.01

### Scroll (Foresight/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Foresight
- **COST:** 3825
- **WT:** 0.01

### Scroll (Gate/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Gate
- **COST:** 8825
- **WT:** 0.01

### Scroll (Heal/Mass)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Heal (Mass)
- **COST:** 3825
- **WT:** 0.01

### Scroll (Implosion)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Implosion
- **COST:** 3825
- **WT:** 0.01

### Scroll (Miracle)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Miracle
- **COST:** 28825
- **WT:** 0.01

### Scroll (Regenerate/Lvl 9)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Regenerate
- **COST:** 3825
- **WT:** 0.01

### Scroll (Shambler)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Shambler
- **COST:** 3825
- **WT:** 0.01

### Scroll (Shapechange/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Shapechange
- **COST:** 3825
- **WT:** 0.01

### Scroll (Soul Bind/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Soul Bind
- **COST:** 3825
- **WT:** 0.01

### Scroll (Storm of Vengeance)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Storm of Vengeance
- **COST:** 3825
- **WT:** 0.01

### Scroll (Summon Monster IX/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Summon Monster IX
- **COST:** 3825
- **WT:** 0.01

### Scroll (Summon Nature's Ally IX)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Summon Nature's Ally IX
- **COST:** 3825
- **WT:** 0.01

### Scroll (Sympathy/Divine)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|Sympathy
- **COST:** 5325
- **WT:** 0.01

### Scroll (True Resurrection)

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=17|True Resurrection
- **COST:** 28825
- **WT:** 0.01

### Staff (Abjuration)

- **COST:** 65000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Usually carved from the heartwood of an ancient oak or other large tree, this staff allows use of the following spells: . Shield (1 charge) . Resist energy (1 charge) . Dispel magic (1 charge) . Lesser globe of invulnerability (2 charges) . Dismissal (2 charges) . Repulsion (3 charges). Strong abjuration; CL 13th;

### Staff (Charming)

- **COST:** 16500
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Made of twisting wood ornately shaped and carved, this staff allows use of the following spells: . Charm person (1 charge) . Charm monster (2 charges) Moderate enchantment; CL 8th

### Staff (Conjuration)

- **COST:** 65000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This staff is usually made of ash or walnut and bears ornate carvings of many different kinds of creatures. It allows use of the following spells: . Unseen servant (1 charge) . Summon swarm (1 charge) . Stinking cloud (1 charge) . Minor creation (2 charges) . Cloudkill (2 charges) . Summon monster VI (3 charges) Strong conjuration; CL 13th

### Staff (Defense)

- **COST:** 58250
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** The staff of defense is a simple-looking staff that throbs with power when held defensively. It allows use of the following spells: . Shield (1 charge) . Shield of faith (1 charge) . Shield other (1 charge) . Shield of law (3 charges) Strong abjuration; CL 15th

### Staff (Divination)

- **COST:** 73500
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Made from a supple length of willow, often with a forked tip, this staff allows use of the following spells: . Detect secret doors (1 charge) . Locate object (1 charge) . Tongues (1 charge) . Locate creature (2 charges) . Prying eyes (2 charges) . True seeing (3 charges) Strong divination; CL 13th

### Staff (Earth and Stone)

- **COST:** 80500
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This staff is topped with a fist-sized emerald that gleams with smoldering power. It allows the use of the following spells: . Passwall (1 charge) . Move earth (1 charge) Moderate transmutation; CL 11th

### Staff (Enchantment)

- **COST:** 65000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Often made from applewood and topped with a clear crystal, this staff allows use of the following spells: . Sleep (1 charge) . Tasha's hideous laughter (1 charge) . Suggestion (1 charge) . Crushing despair (2 charges) . Mind fog (2 charges) . Suggestion, mass (3 charges) Strong enchantment; CL 13th

### Staff (Evocation)

- **COST:** 65000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Usually very smooth and carved from hickory, willow, or yew, this staff allows use of the following spells: . Magic missile (1 charge) . Shatter (1 charge) . Fireball (1 charge) . Ice storm (2 charges) . Wall of force (2 charges) . Chain lightning (3 charges) Strong evocation; CL 13th

### Staff (Fire)

- **COST:** 17750
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Crafted from bronzewood with brass bindings, this staff allows use of the following spells: . Burning hands (1 charge) . Fireball (1 charge) . Wall of fire (2 charges) Moderate evocation; CL 8th

### Staff (Frost)

- **COST:** 56250
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Tipped on either end with a glistening diamond, this rune-covered staff allows use of the following spells: . Ice storm (1 charge) . Wall of ice (1 charge) . Cone of cold (2 charge) Moderate evocation; CL 10th

### Staff (Healing)

- **COST:** 27750
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This white ash staff, with inlaid silver runes, allows use of the following spells: . Lesser restoration (1 charge) . Cure serious wounds (1 charge) . Remove blindness/deafness (2 charges) . Remove disease (3 charges) Moderate conjuration; CL 8th
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=8|Restoration (Lesser)
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=8|Cure Serious Wounds
- **SPELLS:** Magic Item|TIMES=2|CASTERLEVEL=8|Remove Blindness/Deafness
- **SPELLS:** Magic Item|TIMES=3|CASTERLEVEL=8|Remove Disease

### Staff (Illusion)

- **COST:** 65000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This staff is made from ebony or other dark wood and carved into an intricately twisted, fluted, or spiral shape. It allows use of the following spells: . Disguise self (1 charge) . Mirror image (1 charge) . Major image (1 charge) . Rainbow pattern (2 charges) . Persistent image (2 charges) . Mislead (3 charges) Strong illusion; CL 13th

### Staff (Illumination)

- **COST:** 48250
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This staff is usually sheathed in silver and decorated with sunbursts. It allows use of the following spells: . Dancing lights (1 charge) . Flare (1 charge) . Daylight (2 charges) . Sunburst (3 charges) Strong evocation; CL 15th

### Staff (Life)

- **COST:** 155750
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Made of thick oak shod in gold, this staff allows use of the following spells: . Heal (1 charge) . Raise dead (5 charges) Moderate conjuration; CL 11th

### Staff (Necromancy)

- **COST:** 65000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This staff is made from ebony or other dark wood and carved with the images of bones and skulls. It allows use of the following spells: . Cause fear (1 charge) . Ghoul touch (1 charge) . Halt undead (1 charge) . Enervation (2 charges) . Waves of fatigue (2 charges) . Circle of death (3 charges) Strong necromancy; CL 13th

### Staff (Passage)

- **COST:** 170500
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This potent item allows use of the following spells: . Dimension door (1 charge) . Passwall (1 charge) . Phase door (2 charges) . Greater teleport (2 charges) . Astral projection (2 charges) Strong varied; CL 17th

### Staff (Power)

- **PROFICIENCY:** WEAPON|Quarterstaff
- **ALTTYPE:** Weapon.Melee.Bludgeoning
- **COST:** 211000
- **WT:** 4
- **BASEITEM:** Staff
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **ALTCRITMULT:** x2
- **ALTCRITRANGE:** 1
- **DAMAGE:** 1d6
- **ALTDAMAGE:** 1d6
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** COMBAT|AC|2|TYPE=Luck
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** The staff of power is a very potent magic item, with offensive and defensive abilities. It is usually topped with a glistening gem, its shaft straight and smooth. It has the following powers: . Magic missile (1 charge) . Ray of enfeeblement (heightened to 5th level) (1 charge) . Continual flame (1 charge) . Levitate (1 charge) . Lightning bolt (heightened to 5th level) (1 charge) . Fireball (heightened to 5th level) (1 charge) . Cone of cold (2 charges) . Hold monster (2 charges) . Wall of force (in a 10-ft.-diameter hemisphere around the caster only) (2 charges) . Globe of invulnerability (2 charges) The wielder of a staff of power gains a +2 luck bonus to AC and saving throws. The staff is also a +2 quarterstaff, and its wielder may use it to smite opponents. If 1 charge is expended (as a free action), the staff causes double damage (*3 on a critical hit) for 1 round. A staff of power can be used for a retributive strike, requiring it to be broken by its wielder. (If this breaking of the staff is purposeful and declared by the wielder, it can be performed as a standard action that does not require the wielder to make a Strength check.) All charges currently in the staff are instantly released in a 30-foot radius. All within 2 squares of the broken staff take points of damage equal to 8 * the number of charges in the staff, those 3 or 4 squares away take 6 * the number of charges in damage, and those 5 or 6 squares distant take 4 * the number of charges in damage. All those affected can make DC 17 Reflex saves to reduce the damage by half. The character breaking the staff has a 50%% chance of traveling to another plane of existence, but if he does not, the explosive release of spell energy destroys him. Only certain items, including the staff of the magi (page 280) and the staff of power, are capable of being used for a retributive strike. After all charges are used up from the staff, it remains a +2 quarterstaff. (Once empty of charges, it cannot be used for a retributive strike.) Strong varied; CL 15th
- **BONUS:** SAVE|Fortitude,Reflex,Will|2|TYPE=Luck

### Staff (Size Alteration)

- **COST:** 29000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Stout and sturdy, this staff of dark wood allows use of the following spells: . Enlarge person (1 charge) . Reduce person (1 charge) . Shrink item (1 charge) . Enlarge person, mass (1 charge) . Reduce person, mass (1 charge) Faint conjuration; CL 8th

### Staff (Swarming Insects)

- **COST:** 24750
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Made of twisted dark wood with dark spots resembling crawling insects (which occasionally seem to move), this staff allows use of the following spells: . Summon swarm (1 charge) . Insect plague (3 charges) Moderate conjuration; CL 9th;

### Staff (Transmutation)

- **COST:** 65000
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** This staff is generally carved from or decorated with petrified wood and allows use of the following spells: . Expeditious retreat (1 charge) . Alter self (1 charge) . Blink (1 charge) . Polymorph (2 charges) . Baleful polymorph (2 charges) . Disintegrate (3 charges) Strong transmutation; CL 13th

### Staff (Woodlands)

- **PROFICIENCY:** WEAPON|Quarterstaff
- **ALTTYPE:** Weapon.Melee.Bludgeoning
- **COST:** 101250
- **WT:** 4
- **BASEITEM:** Staff
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **ALTCRITMULT:** x2
- **ALTCRITRANGE:** 1
- **DAMAGE:** 1d6
- **ALTDAMAGE:** 1d6
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** Appearing to have grown naturally into its shape, this oak, ash, or yew staff allows use of the following spells: . Charm animal (1 charge) . Speak with animals (1 charge) . Barkskin (2 charges) . Wall of thorns (3 charges) . Summon nature's ally VI (3 charges) . Animate plants (4 charges) The staff may be used as a weapon, functioning as a +2 quarterstaff. The staff of the woodlands also allows its wielder to pass without trace at will, with no charge cost. These two attributes continue to function after all the charges are expended. Moderate varied; CL 13th

### Wand (Acid Arrow)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Acid Arrow]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Bear's Endurance)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Bear's Endurance]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Bull's Strength)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Bull's Strength]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Burning Hands)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Burning Hands]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Burning Hands
- **SPROP:** 15' Cone of flame 1d4 damage, Reflex save for half (PH 207)

### Wand (Call Lightning/5th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Call Lightning]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Call Lightning/8th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Call Lightning]SPELLLEVEL[3]CASTERLEVEL[8]CHARGES[50]

### Wand (Cat's Grace)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Cat's Grace]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Chaos Hammer/8th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Chaos Hammer]SPELLLEVEL[4]CASTERLEVEL[8]CHARGES[50]

### Wand (Charm Animal)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Charm Animal]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]

### Wand (Charm Monster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Charm Monster]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Charm Person)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Charm Person]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]

### Wand (Charm Person/heightened to 3rd-level spell)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Charm Person]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Color Spray)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Color Spray]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Color Spray
- **SPROP:** Knocks unconscious, blinds, and/or stuns 1d6 weak creatures in a 15' cone. Will save (DC12) negates. 5HD or more - stunned for 1 round, 3-4HD are also blinded and stunned for 1d4 rounds first, 2HD or less are also unconscious/blinded/stunned for 2d4 rounds first (PH210)

### Wand (Contagion)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Contagion]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Cure Critical Wounds)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Cure Critical Wounds]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]
- **SPROP:** Cures 4d8+7 damage (PH P.215)

### Wand (Cure Light Wounds)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Cure Light Wounds]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPROP:** Cures 1d8+1 damage (PH P.215)

### Wand (Cure Moderate Wounds)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Cure Moderate Wounds]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Cure Moderate Wounds
- **SPROP:** Cures 2d8+3 damage to touched creature. Damages undead, they can attempt a will save for half damage.

### Wand (Cure Serious Wounds)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Cure Serious Wounds]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]
- **SPROP:** Cures 3d8+5 damage
- **SPROP:** Cures 3d8+5 damage (PH P.216)

### Wand (Darkness)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Darkness]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** 20' radius darkness for 30 minutes

### Wand (Daylight)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Daylight]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Delay Poison)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Delay Poison]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** Target becomes immune to poison for 2 hours (PH P.217)

### Wand (Detect Magic)

- **SPROP:** Detect magical auras. The amount of information revealed depends on how long you study a particular area or subject. (PH 219)
- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Detect Magic]SPELLLEVEL[0]CASTERLEVEL[1]CHARGES[50]

### Wand (Detect Secret Doors)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Detect Secret Doors]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]

### Wand (Dimensional Anchor)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Dimensional Anchor]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Dispel Magic)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Dispel Magic]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Dispel Magic/10th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Dispel Magic]SPELLLEVEL[3]CASTERLEVEL[10]CHARGES[50]

### Wand (Eagle's Splendor)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Eagle's Splendor]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Enlarge Person)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Enlarge Person]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPROP:** Double height and multiply weight by 8. +2 Str, -2 Dex, -1 Attack & AC for 1 minute (PH P.226)

### Wand (False Life)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[False Life]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Fear)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Fear]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]
- **SPROP:** Cause panic in 30' cone for 4 rounds, or Will save (DC15) for just 1 round of shaken

### Wand (Fireball/5th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Fireball]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Fireball/6th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Fireball]SPELLLEVEL[3]CASTERLEVEL[6]CHARGES[50]

### Wand (Fireball/8th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Fireball]SPELLLEVEL[3]CASTERLEVEL[8]CHARGES[50]

### Wand (Fireball/10th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Fireball]SPELLLEVEL[3]CASTERLEVEL[10]CHARGES[50]

### Wand (Fox's Cunning)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Fox's Cunning]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** Gain +4 intelligence for 2 minutes. (PH P.233)

### Wand (Ghoul Touch)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Ghoul Touch]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** (PH P241) Touch to paralyze a single living humanoid for 1d6+2 rounds (Fortitude negates). Victim smells bad - sickening all but you within 10' (fort negates)

### Wand (Greater Invisibility)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Invisibility (Greater)]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]
- **SPROP:** Target becomes invisible, for 7 minutes, unlike normal invisibility, the spell does not end when the target attacks.

### Wand (Hold Person)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Hold Person]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** 1 humanoid within 130' is paralysed for 3 rounds. Will save (DC12) negates (can be made each round). (PH P241)

### Wand (Hold Monster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Hold Monster]SPELLLEVEL[5]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** 1 monster within 130' is paralysed for 5 rounds. Will save (DC12) negates (can be made each round). (PH P241)

### Wand (Hold Person/heightened to 4th-level spell)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Hold Person]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Hold Portal)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Hold Portal]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Hold Portal
- **SPROP:** Magically holds a door within 110' shut for 1 minute. (PH P.241)

### Wand (Holy Smite/8th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Holy Smite]SPELLLEVEL[4]CASTERLEVEL[8]CHARGES[50]

### Wand (Ice Storm)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Ice Storm]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Inflict Critical Wounds)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Inflict Critical Wounds]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Invisibility)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Invisibility]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** Invisible for 3 minutes or until you attack (PH P.245)

### Wand (Keen Edge)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Keen Edge]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Knock)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Knock]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Knock
- **SPROP:** Open stuck,barred, locked, held or arcane locked doors. It opens secret doors, as well as locked or trick opening boxes or chests, it also loosens welds, shackles or chains. Affects an opening of of up to 10sq. ft/level (30') within 130' (PH P.246)

### Wand (Levitate)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Levitate]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** for 3 minutes you, or an object within 30' (upto 300lb) can move up or down at 20' round as a move action. Combat is unstable, gaining a penalty of -1 on attack rolls each round, up to -5. PH P.248

### Wand (Light)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Light]SPELLLEVEL[0]CASTERLEVEL[1]CHARGES[50]
- **SPROP:** 20' radius light (+another 20' dim light) for 10 minutes

### Wand (Lightning Bolt/5th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Lightning Bolt]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]
- **SPROP:** 5d6 damage (reflex half) to all in 120' line

### Wand (Lightning Bolt/6th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Lightning Bolt]SPELLLEVEL[3]CASTERLEVEL[6]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=6|Lightning Bolt
- **SPROP:** 6d6 lightning bolt 120'
- **SPROP:** 6d6 damage (reflex half) to all in 120' line

### Wand (Lightning Bolt/8th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Lightning Bolt]SPELLLEVEL[3]CASTERLEVEL[8]CHARGES[50]
- **SPROP:** 8d6 damage (reflex half) to all in 120' line

### Wand (Lightning Bolt/10th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Lightning Bolt]SPELLLEVEL[3]CASTERLEVEL[10]CHARGES[50]
- **SPROP:** 10d6 damage (reflex half) to all in 120' line

### Wand (Mage Armor)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Mage Armor]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Mage Armor
- **SPROP:** Gives caster +4 Armor bonus for one hour.

### Wand (Magic Missile/1st level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Magic Missile]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Magic Missile
- **SPROP:** One missile travels up to 110' to strike a target for 1d4+1 damage, no save.

### Wand (Magic Missile/3rd level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Magic Missile]SPELLLEVEL[1]CASTERLEVEL[3]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Magic Missile
- **SPROP:** Two missiles travels up to 130' to strike a target for 2d4+2 damage, no save.

### Wand (Magic Missile/5th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Magic Missile]SPELLLEVEL[1]CASTERLEVEL[5]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=5|Magic Missile
- **SPROP:** Three missiles travels up to 150' to strike a target for 3d4+3 damage, no save.

### Wand (Magic Missile/7th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Magic Missile]SPELLLEVEL[1]CASTERLEVEL[7]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=7|Magic Missile
- **SPROP:** Four missiles travels up to 170' to strike a target for 4d4+4 damage, no save.

### Wand (Magic Missile/9th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Magic Missile]SPELLLEVEL[1]CASTERLEVEL[9]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=9|Magic Missile
- **SPROP:** Five missiles travels up to 190' to strike a target for 5d4+5 damage, no save.

### Wand (Major Image)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Major Image]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Mirror Image)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Mirror Image]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Neutralize Poison)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Neutralize Poison]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]
- **SPROP:** Neutralize any existing poison and prevent any poison from affecting the drinker for 70 minutes (PH 257)

### Wand (Order's Wrath/8th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Order's Wrath]SPELLLEVEL[4]CASTERLEVEL[8]CHARGES[50]

### Wand (Owl's Wisdom)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Owl's Wisdom]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Wand (Poison)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Poison]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Polymorph)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Polymorph]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Ray of Enfeeblement/heightened to 4th-level spell)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Ray of Enfeeblement]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Reduce Person)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Reduce Person]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Reduce Person
- **SPROP:** (PH P269)Humanoid target within 45' is halved in height/weight/width and weight is reduced to 1/8th. Size category is reduced by 1, the target gains +2 size bonus to dex, -2 Str and +1 bonus to attack and AC. Lasts 1 minute

### Wand (Restoration)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Restoration]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Searing Light/6th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Searing Light]SPELLLEVEL[3]CASTERLEVEL[6]CHARGES[50]

### Wand (Scorching Ray)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Scorching Ray
- **EQMOD:** SPL_CHRG|SPELLNAME[Scorching Ray]SPELLLEVEL[4]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** Ranged touch attack 35', deals 4d6 fire damage (PH 274)

### Wand (Shatter)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Shatter]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** Break brittle, nonmagical items in 5' radius, or 2d6 damage to crystalline creature. 35'range.

### Wand (Shocking Grasp)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Shocking Grasp]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Shocking Grasp
- **EQMOD:** SPL_CHRG|SPELLNAME|Shocking Grasp|SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPROP:** d6 Electricity touch attack, SR Yes, +3 to hit vs metal armor/metal target

### Wand (Silence)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Silence]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Silence
- **EQMOD:** SPL_CHRG|SPELLNAME|Silence|SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPROP:** 20' radius of silence, 520' range. 3 Minutes.

### Wand (Silent Image)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Silent Image]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]

### Wand (Sleep)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Sleep]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]

### Wand (Slow)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Slow]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]

### Wand (Stoneskin)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Stoneskin]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Suggestion)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Suggestion]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=5|Suggestion
- **SPROP:** Compels one living subject to follow stated course of action for 5 hours. DC:13, Range 45'

### Wand (Suggestion/heightened to 4th-level spell)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Suggestion]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]
- **SPROP:** Compels one living subject to follow stated course of action for 5 hours. DC:14, Range 35'

### Wand (Summon Monster I)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Summon Monster I]SPELLLEVEL[1]CASTERLEVEL[1]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Summon Monster I
- **SPROP:** Summons a creature to the location you specify within 25', that immediately does your bidding for 1 round then disappears. See list on PH P.287

### Wand (Summon Monster II)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Summon Monster II]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Summon Monster II
- **SPROP:** Summons creature(s) to the location you specify within 30' (within 30' of each other), that immediately do your bidding, creatures remains for 2 rounds then disappear. 1x2nd level or 1d3x1st. See list on PH P.287

### Wand (Summon Monster III)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Summon Monster III]SPELLLEVEL[3]CASTERLEVEL[5]CHARGES[50]
- **SPROP:** Summons creature(s) to the location you specify within 30' (within 30' of each other), that immediately do your bidding, creatures remains for 3 rounds then disappear. 1 3rd level, 1d3 x 2nd level or 1d4+1 x 1st. See list on PH P.287

### Wand (Summon Monster IV)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Summon Monster IV]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]
- **SPROP:** Summons creature(s) to the location you specify within 35' (within 30' of each other), that immediately do your bidding, creatures remains for 4 rounds then disappear. 1 4th lvl, 1d3 3rd lvl or 1d4+1 of 2nd or 1st lvl. See list on PH P.287

### Wand (Unholy Blight/8th level caster)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Summon Monster IV]SPELLLEVEL[4]CASTERLEVEL[8]CHARGES[50]

### Wand (Wall of Fire)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Wall of Fire]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Wall of Ice)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Wall of Ice]SPELLLEVEL[4]CASTERLEVEL[7]CHARGES[50]

### Wand (Web)

- **WT:** 0.0625
- **BASEITEM:** Wand
- **EQMOD:** SPL_CHRG|SPELLNAME[Web]SPELLLEVEL[2]CASTERLEVEL[3]CHARGES[50]

### Amulet of Health +2

- **COST:** 4000
- **WT:** 0
- **BONUS:** STAT|CON|2|TYPE=Enhancement
- **SPROP:** This amulet is a golden disk on a chain. It usually bears the image of a lion or other powerful animal. The amulet grants the wearer an enhancement bonus to Constitution of +2. Moderate transmutation; CL 8th
- **SORTKEY:** Amulet of Health +02

### Amulet of Health +4

- **COST:** 16000
- **WT:** 0
- **BONUS:** STAT|CON|4|TYPE=Enhancement
- **SPROP:** This amulet is a golden disk on a chain. It usually bears the image of a lion or other powerful animal. The amulet grants the wearer an enhancement bonus to Constitution of +4. Moderate transmutation; CL 8th
- **SORTKEY:** Amulet of Health +04

### Amulet of Health +6

- **COST:** 36000
- **WT:** 0
- **BONUS:** STAT|CON|6|TYPE=Enhancement
- **SPROP:** This amulet is a golden disk on a chain. It usually bears the image of a lion or other powerful animal. The amulet grants the wearer an enhancement bonus to Constitution of +6. Moderate transmutation; CL 8th
- **SORTKEY:** Amulet of Health +06

### Amulet of Mighty Fists +1

- **COST:** 6000
- **WT:** 0
- **BONUS:** WEAPONPROF=Unarmed Strike|TOHIT,DAMAGE|1|TYPE=Enhancement
- **BONUS:** WEAPONPROF=TYPE.Natural|TOHIT,DAMAGE|1|TYPE=Enhancement
- **SPROP:** This amulet grants an enhancement bonus of +1on attack and damage rolls with unarmed attacks and natural weapons. Faint evocation; CL 5th
- **SORTKEY:** Amulet of Mighty Fists +01

### Amulet of Mighty Fists +2

- **COST:** 24000
- **WT:** 0
- **BONUS:** WEAPONPROF=Unarmed Strike|TOHIT,DAMAGE|2|TYPE=Enhancement
- **BONUS:** WEAPONPROF=TYPE.Natural|TOHIT,DAMAGE|2|TYPE=Enhancement
- **SPROP:** This amulet grants an enhancement bonus of +2 on attack and damage rolls with unarmed attacks and natural weapons. Faint evocation; CL 5th
- **SORTKEY:** Amulet of Mighty Fists +02

### Amulet of Mighty Fists +3

- **COST:** 54000
- **WT:** 0
- **BONUS:** WEAPONPROF=Unarmed Strike|TOHIT,DAMAGE|3|TYPE=Enhancement
- **BONUS:** WEAPONPROF=TYPE.Natural|TOHIT,DAMAGE|3|TYPE=Enhancement
- **SPROP:** This amulet grants an enhancement bonus of +3 on attack and damage rolls with unarmed attacks and natural weapons. Faint evocation; CL 5th
- **SORTKEY:** Amulet of Mighty Fists +03

### Amulet of Mighty Fists +4

- **COST:** 96000
- **WT:** 0
- **BONUS:** WEAPONPROF=Unarmed Strike|TOHIT,DAMAGE|4|TYPE=Enhancement
- **BONUS:** WEAPONPROF=TYPE.Natural|TOHIT,DAMAGE|4|TYPE=Enhancement
- **SPROP:** This amulet grants an enhancement bonus of +4 on attack and damage rolls with unarmed attacks and natural weapons. Faint evocation; CL 5th
- **SORTKEY:** Amulet of Mighty Fists +04

### Amulet of Mighty Fists +5

- **COST:** 150000
- **WT:** 0
- **BONUS:** WEAPONPROF=Unarmed Strike|TOHIT,DAMAGE|5|TYPE=Enhancement
- **BONUS:** WEAPONPROF=TYPE.Natural|TOHIT,DAMAGE|5|TYPE=Enhancement
- **SPROP:** This amulet grants an enhancement bonus of +5 on attack and damage rolls with unarmed attacks and natural weapons. Faint evocation; CL 5th
- **SORTKEY:** Amulet of Mighty Fists +05

### Amulet of Natural Armor +1

- **COST:** 2000
- **WT:** 0
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmorEnhancement
- **SPROP:** This amulet, usually crafted from bone or beast scales, toughens the wearer's body and flesh, giving him an enhancement bonus to his natural armor bonus of from +1. Faint transmutation; CL 5th
- **SORTKEY:** Amulet of Natural Armor +01

### Amulet of Natural Armor +2

- **COST:** 8000
- **WT:** 0
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmorEnhancement
- **SPROP:** This amulet, usually crafted from bone or beast scales, toughens the wearer's body and flesh, giving him an enhancement bonus to his natural armor bonus of from +2. Faint transmutation; CL 5th
- **SORTKEY:** Amulet of Natural Armor +02

### Amulet of Natural Armor +3

- **COST:** 18000
- **WT:** 0
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmorEnhancement
- **SPROP:** This amulet, usually crafted from bone or beast scales, toughens the wearer's body and flesh, giving him an enhancement bonus to his natural armor bonus of from +3. Faint transmutation; CL 5th
- **SORTKEY:** Amulet of Natural Armor +03

### Amulet of Natural Armor +4

- **COST:** 32000
- **WT:** 0
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmorEnhancement
- **SPROP:** This amulet, usually crafted from bone or beast scales, toughens the wearer's body and flesh, giving him an enhancement bonus to his natural armor bonus of from +4. Faint transmutation; CL 5th
- **SORTKEY:** Amulet of Natural Armor +04

### Amulet of Natural Armor +5

- **COST:** 50000
- **WT:** 0
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmorEnhancement
- **SPROP:** This amulet, usually crafted from bone or beast scales, toughens the wearer's body and flesh, giving him an enhancement bonus to his natural armor bonus of from +5. Faint transmutation; CL 5th
- **SORTKEY:** Amulet of Natural Armor +05

### Amulet of the Planes

- **COST:** 120000
- **WT:** 0
- **SPROP:** This device usually appears to be a black circular amulet, although any character looking closely at it sees a dark, moving swirl of color. The amulet allows its wearer to utilize plane shift. However, this is a difficult item to master. The user must make a DC 15 Intelligence check in order to get the amulet to take her to the plane (and the specific location on that plane) that she wants. If she fails, the amulet transports her and all those traveling with her to a random location on that plane (01-60 on d%%) or to a random plane (61-100). Strong conjuration; CL 15th

### Amulet of Proof against Detection and Location

- **COST:** 35000
- **WT:** 0
- **SPROP:** This silver amulet protects the wearer from scrying and magical location just as a nondetection spell does. If a divination spell is attempted against the wearer, the caster of the divination must succeed on a caster level check (1d20 + caster level) against a DC of 19 (as if the caster had cast nondetection on herself ). Moderate abjuration; CL 8th

### Apparatus of the Kwalish

- **COST:** 90000
- **WT:** 500
- **SPROP:** This item appears to be a large, sealed iron barrel, but it has a secret catch (Search DC 20 to locate) that opens a hatch in one end. Anyone who crawls inside finds ten (unlabeled) levers: The device has the following characteristics: hp 200; hardness 15; Spd 20 ft., swim 20 ft.; AC 20 (-1 size, +11 natural); Atk +12 melee (2d8, 2 pincers). Lever (1d10) Lever Function 1 Extend/retract legs and tail 2 Uncover/cover forward porthole 3 Uncover/cover side portholes 4 Extend/retract pincers and feelers 5 Snap pincers 6 Move forward/backward 7 Turn left/right 8 Open "eyes" with continual flame inside/close "eyes" 9 Rise/sink in water 10 Open/close hatch Operating a lever is a full-round action, and no lever may be operated more than once per round. However, since two Medium characters can fit inside, the apparatus can move and attack in the same round. The device can function in water up to 900 feet deep. It holds enough air for a crew of two to survive 1d4+1 hours (twice as long for a single occupant). When activated, the apparatus looks something like a giant lobster. Strong evocation and transmutation; CL 19th

### Bag of Holding (Type I)

- **CONTAINS:** *250
- **COST:** 2500
- **WT:** 15
- **SPROP:** This appears to be a common cloth sack about 2 feet by 4 feet in size. The bag of holding opens into a nondimensional space: Its inside is larger than its outside dimensions. Regardless of what is put into the bag, it weighs 15lbs and its contents can be up to 250lbs and 30 cubic feet. If the bag is overloaded, or if sharp objects pierce it (from inside or outside), the bag ruptures and is ruined. All contents are lost forever. If a bag of holding is turned inside out, its contents spill out, unharmed, but the bag must be put right before it can be used again. If living creatures are placed within the bag, they can survive for up to 10 minutes, after which time they suffocate. Retrieving a specific item from a bag of holding is a move action - unless the bag contains more than an ordinary backpack would hold, in which case retrieving a specific item is a full-round action. If a bag of holding is placed within a portable hole (DMG 264), a rift to the Astral Plane is torn in the space: Bag and hole alike are sucked into the void and forever lost. If a portable hole is placed within a bag of holding, it opens a gate to the Astral Plane: The hole, the bag, and any creatures within a 10-foot radius are drawn there, destroying the portable hole and bag of holding in the process. Moderate conjuration; CL 9th
- **SORTKEY:** Bag of Holding 1

### Bag of Holding (Type II)

- **CONTAINS:** *500
- **COST:** 5000
- **WT:** 25
- **SPROP:** This appears to be a common cloth sack about 2 feet by 4 feet in size. The bag of holding opens into a nondimensional space: Its inside is larger than its outside dimensions. Regardless of what is put into the bag, it weighs 25lbs and its contents can be up to 500lbs and 70 cubic feet. If the bag is overloaded, or if sharp objects pierce it (from inside or outside), the bag ruptures and is ruined. All contents are lost forever. If a bag of holding is turned inside out, its contents spill out, unharmed, but the bag must be put right before it can be used again. If living creatures are placed within the bag, they can survive for up to 10 minutes, after which time they suffocate. Retrieving a specific item from a bag of holding is a move action - unless the bag contains more than an ordinary backpack would hold, in which case retrieving a specific item is a full-round action. If a bag of holding is placed within a portable hole (DMG 264), a rift to the Astral Plane is torn in the space: Bag and hole alike are sucked into the void and forever lost. If a portable hole is placed within a bag of holding, it opens a gate to the Astral Plane: The hole, the bag, and any creatures within a 10-foot radius are drawn there, destroying the portable hole and bag of holding in the process. Moderate conjuration; CL 9th
- **SORTKEY:** Bag of Holding 2

### Bag of Holding (Type III)

- **CONTAINS:** *1000
- **COST:** 7400
- **WT:** 35
- **SPROP:** This appears to be a common cloth sack about 2 feet by 4 feet in size. The bag of holding opens into a nondimensional space: Its inside is larger than its outside dimensions. Regardless of what is put into the bag, it weighs 35lbs and its contents can be up to 1,000lbs and 150 cubic feet. If the bag is overloaded, or if sharp objects pierce it (from inside or outside), the bag ruptures and is ruined. All contents are lost forever. If a bag of holding is turned inside out, its contents spill out, unharmed, but the bag must be put right before it can be used again. If living creatures are placed within the bag, they can survive for up to 10 minutes, after which time they suffocate. Retrieving a specific item from a bag of holding is a move action - unless the bag contains more than an ordinary backpack would hold, in which case retrieving a specific item is a full-round action. If a bag of holding is placed within a portable hole (DMG 264), a rift to the Astral Plane is torn in the space: Bag and hole alike are sucked into the void and forever lost. If a portable hole is placed within a bag of holding, it opens a gate to the Astral Plane: The hole, the bag, and any creatures within a 10-foot radius are drawn there, destroying the portable hole and bag of holding in the process. Moderate conjuration; CL 9th
- **SORTKEY:** Bag of Holding 3

### Bag of Holding (Type IV)

- **CONTAINS:** *1500
- **COST:** 10000
- **WT:** 60
- **SPROP:** This appears to be a common cloth sack about 2 feet by 4 feet in size. The bag of holding opens into a nondimensional space: Its inside is larger than its outside dimensions. Regardless of what is put into the bag, it weighs 60lbs and its contents can be up to 1,500lbs and 250 cubic feet. If the bag is overloaded, or if sharp objects pierce it (from inside or outside), the bag ruptures and is ruined. All contents are lost forever. If a bag of holding is turned inside out, its contents spill out, unharmed, but the bag must be put right before it can be used again. If living creatures are placed within the bag, they can survive for up to 10 minutes, after which time they suffocate. Retrieving a specific item from a bag of holding is a move action - unless the bag contains more than an ordinary backpack would hold, in which case retrieving a specific item is a full-round action. If a bag of holding is placed within a portable hole (DMG 264), a rift to the Astral Plane is torn in the space: Bag and hole alike are sucked into the void and forever lost. If a portable hole is placed within a bag of holding, it opens a gate to the Astral Plane: The hole, the bag, and any creatures within a 10-foot radius are drawn there, destroying the portable hole and bag of holding in the process. Moderate conjuration; CL 9th
- **SORTKEY:** Bag of Holding 4

### Bag of Tricks, Gray

- **COST:** 900
- **WT:** 0
- **SPROP:** This small sack appears normal and empty. However, anyone reaching into the bag feels a small, fuzzy ball. If the ball is removed and tossed up to 20 feet away, it turns into an animal. The animal serves the character who drew it from the bag for 10 minutes (or until slain or ordered back into the bag), at which point it disappears. It can follow any of the commands described in the Handle Animal skill (page 74 of the Player's Handbook). The gray bag can produce: 01-30 Bat, 31-60 Rat, 61-75 Cat, 76-90 Weasel, 91-100 Badger. Animals produced are always random, and only one may exist at a time. Up to ten animals can be drawn from the bag each week. Faint conjuration; CL 3rd

### Bag of Tricks, Rust

- **COST:** 3000
- **WT:** 0
- **SPROP:** This small sack appears normal and empty. However, anyone reaching into the bag feels a small, fuzzy ball. If the ball is removed and tossed up to 20 feet away, it turns into an animal. The animal serves the character who drew it from the bag for 10 minutes (or until slain or ordered back into the bag), at which point it disappears. It can follow any of the commands described in the Handle Animal skill (page 74 of the Player's Handbook). The rust bag can produce: 01-30 Wolverine, 31-60 Wolf, 61-85 Boar, 86-100 Black bear. Animals produced are always random, and only one may exist at a time. Up to ten animals can be drawn from the bag each week. Faint conjuration; CL 5th

### Bag of Tricks, Tan

- **COST:** 6300
- **WT:** 0
- **SPROP:** This small sack appears normal and empty. However, anyone reaching into the bag feels a small, fuzzy ball. If the ball is removed and tossed up to 20 feet away, it turns into an animal. The animal serves the character who drew it from the bag for 10 minutes (or until slain or ordered back into the bag), at which point it disappears. It can follow any of the commands described in the Handle Animal skill (page 74 of the Player's Handbook). The tan bag can produce: 01-30 Brown bear, 31-60 Lion, 61-80 Heavy warhorse (with harness & tack, and accepts whoever drew it from the bag as a rider), 81-90 Tiger, 91-100 Rhinoceros. Animals produced are always random, and only one may exist at a time. Up to ten animals can be drawn from the bag each week. Faint conjuration; CL 9th

### Bead of Force

- **COST:** 3000
- **WT:** 0
- **SPROP:** This small black sphere appears to be a lusterless pearl. You can throw it up to 60 feet with no range penalties. Upon sharp impact, the bead explodes, sending forth a burst that deals 5d6 points of force damage to all creatures within a 10-foot radius. It functions like an Otiluke's resilient sphere spell (Reflex DC 16 negates) with a radius of 10 feet and a duration of 10 minutes. A globe of shimmering force encloses a creature, provided the latter is small enough to fit within the diameter of the sphere. The sphere contains its subject for the spell's duration. The sphere is not subject to damage of any sort except from a rod of cancellation, a rod of negation, disintegrate, or a targeted dispel magic spell. These effects destroy the sphere without harm to the subject. Nothing can pass through the sphere, inside or out, though the subject can breathe normally. The subject may struggle, but the globe cannot be physically moved either by people outside it or by the struggles of those within. The explosion completely consumes the bead, making this a one-use item. Moderate evocation; CL 10th

### Belt, Monk's

- **COST:** 13000
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Monk ~ AC Bonus
- **ABILITY:** Internal|AUTOMATIC|Monk ~ Unarmed Damage
- **BONUS:** VAR|MonkACLVL|5
- **BONUS:** VAR|StunningFistAttackTimes|1
- **BONUS:** VAR|MonkUnarmedDamageLVL|5
- **SPROP:** This simple rope belt, when wrapped around a character's waist, confers great ability in unarmed combat. The wearer's AC and unarmed damage is treated as a monk of five levels higher. If donned by a character with the Stunning Fist feat, the belt lets her make one additional stunning attack per day. If the character is not a monk, she gains the AC and unarmed damage of a 5th-level monk. This AC bonus functions just like the monk's AC bonus. Moderate transmutation; CL 10th

### Belt of Dwarvenkind

- **COST:** 14900
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Dwarf ~ Poison Save Bonus|Dwarf ~ Spell Save Bonus|Dwarf ~ Stonecunning|!PRERACE:1,Dwarf%
- **BONUS:** STAT|CON|2|!PRERACE:1,Dwarf%
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **SPROP:** This belt gives the wearer a +4 competence bonus on Charisma checks and Charisma-based skill checks as they relate to dealing with dwarves, a +2 competence bonus on similar checks when dealing with gnomes and halflings, and a -2 competence penalty on similar checks when dealing with anyone else. The wearer can understand, speak, and read Dwarven. If the wearer is not a dwarf, he gains 60-foot darkvision, dwarven stonecunning, a +2 enhancement bonus to Constitution, and a +2 resistance bonus on saves against poison, spells, or spell-like effects. Moderate divination; CL 12th
- **AUTO:** LANG|Dwarven

### Belt of Giant Strength +4

- **COST:** 16000
- **WT:** 1
- **BONUS:** STAT|STR|4|TYPE=Enhancement
- **SPROP:** This wide belt is made of thick leather and studded with iron. The belt adds to the wearer's Strength score in the form of an enhancement bonus of +4 or +6. Moderate transmutation; CL 10th
- **SORTKEY:** Belt of Strength +04

### Belt of Giant Strength +6

- **COST:** 36000
- **WT:** 1
- **BONUS:** STAT|STR|6|TYPE=Enhancement
- **SPROP:** This wide belt is made of thick leather and studded with iron. The belt adds to the wearer's Strength score in the form of an enhancement bonus of +4 or +6. Moderate transmutation; CL 10th
- **SORTKEY:** Belt of Strength +06

### Boat, Folding

- **CONTAINS:** UNLIM|Any
- **COST:** 7200
- **WT:** 4
- **SPROP:** A folding boat looks like a small wooden box-about 12 inches long, 6 inches wide, and 6 inches deep. It can be used to store items like any other box. If a command word is given, however, the box unfolds itself to form a boat 10 feet long, 4 feet wide, and 2 feet in depth. A second command word causes it to unfold to a ship 24 feet long, 8 feet wide, and 6 feet deep. Any objects formerly stored in the box now rest inside the boat or ship. In its smaller form, the boat has one pair of oars, an anchor, a mast, and a lateen sail. In its larger form, the boat has a deck, single rowing seats, five sets of oars, a steering oar, an anchor, a deck cabin, and a mast with a square sail. The boat can hold four people comfortably, while the ship carries fifteen with ease. A third word of command causes the boat or ship to fold itself into a box once again. The words of command may be inscribed visibly or invisibly on the box, or they may be written elsewhere- perhaps on an item within the box. Faint transmutation; CL 6th

### Boccob's Blessed Book

- **NAMEISPI:** YES
- **NUMPAGES:** 1000
- **PAGEUSAGE:** max(SPELLLEVEL,1)
- **COST:** 12500
- **WT:** 1
- **SPROP:** This well-made tome is always of small size, typically no more than 12 inches tall, 8 inches wide, and 1 inch thick. All such books are durable, waterproof, bound with iron overlaid with silver, and locked. A wizard can fill the 1,000 pages of a Boccob's blessed book with spells without paying the 25 gp per page material cost. This book is never found as randomly generated treasure with spells already inscribed in it. Moderate transmutation; CL 7th

### Boots of Elvenkind

- **COST:** 2500
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** SKILL|Move Silently|5|TYPE=Competence
- **SPROP:** These soft boots enable the wearer to move quietly in virtually any surroundings, granting a +5 competence bonus on Move Silently checks. Faint transmutation; CL 5th

### Boots of Levitation

- **COST:** 7500
- **WT:** 1
- **SLOTS:** 2
- **SPROP:** On command, these leather boots allow the wearer to levitate as if she had cast levitate (PH p.248) on herself. Faint transmutation; CL 3rd

### Boots of Speed

- **COST:** 12000
- **WT:** 1
- **SLOTS:** 2
- **SPROP:** As a free action, the wearer can click her boot heels together, enabling her to act as though affected by a haste spell for up to 10 rounds each day. The duration of the haste effect need not be consecutive rounds. Moderate transmutation; CL 10th

### Boots of Striding and Springing

- **COST:** 5500
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** MOVEADD|TYPE.Walk|10|TYPE=Enhancement
- **BONUS:** SKILL|Jump|5|TYPE=Competence
- **SPROP:** These boots increase the wearer's base land speed by 10 feet. In addition to this striding ability (considered an enhancement bonus), these boots allow the wearer to make great leaps. She can jump with a +5 competence bonus on Jump checks. Faint transmutation; CL 3rd

### Boots of Teleportation

- **COST:** 49000
- **WT:** 3
- **SLOTS:** 2
- **SPROP:** Any character wearing this footwear may teleport three times per day, exactly as if he had cast the spell of the same name. Moderate conjuration; CL 9th

### Boots of the Winterlands

- **COST:** 2500
- **WT:** 1
- **SLOTS:** 2
- **SPROP:** This footgear bestows many powers upon the wearer. First, he is able to travel across snow at his normal speed, leaving no tracks. The boots also enable him to travel at normal speed across the most slippery ice (horizontal surfaces only, not vertical or sharply slanted ones) without falling or slipping. Finally, boots of the winterlands warm the wearer, as if he were affected by an endure elements spell. Faint abjuration and transmutation; CL 5th

### Boots (Winged)

- **COST:** 16000
- **WT:** 1
- **SLOTS:** 2
- **SPROP:** These boots appear to be ordinary footgear. On command, the boots sprout wings at the heel and let the wearer fly, without having to maintain concentration, as if affected by a fly spell. He can fly three times day for up to 5 minutes per flight. Faint transmutation; CL 5th

### Bottle of Air

- **COST:** 7250
- **WT:** 2
- **SPROP:** This item appears to be a normal glass bottle with a cork. When taken to any airless environment (such as underwater or in a vacuum), it retains air within it at all times, continually renewing its contents. This means that a character can draw air out of the bottle to breathe. The bottle can even be shared by multiple characters who pass it around. Breathing out of the bottle is a standard action, but a character so doing can then act for as long as she can hold her breath. Moderate transmutation; CL 7th

### Bowl of Commanding Water Elementals

- **COST:** 100000
- **WT:** 3
- **SPROP:** This large container is usually fashioned from blue or green semiprecious stone (malachite, lapis lazuli, azurite, turquoise, peridot, or sometimes jade). It is about 1 foot in diameter, half that deep, and relatively fragile. When the bowl is filled with fresh water, and certain words are spoken, a Large water elemental appears. The summoning words require 1 full round to speak. In all ways the bowl functions as the summon monster VI spell. Only one elemental can be called at a time. A new elemental requires the bowl to be filled with new water, which cannot happen until after the first elemental disappears (is dispelled, dismissed, or slain). If salt water is used, the elemental is Huge rather than Large (as if summon monster VII had been cast). See page 98 of the Monster Manual for details on water elementals. Strong conjuration; CL 13th

### Bracelet of Friends

- **COST:** 19000
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_4|CHARGES[4]
- **SPROP:** This silver charm bracelet has four charms upon it when created. The owner may designate one person known to him to be keyed to one charm. (This designation takes a standard action, but once done it lasts forever or until changed.) When a charm is grasped and the name of the keyed individual is spoken, that person is called to the spot (a standard action) along with his or her gear, as long as the owner and the called person are on the same plane. The keyed individual knows who is calling, and the bracelet of friends only functions on willing travelers. Once a charm is activated, it disappears. Charms separated from the bracelet are worthless. A bracelet found with fewer than four charms is worth 25%% less for each missing charm. Strong conjuration; CL 15th

### Bracers of Archery (Greater)

- **COST:** 25000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** WEAPONPROF=Longbow|TOHIT|2|TYPE=Competence
- **BONUS:** WEAPONPROF=Longbow|DAMAGE|1|TYPE=Competence
- **BONUS:** WEAPONPROF=Longbow|TOHIT|4|!PREWEAPONPROF:1,Longbow|TYPE=Proficiency
- **BONUS:** WEAPONPROF=Shortbow|TOHIT|2|TYPE=Competence
- **BONUS:** WEAPONPROF=Shortbow|DAMAGE|1|TYPE=Competence
- **BONUS:** WEAPONPROF=Shortbow|TOHIT|4|!PREWEAPONPROF:1,Shortbow|TYPE=Proficiency
- **SPROP:** These wristbands look like normal protective wear. The bracers empower the wearer to use any bow (not including crossbows) as if she were proficient in its use. If she already has proficiency with any type of bow, she gains a +2 competence bonus on attack rolls and a +1 competence bonus on damage rolls whenever using that type of bow. Both bracers must be worn for the magic to be effective. Moderate transmutation; CL 8th

### Bracers of Archery (Lesser)

- **COST:** 5000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** WEAPONPROF=Longbow|TOHIT|1|TYPE=Competence
- **BONUS:** WEAPONPROF=Longbow|TOHIT|4|!PREWEAPONPROF:1,Longbow|TYPE=Proficiency
- **BONUS:** WEAPONPROF=Shortbow|TOHIT|1|TYPE=Competence
- **BONUS:** WEAPONPROF=Shortbow|TOHIT|4|!PREWEAPONPROF:1,Shortbow|TYPE=Proficiency
- **SPROP:** These wristbands look like normal protective wear. The bracers empower the wearer to use any bow (not including crossbows) as if she were proficient in its use. If she already has proficiency with any type of bow, she gains a +1 competence bonus on attack rolls whenever using that type of bow. Both bracers must be worn for the magic to be effective. Faint transmutation; CL 4th

### Bracers of Armor +1

- **COST:** 1000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|1|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +1, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +01

### Bracers of Armor +2

- **COST:** 4000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|2|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +2, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +02

### Bracers of Armor +3

- **COST:** 9000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|3|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +3, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +03

### Bracers of Armor +4

- **COST:** 16000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|4|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +4, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +04

### Bracers of Armor +5

- **COST:** 25000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +5, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +05

### Bracers of Armor +6

- **COST:** 36000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|6|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +6, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +06

### Bracers of Armor +7

- **COST:** 49000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|7|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +7, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +07

### Bracers of Armor +8

- **COST:** 64000
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** These items appear to be wrist or arm guards. They surround the wearer with an invisible but tangible field of force, granting him an armor bonus of +8, just as though he were wearing armor. Both bracers must be worn for the magic to be effective. Moderate conjuration; CL 7th
- **SORTKEY:** Bracers of Armor +08

### Brazier of Commanding Fire Elementals

- **COST:** 100000
- **WT:** 5
- **SPROP:** This device appears to be a normal container for holding burning coals. When a fire is lit in the brazier and the proper summoning words are spoken, a Large fire elemental appears. The summoning words require 1 full round to speak. In all ways the brazier functions as the summon monster VI spell. If brimstone is added, the elemental is Huge instead of Large, and the brazier works as a summon monster VII spell. Only one elemental can be summoned at a time. A new elemental requires a new fire, which cannot be lit until after the first elemental disappears (is dispelled, dismissed, or slain). See page 98 of the Monster Manual for details on fire elementals. Strong conjuration; CL 13th

### Brooch of Shielding

- **COST:** 1500
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_101|CHARGES[101]
- **SPROP:** This appears to be a piece of silver or gold jewelry used to fasten a cloak or cape. In addition to this mundane task, it can absorb magic missiles of the sort generated by spell or spell-like ability. A brooch can absorb up to 101 points of damage from magic missiles before it melts and becomes useless. Faint abjuration; CL 1st

### Broom of Flying

- **COST:** 17000
- **WT:** 3
- **SPROP:** This broom is able to fly through the air as if affected by an overland flight spell (average maneuverability) for up to 9 hours per day (split up as its owner desires). The broom can carry 200 pounds and fly at a speed of 40 feet, or up to 400 pounds at a speed at 30 feet. In addition, the broom can travel alone to any destination named by the owner as long as she has a good idea of the location and layout of that destination. It comes to its owner from as far away as 300 yards when she speaks the command word. The broom of flying has a speed of 40 feet when it has no rider. Moderate transmutation; CL 9th

### Candle of Invocation

- **COST:** 8400
- **WT:** 0.5
- **SPROP:** Each of these special tapers is dedicated to one of the nine alignments. Simply burning the candle generates a favorable aura for the individual so doing if the candle's alignment matches that of the character. Characters of the same alignment as the burning candle add a +2 morale bonus on attack rolls, saving throws, and skill checks while within 30 feet of the flame. A cleric whose alignment matches the candle's operates as if two levels higher for purposes of determining spells per day if he burns the candle during or just prior to his spell preparation time. He can even cast spells normally unavailable to him, as if he were of that higher level, but only so long as the candle continues to burn. Except in special cases (see below), a candle burns for 4 hours. In addition, burning a candle also allows the owner to cast a gate spell, the respondent being of the same alignment as the candle, but the taper is immediately consumed in the process. It is possible to extinguish the candle simply by blowing it out, so users often place it in a lantern to protect it from drafts and the like. Doing this doesn't interfere with its magical properties. Strong conjuration; CL 17th

### Candle of Truth

- **COST:** 2500
- **WT:** 0.5
- **SPROP:** This white tallow candle, when burned, calls into place a zone of truth spell (Will DC 13 negates) in a 5-foot radius centered on the candle. The zone lasts for 1 hour, as the candle burns. If the candle is snuffed before that time, the effect is canceled and the candle ruined. Faint enchantment; CL 3rd

### Cape of the Mountebank

- **COST:** 10080
- **WT:** 1
- **SPROP:** On command, this bright red and gold cape allows the wearer to use the magic of the dimension door spell once per day. When he disappears, he leaves behind a cloud of smoke, appearing in a similar fashion at his destination. Moderate conjuration; CL 9th

### Carpet of Flying (5x5)

- **COST:** 20000
- **WT:** 8
- **SPROP:** This rug is able to fly through the air with a speed of 40ft as if affected by an overland flight spell of unlimited duration. This rug can carry 200lbs. Beautifully and intricately made, the carpet has its own command word to activate it-if the device is within voice range, the command word activates it, whether the speaker is on the rug or not. The carpet is then controlled by spoken directions. A carpet of flying can carry up to double its capacity, but doing so reduces its speed to 30 feet. It has average maneuverability, but a carpet of flying can still hover. Moderate transmutation; CL 10th
- **SORTKEY:** Carpet of Flying, 0505

### Carpet of Flying (5x10)

- **COST:** 35000
- **WT:** 15
- **SPROP:** This rug is able to fly through the air with a speed of 40ft as if affected by an overland flight spell of unlimited duration. This rug can carry 400lbs. Beautifully and intricately made, the carpet has its own command word to activate it-if the device is within voice range, the command word activates it, whether the speaker is on the rug or not. The carpet is then controlled by spoken directions. A carpet of flying can carry up to double its capacity, but doing so reduces its speed to 30 feet. It has average maneuverability, but a carpet of flying can still hover. Moderate transmutation; CL 10th
- **SORTKEY:** Carpet of Flying, 0510

### Carpet of Flying (10x10)

- **COST:** 60000
- **WT:** 10
- **SPROP:** This rug is able to fly through the air with a speed of 40ft as if affected by an overland flight spell of unlimited duration. This rug can carry 800lbs.Beautifully and intricately made, the carpet has its own command word to activate it-if the device is within voice range, the command word activates it, whether the speaker is on the rug or not. The carpet is then controlled by spoken directions. A carpet of flying can carry up to double its capacity, but doing so reduces its speed to 30 feet. It has average maneuverability, but a carpet of flying can still hover. Moderate transmutation; CL 10th
- **SORTKEY:** Carpet of Flying, 1010

### Censer of Controlling Air Elementals

- **COST:** 100000
- **WT:** 1
- **SPROP:** This 6-inch-wide, 1-inch-high perforated golden vessel resembles a thurible found in a place of worship. If it is filled with incense and lit, summoning words spoken over it summon forth a Large air elemental. The summoning words require 1 full round to speak. In all ways the censer functions as the summon monster VI spell. If incense of meditation is burned within the censer, the air elemental is an elder air elemental instead (as if summon monster IX had just been cast). Only one elemental can be summoned at a time. A new elemental requires a new piece of incense, which cannot be lit until after the first elemental disappears (is dispelled, dismissed, or slain). See page 95 of the Monster Manual for details on air elementals. Strong conjuration; CL 17th

### Chaos Diamond

- **COST:** 160000
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|1
- **SPROP:** This lustrous gemstone is uncut and about the size of a human fist. The gem grants its possessor the following powers: . Confusion, lesser . Magic circle against law . Word of chaos . Cloak of chaos Each power is usable 1d4 times per day. (The DM rolls secretly each day for each power separately.) A nonchaotic character who possesses a chaos diamond gains one negative level. Although this level never results in actual level loss, it remains as long as the diamond is in the character's possession and cannot be overcome in any way (including restoration spells). Strong varied; CL 19th

### Chime of Interruption

- **COST:** 16800
- **WT:** 1
- **SPROP:** This instrument can be struck once every 10 minutes, and its resonant tone lasts for 3 full minutes. While the chime is resonating, no spell requiring a verbal component can be cast within a 30-foot radius of it unless the caster can make a Concentration check (DC 15 + the spell's level). Moderate evocation; CL 7th

### Chime of Opening

- **COST:** 3000
- **WT:** 1
- **EQMOD:** CHARGED_ITEM_10|CHARGES[10]
- **SPROP:** A chime of opening is a hollow mithral tube about 1 foot long. When struck, it sends forth magical vibrations that cause locks, lids, doors, valves, and portals to open. The device functions against normal bars, shackles, chains, bolts, and so on. A chime of opening also automatically dispels a hold portal spell or even an arcane lock cast by a wizard of lower than 15th level. The chime must be pointed at the item or gate to be loosed or opened (which must be visible and known to the user). The chime is then struck, a clear tone rings forth, and in 1 round the target lock is unlocked, the shackle is loosed, the secret door is opened, or the lid of the chest is lifted. Each sounding only opens one form of locking, so if a chest is chained, padlocked, locked, and arcane locked, it takes four uses of a chime of opening to get it open. A silence spell negates the power of the device. A brand-new chime can be used a total of ten times before it cracks and becomes useless. Moderate transmutation; CL 11th

### Circlet of Blasting (Minor)

- **COST:** 6480
- **WT:** 0
- **SPROP:** On command, this simple golden headband projects a blast of searing light (3d8 points of damage) once per day. Faint evocation; CL 6th

### Circlet of Blasting (Major)

- **COST:** 23760
- **WT:** 0
- **SPROP:** On command, this elaborate golden headband projects a blast of searing light (5d8 maximized for 40 points of damage) once per day. Strong evocation; CL 17th

### Circlet of Persuasion

- **COST:** 4500
- **WT:** 0
- **BONUS:** SKILL|STAT=CHA|3|TYPE=Competence
- **BONUS:** VAR|TurnCheckBase|3|TYPE=Competence
- **SPROP:** This silver headband grants a +3 competence bonus on the wearer's Charisma-based checks. Faint transmutation; CL 5th

### Cloak of Arachnida

- **COST:** 14000
- **WT:** 1
- **SPROP:** This black garment, embroidered with a weblike pattern in silk, gives the wearer the ability to climb as if a spider climb spell had been placed upon her. In addition, the cloak grants her immunity to entrapment by web spells or webs of any sort-she can actually move in webs at half her normal speed. Once per day, the wearer of this cloak can cast web. She also gains a +2 luck bonus on all Fortitude saves against poison from spiders. Faint conjuration and transmutation; CL 6th

### Cloak of the Bat

- **COST:** 26000
- **WT:** 1
- **BONUS:** SKILL|Hide|5|TYPE=Competence
- **SPROP:** Fashioned of dark brown or black cloth, this cloak bestows a +5 competence bonus on Hide checks. The wearer is also able to hang upside down from the ceiling, like a bat. By holding the edges of the garment, the wearer is able to fly as per the spell. If he desires, the wearer can actually polymorph himself into an ordinary bat and fly accordingly. (All possessions worn or carried are part of the transformation.) Flying, either with the cloak or in bat form, can be accomplished only in darkness (either under the night sky or in a lightless or near-lightless environment underground). Either of the flying powers is usable for up to 7 minutes at a time, but after a flight of any duration the cloak cannot bestow any flying power for a like period of time. Moderate transmutation; CL 7th

### Cloak of Charisma +2

- **COST:** 4000
- **WT:** 2
- **BONUS:** STAT|CHA|2|TYPE=Enhancement
- **SPROP:** This lightweight and fashionable cloak has a highly decorative silver trim. When in a character's possession, it adds a +2 enhancement bonus to her Charisma score. Moderate transmutation; CL 8th
- **SORTKEY:** Cloak of Charisma +02

### Cloak of Charisma +4

- **COST:** 16000
- **WT:** 2
- **BONUS:** STAT|CHA|4|TYPE=Enhancement
- **SPROP:** This lightweight and fashionable cloak has a highly decorative silver trim. When in a character's possession, it adds a +4 enhancement bonus to her Charisma score. Moderate transmutation; CL 8th
- **SORTKEY:** Cloak of Charisma +04

### Cloak of Charisma +6

- **COST:** 36000
- **WT:** 2
- **BONUS:** STAT|CHA|6|TYPE=Enhancement
- **SPROP:** This lightweight and fashionable cloak has a highly decorative silver trim. When in a character's possession, it adds a +6 enhancement bonus to her Charisma score. Moderate transmutation; CL 8th
- **SORTKEY:** Cloak of Charisma +06

### Cloak of Displacement (Minor)

- **COST:** 24000
- **WT:** 1
- **SPROP:** This item appears to be a normal cloak, but when worn by a character its magical properties distort and warp light waves. This displacement works similar to the displacement spell except that it only grants a 20%% miss chance on attacks against the wearer. It functions continually. Faint illusion; CL 3rd

### Cloak of Displacement (Major)

- **COST:** 50000
- **WT:** 1
- **SPROP:** This item appears to be a normal cloak, but on command its magical properties distort and warp light waves. This displacement works just like the displacement spell and lasts for a total of 15 rounds per day, which the wearer can divide up as she sees fit. Moderate illusion; CL 7th

### Cloak of Elvenkind

- **COST:** 2500
- **WT:** 1
- **BONUS:** SKILL|Hide|5|TYPE=Competence
- **SPROP:** This cloak of neutral gray cloth is indistinguishable from an ordinary cloak of the same color. However, when worn with the hood drawn up around the head, it gives the wearer a +5 competence bonus on Hide checks. Faint illusion; CL 3rd

### Cloak of Etherealness

- **COST:** 55000
- **WT:** 1
- **SPROP:** This silvery-gray cloak seems to absorb light rather than be illuminated by it. On command, the cloak makes its wearer ethereal (as the ethereal jaunt spell). The effect is dismissible. The cloak works for a total of up to 10 minutes per day. This duration need not be continuous. Strong transmutation; CL 15th

### Cloak of the Manta Ray

- **COST:** 7200
- **WT:** 1
- **SPROP:** This cloak appears to be made of leather until the wearer enters salt water. At that time the cloak of the manta ray adheres to the individual, and he appears nearly identical to a manta ray (as the polymorph spell, except that it allows only manta ray form). He gains a +3 natural armor bonus, the ability to breathe underwater, and a swim speed of 60 feet, like a real manta ray. Although the cloak does not enable the wearer to bite opponents as a manta ray does, it does have a tail spine that can be used to strike at opponents behind the wearer, dealing 1d6 points of damage. This attack can be used in addition to any other attack the character has, using his highest melee attack bonus. The wearer can release his arms from the cloak without sacrificing underwater movement if so desired. Moderate transmutation; CL 9th;

### Cloak of Resistance +1

- **COST:** 1000
- **WT:** 1
- **SPROP:** These garments offer magic protection in the form of a +1 resistance bonus on all saving throws (Fortitude, Reflex, and Will). Faint abjuration; CL 5th
- **BONUS:** SAVE|Fortitude,Reflex,Will|1|TYPE=Resistance
- **SORTKEY:** Cloak of Resistance +01

### Cloak of Resistance +2

- **COST:** 4000
- **WT:** 1
- **SPROP:** These garments offer magic protection in the form of a +2 resistance bonus on all saving throws (Fortitude, Reflex, and Will). Faint abjuration; CL 5th
- **BONUS:** SAVE|Fortitude,Reflex,Will|2|TYPE=Resistance
- **SORTKEY:** Cloak of Resistance +02

### Cloak of Resistance +3

- **COST:** 9000
- **WT:** 1
- **SPROP:** These garments offer magic protection in the form of a +3 resistance bonus on all saving throws (Fortitude, Reflex, and Will). Faint abjuration; CL 5th
- **BONUS:** SAVE|Fortitude,Reflex,Will|3|TYPE=Resistance
- **SORTKEY:** Cloak of Resistance +03

### Cloak of Resistance +4

- **COST:** 16000
- **WT:** 1
- **SPROP:** These garments offer magic protection in the form of a +4 resistance bonus on all saving throws (Fortitude, Reflex, and Will). Faint abjuration; CL 5th
- **BONUS:** SAVE|Fortitude,Reflex,Will|4|TYPE=Resistance
- **SORTKEY:** Cloak of Resistance +04

### Cloak of Resistance +5

- **COST:** 25000
- **WT:** 1
- **SPROP:** These garments offer magic protection in the form of a +5 resistance bonus on all saving throws (Fortitude, Reflex, and Will). Faint abjuration; CL 5th
- **BONUS:** SAVE|Fortitude,Reflex,Will|5|TYPE=Resistance
- **SORTKEY:** Cloak of Resistance +05

### Crystal Ball

- **COST:** 42000
- **WT:** 7
- **SPROP:** This is the most common form of scrying device, a crystal sphere about 6 inches in diameter. A character can use the device to see over virtually any distance or into other planes of existence, as with the spell scrying (Will DC 16 negates). Certain crystal balls have additional powers that can be used through the crystal ball on the target viewed. Moderate divination; CL 10th

### Crystal Ball (Detect Thoughts)

- **COST:** 51000
- **WT:** 7
- **SPROP:** This is the most common form of scrying device, a crystal sphere about 6 inches in diameter. A character can use the device to see over virtually any distance or into other planes of existence, as with the spell scrying (Will DC 16 negates). Certain crystal balls have additional powers that can be used through the crystal ball on the target viewed. Moderate divination; CL 10th

### Crystal Ball (See Invisibility)

- **COST:** 50000
- **WT:** 7
- **SPROP:** This is the most common form of scrying device, a crystal sphere about 6 inches in diameter. A character can use the device to see over virtually any distance or into other planes of existence, as with the spell scrying (Will DC 16 negates). Certain crystal balls have additional powers that can be used through the crystal ball on the target viewed. Moderate divination; CL 10th

### Crystal Ball (Telepathy)

- **COST:** 70000
- **WT:** 7
- **SPROP:** This is the most common form of scrying device, a crystal sphere about 6 inches in diameter. A character can use the device to see over virtually any distance or into other planes of existence, as with the spell scrying (Will DC 16 negates). Certain crystal balls have additional powers that can be used through the crystal ball on the target viewed. Moderate divination; CL 10th

### Crystal Ball (True Seeing)

- **COST:** 80000
- **WT:** 7
- **SPROP:** This is the most common form of scrying device, a crystal sphere about 6 inches in diameter. A character can use the device to see over virtually any distance or into other planes of existence, as with the spell scrying (Will DC 16 negates). Certain crystal balls have additional powers that can be used through the crystal ball on the target viewed. Moderate divination; CL 10th

### Cube of Force

- **COST:** 62000
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_36|CHARGES[36]
- **SPROP:** This device is about the size of a large die (perhaps 3/4 inch across) and can be made of ivory, bone, or any hard mineral. It enables its possessor to put up a special wall of force 10 feet on a side around her person. This cubic screen moves with the character and is impervious to the attack forms mentioned on the table below. The cube has 36 charges, which are renewed each day. The possessor presses one face of the cube to activate a particular type of screen or to deactivate the device. Each effect costs a certain number of charges to maintain for every minute (or portion of a minute) it is in operation. Also, when an effect is active, the possessor's speed is limited to the maximum value given on the table. When the cube of force is active, attacks dealing more than 30 points of damage drain 1 charge for every 10 points of damage beyond 30 that they deal (40 points of damage drains 1 charge, 50 points drains 2 charges, and so forth). Spells that affect the integrity of the screen, such as disintegrate and passwall, also drain extra charges. Moderate evocation; CL 10th

### Cube of Frost Resistance

- **COST:** 27000
- **WT:** 0
- **SPROP:** This cube is activated or deactivated by pressing one side. When activated, it creates a cubeshaped area 10 feet on a side centered on the possessor (or on the cube itself, if the item is later placed on a surface). The temperature within this area is always at least 65degreeF. The field absorbs all cold-based attacks (such as ice storm, cone of cold, and white dragon breath). However, if the field is subjected to more than 50 points of cold damage in 1 round (from one or multiple attacks), it collapses into its portable form and cannot be reactivated for 1 hour. If the field absorbs more than 100 points of cold damage in a 10- round period, the cube is destroyed. Faint abjuration; CL 5th

### Cubic Gate

- **COST:** 164000
- **WT:** 0
- **SPROP:** This item is fashioned from carnelian. Each of the six sides of the cube is keyed to a plane, one of which is the Material Plane. The character creating the item should choose the planes to which the other five sides are keyed. If such a cube is found as treasure, the DM can determine the planes accessed by the device in any manner he or she chooses. If a side of the cubic gate is pressed once, it opens a gate to a random point on the plane keyed to that side. There is a 10%% chance per minute that an outsider from that plane (determine randomly) comes through it looking for food, fun, or trouble. Pressing the side a second time closes the gate. It is impossible to open more than one gate at a time. If a side is pressed twice in quick succession, the character so doing is transported to a random point on the other plane, along with all creatures in adjacent squares. (The other creatures may avoid this fate by succeeding on DC 23 Will saves). Strong conjuration; CL 13th

### Daern's Instant Fortress

- **NAMEISPI:** YES
- **COST:** 55000
- **WT:** 0
- **SPROP:** This metal cube is small, but when activated by speaking a command word it grows to form a tower 20 feet square and 30 feet high, with arrow slits on all sides and a crenellated battlement atop it. The metal walls extend 10 feet into the ground, rooting it to the spot and preventing it from being tipped over. The fortress has a small door that opens only at the command of the owner of the fortress-even knock spells can't open the door. The adamantine walls of Daern's instant fortress have 100 hit points and hardness 20. The fortress cannot be repaired except by a wish or a miracle, which restores 50 points of damage taken. The fortress springs up in just 1 round, with the door facing the device's owner. The door opens and closes instantly at his command. People and creatures nearby (except the owner) must be careful not to be caught by the fortress's sudden growth. Anyone so caught takes 10d10 points of damage (Reflex DC 19 half ). The fortress is deactivated by speaking a command word (different from the one used to activate it). It cannot be deactivated unless it is empty. Strong conjuration; CL 13th

### Darkskull

- **COST:** 60000
- **WT:** 5
- **SPROP:** This skull, carved from ebony, is wholly evil. Wherever the skull goes, the area around it is treated as though an unhallow spell had been cast with the skull as the touched point of origin (except that no additional spell effect is tied or fixed to the darkskull). Moderate evocation [evil]; CL 9th

### Decanter of Endless Water

- **COST:** 9000
- **WT:** 2
- **SPROP:** If the stopper is removed from this ordinary-looking flask and a command word spoken, an amount of fresh or salt water pours out. Separate command words determine the type as well as the volume and velocity. . "Stream" pours out 1 gallon per round. . "Fountain" produces a 5-foot-long stream at 5 gallons per round. . "Geyser" produces a 20-foot-long, 1-foot-wide stream at 30 gallons per round. The geyser effect causes considerable back pressure, requiring the holder to make a DC 12 Strength check to avoid being knocked down. The force of the geyser deals 1d4 points of damage but can only affect one target per round. The command word must be spoken to stop it. Moderate transmutation; CL 9th;

### Deck of Illusions

- **COST:** 8100
- **WT:** 0.5
- **EQMOD:** CHARGED_ITEM_34|CHARGES[34]
- **SPROP:** This set of parchment cards is usually found in an ivory, leather, or wooden box. A full deck consists of thirty four cards. When a card is drawn at random and thrown to the ground, a major image (PH P252) of a creature is formed. The figment lasts until dispelled. The illusory creature cannot move more than 30 feet away from where the card landed, but otherwise moves and acts as if it were real. At all times it obeys the desires of the character who drew the card. When the illusion is dispelled, the card becomes blank and cannot be used again. If the card is picked up, the illusion is automatically and instantly dispelled. The cards in a deck and the illusions they bring forth are summarized on the following table. (Use one of the first two columns to simulate the contents of a full deck using either ordinary playing cards or tarot cards.) Faint illusion; CL 6th

### Dimensional Shackles

- **COST:** 28000
- **WT:** 5
- **SPROP:** These shackles have golden runes traced across their cold iron surface. Any creature bound within them is affected as if a dimensional anchor spell were cast upon her (no save). They fit any Small to Large creature. The DC to break or slip out of the shackles is 30. Moderate abjuration; CL 11th

### Drums of Panic

- **COST:** 30000
- **WT:** 10
- **SPROP:** These drums are kettle drums (hemispheres about 1-1/2 feet in diameter on stands). They come in pairs and are unremarkable in appearance. If both of the pair are sounded, all creatures within 120 feet (with the exception of those within a 20-foot-radius safe zone around the drums) are affected as by a fear spell (Will DC 16 partial). Drums of panic can be used once per day. Moderate necromancy; CL 7th

### Dust of Appearance

- **COST:** 1800
- **WT:** 0
- **SPROP:** This fine powder appears to be a very fine, very light metallic dust. A single handful of this substance flung into the air coats objects within a 10-foot radius, making them visible even if they are invisible. It likewise negates the effects of blur and displacement. (In this, it works just like the faerie fire spell). The dust also reveals figments, mirror images, and projected images for what they are. A creature coated with the dust takes a -30 penalty on its Hide checks. The dust's effect lasts for 5 minutes. Dust of appearance is typically stored in small silk packets or hollow bone tubes. Faint conjuration; CL 5th

### Dust of Disappearance

- **COST:** 3500
- **WT:** 0
- **SPROP:** This dust looks just like dust of appearance and is typically stored in the same manner. A creature or object touched by it becomes invisible (as greater invisibility). Normal vision can't see dusted creatures or objects, nor can they be detected by magical means, including see invisibility or invisibility purge. Dust of appearance, however, does reveal people and objects made invisible by dust of disappearance. Other factors, such as sound and smell, also allow possible detection. The greater invisibility bestowed by the dust lasts for 2d6 rounds. The invisible creature doesn't know when the duration will end. Moderate illusion; CL 7th

### Dust of Dryness

- **COST:** 850
- **WT:** 0
- **SPROP:** This special dust has many uses. If it is thrown into water, a volume of as much as 100 gallons is instantly transformed to nothingness, and the dust becomes a marble-sized pellet, floating or resting where it was thrown. If this pellet is hurled down, it breaks and releases the same volume of water. The dust affects only water (fresh, salt, alkaline), not other liquids. If the dust is employed against an elemental with the water subtype, the creature must make a DC 18 Fortitude save or be destroyed. The dust deals 5d6 points of damage to the creature even if its saving throw succeeds. Moderate transmutation; CL 11th

### Dust of Illusion

- **COST:** 1200
- **WT:** 0
- **SPROP:** This unremarkable powder resembles chalk dust or powdered graphite. Stare at it, however, and the dust changes color and form. Put dust of illusion on a creature, and that creature is affected as if by a disguise self glamer, with the individual who sprinkles the dust envisioning the illusion desired. An unwilling target is allowed a DC 11 Reflex save to avoid the dust. The glamer lasts for 2 hours. Faint illusion; CL 6th

### Dust of Tracelessness

- **COST:** 250
- **WT:** 0
- **SPROP:** This normal-seeming dust is actually a magic powder that can conceal the passage of its possessor and his companions. Tossing a handful of this dust into the air causes a chamber of up to 100 square feet of floor space to become as dusty, dirty, and cobweb-laden as if it had been abandoned and disused for a decade. A handful of dust sprinkled along a trail causes evidence of the passage of as many as a dozen men and horses to be obliterated for 250 feet back into the distance. The results of the dust are instantaneous, and no magical aura lingers afterward from this use of the dust. Survival checks made to track a quarry across an area affected by this dust have a DC 20 higher than normal. Faint transmutation; CL 3rd

### Efreeti Bottle

- **COST:** 145000
- **WT:** 1
- **SPROP:** This item is typically fashioned of brass or bronze, with a lead stopper bearing special seals. A thin stream of smoke is often seen issuing from it. The bottle can be opened once per day. When opened, the efreeti imprisoned within issues from the bottle instantly. There is a 10%% chance (01-10 on d%%) that the efreeti is insane and attacks immediately upon being released. There is also a 10%% chance (91-100) that the efreeti of the bottle grants three wishes. In either case, the efreeti afterward disappears forever. The other 80%% of the time (11-90), the inhabitant of the bottle loyally serves the character for up to 10 minutes per day (or until the efreeti's death), doing as she commands. (See page 115 of the Monster Manual for efreeti statistics.) Roll each day the bottle is opened for that day's effect. Strong conjuration; CL 14th

### Elemental Gem (Transparent)

- **COST:** 2250
- **WT:** 0
- **SPROP:** This gem contains a conjuration spell attuned to Elemental Plane of Air. When the gem is crushed, smashed, or broken (a standard action), a Large elemental appears as if summoned by a summon nature's ally spell. The elemental is under the control of the creature that broke the gem. Moderate conjuration; CL 11th;

### Elemental Gem (Light Brown)

- **COST:** 2250
- **WT:** 0
- **SPROP:** This gem contains a conjuration spell attuned to Elemental Plane of Earth. When the gem is crushed, smashed, or broken (a standard action), a Large elemental appears as if summoned by a summon nature's ally spell. The elemental is under the control of the creature that broke the gem. Moderate conjuration; CL 11th;

### Elemental Gem (Reddish Orange)

- **COST:** 2250
- **WT:** 0
- **SPROP:** This gem contains a conjuration spell attuned to Elemental Plane of Fire. When the gem is crushed, smashed, or broken (a standard action), a Large elemental appears as if summoned by a summon nature's ally spell. The elemental is under the control of the creature that broke the gem. Moderate conjuration; CL 11th;

### Elemental Gem (Blue-Green)

- **COST:** 2250
- **WT:** 0
- **SPROP:** This gem contains a conjuration spell attuned to Elemental Plane of Water . When the gem is crushed, smashed, or broken (a standard action), a Large elemental appears as if summoned by a summon nature's ally spell. The elemental is under the control of the creature that broke the gem. Moderate conjuration; CL 11th;

### Elixir of Fire Breath

- **COST:** 1100
- **WT:** 0
- **SPROP:** This strange elixir bestows upon the drinker the ability to spit gouts of flame. He can breathe fire up to three times, each time dealing 4d6 points of fire damage to a single target up to 25 feet away. The victim can attempt a DC 13 Reflex save for half damage. Unused blasts dissipate 1 hour after the liquid is consumed. Moderate evocation; CL 11th

### Elixir of Hiding

- **COST:** 250
- **WT:** 0
- **SPROP:** A character drinking this liquid gains an intuitive ability to hide (+10 competence bonus on Hide checks for 1 hour). Faint illusion; CL 5th

### Elixir of Love

- **COST:** 150
- **WT:** 0
- **SPROP:** This sweet-tasting liquid causes the character drinking it to become charmed with the first creature she sees after consuming the draft (as charm person-the drinker must be a humanoid of Medium or smaller size, Will DC 14 negates). The charm effects wear off in 1d3 hours. Faint transmutation; CL 4th

### Elixir of Sneaking

- **COST:** 250
- **WT:** 0
- **SPROP:** This draught of liquid grants the drinker the ability to walk softly and dampens sound around her slightly, granting a +10 competence bonus on Move Silently checks for 1 hour. Faint illusion; CL 5th;

### Elixir of Swimming

- **COST:** 250
- **WT:** 0
- **SPROP:** This elixir bestows swimming ability. An almost imperceptible magic sheath surrounds the drinker, allowing him to glide through the water easily (+10 competence bonus on Swim checks for 1 hour). Faint illusion; CL 2nd

### Elixir of Truth

- **COST:** 500
- **WT:** 0
- **SPROP:** This elixir forces the individual drinking it to say nothing but the truth for 10 minutes (Will DC 13 negates). She is compelled to answer any questions put to her in that time, but with each question she is free to make a separate DC 13 Will save. If one of these secondary saves is successful, she doesn't break free of the truth-compelling enchantment but also doesn't have to answer that particular question. No more than one question can be asked each round. This is a mind-affecting compulsion enchantment. Faint enchantment; CL 5th

### Elixir of Vision

- **COST:** 250
- **WT:** 0
- **SPROP:** Drinking this elixir grants the imbiber the ability to notice acute details with great accuracy (+10 competence bonus on Search checks for 1 hour). Faint divination; CL 2nd

### Eversmoking Bottle

- **COST:** 5400
- **WT:** 1
- **SPROP:** This metal urn is identical in appearance to an efreeti bottle, except that it does nothing but smoke. The amount of smoke is great if the stopper is pulled out, pouring from the bottle and totally obscuring vision across a 50-foot spread in 1 round. If the bottle is left unstoppered, the smoke billows out another 10 feet per round until it has covered a 100-foot radius. This area remains smoke-filled until the eversmoking bottle is stoppered. The bottle must be resealed by a command word, after which the smoke dissipates normally. A moderate wind (11+ mph) disperses the smoke in 4 rounds; a strong wind (21+ mph) disperses the smoke in 1 round. Faint transmutation; CL 3rd

### Eyes of Charming

- **COST:** 56000
- **WT:** 0
- **SPROP:** These two crystal lenses fit over the user's eyes. The wearer is able to use charm person (one target per round) merely by meeting a target's gaze. Those failing a DC 16 Will save are charmed as per the spell. If the wearer has only one lens, the DC of the saving throw is reduced to 10. Moderate enchantment; CL 7th

### Eyes of Charming (Single Lens)

- **COST:** 28000
- **WT:** 0
- **SPROP:** These two crystal lenses fit over the user's eyes. The wearer is able to use charm person (one target per round) merely by meeting a target's gaze. Those failing a DC 16 Will save are charmed as per the spell. If the wearer has only one lens, the DC of the saving throw is reduced to 10. Moderate enchantment; CL 7th

### Eyes of Doom

- **COST:** 25000
- **WT:** 0
- **SPROP:** These crystal lenses fit over the user's eyes, enabling him to cast doom upon those around him (one target per round) as a gaze attack, except that the wearer must take a standard action, and those merely looking at the wearer are not affected. Those failing a DC 11 Will save are affected as by the doom spell. If the wearer has only one lens, the DC of the saving throw is reduced to 10. However, if the wearer has both lenses, he gains the additional power of a continual deathwatch effect and can use fear (Will DC 16 partial) as a normal gaze attack once per week. Moderate necromancy; CL 11th

### Eyes of Doom (Single Lens)

- **COST:** 12500
- **WT:** 0
- **SPROP:** These crystal lenses fit over the user's eyes, enabling him to cast doom upon those around him (one target per round) as a gaze attack, except that the wearer must take a standard action, and those merely looking at the wearer are not affected. Those failing a DC 11 Will save are affected as by the doom spell. If the wearer has only one lens, the DC of the saving throw is reduced to 10. However, if the wearer has both lenses, he gains the additional power of a continual deathwatch effect and can use fear (Will DC 16 partial) as a normal gaze attack once per week. Moderate necromancy; CL 11th

### Eyes of the Eagle

- **COST:** 2500
- **WT:** 0
- **BONUS:** SKILL|Spot|5|TYPE=Competence
- **SPROP:** These items are made of special crystal and fit over the eyes of the wearer. These lenses grant a +5 competence bonus on Spot checks. Wearing only one of the pair causes a character to become dizzy and, in effect, stunned for 1 round. Thereafter, the wearer can use the single lens without being stunned so long as she covers her other eye. Of course, she can remove the single lens and see normally at any time, or wear both lenses to end or avoid the dizziness. Faint divination; CL 3rd

### Eyes of the Eagle (Single Lens)

- **COST:** 1250
- **WT:** 0
- **BONUS:** SKILL|Spot|5|TYPE=Competence
- **SPROP:** These items are made of special crystal and fit over the eyes of the wearer. These lenses grant a +5 competence bonus on Spot checks. Wearing only one of the pair causes a character to become dizzy and, in effect, stunned for 1 round. Thereafter, the wearer can use the single lens without being stunned so long as she covers her other eye. Of course, she can remove the single lens and see normally at any time, or wear both lenses to end or avoid the dizziness. Faint divination; CL 3rd

### Eyes of Petrification

- **COST:** 98000
- **WT:** 0
- **SPROP:** These items are made of special crystal and fit over the eyes of the wearer. They allow her to use a petrification gaze attack (Fortitude DC 19 negates) for 10 rounds per day. Both lenses must be worn for the magic to be effective. Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Bronze Griffon)

- **COST:** 10000
- **WT:** 0
- **SPROP:** This figurine of wondrous power appears to be a miniature statuette of a griffon an inch or so high. When the figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. When animated, a bronze griffon acts in all ways like a normal griffon under the command of its possessor. The item can be used twice per week for up to 6 hours per use. When 6 hours have passed or when the command word is spoken, the bronze griffon once again becomes a tiny statuette. Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Ebony Fly)

- **COST:** 10000
- **WT:** 0
- **SPROP:** This figurine of wondrous power appears to be a miniature statuette of a hippogriff an inch or so high. When the figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. When animated, an ebony fly is the size of a pony and has all the statistics of a hippogriff (Hit Dice, AC, carrying capacity, speed, and so on; see page 152 of the Monster Manual) but can make no attacks. The item can be used three times per week for up to 12 hours per use. When 12 hours have passed or when the command word is spoken, the ebony fly again becomes a tiny statuette. Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Golden Lions)

- **COST:** 16500
- **WT:** 0
- **SPROP:** This pair of figurines of wondrous power appears to be two miniature statuette of lions an inch or so high. When the figurines are tossed down and the correct command word spoken, they become living creatures of normal size. The creatures obey and serves their owner. The creatures understand Common but do not speak. If the figurines are broken or destroyed in their statuette form, they are forever ruined. All magic is lost, their power departed. If slain in animal form, the figurines simply reverts to statuettes that can be used again at a later time. These figurines come in pairs. They become normal adult male lions (see page 274 of the Monster Manual). If slain in combat, the lions cannot be brought back from statuette form for one full week. Otherwise, they can be used once per day for up to 1 hour. They enlarge and shrink upon speaking the command word. Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Ivory Goats)

- **COST:** 21000
- **WT:** 0
- **SPROP:** These figurines of wondrous power appears to be a set of three miniature statuettes of goats an inch or so high. When any figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. Each goat of this trio looks slightly different from the others, and each has a different function: The Goat of Traveling: This statuette provides a speedy and enduring mount equal to that of a heavy horse (see page 273 of the Monster Manual) in every way except appearance. The goat can travel for a maximum of one day each week-continuously or in any combination of periods totaling 24 hours. At this point, or when the command word is uttered, it returns to its statuette form for not less than one day before it can again be used. The Goat of Travail: This statuette becomes an enormous creature, larger than a bull, with the statistics of a nightmare (see page 194 of the Monster Manual) except for the addition of a pair of wicked horns of exceptional size (damage 1d8+4 for each horn). If it is charging to attack, it may only use its horns (but add 6 points of damage to each successful attack in that round). It can be called to life just once per month for up to 12 hours at a time. The Goat of Terror: When called upon with the proper command word, this statuette becomes a destrierlike mount, with the statistics of a light warhorse (see page 274 of the Monster Manual). However, its rider can employ the goat's horns as weapons (one horn as a +3 heavy lance, the other as a +5 longsword). When ridden in an attack against an opponent, the goat of terror radiates fear as the spell in a 30-foot radius (Will DC 16 partial). It can be used once every two weeks for up to 3 hours per use. Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Marble Elephant)

- **COST:** 17000
- **WT:** 0
- **SPROP:** This figurine of wondrous power appears to be a miniature statuette of an elephat, about the size of a human hand. When the figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. Upon utterance of the command word, a marble elephant grows to the size and specifications of a true elephant (see page 272 of the Monster Manual). The animal created from the statuette is fully obedient to the figurine's owner, serving as a beast of burden, a mount, or a combatant. The statuette can be used four times per month for up to 24 hours at a time. Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Obsidian Steed)

- **COST:** 28500
- **WT:** 0
- **SPROP:** This figurine of wondrous power appears to be a miniature statuette of a small, shapeless lump of black stone an inch or so high. Only careful inspection reveals that is vaguely resembles some form of quaduped. When the figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. On command, the near-formless piece of obsidian becomes a fantastic mount. Treat it as a heavy warhorse (see page 273 of the Monster Manual) with the following additional powers usable once per round at will: overland flight, plane shift, and ethereal jaunt. The steed allows itself to be ridden, but if the rider is of good alignment, the steed is 10%% likely per use to carry him to the lower planes and then return to its statuette form. The statuette can be used once per week for one continuous period of up to 24 hours. Note that when an obsidian steed becomes ethereal or plane shifts, its rider and his gear follow suit. Thus, the user can travel to other planes via this means. Strong conjuration and transmutation; CL 15th

### Figurine of Wondrous Power (Onyx Dog)

- **COST:** 15500
- **WT:** 0
- **SPROP:** This figurine of wondrous power appears to be a miniature statuette of a dog an inch or so high. When the figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. When commanded, this statuette changes into a creature with the same properties as a riding dog (see page 272 of the Monster Manual), except that it is endowed with an Intelligence of 8, can communicate in Common, and has exceptional olfactory and visual abilities. (It has the scent ability and adds +4 to its Spot and Search checks.) It has 60-foot darkvision, and it can see invisibility. An onyx dog can be used once per week for up to 6 hours. It obeys only its owner. Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Serpentine Owl)

- **COST:** 9100
- **WT:** 0
- **SPROP:** This figurine of wondrous power appears to be a miniature statuette of an owl an inch or so high. When the figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. This figurine becomes either a normal-sized horned owl or a giant owl (see page 277 or 205 of the Monster Manual, respectively), according to the command word used. The transformation can take place once per day, with a maximum duration of 8 continuous hours. However, after three transformations into giant owl form, the statuette loses all its magical properties. The owl communicates with its owner by telepathic means, informing her of all it sees and hears. (Remember the limitations of its Intelligence.) Moderate transmutation; CL 11th

### Figurine of Wondrous Power (Silver Raven)

- **COST:** 3800
- **WT:** 0
- **SPROP:** This figurine of wondrous power appears to be a miniature silver statuette of a raven an inch or so high. When the figurine is tossed down and the correct command word spoken, it becomes a living creature of normal size. The creature obeys and serves its owner. The creature understands Common but does not speak. If the figurine is broken or destroyed in its statuette form, it is forever ruined. All magic is lost, its power departed. If slain in animal form, the figurine simply reverts to a statuette that can be used again at a later time. This silver figurine turns into a raven on command (but it retains its metallic consistency, which gives it hardness 10). Another command sends it off into the air, bearing a message just like a creature affected by an animal messenger spell (PH p.198) You can mentally impress on the animal a certain place well known to you or an obvious landmark. The directions must be simple, because the animal depends on your knowledge and can't find a destination on its own. You can attach some small item or note to the messenger. The animal then goes to the designated location and waits there until the duration of the spell expires. During this period of waiting, the messenger allows others to approach it and remove any scroll or token it carries. If not commanded to carry a message, the raven obeys the commands of its owner, although it has no special powers or telepathic abilities. It can maintain its nonfigurine status for only 24 hours per week, but the duration need not be continuous. Faint enchantment and transmutation; CL 6th

### Gauntlets of Ogre Power

- **COST:** 4000
- **WT:** 4
- **SLOTS:** 2
- **BONUS:** STAT|STR|2|TYPE=Enhancement
- **SPROP:** These gauntlets are made of tough leather with iron studs running across the back of the hands and fingers. They grant the wearer great strength, adding a +2 enhancement bonus to his Strength score. Both gauntlets must be worn for the magic to be effective. Faint transmutation; CL 6th

### Gauntlet of Rust

- **COST:** 11500
- **WT:** 2
- **SLOTS:** 1
- **SPROP:** This single metal gauntlet looks rusted and pitted but is actually quite powerful. Once per day, it can affect an object as with the rusting grasp spell. It also completely protects the wearer and her gear from rust (magical or otherwise), including the attack of a rust monster. Moderate transmutation; CL 7th

### Gem of Brightness

- **COST:** 13000
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **QUALITY:** Bright Illumination|30 ft.
- **QUALITY:** Shadowy Illumination|60 ft.
- **QUALITY:** Duration|On command
- **SPROP:** This crystal appears to be a long, rough prism. Upon utterance of a command word, the crystal emits bright light of one of three sorts. . One command word causes the gem to shed light as a hooded lantern. This use of the gem does not expend any charges. . Another command word causes the gem of brightness to send out a bright ray 1 foot in diameter and 50 feet long. This strikes as a ranged touch attack, and any creature struck by this beam is blinded for 1d4 rounds unless it makes a DC 14 Fortitude save. This use of the gem expends 1 charge. . The third command word causes the gem to flare in a blinding flash of light that fills a 30-foot cone. Although this glare lasts but a moment, any creature within the cone must make a DC 14 Fortitude save or be blinded for 1d4 rounds. This use expends 5 charges. A newly created gem of brightness has 50 charges. When all its charges are expended, the gem becomes nonmagical. Faint evocation; CL 6th

### Gem of Seeing

- **COST:** 75000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=10|True Seeing
- **SPROP:** This finely cut and polished stone is indistinguishable from an ordinary jewel in appearance. When it is gazed through, a gem of seeing enables the user to see as though she were affected by the true seeing spell (See all things as they truly are, 120' range, PH 296). A gem of seeing can be used for as much as 30 minutes a day, divided up into periods of minutes or rounds as the user sees fit. Moderate divination; CL 10th

### Gloves of Arrow Snaring

- **COST:** 4000
- **WT:** 0
- **SLOTS:** 2
- **ABILITY:** FEAT|VIRTUAL|Snatch Arrows
- **SPROP:** Once snugly worn, these gloves seem to meld with the hands, becoming almost invisible. Twice per day, the wearer can act as if he had the Snatch Arrows feat, even if he does not meet the prerequisites for it. Both gloves must be worn for the magic to be effective. At least one hand must be free to take advantage of the magic. Faint abjuration; CL 3rd

### Gloves of Dexterity +2

- **COST:** 4000
- **WT:** 0
- **SLOTS:** 2
- **BONUS:** STAT|DEX|2|TYPE=Enhancement
- **SPROP:** Dexterity: These thin leather gloves are very flexible and allow for delicate manipulation. They add to the wearer's Dexterity score in the form of an enhancement bonus of +2. Both gloves must be worn for the magic to be effective. Moderate transmutation; CL 8th
- **SORTKEY:** Gloves of Dexterity +02

### Gloves of Dexterity +4

- **COST:** 16000
- **WT:** 0
- **SLOTS:** 2
- **BONUS:** STAT|DEX|4|TYPE=Enhancement
- **SPROP:** Dexterity: These thin leather gloves are very flexible and allow for delicate manipulation. They add to the wearer's Dexterity score in the form of an enhancement bonus of +4. Both gloves must be worn for the magic to be effective. Moderate transmutation; CL 8th
- **SORTKEY:** Gloves of Dexterity +04

### Gloves of Dexterity +6

- **COST:** 36000
- **WT:** 0
- **SLOTS:** 2
- **BONUS:** STAT|DEX|6|TYPE=Enhancement
- **SPROP:** Dexterity: These thin leather gloves are very flexible and allow for delicate manipulation. They add to the wearer's Dexterity score in the form of an enhancement bonus of +6. Both gloves must be worn for the magic to be effective. Moderate transmutation; CL 8th
- **SORTKEY:** Gloves of Dexterity +06

### Glove of Storing

- **CONTAINS:** *20|Any=1
- **COST:** 10000
- **WT:** 0
- **SLOTS:** 1
- **SPROP:** This device is a simple leather glove. On command, one item held in the hand wearing the glove disappears. The item can weigh no more than 20 pounds and must be able to be held in one hand. While stored, the item has negligible weight. With a snap of the fingers wearing the glove, the item reappears. A glove can only store one item at a time. Storing or retrieving the item is a free action. The item is held in stasis and shrunk down so small within the palm of the glove that it cannot be seen. Many owners of a glove of storing find it to be a useful and dramatic way to store weapons, wands, and-because the item is stored in stasis-even lit torches. Spell durations are not suppressed, but continue to expire. If an effect is suppressed or dispelled, the stored item appears instantly. Faint transmutation; CL 6th

### Gloves of Swimming and Climbing

- **COST:** 6250
- **WT:** 0
- **SLOTS:** 2
- **BONUS:** SKILL|Climb,Swim|5|TYPE=Competence
- **SPROP:** These apparently normal lightweight gloves grant a +5 competence bonus on Swim checks and Climb checks. Both gloves must be worn for the magic to be effective. Faint transmutation; CL 5th

### Goggles of Minute Seeing

- **COST:** 1250
- **WT:** 0
- **SPROP:** The lenses of this item are made of special crystal. When placed over the eyes of the wearer, the lenses enable her to see much better than normal at distances of 1 foot or less, granting her a +5 competence bonus on Search checks to find secret doors, traps, and similar concealed objects. Both lenses must be worn for the magic to be effective. Faint divination; CL 3rd

### Goggles of Night

- **COST:** 12000
- **WT:** 0
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **SPROP:** The lenses of this item are made of dark crystal. Even though the lenses are opaque, when placed over the eyes of the wearer they enable him to see normally and also grant him 60-foot darkvision. Both lenses must be worn for the magic to be effective. Faint transmutation; CL 3rd

### Golem Manual (Clay)

- **COST:** 12000
- **WT:** 5
- **SPROP:** A golem manual contains information, incantations and magical power that help a character to craft a golem (see page 134 of the Monster Manual). The instructions therein grant a +5 competence bonus on skill checks made to craft the golem's body. Each manual also holds the prerequisite spells needed for a specific golem, effectively grants the builder use of the Craft Construct feat (see page 303 of the Monster Manual) during the construction of the golem, and grants the character an increase to her caster level for the purpose of crafting a golem. Any golem built using a golem manual does not cost the creator any XP, since the requisite XP are "contained" in the book and "expended" by the book during the creation process. The spells included in a golem manual require a spell trigger activation and can be activated only to assist in the construction of a golem. The cost of the book does not include the cost of constructing the golem's body. Once the golem is finished, the writing in the manual fades and the book is consumed in flames. When the book's ashes are sprinkled upon the golem, it becomes fully animated. The book contains animate objects, bless, commune, prayer, and resurrection. The reader may treat her caster level as two levels higher than normal for the purpose of crafting a clay golem. The book supplies 1,540 XP for the creation of a clay golem. Moderate conjuration, divination, enchantment, and transmutation; CL 11th

### Golem Manual (Flesh)

- **COST:** 8000
- **WT:** 5
- **SPROP:** A golem manual contains information, incantations and magical power that help a character to craft a golem (see page 134 of the Monster Manual). The instructions therein grant a +5 competence bonus on skill checks made to craft the golem's body. Each manual also holds the prerequisite spells needed for a specific golem, effectively grants the builder use of the Craft Construct feat (see page 303 of the Monster Manual) during the construction of the golem, and grants the character an increase to her caster level for the purpose of crafting a golem. Any golem built using a golem manual does not cost the creator any XP, since the requisite XP are "contained" in the book and "expended" by the book during the creation process. The spells included in a golem manual require a spell trigger activation and can be activated only to assist in the construction of a golem. The cost of the book does not include the cost of constructing the golem's body. Once the golem is finished, the writing in the manual fades and the book is consumed in flames. When the book's ashes are sprinkled upon the golem, it becomes fully animated. The book contains animate dead, bull's strength, geas/quest, and limited wish. The reader may treat her caster level as one level higher than normal for the purpose of crafting a flesh golem. The book supplies 780 XP for the creation of a flesh golem. Moderate enchantment, necromancy [evil], and transmutation; CL 8th

### Golem Manual (Iron)

- **COST:** 35000
- **WT:** 5
- **SPROP:** A golem manual contains information, incantations and magical power that help a character to craft a golem (see page 134 of the Monster Manual). The instructions therein grant a +5 competence bonus on skill checks made to craft the golem's body. Each manual also holds the prerequisite spells needed for a specific golem, effectively grants the builder use of the Craft Construct feat (see page 303 of the Monster Manual) during the construction of the golem, and grants the character an increase to her caster level for the purpose of crafting a golem. Any golem built using a golem manual does not cost the creator any XP, since the requisite XP are "contained" in the book and "expended" by the book during the creation process. The spells included in a golem manual require a spell trigger activation and can be activated only to assist in the construction of a golem. The cost of the book does not include the cost of constructing the golem's body. Once the golem is finished, the writing in the manual fades and the book is consumed in flames. When the book's ashes are sprinkled upon the golem, it becomes fully animated. The book contains cloudkill, geas/quest, limited wish, and polymorph any object. The reader may treat her caster level as four levels higher than normal for the purpose of crafting a iron golem. The book supplies 5,600 XP for the creation of a iron golem. Strong conjuration, enchantment and transmutation; CL 16th

### Golem Manual (Stone)

- **COST:** 22000
- **WT:** 5
- **SPROP:** A golem manual contains information, incantations and magical power that help a character to craft a golem (see page 134 of the Monster Manual). The instructions therein grant a +5 competence bonus on skill checks made to craft the golem's body. Each manual also holds the prerequisite spells needed for a specific golem, effectively grants the builder use of the Craft Construct feat (see page 303 of the Monster Manual) during the construction of the golem, and grants the character an increase to her caster level for the purpose of crafting a golem. Any golem built using a golem manual does not cost the creator any XP, since the requisite XP are "contained" in the book and "expended" by the book during the creation process. The spells included in a golem manual require a spell trigger activation and can be activated only to assist in the construction of a golem. The cost of the book does not include the cost of constructing the golem's body. Once the golem is finished, the writing in the manual fades and the book is consumed in flames. When the book's ashes are sprinkled upon the golem, it becomes fully animated. The book contains geas/quest, limited wish, polymorph any object, and slow. The reader may treat her caster level as three levels higher than normal for the purpose of crafting a stone golem. The book supplies 3,400 XP for the creation of a stone golem. Strong abjuration and enchantment; CL 14th

### Golem Manual (Greater Stone)

- **COST:** 44000
- **WT:** 5
- **SPROP:** A golem manual contains information, incantations and magical power that help a character to craft a golem (see page 134 of the Monster Manual). The instructions therein grant a +5 competence bonus on skill checks made to craft the golem's body. Each manual also holds the prerequisite spells needed for a specific golem, effectively grants the builder use of the Craft Construct feat (see page 303 of the Monster Manual) during the construction of the golem, and grants the character an increase to her caster level for the purpose of crafting a golem. Any golem built using a golem manual does not cost the creator any XP, since the requisite XP are "contained" in the book and "expended" by the book during the creation process. The spells included in a golem manual require a spell trigger activation and can be activated only to assist in the construction of a golem. The cost of the book does not include the cost of constructing the golem's body. Once the golem is finished, the writing in the manual fades and the book is consumed in flames. When the book's ashes are sprinkled upon the golem, it becomes fully animated. The book contains geas/quest, limited wish, polymorph any object, and slow. The reader may treat her caster level as three levels higher than normal for the purpose of crafting a stone golem. The book supplies 7,640 XP for the creation of a greater stone golem. Strong abjuration and enchantment; CL 16th

### Hand of Glory

- **COST:** 8000
- **WT:** 2
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=5|Daylight,13|See Invisibility,13
- **BONUS:** SLOTS|RING|1
- **SPROP:** This mummified human hand hangs by a leather cord around a character's neck (taking up space as a magic necklace would). If a magic ring is placed on one of the fingers of the hand, the wearer benefits from the ring as if wearing it herself, and it does not count against her two-ring limit. The hand can wear only one ring at a time. Even without a ring, the hand itself allows its wearer to use daylight and see invisibility each once per day. Faint varied; CL 5th;

### Hand of the Mage

- **COST:** 900
- **WT:** 2
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=2|Mage Hand,10
- **SPROP:** This mummified elf hand hangs by a golden chain around a character's neck (taking up space as a magic necklace would). It allows the wearer to utilize the spell mage hand at will (5lb item with 30', move 15'/rnd). Faint transmutation; CL 2nd

### Harp of Charming

- **COST:** 7500
- **WT:** 5
- **SPROP:** This instrument is a golden, intricately carved harp. When played, it enables the performer to work one suggestion (as the spell, Will DC 14 negates) into the music for each 10 minutes of playing if he can succeed on a DC 14 Perform (string instruments) check. If the check fails, the audience cannot be affected by any further performances from the harpist for 24 hours. Faint enchantment; CL 5th

### Hat of Disguise

- **COST:** 1800
- **WT:** 0
- **BONUS:** SKILL|Disguise|10
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=3|Disguise Self
- **SPROP:** This apparently normal hat allows its wearer to alter her appearance as with a disguise self spell (PH p222) (make yourself and equipment look different - 1 foot shorter or taller, thinner or fatter). As part of the disguise, the hat can be changed to appear as a comb, ribbon, headband, cap, coif, hood, helmet, and so on. Faint illusion; CL 1st

### Headband of Intellect +2

- **COST:** 4000
- **WT:** 0
- **BONUS:** SKILLPOINTS|NUMBER|-1
- **BONUS:** STAT|INT|2|TYPE=Enhancement
- **SPROP:** This headband is a light cord with a small gem set so that it rests upon the forehead of the wearer. The headband provides a +2 enhancement bonus to Intelligence. Moderate transmutation; CL 8th
- **SORTKEY:** Headband of Intellect +02

### Headband of Intellect +4

- **COST:** 16000
- **WT:** 0
- **BONUS:** SKILLPOINTS|NUMBER|-2
- **BONUS:** STAT|INT|4|TYPE=Enhancement
- **SPROP:** This device is a light cord with a small gem set so that it rests upon the forehead of the wearer. The headband adds to the wearer's Intelligence score in the form of an enhancement bonus of +4. This enhancement bonus does not earn the wearer extra skill points when a new level is attained; use the unenhanced Intelligence bonus to determine skill points. Moderate transmutation; CL 8th
- **SORTKEY:** Headband of Intellect +04

### Headband of Intellect +6

- **COST:** 36000
- **WT:** 0
- **BONUS:** SKILLPOINTS|NUMBER|-3
- **BONUS:** STAT|INT|6|TYPE=Enhancement
- **SPROP:** This device is a light cord with a small gem set so that it rests upon the forehead of the wearer. The headband adds to the wearer's Intelligence score in the form of an enhancement bonus of +6. This enhancement bonus does not earn the wearer extra skill points when a new level is attained; use the unenhanced Intelligence bonus to determine skill points. Moderate transmutation; CL 8th
- **SORTKEY:** Headband of Intellect +06

### Helm of Brilliance

- **COST:** 125000
- **WT:** 3
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)
- **BONUS:** VAR|FireResistanceBonusSp|30|TYPE=Base
- **SPROP:** This normal-looking helm takes its true form and manifests its powers when the user dons it and speaks the command word. Made of brilliant silver and polished steel, a newly created helm is set with large magic gems: ten diamonds, twenty rubies, thirty fire opals, and forty opals. When struck by bright light, the helm scintillates and sends forth reflective rays in all directions from its crownlike, gem-tipped spikes. The jewels' functions are as follows: . Diamond: Prismatic spray (save DC 20) . Ruby: Wall of fire . Fire opal: Fireball (10d6, Reflex DC 20 half ) . Opal: Daylight The helm may be used once per round, but each gem can perform its spell-like power just once. Until all its jewels are depleted, a helm of brilliance also has the following magical properties when activated. . It emanates a bluish light when undead are within 30 feet. This light causes 1d6 points of damage per round to all such creatures within that range. . The wearer may command any weapon he wields to become a flaming weapon (see page 224). This is in addition to whatever abilities the weapon may already have (unless the weapon already is a flaming weapon). The command takes 1 round to take effect. . The helm provides resistance to fire 30. This protection does not stack with similar protection from other sources, such as resist energy. Once all its jewels have lost their magic, the helm loses its powers and the gems turn to worthless powder. Removing a jewel destroys it. If a creature wearing the helm is damaged by magical fire (after the fire protection is taken into account) and fails an additional DC 15 Will save, the remaining gems on the helm overload and detonate. Remaining diamonds become prismatic sprays that each randomly target a creature within range (possibly the wearer), rubies become straight-line walls of fire extending outward in a random direction from the helm wearer, and fire opals become fireballs centered on the helm wearer. The opals and the helm itself are destroyed. Strong varied; CL 13th

### Helm of Comprehend Languages and Read Magic

- **COST:** 5200
- **WT:** 3
- **SPROP:** Appearing as a normal helmet, a helm of comprehend languages and read magic grants its wearer the ability to understand the spoken words of any creature and to read text in any language and any magical writing. The wearer gains a +5 competence bonus on Decipher Script checks to understand messages written in incomplete, archaic, or exotic forms. Note that understanding a magical text does not necessarily imply spell use. Faint divination; CL 4th

### Helm of Telepathy

- **COST:** 27000
- **WT:** 3
- **SPROP:** The wearer can use detect thoughts at will. Furthermore, he can send a telepathic message to anyone whose surface thoughts he is reading (allowing two-way communication). Once per day, the wearer of the helm can implant a suggestion (as the spell, Will DC 14 negates) along with his telepathic message. Faint divination and enchantment; CL 5th

### Helm of Teleportation

- **COST:** 73500
- **WT:** 3
- **SPROP:** A character wearing this device may teleport three times per day, exactly as if he had cast the spell of the same name. Moderate conjuration; CL 9th

### Helm of Underwater Action

- **COST:** 57000
- **WT:** 3
- **SPROP:** The wearer of this helmet can see underwater. Drawing the small lenses in compartments on either side into position before the wearer's eyes activates the visual properties of the helm, allowing her to see five times farther than water and light conditions would allow for normal human vision. (Weeds, obstructions, and the like block vision in the usual manner.) If the command word is spoken, the helm of underwater action creates a globe of air around the wearer's head and maintains it until the command word is spoken again, enabling her to breathe freely. Faint transmutation; CL 5th

### Heward's Handy Haversack

- **CONTAINS:** *120
- **COST:** 2000
- **WT:** 5
- **SPROP:** A backpack of this sort appears to be well made, well used, and quite ordinary. It is constructed of finely tanned leather, and the straps have brass hardware and buckles. It has two side pouches, each of which appears large enough to hold about a quart of material. In fact, each is like a bag of holding and can actually hold material of as much as 2 cubic feet in volume or 20 pounds in weight. The large central portion of the pack can contain up to 8 cubic feet or 80 pounds of material. Even when so filled, the backpack always weighs only 5 pounds. While such storage is useful enough, the pack has an even greater power in addition. When the wearer reaches into it for a specific item, that item is always on top. Thus, no digging around and fumbling is ever necessary to find what a haversack contains. Retrieving any specific item from a haversack is a move action, but it does not provoke the attacks of opportunity that retrieving a stored item usually does. Moderate conjuration; CL 9th

### Horn of Blasting

- **COST:** 20000
- **WT:** 1
- **SPROP:** This horn appears to be a normal trumpet. It can be sounded as a normal horn, but if the command word is spoken and the instrument is then played, it deals 5d6 points of sonic damage to creatures within a 40-foot cone and causes them to be deafened for 2d6 rounds (a DC 16 Fortitude save reduces the damage by half and negates the deafening). Crystalline objects and creatures take 7d6 points of sonic damage, with no save unless they're held, worn, or carried by creatures (Will DC 16 negates). If a horn of blasting is used magically more than once in a given day, there is a 20%% cumulative chance with each extra use that it explodes and deals 10d6 points of damage to the person sounding it. Moderate evocation; CL 7th

### Horn of Blasting (Greater)

- **COST:** 70000
- **WT:** 1
- **SPROP:** This horn functions as a horn of blasting, except that it deals 10d6 points of sonic damage, stuns creatures for 1 round, and deafens them for 4d6 rounds (a DC 19 Fortitude reduces the damage by half and negates the stunning and deafening). Crystalline objects take 16d6 points of sonic damage as described for the horn of blasting. A greater horn of blasting also has a 20%% cumulative chance of exploding. Strong evocation; CL 16th

### Horn of Fog

- **COST:** 2000
- **WT:** 1
- **SPROP:** This small bugle allows its possessor to blow forth a thick cloud of heavy fog similar to that of an obscuring mist spell. The fog covers a 10-foot square next to the horn blower each round that the user continues to blow the horn; fog clouds travel 10 feet each round in a straight line from the emanation point unless blocked by something substantial such as a wall. The device makes a deep, foghornlike noise, with the note dropping abruptly to a lower register at the end of each blast. The fog dissipates after 3 minutes. A moderate wind (11+ mph) disperses the fog in 4 rounds; a strong wind (21+ mph) disperses the fog in 1 round. Faint conjuration; CL 3rd

### Horn of Goodness/Evil

- **COST:** 6500
- **WT:** 1
- **SPROP:** This trumpet adapts itself to its owner, so it produces either a good or an evil effect depending on the owner's alignment. If the owner is neither good nor evil, the horn has no power whatsoever. If he is good, then blowing the horn has the effect of a magic circle against evil. If he is evil, then blowing the horn has the effect of a magic circle against good. In either case, this ward lasts for 1 hour. The horn can be blown once per day. Faint abjuration; CL 6th

### Horn of the Tritons

- **COST:** 15100
- **WT:** 2
- **SPROP:** This device is a conch shell that can be blown once per day except by a triton (see page 245 of the Monster Manual), which can sound it three times per day. A horn of the tritons can perform any one of the following functions when blown. . Calm rough waters in a 1-mile radius. This effect dispels a summoned water elemental if it fails a DC 16 Will save. . Attract 5d4 Large sharks (01-30 on d%%), 5d6 Medium sharks (31-80), or 1d10 sea lions (81-100) if the character is in a body of water in which such creatures dwell. The creatures are friendly and obey, to the best of their ability, the one who sounded the horn. . Causes aquatic creatures with Intelligence scores of 1 or 2 within 500 feet to become panicked as if they had been targeted by a fear spell (Will DC 16 partial). Those who successfully save are shaken for 3d6 rounds. Any sounding of a horn of the tritons can be heard by all tritons within a 3-mile radius. Moderate conjuration and transmutation; CL 8th

### Horn of Valhalla (Brass)

- **COST:** 50000
- **WT:** 2
- **SPROP:** This magic instrument comes in four varieties. Each appears to be normal until someone speaks its command word and blows the horn. Then the horn summons a number of human barbarians to fight for the character who summoned them. Each horn can be blown just once every seven days. Any character who uses a horn of Valhalla but doesn't have the prerequisite is attacked by the barbarians she herself summoned. Summoned barbarians are constructs, not actual people (though they seem to be); they arrive with the starting equipment for barbarians given on page 26 of the Player's Handbook. They attack anyone the possessor of the horn commands them to fight until they or their opponents are slain or until 1 hour has elapsed, whichever comes first. Strong conjuration; CL 13th. Type: Brass, Barbarians Summoned: 2d4+1, 3rd level, Prerequisite: Spellcaster level 1st.

### Horn of Valhalla (Bronze)

- **COST:** 50000
- **WT:** 2
- **SPROP:** This magic instrument comes in four varieties. Each appears to be normal until someone speaks its command word and blows the horn. Then the horn summons a number of human barbarians to fight for the character who summoned them. Each horn can be blown just once every seven days. Any character who uses a horn of Valhalla but doesn't have the prerequisite is attacked by the barbarians she herself summoned. Summoned barbarians are constructs, not actual people (though they seem to be); they arrive with the starting equipment for barbarians given on page 26 of the Player's Handbook. They attack anyone the possessor of the horn commands them to fight until they or their opponents are slain or until 1 hour has elapsed, whichever comes first. Strong conjuration; CL 13th. Type: Bronze, Barbarians Summoned: 2d4, 4th level , Prerequisite:Proficiency with all martial weapons or bardic music ability.

### Horn of Valhalla (Iron)

- **COST:** 50000
- **WT:** 2
- **SPROP:** This magic instrument comes in four varieties. Each appears to be normal until someone speaks its command word and blows the horn. Then the horn summons a number of human barbarians to fight for the character who summoned them. Each horn can be blown just once every seven days. Any character who uses a horn of Valhalla but doesn't have the prerequisite is attacked by the barbarians she herself summoned. Summoned barbarians are constructs, not actual people (though they seem to be); they arrive with the starting equipment for barbarians given on page 26 of the Player's Handbook. They attack anyone the possessor of the horn commands them to fight until they or their opponents are slain or until 1 hour has elapsed, whichever comes first. Strong conjuration; CL 13th. Type: Iron 1d4+1, Barbarians Summoned: 5th level , Prerequisite:Proficiency with all martial weapons or bardic music ability.

### Horn of Valhalla (Silver)

- **COST:** 50000
- **WT:** 2
- **SPROP:** This magic instrument comes in four varieties. Each appears to be normal until someone speaks its command word and blows the horn. Then the horn summons a number of human barbarians to fight for the character who summoned them. Each horn can be blown just once every seven days. Any character who uses a horn of Valhalla but doesn't have the prerequisite is attacked by the barbarians she herself summoned. Summoned barbarians are constructs, not actual people (though they seem to be); they arrive with the starting equipment for barbarians given on page 26 of the Player's Handbook. They attack anyone the possessor of the horn commands them to fight until they or their opponents are slain or until 1 hour has elapsed, whichever comes first. Strong conjuration; CL 13th. Type: Silver, Barbarians Summoned: 2d4+2, 2nd level, Prerequisite: None.

### Horseshoes of Speed

- **COST:** 3000
- **WT:** 12
- **SLOTS:** 4
- **BONUS:** MOVEADD|TYPE.Walk|30|TYPE=Enhancement
- **SPROP:** These iron shoes come in sets of four like ordinary horseshoes. When affixed to an animal's hooves, they increase the animal's base land speed by 30 feet; this counts as an enhancement bonus. As with other effects that increase speed, jumping distances increase proportionally. All four shoes must be worn by the same animal for the magic to be effective. Faint transmutation; CL 3rd

### Horseshoes of a Zephyr

- **COST:** 6000
- **WT:** 4
- **SLOTS:** 4
- **SPROP:** These four iron shoes are affixed like normal horseshoes. They allow a horse to travel without actually touching the ground. The horse must still run above (always around 4 inches above) a roughly horizontal surface. This means that nonsolid or unstable surfaces, such as water or lava, can be crossed, and that movement is possible without leaving tracks on any sort of ground. The horse moves at its normal base land speed. All four shoes must be worn by the same animal for the magic to be effective. Faint transmutation; CL 3rd

### Incense of Meditation

- **COST:** 4900
- **WT:** 1
- **SPROP:** This small rectangular block of sweetsmelling incense is visually indistinguishable from nonmagical incense until lit. When it is burning, the special fragrance and pearly-hued smoke of this special incense are recognizable by anyone making a DC 15 Spellcraft check. When a divine spellcaster lights a block of incense of meditation and then spends 8 hours praying and meditating nearby, the incense enables him to prepare all his spells as though affected by the Maximize Spell feat. However, all the spells prepared in this way are at their normal level, not at three levels higher (as with the regular metamagic feat). Each block of incense burns for 8 hours, and the effects persist for 24 hours. Moderate enchantment; CL 7th

### Ioun Stone (Dull Gray)

- **COST:** 25
- **WT:** 0
- **SPROP:** Burnt-out stone
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Clear)

- **COST:** 4000
- **WT:** 0
- **SPROP:** Sustains creature without food or water
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Dusty Rose)

- **COST:** 5000
- **WT:** 0
- **BONUS:** COMBAT|AC|1|TYPE=Insight
- **SPROP:** +1 insight bonus to AC
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Deep Red)

- **COST:** 8000
- **WT:** 0
- **BONUS:** STAT|DEX|2|TYPE=Enhancement
- **SPROP:** +2 enhancement bonus to Dexterity
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Incandescent Blue)

- **COST:** 8000
- **WT:** 0
- **BONUS:** STAT|WIS|2|TYPE=Enhancement
- **SPROP:** +2 enhancement bonus to Wisdom
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Pale Blue)

- **COST:** 8000
- **WT:** 0
- **BONUS:** STAT|STR|2|TYPE=Enhancement
- **SPROP:** +2 enhancement bonus to Strength
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Pink)

- **COST:** 8000
- **WT:** 0
- **BONUS:** STAT|CON|2|TYPE=Enhancement
- **SPROP:** +2 enhancement bonus to Constitution
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Pink and Green)

- **COST:** 8000
- **WT:** 0
- **BONUS:** STAT|CHA|2|TYPE=Enhancement
- **SPROP:** +2 enhancement bonus to Charisma
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Scarlet and Blue)

- **COST:** 8000
- **WT:** 0
- **BONUS:** STAT|INT|2|TYPE=Enhancement
- **SPROP:** +2 enhancement bonus to Intelligence
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Dark Blue)

- **COST:** 10000
- **WT:** 0
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **SPROP:** Alertness (as the feat)
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Vibrant Purple)

- **COST:** 36000
- **WT:** 0
- **SPROP:** Stores three levels of spells, as a Ring of Spell Storing. Stored spells must be placed by a spellcaster but can be used by anyone (see ring of minor spell storing, page 233).
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Iridescent)

- **COST:** 18000
- **WT:** 0
- **SPROP:** Sustains creature without air
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Pale Lavender)

- **COST:** 20000
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_20|CHARGES[20]
- **SPROP:** Absorbs spells of 4th level or lower (20 levels, requires readied action). The works like a rod of absorption, but absorbing a spell requires a readied action, and these stones cannot be used to empower spells.
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Pearly White)

- **COST:** 20000
- **WT:** 0
- **SPROP:** Regenerate 1 point of damage per hour. Regeneration only cures damage taken while the character is using the stone.
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Pale Green)

- **COST:** 30000
- **WT:** 0
- **BONUS:** COMBAT|TOHIT|1|TYPE=Competence
- **BONUS:** SKILL|TYPE.Strength,TYPE.Dexterity,TYPE.Constitution,TYPE.Intelligence,TYPE.Wisdom,TYPE.Charisma|1|TYPE=Competence
- **BONUS:** VAR|TurnCheckBase|1|TYPE=Competence
- **BONUS:** SAVE|Fortitude,Reflex,Will|1|TYPE=Competence
- **SPROP:** +1 Competence bonus on attack rolls, saves, skill checks, and ability checks
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Orange)

- **COST:** 30000
- **WT:** 0
- **BONUS:** VAR|Caster_Level_Bonus|1
- **DEFINE:** Caster_Level_Bonus|0
- **SPROP:** +1 caster level
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Ioun Stone (Lavender and Green)

- **COST:** 40000
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Absorbs spells of 8th level or lower (up to 50 levels before becoming dull grey and useless, requires readied action). This works like a rod of absorption, but absorbing a spell requires a readied action, and these stones cannot be used to empower spells.
- **SPROP:** These crystalline stones always float in the air and must be within 3 feet of their owner to be of any use. When a character first acquires a stone, she must hold it and then release it, whereupon it takes up a circling orbit 1d3 feet from her head. Thereafter, a stone must be grasped or netted to separate it from its owner. The owner may voluntarily seize and stow a stone (to keep it safe while she is sleeping, for example), but she loses the benefits of the stone during that time. Ioun stones have AC 24, 10 hit points, and hardness 5. Moderate varied; CL 12th

### Iron Bands of Binding

- **COST:** 26000
- **WT:** 1
- **SPROP:** When initially discovered, this very potent item appears to be a 3-inch-diameter rusty iron sphere with bandings on the globe. When the proper command word is spoken and the spherical iron device is hurled at an opponent, the bands expand and then contract to bind the target creature on a successful ranged touch attack. A single Large or smaller creature can be captured thus and held immobile until the command word is spoken to bring the bands into spherical form again. The creature can break (and ruin) the bands with a DC 30 Strength check or escape them with a DC 30 Escape Artist check. Iron bands of Bilarro are usable once per day. Strong evocation; CL 13th

### Iron Flask

- **COST:** 170000
- **WT:** 1
- **SPROP:** These special containers are typically inlaid with runes of silver and stoppered by a brass plug bearing a seal engraved with sigils, glyphs, and special symbols. When the user speaks the command word, he can force any creature from another plane into the container, provided that creature fails a DC 19 Will save. The range of this effect is 60 feet. Only one creature at a time can be so contained. Loosing the stopper frees the captured creature. The command word can be given only once per day. If the individual freeing the captured creature speaks the command word, the creature can be forced to serve for 1 hour. If freed without the command word, the creature acts according to its natural inclinations. (It usually attacks the user, unless it perceives a good reason not to.) Any attempt to force the same creature into the flask a second time provides it a +2 bonus on its saving throw and makes it hostile. Strong conjuration; CL 20th

### Keoghtom's Ointment

- **COST:** 4000
- **WT:** 0.5
- **EQMOD:** CHARGED_ITEM_5|CHARGES[5]
- **SPROP:** A jar of this unguent is 3 inches in diameter and 1 inch deep and contains five applications. Placed upon a poisoned wound or swallowed, the ointment detoxifies any poison (as neutralize poison). Applied to a diseased area, it removes disease (as remove disease). Rubbed on a wound, the ointment cures 1d8+5 points of damage (as cure light wounds). Faint conjuration; CL 5th

### Lantern of Revealing

- **CONTAINS:** 1|Liquid=1
- **COST:** 30000
- **WT:** 2
- **QUALITY:** Bright Illumination|30 ft.
- **QUALITY:** Shadowy Illumination|60 ft.
- **QUALITY:** Duration|6 hr./pint
- **SPROP:** This lantern operates as a normal hooded lantern. While it is lit, it also reveals all invisible creatures and objects within 25 feet of it, just like the spell invisibility purge. Faint evocation; CL 5th

### Lens of Detection

- **COST:** 3500
- **WT:** 1
- **BONUS:** SKILL|Search|5
- **SPROP:** This circular prism enables its user to detect minute details, granting a +5 bonus on Search checks. It also aids in following tracks, adding a +5 bonus on Survival checks when tracking. The lens is about 6 inches in diameter and set in a frame with a handle. Moderate divination; CL 9th

### Lyre of Building

- **COST:** 13000
- **WT:** 5
- **SPROP:** If the proper chords are struck, a single use of this lyre negates any attacks made against all inanimate construction (walls, roof, floor, and so on) within 300 feet. This includes the effects of a horn of blasting, a disintegrate spell, or an attack from a ram or similar siege weapon. The lyre can be used in this way once per day, with the protection lasting for 30 minutes. The lyre is also useful with respect to building. Once a week its strings can be strummed so as to produce chords that magically construct buildings, mines, tunnels, ditches, or whatever. The effect produced in but 30 minutes of playing is equal to the work of 100 humans laboring for three days. Each hour after the first, a character playing the lyre must make a DC 18 Perform (string instruments) check. If it fails, she must stop and cannot play the lyre again for this purpose until a week has passed. Faint transmutation; CL 6th

### Mantle of Faith

- **COST:** 76000
- **WT:** 0
- **DR:** 5/Evil
- **SPROP:** This holy garment, worn over normal clothing, grants damage reduction 5/evil to the character wearing it. Strong abjuration [good]; CL 20th

### Mantle of Spell Resistance

- **COST:** 90000
- **WT:** 0
- **SR:** 21
- **SPROP:** This garment, worn over normal clothing or armor, grants the wearer spell resistance 21. Moderate abjuration; CL 9th

### Manual of Bodily Health +1

- **COST:** 27500
- **WT:** 5
- **SPROP:** This thick tome contains tips on health and fitness, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +1 to his Constitution score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Bodily Health +2

- **COST:** 55000
- **WT:** 5
- **SPROP:** This thick tome contains tips on health and fitness, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +2 to his Constitution score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Bodily Health +3

- **COST:** 82500
- **WT:** 5
- **SPROP:** This thick tome contains tips on health and fitness, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +3 to his Constitution score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Bodily Health +4

- **COST:** 110000
- **WT:** 5
- **SPROP:** This thick tome contains tips on health and fitness, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +4 to his Constitution score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Bodily Health +5

- **COST:** 137500
- **WT:** 5
- **SPROP:** This thick tome contains tips on health and fitness, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +5 to his Constitution score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Gainful Exercise +1

- **COST:** 27500
- **WT:** 5
- **SPROP:** This thick tome contains exercise descriptions and diet suggestions, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +1 to her Strength score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Gainful Exercise +2

- **COST:** 55000
- **WT:** 5
- **SPROP:** This thick tome contains exercise descriptions and diet suggestions, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +2 to her Strength score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Gainful Exercise +3

- **COST:** 82500
- **WT:** 5
- **SPROP:** This thick tome contains exercise descriptions and diet suggestions, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +3 to her Strength score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Gainful Exercise +4

- **COST:** 110000
- **WT:** 5
- **SPROP:** This thick tome contains exercise descriptions and diet suggestions, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +4 to her Strength score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Gainful Exercise +5

- **COST:** 137500
- **WT:** 5
- **SPROP:** This thick tome contains exercise descriptions and diet suggestions, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +5 to her Strength score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Quickness of Action +1

- **COST:** 27500
- **WT:** 5
- **SPROP:** This thick tome contains tips on coordination exercises and balance, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +1 to his Dexterity score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Quickness of Action +2

- **COST:** 55000
- **WT:** 5
- **SPROP:** This thick tome contains tips on coordination exercises and balance, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +2 to his Dexterity score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Quickness of Action +3

- **COST:** 82500
- **WT:** 5
- **SPROP:** This thick tome contains tips on coordination exercises and balance, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +3 to his Dexterity score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Quickness of Action +4

- **COST:** 110000
- **WT:** 5
- **SPROP:** This thick tome contains tips on coordination exercises and balance, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +4 to his Dexterity score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Manual of Quickness of Action +5

- **COST:** 137500
- **WT:** 5
- **SPROP:** This thick tome contains tips on coordination exercises and balance, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +5 to his Dexterity score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Mask of the Skull

- **COST:** 22000
- **WT:** 3
- **SPROP:** This ivory mask has been fashioned into the likeness of a human skull. Once per day, after it has been worn for at least 1 hour, the mask can be loosed to fly from the wearer's face. It travels up to 50 feet away from the wearer and attacks a target assigned to it. The grinning skull mask makes a touch attack against the target based on the wearer's base attack bonus. If the attack succeeds, the target must make a DC 20 Fortitude save or be struck dead, as if affected by a finger of death spell. If the target succeeds on his saving throw, he nevertheless takes 3d6+13 points of damage. After attacking (whether successful or not), the mask flies back to its user. The mask has AC 16, 10 hit points, and hardness 6. Strong necromancy and transmutation; CL 13th

### Mattock of the Titans

- **PROFICIENCY:** WEAPON|Morningstar
- **COST:** 23348
- **WT:** 120
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 4d6
- **SIZE:** G
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **SPROP:** This digging tool is 10 feet long. Any creature of at least Huge size can use it to loosen or tumble earth or earthen ramparts (a 10-foot cube every 10 minutes). It also smashes rock (a 10-foot cube per hour). If used as a weapon, it is the equivalent of a Gargantuan +3 adamantine warhammer, dealing 4d6 points of base damage. Strong transmutation; CL 16th

### Maul of the Titans

- **PROFICIENCY:** WEAPON|Greatclub
- **COST:** 25305
- **WT:** 160
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d10
- **SIZE:** L
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **BONUS:** WEAPON|TOHIT|-4
- **BONUS:** WEAPON|TOHIT|4
- **SPROP:** This mallet is 8 feet long. If used as a weapon, it is the equivalent of a +3 greatclub and deals triple damage against inanimate objects. However, the wielder must have a Strength of at least 18 to wield it properly. Otherwise, she takes a -4 penalty on attack rolls. Strong evocation; CL 15th

### Medallion of Thoughts

- **COST:** 12000
- **WT:** 0
- **SPROP:** This appears to be a normal pendant disk hung from a neck chain. Usually fashioned from bronze, copper, or nickel-silver, the medallion allows the wearer to read the thoughts of others, as with the spell detect thoughts. Faint divination; CL 5th

### Mirror of Life Trapping

- **COST:** 200000
- **WT:** 50
- **SPROP:** This crystal device is usually about 4 feet square and framed in metal or wood. It can be hung or placed on a surface and then activated by giving a command word. The same command word deactivates the mirror. A mirror of life trapping has fifteen nonspatial extradimensional compartments within it. Any creature coming within 30 feet of the device and looking at its own reflection must make a DC 23 Will save or be trapped within the mirror in one of the cells. A creature not aware of the nature of the device always sees its own reflection. The probability of a creature seeing its reflection, and thus needing to make the saving throw, drops to 50%% if the creature is aware that the mirror traps life and seeks to avoid looking at it (treat as a gaze attack; see page 294). When a creature is trapped, it is taken bodily into the mirror. Size is not a factor, but constructs and undead are not trapped, nor are inanimate objects and other nonliving matter. A victim's equipment (including clothing and anything being carried) remains behind. If the mirror's owner knows the right command word, he can call the reflection of any creature trapped within to its surface and engage his powerless prisoner in conversation. Another command word frees the trapped creature. Each pair of command words is specific to each prisoner. If the mirror's capacity is exceeded, one victim (determined randomly) is set free in order to accommodate the latest one. If the mirror is broken, all victims currently trapped in it are freed and usually promptly attack the possessor of the device in revenge for their imprisonment. Strong abjuration; CL 17th

### Mirror of Mental Prowess

- **COST:** 175000
- **WT:** 40
- **SPROP:** This mirror resembles an ordinary looking glass 5 feet tall by 2 feet wide. The possessor who knows the proper commands can cause it to perform as follows. . Read the thoughts of any creature reflected therein, as long as the owner is within 25 feet of the mirror, even if those thoughts are in an unknown language. . View other places as if with clairvoyance, but vision extends even onto other planes if the viewer is sufficiently familiar with them. . Use it as a portal to visit other places. The user first views the place with the clairvoyance function, then steps through the mirror to the place pictured. Others can follow her through the mirror if they like. An invisible portal remains on the other side where she arrives, and she can return through that portal. Once she returns, the portal closes. The portal closes on its own after 24 hours (trapping the user if she's still in the other place), and the user can also close it with a command word. Creatures with Intelligence of 12 or higher might notice the portal just as they might notice a magical sensor from a scrying spell. Any creature who steps through the portal appears in front of the mirror. . Once per week the mirror accurately answers one short question regarding a creature whose image is shown on its surface (giving answers similar to those from the legend lore spell). Strong conjuration and divination; CL 17th

### Mirror of Opposition

- **COST:** 92000
- **WT:** 45
- **SPROP:** This item resembles a normal mirror about 4 feet long and 3 feet wide. It can be hung or placed on a surface and then activated by speaking a command word. The same command word deactivates the mirror. If a creature sees its reflection in the mirror's surface, an exact duplicate of that creature comes into being. This opposite immediately attacks the original. The duplicate has all the possessions and powers of its original (including magic). Upon the defeat or destruction of either the duplicate or the original, the duplicate and her items disappear completely. The mirror functions up to four times per day. Strong necromancy; CL 15th

### Murlynd's Spoon

- **COST:** 5400
- **WT:** 0
- **SPROP:** This unremarkable eating utensil is typically fashioned from horn. If the spoon is placed in an empty container- a bowl, a cup, or a dish, for example-the vessel fills with a thick, pasty gruel. Although this substance has a flavor similar to that of warm, wet cardboard, it is highly nourishing and contains everything necessary to sustain any herbivorous, omnivorous, or carnivorous creature. The spoon can produce sufficient gruel each day to feed up to four humans. Faint conjuration; CL 5th

### Necklace of Adaptation

- **COST:** 9000
- **WT:** 0
- **SPROP:** This necklace is a heavy chain with a platinum medallion. The magic of the necklace wraps the wearer in a shell of fresh air, making him immune to all harmful vapors and gases (such as cloudkill and stinking cloud effects, as well as inhaled poisons) and allowing him to breathe, even underwater or in a vacuum. Moderate transmutation; CL 7th;

### Necklace of Fireballs I

- **COST:** 1650
- **WT:** 0
- **SPROP:** his device appears to be nothing but beads on a string, sometimes with the ends tied together to form a necklace. (It does not count as an item worn around the neck for the purpose of determining which of a character's worn magic items is effective.) If a character holds it, however, all can see the strand as it really is-a golden chain from which hang a number of golden spheres. The spheres are detachable by the wearer (and only by the wearer), who can easily hurl one of them up to 70 feet. When a sphere arrives at the end of its trajectory, it detonates as a fireball spell (Reflex DC 14 half ). If the necklace is being worn or carried by a character who fails her saving throw against a magical fire attack, the item must make a saving throw as well (with a save bonus of +7). If the necklace fails to save, all its remaining spheres detonate simultaneously, often with regrettable consequences for the wearer. Moderate evocation; CL 10th. This necklace contains a number of spheres that do the following amount of fire damage: 1*5d6, 2*3d6.
- **EQMOD:** USABLE_ITEM_3|CHARGES[3]

### Necklace of Fireballs II

- **COST:** 2700
- **WT:** 0
- **SPROP:** his device appears to be nothing but beads on a string, sometimes with the ends tied together to form a necklace. (It does not count as an item worn around the neck for the purpose of determining which of a character's worn magic items is effective.) If a character holds it, however, all can see the strand as it really is-a golden chain from which hang a number of golden spheres. The spheres are detachable by the wearer (and only by the wearer), who can easily hurl one of them up to 70 feet. When a sphere arrives at the end of its trajectory, it detonates as a fireball spell (Reflex DC 14 half ). If the necklace is being worn or carried by a character who fails her saving throw against a magical fire attack, the item must make a saving throw as well (with a save bonus of +7). If the necklace fails to save, all its remaining spheres detonate simultaneously, often with regrettable consequences for the wearer. Moderate evocation; CL 10th. This necklace contains a number of spheres that do the following amount of fire damage: 1*6d6, 2*4d6, 2*2d6.
- **EQMOD:** USABLE_ITEM_5|CHARGES[5]

### Necklace of Fireballs III

- **COST:** 4350
- **WT:** 0
- **SPROP:** his device appears to be nothing but beads on a string, sometimes with the ends tied together to form a necklace. (It does not count as an item worn around the neck for the purpose of determining which of a character's worn magic items is effective.) If a character holds it, however, all can see the strand as it really is-a golden chain from which hang a number of golden spheres. The spheres are detachable by the wearer (and only by the wearer), who can easily hurl one of them up to 70 feet. When a sphere arrives at the end of its trajectory, it detonates as a fireball spell (Reflex DC 14 half ). If the necklace is being worn or carried by a character who fails her saving throw against a magical fire attack, the item must make a saving throw as well (with a save bonus of +7). If the necklace fails to save, all its remaining spheres detonate simultaneously, often with regrettable consequences for the wearer. Moderate evocation; CL 10th. This necklace contains a number of spheres that do the following amount of fire damage: 1*7d6, 2*5d6, 4*3d6.
- **EQMOD:** USABLE_ITEM_7|CHARGES[7]

### Necklace of Fireballs IV

- **COST:** 5400
- **WT:** 0
- **SPROP:** his device appears to be nothing but beads on a string, sometimes with the ends tied together to form a necklace. (It does not count as an item worn around the neck for the purpose of determining which of a character's worn magic items is effective.) If a character holds it, however, all can see the strand as it really is-a golden chain from which hang a number of golden spheres. The spheres are detachable by the wearer (and only by the wearer), who can easily hurl one of them up to 70 feet. When a sphere arrives at the end of its trajectory, it detonates as a fireball spell (Reflex DC 14 half ). If the necklace is being worn or carried by a character who fails her saving throw against a magical fire attack, the item must make a saving throw as well (with a save bonus of +7). If the necklace fails to save, all its remaining spheres detonate simultaneously, often with regrettable consequences for the wearer. Moderate evocation; CL 10th. This necklace contains a number of spheres that do the following amount of fire damage: 1*8d6, 2*6d6, 2*4d6, 4*2d6.
- **EQMOD:** USABLE_ITEM_9|CHARGES[9]

### Necklace of Fireballs V

- **COST:** 5850
- **WT:** 0
- **SPROP:** his device appears to be nothing but beads on a string, sometimes with the ends tied together to form a necklace. (It does not count as an item worn around the neck for the purpose of determining which of a character's worn magic items is effective.) If a character holds it, however, all can see the strand as it really is-a golden chain from which hang a number of golden spheres. The spheres are detachable by the wearer (and only by the wearer), who can easily hurl one of them up to 70 feet. When a sphere arrives at the end of its trajectory, it detonates as a fireball spell (Reflex DC 14 half ). If the necklace is being worn or carried by a character who fails her saving throw against a magical fire attack, the item must make a saving throw as well (with a save bonus of +7). If the necklace fails to save, all its remaining spheres detonate simultaneously, often with regrettable consequences for the wearer. Moderate evocation; CL 10th. This necklace contains a number of spheres that do the following amount of fire damage: 1*9d6, 2*7d6, 2*5d6, 2*3d6.
- **EQMOD:** USABLE_ITEM_7|CHARGES[7]

### Necklace of Fireballs VI

- **COST:** 8100
- **WT:** 0
- **SPROP:** his device appears to be nothing but beads on a string, sometimes with the ends tied together to form a necklace. (It does not count as an item worn around the neck for the purpose of determining which of a character's worn magic items is effective.) If a character holds it, however, all can see the strand as it really is-a golden chain from which hang a number of golden spheres. The spheres are detachable by the wearer (and only by the wearer), who can easily hurl one of them up to 70 feet. When a sphere arrives at the end of its trajectory, it detonates as a fireball spell (Reflex DC 14 half ). If the necklace is being worn or carried by a character who fails her saving throw against a magical fire attack, the item must make a saving throw as well (with a save bonus of +7). If the necklace fails to save, all its remaining spheres detonate simultaneously, often with regrettable consequences for the wearer. Moderate evocation; CL 10th. This necklace contains a number of spheres that do the following amount of fire damage: 1*10d6, 2*8d6, 2*6d6, 4*4d6.
- **EQMOD:** USABLE_ITEM_9|CHARGES[9]

### Necklace of Fireballs VII

- **COST:** 8700
- **WT:** 0
- **SPROP:** his device appears to be nothing but beads on a string, sometimes with the ends tied together to form a necklace. (It does not count as an item worn around the neck for the purpose of determining which of a character's worn magic items is effective.) If a character holds it, however, all can see the strand as it really is-a golden chain from which hang a number of golden spheres. The spheres are detachable by the wearer (and only by the wearer), who can easily hurl one of them up to 70 feet. When a sphere arrives at the end of its trajectory, it detonates as a fireball spell (Reflex DC 14 half ). If the necklace is being worn or carried by a character who fails her saving throw against a magical fire attack, the item must make a saving throw as well (with a save bonus of +7). If the necklace fails to save, all its remaining spheres detonate simultaneously, often with regrettable consequences for the wearer. Moderate evocation; CL 10th. This necklace contains a number of spheres that do the following amount of fire damage: 1*10d6, 2*9d6, 2*7d6, 2*5d6, 2*3d6.
- **EQMOD:** USABLE_ITEM_9|CHARGES[9]

### Nolzur's Marvelous Pigments

- **COST:** 4000
- **WT:** 0
- **SPROP:** These magic emulsions enable their possessor to create actual, permanent objects simply by depicting their form in two dimensions. The pigments are applied by a stick tipped with bristles, hair, or fur. The emulsion flows from the application to form the desired object as the artist concentrates on the desired image. One pot of Nolzur's marvelous pigments is sufficient to create a 1,000-cubic-foot object by depicting it two-dimensionally over a 100-square-foot surface. Thus, a 10-foot-by-10- foot rendition of a pit would result in an actual 10-foot-by-10-footby- 10-foot pit; a 10-foot-by-10-foot depiction of a room would result in a 10-foot-by-10-foot-by-10-foot room; and so on. Only normal, inanimate objects can be created-doors, pits, flowers, trees, cells, and so on. Creatures can't be created. The pigments must be applied to a surface (a floor, wall, ceiling, door, or the like). It takes 10 minutes and a DC 15 Craft (painting) check to depict an object with the pigments. Nolzur's marvelous pigments cannot create magic items. Objects of value depicted by the pigments- precious metals, gems, jewelry, ivory, and so on- appear to be valuable but are really made of tin, lead, paste, brass, bone, and other such inexpensive materials. The user can create normal weapons, armor, and any other mundane item (including foodstuffs) whose value does not exceed 2,000 gp. Items created are not magical; the effect is instantaneous. Strong conjuration; CL 15th

### Orb of Storms

- **COST:** 48000
- **WT:** 6
- **SPROP:** This glass sphere is 8 inches in diameter. The possessor can call forth all manner of weather, even supernaturally destructive storms. Once per day she can call upon the orb to use a control weather spell, Once per month, she can conjure a storm of vengeance. The possessor of the orb is continually protected by an endure elements effect. Strong varied; CL 18th

### Pearl of Power (1st Level)

- **COST:** 1000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one first level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (2nd Level)

- **COST:** 4000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one second level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (3rd Level)

- **COST:** 9000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one third level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (4th Level)

- **COST:** 16000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one fourth level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (5th Level)

- **COST:** 25000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one fifth level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (6th Level)

- **COST:** 36000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one sixth level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (7th Level)

- **COST:** 49000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one seventh level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (8th Level)

- **COST:** 64000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one eigth level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (9th Level)

- **COST:** 81000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Once per day on command, a pearl of power enables the possessor to recall any one ninth level spell that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of Power (2 Spells)

- **COST:** 70000
- **WT:** 0
- **SPROP:** This seemingly normal pearl of average size and luster is a potent aid to all spellcasters who prepare spells (clerics, druids, rangers, paladins, and wizards). Twice per day on command, a pearl of power enables the possessor to recall any spell of 6th level or lower that she had prepared and then cast. The spell is then prepared again, just as if it had not been cast. Strong transmutation; CL 17th;

### Pearl of the Sirines

- **COST:** 15300
- **WT:** 0
- **SPROP:** This normal-seeming pearl is beautiful and worth at least 1,000 gp on that basis alone. If it is clasped firmly in hand or held to the breast while the possessor attempts actions related to the pearl's powers, she understands and is able to employ the item. The pearl enables its possessor to breathe in water as if she were in clean, fresh air. Her swim speed is 60 feet, and she can cast spells and act underwater without hindrance. Moderate abjuration and transmutation; CL 8th

### Periapt of Health

- **COST:** 7500
- **WT:** 0
- **SPROP:** The wearer of this blue gem on a silver chain is immune to disease, including supernatural diseases (see Table 8-2: Diseases, page 292). Faint conjuration; CL 5th

### Periapt of Proof against Poison

- **COST:** 27000
- **WT:** 0
- **SPROP:** This item is a brilliant-cut black gem on a delicate silver chain. The wearer is immune to poison, although poisons still active when the periapt is first donned still run their course. Faint conjuration; CL 5th

### Periapt of Wisdom +2

- **COST:** 4000
- **WT:** 0
- **BONUS:** STAT|WIS|2|TYPE=Enhancement
- **SPROP:** Although it appears to be a normal pearl on a light chain, a periapt of wisdom actually increases the possessor's Wisdom score in the form of an enhancement bonus of +2. Moderate transmutation; CL 8th
- **SORTKEY:** Periapt of Wisdom +02

### Periapt of Wisdom +4

- **COST:** 16000
- **WT:** 0
- **BONUS:** STAT|WIS|4|TYPE=Enhancement
- **SPROP:** Although it appears to be a normal pearl on a light chain, a periapt of wisdom actually increases the possessor's Wisdom score in the form of an enhancement bonus of +4. Moderate transmutation; CL 8th
- **SORTKEY:** Periapt of Wisdom +04

### Periapt of Wisdom +6

- **COST:** 36000
- **WT:** 0
- **BONUS:** STAT|WIS|6|TYPE=Enhancement
- **SPROP:** Although it appears to be a normal pearl on a light chain, a periapt of wisdom actually increases the possessor's Wisdom score in the form of an enhancement bonus of +6. Moderate transmutation; CL 8th
- **SORTKEY:** Periapt of Wisdom +06

### Periapt of Wound Closure

- **COST:** 15000
- **WT:** 0
- **SPROP:** This stone is bright red and dangles on a gold chain. The wearer of this periapt automatically becomes stable if his hit points drop to between -1 and -9 inclusive. The periapt doubles the wearer's normal rate of healing or allows normal healing of wounds that would not do so normally. Hit point damage that involves bleeding (such as damage caused by the horned devil's infernal wound ability; see page 55 of the Monster Manual), is negated for the wearer of the periapt, but he is still susceptible to damage from bleeding that causes Constitution loss, such as that dealt by a wounding weapon. Moderate conjuration; CL 10th;

### Phylactery of Faithfulness

- **COST:** 1000
- **WT:** 0
- **SPROP:** This item is a small box containing religious scripture affixed to a leather cord and tied around the forehead. There is no mundane way to determine what function this religious item performs until it is worn. The wearer of a phylactery of faithfulness is aware of any action or item that could adversely affect his alignment and his standing with his deity, including magical effects. He acquires this information prior to performing such an action or becoming associated with such an item if he takes a moment to contemplate the act. Faint divination; CL 1st

### Phylactery of Undead Turning

- **COST:** 11000
- **WT:** 0
- **BONUS:** VAR|TurnLevelUndead|4
- **BONUS:** VAR|TurnDamagePlusUndead|4
- **SPROP:** This item is a boon to any character able to turn undead, allowing him to do so as if his class level were four levels higher than it actually is. Moderate necromancy [good]; CL 10th

### Pipes of Haunting

- **COST:** 6000
- **WT:** 3
- **SPROP:** This magic item appears to be a small set of pan pipes. When played by a person who succeeds on a DC 15 Perform (wind instruments) check, the pipes create an eerie, spellbinding tune. Those within 30 feet who hear the tune must succeed on a DC 13 Will save or become frightened for 4 rounds. Creatures with 6 or more Hit Dice are unaffected. Pipes of haunting can be sounded twice a day. Faint necromancy; CL 4th

### Pipes of Pain

- **COST:** 12000
- **WT:** 3
- **SPROP:** These appear to be like any other standard set of pipes with nothing to reveal their true nature. When played by someone who succeeds on a DC 15 Perform (wind instruments) check, the pipes create a wondrous melody. All within 30 feet must make a DC 14 Will save or be fascinated by the sound. (This is a mind-affecting sonic compulsion.) As soon as the piping stops, all those affected are stricken by intense pain at even the slightest noise. Unless a character is in a totally silent area, she takes 1d4 points of damage per round for 2d4 rounds. During this time, damage from sonic attacks, such as sound burst, is doubled. Thereafter, the least noise causes an affected character to become shaken (except when she is in a totally silent area). This hypersensitivity is a curse and therefore hard to remove (see the bestow curse spell). Faint enchantment and evocation; CL 6th

### Pipes of the Sewers

- **COST:** 1150
- **WT:** 3
- **SPROP:** These wooden pipes appear ordinary, but if the possessor learns the proper tune, he can attract 1d3 rat swarms (see page 239 of the Monster Manual) if rats are within 400 feet. For each 50-foot distance the rats have to travel, there is a 1- round delay. The piper must continue playing until the rats appear, and when they do so, the piper must make a DC 10 Perform (wind instruments) check. Success means that they obey the piper's telepathic commands so long as he continues to play. Failure indicates that they turn on the piper. If for any reason the piper ceases playing, the rats leave immediately. If they are called again within a day, the Perform check DC is 15. If the rats are under the control of another creature, add the HD of the controller to the Perform check DC. Once control is assumed, another check is required each round to maintain it if the other creature is actively seeking to reassert its control. Faint conjuration; CL 2nd

### Pipes of Sounding

- **COST:** 1800
- **WT:** 3
- **SPROP:** When played by a character who has the Perform (wind instruments) skill, these pipes create a variety of sounds. The figment sounds are the equivalent of ghost sound (caster level 2nd). Faint illusion; CL 2nd

### Portable Hole

- **CONTAINS:** *UNLIM|Any
- **COST:** 20000
- **WT:** 0
- **SPROP:** A portable hole is a circle of cloth spun from the webs of a phase spider interwoven with strands of ether and beams of starlight. When opened fully, a portable hole is 6 feet in diameter, but it can be folded up to be as small as a pocket handkerchief. When spread upon any surface, it causes an extradimensional space 10 feet deep to come into being. This hole can be picked up from inside or out by simply taking hold of the edges of the cloth and folding it up. Either way, the entrance disappears, but anything inside the hole remains. The only air in the hole is that which enters when the hole is opened. It contains enough air to supply one Medium creature or two Small creatures for 10 minutes. (See Suffocation, page 304.) The cloth does not accumulate weight even if its hole is filled (with gold, for example). Each portable hole opens on its own particular nondimensional space. If a bag of holding (see page 248) is placed within a portable hole, a rift to the Astral Plane is torn in that place. Both the bag and the cloth are sucked into the void and forever lost. If a portable hole is placed within a bag of holding, it opens a gate to the Astral Plane. The hole, the bag, and any creatures within a 10-foot radius are drawn there, the portable hole and bag of holding being destroyed in the process. Moderate conjuration; CL 12th

### Quaal's Feather Token (Anchor)

- **COST:** 50
- **WT:** 0
- **SPROP:** A small feather that has a specific power to suit a special need, though usable only once. A token useful to moor a craft in water so as to render it immobile for up to one day. Moderate conjuration; CL 12th

### Quaal's Feather Token (Bird)

- **COST:** 300
- **WT:** 0
- **SPROP:** A small feather that has a specific power to suit a special need, though usable only once. A token that can be used to deliver a small written message unerringly to a designated target as would a carrier pigeon. The token lasts as long as it takes to carry the message. Moderate conjuration; CL 12th

### Quaal's Feather Token (Fan)

- **COST:** 200
- **WT:** 0
- **SPROP:** A small feather that has a specific power to suit a special need, though usable only once. A token that forms a huge flapping fan, causing a breeze of sufficient strength to propel one ship (about 25 mph). This wind is not cumulative with existing wind speed-if a severe wind is already blowing, for example, this wind cannot be added to it to create a windstorm. The token can, however, be used to lessen existing winds, creating an area of relative calm or lighter winds (but wave size in a storm is not affected). The fan can be used for up to 8 hours. It does not function on land. Moderate conjuration; CL 12th

### Quaal's Feather Token (Swan Boat)

- **COST:** 450
- **WT:** 0
- **SPROP:** A small feather that has a specific power to suit a special need, though usable only once. A token that forms a swanlike boat capable of moving on water at a speed of 60 feet. It can carry eight horses and gear or thirty-two Medium characters or any equivalent combination. The boat lasts for one day. Moderate conjuration; CL 12th

### Quaal's Feather Token (Tree)

- **COST:** 400
- **WT:** 0
- **SPROP:** A small feather that has a specific power to suit a special need, though usable only once. A token that causes a great oak to spring into being (5-foot diameter trunk, 60-foot height, 40-foot top diameter). This is an instantaneous effect. Moderate conjuration; CL 12th

### Quaal's Feather Token (Whip)

- **COST:** 500
- **WT:** 0
- **SPROP:** A small feather that has a specific power to suit a special need, though usable only once. A token that forms into a huge leather whip and wields itself against any opponent desired just like a dancing weapon (see page 224). The weapon has a +10 base attack bonus, does 1d6+1 points of damage, has a +1 enhancement bonus on attack and damage rolls, and a makes a free grapple attack (with a +15 attack bonus) if it hits. The whip lasts no longer than 1 hour. Moderate conjuration; CL 12th

### Quiver of Ehlonna

- **CONTAINS:** *UNLIM|Ammunition=60|Thrown=18|Weapon=6
- **COST:** 1800
- **WT:** 2
- **SPROP:** This appears to be a typical arrow container capable of holding about twenty arrows. It has three distinct portions, each with a nondimensional space allowing it to store far more than would normally be possible. The first and smallest one can contain up to sixty objects of the same general size and shape as an arrow. The second slightly longer compartment holds up to eighteen objects of the same general size and shape as a javelin. The third and longest portion of the case contains as many as six objects of the same general size and shape as a bow (spears, staffs, or the like). Once the owner has filled it, the quiver can produce any item she wishes, as if from a regular quiver or scabbard. The quiver of Ehlonna weighs the same no matter what's placed inside it. Moderate conjuration; CL 9th

### Ring Gates

- **COST:** 40000
- **WT:** 2
- **SPROP:** These always come in pairs-two iron rings, each about 18 inches in diameter. The rings must be on the same plane of existence and within 100 miles of each other to function. Whatever is put through one ring comes out the other, and up to 100 pounds of material can be transferred each day. (Objects only partially pushed through and then retracted do not count.) This useful device allows for instantaneous transport of items or messages, and even attacks. A character can reach through to grab things near the other ring, or even stab a weapon through if so desired. Alternatively, a character could stick his head through to look around. A spellcaster could even cast a spell through a ring gate. A Small character can make a DC 13 Escape Artist check to slip through. Creatures of Tiny, Diminutive, or Fine size can pass through easily. Each ring has a "entry side" and an "exit side," both marked with appropriate symbols. Strong conjuration; CL 17th

### Ring Gates (Pair)

- **COST:** 40000
- **WT:** 2
- **SPROP:** These always come in pairs-two iron rings, each about 18 inches in diameter. The rings must be on the same plane of existence and within 100 miles of each other to function. Whatever is put through one ring comes out the other, and up to 100 pounds of material can be transferred each day. (Objects only partially pushed through and then retracted do not count.) This useful device allows for instantaneous transport of items or messages, and even attacks. A character can reach through to grab things near the other ring, or even stab a weapon through if so desired. Alternatively, a character could stick his head through to look around. A spellcaster could even cast a spell through a ring gate. A Small character can make a DC 13 Escape Artist check to slip through. Creatures of Tiny, Diminutive, or Fine size can pass through easily. Each ring has a "entry side" and an "exit side," both marked with appropriate symbols. Strong conjuration; CL 17th

### Ring Gates (1 of 2)

- **COST:** 20000
- **WT:** 1
- **SPROP:** These always come in pairs-two iron rings, each about 18 inches in diameter. The rings must be on the same plane of existence and within 100 miles of each other to function. Whatever is put through one ring comes out the other, and up to 100 pounds of material can be transferred each day. (Objects only partially pushed through and then retracted do not count.) This useful device allows for instantaneous transport of items or messages, and even attacks. A character can reach through to grab things near the other ring, or even stab a weapon through if so desired. Alternatively, a character could stick his head through to look around. A spellcaster could even cast a spell through a ring gate. A Small character can make a DC 13 Escape Artist check to slip through. Creatures of Tiny, Diminutive, or Fine size can pass through easily. Each ring has a "entry side" and an "exit side," both marked with appropriate symbols. Strong conjuration; CL 17th

### Robe of the Archmagi (Black)

- **COST:** 75000
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **SR:** 18
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **BONUS:** VAR|NegLevels|3
- **BONUS:** VAR|NegLevels|2
- **SPROP:** This normal-appearing garment is black with an evil alignment. Its wearer, if an arcane spellcaster, gains the following powers. +5 armor bonus to AC. Spell resistance 18. +4 resistance bonus on all saving throws. +2 enhancement bonus on caster level checks made to overcome spell resistance.
- **SPROP:** Due to your alignment, when you donned this robe you gained three negative levels. While these negative levels never result in lost levels, they remain as long as the garment is worn and cannot be overcome in any way (including restoration spells).
- **SPROP:** Due to your alignment, when you donned this robe you gained two negative levels. While these negative levels never result in lost levels, they remain as long as the garment is worn and cannot be overcome in any way (including restoration spells).
- **SPROP:** Strong varied; CL 14th;
- **BONUS:** SAVE|Fortitude,Reflex,Will|4|TYPE=Resistance

### Robe of the Archmagi (Gray)

- **COST:** 75000
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **SR:** 18
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **BONUS:** VAR|NegLevels|2
- **SPROP:** This normal-appearing garment is grey. Its wearer, if an arcane spellcaster, gains the following powers. +5 armor bonus to AC. Spell resistance 18. +4 resistance bonus on all saving throws. +2 enhancement bonus on caster level checks made to overcome spell resistance.
- **SPROP:** Due to your alignment, when you donned this robe you gained two negative levels. While these negative levels never result in lost levels, they remain as long as the garment is worn and cannot be overcome in any way (including restoration spells).
- **SPROP:** Strong varied; CL 14th;
- **BONUS:** SAVE|Fortitude,Reflex,Will|4|TYPE=Resistance

### Robe of the Archmagi (White)

- **COST:** 75000
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **SR:** 18
- **BONUS:** COMBAT|AC|5|TYPE=Armor
- **BONUS:** VAR|NegLevels|3
- **BONUS:** VAR|NegLevels|2
- **SPROP:** This normal-appearing garment is white with a good alignment. Its wearer, if an arcane spellcaster, gains the following powers. +5 armor bonus to AC. Spell resistance 18. +4 resistance bonus on all saving throws. +2 enhancement bonus on caster level checks made to overcome spell resistance.
- **SPROP:** Due to your alignment, when you donned this robe you gained three negative levels. While these negative levels never result in lost levels, they remain as long as the garment is worn and cannot be overcome in any way (including restoration spells).
- **SPROP:** Due to your alignment, when you donned this robe you gained two negative levels. While these negative levels never result in lost levels, they remain as long as the garment is worn and cannot be overcome in any way (including restoration spells).
- **SPROP:** Strong varied; CL 14th;
- **BONUS:** SAVE|Fortitude,Reflex,Will|4|TYPE=Resistance

### Robe of Blending

- **COST:** 30000
- **WT:** 1
- **BONUS:** SKILL|Hide|10|TYPE=Competence
- **SPROP:** When this robe is put on, the wearer intuitively knows that the garment has very special properties. A robe of blending enables its wearer to appear to be part of his surroundings. This allows him a +10 competence bonus on Hide checks. The wearer can adopt the appearance of another creature, as with the disguise self spell, at will. All creatures acquainted with and friendly to the wearer see him normally. Moderate illusion; CL 10th
- **SPROP:** Change Self at will

### Robe of Bones

- **COST:** 2400
- **WT:** 1
- **SPROP:** This handy item functions much like a robe of useful items for the serious necromancer. It appears to be an unremarkable robe, but a character who dons it notes that it is adorned with small embroidered figures representing undead creatures. Only the wearer of the robe can see the embroidery and recognize them for the creatures they become, and detach them. One figure can be detached each round. Detaching a figure causes it to become an actual undead creature(see the list below). The skeleton or zombie is not under the control of the wearer of the robe, but may be subsequently commanded, rebuked, turned, or destroyed. A newly created robe of bones always has two embroidered figures of each of the following undead: . Small goblin skeleton . Medium human commoner skeleton . Medium wolf skeleton . Small goblin zombie . Medium human commoner zombie . Medium wolf zombie Moderate necromancy [evil]; CL 6th;

### Robe of Eyes

- **COST:** 120000
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Retain Dex To AC ~ Flat-footed
- **BONUS:** SKILL|Search,Spot|10|TYPE=Competence
- **BONUS:** VAR|SeeEtheralRange|120|TYPE=Base|
- **BONUS:** VAR|SeeInvisibilityRange|120|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|120|TYPE=Base
- **SPROP:** This valuable garment appears to be a normal robe until it is put on. Its wearer is able to see in all directions at the same moment due to scores of visible, magical eyelike patterns that adorn the robe. She also gains 120-foot darkvision. The robe of eyes sees all forms of invisible or ethereal things within 120 feet. The wearer of a robe of eyes gains a +10 competence bonus on Search checks and Spot checks. She retains her Dexterity bonus to AC even when flat-footed, and she can't be flanked. However, she is not able to avert her eyes or close her eyes when confronted by a creature with a gaze attack. A light or continual flame spell cast directly on a robe of eyes causes it to be blinded for 1d3 minutes. A daylight spell blinds it for 2d4 minutes. Moderate divination; CL 11th;

### Robe of Scintillating Colors

- **COST:** 27000
- **WT:** 1
- **SPROP:** The wearer of this robe can cause the garment to display a shifting pattern of incredible hues, color after color cascading from the upper part of the robe to the hem in sparkling rainbows of dazzling light. The colors daze those near the wearer, conceal the wearer, and illuminate the surroundings. It takes 1 full round after the wearer speaks the command word for the colors to start flowing on the robe. The colors create the equivalent of a gaze attack with a 30-foot range. Those who look at the wearer are dazed for 1d4+1 rounds (Will DC 16 negates). This is a mind-affecting pattern effect. Every round of continuous scintillation of the robe gives the wearer better concealment. The miss chance on attacks against the wearer starts at 10%% and increases by 10%% each round until it reaches 50%% (total concealment). The robe illuminates a 30-foot radius continuously. The effect can be used no more than a total of 10 rounds per day. Moderate illusion; CL 11th;

### Robe of Stars

- **COST:** 58000
- **WT:** 1
- **SPROP:** This garment is typically black or dark blue and embroidered with small white or silver stars. The robe has three magical powers. . It enables its wearer to travel physically to the Astral Plane, along with all that she is wearing or carrying. . It gives its wearer a +1 luck bonus on all saving throws. . Its wearer can use up to six of the embroidered stars on the chest portion of the robe as +5 shuriken. The robe grants its wearer proficiency with such weapons. Each shuriken disappears after it is used. Strong varied; CL 15th
- **BONUS:** SAVE|Fortitude,Will,Reflex|1|TYPE=Luck

### Robe of Useful Items

- **COST:** 7000
- **WT:** 1
- **SPROP:** This appears to be an unremarkable robe, but a character who dons it notes that it is adorned with small cloth patches of various shapes. Only the wearer of the robe can see these patches, recognize them for what items they become, and detach them. One patch can be detached each round. Detaching a patch causes it to become an actual item, as indicated below. A newly created robe of useful items always has two each of the following patches: . Dagger . Bullseye lantern (filled and lit) . Mirror (a highly polished 2-foot-by-4-foot steel mirror) . Pole (10-foot length) . Hempen rope (50-foot coil) . Sack In addition, the robe has several other patches. Roll 4d4 for the number of other patches and then roll for each patch on the table below to determine its nature. Multiple items of the same kind are permissible. Once removed, a patch cannot be replaced. Moderate transmutation; CL 9th;

### Rope of Climbing

- **COST:** 3000
- **WT:** 3
- **SPROP:** A 60-foot-long rope of climbing is no thicker than a wand, but it is strong enough to support 3,000 pounds. Upon command, the rope snakes forward, upward, downward, or in any other direction at 10 feet per round, attaching itself securely wherever its owner desires. It can unfasten itself and return in the same manner. A rope of climbing can be commanded to knot or unknot itself. This causes large knots to appear at 1-foot intervals along the rope. Knotting shortens the rope to a 50-foot length until the knots are untied but lowers the DC of Climb checks while using it by 10. A creature must hold one end of the rope when its magic is invoked. Faint transmutation; CL 3rd

### Rope of Entanglement

- **COST:** 21000
- **WT:** 5
- **SPROP:** A rope of entanglement looks just like any other hempen rope about 30 feet long. Upon command, the rope lashes forward 20 feet or upward 10 feet to entangle a victim. An entangled creature can break free with a DC 20 Strength check or a DC 20 Escape Artist check. The rope has AC 22, 12 hit points, and hardness 10, and it has damage reduction 5/slashing as well. The rope repairs damage to itself at a rate of 1 point per 5 minutes, but if a rope of entanglement is severed (all 12 hit points lost to damage), it is destroyed. Moderate transmutation; CL 12th

### Salve of Slipperiness

- **COST:** 1000
- **WT:** 0
- **SPROP:** This substance provides a +20 competence bonus on all Escape Artist checks, meaning that it is almost impossible to grapple such a character or to tie or chain him up. In addition, such obstructions as webs (magical or otherwise) do not affect an anointed individual. Magic ropes and the like do not avail against this salve. If it is smeared on a floor or on steps, the area should be treated as a long-lasting grease spell. The salve requires 8 hours to wear off normally, or it can be wiped off with an alcohol solution (even wine). Salve of slipperiness is needed to coat the inside of a container that is meant to hold sovereign glue (see below). Faint conjuration; CL 6th

### Scabbard of Keen Edges

- **COST:** 16000
- **WT:** 1
- **SPROP:** This scabbard is fashioned from cured leather and fine silver. It can shrink or enlarge to accommodate any knife, dagger, sword, or similar weapon up to and including a greatsword. Up to three times per day on command, the scabbard casts keen edge on any blade placed within it. Faint transmutation; CL 5th

### Scarab of Protection

- **COST:** 38000
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_12|CHARGES[12]
- **SR:** 20
- **SPROP:** This device appears to be a silver medallion in the shape of a beetle. If it is held for 1 round, an inscription appears on its surface letting the holder know that it is a protective device. The scarab's possessor gains spell resistance 20. The scarab can also absorb energy-draining attacks (such as the slam attack of a vampire spawn), death effects (such as finger of death), and negative energy effects (such as from an inflict critical wounds spell). Upon absorbing twelve such attacks, the scarab turns to powder and is destroyed. Strong abjuration and necromancy; CL 18th

### Scarab, Golembane

- **COST:** 2500
- **WT:** 0
- **SPROP:** This beetle-shaped pin enables its wearer to detect any golem within 60 feet, although he must concentrate (a standard action) in order for the detection to take place. A scarab enables its possessor to combat golems with weapons, unarmed attacks, or natural weapons as if those golems had no damage reduction. Moderate divination; CL 8th;

### Shrouds of Disintegration

- **COST:** 6600
- **WT:** 10
- **SPROP:** These burial wrappings look to be made of fine, embroidered materials. When a body is placed inside, a command word will turn it to dust. The magic of the shrouds is usable only once, after which the wrappings become ordinary, fine cloth. Strong transmutation; CL 15th

### Silversheen

- **COST:** 250
- **WT:** 0
- **SPROP:** This substance can be applied to a weapon as a standard action. It will give the weapon the properties of alchemical silver (see page 284) for 1 hour, replacing the properties of any other special material it might have. For example, a +1 holy adamantine longsword becomes a +1 holy silver longsword for the duration of the effect. One vial will coat a single melee weapon or 20 units of ammunition. Faint transmutation; CL 5th

### Slippers of Spider Climbing

- **COST:** 4800
- **WT:** 0.5
- **SLOTS:** 2
- **SPROP:** When worn, a pair of these slippers enable movement on vertical surfaces or even upside down along ceilings, leaving the wearer's hands free. Her speed is 20 feet. Severely slippery surfaces-icy, oiled, or greased surfaces- make these slippers useless. The slippers can be used for 10 minutes per day, split up as the wearer chooses. Faint transmutation; CL 4th

### Sovereign Glue

- **COST:** 2400
- **WT:** 0
- **SPROP:** This pale amber substance is thick and viscous. Because of its particular powers, it can be contained only in a flask whose inside has been coated with 1 ounce of salve of slipperiness (see the previous page), and each time any of the bonding agent is poured from the flask, a new application of the salve of slipperiness must be put in the flask within 1 round to prevent the remaining glue from adhering to the side of the container. A flask of sovereign glue, when found, holds anywhere from 1 to 7 ounces of the stuff (1d8-1, minimum 1), with the other ounce of the flask's capacity taken up by the salve of slipperiness. One ounce of this adhesive covers 1 square foot of surface, bonding virtually any two substances together in a permanent union. The glue takes 1 round to set. If the objects are pulled apart (a move action) before that time has elapsed, that application of the glue loses its stickiness and is worthless. If the glue is allowed to set, then attempting to separate the two bonded objects has no effect, except when universal solvent is applied to the bond. (Sovereign glue is dissolved by universal solvent.) Strong transmutation; CL 20th;

### Sovereign Glue (Flask)

- **COST:** 16800
- **WT:** 2
- **EQMOD:** CHARGED_ITEM_7|CHARGES[7]
- **SPROP:** This pale amber substance is thick and viscous. Because of its particular powers, it can be contained only in a flask whose inside has been coated with 1 ounce of salve of slipperiness (see the previous page), and each time any of the bonding agent is poured from the flask, a new application of the salve of slipperiness must be put in the flask within 1 round to prevent the remaining glue from adhering to the side of the container. A flask of sovereign glue, when found, holds anywhere from 1 to 7 ounces of the stuff (1d8-1, minimum 1), with the other ounce of the flask's capacity taken up by the salve of slipperiness. One ounce of this adhesive covers 1 square foot of surface, bonding virtually any two substances together in a permanent union. The glue takes 1 round to set. If the objects are pulled apart (a move action) before that time has elapsed, that application of the glue loses its stickiness and is worthless. If the glue is allowed to set, then attempting to separate the two bonded objects has no effect, except when universal solvent is applied to the bond. (Sovereign glue is dissolved by universal solvent.) Strong transmutation; CL 20th;

### Stone of Alarm

- **COST:** 2700
- **WT:** 2
- **SPROP:** This stone cube, when given the command word, affixes itself to any object. If that object is touched thereafter by anyone who does not first speak that same command word, the stone emits a piercing screech for 1 hour that can be heard up to a quarter-mile away (assuming no intervening barriers). Faint abjuration; CL 3rd;

### Stone of Controlling Earth Elementals

- **COST:** 100000
- **WT:** 5
- **SPROP:** A stone of this nature is typically an oddly shaped bit of roughly polished rock. The possessor of such a stone need but utter a few words of summoning, and a Huge earth elemental comes to the summoner. The summoning words require 1 full round to speak, and in all ways the stone functions as the summon monster VII spell. (If sand or rough, unhewn stone is the summoning medium, the elemental that comes is Large instead, and the stone functions as the summon monster VI spell.) The elemental appears in 1d4 rounds. For detailed information about elementals, see page 95 of the Monster Manual. Only one elemental can be summoned at a time. A new elemental requires a new patch of earth or stone, which cannot be accessed until after the first elemental disappears (is dispelled, dismissed, or slain). Strong conjuration; CL 13th;

### Stone of Good Luck (Luckstone)

- **COST:** 20000
- **WT:** 0
- **BONUS:** SKILL|TYPE.Strength,TYPE.Dexterity,TYPE.Constitution,TYPE.Intelligence,TYPE.Wisdom,TYPE.Charisma|1|TYPE=Luck
- **BONUS:** VAR|TurnCheckBase|1|TYPE=Luck
- **SPROP:** This stone is typically a bit of rough polished agate or some similar mineral. Its possessor gains a +1 luck bonus on saving throws, ability checks, and skill checks. Faint evocation; CL 5th;
- **BONUS:** SAVE|Fortitude,Reflex,Will|1|TYPE=Luck

### Stone Horse (Courser)

- **COST:** 10000
- **WT:** 6000
- **SPROP:** Each item of this nature appears to be a fullsized, roughly hewn statue of a horse, carved from some type of hard stone. A command word brings the steed to life, enabling it to carry a burden and even to attack as if it were a real horse of the appropriate kind. A stone horse can carry 1,000 pounds tirelessly and never needs to rest or feed. Damage dealt to it can be repaired by first using a stone to flesh spell, thus causing the stone horse to become a normal horse that can be healed normally. When fully healed, it automatically reverts to its stone form. While in its stone form, it can be fed gems, healing 1 point of damage for each 50 gp worth of mineral it is given. There are two sorts of stone horses. Courser: This item has the statistics of a heavy horse (see page 273 of the Monster Manual), as well as having hardness 10. Destrier: This item has the statistics of a heavy warhorse (see page 273 of the Monster Manual), as well as having hardness 10. Strong transmutation; CL 14th

### Stone Horse (Destrier)

- **COST:** 14800
- **WT:** 6000
- **SPROP:** Each item of this nature appears to be a fullsized, roughly hewn statue of a horse, carved from some type of hard stone. A command word brings the steed to life, enabling it to carry a burden and even to attack as if it were a real horse of the appropriate kind. A stone horse can carry 1,000 pounds tirelessly and never needs to rest or feed. Damage dealt to it can be repaired by first using a stone to flesh spell, thus causing the stone horse to become a normal horse that can be healed normally. When fully healed, it automatically reverts to its stone form. While in its stone form, it can be fed gems, healing 1 point of damage for each 50 gp worth of mineral it is given. There are two sorts of stone horses. Courser: This item has the statistics of a heavy horse (see page 273 of the Monster Manual), as well as having hardness 10. Destrier: This item has the statistics of a heavy warhorse (see page 273 of the Monster Manual), as well as having hardness 10. Strong transmutation; CL 14th

### Stone Salve

- **COST:** 4000
- **WT:** 0
- **SPROP:** This ointment has two uses. If an ounce of it is applied to the flesh of a petrified creature, it returns the creature to flesh as the stone to flesh spell. If an ounce of it is applied to the flesh of a nonpetrified creature, it protects the creature as a stoneskin spell. Strong abjuration and transmutation; CL 13th

### Strand of Prayer Beads (Lesser)

- **COST:** 9600
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Bless
- **SPROP:** This item appears to be a normal string of prayer beads until the owner casts a divine spell. Once that occurs, the owner instantly knows the powers of the prayer beads and how to activate them. Each strand includes two or more special beads, each with a different magic power. Each special bead can be used once per day, except for the bead of summons, which works only once and then becomes nonmagical. The beads of blessing, smiting, and wind walking function as spell trigger items; the beads of karma and summons can be activated by any character capable of casting divine spells. The owner need not hold or wear the strand of prayer beads in any specific location, as long as he carries it somewhere on his person. The power of a special bead is lost if it is removed from the strand. Faint, moderate or strong (many schools); CL 1st (blessing), 5th (healing), 7th (smiting), 9th (karma), 11th (wind walking), 17th (summons)
- **SPROP:** Bead of Blessing 1/day -- Wearer can cast bless. Bead of Healing 1/day -- Wearer can cast his choice of Cure Serious Wounds, Remove Blindness/Deafness, or Remove Disease.

### Strand of Prayer Beads

- **COST:** 25800
- **WT:** 0
- **SPROP:** This item appears to be a normal string of prayer beads until the owner casts a divine spell. Once that occurs, the owner instantly knows the powers of the prayer beads and how to activate them. Each strand includes two or more special beads, each with a different magic power. Each special bead can be used once per day, except for the bead of summons, which works only once and then becomes nonmagical. The beads of blessing, smiting, and wind walking function as spell trigger items; the beads of karma and summons can be activated by any character capable of casting divine spells. The owner need not hold or wear the strand of prayer beads in any specific location, as long as he carries it somewhere on his person. The power of a special bead is lost if it is removed from the strand. Faint, moderate or strong (many schools); CL 1st (blessing), 5th (healing), 7th (smiting), 9th (karma), 11th (wind walking), 17th (summons)
- **SPROP:** Bead of Healing 1/day -- Wearer can cast his choice of cure serious wounds, remove blindness/deafness, or remove disease. Bead of Karma 1/ day -- Wearer casts his spells at +4 caster level. Effect lasts 10 minutes. Bead of Smiting 1/day -- Wearer can cast chaos hammer, holy smite, order's wrath, or unholy blight (Will DC 17 partial).

### Strand of Prayer Beads (Greater)

- **COST:** 95800
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=11|Wind Walk
- **SPROP:** This item appears to be a normal string of prayer beads until the owner casts a divine spell. Once that occurs, the owner instantly knows the powers of the prayer beads and how to activate them. Each strand includes two or more special beads, each with a different magic power. Each special bead can be used once per day, except for the bead of summons, which works only once and then becomes nonmagical. The beads of blessing, smiting, and wind walking function as spell trigger items; the beads of karma and summons can be activated by any character capable of casting divine spells. The owner need not hold or wear the strand of prayer beads in any specific location, as long as he carries it somewhere on his person. The power of a special bead is lost if it is removed from the strand. Faint, moderate or strong (many schools); CL 1st (blessing), 5th (healing), 7th (smiting), 9th (karma), 11th (wind walking), 17th (summons)
- **SPROP:** Bead of Healing 1/day -- Wearer can cast his choice of cure serious wounds, remove blindness/deafness, or remove disease. Bead of Karma 1/ day -- Wearer casts his spells at +4 caster level. Effect lasts 10 minutes. Bead of Summons 1 time only -- Summons a powerful creature of appropriate alignment from the Outer Planes (an angel, devil, etc.) to aid the wearer for one day. (If the wearer uses the bead of summons to summon a deity's emissary frivolously, the deity takes that character's items and places a geas/quest upon him as punishment in the very least.) Bead of Wind Walk 1/day -- Wearer can cast Wind Walk

### Tome of Clear Thought +1

- **COST:** 27500
- **WT:** 5
- **SPROP:** This heavy book contains instruction on improving memory and logic, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +1 to her Intelligence score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Because the tome of clear thought provides an inherent bonus, the reader will earn extra skill points when she attains a new level (unlike with the benefit provided by a headband of intellect). Strong evocation (if miracle is used); CL 17th

### Tome of Clear Thought +2

- **COST:** 55000
- **WT:** 5
- **SPROP:** This heavy book contains instruction on improving memory and logic, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +2 to her Intelligence score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Because the tome of clear thought provides an inherent bonus, the reader will earn extra skill points when she attains a new level (unlike with the benefit provided by a headband of intellect). Strong evocation (if miracle is used); CL 17th

### Tome of Clear Thought +3

- **COST:** 82500
- **WT:** 5
- **SPROP:** This heavy book contains instruction on improving memory and logic, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +3 to her Intelligence score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Because the tome of clear thought provides an inherent bonus, the reader will earn extra skill points when she attains a new level (unlike with the benefit provided by a headband of intellect). Strong evocation (if miracle is used); CL 17th

### Tome of Clear Thought +4

- **COST:** 110000
- **WT:** 5
- **SPROP:** This heavy book contains instruction on improving memory and logic, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +4 to her Intelligence score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Because the tome of clear thought provides an inherent bonus, the reader will earn extra skill points when she attains a new level (unlike with the benefit provided by a headband of intellect). Strong evocation (if miracle is used); CL 17th

### Tome of Clear Thought +5

- **COST:** 137500
- **WT:** 5
- **SPROP:** This heavy book contains instruction on improving memory and logic, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +5 to her Intelligence score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Because the tome of clear thought provides an inherent bonus, the reader will earn extra skill points when she attains a new level (unlike with the benefit provided by a headband of intellect). Strong evocation (if miracle is used); CL 17th

### Tome of Leadership and Influence +1

- **COST:** 27500
- **WT:** 5
- **SPROP:** This ponderous book details suggestions for persuading and inspiring others, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +1 to his Charisma score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th;

### Tome of Leadership and Influence +2

- **COST:** 55000
- **WT:** 5
- **SPROP:** This ponderous book details suggestions for persuading and inspiring others, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +2 to his Charisma score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th;

### Tome of Leadership and Influence +3

- **COST:** 82500
- **WT:** 5
- **SPROP:** This ponderous book details suggestions for persuading and inspiring others, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +3 to his Charisma score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th;

### Tome of Leadership and Influence +4

- **COST:** 110000
- **WT:** 5
- **SPROP:** This ponderous book details suggestions for persuading and inspiring others, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +4 to his Charisma score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th;

### Tome of Leadership and Influence +5

- **COST:** 137500
- **WT:** 5
- **SPROP:** This ponderous book details suggestions for persuading and inspiring others, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, he gains an inherent bonus of +5 to his Charisma score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th;

### Tome of Understanding +1

- **COST:** 27500
- **WT:** 5
- **SPROP:** This thick book contains tips for improving instinct and perception, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +1 to her Wisdom score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Tome of Understanding +2

- **COST:** 55000
- **WT:** 5
- **SPROP:** This thick book contains tips for improving instinct and perception, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +2 to her Wisdom score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Tome of Understanding +3

- **COST:** 82500
- **WT:** 5
- **SPROP:** This thick book contains tips for improving instinct and perception, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +3 to her Wisdom score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Tome of Understanding +4

- **COST:** 110000
- **WT:** 5
- **SPROP:** This thick book contains tips for improving instinct and perception, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +4 to her Wisdom score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Tome of Understanding +5

- **COST:** 137500
- **WT:** 5
- **SPROP:** This thick book contains tips for improving instinct and perception, but entwined within the words is a powerful magical effect. If anyone reads this book, which takes a total of 48 hours over a minimum of six days, she gains an inherent bonus of +5 to her Wisdom score. Once the book is read, the magic disappears from the pages and it becomes a normal book. Strong evocation (if miracle is used); CL 17th

### Unguent of Timelessness

- **COST:** 150
- **WT:** 0
- **SPROP:** When applied to any matter that was once alive (leather, leaves, paper, wood, dead flesh, and so on), this ointment allows that substance to resist the passage of time. Each year of actual time affects the substance as if only a day had passed. The coated object gains a +1 resistance bonus on all saving throws. The unguent never wears off, although it can be magically removed (by dispelling the effect, for instance). One flask contains enough material to coat eight Medium or smaller objects. A Large object counts as two Medium objects, and a Huge object counts as two Large objects. Faint transmutation; CL 3rd;

### Universal Solvent

- **COST:** 50
- **WT:** 0
- **SPROP:** This substance has the unique property of being able to dissolve sovereign glue (see page 266), tanglefoot bags (see page 128 of the Player's Handbook), and the adhesive created by a kuo-toa (see page 163 of the Monster Manual). Applying the solvent is a standard action. Strong transmutation; CL 20th

### Vest of Escape

- **COST:** 5200
- **WT:** 0
- **BONUS:** SKILL|Escape Artist|6|TYPE=Competence
- **BONUS:** SKILL|Open Lock|4|TYPE=Competence
- **SPROP:** Hidden within secret pockets of this simple silk vest are lockpicks that provide a +4 competence bonus on Open Lock checks. The vest also grants its wearer a +6 competence bonus on Escape Artist checks. Faint conjuration and transmutation; CL 4th

### Vestments, Druid

- **COST:** 10000
- **WT:** 0
- **BONUS:** VAR|WildShapeTimes|1
- **SPROP:** This light garment is worn over normal clothing or armor. Most such vestments are green, embroidered with plant or animal motifs. When this item is worn by a character with the wild shape ability, the character can use that ability one additional time each day. Moderate transmutation; CL 10th

### Well of Many Worlds

- **COST:** 82000
- **WT:** 0
- **SPROP:** This strange, interdimensional device looks just like a portable hole. Anything placed within it is immediately cast to another world-a parallel world, another planet, or a different plane, at the DM's option or by random determination. If the well is moved, the random factor again comes into play. It can be picked up, folded, or rolled, just as a portable hole can be. Objects from the world the well touches can come through the opening just as easily as from the initiating place. (It is a two-way portal.) Strong conjuration; CL 17th;

### Wind Fan

- **COST:** 5500
- **WT:** 0
- **SPROP:** A wind fan appears to be nothing more than a wood and papyrus or cloth instrument with which to create a cooling breeze. By uttering the command word, its possessor causes the fan to generate air movement duplicating a gust of wind spell. The fan can be used once per day with no risk. If it is used more frequently, there is a 20%% cumulative chance per usage during that day that the device tears into useless, nonmagical tatters. Faint evocation; CL 5th

### Wings of Flying

- **COST:** 54000
- **WT:** 2
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=17|Fly,13
- **SPROP:** A pair of these wings might appear to be nothing more than a plain cloak of old, black cloth, or they could be as elegant as a long cape of blue feathers. When the wearer speaks the command word, the cloak turns into a pair of bat or bird wings that empower her to fly with a speed of 60 feet (good maneuverability). Moderate transmutation; CL 10th;

### Periapt of the Night Hag (Heartstone)

- **COST:** 1800
- **WT:** 0
- **BONUS:** SAVE|Fortitude,Reflex,Will|2|TYPE=Resistance

### Bag (Coin)

- **CONTAINS:** 2|Any
- **COST:** 0.05
- **WT:** 0.25
- **SPROP:** for Robe of Useful Items.

### Coffer (Silver)

- **CONTAINS:** UNLIM|Any
- **COST:** 2
- **WT:** 3
- **SPROP:** for Robe of Useful Items. 6 in. by 6 in. by 1 ft.

### Dog (War)

- **CONTAINS:** *300|Any
- **COST:** 150
- **WT:** 0
- **SIZE:** M
- **SPROP:** for Robe of Useful Items. Treat as Dog (Riding)

### Door (Iron)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Useful Items. Up to 10 ft. wide and 10 ft. high and barred on one side--must be placed upright, attaches and hinges itself.

### Gem (Robe/100 gp)

- **COST:** 100
- **WT:** 0
- **SPROP:** for Robe of Useful Items.

### Ladder (24 Ft.)

- **COST:** 0.12
- **WT:** 48
- **SPROP:** for Robe of Useful Items.

### Mirror (Large/Steel/Highly Polished)

- **COST:** 100
- **WT:** 30
- **SPROP:** for Robe of Useful Items. 2 by 4 ft.

### Pit (Open)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Useful Items

### Window

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Useful Items. 2 ft. by 4 ft., up to 2 ft. deep

### Amulet of Inescapable Location

- **COST:** 1000
- **WT:** 0
- **SPROP:** Appears to be an Amulet of Proof against Detection and Location, but -10 penalty on all saves against divination spells.

### Armor of Arrow Attraction

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** MAGIC_COST|-1650.Masterwork (Armor).PLUS3A.STEEL
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** +3 in melee, -15 vs. ranged weapons

### Armor of Rage

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** MAGIC_COST|-1050.Masterwork (Armor).PLUS1A.STEEL
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **BONUS:** STAT|CHA|-4
- **SPROP:** All unfriendly characters within 300 feet have a +1 morale bonus on attack rolls against wearer.

### Bag of Devouring

- **CONTAINS:** *250
- **COST:** 0
- **WT:** 15
- **SPROP:** Appears to be a Bag of Holding (Type I).

### Boots of Dancing

- **COST:** 30000
- **WT:** 1
- **SLOTS:** 2
- **SPROP:** Wearer becomes victim of Irresistible Dance in combat.

### Bracers of Defenselessness

- **COST:** 1200
- **WT:** 1
- **SLOTS:** 2
- **BONUS:** COMBAT|AC|-5|TYPE=Armor
- **SPROP:** Appear to be Bracers of Defense +5

### Broom of Animated Attack

- **COST:** 5200
- **WT:** 3
- **SPROP:** Appears to be a Broom of Flying.

### Cloak of Poisonousness

- **COST:** 62000
- **WT:** 1

### Crystal Hypnosis Ball

- **COST:** 0
- **WT:** 7
- **SPROP:** Appears to be a normal Crystal Ball.

### Dust of Sneezing and Choking

- **COST:** 2400
- **WT:** 0
- **SPROP:** Appears to be Dust of Appearance.

### Flask of Curses

- **COST:** 2100
- **WT:** 1.5

### Gauntlets of Fumbling (Gloves)

- **COST:** 1300
- **WT:** 0
- **BONUS:** STAT|DEX|-2
- **SPROP:** Appear to be Gloves of Dexterity. Fumble held items 50%% of the time.

### Gauntlets of Fumbling (Gauntlets)

- **COST:** 1300
- **WT:** 4
- **BONUS:** STAT|DEX|-2
- **SPROP:** Appear to be Gauntlets of Ogre Power. Fumble held items 50%% of the time.

### Helm of Opposite Alignment

- **COST:** 4000
- **WT:** 3
- **SPROP:** Appears to be a typical helmet. Changes alignment to opposite (DC 15 Will negates).

### Incense of Obsession

- **COST:** 200
- **WT:** 1
- **SPROP:** Appears to be Incense of Meditation.

### Mace of Blood

- **PROFICIENCY:** WEAPON|Mace (Heavy)
- **COST:** 16000
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **SPROP:** Must be coated in blood every day, or its bonus fades away until the mace is coated again. DC 13 Will save every day it is possessed or become Chaotic Evil.

### Medallion of Thought Projection

- **COST:** 1800
- **WT:** 0
- **SPROP:** Appears to be a Medallion of Thoughts.

### Necklace of Strangulation

- **COST:** 60000
- **WT:** 0
- **SPROP:** Appears to be a rare and wondrous piece of valuable jewelry and, short of the use of something as powerful as a miracle or a wish, can only be identified as a cursed item when placed around a character's neck. The necklace immediately constricts, dealing 6 points of damage per round. It cannot be removed by any means short of a limited wish, wish, or miracle and remains clasped around the victim's throat even after his death. Only when he has decayed to a dry skeleton (after approximately one month) does the necklace loosen, ready for another victim

### Net of Snaring

- **PROFICIENCY:** WEAPON|Net
- **COST:** 10000
- **WT:** 6
- **EQMOD:** ROPE
- **RANGE:** 30
- **BONUS:** WEAPON|TOHIT|3|TYPE=Enhancement
- **SPROP:** May only be used underwater. 30 Ft. range.

### Periapt of Foul Rotting

- **COST:** 17000
- **WT:** 0
- **SPROP:** Appears as an engraved gem of little value.

### Potion (Poison)

- **COST:** 5000
- **WT:** 0

### Robe of Powerlessness

- **COST:** 5500
- **WT:** 1
- **BONUS:** STAT|STR|-10
- **BONUS:** STAT|INT|-10
- **SPROP:** Appears to be a magic robe of another sort.
- **SPROP:** Change Self at will

### Robe of Vermin

- **COST:** 16500
- **WT:** 1
- **BONUS:** COMBAT|INITIATIVE|-5
- **BONUS:** COMBAT|TOHIT|-2
- **BONUS:** SKILL|ALL|-2
- **SPROP:** Appears to offer great magical defence (+4 saves). Must make a Concentration check (DC 20 + SL) or lose the spell.
- **BONUS:** SAVE|ALL|-2

### Ring (Clumsiness)

- **COST:** 500
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Feather Fall
- **BONUS:** MISC|SPELLFAILURE|20
- **BONUS:** STAT|DEX|-4
- **SPROP:** Functions as a Ring of Feather Falling.

### Scarab of Death

- **COST:** 80000
- **WT:** 0
- **SPROP:** This small pin appears to be any one of the various beneficial amulets, brooches, or scarabs.

### Spear (Cursed Backbiter)

- **PROFICIENCY:** WEAPON|Shortspear
- **COST:** 7500
- **WT:** 3
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **EQMOD:** WOOD
- **WIELD:** OneHanded
- **RANGE:** 20
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** +2 Shortspear. Damages wielder on a natural 1.

### Stone of Weight (Loadstone)

- **COST:** 1000
- **WT:** 0
- **BONUS:** MOVEADD|TYPE.Walk|-(MOVEBASE/2)
- **SPROP:** Appears to be a dark, smoothly polished stone. Reduces base land speed 50%%.

### Sword -2 (Cursed)

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 1500
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|-2|TYPE=Enhancement
- **SPROP:** -2 to hit and damage (minimum 1 pt. damage).

### Sword (Berserking)

- **PROFICIENCY:** WEAPON|Greatsword
- **COST:** 17500
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 2d6
- **EQMOD:** STEEL
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **SPROP:** User gains all benefits and drawbacks of barbarian rage.
- **TEMPBONUS:** PC|SAVE|Will|2|TYPE=Morale
- **TEMPBONUS:** PC|COMBAT|AC|-2
- **TEMPBONUS:** PC|STAT|STR|4
- **TEMPBONUS:** PC|STAT|CON|4

### Vacuous Grimoire

- **COST:** 6000
- **WT:** 3
- **SPROP:** Appears like a normal book on some mildly interesting topic.

### Necklace of Fireballs Strand

- **CONTAINS:** 0|Consumable=9
- **COST:** 0
- **WT:** 0
- **SPROP:** Begins empty. May contain up to 9 Fireball Spheres
- **SORTKEY:** Necklace of Fireballs 0

### Necklace of Fireballs I 2

- **CONTAINS:** 0|Consumable=9
- **COST:** 1650
- **WT:** 0
- **SPROP:** 1-5d6 2-3d6 Fireballs - Value:1,650 gp
- **SORTKEY:** Necklace of Fireballs 1

### Necklace of Fireballs II 2

- **CONTAINS:** 0|Consumable=9
- **COST:** 2700
- **WT:** 0
- **SPROP:** 1-6d6 2-4d6 2-2d6 Fireballs - Value:2,700 gp
- **SORTKEY:** Necklace of Fireballs 2

### Necklace of Fireballs III 2

- **CONTAINS:** 0|Consumable=9
- **COST:** 4350
- **WT:** 0
- **SPROP:** 1-7d6 2-5d6 4-3d6 Fireballs - Value:4,350 gp
- **SORTKEY:** Necklace of Fireballs 3

### Necklace of Fireballs IV 2

- **CONTAINS:** 0|Consumable=9
- **COST:** 5400
- **WT:** 0
- **SPROP:** 1-8d6 2-6d6 2-4d6 4-2d6 Fireballs - Value:5,400 gp
- **SORTKEY:** Necklace of Fireballs 4

### Necklace of Fireballs V 2

- **CONTAINS:** 0|Consumable=9
- **COST:** 5850
- **WT:** 0
- **SPROP:** 1-9d6 2-7d6 2-5d6 2-3d6 Fireballs - Value:5,850 gp
- **SORTKEY:** Necklace of Fireballs 5

### Necklace of Fireballs VI 2

- **CONTAINS:** 0|Consumable=9
- **COST:** 8100
- **WT:** 0
- **SPROP:** 1-10d6 2-8d6 2-6d6 4-4d6 Fireballs - Value:8,100 gp
- **SORTKEY:** Necklace of Fireballs 6

### Necklace of Fireballs VII 2

- **CONTAINS:** 0|Consumable=9
- **COST:** 8700
- **WT:** 0
- **SPROP:** 1-10d6 2-9d6 2-7d6 2-5d6 2-3d6 Fireballs - Value:8,700 gp
- **SORTKEY:** Necklace of Fireballs 7

### Necklace of Fireballs Sphere 2d6

- **COST:** 300
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 02

### Necklace of Fireballs Sphere 3d6

- **COST:** 450
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 03

### Necklace of Fireballs Sphere 4d6

- **COST:** 600
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 04

### Necklace of Fireballs Sphere 5d6

- **COST:** 750
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 05

### Necklace of Fireballs Sphere 6d6

- **COST:** 900
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 06

### Necklace of Fireballs Sphere 7d6

- **COST:** 1050
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 07

### Necklace of Fireballs Sphere 8d6

- **COST:** 1200
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 08

### Necklace of Fireballs Sphere 9d6

- **COST:** 1350
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 09

### Necklace of Fireballs Sphere 10d6

- **COST:** 1500
- **WT:** 0
- **SPROP:** for Necklace of Fireballs
- **SORTKEY:** Necklace of Fireballs Sphere 10

### Robe of Stars 2

- **CONTAINS:** *3|Specific=6
- **COST:** 58000
- **WT:** 1
- **SPROP:** Allows Astral travel, contains 6 +5 Shuriken
- **BONUS:** SAVE|Fortitude,Will,Reflex|1|TYPE=Luck

### Robe of Stars Shuriken +5

- **PROFICIENCY:** WEAPON|Shuriken
- **COST:** 0
- **WT:** 0.1
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d2
- **EQMOD:** STEEL.THROWN_AMMO
- **WIELD:** Light
- **RANGE:** 10
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|5|TYPE=Enhancement

### Robe of Bones 2

- **CONTAINS:** *0|Consumable=12
- **COST:** 2400
- **WT:** 1

### Robe of Bones Skeleton (Goblin/Small)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Bones

### Robe of Bones Skeleton (Human Commoner/Medium)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Bones

### Robe of Bones Skeleton (Wolf/Medium)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Bones

### Robe of Bones Zombie (Goblin/Small)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Bones

### Robe of Bones Zombie (Human Commoner/Medium)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Bones

### Robe of Bones Zombie (Wolf/Medium)

- **COST:** 0
- **WT:** 0
- **SPROP:** for Robe of Bones

### Robe of Useful Items 2

- **CONTAINS:** *UNLIM|Any
- **COST:** 7000
- **WT:** 1
- **SPROP:** Equip with kit.

### Book of Exalted Deeds

- **COST:** 0
- **WT:** 3
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|1|!PRECLASS:1,SPELLCASTER=1
- **SPROP:** This holy book is sacred to divine spellcasters of good alignment (LG, NG, CG). Study of the work requires one week, but upon completion a good spellcaster gains a +1 inherent bonus to Wisdom and one experience level-receiving enough XP to put the character's XP total midway between the minimum needed for his new (higher) level and the minimum needed for the level beyond that. Divine spellcasters neither good nor evil (LN, N, CN) lose 2d6*1,000 XP for perusing the work. Evil divine spellcasters (LE, NE, CE) lose twice that amount. In addition, they have to atone (see the atonement spell) in order to gain further experience. Nonspellcasters who handle or read the book are unaffected. Arcane spellcasters who read it take 1 point of permanent Intelligence drain and lose 1d6*1,000 XP unless they make a DC 15 Will save. Except as indicated above, the writing in a book of exalted deeds can't be distinguished from any other magic book, libram, tome, or so on until perused. Once read, the book vanishes, and the same character can never benefit from reading another book of exalted deeds. Strong evocation [good]; CL 19th;

### Book of Infinite Spells

- **COST:** 0
- **WT:** 3
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|1|!PRECLASS:1,SPELLCASTER=1
- **SPROP:** This work bestows upon any character of any class the ability to use the spells within its pages. However, any character not already able to use spells gains one negative level for as long as the book is in her possession or while she uses its power. A book of infinite spells contains 1d8+22 pages. The nature of each page is determined by a dice roll: 01-50, arcane spell; 51-100, divine spell. Determine the exact spell by using the tables for determining major scroll spells (the third column on Table 7-22: Scroll Spell Levels, along with Table 7-23: Arcane Spell Scrolls and Table 7-24: Divine Spell Scrolls). Once a page is turned, it can never be flipped back-paging through a book of infinite spells is a one-way trip. If the book is closed, it always opens again to the page it was on before the book was closed. When the last page is turned, the book vanishes. Once per day the owner of the book can cast the spell to which the book is opened. If that spell happens to be one that is on the character's class spell list, she can cast it up to four times per day. The pages cannot be ripped out without destroying the book. Similarly, the spells cannot be cast as scroll spells, nor can they be copied into a spellbook-their magic is bound up permanently within the book itself. The owner of the book need not have the book on her person in order to use its power. The book can be stored in a place of safety while the owner is adventuring and still allow its owner to cast spells by means of its power. Each time a spell is cast, there is a chance that the energy connected with its use causes the page to magically turn despite all precautions. The owner knows this and may even benefit from the turning by gaining access to a new spell. The chance of a page turning depends on the spell the page contains and what sort of spellcaster the owner is. Treat each spell use as if a scroll were being employed, for purposes of determining casting time, spell failure, and so on. Strong (all schools); CL 18th

### Book of Vile Darkness

- **COST:** 0
- **WT:** 3
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** VAR|NegLevels|1|!PRECLASS:1,SPELLCASTER=1
- **SPROP:** This is a work of ineffable evil-meat and drink to divine spellcasters of that alignment (LE, NE, CE). To fully consume the contents requires one week of study. Once this has been accomplished, an evil spellcaster gains a +1 inherent bonus to Wisdom and one experience level-receiving enough XP to put the character's XP total midway between the minimum needed for his new (higher) level and the minimum needed for the level beyond that. All lawful neutral, neutral, or chaotic neutral characters who touch the book take 5d4 points of damage, and reading its pages causes them to become evil (Will DC 13 negates). Such converts immediately seek out an evil cleric to confirm their new alignment (with an atonement spell). Divine spellcasters neither good nor evil (LN, N, CN) who read the book either lose 2d6*1,000 XP (01-50 on d%%) or become evil without benefit from the book (51-100). Good divine spellcasters (LG, NG, CG) perusing the pages of the book of vile darkness have to make a DC 16 Fortitude save or die. If they do not die, they must succeed on a DC 15 Will save or suffer from a continuous confusion effect (per the insanity spell). In the latter event, even if the save is successful, the character loses 20,000 XP, minus 1,000 for each point of Wisdom he has. (This calculation cannot result in an XP gain.) Other characters of good alignment take 5d6 points of damage from just handling the tome. If such a character looks inside, there is an 80%% chance that an evil outsider attacks the character that night. Strong evocation [evil]; CL 19th

### Deck of Many Things

- **COST:** 0
- **WT:** 0
- **SPROP:** A deck of many things (both beneficial and baneful) is usually found in a box or leather pouch. Each deck contains a number of cards or plaques made of ivory or vellum. Each is engraved with glyphs, characters, and sigils. As soon as one of these cards is drawn from the pack, its magic is bestowed upon the person who drew it, for better or worse. The character with a deck of many things who wishes to draw a card must announce how many cards she will draw before she begins. Cards must be drawn within 1 hour of each other, and a character can never again draw from this deck any more cards than she has announced. If the character does not willingly draw her allotted number (or if she is somehow prevented from doing so), the cards flip out of the deck on their own. Exception: If the jester is drawn, the possessor of the deck may elect to draw two additional cards. Each time a card is taken from the deck, it is replaced (making it possible to draw the same card twice) unless the draw is the jester or the fool, in which case the card is discarded from the pack. A deck of many things contains 22 cards. To simulate the magic cards, you may want to use tarot cards, as indicated in the second column of the accompanying table. If no tarot deck is available, substitute ordinary playing cards instead, as indicated in the third column. The effects of each card, summarized on the table, are fully described below. Balance: As in "weighed in the balance and found wanting," the character must change to a radically different alignment. If the character fails to act according to the new alignment, she gains a negative level. Comet: The character must single-handedly defeat the next hostile monster or monsters encountered, or the benefit is lost. If successful, the character gains enough XP to attain the next experience level. Donjon: This card signifies imprisonment- either by the imprisonment spell or by some powerful being, at the DM's option. All gear and spells are stripped from the victim in any case. Whether these items are recoverable is, likewise, up to the DM. Draw no more cards. Euryale: The medusalike visage of this card brings a curse that only the fates card or a deity can remove. The -1 penalty on all saving throws is otherwise permanent. Fates: This card enables the character to avoid even an instantaneous occurrence if so desired, for the fabric of reality is unraveled and respun. Note that it does not enable something to happen. It can only stop something from happening or reverse a past occurrence. The reversal is only for the character who drew the card; other party members may have to endure the situation. Flames: Hot anger, jealousy, and envy are but a few of the possible motivational forces for the enmity. The enmity of the outsider can't be ended until one of the parties has been slain. Determine the outsider randomly, and assume that it attacks the character (or plagues her life in some way) within 1d20 days. Fool: The payment of XP and the redraw are mandatory. This card is always discarded when drawn, unlike all others except the jester. Gem: This card indicates wealth. The jewelry is all gold set with gems, each piece worth 2,000 gp, the gems 1,000 gp value each. Idiot: This card causes the drain of 1d4+1 points of Intelligence immediately. The additional draw is optional. Jester: This card is always discarded when drawn, unlike all others except the fool. The redraws are optional. Key: The magic weapon granted must be one usable by the character; use the weapon tables beginning with Table 7-10: Weapon Type Determination until a useful item is awarded. It suddenly appears out of nowhere in the character's hand. Knight: The fighter appears out of nowhere and serves loyally until death. He or she is of the same race (or kind) and gender as the character. (See Chapter 4 of this book for typical NPC statistics for a 4th-level fighter.) Moon: This card sometimes bears the image of a moonstone gem with the appropriate number of wishes shown as gleams therein; sometimes it depicts a moon with its phase indicating the number of wishes (full = four; gibbous = three; half = two; quarter = one). These wishes are the same as those granted by the 9th-level wizard spell and must be used within a number of minutes equal to the number received. Rogue: When this card is drawn, one of the character's NPC friends (preferably a cohort) is totally alienated and forever after hostile. If the character has no cohorts, the enmity of some powerful personage (or community, or religious order) can be substituted. The hatred is secret until the time is ripe for it to be revealed with devastating effect. Ruin: As implied by its name, when this card is drawn, all nonmagical possessions of the drawer are lost. Skull: A dread wraith (see page 258 of the Monster Manual) appears. Treat this creature as an unturnable undead. The character must fight it alone-if others help, they get dread wraiths to fight as well. If the character is slain, she is slain forever and cannot be revived, even with a wish or a miracle. Star: The 2 points are added to any ability the character chooses. They cannot be divided among two abilities. Sun: Roll for a medium wondrous item (Table 7-28: Medium Wondrous Items) until a useful item is indicated. Talons: When this card is drawn, every magic item owned or possessed by the character is instantly and irrevocably gone. Throne:The character becomes a true leader in people's eyes. The castle gained appears in any open area she wishes (but the decision where to place it must be made within 1 hour). Vizier: This card empowers the character drawing it with the one-time ability to call upon a source of wisdom to solve any single problem or answer fully any question upon her request. The query or request must be made within one year. Whether the information gained can be successfully acted upon is another question entirely. The Void: This black card spells instant disaster. The character's body continues to function, as though comatose, but her psyche is trapped in a prison somewhere-in an object on a far plane or planet, possibly in the possession of an outsider. A wish or a miracle does not bring the character back, instead merely revealing the plane of entrapment. Draw no more cards. Strong (all schools); CL 20th.

### Hammer of Thunderbolts

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 0
- **WT:** 15
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 4d6
- **EQMOD:** MAGIC_COST|-32300.PLUS3W.RETRN.STEEL
- **WIELD:** OneHanded
- **MODS:** NO
- **RANGE:** 30
- **SIZE:** L
- **BONUS:** WEAPON|DAMAGE,TOHIT|4|TYPE=Enhancement
- **SPROP:** This +3 Large returning warhammer deals 4d6 points of damage on any hit. Further, if the wielder wears a belt of giant Strength and gauntlets of ogre power and he knows that the hammer is a hammer of thunderbolts (not just a +3 warhammer), the weapon can be used to full effect: It gains a total +5 enhancement bonus, allows all belt and gauntlet bonuses to stack (only when using this weapon), and strikes dead any giant upon whom it scores a hit (Fortitude DC 20 negates the death effect but not the damage). When hurled, on a successful attack the hammer emits a great noise, like a clap of thunder, causing all creatures within 90 feet to be stunned for 1 round (Fortitude DC 15 negates). The hammer's range increment is 30 feet. Strong evocation, necromancy, and transmutation; CL 20th
- **SPROP:** Strikes dead any giant upon whom it scores a hit (Fort DC 20 negates the death effect but not the damage)
- **SPROP:** When hurled, on a successful attack the hammer emits a great noise causing all creatures within 90 feet to be stunned for 1 round (Fort DC 15 negates)

### Philosopher's Stone

- **COST:** 0
- **WT:** 3
- **SPROP:** This rare substance appears to be an ordinary, sooty piece of blackish rock. If the stone is broken open (break DC 20), a cavity is revealed at the stone's heart. This cavity is lined with a magical type of quicksilver that enables any arcane spellcaster to transmute base metals (iron and lead) into silver and gold. A single philosopher's stone can turn from up to 5,000 pounds of iron into silver, or up to 1,000 pounds of lead into gold. However, the quicksilver becomes unstable once the stone is opened and loses its potency within 24 hours, so all transmutations must take place within that period. The quicksilver found in the center of the stone may also be put to another use. If mixed with any cure potion while the substance is still potent, it creates a special oil of life that acts as a true resurrection spell for any dead body it is sprinkled upon. Strong transmutation; CL 20th;

### Sphere of Annihilation

- **COST:** 0
- **WT:** 0
- **SPROP:** A sphere of annihilation is a globe of absolute blackness, a ball of nothingness 2 feet in diameter. The object is actually a hole in the continuity of the multiverse. Any matter that comes in contact with a sphere is instantly sucked into the void, gone, and utterly destroyed. Only the direct intervention of a deity can restore an annihilated character. A sphere of annihilation is static, resting in some spot as if it were a normal hole. It can be caused to move, however, by mental effort (think of this as a mundane form of telekinesis, too weak to move actual objects but a force to which the sphere, being weightless, is sensitive). A character's ability to gain control of a sphere of annihilation (or to keep controlling one) is based on the result of a control check against DC 30 (a move action). A control check is 1d20 + character level + character Int modifier. If the check succeeds, the character can move the sphere (perhaps to bring it into contact with an enemy) as a free action. Control of a sphere can be established from as far away as 40 feet (the character need not approach too closely). Once control is established, it must be maintained by continuing to make control checks (all DC 30) each round. For as long as a character maintains control (does not fail a check) in subsequent rounds, he can control the sphere from a distance of 40 feet + 10 feet per character level. The sphere's speed in a round is 10 feet +5 feet for every 5 points by which the character's control check result in that round exceeded 30. If a control check fails, the sphere slides 10 feet in the direction of the character attempting to move it. If two or more creatures vie for control of a sphere of annihilation, the rolls are opposed. If none are successful, the sphere slips toward the one who rolled lowest. Should a gate spell be cast upon a sphere of annihilation, there is a 50%% chance (01-50 on d%%) that the spell destroys it, a 35%% chance (51-85) that the spell does nothing, and a 15%% chance (86-100) that a gap is torn in the spatial fabric, catapulting everything within a 180-foot radius into another plane (see page 151 for a way to determine this randomly). If a rod of cancellation touches a sphere of annihilation, they negate each other in a tremendous explosion. Everything within a 60-foot radius takes 2d6*10 points of damage. Dispel magic and Mordenkainen's disjunction have no effect on a sphere. See also talisman of the sphere (below). Strong transmutation; CL 20th.

### Staff of the Magi

- **COST:** 0
- **WT:** 5
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **BONUS:** MISC|SR|23
- **SPROP:** A long wooden staff, shod in iron and inscribed with sigils and runes of all types, this potent artifact contains many spell powers and other functions. Some of its powers use charges, while others don't. The following powers do not use charges: . Detect magic . Enlarge person (Fortitude DC 15 negates) . Hold portal . Light . Mage armor . Mage hand The following powers drain 1 charge per usage: . Dispel magic . Fireball (10d6 damage, Reflex DC 17 half ) . Ice storm . Invisibility . Knock . Lightning bolt (10d6 damage, Reflex DC 17 half ) . Passwall . Pyrotechnics (Will or Fortitude DC 16 negates) . Wall of fire . Web These powers drain 2 charges per usage: . Monster summoning IX . Plane shift (Will DC 21 negates) . Telekinesis (400 lb. maximum weight; Will DC 19 negates) A staff of the magi gives the wielder spell resistance 23. If this is willingly lowered, however, the staff can also be used to absorb arcane spell energy directed at its wielder, as a rod of absorption (page 234) does. Unlike the rod, this staff converts spell levels into charges rather than retaining them as spell energy usable by a spellcaster. If the staff absorbs enough spell levels to exceed its limit of 50 charges, it explodes as if a retributive strike had been performed (see below). The wielder has no idea how many spell levels are cast at her, for the staff does not communicate this knowledge as a rod of absorption does. (Thus, absorbing spells can be risky.) Retributive Strike: A staff of the magi can be broken for a retributive strike. Such an act must be purposeful and declared by the wielder. All charges in the staff are released in a 30-foot spread. All within 10 feet of the broken staff take hit points of damage equal to 8 times the number of charges in the staff, those between 11 feet and 20 feet away take points equal to 6 times the number of charges, and those 21 feet to 30 feet distant take 4 times the number of charges. A DC 17 Reflex save reduces damage by half. The character breaking the staff has a 50%% chance (01-50 on d%%) of traveling to another plane of existence (see Table 5-7, page 151), but if she does not (51-100), the explosive release of spell energy destroys her. Only specific items, including the staff of the magi and the staff of power (page 245), are capable of a retributive strike. Strong (all schools); CL 20th

### Talisman of Pure Good

- **COST:** 0
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_6|CHARGES[6]
- **SPROP:** A good (LG, NG, CG) divine spellcaster who possesses this item can cause a flaming crack to open at the feet of an evil (LE, NE, CE) divine spellcaster who is up to 100 feet away. The intended victim is swallowed up forever and sent hurtling to the center of the earth. The wielder of the talisman must be good, and if he is not exceptionally pure in thought and deed (DM's discretion), the evil character gains a DC 19 Reflex saving throw to leap away from the crack. Obviously, the target must be standing on solid ground for this item to function. (In the air, in a high tower, or on a ship are all places of safety against this otherwise potent item.) A talisman of pure good has 6 charges. If a neutral (LN, N, CN) divine spellcaster touches one of these stones, he takes 6d6 points of damage. If an evil divine spellcaster touches one, he takes 8d6 points of damage. All other characters are unaffected by the device. Strong evocation [good]; CL 18th.

### Talisman of the Sphere

- **COST:** 0
- **WT:** 0
- **SPROP:** This small adamantine loop and handle are useless to those unable to cast arcane spells. Characters who cannot cast arcane spells take 5d6 points of damage merely from picking up and holding a talisman of this sort. However, when held by an arcane spellcaster who is concentrating on control of a sphere of annihilation (page 279), a talisman of the sphere doubles the character's modifier on his control check (doubling both his Intelligence bonus and his character level for this purpose). If the wielder of a talisman establishes control, he need check for maintaining control only every other round thereafter. If control is not established, the sphere moves toward him. Note that while many spells and effects of cancellation have no effect upon a sphere of annihilation, the talisman's power of control can be suppressed or canceled. Strong transmutation; CL 16th;

### Talisman of Ultimate Evil

- **COST:** 0
- **WT:** 0
- **EQMOD:** CHARGED_ITEM_6|CHARGES[6]
- **SPROP:** An evil (LE, NE, CE) divine spellcaster who possesses this item can cause a flaming crack to open at the feet of a good (LG, NG, CG) divine spellcaster who is up to 100 feet away. The intended victim is swallowed up forever and sent hurtling to the center of the earth. The wielder of the talisman must be evil, and if she is not exceptionally foul and perverse in the sights of her evil deity (DM's discretion), the good character gains a DC 19 Reflex save to leap away from the crack. Obviously, the target must be standing on solid ground for this item to function. (In the air, in a high tower, or on a ship are all places of safety against this otherwise potent item.) A talisman of ultimate evil has 6 charges. If a neutral (LN, N, CN) divine spellcaster touches one of these stones, she takes 6d6 points of damage. If a good divine spellcaster touches one, she takes 8d6 points of damage. All other characters are unaffected by the device. Strong evocation [evil]; CL 18th.

### Talisman of Zagy

- **COST:** 0
- **WT:** 0
- **SPROP:** A talisman of this sort appears the same as a stone of controlling earth elementals. Its powers are quite different, however, and dependent on the Charisma of the individual holding the talisman. Whenever a character touches a talisman of Zagy, he must make a DC 15 Charisma check. If he fails, the device acts as a stone of weight (page 276). Discarding or destroying it results in 5d6 points of damage to the character and the disappearance of the talisman. If he succeeds, the talisman remains with the character for 5d6 hours, or until a wish is made with it, whichever comes first. It then disappears. If he rolls a natural 20, the character finds it impossible to be rid of the talisman for as many months as he has points of Charisma. In addition, the artifact grants him one wish for every 6 points of the character's Charisma. It also grows warm and throbs whenever its possessor comes within 20 feet of a mechanical or magic trap. (If the talisman is not held, its warning heat and pulses are of no avail.) Regardless of which reaction results, a talisman of Zagy disappears when its time period expires, leaving behind a 10,000 gp diamond in its stead. Strong conjuration; CL 20th;

### The Hand and Eye of Vecna

- **SPROP:** The archlich Vecna may have been the most powerful wizard ever to have lived. He may also have been the most evil. Apparently risen now to deityhood, he left behind relics embodying remnants of his power-the mummified remains of his hand and his eye. Powers of the Eye: In order to function, the Eye of Vecna must be placed in the empty socket of a character's skull. The bearer of the Eye loses 2 points of Charisma, and these points may never be restored. The Eye may not thereafter be removed without resulting in the death of its host. It grants the host continuous darkvision and true seeing. Three times per day each, the host can use the spells eyebite and domination. Once per day, the bearer of the Eye can call forth destruction and unhallow. A nonevil character must make a DC 17 Will save each week to avoid becoming evil. All powers are at caster level 20th, and all DCs to resist their effects are 20. Powers of the Hand: In order to function, the Hand of Vecna must be placed on the end of a left arm whose original hand has been severed. The bearer of the Hand loses 2 points of Dexterity that may never be regained. Removal of the hand thereafter always results in the death of the host. The touch of the Hand, once so placed, deals 1d10 points of cold damage to a target. Three times per day, its touch can permanently drain 1 ability score point (host's choice of ability) from a victim. The host gains the points drained for the rest of that day. (They last until the next sunrise.) Once per day, the bearer of the Hand can call upon blasphemy and unholy aura. A nonevil character must make a DC 17 Will save each week to avoid becoming evil. All powers are at caster level 20th, and all DCs to resist their effects are 20. Powers with Both Artifacts: If a single character bears both the Hand of Vecna and the Eye of Vecna, the DC to resist all powers of both items increases to 25. The host gains +2 to Strength and +2 to Intelligence but takes a -2 penalty to Wisdom. She can call upon summon monster IX once per day (to summon evil outsiders only). A nonevil character who possesses both items must make a DC 23 Will save each week to avoid becoming evil.

### The Mace of Cuthbert

- **PROFICIENCY:** WEAPON|Mace (Heavy)
- **COST:** 0
- **WT:** 3
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** DISRPT.HOLY_M.LAW_M.MAGIC_COST|-2420300.PLUS5W
- **WIELD:** OneHanded
- **MODS:** NO
- **SIZE:** M
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=20|Searing Light,14
- **SPROP:** St. Cuthbert, tales say, once walked the earth as a man. When he did, he used a potent weapon to strike against the infidels and evil beings he encountered everywhere he went. Today, this relic appears to be a simple, well-used cudgel, but its simple appearance hides great power. The Mace of Cuthbert has a +5 enhancement bonus and functions as a heavy mace with the holy, lawful, and disruption special abilities. The wielder can project searing light from the mace at will, at caster level 20th.
- **SPROP:** A simple, well-used cudgel

### Moaning Diamond

- **COST:** 0
- **WT:** 0
- **SPROP:** Said to have been ripped from the ground in a ritual that tortured the earth itself, the Moaning Diamond appears to be an uncut diamond the size of a human fist. At all times, it gives forth a baleful moaning sound, as if in pain. Despite the noise, the Moaning Diamond is not evil (although it was birthed in torture). The wielder of the stone can, three times per day, call upon it to reshape earth and stone as if by the spell stone shape, affecting 5,000 cubic feet of material. The Moaning Diamond can summon an elder earth elemental with maximum hit points that serves the caster until it is slain. Only one such elemental can be summoned at a time; if it is slain, a new creature cannot be summoned for 24 hours. Tales from the past tell of the Moaning Diamond creating stone structures, opening underground chambers where there had been none before, and collapsing entire castles.
- **SPROP:** Can summon an elder earth elemental with max HP that serves the caster until it is slain. Only one such elemental can be summoned at a time; if it is slain, a new creature cannot be summoned for 24 hours.

### Orb of Dragonkind (Black)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Fly,17
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Fly (Will DC 17 negates).

### Orb of Dragonkind (Blue)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Haste,17
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Haste (Fortitude DC 17 negates).

### Orb of Dragonkind (Brass)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Teleport,19
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Teleport (Will DC 19 negates).

### Orb of Dragonkind (Bronze)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Scrying,18
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Scrying (Will DC 18 negates).

### Orb of Dragonkind (Copper)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Suggestion,17
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Suggestion (Will DC 17 negates).

### Orb of Dragonkind (Gold)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=10|Cure Critical Wounds,18|Fly,17|Haste,17|Protection from Energy,17|Scrying,18|Spectral Hand|Suggestion,17|Teleport,19|Wall of Fire
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. The owner of the gold Orb can call upon any power possessed by one of the other Orbs-including the dominate and breath weapon abilities but not AC, save bonuses, or breath weapon immunity-but can only use an individual power once per day. She can use dominate on any other possessor of an Orb within 1 mile (Will DC 23 negates)

### Orb of Dragonkind (Green)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Spectral Hand
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Spectral hand.

### Orb of Dragonkind (Red)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Wall of Fire
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Wall of fire.

### Orb of Dragonkind (Silver)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Cure Critical Wounds,18
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Cure critical wounds (Will DC 18 half ).

### Orb of Dragonkind (White)

- **COST:** 0
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|TIMEUNIT=Round|CASTERLEVEL=10|Protection from Energy,17
- **SPROP:** These fabled Orbs were created eons ago in order to master dragons in the great Dragon Wars. Each contains the essence and personality of an ancient dragon of a different variety (one for each of the major ten different chromatic and metallic dragons). The bearer of an Orb can dominate dragons of its particular variety within 500 feet (as dominate monster), the dragon being forced to make a DC 25 Will save to resist. (Spell resistance is not useful against this effect.) Each Orb of Dragonkind bestows upon the wielder the AC and saving throw bonuses of the dragon within (see the Monster Manual for details on each dragon variety). These values replace whatever values the character would otherwise have, whether they are better or worse. These values cannot be modified by any means short of ridding the character of the Orb. A character possessing an Orb of Dragonkind is immune to the breath weapon-but only the breath weapon-of the dragon variety keyed to the Orb. Thus, the possessor of the Red Dragon Orb of Dragonkind is immune to red dragon breath, but not fire of any other sort. Finally, a character possessing an Orb can herself use the breath weapon of the dragon in the Orb three times per day (see the Monster Manual). All Orbs of Dragonkind can be used to communicate verbally and visually with the possessors of the other Orbs. The owner of an Orb knows whether there are dragons within 10 miles at all times. For dragons of the Orb's particular variety, the range is 100 miles. If within 1 mile of a dragon of the Orb's variety, the wielder can determine the exact location and age of the creature. The bearer of one of these Orbs earns the enmity forever of all dragonkind for profiting by the enslavement of one of their kin, even if she later loses the item. Each Orb also has an individual power that can be invoked once per round at 10th caster level. Protection from energy (cold) (Fortitude DC 17 negates).

### Shadowstaff

- **COST:** 0
- **WT:** 0
- **BONUS:** COMBAT|AC|4
- **SPROP:** This artifact was crafted centuries ago, weaving together the wispy strands of shadow itself into a twisted black staff. The Shadowstaff makes the wielder slightly shadowy and incorporeal, granting him a +4 bonus to AC and Reflex saves (which stacks with any other bonuses). However, in bright light (such as that of the sun, but not a torch) or in absolute darkness, the wielder takes a -2 penalty on all attack rolls, saves, and checks. The Shadowstaff also has these powers. . Summon Shadows: Three times per day the staff may summon 2d4 shadows (see page 221 of the Monster Manual). Immune to turning, they serve the wielder as if called by a summon monster V spell cast at 20th level. . Summon Nightshade: Once per month, the staff can summon a nightcrawler nightshade (see page 195 of the Monster Manual) that serves the wielder as if called by a summon monster IX spell cast at 20th level. . Shadow Form: Three times per day the wielder can become a living shadow, with all the movement powers granted by the gaseous form spell. . Shadow Bolt: Three times per day the staff can project a ray attack that deals 10d6 points of cold damage to a single target. The shadow bolt has a range of 100 feet.
- **BONUS:** SAVE|Reflex|4

### The Shield of the Prator

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 0
- **WT:** 15
- **ACCHECK:** -2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **EQMOD:** MAGIC_COST|-25150.PLUS5S.STEEL
- **SIZE:** M
- **SPELLFAILURE:** 15
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels
- **BONUS:** COMBAT|AC|2|TYPE=Shield
- **BONUS:** VAR|NegLevels|4
- **SPROP:** A hero of old, the paladin Prator bore this relic in many a valiant battle. The Shield of Prator disappeared when Prator fell in the Battle of the Three Hells, although it has reportedly surfaced briefly from time to time since then. This +5 large shield, emblazoned with the symbol of the sun, allows the wielder to cast spells as if she were a 20th-level paladin with a Wisdom score of 20. The spells gained are cumulative with any existing spells per day that the character might have, even if she's already a paladin. The Shield of Prator also grants spell resistance 15 to its wielder. It absorbs the first 10 points of damage from any energy attack (fire, cold, acid, electricity, or sonic). In return for all this, once per year the shield's owner must undertake a quest (no saving throw to avoid) at the behest of a lawful good deity. A character who is evil or chaotic (LE, NE, CE, CN, CG) gains four negative levels if she attempts to use this artifact. Although these negative levels never results in actual level loss, they remain as long as the shield is in hand and cannot be overcome in any way (including restoration spells). The negative levels disappear when the shield is stowed or leaves the wearer's possession.
- **SPROP:** Allows the wielder to cast spells as if she were a 20th-level paladin with a Wisdom score of 20.

### The Sword of Kas

- **SPROP:** The vampire Kas was the dreaded lieutenant of Vecna. He used this mighty blade, created by his master, to betray and attack the archlich, cutting off his hand and eye in a terrible battle before Vecna destroyed him. Only his sword survived, and it is said to forever seek vengeance against Vecna. The Sword of Kas is a +6 unholy keen vorpal longsword. It grants the wielder a +10 enhancement bonus to Strength. The sword is intelligent (Int 15, Wis 13, Cha 16, Ego 34) and chaotic evil. It can be used to cast the following spells, once per day each: call lightning (10d6 points of damage, Reflex DC 14 half ), blasphemy, and unhallow. Once per week it can be used to slay living.

## Equipment Modifiers

### Thrown Ammunition

- **COST:** 0
- **BONUS:** ITEMCOST|TYPE.Masterwork|-294
- **BONUS:** ITEMCOST|TYPE.Adamantine|-2646
- **BONUS:** ITEMCOST|TYPE.Silver|-18
- **BONUS:** ITEMCOST|TYPE.Mithral|319
- **BONUS:** ITEMCOST|TYPE.ColdIron|-1960
- **BONUS:** ITEMCOST|TYPE.Enhancement|(40*PLUSTOTAL*PLUSTOTAL)-(2000*PLUSTOTAL*PLUSTOTAL)|!PRETYPE:1,Epic
- **BONUS:** ITEMCOST|TYPE.Enhancement|(400*PLUSTOTAL*PLUSTOTAL)-(20000*PLUSTOTAL*PLUSTOTAL)

### Gem Value

- **NAMEOPT:** NOTHING
- **COST:** 0
- **PRETYPE:** 1,Gem
- **BONUS:** ITEMCOST|TYPE.Gem|%CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=8000|TITLE=Gem Value
- **CHOOSE:** NUMBER|MIN=1|MAX=8000|TITLE=Gem Value

### Art Value

- **NAMEOPT:** NOTHING
- **COST:** 0
- **PRETYPE:** 1,Art
- **BONUS:** ITEMCOST|TYPE.Art|%CHOICE
- **CHOOSE:** NUMBER|MIN=10|MAX=12000|TITLE=Art Value
- **CHOOSE:** NUMBER|MIN=10|MAX=12000|TITLE=Art Value

### Spell Material Component Value

- **NAMEOPT:** NOTHING
- **COST:** 0
- **PRETYPE:** 1,MaterialComponent
- **BONUS:** ITEMCOST|TYPE.MaterialComponent|%CHOICE
- **CHOOSE:** NUMBER|MIN=0|MAX=50000|TITLE=Material Component Value
- **CHOOSE:** NUMBER|MIN=0|MAX=50000|TITLE=Material Component Value

### Spell Focus Value

- **NAMEOPT:** NOTHING
- **COST:** 0
- **PRETYPE:** 1,SpellFocus
- **BONUS:** ITEMCOST|TYPE.SpellFocus|%CHOICE
- **CHOOSE:** NUMBER|MIN=0|MAX=10000|TITLE=Spell Focus Value
- **CHOOSE:** NUMBER|MIN=0|MAX=10000|TITLE=Spell Focus Value

### Trap Alchemical Effect Lvl 1

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_3,TRAP_ALCH_4,TRAP_ALCH_5,TRAP_ALCH_6,TRAP_ALCH_7,TRAP_ALCH_8,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Alchemical Effect Lvl 1
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 2

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_1,TRAP_ALCH_3,TRAP_ALCH_4,TRAP_ALCH_5,TRAP_ALCH_6,TRAP_ALCH_7,TRAP_ALCH_8,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Alchemical Effect Lvl 2
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 3

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_1,TRAP_ALCH_4,TRAP_ALCH_5,TRAP_ALCH_6,TRAP_ALCH_7,TRAP_ALCH_8,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Alchemical Effect Lvl 3
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 4

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_3,TRAP_ALCH_1,TRAP_ALCH_5,TRAP_ALCH_6,TRAP_ALCH_7,TRAP_ALCH_8,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|4
- **SPROP:** Trap Alchemical Effect Lvl 4
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 5

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_3,TRAP_ALCH_4,TRAP_ALCH_1,TRAP_ALCH_6,TRAP_ALCH_7,TRAP_ALCH_8,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|5
- **SPROP:** Trap Alchemical Effect Lvl 5
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 6

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_3,TRAP_ALCH_4,TRAP_ALCH_5,TRAP_ALCH_1,TRAP_ALCH_7,TRAP_ALCH_8,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|6
- **SPROP:** Trap Alchemical Effect Lvl 6
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 7

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_3,TRAP_ALCH_4,TRAP_ALCH_5,TRAP_ALCH_6,TRAP_ALCH_1,TRAP_ALCH_8,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|7
- **SPROP:** Trap Alchemical Effect Lvl 7
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 8

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_3,TRAP_ALCH_4,TRAP_ALCH_5,TRAP_ALCH_6,TRAP_ALCH_7,TRAP_ALCH_1,TRAP_ALCH_9
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|8
- **SPROP:** Trap Alchemical Effect Lvl 8
- **DEFINE:** TrapCR|0

### Trap Alchemical Effect Lvl 9

- **COST:** 0
- **ITYPE:** TrapAddOn.Alchemical
- **REPLACES:** TRAP_ALCH_2,TRAP_ALCH_3,TRAP_ALCH_4,TRAP_ALCH_5,TRAP_ALCH_6,TRAP_ALCH_7,TRAP_ALCH_8,TRAP_ALCH_1
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|9
- **SPROP:** Trap Alchemical Effect Lvl 9
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 0

- **COST:** -1000
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-2
- **SPROP:** Trap Attack Bonus 0
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 1

- **COST:** -900
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Attack Bonus 1
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 2

- **COST:** -800
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Attack Bonus 2
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 3

- **COST:** -700
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Attack Bonus 3
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 4

- **COST:** -600
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Attack Bonus 4
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 5

- **COST:** -500
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Attack Bonus 5
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 6

- **COST:** -400
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 6

### Trap Attack Bonus 7

- **COST:** -300
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 7

### Trap Attack Bonus 8

- **COST:** -200
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 8

### Trap Attack Bonus 9

- **COST:** -100
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 9

### Trap Attack Bonus 10

- **COST:** 0
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 10

### Trap Attack Bonus 11

- **COST:** 200
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 11

### Trap Attack Bonus 12

- **COST:** 400
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 12

### Trap Attack Bonus 13

- **COST:** 600
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 13

### Trap Attack Bonus 14

- **COST:** 800
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Attack Bonus 14

### Trap Attack Bonus 15

- **COST:** 1000
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Attack Bonus 15
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 16

- **COST:** 1200
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Attack Bonus 16
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 17

- **COST:** 1400
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Attack Bonus 17
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 18

- **COST:** 1600
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Attack Bonus 18
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 19

- **COST:** 1800
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Attack Bonus 19
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 20

- **COST:** 2000
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Attack Bonus 20
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 21

- **COST:** 2200
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Attack Bonus 21
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 22

- **COST:** 2400
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Attack Bonus 22
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 23

- **COST:** 2600
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Attack Bonus 23
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 24

- **COST:** 2800
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_0,TRAP_ATK_BONUS_25
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Attack Bonus 24
- **DEFINE:** TrapCR|0

### Trap Attack Bonus 25

- **COST:** 3000
- **ITYPE:** TrapAddOn.AttackBonus
- **REPLACES:** TRAP_ATK_BONUS_1,TRAP_ATK_BONUS_2,TRAP_ATK_BONUS_3,TRAP_ATK_BONUS_4,TRAP_ATK_BONUS_5,TRAP_ATK_BONUS_6,TRAP_ATK_BONUS_7,TRAP_ATK_BONUS_8,TRAP_ATK_BONUS_9,TRAP_ATK_BONUS_10,TRAP_ATK_BONUS_11,TRAP_ATK_BONUS_12,TRAP_ATK_BONUS_13,TRAP_ATK_BONUS_14,TRAP_ATK_BONUS_15,TRAP_ATK_BONUS_16,TRAP_ATK_BONUS_17,TRAP_ATK_BONUS_18,TRAP_ATK_BONUS_19,TRAP_ATK_BONUS_20,TRAP_ATK_BONUS_21,TRAP_ATK_BONUS_22,TRAP_ATK_BONUS_23,TRAP_ATK_BONUS_24,TRAP_ATK_BONUS_0
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Attack Bonus 25
- **DEFINE:** TrapCR|0

### Trap Average Damage 7

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Average Damage 7
- **DEFINE:** TrapCR|0

### Trap Average Damage 14

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_7,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Average Damage 14
- **DEFINE:** TrapCR|0

### Trap Average Damage 21

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_7,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Average Damage 21
- **DEFINE:** TrapCR|0

### Trap Average Damage 28

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_7,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|4
- **SPROP:** Trap Average Damage 28
- **DEFINE:** TrapCR|0

### Trap Average Damage 35

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_7,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|5
- **SPROP:** Trap Average Damage 35
- **DEFINE:** TrapCR|0

### Trap Average Damage 42

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_7,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|6
- **SPROP:** Trap Average Damage 42
- **DEFINE:** TrapCR|0

### Trap Average Damage 49

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_7,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|7
- **SPROP:** Trap Average Damage 49
- **DEFINE:** TrapCR|0

### Trap Average Damage 56

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_7,TRAP_AVG_DMG_63,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|8
- **SPROP:** Trap Average Damage 56
- **DEFINE:** TrapCR|0

### Trap Average Damage 63

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_7,TRAP_AVG_DMG_70
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|9
- **SPROP:** Trap Average Damage 63
- **DEFINE:** TrapCR|0

### Trap Average Damage 70

- **COST:** 0
- **ITYPE:** TrapAddOn.AveDamage
- **REPLACES:** TRAP_AVG_DMG_14,TRAP_AVG_DMG_21,TRAP_AVG_DMG_28,TRAP_AVG_DMG_35,TRAP_AVG_DMG_42,TRAP_AVG_DMG_49,TRAP_AVG_DMG_56,TRAP_AVG_DMG_63,TRAP_AVG_DMG_7
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|10
- **SPROP:** Trap Average Damage 70
- **DEFINE:** TrapCR|0

### Trap Bypass - Hidden Lock

- **COST:** 300
- **ITYPE:** TrapAddOn.Bypass
- **REPLACES:** TRAP_BYPASS_HIDSWC,TRAP_BYPASS_LOCK
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Bypass - Hidden Lock

### Trap Bypass - Hidden Switch

- **COST:** 200
- **ITYPE:** TrapAddOn.Bypass
- **REPLACES:** TRAP_BYPASS_HIDLOCK,TRAP_BYPASS_LOCK
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Bypass - Hidden Switch

### Trap Bypass - Lock

- **COST:** 100
- **ITYPE:** TrapAddOn.Bypass
- **REPLACES:** TRAP_BYPASS_HIDSWC,TRAP_BYPASS_HIDLOCK
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Bypass - Lock

### Trap Disable DC 13

- **COST:** -700
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Disable DC 13
- **DEFINE:** TrapCR|0

### Trap Disable DC 14

- **COST:** -600
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Disable DC 14
- **DEFINE:** TrapCR|0

### Trap Disable DC 15

- **COST:** -500
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Disable DC 15
- **DEFINE:** TrapCR|0

### Trap Disable DC 16

- **COST:** -400
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 16

### Trap Disable DC 17

- **COST:** -300
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 17

### Trap Disable DC 18

- **COST:** -200
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 18

### Trap Disable DC 19

- **COST:** -100
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 19

### Trap Disable DC 20

- **COST:** 0
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 20

### Trap Disable DC 21

- **COST:** 200
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 21

### Trap Disable DC 22

- **COST:** 400
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 22

### Trap Disable DC 23

- **COST:** 600
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 23

### Trap Disable DC 24

- **COST:** 800
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Disable DC 24

### Trap Disable DC 25

- **COST:** 1000
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Disable DC 25
- **DEFINE:** TrapCR|0

### Trap Disable DC 26

- **COST:** 1200
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Disable DC 26
- **DEFINE:** TrapCR|0

### Trap Disable DC 27

- **COST:** 1400
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Disable DC 27
- **DEFINE:** TrapCR|0

### Trap Disable DC 28

- **COST:** 1600
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Disable DC 28
- **DEFINE:** TrapCR|0

### Trap Disable DC 29

- **COST:** 1800
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Disable DC 29
- **DEFINE:** TrapCR|0

### Trap Disable DC 30

- **COST:** 2000
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Disable DC 30
- **DEFINE:** TrapCR|0

### Trap Disable DC 31

- **COST:** 2200
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Disable DC 31
- **DEFINE:** TrapCR|0

### Trap Disable DC 32

- **COST:** 2400
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Disable DC 32
- **DEFINE:** TrapCR|0

### Trap Disable DC 33

- **COST:** 2600
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Disable DC 33
- **DEFINE:** TrapCR|0

### Trap Disable DC 34

- **COST:** 2800
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_13,TRAP_DISABLE_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Disable DC 34
- **DEFINE:** TrapCR|0

### Trap Disable DC 35

- **COST:** 3000
- **ITYPE:** TrapAddOn.DisableDC
- **REPLACES:** TRAP_DISABLE_DC_14,TRAP_DISABLE_DC_15,TRAP_DISABLE_DC_16,TRAP_DISABLE_DC_17,TRAP_DISABLE_DC_18,TRAP_DISABLE_DC_19,TRAP_DISABLE_DC_20,TRAP_DISABLE_DC_21,TRAP_DISABLE_DC_22,TRAP_DISABLE_DC_23,TRAP_DISABLE_DC_24,TRAP_DISABLE_DC_25,TRAP_DISABLE_DC_26,TRAP_DISABLE_DC_27,TRAP_DISABLE_DC_28,TRAP_DISABLE_DC_29,TRAP_DISABLE_DC_30,TRAP_DISABLE_DC_31,TRAP_DISABLE_DC_32,TRAP_DISABLE_DC_33,TRAP_DISABLE_DC_34,TRAP_DISABLE_DC_13
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Disable DC 35
- **DEFINE:** TrapCR|0

### Trap Damage Bonus Melee +1

- **COST:** 100
- **ITYPE:** TrapAddOn.MeleeDamage
- **REPLACES:** TRAP_DMG_BONUS_MLE_2,TRAP_DMG_BONUS_MLE_3,TRAP_DMG_BONUS_MLE_4,TRAP_DMG_BONUS_MLE_5,TRAP_DMG_BONUS_MLE_6,TRAP_DMG_BONUS_MLE_7,TRAP_DMG_BONUS_MLE_8
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +1

### Trap Damage Bonus Melee +2

- **COST:** 200
- **ITYPE:** TrapAddOn.DamageBonus
- **REPLACES:** TRAP_DMG_BONUS_MLE_1,TRAP_DMG_BONUS_MLE_3,TRAP_DMG_BONUS_MLE_4,TRAP_DMG_BONUS_MLE_5,TRAP_DMG_BONUS_MLE_6,TRAP_DMG_BONUS_MLE_7,TRAP_DMG_BONUS_MLE_8
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +2

### Trap Damage Bonus Melee +3

- **COST:** 300
- **ITYPE:** TrapAddOn.DamageBonusMelee
- **REPLACES:** TRAP_DMG_BONUS_MLE_2,TRAP_DMG_BONUS_MLE_1,TRAP_DMG_BONUS_MLE_4,TRAP_DMG_BONUS_MLE_5,TRAP_DMG_BONUS_MLE_6,TRAP_DMG_BONUS_MLE_7,TRAP_DMG_BONUS_MLE_8
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +3

### Trap Damage Bonus Melee +4

- **COST:** 400
- **ITYPE:** TrapAddOn.DamageBonusMelee
- **REPLACES:** TRAP_DMG_BONUS_MLE_2,TRAP_DMG_BONUS_MLE_3,TRAP_DMG_BONUS_MLE_1,TRAP_DMG_BONUS_MLE_5,TRAP_DMG_BONUS_MLE_6,TRAP_DMG_BONUS_MLE_7,TRAP_DMG_BONUS_MLE_8
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +4

### Trap Damage Bonus Melee +5

- **COST:** 500
- **ITYPE:** TrapAddOn.DamageBonusMelee
- **REPLACES:** TRAP_DMG_BONUS_MLE_2,TRAP_DMG_BONUS_MLE_3,TRAP_DMG_BONUS_MLE_4,TRAP_DMG_BONUS_MLE_1,TRAP_DMG_BONUS_MLE_6,TRAP_DMG_BONUS_MLE_7,TRAP_DMG_BONUS_MLE_8
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +5

### Trap Damage Bonus Melee +6

- **COST:** 600
- **ITYPE:** TrapAddOn.DamageBonusMelee
- **REPLACES:** TRAP_DMG_BONUS_MLE_2,TRAP_DMG_BONUS_MLE_3,TRAP_DMG_BONUS_MLE_4,TRAP_DMG_BONUS_MLE_5,TRAP_DMG_BONUS_MLE_1,TRAP_DMG_BONUS_MLE_7,TRAP_DMG_BONUS_MLE_8
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +6

### Trap Damage Bonus Melee +7

- **COST:** 700
- **ITYPE:** TrapAddOn.DamageBonusMelee
- **REPLACES:** TRAP_DMG_BONUS_MLE_2,TRAP_DMG_BONUS_MLE_3,TRAP_DMG_BONUS_MLE_4,TRAP_DMG_BONUS_MLE_5,TRAP_DMG_BONUS_MLE_6,TRAP_DMG_BONUS_MLE_1,TRAP_DMG_BONUS_MLE_8
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +7

### Trap Damage Bonus Melee +8

- **COST:** 800
- **ITYPE:** TrapAddOn.DamageBonusMelee
- **REPLACES:** TRAP_DMG_BONUS_MLE_2,TRAP_DMG_BONUS_MLE_3,TRAP_DMG_BONUS_MLE_4,TRAP_DMG_BONUS_MLE_5,TRAP_DMG_BONUS_MLE_6,TRAP_DMG_BONUS_MLE_7,TRAP_DMG_BONUS_MLE_1
- **PRETYPE:** 2,Mechanical,Melee
- **SPROP:** Trap Damage BONUS Melee +8

### Trap Damage Bonus Ranged +1

- **COST:** 100
- **ITYPE:** TrapAddOn.RangedDamage
- **REPLACES:** TRAP_DMG_BONUS_RNGD_2,TRAP_DMG_BONUS_RNGD_3,TRAP_DMG_BONUS_RNGD_4
- **PRETYPE:** 2,Mechanical,Ranged
- **SPROP:** Trap Damage BONUS Ranged +1

### Trap Damage Bonus Ranged +2

- **COST:** 200
- **ITYPE:** TrapAddOn.DamageBonus
- **REPLACES:** TRAP_DMG_BONUS_RNGD_1,TRAP_DMG_BONUS_RNGD_3,TRAP_DMG_BONUS_RNGD_4
- **PRETYPE:** 2,Mechanical,Ranged
- **SPROP:** Trap Damage BONUS Ranged +2

### Trap Damage Bonus Ranged +3

- **COST:** 300
- **ITYPE:** TrapAddOn.DamageBonusRanged
- **REPLACES:** TRAP_DMG_BONUS_RNGD_2,TRAP_DMG_BONUS_RNGD_1,TRAP_DMG_BONUS_RNGD_4
- **PRETYPE:** 2,Mechanical,Ranged
- **SPROP:** Trap Damage BONUS Ranged +3

### Trap Damage Bonus Ranged +4

- **COST:** 400
- **ITYPE:** TrapAddOn.DamageBonusRanged
- **REPLACES:** TRAP_DMG_BONUS_RNGD_2,TRAP_DMG_BONUS_RNGD_3,TRAP_DMG_BONUS_RNGD_1
- **PRETYPE:** 2,Mechanical,Ranged
- **SPROP:** Trap Damage BONUS Ranged +4

### Trap Reset - Automatic

- **COST:** 500
- **ITYPE:** TrapAddOn.Automatic
- **REPLACES:** TRAP_MECH_RESET_MANL,TRAP_MECH_RESET_REPAIR,TRAP_RESET_NONE
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reset - Automatic

### Trap Reset - Manual

- **COST:** 0
- **ITYPE:** TrapAddOn.Reset
- **REPLACES:** TRAP_MECH_RESET_AUTO,TRAP_MECH_RESET_REPAIR,TRAP_RESET_NONE
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reset - Manual

### Trap Reset - Repair

- **COST:** -200
- **ITYPE:** TrapAddOn.Reset
- **REPLACES:** TRAP_MECH_RESET_MANL,TRAP_MECH_RESET_AUTO,TRAP_RESET_NONE
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reset - Repair

### Trap Reset - None

- **COST:** -500
- **ITYPE:** TrapAddOn.Reset
- **REPLACES:** TRAP_MECH_RESET_MANL,TRAP_MECH_RESET_REPAIR,TRAP_MECH_RESET_AUTO
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reset - None

### Trap Trigger - Location

- **COST:** 0
- **ITYPE:** TrapAddOn.Trigger
- **REPLACES:** TRAP_MECH_TRIGGER_TIMED,TRAP_MECH_TRIGGER_TOUCH,TRAP_MECH_TRIGGER_TOUCH_ATTCHD,TRAP_TRIG_PROX
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Trigger - Location

### Trap Trigger - Timed

- **COST:** 1000
- **ITYPE:** TrapAddOn.Trigger
- **REPLACES:** TRAP_MECH_TRIGGER_LCTN,TRAP_MECH_TRIGGER_TOUCH,TRAP_MECH_TRIGGER_TOUCH_ATTCHD,TRAP_TRIG_PROX
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Trigger - Timed

### Trap Trigger - Touch

- **COST:** 0
- **ITYPE:** TrapAddOn.Trigger
- **REPLACES:** TRAP_MECH_TRIGGER_TIMED,TRAP_MECH_TRIGGER_LCTN,TRAP_MECH_TRIGGER_TOUCH_ATTCHD,TRAP_TRIG_PROX
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Trigger - Touch

### Trap Trigger - Touch (attached)

- **COST:** -100
- **ITYPE:** TrapAddOn.Trigger
- **REPLACES:** TRAP_MECH_TRIGGER_TIMED,TRAP_MECH_TRIGGER_TOUCH,TRAP_MECH_TRIGGER_LCTN,TRAP_TRIG_PROX
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Trigger - Touch (attached)

### Trap Trigger - Proximity

- **COST:** 1000
- **ITYPE:** TrapAddOn.Trigger
- **REPLACES:** TRAP_MECH_TRIGGER_TIMED,TRAP_MECH_TRIGGER_TOUCH,TRAP_MECH_TRIGGER_TOUCH_ATTCHD,TRAP_MECH_TRIGGER_LCTN
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Trigger - Proximity

### Trap Liquid

- **COST:** 0
- **ITYPE:** TrapAddOn.Liquid
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|5
- **SPROP:** Trap Liquid
- **DEFINE:** TrapCR|0

### Trap Melee

- **COST:** 0
- **ITYPE:** TrapAddOn.Melee
- **REPLACES:** TRAP_RANGED
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Melee

### Trap Ranged

- **COST:** 0
- **ITYPE:** TrapAddOn.Ranged
- **REPLACES:** TRAP_MLEE
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Ranged

### Trap Multiple Target

- **COST:** 0
- **ITYPE:** TrapAddOn.MultipleTarget
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Multiple Target
- **DEFINE:** TrapCR|0

### Trap Pit Spikes

- **COST:** 0
- **ITYPE:** TrapAddOn.PitSpikes
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Pit Spikes
- **DEFINE:** TrapCR|0

### Trap Touch Attack

- **COST:** 0
- **ITYPE:** TrapAddOn.TouchAttack
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Touch Attack
- **DEFINE:** TrapCR|0

### Trap Onset Delay (1 round)

- **COST:** 0
- **ITYPE:** TrapAddOn.OnsetDelay
- **REPLACES:** TRAP_ONSET_2,TRAP_ONSET_3,TRAP_ONSET_4
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Onset Delay (1 round)
- **DEFINE:** TrapCR|0

### Trap Onset Delay (2 rounds)

- **COST:** 0
- **ITYPE:** TrapAddOn.OnsetDelay
- **REPLACES:** TRAP_ONSET_1,TRAP_ONSET_3,TRAP_ONSET_4
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Onset Delay (2 rounds)
- **DEFINE:** TrapCR|0

### Trap Onset Delay (3 rounds)

- **COST:** 0
- **ITYPE:** TrapAddOn.OnsetDelay
- **REPLACES:** TRAP_ONSET_2,TRAP_ONSET_1,TRAP_ONSET_4
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Onset Delay (3 rounds)
- **DEFINE:** TrapCR|0

### Trap Onset Delay (4+ rounds)

- **COST:** 0
- **ITYPE:** TrapAddOn.OnsetDelay
- **REPLACES:** TRAP_ONSET_2,TRAP_ONSET_3,TRAP_ONSET_1
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Onset Delay (4+ rounds)
- **DEFINE:** TrapCR|0

### Trap Poison - Black Adder Venom

- **COST:** 2400
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Poison - Black Adder Venom
- **DEFINE:** TrapCR|0

### Trap Poison - Black Lotus Extract

- **COST:** 90000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABAV,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|8
- **SPROP:** Trap Poison - Black Lotus Extract
- **DEFINE:** TrapCR|0

### Trap Poison - Bloodroot

- **COST:** 2000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABAV,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Poison - Bloodroot
- **DEFINE:** TrapCR|0

### Trap Poison - Burnt Othur Fumes

- **COST:** 42000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABAV,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|6
- **SPROP:** Trap Poison - Burnt Othur Fumes
- **DEFINE:** TrapCR|0

### Trap Poison - Blue Whinnis

- **COST:** 2400
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABAV,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Poison - Blue Whinnis
- **DEFINE:** TrapCR|0

### Trap Poison - Carrion Crawler Brain Juice

- **COST:** 4000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ABAV,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Poison - Carrion Crawler Brain Juice
- **DEFINE:** TrapCR|0

### Trap Poison - Deathblade

- **COST:** 36000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ABAV,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|5
- **SPROP:** Trap Poison - Deathblade
- **DEFINE:** TrapCR|0

### Trap Poison - Dragon Bile

- **COST:** 30000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ABAV,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|6
- **SPROP:** Trap Poison - Dragon Bile
- **DEFINE:** TrapCR|0

### Trap Poison - Greenblood Oil

- **COST:** 2000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_ABAV,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Poison - Greenblood Oil
- **DEFINE:** TrapCR|0

### Trap Poison - Giant Wasp Poison

- **COST:** 4200
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_ABAV,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Poison - Giant Wasp Poison
- **DEFINE:** TrapCR|0

### Trap Poison - Insanity Mist

- **COST:** 30000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_ABAV,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|4
- **SPROP:** Trap Poison - Insanity Mist
- **DEFINE:** TrapCR|0

### Trap Poison - Large Scorpion Venom

- **COST:** 4000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ABAV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Poison - Large Scorpion Venom
- **DEFINE:** TrapCR|0

### Trap Poison - Malyss Root Paste

- **COST:** 10000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_ABAV,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Poison - Malyss Root Paste
- **DEFINE:** TrapCR|0

### Trap Poison - Medium Spider Venom

- **COST:** 3000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_ABAV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Poison - Medium Spider Venom
- **DEFINE:** TrapCR|0

### Trap Poison - Nitharit

- **COST:** 13000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ABAV,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|4
- **SPROP:** Trap Poison - Nitharit
- **DEFINE:** TrapCR|0

### Trap Poison - Purple Worm Poison

- **COST:** 14000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_ABAV,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|4
- **SPROP:** Trap Poison - Purple Worm Poison
- **DEFINE:** TrapCR|0

### Trap Poison - Small Centipede Poison

- **COST:** 1800
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ABAV,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Poison - Small Centipede Poison
- **DEFINE:** TrapCR|0

### Trap Poison - Shadow Essence

- **COST:** 5000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ABAV,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Poison - Shadow Essence
- **DEFINE:** TrapCR|0

### Trap Poison - Sassone Leaf Residue

- **COST:** 6000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ABAV,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Poison - Sassone Leaf Residue
- **DEFINE:** TrapCR|0

### Trap Poison - Terinav Root

- **COST:** 15000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ABAV,TRAP_POISON_AUD,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|5
- **SPROP:** Trap Poison - Terinav Root
- **DEFINE:** TrapCR|0

### Trap Poison - Ungol Dust

- **COST:** 20000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_ABAV,TRAP_POISON_AWP
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|3
- **SPROP:** Trap Poison - Ungol Dust
- **DEFINE:** TrapCR|0

### Trap Poison - Wyvern Poison

- **COST:** 60000
- **ITYPE:** TrapAddOn.Poison
- **REPLACES:** TRAP_POISON_ABLE,TRAP_POISON_ABLR,TRAP_POISON_ABOL,TRAP_POISON_ABWH,TRAP_POISON_ACCB,TRAP_POISON_ADBL,TRAP_POISON_ADRB,TRAP_POISON_AGBL,TRAP_POISON_AGWP,TRAP_POISON_AIM,TRAP_POISON_ALSV,TRAP_POISON_AMRP,TRAP_POISON_AMSV,TRAP_POISON_ANIT,TRAP_POISON_APWP,TRAP_POISON_ASCP,TRAP_POISON_ASHE,TRAP_POISON_ASLR,TRAP_POISON_ATRR,TRAP_POISON_AUD,TRAP_POISON_ABAV
- **PREMULT:** 2,[PRETYPE:1,Mechanical],[!PRETYPE:1,Automatic]
- **BONUS:** VAR|TrapCR|5
- **SPROP:** Trap Poison - Wyvern Poison
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 13

- **COST:** -700
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Reflex Save DC 13
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 14

- **COST:** -600
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Reflex Save DC 14
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 15

- **COST:** -500
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Reflex Save DC 15
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 16

- **COST:** -400
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 16

### Trap Reflex Save DC 17

- **COST:** -300
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 17

### Trap Reflex Save DC 18

- **COST:** -200
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 18

### Trap Reflex Save DC 19

- **COST:** -100
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 19

### Trap Reflex Save DC 20

- **COST:** 0
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 20

### Trap Reflex Save DC 21

- **COST:** 300
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 21

### Trap Reflex Save DC 22

- **COST:** 600
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 22

### Trap Reflex Save DC 23

- **COST:** 900
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 23

### Trap Reflex Save DC 24

- **COST:** 1200
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Reflex Save DC 24

### Trap Reflex Save DC 25

- **COST:** 1500
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Reflex Save DC 25
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 26

- **COST:** 1800
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Reflex Save DC 26
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 27

- **COST:** 2100
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Reflex Save DC 27
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 28

- **COST:** 2400
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Reflex Save DC 28
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 29

- **COST:** 2700
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Reflex Save DC 29
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 30

- **COST:** 3000
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Reflex Save DC 30
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 31

- **COST:** 3300
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Reflex Save DC 31
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 32

- **COST:** 3600
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Reflex Save DC 32
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 33

- **COST:** 3900
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Reflex Save DC 33
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 34

- **COST:** 4200
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_13,TRAP_REFLEX_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Reflex Save DC 34
- **DEFINE:** TrapCR|0

### Trap Reflex Save DC 35

- **COST:** 4500
- **ITYPE:** TrapAddOn.ReflexSave
- **REPLACES:** TRAP_REFLEX_DC_14,TRAP_REFLEX_DC_15,TRAP_REFLEX_DC_16,TRAP_REFLEX_DC_17,TRAP_REFLEX_DC_18,TRAP_REFLEX_DC_19,TRAP_REFLEX_DC_20,TRAP_REFLEX_DC_21,TRAP_REFLEX_DC_22,TRAP_REFLEX_DC_23,TRAP_REFLEX_DC_24,TRAP_REFLEX_DC_25,TRAP_REFLEX_DC_26,TRAP_REFLEX_DC_27,TRAP_REFLEX_DC_28,TRAP_REFLEX_DC_29,TRAP_REFLEX_DC_30,TRAP_REFLEX_DC_31,TRAP_REFLEX_DC_32,TRAP_REFLEX_DC_33,TRAP_REFLEX_DC_34,TRAP_REFLEX_DC_13
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Reflex Save DC 35
- **DEFINE:** TrapCR|0

### Trap Search DC 13

- **COST:** -700
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Search DC 13
- **DEFINE:** TrapCR|0

### Trap Search DC 14

- **COST:** -600
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_13,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Search DC 14
- **DEFINE:** TrapCR|0

### Trap Search DC 15

- **COST:** -500
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_13,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|-1
- **SPROP:** Trap Search DC 15
- **DEFINE:** TrapCR|0

### Trap Search DC 16

- **COST:** -400
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_13,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 16

### Trap Search DC 17

- **COST:** -300
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_13,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 17

### Trap Search DC 18

- **COST:** -200
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_13,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 18

### Trap Search DC 19

- **COST:** -100
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_13,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 19

### Trap Search DC 20

- **COST:** 0
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_13,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 20

### Trap Search DC 21

- **COST:** 200
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_13,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 21

### Trap Search DC 22

- **COST:** 400
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_13,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 22

### Trap Search DC 23

- **COST:** 600
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_13,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 23

### Trap Search DC 24

- **COST:** 800
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_13,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **SPROP:** Trap Search DC 24

### Trap Search DC 25

- **COST:** 1000
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_13,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Search DC 25
- **DEFINE:** TrapCR|0

### Trap Search DC 26

- **COST:** 1200
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_13,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Search DC 26
- **DEFINE:** TrapCR|0

### Trap Search DC 27

- **COST:** 1400
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_13,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Search DC 27
- **DEFINE:** TrapCR|0

### Trap Search DC 28

- **COST:** 1600
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_13,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Search DC 28
- **DEFINE:** TrapCR|0

### Trap Search DC 29

- **COST:** 1800
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_13,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|1
- **SPROP:** Trap Search DC 29
- **DEFINE:** TrapCR|0

### Trap Search DC 30

- **COST:** 2000
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_13,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Search DC 30
- **DEFINE:** TrapCR|0

### Trap Search DC 31

- **COST:** 2200
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_13,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Search DC 31
- **DEFINE:** TrapCR|0

### Trap Search DC 32

- **COST:** 2400
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_13,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Search DC 32
- **DEFINE:** TrapCR|0

### Trap Search DC 33

- **COST:** 2600
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_13,TRAP_SRCH_DC_34,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Search DC 33
- **DEFINE:** TrapCR|0

### Trap Search DC 34

- **COST:** 2800
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_13,TRAP_SRCH_DC_35
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Search DC 34
- **DEFINE:** TrapCR|0

### Trap Search DC 35

- **COST:** 3000
- **ITYPE:** TrapAddOn.SearchDC
- **REPLACES:** TRAP_SRCH_DC_14,TRAP_SRCH_DC_15,TRAP_SRCH_DC_16,TRAP_SRCH_DC_17,TRAP_SRCH_DC_18,TRAP_SRCH_DC_19,TRAP_SRCH_DC_20,TRAP_SRCH_DC_21,TRAP_SRCH_DC_22,TRAP_SRCH_DC_23,TRAP_SRCH_DC_24,TRAP_SRCH_DC_25,TRAP_SRCH_DC_26,TRAP_SRCH_DC_27,TRAP_SRCH_DC_28,TRAP_SRCH_DC_29,TRAP_SRCH_DC_30,TRAP_SRCH_DC_31,TRAP_SRCH_DC_32,TRAP_SRCH_DC_33,TRAP_SRCH_DC_34,TRAP_SRCH_DC_13
- **PRETYPE:** 1,Mechanical
- **BONUS:** VAR|TrapCR|2
- **SPROP:** Trap Search DC 35
- **DEFINE:** TrapCR|0

### Custom Magic

- **ITYPE:** CMagicItem

### +1 (Enhancement to Weapon or Ammunition)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+1
- **PLUS:** 1
- **ITYPE:** Masterwork.Enhancement.Magic.Plus1
- **REPLACES:** PLUS2W,PLUS3W,PLUS4W,PLUS5W,Masterwork (Weapon)
- **PRETYPE:** 1,Ammunition,Weapon
- **BONUS:** ITEMCOST|TYPE=Ammunition|40*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Weapon|2000*HEADPLUSTOTAL*HEADPLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Ammunition|6|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Weapon|300|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **ASSIGNTOALL:** NO
- **SORTKEY:** 01PLUSW

### +1 (Enhancement to Armor)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+1
- **PLUS:** 1
- **ITYPE:** Masterwork.Enhancement.Magic.Plus1
- **REPLACES:** PLUS2A,PLUS3A,PLUS4A,PLUS5A,Masterwork (Armor)
- **PRETYPE:** 1,Armor
- **BONUS:** COMBAT|AC|1|TYPE=ArmorEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Armor|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Armor|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 01PLUSA

### +1 (Enhancement to Shield)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+1
- **PLUS:** 1
- **ITYPE:** Masterwork.Enhancement.Magic.Plus1
- **REPLACES:** PLUS2S,PLUS3S,PLUS4S,PLUS5S,Masterwork (Armor)
- **PRETYPE:** 1,Shield
- **BONUS:** COMBAT|AC|1|TYPE=ShieldEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Shield|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Shield|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 01PLUSS

### +2 (Enhancement to Weapon or Ammunition)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+2
- **PLUS:** 2
- **ITYPE:** Masterwork.Enhancement.Magic.Plus2
- **REPLACES:** PLUS1W,PLUS3W,PLUS4W,PLUS5W,Masterwork (Weapon)
- **PRETYPE:** 1,Ammunition,Weapon
- **BONUS:** ITEMCOST|TYPE=Ammunition|40*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Weapon|2000*HEADPLUSTOTAL*HEADPLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Ammunition|6|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Weapon|300|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** WEAPON|DAMAGE,TOHIT|2|TYPE=Enhancement
- **ASSIGNTOALL:** NO
- **SORTKEY:** 02PLUSW

### +2 (Enhancement to Armor)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+2
- **PLUS:** 2
- **ITYPE:** Masterwork.Enhancement.Magic.Plus2
- **REPLACES:** PLUS1A,PLUS3A,PLUS4A,PLUS5A,Masterwork (Armor)
- **PRETYPE:** 1,Armor
- **BONUS:** COMBAT|AC|2|TYPE=ArmorEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Armor|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Armor|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 02PLUSA

### +2 (Enhancement to Shield)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+2
- **PLUS:** 2
- **ITYPE:** Masterwork.Enhancement.Magic.Plus2
- **REPLACES:** PLUS1S,PLUS3S,PLUS4S,PLUS5S,Masterwork (Armor)
- **PRETYPE:** 1,Shield
- **BONUS:** COMBAT|AC|2|TYPE=ShieldEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Shield|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Shield|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 02PLUSS

### +3 (Enhancement to Weapon or Ammunition)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+3
- **PLUS:** 3
- **ITYPE:** Masterwork.Enhancement.Magic.Plus3
- **REPLACES:** PLUS1W,PLUS2W,PLUS4W,PLUS5W,Masterwork (Weapon)
- **PRETYPE:** 1,Ammunition,Weapon
- **BONUS:** ITEMCOST|TYPE=Ammunition|40*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Weapon|2000*HEADPLUSTOTAL*HEADPLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Ammunition|6|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Weapon|300|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **ASSIGNTOALL:** NO
- **SORTKEY:** 03PLUSW

### +3 (Enhancement to Armor)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+3
- **PLUS:** 3
- **ITYPE:** Masterwork.Enhancement.Magic.Plus3
- **REPLACES:** PLUS1A,PLUS2A,PLUS4A,PLUS5A,Masterwork (Armor)
- **PRETYPE:** 1,Armor
- **BONUS:** COMBAT|AC|3|TYPE=ArmorEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Armor|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Armor|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 03PLUSA

### +3 (Enhancement to Shield)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+3
- **PLUS:** 3
- **ITYPE:** Masterwork.Enhancement.Magic.Plus3
- **REPLACES:** PLUS1S,PLUS2S,PLUS4S,PLUS5S,Masterwork (Armor)
- **PRETYPE:** 1,Shield
- **BONUS:** COMBAT|AC|3|TYPE=ShieldEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Shield|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Shield|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 03PLUSS

### +4 (Enhancement to Weapon or Ammunition)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+4
- **PLUS:** 4
- **ITYPE:** Masterwork.Enhancement.Magic.Plus4
- **REPLACES:** PLUS1W,PLUS2W,PLUS3W,PLUS5W,Masterwork (Weapon)
- **PRETYPE:** 1,Ammunition,Weapon
- **BONUS:** ITEMCOST|TYPE=Ammunition|40*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Weapon|2000*HEADPLUSTOTAL*HEADPLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Ammunition|6|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Weapon|300|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** WEAPON|DAMAGE,TOHIT|4|TYPE=Enhancement
- **ASSIGNTOALL:** NO
- **SORTKEY:** 04PLUSW

### +4 (Enhancement to Armor)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+4
- **PLUS:** 4
- **ITYPE:** Masterwork.Enhancement.Magic.Plus4
- **REPLACES:** PLUS1A,PLUS2A,PLUS3A,PLUS5A,Masterwork (Armor)
- **PRETYPE:** 1,Armor
- **BONUS:** COMBAT|AC|4|TYPE=ArmorEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Armor|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Armor|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 04PLUSA

### +4 (Enhancement to Shield)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+4
- **PLUS:** 4
- **ITYPE:** Masterwork.Enhancement.Magic.Plus4
- **REPLACES:** PLUS1S,PLUS2S,PLUS3S,PLUS5S,Masterwork (Armor)
- **PRETYPE:** 1,Shield
- **BONUS:** COMBAT|AC|4|TYPE=ShieldEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Shield|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Shield|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 04PLUSS

### +5 (Enhancement to Weapon or Ammunition)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+5
- **PLUS:** 5
- **ITYPE:** Masterwork.Enhancement.Magic.Plus5
- **REPLACES:** PLUS1W,PLUS2W,PLUS3W,PLUS4W,Masterwork (Weapon)
- **PRETYPE:** 1,Ammunition,Weapon
- **BONUS:** ITEMCOST|TYPE=Ammunition|40*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Weapon|2000*HEADPLUSTOTAL*HEADPLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Ammunition|6|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Weapon|300|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** WEAPON|DAMAGE,TOHIT|5|TYPE=Enhancement
- **ASSIGNTOALL:** NO
- **SORTKEY:** 05PLUSW

### +5 (Enhancement to Armor)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+5
- **PLUS:** 5
- **ITYPE:** Masterwork.Enhancement.Magic.Plus5
- **REPLACES:** PLUS1A,PLUS2A,PLUS3A,PLUS4A,Masterwork (Armor)
- **PRETYPE:** 1,Armor
- **BONUS:** COMBAT|AC|5|TYPE=ArmorEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Armor|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Armor|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 05PLUSA

### +5 (Enhancement to Shield)

- **FORMATCAT:** MIDDLE
- **NAMEOPT:** TEXT=+5
- **PLUS:** 5
- **ITYPE:** Masterwork.Enhancement.Magic.Plus5
- **REPLACES:** PLUS1S,PLUS2S,PLUS3S,PLUS4S,Masterwork (Armor)
- **PRETYPE:** 1,Shield
- **BONUS:** COMBAT|AC|5|TYPE=ShieldEnhancement
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **BONUS:** ITEMCOST|TYPE=Shield|1000*PLUSTOTAL*PLUSTOTAL
- **BONUS:** ITEMCOST|TYPE=Shield|150|TYPE=Masterwork|!PRETYPE:1,EQMODTYPE=MasterworkQuality
- **ASSIGNTOALL:** NO
- **SORTKEY:** 05PLUSS

### |Ability Bonus (Enhancement)

- **NAMEOPT:** NONAME
- **COST:** (1000*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** STAT|%CHOICE|TYPE=Enhancement
- **SPROP:** Enhancement bonus to ability %CHOICE
- **CHOOSE:** STATBONUS|MIN=-6|MAX=6|TITLE=Ability

### |Armor Bonus (Enhancement)

- **COST:** (1000*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PRETYPE:2,Enhancement,Weapon],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=ArmorEnhancement
- **SPROP:** Enhancement bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=8|TITLE=Armor Enhancement Bonus

### |Bonus Spell

- **COST:** (1000*(max(%CHOICE,1))*(max(%CHOICE,(1/2))))
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** SPELLCAST|CLASS=Any;LEVEL=%CHOICE|1
- **SPROP:** bonus spell
- **CHOOSE:** NUMBER|0|1|2|3|4|5|6|7|8|9|MULTIPLE|TITLE=Spell Level

### |AC Bonus (Deflection)

- **COST:** (2000*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=Deflection
- **SPROP:** Deflection bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Deflection Bonus

### |AC Bonus (Luck)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=Luck
- **SPROP:** Luck bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Armor Other Bonus

### |AC Bonus (Insight)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=Insight
- **SPROP:** Insight bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Armor Other Bonus

### |AC Bonus (Sacred)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=Sacred
- **SPROP:** Sacred bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Armor Other Bonus

### |AC Bonus (Profane)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=Profane
- **SPROP:** Profane bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Armor Other Bonus

### |AC Bonus (Other)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=Other
- **SPROP:** Other bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Armor Other Bonus

### |Natural Armor Bonus (Enhancement)

- **COST:** (2000*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** COMBAT|AC|%CHOICE|TYPE=NaturalArmor
- **SPROP:** Natural Armor bonus to armor class of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Natural Armor Bonus

### |Save Bonus (Resistance)

- **COST:** (1000*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **SPROP:** Resistance bonus to all saving throws of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Resistance Bonus
- **BONUS:** SAVE|Fortitude,Reflex,Will|%CHOICE|TYPE=Resistance

### |Save Bonus (Luck)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **SPROP:** Luck bonus to all saving throws of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Luck Bonus
- **BONUS:** SAVE|Fortitude,Reflex,Will|%CHOICE|TYPE=Luck

### |Save Bonus (Insight)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **SPROP:** Insight bonus to all saving throws of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Insight Bonus
- **BONUS:** SAVE|Fortitude,Reflex,Will|%CHOICE|TYPE=Insight

### |Save Bonus (Sacred)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **SPROP:** Sacred bonus to all saving throws of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Sacred Bonus
- **BONUS:** SAVE|Fortitude,Reflex,Will|%CHOICE|TYPE=Sacred

### |Save Bonus (Profane)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **SPROP:** Profane bonus to all saving throws of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Profane Bonus
- **BONUS:** SAVE|Fortitude,Reflex,Will|%CHOICE|TYPE=Profane

### |Save Bonus (Other)

- **COST:** (2500*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **SPROP:** Other bonus to all saving throws of %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=5|TITLE=Other bonus Bonus
- **BONUS:** SAVE|Fortitude,Reflex,Will|%CHOICE|TYPE=Other

### |Skill Bonus (Competence)

- **COST:** (100*%CHOICE*%CHOICE)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **BONUS:** SKILL|%CHOICE|TYPE=Competence
- **SPROP:** Competence bonus to selected skill of %CHOICE
- **CHOOSE:** SKILLBONUS|MIN=1|MAX=30|TITLE=Skill Bonus

### |Spell Resistance

- **COST:** 10000*(%CHOICE-12)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PRETYPE:2,Enhancement,Weapon],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **SR:** %CHOICE
- **SPROP:** base spell resistance of %CHOICE
- **CHOOSE:** NUMBER|MIN=13|MAX=32|NOSIGN|TITLE=Spell Resistance

### |Spell Effect (Single Use/Use Activated)

- **NAMEOPT:** SPELL
- **COST:** (50*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic.Consumable
- **CHOOSE:** EQBUILDER.SPELL

### |Spell Effect (50 Charges/Spell Trigger)

- **NAMEOPT:** SPELL
- **COST:** ((15*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST))*%CHARGES
- **ITYPE:** Enhancement.Magic
- **CHOOSE:** EQBUILDER.SPELL
- **CHARGES:** 1|50

### |Spell Effect (Command Word)

- **NAMEOPT:** SPELL
- **COST:** (1800*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **CHOOSE:** EQBUILDER.SPELL

### |Spell Effect (Use Activated)

- **NAMEOPT:** SPELL
- **COST:** (2000*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **CHOOSE:** EQBUILDER.SPELL

### |Spell Effect (Staff/Primary Power)

- **NAMEOPT:** SPELL
- **COST:** ((750*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST))/%CHARGES
- **ITYPE:** Enhancement.Magic
- **CHOOSE:** EQBUILDER.SPELL
- **CHARGES:** 1|5

### |Spell Effect (Staff/Secondary Power)

- **NAMEOPT:** SPELL
- **COST:** ((750/4*3*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST))/%CHARGES
- **ITYPE:** Enhancement.Magic
- **CHOOSE:** EQBUILDER.SPELL
- **CHARGES:** 1|5

### |Spell Effect (Staff/Lesser Powers)

- **NAMEOPT:** SPELL
- **COST:** ((750/2*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST))/%CHARGES
- **ITYPE:** Enhancement.Magic
- **CHOOSE:** EQBUILDER.SPELL
- **CHARGES:** 1|5

### |Spell Effect (Continuous/Standard spell duration)

- **NAMEOPT:** SPELL
- **COST:** (2000*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **CHOOSE:** EQBUILDER.SPELL

### |Spell Effect (Continuous/Spell duration measured in rounds)

- **NAMEOPT:** SPELL
- **COST:** (4*(2000*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL))+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **CHOOSE:** EQBUILDER.SPELL

### |Spell Effect (Continuous/Spell duration 1 minute/level)

- **NAMEOPT:** SPELL
- **COST:** (2*(2000*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL))+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **CHOOSE:** EQBUILDER.SPELL

### |Spell Effect (Continuous/Spell duration 10 minutes/level)

- **NAMEOPT:** SPELL
- **COST:** (1.5*(2000*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL))+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **CHOOSE:** EQBUILDER.SPELL

### |Spell Effect (Continuous/Spell duration 24-hours or more)

- **NAMEOPT:** SPELL
- **COST:** (.5*(2000*(max(%SPELLLEVEL,(1/2)))*%CASTERLEVEL))+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic
- **PREMULT:** 1,[PREMULT:2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield,Weapon]],[PRETYPE:1,Amulet,Belt,Bracer,Cape,Glove,Headgear,Instrument,Mantle,Ring,Robe,Shirt,Eyegear,Boot,Staff,Rod]
- **CHOOSE:** EQBUILDER.SPELL

### Divine

- **ITYPE:** Divine
- **!PRETYPE:** 1,Divine,Arcane

### Arcane

- **ITYPE:** Arcane
- **!PRETYPE:** 1,Divine,Arcane

### Minor

- **ITYPE:** Minor
- **PRETYPE:** 1,Arcane,Divine
- **!PRETYPE:** 1,Minor,Medium,Major

### Medium

- **ITYPE:** Medium
- **PRETYPE:** 1,Arcane,Divine
- **!PRETYPE:** 1,Minor,Medium,Major

### Major

- **ITYPE:** Major
- **PRETYPE:** 1,Arcane,Divine
- **!PRETYPE:** 1,Minor,Medium,Major

### |Spell Effect (Single Use/Completion)

- **NAMEOPT:** SPELL
- **COST:** (25*(max((%SPELLLEVEL),(1/2)))*%CASTERLEVEL)+%SPELLCOST+(5*%SPELLXPCOST)
- **ITYPE:** Enhancement.Magic.Consumable
- **PRETYPE:** 3,Scroll,Arcane,Minor
- **CHOOSE:** EQBUILDER.SPELL|Arcane|0|3

### Charges (1)

- **COST:** ((BASECOST/1)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|1

### Charges (2)

- **COST:** ((BASECOST/2)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|2

### Charges (3)

- **COST:** ((BASECOST/3)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|3

### Charges (4)

- **COST:** ((BASECOST/4)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|4

### Charges (5)

- **COST:** ((BASECOST/5)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|5

### Charges (6)

- **COST:** ((BASECOST/6)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|6

### Charges (7)

- **COST:** ((BASECOST/7)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|7

### Charges (9)

- **COST:** ((BASECOST/9)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|9

### Charges (10)

- **COST:** ((BASECOST/10)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|10

### Charges (12)

- **COST:** ((BASECOST/12)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|12

### Charges (20)

- **COST:** ((BASECOST/20)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|20

### Charges (30)

- **COST:** ((BASECOST/30)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|30

### Charges (34)

- **COST:** ((BASECOST/34)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|34

### Charges (36)

- **COST:** ((BASECOST/36)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|36

### Charges (40)

- **COST:** ((BASECOST/40)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|40

### Charges (50)

- **COST:** ((BASECOST/50)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|50

### Charges (60)

- **COST:** ((BASECOST/60)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|60

### Charges (101)

- **COST:** ((BASECOST/101)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|101

### Charges (150)

- **COST:** ((BASECOST/150)*%CHARGES)-BASECOST
- **CHOOSE:** NOCHOICE
- **CHARGES:** 1|150

### Arcane Archer Enhancement

- **COST:** 0
- **PRETYPE:** 1,Arrow
- **!PRETYPE:** 1,Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|ArrowEnhancement|TYPE=Enhancement

### Magical Enhancments (+1)

- **PLUS:** 1

### Magical Enhancments (+2)

- **PLUS:** 2

### Magical Enhancments (+3)

- **PLUS:** 3

### Magical Enhancments (+4)

- **PLUS:** 4

### Magical Enhancments (+5)

- **PLUS:** 5

### Magical Enhancments (+6)

- **PLUS:** 6

### Magical Enhancments (+7)

- **PLUS:** 7

### Magical Enhancments (+8)

- **PLUS:** 8

### Magical Enhancments (+9)

- **PLUS:** 9

### Magical Enhancments (+10)

- **PLUS:** 10

### Magical Enhancment Cost

- **COST:** %CHOICE
- **CHOOSE:** NUMBER|MIN=1|MAX=1000000|TITLE=Additional Cost

### Light Generation

- **COST:** 0
- **PRETYPE:** 1,Weapon
- **SPELLS:** Magic Weapon|TIMES=ATWILL|CASTERLEVEL=1|Light

### Intelligent Item

- **NAMEOPT:** TEXT=Intelligent
- **COST:** 0
- **ITYPE:** IntItem
- **!PRETYPE:** 1,IntItem
- **BONUS:** VAR|ItemEgo|PLUSTOTAL+ALTPLUSTOTAL
- **SPROP:** Intelligent Item ~ Ego Score %|ItemEgo
- **DEFINE:** ItemEgo|0

### Int. Item (Two abilities at 12)

- **NAMEOPT:** NOTHING
- **COST:** 1000
- **ITYPE:** Type1
- **REPLACES:** AMLT_INT_ITEM_2,AMLT_INT_ITEM_3,AMLT_INT_ITEM_4,AMLT_INT_ITEM_5,AMLT_INT_ITEM_6,AMLT_INT_ITEM_7,AMLT_INT_ITEM_8
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **SPROP:** Empathy, 30' vision and hearing

### Int. Item (Two abilities at 13)

- **NAMEOPT:** NOTHING
- **COST:** 2000
- **ITYPE:** Type2
- **REPLACES:** AMLT_INT_ITEM_1,AMLT_INT_ITEM_3,AMLT_INT_ITEM_4,AMLT_INT_ITEM_5,AMLT_INT_ITEM_6,AMLT_INT_ITEM_7,AMLT_INT_ITEM_8
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **SPROP:** Empathy, 60' vision and hearing

### Int. Item (Two abilities at 14)

- **NAMEOPT:** NOTHING
- **COST:** 4000
- **ITYPE:** Type3
- **REPLACES:** AMLT_INT_ITEM_1,AMLT_INT_ITEM_2,AMLT_INT_ITEM_4,AMLT_INT_ITEM_5,AMLT_INT_ITEM_6,AMLT_INT_ITEM_7,AMLT_INT_ITEM_8
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **SPROP:** Speech, 120' vision and hearing

### Int. Item (Two abilities at 15)

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** Type4
- **REPLACES:** AMLT_INT_ITEM_1,AMLT_INT_ITEM_2,AMLT_INT_ITEM_3,AMLT_INT_ITEM_5,AMLT_INT_ITEM_6,AMLT_INT_ITEM_7,AMLT_INT_ITEM_8
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **SPROP:** Speech, 60' darkvision and hearing

### Int. Item (Two abilities at 16)

- **NAMEOPT:** NOTHING
- **COST:** 6000
- **ITYPE:** Type5
- **REPLACES:** AMLT_INT_ITEM_1,AMLT_INT_ITEM_2,AMLT_INT_ITEM_3,AMLT_INT_ITEM_4,AMLT_INT_ITEM_6,AMLT_INT_ITEM_7,AMLT_INT_ITEM_8
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Speech (may read any language it speaks), 60' darkvision and hearing

### Int. Item (Two abilities at 17)

- **NAMEOPT:** NOTHING
- **COST:** 9000
- **ITYPE:** Type6
- **REPLACES:** AMLT_INT_ITEM_1,AMLT_INT_ITEM_2,AMLT_INT_ITEM_3,AMLT_INT_ITEM_4,AMLT_INT_ITEM_5,AMLT_INT_ITEM_7,AMLT_INT_ITEM_8
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Speech (may read any language it speaks), Telepathy, 120' darkvision and hearing

### Int. Item (Two abilities at 18)

- **NAMEOPT:** NOTHING
- **COST:** 12000
- **ITYPE:** Type7
- **REPLACES:** AMLT_INT_ITEM_1,AMLT_INT_ITEM_2,AMLT_INT_ITEM_3,AMLT_INT_ITEM_4,AMLT_INT_ITEM_5,AMLT_INT_ITEM_6,AMLT_INT_ITEM_8
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|3
- **SPROP:** Speech (can read all languages and magic), Telepathy, 120' darkvision and blindsense and hearing

### Int. Item (Two abilities at 19)

- **NAMEOPT:** NOTHING
- **COST:** 15000
- **ITYPE:** Type8
- **REPLACES:** AMLT_INT_ITEM_1,AMLT_INT_ITEM_2,AMLT_INT_ITEM_3,AMLT_INT_ITEM_4,AMLT_INT_ITEM_5,AMLT_INT_ITEM_6,AMLT_INT_ITEM_7
- **PRETYPE:** 2,IntItem,Amulet
- **!PRETYPE:** 1,Type1,Type2,Type3,Type4,Type5,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|3
- **SPROP:** Speech (can read all languages and magic), Telepathy, 120' darkvision and blindsense and hearing

### Int. Item Alignment (CE)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignCE
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:CE
- **SPROP:** Chaotic Evil
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (CG)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignCG
- **REPLACES:** INT_ITEM_ALIGN_CE,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:CG
- **SPROP:** Chaotic Good
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (CN)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignCN
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CE,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:CE,CN,CG
- **SPROP:** Chaotic Neutral
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (LE)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignLE
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_CE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:LE
- **SPROP:** Lawful Evil
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (LG)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignLG
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_CE,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:LG
- **SPROP:** Lawful Good
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (LN)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignLN
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_CE,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:LN,LG,LE
- **SPROP:** Lawful Neutral
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (N)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignN
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_CE,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:TN
- **SPROP:** True Neutral
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (NE)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignNE
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_CE,INT_ITEM_ALIGN_NG
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:NE,LE,CE
- **SPROP:** Neutral Evil
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Alignment (NG)

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AlignNG
- **REPLACES:** INT_ITEM_ALIGN_CG,INT_ITEM_ALIGN_CN,INT_ITEM_ALIGN_LE,INT_ITEM_ALIGN_LG,INT_ITEM_ALIGN_LN,INT_ITEM_ALIGN_N,INT_ITEM_ALIGN_NE,INT_ITEM_ALIGN_CE
- **!PRETYPE:** 1,AlignCE,AlignCG,AlignCN,AlignLE,AlignLG,AlignLN,AlignN,AlignNE,AlignNG
- **BONUS:** VAR|NegLevels|min(3,max(1,floor(ItemEgo/10)))|!PREALIGN:NG,LG,CG
- **SPROP:** Neutral Good
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Int. Item Ability Cha 10

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha10
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_13,INT_ITEM_CHA_14,INT_ITEM_CHA_15,INT_ITEM_CHA_16,INT_ITEM_CHA_17,INT_ITEM_CHA_18,INT_ITEM_CHA_19
- **PRETYPE:** 3,IntItem,Int12,Int13,Int14,Int15,Int16,Int17,Int18,Int19,Wis12,Wis13,Wis14,Wis15,Wis16,Wis17,Wis18,Wis19
- **!PRETYPE:** 2,Wis10,Int10
- **!PRETYPE:** 3,AbilityInt,AbilityCha,AbilityWis
- **SPROP:** Cha 10
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 12

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha12
- **REPLACES:** INT_ITEM_CHA_10,INT_ITEM_CHA_13,INT_ITEM_CHA_14,INT_ITEM_CHA_15,INT_ITEM_CHA_16,INT_ITEM_CHA_17,INT_ITEM_CHA_18,INT_ITEM_CHA_19
- **PRETYPE:** 2,IntItem,Type1
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|1
- **BONUS:** VAR|IntItemPowerMod|1
- **SPROP:** Cha 12
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 13

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha13
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_10,INT_ITEM_CHA_14,INT_ITEM_CHA_15,INT_ITEM_CHA_16,INT_ITEM_CHA_17,INT_ITEM_CHA_18,INT_ITEM_CHA_19
- **PRETYPE:** 2,IntItem,Type2
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|1
- **BONUS:** VAR|IntItemPowerMod|1
- **SPROP:** Cha 13
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 14

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha14
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_13,INT_ITEM_CHA_10,INT_ITEM_CHA_15,INT_ITEM_CHA_16,INT_ITEM_CHA_17,INT_ITEM_CHA_18,INT_ITEM_CHA_19
- **PRETYPE:** 2,IntItem,Type3
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|2
- **BONUS:** VAR|IntItemPowerMod|2
- **SPROP:** Cha 14
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 15

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha15
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_13,INT_ITEM_CHA_14,INT_ITEM_CHA_10,INT_ITEM_CHA_16,INT_ITEM_CHA_17,INT_ITEM_CHA_18,INT_ITEM_CHA_19
- **PRETYPE:** 2,IntItem,Type4
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|2
- **BONUS:** VAR|IntItemPowerMod|2
- **SPROP:** Cha 15
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 16

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha16
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_13,INT_ITEM_CHA_14,INT_ITEM_CHA_15,INT_ITEM_CHA_10,INT_ITEM_CHA_17,INT_ITEM_CHA_18,INT_ITEM_CHA_19
- **PRETYPE:** 2,IntItem,Type5
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|3
- **BONUS:** VAR|IntItemPowerMod|3
- **SPROP:** Cha 16
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 17

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha17
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_13,INT_ITEM_CHA_14,INT_ITEM_CHA_15,INT_ITEM_CHA_16,INT_ITEM_CHA_10,INT_ITEM_CHA_18,INT_ITEM_CHA_19
- **PRETYPE:** 2,IntItem,Type6
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|3
- **BONUS:** VAR|IntItemPowerMod|3
- **SPROP:** Cha 17
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 18

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha18
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_13,INT_ITEM_CHA_14,INT_ITEM_CHA_15,INT_ITEM_CHA_16,INT_ITEM_CHA_17,INT_ITEM_CHA_10,INT_ITEM_CHA_19
- **PRETYPE:** 2,IntItem,Type7
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|4
- **BONUS:** VAR|IntItemPowerMod|4
- **SPROP:** Cha 18
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Cha 19

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityCha.Cha19
- **REPLACES:** INT_ITEM_CHA_12,INT_ITEM_CHA_13,INT_ITEM_CHA_14,INT_ITEM_CHA_15,INT_ITEM_CHA_16,INT_ITEM_CHA_17,INT_ITEM_CHA_18,INT_ITEM_CHA_10
- **PRETYPE:** 2,IntItem,Type8
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityWis
- **BONUS:** VAR|ItemEgo|4
- **BONUS:** VAR|IntItemPowerMod|4
- **SPROP:** Cha 19
- **DEFINE:** IntItemPowerMod|0

### Int. Item Ability Int 10

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int10
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_13,INT_ITEM_INT_14,INT_ITEM_INT_15,INT_ITEM_INT_16,INT_ITEM_INT_17,INT_ITEM_INT_18,INT_ITEM_INT_19
- **PRETYPE:** 3,IntItem,Cha12,Cha13,Cha14,Cha15,Cha16,Cha17,Cha18,Cha19,Wis12,Wis13,Wis14,Wis15,Wis16,Wis17,Wis18,Wis19
- **!PRETYPE:** 2,Wis10,Cha10
- **!PRETYPE:** 3,AbilityInt,AbilityCha,AbilityWis
- **SPROP:** Int 10

### Int. Item Ability Int 12

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int12
- **REPLACES:** INT_ITEM_INT_10,INT_ITEM_INT_13,INT_ITEM_INT_14,INT_ITEM_INT_15,INT_ITEM_INT_16,INT_ITEM_INT_17,INT_ITEM_INT_18,INT_ITEM_INT_19
- **PRETYPE:** 2,IntItem,Type1
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Int 12

### Int. Item Ability Int 13

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int13
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_10,INT_ITEM_INT_14,INT_ITEM_INT_15,INT_ITEM_INT_16,INT_ITEM_INT_17,INT_ITEM_INT_18,INT_ITEM_INT_19
- **PRETYPE:** 2,IntItem,Type2
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Int 13

### Int. Item Ability Int 14

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int14
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_13,INT_ITEM_INT_10,INT_ITEM_INT_15,INT_ITEM_INT_16,INT_ITEM_INT_17,INT_ITEM_INT_18,INT_ITEM_INT_19
- **PRETYPE:** 2,IntItem,Type3
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Int 14

### Int. Item Ability Int 15

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int15
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_13,INT_ITEM_INT_14,INT_ITEM_INT_10,INT_ITEM_INT_16,INT_ITEM_INT_17,INT_ITEM_INT_18,INT_ITEM_INT_19
- **PRETYPE:** 2,IntItem,Type4
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Int 15

### Int. Item Ability Int 16

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int16
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_13,INT_ITEM_INT_14,INT_ITEM_INT_15,INT_ITEM_INT_10,INT_ITEM_INT_17,INT_ITEM_INT_18,INT_ITEM_INT_19
- **PRETYPE:** 2,IntItem,Type5
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|3
- **SPROP:** Int 16

### Int. Item Ability Int 17

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int17
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_13,INT_ITEM_INT_14,INT_ITEM_INT_15,INT_ITEM_INT_16,INT_ITEM_INT_10,INT_ITEM_INT_18,INT_ITEM_INT_19
- **PRETYPE:** 2,IntItem,Type6
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|3
- **SPROP:** Int 17

### Int. Item Ability Int 18

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int18
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_13,INT_ITEM_INT_14,INT_ITEM_INT_15,INT_ITEM_INT_16,INT_ITEM_INT_17,INT_ITEM_INT_10,INT_ITEM_INT_19
- **PRETYPE:** 2,IntItem,Type7
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|4
- **SPROP:** Int 18

### Int. Item Ability Int 19

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityInt.Int19
- **REPLACES:** INT_ITEM_INT_12,INT_ITEM_INT_13,INT_ITEM_INT_14,INT_ITEM_INT_15,INT_ITEM_INT_16,INT_ITEM_INT_17,INT_ITEM_INT_18,INT_ITEM_INT_10
- **PRETYPE:** 2,IntItem,Type8
- **!PRETYPE:** 3,IntItem,AbilityCha,AbilityWis
- **BONUS:** VAR|ItemEgo|4
- **SPROP:** Int 19

### Int. Item Ability Wis 10

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis10
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_13,INT_ITEM_WIS_14,INT_ITEM_WIS_15,INT_ITEM_WIS_16,INT_ITEM_WIS_17,INT_ITEM_WIS_18,INT_ITEM_WIS_19
- **PRETYPE:** 3,IntItem,Int12,Int13,Int14,Int15,Int16,Int17,Int18,Int19,Cha12,Cha13,Cha14,Cha15,Cha16,Cha17,Cha18,Cha19
- **!PRETYPE:** 2,Cha10,Int10
- **!PRETYPE:** 3,AbilityInt,AbilityCha,AbilityWis
- **SPROP:** Wis 10

### Int. Item Ability Wis 12

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis12
- **REPLACES:** INT_ITEM_WIS_10,INT_ITEM_WIS_13,INT_ITEM_WIS_14,INT_ITEM_WIS_15,INT_ITEM_WIS_16,INT_ITEM_WIS_17,INT_ITEM_WIS_18,INT_ITEM_WIS_19
- **PRETYPE:** 2,IntItem,Type1
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Wis 12

### Int. Item Ability Wis 13

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis13
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_10,INT_ITEM_WIS_14,INT_ITEM_WIS_15,INT_ITEM_WIS_16,INT_ITEM_WIS_17,INT_ITEM_WIS_18,INT_ITEM_WIS_19
- **PRETYPE:** 2,IntItem,Type2
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Wis 13

### Int. Item Ability Wis 14

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis14
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_13,INT_ITEM_WIS_10,INT_ITEM_WIS_15,INT_ITEM_WIS_16,INT_ITEM_WIS_17,INT_ITEM_WIS_18,INT_ITEM_WIS_19
- **PRETYPE:** 2,IntItem,Type3
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Wis 14

### Int. Item Ability Wis 15

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis15
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_13,INT_ITEM_WIS_14,INT_ITEM_WIS_10,INT_ITEM_WIS_16,INT_ITEM_WIS_17,INT_ITEM_WIS_18,INT_ITEM_WIS_19
- **PRETYPE:** 2,IntItem,Type4
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Wis 15

### Int. Item Ability Wis 16

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis16
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_13,INT_ITEM_WIS_14,INT_ITEM_WIS_15,INT_ITEM_WIS_10,INT_ITEM_WIS_17,INT_ITEM_WIS_18,INT_ITEM_WIS_19
- **PRETYPE:** 2,IntItem,Type5
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|3
- **SPROP:** Wis 16

### Int. Item Ability Wis 17

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis17
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_13,INT_ITEM_WIS_14,INT_ITEM_WIS_15,INT_ITEM_WIS_16,INT_ITEM_WIS_10,INT_ITEM_WIS_18,INT_ITEM_WIS_19
- **PRETYPE:** 2,IntItem,Type6
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|3
- **SPROP:** Wis 17

### Int. Item Ability Wis 18

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis18
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_13,INT_ITEM_WIS_14,INT_ITEM_WIS_15,INT_ITEM_WIS_16,INT_ITEM_WIS_17,INT_ITEM_WIS_10,INT_ITEM_WIS_19
- **PRETYPE:** 2,IntItem,Type7
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|4
- **SPROP:** Wis 18

### Int. Item Ability Wis 19

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** AbilityWis.Wis19
- **REPLACES:** INT_ITEM_WIS_12,INT_ITEM_WIS_13,INT_ITEM_WIS_14,INT_ITEM_WIS_15,INT_ITEM_WIS_16,INT_ITEM_WIS_17,INT_ITEM_WIS_18,INT_ITEM_WIS_10
- **PRETYPE:** 2,IntItem,Type8
- **!PRETYPE:** 3,IntItem,AbilityInt,AbilityCha
- **BONUS:** VAR|ItemEgo|4
- **SPROP:** Wis 19

### Int. Item Lesser Power - Bless

- **NAMEOPT:** NOTHING
- **COST:** 1000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Bless
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=1|Bless,11

### Int. Item Lesser Power - Bluff 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Bluff 10 Ranks

### Int. Item Lesser Power - Cure Moderate Wounds

- **NAMEOPT:** NOTHING
- **COST:** 6500
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Cure Moderate Wounds
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=3|Cure Moderate Wounds,13

### Int. Item Lesser Power - Darkness

- **NAMEOPT:** NOTHING
- **COST:** 6500
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Darkness
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=3|Darkness,13

### Int. Item Lesser Power - Daze Monster

- **NAMEOPT:** NOTHING
- **COST:** 6500
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Daze Monster
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=3|Daze Monster,13

### Int. Item Lesser Power - Deathwatch

- **NAMEOPT:** NOTHING
- **COST:** 2700
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Deathwatch

### Int. Item Lesser Power - Decipher Script 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Decipher Script 10 Ranks

### Int. Item Lesser Power - Detect Magic

- **NAMEOPT:** NOTHING
- **COST:** 3600
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Detect Magic
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=1|Detect Magic,10

### Int. Item Lesser Power - Diplomacy 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Diplomacy 10 Ranks

### Int. Item Lesser Power - Faerie Fire

- **NAMEOPT:** NOTHING
- **COST:** 1100
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Faerie Fire
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=1|Faerie Fire,11

### Int. Item Lesser Power - Hold Person

- **NAMEOPT:** NOTHING
- **COST:** 6500
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Hold Person
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=3|Hold Person,13

### Int. Item Lesser Power - Intimidate 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Intimidate 10 Ranks

### Int. Item Lesser Power - Knowledge 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Knowledge 10 Ranks, Selected %CHOICE
- **CHOOSE:** SKILL|TYPE=Knowledge

### Int. Item Lesser Power - Listen 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Listen 10 Ranks

### Int. Item Lesser Power - Locate Object

- **NAMEOPT:** NOTHING
- **COST:** 6500
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Locate Object
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=3|Locate Object,13

### Int. Item Lesser Power - Major Image

- **NAMEOPT:** NOTHING
- **COST:** 5400
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Major Image
- **SPELLS:** Intelligent Item|TIMES=1|CASTERLEVEL=5|Major Image,14

### Int. Item Lesser Power - Minor Image

- **NAMEOPT:** NOTHING
- **COST:** 2200
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Minor Image
- **SPELLS:** Intelligent Item|TIMES=1|CASTERLEVEL=3|Minor Image,13

### Int. Item Lesser Power - Search 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Search 10 Ranks

### Int. Item Lesser Power - Sense Motive 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Sense Motive 10 Ranks

### Int. Item Lesser Power - Spellcraft 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Spellcraft 10 Ranks

### Int. Item Lesser Power - Spot 10 Ranks

- **NAMEOPT:** NOTHING
- **COST:** 5000
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Spot 10 Ranks

### Int. Item Lesser Power - Zone of Truth

- **NAMEOPT:** NOTHING
- **COST:** 6500
- **ITYPE:** LesserPower
- **BONUS:** VAR|ItemEgo|1
- **SPROP:** Lesser Power - Zone of Truth
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=3|Zone of Truth,13

### Int. Item Greater Power - Arcane Eye

- **NAMEOPT:** NOTHING
- **COST:** 10000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Arcane Eye
- **SPELLS:** Intelligent Item|TIMES=1|CASTERLEVEL=7|Arcane Eye,16

### Int. Item Greater Power - Cause Fear

- **NAMEOPT:** NOTHING
- **COST:** 7200
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Cause Fear
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=1|Cause Fear,11

### Int. Item Greater Power - Magic Circle Against Chaos

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignLE,AlignLG,AlignLN]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Magic Circle Against Chaos
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=5|Magic Circle Against Chaos,14

### Int. Item Greater Power - Magic Circle Against Evil

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignLG,AlignCG,AlignNG]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Magic Circle Against Evil
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=5|Magic Circle Against Evil,14

### Int. Item Greater Power - Magic Circle Against Good

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignLE,AlignCE,AlignNE]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Magic Circle Against Good
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=5|Magic Circle Against Good,14

### Int. Item Greater Power - Magic Circle Against Law

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignCE,AlignCG,AlignCN]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Magic Circle Against Law
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=5|Magic Circle Against Law,14

### Int. Item Greater Power - Clairvoyance

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Clairvoyance

### Int. Item Greater Power - Deeper Darkness

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Deeper Darkness
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=5|Deeper Darkness,14

### Int. Item Greater Power - Daylight

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Daylight
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=5|Daylight,14

### Int. Item Greater Power - Detect Chaos

- **NAMEOPT:** NOTHING
- **COST:** 7200
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignLE,AlignLG,AlignLN]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Detect Chaos
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=1|Detect Chaos,11

### Int. Item Greater Power - Detect Evil

- **NAMEOPT:** NOTHING
- **COST:** 7200
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignLG,AlignCG,AlignNG]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Detect Evil
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=1|Detect Evil,11

### Int. Item Greater Power - Detect Good

- **NAMEOPT:** NOTHING
- **COST:** 7200
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignLE,AlignCE,AlignNE]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Detect Good
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=1|Detect Good,11

### Int. Item Greater Power - Detect Law

- **NAMEOPT:** NOTHING
- **COST:** 7200
- **ITYPE:** GreaterPower
- **PREMULT:** 2,[PRETYPE:1,Type6,Type7,Type8],[PRETYPE:1,AlignCE,AlignCG,AlignCN]
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Detect Law
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=1|Detect Law,11

### Int. Item Greater Power - Detect Scrying

- **NAMEOPT:** NOTHING
- **COST:** 10000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Detect Scrying

### Int. Item Greater Power - Detect Thoughts

- **NAMEOPT:** NOTHING
- **COST:** 44000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Detect Thoughts
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=3|Detect Thoughts,13

### Int. Item Greater Power - Detect Undead

- **NAMEOPT:** NOTHING
- **COST:** 7200
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Detect Undead
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=1|Detect Undead,11

### Int. Item Greater Power - Dimensional Anchor

- **NAMEOPT:** NOTHING
- **COST:** 10000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Dimensional Anchor
- **SPELLS:** Intelligent Item|TIMES=1|CASTERLEVEL=7|Dimensional Anchor,16

### Int. Item Greater Power - Dismissal

- **NAMEOPT:** NOTHING
- **COST:** 10000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Dismissal
- **SPELLS:** Intelligent Item|TIMES=1|CASTERLEVEL=7|Dismissal,16

### Int. Item Greater Power - Fear

- **NAMEOPT:** NOTHING
- **COST:** 30000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Fear
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=5|Fear,14

### Int. Item Greater Power - Gust of Wind

- **NAMEOPT:** NOTHING
- **COST:** 11000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Gust of Wind
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=3|Gust of Wind,13

### Int. Item Greater Power - Haste

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Haste
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=5|Haste,14

### Int. Item Greater Power - Invisibility Purge

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Invisibility Purge
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=5|Invisibility Purge,14

### Int. Item Greater Power - Lesser Globe of Invulnerability

- **NAMEOPT:** NOTHING
- **COST:** 10000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Lesser Globe of Invulnerability
- **SPELLS:** Intelligent Item|TIMES=1|CASTERLEVEL=7|Globe of Invulnerability (Lesser),16

### Int. Item Greater Power - Locate Creature

- **NAMEOPT:** NOTHING
- **COST:** 30000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Locate Creature
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=7|Locate Creature,16

### Int. Item Greater Power - Quench

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Quench
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=5|Quench,14

### Int. Item Greater Power - Slow

- **NAMEOPT:** NOTHING
- **COST:** 16000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Slow
- **SPELLS:** Intelligent Item|TIMES=3|CASTERLEVEL=5|Slow,14

### Int. Item Greater Power - Status

- **NAMEOPT:** NOTHING
- **COST:** 11000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Status
- **SPELLS:** Intelligent Item|TIMES=ATWILL|CASTERLEVEL=3|Status,13

### Int. Item Greater Power - Wall of Fire

- **NAMEOPT:** NOTHING
- **COST:** 10000
- **ITYPE:** GreaterPower
- **PRETYPE:** 1,Type6,Type7,Type8
- **BONUS:** VAR|ItemEgo|2
- **SPROP:** Greater Power - Wall of Fire
- **SPELLS:** Intelligent Item|TIMES=1|CASTERLEVEL=7|Wall of Fire,16

### Int. Item Dedicated Power - Confusion

- **NAMEOPT:** NOTHING
- **COST:** 50000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Confusion

### Int. Item Dedicated Power - Contagion

- **NAMEOPT:** NOTHING
- **COST:** 56000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONFUSION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Contagion

### Int. Item Dedicated Power - Crushing Despair

- **NAMEOPT:** NOTHING
- **COST:** 50000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CONFUSION,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Crushing Despair

### Int. Item Dedicated Power - Dimension Door

- **NAMEOPT:** NOTHING
- **COST:** 50000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_CONFUSION,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Dimension Door

### Int. Item Dedicated Power - Fireball

- **NAMEOPT:** NOTHING
- **COST:** 60000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_CONFUSION,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Fireball

### Int. Item Dedicated Power - Greater Shout

- **NAMEOPT:** NOTHING
- **COST:** 130000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_CONFUSION,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Greater Shout

### Int. Item Dedicated Power - Ice Storm

- **NAMEOPT:** NOTHING
- **COST:** 50000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_CONFUSION,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Ice Storm

### Int. Item Dedicated Power - Lightning Bolt

- **NAMEOPT:** NOTHING
- **COST:** 60000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_CONFUSION,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Lightning Bolt

### Int. Item Dedicated Power - +2 Luck

- **NAMEOPT:** NOTHING
- **COST:** 80000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_CONFUSION,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **BONUS:** SKILL|TYPE.Strength,TYPE.Dexterity,TYPE.Constitution,TYPE.Intelligence,TYPE.Wisdom,TYPE.Charisma|2|TYPE=Luck
- **BONUS:** WEAPON|TOHIT,DAMAGE|2|TYPE=Luck
- **SPROP:** Dedicated Power - +2 Luck
- **BONUS:** SAVE|ALL|2|TYPE=Luck

### Int. Item Dedicated Power - Mass Inflict Light Wounds

- **NAMEOPT:** NOTHING
- **COST:** 81000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_CONFUSION,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Mass Inflict Light Wounds

### Int. Item Dedicated Power - Phantasmal Killer

- **NAMEOPT:** NOTHING
- **COST:** 50000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_CONFUSION,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Phantasmal Killer

### Int. Item Dedicated Power - Poison

- **NAMEOPT:** NOTHING
- **COST:** 56000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_CONFUSION,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Poison

### Int. Item Dedicated Power - Prying Eyes

- **NAMEOPT:** NOTHING
- **COST:** 81000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_CONFUSION,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Prying Eyes

### Int. Item Dedicated Power - Rusting Grasp

- **NAMEOPT:** NOTHING
- **COST:** 56000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_CONFUSION,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Rusting Grasp

### Int. Item Dedicated Power - Song of Discord

- **NAMEOPT:** NOTHING
- **COST:** 81000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_CONFUSION,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Song of Discord

### Int. Item Dedicated Power - True Resurrection

- **NAMEOPT:** NOTHING
- **COST:** 200000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_CONFUSION,INT_ITEM_WAVES_EXHAUSTION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - True Resurrection

### Int. Item Dedicated Power - Waves of Exhaustion

- **NAMEOPT:** NOTHING
- **COST:** 164000
- **ITYPE:** DedicatedPower
- **REPLACES:** INT_ITEM_CONTAGION,INT_ITEM_CRUSHING_DESPAIR,INT_ITEM_DIMENSION_DOOR,INT_ITEM_FIREBALL,INT_ITEM_GRTR_SHOUT,INT_ITEM_ICE_STORM,INT_ITEM_LGHTNG_BOLT,INT_ITEM_LUCK,INT_ITEM_MASS_INFLICT_LGT_WOUNDS,INT_ITEM_PHANTASMAL_KILLER,INT_ITEM_POISON,INT_ITEM_PRYING_EYES,INT_ITEM_RUSTING_GRASP,INT_ITEM_SONG_DISCORD,INT_ITEM_TRUE_RESURRECTION,INT_ITEM_CONFUSION
- **!PRETYPE:** 1,DedicatedPower
- **SPROP:** Dedicated Power - Waves of Exhaustion

### Int. Item Special Purpose

- **NAMEOPT:** NOTHING
- **ITYPE:** SpecialPurpose
- **PRETYPE:** 1,Type6,Type7,Type8
- **!PRETYPE:** 1,SpecialPurpose
- **BONUS:** VAR|ItemEgo|4

### Int. Item Purpose-Defeat/Slay All

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay All

### Int. Item Purpose-Defeat/Slay Arcane Spellcasters

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Arcane Spellcasters

### Int. Item Purpose-Defeat/Slay Chaos

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Chaos

### Int. Item Purpose-Defeat/Slay Deity Servants

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Deity Servants

### Int. Item Purpose-Defeat/Slay Divine Spellcasters

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Divine Spellcasters

### Int. Item Purpose-Defeat/Slay Evil

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Evil

### Int. Item Purpose-Defeat/Slay Good

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Good

### Int. Item Purpose-Defeat/Slay Law

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Law

### Int. Item Purpose-Defeat/Slay Non-Spellcasters

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Non-Spellcasters

### Int. Item Purpose-Defeat/Slay Race

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Race

### Int. Item Purpose-Defeat/Slay Type of Creature

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defeat/Slay Type of Creature
- **CHOOSE:** STRING|Aberrations|Animals|Constructs|Dragons|Elementals|Fey|Giants|Humanoids (Aquatic)|Humanoids (Dwarf)|Humanoids (Elf)|Humanoids (Gnoll)|Humanoids (Gnome)|Humanoids (Goblinoid)|Humanoids (Halfling)|Humanoids (Human)|Humanoids (Reptilian)|Humanoids (Orc)|Magical Beasts|Monstrous Humanoids|Oozes|Outsiders (Air)|Outsiders (Chaotic)|Outsiders (Earth)|Outsiders (Evil)|Outsiders (Fire)|Outsiders (Good)|Outsiders (Lawful)|Outsiders (Water)|Plants|Undead|Vermin|TITLE=Designated Foe

### Int. Item Purpose-Defend Deity Servants

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEAT_ALL,INT_ITEM_DEFEND_RACE
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defend Deity Servants

### Int. Item Purpose-Defend Race

- **NAMEOPT:** NOTHING
- **COST:** 0
- **ITYPE:** Purpose
- **REPLACES:** INT_ITEM_DEFEAT_ARCANE,INT_ITEM_DEFEAT_CHAOS,INT_ITEM_DEFEAT_DEITY,INT_ITEM_DEFEAT_DIVINE,INT_ITEM_DEFEAT_EVIL,INT_ITEM_DEFEAT_GOOD,INT_ITEM_DEFEAT_LAW,INT_ITEM_DEFEAT_NONSPELL,INT_ITEM_DEFEAT_RACE,INT_ITEM_DEFEAT_TYPE,INT_ITEM_DEFEND_DEITY,INT_ITEM_DEFEAT_ALL
- **!PRETYPE:** 1,Purpose
- **SPROP:** Special Purpose - Defend Race

### Int. Item - Language Choice 1

- **NAMEOPT:** NOTHING
- **ITYPE:** Lang1
- **!PRETYPE:** 1,Lang1
- **SPROP:** Common, %CHOICE
- **CHOOSE:** STRING|Common|Dwarven|Elven|Gnome|Halfling|Giant|Gnoll|Goblin|Orc|Terran|Undercommon|Abyssal|Celestial|Draconic|Infernal|Sylvan|Druidic|Aboleth|Aquan|Auran|Blink Dog|Ettin Pidgin|Formian|Grimlock|Ignan|Sahuagin|Sphinx|Treant|Worg|TITLE=Language

### Int. Item - Language Choice 2

- **NAMEOPT:** NOTHING
- **ITYPE:** Lang2
- **PRETYPE:** 1,Lang1
- **!PRETYPE:** 1,Lang2
- **SPROP:** %CHOICE
- **CHOOSE:** STRING|Common|Dwarven|Elven|Gnome|Halfling|Giant|Gnoll|Goblin|Orc|Terran|Undercommon|Abyssal|Celestial|Draconic|Infernal|Sylvan|Druidic|Aboleth|Aquan|Auran|Blink Dog|Ettin Pidgin|Formian|Grimlock|Ignan|Sahuagin|Sphinx|Treant|Worg|TITLE=Language

### Int. Item - Language Choice 3

- **NAMEOPT:** NOTHING
- **ITYPE:** Lang3
- **PRETYPE:** 1,Lang2
- **!PRETYPE:** 1,Lang3
- **SPROP:** %CHOICE
- **CHOOSE:** STRING|Common|Dwarven|Elven|Gnome|Halfling|Giant|Gnoll|Goblin|Orc|Terran|Undercommon|Abyssal|Celestial|Draconic|Infernal|Sylvan|Druidic|Aboleth|Aquan|Auran|Blink Dog|Ettin Pidgin|Formian|Grimlock|Ignan|Sahuagin|Sphinx|Treant|Worg|TITLE=Language

### Int. Item - Language Choice 4

- **NAMEOPT:** NOTHING
- **ITYPE:** Lang4
- **PRETYPE:** 1,Lang3
- **!PRETYPE:** 1,Lang4
- **SPROP:** %CHOICE
- **CHOOSE:** STRING|Common|Dwarven|Elven|Gnome|Halfling|Giant|Gnoll|Goblin|Orc|Terran|Undercommon|Abyssal|Celestial|Draconic|Infernal|Sylvan|Druidic|Aboleth|Aquan|Auran|Blink Dog|Ettin Pidgin|Formian|Grimlock|Ignan|Sahuagin|Sphinx|Treant|Worg|TITLE=Language

### Wield One Step Greater

- **BONUS:** WEAPON|WIELDCATEGORY|-1

### Wield Two Step Greater

- **BONUS:** WEAPON|WIELDCATEGORY|-2

### Wield Three Step Greater

- **BONUS:** WEAPON|WIELDCATEGORY|-3

### Wield One Step Greater No Penalty

- **BONUS:** WEAPON|WIELDCATEGORY|-1
- **BONUS:** WEAPON|TOHIT|2

### Wield Two Step Greater No Penalty

- **BONUS:** WEAPON|WIELDCATEGORY|-2
- **BONUS:** WEAPON|TOHIT|4

### Wield Three Step Greater No Penalty

- **BONUS:** WEAPON|WIELDCATEGORY|-3
- **BONUS:** WEAPON|TOHIT|6

### Adamantine

- **COST:** 60
- **ITYPE:** Metal.Adamantine.Masterwork
- **REPLACES:** Masterwork (Weapon)
- **PRETYPE:** 1,Metal
- **SPROP:** Ignore 20 hardness
- **ASSIGNTOALL:** NO

### Mithral

- **COST:** 1000
- **ITYPE:** Metal.Mithral.Masterwork
- **REPLACES:** Masterwork (Armor)
- **PRETYPE:** 1,Light
- **PRETYPE:** 1,Metal
- **BONUS:** EQM|WEIGHTDIV|2|TYPE=Enhancement.REPLACE
- **BONUS:** EQMARMOR|ACCHECK|3|TYPE=Enhancement.REPLACE
- **BONUS:** EQMARMOR|MAXDEX|2
- **BONUS:** EQMARMOR|SPELLFAILURE|-10|TYPE=Enhancement
- **SPROP:** 30hp/inch and 15 hardness

### Darkwood

- **COST:** WT*10
- **ITYPE:** Wooden.Darkwood.Masterwork
- **REPLACES:** Masterwork (Armor),Masterwork (Weapon)
- **PRETYPE:** 1,Wood,Wooden
- **BONUS:** EQM|WEIGHTDIV|2
- **BONUS:** EQMARMOR|ACCHECK|2|TYPE=Enhancement
- **BONUS:** ITEMCOST|TYPE.Ammunition|6
- **BONUS:** ITEMCOST|TYPE.Weapon|300
- **BONUS:** ITEMCOST|TYPE.Shield|150
- **BONUS:** WEAPON|TOHIT|1|TYPE=Enhancement
- **SPROP:** 10hp/inch and 5 hardness
- **ASSIGNTOALL:** YES
- **BONUS:** VAR|ArmorCheckPenalty|2

### Dragonhide

- **COST:** BASECOST+300
- **ITYPE:** Dragonhide.Nonmetal.Masterwork
- **REPLACES:** Masterwork (Armor)
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement
- **SPROP:** 10hp/inch and 10 hardness
- **ASSIGNTOALL:** NO

### Cold Iron

- **COST:** (BASECOST)
- **ITYPE:** Metal.ColdIron
- **PRETYPE:** 1,Weapon,Ammunition
- **PRETYPE:** 1,Metal
- **BONUS:** ITEMCOST|TYPE.Enhancement.Ammunition|40
- **BONUS:** ITEMCOST|TYPE.Enhancement.Weapon|2000
- **SPROP:** 30hp/inch and 10 hardness
- **ASSIGNTOALL:** NO

### Alchemical Silver

- **COST:** 0
- **ITYPE:** Metal.Silver
- **PRETYPE:** 1,Weapon,Ammunition
- **PRETYPE:** 1,Metal
- **!PRETYPE:** 1,Mithral,Adamantine,ColdIron,Silver
- **BONUS:** ITEMCOST|TYPE.Ammunition|2
- **BONUS:** ITEMCOST|TYPE.Weapon|20
- **BONUS:** ITEMCOST|TYPE.Weapon|90
- **BONUS:** ITEMCOST|TYPE.Weapon|180
- **BONUS:** WEAPON|DAMAGE|-1|TYPE=Enhancement.STACK
- **SPROP:** 10hp/inch and 8 hardness
- **ASSIGNTOALL:** NO

### Ironwood

- **COST:** 0
- **ITYPE:** Wooden.Magic.Ironwood
- **SPROP:** Wooden but functions as steel, does not burn
- **ASSIGNTOALL:** YES

### Ironwood (+1)

- **COST:** 0
- **ITYPE:** Wooden.Magic.Ironwood
- **BONUS:** COMBAT|AC|1|TYPE=ArmorEnhancement|!PRETYPE:1,Enhancement
- **BONUS:** COMBAT|AC|1|TYPE=ShieldEnhancement|!PRETYPE:1,Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** Wooden but functions as steel, does not burn
- **ASSIGNTOALL:** YES

### Acid Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|AcidResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Acid damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)

### Acid Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|AcidResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Acid damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)

### Acid Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|AcidResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Acid damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)

### Anarchic

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** chaos-aligned,+2d6 chaotic damage vs. law,1 negative level bestowed to lawful wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Animated

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Shield
- **BONUS:** EQM|HANDS|-EQHANDS
- **SPROP:** floats in front of character requiring no hands, but still take normal penalties

### Arrow Catching

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** attracts ranged weapons to it;grants +1(Deflection) vs ranged weapons

### Arrow Deflection

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** Reflex save(DC 20+Missile enhancment) to deflect arrows;1/round
- **ABILITY:** FEAT|VIRTUAL|Deflect Arrows

### Axiomatic

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** law-aligned,+2d6 lawful damage vs. chaos,1 negative level bestowed to chaotic wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Bane

- **PLUS:** 1
- **PRETYPE:** 1,Enhancement
- **PRETYPE:** 1,Weapon,Ammunition
- **SPROP:** +2 enhancement bonus and does +2d6 bonus damage vs. %CHOICE
- **CHOOSE:** STRING|Aberrations|Animals|Constructs|Dragons|Elementals|Fey|Giants|Humanoids (aquatic)|Humanoids (dwarf)|Humanoids (elf)|Humanoids (gnoll)|Humanoids (gnome)|Humanoids (goblinoid)|Humanoids (halfling)|Humanoids (human)|Humanoids (reptilian)|Humanoids (orc)|Magical beasts|Monstrous humanoids|Oozes|Outsiders (air)|Outsiders (chaotic)|Outsiders (earth)|Outsiders (evil)|Outsiders (fire)|Outsiders (good)|Outsiders (lawful)|Outsiders (water)|Plants|Undead|Vermin|TITLE=Designated Foe

### Bashing

- **PLUS:** 1
- **ITYPE:** Bashing.Weapon.Melee
- **PRETYPE:** 2,Enhancement,Heavy
- **BONUS:** EQMWEAPON|DAMAGESIZE|2
- **SPROP:** Damage dice increases to 1d8

### Blinding

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** Flashes light 2/day upon command;Within 20 feet make a Reflex save(DC 14) or be blinded for 1d4 rounds

### Brilliant Energy

- **PLUS:** 4
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** ignores armor and armor enhancement,cannot harm undead,constructs,objects

### Cold Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ColdResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Cold damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)

### Cold Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ColdResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Cold damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)

### Cold Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ColdResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Cold damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)

### Dancing

- **PLUS:** 4
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can be loosed to attack on its own
- **ASSIGNTOALL:** YES

### Defending

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can transfer some or all of sword's enhancement bonus to AC
- **ASSIGNTOALL:** YES

### Disruption

- **PLUS:** 2
- **PRETYPE:** 3,Enhancement,Weapon,Bludgeoning
- **SPROP:** undead hit must make Will save (DC 14) or be destroyed

### Distance

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** EQMWEAPON|RANGEMULT|2
- **SPROP:** range increment doubled
- **ASSIGNTOALL:** YES

### Electricity Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ElectricityResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Electricity damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)

### Electricity Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ElectricityResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Electricity damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)

### Electricity Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ElectricityResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Electricity damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)

### Etherealness

- **COST:** 49000
- **PRETYPE:** 2,Enhancement,Armor
- **SPROP:** to become ethereal (as the Ethereal Jaunt spell) 1/day

### Fire Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|FireResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Fire damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)

### Fire Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|FireResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Fire damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)

### Fire Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|FireResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Fire damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)

### Flaming

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 fire damage

### Flaming Burst

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 fire damage. On a critical hit deals +%d10 additional fire damage|CRITMULT-1

### Fortification (Heavy)

- **PLUS:** 5
- **REPLACES:** Fortification (Light),Fortification (Moderate)
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** Critical and Sneak Attack bonus damage negated(100%% of time)

### Fortification (Light)

- **PLUS:** 1
- **REPLACES:** Fortification (Heavy),Fortification (Moderate)
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** Critical and Sneak Attack bonus damage negated(25%% of time)

### Fortification (Moderate)

- **PLUS:** 3
- **REPLACES:** Fortification (Heavy),Fortification (Light)
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** Critical and Sneak Attack bonus damage negated(75%% of time)

### Frost

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 cold damage

### Ghost touch

- **PLUS:** 3
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** armor and enhancement count vs. incorporeal attacks

### Glamered

- **COST:** 2700
- **PRETYPE:** 2,Enhancement,Armor
- **SPROP:** can appear as normal clothing on command

### Holy

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** good-aligned,+2d6 holy damage vs. evil,1 negative level bestowed to evil wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Icy Burst

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 cold damage. On a critical hit deals +%d10 additional cold damage|CRITMULT-1

### Invulnerability

- **PLUS:** 3
- **PRETYPE:** 2,Enhancement,Armor
- **DR:** 5/Magic

### Keen

- **PLUS:** 1
- **PREMULT:** 3,[PRETYPE:1,Enhancement],[PRETYPE:1,Weapon],[PRETYPE:1,Piercing,Slashing]
- **BONUS:** EQMWEAPON|CRITRANGEDOUBLE|1|TYPE=NonStackingCrit
- **SPROP:** threat range doubled

### Ki Focus

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can use ki attacks through weapon

### Merciful

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** deals extra 1d6 damage,deals subdual damage unless otherwise desired

### Mighty Cleaving

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **BONUS:** VAR|CleaveCount|1
- **SPROP:** allows 1 extra cleave per round (need Cleave feat)

### Reflecting

- **PLUS:** 5
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** spell turning/1 day

### Returning

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Thrown
- **SPROP:** when thrown will return just before thrower's next turn
- **ASSIGNTOALL:** YES

### Seeking

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** veers to target negating any miss chance

### Shadow

- **COST:** 3750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Hide|5|TYPE=Competence
- **SPROP:** +5 competence bonus to wearer's Hide checks

### Shadow (Greater)

- **COST:** 33750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Hide|15|TYPE=Competence
- **SPROP:** +15 competence bonus to wearer's Hide checks

### Shadow (Improved)

- **COST:** 15000
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Hide|10|TYPE=Competence
- **SPROP:** +10 competence bonus to wearer's Hide checks

### Shock

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 electricity damage

### Shocking Burst

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 electricity damage. On a critical hit deals +%d10 additional electricity damage|CRITMULT-1

### Silent moves

- **COST:** 3750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Move Silently|5|TYPE=Competence
- **SPROP:** +5 competence bonus to wearer's Move Silent checks

### Silent moves (Greater)

- **COST:** 33750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Move Silently|15|TYPE=Competence
- **SPROP:** +15 competence bonus to wearer's Move Silent checks

### Silent moves (Improved)

- **COST:** 15000
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Move Silently|10|TYPE=Competence
- **SPROP:** +10 competence bonus to wearer's Move Silent checks

### Slick

- **COST:** 3750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Escape Artist|5|TYPE=Competence
- **SPROP:** +5 competence bonus to wearer's Escape Artist checks

### Slick (Greater)

- **COST:** 33750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Escape Artist|15|TYPE=Competence
- **SPROP:** +15 competence bonus to wearer's Escape Artist checks

### Slick (Improved)

- **COST:** 15000
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Escape Artist|10|TYPE=Competence
- **SPROP:** +10 competence bonus to wearer's Escape Artist checks

### Sonic Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|SonicResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Sonic damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)

### Sonic Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|SonicResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Sonic damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)

### Sonic Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|SonicResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Sonic damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)

### Speed

- **PLUS:** 3
- **PRETYPE:** 2,Enhancement,Weapon
- **BONUS:** WEAPON|ATTACKS|1
- **SPROP:** grants 1 extra attack when full attacking at highest bonus,does not stack with other speed effects

### Spell Resistance

- **PLUS:** 2
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SR:** 13
- **SPROP:** spell resistance 13

### Spell Storing

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can store a single targeted spell of up to 3rd level with a casting time of 1 action

### Throwing

- **PLUS:** 1
- **ITYPE:** Ranged
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **BONUS:** EQMWEAPON|RANGEADD|10
- **SPROP:** can be thrown with a range increment of 10 ft by those proficient in its use
- **ASSIGNTOALL:** YES

### Thundering

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +%d8 sonic damage on critical and permanently deafened unless save vs Fort (DC 14)|CRITMULT-1

### Undead controlling

- **COST:** 49000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** As the control undead spell may control(up to 26HD of undead/day)

### Unholy

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** evil-aligned,+2d6 unholy damage vs. good,1 negative level bestowed to good wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### Vicious

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** deals extra 2d6 damage to target plus 1d6 damage to user.

### Vorpal

- **PLUS:** 5
- **PRETYPE:** 4,Enhancement,Weapon,Melee,Slashing
- **SPROP:** severs opponent's head on natural 20 critical hit

### Wild

- **PLUS:** 3
- **PRETYPE:** 2,Enhancement,Armor
- **SPROP:** preserve armor and enhancment bonus while in wild shape

### Wounding

- **PLUS:** 2
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** Blood loss causes 1 pt of Con damage per hit

### OLD Acid Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|AcidResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Acid damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)

### OLD Acid Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|AcidResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Acid damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)

### OLD Acid Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|AcidResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Acid damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)

### OLD Anarchic

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** chaos-aligned,+2d6 chaotic damage vs. law,1 negative level bestowed to lawful wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### OLD Animated

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Shield
- **BONUS:** EQM|HANDS|-EQHANDS
- **SPROP:** floats in front of character requiring no hands, but still take normal penalties

### OLD Arrow Catching

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** attracts ranged weapons to it;grants +1(Deflection) vs ranged weapons

### OLD Arrow Deflection

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** Reflex save(DC 20+Missile enhancment) to deflect arrows;1/round
- **ABILITY:** FEAT|VIRTUAL|Deflect Arrows

### OLD Axiomatic

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** law-aligned,+2d6 lawful damage vs. chaos,1 negative level bestowed to chaotic wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### OLD Bane

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +2 enhancement bonus and does +2d6 bonus damage vs. %CHOICE
- **CHOOSE:** STRING|Aberrations|Animals|Constructs|Dragons|Elementals|Fey|Giants|Humanoids (aquatic)|Humanoids (dwarf)|Humanoids (elf)|Humanoids (gnoll)|Humanoids (gnome)|Humanoids (goblinoid)|Humanoids (halfling)|Humanoids (human)|Humanoids (reptilian)|Humanoids (orc)|Magical beasts|Monstrous humanoids|Oozes|Outsiders (air)|Outsiders (chaotic)|Outsiders (earth)|Outsiders (evil)|Outsiders (fire)|Outsiders (good)|Outsiders (lawful)|Outsiders (water)|Plants|Undead|Vermin|TITLE=Designated Foe

### OLD Bashing

- **PLUS:** 1
- **ITYPE:** Bashing.Weapon.Melee
- **PRETYPE:** 2,Enhancement,Shield
- **BONUS:** VAR|ShieldBashingDieSizeStep|2
- **BONUS:** EQMWEAPON|DAMAGESIZE|2
- **SPROP:** damage dice increases by one step

### OLD Blinding

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** Flashes light 2/day upon command;Within 20 feet make a Reflex save(DC 14) or be blinded for 1d4 rounds

### OLD Brilliant Energy

- **PLUS:** 4
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** ignores armor and armor enhancement,cannot harm undead,constructs,objects

### OLD Cold Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ColdResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Cold damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)

### OLD Cold Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ColdResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Cold damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)

### OLD Cold Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ColdResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Cold damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Cold (Sp)

### OLD Dancing

- **PLUS:** 4
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can be loosed to attack on its own
- **ASSIGNTOALL:** YES

### OLD Defending

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can transfer some or all of sword's enhancement bonus to AC
- **ASSIGNTOALL:** YES

### OLD Disruption

- **PLUS:** 2
- **PRETYPE:** 3,Enhancement,Weapon,Bludgeoning
- **SPROP:** undead hit must make Will save (DC 14) or be destroyed

### OLD Distance

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** EQMWEAPON|RANGEMULT|2
- **SPROP:** range increment doubled
- **ASSIGNTOALL:** YES

### OLD Electricity Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ElectricityResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Electricity damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)

### OLD Electricity Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ElectricityResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Electricity damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)

### OLD Electricity Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|ElectricityResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Electricity damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Electricity (Sp)

### OLD Etherealness

- **COST:** 49000
- **PRETYPE:** 2,Enhancement,Armor
- **SPROP:** to become ethereal (as the Ethereal Jaunt spell) 1/day

### OLD Fire Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|FireResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Fire damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)

### OLD Fire Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|FireResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Fire damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)

### OLD Fire Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|FireResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Fire damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)

### OLD Flaming

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 fire damage

### OLD Flaming Burst

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 fire damage. On a critical hit deals +%d10 additional fire damage|CRITMULT-1

### OLD Fortification (Heavy)

- **PLUS:** 5
- **REPLACES:** FRT_LGHT,FRT_MOD
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** Critical and Sneak Attack bonus damage negated(100%% of time)

### OLD Fortification (Light)

- **PLUS:** 1
- **REPLACES:** FRT_HVY,FRT_MOD
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** Critical and Sneak Attack bonus damage negated(25%% of time)

### OLD Fortification (Moderate)

- **PLUS:** 3
- **REPLACES:** FRT_HVY,FRT_LGHT
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** Critical and Sneak Attack bonus damage negated(75%% of time)

### OLD Frost

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 cold damage

### OLD Ghost touch

- **PLUS:** 3
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** armor and enhancement count vs. incorporeal attacks

### OLD Glamered

- **COST:** 2700
- **PRETYPE:** 2,Enhancement,Armor
- **SPROP:** can appear as normal clothing on command

### OLD Holy

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** good-aligned,+2d6 holy damage vs. evil,1 negative level bestowed to evil wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### OLD Icy Burst

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 cold damage. On a critical hit deals +%d10 additional cold damage|CRITMULT-1

### OLD Invulnerability

- **PLUS:** 3
- **PRETYPE:** 2,Enhancement,Armor
- **DR:** 5/Magic

### OLD Ki Focus

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can use ki attacks through weapon

### OLD Merciful

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** deals extra 1d6 damage,deals subdual damage unless otherwise desired

### OLD Mighty Cleaving

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **BONUS:** VAR|CleaveCount|1
- **SPROP:** allows 1 extra cleave per round (need Cleave feat)

### OLD Reflecting

- **PLUS:** 5
- **PRETYPE:** 2,Enhancement,Shield
- **SPROP:** spell turning/1 day

### OLD Returning

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Thrown
- **SPROP:** when thrown will return just before thrower's next turn
- **ASSIGNTOALL:** YES

### OLD Seeking

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** veers to target negating any miss chance

### OLD Shadow

- **COST:** 3750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Hide|5|TYPE=Competence
- **SPROP:** +5 competence bonus to wearer's Hide checks

### OLD Shadow (Greater)

- **COST:** 33750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Hide|15|TYPE=Competence
- **SPROP:** +15 competence bonus to wearer's Hide checks

### OLD Shadow (Improved)

- **COST:** 15000
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Hide|10|TYPE=Competence
- **SPROP:** +10 competence bonus to wearer's Hide checks

### OLD Shock

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 electricity damage

### OLD Shocking Burst

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +1d6 electricity damage. On a critical hit deals +%d10 additional electricity damage|CRITMULT-1

### OLD Silent moves

- **COST:** 3750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Move Silently|5|TYPE=Competence
- **SPROP:** +5 competence bonus to wearer's Move Silent checks

### OLD Silent moves (Greater)

- **COST:** 33750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Move Silently|15|TYPE=Competence
- **SPROP:** +15 competence bonus to wearer's Move Silent checks

### OLD Silent moves (Improved)

- **COST:** 15000
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Move Silently|10|TYPE=Competence
- **SPROP:** +10 competence bonus to wearer's Move Silent checks

### OLD Slick

- **COST:** 3750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Escape Artist|5|TYPE=Competence
- **SPROP:** +5 competence bonus to wearer's Escape Artist checks

### OLD Slick (Greater)

- **COST:** 33750
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Escape Artist|15|TYPE=Competence
- **SPROP:** +15 competence bonus to wearer's Escape Artist checks

### OLD Slick (Improved)

- **COST:** 15000
- **PRETYPE:** 2,Enhancement,Armor
- **BONUS:** SKILL|Escape Artist|10|TYPE=Competence
- **SPROP:** +10 competence bonus to wearer's Escape Artist checks

### OLD Sonic Resistance

- **COST:** 18000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|SonicResistanceBonusSp|10|TYPE=Base
- **SPROP:** absorbs 10 points of Sonic damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)

### OLD Sonic Resistance (Greater)

- **COST:** 66000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|SonicResistanceBonusSp|30|TYPE=Base
- **SPROP:** absorbs 30 points of Sonic damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)

### OLD Sonic Resistance (Improved)

- **COST:** 42000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **BONUS:** VAR|SonicResistanceBonusSp|20|TYPE=Base
- **SPROP:** absorbs 20 points of Sonic damage per attack
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Sonic (Sp)

### OLD Spell Resistance

- **PLUS:** 2
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SR:** 13
- **SPROP:** spell resistance 13

### OLD Spell Storing

- **PLUS:** 1
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** can store a single targeted spell of up to 3rd level with a casting time of 1 action

### OLD Throwing

- **PLUS:** 1
- **ITYPE:** Ranged
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **BONUS:** EQMWEAPON|RANGEADD|10
- **SPROP:** can be thrown with a range increment of 10 ft by those proficient in its use
- **ASSIGNTOALL:** YES

### OLD Thundering

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Ammunition
- **SPROP:** +%d8 sonic damage on critical and permanently deafened unless save vs Fort (DC 14)|CRITMULT-1

### OLD Undead controlling

- **COST:** 49000
- **PREMULT:** 2,[PRETYPE:1,Enhancement],[PRETYPE:1,Armor,Shield]
- **SPROP:** As the control undead spell may control(up to 26HD of undead/day)

### OLD Unholy

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Ammunition
- **BONUS:** VAR|NegLevels|1
- **SPROP:** evil-aligned,+2d6 unholy damage vs. good,1 negative level bestowed to good wielder
- **ABILITY:** Special Ability|AUTOMATIC|Negative Levels

### OLD Wild

- **PLUS:** 3
- **PRETYPE:** 2,Enhancement,Armor
- **SPROP:** preserve armor and enhancment bonus while in wild shape

### OLD Wounding

- **PLUS:** 2
- **PRETYPE:** 3,Enhancement,Weapon,Melee
- **SPROP:** Blood loss causes 1 pt of Con damage per hit

### OLD Adamantine

- **COST:** 60
- **ITYPE:** Metal.Adamantine.Masterwork
- **REPLACES:** Masterwork (Weapon)
- **PRETYPE:** 1,Metal
- **SPROP:** Ignore 20 hardness
- **ASSIGNTOALL:** NO

### OLD Mithral

- **COST:** 1000
- **ITYPE:** Metal.Mithral.Masterwork
- **REPLACES:** Masterwork (Armor)
- **PRETYPE:** 1,Light
- **PRETYPE:** 1,Metal
- **BONUS:** EQM|WEIGHTDIV|2|TYPE=Enhancement.REPLACE
- **BONUS:** EQMARMOR|ACCHECK|3|TYPE=Enhancement.REPLACE
- **BONUS:** EQMARMOR|MAXDEX|2
- **BONUS:** EQMARMOR|SPELLFAILURE|-10|TYPE=Enhancement
- **SPROP:** 30hp/inch and 15 hardness

### OLD Darkwood

- **COST:** WT*10
- **ITYPE:** Wooden.Darkwood.Masterwork
- **REPLACES:** Masterwork (Armor),Masterwork (Weapon)
- **PRETYPE:** 1,Wooden
- **BONUS:** EQM|WEIGHTDIV|2
- **BONUS:** EQMARMOR|ACCHECK|2|TYPE=Enhancement
- **BONUS:** ITEMCOST|TYPE.Ammunition|6
- **BONUS:** ITEMCOST|TYPE.Weapon|300
- **BONUS:** ITEMCOST|TYPE.Shield|150
- **BONUS:** WEAPON|TOHIT|1|TYPE=Enhancement
- **SPROP:** 10hp/inch and 5 hardness
- **ASSIGNTOALL:** YES

### OLD Dragonhide

- **COST:** BASECOST+300
- **ITYPE:** Dragonhide.Nonmetal.Masterwork
- **REPLACES:** Masterwork (Armor)
- **BONUS:** EQMARMOR|ACCHECK|1|TYPE=Enhancement
- **SPROP:** 10hp/inch and 10 hardness
- **ASSIGNTOALL:** NO

### OLD Cold Iron

- **COST:** (BASECOST)
- **ITYPE:** Metal.ColdIron
- **PRETYPE:** 1,Weapon,Ammunition
- **PRETYPE:** 1,Metal
- **BONUS:** ITEMCOST|TYPE.Enhancement.Ammunition|40
- **BONUS:** ITEMCOST|TYPE.Enhancement.Weapon|2000
- **SPROP:** 30hp/inch and 10 hardness
- **ASSIGNTOALL:** NO

### OLD Alchemical Silver

- **COST:** 0
- **ITYPE:** Metal.Silver
- **PRETYPE:** 1,Weapon,Ammunition
- **PRETYPE:** 1,Metal
- **!PRETYPE:** 1,Mithral,Adamantine,ColdIron,Silver
- **BONUS:** ITEMCOST|TYPE.Ammunition|2
- **BONUS:** ITEMCOST|TYPE.Weapon|20
- **BONUS:** ITEMCOST|TYPE.Weapon|90
- **BONUS:** ITEMCOST|TYPE.Weapon|180
- **BONUS:** WEAPON|DAMAGE|-1|TYPE=Enhancement.STACK
- **SPROP:** 10hp/inch and 8 hardness
- **ASSIGNTOALL:** NO

### OLD Ironwood

- **COST:** 0
- **ITYPE:** Wooden.Magic.Ironwood
- **SPROP:** Wooden but functions as steel, does not burn
- **ASSIGNTOALL:** YES

### OLD Ironwood (+1)

- **COST:** 0
- **ITYPE:** Wooden.Magic.Ironwood
- **BONUS:** COMBAT|AC|1|TYPE=ArmorEnhancement|!PRETYPE:1,Enhancement
- **BONUS:** COMBAT|AC|1|TYPE=ShieldEnhancement|!PRETYPE:1,Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **BONUS:** WEAPON|DAMAGE,TOHIT|1|TYPE=Enhancement
- **SPROP:** Wooden but functions as steel, does not burn
- **ASSIGNTOALL:** YES

## Feats

### Improved Familiar


This feat allows spellcasters to acquire a new familiar from a nonstandard list, but only when they could normally acquire a new familiar.

### Tattoo Focus

- **PRETEXT:** From Thay, Specialized in a school of magic.

You bear the powerful magical tattoos of a Red Wizard of Thay.

Add +1 to the DC for all saving throws against spells from your specialized school. You get a +1 bonus on caster level checks (1d20 + caster level) to overcome a creature's spell resistance when casting spells from that school. Special: Only characters with the Tattoo Focus feat can participate in Red Wizard circle magic (see below).

### Exotic Weapon Proficiency (Firearms)

- **AUTO:** WEAPONPROF|TYPE=Firearms
- **PRETOTALAB:** 1

You understand how to use firearms in combat.

### Exotic Weapon Proficiency (Futuristic)

- **AUTO:** WEAPONPROF|TYPE=Futuristic
- **PRETOTALAB:** 1

You understand how to use futuristic weapons in combat.

## Kits

### STARTPACK:NPC Funds Lv 01

- **APPLY:** INSTANT

### FUNDS:gp

- **QTY:** 900

### STARTPACK:NPC Funds Lv 02

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 03

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 04

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 05

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 06

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 07

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 08

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 09

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 10

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 11

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 12

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 13

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 14

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 15

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 16

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 17

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 18

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 19

- **APPLY:** INSTANT

### STARTPACK:NPC Funds Lv 20

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 02

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 03

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 04

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 05

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 06

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 07

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 08

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 09

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 10

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 11

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 12

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 13

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 14

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 15

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 16

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 17

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 18

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 19

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 20

- **APPLY:** INSTANT

### STARTPACK:PC Funds Lv 1

- **APPLY:** INSTANT

## Profs Weapon

### Blowgun


### Kusari-Gama


### Pistol


### Musket


### NoProfReq


### Pistol (Automatic)


### Pistol (Revolver


### Rifle (Hunting)


### Rifle (Automatic)


### Shotgun


### Grenade Launcher


### Laser Pistol


### Antimatter Rifle


### Laser Rifle


### Flamer


## Spells

### Corrupt Weapon

- **CLASSES:** Blackguard=1
- **SCHOOL:** Transmutation
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **ITEM:** Potion
- **TARGETAREA:** Weapon touched
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** None
- **SPELLRES:** No

Weapon strikes true against good foes.

## Templates

### Dragon Disciple Attacks

- **TEMPLATE:** CHOOSE:Dragon Disciple Attacks Small|Dragon Disciple Attacks Medium|Dragon Disciple Attacks Large

### Dragon Disciple Attacks Small

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Bludgeoning.Piercing.Slashing,*1,1d4|Claw,Weapon.Natural.Melee.Piercing.Slashing,*2,1d3

### Dragon Disciple Attacks Medium

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Bludgeoning.Piercing.Slashing,*1,1d6|Claw,Weapon.Natural.Melee.Piercing.Slashing,*2,1d4

### Dragon Disciple Attacks Large

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Bludgeoning.Piercing.Slashing,*1,1d8|Claw,Weapon.Natural.Melee.Piercing.Slashing,*2,1d6

### Disease Damage (Blinding Sickness)

- **TEMPVALUE:** MIN=1|MAX=4|TITLE=Stength Damage
- **TEMPDESC:** Infection DC 16 (Ingested), Incubation 1d3 days, Damage 1d4 Str (Each time the victim takes 2 or more damage from the disease, he must make another Fortitude save or be permanently blinded), Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|STR|-1*(%CHOICE)

### Disease Damage (Cackle Fever)

- **TEMPVALUE:** MIN=1|MAX=6|TITLE=Wisdom Damage
- **TEMPDESC:** Infection DC 16 (Inhaled), Incubation 1 day, Damage 1d6 Wis, Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|WIS|-1*(%CHOICE)

### Disease Damage (Demon Fever)

- **TEMPVALUE:** MIN=1|MAX=6|TITLE=Constitution Damage
- **TEMPDESC:** Infection DC 18 (Injury), Incubation 1 day, Damage 1d6 Con (When damaged, character must succeed on another saving throw or 1 point of damage is permanent drain instead), Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|CON|-1*(%CHOICE)

### Disease Damage (Devil Chills)

- **TEMPVALUE:** MIN=1|MAX=4|TITLE=Stength Damage
- **TEMPDESC:** Infection DC 14 (Injury), Incubation 1d4 days, Damage 1d4 Str (The victim must make three successful Fortitude saving throws in a row to recover from devil chills), Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|STR|-1*(%CHOICE)

### Disease Damage (Filth Fever/Dex Damage)

- **TEMPVALUE:** MIN=1|MAX=3|TITLE=Dexterity Damage
- **TEMPDESC:** Infection DC 12 (Injury), Incubation 1d3 days, Damage 1d3 Dex, 1d3 Con, Apply this temporary bonus for the dexterity damage each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|DEX|-1*(%CHOICE)

### Disease Damage (Filth Fever/Con Damage)

- **TEMPVALUE:** MIN=1|MAX=3|TITLE=Constitution Damage
- **TEMPDESC:** Infection DC 12 (Injury), Incubation 1d3 days, Damage 1d3 Dex, 1d3 Con, Apply this temporary bonus for the constitution damage each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|Con|-1*(%CHOICE)

### Disease Damage (Mindfire)

- **TEMPVALUE:** MIN=1|MAX=4|TITLE=Intelligence Damage
- **TEMPDESC:** Infection DC 12 (Inhaled), Incubation 1 day, Damage 1d4 Int, Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|INT|-1*(%CHOICE)

### Disease Damage (Mummy Rot)

- **TEMPVALUE:** MIN=1|MAX=6|TITLE=Constitution Damage
- **TEMPDESC:** Infection DC 20 (Contact), Incubation 1 day, Damage 1d6 Con (Successful saves do not allow the character to recover, Only magical healing can save the character), Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|CON|-1*(%CHOICE)

### Disease Damage (Red Ache)

- **TEMPVALUE:** MIN=1|MAX=6|TITLE=Stength Damage
- **TEMPDESC:** Infection DC 15 (Injury), Incubation 1d3 days, Damage 1d6 Str, Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|STR|-1*(%CHOICE)

### Disease Damage (Shakes)

- **TEMPVALUE:** MIN=1|MAX=8|TITLE=Dexterity Damage
- **TEMPDESC:** Infection DC 13 (Contact), Incubation 1 day, Damage 1d8 Dex, Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|DEX|-1*(%CHOICE)

### Disease Damage (Slimy Doom)

- **TEMPVALUE:** MIN=1|MAX=4|TITLE=Constitution Damage
- **TEMPDESC:** Infection DC 14 (Contact), Incubation 1 day, Damage 1d4 Con (When damaged, character must succeed on another saving throw or 1 point of damage is permanent drain instead), Apply this temporary bonus each day the victim takes damage.
- **TEMPBONUS:** ANYPC|STAT|STR|-1*(%CHOICE)

### Funds - PC

- **PRECLASS:** 1,TYPE.Base=1
- **KIT:** 1|PC Funds Lv 02|PC Funds Lv 03|PC Funds Lv 04|PC Funds Lv 05|PC Funds Lv 06|PC Funds Lv 07|PC Funds Lv 08|PC Funds Lv 09|PC Funds Lv 10|PC Funds Lv 11|PC Funds Lv 12|PC Funds Lv 1|PC Funds Lv 14|PC Funds Lv 15|PC Funds Lv 16|PC Funds Lv 17|PC Funds Lv 18|PC Funds Lv 19|PC Funds Lv 20

Adds starting funds for PC

### Funds - NPC

- **PRECLASS:** 1,TYPE.Base=1
- **KIT:** 1|NPC Funds Lv 01|NPC Funds Lv 02|NPC Funds Lv 03|NPC Funds Lv 04|NPC Funds Lv 05|NPC Funds Lv 06|NPC Funds Lv 07|NPC Funds Lv 08|NPC Funds Lv 09|NPC Funds Lv 10|NPC Funds Lv 11|NPC Funds Lv 12|NPC Funds Lv 13|NPC Funds Lv 14|NPC Funds Lv 15|NPC Funds Lv 16|NPC Funds Lv 17|NPC Funds Lv 18|NPC Funds Lv 19|NPC Funds Lv 20

Adds starting funds for NPC

### Funds - None


Adds no starting funds

### First Level

- **CHOOSE:** TEMPLATE|QUALIFIED[TYPE=First Level]
- **TEMPLATE:** %LIST

### First Level ~ Barbarian

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Barbarian=1

Specify initial starting funds for class Barbarian

### First Level ~ Bard

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Bard=1

Specify initial starting funds for class Bard

### First Level ~ Cleric

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Cleric=1

Specify initial starting funds for class Cleric

### First Level ~ Druid

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Druid=1

Specify initial starting funds for class Druid

### First Level ~ Fighter

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Fighter=1

Specify initial starting funds for class Fighter

### First Level ~ Monk

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Monk=1

Specify initial starting funds for class Monk

### First Level ~ Rogue

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Rogue=1

Specify initial starting funds for class Rogue

### First Level ~ Ranger

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Ranger=1

Specify initial starting funds for class Ranger

### First Level ~ Paladin

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Paladin=1

Specify initial starting funds for class Paladin

### First Level ~ Sorcerer

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Sorcerer=1

Specify initial starting funds for class Sorceror

### First Level ~ Wizard

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None
- **PRECLASS:** 1,Wizard=1

Specify initial starting funds for class Wizard

### First Level ~ Not Listed

- **TEMPLATE:** CHOOSE:Funds - PC|Funds - NPC|Funds - None

Specifies starting funds - use class specific instead, if listed


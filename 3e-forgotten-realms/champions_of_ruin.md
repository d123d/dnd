# Champions of Ruin

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Special Abilities

### Draegloth Racial Trait Default


### Darkvision

- **BONUS:** VAR|RacialVision|1
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

Draegloth can see in the dark up to %1 feet. Darkvision is black and white only, but it is otherwise like normal sight, and Draegloths can function just fine with no light at all.|DarkvisionRange

### Draegloth Resistance

- **ASPECT:** SaveBonus|+%1 racial saving throw bonus against enchantment spells or effects.|DraeglothSaveBonus
- **DEFINE:** DraeglothSaveBonus|0
- **BONUS:** VAR|DraeglothSaveBonus|2

Immunity to magic sleep effects, and a +%1 racial saving throw bonus against enchantment spells or effects.|DraeglothSaveBonus

### Weapon and Armor Proficiency

- **AUTO:** WEAPONPROF|TYPE=Simple

You are proficient with all simple weapons, but no armor or shields.

### Feats


Your racial class hitdice provides an extra feat at first, fourth, and tenth level.

### Natural Attacks

- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Piercing.Slashing,*2,1d4
- **PREMULT:** 2,[PREVARGTEQ:DraeglothLVL,1],[PREVARLT:DraeglothLVL,3]

You have 2 claw attacks at 1d4 each.

### Energy Resistance

- **ABILITY:** Special Ability|AUTOMATIC|Resistance To Acid|Resistance To Cold|Resistance to Electricity|Resistance To Fire
- **BONUS:** VAR|AcidResistanceBonus|DraeglothEnergyRes|TYPE=Resistance
- **BONUS:** VAR|ColdResistanceBonus|DraeglothEnergyRes|TYPE=Resistance
- **BONUS:** VAR|ElectricityResistanceBonus|DraeglothEnergyRes|TYPE=Resistance
- **BONUS:** VAR|FireResistanceBonus|DraeglothEnergyRes|TYPE=Resistance
- **DEFINE:** DraeglothEnergyRes|0

You have Energy resistance (acid, cold, electricity, and fire) %1.|DraeglothEnergyRes

### Dancing Lights

- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=DraeglothHD|Dancing Lights

You can cast dancing lights 1/day as a sorcerer of your HD.

### Natural Armor


Your skin provides you a natural armor bonus of 1, and improves to 3 at level 7 and 5 at level 10.

### Faerie Fire

- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=DraeglothHD|Faerie Fire

You can cast faerie fire 1/day as a sorcerer of your HD.

### Darkness

- **DEFINE:** DarknessUses|0
- **SPELLS:** Innate|TIMES=DarknessUses|CASTERLEVEL=DraeglothHD|Darkness

You can cast darkness %1/day as a sorcerer of your HD.|DarknessUses

### Desecrate

- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=DraeglothHD|Desecrate

You can cast desecrate 1/day as a sorcerer of your HD.

### Poison Immunity

- **ABILITY:** Special Ability|AUTOMATIC|Immunity To Poison

### Unholy Blight

- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=DraeglothHD|Unholy Blight

You can cast unholy blight 1/day as a sorcerer of your HD.

### Large Size


Your size category is increased from Medium to Large. You also gain a 10-ft reach with your claw and melee attacks.

### Extaminaar Racial Trait Default


### Low-Light Vision

- **BONUS:** VAR|HasLowLightVision|1

An extaminaar can see twice as far as a human in starlight, moonlight, torchlight, and similar conditions of poor illumination. She retains the ability to distinguish color and detail under these conditions.

### Poison Resistance

- **ASPECT:** SaveBonus|+%1 racial bonus on saving throws against poison|ExtaminaarPoisonSaveBonus
- **BONUS:** VAR|ExtaminaarPoisonSaveBonus|2
- **DEFINE:** ExtaminaarPoisonSaveBonus|0

+%1 racial bonus on saving throws against poison|ExtaminaarPoisonSaveBonus

### Skill Bonus

- **BONUS:** SKILL|Swim|4|TYPE=Racial
- **BONUS:** SKILL|Escape Artist|2|TYPE=Racial

Extaminaars are comfortable in the water and their light frames make it easy for them to stay afloat, they receive a +4 bonus to Swim checks. They can easily wriggle their way out of sticky situations and receive a +2 bonus on Escape Artist checks.

### Racial Spells

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=TL|Speak with Animals
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Charm Animal

You can cast speak with animals (snakes only) at will and charm animal (snakes only) 3/day.

### Krinth Racial Trait Default


### Krinth Resistance

- **ASPECT:** SaveBonus|+%1 racial saving throw bonus against shadow spells or effects and +%2 against Fear effects.|KrinthSpellBonus|KrinthFearBonus
- **BONUS:** SAVE|BASE.Will|KrinthWillBonus
- **DEFINE:** KrinthWillBonus|0
- **DEFINE:** KrinthSpellBonus|0
- **DEFINE:** KrinthFearBonus|0
- **BONUS:** VAR|KrinthWillBonus,KrinthSpellBonus|1
- **BONUS:** VAR|KrinthFearBonus|4

Krinth have a +%1 racial saving throw bonus on all Will saves, an additional +%2 against spells and spell-like abilities with the shadow descriptor and a +%3 bonus on saves vs fear. Krinth are immune to the shaken effect.|KrinthWillBonus|KrinthSpellBonus|KrinthFearBonus

### Craven Save Penalty

- **ASPECT:** SaveBonus|-2 penalty on saves against fear

### Craven Sneak Attack Bonus


Add +%1 damage to any sneak attack roll.|TL

### Poison Save Immune Bonus

- **ASPECT:** SaveBonus|+1 circumstance on saves against poisons

### Feral Rage


Your black blood cultist level stacks with your barbarian levels for your rage ability. Additionally, when raging, you gain Natural Attacks.

### Damage Reduction

- **DR:** 0/Silver

You gain damage reduction overcome by silver.

### Improved Grapple

- **ABILITY:** FEAT|VIRTUAL|Improved Grapple

You gain the Improved Grapple feat even if you don't meet the requirements.

### Scent

- **ABILITY:** Special Ability|AUTOMATIC|Scent

You gain the scent ability.

### Stranglehold


You have learned to snap necks of fallen enemies, allowing you to administer a coup de grace with your bite attack as a move action.

### Savage Grapple


You deal damage as if you had hit with all of your natural weapons (including rend if you are raging) on a successful grapple check.

### Feral Form


You have gained great control over your bestial nature and can use your natural attacks even when not raging.

### Spells


You gain spells that are prepared as a ranger from the Justice of Weald and Woe list.

### Woodland Stride


You can move through any sort of undergrowth as the druid ability.

### SneakAttack


You gain sneak attack as a rogue. If you had it before, it is just improved as a rogue.

### Lucky Shot


Once per day as a free action, you can gain a +10 insight bonus to one attack roll with your longbow. You must declare the use before you roll.

### Trackless Step


You leave no trail in natural surroundings and cannot be tracked. You can leave a trail if you desire.

### Poison Use


You can create and extract natural poisons and apply them to weapons without any danger of harming yourself.

### Steady Hand


You can fire your bow without provoking attacks of opportunity. You can benefit from this only while wearing light or no armor.

### Hide in Plain Sight


You gain the ability to hide in plain sight as a ranger.

### Death Attack


You can study a target for 3 rounds and make an attack that has the possibility of paralyzing or killing the victim (Fort save DC20 + INT) as an assassin.

### Creature of Darkness

- **BONUS:** SKILL|Ride|-2

Animals can sense the death in you, causing them to fear you. All animals except bats, rats, and wolves have their attitude moved down one category when they first approach you. You have a -2 penalty on Ride checks.

### Hesitating Stare

- **DEFINE:** HesitatingStareTimes|0

You can force your opponents to confront their own mortality with a glance. You can do this %1 times per day even when you are surprised by glancing at a foe within 30 feet. The target must make a Will save (DC 10 + your class level/2 + CHA) or be stunned for 1 round.|HesitatingStareTimes

### Light Sensitivity


In sunlight or bright magical light, you are dazzled.

### Spider Climb

- **SPELLS:** Class|TIMES=(min(1,CHA))|CASTERLEVEL=classlevel("Night Mask Deathbringer")|Spider Climb

You can act as if you are under the influence of a spider climb spell up to your CHA mod times per day.

### Feral Sense

- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

You gain low light vision.

You gain Darkvision out to 60 ft.

### Speak with Creatures of the Night


You can speak with rats, bats, and wolves as if under the influence of a speak with animals spell.

### Ghost Step

- **DEFINE:** GhostStepTimes|0

%1 times per day you can make yourself invisible for 1 round. This is a swift action.|GhostStepTimes

### Lesser Blood Bond


You can break down the will of your enemies. You get your enemy to drink 3 drops of your blood. They are then effected by a charm person with a Will DC of 10 + your class level + CHA mod. You can have up to your CHA mod number of blood bonds active.

### Sneak Attack


You gain sneak attack as a rogue. If you had it before, it is just improved as a rogue.

### Improved Evasion


Your pseudo-vampiric celerity grants you supernatural reflexes. You take no damage on a Reflex save against area of effect attacks and half on a failed save. This can't help you if you are helpless.

### Slippery Mind


You mind is only partly mortal, allowing you to shrug off mental attacks and compulsions more easily than others. Any time you are affected by an enchantment spell or effect and fail your saving throw, you can attempt the save a second time 1 round later.

### Greater Blood Bond


Like lesser blood bond but the target is affected by a dominate person.

### Bonus Feat or Spells

- **BONUS:** ABILITYPOOL|Thrall of Eltab Bonus Ability|(ThrallOfEltabLVL+2)/3

When a thrall of Eltab attains 1st, 4th, 7th, and 10th level, the character gains new spells per day as if she had also gained a level in whatever spellcasting class she belonged to before she added the prestige class, or else she gains a bonus feat of her choice. If the thrall chooses +1 spellcasting level, she does not gain any other benefit a character of that class would have gained (improved chance of controlling or rebuking undead, metamagic or item creation feats, hit points beyond those received from the prestige class, and so on), except for an increased effective level of spellcasting. This essentially means that she adds the new level to the level of whatever other spellcasting class the character has, then determines spells per day, spells known, and caster level accordingly. If a character had more than one spellcasting class before she became a thrall of Eltab, she must decide to which class she adds the level for purposes of determining spells per day. A thrall of Eltab is free to choose the bonus feat at one opportunity and the spellcasting level the next time the decision arises, or vice versa. Characters who are not spellcasters must choose the bonus feat. Level: %1|ThrallOfEltabLVL

### Bone Spurs

- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Piercing,*1,1d6

A 1st-level thrall gains a profusion of sharp bone spurs emerging from his skull, which provide a gore attack (if they did not already have one).

### Scaly Flesh

- **BONUS:** COMBAT|AC|TOENaturalArmorAdjustment|TYPE=NaturalArmor

The thrall gains dark red, scaly flesh, which provides a +%1 natural armor bonus (beginning at 1 at 1st level and increasing at 4th, 7th, and 10th levels). The bonus stacks with natural sources but not magical sources.|TOENaturalArmorAdjustment

### Touch of Fear

- **SPELLS:** Innate|TIMES=3|TIMEUNIT=Day|CASTERLEVEL=10|Cause Fear,16

Three times per day, a thrall can produce an effect identical to a Cause Fear spell cast by a 10th level caster.

### Burrow

- **MOVE:** Burrow,10

A 3rd-level thrall can burrow at a speed of 10 feet; this does not stack.

### Summon Demon


Once per day, a thrall can summon a demon, at 5th level the demon's is 5HD or less, at 9th level this increases to 10HD or less. This ability functions as a Summon Monster spell cast by a 15th-level caster.

### Demoncyst Jump


Once per day, a thrall can produce an effect identical to a Teleport spell, as cast by a 10th level caster, while within a demoncyst to another demoncyst.

### Immunity to Electricity


An 8th-level thrall is immune to electricity.

### Death Gaze


At 10th level, a thrall gains a gaze attack: death, 30 feet, Fortitude DC %1 (10 + thrall's class level + CHA bonus).|(10+CL+CHA)

### Additional Spellcaster Level

- **ADD:** SPELLCASTER|ANY
- **CHOOSE:** NOCHOICE
- **MULT:** YES
- **STACK:** YES

### Bonus Feat

- **BONUS:** ABILITYPOOL|FEAT|1
- **CHOOSE:** NOCHOICE
- **MULT:** YES
- **STACK:** YES

## Ability Categories

### ABILITYCATEGORY:Thrall of Eltab Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Thrall of Eltab Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Thrall Of Eltab Bonus Ability

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **ABILITYLIST:** Demonic Thrall ~ Additional Spellcaster Level|Demonic Thrall ~ Bonus Feat
- **PLURAL:** Thrall Of Eltab Abilities
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Draegloth Racial Trait

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Draegloth Racial Abilities
- **DISPLAYLOCATION:** Racial Abilities

### ABILITYCATEGORY:Extaminaar Racial Trait

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Extaminaar Racial Abilities
- **DISPLAYLOCATION:** Racial Abilities

### ABILITYCATEGORY:Krinth Racial Trait

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Krinth Racial Abilities
- **DISPLAYLOCATION:** Racial Abilities

### ABILITYCATEGORY:JoWW Bonus Feat

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **PLURAL:** Justice of Weald and Woe Feats
- **DISPLAYLOCATION:** Feats
- **ABILITYLIST:** Deflect Arrows|Far Shot|Improved Critical (Longbow)|Improved Precise Shot|Manyshot|Mounted Archery|Precise Shot|Rapid Shot|Shot on the Run|Snatch Arrows|Weapon Specialization (Longbow)|Greater Weapon Focus (Longbow)|Greater Weapon Specialization (Longbow)

## Biosettings

### AGESET:2|Adult


### RACENAME:Draegloth

- **CLASS:** Barbarian,Draegloth,Rogue,Sorcerer,Soulknife,Wilder[BASEAGEADD:2d6]|Bard,Fighter,Paladin,Ranger,Psychic Warrior[BASEAGEADD:4d6]|Cleric,Druid,Monk,Psion,Shadowcaster,Wizard[BASEAGEADD:3d6]

### RACENAME:Extaminaar

- **CLASS:** Barbarian,Rogue,Sorcerer,Soulknife,Wilder[BASEAGEADD:1d4]|Bard,Fighter,Paladin,Ranger,Psychic Warrior[BASEAGEADD:1d6]|Cleric,Druid,Monk,Psion,Shadowcaster,Wizard[BASEAGEADD:2d6]

### RACENAME:Extamiaar

- **BASEAGE:** 14
- **MAXAGE:** 29
- **AGEDIEROLL:** 1d12

### RACENAME:Krinth

- **CLASS:** Barbarian,Rogue,Sorcerer,Soulknife,Wilder[BASEAGEADD:1d4]|Bard,Fighter,Paladin,Ranger,Psychic Warrior[BASEAGEADD:1d6]|Cleric,Druid,Monk,Psion,Shadowcaster,Wizard[BASEAGEADD:2d6]

### AGESET:3|Middle-Aged


### AGESET:4|Old


### AGESET:5|Venerable


## Classes

### CLASS:Draegloth

- **HD:** 10
- **FACT:** ClassType|Monster
- **FACT:** Abb|Draeg
- **MAXLEVEL:** 10
- **DEFINE:** DraeglothLVL|0
- **BONUS:** VAR|DraeglothLVL|CL
- **DEFINE:** DraeglothHD|0
- **BONUS:** VAR|DraeglothHD|1
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|DraeglothHD/2+2
- **BONUS:** COMBAT|BASEAB|1

### 1

- **ABILITY:** Special Ability|AUTOMATIC|Draegloth ~ Dancing Lights|Draegloth ~ Energy Resistance|Draegloth ~ Feats|Draegloth ~ Natural Attacks|Draegloth ~ Weapon and Armor Proficiency

### 2

- **ABILITY:** Special Ability|AUTOMATIC|Draegloth ~ Darkness|Draegloth ~ Faerie Fire|Draegloth ~ Natural Armor

### 4

- **ABILITY:** Special Ability|AUTOMATIC|Draegloth ~ Desecrate

### 5

- **ABILITY:** Special Ability|AUTOMATIC|Draegloth ~ Poison Immunity

### 7

- **ABILITY:** Special Ability|AUTOMATIC|Draegloth ~ Unholy Blight

### 9

- **ABILITY:** Special Ability|AUTOMATIC|Draegloth ~ Large Size

### 3

- **BONUS:** STAT|DEX|2
- **BONUS:** VAR|DarknessUses|1
- **DONOTADD:** HITDIE|SKILLPOINTS

### 6

- **BONUS:** STAT|STR|2
- **BONUS:** VAR|DraeglothHD|1
- **BONUS:** VAR|DarknessUses|1

### 8

- **BONUS:** STAT|DEX|2
- **BONUS:** VAR|DraeglothHD|1
- **BONUS:** VAR|DarknessUses|1

### 10

- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** FEAT|POOL|1
- **BONUS:** STAT|STR|2
- **BONUS:** VAR|DraeglothHD|1
- **BONUS:** VAR|DraeglothEnergyRes|10

### CLASS:Black Blood Cultist

- **HD:** 12
- **FACT:** ClassType|Prestige
- **FACT:** Abb|BBC
- **MAXLEVEL:** 10
- **DEFINE:** BlackBloodCultistLVL|0
- **BONUS:** VAR|BlackBloodCultistLVL|CL
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE

### CLASS:Justice of Weald and Woe

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|JoWW
- **MAXLEVEL:** 10
- **DEFINE:** JusticeofWealdandWoeLVL|0
- **BONUS:** VAR|JusticeofWealdandWoeLVL|CL
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE

### CLASS:Night Mask Deathbringer

- **HD:** 6
- **FACT:** ClassType|Prestige
- **FACT:** Abb|NMDB
- **MAXLEVEL:** 10
- **DEFINE:** NightMaskDeathbringerLVL|0
- **BONUS:** VAR|NightMaskDeathbringerLVL|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE

### CLASS:Shade Hunter


### CLASS:Thayan Gladiator


### CLASS:Vengeance Knight


### CLASS:Thrall of Eltab

- **HD:** 8
- **FACT:** ClassType|Prestige
- **MAXLEVEL:** 10

## Equipment

### GRAY PORTRAIT

- **WT:** 10

### Hellsteel

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1500
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** MAGIC_COST|15000.Masterwork (Armor).PLUS3A
- **MAXDEX:** 1
- **SPELLFAILURE:** 35
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Fire (Sp)
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=10|Fire Shield
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **BONUS:** VAR|FireResistanceBonusSp|5|TYPE=Base
- **SPROP:** This suit grants the wearer Resistance of Fire 5.

### Flensing Gauntlet

- **PROFICIENCY:** WEAPON|Gauntlet (Spiked)
- **COST:** 5
- **WT:** 0
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** MAGIC_COST|15000.Masterwork (Weapon).PLUS1W.STEEL
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** EQM|WEIGHTADD|-1
- **SPROP:** The target of an hit must make a Fort save DC16 or take 1d6 extra damage, plus 1d4 points of CON damage and 1d4 points CHA damage. Making the save you still take 1/2 the hp damage.

### Camellia of the Black Lady

- **COST:** 7000
- **WT:** 0
- **SPROP:** The wearer can designate 1 target. When they enter within 20 ft of the wearer, they must make a DC 19 Will save (or 21 if Selune is their patron) or be captivated by a dominate person and a remorseless charm effect. They must follow the instructions of the wearer for 9 days or until the effect is otherwise ended. When it ends, the target is then effected by a poison spell dealing 1d10 CON damage instantly and a second 1d10 CON 1 minute later. Each requires a Fortitude save (DC19 or 21). The item has only 1 charge, once spent it is still worth 200 gp.

### Sanguine Nostrom

- **COST:** 5000
- **WT:** 0
- **SPROP:** Combining the powder with an enemy's heart killed no more than 1 minute ago and consuming the heart provides a moment of prescience spell effect with the caster level equal to the victims HD.

## Equipment Modifiers

### Gnashing

- **PLUS:** 1
- **PRETYPE:** 2,Enhancement,Armor
- **SPROP:** If the wearer is grappled the suit deals 1d6 damage to the foe.

### Hideous

- **COST:** 3750
- **PRETYPE:** 2,Enhancement,Armor.Shield
- **BONUS:** SKILL|Intimidate|5|TYPE=Competence
- **BONUS:** SKILL|Diplomacy|-2|TYPE=Competence

### Hideous (Improved)

- **COST:** 15000
- **PRETYPE:** 2,Enhancement,Armor.Shield
- **BONUS:** SKILL|Intimidate|10|TYPE=Competence
- **BONUS:** SKILL|Diplomacy|-2|TYPE=Competence

### Hideous (Greater)

- **COST:** 33750
- **PRETYPE:** 2,Enhancement,Armor.Shield
- **BONUS:** SKILL|Intimidate|15|TYPE=Competence
- **BONUS:** SKILL|Diplomacy|-2|TYPE=Competence

### Ocular

- **PLUS:** 2
- **PRETYPE:** 2,Enhancement,Armor.Shield
- **BONUS:** SKILL|Spot,Search|4|TYPE=Competence
- **SPROP:** The wearer can't be flanked though the this property can be negated by a blindness spell.

### Wary

- **COST:** 5000
- **PRETYPE:** 2,Enhancement,Armor.Shield
- **SPROP:** The wearer gets a bonus of +4 levels with respect to his uncanny dodge ability.

### Doomstrike

- **PLUS:** 1
- **PREMULT:** 2,[PRETYPE:2,Enhancement,Weapon],[PRETYPE:1,Melee]
- **SPROP:** With every weapon sunder, the wielder gets a Cleave attack into the enemy.
- **ABILITY:** FEAT|VIRTUAL|Cleave

### Ravenous

- **PLUS:** 2
- **PREMULT:** 2,[PRETYPE:2,Enhancement,Weapon],[PRETYPE:1,Melee]
- **SPROP:** After wounding a creature, subsequent hits in a round do an extra 2d6 damage each.

### Splitting

- **PLUS:** 3
- **PREMULT:** 2,[PRETYPE:2,Enhancement,Weapon],[PRETYPE:1,Ranged]
- **SPROP:** Any arrow or bolt fired from a splitting weapon magically splits into two identical missiles mid-flight (you must make 2 attack rolls).

## Feats

### Bloodsoaked Intimidate

- **PREABILITY:** 1,CATEGORY=FEAT,Snatch Trophy

Your bloody and vicious approach to combat makes you a fearsome foe.

When you collect a trophy using the Snatch Trophy feat, you can make an Intimidate check as a swift action against an adjacent opponent who witnesses your savage act.

### Chakram Ricochet

- **PRETOTALAB:** 1
- **PRESTAT:** 1,DEX=13
- **PREWEAPONPROF:** 1,Chakram

You can hurl a chakram so that it strikes two enemies instead of one.

If you hit a creature with a thrown chakram, you can cause it to ricochet and strike a secondary target in an adjacent square. You immediately make an attack roll against the target at -2 penalty but deal damage normally. If you are a rogue you can sneak attack against both targets.

### Craven

- **PREMULT:** 2,[PREABILITY:1,CATEGORY=Special Ability,Sneak Attack],[!PREABILITY:1,CATEGORY=Special Ability,Immunity to Fear]

Like most sly rogues, you are a dangerous coward. However, your sneak attacks deal more damage than normal.

You take a -2 penalty on saves vs. fear. However when making a sneak attack, you deal an extra 1 point of damage per character level.

### Dire Flail Smash

- **PREABILITY:** 3,CATEGORY=FEAT,Improved Sunder,Power Attack,Weapon Focus (Dire Flail)
- **PRESTAT:** 1,STR=13

Target struck by both ends of your flail is also dazed for 1 round.

If you hit the same creature with both ends of your dire flail in the same round, it must make a Fortitude save (DC 10 + Character level/2 + STR mod) or be dazed with pain for 1 round.

### Dirty Rat

- **PRESKILL:** 1,Tumble=4

You are quite adept at slipping under a foe's guard while he is distracted.

You gain an additional +1 bonus on attack rolls when flanking an opponent.

### Feral Animal Companion

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Animal Companion
- **PREALIGN:** LE,NE,CE

You can enslave a feral animal and adopt it as your animal companion.

Instead of calling a normal animal, you call an animal that foams at the mouth. Any creature harmed by the creature must succeed on a DC 15 Fortitude save or contract red ache. Additionally, your animal companion gets a +2 bonus to Strength and Constitution. Attempts by others to influence your companion with Handle Animal are made at a -10 penalty.

### Flay Foe

- **PRETOTALAB:** 6
- **PRESTAT:** 1,STR=15
- **PREWEAPONPROF:** 1,TYPE=Slashing

You are skilled at flaying the flesh from your enemy's bones.

If you hit the same enemy more than once in a single round with a slashing weapon, you deal an extra 1d6 points of damage with each hit after the first.

### Improved Fiendish Servant

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Fiendish Servant

You gain the service of a powerful fiendish animal servitor.

Add the following creatures to your eligible fiendish servants: ape, black bear, boar, crocodile, dire badger, dire bat, dire weasel, heavy warhorse, leopard, monitor lizard, constrictor snake, large viper snake, and wolverine. The creature will have the fiendish template.

### Malign Spell Focus

- **PREALIGN:** LE,NE,CE
- **BONUS:** DC|DESCRIPTOR.Evil|1

Your evil spells are more potent then usual due to a deal forged with an evil power.

You gain a +1 DC bonus on all spells with the evil descriptor.

### Mortifying Attack

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Death Attack

Those who witness your brutal death attack are unnerved and jarred by the experience.

All creatures within 30 feet that witness you make a successful death attack must succeed on a Will save (DC equal to the death attack damage dealt) or be shaken for 2d4 rounds. Any creature you consider an ally is immune. In addition, creatures that fail their save are so horrified that they lose their Dex bonus to AC for 1 round. If the target survives the attack, he must make the save as well. This is an extraordinary fear effect.

### Mutilator

- **PRETOTALAB:** 4

After striking down your enemy in battle, you can skillfully mutilate the corpse to prevent others from raising it from the dead.

After delivering the killing blow to a creature (that is reducing it to -10 hp) with a melee weapon, you can decapitate or otherwise hack apart the corpse as a free action. Doing so does not provoke an AoO and ensures that the raise dead spell cannot be used. You can do this only once per round.

### Natural Bully

- **PRESKILL:** 1,Intimidate=6

You easily terrify weaker adversaries.

All enemies within 30 feet of you that have one-half your HD or less are bullied; they take a -2 morale penalty on attack rolls made against you. A bullied enemy that succeeds in hitting and damaging you is no longer subject to the penalty and cannot be bullied by you for 24 hours. Creatures immune to fear effects cannot be bullied and do not take the penalty on attack rolls to hit you.

### Node Defense

- **PREABILITY:** 1,CATEGORY=FEAT,Node Spellcasting

You can use the magical power of a node to defend yourself from harm.

You receive an insight bonus to your AC and saving throws equal to the class of any node that you currently occupy and to which you are attuned, up to a maximum of +4.

### Node Sensitive


You can perceive a node just by passing near it.

You automatically note the presence of any node to which you are attuned within 30 feet, rather than needing a DC20 Intelligence check to do so.

### Node Spellcasting

- **PRESPELLTYPE:** 1,ANY=1
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** STRING|Earth|Evil|Shadow Weave

You ave discovered the secret of the magic of a particular type of node.

You are attuned to one type of node and the magical power it provides. When you choost this feat, choose a type of node (earth, evil, or shadow weave). This feat grants you access to the various node magic feats and node powers, and allows you to make a Spellcraft check instead of an Intelligence check to notice nearby nodes to which you are attuned. You can take this feat multiple times to gain the different type of nodes.

### Node Store

- **PREABILITY:** 1,CATEGORY=FEAT,Node Store
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** SPELLS|ALL[KNOWN=YES]
- **SELECT:** 2

You can store a prepared spell in a node to which you are attuned.

Each time you take this feat, choose 2 spells of any level that you know and can cast. If you prepare spells, you can now prepare those spells in addition to your normal complement as long as your are in a node to which you are attuned. These spells are stored in the node, not in your mind. If you don't prepare spells, you have 2 extra spell slots that are only usable for the specified spells within a node.

### Poison Immunity

- **MULT:** YES
- **CHOOSE:** EQUIPMENT|TYPE=Poison
- **ABILITY:** Special Ability|AUTOMATIC|Poison Save Immune Bonus

After prolonged exposure to a poison or toxin, you have rendered yourself immune to it.

You are immune to one specific poison. You also gain a +1 circumstance bonus on saves against other poisons. Though you can take this feat multiple times the +1 bonus does not stack.

### Pulverize Foe

- **PRETOTALAB:** 6
- **PRESTAT:** 1,STR=15
- **PREWEAPONPROF:** 1,TYPE=Bludgeoning

You enjoy smashing you your opponents into submission.

If you hit the same enemy more than once in a single round with your bludgeoning melee weapon, you deal an extra 1d6 points of damage per hit with each hit after the first.

### Shadowform Familiar

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Familiar
- **PRERACE:** 1,Krinth

You can summon a familiar from the plane of shadow.

If you summon a new familiar after acquiring this feat, it can have the shadow form type. It will be insubstantial and incorporeal, but it can not travel farther from you then 30 ft per caster level. If it is separated from you by more than this amount it dissipates and is considered slain.

### Shadowstrike

- **PRETOTALAB:** 1
- **PRERACE:** 1,Krinth

Due to your ties to the Plane of Shadow, you strike more effectively in areas of dim illumination.

When attacking with a melee weapon in an area of shadowy illumination, you gain a +1 circumstance bonus to hit and deal an extra 1d6 points of damage.

### Skewer Foe

- **PRETOTALAB:** 6
- **PRESTAT:** 1,STR=15
- **PREWEAPONPROF:** 1,TYPE=Piercing

A ruthless combatant, you like to impale your enemies on spears or similar weapons.

If you hit the same enemy more than once in a single round with a piercing melee weapon, you deal an extra 1d6 points of damage on each hit after the first.

### Snatch Trophy


You can quickly and skillfully collect a trophy of your victory over a fallen foe.

After you deal enough damage to drop a creature to negative hit points, you can slice or pry off a trophy as a free action. You must be adjacent to the dead or dying creature. The trophy can be a small body part such as an ear or finger. This requires a light slashing or piercing weapon and deals 1d6 damage to the target creature. Alternatively it can be a small item weighing 2 lbs or less.

### Touch of Benevolence

- **PREALIGN:** LE,NE,CE

Despite your evil alignment, you are prone to moments of benevolence and mercy.

Although you are evil and spells such as detect alignment will reveal your true alignment, you have a 50%% chance of ignoring any effect that specifically targets or damages evil creatures. To keep this feat, you must demonstrate periodic acts of kindness and mercy.

### Doomspeak

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Bardic Music
- **PRESKILL:** 2,Intimidate=8,TYPE.Perform=8

You can demoralize an enemy with horrible condemnations and grim portents of impending doom.

You can use a bardic music use to utter a curse on any enemy within 120 feet. The target must be able to hear you and comprehend your remarks. If the target fails a Will save (DC 10 + your character level + Cha mod) is cursed with a -10 penalty on attack rolls, saves, ability checks, and skill checks for 1 round. This is a supernatural, necromantic effect.

### Profane Outburst

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Rebuke Undead
- **PREALIGN:** LE,NE,CE

With a horrendous release of divine energy you teel your undead allies and minions against harm.

As a standard action, you can spend a rebuke undead attempt to bathe all undead within 60 ft in divine energy granting them a +1 profane bonus to AC for 1 minute.

### Via Negativa

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Rebuke Undead

You can channel a greater amount of negative energy into your inflict spells.

As a free action, you can spend a rebuke attempts to deal harm with an inflict spell. You must spend the rebuke attempt before making the attack roll. If the attack roll succeeds, the victim takes 1 extra point per character level of damage. If the attack roll fails, the rebuke attempt is spent and wasted.

### Initiate of Ghaunadaur

- **PRECLASS:** 1,Cleric=3
- **PREDEITY:** 1,Ghaunadaur
- **ABILITY:** Special Ability|AUTOMATIC|Basic Turning|Rebuke Ooze
- **SPELLKNOWN:** CLASS|Cleric=1|Corrosive Grasp
- **SPELLKNOWN:** CLASS|Cleric=2|Blindsight
- **SPELLKNOWN:** CLASS|Cleric=3|Amorphous Form
- **SPELLKNOWN:** CLASS|Cleric=5|Slime Hurl
- **SPELLKNOWN:** CLASS|Cleric=7|Mantle of the Slime Lord

You can command or rebuke oozes as an evil cleric rebukes undead. You can use this 3 + your Cha mod, add Ghaunadaurite spells to your list.

You gain the ability to rebuke/command oozes, 3 + Cha mod times per day. Add 5 spells to your list.

### Initiate of Gruumsh

- **PRECLASS:** 1,Blackguard=3,Cleric=3,Ranger%=8
- **PREDEITY:** 1,Gruumsh
- **PRERACE:** 1,Orc%,Half-Orc
- **SPELLKNOWN:** CLASS|Cleric=2|Battle Line
- **SPELLKNOWN:** CLASS|Cleric=3|Bloodspear
- **SPELLKNOWN:** CLASS|Cleric=5|Pocket Cave
- **SPELLKNOWN:** CLASS|Cleric=6|Eyebite
- **SPELLKNOWN:** CLASS|Cleric=7|Waves of Exhaustion
- **SPELLKNOWN:** CLASS|Blackguard=2|Battle Line
- **SPELLKNOWN:** CLASS|Blackguard=3|Bloodspear
- **SPELLKNOWN:** CLASS|Ranger=2|Battle Line
- **SPELLKNOWN:** CLASS|Ranger=3|Bloodspear

Hide and Move Silently are class skills; add Arvoreenite spells to your spell list

Once per day you can cast any cure or inflict spell you have prepared as a swift action. Add 2 or 5 spells to your spell list.

### Initiate of Kossuth

- **PRECLASS:** 1,Cleric=3
- **PREDEITY:** 1,Kossuth
- **SPELLKNOWN:** CLASS|Cleric=2|Scorch
- **SPELLKNOWN:** CLASS|Cleric=4|Fire Stride
- **SPELLKNOWN:** CLASS|Cleric=5|Shroud of Flame
- **SPELLKNOWN:** CLASS|Cleric=8|Incendiary Cloud

All fire elementals that you summon using the summon monster spells have +2 hit points per die. Add Kossuthite spells to your list.

You add +2 hit points per HD to any fire elemental you summon with a summon monster spell. Add 4 spells to your spell list.

### Initiate of Loviatar

- **PRECLASS:** 1,Cleric=5
- **PREDEITY:** 1,Loviatar
- **SPELLKNOWN:** CLASS|Cleric=2|Rebuke
- **SPELLKNOWN:** CLASS|Cleric=3|Mystic Lash
- **SPELLKNOWN:** CLASS|Cleric=5|Fleshshiver

In each combat, your initial pain provides you a combat boost; add Loviatarite spells to your spell list

The first time you take damage in a combat, you gain a +1 morale bonus on attack rolls and saves against fear for %1 minutes. Add 3 spells to your spell list.|classlevel("Cleric")

### Initiate of Shar

- **PRECLASS:** 1,Blackguard=1,Cleric=3
- **PREDEITY:** 1,Shar
- **CSKILL:** Bluff|Hide
- **SPELLKNOWN:** CLASS|Cleric=1|Disguise Self
- **SPELLKNOWN:** CLASS|Cleric=3|Crushing Despair
- **SPELLKNOWN:** CLASS|Cleric=4|Armor of Darkness
- **SPELLKNOWN:** CLASS|Cleric=5|Darkbolt
- **SPELLKNOWN:** CLASS|Blackguard=1|Disguise Self
- **SPELLKNOWN:** CLASS|Blackguard=3|Crushing Despair
- **SPELLKNOWN:** CLASS|Blackguard=4|Armor of Darkness

Bluff and Hide are class skills, add Sharite spells to your list.

You add Bluff and Hide to your Class Skill List. You add 3 or 4 spells to your list.

### Initiate of Varae

- **PRECLASS:** 1,Cleric=3
- **PREDEITY:** 1,Varae
- **PRERACE:** 1,Extaminaar
- **SPELLKNOWN:** CLASS|Cleric=2|Blinding Spittle
- **SPELLKNOWN:** CLASS|Cleric=4|Serpent Arrow
- **SPELLKNOWN:** CLASS|Cleric=6|Veil
- **SPELLKNOWN:** CLASS|Cleric=8|Animal Shapes

You add can turn your skin into emerald scales once per day, add Varaeite spells to your list.

Once per day as a standard action, you can transform your skin into emerald scales. The scales absorb magic missile damage as a shield spell and enable you to pass through walls of force. They last for %1 minutes. This is a supernatural ability. You add 4 spells to your list.|classlevel("Cleric")

### Corrupt Spell

- **PREALIGN:** LE,NE,CE
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** SPELLS|ALL[KNOWN=YES]

You can transform one of your spells into a thing of evil due to a deal you make with an evil power.

This feat adds the evil descriptor to one damaging spell that you cast. You must choose the spell when you select the feat. Half the damage done by the spell is unholy damage rather then elemental.

### Entangling Spell

- **ADDSPELLLEVEL:** 2

Your spell releases residual eldritch power that entangles your enemies.

You can apply this metamagic effect to any instantaneous damaging spell. After casting the spell, lingering tentacles of raw energy persist; creatures damaged by the spell are entangled for 1 round. The spell could be dispelled during this time. It uses a slot 2 higher than normal.

### Lingering Spell

- **ADDSPELLLEVEL:** 1

Residual eldritch energy from your spell continues to harm enemies after the spell's main effect has expired.

You can apply this metamagic effect to any instantaneous damaging spell. After casting the spell, lingering tentacles of raw energy persist and damage all creatures effected by the spell for 1d6 damage on your turn in the second round. The spell could be dispelled during this time. It uses a slot 1 higher than normal.

### Metanode Spell

- **PREABILITY:** 1,CATEGORY=FEAT,Node Spellcasting
- **PRESPELLTYPE:** 1,ANY=1

You cast metamagic spells to greater effect in nodes to which you are attuned than elsewhere.

When casting a spell improved by a metamagic feat, you can deduct the class of the node layer in which you currently stand from the increased spell level. The class of the layer does not equal the class of the node unless you are standing in the innermost portion of it. If you use this feat to reduce the cost of preparing a metamagic spell and then leave the node, the spell you prepared is unavailable until you return to a node layer of at least the same class as the one in which the spell was prepared.

### Reaping Spell

- **PREALIGN:** LE,NE,CE
- **ADDSPELLLEVEL:** 3

The dark energy of your spell devours the soul of any creature killed it.

A raise dead, reincarnate, or resurrection spell cannot return to life a creature killed by a reaping spell, and a true resurrection 50%% chance of success. A reaping spell that fails to kill a target has no extra effect. It uses a spell slot 3 levels higher than the spells actual level.

### Demonsworn Knight

- **PRETOTALAB:** 4
- **PREABILITY:** 1,CATEGORY=FEAT,Thrall to Demon
- **PREMULT:** 2,[!PREABILITY:1,CATEGORY=FEAT,Hellbound Knight],[!PREABILITY:1,CATEGORY=FEAT,Tormented Knight]

A scornful champion of the demon princes, you detest and oppose devils and other creatures that refuse to heed the call of chaos.

Any weapon you wield is treated as chaotic- and evil- for purposes of overcoming damage reduction. In addition, against lawful outsiders, you deal an extra 1d6 points of damage with any successful weapon attack. This feat can only be taken once. In taking it your eyes turn dead black and your teeth become as sharp as fangs. A creature that takes this can not also take Hellbound Knight or Tormented Knight.

### Disciple of Darkness

- **PREALIGN:** LE
- **PREMULT:** 2,[!PREABILITY:1,CATEGORY=FEAT,Scion of Sorrow],[!PREABILITY:1,CATEGORY=FEAT,Thrall to Demon]

You formally supplicate yourself to an archdevil. In return for this obedience, you gain a small measure of the archdevil's power.

Once per day, while performing an evil act, you can call upon your diabolic patron to add a +1 luck bonus to any one attack roll, saving throw, ability check, skill check, or level check. This feat can only be taken once. A character that takes it can not also take Scion of Sorrow or Thrall of the Demon.

### Evil Brand


You are physically marked forever as a servant of an evil power greater than yourself or as a villain that seeks only death, destruction, and misery for others.

Evil creatures automatically recognize the symbol now emblazoned upon you as a sign of your utter depravity or discipleship to a powerful patron, although the specific identity of the patron is not revealed. You gain a +2 circumstance bonus on Diplomacy and Intimidate checks made against evil creatures.

### Evil Embraced

- **PREABILITY:** 1,CATEGORY=FEAT,Evil Brand

You embrace the power of your fiendish patron and call upon that power in moments of great need.

Once per day, as an immediate action you can call upon your fiendish patron to steel you against harm. You gain damage reduction 10/good for 1 round (until the start of your next turn).

### Hellbound Knight

- **PRETOTALAB:** 4
- **PREABILITY:** 1,CATEGORY=FEAT,Disciple of Darkness
- **PREMULT:** 2,[!PREABILITY:1,CATEGORY=FEAT,Demonsworn Knight],[!PREABILITY:1,CATEGORY=FEAT,Tormented Knight]

As a devoted disciple of the Nine Hells, you have sworn to strike down creatures that oppose law and threaten tyranny.

Any weapon you wield is treated as lawful- and evil- aligned for the purpose of overcoming damage reduction. In addition, against chaotic outsiders, you gain a +1 profane bonus on attack rolls. This feat can only be taken once. A character that takes this cannot also take Demonsworn Knight or Tormented Knight. In addition, as soon as you take this feat, you eyes turn red.

### Scion of Sorrow

- **PREALIGN:** NE
- **PREMULT:** 2,[!PREABILITY:1,CATEGORY=FEAT,Disciple of Darkness],[!PREABILITY:1,CATEGORY=FEAT,Thrall to Demon]

You formally supplicate yourself to a powerful yugoloth lord. In return for your unflinching obedience, you gain a small measure of the wretched fiend's power.

Once per day, while performing an evil act, you can call upon your fiendish patron to add a +1 luck bonus to any one attack roll, saving throw, ability check, skill check, or level check. This feat can only be taken once. A character who takes this feat cannot also take Disciple of Darkness or Thrall to Demon.

### Thrall to Demon

- **PREALIGN:** CE
- **PREMULT:** 2,[!PREABILITY:1,CATEGORY=FEAT,Disciple of Darkness],[!PREABILITY:1,CATEGORY=FEAT,Scion of Sorrow]

You formally supplicate yourself to a demon prince. In return for this obedience, you gain a small measure of the demon prince's power.

Once per day, while performing an evil act, you can call upon your demonic patron to add a +1 luck bonus to any one attack roll, saving throw, ability check, skill check, or level check. This feat can only be taken once. A character who takes this feat cannot also take Scion of Suffering or Thrall to Demon.

### Tormented Knight

- **PRETOTALAB:** 4
- **PREABILITY:** 1,CATEGORY=FEAT,Scion of Sorrow
- **PREMULT:** 2,[!PREABILITY:1,CATEGORY=FEAT,Demonsworn Knight],[!PREABILITY:1,CATEGORY=FEAT,Hellbound Knight]

You are inexorably bound to the loathsome yugoloths that lurk in the Barrens of Doom and Despair, and you strive to bring misery and pain to all that oppose them.

Any weapon you wield is treated as evil-aligned for the purpose of overcoming damage reduction. Any chaotic or lawful outsider you successfully damage with a melee or ranged weapon must succeed on a Fortitude save (DC 10 + damage dealt) or take 1d4 points of Charisma damage. This feat can only be taken once. A character who takes this feat cannot also take the Demonsworn Knight or Hellbound Knight feat. In addition, as soon as your take this feat, your flesh turns pale and becomes unnaturally cold to the touch.

## Races

### Draegloth

- **FAVCLASS:** Cleric
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Aquan,Common,Draconic,Drow Sign Language,Gnome,Goblin,Kuo-toan
- **BONUS:** STAT|CON|2
- **AUTO:** LANG|Abyssal|Elven|Undercommon
- **ABILITY:** Internal|AUTOMATIC|Draegloth Racial Trait Default
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Draegloth
- **LEVELADJUSTMENT:** 1
- **CR:** 1

### Extaminaar

- **FAVCLASS:** Rogue
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Abyssal,Chondathan,Draconic
- **AUTO:** LANG|Common|Turmic|Yuan-ti
- **ABILITY:** Internal|AUTOMATIC|Extaminaar Racial Trait Default
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Extaminaar
- **CR:** 1

### Krinth

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Abyssal,Chondathan,Damaran,Undercommon
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-2
- **AUTO:** LANG|Common|Netherese
- **ABILITY:** Internal|AUTOMATIC|Krinth Racial Trait Default
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Krinth
- **CR:** 1

## Spells

### Air Breathing

- **CLASSES:** Cleric,Druid,Sorcerer,Wizard=3
- **SCHOOL:** Transmutation
- **COMPS:** S,M,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Creature(s) touched
- **DURATION:** (CASTERLEVEL*2) hours [D]
- **SAVEINFO:** Will negates (h)
- **SPELLRES:** Yes (h)

Subject(s) can breathe air freely (and water if they could before). You can divide the duration between targets.

### Anathema

- **CLASSES:** Cleric,Druid=9
- **SCHOOL:** Enchantment
- **SUBSCHOOL:** Compulsion
- **COMPS:** V,S,F,DF
- **CASTTIME:** 1 round
- **RANGE:** Unlimited
- **TARGETAREA:** One creature of the same faith as the caster
- **DURATION:** Permanent [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Permanently break the divine link between your god and lower ranked members (Cleric, druid, ranger, etc) of your faith. They can no longer use divine spells.

### Arrowsplit

- **CLASSES:** Assassin,Justice of Weald and Woe,Ranger=3
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One masterwork arrow or bolt
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

Transform a masterwork arrow or bolt mid-flight into 1d4+1 masterwork missiles.

### Battle Line

- **SCHOOL:** Abjuration
- **COMPS:** V,S,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Up to (min(CASTERLEVEL*2),10) 5-ft squares [S]
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

Draw an invisible, unholy line in the sand that causes anyone crossing it to make a Will save or become shaken.

### Bedevil

- **CLASSES:** Blackguard,Sorcerer,Wizard=3
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Summoning
- **DESCRIPTOR:** Evil
- **COMPS:** V,S,M
- **CASTTIME:** 1 round
- **RANGE:** Unlimited
- **TARGETAREA:** One creature
- **DURATION:** (CASTERLEVEL) days [D]
- **SAVEINFO:** No
- **SPELLRES:** Yes

Summon a mischievous spirit to torment your enemy. It appears next to you then finds the target wherever it is. The target takes a -1 penalty on all ability checks, skill checks, and Will saves, and has an additional 5%% arcane spell failure chance for the duration. The spirit can be detected by a Detect Evil spell, can be temporarily blocked by a Protection from Evil, and can only be banished by a Dispel Evil.

### Bloodfreeze Arrow

- **CLASSES:** Assassin,Justice of Weald and Woe,Ranger=4
- **SCHOOL:** Transmutation
- **COMPS:** V,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One masterwork arrow or bolt
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude partial
- **SPELLRES:** Yes

Masterwork arrow or bolt deals extra 2d6 cold damage and unless the target makes the Fortitude save they are paralyzed. They remain paralyzed until they make a successful Fortitude save on their turn.

### Bloodspear

- **SCHOOL:** Transmutation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Spear touched
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** None
- **SPELLRES:** No

You channel Gruumsh's power into a spear, its tip drips blood and has the wounding ability as long as you remain hold on it and for 1 throw.

### Bonefiddle

- **CLASSES:** Bard=2
- **SCHOOL:** Necromancy
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Once creature with a skeleton or exoskeleton
- **DURATION:** Concentration, up to (CASTERLEVEL) rounds
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes
- **COST:** 30

Target takes 1d6 sonic damage/round and -20 penalty on Move Silently checks, this disrupts spell casting.

### Brilliant Energy Arrow

- **CLASSES:** Assassin,Justice of Weald and Woe,Ranger=2
- **SCHOOL:** Transmutation
- **COMPS:** V,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One masterwork arrow or bolt
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

Masterwork arrow or bolt radiates light as a torch and ignores armor, but will not damage constructs, undead, or objects.

### Control Darkness and Shadow

- **CLASSES:** Bard=2|Sorcerer,Wizard=3
- **SCHOOL:** Transmutation
- **DESCRIPTOR:** Darkness|Shadow
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Shadows in (CASTERLEVEL) 5-ft cubes
- **DURATION:** Concentration + (CASTERLEVEL) rounds
- **SAVEINFO:** None
- **SPELLRES:** No

Manipulate existing areas of darkness and shadow to Deepen them (adding +4 to Hide checks and increasing concealment), Lighten them (make it impossible to hide in them and remove concealment), or Move them (shape as you wish to duplicate a silent image effect).

### Darkflame Arrow

- **CLASSES:** Assassin,Justice of Weald and Woe,Ranger=3
- **SCHOOL:** Evocation
- **COMPS:** V,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One masterwork arrow or bolt
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

Masterwork arrow or bolt deals normal damage plus 2d6 damage each round for 3 rounds.

### Doublestrike Arrow

- **CLASSES:** Justice of Weald and Woe,Ranger=4
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One arrow or bolt
- **DURATION:** 1 round
- **SAVEINFO:** None
- **SPELLRES:** No

One arrow or bolt strikes two targets within 30 feet of each other. You must make separate attack rolls against each.

### Enrange Animals

- **CLASSES:** Druid,Ranger=1
- **SCHOOL:** Enchantment
- **SUBSCHOOL:** Compulsion
- **DESCRIPTOR:** Mind-Affecting
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Animals within 30-ft. of each other
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

Render 2d4 + (CASTERLEVEL) HD of normal animals hostile and vicious. Dire or trained animals are allowed the saves, normal animals are not. Affected creatures attack the nearest creature.

### Locate Node

- **CLASSES:** Druid,Sorcerer,Wizard=2|Cleric=3
- **SCHOOL:** Divination
- **COMPS:** V,S,F/DF
- **CASTTIME:** 1 standard action
- **RANGE:** (CASTERLEVEL) miles
- **TARGETAREA:** Circle, centered on you, with a radius of (CASTERLEVEL) miles
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** None
- **SPELLRES:** No

Finds closest node in a (CASTERLEVEL) mile radius.

### Love's Lament

- **CLASSES:** Bard=3
- **SCHOOL:** Enchantment
- **SUBSCHOOL:** Compulsion
- **DESCRIPTOR:** Mind-Affecting
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** 60 ft.
- **TARGETAREA:** Cone-shaped burst
- **DURATION:** Instantaneous
- **SAVEINFO:** Will partial
- **SPELLRES:** Yes

Creatures in 60-ft. cone take a -4 penalty on Listen checks for 1 round. Those that fail the save take 1d6 Wisdom damage and are nauseated for 1d4 rounds.

### Mantle of the Slime Lord

- **SCHOOL:** Abjuration
- **COMPS:** V,S,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** Nimbus of divine energy
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

You gain a glossy nimbus of energy. While active nonintelligent oozes will not attack you unless you attack them. Additionally, you are immune to poison, sleep, paralysis, polymorph, and stun effects. Lastly, when a critical hit or sneak attack is scored on you there is a 75%% chance that it will result only in standard damage.

### Mark of the Unfaithful

- **CLASSES:** Cleric,Druid=7
- **SCHOOL:** Evocation
- **COMPS:** V,S,F
- **CASTTIME:** 1 round
- **RANGE:** Unlimited
- **TARGETAREA:** One creature
- **DURATION:** Permanent
- **SAVEINFO:** None
- **SPELLRES:** Yes

Mark someone as an enemy of your faith, such that any other member of your faith receives a +6 bonus on Sense Motive checks against the marked creature. Clerics and paladins automatically detect the mark just by looking at the victim.

### Necrotic Skull Bomb

- **CLASSES:** Cleric,Sorcerer,Wizard=5
- **SCHOOL:** Necromancy
- **COMPS:** V,S,M
- **CASTTIME:** 1 swift action
- **RANGE:** Close
- **TARGETAREA:** 20-ft.-radius spread
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes

Exploding skull releases negative energy; lving targets each gain 1d4 negative levels which last (min(CASTERLEVEL,15)) hours. Undead in the area gain 1d4x5 temporary hp for 1 hour.

### Node Door

- **CLASSES:** Druid,Sorcerer,Wizard=3
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Teleportation
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Varies
- **TARGETAREA:** You and touched objects or touched willing creatures
- **DURATION:** Instantaneous
- **SAVEINFO:** None and Will negates (o)
- **SPELLRES:** No and Yes (o)

Allows teleportation between any known nodes. If the node you wish to go to is fully occupied or destroyed, you "bounce" to the next nearest taking 2d6 damage. You can bring (CASTERLEVEL/3) willing creature of size Medium or smaller. Large creatures count as 2 medium creatures. The saves only apply to objects held or in use by an unwilling person.

### Node Genesis

- **CLASSES:** Sorcerer,Wizard=9
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V,XP
- **CASTTIME:** 1 tenday (8 hrs/day)
- **RANGE:** Touch
- **TARGETAREA:** One Class 1 node with a 10-ft. radius
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No
- **XPCOST:** 5000

Creates a Class 1 node.

### Node Lock

- **CLASSES:** Sorcerer,Wizard=2
- **SCHOOL:** Abjuration
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** One node
- **DURATION:** Permanent
- **SAVEINFO:** None
- **SPELLRES:** No

Deters others from using a node's powers by adding a +15 to each Spellcraft DC associated to use the node's powers. The effect can be broken with a Dispel Magic.

### Pocket Cave

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V,S,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Extradimensional cave, up to (CASTERLEVEL*2) 10-ft cubes [S]
- **DURATION:** (CASTERLEVEL) hours [D]
- **SAVEINFO:** None
- **SPELLRES:** No

You conjure up an extradimensional plane with one entrance (4 ft wide, 8-ft tall) on the plane that you cast it. Only those you allow to can enter. You can open and close the cave at will. It provides clean water and edible fungus. If you are in the cave when the spell ends you are deposited back in the home plane at the entrance.

### Ravage

- **CLASSES:** Cleric=7
- **SCHOOL:** Necromancy
- **DESCRIPTOR:** Evil
- **COMPS:** V,S,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** 10-ft.-radius cylinder, 40 ft. high
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes

A pillar of black, unholy power deals (min((CASTERLEVEL/2),10))d6 vile damage that can only be healed with a consecrate or hallow spell.

### Remorseless Charm

- **CLASSES:** Bard=5|Cleric,Sorcerer,Wizard=6
- **SCHOOL:** Enchantment
- **SUBSCHOOL:** Compulsion
- **DESCRIPTOR:** Evil|Mind-Affecting
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** One creature
- **DURATION:** Permanent until broken [D]
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes
- **COST:** 1000

Suppress target's alignment, removing all alignment-related inhibitions until broken by a break enchantment or similar spell or dismissed by the caster.

### Scourge of Force

- **CLASSES:** Sorcerer,Wizard=2
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** (min(4,(1+CASTERLEVEL/3))) tendrils of of force against one or more targets, no two of which are more than 30 ft. apart
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

(min(4,(1+CASTERLEVEL/3))) tendrils of force lash foes with melee touch attacks at your highest BAB for 1d8+(min(5,CASTERLEVEL/2)) damage each.

### Serpent Arrow

- **CLASSES:** Justice of Weald and Woe=3|Sorcerer,Wizard=4
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Up to 8 projectiles, all of which must be within 40 ft of each other at the time of casting
- **DURATION:** (CASTERLEVEL*10) minutes
- **SAVEINFO:** None
- **SPELLRES:** No

Transforms missiles into Tiny vipers that automatically bite any creature they hit for 1 point of damage plus DC 11 d6 CON pri/sec poison. If you miss with your attack, the snake slithers to the next closest target.

### Shadow Arrow

- **CLASSES:** Assassin,Justice of Weald and Woe,Ranger=4
- **SCHOOL:** Necromancy
- **COMPS:** V,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One masterwork arrow or bolt
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

Masterwork arrow or bolt deals 1d6 points of Strength damage instead of normal damage.

### Shadow Trap

- **CLASSES:** Cleric,Sorcerer,Wizard=7
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Summoning
- **DESCRIPTOR:** Shadow
- **COMPS:** V,S,M
- **CASTTIME:** 10 minutes
- **RANGE:** Touch
- **TARGETAREA:** One object
- **DURATION:** (CASTERLEVEL) hours [D]
- **SAVEINFO:** Reflex half
- **SPELLRES:** Yes

Bind a greater shadow to an object as its guardian.

### Slashing Darkness

- **CLASSES:** Cleric=3
- **SCHOOL:** Evocation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** Ray
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

Ray deals (min(5,CASTERLEVEL/2))d8 damage or heals undead the same amount.

### Slime Hurl

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V,S,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Three globes of green slime
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No

You conjure and hurl 3 globs of slime with RTA at your best BAB. Any creature is coated in green slime. It does not dissipate when the spell ends.

### Spellslayer Arrow

- **CLASSES:** Assassin,Justice of Weald and Woe,Ranger=2
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One masterwork arrow or bolt
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

Masterwork arrow or bolt deals extra 1d4 pts of damage/spell level effecting the creature.

### Symphonic Nightmare

- **CLASSES:** Bard=6
- **SCHOOL:** Enchantment
- **SUBSCHOOL:** Compulsion
- **DESCRIPTOR:** Mind-Affecting
- **COMPS:** V,S,F
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Living creature touched
- **DURATION:** (CASTERLEVEL) days [D]
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

Haunting music disrupts target's sleep for (CASTERLEVEL) days, causing them to incur a -2 penalty on Wisdom checks and prevents them from regaining health or spells from rest. This can be lifted with a remove curse from a higher level caster or a better spell.

### Undersong

- **CLASSES:** Bard=1
- **SCHOOL:** Transmutation
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** None
- **SPELLRES:** No

Make Perform checks in place of Concentration checks allowing you to perform other tasks while maintaining Concentration.

### Unholy Beast

- **CLASSES:** Druid=4
- **SCHOOL:** Transmutation
- **DESCRIPTOR:** Evil
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** One animal of up to (CASTERLEVEL) HD
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes

Target animal transforms into an unholy minion under your control gaining +2 to Strength, Dexterity, Constitution, and natural armor. Further, its natural attacks improve as though it is 1 size larger.

### Whip of Thorns

- **CLASSES:** Druid=2
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** 15-ft-long whip covered in sharp thorns
- **DURATION:** (CASTERLEVEL) round or until discharged
- **SAVEINFO:** None
- **SPELLRES:** No

Create a thorny whip that can damage (1d8+1 lethal) or entangle opponents, Once entangled, they take 1d4 points of damage per round they try to escape.

### Woodwisp Arrow

- **CLASSES:** Assassin,Druid,Justice of Weald and Woe,Ranger=1
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 swift action
- **RANGE:** Touch
- **TARGETAREA:** One masterwork arrow or bolt
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Enables a masterwork arrow or bow to pass through wood, removing bonus AC from shields, converting cover to concealment.


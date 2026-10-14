# Monster Manual

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Special Abilities

### Energy Drain


This attack saps a living opponent's vital energy and happens automatically when a melee or ranged attack hits. Each successful energy drain bestows one or more negative levels (the creature's description specifies how many). If an attack that includes an energy drain scores a critical hit, it drains twice the given amount. Unless otherwise specified in the creature's description, a draining creature gains 5 temporary hit points (10 on a critical hit) for each negative level it bestows on an opponent. These temporary hit points last for a maximum of 1 hour. An affected opponent takes a -1 penalty on all skill checks and ability checks, attack rolls, and saving throws, and loses one effective level or Hit Die (whenever level is used in a die roll or calculation) for each negative level. A spellcaster loses one spell slot of the highest level of spells she can cast and (if applicable) one prepared spell of that level; this loss persists until the negative level is removed. Negative levels remain until 24 hours have passed or until they are removed with a spell, such as restoration. If a negative level is not removed before 24 hours have passed, the affected creature must attempt a Fortitude save (DC 10 + 1/2 draining creature's racial HD + draining creature's Cha modifier; the exact DC is given in the creature's descriptive text). On a success, the negative level goes away with no harm to the creature. On a failure, the negative level goes away, but the creature's level is also reduced by one. A separate saving throw is required for each negative level.

### Improved Grab


If a creature with this special attack hits with a melee weapon (usually a claw or bite attack), it deals normal damage and attempts to start a grapple as a free action without provoking an attack of opportunity (see Grapple, page 155 of the Player's Handbook). No initial touch attack is required. Unless otherwise noted, improved grab works only against opponents at least one size category smaller than the creature. The creature has the option to conduct the grapple normally, or simply use the part of its body it used in the improved grab to hold the opponent. If it chooses to do the latter, it takes a -20 penalty on grapple checks, but is not considered grappled itself; the creature does not lose its Dexterity bonus to AC, still threatens an area, and can use its remaining attacks against other opponents. A successful hold does not deal any extra damage unless the creature also has the constrict special attack. If the creature does not constrict, each successful grapple check it makes during successive rounds automatically deals the damage indicated for the attack that established the hold. Otherwise, it deals constriction damage as well (the amount is given in the creature's descriptive text). When a creature gets a hold after an improved grab attack, it pulls the opponent into its space. This act does not provoke attacks of opportunity. It can even move (possibly carrying away the opponent), provided it can drag the opponent's weight.

### Poison


Poison attacks deal initial damage, such as ability damage (see page 305) or some other effect, to the opponent on a failed Fortitude save. Unless otherwise noted, another saving throw is required 1 minute later (regardless of the first save's result) to avoid secondary damage. A creature's descriptive text provides the details. A creature with a poison attack is immune to its own poison and the poison of others of its kind. The Fortitude save DC against a poison attack is equal to 10 + 1/2 poisoning creature's racial HD + poisoning creature's Con modifier (the exact DC is given in the creature's descriptive text). A successful save avoids (negates) the damage.

### Pounce


When a creature with this special attack makes a charge, it can follow with a full attack-including rake attacks if the creature also has the rake ability.

### Rake


A creature with this special attack gains extra natural attacks when it grapples its foe. Normally, a monster can attack with only one of its natural weapons while grappling, but a monster with the rake ability usually gains two additional claw attacks that it can use only against a grappled foe. Rake attacks are not subject to the usual -4 penalty for attacking with a natural weapon in a grapple. A monster with the rake ability must begin its turn grappling to use its rake-it can't begin a grapple and rake in the same turn.

### Rend


### Immunity To Confusion


### Immunity To Poison


### Immunity To Sonic


### Deep

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Dwarf ~ Deep],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Deep Dwarf
- **ABILITY:** Special Ability|AUTOMATIC|Deep Dwarf ~ Light Sensitivity
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Darkvision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfRacialVision
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Weapon Familiarity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfWeaponFamiliarity
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stonecunning|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfStonecunning
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stability|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfStability
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Poison Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfPoisonSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Spell Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfSpellSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Attack Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfAttackBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Dodge Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfDodgeBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Appraise Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfAppraiseBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Craft Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfCraftBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Dwarf)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Dwarf)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|CON|2|TYPE=Racial
- **BONUS:** STAT|CHA|-2|TYPE=Racial
- **BONUS:** VAR|DarkvisionRange|90|TYPE=Base
- **BONUS:** VAR|DwarfPoisonSaveBonus,DwarfSpellSaveBonus|1
- **COST:** 0

### Duergar

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Dwarf ~ Duergar],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=max(3,(TL*2))|Enlarge Person,11+INT|Invisibility,12+INT
- **TEMPLATE:** Duergar Dwarf
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **ABILITY:** Special Ability|AUTOMATIC|Duergar ~ Light Sensitivity|Duergar ~ Racial Immunity|Duergar ~ Spell-Like Abilities
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Darkvision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfRacialVision
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Weapon Familiarity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfWeaponFamiliarity
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stonecunning|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfStonecunning
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stability|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfStability
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Poison Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfPoisonSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Spell Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfSpellSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Attack Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfAttackBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Dodge Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfDodgeBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Appraise Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfAppraiseBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Craft Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfCraftBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Duergar)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Duergar)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** SKILL|Move Silently|4|TYPE=Racial
- **BONUS:** SKILL|Listen,Spot|1|TYPE=Racial
- **BONUS:** STAT|CON|2|TYPE=Racial
- **BONUS:** STAT|CHA|-4|TYPE=Racial
- **BONUS:** VAR|DarkvisionRange|120|TYPE=Base
- **COST:** 0

### Mountain

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Dwarf ~ Mountain],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Mountain Dwarf
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Darkvision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfRacialVision
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Weapon Familiarity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfWeaponFamiliarity
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stonecunning|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfStonecunning
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stability|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfStability
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Poison Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfPoisonSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Spell Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfSpellSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Attack Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfAttackBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Dodge Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfDodgeBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Appraise Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfAppraiseBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Craft Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DwarfCraftBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Dwarf)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Dwarf)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|CON|2|TYPE=Racial
- **BONUS:** STAT|CHA|-2|TYPE=Racial
- **COST:** 0

### Aquatic

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Elf ~ Aquatic],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Aquatic Elf
- **ABILITY:** Special Ability|AUTOMATIC|Aquatic Elf Traits
- **ABILITY:** Elf Race Trait|AUTOMATIC|Aquatic Elf ~ Gills|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfGills
- **ABILITY:** Elf Race Trait|AUTOMATIC|Aquatic Elf ~ Superior Low-light Vision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfSuperiorLowLightVision
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Racial Immunity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfRacialImmunity
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Low-Light Vision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfLowLightVision
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Weapon Proficiency|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfWeaponProficiency
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Skill Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfSkillBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|CON|-2|TYPE=Racial
- **BONUS:** STAT|DEX|2|TYPE=Racial
- **COST:** 0

### Drow

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Elf ~ Drow],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Drow Elf
- **TEMPLATE:** CHOOSE:Drow Male|Drow Female
- **ABILITY:** Special Ability|AUTOMATIC|Drow Traits
- **ABILITY:** Elf Race Trait|AUTOMATIC|Drow ~ Darkvision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowDarkvision
- **ABILITY:** Elf Race Trait|AUTOMATIC|Drow ~ Light Blindness|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowLightBlindness
- **ABILITY:** Elf Race Trait|AUTOMATIC|Drow ~ Poison|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowPoison
- **ABILITY:** Elf Race Trait|AUTOMATIC|Drow ~ Spell-Like Abilities|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowSpellLikeAbilities
- **ABILITY:** Elf Race Trait|AUTOMATIC|Drow ~ Spell Resistance|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowSpellResistance
- **ABILITY:** Elf Race Trait|AUTOMATIC|Drow ~ Weapon Proficiency|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowWeaponProficiency
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Racial Immunity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowRacialImmunity
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Skill Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.DrowSkillBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Drow)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Drow)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|CON|-2|TYPE=Racial
- **BONUS:** STAT|DEX,INT,CHA|2|TYPE=Racial
- **COST:** 0

### Gray

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Elf ~ Gray],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Gray Elf
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Racial Immunity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfRacialImmunity
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Low-Light Vision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfLowLightVision
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Weapon Proficiency|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfWeaponProficiency
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Skill Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfSkillBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|STR,CON|-2|TYPE=Racial
- **BONUS:** STAT|DEX,INT|2|TYPE=Racial
- **COST:** 0

### Wild

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Elf ~ Wild],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Wild Elf
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Racial Immunity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfRacialImmunity
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Low-Light Vision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfLowLightVision
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Weapon Proficiency|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfWeaponProficiency
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Skill Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfSkillBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|INT|-2|TYPE=Racial
- **BONUS:** STAT|DEX|2|TYPE=Racial
- **COST:** 0

### Wood

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Elf ~ Wood],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Wood Elf
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Racial Immunity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfRacialImmunity
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Low-Light Vision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfLowLightVision
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Weapon Proficiency|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfWeaponProficiency
- **ABILITY:** Elf Race Trait|AUTOMATIC|Elf ~ Skill Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.ElfSkillBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Elf)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|CON,INT|-2|TYPE=Racial
- **BONUS:** STAT|STR,DEX|2|TYPE=Racial
- **COST:** 0

### Svirfneblin

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Gnome ~ Svirfneblin],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Blindness/Deafness,16+CHA|Blur,14+CHA|Disguise Self,15+CHA
- **TEMPLATE:** Svirfneblin Gnome
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Low-Light Vision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeRacialVision
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Weapon Familiarity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeWeaponFamiliarity
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeSaveBonus
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial School DC Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeIllusionDC
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Attack Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeAttacksBonus
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Dodge Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeDodgeBonus
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Listen Skill|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeRacialListenSkill
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Alchemy Skill|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeRacialAlchemySkill
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Spell-Like Abilities|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeSpellLikeAbilities
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Svirfneblin ~ Stonecunning
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Svirfneblin)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Svirfneblin)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** COMBAT|AC|4|TYPE=Dodge.STACK
- **BONUS:** DC|SCHOOL.Illusion|1
- **BONUS:** SKILL|Craft (Alchemy),Listen,Hide|2|TYPE=Racial
- **BONUS:** STAT|STR|-2|TYPE=Racial
- **BONUS:** STAT|DEX|2|TYPE=Racial
- **BONUS:** STAT|WIS|2|TYPE=Racial
- **BONUS:** STAT|CHA|-4|TYPE=Racial
- **BONUS:** VAR|DarkvisionRange|120|TYPE=Base
- **SR:** TL+11
- **COST:** 0
- **BONUS:** SAVE|Fortitude,Reflex,Will|2|TYPE=Racial

### Forest

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Gnome ~ Forest],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Forest Gnome
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Low-Light Vision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeRacialVision
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Weapon Familiarity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeWeaponFamiliarity
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeSaveBonus
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial School DC Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeIllusionDC
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Attack Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeAttacksBonus
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Dodge Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeDodgeBonus
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Listen Skill|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeRacialListenSkill
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Racial Alchemy Skill|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeRacialAlchemySkill
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Gnome ~ Spell-Like Abilities|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.GnomeSpellLikeAbilities
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Forest Gnome Traits ~ Forest Gnome
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Forest Gnome ~ Pass without Trace
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Forest Gnome ~ Hide Bonus
- **ABILITY:** Gnome Race Trait|AUTOMATIC|Forest Gnome ~ Languages|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace,TYPE.BonusLangReplace
- **COST:** 0
- **BONUS:** VAR|AllowGnomeSLA_SpeakWithAnimals|-1|TYPE=Boolean

### Tallfellow

- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,Halfling ~ Tallfellow],[!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice]
- **TEMPLATE:** Tallfellow Halfling
- **ABILITY:** Halfling Race Trait|AUTOMATIC|Halfling ~ Racial +2 Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.HalflingMoraleSaveBonus
- **ABILITY:** Halfling Race Trait|AUTOMATIC|Halfling ~ Racial +1 Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.HalflingSaveBonus
- **ABILITY:** Halfling Race Trait|AUTOMATIC|Halfling ~ Racial Attack Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DisableRacialTraits,TYPE.HalflingAttackBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Tallfellow Halfling)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Tallfellow Halfling)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** SKILL|Listen,Search,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|-2|TYPE=Racial
- **BONUS:** STAT|DEX|2|TYPE=Racial
- **COST:** 0

### Language ~ Auto (Duergar)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Dwarven
- **ABILITY:** Language|AUTOMATIC|Undercommon

### Language ~ Auto (Drow)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Elven
- **ABILITY:** Language|AUTOMATIC|Undercommon

### Language ~ Auto (Svirfneblin)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Gnome
- **ABILITY:** Language|AUTOMATIC|Undercommon

### Language ~ Auto (Tallfellow Halfling)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Halfling
- **ABILITY:** Language|AUTOMATIC|Elven

### Language ~ Auto (Deep Halfling)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Halfling
- **ABILITY:** Language|AUTOMATIC|Dwarven

### Language ~ Bonus (Duergar)

- **TEMPLATE:** Language ~ Bonus (Duergar)

### Language ~ Bonus (Drow)

- **TEMPLATE:** Language ~ Bonus (Drow)

### Language ~ Bonus (Svirfneblin)

- **TEMPLATE:** Language ~ Bonus (Svirfneblin)

### Language ~ Bonus (Tallfellow Halfling)

- **TEMPLATE:** Language ~ Bonus (Tallfellow Halfling)

### Language ~ Bonus (Deep Halfling)

- **TEMPLATE:** Language ~ Bonus (Deep Halfling)

### Deep Dwarf Racial Traits


### Light Sensitivity


Deep dwarves are dazzled in bright sunlight or within the radius of a daylight spell.

### Duergar Traits


### Spell-Like Abilities


1/day-enlarge person and invisibility as a wizard of twice the duergar's class level (minimum caster level 3rd); these abilities affect only the duergar and whatever it carries.

### Immunity to paralysis, phantasms, and poison

- **ABILITY:** Special Ability|AUTOMATIC|Immunity To Paralysis|Immunity to Phantasms|Immunity to Poison

This trait replaces the hill dwarf's +2 racial bonus on saving throws against poison.

### Aquatic Elf Traits


### Superior Low-Light Vision


Aquatic elves can see four times as far as a human in starlight, moonlight, torchlight, and similar conditions of low illumination. This trait replaces the high elf's low-light vision.

### Gills


Aquatic elves can survive out of the water for 1 hour per point of Constitution (after that, refer to the suffocation rules).

### Drow Traits


+2 Intelligence, +2 Charisma.

Darkvision out to 120 feet. This trait replaces the high elf's low-light vision.

Spell resistance equal to 11 + class levels.

+2 racial bonus on Will saves against spells and spell-like abilities.

Spell-Like Abilities: Drow can use the following spell-like abilities once per day: dancing lights, darkness, faerie fire. Caster level equals the drow's class levels.

Weapon Proficiency: A drow is automatically proficient with the hand crossbow, the rapier, and the short sword. This trait replaces the high elf 's weapon proficiency.

Light Blindness: Abrupt exposure to bright light (such as sunlight or a daylight spell) blinds drow for 1 round. On subsequent rounds, they are dazzled as long as they remain in the affected area.

### Darkvision

- **BONUS:** VAR|DarkvisionRange|120|TYPE=Base

Darkvision out to 120 feet. This trait replaces the high elf's low-light vision.

### Light Blindness


Abrupt exposure to bright light (such as sunlight or a daylight spell) blinds drow for 1 round. On subsequent rounds, they are dazzled as long as they remain in the affected area.

### Weapon Proficiency

- **AUTO:** WEAPONPROF|Crossbow (Hand)|Rapier|Sword (Short)

A drow is automatically proficient with the hand crossbow, the rapier, and the short sword. This trait replaces the high elf 's weapon proficiency.

### Spell Resistance

- **SR:** TL+11

### Svirfneblin Traits


These traits are in addition to the rock gnome traits, except where noted. -2 Strength, +2 Dexterity, +2 Wisdom, -4 Charisma. These adjustments replace the rock gnome's ability score adjustments. Stonecunning: This ability grants deep gnomes a +2 racial bonus on Search checks to notice unusual stonework. A deep gnome who merely comes within 10 feet of unusual stonework can make a Search check as though actively searching, and can use the Search skill to find stonework traps as a rogue can. A svirfneblin can also intuit depth, sensing the approximate distance underground as naturally as a human can sense which way is up. Darkvision out to 120 feet and low-light vision. Spell resistance equal to 11 + class levels. +2 racial bonus on all saving throws (figured into the statistics for the character presented here). This trait replaces the rock gnome's racial bonus on saving throws against illusions. Add +1 to the Difficulty Class for all saving throws against illusion spells cast by svirfneblin. This adjustment stacks with those from similar effects, such as the Spell Focus feat. +1 racial bonus on attack rolls against kobolds and goblinoids. +4 dodge bonus to Armor Class against all creatures (figured into the statistics for the character presented here). This trait replaces the rock gnome's dodge bonus against giants. Automatic Languages: Undercommon, Gnome, Common. Bonus Languages: Dwarven, Elven, Giant, Goblin, Orc, Terran. This trait replaces the rock gnome's automatic and bonus languages. Spell-Like Abilities: 1/day blindness/deafness (typical save DC 13), blur, disguise self. Caster level equals the svirfneblin's class levels. The save DC is Charisma-based and include a +4 racial modifier. This trait replaces the rock gnome's spell-like abilities. Nondetection (Su): A svirfneblin has a continuous nondetection ability as the spell (caster level equal to class levels). +2 racial bonus on Craft (alchemy) and Listen checks. +2 racial bonus on Hide checks, which improves to +4 underground.

### Stonecunning


This ability grants deep gnomes a +2 racial bonus on Search checks to notice unusual stonework. A deep gnome who merely comes within 10 feet of unusual stonework can make a Search check as though actively searching, and can use the Search skill to find stonework traps as a rogue can. A svirfneblin can also intuit depth, sensing the approximate distance underground as naturally as a human can sense which way is up.

### Forest Gnome Traits


These traits are in addition to the rock gnome traits, except where noted. Pass without Trace (Su): A forest gnome has the innate ability to use pass without trace (self only, as a free action) as the spell cast by a druid of the forest gnome's class levels. +1 racial bonus on attack rolls against kobolds, goblinoids, orcs, and reptilian humanoids. Automatic Languages: Gnome, Elven, Sylvan, and a simple language that enables them to communicate on a very basic level with forest animals (this replaces the rock gnome's speak with animals ability). Bonus Languages: Common, Draconic, Dwarven, Giant, Goblin, Orc. This trait replaces the rock gnome's automatic and bonus languages. +4 racial bonus on Hide checks, which improves to +8 in a wooded area.

### Pass without Trace

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=TL|Pass Without Trace

A forest gnome has the innate ability to use pass without trace (self only, as a free action) as the spell cast by a druid of the forest gnome's class levels.

### Skill Bonus

- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** SITUATION|Hide=in a wooded area|4|TYPE=Racial

+4 racial bonus on Hide checks, which improves to +8 in a wooded area.

### Languages

- **ABILITY:** Language|AUTOMATIC|Gnome|Elven|Sylvan|Forest Animals
- **TEMPLATE:** Language ~ Common
- **TEMPLATE:** Language ~ Draconic
- **TEMPLATE:** Language ~ Dwarven
- **TEMPLATE:** Language ~ Giant
- **TEMPLATE:** Language ~ Goblin
- **TEMPLATE:** Language ~ Orc

### Tallfellow Traits


These traits are in addition to the lightfoot halfling traits, except where noted. +2 racial bonus on Search, Spot, and Listen checks. Like an elf, a tallfellow who merely passes within 5 feet of a secret or concealed door is entitled to a Search check as though actively looking for it. This trait replaces the lightfoot's +2 bonus on Listen checks. Tallfellows are less athletic than lightfoot halflings and do not have a racial bonus on Climb, Jump, and Move Silently checks.

### Deep Halfling Traits

- **ASPECT:** RaceMaster|Yes

These traits are in addition to the lightfoot halfling traits, except where noted. Darkvision out to 60 feet. Stonecunning: Like dwarves, deep halflings have a +2 racial bonus on checks to notice unusual stonework. Something that isn't stone but that is disguised as stone also counts as unusual stonework. A deep halfling who merely comes within 10 feet of unusual stonework can make a check as though actively searching and can use the Search skill to find stonework traps as a rogue can. A deep halfling can also intuit depth, sensing the approximate distance underground as naturally as a human can sense which way is up. +2 racial bonus on Appraise checks and Craft checks that are related to stone or metal. Deep halflings are less athletic than lightfoot halflings and do not have a racial bonus on Climb, Jump, and Move Silently checks.

### Race Traits ~ Black Dragon

- **MOVE:** Walk,60,Swim,60
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Black Dragon ~ Breath Weapon|Black Dragon ~ Water Breathing|Immunity to Acid
- **ABILITY:** Special Ability|AUTOMATIC|Black Dragon ~ Other Spell-Like Abilities
- **ABILITY:** Special Ability|AUTOMATIC|Black Dragon ~ Corrupt Water
- **ABILITY:** Special Ability|AUTOMATIC|Black Dragon ~ Charm Reptile
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|-2|TYPE=Racial
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|(DragonLVL-1)/3
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|3
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonNaturalArmor|3

### Race Traits ~ Blue Dragon

- **MOVE:** Walk,40,Burrow,20
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Blue Dragon ~ Breath Weapon|Blue Dragon ~ Create/Destroy Water|Blue Dragon ~ Skills|Immunity To Electricity
- **ABILITY:** Special Ability|AUTOMATIC|Blue Dragon ~ Sound Imitation
- **ABILITY:** Special Ability|AUTOMATIC|Blue Dragon ~ Other Spell-Like Abilities
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|(DragonLVL-3)/3
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonLevelAdjustment|5
- **BONUS:** VAR|DragonNaturalArmor|5

### Race Traits ~ Green Dragon

- **MOVE:** Walk,40,Swim,40
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Green Dragon ~ Breath Weapon|Green Dragon ~ Skills|Green Dragon ~ Water Breathing|Immunity to Acid
- **ABILITY:** Special Ability|AUTOMATIC|Green Dragon ~ Spell-Like Abilities
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|(DragonLVL-2)/3
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|5
- **BONUS:** VAR|DragonLevelAdjustment|6
- **BONUS:** VAR|DragonNaturalArmor|4

### Race Traits ~ Red Dragon

- **MOVE:** Walk,40
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Red Dragon ~ Breath Weapon|Red Dragon ~ Skills
- **ABILITY:** Special Ability|AUTOMATIC|Red Dragon ~ Locate Object
- **ABILITY:** Special Ability|AUTOMATIC|Red Dragon ~ Other Spell-Like Abilities
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** STAT|STR|6|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|CON|4|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|(DragonLVL-4)/3
- **BONUS:** VAR|DragonSizeTracker|2
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonLevelAdjustment|5
- **BONUS:** VAR|DragonLevelAdjustment|6
- **BONUS:** VAR|DragonNaturalArmor|6

### Race Traits ~ White Dragon

- **MOVE:** Walk,60,Burrow,30,Swim,60
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|White Dragon ~ Breath Weapon|White Dragon ~ Icewalking|White Dragon ~ Skills
- **ABILITY:** Special Ability|AUTOMATIC|White Dragon ~ Other Spell-Like Abilities
- **ABILITY:** Special Ability|AUTOMATIC|White Dragon ~ Freezing Fog
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MOVEADD|TYPE.Fly|50
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|-4|TYPE=Racial
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|DragonLVL/3
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|2
- **BONUS:** VAR|DragonLevelAdjustment|3
- **BONUS:** VAR|DragonLevelAdjustment|3
- **BONUS:** VAR|DragonLevelAdjustment|5
- **BONUS:** VAR|DragonNaturalArmor|2

### Race Traits ~ Brass Dragon

- **MOVE:** Walk,60,Burrow,30
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Brass Dragon ~ Breath Weapon|Brass Dragon ~ Skills
- **ABILITY:** Special Ability|AUTOMATIC|Brass Dragon ~ Spell-Like Abilities
- **ABILITY:** Special Ability|AUTOMATIC|Brass Dragon ~ Summon Djinni
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MOVEADD|TYPE.Fly|50
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|2
- **BONUS:** VAR|DragonLevelAdjustment|3
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonAgeCategory|min(((DragonLVL-1)/3),12)
- **BONUS:** VAR|DragonNaturalArmor|3

### Race Traits ~ Bronze Dragon

- **MOVE:** Walk,40,Swim,60
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Bronze Dragon ~ Breath Weapon|Bronze Dragon ~ Skills|Bronze Dragon ~ Water Breathing|Immunity To Electricity
- **ABILITY:** Special Ability|AUTOMATIC|Bronze Dragon ~ Alternate Form
- **ABILITY:** Special Ability|AUTOMATIC|Bronze Dragon ~ Spell-Like Abilities
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|4|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|4|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonLevelAdjustment|6
- **BONUS:** VAR|DragonAgeCategory|min((DragonLVL-3)/3),12
- **BONUS:** VAR|DragonNaturalArmor|5

### Race Traits ~ Copper Dragon

- **MOVE:** Walk,40
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Copper Dragon ~ Breath Weapon|Copper Dragon ~ Skills|Copper Dragon ~ Spider Climb|Immunity to Acid
- **ABILITY:** Special Ability|AUTOMATIC|Copper Dragon ~ Spell-Like Abilities
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|(DragonLVL-2)/3
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|2
- **BONUS:** VAR|DragonLevelAdjustment|3
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonNaturalArmor|4

### Race Traits ~ Gold Dragon

- **MOVE:** Walk,60,Swim,60
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Gold Dragon ~ Alternate Form|Gold Dragon ~ Breath Weapon|Gold Dragon ~ Skills|Gold Dragon ~ Water Breathing
- **ABILITY:** Special Ability|AUTOMATIC|Gold Dragon ~ Other Spell-Like Abilities
- **ABILITY:** Special Ability|AUTOMATIC|Gold Dragon ~ Luck Bonus
- **ABILITY:** Special Ability|AUTOMATIC|Gold Dragon ~ Detect Gems
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MOVEADD|TYPE.Fly|50
- **BONUS:** STAT|STR|6|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|4|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|4|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|(DragonLVL-5)/3
- **BONUS:** VAR|DragonSizeTracker|2
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonLevelAdjustment|5
- **BONUS:** VAR|DragonLevelAdjustment|6
- **BONUS:** VAR|DragonNaturalArmor|7

### Race Traits ~ Silver Dragon

- **MOVE:** Walk,40
- **ABILITY:** Internal|AUTOMATIC|True Dragon Defaults
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Acid|Silver Dragon ~ Alternate Form|Silver Dragon ~ Breath Weapon|Silver Dragon ~ Cloudwalking|Silver Dragon ~ Skills
- **ABILITY:** Special Ability|AUTOMATIC|Silver Dragon ~ Spell-Like Abilities
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|3
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|2
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|2|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|STR|4|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|CON|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|4|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|INT,CHA|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** STAT|WIS|2|TYPE=Racial.STACK
- **BONUS:** VAR|DragonAgeCategory|(DragonLVL-1)/3
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonSizeTracker|1
- **BONUS:** VAR|DragonLevelAdjustment|3
- **BONUS:** VAR|DragonLevelAdjustment|4
- **BONUS:** VAR|DragonNaturalArmor|6

### Breath Weapon

- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|BlackDragonBWDieSize|4

A black dragon has one type of breath weapon, a line of acid. Damage %1d%2, DC %3, Length %4|DragonBreathWeaponDice|DragonBreathWeaponDieSize|DC_Breath_Weapon|DragonBreathWeaponLine

### Charm Reptile


A great wyrm black dragon can use this ability three times per day. It works as a mass charm spell that affects only reptilian animals. The dragon can communicate with any charmed reptiles as though casting a speak with animals spell. This ability is the equivalent of a 1st-level spell.

### Water Breathing


A black dragon can breathe underwater indefinitely and can freely use its breath weapon, spells, and other abilities while submerged.

### Corrupt Water


Once per day an adult or older black dragon can stagnate 10 cubic feet of water, making it become still, foul, and unable to support animal life. The ability spoils liquids containing water. Magic items (such as potions) and items in a creature's possession must succeed on a Will save (DC equal to that of the dragon's frightful presence) or become fouled. This ability is the equivalent of a 1st-level spell. Its range is equal to that of the dragon's frightful presence.

### Charm Reptiles


A great wyrm black dragon can use this ability three times per day. It works as a mass charm spell that affects only reptilian animals. The dragon can communicate with any charmed reptiles as though casting a speak with animals spell. This ability is the equivalent of a 1st-level spell.

### Other Spell-Like Abilities


3/day-darkness (juvenile or older; radius 10 feet per age category), insect plague (ancient or older); 1/day-plant growth (old or older).

### Skills


Hide, Move Silently, and Swim are considered class skills for black dragons.

### Create/Destroy Water


A blue dragon of any age can use this ability three times per day. It works like the create water spell, except that the dragon can decide to destroy water instead of creating it, which automatically spoils unattended liquids containing water. Magic items (such as potions) and items in a creature's possession must succeed on a Will save (DC equal to that of the dragon's frightful presence) or be ruined. This ability is the equivalent of a 1st-level spell.

### Sound Imitation


A juvenile or older blue dragon can mimic any voice or sound it has heard, anytime it likes. Listeners must succeed on a Will save (DC equal to that of the dragon's frightful presence) to detect the ruse.

### Locate Object


A juvenile or older red dragon can use this ability as the spell of the same name, once per day per age category.

### Icewalking


This ability works like the spider climb spell, but the surfaces the dragon climbs must be icy. It is always in effect.

### Freezing Fog

- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Freezing Fog ~ White Dragon

An old or older white dragon can use this ability three times per day. It is similar to a solid fog spell but also causes a rime of slippery ice to form on any surface the fog touches, creating the effect of a grease spell. The dragon is immune to the grease effect because of its icewalking ability. This ability is the equivalent of a 5th-level spell.

### Summon Djinni


This ability, usable by a great wyrm brass dragon, works like a summon monster spell, except that it summons one djinni. This ability is the equivalent of a 7th-level spell.

### Alternate Form


A young or older bronze dragon can assume any animal or humanoid form of Medium size or smaller as a standard action three times per day. This ability functions as a polymorph spell cast on itself at its caster level, except that the dragon does not regain hit points for changing form and can only assume the form of an animal or humanoid. The dragon can remain in its animal or humanoid form until it chooses to assume a new one or return to its natural form.

### Spider Climb


A copper dragon can climb on stone surfaces as though using the spider climb spell.

### Luck Bonus


Once per day an adult or older gold dragon can touch a gem, usually one embedded in the dragon's hide, and enspell it to bring good luck. As long as the dragon carries the gem, it and every good creature in a 10-foot radius per age category of the dragon receives a +1 luck bonus on all saving throws and similar rolls, as for a stone of good luck (see the item description, page 267 of the Dungeon Master's Guide). If the dragon gives an enspelled gem to another creature, only that bearer gets the bonus. The effect lasts 1d3 hours plus 3 hours per age category of the dragon but ends if the gem is destroyed. This ability is the equivalent of a 2nd-level spell.

### Detect Gems


An old or older gold dragon can use this ability three times per day. This is a divination effect similar to a detect magic spell, except that it finds only gems. The dragon can scan a 60-degree arc each round: By concentrating for 1 round it knows if there are any gems within the arc; 2 rounds of concentration reveal the exact number of gems; and 3 rounds reveal their exact location, type, and value. This ability is the equivalent of a 2nd level spell.

### Cloudwalking


A silver dragon can tread on clouds or fog as though on solid ground. The ability functions continuously but can be negated or resumed at will.

### Bard Class

- **ADD:** SPELLCASTER|Bard

### Cleric Class

- **ADD:** SPELLCASTER|Cleric

### Sorcerer Class

- **ADD:** SPELLCASTER|Sorcerer

### Wizard Class

- **ADD:** SPELLCASTER|Wizard

### Air Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Air
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Air|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Animal Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Animal
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Animal|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Chaos Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Chaos
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Chaos|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Death Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Death
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Death|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Destruction Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Destruction
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Destruction|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Earth Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Earth
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Earth|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Evil Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Evil
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Evil|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Fire Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Fire
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Fire|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Good Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Good
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Good|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Healing Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Healing
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Healing|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Law Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Law
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Law|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Luck Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Luck
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Luck|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Knowledge Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Knowledge
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Knowledge|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Magic Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Magic
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Magic|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Plant Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Plant
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Plant|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Protection Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Protection
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Protection|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Strength Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Strength
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Strength|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Sun Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Sun
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Sun|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Travel Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Travel
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Travel|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Trickery Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Trickery
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Trickery|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### War Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ War
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ War|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Water Domain

- **ABILITY:** Internal|AUTOMATIC|Cleric Domain ~ Water
- **ABILITY:** Internal|AUTOMATIC|Sorcerer Domain ~ Water|!PREABILITY:1,CATEGORY=Internal,Cleric Class

### Sorcerer Domain ~ Air

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Obscuring Mist|Sorcerer/Cleric (Arcane)=2|Wind Wall|Sorcerer/Cleric (Arcane)=3|Gaseous Form|Sorcerer/Cleric (Arcane)=4|Air Walk|Sorcerer/Cleric (Arcane)=5|Control Winds|Sorcerer/Cleric (Arcane)=6|Chain Lightning|Sorcerer/Cleric (Arcane)=7|Control Weather|Sorcerer/Cleric (Arcane)=8|Whirlwind|Sorcerer/Cleric (Arcane)=9|Elemental Swarm

### Sorcerer Domain ~ Animal

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Calm Animals|Sorcerer/Cleric (Arcane)=2|Hold Animal|Sorcerer/Cleric (Arcane)=3|Dominate Animal|Sorcerer/Cleric (Arcane)=4|Summon Nature's Ally IV|Sorcerer/Cleric (Arcane)=5|Commune with Nature|Sorcerer/Cleric (Arcane)=6|Antilife Shell|Sorcerer/Cleric (Arcane)=7|Animal Shapes|Sorcerer/Cleric (Arcane)=8|Summon Nature's Ally VIII|Sorcerer/Cleric (Arcane)=9|Shapechange

### Sorcerer Domain ~ Chaos

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Protection from Law|Sorcerer/Cleric (Arcane)=2|Shatter|Sorcerer/Cleric (Arcane)=3|Magic Circle against Law|Sorcerer/Cleric (Arcane)=4|Chaos Hammer|Sorcerer/Cleric (Arcane)=5|Dispel Law|Sorcerer/Cleric (Arcane)=6|Animate Objects|Sorcerer/Cleric (Arcane)=7|Word of Chaos|Sorcerer/Cleric (Arcane)=8|Cloak of Chaos|Sorcerer/Cleric (Arcane)=9|Summon Monster IX

### Sorcerer Domain ~ Death

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Cause Fear|Sorcerer/Cleric (Arcane)=2|Death Knell|Sorcerer/Cleric (Arcane)=3|Animate Dead|Sorcerer/Cleric (Arcane)=4|Death Ward|Sorcerer/Cleric (Arcane)=5|Slay Living|Sorcerer/Cleric (Arcane)=6|Create Undead|Sorcerer/Cleric (Arcane)=7|Destruction|Sorcerer/Cleric (Arcane)=8|Create Greater Undead|Sorcerer/Cleric (Arcane)=9|Wail of the Banshee

### Sorcerer Domain ~ Destruction

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Inflict Light Wounds|Sorcerer/Cleric (Arcane)=2|Shatter|Sorcerer/Cleric (Arcane)=3|Contagion|Sorcerer/Cleric (Arcane)=4|Inflict Critical Wounds|Sorcerer/Cleric (Arcane)=5|Inflict Light Wounds (Mass)|Sorcerer/Cleric (Arcane)=6|Harm|Sorcerer/Cleric (Arcane)=7|Disintegrate|Sorcerer/Cleric (Arcane)=8|Earthquake|Sorcerer/Cleric (Arcane)=9|Implosion

### Sorcerer Domain ~ Earth

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Magic Stone|Sorcerer/Cleric (Arcane)=2|Soften Earth and Stone|Sorcerer/Cleric (Arcane)=3|Stone Shape|Sorcerer/Cleric (Arcane)=4|Spike Stones|Sorcerer/Cleric (Arcane)=5|Wall of Stone|Sorcerer/Cleric (Arcane)=6|Stoneskin|Sorcerer/Cleric (Arcane)=7|Earthquake|Sorcerer/Cleric (Arcane)=8|Iron Body|Sorcerer/Cleric (Arcane)=9|Elemental Swarm

### Sorcerer Domain ~ Evil

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Protection from Good|Sorcerer/Cleric (Arcane)=2|Desecrate|Sorcerer/Cleric (Arcane)=3|Magic Circle against Good|Sorcerer/Cleric (Arcane)=4|Unholy Blight|Sorcerer/Cleric (Arcane)=5|Dispel Good|Sorcerer/Cleric (Arcane)=6|Create Undead|Sorcerer/Cleric (Arcane)=7|Blasphemy|Sorcerer/Cleric (Arcane)=8|Unholy Aura|Sorcerer/Cleric (Arcane)=9|Summon Monster IX

### Sorcerer Domain ~ Fire

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Burning Hands|Sorcerer/Cleric (Arcane)=2|Produce Flame|Sorcerer/Cleric (Arcane)=3|Resist Energy|Sorcerer/Cleric (Arcane)=4|Wall of Fire|Sorcerer/Cleric (Arcane)=5|Fire Shield|Sorcerer/Cleric (Arcane)=6|Fire Seeds|Sorcerer/Cleric (Arcane)=7|Fire Storm|Sorcerer/Cleric (Arcane)=8|Incendiary Cloud|Sorcerer/Cleric (Arcane)=9|Elemental Swarm

### Sorcerer Domain ~ Good

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Protection from Evil|Sorcerer/Cleric (Arcane)=2|Aid|Sorcerer/Cleric (Arcane)=3|Magic Circle against Evil|Sorcerer/Cleric (Arcane)=4|Holy Smite|Sorcerer/Cleric (Arcane)=5|Dispel Evil|Sorcerer/Cleric (Arcane)=6|Blade Barrier|Sorcerer/Cleric (Arcane)=7|Holy Word|Sorcerer/Cleric (Arcane)=8|Holy Aura|Sorcerer/Cleric (Arcane)=9|Summon Monster IX

### Sorcerer Domain ~ Healing

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Cure Light Wounds|Sorcerer/Cleric (Arcane)=2|Cure Moderate Wounds|Sorcerer/Cleric (Arcane)=3|Cure Serious Wounds|Sorcerer/Cleric (Arcane)=4|Cure Critical Wounds|Sorcerer/Cleric (Arcane)=5|Cure Light Wounds (Mass)|Sorcerer/Cleric (Arcane)=6|Heal|Sorcerer/Cleric (Arcane)=7|Regenerate|Sorcerer/Cleric (Arcane)=8|Cure Critical Wounds (Mass)|Sorcerer/Cleric (Arcane)=9|Heal (Mass)

### Sorcerer Domain ~ Law

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Protection from Chaos|Sorcerer/Cleric (Arcane)=2|Calm Emotions|Sorcerer/Cleric (Arcane)=3|Magic Circle against Chaos|Sorcerer/Cleric (Arcane)=4|Order's Wrath|Sorcerer/Cleric (Arcane)=5|Dispel Chaos|Sorcerer/Cleric (Arcane)=6|Hold Monster|Sorcerer/Cleric (Arcane)=7|Dictum|Sorcerer/Cleric (Arcane)=8|Shield of Law|Sorcerer/Cleric (Arcane)=9|Summon Monster IX

### Sorcerer Domain ~ Luck

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Entropic Shield|Sorcerer/Cleric (Arcane)=2|Aid|Sorcerer/Cleric (Arcane)=3|Protection from Energy|Sorcerer/Cleric (Arcane)=4|Freedom of Movement|Sorcerer/Cleric (Arcane)=5|Break Enchantment|Sorcerer/Cleric (Arcane)=6|Mislead|Sorcerer/Cleric (Arcane)=7|Spell Turning|Sorcerer/Cleric (Arcane)=8|Moment of Prescience|Sorcerer/Cleric (Arcane)=9|Miracle

### Sorcerer Domain ~ Knowledge

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Detect Secret Doors|Sorcerer/Cleric (Arcane)=2|Detect Thoughts|Sorcerer/Cleric (Arcane)=3|Clairaudience/Clairvoyance|Sorcerer/Cleric (Arcane)=4|Divination|Sorcerer/Cleric (Arcane)=5|True Seeing|Sorcerer/Cleric (Arcane)=6|Find the Path|Sorcerer/Cleric (Arcane)=7|Legend Lore|Sorcerer/Cleric (Arcane)=8|Discern Location|Sorcerer/Cleric (Arcane)=9|Foresight

### Sorcerer Domain ~ Magic

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Magic Aura|Sorcerer/Cleric (Arcane)=2|Identify|Sorcerer/Cleric (Arcane)=3|Dispel Magic|Sorcerer/Cleric (Arcane)=4|Imbue with Spell Ability|Sorcerer/Cleric (Arcane)=5|Spell Resistance|Sorcerer/Cleric (Arcane)=6|Antimagic Field|Sorcerer/Cleric (Arcane)=7|Spell Turning|Sorcerer/Cleric (Arcane)=8|Protection from Spells|Sorcerer/Cleric (Arcane)=9|Mage's Disjunction

### Sorcerer Domain ~ Plant

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Entangle|Sorcerer/Cleric (Arcane)=2|Barkskin|Sorcerer/Cleric (Arcane)=3|Plant Growth|Sorcerer/Cleric (Arcane)=4|Command Plants|Sorcerer/Cleric (Arcane)=5|Wall of Thorns|Sorcerer/Cleric (Arcane)=6|Repel Wood|Sorcerer/Cleric (Arcane)=7|Animate Plants|Sorcerer/Cleric (Arcane)=8|Control Plants|Sorcerer/Cleric (Arcane)=9|Shambler

### Sorcerer Domain ~ Protection

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Sanctuary|Sorcerer/Cleric (Arcane)=2|Shield Other|Sorcerer/Cleric (Arcane)=3|Protection from Energy|Sorcerer/Cleric (Arcane)=4|Spell Immunity|Sorcerer/Cleric (Arcane)=5|Spell Resistance|Sorcerer/Cleric (Arcane)=6|Antimagic Field|Sorcerer/Cleric (Arcane)=7|Repulsion|Sorcerer/Cleric (Arcane)=8|Mind Blank|Sorcerer/Cleric (Arcane)=9|Prismatic Sphere

### Sorcerer Domain ~ Strength

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Enlarge Person|Sorcerer/Cleric (Arcane)=2|Bull's Strength|Sorcerer/Cleric (Arcane)=3|Magic Vestment|Sorcerer/Cleric (Arcane)=4|Spell Immunity|Sorcerer/Cleric (Arcane)=5|Righteous Might|Sorcerer/Cleric (Arcane)=6|Stoneskin|Sorcerer/Cleric (Arcane)=7|Grasping Hand|Sorcerer/Cleric (Arcane)=8|Clenched Fist|Sorcerer/Cleric (Arcane)=9|Crushing Hand

### Sorcerer Domain ~ Sun

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Endure Elements|Sorcerer/Cleric (Arcane)=2|Heat Metal|Sorcerer/Cleric (Arcane)=3|Searing Light|Sorcerer/Cleric (Arcane)=4|Fire Shield|Sorcerer/Cleric (Arcane)=5|Flame Strike|Sorcerer/Cleric (Arcane)=6|Fire Seeds|Sorcerer/Cleric (Arcane)=7|Sunbeam|Sorcerer/Cleric (Arcane)=8|Sunburst|Sorcerer/Cleric (Arcane)=9|Prismatic Sphere

### Sorcerer Domain ~ Travel

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Longstrider|Sorcerer/Cleric (Arcane)=2|Locate Object|Sorcerer/Cleric (Arcane)=3|Fly|Sorcerer/Cleric (Arcane)=4|Dimension Door|Sorcerer/Cleric (Arcane)=5|Teleport|Sorcerer/Cleric (Arcane)=6|Find the Path|Sorcerer/Cleric (Arcane)=7|Teleport (Greater)|Sorcerer/Cleric (Arcane)=8|Phase Door|Sorcerer/Cleric (Arcane)=9|Astral Projection

### Sorcerer Domain ~ Trickery

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Disguise Self|Sorcerer/Cleric (Arcane)=2|Invisibility|Sorcerer/Cleric (Arcane)=3|Nondetection|Sorcerer/Cleric (Arcane)=4|Confusion|Sorcerer/Cleric (Arcane)=5|False Vision|Sorcerer/Cleric (Arcane)=6|Mislead|Sorcerer/Cleric (Arcane)=7|Screen|Sorcerer/Cleric (Arcane)=8|Polymorph Any Object|Sorcerer/Cleric (Arcane)=9|Time Stop

### Sorcerer Domain ~ War

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Magic Weapon|Sorcerer/Cleric (Arcane)=2|Spiritual Weapon|Sorcerer/Cleric (Arcane)=3|Magic Vestment|Sorcerer/Cleric (Arcane)=4|Divine Power|Sorcerer/Cleric (Arcane)=5|Flame Strike|Sorcerer/Cleric (Arcane)=6|Blade Barrier|Sorcerer/Cleric (Arcane)=7|Power Word Blind|Sorcerer/Cleric (Arcane)=8|Power Word Stun|Sorcerer/Cleric (Arcane)=9|Power Word Kill

### Sorcerer Domain ~ Water

- **SPELLLEVEL:** CLASS|Sorcerer/Cleric (Arcane)=1|Obscuring Mist|Sorcerer/Cleric (Arcane)=2|Fog Cloud|Sorcerer/Cleric (Arcane)=3|Water Breathing|Sorcerer/Cleric (Arcane)=4|Control Water|Sorcerer/Cleric (Arcane)=5|Ice Storm|Sorcerer/Cleric (Arcane)=6|Cone of Cold|Sorcerer/Cleric (Arcane)=7|Acid Fog|Sorcerer/Cleric (Arcane)=8|Horrid Wilting|Sorcerer/Cleric (Arcane)=9|Elemental Swarm

### Cleric Domain ~ Air

- **SPELLLEVEL:** CLASS|Cleric=1|Obscuring Mist|Cleric=2|Wind Wall|Cleric=3|Gaseous Form|Cleric=4|Air Walk|Cleric=5|Control Winds|Cleric=6|Chain Lightning|Cleric=7|Control Weather|Cleric=8|Whirlwind|Cleric=9|Elemental Swarm

### Cleric Domain ~ Animal

- **SPELLLEVEL:** CLASS|Cleric=1|Calm Animals|Cleric=2|Hold Animal|Cleric=3|Dominate Animal|Cleric=4|Summon Nature's Ally IV|Cleric=5|Commune with Nature|Cleric=6|Antilife Shell|Cleric=7|Animal Shapes|Cleric=8|Summon Nature's Ally VIII|Cleric=9|Shapechange

### Cleric Domain ~ Chaos

- **SPELLLEVEL:** CLASS|Cleric=1|Protection from Law|Cleric=2|Shatter|Cleric=3|Magic Circle against Law|Cleric=4|Chaos Hammer|Cleric=5|Dispel Law|Cleric=6|Animate Objects|Cleric=7|Word of Chaos|Cleric=8|Cloak of Chaos|Cleric=9|Summon Monster IX

### Cleric Domain ~ Death

- **SPELLLEVEL:** CLASS|Cleric=1|Cause Fear|Cleric=2|Death Knell|Cleric=3|Animate Dead|Cleric=4|Death Ward|Cleric=5|Slay Living|Cleric=6|Create Undead|Cleric=7|Destruction|Cleric=8|Create Greater Undead|Cleric=9|Wail of the Banshee

### Cleric Domain ~ Destruction

- **SPELLLEVEL:** CLASS|Cleric=1|Inflict Light Wounds|Cleric=2|Shatter|Cleric=3|Contagion|Cleric=4|Inflict Critical Wounds|Cleric=5|Inflict Light Wounds (Mass)|Cleric=6|Harm|Cleric=7|Disintegrate|Cleric=8|Earthquake|Cleric=9|Implosion

### Cleric Domain ~ Earth

- **SPELLLEVEL:** CLASS|Cleric=1|Magic Stone|Cleric=2|Soften Earth and Stone|Cleric=3|Stone Shape|Cleric=4|Spike Stones|Cleric=5|Wall of Stone|Cleric=6|Stoneskin|Cleric=7|Earthquake|Cleric=8|Iron Body|Cleric=9|Elemental Swarm

### Cleric Domain ~ Evil

- **SPELLLEVEL:** CLASS|Cleric=1|Protection from Good|Cleric=2|Desecrate|Cleric=3|Magic Circle against Good|Cleric=4|Unholy Blight|Cleric=5|Dispel Good|Cleric=6|Create Undead|Cleric=7|Blasphemy|Cleric=8|Unholy Aura|Cleric=9|Summon Monster IX

### Cleric Domain ~ Fire

- **SPELLLEVEL:** CLASS|Cleric=1|Burning Hands|Cleric=2|Produce Flame|Cleric=3|Resist Energy|Cleric=4|Wall of Fire|Cleric=5|Fire Shield|Cleric=6|Fire Seeds|Cleric=7|Fire Storm|Cleric=8|Incendiary Cloud|Cleric=9|Elemental Swarm

### Cleric Domain ~ Good

- **SPELLLEVEL:** CLASS|Cleric=1|Protection from Evil|Cleric=2|Aid|Cleric=3|Magic Circle against Evil|Cleric=4|Holy Smite|Cleric=5|Dispel Evil|Cleric=6|Blade Barrier|Cleric=7|Holy Word|Cleric=8|Holy Aura|Cleric=9|Summon Monster IX

### Cleric Domain ~ Healing

- **SPELLLEVEL:** CLASS|Cleric=1|Cure Light Wounds|Cleric=2|Cure Moderate Wounds|Cleric=3|Cure Serious Wounds|Cleric=4|Cure Critical Wounds|Cleric=5|Cure Light Wounds (Mass)|Cleric=6|Heal|Cleric=7|Regenerate|Cleric=8|Cure Critical Wounds (Mass)|Cleric=9|Heal (Mass)

### Cleric Domain ~ Law

- **SPELLLEVEL:** CLASS|Cleric=1|Protection from Chaos|Cleric=2|Calm Emotions|Cleric=3|Magic Circle against Chaos|Cleric=4|Order's Wrath|Cleric=5|Dispel Chaos|Cleric=6|Hold Monster|Cleric=7|Dictum|Cleric=8|Shield of Law|Cleric=9|Summon Monster IX

### Cleric Domain ~ Luck

- **SPELLLEVEL:** CLASS|Cleric=1|Entropic Shield|Cleric=2|Aid|Cleric=3|Protection from Energy|Cleric=4|Freedom of Movement|Cleric=5|Break Enchantment|Cleric=6|Mislead|Cleric=7|Spell Turning|Cleric=8|Moment of Prescience|Cleric=9|Miracle

### Cleric Domain ~ Knowledge

- **SPELLLEVEL:** CLASS|Cleric=1|Detect Secret Doors|Cleric=2|Detect Thoughts|Cleric=3|Clairaudience/Clairvoyance|Cleric=4|Divination|Cleric=5|True Seeing|Cleric=6|Find the Path|Cleric=7|Legend Lore|Cleric=8|Discern Location|Cleric=9|Foresight

### Cleric Domain ~ Magic

- **SPELLLEVEL:** CLASS|Cleric=1|Magic Aura|Cleric=2|Identify|Cleric=3|Dispel Magic|Cleric=4|Imbue with Spell Ability|Cleric=5|Spell Resistance|Cleric=6|Antimagic Field|Cleric=7|Spell Turning|Cleric=8|Protection from Spells|Cleric=9|Mage's Disjunction

### Cleric Domain ~ Plant

- **SPELLLEVEL:** CLASS|Cleric=1|Entangle|Cleric=2|Barkskin|Cleric=3|Plant Growth|Cleric=4|Command Plants|Cleric=5|Wall of Thorns|Cleric=6|Repel Wood|Cleric=7|Animate Plants|Cleric=8|Control Plants|Cleric=9|Shambler

### Cleric Domain ~ Protection

- **SPELLLEVEL:** CLASS|Cleric=1|Sanctuary|Cleric=2|Shield Other|Cleric=3|Protection from Energy|Cleric=4|Spell Immunity|Cleric=5|Spell Resistance|Cleric=6|Antimagic Field|Cleric=7|Repulsion|Cleric=8|Mind Blank|Cleric=9|Prismatic Sphere

### Cleric Domain ~ Strength

- **SPELLLEVEL:** CLASS|Cleric=1|Enlarge Person|Cleric=2|Bull's Strength|Cleric=3|Magic Vestment|Cleric=4|Spell Immunity|Cleric=5|Righteous Might|Cleric=6|Stoneskin|Cleric=7|Grasping Hand|Cleric=8|Clenched Fist|Cleric=9|Crushing Hand

### Cleric Domain ~ Sun

- **SPELLLEVEL:** CLASS|Cleric=1|Endure Elements|Cleric=2|Heat Metal|Cleric=3|Searing Light|Cleric=4|Fire Shield|Cleric=5|Flame Strike|Cleric=6|Fire Seeds|Cleric=7|Sunbeam|Cleric=8|Sunburst|Cleric=9|Prismatic Sphere

### Cleric Domain ~ Travel

- **SPELLLEVEL:** CLASS|Cleric=1|Longstrider|Cleric=2|Locate Object|Cleric=3|Fly|Cleric=4|Dimension Door|Cleric=5|Teleport|Cleric=6|Find the Path|Cleric=7|Teleport (Greater)|Cleric=8|Phase Door|Cleric=9|Astral Projection

### Cleric Domain ~ Trickery

- **SPELLLEVEL:** CLASS|Cleric=1|Disguise Self|Cleric=2|Invisibility|Cleric=3|Nondetection|Cleric=4|Confusion|Cleric=5|False Vision|Cleric=6|Mislead|Cleric=7|Screen|Cleric=8|Polymorph Any Object|Cleric=9|Time Stop

### Cleric Domain ~ War

- **SPELLLEVEL:** CLASS|Cleric=1|Magic Weapon|Cleric=2|Spiritual Weapon|Cleric=3|Magic Vestment|Cleric=4|Divine Power|Cleric=5|Flame Strike|Cleric=6|Blade Barrier|Cleric=7|Power Word Blind|Cleric=8|Power Word Stun|Cleric=9|Power Word Kill

### Cleric Domain ~ Water

- **SPELLLEVEL:** CLASS|Cleric=1|Obscuring Mist|Cleric=2|Fog Cloud|Cleric=3|Water Breathing|Cleric=4|Control Water|Cleric=5|Ice Storm|Cleric=6|Cone of Cold|Cleric=7|Acid Fog|Cleric=8|Horrid Wilting|Cleric=9|Elemental Swarm

### Fast Healing

- **DEFINE:** FastHealingRate|0
- **ASPECT:** NAME|Fast Healing %1|FastHealingRate

### Amphibious


Creature can breathe both air and water.

### Fast Healing 5


### Fast Healing 2


### Enslave

- **DEFINE:** DC_Enslave|0
- **BONUS:** VAR|DC_Enslave|DC_CHA
- **BONUS:** VAR|DC_Enslave|2
- **ABILITY:** Ability Focus|AUTOMATIC|Enslave

Three times per day, an aboleth can attempt to enslave any one living creature within 30 feet. The target must succeed on a DC %1 Will save or be affected as though by a dominate person spell (caster level 16th). An enslaved creature obeys the aboleth's telepathic commands until freed by remove curse, and can attempt a new Will save every 24 hours to break free. The control is also broken if the aboleth dies or travels more than 1 mile from its slave. The save DC is Charisma-based.|DC_Enslave

### Psionics


At will-hypnotic pattern (DC 15), illusory wall (DC 17), mirage arcana (DC 18), persistent image (DC 18), programmed image (DC 19), project image (DC 20), veil (DC 19). Effective caster level 16th. The save DCs are Charisma-based.

### Slime

- **DEFINE:** DC_Slime|0
- **BONUS:** VAR|DC_Slime|DC_CON
- **BONUS:** VAR|DC_Slime|2
- **ABILITY:** Ability Focus|AUTOMATIC|Slime

A blow from an aboleth's tentacle can cause a terrible affliction. A creature hit by a tentacle must succeed on a DC %1 Fortitude save or begin to transform over the next 1d4+1 minutes, the skin gradually becoming a clear, slimy membrane. An afflicted creature must remain moistened with cool, fresh water or take 1d12 points of damage every 10 minutes. The slime reduces the creature's natural armor bonus by 1 (but never to less than 0). The save DC is Constitution-based. A remove disease spell cast before the transformation is complete will restore an afflicted creature to normal. Afterward, however, only a heal or mass heal spell can reverse the affliction.|DC_Slime

### Mucus Cloud

- **DEFINE:** DC_Mucus_Cloud|0
- **BONUS:** VAR|DC_Mucus_Cloud|DC_CON
- **BONUS:** VAR|DC_Mucus_Cloud|2
- **ABILITY:** Ability Focus|AUTOMATIC|Mucus Cloud

An aboleth underwater surrounds itself with a viscous cloud of mucus roughly 1 foot thick. Any creature coming into contact with and inhaling this substance must succeed on a DC %1 Fortitude save or lose the ability to breathe air for the next 3 hours. An affected creature suffocates in 2d6 minutes if removed from the water. Renewed contact with the mucus cloud and failing another Fortitude save continues the effect for another 3 hours. The save DC is Constitution-based.|DC_Mucus_Cloud

### Natural Weapons


An achaierai's natural weapons, as well as any weapons it wields, are treated as evil-aligned and lawfulaligned for the purpose of overcoming damage reduction.

### Black Cloud

- **DEFINE:** DC_Black_Cloud|0
- **BONUS:** VAR|DC_Black_Cloud|DC_CON
- **BONUS:** VAR|DC_Black_Cloud|2
- **ABILITY:** Ability Focus|AUTOMATIC|Black Cloud

Up to three times per day an achaierai can release a choking, toxic black cloud. Those other than achaierai within 10 feet instantly take 2d6 points of damage. They must also succeed on a DC %1 Fortitude save or be affected for 3 hours as though by an insanity spell (caster level 16th). The save DC is Constitution-based.|DC_Black_Cloud

### Babble

- **DEFINE:** DC_Babble|0
- **BONUS:** VAR|DC_Babble|DC_CHA
- **BONUS:** VAR|DC_Babble|2
- **ABILITY:** Ability Focus|AUTOMATIC|Babble

An allip constantly mutters and whines to itself, creating a hypnotic effect. All sane creatures within 60 feet of the allip must succeed on a DC 16 Will save or be affected as though by a hypnotism spell for 2d4 rounds. This is a sonic mind-affecting compulsion effect. Creatures that successfully save cannot be affected by the same allip's babble for 24 hours. The save DC is Charisma-based.|DC_Babble

### Madness


Anyone targeting an allip with a thought detection, mind control, or telepathic ability makes direct contact with its tortured mind and takes 1d4 points of Wisdom damage.

### Wisdom Drain


An allip causes 1d4 points of Wisdom drain each time it hits with its incorporeal touch attack. On each such successful attack, it gains 5 temporary hit points.

### Protective Aura


Against attacks made or effects created by evil creatures, this ability provides a +4 deflection bonus to AC and a +4 resistance bonus on saving throws to anyone within 20 feet of the angel. Otherwise, it functions as a magic circle against evil effect and a lesser globe of invulnerability, both with a radius of 20 feet (caster level equals angel's HD). This aura can be dispelled, but the angel can create it again as a free action on its next turn. (The defensive benefits from the circle are not included in an angel's statistics block.)

### Tongues


All angels can speak with any creature that has a language, as though using a tongues spell (caster level equal to angel's Hit Dice). This ability is always active.

### Angel Traits


An angel possesses the following traits (unless otherwise noted in a creature's entry). Darkvision out to 60 feet and low-light vision. Immunity to acid, cold, and petrification. Resistance to electricity 10 and fire 10. +4 racial bonus on saves against poison. Protective Aura (Su): Against attacks made or effects created by evil creatures, this ability provides a +4 deflection bonus to AC and a +4 resistance bonus on saving throws to anyone within 20 feet of the angel. Otherwise, it functions as a magic circle against evil effect and a lesser globe of invulnerability, both with a radius of 20 feet (caster level equals angel's HD). This aura can be dispelled, but the angel can create it again as a free action on its next turn. (The defensive benefits from the circle are not included in an angel's statistics block.) Tongues (Su): All angels can speak with any creature that has a language, as though using a tongues spell (caster level equal to angel's Hit Dice). This ability is always active.

### Race Traits ~ Astral Daeva

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Astral Daeva ~ Change Shape|Astral Daeva ~ Natural Weapons|Astral Daeva ~ Spell-Like Abilities|Astral Daeva ~ Stun|Astral Daeva ~ Uncanny Dodge

### Change Shape


An astral deva can assume the form of any Small or Medium humanoid.

### Stun

- **DEFINE:** DC_Stun|0
- **BONUS:** VAR|DC_Stun|DC_STR
- **BONUS:** VAR|DC_Stun|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stun

If an astral deva strikes an opponent twice in one round with its mace, that creature must succeed on a DC %1 Fortitude save or be stunned for 1d6 rounds. The save DC is Strength-based.|DC_Stun

### Uncanny Dodge


An astral deva retains its Dexterity bonus to AC when flat-footed, and it cannot be flanked except by a rogue of at least 16th level. It can flank characters with the uncanny dodge ability as if it were a 12th-level rogue.

### Race Traits ~ Planetar

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Planetar ~ Natural Weapons|Planetar ~ Regeneration|Planetar ~ Spell-Like Abilities|Planetar ~ Spells

### Regeneration


A planetar takes damage from evil-aligned weapons and from spells and effects with the evil descriptor.

### Spells

- **BONUS:** ABILITYPOOL|All Monster Domains|2

Planetars can cast divine spells as 17th-level clerics. A planetar has access to two of the following domains: Air, Destruction, Good, Law, or War (plus any others from its deity). The save DCs are Wisdom-based. Typical Cleric Spells Prepared (6/8/8/7/7/6/6/4/3/2; save DC 16 + spell level): 0-create water, detect magic, guidance, resistance (2), virtue; 1st-bless (2), cause fear, divine favor (2), entropic shield, inflict light wounds*, shield of faith; 2nd-aid*, align weapon, bear 's endurance, bull's strength (2), consecrate, eagle's splendor, hold person; 3rd-contagion*, daylight, invisibility purge, prayer (2), summon monster III, wind wall; 4th- death ward, dismissal, inflict critical wounds*, neutralize poison (2), summon monster IV; 5th- break enchantment, circle of doom*, dispel evil, mark of justice, plane shift, righteous might; 6th-banishment, greater dispel magic, harm*, heal, heroes' feast, mass cure moderate wounds; 7th- dictum, disintegrate*, holy word, regenerate; 8th-holy aura*, mass cure critical wounds, shield of law; 9th-implosion, summon monster IX (good)*. *Domain spell. Domains: Destruction and Good.

### Race Traits ~ Solar

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Solar ~ Natural Weapons|Solar ~ Regeneration|Solar ~ Spell-Like Abilities|Solar ~ Spells

### Blind


A sheetlike animated object such as a carpet or tapestry can grapple an opponent up to three sizes larger than itself. The object makes a normal grapple check. If it wins, it wraps itself around the opponent's head, causing that creature to be blinded until removed.

### Constrict


A flexible animated object such as a rope, vine, or rug deals damage equal to its slam damage value plus 1? times its Strength bonus with a successful grapple check against a creature up to one size larger than itself. An object of at least Large size can make constriction attacks against multiple creatures at once, if they all are at least two sizes smaller than the object and can fit under it.

### Hardness


An animated object has the same hardness it had before it was animated.

### Improved Speed


The base land speed given in the statistics block assume that an animated object lurches, rocks, or slithers along. Objects with two legs (statues, ladders) or a similar shape that allows faster movement have a +10 foot bonus to speed. Objects with multiple legs (tables, chairs) have a +20 foot bonus to speed. Wheeled objects have a +40 foot bonus to speed. Objects might have additional modes of movement. A wooden object can float and has a swim speed equal to half its land speed. A rope or similar sinuous object has a climb speed equal to half its land speed. A sheetlike object can fly (clumsy maneuverability) at half its normal speed.

### Trample


An animated object of at least Large size and with a hardness of at least 10 can trample creatures two or more sizes smaller than itself, dealing damage equal to the object's slam damage + 1 1/2 times its Strength bonus. Opponents who do not make attacks of opportunity against the object can attempt Reflex saves (DC 10 + 1/2 object's HD + object's Str modifier) to halve the damage.

### Walk

- **BONUS:** MOVEADD|TYPE.Walk|10
- **BONUS:** MOVEADD|TYPE.Walk|20
- **BONUS:** MOVEADD|TYPE.Walk|30

### Legs

- **MOVE:** Legs,10
- **BONUS:** MOVEADD|TYPE.Walk|-10
- **BONUS:** MOVEADD|TYPE.Legs|10
- **BONUS:** MOVEADD|TYPE.Legs|20
- **BONUS:** MOVEADD|TYPE.Legs|30
- **BONUS:** MOVEADD|TYPE.Legs|40

### Multiple Legs

- **MOVE:** Multiple Legs,10
- **BONUS:** MOVEADD|TYPE.Walk|-10
- **BONUS:** MOVEADD|TYPE.Multiple Legs|20
- **BONUS:** MOVEADD|TYPE.Multiple Legs|30
- **BONUS:** MOVEADD|TYPE.Multiple Legs|40
- **BONUS:** MOVEADD|TYPE.Multiple Legs|50

### Wheels

- **MOVE:** Wheels,10
- **BONUS:** MOVEADD|TYPE.Walk|-10
- **BONUS:** MOVEADD|TYPE.Wheels|40
- **BONUS:** MOVEADD|TYPE.Wheels|50
- **BONUS:** MOVEADD|TYPE.Wheels|60
- **BONUS:** MOVEADD|TYPE.Wheels|70

### Spit Acid

- **DEFINE:** DC_Spit_Acid|0
- **BONUS:** VAR|DC_Spit_Acid|DC_CON
- **BONUS:** VAR|DC_Spit_Acid|2
- **ABILITY:** Ability Focus|AUTOMATIC|Spit Acid

30-ft. line, once every 6 hours; damage 4d4 acid, Reflex DC %1 half. One such attack depletes the ankheg's acid supply for 6 hours. It cannot spit acid or deal acid damage during this time. The save DC is Constitution-based. An ankheg does not use this ability unless it is desperate or frustrated. It most often spits acid when reduced to fewer than half its full normal hit points or when it has not successfully grabbed an opponent.|DC_Spit_Acid

### Web


In spider or hybrid form (see below), an aranea can throw a web up to six times per day. This is similar to an attack with a net but has a maximum range of 50 feet, with a range increment of 10 feet, and is effective against targets of up to Large size. The web anchors the target in place, allowing no movement. An entangled creature can escape with a DC 13 Escape Artist check or burst the web with a DC 17 Strength check. The check DCs are Constitution-based, and the Strength check DC includes a +4 racial bonus. The web has 6 hit points, hardness 0, and takes double damage from fire.

### Aura of Menace


A righteous aura surrounds archons that fight or get angry. Any hostile creature within a 20-foot radius of an archon must succeed on a Will save to resist its effects. The save DC varies with the type of archon, is Charisma-based, and includes a +2 racial bonus. Those who fail take a -2 penalty on attacks, AC, and saves for 24 hours or until they successfully hit the archon that generated the aura. A creature that has resisted or broken the effect cannot be affected again by the same archon's aura for 24 hours.

### Magic Circle against Evil


A magic circle against evil effect always surrounds an archon (caster level equals the archon's Hit Dice). (The defensive benefits from the circle are not included in an archon's statistics block.)

### Teleport


Archons can use greater teleport at will, as the spell (caster level 14th), except that the creature can transport only itself and up to 50 pounds of objects.

### Light Ray


A lantern archon's light rays have a range of 30 feet. This attack overcomes damage reduction of any type.

### Trumpet

- **DEFINE:** DC_Trumpet|0
- **BONUS:** VAR|DC_Trumpet|DC_CHA
- **BONUS:** VAR|DC_Trumpet|2
- **ABILITY:** Ability Focus|AUTOMATIC|Trumpet

An archon's trumpet produces music of utter clarity, piercing beauty, and, if the trumpet archon wills it, paralyzing awe. All creatures except archons within 100 feet of the blast must succeed on a DC %1 Fortitude save or be paralyzed for 1d4 rounds. The save DC is Charisma-based. The archon can also command its trumpet to become a +4 greatsword as a free action. If a trumpet is ever stolen, it becomes a chunk of useless metal until the owner can recover it. Woe betide any thief caught with one.|DC_Trumpet

### Electricity Ray


An arrowhawk can fire this ray once per round, with a range of 50 feet.

### Entangle

- **DEFINE:** DC_Entangle|0
- **BONUS:** VAR|DC_Entangle|DC_WIS
- **BONUS:** VAR|DC_Entangle|2
- **ABILITY:** Ability Focus|AUTOMATIC|Entangle

An assassin vine can animate plants within 30 feet of itself as a free action (Ref DC %1 partial). The effect lasts until the vine dies or decides to end it (also a free action). The save DC is Wisdom-based. The ability is otherwise similar to entangle (caster level 4th).|DC_Entangle

### Blindsight


Assassin vines have no visual organs but can ascertain all foes within 30 feet using sound, scent, and vibration.

### Camouflage


Since an assassin vine looks like a normal plant when at rest, it takes a DC 20 Spot check to notice it before it attacks. Anyone with ranks in Survival or Knowledge (nature) can use one of those skills instead of Spot to notice the plant. Dwarves can use stonecunning to notice the subterranean version.

### Fear Aura

- **DEFINE:** DC_Fear|0
- **BONUS:** VAR|DC_Fear|DC_CHA
- **BONUS:** VAR|DC_Fear|2
- **ABILITY:** Ability Focus|AUTOMATIC|Fear

Once per day an avoral can create an aura of fear in a 20-foot radius. It is otherwise identical with fear from an 8th-level caster (save DC %1). The save DC is Charisma-based.|DC_Fear

### Lay on Hands


As the paladin class feature, except that each day, an avoral can heal an amount of damage equal to its full normal hit points.

### Speak with Animals


This ability works like speak with animals (caster level 8th) but is a free action and does not require sound.

### True Seeing


This ability is identical with true seeing (caster level 14th), except that it has personal range and the avoral must concentrate for 1 full round before it takes effect. Thereafter the ability remains in effect as long as the avoral concentrates on it.

### Heat


An azer's body is intensely hot, so its unarmed attacks deal extra fire damage. Its metallic weapons also conduct this heat.

### Feed


When a barghest slays a humanoid opponent, it can feed on the corpse, devouring both flesh and life force, as a full-round action. Feeding destroys the victim's body and prevents any form of raising or resurrection that requires part of the corpse. There is a 50%% chance that a wish, miracle, or true resurrection spell can restore a devoured victim to life. Check once for each destroyed creature. If the check fails, the creature cannot be brought back to life by mortal magic. A barghest advances in Hit Dice by consuming corpses in this fashion. For every three suitable corpses a barghest devours, it gains 1 Hit Die, and its Strength, Constitution, and natural armor increase by +1. Its attack bonus and saves improve as normal for an outsider of its Hit Dice, and it gains skill points, feats, and ability score improvements normally. The barghest only advances by consuming the corpses of creatures whose Hit Dice or levels are equal to or greater than its own current total. A barghest that reaches 9 Hit Dice through feeding immediately becomes a greater barghest upon completion of the act.

### Pass Without Trace


A barghest in wolf form can use pass without trace (as the spell) as a free action.

### Petrifying Gaze

- **DEFINE:** DC_Petrifying_Gaze|0
- **BONUS:** VAR|DC_Petrifying_Gaze|DC_CHA
- **BONUS:** VAR|DC_Petrifying_Gaze|2
- **ABILITY:** Ability Focus|AUTOMATIC|Petrifying Gaze

Turn to stone permanently, range 30 feet; Fortitude DC 13 negates. The save DC is Charisma-based.|DC_Petrifying_Gaze

### Swallow Whole


A behir can try to swallow a grabbed Medium or smaller opponent by making a successful grapple check. A behir that swallows an opponent can use its Cleave feat to bite and grab another opponent. A swallowed creature takes 2d8+8 points of bludgeoning damage and 8 points of acid damage per round from the behir's gizzard. A swallowed creature can cut its way out by using a light slashing or piercing weapon to deal 25 points of damage to the gizzard (AC 15). Once the creature exits, muscular action closes the hole; another swallowed opponent must cut its own way out. A behir's gizzard can hold 2 Medium, 8 Small, 32 Tiny, or 128 Diminutive or smaller opponents.

### Eye Rays


Each of a beholder's small eyes can produce a magical ray once per round as a free action. During a single round, a creature can aim only two eye rays (gauth) or three eye rays (beholder) at targets in any one 90-degree arc (up, forward, backward, left, right, or down). The remaining eyes must aim at targets in other arcs, or not at all. A beholder can tilt and pan its body each round to change which rays it can bring to bear in any given arc. Each eye's effect resembles a spell (caster level 8th level for a gauth, or 14th for a beholder), but follows the rules for a ray (see Aiming a Spell, page 175 of the Player's Handbook).

### All-Around Vision

- **BONUS:** SKILL|Spot,Search|4|TYPE=Racial

Beholders are exceptionally alert and circumspect. Their many eyes give them a +4 racial bonus on Spot and Search checks, and they can't be flanked.

### Flight


A beholder's body is naturally buoyant. This buoyancy allows it to fly at a speed of 20 feet. This buoyancy also grants it a permanent feather fall effect (as the spell) with personal range.

### Race Traits ~ Gauth

- **ABILITY:** Special Ability|AUTOMATIC|Beholder Race ~ All-Around Vision|Beholder Race ~ Eye Rays|Beholder Race ~ Flight|Gauth ~ Eye Rays|Gauth ~ Stunning Gaze

### Stunning Gaze

- **DEFINE:** DC_Stun|0
- **BONUS:** VAR|DC_Stun|DC_CHA
- **BONUS:** VAR|DC_Stun|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stun

Stun for 1 round, 30 feet, Will DC %1 negates. The save DC is Charisma-based. Any creature meeting the gaze of the gauth's central eye is subject to its stunning gaze attack. Since the gauth can use its eye-rays as a free action, the creature can use a standard action to focus its stunning gaze on an opponent and attack with all eye rays that bear on its foes at the same time.|DC_Stun

### Race Traits ~ Beholder

- **ABILITY:** Special Ability|AUTOMATIC|Beholder ~ Antimagic Cone|Beholder ~ Eye Rays|Beholder Race ~ All-Around Vision|Beholder Race ~ Eye Rays|Beholder Race ~ Flight

### Antimagic Cone


A beholder's central eye continually produces a 150- foot cone of antimagic. This functions just like antimagic field (caster level 13th). All magical and supernatural powers and effects within the cone are suppressed-even the beholder's own eye rays. Once each round, during its turn, the beholder decides whether the antimagic cone is active or not (the beholder deactivates the cone by shutting its central eye).

### Smoke Claws

- **DEFINE:** DC_Smoke_Claws|0
- **BONUS:** VAR|DC_Smoke_Claws|DC_CHA
- **BONUS:** VAR|DC_Smoke_Claws|2
- **ABILITY:** Ability Focus|AUTOMATIC|Smoke Claws

A belker in smoke form (see below) can engulf opponents by moving on top of them. It fills the air around one Medium or smaller opponent without provoking an attack of opportunity. The target must succeed on a DC %1 Fortitude save or inhale part of the creature. The save DC is Constitution-based. Smoke inside the victim solidifies into a claw and begins to rip at the surrounding organs, dealing 3d4 points of damage per round. An affected creature can attempt another Fortitude save each subsequent round to cough out the semivaporous menace.|DC_Smoke_Claws

### Smoke Form


Most of the time a belker is more or less solid, but at will it can assume smoke form. It can switch forms once per round as a free action and can spend up to 20 rounds per day in smoke form. A belker in smoke form can fly at a speed of 50 feet (perfect). The ability is otherwise similar to a gaseous form spell (caster level 7th).

### Blink


A blink dog can use blink as the spell (caster level 8th), and can evoke or end the effect as a free action.

### Dimension Door


A blink dog can teleport, as dimension door (caster level 8th), once per round as a free action. The ability affects only the blink dog, which never appears within a solid object and can act immediately after teleporting.

### Death Gaze

- **DEFINE:** DC_Death_Gaze|0
- **BONUS:** VAR|DC_Death_Gaze|DC_CHA
- **BONUS:** VAR|DC_Death_Gaze|2
- **ABILITY:** Ability Focus|AUTOMATIC|Death Gaze

Death, range 30 feet, Fortitude DC %1 negates. Humanoids who die from this attack are transformed into bodaks 24 hours later. The save DC is Charisma-based.|DC_Death_Gaze

### Vulnerability to Sunlight


Bodaks loathe sunlight, for its merest touch burns their impure flesh. Each round of exposure to the direct rays of the sun deals 1 point of damage to the creature.

### Whirlwind Blast

- **DEFINE:** DC_Whirlwind_Blast|0
- **BONUS:** VAR|DC_Whirlwind_Blast|DC_CON
- **BONUS:** VAR|DC_Whirlwind_Blast|2
- **ABILITY:** Ability Focus|AUTOMATIC|Whirlwind Blast

When in whirlwind form, a bralani can attack with a scouring blast of wind, dealing 3d6 points of damage in a 20-foot line (Reflex DC %1 half ). The save DC is Constitution-based.|DC_Whirlwind_Blast

### Leap


A bulette can jump into the air during combat. This allows it to make four claw attacks instead of two, each with a +15 attack bonus, but it cannot bite.

### Paralysis

- **DEFINE:** DC_Paralysis|0
- **BONUS:** VAR|DC_Paralysis|DC_CON
- **BONUS:** VAR|DC_Paralysis|2
- **ABILITY:** Ability Focus|AUTOMATIC|Paralysis

Those hit by a carrion crawler's tentacle attack must succeed on a DC %1 Fortitude save or be paralyzed for 2d4 rounds. The save DC is Constitution- based.|DC_Paralysis

### Corporeal Instability

- **DEFINE:** DC_Corporeal_Instability|0
- **BONUS:** VAR|DC_Corporeal_Instability|DC_CON
- **BONUS:** VAR|DC_Corporeal_Instability|2
- **ABILITY:** Ability Focus|AUTOMATIC|Corporeal Instability

A blow from a chaos beast against a living creature can cause a terrible transformation. The creature must succeed on a DC %1 Fortitude save or become a spongy, amorphous mass. Unless the victim manages to control the effect (see below), its shape melts, flows, writhes, and boils. The save DC is Constitution-based. An affected creature is unable to hold or use any item. Clothing, armor, rings, and helmets become useless. Large items worn or carried-armor, backpacks, even shirts-hamper more than help, reducing the victim's Dexterity score by 4. Soft or misshapen feet and legs reduce speed to 10 feet or one-quarter normal, whichever is less. Searing pain courses along the nerves, so strong that the victim cannot act coherently. The victim cannot cast spells or use magic items, and it attacks blindly, unable to distinguish friend from foe (-4 penalty on attack rolls and a 50%% miss chance, regardless of the attack roll). Each round the victim spends in an amorphous state causes 1 point of Wisdom drain from mental shock. If the victim's Wisdom score falls to 0, it becomes a chaos beast. A victim can regain its own shape by taking a standard action to attempt a DC 15 Charisma check (this check DC does not vary for a chaos beast with different Hit Dice or ability scores). A success reestablishes the creature's normal form for 1 minute. On a failure, the victim can still repeat this check each round until successful. Corporeal instability is not a disease or a curse and so is hard to remove. A shapechange or stoneskin spell does not cure an afflicted creature but fixes its form for the duration of the spell. A restoration, heal, or greater restoration spell removes the affliction (a separate restoration is necessary to restore any drained points of Wisdom).|DC_Corporeal_Instability

### Immunity to Transformation


No mortal magic can permanently affect or fix a chaos beast's form. Effects such as polymorphing or petrification force the creature into a new shape, but at the start of its next turn it immediately returns to its mutable form as a free action.

### Quickness


Although not particularly dexterous, a choker is supernaturally quick. It can take an extra standard action or move action during its turn each round.

### Paralytic Tentacles

- **DEFINE:** DC_Paralytic_Tentacles|0
- **BONUS:** VAR|DC_Paralytic_Tentacles|DC_CON
- **BONUS:** VAR|DC_Paralytic_Tentacles|2
- **ABILITY:** Ability Focus|AUTOMATIC|Paralytic Tentacles

A chuul can transfer grabbed victims from a claw to its ten- tacles as a move action. The tentacles grapple with the same strength as the claw but deal no damage. However, they exude a paralytic secretion. Anyone held in the tentacles must succeed on a DC %1 Fortitude save each round on the chuul's turn or be paralyzed for 6 rounds. The save DC is Constitution-based. While held in the tentacles, paralyzed or not, a victim automatically takes 1d8+2 points of damage each round from the creature's mandibles.|DC_Paralytic_Tentacles

### Moan


A cloaker can emit a dangerous subsonic moan as a standard action. By changing the frequency, the cloaker can cause one of four effects. Cloakers are immune to these sonic, mindaffecting attacks. Unless otherwise specified, a creature that successfully saves against one of these effects cannot be affected by the same moan effect from the same cloaker for 24 hours. All save DCs for moan effects are Charisma-based.

Unnerve: Anyone within a 60-foot spread automatically takes a -2 penalty on attack and damage rolls. Those forced to hear the moan for more than 6 consecutive rounds must succeed on a DC 15 Will save or enter a trance, unable to attack or defend themselves until the moaning stops.

Fear: Anyone within a 30-foot spread must succeed on a DC 15 Will save or become panicked for 2 rounds.

Nausea: Anyone in a 30-foot cone must succeed on a DC 15 Fortitude save or be overcome by nausea and weakness. Affected characters fall prone and become nauseated for 1d4+1 rounds.

Stupor: A single creature within 30 feet of the cloaker must succeed on a DC 15 Fortitude save or be affected as though by a hold monster spell for 5 rounds. Even after a successful save, the creature must repeat the save if the cloaker uses this effect again.

### Engulf


A cloaker can try to wrap a Medium or smaller creature in its body as a standard action. The cloaker attempts a grapple that does not provoke an attack of opportunity. If it wins the grapple check, it establishes a hold and bites the engulfed victim with a +4 bonus on its attack roll. It can still use its whiplike tail to strike at other targets. Attacks that hit an engulfing cloaker deal half their damage to the monster and half to the trapped victim.

### Shadow Shift


A cloaker can manipulate shadows. This ability is effective only in shadowy areas and has three possible effects.

Obscure Vision: The cloaker gains concealment (20%% miss chance) for 1d4 rounds.

Dancing Images: This effect duplicates a mirror image spell (caster level 6th).

Silent Image: This effect duplicates a silent image spell (DC 15, caster level 6th). The save DC is Charisma-based.

### Petrification

- **DEFINE:** DC_Petrification|0
- **BONUS:** VAR|DC_Petrification|DC_CON
- **BONUS:** VAR|DC_Petrification|2
- **ABILITY:** Ability Focus|AUTOMATIC|Petrification

Creatures hit by a cockatrice's bite attack must succeed on a DC %1 Fortitude save or instantly turn to stone. The save DC is Constitution-based. Cockatrices have immunity to the petrification ability of other cockatrices, but other petrification attacks affect them normally.|DC_Petrification

### Ethereal Jaunt


This ability works like the ethereal jaunt spell (caster level 16th).

### Telepathy


A couatl can communicate telepathically with any creature within 90 feet that has an Intelligence score. The creature can respond to the couatl if it wishes-no common language is needed.

### Darkness


Once per day a darkmantle can cause darkness as the darkness spell (caster level 5th). It most often uses this ability just before attacking.

### Corrosive Slime


A delver produces a mucuslike slime that contains a highly corrosive substance. The slime is particularly effective against stone. A delver's mere touch deals 2d6 points of acid damage to organic creatures or objects. Against metallic creatures or objects, a delver's slime deals 4d8 points of damage, and against stony creatures (including earth elementals) or objects it deals 8d10 points of damage. A slam attack by a delver leaves a patch of slime that deals 2d6 points of damage on contact and another 2d6 points of damage in each of the next 2 rounds. A large quantity (at least a quart) of water or weak acid, such as vinegar, washes off the slime. An opponent's armor and clothing dissolve and become useless immediately unless the wearer succeeds on a DC 22 Reflex save. Weapons that strike a delver also dissolve immediately unless the wielder succeeds on a DC 22 Reflex save. A creature attacking a delver with natural weapons takes damage from its slime each time an attack hits unless the creature succeeds on a DC 22 Reflex save. These save DCs are Constitution-based.

### Stone Shape


A delver can alter its slime to temporarily soften stone instead of dissolving it. Once every 10 minutes, a delver can soften and shape up to 25 cubic feet of stone, as a stone shape spell (caster level 15th).

### Sneak Attack


A babau can make a sneak attack like a rogue, dealing an extra 2d6 points of damage whenever a foe is denied his or her Dexterity bonus, or when the babau is flanking.

### Protective Slime


A slimy red jelly coats the babau's skin. Any weapon that touches it takes 1d8 points of acid damage from the corrosive goo, and the weapon's hardness does not reduce this damage. A magic weapon may attempt a DC 18 Reflex save to avoid taking this damage. A creature who strikes the babau with an unarmed attack, unarmed strike, touch spell, or natural weapon takes this damage as well but can negate the damage with a DC 18 Reflex save. The save DCs are Constitution-based.

### Summon Demon


Once per day a babau can attempt to summon 1 babau with a 40%% chance of success. This ability is the equivalent of a 3rd-level spell.

### Death Throes

- **DEFINE:** DC_Death_Throes|0
- **BONUS:** VAR|DC_Death_Throes|DC_CON
- **BONUS:** VAR|DC_Death_Throes|2
- **ABILITY:** Ability Focus|AUTOMATIC|Death Throes

When killed, a balor explodes in a blinding flash of light that deals 100 points of damage to anything within 100 feet (Reflex DC %1 half ). This explosion automatically destroys any weapons the balor is holding. The save DC is Constitution-based.|DC_Death_Throes

### Vorpal Sword


Every balor carries a +1 vorpal longsword that looks like a flame or a bolt of lightning.

### Flaming Body


The body of a balor is wreathed in flame. Anyone grappling a balor takes 6d6 points of fire damage each round.

### Rend Armor


If a bebilith hits with both claw attacks, it pulls apart any armor worn by its foe. This attack deals 4d6+18 points of damage to the opponent's armor. Creatures not wearing armor are unaffected by this special attack. Armor reduced to 0 hit points is destroyed. Damaged armor may be repaired with a successful Craft (armorsmithing) check.

### Plane Shift


This ability affects only the bebilith. It is otherwise similar to the spell (caster level 12th).

### Stench

- **DEFINE:** DC_Stench|0
- **BONUS:** VAR|DC_Stench|DC_CON
- **BONUS:** VAR|DC_Stench|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stench

A hezrou's skin produces a foul-smelling, toxic liquid whenever it fights. Any living creature (except other demons) within 10 feet must succeed on a DC 24 Fortitude save or be nauseated for as long as it remains within the affected area and for 1d4 rounds afterward. Creatures that successfully save are sickened for as long as they remain in the area. A creature that successfully saves cannot be affected again by the same hezrou's stench for 24 hours. A delay poison or neutralize poison spell removes either condition from one creature. Creatures that have immunity to poison are unaffected, and creatures resistant to poison receive their normal bonus on their saving throws.. The save DC is Constitution-based.|DC_Stench

### Feats


In combination with its natural abilities, a marilith's Multiweapon Fighting feat allows it to attack with all its arms at no penalty.

### Smite

- **DEFINE:** DC_Smite|0
- **BONUS:** VAR|DC_Smite|DC_CHA
- **BONUS:** VAR|DC_Smite|2
- **ABILITY:** Ability Focus|AUTOMATIC|Smite

Three times per day a nalfeshnee can create a nimbus of unholy light. When the demon triggers the ability, rainbow-colored beams play around its body. One round later they burst in a 60-foot radius. Any creature within this area must succeed on a DC %1 Will save or be dazed for 1d10 rounds as visions of its worst fears hound it. The creature receives its full Dexterity and shield bonuses to AC if attacked but can take no actions. Other demons are immune to this effect. The save DC is Charisma-based.|DC_Smite

### Find Target


When ordered to find an item or a creature, a retriever does so unerringly, as though guided by discern location. The being giving the order must have seen (or must have an item belonging to) the creature to be found, or must have touched the object to be located. This ability is the equivalent of an 8th-level spell.

### Dance of Ruin

- **DEFINE:** DC_Dance_of_Ruin|0
- **BONUS:** VAR|DC_Dance_of_Ruin|DC_CHA
- **BONUS:** VAR|DC_Dance_of_Ruin|2
- **ABILITY:** Ability Focus|AUTOMATIC|Dance of Ruin

To use this ability, a group of at least three vrocks must join hands in a circle, dancing wildly and chanting. At the end of 3 rounds of dancing, a wave of crackling energy flashes outward in a 100-foot radius. All creatures except for demons within the radius take 20d6 points of damage (Reflex DC 18 half ). Stunning, paralyzing, or slaying one of the vrocks stops the dance. The save DC is Charisma-based.|DC_Dance_of_Ruin

### Spores


A vrock can release masses of spores from its body once every 3 rounds as a free action. The spores automatically deal 1d8 points of damage to all creatures adjacent to the vrock. They then penetrate the skin and grow, dealing an additional 1d4 points of damage each round for 10 rounds. At the end of this time, the victim is covered with a tangle of viny growths. (The vines are harmless and wither away in 1d4 days.) A delay poison spell stops the spores' growth for its duration. Bless, neutralize poison, or remove disease kills the spores, as does sprinkling the victim with a vial of holy water.

### Stunning Screech

- **DEFINE:** DC_Stunning_Screech|0
- **BONUS:** VAR|DC_Stunning_Screech|DC_CON
- **BONUS:** VAR|DC_Stunning_Screech|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stunning Screech

Once per hour a vrock can emit a piercing screech. All creatures except for demons within a 30-foot radius must succeed on a DC 22 Fortitude save or be stunned for 1 round. The save DC is Constitution-based.|DC_Stunning_Screech

### Poison Use


Derro typically carry 2d4 doses of greenblood oil or Medium monstrous spider venom, applying it to their crossbow bolts. Derro are not at risk of poisoning themselves when handling poison.

### Destructive Harmonics


A destrachan can blast sonic energy in a cone up to 80 feet long. It can also use this attack to affect any creatures or objects within a 30-foot radius. It can tune the harmonics of this destructive power to affect different types of targets. All save DCs are Charisma-based.

Flesh: Disrupting tissue and rending bone, this attack deals 4d6 points of damage to all within the area (Reflex DC 15 half ).

Nerves: A destrachan can focus its harmonics to knock out foes rather than slay them. This attack deals 6d6 points of nonlethal damage to all within the area (Reflex DC 15 half ).

Material: When using this form of harmonics, a destrachan chooses wood, stone, metal, or glass. All objects made of that material within the area must succeed on a DC 15 Fortitude save or shatter. Objects (or portions of objects) that have up to 30 hit points are potentially affected by this attack.

### Immunities


Destrachans have immunity to gaze attacks, visual effects, illusions, and other attack forms that rely on sight.

### Protection from Sonics


While they can be affected by loud noises and sonic spells (such as ghost sound or silence), destrachans are less vulnerable to sonic attacks (+4 circumstance bonus on all saves) because they can protect their ears. A destrachan whose sense of hearing is impaired is effectively blinded, and all targets are treated as having total concealment.

### See in Darkness


All baatezu can see perfectly in darkness of any kind, even that created by a deeper darkness spell.

### Summon


Baatezu share the ability to summon others of their kind (the success chance and type of baatezu summoned are noted in each monster description).

### Fear

- **DEFINE:** DC_Fear|0
- **BONUS:** VAR|DC_Fear|DC_CHA
- **BONUS:** VAR|DC_Fear|2
- **ABILITY:** Ability Focus|AUTOMATIC|Fear

A creature hit by a barbed devil must succeed on a DC %1 Will save or be affected as though by fear (caster level 9th). Whether or not the save is successful, that creature cannot be affected by that same barbed devil's fear ability for 24 hours. The save DC is Charisma-based.|DC_Fear

### Impale


A barbed devil deals 3d8+9 points of piercing damage to a grabbed opponent with a successful grapple check.

### Summon Devil


Once per day a barbed devil can attempt to summon 1d6 bearded devils or another barbed devil with a 35%% chance of success. This ability is the equivalent of a 4th-level spell.

### Barbed Defense


Any creature striking a barbed devil with handheld weapons or natural weapons takes 1d8+6 points of piercing and slashing damage from the devil's barbs. Note that weapons with exceptional reach, such as longspears, do not endanger their users in this way.

### Infernal Wound

- **DEFINE:** DC_Infernal_Wound|0
- **BONUS:** VAR|DC_Infernal_Wound|DC_CON
- **BONUS:** VAR|DC_Infernal_Wound|2
- **ABILITY:** Ability Focus|AUTOMATIC|Infernal Wound

The damage a bearded devil deals with its glaive causes a persistent wound. An injured creature loses 2 additional hit points each round. The wound does not heal naturally and resists healing spells. The continuing hit point loss can be stopped by a DC %1 Heal check, a cure spell, or a heal spell. However, a character attempting to cast a cure spell or a heal spell on a creature damaged by a bearded devil's glaive must succeed on a DC %1 caster level check, or the spell has no effect on the injured character. A successful Heal check automatically stops the continuing hit point loss as well as restoring hit points. The infernal wound is a supernatural ability of the bearded devil, not of the weapon. The check DC is Constitution-based.|DC_Infernal_Wound

### Beard

- **DEFINE:** DC_Beard|0
- **BONUS:** VAR|DC_Beard|DC_CON
- **BONUS:** VAR|DC_Beard|2
- **ABILITY:** Ability Focus|AUTOMATIC|Beard

If a bearded devil hits a single opponent with both claw attacks, it automatically hits with its beard. The affected creature takes 1d8+2 points of damage and must succeed on a DC %1 Fortitude save or be infected with a vile disease known as devil chills (incubation period 1d4 days, damage 1d4 Str). Damage is dealt each day until the afflicted creature succeeds on three consecutive Fortitude saves, the disease is cured magically, or the creature dies. The save DC is Constitution-based.|DC_Beard

### Battle Frenzy


Twice per day, a bearded devil can work itself into a battle frenzy similar to the barbarian's rage (+4 Strength, +4 Constitution, +2 morale bonus on Will saves, -2 AC penalty). The frenzy lasts for 6 rounds, and the bearded devil suffers no ill effects afterward.

### Dancing Chains

- **DEFINE:** DC_Dancing_Chains|0
- **BONUS:** VAR|DC_Dancing_Chains|DC_CHA
- **BONUS:** VAR|DC_Dancing_Chains|2
- **ABILITY:** Ability Focus|AUTOMATIC|Dancing Chains

A chain devil's most awesome attack is its ability to control up to four chains within 20 feet as a standard action, making the chains dance or move as it wishes. In addition, a chain devil can increase these chains' length by up to 15 feet and cause them to sprout razor-edged barbs. These chains attack as effectively as the devil itself. If a chain is in another creature's possession, the creature can attempt a DC %1 Will save to break the chain devil's power over that chain. If the save is successful, the kyton cannot attempt to control that particular chain again for 24 hours or until the chain leaves the creature's possession. The save DC is Charisma-based. A chain devil can climb chains it controls at its normal speed without making Climb checks.|DC_Dancing_Chains

### Unnerving Gaze

- **DEFINE:** DC_Unnerving_Gaze|0
- **BONUS:** VAR|DC_Unnerving_Gaze|DC_CHA
- **BONUS:** VAR|DC_Unnerving_Gaze|2
- **ABILITY:** Ability Focus|AUTOMATIC|Unnerving Gaze

Range 30 ft., Will DC %1 negates. A chain devil can make its face resemble one of an opponent's departed loved ones or bitter enemies. Those who fail their saves take a -2 penalty on attack rolls for 1d3 rounds. The save DC is Charisma-based.|DC_Unnerving_Gaze

### Invisible in Light


A hellcat is invisible in any area lit well enough for a human to see. In a darkened area, it shows up as a faintly glowing outline visible up to 30 feet away (60 feet if the viewer has low-light vision). Magical darkness smothers the glow and conceals the outline.

### Slow

- **DEFINE:** DC_Slow|0
- **BONUS:** VAR|DC_Slow|DC_CON
- **BONUS:** VAR|DC_Slow|2
- **ABILITY:** Ability Focus|AUTOMATIC|Slow

A hit from an ice devil's tail or spear induces numbing cold. The opponent must succeed on a DC %1 Fortitude save or be affected as though by a slow spell for 1d6 rounds. The save DC is Constitution-based.|DC_Slow

### Mindless


Immunity to mind-affecting effects (charms, compulsions, phantasms, patterns, and morale effects).

### Disease

- **DEFINE:** DC_Disease|0
- **BONUS:** VAR|DC_Disease|DC_CON
- **BONUS:** VAR|DC_Disease|2
- **ABILITY:** Ability Focus|AUTOMATIC|Disease

A creature struck by a pit fiend's bite attack must succeed on a DC %1 Fortitude save or be infected with a vile disease known as devil chills (incubation period 1d4 days, damage 1d4 Str). The save DC is Constitution-based.|DC_Disease

### Trap Essence

- **DEFINE:** DC_Trap_Essence|0
- **BONUS:** VAR|DC_Trap_Essence|DC_CHA
- **BONUS:** VAR|DC_Trap_Essence|2
- **ABILITY:** Ability Focus|AUTOMATIC|Trap Essence

The devourer is named for its ability to consume an enemy's life essence. to do so, it must forgo its normal melee attacks and make a trap essence attack. This requires a normal attack roll but deals no damage. The he save DC is Charisma-based. A slain creature's essence is trapped within the devourer's ribs, and the tiny figure takes on that victim's features. The trapped essence cannot be raised or resurrected, but a limited wish, miracle, or wish spell frees it, as does destroying the devourer. A devourer can hold only one essence at a time. The trapped essence provides a devourer with enough power to use five spell-like abilities for each Hit Die or level of the trapped creature. As this energy is expended, the twisted soul fades away until it evaporates completely. The trapped essence gains one negative level for every five times the devourer uses one of its spell-like abilities. When the essence's number of negative levels equals the creature's total Hit Dice or level, the essence is destroyed. If an essence is freed, the restored creature must succeed on a DC %1 Fortitude save for each negative level or lose that level permanently.|DC_Trap_Essence

### Spell Deflection


The trapped essence provides a measure of magical protection. If any of the following spells are cast at the devourer and overcome its spell resistance, they affect the imprisoned essence instead: banishment, chaos hammer, confusion, crushing despair, detect thoughts, dispel evil, dominate person, fear, geas/quest, holy word, hypnosis, imprisonment, magic jar, maze, suggestion, trap the soul, or any form of charm or compulsion. In many cases, this deflection effectively neutralizes the spell. Some of these effects might eliminate the trapped essence, depriving the devourer of its spell-like abilities until it can consume another victim.

### Acid Spray

- **DEFINE:** DC_Acid_Spray|0
- **BONUS:** VAR|DC_Acid_Spray|DC_CON
- **BONUS:** VAR|DC_Acid_Spray|2
- **ABILITY:** Ability Focus|AUTOMATIC|Acid Spray

A digester can spray acid in a 20-foot cone, dealing 4d8 points of damage to everything in the area. Once a digester uses this ability, it can't use it again until 1d4 rounds later. The creature can also produce a concentrated stream of acid that deals 8d8 points of damage to a single target within 5 feet. In either case, a DC %1 Reflex save halves the damage. The save DC is Constitution-based.|DC_Acid_Spray

### Powerful Charge


When a triceratops charges, its gore attack deals 4d8+20 points of damage.

### Rage


A dire badger that takes damage in combat flies into a berserk rage on its next turn, clawing and biting madly until either it or its opponent is dead. It gains +4 Strength, +4 Constitution, and -2 AC. The creature cannot end its rage voluntarily.

### Blindsense


A dire bat uses echolocation to pinpoint creatures within 40 feet. Opponents still have total concealment against the bat unless it can actually see them.

### Ferocity


A dire boar is such a tenacious combatant that it continues to fight without penalty even while disabled or dying.

### Keen Scent


A dire shark can notice creatures by scent in a 180-foot radius and can detect blood in the water at a range of up to 1 mile.

### Attach


A dire weasel that hits with its bite attack latches onto the opponent's body with its powerful jaws. An attached dire weasel loses its Dexterity bonus to AC and thus has an AC of 12. An attached dire weasel can be struck with a weapon or grappled itself. to remove an attached dire weasel through grappling, the opponent must achieve a pin against the creature.

### Blood Drain


A dire weasel drains blood for 1d4 points of Constitution damage each round it remains attached.

### Trip


A dire wolf that hits with a bite attack can attempt to trip its opponent (+11 check modifier) as a free action without making a touch attack or provoking an attack of opportunity. If the attempt fails, the opponent cannot react to trip the dire wolf.

### Race Traits ~ Displacer Beast

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=DisplacerBeastRaceAbility

### Displacement


A light-bending glamer continually surrounds a displacer beast, making it difficult to surmise the creature's true location. Any melee or ranged attack directed at it has a 50%% miss chance unless the attacker can locate the beast by some means other than sight. A true seeing effect allows the user to see the beast's position, but see invisibility has no effect.

### Resistance to Ranged Attacks


A displacer beast has a +2 resistance bonus on saves against any ranged magical attack that specifically targets it (except for ranged touch attacks).

### Detect Thoughts


A doppelganger can continuously use detect thoughts as the spell (caster level 18th; Will DC 13 negates). It can suppress or resume this ability as a free action. The save DC is Charisma-based.

### Capsize


A submerged dragon turtle that surfaces under a boat or ship less than 20 feet long capsizes the vessel 95%% of the time. It has a 50%% chance to capsize a vessel from 20 to 60 feet long and a 20%% chance to capsize one over 60 feet long.

### Roar

- **DEFINE:** DC_Roar|0
- **BONUS:** VAR|DC_Roar|DC_CHA
- **BONUS:** VAR|DC_Roar|2
- **ABILITY:** Ability Focus|AUTOMATIC|Roar

A dragonne can loose a devastating roar every 1d4 rounds. All creatures except dragonnes within 120 feet must succeed on a DC %1 Will save or become fatigued. Those within 30 feet who fail their saves become exhausted. The save DC is Charisma-based.|DC_Roar

### Tree Dependent


Each dryad is mystically bound to a single, enormous oak tree and must never stray more than 300 yards from it. Any who do become ill and die within 4d6 hours. A dryad's oak does not radiate magic.

### Wild Empathy


This power works like the druid's wild empathy class feature, except that the dryad has a +6 racial bonus on the check.

### Evasion


With a successful Reflex save against an attack that allows a Reflex save for half damage, a giant eagle takes no damage.

### Air Mastery


Airborne creatures take a -1 penalty on attack and damage rolls against an air elemental.

### Whirlwind


The elemental can transform itself into a whirlwind once every 10 minutes and remain in that form for up to 1 round for every 2 HD it has. In this form, the elemental can move through the air or along a surface at its fly speed. The whirlwind is 5 feet wide at the base, up to 30 feet wide at the top, and up to 50 feet tall, depending on the elemental's size. The elemental controls the exact height, but it must be at least 10 feet. The elemental's movement while in whirlwind form does not provoke attacks of opportunity, even if the elemental enters the space another creature occupies. Another creature might be caught in the whirlwind if it touches or enters the whirlwind, or if the elemental moves into or through the creature's space. Creatures one or more size categories smaller than the elemental might take damage when caught in the whirlwind (see the table below for details) and may be lifted into the air. An affected creature must succeed on a Reflex save when it comes into contact with the whirlwind or take the indicated damage. It must also succeed on a second Reflex save or be picked up bodily and held suspended in the powerful winds, automatically taking the indicated damage each round. A creature that can fly is allowed a Reflex save each round to escape the whirlwind. The creature still takes damage but can leave if the save is successful. The DC for saves against the whirlwind's effects varies with the elemental's size (see the table). The save DC is Strength based. Creatures trapped in the whirlwind cannot move except to go where the elemental carries them or to escape the whirlwind. Creatures caught in the whirlwind can otherwise act normally, but must succeed on a Concentration check (DC 15 + spell level) to cast a spell. Creatures caught in the whirlwind take a -4 penalty to Dexterity and a -2 penalty on attack rolls. The elemental can have only as many creatures trapped inside the whirlwind at one time as will fit inside the whirlwind's volume. The elemental can eject any carried creatures whenever it wishes, depositing them wherever the whirlwind happens to be. A summoned elemental always ejects trapped creatures before returning to its home plane. If the whirlwind's base touches the ground, it creates a swirling cloud of debris. This cloud is centered on the elemental and has a diameter equal to half the whirlwind's height. The cloud obscures all vision, including darkvision, beyond 5 feet. Creatures 5 feet away have concealment, while those farther away have total concealment. Those caught in the cloud must succeed on a Concentration check (DC 15 + spell level) to cast a spell. An elemental in whirlwind form cannot make slam attacks and does not threaten the area around it.

### Earth Mastery


An earth elemental gains a +1 bonus on attack and damage rolls if both it and its foe are touching the ground. If an opponent is airborne or waterborne, the elemental takes a -4 penalty on attack and damage rolls. (These modifiers are not included in the statistics block.)

### Push


An earth elemental can start a bull rush maneuver without provoking an attack of opportunity. The combat modifiers given in Earth Mastery, above, also apply to the elemental's opposed Strength checks.

### Earth Glide


An earth elemental can glide through stone, dirt, or almost any other sort of earth except metal as easily as a fish swims through water. Its burrowing leaves behind no tunnel or hole, nor does it create any ripple or other signs of its presence. A move earth spell cast on an area containing a burrowing earth elemental flings the elemental back 30 feet, stunning the creature for 1 round unless it succeeds on a DC 15 Fortitude save.

### Burn


A fire elemental's slam attack deals bludgeoning damage plus fire damage from the elemental's flaming body. Those hit by a fire elemental's slam attack also must succeed on a Reflex save or catch on fire. The flame burns for 1d4 rounds. The save DC varies with the elemental's size (see the table below). A burning creature can take a move action to put out the flame. The save DC is Constitution- based. Creatures hitting a fire elemental with natural weapons or unarmed attacks take fire damage as though hit by the elemental's attack, and also catch on fire unless they succeed on a Reflex save.

### Water Mastery


A water elemental gains a +1 bonus on attack and damage rolls if both it and its opponent are touching water. If the opponent or the elemental is touching the ground, the elemental takes a -4 penalty on attack and damage rolls. (These modifiers are not included in the statistics block.) A water elemental can be a serious threat to a ship that crosses its path. An elemental can easily overturn small craft (5 feet of length per Hit Die of the elemental) and stop larger vessels (10 feet long per HD). Even large ships (20 feet long per HD) can be slowed to half speed.

### Drench


The elemental's touch puts out torches, campfires, exposed lanterns, and other open flames of nonmagical origin if these are of Large size or smaller. The creature can dispel magical fire it touches as dispel magic (caster level equals elemental's HD).

### Vortex


The elemental can transform itself into a whirlpool once every 10 minutes, provided it is underwater, and remain in that form for up to 1 round for every 2 HD it has. In vortex form, the elemental can move through the water or along the bottom at its swim speed. The vortex is 5 feet wide at the base, up to 30 feet wide at the top, and 10 feet or more tall, depending on the elemental's size. The elemental controls the exact height, but it must be at least 10 feet. The elemental's movement while in vortex form does not provoke attacks of opportunity, even if the elemental enters the space another creature occupies. Another creature might be caught in the vortex if it touches or enters the vortex, or if the elemental moves into or through the creature's space. Creatures one or more size categories smaller than the elemental might take damage when caught in the vortex (see the table below for details) and may be swept up by it. An affected creature must succeed on a Reflex save when it comes into contact with the vortex or take the indicated damage. It must also succeed on a second Reflex save or be picked up bodily and held suspended in the powerful currents, automatically taking damage each round. An affected creature is allowed a Reflex save each round to escape the vortex. The creature still takes damage, but can leave if the save is successful. The DC for saves against the vortex's effects varies with the elemental's size. The save DC is Strength-based. Creatures trapped in the vortex cannot move except to go where the elemental carries them or to escape the whirlwind. Creatures caught in the whirlwind can otherwise act normally, but must make a Concentration check (DC 10 + spell level) to cast a spell. Creatures caught in the whirlwind take a -4 penalty to Dexterity and a -2 penalty on attack rolls. The elemental can have only as many creatures trapped inside the vortex at one time as will fit inside the vortex's volume. The elemental can eject any carried creatures whenever it wishes, depositing them wherever the vortex happens to be. A summoned elemental always ejects trapped creatures before returning to its home plane. If the vortex's base touches the bottom, it creates a swirling cloud of debris. This cloud is centered on the elemental and has a diameter equal to half the vortex's height. The cloud obscures all vision, including darkvision, beyond 5 feet. Creatures 5 feet away have concealment, while those farther away have total concealment. Those caught in the cloud must make a Concentration check (DC 15 + spell level) to cast a spell. An elemental in vortex form cannot make slam attacks and does not threaten the area around it.

### Detect Magic


Ethereal filchers can detect magic as the spell (caster level 5th) at will.

### Superior Two-Weapon Fighting


An ettin fights with a morningstar or javelin in each hand. Because each of its two heads controls an arm, the ettin does not take a penalty on attack or damage rolls for attacking with two weapons.

### Hive Mind


All formians within 50 miles of their queen are in constant communication. If one is aware of a particular danger, they all are. If one in a group is not flatfooted, none of them are. No formian in a group is considered flanked unless all of them are.

### Cure Serious Wounds


Eight workers together can heal a creature's wounds as though using the cure serious wounds spell (caster level 7th). This is a full-round action for all eight workers.

### Make Whole


Three workers together can repair an object as though using the make whole spell (caster level 7th). This is a fullround action for all three workers.

### Dominate Monster

- **DEFINE:** DC_Dominate_Monster|0
- **BONUS:** VAR|DC_Dominate_Monster|DC_CHA
- **BONUS:** VAR|DC_Dominate_Monster|2
- **ABILITY:** Ability Focus|AUTOMATIC|Dominate Monster

A taskmaster can use a dominate monster ability as the spell from a 10th-level caster (Will DC %1 negates), although the subject may be of any kind and may be up to Large size. Creatures that successfully save cannot be affected by the same taskmaster's dominate monster ability for 24 hours. A single taskmaster can dominate up to four subjects at a time. The save DC is Charisma-based.|DC_Dominate_Monster

### Dominated Creature


A taskmaster is never encountered alone. One dominated nonformian creature always accompanies it (choose or determine randomly any creature of CR 4).

### Trill

- **DEFINE:** DC_Trill|0
- **BONUS:** VAR|DC_Trill|DC_CHA
- **BONUS:** VAR|DC_Trill|2
- **ABILITY:** Ability Focus|AUTOMATIC|Trill

A frost worm can emit a noise that forces its prey to stand motionless. This sonic mind-affecting compulsion affects all creatures other than frost worms within a 100-foot radius. Creatures must succeed on a DC 17 Will save or be stunned for as long as the worm trills and for 1d4 rounds thereafter, even if they are attacked. However, if attacked or violently shaken (a full-round action), a victim is allowed another saving throw. Once a creature has resisted or broken the effect, it cannot be affected again by that same frost worm's trill for 24 hours. The effect's caster level is 14th. The save DC is Charisma-based.|DC_Trill

### Cold


A frost worm's body generates intense cold, causing opponents to take an extra 1d8 points of cold damage every time the creature succeeds on a bite attack. Creatures attacking a frost worm unarmed or with natural weapons take this same cold damage each time one of their attacks hits.

### Shriek


Movement or a light source within 10 feet of a shrieker causes the fungus to emit a piercing sound that lasts for 1d3 rounds. The sound attracts nearby creatures that are disposed to investigate it. Some creatures that live near shriekers come to learn that the fungus's noise means there is food nearby.

### Freeze


A gargoyle can hold itself so still it appears to be a statue. An observer must succeed on a DC 20 Spot check to notice the gargoyle is really alive.

### Change Size

- **DEFINE:** DC_Change_Size|0
- **BONUS:** VAR|DC_Change_Size|DC_CHA
- **BONUS:** VAR|DC_Change_Size|2
- **ABILITY:** Ability Focus|AUTOMATIC|Change Size

Twice per day, an efreeti can magically change a creature's size. This works just like an enlarge person or reduce person spell (the efreeti chooses when using the ability), except that the ability can work on the efreeti. A DC %1 Fortitude save negates the effect. The save DC is Charisma-based. This is the equivalent of a 2nd-level spell.|DC_Change_Size

### Elemental Endurance


Jann can survive on the Elemental Planes of Air, Earth, Fire, or Water for up to 48 hours. Failure to return to the Material Plane before that time expires causes a janni to take 1 point of damage per additional hour spent on the elemental plane, until it dies or returns to the Material Plane.

### Gaze


In humanoid form-slay evil creatures of 5 or less HD, range 60 feet, Will DC 18 negates. Even if the save succeeds, the creature is affected as though by a fear spell for 2d10 rounds. Nonevil creatures, and evil creatures with more than 5 HD, must succeed on a DC 18 Will save or suffer the fear effect. The save DCs are Charisma-based.

### Corrupting Gaze


A ghost can blast living beings with a glance, at a range of up to 30 feet. Creatures that meet the ghost's gaze must succeed on a Fortitude save or take 2d10 points of damage and 1d4 points of Charisma damage.

### Corrupting Touch


A ghost that hits a living target with its incorporeal touch attack deals 1d6 points of damage. Against ethereal opponents, it adds its Strength modifier to attack and damage rolls. Against nonethereal opponents, it adds its Dexterity modifier to attack rolls only.

### Draining Touch


A ghost that hits a living target with its incorporeal touch attack drains 1d4 points from any one ability score it selects. On each such successful attack, the ghost heals 5 points of damage to itself. Against ethereal opponents, it adds its Strength modifier to attack rolls only. Against nonethereal opponents, it adds its Dexterity modifier to attack rolls only.

### Frightful Moan


A ghost can emit a frightful moan as a standard action. All living creatures within a 30-foot spread must succeed on a Will save or become panicked for 2d4 rounds. This is a sonic necromantic mind-affecting fear effect. A creature that successfully saves against the moan cannot be affected by the same ghost's moan for 24 hours.

### Horrific Appearance


Any living creature within 60 feet that views a ghost must succeed on a Fortitude save or immediately take 1d4 points of Strength damage, 1d4 points of Dexterity damage, and 1d4 points of Constitution damage. A creature that successfully saves against this effect cannot be affected by the same ghost's horrific appearance for 24 hours.

### Malevolence


Once per round, an ethereal ghost can merge its body with a creature on the Material Plane. This ability is similar to a magic jar spell (caster level 10th or the ghost's Hit Dice, whichever is higher), except that it does not require a receptacle. to use this ability, the ghost must be manifested and it must try move into the target's space; moving into the target's space to use the malevolence ability does not provoke attacks of opportunity. The target can resist the attack with a successful Will save (DC 15 + ghost's Cha modifier). A creature that successfully saves is immune to that same ghost's malevolence for 24 hours, and the ghost cannot enter the target's space. If the save fails, the ghost vanishes into the target's body.

### Manifestation


Every ghost has this ability. A ghost dwells on the Ethereal Plane and, as an ethereal creature, it cannot affect or be affected by anything in the material world. When a ghost manifests, it partly enters the Material Plane and becomes visible but incorporeal on the Material Plane. A manifested ghost can be harmed only by other incorporeal creatures, magic weapons, or spells, with a 50%% chance to ignore any damage from a corporeal source. A manifested ghost can pass through solid objects at will, and its own attacks pass through armor. A manifested ghost always moves silently. A manifested ghost can strike with its touch attack or with a ghost touch weapon (see Ghostly Equipment, below). A manifested ghost remains partially on the Ethereal Plane, where is it not incorporeal. A manifested ghost can be attacked by opponents on either the Material Plane or the Ethereal Plane. The ghost's incorporeality helps protect it from foes on the Material Plane, but not from foes on the Ethereal Plane. When a spellcasting ghost is not manifested and is on the Ethereal Plane, its spells cannot affect targets on the Material Plane, but they work normally against ethereal targets. When a spellcasting ghost manifests, its spells continue to affect ethereal targets and can affect targets on the Material Plane normally unless the spells rely on touch. A manifested ghost's touch spells don't work on nonethereal targets. A ghost has two home planes, the Material Plane and the Ethereal Plane. It is not considered extraplanar when on either of these planes.

### Telekinesis


A ghost can use telekinesis as a standard action (caster level 12th or equal to the ghost's HD, whichever is higher). When a ghost uses this power, it must wait 1d4 rounds before using it again.

### Special Qualities


A ghost has all the special qualities of the base creature as well as those described below.

### Rejuvenation


In most cases, it's difficult to destroy a ghost through simple combat: The "destroyed" spirit will often restore itself in 2d4 days. Even the most powerful spells are usually only temporary solutions. A ghost that would otherwise be destroyed returns to its old haunts with a successful level check (1d20 + ghost's HD) against DC 16. As a rule, the only way to get rid of a ghost for sure is to determine the reason for its existence and set right whatever prevents it from resting in peace. The exact means varies with each spirit and may require a good deal of research.

### Turn Resistance


A ghost has +4 turn resistance.

### Ghoul Fever

- **DEFINE:** DC_Disease|0
- **BONUS:** VAR|DC_Disease|DC_CHA
- **BONUS:** VAR|DC_Disease|2
- **ABILITY:** Ability Focus|AUTOMATIC|Disease

Disease-bite, Fortitude DC %1, incubation period 1 day, damage 1d3 Con and 1d3 Dex. The save DC is Charisma-based. An afflicted humanoid who dies of ghoul fever rises as a ghoul at the next midnight. A humanoid who becomes a ghoul in this way retains none of the abilities it possessed in life. It is not under the control of any other ghouls, but it hungers for the flesh of the living and behaves like a normal ghoul in all respects. A humanoid of 4 Hit Dice or more rises as a ghast, not a ghoul.|DC_Disease

### Rock Throwing


Adult giants are accomplished rock throwers and receive a +1 racial bonus on attack rolls when throwing rocks. A giant of at least Large size can hurl rocks weighing 40 to 50 pounds each (Small objects) up to five range increments. The size of the range increment varies with the giant's variety. A Huge giant can hurl rocks of 60 to 80 pounds (Medium objects).

### Rock Catching


A giant of at least Large size can catch Small, Medium, or Large rocks (or projectiles of similar shape). Once per round, a giant that would normally be hit by a rock can make a Reflex save to catch it as a free action. The DC is 15 for a Small rock, 20 for a Medium one, and 25 for a Large one. (If the projectile provides a magical bonus on attack rolls, the DC increases by that amount.) The giant must be ready for and aware of the attack in order to make a rock catching attempt.

### Oversized Weapon


A cloud giant wields a great, two-handed morningstar (big enough for Gargantuan creatures) without penalty.

### Freedom of Movement


Storm giants have a continuous freedom of movement ability as the spell (caster level 20th). The effect can be dispelled, but the storm giant can create it again on its next turn as a free action.

### Race Traits ~ Githyanki

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=GithyankiRaceAbility

### Red Dragon Pact

- **BONUS:** SKILL|Diplomacy (Red Dragons)|4

Githyanki have a racial pact with red dragons, which sometimes serve githyanki as mounts. Individually, githyanki have a +4 racial bonus on Diplomacy checks when dealing with red dragons. In large groups, they can make temporary alliances with red dragons at the option of the Dungeon Master.

### Githyanki Race Traits


- +2 Dexterity, +2 Constitution, -2 Wisdom. -Medium size. -A githyanki's base land speed is 30 feet. -Darkvision out to 60 feet. -Racial Feats: A githyanki character gains feats according to its character class. -Special Attacks (see above): Psionics. -Special Qualities (see above): Psionics, spell resistance equal to class levels +5. -Automatic Languages: Githyanki. Bonus Languages: Common, Infernal, Draconic, Undercommon. -Favored Class: Fighter. -Level adjustment +2.

### Race Traits ~ Githzerai

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=GithzeraiRaceAbility

### Inertial Armor

- **BONUS:** COMBAT|AC|4|TYPE=Armor

Githzerai can use psychic force to block an enemy's blows. This ability gives them a +4 armor bonus to AC as long as they remain conscious. This is the equivalent of a 1stlevel spell.

### Gibbering

- **DEFINE:** DC_Gibbering|0
- **BONUS:** VAR|DC_Gibbering|DC_CHA
- **BONUS:** VAR|DC_Gibbering|2
- **ABILITY:** Ability Focus|AUTOMATIC|Gibbering

As soon as a mouther spots something edible, it begins a constant gibbering as a free action. All creatures (other than mouthers) within a 60-foot spread must succeed on a DC %1 Will save or be affected as though by a confusion spell for 1d2 rounds. This is a sonic mind-affecting compulsion effect. A creature that successfully saves cannot be affected by the same gibbering mouther's gibbering for 24 hours. The save DC is Charisma-based.|DC_Gibbering

### Spittle

- **DEFINE:** DC_Spittle|0
- **BONUS:** VAR|DC_Spittle|DC_CON
- **BONUS:** VAR|DC_Spittle|2
- **ABILITY:** Ability Focus|AUTOMATIC|Spittle

As a free action every round, a gibbering mouther fires a stream of spittle at one opponent within 30 feet. The mouther makes a ranged touch attack; if it hits, it deals 1d4 points of acid damage, and the target must succeed on a DC %1 Fortitude save or be blinded for 1d4 rounds. Eyeless creatures are immune to the blinding effect, but are still subject to the acid damage. The save DC is Constitution-based.|DC_Spittle

### Ground Manipulation


At will, as a standard action, a gibbering mouther can cause stone and earth in all adjacent squares to become a morass akin to quicksand. Softening earth, sand, or the like takes 1 round, while stone takes 2 rounds. Anyone other than the mouther in that area must take a move-equivalent action to avoid becoming mired (treat as being pinned).

### Amorphous


A gibbering mouther is not subject to critical hits. It cannot be flanked.

### Race Traits ~ Gnoll


### Immunity to Magic


Golems have immunity to most magical and supernatural effects, except when otherwise noted.

### Berserk


When a clay golem enters combat, there is a cumulative 1%% chance each round that its elemental spirit breaks free and the golem goes berserk. The uncontrolled golem goes on a rampage, attacking the nearest living creature or smashing some object smaller than itself if no creature is within reach, then moving on to spread more destruction. Once a clay golem goes berserk, no known method can reestablish control.

### Cursed Wound


The damage a clay golem deals doesn't heal naturally and resists healing spells. A character attempting to cast a conjuration (healing) spell on a creature damaged by a clay golem must succeed on a DC 26 caster level check, or the spell has no effect on the injured character.

### Haste


After it has engaged in at least 1 round of combat, a clay golem can haste itself once per day as a free action. The effect lasts 3 rounds and is otherwise the same as the spell.

### Weakness

- **DEFINE:** DC_Weakness|0
- **BONUS:** VAR|DC_Weakness|DC_CHA
- **BONUS:** VAR|DC_Weakness|2
- **ABILITY:** Ability Focus|AUTOMATIC|Weakness

A green hag can weaken a foe by making a special touch attack. The opponent must succeed on a DC %1 Fortitude save or take 2d4 points of Strength damage. The save DC is Charisma-based.|DC_Weakness

### Mimicry


A green hag can imitate the sounds of almost any animal found near its lair.

### Evil Eye

- **DEFINE:** DC_Evil_Eye|0
- **BONUS:** VAR|DC_Evil_Eye|DC_CHA
- **BONUS:** VAR|DC_Evil_Eye|2
- **ABILITY:** Ability Focus|AUTOMATIC|Evil Eye

Three times per day, a sea hag can cast its dire gaze upon any single creature within 30 feet. The target must succeed on a DC %1 Will save or be dazed for three days, although remove curse or dispel evil can restore sanity sooner. In addition, an affected creature must succeed on a DC %1 Fortitude save or die from fright. Creatures with immunity to fear effects are not affected by the sea hag's evil eye. The save DCs are Charisma-based.|DC_Evil_Eye

### Wings

- **TEMPLATE:** Half-Celestial Wings

A half-celestial has feathered wings and can fly at twice the base creature's base land speed (good maneuverability). If the base creature has a fly speed, use that instead.

### Daylight


Half-celestials can use a daylight effect (as the spell) at will.

### Smite Evil


Once per day a half-celestial can make a normal melee attack to deal extra damage equal to its HD (maximum of +20) against an evil foe.

### Poison Resistance


+4 racial bonus on Fortitude saves against poison.

### Speed


A half-dragon that is Large or larger has wings and can fly at twice its base land speed (maximum 120 ft.) with average maneuverability. A half-dragon that is Medium or smaller does not have wings.

### Smite Good


Once per day the creature can make a normal melee attack to deal extra damage equal to its HD (maximum of +20) against a good foe.

### Captivating Song

- **DEFINE:** DC_Captivating_Song|0
- **BONUS:** VAR|DC_Captivating_Song|DC_CHA
- **BONUS:** VAR|DC_Captivating_Song|2
- **ABILITY:** Ability Focus|AUTOMATIC|Captivating Song

The most insidious ability of the harpy is its song. When a harpy sings, all creatures (other than harpies) within a 300-foot spread must succeed on a DC %1 Will save or become captivated. This is a sonic mind-affecting charm effect. A creature that successfully saves cannot be affected again by the same harpy's song for 24 hours. The save DC is Charisma-based. A captivated victim walks toward the harpy, taking the most direct route available. If the path leads into a dangerous area (through flame, off a cliff, or the like), that creature gets a second saving throw. Captivated creatures can take no actions other than to defend themselves. (Thus, a fighter cannot run away or attack but takes no defensive penalties.) A victim within 5 feet of the harpy stands there and offers no resistance to the monster's attacks. The effect continues for as long as the harpy sings and for 1 round thereafter. A bard's countersong ability allows the captivated creature to attempt a new Will save.|DC_Captivating_Song

### Fiery Bite


A hell hound deals an extra 1d6 points of fire damage every time it bites an opponent, as if its bite were a flaming weapon.

### Quills

- **DEFINE:** DC_Quills|0
- **BONUS:** VAR|DC_Quills|DC_DEX
- **BONUS:** VAR|DC_Quills|2
- **ABILITY:** Ability Focus|AUTOMATIC|Quills

A howler's neck bristles with long quills. While biting, the creature thrashes about, striking with 1d4 of them. An opponent hit by a howler's quill attack must succeed on a DC %1 Reflex save or have the quill break off in his or her flesh. Lodged quills impose a -1 penalty on attacks, saves, and checks per quill. The save DC is Dexterity-based. A quill can be removed safely with a DC 20 Heal check; otherwise, removing a quill deals an extra 1d6 points of damage.|DC_Quills

### Howl

- **DEFINE:** DC_Howl|0
- **BONUS:** VAR|DC_Howl|DC_CHA
- **BONUS:** VAR|DC_Howl|2
- **ABILITY:** Ability Focus|AUTOMATIC|Howl

All beings other than outsiders that hear the creature's howling for an hour or longer are subject to its effect, though it does not help the howler in combat. Anyone within hearing range of a howler for a full hour must succeed on a DC %1 Will save or take 1 point of Wisdom damage. The save DC is Charisma-based. The save must be repeated for each hour of exposure. This is a sonic mind-affecting effect.|DC_Howl

### Five

- **TEMPLATE:** Hydra ~ Five Headed
- **BONUS:** VAR|HydraHeadCount|5
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*5,1d10

### Six

- **TEMPLATE:** Hydra ~ Six Headed
- **BONUS:** VAR|HydraHeadCount|6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*6,1d10

### Seven

- **TEMPLATE:** Hydra ~ Seven Headed
- **BONUS:** STAT|STR|2|TYPE=Racial
- **BONUS:** VAR|HydraHeadCount|7
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*7,1d10

### Eight

- **TEMPLATE:** Hydra ~ Eight Headed
- **BONUS:** STAT|STR|2|TYPE=Racial
- **BONUS:** VAR|HydraHeadCount|8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*8,1d10

### Nine

- **TEMPLATE:** Hydra ~ Nine Headed
- **BONUS:** STAT|STR|4|TYPE=Racial
- **BONUS:** VAR|HydraHeadCount|9
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*9,1d10

### Ten

- **TEMPLATE:** Hydra ~ Ten Headed
- **BONUS:** STAT|STR|4|TYPE=Racial
- **BONUS:** VAR|HydraHeadCount|10
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*10,1d10

### Eleven

- **TEMPLATE:** Hydra ~ Eleven Headed
- **BONUS:** STAT|STR|6|TYPE=Racial
- **BONUS:** VAR|HydraHeadCount|11
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*11,1d10

### Twelve

- **TEMPLATE:** Hydra ~ Twelve Headed
- **BONUS:** STAT|STR|6|TYPE=Racial
- **BONUS:** VAR|HydraHeadCount|12
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*12,1d10

### Enervation Ray


A kolyarut can fire a black enervation ray at targets within 200 feet. The effect is identical with the enervation spell (caster level 13th).

### Vampiric Touch


As a melee touch attack, a kolyarut can steal life force from its foe, as the vampiric touch spell (caster level 13th).

### Fists of Thunder and Lightning

- **DEFINE:** DC_Fists_of_Thunder_and_Lightning|0
- **BONUS:** VAR|DC_Fists_of_Thunder_and_Lightning|DC_STR
- **BONUS:** VAR|DC_Fists_of_Thunder_and_Lightning|2
- **ABILITY:** Ability Focus|AUTOMATIC|Fists of Thunder and Lightning

A marut's left fist delivers a loud thunderclap whenever it hits something, dealing an extra 3d6 points of sonic damage and causing the target to be deafened for 2d6 rounds (Fortitude DC %1 negates the deafness). Its right fist delivers a shock for an extra 3d6 points of electricity damage, and the flash of lightning causes the target to be blinded for 2d6 rounds (Fortitude DC %1 negates the blindness). The save DCs are Strength-based and include the marut's Ability Focus feat.|DC_Fists_of_Thunder_and_Lightning

### Natural Invisibility


This ability is constant, allowing a stalker to remain invisible even when attacking. This ability is inherent and not subject to the invisibility purge spell.

### Improved Tracking


An invisible stalker is a consummate tracker and makes Spot checks instead of the usual Survival checks to trace a creature's passage.

### Jet


A kraken can jet backward once per round as a full-round action, at a speed of 280 feet. It must move in a straight line, but does not provoke attacks of opportunity while jetting.

### Ink Cloud


A kraken can emit a cloud of jet-black ink in an 80-foot spread once per minute as a free action. The cloud provides total concealment, which the kraken normally uses to escape a fight that is going badly. Creatures within the cloud are considered to be in darkness.

### Scare

- **DEFINE:** DC_Scare|0
- **BONUS:** VAR|DC_Scare|DC_CHA
- **BONUS:** VAR|DC_Scare|2
- **ABILITY:** Ability Focus|AUTOMATIC|Scare

As a standard action, a krenshar can pull the skin back from its head, revealing the musculature and bony structures of its skull. This alone is usually sufficient to scare away foes (treat as a Bluff check with a +3 bonus). Combining this scare ability with a loud screech produces an unsettling effect that works like a scare spell from a 3rd-level caster (Will DC %1 partial). A creature that successfully saves cannot be affected again by the same krenshar's scare ability for 24 hours. The shriek does not affect other krenshars. This is a supernatural, sonic mind-affecting fear effect. The save DC is Charisma-based.|DC_Scare

### Race Traits ~ Kuo-Toa

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=KuoToaRaceAbility

### Lightning Bolt


Two or more kuo-toa clerics (known as whips) operating together can generate a stroke of lightning every 1d4 rounds. The whips must join hands to launch the bolt but need merely be within 30 feet of one another while it builds. The lightning bolt deals 1d6 points of electricity damage per whip, but a successful Reflex save (DC 13 + number of whips) halves this amount.

### Pincer Staff


Many kuo-toa fighters and all whips of 7th level or higher carry this Large exotic weapon. A pincer staff deals 1d10 points of bludgeoning damage, threatens a critical hit on a natural 20, and deals double damage on a critical hit. It has a 10-foot reach and cannot be used against an adjacent opponent. A wielder that hits an opponent of at least Small but no larger than Large size can attempt to start a grapple as a free action without provoking an attack of opportunity. If the wielder wins the grapple check, the staff establishes a hold and grabs the opponent, dealing 1d10 points of damage each round the hold is maintained.

### Adhesive


Kuo-toas use their own body oil and other materials to give their shields a finish almost like flypaper, holding fast any creatures or items touching them. Anyone who makes an unsuccessful melee attack against a kuo-toa must succeed on a DC 14 Reflex save, or the attacker's weapon sticks to the shield and is yanked out of the wielder's grasp. Creatures using natural weapons are automatically grappled if they get stuck. A kuo-toa requires 1 hour and special materials costing 20 gp to coat a shield with adhesive. The adhesive remains good for up to three days or until it actually catches someone or something (in which case the shield can trap no additional items, since the adhesive is used up). Pulling a stuck weapon or limb from a shield requires a DC 20 Strength check.

### Keen Sight


Kuo-toas have excellent vision thanks to their two independently focusing eyes. Their eyesight is so keen that they can spot a moving object or creature even if it is invisible or ethereal. Only by remaining perfectly still can such objects or creatures avoid their notice.

### Slippery


All kuo-toas secrete an oily film that makes them difficult to grapple or snare. Webs, magical or otherwise, don't affect kuo-toas, and they usually can wriggle free from most other forms of confinement.

### Special Attacks


A lich retains all the base creature's special attacks and gains those described below. Save DCs are equal to 10 + 1/2 lich's HD + lich's Cha modifier unless otherwise noted.

### Paralyzing Touch


Any living creature a lich hits with its touch attack must succeed on a Fortitude save or be permanently paralyzed. Remove paralysis or any spell that can remove a curse can free the victim (see the bestow curse spell description). The effect cannot be dispelled. Anyone paralyzed by a lich seems dead, though a DC 20 Spot check or a DC 15 Heal check reveals that the victim is still alive..

### Damage Reduction


A lich's undead body is tough, giving the creature damage reduction 15/bludgeoning and magic. Its natural weapons are treated as magic weapons for the purpose of overcoming damage reduction.

### Abilities


Increase from the base creature as follows: Int +2, Wis +2, Cha +2. Being undead, a lich has no Constitution score.

### Race Traits ~ Lizardfolk

- **BONUS:** ABILITYPOOL|Lizardfolk Subrace|1
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Club|Javelin|TYPE=Simple

### Lizardfolk

- **BONUS:** STAT|STR,CON|2|TYPE=Racial
- **BONUS:** STAT|INT|-2|TYPE=Racial
- **ABILITY:** Special Ability|AUTOMATIC|Lizardfolk ~ Hold Breath
- **ABILITY:** Special Ability|AUTOMATIC|Lizardfolk ~ Skills
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4

### Hold Breath


A lizardfolk can hold its breath for a number of rounds equal to four times its Constitution score before it risks drowning.

### Bear Empathy


Communicate with bears and dire bears, and +4 racial bonus on Charisma-based checks against bears and dire bears.

### Curse of Lycanthropy

- **DEFINE:** DC_Curse_of_Lycanthropy|0
- **BONUS:** VAR|DC_Curse_of_Lycanthropy|15
- **BONUS:** VAR|DC_Curse_of_Lycanthropy|2
- **ABILITY:** Ability Focus|AUTOMATIC|Curse of Lycanthropy

Any humanoid or giant hit by a werebear's bite attack in animal or hybrid form must succeed on a DC %1 Fortitude save or contract lycanthropy.|DC_Curse_of_Lycanthropy

### Boar Empathy


Communicate with boars and dire boars, and +4 racial bonus on Charisma-based checks against boars and dire boars.

### Rat Empathy


Communicate with rats and dire rats, and +4 racial bonus on Charisma-based checks against rats and dire rats.

### Alternate Form (Su)


A weretiger can assume a bipedal hybrid form or the form of a tiger.

### Curse of Lycanthropy (Su)

- **DEFINE:** DC_Curse_of_Lycanthropy|0
- **BONUS:** VAR|DC_Curse_of_Lycanthropy|15
- **BONUS:** VAR|DC_Curse_of_Lycanthropy|2
- **ABILITY:** Ability Focus|AUTOMATIC|Curse of Lycanthropy

Any humanoid or giant hit by a weretiger's bite attack in animal or hybrid form must succeed on a DC %1 Fortitude save or contract lycanthropy.|DC_Curse_of_Lycanthropy

### Improved Grab (Ex)


To use this ability, a weretiger in tiger form must hit with a claw or bite attack. It can then attempt to start a grapple as a free action without provoking an attack of opportunity. If it wins the grapple check, it establishes a hold and can rake.

### Pounce (Ex)


If a weretiger in tiger form charges an opponent, it can make a full attack, including two rake attacks.

### Tiger Empathy


Communicate with tigers and dire tigers, and +4 racial bonus on Charisma-based checks against tigers and dire tigers.

### Wolf Empathy


Communicate with wolves and dire wolves, and +4 racial bonus on Charisma-based checks against wolves and dire wolves.

### Combustion

- **DEFINE:** DC_Combustion|0
- **BONUS:** VAR|DC_Combustion|DC_CON
- **BONUS:** VAR|DC_Combustion|2
- **ABILITY:** Ability Focus|AUTOMATIC|Combustion

Anyone a magmin touches must succeed on a DC %1 Reflex save or take an extra 1d8 points of fire damage as clothes ignite or armor becomes searing hot. The damage continues for another 1d4+2 rounds after the magmin's last successful attack. Magmins can also ignite flammable materials with a touch. The save DC is Constitution-based.|DC_Combustion

### Fiery Aura

- **DEFINE:** DC_Fiery_Aura|0
- **BONUS:** VAR|DC_Fiery_Aura|DC_CON
- **BONUS:** VAR|DC_Fiery_Aura|2
- **ABILITY:** Ability Focus|AUTOMATIC|Fiery Aura

Anyone within 20 feet of a magmin must succeed on a DC %1 Fortitude save or take 1d6 points of heat damage per round from the intense heat. The save DC is Constitution-based.|DC_Fiery_Aura

### Melt Weapons

- **DEFINE:** DC_Melt_Weapons|0
- **BONUS:** VAR|DC_Melt_Weapons|DC_CON
- **BONUS:** VAR|DC_Melt_Weapons|2
- **ABILITY:** Ability Focus|AUTOMATIC|Melt Weapons

Any metal weapon that strikes a magmin must succeed on a DC %1 Fortitude save or melt away into slag. The save DC is Constitution-based.|DC_Melt_Weapons

### Spikes


With a snap of its tail, a manticore can loose a volley of six spikes as a standard action (make an attack roll for each spike). This attack has a range of 180 feet with no range increment. All targets must be within 30 feet of each other. The creature can launch only twenty-four spikes in any 24-hour period.

### Summon Mephit


Once per day, a mephit can attempt to summon another mephit of the same variety, much as though casting a summon monster spell, but with only a 25%% chance of success. Roll d%%: On a failure, no creature answers the summons that day. A mephit that has just been summoned cannot use its own summon ability for 1 hour. This ability is the equivalent of a 2nd-level spell.

### Crush


A mimic deals 1d8+4 points of damage with a successful grapple check.

### Mimic Shape


A mimic can assume the general shape of any object that fills roughly 150 cubic feet (5 feet by 5 feet by 6 feet), such as a massive chest, a stout bed, or a wide door frame. The creature cannot substantially alter its size, though. A mimic's body is hard and has a rough texture, no matter what appearance it might present. Anyone who examines the mimic can detect the ruse with a successful Spot check opposed by the mimic's Disguise check. Of course, by this time it is generally far too late.

### Race Traits ~ Mind Flayer

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=MindFlayerRaceAbility

### Mind Blast

- **DEFINE:** DC_Mind_Blast|0
- **BONUS:** VAR|DC_Mind_Blast|DC_CHA
- **BONUS:** VAR|DC_Mind_Blast|2
- **ABILITY:** Ability Focus|AUTOMATIC|Mind Blast

This psionic attack is a cone 60 feet long. Anyone caught in this cone must succeed on a DC %1 Will save or be stunned for 3d4 rounds. Mind flayers often hunt using this power and then drag off one or two of their stunned victims to feed upon. The save DC is Charisma-based. This ability is the equivalent of a 4th level spell.|DC_Mind_Blast

### Extract


A mind flayer that begins its turn with all four tentacles attached and that makes a successful grapple check automatically extracts the opponent's brain, instantly killing that creature. This power is useless against constructs, elementals, oozes, plants, and undead. It is not instantly fatal to foes with multiple heads, such as ettins and hydras.

### Natural Cunning


Although minotaurs are not especially intelligent, they possess innate cunning and logical ability. This gives them immunity to maze spells, prevents them from ever becoming lost, and enables them to track enemies. Further, they are never caught flat-footed.

### Create Spawn


Creatures killed by a mohrg rise after 1d4 days as zombies under the morhg's control. They do not possess any of the abilities they had in life.

### Despair

- **DEFINE:** DC_Despair|0
- **BONUS:** VAR|DC_Despair|DC_CHA
- **BONUS:** VAR|DC_Despair|2
- **ABILITY:** Ability Focus|AUTOMATIC|Despair

At the mere sight of a mummy, the viewer must succeed on a DC %1 Will save or be paralyzed with fear for 1d4 rounds. Whether or not the save is successful, that creature cannot be affected again by the same mummy's despair ability for 24 hours. The save DC is Charisma-based.|DC_Despair

### Mummy Rot

- **DEFINE:** DC_Mummy_Rot|0
- **BONUS:** VAR|DC_Mummy_Rot|DC_CHA
- **BONUS:** VAR|DC_Mummy_Rot|2
- **ABILITY:** Ability Focus|AUTOMATIC|Mummy Rot

Supernatural disease-slam, Fortitude DC %1, incubation period 1 minute; damage 1d6 Con and 1d6 Cha. The save DC is Charisma-based. Unlike normal diseases, mummy rot continues until the victim reaches Constitution 0 (and dies) or is cured as described below. Mummy rot is a powerful curse, not a natural disease. A character attempting to cast any conjuration (healing) spell on a creature afflicted with mummy rot must succeed on a DC 20 caster level check, or the spell has no effect on the afflicted character. to eliminate mummy rot, the curse must first be broken with break enchantment or remove curse (requiring a DC 20 caster level check for either spell), after which a caster level check is no longer necessary to cast healing spells on the victim, and the mummy rot can be magically cured as any normal disease. An afflicted creature who dies of mummy rot shrivels away into sand and dust that blow away into nothing at the first wind.|DC_Mummy_Rot

### Resistance to Charm


Dark nagas have a +2 racial bonus on saving throws against all charm effects (not included in the statistics block).

### Guarded Thoughts


Dark nagas are immune to any form of mind reading.

### Spit


A guardian naga can spit its venom up to 30 feet as a standard action. This is a ranged touch attack with no range increment. Opponents hit by this attack must make successful saves (see above) to avoid the effect.

### Charming Gaze

- **DEFINE:** DC_Charming_Gaze|0
- **BONUS:** VAR|DC_Charming_Gaze|DC_CHA
- **BONUS:** VAR|DC_Charming_Gaze|2
- **ABILITY:** Ability Focus|AUTOMATIC|Charming Gaze

As charm person, 30 feet, Will DC %1 negates. The save DC is Charisma-based.|DC_Charming_Gaze

### Dream Haunting


Night hags can visit the dreams of chaotic or evil individuals by using a special periapt known as a heartstone to become ethereal, then hovering over the creature. Once a hag invades someone's dreams, it rides on the victim's back until dawn. The sleeper suffers from tormenting dreams and takes 1 point of Constitution drain upon awakening. Only another ethereal being can stop these nocturnal intrusions, by confronting and defeating the night hag.

### Flaming Hooves


A blow from a nightmare's hooves sets combustible materials alight.

### Smoke


During the excitement of battle, a nightmare snorts and neighs with rage. This snorting fills a 15-foot cone with a hot, sulfurous smoke that chokes and blinds opponents. Anyone in the cone must succeed on a DC 16 Fortitude save or take a -2 penalty on all attack and damage rolls until 1d6 minutes after leaving the cone. The cone lasts 1 round, and the nightmare uses it once as a free action during its turn each round. The save DC is Constitution-based. Because of the smoke it gives off, a nightmare has concealment against creatures 5 feet away and total concealment against creatures 10 feet or farther away. The smoke does not obscure the nightmare's vision at all.

### Astral Projection and Etherealness


These abilities function just like the spells of the same names (caster level 20th); a nightmare can use either at will.

### Aversion to Daylight


If exposed to natural daylight (not merely a daylight spell), nightshades take a -4 penalty on all attack rolls, saving throws, and skill checks.

### Desecrating Aura


All nightshades give off a 20-footradius emanation of utter desecration, imbuing their surroundings with negative energy. This ability works much like a desecrate spell, except that the nightshade's evil is so great that it is treated as the shrine of an evil power. All undead within 20 feet of the nightshade (including the creature itself ) gain a +2 profane bonus on attack rolls, damage rolls, and saving throws, and +2 hit points per HD. (The nightshade Hit Dice, attack, and save entries given here include these profane bonuses.) Charisma checks made to turn undead within this area take a -6 penalty. A nightshade's desecrating aura cannot be dispelled except by a dispel evil spell or similar effect. If the effect is dispelled, the nightshade can resume it as a free action on its next turn. Its desecrating aura is suppressed if a nightshade enters a consecrated or hallowed area, but the nightshade's presence also suppresses the consecrated or hallowed effect for as long as it remains in the area.

### Summon Undead


A nightcrawler can summon undead creatures once per night: 9-16 shadows, 3-6 greater shadows, or 2-4 dread wraiths. The undead arrive in 1d10 rounds and serve for 1 hour or until released.

### Crush Item

- **DEFINE:** DC_Crush_Item|0
- **BONUS:** VAR|DC_Crush_Item|DC_STR
- **BONUS:** VAR|DC_Crush_Item|2
- **ABILITY:** Ability Focus|AUTOMATIC|Crush Item

A nightwalker can destroy any weapon or item of Large size or smaller (even magic ones, but not artifacts) by picking it up and crushing it between its hands. The nightwalker must make a successful disarm attempt to grab an item held by an opponent. The item is entitled to a DC %1 Fortitude save to resist destruction. The save DC is Strength-based.|DC_Crush_Item

### Evil Gaze

- **DEFINE:** DC_Evil_Gaze|0
- **BONUS:** VAR|DC_Evil_Gaze|DC_CHA
- **BONUS:** VAR|DC_Evil_Gaze|2
- **ABILITY:** Ability Focus|AUTOMATIC|Evil Gaze

Fear, 30 feet. A creature that meets the nightwalker's gaze must succeed on a DC %1 Will save or be paralyzed with fear for 1d8 rounds. Whether or not the save is successful, that creature cannot be affected again by the same nightshade's gaze for 24 hours. This is a mind-affecting fear effect. The save DC is Charisma-based.|DC_Evil_Gaze

### Magic Drain

- **DEFINE:** DC_Magic_Drain|0
- **BONUS:** VAR|DC_Magic_Drain|DC_CHA
- **BONUS:** VAR|DC_Magic_Drain|2
- **ABILITY:** Ability Focus|AUTOMATIC|Magic Drain

A nightwing can weaken magic armor, weapons, and shields by making a successful touch attack. The targeted item must succeed on a DC %1 Fortitude save or lose 1 point of its enhancement bonus. The save DC is Charisma-based. An item that loses its entire enhancement bonus becomes merely a masterwork item and loses any special abilities (such as flaming) as well. Casting dispel evil upon the item reverses the effect of the magic drain, provided this occurs within a number of days after the attack equal to the caster's level and the caster succeeds on a DC 29 caster level check.|DC_Magic_Drain

### Blinding Beauty

- **DEFINE:** DC_Blinding_Beauty|0
- **BONUS:** VAR|DC_Blinding_Beauty|DC_CHA
- **BONUS:** VAR|DC_Blinding_Beauty|2
- **ABILITY:** Ability Focus|AUTOMATIC|Blinding Beauty

This ability affects all humanoids within 30 feet of a nymph. Those who look directly at a nymph must succeed on a DC %1 Fortitude save or be blinded permanently as though by the blindness spell. A nymph can suppress or resume this ability as a free action. The save DC is Charisma-based.|DC_Blinding_Beauty

### Stunning Glance

- **DEFINE:** DC_Stunning_Glance|0
- **BONUS:** VAR|DC_Stunning_Glance|DC_CHA
- **BONUS:** VAR|DC_Stunning_Glance|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stunning Glance

As a standard action, a wrathful nymph can stun a creature within 30 feet with a look. The target creature must succeed on a DC %1 Fortitude save or be stunned for 2d4 rounds. The save DC is Charisma-based.|DC_Stunning_Glance

### Unearthly Grace


A nymph adds her Charisma modifier as a bonus on all her saving throws, and as a deflection bonus to her Armor Class. (The statistics block already reflects these bonuses).

### Acid

- **DEFINE:** DC_Acid|0
- **BONUS:** VAR|DC_Acid|DC_CON
- **BONUS:** VAR|DC_Acid|2
- **ABILITY:** Ability Focus|AUTOMATIC|Acid

The creature secretes a digestive acid that dissolves organic material and metal quickly, but does not affect stone. Any melee hit or constrict attack deals acid damage, and the opponent's armor and clothing dissolve and become useless immediately unless they succeed on DC %1 Reflex saves. A metal or wooden weapon that strikes a black pudding also dissolves immediately unless it succeeds on a DC %1 Reflex save. The save DCs are Constitution-based. The pudding's acidic touch deals 21 points of damage per round to wooden or metal objects, but the ooze must remain in contact with the object for 1 full round to deal this damage.|DC_Acid

### Split


Slashing and piercing weapons deal no damage to a black pudding. Instead the creature splits into two identical puddings, each with half of the original's current hit points (round down). A pudding with 10 hit points or less cannot be further split and dies if reduced to 0 hit points.

### Transparent


Gelatinous cubes are hard to see, even under ideal conditions, and it takes a DC 15 Spot check to notice one. Creatures who fail to notice a cube and walk into it are automatically engulfed.

### Greater Invisibility


This ability is constant, allowing a phantom fungus to remain invisible even when attacking. It works like greater invisibility (caster level 12th) and lasts as long as the phantom fungus is alive. This ability is not subject to the invisibility purge spell. A phantom fungus becomes visible 1 minute after it is killed.

### Resilient


A phasm has a +4 racial bonus on Fortitude and Reflex saves (included in the statistics block).

### Tremorsense


A phasm can automatically sense the location of anything within 60 feet that is in contact with the ground, so long as it is touching the ground itself.

### Paralyzing Gaze

- **DEFINE:** DC_Paralysis|0
- **BONUS:** VAR|DC_Paralysis|DC_CON
- **BONUS:** VAR|DC_Paralysis|2
- **ABILITY:** Ability Focus|AUTOMATIC|Paralysis

Paralysis for 1d6 rounds, 30 feet, Fortitude DC %1 negates. The save DC is Charisma-based.|DC_Paralysis

### Positive Energy Lash


A ravid can make a touch attack or hit with a claw or tail slap attack to infuse a target with positive energy. The energy produces an unpleasant tingle in living creatures, and against undead foes (even incorporeal ones) it deals 2d10 points of damage.

### Animate Objects


Once per round, a random object within 20 feet of a ravid animates as though by the spell animate objects (caster level 20th). These objects defend the ravid to the best of their ability, but the ravid isn't intelligent enough to employ elaborate tactics with them.

### Drag

- **DEFINE:** DC_Drag|0
- **BONUS:** VAR|DC_Drag|DC_STR
- **BONUS:** VAR|DC_Drag|2
- **ABILITY:** Ability Focus|AUTOMATIC|Drag
- **DEFINE:** DC_Drag_Escape_Artist|0
- **BONUS:** VAR|DC_Drag_Escape_Artist|DC_Drag+4

If a roper hits with a strand attack, the strand latches onto the opponent's body. This deals no damage but drags the stuck opponent 10 feet closer each subsequent round (provoking no attack of opportunity) unless that creature breaks free, which requires a DC %1 Escape Artist check or a DC %2 Strength check. The check DCs are Strength-based, and the Escape Artist DC includes a +4 racial bonus. A roper can draw in a creature within 10 feet of itself and bite with a +4 attack bonus in the same round. A strand has 10 hit points and can be attacked by making a successful sunder attempt. However, attacking a roper's strand does not provoke an attack of opportunity. If the strand is currently attached to a target, the roper takes a -4 penalty on its opposed attack roll to resist the sunder attempt. Severing a strand deals no damage to a roper.|DC_Drag_Escape_Artist|DC_Drag

### Strands


Most encounters with a roper begin when it fires strong, sticky strands. The creature can have up to six strands at once, and they can strike up to 50 feet away (no range increment). If a strand is severed, the roper can extrude a new one on its next turn as a free action.

### Rust

- **DEFINE:** DC_Rust|0
- **BONUS:** VAR|DC_Rust|4+DC_CON
- **BONUS:** VAR|DC_Rust|2
- **ABILITY:** Ability Focus|AUTOMATIC|Rust

A rust monster that makes a successful touch attack with its antennae causes the target metal to corrode, falling to pieces and becoming useless immediately. The touch can destroy up to a 10-foot cube of metal instantly. Magic armor and weapons, and other magic items made of metal, must succeed on a DC %1 Reflex save or be dissolved. The save DC is Constitution-based and includes a +4 racial bonus. A metal weapon that deals damage to a rust monster corrodes immediately. Wooden, stone, and other nonmetallic weapons are unaffected.|DC_Rust

### Blood Frenzy


Once per day a sahuagin that takes damage in combat can fly into a frenzy in the following round, clawing and biting madly until either it or its opponent is dead. It gains +2 Constitution and +2 Strength, and takes a -2 penalty to Armor Class. A sahuagin cannot end its frenzy voluntarily.

### Freshwater Sensitivity


A sahuagin fully immersed in fresh water must succeed on a DC 15 Fortitude save or become fatigued. Even on a success, it must repeat the save attempt every 10 minutes it remains immersed.

### Speak with Sharks


Sahuagin can communicate telepathically with sharks up to 150 feet away. The communication is limited to fairly simple concepts such as "food," "danger," and "enemy." Sahuagin can use the Handle Animal skill to befriend and train sharks.

### Water Dependent


Sahuagin can survive out of the water for 1 hour per 2 points of Constitution (after that, refer to the drowning rules on page 304 of the Dungeon Master 's Guide).

### Pipes

- **DEFINE:** DC_Pipes|0
- **BONUS:** VAR|DC_Pipes|DC_CHA
- **BONUS:** VAR|DC_Pipes|2
- **ABILITY:** Ability Focus|AUTOMATIC|Pipes

Satyrs can play a variety of magical tunes on their pan pipes. Usually, only one satyr in a group carries pipes. When it plays, all creatures within a 60-foot spread (except satyrs) must succeed on a DC %1 Will save or be affected by charm person, sleep, or fear (caster level 10th; the satyr chooses the tune and its effect). In the hands of other beings, these pipes have no special powers. A creature that successfully saves against any of the pipe's effects cannot be affected by the same set of pipes for 24 hours. The save DC is Charisma-based.|DC_Pipes

### Strength Damage


The touch of a shadow deals 1d6 points of Strength damage to a living foe. A creature reduced to Strength 0 by a shadow dies. This is a negative energy effect.

### Bay

- **DEFINE:** DC_Bay|0
- **BONUS:** VAR|DC_Bay|DC_CHA
- **BONUS:** VAR|DC_Bay|2
- **ABILITY:** Ability Focus|AUTOMATIC|Bay

When a shadow mastiff howls or barks, all creatures except evil outsiders within a 300-foot spread must succeed on a DC %1 Will save or become panicked for 2d4 rounds. This is a sonic mind-affecting fear effect. Whether or not the save is successful, an affected creature is immune to the same mastiff 's bay for 24 hours. The save DC is Charisma-based.|DC_Bay

### Shadow Blend


In any condition of illumination other than full daylight, a shadow mastiff can disappear into the shadows, giving it total concealment. Artificial illumination, even a light or continual flame spell, does not negate this ability. A daylight spell, however, will.

### Immunity to Electricity


Shamblers take no damage from electricity. Instead, any electricity attack used against a shambler temporarily grants it 1d4 points of Constitution. The shambler loses these points at the rate of 1 per hour.

### Find Master


As long as a shield guardian and its amulet are on the same plane, the shield guardian can find the amulet wearer (or just the amulet, if it is removed after the guardian is called).

### Guard


If ordered to do so, a shield guardian moves swiftly to defend the wearer of its amulet, blocking blows and disrupting foes. All attacks against the amulet wearer take a -2 penalty when the shield guardian is adjacent to its master.

### Shield Other


The wearer of a shield guardian's amulet can activate this defensive ability if within 100 feet of the shield guardian. Just as the spell of the same name, this ability transfers to the shield guardian half the damage that would be dealt to the amulet wearer (this ability does not provide the spell's AC or save bonuses).

### Spell Storing


A shield guardian can store one spell of 4th level or lower that is cast into it by another creature. It "casts" this spell when commanded to do so or when a predefined situation arises. Once this spell is used, the shield guardian can store another spell (or the same spell again).

### Stunning Shock

- **DEFINE:** DC_Stunning_Shock|0
- **BONUS:** VAR|DC_Stunning_Shock|DC_CON
- **BONUS:** VAR|DC_Stunning_Shock|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stunning Shock

Once per round, a shocker lizard can deliver an electrical shock to a single opponent within 5 feet. This attack deals 2d8 points of nonlethal damage to living opponents (Reflex DC %1 half ). The save DC is Constitution-based.|DC_Stunning_Shock

### Lethal Shock


Whenever two or more shocker lizards are within 20 feet of each other, they can work together to create a lethal shock. This effect has a radius of 20 feet, centered on any one contributing lizard. The shock deals 2d8 points of electricity damage for each lizard contributing to it, to a maximum of 12d8. A Reflex save (DC 10 + number of lizards contributing) reduces the damage by half.

### Electricity Sense


Shocker lizards automatically detect any electrical discharges within 100 feet.

### Race Traits ~ Red Slaad

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=RedSlaadRaceAbility

### Implant

- **DEFINE:** DC_Implant|0
- **BONUS:** VAR|DC_Implant|DC_CON
- **BONUS:** VAR|DC_Implant|2
- **ABILITY:** Ability Focus|AUTOMATIC|Implant

A red slaad that hits with a claw attack can inject an egg pellet into the opponent's body. The affected creature must succeed on a DC %1 Fortitude save to avoid implantation. The save DC is Constitution-based. Often the slaad implants an unconscious or otherwise helpless creature (which gets no saving throw). The egg gestates for one week before hatching into a blue slaad that eats its way out, killing the host. Twenty-four hours before the egg fully matures, the victim falls extremely ill (-10 to all ability scores, to a minimum of 1). A remove disease spell rids a victim of the pellet, as does a DC 25 Heal check. If the check fails, the healer can try again, but each attempt (successful or not) deals 1d4 points of damage to the patient. If the host is an arcane spellcaster, the egg pellet instead hatches into a green slaad.|DC_Implant

### Stunning Croak

- **DEFINE:** DC_Stunning_Croak|0
- **BONUS:** VAR|DC_Stunning_Croak|DC_CON
- **BONUS:** VAR|DC_Stunning_Croak|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stunning Croak

Once per day a red slaad can emit a loud croak. Every creature (except slaadi) within 20 feet must succeed on a DC %1 Fortitude save or be stunned for 1d3 rounds. The save DC is Constitution-based.|DC_Stunning_Croak

### Summon Slaad


Once per day a red slaad can attempt to summon another red slaad with a 40%% chance of success. This ability is the equivalent of a 3rd-level spell.

### Race Traits ~ Blue Slaad

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=BlueSlaadRaceAbility

### Slaad Fever

- **DEFINE:** DC_Slaad_Fever|0
- **BONUS:** VAR|DC_Slaad_Fever|DC_CON
- **BONUS:** VAR|DC_Slaad_Fever|2
- **ABILITY:** Ability Focus|AUTOMATIC|Slaad Fever

Supernatural disease-bite, Fortitude DC %1, incubation period 1 day, damage 1d3 Dex and 1d3 Cha. The save DC is Constitution-based. An afflicted humanoid reduced to Charisma 0 by slaad fever immediately transforms into a red slaad. It retains none of the features, traits, memories, or abilities of its former self, and is a normal red slaad in all respects. If the infected being is an arcane spellcaster, the disease instead produces a green slaad.|DC_Slaad_Fever

### Race Traits ~ Green Slaad

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=GreenSlaadRaceAbility

### Race Traits ~ Gray Slaad

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=GraySlaadRaceAbility

### Race Traits ~ Death Slaad

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=DeathSlaadRaceAbility

### Unnatural Aura


Animals, whether wild or domesticated, can sense the unnatural presence of a spectre at a distance of 30 feet. They do not willingly approach nearer than that and panic if forced to do so; they remain panicked as long as they are within that range.

### Sunlight Powerlessness


Spectres are powerless in natural sunlight (not merely a daylight spell) and flee from it. A spectre caught in sunlight cannot attack and can take only a single move or attack action in a round.

### Fiddle

- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=8|Irresistible Dance
- **DEFINE:** DC_Fiddle|0
- **BONUS:** VAR|DC_Fiddle|DC_CHA
- **BONUS:** VAR|DC_Fiddle|2
- **ABILITY:** Ability Focus|AUTOMATIC|Fiddle

One grig in each band carries a tiny, grig-sized fiddle. When the fiddler plays, any nonsprite within 30 feet of the instrument must succeed on a DC %1 Will save or be affected as though by Otto's Irresistible Dance for as long as the playing continues. The save DC is Charisma-based.|DC_Fiddle

### Charm Person

- **DEFINE:** DC_Charm_Person|0
- **BONUS:** VAR|DC_Charm_Person|DC_CHA
- **BONUS:** VAR|DC_Charm_Person|2
- **ABILITY:** Ability Focus|AUTOMATIC|Charm Person

A nixie can use charm person three times per day as the spell (caster level 4th). Those affected must succeed on a DC %1 Will save or be charmed for 24 hours. Most charmed creatures are used to perform heavy labor, guard duty, and other onerous tasks for the nixie community. Shortly before the effect wears off, the nixie escorts the charmed creature away and orders it to keep walking. The save DC is Charisma-based.|DC_Charm_Person

### Special Arrows

- **DEFINE:** DC_Pixie_Arrow|0
- **BONUS:** VAR|DC_Pixie_Arrow|2+DC_CHA
- **BONUS:** VAR|DC_Pixie_Arrow|2
- **ABILITY:** Ability Focus|AUTOMATIC|Pixie Arrow

Pixies sometimes employ arrows that deal no damage but can erase memory or put a creature to sleep.

Memory Loss: An opponent struck by this arrow must succeed on a DC %1 Will save or lose all memory. The save DC is Charisma-based and includes a +2 racial bonus. The subject retains skills, languages, and class abilities but forgets everything else until he or she receives a heal spell or memory restoration with limited wish, wish, or miracle.|DC_Pixie_Arrow

Sleep: Any opponent struck by this arrow, regardless of Hit Dice, must succeed on a DC %1 Fortitude save or be affected as though by a sleep spell. The save DC is Charisma-based and includes a +2 racial bonus.|DC_Pixie_Arrow

### Distraction

- **DEFINE:** DC_Distraction|0
- **BONUS:** VAR|DC_Distraction|DC_CON
- **BONUS:** VAR|DC_Distraction|2
- **ABILITY:** Ability Focus|AUTOMATIC|Distraction

Any living creature that begins its turn with a swarm in its space must succeed on a DC %1 Fortitude save or be nauseated for 1 round. The save DC is Constitution-based.|DC_Distraction

### Wounding


Any living creature damaged by a bat swarm continues to bleed, losing 1 hit point per round thereafter. Multiple wounds do not result in cumulative bleeding loss. The bleeding can be stopped by a DC 10 Heal check or the application of a cure spell or some other healing magic.

### Inhabit


A hellwasp swarm can enter the body of a helpless or dead creature by crawling into its mouth and other orifices. Inhabiting requires 1 minute, and the victim must be Small, Medium, or Large (although four swarms working together can inhabit a Huge creature). The swarm can abandon the body at any time, although doing this takes 1 full round. Any attack against the host deals half damage to the hellwasp swarm as well, although the swarm's resistances and immunities may negate some or all of this damage. If a hellwasp swarm inhabits a dead body, it can restore animation to the creature and control its movements, effectively transforming it into a zombie of the appropriate size for as long as the swarm remains inside. If a hellwasp swarm inhabits a living victim, it can neutralize the effects of its own poison and control the victim's movement and actions as if using dominate monster on the victim. The hellwasps quickly consume a living victim, dealing 2d4 points of Constitution damage per hour they inhabit a body. A body reduced to Constitution 0 is dead. A hellwasp-inhabited creature is relatively easy to spot, since its skin crawls with the forms of insects inside. The swarm is intelligent enough to attempt to hide beneath loose clothing or a large cloak to keep its presence from being detected. The swarm can attempt a Disguise check to conceal its inhabitation of a host, with a -4 penalty if currently inhabiting a Small host. A remove disease or heal spell cast on an inhabited victim forces the hellwasp swarm to abandon its host.

### Augmented Critical


The tarrasque's bite threatens a critical hit on a natural attack roll of 18-20, dealing triple damage on a successful critical hit.

### Frightful Presence

- **DEFINE:** DC_Frightful_Presence|0
- **BONUS:** VAR|DC_Frightful_Presence|DC_CHA
- **BONUS:** VAR|DC_Frightful_Presence|2
- **ABILITY:** Ability Focus|AUTOMATIC|Frightful Presence

The tarrasque can inspire terror by charging or attacking. Affected creatures must succeed on a DC %1 Will save or become shaken, remaining in that condition as long as they remain with 60 feet of the tarrasque. The save DC is Charisma-based.|DC_Frightful_Presence

### Rush


Once per minute, the normally slow-moving tarrasque can move at a speed of 150 feet.

### Carapace


The tarrasque's armorlike carapace is exceptionally tough and highly reflective, deflecting all rays, lines, cones, and even magic missile spells. There is a 30%% chance of reflecting any such effect back at the caster; otherwise, it is merely negated. Check for reflection before rolling to overcome the creature's spell resistance.

### Swallow Whole/Paralysis

- **DEFINE:** DC_Paralysis|0
- **BONUS:** VAR|DC_Paralysis|DC_CON
- **BONUS:** VAR|DC_Paralysis|2
- **ABILITY:** Ability Focus|AUTOMATIC|Paralysis

A tendriculos can try to swallow a grabbed opponent by making a successful grapple check. Once inside the plant's mass, the opponent must succeed on a DC %1 Fortitude save or be paralyzed for 3d6 rounds by the tendriculos's digestive juices, taking 2d6 points of acid damage per round. A new save is required each round inside the plant. The save DC is Constitution-based. A swallowed creature that avoids paralysis can climb out of the mass with a successful grapple check. This returns it to the plant's maw, where another successful grapple check is needed to get free. A swallowed creature can also cut its way out by using a light slashing or piercing weapon to deal 25 points of damage to the tendriculos's interior (AC 14). Once the creature exits, the plant's regenerative capacity closes the hole; another swallowed opponent must cut its own way out. A Huge tendriculos's interior can hold 2 Large, 8 Medium, 32 Small, 128 Tiny, or 512 Diminutive or smaller opponents.|DC_Paralysis

### Animate Trees


A treant can animate trees within 180 feet at will, controlling up to two trees at a time. It takes 1 full round for a normal tree to uproot itself. Thereafter it moves at a speed of 10 feet and fights as a treant in all respects. Animated trees lose their ability to move if the treant that animated them is incapacitated or moves out of range. The ability is otherwise similar to liveoak (caster level 12th). Animated trees have the same vulnerability to fire that a treant has.

### Double Damage against Objects


A treant or animated tree that makes a full attack against an object or structure deals double damage.

### Race Traits ~ Umber Hulk

- **ABILITY:** Special Ability|AUTOMATIC|Umber Hulk ~ Confusing Gaze

### Confusing Gaze


Confusion as the spell, 30 feet, caster level 8th, Will DC 15 negates. The save DC is Charisma-based.

### Children of the Night


Vampires command the lesser creatures of the world and once per day can call forth 1d6+1 rat swarms, 1d4+1 bat swarms, or a pack of 3d6 wolves as a standard action. (If the base creature is not terrestrial, this power might summon other creatures of similar power.) These creatures arrive in 2d6 rounds and serve the vampire for up to 1 hour.

### Dominate

- **DEFINE:** DC_Domination|0
- **BONUS:** VAR|DC_Domination|DC_CHA
- **BONUS:** VAR|DC_Domination|2
- **ABILITY:** Ability Focus|AUTOMATIC|Domination

A vampire can crush an opponent's will just by looking onto his or her eyes. This is similar to a gaze attack, except that the vampire must use a standard action, and those merely looking at it are not affected. Anyone the vampire targets must succeed on a Will save or fall instantly under the vampire's influence as though by a dominate person spell (caster level 12th). The ability has a range of 30 feet. [DC %1]|DC_Domination

### Gaseous Form


As a standard action, a vampire can assume gaseous form at will as the spell (caster level 5th), but it can remain gaseous indefinitely and has a fly speed of 20 feet with perfect maneuverability.

### Resistances


A vampire has resistance to cold 10 and electricity 10.

### Vampire Weaknesses


For all their power, vampires have a number of weaknesses.

Repelling a Vampire: Vampires cannot tolerate the strong odor of garlic and will not enter an area laced with it. Similarly, they recoil from a mirror or a strongly presented holy symbol. These things don't harm the vampire-they merely keep it at bay. A recoiling vampire must stay at least 5 feet away from a creature holding the mirror or holy symbol and cannot touch or make melee attacks against the creature holding the item for the rest of the encounter. Holding a vampire at bay takes a standard action.

Vampires are also unable to cross running water, although they can be carried over it while resting in their coffins or aboard a ship.

They are utterly unable to enter a home or other building unless invited in by someone with the authority to do so. They may freely enter public places, since these are by definition open to all.

Slaying a Vampire: Reducing a vampire's hit points to 0 or lower incapacitates it but doesn't always destroy it (see the note on fast healing). However, certain attacks can slay vampires. Exposing any vampire to direct sunlight disorients it: It can take only a single move action or attack action and is destroyed utterly in the next round if it cannot escape. Similarly, immersing a vampire in running water robs it of one-third of its hit points each round until it is destroyed at the end of the third round of immersion. Driving a wooden stake through a vampire's heart instantly slays the monster. However, it returns to life if the stake is removed, unless the body is destroyed. A popular tactic is to cut off the creature's head and fill its mouth with holy wafers (or their equivalent).

### Domination

- **DEFINE:** DC_Domination|0
- **BONUS:** VAR|DC_Domination|DC_CHA
- **BONUS:** VAR|DC_Domination|2
- **ABILITY:** Ability Focus|AUTOMATIC|Domination

A vampire spawn can crush an opponent's will just by looking onto his or her eyes. This is similar to a gaze attack, except that the vampire must take a standard action, and those merely looking at it are not affected. Anyone the vampire targets must succeed on a DC %1 Will save or fall instantly under the vampire's influence as though by a dominate person spell from a 5th level caster. The ability has a range of 30 feet. The save DC is Charisma-based.|DC_Domination

### Kiss

- **DEFINE:** DC_Kiss|0
- **BONUS:** VAR|DC_Kiss|4+DC_CON
- **BONUS:** VAR|DC_Kiss|2
- **ABILITY:** Ability Focus|AUTOMATIC|Kiss

A vargouille can kiss a paralyzed target with a successful melee touch attack. An affected opponent must succeed on a DC %1 Fortitude save or begin a terrible transformation that turns the creature into a vargouille within 24 hours (and often much sooner; roll 1d6 separately for each phase of the transformation). First, over a period of 1d6 hours, all the victim's hair falls out. Within another 1d6 hours thereafter, the ears grow into leathery wings, tentacles sprout on the chin and scalp, and the teeth become long, pointed fangs. During the next 1d6 hours, the victim takes Intelligence drain and Charisma drain equal to 1 point per hour (to a minimum of 3). The transformation is complete 1d6 hours later, when the head breaks free of the body (which promptly dies) and becomes a vargouille. This transformation is interrupted by sunlight, and even a daylight spell can delay death, but to reverse the transformation requires remove disease. The save DC is Constitution-based and includes a +4 racial bonus.|DC_Kiss

### Freezing Bite


A winter wolf deals an extra 1d6 points of cold damage every time it bites an opponent, as if its bite were a frost weapon.

### Daylight Powerlessness


Wraiths are utterly powerless in natural sunlight (not merely a daylight spell) and flee from it.

### Constitution Drain

- **DEFINE:** DC_Constitution_Drain|0
- **BONUS:** VAR|DC_Constitution_Drain|DC_CHA
- **BONUS:** VAR|DC_Constitution_Drain|2
- **ABILITY:** Ability Focus|AUTOMATIC|Constitution Drain

Living creatures hit by a wraith's incorporeal touch attack must succeed on a DC %1 Fortitude save or take 1d6 points of Constitution drain. The save DC is Charisma-based. On each such successful attack, the wraith gains 5 temporary hit points.|DC_Constitution_Drain

### Lifesense


A dread wraith notices and locates living creatures within 60 feet, just as if it possessed the blindsight ability. It also senses the strength of their life force automatically, as if it had cast deathwatch.

### Planewalk


These planar travelers like to slip between the folds of space to attack enemies as though from thin air. They can cross from the Ethereal Plane with a move action but take 2 rounds to cross back, during which time they are immobile. As a xill fades away, it becomes harder to hit: Opponents have a 20%% miss chance in the first round and a 50%% miss chance in the second. A xill can planewalk with a willing or helpless creature.

### Sonic Lance


Once every 2 rounds, a yrthak can focus sonic energy in a ray up to 60 feet long. This is a ranged touch attack that deals 6d6 points of damage to a single target.

### Explosion


A yrthak can fire its sonic lance at the ground, a large rock, a stone wall, or the like to create an explosion of shattered stone. This attack deals 2d6 points of piercing damage to all within 10 feet of the effect's center. This counts as a use of the sonic lance attack and thus is usable only once every 2 rounds, and never on the round following a sonic lance attack.

### Detect Poison


All yuan-ti have the psionic ability to detect poison as the spell (caster level 6th).

### Race Traits ~ Pureblood Yuan-Ti

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=PurebloodYuantiRaceAbility

### Race Traits ~ Halfblood Yuan-Ti

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=HalfbloodYuantiRaceAbility

### Produce Acid


A yuan-ti halfblood has the psionic power to exude acid from its body, dealing 3d6 points of acid damage to the next creature it touches, including a creature hit by its bite attack. If the yuan-ti is grappling or pinning a foe when it uses this power, its grasp deals 5d6 points of acid damage. The acid becomes inert when it leaves the yuan-ti's body, and the yuan-ti is immune to its effects.

### Chameleon Power


A yuan-ti halfblood can psionically change the coloration of itself and its equipment to match its surroundings, granting it a +10 circumstance bonus on Hide checks.

### Race Traits ~ Abomination Yuan-Ti

- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AbominationYuantiRaceAbility

### Aversion

- **DEFINE:** DC_Aversion|0
- **BONUS:** VAR|DC_Aversion|DC_CHA
- **BONUS:** VAR|DC_Aversion|2
- **ABILITY:** Ability Focus|AUTOMATIC|Aversion

A yuan-ti abomination can psionically create a compulsion effect targeting one creature within 30 feet. The target must succeed on a DC %1 Will save or gain an aversion to snakes for 10 minutes. Affected creatures must stay at least 20 feet away from any snake or yuanti, alive or dead; if already within 20 feet, they move away. A subject unable to move away, or one attacked by snakes or yuan-ti, is overcome with revulsion. This revulsion reduces the creature's Dexterity score by 4 points until the effect wears off or the subject is no longer within 20 feet of a snake or yuan-ti. This ability is otherwise similar to antipathy as the spell (caster level 16th). The save DC is Charisma-based.|DC_Aversion

### Single Actions Only


Zombies have poor reflexes and can perform only a single move action or attack action each round. A zombie can move up to its speed and attack in the same round, but only if it attempts a charge.

### Stampede

- **DEFINE:** DC_Stampede|0
- **BONUS:** VAR|DC_Stampede|DC_STR
- **BONUS:** VAR|DC_Stampede|2
- **ABILITY:** Ability Focus|AUTOMATIC|Stampede

A frightened herd of bison flees as a group in a random direction (but always away from the perceived source of danger). They literally run over anything of Large size or smaller that gets in their way, dealing 1d12 points of damage for each five bison in the herd (Reflex DC %1 half ). The save DC is Strength-based.|DC_Stampede

### Sprint


Once per hour, a cheetah can move ten times its normal speed (500 feet) when it makes a charge.

### Combat


If trained for war, these animals can make trip attacks just as wolves do (see the Wolf entry). A riding dog can fight while carrying a rider, but the rider cannot also attack unless he or she succeeds on a Ride check.

### Tentacles


An opponent can attack a giant octopus's tentacles with a sunder attempt as if they were weapons. A giant octopus's tentacles have 10 hit points each. If a giant octopus is currently grappling a target with the tentacle that is being attacked, it usually uses another limb to make its attack of opportunity against the opponent making the sunder attempt. Severing one of a giant octopus's tentacles deals 5 points of damage to the creature. A giant octopus usually withdraws from combat if it loses four tentacles. The creature regrows severed limbs in 1d10+10 days.

### Race Traits ~ Ape

- **ABILITY:** Special Ability|AUTOMATIC|Ape ~ Skills|Scent

### Race Traits ~ Baboon

- **ABILITY:** Special Ability|AUTOMATIC|Baboon ~ Skills|Scent

### Race Traits ~ Badger

- **ABILITY:** Special Ability|AUTOMATIC|Badger ~ Rage|Badger ~ Skills|Scent

### Race Traits ~ Bat

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Bat ~ Blindsense|Bat ~ Skills

### Race Traits ~ Bear (Black)

- **ABILITY:** Special Ability|AUTOMATIC|Black Bear ~ Skills|Scent

### Race Traits ~ Bear (Brown)

- **ABILITY:** Special Ability|AUTOMATIC|Brown Bear ~ Improved Grab|Brown Bear ~ Skills|Scent

### Race Traits ~ Bear (Polar)

- **ABILITY:** Special Ability|AUTOMATIC|Polar Bear ~ Improved Grab|Polar Bear ~ Skills|Scent

### Race Traits ~ Bison

- **ABILITY:** Special Ability|AUTOMATIC|Bison ~ Stampede|Scent

### Race Traits ~ Boar

- **ABILITY:** Special Ability|AUTOMATIC|Boar ~ Ferocity|Scent

### Race Traits ~ Camel

- **ABILITY:** Special Ability|AUTOMATIC|Scent

### Race Traits ~ Camel (Bactrian)

- **ABILITY:** Special Ability|AUTOMATIC|Scent

### Race Traits ~ Cat

- **ABILITY:** Special Ability|AUTOMATIC|Cat ~ Skills|Scent

### Race Traits ~ Cheetah

- **ABILITY:** Special Ability|AUTOMATIC|Cheetah ~ Sprint|Cheetah ~ Trip|Scent

### Race Traits ~ Crocodile

- **ABILITY:** Special Ability|AUTOMATIC|Crocodile ~ Hold Breath|Crocodile ~ Improved Grab|Crocodile ~ Skills

### Race Traits ~ Crocodile (Giant)

- **ABILITY:** Special Ability|AUTOMATIC|Crocodile ~ Hold Breath|Crocodile ~ Improved Grab|Crocodile ~ Skills

### Race Traits ~ Dog

- **ABILITY:** Special Ability|AUTOMATIC|Dog ~ Skills|Scent

### Race Traits ~ Dog (Riding)

- **ABILITY:** Special Ability|AUTOMATIC|Riding Dog ~ Combat|Riding Dog ~ Skills|Scent

### Race Traits ~ Donkey

- **ABILITY:** Special Ability|AUTOMATIC|Donkey ~ Skills|Scent

### Race Traits ~ Eagle

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Eagle ~ Skills

### Race Traits ~ Elephant

- **ABILITY:** Special Ability|AUTOMATIC|Elephant ~ Trample|Scent

### Race Traits ~ Elephant (Indian)

- **ABILITY:** Special Ability|AUTOMATIC|Elephant ~ Trample|Scent

### Race Traits ~ Hawk

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Hawk ~ Skills

### Race Traits ~ Horse (Heavy)

- **ABILITY:** Special Ability|AUTOMATIC|Heavy Horse ~ Combat|Horse Shared ~ Combat|Scent

### Race Traits ~ Horse (Light)

- **ABILITY:** Special Ability|AUTOMATIC|Horse Shared ~ Combat|Light Horse ~ Combat|Scent

### Race Traits ~ Horse (Warhorse Heavy)

- **TEMPLATE:** War Trained
- **ABILITY:** Special Ability|AUTOMATIC|Heavy Warhorse ~ Combat|Scent

### Race Traits ~ Horse (Warhorse Light)

- **TEMPLATE:** War Trained
- **ABILITY:** Special Ability|AUTOMATIC|Light Warhorse ~ Combat|Scent

### Race Traits ~ Hyena

- **ABILITY:** Special Ability|AUTOMATIC|Hyena ~ Skills|Hyena ~ Trip|Scent

### Race Traits ~ Leopard

- **ABILITY:** Special Ability|AUTOMATIC|Leopard ~ Improved Grab|Leopard ~ Pounce|Leopard ~ Rake|Leopard ~ Skills|Scent

### Race Traits ~ Lion

- **ABILITY:** Special Ability|AUTOMATIC|Lion ~ Improved Grab|Lion ~ Pounce|Lion ~ Rake|Lion ~ Skills|Scent

### Race Traits ~ Lizard

- **ABILITY:** Special Ability|AUTOMATIC|Lizard ~ Skills

### Race Traits ~ Lizard (Monitor)

- **ABILITY:** Special Ability|AUTOMATIC|Monitor Lizard ~ Skills

### Race Traits ~ Manta Ray

- **ABILITY:** Special Ability|AUTOMATIC|Manta Ray ~ Combat|Manta Ray ~ Skills

### Race Traits ~ Monkey

- **ABILITY:** Special Ability|AUTOMATIC|Monkey ~ Skills

### Race Traits ~ Mule

- **ABILITY:** Special Ability|AUTOMATIC|Mule ~ Skills|Scent

### Race Traits ~ Octopus

- **ABILITY:** Special Ability|AUTOMATIC|Octopus ~ Improved Grab|Octopus ~ Ink Cloud|Octopus ~ Jet|Octopus ~ Skills

### Race Traits ~ Octopus (Giant)

- **ABILITY:** Special Ability|AUTOMATIC|Giant Octopus ~ Constrict|Giant Octopus ~ Improved Grab|Giant Octopus ~ Ink Cloud|Giant Octopus ~ Jet|Giant Octopus ~ Skills|Giant Octopus ~ Tentacles

### Race Traits ~ Owl

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Owl ~ Skills

### Race Traits ~ Pony

- **ABILITY:** Special Ability|AUTOMATIC|Pony ~ Combat|Scent

### Race Traits ~ Pony (War)

- **TEMPLATE:** War Trained
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Warpony ~ Combat

### Race Traits ~ Porpoise

- **ABILITY:** Special Ability|AUTOMATIC|Porpoise ~ Blindsight|Porpoise ~ Hold Breath|Porpoise ~ Skills

### Race Traits ~ Rat

- **ABILITY:** Special Ability|AUTOMATIC|Rat ~ Skills|Scent

### Race Traits ~ Raven

- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability

### Race Traits ~ Rhinoceros

- **ABILITY:** Special Ability|AUTOMATIC|Rhinoceros ~ Powerful Charge

### Race Traits ~ Shark (Medium)

- **ABILITY:** Special Ability|AUTOMATIC|Shark ~ Blindsense|Shark ~ Keen Scent|Shark ~ Skills

### Race Traits ~ Shark (Large)

- **ABILITY:** Special Ability|AUTOMATIC|Shark ~ Blindsense|Shark ~ Keen Scent|Shark ~ Skills

### Race Traits ~ Shark (Huge)

- **ABILITY:** Special Ability|AUTOMATIC|Shark ~ Blindsense|Shark ~ Keen Scent|Shark ~ Skills

### Race Traits ~ Snake (Constrictor)

- **ABILITY:** Special Ability|AUTOMATIC|Constrictor Snake ~ Constrict|Constrictor Snake ~ Improved Grab|Scent|Snake Shared ~ Skills

### Race Traits ~ Snake (Constrictor/Giant)

- **ABILITY:** Special Ability|AUTOMATIC|Constrictor Snake ~ Constrict|Constrictor Snake ~ Improved Grab|Scent|Snake Shared ~ Skills

### Race Traits ~ Snake (Viper/Tiny)

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Snake Shared ~ Skills|Viper Snake ~ Poison

### Race Traits ~ Snake (Viper/Small)

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Snake Shared ~ Skills|Viper Snake ~ Poison

### Race Traits ~ Snake (Viper/Medium)

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Snake Shared ~ Skills|Viper Snake ~ Poison

### Race Traits ~ Snake (Viper/Large)

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Snake Shared ~ Skills|Viper Snake ~ Poison

### Race Traits ~ Snake (Viper/Huge)

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Snake Shared ~ Skills|Viper Snake ~ Poison

### Race Traits ~ Squid

- **ABILITY:** Special Ability|AUTOMATIC|Squid ~ Improved Grab|Squid ~ Ink Cloud|Squid ~ Jet|Squid ~ Skills

### Race Traits ~ Squid (Giant)

- **ABILITY:** Special Ability|AUTOMATIC|Giant Squid ~ Combat|Giant Squid ~ Constrict|Giant Squid ~ Improved Grab|Giant Squid ~ Ink Cloud|Giant Squid ~ Jet|Giant Squid ~ Skills

### Race Traits ~ Tiger

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Tiger ~ Improved Grab|Tiger ~ Pounce|Tiger ~ Rake|Tiger ~ Skills

### Race Traits ~ Toad

- **ABILITY:** Special Ability|AUTOMATIC|Amphibious|Toad ~ Skills

### Race Traits ~ Weasel

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Weasel ~ Attach|Weasel ~ Skills

### Race Traits ~ Whale (Baleen)

- **ABILITY:** Special Ability|AUTOMATIC|Whale ~ Blindsight|Whale ~ Hold Breath|Whale ~ Skills

### Race Traits ~ Whale (Cachalot)

- **ABILITY:** Special Ability|AUTOMATIC|Whale ~ Blindsight|Whale ~ Hold Breath|Whale ~ Skills

### Race Traits ~ Whale (Orca)

- **ABILITY:** Special Ability|AUTOMATIC|Whale ~ Blindsight|Whale ~ Hold Breath|Whale ~ Skills

### Race Traits ~ Wolf

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Wolf ~ Skills|Wolf ~ Trip

### Race Traits ~ Wolverine

- **ABILITY:** Special Ability|AUTOMATIC|Scent|Wolverine ~ Rage|Wolverine ~ Skills

### Acid Sting


A giant soldier ant has a stinger and an acid-producing gland in its abdomen. If it successfully grabs an opponent, it can attempt to sting each round (+3 attack bonus). A hit with the sting attack deals 1d4+1 points of piercing damage and 1d4 points of acid damage.

### Breath Weapon ~ Cone of Cold

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Cold %2d%3 cold DC %4|BreathWeaponCone|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Corrosive Gas

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Corrosive Gas %2d%3 acid DC %4|BreathWeaponCone|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Fire

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Fire %2d%3 Fire DC %4|BreathWeaponCone|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Paralyzing Gas

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDuration|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Paralyzing Gas DC %2 for 1d6+%3 rounds|BreathWeaponCone|DC_Breath_Weapon|BreathWeaponDuration

### Breath Weapon ~ Cone of Repulsion Gas

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDuration|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Repulsion Gas DC %2 for 1d6+%3 rounds|BreathWeaponCone|DC_Breath_Weapon|BreathWeaponDuration

### Breath Weapon ~ Cone of Sleep

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDuration|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Sleep DC %2 for 1d6+%3 rounds|BreathWeaponCone|DC_Breath_Weapon|BreathWeaponDuration

### Breath Weapon ~ Cone of Slow

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDuration|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Slow DC %2 for 1d6+%3 rounds|BreathWeaponCone|DC_Breath_Weapon|BreathWeaponDuration

### Breath Weapon ~ Cone of Weakening Gas

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponStatDamage|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Weakening Gas DC %2 or -%3 STR|BreathWeaponCone|DC_Breath_Weapon|BreathWeaponStatDamage

### Breath Weapon ~ Line of Acid

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Line of Acid %2d%3 acid DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Line of Fire

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Line of Fire %2d%3 fire DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Line of Lightning

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Line of Lightning %2d%3 electricity DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Force

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone of Force %2d%3 DC %4|BreathWeaponCone|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Prismatic Spray

- **DEFINE:** BreathWeaponSpray|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Prismatic Spray Effect DC %2|BreathWeaponSpray|DC_Breath_Weapon

### Half-Dragon Breath Weapon ~ Cone of Acid

- **DEFINE:** HalfDragonBreathTimes|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|HalfDragonBreathTimes|1
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

30' Cone of Acid %1/day 6d8 (DC %2)|HalfDragonBreathTimes|DC_Breath_Weapon

### Half-Dragon Breath Weapon ~ Cone of Cold

- **DEFINE:** HalfDragonBreathTimes|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|HalfDragonBreathTimes|1
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

30' Cone of Cold %1/day 6d8 (DC %2)|HalfDragonBreathTimes|DC_Breath_Weapon

### Half-Dragon Breath Weapon ~ Cone of Fire

- **DEFINE:** HalfDragonBreathTimes|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|HalfDragonBreathTimes|1
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

30' Cone of Fire %1/day 6d8 (DC %2)|HalfDragonBreathTimes|DC_Breath_Weapon

### Half-Dragon Breath Weapon ~ Line of Acid

- **DEFINE:** HalfDragonBreathTimes|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|HalfDragonBreathTimes|1
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

60' Line of Acid %1/day 6d8 (DC %2)|HalfDragonBreathTimes|DC_Breath_Weapon

### Half-Dragon Breath Weapon ~ Line of Electricity

- **DEFINE:** HalfDragonBreathTimes|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|HalfDragonBreathTimes|1
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

60' Line of Electricity %1/day 6d8 (DC %2)|HalfDragonBreathTimes|DC_Breath_Weapon

### Half-Dragon Breath Weapon ~ Line of Fire

- **DEFINE:** HalfDragonBreathTimes|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|HalfDragonBreathTimes|1
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

60' Line of Fire %1/day 6d8 (DC %2)|HalfDragonBreathTimes|DC_Breath_Weapon

### Hydra ~ Breath Fire

- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|10+floor(HydraHeadCount/2)+CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1 heads every 1d4 rounds/3d6 Fire Damage/DC %2 for half|HydraHeadCount|DC_Breath_Weapon

### Hydra ~ Breath Frost

- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|10+floor(HydraHeadCount/2)+CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1 heads every 1d4 rounds/3d6 Cold Damage/DC %2 for half|HydraHeadCount|DC_Breath_Weapon

### +2 racial bonus on Appraise checks that are related to stone or metal items.

- **DEFINE:** DwarfAppraiseSkillBonus|0
- **BONUS:** VAR|DwarfAppraiseSkillBonus|2
- **TEMPBONUS:** PC|SKILL|Appraise|DwarfAppraiseSkillBonus|TYPE=Racial

+%1 racial bonus on Appraise checks that are related to stone or metal items.|DwarfAppraiseSkillBonus

### +2 racial bonus on Craft checks that are related to stone or metal.

- **DEFINE:** DwarfCraftSkillBonus|0
- **BONUS:** SKILL|Craft (Armorsmithing),Craft (Blacksmithing),Craft (Metalworking),Craft (Stoneworking),Craft (Weaponsmithing)|2|TYPE=Racial
- **BONUS:** VAR|DwarfCraftSkillBonus|2
- **TEMPBONUS:** PC|SKILL|TYPE.Craft|DwarfCraftSkillBonus|TYPE=Racial

+%1 racial bonus on Craft checks that are related to stone or metal.|DwarfCraftSkillBonus

### Fey Proficiencies

- **AUTO:** WEAPONPROF|TYPE=Simple

### Giant Proficiencies

- **AUTO:** WEAPONPROF|TYPE=Simple|TYPE=Martial

### Humanoid Proficiencies

- **AUTO:** WEAPONPROF|TYPE=Simple

### Monstrous Humanoid Proficiencies

- **AUTO:** WEAPONPROF|TYPE=Simple

### Outsider Proficiencies

- **AUTO:** WEAPONPROF|TYPE=Simple|TYPE=Martial

### Undead Proficiencies

- **AUTO:** WEAPONPROF|TYPE=Simple

### Fists


### Keening


### Ray


### Seduction


### Soul Portal


### Tail Sweep


### Pixie Arrow


### Race Size ~ Long

- **DEFINE:** RaceSizeIsLong|0
- **BONUS:** VAR|RaceSizeIsLong|1

### Goblin

- **BONUS:** ABILITYPOOL|Race Base|1|TYPE=Base

### Hobgoblin

- **BONUS:** ABILITYPOOL|Race Base|1|TYPE=Base

### Orc

- **BONUS:** ABILITYPOOL|Race Base|1|TYPE=Base

### Kobold

- **BONUS:** ABILITYPOOL|Race Base|1|TYPE=Base

### Aasimar

- **BONUS:** ABILITYPOOL|Race Base|1|TYPE=Base

### Tiefling

- **BONUS:** ABILITYPOOL|Race Base|1|TYPE=Base

### Race Traits ~ Goblin

- **ABILITY:** Goblin Subrace|AUTOMATIC|Goblin ~ Base|!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice

### Race Traits ~ Hobgoblin

- **ABILITY:** Hobgoblin Subrace|AUTOMATIC|Hobgoblin ~ Base|!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice

### Race Traits ~ Orc

- **ABILITY:** Orc Subrace|AUTOMATIC|Orc ~ Base|!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice

### Race Traits ~ Kobold

- **ABILITY:** Kobold Subrace|AUTOMATIC|Kobold ~ Base|!PREABILITY:1,CATEGORY=Internal,TYPE.AltSubraceChoice

### Race Traits ~ Planetouched (Aasimar)

- **BONUS:** ABILITYPOOL|Aasimar Subrace|1
- **DEFINE:** AasimarRaceSelection|0
- **ABILITY:** Internal|AUTOMATIC|Aasimar Subrace ~ Standard
- **ABILITY:** Internal|AUTOMATIC|Assign Race Type ~ Outsider|Assign Race Subtype ~ Native
- **DEFINE:** DefaultRaceType|0

### Race Traits ~ Planetouched (Tiefling)

- **BONUS:** ABILITYPOOL|Tiefling Subrace|1
- **DEFINE:** TieflingRaceSelection|0
- **ABILITY:** Internal|AUTOMATIC|Tiefling Subrace ~ Standard
- **ABILITY:** Internal|AUTOMATIC|Assign Race Type ~ Outsider|Assign Race Subtype ~ Native

### Language ~ Auto (Goblin)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Goblin

### Language ~ Auto (Hobgoblin)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Goblin

### Language ~ Auto (Orc)

- **ABILITY:** Language|AUTOMATIC|Common
- **ABILITY:** Language|AUTOMATIC|Orc

### Language ~ Auto (Kobold)

- **ABILITY:** Language|AUTOMATIC|Draconic

### Language ~ Bonus (Goblin)

- **TEMPLATE:** Language ~ Bonus (Goblin)

### Language ~ Bonus (Hobgoblin)

- **TEMPLATE:** Language ~ Bonus (Hobgoblin)

### Language ~ Bonus (Orc)

- **TEMPLATE:** Language ~ Bonus (Orc)

### Language ~ Bonus (Kobold)

- **TEMPLATE:** Language ~ Bonus (Kobold)

### Race Traits ~ Carrion Crawler

- **ABILITY:** Special Ability|AUTOMATIC|Carrion Crawler ~ Paralysis|Carrion Crawler ~ Skills|Scent

### Race Traits ~ Asperi

- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability|Uncanny Dodge ~ Base|TYPE=Asperi Race Trait
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** VAR|RaceSizeIsLong|1

### Dodge Arrows


A Flying Asperi gains a +2 dodge bonus to AC against any missile attack during any turn in which it takes a move action. If it has a rider, he or she also gains the bonus. The bonus lasts until the asperi's next turn.

### Feather Fall

- **SPELLS:** Innate|TIMES=4|CASTERLEVEL=4|Feather Fall

An asperi can use feather fall up to four times per day. Caster level 4th.

### Ride the Wind


This ability is similar to the effect of Air Walk spell in most respect.

### Wind Immunity


Winds have no effect on an asperi unless it chooses to ride them for additional movement (see Ride the Wind)

### Training


Training DC 22 (young) or 29 (adult) Handle Animal check. Require a normal saddle. Professional trainers charge 2000 gp to rear or train.

## Ability Categories

### ABILITYCATEGORY:Ability Focus

- **EDITABLE:** NO
- **EDITPOOL:** NO

### ABILITYCATEGORY:Ghost Ability

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Ghost Abilities
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Dragon Age

- **EDITABLE:** YES
- **EDITPOOL:** NO

### ABILITYCATEGORY:All Monster Domains

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Drider Caster Choice

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **ABILITYLIST:** Cleric Class|Wizard Class|Sorcerer Class
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Drider Domain

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **ABILITYLIST:** Chaos Domain|Destruction Domain|Evil Domain|Trickery Domain
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Lammasu Domain

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **ABILITYLIST:** Good Domain|Healing Domain|Knowledge Domain|Law Domain
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Animated Object Move

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Hydra Heads

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Kobold Race Trait

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **PLURAL:** Kobold Race Traits
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Hobgoblin Race Trait

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **PLURAL:** Hobgoblin Race Traits
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Orc Race Trait

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **PLURAL:** Orc Race Traits
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Goblin Race Trait

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **PLURAL:** Goblin Race Traits
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Goblin Subrace

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Hobgoblin Subrace

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Orc Subrace

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Kobold Subrace

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Aasimar Subrace

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Tiefling Subrace

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

### ABILITYCATEGORY:Lizardfolk Subrace

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Race Traits

## Classes

### CLASS:Planetar

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 42
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 1

- **BONUS:** PCLEVEL|Cleric|1
- **ADD:** SPELLCASTER|Cleric

### 2

- **BONUS:** PCLEVEL|Cleric|1

### 3

- **BONUS:** PCLEVEL|Cleric|1

### 4

- **BONUS:** PCLEVEL|Cleric|1

### 5

- **BONUS:** PCLEVEL|Cleric|1

### 6

- **BONUS:** PCLEVEL|Cleric|1

### 7

- **BONUS:** PCLEVEL|Cleric|1
- **BONUS:** PCLEVEL|Cleric|1

### 8

- **BONUS:** PCLEVEL|Cleric|1

### 9

- **BONUS:** PCLEVEL|Cleric|1

### 10

- **BONUS:** PCLEVEL|Cleric|1

### 11

- **BONUS:** PCLEVEL|Cleric|1

### 12

- **BONUS:** PCLEVEL|Cleric|1

### 13

- **BONUS:** PCLEVEL|Cleric|1

### 14

- **BONUS:** PCLEVEL|Cleric|1
- **BONUS:** PCLEVEL|Cleric|1

### CLASS:Solar

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 66
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 16

- **BONUS:** PCLEVEL|Cleric|1

### 17

- **BONUS:** PCLEVEL|Cleric|1

### 18

- **BONUS:** PCLEVEL|Cleric|1

### 19

- **BONUS:** PCLEVEL|Cleric|1

### 20

- **BONUS:** PCLEVEL|Cleric|1

### 21

- **BONUS:** PCLEVEL|Cleric|1

### 22

- **BONUS:** PCLEVEL|Cleric|1

### CLASS:Trumpet Archon

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 36
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Aranea

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 3
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Couatl

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 27
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Drider Cleric

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 6
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Drider Sorcerer

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 6
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Drider Wizard

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 6
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Formian Queen

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 40
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 15

- **BONUS:** PCLEVEL|Sorcerer|1

### CLASS:Ghaele

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 30
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Lammasu

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 21
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Lillend

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 21
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Dark Naga

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 27
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Guardian Naga

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 33
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Spirit Naga

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 27
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Water Naga

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 21
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Nymph

- **HD:** 6
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 12
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABPoor|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Rakshasa

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 7
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Androsphinx

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 36
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Lycanthrope (Generic)

- **HD:** 8
- **FACT:** ClassType|Monster

### CLASS:Lycanthrope (Werebear)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 6

### CLASS:Lycanthrope (Wereboar)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 3

### CLASS:Lycanthrope (Wererat)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 1

### CLASS:Lycanthrope (Weretiger)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 6

### CLASS:Lycanthrope (Werewolf)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 2

### CLASS:Lycanthrope (Dire Wereboar)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** 12

## Companion Modifiers

### FOLLOWER:HoundArchonSpecialMount=1

- **HD:** 2
- **ABILITY:** Special Ability|AUTOMATIC|Special Mount ~ Improved Evasion
- **PRERACE:** 1,Dragon (Bronze)
- **KIT:** 1|Bronze Dragon Companion
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor.STACK
- **BONUS:** MOVEADD|TYPE.Walk|10
- **BONUS:** MOVEADD|TYPE.Swim|10
- **BONUS:** MOVEADD|TYPE.Climb|10
- **BONUS:** MOVEADD|TYPE.Burrow|10
- **BONUS:** MOVEADD|TYPE.Fly|10
- **BONUS:** STAT|STR|4

## Equipment

### Giant Rock (Large)

- **PROFICIENCY:** WEAPON|Giant Rock
- **DAMAGE:** 2d6
- **RANGE:** 120
- **SIZE:** L
- **BONUS:** WEAPON|ATTACKSPROGRESS|-3

### Giant Rock (Huge)

- **PROFICIENCY:** WEAPON|Giant Rock
- **DAMAGE:** 2d8
- **RANGE:** 120
- **SIZE:** H
- **BONUS:** WEAPON|ATTACKSPROGRESS|-3

### Giant Rock (Fire Giant)

- **PROFICIENCY:** WEAPON|Giant Rock
- **DAMAGE:** 2d6
- **RANGE:** 120
- **SIZE:** L
- **BONUS:** WEAPON|ATTACKSPROGRESS|-3
- **SPROP:** +2d6 fire damage

### Giant Rock (Stone Giant)

- **PROFICIENCY:** WEAPON|Giant Rock
- **DAMAGE:** 2d8
- **RANGE:** 180
- **SIZE:** L
- **BONUS:** WEAPON|ATTACKSPROGRESS|-3

### Giant Rock (Cloud Giant)

- **PROFICIENCY:** WEAPON|Giant Rock
- **DAMAGE:** 2d8
- **RANGE:** 140
- **SIZE:** L
- **BONUS:** WEAPON|ATTACKSPROGRESS|-3

## Feats

### Ability Focus

- **PREABILITY:** 1,CATEGORY=Ability Focus,TYPE.Ability Focus
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** ABILITY|Ability Focus|PC,TYPE=Ability Focus

Add +2 to the DC for all saving throws against the special attack on which the creature focuses. Special: A creature can gain this feat multiple times. Its effects do not stack. Each time the creature takes the feat, it applies to a different special attack.

### Awesome Blow

- **PREABILITY:** 2,CATEGORY=FEAT,Power Attack,Improved Bull Rush
- **PRESIZEGTEQ:** L
- **PRESTAT:** 1,STR=25

As a standard action, the creature may choose to subtract 4 from its melee attack roll and deliver an awesome blow. If the creature hits a corporeal opponent smaller than itself with an awesome blow, its opponent must succeed on a Reflex save (DC = damage dealt) or be knocked flying 10 feet in a direction of the attacking creature's choice and fall prone. The attacking creature can only push the opponent in a straight line, and the opponent can't move closer to the attacking creature than the square it started in. If an obstacle prevents the completion of the opponent's move, the opponent and the obstacle each take 1d6 points of damage, and the opponent stops in the space adjacent to the obstacle.

### Craft Construct

- **PREABILITY:** 2,CATEGORY=FEAT,Craft Magic Arms and Armor,Craft Wondrous Item

A creature with this feat can create any construct whose prerequisites it meets. Enchanting a construct takes one day for each 1,000 gp in its market price. To enchant a construct, a spellcaster must spend 1/25 the item's price in XP and use up raw materials costing half of this price (see the Golem, Homunculus, and Shield Guardian monster entries for details). A creature with this feat can repair constructs that have taken damage. In one day of work, the creature can repair up to 20 points of damage by expending 50 gp per point of damage repaired. A newly created construct has average hit points for its Hit Dice.

### Empower Spell-Like Ability

- **PRETEXT:** Spell-like ability at caster level 6th or higher.
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** SPELLS|SPELLBOOK=Innate

Choose one of the creature's spell-like abilities, subject to the restrictions below. The creature can use that ability as an empowered spell-like ability three times per day (or less, if the ability is normally usable only once or twice per day). When a creature uses an empowered spell-like ability, all variable, numeric effects of the spell-like ability are increased by onehalf. An empowered spell-like ability does half again as much damage as normal, cures half again as many hit points, affects half again as many targets, and so on as appropriate. Saving throws and opposed rolls (such as the one made when a character casts dispel magic) are not affected. Spell-like abilities without random variables are not affected. The creature can only select a spell-like ability duplicating a spell with a level less than or equal to half its caster level (round down) -2. For a summary, see the table in the description of the Quicken Spell-Like Ability feat. For example, a creature that uses its spell-like abilities as a 13th-level caster can only empower spelllike abilities duplicating spells of 4th level or lower. Special: This feat can be taken multiple times. Each time it is taken, the creature can apply it to a different one of its spell-like abilites.

### Flyby Attack

- **PREMOVE:** 1,Fly=1

When flying, the creature can take a move action (including a dive) and another standard action at any point during the move. The creature cannot take a second move action during a round when it makes a flyby attack. Normal: Without this feat, the creature takes a standard action either before or after its move.

### Hover

- **PREMOVE:** 1,Fly=1

When flying, the creature can halt its forward motion and hover in place as a move action. It can then fly in any direction, including straight down or straight up, at half speed, regardless of its maneuverability. If a creature begins its turn hovering, it can hover in place for the turn and take a full-round action. A hovering creature cannot make wing attacks, but it can attack with all other limbs and appendages it could use in a full attack. The creature can instead use a breath weapon or cast a spell instead of making physical attacks, if it could normally do so. If a creature of Large size or larger hovers within 20 feet of the ground in an area with lots of loose debris, the draft from its wings creates a hemispherical cloud with a radius of 60 feet. The winds so generated can snuff torches, small campfires, exposed lanterns, and other small, open flames of nonmagical origin. Clear vision within the cloud is limited to 10 feet. Creatures have concealment at 15 to 20 feet (20%% miss chance). At 25 feet or more, creatures have total concealment (50%% miss chance, and opponents cannot use sight to locate the creature). Those caught in the cloud must succeed on a Concentration check (DC 10 + 1/2 creature's HD) to cast a spell. Normal: Without this feat, a creature must keep moving while flying unless it has perfect maneuverability.

### Improved Natural Armor

- **PRESTAT:** 1,CON=13
- **PREVARGTEQ:** BONUS.COMBAT.AC.NaturalArmor,1
- **STACK:** YES
- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor.STACK

The creature's natural armor bonus increases by 1. Special: A creature can gain this feat multiple times. Each time the creature takes the feat, its natural armor bonus increases by another point.

### Improved Natural Attack

- **PREWEAPONPROF:** 1,TYPE.Natural
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** WEAPONPROFICIENCY|PC,TYPE=Natural
- **BONUS:** WEAPONPROF=%LIST|DAMAGESIZE|1
- **PRETOTALAB:** 4

Choose one of the creature's natural attack forms. The damage for this natural weapon increases by one step, as if the creature's size had increased by one category: 1d2, 1d3, 1d4, 1d6, 1d8, 2d6, 3d6, 4d6, 6d6, 8d6, 12d6. A weapon or attack that deals 1d10 points of damage increases as follows: 1d10, 2d8, 3d8, 4d8, 6d8, 8d8, 12d8.

### Multiattack

- **BONUS:** COMBAT|TOHIT-SECONDARY|3

The creature's secondary attacks with natural weapons take only a -2 penalty. Normal: Without this feat, the creature's secondary attacks with natural weapons take a -5 penalty.

### Multiweapon Fighting

- **PREHANDSGTEQ:** 3
- **PRESTAT:** 1,DEX=13
- **BONUS:** COMBAT|TOHIT-PRIMARY|2
- **BONUS:** COMBAT|TOHIT-SECONDARY|6
- **SERVESAS:** ABILITY=FEAT|Two-Weapon Fighting

Penalties for fighting with multiple weapons are reduced by 2 with the primary hand and reduced by 6 with off hands. Normal: A creature without this feat takes a -6 penalty on attacks made with its primary hand and a -10 penalty on attacks made with its off hands. (It has one primary hand, and all the others are off hands.) See Two-Weapon Fighting, page 160 of the Player's Handbook.

### Quicken Spell-Like Ability

- **PRETEXT:** Spell-like ability at caster level 10th or higher.
- **STACK:** NO
- **MULT:** YES
- **CHOOSE:** SPELLS|SPELLBOOK=Innate

Choose one of the creature's spell-like abilities, subject to the restrictions described below. The creature can use that ability as a quickened spell-like ability three times per day (or less, if the ability is normally usable only once or twice per day). Using a quickened spell-like ability is a free action that does not provoke an attack of opportunity. The creature can perform another action-including the use of another spell-like ability-in the same round that it uses a quickened spell-like ability. The creature may use only one quickened spell-like ability per round. The creature can only select a spell-like ability duplicating a spell with a level less than or equal to half its caster level (round down) -4. For a summary, see the table below. For example, a creature that uses its spell-like abilities as a 15th-level caster can only quicken spell-like abilities duplicating spells of 3rd level or lower. In addition, a spell-like ability that duplicates a spell with a casting time greater than 1 full round cannot be quickened. Normal: Normally the use of a spell-like ability requires a standard action and provokes an attack of opportunity unless noted otherwise. Special: This feat can be taken multiple times. Each time it is taken, the creature can apply it to a different one of its spell-like abilities.

### Snatch

- **PRESIZEGTEQ:** H

The creature can choose to start a grapple when it hits with a claw or bite attack, as though it had the improved grab special attack. If the creature gets a hold on a creature three or more sizes smaller, it squeezes each round for automatic bite or claw damage. A snatched opponent held in the creature's mouth is not allowed a Reflex save against the creature's breath weapon, if it has one. The creature can drop a creature it has snatched as a free action or use a standard action to fling it aside. A flung creature travels 1d6x10 feet, and takes 1d6 points of damage per 10 feet traveled. If the creature flings a snatched opponent while flying, the opponent takes this amount or falling damage, whichever is greater.

### Wingover

- **PREMOVE:** 1,Fly=1

A flying creature with this feat can change direction quickly once each round as a free action. This feat allows it to turn up to 180 degrees regardless of its maneuverability, in addition to any other turns it is normally allowed. A creature cannot gain altitude during a round when it executes a wingover, but it can dive. The change of direction consumes 10 feet of flying movement.

## Kits

### STARTPACK:Giant Ant (Worker) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Ant (Worker)]

### RACE:Giant Ant (Worker)

- **!PRERACE:** 1,%

### NAME:Giant Worker Ant


### ALIGN:TN


### STAT:WIS=11|CHA=11|STR=10|DEX=10|CON=10|INT=10


### STARTPACK:Giant Ant (Soldier) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Ant (Soldier)]

### RACE:Giant Ant (Soldier)

- **!PRERACE:** 1,%

### NAME:Giant Soldier Ant


### STAT:CON=11|WIS=11|CHA=11|STR=10|DEX=10|INT=10


### STARTPACK:Giant Ant (Queen) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Ant (Queen)]

### RACE:Giant Ant (Queen)

- **!PRERACE:** 1,%

### NAME:Giant Ant Queen


### STAT:DEX=11|CON=11|WIS=11|CHA=11|STR=10|INT=10


### STARTPACK:Giant Bee Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Bee]

### RACE:Giant Bee

- **!PRERACE:** 1,%

### NAME:Giant Bee


### STAT:STR=11|CON=11|CHA=11|DEX=10|INT=10|WIS=10


### STARTPACK:Giant Bombardier Beetle Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Bombardier Beetle]

### RACE:Giant Bombardier Beetle

- **!PRERACE:** 1,%

### NAME:Giant Bombardier Beetle


### STAT:STR=11|CHA=11|DEX=10|CON=10|INT=10|WIS=10


### STARTPACK:Giant Fire Beetle Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Fire Beetle]

### RACE:Giant Fire Beetle

- **!PRERACE:** 1,%

### NAME:Giant Fire Beetle


### STAT:DEX=11|CON=11|CHA=11|STR=10|INT=10|WIS=10


### STARTPACK:Giant Praying Mantis Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Praying Mantis]

### RACE:Giant Praying Mantis

- **!PRERACE:** 1,%

### NAME:Giant Praying Mantis


### STARTPACK:Giant Stag Beetle Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Stag Beetle]

### RACE:Giant Stag Beetle

- **!PRERACE:** 1,%

### NAME:Giant Stag Beetle


### STARTPACK:Giant Wasp Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant Wasp]

### RACE:Giant Wasp

- **!PRERACE:** 1,%

### NAME:Giant Wasp


### STARTPACK:Monstrous Centipede (Tiny) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Centipede (Tiny)]

### RACE:Monstrous Centipede (Tiny)

- **!PRERACE:** 1,%

### NAME:Tiny Monstrous Centipede


### STAT:DEX=11|STR=10|CON=10|INT=10|WIS=10|CHA=10


### STARTPACK:Monstrous Centipede (Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Centipede (Small)]

### RACE:Monstrous Centipede (Small)

- **!PRERACE:** 1,%

### NAME:Small Monstrous Centipede


### STAT:STR=11|DEX=11|CON=10|INT=10|WIS=10|CHA=10


### STARTPACK:Monstrous Centipede (Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Centipede (Medium)]

### RACE:Monstrous Centipede (Medium)

- **!PRERACE:** 1,%

### NAME:Medium Monstrous Centipede


### STARTPACK:Monstrous Centipede (Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Centipede (Large)]

### RACE:Monstrous Centipede (Large)

- **!PRERACE:** 1,%

### NAME:Large Monstrous Centipede


### STARTPACK:Monstrous Centipede (Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Centipede (Huge)]

### RACE:Monstrous Centipede (Huge)

- **!PRERACE:** 1,%

### NAME:Huge Monstrous Centipede


### STARTPACK:Monstrous Centipede (Colossal) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Centipede (Colossal)]

### RACE:Monstrous Centipede (Colossal)

- **!PRERACE:** 1,%

### NAME:Colossal Monstrous Centipede


### STARTPACK:Monstrous Centipede (Gargantuan) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Centipede (Gargantuan)]

### RACE:Monstrous Centipede (Gargantuan)

- **!PRERACE:** 1,%

### NAME:Gargantuan Monstrous Centipede


### STARTPACK:Monstrous Scorpion (Tiny) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Scorpion (Tiny)]

### RACE:Monstrous Scorpion (Tiny)

- **!PRERACE:** 1,%

### NAME:Tiny Monstrous Scorpion


### STAT:STR=11|DEX=10|CON=10|INT=10|WIS=10|CHA=10


### STARTPACK:Monstrous Scorpion (Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Scorpion (Small)]

### RACE:Monstrous Scorpion (Small)

- **!PRERACE:** 1,%

### NAME:Small Monstrous Scorpion


### STARTPACK:Monstrous Scorpion (Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Scorpion (Medium)]

### RACE:Monstrous Scorpion (Medium)

- **!PRERACE:** 1,%

### NAME:Medium Monstrous Scorpion


### STARTPACK:Monstrous Scorpion (Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Scorpion (Large)]

### RACE:Monstrous Scorpion (Large)

- **!PRERACE:** 1,%

### NAME:Large Monstrous Scorpion


### STARTPACK:Monstrous Scorpion (Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Scorpion (Huge)]

### RACE:Monstrous Scorpion (Huge)

- **!PRERACE:** 1,%

### NAME:Huge Monstrous Scorpion


### STARTPACK:Monstrous Scorpion (Colossal) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Scorpion (Colossal)]

### RACE:Monstrous Scorpion (Colossal)

- **!PRERACE:** 1,%

### NAME:Colossal Monstrous Scorpion


### STARTPACK:Monstrous Scorpion (Gargantuan) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Scorpion (Gargantuan)]

### RACE:Monstrous Scorpion (Gargantuan)

- **!PRERACE:** 1,%

### NAME:Gargantuan Monstrous Scorpion


### STARTPACK:Monstrous Spider (Tiny) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Spider (Tiny)]

### RACE:Monstrous Spider (Tiny)

- **!PRERACE:** 1,%

### NAME:Tiny Monstrous Spider


### STARTPACK:Monstrous Spider (Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Spider (Small)]

### RACE:Monstrous Spider (Small)

- **!PRERACE:** 1,%

### NAME:Small Monstrous Spider


### STARTPACK:Monstrous Spider (Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Spider (Medium)]

### RACE:Monstrous Spider (Medium)

- **!PRERACE:** 1,%

### NAME:Medium Monstrous Spider


### STARTPACK:Monstrous Spider (Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Spider (Large)]

### RACE:Monstrous Spider (Large)

- **!PRERACE:** 1,%

### NAME:Large Monstrous Spider


### STARTPACK:Monstrous Spider (Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Spider (Huge)]

### RACE:Monstrous Spider (Huge)

- **!PRERACE:** 1,%

### NAME:Huge Monstrous Spider


### STARTPACK:Monstrous Spider (Colossal) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Spider (Colossal)]

### RACE:Monstrous Spider (Colossal)

- **!PRERACE:** 1,%

### NAME:Colossal Monstrous Spider


### STARTPACK:Monstrous Spider (Gargantuan) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Spider (Gargantuan)]

### RACE:Monstrous Spider (Gargantuan)

- **!PRERACE:** 1,%

### NAME:Gargantuan Monstrous Spider


### STARTPACK:Aboleth Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Aboleth]

### ALIGN:LE


### RACE:Aboleth

- **!PRERACE:** 1,%

### NAME:Aboleth


### SKILL:Concentration

- **RANK:** 11

### SKILL:Listen

- **RANK:** 11

### SKILL:Spot

- **RANK:** 11

### SKILL:TYPE=Knowledge

- **RANK:** 11

### ABILITY:CATEGORY=FEAT|Alertness


### ABILITY:CATEGORY=FEAT|Combat Casting


### ABILITY:CATEGORY=FEAT|Iron Will


### STAT:INT=11|WIS=11|CHA=11|STR=10|DEX=10|CON=10


### STARTPACK:Achaierai Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Achaierai]

### STAT:STR=11|DEX=11|INT=11|CON=10|WIS=10|CHA=10


### RACE:Achaierai

- **!PRERACE:** 1,%

### NAME:Achaierai


### SKILL:Balance

- **RANK:** 9

### SKILL:Climb

- **RANK:** 9

### SKILL:Hide

- **RANK:** 9

### SKILL:Move Silently

- **RANK:** 9

### SKILL:Sense Motive

- **RANK:** 9

### SKILL:Jump

- **RANK:** 9

### ABILITY:CATEGORY=FEAT|Dodge


### ABILITY:CATEGORY=FEAT|Mobility


### ABILITY:CATEGORY=FEAT|Spring Attack


### STARTPACK:Allip Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Allip]

### STAT:INT=10|WIS=11|STR=10|DEX=10|CON=10|CHA=10


### RACE:Allip

- **!PRERACE:** 1,%

### NAME:Allip


### ALIGN:NE


### SKILL:Search

- **RANK:** 4

### SKILL:Intimidate

- **RANK:** 3

### ABILITY:CATEGORY=FEAT|Improved Initiative


### ABILITY:CATEGORY=FEAT|Lightning Reflexes


### STARTPACK:Angel (Astral Deva) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Angel (Astral Deva)]

### STAT:INT=10|WIS=10|STR=10|DEX=10|CON=10|CHA=10


### RACE:Angel (Astral Deva)

- **!PRERACE:** 1,%

### NAME:Astral Deva


### ALIGN:LG|NG|CG


### SKILL:Diplomacy

- **RANK:** 15

### SKILL:Escape Artist

- **RANK:** 15

### SKILL:TYPE=Knowledge|TYPE=Craft

- **RANK:** 15
- **COUNT:** 3

### ABILITY:CATEGORY=FEAT|Cleave


### ABILITY:CATEGORY=FEAT|Great Fortitude


### ABILITY:CATEGORY=FEAT|Power Attack


### GEAR:Mace (Heavy)

- **SIZE:** PC
- **LOCATION:** Both Hands
- **EQMOD:** Masterwork (Weapon).PLUS3W.DISRPT

### STARTPACK:Angel (Planetar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Angel (Planetar)]

### STAT:STR=11|DEX=11|WIS=11|CON=10|INT=10|CHA=10


### RACE:Angel (Planetar)

- **!PRERACE:** 1,%

### NAME:Planetar


### ABILITY:CATEGORY=FEAT|Blind-Fight


### ABILITY:CATEGORY=FEAT|Improved Sunder


### GEAR:Greatsword

- **SIZE:** PC
- **LOCATION:** Both Hands
- **EQMOD:** Masterwork (Weapon).PLUS3W

### DEITY:None

- **DOMAIN:** Destruction|Good

### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Aid|Align Weapon|Banishment|Bear's Endurance|Bless=2|Break Enchantment|Bull's Strength=2|Cause Fear|Consecrate|Contagion|Create Water|Cure Critical Wounds (Mass)|Cure Moderate Wounds (Mass)|Daylight|Death Ward|Detect Magic|Dictum|Disintegrate|Dismissal|Dispel Evil|Dispel Magic (Greater)|Divine Favor=2|Doom|Eagle's Splendor|Entropic Shield|Guidance|Harm|Heal|Heroes' Feast|Hold Person|Holy Aura|Holy Word|Implosion|Inflict Critical Wounds|Inflict Light Wounds|Invisibility Purge|Mark of Justice|Neutralize Poison=2|Plane Shift|Prayer=2|Regenerate|Resistance=2|Righteous Might|Shield of Faith|Shield of Law|Summon Monster III|Summon Monster IV|Summon Monster IX|Virtue|Wind Wall


### STARTPACK:Angel (Solar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Angel (Solar)]

### RACE:Angel (Solar)

- **!PRERACE:** 1,%

### NAME:Solar


### SKILL:Spellcraft

- **RANK:** 21

### ABILITY:CATEGORY=FEAT|Great Cleave


### ABILITY:CATEGORY=FEAT|Track


### GEAR:Longbow (Composite)

- **SIZE:** PC
- **LOCATION:** Carried
- **EQMOD:** Masterwork (Weapon).PLUS2W.BOWSTR|5

### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Align Weapon|Banishment|Bear's Endurance=2|Bless=2|Break Enchantment|Bull's Strength=2|Cause Fear|Chain Lightning|Consecrate|Control Weather|Control Winds|Create Water|Cure Critical Wounds (Mass)=2|Cure Moderate Wounds (Mass)|Daylight|Death Ward=2|Destruction|Detect Magic|Dictum|Dismissal=2|Dispel Evil|Divine Favor=2|Divine Power|Eagle's Splendor|Elemental Swarm|Entropic Shield|Ethereal Jaunt|Etherealness|Fire Storm|Guidance=2|Heal (Mass)|Heroes' Feast|Holy Aura|Holy Word|Invisibility Purge|Magic Circle against Evil|Magic Vestment|Miracle|Neutralize Poison=2|Obscuring Mist|Plane Shift|Prayer=2|Protection from Energy|Regenerate|Resistance=2|Righteous Might=2|Shield of Faith|Spiritual Weapon|Storm of Vengeance|Symbol of Pain|Undeath to Death|Whirlwind|Wind Wall|Word of Recall


### STARTPACK:Animated Object (Tiny) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Animated Object (Tiny)]

### RACE:Animated Object (Tiny)

- **!PRERACE:** 1,%

### NAME:Tiny Animated Object


### STARTPACK:Animated Object (Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Animated Object (Small)]

### RACE:Animated Object (Small)

- **!PRERACE:** 1,%

### NAME:Small Animated Object


### STARTPACK:Animated Object (Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Animated Object (Medium)]

### RACE:Animated Object (Medium)

- **!PRERACE:** 1,%

### NAME:Medium Animated Object


### STARTPACK:Animated Object (Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Animated Object (Large)]

### RACE:Animated Object (Large)

- **!PRERACE:** 1,%

### NAME:Large Animated Object


### STARTPACK:Animated Object (Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Animated Object (Huge)]

### RACE:Animated Object (Huge)

- **!PRERACE:** 1,%

### NAME:Huge Animated Object


### STARTPACK:Animated Object (Gargantuan) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Animated Object (Gargantuan)]

### RACE:Animated Object (Gargantuan)

- **!PRERACE:** 1,%

### NAME:Gargantuan Animated Object


### STARTPACK:Animated Object (Colossal) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Animated Object (Colossal)]

### RACE:Animated Object (Colossal)

- **!PRERACE:** 1,%

### NAME:Colossal Animated Object


### STARTPACK:Ankheg Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ankheg]

### RACE:Ankheg

- **!PRERACE:** 1,%

### NAME:Ankheg


### ABILITY:CATEGORY=FEAT|Toughness


### STAT:STR=11|CON=11|WIS=11|DEX=10|INT=10|CHA=10


### STARTPACK:Aranea Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Aranea]

### RACE:Aranea

- **!PRERACE:** 1,%

### NAME:Aranea


### ABILITY:CATEGORY=FEAT|Weapon Finesse


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Daze|Detect Magic|Ghost Sound|Light|Mage Armor|Resistance|Silent Image|Sleep


### STARTPACK:Archon (Hound Archon) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Archon (Hound Archon)]

### RACE:Archon (Hound Archon)

- **!PRERACE:** 1,%

### NAME:Hound Archon


### ALIGN:LG


### SKILL:Survival

- **RANK:** 9

### STARTPACK:Archon (Lantern Archon) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Archon (Lantern Archon)]

### RACE:Archon (Lantern Archon)

- **!PRERACE:** 1,%

### NAME:Lantern Archon


### SKILL:Knowledge (The Planes)

- **RANK:** 4

### STAT:DEX=11|WIS=11|STR=10|CON=10|INT=10|CHA=10


### STARTPACK:Archon (Trumpet Archon) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Archon (Trumpet Archon)]

### RACE:Archon (Trumpet Archon)

- **!PRERACE:** 1,%

### NAME:Trumpet Archon


### SKILL:Ride

- **RANK:** 15

### SKILL:Handle Animal

- **RANK:** 15

### SKILL:Perform (Wind Instruments)

- **RANK:** 15

### ABILITY:CATEGORY=FEAT|Combat Reflexes


### STAT:DEX=11|CON=11|STR=10|INT=10|WIS=10|CHA=10


### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Aid|Banishment|Blade Barrier|Bless=2|Bull's Strength=2|Consecrate|Cure Light Wounds (Mass)|Cure Serious Wounds (Mass)|Daylight|Detect Magic|Dictum|Dismissal|Dispel Evil|Divine Favor=2|Divine Power|Heal|Holy Smite|Holy Word|Invisibility Purge|Light|Magic Circle against Chaos|Magic Vestment|Neutralize Poison|Owl's Wisdom=2|Plane Shift|Protection from Chaos|Protection from Energy=2|Purify Food and Drink|Raise Dead|Read Magic|Resistance=2|Restoration (Lesser)|Sanctuary|Shield of Faith|Spell Immunity|Undeath to Death


### STARTPACK:Arrowhawk (Adult) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Arrowhawk (Adult)]

### RACE:Arrowhawk (Adult)

- **!PRERACE:** 1,%

### NAME:Adult Arrowhawk


### ABILITY:CATEGORY=FEAT|Flyby Attack


### STAT:DEX=11|WIS=11|CHA=11|STR=10|CON=10|INT=10


### STARTPACK:Arrowhawk (Elder) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Arrowhawk (Elder)]

### RACE:Arrowhawk (Elder)

- **!PRERACE:** 1,%

### NAME:Elder Arrowhawk


### STARTPACK:Arrowhawk (Juvenile) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Arrowhawk (Juvenile)]

### RACE:Arrowhawk (Juvenile)

- **!PRERACE:** 1,%

### NAME:Juvenile Arrowhawk


### STARTPACK:Assassin Vine Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Assassin Vine]

### RACE:Assassin Vine

- **!PRERACE:** 1,%

### NAME:Assassin Vine


### STARTPACK:Athach Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Athach]

### ALIGN:CE


### RACE:Athach

- **!PRERACE:** 1,%

### NAME:Athach


### ABILITY:CATEGORY=FEAT|Multiweapon Fighting


### ABILITY:CATEGORY=FEAT|Weapon Focus(Bite)


### STAT:DEX=11|CON=11|INT=11|STR=10|WIS=10|CHA=10


### GEAR:Morningstar

- **SIZE:** PC
- **LOCATION:** Primary Hand

### GEAR:Hide

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Avoral Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Guardinal (Avoral)]

### RACE:Guardinal (Avoral)

- **!PRERACE:** 1,%

### NAME:Avoral


### ALIGN:NG


### SKILL:Bluff

- **RANK:** 10

### ABILITY:CATEGORY=FEAT|Empower Spell-Like Ability(Magic Missile)


### STARTPACK:Azer Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Azer]

### RACE:Azer

- **!PRERACE:** 1,%

### NAME:Azer


### ALIGN:LN


### SKILL:Appraise

- **RANK:** 5

### SKILL:TYPE=Craft

- **RANK:** 5
- **COUNT:** 2

### STAT:STR=11|DEX=11|CON=11|CHA=11|INT=10|WIS=10


### GEAR:Shield (Heavy/Wood)

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Scale Mail

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Shortspear

- **SIZE:** PC
- **LOCATION:** Carried

### GEAR:Warhammer

- **SIZE:** PC
- **LOCATION:** Primary Hand

### STARTPACK:Barghest Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Barghest]

### RACE:Barghest

- **!PRERACE:** 1,%

### NAME:Barghest


### STAT:STR=11|DEX=11|CON=11|INT=10|WIS=10|CHA=10


### STARTPACK:Barghest (Greater) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Barghest (Greater)]

### RACE:Barghest (Greater)

- **!PRERACE:** 1,%

### NAME:Greater Barghest


### SKILL:Tumble

- **RANK:** 12

### STARTPACK:Basilisk Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Basilisk]

### RACE:Basilisk

- **!PRERACE:** 1,%

### NAME:Basilisk


### STARTPACK:Basilisk (Abyssal/Greater) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Basilisk]

### RACE:Basilisk (Abyssal/Greater)

- **!PRERACE:** 1,%

### NAME:Abyssal Greater Basilisk


### ABILITY:CATEGORY=FEAT|Improved Natural Attack(Bite)


### STAT:STR=10|CON=11|CHA=11|DEX=10|INT=11|WIS=10


### STARTPACK:Behir Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Behir]

### RACE:Behir

- **!PRERACE:** 1,%

### NAME:Behir


### STARTPACK:Belker Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Belker]

### RACE:Belker

- **!PRERACE:** 1,%

### NAME:Belker


### ABILITY:CATEGORY=FEAT|Multiattack


### STARTPACK:Blink Dog Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Blink Dog]

### RACE:Blink Dog

- **!PRERACE:** 1,%

### NAME:Blink Dog


### ABILITY:CATEGORY=FEAT|Run


### STARTPACK:Bodak Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bodak]

### RACE:Bodak

- **!PRERACE:** 1,%

### NAME:Bodak


### ABILITY:CATEGORY=FEAT|Weapon Focus(Slam)


### STARTPACK:Bralani Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Eladrin (Bralani)]

### RACE:Eladrin (Bralani)

- **!PRERACE:** 1,%

### NAME:Bralani


### ALIGN:CG


### STAT:CON=11|INT=11|STR=10|DEX=10|WIS=10|CHA=10


### GEAR:Scimitar

- **SIZE:** PC
- **LOCATION:** Primary Hand
- **EQMOD:** Masterwork (Weapon).PLUS1W.HOLY_M

### STARTPACK:Bugbear Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bugbear]

### RACE:Bugbear

- **!PRERACE:** 1,%

### NAME:Bugbear


### ABILITY:CATEGORY=FEAT|Weapon Focus(Morningstar)


### GEAR:Javelin

- **SIZE:** PC
- **LOCATION:** Carried

### GEAR:Leather

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Shield (Light/Wood)

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Bulette Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bulette]

### RACE:Bulette

- **!PRERACE:** 1,%

### NAME:Bulette


### STARTPACK:Centaur Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Centaur]

### RACE:Centaur

- **!PRERACE:** 1,%

### NAME:Centaur


### ABILITY:CATEGORY=FEAT|Weapon Focus(Hoof)


### GEAR:Longsword

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Chaos Beast Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Chaos Beast]

### RACE:Chaos Beast

- **!PRERACE:** 1,%

### NAME:Chaos Beast


### ALIGN:CN


### STARTPACK:Chimera Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Chimera]

### RACE:Chimera

- **!PRERACE:** 1,%

### NAME:Chimera


### ABILITY:CATEGORY=FEAT|Hover


### STAT:STR=11|DEX=11|CON=11|WIS=11|INT=10|CHA=10


### STARTPACK:Choker Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Choker]

### RACE:Choker

- **!PRERACE:** 1,%

### NAME:Choker


### ABILITY:CATEGORY=FEAT|Stealthy


### STARTPACK:Chuul Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Chuul]

### RACE:Chuul

- **!PRERACE:** 1,%

### NAME:Chuul


### STAT:CHA=11|STR=10|DEX=10|CON=10|INT=10|WIS=10


### STARTPACK:Cloaker Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Cloaker]

### RACE:Cloaker

- **!PRERACE:** 1,%

### NAME:Cloaker


### STAT:STR=11|CON=11|WIS=11|CHA=11|DEX=10|INT=10


### STARTPACK:Cockatrice Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Cockatrice]

### RACE:Cockatrice

- **!PRERACE:** 1,%

### NAME:Cockatrice


### STARTPACK:Couatl Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Couatl]

### RACE:Couatl

- **!PRERACE:** 1,%

### NAME:Couatl


### SKILL:Use Magic Device

- **RANK:** 12

### ABILITY:CATEGORY=FEAT|Empower Spell


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Charm Monster|Cure Minor Wounds|Cure Moderate Wounds|Daze|Disrupt Undead|Eagle's Splendor|Endure Elements|Freedom of Movement|Gaseous Form|Light|Mage Armor|Magic Circle against Evil|Obscuring Mist|Protection from Chaos|Ray of Frost|Read Magic|Resistance|Scorching Ray|Silence|Summon Monster III|True Strike|Wind Wall


### STARTPACK:Darkmantle Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Darkmantle]

### RACE:Darkmantle

- **!PRERACE:** 1,%

### NAME:Darkmantle


### STAT:CON=11|STR=10|DEX=10|INT=10|WIS=10|CHA=10


### STARTPACK:Delver Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Delver]

### RACE:Delver

- **!PRERACE:** 1,%

### NAME:Delver


### SKILL:Knowledge (Dungeoneering)

- **RANK:** 12

### STARTPACK:Demon (Babau) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Babau)]

### RACE:Demon (Babau)

- **!PRERACE:** 1,%

### NAME:Babau


### SKILL:Disable Device

- **RANK:** 10

### SKILL:Disguise

- **RANK:** 10

### SKILL:Open Lock

- **RANK:** 10

### SKILL:Sleight of Hand

- **RANK:** 10

### STAT:STR=11|WIS=11|DEX=10|CON=10|INT=10|CHA=10


### STARTPACK:Demon (Balor) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Balor)]

### RACE:Demon (Balor)

- **!PRERACE:** 1,%

### NAME:Balor


### ABILITY:CATEGORY=FEAT|Improved Two-Weapon Fighting


### ABILITY:CATEGORY=FEAT|Quicken Spell-Like Ability(Telekinesis)


### ABILITY:CATEGORY=FEAT|Two-Weapon Fighting


### ABILITY:CATEGORY=FEAT|Weapon Focus(Longsword)


### GEAR:Whip

- **SIZE:** PC
- **LOCATION:** Secondary Hand
- **EQMOD:** Masterwork (Weapon).PLUS1W.FLM_M

### STARTPACK:Demon (Bebilith) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Bebilith)]

### RACE:Demon (Bebilith)

- **!PRERACE:** 1,%

### NAME:Bebilith


### ABILITY:CATEGORY=FEAT|Improved Grapple


### STARTPACK:Demon (Dretch) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Dretch)]

### RACE:Demon (Dretch)

- **!PRERACE:** 1,%

### NAME:Dretch


### STARTPACK:Demon (Glabrezu) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Glabrezu)]

### RACE:Demon (Glabrezu)

- **!PRERACE:** 1,%

### NAME:Glabrezu


### ABILITY:CATEGORY=FEAT|Persuasive


### STAT:STR=11|CON=11|DEX=10|INT=10|WIS=10|CHA=10


### STARTPACK:Demon (Hezrou) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Hezrou)]

### RACE:Demon (Hezrou)

- **!PRERACE:** 1,%

### NAME:Hezrou


### STARTPACK:Demon (Marilith) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Marilith)]

### RACE:Demon (Marilith)

- **!PRERACE:** 1,%

### NAME:Marilith


### ABILITY:CATEGORY=FEAT|Combat Expertise


### STARTPACK:Demon (Nalfeshnee) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Nalfeshnee)]

### RACE:Demon (Nalfeshnee)

- **!PRERACE:** 1,%

### NAME:Nalfeshnee


### SKILL:Knowledge (Arcana)

- **RANK:** 17

### ABILITY:CATEGORY=FEAT|Improved Bull Rush


### STARTPACK:Demon (Quasit) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Quasit)]

### RACE:Demon (Quasit)

- **!PRERACE:** 1,%

### NAME:Quasit


### STARTPACK:Demon (Retriever) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Retriever)]

### RACE:Demon (Retriever)

- **!PRERACE:** 1,%

### NAME:Retriever


### STARTPACK:Demon (Succubus) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Succubus)]

### RACE:Demon (Succubus)

- **!PRERACE:** 1,%

### NAME:Succubus


### STARTPACK:Demon (Vrock) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Vrock)]

### RACE:Demon (Vrock)

- **!PRERACE:** 1,%

### NAME:Vrock


### STARTPACK:Derro Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Derro]

### RACE:Derro

- **!PRERACE:** 1,%

### NAME:Derro


### GEAR:Buckler

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Crossbow (Repeating Light)

- **SIZE:** PC
- **LOCATION:** Carried

### GEAR:Sword (Short)

- **SIZE:** PC
- **LOCATION:** Primary Hand

### GEAR:Studded Leather

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Destrachan Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Destrachan]

### RACE:Destrachan

- **!PRERACE:** 1,%

### NAME:Destrachan


### STARTPACK:Devil (Barbed (Hamatula)) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Barbed (Hamatula))]

### RACE:Devil (Barbed (Hamatula))

- **!PRERACE:** 1,%

### NAME:Barbed Devil (Hamatula)


### STARTPACK:Devil (Bearded (Barbazu)) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Bearded (Barbazu))]

### RACE:Devil (Bearded (Barbazu))

- **!PRERACE:** 1,%

### NAME:Bearded Devil (Barbazu)


### ABILITY:CATEGORY=FEAT|Weapon Focus(Glaive)


### GEAR:Glaive

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Devil (Bone (Osyluth)) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Bone (Osyluth))]

### RACE:Devil (Bone (Osyluth))

- **!PRERACE:** 1,%

### NAME:Bone Devil (Osyluth)


### STARTPACK:Devil (Chain (Kyton)) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Chain (Kyton))]

### RACE:Devil (Chain (Kyton))

- **!PRERACE:** 1,%

### NAME:Chain Devil (Kyton)


### SKILL:Craft (Blacksmithing)

- **RANK:** 11

### ABILITY:CATEGORY=FEAT|Improved Critical(Chain)


### STARTPACK:Devil (Erinyes) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Erinyes)]

### RACE:Devil (Erinyes)

- **!PRERACE:** 1,%

### NAME:Erinyes


### ABILITY:CATEGORY=FEAT|Point Blank Shot


### ABILITY:CATEGORY=FEAT|Precise Shot


### ABILITY:CATEGORY=FEAT|Rapid Shot


### ABILITY:CATEGORY=FEAT|Shot on the Run


### GEAR:Rope (Hempen/50 Ft.)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Devil (Hellcat (Bezekira)) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Hellcat (Bezekira))]

### RACE:Devil (Hellcat (Bezekira))

- **!PRERACE:** 1,%

### NAME:Hellcat (Bezekira)


### SKILL:Swim

- **RANK:** 11

### STARTPACK:Devil (Horned (Cornugon)) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Horned (Cornugon))]

### RACE:Devil (Horned (Cornugon))

- **!PRERACE:** 1,%

### NAME:Horned Devil (Cornugon)


### ABILITY:CATEGORY=FEAT|Weapon Focus(Chain (Spiked))


### GEAR:Chain (Spiked)

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Devil (Ice (Gelugon)) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Ice (Gelugon))]

### RACE:Devil (Ice (Gelugon))

- **!PRERACE:** 1,%

### NAME:Ice Devil (Gelugon)


### ABILITY:CATEGORY=FEAT|Weapon Focus(Spear)


### GEAR:Spear

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Devil (Imp) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Imp)]

### RACE:Devil (Imp)

- **!PRERACE:** 1,%

### NAME:Imp


### STARTPACK:Devil (Lemure) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Lemure)]

### RACE:Devil (Lemure)

- **!PRERACE:** 1,%

### NAME:Lemure


### STARTPACK:Devil (Pit Fiend) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Pit Fiend)]

### RACE:Devil (Pit Fiend)

- **!PRERACE:** 1,%

### NAME:Pit Fiend


### SKILL:Knowledge (Religion)

- **RANK:** 21

### SKILL:Knowledge (Nature)

- **RANK:** 2

### ABILITY:CATEGORY=FEAT|Quicken Spell-Like Ability(Fireball)


### STARTPACK:Devourer Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devourer]

### RACE:Devourer

- **!PRERACE:** 1,%

### NAME:Devourer


### ABILITY:CATEGORY=FEAT|Weapon Focus(Claw)


### STARTPACK:Digester Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Digester]

### RACE:Digester

- **!PRERACE:** 1,%

### NAME:Digester


### STARTPACK:Dinosaur (Deinonychus) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Deinonychus)]

### RACE:Dinosaur (Deinonychus)

- **!PRERACE:** 1,%

### NAME:Deinonychus


### STARTPACK:Dinosaur (Elasmosaurus) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Elasmosaurus)]

### RACE:Dinosaur (Elasmosaurus)

- **!PRERACE:** 1,%

### NAME:Elasmosaurus


### STARTPACK:Dinosaur (Megaraptor) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Megaraptor)]

### RACE:Dinosaur (Megaraptor)

- **!PRERACE:** 1,%

### NAME:Megaraptor


### STARTPACK:Dinosaur (Triceratops) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Triceratops)]

### RACE:Dinosaur (Triceratops)

- **!PRERACE:** 1,%

### NAME:Triceratops


### STARTPACK:Dinosaur (Tyrannosaurus) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Tyrannosaurus)]

### RACE:Dinosaur (Tyrannosaurus)

- **!PRERACE:** 1,%

### NAME:Tyrannosaurus


### STAT:CON=11|WIS=11|STR=10|DEX=10|INT=10|CHA=10


### STARTPACK:Dire Animal (Dire Ape) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Ape)]

### RACE:Dire Animal (Dire Ape)

- **!PRERACE:** 1,%

### NAME:Dire Ape


### STAT:DEX=11|CHA=11|STR=10|CON=10|INT=10|WIS=10


### STARTPACK:Dire Animal (Dire Badger) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Badger)]

### RACE:Dire Animal (Dire Badger)

- **!PRERACE:** 1,%

### NAME:Dire Badger


### STARTPACK:Dire Animal (Dire Bat) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Bat)]

### RACE:Dire Animal (Dire Bat)

- **!PRERACE:** 1,%

### NAME:Dire Bat


### STARTPACK:Dire Animal (Dire Bear) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Bear)]

### RACE:Dire Animal (Dire Bear)

- **!PRERACE:** 1,%

### NAME:Dire Bear


### ABILITY:CATEGORY=FEAT|Endurance


### STARTPACK:Dire Animal (Dire Boar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Boar)]

### RACE:Dire Animal (Dire Boar)

- **!PRERACE:** 1,%

### NAME:Dire Boar


### STARTPACK:Dire Animal (Dire Lion) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Lion)]

### RACE:Dire Animal (Dire Lion)

- **!PRERACE:** 1,%

### NAME:Dire Lion


### STARTPACK:Dire Animal (Dire Rat) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Rat)]

### RACE:Dire Animal (Dire Rat)

- **!PRERACE:** 1,%

### NAME:Dire Rat


### STARTPACK:Dire Animal (Dire Shark) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Shark)]

### RACE:Dire Animal (Dire Shark)

- **!PRERACE:** 1,%

### NAME:Dire Shark


### STARTPACK:Dire Animal (Dire Tiger) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Tiger)]

### RACE:Dire Animal (Dire Tiger)

- **!PRERACE:** 1,%

### NAME:Dire Tiger


### ABILITY:CATEGORY=FEAT|Improved Natural Attack(Claw)


### STARTPACK:Dire Animal (Dire Weasel) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Weasel)]

### RACE:Dire Animal (Dire Weasel)

- **!PRERACE:** 1,%

### NAME:Dire Weasel


### STARTPACK:Dire Animal (Dire Wolf) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Wolf)]

### RACE:Dire Animal (Dire Wolf)

- **!PRERACE:** 1,%

### NAME:Dire Wolf


### STARTPACK:Dire Animal (Dire Wolverine) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Wolverine)]

### RACE:Dire Animal (Dire Wolverine)

- **!PRERACE:** 1,%

### NAME:Dire Wolverine


### STARTPACK:Doppelganger Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Doppelganger]

### RACE:Doppelganger

- **!PRERACE:** 1,%

### NAME:Doppelganger


### STAT:DEX=11|INT=11|CHA=11|STR=10|CON=10|WIS=10


### STARTPACK:Dragon Turtle Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dragon Turtle]

### RACE:Dragon Turtle

- **!PRERACE:** 1,%

### NAME:Dragon Turtle


### ABILITY:CATEGORY=FEAT|Snatch


### STARTPACK:Dragonne Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dragonne]

### RACE:Dragonne

- **!PRERACE:** 1,%

### NAME:Dragonne


### STARTPACK:Drider Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Drider (Cleric)]

### GEAR:Dagger

- **SIZE:** PC
- **LOCATION:** Primary Hand

### GEAR:Shortbow

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Drider (Cleric) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Drider]

### ABILITY:CATEGORY=Turn Undead|Rebuke Undead


### KIT:Drider Default


### ABILITY:CATEGORY=Drider Caster Choice|Cleric Class


### STARTPACK:Drider (Sorcerer) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Drider]

### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Daze|Detect Magic|Ghost Sound|Mage Hand|Ray of Frost|Read Magic|Resistance|Mage Armor|Magic Missile|Ray of Enfeeblement|Silent Image|Invisibility|Web|Lightning Bolt


### ABILITY:CATEGORY=Drider Caster Choice|Sorcerer Class


### STARTPACK:Drider (Wizard) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Drider]

### ABILITY:CATEGORY=Drider Caster Choice|Wizard Class


### STARTPACK:Dryad Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dryad]

### RACE:Dryad

- **!PRERACE:** 1,%

### NAME:Dryad


### STAT:DEX=11|CON=11|WIS=11|STR=10|INT=10|CHA=10


### GEAR:Longbow

- **SIZE:** PC
- **LOCATION:** Carried
- **EQMOD:** Masterwork (Weapon)

### STARTPACK:Dwarf (Duergar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Dwarf],[PREABILITY:1,CATEGORY=Internal,Dwarf ~ Duergar]]

### RACE:Dwarf

- **!PRERACE:** 1,%

### NAME:Duergar


### ABILITY:CATEGORY=Dwarf Subrace|Dwarf ~ Duergar

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.DwarfSubrace

### STAT:STR=13|DEX=11|CON=12|INT=10|WIS=9|CHA=8


### CLASS:Warrior

- **LEVEL:** 1

### GEAR:Chainmail

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Shield (Heavy/Metal)

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Crossbow (Light)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Eagle (Giant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Eagle (Giant)]

### RACE:Eagle (Giant)

- **!PRERACE:** 1,%

### NAME:Eagle (Giant)


### STARTPACK:Elemental (Air Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Air Small)]

### RACE:Elemental (Air Small)

- **!PRERACE:** 1,%

### NAME:Elemental (Air Small)


### STARTPACK:Elemental (Air Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Air Medium)]

### RACE:Elemental (Air Medium)

- **!PRERACE:** 1,%

### NAME:Elemental (Air Medium)


### STARTPACK:Elemental (Air Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Air Large)]

### RACE:Elemental (Air Large)

- **!PRERACE:** 1,%

### NAME:Elemental (Air Large)


### STARTPACK:Elemental (Air Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Air Huge)]

### RACE:Elemental (Air Huge)

- **!PRERACE:** 1,%

### NAME:Elemental (Air Huge)


### STARTPACK:Elemental (Air Greater) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Air Greater)]

### RACE:Elemental (Air Greater)

- **!PRERACE:** 1,%

### NAME:Elemental (Air Greater)


### STARTPACK:Elemental (Air Elder) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Air Elder)]

### RACE:Elemental (Air Elder)

- **!PRERACE:** 1,%

### NAME:Elemental (Air Elder)


### STARTPACK:Elemental (Earth Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Earth Small)]

### RACE:Elemental (Earth Small)

- **!PRERACE:** 1,%

### NAME:Elemental (Earth Small)


### STARTPACK:Elemental (Earth Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Earth Medium)]

### RACE:Elemental (Earth Medium)

- **!PRERACE:** 1,%

### NAME:Elemental (Earth Medium)


### STARTPACK:Elemental (Earth Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Earth Large)]

### RACE:Elemental (Earth Large)

- **!PRERACE:** 1,%

### NAME:Elemental (Earth Large)


### STARTPACK:Elemental (Earth Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Earth Huge)]

### RACE:Elemental (Earth Huge)

- **!PRERACE:** 1,%

### NAME:Elemental (Earth Huge)


### ABILITY:CATEGORY=FEAT|Awesome Blow


### STARTPACK:Elemental (Earth Greater) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Earth Greater)]

### RACE:Elemental (Earth Greater)

- **!PRERACE:** 1,%

### NAME:Elemental (Earth Greater)


### STARTPACK:Elemental (Earth Elder) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Earth Elder)]

### RACE:Elemental (Earth Elder)

- **!PRERACE:** 1,%

### NAME:Elemental (Earth Elder)


### ABILITY:CATEGORY=FEAT|Improved Critical(Slam)


### STARTPACK:Elemental (Fire Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Fire Small)]

### RACE:Elemental (Fire Small)

- **!PRERACE:** 1,%

### NAME:Elemental (Fire Small)


### STARTPACK:Elemental (Fire Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Fire Medium)]

### RACE:Elemental (Fire Medium)

- **!PRERACE:** 1,%

### NAME:Elemental (Fire Medium)


### STARTPACK:Elemental (Fire Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Fire Large)]

### RACE:Elemental (Fire Large)

- **!PRERACE:** 1,%

### NAME:Elemental (Fire Large)


### STARTPACK:Elemental (Fire Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Fire Huge)]

### RACE:Elemental (Fire Huge)

- **!PRERACE:** 1,%

### NAME:Elemental (Fire Huge)


### STARTPACK:Elemental (Fire Greater) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Fire Greater)]

### RACE:Elemental (Fire Greater)

- **!PRERACE:** 1,%

### NAME:Elemental (Fire Greater)


### STARTPACK:Elemental (Fire Elder) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Fire Elder)]

### RACE:Elemental (Fire Elder)

- **!PRERACE:** 1,%

### NAME:Elemental (Fire Elder)


### STARTPACK:Elemental (Water Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Water Small)]

### RACE:Elemental (Water Small)

- **!PRERACE:** 1,%

### NAME:Elemental (Water Small)


### STARTPACK:Elemental (Water Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Water Medium)]

### RACE:Elemental (Water Medium)

- **!PRERACE:** 1,%

### NAME:Elemental (Water Medium)


### STARTPACK:Elemental (Water Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Water Large)]

### RACE:Elemental (Water Large)

- **!PRERACE:** 1,%

### NAME:Elemental (Water Large)


### STARTPACK:Elemental (Water Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Water Huge)]

### RACE:Elemental (Water Huge)

- **!PRERACE:** 1,%

### NAME:Elemental (Water Huge)


### STARTPACK:Elemental (Water Greater) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Water Greater)]

### RACE:Elemental (Water Greater)

- **!PRERACE:** 1,%

### NAME:Elemental (Water Greater)


### STARTPACK:Elemental (Water Elder) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elemental (Water Elder)]

### RACE:Elemental (Water Elder)

- **!PRERACE:** 1,%

### NAME:Elemental (Water Elder)


### STARTPACK:Ethereal Filcher Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ethereal Filcher]

### RACE:Ethereal Filcher

- **!PRERACE:** 1,%

### NAME:Ethereal Filcher


### STARTPACK:Ethereal Marauder Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ethereal Marauder]

### RACE:Ethereal Marauder

- **!PRERACE:** 1,%

### NAME:Ethereal Marauder


### STARTPACK:Ettercap Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ettercap]

### RACE:Ettercap

- **!PRERACE:** 1,%

### NAME:Ettercap


### SKILL:Craft (Trapmaking)

- **RANK:** 2

### STARTPACK:Ettin Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ettin]

### RACE:Ettin

- **!PRERACE:** 1,%

### NAME:Ettin


### STARTPACK:Elf (Drow) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Elf],[PREABILITY:1,CATEGORY=Internal,Elf ~ Drow]]

### RACE:Elf

- **!PRERACE:** 1,%

### NAME:Elf (Drow)


### ABILITY:CATEGORY=Elf Subrace|Elf ~ Drow

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.ElfSubrace

### GEAR:Chain Shirt

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Shield (Light/Metal)

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Rapier

- **SIZE:** PC
- **LOCATION:** Primary Hand

### GEAR:Crossbow (Hand)

- **SIZE:** PC
- **LOCATION:** Carried

### ABILITY:CATEGORY=FEAT|Weapon Focus(Rapier)


### STARTPACK:Formian (Worker) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Formian (Worker)]

### RACE:Formian (Worker)

- **!PRERACE:** 1,%

### NAME:Formian (Worker)


### ABILITY:CATEGORY=FEAT|Skill Focus


### STARTPACK:Formian (Warrior) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Formian (Warrior)]

### RACE:Formian (Warrior)

- **!PRERACE:** 1,%

### NAME:Formian (Warrior)


### STARTPACK:Formian (Taskmaster) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Formian (Taskmaster)]

### RACE:Formian (Taskmaster)

- **!PRERACE:** 1,%

### NAME:Formian (Taskmaster)


### STAT:INT=11|CHA=11|STR=10|DEX=10|CON=10|WIS=10


### STARTPACK:Formian (Myrmarch) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Formian (Myrmarch)]

### RACE:Formian (Myrmarch)

- **!PRERACE:** 1,%

### NAME:Formian (Myrmarch)


### STARTPACK:Formian (Queen) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Formian (Queen)]

### RACE:Formian (Queen)

- **!PRERACE:** 1,%

### NAME:Formian (Queen)


### GENDER:Female


### ABILITY:CATEGORY=FEAT|Improved Counterspell


### ABILITY:CATEGORY=FEAT|TYPE=ItemCreation


### ABILITY:CATEGORY=FEAT|Maximize Spell


### ABILITY:CATEGORY=FEAT|Spell Focus(Enchantment)


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Acid Splash|Analyze Dweomer|Arcane Mark|Black Tentacles|Comprehend Languages|Cone of Cold|Confusion|Daze|Detect Magic|Detect Scrying|Dismissal|Dispel Magic|Geas/Quest|Heroism|Hypnotic Pattern|Identify|Invisibility|Light|Mage Armor|Mage Hand|Magic Missile|Nondetection|Prismatic Wall|Protection from Arrows|Read Magic|Repulsion|Resist Energy|Resistance|Scorching Ray|Scrying|Shield|Slow|Summon Monster VII|Teleport|Temporal Stasis|Touch of Fatigue|Vision|Wall of Force|Waves of Exhaustion


### STARTPACK:Frost Worm Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Frost Worm]

### RACE:Frost Worm

- **!PRERACE:** 1,%

### NAME:Frost Worm


### STARTPACK:Fungus (Shrieker) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Fungus (Shrieker)]

### RACE:Fungus (Shrieker)

- **!PRERACE:** 1,%

### NAME:Fungus (Shrieker)


### STARTPACK:Fungus (Violet) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Fungus (Violet)]

### RACE:Fungus (Violet)

- **!PRERACE:** 1,%

### NAME:Fungus (Violet)


### STARTPACK:Gargoyle Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Gargoyle,Gargoyle (Kapoacinth)]

### RACE:Gargoyle

- **!PRERACE:** 1,%

### NAME:Gargoyle


### STAT:STR=11|WIS=11|CHA=11|DEX=10|CON=10|INT=10


### STARTPACK:Kapoacinth Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Gargoyle (Kapoacinth)]

### RACE:Gargoyle (Kapoacinth)

- **!PRERACE:** 1,%

### KIT:Gargoyle Default


### NAME:Kapoacinth


### STARTPACK:Genie (Djinni) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Genie (Djinni)]

### RACE:Genie (Djinni)

- **!PRERACE:** 1,%

### NAME:Djinni


### STARTPACK:Genie (Efreeti) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Genie (Efreeti)]

### RACE:Genie (Efreeti)

- **!PRERACE:** 1,%

### NAME:Efreeti


### ABILITY:CATEGORY=FEAT|Quicken Spell-Like Ability(Scorching Ray)


### STAT:STR=11|DEX=11|WIS=11|CHA=11|CON=10|INT=10


### STARTPACK:Genie (Janni) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Genie (Janni)]

### RACE:Genie (Janni)

- **!PRERACE:** 1,%

### NAME:Janni


### STARTPACK:Ghaele Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Eladrin (Ghaele)]

### RACE:Eladrin (Ghaele)

- **!PRERACE:** 1,%

### NAME:Ghaele


### ABILITY:CATEGORY=FEAT|Improved Disarm


### ABILITY:CATEGORY=FEAT|Improved Trip


### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Aid|Align Weapon|Animal Shapes|Banishment|Bear's Endurance|Blade Barrier|Bless|Calm Animals|Chain Lightning|Command|Control Winds|Cure Minor Wounds|Daylight|Death Ward|Detect Magic|Dismissal|Divine Favor|Divine Power|Flame Strike|Gaseous Form|Guidance|Heal|Hold Animal|Holy Word|Light|Obscuring Mist|Prayer|Raise Dead|Remove Curse|Remove Paralysis|Resistance|Restoration|Restoration (Lesser)|Sanctuary|Searing Light|Shield of Faith|Summon Monster VII|Summon Nature's Ally IV|True Seeing|Virtue|Water Breathing|Zone of Truth


### STARTPACK:Ghoul Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ghoul,Ghoul (Lacedon)]

### RACE:Ghoul

- **!PRERACE:** 1,%

### NAME:Ghoul


### STAT:STR=11|DEX=11|INT=11|WIS=10|CHA=10


### STARTPACK:Lacedon Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ghoul (Lacedon)]

### RACE:Ghoul (Lacedon)

- **!PRERACE:** 1,%

### KIT:Ghoul Default


### NAME:Lacedon


### STARTPACK:Ghoul (Ghast) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ghoul (Ghast)]

### RACE:Ghoul (Ghast)

- **!PRERACE:** 1,%

### NAME:Ghast


### STARTPACK:Giant (Cloud) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Cloud)]

### RACE:Giant (Cloud)

- **!PRERACE:** 1,%

### NAME:Cloud Giant


### ALIGN:NE|NG


### SKILL:Perform (String Instruments)

- **RANK:** 1

### ABILITY:CATEGORY=FEAT|Improved Overrun


### STARTPACK:Giant (Fire) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Fire)]

### RACE:Giant (Fire)

- **!PRERACE:** 1,%

### NAME:Fire Giant


### GEAR:Half-Plate

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Giant (Frost) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Frost)]

### RACE:Giant (Frost)

- **!PRERACE:** 1,%

### NAME:Frost Giant


### GEAR:Greataxe

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Giant (Hill) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Hill)]

### RACE:Giant (Hill)

- **!PRERACE:** 1,%

### NAME:Hill Giant


### ABILITY:CATEGORY=FEAT|Weapon Focus(Greatclub)


### GEAR:Greatclub

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Giant (Stone) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Stone)]

### RACE:Giant (Stone)

- **!PRERACE:** 1,%

### NAME:Stone Giant


### STARTPACK:Giant (Storm) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Storm)]

### RACE:Giant (Storm)

- **!PRERACE:** 1,%

### NAME:Storm Giant


### SKILL:Perform (Sing)

- **RANK:** 10

### GEAR:Breastplate

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Gibbering Mouther Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Gibbering Mouther]

### RACE:Gibbering Mouther

- **!PRERACE:** 1,%

### NAME:Gibbering Mouther


### STARTPACK:Girallon Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Girallon]

### RACE:Girallon

- **!PRERACE:** 1,%

### NAME:Girallon


### STARTPACK:Gnoll Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Gnoll]

### RACE:Gnoll

- **!PRERACE:** 1,%

### NAME:Gnoll


### GEAR:Battleaxe

- **SIZE:** PC
- **LOCATION:** Primary Hand

### STARTPACK:Golem (Clay) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Golem (Clay)]

### RACE:Golem (Clay)

- **!PRERACE:** 1,%

### NAME:Clay Golem


### STARTPACK:Golem (Flesh) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Golem (Flesh)]

### RACE:Golem (Flesh)

- **!PRERACE:** 1,%

### NAME:Flesh Golem


### STARTPACK:Golem (Iron) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Golem (Iron)]

### RACE:Golem (Iron)

- **!PRERACE:** 1,%

### NAME:Iron Golem


### STARTPACK:Golem (Stone) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Golem (Stone)]

### RACE:Golem (Stone)

- **!PRERACE:** 1,%

### NAME:Stone Golem


### STARTPACK:Golem (Stone/Greater) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Golem (Stone)]

### NAME:Greater Stone Golem


### CLASS:Construct (Mindless)

- **LEVEL:** 28

### STARTPACK:Gorgon Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Gorgon]

### RACE:Gorgon

- **!PRERACE:** 1,%

### NAME:Gorgon


### STARTPACK:Gray Render Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Gray Render]

### RACE:Gray Render

- **!PRERACE:** 1,%

### NAME:Gray Render


### STAT:STR=11|INT=11|DEX=10|CON=10|WIS=10|CHA=10


### STARTPACK:Grick Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Grick]

### RACE:Grick

- **!PRERACE:** 1,%

### NAME:Grick


### STAT:CON=11|INT=11|CHA=11|STR=10|DEX=10|WIS=10


### STARTPACK:Griffon Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Griffon]

### RACE:Griffon

- **!PRERACE:** 1,%

### NAME:Griffon


### STAT:DEX=11|INT=11|WIS=11|STR=10|CON=10|CHA=10


### STARTPACK:Grimlock Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Grimlock]

### RACE:Grimlock

- **!PRERACE:** 1,%

### NAME:Grimlock


### STARTPACK:Gnome (Svirfneblin) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Gnome],[PREABILITY:1,CATEGORY=Internal,Gnome ~ Svirfneblin]]

### RACE:Gnome

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=Gnome Subrace|Gnome ~ Svirfneblin

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.GnomeSubrace

### NAME:Svirfneblin


### GEAR:Banded Mail

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Pick (Heavy)

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Goblin Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Goblin]

### RACE:Goblin

- **!PRERACE:** 1,%

### NAME:Goblin


### STARTPACK:Hag (Annis) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hag (Annis)]

### RACE:Hag (Annis)

- **!PRERACE:** 1,%

### NAME:Annis Hag


### STAT:STR=11|INT=11|WIS=11|DEX=10|CON=10|CHA=10


### STARTPACK:Hag (Green) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hag (Green)]

### RACE:Hag (Green)

- **!PRERACE:** 1,%

### NAME:Green Hag


### SKILL:TYPE=Craft|TYPE=Knowledge

- **RANK:** 6

### STARTPACK:Hag (Sea) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hag (Sea)]

### RACE:Hag (Sea)

- **!PRERACE:** 1,%

### NAME:Sea Hag


### STARTPACK:Harpy Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Harpy]

### RACE:Harpy

- **!PRERACE:** 1,%

### NAME:Harpy


### SKILL:Perform (Oratory)

- **RANK:** 2

### GEAR:Club

- **SIZE:** PC
- **LOCATION:** Primary Hand

### STARTPACK:Hell Hound Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hell Hound]

### RACE:Hell Hound

- **!PRERACE:** 1,%

### NAME:Hell Hound


### STARTPACK:Hippogriff Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hippogriff]

### RACE:Hippogriff

- **!PRERACE:** 1,%

### NAME:Hippogriff


### ABILITY:CATEGORY=FEAT|Wingover


### STARTPACK:Hobgoblin Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hobgoblin]

### RACE:Hobgoblin

- **!PRERACE:** 1,%

### NAME:Hobgoblin


### STARTPACK:Homunculus Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Homunculus]

### RACE:Homunculus

- **!PRERACE:** 1,%

### NAME:Homunculus


### STARTPACK:Howler Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Howler]

### RACE:Howler

- **!PRERACE:** 1,%

### NAME:Howler


### STARTPACK:Hydra (Eight Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Eight]]

### RACE:Hydra

- **!PRERACE:** 1,%

### NAME:Eight Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Eight

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Eleven Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Eleven]]

### NAME:Eleven Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Eleven

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Five Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Five]]

### NAME:Five Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Five

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Nine Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Nine]]

### NAME:Nine Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Nine

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Seven Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Seven]]

### NAME:Seven Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Seven

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Six Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Six]]

### NAME:Six Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Six

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Ten Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Ten]]

### NAME:Ten Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Ten

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Twelve Headed) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PREMULT:2,[PRERACE:1,Hydra],[PREABILITY:1,CATEGORY=Internal,Hydra Heads ~ Twelve]]

### NAME:Twelve Headed Hydra


### ABILITY:CATEGORY=Hydra Heads|Hydra Heads ~ Twelve

- **!PREABILITY:** 1,CATEGORY=Internal,TYPE.Hydra Heads

### STARTPACK:Hydra (Pyrohydra) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,TYPE.Hydra Heads]

### TEMPLATE:Hydra (Pyrohydra)


### STARTPACK:Hydra (Cryohydra) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[PREABILITY:1,CATEGORY=Internal,TYPE.Hydra Heads]

### TEMPLATE:Hydra (Cryohydra)


### STARTPACK:Inevitable (Kolyarut) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Inevitable (Kolyarut)]

### RACE:Inevitable (Kolyarut)

- **!PRERACE:** 1,%

### NAME:Inevitable (Kolyarut)


### SKILL:Gather Information

- **RANK:** 5

### ABILITY:CATEGORY=FEAT|Quicken Spell-Like Ability(Suggestion)


### STARTPACK:Inevitable (Marut) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Inevitable (Marut)]

### RACE:Inevitable (Marut)

- **!PRERACE:** 1,%

### NAME:Inevitable (Marut)


### ABILITY:CATEGORY=FEAT|Ability Focus(Fists)


### GEAR:Full Plate

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Inevitable (Zelekhut) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Inevitable (Zelekhut)]

### RACE:Inevitable (Zelekhut)

- **!PRERACE:** 1,%

### NAME:Inevitable (Zelekhut)


### ABILITY:CATEGORY=FEAT|Ride-By Attack


### ABILITY:CATEGORY=FEAT|Spirited Charge


### GEAR:Barding (Full Plate)

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Invisible Stalker Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Invisible Stalker]

### RACE:Invisible Stalker

- **!PRERACE:** 1,%

### NAME:Invisible Stalker


### STARTPACK:Kobold Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Kobold]

### RACE:Kobold

- **!PRERACE:** 1,%

### NAME:Kobold


### GEAR:Sling

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Kraken Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Kraken]

### RACE:Kraken

- **!PRERACE:** 1,%

### NAME:Kraken


### SKILL:Knowledge (Geography)

- **RANK:** 12

### ABILITY:CATEGORY=FEAT|Improved Critical(Tentacle)


### STARTPACK:Krenshar Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Krenshar]

### RACE:Krenshar

- **!PRERACE:** 1,%

### NAME:Krenshar


### STARTPACK:Lamia Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lamia]

### RACE:Lamia

- **!PRERACE:** 1,%

### NAME:Lamia


### STARTPACK:Lammasu Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lammasu]

### RACE:Lammasu

- **!PRERACE:** 1,%

### NAME:Lammasu


### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Aid|Bear's Endurance|Bless=2|Bull's Strength|Daylight|Detect Evil|Detect Magic|Dispel Magic|Divine Favor|Entropic Shield|Guidance=2|Holy Smite|Light|Magic Circle against Evil|Neutralize Poison|Protection from Evil|Read Magic|Remove Curse|Resist Energy|Resistance|Restoration (Lesser)


### STARTPACK:Leonal Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Guardinal (Leonal)]

### RACE:Guardinal (Leonal)

- **!PRERACE:** 1,%

### NAME:Leonal


### ABILITY:CATEGORY=FEAT|Ability Focus(Roar)


### STAT:STR=11|DEX=11|CHA=11|CON=10|INT=10|WIS=10


### STARTPACK:Lillend Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lillend]

### RACE:Lillend

- **!PRERACE:** 1,%

### NAME:Lillend


### SKILL:TYPE=Perform

- **RANK:** 10

### ABILITY:CATEGORY=FEAT|Extend Spell


### SPELLS:SPELLBOOK=Known Spells|CLASS=Bard|Charm Person|Cure Light Wounds|Dancing Lights|Daze|Detect Magic|Hold Person|Identify|Invisibility|Lullaby|Mage Hand|Read Magic|Sleep|Sound Burst


### STARTPACK:Lizardfolk Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lizardfolk]

### RACE:Lizardfolk

- **!PRERACE:** 1,%

### NAME:Lizardfolk


### STAT:STR=11|CON=11|INT=11|DEX=10|WIS=10|CHA=10


### STARTPACK:Locathah Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Locathah]

### RACE:Locathah

- **!PRERACE:** 1,%

### NAME:Locathah


### ABILITY:CATEGORY=FEAT|Weapon Focus(Longspear)


### GEAR:Longspear

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Lycanthrope (Werebear) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Human]

### NAME:Werebear


### RACE:Human

- **!PRERACE:** 1,%

### TEMPLATE:Lycanthrope|Werebear|Natural Lycanthrope


### GEAR:Axe (Throwing)

- **SIZE:** M
- **LOCATION:** Carried

### STARTPACK:Lycanthrope (Wereboar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Human]

### NAME:Wereboar


### TEMPLATE:Lycanthrope|Wereboar|Natural Lycanthrope


### STARTPACK:Lycanthrope (Wererat) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Human]

### NAME:Wererat


### TEMPLATE:Lycanthrope|Natural Lycanthrope|Wererat


### STARTPACK:Lycanthrope (Weretiger) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Human]

### NAME:Weretiger


### TEMPLATE:Lycanthrope|Natural Lycanthrope|Weretiger


### STARTPACK:Lycanthrope (Werewolf) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Human]

### NAME:Werewolf


### TEMPLATE:Lycanthrope|Natural Lycanthrope|Werewolf


### STARTPACK:Lycanthrope (Hill Giant Dire Wereboar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Hill)]

### NAME:Hill Giant Dire Wereboar


### STAT:STR=11|DEX=10|CON=11|INT=10|WIS=10|CHA=11


### TEMPLATE:Lycanthrope|Natural Lycanthrope|Dire Wereboar


### STARTPACK:Lycanthrope (Werewolf Lord) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Human]

### NAME:Werewolf Lord


### STAT:STR=16|DEX=14|CON=14|INT=10|WIS=10|CHA=12


### CLASS:Fighter

- **LEVEL:** 1

### ABILITY:CATEGORY=FEAT|Exotic Weapon Proficiency(Sword (Bastard))


### ABILITY:CATEGORY=Fighter Feat|Weapon Focus (Sword (Bastard))


### TEMPLATE:Lycanthrope|Natural Lycanthrope|Dire Werewolf


### ABILITY:CATEGORY=Fighter Feat|Combat Reflexes


### ABILITY:CATEGORY=Fighter Feat|Weapon Specialization(Sword (Bastard))


### ABILITY:CATEGORY=Fighter Feat|Cleave


### ABILITY:CATEGORY=Fighter Feat|Improved Critical(Bite)


### ABILITY:CATEGORY=FEAT|Improved Natural Armor


### ABILITY:CATEGORY=Fighter Feat|Improved Critical(Sword (Bastard))


### GEAR:Sword (Bastard)

- **SIZE:** PC
- **LOCATION:** Primary Hand
- **EQMOD:** Masterwork (Weapon).PLUS2W

### GEAR:Gauntlets of Ogre Power

- **LOCATION:** Equipped

### GEAR:Cloak of Resistance +2

- **LOCATION:** Equipped

### STARTPACK:Magmin Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Magmin]

### RACE:Magmin

- **!PRERACE:** 1,%

### NAME:Magmin


### STARTPACK:Manticore Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Manticore]

### RACE:Manticore

- **!PRERACE:** 1,%

### NAME:Manticore


### ABILITY:CATEGORY=FEAT|Weapon Focus(Spikes)


### STAT:DEX=11|CON=11|INT=11|CHA=11|STR=10|WIS=10


### STARTPACK:Medusa Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Medusa]

### RACE:Medusa

- **!PRERACE:** 1,%

### NAME:Medusa


### STARTPACK:Mephit (Air) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Air)]

### RACE:Mephit (Air)

- **!PRERACE:** 1,%

### NAME:Air Mephit


### STARTPACK:Mephit (Dust) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Dust)]

### RACE:Mephit (Dust)

- **!PRERACE:** 1,%

### NAME:Dust Mephit


### STARTPACK:Mephit (Earth) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Earth)]

### RACE:Mephit (Earth)

- **!PRERACE:** 1,%

### NAME:Earth Mephit


### STARTPACK:Mephit (Fire) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Fire)]

### RACE:Mephit (Fire)

- **!PRERACE:** 1,%

### NAME:Fire Mephit


### STARTPACK:Mephit (Ice) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Ice)]

### RACE:Mephit (Ice)

- **!PRERACE:** 1,%

### NAME:Ice Mephit


### STARTPACK:Mephit (Magma) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Magma)]

### RACE:Mephit (Magma)

- **!PRERACE:** 1,%

### NAME:Magma Mephit


### STARTPACK:Mephit (Ooze) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Ooze)]

### RACE:Mephit (Ooze)

- **!PRERACE:** 1,%

### NAME:Ooze Mephit


### STARTPACK:Mephit (Salt) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Salt)]

### RACE:Mephit (Salt)

- **!PRERACE:** 1,%

### NAME:Salt Mephit


### STARTPACK:Mephit (Steam) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Steam)]

### RACE:Mephit (Steam)

- **!PRERACE:** 1,%

### NAME:Steam Mephit


### STARTPACK:Mephit (Water) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mephit (Water)]

### RACE:Mephit (Water)

- **!PRERACE:** 1,%

### NAME:Water Mephit


### STARTPACK:Merfolk Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Merfolk]

### RACE:Merfolk

- **!PRERACE:** 1,%

### NAME:Merfolk


### GEAR:Trident

- **SIZE:** PC
- **LOCATION:** Both Hands

### GEAR:Crossbow (Heavy)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Mimic Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mimic]

### RACE:Mimic

- **!PRERACE:** 1,%

### NAME:Mimic


### STARTPACK:Minotaur Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Minotaur]

### RACE:Minotaur

- **!PRERACE:** 1,%

### NAME:Minotaur


### STARTPACK:Mohrg Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mohrg]

### RACE:Mohrg

- **!PRERACE:** 1,%

### NAME:Mohrg


### STARTPACK:Mummy Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mummy]

### RACE:Mummy

- **!PRERACE:** 1,%

### NAME:Mummy


### STARTPACK:Naga (Dark) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Naga (Dark)]

### RACE:Naga (Dark)

- **!PRERACE:** 1,%

### NAME:Dark Naga


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Cat's Grace|Daze|Detect Magic|Displacement|Expeditious Retreat|Invisibility|Light|Lightning Bolt|Mage Hand|Magic Missile|Open/Close|Ray of Enfeeblement|Ray of Frost|Read Magic|Scorching Ray|Shield|Silent Image


### STARTPACK:Naga (Guardian) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Naga (Guardian)]

### RACE:Naga (Guardian)

- **!PRERACE:** 1,%

### NAME:Guardian Naga


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Cure Light Wounds|Cure Minor Wounds|Cure Serious Wounds|Daze|Detect Magic|Detect Thoughts|Dispel Magic|Divine Favor|Divine Power|Expeditious Retreat|Invisibility (Greater)|Light|Lightning Bolt|Mage Armor|Mage Hand|Magic Missile|Open/Close|Ray of Frost|Read Magic|Restoration (Lesser)|Scorching Ray|See Invisibility


### STARTPACK:Naga (Spirit) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Naga (Spirit)]

### RACE:Naga (Spirit)

- **!PRERACE:** 1,%

### NAME:Spirit Naga


### ABILITY:CATEGORY=FEAT|Ability Focus(Charming Gaze)


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Cat's Grace|Charm Person|Cure Light Wounds|Cure Minor Wounds|Daze|Detect Magic|Displacement|Divine Favor|Fireball|Invisibility|Mage Hand|Magic Missile|Open/Close|Ray of Frost|Read Magic|Shield of Faith|Summon Swarm


### STARTPACK:Naga (Water) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Naga (Water)]

### RACE:Naga (Water)

- **!PRERACE:** 1,%

### NAME:Water Naga


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Acid Arrow|Acid Splash|Daze|Detect Magic|Expeditious Retreat|Invisibility|Light|Mage Hand|Magic Missile|Mirror Image|Obscuring Mist|Open/Close|Protection from Energy|Read Magic|Shield|Suggestion|True Strike


### STARTPACK:Night Hag Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Night Hag]

### RACE:Night Hag

- **!PRERACE:** 1,%

### NAME:Night Hag


### ABILITY:CATEGORY=FEAT|Mounted Combat


### GEAR:Periapt of the Night Hag (Heartstone)

- **LOCATION:** Equipped

### STARTPACK:Nightmare Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Nightmare]

### RACE:Nightmare

- **!PRERACE:** 1,%

### NAME:Nightmare


### STARTPACK:Nightshade (Nightcrawler) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Nightshade (Nightcrawler)]

### STAT:DEX=10|INT=10|WIS=10|STR=10|CON=10|CHA=10


### RACE:Nightshade (Nightcrawler)

- **!PRERACE:** 1,%

### NAME:Nightshade (Nightcrawler)


### ABILITY:CATEGORY=FEAT|Improved Critical(Bite)


### ABILITY:CATEGORY=FEAT|Improved Critical(Sting)


### ABILITY:CATEGORY=FEAT|Quicken Spell-Like Ability(Cone Of Cold)


### STARTPACK:Nightshade (Nightwalker) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Nightshade (Nightwalker)]

### RACE:Nightshade (Nightwalker)

- **!PRERACE:** 1,%

### NAME:Nightshade (Nightwalker)


### ABILITY:CATEGORY=FEAT|Quicken Spell-Like Ability(Unholy Blight)


### STARTPACK:Nightshade (Nightwing) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Nightshade (Nightwing)]

### RACE:Nightshade (Nightwing)

- **!PRERACE:** 1,%

### NAME:Nightshade (Nightwing)


### STARTPACK:Nymph Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Nymph]

### RACE:Nymph

- **!PRERACE:** 1,%

### NAME:Nymph


### SKILL:Heal

- **RANK:** 9

### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Druid|Barkskin|Call Lightning|Cure Light Wounds|Cure Minor Wounds|Cure Moderate Wounds|Detect Magic|Entangle|Flare|Guidance|Heat Metal|Light|Longstrider|Protection from Energy|Resistance|Restoration (Lesser)|Rusting Grasp|Speak with Animals|Tree Shape


### STARTPACK:Ogre Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ogre]

### RACE:Ogre

- **!PRERACE:** 1,%

### NAME:Ogre


### STARTPACK:Ogre (Merrow) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ogre (Merrow)]

### RACE:Ogre (Merrow)

- **!PRERACE:** 1,%

### NAME:Merrow


### STARTPACK:Ogre Mage Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ogre Mage]

### RACE:Ogre Mage

- **!PRERACE:** 1,%

### NAME:Ogre Mage


### STARTPACK:Ooze (Black Pudding) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ooze (Black Pudding)]

### STAT:STR=11|DEX=10|CON=10|WIS=10|CHA=10


### RACE:Ooze (Black Pudding)

- **!PRERACE:** 1,%

### NAME:Black Pudding


### STARTPACK:Ooze (Gelatinous Cube) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ooze (Gelatinous Cube)]

### STAT:STR=10|DEX=10|CON=10|WIS=10|CHA=10


### RACE:Ooze (Gelatinous Cube)

- **!PRERACE:** 1,%

### NAME:Gelatinous Cube


### STARTPACK:Ooze (Gray) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ooze (Gray)]

### STAT:CON=11|STR=10|DEX=10|WIS=10|CHA=10


### RACE:Ooze (Gray)

- **!PRERACE:** 1,%

### NAME:Gray


### STARTPACK:Ooze (Ochre Jelly) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ooze (Ochre Jelly)]

### RACE:Ooze (Ochre Jelly)

- **!PRERACE:** 1,%

### NAME:Ochre Jelly


### STARTPACK:Otyugh Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Otyugh]

### RACE:Otyugh

- **!PRERACE:** 1,%

### NAME:Otyugh


### ABILITY:CATEGORY=FEAT|Weapon Focus(Tentacle)


### STARTPACK:Owl (Giant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Owl (Giant)]

### RACE:Owl (Giant)

- **!PRERACE:** 1,%

### NAME:Giant Owl


### STARTPACK:Owlbear Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Owlbear]

### RACE:Owlbear

- **!PRERACE:** 1,%

### NAME:Owlbear


### STARTPACK:Pegasus Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Pegasus]

### RACE:Pegasus

- **!PRERACE:** 1,%

### NAME:Pegasus


### STARTPACK:Phantom Fungus Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Phantom Fungus]

### RACE:Phantom Fungus

- **!PRERACE:** 1,%

### NAME:Phantom Fungus


### STARTPACK:Phase Spider Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Phase Spider]

### RACE:Phase Spider

- **!PRERACE:** 1,%

### NAME:Phase Spider


### ABILITY:CATEGORY=FEAT|Ability Focus(Poison)


### STAT:STR=11|DEX=11|INT=11|WIS=11|CON=10|CHA=10


### STARTPACK:Phasm Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Phasm]

### RACE:Phasm

- **!PRERACE:** 1,%

### NAME:Phasm


### STARTPACK:Pseudodragon Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Pseudodragon]

### RACE:Pseudodragon

- **!PRERACE:** 1,%

### NAME:Pseudodragon


### STARTPACK:Purple Worm Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Purple Worm]

### RACE:Purple Worm

- **!PRERACE:** 1,%

### NAME:Purple Worm


### ABILITY:CATEGORY=FEAT|Weapon Focus(Sting)


### STARTPACK:Orc Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Orc]

### RACE:Orc

- **!PRERACE:** 1,%

### NAME:Orc


### GEAR:Falchion

- **SIZE:** PC
- **LOCATION:** Both Hands

### STARTPACK:Planetouched (Aasimar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Planetouched (Aasimar)]

### TEMPLATE:Default Aasimar


### RACE:Planetouched (Aasimar)

- **!PRERACE:** 1,%

### NAME:Aasimar


### STARTPACK:Planetouched (Tiefling) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Planetouched (Tiefling)]

### TEMPLATE:Default Tiefling


### RACE:Planetouched (Tiefling)

- **!PRERACE:** 1,%

### NAME:Tiefling


### ALIGN:LE|NE|CE


### STARTPACK:Rakshasa Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Rakshasa]

### RACE:Rakshasa

- **!PRERACE:** 1,%

### NAME:Rakshasa


### SPELLS:SPELLBOOK=Known Spells|CLASS=Sorcerer|Acid Arrow|Bear's Endurance|Charm Person|Detect Magic|Haste|Invisibility|Light|Mage Armor|Mage Hand|Magic Missile|Message|Read Magic|Resistance|Shield|Silent Image|Suggestion|Touch of Fatigue


### STARTPACK:Rast Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Rast]

### RACE:Rast

- **!PRERACE:** 1,%

### NAME:Rast


### STAT:CON=11|INT=11|WIS=11|STR=10|DEX=10|CHA=10


### STARTPACK:Ravid Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ravid]

### RACE:Ravid

- **!PRERACE:** 1,%

### NAME:Ravid


### STARTPACK:Remorhaz Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Remorhaz]

### RACE:Remorhaz

- **!PRERACE:** 1,%

### NAME:Remorhaz


### STARTPACK:Roc Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Roc]

### RACE:Roc

- **!PRERACE:** 1,%

### NAME:Roc


### STARTPACK:Roper Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Roper]

### RACE:Roper

- **!PRERACE:** 1,%

### NAME:Roper


### ABILITY:CATEGORY=FEAT|Weapon Focus(Strand)


### STARTPACK:Rust Monster Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Rust Monster]

### RACE:Rust Monster

- **!PRERACE:** 1,%

### NAME:Rust Monster


### STARTPACK:Sahuagin Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sahuagin]

### RACE:Sahuagin

- **!PRERACE:** 1,%

### NAME:Sahuagin


### STARTPACK:Sahuagin (Mutant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sahuagin]

### KIT:Sahuagin Default


### TEMPLATE:Sahuagin (Mutant)


### NAME:Mutant Sahuagin


### STARTPACK:Sahuagin (Malenti) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sahuagin (Malenti)]

### RACE:Sahuagin (Malenti)

- **!PRERACE:** 1,%

### NAME:Malenti


### STARTPACK:Salamander (Average) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Salamander (Average)]

### RACE:Salamander (Average)

- **!PRERACE:** 1,%

### NAME:Salamander (Average)


### STARTPACK:Salamander (Flamebrother) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Salamander (Flamebrother)]

### RACE:Salamander (Flamebrother)

- **!PRERACE:** 1,%

### NAME:Salamander (Flamebrother)


### STARTPACK:Salamander (Noble) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Salamander (Noble)]

### RACE:Salamander (Noble)

- **!PRERACE:** 1,%

### NAME:Salamander (Noble)


### ABILITY:CATEGORY=FEAT|Skill Focus(Craft (Blacksmithing))


### STARTPACK:Satyr Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Satyr]

### RACE:Satyr

- **!PRERACE:** 1,%

### NAME:Satyr


### STARTPACK:Sea Cat Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sea Cat]

### RACE:Sea Cat

- **!PRERACE:** 1,%

### NAME:Sea Cat


### STARTPACK:Shadow Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shadow]

### RACE:Shadow

- **!PRERACE:** 1,%

### NAME:Shadow


### STARTPACK:Shadow Mastiff Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shadow Mastiff]

### RACE:Shadow Mastiff

- **!PRERACE:** 1,%

### NAME:Shadow Mastiff


### STARTPACK:Shambling Mound Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shambling Mound]

### STAT:STR=11|CON=11|INT=11|CHA=11|DEX=10|WIS=10


### RACE:Shambling Mound

- **!PRERACE:** 1,%

### NAME:Shambling Mound


### STARTPACK:Shield Guardian Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shield Guardian]

### RACE:Shield Guardian

- **!PRERACE:** 1,%

### NAME:Shield Guardian


### STAT:STR=10|DEX=10|WIS=10|CHA=11


### STARTPACK:Shocker Lizard Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shocker Lizard]

### RACE:Shocker Lizard

- **!PRERACE:** 1,%

### NAME:Shocker Lizard


### STARTPACK:Skeleton (Human Warrior) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Human Warrior)]

### RACE:Skeleton (Human Warrior)

- **!PRERACE:** 1,%

### NAME:Skeleton (Human Warrior)


### STARTPACK:Skeleton (Wolf) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Wolf)]

### RACE:Skeleton (Wolf)

- **!PRERACE:** 1,%

### NAME:Skeleton (Wolf)


### STARTPACK:Skeleton (Owlbear) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Owlbear)]

### RACE:Skeleton (Owlbear)

- **!PRERACE:** 1,%

### NAME:Skeleton (Owlbear)


### STARTPACK:Skeleton (Troll) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Troll)]

### RACE:Skeleton (Troll)

- **!PRERACE:** 1,%

### NAME:Skeleton (Troll)


### STARTPACK:Skeleton (Chimera) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Chimera)]

### RACE:Skeleton (Chimera)

- **!PRERACE:** 1,%

### NAME:Skeleton (Chimera)


### STARTPACK:Skeleton (Ettin) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Ettin)]

### RACE:Skeleton (Ettin)

- **!PRERACE:** 1,%

### NAME:Skeleton (Ettin)


### STARTPACK:Skeleton (Advanced Megaraptor) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Advanced Megaraptor)]

### RACE:Skeleton (Advanced Megaraptor)

- **!PRERACE:** 1,%

### NAME:Skeleton (Advanced Megaraptor)


### STARTPACK:Skeleton (Cloud Giant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Cloud Giant)]

### RACE:Skeleton (Cloud Giant)

- **!PRERACE:** 1,%

### NAME:Skeleton (Cloud Giant)


### STARTPACK:Skeleton (Young Adult Red Dragon) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skeleton (Young Adult Red Dragon)]

### RACE:Skeleton (Young Adult Red Dragon)

- **!PRERACE:** 1,%

### NAME:Skeleton (Young Adult Red Dragon)


### STARTPACK:Skum Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Skum]

### RACE:Skum

- **!PRERACE:** 1,%

### NAME:Skum


### STARTPACK:Spectre Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Spectre]

### RACE:Spectre

- **!PRERACE:** 1,%

### NAME:Spectre


### STARTPACK:Sphinx (Androsphinx) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sphinx (Androsphinx)]

### RACE:Sphinx (Androsphinx)

- **!PRERACE:** 1,%

### NAME:Androsphinx


### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Bull's Strength|Cure Minor Wounds|Cure Serious Wounds|Daylight|Detect Magic|Divine Favor|Guidance|Invisibility Purge|Light|Protection from Evil|Remove Fear|Remove Paralysis|Resist Energy|Resistance|Searing Light|Shield Other|Shield of Faith|Summon Monster I|Summon Monster II


### STARTPACK:Sphinx (Criosphinx) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sphinx (Criosphinx)]

### RACE:Sphinx (Criosphinx)

- **!PRERACE:** 1,%

### NAME:Criosphinx


### STARTPACK:Sphinx (Gynosphinx) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sphinx (Gynosphinx)]

### RACE:Sphinx (Gynosphinx)

- **!PRERACE:** 1,%

### NAME:Gynosphinx


### STARTPACK:Sphinx (Hieracosphinx) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sphinx (Hieracosphinx)]

### RACE:Sphinx (Hieracosphinx)

- **!PRERACE:** 1,%

### NAME:Hieracosphinx


### STARTPACK:Spider Eater Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Spider Eater]

### RACE:Spider Eater

- **!PRERACE:** 1,%

### NAME:Spider Eater


### STARTPACK:Sprite (Grig) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sprite (Grig)]

### RACE:Sprite (Grig)

- **!PRERACE:** 1,%

### NAME:Grig


### STARTPACK:Sprite (Nixie) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sprite (Nixie)]

### RACE:Sprite (Nixie)

- **!PRERACE:** 1,%

### NAME:Nixie


### STARTPACK:Sprite (Pixie) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Sprite (Pixie)]

### RACE:Sprite (Pixie)

- **!PRERACE:** 1,%

### NAME:Pixie


### STARTPACK:Stirge Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Stirge]

### RACE:Stirge

- **!PRERACE:** 1,%

### NAME:Stirge


### STARTPACK:Swarm (Bat) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Swarm (Bat)]

### RACE:Swarm (Bat)

- **!PRERACE:** 1,%

### NAME:Bat Swarm


### STARTPACK:Swarm (Centipede) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Swarm (Centipede)]

### STAT:DEX=11|STR=10|CON=10|WIS=10|CHA=10


### RACE:Swarm (Centipede)

- **!PRERACE:** 1,%

### NAME:Centipede Swarm


### STARTPACK:Swarm (Hellwasp) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Swarm (Hellwasp)]

### RACE:Swarm (Hellwasp)

- **!PRERACE:** 1,%

### NAME:Hellwasp Swarm


### STARTPACK:Swarm (Locust) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Swarm (Locust)]

### RACE:Swarm (Locust)

- **!PRERACE:** 1,%

### NAME:Locust Swarm


### STARTPACK:Swarm (Rat) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Swarm (Rat)]

### RACE:Swarm (Rat)

- **!PRERACE:** 1,%

### NAME:Rat Swarm


### STARTPACK:Swarm (Spider) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Swarm (Spider)]

### RACE:Swarm (Spider)

- **!PRERACE:** 1,%

### NAME:Spider Swarm


### STARTPACK:Tarrasque Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Tarrasque]

### RACE:Tarrasque

- **!PRERACE:** 1,%

### NAME:Tarrasque


### STARTPACK:Tendriculos Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Tendriculos]

### RACE:Tendriculos

- **!PRERACE:** 1,%

### NAME:Tendriculos


### STARTPACK:Thoqqua Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Thoqqua]

### RACE:Thoqqua

- **!PRERACE:** 1,%

### NAME:Thoqqua


### STARTPACK:Titan Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Titan]

### RACE:Titan

- **!PRERACE:** 1,%

### NAME:Titan


### ALIGN:CG|CN|CE


### ABILITY:CATEGORY=FEAT|Quicken Spell-Like Ability(Chain Lightning)


### STARTPACK:Tojanida (Adult) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Tojanida (Adult)]

### RACE:Tojanida (Adult)

- **!PRERACE:** 1,%

### NAME:Adult Tojanida


### STARTPACK:Tojanida (Elder) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Tojanida (Elder)]

### RACE:Tojanida (Elder)

- **!PRERACE:** 1,%

### NAME:Elder Tojanida


### STARTPACK:Tojanida (Juvenile) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Tojanida (Juvenile)]

### RACE:Tojanida (Juvenile)

- **!PRERACE:** 1,%

### NAME:Juvenile Tojanida


### STARTPACK:Treant Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Treant]

### RACE:Treant

- **!PRERACE:** 1,%

### NAME:Treant


### STARTPACK:Triton Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Triton]

### RACE:Triton

- **!PRERACE:** 1,%

### NAME:Triton


### STARTPACK:Troglodyte Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Troglodyte]

### RACE:Troglodyte

- **!PRERACE:** 1,%

### NAME:Troglodyte


### ABILITY:CATEGORY=FEAT|Weapon Focus(Javelin)


### STARTPACK:Troll Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Troll%]

### RACE:Troll

- **!PRERACE:** 1,%

### NAME:Troll


### STARTPACK:Troll (Scrag) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Troll]

### KIT:Troll Default


### NAME:Scrag


### TEMPLATE:Troll (Scrag)


### STARTPACK:Unicorn Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Unicorn]

### RACE:Unicorn

- **!PRERACE:** 1,%

### NAME:Unicorn


### ABILITY:CATEGORY=FEAT|Skill Focus(Survival)


### STARTPACK:Vampire Spawn Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Vampire Spawn]

### RACE:Vampire Spawn

- **!PRERACE:** 1,%

### NAME:Vampire Spawn


### SKILL:TYPE=Craft|TYPE=Profession

- **RANK:** 4

### STAT:INT=11|WIS=11|STR=10|DEX=10|CON=10|CHA=10


### STARTPACK:Vargouille Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Vargouille]

### RACE:Vargouille

- **!PRERACE:** 1,%

### NAME:Vargouille


### STAT:DEX=11|INT=11|STR=10|CON=10|WIS=10|CHA=10


### STARTPACK:Wight Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Wight]

### RACE:Wight

- **!PRERACE:** 1,%

### NAME:Wight


### STARTPACK:Will-o'-Wisp Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Will-o'-Wisp]

### RACE:Will-o'-Wisp

- **!PRERACE:** 1,%

### NAME:Will-o'-Wisp


### STARTPACK:Winter Wolf Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Winter Wolf]

### RACE:Winter Wolf

- **!PRERACE:** 1,%

### NAME:Winter Wolf


### STARTPACK:Worg Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Worg]

### RACE:Worg

- **!PRERACE:** 1,%

### NAME:Worg


### STARTPACK:Wraith Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Wraith]

### RACE:Wraith

- **!PRERACE:** 1,%

### NAME:Wraith


### STAT:CHA=11|DEX=10|INT=10|WIS=10


### STARTPACK:Wraith (Dread) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Wraith (Dread)]

### RACE:Wraith (Dread)

- **!PRERACE:** 1,%

### NAME:Dread Wraith


### ABILITY:CATEGORY=FEAT|Improved Natural Attack(Incorporeal Touch)


### STAT:INT=11|DEX=10|WIS=10|CHA=10


### STARTPACK:Wyvern Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Wyvern]

### RACE:Wyvern

- **!PRERACE:** 1,%

### NAME:Wyvern


### STARTPACK:Xill Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Xill]

### RACE:Xill

- **!PRERACE:** 1,%

### NAME:Xill


### STARTPACK:Xorn (Minor) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Xorn (Minor)]

### RACE:Xorn (Minor)

- **!PRERACE:** 1,%

### NAME:Minor Xorn


### STARTPACK:Xorn (Average) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Xorn (Average)]

### RACE:Xorn (Average)

- **!PRERACE:** 1,%

### NAME:Average Xorn


### STARTPACK:Xorn (Elder) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Xorn (Elder)]

### RACE:Xorn (Elder)

- **!PRERACE:** 1,%

### NAME:Elder Xorn


### STARTPACK:Yeth Hound Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Yeth Hound]

### RACE:Yeth Hound

- **!PRERACE:** 1,%

### NAME:Yeth Hound


### STARTPACK:Yrthak Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Yrthak]

### RACE:Yrthak

- **!PRERACE:** 1,%

### NAME:Yrthak


### STAT:CON=11|INT=11|WIS=11|CHA=11|STR=10|DEX=10


### STARTPACK:Zombie (Kobold) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Kobold)]

### RACE:Zombie (Kobold)

- **!PRERACE:** 1,%

### NAME:Zombie (Kobold)


### STARTPACK:Zombie (Human Commoner) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Human Commoner)]

### RACE:Zombie (Human Commoner)

- **!PRERACE:** 1,%

### NAME:Zombie (Human Commoner)


### STAT:DEX=10|STR=10|CON=10|INT=10|WIS=10|CHA=10


### STARTPACK:Zombie (Troglodyte) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Troglodyte)]

### RACE:Zombie (Troglodyte)

- **!PRERACE:** 1,%

### NAME:Zombie (Troglodyte)


### STARTPACK:Zombie (Bugbear) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Bugbear)]

### RACE:Zombie (Bugbear)

- **!PRERACE:** 1,%

### NAME:Zombie (Bugbear)


### STARTPACK:Zombie (Ogre) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Ogre)]

### RACE:Zombie (Ogre)

- **!PRERACE:** 1,%

### NAME:Zombie (Ogre)


### STARTPACK:Zombie (Minotaur) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Minotaur)]

### RACE:Zombie (Minotaur)

- **!PRERACE:** 1,%

### NAME:Zombie (Minotaur)


### STARTPACK:Zombie (Wyvern) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Wyvern)]

### RACE:Zombie (Wyvern)

- **!PRERACE:** 1,%

### NAME:Zombie (Wyvern)


### STARTPACK:Zombie (Gray Render) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Zombie (Gray Render)]

### RACE:Zombie (Gray Render)

- **!PRERACE:** 1,%

### NAME:Zombie (Gray Render)


### STARTPACK:Ape Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ape]

### RACE:Ape

- **!PRERACE:** 1,%

### NAME:Ape


### STARTPACK:Baboon Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Baboon]

### RACE:Baboon

- **!PRERACE:** 1,%

### NAME:Baboon


### STARTPACK:Badger Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Badger]

### RACE:Badger

- **!PRERACE:** 1,%

### NAME:Badger


### ABILITY:CATEGORY=FEAT|Agile


### STARTPACK:Bat Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bat]

### RACE:Bat

- **!PRERACE:** 1,%

### NAME:Bat


### STARTPACK:Bear (Black) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bear (Black)]

### RACE:Bear (Black)

- **!PRERACE:** 1,%

### NAME:Black Bear


### STARTPACK:Bear (Brown) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bear (Brown)]

### RACE:Bear (Brown)

- **!PRERACE:** 1,%

### NAME:Brown Bear


### STARTPACK:Bear (Polar) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bear (Polar)]

### RACE:Bear (Polar)

- **!PRERACE:** 1,%

### NAME:Polar Bear


### STARTPACK:Bison Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bison]

### RACE:Bison

- **!PRERACE:** 1,%

### NAME:Bison


### STAT:WIS=11|STR=10|DEX=10|CON=10|INT=10|CHA=10


### STARTPACK:Boar Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Boar]

### RACE:Boar

- **!PRERACE:** 1,%

### NAME:Boar


### STARTPACK:Camel Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Camel%]

### RACE:Camel

- **!PRERACE:** 1,%

### NAME:Camel


### STARTPACK:Camel (Bactrian) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Camel (Bactrian)]

### RACE:Camel (Bactrian)

- **!PRERACE:** 1,%

### KIT:Camel Default


### NAME:Bactrian Camel


### STARTPACK:Cat Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Cat]

### RACE:Cat

- **!PRERACE:** 1,%

### NAME:Cat


### STARTPACK:Cheetah Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Cheetah]

### RACE:Cheetah

- **!PRERACE:** 1,%

### NAME:Cheetah


### STARTPACK:Crocodile Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Crocodile]

### RACE:Crocodile

- **!PRERACE:** 1,%

### NAME:Crocodile


### ABILITY:CATEGORY=FEAT|Skill Focus(Hide)


### STARTPACK:Crocodile (Giant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Crocodile (Giant)]

### RACE:Crocodile (Giant)

- **!PRERACE:** 1,%

### NAME:Giant Crocodile


### STARTPACK:Dog Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dog]

### RACE:Dog

- **!PRERACE:** 1,%

### NAME:Dog


### STARTPACK:Dog (Riding) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dog (Riding)]

### RACE:Dog (Riding)

- **!PRERACE:** 1,%

### NAME:Riding Dog


### STARTPACK:Donkey Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Donkey]

### RACE:Donkey

- **!PRERACE:** 1,%

### NAME:Donkey


### STARTPACK:Eagle Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Eagle]

### RACE:Eagle

- **!PRERACE:** 1,%

### NAME:Eagle


### STARTPACK:Elephant Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elephant%]

### RACE:Elephant

- **!PRERACE:** 1,%

### NAME:Elephant


### ABILITY:CATEGORY=FEAT|Skill Focus(Listen)


### STARTPACK:Elephant (Indian) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elephant (Indian)]

### RACE:Elephant (Indian)

- **!PRERACE:** 1,%

### KIT:Elephant Default


### NAME:Indian Elephant


### STARTPACK:Hawk Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hawk]

### RACE:Hawk

- **!PRERACE:** 1,%

### NAME:Hawk


### STARTPACK:Horse (Heavy) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Horse (Heavy)]

### RACE:Horse (Heavy)

- **!PRERACE:** 1,%

### NAME:Heavy Horse


### STARTPACK:Horse (Light) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Horse (Light)]

### RACE:Horse (Light)

- **!PRERACE:** 1,%

### NAME:Light Horse


### STARTPACK:Horse (Warhorse Heavy) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Horse (Warhorse Heavy)]

### RACE:Horse (Warhorse Heavy)

- **!PRERACE:** 1,%

### NAME:Heavy Warhorse


### STARTPACK:Horse (Warhorse Light) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Horse (Warhorse Light)]

### RACE:Horse (Warhorse Light)

- **!PRERACE:** 1,%

### NAME:Light Warhorse


### STARTPACK:Hyena Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hyena]

### RACE:Hyena

- **!PRERACE:** 1,%

### NAME:Hyena


### STARTPACK:Leopard Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Leopard]

### RACE:Leopard

- **!PRERACE:** 1,%

### NAME:Leopard


### STARTPACK:Lion Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lion]

### RACE:Lion

- **!PRERACE:** 1,%

### NAME:Lion


### STARTPACK:Lizard Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lizard]

### RACE:Lizard

- **!PRERACE:** 1,%

### NAME:Lizard


### STARTPACK:Lizard (Monitor) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lizard (Monitor)]

### RACE:Lizard (Monitor)

- **!PRERACE:** 1,%

### NAME:Monitor Lizard


### STARTPACK:Manta Ray Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Manta Ray]

### RACE:Manta Ray

- **!PRERACE:** 1,%

### NAME:Manta Ray


### STARTPACK:Monkey Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monkey]

### RACE:Monkey

- **!PRERACE:** 1,%

### NAME:Monkey


### STARTPACK:Mule Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mule]

### RACE:Mule

- **!PRERACE:** 1,%

### NAME:Mule


### STARTPACK:Octopus Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Octopus]

### RACE:Octopus

- **!PRERACE:** 1,%

### NAME:Octopus


### STARTPACK:Octopus (Giant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Octopus (Giant)]

### RACE:Octopus (Giant)

- **!PRERACE:** 1,%

### NAME:Giant Octopus


### STARTPACK:Owl Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Owl]

### RACE:Owl

- **!PRERACE:** 1,%

### NAME:Owl


### STARTPACK:Pony Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Pony]

### RACE:Pony

- **!PRERACE:** 1,%

### NAME:Pony


### STARTPACK:Pony (War) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Pony (War)]

### RACE:Pony (War)

- **!PRERACE:** 1,%

### NAME:War Pony


### STARTPACK:Porpoise Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Porpoise]

### RACE:Porpoise

- **!PRERACE:** 1,%

### NAME:Porpoise


### STARTPACK:Rat Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Rat]

### RACE:Rat

- **!PRERACE:** 1,%

### NAME:Rat


### STARTPACK:Raven Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Raven]

### RACE:Raven

- **!PRERACE:** 1,%

### NAME:Raven


### STARTPACK:Rhinoceros Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Rhinoceros]

### RACE:Rhinoceros

- **!PRERACE:** 1,%

### NAME:Rhinoceros


### ABILITY:CATEGORY=FEAT|Improved Natural Attack(Gore)


### STARTPACK:Shark (Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shark (Medium)]

### RACE:Shark (Medium)

- **!PRERACE:** 1,%

### NAME:Medium Shark


### STARTPACK:Shark (Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shark (Large)]

### RACE:Shark (Large)

- **!PRERACE:** 1,%

### NAME:Large Shark


### STARTPACK:Shark (Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shark (Huge)]

### RACE:Shark (Huge)

- **!PRERACE:** 1,%

### NAME:Huge Shark


### STARTPACK:Snake (Constrictor) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Constrictor)]

### RACE:Snake (Constrictor)

- **!PRERACE:** 1,%

### NAME:Constrictor Snake


### STARTPACK:Snake (Constrictor/Giant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Constrictor/Giant)]

### RACE:Snake (Constrictor/Giant)

- **!PRERACE:** 1,%

### NAME:Giant Constrictor Snake


### STARTPACK:Snake (Viper/Tiny) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Tiny)]

### RACE:Snake (Viper/Tiny)

- **!PRERACE:** 1,%

### NAME:Tiny Viper


### STARTPACK:Snake (Viper/Small) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Small)]

### RACE:Snake (Viper/Small)

- **!PRERACE:** 1,%

### NAME:Small Viper


### STARTPACK:Snake (Viper/Medium) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Medium)]

### RACE:Snake (Viper/Medium)

- **!PRERACE:** 1,%

### NAME:Medium Viper


### STARTPACK:Snake (Viper/Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Large)]

### RACE:Snake (Viper/Large)

- **!PRERACE:** 1,%

### NAME:Large Viper


### STARTPACK:Snake (Viper/Huge) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Huge)]

### RACE:Snake (Viper/Huge)

- **!PRERACE:** 1,%

### NAME:Huge Viper


### STARTPACK:Squid Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Squid]

### RACE:Squid

- **!PRERACE:** 1,%

### NAME:Squid


### STARTPACK:Squid (Giant) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Squid (Giant)]

### RACE:Squid (Giant)

- **!PRERACE:** 1,%

### NAME:Giant Squid


### ABILITY:CATEGORY=FEAT|Diehard


### STARTPACK:Tiger Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Tiger]

### RACE:Tiger

- **!PRERACE:** 1,%

### NAME:Tiger


### STARTPACK:Toad Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Toad]

### RACE:Toad

- **!PRERACE:** 1,%

### NAME:Toad


### STARTPACK:Weasel Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Weasel]

### RACE:Weasel

- **!PRERACE:** 1,%

### NAME:Weasel


### STARTPACK:Whale (Baleen) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Whale (Baleen)]

### RACE:Whale (Baleen)

- **!PRERACE:** 1,%

### NAME:Baleen Whale


### STARTPACK:Whale (Cachalot) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Whale (Cachalot)]

### RACE:Whale (Cachalot)

- **!PRERACE:** 1,%

### NAME:Cachalot Whale


### STARTPACK:Whale (Orca) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Whale (Orca)]

### RACE:Whale (Orca)

- **!PRERACE:** 1,%

### NAME:Orca Whale


### STARTPACK:Wolf Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Wolf]

### RACE:Wolf

- **!PRERACE:** 1,%

### NAME:Wolf


### STARTPACK:Wolverine Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Wolverine]

### RACE:Wolverine

- **!PRERACE:** 1,%

### NAME:Wolverine


### STARTPACK:Bat Familiar


### STARTPACK:Cat Familiar


### STARTPACK:Hawk Familiar


### STARTPACK:Lizard Familiar


### STARTPACK:Owl Familiar


### STARTPACK:Rat Familiar


### STARTPACK:Raven Familiar


### STARTPACK:Snake Familiar


### STARTPACK:Toad Familiar


### STARTPACK:Weasel Familiar


### STARTPACK:Aboleth Mage

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Aboleth]

### STAT:STR=12|DEX=14|CON=14|INT=16|WIS=10|CHA=8


### NAME:Aboleth Mage


### SKILL:Knowledge (History)

- **RANK:** 10

### CLASS:Wizard

- **LEVEL:** 10
- **SUBCLASS:** Wizard

### ABILITY:CATEGORY=Wizard Feat|Empower Spell


### SKILL:Decipher Script

- **RANK:** 10

### ABILITY:CATEGORY=FEAT|Eschew Materials


### ABILITY:CATEGORY=FEAT|Spell Focus(Illusion)

- **FREE:** YES

### ABILITY:CATEGORY=FEAT|Spell Penetration


### SPELLS:SPELLBOOK=Prepared Spells|Daze|Detect Magic=2|Resistance|Alarm|Charm Person|Color Spray|Mage Armor|Magic Missile=2|Blur|Bull's Strength|Darkness|Fox's Cunning|See Invisibility|Dispel Magic|Displacement|Fly|Lightning Bolt|Invisibility (Greater)|Phantasmal Killer|Scrying|Stoneskin|Hold Monster|Lightning Bolt[Empower Spell]|Wall of Force


### STARTPACK:Hound Archon Hero

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Archon (Hound Archon)]

### NAME:Hound Archon Hero


### CLASS:Paladin

- **LEVEL:** 11

### STAT:STR=17|DEX=10|CON=14|INT=8|WIS=12|CHA=14


### ABILITY:CATEGORY=FEAT|Leadership


### ABILITY:CATEGORY=FEAT|Weapon Focus(Greatsword)


### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Paladin|Bull's Strength|Divine Favor|Eagle's Splendor|Protection from Evil


### STARTPACK:Aboleth with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Aboleth]

### KIT:Aboleth Default


### KIT:Treasure Table


### STARTPACK:Achaierai with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Achaierai]

### KIT:Achaierai Default


### STARTPACK:Angel (Astral Deva) with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Angel (Astral Deva)]

### KIT:Angel (Astral Deva) Default


### KIT:Treasure Table Goods CR14


### KIT:Treasure Table Items CR14


### STARTPACK:Angel (Planetar) with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Angel (Planetar)]

### KIT:Angel (Planetar) Default


### KIT:Treasure Table Goods CR16


### KIT:Treasure Table Items CR16


### STARTPACK:Angel (Solar) with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Angel (Solar)]

### KIT:Angel (Solar) Default


### KIT:Treasure Table Goods CR20


### KIT:Treasure Table Items CR20


### STARTPACK:Aranea with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Aranea]

### KIT:Aranea Default


### KIT:Treasure Table Coins CR4


### KIT:Treasure Table Goods CR4


### KIT:Treasure Table Items CR4


### STARTPACK:Archon (Hound Archon) with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Archon (Hound Archon)]

### KIT:Archon (Hound Archon) Default


### STARTPACK:Archon (Trumpet Archon) with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Archon (Trumpet Archon)]

### KIT:Archon (Trumpet Archon) Default


### STARTPACK:Assassin Vine with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Assassin Vine]

### KIT:Assassin Vine Default


### KIT:Treasure Table 1/10 Coins CR3


### SELECT:roll("1d100")


### KIT:Treasure Table Goods CR3

- **OPTION:** 1,50

### KIT:Treasure Table Items CR3

- **OPTION:** 1,50

### STARTPACK:Athach with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Athach]

### KIT:Athach Default


### KIT:Treasure Table 1/2 Coins CR8


### KIT:Treasure Table Goods CR8


### KIT:Treasure Table Items CR8


### STARTPACK:Avoral with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Avoral]

### KIT:Avoral Default


### KIT:Treasure Table Goods CR9


### KIT:Treasure Table Items CR9


### STARTPACK:Azer with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Azer]

### KIT:Azer Default


### KIT:Treasure Table Coins CR2


### KIT:Treasure Table Goods CR2


### KIT:Treasure Table Items CR2


### STARTPACK:Barghest with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Barghest]

### KIT:Barghest Default


### STARTPACK:Barghest (Greater) with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Barghest (Greater)]

### KIT:Barghest (Greater) Default


### STARTPACK:Basilisk (Abyssal/Greater) with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Basilisk]

### KIT:Basilisk (Abyssal/Greater) Default


### STARTPACK:Behir with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Behir]

### KIT:Behir Default


### STARTPACK:Bralani with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bralani]

### KIT:Bralani Default


### KIT:Treasure Table Goods CR6


### KIT:Treasure Table Items CR6


### STARTPACK:Bugbear with Treasure Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bugbear]

### KIT:Bugbear Default


### STARTPACK:Frost Giant Jarl

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Giant (Frost)]

### NAME:Frost Giant Jarl


### STAT:STR=14|DEX=14|CON=12|INT=10|WIS=8|CHA=16


### CLASS:Blackguard

- **LEVEL:** 8

### ABILITY:CATEGORY=FEAT|Quick Draw


### GEAR:Ring of Energy Resistance (Minor/Fire)

- **LOCATION:** Equipped

### GEAR:Cloak of Charisma +2

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Poison (Bloodroot)

- **QTY:** 2
- **LOCATION:** Carried

### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Blackguard|Bull's Strength|Cause Fear|Doom|Magic Weapon


### STARTPACK:Harpy Archer

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Harpy]

### NAME:Harpy Archer


### STAT:STR=12|DEX=16|CON=14|INT=10|WIS=9|CHA=13


### ABILITY:CATEGORY=Fighter Feat|Weapon Focus(Longbow)


### ABILITY:CATEGORY=Fighter Feat|Point Blank Shot


### ABILITY:CATEGORY=Fighter Feat|Weapon Specialization(Longbow)


### ABILITY:CATEGORY=FEAT|Improved Critical(Longbow)


### ABILITY:CATEGORY=Fighter Feat|Manyshot


### GEAR:Arrow

- **QTY:** 10
- **SIZE:** PC
- **LOCATION:** Carried
- **EQMOD:** C_IRON

### GEAR:Bracers of Archery (Lesser)

- **SIZE:** PC
- **LOCATION:** Equipped

### GEAR:Potion (Cat's Grace)

- **SIZE:** PC
- **LOCATION:** Carried

### GEAR:Potion (Cure Moderate Wounds)

- **SIZE:** PC
- **LOCATION:** Carried

### GEAR:Ring of Protection +1

- **SIZE:** PC
- **LOCATION:** Equipped

### STARTPACK:Nessian Warhound

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hell Hound]

### NAME:Nessian Warhound


### CLASS:Outsider

- **LEVEL:** 8

### ABILITY:CATEGORY=FEAT|Weapon Focus (Bite)


### ABILITY:CATEGORY=FEAT|Improved Critical (Bite)


### ABILITY:CATEGORY=FEAT|Armor Proficiency (Light)

- **FREE:** YES

### GEAR:Barding (Chain Shirt)

- **SIZE:** PC
- **LOCATION:** Equipped
- **EQMOD:** PLUS2A

### STAT:STR=16|DEX=14|CON=14|INT=8|WIS=12|CHA=10


### STARTPACK:Default Giant Rock (Huge)

- **EQUIPBUY:** 0

### GEAR:Giant Rock (Huge)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Default Giant Rock (Large)

- **EQUIPBUY:** 0

### GEAR:Giant Rock (Large)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Default Giant Rock (Fire)

- **EQUIPBUY:** 0

### GEAR:Giant Rock (Fire Giant)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Default Giant Rock (Stone)

- **EQUIPBUY:** 0

### GEAR:Giant Rock (Stone Giant)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Default Giant Rock (Cloud)

- **EQUIPBUY:** 0

### GEAR:Giant Rock (Cloud Giant)

- **SIZE:** PC
- **LOCATION:** Carried

### STARTPACK:Golden Protector

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lammasu]

### NAME:Golden Protector


### STAT:STR=8|DEX=15|CON=14|INT=10|WIS=14|CHA=12


### CLASS:Lammasu

- **LEVEL:** 3

### TEMPLATE:Celestial|Half-Dragon (Gold)


### GEAR:Bracers of Armor +2

- **SIZE:** PC
- **LOCATION:** Equipped

### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Aid|Bear's Endurance|Bless=2|Bull's Strength|Daylight|Detect Evil|Detect Magic|Dismissal|Dispel Magic|Divine Favor=2|Entropic Shield|Guidance=2|Holy Smite|Light|Magic Circle against Evil|Neutralize Poison|Protection from Evil|Read Magic|Remove Curse|Resist Energy|Resistance|Restoration (Lesser)


### STARTPACK:Mummy Lord

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Mummy]

### STAT:STR=12|DEX=12|INT=12|WIS=16|CHA=13


### NAME:Mummy Lord


### CLASS:Cleric

- **LEVEL:** 10

### GEAR:Brooch of Shielding

- **LOCATION:** Equipped

### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Detect Magic=2|Guidance|Read Magic|Resistance|Virtue|Bane|Command|Deathwatch|Divine Favor|Doom|Sanctuary|Shield of Faith|Bull's Strength|Death Knell|Hold Person|Resist Energy|Silence|Spiritual Weapon|Animate Dead|Deeper Darkness|Dispel Magic|Invisibility Purge|Searing Light|Air Walk|Dismissal|Divine Power|Giant Vermin|Spell Immunity|Insect Plague|Slay Living|Spell Resistance|Symbol of Pain


### STARTPACK:Nightmare (Cauchemar)

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Nightmare]

### STAT:STR=15|DEX=12|CON=14|INT=14|WIS=10|CHA=10


### TEMPLATE:Default Cauchemar Nightmare


### NAME:Nightmare, Cauchemar


### STARTPACK:Ogre Barbarian

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ogre]

### NAME:Ogre Barbarian


### STAT:STR=16|DEX=13|CON=14|INT=12|WIS=10|CHA=8


### CLASS:Barbarian

- **LEVEL:** 4

### STARTPACK:Elder Black Pudding

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ooze (Black Pudding)]

### NAME:Elder Black Pudding


### STAT:STR=12|DEX=10|CON=12|WIS=10|CHA=10


### CLASS:Ooze

- **LEVEL:** 10

### STARTPACK:Greater Shadow

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shadow]

### NAME:Greater Shadow


### STAT:DEX=11|INT=10|WIS=10|CHA=12


### CLASS:Undead

- **LEVEL:** 6

### STARTPACK:Troll Hunter

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Troll]

### NAME:Troll Hunter


### STAT:STR=13|DEX=8|CON=10|INT=14|WIS=17|CHA=14


### CLASS:Ranger

- **LEVEL:** 6

### ABILITY:CATEGORY=Favored Enemy|Favored Enemy ~ Humanoid (Elf)


### ABILITY:CATEGORY=Ranger Combat Style|Combat Style ~ Two-Weapon Fighting


### ABILITY:CATEGORY=Favored Enemy Bonus|Favored Enemy Bonus ~ Humanoid (Elf)


### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Ranger|Entangle|Resist Energy


### STARTPACK:Celestial Charger

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Unicorn]

### NAME:Celestial Charger


### STAT:STR=14|DEX=12|CON=10|INT=13|WIS=17|CHA=8


### CLASS:Magical Beast

- **LEVEL:** 4

### TEMPLATE:Celestial


### ABILITY:CATEGORY=FEAT|Extra Turning


### ABILITY:CATEGORY=FEAT|Improved Turning


### GEAR:Bracers of Armor +5

- **LOCATION:** Equipped

### SPELLS:SPELLBOOK=Prepared Spells|CLASS=Cleric|Detect Magic|Detect Poison=2|Light|Virtue=2|Bless=2|Calm Animals|Obscuring Mist|Remove Fear|Sanctuary|Shield of Faith|Aid|Aid|Restoration (Lesser)|Remove Paralysis|Shield Other|Prayer|Protection from Energy|Remove Curse|Searing Light=2|Air Walk|Divine Power|Holy Smite|Restoration


### STARTPACK:Minor Armor and Shields

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Shield

- **OPTION:** 1,60

### KIT:+1 Armor

- **OPTION:** 61,80

### KIT:+2 Shield

- **OPTION:** 81,85

### KIT:+2 Armor

- **OPTION:** 86,87

### KIT:Minor Specific Armor

- **OPTION:** 88,89

### KIT:Minor Specific Shield

- **OPTION:** 90,91

### KIT:Minor Armor and Shields Special Ability

- **OPTION:** 92,100

### STARTPACK:Minor Armor and Shields Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Shield Minor Special Ability

- **OPTION:** 1,60

### KIT:+1 Armor Minor Special Ability

- **OPTION:** 61,80

### KIT:+2 Shield Minor Special Ability

- **OPTION:** 81,85

### KIT:+2 Armor Minor Special Ability

- **OPTION:** 86,87

### STARTPACK:Medium Armor and Shields

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Shield

- **OPTION:** 31,40

### KIT:+3 Armor

- **OPTION:** 41,50

### KIT:+4 Shield

- **OPTION:** 51,55

### KIT:+4 Armor

- **OPTION:** 56,57

### KIT:Medium Specific Armor

- **OPTION:** 58,60

### KIT:Medium Specific Shield

- **OPTION:** 61,63

### KIT:Medium Armor and Shields Special Ability

- **OPTION:** 64,100

### STARTPACK:Medium Armor and Shields Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Shield Medium Special Ability

- **OPTION:** 1,5

### KIT:+1 Armor Medium Special Ability

- **OPTION:** 6,10

### KIT:+2 Shield Medium Special Ability

- **OPTION:** 11,20

### KIT:+2 Armor Medium Special Ability

- **OPTION:** 21,30

### KIT:+3 Shield Medium Special Ability

- **OPTION:** 31,40

### KIT:+3 Armor Medium Special Ability

- **OPTION:** 41,50

### KIT:+4 Shield Medium Special Ability

- **OPTION:** 51,55

### KIT:+4 Armor Medium Special Ability

- **OPTION:** 56,57

### STARTPACK:Major Armor and Shields

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+5 Shield

- **OPTION:** 39,49

### KIT:+5 Armor

- **OPTION:** 50,57

### KIT:Major Specific Armor

- **OPTION:** 58,60

### KIT:Major Specific Shield

- **OPTION:** 61,63

### KIT:Major Armor and Shields Special Ability

- **OPTION:** 64,100

### STARTPACK:Major Armor and Shields Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Shield Major Special Ability

- **OPTION:** 1,8

### KIT:+3 Armor Major Special Ability

- **OPTION:** 9,16

### KIT:+4 Shield Major Special Ability

- **OPTION:** 17,27

### KIT:+4 Armor Major Special Ability

- **OPTION:** 28,38

### KIT:+5 Shield Major Special Ability

- **OPTION:** 39,49

### KIT:+5 Armor Major Special Ability

- **OPTION:** 50,57

### STARTPACK:+1 Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Shield (Tower/Wood)

- **SIZE:** PC
- **EQMOD:** Masterwork (Armor).PLUS1S
- **OPTION:** 96,100

### STARTPACK:+2 Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Minor Specific Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Darkwood Buckler

- **OPTION:** 1,30

### GEAR:Mithral Heavy Shield

- **OPTION:** 81,95

### GEAR:Caster's Shield

- **OPTION:** 96,100

### STARTPACK:Medium Specific Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Spined Shield

- **OPTION:** 86,90

### GEAR:Lion's Shield

- **OPTION:** 91,95

### GEAR:Winged Shield

- **OPTION:** 96,100

### STARTPACK:Major Specific Shield

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Absorbing Shield

- **OPTION:** 91,100

### STARTPACK:+1 Shield Minor Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### TABLE:Special Ability (B)

- **VALUES:** EQMOD:ARW_CAT|1,20|LOOKUP:Special Ability (B),roll("1d100")|21,40|EQMOD:BLIND|41,50|EQMOD:FRT_LGHT|51,75|EQMOD:ARW_DEF|76,92|EQMOD:ANMATD|93,97|EQMOD:SPELL_RES_13|98,99|[LOOKUP:Special Ability (B),roll("1d100")][LOOKUP:Special Ability (B),roll("1d100")]|100

### TABLE:Special Ability (L)

- **VALUES:** EQMOD:ARW_CAT|1,20|EQMOD:BASH_L|21,40|EQMOD:BLIND|41,50|EQMOD:FRT_LGHT|51,75|EQMOD:ARW_DEF|76,92|EQMOD:ANMATD|93,97|EQMOD:SPELL_RES_13|98,99|[LOOKUP:Special Ability (L),roll("1d100")][LOOKUP:Special Ability (L),roll("1d100")]|100

### TABLE:Special Ability (H)

- **VALUES:** EQMOD:ARW_CAT|1,20|EQMOD:BASH_H|21,40|EQMOD:BLIND|41,50|EQMOD:FRT_LGHT|51,75|EQMOD:ARW_DEF|76,92|EQMOD:ANMATD|93,97|EQMOD:SPELL_RES_13|98,99|[LOOKUP:Special Ability (H),roll("1d100")][LOOKUP:Special Ability (H),roll("1d100")]|100

### TABLE:Special Ability (T)

- **VALUES:** EQMOD:ARW_CAT|1,20|LOOKUP:Special Ability (T),roll("1d100")|21,40|EQMOD:BLIND|41,50|EQMOD:FRT_LGHT|51,75|EQMOD:ARW_DEF|76,92|EQMOD:ANMATD|93,97|EQMOD:SPELL_RES_13|98,99|[LOOKUP:Special Ability (T),roll("1d100")][LOOKUP:Special Ability (T),roll("1d100")]|100

### STARTPACK:+2 Shield Minor Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+1 Shield Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Shield Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Shield Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Shield Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Shield Major Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Shield Major Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Shield Major Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+1 Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Padded

- **SIZE:** PC
- **EQMOD:** Masterwork (Armor).PLUS1A
- **OPTION:** 1

### GEAR:Splint Mail

- **SIZE:** PC
- **EQMOD:** Masterwork (Armor).PLUS1A
- **OPTION:** 58

### STARTPACK:+2 Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Minor Specific Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Mithral Shirt

- **OPTION:** 1,50

### GEAR:Dragonhide Plate

- **OPTION:** 51,80

### GEAR:Elven Chain

- **OPTION:** 81,100

### STARTPACK:Medium Specific Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Rhino Hide

- **OPTION:** 58,67

### GEAR:Adamantine Breastplate

- **OPTION:** 68,82

### GEAR:Dwarven Plate

- **OPTION:** 83,97

### GEAR:Banded Mail of Luck

- **OPTION:** 98,100

### STARTPACK:Major Specific Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Celestial Armor

- **OPTION:** 33,50

### GEAR:Plate Armor of the Deep

- **OPTION:** 51,60

### GEAR:Breastplate of Command

- **OPTION:** 61,75

### GEAR:Mithral Full Plate of Speed

- **OPTION:** 76,90

### GEAR:Demon Armor

- **OPTION:** 91,100

### STARTPACK:+1 Armor Minor Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### TABLE:Special Ability

- **VALUES:** EQMOD:GLAM|1,25|EQMOD:FRT_LGHT|26,32|EQMOD:SLK|33,52|EQMOD:SHDW|53,72|EQMOD:SLNT_MV|73,92|EQMOD:SPELL_RES_13|93,96|EQMOD:SLK_IMP|97|EQMOD:SHDW_IMP|98|EQMOD:SLNT_MV_IM|99|[LOOKUP:Special Ability,roll("1d100")][LOOKUP:Special Ability,roll("1d100")]|100

### STARTPACK:+2 Armor Minor Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+1 Armor Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Armor Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Armor Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Armor Medium Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Armor Major Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Armor Major Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Armor Major Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Art 55gp

- **OPTION:** 1,10

### KIT:Treasure Table Art 105gp

- **OPTION:** 11,25

### KIT:Treasure Table Art 350gp

- **OPTION:** 26,40

### KIT:Treasure Table Art 550gp

- **OPTION:** 41,50

### KIT:Treasure Table Art 700gp

- **OPTION:** 51,60

### KIT:Treasure Table Art 1050gp

- **OPTION:** 61,70

### KIT:Treasure Table Art 1400gp

- **OPTION:** 71,80

### KIT:Treasure Table Art 1750gp

- **OPTION:** 81,85

### KIT:Treasure Table Art 2500gp

- **OPTION:** 86,90

### KIT:Treasure Table Art 3500gp

- **OPTION:** 91,95

### KIT:Treasure Table Art 5000gp

- **OPTION:** 96,99

### KIT:Treasure Table Art 7000gp

- **OPTION:** 100

### STARTPACK:Treasure Table Art 55gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d4")


### GEAR:Art (Silver Ewer)

- **EQMOD:** ART|EVAL(roll("1d10")*10)
- **OPTION:** 1

### GEAR:Art (Statuette (Carved Bone))

- **EQMOD:** ART|EVAL(roll("1d10")*10)
- **OPTION:** 2

### GEAR:Art (Statuette (Ivory))

- **EQMOD:** ART|EVAL(roll("1d10")*10)
- **OPTION:** 3

### GEAR:Art (Bracelet (Small/Gold/Finely Wrought))

- **EQMOD:** ART|EVAL(roll("1d10")*10)
- **OPTION:** 4

### STARTPACK:Treasure Table Art 105gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d3")


### GEAR:Art (Vestments (Cloth of Gold))

- **EQMOD:** ART|EVAL(roll("3d6")*10)
- **OPTION:** 1

### GEAR:Art (Mask (Black Velvet with Numerous Citrines))

- **EQMOD:** ART|EVAL(roll("3d6")*10)
- **OPTION:** 2

### GEAR:Art (Chalice (Silver with Lapis Lazuli Gems)

- **EQMOD:** ART|EVAL(roll("3d6")*10)
- **OPTION:** 3

### STARTPACK:Treasure Table Art 350gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d2")


### GEAR:Art (Tapestry (Large/Wool/Well-Done))

- **EQMOD:** ART|EVAL(roll("1d6")*100)
- **OPTION:** 1

### GEAR:Art (Mug (Brass with Jade Inlays))

- **EQMOD:** ART|EVAL(roll("1d6")*100)
- **OPTION:** 2

### STARTPACK:Treasure Table Art 550gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Comb (Silver with Moonstones))

- **EQMOD:** ART|EVAL(roll("1d10")*100)
- **OPTION:** 1

### GEAR:Art (Longsword (Silver-Plated with Jet Jewel in Hilt))

- **EQMOD:** ART|EVAL(roll("1d10")*100)
- **OPTION:** 2

### STARTPACK:Treasure Table Art 700gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Harp (Carved Exotic Wood with Ivory Inlay and Zircon Gems))

- **EQMOD:** ART|EVAL(roll("2d6")*100)
- **OPTION:** 1

### GEAR:Art (Idol (Solid Gold 10 lb.))

- **EQMOD:** ART|EVAL(roll("2d6")*100)
- **OPTION:** 2

### STARTPACK:Treasure Table Art 1050gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Comb (Gold Dragon with Red Garnet Eye))

- **EQMOD:** ART|EVAL(roll("3d6")*100)
- **OPTION:** 1

### GEAR:Art (Stopper Cork (Gold and Topaz))

- **EQMOD:** ART|EVAL(roll("3d6")*100)
- **OPTION:** 2

### GEAR:Art (Dagger (Ceremonial Electrum with Star Ruby in the Pommel))

- **EQMOD:** ART|EVAL(roll("3d6")*100)
- **OPTION:** 3

### STARTPACK:Treasure Table Art 1400gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Eyepatch (Mock Eye of Sapphire and Moonstone))

- **EQMOD:** ART|EVAL(roll("4d6")*100)
- **OPTION:** 1

### GEAR:Art (Pendant (Fire Opal on Fine Gold Chain))

- **EQMOD:** ART|EVAL(roll("4d6")*100)
- **OPTION:** 2

### GEAR:Art (Painting (Old Masterpiece))

- **EQMOD:** ART|EVAL(roll("4d6")*100)
- **OPTION:** 3

### STARTPACK:Treasure Table Art 1750gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Mantle (Embroidered Silk and Velvet with Numerous Moonstones))

- **EQMOD:** ART|EVAL(roll("5d6")*100)
- **OPTION:** 1

### GEAR:Art (Pendant (Sapphire on Gold Chain))

- **EQMOD:** ART|EVAL(roll("5d6")*100)
- **OPTION:** 1

### STARTPACK:Treasure Table Art 2500gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Glove (Embroidered and Bejeweled))

- **EQMOD:** ART|EVAL(roll("1d4")*1000)
- **OPTION:** 1

### GEAR:Art (Anklet (Jeweled))

- **EQMOD:** ART|EVAL(roll("1d4")*1000)
- **OPTION:** 2

### GEAR:Art (Music Box (Gold))

- **EQMOD:** ART|EVAL(roll("1d4")*1000)
- **OPTION:** 3

### STARTPACK:Treasure Table Art 3500gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Circlet (Golden with Four Aquamarines))

- **EQMOD:** ART|EVAL(roll("1d6")*1000)
- **OPTION:** 1

### GEAR:Art (Necklace (String of Small Pink Pearls))

- **EQMOD:** ART|EVAL(roll("1d6")*1000)
- **OPTION:** 2

### STARTPACK:Treasure Table Art 5000gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Crown (Jeweled Gold))

- **EQMOD:** ART|EVAL(roll("2d4")*1000)
- **OPTION:** 1

### GEAR:Art (Ring (Jeweled Electrum))

- **EQMOD:** ART|EVAL(roll("2d4")*1000)
- **OPTION:** 2

### STARTPACK:Treasure Table Art 7000gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Art (Ring (Gold and Ruby))

- **EQMOD:** ART|EVAL(roll("2d6")*1000)
- **OPTION:** 1

### GEAR:Art (Cup (Gold Set with Emeralds))

- **EQMOD:** ART|EVAL(roll("2d6")*1000)
- **OPTION:** 2

### STARTPACK:Treasure Table

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Coins CR1

- **PREVAREQ:** CR,1

### KIT:Treasure Table Goods CR1

- **PREVAREQ:** CR,1

### KIT:Treasure Table Items CR1

- **PREVAREQ:** CR,1

### KIT:Treasure Table Coins CR3

- **PREVAREQ:** CR,3

### KIT:Treasure Table Coins CR5

- **PREVAREQ:** CR,5

### KIT:Treasure Table Goods CR5

- **PREVAREQ:** CR,5

### KIT:Treasure Table Items CR5

- **PREVAREQ:** CR,5

### KIT:Treasure Table Coins CR6

- **PREVAREQ:** CR,6

### KIT:Treasure Table Coins CR7

- **PREVAREQ:** CR,7

### KIT:Treasure Table Goods CR7

- **PREVAREQ:** CR,7

### KIT:Treasure Table Items CR7

- **PREVAREQ:** CR,7

### KIT:Treasure Table Coins CR8

- **PREVAREQ:** CR,8

### KIT:Treasure Table Coins CR9

- **PREVAREQ:** CR,9

### KIT:Treasure Table Coins CR10

- **PREVAREQ:** CR,10

### KIT:Treasure Table Goods CR10

- **PREVAREQ:** CR,10

### KIT:Treasure Table Items CR10

- **PREVAREQ:** CR,10

### KIT:Treasure Table Coins CR11

- **PREVAREQ:** CR,11

### KIT:Treasure Table Goods CR11

- **PREVAREQ:** CR,11

### KIT:Treasure Table Items CR11

- **PREVAREQ:** CR,11

### KIT:Treasure Table Coins CR12

- **PREVAREQ:** CR,12

### KIT:Treasure Table Goods CR12

- **PREVAREQ:** CR,12

### KIT:Treasure Table Items CR12

- **PREVAREQ:** CR,12

### KIT:Treasure Table Coins CR13

- **PREVAREQ:** CR,13

### KIT:Treasure Table Goods CR13

- **PREVAREQ:** CR,13

### KIT:Treasure Table Items CR13

- **PREVAREQ:** CR,13

### KIT:Treasure Table Coins CR14

- **PREVAREQ:** CR,14

### KIT:Treasure Table Coins CR15

- **PREVAREQ:** CR,15

### KIT:Treasure Table Goods CR15

- **PREVAREQ:** CR,15

### KIT:Treasure Table Items CR15

- **PREVAREQ:** CR,15

### KIT:Treasure Table Coins CR16

- **PREVAREQ:** CR,16

### KIT:Treasure Table Coins CR17

- **PREVAREQ:** CR,17

### KIT:Treasure Table Goods CR17

- **PREVAREQ:** CR,17

### KIT:Treasure Table Items CR17

- **PREVAREQ:** CR,17

### KIT:Treasure Table Coins CR18

- **PREVAREQ:** CR,18

### KIT:Treasure Table Goods CR18

- **PREVAREQ:** CR,18

### KIT:Treasure Table Items CR18

- **PREVAREQ:** CR,18

### KIT:Treasure Table Coins CR19

- **PREVAREQ:** CR,19

### KIT:Treasure Table Goods CR19

- **PREVAREQ:** CR,19

### KIT:Treasure Table Items CR19

- **PREVAREQ:** CR,19

### KIT:Treasure Table Coins CR20

- **PREVARGTEQ:** CR,20

### KIT:Treasure Table Major Magic Items

- **PREVARGTEQ:** CR,21

### STARTPACK:Treasure Table Standard CR01

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR02

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR03

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR04

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR05

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR06

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR07

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR08

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR09

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR11

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR13

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR14

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR15

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR16

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR17

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR18

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR19

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR20

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR21

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR22

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR23

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR24

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR25

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR26

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR27

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR28

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR29

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Standard CR30

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR1

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR01

### GEAR:Coin (Copper)

- **QTY:** roll("1d6")*1000
- **OPTION:** 15,29

### GEAR:Coin (Silver)

- **QTY:** roll("1d8")*100
- **OPTION:** 30,52

### GEAR:Coin (Gold)

- **QTY:** roll("2d8")*10
- **OPTION:** 53,95

### GEAR:Coin (Platinum)

- **QTY:** roll("1d4")*10
- **OPTION:** 96,100

### STARTPACK:Treasure Table Coins CR2

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR02

### STARTPACK:Treasure Table Coins CR3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR03

### STARTPACK:Treasure Table Coins CR4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR04

### STARTPACK:Treasure Table Coins CR5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR05

### STARTPACK:Treasure Table Coins CR6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR06

### STARTPACK:Treasure Table Coins CR7

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR07

### STARTPACK:Treasure Table Coins CR8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR08

### STARTPACK:Treasure Table Coins CR9

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Coins CR09

### STARTPACK:Treasure Table Coins CR10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR11

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR13

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR14

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR15

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR16

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR17

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR18

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR19

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Coins CR20

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR1

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR01

### STARTPACK:Treasure Table 1/2 Coins CR2

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR02

### STARTPACK:Treasure Table 1/2 Coins CR3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR03

### STARTPACK:Treasure Table 1/2 Coins CR4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR04

### STARTPACK:Treasure Table 1/2 Coins CR5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR05

### STARTPACK:Treasure Table 1/2 Coins CR6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR06

### STARTPACK:Treasure Table 1/2 Coins CR7

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR07

### STARTPACK:Treasure Table 1/2 Coins CR8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR08

### STARTPACK:Treasure Table 1/2 Coins CR9

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/2 Coins CR09

### STARTPACK:Treasure Table 1/2 Coins CR10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR11

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR13

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR14

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR15

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR16

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR17

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR18

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR19

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/2 Coins CR20

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR1

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR01

### STARTPACK:Treasure Table 1/10 Coins CR2

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR02

### STARTPACK:Treasure Table 1/10 Coins CR3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR03

### STARTPACK:Treasure Table 1/10 Coins CR4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR04

### STARTPACK:Treasure Table 1/10 Coins CR5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR05

### STARTPACK:Treasure Table 1/10 Coins CR6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR06

### STARTPACK:Treasure Table 1/10 Coins CR7

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR07

### STARTPACK:Treasure Table 1/10 Coins CR8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR08

### STARTPACK:Treasure Table 1/10 Coins CR9

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table 1/10 Coins CR09

### STARTPACK:Treasure Table 1/10 Coins CR10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR11

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR13

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR14

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR15

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR16

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR17

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR18

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR19

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table 1/10 Coins CR20

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Gems

- **APPLY:** INSTANT

### KIT:Treasure Table Gems 10gp

- **OPTION:** 1,25

### KIT:Treasure Table Gems 50gp

- **OPTION:** 26,50

### KIT:Treasure Table Gems 100gp

- **OPTION:** 51,70

### KIT:Treasure Table Gems 500gp

- **OPTION:** 71,90

### KIT:Treasure Table Gems 1000gp

- **OPTION:** 91,99

### KIT:Treasure Table Gems 5000gp

- **OPTION:** 100

### STARTPACK:Treasure Table Gems 10gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d13")


### GEAR:Gem (Agate (Banded))

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 1

### GEAR:Gem (Agate (Eye))

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 2

### GEAR:Gem (Agate (Moss))

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 3

### GEAR:Gem (Azurite)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 4

### GEAR:Gem (Quartz (Blue))

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 5

### GEAR:Gem (Hematite)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 6

### GEAR:Gem (Lapis Lazuli)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 7

### GEAR:Gem (Malachite)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 8

### GEAR:Gem (Obsidian)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 9

### GEAR:Gem (Rhodochrosite)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 10

### GEAR:Gem (Tiger Eye)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 11

### GEAR:Gem (Turquoise)

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 12

### GEAR:Gem (Pearl (Freshwater/Irregular))

- **EQMOD:** GEM|EVAL(roll("4d4"))
- **OPTION:** 13

### STARTPACK:Treasure Table Gems 50gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d17")


### GEAR:Gem (Bloodstone)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 1

### GEAR:Gem (Carnelian)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 2

### GEAR:Gem (Chalcedony)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 3

### GEAR:Gem (Chrysoprase)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 4

### GEAR:Gem (Citrine)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 5

### GEAR:Gem (Iolite)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 6

### GEAR:Gem (Jasper)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 7

### GEAR:Gem (Moonstone)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 8

### GEAR:Gem (Onyx)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 9

### GEAR:Gem (Peridot)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 10

### GEAR:Gem (Rock Crystal (Clear Quartz))

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 11

### GEAR:Gem (Sard)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 12

### GEAR:Gem (Sardonyx)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 13

### GEAR:Gem (Quartz (Rose))

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 14

### GEAR:Gem (Quartz (Smoky))

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 15

### GEAR:Gem (Quartz (Star Rose))

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 16

### GEAR:Gem (Zircon)

- **EQMOD:** GEM|EVAL(roll("2d4")*10)
- **OPTION:** 17

### STARTPACK:Treasure Table Gems 100gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d16")


### GEAR:Gem (Amber)

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 1

### GEAR:Gem (Amethyst)

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 2

### GEAR:Gem (Chrysoberyl)

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 3

### GEAR:Gem (Coral)

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 4

### GEAR:Gem (Garnet (Red))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 5

### GEAR:Gem (Garnet (Brown-Green))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 6

### GEAR:Gem (Jade)

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 7

### GEAR:Gem (Jet)

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 8

### GEAR:Gem (Pearl (White))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 9

### GEAR:Gem (Pearl (Golden))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 10

### GEAR:Gem (Pearl (Pink))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 11

### GEAR:Gem (Pearl (Silver))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 12

### GEAR:Gem (Spinel (Red))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 13

### GEAR:Gem (Spinel (Red-Brown))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 14

### GEAR:Gem (Spinel (Deep Green))

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 15

### GEAR:Gem (Tourmaline)

- **EQMOD:** GEM|EVAL(roll("4d4")*10)
- **OPTION:** 16

### STARTPACK:Treasure Table Gems 500gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d6")


### GEAR:Gem (Alexandrite)

- **EQMOD:** GEM|EVAL(roll("2d4")*100)
- **OPTION:** 1

### GEAR:Gem (Aquamarine)

- **EQMOD:** GEM|EVAL(roll("2d4")*100)
- **OPTION:** 2

### GEAR:Gem (Garnet (Violet))

- **EQMOD:** GEM|EVAL(roll("2d4")*100)
- **OPTION:** 3

### GEAR:Gem (Pearl (Black))

- **EQMOD:** GEM|EVAL(roll("2d4")*100)
- **OPTION:** 4

### GEAR:Gem (Spinel (Deep Blue))

- **EQMOD:** GEM|EVAL(roll("2d4")*100)
- **OPTION:** 5

### GEAR:Gem (Topaz (Golden Yellow))

- **EQMOD:** GEM|EVAL(roll("2d4")*100)
- **OPTION:** 6

### STARTPACK:Treasure Table Gems 1000gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d10")


### GEAR:Gem (Emerald)

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 1

### GEAR:Gem (Opal (White))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 2

### GEAR:Gem (Opal (Black))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 3

### GEAR:Gem (Opal (Fire))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 4

### GEAR:Gem (Sapphire (Blue))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 5

### GEAR:Gem (Corundum (Firey Yellow))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 6

### GEAR:Gem (Corundum (Rich Purple))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 7

### GEAR:Gem (Star Sapphire (Blue))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 8

### GEAR:Gem (Star Sapphire (Black))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 9

### GEAR:Gem (Ruby (Star))

- **EQMOD:** GEM|EVAL(roll("4d4")*100)
- **OPTION:** 10

### STARTPACK:Treasure Table Gems 5000gp

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d7")


### GEAR:Gem (Emerald (Clearest Bright Green))

- **EQMOD:** GEM|EVAL(roll("2d4")*1000)
- **OPTION:** 1

### GEAR:Gem (Diamond (Blue-White))

- **EQMOD:** GEM|EVAL(roll("2d4")*1000)
- **OPTION:** 2

### GEAR:Gem (Diamond (Canary))

- **EQMOD:** GEM|EVAL(roll("2d4")*1000)
- **OPTION:** 3

### GEAR:Gem (Diamond (Pink))

- **EQMOD:** GEM|EVAL(roll("2d4")*1000)
- **OPTION:** 4

### GEAR:Gem (Diamond (Brown))

- **EQMOD:** GEM|EVAL(roll("2d4")*1000)
- **OPTION:** 5

### GEAR:Gem (Diamond (Blue))

- **EQMOD:** GEM|EVAL(roll("2d4")*1000)
- **OPTION:** 6

### GEAR:Gem (Jacinth)

- **EQMOD:** GEM|EVAL(roll("2d4")*1000)
- **OPTION:** 7

### STARTPACK:Treasure Table Goods CR1

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR01

### KIT:Treasure Table Gems

- **OPTION:** 91,95

### KIT:Treasure Table Art

- **OPTION:** 96,100

### STARTPACK:Treasure Table Goods CR2

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR02

### KIT:Treasure Table Gems 1d3

- **OPTION:** 82,95

### KIT:Treasure Table Art 1d3

- **OPTION:** 96,100

### STARTPACK:Treasure Table Goods CR3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR03

### STARTPACK:Treasure Table Goods CR4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR04

### KIT:Treasure Table Gems 1d4

- **OPTION:** 71,95

### STARTPACK:Treasure Table Goods CR5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR05

### KIT:Treasure Table Art 1d4

- **OPTION:** 96,100

### STARTPACK:Treasure Table Goods CR6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR06

### STARTPACK:Treasure Table Goods CR7

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR07

### STARTPACK:Treasure Table Goods CR8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR08

### KIT:Treasure Table Gems 1d6

- **OPTION:** 46,85

### STARTPACK:Treasure Table Goods CR9

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Goods CR09

### KIT:Treasure Table Gems 1d8

- **OPTION:** 41,80

### STARTPACK:Treasure Table Goods CR10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Art 1d6

- **OPTION:** 80,100

### STARTPACK:Treasure Table Goods CR11

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 1d10

- **OPTION:** 25,74

### STARTPACK:Treasure Table Goods CR12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Art 1d8

- **OPTION:** 71,100

### STARTPACK:Treasure Table Goods CR13

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 1d12

- **OPTION:** 12,66

### KIT:Treasure Table Art 1d10

- **OPTION:** 67,100

### STARTPACK:Treasure Table Goods CR14

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 2d8

- **OPTION:** 12,66

### KIT:Treasure Table Art 2d6

- **OPTION:** 67,100

### STARTPACK:Treasure Table Goods CR15

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 2d10

- **OPTION:** 10,65

### KIT:Treasure Table Art 2d8

- **OPTION:** 66,100

### STARTPACK:Treasure Table Goods CR16

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 4d6

- **OPTION:** 8,64

### KIT:Treasure Table Art 2d10

- **OPTION:** 65,100

### STARTPACK:Treasure Table Goods CR17

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 4d8

- **OPTION:** 5,63

### KIT:Treasure Table Art 3d8

- **OPTION:** 64,100

### STARTPACK:Treasure Table Goods CR18

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 3d12

- **OPTION:** 5,54

### KIT:Treasure Table Art 3d10

- **OPTION:** 55,100

### STARTPACK:Treasure Table Goods CR19

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 6d6

- **OPTION:** 4,50

### KIT:Treasure Table Art 6d6

- **OPTION:** 51,100

### STARTPACK:Treasure Table Goods CR20

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Gems 4d10

- **OPTION:** 3,38

### KIT:Treasure Table Art 7d6

- **OPTION:** 39,100

### STARTPACK:Treasure Table Gems 1d3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Gems 1d4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Gems 1d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Gems 1d8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d8")


### STARTPACK:Treasure Table Gems 1d10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Gems 1d12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("1d12")


### STARTPACK:Treasure Table Gems 2d8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("2d8")


### STARTPACK:Treasure Table Gems 2d10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("2d10")


### STARTPACK:Treasure Table Gems 4d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("4d6")


### STARTPACK:Treasure Table Gems 4d8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("4d8")


### STARTPACK:Treasure Table Gems 3d12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("3d12")


### STARTPACK:Treasure Table Gems 6d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("6d6")


### STARTPACK:Treasure Table Gems 4d10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("4d10")


### STARTPACK:Treasure Table Art 1d3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 1d4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 1d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 1d8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 1d10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 2d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("2d6")


### STARTPACK:Treasure Table Art 2d8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 2d10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 3d8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("3d8")


### STARTPACK:Treasure Table Art 3d10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("3d10")


### STARTPACK:Treasure Table Art 6d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Art 7d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("7d6")


### STARTPACK:Treasure Table Items CR1

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR01

### KIT:Treasure Table Mundane Items

- **OPTION:** 72,95

### KIT:Treasure Table Minor Magic Items

- **OPTION:** 96,100

### STARTPACK:Treasure Table Items CR2

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR02

### STARTPACK:Treasure Table Items CR3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR03

### KIT:Treasure Table Mundane Items 1d3

- **OPTION:** 50,79

### STARTPACK:Treasure Table Items CR4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR04

### KIT:Treasure Table Mundane Items 1d4

- **OPTION:** 43,62

### STARTPACK:Treasure Table Items CR5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR05

### KIT:Treasure Table Minor Magic Items 1d3

- **OPTION:** 68,100

### STARTPACK:Treasure Table Items CR6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR06

### KIT:Treasure Table Medium Magic Items

- **OPTION:** 100

### STARTPACK:Treasure Table Items CR7

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR07

### STARTPACK:Treasure Table Items CR8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR08

### KIT:Treasure Table Minor Magic Items 1d4

- **OPTION:** 49,96

### STARTPACK:Treasure Table Items CR9

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Treasure Table Items CR09

### STARTPACK:Treasure Table Items CR10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Items CR11

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Items CR12

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Minor Magic Items 1d6

- **OPTION:** 28,82

### STARTPACK:Treasure Table Items CR13

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Items CR14

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Items CR15

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Minor Magic Items 1d10

- **OPTION:** 12,46

### STARTPACK:Treasure Table Items CR16

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Medium Magic Items 1d3

- **OPTION:** 47,90

### STARTPACK:Treasure Table Items CR17

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Items CR18

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Medium Magic Items 1d4

- **OPTION:** 25,80

### STARTPACK:Treasure Table Items CR19

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Items CR20

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Major Magic Items 1d3

- **OPTION:** 66,100

### STARTPACK:Treasure Table Mundane Items 1d3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Mundane Items 1d4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Minor Magic Items 1d3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Minor Magic Items 1d4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Minor Magic Items 1d6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Minor Magic Items 1d10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Medium Magic Items 1d3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Medium Magic Items 1d4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Major Magic Items 1d3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Minor Magic Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Minor Armor and Shields

- **OPTION:** 1,4

### KIT:Minor Weapons

- **OPTION:** 5,9

### KIT:Minor Potions

- **OPTION:** 10,44

### KIT:Minor Rings

- **OPTION:** 45,46

### KIT:Minor Scrolls

- **OPTION:** 47,81

### KIT:Minor Wands

- **OPTION:** 82,91

### KIT:Minor Wondrous Items

- **OPTION:** 92,100

### STARTPACK:Treasure Table Medium Magic Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Medium Armor and Shields

- **OPTION:** 1,10

### KIT:Medium Weapons

- **OPTION:** 11,20

### KIT:Medium Potions

- **OPTION:** 21,30

### KIT:Medium Rings

- **OPTION:** 31,40

### KIT:Medium Rods

- **OPTION:** 41,50

### KIT:Medium Scrolls

- **OPTION:** 51,65

### KIT:Medium Staffs

- **OPTION:** 66,68

### KIT:Medium Wands

- **OPTION:** 69,83

### KIT:Medium Wondrous Items

- **OPTION:** 84,100

### STARTPACK:Treasure Table Major Magic Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Major Armor and Shields

- **OPTION:** 1,10

### KIT:Major Weapons

- **OPTION:** 11,20

### KIT:Major Potions

- **OPTION:** 21,25

### KIT:Major Rings

- **OPTION:** 26,35

### KIT:Major Rods

- **OPTION:** 36,45

### KIT:Major Scrolls

- **OPTION:** 46,55

### KIT:Major Staffs

- **OPTION:** 56,75

### KIT:Major Wands

- **OPTION:** 76,80

### KIT:Major Wondrous Items

- **OPTION:** 81,100

### STARTPACK:Treasure Table Mundane Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Alchemical Items

- **OPTION:** 1,17

### KIT:Treasure Table Mundane Armor

- **OPTION:** 18,50

### KIT:Treasure Table Mundane Weapon

- **OPTION:** 51,83

### KIT:Treasure Table Tools and Gear

- **OPTION:** 84,100

### STARTPACK:Treasure Table Alchemical Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Alchemist's Fire (Flask)

- **QTY:** roll("1d4")
- **OPTION:** 1,12

### GEAR:Acid (Flask)

- **QTY:** roll("2d4")
- **OPTION:** 13,24

### GEAR:Smokestick

- **QTY:** roll("1d4")
- **OPTION:** 25,36

### GEAR:Holy Water (Flask)

- **QTY:** roll("1d4")
- **OPTION:** 37,48

### GEAR:Antitoxin (Vial)

- **QTY:** roll("1d4")
- **OPTION:** 49,62

### GEAR:Everburning Torch

- **OPTION:** 63,74

### GEAR:Tanglefoot Bag

- **QTY:** roll("1d4")
- **OPTION:** 75,88

### GEAR:Thunderstone

- **QTY:** roll("1d4")
- **OPTION:** 89,100

### STARTPACK:Treasure Table Mundane Armor

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Treasure Table Mundane Armor (Small)

- **OPTION:** 1,10

### KIT:Treasure Table Mundane Armor (Medium)

- **OPTION:** 11,100

### STARTPACK:Treasure Table Mundane Armor (Small)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Darkwood Shield (Small)

- **OPTION:** 81,90

### KIT:Masterwork Shield (Small)

- **OPTION:** 91,100

### STARTPACK:Darkwood Shield (Small)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Masterwork Shield (Small)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Mundane Armor (Medium)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Darkwood Shield (Medium)

- **OPTION:** 81,90

### KIT:Masterwork Shield (Medium)

- **OPTION:** 91,100

### STARTPACK:Darkwood Shield (Medium)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Masterwork Shield (Medium)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Treasure Table Mundane Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Masterwork Common Melee Weapon

- **OPTION:** 1,50

### KIT:Masterwork Uncommon Weapon

- **OPTION:** 51,70

### KIT:Masterwork Common Ranged Weapon

- **OPTION:** 71,100

### STARTPACK:Treasure Table Tools and Gear

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Backpack

- **OPTION:** 1,3

### GEAR:Crowbar

- **OPTION:** 4,6

### GEAR:Lantern (Bullseye)

- **OPTION:** 7,11

### GEAR:Lock (Simple)

- **OPTION:** 12,16

### GEAR:Lock (Average)

- **OPTION:** 17,21

### GEAR:Lock (Good)

- **OPTION:** 22,28

### GEAR:Lock (Superior)

- **OPTION:** 29,35

### GEAR:Manacles (Masterwork/Medium)

- **OPTION:** 36,40

### GEAR:Mirror (Small/Steel)

- **OPTION:** 41,43

### GEAR:Rope (Silk/50 Ft.)

- **OPTION:** 44,46

### GEAR:Spyglass

- **OPTION:** 47,53

### KIT:Artisan's Tools (Masterwork)

- **OPTION:** 54,58

### GEAR:Climber's Kit

- **OPTION:** 59,63

### GEAR:Disguise Kit

- **OPTION:** 64,68

### GEAR:Healer's Kit

- **OPTION:** 69,73

### GEAR:Holy Symbol (Silver)

- **OPTION:** 74,77

### GEAR:Hourglass

- **OPTION:** 78,81

### GEAR:Magnifying Glass

- **OPTION:** 82,88

### KIT:Musical Instrument (Masterwork)

- **OPTION:** 89,95

### GEAR:Thieves' Tools

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 96,100

### STARTPACK:Artisan's Tools (Masterwork)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Artisan's Tools (Armorsmithing)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 1

### GEAR:Artisan's Tools (Bowmaking)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 2

### GEAR:Artisan's Tools (Blacksmithing)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 3

### GEAR:Artisan's Tools (Carpentry)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 4

### GEAR:Artisan's Tools (Leatherworking)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 5

### GEAR:Artisan's Tools (Painting)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 6

### GEAR:Artisan's Tools (Pottery)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 7

### GEAR:Artisan's Tools (Sculpting)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 8

### GEAR:Artisan's Tools (Shipmaking)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 9

### GEAR:Artisan's Tools (Stonemasonry)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 10

### GEAR:Artisan's Tools (Trapmaking)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 11

### GEAR:Artisan's Tools (Weaponsmithing)

- **EQMOD:** Masterwork (Tools)
- **OPTION:** 12

### STARTPACK:Musical Instrument (Masterwork)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Musical Instrument (Bells)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 1

### GEAR:Musical Instrument (Chime)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 2

### GEAR:Musical Instrument (Drum)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 3

### GEAR:Musical Instrument (Gong)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 4

### GEAR:Musical Instrument (Fiddle)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 5

### GEAR:Musical Instrument (Harp)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 6

### GEAR:Musical Instrument (Lute)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 7

### GEAR:Musical Instrument (Mandolin)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 8

### GEAR:Musical Instrument (Flute)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 9

### GEAR:Musical Instrument (Pan Pipes)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 10

### GEAR:Musical Instrument (Recorder)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 11

### GEAR:Musical Instrument (Shawm)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 12

### GEAR:Musical Instrument (Trumpet)

- **EQMOD:** Masterwork (Instrument)
- **OPTION:** 13

### STARTPACK:Masterwork Common Melee Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Kama

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 25,28

### GEAR:Mace (Light)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 42,45

### GEAR:Nunchaku

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 51,54

### GEAR:Quarterstaff

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 55,57

### GEAR:Siangham

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 71,74

### GEAR:Waraxe (Dwarven)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 90,100

### STARTPACK:Masterwork Uncommon Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Axe (Orc Double)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 1,3

### GEAR:Dagger (Punching)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 20,21

### GEAR:Flail (Dire)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 24,26

### GEAR:Flail (Heavy)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 27,31

### GEAR:Flail

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 32,35

### GEAR:Gauntlet

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 36,37

### GEAR:Gauntlet (Spiked)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 38,39

### GEAR:Guisarme

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 44,45

### GEAR:Halberd

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 46,48

### GEAR:Hammer (Gnome Hooked)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 52,54

### GEAR:Hammer (Light)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 55,56

### GEAR:Handaxe

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 57,58

### GEAR:Kukri

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 59,61

### GEAR:Lance

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 62,64

### GEAR:Net

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 71,72

### GEAR:Pick (Light)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 75,76

### GEAR:Ranseur

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 77,78

### GEAR:Sap

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 79,80

### GEAR:Scythe

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 81,82

### GEAR:Shuriken

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 83,84

### GEAR:Sickle

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 85,86

### GEAR:Sword (Two-Bladed)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 87,89

### GEAR:Urgrosh (Dwarven)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 92,94

### STARTPACK:Masterwork Common Ranged Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Masterwork Ammunition

- **OPTION:** 1,10

### GEAR:Dart

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 36,39

### GEAR:Shortbow (Composite)

- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 47,51

### STARTPACK:Masterwork Ammunition

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Bolt (Crossbow)

- **QTY:** 50
- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 51,80

### GEAR:Bullet (Sling)

- **QTY:** 50
- **EQMOD:** Masterwork (Weapon)
- **OPTION:** 81,100

### STARTPACK:Minor Potions

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Cure Light Wounds)

- **OPTION:** 1,10

### GEAR:Potion (Endure Elements)

- **OPTION:** 11,13

### GEAR:Potion (Hide from Animals)

- **OPTION:** 14,15

### GEAR:Potion (Hide from Undead)

- **OPTION:** 16,17

### GEAR:Potion (Jump)

- **OPTION:** 18,19

### GEAR:Potion (Mage Armor)

- **OPTION:** 20,22

### GEAR:Potion (Magic Fang)

- **OPTION:** 23,25

### GEAR:Potion (Oil of Magic Stone)

- **OPTION:** 26

### GEAR:Potion (Oil of Magic Weapon)

- **OPTION:** 27,29

### GEAR:Potion (Pass without Trace)

- **OPTION:** 30

### KIT:Potion (Protection from Alignment)

- **OPTION:** 31,32

### GEAR:Potion (Remove Fear)

- **OPTION:** 33,34

### GEAR:Potion (Sanctuary)

- **OPTION:** 35

### GEAR:Potion (Shield of Faith +2)

- **OPTION:** 36,38

### GEAR:Potion (Oil of Shillelagh)

- **OPTION:** 39

### GEAR:Potion (Oil of Bless Weapon)

- **OPTION:** 40,41

### GEAR:Potion (Enlarge Person)

- **OPTION:** 42,44

### GEAR:Potion (Reduce Person)

- **OPTION:** 45

### GEAR:Potion (Aid)

- **OPTION:** 46,47

### GEAR:Potion (Barkskin +2)

- **OPTION:** 48,50

### GEAR:Potion (Bear's Endurance)

- **OPTION:** 51,53

### GEAR:Potion (Blur)

- **OPTION:** 54,56

### GEAR:Potion (Bull's Strength)

- **OPTION:** 57,59

### GEAR:Potion (Oil of Darkness)

- **OPTION:** 68

### GEAR:Potion (Darkness)

- **OPTION:** 69,71

### GEAR:Potion (Delay Poison)

- **OPTION:** 72,74

### GEAR:Potion (Eagle's Splendor)

- **OPTION:** 75,76

### GEAR:Potion (Fox's Cunning)

- **OPTION:** 77,78

### KIT:Potion or Oil of Invisibility

- **OPTION:** 79,81

### GEAR:Potion (Lesser Restoration)

- **OPTION:** 82,84

### KIT:Potion or Oil of Levitate

- **OPTION:** 85,86

### GEAR:Potion (Misdirection)

- **OPTION:** 87

### GEAR:Potion (Owl's Wisdom)

- **OPTION:** 88,89

### GEAR:Potion (Protection from Arrows 10/magic)

- **OPTION:** 90,91

### GEAR:Potion (Remove Paralysis)

- **OPTION:** 92,93

### KIT:Potion Resist Energy 10

- **OPTION:** 94,96

### GEAR:Potion (Shield of Faith +3)

- **OPTION:** 97

### GEAR:Potion (Spider Climb)

- **OPTION:** 98,99

### GEAR:Potion (Undetectable Alignment)

- **OPTION:** 100

### STARTPACK:Medium Potions

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Barkskin +3)

- **OPTION:** 51

### GEAR:Potion (Shield of Faith +4)

- **OPTION:** 52

### KIT:Potion (Resist Energy 20)

- **OPTION:** 53,55

### GEAR:Potion (Cure Serious Wounds)

- **OPTION:** 56,60

### GEAR:Potion (Oil of Daylight)

- **OPTION:** 61

### GEAR:Potion (Displacement)

- **OPTION:** 62,64

### GEAR:Potion (Oil of Flame Arrow)

- **OPTION:** 65

### GEAR:Potion (Fly)

- **OPTION:** 66,68

### GEAR:Potion (Gaseous Form)

- **OPTION:** 69

### GEAR:Potion (Greater Magic Fang +1)

- **OPTION:** 70,71

### GEAR:Potion (Oil of Greater Magic Weapon +1)

- **OPTION:** 72,73

### GEAR:Potion (Haste)

- **OPTION:** 74,75

### GEAR:Potion (Heroism)

- **OPTION:** 76,78

### GEAR:Potion (Oil of Keen Edge)

- **OPTION:** 79,80

### KIT:Potion (Magic Circle against Alignment)

- **OPTION:** 81

### GEAR:Potion (Oil of Magic Vestment +1)

- **OPTION:** 82,83

### GEAR:Potion (Neutralize Poison)

- **OPTION:** 84,86

### GEAR:Potion (Nondetection)

- **OPTION:** 87,88

### KIT:Potion (Protection from Energy)

- **OPTION:** 89,91

### GEAR:Potion (Rage)

- **OPTION:** 92,93

### GEAR:Potion (Remove Blindness/Deafness)

- **OPTION:** 94

### GEAR:Potion (Remove Curse)

- **OPTION:** 95

### GEAR:Potion (Remove Disease)

- **OPTION:** 96

### GEAR:Potion (Tongues)

- **OPTION:** 97

### GEAR:Potion (Water Breathing)

- **OPTION:** 98,99

### GEAR:Potion (Water Walk)

- **OPTION:** 100

### STARTPACK:Major Potions

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Barkskin +4)

- **OPTION:** 62,63

### GEAR:Potion (Shield of Faith +5)

- **OPTION:** 64

### GEAR:Potion (Good Hope)

- **OPTION:** 65

### KIT:Potion (Resist Energy 30)

- **OPTION:** 66,68

### GEAR:Potion (Barkskin +5)

- **OPTION:** 69

### GEAR:Potion (Greater Magic Fang +2)

- **OPTION:** 70,73

### GEAR:Potion (Oil of Greater Magic Weapon +2)

- **OPTION:** 74,77

### GEAR:Potion (Oil of Magic Vestment +2)

- **OPTION:** 78,81

### GEAR:Potion (Protection from Arrows 15/Magic)

- **OPTION:** 82

### GEAR:Potion (Greater Magic Fang +3)

- **OPTION:** 83,85

### GEAR:Potion (Oil of Greater Magic Weapon +3)

- **OPTION:** 86,88

### GEAR:Potion (Oil of Magic Vestment +3)

- **OPTION:** 89,91

### GEAR:Potion (Greater Magic Fang +4)

- **OPTION:** 92,93

### GEAR:Potion (Oil of Greater Magic Weapon +4)

- **OPTION:** 94,95

### GEAR:Potion (Oil of Magic Vestment +4)

- **OPTION:** 96,97

### GEAR:Potion (Greater Magic Fang +5)

- **OPTION:** 98

### GEAR:Potion (Oil of Greater Magic Weapon +5)

- **OPTION:** 99

### GEAR:Potion (Oil of Magic Vestment +5)

- **OPTION:** 100

### STARTPACK:Potion (Protection from Alignment)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Protection from Chaos)

- **OPTION:** 1

### GEAR:Potion (Protection from Evil)

- **OPTION:** 2

### GEAR:Potion (Protection from Good)

- **OPTION:** 3

### GEAR:Potion (Protection from Law)

- **OPTION:** 4

### STARTPACK:Potion or Oil of Invisibility

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Invisibility)

- **OPTION:** 1,50

### GEAR:Potion (Oil of Invisibility)

- **OPTION:** 51,100

### STARTPACK:Potion or Oil of Levitate

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Levitate)

- **OPTION:** 1,50

### GEAR:Potion (Oil of Levitate)

- **OPTION:** 51,100

### STARTPACK:Potion Resist Energy 10

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Resist Energy 10/Acid)

- **OPTION:** 1,20

### GEAR:Potion (Resist Energy 10/Cold)

- **OPTION:** 21,40

### GEAR:Potion (Resist Energy 10/Electricity)

- **OPTION:** 41,60

### GEAR:Potion (Resist Energy 10/Fire)

- **OPTION:** 61,80

### GEAR:Potion (Resist Energy 10/Sonic)

- **OPTION:** 81,100

### STARTPACK:Potion (Resist Energy 20)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Resist Energy 20/Acid)

- **OPTION:** 1,20

### GEAR:Potion (Resist Energy 20/Cold)

- **OPTION:** 21,40

### GEAR:Potion (Resist Energy 20/Electricity)

- **OPTION:** 41,60

### GEAR:Potion (Resist Energy 20/Fire)

- **OPTION:** 61,80

### GEAR:Potion (Resist Energy 20/Sonic)

- **OPTION:** 81,100

### STARTPACK:Potion (Magic Circle against Alignment)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Magic Circle against Chaos)

- **OPTION:** 1,25

### GEAR:Potion (Magic Circle against Evil)

- **OPTION:** 26,50

### GEAR:Potion (Magic Circle against Good)

- **OPTION:** 51,75

### GEAR:Potion (Magic Circle against Law)

- **OPTION:** 76,100

### STARTPACK:Potion (Protection from Energy)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Protection from Energy/Acid)

- **OPTION:** 1,20

### GEAR:Potion (Protection from Energy/Cold)

- **OPTION:** 21,40

### GEAR:Potion (Protection from Energy/Electricity)

- **OPTION:** 41,60

### GEAR:Potion (Protection from Energy/Fire)

- **OPTION:** 61,80

### GEAR:Potion (Protection from Energy/Sonic)

- **OPTION:** 81,100

### STARTPACK:Potion (Resist Energy 30)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Potion (Resist Energy 30/Acid)

- **OPTION:** 1,20

### GEAR:Potion (Resist Energy 30/Cold)

- **OPTION:** 21,40

### GEAR:Potion (Resist Energy 30/Electricity)

- **OPTION:** 41,60

### GEAR:Potion (Resist Energy 30/Fire)

- **OPTION:** 61,80

### GEAR:Potion (Resist Energy 30/Sonic)

- **OPTION:** 81,100

### STARTPACK:Minor Rings

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Ring of Feather Falling

- **OPTION:** 19,28

### GEAR:Ring of Sustenance

- **OPTION:** 29,36

### GEAR:Ring of Climbing

- **OPTION:** 37,44

### GEAR:Ring of Jumping

- **OPTION:** 45,52

### GEAR:Ring of Swimming

- **OPTION:** 53,60

### GEAR:Ring of Counterspells

- **OPTION:** 61,70

### GEAR:Ring of Mind Shielding

- **OPTION:** 71,75

### GEAR:Ring of Protection +2

- **OPTION:** 76,80

### GEAR:Ring of Force Shield

- **OPTION:** 81,85

### GEAR:Ring of the Ram

- **OPTION:** 86,90

### GEAR:Ring of Animal Friendship

- **OPTION:** 91,93

### KIT:Ring of Energy Resistance (Minor)

- **OPTION:** 94,96

### GEAR:Ring of Chameleon Power

- **OPTION:** 97,98

### GEAR:Ring of Water Walking

- **OPTION:** 99,100

### STARTPACK:Medium Rings

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Ring of Climbing (Improved)

- **OPTION:** 29,34

### GEAR:Ring of Jumping (Improved)

- **OPTION:** 35,40

### GEAR:Ring of Swimming (Improved)

- **OPTION:** 41,46

### GEAR:Ring of Protection +3

- **OPTION:** 67,71

### GEAR:Ring of Spell Storing (Minor)

- **OPTION:** 72,76

### GEAR:Ring of Invisibility

- **OPTION:** 77,81

### GEAR:Ring of Wizardry I

- **OPTION:** 82,85

### GEAR:Ring of Evasion

- **OPTION:** 86,90

### GEAR:Ring of X-Ray Vision

- **OPTION:** 91,93

### GEAR:Ring of Blinking

- **OPTION:** 94,97

### KIT:Ring of Energy Resistance (Major)

- **OPTION:** 98,100

### STARTPACK:Major Rings

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Ring of Protection +4

- **OPTION:** 40,49

### GEAR:Ring of Wizardry II

- **OPTION:** 50,55

### GEAR:Ring of Freedom of Movement

- **OPTION:** 56,60

### KIT:Ring of Energy Resistance (Greater)

- **OPTION:** 61,63

### GEAR:Ring of Friend Shield

- **OPTION:** 64,65

### GEAR:Ring of Protection +5

- **OPTION:** 66,70

### GEAR:Ring of Shooting Stars

- **OPTION:** 71,74

### GEAR:Ring of Spell Storing

- **OPTION:** 75,79

### GEAR:Ring of Wizardry III

- **OPTION:** 80,83

### GEAR:Ring of Telekinesis

- **OPTION:** 84,86

### GEAR:Ring of Regeneration

- **OPTION:** 87,88

### GEAR:Ring of Three Wishes

- **OPTION:** 89

### GEAR:Ring of Spell Turning

- **OPTION:** 90,92

### GEAR:Ring of Wizardry IV

- **OPTION:** 93,94

### GEAR:Ring of Djinni Calling

- **OPTION:** 95

### GEAR:Ring of Elemental Command (Air)

- **OPTION:** 96

### GEAR:Ring of Elemental Command (Earth)

- **OPTION:** 97

### GEAR:Ring of Elemental Command (Fire)

- **OPTION:** 98

### GEAR:Ring of Elemental Command (Water)

- **OPTION:** 99

### GEAR:Ring of Spell Storing (Major)

- **OPTION:** 100

### STARTPACK:Ring of Energy Resistance (Minor)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Ring of Energy Resistance (Minor/Acid)

- **OPTION:** 1,20

### GEAR:Ring of Energy Resistance (Minor/Cold)

- **OPTION:** 21,40

### GEAR:Ring of Energy Resistance (Minor/Electricity)

- **OPTION:** 41,60

### GEAR:Ring of Energy Resistance (Minor/Sonic)

- **OPTION:** 81,100

### STARTPACK:Ring of Energy Resistance (Major)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Ring of Energy Resistance (Major/Acid)

- **OPTION:** 1,20

### GEAR:Ring of Energy Resistance (Major/Cold)

- **OPTION:** 21,40

### GEAR:Ring of Energy Resistance (Major/Electricity)

- **OPTION:** 41,60

### GEAR:Ring of Energy Resistance (Major/Fire)

- **OPTION:** 61,80

### GEAR:Ring of Energy Resistance (Major/Sonic)

- **OPTION:** 81,100

### STARTPACK:Ring of Energy Resistance (Greater)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Ring of Energy Resistance (Greater/Acid)

- **OPTION:** 1,20

### GEAR:Ring of Energy Resistance (Greater/Cold)

- **OPTION:** 21,40

### GEAR:Ring of Energy Resistance (Greater/Electricity)

- **OPTION:** 41,60

### GEAR:Ring of Energy Resistance (Greater/Fire)

- **OPTION:** 61,80

### GEAR:Ring of Energy Resistance (Greater/Sonic)

- **OPTION:** 81,100

### STARTPACK:Medium Rods

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Rod (Enlarge/Lesser)

- **OPTION:** 1,7

### GEAR:Rod (Extend/Lesser)

- **OPTION:** 8,14

### GEAR:Rod (Silent/Lesser)

- **OPTION:** 15,21

### GEAR:Rod (Immovable)

- **OPTION:** 22,28

### GEAR:Rod (Empower/Lesser)

- **OPTION:** 29,35

### GEAR:Rod (Metal and Mineral Detection)

- **OPTION:** 36,42

### GEAR:Rod (Cancellation)

- **OPTION:** 43,53

### GEAR:Rod (Enlarge)

- **OPTION:** 54,57

### GEAR:Rod (Extend)

- **OPTION:** 58,61

### GEAR:Rod (Silent)

- **OPTION:** 62,65

### GEAR:Rod (Wonder)

- **OPTION:** 66,71

### GEAR:Rod (Python)

- **OPTION:** 72,79

### GEAR:Rod (Maximize/Lesser)

- **OPTION:** 80,83

### GEAR:Rod (Flame Extinguishing)

- **OPTION:** 84,89

### GEAR:Rod (Viper)

- **OPTION:** 90,97

### GEAR:Rod (Empower)

- **OPTION:** 98,99

### GEAR:Rod (Quicken/Lesser)

- **OPTION:** 100

### STARTPACK:Major Rods

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Rod (Enemy Detection)

- **OPTION:** 26,30

### GEAR:Rod (Enlarge/Greater)

- **OPTION:** 31,36

### GEAR:Rod (Extend/Greater)

- **OPTION:** 37,42

### GEAR:Rod (Silent/Greater)

- **OPTION:** 43,48

### GEAR:Rod (Splendor)

- **OPTION:** 49,53

### GEAR:Rod (Withering)

- **OPTION:** 54,58

### GEAR:Rod (Thunder and Lightning)

- **OPTION:** 65,69

### GEAR:Rod (Negation)

- **OPTION:** 74,77

### GEAR:Rod (Absorption)

- **OPTION:** 78,80

### GEAR:Rod (Flailing)

- **OPTION:** 81,84

### GEAR:Rod (Maximize)

- **OPTION:** 85,86

### GEAR:Rod (Rulership)

- **OPTION:** 87,88

### GEAR:Rod (Security)

- **OPTION:** 89,90

### GEAR:Rod (Lordly Might)

- **OPTION:** 91,92

### GEAR:Rod (Empower/Greater)

- **OPTION:** 93,94

### GEAR:Rod (Quicken)

- **OPTION:** 95,96

### GEAR:Rod (Alertness)

- **OPTION:** 97,98

### GEAR:Rod (Maximize/Greater)

- **OPTION:** 99

### GEAR:Rod (Quicken/Greater)

- **OPTION:** 100

### STARTPACK:Minor Scrolls

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Minor Arcane Scroll

- **OPTION:** 1,70

### KIT:Minor Divine Scroll

- **OPTION:** 71,100

### STARTPACK:Minor Arcane Scroll

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Minor Arcane Scroll Spell

- **OPTION:** 1

### STARTPACK:Minor Arcane Scroll Spell

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Arcane Scroll Level 0

- **OPTION:** 1

### KIT:Arcane Scroll Level 1

- **OPTION:** 6

### KIT:Arcane Scroll Level 2

- **OPTION:** 51

### KIT:Arcane Scroll Level 3

- **OPTION:** 96

### STARTPACK:Minor Divine Scroll

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Minor Divine Scroll Spell

- **OPTION:** 1

### STARTPACK:Minor Divine Scroll Spell

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Divine Scroll Level 0

- **OPTION:** 1

### KIT:Divine Scroll Level 1

- **OPTION:** 6

### KIT:Divine Scroll Level 2

- **OPTION:** 51

### KIT:Divine Scroll Level 3

- **OPTION:** 96

### STARTPACK:Medium Scrolls

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Medium Arcane Scroll

- **OPTION:** 1,70

### KIT:Medium Divine Scroll

- **OPTION:** 71,100

### STARTPACK:Medium Arcane Scroll

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Medium Arcane Scroll Spell

- **OPTION:** 1

### STARTPACK:Medium Arcane Scroll Spell

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Arcane Scroll Level 4

- **OPTION:** 66

### KIT:Arcane Scroll Level 5

- **OPTION:** 96

### STARTPACK:Medium Divine Scroll

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Medium Divine Scroll Spell

- **OPTION:** 1

### STARTPACK:Medium Divine Scroll Spell

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Divine Scroll Level 4

- **OPTION:** 66

### KIT:Divine Scroll Level 5

- **OPTION:** 96

### STARTPACK:Major Scrolls

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Major Arcane Scroll

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Major Arcane Scroll Spell

- **OPTION:** 1

### STARTPACK:Major Arcane Scroll Spell

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Arcane Scroll Level 6

- **OPTION:** 51

### KIT:Arcane Scroll Level 7

- **OPTION:** 71

### KIT:Arcane Scroll Level 8

- **OPTION:** 86

### KIT:Arcane Scroll Level 9

- **OPTION:** 96

### STARTPACK:Major Divine Scroll

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Major Divine Scroll Spell

- **OPTION:** 1

### STARTPACK:Major Divine Scroll Spell

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:Divine Scroll Level 6

- **OPTION:** 51

### KIT:Divine Scroll Level 7

- **OPTION:** 71

### KIT:Divine Scroll Level 8

- **OPTION:** 86

### KIT:Divine Scroll Level 9

- **OPTION:** 96

### STARTPACK:Arcane Scroll Level 0

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Acid Splash)

- **OPTION:** 1,4

### GEAR:Scroll (Arcane Mark)

- **OPTION:** 5,8

### GEAR:Scroll (Dancing Lights)

- **OPTION:** 9,13

### GEAR:Scroll (Daze)

- **OPTION:** 14,17

### GEAR:Scroll (Detect Magic/Arcane)

- **OPTION:** 18,24

### GEAR:Scroll (Detect Poison/Arcane)

- **OPTION:** 25,28

### GEAR:Scroll (Disrupt Undead)

- **OPTION:** 29,32

### GEAR:Scroll (Flare/Arcane)

- **OPTION:** 33,37

### GEAR:Scroll (Ghost Sound)

- **OPTION:** 38,42

### GEAR:Scroll (Know Direction/Arcane)

- **OPTION:** 43,44

### GEAR:Scroll (Light/Arcane)

- **OPTION:** 45,50

### GEAR:Scroll (Lullaby)

- **OPTION:** 51,52

### GEAR:Scroll (Mage Hand)

- **OPTION:** 53,57

### GEAR:Scroll (Mending/Arcane)

- **OPTION:** 58,62

### GEAR:Scroll (Message)

- **OPTION:** 63,67

### GEAR:Scroll (Open/Close)

- **OPTION:** 68,72

### GEAR:Scroll (Prestidigitation)

- **OPTION:** 73,77

### GEAR:Scroll (Ray of Frost)

- **OPTION:** 78,81

### GEAR:Scroll (Read Magic/Arcane)

- **OPTION:** 82,87

### GEAR:Scroll (Resistance/Arcane)

- **OPTION:** 88,94

### GEAR:Scroll (Summon Instrument)

- **OPTION:** 95,96

### GEAR:Scroll (Touch of Fatigue)

- **OPTION:** 97,100

### STARTPACK:Arcane Scroll Level 1

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Alarm/Arcane)

- **OPTION:** 1,3

### GEAR:Scroll (Animate Rope)

- **OPTION:** 4,5

### GEAR:Scroll (Burning Hands)

- **OPTION:** 6,7

### GEAR:Scroll (Cause Fear/Arcane)

- **OPTION:** 8,9

### GEAR:Scroll (Charm Person)

- **OPTION:** 10,12

### GEAR:Scroll (Chill Touch)

- **OPTION:** 13,14

### GEAR:Scroll (Color Spray)

- **OPTION:** 15,16

### GEAR:Scroll (Comprehend Languages/Arcane)

- **OPTION:** 17,19

### GEAR:Scroll (Confusion/Lesser)

- **OPTION:** 20

### GEAR:Scroll (Cure Light Wounds/Arcane)

- **OPTION:** 21

### GEAR:Scroll (Detect Secret Doors)

- **OPTION:** 22,24

### GEAR:Scroll (Detect Undead/Arcane)

- **OPTION:** 25,26

### GEAR:Scroll (Disguise Self/Lvl 1)

- **OPTION:** 27,29

### GEAR:Scroll (Endure Elements/Arcane)

- **OPTION:** 30,32

### GEAR:Scroll (Enlarge Person)

- **OPTION:** 33,35

### GEAR:Scroll (Erase)

- **OPTION:** 36,37

### GEAR:Scroll (Expeditious Retreat)

- **OPTION:** 38,40

### GEAR:Scroll (Feather Fall)

- **OPTION:** 41

### GEAR:Scroll (Grease)

- **OPTION:** 42,43

### GEAR:Scroll (Hold Portal)

- **OPTION:** 44,45

### GEAR:Scroll (Hypnotism)

- **OPTION:** 46,47

### GEAR:Scroll (Identify)

- **OPTION:** 48,49

### GEAR:Scroll (Jump/Arcane)

- **OPTION:** 50,51

### GEAR:Scroll (Mage Armor)

- **OPTION:** 52,54

### GEAR:Scroll (Magic Missile)

- **OPTION:** 55,56

### GEAR:Scroll (Magic Weapon/Arcane)

- **OPTION:** 57,59

### GEAR:Scroll (Mount)

- **OPTION:** 60,62

### GEAR:Scroll (Magic Aura)

- **OPTION:** 63,64

### GEAR:Scroll (Obscuring Mist/Arcane)

- **OPTION:** 65,66

### GEAR:Scroll (Protection from Chaos/Arcane)

- **OPTION:** 67,68

### GEAR:Scroll (Protection from Evil/Arcane)

- **OPTION:** 69,70

### GEAR:Scroll (Protection from Good/Arcane)

- **OPTION:** 71,72

### GEAR:Scroll (Protection from Law/Arcane)

- **OPTION:** 73,74

### GEAR:Scroll (Ray of Enfeeblement)

- **OPTION:** 75,76

### GEAR:Scroll (Reduce Person)

- **OPTION:** 77,78

### GEAR:Scroll (Remove Fear/Arcane)

- **OPTION:** 79,80

### GEAR:Scroll (Shield)

- **OPTION:** 81,82

### GEAR:Scroll (Shocking Grasp)

- **OPTION:** 83,84

### GEAR:Scroll (Silent Image)

- **OPTION:** 85,86

### GEAR:Scroll (Sleep)

- **OPTION:** 87,88

### GEAR:Scroll (Summon Monster I/Arcane)

- **OPTION:** 89,90

### GEAR:Scroll (Floating Disk)

- **OPTION:** 91,93

### GEAR:Scroll (True Strike)

- **OPTION:** 94,95

### GEAR:Scroll (Undetectable Alignment/Arcane)

- **OPTION:** 96

### GEAR:Scroll (Unseen Servant)

- **OPTION:** 97,98

### GEAR:Scroll (Ventriloquism)

- **OPTION:** 99,100

### STARTPACK:Arcane Scroll Level 2

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animal Messenger/Arcane)

- **OPTION:** 1

### GEAR:Scroll (Animal Trance/Arcane)

- **OPTION:** 2

### GEAR:Scroll (Arcane Lock)

- **OPTION:** 3

### GEAR:Scroll (Bear's Endurance/Arcane)

- **OPTION:** 4,6

### GEAR:Scroll (Blindness/Deafness/Arcane)

- **OPTION:** 7,8

### GEAR:Scroll (Blur)

- **OPTION:** 9,10

### GEAR:Scroll (Bull's Strength/Arcane)

- **OPTION:** 11,13

### GEAR:Scroll (Calm Emotions/Arcane)

- **OPTION:** 14

### GEAR:Scroll (Cat's Grace/Arcane)

- **OPTION:** 15,17

### GEAR:Scroll (Command Undead)

- **OPTION:** 18,19

### GEAR:Scroll (Continual Flame/Arcane)

- **OPTION:** 20

### GEAR:Scroll (Cure Moderate Wounds/Arcane)

- **OPTION:** 21

### GEAR:Scroll (Darkness/Arcane)

- **OPTION:** 22

### GEAR:Scroll (Darkvision/Arcane)

- **OPTION:** 23,25

### GEAR:Scroll (Daze Monster)

- **OPTION:** 26

### GEAR:Scroll (Delay Poison/Arcane)

- **OPTION:** 27

### GEAR:Scroll (Detect Thoughts)

- **OPTION:** 28,29

### GEAR:Scroll (Disguise Self/Lvl 2)

- **OPTION:** 30,31

### GEAR:Scroll (Eagle's Splendor/Arcane)

- **OPTION:** 32,34

### GEAR:Scroll (Enthrall/Arcane)

- **OPTION:** 35

### GEAR:Scroll (False Life)

- **OPTION:** 36,37

### GEAR:Scroll (Flaming Sphere/Arcane)

- **OPTION:** 38,39

### GEAR:Scroll (Fog Cloud/Arcane)

- **OPTION:** 40

### GEAR:Scroll (Fox's Cunning)

- **OPTION:** 41,43

### GEAR:Scroll (Ghoul Touch)

- **OPTION:** 44

### GEAR:Scroll (Glitterdust)

- **OPTION:** 45,46

### GEAR:Scroll (Gust of Wind/Arcane)

- **OPTION:** 47

### GEAR:Scroll (Hypnotic Pattern)

- **OPTION:** 48,49

### GEAR:Scroll (Invisibility)

- **OPTION:** 50,52

### GEAR:Scroll (Knock)

- **OPTION:** 53,55

### GEAR:Scroll (Phantom Trap)

- **OPTION:** 56

### GEAR:Scroll (Levitate)

- **OPTION:** 57,58

### GEAR:Scroll (Locate Object/Arcane)

- **OPTION:** 59

### GEAR:Scroll (Magic Mouth)

- **OPTION:** 60

### GEAR:Scroll (Acid Arrow)

- **OPTION:** 61,62

### GEAR:Scroll (Minor Image)

- **OPTION:** 63

### GEAR:Scroll (Mirror Image)

- **OPTION:** 64,65

### GEAR:Scroll (Misdirection)

- **OPTION:** 66

### GEAR:Scroll (Obscure Object/Arcane)

- **OPTION:** 67

### GEAR:Scroll (Owl's Wisdom/Arcane)

- **OPTION:** 68,70

### GEAR:Scroll (Protection from Arrows)

- **OPTION:** 71,73

### GEAR:Scroll (Pyrotechnics)

- **OPTION:** 74,75

### GEAR:Scroll (Resist Energy/Arcane)

- **OPTION:** 76,78

### GEAR:Scroll (Rope Trick)

- **OPTION:** 79

### GEAR:Scroll (Scare)

- **OPTION:** 80

### GEAR:Scroll (Scorching Ray)

- **OPTION:** 81,82

### GEAR:Scroll (See Invisibility)

- **OPTION:** 83,85

### GEAR:Scroll (Shatter/Arcane)

- **OPTION:** 86

### GEAR:Scroll (Silence/Arcane)

- **OPTION:** 87

### GEAR:Scroll (Sound Burst/Arcane)

- **OPTION:** 88

### GEAR:Scroll (Spectral Hand)

- **OPTION:** 89

### GEAR:Scroll (Spider Climb/Arcane)

- **OPTION:** 90,91

### GEAR:Scroll (Summon Monster II/Arcane)

- **OPTION:** 92,93

### GEAR:Scroll (Summon Swarm/Arcane)

- **OPTION:** 94,95

### GEAR:Scroll (Hideous Laughter)

- **OPTION:** 96

### GEAR:Scroll (Touch of Idiocy)

- **OPTION:** 97

### GEAR:Scroll (Web)

- **OPTION:** 98,99

### GEAR:Scroll (Whispering Wind)

- **OPTION:** 100

### STARTPACK:Arcane Scroll Level 3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Arcane Sight)

- **OPTION:** 1,2

### GEAR:Scroll (Blink)

- **OPTION:** 3,4

### GEAR:Scroll (Clairaudience/Clairvoyance)

- **OPTION:** 5,6

### GEAR:Scroll (Cure Serious Wounds/Arcane)

- **OPTION:** 7

### GEAR:Scroll (Daylight/Arcane)

- **OPTION:** 8,10

### GEAR:Scroll (Deep Slumber)

- **OPTION:** 11,12

### GEAR:Scroll (Dispel Magic/Arcane)

- **OPTION:** 13,15

### GEAR:Scroll (Displacement)

- **OPTION:** 16,17

### GEAR:Scroll (Explosive Runes)

- **OPTION:** 18

### GEAR:Scroll (Fireball)

- **OPTION:** 19,20

### GEAR:Scroll (Flame Arrow)

- **OPTION:** 21,22

### GEAR:Scroll (Fly)

- **OPTION:** 23,25

### GEAR:Scroll (Gaseous Form)

- **OPTION:** 26,27

### GEAR:Scroll (Gentle Repose/Arcane)

- **OPTION:** 28,29

### GEAR:Scroll (Glibness)

- **OPTION:** 30

### GEAR:Scroll (Good Hope)

- **OPTION:** 31

### GEAR:Scroll (Halt Undead)

- **OPTION:** 32,33

### GEAR:Scroll (Haste)

- **OPTION:** 34,36

### GEAR:Scroll (Heroism)

- **OPTION:** 37,38

### GEAR:Scroll (Hold Person/Arcane)

- **OPTION:** 39,40

### GEAR:Scroll (Illusory Script)

- **OPTION:** 41

### GEAR:Scroll (Invisibility Sphere)

- **OPTION:** 42,44

### GEAR:Scroll (Keen Edge)

- **OPTION:** 45,47

### GEAR:Scroll (Tiny Hut)

- **OPTION:** 48,49

### GEAR:Scroll (Lightning Bolt)

- **OPTION:** 50,51

### GEAR:Scroll (Magic Circle against Chaos/Arcane)

- **OPTION:** 52,53

### GEAR:Scroll (Magic Circle against Evil/Arcane)

- **OPTION:** 54,55

### GEAR:Scroll (Magic Circle against Good/Arcane)

- **OPTION:** 56,57

### GEAR:Scroll (Magic Circle against Law/Arcane)

- **OPTION:** 58,59

### GEAR:Scroll (Magic Weapon/Greater/Arcane)

- **OPTION:** 60,62

### GEAR:Scroll (Major Image)

- **OPTION:** 63,64

### GEAR:Scroll (Nondetection/Arcane)

- **OPTION:** 65,66

### GEAR:Scroll (Phantom Steed)

- **OPTION:** 67,68

### GEAR:Scroll (Protection from Energy)

- **OPTION:** 69,71

### GEAR:Scroll (Rage)

- **OPTION:** 72,73

### GEAR:Scroll (Ray of Exhaustion)

- **OPTION:** 74,75

### GEAR:Scroll (Sculpt Sound)

- **OPTION:** 76

### GEAR:Scroll (Secret Page)

- **OPTION:** 77

### GEAR:Scroll (Sepia Snake Sigil)

- **OPTION:** 78

### GEAR:Scroll (Shrink Item)

- **OPTION:** 79

### GEAR:Scroll (Sleet Storm/Arcane)

- **OPTION:** 80,81

### GEAR:Scroll (Slow)

- **OPTION:** 82,83

### GEAR:Scroll (Speak with Animals/Arcane)

- **OPTION:** 84

### GEAR:Scroll (Stinking Cloud)

- **OPTION:** 85,86

### GEAR:Scroll (Suggestion)

- **OPTION:** 87,88

### GEAR:Scroll (Summon Monster III/Arcane)

- **OPTION:** 89,90

### GEAR:Scroll (Tongues)

- **OPTION:** 91,93

### GEAR:Scroll (Vampiric Touch)

- **OPTION:** 94,95

### GEAR:Scroll (Water Breathing/Arcane)

- **OPTION:** 96,98

### GEAR:Scroll (Wind Wall/Arcane)

- **OPTION:** 99,100

### STARTPACK:Arcane Scroll Level 4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animate Dead/Arcane)

- **OPTION:** 1,2

### GEAR:Scroll (Arcane Eye)

- **OPTION:** 3,5

### GEAR:Scroll (Bestow Curse/Arcane)

- **OPTION:** 6,7

### GEAR:Scroll (Charm Monster)

- **OPTION:** 8,10

### GEAR:Scroll (Confusion)

- **OPTION:** 11,13

### GEAR:Scroll (Contagion/Arcane)

- **OPTION:** 14,15

### GEAR:Scroll (Crushing Despair)

- **OPTION:** 16,17

### GEAR:Scroll (Cure Critical Wounds/Arcane)

- **OPTION:** 18

### GEAR:Scroll (Detect Scrying)

- **OPTION:** 19

### GEAR:Scroll (Dimension Door)

- **OPTION:** 20,23

### GEAR:Scroll (Dimensional Anchor/Arcane)

- **OPTION:** 24,26

### GEAR:Scroll (Enervation)

- **OPTION:** 27,28

### GEAR:Scroll (Enlarge Person/Mass)

- **OPTION:** 29,30

### GEAR:Scroll (Black Tentacles)

- **OPTION:** 31,32

### GEAR:Scroll (Fear)

- **OPTION:** 33,34

### GEAR:Scroll (Fire Shield)

- **OPTION:** 35,37

### GEAR:Scroll (Fire Trap/Arcane)

- **OPTION:** 38,39

### GEAR:Scroll (Freedom of Movement/Arcane)

- **OPTION:** 40,42

### GEAR:Scroll (Geas/Lesser)

- **OPTION:** 43

### GEAR:Scroll (Globe of Invulnerability/Lesser)

- **OPTION:** 44,46

### GEAR:Scroll (Hallucinatory Terrain)

- **OPTION:** 47,48

### GEAR:Scroll (Ice Storm/Arcane)

- **OPTION:** 49,50

### GEAR:Scroll (Illusory Wall)

- **OPTION:** 51,52

### GEAR:Scroll (Invisibility/Greater)

- **OPTION:** 53,55

### GEAR:Scroll (Secure Shelter)

- **OPTION:** 56,57

### GEAR:Scroll (Locate Creature)

- **OPTION:** 58

### GEAR:Scroll (Minor Creation)

- **OPTION:** 59,60

### GEAR:Scroll (Modify Memory)

- **OPTION:** 61

### GEAR:Scroll (Neutralize Poison/Arcane)

- **OPTION:** 62

### GEAR:Scroll (Resilient Sphere)

- **OPTION:** 63,64

### GEAR:Scroll (Phantasmal Killer)

- **OPTION:** 65,66

### GEAR:Scroll (Polymorph)

- **OPTION:** 67,68

### GEAR:Scroll (Rainbow Pattern)

- **OPTION:** 69,70

### GEAR:Scroll (Mnemonic Enhancer)

- **OPTION:** 71

### GEAR:Scroll (Reduce Person/Mass)

- **OPTION:** 72,73

### GEAR:Scroll (Remove Curse/Arcane)

- **OPTION:** 74,76

### GEAR:Scroll (Repel Vermin/Arcane)

- **OPTION:** 77

### GEAR:Scroll (Scrying/Arcane)

- **OPTION:** 78,79

### GEAR:Scroll (Shadow Conjuration)

- **OPTION:** 80,81

### GEAR:Scroll (Shout)

- **OPTION:** 82,83

### GEAR:Scroll (Solid Fog)

- **OPTION:** 84,85

### GEAR:Scroll (Speak with Plants/Arcane)

- **OPTION:** 86

### GEAR:Scroll (Stone Shape)

- **OPTION:** 87,88

### GEAR:Scroll (Stoneskin/Arcane)

- **OPTION:** 89,91

### GEAR:Scroll (Summon Monster IV/Arcane)

- **OPTION:** 92,93

### GEAR:Scroll (Wall of Fire/Arcane)

- **OPTION:** 94,96

### GEAR:Scroll (Wall of Ice)

- **OPTION:** 97,99

### GEAR:Scroll (Zone of Silence)

- **OPTION:** 100

### STARTPACK:Arcane Scroll Level 5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animal Growth/Arcane)

- **OPTION:** 1,2

### GEAR:Scroll (Baleful Polymorph/Arcane)

- **OPTION:** 3,5

### GEAR:Scroll (Interposing Hand)

- **OPTION:** 6,7

### GEAR:Scroll (Blight/Arcane)

- **OPTION:** 8,9

### GEAR:Scroll (Break Enchantment/Arcane)

- **OPTION:** 10,12

### GEAR:Scroll (Cloudkill)

- **OPTION:** 13,14

### GEAR:Scroll (Cone of Cold)

- **OPTION:** 15,17

### GEAR:Scroll (Contact Other Plane)

- **OPTION:** 18,19

### GEAR:Scroll (Cure Light Wounds/Mass/Arcane)

- **OPTION:** 20

### GEAR:Scroll (Dismissal/Arcane)

- **OPTION:** 21,23

### GEAR:Scroll (Dispel Magic/Greater/Arcane/Lvl 5)

- **OPTION:** 24,26

### GEAR:Scroll (Dominate Person)

- **OPTION:** 27,28

### GEAR:Scroll (Dream)

- **OPTION:** 29

### GEAR:Scroll (Fabricate)

- **OPTION:** 30,31

### GEAR:Scroll (False Vision)

- **OPTION:** 32,33

### GEAR:Scroll (Feeblemind)

- **OPTION:** 34,35

### GEAR:Scroll (Hold Monster)

- **OPTION:** 36,39

### GEAR:Scroll (Secret Chest)

- **OPTION:** 40

### GEAR:Scroll (Magic Jar)

- **OPTION:** 41

### GEAR:Scroll (Major Creation)

- **OPTION:** 42,43

### GEAR:Scroll (Mind Fog)

- **OPTION:** 44,45

### GEAR:Scroll (Mirage Arcana)

- **OPTION:** 46,47

### GEAR:Scroll (Mage's Faithful Hound)

- **OPTION:** 48,49

### GEAR:Scroll (Mage's Private Sanctum)

- **OPTION:** 50,51

### GEAR:Scroll (Nightmare)

- **OPTION:** 52,53

### GEAR:Scroll (Overland Flight)

- **OPTION:** 54,57

### GEAR:Scroll (Passwall)

- **OPTION:** 58,60

### GEAR:Scroll (Permanency)

- **OPTION:** 61

### GEAR:Scroll (Persistent Image)

- **OPTION:** 62,63

### GEAR:Scroll (Planar Binding/Lesser)

- **OPTION:** 64,65

### GEAR:Scroll (Prying Eyes)

- **OPTION:** 66,67

### GEAR:Scroll (Telepathic Bond)

- **OPTION:** 68,69

### GEAR:Scroll (Seeming)

- **OPTION:** 70,71

### GEAR:Scroll (Sending/Arcane)

- **OPTION:** 72,74

### GEAR:Scroll (Shadow Evocation)

- **OPTION:** 75,76

### GEAR:Scroll (Song of Discord)

- **OPTION:** 77

### GEAR:Scroll (Summon Monster V/Arcane)

- **OPTION:** 78,79

### GEAR:Scroll (Symbol of Pain/Arcane)

- **OPTION:** 80

### GEAR:Scroll (Symbol of Sleep/Arcane)

- **OPTION:** 81

### GEAR:Scroll (Telekinesis)

- **OPTION:** 82,83

### GEAR:Scroll (Teleport)

- **OPTION:** 84,88

### GEAR:Scroll (Transmute Mud to Rock/Arcane)

- **OPTION:** 89,90

### GEAR:Scroll (Transmute Rock to Mud/Arcane)

- **OPTION:** 91,92

### GEAR:Scroll (Wall of Force)

- **OPTION:** 93,95

### GEAR:Scroll (Wall of Stone)

- **OPTION:** 96,98

### GEAR:Scroll (Waves of Fatigue)

- **OPTION:** 99,100

### STARTPACK:Arcane Scroll Level 6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Acid Fog)

- **OPTION:** 1,2

### GEAR:Scroll (Analayze Dweomer)

- **OPTION:** 3,5

### GEAR:Scroll (Animate Objects/Arcane)

- **OPTION:** 6

### GEAR:Scroll (Antimagic Field/Arcane)

- **OPTION:** 7,9

### GEAR:Scroll (Bear's Endurance/Mass/Arcane)

- **OPTION:** 10,12

### GEAR:Scroll (Forceful Hand)

- **OPTION:** 13,14

### GEAR:Scroll (Bull's Strength/Mass/Arcane)

- **OPTION:** 15,17

### GEAR:Scroll (Cat's Grace/Mass/Arcane)

- **OPTION:** 18,20

### GEAR:Scroll (Chain Lightning)

- **OPTION:** 21,23

### GEAR:Scroll (Circle of Death)

- **OPTION:** 24,25

### GEAR:Scroll (Contingency)

- **OPTION:** 26

### GEAR:Scroll (Control Water/Arcane)

- **OPTION:** 27,28

### GEAR:Scroll (Create Undead/Arcane)

- **OPTION:** 29

### GEAR:Scroll (Cure Moderate Wounds/Mass/Arcane)

- **OPTION:** 30

### GEAR:Scroll (Disintegrate)

- **OPTION:** 31,33

### GEAR:Scroll (Dispel Magic/Greater/Arcane/Lvl 6)

- **OPTION:** 34,37

### GEAR:Scroll (Eagle's Splendor/Mass/Arcane)

- **OPTION:** 38,40

### GEAR:Scroll (Eyebite)

- **OPTION:** 41,42

### GEAR:Scroll (Find the Path/Arcane)

- **OPTION:** 43

### GEAR:Scroll (Flesh to Stone)

- **OPTION:** 44,45

### GEAR:Scroll (Fox's Cunning/Mass)

- **OPTION:** 46,48

### GEAR:Scroll (Geas/Quest/Arcane)

- **OPTION:** 49

### GEAR:Scroll (Globe of Invulnerability)

- **OPTION:** 50,52

### GEAR:Scroll (Guards and Wards)

- **OPTION:** 53

### GEAR:Scroll (Heroes' Feast/Arcane)

- **OPTION:** 54

### GEAR:Scroll (Heroism/Greater)

- **OPTION:** 55,56

### GEAR:Scroll (Legend Lore)

- **OPTION:** 57

### GEAR:Scroll (Mislead)

- **OPTION:** 58,59

### GEAR:Scroll (Mage's Lucubration)

- **OPTION:** 60

### GEAR:Scroll (Move Earth/Arcane)

- **OPTION:** 61,62

### GEAR:Scroll (Freezing Sphere)

- **OPTION:** 63,64

### GEAR:Scroll (Owl's Wisdom/Mass/Arcane)

- **OPTION:** 65,67

### GEAR:Scroll (Permanent Image)

- **OPTION:** 68,69

### GEAR:Scroll (Planar Binding)

- **OPTION:** 70,71

### GEAR:Scroll (Programmed Image)

- **OPTION:** 72,73

### GEAR:Scroll (Repulsion/Arcane)

- **OPTION:** 74,75

### GEAR:Scroll (Shadow Walk)

- **OPTION:** 76,78

### GEAR:Scroll (Stone to Flesh)

- **OPTION:** 79,81

### GEAR:Scroll (Suggestion/Mass)

- **OPTION:** 82,83

### GEAR:Scroll (Summon Monster VI/Arcane)

- **OPTION:** 84,85

### GEAR:Scroll (Symbol of Fear/Arcane)

- **OPTION:** 86

### GEAR:Scroll (Symbol of Persuasion/Arcane)

- **OPTION:** 87

### GEAR:Scroll (Sympathetic Vibration)

- **OPTION:** 88

### GEAR:Scroll (Transformation)

- **OPTION:** 89,90

### GEAR:Scroll (True Seeing/Arcane)

- **OPTION:** 91,93

### GEAR:Scroll (Undeath to Death/Arcane)

- **OPTION:** 94,95

### GEAR:Scroll (Veil)

- **OPTION:** 96,97

### GEAR:Scroll (Wall of Iron)

- **OPTION:** 98,100

### STARTPACK:Arcane Scroll Level 7

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Arcane Sight/Greater)

- **OPTION:** 1,3

### GEAR:Scroll (Banishement/Arcane)

- **OPTION:** 4,7

### GEAR:Scroll (Grasping Hand)

- **OPTION:** 8,10

### GEAR:Scroll (Control Undead)

- **OPTION:** 11,13

### GEAR:Scroll (Control Weather/Arcane/Lvl 7)

- **OPTION:** 14,16

### GEAR:Scroll (Delayed Blast Fireball)

- **OPTION:** 17,19

### GEAR:Scroll (Instant Summons)

- **OPTION:** 20,21

### GEAR:Scroll (Ethereal Jaunt/Arcane)

- **OPTION:** 22,25

### GEAR:Scroll (Finger of Death/Arcane)

- **OPTION:** 26,28

### GEAR:Scroll (Forcecage)

- **OPTION:** 29,31

### GEAR:Scroll (Hold Person/Mass)

- **OPTION:** 32,35

### GEAR:Scroll (Insanity)

- **OPTION:** 36,38

### GEAR:Scroll (Invisibility/Mass)

- **OPTION:** 39,42

### GEAR:Scroll (Limited Wish)

- **OPTION:** 43

### GEAR:Scroll (Mage's Magnificent Mansion)

- **OPTION:** 44,45

### GEAR:Scroll (Mage's Sword)

- **OPTION:** 46,48

### GEAR:Scroll (Phase Door)

- **OPTION:** 49,51

### GEAR:Scroll (Plane Shift/Arcane)

- **OPTION:** 52,54

### GEAR:Scroll (Power Word Blind)

- **OPTION:** 55,57

### GEAR:Scroll (Prismatic Spray)

- **OPTION:** 58,61

### GEAR:Scroll (Project Image)

- **OPTION:** 62,64

### GEAR:Scroll (Reverse Gravity/Arcane)

- **OPTION:** 65,67

### GEAR:Scroll (Scrying/Greater/Arcane)

- **OPTION:** 68,70

### GEAR:Scroll (Sequester)

- **OPTION:** 71,73

### GEAR:Scroll (Shadow Conjuration/Greater)

- **OPTION:** 74,76

### GEAR:Scroll (Simulacrum)

- **OPTION:** 77

### GEAR:Scroll (Spell Turning)

- **OPTION:** 78,80

### GEAR:Scroll (Statue)

- **OPTION:** 81,82

### GEAR:Scroll (Summon Monster VII/Arcane)

- **OPTION:** 83,85

### GEAR:Scroll (Symbol of Stunning/Arcane)

- **OPTION:** 86

### GEAR:Scroll (Symbol of Weakness/Arcane)

- **OPTION:** 87

### GEAR:Scroll (Teleport Object)

- **OPTION:** 88,90

### GEAR:Scroll (Teleport/Greater)

- **OPTION:** 91,95

### GEAR:Scroll (Vision)

- **OPTION:** 96,97

### GEAR:Scroll (Waves of Exhaustion)

- **OPTION:** 98,100

### STARTPACK:Arcane Scroll Level 8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Antipathy/Arcane)

- **OPTION:** 1,2

### GEAR:Scroll (Clenched Fist)

- **OPTION:** 3,5

### GEAR:Scroll (Binding)

- **OPTION:** 6,8

### GEAR:Scroll (Charm Monster/Mass)

- **OPTION:** 9,12

### GEAR:Scroll (Clone)

- **OPTION:** 13

### GEAR:Scroll (Create Greater Undead/Arcane)

- **OPTION:** 14,16

### GEAR:Scroll (Demand)

- **OPTION:** 17,19

### GEAR:Scroll (Dimensional Lock/Arcane)

- **OPTION:** 20,22

### GEAR:Scroll (Discern Location/Arcane)

- **OPTION:** 23,26

### GEAR:Scroll (Horrid Wilting)

- **OPTION:** 27,29

### GEAR:Scroll (Incendiary Cloud)

- **OPTION:** 30,32

### GEAR:Scroll (Iron Body)

- **OPTION:** 33,35

### GEAR:Scroll (Maze)

- **OPTION:** 36,38

### GEAR:Scroll (Mind Blank)

- **OPTION:** 39,41

### GEAR:Scroll (Moment of Prescience)

- **OPTION:** 42,44

### GEAR:Scroll (Telekinetic Sphere)

- **OPTION:** 45,48

### GEAR:Scroll (Irresistible Dance)

- **OPTION:** 49,51

### GEAR:Scroll (Planar Binding/Greater)

- **OPTION:** 52,54

### GEAR:Scroll (Polar Ray)

- **OPTION:** 55,57

### GEAR:Scroll (Polymorph Any Object)

- **OPTION:** 58,60

### GEAR:Scroll (Power Word Stun)

- **OPTION:** 61,63

### GEAR:Scroll (Prismatic Wall)

- **OPTION:** 64,66

### GEAR:Scroll (Protection from Spells)

- **OPTION:** 67,70

### GEAR:Scroll (Prying Eyes/Greater)

- **OPTION:** 71,73

### GEAR:Scroll (Scintillating Pattern)

- **OPTION:** 74,76

### GEAR:Scroll (Screen)

- **OPTION:** 77,78

### GEAR:Scroll (Shadow Evocation/Greater)

- **OPTION:** 79,81

### GEAR:Scroll (Shout/Greater)

- **OPTION:** 82,84

### GEAR:Scroll (Summon Monster VIII/Arcane)

- **OPTION:** 85,87

### GEAR:Scroll (Sunburst/Arcane)

- **OPTION:** 88,90

### GEAR:Scroll (Symbol of Death/Arcane)

- **OPTION:** 91

### GEAR:Scroll (Symbol of Insanity/Arcane)

- **OPTION:** 92

### GEAR:Scroll (Sympathy/Arcane)

- **OPTION:** 93,94

### GEAR:Scroll (Temporal Stasis)

- **OPTION:** 95,98

### GEAR:Scroll (Trap the Soul)

- **OPTION:** 99,100

### STARTPACK:Arcane Scroll Level 9

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Astral Projection/Arcane)

- **OPTION:** 1,3

### GEAR:Scroll (Crushing Hand)

- **OPTION:** 4,7

### GEAR:Scroll (Dominate Monster)

- **OPTION:** 8,12

### GEAR:Scroll (Energy Drain/Arcane)

- **OPTION:** 13,16

### GEAR:Scroll (Etherealness/Arcane)

- **OPTION:** 17,21

### GEAR:Scroll (Foresight/Arcane)

- **OPTION:** 22,25

### GEAR:Scroll (Freedom)

- **OPTION:** 26,31

### GEAR:Scroll (Gate)

- **OPTION:** 32,36

### GEAR:Scroll (Hold Monster/Mass)

- **OPTION:** 37,40

### GEAR:Scroll (Imprisonment)

- **OPTION:** 41,44

### GEAR:Scroll (Meteor Swarm)

- **OPTION:** 45,49

### GEAR:Scroll (Mage's Disjunction)

- **OPTION:** 50,53

### GEAR:Scroll (Power Word Kill)

- **OPTION:** 54,58

### GEAR:Scroll (Prismatic Sphere)

- **OPTION:** 59,62

### GEAR:Scroll (Refuge/Arcane)

- **OPTION:** 63,66

### GEAR:Scroll (Shades)

- **OPTION:** 67,70

### GEAR:Scroll (Shapechange/Arcane)

- **OPTION:** 71,76

### GEAR:Scroll (Soul Bind/Arcane)

- **OPTION:** 77,79

### GEAR:Scroll (Summon Monster IX)

- **OPTION:** 80,83

### GEAR:Scroll (Teleportation Circle)

- **OPTION:** 84,86

### GEAR:Scroll (Time Stop)

- **OPTION:** 87,91

### GEAR:Scroll (Wail of the Banshee)

- **OPTION:** 92,95

### GEAR:Scroll (Weird)

- **OPTION:** 96,99

### GEAR:Scroll (Wish)

- **OPTION:** 100

### STARTPACK:Divine Scroll Level 0

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Create Water)

- **OPTION:** 1,7

### GEAR:Scroll (Cure Minor Wounds)

- **OPTION:** 8,14

### GEAR:Scroll (Detect Magic/Divine)

- **OPTION:** 15,22

### GEAR:Scroll (Detect Poison/Divine)

- **OPTION:** 23,29

### GEAR:Scroll (Flare/Divine)

- **OPTION:** 30,36

### GEAR:Scroll (Guidance)

- **OPTION:** 37,43

### GEAR:Scroll (Inflict Minor Wounds)

- **OPTION:** 44,50

### GEAR:Scroll (Know Direction/Divine)

- **OPTION:** 51,57

### GEAR:Scroll (Light/Divine)

- **OPTION:** 58,65

### GEAR:Scroll (Mending/Divine)

- **OPTION:** 66,72

### GEAR:Scroll (Purify Food and Drink)

- **OPTION:** 73,79

### GEAR:Scroll (Read Magic/Divine)

- **OPTION:** 80,86

### GEAR:Scroll (Resistance/Divine)

- **OPTION:** 87,93

### GEAR:Scroll (Virtue)

- **OPTION:** 94,100

### STARTPACK:Divine Scroll Level 1

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Alarm/Divine)

- **OPTION:** 1

### GEAR:Scroll (Bane)

- **OPTION:** 2,3

### GEAR:Scroll (Bless)

- **OPTION:** 4,6

### GEAR:Scroll (Bless Water)

- **OPTION:** 7,9

### GEAR:Scroll (Bless Weapon)

- **OPTION:** 10

### GEAR:Scroll (Calm Animals)

- **OPTION:** 11,12

### GEAR:Scroll (Cause Fear/Divine)

- **OPTION:** 13,14

### GEAR:Scroll (Charm Animal)

- **OPTION:** 15,16

### GEAR:Scroll (Command)

- **OPTION:** 17,19

### GEAR:Scroll (Comprehend Languages/Divine)

- **OPTION:** 20,21

### GEAR:Scroll (Cure Light Wounds/Divine)

- **OPTION:** 22,26

### GEAR:Scroll (Curse Water)

- **OPTION:** 27,28

### GEAR:Scroll (Deathwatch)

- **OPTION:** 29,30

### GEAR:Scroll (Detect Animals or Plants)

- **OPTION:** 31,32

### KIT:Scroll (Detect Alignment)

- **OPTION:** 33,35

### GEAR:Scroll (Detect Snares and Pits)

- **OPTION:** 36,37

### GEAR:Scroll (Detect Undead/Divine)

- **OPTION:** 38,39

### GEAR:Scroll (Divine Favor)

- **OPTION:** 40,41

### GEAR:Scroll (Doom)

- **OPTION:** 42,43

### GEAR:Scroll (Endure Elements/Divine)

- **OPTION:** 44,48

### GEAR:Scroll (Entangle)

- **OPTION:** 49,50

### GEAR:Scroll (Entropic Shield)

- **OPTION:** 51,52

### GEAR:Scroll (Faerie Fire)

- **OPTION:** 53,54

### GEAR:Scroll (Goodberry)

- **OPTION:** 55,56

### GEAR:Scroll (Hide from Animals)

- **OPTION:** 57,58

### GEAR:Scroll (Hide from Undead)

- **OPTION:** 59,60

### GEAR:Scroll (Inflict Light Wounds)

- **OPTION:** 61,62

### GEAR:Scroll (Jump/Divine)

- **OPTION:** 63,64

### GEAR:Scroll (Longstrider)

- **OPTION:** 65,66

### GEAR:Scroll (Magic Fang)

- **OPTION:** 67,68

### GEAR:Scroll (Magic Stone)

- **OPTION:** 69,72

### GEAR:Scroll (Magic Weapon/Divine)

- **OPTION:** 73,74

### GEAR:Scroll (Obscuring Mist/Divine)

- **OPTION:** 75,78

### GEAR:Scroll (Pass Without Trace)

- **OPTION:** 79,80

### GEAR:Scroll (Produce Flame)

- **OPTION:** 81,82

### GEAR:Scroll (Protection from Chaos/Divine)

- **OPTION:** 83

### GEAR:Scroll (Protection from Evil/Divine)

- **OPTION:** 84

### GEAR:Scroll (Protection from Good/Divine)

- **OPTION:** 85

### GEAR:Scroll (Protection from Law/Divine)

- **OPTION:** 86

### GEAR:Scroll (Remove Fear/Divine)

- **OPTION:** 87,88

### GEAR:Scroll (Sanctuary)

- **OPTION:** 89,90

### GEAR:Scroll (Shield of Faith)

- **OPTION:** 91,92

### GEAR:Scroll (Shillelagh)

- **OPTION:** 93,94

### GEAR:Scroll (Speak with Animals/Divine)

- **OPTION:** 95,96

### GEAR:Scroll (Summon Monster I/Divine)

- **OPTION:** 97,98

### GEAR:Scroll (Summon Nature's Ally I)

- **OPTION:** 99,100

### STARTPACK:Scroll (Detect Alignment)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Detect Chaos)

- **OPTION:** 1

### GEAR:Scroll (Detect Evil)

- **OPTION:** 2

### GEAR:Scroll (Detect Good)

- **OPTION:** 3

### GEAR:Scroll (Detect Law)

- **OPTION:** 4

### STARTPACK:Divine Scroll Level 2

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animal Messenger/Divine)

- **OPTION:** 1

### GEAR:Scroll (Animal Trance/Divine)

- **OPTION:** 2

### GEAR:Scroll (Augury)

- **OPTION:** 3,4

### GEAR:Scroll (Barkskin)

- **OPTION:** 5,6

### GEAR:Scroll (Bear's Endurance/Divine)

- **OPTION:** 7,9

### GEAR:Scroll (Bull's Strength/Divine)

- **OPTION:** 10,12

### GEAR:Scroll (Calm Emotions/Divine)

- **OPTION:** 13,14

### GEAR:Scroll (Cat's Grace/Divine)

- **OPTION:** 15,17

### GEAR:Scroll (Chill Metal)

- **OPTION:** 18

### GEAR:Scroll (Consecrate)

- **OPTION:** 19,20

### GEAR:Scroll (Cure Moderate Wounds/Divine)

- **OPTION:** 21,24

### GEAR:Scroll (Darkness/Divine)

- **OPTION:** 25,26

### GEAR:Scroll (Death Knell)

- **OPTION:** 27

### GEAR:Scroll (Delay Poison/Divine)

- **OPTION:** 28,30

### GEAR:Scroll (Desecrate)

- **OPTION:** 31,32

### GEAR:Scroll (Eagle's Splendor/Divine)

- **OPTION:** 33,35

### GEAR:Scroll (Enthrall/Divine)

- **OPTION:** 36,37

### GEAR:Scroll (Find Traps)

- **OPTION:** 38,39

### GEAR:Scroll (Fire Trap/Divine)

- **OPTION:** 40

### GEAR:Scroll (Flame Blade)

- **OPTION:** 41,42

### GEAR:Scroll (Flaming Sphere/Divine)

- **OPTION:** 43,44

### GEAR:Scroll (Fog Cloud/Divine)

- **OPTION:** 45,46

### GEAR:Scroll (Gentle Repose/Divine)

- **OPTION:** 47

### GEAR:Scroll (Gust of Wind/Divine)

- **OPTION:** 48

### GEAR:Scroll (Heat Metal)

- **OPTION:** 49

### GEAR:Scroll (Hold Animal)

- **OPTION:** 50,51

### GEAR:Scroll (Hold Person/Divine)

- **OPTION:** 52,54

### GEAR:Scroll (Inflict Moderate Wounds)

- **OPTION:** 55,56

### GEAR:Scroll (Make Whole)

- **OPTION:** 57,58

### GEAR:Scroll (Owl's Wisdom/Divine)

- **OPTION:** 59,61

### GEAR:Scroll (Reduce Animal)

- **OPTION:** 62

### GEAR:Scroll (Remove Paralysis)

- **OPTION:** 63,64

### GEAR:Scroll (Resist Energy/Divine)

- **OPTION:** 65,67

### GEAR:Scroll (Restoration/Lesser)

- **OPTION:** 68,70

### GEAR:Scroll (Shatter/Divine)

- **OPTION:** 71,72

### GEAR:Scroll (Shield Other)

- **OPTION:** 73,74

### GEAR:Scroll (Silence/Divine)

- **OPTION:** 75,76

### GEAR:Scroll (Snare/Lvl 2)

- **OPTION:** 77

### GEAR:Scroll (Soften Earth and Stone)

- **OPTION:** 78

### GEAR:Scroll (Sound Burst/Divine)

- **OPTION:** 79,80

### GEAR:Scroll (Speak with Plants/Divine/Lvl 2)

- **OPTION:** 81

### GEAR:Scroll (Spider Climb/Divine)

- **OPTION:** 82,83

### GEAR:Scroll (Spiritual Weapon)

- **OPTION:** 84,85

### GEAR:Scroll (Status)

- **OPTION:** 86

### GEAR:Scroll (Summon Monster II/Divine)

- **OPTION:** 87,88

### GEAR:Scroll (Summon Nature's Ally II)

- **OPTION:** 89,90

### GEAR:Scroll (Summon Swarm/Divine)

- **OPTION:** 91,92

### GEAR:Scroll (Tree Shape)

- **OPTION:** 93

### GEAR:Scroll (Undetectable Alignment/Divine)

- **OPTION:** 94,95

### GEAR:Scroll (Warp Wood)

- **OPTION:** 96,97

### GEAR:Scroll (Wood Shape)

- **OPTION:** 98

### GEAR:Scroll (Zone of Truth)

- **OPTION:** 99,100

### STARTPACK:Divine Scroll Level 3

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animate Dead/Divine)

- **OPTION:** 1,2

### GEAR:Scroll (Bestow Curse/Divine)

- **OPTION:** 3,4

### GEAR:Scroll (Blindness/Deafness/Divine)

- **OPTION:** 5,6

### GEAR:Scroll (Call Lightning)

- **OPTION:** 7,8

### GEAR:Scroll (Contagion/Divine)

- **OPTION:** 9,10

### GEAR:Scroll (Continual Flame/Divine)

- **OPTION:** 11,12

### GEAR:Scroll (Create Food and Water)

- **OPTION:** 13,14

### GEAR:Scroll (Cure Serious Wounds/Divine)

- **OPTION:** 15,18

### GEAR:Scroll (Darkvision/Divine)

- **OPTION:** 19

### GEAR:Scroll (Daylight/Divine)

- **OPTION:** 20,21

### GEAR:Scroll (Deeper Darkness)

- **OPTION:** 22,23

### GEAR:Scroll (Diminish Plants)

- **OPTION:** 24,25

### GEAR:Scroll (Dispel Magic/Divine)

- **OPTION:** 26,27

### GEAR:Scroll (Dominate Animal)

- **OPTION:** 28,29

### GEAR:Scroll (Glyph of Warding)

- **OPTION:** 30,31

### GEAR:Scroll (Heal Mount)

- **OPTION:** 32

### GEAR:Scroll (Helping Hand)

- **OPTION:** 33,34

### GEAR:Scroll (Inflict Serious Wounds)

- **OPTION:** 35,36

### GEAR:Scroll (Invisibility Purge)

- **OPTION:** 37,38

### GEAR:Scroll (Locate Object/Divine)

- **OPTION:** 39,40

### KIT:Scroll (Magic Circle against Alignment)

- **OPTION:** 41,46

### GEAR:Scroll (Magic Fang/Greater)

- **OPTION:** 47,48

### GEAR:Scroll (Magic Vestment)

- **OPTION:** 49,50

### GEAR:Scroll (Meld into Stone)

- **OPTION:** 51,52

### GEAR:Scroll (Neutralize Poison/Divine)

- **OPTION:** 53,55

### GEAR:Scroll (Obscure Object/Divine)

- **OPTION:** 56,57

### GEAR:Scroll (Plant Growth)

- **OPTION:** 58,59

### GEAR:Scroll (Prayer)

- **OPTION:** 60,62

### GEAR:Scroll (Protection from Energy/Divine)

- **OPTION:** 63,64

### GEAR:Scroll (Quench)

- **OPTION:** 65,66

### GEAR:Scroll (Remove Blindness/Deafness)

- **OPTION:** 67,69

### GEAR:Scroll (Remove Curse/Divine)

- **OPTION:** 70,71

### GEAR:Scroll (Remove Disease)

- **OPTION:** 72,73

### GEAR:Scroll (Searing Light)

- **OPTION:** 74,76

### GEAR:Scroll (Sleet Storm/Divine)

- **OPTION:** 77,78

### GEAR:Scroll (Snare/Lvl 3)

- **OPTION:** 79,80

### GEAR:Scroll (Speak with Dead)

- **OPTION:** 81,83

### GEAR:Scroll (Speak with Plants/Divine/Lvl 3)

- **OPTION:** 84,85

### GEAR:Scroll (Spike Growth)

- **OPTION:** 86,87

### GEAR:Scroll (Summon Monster III/Divine)

- **OPTION:** 90,91

### GEAR:Scroll (Summon Nature's Ally III)

- **OPTION:** 92,93

### GEAR:Scroll (Water Breathing/Divine)

- **OPTION:** 94,96

### GEAR:Scroll (Water Walk)

- **OPTION:** 97,98

### GEAR:Scroll (Wind Wall/Divine)

- **OPTION:** 99,100

### STARTPACK:Scroll (Magic Circle against Alignment)

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Magic Circle against Chaos/Divine)

- **OPTION:** 1

### GEAR:Scroll (Magic Circle against Evil/Divine)

- **OPTION:** 2

### GEAR:Scroll (Magic Circle against Good/Divine)

- **OPTION:** 3

### GEAR:Scroll (Magic Circle against Law/Divine)

- **OPTION:** 4

### STARTPACK:Divine Scroll Level 4

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Air Walk)

- **OPTION:** 1,5

### GEAR:Scroll (Antiplant Shell)

- **OPTION:** 6,7

### GEAR:Scroll (Blight/Divine)

- **OPTION:** 8,9

### GEAR:Scroll (Break Enchantment/Divine/Lvl 4)

- **OPTION:** 10,11

### GEAR:Scroll (Command Plants)

- **OPTION:** 12,13

### GEAR:Scroll (Control Water)

- **OPTION:** 14,15

### GEAR:Scroll (Cure Critical Wounds/Divine)

- **OPTION:** 16,21

### GEAR:Scroll (Death Ward)

- **OPTION:** 22,26

### GEAR:Scroll (Dimensional Anchor/Divine)

- **OPTION:** 27,31

### GEAR:Scroll (Discern Lies)

- **OPTION:** 32,34

### GEAR:Scroll (Dismissal/Divine)

- **OPTION:** 35,37

### GEAR:Scroll (Divination)

- **OPTION:** 38,39

### GEAR:Scroll (Divine Power)

- **OPTION:** 40,42

### GEAR:Scroll (Freedom of Movement/Divine)

- **OPTION:** 43,47

### GEAR:Scroll (Giant Vermin)

- **OPTION:** 48,49

### GEAR:Scroll (Holy Sword)

- **OPTION:** 50,51

### GEAR:Scroll (Imbue with Spell Ability)

- **OPTION:** 52,54

### GEAR:Scroll (Inflict Critical Wounds)

- **OPTION:** 55,57

### GEAR:Scroll (Magic Weapon/Greater/Divine)

- **OPTION:** 58,60

### GEAR:Scroll (Nondetection/Divine)

- **OPTION:** 61,62

### GEAR:Scroll (Planar Ally/Lesser)

- **OPTION:** 63,64

### GEAR:Scroll (Poison)

- **OPTION:** 65,67

### GEAR:Scroll (Reincarnate)

- **OPTION:** 68,69

### GEAR:Scroll (Repel Vermin/Divine)

- **OPTION:** 70,71

### GEAR:Scroll (Restoration)

- **OPTION:** 72,76

### GEAR:Scroll (Rusting Grasp)

- **OPTION:** 77,78

### GEAR:Scroll (Sending/Divine)

- **OPTION:** 79,81

### GEAR:Scroll (Spell Immunity)

- **OPTION:** 82,85

### GEAR:Scroll (Spike Stones)

- **OPTION:** 86,87

### GEAR:Scroll (Summon Monster IV/Divine)

- **OPTION:** 88,90

### GEAR:Scroll (Summon Nature's Ally IV)

- **OPTION:** 91,93

### GEAR:Scroll (Tongues/Divine)

- **OPTION:** 94,98

### GEAR:Scroll (Tree Stride)

- **OPTION:** 99,100

### STARTPACK:Divine Scroll Level 5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animal Growth/Divine)

- **OPTION:** 1,3

### GEAR:Scroll (Atonement)

- **OPTION:** 4,5

### GEAR:Scroll (Awaken)

- **OPTION:** 6

### GEAR:Scroll (Baleful Polymorph/Divine)

- **OPTION:** 7,9

### GEAR:Scroll (Break Enchantment/Divine/Lvl 5)

- **OPTION:** 10,13

### GEAR:Scroll (Call Lightning Storm)

- **OPTION:** 14,16

### GEAR:Scroll (Command/Greater)

- **OPTION:** 17,20

### GEAR:Scroll (Commune)

- **OPTION:** 21

### GEAR:Scroll (Commune with Nature)

- **OPTION:** 22

### GEAR:Scroll (Control Winds)

- **OPTION:** 23,24

### GEAR:Scroll (Cure Light Wounds/Mass/Divine)

- **OPTION:** 25,30

### GEAR:Scroll (Dispel Chaos)

- **OPTION:** 31

### GEAR:Scroll (Dispel Evil)

- **OPTION:** 32

### GEAR:Scroll (Dispel Good)

- **OPTION:** 33

### GEAR:Scroll (Dispel Law)

- **OPTION:** 34

### GEAR:Scroll (Disrupting Weapon)

- **OPTION:** 35,38

### GEAR:Scroll (Flame Strike)

- **OPTION:** 39,41

### GEAR:Scroll (Hallow)

- **OPTION:** 42,43

### GEAR:Scroll (Ice Storm/Divine)

- **OPTION:** 44,46

### GEAR:Scroll (Inflict Light Wounds/Mass)

- **OPTION:** 47,49

### GEAR:Scroll (Insect Plague)

- **OPTION:** 50,52

### GEAR:Scroll (Mark of Justice)

- **OPTION:** 53

### GEAR:Scroll (Plane Shift/Divine)

- **OPTION:** 54,56

### GEAR:Scroll (Raise Dead)

- **OPTION:** 57,58

### GEAR:Scroll (Righteous Might)

- **OPTION:** 59,61

### GEAR:Scroll (Scrying/Divine)

- **OPTION:** 62,63

### GEAR:Scroll (Slay Living)

- **OPTION:** 64,66

### GEAR:Scroll (Spell Resistance)

- **OPTION:** 67,69

### GEAR:Scroll (Stoneskin/Divine)

- **OPTION:** 70,71

### GEAR:Scroll (Summon Monster V/Divine)

- **OPTION:** 72,74

### GEAR:Scroll (Summon Nature's Ally V)

- **OPTION:** 75,77

### GEAR:Scroll (Symbol of Pain/Divine)

- **OPTION:** 78

### GEAR:Scroll (Symbol of Sleep/Divine)

- **OPTION:** 79

### GEAR:Scroll (Transmute Mud to Rock/Divine)

- **OPTION:** 80,82

### GEAR:Scroll (Transmute Rock to Mud/Divine)

- **OPTION:** 83,85

### GEAR:Scroll (True Seeing/Divine)

- **OPTION:** 86,89

### GEAR:Scroll (Unhallow)

- **OPTION:** 90,91

### GEAR:Scroll (Wall of Fire/Divine)

- **OPTION:** 92,94

### GEAR:Scroll (Wall of Stone/Divine)

- **OPTION:** 95,97

### GEAR:Scroll (Wall of Thorns)

- **OPTION:** 98,100

### STARTPACK:Divine Scroll Level 6

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animate Objects/Divine)

- **OPTION:** 1,3

### GEAR:Scroll (Antilife Shell)

- **OPTION:** 4,6

### GEAR:Scroll (Banishment/Divine)

- **OPTION:** 7,9

### GEAR:Scroll (Bear's Endurance/Mass/Divine)

- **OPTION:** 10,13

### GEAR:Scroll (Blade Barrier)

- **OPTION:** 14,16

### GEAR:Scroll (Bull's Strength/Mass/Divine)

- **OPTION:** 17,20

### GEAR:Scroll (Cat's Grace/Mass/Divine)

- **OPTION:** 21,24

### GEAR:Scroll (Create Undead/Divine)

- **OPTION:** 25

### GEAR:Scroll (Cure Moderate Wounds/Mass/Divine)

- **OPTION:** 26,29

### GEAR:Scroll (Dispel Magic/Greater/Divine)

- **OPTION:** 30,33

### GEAR:Scroll (Eagle's Splendor/Mass/Divine)

- **OPTION:** 34,37

### GEAR:Scroll (Find the Path/Divine)

- **OPTION:** 38,40

### GEAR:Scroll (Fire Seeds)

- **OPTION:** 41,43

### GEAR:Scroll (Forbiddance)

- **OPTION:** 44

### GEAR:Scroll (Geas/Quest/Divine)

- **OPTION:** 45

### GEAR:Scroll (Glyph of Warding/Greater)

- **OPTION:** 46

### GEAR:Scroll (Harm)

- **OPTION:** 47,49

### GEAR:Scroll (Heal)

- **OPTION:** 50,52

### GEAR:Scroll (Heroes' Feast/Divine)

- **OPTION:** 53,55

### GEAR:Scroll (Inflict Moderate Wounds/Mass)

- **OPTION:** 56,58

### GEAR:Scroll (Ironwood)

- **OPTION:** 59,61

### GEAR:Scroll (Liveoak)

- **OPTION:** 62

### GEAR:Scroll (Move Earth/Divine)

- **OPTION:** 63,65

### GEAR:Scroll (Owl's Wisdom/Mass/Divine)

- **OPTION:** 66,69

### GEAR:Scroll (Planar Ally)

- **OPTION:** 70,71

### GEAR:Scroll (Repel Wood)

- **OPTION:** 72,74

### GEAR:Scroll (Spellstaff)

- **OPTION:** 75,77

### GEAR:Scroll (Stone Tell)

- **OPTION:** 78,80

### GEAR:Scroll (Summon Monster VI/Divine)

- **OPTION:** 81,83

### GEAR:Scroll (Summon Nature's Ally VI)

- **OPTION:** 84,86

### GEAR:Scroll (Symbol of Fear/Divine)

- **OPTION:** 87

### GEAR:Scroll (Symbol of Persuasion/Divine)

- **OPTION:** 88

### GEAR:Scroll (Transport via Plants)

- **OPTION:** 89,91

### GEAR:Scroll (Undeath to Death/Divine)

- **OPTION:** 92,94

### GEAR:Scroll (Wind Walk)

- **OPTION:** 95,97

### GEAR:Scroll (Word of Recall)

- **OPTION:** 98,100

### STARTPACK:Divine Scroll Level 7

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animate Plants)

- **OPTION:** 1,5

### GEAR:Scroll (Blasphemy)

- **OPTION:** 6,9

### GEAR:Scroll (Changestaff)

- **OPTION:** 10,14

### GEAR:Scroll (Control Weather/Divine)

- **OPTION:** 15,16

### GEAR:Scroll (Creeping Doom)

- **OPTION:** 17,21

### GEAR:Scroll (Cure Serious Wounds/Mass)

- **OPTION:** 22,27

### GEAR:Scroll (Destruction)

- **OPTION:** 28,32

### GEAR:Scroll (Dictum)

- **OPTION:** 33,36

### GEAR:Scroll (Ethereal Jaunt/Divine)

- **OPTION:** 37,41

### GEAR:Scroll (Holy Word)

- **OPTION:** 42,45

### GEAR:Scroll (Inflict Serious Wounds/Mass)

- **OPTION:** 46,50

### GEAR:Scroll (Refuge/Divine)

- **OPTION:** 51,55

### GEAR:Scroll (Regenerate/Lvl 7)

- **OPTION:** 56,60

### GEAR:Scroll (Repulsion/Divine)

- **OPTION:** 61,65

### GEAR:Scroll (Restoration/Greater)

- **OPTION:** 66,69

### GEAR:Scroll (Resurrection)

- **OPTION:** 70,71

### GEAR:Scroll (Scrying/Greater/Divine)

- **OPTION:** 72,76

### GEAR:Scroll (Summon Monster VII/Divine)

- **OPTION:** 77,81

### GEAR:Scroll (Summon Nature's Ally VII)

- **OPTION:** 82,85

### GEAR:Scroll (Sunbeam)

- **OPTION:** 86,90

### GEAR:Scroll (Symbol of Stunning/Divine)

- **OPTION:** 91

### GEAR:Scroll (Symbol of Weakness/Divine)

- **OPTION:** 92

### GEAR:Scroll (Transmute Metal to Wood)

- **OPTION:** 93,97

### GEAR:Scroll (Word of Chaos)

- **OPTION:** 98,100

### STARTPACK:Divine Scroll Level 8

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Animal Shapes)

- **OPTION:** 1,4

### GEAR:Scroll (Antimagic Field/Divine)

- **OPTION:** 5,10

### GEAR:Scroll (Cloak of Chaos)

- **OPTION:** 11,13

### GEAR:Scroll (Control Plants)

- **OPTION:** 14,17

### GEAR:Scroll (Create Greater Undead/Divine)

- **OPTION:** 18,20

### GEAR:Scroll (Cure Critical Wounds/Mass)

- **OPTION:** 21,27

### GEAR:Scroll (Dimensional Lock/Divine)

- **OPTION:** 28,32

### GEAR:Scroll (Discern Location/Divine)

- **OPTION:** 33,36

### GEAR:Scroll (Earthquake)

- **OPTION:** 37,41

### GEAR:Scroll (Finger of Death/Divine)

- **OPTION:** 42,45

### GEAR:Scroll (Fire Storm)

- **OPTION:** 46,49

### GEAR:Scroll (Holy Aura)

- **OPTION:** 50,52

### GEAR:Scroll (Inflict Critical Wounds/Mass)

- **OPTION:** 53,56

### GEAR:Scroll (Planar Ally/Greater)

- **OPTION:** 57,60

### GEAR:Scroll (Repel Metal or Stone)

- **OPTION:** 61,65

### GEAR:Scroll (Reverse Gravity/Divine)

- **OPTION:** 66,69

### GEAR:Scroll (Shield of Law)

- **OPTION:** 70,72

### GEAR:Scroll (Spell Immunity/Greater)

- **OPTION:** 73,76

### GEAR:Scroll (Summon Monster VIII/Divine)

- **OPTION:** 77,80

### GEAR:Scroll (Summon Nature's Ally VIII)

- **OPTION:** 81,84

### GEAR:Scroll (Sunburst/Divine)

- **OPTION:** 85,89

### GEAR:Scroll (Symbol of Death/Divine)

- **OPTION:** 90,91

### GEAR:Scroll (Symbol of Insanity/Divine)

- **OPTION:** 92,93

### GEAR:Scroll (Unholy Aura)

- **OPTION:** 94,96

### GEAR:Scroll (Whirlwind)

- **OPTION:** 97,100

### STARTPACK:Divine Scroll Level 9

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Scroll (Antipathy/Divine)

- **OPTION:** 1,4

### GEAR:Scroll (Astral Projection/Divine)

- **OPTION:** 5,7

### GEAR:Scroll (Elemental Swarm)

- **OPTION:** 8,13

### GEAR:Scroll (Energy Drain/Divine)

- **OPTION:** 14,19

### GEAR:Scroll (Etherealness/Divine)

- **OPTION:** 20,25

### GEAR:Scroll (Foresight/Divine)

- **OPTION:** 26,31

### GEAR:Scroll (Gate/Divine)

- **OPTION:** 32,37

### GEAR:Scroll (Heal/Mass)

- **OPTION:** 38,46

### GEAR:Scroll (Implosion)

- **OPTION:** 47,53

### GEAR:Scroll (Miracle)

- **OPTION:** 54,55

### GEAR:Scroll (Regenerate/Lvl 9)

- **OPTION:** 56,61

### GEAR:Scroll (Shambler)

- **OPTION:** 62,66

### GEAR:Scroll (Shapechange/Divine)

- **OPTION:** 67,72

### GEAR:Scroll (Soul Bind/Divine)

- **OPTION:** 73,77

### GEAR:Scroll (Storm of Vengeance)

- **OPTION:** 78,83

### GEAR:Scroll (Summon Monster IX/Divine)

- **OPTION:** 84,89

### GEAR:Scroll (Summon Nature's Ally IX)

- **OPTION:** 90,95

### GEAR:Scroll (Sympathy/Divine)

- **OPTION:** 96,99

### GEAR:Scroll (True Resurrection)

- **OPTION:** 100

### STARTPACK:Medium Staffs

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Staff (Charming)

- **OPTION:** 1,15

### GEAR:Staff (Fire)

- **OPTION:** 16,30

### GEAR:Staff (Swarming Insects)

- **OPTION:** 31,40

### GEAR:Staff (Healing)

- **OPTION:** 41,60

### GEAR:Staff (Size Alteration)

- **OPTION:** 61,75

### GEAR:Staff (Illumination)

- **OPTION:** 76,90

### GEAR:Staff (Frost)

- **OPTION:** 91,95

### GEAR:Staff (Defense)

- **OPTION:** 96,100

### STARTPACK:Major Staffs

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Staff (Abjuration)

- **OPTION:** 39,43

### GEAR:Staff (Conjuration)

- **OPTION:** 44,48

### GEAR:Staff (Enchantment)

- **OPTION:** 49,53

### GEAR:Staff (Evocation)

- **OPTION:** 54,58

### GEAR:Staff (Illusion)

- **OPTION:** 59,63

### GEAR:Staff (Necromancy)

- **OPTION:** 64,68

### GEAR:Staff (Transmutation)

- **OPTION:** 69,73

### GEAR:Staff (Divination)

- **OPTION:** 74,77

### GEAR:Staff (Earth and Stone)

- **OPTION:** 78,82

### GEAR:Staff (Woodlands)

- **OPTION:** 83,87

### GEAR:Staff (Life)

- **OPTION:** 88,92

### GEAR:Staff (Passage)

- **OPTION:** 93,97

### GEAR:Staff (Power)

- **OPTION:** 98,100

### STARTPACK:Minor Wands

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Wand (Detect Magic)

- **OPTION:** 1,2

### GEAR:Wand (Light)

- **OPTION:** 3,4

### GEAR:Wand (Burning Hands)

- **OPTION:** 5,7

### GEAR:Wand (Charm Animal)

- **OPTION:** 8,10

### GEAR:Wand (Charm Person)

- **OPTION:** 11,13

### GEAR:Wand (Color Spray)

- **OPTION:** 14,16

### GEAR:Wand (Cure Light Wounds)

- **OPTION:** 17,19

### GEAR:Wand (Detect Secret Doors)

- **OPTION:** 20,22

### GEAR:Wand (Enlarge Person)

- **OPTION:** 23,25

### GEAR:Wand (Magic Missile/1st level caster)

- **OPTION:** 26,28

### GEAR:Wand (Shocking Grasp)

- **OPTION:** 29,31

### GEAR:Wand (Summon Monster I)

- **OPTION:** 32,34

### GEAR:Wand (Magic Missile/3rd level caster)

- **OPTION:** 35,36

### GEAR:Wand (Magic Missile/5th level caster)

- **OPTION:** 37

### GEAR:Wand (Bear's Endurance)

- **OPTION:** 38,40

### GEAR:Wand (Bull's Strength)

- **OPTION:** 41,43

### GEAR:Wand (Cat's Grace)

- **OPTION:** 44,46

### GEAR:Wand (Cure Moderate Wounds)

- **OPTION:** 47,49

### GEAR:Wand (Darkness)

- **OPTION:** 50,51

### GEAR:Wand (Daylight)

- **OPTION:** 52,54

### GEAR:Wand (Delay Poison)

- **OPTION:** 55,57

### GEAR:Wand (Eagle's Splendor)

- **OPTION:** 58,60

### GEAR:Wand (False Life)

- **OPTION:** 61,63

### GEAR:Wand (Fox's Cunning)

- **OPTION:** 64,66

### GEAR:Wand (Ghoul Touch)

- **OPTION:** 67,68

### GEAR:Wand (Hold Person)

- **OPTION:** 69,71

### GEAR:Wand (Invisibility)

- **OPTION:** 72,74

### GEAR:Wand (Knock)

- **OPTION:** 75,77

### GEAR:Wand (Levitate)

- **OPTION:** 78,80

### GEAR:Wand (Acid Arrow)

- **OPTION:** 81,83

### GEAR:Wand (Mirror Image)

- **OPTION:** 84,86

### GEAR:Wand (Owl's Wisdom)

- **OPTION:** 87,89

### GEAR:Wand (Shatter)

- **OPTION:** 90,91

### GEAR:Wand (Silence)

- **OPTION:** 92,94

### GEAR:Wand (Summon Monster II)

- **OPTION:** 95,97

### GEAR:Wand (Web)

- **OPTION:** 98,100

### STARTPACK:Medium Wands

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Wand (Magic Missile/7th level caster)

- **OPTION:** 60,62

### GEAR:Wand (Magic Missile/9th level caster)

- **OPTION:** 63,64

### GEAR:Wand (Call Lightning/5th level caster)

- **OPTION:** 65,67

### GEAR:Wand (Charm Person/heightened to 3rd-level spell)

- **OPTION:** 68

### GEAR:Wand (Contagion)

- **OPTION:** 69,70

### GEAR:Wand (Cure Serious Wounds)

- **OPTION:** 71,74

### GEAR:Wand (Dispel Magic)

- **OPTION:** 75,77

### GEAR:Wand (Fireball/5th level caster)

- **OPTION:** 78,81

### GEAR:Wand (Keen Edge)

- **OPTION:** 82,83

### GEAR:Wand (Lightning Bolt/5th level caster)

- **OPTION:** 84,87

### GEAR:Wand (Major Image)

- **OPTION:** 88,89

### GEAR:Wand (Slow)

- **OPTION:** 90,91

### GEAR:Wand (Suggestion)

- **OPTION:** 92,94

### GEAR:Wand (Summon Monster III)

- **OPTION:** 95,97

### GEAR:Wand (Fireball/6th level caster)

- **OPTION:** 98

### GEAR:Wand (Lightning Bolt/6th level caster)

- **OPTION:** 99

### GEAR:Wand (Searing Light/6th level caster)

- **OPTION:** 100

### STARTPACK:Major Wands

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Wand (Call Lightning/8th level caster)

- **OPTION:** 36,37

### GEAR:Wand (Fireball/8th level caster)

- **OPTION:** 38,39

### GEAR:Wand (Lightning Bolt/8th level caster)

- **OPTION:** 40,41

### GEAR:Wand (Charm Monster)

- **OPTION:** 42,45

### GEAR:Wand (Cure Critical Wounds)

- **OPTION:** 46,50

### GEAR:Wand (Dimensional Anchor)

- **OPTION:** 51,52

### GEAR:Wand (Fear)

- **OPTION:** 53,55

### GEAR:Wand (Greater Invisibility)

- **OPTION:** 56,59

### GEAR:Wand (Hold Person/heightened to 4th-level spell)

- **OPTION:** 60

### GEAR:Wand (Ice Storm)

- **OPTION:** 61,65

### GEAR:Wand (Inflict Critical Wounds)

- **OPTION:** 66,68

### GEAR:Wand (Neutralize Poison)

- **OPTION:** 69,72

### GEAR:Wand (Poison)

- **OPTION:** 73,74

### GEAR:Wand (Polymorph)

- **OPTION:** 75,77

### GEAR:Wand (Ray of Enfeeblement/heightened to 4th-level spell)

- **OPTION:** 78

### GEAR:Wand (Suggestion/heightened to 4th-level spell)

- **OPTION:** 79

### GEAR:Wand (Summon Monster IV)

- **OPTION:** 80,82

### GEAR:Wand (Wall of Fire)

- **OPTION:** 83,86

### GEAR:Wand (Wall of Ice)

- **OPTION:** 87,90

### GEAR:Wand (Dispel Magic/10th level caster)

- **OPTION:** 91

### GEAR:Wand (Fireball/10th level caster)

- **OPTION:** 92

### GEAR:Wand (Lightning Bolt/10th level caster)

- **OPTION:** 93

### GEAR:Wand (Chaos Hammer/8th Level Caster)

- **OPTION:** 94

### GEAR:Wand (Holy Smite/8th level caster)

- **OPTION:** 95

### GEAR:Wand (Order's Wrath/8th level caster)

- **OPTION:** 96

### GEAR:Wand (Unholy Blight/8th level caster)

- **OPTION:** 97

### GEAR:Wand (Restoration)

- **OPTION:** 98,99

### GEAR:Wand (Stoneskin)

- **OPTION:** 100

### STARTPACK:Minor Weapons

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Weapon

- **OPTION:** 1,70

### KIT:+2 Weapon

- **OPTION:** 71,85

### KIT:Minor Specific Weapon

- **OPTION:** 86,90

### KIT:Minor Weapons Special Ability

- **OPTION:** 91,100

### STARTPACK:Medium Weapons

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Weapon

- **OPTION:** 30,58

### KIT:+4 Weapon

- **OPTION:** 59,62

### KIT:Medium Specific Weapon

- **OPTION:** 63,68

### KIT:Medium Weapons Special Ability

- **OPTION:** 69,100

### STARTPACK:Major Weapons

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+5 Weapon

- **OPTION:** 39,49

### KIT:Major Specific Weapon

- **OPTION:** 50,63

### KIT:Major Weapons Special Ability

- **OPTION:** 64,100

### STARTPACK:+1 Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Common Melee Weapon

- **OPTION:** 1,50

### KIT:+1 Uncommon Weapon

- **OPTION:** 51,70

### KIT:+1 Common Ranged Weapon

- **OPTION:** 71,100

### STARTPACK:+1 Common Melee Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+1 Uncommon Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+1 Common Ranged Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Ammunition

- **OPTION:** 1,10

### STARTPACK:+1 Ammunition

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+2 Common Melee Weapon

- **OPTION:** 1,50

### KIT:+2 Uncommon Weapon

- **OPTION:** 51,70

### KIT:+2 Common Ranged Weapon

- **OPTION:** 71,100

### STARTPACK:+2 Common Melee Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Uncommon Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Common Ranged Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+2 Ammunition

- **OPTION:** 1,10

### STARTPACK:+2 Ammunition

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Common Melee Weapon

- **OPTION:** 1,50

### KIT:+3 Uncommon Weapon

- **OPTION:** 51,70

### KIT:+3 Common Ranged Weapon

- **OPTION:** 71,100

### STARTPACK:+3 Common Melee Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Uncommon Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Common Ranged Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Ammunition

- **OPTION:** 1,10

### STARTPACK:+3 Ammunition

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+4 Common Melee Weapon

- **OPTION:** 1,50

### KIT:+4 Uncommon Weapon

- **OPTION:** 51,70

### KIT:+4 Common Ranged Weapon

- **OPTION:** 71,100

### STARTPACK:+4 Common Melee Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Uncommon Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Common Ranged Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+4 Ammunition

- **OPTION:** 1,10

### STARTPACK:+4 Ammunition

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+5 Common Melee Weapon

- **OPTION:** 1,50

### KIT:+5 Uncommon Weapon

- **OPTION:** 51,70

### KIT:+5 Common Ranged Weapon

- **OPTION:** 71,100

### STARTPACK:+5 Common Melee Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Uncommon Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Common Ranged Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+5 Ammunition

- **OPTION:** 1,10

### STARTPACK:+5 Ammunition

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Minor Specific Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Sleep Arrow

- **OPTION:** 1,15

### GEAR:Screaming Bolt

- **OPTION:** 16,25

### GEAR:Javelin of Lightning

- **OPTION:** 66,75

### GEAR:Slaying Arrow

- **OPTION:** 76,80

### STARTPACK:Medium Specific Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Slaying Arrow (Greater)

- **OPTION:** 34,37

### GEAR:Shatterspike

- **OPTION:** 38,40

### GEAR:Dagger of Venom

- **OPTION:** 41,46

### GEAR:Trident of Warning

- **OPTION:** 47,51

### GEAR:Assassin's Dagger

- **OPTION:** 52,57

### GEAR:Shifter's Sorrow

- **OPTION:** 58,62

### GEAR:Trident of Fish Command

- **OPTION:** 63,66

### GEAR:Flame Tongue

- **OPTION:** 67,74

### GEAR:Luck Blade (0 wishes)

- **OPTION:** 75,79

### GEAR:Sword of Subtlety

- **OPTION:** 80,86

### GEAR:Sword of the Planes

- **OPTION:** 87,91

### GEAR:Nine Lives Stealer

- **OPTION:** 92,95

### GEAR:Sword of Life Stealing

- **OPTION:** 96,98

### GEAR:Oathbow

- **OPTION:** 99,100

### STARTPACK:Major Specific Weapon

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Mace of Terror

- **OPTION:** 47,51

### GEAR:Life Drinker

- **OPTION:** 52,57

### GEAR:Sylvan Scimitar

- **OPTION:** 58,62

### GEAR:Rapier of Puncturing

- **OPTION:** 63,67

### GEAR:Sunblade (Short)

- **OPTION:** 68,73

### GEAR:Frost Brand

- **OPTION:** 74,79

### GEAR:Dwarven Thrower

- **OPTION:** 80,84

### GEAR:Luck Blade (1 wish)

- **OPTION:** 85,91

### GEAR:Mace of Smiting

- **OPTION:** 92,95

### GEAR:Luck Blade (2 wishes)

- **OPTION:** 96,97

### GEAR:Holy Avenger

- **OPTION:** 98,99

### GEAR:Luck Blade (3 wishes)

- **OPTION:** 100

### STARTPACK:Minor Weapons Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Weapon Special Ability

- **OPTION:** 1,70

### KIT:+2 Weapon Special Ability

- **OPTION:** 71,85

### STARTPACK:+1 Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Common Melee Weapon Special Ability

- **OPTION:** 1,50

### KIT:+1 Uncommon Weapon Special Ability

- **OPTION:** 51,70

### KIT:+1 Common Ranged Weapon Special Ability

- **OPTION:** 71,100

### STARTPACK:+1 Common Melee Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### TABLE:Minor Special Ability (P/S)

- **VALUES:** EQMOD:BANE_M|1,10|EQMOD:DEFEND|11,17|EQMOD:FLM_M|18,27|EQMOD:FROST_M|28,37|EQMOD:SHOCK_M|38,47|EQMOD:GHOST_M|48,56|EQMOD:KEEN|57,67|EQMOD:KIFOC|68,71|EQMOD:MERC_M|72,75|EQMOD:MI_CLE|76,82|EQMOD:SPL_STR|83,87|EQMOD:THROW|88,91|EQMOD:THNDR_M|92,95|EQMOD:VICIOUS|96,99|[LOOKUP:Minor Special Ability (P/S),roll("1d100")][LOOKUP:Minor Special Ability (P/S),roll("1d100")]|100

### TABLE:Minor Special Ability (B)

- **VALUES:** EQMOD:BANE_M|1,10|EQMOD:DEFEND|11,17|EQMOD:FLM_M|18,27|EQMOD:FROST_M|28,37|EQMOD:SHOCK_M|38,47|EQMOD:GHOST_M|48,56|LOOKUP:Minor Special Ability (B),roll("1d100")|57,67|EQMOD:KIFOC|68,71|EQMOD:MERC_M|72,75|EQMOD:MI_CLE|76,82|EQMOD:SPL_STR|83,87|EQMOD:THROW|88,91|EQMOD:THNDR_M|92,95|EQMOD:VICIOUS|96,99|[LOOKUP:Minor Special Ability (B),roll("1d100")][LOOKUP:Minor Special Ability (B),roll("1d100")]|100

### STARTPACK:+1 Uncommon Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### TABLE:Minor Special Ability (R)

- **VALUES:** EQMOD:BANE_R|1,12|EQMOD:DISTNC|13,25|EQMOD:FLM_R|26,40|EQMOD:FROST_R|41,55|EQMOD:MERC_R|56,60|EQMOD:RETRN|61,68|EQMOD:SHOCK_R|69,83|EQMOD:SEEK|84,93|EQMOD:THNDR_R|94,99|[LOOKUP:Minor Special Ability (R),roll("1d100")][LOOKUP:Minor Special Ability (R),roll("1d100")]|100

### TABLE:Minor Special Ability (A)

- **VALUES:** EQMOD:BANE_A|1,12|LOOKUP:Minor Special Ability (A),roll("1d100")|13,25|EQMOD:FLM_A|26,40|EQMOD:FROST_A|41,55|EQMOD:MERC_A|56,60|EQMOD:RETRN|61,68|EQMOD:SHOCK_A|69,83|LOOKUP:Minor Special Ability (A),roll("1d100")|84,93|EQMOD:THNDR_A|94,99|[LOOKUP:Minor Special Ability (A),roll("1d100")][LOOKUP:Minor Special Ability (A),roll("1d100")]|100

### STARTPACK:+1 Common Ranged Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Ammunition Special Ability

- **OPTION:** 1,10

### TABLE:Minor Special Ability

- **VALUES:** EQMOD:BANE_R|1,12|EQMOD:DISTNC|13,25|EQMOD:FLM_R|26,40|EQMOD:FROST_R|41,55|EQMOD:MERC_R|56,60|EQMOD:RETRN|61,68|EQMOD:SHOCK_R|69,83|EQMOD:SEEK|84,93|EQMOD:THNDR_R|94,99|[LOOKUP:Minor Special Ability,roll("1d100")][LOOKUP:Minor Special Ability,roll("1d100")]|100

### STARTPACK:+1 Ammunition Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+2 Common Melee Weapon Special Ability

- **OPTION:** 1,50

### KIT:+2 Uncommon Weapon Special Ability

- **OPTION:** 51,70

### KIT:+2 Common Ranged Weapon Special Ability

- **OPTION:** 71,100

### STARTPACK:+2 Common Melee Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Uncommon Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Common Ranged Weapon Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Ammunition Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Medium Weapons Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Weapon Md Special Ability

- **OPTION:** 1,10

### KIT:+2 Weapon Md Special Ability

- **OPTION:** 11,29

### KIT:+3 Weapon Md Special Ability

- **OPTION:** 30,58

### KIT:+4 Weapon Md Special Ability

- **OPTION:** 59,62

### STARTPACK:+1 Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Common Melee Weapon Md Special Ability

- **OPTION:** 1,50

### KIT:+1 Uncommon Weapon Md Special Ability

- **OPTION:** 51,70

### KIT:+1 Common Ranged Weapon Md Special Ability

- **OPTION:** 71,100

### STARTPACK:+1 Common Melee Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### TABLE:Special Ability (P/S)

- **VALUES:** EQMOD:BANE_M|1,6|EQMOD:DEFEND|7,12|EQMOD:FLM_M|13,19|EQMOD:FROST_M|20,26|EQMOD:SHOCK_M|27,33|EQMOD:GHOST_M|34,38|EQMOD:KEEN|39,44|EQMOD:KIFOC|45,48|EQMOD:MERC_M|49,50|EQMOD:MI_CLE|51,54|EQMOD:SPL_STR|55,59|EQMOD:THROW|60,63|EQMOD:THNDR_M|64,65|EQMOD:VICIOUS|66,69|EQMOD:CHAOS_M|70,72|EQMOD:LAW_M|73,75|LOOKUP:Special Ability (P/S),roll("1d100")|76,78|EQMOD:FLM_BR_M|79,81|EQMOD:ICE_BR_M|82,84|EQMOD:HOLY_M|85,87|EQMOD:SHK_BR_M|88,90|EQMOD:UNHLY_M|91,93|EQMOD:WOUND|94,95|[LOOKUP:Special Ability (P/S),roll("1d100")][LOOKUP:Special Ability (P/S),roll("1d100")]|96,100

### STARTPACK:+1 Uncommon Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### TABLE:Special Ability (Any)

- **VALUES:** EQMOD:BANE_M|1,6|EQMOD:DEFEND|7,12|EQMOD:FLM_M|13,19|EQMOD:FROST_M|20,26|EQMOD:SHOCK_M|27,33|EQMOD:GHOST_M|34,38|EQMOD:KEEN|39,44|EQMOD:KIFOC|45,48|EQMOD:MERC_M|49,50|EQMOD:MI_CLE|51,54|EQMOD:SPL_STR|55,59|EQMOD:THROW|60,63|EQMOD:THNDR_M|64,65|EQMOD:VICIOUS|66,69|EQMOD:CHAOS_M|70,72|EQMOD:LAW_M|73,75|EQMOD:DISRPT|76,78|EQMOD:FLM_BR_M|79,81|EQMOD:ICE_BR_M|82,84|EQMOD:HOLY_M|85,87|EQMOD:SHK_BR_M|88,90|EQMOD:UNHLY_M|91,93|EQMOD:WOUND|94,95|[LOOKUP:Special Ability (Any),roll("1d100")][LOOKUP:Special Ability (Any),roll("1d100")]|96,100

### TABLE:Special Ability (R)

- **VALUES:** EQMOD:BANE_R|1,8|EQMOD:DISTNC|9,16|EQMOD:FLM_R|17,28|EQMOD:FROST_R|29,40|EQMOD:MERC_R|41,42|EQMOD:RETRN|43,47|EQMOD:SHOCK_R|48,59|EQMOD:SEEK|60,64|EQMOD:THNDR_R|65,68|EQMOD:CHAOS_R|69,71|EQMOD:LAW_R|72,74|EQMOD:FLM_BR_R|75,79|EQMOD:HOLY_R|80,82|EQMOD:ICE_BR_R|83,87|EQMOD:SHK_BR_R|88,92|EQMOD:UNHLY_R|93,95|[LOOKUP:Special Ability (R),roll("1d100")][LOOKUP:Special Ability (R),roll("1d100")]|96,100

### TABLE:Special Ability (A)

- **VALUES:** EQMOD:BANE_A|1,8|LOOKUP:Special Ability (A),roll("1d100")|9,16|EQMOD:FLM_A|17,28|EQMOD:FROST_A|29,40|EQMOD:MERC_A|41,42|EQMOD:RETRN|43,47|EQMOD:SHOCK_A|48,59|LOOKUP:Special Ability (A),roll("1d100")|60,64|EQMOD:THNDR_A|65,68|EQMOD:CHAOS_A|69,71|EQMOD:LAW_A|72,74|EQMOD:FLM_BR_A|75,79|EQMOD:HOLY_A|80,82|EQMOD:ICE_BR_A|83,87|EQMOD:SHK_BR_A|88,92|EQMOD:UNHLY_A|93,95|[LOOKUP:Special Ability (A),roll("1d100")][LOOKUP:Special Ability (A),roll("1d100")]|96,100

### STARTPACK:+1 Common Ranged Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+1 Ammunition Md Special Ability

- **OPTION:** 1,10

### STARTPACK:+1 Ammunition Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+2 Common Melee Weapon Md Special Ability

- **OPTION:** 1,50

### KIT:+2 Uncommon Weapon Md Special Ability

- **OPTION:** 51,70

### KIT:+2 Common Ranged Weapon Md Special Ability

- **OPTION:** 71,100

### STARTPACK:+2 Common Melee Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Uncommon Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+2 Common Ranged Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+2 Ammunition Md Special Ability

- **OPTION:** 1,10

### STARTPACK:+2 Ammunition Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Common Melee Weapon Md Special Ability

- **OPTION:** 1,50

### KIT:+3 Uncommon Weapon Md Special Ability

- **OPTION:** 51,70

### KIT:+3 Common Ranged Weapon Md Special Ability

- **OPTION:** 71,100

### STARTPACK:+3 Common Melee Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Uncommon Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Common Ranged Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Ammunition Md Special Ability

- **OPTION:** 1,10

### STARTPACK:+3 Ammunition Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+4 Common Melee Weapon Md Special Ability

- **OPTION:** 1,50

### KIT:+4 Uncommon Weapon Md Special Ability

- **OPTION:** 51,70

### KIT:+4 Common Ranged Weapon Md Special Ability

- **OPTION:** 71,100

### STARTPACK:+4 Common Melee Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Uncommon Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Common Ranged Weapon Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+4 Ammunition Md Special Ability

- **OPTION:** 1,10

### STARTPACK:+4 Ammunition Md Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Major Weapons Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Weapon Mj Special Ability

- **OPTION:** 1,20

### KIT:+4 Weapon Mj Special Ability

- **OPTION:** 21,38

### KIT:+5 Weapon Mj Special Ability

- **OPTION:** 39,49

### STARTPACK:+3 Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Common Melee Weapon Mj Special Ability

- **OPTION:** 1,50

### KIT:+3 Uncommon Weapon Mj Special Ability

- **OPTION:** 51,70

### KIT:+3 Common Ranged Weapon Mj Special Ability

- **OPTION:** 71,100

### STARTPACK:+3 Common Melee Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Uncommon Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+3 Common Ranged Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+3 Ammunition Mj Special Ability

- **OPTION:** 1,10

### STARTPACK:+3 Ammunition Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+4 Common Melee Weapon Mj Special Ability

- **OPTION:** 1,50

### KIT:+4 Uncommon Weapon Mj Special Ability

- **OPTION:** 51,70

### KIT:+4 Common Ranged Weapon Mj Special Ability

- **OPTION:** 71,100

### STARTPACK:+4 Common Melee Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Uncommon Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+4 Common Ranged Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+4 Ammunition Mj Special Ability

- **OPTION:** 1,10

### STARTPACK:+4 Ammunition Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+5 Common Melee Weapon Mj Special Ability

- **OPTION:** 1,50

### KIT:+5 Uncommon Weapon Mj Special Ability

- **OPTION:** 51,70

### KIT:+5 Common Ranged Weapon Mj Special Ability

- **OPTION:** 71,100

### STARTPACK:+5 Common Melee Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Uncommon Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:+5 Common Ranged Weapon Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### KIT:+5 Ammunition Mj Special Ability

- **OPTION:** 1,10

### STARTPACK:+5 Ammunition Mj Special Ability

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### STARTPACK:Minor Wondrous Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Feather Token (Anchor)

- **OPTION:** 1

### GEAR:Universal Solvent

- **OPTION:** 2

### GEAR:Elixir of Love

- **OPTION:** 3

### GEAR:Unguent of Timelessness

- **OPTION:** 4

### GEAR:Feather Token (Fan)

- **OPTION:** 5

### GEAR:Dust of Tracelessness

- **OPTION:** 6

### GEAR:Elixir of Hiding

- **OPTION:** 7

### GEAR:Elixir of Sneaking

- **OPTION:** 8

### GEAR:Elixir of Swimming

- **OPTION:** 9

### GEAR:Elixir of Vision

- **OPTION:** 10

### GEAR:Silversheen

- **OPTION:** 11

### GEAR:Feather Token (Bird)

- **OPTION:** 12

### GEAR:Feather Token (Tree)

- **OPTION:** 13

### GEAR:Feather Token (Swan Boat)

- **OPTION:** 14

### GEAR:Elixir of Truth

- **OPTION:** 15

### GEAR:Feather Token (Whip)

- **OPTION:** 16

### GEAR:Dust of Dryness

- **OPTION:** 17

### GEAR:Bag of Tricks (Gray)

- **OPTION:** 18

### GEAR:Hand of the Mage

- **OPTION:** 19

### GEAR:Bracers of Armor +1

- **OPTION:** 20

### GEAR:Cloak of Resistance +1

- **OPTION:** 21

### GEAR:Pearl of Power (1st Level)

- **OPTION:** 22

### GEAR:Phylactery of Faithfulness

- **OPTION:** 23

### GEAR:Salve of Slipperiness

- **OPTION:** 24

### GEAR:Elixir of Fire Breath

- **OPTION:** 25

### GEAR:Pipes of the Sewers

- **OPTION:** 26

### GEAR:Dust of Illusion

- **OPTION:** 27

### GEAR:Goggles of Minute Seeing

- **OPTION:** 28

### GEAR:Necklace of Fireballs I

- **OPTION:** 30

### GEAR:Dust of Appearance

- **OPTION:** 31

### GEAR:Hat of Disguise

- **OPTION:** 32

### GEAR:Pipes of Sounding

- **OPTION:** 33

### GEAR:Efficient Quiver

- **OPTION:** 34

### GEAR:Amulet of Natural Armor +1

- **OPTION:** 35

### GEAR:Handy Haversack

- **OPTION:** 36

### GEAR:Horn of Fog

- **OPTION:** 37

### GEAR:Elemental Gem (Transparent)

- **OPTION:** 38

### GEAR:Robe of Bones

- **OPTION:** 39

### GEAR:Sovereign Glue

- **OPTION:** 40

### GEAR:Bag of Holding (Type I)

- **OPTION:** 41

### GEAR:Boots of Elvenkind

- **OPTION:** 42

### GEAR:Boots of the winterlands

- **OPTION:** 43

### GEAR:Candle of Truth

- **OPTION:** 44

### GEAR:Cloak of Elvenkind

- **OPTION:** 45

### GEAR:Eyes of the Eagle

- **OPTION:** 46

### GEAR:Scarab (Golembane)

- **OPTION:** 47

### GEAR:Necklace of Fireballs II

- **OPTION:** 48

### GEAR:Stone of Alarm

- **OPTION:** 49

### GEAR:Bag of Tricks (Rust)

- **OPTION:** 50

### GEAR:Bead of Force

- **OPTION:** 51

### GEAR:Chime of Opening

- **OPTION:** 52

### GEAR:Horseshoes of Speed

- **OPTION:** 53

### GEAR:Rope of Climbing

- **OPTION:** 54

### GEAR:Dust of Disappearance

- **OPTION:** 55

### GEAR:Lens of Detection

- **OPTION:** 56

### GEAR:Vestments (Druid)

- **OPTION:** 57

### GEAR:Figurine of Wondrous Power (Silver Raven)

- **OPTION:** 58

### GEAR:Amulet of Health +2

- **OPTION:** 59

### GEAR:Gloves of Arrow Snaring

- **OPTION:** 64

### GEAR:Gloves of Dexterity +2

- **OPTION:** 65

### GEAR:Headband of Intellect +2

- **OPTION:** 66

### GEAR:Ioun Stone (Clear)

- **OPTION:** 67

### GEAR:Restorative Ointment

- **OPTION:** 68

### GEAR:Marvelous Pigments

- **OPTION:** 69

### GEAR:Pearl of Power (2nd Level)

- **OPTION:** 70

### GEAR:Periapt of Wisdom +2

- **OPTION:** 71

### GEAR:Stone Salve

- **OPTION:** 72

### GEAR:Necklace of Fireballs III

- **OPTION:** 73

### GEAR:Circlet of Persuasion

- **OPTION:** 74

### GEAR:Slippers of Spider Climbing

- **OPTION:** 75

### GEAR:Incense of Meditation

- **OPTION:** 76

### GEAR:Bag of Holding (Type II)

- **OPTION:** 77

### GEAR:Ioun Stone (Dusty Rose)

- **OPTION:** 79

### GEAR:Helm of Comprehend Languages and Read Magic

- **OPTION:** 80

### GEAR:Vest of Escape

- **OPTION:** 81

### GEAR:Eversmoking Bottle

- **OPTION:** 82

### GEAR:Sustaining Spoon

- **OPTION:** 83

### GEAR:Necklace of Fireballs IV

- **OPTION:** 84

### GEAR:Boots of Striding and Springing

- **OPTION:** 85

### GEAR:Wind Fan

- **OPTION:** 86

### GEAR:Amulet of Mighty Fists +1

- **OPTION:** 87

### GEAR:Horseshoes of a Zephyr

- **OPTION:** 88

### GEAR:Pipes of Haunting

- **OPTION:** 89

### GEAR:Necklace of Fireballs V

- **OPTION:** 90

### GEAR:Gloves of Swimming/Climbing

- **OPTION:** 91

### GEAR:Bag of Tricks (Tan)

- **OPTION:** 92

### GEAR:Circlet of Blasting (Minor)

- **OPTION:** 93

### GEAR:Horn of Goodness/Evil

- **OPTION:** 94

### GEAR:Robe of Useful Items

- **OPTION:** 95

### GEAR:Boat (Folding)

- **OPTION:** 96

### GEAR:Cloak of the Manta Ray

- **OPTION:** 97

### GEAR:Bottle of Air

- **OPTION:** 98

### GEAR:Bag of Holding (Type III)

- **OPTION:** 99

### GEAR:Periapt of Health

- **OPTION:** 100

### STARTPACK:Medium Wondrous Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Boots of Levitation

- **OPTION:** 1

### GEAR:Harp of Charming

- **OPTION:** 2

### GEAR:Amulet of Natural Armor +2

- **OPTION:** 3

### GEAR:Golem Manual (Flesh)

- **OPTION:** 4

### GEAR:Hand of Glory

- **OPTION:** 5

### GEAR:Ioun Stone (Deep Red)

- **OPTION:** 6

### GEAR:Ioun Stone (Incandescent Blue)

- **OPTION:** 7

### GEAR:Ioun Stone (Pale Blue)

- **OPTION:** 8

### GEAR:Ioun Stone (Pink and Green)

- **OPTION:** 9

### GEAR:Ioun Stone (Pink)

- **OPTION:** 10

### GEAR:Ioun Stone (Scarlet and Blue)

- **OPTION:** 11

### GEAR:Deck of Illusions

- **OPTION:** 12

### GEAR:Necklace of Fireballs VI

- **OPTION:** 13

### GEAR:Candle of Invocation

- **OPTION:** 14

### GEAR:Bracers of Armor +3

- **OPTION:** 15

### GEAR:Cloak of Resistance +3

- **OPTION:** 16

### GEAR:Decanter of Endless Water

- **OPTION:** 17

### GEAR:Necklace of Adaptation

- **OPTION:** 18

### GEAR:Pearl of Power (3rd Level)

- **OPTION:** 19

### GEAR:Talisman of the Sphere

- **OPTION:** 20

### GEAR:Figurine of Wondrous Power (Serpentine Owl)

- **OPTION:** 21

### GEAR:Necklace of Fireballs VII

- **OPTION:** 22

### GEAR:Strand of Prayer Beads (Lesser)

- **OPTION:** 23

### GEAR:Bag of Holding (Type IV)

- **OPTION:** 24

### GEAR:Figurine of Wondrous Power (Bronze Griffon)

- **OPTION:** 25

### GEAR:Figurine of Wondrous Power (Ebony Fly)

- **OPTION:** 26

### GEAR:Glove of Storing

- **OPTION:** 27

### GEAR:Ioun Stone (Dark Blue)

- **OPTION:** 28

### GEAR:Stone Horse (Courser)

- **OPTION:** 29

### GEAR:Cape of the Mountebank

- **OPTION:** 30

### GEAR:Phylactery of Undead Turning

- **OPTION:** 31

### GEAR:Gauntlet of Rust

- **OPTION:** 32

### GEAR:Boots of Speed

- **OPTION:** 33

### GEAR:Goggles of Night

- **OPTION:** 34

### GEAR:Golem Manual (Clay)

- **OPTION:** 35

### GEAR:Medallion of Thoughts

- **OPTION:** 36

### GEAR:Pipes of Pain

- **OPTION:** 37

### GEAR:Blessed Book

- **OPTION:** 38

### GEAR:Belt (Monk's)

- **OPTION:** 39

### GEAR:Gem of Brightness

- **OPTION:** 40

### GEAR:Lyre of Building

- **OPTION:** 41

### GEAR:Cloak of Arachnida

- **OPTION:** 42

### GEAR:Stone Horse (Destrier)

- **OPTION:** 43

### GEAR:Belt of Dwarvenkind

- **OPTION:** 44

### GEAR:Periapt of Wound Closure

- **OPTION:** 45

### GEAR:Horn of the Tritons

- **OPTION:** 46

### GEAR:Pearl of the Sirines

- **OPTION:** 47

### GEAR:Figurine of Wondrous Power (Onyx Dog)

- **OPTION:** 48

### GEAR:Amulet of Health +4

- **OPTION:** 49

### GEAR:Belt of Giant Strength +4

- **OPTION:** 50

### GEAR:Boots (Winged)

- **OPTION:** 51

### GEAR:Bracers of Armor +4

- **OPTION:** 52

### GEAR:Cloak of Charisma +4

- **OPTION:** 53

### GEAR:Cloak of Resistance +4

- **OPTION:** 54

### GEAR:Gloves of Dexterity +4

- **OPTION:** 55

### GEAR:Headband of Intellect +4

- **OPTION:** 56

### GEAR:Pearl of Power (4th Level)

- **OPTION:** 57

### GEAR:Periapt of Wisdom +4

- **OPTION:** 58

### GEAR:Scabbard of Keen Edges

- **OPTION:** 59

### GEAR:Figurine of Wondrous Power (Golden Lions)

- **OPTION:** 60

### GEAR:Chime of Interruption

- **OPTION:** 61

### GEAR:Broom of Flying

- **OPTION:** 62

### GEAR:Figurine of Wondrous Power (Marble Elephant)

- **OPTION:** 63

### GEAR:Amulet of Natural Armor +3

- **OPTION:** 64

### GEAR:Ioun Stone (Iridescent)

- **OPTION:** 65

### GEAR:Bracelet of Friends

- **OPTION:** 66

### GEAR:Carpet of Flying (5x5)

- **OPTION:** 67

### GEAR:Horn of Blasting

- **OPTION:** 68

### GEAR:Ioun Stone (Pale Lavender)

- **OPTION:** 69

### GEAR:Ioun Stone (Pearly White)

- **OPTION:** 70

### GEAR:Portable Hole

- **OPTION:** 71

### GEAR:Stone of Good Luck (Luckstone)

- **OPTION:** 72

### GEAR:Figurine of Wondrous Power (Ivory Goats)

- **OPTION:** 73

### GEAR:Rope of Entanglement

- **OPTION:** 74

### GEAR:Golem Manual (Stone)

- **OPTION:** 75

### GEAR:Mask of the Skull

- **OPTION:** 76

### GEAR:Mattock of the Titans

- **OPTION:** 77

### GEAR:Circlet of Blasting (Major)

- **OPTION:** 78

### GEAR:Amulet of Mighty Fists +2

- **OPTION:** 79

### GEAR:Cloak of Displacement (Minor)

- **OPTION:** 80

### GEAR:Helm of Underwater Action

- **OPTION:** 81

### GEAR:Bracers of Archery (Greater)

- **OPTION:** 82

### GEAR:Cloak of Resistance +5

- **OPTION:** 84

### GEAR:Eyes of Doom

- **OPTION:** 85

### GEAR:Pearl of Power (5th Level)

- **OPTION:** 86

### GEAR:Maul of the Titans

- **OPTION:** 87

### GEAR:Strand of Prayer Beads

- **OPTION:** 88

### GEAR:Cloak of the Bat

- **OPTION:** 89

### GEAR:Iron Bands of Binding

- **OPTION:** 90

### GEAR:Cube of Frost Resistance

- **OPTION:** 91

### GEAR:Helm of Telepathy

- **OPTION:** 92

### GEAR:Periapt of Proof against Poison

- **OPTION:** 93

### GEAR:Robe of Scintillating Colors

- **OPTION:** 94

### GEAR:Manual of Bodily Health +1

- **OPTION:** 95

### GEAR:Manual of Gainful Exercise +1

- **OPTION:** 96

### GEAR:Manual of Quickness of Action +1

- **OPTION:** 97

### GEAR:Tome of Clear Thought +1

- **OPTION:** 98

### GEAR:Tome of Leadership and Influence +1

- **OPTION:** 99

### GEAR:Tome of Understanding +1

- **OPTION:** 100

### STARTPACK:Major Wondrous Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Dimensional Shackles

- **OPTION:** 1

### GEAR:Figurine of Wondrous Power (Obsidian Steed)

- **OPTION:** 2

### GEAR:Drums of Panic

- **OPTION:** 3

### GEAR:Ioun Stone (Orange)

- **OPTION:** 4

### GEAR:Ioun Stone (Pale Green)

- **OPTION:** 5

### GEAR:Lantern of Revealing

- **OPTION:** 6

### GEAR:Robe of Blending

- **OPTION:** 7

### GEAR:Amulet of Natural Armor +4

- **OPTION:** 8

### GEAR:Amulet of Proof against Detection and Location

- **OPTION:** 9

### GEAR:Carpet of Flying (5x10)

- **OPTION:** 10

### GEAR:Golem Manual (Iron)

- **OPTION:** 11

### GEAR:Amulet of Health +6

- **OPTION:** 12

### GEAR:Belt of Giant Strength +6

- **OPTION:** 13

### GEAR:Bracers of Armor +6

- **OPTION:** 14

### GEAR:Cloak of Charisma +6

- **OPTION:** 15

### GEAR:Gloves of Dexterity +6

- **OPTION:** 16

### GEAR:Headband of Intellect +6

- **OPTION:** 17

### GEAR:Ioun Stone (Vibrant Purple)

- **OPTION:** 18

### GEAR:Pearl of Power (6th Level)

- **OPTION:** 19

### GEAR:Periapt of Wisdom +6

- **OPTION:** 20

### GEAR:Scarab of Protection

- **OPTION:** 21

### GEAR:Ioun Stone (Lavender and Green)

- **OPTION:** 22

### GEAR:Ring Gates

- **OPTION:** 23

### GEAR:Crystal Ball

- **OPTION:** 24

### GEAR:Golem Manual (Greater Stone)

- **OPTION:** 25

### GEAR:Orb of Storms

- **OPTION:** 26

### GEAR:Boots of Teleportation

- **OPTION:** 27

### GEAR:Bracers of Armor +7

- **OPTION:** 28

### GEAR:Pearl of Power (7th Level)

- **OPTION:** 29

### GEAR:Amulet of Natural Armor +5

- **OPTION:** 30

### GEAR:Cloak of Displacement (Major)

- **OPTION:** 31

### GEAR:Crystal Ball (See Invisibility)

- **OPTION:** 32

### KIT:Horn of Valhalla

- **OPTION:** 33

### GEAR:Crystal Ball (Detect Thoughts)

- **OPTION:** 34

### GEAR:Amulet of Mighty Fists +3

- **OPTION:** 36

### GEAR:Wings of Flying

- **OPTION:** 37

### GEAR:Cloak of Etherealness

- **OPTION:** 38

### GEAR:Instant Fortress

- **OPTION:** 39

### GEAR:Manual of Bodily Health +2

- **OPTION:** 40

### GEAR:Manual of Gainful Exercise +2

- **OPTION:** 41

### GEAR:Manual of Quickness of Action +2

- **OPTION:** 42

### GEAR:Tome of Clear Thought +2

- **OPTION:** 43

### GEAR:Tome of Leadership and Influence +2

- **OPTION:** 44

### GEAR:Tome of Understanding +2

- **OPTION:** 45

### GEAR:Eyes of Charming

- **OPTION:** 46

### GEAR:Robe of Stars

- **OPTION:** 47

### GEAR:Carpet of Flying (10x10)

- **OPTION:** 48

### GEAR:Darkskull

- **OPTION:** 49

### GEAR:Cube of Force

- **OPTION:** 50

### GEAR:Bracers of Armor +8

- **OPTION:** 51

### GEAR:Pearl of Power (8th Level)

- **OPTION:** 52

### GEAR:Crystal Ball (Telepathy)

- **OPTION:** 53

### GEAR:Horn of Blasting (Greater)

- **OPTION:** 54

### GEAR:Pearl of Power (2 Spells)

- **OPTION:** 55

### GEAR:Helm of Teleportation

- **OPTION:** 56

### GEAR:Gem of Seeing

- **OPTION:** 57

### KIT:Robe of the Archmagi

- **OPTION:** 58

### GEAR:Mantle of Faith

- **OPTION:** 59

### GEAR:Crystal Ball (True Seeing)

- **OPTION:** 60

### GEAR:Pearl of Power (9th Level)

- **OPTION:** 61

### GEAR:Well of Many Worlds

- **OPTION:** 62

### GEAR:Manual of Bodily Health +3

- **OPTION:** 63

### GEAR:Manual of Gainful Exercise +3

- **OPTION:** 64

### GEAR:Manual of Quickness of Action +3

- **OPTION:** 65

### GEAR:Tome of Clear Thought +3

- **OPTION:** 66

### GEAR:Tome of Leadership and Influence +3

- **OPTION:** 67

### GEAR:Tome of Understanding +3

- **OPTION:** 68

### GEAR:Apparatus of the Kwalish

- **OPTION:** 69

### GEAR:Mantle of Spell Resistance

- **OPTION:** 70

### GEAR:Mirror of Opposition

- **OPTION:** 71

### GEAR:Strand of Prayer Beads (Greater)

- **OPTION:** 72

### GEAR:Amulet of Mighty Fists +4

- **OPTION:** 73

### GEAR:Eyes of Petrification

- **OPTION:** 74

### GEAR:Bowl of Commanding Water Elementals

- **OPTION:** 75

### GEAR:Brazier of Commanding Fire Elementals

- **OPTION:** 76

### GEAR:Censer of Controlling Air Elementals

- **OPTION:** 77

### GEAR:Stone of Controlling Earth Elementals

- **OPTION:** 78

### GEAR:Manual of Bodily Health +4

- **OPTION:** 79

### GEAR:Manual of Gainful Exercise +4

- **OPTION:** 80

### GEAR:Manual of Quickness of Action +4

- **OPTION:** 81

### GEAR:Tome of Clear Thought +4

- **OPTION:** 82

### GEAR:Tome of Leadership and Influence +4

- **OPTION:** 83

### GEAR:Tome of Understanding +4

- **OPTION:** 84

### GEAR:Amulet of the Planes

- **OPTION:** 85

### GEAR:Robe of Eyes

- **OPTION:** 86

### GEAR:Helm of Brilliance

- **OPTION:** 87

### GEAR:Manual of Bodily Health +5

- **OPTION:** 88

### GEAR:Manual of Gainful Exercise +5

- **OPTION:** 89

### GEAR:Manual of Quickness of Action +5

- **OPTION:** 90

### GEAR:Tome of Clear Thought +5

- **OPTION:** 91

### GEAR:Tome of Leadership and Influence +5

- **OPTION:** 92

### GEAR:Tome of Understanding +5

- **OPTION:** 93

### GEAR:Efreeti Bottle

- **OPTION:** 94

### GEAR:Amulet of Mighty Fists +5

- **OPTION:** 95

### GEAR:Chaos Diamond

- **OPTION:** 96

### GEAR:Cubic Gate

- **OPTION:** 97

### GEAR:Iron Flask

- **OPTION:** 98

### GEAR:Mirror of Mental Prowess

- **OPTION:** 99

### GEAR:Mirror of Life Trapping

- **OPTION:** 100

### STARTPACK:Robe of the Archmagi

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Robe of the Archmagi (White)

- **OPTION:** 1,45

### GEAR:Robe of the Archmagi (Gray)

- **OPTION:** 46,75

### GEAR:Robe of the Archmagi (Black)

- **OPTION:** 76,100

### STARTPACK:Horn of Valhalla

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Horn of Valhalla (Silver)

- **OPTION:** 1,40

### GEAR:Horn of Valhalla (Brass)

- **OPTION:** 41,75

### GEAR:Horn of Valhalla (Bronze)

- **OPTION:** 76,90

### GEAR:Horn of Valhalla (Iron)

- **OPTION:** 91,100

### STARTPACK:Specific Cursed Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Incense of Obsession

- **OPTION:** 01,05

### GEAR:Ring (Clumsiness)

- **OPTION:** 06,15

### GEAR:Amulet of Inescapable Location

- **OPTION:** 16,20

### GEAR:Stone of Weight (Loadstone)

- **OPTION:** 21,25

### GEAR:Bracers of Defenselessness

- **OPTION:** 26,30

### KIT:Gauntlets of Fumbling

- **OPTION:** 31,35

### GEAR:Sword -2 (Cursed)

- **OPTION:** 36,40

### GEAR:Armor of Rage

- **OPTION:** 41,43

### GEAR:Medallion of Thought Projection

- **OPTION:** 44,46

### GEAR:Flask of Curses

- **OPTION:** 47,52

### GEAR:Dust of Sneezing and Choking

- **OPTION:** 53,54

### GEAR:Helm of Opposite Alignment

- **OPTION:** 55

### GEAR:Potion (Poison)

- **OPTION:** 56,60

### GEAR:Broom of Animated Attack

- **OPTION:** 61

### GEAR:Robe of Powerlessness

- **OPTION:** 62,63

### GEAR:Vacuous Grimoire

- **OPTION:** 64

### GEAR:Spear (Cursed Backbiter)

- **OPTION:** 65,68

### GEAR:Armor of Arrow Attraction

- **OPTION:** 69,70

### GEAR:Net of Snaring

- **OPTION:** 71,72

### GEAR:Bag of Devouring

- **OPTION:** 73,75

### GEAR:Mace of Blood

- **OPTION:** 76,80

### GEAR:Robe of Vermin

- **OPTION:** 81,85

### GEAR:Periapt of Foul Rotting

- **OPTION:** 86,88

### GEAR:Sword (Berserking)

- **OPTION:** 89,92

### GEAR:Boots of Dancing

- **OPTION:** 93,96

### GEAR:Crystal Hypnosis Ball

- **OPTION:** 97

### GEAR:Necklace of Strangulation

- **OPTION:** 98

### GEAR:Cloak of Poisonousness

- **OPTION:** 99

### GEAR:Scarab of Death

- **OPTION:** 100

### STARTPACK:Gauntlets of Fumbling

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Gauntlets of Fumbling (Gloves)

- **OPTION:** 1,50

### GEAR:Gauntlets of Fumbling (Gauntlets)

- **OPTION:** 51,100

### STARTPACK:Necklace of Fireballs I

- **APPLY:** INSTANT
- **EQUIPBUY:** 100
- **SORTKEY:** Necklace of Fireballs 1

### GEAR:Necklace of Fireballs I 2


### KIT:Necklace of Fireballs Spheres I


### STARTPACK:Necklace of Fireballs Spheres I

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Necklace of Fireballs Spheres 01

### GEAR:Necklace of Fireballs Sphere 5d6

- **QTY:** 1

### GEAR:Necklace of Fireballs Sphere 3d6

- **QTY:** 2

### STARTPACK:Necklace of Fireballs II

- **APPLY:** INSTANT
- **EQUIPBUY:** 100
- **SORTKEY:** Necklace of Fireballs 2

### GEAR:Necklace of Fireballs II 2


### KIT:Necklace of Fireballs Spheres II


### STARTPACK:Necklace of Fireballs Spheres II

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Necklace of Fireballs Spheres 02

### GEAR:Necklace of Fireballs Sphere 6d6

- **QTY:** 1

### GEAR:Necklace of Fireballs Sphere 4d6

- **QTY:** 2

### GEAR:Necklace of Fireballs Sphere 2d6

- **QTY:** 2

### STARTPACK:Necklace of Fireballs III

- **APPLY:** INSTANT
- **EQUIPBUY:** 100
- **SORTKEY:** Necklace of Fireballs 3

### GEAR:Necklace of Fireballs III 2


### KIT:Necklace of Fireballs Spheres III


### STARTPACK:Necklace of Fireballs Spheres III

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Necklace of Fireballs Spheres 03

### GEAR:Necklace of Fireballs Sphere 7d6

- **QTY:** 1

### STARTPACK:Necklace of Fireballs IV

- **APPLY:** INSTANT
- **EQUIPBUY:** 100
- **SORTKEY:** Necklace of Fireballs 4

### GEAR:Necklace of Fireballs IV 2


### KIT:Necklace of Fireballs Spheres IV


### STARTPACK:Necklace of Fireballs Spheres IV

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Necklace of Fireballs Spheres 04

### GEAR:Necklace of Fireballs Sphere 8d6

- **QTY:** 1

### STARTPACK:Necklace of Fireballs V

- **APPLY:** INSTANT
- **EQUIPBUY:** 100
- **SORTKEY:** Necklace of Fireballs 5

### GEAR:Necklace of Fireballs V 2


### KIT:Necklace of Fireballs Spheres V


### STARTPACK:Necklace of Fireballs Spheres V

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Necklace of Fireballs Spheres 05

### GEAR:Necklace of Fireballs Sphere 9d6

- **QTY:** 1

### STARTPACK:Necklace of Fireballs VI

- **APPLY:** INSTANT
- **EQUIPBUY:** 100
- **SORTKEY:** Necklace of Fireballs 6

### GEAR:Necklace of Fireballs VI 2


### KIT:Necklace of Fireballs Spheres VI


### STARTPACK:Necklace of Fireballs Spheres VI

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Necklace of Fireballs Spheres 06

### GEAR:Necklace of Fireballs Sphere 10d6

- **QTY:** 1

### STARTPACK:Necklace of Fireballs VII

- **APPLY:** INSTANT
- **EQUIPBUY:** 100
- **SORTKEY:** Necklace of Fireballs 7

### GEAR:Necklace of Fireballs VII 2


### KIT:Necklace of Fireballs Spheres VII


### STARTPACK:Necklace of Fireballs Spheres VII

- **APPLY:** INSTANT
- **EQUIPBUY:** 0
- **SORTKEY:** Necklace of Fireballs Spheres 07

### STARTPACK:Robe of Bones

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Robe of Bones 2


### KIT:Robe of Bones Patches


### STARTPACK:Robe of Bones Patches

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Robe of Bones Skeleton (Goblin/Small)

- **QTY:** 2

### GEAR:Robe of Bones Skeleton (Human Commoner/Medium)

- **QTY:** 2

### GEAR:Robe of Bones Skeleton (Wolf/Medium)

- **QTY:** 2

### GEAR:Robe of Bones Zombie (Goblin/Small)

- **QTY:** 2

### GEAR:Robe of Bones Zombie (Human Commoner/Medium)

- **QTY:** 2

### GEAR:Robe of Bones Zombie (Wolf/Medium)

- **QTY:** 2

### STARTPACK:Robe of Stars

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Robe of Stars 2


### KIT:Robe of Stars Shuriken +5


### STARTPACK:Robe of Stars Shuriken +5

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Robe of Stars Shuriken +5

- **QTY:** 6

### STARTPACK:Robe of Useful Items

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Robe of Useful Items 2


### KIT:Robe of Useful Items Gear


### STARTPACK:Robe of Useful Items Gear

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Mirror (Large/Steel/Highly Polished)

- **QTY:** 2

### GEAR:Pole (10 Ft.)

- **QTY:** 2

### GEAR:Sack

- **QTY:** 2

### KIT:Robe of Useful Items Component Number


### STARTPACK:Robe of Useful Items Component Number

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### SELECT:roll("4d4")


### KIT:Robe of Useful Items Component

- **OPTION:** 16

### STARTPACK:Robe of Useful Items Component

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

### GEAR:Bag (Coin)

- **OPTION:** 1,8

### GEAR:Coffer (Silver)

- **OPTION:** 9,15

### GEAR:Door (Iron)

- **OPTION:** 16,22

### GEAR:Gem (Robe/100 gp)

- **QTY:** 10
- **OPTION:** 23,30

### GEAR:Ladder (24 Ft.)

- **OPTION:** 31,44

### GEAR:Mule

- **OPTION:** 45,51

### GEAR:Saddlebags

- **OPTION:** 45,51

### GEAR:Pit (Open)

- **OPTION:** 52,59

### GEAR:Rowboat

- **OPTION:** 69,75

### KIT:Minor Scroll Spell

- **OPTION:** 76,83

### GEAR:Dog (War)

- **QTY:** 2
- **OPTION:** 84,90

### GEAR:Window

- **OPTION:** 91,96

### GEAR:Ram (Portable)

- **OPTION:** 97,100

### STARTPACK:Minor Scroll Spell

- **APPLY:** INSTANT
- **EQUIPBUY:** 0

## Languages

### Aboleth


### Aquan


### Auran


### Blink Dog


### Drow Sign Language


### Ettin Pidgin


### Formian


### Grimlock


### Ignan


### Sahuagin


### Sphinx


### Treant


### Telepathy

- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Telepathy

### Worg


### Kuo-toan


### Githyanki


### Githzerai


### Slaad


### Yuan-Ti


### Forest Animals


## Profs Weapon

### Giant Rock


## Races

### Goblin

- **FAVCLASS:** Rogue
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **AUTO:** LANG|Common|Goblin
- **ABILITY:** Race|AUTOMATIC|Goblin
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Goblinoid
- **CR:** 1/2

### Hobgoblin

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **AUTO:** LANG|Common|Goblin
- **ABILITY:** Race|AUTOMATIC|Hobgoblin
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Goblinoid
- **LEVELADJUSTMENT:** 1
- **CR:** 1/2

### Orc

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **AUTO:** LANG|Common|Orc
- **ABILITY:** Race|AUTOMATIC|Orc
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Orc
- **CR:** 1/2

### Kobold

- **FAVCLASS:** Sorcerer
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Race|AUTOMATIC|Kobold
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Reptilian
- **CR:** 1/4

### Aasimar

- **SORTKEY:** A1
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **CR:** 1/2
- **INFO:** DESC|Planetouched human creatures with a hint of celestial or diety in their ancestry.
- **ABILITY:** Race|AUTOMATIC|Aasimar

### Tiefling

- **SORTKEY:** A8
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **CR:** 1/2
- **INFO:** DESC|Planetouched human creatures descended from an evil outsider such as a demon or devil.
- **ABILITY:** Race|AUTOMATIC|Tiefling

### Lizardfolk

- **FAVCLASS:** Druid
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Aquan,Gnoll,Goblin,Orc
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **MONCSKILL:** Balance|Jump|Swim
- **AUTO:** LANG|Common|Draconic
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Lizardfolk
- **LEGS:** 2
- **HANDS:** 3
- **MONSTERCLASS:** Humanoid:2
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Reptilian
- **BONUS:** VAR|LevelAdjustment|1|TYPE=Base
- **CR:** 1

### Aboleth

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,10,Swim,60
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Concentration|Listen|Spot|Swim|TYPE=Knowledge
- **AUTO:** LANG|Aboleth|Aquan|Undercommon
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aboleth ~ Enslave|Aboleth ~ Mucus Cloud|Aboleth ~ Psionics|Aboleth ~ Skills|Aboleth ~ Slime
- **LEGS:** 0
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Finesseable.Bludgeoning.Slime,*4,1d6
- **MONSTERCLASS:** Aberration:8
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 16,24
- **CR:** 7

### Achaierai

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Balance|Climb|Diplomacy|Hide|Jump|Listen|Move Silently|Sense Motive|Spot
- **AUTO:** LANG|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Achairai ~ Black Cloud|Achairai ~ Natural Weapons
- **LEGS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6
- **SR:** 19
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Evil|Extraplanar|Lawful
- **HITDICEADVANCEMENT:** 12,18
- **CR:** 5
- **KIT:** 1|LE

### Allip

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Fly,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TurnResistBonus|2
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Hide|Intimidate|Listen|Search|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Allip ~ Babble|Allip ~ Madness|Allip ~ Wisdom Drain|Turn Resistance
- **LEGS:** 0
- **NATURALATTACKS:** Incorporeal touch,Weapon.Natural.Melee.Finesseable.Wisdom,*1,1d4
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **RACESUBTYPE:** Incorporeal
- **HITDICEADVANCEMENT:** 12
- **CR:** 3
- **KIT:** 1|NE

### Angel (Astral Deva)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50,Fly,100
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|8
- **BONUS:** STAT|WIS|8
- **BONUS:** STAT|CHA|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|UncannyDodgeFlankingLevel|12
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** VAR|UncannyDodgeLevel|2
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Hide|Intimidate|Listen|Move Silently|Sense Motive|Spot|Use Rope|TYPE=Craft|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Mace (Heavy)|TYPE=Martial|TYPE=Simple
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Astral Daeva
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **DEFINE:** UncannyDodgeLevel|0
- **SR:** 30
- **DR:** 10/Evil
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Angel|Extraplanar|Good
- **HITDICEADVANCEMENT:** 18,36
- **LEVELADJUSTMENT:** 8
- **CR:** 14
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Aid,12+CHA|Continual Flame,12+CHA|Detect Evil,11+CHA|Discern Lies,14+CHA|Dispel Evil,15+CHA|Dispel Magic,13+CHA|Holy Aura,18+CHA|Holy Smite,14+CHA|Holy Word,17+CHA|Invisibility (Self Only),12+CHA|Plane Shift,17+CHA|Polymorph (Self Only),14+CHA|Remove Curse,13+CHA|Remove Disease,13+CHA|Remove Fear,11+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=12|Blade Barrier,16+CHA|Heal,16+CHA
- **SPELLS:** Innate|TIMES=7|CASTERLEVEL=12|Cure Light Wounds,11+CHA|See Invisibility,12+CHA
- **KIT:** 1|CG|LG|NG

### Angel (Planetar)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,90
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|19|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Cleric|16
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|12
- **BONUS:** STAT|WIS|12
- **BONUS:** STAT|CHA|12
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spot|Use Rope|TYPE=Craft|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Greatsword|TYPE=Martial|TYPE=Simple
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Planetar
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8
- **SR:** 30
- **DR:** 10/Evil
- **MONSTERCLASS:** Outsider:14
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Angel|Extraplanar|Good
- **HITDICEADVANCEMENT:** 21,42
- **CR:** 16
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=17|Continual Flame,12+CHA|Dispel Magic,13+CHA|Holy Smite,14+CHA|Invisibility (Self Only),12+CHA|Remove Curse,13+CHA|Remove Disease,13+CHA|Remove Fear,11+CHA|Restoration (Lesser),12+CHA|Speak with Dead,13+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=17|Charm Monster (Mass),18+CHA|Earthquake,18+CHA|Restoration (Greater),17+CHA|Waves of Exhaustion,17+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=17|Blade Barrier,16+CHA|Flame Strike,15+CHA|Polymorph (Self Only),14+CHA|Power Word Stun,18+CHA|Raise Dead,15+CHA|Waves of Fatigue,15+CHA
- **ADD:** SPELLCASTER|Cleric
- **KIT:** 1|CG|LG|NG

### Angel (Solar)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50,Fly,150
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|21|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Cleric|19
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|12
- **BONUS:** STAT|WIS|14
- **BONUS:** STAT|CHA|14
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Hide|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival|Use Rope|TYPE=Craft|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Greatsword|Longbow|TYPE=Martial|TYPE=Simple
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Solar
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8
- **SR:** 32
- **DR:** 15/Epic and Evil
- **MONSTERCLASS:** Outsider:22
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Angel|Extraplanar|Good
- **HITDICEADVANCEMENT:** 33,66
- **CR:** 23
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=20|Aid,12+CHA|Animate Objects,16+CHA|Commune,15+CHA|Continual Flame,12+CHA|Dimensional Anchor,14+CHA|Dispel Magic (Greater),16+CHA|Holy Smite,14+CHA|Imprisonment,19+CHA|Invisibility (Self Only),12+CHA|Polymorph (Self Only),14+CHA|Remove Curse,13+CHA|Remove Disease,13+CHA|Remove Fear,11+CHA|Resist Energy,12+CHA|Restoration (Lesser),12+CHA|Speak with Dead,13+CHA|Summon Monster VII,17+CHA|Waves of Fatigue,15+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=20|Power Word Blind,17+CHA|Power Word Kill,19+CHA|Power Word Stun,18+CHA|Prismatic Spray,17+CHA|Restoration (Greater),17+CHA|Wish,19+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=20|Blade Barrier,16+CHA|Charm Monster (Mass),18+CHA|Earthquake,18+CHA|Heal,16+CHA|Permanency,15+CHA|Resurrection,17+CHA|Waves of Exhaustion,17+CHA
- **ADD:** SPELLCASTER|Cleric
- **KIT:** 1|CG|LG|NG

### Animated Object (Tiny)

- **SIZE:** T
- **MOVE:** Walk,10
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** ABILITYPOOL|Animated Object Move|1
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|WIS|-9
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AnimatedObject
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d3
- **MONSTERCLASS:** Construct (Mindless):1
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** Half Hitdie
- **CR:** 1/2
- **KIT:** 1|TN

### Animated Object (Small)

- **SIZE:** S
- **MOVE:** Walk,10
- **FACE:** 5
- **REACH:** 5
- **BONUS:** ABILITYPOOL|Animated Object Move|1
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|WIS|-9
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AnimatedObject
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4
- **MONSTERCLASS:** Construct (Mindless):1
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **CR:** 1
- **KIT:** 1|TN

### Animated Object (Medium)

- **SIZE:** M
- **MOVE:** Walk,10
- **FACE:** 5
- **REACH:** 5
- **BONUS:** ABILITYPOOL|Animated Object Move|1
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|WIS|-9
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AnimatedObject
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Construct (Mindless):2
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **CR:** 2
- **KIT:** 1|TN

### Animated Object (Large)

- **SIZE:** L
- **MOVE:** Walk,10
- **FACE:** 10
- **REACH:** 5
- **BONUS:** ABILITYPOOL|Animated Object Move|1
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|WIS|-9
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AnimatedObject
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **MONSTERCLASS:** Construct (Mindless):4
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **CR:** 3
- **KIT:** 1|TN

### Animated Object (Huge)

- **SIZE:** H
- **MOVE:** Walk,10
- **FACE:** 15
- **REACH:** 10
- **BONUS:** ABILITYPOOL|Animated Object Move|1
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|WIS|-9
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AnimatedObject
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Construct (Mindless):8
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **CR:** 5
- **KIT:** 1|TN

### Animated Object (Gargantuan)

- **SIZE:** G
- **MOVE:** Walk,10
- **FACE:** 20
- **REACH:** 15
- **BONUS:** ABILITYPOOL|Animated Object Move|1
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|-4
- **BONUS:** STAT|WIS|-9
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AnimatedObject
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8
- **MONSTERCLASS:** Construct (Mindless):16
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **CR:** 7
- **KIT:** 1|TN

### Animated Object (Colossal)

- **SIZE:** C
- **MOVE:** Walk,10
- **FACE:** 30
- **REACH:** 20
- **BONUS:** ABILITYPOOL|Animated Object Move|1
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-6
- **BONUS:** STAT|WIS|-9
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|TYPE=AnimatedObject
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,4d6
- **MONSTERCLASS:** Construct (Mindless):32
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **CR:** 10
- **KIT:** 1|TN

### Ankheg

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Burrow,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Ankheg ~ Improved Grab|Ankheg ~ Spit Acid
- **LEGS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Acid,*1,2d6
- **MONSTERCLASS:** Magical Beast:3
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 4,9
- **CR:** 3
- **KIT:** 1|TN

### Aranea

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50,Climb,25
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer|2
- **BONUS:** SKILL|Jump,Listen,Spot|2|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Web|TOHIT|5
- **MONCSKILL:** Climb|Concentration|Escape Artist|Jump|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Iron Will
- **AUTO:** LANG|Common|Sylvan
- **ABILITY:** Special Ability|AUTOMATIC|Aranea ~ Change Shape|Aranea ~ Poison|Aranea ~ Skills|Aranea ~ Spells|Aranea ~ Web
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d6|Web,Weapon.Natural.Ranged.Touch.Entangle,*1,1d0
- **MONSTERCLASS:** Magical Beast:3
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Shapechanger
- **LEVELADJUSTMENT:** 4
- **CR:** 4
- **ADD:** SPELLCASTER|Sorcerer

### Archon (Lantern)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Concentration|Diplomacy|Knowledge (The Planes)|Listen|Sense Motive|Spot
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Lantern Archon ~ Aura of Menace|Lantern Archon ~ Light Ray|Lantern Archon ~ Spell-Like Abilities
- **LEGS:** 0
- **NATURALATTACKS:** Ray,Weapon.Natural.Ranged.Touch.Piercing,*2,1d6
- **DR:** 10/Evil
- **MONSTERCLASS:** Outsider:1
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Archon|Extraplanar|Good|Lawful
- **HITDICEADVANCEMENT:** 4
- **CR:** 2
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=3|Aid,12+CHA|Continual Flame,12+CHA|Detect Evil,11+CHA
- **KIT:** 1|LG

### Archon (Hound)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HoundArchonSpecialMount|1
- **MONCSKILL:** Concentration|Diplomacy|Hide|Jump|Listen|Move Silently|Sense Motive|Spot|Survival
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Greatsword|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Hound Archon ~ Aura of Menace|Hound Archon ~ Change Shape|Hound Archon ~ Skills|Hound Archon ~ Spell-Like Abilities|Scent
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8|Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **DEFINE:** HoundArchonSpecialMount|0
- **SR:** 16
- **DR:** 10/Evil
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Archon|Extraplanar|Good|Lawful
- **HITDICEADVANCEMENT:** 9,18
- **LEVELADJUSTMENT:** 5
- **CR:** 4
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=6|Aid,12+CHA|Continual Flame,12+CHA|Detect Evil,11+CHA|Message,10+CHA
- **KIT:** 1|LG

### Archon (Trumpet)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Fly,90
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Cleric|13
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Handle Animal|Listen|Move Silently|Perform (Wind Instruments)|Ride|Sense Motive|Spot|Use Rope|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Greatsword|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Trumpet Archon ~ Aura of Menace|Trumpet Archon ~ Spell-Like Abilities|Trumpet Archon ~ Spells|Trumpet Archon ~ Trumpet
- **LEGS:** 2
- **SR:** 29
- **DR:** 10/Evil
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Archon|Extraplanar|Good|Lawful
- **HITDICEADVANCEMENT:** 18,36
- **LEVELADJUSTMENT:** 8
- **CR:** 14
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Continual Flame,12+CHA|Detect Evil,11+CHA|Message,10+CHA
- **ADD:** SPELLCASTER|Cleric
- **KIT:** 1|LG

### Arrowhawk (Adult)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Bite|TOHIT|5
- **MONCSKILL:** Diplomacy|Escape Artist|Knowledge (The Planes)|Listen|Move Silently|Search|Sense Motive|Spot|Survival|Use Rope
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Arrowhawk ~ Electricity Ray|Immunity to Acid|Immunity to Electricity|Immunity to Poison|Resistance to Cold|Resistance to Fire
- **LEGS:** 0
- **NATURALATTACKS:** Electricity Ray,Weapon.Natural.Ranged.Touch.Piercing,*1,2d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 14
- **CR:** 5
- **KIT:** 1|TN

### Arrowhawk (Elder)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Fly,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Bite|TOHIT|5
- **MONCSKILL:** Diplomacy|Escape Artist|Knowledge (The Planes)|Listen|Move Silently|Search|Sense Motive|Spot|Survival|Use Rope
- **ABILITY:** FEAT|AUTOMATIC|Weapon Focus(Bite)
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Arrowhawk ~ Electricity Ray|Immunity to Acid|Immunity to Electricity|Immunity to Poison|Resistance to Cold|Resistance to Fire
- **LEGS:** 0
- **NATURALATTACKS:** Electricity Ray,Weapon.Natural.Ranged.Touch.Piercing,*1,2d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Outsider:15
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 24,32
- **CR:** 8
- **KIT:** 1|TN

### Arrowhawk (Juvenile)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Bite|TOHIT|5
- **MONCSKILL:** Diplomacy|Escape Artist|Knowledge (The Planes)|Listen|Move Silently|Search|Sense Motive|Spot|Survival|Use Rope
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Arrowhawk ~ Electricity Ray|Immunity to Acid|Immunity to Electricity|Immunity to Poison|Resistance to Cold|Resistance to Fire
- **LEGS:** 0
- **NATURALATTACKS:** Electricity Ray,Weapon.Natural.Ranged.Touch.Piercing,*1,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 6
- **CR:** 3
- **KIT:** 1|TN

### Assassin Vine

- **SIZE:** L
- **MOVE:** Walk,5
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|BlindsightRange|30|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|Assassin Vine ~ Blindsight|Assassin Vine ~ Camouflage|Assassin Vine ~ Constrict|Assassin Vine ~ Entangle|Assassin Vine ~ Improved Grab|Immunity to Electricity|Resistance to Cold|Resistance to Fire
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Plant (Mindless):4
- **RACETYPE:** Plant
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 4,16,32,*
- **CR:** 3
- **KIT:** 1|TN

### Athach

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,50
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Jump|Listen|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Morningstar|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Athach ~ Poison
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Thrown Rock,Weapon.Natural.Ranged.Thrown.Bludgeoning,*1,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d8
- **MONSTERCLASS:** Aberration:14
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 28
- **LEVELADJUSTMENT:** 5
- **CR:** 8

### Azer

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Abyssal,Aquan,Auran,Celestial,Infernal,Terran
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Appraise|Climb|Hide|Jump|Listen|Search|Spot|TYPE=Craft
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Common|Ignan
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Shortspear|Warhammer|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Azer ~ Heat
- **LEGS:** 2
- **SR:** 13
- **MONSTERCLASS:** Outsider:2
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Fire
- **LEVELADJUSTMENT:** 4
- **CR:** 2
- **KIT:** 1|LN

### Barghest

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Hide|Intimidate|Jump|Listen|Move Silently|Search|Sense Motive|Spot|Survival
- **AUTO:** LANG|Goblin|Infernal|Worg
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Barghest ~ Change Shape|Barghest ~ Feed|Barghest ~ Natural Weapons|Barghest ~ Pass Without Trace|Barghest ~ Skills|Barghest ~ Spell-Like Abilities|Scent
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Evil|Extraplanar|Lawful|Shapechanger
- **CR:** 4
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=HD|Blink,13+CHA|Levitate,12+CHA|Misdirection,12+CHA|Rage,13+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=HD|Charm Monster,14+CHA|Crushing Despair,14+CHA|Dimension Door,14+CHA
- **KIT:** 1|LE

### Barghest (Greater)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|8
- **BONUS:** STAT|WIS|8
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Bluff|Climb|Concentration|Diplomacy|Disguise|Hide|Intimidate|Jump|Listen|Move Silently|Sense Motive|Spot|Survival|Tumble
- **AUTO:** LANG|Goblin|Infernal|Worg
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Barghest ~ Change Shape|Barghest ~ Feed|Barghest ~ Natural Weapons|Barghest ~ Pass Without Trace|Barghest ~ Skills|Barghest ~ Spell-Like Abilities|Greater Barghest ~ Spell-Like Abilities|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **DR:** 10/Magic
- **MONSTERCLASS:** Outsider:9
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Evil|Extraplanar|Lawful|Shapechanger
- **CR:** 5
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=HD|Blink,13+CHA|Invisibility Sphere|Levitate,12+CHA|Misdirection,12+CHA|Rage,13+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=HD|Bull's Strength (Mass)|Charm Monster,14+CHA|Crushing Despair,14+CHA|Dimension Door,14+CHA|Enlarge Person (Mass)
- **KIT:** 1|LE

### Basilisk

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Basilisk ~ Petrifying Gaze|Basilisk ~ Skills
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:6
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 10,18
- **CR:** 5
- **KIT:** 1|TN

### Basilisk (Abyssal/Greater)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|SmiteGood|1
- **BONUS:** VAR|SmiteGoodDamage|18
- **BONUS:** VAR|ColdResistanceBonus,FireResistanceBonus|10
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Abyssal Greater Basilisk ~ Natural Weapons|Basilisk ~ Petrifying Gaze|Basilisk ~ Skills|Resistance to Cold|Resistance to Fire|Smite Good
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d10
- **DR:** 10/Magic
- **MONSTERCLASS:** Magical Beast:18
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Abyssal Greater Basilisk
- **CR:** 12
- **KIT:** 1|CE

### Behir

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40,Climb,15
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Listen|Spot|Survival
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Behir ~ Breath Weapon|Behir ~ Constrict|Behir ~ Improved Grab|Behir ~ Rake|Behir ~ Skills|Behir ~ Swallow Whole|Immunity to Electricity|Scent|Trip
- **LEGS:** 12
- **HANDS:** 7
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d4
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 13,27
- **CR:** 8

### Beholder (Gauth)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,5,Fly,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Gauth
- **NATURALATTACKS:** Eye Rays (Touch),Ranged.Weapon.Natural,*1,1|Bite,Melee.Weapon.Natural,*1,1d6
- **MONSTERCLASS:** Aberration:6
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 12,18
- **CR:** 6
- **SORTKEY:** Beholder

### Beholder

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,5,Fly,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Beholder
- **NATURALATTACKS:** Eye Rays (Touch),Ranged.Weapon.Natural,*1,1|Bite,Melee.Weapon.Natural,*1,2d4
- **MONSTERCLASS:** Aberration:11
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 16,33
- **CR:** 13
- **SORTKEY:** Beholder

### Belker

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,50
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Listen|Move Silently|Spot
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Belker ~ Skills|Belker ~ Smoke Claws|Belker ~ Smoke Form
- **LEGS:** 0
- **HANDS:** 5
- **NATURALATTACKS:** Wing,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **MONSTERCLASS:** Elemental:7
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 10,21
- **CR:** 6

### Blink Dog

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Sense Motive|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Track
- **AUTO:** LANG|Blink Dog
- **ABILITY:** Special Ability|AUTOMATIC|Blink Dog ~ Blink|Blink Dog ~ Dimension Door|Scent
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 7,12
- **CR:** 2

### Bodak

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Move Silently|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Bodak ~ Death Gaze|Bodak ~ Vulnerability to Sunlight|Immunity to Electricity|Resistance to Acid|Resistance to Fire
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **DR:** 10/Cold Iron
- **MONSTERCLASS:** Undead:9
- **RACETYPE:** Undead
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 13,27
- **CR:** 8
- **KIT:** 1|CE

### Bugbear

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Draconic,Elven,Giant,Gnoll,Orc
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Listen|Move Silently|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light
- **AUTO:** LANG|Common|Goblin
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Javelin|Morningstar|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Bugbear ~ Skills|Scent
- **LEGS:** 2
- **MONSTERCLASS:** Humanoid:3
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Goblinoid
- **LEVELADJUSTMENT:** 1
- **CR:** 2

### Bulette

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40,Burrow,10
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Jump|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Bulette ~ Leap|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 16,27
- **CR:** 7
- **KIT:** 1|TN

### Carrion Crawler

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Climb,15
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-10
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-4
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Carrion Crawler
- **NATURALATTACKS:** Tenatacles,Melee.Weapon.Natural,*8,0|Bite,Melee.Weapon.Natural,*1,1d4
- **MONSTERCLASS:** Aberration:3
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 6,9
- **CR:** 4
- **KIT:** 1|TN

### Centaur

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **LANGBONUS:** Common,Gnome,Halfling
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,CON|4
- **BONUS:** STAT|INT|-2
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-1*(max(0,(STR/2)))
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **MONCSKILL:** Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Elven|Sylvan
- **AUTO:** WEAPONPROF|Longbow|Longsword|TYPE=Simple
- **LEGS:** 4
- **HANDS:** 2
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 2
- **CR:** 3

### Chaos Beast

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX,CON|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Escape Artist|Hide|Jump|Listen|Search|Spot|Survival|Tumble|Use Rope
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Chaos Beast ~ Corporeal Instability|Chaos Beast ~ Immunity to Transformation|Chaos Beast ~ Natural Weapons|Immunity to Critical Hits
- **LEGS:** 0
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.CorporealInstability,*2,1d3
- **SR:** 15
- **MONSTERCLASS:** Outsider:8
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar
- **HITDICEADVANCEMENT:** 12,24
- **CR:** 7
- **KIT:** 1|CN

### Chimera

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** VAR|Maneuverability|2
- **BONUS:** WEAPONPROF=Bite (Lion)|DAMAGE|max(0,STR/2)
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,STR/2)
- **BONUS:** WEAPONPROF=Bite (Lion)|TOHIT|2
- **BONUS:** WEAPONPROF=Gore|TOHIT|2
- **MONCSKILL:** Hide|Listen|Spot
- **AUTO:** LANG|Draconic
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Chimera ~ Breath Weapon|Chimera ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 5
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Bite (Lion),Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8|Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 13,27
- **CR:** 7

### Choker

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Climb,10
- **FACE:** 5
- **REACH:** 10
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON,WIS|2
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Move Silently
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** LANG|Undercommon
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Choker ~ Constrict|Choker ~ Improved Grab|Choker ~ Quickness|Choker ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d3
- **MONSTERCLASS:** Aberration:3
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 6,12
- **CR:** 2

### Chuul

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Swim,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Hide|Listen|Spot|Swim
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Chuul ~ Amphibious|Chuul ~ Constrict|Chuul ~ Improved Grab|Chuul ~ Paralytic Tentacles|Chuul ~ Skills|Immunity to Poison
- **LEGS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6
- **MONSTERCLASS:** Aberration:11
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 16,33
- **CR:** 7

### Cloaker

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Fly,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX,CON|6
- **BONUS:** STAT|INT,WIS,CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **AUTO:** LANG|Undercommon
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Cloaker ~ Engulf|Cloaker ~ Moan|Cloaker ~ Shadow Shift
- **LEGS:** 0
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Aberration:6
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 9,18
- **CR:** 5

### Cockatrice

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** VAR|Maneuverability|2
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Cockatrice ~ Petrification
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Petrification,*1,1d4
- **MONSTERCLASS:** Magical Beast:5
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 8,15
- **CR:** 3
- **KIT:** 1|TN

### Couatl

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Fly,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|9
- **BONUS:** STAT|STR,WIS|8
- **BONUS:** STAT|DEX,INT,CHA|6
- **BONUS:** STAT|CON|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Diplomacy|Jump|Listen|Search|Sense Motive|Spellcraft|Spot|Survival|Tumble|Use Magic Device|TYPE=Knowledge
- **ABILITY:** FEAT|AUTOMATIC|Eschew Materials
- **AUTO:** LANG|Celestial|Common|Draconic|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Couatl ~ Constrict|Couatl ~ Ethereal Jaunt|Couatl ~ Improved Grab|Couatl ~ Poison|Couatl ~ Psionics|Couatl ~ Spells|Couatl ~ Telepathy
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d3
- **MONSTERCLASS:** Outsider:9
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Native
- **HITDICEADVANCEMENT:** 13,27
- **LEVELADJUSTMENT:** 7
- **CR:** 10
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|LG

### Darkmantle

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Fly,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot,Hide|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** VAR|BlindsightRange|90|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Darkmantle ~ Blindsight|Darkmantle ~ Constrict|Darkmantle ~ Darkness|Darkmantle ~ Improved Grab|Darkmantle ~ Skills
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4
- **MONSTERCLASS:** Magical Beast:1
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 3
- **CR:** 1
- **KIT:** 1|TN

### Delver

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Burrow,10
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX,CHA|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT,WIS|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Knowledge (Dungeoneering)|Knowledge (Nature)|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Terran|Undercommon
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Delver ~ Corrosive Slime|Delver ~ Stone Shape|Immunity to Acid
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Acid,*2,1d6
- **MONSTERCLASS:** Aberration:15
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 30,45
- **CR:** 9

### Demon (Babau)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Listen,Move Silently,Search|8|TYPE=Racial
- **BONUS:** STAT|STR,CON|10
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|SneakAttackDice|2
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Climb|Disable Device|Disguise|Escape Artist|Hide|Listen|Move Silently|Open Lock|Search|Sleight of Hand|Survival|Use Rope
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Babau ~ Natural Weapons|Babau ~ Protective Slime|Babau ~ Skills|Babau ~ Sneak Attack|Babau ~ Spell-Like Abilities|Babau ~ Summon Demon
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **SR:** 14
- **DR:** 10/Cold Iron or Good
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Evil|Demon|Tanar'ri
- **HITDICEADVANCEMENT:** 7,14,21
- **CR:** 6
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=7|Darkness,12+CHA|Dispel Magic,13+CHA|See Invisibility,12+CHA|Teleport (Greater/Self Only),17+CHA
- **KIT:** 1|CE

### Demon (Balor)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Fly,90
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|19|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX,INT,WIS|14
- **BONUS:** STAT|CON|20
- **BONUS:** STAT|CHA|16
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival|Use Magic Device|TYPE=Knowledge
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|Longsword|Whip|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Balor ~ Death Throes|Balor ~ Entangle|Balor ~ Flaming Body|Balor ~ Natural Weapons|Balor ~ Skills|Balor ~ Spell-Like Abilities|Balor ~ Summon Demon|Balor ~ True Seeing|Balor ~ Vorpal Sword|Immunity to Fire
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d10
- **SR:** 28
- **DR:** 15/Cold Iron and Good
- **MONSTERCLASS:** Outsider:20
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Demon|Extraplanar|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 30,60
- **CR:** 20
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=20|Blasphemy,17+CHA|Dispel Magic (Greater),16+CHA|Dominate Monster,19+CHA|Insanity,17+CHA|Power Word Stun,18+CHA|Telekinesis,15+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Aura,18+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=20|Fire Storm,18+CHA|Implosion,19+CHA
- **KIT:** 1|CE

### Demon (Bebilith)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40,Climb,20
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX,WIS,CHA|2
- **BONUS:** STAT|CON|16
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Diplomacy|Hide|Jump|Listen|Move Silently|Search|Sense Motive|Spot|Survival
- **AUTO:** LANG|Abyssal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Bebilith ~ Natural Weapons|Bebilith ~ Plane Shift|Bebilith ~ Poison|Bebilith ~ Rend Armor|Bebilith ~ Skills|Bebilith ~ Telepathy|Bebilith ~ Web|Scent
- **LEGS:** 8
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4|Web,Weapon.Natural.Ranged.touch.Entangle,*1,1d0
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Evil
- **HITDICEADVANCEMENT:** 18,36
- **CR:** 10
- **KIT:** 1|CE

### Demon (Dretch)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Hide|Listen|Move Silently|Search|Spot|Survival
- **AUTO:** LANG|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Dretch ~ Natural Weapons|Dretch ~ Spell-Like Abilities|Dretch ~ Summon Demon|Dretch ~ Telepathy
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **DR:** 5/Cold Iron or Good
- **MONSTERCLASS:** Outsider:2
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Demon|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 6
- **LEVELADJUSTMENT:** 2
- **CR:** 2
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=2|Scare,12+CHA|Stinking Cloud,13+CHA
- **KIT:** 1|CE

### Demon (Glabrezu)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|19|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR,CON|20
- **BONUS:** STAT|INT,WIS|6
- **BONUS:** STAT|CHA|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Glabrezu ~ Improved Grab|Glabrezu ~ Natural Weapons|Glabrezu ~ Skills|Glabrezu ~ Spell-Like Abilities|Glabrezu ~ Summon Demon|Glabrezu ~ True Seeing
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Pincer,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **SR:** 21
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Demon|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 18,36
- **CR:** 13
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=14|Chaos Hammer,14+CHA|Confusion,14+CHA|Dispel Magic,13+CHA|Mirror Image,12+CHA|Reverse Gravity,17+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=14|Power Word Stun,18+CHA
- **KIT:** 1|CE

### Demon (Hezrou)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CON|18
- **BONUS:** STAT|INT,WIS|4
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Climb|Concentration|Escape Artist|Hide|Intimidate|Listen|Move Silently|Search|Spellcraft|Spot|Survival|Use Rope
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Hezrou ~ Improved Grab|Hezrou ~ Natural Weapons|Hezrou ~ Skills|Hezrou ~ Spell-Like Abilities|Hezrou ~ Stench|Hezrou ~ Summon Demon
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8
- **SR:** 19
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:10
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Demon|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 15,30
- **LEVELADJUSTMENT:** 9
- **CR:** 11
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=13|Chaos Hammer,14+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=13|Blasphemy,17+CHA|Gaseous Form,13+CHA
- **KIT:** 1|CE

### Demon (Marilith)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|16|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR,CON|18
- **BONUS:** STAT|DEX,INT,WIS|8
- **BONUS:** STAT|CHA|14
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival|Use Magic Device
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|Longsword|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Marilith ~ Constrict|Marilith ~ Feats|Marilith ~ Improved Grab|Marilith ~ Natural Weapons|Marilith ~ Skills|Marilith ~ Spell-Like Abilities|Marilith ~ Summon Demon|Marilith ~ True Seeing
- **LEGS:** 0
- **HANDS:** 7
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,4d6|Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*6,1d8
- **SR:** 25
- **DR:** 10/Good and Cold Iron
- **MONSTERCLASS:** Outsider:16
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Demon|Extraplanar|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 20,48
- **CR:** 17
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=16|Align Weapon,12+CHA|Blade Barrier,16+CHA|Magic Weapon,11+CHA|Polymorph,14+CHA|Project Image,16+CHA|See Invisibility,12+CHA|Telekinesis,15+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Aura,18+CHA
- **KIT:** 1|CE

### Demon (Nalfeshnee)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Fly,40
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|18|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|16
- **BONUS:** STAT|INT,WIS|12
- **BONUS:** STAT|CHA|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Hide|Intimidate|Knowledge (Arcana)|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival|Use Magic Device
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Nalfeshnee ~ Natural Weapons|Nalfeshnee ~ Skills|Nalfeshnee ~ Smite|Nalfeshnee ~ Spell-Like Abilities|Nalfeshnee ~ Summon Demon|Nalfeshnee ~ True Seeing
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8
- **SR:** 22
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:14
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Demon|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 20,42
- **CR:** 14
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Call Lightning,13+CHA|Dispel Magic (Greater),16+CHA|Feeblemind,15+CHA|Slow,13+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Aura,18+CHA
- **KIT:** 1|CE

### Demon (Quasit)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,20,Fly,50
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Hide|Intimidate|Listen|Move Silently|Search|Spellcraft|Spot|TYPE=Knowledge
- **AUTO:** LANG|Abyssal|Common
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Fast Healing 2|Immunity to Poison|Quasit ~ Alternate Form|Quasit ~ Natural Weapons|Quasit ~ Poison|Quasit ~ Spell-Like Abilities|Resistance to Fire
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Poison,*2,1d3|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **DR:** 5/Cold Iron or Good
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Demon|Extraplanar|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 6
- **CR:** 2
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=6|Detect Good,11+CHA|Detect Magic,10+CHA|Invisibility (Self Only),12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Cause Fear (Radius),11+CHA
- **KIT:** 1|CE

### Demon (Retriever)

- **SIZE:** H
- **MOVE:** Walk,50
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **ABILITY:** Special Ability|AUTOMATIC|Fast Healing 5|Retriever ~ Eye Rays|Retriever ~ Find Target|Retriever ~ Improved Grab
- **LEGS:** 4
- **HANDS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*4,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **NATURALATTACKS:** Eye Ray,Weapon.Natural.Ranged.Touch,*1,1d0
- **MONSTERCLASS:** Construct (Mindless):10
- **RACETYPE:** Construct
- **RACESUBTYPE:** Extraplanar|Mindless
- **HITDICEADVANCEMENT:** 15,30
- **CR:** 11
- **KIT:** 1|CE

### Demon (Succubus)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR,DEX,CON|2
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|16
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|3
- **BONUS:** VAR|EnergyDrainLevels|1
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Escape Artist|Hide|Intimidate|Listen|Move Silently|Search|Spot|Survival|Use Rope|TYPE=Knowledge
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Succubus ~ Energy Drain|Succubus ~ Natural Weapons|Succubus ~ Skills|Succubus ~ Spell-Like Abilities|Succubus ~ Summon Demon|Succubus ~ Tongues
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **SR:** 18
- **DR:** 10/Cold Iron or Good
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Demon|Extraplanar|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 12
- **LEVELADJUSTMENT:** 6
- **CR:** 7
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Charm Monster,14+CHA|Detect Good,11+CHA|Detect Thoughts,12+CHA|Ethereal Jaunt,17+CHA|Polymorph,14+CHA|Suggestion,13+CHA|Teleport (Greater/Self Only),17+CHA
- **KIT:** 1|CE

### Demon (Vrock)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,50
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX,INT|4
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|WIS,CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Concentration|Diplomacy|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Abyssal|Celestial|Draconic
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Vrock ~ Dance of Ruin|Vrock ~ Natural Weapons|Vrock ~ Skills|Vrock ~ Spell-Like Abilities|Vrock ~ Spores|Vrock ~ Stunning Screech|Vrock ~ Summon Demon
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8|Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **SR:** 17
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:10
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Demon|Extraplanar|Evil|Tanar'ri
- **HITDICEADVANCEMENT:** 14,30
- **LEVELADJUSTMENT:** 8
- **CR:** 9
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Mirror Image,12+CHA|Telekinesis,15+CHA|Teleport (Greater/Self Only),17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=12|Heroism,13+CHA
- **KIT:** 1|CE

### Derro

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|-6
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|SneakAttackDice|1
- **MONCSKILL:** Bluff|Hide|Listen|Move Silently
- **AUTO:** ARMORPROF|ARMORTYPE=Light
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Crossbow (Repeating Light)|Sword (Short)|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Derro ~ Madness|Derro ~ Poison Use|Derro ~ Skills|Derro ~ Sneak Attack|Derro ~ Spell-Like Abilities|Derro ~ Vulnerability to Sunlight
- **LEGS:** 2
- **SR:** 15
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Monstrous Humanoid
- **CR:** 3
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=3|Darkness,12+CHA|Ghost Sound,10+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=3|Daze,10+CHA|Sound Burst,12+CHA

### Destrachan

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen|10|TYPE=Racial
- **BONUS:** STAT|STR,WIS|8
- **BONUS:** STAT|DEX,INT,CHA|2
- **BONUS:** STAT|CON|6
- **BONUS:** VAR|BlindsightRange|100|TYPE=Base
- **MONCSKILL:** Hide|Listen|Move Silently|Survival
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Destrachan ~ Blindsight|Destrachan ~ Destructive Harmonics|Destrachan ~ Immunities|Destrachan ~ Protection From Sonics|Destrachan ~ Skills
- **LEGS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Aberration:8
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 16,24
- **CR:** 8

### Devil (Barbed (Hamatula))

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX,CON|12
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **MONCSKILL:** Concentration|Diplomacy|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Barbed Devil ~ Barbed Defense|Barbed Devil ~ Fear|Barbed Devil ~ Impale|Barbed Devil ~ Improved Grab|Barbed Devil ~ Natural Weapons|Barbed Devil ~ Spell-Like Abilities|Barbed Devil ~ Summon Devil
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Fear,*2,2d8
- **SR:** 23
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Devil|Extraplanar|Evil|Lawful|Baatezu
- **HITDICEADVANCEMENT:** 24,36
- **CR:** 11
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Hold Person,12+CHA|Major Image,13+CHA|Scorching Ray (2 rays only),12+CHA|Teleport (Greater/Self Only),17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=12|Order's Wrath,14+CHA|Unholy Blight,14+CHA
- **KIT:** 1|LE

### Devil (Bearded (Barbazu))

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **MONCSKILL:** Climb|Diplomacy|Hide|Listen|Move Silently|Sense Motive|Spot
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Glaive|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Bearded Devil ~ Battle Frenzy|Bearded Devil ~ Beard|Bearded Devil ~ Infernal Wound|Bearded Devil ~ Natural Weapons|Bearded Devil ~ Spell-Like Abilities|Bearded Devil ~ Summon Devil
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **SR:** 17
- **DR:** 5/Silver or Good
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Devil|Extraplanar|Evil|Lawful|Baatezu
- **HITDICEADVANCEMENT:** 9,18
- **LEVELADJUSTMENT:** 6
- **CR:** 5
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Teleport (Greater/Self Only),17+CHA
- **KIT:** 1|LE

### Devil (Bone (Osyluth))

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX,CON|10
- **BONUS:** STAT|INT,WIS,CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FearAuraRadius|5
- **BONUS:** VAR|FearAuraDC|17
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Bone Devil ~ Fear Aura|Bone Devil ~ Natural Weapons|Bone Devil ~ Poison|Bone Devil ~ Spell-Like Abilities|Bone Devil ~ Summon Devil
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,3d4
- **SR:** 21
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:10
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Devil|Extraplanar|Evil|Lawful|Baatezu
- **HITDICEADVANCEMENT:** 20,30
- **CR:** 9
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Dimensional Anchor,14+CHA|Fly,13+CHA|Invisibility (Self Only),12+CHA|Major Image,13+CHA|Teleport (Greater/Self Only),17+CHA|Wall of Ice,14+CHA
- **KIT:** 1|LE

### Devil (Chain (Kyton))

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Craft (Armorsmithing),Craft (Blacksmithing),Craft (Metalworking),Craft (Weaponsmithing)|8|TYPE=Racial
- **BONUS:** STAT|STR,DEX,CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Craft (Blacksmithing)|Escape Artist|Intimidate|Listen|Spot|Use Rope
- **AUTO:** LANG|Common|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Chain Devil ~ Dancing Chains|Chain Devil ~ Natural Weapons|Chain Devil ~ Regeneration|Chain Devil ~ Skills|Chain Devil ~ Unnerving Gaze|Immunity to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Chain,Weapon.Natural.Melee.Finesseable.Reach.Bludgeoning.Piercing,*2,2d4
- **SR:** 18
- **DR:** 5/Silver or Good
- **MONSTERCLASS:** Outsider:8
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Evil|Lawful
- **HITDICEADVANCEMENT:** 16
- **LEVELADJUSTMENT:** 6
- **CR:** 6
- **KIT:** 1|LE

### Devil (Erinyes)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX,CON,CHA|10
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Hide|Listen|Move Silently|Search|Sense Motive|Spot|Survival|Use Rope|TYPE=Knowledge
- **ABILITY:** FEAT|AUTOMATIC|Dodge|Mobility
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Longsword|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Erinyes ~ Entangle|Erinyes ~ Natural Weapons|Erinyes ~ Spell-Like Abilities|Erinyes ~ Summon Devil|Erinyes ~ True Seeing
- **LEGS:** 2
- **NATURALATTACKS:** Rope,Weapon.Natural.Ranged.Entangle,*1,1d0
- **SR:** 20
- **DR:** 5/Good
- **MONSTERCLASS:** Outsider:9
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Evil|Lawful
- **HITDICEADVANCEMENT:** 18
- **LEVELADJUSTMENT:** 7
- **CR:** 8
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Charm Monster,14+CHA|Minor Image,14+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Blight,14+CHA
- **KIT:** 1|LE

### Devil (Hellcat (Bezekira))

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Balance|Climb|Hide|Jump|Listen|Move Silently|Spot|Swim
- **AUTO:** LANG|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Hellcat ~ Improved Grab|Hellcat ~ Invisible In Light|Hellcat ~ Natural Weapons|Hellcat ~ Pounce|Hellcat ~ Rake|Hellcat ~ Skills|Resistance to Fire|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **SR:** 19
- **DR:** 5/Good
- **MONSTERCLASS:** Outsider:8
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Evil|Lawful
- **HITDICEADVANCEMENT:** 10,24
- **CR:** 7
- **KIT:** 1|LE

### Devil (Horned (Cornugon))

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Fly,50
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|19|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX,CON|14
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|8
- **BONUS:** STAT|CHA|12
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FearAuraRadius|5
- **BONUS:** VAR|FearAuraDC|10+(TL/2)+CHA
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Climb|Concentration|Diplomacy|Disguise|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spot|Survival
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Chain (Spiked)|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Horned Devil ~ Fear Aura|Horned Devil ~ Infernal Wound|Horned Devil ~ Natural Weapons|Horned Devil ~ Regeneration|Horned Devil ~ Spell-Like Abilities|Horned Devil ~ Stun|Horned Devil ~ Summon Devil
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning.InfernalWound,*1,2d6
- **SR:** 28
- **DR:** 10/Good and Silver
- **MONSTERCLASS:** Outsider:15
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Devil|Extraplanar|Evil|Lawful|Baatezu
- **HITDICEADVANCEMENT:** 20,45
- **CR:** 16
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=15|Dispel Chaos,15+CHA|Dispel Good,15+CHA|Magic Circle against Good,13+CHA|Persistent Image,15+CHA|Teleport (Greater/Self Only),17+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=15|Fireball,13+CHA|Lightning Bolt,13+CHA
- **KIT:** 1|LE

### Devil (Ice (Gelugon))

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|18|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON,INT,WIS|12
- **BONUS:** STAT|DEX,CHA|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FearAuraRadius|10
- **BONUS:** VAR|FearAuraDC|10+(TL/2)+CHA
- **MONCSKILL:** Bluff|Climb|Concentration|Diplomacy|Disguise|Intimidate|Jump|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Spear|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Ice Devil ~ Fear Aura|Ice Devil ~ Natural Weapons|Ice Devil ~ Regeneration|Ice Devil ~ Slow|Ice Devil ~ Spell-Like Abilities|Ice Devil ~ Summon Devil
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d10|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning.Slow,*1,3d6
- **SR:** 25
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:14
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Devil|Extraplanar|Evil|Lawful|Baatezu
- **HITDICEADVANCEMENT:** 28,42
- **CR:** 13
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=13|Cone of Cold,15+CHA|Fly,13+CHA|Ice Storm,14+CHA|Persistent Image,15+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Aura,18+CHA|Wall of Ice,14+CHA
- **KIT:** 1|LE

### Devil (Imp)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,20,Fly,50
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|FireResistanceBonus|5
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Sting|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Diplomacy|Hide|Listen|Move Silently|Search|Spellcraft|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Fast Healing 2|Imp ~ Alternate Form|Imp ~ Natural Weapons|Imp ~ Poison|Imp ~ Spell-Like Abilities|Resistance to Fire
- **LEGS:** 2
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d4
- **DR:** 5/Good or Silver
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Evil|Lawful
- **HITDICEADVANCEMENT:** 6
- **CR:** 2
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=6|Detect Good,11+CHA|Detect Magic,10+CHA|Invisibility (Self Only),12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Suggestion,13+CHA
- **KIT:** 1|LE

### Devil (Lemure)

- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILLPOOL|CLASS=Outsider;LEVEL=1|-8
- **BONUS:** SKILLPOOL|CLASS=Outsider;LEVEL=2|-32
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Lemure ~ Mindless|Lemure ~ Natural Weapons
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **DR:** 5/Good or Silver
- **MONSTERCLASS:** Outsider:2
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Evil|Lawful|Devil|Mindless|Baatezu
- **HITDICEADVANCEMENT:** 6
- **CR:** 1
- **KIT:** 1|LE

### Devil (Pit Fiend)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Fly,60
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|23|TYPE=NaturalArmor
- **BONUS:** STAT|STR|26
- **BONUS:** STAT|DEX,CON,INT,WIS,CHA|16
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FearAuraRadius|20
- **BONUS:** VAR|FearAuraDC|10+(TL/2)+CHA
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Balance|Bluff|Climb|Concentration|Diplomacy|Disguise|Hide|Intimidate|Jump|Knowledge (Arcana)|Knowledge (Nature)|Knowledge (Religion)|Knowledge (The Planes)|Listen|Move Silently|Search|Spellcraft|Spot|Survival|Tumble
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Pit Fiend ~ Constrict|Pit Fiend ~ Fear Aura|Pit Fiend ~ Improved Grab|Pit Fiend ~ Poison|Pit Fiend ~ Regeneration|Pit Fiend ~ Spell-Like Abilities|Pit Fiend ~ Summon Devil
- **LEGS:** 2
- **HANDS:** 6
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d8|Wing,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison.Disease,*1,4d6|Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8
- **SR:** 32
- **DR:** 15/Good and Silver
- **MONSTERCLASS:** Outsider:18
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Devil|Extraplanar|Evil|Lawful|Baatezu
- **HITDICEADVANCEMENT:** 36,54
- **CR:** 20
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=18|Blasphemy,17+CHA|Create Undead,16+CHA|Dispel Magic (Greater),16+CHA|Fireball,13+CHA|Hold Monster (Mass),19+CHA|Invisibility,12+CHA|Magic Circle against Good,13+CHA|Persistent Image,15+CHA|Power Word Stun,18+CHA|Teleport (Greater/Self Only),17+CHA|Unholy Aura,18+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=18|Meteor Swarm,19+CHA
- **KIT:** 1|LE

### Devourer

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|INT,WIS,CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|EnergyDrainLevels|1
- **MONCSKILL:** Climb|Concentration|Diplomacy|Jump|Listen|Move Silently|Search|Sense Motive|Spot|Survival
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Devourer ~ Energy Drain|Devourer ~ Spell Deflection|Devourer ~ Spell-Like Abilities|Devourer ~ Trap Essence
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **SR:** 21
- **MONSTERCLASS:** Undead:12
- **RACETYPE:** Undead
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 24,36
- **CR:** 11
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=18|Confusion,14+CHA|Control Undead,17+CHA|Ghoul Touch,12+CHA|Planar Ally (Lesser),14+CHA|Ray of Enfeeblement,11+CHA|Spectral Hand,12+CHA|Suggestion,13+CHA|True Seeing,16+CHA
- **KIT:** 1|NE

### Digester

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Jump|4|TYPE=Racial
- **BONUS:** STAT|STR,CON|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Claw|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Jump|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Digester ~ Acid Spray|Digester ~ Skills|Immunity to Acid|Scent
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:8
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 12,24
- **CR:** 6
- **KIT:** 1|TN

### Dinosaur (Deinonychus)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Jump,Listen,Spot,Survival|8|TYPE=Racial
- **BONUS:** STAT|STR,CON|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Hide|Jump|Listen|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Deinonychus ~ Pounce|Deinonychus ~ Skills|Scent
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d4
- **MONSTERCLASS:** Animal:4
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 8
- **CR:** 3
- **KIT:** 1|TN

### Dinosaur (Elasmosaurus)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Swim,50
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Elasmosaurus ~ Skills|Scent
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **MONSTERCLASS:** Animal:10
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 20,30
- **CR:** 7
- **KIT:** 1|TN

### Dinosaur (Megaraptor)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,60
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Jump,Listen,Spot,Survival|8|TYPE=Racial
- **BONUS:** STAT|STR,CON|10
- **BONUS:** STAT|DEX,WIS|4
- **BONUS:** STAT|INT|-8
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Hide|Jump|Listen|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Megaraptor ~ Pounce|Megaraptor ~ Skills|Scent
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Animal:8
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 16,24
- **CR:** 6
- **KIT:** 1|TN

### Dinosaur (Triceratops)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Triceratops ~ Powerful Charge|Triceratops ~ Trample
- **LEGS:** 4
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,2d8
- **MONSTERCLASS:** Animal:16
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 32,48
- **CR:** 9
- **KIT:** 1|TN

### Dinosaur (Tyrannosaurus)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Tyrannosaurus ~ Improved Grab|Tyrannosaurus ~ Skills|Tyrannosaurus ~ Swallow Whole
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,3d6
- **MONSTERCLASS:** Animal:18
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 36,54
- **CR:** 8
- **KIT:** 1|TN

### Dire Animal (Dire Ape)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Climb,15
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX,CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Climb|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Dire Ape ~ Rend|Dire Ape ~ Skills|Scent
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal (Will):5
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 15
- **CR:** 3
- **KIT:** 1|TN

### Dire Animal (Dire Badger)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Burrow,10
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Track
- **ABILITY:** Special Ability|AUTOMATIC|Dire Badger ~ Rage|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal (Will):3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 3,9
- **CR:** 2
- **KIT:** 1|TN

### Dire Animal (Dire Bat)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Fly,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR,CON|6
- **BONUS:** STAT|DEX|12
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|BlindsenseRange|40|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Dire Bat ~ Blindsense|Dire Bat ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal (Will):4
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 12
- **CR:** 2
- **KIT:** 1|TN

### Dire Animal (Dire Bear)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-8
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Listen|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Dire Bear ~ Improved Grab|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **MONSTERCLASS:** Animal (Will):12
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 16,36
- **CR:** 7
- **KIT:** 1|TN

### Dire Animal (Dire Boar)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Dire Boar ~ Ferocity|Scent
- **LEGS:** 4
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Animal (Will):7
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 16,21
- **CR:** 4
- **KIT:** 1|TN

### Dire Animal (Dire Lion)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Dire Lion ~ Improved Grab|Dire Lion ~ Pounce|Dire Lion ~ Rake|Dire Lion ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal (Will):8
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 16,24
- **CR:** 5
- **KIT:** 1|TN

### Dire Animal (Dire Rat)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,40,Climb,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Swim|8|TYPE=Racial
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON,WIS|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Listen|Move Silently|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Dire Rat ~ Disease|Dire Rat ~ Skills|Scent
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Disease,*1,1d4
- **MONSTERCLASS:** Animal (Will):1
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 3,6
- **CR:** 1/3
- **KIT:** 1|TN

### Dire Animal (Dire Shark)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Swim,60
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|KeenScentRange|180|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Dire Shark ~ Improved Grab|Dire Shark ~ Keen Scent|Dire Shark ~ Skills|Dire Shark ~ Swallow Whole
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d10
- **MONSTERCLASS:** Animal (Will):18
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 32,54
- **CR:** 9
- **KIT:** 1|TN

### Dire Animal (Dire Tiger)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Hide|Jump|Listen|Move Silently|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Dire Tiger ~ Improved Grab|Dire Tiger ~ Pounce|Dire Tiger ~ Rake|Dire Tiger ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d4
- **MONSTERCLASS:** Animal (Will):16
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 32,48
- **CR:** 8
- **KIT:** 1|TN

### Dire Animal (Dire Weasel)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Dire Weasel ~ Attach|Dire Weasel ~ Blood Drain|Scent
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal (Will):3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 6,9
- **CR:** 2
- **KIT:** 1|TN

### Dire Animal (Dire Wolf)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Listen,Move Silently,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Track
- **ABILITY:** Special Ability|AUTOMATIC|Dire Wolf ~ Skills|Dire Wolf ~ Trip|Scent
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal (Will):6
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 18
- **CR:** 3
- **KIT:** 1|TN

### Dire Animal (Dire Wolverine)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Climb,10
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Climb|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Track
- **ABILITY:** Special Ability|AUTOMATIC|Dire Wolverine ~ Rage|Dire Wolverine ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal (Will):5
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 15
- **CR:** 4
- **KIT:** 1|TN

### Displacer Beast

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** WEAPONPROF=Tentacles|REACH|5
- **AUTO:** LANG|Common
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Displacer Beast
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **NATURALATTACKS:** Tentacles,Natural.Melee.Weapon,*2,1d6|Bite,Natural.Melee.Weapon,*1,1d8
- **MONSTERCLASS:** Magical Beast:6
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 9,18
- **LEVELADJUSTMENT:** 4
- **CR:** 4

### Displacer Beast Pack Lord

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** WEAPONPROF=Tentacles|REACH|5
- **AUTO:** LANG|Common
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Displacer Beast
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **NATURALATTACKS:** Tentacles,Natural.Melee.Weapon,*2,1d8|Bite,Natural.Melee.Weapon,*1,2d6
- **MONSTERCLASS:** Magical Beast:18
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 9,18
- **LEVELADJUSTMENT:** 4
- **CR:** 12

### Doppelganger

- **FAVCLASS:** Rogue
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Auran,Dwarven,Elven,Giant,Gnome,Halfling,Terran
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Bluff,Disguise|4|TYPE=Racial
- **BONUS:** STAT|STR,DEX,CON,INT,CHA|2
- **BONUS:** STAT|WIS|4
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Intimidate|Listen|Sense Motive|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Doppelganger ~ Change Shape|Doppelganger ~ Detect Thoughts|Doppelganger ~ Skills|Immunity to Charm Effects|Immunity to Sleep
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Shapechanger
- **LEVELADJUSTMENT:** 4
- **CR:** 3

### Black Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer|-1
- **BONUS:** PCLEVEL|Sorcerer|(DragonAgeCategory-5)*2
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spot|Swim|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Black Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **MONSTERCLASS:** Dragon:4
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Water
- **CR:** 3
- **ADD:** SPELLCASTER|Sorcerer
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Chromatic

### Blue Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|-1
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|(DragonAgeCategory-4)*2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Escape Artist|Hide|Intimidate|Listen|Search|Sense Motive|Spellcraft|Spot|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Blue Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **DEFINE:** AirDomainAllowed|0
- **DEFINE:** EvilDomainAllowed|0
- **DEFINE:** LawDomainAllowed|0
- **BONUS:** VAR|AirDomainAllowed|1
- **BONUS:** VAR|EvilDomainAllowed|1
- **BONUS:** VAR|LawDomainAllowed|1
- **MONSTERCLASS:** Dragon:6
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Earth
- **CR:** 3
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Chromatic

### Green Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer|-1
- **BONUS:** PCLEVEL|Sorcerer|(DragonAgeCategory-4)*2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Escape Artist|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spot|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Green Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **MONSTERCLASS:** Dragon:5
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Air
- **CR:** 3
- **ADD:** SPELLCASTER|Sorcerer
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Chromatic

### Red Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|-1
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|(DragonAgeCategory-3)*2
- **MONCSKILL:** Appraise|Bluff|Concentration|Diplomacy|Escape Artist|Intimidate|Jump|Listen|Search|Sense Motive|Spot|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Red Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **DEFINE:** ChaosDomainAllowed|0
- **DEFINE:** EvilDomainAllowed|0
- **DEFINE:** FireDomainAllowed|0
- **BONUS:** VAR|ChaosDomainAllowed|1
- **BONUS:** VAR|EvilDomainAllowed|1
- **BONUS:** VAR|FireDomainAllowed|1
- **MONSTERCLASS:** Dragon:7
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Fire
- **CR:** 4
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Chromatic

### White Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer|-1
- **BONUS:** PCLEVEL|Sorcerer|(DragonAgeCategory-6)*2
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Hide|Intimidate|Listen|Move Silently|Search|Sense Motive|Spot|Swim|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ White Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **MONSTERCLASS:** Dragon:3
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Cold
- **CR:** 2
- **ADD:** SPELLCASTER|Sorcerer
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Chromatic

### Brass Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|-1
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|(DragonAgeCategory-3)*2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Escape Artist|Gather Information|Intimidate|Listen|Search|Sense Motive|Spot|Survival|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Brass Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **DEFINE:** ChaosDomainAllowed|0
- **DEFINE:** KnowledgeDomainAllowed|0
- **BONUS:** VAR|ChaosDomainAllowed|1
- **BONUS:** VAR|KnowledgeDomainAllowed|1
- **MONSTERCLASS:** Dragon:4
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Fire
- **CR:** 3
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Metallic

### Bronze Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|-1
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|(DragonAgeCategory-3)*2
- **MONCSKILL:** Concentration|Diplomacy|Disguise|Escape Artist|Intimidate|Listen|Search|Sense Motive|Spot|Survival|Swim|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Bronze Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **DEFINE:** AnimalDomainAllowed|0
- **DEFINE:** LawDomainAllowed|0
- **DEFINE:** WaterDomainAllowed|0
- **BONUS:** VAR|AnimalDomainAllowed|1
- **BONUS:** VAR|LawDomainAllowed|1
- **BONUS:** VAR|WaterDomainAllowed|1
- **MONSTERCLASS:** Dragon:6
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Water
- **CR:** 3
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Metallic

### Copper Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|-1
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|(DragonAgeCategory-3)*2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Escape Artist|Hide|Intimidate|Jump|Listen|Search|Sense Motive|Spot|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Copper Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **DEFINE:** ChaosDomainAllowed|0
- **DEFINE:** EarthDomainAllowed|0
- **DEFINE:** TrickeryDomainAllowed|0
- **BONUS:** VAR|ChaosDomainAllowed|1
- **BONUS:** VAR|EarthDomainAllowed|1
- **BONUS:** VAR|TrickeryDomainAllowed|1
- **MONSTERCLASS:** Dragon:5
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Earth
- **CR:** 3
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Metallic

### Gold Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|-1
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|(DragonAgeCategory-3)*2
- **MONCSKILL:** Concentration|Diplomacy|Disguise|Escape Artist|Heal|Intimidate|Listen|Search|Sense Motive|Spot|Swim|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Gold Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **DEFINE:** LuckDomainAllowed|0
- **DEFINE:** LawDomainAllowed|0
- **DEFINE:** GoodDomainAllowed|0
- **BONUS:** VAR|LuckDomainAllowed|1
- **BONUS:** VAR|LawDomainAllowed|1
- **BONUS:** VAR|GoodDomainAllowed|1
- **MONSTERCLASS:** Dragon:8
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Fire
- **CR:** 5
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Metallic

### Silver Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,30
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|-1
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|(DragonAgeCategory-3)*2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Escape Artist|Intimidate|Jump|Listen|Search|Sense Motive|Spot|Use Magic Device|TYPE=Knowledge
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Silver Dragon
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 4
- **DEFINE:** AirDomainAllowed|0
- **DEFINE:** GoodDomainAllowed|0
- **DEFINE:** LawDomainAllowed|0
- **DEFINE:** SunDomainAllowed|0
- **BONUS:** VAR|AirDomainAllowed|1
- **BONUS:** VAR|GoodDomainAllowed|1
- **BONUS:** VAR|LawDomainAllowed|1
- **BONUS:** VAR|SunDomainAllowed|1
- **MONSTERCLASS:** Dragon:7
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Cold
- **CR:** 4
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)
- **KIT:** 1|Dragon Default Stat Array
- **SORTKEY:** Dragon_Metallic

### Dragon Turtle

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Swim,30
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|17|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT,WIS,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Diplomacy|Hide|Intimidate|Listen|Search|Sense Motive|Spot|Survival|Swim
- **AUTO:** LANG|Aquan|Common|Draconic
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Dragon Turtle ~ Breath Weapon|Dragon Turtle ~ Capsize|Dragon Turtle ~ Skills|Immunity to Fire|Immunity to Paralysis|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d8
- **MONSTERCLASS:** Dragon:12
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 24,36
- **CR:** 9

### Dragonne

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Fly,30
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Draconic
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Dragonne ~ Pounce|Dragonne ~ Roar|Dragonne ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 12,27
- **CR:** 7

### Drider

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Climb,15
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR,DEX,INT|4
- **BONUS:** STAT|CON,WIS,CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Concentration|Hide|Listen|Move Silently|Spot
- **AUTO:** LANG|Common|Elven|Undercommon
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Drider ~ Poison|Drider ~ Skills|Drider ~ Spell-Like Abilities|Drider ~ Spells
- **ABILITY:** Internal|AUTOMATIC|Race Size ~ Long
- **LEGS:** 8
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d4
- **SR:** 17
- **MONSTERCLASS:** Aberration:6
- **RACETYPE:** Aberration
- **LEVELADJUSTMENT:** 4
- **CR:** 7
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Clairaudience/Clairvoyance,13+CHA|Dancing Lights,10+CHA|Darkness,12+CHA|Detect Good,11+CHA|Detect Law,11+CHA|Detect Magic,10+CHA|Dispel Magic,13+CHA|Faerie Fire,11+CHA|Levitate,12+CHA|Suggestion,13+CHA
- **KIT:** 1|CE

### Dryad

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX,CHA|8
- **BONUS:** STAT|INT,WIS|4
- **MONCSKILL:** Escape Artist|Handle Animal|Hide|Knowledge (Nature)|Listen|Move Silently|Ride|Spot|Survival|Use Rope
- **AUTO:** LANG|Common|Elven|Sylvan
- **AUTO:** WEAPONPROF|Dagger|Longbow|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Dryad ~ Spell-Like Abilities|Dryad ~ Tree Dependent|Dryad ~ Wild Empathy
- **LEGS:** 2
- **DR:** 5/Cold Iron
- **MONSTERCLASS:** Fey:4
- **RACETYPE:** Fey
- **CR:** 3
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=6|Entangle,11+WIS|Speak with Plants,13+WIS|Tree Shape,12+WIS
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Suggestion,13+WIS
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=6|Charm Person,11+WIS|Deep Slumber,13+WIS|Tree Stride,15+CHA

### Eagle (Giant)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Fly,80
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|4
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Knowledge (Nature)|Listen|Sense Motive|Spot|Survival
- **AUTO:** LANG|Auran|Common
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Giant Eagle ~ Evasion|Giant Eagle ~ Skills
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 8,12
- **CR:** 3

### Eladrin (Bralani)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Fly,100
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Handle Animal|Hide|Jump|Listen|Move Silently|Ride|Sense Motive|Spot|Tumble|Use Rope
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Scimitar|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Bralani ~ Alternate Form|Bralani ~ Natural Weapons|Bralani ~ Spell-Like Abilities|Bralani ~ Tongues|Bralani ~ Whirlwind Blast|Immunity to Electricity|Immunity to Petrification|Resistance to Cold|Resistance to Fire
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **SR:** 17
- **DR:** 10/Cold Iron or Evil
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Good
- **HITDICEADVANCEMENT:** 12,18
- **LEVELADJUSTMENT:** 5
- **CR:** 6
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=6|Blur,12+CHA|Charm Person,11+CHA|Gust of Wind,12+CHA|Mirror Image,12+CHA|Wind Wall,13+CHA
- **SPELLS:** Innate|TIMES=2|CASTERLEVEL=6|Cure Serious Wounds,13+CHA|Lightning Bolt,13+CHA
- **KIT:** 1|CG

### Eladrin (Ghaele)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50,Fly,150
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Cleric|13
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT,WIS|6
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Handle Animal|Hide|Listen|Move Silently|Ride|Sense Motive|Spot|Use Rope|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|Greatsword|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Ghaele ~ Alternate Form|Ghaele ~ Gaze|Ghaele ~ Light Ray|Ghaele ~ Natural Weapons|Ghaele ~ Protective Aura|Ghaele ~ Spell-Like Abilities|Ghaele ~ Spells|Ghaele ~ Tongues|Immunity to Electricity|Immunity to Petrification|Resistance to Cold|Resistance to Fire
- **LEGS:** 2
- **NATURALATTACKS:** Light Ray,Weapon.Natural.Ranged.Touch.Piercing,*2,2d12
- **SR:** 28
- **DR:** 10/Evil and Cold Iron
- **MONSTERCLASS:** Outsider:10
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Good
- **HITDICEADVANCEMENT:** 15,30
- **CR:** 13
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Aid,12+CHA|Charm Monster,14+CHA|Color Spray,11+CHA|Comprehend Languages,11+CHA|Continual Flame,13+CHA|Cure Light Wounds,11+CHA|Dancing Lights,10+CHA|Detect Evil,11+CHA|Detect Thoughts,12+CHA|Disguise Self,11+CHA|Dispel Magic,13+CHA|Hold Monster,15+CHA|Invisibility (Greater/Self Only),14+CHA|Major Image,13+CHA|See Invisibility,13+CHA|Teleport (Greater/Self Only),17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=12|Chain Lightning,16+CHA|Prismatic Spray,17+CHA|Wall of Force,15+CHA
- **ADD:** SPELLCASTER|Cleric
- **KIT:** 1|CG

### Elemental (Air Small)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Fly,100
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Air Elemental ~ Air Mastery|Air Elemental ~ Whirlwind
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4
- **MONSTERCLASS:** Elemental:2
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 3
- **CR:** 1

### Elemental (Air Medium)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Fly,100
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Air Elemental ~ Air Mastery|Air Elemental ~ Whirlwind
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Elemental:4
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 7
- **CR:** 3

### Elemental (Air Large)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Fly,100
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|14
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Air Elemental ~ Air Mastery|Air Elemental ~ Whirlwind
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:8
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 15
- **CR:** 5

### Elemental (Air Huge)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Fly,100
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|8
- **BONUS:** STAT|DEX|18
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Air Elemental ~ Air Mastery|Air Elemental ~ Whirlwind
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:16
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 20
- **CR:** 7

### Elemental (Air Greater)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Fly,100
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|20
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Air Elemental ~ Air Mastery|Air Elemental ~ Whirlwind
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:21
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 23
- **CR:** 9

### Elemental (Air Elder)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Fly,100
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|22
- **BONUS:** STAT|CON|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Auran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Air Elemental ~ Air Mastery|Air Elemental ~ Whirlwind
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:24
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 48
- **CR:** 11

### Elemental (Earth Small)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Earth Elemental ~ Earth Glide|Earth Elemental ~ Earth Mastery|Earth Elemental ~ Push
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Elemental:2
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Earth|Extraplanar
- **HITDICEADVANCEMENT:** 3
- **CR:** 1

### Elemental (Earth Medium)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Earth Elemental ~ Earth Glide|Earth Elemental ~ Earth Mastery|Earth Elemental ~ Push
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **MONSTERCLASS:** Elemental:4
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Earth|Extraplanar
- **HITDICEADVANCEMENT:** 7
- **CR:** 3

### Elemental (Earth Large)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Earth Elemental ~ Earth Glide|Earth Elemental ~ Earth Mastery|Earth Elemental ~ Push
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:8
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Earth|Extraplanar
- **HITDICEADVANCEMENT:** 15
- **CR:** 5

### Elemental (Earth Huge)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Earth Elemental ~ Earth Glide|Earth Elemental ~ Earth Mastery|Earth Elemental ~ Push
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:16
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Earth|Extraplanar
- **HITDICEADVANCEMENT:** 20
- **CR:** 7

### Elemental (Earth Greater)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX,INT|-2
- **BONUS:** STAT|CON|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Earth Elemental ~ Earth Glide|Earth Elemental ~ Earth Mastery|Earth Elemental ~ Push
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:21
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Earth|Extraplanar
- **HITDICEADVANCEMENT:** 23
- **CR:** 9

### Elemental (Earth Elder)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|22
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Earth Elemental ~ Earth Glide|Earth Elemental ~ Earth Mastery|Earth Elemental ~ Push
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:24
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Earth|Extraplanar
- **HITDICEADVANCEMENT:** 48
- **CR:** 11

### Elemental (Fire Small)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fire Elemental ~ Burn
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*1,1d4
- **MONSTERCLASS:** Elemental:2
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Fire|Extraplanar
- **HITDICEADVANCEMENT:** 3
- **CR:** 1

### Elemental (Fire Medium)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fire Elemental ~ Burn
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*1,1d6
- **MONSTERCLASS:** Elemental:4
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Fire|Extraplanar
- **HITDICEADVANCEMENT:** 7
- **CR:** 3

### Elemental (Fire Large)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fire Elemental ~ Burn
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*2,2d6
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:8
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Fire|Extraplanar
- **HITDICEADVANCEMENT:** 15
- **CR:** 5

### Elemental (Fire Huge)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,60
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|8
- **BONUS:** STAT|DEX|14
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fire Elemental ~ Burn
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*2,2d8
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:16
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Fire|Extraplanar
- **HITDICEADVANCEMENT:** 20
- **CR:** 7

### Elemental (Fire Greater)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,60
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|16
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fire Elemental ~ Burn
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*2,2d8
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:21
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Fire|Extraplanar
- **HITDICEADVANCEMENT:** 23
- **CR:** 9

### Elemental (Fire Elder)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,60
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|18
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative|Weapon Finesse
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fire Elemental ~ Burn
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*2,2d8
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:24
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Fire|Extraplanar
- **HITDICEADVANCEMENT:** 48
- **CR:** 11

### Elemental (Water Small)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Swim,90
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Water Elemental ~ Drench|Water Elemental ~ Vortex|Water Elemental ~ Water Mastery
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Elemental:2
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Water|Extraplanar
- **HITDICEADVANCEMENT:** 3
- **CR:** 1

### Elemental (Water Medium)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Swim,90
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Water Elemental ~ Drench|Water Elemental ~ Vortex|Water Elemental ~ Water Mastery
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **MONSTERCLASS:** Elemental:4
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Water|Extraplanar
- **HITDICEADVANCEMENT:** 7
- **CR:** 3

### Elemental (Water Large)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Swim,90
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Water Elemental ~ Drench|Water Elemental ~ Vortex|Water Elemental ~ Water Mastery
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:8
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Water|Extraplanar
- **HITDICEADVANCEMENT:** 15
- **CR:** 5

### Elemental (Water Huge)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Swim,120
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Water Elemental ~ Drench|Water Elemental ~ Vortex|Water Elemental ~ Water Mastery
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 5/-
- **MONSTERCLASS:** Elemental:16
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Water|Extraplanar
- **HITDICEADVANCEMENT:** 20
- **CR:** 7

### Elemental (Water Greater)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Swim,120
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX,CON|10
- **BONUS:** STAT|INT|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Water Elemental ~ Drench|Water Elemental ~ Vortex|Water Elemental ~ Water Mastery
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:21
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Water|Extraplanar
- **HITDICEADVANCEMENT:** 23
- **CR:** 9

### Elemental (Water Elder)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Swim,120
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|12
- **BONUS:** STAT|CON|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Water Elemental ~ Drench|Water Elemental ~ Vortex|Water Elemental ~ Water Mastery
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 10/-
- **MONSTERCLASS:** Elemental:24
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Water|Extraplanar
- **HITDICEADVANCEMENT:** 48
- **CR:** 11

### Ethereal Filcher

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Sleight of Hand|8|TYPE=Racial
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Sleight of Hand|Spot
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Ethereal Filcher ~ Detect Magic|Ethereal Filcher ~ Ethereal Jaunt|Ethereal Filcher ~ Skills
- **LEGS:** 1
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Aberration:5
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 7,15
- **CR:** 3

### Ethereal Marauder

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Move Silently,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Ethereal Marauder ~ Ethereal Jaunt|Ethereal Marauder ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Magical Beast:2
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 3
- **KIT:** 1|TN

### Ettercap

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Climb,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Craft (Trapmaking),Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR,WIS|4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Climb|Craft (Trapmaking)|Hide|Listen|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Ettercap ~ Poison|Ettercap ~ Skills|Ettercap ~ Web
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **MONSTERCLASS:** Aberration:5
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 7,15
- **LEVELADJUSTMENT:** 4
- **CR:** 3

### Ettin

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Search,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|HasLowLightVision|1
- **MONCSKILL:** Listen|Search|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Ettin Pidgin
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Javelin|Morningstar|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Ettin ~ Skills|Ettin ~ Superior Two-Weapon Fighting
- **LEGS:** 2
- **MONSTERCLASS:** Giant:10
- **RACETYPE:** Giant
- **LEVELADJUSTMENT:** 5
- **CR:** 6

### Formian (Worker)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Normal
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Listen|Search|Spot|TYPE=Craft
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Formian Shared ~ Hive Mind|Formian Worker ~ Cure Serious Wounds|Formian Worker ~ Make Whole|Formian Worker ~ Natural Weapons|Immunity to Cold|Immunity to Petrification|Immunity to Poison|Resistance to Electricity|Resistance to Fire
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Outsider:1
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Lawful|Extraplanar
- **HITDICEADVANCEMENT:** 1,3
- **CR:** 1/2
- **KIT:** 1|LN

### Formian (Warrior)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Normal
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Climb|Hide|Jump|Listen|Move Silently|Tumble
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Formian Shared ~ Hive Mind|Formian Warrior ~ Natural Weapons|Formian Warrior ~ Poison|Immunity to Cold|Immunity to Petrification|Immunity to Poison|Resistance to Electricity|Resistance to Fire
- **LEGS:** 4
- **HANDS:** 4
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **SR:** 18
- **MONSTERCLASS:** Outsider:4
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Lawful|Extraplanar
- **HITDICEADVANCEMENT:** 8,12
- **CR:** 3
- **KIT:** 1|LN

### Formian (Taskmaster)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Normal
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CHA|8
- **BONUS:** STAT|DEX,WIS|6
- **BONUS:** STAT|CON|4
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Climb|Diplomacy|Hide|Intimidate|Listen|Search|Sense Motive|Spot|Survival
- **AUTO:** LANG|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Formian Shared ~ Hive Mind|Formian Taskmaster ~ Dominated Creature|Formian Taskmaster ~ Dominate Monster|Formian Taskmaster ~ Natural Weapons|Formian Taskmaster ~ Poison|Immunity to Cold|Immunity to Petrification|Immunity to Poison|Resistance to Electricity|Resistance to Fire
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **SR:** 21
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Lawful|Extraplanar
- **HITDICEADVANCEMENT:** 9,12
- **CR:** 7
- **KIT:** 1|LN

### Formian (Myrmarch)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **VISION:** Normal
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX,CON|8
- **BONUS:** STAT|INT,WIS,CHA|6
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Climb|Concentration|Diplomacy|Hide|Listen|Move Silently|Search|Sense Motive|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Common|Formian
- **AUTO:** WEAPONPROF|Javelin|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fast Healing 2|Formian Myrmarch ~ Natural Weapons|Formian Myrmarch ~ Poison|Formian Myrmarch ~ Spell-Like Abilities|Formian Shared ~ Hive Mind|Immunity to Cold|Immunity to Petrification|Immunity to Poison|Resistance to Electricity|Resistance to Fire
- **LEGS:** 4
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **SR:** 25
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Lawful|Extraplanar
- **HITDICEADVANCEMENT:** 18,24
- **CR:** 10
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Charm Monster,14+CHA|Clairaudience/Clairvoyance,13+CHA|Detect Chaos,11+CHA|Detect Thoughts,12+CHA|Magic Circle against Chaos,13+CHA|Teleport (Greater),17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=12|Dictum,17+CHA|Order's Wrath,14+CHA
- **KIT:** 1|LN

### Formian (Queen)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,0
- **FACE:** 10
- **REACH:** 5
- **VISION:** Normal
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer|16
- **BONUS:** STAT|CON,INT,WIS,CHA|10
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Appraise|Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Sense Motive|Spellcraft|Spot|Use Magic Device|TYPE=Knowledge
- **ABILITY:** FEAT|AUTOMATIC|Eschew Materials
- **AUTO:** LANG|Common|Formian|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fast Healing 2|Formian Queen ~ Spell-Like Abilities|Formian Queen ~ Spells|Formian Queen ~ Telepathy|Formian Shared ~ Hive Mind|Immunity to Cold|Immunity to Petrification|Immunity to Poison|Resistance to Electricity|Resistance to Fire
- **LEGS:** 0
- **DEFINESTAT:** NONSTAT|STR
- **DEFINESTAT:** NONSTAT|DEX
- **SR:** 30
- **MONSTERCLASS:** Outsider:20
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Lawful|Extraplanar
- **HITDICEADVANCEMENT:** 20,30,40
- **CR:** 17
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=17|Calm Emotions,12+CHA|Charm Monster,14+CHA|Clairaudience/Clairvoyance,13+CHA|Detect Chaos,11+CHA|Detect Thoughts,12+CHA|Dictum,17+CHA|Divination,14+CHA|Hold Monster,15+CHA|Magic Circle against Chaos,13+CHA|Order's Wrath,14+CHA|Shield of Law,18+CHA|True Seeing,16+CHA
- **ADD:** SPELLCASTER|Sorcerer
- **KIT:** 1|LN

### Frost Worm

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Burrow,10
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|HasLowLightVision|1
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Frost Worm ~ Breath Weapon|Frost Worm ~ Cold|Frost Worm ~ Death Throes|Frost Worm ~ Skills|Frost Worm ~ Trill
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Cold,*1,1d10
- **MONSTERCLASS:** Magical Beast:14
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Cold
- **HITDICEADVANCEMENT:** 21,42
- **CR:** 12

### Fungus (Shrieker)

- **SIZE:** M
- **MOVE:** Walk,0
- **FACE:** 5
- **REACH:** 0
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|-8
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|HasLowLightVision|1
- **ABILITY:** Special Ability|AUTOMATIC|Shrieker ~ Shriek
- **LEGS:** 0
- **DEFINESTAT:** NONSTAT|STR
- **DEFINESTAT:** LOCK|DEX|0
- **MONSTERCLASS:** Plant (Mindless):2
- **RACETYPE:** Plant
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 3
- **CR:** 1
- **KIT:** 1|TN

### Fungus (Violet)

- **SIZE:** M
- **MOVE:** Walk,10
- **FACE:** 5
- **REACH:** 10
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|6
- **BONUS:** VAR|HasLowLightVision|1
- **ABILITY:** Special Ability|AUTOMATIC|Violet Fungus ~ Poison
- **LEGS:** 1
- **HANDS:** 4
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Finesseable.Bludgeoning.Poison,*4,1d6
- **MONSTERCLASS:** Plant (Mindless):2
- **RACETYPE:** Plant
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 6
- **CR:** 3
- **KIT:** 1|TN

### Gargoyle

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Fly,60
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Auran,Dwarven,Elven,Giant,Gnome,Halfling
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Listen,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR,DEX|4
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT,CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Hide|Listen|Spot
- **AUTO:** LANG|Common|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Gargoyle ~ Freeze|Gargoyle ~ Natural Weapons|Gargoyle ~ Skills
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d6
- **DR:** 10/Magic
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Earth
- **HITDICEADVANCEMENT:** 6,12
- **LEVELADJUSTMENT:** 5
- **CR:** 4
- **SORTKEY:** Gargoyle

### Kapoacinth

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Swim,60
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Auran,Dwarven,Elven,Giant,Gnome,Halfling
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Listen,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR,DEX|4
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT,CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Hide|Listen|Spot
- **AUTO:** LANG|Common|Terran
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Gargoyle ~ Freeze|Gargoyle ~ Natural Weapons|Gargoyle ~ Skills
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d6
- **DR:** 10/Magic
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 6,12
- **LEVELADJUSTMENT:** 5
- **CR:** 4
- **SORTKEY:** Gargoyle

### Genie (Djinni)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Fly,60
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX|8
- **BONUS:** STAT|CON,INT,WIS,CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Appraise|Concentration|Diplomacy|Escape Artist|Listen|Move Silently|Sense Motive|Spellcraft|Spot|Use Rope|TYPE=Craft|TYPE=Knowledge
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** LANG|Auran|Celestial|Common|Ignan
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Djinni ~ Air Mastery|Djinni ~ Spell-Like Abilities|Djinni ~ Whirlwind|Genie Shared ~ Plane Shift|Immunity to Acid|Telepathy
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d8
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 10,21
- **LEVELADJUSTMENT:** 6
- **CR:** 5
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=20|Invisibility (Self Only),12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=20|Create Food and Water,13+CHA|Create Wine,11+CHA|Gaseous Form (Self Only),13+CHA|Major Creation (vegetable matter is permanent),15+CHA|Persistent Image,15+CHA|Wind Walk,16+CHA
- **KIT:** 1|CG

### Genie (Efreeti)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Fly,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON,WIS,CHA|4
- **BONUS:** STAT|INT|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Move Silently|Sense Motive|Spellcraft|Spot|TYPE=Craft
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** LANG|Auran|Common|Ignan|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Efreeti ~ Change Size|Efreeti ~ Heat|Efreeti ~ Spell-Like Abilities|Genie Shared ~ Plane Shift|Immunity to Fire|Telepathy|Vulnerability to Cold
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*2,1d8
- **MONSTERCLASS:** Outsider:10
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Fire
- **HITDICEADVANCEMENT:** 15,30
- **CR:** 8
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=12|Detect Magic,10+CHA|Produce Flame,11+CHA|Pyrotechnics,12+CHA|Scorching Ray (1 ray only),12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=12|Gaseous Form,13+CHA|Grant up to three wishes (to nongenies only),19+CHA|Permanent Image,16+CHA|Polymorph (Self Only),14+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=12|Invisibility,12+CHA|Wall of Fire,14+CHA
- **KIT:** 1|LE

### Genie (Janni)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX,INT,WIS|4
- **BONUS:** STAT|CON,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Appraise|Concentration|Diplomacy|Escape Artist|Listen|Move Silently|Ride|Sense Motive|Spot|Use Rope|TYPE=Craft
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** LANG|Common
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Longbow|Scimitar|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Genie Shared ~ Plane Shift|Janni ~ Change Size|Janni ~ Elemental Endurance|Janni ~ Spell-Like Abilities|Resistance to Fire|Telepathy
- **LEGS:** 2
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Native
- **HITDICEADVANCEMENT:** 9,18
- **LEVELADJUSTMENT:** 5
- **CR:** 4
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=12|Invisibility (Self Only),12+CHA|Speak with Animals,11+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=7|Create Food and Water,10+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=12|Ethereal Jaunt (1 hour),17+CHA

### Ghoul

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX,WIS|4
- **BONUS:** STAT|INT,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Balance|Climb|Hide|Jump|Move Silently|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Ghoul ~ Ghoul Fever|Ghoul ~ Paralysis|Turn Resistance
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Paralysis.Disease,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Paralysis,*2,1d3
- **MONSTERCLASS:** Undead:2
- **RACETYPE:** Undead
- **HITDICEADVANCEMENT:** 3
- **CR:** 1
- **KIT:** 1|CE
- **SORTKEY:** Ghoul_1

### Lacedon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX,WIS|4
- **BONUS:** STAT|INT,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Balance|Climb|Hide|Jump|Move Silently|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Ghoul ~ Ghoul Fever|Ghoul ~ Paralysis|Turn Resistance
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Paralysis.Disease,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Paralysis,*2,1d3
- **MONSTERCLASS:** Undead:2
- **RACETYPE:** Undead
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 3
- **CR:** 1
- **SORTKEY:** Ghoul_2

### Ghast

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX,CHA|6
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Balance|Climb|Hide|Jump|Move Silently|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Ghast ~ Ghoul Fever|Ghast ~ Stench|Ghast ~ Stench|Turn Resistance
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Paralysis.Disease,*1,1d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Paralysis,*2,1d4
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **HITDICEADVANCEMENT:** 8
- **CR:** 3
- **SORTKEY:** Ghoul_3

### Giant (Cloud)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,50
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX,INT,CHA|2
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|WIS|6
- **BONUS:** WEAPONPROF=Thrown Rock|TOHIT|1|TYPE=Racial
- **BONUS:** WEAPONPROF=Giant Rock|TOHIT|1|TYPE=Racial
- **MONCSKILL:** Climb|Diplomacy|Intimidate|Listen|Perform (String Instruments)|Sense Motive|Spot|TYPE=Craft
- **AUTO:** ARMORPROF|ARMORTYPE=Light
- **AUTO:** LANG|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Morningstar|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Cloud Giant ~ Oversized Weapon|Cloud Giant ~ Rock Throwing|Giant Shared ~ Rock Catching|Giant Shared ~ Rock Throwing|Scent
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6
- **NATURALATTACKS:** Thrown Rock,Weapon.Natural.Ranged.Thrown.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Giant:17
- **RACETYPE:** Giant
- **RACESUBTYPE:** Air
- **CR:** 11
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=15|Fog Cloud,12+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=15|Levitate (Self Only),12+CHA|Obscuring Mist,11+CHA
- **KIT:** 1|Default Giant Rock (Cloud)

### Giant (Fire)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|WIS|4
- **BONUS:** WEAPONPROF=Thrown Rock|TOHIT|1|TYPE=Racial
- **BONUS:** WEAPONPROF=Giant Rock|TOHIT|1|TYPE=Racial
- **MONCSKILL:** Climb|Intimidate|Jump|Spot|TYPE=Craft
- **AUTO:** ARMORPROF|ARMORTYPE=Heavy|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Greatsword|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Fire Giant ~ Rock Throwing|Giant Shared ~ Rock Catching|Giant Shared ~ Rock Throwing
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **NATURALATTACKS:** Thrown Rock,Weapon.Natural.Ranged.Thrown.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Giant:15
- **RACETYPE:** Giant
- **RACESUBTYPE:** Fire
- **LEVELADJUSTMENT:** 4
- **CR:** 10
- **KIT:** 1|Default Giant Rock (Fire)

### Giant (Frost)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|WIS|4
- **BONUS:** WEAPONPROF=Thrown Rock|TOHIT|1|TYPE=Racial
- **BONUS:** WEAPONPROF=Giant Rock|TOHIT|1|TYPE=Racial
- **MONCSKILL:** Climb|Intimidate|Jump|Spot|TYPE=Craft
- **AUTO:** ARMORPROF|ARMORTYPE=Light
- **AUTO:** LANG|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Greataxe|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Frost Giant ~ Rock Throwing|Giant Shared ~ Rock Catching|Giant Shared ~ Rock Throwing
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **NATURALATTACKS:** Thrown Rock,Weapon.Natural.Ranged.Thrown.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Giant:14
- **RACETYPE:** Giant
- **RACESUBTYPE:** Cold
- **LEVELADJUSTMENT:** 4
- **CR:** 9
- **KIT:** 1|Default Giant Rock (Large)

### Giant (Hill)

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Common,Draconic,Elven,Goblin,Orc
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT,CHA|-4
- **BONUS:** WEAPONPROF=Thrown Rock|TOHIT|1|TYPE=Racial
- **BONUS:** WEAPONPROF=Giant Rock|TOHIT|1|TYPE=Racial
- **MONCSKILL:** Climb|Jump|Listen|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Greatclub|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Giant Shared ~ Rock Catching|Giant Shared ~ Rock Throwing|Hill Giant ~ Rock Throwing
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **NATURALATTACKS:** Thrown Rock,Weapon.Natural.Ranged.Thrown.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Giant:12
- **RACETYPE:** Giant
- **LEVELADJUSTMENT:** 4
- **CR:** 7
- **KIT:** 1|Default Giant Rock (Large)

### Giant (Stone)

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Common,Draconic,Elven,Goblin,Orc
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Thrown Rock|TOHIT|1|TYPE=Racial
- **BONUS:** WEAPONPROF=Giant Rock|TOHIT|1|TYPE=Racial
- **BONUS:** WEAPONPROF=Giant Rock|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Thrown Rock|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Greatclub|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Giant Shared ~ Rock Catching|Giant Shared ~ Rock Throwing|Stone Giant ~ Rock Catching|Stone Giant ~ Rock Throwing|Stone Giant ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **NATURALATTACKS:** Thrown Rock,Weapon.Natural.Ranged.Thrown.Bludgeoning,*1,2d8
- **MONSTERCLASS:** Giant:14
- **RACETYPE:** Giant
- **RACESUBTYPE:** Earth
- **CR:** 8
- **KIT:** 1|Default Giant Rock (Stone)

### Giant (Storm)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,50
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** STAT|STR|28
- **BONUS:** STAT|DEX,CHA|4
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|10
- **MONCSKILL:** Climb|Concentration|Diplomacy|Intimidate|Jump|Listen|Perform (Sing)|Sense Motive|Spot|Swim|TYPE=Craft
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Greatsword|Longbow|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Giant Shared ~ Rock Catching|Immunity to Electricity|Storm Giant ~ Freedom of Movement|Storm Giant ~ Skills|Storm Giant ~ Spell-Like Abilities|Storm Giant ~ Water Breathing
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6
- **MONSTERCLASS:** Giant:19
- **RACETYPE:** Giant
- **CR:** 13
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=15|Call Lightning,13+CHA|Chain Lightning,16+CHA
- **SPELLS:** Innate|TIMES=2|CASTERLEVEL=20|Control Weather|Levitate,12+CHA

### Gibbering Mouther

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,10,Swim,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|DEX,WIS,CHA|2
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Spittle|TOHIT|5
- **MONCSKILL:** Listen|Spot|Swim
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Gibbering Mouther ~ Amorphous|Gibbering Mouther ~ Blood Drain|Gibbering Mouther ~ Engulf|Gibbering Mouther ~ Gibbering|Gibbering Mouther ~ Ground Manipulation|Gibbering Mouther ~ Improved Grab|Gibbering Mouther ~ Skills|Gibbering Mouther ~ Spittle
- **LEGS:** 0
- **HANDS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Acid,*6,1|Spittle,Weapon.Natural.Ranged.Touch.Acid.Blindness,*1,1d0
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Aberration:4
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 4,12
- **CR:** 5

### Girallon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Climb,40
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Girallon ~ Rend|Girallon ~ Skills|Scent
- **LEGS:** 2
- **HANDS:** 5
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*4,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:7
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 10,21
- **CR:** 6

### Githyanki

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **LANGBONUS:** Common,Draconic,Infernal,Undercommon
- **BONUS:** STAT|DEX,CON|2
- **BONUS:** STAT|WIS|-2
- **AUTO:** LANG|Githyanki
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Githyanki
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Extraplanar
- **LEVELADJUSTMENT:** 2

### Githzerai

- **FAVCLASS:** Monk
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **LANGBONUS:** Common,Slaad,Undercommon
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|INT|-2
- **AUTO:** LANG|Githzerai
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Githzerai
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Extraplanar
- **LEVELADJUSTMENT:** 2

### Gnoll

- **FAVCLASS:** Ranger
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Common,Draconic,Elven,Goblin,Orc
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT,CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light
- **AUTO:** LANG|Gnoll
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Battleaxe|Shortbow|TYPE=Simple
- **LEGS:** 2
- **MONSTERCLASS:** Humanoid (Fortitude):2
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Gnoll
- **LEVELADJUSTMENT:** 1
- **CR:** 1
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Gnoll

### Golem (Clay)

- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Clay Golem ~ Berserk|Clay Golem ~ Cursed Wound|Clay Golem ~ Haste|Clay Golem ~ Immunity to Magic|Golem Shared ~ Immunity to Magic
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.CursedWound,*2,2d10
- **DR:** 10/Adamantine and Bludgeoning
- **MONSTERCLASS:** Construct (Mindless):11
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 18,33
- **CR:** 10
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=3|Haste,13

### Golem (Flesh)

- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Flesh Golem ~ Berserk|Flesh Golem ~ Immunity to Magic|Golem Shared ~ Immunity to Magic
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8
- **DR:** 5/Adamantine
- **MONSTERCLASS:** Construct (Mindless):9
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 18,27
- **CR:** 7

### Golem (Iron)

- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|22|TYPE=NaturalArmor
- **BONUS:** STAT|STR|22
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Golem Shared ~ Immunity to Magic|Iron Golem ~ Breath Weapon|Iron Golem ~ Immunity to Magic
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 15/Adamantine
- **MONSTERCLASS:** Construct (Mindless):18
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 24,54
- **CR:** 13

### Golem (Stone)

- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|18|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Golem Shared ~ Immunity to Magic|Stone Golem ~ Immunity to Magic|Stone Golem ~ Slow
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d10
- **DR:** 10/Adamantine
- **MONSTERCLASS:** Construct (Mindless):14
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 21,42
- **CR:** 11

### Gorgon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Gorgon ~ Breath Weapon|Gorgon ~ Trample|Scent
- **LEGS:** 4
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Magical Beast:8
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 15,24
- **CR:** 8

### Gray Render

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Hide|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Gray Render ~ Improved Grab|Gray Render ~ Rend|Gray Render ~ Skills|Scent
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Magical Beast:10
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 15,30
- **CR:** 8

### Grick

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Climb,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX,WIS|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Track
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Grick ~ Skills|Scent
- **LEGS:** 0
- **HANDS:** 5
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Finesseable.Bludgeoning,*4,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **DR:** 10/Magic
- **MONSTERCLASS:** Aberration:2
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 3

### Griffon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,80
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Jump|Listen|Spot
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Griffon ~ Pounce|Griffon ~ Rake|Griffon ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **MONSTERCLASS:** Magical Beast:7
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 10,21
- **LEVELADJUSTMENT:** 3
- **CR:** 4

### Grimlock

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Draconic,Dwarven,Gnome,Terran,Undercommon
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX,CON|2
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|BlindsightRange|40|TYPE=Base
- **MONCSKILL:** Climb|Hide|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Track
- **AUTO:** LANG|Common|Grimlock
- **AUTO:** WEAPONPROF|Battleaxe|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Grimlock ~ Blindsight|Grimlock ~ Immunities|Grimlock ~ Skills|Scent
- **LEGS:** 2
- **MONSTERCLASS:** Monstrous Humanoid:2
- **RACETYPE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 2
- **CR:** 1

### Guardinal (Avoral)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Fly,90
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|12
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|FearAuraRadius|20
- **BONUS:** VAR|FearAuraDC|10+(TL/2)+CHA
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Handle Animal|Hide|Intimidate|Listen|Move Silently|Ride|Sense Motive|Spellcraft|Spot|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Draconic|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Avoral ~ Fear Aura|Avoral ~ Lay on Hands|Avoral ~ Natural Weapons|Avoral ~ Skills|Avoral ~ Speak with Animals|Avoral ~ Spell-Like Abilities|Avoral ~ True Seeing|Immunity to Electricity|Immunity to Petrification|Resistance to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6
- **NATURALATTACKS:** Wing,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8
- **SR:** 25
- **DR:** 10/Evil or Silver
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Good
- **HITDICEADVANCEMENT:** 14,21
- **CR:** 9
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=8|Aid,12+CHA|Blur (Self Only),12+CHA|Command,11+CHA|Detect Magic,10+CHA|Dimension Door,14+CHA|Dispel Magic,13+CHA|Gust of Wind,12+CHA|Hold Person,13+CHA|Light,10+CHA|Magic Circle against Evil (Self Only),13+CHA|Magic Missile,11+CHA|See Invisibility,12+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=8|Lightning Bolt,13+CHA
- **KIT:** 1|NG

### Guardinal (Leonal)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT,WIS,CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **MONCSKILL:** Balance|Concentration|Diplomacy|Hide|Intimidate|Jump|Listen|Move Silently|Sense Motive|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Celestial|Common|Draconic
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Electricity|Immunity to Petrification|Leonal ~ Improved Grab|Leonal ~ Lay On Hands|Leonal ~ Natural Weapons|Leonal ~ Pounce|Leonal ~ Protective Aura|Leonal ~ Rake|Leonal ~ Skills|Leonal ~ Speak with Animals|Leonal ~ Spell-Like Abilities|Resistance to Cold|Roar
- **LEGS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **SR:** 28
- **DR:** 10/Evil and Silver
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Good
- **HITDICEADVANCEMENT:** 18,36
- **CR:** 12
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=10|Detect Thoughts,12+CHA|Fireball,13+CHA|Hold Monster,15+CHA|Polymorph,14+CHA|Wall of Force,15+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=10|Heal,16+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=10|Cure Critical Wounds,14+CHA|Neutralize Poison,13+CHA|Remove Disease,13+CHA
- **KIT:** 1|NG

### Hag (Annis)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX,INT,WIS|2
- **BONUS:** STAT|CON|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Hide|Intimidate|Listen|Spot
- **AUTO:** LANG|Common|Giant
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Hag Annis ~ Improved Grab|Hag Annis ~ Rake|Hag Annis ~ Rend|Hag Annis ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **SR:** 19
- **DR:** 2/Bludgeoning
- **MONSTERCLASS:** Monstrous Humanoid:7
- **RACETYPE:** Monstrous Humanoid
- **CR:** 6
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=8|Disguise Self,11+CHA|Fog Cloud,12+CHA

### Hag (Green)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,CON,INT,WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|90|TYPE=Base
- **MONCSKILL:** Concentration|Hide|Listen|Spot|TYPE=Craft|TYPE=Knowledge
- **AUTO:** LANG|Common|Giant
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Green Hag ~ Mimicry|Green Hag ~ Skills|Green Hag ~ Spell-Like Abilities|Green Hag ~ Weakness
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **SR:** 18
- **MONSTERCLASS:** Monstrous Humanoid:9
- **RACETYPE:** Monstrous Humanoid
- **CR:** 5
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=9|Dancing Lights,10+CHA|Disguise Self,12+CHA|Ghost Sound,10+CHA|Invisibility,12+CHA|Pass without Trace,11+CHA|Tongues,13+CHA|Water Breathing,13+CHA

### Hag (Sea)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,CON,WIS|2
- **BONUS:** STAT|CHA|4
- **MONCSKILL:** Hide|Listen|Spot|Swim|TYPE=Craft|TYPE=Knowledge
- **AUTO:** LANG|Common|Giant
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Sea Hag ~ Amphibious|Sea Hag ~ Evil Eye|Sea Hag ~ Horrific Appearance|Sea Hag ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **SR:** 14
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Aquatic
- **CR:** 4

### Harpy

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Fly,80
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Bluff,Listen|4|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Intimidate|Listen|Perform (Oratory)|Spot
- **AUTO:** WEAPONPROF|Club|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Harpy ~ Captivating Song|Harpy ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **MONSTERCLASS:** Monstrous Humanoid:7
- **RACETYPE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 4

### Hell Hound

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Move Silently|5|TYPE=Racial
- **BONUS:** STAT|STR,DEX,CON|2
- **BONUS:** STAT|INT,CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Jump|Listen|Move Silently|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Track
- **AUTO:** LANG|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Hell Hound ~ Breath Weapon|Hell Hound ~ Fiery Bite|Hell Hound ~ Skills
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Fire,*1,1d8
- **MONSTERCLASS:** Outsider:4
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Evil|Extraplanar|Fire|Lawful
- **HITDICEADVANCEMENT:** 8,12
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **KIT:** 1|LE

### Hippogriff

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50,Fly,100
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Hippogriff ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:3
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 6,9
- **CR:** 2
- **KIT:** 1|TN

### Homunculus

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,20,Fly,50
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Homunculus ~ Poison
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d4
- **MONSTERCLASS:** Construct:2
- **RACETYPE:** Construct
- **HITDICEADVANCEMENT:** 6
- **CR:** 1

### Howler

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON,WIS|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Listen|Move Silently|Search|Spot|Survival
- **AUTO:** LANG|Abyssal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Howler ~ Howl|Howler ~ Natural Weapons|Howler ~ Quills
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Quill,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d6
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Evil|Extraplanar
- **HITDICEADVANCEMENT:** 9,18
- **CR:** 3
- **KIT:** 1|CE

### Hydra

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Swim,20
- **FACE:** 15
- **REACH:** 10
- **BONUS:** ABILITYPOOL|Hydra Heads|1
- **BONUS:** COMBAT|AC|HydraNaturalArmor|TYPE=NaturalArmor
- **BONUS:** MISC|CR|HydraHeadCount-1
- **BONUS:** SKILL|Listen,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|HydraNaturalArmor|HydraHeadCount+1
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Combat Reflexes
- **ABILITY:** Special Ability|AUTOMATIC|Hydra ~ Fast Healing|Hydra ~ Feats|Hydra ~ Skills|Scent
- **LEGS:** 4
- **DEFINE:** HydraNaturalArmor|0
- **DEFINE:** HydraHeadCount|0
- **MONSTERCLASS:** Magical Beast:5
- **RACETYPE:** Magical Beast

### Inevitable (Kolyarut)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** SKILL|Disguise,Gather Information,Sense Motive|4|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|WIS,CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Vampiric Touch|DAMAGE|-1*(STR)
- **BONUS:** WEAPONPROF=Enervation Ray|TOHIT|5
- **BONUS:** WEAPONPROF=Slam|TOHIT|5
- **MONCSKILL:** Diplomacy|Disguise|Gather Information|Listen|Search|Sense Motive|Spot|Survival
- **AUTO:** ARMORPROF|Banded Mail
- **AUTO:** LANG|Abyssal|Celestial|Infernal
- **AUTO:** WEAPONPROF|Longsword
- **ABILITY:** Special Ability|AUTOMATIC|Inevitable ~ Fast Healing|Inevitable ~ Natural Weapons|Kolyarut ~ Enervation Ray|Kolyarut ~ Natural Weapons|Kolyarut ~ Skills|Kolyarut ~ Spell-Like Abilities|Kolyarut ~ Vampiric Touch
- **LEGS:** 2
- **NATURALATTACKS:** Vampiric Touch,Weapon.Natural.Melee.Finesseable.Bludgeoning.Touch,1,5d6|Enervation Ray,Weapon.Natural.Ranged.Touch.Piercing,*1,as spell|Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,1,1d6
- **SR:** 22
- **DR:** 10/Chaotic
- **MONSTERCLASS:** Construct:13
- **RACETYPE:** Construct
- **RACESUBTYPE:** Extraplanar|Lawful
- **HITDICEADVANCEMENT:** 22,39
- **CR:** 12
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=13|Discern Lies,14+CHA|Disguise Self,14+CHA|Fear,14+CHA|Hold Person,13+CHA|Invisibility,12+CHA|Locate Creature,14+CHA|Suggestion,13+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=13|Hold Monster,14+CHA|Mark of Justice,5+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=13|Geas/Quest,16+CHA
- **KIT:** 1|LN

### Inevitable (Marut)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|16|TYPE=NaturalArmor
- **BONUS:** SKILL|Concentration,Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX,INT|2
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Right Slam|TOHIT|5
- **BONUS:** WEAPONPROF=Right Slam|DAMAGE|STR/2
- **MONCSKILL:** Concentration|Diplomacy|Knowledge (Religion)|Listen|Search|Sense Motive|Spot|Survival
- **AUTO:** ARMORPROF|Full Plate
- **AUTO:** LANG|Abyssal|Celestial|Infernal
- **ABILITY:** Special Ability|AUTOMATIC|Inevitable ~ Fast Healing|Inevitable ~ Natural Weapons|Marut ~ Fists of Thunder and Lightning|Marut ~ Natural Weapons|Marut ~ Skills|Marut ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Left Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Sonic,*1,2d6|Right Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Electricity,*1,2d6
- **SR:** 25
- **DR:** 15/Chaotic
- **MONSTERCLASS:** Construct:15
- **RACETYPE:** Construct
- **RACESUBTYPE:** Extraplanar|Lawful
- **HITDICEADVANCEMENT:** 28,45
- **CR:** 15
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=14|Air Walk,14+CHA|Command (Greater),15+CHA|Dimension Door,14+CHA|Dispel Magic (Greater),16+CHA|Fear,14+CHA|Inflict Light Wounds (Mass),15+CHA|Locate Creature,14+CHA|True Seeing,15+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=14|Chain Lightning,16+CHA|Circle of Death,16+CHA|Mark of Justice,15+CHA|Wall of Force,15+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=14|Earthquake,18+CHA|Geas/Quest,16+CHA|Plane Shift,15+CHA
- **KIT:** 1|LN

### Inevitable (Zelekhut)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** SKILL|Search,Sense Motive|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Diplomacy|Listen|Search|Sense Motive|Spot|Survival
- **AUTO:** ARMORPROF|ARMORTYPE=Heavy
- **AUTO:** LANG|Abyssal|Celestial|Infernal
- **AUTO:** WEAPONPROF|Chain (Spiked)
- **ABILITY:** Special Ability|AUTOMATIC|Inevitable ~ Fast Healing|Inevitable ~ Natural Weapons|Zelekhut ~ Feats|Zelekhut ~ Natural Weapons|Zelekhut ~ Skills|Zelekhut ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Spiked Chains,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Electricity,*2,2d6
- **SR:** 20
- **DR:** 10/Chaotic
- **MONSTERCLASS:** Construct:8
- **RACETYPE:** Construct
- **RACESUBTYPE:** Extraplanar|Lawful
- **HITDICEADVANCEMENT:** 16,24
- **LEVELADJUSTMENT:** 7
- **CR:** 9
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=8|Clairaudience/Clairvoyance,13+CHA|Dimensional Anchor,14+CHA|Dispel Magic,13+CHA|Fear,14+CHA|Hold Person,13+CHA|Locate Creature,14+CHA|True Seeing,15+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=8|Hold Monster,15+CHA|Mark of Justice,15+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=8|Geas (Lesser),14+CHA
- **KIT:** 1|LN

### Invisible Stalker

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX|8
- **BONUS:** STAT|CON,INT,WIS|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Listen|Move Silently|Search|Spot|Survival
- **AUTO:** LANG|Auran|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Invisible Stalker ~ Improved Tracking|Invisible Stalker ~ Natural Invisibility
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **MONSTERCLASS:** Elemental (Air/Fire):8
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air|Extraplanar
- **HITDICEADVANCEMENT:** 12,24
- **CR:** 7

### Kraken

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** G
- **MOVE:** Swim,20
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|CON|18
- **BONUS:** STAT|INT,WIS,CHA|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Concentration|Diplomacy|Hide|Intimidate|Knowledge (Geography)|Knowledge (Nature)|Listen|Search|Sense Motive|Spot|Survival|Swim|Use Magic Device
- **AUTO:** LANG|Aquan|Common
- **ABILITY:** Special Ability|AUTOMATIC|Kraken ~ Constrict|Kraken ~ Improved Grab|Kraken ~ Ink Cloud|Kraken ~ Jet|Kraken ~ Skills|Kraken ~ Spell-Like Abilities
- **LEGS:** 0
- **HANDS:** 9
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Finesseable.Reach.4Reach.Bludgeoning,*2,2d8|Arm,Weapon.Natural.Melee.Finesseable.Reach.2Reach.Bludgeoning,*6,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6
- **MONSTERCLASS:** Magical Beast:20
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 32,60
- **CR:** 12
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=9|Control Weather,17+CHA|Control Winds,15+CHA|Dominate Animal,13+CHA|Resist Energy,12+CHA

### Krenshar

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Hide|Jump|Listen|Move Silently
- **ABILITY:** FEAT|AUTOMATIC|Track
- **ABILITY:** Special Ability|AUTOMATIC|Krenshar ~ Scare|Krenshar ~ Skills|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **MONSTERCLASS:** Magical Beast:2
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 4,8
- **BONUS:** VAR|LevelAdjustment|2|TYPE=Base
- **CR:** 1

### Kuo-Toa

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-2
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Kuo-Toa
- **MONSTERCLASS:** Monstrous Humanoid:2
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Aquatic
- **BONUS:** VAR|LevelAdjustment|3|TYPE=Base
- **CR:** 2

### Lamia

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** SKILL|Bluff,Hide|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,WIS|4
- **BONUS:** STAT|CON,INT,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Hide|Intimidate|Spot
- **AUTO:** WEAPONPROF|Dagger
- **ABILITY:** Special Ability|AUTOMATIC|Lamia ~ Skills|Lamia ~ Spell-Like Abilities|Lamia ~ Wisdom Drain
- **LEGS:** 4
- **NATURALATTACKS:** Touch,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 13,27
- **BONUS:** VAR|LevelAdjustment|4|TYPE=Base
- **CR:** 6
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=9|Disguise Self,11+CHA|Ventriloquism,11+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=9|Deep Slumber,13+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=9|Charm Monster,14+CHA|Major Image,13+CHA|Mirror Image,12+CHA|Suggestion,13+CHA

### Lammasu

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Cleric|7
- **BONUS:** SKILL|Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON,INT,WIS|6
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Concentration|Diplomacy|Knowledge (Arcana)|Listen|Sense Motive|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Lammasu ~ Magic Circle against Evil|Lammasu ~ Pounce|Lammasu ~ Skills|Lammasu ~ Spell-Like Abilities|Lammasu ~ Spells|Rake
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Magical Beast:7
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 10,21
- **BONUS:** VAR|LevelAdjustment|5|TYPE=Base
- **CR:** 8
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=7|Dimension Door,14+CHA
- **SPELLS:** Innate|TIMES=2|CASTERLEVEL=7|Invisibility (Greater/Self Only),14+CHA
- **ADD:** SPELLCASTER|Cleric
- **KIT:** 1|LG

### Lillend

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Fly,70
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Bard|5
- **BONUS:** SKILL|Survival|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX,WIS|6
- **BONUS:** STAT|CON,INT|4
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|Maneuverability|3
- **BONUS:** WEAPONPROF=Tail|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Appraise|Concentration|Diplomacy|Knowledge (Arcana)|Listen|Sense Motive|Spellcraft|Spot|Survival|TYPE=Perform
- **AUTO:** LANG|Abyssal|Celestial|Common|Infernal
- **AUTO:** WEAPONPROF|Sword (Short)|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Immunity to Poison|Lillend ~ Constrict|Lillend ~ Improved Grab|Lillend ~ Natural Weapons|Lillend ~ Skills|Lillend ~ Spell-Like Abilities|Lillend ~ Spells|Resistance to Fire
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar|Good
- **HITDICEADVANCEMENT:** 10,21
- **BONUS:** VAR|LevelAdjustment|6|TYPE=Base
- **CR:** 7
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=10|Charm Person,11+CHA|Speak with Animals,13+CHA|Speak with Plants,14+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=10|Darkness,12+CHA|Hallucinatory Terrain,14+CHA|Knock,12+CHA|Light,10+CHA
- **ADD:** SPELLCASTER|Bard
- **KIT:** 1|CG

### Locathah

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,10,Swim,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX,INT,WIS|2
- **MONCSKILL:** Listen|Spot|Swim|TYPE=Craft
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|Crossbow (Light)|Longspear|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Locathah ~ Skills
- **LEGS:** 2
- **MONSTERCLASS:** Humanoid (Fortitude):2
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Aquatic
- **BONUS:** VAR|LevelAdjustment|1|TYPE=Base
- **CR:** 1/2

### Magmin

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Burning touch|DAMAGE|-1*(STR)
- **BONUS:** WEAPONPROF=Slam|DAMAGE|STR/2
- **MONCSKILL:** Climb|Spot
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Magmin ~ Combustion|Magmin ~ Fiery Aura|Magmin ~ Melt Weapons|Magmin ~ Natural Weapons
- **LEGS:** 2
- **NATURALATTACKS:** Burning touch,Weapon.Natural.Melee.Finesseable.Touch.Fire.Combustion,*1,1d8
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Combustion,*1,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Elemental (Air/Fire):2
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Fire|Extraplanar
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 3
- **KIT:** 1|CN

### Manticore

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|1
- **BONUS:** WEAPONPROF=Spikes|DAMAGE|2
- **BONUS:** WEAPONPROF=Spikes|CRITRANGEADD|1
- **MONCSKILL:** Listen|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Track
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Manticore ~ Skills|Manticore ~ Spikes|Scent
- **LEGS:** 4
- **HANDS:** 6
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **NATURALATTACKS:** Spikes,Weapon.Natural.Ranged.Piercing,*6,1d8
- **MONSTERCLASS:** Magical Beast:6
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 16,18
- **LEVELADJUSTMENT:** 3
- **CR:** 5

### Medusa

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON,INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Snakes|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Intimidate|Move Silently|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|Dagger|Shortbow|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Medusa ~ Petrifying Gaze|Medusa ~ Poison
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Snakes,Weapon.Natural.Melee.Finesseable.Slashing.Poison,*1,1d4
- **MONSTERCLASS:** Monstrous Humanoid:6
- **RACETYPE:** Monstrous Humanoid
- **CR:** 7

### Mephit (Air)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Intimidate|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Auran|Common
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Air Mephit ~ Breath Weapon|Air Mephit ~ Fast Healing|Air Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Air|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Blur,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Gust of Wind,12+CHA

### Mephit (Dust)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Intimidate|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Auran|Common
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Dust Mephit ~ Breath Weapon|Dust Mephit ~ Fast Healing|Dust Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Air|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Blur,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Wind Wall,13+CHA

### Mephit (Earth)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Intimidate|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Common|Terran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Earth Mephit ~ Breath Weapon|Earth Mephit ~ Change Size|Earth Mephit ~ Fast Healing|Earth Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Earth|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Soften Earth and Stone,12+CHA

### Mephit (Fire)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Common|Ignan
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Fire Mephit ~ Breath Weapon|Fire Mephit ~ Fast Healing|Fire Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Fire,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Fire|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Scorching Ray,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Heat Metal,12+CHA

### Mephit (Ice)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Auran|Common
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Ice Mephit ~ Breath Weapon|Ice Mephit ~ Fast Healing|Ice Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Cold,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Air|Cold|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Magic Missile,11+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Chill Metal,12+CHA

### Mephit (Magma)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Common|Ignan
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Magma Mephit ~ Breath Weapon|Magma Mephit ~ Fast Healing|Magma Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Fire,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Fire|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Shapechange,19+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Pyrotechnics,12+CHA

### Mephit (Ooze)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,40,Swim,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CHA|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Listen|Move Silently|Spot|Swim|Use Rope
- **AUTO:** LANG|Aquan|Common
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Ooze Mephit ~ Breath Weapon|Ooze Mephit ~ Fast Healing|Ooze Mephit ~ Skills|Ooze Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Water|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Acid Arrow,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Stinking Cloud,13+CHA

### Mephit (Salt)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Common|Terran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Salt Mephit ~ Breath Weapon|Salt Mephit ~ Fast Healing|Salt Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Earth|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Glitterdust,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Draw Moisture,12+CHA

### Mephit (Steam)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Listen|Move Silently|Spot|Use Rope
- **AUTO:** LANG|Common|Ignan
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Steam Mephit ~ Breath Weapon|Steam Mephit ~ Fast Healing|Steam Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Fire,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Fire|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Blur,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Steaming Rainstorm,12+CHA

### Mephit (Water)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Fly,40,Swim,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CHA|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Escape Artist|Hide|Listen|Move Silently|Spot|Swim|Use Rope
- **AUTO:** LANG|Aquan|Common
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Water Mephit ~ Breath Weapon|Water Mephit ~ Fast Healing|Water Mephit ~ Skills|Water Mephit ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **DR:** 5/Magic
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Mephit|Water|Extraplanar
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Hour|CASTERLEVEL=3|Acid Arrow,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Stinking Cloud,13+CHA

### Merfolk

- **FAVCLASS:** Bard
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,5,Swim,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|DEX,CON,CHA|2
- **AUTO:** LANG|Common|Aquan
- **ABILITY:** Special Ability|AUTOMATIC|Merfolk ~ Amphibious|Merfolk ~ Skills
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Aquatic
- **LEVELADJUSTMENT:** 1
- **CR:** 1/2

### Mimic

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Disguise|8|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|CON|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Disguise|Listen|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Acid|Mimic ~ Adhesive|Mimic ~ Crush|Mimic ~ Mimic Shape|Mimic ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d8
- **MONSTERCLASS:** Aberration:7
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Shapechanger
- **HITDICEADVANCEMENT:** 10,21
- **CR:** 4

### Mind Flayer

- **FAVCLASS:** Wizard
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **LANGBONUS:** Abyssal,Aquan,Draconic,Dwarven,Elven,Gnome,Infernal,Terran
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|8,
- **BONUS:** STAT|WIS,CHA|6
- **BONUS:** VAR|MindFlayerSR|25-8+TL
- **BONUS:** VAR|TelepathyRange|100
- **MONCSKILL:** Bluff|Concentration|Hide|Intimidate|Listen|Move Silently|Spot|TYPE=Knowledge
- **AUTO:** LANG|Common|Undercommon
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Mind Flayer
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Tentacle,Natural.Melee.Weapon.Bludgeon,*4,1d4
- **DEFINE:** MindFlayerSR|0
- **DEFINE:** TelepathyRange|0
- **SR:** MindFlayerSR
- **MONSTERCLASS:** Aberration:8
- **RACETYPE:** Aberration
- **LEVELADJUSTMENT:** 7

### Minotaur

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Goblin,Orc,Terran
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Search,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Intimidate|Jump|Listen|Search|Spot
- **AUTO:** LANG|Common|Giant
- **AUTO:** WEAPONPROF|Greataxe|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Minotaur ~ Natural Cunning|Minotaur ~ Powerful Charge|Minotaur ~ Skills|Scent
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Monstrous Humanoid:6
- **RACETYPE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 4

### Mohrg

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Listen|Move Silently|Spot|Swim
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Mohrg ~ Create Spawn|Mohrg ~ Improved Grab|Mohrg ~ Paralyzing Touch
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **NATURALATTACKS:** Tongue,Weapon.Natural.Melee.Finesseable.Touch.Paralysis,*1,1d0
- **MONSTERCLASS:** Undead:14
- **RACETYPE:** Undead
- **HITDICEADVANCEMENT:** 21,28
- **CR:** 8
- **KIT:** 1|CE

### Mummy

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS,CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Mummy ~ Despair|Mummy ~ Mummy Rot|Vulnerability to Fire
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.MummyRot,*1,1d6
- **DR:** 5/-
- **MONSTERCLASS:** Undead:8
- **RACETYPE:** Undead
- **HITDICEADVANCEMENT:** 16,24
- **CR:** 5

### Naga (Dark)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer|6
- **BONUS:** STAT|STR,DEX,CON,WIS|4
- **BONUS:** STAT|INT,CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Sense Motive|Spellcraft|Spot
- **ABILITY:** FEAT|AUTOMATIC|Eschew Materials
- **AUTO:** LANG|Common|Infernal
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Dark Naga ~ Detect Thoughts|Dark Naga ~ Guarded Thoughts|Dark Naga ~ Poison|Dark Naga ~ Spells|Immunity to Poison|Resistance to Charm
- **LEGS:** 0
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Aberration:9
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 13,27
- **CR:** 8
- **ADD:** SPELLCASTER|Sorcerer

### Naga (Guardian)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|10
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON,WIS,CHA|8
- **BONUS:** STAT|INT|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Sense Motive|Spellcraft|Spot
- **ABILITY:** FEAT|AUTOMATIC|Eschew Materials
- **AUTO:** LANG|Celestial|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Guardian Naga ~ Poison|Guardian Naga ~ Spells|Guardian Naga ~ Spit
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d6
- **NATURALATTACKS:** Spit,Weapon.Natural.Ranged.Touch.Poison,*1,1d0
- **MONSTERCLASS:** Aberration:11
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 16,33
- **CR:** 10
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)

### Naga (Spirit)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer/Cleric (Arcane)|8
- **BONUS:** STAT|STR,CON|8
- **BONUS:** STAT|DEX,INT|2
- **BONUS:** STAT|WIS,CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|CharmingGazeDC|10+(HD/2)+CHA
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Listen|Spellcraft|Spot
- **ABILITY:** FEAT|AUTOMATIC|Eschew Materials
- **AUTO:** LANG|Abyssal|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Spirit Naga ~ Charming Gaze|Spirit Naga ~ Poison|Spirit Naga ~ Spells
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d6
- **MONSTERCLASS:** Aberration:9
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 13,27
- **CR:** 9
- **ADD:** SPELLCASTER|Sorcerer/Cleric (Arcane)

### Naga (Water)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Swim,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer|6
- **BONUS:** STAT|STR,WIS|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Listen|Spellcraft|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Eschew Materials
- **AUTO:** LANG|Aquan|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Water Naga ~ Poison|Water Naga ~ Skills|Water Naga ~ Spells
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d6
- **MONSTERCLASS:** Aberration:7
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 10,21
- **CR:** 7
- **ADD:** SPELLCASTER|Sorcerer

### Night Hag

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|8
- **BONUS:** STAT|DEX,CHA|2
- **BONUS:** STAT|WIS|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Ride|Sense Motive|Spellcraft|Spot
- **AUTO:** LANG|Abyssal|Celestial|Common|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold|Immunity to Fear|Immunity to Fire|Immunity to Sleep|Night Hag ~ Disease|Night Hag ~ Dream Haunting|Night Hag ~ Natural Weapons|Night Hag ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Disease,*1,2d6
- **SR:** 25
- **DR:** 10/Cold Iron and Magic
- **MONSTERCLASS:** Outsider:8
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Evil|Extraplanar
- **HITDICEADVANCEMENT:** 16
- **CR:** 9
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=8|Detect Chaos,11+CHA|Detect Evil,11+CHA|Detect Good,11+CHA|Detect Law,11+CHA|Detect Magic,10+CHA|Magic Missile,11+CHA|Polymorph (Self Only),14+CHA|Ray of Enfeeblement,11+CHA|Sleep,11+CHA
- **KIT:** 1|NE

### Nightmare

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Fly,90
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT,WIS,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Concentration|Diplomacy|Intimidate|Knowledge (The Planes)|Listen|Move Silently|Search|Sense Motive|Spot|Survival
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Nightmare ~ Astral Projection and Etherealness|Nightmare ~ Flaming Hooves|Nightmare ~ Natural Weapons|Nightmare ~ Smoke
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*2,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Evil|Extraplanar
- **HITDICEADVANCEMENT:** 10,18
- **LEVELADJUSTMENT:** 4
- **CR:** 5
- **KIT:** 1|NE

### Nightshade (Nightcrawler)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** G
- **MOVE:** Walk,30,Burrow,60
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|29|TYPE=NaturalArmor
- **BONUS:** STAT|STR|38
- **BONUS:** STAT|INT,WIS|10
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** VAR|EnergyDrainLevels|1
- **MONCSKILL:** Concentration|Diplomacy|Hide|Knowledge (Arcana)|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival
- **AUTO:** LANG|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold|Nightcrawler ~ Energy Drain|Nightcrawler ~ Improved Grab|Nightcrawler ~ Natural Weapons|Nightcrawler ~ Poison|Nightcrawler ~ Spell-Like Abilities|Nightcrawler ~ Summon Undead|Nightcrawler ~ Swallow Whole|Nightshade Shared ~ Aversion to Daylight|Nightshade Shared ~ Desecrating Aura|Telepathy
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d8
- **SR:** 31
- **DR:** 15/Silver and Magic
- **MONSTERCLASS:** Undead:25
- **RACETYPE:** Undead
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 25,50
- **CR:** 18
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=25|Contagion,14+CHA|Deeper Darkness,13+CHA|Detect Magic,10+CHA|Dispel Magic (Greater),16+CHA|Haste,13+CHA|Invisibility,12+CHA|See Invisibility,12+CHA|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=25|Finger of Death,17+CHA|Hold Monster (Mass),19+CHA|Plane Shift,17+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=25|Cone of Cold,15+CHA|Confusion,14+CHA|Hold Monster,15+CHA
- **KIT:** 1|CE

### Nightshade (Nightwalker)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40,Fly,20
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|22|TYPE=NaturalArmor
- **BONUS:** STAT|STR|28
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT,WIS|10
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Concentration|Diplomacy|Hide|Knowledge (Arcana)|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival
- **AUTO:** LANG|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Immunity to Cold|Nightshade Shared ~ Aversion to Daylight|Nightshade Shared ~ Desecrating Aura|Nightwalker ~ Crush Item|Nightwalker ~ Evil Gaze|Nightwalker ~ Natural Weapons|Nightwalker ~ Spell-Like Abilities|Nightwalker ~ Summon Undead|Telepathy
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **SR:** 29
- **DR:** 15/Silver and Magic
- **MONSTERCLASS:** Undead:21
- **RACETYPE:** Undead
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 31,42
- **CR:** 16
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=21|Contagion,14+CHA|Deeper Darkness,13+CHA|Detect Magic,10+CHA|Dispel Magic (Greater),16+CHA|Haste,13+CHA|See Invisibility,12+CHA|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=21|Cone of Cold,15+CHA|Finger of Death,17+CHA|Plane Shift,17+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=21|Confusion,14+CHA|Hold Monster,15+CHA|Invisibility,12+CHA
- **KIT:** 1|CE

### Nightshade (Nightwing)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Fly,60
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|18|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX,INT,CHA|8
- **BONUS:** STAT|WIS|10
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Concentration|Diplomacy|Hide|Listen|Move Silently|Search|Sense Motive|Spellcraft|Spot|Survival
- **AUTO:** LANG|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Immunity to Cold|Nightshade Shared ~ Aversion to Daylight|Nightshade Shared ~ Desecrating Aura|Nightwing ~ Magic Drain|Nightwing ~ Natural Weapons|Nightwing ~ Skills|Nightwing ~ Spell-Like Abilities|Nightwing ~ Summon Undead|Telepathy
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.MagicDrain,*1,2d6
- **SR:** 27
- **DR:** 15/Silver and Magic
- **MONSTERCLASS:** Undead:17
- **RACETYPE:** Undead
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 25,34
- **CR:** 14
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=17|Contagion,14+CHA|Deeper Darkness,13+CHA|Detect Magic,10+CHA|Haste,13+CHA|See Invisibility,12+CHA|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=17|Cone of Cold,15+CHA|Finger of Death,17+CHA|Plane Shift,17+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=17|Confusion,14+CHA|Dispel Magic (Greater),16+CHA|Hold Monster,15+CHA|Invisibility,12+CHA
- **KIT:** 1|CE

### Nymph

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|CHA|TYPE=Deflection
- **BONUS:** PCLEVEL|Druid|6
- **BONUS:** STAT|DEX,INT,WIS|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|WildEmpathy|6|TYPE=Racial
- **BONUS:** VAR|StunningGlance,BlindingBeauty|13+CHA
- **MONCSKILL:** Concentration|Diplomacy|Escape Artist|Handle Animal|Heal|Hide|Listen|Move Silently|Ride|Sense Motive|Spot|Swim|Use Rope
- **AUTO:** LANG|Common|Sylvan
- **AUTO:** WEAPONPROF|Dagger|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Nymph ~ Blinding Beauty|Nymph ~ Skills|Nymph ~ Spell-Like Abilities|Nymph ~ Spells|Nymph ~ Stunning Glance|Nymph ~ Unearthly Grace|Nymph ~ Wild Empathy
- **LEGS:** 2
- **DR:** 10/Cold Iron
- **MONSTERCLASS:** Fey:6
- **RACETYPE:** Fey
- **HITDICEADVANCEMENT:** 12
- **LEVELADJUSTMENT:** 7
- **CR:** 7
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=7|Dimension Door,14+WIS
- **ADD:** SPELLCASTER|Druid
- **BONUS:** SAVE|Fortitude,Reflex,Will|CHA|TYPE=Racial

### Ogre

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Dwarven,Goblin,Orc,Terran
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT,CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Listen|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Common|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Greatclub|Javelin|TYPE=Martial|TYPE=Simple
- **LEGS:** 2
- **MONSTERCLASS:** Giant:4
- **RACETYPE:** Giant
- **LEVELADJUSTMENT:** 3
- **CR:** 3

### Ogre (Merrow)

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Swim,40,Walk,30
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Dwarven,Goblin,Orc,Terran
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT,CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Climb|Listen|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Common|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Longspear|Javelin|TYPE=Martial|TYPE=Simple
- **LEGS:** 2
- **MONSTERCLASS:** Giant:4
- **RACETYPE:** Giant
- **RACESUBTYPE:** Aquatic
- **LEVELADJUSTMENT:** 3
- **CR:** 3

### Ogre Mage

- **FAVCLASS:** Sorcerer
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Fly,40
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Dwarven,Goblin,Infernal,Orc
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CON,CHA|6
- **BONUS:** STAT|INT,WIS|4
- **BONUS:** VAR|DarkvisionRange|90
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Concentration|Listen|Spellcraft|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light
- **AUTO:** LANG|Common|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Greatsword|Longbow|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Ogre Mage ~ Flight|Ogre Mage ~ Regeneration|Ogre Mage ~ Spell-Like Abilities
- **LEGS:** 2
- **SR:** 19
- **MONSTERCLASS:** Giant:5
- **RACETYPE:** Giant
- **LEVELADJUSTMENT:** 7
- **CR:** 8
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=9|Darkness,12+CHA|Invisibility,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=9|Charm Person,11+CHA|Cone of Cold,15+CHA|Gaseous Form,13+CHA|Polymorph,14+CHA|Sleep,11+CHA

### Ooze (Black Pudding)

- **SIZE:** H
- **MOVE:** Walk,20,Climb,20
- **FACE:** 15
- **REACH:** 10
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX,WIS,CHA|-9
- **BONUS:** STAT|CON|12
- **BONUS:** VAR|BlindsightRange|60
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb
- **ABILITY:** Special Ability|AUTOMATIC|Black Pudding ~ Acid|Black Pudding ~ Constrict|Black Pudding ~ Improved Grab|Black Pudding ~ Skills|Black Pudding ~ Split
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Acid,*1,2d6
- **MONSTERCLASS:** Ooze:10
- **RACETYPE:** Ooze
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 15,30
- **CR:** 7
- **KIT:** 1|TN

### Ooze (Gelatinous Cube)

- **SIZE:** H
- **MOVE:** Walk,15
- **FACE:** 15
- **REACH:** 10
- **BONUS:** STAT|DEX,WIS,CHA|-9
- **BONUS:** STAT|CON|16
- **BONUS:** VAR|BlindsightRange|60
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|Gelatinous Cube ~ Acid|Gelatinous Cube ~ Engulf|Gelatinous Cube ~ Paralysis|Gelatinous Cube ~ Transparent|Immunity to Electricity
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Acid,*1,1d6
- **MONSTERCLASS:** Ooze:4
- **RACETYPE:** Ooze
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 12,24
- **CR:** 3
- **KIT:** 1|TN

### Ooze (Gray)

- **SIZE:** M
- **MOVE:** Walk,10
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX,WIS,CHA|-9
- **BONUS:** STAT|CON|10
- **BONUS:** VAR|BlindsightRange|60
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|Gray Ooze ~ Acid|Gray Ooze ~ Constrict|Gray Ooze ~ Improved Grab|Gray Ooze ~ Transparent|Immunity to Cold|Immunity to Fire
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Acid,*1,1d6
- **MONSTERCLASS:** Ooze:3
- **RACETYPE:** Ooze
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 6,9
- **CR:** 4
- **KIT:** 1|TN

### Ooze (Ochre Jelly)

- **SIZE:** L
- **MOVE:** Walk,10,Climb,10
- **FACE:** 10
- **REACH:** 5
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX,WIS,CHA|-9
- **BONUS:** STAT|CON|12
- **BONUS:** VAR|BlindsightRange|60
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb
- **ABILITY:** Special Ability|AUTOMATIC|Ochre Jelly ~ Acid|Ochre Jelly ~ Constrict|Ochre Jelly ~ Improved Grab|Ochre Jelly ~ Skills|Split
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Acid,*1,2d4
- **MONSTERCLASS:** Ooze:6
- **RACETYPE:** Ooze
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 9,18
- **CR:** 5
- **KIT:** 1|TN

### Otyugh

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|CON,WIS|2
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Hide|Listen|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Otyugh ~ Constrict|Otyugh ~ Disease|Otyugh ~ Improved Grab|Otyugh ~ Skills|Scent
- **LEGS:** 3
- **HANDS:** 3
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Reach.Finesseable.Bludgeoning,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Aberration:6
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 8,18
- **CR:** 4

### Owl (Giant)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Fly,70
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen|8|TYPE=Racial
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|4
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Knowledge (Nature)|Listen|Move Silently|Spot
- **AUTO:** LANG|Common|Sylvan
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Giant Owl ~ Skills|Giant Owl ~ Superior Low-Light Vision
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 8,12
- **LEVELADJUSTMENT:** 3
- **CR:** 3

### Owlbear

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|10
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|INT|-8
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Owlbear ~ Improved Grab|Scent
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:5
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 8,15
- **CR:** 4
- **KIT:** 1|TN

### Pegasus

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60,Fly,120
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS,CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Diplomacy|Listen|Sense Motive|Spot
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Pegasus ~ Skills|Pegasus ~ Spell-Like Abilities|Scent
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 8
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=5|Detect Evil (60 ft. radius),11+CHA|Detect Good (60 ft. radius),11+CHA

### Phantom Fungus

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Move Silently|5|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-2
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Phantom Fungus ~ Greater Invisibility|Phantom Fungus ~ Skills
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Plant:2
- **RACETYPE:** Plant
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 3
- **KIT:** 1|TN

### Phase Spider

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Climb,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR,DEX,CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Phase Spider ~ Ethereal Jaunt|Phase Spider ~ Poison|Phase Spider ~ Skills
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d6
- **MONSTERCLASS:** Magical Beast:5
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 8,15
- **CR:** 5
- **KIT:** 1|TN

### Phasm

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX,CON,WIS,CHA|4
- **BONUS:** STAT|INT|6
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Climb|Diplomacy|Disguise|Intimidate|Listen|Spot|Survival|TYPE=Craft|TYPE=Knowledge
- **AUTO:** LANG|Common|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Phasm ~ Alternate Form|Phasm ~ Amorphous|Phasm ~ Resilient|Phasm ~ Skills|Phasm ~ Tremorsense|Scent|Telepathy
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d3
- **MONSTERCLASS:** Aberration:15
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Shapechanger
- **HITDICEADVANCEMENT:** 15,21,45
- **CR:** 7
- **BONUS:** SAVE|Fortitude,Reflex|4|TYPE=Racial

### Pseudodragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,15,Fly,60
- **FACE:** 2.5
- **REACH:** 2
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON,WIS|2
- **BONUS:** VAR|BlindsenseRange|60|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,-STR)
- **MONCSKILL:** Hide|Listen|Search|Sense Motive|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **AUTO:** LANG|Telepathy
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Immunity to Paralysis|Immunity to Sleep|Pseudodragon ~ Blindsense|Pseudodragon ~ Poison|Pseudodragon ~ Skills|Pseudodragon ~ Telepathy
- **LEGS:** 4
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Reach.Piercing.Poison,*1,1d3|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1
- **SR:** 19
- **MONSTERCLASS:** Dragon:2
- **RACETYPE:** Dragon
- **HITDICEADVANCEMENT:** 4
- **LEVELADJUSTMENT:** 3
- **CR:** 1
- **KIT:** 1|NG

### Purple Worm

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** G
- **MOVE:** Walk,20,Burrow,20,Swim,10
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX|-4
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS,CHA|-2
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Listen|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Purple Worm ~ Improved Grab|Purple Worm ~ Poison|Purple Worm ~ Skills|Purple Worm ~ Swallow Whole
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d6
- **MONSTERCLASS:** Magical Beast:16
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 32,48
- **CR:** 12
- **KIT:** 1|TN

### Rakshasa

- **FAVCLASS:** Sorcerer
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Sylvan,Undercommon
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Sorcerer|6
- **BONUS:** SKILL|Bluff,Disguise|4|TYPE=Racial
- **BONUS:** STAT|STR,INT,WIS|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON,CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Move Silently|Perform (Oratory)|Sense Motive|Spellcraft|Spot
- **AUTO:** LANG|Common|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Rakshasa ~ Change Shape|Rakshasa ~ Detect Thoughts|Rakshasa ~ Skills|Rakshasa ~ Spells
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **SR:** 27
- **DR:** 15/Good and Piercing
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Native
- **LEVELADJUSTMENT:** 7
- **CR:** 10
- **ADD:** SPELLCASTER|Sorcerer
- **KIT:** 1|LE

### Rast

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,5,Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX,CON,WIS,CHA|2
- **BONUS:** STAT|INT|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Immunity to Fire|Rast ~ Blood Drain|Rast ~ Flight|Rast ~ Improved Grab|Rast ~ Paralyzing Gaze|Vulnerability to Cold
- **LEGS:** 0
- **HANDS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*4,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Outsider:4
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Fire
- **HITDICEADVANCEMENT:** 6,12
- **CR:** 5

### Ravid

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON,WIS|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Escape Artist|Hide|Listen|Move Silently|Spot|Survival|Use Rope
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Immunity to Fire|Ravid ~ Animate Objects|Ravid ~ Feats|Ravid ~ Flight|Ravid ~ Positive Energy Lash
- **LEGS:** 0
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning.PositiveEnergy,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.PositiveEnergy,*1,1d4
- **NATURALATTACKS:** Tail Touch,Weapon.Natural.Melee.Touch.PositiveEnergy,*1,1d0
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 4,9
- **CR:** 5
- **KIT:** 1|TN

### Remorhaz

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Burrow,20
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen|4|TYPE=Racial
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Remorhaz ~ Heat|Remorhaz ~ Improved Grab|Remorhaz ~ Skills|Remorhaz ~ Swallow Whole
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **MONSTERCLASS:** Magical Beast:7
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 14,21
- **CR:** 7

### Roc

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** G
- **MOVE:** Walk,20,Fly,80
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Roc ~ Skills
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **MONSTERCLASS:** Animal:18
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 32,54
- **CR:** 9
- **KIT:** 1|TN

### Roper

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,INT,CHA|2
- **BONUS:** STAT|CON,WIS|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Listen|Spot
- **AUTO:** LANG|Terran|Undercommon
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Electricity|Resistance to Cold|Roper ~ Drag|Roper ~ Skills|Roper ~ Strands|Roper ~ Weakness|Vulnerability to Fire
- **LEGS:** 1
- **HANDS:** 7
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Slashing,*1,2d6
- **NATURALATTACKS:** Strand,Weapon.Natural.Ranged.Touch.Drag.Reach,*6,1d0
- **SR:** 30
- **MONSTERCLASS:** Magical Beast:10
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 15,30
- **CR:** 12

### Rust Monster

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON,WIS|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Rust Monster ~ Rust|Scent
- **LEGS:** 4
- **NATURALATTACKS:** Antennae,Weapon.Natural.Melee.Finesseable.Touch.Rust,*1,1d0|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Aberration:5
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 8,15
- **CR:** 3
- **KIT:** 1|TN

### Sahuagin

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,60
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Aquan,Common
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|BlindsenseRange|30|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Handle Animal|Hide|Listen|Profession (Hunter)|Ride|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Multiattack
- **AUTO:** LANG|Sahuagin
- **AUTO:** WEAPONPROF|Crossbow (Heavy)|Trident|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Sahuagin ~ Blindsense|Sahuagin ~ Blood Frenzy|Sahuagin ~ Freshwater Sensitivity|Sahuagin ~ Light Blindness|Sahuagin ~ Rake|Sahuagin ~ Skills|Sahuagin ~ Speak With Sharks|Sahuagin ~ Water Dependent
- **LEGS:** 2
- **HANDS:** 5
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Monstrous Humanoid:2
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 5,10
- **LEVELADJUSTMENT:** 3
- **CR:** 2

### Sahuagin (Mutant)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,60
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Aquan,Common
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|BlindsenseRange|30|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Handle Animal|Hide|Listen|Profession (Hunter)|Ride|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Multiattack
- **AUTO:** LANG|Sahuagin
- **AUTO:** WEAPONPROF|Crossbow (Heavy)|Trident|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Sahuagin ~ Blindsense|Sahuagin ~ Blood Frenzy|Sahuagin ~ Freshwater Sensitivity|Sahuagin ~ Light Blindness|Sahuagin ~ Rake|Sahuagin ~ Skills|Sahuagin ~ Speak With Sharks|Sahuagin ~ Water Dependent
- **LEGS:** 2
- **HANDS:** 9
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*4,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Monstrous Humanoid:2
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 5,10
- **LEVELADJUSTMENT:** 3
- **CR:** 2

### Sahuagin (Malenti)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,40
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Aquan,Common
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|BlindsenseRange|30|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Handle Animal|Hide|Listen|Profession (Hunter)|Ride|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Multiattack
- **AUTO:** LANG|Sahuagin
- **AUTO:** WEAPONPROF|Crossbow (Heavy)|Trident|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Malenti ~ Light Sensitivity|Sahuagin ~ Blindsense|Sahuagin ~ Blood Frenzy|Sahuagin ~ Freshwater Sensitivity|Sahuagin ~ Skills|Sahuagin ~ Speak With Sharks|Sahuagin ~ Water Dependent
- **LEGS:** 2
- **HANDS:** 2
- **MONSTERCLASS:** Monstrous Humanoid:2
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 5,10
- **LEVELADJUSTMENT:** 3
- **CR:** 2

### Salamander (Average)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** SKILL|Craft (Blacksmithing)|4|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Tail|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Craft (Blacksmithing)|Diplomacy|Disguise|Hide|Intimidate|Listen|Move Silently|Search|Spot
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|Spear|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Salamander ~ Constrict|Salamander ~ Feats|Salamander ~ Heat|Salamander ~ Improved Grab|Salamander ~ Natural Weapons|Salamander ~ Skills|Salamander ~ Spell-Like Abilities
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*1,2d6
- **DR:** 10/Magic
- **MONSTERCLASS:** Outsider:9
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Fire
- **HITDICEADVANCEMENT:** 14
- **LEVELADJUSTMENT:** 5
- **CR:** 6

### Salamander (Flamebrother)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** SKILL|Craft (Blacksmithing)|4|TYPE=Racial
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Tail|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Craft (Blacksmithing)|Hide|Listen|Move Silently|Spot
- **AUTO:** LANG|Ignan
- **AUTO:** WEAPONPROF|Spear|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Salamander ~ Constrict|Salamander ~ Feats|Salamander ~ Heat|Salamander ~ Improved Grab|Salamander ~ Natural Weapons|Salamander ~ Skills|Salamander ~ Spell-Like Abilities
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*1,1d4
- **MONSTERCLASS:** Outsider:4
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Fire
- **HITDICEADVANCEMENT:** 6
- **LEVELADJUSTMENT:** 4
- **CR:** 3

### Salamander (Noble)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Craft (Blacksmithing)|4|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Tail|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Craft (Blacksmithing)|Diplomacy|Hide|Intimidate|Listen|Move Silently|Spot
- **AUTO:** LANG|Common|Ignan
- **AUTO:** WEAPONPROF|Longspear|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Salamander ~ Constrict|Salamander ~ Feats|Salamander ~ Heat|Salamander ~ Improved Grab|Salamander ~ Natural Weapons|Salamander ~ Skills|Salamander ~ Spell-Like Abilities
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*1,2d8
- **DR:** 15/Magic
- **MONSTERCLASS:** Outsider:15
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Fire
- **HITDICEADVANCEMENT:** 21,45
- **CR:** 10

### Satyr

- **FAVCLASS:** Bard
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Common,Elven,Gnome
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Listen,Move Silently,Spot|4|TYPE=Racial
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** WEAPONPROF=Head butt|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Hide|Intimidate|Knowledge (Nature)|Listen|Move Silently|Perform (Wind Instruments)|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Alertness
- **AUTO:** LANG|Sylvan
- **AUTO:** WEAPONPROF|Dagger|Shortbow|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Satyr ~ Pipes|Satyr ~ Skills
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Head butt,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **DR:** 5/Cold Iron
- **MONSTERCLASS:** Fey:5
- **RACETYPE:** Fey
- **HITDICEADVANCEMENT:** 10
- **LEVELADJUSTMENT:** 3
- **CR:** 2

### Sea Cat

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Swim,40
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Listen|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Sea Cat ~ Hold Breath|Sea Cat ~ Rend|Sea Cat ~ Skills
- **LEGS:** 0
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:6
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 9,18
- **CR:** 4

### Shadow

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Fly,40
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** CE
- **BONUS:** SKILL|Search|4|TYPE=Racial
- **BONUS:** SKILL|Listen,Spot|2|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** VAR|TurnResistBonus|2
- **MONCSKILL:** Hide|Listen|Search|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability
- **ABILITY:** Special Ability|VIRTUAL|Shadow ~ Create Spawn
- **ABILITY:** Special Ability|AUTOMATIC|Shadow ~ Skills|Shadow ~ Strength Damage|Turn Resistance
- **LEGS:** 0
- **NATURALATTACKS:** Incorporeal touch,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d6
- **DEFINE:** ShadowSpawnBlock|0
- **MONSTERCLASS:** Undead:3
- **RACETYPE:** Undead
- **RACESUBTYPE:** Incorporeal
- **HITDICEADVANCEMENT:** 9
- **CR:** 3

### Shadow Mastiff

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Track
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Shadow ~ Skills Mastiff|Shadow Mastiff ~ Bay|Shadow Mastiff ~ Shadow Blend|Shadow Mastiff ~ Trip
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Outsider:4
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 6,12
- **LEVELADJUSTMENT:** 3
- **CR:** 5

### Shambling Mound

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Swim,20
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Listen,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Hide|Listen|Move Silently
- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Fire|Shambling Mound ~ Constrict|Shambling Mound ~ Immunity to Electricity|Shambling Mound ~ Improved Grab|Shambling Mound ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **MONSTERCLASS:** Plant:8
- **RACETYPE:** Plant
- **HITDICEADVANCEMENT:** 12,24
- **LEVELADJUSTMENT:** 6
- **CR:** 6

### Shield Guardian

- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|FastHealing|5
- **ABILITY:** Special Ability|AUTOMATIC|Fast Healing 5|Shield Guardian ~ Find Master|Shield Guardian ~ Guard|Shield Guardian ~ Shield Other|Shield Guardian ~ Spell Storing
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d8
- **MONSTERCLASS:** Construct (Mindless):15
- **RACETYPE:** Construct
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 24,45
- **CR:** 8

### Shocker Lizard

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,40,Climb,20,Swim,20
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** SKILL|Listen,Spot|2|TYPE=Racial
- **BONUS:** SKILL|Climb,Jump|max(STR,DEX)-STR
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Listen|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Electricity|Shocker Lizard ~ Electricity Sense|Shocker Lizard ~ Lethal Shock|Shocker Lizard ~ Skills|Shocker Lizard ~ Stunning Shock
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Magical Beast:2
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 2

### Skeleton (Human Warrior)

- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Claw|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** SHIELDPROF|SHIELDTYPE=Heavy
- **AUTO:** WEAPONPROF|Scimitar|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):1
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 1/3

### Skeleton (Wolf)

- **SIZE:** M
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):2
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 3,6
- **CR:** 1

### Skeleton (Owlbear)

- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):5
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 8,15
- **CR:** 2

### Skeleton (Troll)

- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):6
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 3

### Skeleton (Chimera)

- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **NATURALATTACKS:** Second Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):9
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 13,27
- **CR:** 4

### Skeleton (Ettin)

- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):10
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 5

### Skeleton (Advanced Megaraptor)

- **SIZE:** H
- **MOVE:** Walk,60
- **FACE:** 15
- **REACH:** 10
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):12
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 16,20
- **CR:** 6

### Skeleton (Cloud Giant)

- **SIZE:** H
- **MOVE:** Walk,50
- **FACE:** 15
- **REACH:** 15
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Claw|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Cloud Giant ~ Oversized Weapon|Immunity to Cold
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d8
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):17
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 7

### Skeleton (Young Adult Red Dragon)

- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 10
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold|Immunity to Fire
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Wing,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d8|Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead (Mindless):19
- **RACETYPE:** Undead
- **RACESUBTYPE:** Fire
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 0
- **CR:** 8

### Skum

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Swim,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Hide|Listen|Move Silently|Spot|Swim
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Amphibious|Skum ~ Rake|Skum ~ Skills
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Aberration:2
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 4,6
- **LEVELADJUSTMENT:** 3
- **CR:** 2

### Slaad (Red)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|-4
- **BONUS:** STAT|CHA|-2
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Red Slaad
- **NATURALATTACKS:** Bite,Natural.Melee.Weapon,*1,2d8|Claws,Natural.Melee.Weapon,*2,1d4
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar
- **HITDICEADVANCEMENT:** 10,21

### Slaad (Blue)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|-4
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Blue Slaad
- **NATURALATTACKS:** Claws,Natural.Melee.Weapon,*4,2d6|Bite,Natural.Melee.Weapon,*1,2d8
- **MONSTERCLASS:** Outsider:8
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar
- **HITDICEADVANCEMENT:** 12,24

### Slaad (Green)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|CHA|2
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Green Slaad
- **NATURALATTACKS:** Claws,Natural.Melee.Weapon,*2,1d6|Bite,Natural.Melee.Weapon,*1,2d8
- **MONSTERCLASS:** Outsider:9
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar
- **HITDICEADVANCEMENT:** 15,27

### Slaad (Gray)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|4
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Gray Slaad
- **NATURALATTACKS:** Claws,Natural.Melee.Weapon,*2,2d4|Bite,Natural.Melee.Weapon,*1,2d8
- **MONSTERCLASS:** Outsider:10
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar
- **HITDICEADVANCEMENT:** 15,30

### Slaad (Death)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|12
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|8
- **BONUS:** STAT|WIS|8
- **BONUS:** STAT|CHA|8
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Death Slaad
- **NATURALATTACKS:** Claws,Natural.Melee.Weapon,*2,3d6|Bite,Natural.Melee.Weapon,*1,2d10
- **MONSTERCLASS:** Outsider:15
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar
- **HITDICEADVANCEMENT:** 22,45

### Spectre

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Fly,80
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** LE
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** VAR|EnergyDrainLevels|2
- **MONCSKILL:** Hide|Intimidate|Knowledge (Religion)|Listen|Search|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Spectre ~ Create Spawn|Spectre ~ Energy Drain|Spectre ~ Sunlight Powerlessness|Spectre ~ Unnatural Aura|Turn Resistance
- **LEGS:** 0
- **NATURALATTACKS:** Incorporeal touch,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Undead:7
- **RACETYPE:** Undead
- **RACESUBTYPE:** Incorporeal
- **HITDICEADVANCEMENT:** 14
- **CR:** 7

### Sphinx (Androsphinx)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50,Fly,80
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** CG
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** PCLEVEL|Cleric|6
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Intimidate|Listen|Spot|Survival|TYPE=Knowledge
- **AUTO:** LANG|Common|Draconic|Sphinx
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Androsphinx ~ Rake|Androsphinx ~ Roar|Androsphinx ~ Spells|Sphinx ~ Pounce|Sphinx ~ Rake
- **LEGS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4
- **MONSTERCLASS:** Magical Beast:12
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 18,36
- **LEVELADJUSTMENT:** 5
- **CR:** 9
- **ADD:** SPELLCASTER|Cleric

### Sphinx (Criosphinx)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,60
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|CON|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Intimidate|Listen|Spot
- **AUTO:** LANG|Common|Draconic|Sphinx
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Criosphinx ~ Rake|Sphinx ~ Pounce|Sphinx ~ Rake
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Magical Beast:10
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 15,30
- **LEVELADJUSTMENT:** 3
- **CR:** 7

### Sphinx (Gynosphinx)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Fly,60
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|8
- **BONUS:** STAT|WIS|8
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Intimidate|Listen|Sense Motive|Spot
- **AUTO:** LANG|Common|Draconic|Sphinx
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Gynosphinx ~ Rake|Gynosphinx ~ Spell-Like Abilities|Sphinx ~ Pounce|Sphinx ~ Rake
- **LEGS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Magical Beast:8
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 12,24
- **LEVELADJUSTMENT:** 4
- **CR:** 8
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=14|Comprehend Languages,11+CHA|Dispel Magic,13+CHA|Legend Lore,16+CHA|Locate Object,14+CHA|Remove Curse,14+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=14|Clairaudience/Clairvoyance,13+CHA|Detect Magic,10+CHA|Read Magic,10+CHA|See Invisibility,12+CHA

### Sphinx (Hieracosphinx)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,90
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Common|Draconic|Sphinx
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Hieracosphinx ~ Rake|Hieracosphinx ~ Skills|Sphinx ~ Pounce|Sphinx ~ Rake
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d10|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 14,27
- **LEVELADJUSTMENT:** 5
- **CR:** 5

### Spider Eater

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,60
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Scent|Spider Eater ~ Freedom of Movement|Spider Eater ~ Implant|Spider Eater ~ Poison|Spider Eater ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 4,12
- **CR:** 5

### Sprite (Grig)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,20,Fly,40
- **FACE:** 2.5
- **REACH:** 0
- **PREALIGN:** NG
- **LANGBONUS:** Common
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Search,Spot|2|TYPE=Racial
- **BONUS:** SKILL|Jump|8|TYPE=Racial
- **BONUS:** STAT|STR|-6
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Escape Artist|Hide|Jump|Listen|Move Silently|Perform (String Instruments)|Search|Spot|TYPE=Craft
- **ABILITY:** FEAT|AUTOMATIC|Dodge
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **AUTO:** LANG|Sylvan
- **AUTO:** WEAPONPROF|Longbow|Sword (Short)|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Grig ~ Fiddle|Grig ~ Skills|Grig ~ Spell-Like Abilities|SPRITE ~ Skills
- **LEGS:** 4
- **SR:** 17
- **DR:** 5/Cold Iron
- **MONSTERCLASS:** Fey:1
- **RACETYPE:** Fey
- **TEMPLATE:** Half Hitdie
- **HITDICEADVANCEMENT:** 3
- **LEVELADJUSTMENT:** 3
- **CR:** 1
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=9|Disguise Self,11+CHA|Entangle,11+CHA|Invisibility,12+CHA|Pyrotechnics,12+CHA|Ventriloquism,11+CHA
- **INFO:** DESC|This tiny being has a humanoid head, torso, and arms, with the wings, antennae, and legs of a cricket. Grigs are mischievous and lighthearted. They have no fear of larger creatures and delight in playing tricks on them. Favorite pranks include stealing food, collapsing tents, and using ventriloquism to make objects talk. Grigs can leap great distances. They have light blue skin, forestgreen hair, and brown hairy legs, and usually wear tunics or brightly colored vests with buttons made from tiny gems. A grig stands 1-1/2 feet tall and weighs about 1 pound. Grigs are fierce by sprite standards, attacking opponents fearlessly with bow and dagger. (ECL 3)

### Sprite (Nixie)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Swim,30
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** SKILL|Listen,Search,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|8
- **MONCSKILL:** Bluff|Escape Artist|Handle Animal|Hide|Listen|Perform (Sing)|Search|Sense Motive|Spot|Swim|TYPE=Craft
- **ABILITY:** FEAT|AUTOMATIC|Dodge
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **AUTO:** LANG|Aquan|Sylvan
- **AUTO:** WEAPONPROF|Crossbow (Light)|Sword (Short)|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Amphibious|Nixie ~ Charm Person|Nixie ~ Skills|Nixie ~ Water Breathing|Nixie ~ Wild Empathy|SPRITE ~ Skills
- **LEGS:** 2
- **SR:** 16
- **DR:** 5/Cold Iron
- **MONSTERCLASS:** Fey:1
- **RACETYPE:** Fey
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 3
- **LEVELADJUSTMENT:** 3
- **CR:** 1

### Sprite (Pixie)

- **FAVCLASS:** Sorcerer
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Fly,60
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** NG
- **LANGBONUS:** Elven,Gnome,Halfling
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Search,Spot|2|TYPE=Racial
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Bluff|Concentration|Escape Artist|Hide|Listen|Move Silently|Ride|Search|Sense Motive|Spot
- **ABILITY:** FEAT|AUTOMATIC|Dodge
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **AUTO:** LANG|Common|Sylvan
- **AUTO:** WEAPONPROF|Longbow|Sword (Short)|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Pixie ~ Greater Invisibility|Pixie ~ Special Arrows|Pixie ~ Spell-Like Abilities|SPRITE ~ Skills
- **LEGS:** 2
- **SR:** 15
- **DR:** 10/Cold Iron
- **MONSTERCLASS:** Fey:1
- **RACETYPE:** Fey
- **TEMPLATE:** CHOOSE:Pixie Ability (Otto's Irresistible Dance)|Unable to use Otto's Irresistible Dance
- **HITDICEADVANCEMENT:** 3
- **LEVELADJUSTMENT:** 4
- **CR:** 4
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=8|Confusion (Lesser),11+CHA|Dancing Lights,10+CHA|Detect Chaos,11+CHA|Detect Evil,11+CHA|Detect Good,11+CHA|Detect Law,11+CHA|Detect Thoughts,12+CHA|Dispel Magic,13+CHA|Entangle,11+CHA|Permanent Image,16+CHA

### Stirge

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,10,Fly,40
- **FACE:** 2.5
- **REACH:** 0
- **PREALIGN:** TN
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **BONUS:** WEAPONPROF=Touch|DAMAGE|-1*(STR)
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Stirge ~ Attach|Stirge ~ Blood Drain
- **LEGS:** 4
- **NATURALATTACKS:** Touch,Weapon.Natural.Melee.Finesseable.Piercing,*1,Attach
- **MONSTERCLASS:** Magical Beast:1
- **RACETYPE:** Magical Beast
- **CR:** 1/2

### Swarm (Bat)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** D
- **MOVE:** Walk,5,Fly,40
- **FACE:** 10
- **REACH:** 0
- **PREALIGN:** TN
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|BlindsenseRange|20|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Swarm|DAMAGE|-1*(STR)
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Bat Swarm ~ Blindsense|Bat Swarm ~ Distraction|Bat Swarm ~ Skills|Bat Swarm ~ Wounding
- **LEGS:** 0
- **NATURALATTACKS:** Swarm,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **RACESUBTYPE:** Swarm
- **CR:** 2

### Swarm (Centipede)

- **SIZE:** D
- **MOVE:** Walk,20,Climb,20
- **FACE:** 10
- **REACH:** 0
- **PREALIGN:** TN
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|-2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Swarm|DAMAGE|-1*(STR)
- **MONCSKILL:** Climb|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Centipede Swarm ~ Distraction|Centipede Swarm ~ Poison|Centipede Swarm ~ Skills
- **LEGS:** 0
- **NATURALATTACKS:** Swarm,Weapon.Natural.Melee.Finesseable.Bludgeoning.Poison,*1,2d6
- **MONSTERCLASS:** Vermin:9
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Swarm
- **RACESUBTYPE:** Mindless
- **CR:** 4

### Swarm (Hellwasp)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** D
- **MOVE:** Walk,5,Fly,40
- **FACE:** 10
- **REACH:** 0
- **PREALIGN:** LE
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|12
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** WEAPONPROF=Swarm|DAMAGE|-1*(STR)
- **MONCSKILL:** Hide|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Hellwasp Swarm ~ Distraction|Hellwasp Swarm ~ Hive Mind|Hellwasp Swarm ~ Inhabit|Hellwasp Swarm ~ Natural Weapons|Hellwasp Swarm ~ Poison|Resistance to Fire
- **LEGS:** 0
- **NATURALATTACKS:** Swarm,Weapon.Natural.Melee.Finesseable.Bludgeoning.Poison,*1,3d6
- **DR:** 10/Magic
- **MONSTERCLASS:** Magical Beast:12
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Swarm|Extraplanar|Evil
- **CR:** 8

### Swarm (Locust)

- **SIZE:** D
- **MOVE:** Walk,10,Fly,30
- **FACE:** 10
- **REACH:** 0
- **PREALIGN:** TN
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|-2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **BONUS:** WEAPONPROF=Swarm|DAMAGE|-1*(STR)
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Locust Swarm ~ Distraction|Locust Swarm ~ Skills
- **LEGS:** 0
- **NATURALATTACKS:** Swarm,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Vermin:6
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Swarm
- **RACESUBTYPE:** Mindless
- **CR:** 3

### Swarm (Rat)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,15,Climb,15
- **FACE:** 10
- **REACH:** 0
- **PREALIGN:** TN
- **BONUS:** SKILL|Balance,Swim|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** SKILL|Swim,Climb|max(STR,DEX)-STR
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Swarm|DAMAGE|-1*(STR)
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Rat Swarm ~ Disease|Rat Swarm ~ Distraction|Rat Swarm ~ Skills|Scent
- **LEGS:** 0
- **NATURALATTACKS:** Swarm,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Animal:4
- **RACETYPE:** Animal
- **RACESUBTYPE:** Swarm
- **CR:** 2

### Swarm (Spider)

- **SIZE:** D
- **MOVE:** Walk,20,Climb,20
- **FACE:** 10
- **REACH:** 0
- **PREALIGN:** TN
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Swarm|DAMAGE|-1*(STR)
- **MONCSKILL:** Climb|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Spider Swarm ~ Distraction|Spider Swarm ~ Poison|Spider Swarm ~ Skills
- **LEGS:** 0
- **NATURALATTACKS:** Swarm,Weapon.Natural.Melee.Finesseable.Bludgeoning.Poison,*1,1d6
- **MONSTERCLASS:** Vermin:2
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Swarm
- **RACESUBTYPE:** Mindless
- **CR:** 1

### Tarrasque

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** C
- **MOVE:** Walk,20
- **FACE:** 30
- **REACH:** 20
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|30|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|34
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|24
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|EnergyDrainLevels|1
- **MONCSKILL:** Listen|Search|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Ability Damage|Immunity to Disease|Immunity to Energy Drain|Immunity to Fire|Immunity to Poison|Scent|Tarrasque ~ Augmented Critical|Tarrasque ~ Carapace|Tarrasque ~ Frightful Presence|Tarrasque ~ Improved Grab|Tarrasque ~ Natural Weapons|Tarrasque ~ Regeneration|Tarrasque ~ Rush|Tarrasque ~ Skills|Tarrasque ~ Swallow Whole
- **LEGS:** 4
- **HANDS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d8|Horn,Weapon.Natural.Melee.Finesseable.Piercing,*2,1d10|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d12|Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,3d8
- **SR:** 32
- **DR:** 15/Epic
- **MONSTERCLASS:** Magical Beast:48
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 99
- **CR:** 20

### Tendriculos

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20
- **FACE:** 15
- **REACH:** 15
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|RegenerationRate|4
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Tendriculos ~ Improved Grab|Tendriculos ~ Regeneration|Tendriculos ~ Swallow Whole/Paralysis
- **LEGS:** 1
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Tendril,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Plant:9
- **RACETYPE:** Plant
- **HITDICEADVANCEMENT:** 16,27
- **CR:** 6

### Thoqqua

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Burrow,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Move Silently|Survival
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Thoqqua ~ Burn|Thoqqua ~ Heat
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Fire,*1,1d6
- **MONSTERCLASS:** Elemental (Earth/Water):3
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Earth|Extraplanar|Fire
- **HITDICEADVANCEMENT:** 3,9
- **CR:** 2

### Titan

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,60
- **FACE:** 15
- **REACH:** 15
- **PREALIGN:** CG,CN,CE
- **BONUS:** COMBAT|AC|19|TYPE=NaturalArmor
- **BONUS:** STAT|STR|32
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|28
- **BONUS:** STAT|INT|10
- **BONUS:** STAT|WIS|18
- **BONUS:** STAT|CHA|14
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Balance|Bluff|Climb|Concentration|Diplomacy|Disguise|Heal|Intimidate|Jump|Listen|Perform (Oratory)|Search|Sense Motive|Spellcraft|Spot|Survival|Swim|TYPE=Craft|TYPE=Knowledge
- **AUTO:** ARMORPROF|ARMORTYPE=Heavy|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Abyssal|Celestial|Common|Draconic|Giant
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Javelin|Warhammer|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Titan ~ Natural Weapons|Titan ~ Oversized Weapon|Titan ~ Spell-Like Abilities
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d8
- **SR:** 32
- **DR:** 15/Lawful
- **MONSTERCLASS:** Outsider:20
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Chaotic|Extraplanar
- **HITDICEADVANCEMENT:** 30,60
- **CR:** 21
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=20|Chain Lightning,16+CHA|Charm Monster,14+CHA|Cure Critical Wounds,14+CHA|Dispel Magic (Greater),16+CHA|Fire Storm,17+CHA|Hold Monster,15+CHA|Invisibility Purge,13+CHA|Invisibility,12+CHA|Levitate,12+CHA|Persistent Image,15+CHA|Polymorph,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=20|Gate,19+CHA|Maze,18+CHA|Meteor Swarm,19+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=20|Etherealness,19+CHA|Word of Chaos,15+CHA
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=20|Daylight,13+CHA|Holy Smite,14+CHA|Remove Curse,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=20|Restoration (Greater),17+CHA
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=20|Bestow Curse,14+CHA|Deeper Darkness,13+CHA|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=20|Crushing Hand,19+CHA

### Tojanida (Adult)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,10,Swim,90
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** SKILL|Search,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Diplomacy|Escape Artist|Hide|Knowledge (The Planes)|Listen|Search|Sense Motive|Spot|Survival|Swim|Use Rope
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Acid|Immunity to Cold|Resistance to Electricity|Resistance to Fire|Tojanida ~ All-Around Vision|Tojanida ~ Improved Grab|Tojanida ~ Ink Cloud|Tojanida ~ Skills
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Water
- **HITDICEADVANCEMENT:** 14
- **CR:** 5

### Tojanida (Elder)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Swim,90
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** SKILL|Search,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Escape Artist|Hide|Intimidate|Knowledge (The Planes)|Listen|Search|Sense Motive|Spot|Survival|Swim|Use Rope
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Acid|Immunity to Cold|Resistance to Electricity|Resistance to Fire|Tojanida ~ All-Around Vision|Tojanida ~ Improved Grab|Tojanida ~ Ink Cloud|Tojanida ~ Skills
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8
- **MONSTERCLASS:** Outsider:15
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Water
- **HITDICEADVANCEMENT:** 24,45
- **CR:** 9

### Tojanida (Juvenile)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,10,Swim,90
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** SKILL|Search,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **MONCSKILL:** Diplomacy|Escape Artist|Hide|Knowledge (The Planes)|Listen|Search|Sense Motive|Spot|Survival|Swim|Use Rope
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Acid|Immunity to Cold|Resistance to Electricity|Resistance to Fire|Tojanida ~ All-Around Vision|Tojanida ~ Improved Grab|Tojanida ~ Ink Cloud|Tojanida ~ Skills
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Water
- **HITDICEADVANCEMENT:** 6
- **CR:** 3

### Treant

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|2
- **MONCSKILL:** Diplomacy|Hide|Intimidate|Knowledge (Nature)|Listen|Sense Motive|Spot|Survival
- **AUTO:** LANG|Common|Sylvan|Treant
- **ABILITY:** Special Ability|AUTOMATIC|Treant ~ Animate Trees|Treant ~ Double Damage Against Objects|Treant ~ Skills|Treant ~ Trample|Vulnerability to Fire
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **DR:** 10/Slashing
- **MONSTERCLASS:** Plant:7
- **RACETYPE:** Plant
- **HITDICEADVANCEMENT:** 16,21
- **LEVELADJUSTMENT:** 5
- **CR:** 8

### Triton

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,5,Swim,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Diplomacy|Hide|Listen|Move Silently|Ride|Search|Sense Motive|Spot|Survival|Swim|TYPE=Craft
- **AUTO:** LANG|Aquan|Common
- **AUTO:** WEAPONPROF|Crossbow (Heavy)|Trident|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Triton ~ Skills|Triton ~ Spell-Like Abilities
- **LEGS:** 2
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Native|Water
- **HITDICEADVANCEMENT:** 9
- **LEVELADJUSTMENT:** 3
- **CR:** 2
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=7|Summon Nature's Ally IV,14+CHA

### Troglodyte

- **FAVCLASS:** Cleric
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Common,Giant,Goblin,Orc
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-2
- **BONUS:** VAR|DarkvisionRange|90|TYPE=Base
- **BONUS:** VAR|TrogStenchDC|11+CON
- **MONCSKILL:** Hide|Listen
- **ABILITY:** FEAT|AUTOMATIC|Multiattack
- **AUTO:** LANG|Draconic
- **AUTO:** WEAPONPROF|Club|Javelin|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Troglodyte ~ Skills|Troglodyte ~ Stench
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,1,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,1,1d4
- **MONSTERCLASS:** Humanoid (Fortitude):2
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Reptilian
- **LEVELADJUSTMENT:** 3
- **CR:** 1

### Troll

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Common,Orc
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|90|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Giant
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Troll ~ Regeneration|Troll ~ Rend
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Giant:6
- **RACETYPE:** Giant
- **LEVELADJUSTMENT:** 5
- **CR:** 5

### Troll (Scrag)

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Common,Orc
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|90|TYPE=Base
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Giant
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Troll ~ Regeneration|Troll ~ Rend
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Giant:6
- **RACETYPE:** Giant
- **LEVELADJUSTMENT:** 5
- **CR:** 5

### Umber Hulk

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Burrow,20
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|CHA|2
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Umber Hulk
- **NATURALATTACKS:** Claws,Natural.Melee.Weapon,*2,2d4|Bite,Natural.Melee.Weapon,*1,2d8
- **MONSTERCLASS:** Aberration:8
- **RACETYPE:** Aberration
- **HITDICEADVANCEMENT:** 12,24

### Unicorn

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR,CON,WIS|10
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|14
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Horn|DAMAGE,TOHIT|3|TYPE=Enhancement
- **MONCSKILL:** Jump|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Common|Sylvan
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Charm|Immunity to Compulsion|Immunity to Poison|Scent|Unicorn ~ Magic Circle against Evil|Unicorn ~ Skills|Unicorn ~ Spell-Like Abilities|Unicorn ~ Wild Empathy
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Horn,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8|Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 8
- **LEVELADJUSTMENT:** 4
- **CR:** 3
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=8|Detect Evil,11+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=5|Cure Light Wounds,11+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=5|Cure Moderate Wounds,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=8|Neutralize Poison,15+CHA|Teleport (Greater),17+CHA
- **KIT:** 1|CG

### Vampire Spawn

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Bluff,Hide,Listen,Move Silently,Search,Sense Motive,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX,CHA|4
- **BONUS:** STAT|INT,WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|EnergyDrainLevels|1
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Bluff|Climb|Diplomacy|Hide|Jump|Listen|Move Silently|Search|Sense Motive|Spot|TYPE=Craft|TYPE=Profession
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** FEAT|AUTOMATIC|Alertness|Improved Initiative|Lightning Reflexes
- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Cold|Resistance to Electricity|Turn Resistance|Vampire ~ Blood Drain Spawn|Vampire ~ Energy Drain Spawn|Vampire ~ Fast Healing Spawn|Vampire ~ Gaseous Form Spawn|Vampire ~ Spider Climb Spawn|Vampire ~ Vampire Weaknesses Spawn|Vampire Spawn ~ Domination|Vampire Spawn ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **DR:** 5/Silver
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **CR:** 4
- **KIT:** 1|CE|LE|NE

### Vargouille

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Fly,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|DEX,CON,WIS|2
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Intimidate|Listen|Move Silently|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **AUTO:** LANG|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Vargouille ~ Kiss|Vargouille ~ Natural Weapons|Vargouille ~ Poison|Vargouille ~ Shriek
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d4
- **MONSTERCLASS:** Outsider:1
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Evil|Extraplanar
- **HITDICEADVANCEMENT:** 3
- **CR:** 2
- **KIT:** 1|NE

### Wight

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Move Silently|8|TYPE=Racial
- **BONUS:** STAT|STR,DEX,WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|EnergyDrainLevels|1
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Wight ~ Create Spawn|Wight ~ Energy Drain|Wight ~ Skills
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **HITDICEADVANCEMENT:** 8
- **CR:** 3
- **KIT:** 1|LE

### Will-o'-Wisp

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Fly,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=Deflection
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|18
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|5
- **BONUS:** WEAPONPROF=Shock|DAMAGE|-1*(STR)
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Intimidate|Listen|Search|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **AUTO:** LANG|Auran|Common
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Will-O'-Wisp ~ Immunity to Magic|Will-O'-Wisp ~ Natural Invisibility
- **LEGS:** 0
- **NATURALATTACKS:** Shock,Weapon.Natural.Melee.Finesseable.Bludgeoning.Electricity,*1,2d8
- **MONSTERCLASS:** Aberration:9
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Air
- **HITDICEADVANCEMENT:** 18
- **CR:** 6

### Winter Wolf

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Move Silently,Spot|1|TYPE=Racial
- **BONUS:** SKILL|Hide|2|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|BreathWeaponCone|15
- **BONUS:** VAR|BreathWeaponDice|4
- **BONUS:** VAR|BreathWeaponDamageDie|6
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Common|Giant
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Winter Wolf ~ Breath Weapon|Winter Wolf ~ Freezing Bite|Winter Wolf ~ Skills|Winter Wolf ~ Trip
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Cold,*1,1d8
- **MONSTERCLASS:** Magical Beast:6
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Cold
- **HITDICEADVANCEMENT:** 9,18
- **LEVELADJUSTMENT:** 3
- **CR:** 5

### Worg

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen,Move Silently,Spot|1|TYPE=Racial
- **BONUS:** SKILL|Hide|2|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX,CON,WIS|4
- **BONUS:** STAT|INT|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Worg
- **ABILITY:** Special Ability|AUTOMATIC|Scent|Worg ~ Skills|Worg ~ Trip
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 6,12
- **LEVELADJUSTMENT:** 1
- **CR:** 2

### Wraith

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT,WIS,CHA|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Diplomacy|Hide|Intimidate|Listen|Search|Sense Motive|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Alertness|Improved Initiative
- **AUTO:** LANG|Common|Infernal
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Turn Resistance|Wraith ~ Constitution Drain|Wraith ~ Create Spawn|Wraith Shared ~ Daylight Powerlessness|Wraith Shared ~ Unnatural Aura
- **LEGS:** 0
- **NATURALATTACKS:** Incorporeal touch,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d4
- **MONSTERCLASS:** Undead:5
- **RACETYPE:** Undead
- **RACESUBTYPE:** Incorporeal
- **HITDICEADVANCEMENT:** 10
- **CR:** 5
- **KIT:** 1|LE

### Wraith (Dread)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Fly,60
- **FACE:** 10
- **REACH:** 10
- **BONUS:** STAT|DEX|18
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|8
- **BONUS:** STAT|CHA|14
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Diplomacy|Hide|Intimidate|Knowledge (Religion)|Listen|Search|Sense Motive|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Alertness|Improved Initiative
- **AUTO:** LANG|Common|Infernal
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Dread Wraith ~ Constitution Drain|Dread Wraith ~ Create Spawn|Dread Wraith ~ Lifesense|Wraith Shared ~ Daylight Powerlessness|Wraith Shared ~ Unnatural Aura
- **LEGS:** 0
- **NATURALATTACKS:** Incorporeal touch,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Undead:16
- **RACETYPE:** Undead
- **RACESUBTYPE:** Incorporeal
- **HITDICEADVANCEMENT:** 32
- **CR:** 11
- **KIT:** 1|LE

### Wyvern

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Fly,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|3|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** FEAT|AUTOMATIC|Multiattack
- **AUTO:** LANG|Draconic
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Immunity to Paralysis|Immunity to Sleep|Scent|Wyvern ~ Improved Grab|Wyvern ~ Poison|Wyvern ~ Skills
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Wing,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d8|Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6
- **MONSTERCLASS:** Dragon:7
- **RACETYPE:** Dragon
- **HITDICEADVANCEMENT:** 7,10,21
- **CR:** 6

### Xill

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CON|4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT,WIS|2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **MONCSKILL:** Balance|Climb|Diplomacy|Escape Artist|Intimidate|Listen|Move Silently|Sense Motive|Spot|Tumble|Use Rope
- **ABILITY:** FEAT|AUTOMATIC|Multiattack
- **AUTO:** LANG|Infernal
- **AUTO:** WEAPONPROF|Longbow|Sword (Short)|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Xill ~ Implant|Xill ~ Improved Grab|Xill ~ Paralysis|Xill ~ Planewalk
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d4
- **SR:** 21
- **MONSTERCLASS:** Outsider:5
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar
- **HITDICEADVANCEMENT:** 8,15
- **LEVELADJUSTMENT:** 4
- **CR:** 6
- **KIT:** 1|LE

### Xorn (Minor)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Burrow,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** SKILL|Search,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR,CON|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **MONCSKILL:** Hide|Intimidate|Knowledge (Dungeoneering)|Listen|Move Silently|Search|Spot|Survival
- **AUTO:** LANG|Common|Terran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold|Immunity to Fire|Resistance to Electricity|Xorn ~ All-Around Vision|Xorn ~ Earth Glide
- **LEGS:** 3
- **HANDS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*3,1d3
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Earth
- **HITDICEADVANCEMENT:** 6
- **CR:** 3

### Xorn (Average)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Burrow,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** SKILL|Search,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|CON|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **MONCSKILL:** Hide|Intimidate|Knowledge (Dungeoneering)|Listen|Move Silently|Search|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Cleave
- **AUTO:** LANG|Common|Terran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold|Immunity to Fire|Resistance to Electricity|Xorn ~ All-Around Vision|Xorn ~ Earth Glide
- **LEGS:** 3
- **HANDS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*3,1d4
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Earth
- **HITDICEADVANCEMENT:** 14
- **CR:** 6

### Xorn (Elder)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Burrow,20
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|16|TYPE=NaturalArmor
- **BONUS:** SKILL|Search,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|CON|8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **MONCSKILL:** Hide|Intimidate|Knowledge (Dungeoneering)|Listen|Move Silently|Search|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Cleave
- **AUTO:** LANG|Common|Terran
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold|Immunity to Fire|Resistance to Electricity|Xorn ~ All-Around Vision|Xorn ~ Earth Glide
- **LEGS:** 3
- **HANDS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*3,1d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Outsider:15
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Earth
- **HITDICEADVANCEMENT:** 21,45
- **CR:** 8

### Yeth Hound

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Search|Spot|Survival
- **AUTO:** LANG|Infernal
- **AUTO:** WEAPONPROF|TYPE=Martial|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Scent|Yeth Hound ~ Bay|Yeth Hound ~ Flight|Yeth Hound ~ Natural Weapons|Yeth Hound ~ Skills|Yeth Hound ~ Trip
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **DR:** 10/Silver
- **MONSTERCLASS:** Outsider:3
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Evil
- **HITDICEADVANCEMENT:** 6,9
- **LEVELADJUSTMENT:** 3
- **CR:** 3
- **KIT:** 1|NE

### Yrthak

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Fly,60
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|BlindsightRange|120|TYPE=Base
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Listen|Move Silently
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Yrthak ~ Blindsight|Yrthak ~ Explosion|Yrthak ~ Immunities|Yrthak ~ Skills|Yrthak ~ Sonic Lance
- **LEGS:** 0
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d6
- **NATURALATTACKS:** Sonic Lance,Weapon.Natural.Ranged.Sonic,*1,6d6
- **MONSTERCLASS:** Magical Beast:12
- **RACETYPE:** Magical Beast
- **HITDICEADVANCEMENT:** 16,36
- **CR:** 9

### Yuan-Ti (Pureblood)

- **FAVCLASS:** Ranger
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Abyssal,Draconic
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|DEX,INT,CHA|2
- **AUTO:** LANG|Yuan-ti|Common
- **ABILITY:** FEAT|VIRTUAL|Alertness|Blind-Fight
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Pureblood Yuan-Ti
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 3

### Yuan-Ti (Halfblood)

- **FAVCLASS:** Ranger
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Abyssal,Draconic
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX,CON|2
- **BONUS:** STAT|INT,WIS|8
- **BONUS:** STAT|CHA|6
- **BONUS:** WEAPONPROF=Bite|TOHIT|-5
- **AUTO:** LANG|Yuan-ti|Common
- **ABILITY:** FEAT|VIRTUAL|Alertness|Blind-Fight
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Halfblood Yuan-Ti
- **NATURALATTACKS:** Bite,Natural.Melee.Weapon,*1,1d6
- **MONSTERCLASS:** Monstrous Humanoid:7
- **RACETYPE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 5
- **CR:** 3

### Yuan-Ti (Abomination)

- **FAVCLASS:** Cleric
- **SIZE:** L
- **MOVE:** Walk,30,Climb,20,Swim,20
- **FACE:** 10
- **REACH:** 10
- **LANGBONUS:** Abyssal,Draconic
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR,CHA|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT,WIS|10
- **BONUS:** WEAPONPROF=Bite|TOHIT|-5
- **AUTO:** LANG|Yuan-ti|Common
- **ABILITY:** FEAT|VIRTUAL|Alertness|Blind-Fight
- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Abomination Yuan-Ti
- **NATURALATTACKS:** Bite,Natural.Melee.Weapon,*1,2d6
- **MONSTERCLASS:** Monstrous Humanoid:9
- **RACETYPE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 3

### Zombie (Kobold)

- **SIZE:** S
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):2
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 1/2
- **KIT:** 1|NE

### Zombie (Human Commoner)

- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):2
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 1/2
- **KIT:** 1|NE

### Zombie (Troglodyte)

- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|-4
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** WEAPONPROF|Greatclub|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):4
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 1
- **KIT:** 1|NE

### Zombie (Bugbear)

- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** SHIELDPROF|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):6
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 2
- **KIT:** 1|NE

### Zombie (Ogre)

- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|-4
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** WEAPONPROF|Greatclub|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **LEGS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):8
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 3
- **KIT:** 1|NE

### Zombie (Minotaur)

- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** WEAPONPROF|Greataxe|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **LEGS:** 2
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):12
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 4
- **KIT:** 1|NE

### Zombie (Wyvern)

- **SIZE:** L
- **MOVE:** Walk,20,Fly,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Zombie ~ Single Actions Only
- **LEGS:** 4
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,2d6
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):14
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 14,20
- **CR:** 4
- **KIT:** 1|NE

### Zombie (Gray Render)

- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CHA|-9
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Toughness
- **AUTO:** WEAPONPROF|TYPE=Simple
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **DR:** 5/Slashing
- **MONSTERCLASS:** Undead (Mindless):20
- **RACETYPE:** Undead
- **RACESUBTYPE:** Mindless
- **CR:** 6
- **KIT:** 1|NE

### Ape

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Ape
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Climb,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Climb|Listen|Spot
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:4
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 8
- **CR:** 2
- **KIT:** 1|TN

### Baboon

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Baboon
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Climb,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Listen|Spot
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 3
- **CR:** 1/2
- **KIT:** 1|TN

### Badger

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Badger
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30,Burrow,10
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Escape Artist|4|TYPE=Racial
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|RageTimes,RageDuration|1
- **MONCSKILL:** Escape Artist|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|AUTOMATIC|Track
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d2|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 2
- **CR:** 1/2
- **KIT:** 1|TN

### Bat

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Bat
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** D
- **MOVE:** Walk,5,Fly,40
- **FACE:** 1
- **REACH:** 0
- **BONUS:** SKILL|Listen,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|BlindsenseRange|20|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **LEGS:** 2
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Quarter Hitdie
- **CR:** 1/10
- **KIT:** 1|TN

### Bear (Black)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Bear (Black)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Swim|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Climb|Listen|Spot|Swim
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 5
- **CR:** 2
- **KIT:** 1|TN

### Bear (Brown)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Bear (Brown)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Swim|4|TYPE=Racial
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Animal:6
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 10
- **CR:** 4
- **KIT:** 1|TN

### Bear (Polar)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Bear (Polar)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Swim,30
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Hide|Listen|Spot|Swim
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Animal:8
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 12
- **CR:** 4
- **KIT:** 1|TN

### Bison

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Bison
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Animal:5
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 7
- **CR:** 2
- **KIT:** 1|TN

### Boar

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Boar
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 5
- **CR:** 2
- **KIT:** 1|TN

### Camel

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Camel
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Bite|DAMAGE|-ceil(STR/2)
- **BONUS:** WEAPONPROF=Bite|TOHIT|-5
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Camel (Bactrian)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Camel (Bactrian)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** MOVEADD|TYPE.Walk|-10
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-6
- **BONUS:** STAT|CON|2
- **BONUS:** WEAPONPROF=Bite|DAMAGE|-ceil(STR/2)
- **BONUS:** WEAPONPROF=Bite|TOHIT|-5
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Cat

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Cat
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,30
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** SKILL|Balance,Jump|8|TYPE=Racial
- **BONUS:** SKILL|Climb,Hide,Move Silently|4|TYPE=Racial
- **BONUS:** SKILL|Climb,Jump|(DEX-STR)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Balance|Climb|Hide|Jump|Listen|Move Silently|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d2|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Half Hitdie
- **CR:** 1/4
- **KIT:** 1|TN

### Cheetah

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Cheetah
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d2
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 5
- **CR:** 2
- **KIT:** 1|TN

### Crocodile

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Crocodile
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Swim,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot|Swim
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d12
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 5
- **CR:** 2
- **KIT:** 1|TN

### Crocodile (Giant)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Crocodile (Giant)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Swim,30
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot|Swim
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d12
- **MONSTERCLASS:** Animal:7
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 14
- **CR:** 4
- **KIT:** 1|TN

### Dog

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Dog
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump|4|TYPE=Racial
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Jump|Listen|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Track
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **CR:** 1/3
- **KIT:** 1|TN

### Dog (Riding)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Dog (Riding)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump|4|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Jump|Listen|Spot|Survival|Swim
- **ABILITY:** FEAT|AUTOMATIC|Track
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Donkey

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Donkey
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance|2|TYPE=Racial
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d2
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **CR:** 1/6
- **KIT:** 1|TN

### Eagle

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Eagle
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,10,Fly,80
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|8|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **LEGS:** 2
- **HANDS:** 3
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 1,3
- **CR:** 1/2
- **KIT:** 1|TN

### Elephant

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Elephant
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6|Stamp,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,2d8
- **MONSTERCLASS:** Animal:11
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 22
- **CR:** 7
- **KIT:** 1|TN

### Elephant (Indian)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Elephant (Indian)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6|Stamp,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,2d8
- **MONSTERCLASS:** Animal:11
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 22
- **CR:** 7
- **KIT:** 1|TN

### Hawk

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Hawk
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,10,Fly,60
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|Maneuverability|3
- **BONUS:** WEAPONPROF=Talons|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 2
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **CR:** 1/3
- **KIT:** 1|TN

### Horse (Heavy)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Horse (Heavy)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-ceil(STR/2)
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Horse (Light)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Horse (Light)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-ceil(STR/2)
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Horse (Warhorse Heavy)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Horse (Warhorse Heavy)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:4
- **RACETYPE:** Animal
- **CR:** 2
- **KIT:** 1|TN

### Horse (Warhorse Light)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Horse (Warhorse Light)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Hyena

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Hyena
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 3,5
- **CR:** 1
- **KIT:** 1|TN

### Leopard

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Leopard
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Climb,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Jump|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Balance|Climb|Hide|Jump|Listen|Move Silently|Spot
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 5
- **CR:** 2
- **KIT:** 1|TN

### Lion

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Lion
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Balance|Hide|Listen|Move Silently|Spot
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal:5
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 8
- **CR:** 3
- **KIT:** 1|TN

### Lizard

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Lizard
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,20,Climb,20
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Climb|DEX-STR
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Half Hitdie
- **CR:** 1/6
- **KIT:** 1|TN

### Lizard (Monitor)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Lizard (Monitor)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Swim,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Listen|Move Silently|Spot|Swim
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 5
- **CR:** 2
- **KIT:** 1|TN

### Manta Ray

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Manta Ray
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Swim,30
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Ram|DAMAGE|-ceil(STR/2)
- **BONUS:** WEAPONPROF=Ram|TOHIT|-5
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Ram,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Animal:4
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 1
- **KIT:** 1|TN

### Monkey

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Monkey
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,30,Climb,30
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** SKILL|Balance|8|TYPE=Racial
- **BONUS:** SKILL|Climb|(DEX-STR)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **LEGS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 1,3
- **CR:** 1/6
- **KIT:** 1|TN

### Mule

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Mule
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Octopus

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Octopus
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Swim,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** SKILL|Escape Artist|10|TYPE=Racial
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Arms|DAMAGE|-STR
- **MONCSKILL:** Escape Artist|Hide|Listen|Spot|Swim
- **LEGS:** 0
- **HANDS:** 9
- **NATURALATTACKS:** Arms,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,0|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 2,6
- **CR:** 1
- **KIT:** 1|TN

### Octopus (Giant)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Octopus (Giant)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Swim,30
- **FACE:** 10
- **REACH:** 10
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** SKILL|Escape Artist|10|TYPE=Racial
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **MONCSKILL:** Escape Artist|Hide|Listen|Spot|Swim
- **LEGS:** 0
- **HANDS:** 9
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Finesseable.Bludgeoning,*8,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal:8
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 12,24
- **CR:** 8
- **KIT:** 1|TN

### Owl

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Owl
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,10,Fly,40
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Listen|8|TYPE=Racial
- **BONUS:** SKILL|Move Silently|14|TYPE=Racial
- **BONUS:** STAT|STR|-6
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|Maneuverability|3
- **BONUS:** WEAPONPROF=Talons|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Move Silently|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 2
- **NATURALATTACKS:** Talons,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 1,2
- **CR:** 1/4
- **KIT:** 1|TN

### Pony

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Pony
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-ceil(STR/2)
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d3
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **CR:** 1/4
- **KIT:** 1|TN

### Pony (War)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Pony (War)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|CHA|-6
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d3
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **CR:** 1/2
- **KIT:** 1|TN

### Porpoise

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Porpoise
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Swim,80
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot,Listen|4|TYPE=Racial
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|BlindsightRange|120|TYPE=Base
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d4
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 1/2
- **KIT:** 1|TN

### Rat

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Rat
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,15,Climb,15,Swim,15
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** SKILL|Balance,Swim|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Move Silently|4|TYPE=Racial
- **BONUS:** SKILL|Climb,Swim|(DEX-STR)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Move Silently|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Quarter Hitdie
- **CR:** 1/8
- **KIT:** 1|TN

### Raven

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Raven
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,10,Fly,40
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|Maneuverability|3
- **BONUS:** WEAPONPROF=Claw|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d2
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Quarter Hitdie
- **CR:** 1/6
- **KIT:** 1|TN

### Rhinoceros

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Rhinoceros
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Gore|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot
- **LEGS:** 4
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8
- **MONSTERCLASS:** Animal:8
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 12,24
- **CR:** 4
- **KIT:** 1|TN

### Shark (Medium)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Shark (Medium)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Swim,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|BlindsenseRange|30|TYPE=Base|
- **BONUS:** VAR|KeenScentRange|180|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 6
- **CR:** 1
- **KIT:** 1|TN

### Shark (Large)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Shark (Large)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Swim,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|BlindsenseRange|30|TYPE=Base|
- **BONUS:** VAR|KeenScentRange|180|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal:7
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 9
- **CR:** 2
- **KIT:** 1|TN

### Shark (Huge)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Shark (Huge)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Swim,60
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|BlindsenseRange|30|TYPE=Base|
- **BONUS:** VAR|KeenScentRange|180|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Animal:10
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 17
- **CR:** 4
- **KIT:** 1|TN

### Snake (Constrictor)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Snake (Constrictor)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Climb,20,Swim,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Listen,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 5,10
- **CR:** 2
- **KIT:** 1|TN

### Snake (Constrictor/Giant)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Snake (Constrictor/Giant)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Climb,20,Swim,20
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Listen,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal:11
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 16,33
- **CR:** 5
- **KIT:** 1|TN

### Snake (Viper/Tiny)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Snake (Viper/Tiny)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,15,Climb,15,Swim,15
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Listen,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|-6
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **BONUS:** WEAPONPROF=Bite|DAMAGE|-min(0,STR)
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Quarter Hitdie
- **CR:** 1/3
- **KIT:** 1|TN

### Snake (Viper/Small)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Snake (Viper/Small)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,20,Climb,20,Swim,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Listen,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d2
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **CR:** 1/2
- **KIT:** 1|TN

### Snake (Viper/Medium)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Snake (Viper/Medium)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Climb,20,Swim,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Listen,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d4
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **CR:** 1
- **KIT:** 1|TN

### Snake (Viper/Large)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Snake (Viper/Large)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Climb,20,Swim,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Listen,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)|TYPE=Racial.STACK
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d4
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **CR:** 2
- **KIT:** 1|TN

### Snake (Viper/Huge)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Snake (Viper/Huge)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20,Climb,20,Swim,20
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Hide,Listen,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)|TYPE=Racial.STACK
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Listen|Spot|Swim
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d6
- **MONSTERCLASS:** Animal:6
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 18
- **CR:** 3
- **KIT:** 1|TN

### Squid

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Squid
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Swim,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|TOHIT.GRAPPLE|4|TYPE=Racial
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Arms|DAMAGE|-STR
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **HANDS:** 11
- **NATURALATTACKS:** Arms,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,0|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 6,11
- **CR:** 1
- **KIT:** 1|TN

### Squid (Giant)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Squid (Giant)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Swim,80
- **FACE:** 15
- **REACH:** 15
- **BONUS:** COMBAT|TOHIT.GRAPPLE|4|TYPE=Racial
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-8
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **HANDS:** 11
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Melee.Finesseable.Bludgeoning,*10,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **MONSTERCLASS:** Animal:12
- **RACETYPE:** Animal
- **RACESUBTYPE:** Aquatic
- **HITDICEADVANCEMENT:** 18,36
- **CR:** 9
- **KIT:** 1|TN

### Tiger

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Tiger
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Balance,Hide,Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Balance|Hide|Listen|Move Silently|Spot|Swim
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Animal:6
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 12,18
- **CR:** 4
- **KIT:** 1|TN

### Toad

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Toad
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** D
- **MOVE:** Walk,5
- **FACE:** 1
- **REACH:** 0
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|-9
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-6
- **MONCSKILL:** Hide|Listen|Spot
- **LEGS:** 4
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Quarter Hitdie
- **CR:** 1/10
- **KIT:** 1|TN

### Weasel

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Weasel
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** T
- **MOVE:** Walk,20,Climb,20
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** SKILL|Balance,Climb|8|TYPE=Racial
- **BONUS:** SKILL|Move Silently|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max((DEX-STR),0)
- **BONUS:** STAT|STR|-8
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Balance|Climb|Hide|Move Silently|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Animal:1
- **RACETYPE:** Animal
- **TEMPLATE:** Half Hitdie
- **CR:** 1/4
- **KIT:** 1|TN

### Whale (Baleen)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Whale (Baleen)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** G
- **MOVE:** Swim,40
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot,Listen|4|TYPE=Racial
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|12
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|BlindsightRange|120|TYPE=Base
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **MONSTERCLASS:** Animal:12
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 18,36
- **CR:** 6
- **KIT:** 1|TN

### Whale (Cachalot)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Whale (Cachalot)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** G
- **MOVE:** Swim,40
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot,Listen|4|TYPE=Racial
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|BlindsightRange|120|TYPE=Base
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,3d6|Tail,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8
- **MONSTERCLASS:** Animal:12
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 18,36
- **CR:** 7
- **KIT:** 1|TN

### Whale (Orca)

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Whale (Orca)
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Swim,50
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot,Listen|4|TYPE=Racial
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|BlindsightRange|120|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Listen|Spot|Swim
- **LEGS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Animal:9
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 13,27
- **CR:** 5
- **KIT:** 1|TN

### Wolf

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Wolf
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Hide|Listen|Move Silently|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Track
- **LEGS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:2
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 3,6
- **CR:** 1
- **KIT:** 1|TN

### Wolverine

- **ABILITY:** Internal|AUTOMATIC|Race Traits ~ Wolverine
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Burrow,10,Climb,10
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-8
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|RageTimes,RageDuration|1
- **MONCSKILL:** Climb|Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Track
- **LEGS:** 4
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Animal:3
- **RACETYPE:** Animal
- **HITDICEADVANCEMENT:** 3,5
- **CR:** 2
- **KIT:** 1|TN

### Giant Ant (Worker)

- **SIZE:** M
- **MOVE:** Walk,50,Climb,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|CHA|-2
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb
- **ABILITY:** FEAT|AUTOMATIC|Track
- **ABILITY:** Special Ability|AUTOMATIC|Giant Ant ~ Improved Grab|Giant Ant ~ Skills|Scent
- **LEGS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Vermin:2
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 1
- **KIT:** 1|TN

### Giant Ant (Soldier)

- **SIZE:** M
- **MOVE:** Walk,50,Climb,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON,WIS|2
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb
- **ABILITY:** FEAT|AUTOMATIC|Track
- **ABILITY:** Special Ability|AUTOMATIC|Giant Ant ~ Acid Sting|Giant Ant ~ Improved Grab|Giant Ant ~ Skills|Scent
- **LEGS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d4
- **MONSTERCLASS:** Vermin:2
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 2
- **KIT:** 1|TN

### Giant Ant (Queen)

- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|9|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON,WIS|2
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **ABILITY:** FEAT|AUTOMATIC|Track
- **ABILITY:** Special Ability|AUTOMATIC|Giant Ant ~ Improved Grab|Giant Ant ~ Skills|Scent
- **LEGS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Vermin:4
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** Female Only
- **HITDICEADVANCEMENT:** 6,8
- **CR:** 2
- **KIT:** 1|TN

### Giant Bee

- **SIZE:** M
- **MOVE:** Walk,20,Fly,80
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Sting|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Giant Bee ~ Poison|Giant Bee ~ Skills
- **LEGS:** 6
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d4
- **MONSTERCLASS:** Vermin:3
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 6,9
- **CR:** 1
- **KIT:** 1|TN

### Giant Bombardier Beetle

- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|Giant Bombardier Beetle ~ Acid Spray
- **LEGS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Vermin:2
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 4,6
- **CR:** 2
- **KIT:** 1|TN

### Giant Fire Beetle

- **SIZE:** S
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **LEGS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d4
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 3
- **CR:** 1/3
- **KIT:** 1|TN

### Giant Stag Beetle

- **SIZE:** L
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|Giant Stag Beetle ~ Trample
- **LEGS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6
- **MONSTERCLASS:** Vermin:7
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 10,21
- **CR:** 4
- **KIT:** 1|TN

### Giant Praying Mantis

- **SIZE:** L
- **MOVE:** Walk,20,Fly,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON,WIS|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Giant Praying Mantis ~ Improved Grab|Giant Praying Mantis ~ Skills
- **LEGS:** 6
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Vermin:4
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 8,12
- **CR:** 3
- **KIT:** 1|TN

### Giant Wasp

- **SIZE:** L
- **MOVE:** Walk,20,Fly,60
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX,WIS|2
- **BONUS:** STAT|CON|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|Maneuverability|4
- **BONUS:** WEAPONPROF=Sting|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Giant Wasp ~ Poison|Giant Wasp ~ Skills
- **LEGS:** 6
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d3
- **MONSTERCLASS:** Vermin:5
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 8,15
- **CR:** 3
- **KIT:** 1|TN

### Monstrous Centipede (Tiny)

- **SIZE:** T
- **MOVE:** Walk,20,Climb,20
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|-9
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Centipede ~ Poison|Monstrous Centipede ~ Skills
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d3
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** Quarter Hitdie
- **CR:** 1/8
- **KIT:** 1|TN

### Monstrous Centipede (Small)

- **SIZE:** S
- **MOVE:** Walk,30,Climb,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|-6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Centipede ~ Poison|Monstrous Centipede ~ Skills
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d4
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** Half Hitdie
- **CR:** 1/4
- **KIT:** 1|TN

### Monstrous Centipede (Medium)

- **SIZE:** M
- **MOVE:** Walk,40,Climb,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Centipede ~ Poison|Monstrous Centipede ~ Skills
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d6
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **CR:** 1/2
- **KIT:** 1|TN

### Monstrous Centipede (Large)

- **SIZE:** L
- **MOVE:** Walk,40,Climb,40
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Centipede ~ Poison|Monstrous Centipede ~ Skills
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d8
- **MONSTERCLASS:** Vermin:3
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 5
- **CR:** 1
- **KIT:** 1|TN

### Monstrous Centipede (Huge)

- **SIZE:** H
- **MOVE:** Walk,40,Climb,40
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Centipede ~ Poison|Monstrous Centipede ~ Skills
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d6
- **MONSTERCLASS:** Vermin:6
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 11
- **CR:** 2
- **KIT:** 1|TN

### Monstrous Centipede (Gargantuan)

- **SIZE:** G
- **MOVE:** Walk,40,Climb,40
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Centipede ~ Poison|Monstrous Centipede ~ Skills
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d8
- **MONSTERCLASS:** Vermin:12
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 23
- **CR:** 6
- **KIT:** 1|TN

### Monstrous Centipede (Colossal)

- **SIZE:** C
- **MOVE:** Walk,40,Climb,40
- **FACE:** 30
- **REACH:** 20
- **BONUS:** COMBAT|AC|16|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|8|TYPE=Racial
- **BONUS:** SKILL|Climb|max(STR,DEX)-STR
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Centipede ~ Poison|Monstrous Centipede ~ Skills
- **LEGS:** 48
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,4d6
- **MONSTERCLASS:** Vermin:24
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 48
- **CR:** 9
- **KIT:** 1|TN

### Monstrous Scorpion (Tiny)

- **SIZE:** T
- **MOVE:** Walk,20
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|max(DEX,STR)-STR
- **BONUS:** SKILL|Climb,Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR,CHA|-8
- **BONUS:** STAT|CON|4
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Scorpion ~ Constrict|Monstrous Scorpion ~ Improved Grab|Monstrous Scorpion ~ Poison|Monstrous Scorpion ~ Skills
- **LEGS:** 6
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d2|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d2
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** Half Hitdie
- **CR:** 1/4
- **KIT:** 1|TN

### Monstrous Scorpion (Small)

- **SIZE:** S
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|max(DEX,STR)-STR
- **BONUS:** SKILL|Climb,Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Scorpion ~ Constrict|Monstrous Scorpion ~ Improved Grab|Monstrous Scorpion ~ Poison|Monstrous Scorpion ~ Skills
- **LEGS:** 6
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d3
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **CR:** 1/2
- **KIT:** 1|TN

### Monstrous Scorpion (Medium)

- **SIZE:** M
- **MOVE:** Walk,40
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|max(DEX,STR)-STR
- **BONUS:** SKILL|Climb,Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Scorpion ~ Constrict|Monstrous Scorpion ~ Improved Grab|Monstrous Scorpion ~ Poison|Monstrous Scorpion ~ Skills
- **LEGS:** 6
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d4
- **MONSTERCLASS:** Vermin:2
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 4
- **CR:** 1
- **KIT:** 1|TN

### Monstrous Scorpion (Large)

- **SIZE:** L
- **MOVE:** Walk,50
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|max(DEX,STR)-STR
- **BONUS:** SKILL|Climb,Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Scorpion ~ Constrict|Monstrous Scorpion ~ Improved Grab|Monstrous Scorpion ~ Poison|Monstrous Scorpion ~ Skills
- **LEGS:** 6
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,1d6
- **MONSTERCLASS:** Vermin:5
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 9
- **CR:** 3
- **KIT:** 1|TN

### Monstrous Scorpion (Huge)

- **SIZE:** H
- **MOVE:** Walk,50
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|12|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|max(DEX,STR)-STR
- **BONUS:** SKILL|Climb,Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Scorpion ~ Constrict|Monstrous Scorpion ~ Improved Grab|Monstrous Scorpion ~ Poison|Monstrous Scorpion ~ Skills
- **LEGS:** 6
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d4
- **MONSTERCLASS:** Vermin:10
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 19
- **CR:** 7
- **KIT:** 1|TN

### Monstrous Scorpion (Gargantuan)

- **SIZE:** G
- **MOVE:** Walk,50
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|18|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|max(DEX,STR)-STR
- **BONUS:** SKILL|Climb,Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Scorpion ~ Constrict|Monstrous Scorpion ~ Improved Grab|Monstrous Scorpion ~ Poison|Monstrous Scorpion ~ Skills
- **LEGS:** 6
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d6
- **MONSTERCLASS:** Vermin:20
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 39
- **CR:** 10
- **KIT:** 1|TN

### Monstrous Scorpion (Colossal)

- **SIZE:** C
- **MOVE:** Walk,50
- **FACE:** 40
- **REACH:** 30
- **BONUS:** COMBAT|AC|25|TYPE=NaturalArmor
- **BONUS:** COMBAT|TOHIT.GRAPPLE|max(DEX,STR)-STR
- **BONUS:** SKILL|Climb,Hide,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|24
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **MONCSKILL:** Climb|Hide|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Scorpion ~ Constrict|Monstrous Scorpion ~ Improved Grab|Monstrous Scorpion ~ Poison|Monstrous Scorpion ~ Skills
- **LEGS:** 6
- **HANDS:** 3
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d8|Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d8
- **MONSTERCLASS:** Vermin:40
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **HITDICEADVANCEMENT:** 60
- **CR:** 12
- **KIT:** 1|TN

### Monstrous Spider (Tiny)

- **SIZE:** T
- **MOVE:** Walk,20,Climb,10
- **FACE:** 2.5
- **REACH:** 0
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(DEX,STR)-STR
- **BONUS:** STAT|STR,CHA|-8
- **BONUS:** STAT|DEX|6
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Poison|Monstrous Spider ~ Skills|Monstrous Spider ~ Tremorsense
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d3
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** Half Hitdie
- **TEMPLATE:** CHOOSE:Hunting|Web Spinning
- **CR:** 1/4
- **KIT:** 1|TN

### Monstrous Spider (Small)

- **SIZE:** S
- **MOVE:** Walk,30,Climb,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(DEX,STR)-STR
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Poison|Monstrous Spider ~ Skills|Monstrous Spider ~ Tremorsense
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d4
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** CHOOSE:Hunting|Web Spinning
- **CR:** 1/2
- **KIT:** 1|TN

### Monstrous Spider (Medium)

- **SIZE:** M
- **MOVE:** Walk,30,Climb,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(DEX,STR)-STR
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** FEAT|AUTOMATIC|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Poison|Monstrous Spider ~ Skills|Monstrous Spider ~ Tremorsense
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d6
- **MONSTERCLASS:** Vermin:2
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** CHOOSE:Hunting|Web Spinning
- **HITDICEADVANCEMENT:** 3
- **CR:** 1
- **KIT:** 1|TN

### Monstrous Spider (Large)

- **SIZE:** L
- **MOVE:** Walk,30,Climb,20
- **FACE:** 10
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(DEX,STR)-STR
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Poison|Monstrous Spider ~ Skills|Monstrous Spider ~ Tremorsense
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,1d8
- **MONSTERCLASS:** Vermin:4
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** CHOOSE:Hunting|Web Spinning
- **HITDICEADVANCEMENT:** 7
- **CR:** 2
- **KIT:** 1|TN

### Monstrous Spider (Huge)

- **SIZE:** H
- **MOVE:** Walk,30,Climb,20
- **FACE:** 15
- **REACH:** 10
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(DEX,STR)-STR
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Poison|Monstrous Spider ~ Skills|Monstrous Spider ~ Tremorsense
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d6
- **MONSTERCLASS:** Vermin:8
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** CHOOSE:Hunting|Web Spinning
- **HITDICEADVANCEMENT:** 15
- **CR:** 5
- **KIT:** 1|TN

### Monstrous Spider (Gargantuan)

- **SIZE:** G
- **MOVE:** Walk,30,Climb,20
- **FACE:** 20
- **REACH:** 15
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(DEX,STR)-STR
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Poison|Monstrous Spider ~ Skills|Monstrous Spider ~ Tremorsense
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,2d8
- **MONSTERCLASS:** Vermin:16
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** CHOOSE:Hunting|Web Spinning
- **HITDICEADVANCEMENT:** 31
- **CR:** 8
- **KIT:** 1|TN

### Monstrous Spider (Colossal)

- **SIZE:** C
- **MOVE:** Walk,30,Climb,20
- **FACE:** 40
- **REACH:** 30
- **BONUS:** COMBAT|AC|18|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Spot|4|TYPE=Racial
- **BONUS:** SKILL|Climb|max(DEX,STR)-STR
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX,CON|4
- **BONUS:** STAT|CHA|-8
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **BONUS:** VAR|TremorsenseRange|60|TYPE=Base
- **BONUS:** WEAPONPROF=Bite|DAMAGE|max(0,(STR/2))
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Poison|Monstrous Spider ~ Skills|Monstrous Spider ~ Tremorsense
- **LEGS:** 8
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Poison,*1,4d6
- **MONSTERCLASS:** Vermin:32
- **RACETYPE:** Vermin
- **RACESUBTYPE:** Mindless
- **TEMPLATE:** CHOOSE:Hunting|Web Spinning
- **HITDICEADVANCEMENT:** 60
- **CR:** 11
- **KIT:** 1|TN

## Skills

### Control Shape

- **KEYSTAT:** WIS
- **USEUNTRAINED:** YES
- **PRETEMPLATE:** 1,Afflicted Lycanthrope

### Diplomacy (Red Dragons)

- **KEYSTAT:** CHA
- **USEUNTRAINED:** YES
- **CLASSES:** ALL
- **PRERULE:** 1,DISPLAYSKILLUSE
- **PREVARNEQ:** var("SKILL.Diplomacy (Red Dragons).MISC"),var("SKILL.Diplomacy.MISC")
- **PREABILITY:** 1,CATEGORY=Special Ability,Githyanki ~ Red Dragon Pact

## Spells

### Blur (Self Only)

- **SCHOOL:** Illusion
- **SUBSCHOOL:** Glamer
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) minutes [D]

Attacks miss subject 20%% of the time.

### Cause Fear (Radius)

- **SCHOOL:** Necromancy
- **DESCRIPTOR:** Fear|Mind-Affecting
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** 0 ft.
- **TARGETAREA:** 30-ft.-radius burst centered on you
- **DURATION:** 1d4 rounds or 1 round; see text
- **SAVEINFO:** Will partial
- **SPELLRES:** Yes

One or more creatures of 5 HD or less flees for 1d4 rounds.

### Create Wine

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **DESCRIPTOR:** Water
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Up to (CASTERLEVEL*2) gallons of water
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No

Creates (CASTERLEVEL*2) gallons of wine.

### Create/Destroy Water

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **DESCRIPTOR:** Water
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Up to (CASTERLEVEL*2) gallons of water
- **DURATION:** Instantaneous
- **SAVEINFO:** Will negates (object); see text
- **SPELLRES:** No

Creates or destroys (CASTERLEVEL*2) gallons of water.

### Darkness (40 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

40-ft. radius of supernatural shadow.

### Darkness (50 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

50-ft. radius of supernatural shadow.

### Darkness (60 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

60-ft. radius of supernatural shadow.

### Darkness (70 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

70-ft. radius of supernatural shadow.

### Darkness (80 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

80-ft. radius of supernatural shadow.

### Darkness (90 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

90-ft. radius of supernatural shadow.

### Darkness (100 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

100-ft. radius of supernatural shadow.

### Darkness (110 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

110-ft. radius of supernatural shadow.

### Darkness (120 ft. radius)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Darkness
- **COMPS:** V, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Object touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

120-ft. radius of supernatural shadow.

### Detect Evil (60 ft. radius)

- **SCHOOL:** Divination
- **COMPS:** V, S, DF
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** 60-ft.-radius emanation centered on you
- **DURATION:** Concentration, up to (CASTERLEVEL*10) minutes [D]

Reveals creatures, spells, or objects of selected alignment.

### Detect Gems

- **SCHOOL:** Divination
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** 60 ft.
- **TARGETAREA:** Cone-shaped emanation
- **DURATION:** Concentration, up to (CASTERLEVEL) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Detects gems within 60 ft.

### Detect Good (60 ft. radius)

- **SCHOOL:** Divination
- **COMPS:** V, S, DF
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** 60-ft.-radius emanation centered on you
- **DURATION:** Concentration, up to (CASTERLEVEL*10) minutes [D]

Reveals creatures, spells, or objects of selected alignment.

### Draw Moisture

- **SCHOOL:** Necromancy
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** 0 ft.
- **TARGETAREA:** 20-ft.-radius burst centered on you
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude half
- **SPELLRES:** Yes

Living creatures in the area take 2d8 points of damage. Plant and aquatic creatures take a -2 penalty on their saving throws.

### Endure Elements (40 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 40-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (50 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 50-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (60 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 60-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (70 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 70-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (80 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 80-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (90 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 90-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (100 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 100-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (110 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 110-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Endure Elements (120 ft. radius)

- **SCHOOL:** Abjuration
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** 120-ft.-radius emanation centered on creature touched
- **DURATION:** 24 hours
- **SAVEINFO:** Will negates (harmless)
- **SPELLRES:** Yes (harmless)

Creatures in the radius can exist comfortably in hot or cold environments.

### Ethereal Jaunt (1 hour)

- **SCHOOL:** Transmutation
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** 1 hour [D]
- **SAVEINFO:** None
- **SPELLRES:** No

You become ethereal for 1 hour.

### Freezing Fog

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** Fog spreads in 20-ft. radius, 20 ft. high
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** See text
- **SPELLRES:** No

As solid fog, but surfaces become icy replicating the effect of a grease spell in the area.

### Gaseous Form (Self Only)

- **SCHOOL:** Transmutation
- **COMPS:** S, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** 1 hour [D]

You become insubstantial and can fly slowly.

### Invisibility (Greater/Self Only)

- **SCHOOL:** Illusion
- **SUBSCHOOL:** Glamer
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

As invisibility, but you can attack and stay invisible.

### Invisibility (Self Only)

- **SCHOOL:** Illusion
- **SUBSCHOOL:** Glamer
- **COMPS:** V, S, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) minutes [D]

You are invisible for (CASTERLEVEL) minutes or until you attack.

### Levitate (Self Only)

- **SCHOOL:** Transmutation
- **COMPS:** V, S, F
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You and up to 2,000 pounds
- **DURATION:** (CASTERLEVEL) minutes [D]

You move up and down at your direction.

### Luck Bonus

- **SCHOOL:** Transmutation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** One touched gem
- **DURATION:** 1d3+((CASTERLEVEL)*3) hours
- **SAVEINFO:** None
- **SPELLRES:** No

You can enchant one gem you touch to give a +1 luck bonus to saves, as per a stone of good luck.

### Magic Circle against Evil (Self Only)

- **SCHOOL:** Abjuration
- **DESCRIPTOR:** Good
- **COMPS:** V, S, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** 10-ft.-radius emanation centered on you
- **DURATION:** (CASTERLEVEL*10) minutes

+2 to AC and saves, counter mind control, hedge out elementals and outsiders in 10-ft. radius and (CASTERLEVEL*10) minutes.

### Major Creation (vegetable matter is permanent)

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V, S, M
- **CASTTIME:** 10 minutes
- **RANGE:** Close
- **TARGETAREA:** Unattended, nonmagical object of nonliving plant matter, up to 1 cu. ft./level
- **DURATION:** See text
- **SAVEINFO:** None
- **SPELLRES:** No

As minor creation, plus stone and metal.

### Permanent Image (visual and auditory elements only)

- **SCHOOL:** Illusion
- **SUBSCHOOL:** Figment
- **COMPS:** V, S, F
- **CASTTIME:** 1 standard action
- **RANGE:** Long
- **TARGETAREA:** Figment that cannot extend beyond a 20-ft. cube + (CASTERLEVEL) 10-ft. cubes [S]
- **DURATION:** Permanent [D]
- **SAVEINFO:** Will disbelief (if interacted with)
- **SPELLRES:** No

Includes sight and sound.

### Polymorph (Self Only)

- **SCHOOL:** Transmutation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) minutes [D]

You assume a new form.

### Polymorph (Humanoid Only)

- **SCHOOL:** Transmutation
- **COMPS:** V, S, M
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Willing living creature touched
- **DURATION:** 1 hour [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Gives one willing subject a new humanoid form.

### Scorching Ray (1 ray only)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Fire
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** 1 ray
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

1 ray, ranged touch attack deals 4d6 fire damage.

### Scorching Ray (2 rays only)

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Fire
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** 2 rays
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

2 rays, ranged touch attack deals 4d6 fire damage.

### Speak with Burrowing Mammals

- **SCHOOL:** Divination
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** None
- **SPELLRES:** No

You can communicate with Burrowing Mammals.

### Steaming Rainstorm

- **SCHOOL:** Conjuration
- **DESCRIPTOR:** Fire
- **COMPS:** V, S
- **CASTTIME:** 1 standard action
- **RANGE:** 0 ft.
- **TARGETAREA:** 20-ft. square area
- **DURATION:** Instantaneous
- **SAVEINFO:** Reflex half
- **SPELLRES:** No

Living creatures caught in the area take 2d6 points of fire damage.

### Summon Djinni

- **SCHOOL:** Conjuration
- **COMPS:** V, S, F
- **CASTTIME:** 1 round
- **RANGE:** Close
- **TARGETAREA:** One summoned djinni
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Calls a djinni to fight for you.

### Summon Monster VII (Huge Fire Elemental)

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Summoning
- **COMPS:** V, S, F/DF
- **CASTTIME:** 1 round
- **RANGE:** Close
- **TARGETAREA:** One summoned elemental
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Calls a Huge fire elemental to fight for you.

### Summon Monster IX (celestials only)

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Summoning
- **COMPS:** V, S, F/DF
- **CASTTIME:** 1 round
- **RANGE:** Close
- **TARGETAREA:** One summoned celestial
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Calls a celestial creature to fight for you.

### Teleport (Greater/Self Only)

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Teleportation
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You and up to 50 pounds of objects
- **DURATION:** Instantaneous

As teleport, but no range limit and no off-target arrival.

### Teleport (Greater/Forest Boundries Only)

- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Teleportation
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** Instantaneous

As greater teleport, but you cannot teleport beyond the forest boundries nor back from outside.

### Transmute Mud to Rock or Rock to Mud

- **SCHOOL:** Transmutation
- **DESCRIPTOR:** Earth
- **COMPS:** V, S, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** Up to (CASTERLEVEL*2) 10 ft. cubes [S]
- **DURATION:** Permanent; see text
- **SAVEINFO:** See text
- **SPELLRES:** No

Transforms (CASTERLEVEL*2) 10-ft. cubes.

### Grant up to three wishes (to nongenies only)

- **SCHOOL:** Universal
- **COMPS:** V, XP
- **CASTTIME:** 1 standard action
- **RANGE:** See text
- **TARGETAREA:** See text
- **DURATION:** See text
- **SAVEINFO:** See text
- **SPELLRES:** Yes
- **XPCOST:** 5000

As limited wish, but with fewer limits.

## Templates

### Base Race Type

- **TEMPLATE:** CHOOSE:Base Race Type ~ Aberration|Base Race Type ~ Animal|Base Race Type ~ Construct|Base Race Type ~ Dragon|Base Race Type ~ Elemental|Base Race Type ~ Fey|Base Race Type ~ Giant|Base Race Type ~ Humanoid|Base Race Type ~ Magical Beast|Base Race Type ~ Monstrous Humanoid|Base Race Type ~ Ooze|Base Race Type ~ Outsider|Base Race Type ~ Plant|Base Race Type ~ Undead|Base Race Type ~ Vermin

### Base Race Type ~ Aberration

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Aberration,TYPE=Aberration
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Aberration

### Base Race Type ~ Animal

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Animal,TYPE=Animal
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Animal

### Base Race Type ~ Construct

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Construct,TYPE=Construct
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Construct

### Base Race Type ~ Dragon

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Dragon,TYPE=Dragon
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Dragon

### Base Race Type ~ Elemental

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Elemental,TYPE=Elemental
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Elemental

### Base Race Type ~ Fey

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Fey,TYPE=Fey
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Fey

### Base Race Type ~ Giant

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Giant,TYPE=Giant
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Giant

### Base Race Type ~ Humanoid

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Humanoid,TYPE=Humanoid
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Humanoid

### Base Race Type ~ Magical Beast

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Magical Beast,TYPE=Magical Beast
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Magical Beast

### Base Race Type ~ Monstrous Humanoid

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Monstrous Humanoid,TYPE=Monstrous Humanoid
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Monstrous Humanoid

### Base Race Type ~ Ooze

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Ooze,TYPE=Ooze
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Ooze

### Base Race Type ~ Outsider

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Outsider,TYPE=Outsider
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Outsider

### Base Race Type ~ Plant

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Plant,TYPE=Plant
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Plant

### Base Race Type ~ Undead

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Undead,TYPE=Undead
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Undead

### Base Race Type ~ Vermin

- **DEFINE:** BaseRaceTypeUnchanged|0
- **PRERACE:** 2,RACETYPE=Vermin,TYPE=Vermin
- **BONUS:** VAR|BaseRaceTypeUnchanged|1
- **BONUS:** VAR|BaseRaceTypeUnchanged|-1
- **ABILITY:** Internal|AUTOMATIC|Augmented Vermin

### RaceSubtype ~ Augmented Aberration

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Aberration

### RaceSubtype ~ Augmented Animal

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Animal

### RaceSubtype ~ Augmented Construct

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Construct

### RaceSubtype ~ Augmented Dragon

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Dragon

### RaceSubtype ~ Augmented Elemental

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Elemental

### RaceSubtype ~ Augmented Fey

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Fey

### RaceSubtype ~ Augmented Giant

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Giant

### RaceSubtype ~ Augmented Humanoid

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Humanoid

### RaceSubtype ~ Augmented Magical Beast

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Magical Beast

### RaceSubtype ~ Augmented Monstrous Humanoid

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Monstrous Humanoid

### RaceSubtype ~ Augmented Ooze

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Ooze

### RaceSubtype ~ Augmented Outsider

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Outsider

### RaceSubtype ~ Augmented Plant

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Plant

### RaceSubtype ~ Augmented Undead

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Undead

### RaceSubtype ~ Augmented Vermin

- **REMOVABLE:** YES
- **RACESUBTYPE:** Augmented Vermin

### Non-Ability ~ Strength

- **DEFINESTAT:** NONSTAT|STR

### Non-Ability ~ Dexterity

- **DEFINESTAT:** NONSTAT|DEX

### Non-Ability ~ Constitution

- **DEFINESTAT:** NONSTAT|CON

### Non-Ability ~ Intelligence

- **DEFINESTAT:** NONSTAT|INT

### Non-Ability ~ Wisdom

- **DEFINESTAT:** NONSTAT|WIS

### Non-Ability ~ Charisma

- **DEFINESTAT:** NONSTAT|CHA

### F

- **SIZE:** F

### D

- **SIZE:** D

### T

- **SIZE:** T

### S

- **SIZE:** S

### M

- **SIZE:** M

### L

- **SIZE:** L

### H

- **SIZE:** H

### C

- **SIZE:** C

### C+

- **SIZE:** P

### Wyrmling

- **SUBRACE:** YES

### Very Young

- **SUBRACE:** YES

### Young

- **SUBRACE:** YES

### Juvenile

- **SUBRACE:** YES

### Young Adult

- **SUBRACE:** YES

### Adult

- **SUBRACE:** YES

### Mature Adult

- **SUBRACE:** YES

### Old

- **SUBRACE:** YES

### Very Old

- **SUBRACE:** YES

### Ancient

- **SUBRACE:** YES

### Wyrm

- **SUBRACE:** YES

### Great Wyrm

- **SUBRACE:** YES

### Half Hitdie

- **HITDIE:** %/2|CLASS.TYPE=Monster

### Quarter Hitdie

- **HITDIE:** %/4|CLASS.TYPE=Monster

### Eighth Hitdie

- **HITDIE:** %/8|CLASS.TYPE=Monster

### Drow Male

- **FAVOREDCLASS:** Wizard
- **GENDERLOCK:** Male

### Drow Female

- **FAVOREDCLASS:** Cleric
- **GENDERLOCK:** Female

### Hunting

- **BONUS:** MOVEADD|TYPE.Walk|10
- **BONUS:** SKILL|Jump|10|TYPE=Racial
- **BONUS:** SKILL|Spot|8|TYPE=Racial
- **REMOVABLE:** YES
- **SUBRACE:** YES

### Web Spinning

- **BONUS:** VAR|MonstrousSpiderWebBreakDC|4|TYPE=Racial
- **BONUS:** VAR|MonstrousSpiderWebHp|2
- **BONUS:** VAR|MonstrousSpiderWebHp|4
- **BONUS:** VAR|MonstrousSpiderWebHp|6
- **BONUS:** VAR|MonstrousSpiderWebHp|12
- **BONUS:** VAR|MonstrousSpiderWebHp|14
- **BONUS:** VAR|MonstrousSpiderWebHp|16
- **BONUS:** VAR|MonstrousSpiderWebHp|18
- **BONUS:** VAR|MonstrousSpiderWebEscapeDC,MonstrousSpiderWebBreakDC|0
- **BONUS:** VAR|MonstrousSpiderWebEscapeDC,MonstrousSpiderWebBreakDC|0
- **BONUS:** VAR|MonstrousSpiderWebEscapeDC,MonstrousSpiderWebBreakDC|1
- **BONUS:** VAR|MonstrousSpiderWebEscapeDC,MonstrousSpiderWebBreakDC|2
- **BONUS:** VAR|MonstrousSpiderWebEscapeDC,MonstrousSpiderWebBreakDC|4
- **BONUS:** VAR|MonstrousSpiderWebEscapeDC,MonstrousSpiderWebBreakDC|8
- **BONUS:** VAR|MonstrousSpiderWebEscapeDC,MonstrousSpiderWebBreakDC|16
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Spider ~ Web
- **REMOVABLE:** YES
- **SUBRACE:** YES
- **TEMPDESC:** Web-spinning spiders have a +8 racial bonus on Hide and Move Silently checks when using their webs
- **TEMPBONUS:** PC|SKILL|Hide,Move Silently|8|TYPE=Racial

### Pixie Ability (Otto's Irresistible Dance)

- **CR:** 1
- **LEVELADJUSTMENT:** 3
- **PRERACE:** 1,Sprite (Pixie)
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=8|Irresistible Dance,18+CHA

### Unable to use Otto's Irresistible Dance


### Abyssal Greater Basilisk

- **RACETYPE:** Outsider
- **RACESUBTYPE:** Augmented Magical Beast|Extraplanar

### Default Aasimar

- **CSKILL:** Heal|Knowledge (Religion)|Listen|Spot

### Default Tiefling

- **CSKILL:** Bluff|Hide|Move Silently|Sleight of Hand

### Default Roper

- **BONUS:** WEAPONPROF=Strand|TOHIT|2

### Default Cauchemar Nightmare

- **CSKILL:** Bluff|Knowledge (Arcana)

### Male Only

- **GENDERLOCK:** Male

### Female Only

- **GENDERLOCK:** Female

### Hydra (Pyrohydra)

- **PRERACE:** 1,Hydra%
- **!PRETEMPLATE:** 1,Hydra (Cryohydra)
- **ABILITY:** Special Ability|AUTOMATIC|Hydra ~ Breath Fire|Immunity to Fire
- **SUBRACE:** Pyrohydra
- **RACESUBTYPE:** Fire

### Hydra (Cryohydra)

- **PRERACE:** 1,Hydra%
- **!PRETEMPLATE:** 1,Hydra (Pyrohydra)
- **ABILITY:** Special Ability|AUTOMATIC|Hydra ~ Breath Frost|Immunity to Cold
- **SUBRACE:** Cryohydra
- **RACESUBTYPE:** Cold

### Sahuagin (Mutant)

- **HANDS:** 4
- **PRERACE:** 1,Sahuagin
- **SUBRACE:** Mutant

### Troll (Scrag)

- **PRERACE:** 1,Troll
- **BONUS:** MOVEADD|TYPE.Walk|-10
- **ABILITY:** Special Ability|AUTOMATIC|Scrag ~ Regenerate in Water
- **MOVE:** Swim,40
- **SUBRACE:** Scrag
- **RACESUBTYPE:** Aquatic

### Celestial

- **DR:** 5/Magic
- **DR:** 10/Magic
- **LEVELADJUSTMENT:** 3
- **TEMPLATE:** CHOOSE:Celestial (Animal)|Celestial (Vermin)
- **TEMPLATE:** CHOOSE:Int Bonus +1|Int Bonus +2|Int Bonus +3
- **DEFINE:** CelestialSR|0
- **PREALIGN:** LG,NG,CG
- **PRERACE:** 1,RACETYPE=Animal,RACETYPE=Aberration,RACETYPE=Dragon,RACETYPE=Fey,RACETYPE=Giant,RACETYPE=Humanoid,RACETYPE=Magical Beast,RACETYPE=Monstrous Humanoid,RACETYPE=Plant,RACETYPE=Vermin
- **!PRETEMPLATE:** 1,Incorporeal
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** VAR|AcidResistanceBonus,ColdResistanceBonus,ElectricityResistanceBonus|5+((TL>=8)*5)
- **BONUS:** VAR|SmiteEvil|1
- **BONUS:** VAR|SmiteEvilDamage|min(TL,20)
- **BONUS:** VAR|CelestialSR|min(TL+5,25)
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Acid|Resistance to Cold|Resistance to Electricity|Smite Evil
- **SR:** CelestialSR
- **RACESUBTYPE:** Extraplanar

### Celestial (Animal)

- **PRERACE:** 1,TYPE=Animal
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Augmented Animal

### Celestial (Vermin)

- **DEFINESTAT:** STAT|INT
- **PRERACE:** 1,TYPE=Vermin
- **KIT:** 1|Vermin Intelligence
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Augmented Vermin

### Half-Celestial

- **DR:** 5/Magic
- **LEVELADJUSTMENT:** 4
- **DEFINE:** HalfCelestialSR|0
- **PREALIGN:** LG,LN,NG,TN,CG,CN
- **!PRERACE:** 1,RACETYPE=Undead,RACETYPE=Construct
- **PRESTAT:** 1,INT=4
- **!PRETEMPLATE:** 1,Incorporeal
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor.STACK
- **BONUS:** DR|Magic|5
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** STAT|STR,CON,WIS,CHA|4
- **BONUS:** STAT|DEX,INT|2
- **BONUS:** VAR|AcidResistanceBonus,ColdResistanceBonus,ElectricityResistanceBonus|10
- **BONUS:** VAR|HalfCelestialSR|min(TL+10,35)
- **BONUS:** VAR|SmiteEvil|1
- **BONUS:** VAR|SmiteEvilDamage|min(TL,20)
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Half-Celestial ~ Daylight|Half-Celestial ~ Poison Resistance|Half-Celestial ~ Smite Evil|Half-Celestial ~ Wings|Immunity to Disease|Resistance to Acid|Resistance to Cold|Resistance to Electricity
- **MOVECLONE:** Walk,Fly,*2
- **SR:** HalfCelestialSR
- **RACETYPE:** Outsider
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Holy Word,17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Hallow,15+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Charm Monster (Mass),18+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Summon Monster IX,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Resurrection,17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Aid,12+CHA|Detect Evil,11+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Cure Serious Wounds,13+CHA|Neutralize Poison,13+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Holy Smite,14+CHA|Remove Disease,13+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Dispel Evil,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Bless,11+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Holy Aura,18+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Protection from Evil,11+CHA

### Half-Celestial Wings

- **TEMPLATE:** CHOOSE:Has Pre-existing Fly Speed ~ Half-Celestial|No Pre-existing Fly Speed ~ Half-Celestial

### Has Pre-existing Fly Speed ~ Half-Celestial

- **PREMOVE:** 1,Fly=1

### No Pre-existing Fly Speed ~ Half-Celestial

- **!PREMOVE:** 1,Fly=1
- **BONUS:** VAR|Maneuverability|3
- **MOVE:** Fly,60

### Fiendish

- **DR:** 5/Magic
- **DR:** 10/Magic
- **LEVELADJUSTMENT:** 3
- **TEMPLATE:** CHOOSE:Fiendish (Animal)|Fiendish (Vermin)
- **TEMPLATE:** CHOOSE:Int Bonus +1|Int Bonus +2|Int Bonus +3
- **DEFINE:** FiendishSR|0
- **PREALIGN:** LN,LE,TN,NE,CN,CE
- **PRERACE:** 1,RACETYPE=Animal,RACETYPE=Aberration,RACETYPE=Dragon,RACETYPE=Fey,RACETYPE=Giant,RACETYPE=Humanoid,RACETYPE=Magical Beast,RACETYPE=Monstrous Humanoid,RACETYPE=Ooze,RACETYPE=Plant,RACETYPE=Vermin
- **!PRETEMPLATE:** 1,Incorporeal
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** VAR|ColdResistanceBonus,FireResistanceBonus|5+((TL>=8)*5)
- **BONUS:** VAR|SmiteGood|1
- **BONUS:** VAR|SmiteGoodDamage|min(TL,20)
- **BONUS:** VAR|FiendishSR|min(TL+5,25)
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Cold|Resistance to Fire|Smite Good
- **SR:** FiendishSR
- **RACESUBTYPE:** Extraplanar

### Fiendish (Animal)

- **PRERACE:** 1,RACETYPE=Animal
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Augmented Animal

### Fiendish (Vermin)

- **DEFINESTAT:** STAT|INT
- **PRERACE:** 1,RACETYPE=Vermin
- **KIT:** 1|Vermin Intelligence
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Augmented Vermin

### Fiendish (Magical Beast)

- **TEMPLATE:** Fiendish

### Half-Fiend

- **DR:** 5/Magic
- **LEVELADJUSTMENT:** 4
- **TEMPLATE:** CHOOSE:Bite ~ Claw (Fine)|Bite ~ Claw (Diminutive)|Bite ~ Claw (Tiny)|Bite ~ Claw (Small)|Bite ~ Claw (Medium)|Bite ~ Claw (Large)|Bite ~ Claw (Huge)|Bite ~ Claw (Gargantuan)|Bite ~ Claw (Colossal)
- **DEFINE:** HalfFiendSR|0
- **PREALIGN:** LE,NE,CE
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor.STACK
- **BONUS:** DR|Magic|5
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|AcidResistanceBonus,ColdResistanceBonus,ElectricityResistanceBonus,FireResistanceBonus|10
- **BONUS:** VAR|HalfFiendSR|TL+10
- **BONUS:** VAR|SmiteGood|1
- **BONUS:** VAR|SmiteGoodDamage|min(TL,20)
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base
- **ABILITY:** Special Ability|AUTOMATIC|Half-Fiend ~ Smite Good|Half-Fiend ~ Special Qualities|Half-Fiend ~ Speed|Immunity to Poison|Resistance to Acid|Resistance to Cold|Resistance to Electricity|Resistance to Fire
- **MOVECLONE:** Walk,Fly,*1
- **SR:** HalfFiendSR
- **RACETYPE:** Outsider
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Blasphemy,17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Unhallow,15+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Horrid Wilting,18+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Summon Monster IX,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Destruction,17+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Desecrate,12+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=TL|Contagion,13+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Unholy Aura,18+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Poison,14+CHA
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=TL|Darkness,12+CHA

### Half-Dragon

- **HITDIE:** %up1|CLASS.TYPE=Monster
- **CR:** 2
- **LEVELADJUSTMENT:** 3
- **TEMPLATE:** CHOOSE:Half-Dragon Wings ~ Normal|Half-Dragon Wings ~ Fast
- **TEMPLATE:** CHOOSE:Bite ~ Claw (Fine)|Bite ~ Claw (Diminutive)|Bite ~ Claw (Tiny)|Bite ~ Claw (Small)|Bite ~ Claw (Medium)|Bite ~ Claw (Large)|Bite ~ Claw (Huge)|Bite ~ Claw (Gargantuan)|Bite ~ Claw (Colossal)
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor.STACK
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|CON,INT,CHA|2
- **BONUS:** VAR|HalfDragonBreathDC|DefaultDCCon
- **BONUS:** MONSKILLPTS|LOCKNUMBER|6
- **ABILITY:** Special Ability|AUTOMATIC|Low-Light Vision
- **RACETYPE:** Dragon

### Half-Dragon (Black)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** CE
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Line of Acid|Immunity to Acid

### Half-Dragon (Blue)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** LE
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Line of Electricity|Immunity to Electricity

### Half-Dragon (Green)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** LE
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Cone of Acid|Immunity to Acid

### Half-Dragon (Red)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** CE
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Cone of Fire|Immunity to Fire

### Half-Dragon (White)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** CE
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Cone of Cold|Immunity to Cold

### Half-Dragon (Brass)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** CG
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Line of Fire|Immunity to Fire

### Half-Dragon (Bronze)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** LG
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Line of Electricity|Immunity to Electricity

### Half-Dragon (Copper)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** CG
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Line of Acid|Immunity to Acid

### Half-Dragon (Gold)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** LG
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Cone of Fire|Immunity to Fire

### Half-Dragon (Silver)

- **TEMPLATE:** Half-Dragon
- **PREALIGN:** LG
- **ABILITY:** Special Ability|AUTOMATIC|Half-Dragon Breath Weapon ~ Cone of Cold|Immunity to Cold

### Half-Dragon Wings ~ Normal

- **!PREMOVE:** 1,Walk=60
- **PRESIZEGTEQ:** L
- **BONUS:** VAR|Maneuverability|3
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Half-Dragon ~ Speed
- **MOVECLONE:** Walk,Fly,*2

### Half-Dragon Wings ~ Fast

- **PREMOVE:** 1,Walk=60
- **PRESIZEGTEQ:** L
- **BONUS:** VAR|Maneuverability|3
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Half-Dragon ~ Speed
- **MOVE:** Fly,120

### Lycanthrope

- **TEMPLATE:** CHOOSE:Werebear|Wereboar|Wererat|Weretiger|Werewolf|Dire Werewolf|Dire Wereboar
- **TEMPLATE:** CHOOSE:Natural Lycanthrope|Afflicted Lycanthrope
- **DEFINE:** NoTypeTraits|0
- **PRERACE:** 1,RACETYPE=Humanoid,RACETYPE=Giant
- **!PRETEMPLATE:** 1,Lycanthrope
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor.STACK
- **BONUS:** HP|CURRENTMAX|(AnimalCon/2)*AnimalHD|!PRETEMPLATE:1,Lycanthrope (Animal Form),Lycanthrope (Hybrid Form)
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|NoTypeTraits|1
- **BONUS:** VAR|HasLowLightVision|1
- **ABILITY:** Special Ability|AUTOMATIC|Scent
- **ABILITY:** FEAT|VIRTUAL|Iron Will
- **RACESUBTYPE:** Shapechanger

### Natural Lycanthrope

- **LEVELADJUSTMENT:** 3
- **PRETEMPLATE:** 1,Lycanthrope
- **!PRETEMPLATE:** 1,Afflicted Lycanthrope

### Afflicted Lycanthrope

- **LEVELADJUSTMENT:** 3
- **PRETEMPLATE:** 1,Lycanthrope
- **!PRETEMPLATE:** 1,Natural Lycanthrope
- **CSKILL:** Control Shape

### Lycanthrope (Animal Form)

- **SIZE:** AnimalSize
- **LEGS:** 4
- **HANDS:** 0
- **DR:** 10/silver
- **DR:** 5/silver
- **TEMPLATE:** CHOOSE:Werebear Attacks|Wereboar Attacks|Wererat Attacks|Weretiger Attacks|Werewolf Attacks|Dire Werewolf Attacks|Dire Wereboar Attacks
- **PRETEMPLATE:** 1,Lycanthrope
- **!PRETEMPLATE:** 1,Lycanthrope (Hybrid Form)
- **BONUS:** COMBAT|AC|AnimalAC|TYPE=NaturalArmor
- **BONUS:** HP|CURRENTMAX|-((AnimalCon/2)*(TL-AnimalHD))
- **BONUS:** MOVEADD|TYPE.Walk|AnimalMove-MOVEBASE
- **BONUS:** SLOTS|WEAPON|-2
- **BONUS:** SLOTS|ARMOR|-1
- **BONUS:** STAT|STR|AnimalStr
- **BONUS:** STAT|DEX|AnimalDex
- **BONUS:** STAT|CON|AnimalCon

### Lycanthrope (Hybrid Form)

- **SIZE:** max(AnimalSize,var("RACESIZE"))
- **DR:** 10/silver
- **DR:** 5/silver
- **TEMPLATE:** CHOOSE:Hybrid Attacks (Small)|Hybrid Attacks (Medium)|Hybrid Attacks (Medium~Wereboar)|Hybrid Attacks (Large)|Hybrid Attacks (Large~Dire Wereboar)|Hybrid Attacks (Huge)
- **PRETEMPLATE:** 1,Lycanthrope
- **!PRETEMPLATE:** 1,Lycanthrope (Animal Form)
- **BONUS:** COMBAT|AC|AnimalAC|TYPE=NaturalArmor
- **BONUS:** HP|CURRENTMAX|-((AnimalCon/2)*(TL-AnimalHD))
- **BONUS:** STAT|STR|AnimalStr
- **BONUS:** STAT|DEX|AnimalDex
- **BONUS:** STAT|CON|AnimalCon

### Werebear

- **CR:** 4
- **DEFINE:** AnimalSize|0
- **DEFINE:** AnimalHD|0
- **DEFINE:** AnimalMove|0
- **DEFINE:** AnimalAC|0
- **DEFINE:** AnimalStr|0
- **DEFINE:** AnimalDex|0
- **DEFINE:** AnimalCon|0
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=1|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=2|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=3|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=4|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=5|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=6|-1
- **BONUS:** VAR|AnimalSize|5
- **BONUS:** VAR|AnimalHD|6
- **BONUS:** VAR|AnimalMove|40
- **BONUS:** VAR|AnimalAC|5
- **BONUS:** VAR|AnimalStr|16
- **BONUS:** VAR|AnimalDex|2
- **BONUS:** VAR|AnimalCon|8
- **CSKILL:** Listen|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Werebear ~ Alternate Form|Werebear ~ Bear Empathy|Werebear ~ Curse of Lycanthropy
- **ABILITY:** Special Ability|VIRTUAL|Werebear ~ Improved Grab
- **ABILITY:** FEAT|VIRTUAL|Track
- **ADDLEVEL:** Animal|6

### Werebear Attacks

- **PRETEMPLATE:** 1,Werebear
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6

### Wereboar

- **CR:** 3
- **DEFINE:** AnimalSize|0
- **DEFINE:** AnimalHD|0
- **DEFINE:** AnimalMove|0
- **DEFINE:** AnimalAC|0
- **DEFINE:** AnimalStr|0
- **DEFINE:** AnimalCon|0
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=1|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=2|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=3|-1
- **BONUS:** VAR|AnimalSize|4
- **BONUS:** VAR|AnimalHD|3
- **BONUS:** VAR|AnimalMove|40
- **BONUS:** VAR|AnimalAC|6
- **BONUS:** VAR|AnimalStr|4
- **BONUS:** VAR|AnimalCon|6
- **CSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Wereboar ~ Alternate Form|Wereboar ~ Boar Empathy|Wereboar ~ Curse of Lycanthropy|Wereboar ~ Ferocity
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **ADDLEVEL:** Animal|3

### Wereboar Attacks

- **PRETEMPLATE:** 1,Wereboar
- **BONUS:** WEAPONPROF=Gore|DAMAGE|STR/2
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8

### Wererat

- **CR:** 2
- **DEFINE:** AnimalSize|0
- **DEFINE:** AnimalHD|0
- **DEFINE:** AnimalMove|0
- **DEFINE:** AnimalAC|0
- **DEFINE:** AnimalDex|0
- **DEFINE:** AnimalCon|0
- **BONUS:** MOVEADD|TYPE.Climb|-10
- **BONUS:** SKILL|Swim|8|TYPE=Racial
- **BONUS:** SKILL|Climb,Swim|DEX-STR
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=1|-1
- **BONUS:** VAR|AnimalSize|3
- **BONUS:** VAR|AnimalHD|1
- **BONUS:** VAR|AnimalMove|40
- **BONUS:** VAR|AnimalAC|1
- **BONUS:** VAR|AnimalStr|6
- **BONUS:** VAR|AnimalCon|2
- **CSKILL:** Climb|Hide|Listen|Move Silently|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Wererat ~ Alternate Form|Wererat ~ Curse of Lycanthropy|Wererat ~ Rat Empathy
- **ABILITY:** Special Ability|VIRTUAL|Wererat ~ Disease
- **ABILITY:** FEAT|VIRTUAL|Weapon Finesse
- **ADDLEVEL:** Animal (Will)|1

### Wererat Attacks

- **PRETEMPLATE:** 1,Wererat
- **BONUS:** WEAPONPROF=Bite|DAMAGE|STR/2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing.Disease,*1,1d4

### Weretiger

- **CR:** 4
- **DEFINE:** AnimalSize|0
- **DEFINE:** AnimalHD|0
- **DEFINE:** AnimalMove|0
- **DEFINE:** AnimalAC|0
- **DEFINE:** AnimalStr|0
- **DEFINE:** AnimalDex|0
- **DEFINE:** AnimalCon|0
- **BONUS:** SKILL|Balance,Hide,Move Silently|4|TYPE=Racial
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=1|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=2|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=3|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=4|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=5|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=6|-1
- **BONUS:** VAR|AnimalSize|5
- **BONUS:** VAR|AnimalHD|6
- **BONUS:** VAR|AnimalMove|40
- **BONUS:** VAR|AnimalAC|3
- **BONUS:** VAR|AnimalStr|12
- **BONUS:** VAR|AnimalDex|4
- **BONUS:** VAR|AnimalCon|4
- **CSKILL:** Balance|Hide|Listen|Move Silently|Spot|Swim
- **ABILITY:** Special Ability|AUTOMATIC|Weretiger ~ Alternate Form|Weretiger ~ Curse of Lycanthropy|Weretiger ~ Tiger Empathy
- **ABILITY:** Special Ability|VIRTUAL|Weretiger ~ Improved Grab|Weretiger ~ Pounce|Weretiger ~ Rake
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **ADDLEVEL:** Animal|6

### Weretiger Attacks

- **PRETEMPLATE:** 1,Weretiger
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8

### Werewolf

- **CR:** 2
- **DEFINE:** AnimalSize|0
- **DEFINE:** AnimalHD|0
- **DEFINE:** AnimalMove|0
- **DEFINE:** AnimalAC|0
- **DEFINE:** AnimalStr|0
- **DEFINE:** AnimalDex|0
- **DEFINE:** AnimalCon|0
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=1|-1
- **BONUS:** SKILLPOOL|CLASS.Animal;LEVEL=2|-1
- **BONUS:** VAR|AnimalSize|4
- **BONUS:** VAR|AnimalHD|2
- **BONUS:** VAR|AnimalMove|50
- **BONUS:** VAR|AnimalAC|2
- **BONUS:** VAR|AnimalStr|2
- **BONUS:** VAR|AnimalDex|4
- **BONUS:** VAR|AnimalCon|4
- **CSKILL:** Hide|Listen|Move Silently|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Werewolf ~ Alternate Form|Werewolf ~ Curse of Lycanthropy|Werewolf ~ Wolf Empathy
- **ABILITY:** Special Ability|VIRTUAL|Werewolf ~ Trip
- **ABILITY:** FEAT|VIRTUAL|Track
- **ADDLEVEL:** Animal|2

### Werewolf Attacks

- **PRETEMPLATE:** 1,Werewolf
- **BONUS:** WEAPONPROF=Bite|DAMAGE|STR/2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6

### Dire Wereboar

- **CR:** 4
- **DEFINE:** AnimalSize|0
- **DEFINE:** AnimalHD|0
- **DEFINE:** AnimalMove|0
- **DEFINE:** AnimalAC|0
- **DEFINE:** AnimalStr|0
- **DEFINE:** AnimalCon|0
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=1|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=2|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=3|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=4|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=5|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=6|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=7|-1
- **BONUS:** VAR|AnimalSize|5
- **BONUS:** VAR|AnimalHD|7
- **BONUS:** VAR|AnimalMove|40
- **BONUS:** VAR|AnimalAC|6
- **BONUS:** VAR|AnimalStr|16
- **BONUS:** VAR|AnimalCon|6
- **CSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Dire Wereboar ~ Alternate Form|Dire Wereboar ~ Boar Empathy|Dire Wereboar ~ Curse of Lycanthropy|Dire Wereboar ~ Ferocity
- **ABILITY:** FEAT|VIRTUAL|Alertness
- **ADDLEVEL:** Animal (Will)|7

### Dire Wereboar Attacks

- **PRETEMPLATE:** 1,Dire Wereboar
- **BONUS:** WEAPONPROF=Gore|DAMAGE|STR/2
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8

### Dire Werewolf

- **CR:** 4
- **DEFINE:** AnimalSize|0
- **DEFINE:** AnimalHD|0
- **DEFINE:** AnimalMove|0
- **DEFINE:** AnimalAC|0
- **DEFINE:** AnimalStr|0
- **DEFINE:** AnimalDex|0
- **DEFINE:** AnimalCon|0
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=1|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=2|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=3|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=4|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=5|-1
- **BONUS:** SKILLPOOL|CLASS.Animal (Will);LEVEL=6|-1
- **BONUS:** VAR|AnimalSize|5
- **BONUS:** VAR|AnimalHD|6
- **BONUS:** VAR|AnimalMove|40
- **BONUS:** VAR|AnimalAC|4
- **BONUS:** VAR|AnimalStr|14
- **BONUS:** VAR|AnimalDex|4
- **BONUS:** VAR|AnimalCon|6
- **CSKILL:** Hide|Listen|Move Silently|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Werewolf ~ Wolf Empathy
- **ABILITY:** Special Ability|VIRTUAL|Werewolf ~ Trip
- **ABILITY:** FEAT|VIRTUAL|Track
- **ADDLEVEL:** Animal (Will)|6

### Dire Werewolf Attacks

- **PRETEMPLATE:** 1,Dire Werewolf
- **BONUS:** WEAPONPROF=Bite|DAMAGE|STR/2
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8

### Hybrid Attacks (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4

### Hybrid Attacks (Medium)

- **PRESIZEEQ:** M
- **!PRETEMPLATE:** 1,Wereboar
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6

### Hybrid Attacks (Medium~Wereboar)

- **PRESIZEEQ:** M
- **PRETEMPLATE:** 1,Wereboar
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Gore,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6

### Hybrid Attacks (Large)

- **PRESIZEEQ:** L
- **!PRETEMPLATE:** 1,Dire Wereboar
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8

### Hybrid Attacks (Large~Dire Wereboar)

- **PRESIZEEQ:** L
- **PRETEMPLATE:** 1,Dire Wereboar
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Gore,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8

### Hybrid Attacks (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6

### Ghost

- **HITDIE:** 12
- **CR:** 2
- **LEVELADJUSTMENT:** 5
- **TEMPLATE:** CHOOSE:Ghost (1 Special Attack)|Ghost (2 Special Attacks)|Ghost (3 Special Attacks)
- **DEFINE:** GhostAbilityDC|0
- **PRERACE:** 1,RACETYPE=Aberration,RACETYPE=Animal,RACETYPE=Dragon,RACETYPE=Giant,RACETYPE=Humanoid,RACETYPE=Magical Beast,RACETYPE=Monstrous Humanoid,RACETYPE=Plant
- **PRESTAT:** 1,CHA=6
- **BONUS:** COMBAT|AC|max(CHA,1)|TYPE=Deflection
- **BONUS:** SKILL|Hide,Listen,Search,Spot|8|TYPE=Racial
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|TurnResistBonus|4
- **BONUS:** VAR|GhostAbilityDC|10+(TL/2)+CHA
- **BONUS:** VAR|Maneuverability|5
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability|Ghost ~ Manifestation|Ghost ~ Rejuvenation|Ghost ~ Turn Resistance
- **MOVE:** Fly,30
- **RACETYPE:** Undead
- **RACETYPE:** Undead
- **RACESUBTYPE:** Incorporeal
- **RACESUBTYPE:** Incorporeal

### Lich

- **HITDIE:** 12
- **CR:** 2
- **DR:** 15/Bludgeoning and Magic
- **LEVELADJUSTMENT:** 4
- **DEFINE:** LichAbilityDC|0
- **PREALIGN:** LE,NE,CE
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide,Listen,Move Silently,Search,Sense Motive,Spot|8|TYPE=Racial
- **BONUS:** STAT|INT,WIS,CHA|2
- **BONUS:** VAR|TurnResistBonus|4
- **BONUS:** VAR|LichAbilityDC|10+(TL/2)+CHA
- **BONUS:** VAR|FearAuraRadius|60
- **BONUS:** VAR|FearAuraDC|LichAbilityDC
- **ABILITY:** Special Ability|AUTOMATIC|Lich ~ Abilities|Lich ~ Damage Reduction|Lich ~ Fear Aura|Lich ~ Immunities|Lich ~ Paralyzing Touch|Lich ~ Skills|Lich ~ Special Attacks|Lich ~ Special Qualities|Lich ~ Spells|Lich ~ Turn Resistance
- **RACETYPE:** Undead
- **RACETYPE:** Undead

### Skeleton

- **HITDIE:** 12
- **DR:** 5/Bludgeoning
- **TEMPLATE:** CHOOSE:Claw (Fine)|Claw (Diminutive)|Claw (Tiny)|Claw (Small)|Claw (Medium)|Claw (Large)|Claw (Huge)|Claw (Gargantuan)|Claw (Colossal)
- **DEFINESTAT:** NONSTAT|INT
- **DEFINESTAT:** NONSTAT|WIS
- **DEFINESTAT:** LOCK|CHA|1
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** STAT|DEX|2
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold
- **ABILITY:** FEAT|AUTOMATIC|Improved Initiative
- **RACETYPE:** Undead
- **RACETYPE:** Undead
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|HD/3
- **BONUS:** SAVE|BASE.Will|HD/2+2

### Vampire

- **HITDIE:** 12
- **CR:** 2
- **DR:** 10/Silver and Magic
- **LEVELADJUSTMENT:** 8
- **TEMPLATE:** CHOOSE:Slam (Fine)|Slam (Diminutive)|Slam (Tiny)|Slam (Small)|Slam (Medium)|Slam (Large)|Slam (Huge)|Slam (Gargantuan)|Slam (Colossal)
- **DEFINE:** VampireAbilityDC|0
- **PREALIGN:** LE,NE,CE
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor.STACK
- **BONUS:** SKILL|Bluff,Hide,Listen,Move Silently,Search,Sense Motive,Spot|8|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|FastHealing|5
- **BONUS:** VAR|ColdResistanceBonus,ElectricityResistanceBonus|10
- **BONUS:** VAR|TurnResistBonus|4
- **BONUS:** VAR|VampireAbilityDC|15+CHA
- **ABILITY:** Special Ability|AUTOMATIC|Resistance to Cold|Resistance to Electricity|Vampire ~ Alternate Form|Vampire ~ Blood Drain|Vampire ~ Children of the Night|Vampire ~ Create Spawn|Vampire ~ Damage Reduction|Vampire ~ Dominate|Vampire ~ Energy Drain|Vampire ~ Fast Healing|Vampire ~ Gaseous Form|Vampire ~ Resistances|Vampire ~ Special Qualities|Vampire ~ Spider Climb|Vampire ~ Turn Resistance|Vampire ~ Vampire Weaknesses
- **ABILITY:** FEAT|AUTOMATIC|Dodge
- **ABILITY:** FEAT|AUTOMATIC|Alertness|Combat Reflexes|Improved Initiative|Lightning Reflexes
- **RACETYPE:** Undead
- **RACETYPE:** Undead

### Zombie

- **HITDIE:** 12
- **DR:** 5/Slashing
- **TEMPLATE:** CHOOSE:Slam (Fine)|Slam (Diminutive)|Slam (Tiny)|Slam (Small)|Slam (Medium)|Slam (Large)|Slam (Huge)|Slam (Gargantuan)|Slam (Colossal)
- **DEFINESTAT:** NONSTAT|INT
- **DEFINESTAT:** NONSTAT|WIS
- **DEFINESTAT:** LOCK|CHA|1
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** MISC|CR|1
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|-2
- **ABILITY:** Special Ability|AUTOMATIC|Zombie ~ Single Actions Only
- **RACETYPE:** Undead
- **RACETYPE:** Undead
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|HD/3
- **BONUS:** SAVE|BASE.Will|HD/2+2

### Ghost (1 Special Attack)

- **BONUS:** ABILITYPOOL|Ghost Ability|1

### Ghost (2 Special Attacks)

- **BONUS:** ABILITYPOOL|Ghost Ability|2

### Ghost (3 Special Attacks)

- **BONUS:** ABILITYPOOL|Ghost Ability|3

### Bite ~ Claw (Fine)

- **PRESIZEEQ:** F
- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1

### Bite ~ Claw (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d2|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1

### Bite ~ Claw (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d2|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d2

### Bite ~ Claw (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d3

### Bite ~ Claw (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d4

### Bite ~ Claw (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d6

### Bite ~ Claw (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d8

### Bite ~ Claw (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,3d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,2d6

### Bite ~ Claw (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,3d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,3d6

### Claw (Fine)

- **PRESIZEEQ:** F
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1

### Claw (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1

### Claw (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d2

### Claw (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3

### Claw (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4

### Claw (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6

### Claw (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8

### Claw (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6

### Claw (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d8

### Slam (Fine)

- **PRESIZEEQ:** F
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1

### Slam (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d2

### Slam (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d3

### Slam (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4

### Slam (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6

### Slam (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8

### Slam (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6

### Slam (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8

### Slam (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,4d6

### Int Bonus +1

- **PREVAREQ:** INTSCORE,2
- **BONUS:** STAT|INT|1

### Int Bonus +2

- **PREVAREQ:** INTSCORE,1
- **BONUS:** STAT|INT|2

### Int Bonus +3

- **PREVAREQ:** INTSCORE,0
- **BONUS:** STAT|INT|3

### Deep

- **FAVOREDCLASS:** Fighter
- **SUBRACE:** Deep

### Duergar

- **LEVELADJUSTMENT:** 1
- **FAVOREDCLASS:** Fighter
- **SUBRACE:** Duergar

### Mountain

- **FAVOREDCLASS:** Fighter
- **SUBRACE:** Mountain

### Aquatic

- **FAVOREDCLASS:** Fighter
- **MOVE:** Swim,40
- **SUBRACE:** Aquatic
- **RACESUBTYPE:** Aquatic
- **VISION:** Superior Low-Light Vision

### Drow

- **CR:** 1
- **LEVELADJUSTMENT:** 3
- **SUBRACE:** Drow

### Gray

- **FAVOREDCLASS:** Wizard
- **SUBRACE:** Gray

### Wild

- **FAVOREDCLASS:** Sorcerer
- **SUBRACE:** Wild

### Wood

- **FAVOREDCLASS:** Ranger
- **SUBRACE:** Wood

### Svirfneblin

- **CR:** 1
- **LEVELADJUSTMENT:** 3
- **FAVOREDCLASS:** Rogue
- **SUBRACE:** Svirfneblin

### Forest

- **FAVOREDCLASS:** Bard
- **SUBRACE:** Forest

### Tallfellow

- **FAVOREDCLASS:** Rogue
- **SUBRACE:** Tallfellow

### Language ~ Bonus (Duergar)

- **LANGBONUS:** Draconic,Giant,Goblin,Orc,Terran

### Language ~ Bonus (Drow)

- **LANGBONUS:** Abyssal,Aquan,Draconic,Drow Sign Language,Gnome,Goblin,Kuo-toan

### Language ~ Bonus (Svirfneblin)

- **LANGBONUS:** Dwarven,Elven,Giant,Goblin,Orc,Terran

### Language ~ Bonus (Tallfellow Halfling)

- **LANGBONUS:** Dwarven,Gnome,Goblin,Orc

### Language ~ Bonus (Deep Halfling)

- **LANGBONUS:** Elven,Gnome,Goblin,Orc

### Language ~ Bonus (Goblin)

- **LANGBONUS:** Draconic,Elven,Giant,Gnoll,Orc

### Language ~ Bonus (Hobgoblin)

- **LANGBONUS:** Draconic,Dwarven,Giant,Infernal,Orc

### Language ~ Bonus (Kobold)

- **LANGBONUS:** Common,Undercommon

### Language ~ Bonus (Orc)

- **LANGBONUS:** Dwarven,Giant,Gnoll,Goblin,Undercommon

### Language ~ Bonus (Aasimar)

- **LANGBONUS:** Draconic,Dwarven,Elven,Gnome,Halfling,Sylvan

### Language ~ Bonus (Tiefling)

- **LANGBONUS:** Draconic,Dwarven,Elven,Gnome,Halfling

### Language ~ Aboleth

- **LANGBONUS:** Aboleth

### Language ~ Aquan

- **LANGBONUS:** Aquan

### Language ~ Auran

- **LANGBONUS:** Auran

### Language ~ Blink Dog

- **LANGBONUS:** Blink Dog

### Language ~ Drow Sign Language

- **LANGBONUS:** Drow Sign Language

### Language ~ Ettin Pidgin

- **LANGBONUS:** Ettin Pidgin

### Language ~ Formian

- **LANGBONUS:** Formian

### Language ~ Grimlock

- **LANGBONUS:** Grimlock

### Language ~ Ignan

- **LANGBONUS:** Ignan

### Language ~ Sahuagin

- **LANGBONUS:** Sahuagin

### Language ~ Sphinx

- **LANGBONUS:** Sphinx

### Language ~ Treant

- **LANGBONUS:** Treant

### Language ~ Telepathy

- **LANGBONUS:** Telepathy

### Language ~ Worg

- **LANGBONUS:** Worg

### Language ~ Kuo-toan

- **LANGBONUS:** Kuo-toan

### Language ~ Githyanki

- **LANGBONUS:** Githyanki

### Language ~ Githzerai

- **LANGBONUS:** Githzerai

### Language ~ Slaad

- **LANGBONUS:** Slaad

### Language ~ Yuan-Ti

- **LANGBONUS:** Yuan-Ti

### Five Headed

- **SUBRACE:** Five Headed

### Six Headed

- **SUBRACE:** Six Headed
- **ADDLEVEL:** Magical Beast|1

### Seven Headed

- **SUBRACE:** Seven Headed
- **ADDLEVEL:** Magical Beast|2

### Eight Headed

- **SUBRACE:** Eight Headed
- **ADDLEVEL:** Magical Beast|3

### Nine Headed

- **SUBRACE:** Nine Headed
- **ADDLEVEL:** Magical Beast|4

### Ten Headed

- **SUBRACE:** Ten Headed
- **ADDLEVEL:** Magical Beast|5

### Eleven Headed

- **SUBRACE:** Eleven Headed
- **ADDLEVEL:** Magical Beast|6

### Twelve Headed

- **SUBRACE:** Twelve Headed
- **ADDLEVEL:** Magical Beast|7

### Standard Tiefling

- **LEVELADJUSTMENT:** 1

### Standard Aasimar

- **LEVELADJUSTMENT:** 1


# City of Splendors: Waterdeep

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Special Abilities

### Weapon and Armor Proficiency


You gain no proficiency with weapons, armor, or shields.

### Damage Reduction

- **DEFINE:** GrayHandEnforcerDamageReduction|0
- **DR:** GrayHandEnforcerDamageReduction/-

You have damage reduction %1/- or have existing damage reduction boosted.|Gray Hand EnforcerDamageReduction

### Gray Hand Token


You have a token (a clasp, ring, or brooch) in the shape of the Gray Hand symbol. This grants you a +5 on Charisma-based skill checks made against officers or officials of Waterdeep that see the token. You may not be arrested or hindered unless the official is a Lord, magistrate, or civilar of the Guard or Watch.

### Dragonward Strike

- **DEFINE:** DragonwardStrike|0

By calling upon the power of Ahghairon's dragonward, you can launch a mighty attack. %1 times per day you can make a melee attack with a +4 bonus on your attack roll and a damage bonus of %2. You must declare the strike before your roll the dice. Alternatively, you can use this power to boost a single casting of a spell as though it was effected by the Empower Spell Feat. These abilities are only usable within 10 miles of Waterdeep.|DragonwardStrike|GrayHandEnforcerLVL

### Spell Resistance

- **SR:** TL+5

You now have a spell resistance of %1.|TL+5

### Lord's Boon


You gain the ability to heal your own wounds as a paladin's lay on hands ability. You can heal 20 hp per day all at once or spread out among several uses.

### Moon Blessing


During days and nights of the waning or new moon, you can channel Selune's influence over the weave to reduce the impact of magic directed against you. At the cost of a turn undead attempt, you receive a sared bonus of +%1 on a single saving throw or spell-like ability. You can use this as an immediate action. During days and nights of the waxing or full moon, you can increase the effect of magic cast by you. At the cost of a turn undead attempt, you increase your save DC of a single spell or spell-like ability by +%1. Using this ability is a swift action.|Knight of the Blue MoonLVL

### Special Mount

- **ABILITY:** Special Ability|AUTOMATIC|Special Mount
- **BONUS:** VAR|SpecialMountLVL|PaladinLvl
- **BONUS:** VAR|SpecialMountLVL|SorcererLVL

This ability is identical to the paladin ability of the same name, except the mount will always match your alignment. Levels of Paladin and Knight of the Blue Moon stack for this ability. In addition if you don't have a familiar, your sorcerer or wizard levels stack as well.

### Faerie Fire

- **SPELLS:** Class|TIMES=3|CASTERLEVEL=Knight of the Blue MoonLVL|Faerie Fire

You can use faerie fire as the spell, three times per day.

### Lunar Sight

- **BONUS:** VAR|HasLowlightVision|1

You have low-light vision.

### Divine Moonlight

- **BONUS:** CASTERLEVEL|DESCRIPTOR.Light|1

You gain a +1 Caster level bonus with spells with the Light descriptor.

### Selune's Foresight

- **BONUS:** COMBAT|INITIATIVE|2

You can tap into the prophetic powers associated with the moon, giving you a +2 bonus on initiative rolls.

### Weavesight

- **SPELLS:** Class|TIMES=3|CASTERLEVEL=Knight of the Blue MoonLVL|Arcane Sight

You can use arcane sight as the spell, three times per day.

### Moon Kiss


You can channel the silver light of Selune into the weapons and armor you use. When the moon is waxing or full, at the cost of a single use of turn undead, a magic weapon can be imbued with the brilliant property for 1 round as a swift action. When the moon is waning or new, at the cost of a single attempt to turn undead, you armor receives spell resistance (SR 10 + character level) for 1 round as an immediate action.

### Lore

- **BONUS:** VAR|BardicKnowledgeLvl|MoonstarAgentLVL

Like a bard, you have a knack for picking up odd bits of knowledge. This ability works exactly like the bard ability. If you have bard, Harper agent, or loremaster levels, they stack with this ability.

### Oghma's Insight

- **ADD:** ABILITY|FEAT|VIRTUAL|Skill Focus(Knowledge%)

You gain Skill Focus in any Knowledge skill that you know.

### Laeral's Intuition

- **SPELLS:** Class|TIMES=3|CASTERLEVEL=MoonstarAgentLVL|Detect Thoughts

You can cast detect thoughts as the spell three times per day.

### Mystra's Boon

- **ASPECT:** SaveBonus|+2 save bonus against all spells

You gain a +2 sacred bonus on all saving throws against spells.

### Khelben's Call

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=MoonstarAgentLVL|Sending

You can cast sending as the spell once per day.

### Sun Soul

- **DEFINE:** SunSoulLevel|0
- **SPELLS:** Class|TIMES=1|CASTERLEVEL=SunSoulLevel|Daylight

You can radiate light as per the daylight spell for 1 minute caster level (total of your Sun Soul Monk, Monk, and Paladin levels).

### Monk Abilities


Your Sun Soul Monk levels stack with your Monk levels for flurry of blows, unarmed damage, AC bonus, and unarmored speed bonus.

### Low-Light Vision

- **BONUS:** VAR|HasLowlightVision|1

You gain low-light vision if you don't already have it.

### Sun Soulray

- **DEFINE:** SunSoulrayTimes|0
- **SPELLS:** Class|TIMES=SunSoulrayTimes|CASTERLEVEL=SunSoulLevel|Searing Light,13+WIS

You gain the ability to project a blast of light from your open palm as per the searing light spell.

### Flaming Fists

- **DEFINE:** FlamingFistTimes|0

You can channel your inner light into your unarmed attack as a swift action, giving your hands the flaming weapon ability for %1 rounds. You can do this %2/day. At 6th level, this improves to the flaming burst ability.|WIS|FlamingFistTimes

### Abundant Step

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=((SunSoulMonkLVL+classlevel("Monk")/2))|Dimension Door

You can slip magically between spaces as if using the dimension door spell 1/day.

### Greater Sun Soul

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=SunSoulLevel|Fire Shield

1/day you can wreathe yourself in flames as per the fire shield spell (warm version only).

### Darkvision

- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

You gain Darkvision out to 60 ft if you did not already have it.

### Sun Soulbeam

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=SunSoulLevel|Sunbeam,17+WIS

You can emit a dazzling beam of light from your hands, equivalent to the sunbeam spell once per day.

### Tongue of the Sun and Moon


You can speak with any living creature.

## Ability Categories

### ABILITYCATEGORY:CoralPowerAbility

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Class Ability

### ABILITYCATEGORY:Ranger Lvl2 Feat

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Feats

### ABILITYCATEGORY:Lion and the Unicorn Bonus

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **DISPLAYLOCATION:** Class Ability

### ABILITYCATEGORY:KotFH Bonus Feat

- **EDITABLE:** YES
- **EDITPOOL:** NO
- **FRACTIONALPOOL:** NO
- **ABILITYLIST:** Animal Affinity|Greater Weapon Focus (Lance)|Greater Weapon Specialization (Lance)|Ride-By Attack|Skill Focus (Ride)|Spirited Charge|Trample|Weapon Specialization (Lance)
- **DISPLAYLOCATION:** Feats

## Classes

### CLASS:Gray Hand Enforcer

- **HD:** 10
- **FACT:** ClassType|Prestige
- **FACT:** Abb|GHE
- **MAXLEVEL:** 5
- **DEFINE:** GrayHandEnforcerLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|GrayHandEnforcerLVL|CL
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### 1

- **BONUS:** VAR|GrayHandEnforcerDamageReduction|(CL/2)+1
- **ABILITY:** Special Ability|AUTOMATIC|Gray Hand Enforcer ~ Damage Reduction|Gray Hand Enforcer ~ Gray Hand Token|Gray Hand Enforcer ~ Weapon and Armor Proficiency

### 2

- **BONUS:** VAR|DragonwardStrike|CL/2
- **ADD:** SPELLCASTER|ANY
- **ABILITY:** Special Ability|AUTOMATIC|Gray Hand Enforcer ~ Dragonward Strike

### 3

- **ADD:** SPELLCASTER|ANY

### 4

- **ADD:** SPELLCASTER|ANY
- **ABILITY:** Special Ability|AUTOMATIC|Gray Hand Enforcer ~ Spell Resistance

### 5

- **ADD:** SPELLCASTER|ANY
- **ABILITY:** Special Ability|AUTOMATIC|Gray Hand Enforcer ~ Lord's Boon

### CLASS:Knight of the Blue Moon

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|KotBM
- **MAXLEVEL:** 5
- **DEFINE:** KnightoftheBlueMoonLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|KnightoftheBlueMoonLVL|CL
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Moonstar Agent

- **HD:** 6
- **FACT:** ClassType|Prestige
- **FACT:** Abb|MsAgt
- **MAXLEVEL:** 5
- **DEFINE:** MoonstarAgentLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|MoonstarAgentLVL|CL
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Sun Soul Monk

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|SnSlMk
- **MAXLEVEL:** 10
- **DEFINE:** SunSoulMonkLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|SunSoulMonkLVL|CL
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3

### 6

- **BONUS:** VAR|SunSoulrayTimes,FlamingFistTimes|1

### 7

- **ABILITY:** Special Ability|AUTOMATIC|Sun Soul Monk ~ Greater Sun Soul

### 8

- **BONUS:** VAR|SunSoulrayTimes|1
- **ABILITY:** Special Ability|AUTOMATIC|Sun Soul Monk ~ Darkvision

### 9

- **BONUS:** VAR|FlamingFistTimes|1

### 10

- **ABILITY:** Special Ability|AUTOMATIC|Sun Soul Monk ~ Sun Soulbeam|Tongue of the Sun and Moon

## Equipment

### Longbow (Composite).COPY=Bow of Hosark


### Axe of Heavenly Fire

- **PROFICIENCY:** WEAPON|Greataxe
- **COST:** 40
- **WT:** 16
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 3d6
- **EQMOD:** HOLY_M.Masterwork (Weapon).PLUS3W.STEEL
- **WIELD:** TwoHanded
- **SIZE:** L
- **QUALITY:** Bright Illumination|20 ft.
- **QUALITY:** Shadowy Illumination|40 ft.
- **SPROP:** Is sacred to Tyr.

### Ettin Axe of Uruth

- **PROFICIENCY:** WEAPON|Axe (Orc Double)
- **COST:** 60
- **WT:** 15
- **SLOTS:** 2
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **ALTCRITMULT:** x3
- **ALTCRITRANGE:** 1
- **DAMAGE:** 1d8
- **ALTDAMAGE:** 1d8
- **EQMOD:** ICE_BR_M.MAGIC_COST|28000.Masterwork (Weapon).PLUS1W.STEEL
- **ALTEQMOD:** FLM_BR_M.Masterwork (Weapon).PLUS1W.STEEL
- **WIELD:** TwoHanded
- **SIZE:** M
- **QUALITY:** Bright Illumination|20 ft.
- **QUALITY:** Shadowy Illumination|40 ft.
- **SPROP:** It is imbued with 2 sentiences, Ur and Krypt. UR is LE, Int 14, Wis 14, Cha 10, speaks Common Orc, and Troll, has 120-ft vision and hearing and an Ego of 9. Krypt is CE, Int 14, Wis 10, Cha 14, speaks Common, Orc, and Troll, has 120-ft vision and hearing, Ego of 9. The item has 10 ranks in bluff and intimidate.

### Gauntlets of Weaponry Arcane

- **PROFICIENCY:** WEAPON|Gauntlet
- **COST:** 2000
- **WT:** 4
- **SLOTS:** 2
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d3
- **WIELD:** Light
- **SIZE:** M
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=1|Magic Weapon
- **SPROP:** Affects a weapon only while it is in contact with the gauntlets.

### Gurt's Greataxe

- **PROFICIENCY:** WEAPON|Greataxe
- **COST:** 20
- **WT:** 24
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 3d6
- **EQMOD:** BANE_M|Humanoids (human).MAGIC_COST|4340.Masterwork (Weapon).PLUS1W.STEEL.THNDR_M
- **WIELD:** TwoHanded
- **SIZE:** L
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=8|Chill Metal
- **QUALITY:** Bright Illumination|20 ft.
- **QUALITY:** Shadowy Illumination|40 ft.
- **QUALITY:** Duration|below 0?F

### Lance of Burning Blackfire

- **PROFICIENCY:** WEAPON|Lance
- **COST:** 10
- **WT:** 10
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** CRRSV.DARK.FLM_M.MAGIC_COST|-250.Masterwork (Weapon).PLUS1W
- **WIELD:** TwoHanded
- **REACHMULT:** 2
- **SIZE:** M
- **SPROP:** Made of blackwood and inscribed with sacred rune of Mystra

### Magebane

- **PROFICIENCY:** WEAPON|Sword (Bastard)
- **COST:** 35
- **WT:** 6
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d10
- **EQMOD:** MAGIC_COST|94600.Masterwork (Weapon).PLUS2W.STEEL
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|WIELDCATEGORY|-1
- **SPROP:** Intelligent bastard sword made of black metal. Runew of green fire decorate it but do not shed light. It is intelligent AL NE; Int 17, Wis 10, Cha 17; Speech [Auran, Alzhedo, Common], telepathy, darkvision and hearomg 120 ft, Ego Score 16, Can Detect Magic at will, has 10 ranks in Knowledge (arcana) and spot. Has the dedicated power Feeblemind.

### Muiral's Decapitator

- **PROFICIENCY:** WEAPON|Greatsword
- **COST:** 100
- **WT:** 16
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 3d6
- **EQMOD:** ADAMANT_WEAP.MAGIC_COST|4000.Masterwork (Weapon).PLUS3W.VORPAL
- **WIELD:** TwoHanded
- **SIZE:** L
- **SPROP:** Magic items struck by this sword glow with a pale radiance for 1d4+1 rounds.

### Quarterstaff of Alcedor

- **PROFICIENCY:** WEAPON|Quarterstaff
- **ALTTYPE:** Weapon.Melee.Bludgeoning
- **COST:** 0
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **ALTCRITMULT:** x2
- **ALTCRITRANGE:** 1
- **DAMAGE:** 1d6
- **ALTDAMAGE:** 1d6
- **EQMOD:** Masterwork (Weapon).PLUS3W.Weapon ~ Spellstrike.WOOD
- **ALTEQMOD:** Masterwork (Weapon).PLUS3W.Weapon ~ Shattermantle.WOOD
- **WIELD:** TwoHanded
- **SIZE:** M

### Spiked Gauntlet of Ulbaerag

- **PROFICIENCY:** WEAPON|Gauntlet (Spiked)
- **COST:** 5
- **WT:** 1
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** Masterwork (Weapon).PLUS3W.STEEL.WOUND
- **WIELD:** Light
- **SIZE:** M
- **SPROP:** The gauntlet drips blood as long as a victime wounded by it continues to bleed.

### Viperfang

- **PROFICIENCY:** WEAPON|Dagger
- **COST:** 2
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d4
- **EQMOD:** CRRSV.MAGIC_COST|32000.Masterwork (Weapon).PLUS2W.STEEL
- **WIELD:** Light
- **RANGE:** 10
- **SIZE:** M
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=15|Poison,14
- **SPROP:** Adds +1 to the DC of a death attack.

### Ring of Heavy Armor

- **COST:** 72000
- **WT:** 0
- **EQMOD:** FRT_HVY
- **BONUS:** COMBAT|AC|1|TYPE=Deflection

### Ring of Light Armor

- **COST:** 8000
- **WT:** 0
- **EQMOD:** FRT_LGHT
- **BONUS:** COMBAT|AC|1|TYPE=Deflection

### Ring of Medium Armor

- **COST:** 32000
- **WT:** 0
- **EQMOD:** FRT_MOD
- **BONUS:** COMBAT|AC|1|TYPE=Deflection

### Ring of Research

- **COST:** 2500
- **WT:** 0
- **SPROP:** This ring doubles your circumstance bonus on Knowledge checks when using a library. If not specified, add +2 to the roll.

### Morgan's Staff

- **PROFICIENCY:** WEAPON|Quarterstaff
- **ALTTYPE:** Weapon.Melee.Bludgeoning
- **COST:** 0
- **WT:** 4
- **BASEITEM:** Staff
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **ALTCRITMULT:** x2
- **ALTCRITRANGE:** 1
- **DAMAGE:** 1d6
- **ALTDAMAGE:** 1d6
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50].Masterwork (Weapon).PLUS1W.THNDR_M.WOOD
- **ALTEQMOD:** PLUS1W.SHOCK_M
- **WIELD:** TwoHanded
- **SIZE:** M
- **SPROP:** Can cast Baleful Polymorph [1 charge], Chain Lightning [1 charge], or Thunderlance [1 charge]

### Staff (Banishment)

- **COST:** 47532
- **WT:** 1
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Can cast Banishment [2 charges], Dismissal [1 charge], Repulsion [2 charges], Slow [1 charge]

### Staff (Rejecting)

- **COST:** 12375
- **WT:** 1
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Can cast Trobriand's Baleful Teleport [2 charges]

### Amulet of Alcedor

- **COST:** 318500
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=13|Hold Person,14
- **SPROP:** Victims that fail the will save are also automatically affected by vampiric touch.

### Amulet of Fire Breath

- **COST:** 10800
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=3|CASTERLEVEL=5|Palarandusk's Fire Breath

### Amulet of the Watch

- **COST:** 2160
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=3|Whispering Wind

### Belabrantan Caparison of Warmth

- **COST:** 3000
- **WT:** 5
- **SPROP:** This robe for a griffen keeps both a steed and its rider comfortable as though they had an endure elements spell cast upon them. This item uses the robe slot on a griffon.

### Bit and Bridle of Griffonriding

- **COST:** 5000
- **WT:** 2
- **BONUS:** SKILL|Ride|10|TYPE=Circumstance
- **SPROP:** This item uses the amulet slot on a griffon.

### Griffon Badge of Waterdeep

- **COST:** 4000
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Feather Fall
- **SPROP:** The spell can be activated as an immediate action.

### Griffon Lancesaddle

- **COST:** 1860
- **WT:** 40
- **SPROP:** This exotic military saddle for for griffons has 6 small cylinders with enough space for a heavy lance each. It uses the cape slot on a griffon.

### Laeral's Anklets

- **COST:** 135000
- **WT:** 0
- **SLOTS:** 2
- **ABILITY:** Special Ability|VIRTUAL|Resistance To Acid (Sp)
- **SPELLS:** Magic Item|TIMES=2|CASTERLEVEL=9|Passwall
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **BONUS:** VAR|AcidResistanceBonusSp|5|TYPE=Base
- **SPROP:** The anklets have the everbright property and are immune to acid and rusting.

### Laeral's Robes

- **CONTAINS:** *120
- **COST:** 160500
- **WT:** 1
- **ABILITY:** Special Ability|AUTOMATIC|Retain Dex To AC ~ Flat-footed
- **BONUS:** SAVE|Fortitude,Reflex,Will|5|TYPE=Resistance
- **BONUS:** SKILL|Search,Spot|10|TYPE=Competence
- **BONUS:** VAR|SeeEtheralRange|120|TYPE=Base|
- **BONUS:** VAR|SeeInvisibilityRange|120|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|120|TYPE=Base
- **SPROP:** Can't avert eyes from Gaze Attack

### Lords' Amulet

- **COST:** 35000
- **WT:** 0
- **SPROP:** Functions as both a port key for Waterdeep portals and an amulet of proof against detection and location

### Lords' Helm

- **COST:** 8750
- **WT:** 0
- **SPROP:** Acts as a ring of mind shielding.

### Lords' Ring

- **COST:** 92250
- **WT:** 0
- **SLOTS:** 1
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=9|Sending|Teleport
- **SPROP:** Functions as a periapt of proof against poison.

### Lords' Robe

- **COST:** 3000
- **WT:** 1
- **SPROP:** The wearer is affected by a disguise self spell to appear 6 ft tall and of indeterminate gender.

### Mask of Lhestyn

- **COST:** 14700
- **WT:** 0
- **SPROP:** Functions as both a hat of disguise and a medallion of thoughts

### Spell-Lens

- **COST:** 13500
- **WT:** 0
- **SPROP:** When attached to a wand, it drains 3 charges per casting but the spell is Empowered and Enlarged.

### Slippers of Shadowwalking

- **COST:** 23760
- **WT:** 0.5
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Shadow Walk
- **SPROP:** Is a shadow weave item.

### Stamp of the Messenger (Silver)

- **COST:** 1000
- **WT:** 1
- **SPROP:** Produces its own sealing wax.

### Stamp of the Messenger (Gold)

- **COST:** 2750
- **WT:** 1
- **SPROP:** Stamps made with this can become animated (Flying Wax Seal).

### Teukiir Badge

- **COST:** 12000
- **WT:** 0
- **SPROP:** 1/day this badge allows the bearer to transport himself to the Silver Safehold.

### Poison (Sleep Smoke)

- **COST:** 25
- **WT:** 0
- **SPROP:** Airborn, smoke-based globe. 10ft dia in round 1, 20 ft in round 2. Inhaled DC 15, Init: Unconscious for 1 minute, Sec: Unconscious for 1d3 minutes

## Feats

### Dungeoneer's Intuition

- **PREABILITY:** 1,CATEGORY=Special Ability,Trap Sense
- **PRESTAT:** 1,WIS=13
- **BONUS:** VAR|TrapSenseBonus|WIS

Add Wisdom bonus to trap sense, add trap sense bonuses to AC during surprise round.

You add your Wisdom bonus to your trap sense bonus. In addition, you can apply your trap sense bonus to your AC during a surprise round.

### Hand of Tyr

- **PREABILITY:** 1,CATEGORY=Special Ability,Turn Undead
- **PREALIGN:** LG
- **PREDEITY:** 1,Tyr
- **BONUS:** SAVE|Will|1|TYPE=Sacred
- **BONUS:** COMBAT|BASEAB,DAMAGE.Melee|1|TYPE=Sacred

+1 sacred bonus on attack rolls, damage rolls, and Will saves.

As long as your refreain from using your right hand, you receive a +1 sacred bonus on attack rolls, damage rolls, and Will saves.

### Jester's Magic (Bardic)

- **PRESKILL:** 1,Perform (Acting)=8,Perform (Comedy)=8
- **PRESPELLCAST:** TYPE=Arcane
- **BONUS:** CASTERLEVEL|SPELL.Prestidigitation|1
- **BONUS:** CASTERLEVEL|SPELL.Remove Fear|1
- **BONUS:** CASTERLEVEL|SPELL.Hypnotism|1
- **BONUS:** CASTERLEVEL|SPELL.Hideous Laughter|1
- **BONUS:** CASTERLEVEL|SPELL.Calm Emotions|1
- **BONUS:** CASTERLEVEL|SPELL.Enthrall|1
- **BONUS:** CASTERLEVEL|SPELL.Confusion|1
- **BONUS:** CASTERLEVEL|SPELL.Glibness|1
- **BONUS:** CASTERLEVEL|SPELL.Modify Memory|1
- **BONUS:** CASTERLEVEL|SPELL.Suggestion (Mass)|1
- **BONUS:** CASTERLEVEL|SPELL.Irresistible Dance|1

+1 caster level for jester's magic.

When casting bardic jester magic, you enjoy a +1 caster level. These spells are 0-prestidigitation; 1-remove fear, hideous laughter, hypnotism; 2-calm emotions, enthrall; 3-confusion, glibness; 4-modify memory; 5-mass suggestion; 6-irresistible dance

### Jester's Magic (Mage)

- **PRESKILL:** 1,Perform (Acting)=8,Perform (Comedy)=8
- **PRESPELLCAST:** TYPE=Arcane
- **BONUS:** CASTERLEVEL|SPELL.Prestidigitation|1
- **BONUS:** CASTERLEVEL|SPELL.Grease|1
- **BONUS:** CASTERLEVEL|SPELL.Hypnotism|1
- **BONUS:** CASTERLEVEL|SPELL.Hideous Laughter|1
- **BONUS:** CASTERLEVEL|SPELL.Rope Trick|1
- **BONUS:** CASTERLEVEL|SPELL.Deep Slumber|1
- **BONUS:** CASTERLEVEL|SPELL.Suggestion|1
- **BONUS:** CASTERLEVEL|SPELL.Confusion|1
- **BONUS:** CASTERLEVEL|SPELL.Seeming|1
- **BONUS:** CASTERLEVEL|SPELL.Suggestion (Mass)|1
- **BONUS:** CASTERLEVEL|SPELL.Project Image|1
- **BONUS:** CASTERLEVEL|SPELL.Irresistible Dance|1
- **BONUS:** CASTERLEVEL|SPELL.Weird|1

+1 caster level for jester's magic.

When casting mage jester magic, you enjoy a +1 caster level. These spells are 0-prestidigitation; 1-grease, hypnotism; 2-hideous laughter, rope trick; 3-deep slumber, suggestion; 4-confusion; 5-seeming; 6-mass suggestion; 7-project image; 8-irresistible dance; 9-weird

### Lunar Magic

- **PREDEITY:** 1,Selune,Mystra
- **PRESPELLCAST:** TYPE=Arcane,TYPE=Divine

Caster level varies with the phase of the moon.

Your caster level varies by Selune's position in the sky. On the 15, 16, and 17th of each month, as Selune is in her New Phase, your are -1 to your caster level. On the 30, 1, and 2nd of each month you are +1 to your caster level.

### Veil of Cyric

- **PREALIGN:** LE,NE,CE
- **PREDEITYALIGN:** LG,NG,CG,LN,TN,CN

Not detected as evil unless the detector's aura strength exceeds yours.

You do not register as evil to the detect evil spell or spell-like ability, unless the caster's aura power exceeds your own.

### Initiate of Shar

- **PRECLASS:** 1,Blackguard=1,Cleric=3
- **PREDEITY:** 1,Shar
- **CSKILL:** Bluff|Hide
- **SPELLKNOWN:** CLASS|Cleric=1|Disguise Self
- **SPELLKNOWN:** CLASS|Blackguard=1|Disguise Self
- **SPELLKNOWN:** CLASS|Cleric=3|Crushing Despair
- **SPELLKNOWN:** CLASS|Blackguard=3|Crushing Despair
- **SPELLKNOWN:** CLASS|Cleric=4|Armor of Darkness
- **SPELLKNOWN:** CLASS|Blackguard=4|Armor of Darkness
- **SPELLKNOWN:** CLASS|Cleric=5|Darkbolt

Bluff and Hide are class skills, add Sharite spells to your list.

You add Bluff and Hide to your Class Skill List. You add 4 or 5 spells to your list.

## Spells

### Binding Chain of Fate

- **CLASSES:** Sorcerer,Wizard=9
- **SCHOOL:** Evocation
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** Whirling chain of force
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

Chain encircles target

### Ensul's Soultheft

- **CLASSES:** Sorcerer,Wizard=9
- **SCHOOL:** Necromancy
- **DESCRIPTOR:** Evil
- **COMPS:** V,S,M
- **CASTTIME:** 1 full round
- **RANGE:** Touch
- **TARGETAREA:** Living, corporeal creature touched
- **DURATION:** (CASTERLEVEL) rounds (D); see text
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

Evil

### Halaster's Blacksphere

- **CLASSES:** Sorcerer,Wizard=8
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** 10-ft.-radius burst and globe
- **DURATION:** 2d4 rounds + (CASTERLEVEL) rounds
- **SAVEINFO:** Reflex half; see text
- **SPELLRES:** Yes

See text

### Halaster's Fetch I

- **CLASSES:** Sorcerer,Wizard=4
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Calling
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Fetch II

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Calling
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Fetch III

- **CLASSES:** Sorcerer,Wizard=6
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Calling
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Fetch IV

- **CLASSES:** Sorcerer,Wizard=7
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Calling
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Fetch V

- **CLASSES:** Sorcerer,Wizard=8
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Calling
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Fetch VI

- **CLASSES:** Sorcerer,Wizard=9
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Calling
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Image Swap

- **CLASSES:** Bard,Sorcerer,Wizard=4
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Teleportation
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** You and touched objects weighing up to 50 lb./level
- **DURATION:** Instantaneous
- **SAVEINFO:** None and Will negates (object)
- **SPELLRES:** No and Yes (object)

See Text

### Halaster's Light Step

- **CLASSES:** Bard,Sorcerer,Wizard=2
- **SCHOOL:** Transmutation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Shaking Hand

- **CLASSES:** Sorcerer,Wizard=6
- **SCHOOL:** Evocation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Halaster's Teleport Cage

- **CLASSES:** Sorcerer,Wizard=9
- **SCHOOL:** Abjuration
- **COMPS:** V,S,M
- **CASTTIME:** 10 minutes
- **RANGE:** Close
- **TARGETAREA:** One 10-ft. cube per level
- **DURATION:** Permanent
- **SAVEINFO:** None
- **SPELLRES:** No

See Text

### Jhanifer's Deliquence

- **CLASSES:** Sorcerer,Wizard=4
- **SCHOOL:** Transmutation
- **DESCRIPTOR:** Cold|Water
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

As transmute rock to mud; see text

### Jumpgout

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Fire
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** 5-ft.-radius pillar of flame, up to 30 ft. tall
- **DURATION:** 2 rounds
- **SAVEINFO:** Reflex half; see text
- **SPELLRES:** Yes

See Text

### Khelben's Dweomerdoom

- **CLASSES:** Sorcerer,Wizard=9
- **SCHOOL:** Abjuration
- **COMPS:** V,S,F
- **CASTTIME:** 1 swift action
- **RANGE:** Close
- **TARGETAREA:** 1 creature
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No

See text

### Laeral's Crowning Touch

- **CLASSES:** Cleric,Sorcerer,Wizard=9
- **SCHOOL:** Necromancy
- **COMPS:** V,S,F,XP
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** One spellcaster
- **DURATION:** 1 year and 1 day
- **SAVEINFO:** Will negates; see text
- **SPELLRES:** Yes

Requires Text.

### Laeral's Silver Lance

- **CLASSES:** Sorcerer,Wizard=3
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force
- **COMPS:** V,S,F
- **CASTTIME:** 1 standard action
- **RANGE:** Long
- **TARGETAREA:** None
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude partial; see text
- **SPELLRES:** Yes

Requires Text.

### Palarandusk's Fire Breath

- **CLASSES:** Sorcerer,Wizard=2
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Fire
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** One hour or until discharged
- **SAVEINFO:** Reflex half
- **SPELLRES:** Yes

Requires Text.

### Steelsting

- **CLASSES:** Sorcerer,Wizard=4
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force
- **COMPS:** V
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Trobriand's Baleful Teleport

- **CLASSES:** Sorcerer,Wizard=6
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Teleportation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]

Requires Text.

### Trobriand's Crytalbrittle

- **CLASSES:** Bard,Sorcerer,Wizard=3
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** One nonmagical object up to 1 cu. ft. per level
- **DURATION:** Permanent
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes

Requires Text.

### Trobriand's Glassee

- **CLASSES:** Sorcerer,Wizard=6
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** One nonmagical stone or metal object up to 1 cu. ft. per level
- **DURATION:** Permanent
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes

This spell gives the target object the transparency of glass.


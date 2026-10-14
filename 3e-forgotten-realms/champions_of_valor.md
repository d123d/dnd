# Champions of Valor

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Special Abilities

### Initiate of Anhur


### Initiate of Arvoreen


### Initiate of Baravar Cloakshadow


### Initiate of Eilistraee


### Initiate of Holy Realm


### Initiate of Horus-Re


### Initiate of Milil


### Initiate of Nobanion


### Initiate of Tymora


### Unarmed Damage

- **TEMPBONUS:** PC|UDAM|CLASS.Monk|2
- **TEMPBONUS:** PC|VAR|CarmendineMonkBonus|1

### AC Bonus

- **TEMPBONUS:** PC|VAR|MonkACLVL|2
- **TEMPBONUS:** PC|VAR|CarmendineMonkBonus|1

### Speed Bonus

- **TEMPBONUS:** PC|VAR|MonkMoveLVL|2
- **TEMPBONUS:** PC|VAR|CarmendineMonkBonus|1

### Everbright Blessing

- **ABILITY:** Special Ability|AUTOMATIC|Resistance To Acid
- **BONUS:** VAR|AcidResistanceBonus|5

Your armor, shield, and primary weapon are treated as though they have the everbright ability, shining like polished silver and are immune to acid and rust attacks. The armor provides you with Resistance to Acid 5. This ability is removed if you drop the items or hand them to someone else. This replaces the Divine Health Class Feature

### Valiant Rescue


Up to %1 times per day you can charge into melee with a creature that threatens an ally and still make a full attack with a single weapon. During this charge you benefit from the Mobility feat. If mounted that extends to your mount as well. This ability replaces the Turn Undead class feature.|(3+CHA)

### Binding Oath


You can magically link 2 willing individuals with an oath. You know and the other party know immediately if the 3rd party violates the oath. Additionally the violating party is fatigued for %1 days from the violation. You may perform this ability %2 times per week. This ability replaces the Remove Disease class feature.|PaldinLVL|(PaldinLVL-3)/3

### Touch of Fatigue

- **SPELLS:** Class|TIMES=ATWILL|CASTERLEVEL=PaldinLVL|Touch of Fatigue,10+CHA

You can use the touch of fatigue ability at will against those who stray from their promises or to punish those guilty of minor infractions.

### Lay on Hands

- **DEFINE:** LayOnHands|0
- **DEFINE:** LayOnHandsLVL|0
- **BONUS:** VAR|LayOnHands|LayOnHandsLVL*max(CHA,1)

You gain the ability to heal wounds with your touch like the Paladin class feature. You can heal %1 hp/day. This replaces the standard Monk class feature, Still Mind.|LayOnHands

If you have a Charisma score of 12 or higher can heal wounds (her own or those of others) by touch. Each day she can heal a total number of hit points of damage equal to her monk level x her Charisma bonus, if your charisma is 11 or lower you may only heal your level in hps per day. A monk may choose to divide her healing among multiple recipients, and she doesn't have to use it all at once. Using lay on hands is a standard action. Alternatively, a monk can use any or all of this healing power to deal damage to undead creatures. Using lay on hands in this way requires a successful melee touch attack and doesn't provoke an attack of opportunity. The monk decides how many of her daily allotment of points to use as damage after successfully touching an undead creature.

### Tenacious Tracker

- **ABILITY:** FEAT|VIRTUAL|Track

You can follow the trail of those cruel enough to torture and maim others. You receive track as a bonus feat and gain a +10 competence bonus on your Survival check against followers of Loviatar. Furthermore, if you touch someone who has been tortured by a follower of Loviatar in the previous hour our receive a clear mental image of that person's true appearance. This replaces the Monk's standard bonus feat at 6th level.

### Locate Creature

- **DEFINE:** LocateCreatureLVL|0
- **SPELLS:** Class|TIMES=1|CASTERLEVEL=LocateCreatureLVL|Locate Creature

You can use Locate Creature once per day, but only to find a creature that has Loviatar as their patron deity.

### Bird of Prey


%1 times per day you can take on the aspects of a hawk. Your hands turn into claws that deal 1d4 damage +%2 against evil creatures. These attacks are considered magic, good-aligned weapons for purposes of overcoming damage reduction. The transformation lasts for %3 rounds. This replaces the standard paladin ability to Smite Evil.|(PaladinLVL/5+1)|(PaladinLVL/2)|(CHA+3)

### Smite Minions of Set

- **DEFINE:** PaladinSmiteSetLVL|0

You gain the Smite Evil class feature but it is only useable against minions of Set. %1 times per day you can hit for an extra %2 points of damage. This replaces the standard paladin ability to remove disease.|(PaladinSmiteSetLVL-6)/3+1|PaladinSmiteSetLVL

### Horus-Re's Glory


Your armor shines brightly (as the daylight spell). This illumination can be suppressed or resumed at will with a standard action. This replaces the 3rd level spell slot granted at 12th level.

### Favored Enemy


You gain lycanthropes as a favored enemy like the ranger class feature. This fixed +2 bonus applies against all lycanthropes on Bluff, Listen, Sense Motive, Spot, Survival checks against the creatures as well as weapon damage rolls and replaces the standard paladin class feature, Turn Undead.

### Cure Lycanthropy


You can use your normal paladin Remove Disease ability to cure lycanthropy within 3 days a the attack as though a 12th-lvl cleric cast a break enchantment spell on the night of a full moon.

### Battlesong


Once per day you can inspire courage as per the bard ability by singing a battle song. Your level for this is %1. You do not need any ranks in perform to use this ability. This replaces your 2nd-level spell at 10th level.|(PaladinLVL-4)

### Dancing Feint


You can use your Perform (Dance) skill to feint in combat as if it were the Bluff skill.

### Combat Dancing


If you have at least 5 ranks in Perform (Dance), you gain a +2 dodge bonus against attacks of opportunity. If you use Spring Attack, you get a +2 bonus to hit on your attack roll in that maneuver.

### Bonus Spells 1


When you take your first level in Dukar, you must choose your order (based on coral color). Jhimar (Red Coral) - Enchantment &amp; Evocation spells. Kupav (Blue Coral) - Abjuration &amp; Transmutation Spells. Maalirn (Green Coral) - Conjuration &amp; Divination Spells. Numos (White Coral) - Illusion &amp; Necromancy Spells. Similar to choosing to be a specialist caster, once you make this choice you cannot switch it. Your 2 bonus spells added to your spell book must come from the schools of your specialty.

### Bonus Spells 2


When you take your first level in Dukar, you must choose your order (based on coral color). Jhimar (Red Coral) - Enchantment &amp; Evocation spells. Kupav (Blue Coral) - Abjuration &amp; Transmutation Spells. Maalirn (Green Coral) - Conjuration &amp; Divination Spells. Numos (White Coral) - Illusion &amp; Necromancy Spells. Similar to choosing to be a specialist caster, once you make this choice you cannot switch it. Your 2 bonus spells added to your spell book must come from the schools of your specialty.

### Bonus Spells 3


When you take your first level in Dukar, you must choose your order (based on coral color). Jhimar (Red Coral) - Enchantment &amp; Evocation spells. Kupav (Blue Coral) - Abjuration &amp; Transmutation Spells. Maalirn (Green Coral) - Conjuration &amp; Divination Spells. Numos (White Coral) - Illusion &amp; Necromancy Spells. Similar to choosing to be a specialist caster, once you make this choice you cannot switch it. Your 2 bonus spells added to your spell book must come from the schools of your specialty.

### Coral Claw

- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Piercing.Slashing,1,1d4

You can extend the coral under your skin to form a sharp spike giving you a 1d4 point claw attack. Extending or Retracting this claw is a swift action. This replaces the normal wizard bonus feat at 5th level.

### Coral Power


At 10th and 15th level you get to choose a power up from the Coral Power Pool. If you take an ability twice, it boosts the affect.

### Acid


You add 1d4 points of acid damage to your claw attacks. This acid cannot be stored for later use. The acid will not harm you or your gear. You can suspend and resume its release as a free action.|!PREABILITY:1,CATEGORY=Special Ability,Coral Power ~ Acid 2

### Acid 2

- **PREABILITY:** 1,CATEGORY=Special Ability,Coral Power ~ Acid

You add 1d8 points of acid damage to your claw attacks. This acid cannot be stored for later use. The acid will not harm you or your gear. You can suspend and resume its release as a free action.

### Armor


3 times per day as a standard action, you can make your coral extend hard growths across your skin giving you a +1 enhancement to your natural armor. This lasts for 10 minutes after which it crumbles to dust.|!PREABILITY:1,CATEGORY=Special Ability,Coral Power ~ Armor 2

### Armor 2

- **PREABILITY:** 1,CATEGORY=Special Ability,Coral Power ~ Armor

3 times per day as a standard action, you can make your coral extend hard growths across your skin giving you a +2 enhancement to your natural armor. This lasts for 10 minutes after which it crumbles to dust.

### Color Spray

- **DEFINE:** CoralPowerColorSprayDC|0
- **BONUS:** VAR|CoralPowerColorSprayDC|11+INT
- **SPELLS:** Class|TIMES=ATWILL|CASTERLEVEL=classlevel("Wizard")|Color Spray,CoralPowerColorSprayDC

Your coral can glow in intensely confusing patterns. At will as a standard action, you can use this light to create a color spray effect. You must have one hand free and uncovered to do so.

### Color Spray 2

- **PREABILITY:** 1,CATEGORY=Special Ability,Coral Power ~ Color Spray
- **BONUS:** VAR|CoralPowerColorSprayDC|2

Taking this power a 2nd time adds 2 to your DC.

### Wound Transfer


Your coral allows you to transfer life energy by touching another creature. You can heal an ally by sacrificing some of your own health. This allows your to transfer 1d6 of your hp to an ally. If it would boost him over his normal total they are considered temporary hps and will last 1 hour. You cannot boost an ally more than +10 over his normal maximum.|!PREABILITY:1,CATEGORY=Special Ability,Coral Power ~ Wound Transfer 2

### Wound Transfer 2

- **PREABILITY:** 1,CATEGORY=Special Ability,Coral Power ~ Wound Transfer

Your coral allows you to transfer life energy by touching another creature. You can heal an ally by sacrificing some of your own health. This allows your to transfer 2d6 of your hp to an ally. If it would boost him over his normal total they are considered temporary hps and will last 1 hour. You cannot boost an ally more than +10 over his normal maximum.

### Corpse Strike


%1 times per day, as a swift action, you can surround your weapon with a visible gray aura of holy power that sheds light equal to a candle. Any weapon so affected can ignore any damage reduction other then DR/Epic possessed by an undead creature, regardless of its source. This aura lasts for %2 minutes. This ability replaces the normal paladin ability to Smite Evil.|PaladinLVL/5+1|PaladinLVL

### Undead Knowledge

- **DEFINE:** UndeadKnowledge|0

You get a +%1 competence bonus on Knowledge (religion) checks concerning the undead.|UndeadKnowledge

### Eternal Vigor


You can ignore the effects of negative levels bestowed upon you by undead. This replaces the normal paladin divine health class feature.

### Greater Turning


You can perform a greater turning %1 times per day, just as if you had the Sun domain feature. Any creature that you would normally turn is instead destroyed. This replaces the normal remove disease feature.|(PaladinLVL-6)/3+1

### Fast Charge


You gain a +%1 ft enhancement bonus to your movement when you charge. This replaces the barbarian Trap Sense class feature.|(BarbarianLVL/3*10)

### Awesome Charge


While enraged, you can make an attack at the end of the charge as though you had the Awesome Blow feat. This replaces the normal barbarian uncanny dodge class feature.

### Raging Vigor


As a standard action, you can expend a rage use to heal yourself damage equal to twice your hit dice. You may use this even during another rage. This replaces the barbarian's normal damage reduction gained at 7th level.

### Spontaneous Curing


You can spontaneously convert prepared druid spells of 1st level or higher into cure light wounds spells, just as a cleric can. This does not extend to higher level level cure spells. This replaces the Resist Nature's Lure class ability.

### Wild Shape


You can use a wild shape use (or include as part of another shift) to gain humanoid hands. For instance a unicorn fangshield druid could take the form of a wolf with humanoid hands. Doing so eliminates any claw related natural attacks associated with the new form.

### Wild Shape (Humanoid)


You can use your wild shape ability to assume a Medium humanoid form. You can resemble a human, dwarf, elf, or other medium humanoid as you desire. This locks out 1 use/day of your wild shape.

### Combat Style

- **ABILITY:** Special Ability|AUTOMATIC|Fangshield Ranger ~ Combat Tree

Often lacking hands, Fangshield rangers have a third option for their combat style: natural attacks. If you select this style you get Multiattack or improved Natural Attack as a bonus feat at 2nd level. At 6th level you get Weapon Focus in your choice of natural weapons, At 11th level you get Weapon Focus in a second natural weapon or Greater Weapon Focus in your first.

### Combat Tree

- **DEFINE:** RangerCombatTreeLVL|0
- **DEFINE:** RangerCombatTree|0
- **BONUS:** ABILITYPOOL|Ranger Combat Style|1
- **BONUS:** VAR|RangerCombatTree|1
- **BONUS:** VAR|RangerCombatTree|1
- **BONUS:** VAR|RangerCombatTree|1

### Animal Companion


Being beastlike yourself, you form a tighter bond to your animal companion and add 2 to your effective druid level.

### Lion and the Unicorn

- **BONUS:** ABILITYPOOL|Lion and the Unicorn Bonus|1

You must choose an affinity for Nobanion or Lurue. Regardless of your current patron deity this does not form a religious conflict. The bonus you get will replace your 2nd favored enemy.

### Natural Fighting

- **!PREABILITY:** 1,CATEGORY=Special Ability,TYPE=RangerCombatStyle
- **PRECLASS:** 1,Fangshield Ranger=1

### Combat Style Multiattack

- **ABILITY:** FEAT|VIRTUAL|Multiattack
- **BONUS:** ABILITYPOOL|Fangshield Ranger Weapon Focus|1

### Combat Style Improved Natural Attack

- **CHOOSE:** WEAPONPROFICIENCY|PC,TYPE=Natural
- **MULT:** YES
- **ABILITY:** FEAT|VIRTUAL|Improved Natural Attack (%CHOICE)
- **ABILITY:** FEAT|VIRTUAL|Weapon Focus (%CHOICE)
- **ABILITY:** FEAT|VIRTUAL|Greater Weapon Focus (%CHOICE)

### Multiattack

- **ABILITY:** FEAT|VIRTUAL|Multiattack

### Improved Natural Attack

- **MULT:** YES
- **CHOOSE:** WEAPONPROFICIENCY|PC,TYPE=Natural
- **ABILITY:** FEAT|VIRTUAL|Improved Natural Attack (%LIST)

### Natural Weapon Focus

- **MULT:** YES
- **CHOOSE:** WEAPONPROFICIENCY|PC,TYPE=Natural
- **ABILITY:** FEAT|VIRTUAL|Weapon Focus (%LIST)

### Second Natural Weapon Focus

- **MULT:** YES
- **CHOOSE:** WEAPONPROFICIENCY|PC,TYPE=Natural
- **ABILITY:** FEAT|VIRTUAL|Weapon Focus (%LIST)

### Greater Natural Weapon Focus

- **PREABILITY:** 1,CATEGORY=FEAT,Weapon Focus (TYPE=Natural)
- **MULT:** YES
- **CHOOSE:** WEAPONPROFICIENCY|PC,TYPE=Natural
- **ABILITY:** FEAT|VIRTUAL|Greater Weapon Focus (%LIST)

### Lurue Dedicated


You get a +1 sacred bonus to AC during the night.

### Nobanion Dedicated


You get a +1 sacred bonus to AC during the day.

### Defend the Weak


You can protect nearby allies in combat. If you use Combat Expertise, Fight Defensively, or the Total Defense action, you can grant the dodge bonus to AC from these actions to any adjacent creature in addition to yourself. This replaces the aura of courage class feature.

### Shield Other

- **SPELLS:** Class|TIMES=(max(1,CHA))|CASTERLEVEL=PaladinLVL|Shield Other

You can use shield other as a spell like ability by touching the target. This replaces the Turn Undead class feature.

### Expanded Healing


You treat your paladin level as 3 levels higher for purposes of determining your healing capabilities. This replaces the additional use of Smite Evil that you would have gained at 10th level.

### Detect Magic

- **SPELLS:** Class|TIMES=ATWILL|CASTERLEVEL=PaladinLVL|Detect Magic

You can use detect magic at will. This replaces a paladin's normal detect evil ability.

### Enemy of Strife


Golden Lions automatically ignore miss chances from concealment and overcome damage reduction as though they are fighting with good-aligned weapon against Zhentarim and the churches of Bane and Cyric. This replaces the paladin's normal Turn Undead ability.

### Restore the Weave


%1 times per day, the Golden Lion can repair a 5-foot cube of dead magic or wild magic area adjacent to them if they are in a normal area.|(PaladinLVL-6)/3+1

### Censure Devil


You can utter a word censure a devil within 30 ft of you. The devil gets a Will save (DC %1) or be dazed for 1 round. This ability can be used %2 times per day.|(10+PaladinLVL/2+CHA)|(3+CHA)

### Zone of Truth

- **SPELLS:** Class|TIMES=((PaladinLVL-6)/3+1)|TIMEUNIT=Week|CASTERLEVEL=PaladinLVL|Zone of Truth

You can use Zone of Truth %1 times per week. This ability replaces the paladin's Remove Disease ability.|(PaladinLVL-6)/3+1

### Firemane Aura


Once per day, you can create an aura of holy flame around your body. As this activates, you hair (or mane) momentarily turns into brilliant golden flame. Any evil creature striking you with in melee takes %1 damage, half of which is holy rather then damage. The effect lasts for a minute and replaces the normal paladin's aura of courage class feature.|PaladinLVL

### Wild Fighting


As a free action, you can enter a state of wild fighting for 1 round. During that round you make one extra melee attack but all are at -2. You must make a full attack to benefit from this ability. You can use it %1 times per day. This class ability replaces Turn Undead.|(CHA+3)

### Flying Lion


Once per day as a full-round action, you can grow eagle's wings. These will remain for up to %1 minutes though you can dismiss them as a free action. You can fly at your normal land speed with poor maneuverability with these wings. If you are not a lionine creature, you also gain catlike eyes, a thick mane of hair, and larger teeth. This replaces the standard paladin ability of Special Mount.|(PaladinLVL*10)

### Imp Spellcasting

- **BONUS:** CASTERLEVEL|Paladin|2

In addition to getting a bonus spell at each level, when casting paladin spells, you treat your caster level as 2 higher then normal. If you have arcane caster levels, you can add them to your paladin level as well.

### Smite Evil


In addition to your normal smite evil effect, if you hit a creature that is a spell caster, if finds it temporarily difficult to cast spells or use spell completion or spell trigger items. For 1 round, it must make a Concentration check (DC %1 + Spell Level) or lose the spell.|(10+PaladinLVL+CHA)

### Spellshatter


%1 times per day, you can choose to deliver a targeted greater dispel magic effect with a melee attack. You must decide to do this before you make the attack. If the attack hits, the greater dispel magic effect with your paladin level (plus any arcane caster levels that you have).|((PaladinLVL/5)+1)

### Sunder the Sadistic


You have the ability to reduce to rubble objects and structures dedicated to evil. Whenever you attack an object owned by a character who has Loviatar as a patron deity, or an object that is part of a temple or other structure dedicated to Loviatar, you can ignore the object's hardness. You can also use your smite evil against these objects as though they were creatuers. This replaces the Turn Undead class feature.

### Delay Poison


As your enemies frequently employ poison, you can use delay poison %1 times per week. This replaces the remove disease class feature.|((PaladinLVL/5)+1)

### Purifying Flame


You can transform your ki into purifying fire. Once per round, and %1 times per day, you can add 1d6 points of fire damage to your unarmed strike. This replaces the monk bonus feat at level 1.|(MonkLVL)

### Resistance to Fire

- **ABILITY:** Special Ability|AUTOMATIC|Resistance To Fire
- **BONUS:** VAR|FireResistanceBonus|5

You develop Resistance to Fire 5. This replaces the monk class feature, Still Mind.

### Fire Stride

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=MonkLVL|Fire Stride

You can use Fire Stride once per day. This replaces the Abundant Step class feature.

### Spontaneous Faith Healing


You can spontaneously convert a prepared spell of 1st level or higher into a faith healing spell. This ability replaces 1 2nd level spell slot.

### Imbue with Spell Ability

- **SPELLS:** Class|TIMES=(ClericLVL/2)|CASTERLEVEL=ClericLVL|Imbue with Spell Ability

You can use Imbue with Spell Ability %1 times per day to give a creature a single level 0 or level 1 spell that you have prepared. This ability replaces 1 3rd level spell slot.|(ClericLVL/2)

### Turn Invader


When standing in your homeland, you can use your turn undead to frighten (not destroy) monsters or enemies of the Holy Realm.

### Brilliant Strategy


You can draw upon her instinct for battle as an immediate action granting you an insight bonus on your AC of %1 for 1 round. You can use this ability %2 times per day. This ability replaces the Divine Grace class feature.|CHA|(PaladinLVL/2)

### Military Knowledge

- **DEFINE:** MilitaryKnowledge|0

You have a bonus of +%1 on Knowledge checks concerning military history or strategy.|MilitaryKnowledge

### Turn Undead


You are not as skilled at turning undead as a normal paladin. You can only use the ability a number times per day equal to your Charisma modifier.

### Spells

- **SPELLKNOWN:** CLASS|Paladin=1|Deathwatch
- **SPELLKNOWN:** CLASS|Paladin=2|Augury,Status

You add augury (2nd level), deathwatch (1st level), and status (2nd level) to your paladin spell list.

### Spontaneous Extend


Once per day you can cast a spell as if you prepared it with the Extend Spell feat without shifting the level or the casting time. This ability replaces your 1st level spell slot gained at 6th level.

### Trained Militia


All of your cohorts and followers are treated as though they have Martial Weapon Proficiency in the weapon of your choice. You can choose a different weapon for each follower.

### Enduring Personality


You are immune to any effect that would deal Charisma damage or Charisma drain. This replaces the Divine Health class feature.

### Heroism

- **SPELLS:** Class|TIMES=((PaladinLVL/5)+1)|TIMEUNIT=Week|CASTERLEVEL=PaladinLVL|Heroism

You can use Heroism %1 times per week. You can't use this ability on yourself, only on another creature. It replaces the Remove Disease ability.|((PaladinLVL/5)+1)

### Heroic Rapture


Once per day, you can spend a full-round action to embrace another creature and grant them bravery. They get a +4 morale bonus on attack rolls, saves, and skill checks, immunity to fear, and %1 temporary hitpoints. These effects last for a minute. This replaces your 3rd level spell slot gained at 12th level.|PaladinLVL

### Walk in Silence


You can move with amazing silence, receiving a +5 circumstance bonus on Move Silently for 1 round. You activate this ability as a swift action and can use is %1 times per day. This only functions if you are wearing light or no armor and carrying a light load.|(RangerLVL/2)

### Bane Weapon

- **BONUS:** VAR|RangerCombatTree|-1

You can temporarily turn any weapon you wield into a bane weapon. This takes a full-round action at which point you choose the type (and subtype if applicable). It must be one of your favored enemies. The effect lasts for %1 round. and can be used %2 times per day. The effect ends if you drop the weapon. This replaces the 2nd tier combat style normally gained at 6th level.|(RangerLVL/2)|(max(0,WIS)+1)

### Portal Analysis


You automatically sense portals within 10 ft and can thereafter study it as if using the analyze portal spell. If you can activate the portal, you can use portal well when you enter it (1/day). This ability replaces the swift tracker class feature.

### Weavespeak


Once per day you can send up to a 25 word message to nearest cleric, paladin, or ranger of Mystra (not your choice) as per the sending spell. This replaces the Endurance feat.

### Bonus Spells


You gain 1 bonus spell at each ranger spell level. This replaces your Animal Companion.

### Spellcasting

- **BONUS:** CASTERLEVEL|Ranger|2

When casting ranger spells, you level is treated as 2 higher than normal. If you have arcane spell caster levels, you may add them to your ranger level as well.

### Spell List

- **SPELLKNOWN:** CLASS|Ranger=2|See Invisibility
- **SPELLKNOWN:** CLASS|Ranger=4|Word of Recall

You add see invisibility (2nd level) and word of recall (4th level) to your ranger spell list. This replaces the swift tracker class feature.

### Know Greatest Enemy


You automatically know which enemy has the highest CR. This applies to enemies within 60 feet. You don't know how tough the enemy is, just which is the most powerful. This replaces the paladin's standard detect evil class feature.

### Vigilant Aid


When you use the aid another special attack in melee combat to give to give an ally a bonus to AC, you spend only a move action rather then a standard action. She can use 2 aid anothers in a single round, but no ally can be aided more than once. This replaces the standard paladin divine health class feature.

### Awesome Smite


You can repel enemies with powerful holy power. As a standard action, she can spend a daily smite evil attempt and strike an evil creature with the Awesome Blow feat. If you use this ability, you don't get your normal smite evil benefit on the blow. You are treated as 1 size category larger than normal for determining what creatures you can affect. If you use it against a non-evil creature, no effect occurs but the smite attempt is spent. This replaces the Turn Undead class feature.

### Tougher than Small


When you would be subject to a size modifier (such as for opposed checks), she is treated as one size larger if doing so is advantageous to her. This stacks with other effects that change your size category. This replaces the standard paladin's aura of courage class feature.

### Uncanny Dodge


You gain the Uncanny Dodge feature instead of the Turn Undead class feature.

### Haste Self

- **SPELLS:** Class|TIMES=((PaladinLVL/5)+1)|CASTERLEVEL=(PaladinLVL/2)|Haste

You can use the haste effect on yourself %1 per day. This replaces the 1st level spell slot gained at 6th level.|((PaladinLVL/5)+1)

### Weapon and Armor Proficiency

- **AUTO:** ARMORPROF|ARMORTYPE=Heavy|ARMORTYPE=Light|ARMORTYPE=Medium

You gain proficiency in light, medium, and heavy armor.

### Flying Hunt Armor


At 1st level you are considered a novice and receive a suit of flying hunt armor. If the suit of armor is lost or destroyed, you must pay the gp cost to replace it.

### Pegasus Mount


You receive a trained pegasus to serve you in your defense of Nimbral. The mount remains with you until it is slain or dismissed. It requires food and rest and you are responsible for its needs. When riding it, you gain a competence bonus of %1 on your Ride checks. If the mount dies, you can have it raised (at normal cost) or obtain another mount (with 1 week of training and meditation).|Knight of the Flying HuntLVL

### Armored Ease

- **DEFINE:** ArmoredEase|0
- **BONUS:** MISC|ACCHECK|-1*ArmoredEase

You have learned to adapt your movements to restrictive armors. You ACP is reduced by %1.|ArmoredEase

### Storm Armor


You are considered a full Knight and your flying hunt armor is enhanced to become storm armor.

### Greater Storm Armor


You are recognized as an excellent and experienced leader. You armor is upgraded to greater storm armor and you can add one effect to it (Arrow Deflection, Fortification (light), Magic Missile (3/day, CL 7), Mirror Image (1/day; CL 10), Spell Resistance 13, or Water Walk (as the ring)); Alternatively, you may pick your own additional armor mod with a price of up to 30000 gp or +3 mod bonus and add it paying just 75%% of the normal cost.

### Read Magic

- **SPELLS:** Class|TIMES=ATWILL|CASTERLEVEL=Caster_Level_Knight_of_the_Weave|Read Magic

You can use Read Magic at Will.

### Armored Caster


You can cast arcane spells in light armor without being subject to spell failure.

You can cast arcane spells in light or medium armor without being subject to spell failure.

### Fast Metamagic


When spontaneously casting an arcane spell (Knight or Sorcerer spell), you can expend an extra slot (must equal or exceed the spell slot used to cast the metamagic affected spell) to cast the spell with one or more metamagic effects applied without extending the casting time.

### Spellfire


You can convert your available arcane spells (from any class) to healing spellfire. Converting 1 spell slot heals by touch 2 hp/spell level spent.

You can also convert your arcane spells into spellfire blasts. As a standard action, you can convert a single spell into a ranged touch attack (400 ft max), dealing 1d6 points of spellfire damage/spell level expended. Reflex DC 20 for half. Half of the total damage is fire and half is raw magic.

### Aura of Good

- **BONUS:** VAR|AuraGoodLvl|TriadicKnightLVL

A Triadic Knight levels stack with other classes levels for the purpose of determining the power of your aura of good.

### Special Mount

- **BONUS:** VAR|SpecialMountLVL|TriadicKnightLVL

A Triadic Knight gains the service of a special steed. This stacks with Paladin levels.

### Hands of Ilmater


A Triadic Knights can no longer become nauseated or sickened.

### Martyr's Embrace

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=(TriadicKnightLVL * 2)|Shield Other

A Triadic Knight can cast Shield Other 1/day; caster level equal to twice class level.

### Eyes of Tyr


A Triadic Knight can no longer become dazzled or blinded (except by physical damage).

### Judge's Insight

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=(TriadicKnightLVL * 2)|Discern Lies

A Triadic Knight can cast Discern Lies 1/day; caster level equal to twice class level.

### Heart of Torm


A Triadic Knight is immune to fear.

### Lion's Roar

- **SPELLS:** Class|TIMES=1|CASTERLEVEL=(TriadicKnightLVL * 2)|Shout

A Triadic Knight can cast Should 1/day; caster level equal to twice class level.

### Threefold Smite


A Triadic Knight can combine three Smite Evil attempts in a single attack; doing so requires requires a full round action, and both requires and costs three of your daily attempts. This triples the bonus on damage rolls (+%1); as Triadic Knight levels are stacked with Paladin levels.|((TriadicKnightLVL + PaladinSmiteEvilLVL) * 3)

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

### ABILITYCATEGORY:Ranger Natural Combat Style

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Ranger Combat Styles
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Triadic Knight Class Feature

- **EDITABLE:** NO
- **EDITPOOL:** NO
- **PLURAL:** Triadic Knight Class Features
- **DISPLAYLOCATION:** Class Features

### ABILITYCATEGORY:Fangshield Ranger Weapon Focus

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Fangshield Ranger Weapon Foci
- **DISPLAYLOCATION:** Class Features

## Classes

### SUBSTITUTIONCLASS:Berronar Valkyrie

- **PREDEITY:** 1,Berronar
- **PREGENDER:** F
- **PRERACE:** 1,Dwarf%

### SUBSTITUTIONLEVEL:3

- **ABILITY:** Special Ability|AUTOMATIC|Berronar Valkyrie ~ Everbright Blessing

### SUBSTITUTIONLEVEL:4

- **ABILITY:** Special Ability|AUTOMATIC|Berronar Valkyrie ~ Valiant Rescue
- **ADD:** SPELLCASTER|Paladin

### SUBSTITUTIONLEVEL:6

- **ABILITY:** Special Ability|AUTOMATIC|Berronar Valkyrie ~ Binding Oath|Berronar Valkyrie ~ Touch of Fatigue
- **ADD:** SPELLCASTER|Paladin

### SUBSTITUTIONCLASS:Broken One

- **ADD:** CLASSSKILLS|Heal,Survival
- **PREDEITY:** 1,Ilmater

### SUBSTITUTIONLEVEL:7

- **BONUS:** VAR|LocateCreatureLVL|CL
- **ABILITY:** Special Ability|AUTOMATIC|Broken One ~ Locate Creature

### SUBSTITUTIONCLASS:Claw of the Sun and the Ankh

- **PREDEITY:** 1,Horus-Re

### SUBSTITUTIONLEVEL:1

- **ABILITY:** Special Ability|AUTOMATIC|Claw of the Sun and the Ankh ~ Bird of Prey|Paladin ~ Aura of Good|Paladin ~ Detect Evil

### SUBSTITUTIONLEVEL:12

- **BONUS:** SPELLCAST|CLASS=Paladin;LEVEL=3|-1
- **ABILITY:** Special Ability|AUTOMATIC|Claw of the Sun and the Ankh ~ Horus-Re's Glory
- **ADD:** SPELLCASTER|Paladin

### SUBSTITUTIONCLASS:Crescent Moon Knight

- **ADD:** CLASSSKILLS|Knowledge (Impiltur)
- **PREDEITY:** 1,Clangeddin Silverbeard,Selune

### SUBSTITUTIONLEVEL:10

- **BONUS:** SPELLCAST|CLASS=Paladin;LEVEL=2|-1
- **ABILITY:** Special Ability|AUTOMATIC|Crescent Moon Knight ~ Battlesong
- **ADD:** SPELLCASTER|Paladin

### SUBSTITUTIONCLASS:Darksong Knight

- **ADD:** CLASSSKILLS|Perform (Dance)
- **PREDEITY:** 1,Eilistrae
- **HD:** 8

### SUBSTITUTIONLEVEL:2

- **ABILITY:** Special Ability|AUTOMATIC|Darksong Knight ~ Dancing Feint

### SUBSTITUTIONLEVEL:8

- **ABILITY:** Special Ability|AUTOMATIC|Darksong Knight ~ Combat Dancing

### SUBSTITUTIONCLASS:Dukar

- **PREITEM:** 1,Dukar Hand Coral
- **PRETEXT:** The character must undergo a ritual and have living coral implanted under his skin.

### SUBSTITUTIONLEVEL:5

- **ABILITY:** Special Ability|AUTOMATIC|Dukar ~ Bonus Spells 1|Dukar ~ Coral Claw
- **ADD:** SPELLCASTER|Wizard

### SUBSTITUTIONLEVEL:15

- **BONUS:** ABILITYPOOL|CoralPowerAbility|1
- **ABILITY:** Special Ability|AUTOMATIC|Dukar ~ Bonus Spells 3
- **ADD:** SPELLCASTER|Wizard

### SUBSTITUTIONCLASS:Eternal Order

- **PREDEITY:** 1,Kelemvor

### SUBSTITUTIONCLASS:Fangshield Barbarian

- **PRERACETYPE:** Animal,Fey,Giant,Magical Beast,Monstrous Humanoid

### SUBSTITUTIONCLASS:Fangshield Druid

- **PRERACETYPE:** Animal,Fey,Giant,Magical Beast,Monstrous Humanoid

### SUBSTITUTIONCLASS:Golden Cup

- **PREDEITY:** 1,Ilmater

### SUBSTITUTIONCLASS:Golden Lion

- **PREDEITY:** 1,Torm

### SUBSTITUTIONCLASS:Holy Judge

- **PREDEITY:** 1,Tyr

### SUBSTITUTIONCLASS:Lion Legionnaire

- **PREDEITY:** 1,Nobanion

### SUBSTITUTIONCLASS:Mystic Fire Knight

- **PREDEITY:** 1,Mystra
- **HD:** 8

### SUBSTITUTIONCLASS:Noble Heart

- **PREDEITY:** 1,Ilmater

### SUBSTITUTIONCLASS:Phoenix Disciple

- **PREALIGN:** LG
- **PREDEITY:** 1,Kossuth

### SUBSTITUTIONCLASS:Purple Staff

- **PREDEITY:** 1,Chauntea,Helm,Lathander,Nobanion,Selune,Sune

### SUBSTITUTIONLEVEL:9

- **ABILITY:** Special Ability|AUTOMATIC|Purple Staff ~ Turn Invader
- **ADD:** SPELLCASTER|Cleric

### SUBSTITUTIONCLASS:Red Falcon

- **PREDEITY:** 1,Red Knight

### SUBSTITUTIONCLASS:Ruby Rose Knight

- **PREDEITY:** 1,Sune
- **HD:** 8

### SUBSTITUTIONCLASS:Shadow Sword

- **PREDEITY:** 1,Shaundakul

### SUBSTITUTIONCLASS:Shooting Star

- **PREDEITY:** 1,Mystra

### SUBSTITUTIONLEVEL:11

- **BONUS:** SPELLCAST|CLASS=Ranger;LEVEL=3|1
- **ADD:** SPELLCASTER|Ranger

### SUBSTITUTIONLEVEL:14

- **BONUS:** SPELLCAST|CLASS=Ranger;LEVEL=4|1
- **ADD:** SPELLCASTER|Ranger

### SUBSTITUTIONCLASS:Wary Swordknight

- **PREDEITY:** 1,Arvoreen
- **PRERACE:** 1,Halfling%

### CLASS:Knight of the Flying Hunt

- **HD:** 6
- **FACT:** ClassType|Prestige
- **FACT:** Abb|KotFH
- **MAXLEVEL:** 10
- **DEFINE:** KnightoftheFlyingHuntLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|KnightoftheFlyingHuntLVL|CL
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### 1

- **ABILITY:** Special Ability|AUTOMATIC|Knight of the Flying Hunt ~ Flying Hunt Armor|Knight of the Flying Hunt ~ Pegasus Mount|Knight of the Flying Hunt ~ Weapon and Armor Proficiency

### 2

- **BONUS:** VAR|ArmoredEase|2
- **ABILITY:** Special Ability|AUTOMATIC|Knight of the Flying Hunt ~ Armored Ease

### 4

- **BONUS:** ABILITYPOOL|Knight of the Flying Hunt Bonus Feat|(CL/4)

### 5

- **ABILITY:** Special Ability|AUTOMATIC|Knight of the Flying Hunt ~ Storm Armor

### 7

- **BONUS:** VAR|ArmoredEase|2

### 10

- **ABILITY:** Special Ability|AUTOMATIC|Knight of the Flying Hunt ~ Greater Storm Armor

### CLASS:Knight of the Weave

- **HD:** 8
- **FACT:** ClassType|Prestige
- **FACT:** Abb|KotW
- **MAXLEVEL:** 10
- **DEFINE:** KnightoftheWeaveLVL|0
- **DEFINE:** KnightoftheWeaveCasterLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|KnightoftheWeaveLVL|CL
- **BONUS:** VAR|KnightoftheWeaveCasterLVL|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### 6

- **ABILITY:** Special Ability|AUTOMATIC|Knight of the Weave ~ Spellfire

### 3

- **CAST:** 0,3,2
- **KNOWN:** 0,3,2

### 8

- **CAST:** 0,4,4,3,3,2,2
- **KNOWN:** 0,4,4,3,3,2,2

### 9

- **CAST:** 0,4,4,4,3,3,2
- **KNOWN:** 0,4,4,4,3,3,2

### CLASS:Triadic Knight

- **HD:** 10
- **FACT:** ClassType|Prestige
- **FACT:** Abb|Triadic
- **MAXLEVEL:** 7

## Equipment

### Glassteel Chain Shirt

- **PROFICIENCY:** ARMOR|Chain Shirt
- **COST:** 2100
- **WT:** 12
- **ACCHECK:** 0
- **EQMOD:** Glasssteel (Armor/Light)
- **MAXDEX:** 6
- **SPELLFAILURE:** 18
- **BONUS:** COMBAT|AC|4|TYPE=Armor

### Glassteel Scale Mail

- **PROFICIENCY:** ARMOR|Scale Mail
- **COST:** 6050
- **WT:** 15
- **ACCHECK:** -1
- **EQMOD:** Glasssteel (Armor/Light)
- **MAXDEX:** 5
- **SPELLFAILURE:** 23
- **BONUS:** COMBAT|AC|4|TYPE=Armor

### Glassteel Chainmail

- **PROFICIENCY:** ARMOR|Chainmail
- **COST:** 6150
- **WT:** 20
- **ACCHECK:** -2
- **EQMOD:** Glasssteel (Armor/Light)
- **MAXDEX:** 4
- **SPELLFAILURE:** 27
- **BONUS:** COMBAT|AC|5|TYPE=Armor

### Glassteel Breastplate

- **PROFICIENCY:** ARMOR|Breastplate
- **COST:** 6200
- **WT:** 15
- **ACCHECK:** -1
- **EQMOD:** Glasssteel (Armor/Medium)
- **MAXDEX:** 5
- **SPELLFAILURE:** 23
- **BONUS:** COMBAT|AC|5|TYPE=Armor

### Glassteel Splint Mail

- **PROFICIENCY:** ARMOR|Splint Mail
- **COST:** 12200
- **WT:** 22
- **ACCHECK:** -4
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 2
- **SPELLFAILURE:** 36
- **BONUS:** COMBAT|AC|6|TYPE=Armor

### Glassteel Banded Mail

- **PROFICIENCY:** ARMOR|Banded Mail
- **COST:** 12250
- **WT:** 17
- **ACCHECK:** -3
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 3
- **SPELLFAILURE:** 32
- **BONUS:** COMBAT|AC|6|TYPE=Armor

### Glassteel Half-Plate

- **PROFICIENCY:** ARMOR|Half-Plate
- **COST:** 12600
- **WT:** 25
- **ACCHECK:** -4
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 2
- **SPELLFAILURE:** 36
- **BONUS:** COMBAT|AC|7|TYPE=Armor

### Glassteel Full Plate

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 13500
- **WT:** 25
- **ACCHECK:** -3
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 3
- **SPELLFAILURE:** 32
- **BONUS:** COMBAT|AC|8|TYPE=Armor

### Glassteel Buckler

- **PROFICIENCY:** SHIELD|Buckler
- **COST:** 2015
- **WT:** 2
- **ACCHECK:** 0
- **EQMOD:** Glasssteel (Shield)
- **SPELLFAILURE:** 4
- **BONUS:** COMBAT|AC|1|TYPE=Shield
- **BONUS:** COMBAT|TOHIT|-1
- **BONUS:** COMBAT|TOHIT-SECONDARY|-1

### Glassteel Shield (Light/Metal)

- **PROFICIENCY:** SHIELD|Shield (Light)
- **COST:** 2009
- **WT:** 3
- **ACCHECK:** 0
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d3
- **EQMOD:** Glasssteel (Shield)
- **WIELD:** Light
- **SIZE:** M
- **SPELLFAILURE:** 4
- **BONUS:** COMBAT|AC|1|TYPE=Shield

### Glassteel Shield (Heavy/Metal)

- **PROFICIENCY:** SHIELD|Shield (Heavy)
- **COST:** 2020
- **WT:** 7
- **ACCHECK:** 0
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d4
- **EQMOD:** Glasssteel (Shield)
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLFAILURE:** 14
- **BONUS:** COMBAT|AC|2|TYPE=Shield

### Glassteel Shield (Tower)

- **PROFICIENCY:** SHIELD|Tower Shield
- **COST:** 2030
- **WT:** 22
- **ACCHECK:** -7
- **EQMOD:** Glasssteel (Shield)
- **SPELLFAILURE:** 45
- **BONUS:** COMBAT|AC|4|TYPE=Shield
- **BONUS:** WEAPON|TOHIT|-2
- **BONUS:** WEAPON|TOHIT|SHIELDACCHECK|!PREABILITY:1,CATEGORY=FEAT,Tower Shield Proficiency
- **SPROP:** Tower shields can grant full cover, see text

### Glassteel Barding (Chain Shirt)

- **PROFICIENCY:** ARMOR|Chain Shirt
- **COST:** 2200
- **WT:** 12
- **ACCHECK:** 0
- **EQMOD:** Glasssteel (Armor/Light)
- **MAXDEX:** 6
- **SPELLFAILURE:** 18
- **BONUS:** COMBAT|AC|4|TYPE=Armor

### Glassteel Barding (Scale Mail)

- **PROFICIENCY:** ARMOR|Scale Mail
- **COST:** 6100
- **WT:** 15
- **ACCHECK:** -1
- **EQMOD:** Glasssteel (Armor/Medium)
- **MAXDEX:** 5
- **SPELLFAILURE:** 23
- **BONUS:** COMBAT|AC|4|TYPE=Armor

### Glassteel Barding (Chainmail)

- **PROFICIENCY:** ARMOR|Chainmail
- **COST:** 6300
- **WT:** 20
- **ACCHECK:** -2
- **EQMOD:** Glasssteel (Armor/Medium)
- **MAXDEX:** 4
- **SPELLFAILURE:** 27
- **BONUS:** COMBAT|AC|5|TYPE=Armor

### Glassteel Barding (Breastplate)

- **PROFICIENCY:** ARMOR|Breastplate
- **COST:** 6400
- **WT:** 15
- **ACCHECK:** -1
- **EQMOD:** Glasssteel (Armor/Medium)
- **MAXDEX:** 5
- **SPELLFAILURE:** 23
- **BONUS:** COMBAT|AC|5|TYPE=Armor

### Glassteel Barding (Splint Mail)

- **PROFICIENCY:** ARMOR|Splint Mail
- **COST:** 12400
- **WT:** 22
- **ACCHECK:** -4
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 2
- **SPELLFAILURE:** 36
- **BONUS:** COMBAT|AC|6|TYPE=Armor

### Glassteel Barding (Banded Mail)

- **PROFICIENCY:** ARMOR|Banded Mail
- **COST:** 12500
- **WT:** 17
- **ACCHECK:** -3
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 3
- **SPELLFAILURE:** 32
- **BONUS:** COMBAT|AC|6|TYPE=Armor

### Glassteel Barding (Half-Plate)

- **PROFICIENCY:** ARMOR|Half-Plate
- **COST:** 13200
- **WT:** 25
- **ACCHECK:** -4
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 2
- **SPELLFAILURE:** 36
- **BONUS:** COMBAT|AC|7|TYPE=Armor

### Glassteel Barding (Full Plate)

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 15000
- **WT:** 25
- **ACCHECK:** -3
- **EQMOD:** Glasssteel (Armor/Heavy)
- **MAXDEX:** 3
- **SPELLFAILURE:** 32
- **BONUS:** COMBAT|AC|8|TYPE=Armor

### Albruin

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 49475
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** ALCHM
- **WIELD:** OneHanded
- **SIZE:** M
- **SPELLS:** Magic Item|TIMES=3|CASTERLEVEL=9|Cure Moderate Wounds|Invisibility Purge
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=9|Neutralize Poison
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=9|Read Magic
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **QUALITY:** Bright Illumination|20 ft.
- **QUALITY:** Shadowy Illumination|40 ft.
- **SPROP:** AL CN; Int 17, Wis 10, Cha 17; Speech (Common, Elven, Undercommon, Thieves' Cant); Telepathy; 120 ft. Darkvision & Hearing; Ego score 16; Can shed eerie blue light (equiv to spell) when drawn;

### Chalsembyr's Heart

- **PROFICIENCY:** WEAPON|Greatsword
- **COST:** 12
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 2d6
- **EQMOD:** C_IRON.MAGIC_COST|90126.Masterwork (Weapon).PLUS2W
- **WIELD:** TwoHanded
- **SIZE:** M
- **BONUS:** WEAPON|DAMAGE,TOHIT|3|TYPE=Enhancement
- **SPROP:** In the hands of a paladin of Torm, the weapon is a +5 holy cold iron greatsword; AL LG; Int 13, Wis 14, Cha 16; Telepathy, 120 ft. vision and hearing, read languages; Ego score 24; It has 10 ranks in Decipher Script and Knowledge (history Chalsembyr); Detect Thoughts at will, and can perform soul bind on the paladin's death.

### Dornavver

- **PROFICIENCY:** WEAPON|Sword (Bastard)
- **COST:** 70
- **WT:** 12
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d10
- **EQMOD:** BANE_M|Outsider.MAGIC_COST|229965.Masterwork (Weapon).PLUS3W.STEEL
- **WIELD:** TwoHanded
- **SIZE:** M
- **ABILITY:** FEAT|VIRTUAL|Improved Initiative
- **BONUS:** WEAPON|WIELDCATEGORY|-1
- **QUALITY:** Bright Illumination|20 ft.
- **QUALITY:** Shadowy Illumination|40 ft.
- **SPROP:** The sword's glow only works within 60 ft of a demon. The bearer gets a +3 on all saves against demons. Any demon struck by the blade must make a DC 20 Will save or be blocked from using its summoning ability for 1 hour.

### Hadryllis

- **PROFICIENCY:** WEAPON|Greatsword
- **COST:** 12
- **WT:** 8
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 2d6
- **EQMOD:** BANE_M|Outsider.C_IRON.MAGIC_COST|100000.Masterwork (Weapon).PLUS3W
- **WIELD:** TwoHanded
- **SIZE:** M
- **SPELLS:** Magic Item|TIMES=3|CASTERLEVEL=18|Blindness/Deafness|Bull's Strength|Invisibility Purge
- **SPELLS:** Magic Item|TIMES=ATWILL|CASTERLEVEL=18|Detect Magic
- **QUALITY:** Bright Illumination|20 ft.
- **QUALITY:** Shadowy Illumination|40 ft.
- **SPROP:** AL CG; Int 17, Wis 10, Cha 17; Speech (Common, Dwarf, Elf, Orc, Raumvira); Telepathy; 120 ft. darkvision and hearing; Ego score 19.

### Oath-Hammer

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 12
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** MAGIC_COST|22288.Masterwork (Weapon).PLUS2W.STEEL
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** If you activate the hammer by swearing an oath in dwarven. In which case, the hammer becomes +5, does an extra 2d6 points of damage, and increases its critical multiplier to x4.

### Flaming Oath-Hammer

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 12
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** FLM_M.MAGIC_COST|26288.Masterwork (Weapon).PLUS2W.STEEL
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** If you activate the hammer by swearing an oath in dwarven. In which case, the hammer becomes +5, does an extra 2d6 points of damage, and increases its critical multiplier to x4.

### Drow-Bane Oath-Hammer

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 12
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** BANE_M|Humanoids (elf).MAGIC_COST|26288.Masterwork (Weapon).PLUS2W.STEEL
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** If you activate the hammer by swearing an oath in dwarven. In which case, the hammer becomes +5, does an extra 2d6 points of damage, and increases its critical multiplier to x4.

### Throwing Returning Oath-Hammer

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 12
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** MAGIC_COST|30288.Masterwork (Weapon).PLUS2W.RETRN.STEEL.THROW
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** If you activate the hammer by swearing an oath in dwarven. In which case, the hammer becomes +5, does an extra 2d6 points of damage, and increases its critical multiplier to x4.

### Doomwarding Oath-Hammer

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 12
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** CHARGED_ITEM_7|CHARGES[7].MAGIC_COST|22288.Masterwork (Weapon).PLUS2W.STEEL
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** If you activate the hammer by swearing an oath in dwarven. In which case, the hammer becomes +5, does an extra 2d6 points of damage, and increases its critical multiplier to x4.

### Knockback Oath-Hammer

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 12
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** KNOCKBACK_WEAP.MAGIC_COST|66288.Masterwork (Weapon).PLUS2W.STEEL
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** If you activate the hammer by swearing an oath in dwarven. In which case, the hammer becomes +5, does an extra 2d6 points of damage, and increases its critical multiplier to x4.

### Anvil of Hope

- **PROFICIENCY:** WEAPON|Warhammer
- **COST:** 12
- **WT:** 5
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** MAGIC_COST|13600.MERC_M.Masterwork (Weapon).PLUS1W.STEEL
- **WIELD:** OneHanded
- **RANGE:** 30
- **SIZE:** M
- **SPROP:** It can produce a good hope effect once per day. It emits a 60-ft aura that affects good dwarves. Any such opponent must make a DC 11 Will save or leave the battle to ponder for 1 hour.

### Lady Justice

- **PROFICIENCY:** WEAPON|Longsword
- **COST:** 8
- **WT:** 4
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d8
- **EQMOD:** MAGIC_COST|17007.MERC_M.Masterwork (Weapon).PLUS1W.STEEL
- **WIELD:** OneHanded
- **SIZE:** M
- **SPROP:** The weapon can free opponents under the effect of magic that causes them to attack you. You get to make a dispel check (d20+10). It also radiates a protective aura in a 20-ft radius that gives a +4 resistance bonus against mind-affecting spells.

### Lord of Sleep

- **PROFICIENCY:** WEAPON|Longbow
- **CONTAINS:** UNLIM|Arrow|SpecificArrow
- **COST:** 8
- **WT:** 3
- **SLOTS:** 2
- **CRITMULT:** x3
- **CRITRANGE:** 1
- **DAMAGE:** 1d8
- **EQMOD:** MAGIC_COST|24467.MERC_R.Masterwork (Weapon).PLUS1W.WOOD
- **WIELD:** TwoHanded
- **RANGE:** 110
- **SIZE:** M
- **SPROP:** It can fire rays of light that cause targets with 4 HD or less to make a DC 11 Will save or fall asleep for 10 minutes as if affected by a sleep spell. It can fire up to 5 of these arrows per round. Once per day it can produce a solid fog effect.

### Maid of the Waters

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
- **EQMOD:** MAGIC_COST|20800.MERC_M.Masterwork (Weapon).PLUS1W.WOOD
- **ALTEQMOD:** MERC_M.Masterwork (Weapon).PLUS1W.WOOD
- **WIELD:** TwoHanded
- **SIZE:** M
- **SPROP:** It radiates a calm emotions effect. Once per day it can twist to form a symbol of persuasion. All creatures affected by it view the wielder as a friend.

### Mace of the Brightwalkers

- **PROFICIENCY:** WEAPON|Mace (Light)
- **COST:** 5
- **WT:** 3
- **CRITMULT:** x2
- **CRITRANGE:** 1
- **DAMAGE:** 1d6
- **EQMOD:** MAGIC_COST|14695.Masterwork (Weapon).PLUS1W.STEEL
- **WIELD:** Light
- **SIZE:** M
- **BONUS:** VAR|TurnDamagePlusUndead|6
- **SPROP:** This mace grants the wielder a +6 sacred bonus on turning checks.

### Vilebiter Blade

- **PROFICIENCY:** WEAPON|Dagger
- **COST:** 2
- **WT:** 1
- **CRITMULT:** x2
- **CRITRANGE:** 2
- **DAMAGE:** 1d4
- **EQMOD:** MAGIC_COST|6400.Masterwork (Weapon).PLUS1W.STEEL
- **WIELD:** Light
- **RANGE:** 10
- **SIZE:** M
- **SPROP:** When used against an evil opponent, the bonus increases to +2, and an evil target must make a DC 16 Will save or take 1 point of damage to a random ability score.

### Flying Hunt Armor

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1000
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** ARMRGLSSTLH.MAGIC_COST|500.Masterwork (Armor).PLUS1A
- **MAXDEX:** 1
- **SIZE:** M
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** This armor also functions as a ring of feather falling.

### Storm Armor

- **PROFICIENCY:** ARMOR|Full Plate
- **COST:** 1000
- **WT:** 50
- **ACCHECK:** -6
- **EQMOD:** ARMRGLSSTLH.INVULN.MAGIC_COST|500.Masterwork (Armor).PLUS1A.RST_ELE
- **MAXDEX:** 1
- **SIZE:** M
- **SPELLFAILURE:** 35
- **BONUS:** COMBAT|AC|8|TYPE=Armor
- **SPROP:** This armor also functions as a ring of feather falling.

### Dukar Hand Coral

- **COST:** 1600
- **WT:** 0
- **SPROP:** You add your hit dice to your daily regeneration rate. You can regenerate missing tissues. It extends the amount of time you can be in or out of water.

### Faith Token (Arvoreen)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Message|Virtue

### Faith Token (Chauntea)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Mending|Naturewatch

### Faith Token (Corellon Larethian)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Magic|Summon Instrument

### Faith Token (Eilistraee)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Ghost Sound|Guidance

### Faith Token (Garl Glittergold)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Prestidigitation|Virtue

### Faith Token (Hanali Celanil)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Minor Disguise

### Faith Token (Helm)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Virtue

### Faith Token (Horus-Re)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Flare|Message

### Faith Token (Ilmater)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Cure Minor Wounds

### Faith Token (Lathander)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Light

### Faith Token (Lurue)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Cure Minor Wounds|Light

### Faith Token (Mielikki)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Detect Poison|Know Direction

### Faith Token (Moradin)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Resistance

### Faith Token (Oghma)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Songbird|Summon Instrument

### Faith Token (Selune)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Light|Lullaby

### Faith Token (Sune)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Daze|Minor Disguise

### Faith Token (Torm)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Guidance|Virtue

### Faith Token (Tymora)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Guidance

### Faith Token (Tyr)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Resistance|Virtue

### Faith Token (Yondalla)

- **COST:** 300
- **WT:** 0
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=1|Open/Close|Purify Food and Drink

### Harper Token

- **COST:** 300
- **WT:** 0
- **SPROP:** Provides a +2 competence bonus on a single skill such as Climb, Diplomacy, Hide, Knowledge (Arcana), or Perform (Sing).

### Ring of Truth-Telling

- **COST:** 27000
- **WT:** 0
- **SPROP:** The ring provides the effects of both detect thoughts and zone of truth within a 20-foot-radius as long as the wearer concentrates or up to 3 minutes.

### Tabard of the Nimbral Herald

- **COST:** 5400
- **WT:** 2
- **SPROP:** Once per day you can fly for up to 5 minutes.

### Zundaerazylm's Nevertokens

- **COST:** 67000
- **WT:** 0.5
- **SPROP:** Functions as a glove of storing, a ring of feather falling, and ring of mind shielding. They also have the powers of Sending, Teleport, Trace Nevertoken (as know direction).

### Crown of Narfell

- **COST:** 900000
- **WT:** 5
- **SPROP:** At will, once per round, the bearer can use any of the following effects: favor of Ilmater, Glory of the Martyr, Hand of Tomr, Holy Sword, Mark of Justice, or Order's Wrath. 3 times per day, the bearer can cloak himself in a holy aura effect.

### Doomwarden Bracers

- **COST:** 58300
- **WT:** 1
- **SLOTS:** 2
- **SPELLS:** Magic Item|TIMES=1|CASTERLEVEL=7|Consecrate|Death Ward|Holy Smite
- **BONUS:** COMBAT|AC|3|TYPE=Armor

### Mask of Tears

- **COST:** 17000
- **WT:** 0
- **SPROP:** Any NPC who sees the a you wearing the mask must succeed on a DC 14 Will save or have his attitude shifted one category away from hostile. Once per day the wearer can spit forth tears from the mask with a range increment of 10 feet. WWhen used in this way it has a cure critical wounds effect upon the creature it strikes. If a bard wears the mask, his spells and music effects relying on sadness or despair last 1 round longer.

### Staff of Celestial Light

- **COST:** 98200
- **WT:** 5
- **BASEITEM:** Staff
- **EQMOD:** CHARGED_ITEM_50|CHARGES[50]
- **SPROP:** Can activate the following spells: Daylight (1 charge), Summon Monster IX (Iconal Guardinal) (2 charges), Dispel Magic (2 charges), Searing Light (2 charges).

## Equipment Modifiers

### Home Champion

- **PLUS:** 1
- **ITYPE:** HomeC
- **PRETYPE:** 3,Enhancement,Weapon,Ranged
- **!PRETYPE:** 1,Thrown
- **SPROP:** In homeland, wielded by Defender, weapon gains +2 enhancement and deals an extra 2d6 of damage. Hit opponent is bestowed one negative level.

### Sacrificial Smite

- **PLUS:** 1
- **ITYPE:** SACRS
- **PRETYPE:** 3,Enhancement,Weapon,Ranged
- **!PRETYPE:** 1,Thrown
- **SPROP:** Gain one extra smite for one negative level.

### Glassteel

- **COST:** WT*100
- **ITYPE:** Glassteel.Masterwork
- **REPLACES:** Masterwork (Weapon),Masterwork (Instrument),Masterwork (Tools)
- **PRETYPE:** 1,Metal
- **BONUS:** EQM|WEIGHTDIV|2|TYPE=Enhancement.REPLACE
- **BONUS:** WEAPON|TOHIT|1|TYPE=Enhancement
- **BONUS:** WEAPON|TOHIT|1|TYPE=Enhancement
- **SPROP:** 40hp/inch and 20 hardness

## Feats

### Broken One's Sacrifice

- **PRESTAT:** 1,WIS=13
- **PRETEXT:** Member of the Broken Ones monk order

You choose to suffer damage or ill effect intended for ally

As an immediate action, you can intervene on behalf of an adjacent ally (of your size or smaller). When you activate the feat, you change places. In addition to taking the effect your ally would have, you become fatigued.

### Carmendine Monk

- **PRESTAT:** 1,INT=13
- **PRETEXT:** Member of the Zealots of the Written Word monk order
- **DEFINE:** CarmendineMonkBonus|0
- **ABILITY:** Special Ability|AUTOMATIC|Carmendine Monk ~ AC Bonus|Carmendine Monk ~ Speed Bonus|Carmendine Monk ~ Unarmed Damage
- **BONUS:** COMBAT|AC|if((INT>WIS),(INT-WIS),0)
- **BONUS:** VAR|QuiveringPalmDC|if((INT>WIS),(INT-WIS),0)
- **BONUS:** VAR|StunningFistDC|if((INT>WIS),(INT-WIS),0)

Use your Int bonus instead of Wis bonus for monk abilities; treat your monk level as one higher for a selected monk ability

You use your Intelligence bonus instead of your Wisdom bonus for determining your monk AC bonus and for determining your studding fist and quivering palm DCs. You can study your thesis notes for 1 hour to treat your Monk level as 2 higher for determining your unarmed damage, AC bonus, or unarmored speed bonus. This effect lasts for 24 hours.

### Detect Shadow Weave User

- **PRESKILL:** 2,Knowledge (Arcana)=5,Spellcraft=5

You can tell whether a spell comes from the Weave or the Shadow Weave

When you observe spell casting or magical effects you can make a Spellcraft check (DC 15 + spell level) as an immediate action to determine whether it is powered by the Weave or Shadow Weave. When using detect magic, you automatically identify this on any aura you detect.

### Druuth Slayer

- **PRESKILL:** 2,Knowledge (Dungeoneering)=2,Knowledge (Nature)=2
- **BONUS:** SAVE|Will|1

+1 bonus on Will saves; recognize shapechanged doppelgangers; new save against mind flayer's mind blast each round

This feat grants 3 benefits. First, you get a +1 bonus on Will saves. Second, you gain a +10 bonus to Spot checks to recognize a doppelganger that is shapechanged. Third, if affected by a mind flayer's mind blast, you get a new saving throw every round at the end of your turn to end the stun effect.

### From Smite to Song

- **PRESKILL:** 1,TYPE.Perform=3
- **PRETEXT:** Member of the Harmonious Order
- **ABILITY:** Special Ability|AUTOMATIC|Bardic Music ~ Inspire Courage
- **BONUS:** VAR|InspireCourageLVL|classlevel("Paladin%")
- **CSKILL:** TYPE=Perform

Spend one smite evil attempt to inspire courage; add Perform to list of class skills

You can spend smite evil attempt to duplicate the effects of the inspire courage bardic music ability. Your effect bard level is equal to your paladin level. You also add Perform as a paladin class skill.

### Overcome Shadow Weave

- **PRECHECKBASE:** 1,Will=3
- **PRESKILL:** 2,Knowledge (Arcana)=5,Spellcraft=5
- **PRETEXT:** Weave Using spell caster

+5 bonus on caster level checks to detect, counterspell, and dispel Shadow Weave effects

You get a +5 bonus on caster level checks to detect, counterspell, and dispel Shadow Weave effects.

### Silver Blood

- **PRECHECKBASE:** 1,Fortitude=2

Immune to lycanthropy; any lycanthrope that bites you must make a Fortitude save or take damage

You cannot be infected with lycanthropy. Any lycanthrope that bites you must make a Fortitude save (DC %1) or take %2 damage. This damage is treated as silver for the purpose of overcoming a lycanthrope's damage reduction. If you already were an afflicted lycanthrope, the DCs for your Control Shape checks increase by 5 and you lose your DR. If you were a natural lycanthrope, you must make a DC 15 Control Shape check to change form and your DR reduces to 5/silver.|(10+TL/2+CON)|max(1,CON)

### Silver Fang

- **PRECHECKBASE:** 1,Fortitude=4
- **PRETEXT:** Member or ally of the Fangshields

Your natural attacks and unarmed strikes count as silver weapons for the purpose of overcoming DR

Your natural attacks and unarmed strieks count as silver weapons for the purposes of overcomming damage reduction. If you were a lycanthrope, you natural attacks no longer infect others.

### Smiting Power

- **PREABILITY:** 1,CATEGORY=Special Ability,Smite%
- **PREABILITY:** 1,CATEGORY=FEAT,Power Attack

Add smite bonuses to bull rush or overrun

You can use your smite ability when making a bull rush or overrun attempt. You add your smite to hit bonus to your opposed check for the special attack. If you win the check, you deal the damage equal to the smite bonus. You must declare this before beginning the bull rush or overrun attempt.

### Sword of the Arcane Order

- **PRECLASS:** 1,Paladin%=4,Ranger%=4
- **PREDEITY:** 1,Azuth,Mystra
- **PRESTAT:** 1,INT=13
- **PRETEXT:** Member of the Knights of the Mystic Fire, Order of the Shooting Starts, or Swords of the High One
- **BONUS:** CASTERLEVEL|Wizard|RangerLVL
- **BONUS:** CASTERLEVEL|Wizard|PaladinLVL

Use paladin or ranger spell slots to prepare wizard spells that you know; add paladin and ranger class levels to your wizard level to determine your wizard caster level

You can use your paladin and ranger spell slots to prepare wizard spells. You must have a minimum Intelligence of 10 + the spell's level to prepare it. The save DC will be based on your INT mod. These spells can be taken from your spellbook (if you have one) or another character's spellbook (in which case you must succeed on a Spellcraft check to prepare the spell). If you have wizard levels, your caster level is boosted by your paladin or ranger levels.

### Sun Soul Monk

- **PRECLASS:** 1,Monk=4
- **PRETEXT:** Member of the Sun Soul Order

See feat description

You can channel your ki to turn an undead creature. 1/day you can choose to imbue an unarmed strike with ki before your roll the dice. If you hit an undead creature, it is turned unless it succeeds on a Will save (DC %1). If it has turn resistance it adds its modifier to its save attempt. If you have the Stunning Fist feat, you can expend a daily use of that ability to power this feat. If you have turn undead, you can expend a use of that power to use this feat.|(10+TL/2+WIS)

Your unarmed strike deals 1 extra point of cold damage and counts as silver weapons for purposes of overcoming DR. When in moonlight, you treat your monk level as 3 levels higher for your move bonus.

Your combat style is fascinating to watch. 1/day as a standard action, you can perform a maneuver that fascinates a single target within 30 feet that can see you (Will negates, DC %1). Creatures of a different type then you get a +4 bonus on their save. This supernatural effect lasts 1 round. If you have the Stunning Fist feat, you can use daily uses of that to power this feat.|(10+TL/2+CHA)

### Mark of the Triad

- **PREABILITY:** 1,CATEGORY=FEAT,Initiate of Ilmater,Initiate of Torm,Initiate of Tyr

Spend turn undead attempt to imbue a greatsowrd, longsword, or unarmed strike with axiomatic or holy ability for 1 round

You can spend a turn undead attempt as a swift action and imbue your greatsword, longsword or unarmed strike with either the axiomatic or holy special ability. Either effect lasts until the start of your next turn.

### Defender of the Homeland

- **PREALIGN:** LG,NG,CG
- **PRESTAT:** 1,WIS=13

+1 sacred bonus to AC and immunity to fear while in your homeland

When fighting in your home region you gain a +1 sacred bonus to AC and immunity to fear effects.

### Knight of the Red Falcon

- **PRECLASS:** 1,Cleric=4,Fighter=4,Paladin%=4
- **PRETEXT:** Member of the Order of the Red Falcon

+1 morale bonus to AC when adjacent to multiple enemies

You gain a +1 morale bonus to AC when you are adjacent to more than 1 enemy. (Helpless enemies don't count toward this benefit)

### Knight of the Risen Scepter

- **PRECLASS:** 1,Paladin%=8,Ranger%=8
- **PREDEITY:** 1,Osiris

+3 sacred bonus on saves against death, energy drain, or ability drain; resurrected if slain by a follower of set

You get a +4 sacred bonus on saving throws against death effects, energy drain, and ability drain. If you are slain by a follower of Set, you come back to life 1 hour later as though a resurrection was cast upon you. You get a negative level rather then loose 1 level. This negative level remains until you gain a level or kill the follower of set that killed you.

### Knight of Tyr's Holy Judgement

- **PRESTAT:** 1,INT=13
- **PRETEXT:** Member of the Knights of the Holy Judgement

Add your paladin level to Intelligence or Knowledge checks regarding laws; sense presence of devils using detect evil; +1 sacred bonus to AC against devils

You gain a supernatural ability to sense and understand laws. Add you paladin level to any Knowledge or Intelligence checks made regarding laws. When you use your detect evil ability, the second round of use reveals whether or not any creatures in the area of effect are devils. You can identify them in the third round of use by the strength of their aura. You also gain a +1 sacred bonus to AC against devils.

### Knight of Tyr's Merciful Sword

- **PRESTAT:** 1,WIS=13
- **PRETEXT:** Member of the Knights of the Merciful Sword

Sense greatest evil with 1 mile or 10 miles; +1 sacred bonus to AC against demons

You gain the supernatural ability to sense injustice and great evil. Once per week, as a standard action, you can concentrate to sense the direction of a great injustice or evil within 1 mile of you. Alternatively, you can meditate for 8 hours to expand your range to 10 miles. Murder, treason, and the presence of evil outsiders rank highest with this sense, while other crimes, injustices, and evil creatures rank lower, similar to the aura strengths listed in the detect evil spell. You also gain a +1 sacred bonus to AC against demons.

### Paladin of the Noble Heart

- **PRESKILL:** 1,Knowledge (Religion)=4
- **PRETEXT:** Member of the Companions of the Noble Heart

Smite evil once/day against follower of Loviatar or item of her church

You get one extra smite evil attempt per day that can be used only on followers of Loviatar or items of her church. You also get a +1 sacred bonus on Fortitude saves against effects created by the followers of Loviatar.

### Initiate of Anhur

- **PRECLASS:** 1,Cleric=5,Ranger%=5
- **PREDEITY:** 1,Anhur
- **SPELLKNOWN:** CLASS|Cleric=1|Bless Weapon
- **SPELLKNOWN:** CLASS|Ranger=1|Bless Weapon
- **SPELLKNOWN:** CLASS|Ranger=2|Spiritual Weapon
- **SPELLKNOWN:** CLASS|Cleric=2|Thunderstroke
- **SPELLKNOWN:** CLASS|Ranger=2|Thunderstroke

No penalty on Listen checks when distracted or asleep; make attacks of opportunity when flat-footed, add Anhurite spells to your list

You take no penalty on Listen checks for being distracted or asleep. You can make attacks of opportunity when flatfooted as though you had the Combat Reflexes feat. You add 2 or 3 spells to your list.

### Initiate of Arvoreen

- **PRECLASS:** 1,Cleric=4,Paladin%=4
- **PREDEITY:** 1,Arvoreen
- **PRERACE:** 1,Halfling%
- **CSKILL:** Hide|Move Silently
- **SPELLKNOWN:** CLASS|Cleric=1|Enlarge Person
- **SPELLKNOWN:** CLASS|Cleric=1|Low-Light Vision
- **SPELLKNOWN:** CLASS|Cleric=1|Message
- **SPELLKNOWN:** CLASS|Cleric=2|Blade Thirst
- **SPELLKNOWN:** CLASS|Cleric=1|Safe Clearing
- **SPELLKNOWN:** CLASS|Ranger=1|Enlarge Person
- **SPELLKNOWN:** CLASS|Ranger=1|Low-Light Vision
- **SPELLKNOWN:** CLASS|Ranger=1|Message
- **SPELLKNOWN:** CLASS|Ranger=2|Blade Thirst
- **SPELLKNOWN:** CLASS|Ranger=1|Safe Clearing

Hide and Move Silently are class skills; add Arvoreenite spells to your spell list

Add Hide and Move Silently to your list of cleric or paladin class skills. Add 5 spells to your spell list.

### Initiate of Baravar Cloakshadow

- **PRECLASS:** 1,Cleric=4,Paladin%=4
- **PREDEITY:** 1,Baravar Cloakshadow
- **PRERACE:** 1,Gnome%
- **SPELLKNOWN:** CLASS|Cleric=1|Camouflage
- **SPELLKNOWN:** CLASS|Cleric=2|Invisibility
- **SPELLKNOWN:** CLASS|Cleric=2|Invisibility (Swift)
- **SPELLKNOWN:** CLASS|Cleric=3|Displacement
- **SPELLKNOWN:** CLASS|Cleric=4|Dimension Door
- **SPELLKNOWN:** CLASS|Paladin=1|Camouflage
- **SPELLKNOWN:** CLASS|Paladin=2|Invisibility
- **SPELLKNOWN:** CLASS|Paladin=2|Invisibility (Swift)
- **SPELLKNOWN:** CLASS|Paladin=3|Displacement
- **SPELLKNOWN:** CLASS|Paladin=4|Dimension Door

Spend a turn/rebuke attempt to recognize all illusions within 60 ft; add Baravar Cloakshadowite spells to your spell list

You can spend a turn/rebuke attempt to recognize all visible illusion effects within 60 ft of your. If the illusion has a save that includes "disbelief", you are immediately awarded a successful save against it. Illusions that have no visible effect such as invisibility are not revealed by this action. Add 5 spells to your list.

### Initiate of Eilistraee

- **PRECLASS:** 1,Cleric=4,Ranger%=4
- **PREDEITY:** 1,Eilistraee
- **PRERACE:** 1,Elf (Drow%,Half-Elf (Drow)
- **SPELLKNOWN:** CLASS|Cleric=1|Eilistraee's Moonfire
- **SPELLKNOWN:** CLASS|Cleric=3|Spellsong (Lesser)
- **SPELLKNOWN:** CLASS|Cleric=6|Spellsong
- **SPELLKNOWN:** CLASS|Ranger=1|Eilistraee's Moonfire
- **SPELLKNOWN:** CLASS|Ranger=3|Spellsong (Lesser)

Replace one spell-like ability with magic missile 1/day; add Eilistraeeite spells to your spell list

Once per day, you can spend one your racial spell-like abilities (dancing lights, darkness, or faerie fire) to produce a magic missile as a sorcerer of your cleric or ranger level. Add 2 or 3 spells to your spell list.

### Initiate of Holy Realm

- **PRECLASS:** 1,Cleric=3,Paladin%=3,Ranger%=3
- **PREDEITY:** 1,Chauntea,Helm,Lathander,Nobanion,Selune,Sune
- **SPELLKNOWN:** CLASS|Cleric=1|Alarm
- **SPELLKNOWN:** CLASS|Cleric=1|Handfire
- **SPELLKNOWN:** CLASS|Cleric=1|Horrible Taste
- **SPELLKNOWN:** CLASS|Cleric=1|Rosemantle
- **SPELLKNOWN:** CLASS|Cleric=2|Lionheart
- **SPELLKNOWN:** CLASS|Cleric=2|Love Bite
- **SPELLKNOWN:** CLASS|Cleric=2|Warning
- **SPELLKNOWN:** CLASS|Paladin=1|Alarm
- **SPELLKNOWN:** CLASS|Paladin=1|Handfire
- **SPELLKNOWN:** CLASS|Paladin=1|Horrible Taste
- **SPELLKNOWN:** CLASS|Paladin=1|Rosemantle
- **SPELLKNOWN:** CLASS|Paladin=2|Lionheart
- **SPELLKNOWN:** CLASS|Paladin=2|Love Bite
- **SPELLKNOWN:** CLASS|Paladin=2|Warning
- **SPELLKNOWN:** CLASS|Ranger=1|Alarm
- **SPELLKNOWN:** CLASS|Ranger=1|Handfire
- **SPELLKNOWN:** CLASS|Ranger=1|Horrible Taste
- **SPELLKNOWN:** CLASS|Ranger=1|Rosemantle
- **SPELLKNOWN:** CLASS|Ranger=2|Lionheart
- **SPELLKNOWN:** CLASS|Ranger=2|Love Bite
- **SPELLKNOWN:** CLASS|Ranger=2|Warning

+1 sacred bonus on saves within the Holy Realm or while on a quest to help the Holy Realm; add Holy Realmite spells to your spell list

You get a +1 sacred bonus on all saving throws while within the Holy Realm or on a quest for the holy realm. Add 7 spells to your spell list.

### Initiate of Horus-Re

- **PRECLASS:** 1,Cleric=4,Paladin%=4,Ranger%=4
- **PREDEITY:** 1,Horus-Re
- **SPELLKNOWN:** CLASS|Cleric=1|Disk of Solar Vengeance
- **SPELLKNOWN:** CLASS|Cleric=1|Herald's Call
- **SPELLKNOWN:** CLASS|Cleric=2|Stormvoice
- **SPELLKNOWN:** CLASS|Cleric=3|Righteous Fury
- **SPELLKNOWN:** CLASS|Paladin=1|Command
- **SPELLKNOWN:** CLASS|Paladin=1|Disk of Solar Vengeance
- **SPELLKNOWN:** CLASS|Paladin=1|Herald's Call
- **SPELLKNOWN:** CLASS|Paladin=2|Stormvoice
- **SPELLKNOWN:** CLASS|Paladin=3|Searing Light
- **SPELLKNOWN:** CLASS|Ranger=1|Command
- **SPELLKNOWN:** CLASS|Ranger=1|Disk of Solar Vengeance
- **SPELLKNOWN:** CLASS|Ranger=1|Herald's Call
- **SPELLKNOWN:** CLASS|Ranger=2|Stormvoice
- **SPELLKNOWN:** CLASS|Ranger=3|Searing Light

Assume hawk form for 1 hour 1/day; add Horus-Reite spells to your spell list

Once per day you can use wild shape (as the druid ability) to take the shape of a hawk for 1 hour. This is a supernatural ability. Add 4 or 5 spells to your spell list.

### Initiate of Milil

- **PRECLASS:** 1,Cleric=4,Paladin%=4
- **PREDEITY:** 1,Milil
- **PRESKILL:** 1,TYPE.Perform=3
- **BONUS:** VAR|BardicMusicLvl|classlevel("Cleric")
- **BONUS:** VAR|BardicMusicLvl|classlevel("Paladin")
- **SPELLKNOWN:** CLASS|Cleric=1|Harmony
- **SPELLKNOWN:** CLASS|Cleric=2|Dispel Silence
- **SPELLKNOWN:** CLASS|Cleric=3|Reveille
- **SPELLKNOWN:** CLASS|Paladin=1|Harmony
- **SPELLKNOWN:** CLASS|Paladin=2|Dispel Silence
- **SPELLKNOWN:** CLASS|Paladin=3|Reveille

Your bard, cleric, &amp; paladin levels stack for your bardic music abilities, you may spend turn attempts to activate bardic music; add Mililite spells to your spell list

Your bard, cleric, and paladin levels stack for the purpose of determining what kinds of bardic music are available to you. You must still meet the Perform rank requirements. Add 3 spells to your spell list.

### Initiate of Nobanion

- **PRECLASS:** 1,Cleric=4,Paladin%=4
- **PREDEITY:** 1,Nobanion
- **SPELLKNOWN:** CLASS|Cleric=2|Lionheart
- **SPELLKNOWN:** CLASS|Cleric=3|Summon Nature's Ally II
- **SPELLKNOWN:** CLASS|Cleric=4|Shout
- **SPELLKNOWN:** CLASS|Paladin=2|Lionheart
- **SPELLKNOWN:** CLASS|Paladin=3|Summon Nature's Ally II
- **SPELLKNOWN:** CLASS|Paladin=4|Shout

Use wild empathy on felines or part-felines; smite evil 1/day against follower of Malar; add Nobanionite spells to your spell list

You gain wild empathy (as the druid class feature) but only useable on feline or part-feline animals or magical beasts (such as chimeras, dire lions, dire tigers, dragonnes, and manitcores); your effective druid level for this check is the sum of your druid, ranger, cleric, and paladin levels. Once per day you may also make a melee attack with a +4 bonus and with a bonus damage equal to the sum of your cleric, druid, ranger, and paladin levels against a follower or Malar or an item of his church. You must declare the attempt before you strike. Also add 3 spells to your list.

### Initiate of Torm

- **PRECLASS:** 1,Cleric=4,Paladin%=4
- **PREDEITY:** 1,Torm
- **SPELLKNOWN:** CLASS|Cleric=1|Bless Weapon
- **SPELLKNOWN:** CLASS|Cleric=4|Hand of Torm
- **SPELLKNOWN:** CLASS|Paladin=1|Command
- **SPELLKNOWN:** CLASS|Paladin=4|Hand of Torm

You have been initiated into the greatest secrets of Torm's church.

You gain the Smite power. 1/day you may make a melee attack at a +4 bonus and add damage equal to the sum of your cleric and paladin levels. This attack only functions against a follower of Bane or Cyric (or related incarnations). You must declare the attempt before you roll. Add 2 spells to your spell list.

### Initiate of Tymora

- **PRECLASS:** 1,Cleric=4,Ranger%=4
- **PREDEITY:** 1,Tymora
- **SPELLKNOWN:** CLASS|Cleric=1|Fleeting Fortune
- **SPELLKNOWN:** CLASS|Cleric=2|Favor of Tymora
- **SPELLKNOWN:** CLASS|Ranger=1|Fleeting Fortune
- **SPELLKNOWN:** CLASS|Ranger=2|Favor of Tymora

+5 luck bonus on attack roll, saving throw, skill check, or ability check 1/day; add Tymoraite spells to your spell list

You may add a +5 bonus to any single roll you make 1/day as a luck bonus. If you have the Luck domain and use that reroll ability, the bonus carries over to the reroll. Add 2 spells to your list.

### Duerran Metaform Training

- **PRERACE:** 1,Dwarf (Gray%

Spend 5 power points to activate your enlarge person spell-like ability

You can expend 5 power points for an additional activation of your enlarge person ability.

### Duerran Stealth Training

- **PRERACE:** 1,Dwarf (Gray%

Spend 7 power points to activate your invisiblity spell-like ability

You can expend 7 power points for an additional activation of your invisibility ability.

### Air Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can defend yourself with the power of air.

Once per day as a swift action, you can shroud yourself in a mantle of air. This effect grants you a +1 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus to AC. This bonus increases by 1 for every four character levels you possess (maximum +6 at 20th level). In addition, thrown and projectile weapons have an automatic 50%% miss chance against you while the air mantle is active. This protection lasts for 1 minute. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Animal Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You enhance your own abilities with the characteristics of animals.

Once per day as a swift action, you can give yourself the power of a specific animal. Select one of the following abilities each time you activate the feat. Each effect lasts for 1 minute. Ape's Fury: Gain a +2 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus to your Strength score. The value of this bonus increases by 2 for every six character levels you possess (maximum +8 at 18th level). When you activate ape's jury, fur sprouts all over your body and remains until the effect ends. Cheetah's Sprint: Gain a +5-foot sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus to your base land speed. The value of this bonus increases by 5 feet for every four character levels you possess (maximum +30 feet at 20th level). Your body is covered in black spots while cheetah's sprint is active. Hawk's Flight: You can fly as if using the overland flight spell. At 5th level and every five levels thereafter, you gain a +5-foot sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus to your base fly speed (maximum +20 feet at 20th level). Intangible, luminescent wings grow from your back when you activate hawk's flight and remain as long as the effect is active. Serpent's Strike: You gain a natural bite attack that deals 1d3 points of Constitution damage but no hit point damage. A successful Fortitude save (DC 10 + 1/2 your character level + your Cha modifier) negates the Constitution damage. Creatures immune to poison are immune to this effect. Your upper canine teeth grow into fangs when you activate serpent's strike and remain in that form as long as the effect is active. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend. Special: You can have multiple abilities active simultaneously. However, you can still activate only one ability per round.

### Awesome Smite

- **PRETEXT:** Prerequisites: Power Attack, base attack bonus +6, smite ability.
- **PREABILITY:** 1,CATEGORY=FEAT,Power Attack
- **PRETOTALAB:** 6
- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Smite

Through a combination of sheer muscle and mystical acumen, you can deliver devastating smite attacks.

This feat allows the use of three tactical maneuvers, each of which requires that you make a smite attack while using the Power Attack feat (minimum attack penalty -l). You must declare the use of this feat before making the attack roll. You can employ only one of these maneuvers at a time. Demolishing Smite: Your smite attack punches through your enemy's defenses. For the purpose of this single attack, you can ignore a number of points of damage reduction (except DR/- or DR/epic) up to twice your Charisma bonus (if any). For instance, if your Charisma is 17 (+3 bonus), you ignore 6 points of your target's damage reduction when making a demolishing smite. Overwhelming Smite: Your smite attack can knock an opponent prone. If the attack hits and deals damage, it is treated as though it were also a trip attack. Make a Strength check opposed by the defender's Strength or Dexterity, with all the normal trip modifiers (PH 158). A foe that resists is not entitled to make a trip attempt against you in return. You can attempt an overwhelming smite only once per round. Seeking Smite: Your smite attack is uncannily guided to its target. For the purpose of this single attack, you ignore any miss chance your foe might have, though your weapon must still be able to strike the target. Thus, while this maneuver allows you to strike an incorporeal creature unerringly with a magic sword, it does not allow you to strike it with a nonmagical weapon.

### Battle Blessing

- **PRETEXT:** Prerequisites: Ability to cast paladin spells.

You can cast spells more quickly than usual in the heat of battle.

You can cast most of your paladin spells faster than normal. If the spell normally requires a standard action, you can cast it as a swift action. If it normally requires a full round to cast, you can cast it as a standard action. Spells with longer or shorter casting times are not affected by this feat.

### Bestial Charge

- **PRETEXT:** Prerequisite: Base attack bonus +4, wild shape class feature.
- **PRETOTALAB:** 4
- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Wild Shape

You have learned to take complete advantage of the animal forms you can assume.

This feat allows the use of three tactical maneuvers, each of which requires that you attempt a charge attack in the round immediately following your shift into animal form using wild shape. If you have the Swift Wild Shape feat (page 62), you can attempt the charge in the same round as you change forms. Pouncing Charge: You can make a full attack after you charge, as if you had the pounce ability (MM 313). If the animal form you have assumed normally has the pounce ability, your bonus on attack rolls when charging increases to +3. Striking Charge: For the purpose of this charge attack only, you gain an extra 5 feet of reach by suddenly striking forward with your head and neck. You must assume a serpentine animal form to employ this maneuver. Twisting Charge: You can change direction during a charge, as long as you move at least 10 feet both before and after you turn. You must assume an animal form with four or more legs to employ this maneuver. Normal: You can make only a single attack after charging, with a +2 bonus on attack rolls. You can charge only in a straight line.

### Chaos Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

The forces of chaos assist you in combat.

Once per day as a swift action, you can summon the force of chaos to aid you. When you activate this ability, roll 1d6. If the result is odd, add that number as a sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on your attack rolls until your next action. If the result is even, add that number as a sacred or profane bonus to your AC. At the beginning of each action thereafter, roll the die again and apply the designated bonus. This effect lasts for 1 minute. When you attain 10th level, the die you roll increases to a d8. When you attain 15th level, the die increases to a d10. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Charnel Miasma

- **PRETEXT:** Prerequisites: Access to the Death domain.

Your close connection to death magic causes others to find your company unpleasant.

As long as you have a 2nd-level or higher Death domain spell available to cast, you exude an almost imperceptible scent of the grave wherever you go. As a standard action, you can force one foe within 30 feet to attempt a Will save or be shaken for 1 minute. If you use this ability on an already shaken creature and it fails its saving throw, it becomes panicked for 1 minute or until it spends 1 full round out of line of sight of you. Creatures that succeed on this save are not affected again by your charnel miasma for 24 hours. As a secondary benefit, you gain a +1 competence bonus to your caster level when casting death spells.

### Death Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

The power of death imbues your weapon with exceptional might.

Once per day as a swift action, you can cause one of your melee weapons to radiate negative energy for 1 minute. When you make a successful attack with this weapon, the target must succeed on a Fortitude save (DC 10 +1/2 your character level + your Cha modifier) or gain a negative level. You can bestow only one negative level per target for every four character levels you possess (minimum one, maximum five negative levels at 20th level). Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Destruction Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

Your attacks weaken your opponents' defenses.

Once per day as an immediate action, you can call upon the forces of destruction to weaken your opponents' defenses. If you deal damage with a melee attack (but not a melee touch attack) while this ability is active, you temporarily reduce the struck opponent's armor bonus or natural armor bonus by 1. Reductions from multiple hits stack, to a minimum bonus of+0. If the opponent has both armor and natural armor bonuses, it chooses which one to reduce. Once one bonus reaches +0, the other bonus automatically gets reduced until it too reaches +0 or the effect ends. This effect lasts for 1 minute, after which all armor and natural armor bonuses reduced in this way return to normal. Upon reaching 10th level, you reduce your opponent's armor or natural armor bonus by 2 per successful hit. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

### Earth Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can manipulate the earth to your advantage.

Once per day as an immediate action, you can ignore the effects of difficult terrain or make terrain near you more difficult to move through. If you use this ability on yourself, you can ignore the effects of difficult terrain for 1 minute. This ability also grants you a +5 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on Balance, Climb, and Jump checks. If you use this ability to affect nearby terrain, you can change one 5-foot square of earth or stone from normal to difficult terrain for every three character levels you possess (minimum 1 square; maximum 6 squares at 18th level). The first square you change must be within 30 feet of you, and all other squares must be linked to that one in an unbroken line. Thus, the second square must be adjacent to the first, the third must be adjacent to the first or second, and so on. This change lasts for 1 minute. On attaining 10th level, you can cause stone spikes to grow from any surface you have changed to difficult terrain using this ability. These spikes work like caltrops (PH 126), except that the bonus on attack rolls for each spike equals your base attack bonus, and they cannot be swept away. This effect also lasts 1 minute. If you cause spikes to appear underneath a creature on the affected surface, they immediately "attack. " Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

### Elemental Essence

- **PRETEXT:** Prerequisites: Any other wild feat, wild shape class feature.
- **PREABILITY:** 1,CATEGORY=Feat,TYPE.Wild
- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Wild Shape
- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can channel the power of the four elements from the natural world around you.

When you first select this feat, choose one type of energy: acid, cold, electricity, or fire. This choice cannot thereafter be changed. You can spend one daily use of your wild shape ability to surround your limbs and weapons with an aura of the chosen energy. While this effect is active, each melee attack you make deals an extra 1d6 points of the appropriate type of energy damage. Additionally, you gain resistance 5 against that type of energy. These effects last for 1 minute. Special: You can select this feat multiple times. Its effects do not stack. Each time you take it, you must select a different type of energy to which the feat applies. You cannot use this feat to activate multiple energy types at the same time.

### Evil Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

The power of evil cloaks you and your allies.

Once per day as an immediate action, you can surround yourself with an aura of evil that grants you and each of your allies within 30 feet damage reduction that can be overcome only by good-aligned weapons. The numeric value of this damage reduction is 1 + l/five character levels you possess (maximum 5/good at 20th level). In addition, your and your allies' natural and weapon attacks are evil-aligned for the purpose of overcoming damage reduction. This effect lasts for 1 minute. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

### Fire Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can burn your enemies with your melee attacks.

Once per day as a swift action, you can sheathe your body in red and orange flames. The fire does not harm you, but you illuminate the nearby area as a torch would. While you are thus alight, each of your melee attacks deals 1 extra point of fire damage + 1 point for every three character levels you possess (maximum +7 at 18th level). This effect lasts for 1 minute. Any foe injured by this fire ignites and burns for an additional 1d4 points of fire damage per round unless it succeeds on a Reflex save (DC 10 + 1/2 your character level + your Cha modifier). A burning creature can take a move action to automatically douse the flames. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each two daily turn or rebuke uses you expend.

### Fragile Construct

- **PRETEXT:** Prerequisites: Access to the Destruction domain.

Your innate attunement to the forces of entropy allows you to weaken objects with the force of your will.

As long as you have a 3rd-level or higher Destruction domain spell available to cast, you can enhance the inherent flaws of objects. Using this ability requires a touch or a melee touch attack (if used against an opponent). For a number of rounds equal to your caster level, the hardness or damage reduction of the touched object or construct is reduced by an amount equal to the level of the highest-level Destruction domain spell you have available to cast. This ability cannot reduce an object's hardness or damage reduction below 0. As a secondary benefit, you gain a +1 insight bonus on all sunder attempts that you make.

### Good Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

The power of good shields you and your allies.

Once per day as an immediate action, you can surround yourself with an aura of good that grants you and each of your allies within 30 feet damage reduction that can be overcome only by evil-aligned weapons. The numeric value of this damage reduction is 1 + l/five character levels you possess (maximum 5/evil at 20th level). In addition, your and your allies' natural and weapon attacks are good-aligned for the purpose of overcoming damage reduction. This effect lasts for 1 minute. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

### Great And Small

- **PRETEXT:** Prerequisite: Wild shape class feature, ability to assume the form of a Large creature using wild shape.
- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Wild Shape
- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Wild Shape Size Large

By channeling the spirits of all creatures, you can increase or decrease your size without otherwise changing your form.

You can spend one daily use of your wild shape ability to either grow or shrink one size category. You cannot use this feat multiple times to grow or shrink more than one category beyond your normal size, nor does this effect stack with others that change your size. You can activate this feat only while in your normal form. This supernatural ability otherwise functions as the spells enlarge person and reduce person (caster level equals your character level).

### Healing Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can heal damage faster than normal.

Once per day, you can gain fast healing 1, +1 for every five character levels you possess (maximum fast healing 5 at 20th level). This effect lasts for 1 minute. You can activate this feat as an immediate action or, if you have a daily available, it automatically activates if you are reduced to 0 hit points or below (but not killed). Special: As a full-round action, you can transfer this ability to a willing recipient as a touch spell. Doing so counts as one daily use of the ability. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

### Holy Potency

- **PRETEXT:** Prerequisites: Base attack bonus +4, ability to spontaneously cast cure or inflict spells, ability to turn or rebuke undead.
- **PRETOTALAB:** 4
- **PREABILITY:** 1,CATEGORY=Special Ability,TYPE.Turn,TYPE.Rebuke

You have learned to manipulate the energies of the divine to great martial effect.

This feat allows you the use of two of the four following tactical maneuvers. The first two maneuvers are available only if you channel positive energy, while the latter two are available only if you channel negative energy. Balance of Life: The positive energy you channel when healing temporarily bolsters you physically. To use this maneuver, you must first cast a cure spell, then attempt either a melee attack or a Strength-based check in the following round. You gain a bonus on that attack roll or check equal to the level of the cure spell cast. Conduit of Life: Two conduits of positive energy (turning and healing) reinforce each other, making your cure spells more potent. To use this maneuver, you must first attempt to turn undead, then make an attack with a cure spell (or other positive-energy spell) against an undead creature in the following round. You gain a bonus on your damage roll for the spell equal to one-half the result of the initial turning check, and the save DC increases by an amount equal to your Charisma bonus (if any). If you roll a natural 20 on your attack roll when delivering the spell (assuming one is necessary) and the target fails its save, the spell deals double damage. Conduit of Death: Two conduits of negative energy (rebuking and dealing damage) reinforce each other, making your inflict spells more potent. To use this maneuver, you must first attempt to rebuke undead, then make an attack with an inflict spell (or other negative-energy spell) against a living creature in the following round. You gain a bonus on your damage roll for the spell equal to one-half the result of the initial turning check, and the save DC increases by an amount equal to your Charisma bonus (if any), furthermore, the critical threat range of the attack increases by l. Touch of Death: The negative energy you channel lingers, increasing the severity of the wounds you inflict. To use this maneuver, you must first cast an inflict spell, then attempt a melee attack against a living creature in the following round. If the attack hits, it deals extra damage equal to twice the level of the inflict spell cast.

### Holy Warrior

- **PRETEXT:** Prerequisites: Ability to cast 4th-level spells, access to the War domain.

Your zeal on the battlefield allows you to deal extra damage in combat.

As long as you have a 4th-level or higher War domain spell available to cast, you gain a bonus on your weapon damage rolls equal to the level of the highest-level War spell you have available to cast. As a secondary benefit, you gain a +1 competence bonus to your caster level when casting force spells.

### Imbued Healing

- **PRETEXT:** Prerequisites: Ability to cast conjuration (healing) spells; access to one or more domains.

You imbue your healing spells with additional benefits based on the power of your belief.

Whenever you cast a lst-level or higher conjuration (healing) spell, you not only heal your subject of hit point damage, but you also confer on it a carrier effect deriving from a domain to which you have access. If you have access to more than one of the following domains, choose which carrier effect to use each time you use this ability. Each of these carrier effects has a duration of 1 minute per level of the conjuration (healing) spell cast and an equivalent spell level. If you are using domains from publications other than the Player's Handbook, use the Domains from Publications Other Than the Player's Handbook sidebar on page 53 to determine an appropriate domain equivalency. Air: Electricity resistance 5. Animal: Scent ability. Chaos: +2 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on a randomly determined ability score. Death: +4 on saving throws against death effects. Destruction: +2 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on melee damage rolls. Earth: Acid resistance 5. Evil: DR 3/good. Fire: Fire resistance 5. Good: DR 3/evil. Healing: 1 temporary hit point per level or HD. These temporary hit points last for up to 1 hour. Knowledge: +2 insight bonus on skill and ability checks. Law: +4 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on saving throws against mind-affecting spells or spell-like abilities. Luck: When rolling for damage, treat any die roll result of 1 as 2, unless 1 is the maximum result possible. Magic: +2 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on saves against spells and spelllike abilities. Plant: Light fortification (25%% chance to avoid extra damage from critical hits and sneak attacks). Protection: +2 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus to AC when fighting defensively. Strength: +2 on damage rolls with any melee attack. Sun: Low-light vision; +2 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on Spot checks. Travel: +5-foot bonus to base land speed. Trickery: +6 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on Bluff checks. War: +1 on attack rolls with weapons (not natural weapons). Water: +6 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on Swim checks. Special: When you use a conjuration (healing) spell to deal damage to a target, you cannot confer one of these carrier effects on that target. Special: Different carrier effects can affect the same target concurrently, even if the domains are normally opposed in nature (Law/Chaos, Good/Evil, and so forth). Special: If your conjuration (healing) spell affects multiple creatures, you can choose only one carrier effect per casting. All targets are subject to that same effect.

### Knowledge Devotion

- **PRETEXT:** Prerequisite: Knowledge (any) 5 ranks.
- **PRESKILL:** 1,TYPE.Knowledge=5

You can use your knowledge to exploit your foes' weaknesses and overcome their strengths.

Upon selecting this feat, you immediately add one Knowledge skill of your choice to your list of class skills. Thereafter, you treat that skill as a class skill, regardless of which class you are advancing in. Whenever you fight a creature, you can make a Knowledge check based on its type, as described on page 78 of the Player's Handbook, provided that you have at least one rank in the appropriate Knowledge skill. You then receive an insight bonus on attack rolls and damage rolls against that creature type for the remainder of the combat. The amount of the bonus depends on your Knowledge check result, as given on the following table. You can make only one Knowledge check per creature type per combat. If you fight creatures of multiple types during the same combat, you can make one Knowledge check per type, thereby possibly gaining different bonuses against different opponents. This benefit is an extraordinary ability.

### Law Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

The power of law assists you in combat.

Once per day as a swift action, you can summon the power of law to aid you. Upon activating this ability, you immediately gain a +3 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus on your attack rolls or to your AC until your next action. At the beginning of your next action, you can reallocate the bonus if desired. This effect lasts for 1 minute. The bonus increases to +5 when you attain 10th level, and to +7 when you attain 15th level. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Luck Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

Luck makes your attacks more effective.

Once per day as a swift action, you can activate this ability to improve your combat prowess. For 1 minute, if the result of any damage roll you make is below average, you can increase it to one-half the maximum possible (rounded up). This effect works for all damage you deal, whether from physical or magical attacks. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Magic Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You channel your faith into a bolt of energy that strikes your target from afar.

Once per day as a standard action, you can launch an energy bolt as a ranged touch attack against a target within 30 feet, + 5 feet per two character levels you possess. If this attack hits, it deals 1d6 points of damage per two character levels you possess. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each two daily turn or rebuke uses you expend.

### Mitigate Suffering

- **PRETEXT:** Prerequisite: Ability to cast 2nd-level spells.

You can temporarily relieve ability damage.

As long as you have any restoration spell or another conjuration (healing) spell that cures ability damage available to cast, you can confer temporary ability points on yourself or anally. As a standard action, you can create 2 points + 1 point per level of the highest-level such spell you have available to cast. These ability points can be applied to any single damaged ability, raising it to a maximum of its starting score. Temporary ability points granted in this way disappear after 10 minutes, returning the subject to its previous damaged state unless some other effect restores the lost ability points first. You can use this effect on the same individual as many times as you wish. As a secondary benefit, you gain a +1 competence bonus to your caster level when casting conjuration (healing) spells.

### Plant Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

Your body takes on the resilience of plants.

Once per day as an immediate action, you can force your body to take on plant characteristics. Your skin becomes brown and barklike, your hair becomes leafy, and your blood oozes like sap. This effect lasts for 1 minute. While in this form, your natural armor bonus increases by 2. In addition, you gain light fortification (25%% chance to ignore extra damage from critical hits and sneak attacks). The resistance chance granted by this fortification effect increases to 50%% when you attain 10th level and to 75%% when you attain 15th level. At 20th level, you gain heavy fortification (immune to critical hits and sneak attack damage) while in this form. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each two daily turn or rebuke uses you expend.

### Protection Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You exude an aura that protects you and those around you.

Once per day as an immediate action, you can activate a protective aura. While it is active, you gain a +2 sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus to AC, as does every ally within 30 feet of you. This bonus increases by 1 for every four character levels you possess (maximum +7 at 20th level). This effect lasts for 1 minute. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Protective Ward

- **PRETEXT:** Prerequisite: Access to the Protection domain.

Your connection to the divine principle of protection shields you or an ally from attacks.

As long as you have an abjuration spell available to cast, you can use a standard action to provide a sacred (if your deity is good or neutral) or profane (if your deity is evil) bonus to AC equal to the level of the highest-level abjuration spell you have available to cast. You can apply this bonus either to your AC or to that of a single ally within 30 feet, and it persists until the beginning of your next turn. As a secondary benefit, you gain a +1 competence bonus to your caster level when casting abjuration spells.

### Retrieve Spell

- **PRETEXT:** Prerequisite: Any two divine feats, ability to turn or rebuke undead.

You can channel raw divine energy to recharge a previously cast spell.

As a standard action, you can expend turn or rebuke undead attempts to recover a spell you have already cast that day. You must spend a number of daily uses equal to 1 + the level of the spell you wish to recover. You can recover only spells within the class that grants your turn or rebuke undead ability. You cannot, for example, use this ability to regain a previously cast wizard spell.

### Spiritual Counter

- **PRETEXT:** Prerequisite: Any other divine feat, ability to turn or rebuke undead.

Your devotion and faith allow you to counter the effects of other spells.

As a standard (readied) action, you can expend one or more turn or rebuke undead attempts to counter another caster's spell, as though you had cast the same spell yourself (see Counterspells, PH 170). You must spend a number of daily uses equal to 2+ the level of the spell you wish to counter (minimum l) and be able to cast that spell as if it were on your spell list. Normal: You can counter a spell only by casting the same spell, a specific counterspell, or dispel magic.

### Spontaneous Domains

- **PRETEXT:** Prerequisites: Ability to cast 3rd-level spells, access to two or more cleric domains.

You need not prepare your domain spells in advance.

When preparing your spells for the day, you can leave your domain slots open. You can then choose, when the situation arises, to cast any of the domain spells you could normally have prepared for a given level. However, you are still limited to one domain spell per level per day. Normal: Clerics must prepare their domain spells before casting.

### Strength Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can overcome an opponent's normal resistance to damage.

Once per day as a swift action, you can bypass hardness with your melee attacks for 1 minute. In addition, you gain a slam attack as a natural weapon, and all your melee attacks (natural or not) gain the adamantine property for the purpose of overcoming damage reduction. As a natural weapon, your slam attack does not provoke attacks of opportunity. It deals damage based on your size and character level, as given on the following table. If you already have a natural weapon, use whichever damage value is higher. You gain a +2 circumstance bonus on any damage rolls you make with that weapon. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

### Sun Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

Your weapon blazes with the power of the sun.

Once per day as a swift action, you can cause one of your melee weapons to glow with the power of the sun. The illumination radius is the same as that of a torch, but the light is true sunlight and affects creatures within a 10-foot! radius as such. This effect lasts for 1 minute. While your weapon glows, it deals an additional 1 point I of sacred (if your deity is good or neutral) or profane (if your deity is evil) damage per character level you possess to any undead it strikes. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

### Swift Call

- **PRETEXT:** Prerequisite: Special mount class feature.

You can call your special mount in the blink of an eye.

You can call your special mount as a swift action. Normal: Calling a special mount is a full-round action.

### Swift Wild Shape

- **PRETEXT:** Prerequisites: Dex 13, Fast Wild Shape, wild shape I class feature.

You can shift forms in the blink of an eye.

You can activate your wild shape ability as a swift action. Normal: Activating wild shape is a standard action.

### Touch Of Healing

- **PRETEXT:** Prerequisite: Ability to cast 2nd-level spells.

You can channel divine energy into healing with a touch.

As long as you have a conjuration (healing) spell of 2nd level or higher available to cast, you can spend a standard action to touch a target creature and heal 3 points of damage per level of the highest-level conjuration (healing) spell you have available to cast. You can use this ability only on a target that has been reduced to one-half or fewer of its total hit points. The effect ends once you've healed the subject up to half its normal maximum hit points. This ability has no effect on creatures that can't be healed by cure spells. As a secondary benefit, you gain a +1 competence bonus to your caster level when casting conjuration (healing) spells.

### Travel Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can move quickly around the battlefield.

Once per day as a swift action, you can activate this ability to move up to your speed as a swift action each round. Thus, you can move your speed and then take a full-round action, or move and take two other actions (two move actions or one move action and one standard action). This effect lasts for 1 minute. Special: You cannot take a 5-foot step in the same round that you use this feat to move as a swift action. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each two daily turn or rebuke uses you expend.

### Trickery Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You project a simulacrum of yourself that can perform limited tasks.

Once per day as a standard action, you can create an exact duplicate of yourself up to 30 feet away. You can control this simulacrum's movements as a free action. The image becomes more "real" as you advance in level. This ability is usable up to a maximum of 1 minute per level each day. The simulacrum combines the characteristics of the silent image (PH 279) and unseen servant (PH 297) spells. Its hit points are equal to 6 + your character level. It ignores terrain effects and moves like an unseen servant, making no noise in the process, though it makes normal motions while traveling. If you have a fly speed, the image appears to fly when not in contact with the ground; otherwise, it walks on open air. You can do anything with this image that you could do with the unseen servant spell and are under the same limitations. When you attain 5th level, you gain more control over the simulacrum. At this point, it behaves more like a major image spell (PH 252), though it still performs actions like an unseen servant. As long as the simulacrum remains within 5 feet of your position (and you can direct it to do so as a free action), you can perform a Bluff check in combat as a swift action. You gain a +4 bonus on this check, which is opposed by your opponents' Sense Motive checks. If you are successful, your foes believe the image is you (and vice versa) for 1 round. Once you reach 10th level, you can spend a swift action to transfer your perceptions to the simulacrum and perceive the world from its point of view rather than your own. You can move the image as if it were your own body, using the simulacrum's movement characteristics (ignoring terrain, "flying, " and the like). You can also perform any skill and ability checks using the simulacrum, as long as they do not require a Strength score higher than 2. The image has phantom versions of all your equipment (such as lockpicks), but any such items that lose direct contact with it immediately dissipate. When you attain 15th level, the image can become more "real" at your command. It gains a Strength score equal to one-half your own and can perform combat actions using phantom versions of your gear. Any of these items that lose contact with the image dissipate immediately. Thus, the image can wield a sword, but if it shoots a bow, the arrow disappears as soon as it is fired. Equipment that extends more than 5 feet from the image (such as a length of rope) also disappears beyond that distance. In addition, you can now cast spells originating from the image as if with a project image spell (PH 265), with one exception. If you lose line of effect to the image, the effect does not end; you just can't cast spells originating from the image until you gain line of effect again. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Umbral Shroud

- **PRETEXT:** Prerequisites: Ability to cast 3rd-level spells.

You control darkness and shadows.

As long as you have a 3rd-level or higher darkness spell available to cast, shadows and darkness appear to obey your will. As a standard action, you can direct these shadows to obscure the vision of one foe within 30 feet. If your target fails a Will save, its attacks have a miss chance equal to 5%% per level of the highest-level darkness spell you have available to cast. This effect lasts until the beginning of your next action. Creatures that do not rely on sight are unaffected by this effect, and those with Blind-Fight or similar abilities can fight as they normally would. As a secondary benefit, you gain darkvision out to 10 feet. If you already have darkvision, its range increases by 10 feet.

### Venom's Gift

- **PRETEXT:** Prerequisites: Any two wild feats, wild shape class feature, ability to assume plant form using wild shape.

You can imbue your natural attacks with a touch of venom.

As a standard action, you can expend one daily use of your wild shape ability to envenom your natural attacks for up to 1 round per caster level you possess. An ordinary unarmed strike does not qualify for this benefit; you must have a true natural attack, though it can be the result of a transmutation spell or other shapechange effect. Poison: Injury, Fortitude negates (DC 10 +1/2 your HD + your Con modifier), 1d2 Str/ld2 Str.

### War Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can control your abilities more effectively in combat.

Once per day, when fighting defensively as a standard or full-round action, you take a -3 penalty on all attack rolls in a round and gain a +3 dodge bonus to AC in the same round. When you attain 7th level, your penalty on attack rolls drops to -2 and your dodge bonus increases to +4. When you attain 15th level, your penalty on attack rolls drops to -1 and your dodge bonus increases to +5. This bonus stacks with the bonus to AC granted by the Combat Expertise feat. This benefit is an extraordinary ability. Normal: When fighting defensively, you take a -4 penalty on all attacks in a round and gain a +2 dodge bonus to AC for the same round. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each three daily turn or rebuke uses you expend.

### Water Devotion

- **MULT:** YES
- **CHOOSE:** NOCHOICE
- **STACK:** YES

You can create a water guardian.

Once per day as a standard action, you can pour the contents of a full waterskin on the ground and summon forth a water elemental on that spot. The creature remains and follows your commands for 1 minute. The size of the elemental is based on your character level, as given in the table below. Special: You can select this feat multiple times, gaining one additional daily use each time you take it. Special: If you have the ability to turn or rebuke undead, you gain one additional daily use of this feat for each daily turn or rebuke use you expend.

## Spells

### Animate with the Spirit

- **CLASSES:** ALL=4
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Summoning
- **DESCRIPTOR:** Good|Sanctified
- **COMPS:** V,S,DF*
- **CASTTIME:** 10 minutes
- **RANGE:** Medium
- **TARGETAREA:** One corpse with HD equal to or less than your caster level
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Requests a spirit of a good aligned outsider to inhabit a corpse (6 HD max). This then fights for you. Summoning the spirit drains you of 1d3 points of Strength.

### Benign Projection

- **CLASSES:** ALL=6
- **SCHOOL:** Illusion
- **SUBSCHOOL:** Shadow
- **DESCRIPTOR:** Good|Sanctified
- **COMPS:** V,S,DF*
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** One shadow duplicate of you or just your face
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** Will disbelief (if interacted with)
- **SPELLRES:** Yes

You create an image of you that can shed light as a candle. It can only mimic your actions and speech, but you can cast spells with it from the abjuration, divination, and conjuration (healing) schools. Creating it drains you of 1d2 points of Strength.

### Celestial Fortress

- **CLASSES:** ALL=4
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **DESCRIPTOR:** Good|Sanctified
- **COMPS:** V,S,DF*
- **CASTTIME:** 10 minutes
- **RANGE:** Close
- **TARGETAREA:** 20 ft. square structure
- **DURATION:** (CASTERLEVEL*2) hours [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Creates a simple flat-roofed fort with a sturdy door, fireplace, but no windows. It is protected by consecrate and magic circle against evil. Creating it drains you of 1d2 points of Constitution.

### Convert Wand

- **CLASSES:** Cleric=5
- **SCHOOL:** Transmutation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Wand touched
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** None
- **SPELLRES:** No

Temporarily changes any wand into a healing wand with the same number of charges.

### Create Lantern Archon

- **CLASSES:** ALL=3
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **DESCRIPTOR:** Good|Light|Sanctified
- **COMPS:** V,S,DF*
- **CASTTIME:** 1 hour
- **RANGE:** Close
- **TARGETAREA:** One lantern archon
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No

Creates one new lantern archon in service of your patron deity. It will be friendly to you, but not under your control. It will perform 1 nonhazardous task of your choice for up to 1 hour without payment. Creating it will drain you of 1d2 points of Constitution.

### Dawnshroud

- **CLASSES:** Cleric,Druid=5
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Light
- **COMPS:** V,S,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Willing creature touched
- **DURATION:** (CASTERLEVEL*10) minutes [D]
- **SAVEINFO:** Will half; see text
- **SPELLRES:** Yes

Acts as a daylight spell, harms oozes and undead, each round they take 1d6 out to 60 ft or 1 point out to 120 ft. If the target touches a subject creature, they take 1d6+(min(CASTERLEVEL,15)) points of damage.

### Disk of Solar Vengeance

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Fire
- **COMPS:** V,S,DF
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds or until discharged [D]
- **SAVEINFO:** None
- **SPELLRES:** Yes

This spell creates a disk of flame behind your head. It gives you Resistance to Cold 5 and any creature that strikes you without a reach weapon takes 1d6+(MIN(CASTERLEVEL,5)) points of fire damage. This discharages the spell. You can also discharge the spell willingly as a touch attack.

### Dispel Silence

- **SCHOOL:** Abjuration
- **COMPS:** S,DF
- **CASTTIME:** 1 immediate action
- **RANGE:** Medium
- **TARGETAREA:** One silence effect
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No

This spell dispels a silence effect. While you have it prepared, you get a +2 on Listen checks.

### Eilistraee's Moonfire

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Light
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Creature touched
- **DURATION:** 1 minute/level or until discharged
- **SAVEINFO:** None
- **SPELLRES:** Yes

You can use the moonfire as a melee touch attack that deals 2d6 of cold damage +(max(CASTERLEVEL,5)) or use it to spawn a (CASTERLEVEL) minute dancing lights spell.

### Favor of Tymora

- **SCHOOL:** Evocation
- **COMPS:** V,S,F
- **CASTTIME:** 1 immediate action
- **RANGE:** Close
- **TARGETAREA:** One creature
- **DURATION:** (CASTERLEVEL/3) rounds
- **SAVEINFO:** Will negates (h)
- **SPELLRES:** Yes (h)

The target creature gets a +2 luck bonus to AC.

### Faith Healing Wand

- **CLASSES:** Cleric=3
- **SCHOOL:** Transmutation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Wand touched
- **DURATION:** (CASTERLEVEL) minutes
- **SAVEINFO:** None
- **SPELLRES:** No

Temporarily changes any wand into a wand of faith healing with the same number of charges.

### Fleeting Fortune

- **SCHOOL:** Transmutation
- **COMPS:** V,S
- **CASTTIME:** 1 immediate action
- **RANGE:** Close
- **TARGETAREA:** One creature
- **DURATION:** One round or until discharged
- **SAVEINFO:** Yes (h)
- **SPELLRES:** Yes (h)

The target gets a +5 luck bonus on a single skill check of her choice.

### Golden Dragonmail

- **CLASSES:** Sorcerer,Wizard=3
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V,S,F
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** One suit of magic armor
- **DURATION:** (CASTERLEVEL) hours [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Creates a suit of shining golden full plate (treat as +1 mithral full plate for arcane spell failure and AC). If you are a sorcerer, you also benefit from Res to Fire 10.

### Holy Fire Shield

- **CLASSES:** ALL=4
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Good|Sanctified
- **COMPS:** V,S*
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Creatures attacking you take fire or cold damage, with 1/2 being divine energy like the flame strike spell. Casting this gives you 1d3 points of Strength damage.

### Horrible Taste

- **CLASSES:** Druid,Ranger=1
- **SCHOOL:** Evocation
- **COMPS:** V,S
- **CASTTIME:** 1 immediate action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** Fortitude special
- **SPELLRES:** No

Any creature that hits you with a bite attack must succeed on a Fortitude save or become nauseated until you next turn. Creatures immune to poison are unaffected by the spell.

### Invisibility (Swift)

- **CLASSES:** Bard=1|Assassin=2
- **SCHOOL:** Illusion
- **SUBSCHOOL:** Glamer
- **COMPS:** V
- **CASTTIME:** 1 swift action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** 1 round
- **SAVEINFO:** None
- **SPELLRES:** No

You are invisible for 1 round or until you attack.

### Lionheart

- **SCHOOL:** Abjuration
- **DESCRIPTOR:** Mind-Affecting
- **COMPS:** V,S,M
- **CASTTIME:** 1 immediate action
- **RANGE:** Touch
- **TARGETAREA:** ((CASTERLEVEL/4)+1) creatures, no two of which can be more than 30 ft. apart
- **DURATION:** 1 minute
- **SAVEINFO:** Will negates (h)
- **SPELLRES:** Yes (h)

Suppresses fear or gives +4 on saves against fear for (CASTERLEVEL/4+1) subjects.

### Love Bite

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** One creature
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** Yes

You choose either Fleeting Kiss (The target feels a kiss, which is used as a signal) or Love Bite (The target takes 1 pt of damage). This can be used to deliver a held touch spell at range by making the touch attack with a +2 bonus.

### Portal Well

- **CLASSES:** Bard,Cleric,Druid,Sorcerer,Wizard=2
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Active portal touched
- **DURATION:** (CASTERLEVEL) rounds [D]
- **SAVEINFO:** None
- **SPELLRES:** No

You create an extradimensional space in an active portal that you can hide in for the duration by entering the portal.

### Rend Shadow Weave

- **CLASSES:** Cleric,Sorcerer,Wizard=3
- **SCHOOL:** Abjuration
- **COMPS:** V,S,M
- **CASTTIME:** 1 minute
- **RANGE:** Close
- **TARGETAREA:** One 10 ft.-cube area of the Shadow Weave
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No
- **COST:** 50

Creates a zone of dead magic for the Shadow Weave. While you have this spell prepared, you get a +2 competence bonus on caster level checks to dispel Shadow Weave effects.

### Ruinic Marker

- **CLASSES:** Cleric=4
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **DESCRIPTOR:** Earth
- **COMPS:** V,S,M
- **CASTTIME:** 10 minutes
- **RANGE:** Close
- **TARGETAREA:** One stone pillar
- **DURATION:** Permanent
- **SAVEINFO:** See text
- **SPELLRES:** No
- **COST:** 25

You create a slender stone pillar 2 ft in diameter and 6 ft tall in the shape of your choice. You can inscribe up to 25 words on it. It also bears of glyph of warding (blast) that you can set to activate as you desire. When it activates, the marker is destroyed. This spell uses 1 vial of holy water.

### Shard Blessing Aura

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Abjuration
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** None
- **SPELLRES:** No

Aura creates lesser globe of invulnerability. If you are a sorcerer with Selune with you patron you also benefit from Protection from evil.

### Silver Dragonmail

- **CLASSES:** Sorcerer,Wizard=2
- **SCHOOL:** Conjuration
- **SUBSCHOOL:** Creation
- **COMPS:** V,S,F
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** One suit of magic armor
- **DURATION:** (CASTERLEVEL) hours [D]
- **SAVEINFO:** None
- **SPELLRES:** No

Creates a suit of +1 mithral breastplate on you with which you are proficient. Arcane spell failure and armor check penalties still apply. This has no affect if you were already wearing armor. If you are a sorcerer, this also gives you Cold Resistance 5.

### Skin of the Steel Dragon

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Abjuration
- **COMPS:** V,S,M
- **CASTTIME:** 1 immediate action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL)/3 rounds
- **SAVEINFO:** None
- **SPELLRES:** Yes

Grants you spell resistance of (CASTERLEVEL+10). If you are a sorcerer you also gain +5 on saves vs. poison.

### Spellsong

- **SCHOOL:** Transmutation
- **COMPS:** V,S,DF
- **CASTTIME:** 1 round
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No

When you cast this spell you immediately prepare one spell of 4th level or lower in this slot. As with other bard spells this does not work with Silent Spell.

### Spellsong (Lesser)

- **SCHOOL:** Transmutation
- **COMPS:** V,S,DF
- **CASTTIME:** 1 round
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** Instantaneous
- **SAVEINFO:** None
- **SPELLRES:** No

When you cast this spell you immediately prepare one spell of 1st level or lower in this slot. As with other bard spells this does not work with Silent Spell.

### Spiderbind

- **CLASSES:** Cleric=3
- **SCHOOL:** Transmutation
- **COMPS:** V,S,M
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** (CASTERLEVEL/2) spider or spiderlike creatures, no two of which can be more than 30 ft. apart
- **DURATION:** (CASTERLEVEL) rounds
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes

Affected creatures are affected as a slow spell, reduced to one move or attack action during the round. Additionally, they take a -1 penalty on attack rolls, AC, and Reflex saves. They move at half their normal speed rounded down. Their poison attacks don't work for the duration. While the spell is prepared, you get a +2 circumstance save bonus against poison.

### Stars of Arvandor

- **CLASSES:** Sorcerer,Wizard=3|Cleric,Druid,Ranger=4
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force|Good
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** (min(CASTERLEVEL,10)) stars
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** Yes

Create (min(CASTERLEVEL,10)) stars that orbit your head like ioun stones. As a swift action you can launch 1 star as a RTA to deal 1d8 nonlethal damage against non-evil targets or lethal damage against evil targets. As a standard action you can launch 3, though you must make a separate attack for each star.

### Stars of Mystra

- **CLASSES:** Cleric=4
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Force|Good
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** (min(CASTERLEVEL/3,5)) stars
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes

Create (min(CASTERLEVEL/3,5)) stars that orbit your head like ioun stones. As a swift action you can launch 1 star at a target as a RTA. Each evil creature struck must make a save or lose a prepared spell or spell slot of level 4 or the highest lower level slot available determined randomly.

### Stars of Selune

- **CLASSES:** Cleric=4
- **SCHOOL:** Evocation
- **DESCRIPTOR:** Cold|Force
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Close
- **TARGETAREA:** (min(CASTERLEVEL/3,5)) stars
- **DURATION:** (CASTERLEVEL) minutes [D]
- **SAVEINFO:** None
- **SPELLRES:** Yes

Create (min(CASTERLEVEL/3,5)) stars that orbit your head like ioun stones. As a swift action you can launch 1 star at a target as a RTA. Each star deals 1d8 of force and 1d8 of cold damage to the target.

### Stormvoice

- **SCHOOL:** Evocation
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Personal
- **TARGETAREA:** You
- **DURATION:** (CASTERLEVEL) minutes or until discharged [D]
- **SAVEINFO:** None
- **SPELLRES:** Yes

You voice is amplified. Subtract 10 from the DC of Listen checks made to hear you. You also gain a +2 competence bonus on Intimidate. While the spell is active, you can make a swift action to create a 15-foot-long cone-shaped burst with a shout. Targets take 1d8 points of sonic damage and make a Fortitude save or be stunned for 1 round. Doing so discharges the spell. Creatures that cannot hear are not stunned but still take the damage.

### Thunderstroke

- **SCHOOL:** Evocation
- **DESCRIPTOR:** Electricity
- **COMPS:** V,S
- **CASTTIME:** 1 standard action
- **RANGE:** Medium
- **TARGETAREA:** One creature or object
- **DURATION:** Instantaneous
- **SAVEINFO:** Reflex half
- **SPELLRES:** Yes

You call down a bolt of electricity that unerringly strikes your target dealing (min(CASTERLEVEL,5))d6. A small rumble of thunder accompanies the bolt, which is as loud as a battle (LISTEND DC -10 to hear).

### Vision of Punishment

- **CLASSES:** ALL=1
- **SCHOOL:** Divination
- **DESCRIPTOR:** Mind-Affecting|Good|Sanctified
- **COMPS:** V,DF*
- **CASTTIME:** 1 swift action
- **RANGE:** Close
- **TARGETAREA:** One evil living creatures
- **DURATION:** (CASTERLEVEL/3) rounds
- **SAVEINFO:** Will partial
- **SPELLRES:** Yes

You give a target a vision of what awaits it in the afterlife. For most evil creatures this is a gut-wrenching vision. The target is nauseated if it fails its save, otherwise, it is sickened. The caster takes 1d2 points of Strength damage.


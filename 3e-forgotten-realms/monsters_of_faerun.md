# Monsters of Faerun

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Abilities

### CATEGORY=Internal|Dwarf ~ Hill.COPY=Dwarf ~ Shield


### Attack Bonus

- **DEFINE:** DwarfRacialCombatBonus|0
- **BONUS:** VAR|DwarfRacialCombatBonus|1
- **ASPECT:** CombatBonus|+%1 racial bonus on attack rolls against orcs and goblinoids|DwarfRacialCombatBonus

+%1 racial bonus on attack rolls against aberrations|DwarfRacialCombatBonus

### Gold

- **BONUS:** STAT|CHA|2
- **BONUS:** STAT|DEX|-2
- **TEMPLATE:** Hill Dwarf
- **ABILITY:** Internal|AUTOMATIC|Favored Class ~ Fighter
- **COST:** 0
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Darkvision|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfRacialVision
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Weapon Familiarity|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfWeaponFamiliarity
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stonecunning|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfStonecunning
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Stability|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfStability
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Poison Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfPoisonSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Spell Save Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfSpellSaveBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Gold Dwarf ~ Attack Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfAttackBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Dodge Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfDodgeBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Appraise Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfAppraiseBonus
- **ABILITY:** Dwarf Race Trait|AUTOMATIC|Dwarf ~ Craft Bonus|!PREABILITY:1,CATEGORY=Special Ability,TYPE.DwarfCraftBonus
- **ABILITY:** Internal|AUTOMATIC|Language ~ Auto (Dwarf)|!PREABILITY:1,CATEGORY=Internal,TYPE.AutoLangReplace
- **ABILITY:** Internal|AUTOMATIC|Language ~ Bonus (Dwarf)|!PREABILITY:1,CATEGORY=Internal,TYPE.BonusLangReplace
- **BONUS:** STAT|CON|2|TYPE=Racial
- **BONUS:** STAT|CHA|-2|TYPE=Racial

### CATEGORY=Internal|Dwarf ~ Hill.COPY=Dwarf ~ Urdunnir


### Summon Large Air Elemental


### Drown


The first victim hit by an aballin's pseudopods must make an opposed grapple check with the aballin (whose check is +11). If the Aballin's wins, it begins drowning the victim. The aballin is acid, so Water Breathing, and similar effects are useless. Trapped victims can attack the aballin or make grapple checks to escape. Slashing and piercing attacks do not affect the aballin, but have a 25%% chance to affect the victim. While grappling, the aballin continues attacking others with its pseudopods.

### Passive State


In its passive state the aballin cannot be harmed by any attack that would not affect a normal pool of water.

### Vulnerability to Water Affecting Spells


### Abishai Qualities

- **ABILITY:** Special Ability|AUTOMATIC|Abishai ~ Summon Baatezu|Abishai ~ Regeneration|Abishai ~ See In Darkness|Abishai ~ Telepathy|Abishai ~ Vulnerability to Holy Water|Abishai ~ Immunity to Fire|Abishai ~ Immunity to Poison

### Summon Baatezu


Summon 2d6 lemures with a 50%% success rate or an abishai of a random color with a 20%% success rate.

### Regeneration

- **ABILITY:** Special Ability|VIRTUAL|RegenerationChoice (Holy)
- **ASPECT:** NAME|Regeneration %1|RegenerationRate
- **DEFINE:** RegenerationRate|0
- **BONUS:** VAR|RegenerationRate|HD

Holy water, Holy weapons and Blessed weapons do normal damage to abishai.

### See In Darkness


See perfectly in darkness of any kind, even a Deeper Darkness.

### Telepathy

- **ABILITY:** Special Ability|VIRTUAL|Telepathy
- **DEFINE:** TelepathyRange|0
- **BONUS:** VAR|TelepathyRange|100

Communicate with any creatyre within %1' that has language.|TelepathyRange

### Vulnerability to Holy Water


take 2d4 damage from a flask, or 1 damage from a splash.

### Immunity to Slashing Weapons


### Immunity to Piercing Weapons


### Imunity to Fire

- **ABILITY:** Special Ability|VIRTUAL|Immunity to Fire

### Imunity to Poison

- **ABILITY:** Special Ability|VIRTUAL|Immunity to Poison

### Immunity to Enchantment

- **ABILITY:** Special Ability|VIRTUAL|Immunity to Enchantment

### Poison Tail


Victims hit by your tail slap must save Foritude(15) or be poisoned. Onset time is 1 minute, damge is 2d6 damage, secondary is 1d4 temporary constitution damage. Those who fail the Fortitude save must save Will(15) or suffer a Confusion effect for the next two rounds.

### Dexterity Damage


In addition to normal claw damage, deal 1 Dex damage on an successful hit.

### Spells

- **SPELLS:** Innate|TIMES=1|TIMEUNIT=3 rounds|CASTERLEVEL=4|Magic Missile,11+CHA
- **SPELLS:** Innate|TIMES=1|TIMEUNIT=10 minutes|CASTERLEVEL=4|Blink,11+CHA

### Immunities

- **ABILITY:** Special Ability|VIRTUAL|Immunity to Cold

Immune to cold, half damage from slashing and piercing weapons.

### See Invisible


See invisible creatures and objects.

### Fast Healing

- **ABILITY:** Special Ability|VIRTUAL|Fast Healing
- **ASPECT:** NAME|Fast Healing %1|FastHealingRate
- **DEFINE:** FastHealingRate|0
- **BONUS:** VAR|FastHealingRate|2

### Immunity to Acid

- **ABILITY:** Special Ability|VIRTUAL|Immunity to Acid

### Immunity to Poison

- **ABILITY:** Special Ability|VIRTUAL|Immunity to Poison

### Poison

- **ABILITY:** Special Ability|VIRTUAL|Poison

Victims of Bite or Tail attack save Foritude (18) or be injected. Initial, 2d4 points of temporary Constitution damage, secondary 1d3 Hours of unconsciousness.

### Resistance to Petrificaiton


+3 on saves versus petrification.

### Magic Item Use


Can use your tentacles to freely use amulets, rings, rods, wands, potions, and other similar small magic items.

### Paralysis


Bite victims are paralyzed for 1d6+2 minutes unless they save Fortitude(14).

### See Invisibility


Within 60'

### Weapon Immunities


1/2 damage from slashing and piercing weapons.

### Frightful Presence

- **ABILITY:** Special Ability|VIRTUAL|Frightful Presence
- **DEFINE:** FrightfulPresenceRange|0
- **DEFINE:** FrightfulPresenceDC|0
- **BONUS:** VAR|FrightfulPresenceRange|0
- **BONUS:** VAR|FrightfulPresenceDC|10+CON

### Hold Person

- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=TL|Hold Monster,14+CHA

### Missile Deflection

- **BONUS:** COMBAT|AC|4|TYPE=Deflection

Stops missile attacks, turning away physical ones and absorbing magical ones like Acid Arrow and Magic MIssile. Also adds+4 AC (Deflection)

### Skills

- **BONUS:** Skill|Hide,Jump,Move Silently|8|TYPE=Racial
- **BONUS:** Skill|Listen,Spot|4|TYPE=Racial
- **BONUS:** Skill|Balance|12|TYPE=Racial

Gain an additional +4 to Hide and Move Silently in tall grass or heavy undergrowth.

### Eye Gouge

- **ABILITY:** FEAT|AUTOMATIC|Improved Critical (Tongue)

Beholders/beholderkin whose eyes have special abilities who are struck with a tonge save Reflex (18) or have an eye disabled for 2d6 rounds (or permanently on a roll of 12). There is a 50%% chance it is the central eye, otherwise choose randomly. If the same eye is struck multiple times, the duration is cumulative.

### Air Walk


As the spell, continuous.

### Feather Fall

- **ABILITY:** Spell-Like Ability|VIRTUAL|Feather Fall

A Helmed Horror's Air Walk ability allows it to Feather Fall at will.

### Immunity to Magic Missile


### Spell Immunities

- **MULT:** YES
- **CHOOSE:** NUMCHOICES=1|SPELLS|ALL

### Absorb Energy


Take no damage from fire or lightning, being healed by as much damage would be dealt. At above 60 HP, split into 2 30 HP Nyths, striking all living creatures within 30' with 1d3 magic missiles each.

### Immunity to Charm Effects

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Charm Effects

### Immunity to Compulsion Effects


### Immunity to Morale Effects


You are never subject to morale effects or modifiers.

### Immunity to Phantasms

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Phantasms

### Invisibility


Can become invisible for 2d4 rounds, if you fire a magic missile you are visible and glow brightly until your next action.

### Reflect Magic Missile


Magic Missiles aimed at you are reflected at the caster.

### Silence


Make no sound unless speaking. Cannot be heard with a Listen check unless they want to be.

### Absorb Magic


Damaging spells permanently grant 1 point per damage they would have dealt. Fire and cold spells do damage (reduced for cold) but dissipate after 1 round. Nondamaging spells grant 1 HP per spell level. Contact with a magic item drains 1d4 charges on contact, and 1d4 each round thereafter. Non-charged items have their functions negated for the duration of contact and 1d4 rounds thereafter. If a character enveloped in a Nishruu tries to use a potion or scroll, it does not take effect until 1d4 rounds after they leave it. Artifacts do not operate while in contact with a Nishruu and for 1 round thereafter. Arcane and Divine casters lose 1 random prepared spell when in contact with a Nishruu, and one per turn thereafter - each spell lost requires a Will(15) save or be Feebleminded.

### Charge Magic


When dying, any charged item in contact with the mist gains 1d6 charges, and any magic weapon that strikes the killing blow gains the Spell Storing quality fo 1d6 days.

### Gaseous Form

- **DR:** 20/+1

Can drift against the wind, fit through small openings...

### Vulnerabilities


A Rod of Absorbtion or Ring of Spell Turning has a 5%% chance of destroying a Nishruu on contact (with no ill effects other than turning the item red). If they do not destroy the Nishruu, they are negated like any other item. Thrown salt deals 2d10 damage to you. (Ranged touch, Range increment 5, max range 10)

### All-Around Vision

- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** SKILL|Search|8|TYPE=Racial

Cannot be flanked, cannot be sneak attacked once it has acted in an encounter.

### Flight

- **ABILITY:** Special Ability|AUTOMATIC|Flight

### Immunity to Charm

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Charm Effects

### Immunity to Command


### Alternate Form


Pterafolk can assume the form of a Pteranadon.

### Alternate Form (Snake Form)


%1/day, assume legless form. Lose all Claw attacks, but gain a Constrict attack (Small=1d8,Med=2d6, Large=2d8, Huge=3d6, Gargantuan=3d8, Collossal=5d6). If you hit with this attack, you may make a free grapple attempt. If you grapple, you may deal contstrict damage every turn until the victim escapes.|SnakeFormTimes

### Alternate Form (Humanoid Form)


%1

### Weapon Power

- **BONUS:** ABILITYPOOL|Helmed Horror Weapon Power|1

### Weapon Power (None)


No Weapon Power

### Weapon Power (Flaming)


Apply the selected trait to any weapon you wield.

### Weapon Power (Flaming Burst)


Apply the selected trait to any weapon you wield.

### Weapon Power (Frost)


Apply the selected trait to any weapon you wield.

### Weapon Power (Keen)


Apply the selected trait to any weapon you wield.

### Weapon Power (Shock)


Apply the selected trait to any weapon you wield.

### Weapon Power (Shocking Burst)


Apply the selected trait to any weapon you wield.

### Weapon Power (Speed)


Apply the selected trait to any weapon you wield.

### Weapon Power (Thundering)


Apply the selected trait to any weapon you wield.

### Weapon Power (Wounding)


Apply the selected trait to any weapon you wield.

### Immunity to Hold Effects


You are immune to Hold effects.

### Alternate Form (Humanoid)


Assume the form of a Medium humanoid %1 times per day.|HumanoidFormTimes

### Alternate Form (Snake)


Lose claws but gain Constrct %1 times per day.|SnakeFormTimes

### Archetypal Shape


Others cannot magically assume the shape of a Sharn.

### Arrow Evasion


Arrows and Crossbow bolts, and other normal or non-extraordinary missiles have a 20%% miss chance against a Tall Mouther.

### Blood Drain


On Tentacle hit, victims must make a Fortitude Check (DC 18) or take 1d3 temporary Constitution damage, restoring 1d6 HP to the Death Kiss similar to the Fast Healing ability.

### Stinger


Can move 20' straight up or down so long as it passes through at least a foot of earth. For every 5' or fraction thereof, it takes 1d3 damage. If its movement would stop inside a solid object, it takes the full damage, but does not move.

### Bone Bite


On a critical hit, bite does X3 damage and either Armor or Shield (chosen randomly of the victim has both) must save (DC 16) or be torn into pieces.

### True Seeing


As the spell.

### Web


8/Day Choldriths may cast a web (as a net attack, but with a maximum range of 50' and a 10' range increment). The web anchors the target in place, allowing no movement.

### Nauseating Stench


Any corporeal being with 8 or fewer HD coming within 80' of a Gulguthydra must save Foritude (23) or be nauseated for 1d10 rounds. At the end of that time if they are still in range they myst make the same save again. A single successfule save renders them immune for 1 day. Nauseated characters are unable to attack, cast spells, concentrate on spells, or do anything requiring attention.

### Immunity to Gaze


You are immune to gaze attacks.

### Sacrifice Eyestalk


You have sacrificed %1 Eyestalks to cast spells.|SacrificedStalks

### Sacrificed Eyestalk

- **MULT:** YES
- **CHOOSE:** STRING|Charm Monster|Charm Person|Disintegrate|Fear|Finger of Death|Flesh To Stone|Inflict Moderate Wounds|Sleep|Slow|Telekinesis

You have sacrificed your %1 Eyestalk to cast spells.|%CHOOSE

### Breath Weapon


1/minute breathe a 10' wide, 10' tall, 30' long cloud of gas. Those within must save (reflex/21) or take 1d6 temporary Strength damage.

### Roar


1/day roar, those within 30' save Fortitude(13) or be stunnded for 1d4 rounds by the sonic attack. Those within 10' must save (fortitude/13) or be deafened for 2d10 minutes.

### Tanarukk Racial Trait Default

- **ABILITY:** Special Ability|AUTOMATIC|Tanarukk ~ Control Flames

### Control Flames


2/day a Tanarukk may diminish a flame to coals, or flare it to the brightness of daylight. This does not affect fuel consumption and lasts 5 minutes.

### Fey'ri Racial Trait Default

- **BONUS:** ABILITYPOOL|Fey'Ri Demonic Ability|4
- **ABILITY:** Special Ability|AUTOMATIC|Elf ~ Racial Immunity|Fey'ri ~ Alternate Form

### Charm Person

- **SPELLS:** INNATE|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=max(1,TL)|Charm Person,11+CHA

### Clairaudience/Clairvoyance

- **SPELLS:** INNATE|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=max(1,TL)|Clairaudience/Clairvoyance,11+CHA

### Damage Reduction 10/+1

- **DR:** 10/+1

### Darkness

- **SPELLS:** INNATE|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=max(1,TL)|Darkness,11+CHA

### Detect Thoughts

- **SPELLS:** INNATE|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=max(1,TL)|Detect Thoughts,12+CHA

### Dimension Door

- **SPELLS:** INNATE|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=max(1,TL)|Dimension Door

### Enervation

- **SPELLS:** INNATE|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=max(1,TL)|Enervation,14+CHA

### Suggestion

- **SPELLS:** INNATE|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=max(1,TL)|Suggestion,12+CHA

### Fire Resistance 10

- **ABILITY:** Special Ability|AUTOMATIC|Resistance To Fire ~ Tiefling
- **BONUS:** VAR|FireResistanceBonus|5|Racial.STACK

### +2 Racial Bonus on saves versus electricity


### +2 Racial Bonus on saves versus poison


### Waterwalking


Make a Dex(10) check to walk on the surface of water. Failure means losing your footing (bobbing on the surface of the water, but otherwise acting normally). Recovering your waterwalking footing is a Full Round action.

### Detect Magic

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=TL|Detect Magic

### Immunity to Illusions


Immune to sight-based illusions.

### Spike Stones

- **SPELLS:** Innate|TIMES=3|TIMEUNIT=day|CASTERLEVEL=5|Spike Stones,15+CHA

### Stone Shape

- **SPELLS:** Innate|TIMES=3|TIMEUNIT=day|CASTERLEVEL=5|Stone Shape,15+CHA

### Vulnerability to Silence


Silenced Tomb Tappers lose their blindsight and are effectively treated as Blind due to the loss of their sonar.

### Vulnerability to Ki


Can be struck and damaged by any character who possesses the Ki Strike ability (bypasing DR) and deals +1d6 damage for each point of Ki Strike they possess.

### Paralyzing Glare


First time your confront your killer, they must make a Will(%1) or be paralyzed for 2d4 rounds.|10+TL/2

### Vengeful Strike


Melee attacks against your killer do +1d10 damage.

### Find the Guilty


So long as you are on the same plane as your killer, know their direction and distance. Given certain magical abilities, this may extend across planar boundaries.

### Immunity to Cold

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold

### Immunity to Electricity

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Electricity

### Immunity to Gas


### Immunity to Mind-Affecting

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Mind-Affecting

### Immunity to Polymorph

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Polymorph

### Immunity to Turning


You are immune to Turning and Command Undead effects.

### Training


Will only allow themselves to be ridden by human or drow females of evil alignment.

### Gibber


Creatures with fewer than 2HD who can hear you, roll Will(10) or be shaken. Even those with 2+ HD suffer -2 on Concentration checks.

### Teamwork


For each Gibberling grappling a foe, all get a +2 Competence bonus vs that foe.

### Bunching


Up to3 Gibberlings can occupy a 5' space.

### Sunbeam

- **SPELLS:** Innate|TIMES=1d3|TIMEUNIT=Day|CASTERLEVEL=15|Sunbeam,15+CHA

### Targeted Dispel


Any creature struck in melee by a Diamond Golem is the subject of a Targeted Dispel Magic as if cast by a 16th level wizard.

### True Strike

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=15|True Strike,11+CHA

### Summoning


Bullywug clerics casting Summon Monster spells have a 50%% chance of summoning one more monster than the spell indicates, and a 25%% chance of their summoned monsters rampaging out of control, attacking randomly.

### Summon Air Elemental

- **ABILITY:** Special Ability|AUTOMATIC|Brown Dragon ~ Summon Air Elemental ~ Huge
- **ABILITY:** Special Ability|AUTOMATIC|Brown Dragon ~ Summon Air Elemental ~ Greater
- **DEFINE:** SummonAirELementalType|0

### Sting


+1d6 Cold Damage

### Spellray


Use your eye rays to deliver touch spells for your master. Your master casts the spell on you, on your next action, you must target something with the spell as a ranged touch attack. If you do not, the spell is lost.

### Spell Imprinting


When Darkenbeasts are created, the creator can cast a spell and imprint it on them. They may choose to cast a spell imprinted on a Darkenbeast withing 30' as if casting normally. This destroys the darkenbeast, and the spell has a 25%% chance of failure + 10%% for each Darkenbeast imprinted spell attempted that day.

### Spectral Form


3/day, for 10 min at a time, become Incorporeal (losing the Natural Armorm bonus of +5, but gaining a %1 deflection bonus)|CHA

### Spawn


Take 1d4 days to grow a spawn which is similar (class, abilities, etc) to a corporeal native living creature of the Material Plane. I is sufficiently loyal that it cannot even be made to attack you by magical means.

### Smite The Fallen


Do double damage against prone opponents.

### Sleep Arrows


There is a 10%% chance a Hybsil has 1d3 sleep arrows from pixies. They will only be used in life or death situations, and any creature struck by one must make a Fortitude Save (difficulty 15) or be affected as by the Sleep spell.

### Hold Monster

- **SPELLS:** Innate|TIMES=1|TIMEUNIT=Day|CASTERLEVEL=HD|Hold Monster,14+CHA

### Silver Vulnerability


Silver weapons do maximum damage against Malaugrym, and it cannot be healed naturally (including via the Malaugrym's Fast Healing ability).

### Sickening Cloud


A creature who comes within 5' of a Tyrantfog Zombie must make a Foritude (13) save, or take 1 point of temporary constitution damage. Only one save per encounter is required.

### Plane Shift


Plane Shift to and from the Plane of Shadow at will. 1/day take up to 7 cloakers with you.

### Shadow Shift

- **ABILITY:** Special Ability|AUTOMATIC|Shadow Shift ~ Obscure Vision|Shadow Shift ~ Dancing Images|Shadow Shift ~ Silent Image

Shadow Shift abilities are only effective in shadowy lighting.

### Shadow Shift (Obscure Vision)


Gain 1/4 concealment for 1d4 rounds.

### Shadow Shift (Dancing Image)

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=9|Mirror Image,12+CHA

Duplicate the effects of a Mirror Image spell cast by a 9th level Sorcerer.

### Shadow Shift (Silent Image)

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=9|Silent Image,11+CHA

As the spell, cast by a 9th level sorcerer.

### Shadow Learning Bonus

- **ASPECT:** SkillBonus|+2 bonus to Spellcraft when learning Shadow

### Sandstorm


1/day create a violent vortex up to 80 yards (240') away, all creatures within a 60' radius of the center take 1d6 damage each round they are in the radius. Characters within the swirling sand are blinded and must make a Balance(15) check if they move more than 5' or fall prone.

### Rock Throwing


Throw rocks of 40-50 lb (or other Small objects) up to 5 range increments of 140'. +1 racial bonus to attack when throwing rocks.

### Rock Catching


Catch Small, Medium or Large Projectiles. 1/round, when you would normally be hit by one, make a Reflex save (15 for Small, 20 for Medium, 25 for Large). You must be ready for and aware of the attack.

### Resistance to Magic


+2 bonus to all saves versus magical Effects.

### Polymorph Rend


Touch a target under the effects of Polymorph, Shapechange, or similar (cast by someone other than you) and deal 6d6 damage.

### Pin


Jump and land a Medium or smaller creature (or creatures, in a 10'x30' area) who must make a Reflex(21) save or be pinned. You may choose whether or not to do damage. Creatures that lie still take no damage (treat as a grapple attack) while those that struggle take 4d6 damage per round until they escape.

### Moan

- **ABILITY:** Special Ability|AUTOMATIC|Cloaker Lord ~ Moan (Unnerve)|Cloaker Lord ~ Moan (Fear)|Cloaker Lord ~ Moan (Nausea)|Cloaker Lord ~ Moan (Stupor)

One moan effect per round.

### Moan (Unnerve)


All within 90' suffer -2 morale penalty, to attack and damage rolls. Thos who hear for 6 consecutive turns must make a will save (DC 16) or enter a trance and be unable to attack or defend themselves until the moaning stops.

### Moan (Fear)


All within 40' Must make a Will save (DC 16) or flee for 2 rounds.

### Moan (Stupor)


A single individual no more than 50' away must save Fortitude(16) or be affected by Hold Monster. A Cloaker Lord can only affect one creature this way at a time. Affecting a new one releases the previous.

### Moan (Nausea)


Everyone within 40' must save Fortitude(16) or be Nauseated, and unable to attack or defend themselves for 1d4+1 rounds

### Infective Touch


Victims of your Claw attacks must save (Fortitude/13) at the end of the battle. If they fail, they sicken (Incubation is 1d4 days, taking 1 point of temporary Strength damage at that time, and make a new save each day thereafter. Each failed save costs them 1d2 Constitution and 1d4 Strength, and then Save again or suffer a permanent point each of Strenght and Constitution drain).

### Mimicry


You are adept a mimicing noises and voices.

### Marsh Move


Suffer no movement penalties from Marsh or mud.

### Magic Missile


Every other round fire a single Magic Missile at a target within 110' dealing 1d4+1 damage.

### Levitate


Levitate with vertical speed of 20', and Feather Fall at will.

### Independent Action

- **ABILITY:** FEAT|AUTOMATIC|Multiweapon Fighting

### Impalement


Jump into the air and land on an opponent. Make a single (+5 melee) attack. If you fall at least 20' for this attack, and +1 damage per leg that strikes. Small or smaller creatures are hit by 3 legs, medium creatures get 4, 5 for large, 6 for huge, and gargantuan or larger get all 8.

### Immunity to Web


Cannot be caught in a spider's web or Web spell

### Hit Point Drain


Your bite has a 1 in 6 chance of permanentl draining a hit point from your victim and permanently transferring it to you. This is as part of the normal bite damage, not in addition to it.

### Hide in Fog


+4 to hide in light fg, +7 to hide in heavy fog (including size penalty).

### Sharn


Summon and maintain up to 3 portals. You can see, attack, and cast spells through them. Can form up to 3 within 20' as a full round action, move 20' as a free action before you take your regular action, they do not block movement or line-of-sight/effect, and creatures can occupy the same space as the portal with no ill effects other than being in range of a Sharn. Banish as a free action. Max range 100', movement beyond which causes them to disappear. Casting or attackiing through a portal requires reaching throug - an oponent with a readied action can attack or cast on you in that moment (.but you have 9/10 cover:+10 AC, +4 reflex). Your reach from a portal is only 5'. Others cannot travel, attach or cast through the portal except as previously noted. Hex portals can flank/threaten. Can be dispelled, or eliminated by Antimagic Zone, and cannot be made invisible.

### Heart Rip


Deceased victims who is Coup Degraced by a Peryton has its heart ripped out. They may not be returned to life via Raise Dead, though True Resurrection and similar effects still function.

### Healing from Fire


Immune to fire/heat damage. 3 rounds in which you are exposed to intense heat or flame heals you as Cure Light Wounds (1d8+1 damage healed). A Fireball or other intense fiery attack heals you fully and instantly.

### Fixed Shape


You may not be affected by Polymorh, Shapechange, or similar effects.

### Fireball


2/hour, launch a ball of fire up to 60'. It has a burst radius of 10'. Deals 1d6 damage. Reflex(14) negates.

### Feed


Eat a fallen foe (which can be delayed up to %1 days), each 8 HD comsumed grants you an HD increase of 1. This destroys the victim's body, and prevents any retrieval short of a Wish, Miracle, or True Resurrectin, and even these have a 50%% of failure.|HD

### Fear Aura


Characters within 30' must save Will(13) each minute or become Shaken (-2 on attacks, checks, saves).

### Eye Rays


Use one of your four rays per round - and if you use Daze or Ray of frost, you cannot use Daze or Ray of Frost again for 2 rounds. They are Cause Fear (range 35', save DC 10), Daze (range 35', DC 10), Mage Hand (as a 4th Level caster, range 35', you do not have to use a Move Equivalent action to move a single item weighing 5 or less lb no more than 15' per round), Ray of Frost (Range 35')

### Engulf


Wrap a Large or smaller opponent in your body. Make a grapple attack that does not provoke an Attack of Opportunity. If you achieve your hold, you can use tail against other targets. You may bite the victim at a +4 bonus. Attacks against you deal half their damage to the engulfed victim.

### Emerald Gates


1d2/day as a standard action, create a gate that lasts 1d6 rounds. On a 6, it lasts 1d6 hours. Functions as a Teleportation Circle, but the destination is random (to anywhere any other Emerald Golem has been). They tend not to lead into volcanos, or 300' in the air, but are not guaranteed to be hospitable.

### Death Shiver


At death, all within 1d10*5' roll Reflex(15) or suffer 2d10 Electrical damage.

### Electric Aura


1%% chance per damage dealt by Slashing or Pierching weapons to shock the attacker for 1d10 damage (electric). Reflex(15) negates. If the blow reduces you to 0 or fewer HP, the chance increases to 5%% per damage dealt.

### Dominate Cloakers


Cloaker lords are the unqestioned rulers of cloaker communities.

### Distraction


Not listed in my copy of MONF

### Disarm


Forego all attacks in a round to mould yourself around an opponent's weapon. When a weapon successfully hits you, it sinks in, requiring a Strength(20) check to free.

### Cover


Usually in a pile of treasure and detritus granting 1/2 cover (+4 AC, +2 Reflex).

### Water Breathing

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=14|Water Breathing,12+CHA

### Heal


Casterlevel 14, self only.

### Change Shape


Assume the form of any Small or Medium humanoid.

### Consume Identity


If you eat the brain of a Medium or smaller humanoid, you consume their identity and memories. You mimic them with 100%% accuracy, and retain their memories, abilities, and alignment (except for Cleric spells 2nd level or higher and Paladin special abilities, or other powers granted by a specific deity). When you consume 3 or more, roll will (16) to avoid losing one at random. You may not hold more than you have HD, and lose a random one each time you gain a new one at that point. If you violate their alignment while wearing them, you are forced into your base form for 1d10 rounds. In your base form, your retain basic recollections of the identities, but not deeper memories. Memories from lost identities fade quickly.

### Constrict


Free grapple attempt on a successful tentacle attack, without provoking an attack of opportunity. If you win, deal 1d4+4 damage to the victim each round until they break the hold.

### Charming Gaze


In humanoid form those who meet your gaze save Will(15) or treat your Charisma as 2d4 points higher.

## Abilitycategory

### ABILITYCATEGORY:Helmed Horror Weapon Power

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Helmed Horror Weapon Powers
- **DISPLAYLOCATION:** Racial Abilities

### ABILITYCATEGORY:Sacrificed Eyestalk

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Sacrificed Eyestalks
- **DISPLAYLOCATION:** Racial Abilities

### ABILITYCATEGORY:Fey'Ri Demonic Ability

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Fey'Ri Demonic Abilities
- **DISPLAYLOCATION:** Racial Abilities

### ABILITYCATEGORY:Helmed Horror Spell Immunity

- **EDITABLE:** YES
- **EDITPOOL:** YES
- **FRACTIONALPOOL:** NO
- **PLURAL:** Helmed Horror Spell Immunities
- **DISPLAYLOCATION:** Racial Abilities

## Classes

### CLASS:Beholder Mage (MoF)

- **HD:** 4
- **FACT:** Abb|BeHM
- **MAXLEVEL:** 10
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABPoor|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 1

- **CAST:** 6,3
- **ABILITY:** Special Ability|AUTOMATIC|Beholder Mage ~ Sacrifice Eyestalk
- **DEFINE:** SacrificedStalks|0
- **BONUS:** VAR|SacrificedStalks|min(10,CL+1)

### 2

- **CAST:** 6,5,3

### 3

- **CAST:** 6,6,5,3
- **BONUS:** VAR|FamiliarLVL|CL
- **ABILITY:** Special Ability|AUTOMATIC|Summon Familiar

### 4

- **CAST:** 6,6,6,5,3

### 5

- **CAST:** 6,6,6,6,5,3

### 6

- **CAST:** 6,6,6,6,6,5,3

### 7

- **CAST:** 6,6,6,6,6,6,5,3

### 8

- **CAST:** 6,6,6,6,6,6,6,5,3

### 9

- **CAST:** 6,6,6,6,6,6,6,6,5,3

### 10

- **CAST:** 6,6,6,6,6,6,6,6,6,5

### CLASS:Banelar

- **HD:** 10
- **MAXLEVEL:** 21
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** DOMAIN|NUMBER|3
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Choldrith

- **HD:** 8
- **MAXLEVEL:** 4
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** DOMAIN|NUMBER|3
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Cloaker Lord

- **HD:** 8
- **MAXLEVEL:** 9
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### SUBCLASS:Shadow

- **COST:** 0
- **CHOICE:** SUBSCHOOL|Shadow
- **KNOWNSPELLSFROMSPECIALTY:** 1

### SUBCLASSLEVEL:1

- **ABILITY:** Special Ability|AUTOMATIC|Shadow Learning Bonus

### CLASS:Sharn

- **HD:** 8
- **MAXLEVEL:** 12
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** DOMAIN|NUMBER|4
- **BONUS:** DOMAIN|NUMBER|4
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 11

- **BONUS:** PCLEVEL|Sorcerer|1

### 12

- **BONUS:** PCLEVEL|Cleric|1

### CLASS:Brown Dragon

- **HD:** 12
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 15

- **ADD:** SPELLCASTER|Sorcerer
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=DragonCL|Create Water

### 17

- **BONUS:** PCLEVEL|Sorcerer|1

### 18

- **SR:** 20
- **DR:** 5/Magic
- **BONUS:** PCLEVEL|Sorcerer|1

### 20

- **BONUS:** PCLEVEL|Sorcerer|1

### 21

- **SR:** 23
- **BONUS:** PCLEVEL|Sorcerer|1
- **ABILITY:** Special Ability|AUTOMATIC|Brown Dragon ~ Sandstorm

### 23

- **BONUS:** PCLEVEL|Sorcerer|1

### 24

- **SR:** 25
- **DR:** 10/Magic
- **BONUS:** PCLEVEL|Sorcerer|1

### 26

- **BONUS:** PCLEVEL|Sorcerer|1

### 27

- **SR:** 27
- **BONUS:** PCLEVEL|Sorcerer|1
- **BONUS:** VAR|SummonAirElementalPerDay|1
- **ABILITY:** Special Ability|AUTOMATIC|Brown Dragon ~ Summon Air Elemental ~ Huge

### 29

- **BONUS:** PCLEVEL|Sorcerer|1

### 30

- **SR:** 28
- **DR:** 15/Magic
- **BONUS:** PCLEVEL|Sorcerer|1

### 32

- **BONUS:** PCLEVEL|Sorcerer|1

### 33

- **SR:** 30
- **BONUS:** PCLEVEL|Sorcerer|1
- **BONUS:** VAR|SummonAirElementalPerDay|1
- **BONUS:** VAR|SummonAirELementalType|1

### 35

- **BONUS:** PCLEVEL|Sorcerer|1

### 36

- **SR:** 32
- **DR:** 20/Magic
- **BONUS:** PCLEVEL|Sorcerer|1

### 38

- **BONUS:** PCLEVEL|Sorcerer|1

### 39

- **SR:** 34
- **BONUS:** PCLEVEL|Sorcerer|1
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=DragonCL|Disintegrate,16+CHA

### CLASS:Deep Dragon

- **HD:** 12
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Song Dragon

- **HD:** 12
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### 14

- **BONUS:** VAR|DragonAge|1
- **ADD:** SPELLCASTER|Sorcerer
- **SPELLS:** Innate|TIMES=2|CASTERLEVEL=DragonCL|Blink

### 16

- **BONUS:** PCLEVEL|Sorcerer|1

### 19

- **BONUS:** PCLEVEL|Sorcerer|1

### 22

- **BONUS:** PCLEVEL|Sorcerer|1

### 25

- **BONUS:** PCLEVEL|Sorcerer|1

### 28

- **BONUS:** PCLEVEL|Sorcerer|1

### 31

- **BONUS:** PCLEVEL|Sorcerer|1

### 34

- **BONUS:** PCLEVEL|Sorcerer|1

### 37

- **BONUS:** PCLEVEL|Sorcerer|1

## Companion Modifiers

### FOLLOWER:FamiliarLVL=1

- **ABILITY:** Special Ability|AUTOMATIC|Spellray

## Equipment

### Silverweave Armor

- **PROFICIENCY:** ARMOR|Chainmail
- **COST:** 50
- **WT:** 20
- **ACCHECK:** -1
- **EQMOD:** STEEL
- **MAXDEX:** 5
- **SPELLFAILURE:** 15
- **BONUS:** COMBAT|AC|3|TYPE=Armor

### Pearl Armor

- **PROFICIENCY:** ARMOR|Chainmail
- **COST:** 300
- **WT:** 40
- **ACCHECK:** -5
- **EQMOD:** STEEL
- **MAXDEX:** 2
- **SPELLFAILURE:** 30
- **BONUS:** COMBAT|AC|5|TYPE=Armor

## Kits

### STARTPACK:Default Dragonkin

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Monstrous Humanoid]

### RACE:Dragonkin

- **!PRERACE:** 1,%

### NAME:Dragonkin


### ALIGN:CE


### SKILL:Intimidate

- **RANK:** 10

### SKILL:Listen

- **RANK:** 10

### SKILL:Spot

- **RANK:** 10

### ABILITY:CATEGORY=FEAT|Flyby Attack


### ABILITY:CATEGORY=FEAT|Great Fortitude


### STAT:STR=11|DEX=11|CON=11|INT=10|WIS=10|CHA=10


### GEAR:Longspear

- **SIZE:** PC
- **LOCATION:** Carried

## Languages

### Bullywi


### Hybsil


### Malaugrym


### Nishruu


### Quaggoth


### Sharn


### Siv


### Stinger


### Beholder


## Races

### Tiefling Fey'ri

- **FAVCLASS:** Sorcerer
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **LANGBONUS:** Draconic,Gnoll,Gnome,Goblin,Orc,Sylvan
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-2
- **AUTO:** LANG|Common|Elven|Abyssal
- **ABILITY:** Internal|AUTOMATIC|Fey'ri Racial Trait Default
- **LEGS:** 2
- **HANDS:** 2
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Planetouched|Tiefling|Elf|Half-Elf
- **LEVELADJUSTMENT:** 2
- **CR:** 2
- **SORTKEY:** Planetouched

### Tiefling Tanarukk

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Hide|Intimidate|Listen|Search|Spot
- **AUTO:** LANG|Abyssal|Orc
- **ABILITY:** Internal|AUTOMATIC|Tanarukk Racial Trait Default
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Outsider:5
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Extraplanar|Planetouched|Tiefling|Orc|Half-Orc
- **LEVELADJUSTMENT:** 3
- **CR:** 2
- **SORTKEY:** Planetouched

### Brown Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,60,Burrow,60
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **AUTO:** LANG|Draconic
- **AUTO:** WEAPONPROF|TYPE=Simple
- **LEGS:** 4
- **MONSTERCLASS:** Dragon:6
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Earth
- **KIT:** 1|CN
- **SORTKEY:** Dragon

### Deep Dragon

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **MOVE:** Walk,40,Fly,100,Burrow,20,Swim,30
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **AUTO:** LANG|Draconic
- **AUTO:** WEAPONPROF|TYPE=Simple
- **LEGS:** 4
- **MONSTERCLASS:** Dragon:6
- **RACETYPE:** Dragon
- **RACESUBTYPE:** Earth
- **KIT:** 1|CE
- **SORTKEY:** Dragon

### Aarakocra

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Fly,60
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|4
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Knowledge (Nature)|Listen|Spot|Survival|TYPE=Craft
- **AUTO:** LANG|Common|Auran
- **AUTO:** WEAPONPROF|Javelin
- **ABILITY:** Special Ability|AUTOMATIC|Summon Large Air elemental ~ Aarakocra
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Talon,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Monstrous Humanoid:1
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 2
- **CR:** 1/2

### Ooze (Aballin)

- **SIZE:** L
- **MOVE:** Walk,20,Swim,40
- **FACE:** 5
- **REACH:** 10
- **VISION:** Blindsight (60')
- **PREALIGN:** TN
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-4
- **BONUS:** WEAPONPROF=Slam|DAMAGE|max(0,(STR/2))
- **ABILITY:** Special Ability|AUTOMATIC|Drown ~ Aballin|Immunity to Cold|Immunity to Electricity|Immunity to Fire|Passive State ~ Aballin|Vulnerability to Water Affecting Spells ~ Aballin|Immunity to Slashing Weapons ~ Aballin|Immunity to Piercing Weapons ~ Aballin
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning.Acid,*1,1d8
- **DR:** 10/Magic and Bludgeoning
- **MONSTERCLASS:** Ooze:3
- **RACETYPE:** Ooze
- **TEMPLATE:** Ooze|Mindless
- **HITDICEADVANCEMENT:** 5,9
- **CR:** 4

### Devil (Abishai/White)

- **ABILITY:** Special Ability|AUTOMATIC|Abishai Qualities
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,40
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** LE
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Escape Artist|Intimidate|Listen|Search|Spot
- **AUTO:** LANG|Common|Infernal
- **ABILITY:** Special Ability|AUTOMATIC|Sting ~ Abishai White
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 5/Good
- **MONSTERCLASS:** Outsider:4
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider|Extraplanar
- **TEMPLATE:** Abishai
- **TEMPLATE:** Evil|Lawful
- **HITDICEADVANCEMENT:** 6
- **LEVELADJUSTMENT:** 6
- **CR:** 5

### Devil (Abishai/Black)

- **ABILITY:** Special Ability|AUTOMATIC|Abishai Qualities
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,40
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** LE
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Escape Artist|Intimidate|Listen|Search|Spot
- **AUTO:** LANG|Common|Infernal
- **ABILITY:** Special Ability|AUTOMATIC|Sting ~ Abishai Black
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 5/Good
- **MONSTERCLASS:** Outsider:4
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider|Extraplanar
- **TEMPLATE:** Abishai
- **TEMPLATE:** Evil|Lawful
- **HITDICEADVANCEMENT:** 7
- **LEVELADJUSTMENT:** 6
- **CR:** 5

### Devil (Abishai/Green)

- **ABILITY:** Special Ability|AUTOMATIC|Abishai Qualities
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,40
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** LE
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Escape Artist|Intimidate|Listen|Search|Spot
- **AUTO:** LANG|Common|Infernal
- **ABILITY:** Special Ability|AUTOMATIC|Sting ~ Abishai Green
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 5/Good
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider|Extraplanar
- **TEMPLATE:** Abishai
- **TEMPLATE:** Evil|Lawful
- **HITDICEADVANCEMENT:** 8
- **LEVELADJUSTMENT:** 7
- **CR:** 5

### Devil (Abishai/Blue)

- **ABILITY:** Special Ability|AUTOMATIC|Abishai Qualities
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** LE
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Escape Artist|Intimidate|Listen|Search|Spot
- **AUTO:** LANG|Common|Infernal
- **ABILITY:** Special Ability|AUTOMATIC|Sting ~ Abishai Blue
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:7
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider|Extraplanar
- **TEMPLATE:** Abishai
- **TEMPLATE:** Evil|Lawful
- **HITDICEADVANCEMENT:** 9
- **LEVELADJUSTMENT:** 8
- **CR:** 5

### Devil (Abishai/Red)

- **ABILITY:** Special Ability|AUTOMATIC|Abishai Qualities
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Fly,50
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** LE
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Disguise|Escape Artist|Intimidate|Listen|Search|Spot
- **AUTO:** LANG|Common|Infernal|Celestial
- **ABILITY:** Special Ability|AUTOMATIC|Sting ~ Abishai Red
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 10/Good
- **MONSTERCLASS:** Outsider:8
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider|Extraplanar
- **TEMPLATE:** Abishai
- **TEMPLATE:** Evil|Lawful
- **HITDICEADVANCEMENT:** 10
- **LEVELADJUSTMENT:** 9
- **CR:** 5

### Alaghi

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Common,Giant,Goblin
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **AUTO:** LANG|Sylvan
- **AUTO:** WEAPONPROF|Javelin|Handaxe
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d4
- **MONSTERCLASS:** Monstrous Humanoid:9
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 2
- **CR:** 4

### Asabi (Common)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,50,Burrow,20
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump|8|TYPE=Racial
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **MONCSKILL:** Hide|Jump|Move Silently
- **AUTO:** ARMORPROF|Leather
- **AUTO:** WEAPONPROF|Scimitar|Crossbow (Light)
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Reptilian
- **TEMPLATE:** Monstrous Humanoid
- **TEMPLATE:** Reptilian
- **HITDICEADVANCEMENT:** 3,6
- **LEVELADJUSTMENT:** 3
- **CR:** 1

### Asabi (Stingtail)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40,Burrow,30
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump|8|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-2
- **MONCSKILL:** Hide|Jump|Move Silently
- **AUTO:** ARMORPROF|Leather
- **ABILITY:** Special Ability|AUTOMATIC|Asabi ~ Immunity to Enchantment|Asabi ~ Poison Tail
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6|Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning.Poison,*1,1d4
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Reptilian
- **TEMPLATE:** Monstrous Humanoid
- **TEMPLATE:** Reptilian
- **HITDICEADVANCEMENT:** 3,6
- **LEVELADJUSTMENT:** 5
- **CR:** 1

### Banedead

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** LE
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **MONCSKILL:** Hide|Knowledge (Religion)|Listen|Move Silently|Search|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Banedead ~ Dexterity Damage
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 5/Silver
- **MONSTERCLASS:** Undead:6
- **RACETYPE:** Undead
- **TEMPLATE:** Undead
- **CR:** 3

### Baneguard

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|INT|-2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **MONCSKILL:** Hide|Listen|Move Silently|Search|Spot
- **AUTO:** WEAPONPROF|Longsword
- **ABILITY:** Special Ability|AUTOMATIC|Baneguard ~ Spells
- **ABILITY:** Special Ability|AUTOMATIC|Baneguard ~ Immunities
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **TEMPLATE:** Undead
- **CR:** 2

### Baneguard.COPY=Baneguard (Direguard)


### Banelar

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Swim,30
- **FACE:** 15
- **REACH:** 15
- **VISION:** Darkvision (60')|Low-Light Vision
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|PetrificationResistanceBonus|3
- **BONUS:** VAR|FastHealing|2
- **MONCSKILL:** Concentration|Diplomacy|Intimidate|Spot|Use Magic Device
- **AUTO:** LANG|Common|Draconic|Orc
- **ABILITY:** Special Ability|AUTOMATIC|Banelar ~ Fast Healing|Banelar ~ Immunity to Acid|Banelar ~Immunity to Poison|Banelar ~Poison|Banelar ~ Resistance to Petrification|Banelar ~ Magic Item Use
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Sting,Weapon.Natural.Melee.Finesseable.Piercing.Poison,*1,2d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing.Poison,*1,1d3
- **MONSTERCLASS:** Banelar:7
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **HITDICEADVANCEMENT:** 7,15,21
- **CR:** 5

### Bat (Deep/Bonebat)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,10,Fly,50
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** NE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Bonebat ~ Paralysis|Bonebat ~ See Invisibility|Bonebat ~ Weapon Immunities
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 5/Bludgeoning
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **TEMPLATE:** Undead
- **CR:** 2

### Bat (Deep/Night Hunter)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,10,Fly,50
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** VAR|FrightfulPresRange|30
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Night Hunter ~ Frightful Presence
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 2
- **NATURALATTACKS:** Tail Stab,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **MONSTERCLASS:** Magical Beast:2
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **HITDICEADVANCEMENT:** 2,6
- **CR:** 1

### Bat (Deep/Sinister)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Fly,50
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|HoldMonsterPerDay|1
- **BONUS:** VAR|HoldMonsterLVL|HD
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Sinister ~ Hold Monster|Sinister ~ Missile Deflection
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Magical Beast:2
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **HITDICEADVANCEMENT:** 2,6
- **CR:** 1

### Beast of Malar (Hunting Panther)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,60
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot,Listen|4|TYPE=Racial
- **BONUS:** SKILL|Hide,Jump,Move Silently|8|TYPE=Racial
- **BONUS:** SKILL|Balance|12|TYPE=Racial
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|12
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|RegenerationRate|6
- **MONCSKILL:** Balance|Climb|Hide|Jump|Listen|Move Silently|Spot|Survival|Swim
- **ABILITY:** FEAT|AUTOMATIC|Track|Weapon Finesse
- **ABILITY:** Special Ability|AUTOMATIC|Improved Grab|Pounce|Rake
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Fear|RegenerationChoice (Divine magic and blessed weapons)|Scent
- **ABILITY:** Special Ability|AUTOMATIC|Beast of Malar ~ Panther Skill
- **LEGS:** 4
- **HANDS:** 0
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 10/Magic and Silver
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Shapechanger
- **TEMPLATE:** Magical Beast|Shapechanger
- **CR:** 11

### Beast of Malar (Claw Slayer)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Climb,20
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot,Listen|4|TYPE=Racial
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|RegenerationRate|6
- **MONCSKILL:** Climb|Hide|Jump|Listen|Move Silently|Spot|Survival|Swim
- **ABILITY:** FEAT|AUTOMATIC|Improved Critical(Claw)|Power Attack
- **ABILITY:** Special Ability|AUTOMATIC|Improved Grab
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Fear|RegenerationChoice (Divine magic and blessed weapons)
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,2d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*4,1d6
- **DR:** 10/Magic and Silver
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Shapechanger
- **TEMPLATE:** Magical Beast|Shapechanger
- **CR:** 11

### Beast of Malar (Bat Form)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,10,Fly,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot,Listen|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|RegenerationRate|6
- **MONCSKILL:** Climb|Hide|Jump|Listen|Move Silently|Spot|Survival|Swim
- **ABILITY:** FEAT|AUTOMATIC|Flyby Attack|Improved Critical(Bite)|Weapon Focus(Bite)
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Fear|RegenerationChoice (Divine magic and blessed weapons)
- **LEGS:** 4
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 10/Magic and Silver
- **MONSTERCLASS:** Magical Beast:9
- **RACETYPE:** Magical Beast
- **RACESUBTYPE:** Shapechanger
- **TEMPLATE:** Magical Beast|Shapechanger
- **CR:** 11

### Beholderkin (Death Kiss)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,5,Fly,30
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Hide|Listen|Search|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Blood Drain ~ Death Kiss|Improved Grab
- **ABILITY:** Special Ability|AUTOMATIC|Death Kiss ~ Death Shiver|Death Kiss ~ Electric Aura|Flight
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 10
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*10,1d4
- **MONSTERCLASS:** Aberration:12
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **HITDICEADVANCEMENT:** 15,30,36
- **CR:** 11

### Beholderkin (Eyeball)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** D
- **MOVE:** Walk,5,Fly,40
- **FACE:** 1
- **REACH:** 0
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** SKILL|Spot|4|TYPE=Racial
- **BONUS:** SKILL|Search|8|TYPE=Racial
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|-2
- **BONUS:** STAT|INT|-8
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Hide|Listen|Search|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Eyeball ~ Eye Rays
- **ABILITY:** Special Ability|AUTOMATIC|Eyeball ~ All-Around Vision|Eyeball ~ Flight|Eyeball ~ Immunity to Charm|Eyeball ~ Immunity to Command
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Eye Rays,Weapon.Natural.Finesseable.Ranged.Touch,*10,0|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Aberration:1
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **HITDICEADVANCEMENT:** 1,3
- **CR:** 1/2

### Beholderkin (Gouger)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Fly,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-2
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|Maneuverability|4
- **MONCSKILL:** Hide|Listen|Move Silently|Search|Spot|Survival
- **AUTO:** LANG|Common|Undercommon|Beholder
- **ABILITY:** Special Ability|AUTOMATIC|Beholder ~ Antimagic Cone|Gouger ~ Eye Gouge
- **ABILITY:** Special Ability|AUTOMATIC|Gouger ~ All-Around Vision|Gouger ~ Flight
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,2d6|Tongue,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d8,SPROP=Eye Gouge
- **MONSTERCLASS:** Aberration:14
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **HITDICEADVANCEMENT:** 30,42
- **CR:** 11

### Bullywug

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Swim,30
- **FACE:** 5
- **REACH:** 5
- **LANGBONUS:** Aquan,Infernal,Sylvan
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|-4
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Hide|Swim
- **AUTO:** LANG|Bullywi
- **AUTO:** WEAPONPROF|Shortspear
- **ABILITY:** Special Ability|AUTOMATIC|Bullywug ~ Marsh Move|Bullywug ~ Summoning
- **ABILITY:** Special Ability|AUTOMATIC|Bullywug Skill
- **LEGS:** 2
- **HANDS:** 2
- **MONSTERCLASS:** Humanoid:1
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Aquatic
- **TEMPLATE:** Humanoid|Aquatic
- **CR:** 1

### Choldrith

- **FAVCLASS:** Cleric
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Climb,20
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|DarknessPerDay|2
- **BONUS:** VAR|BlessPerDay|2
- **BONUS:** VAR|DarknessLVL|HD
- **BONUS:** VAR|BlessLVL|HD
- **MONCSKILL:** Balance|Climb|Concentration|Jump|Knowledge (Religion)|Spellcraft
- **AUTO:** LANG|Undercommon|Abyssal
- **ABILITY:** Special Ability|AUTOMATIC|Poison|Choldrith ~ Web
- **ABILITY:** Special Ability|AUTOMATIC|Bless (Sp)|Darkness (Sp)
- **LEGS:** 6
- **HANDS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing.Poison,*1,2d4
- **SR:** 13
- **MONSTERCLASS:** Choldrith:4
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **LEVELADJUSTMENT:** 5
- **CR:** 4

### Chosen One

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **MONCSKILL:** Climb|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Poison
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing.Poison,*2,1d8
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 4
- **CR:** 2

### Cloaker Lord

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,10,Fly,50
- **FACE:** 15
- **REACH:** 10
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** STAT|STR|16
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|8
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Hide|Knowledge (arcana)|Listen|Move Silently|Spellcraft|Spot
- **ABILITY:** FEAT|AUTOMATIC|Blind-Fight
- **AUTO:** LANG|Undercommon
- **ABILITY:** Special Ability|AUTOMATIC|Cloaker Lord ~ Dominate Cloakers|Cloaker Lord ~ Engulf|Cloaker Lord ~ Moan
- **ABILITY:** Special Ability|AUTOMATIC|Cloaker Lord ~ Plane Shift|Cloaker Lord ~ Shadow Shift
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6|Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d4
- **SR:** 18
- **MONSTERCLASS:** Cloaker Lord:9
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **CR:** 7

### Swarm (Crawling Claw)

- **SIZE:** D
- **MOVE:** Walk,20
- **FACE:** 10
- **REACH:** 0
- **VISION:** Blindsight (60')
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|WIS|-6
- **BONUS:** STAT|CHA|-6
- **BONUS:** WEAPONPROF=Swarm|DAMAGE|-1*(STR)
- **ABILITY:** Special Ability|AUTOMATIC|Crawling Claw ~ Distraction|Crawling Claw ~ Smite Fallen
- **ABILITY:** Special Ability|AUTOMATIC|Crawling Claw ~ Immunity to Gaze
- **LEGS:** 0
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1
- **NATURALATTACKS:** Swarm,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,3d6
- **SR:** 10
- **MONSTERCLASS:** Construct:1
- **RACETYPE:** Construct
- **TEMPLATE:** Construct|Mindless|Swarm
- **CR:** 1/3

### Darkenbeast

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,5,Fly,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **PREALIGN:** NE
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|Maneuverability|2
- **MONCSKILL:** Hide|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Darkenbeast ~ Spell Imprinting
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Mind-Affecting|Vulnerability to Sunlight
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **SR:** 15
- **MONSTERCLASS:** Magical Beast:5
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **CR:** 4

### Dark Tree

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,10
- **FACE:** 10
- **REACH:** 15
- **VISION:** Low-Light Vision
- **BONUS:** COMBAT|AC|13|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|ConfusionLVL|HD
- **BONUS:** VAR|FireResistanceBonus|15
- **MONCSKILL:** Disguise
- **ABILITY:** Special Ability|AUTOMATIC|Confusion (Sp/CHA/at will)|Improved Grab
- **ABILITY:** Special Ability|AUTOMATIC|Resistance To Fire|Vulnerability to Cold
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **MONSTERCLASS:** Plant:10
- **RACETYPE:** Plant
- **TEMPLATE:** Plant
- **HITDICEADVANCEMENT:** 16,30
- **CR:** 7

### Deepspawn

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,20,Swim,20
- **FACE:** 15
- **REACH:** 20
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|-6
- **BONUS:** VAR|DetectThoughtsLVL|14
- **BONUS:** VAR|WaterBreathingLVL|14
- **BONUS:** VAR|HealLVL|14
- **MONCSKILL:** Craft (Trapmaking)|Diplomacy|Hide|Knowledge (Dungeoneering)|Listen|Sense Motive|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Deepspawn ~ Constrict|Deepspawn ~ Hold Monster
- **ABILITY:** Special Ability|AUTOMATIC|Deepspawn ~ Cover|Deepspawn ~ Detect Thoughts|Deepspawn ~ Heal|Immunity to Poison|Deepspawn ~ Spawn|Deepspawn ~ Water Breathing
- **LEGS:** 0
- **HANDS:** 6
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*3,2d6|Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*3,1d4
- **SR:** 27
- **MONSTERCLASS:** Aberration:14
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **HITDICEADVANCEMENT:** 16,32,42
- **CR:** 8

### Demon (Ghour)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 15
- **VISION:** Darkvision (60')
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|BreathWeaponCloud|10
- **BONUS:** VAR|BreathWeaponDice|1
- **BONUS:** VAR|BreathWeaponDamageDie|6
- **BONUS:** VAR|FireResistanceBonus,ColdResistanceBonus,AcidResistanceBonus|10
- **BONUS:** VAR|TelepathyRange|100
- **BONUS:** WEAPONPROF=Horn|CRITMULTADD|2
- **MONCSKILL:** Bluff|Climb|Concentration|Diplomacy|Disguise|Hide|Intimidate|Jump|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Abyssal|Giant
- **ABILITY:** Special Ability|AUTOMATIC|Ghour ~ Breath Weapon ~ Cloud of Noxious Gas|Ghour ~ Roar
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Electricity|Immunity to Poison|Resistance To Acid|Resistance To Cold|Resistance To Fire|Scent|Telepathy
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Horn,Weapon.Natural.Melee.Finesseable.Piercing,*2,1d8|Hand,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6
- **SR:** 25
- **DR:** 15/Good
- **MONSTERCLASS:** Outsider:12
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider|Extraplanar
- **TEMPLATE:** Chaotic|Evil
- **HITDICEADVANCEMENT:** 15,31,36
- **CR:** 12
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=14|Blasphemy|Chaos Hammer|Deeper Darkness|Desecrate|Detect Good|Detect Magic|Magic Circle against Good|Teleport (Greater)|Unholy Blight
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=14|Confusion|Fear|Maze|Righteous Might

### Doppelganger (Greater)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Bluff,Disguise|4|TYPE=Racial
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|6
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|2
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Intimidate|Listen|Search|Sense Motive|Spot
- **ABILITY:** FEAT|AUTOMATIC|Alertness
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|Rapier
- **ABILITY:** Special Ability|AUTOMATIC|Greater Doppelganger ~ Detect Thoughts|Greater Doppelganger ~ Polymorph Rend
- **ABILITY:** Special Ability|AUTOMATIC|Greater Doppelganger ~ Change Shape|Greater Doppelganger ~ Consume Identity|Immunity to Charm Effects|Greater Doppelganger ~ Immunity to Hold Effects|Immunity to Mind-Affecting|Immunity to Sleep
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d6
- **MONSTERCLASS:** Monstrous Humanoid:9
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Shapechanger
- **TEMPLATE:** Monstrous Humanoid
- **TEMPLATE:** Shapechanger
- **CR:** 12

### Dragonkin

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **LANGBONUS:** Common,Gnome,Halfling
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|3
- **BONUS:** STAT|INT|0
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|3
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **MONCSKILL:** Listen|Move Silently|Spot|Survival
- **ABILITY:** FEAT|AUTOMATIC|Flyby Attack|Great Fortitude
- **AUTO:** LANG|Draconic
- **AUTO:** WEAPONPROF|Longspear|TYPE=Simple
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Foreclaw,Weapon.Natural.Melee.Finesseable.Slashing,*2,1d6
- **MONSTERCLASS:** Monstrous Humanoid:7
- **RACETYPE:** Monstrous Humanoid
- **CR:** 3

### Dread Warrior

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** SKILL|Climb,Jump,Spot|4|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Climb|Jump|Spot
- **AUTO:** ARMORPROF|Banded Mail|Splint Mail|ARMORTYPE=Light
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Battleaxe|Longsword
- **LEGS:** 2
- **HANDS:** 2
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **TEMPLATE:** Undead
- **CR:** 3

### Firenewt

- **FAVCLASS:** Barbarian
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|BreathWeaponLine|5
- **BONUS:** VAR|BreathWeaponDice|1
- **BONUS:** VAR|BreathWeaponDamageDie|6
- **MONCSKILL:** Intimidate|Listen|Ride|Spot
- **AUTO:** ARMORPROF|Chainmail|ARMORTYPE=Light
- **AUTO:** LANG|Draconic
- **AUTO:** WEAPONPROF|Longsword
- **ABILITY:** Special Ability|AUTOMATIC|Breath Weapon ~ Line of Fire
- **ABILITY:** Special Ability|AUTOMATIC|Firenewt Skill
- **LEGS:** 2
- **HANDS:** 2
- **MONSTERCLASS:** Monstrous Humanoid:2
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Reptilian
- **TEMPLATE:** Monstrous Humanoid
- **TEMPLATE:** Reptilian
- **TEMPLATE:** Fire
- **LEVELADJUSTMENT:** 3
- **CR:** 1

### Ghaunadan

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Blindsight (60')
- **LANGBONUS:** Common
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|6
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Hide|Intimidate
- **AUTO:** LANG|Abyssal|Undercommon
- **AUTO:** WEAPONPROF|Longsword
- **ABILITY:** Special Ability|AUTOMATIC|Ghaunadan ~ Charming Gaze|Ghaunadan ~ Paralysis
- **ABILITY:** Special Ability|AUTOMATIC|Ghaunadan ~ Change Shape|Ghaunadan ~ Disarm|Immunity to Critical Hits|Immunity to Flanking|Immunity to Paralysis|Immunity to Poison|Immunity to Polymorph|Immunity to Sleep|Immunity to Stunning
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Pseudopod,Weapon.Natural.Melee.Finesseable.Bludgeoning.Paralysis,*2,1d6
- **DR:** 5/Piercing or Slashing
- **MONSTERCLASS:** Aberration:5
- **RACETYPE:** Aberration
- **RACESUBTYPE:** Shapechanger
- **TEMPLATE:** Aberration
- **TEMPLATE:** Shapechanger
- **LEVELADJUSTMENT:** 6
- **CR:** 5

### Giant (Fog)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40
- **FACE:** 15
- **REACH:** 15
- **VISION:** Low-Light Vision
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|18
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** WEAPONPROF=Thrown Rock|TOHIT|1|TYPE=Racial
- **MONCSKILL:** Climb|Hide|Jump|Listen|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light
- **AUTO:** LANG|Giant|Common
- **AUTO:** WEAPONPROF|Greatclub
- **ABILITY:** Special Ability|AUTOMATIC|Fog Giant ~ Rock Throwing
- **ABILITY:** Special Ability|AUTOMATIC|Fog Giant ~ Hide in Fog|Fog Giant ~ Rock Catching
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Thrown Rock,Weapon.Natural.Ranged.Thrown.Bludgeoning,*1,2d6
- **MONSTERCLASS:** Giant:14
- **RACETYPE:** Giant
- **TEMPLATE:** Giant
- **TEMPLATE:** Air
- **CR:** 8

### Giant (Phaerlin)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,20
- **FACE:** 15
- **REACH:** 15
- **VISION:** Low-Light Vision
- **BONUS:** COMBAT|AC|10|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|-2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|-2
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|FrightfulPresRange|30
- **MONCSKILL:** Listen|Spot
- **AUTO:** LANG|Giant|Common
- **ABILITY:** Special Ability|AUTOMATIC|Frightful Presence
- **ABILITY:** Special Ability|AUTOMATIC|Scent
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d8
- **SR:** 14
- **MONSTERCLASS:** Giant:8
- **RACETYPE:** Giant
- **TEMPLATE:** Giant
- **TEMPLATE:** Earth
- **HITDICEADVANCEMENT:** 16
- **LEVELADJUSTMENT:** 5
- **CR:** 3

### Giant Strider

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-10
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|MagicResistanceBonus|2
- **MONCSKILL:** Listen
- **ABILITY:** Special Ability|AUTOMATIC|Giant Strider ~ Fireball
- **ABILITY:** Special Ability|AUTOMATIC|Giant Strider ~ Healing from Fire|Giant Strider ~ Resistance to Magic
- **LEGS:** 2
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d8
- **NATURALATTACKS:** Kick,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:2
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **TEMPLATE:** Fire
- **HITDICEADVANCEMENT:** 6
- **LEVELADJUSTMENT:** 2
- **CR:** 1

### Gibberling

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** CN
- **BONUS:** COMBAT|AC|1|TYPE=NaturalArmor
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|WIS|-4
- **BONUS:** STAT|CHA|-8
- **MONCSKILL:** Spot
- **AUTO:** WEAPONPROF|Dagger
- **ABILITY:** Special Ability|AUTOMATIC|Gibberling ~ Gibber|Gibberling ~ Teamwork
- **ABILITY:** Special Ability|AUTOMATIC|Gibberling ~ Bunching|Vulnerability to Fire|Vulnerability to Sunlight
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Monstrous Humanoid:1
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Gibberling
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 1
- **CR:** 1/3

### Goblin (Dekanter)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|FastHealing|3
- **BONUS:** VAR|ColdResistanceBonus|5
- **BONUS:** WEAPONPROF=Gore|CRITMULTADD|1
- **MONCSKILL:** Climb|Intimidate|Jump|Listen|Spot
- **AUTO:** LANG|Goblin|Undercommon
- **ABILITY:** Special Ability|AUTOMATIC|Fast Healing|Resistance To Cold
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Gore,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d6|Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Goblinoid
- **TEMPLATE:** Humanoid
- **TEMPLATE:** Goblinoid
- **LEVELADJUSTMENT:** 3
- **CR:** 1

### Golem (Gemstone/Ruby)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Burrow,10
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-10
- **BONUS:** VAR|RegenerationRate|10
- **MONCSKILL:** Climb|Jump
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Magic|RegenerationChoice (Sonic Attacks)
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **DR:** 10/Adamantine
- **MONSTERCLASS:** Construct:10
- **RACETYPE:** Construct
- **TEMPLATE:** Construct
- **HITDICEADVANCEMENT:** 20,30
- **CR:** 11

### Golem (Gemstone/Emerald)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|17|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-10
- **MONCSKILL:** Climb|Jump
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Emerald Golem ~ Emerald Gates|Immunity to Magic
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **DR:** 10/Adamantine
- **MONSTERCLASS:** Construct:12
- **RACETYPE:** Construct
- **TEMPLATE:** Construct
- **HITDICEADVANCEMENT:** 24,36
- **CR:** 12

### Golem (Gemstone/Diamond)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|19|TYPE=NaturalArmor
- **BONUS:** STAT|STR|20
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-10
- **BONUS:** VAR|SunbeamLVL|15
- **BONUS:** VAR|TrueStrikeLVL|15
- **MONCSKILL:** Climb|Jump
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Diamond Golem ~ Sunbeam|Diamond Golem ~ Targeted Dispel|Diamond Golem ~ True Strike
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Magic|Gemstone Golem ~ Vulnerability to Ki
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6
- **DR:** 10/Adamantine
- **MONSTERCLASS:** Construct:12
- **RACETYPE:** Construct
- **TEMPLATE:** Construct
- **HITDICEADVANCEMENT:** 24,36
- **CR:** 12

### Golem (Thayan)

- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CHA|-10
- **ABILITY:** FEAT|AUTOMATIC|Point Blank Shot|Precise Shot|Rapid Shot
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|Longbow
- **ABILITY:** Special Ability|AUTOMATIC|Thayan Golem ~ Immunity to Magic Missile
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6
- **SR:** 12
- **DR:** 10/Adamantine
- **MONSTERCLASS:** Construct (Mindless):7
- **RACETYPE:** Construct
- **TEMPLATE:** Construct|Mindless
- **HITDICEADVANCEMENT:** 11
- **CR:** 8

### Green Warder

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20
- **FACE:** 5
- **REACH:** 5
- **VISION:** Low-Light Vision
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|6
- **BONUS:** VAR|SleepLVL|4
- **BONUS:** VAR|ConfusionLVL|8
- **BONUS:** VAR|AlarmPerDay|2
- **BONUS:** VAR|AlarmLVL|3
- **MONCSKILL:** Hide|Move Silently|Survival
- **AUTO:** LANG|Common|Elven
- **ABILITY:** Special Ability|AUTOMATIC|Confusion (Sp/6 round)|Sleep (Sp/3 round)
- **ABILITY:** Special Ability|AUTOMATIC|Alarm (Sp)
- **ABILITY:** Special Ability|AUTOMATIC|Green Warder Skill
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4
- **MONSTERCLASS:** Plant:4
- **RACETYPE:** Plant
- **TEMPLATE:** Plant
- **HITDICEADVANCEMENT:** 6
- **LEVELADJUSTMENT:** 4
- **CR:** 4
- **TEMPLATE:** Green Warder

### Groundling

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Burrow,30
- **FACE:** 5
- **REACH:** 5
- **PREALIGN:** LE
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|MagicResistanceBonus|2
- **BONUS:** VAR|PoisonResistanceBonus|2
- **MONCSKILL:** Escape Artist|Listen|Survival
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Improved Grab
- **ABILITY:** Special Ability|AUTOMATIC|Groundling ~ Resistance to Magic|Resistance to Poison
- **LEGS:** 4
- **HANDS:** 0
- **NATURALATTACKS:** Claw,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **HITDICEADVANCEMENT:** 9
- **LEVELADJUSTMENT:** 3
- **CR:** 2

### Gulguthydra

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,30,Swim,30
- **FACE:** 15
- **REACH:** 15
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|15|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|-2
- **BONUS:** STAT|CHA|4
- **MONCSKILL:** Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Improved Grab
- **ABILITY:** Special Ability|AUTOMATIC|Gulguthydra ~ Nauseating Stench
- **LEGS:** 4
- **HANDS:** 2
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*6,2d8
- **MONSTERCLASS:** Aberration:15
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **HITDICEADVANCEMENT:** 30,45
- **CR:** 12

### Half-Fiend (Draegloth)

- **FAVCLASS:** Cleric
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|12
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|2
- **BONUS:** VAR|AcidResistanceBonus|10
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|ElectricityResistanceBonus|10
- **BONUS:** VAR|FireResistanceBonus|10
- **BONUS:** VAR|EnchantmentResistanceBonus|2
- **MONCSKILL:** Concentration|Hide|Jump|Knowledge (Religion)|Listen|Move Silently|Search|Spellcraft|Spot
- **AUTO:** LANG|Abyssal|Undercommon
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Poison|Immunity to Sleep|Resistance To Acid|Resistance To Cold|Resistance To Electricity|Resistance to Enchantment|Resistance To Fire
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider|Half-Fiend
- **CR:** 5
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=6|Dancing Lights|Desecrate|Faerie Fire|Unholy Blight,14+CHA
- **SPELLS:** Innate|TIMES=4|CASTERLEVEL=6|Darkness

### Helmed Horror

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** TN
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|FeatherFallLVL|TL
- **AUTO:** ARMORPROF|Full Plate|ARMORTYPE=Light|ARMORTYPE=Medium
- **AUTO:** LANG|Common
- **AUTO:** WEAPONPROF|Greatsword|Crossbow (Heavy)
- **ABILITY:** Special Ability|AUTOMATIC|Helmed Horror ~ Weapon Power
- **ABILITY:** Special Ability|AUTOMATIC|Helmed Horror ~ Air Walk|Helmed Horror ~ Feather Falls|Helmed Horror ~ Immunity to Magic Missile|Helmed Horror ~ See Invisibility
- **BONUS:** ABILITYPOOL|Helmed Horror Spell Immunity|3
- **LEGS:** 2
- **HANDS:** 2
- **MONSTERCLASS:** Construct:13
- **RACETYPE:** Construct
- **TEMPLATE:** Construct
- **HITDICEADVANCEMENT:** 20
- **CR:** 10

### Hybsil

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Walk,50
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump|2|TYPE=Racial
- **BONUS:** SKILL|Survival|4|TYPE=Racial
- **BONUS:** STAT|STR|-2
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **MONCSKILL:** Bluff|Disable Device|Hide|Jump|Listen|Search|Spot|Survival|Use Rope|TYPE=Craft
- **ABILITY:** FEAT|AUTOMATIC|Dodge|Mobility
- **AUTO:** LANG|Hybsil
- **AUTO:** WEAPONPROF|Dagger|Shortbow
- **ABILITY:** Special Ability|AUTOMATIC|Hybsil ~ Sleep Arrows
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Poison|See Invisibility
- **LEGS:** 4
- **HANDS:** 2
- **MONSTERCLASS:** Fey:1
- **RACETYPE:** Fey
- **TEMPLATE:** Fey
- **CR:** 1
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=3|Pass without Trace,11+WIS
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=3|Dancing Lights|Jump,11+CHA|Mirror Image

### Ibrandlin

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** G
- **MOVE:** Walk,20,Climb,20
- **FACE:** 20
- **REACH:** 15
- **PREALIGN:** LN
- **BONUS:** COMBAT|AC|11|TYPE=NaturalArmor
- **BONUS:** STAT|STR|25
- **BONUS:** STAT|CON|14
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|BreathWeaponCone|30
- **BONUS:** VAR|BreathWeaponDice|2
- **BONUS:** VAR|BreathWeaponDamageDie|6
- **MONCSKILL:** Climb|Jump|Listen|Search|Spot
- **AUTO:** LANG|Draconic
- **ABILITY:** Special Ability|AUTOMATIC|Breath Weapon ~ Cone of Fire|Ibrandlin ~ Pin
- **LEGS:** 4
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,4d6|Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*4,2d8
- **SR:** 20
- **MONSTERCLASS:** Dragon:10
- **RACETYPE:** Dragon
- **TEMPLATE:** Dragon
- **TEMPLATE:** Fire
- **HITDICEADVANCEMENT:** 20
- **LEVELADJUSTMENT:** 8
- **CR:** 5

### Ice Serpent

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,80
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|14
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|-6
- **BONUS:** STAT|WIS|2
- **MONCSKILL:** Move Silently|Spot
- **AUTO:** LANG|Abyssal|Giant
- **ABILITY:** Special Ability|AUTOMATIC|Ice Serpent ~ Constrict
- **LEGS:** 0
- **HANDS:** 0
- **DR:** 5/Magic
- **MONSTERCLASS:** Elemental:6
- **RACETYPE:** Elemental
- **RACESUBTYPE:** Air
- **TEMPLATE:** Elemental
- **TEMPLATE:** Air|Cold
- **HITDICEADVANCEMENT:** 9,18
- **LEVELADJUSTMENT:** 4
- **CR:** 3

### Leucrotta

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,50,Climb,20
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|8
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|CHA|-8
- **BONUS:** WEAPONPROF=Bite|CRITMULTADD |1
- **MONCSKILL:** Climb|Hide|Jump|Move Silently|Search|Spot|Survival
- **AUTO:** LANG|Common|Draconic|Giant
- **ABILITY:** Special Ability|AUTOMATIC|Leucrotta ~ Bone Bite
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Charm Effects|Leucrotta ~ Immunity to Compulsion Effects|Leucrotta ~ Mimicry|Scent
- **LEGS:** 4
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Magical Beast:6
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **HITDICEADVANCEMENT:** 16,18
- **LEVELADJUSTMENT:** 4
- **CR:** 4

### Malaugrym

- **FAVCLASS:** Wizard
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Fly,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** MISC|SR|TL-5
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|FastHealing|3
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Bluff|Diplomacy|Disguise|Intimidate|Listen|Search|Sense Motive|Spot|TYPE=Knowledge
- **ABILITY:** FEAT|AUTOMATIC|Great Fortitude|Iron Will
- **AUTO:** LANG|Common|Malaugrym
- **ABILITY:** Special Ability|AUTOMATIC|Malaugrym ~ Change Shape|Fast Healing|Immunity to Poison|Malaugrym ~ Silver Vulnerability
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Tentacle,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **SR:** 15
- **DR:** 10/Silver
- **MONSTERCLASS:** Outsider:5
- **RACETYPE:** Outsider
- **RACESUBTYPE:** Shapechanger
- **TEMPLATE:** Outsider|Extraplanar
- **TEMPLATE:** Shapechanger
- **TEMPLATE:** Evil
- **LEVELADJUSTMENT:** 6
- **CR:** 4

### Meazel

- **FAVCLASS:** Rogue
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** SKILL|Swim|4|TYPE=Racial
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|CHA|-4
- **BONUS:** VAR|SneakAttackDice|3
- **BONUS:** VAR|EvasionUsable,ImprovedEvasionUsable|1|TYPE=Prerequisite
- **MONCSKILL:** Hide|Move Silently|Sleight of Hand|Swim
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Disease|Sneak Attack
- **ABILITY:** Special Ability|AUTOMATIC|Evasion
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing.Disease,*2,1d4
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 4

### Myrlochar

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Climb,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Blindsight (60')
- **PREALIGN:** CE
- **BONUS:** COMBAT|AC|6|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** SKILL|Jump|6|TYPE=Racial
- **BONUS:** SKILL|Spot|12|TYPE=Racial
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|2
- **MONCSKILL:** Balance|Climb|Hide|Jump|Knowledge (Religion)|Listen|Spot|Survival|Tumble
- **AUTO:** LANG|Abyssal|Undercommon
- **ABILITY:** Special Ability|AUTOMATIC|Myrlochar ~ Hit Point Drain
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Charm Effects|Myrlochar ~ Immunity to Compulsion Effects|Myrlochar ~ Immunity to Morale Effects|Immunity to Phantasms|Immunity to Poison|Immunity to Sleep|Myrlochar ~ Immunity to Web|Myrlochar ~ Levitate|Myrlochar ~ Silence
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6|Leg,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Outsider:6
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider
- **TEMPLATE:** Chaotic|Evil
- **HITDICEADVANCEMENT:** 12
- **LEVELADJUSTMENT:** 5
- **CR:** 4

### Nishruu

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Fly,20
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|ColdResistanceBonus|10
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Concentration|Knowledge (arcana)|Knowledge (History)|Knowledge (The Planes)|Listen|Move Silently|Search|Spellcraft|Spot
- **AUTO:** LANG|Nishruu
- **ABILITY:** Special Ability|AUTOMATIC|Nishruu ~ Absorb Magic
- **ABILITY:** Special Ability|AUTOMATIC|Nishruu ~ Charge Magic|Nishruu ~ Gaseous Form|Immunity to Mind-Affecting|Resistance To Cold|Nishruu ~ Vulnerability to Salt
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 0
- **DEFINESTAT:** NONSTAT|STR
- **DR:** 10/Magic
- **MONSTERCLASS:** Outsider:9
- **RACETYPE:** Outsider
- **TEMPLATE:** Outsider
- **TEMPLATE:** Chaotic
- **HITDICEADVANCEMENT:** 15,27
- **CR:** 6

### Nyth

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** S
- **MOVE:** Fly,50
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|4|TYPE=Deflection
- **BONUS:** STAT|STR|-4
- **BONUS:** STAT|DEX|18
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|6
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Diplomacy|Knowledge (arcana)|Listen|Sense Motive|Spot
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Nyth ~ Magic Missile
- **ABILITY:** Special Ability|AUTOMATIC|Nyth ~ Absorb Energy|Nyth ~ Immunity to Charm Effects|Nyth ~ Immunity to Compulsion Effects|Nyth ~ Immunity to Morale Effects|Nyth ~ Immunity to Phantasms|Nyth ~ Invisibility|Nyth ~ Reflect Magic Missile|Nyth ~ Silence
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 0
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **SR:** 15
- **MONSTERCLASS:** Aberration:7
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **LEVELADJUSTMENT:** 10
- **CR:** 5

### Peryton

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,20,Fly,60
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **PREALIGN:** CE
- **LANGBONUS:** ALL
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|WIS|2
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Intimidate|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Common
- **ABILITY:** Special Ability|AUTOMATIC|Peryton ~ Heart Rip
- **ABILITY:** Special Ability|AUTOMATIC|Scent
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 0
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d4|Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d3|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d6
- **DR:** 10/Magic
- **MONSTERCLASS:** Magical Beast:5
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **HITDICEADVANCEMENT:** 10,15
- **LEVELADJUSTMENT:** 3
- **CR:** 5

### Pterafolk

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30,Fly,30
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|7|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|Maneuverability|3
- **MONCSKILL:** Climb|Hide|Intimidate|Jump|Listen|Move Silently|Search|Spot
- **ABILITY:** FEAT|AUTOMATIC|Flyby Attack
- **AUTO:** LANG|Draconic
- **ABILITY:** Special Ability|AUTOMATIC|Pterafolk ~ Alternate Form
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d6|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d8
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **RACESUBTYPE:** Shapechanger
- **TEMPLATE:** Monstrous Humanoid
- **TEMPLATE:** Reptilian|Shapechanger
- **HITDICEADVANCEMENT:** 12
- **LEVELADJUSTMENT:** 4
- **CR:** 3

### Quaggoth

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30,Climb,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|HIDE|2|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **MONCSKILL:** Climb|Hide|Listen|Spot|Survival
- **AUTO:** LANG|Quaggoth
- **AUTO:** WEAPONPROF|Club
- **ABILITY:** Special Ability|AUTOMATIC|Rage
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Fear|Scent
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d4
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 2
- **CR:** 3

### Shalarin

- **FAVCLASS:** Fighter
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Swim,40
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|DEX|4
- **MONCSKILL:** Listen|Spot
- **AUTO:** ARMORPROF|ARMORTYPE=Light|ARMORTYPE=Silverweave
- **AUTO:** LANG|Aquan
- **AUTO:** WEAPONPROF|Trident
- **LEGS:** 2
- **HANDS:** 2
- **MONSTERCLASS:** Humanoid:1
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Aquatic
- **TEMPLATE:** Humanoid|Aquatic
- **CR:** 1/2

### Sharn

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,10,Fly,40
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **PREALIGN:** CN
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|10
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|8
- **BONUS:** STAT|WIS|8
- **BONUS:** STAT|CHA|8
- **BONUS:** VAR|RegenerationRate|2
- **BONUS:** VAR|EvasionUsable,ImprovedEvasionUsable|1|TYPE=Prerequisite
- **BONUS:** VAR|Maneuverability|5
- **MONCSKILL:** Bluff|Concentration|Diplomacy|Knowledge (arcana)|Listen|Search|Sense Motive|Spellcraft|Spot
- **ABILITY:** FEAT|AUTOMATIC|Alertness|Multiattack|Multiweapon Fighting
- **AUTO:** LANG|Sharn
- **ABILITY:** Special Ability|AUTOMATIC|Sharn ~ Hex Portal
- **ABILITY:** Special Ability|AUTOMATIC|Sharn ~ Archetypal Shape|Evasion|Sharn ~ Fixed Shape|Immunity to Mind-Affecting|Immunity to Polymorph|Sharn ~ Independent Action|RegenerationChoice (Lawful Weapons Spells and Outsiders)
- **LEGS:** 0
- **HANDS:** 9
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*9,1d6|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,2d6
- **DR:** 10/Cold Iron
- **MONSTERCLASS:** Sharn:4
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **HITDICEADVANCEMENT:** 8,12
- **LEVELADJUSTMENT:** 5
- **CR:** 6

### Siv

- **FAVCLASS:** Monk
- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,40,Swim,20
- **FACE:** 5
- **REACH:** 5
- **BONUS:** COMBAT|AC|2|TYPE=NaturalArmor
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CHA|-2
- **BONUS:** VAR|ColdResistanceBonus|5
- **MONCSKILL:** Listen|Spot
- **ABILITY:** FEAT|AUTOMATIC|Exotic Weapon Proficiency(Siangham)
- **AUTO:** LANG|Siv
- **AUTO:** WEAPONPROF|Siangham|Net|Sling
- **ABILITY:** Special Ability|AUTOMATIC|Resistance To Cold|Siv ~ Waterwalking
- **LEGS:** 2
- **HANDS:** 2
- **MONSTERCLASS:** Humanoid:1
- **RACETYPE:** Humanoid
- **RACESUBTYPE:** Aquatic
- **TEMPLATE:** Humanoid|Aquatic
- **LEVELADJUSTMENT:** 1
- **CR:** 1

### Spectral Panther

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')|Low-Light Vision
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** SKILL|Move Silently|4|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|6
- **BONUS:** STAT|INT|2
- **BONUS:** STAT|WIS|4
- **BONUS:** STAT|CHA|2
- **BONUS:** VAR|FastHealing|2
- **BONUS:** VAR|SpectralFormPerDay|3
- **MONCSKILL:** Hide|Jump|Listen|Move Silently|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Spectral Panther ~ Fear Aura
- **ABILITY:** Special Ability|AUTOMATIC|Fast Healing|Scent|Spectral Panther ~ Spectral Form
- **ABILITY:** Special Ability|AUTOMATIC|Spectral Panther Skill
- **LEGS:** 4
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d3
- **MONSTERCLASS:** Magical Beast:3
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **HITDICEADVANCEMENT:** 9
- **LEVELADJUSTMENT:** 3
- **CR:** 4

### Subterran Spider (Hairy)

- **SIZE:** F
- **MOVE:** Walk,20,Climb,10
- **FACE:** 0.5
- **REACH:** 0
- **PREALIGN:** TN
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** SKILL|Jump|6|TYPE=Racial
- **BONUS:** SKILL|Spot|12|TYPE=Racial
- **BONUS:** STAT|STR|-10
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CHA|-8
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Poison
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Poison
- **LEGS:** 8
- **HANDS:** 0
- **NATURALATTACKS:** Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing.Poison,*1,1d2
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **TEMPLATE:** Vermin|Mindless
- **CR:** 1/2

### Subterran Spider (Sword)

- **SIZE:** L
- **MOVE:** Walk,20,Climb,20
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|8|TYPE=NaturalArmor
- **BONUS:** SKILL|Hide|4|TYPE=Racial
- **BONUS:** SKILL|Jump|6|TYPE=Racial
- **BONUS:** SKILL|Spot|12|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|-8
- **MONCSKILL:** Climb|Hide|Jump|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Sword Spider ~ Impalement|Sword Spider ~ Poison
- **LEGS:** 8
- **HANDS:** 0
- **NATURALATTACKS:** Leg,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*8,1d6|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing.Poison,*1,1d8
- **MONSTERCLASS:** Vermin:1
- **RACETYPE:** Vermin
- **TEMPLATE:** Vermin|Mindless
- **CR:** 1/2

### Stinger

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,30
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')|Tremorsense (60')
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|4
- **BONUS:** STAT|CON|4
- **BONUS:** STAT|CHA|2
- **MONCSKILL:** Hide|Listen|Move Silently|Search|Spot|Survival
- **AUTO:** LANG|Stinger
- **AUTO:** WEAPONPROF|Chain (Spiked)
- **ABILITY:** Special Ability|AUTOMATIC|Poison
- **ABILITY:** Special Ability|AUTOMATIC|Stinger ~ Bolthole Magic
- **LEGS:** 8
- **HANDS:** 2
- **NATURALATTACKS:** Stinger,Weapon.Natural.Finesseable.Melee.Piercing.Slashing.Poison,*1,1d6|Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Monstrous Humanoid:4
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 4

### Tall Mouther

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 10
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|5|TYPE=NaturalArmor
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|8
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|INT|-2
- **BONUS:** STAT|CHA|-4
- **MONCSKILL:** Climb|Hide|Listen|Search|Spot|Survival
- **AUTO:** LANG|Common|Halfling
- **ABILITY:** Special Ability|AUTOMATIC|Tall Mouther ~ Arrow Evasion
- **LEGS:** 2
- **HANDS:** 4
- **NATURALATTACKS:** Buffet,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*4,1d4|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,2d6
- **MONSTERCLASS:** Aberration:7
- **RACETYPE:** Aberration
- **TEMPLATE:** Aberration
- **HITDICEADVANCEMENT:** 14,21
- **CR:** 5

### Tomb Tapper

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** H
- **MOVE:** Walk,40,Burrow,15
- **FACE:** 15
- **REACH:** 15
- **VISION:** Blindsight (120')|Darkvision (60')|Tremorsense (60')
- **PREALIGN:** TN
- **BONUS:** COMBAT|AC|14|TYPE=NaturalArmor
- **BONUS:** STAT|STR|14
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|CHA|6
- **BONUS:** VAR|StoneShapePerDay|3
- **BONUS:** VAR|StoneShapeLVL|6
- **BONUS:** VAR|SpikeStonesPerDay|7
- **BONUS:** VAR|SpikeStonesLVL|5
- **BONUS:** VAR|DetectMagicLVL|HD
- **MONCSKILL:** Appraise|Listen|Search|Spot|Survival
- **AUTO:** WEAPONPROF|Warhammer
- **ABILITY:** Special Ability|AUTOMATIC|Tomb Tapper ~ Detect Magic|Tomb Tapper ~ Immunity to Gaze|Tomb Tapper ~ Immunity to Illusions|Tomb Tapper ~ Spike Stones|Tomb Tapper ~ Stone Shape|Tomb Tapper ~ Vulnerability to Silence
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Slam,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,2d8
- **DR:** 5/Adamantine
- **MONSTERCLASS:** Construct:12
- **RACETYPE:** Construct
- **TEMPLATE:** Construct
- **HITDICEADVANCEMENT:** 24
- **CR:** 14

### Unicorn (Black Unicorn)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,60
- **FACE:** 10
- **REACH:** 5
- **PREALIGN:** CE
- **BONUS:** STAT|STR|10
- **BONUS:** STAT|DEX|6
- **BONUS:** STAT|CON|10
- **BONUS:** STAT|INT|4
- **BONUS:** STAT|WIS|10
- **BONUS:** STAT|CHA|18
- **BONUS:** VAR|InflictLightWoundsPerDay|3
- **BONUS:** VAR|InflictLightWoundsLVL|HD
- **MONCSKILL:** Intimidate|Listen|Move Silently|Spot|Survival
- **ABILITY:** Special Ability|AUTOMATIC|Inflict Light Wounds (Sp)
- **ABILITY:** Special Ability|AUTOMATIC|Training ~ Unicorn
- **LEGS:** 4
- **HANDS:** 0
- **NATURALATTACKS:** Horn,Weapon.Natural.Melee.Finesseable.Piercing,*1,1d8|Bite,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*1,1d8|Hoof,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4
- **MONSTERCLASS:** Magical Beast:4
- **RACETYPE:** Magical Beast
- **TEMPLATE:** Magical Beast
- **HITDICEADVANCEMENT:** 8
- **CR:** 3
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=HD|Teleport (Greater),17+CHA

### Wemic

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump|8|TYPE=Racial
- **BONUS:** STAT|STR|8
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-2
- **MONCSKILL:** Hide|Jump|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Sylvan|Common
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Club
- **LEGS:** 4
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Monstrous Humanoid:5
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 3

### Wemic (Mountain)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** L
- **MOVE:** Walk,40
- **FACE:** 10
- **REACH:** 5
- **VISION:** Darkvision (60')
- **BONUS:** COMBAT|AC|4|TYPE=NaturalArmor
- **BONUS:** SKILL|Jump|8|TYPE=Racial
- **BONUS:** STAT|STR|6
- **BONUS:** STAT|DEX|2
- **BONUS:** STAT|CON|2
- **BONUS:** STAT|CHA|-2
- **MONCSKILL:** Hide|Jump|Listen|Move Silently|Spot|Survival
- **AUTO:** LANG|Sylvan|Common
- **AUTO:** SHIELDPROF|SHIELDTYPE=Buckler|SHIELDTYPE=Heavy|SHIELDTYPE=Light
- **AUTO:** WEAPONPROF|Club
- **LEGS:** 4
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing,*2,1d6
- **MONSTERCLASS:** Monstrous Humanoid:3
- **RACETYPE:** Monstrous Humanoid
- **TEMPLATE:** Monstrous Humanoid
- **LEVELADJUSTMENT:** 3
- **CR:** 3

### Zombie (Tyrantfog)

- **STARTFEATS:** 1
- **FACT:** HasFirstLevelFeat|True
- **SIZE:** M
- **MOVE:** Walk,30
- **FACE:** 5
- **REACH:** 5
- **VISION:** Darkvision (60')
- **PREALIGN:** LE,NE,CE
- **BONUS:** COMBAT|AC|5|TYPE=Deflection
- **BONUS:** STAT|STR|2
- **BONUS:** STAT|INT|-4
- **BONUS:** STAT|WIS|2
- **BONUS:** STAT|CHA|2
- **MONCSKILL:** Climb|Listen|Spot
- **ABILITY:** Special Ability|AUTOMATIC|Tyrantfog ~ Infective Touch|Tyrantfog ~ Sickening Cloud
- **LEGS:** 2
- **HANDS:** 2
- **NATURALATTACKS:** Claw,Weapon.Natural.Finesseable.Melee.Piercing.Slashing.Disease,*2,1d6
- **DR:** 5/Magic
- **MONSTERCLASS:** Undead:4
- **RACETYPE:** Undead
- **TEMPLATE:** Undead
- **HITDICEADVANCEMENT:** 8
- **CR:** 3

## Spells

### Create Chosen One

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Alteration
- **COMPS:** V, S, M
- **CASTTIME:** 1 Hour
- **RANGE:** Touch
- **TARGETAREA:** One human
- **DURATION:** Instantaneous
- **SAVEINFO:** Will negates
- **SPELLRES:** Yes
- **PRECLASS:** 1,Red Wizard=1

Turn a normal human (max 3 level or hd) into a maddened, murderous creature.

### Create Crawling Claw

- **CLASSES:** Sorcerer,Wizard=3
- **SCHOOL:** Transmutation
- **COMPS:** V, S, M
- **CASTTIME:** 1 Hour
- **RANGE:** Close
- **TARGETAREA:** Severed left hands within a 5-foot radius circle.
- **DURATION:** Instantaneous
- **SPELLRES:** Yes

Create a number of crawling claw.

### Create Darkenbeast

- **CLASSES:** Sorcerer,Wizard=5
- **SCHOOL:** Transmutation
- **DESCRIPTOR:** Evil
- **COMPS:** V, S, M
- **CASTTIME:** 1 Hour
- **RANGE:** Close
- **TARGETAREA:** One animal of no more than 2 HD.
- **DURATION:** Instantaneous
- **SAVEINFO:** See text
- **SPELLRES:** Yes
- **COST:** 200

Transmute a small or medium animal with no more than 2 HD into a darkenbeast.

### Shape Metal

- **CLASSES:** Cleric=4|Sorcerer,Wizard=5
- **SCHOOL:** Transmutation
- **COMPS:** V, S, M/DF
- **CASTTIME:** 1 standard action
- **RANGE:** Touch
- **TARGETAREA:** Metal or metal object, up to 10 cubic foot + 1 cubic foot/level.
- **DURATION:** Instantaneous
- **SAVEINFO:** Fortitude negates
- **SPELLRES:** Yes

As Stone Shape but affect metal instead of stone.

## Templates

### Beast of Xvim

- **TEMPLATE:** CHOOSE:Beast of Xvim (Animal)|Beast of Xvim (Magical Beast)|Beast of Xvim (Dragon)|Beast of Xvim (Aberration)|Beast of Xvim (Outsider)|Beast of Xvim (Undead)
- **PREALIGN:** LE
- **BONUS:** MISC|CR|1
- **BONUS:** STAT|CHA|4
- **BONUS:** VAR|FrightfulPresRange|30
- **BONUS:** VAR|SmiteGood|1
- **BONUS:** VAR|SmiteGoodDamage|HD
- **BONUS:** WEAPONPROF=TYPE.Natural|DAMAGESIZE|1
- **ABILITY:** Special Ability|AUTOMATIC|Beast of Xvim ~ Feed|Frightful Presence|Smite Good
- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Fear|Immunity to Poison
- **VISION:** Darkvision (60')
- **HD:** 4+:DR:5/Magic

### Beast of Xvim (Animal)

- **ADDLEVEL:** Animal|1

### Beast of Xvim (Magical Beast)

- **ADDLEVEL:** Magical Beast|1

### Beast of Xvim (Dragon)

- **ADDLEVEL:** Dragon|1

### Beast of Xvim (Aberration)

- **ADDLEVEL:** Aberration|1

### Beast of Xvim (Outsider)

- **ADDLEVEL:** Outsider|1

### Beast of Xvim (Undead)

- **ADDLEVEL:** Undead|1

### Curst

- **HITDIE:** 12|CLASS.TYPE=Monster
- **LEVELADJUSTMENT:** 3
- **TEMPLATE:** Undead
- **PREALIGN:** CN
- **PRERACE:** 1,RACETYPE=Humanoid
- **BONUS:** COMBAT|AC|3|TYPE=NaturalArmor.REPLACE
- **BONUS:** MISC|CR|1
- **BONUS:** SKILL|Craft (Alchemy)|-2
- **BONUS:** VAR|RegenerationRate|1
- **ABILITY:** Special Ability|AUTOMATIC|Curst ~ Immunity to Turning|Curst ~ Regeneration|Resistance To Cold|Resistance To Fire
- **SR:** 12+TL
- **RACETYPE:** Undead

### Revenant

- **HITDIE:** 12|CLASS.TYPE=Monster
- **DR:** 5/Magic
- **TEMPLATE:** Undead
- **PREALIGN:** TN
- **PRERACE:** 1,RACETYPE=Humanoid
- **BONUS:** MISC|CR|1
- **BONUS:** STAT|STR|4
- **BONUS:** STAT|2|CHA
- **BONUS:** VAR|FastHealing|3
- **ABILITY:** Special Ability|AUTOMATIC|Revenant ~ Paralyzing Glare|Revenant ~ Vengeful Strike
- **ABILITY:** Special Ability|AUTOMATIC|Revenant ~ Fast Healing|Revenant ~ Find the Guilty|Revenant ~ Immunity to Acid|Revenant ~ Immunity to Cold|Revenant ~ Immunity to Electricity|Revenant ~ Immunity to Gas|Revenant ~ Immunity to Mind-Affecting|Revenant ~ Immunity to Polymorph|Revenant ~ Immunity to Turning
- **RACETYPE:** Undead
- **VISION:** Darkvision (60')

### Abishai

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=HD|Animate Dead|Alter Self|Charm Person,11+CHA|Command,11+CHA|Desecrate,12+CHA|Detect Good,13+CHA|Major Image,14+CHA|Suggestion,12+CHA|Scare,11+CHA
- **ABILITY:** Special Ability|AUTOMATIC|Abishai ~ Summon Baatezu|Abishai ~ Immunities|Abishai ~ Regeneration|Abishai ~ See In Darkness|Telepathy|Abishai ~ Vulnerability to Holy Water
- **BONUS:** VAR|TelepathyRange|100

### Construct

- **RACETYPE:** Construct
- **DEFINESTAT:** NONSTAT|CON

### Goblinoid

- **RACESUBTYPE:** Goblinoid

### Ooze

- **RACETYPE:** Ooze

### Green Warder

- **BONUSSKILLPOINTS:** 4


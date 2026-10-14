# Universal Rules

*D&D 3.5e Forgotten Realms game data, converted from PCGen open-source datasets (LGPL).*

## Spells

### Bloodline Aberrant ~ Acidic Ray

- **DEFINE:** AcidicRayDamage|0
- **BONUS:** VAR|AcidicRayDamage|BloodlineLVL/2

Starting at 1st level, you can fire an acidic ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. The acidic ray deals 1d6 points of acid damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

Acidic ray 1d6+%1 (%2/day)|AcidicRayDamage|BloodlinePowerTimes

### Bloodline Accursed ~ Dream Walking


At 15th level, you can enter the ethereal plane. This functions like ethereal jaunt, but with a duration of 1 minute for every 2 sorcerer levels you possess. Once during this trip, you may cast nightmare as a spell-like ability on a creature you see on the Material Plane. (This is an exception to the normal rule that ethereal creatures cannot affect targets on the Material Plane).

### Bloodline Aquatic ~ Dehydrating Touch


Starting at 1st level, you can make a melee touch attack as a standard action that inflicts 1d6 points of nonlethal damage + 1 for every two sorcerer levels you possess and sickens the target for 1 round. Oozes, plants, and creatures with the aquatic or water subtypes suffer lethal damage instead. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Aquatic ~ Raise the Deep


At 15th level, you raise water as per control water, but no water need be present. This created water is stationary and does not flow out of the area where you create it; it lasts 1 round per sorcerer level and then disappears. At 20th level, the dimensions of the effect are doubled. You may use this ability once per day.

### Bloodline Boreal ~ Cold Steel

- **DEFINE:** ColdSteelPerDay|0
- **BONUS:** VAR|ColdSteelPerDay|BloodlinePowerTimes

At 1st level, you can touch a weapon or up to 50 pieces of ammunition as a standard action, giving it the frost property for a number of rounds equal to 1/2 your sorcerer level (minimum 1). At 9th level, you can confer the icy burst property instead, but the duration of the power is halved. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|ColdSteelPerDay

### Bloodline Boreal ~ Blizzard


At 15th level, you can create a savage winter storm centered on you. This power acts as control winds, but in addition the entire area (not including the "eye" at the center of the storm) is affected as a sleet storm and all in the area are exposed to extreme cold. You may use this ability once per day.

### Bloodline Celestial ~ Heavenly Fire


Starting at 1st level, you can unleash a ray of heavenly fire as a standard action, targeting any foe within 30 feet as a ranged touch attack. Against evil creatures, this ray deals 1d4 points of damage + 1 for every two sorcerer levels you possess. This damage is divine and not subject to energy resistance or immunity. This ray heals good creatures of 1d4 points of damage + 1 for every two sorcerer levels you possess. A good creature cannot benefit from your heavenly fire more than once per day. Neutral creatures are neither harmed nor healed by this effect. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Demon ~ Wasting Ray


At 1st level, as a standard action, you can impose either starvation or thirst upon a living creature you can see within 30 feet. This requires the creature to make a Constitution check each round (DC 10 + 1 for each previous check) to avoid taking 1d6 points of nonlethal damage. The creature must continue to make these checks until, as a full-round action, it quenches its thirst or sates its hunger (see starvation and thirst). You can use this ability a number of times per day equal to 3 + your Charisma modifier, but can only apply it once every 24 hours to any given creature. Creatures that do not need to eat are immune to this effect.

### Bloodline Demon ~ Wound Warp


At 15th level, you gain the ability to travel across the battlefield by literally erupting from the fatal wounds of deceased creatures. As a standard action once per day, you can teleport to an unoccupied square adjacent to any dead creature within 10 feet per caster level. Any creatures adjacent to the square you teleport to take 4d6 points of acid damage as you burst into being and shower them with acidic bile. Creatures that make successful Reflex saves (DC 10 + 1/2 your sorcerer level + your Charisma modifier) take half damage. This ability otherwise functions like dimension door. At 20th level, you can use this ability twice per day.

### Bloodline Deep Earth ~ Tremor


At 1st level, as a standard action, you can cause the ground to shake beneath a single creature within 30 feet, functioning as a trip maneuver using your sorcerer level plus your Charisma modifier in place of your CMB. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Deep Earth ~ Crystal Shard

- **DEFINE:** CrystalShardPerDay|0
- **BONUS:** VAR|CrystalShardPerDay|1
- **BONUS:** VAR|CrystalShardPerDay|1
- **BONUS:** VAR|CrystalShardPerDay|1

At 9th level, you can touch a metal or stone weapon (or up to 50 pieces of ammunition) as a standard action, giving it the bane property against any creature with the earth subtype, oozes, or constructs made of stone or metal, for 1 minute. You can use this ability once per day at 9th level, twice per day at 17th, and three times per day at 20th.

### Bloodline Destined ~ Touch of Destiny


At 1st level, you can touch a creature as a standard action, giving it an insight bonus on attack rolls, skill checks, ability checks, and saving throws equal to 1/2 your sorcerer level (minimum 1) for 1 round. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

### Bloodline Djinni ~ Electricity Ray

- **DEFINE:** ElectricityRay|0
- **DEFINE:** ElectricityRayDie|6
- **DEFINE:** ElectricityDamage|0
- **BONUS:** VAR|ElectricityRay|1
- **BONUS:** VAR|ElectricityDamage|BloodlineLVL/2
- **AUTO:** EQUIP|Electricity Ray

Starting at 1st level, you can unleash an elemental ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. This ray deals 1d6 points of electricity damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

### Bloodline Efreeti ~ Fire Ray

- **DEFINE:** FireRay|0
- **DEFINE:** FireRayDie|6
- **DEFINE:** FireDamage|0
- **BONUS:** VAR|FireRay|1
- **BONUS:** VAR|FireDamage|BloodlineLVL/2
- **AUTO:** EQUIP|Fire Ray

Starting at 1st level, you can unleash an elemental ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. This ray deals 1d6 points of fire damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

### Bloodline ~ Elemental Ray (Air)

- **AUTO:** EQUIP|Elemental Ray ~ Air

Starting at 1st level, you can unleash an elemental ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. This ray deals 1d6 points of electricity damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline ~ Elemental Ray (Earth)

- **AUTO:** EQUIP|Elemental Ray ~ Earth

Starting at 1st level, you can unleash an elemental ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. This ray deals 1d6 points of Acid damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline ~ Elemental Ray (Fire)

- **AUTO:** EQUIP|Elemental Ray ~ Fire

Starting at 1st level, you can unleash an elemental ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. This ray deals 1d6 points of fire damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline ~ Elemental Ray (Water)

- **AUTO:** EQUIP|Elemental Ray ~ Water

Starting at 1st level, you can unleash an elemental ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. This ray deals 1d6 points of Cold damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline ~ Elemental Blast (Air)


At 9th level, you can unleash a blast of elemental power once per day. This 20-foot-radius burst does 1d6 points of Electricity damage per sorcerer level. Those caught in the area of your blast receive a Reflex save for half damage. Creatures that fail their saves gain vulnerability to your energy type until the end of your next turn. The DC of this save is equal to 10 + 1/2 your sorcerer level + your Charisma modifier. At 9th level, you can use this ability once per day. At 17th level, you can use this ability twice per day. At 20th level, you can use this ability three times per day. This power has a range of 60 feet.

%1/day (Ref DC %2)|ElementalBlastPerDay|ElementalBlastDC

### Bloodline ~ Elemental Blast (Earth)


At 9th level, you can unleash a blast of elemental power once per day. This 20-foot-radius burst does 1d6 points of Acid damage per sorcerer level. Those caught in the area of your blast receive a Reflex save for half damage. Creatures that fail their saves gain vulnerability to your energy type until the end of your next turn. The DC of this save is equal to 10 + 1/2 your sorcerer level + your Charisma modifier. At 9th level, you can use this ability once per day. At 17th level, you can use this ability twice per day. At 20th level, you can use this ability three times per day. This power has a range of 60 feet.

%1/day (Ref DC %2)|ElementalBlastPerDay|ElementalBlastDC

### Bloodline ~ Elemental Blast (Fire)


At 9th level, you can unleash a blast of elemental power once per day. This 20-foot-radius burst does 1d6 points of Fire damage per sorcerer level. Those caught in the area of your blast receive a Reflex save for half damage. Creatures that fail their saves gain vulnerability to your energy type until the end of your next turn. The DC of this save is equal to 10 + 1/2 your sorcerer level + your Charisma modifier. At 9th level, you can use this ability once per day. At 17th level, you can use this ability twice per day. At 20th level, you can use this ability three times per day. This power has a range of 60 feet.

%1/day (Ref DC %2)|ElementalBlastPerDay|ElementalBlastDC

### Bloodline ~ Elemental Blast (Water)


At 9th level, you can unleash a blast of elemental power once per day. This 20-foot-radius burst does 1d6 points of Cold damage per sorcerer level. Those caught in the area of your blast receive a Reflex save for half damage. Creatures that fail their saves gain vulnerability to your energy type until the end of your next turn. The DC of this save is equal to 10 + 1/2 your sorcerer level + your Charisma modifier. At 9th level, you can use this ability once per day. At 17th level, you can use this ability twice per day. At 20th level, you can use this ability three times per day. This power has a range of 60 feet.

%1/day (Ref DC %2)|ElementalBlastPerDay|ElementalBlastDC

### Bloodline ~ Elemental Movement (Air)

- **BONUS:** VAR|Maneuverability|3
- **MOVE:** Fly,60
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability

At 15th level, you gain Fly 60-ft (Average)

### Bloodline ~ Elemental Movement (Earth)

- **MOVE:** Burrow,30

At 15th level, you gain a special movement type or bonus. This ability is based on your chosen element.

### Bloodline ~ Elemental Movement (Fire)

- **BONUS:** MOVEADD|TYPE.Walk|30

At 15th level, you gain a special movement type or bonus. This ability is based on your chosen element.

### Bloodline ~ Elemental Movement (Water)

- **MOVE:** Swim,30

At 15th level, you gain a special movement type or bonus. This ability is based on your chosen element.

### Bloodline Fey ~ Laughing Touch


At 1st level, you can cause a creature to burst out laughing for 1 round as a melee touch attack. A laughing creature can only take a move action but can defend itself normally. Once a creature has been affected by laughing touch, it is immune to its effects for 24 hours. You can use this ability a number of times per day equal to 3 + your Charisma modifier. This is a mind-affecting effect.

%1/day|BloodlinePowerTimes

### Bloodline Fey ~ Fleeting Glance


At 9th level, you can turn invisible for a number of rounds per day equal to your sorcerer level. This ability functions as greater invisibility. These rounds need not be consecutive.

%1 rounds/day|BloodlineLVL

### Bloodline Infernal ~ Corrupting Touch


At 1st level, you can cause a creature to become shaken as a melee touch attack. This effect persists for a number of rounds equal to 1/2 your sorcerer level (minimum 1). Creatures shaken by this ability radiate an aura of evil, as if they were an evil outsider (see detect evil). Multiple touches do not stack, but they do add to the duration. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Infernal ~ Hellfire

- **DEFINE:** HellfirePerDay|0
- **DEFINE:** HellfireDamage|0
- **DEFINE:** HellfireDC|0
- **BONUS:** VAR|HellfirePerDay|1
- **BONUS:** VAR|HellfirePerDay|1
- **BONUS:** VAR|HellfirePerDay|1
- **BONUS:** VAR|HellfireDamage|BloodlineLVL
- **BONUS:** VAR|HellfireDC|10+(BloodlineLVL/2)+CHA

At 9th level, you can call down a column of hellfire. This 10-foot-radius burst does 1d6 points of fire damage per sorcerer level. Those caught in the area of your blast receive a Reflex save for half damage. Good creatures that fail their saves are shaken for a number of rounds equal to your sorcerer level. The DC of this save is equal to 10 + 1/2 your sorcerer level + your Charisma modifier. At 9th level, you can use this ability once per day. At 17th level, you can use this ability twice per day. At 20th level, you can use this ability three times per day. This power has a range of 60 feet.

%1/day %2d6 Fire burst (Reflex DC %3)|HellfirePerDay|HellfireDamage|HelfireDC

### Bloodline Protean ~ Protoplasm


At 1st level, you can create a ball of entropic protoplasm and hurl it at targets within 30 feet. This protoplasm acts as a tanglefoot bag that also inflicts 1 point of acid damage per round to a creature entangled by it. The protoplasm dissolves within 1d3 rounds. You may use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Protean ~ Reality Wrinkle


At 9th level, you can surround yourself with a mobile, 10-foot-radius emanation of mutable reality. This rippling distortion is similar to solid fog but does not provide concealment or block line of sight. Your movement is not slowed by this aura. Attacks from outside the aura suffer a 20%% miss chance against targets inside the aura. You may use this ability a number of rounds per day equal to your sorcerer level, though this duration need not be continuous.

%1 rnd/day|BloodlineLVL

### Bloodline Shadow ~ Shadowstrike


At 1st level, you can make a melee touch attack as a standard action that inflicts 1d4 points of nonlethal damage + 1 for every two sorcerer levels you possess. In addition, the target is dazzled for 1 minute. Creatures with low-light vision or darkvision are not dazzled by this ability. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Shadow ~ Shadow Well


At 9th level, you can use the Stealth skill even while being observed and without cover or concealment, as long as you are within 10 feet of a shadow other than your own. In addition, when within an area of darkness or dim light, as a standard action you may choose to switch places with a willing ally within 60 feet, who must also be in darkness or dim light. At 13th level, you can instead switch the positions of two willing allies, each of whom must be within 60 feet of you. Unless otherwise noted, this travel is identical to dimension door. You may use the ability to switch places once per day at 9th level, plus one additional time per day at 17th level and 20th level.

### Bloodline Shadow ~ Enveloping Darkness


At 15th level, you may create an area of deeper darkness that you can see through without penalty. All creatures except you are entangled within this darkness unless using freedom of movement or a similar effect. You may use this ability once per day.

### Bloodline Shaitan ~ Acid Ray

- **DEFINE:** AcidRay|0
- **DEFINE:** AcidRayDie|6
- **DEFINE:** AcidDamage|0
- **BONUS:** VAR|AcidRay|1
- **BONUS:** VAR|AcidDamage|BloodlineLVL/2
- **AUTO:** EQUIP|Acid Ray

tarting at 1st level, you can unleash an elemental ray as a standard action, targeting any foe within 30 feet as a ranged touch attack. This ray deals 1d6 points of acid damage + 1 for every two sorcerer levels you possess. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

Acid ray 1d6+%1 (%2/day)|AcidicRayDamage|BloodlinePowerTimes

### Bloodline Undead ~ Grave Touch


Starting at 1st level, you can make a melee touch attack as a standard action that causes a living creature to become shaken for a number of rounds equal to 1/2 your sorcerer level (minimum 1). If you touch a shaken creature with this ability, it becomes frightened for 1 round if it has fewer Hit Dice than your sorcerer level. You can use this ability a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Undead ~ Grasp of the Dead

- **DEFINE:** GraspOfTheDeadPerDay|0
- **DEFINE:** GraspOfTheDeadDC|0
- **BONUS:** VAR|GraspOfTheDeadPerDay|1
- **BONUS:** VAR|GraspOfTheDeadPerDay|1
- **BONUS:** VAR|GraspOfTheDeadPerDay|1
- **BONUS:** VAR|GraspOfTheDeadDC|10+(BloodlineLVL/2)+CHA

t 9th level, you can cause a swarm of skeletal arms to burst from the ground to rip and tear at your foes. The skeletal arms erupt from the ground in a 20-foot-radius burst. Anyone in this area takes 1d6 points of slashing damage per sorcerer level. Those caught in the area receive a Reflex save for half damage. Those who fail the save are unable to move for 1 round. The DC of this save is equal to 10 + 1/2 your sorcerer level + your Charisma modifier. The skeletal arms disappear after 1 round. The arms must burst up from a solid surface. At 9th level, you can use this ability once per day. At 17th level, you can use this ability twice per day. At 20th level, you can use this ability three times per day. This power has a range of 60 feet.

%1/day (Ref DC %2)|GraspOfTheDeadPerDay|GraspOfTheDeadDC

### Bloodline Undead ~ Incorporeal Form


At 15th level, you can become incorporeal for 1 round per sorcerer level. While in this form, you gain the incorporeal subtype. You only take half damage from corporeal sources as long as they are magic (you take no damage from non-magic weapons and objects). Likewise, your spells deal only half damage to corporeal creatures. Spells and other effects that do not deal damage function normally. You can use this ability once per day.

### Bloodline Verdant ~ Tanglevine


At 1st level, as a standard action, you can create a 15-foot-long, animated vine that springs from your hand. This vine lasts for 1 round and can be used to make a single disarm, steal, or trip combat maneuver, using your sorcerer level plus your Charisma modifier in place of your normal CMB. You can use this power a number of times per day equal to 3 + your Charisma modifier.

%1/day|BloodlinePowerTimes

### Bloodline Verdant ~ Massmorph


At 9th level, as a full-round action, you can alter the size and health of plant life, as if using plant growth or diminish plants. Alternatively, you can transform one willing non-plant creature per sorcerer level (no two of which can be more than 30 feet apart) as tree shape. You may transform creatures as plant shape I at 15th level, or plant shape II at 20th level. You can transform non-plant creatures using this power once per day.

### Calm Emotions (Sp)

- **DEFINE:** CalmEmotionPerDay|0
- **DEFINE:** CalmEmotionsLVL|0
- **SPELLS:** Innate|TIMES=CalmEmotionsPerDay|CASTERLEVEL=CalmEmotionsLVL|Calm Emotions,12+CHA

### Freezing Spires

- **DEFINE:** FreezingSpiresPerDay|0
- **DEFINE:** FreezingSpiresDC|10+(HD/2)+CHA

%1/day (Fort DC %2)|FreezingSpiresPerDay|FreezingSpiresDC

### Regenerate (Sp)

- **DEFINE:** RegeneratePerDay|0
- **DEFINE:** RegenerateLVL|0
- **SPELLS:** Innate|TIMES=RegeneratePerDay|CASTERLEVEL=RegenerateLVL|Regenerate,17+CHA

### Detect Animals or Plants (Sp)

- **DEFINE:** DetectAnimalsOrPlantsPerDay|0
- **DEFINE:** DetectAnimalsOrPlantsLVL|0
- **SPELLS:** Innate|TIMES=DetectAnimalsOrPlantsPerDay|CASTERLEVEL=DetectAnimalsOrPlantsLVL|Detect Animals or Plants,11+CHA

### Detect Animals or Plants (Sp/atwill)

- **DEFINE:** DetectAnimalsOrPlantsLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectAnimalsOrPlantsLVL|Detect Animals or Plants,11+CHA

### Hide from Animals (Sp)

- **DEFINE:** DetectAnimalsOrPlantsPerDay|0
- **DEFINE:** HideFromAnimalsLVL|0
- **SPELLS:** Innate|TIMES=HideFromAnimalsPerDay|CASTERLEVEL=HideFromAnimalsLVL|Hide from Animals,11+CHA

### Hide from Animals (Sp/atwill)

- **DEFINE:** HideFromAnimalsLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=HideFromAnimalsLVL|Hide from Animals,11+CHA

### Final Rest (Sp)

- **DEFINE:** FinalRestPerDay|0
- **DEFINE:** FinalRestLVL|0
- **SPELLS:** Innate|TIMES=FinalRestPerDay|CASTERLEVEL=FinalRestLVL|Final Rest,11+CHA

### Bale Eye ~ Fear

- **DEFINE:** CauseFearPerDay|0
- **DEFINE:** CauseFearLVL|0
- **SPELLS:** Bale Eye|TIMES=CauseFearPerDay|CASTERLEVEL=CauseFearLVL|Cause Fear,11+CHA

### Body Equilibrium (Sp/at will)

- **DEFINE:** BodyEquilibriumLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=BodyEquilibriumLVL|Body Equilibrium

### Defensive Precognition (Sp/at will)

- **DEFINE:** DefensivePrecognitionLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DefensivePrecognitionLVL|Precognition (Defensive)

### Inertial Armor (Sp/at will)

- **DEFINE:** InertialArmorLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=InertialArmorLVL|Inertial Armor

### Wave of Fire

- **DEFINE:** WavesOfFireDC|10+CON+(HD/2)
- **BONUS:** VAR|WavesOfFireDC|2

Ref DC %1 half|WavesOfFireDC

### Whirlwind (Sp)

- **DEFINE:** WhirlwindPerDay|0
- **DEFINE:** WhirlwindLVL|0
- **SPELLS:** Innate|TIMES=WhirlwindPerDay|CASTERLEVEL=WhirlwindLVL|Whirlwind,18+CHA

### Wildstrike

- **DEFINE:** WildstrikePerDay|0

%1/day|WildstrikePerDay

### Unhallow (Sp per week)

- **DEFINE:** UnhallowPerWeek|0
- **DEFINE:** UnhallowLVL|0
- **SPELLS:** Innate|TIMES=UnhallowPerWeek|TIMEUNIT=Week|CASTERLEVEL=UnhallowLVL|Unhallow,15+CHA

### Unhallow (Sp)

- **DEFINE:** UnhallowPerDay|0
- **DEFINE:** UnhallowLVL|0
- **SPELLS:** Innate|TIMES=UnhallowPerDay|CASTERLEVEL=UnhallowLVL|Unhallow,15+CHA

### Unholy Aura (Sp)

- **DEFINE:** UnholyAuraPerDay|0
- **DEFINE:** UnholyAuraLVL|0
- **SPELLS:** Innate|TIMES=UnholyAuraPerDay|CASTERLEVEL=UnholyAuraLVL|Unholy Aura,18+CHA

### Unholy Blight (Sp)

- **DEFINE:** UnholyBlightPerDay|0
- **DEFINE:** UnholyBlightLVL|0
- **SPELLS:** Innate|TIMES=UnholyBlightPerDay|CASTERLEVEL=UnholyBlightLVL|Unholy Blight,14+CHA

### Visage of Terror

- **DEFINE:** VisageOfTerrorPerDay|0
- **DEFINE:** VisageOfTerrorDC|10+CHA

%1/day (Will DC %2)|VisageOfTerrorPerDay|VisageOfTerrorDC

### Vision (Sp)

- **DEFINE:** VisionPerDay|0
- **DEFINE:** VisionLVL|0
- **SPELLS:** Innate|TIMES=VisionPerDay|CASTERLEVEL=VisionLVL|Vision

### Wail of the Banshee (Sp)

- **DEFINE:** WailOfTheBansheePerDay|0
- **DEFINE:** WailOfTheBansheeLVL|0
- **SPELLS:** Innate|TIMES=WailOfTheBansheePerDay|CASTERLEVEL=WailOfTheBansheeLVL|Wail of the Banshee,19+CHA

### Warding

- **DEFINE:** WardingPerDay|0

%1/day|WardingPerDay

### Warp Wood (Sp/atwill/Wis)

- **DEFINE:** WarpWoodLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=WarpWoodLVL|Warp Wood,12+WIS

### Warrior Cry

- **DEFINE:** WarriorCryPerDay|0

%1/day|WarriorCryPerDay

### Tunnelport (Sp)

- **DEFINE:** TunnelportPerDay|0
- **DEFINE:** TunnelportLVL|0
- **BONUS:** VAR|DimensionDoorPerDay|TunnelportPerDay
- **BONUS:** VAR|DimensionDoorLVL|2*TunnelportLVL
- **ABILITY:** Special Ability|VIRTUAL|Dimension Door (Sp)

### Unbond

- **DEFINE:** UnbondTimes|0

%1/day|UnbondTimes

### Transfer Spell Like Ability


### Thunderous Roar

- **DEFINE:** ThunderousRoarPerDay|0

%1/day|ThunderousRoarPerDay

### Summon Archons ~ Hebdomad


2/day summon 4d10 Lantern Archons, 2d4 Sword Archons, 1d4 Trumpet Archons, 1d2 Throne Archons or another member of the Hebdomad.

### Summon Baatezu ~ Abishai


2/day summon 2d6 Lemures 50%% or random color abishai 20%%.

### Summon Baatezu ~ Advespa


1/day summon 1d2 Advespa 30%%.

### Summon Baatezu ~ Amnizu


1/day summon 1d3 Advespa or 1 Amnizu 50%%.

### Summon Baatezu ~ Ghargatula


1/day summon 1 Cornugon 25%%.

### Summon Baatezu ~ Hellfire Wyrm


1/day summon 1 Barbazu, Cornugon or Gelugon 100%%.

### Summon Baatezu ~ Kocrachon


2/day summon 1 Kocrachon 40%%.

### Summon Celestial ~ Hollyphant


1/day summon 1 Hollyphant, Asura or Avoral 45%%.

### Summon Cornugon (Sp)

- **DEFINE:** SummonCornugonPerDay|0

%1/day|SummonCornugonPerDay

### Summon Creatures (Sp)


1/day summon 1d4 Ghouls 100%% or 2d4 Dretches 60%%.

### Summon Demodand ~ Farastu


1/day summon 1d4 Farastu 30%% (result 71-100).

### Summon Demodand ~ Kelubar


1/day summon 1d2 Kelubar 40%% (result 61-100) or 1d4 Farastu 60%% (result 41-100).

### Summon Demodand ~ Shator


1/day summon 1d2 Shator 30%% (result 71-100) or 1d4 Kelubars or 1d6 Farastus 70%% (result 31-100).

### Summon Demon (Sp)

- **DEFINE:** SummonDemonPerDay|0

%1/day|SummonDemonPerDay

### Summon Dragon

- **DEFINE:** SummonDragonPerDay|0

%1/day|SummonDragonPerDay

### Summon Elemental (Sp)

- **DEFINE:** SummonElementalPerDay|0

%1/day|SummonElementalPerDay

### Summon Erinyes (Sp)

- **DEFINE:** SummonErinyesPerDay|0

%1/day|SummonErinyesPerDay

### Summon Fiend (Sp)

- **DEFINE:** SummonFiendPerDay|0

%1/day|SummonFiendPerDay

### Summon Gelugon (Sp)

- **DEFINE:** SummonGelugonPerDay|0

%1/day|SummonGelugonPerDay

### Summon Giants


### Summon Giants ~ Mountain Giant


1/day summon 1d8+1 ogres, 1d6+1 trolls, or 1d4+1 hill giants 25%%

### Summon Greater Air Elemental (Sp)

- **DEFINE:** SummonAirElementalPerDay|0

%1/day|SummonAirElementalPerDay

### Summon Hamatula (Sp)

- **DEFINE:** SummonHamatulaPerDay|0

%1/day|SummonHamatulaPerDay

### Summon Hellcat (Sp)

- **DEFINE:** SummonHellcatPerDay|0

%1/day|SummonHellcatPerDay

### Summon Huge Air Elemental (Sp)

- **DEFINE:** SummonAirElementalPerDay|0

%1/day|SummonAirElementalPerDay

### Summon Jackals ~ Jackal Lord


3/day summon 8HD of jackals.

### Summon Major Demon (Sp)

- **DEFINE:** SummonMajorDemonPerDay|0

%1/day|SummonMajorDemonPerDay

### Summon Major Devil (Sp)

- **DEFINE:** SummonMajorDevilPerDay|0

%1/day|SummonMajorDevilPerDay

### Summon Monster ~ Styx Dragon


1/day summon a fiendish giant squid, 1d3 fiendish giant octopi or large tojanidas, or 1d4+1 large water elementals, huge fiendish sharks or fiendish giant crocodile.

### Summon Monster ~ Summoning Ooze

- **DEFINE:** SummonMonsterLVL|0

1/round Summon Monster %1|SummonMonsterLVL

### Summon Night Hag (Sp)

- **DEFINE:** SummonNightHagLVL|0
- **DEFINE:** SummonNightHagTimes|0
- **SPELLS:** Innate|TIMES=SummonNightHagTimes|CASTERLEVEL=SummonNightHagLVL|Summon Monster VII

### Summon Nightwing (Sp)

- **DEFINE:** SummonNightwingPerDay|0

%1/day|SummonNightwingPerDay

### Summon Nightwing (Sp/week)

- **DEFINE:** SummonNightwingPerWeek|0

%1/week|SummonNightwingPerWeek

### Summon Ooze (Sp)

- **DEFINE:** SummonOozePerDay|0

%1/day|SummonOozePerDay

### Summon Osyluth (Sp)

- **DEFINE:** SummonOsyluthPerDay|0

%1/day|SummonOsyluthPerDay

### Summon Pudding (Sp)

- **DEFINE:** SummonPuddingPerDay|0

%1/day|SummonPuddingPerDay

### Summon Fiendish Gnoll (Sp)

- **DEFINE:** SummonFiendishGnollPerDay|0

%1/day|SummonFiendishGnollPerDay

### Summon Rilmani ~ Aurumach


1/day summon 2d4 ferrumach or 1d2 cuprilach.

### Summon Rilmani ~ Cuprilach


1/day summon 1d3 ferrumach 75%%

### Summon Rilmani ~ Ferrumach


1/day summon 1d2 ferrumach 35%%

### Summon Satyr ~ Crossroads Guardian


1/day summon 1d3 satyrs with pipes 35%%

### Summon Slaad ~ Mud Slaad


1/day summon 1 mud slaad 40%% or 1 red slaad 20%%.

### Summon Swarm (Sp)

- **DEFINE:** SummonSwarmPerDay|0
- **DEFINE:** SummonSwarmLVL|0
- **SPELLS:** Innate|TIMES=SummonSwarmPerDay|CASTERLEVEL=SummonSwarmLVL|Summon Swarm

### Summon Tanar'ri ~ Alkilith


1/day summon Herzou 50%%

### Summon Tanar'ri ~ Arrow Demon


1/day summon Arrow Demon 35%% or 1d6 Dretches 100%%

### Summon Tanar'ri ~ Babau


1/day summon Babau 40%%

### Summon Tanar'ri ~ Bar-lgura


1/day summon Bar-lgura 35%%

### Summon Tanar'ri ~ Chasm


1/day summon Rutterkin or Chasm 40%%

### Summon Tanar'ri ~ Jarilith


1/day summon Jarilith 35%%

### Summon Tanar'ri ~ Jovoc


1/day summon Jovoc 25%%

### Summon Tanar'ri ~ Kelvezu


1/day summon Kelvezu 25%%

### Summon Tanar'ri ~ Klurichir


1/day summon 4d10 Quasit, 1d6 Herzous, 2 Nalfeshnees, 2 Glabrezus, 2 Marilith or 2 Balors 100%%.

### Summon Tanar'ri ~ Myrmyxicus


1/day summon 2d6 Skulvyns or 1 Herzou 55%%

### Summon Tanar'ri ~ Palrethee


1/day summon Palrethee 30%%

### Summon Tanar'ri ~ Rutterkin


1/day summon Rutterkin 35%% or Chasm 10%%

### Summon Tempest

- **DEFINE:** SummonTempestPerWeek|0

%1/week|SummonTempestPerWeek

### Summon the Entombed

- **DEFINE:** SummonTheEntombed|0

%1/day|SummonTheEntombed

### Summon Undead (Sp)

- **DEFINE:** SummonUndeadPerDay|0

%1/day|SummonUndeadPerDay

### Summon Yugoloth ~ Arcanoloth


1/day summon Arcanoloth 40%%

### Summon Yugoloth ~ Canoloth


1/day summon Mezzoloth or 1d3 Canoloth 40%%

### Summon Yugoloth ~ Marraenoloth


1/day summon Marraenoloth 75%%

### Summon Yugoloth ~ Mezzoloth


1/day summon Mezzoloth 40%%

### Summon Yugoloth ~ Nycaloth


1/day summon Nycaloth or 1d3 Mezzoloth 30%%

### Summon Yugoloth ~ Piscoloth


2/day summon 4 Skeroloths 60%% or 1d3 Mezzoloth 35%%.

### Summon Yugoloth ~ Skeroloth


1/day summon 1 Skeroloths 40%%.

### Summon Yugoloth ~ Ultraloth


1/day summon 1d4 Nycaloth, 1d6 Mezzoloth or another Ultroloth 35%%.

### Summoning


### Sunbeam (Sp/gemstone)

- **DEFINE:** SunbeamLVL|0
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=SunbeamLVL|Sunbeam,17+CHA

1d3 times/day

### Sunburst (Sp/Wis)

- **DEFINE:** SunburstPerDay|0
- **DEFINE:** SunburstLVL|0
- **SPELLS:** Innate|TIMES=SunburstPerDay|CASTERLEVEL=SunburstLVL|Sunburst,18+WIS

### Storm of Elemental Fury

- **DEFINE:** StormElementalFuryPerDay|0

%1/day|StormElementalFuryPerDay

### Storm Ride


### Spirit Journey

- **DEFINE:** SpiritJourneyTimes|0

%1/day|SpiritJourneyTimes

### Starmantle (Sp)

- **DEFINE:** StarmantlePerDay|0
- **DEFINE:** StarmantleLVL|0
- **SPELLS:** Innate|TIMES=StarmantlePerDay|CASTERLEVEL=StarmantleLVL|Starmantle,16+CHA

### Steal (Sp)

- **DEFINE:** StealPerDay|0
- **DEFINE:** StealLVL|0
- **SPELLS:** Innate|TIMES=StealPerDay|CASTERLEVEL=StealLVL|Telekinesis,15+CHA

max 5 punds.

### Steal SpellLike Ability


### Sticks to Snakes (Sp)

- **DEFINE:** SticksToSnakesPerDay|0
- **DEFINE:** SticksToSnakesLVL|0
- **SPELLS:** Innate|TIMES=SticksToSnakesPerDay|CASTERLEVEL=SticksToSnakesLVL|Sticks to Snakes,14+CHA

### Sticky Pads

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=20|Spider Climb

### Spell Fury

- **DEFINE:** SpellFuryTimes|0

%1/rage|SpellFuryTimes

### Spell Mimic

- **DEFINE:** SpellMimicPerDay|0

%1/day|SpellMimicPerDay

### Spellcast


### Spew Vermin (Sp)

- **SERVESAS:** ABILITY=Special Ability|Breath Weapon
- **DEFINE:** SpewVerminCone|0
- **DEFINE:** SpewVerminDice|0
- **DEFINE:** SpewVerminDamageDie|0
- **DEFINE:** SpewVerminDC|10+CON
- **BONUS:** VAR|SpewVerminDC|2

%1' Spew Vermin (Sp) %2d%3 DC %4|SpewVerminCone|SpewVerminDice|SpewVerminDamageDie|SpewVerminDC

### Spider Hand (Sp)

- **DEFINE:** SpiderHandPerDay|0
- **DEFINE:** SpiderHandLVL|0

%1/day|SpiderHandPerDay

### Spider Legs (Sp)

- **DEFINE:** SpiderLegsPerDay|0
- **DEFINE:** SpiderLegsLVL|0
- **SPELLS:** Innate|TIMES=SpiderLegsPerDay|CASTERLEVEL=SpiderLegsLVL|Spider Legs,11+CHA

### Speak with Dead Animals

- **DEFINE:** SpeakDeadAnimalTimes|0

%1/day|SpeakDeadAnimalTimes

### Snake Darts (Sp)

- **DEFINE:** SnakeDartsPerDay|0
- **DEFINE:** SnakeDartsLVL|0
- **SPELLS:** Innate|TIMES=SnakeDartsPerDay|CASTERLEVEL=SnakeDartsLVL|Snake Darts,14+CHA

### Sorcerous Knack

- **DEFINE:** SorcerousKnackPerDay|0

%1/Day|SorcerousKnackPerDay

### Sleep Dance

- **DEFINE:** SleepDancePerDay|0
- **DEFINE:** SleepDanceDC|10+CHA

%1/day (Will DC %2)|SleepDancePerDay|SleepDanceDC

### Sleep Dust


10'ft radius (Fort save DC %1)|10+(HD/2)+CON

### Shield of Prudence

- **DEFINE:** ShieldOfPrudence|0

%1/day|ShieldOfPrudence

### Sense Elements


### Sense Link

- **DEFINE:** SenseLinkDC|13+CHA

Will DC %1|SenseLinkDC

### Shadow Image (Sp)


### Shadow Stride (Sp)


### Shadow Travel (Sp)


### Shadow Walk (Sp) Nep

- **DEFINE:** ShadowWalkLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=ShadowWalkLVL|Shadow Walk,13+CHA

### Shadow Walk (Sp)

- **DEFINE:** ShadowWalkLVL|0
- **DEFINE:** ShadowWalkTimes|0
- **SPELLS:** Innate|TIMES=ShadowWalkTimes|CASTERLEVEL=ShadowWalkLVL|Shadow Walk,15+CHA

### Shield Master


### Searing Light (Sp)

- **DEFINE:** SearingLightLVL|0
- **DEFINE:** SearingLightPerDay|0
- **SPELLS:** Innate|TIMES=SearingLightPerDay|CASTERLEVEL=SearingLightLVL|Searing Light,13+CHA

### Searing Light (Sp/round)


once per round, as long as Radiant Aura is in effect.

### Sandman's Gift


### Sands of Sleep

- **DEFINE:** SandOfSleepDC|10+CHA+(HD/2)
- **BONUS:** VAR|SandOfSleepDC|2

Will DC %1|SandOfSleepDC

### Scry on Cultist


once per day Scry on any creature that have sworn a blood oath with the fiend.

### Reefwalking

- **DEFINE:** ReefwalkingPerDay|WIS

%1/day|ReefwalkingPerDay

### Reflective Pulse

- **DEFINE:** ReflectivePulsePerDay|0

%1/day|ReflectivePulsePerDay

### Reflective Spell Resistance

- **DEFINE:** ReflectiveSR|0

%1|ReflectiveSR

### Riddle ~ Apocripha

- **DEFINE:** RiddleApocryphaPerWeek|0

%1/weeks|RiddleApocryphaPerWeek

### Riddle ~ Conundrum

- **DEFINE:** RiddleConundrumPerDay|0

%1/day|RiddleConundrumPerDay

### Riddle ~ Enigma

- **DEFINE:** RiddleEnigmaPerWeek|0

%1/weeks|RiddleEnigmaPerWeek

### Riddle ~ Koan

- **DEFINE:** RiddleKoanPerDay|0

%1/day|RiddleKoanPerDay

### Riddle ~ Mystery

- **DEFINE:** RiddleMysteryPerDay|0

%1/day|RiddleMysteryPerDay

### Rotting Touch (Sp)

- **DEFINE:** RottingTouchPerDay|0

%1/day|RottingTouchPerDay

### Runic Spell


### Rusting Grasp (Sp)

- **DEFINE:** RustingGraspPerDay|0
- **DEFINE:** RustingGraspLVL|0
- **SPELLS:** Innate|TIMES=RustingGraspPerDay|CASTERLEVEL=RustingGraspLVL|Rusting Grasp,11+CHA

### Reactive Warding


### Read Thoughts (Sp)

- **DEFINE:** ReadThoughtsPower|0
- **DEFINE:** ReadThoughtsPerDay|0
- **DEFINE:** ReadThoughtsDC|10+INT

%1/day (Will DC %2)|ReadThoughtsPerDay|ReadThoughtsDC

At will (Will DC %1)|ReadThoughtsDC

### Recall Spirit

- **DEFINE:** RecallSpiritTimes|0

%1/week|RecallSpiritTimes

### Protective Aura (Sp)

- **DEFINE:** ProtectiveAuraPerDay|0

%1/day|ProtectiveAuraPerDay

### Push the Weak Mind

- **DEFINE:** PushWeakMindPerDay|0

%1/day|PushWeakMindPerDay

### Polar Ray (Sp)

- **DEFINE:** PolarRayPerDay|0
- **DEFINE:** PolarRayLVL|0
- **SPELLS:** Innate|TIMES=PolarRayPerDay|CASTERLEVEL=PolarRayLVL|Polar Ray,18+CHA

### Polymorph Rend


6d6 dmage touch attack to polymorphed creature.

### Permanent Item Drain


### Phagocytize Dreams


permanent drain 2 INT, WIS, CHA.

### Phase Door (Sp)

- **DEFINE:** PhaseDoorPerDay|0
- **DEFINE:** PhaseDoorLVL|0
- **SPELLS:** Innate|TIMES=PhaseDoorPerDay|CASTERLEVEL=PhaseDoorLVL|Phase Door,17

%1/day|PhaseDoorPerDay

### Planar Tracking (Sp)

- **DEFINE:** PlanarTrackingLVL|0
- **DEFINE:** PlanarTrackingTimes|0
- **SPELLS:** Innate|TIMES=PlanarTrackingTimes|CASTERLEVEL=PlanarTrackingLVL|Plane Shift

### Mind Blast

- **DEFINE:** MindBlastCone|0
- **DEFINE:** MindBlastDice|0
- **DEFINE:** MindBlastDamageDie|0
- **DEFINE:** MindBlastDC|10+(HD/2)+CON
- **BONUS:** VAR|MindBlastDC|2

%1' Cone of Cold %2d%3 cold DC %4|MindBlastCone|MindBlastDice|MindBlastDamageDie|MindBlastDC

### Mind Blast (Sp)

- **DEFINE:** MindBlastDC|14+CHA

Will DC %1|MindBlastDC

### Mind Probe (Sp)

- **DEFINE:** MindProbePerDay|0
- **DEFINE:** MindProbeDC|10+INT

%1/day (Will DC %2)|MindProbePerDay|MindProbeDC

### Mind Reading

- **DEFINE:** MindReadingDC|10+(HD/2)+CHA

Will DC %1|MindReadingDC

### Mindread

- **DEFINE:** MindreadPerDay|0

%1/day|MindreadPerDay

### Moment of Prescience (Sp)

- **DEFINE:** MomentOfPresciencePerDay|0
- **DEFINE:** MomentOfPrescienceLVL|0
- **SPELLS:** Innate|TIMES=MomentOfPresciencePerDay|CASTERLEVEL=MomentOfPrescienceLVL|Moment of Prescience

### Multiple Channel Spell


### Mark of Justice (Sp)

- **DEFINE:** MarkOfJusticePerDay|0
- **DEFINE:** MarkOfJusticeLVL|0
- **SPELLS:** Innate|TIMES=MarkOfJusticePerDay|CASTERLEVEL=MarkOfJusticeLVL|Mark of Justice,14+CHA

### Mass Aversion (Sp)

- **DEFINE:** MassAversionDC|18+CHA

Will DC %1|MassAversionDC

### Mass Baleful Polymorph (Sp)

- **DEFINE:** MassBalefulPolymorphPerDay|0
- **DEFINE:** MassBalefulPolymorphLVL|0
- **SPELLS:** Innate|TIMES=MassBalefulPolymorphPerDay|CASTERLEVEL=MassBalefulPolymorphLVL|Baleful Polymorph (Mass),15+WIS

### Mass Cure Light Wounds

- **DEFINE:** MassCureLightWoundsTimes|0
- **DEFINE:** MassCureLightWoundsLVL|0
- **SPELLS:** Innate|TIMES=MassCureLightWoundsTimes|CASTERLEVEL=MassCureLightWoundsLVL|Cure Light Wounds (Mass),15+WIS

### Mass Heal (Sp)

- **DEFINE:** MassHealTimes|0
- **DEFINE:** MassHealLVL|0
- **SPELLS:** Innate|TIMES=MassHealTimes|CASTERLEVEL=MassHealLVL|Heal (Mass),19+WIS

### Lore of the Stones


### Lose the Way

- **DEFINE:** LoseTheWayPerDay|0

%1/day|LoseTheWayPerDay

### Lurue's Voice (Sp)

- **DEFINE:** LurueVoiceLVL|0
- **SPELLS:** Innate|TIMES=3|CASTERLEVEL=LurueVoiceLVL|Speak with Animals,11+CHA

### Lightning

- **DEFINE:** LightningPerDay|0
- **DEFINE:** LightningDuration|0

%1/day %2 rounds|LightningPerDay|LightningDuration

### Lightning Bolt

- **DEFINE:** LightningBoltRange|0
- **DEFINE:** LightningBoltDamageDie|0
- **DEFINE:** LigtningBoltDC|13+CHA

Once every 2 rounds %1-ft Ligntning Bolt %2d6 (Reflex DC %3)|LightningBoltRange|LightningBoltDamageDie|LigtningBoltDC

### Joie de Vivre (Sp)

- **DEFINE:** GoodHopePerDay|0
- **DEFINE:** GoodHopeLVL|0
- **SPELLS:** Innate|TIMES=GoodHopePerDay|CASTERLEVEL=GoodHopeLVL|Demon Wings,10+CHA

### Kaleidoscopic Doom

- **DEFINE:** KaleidoscopicDoomPerDay|0

%1/day|KaleidoscopicDoomPerDay

### Lesser Geas (Sp)

- **DEFINE:** LesserGeasPerDay|0
- **DEFINE:** LesserGeasLVL|0
- **SPELLS:** Innate|TIMES=LesserGeasPerDay|CASTERLEVEL=LesserGeasLVL|Geas (Lesser)

### Lift


### Invocation

- **DEFINE:** InvocationDC|10+CHA
- **DEFINE:** InvocationLVL|0
- **BONUS:** VAR|InvocationDC|2

### Iron Body (Sp)

- **DEFINE:** IronBodyPerDay|0
- **DEFINE:** IronBodyLVL|0
- **SPELLS:** Innate|TIMES=IronBodyPerDay|CASTERLEVEL=IronBodyLVL|Iron Body,18+CHA

### Ice Runes


### Ice Skate (Sp)

- **DEFINE:** IceSkatePerDay|0
- **DEFINE:** IceSkateLVL|0
- **SPELLS:** Innate|TIMES=IceSkatePerDay|CASTERLEVEL=IceSkateLVL|Ice Skate,11+CHA

### Iceberg (Sp)

- **DEFINE:** IcebergPerDay|0
- **DEFINE:** IcebergLVL|0
- **SPELLS:** Innate|TIMES=IcebergPerDay|CASTERLEVEL=IcebergLVL|Iceberg,19+CHA

### Icy Greataxe

- **DEFINE:** IcyGreataxeDuration|0

%1 rounds/day|IcyGreataxeDuration

### Identification (Sp)


### Imbue With Spell Ability (Sp)

- **DEFINE:** ImbueWithSpellAbilityTimes|0
- **DEFINE:** ImbueWithSpellAbilityLVL|0
- **SPELLS:** Innate|TIMES=ImbueWithSpellAbilityTimes|CASTERLEVEL=ImbueWithSpellAbilityLVL|Imbue with Spell Ability,14+WIS

### Imbuement


### Incendiary Cloud (Sp)

- **DEFINE:** IncendiaryCloudPerDay|0
- **DEFINE:** IncendiaryCloudLVL|0
- **SPELLS:** Innate|TIMES=IncendiaryCloudPerDay|CASTERLEVEL=IncendiaryCloudLVL|Incendiary Cloud,18+CHA

### Incite Madness

- **DEFINE:** InciteMadnessDC|10+(HD/2)+CHA

Will DC %1|InciteMadnessDC

### Hold Demon (Sp)

- **DEFINE:** HoldDemonPerDay|0
- **DEFINE:** HoldDemonLVL|0
- **SPELLS:** Innate|TIMES=HoldDemonPerDay|CASTERLEVEL=HoldDemonLVL|Hold Person,12+CHA

### Healing Touch (Sp)


### Hellfire Storm (Sp)

- **DEFINE:** HellfireStormPerDay|0
- **DEFINE:** HellfireStormLVL|0
- **SPELLS:** Innate|TIMES=HellfireStormPerDay|CASTERLEVEL=HellfireStormLVL|Hellfire Storm,17+CHA

### Hide from Dragons (Sp)

- **DEFINE:** HideFromDragonsPerDay|0
- **DEFINE:** HideFromDragonsLVL|0
- **SPELLS:** Innate|TIMES=HideFromDragonsPerDay|CASTERLEVEL=HideFromDragonsLVL|Hide from Dragons,17+CHA

### Hellfire (Sp)

- **DEFINE:** HellfirePerDay|0
- **DEFINE:** HellfireLVL|0
- **SPELLS:** Innate|TIMES=HellfirePerDay|CASTERLEVEL=HellfireLVL|Hellfire,14+CHA

### Greater Glyph of Warding (Sp)

- **DEFINE:** GreaterGlyphOfWardingLVL|0
- **DEFINE:** GreaterGlyphOfWardingPerDay|0
- **SPELLS:** Innate|TIMES=GreaterGlyphOfWardingPerDay|CASTERLEVEL=GreaterGlyphOfWardingLVL|Glyph of Warding (Greater),16+CHA

### Greater Permanent Item Drain


### Greater Tunnelport (Sp)

- **DEFINE:** GreaterTunnelportPerDay|0
- **DEFINE:** GreaterTunnelportLVL|0
- **BONUS:** VAR|GreaterTeleportPerDay|GreaterTunnelportPerDay
- **BONUS:** VAR|GreaterTeleportLVL|2*GreaterTunnelportLVL
- **ABILITY:** Special Ability|VIRTUAL|Greater Teleport (Sp)

### Greater Charged Item Drain


### Glory of the Martyr (Sp)

- **DEFINE:** GloryOfTheMartyrPerDay|0
- **DEFINE:** GloryOfTheMartyrLVL|0
- **SPELLS:** Innate|TIMES=GloryOfTheMartyrPerDay|CASTERLEVEL=GloryOfTheMartyrLVL|Glory of the Martyr,14+CHA

### Frost Greataxe

- **DEFINE:** FrostGreataxeDuration|0

%1 rounds/day|FrostGreataxeDuration

### For Medicinal Purpose (Sp)

- **DEFINE:** MedicinalPurposePerDay|0

%1/day|MedicinalPurposePerDay

### Fish Cloud (Sp)


### Flare (Sp)

- **DEFINE:** FlarePerDay|0
- **DEFINE:** FlareLVL|0
- **SPELLS:** Innate|TIMES=FlarePerDay|CASTERLEVEL=FlareLVL|Flare,10+CHA

### Flight (Sp)


the flight is magical, as per Fly spell, but with creature's original fly speed.

### Flirtation ~ Suggestion (Sp)


### Fiery Shield


### Find the Path (Sp)

- **DEFINE:** FindThePathPerDay|0
- **DEFINE:** FindThePathLVL|0
- **SPELLS:** Innate|TIMES=FindThePathPerDay|CASTERLEVEL=FindThePathLVL|Find the Path,16+WIS

%1/day|FindThePathPerDay

### Fateful Stride

- **DEFINE:** FatefulStrideTimes|0

%1/day|FatefulStrideTimes

### Favored of the Spirits


### Evil Authority

- **DEFINE:** EvilAuthorityPerDay|0
- **DEFINE:** EvilAuthorityDC|10+CHA

%1/day (Will DC %2)|EvilAuthorityPerDay|EvilAuthorityDC

### Explosive Gem

- **DEFINE:** ExplosivesGemsDice|0
- **DEFINE:** ExplosivesGemsDC|0

%1d6 (Ref DC %2 half)|ExplosivesGemsDice|ExplosivesGemsDC

### Eye of Fear (Sp)

- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=15|Fear,13+CHA

### Eye of Flame (Sp)


%1/3 rounds, Fireball, 15th casterlevel (Ref DC %1)|13+CHA

### False Vision

- **DEFINE:** FalseVisionTimes|0

%1/day|FalseVisionTimes

### Enthrall (Sp)

- **DEFINE:** EnthrallPerDay|0
- **DEFINE:** EnthrallLVL|0
- **SPELLS:** Innate|TIMES=EnthrallPerDay|CASTERLEVEL=EnthrallLVL|Enthrall,12+CHA

### Enthralling Dance

- **DEFINE:** EnthrallingDancePerDay|0
- **DEFINE:** EnthrallingDanceDC|10+CHA

%1/day (Will DC %2)|EnthrallingDancePerDay|EnthrallingDanceDC

### Eternal Charm

- **DEFINE:** EternalCharmNumber|0

%1 creature|EternalCharmNumber

### Ego Manifestation

- **DEFINE:** EgoManifestationPerDay|0

%1/day|EgoManifestationPerDay

### Eladrin Form (Sp)

- **DEFINE:** EladrinFormPerDay|0
- **DEFINE:** EladrinFormLVL|0
- **SPELLS:** Innate|TIMES=EladrinFormPerDay|CASTERLEVEL=EladrinFormLVL|Eladrin Form,17+CHA

### Elder Glyph of Warding (Sp)

- **DEFINE:** ElderGlyphOfWardingLVL|0
- **DEFINE:** ElderGlyphOfWardingPerDay|0
- **SPELLS:** Innate|TIMES=ElderGlyphOfWardingPerDay|CASTERLEVEL=ElderGlyphOfWardingLVL|Glyph of Warding (Elder),19+CHA

### Eldritch Blast

- **DEFINE:** EldritchBlastDie|6
- **DEFINE:** EldritchBlast|0
- **AUTO:** EQUIP|Eldritch Blast
- **ASPECT:** Ability Benefit|+%1d%2|EldritchBlast|EldritchBlastDie

+%1d%2|EldritchBlast|EldritchBlastDie

### Emerald Gates


### Earth's Blood

- **DEFINE:** EarthsBloodPerDay|0

%1/day|EarthsBloodPerDay

### Dreaming Vision


### Drinking Blood


### Dominate Person (Sp)

- **DEFINE:** DominatePersonPerDay|0
- **DEFINE:** DominatePersonLVL|0
- **SPELLS:** Innate|TIMES=DominatePersonPerDay|CASTERLEVEL=DominatePersonLVL|Dominate Person,15+CHA

### Dominate Spawn

- **DEFINE:** DominateSpawnDC|10+CON

Will DC %1|DominateSpawnDC

### Dominate Animal (Sp)

- **DEFINE:** DominateAnimalPerDay|0
- **DEFINE:** DominateAnimalLVL|0
- **SPELLS:** Innate|TIMES=DominateAnimalPerDay|CASTERLEVEL=DominateAnimalLVL|Dominate Animal,13+CHA

### Dominate Animal (Sp/at will/WIS)

- **DEFINE:** DominateAnimalLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DominateAnimalLVL|Dominate Animal,13+WIS

### Dominate Demon (Sp)

- **DEFINE:** DominateDemonPerDay|0
- **DEFINE:** DominateDemonLVL|0
- **SPELLS:** Innate|TIMES=DominateDemonPerDay|CASTERLEVEL=DominateDemonLVL|Dominate Person,15+CHA

### Dispelling Blast

- **DEFINE:** DispellingBlastPerDay|3

%1/day|DispellingBlastPerDay

### Dispelling Touch


### Commune with Dragon Spirit (Sp)


### Animate Vines (Sp)


### Blessed Sight (Sp always active)


always active

### Blood of the Martyr (Sp)

- **DEFINE:** BloodOfTheMartyrPerDay|0
- **DEFINE:** BloodOfTheMartyrLVL|0
- **SPELLS:** Innate|TIMES=BloodOfTheMartyrPerDay|CASTERLEVEL=BloodOfTheMartyrLVL|Blood of the Martyr,14+CHA

### Bone of the Earth (Sp)

- **DEFINE:** BonesOfEarthLVL|0
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=BonesOfEarthLVL|Shadow Walk,16+CHA

### Breath of Flame (Sp)

- **SERVESAS:** ABILITY=Special Ability|Breath Weapon
- **DEFINE:** BreathOfFlameCone|0
- **DEFINE:** BreathOfFlameDice|0
- **DEFINE:** BreathOfFlameDamageDie|0
- **DEFINE:** BreathOfFlameDC|10+CON
- **BONUS:** VAR|BreathOfFlameDC|2

%1' Breath of Flame (Sp) %2d%3 Fire DC %4|BreathOfFlameCone|BreathOfFlameDice|BreathOfFlameDamageDie|BreathOfFlameDC

### Cavalry of Dire Bears (Sp)

- **DEFINE:** CavalryOfDireBearsPerWeek|0

%1/week|CavalryOfDireBearPerWeek

### Celestial Brilliance (Sp)

- **DEFINE:** CelestialBrilliancePerDay|0
- **DEFINE:** CelestialBrillianceLVL|0
- **SPELLS:** Innate|TIMES=CelestialBrilliancePerDay|CASTERLEVEL=CelestialBrillianceLVL|Celestial Brilliance,14+CHA

### Charm Demon (Sp)

- **DEFINE:** CharmDemonPerDay|0
- **DEFINE:** CharmDemonLVL|0
- **SPELLS:** Innate|TIMES=CharmDemonPerDay|CASTERLEVEL=CharmDemonLVL|Charm Person,11+CHA

### Cheat (Sp)

- **DEFINE:** CheatPerDay|0
- **DEFINE:** CheatLVL|0
- **SPELLS:** Innate|TIMES=CheatPerDay|CASTERLEVEL=CheatLVL|Cheat,11+CHA

### Clutch of Orcus (Sp)

- **DEFINE:** ClutchOfOrcusPerDay|0
- **DEFINE:** ClutchOfOrcusLVL|0
- **SPELLS:** Innate|TIMES=ClutchOfOrcusPerDay|CASTERLEVEL=ClutchOfOrcusLVL|Clutch of Orcus,13+CHA

### Color Spray (Sp)

- **DEFINE:** ColorSprayPerDay|0
- **DEFINE:** ColorSprayLVL|0
- **SPELLS:** Innate|TIMES=ColorSprayPerDay|CASTERLEVEL=ColorSprayLVL|Color Spray,11+CHA

### Command (Greater/Sp)

- **DEFINE:** GreaterCommandPerDay|0
- **DEFINE:** GreaterCommandLVL|0
- **SPELLS:** Innate|TIMES=GreaterCommandPerDay|CASTERLEVEL=GreaterCommandLVL|Command (Greater),15+CHA

### Command Ooze (Sp)

- **DEFINE:** CommandOozeDC|10+(HD/2)+CHA

Will DC %1|CommandOozeDC

### Control Flames (Sp)

- **DEFINE:** ControlFlamesPerDay|0
- **DEFINE:** ControlFlamesLVL|0
- **SPELLS:** Innate|TIMES=ControlFlamesPerDay|CASTERLEVEL=ControlFlamesLVL|Control Flames,10+CHA

### Control Light (Sp)


### Defensive Aura

- **DEFINE:** DefensiveAuraBonus|0
- **BONUS:** COMBAT|AC|DefensiveAuraBonus|TYPE=Deflection

+%1 deflection bonus on AC.

### Deforestation


### Demogorgon's Will (Sp)

- **DEFINE:** DemogorgonSWillPerDay|0

%1/day|DemogorgonSWillPerDay

### Destroy Impious Receptacle

- **DEFINE:** DestroyImpiousReceptaclePerWeek|0

%1/week|DestroyImpiousReceptaclePerWeek

### Destruction (Sp)

- **DEFINE:** DestructionPerDay|0
- **DEFINE:** DestructionLVL|0
- **SPELLS:** Innate|TIMES=DestructionPerDay|CASTERLEVEL=DestructionLVL|Destruction,17+CHA

### Detect Aberrant Taint


### Detect Chaos

- **DEFINE:** DetectChaosLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectChaosLVL|Detect Chaos,11+WIS

### Detect Chaos (Sp)

- **DEFINE:** DetectChaosPerDay|0
- **DEFINE:** DetectChaosLVL|0
- **SPELLS:** Innate|TIMES=DetectChaosPerDay|CASTERLEVEL=DetectChaosLVL|Detect Chaos,11+CHA

### Detect Evil (Sp always active)


always active

### Detect Fire (Sp/atwill/wis)

- **DEFINE:** DetectFireLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectFireLVL|Detect Fire,11+WIS

### Detect Law (Sp always active)


always active

### Detect Lies

- **DEFINE:** DetectLiesLVL|0
- **SPELLS:** Innate|TIMES=1|CASTERLEVEL=DetectLiesLVL|Discern Lies,13+WIS

### Detect Living (Sp)

- **DEFINE:** DetectLivingPerDay|0

%1/day|DetectLivingPerDay

### Detect Magic (Sp always active)


always active

### Detect Magic (Sp at will)

- **DEFINE:** DetectMagicWillLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectMagicWillLVL|Detect Magic,11+WIS

### Detect Magic (Sp)

- **DEFINE:** DetectMagicLVL|0
- **DEFINE:** DetectMagicPerDay|0
- **SPELLS:** Innate|TIMES=DetectMagicPerDay|CASTERLEVEL=DetectMagicLVL|Detect Magic,11+CHA

### Detect Minion of Iborighu


### Detect Mortals (Sp)


### Detect Poison (Sp/atwill)

- **DEFINE:** DetectPoisonLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectPoisonLVL|Detect Poison

### Detect Snares and Pits (Sp always active)


always active

### Detect Spirits

- **DEFINE:** DetectSpiritLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectSpiritLVL|Detect Spirits,11+WIS

### Detect Thoughts (Sp)

- **DEFINE:** DetectThoughtsPerDay|0
- **DEFINE:** DetectThoughtsLVL|0
- **SPELLS:** Innate|TIMES=DetectThoughtsPerDay|CASTERLEVEL=DetectThoughtsLVL|Detect Thoughts,11+CHA

### Detect Thoughts (Sp/atwill)

- **DEFINE:** DetectThoughtsLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectThoughtsLVL|Detect Thoughts,11+CHA

### Detect Thoughts (Sp/Scourge)

- **SERVESAS:** ABILITY=Special Ability|Detect Thoughts (Sp)
- **DEFINE:** DetectThoughtsPerDay|0
- **DEFINE:** DetectThoughtsLVL|0
- **DEFINE:** DetectThoughtsDC|0
- **SPELLS:** Innate|TIMES=DetectThoughtsPerDay|CASTERLEVEL=DetectThoughtsLVL|Detect Thoughts,11+CHA+DetectThoughtsDC

### Detect Treasure

- **DEFINE:** DetectTreasurePerDay|0

%1/day|DetectTreasurePerDay

### Detect Undead (Sp)

- **DEFINE:** DetectUndeadLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DetectUndeadLVL|Detect Undead,11+WIS

### Dimension Door (Sp)

- **DEFINE:** DimensionDoorPerDay|0
- **DEFINE:** DimensionDoorLVL|0
- **SPELLS:** Innate|TIMES=DimensionDoorPerDay|CASTERLEVEL=DimensionDoorLVL|Dimension Door

### Dimensional Anchor (Sp)

- **DEFINE:** DimensionalAnchorPerDay|0
- **DEFINE:** DimensionalAnchorLVL|0
- **SPELLS:** Dimensional Anchor|TIMES=DimensionalAnchorPerDay|CASTERLEVEL=DimensionalAnchorLVL|Dimensional Anchor

### Discern Lies

- **DEFINE:** DiscernLiesTimes|0

%1/day|DiscernLiesTimes

### Discern Lies (Sp always active)


always active

### Discern Location

- **DEFINE:** DiscernLocationPerDay|0
- **DEFINE:** DiscernLocationLVL|0
- **SPELLS:** Innate|TIMES=DiscernLocationPerDay|CASTERLEVEL=DiscernLocationLVL|Discern Location,18+WIS

%1/day|DiscernLocationPerDay

### Dispel Fire (Sp/wis)

- **DEFINE:** DispelFirePerDay|0
- **DEFINE:** DispelFireLVL|0
- **SPELLS:** Innate|TIMES=DispelFirePerDay|CASTERLEVEL=DispelFireLVL|Dispel Fire,15+WIS

##  Datacontrols

### DEFAULTVARIABLEVALUE:ORDEREDPAIR|0,0


### DEFAULTVARIABLEVALUE:NUMBER|0


### DEFAULTVARIABLEVALUE:BOOLEAN|False


### DEFAULTVARIABLEVALUE:STRING|


### DEFAULTVARIABLEVALUE:DICE|0


### DEFAULTVARIABLEVALUE:ALIGNMENT|None


### DEFAULTVARIABLEVALUE:HANDED|Right


### DEFAULTVARIABLEVALUE:DEITY|None


### FACTDEF:RACE|BaseSize

- **DATAFORMAT:** SIZEADJUSTMENT
- **REQUIRED:** NO
- **EXPLANATION:** All Races must have a Size - in the case of multiple sizes, use the SMALLEST allowed.

### FACTDEF:RACE|IsPC

- **DATAFORMAT:** BOOLEAN
- **REQUIRED:** NO
- **EXPLANATION:** Determine if the Race is meant to be PC playable.

### FACTDEF:ABILITY|AppliedName

- **DATAFORMAT:** String

### FACTDEF:CLASS|Abb

- **DATAFORMAT:** String

### FACTDEF:CLASS|ClassType

- **DATAFORMAT:** String

### FACTDEF:CLASS|SpellType

- **DATAFORMAT:** String
- **SELECTABLE:** YES

### FACTDEF:DEITY|Symbol

- **DATAFORMAT:** String

### FACTDEF:DEITY|Worshippers

- **DATAFORMAT:** String

### FACTDEF:DEITY|Title

- **DATAFORMAT:** String

### FACTDEF:DEITY|Appearance

- **DATAFORMAT:** String

### FACTDEF:DEITY|Domain

- **DATAFORMAT:** String

### FACTDEF:EQUIPMENT|RateOfFire

- **DATAFORMAT:** String

### FACTDEF:TEMPLATE|AppliedName

- **DATAFORMAT:** String

### FACTSETDEF:DEITY|Pantheon

- **DATAFORMAT:** String
- **SELECTABLE:** YES

### FACTSETDEF:DEITY|Race

- **DATAFORMAT:** String

### FACTDEF:ABILITY|HasWalk

- **DATAFORMAT:** BOOLEAN

### FACTDEF:ABILITY|HasFly

- **DATAFORMAT:** BOOLEAN

### FACTDEF:ABILITY|HasBurrow

- **DATAFORMAT:** BOOLEAN

### FACTDEF:ABILITY|HasSwim

- **DATAFORMAT:** BOOLEAN

### FACTDEF:ABILITY|HasClimb

- **DATAFORMAT:** BOOLEAN

### FACTDEF:ABILITY|ReplacesBackgroundFeature

- **DATAFORMAT:** BOOLEAN

### FACTDEF:STAT|Abb

- **DATAFORMAT:** STRING
- **EXPLANATION:** Output the STAT Abbreviation

## Special Abilities

### Movement Mode


### Movement Mode ~ Walk

- **BONUS:** MOVEADD|TYPE.Walk|Move_Walk

### Movement Mode ~ Swim

- **BONUS:** MOVEADD|TYPE.Swim|Move_Swim

### Movement Mode ~ Fly

- **BONUS:** MOVEADD|TYPE.Fly|Move_Fly

### Movement Mode ~ Climb

- **BONUS:** MOVEADD|TYPE.Climb|Move_Climb

### Movement Mode ~ Burrow

- **BONUS:** MOVEADD|TYPE.Burrow|Move_Burrow

### REACH_0

- **TEMPLATE:** REACH_0

### REACH_5

- **TEMPLATE:** REACH_5

### REACH_10

- **TEMPLATE:** REACH_10

### REACH_15

- **TEMPLATE:** REACH_15

### REACH_20

- **TEMPLATE:** REACH_20

### REACH_30

- **TEMPLATE:** REACH_30

### FACE_0

- **TEMPLATE:** FACE_0

### FACE_1

- **TEMPLATE:** FACE_1

### FACE_2

- **TEMPLATE:** FACE_2

### FACE_5

- **TEMPLATE:** FACE_5

### FACE_10

- **TEMPLATE:** FACE_10

### FACE_15

- **TEMPLATE:** FACE_15

### FACE_20

- **TEMPLATE:** FACE_20

### FACE_30

- **TEMPLATE:** FACE_30

### SIZE_F

- **TEMPLATE:** SIZE_F

### SIZE_D

- **TEMPLATE:** SIZE_D

### SIZE_T

- **TEMPLATE:** SIZE_T

### SIZE_S

- **TEMPLATE:** SIZE_S

### SIZE_M

- **TEMPLATE:** SIZE_M

### SIZE_L

- **TEMPLATE:** SIZE_L

### SIZE_H

- **TEMPLATE:** SIZE_H

### SIZE_G

- **TEMPLATE:** SIZE_G

### SIZE_C

- **TEMPLATE:** SIZE_C

### SIZE_C+

- **TEMPLATE:** SIZE_C+

### Bypass Size Mods

- **BONUS:** VAR|BypassSizeMods|1|TYPE=Boolean

### Size Tracker

- **DEFINE:** BaseSize|0
- **DEFINE:** CurrentSize|0
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Fine
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Diminutive
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Tiny
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Small
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Medium
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Large
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Huge
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Gargantuan
- **ABILITY:** Internal|AUTOMATIC|Base Size ~ Colossal
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Fine
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Diminutive
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Tiny
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Small
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Medium
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Large
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Huge
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Gargantuan
- **ABILITY:** Internal|AUTOMATIC|Current Size ~ Colossal
- **DEFINE:** SizeIncrease|0
- **DEFINE:** SizeDecrease|0
- **BONUS:** VAR|SizeIncrease|max(0,CurrentSize-BaseSize)
- **BONUS:** VAR|SizeDecrease|max(0,BaseSize-CurrentSize)

### Current Size ~ Fine

- **BONUS:** VAR|CurrentSize|1|TYPE=Base

### Current Size ~ Diminutive

- **BONUS:** VAR|CurrentSize|2|TYPE=Base

### Current Size ~ Tiny

- **BONUS:** VAR|CurrentSize|3|TYPE=Base

### Current Size ~ Small

- **BONUS:** VAR|CurrentSize|4|TYPE=Base

### Current Size ~ Medium

- **BONUS:** VAR|CurrentSize|5|TYPE=Base

### Current Size ~ Large

- **BONUS:** VAR|CurrentSize|6|TYPE=Base

### Current Size ~ Huge

- **BONUS:** VAR|CurrentSize|7|TYPE=Base

### Current Size ~ Gargantuan

- **BONUS:** VAR|CurrentSize|8|TYPE=Base

### Current Size ~ Colossal

- **BONUS:** VAR|CurrentSize|9|TYPE=Base

### Base Size ~ Fine

- **BONUS:** VAR|BaseSize|1|TYPE=Base

### Base Size ~ Diminutive

- **BONUS:** VAR|BaseSize|2|TYPE=Base

### Base Size ~ Tiny

- **BONUS:** VAR|BaseSize|3|TYPE=Base

### Base Size ~ Small

- **BONUS:** VAR|BaseSize|4|TYPE=Base

### Base Size ~ Medium

- **BONUS:** VAR|BaseSize|5|TYPE=Base

### Base Size ~ Large

- **BONUS:** VAR|BaseSize|6|TYPE=Base

### Base Size ~ Huge

- **BONUS:** VAR|BaseSize|7|TYPE=Base

### Base Size ~ Gargantuan

- **BONUS:** VAR|BaseSize|8|TYPE=Base

### Base Size ~ Colossal

- **BONUS:** VAR|BaseSize|9|TYPE=Base

### LEVEL_ADJUSTMENT_1

- **TEMPLATE:** LEVEL_ADJUSTMENT_1

### LEVEL_ADJUSTMENT_2

- **TEMPLATE:** LEVEL_ADJUSTMENT_2

### LEVEL_ADJUSTMENT_3

- **TEMPLATE:** LEVEL_ADJUSTMENT_3

### LEVEL_ADJUSTMENT_4

- **TEMPLATE:** LEVEL_ADJUSTMENT_4

### LEVEL_ADJUSTMENT_5

- **TEMPLATE:** LEVEL_ADJUSTMENT_5

### LEVEL_ADJUSTMENT_6

- **TEMPLATE:** LEVEL_ADJUSTMENT_6

### Default

- **DEFINE:** Caster_Level_Bonus|0
- **DEFINE:** DarkvisionRange|0
- **DEFINE:** HasLowlightVision|0
- **DEFINE:** FirstLevelFeatTaken|0
- **DEFINE:** FirstLevelFeatAllowed|0
- **DEFINE:** ClassBABPoor|0
- **DEFINE:** ClassBABModerate|0
- **DEFINE:** ClassBABFull|0
- **DEFINE:** UseAlternateBABProgression|0
- **ABILITY:** Special Ability|AUTOMATIC|Low-Light Vision
- **ABILITY:** Special Ability|AUTOMATIC|Darkvision
- **ABILITY:** Internal|AUTOMATIC|Defines
- **ABILITY:** Special Ability|AUTOMATIC|Aerial Maneuverability
- **ABILITY:** Special Ability|AUTOMATIC|Uncanny Dodge ~ Base
- **BONUS:** COMBAT|REACH|-5
- **BONUS:** COMBAT|REACH|-5
- **BONUS:** COMBAT|BASEAB|ClassBABPoor*1/2|TYPE=ClassBABPoor
- **BONUS:** COMBAT|BASEAB|ClassBABModerate*3/4|TYPE=ClassBABModerate
- **BONUS:** VAR|FirstLevelFeatTaken|count("ABILITIES","CATEGORY=FEAT","NATURE=Normal","TYPE=FirstLevel")
- **BONUS:** VAR|FirstLevelFeatAllowed|1
- **BONUS:** VAR|FirstLevelFeatAllowed|1
- **BONUS:** VAR|DC_CHA|10+(HD/2)+CHA
- **BONUS:** VAR|DC_CON|10+(HD/2)+CON
- **BONUS:** VAR|DC_INT|10+(HD/2)+INT
- **BONUS:** VAR|DC_WIS|10+(HD/2)+WIS
- **BONUS:** VAR|DC_STR|10+(HD/2)+STR
- **BONUS:** VAR|DC_DEX|10+(HD/2)+DEX
- **DEFINE:** DC_CHA|0
- **DEFINE:** DC_CON|0
- **DEFINE:** DC_INT|0
- **DEFINE:** DC_WIS|0
- **DEFINE:** DC_STR|0
- **DEFINE:** DC_DEX|0
- **DEFINE:** Caster_Level_Bonus|0
- **DEFINE:** DragonAge|0

### Level Adjustment Tracker


### Level Adjustment +1

- **TEMPLATE:** Level Adjustment +1

### Level Adjustment +2

- **TEMPLATE:** Level Adjustment +2

### Level Adjustment +3

- **TEMPLATE:** Level Adjustment +3

### Level Adjustment +4

- **TEMPLATE:** Level Adjustment +4

### Level Adjustment +5

- **TEMPLATE:** Level Adjustment +5

### Level Adjustment +6

- **TEMPLATE:** Level Adjustment +6

### Level Adjustment +7

- **TEMPLATE:** Level Adjustment +7

### Level Adjustment +8

- **TEMPLATE:** Level Adjustment +8

### Level Adjustment +9

- **TEMPLATE:** Level Adjustment +9

### Low-Light Vision

- **DEFINE:** LowLightDistance|0
- **BONUS:** VAR|LowLightDistance|2
- **VISION:** Low-Light Vision
- **ASPECT:** Vision|Low-Light Vision

You can see %1x as far as humans in low illumination. Characters with low-light vision have eyes that are so sensitive to light that they can see twice as far as normal in dim light. Low-light vision is color vision. A spellcaster with low-light vision can read a scroll as long as even the tiniest candle flame is next to her as a source of light. Characters with low-light vision can see outdoors on a moonlit night as well as they can during the day.|LowLightDistance

### Darkvision

- **DEFINE:** DarkvisionRange|0
- **VISION:** Darkvision (DarkvisionRange)
- **ASPECT:** Vision|Darkvision %1'|DarkvisionRange

Range %1 ft.;|DarkvisionRange

Darkvision is the extraordinary ability to see with no light source at all, out to a range specified for the creature. Darkvision is black and white only (colors cannot be discerned). It does not allow characters to see anything that they could not see otherwise-invisible objects are still invisible, and illusions are still visible as what they seem to be. Likewise, darkvision subjects a creature to gaze attacks normally. The presence of light does not spoil darkvision.|DarkvisionRange

### Creature Type

- **TEMPLATE:** Base Race Type
- **ABILITY:** Special Ability|AUTOMATIC|Aberration Type
- **ABILITY:** Special Ability|AUTOMATIC|Animal Type
- **ABILITY:** Special Ability|AUTOMATIC|Construct Type|!PRERACE:1,RACESUBTYPE=Living Construct
- **ABILITY:** Special Ability|AUTOMATIC|Dragon Type

### Aberration Type

- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Animal Type

- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base
- **ABILITY:** Internal|AUTOMATIC|TYPE=ArmorProfHeavy
- **DEFINE:** AnimalWarTrained|0

### Construct Type

- **ABILITY:** Internal|AUTOMATIC|Non-Ability ~ Constitution
- **DEFINE:** DisableNonAbilityConstitution|0
- **BONUS:** HP|CURRENTMAX|max(SIZE-2,0)*10
- **BONUS:** HP|CURRENTMAX|max(SIZE-6,0)*10
- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Dragon Type

- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Elemental Type

- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Fey Type

- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base

### Giant Type

- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base

### Humanoid Type


### Magical Beast Type

- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Monstrous Humanoid Type

- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Ooze Type

- **DEFINE:** OozeObjectAcidDamageAmount|0
- **DEFINE:** OozeHasObjectAcidDamage|0
- **ABILITY:** Internal|AUTOMATIC|Non-Ability ~ Intelligence
- **ABILITY:** Special Ability|AUTOMATIC|Ooze Shared ~ Blindsight
- **BONUS:** VAR|OozeObjectAcidDamageAmount|DefaultDCCon
- **VISION:** Blind

### Outsider Type

- **ABILITY:** Special Ability|AUTOMATIC|Outsider House Rule ~ Martial Weapons
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Plant Type

- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base

### Undead Type

- **TEMPLATE:** Non-Ability ~ Constitution
- **BONUS:** SKILL|Concentration|CHA-CON

### Vermin Type

- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Air Subtype


### Angel Subtype

- **ABILITY:** Special Ability|AUTOMATIC|Angel ~ Protective Aura|Angel ~ Tongues|Immunity to Acid|Immunity to Cold|Immunity to Petrification
- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Aquatic Subtype


### Archon Subtype

- **ABILITY:** Special Ability|AUTOMATIC|Archon ~ Aura of Menace|Archon ~ Magic Circle against Evil|Archon ~ Teleport|Archon ~ Tongues|Immunity to Electricity|Immunity to Petrification
- **BONUS:** VAR|HasLowLightVision|1|TYPE=Base
- **BONUS:** VAR|DarkvisionRange|60|TYPE=Base

### Augmented Subtype


### Chaotic Subtype


### Cold Subtype

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Cold|Vulnerability to Fire

### Tanar'ri Subtype

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Electricity|Immunity to Poison|Resistance to Acid|Resistance to Cold|Resistance to Fire|Summon Demon|Telepathy
- **BONUS:** VAR|AcidResistanceBonus|10|TYPE=Resistance
- **BONUS:** VAR|ColdResistanceBonus|10|TYPE=Resistance
- **BONUS:** VAR|FireResistanceBonus|10|TYPE=Resistance

### Baatezu Subtype

- **ABILITY:** Special Ability|AUTOMATIC|Baatezu ~ See in Darkness|Baatezu ~ Summon|Immunity to Fire|Immunity to Poison|Resistance to Acid|Resistance to Cold|Telepathy
- **BONUS:** VAR|AcidResistanceBonus|10|TYPE=Resistance
- **BONUS:** VAR|ColdResistanceBonus|10|TYPE=Resistance

### Earth Subtype


### Evil Subtype


### Extraplanar Subtype


### Fire Subtype

- **ABILITY:** Special Ability|AUTOMATIC|Immunity to Fire|Vulnerability to Cold

### Goblinoid Subtype


### Good Subtype


### Incorporeal Subtype

- **DEFINE:** CanNotGrapple|0
- **DEFINE:** IncorporealDeflectionBonus|0
- **BONUS:** COMBAT|AC|IncorporealDeflectionBonus|TYPE=Deflection
- **BONUS:** COMBAT|TOHIT.MELEE|DEX
- **BONUS:** VAR|CanNotGrapple|1
- **BONUS:** VAR|IncorporealDeflectionBonus|max(1,CHA)

### Lawful Subtype


### Mephit Subtype

- **ABILITY:** Special Ability|AUTOMATIC|Mephit ~ Breath Weapon|Mephit ~ Fast Healing|Mephit ~ Natural Weapons|Mephit ~ Spell-Like Abilities|Mephit ~ Summon Mephit

### Native Subtype


### Reptilian Subtype


### Shapechanger Subtype


### Swarm Subtype

- **DEFINE:** CanNotGrapple|0
- **BONUS:** VAR|CanNotGrapple|1

### Water Subtype


### Mindless

- **TEMPLATE:** Non-Ability ~ Intelligence

### Deathless Type

- **TEMPLATE:** Non-Ability ~ Constitution
- **BONUS:** SKILL|Concentration|CHA-CON

### Living Construct Subtype

- **DEFINE:** DisableNonAbilityConstitution|0
- **BONUS:** VAR|DisableNonAbilityConstitution|1

### Assign Race Type ~ Aberration

- **TEMPLATE:** Assign Race Type ~ Aberration

### Assign Race Type ~ Animal

- **TEMPLATE:** Assign Race Type ~ Animal

### Assign Race Type ~ Construct

- **TEMPLATE:** Assign Race Type ~ Construct

### Assign Race Type ~ Dragon

- **TEMPLATE:** Assign Race Type ~ Dragon

### Assign Race Type ~ Elemental

- **TEMPLATE:** Assign Race Type ~ Elemental

### Assign Race Type ~ Fey

- **TEMPLATE:** Assign Race Type ~ Fey

### Assign Race Type ~ Giant

- **TEMPLATE:** Assign Race Type ~ Giant

### Assign Race Type ~ Humanoid

- **TEMPLATE:** Assign Race Type ~ Humanoid

### Assign Race Type ~ Magical Beast

- **TEMPLATE:** Assign Race Type ~ Magical Beast

### Assign Race Type ~ Monstrous Humanoid

- **TEMPLATE:** Assign Race Type ~ Monstrous Humanoid

### Assign Race Type ~ Ooze

- **TEMPLATE:** Assign Race Type ~ Ooze

### Assign Race Type ~ Outsider

- **TEMPLATE:** Assign Race Type ~ Outsider

### Assign Race Type ~ Plant

- **TEMPLATE:** Assign Race Type ~ Plant

### Assign Race Type ~ Undead

- **TEMPLATE:** Assign Race Type ~ Undead

### Assign Race Type ~ Vermin

- **TEMPLATE:** Assign Race Type ~ Vermin

### Assign Race Subtype ~ Air

- **TEMPLATE:** Assign Race Subtype ~ Air

### Assign Race Subtype ~ Angel

- **TEMPLATE:** Assign Race Subtype ~ Angel

### Assign Race Subtype ~ Aquatic

- **TEMPLATE:** Assign Race Subtype ~ Aquatic

### Assign Race Subtype ~ Archon

- **TEMPLATE:** Assign Race Subtype ~ Archon

### Assign Race Subtype ~ Augmented

- **TEMPLATE:** Assign Race Subtype ~ Augmented

### Assign Race Subtype ~ Chaotic

- **TEMPLATE:** Assign Race Subtype ~ Chaotic

### Assign Race Subtype ~ Cold

- **TEMPLATE:** Assign Race Subtype ~ Cold

### Assign Race Subtype ~ Evil

- **TEMPLATE:** Assign Race Subtype ~ Evil

### Assign Race Subtype ~ Fire

- **TEMPLATE:** Assign Race Subtype ~ Fire

### Assign Race Subtype ~ Good

- **TEMPLATE:** Assign Race Subtype ~ Good

### Assign Race Subtype ~ Earth

- **TEMPLATE:** Assign Race Subtype ~ Earth

### Assign Race Subtype ~ Lawful

- **TEMPLATE:** Assign Race Subtype ~ Lawful

### Assign Race Subtype ~ Reptilian

- **TEMPLATE:** Assign Race Subtype ~ Reptilian

### Assign Race Subtype ~ Shapechanger

- **TEMPLATE:** Assign Race Subtype ~ Shapechanger

### Assign Race Subtype ~ Swarm

- **TEMPLATE:** Assign Race Subtype ~ Swarm

### Assign Race Subtype ~ Water

- **TEMPLATE:** Assign Race Subtype ~ Water

### Assign Race Subtype ~ Extraplanar

- **TEMPLATE:** Assign Race Subtype ~ Extraplanar

### Assign Race Subtype ~ Native

- **TEMPLATE:** Assign Race Subtype ~ Native

### Assign Race Type ~ Deathless

- **TEMPLATE:** Assign Race Type ~ Deathless

### Symbiont Subtype

- **DEFINE:** EgoScore|0
- **ABILITY:** Special Ability|AUTOMATIC|Symbiont Subtype ~ Share Spells
- **BONUS:** VAR|EgoScore|max(INT,0)+max(WIS,0)+max(CHA,0)
- **BONUS:** VAR|EgoScore|2*count("ABILITIES","CATEGORY=Special Ability","TYPE=SpecialAttack")
- **BONUS:** VAR|EgoScore|1*count("ABILITIES","CATEGORY=Special Ability","TYPE=SpecialQuality")
- **BONUS:** VAR|EgoScore|4
- **ASPECT:** SaveBonus|Ego %1|EgoScore

### Share Spells


Any spell the host creature casts on itself automatically also affects the symbiont. Additionally, the host may cast a spell with a target of "You" on the symbiont instead of on itself. Likewise, a symbiont can choose to have any spell or spell-like ability it uses on itself also affect the host creature, and may cast a spell with a target of "You" on its host instead of on itself. The host and symbiont can share spells even if the spells normally do not affect creatures of the host or symbiont's type. Spells targeted on the host by another spellcaster do not affect the symbiont, and vice versa.

### Augmented Aberration

- **TEMPLATE:** RaceSubtype ~ Augmented Aberration

### Augmented Animal

- **TEMPLATE:** RaceSubtype ~ Augmented Animal

### Augmented Construct

- **TEMPLATE:** RaceSubtype ~ Augmented Construct

### Augmented Dragon

- **TEMPLATE:** RaceSubtype ~ Augmented Dragon

### Augmented Elemental

- **TEMPLATE:** RaceSubtype ~ Augmented Elemental

### Augmented Fey

- **TEMPLATE:** RaceSubtype ~ Augmented Fey

### Augmented Giant

- **TEMPLATE:** RaceSubtype ~ Augmented Giant

### Augmented Humanoid

- **TEMPLATE:** RaceSubtype ~ Augmented Humanoid

### Augmented Magical Beast

- **TEMPLATE:** RaceSubtype ~ Augmented Magical Beast

### Augmented Monstrous Humanoid

- **TEMPLATE:** RaceSubtype ~ Augmented Monstrous Humanoid

### Augmented Ooze

- **TEMPLATE:** RaceSubtype ~ Augmented Ooze

### Augmented Outsider

- **TEMPLATE:** RaceSubtype ~ Augmented Outsider

### Augmented Plant

- **TEMPLATE:** RaceSubtype ~ Augmented Plant

### Augmented Undead

- **TEMPLATE:** RaceSubtype ~ Augmented Undead

### Augmented Vermin

- **TEMPLATE:** RaceSubtype ~ Augmented Vermin

### Dragonblood Subtype


### Psionic

- **DEFINE:** BasePowerPoints|0
- **DEFINE:** BonusPowerPoints|0
- **DEFINE:** TotalPowerPoints|0
- **BONUS:** VAR|TotalPowerPoints|BasePowerPoints
- **BONUS:** VAR|TotalPowerPoints|BonusPowerPoints

Total Power Points %1; Base Power Points %2; Bonus Power Points %3|TotalPowerPoints|BasePowerPoints|BonusPowerPoints

### Non-Ability ~ Constitution

- **TEMPLATE:** Non-Ability ~ Constitution

### Non-Ability ~ Intelligence

- **TEMPLATE:** Non-Ability ~ Intelligence

### Blindsense

- **DEFINE:** BlindsenseRange|0
- **VISION:** Blindsense (BlindsenseRange)
- **ASPECT:** Vision|Blindsense %1 ft.|BlindsenseRange

Range %1 ft.;|BlindsenseRange

The creature has blindsense, a lesser ability that lets the creature notice things it cannot see, but without the precision of blindsight. The creature with blindsense usually does not need to make Spot or Listen checks to notice and locate creatures within range of its blindsense ability, provided that it has line of effect to that creature. Any opponent the creature cannot see has total concealment (50%% miss chance) against the creature with blindsense, and the blindsensing creature still has the normal miss chance when attacking foes that have concealment. Visibility still affects the movement of a creature with blindsense. A creature with blindsense is still denied its Dexterity bonus to Armor Class against attacks from creatures it cannot see.|BlindsenseRange

### Blindsight

- **DEFINE:** BlindsightRange|0
- **VISION:** Blindsight (BlindsightRange)
- **ASPECT:** Vision|Blindsight %1 ft.|BlindsightRange

Range %1 ft.;|BlindsightRange

The creature has blindsight, the extraordinary ability to use a nonvisual sense (or a combination of such senses) to operate effectively without vision. Such sense may include sensitivity to vibrations, acute scent, keen hearing, or echolocation. This ability makes invisibility and concealment (even magical darkness) irrelevant to the creature (though it still can't see ethereal creatures and must have line of effect to a creature or object to discern that creature or object). This ability operates out to a range specified in the creature description. The creature usually does not need to make Spot or Listen checks to notice creatures within range of its blindsight ability. Unless noted otherwise, blindsight is continuous, and the creature need do nothing to use it. Some forms of blindsight, however, must be triggered as a free action. If so, this is noted in the creature's description. If a creature must trigger its blindsight ability, the creature gains the benefits of blindsight only during its turn. Blindsight never allows a creature to distinguish color or visual contrast. A creature cannot read with blindsight. Blindsight does not subject a creature to gaze attacks (even though darkvision does). Blinding attacks do not penalize creatures using blindsight. Deafening attacks thwart blindsight if it relies on hearing. Blindsight works underwater but not in a vacuum. Blindsight negates displacement and blur effects.|BlindsightRange

### Tremorsense

- **DEFINE:** TremorsenseRange|0
- **VISION:** Tremorsense (TremorsenseRange)
- **ASPECT:** Vision|Tremorsense %1 ft.|TremorsenseRange

Range %1 ft.;|TremorsenseRange

A creature with tremorsense automatically senses the location of anything that is in contact with the ground and within range. Aquatic creatures with tremorsense can also sense the location of creatures moving through water. If no straight path exists through the ground from the creature to those that it's sensing, then the range defines the maximum distance of the shortest indirect path. It must itself be in contact with the ground, and the creatures must be moving. As long as the other creatures are taking physical actions, including casting spells with somatic components, they're considered moving; they don't have to move from place to place for a creature with tremorsense to detect them.|TremorsenseRange

### Keen Scent

- **DEFINE:** KeenScentRange|0
- **VISION:** Keen Scent (KeenScentRange)
- **ASPECT:** Vision|Keen Scent %1 ft.|KeenScentRange

Range %1 ft.|KeenScentRange

### See Etheral

- **DEFINE:** SeeEtheralRange|0
- **VISION:** See Etheral (SeeEtheralRange)
- **ASPECT:** Vision|See Etheral %1 ft.|SeeEtheralRange

Range %1 ft.|SeeEtheralRange

### See Invisibility

- **DEFINE:** SeeInvisibilityRange|0
- **VISION:** See Invisibility (SeeInvisibilityRange)
- **ASPECT:** Vision|See Invisibility %1 ft.|SeeInvisibilityRange

Range %1 ft.|SeeInvisibilityRange

### Superior Low-Light Vision


### Resistance to Mind-Affecting


### Resistance to Paralysis


### Resistance to Poison


### Resistance to Sleep


### Resistance to Stunning


### Spell Resistance


### Immunity to Aging


### Immunity to Non-Magical Disease


### Flight


### True Dragon Defaults

- **DEFINE:** NoFlight|0
- **DEFINE:** DragonSizeTracker|0
- **DEFINE:** DragonLevelAdjustment|0
- **DEFINE:** DragonBreathWeaponLine|0
- **DEFINE:** DragonBreathWeaponCone|0
- **DEFINE:** DragonBreathWeaponDC|0
- **DEFINE:** DragonBreathWeaponDieSize|0
- **DEFINE:** DragonBreathWeaponDice|0
- **DEFINE:** DragonAgeCategory|0
- **ABILITY:** Internal|AUTOMATIC|SIZE_T
- **ABILITY:** Internal|AUTOMATIC|SIZE_S
- **ABILITY:** Internal|AUTOMATIC|SIZE_M
- **ABILITY:** Internal|AUTOMATIC|SIZE_L
- **ABILITY:** Internal|AUTOMATIC|SIZE_H
- **ABILITY:** Internal|AUTOMATIC|SIZE_G
- **ABILITY:** Internal|AUTOMATIC|SIZE_C
- **ABILITY:** Internal|AUTOMATIC|LEVEL_ADJUSTMENT_1
- **ABILITY:** Internal|AUTOMATIC|LEVEL_ADJUSTMENT_2
- **ABILITY:** Internal|AUTOMATIC|LEVEL_ADJUSTMENT_3
- **ABILITY:** Internal|AUTOMATIC|LEVEL_ADJUSTMENT_4
- **ABILITY:** Internal|AUTOMATIC|LEVEL_ADJUSTMENT_5
- **ABILITY:** Internal|AUTOMATIC|LEVEL_ADJUSTMENT_6
- **ABILITY:** Internal|AUTOMATIC|DRAGON_FLY_SPEED_100
- **ABILITY:** Internal|AUTOMATIC|DRAGON_FLY_SPEED_150
- **ABILITY:** Internal|AUTOMATIC|DRAGON_FLY_SPEED_200
- **ABILITY:** Internal|AUTOMATIC|DRAGON_ATTACKS_T
- **ABILITY:** Internal|AUTOMATIC|DRAGON_ATTACKS_S
- **ABILITY:** Internal|AUTOMATIC|DRAGON_ATTACKS_M
- **ABILITY:** Internal|AUTOMATIC|DRAGON_ATTACKS_L
- **ABILITY:** Internal|AUTOMATIC|DRAGON_ATTACKS_H
- **ABILITY:** Internal|AUTOMATIC|DRAGON_ATTACKS_G
- **ABILITY:** Internal|AUTOMATIC|DRAGON_ATTACKS_C
- **ABILITY:** Internal|AUTOMATIC|Wyrmling
- **ABILITY:** Internal|AUTOMATIC|Very Young
- **ABILITY:** Internal|AUTOMATIC|Young
- **ABILITY:** Internal|AUTOMATIC|Juvenile
- **ABILITY:** Internal|AUTOMATIC|Young Adult
- **ABILITY:** Internal|AUTOMATIC|Adult
- **ABILITY:** Internal|AUTOMATIC|Mature Adult
- **ABILITY:** Internal|AUTOMATIC|Old
- **ABILITY:** Internal|AUTOMATIC|Very Old
- **ABILITY:** Internal|AUTOMATIC|Ancient
- **ABILITY:** Internal|AUTOMATIC|Wyrm
- **ABILITY:** Internal|AUTOMATIC|Great Wyrm
- **ABILITY:** Special Ability|AUTOMATIC|Flight Maneuverability
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Bite
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Claw
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Wing
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Tail Slap
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Crush
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Tail Sweep
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Grappling
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Breath Weapon
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Frightful Presence
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Spells
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Spell-Like Abilities
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Damage Reduction
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Immunities
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Spell Resistance
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Blindsense
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Keen Senses
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Skills
- **ABILITY:** Special Ability|AUTOMATIC|Dragon ~ Feats
- **BONUS:** VAR|DragonBreathWeaponDice|2*DragonAgeCategory
- **BONUS:** VAR|DragonBreathWeaponDC|10+(DragonLVL/2)+CON
- **BONUS:** VAR|DragonBreathWeaponLine|30
- **BONUS:** VAR|DragonBreathWeaponCone|15
- **BONUS:** VAR|DragonBreathWeaponLine|10
- **BONUS:** VAR|DragonBreathWeaponLine|20
- **BONUS:** VAR|DragonBreathWeaponLine|20
- **BONUS:** VAR|DragonBreathWeaponLine|20
- **BONUS:** VAR|DragonBreathWeaponLine|20
- **BONUS:** VAR|DragonBreathWeaponLine|20
- **BONUS:** VAR|DragonBreathWeaponCone|5
- **BONUS:** VAR|DragonBreathWeaponCone|10
- **BONUS:** VAR|DragonBreathWeaponCone|10
- **BONUS:** VAR|DragonBreathWeaponCone|10
- **BONUS:** VAR|DragonBreathWeaponCone|10
- **BONUS:** VAR|DragonBreathWeaponCone|10
- **BONUS:** COMBAT|AC|DragonNaturalArmor|TYPE=NaturalArmor
- **DEFINE:** DragonNaturalArmor|0
- **BONUS:** VAR|DragonNaturalArmor|DragonLVL-1

### Bite


Bite attacks deal the indicated damage plus the dragon's Strength bonus. A dragon also can use its bite to snatch opponents if it has the Snatch feat (see page 304).

### Claw


Claw attacks deal the indicated damage plus 1/2 the dragon's Strength bonus (round down). The dragon also can use its claws to snatch opponents if it has the Snatch feat (see page 304). Claw attacks are secondary attacks, requiring a -5 penalrty on the attack roll. (Many dragons choose the Multiattack feat to lessen this penalty to -2).

### Wing


The dragon can slam opponents with its wings, even when flying. Wing attacks deal the indicated damage plus 1/2 the dragon's Strength bonus (round down) and are treated as secondary attacks.

### Tail Slap


The dragon can slap one opponent each round with its tail. A tail slap deals the indicated damage plus 1-1/2 times the dragon's Strength bonus (round down) and is treated as a secondary attack.

### Grappling


Dragons do not favor grapple attacks, though their crush attack (and Snatch feat, if they know it) use normal grapple rules. A dragon can always use its breath weapon while grappling, as well as its spells and spell-like or supernatural abilities, provided it succeeds on Concentration checks.

### DRAGON_FLY_SPEED_100

- **DEFINE:** Maneuverability|0
- **MOVE:** Fly,100
- **BONUS:** VAR|Maneuverability|3

### DRAGON_FLY_SPEED_150

- **DEFINE:** Maneuverability|0
- **MOVE:** Fly,150
- **BONUS:** VAR|Maneuverability|2

### DRAGON_FLY_SPEED_200

- **DEFINE:** Maneuverability|0
- **MOVE:** Fly,200
- **BONUS:** VAR|Maneuverability|1

### DRAGON_ATTACKS_T

- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4|Claws,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3

### DRAGON_ATTACKS_S

- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6|Claws,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4

### DRAGON_ATTACKS_M

- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8|Claws,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Wings,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d4

### DRAGON_ATTACKS_L

- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6|Claws,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Wings,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d6|Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,1d8

### DRAGON_ATTACKS_H

- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8|Claws,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Wings,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,1d8|Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6|Crush,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8

### DRAGON_ATTACKS_G

- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6|Claws,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,2d8|Wings,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d6|Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8|Crush,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,4d6|Tail Sweep,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d6

### DRAGON_ATTACKS_C

- **NATURALATTACKS:** Bite,Weapon.Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d8|Claws,Weapon.Natural.Melee.Finesseable.Piercing.Slashing,*2,4d6|Wings,Weapon.Natural.Melee.Finesseable.Bludgeoning,*2,2d8|Tail Slap,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,4d6|Crush,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,4d8|Tail Sweep,Weapon.Natural.Melee.Finesseable.Bludgeoning,*1,2d8

### Wyrmling

- **TEMPLATE:** Wyrmling

### Very Young

- **TEMPLATE:** Very Young

### Young

- **TEMPLATE:** Young

### Juvenile

- **TEMPLATE:** Juvenile

### Young Adult

- **TEMPLATE:** Young Adult

### Adult

- **TEMPLATE:** Adult

### Mature Adult

- **TEMPLATE:** Mature Adult

### Old

- **TEMPLATE:** Old

### Very Old

- **TEMPLATE:** Very Old

### Ancient

- **TEMPLATE:** Ancient

### Wyrm

- **TEMPLATE:** Wyrm

### Great Wyrm

- **TEMPLATE:** Great Wyrm

### Dragon Age Selected


### Crush


This special attack allows a flying or jumping dragon of at least Huge size to land on opponents as a standard action, using its whole body to crush them. Crush attacks are effective only against opponents three or more size categories smaller than the dragon (though it can attempt normal overrun or grapple attacks against larger opponents). A crush attack affects as many creatures as can fit under the dragon's body. Creatures in the affected area must succeed on a Reflex save (DC equal to that of the dragon's breath weapon) or be pinned, automatically taking bludgeoning damage during the next round unless the dragon moves off them. If the dragon chooses to maintain the pin, treat it as a normal grapple attack. Pinned opponents take damage from the crush each round if they don't escape. A crush attack deals the indicated damage plus 1-1/2 times the dragon's Strength bonus (round down). Grappling: Dragons do not favor grapple attacks, though their crush attack (and Snatch feat, if they know it) use normal grapple rules. A dragon can always use its breath weapon while grappling, as well as its spells and spell-like or supernatural abilities, provided it succeeds on Concentration checks.

### Tail Sweep


This special attack allows a dragon of at least Gargantuan size to sweep with its tail as a standard action. The sweep affects a half-circle with a radius of 30 feet (or 40 feet for a Colossal dragon), extending from an intersection on the edge of the dragon's space in any direction. Creatures within the swept area are affected if they are four or more size categories smaller than the dragon. A tail sweep automatically deals the indicated damage plus 1-1/2 times the dragon's Strength bonus (round down). Affected creatures can attempt Reflex saves to take half damage (DC equal to that of the dragon's breath weapon).

### Breath Weapon

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

Using a breath weapon is a standard action. Once a dragon breathes, it can't breathe again until 1d4 rounds later. If a dragon has more than one type of breath weapon, it still can breathe only once every 1d4 rounds. A blast from a breath weapon always starts at any intersection adjacent to the dragon and extends in a direction of the dragon's choice, with an area as noted on the table below. If the breath weapon deals damage, creatures caught in the area can attempt Reflex saves to take half damage; the DC depends on the dragon's age and variety, and is given in each individual entry. Saves against nondamaging breath weapons use the same DC; the kind of saving throw is noted in the variety descriptions. The save DC against a breath weapon is 10 + 1/2 dragon's HD + dragon's Con modifier. Breath weapons come in two basic shapes, line and cone, whose areas vary with the dragon's size.

### Frightful Presence

- **DEFINE:** FrightfulPresenceRange|0
- **BONUS:** VAR|FrightfulPresenceRange|DragonAgeCategory*30
- **DEFINE:** DragonFrightfulPresenceDC|0
- **BONUS:** VAR|DragonFrightfulPresenceDC|10+(DragonLVL/2)+CHA

A young adult or older dragon can unsettle foes with its mere presence. The ability takes effect automatically whenever the dragon attacks, charges, or flies overhead. Creatures within a radius of 30 feet x the dragon's age category are subject to the effect if they have fewer HD than the dragon. A potentially affected creature that succeeds on a Will save (DC 10 + 1/2 dragon's HD + dragon's Cha modifier) remains immune to that dragon's frightful presence for 24 hours. On a failure, creatures with 4 or less HD become panicked for 4d6 rounds and those with 5 or more HD become shaken for 4d6 rounds. Dragons ignore the frightful presence of other dragons.

Range %1, DC %2|FrightfulPresenceRange|DragonFrightfulPresenceDC

### Spells


A dragon knows and casts arcane spells as a sorcerer of the level indicated in its variety description, gaining bonus spells for a high Charisma score. Some dragons can also cast spells from the cleric list or cleric domain lists as arcane spells.

### Spell-Like Abilities


A dragon's spelllike abilities depend on its age and variety. It gains the abilities indicated for its age plus all previous ones. Its age category or its sorcerer caster level, whichever is higher, is the caster level for these abilities. The save DC is 10 + dragon's Cha modifier + spell level. All spell-like abilities are usable once per day unless otherwise noted.

### Damage Reduction


Young adult and older dragons have damage reduction. Their natural weapons are treated as magic weapons for the purpose of overcoming damage reduction.

### Immunities


All dragons have immunity to sleep and paralysis effects. Each variety of dragon has immunity to one or two additional forms of attack no matter what its age, as given in its description.

### Keen Senses


A dragon sees four times as well a human in shadowy illumination and twice as well in normal light. It also has darkvision out to 120 feet.

### Skills


All dragons have skill points equal to (6 + Int modifier, minimum 1) ? (Hit Dice + 3). Most dragons purchase the following skills at the maximum ranks possible: Listen, Search, and Spot. The remaining skill points are generally spent on Concentration, Diplomacy, Escape Artist, Intimidate, Knowledge (any), Sense Motive, and Use Magic Device at a cost of 1 skill point per rank. All these skills are considered class skills for dragons. (Each dragon has other class skills as well, as noted in the variety descriptions.)

### Feats


All dragons have one feat, plus an additional feat per 3 Hit Dice, just like any other creature. Dragons favor Alertness, Blind-Fight, Cleave, Flyby Attack, Hover, Improved Initiative, Improved Sunder, Power Attack, Snatch, Weapon Focus (claw or bite), Wingover, and any metamagic feat that is available and useful to sorcerers.

### Breath Weapon ~ Line of Cold

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Line, %2d%3 Cold DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Line of Concussive Force

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Line, %2d%3 Concussive Force DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Line of Disease

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Line, %2d%3 Disease DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Line of Paralyzing Gas

- **DEFINE:** BreathWeaponLine|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Line, %2d%3 Paralyzing Gas DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Brilliant Light

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone, %2d%3 Brilliant Light DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Dehydratation

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone, %2d%3 Dehydratation DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Disease

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone, %2d%3 Disease DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Keening Energy

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone, %2d%3 Keening Energy DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Sonic Energy

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone, %2d%3 Sonic Energy DC %4|BreathWeaponLine|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Breath Weapon ~ Cone of Acid

- **DEFINE:** BreathWeaponCone|0
- **DEFINE:** BreathWeaponDice|0
- **DEFINE:** BreathWeaponDamageDie|0
- **DEFINE:** DC_Breath_Weapon|0
- **BONUS:** VAR|DC_Breath_Weapon|DC_CON
- **BONUS:** VAR|DC_Breath_Weapon|2
- **ABILITY:** Ability Focus|AUTOMATIC|Breath Weapon

%1' Cone, %2d%3 acid DC %4|BreathWeaponCone|BreathWeaponDice|BreathWeaponDamageDie|DC_Breath_Weapon

### Immunity To Air Effects


### Immunity To Chaotic Spells


### Immunity To Death from Massive Damage


### Immunity To Enchantment


### Immunity To Non-lethal Damage


### Immunity To Rust


### Resistance To Force


### Resistance To Ranged Attack


### Planar Travel


### Vulnerability To Shatter


### Water Breathing


### Bite (Fine)

- **PRESIZEEQ:** F
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1

### Bite (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d2

### Bite (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d3

### Bite (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4

### Bite (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6

### Bite (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8

### Bite (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6

### Bite (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,3d6

### Bite (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6

### Gore

- **ABILITY:** Internal|AUTOMATIC|Gore (Fine)
- **ABILITY:** Internal|AUTOMATIC|Gore (Diminutive)
- **ABILITY:** Internal|AUTOMATIC|Gore (Tiny)
- **ABILITY:** Internal|AUTOMATIC|Gore (Small)
- **ABILITY:** Internal|AUTOMATIC|Gore (Medium)
- **ABILITY:** Internal|AUTOMATIC|Gore (Large)
- **ABILITY:** Internal|AUTOMATIC|Gore (Huge)
- **ABILITY:** Internal|AUTOMATIC|Gore (Gargantuan)
- **ABILITY:** Internal|AUTOMATIC|Gore (Colossal)

### Gore (Fine)

- **PRESIZEEQ:** F
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1

### Gore (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d2

### Gore (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d3

### Gore (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d4

### Gore (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d6

### Gore (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d8

### Gore (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,2d6

### Gore (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,2d8

### Gore (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Gore,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,4d6

### Pincers

- **ABILITY:** Internal|AUTOMATIC|Pincers (Fine)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Diminutive)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Tiny)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Small)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Medium)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Large)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Huge)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Gargantuan)
- **ABILITY:** Internal|AUTOMATIC|Pincers (Colossal)

### Pincers (Fine)

- **PRESIZEEQ:** F
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1

### Pincers (Diminutive)

- **PRESIZEEQ:** D
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d2

### Pincers (Tiny)

- **PRESIZEEQ:** T
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d3

### Pincers (Small)

- **PRESIZEEQ:** S
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d4

### Pincers (Medium)

- **PRESIZEEQ:** M
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d6

### Pincers (Large)

- **PRESIZEEQ:** L
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d8

### Pincers (Huge)

- **PRESIZEEQ:** H
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d6

### Pincers (Gargantuan)

- **PRESIZEEQ:** G
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d8

### Pincers (Colossal)

- **PRESIZEEQ:** C
- **BONUS:** WEAPONPROF=Pincers|TOHIT|-5
- **BONUS:** WEAPONPROF=Pincers|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Pincers,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,4d6

### Tail Slap (Fine)

- **PRESIZEEQ:** F
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1

### Tail Slap (Diminutive)

- **PRESIZEEQ:** D
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d2

### Tail Slap (Tiny)

- **PRESIZEEQ:** T
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d3

### Tail Slap (Small)

- **PRESIZEEQ:** S
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d4

### Tail Slap (Medium)

- **PRESIZEEQ:** M
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d6

### Tail Slap (Large)

- **PRESIZEEQ:** L
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d8

### Tail Slap (Huge)

- **PRESIZEEQ:** H
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d6

### Tail Slap (Gargantuan)

- **PRESIZEEQ:** G
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d8

### Tail Slap (Colossal)

- **PRESIZEEQ:** C
- **BONUS:** WEAPONPROF=Tail Slap|TOHIT|-5
- **BONUS:** WEAPONPROF=Tail Slap|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tail Slap,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,4d6

### Claw (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,1

### Claw (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,1d2

### Claw (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,1d3

### Claw (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,1d4

### Claw (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,1d6

### Claw (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,1d8

### Claw (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,2d6

### Claw (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Claw,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*2,2d8

### Slam

- **ABILITY:** Internal|AUTOMATIC|Slam (Diminutive)
- **ABILITY:** Internal|AUTOMATIC|Slam (Tiny)
- **ABILITY:** Internal|AUTOMATIC|Slam (Small)
- **ABILITY:** Internal|AUTOMATIC|Slam (Medium)
- **ABILITY:** Internal|AUTOMATIC|Slam (Large)
- **ABILITY:** Internal|AUTOMATIC|Slam (Huge)
- **ABILITY:** Internal|AUTOMATIC|Slam (Gargantuan)
- **ABILITY:** Internal|AUTOMATIC|Slam (Colossal)

### Slam (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,1

### Slam (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,1d2

### Slam (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,1d3

### Slam (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,1d4

### Slam (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,1d6

### Slam (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,1d8

### Slam (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,2d6

### Slam (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Slam,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Slashing,*1,2d8

### Sting

- **ABILITY:** Internal|AUTOMATIC|Sting (Diminutive)
- **ABILITY:** Internal|AUTOMATIC|Sting (Tiny)
- **ABILITY:** Internal|AUTOMATIC|Sting (Small)
- **ABILITY:** Internal|AUTOMATIC|Sting (Medium)
- **ABILITY:** Internal|AUTOMATIC|Sting (Large)
- **ABILITY:** Internal|AUTOMATIC|Sting (Huge)
- **ABILITY:** Internal|AUTOMATIC|Sting (Gargantuan)
- **ABILITY:** Internal|AUTOMATIC|Sting (Colossal)

### Sting (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1

### Sting (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d2

### Sting (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d3

### Sting (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d4

### Sting (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d6

### Sting (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,1d8

### Sting (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,2d6

### Sting (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Sting,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing,*1,2d8

### Talons

- **ABILITY:** Internal|AUTOMATIC|Talons (Diminutive)
- **ABILITY:** Internal|AUTOMATIC|Talons (Tiny)
- **ABILITY:** Internal|AUTOMATIC|Talons (Small)
- **ABILITY:** Internal|AUTOMATIC|Talons (Medium)
- **ABILITY:** Internal|AUTOMATIC|Talons (Large)
- **ABILITY:** Internal|AUTOMATIC|Talons (Huge)
- **ABILITY:** Internal|AUTOMATIC|Talons (Gargantuan)
- **ABILITY:** Internal|AUTOMATIC|Talons (Colossal)

### Talons (Diminutive)

- **PRESIZEEQ:** D
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,1

### Talons (Tiny)

- **PRESIZEEQ:** T
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,1d2

### Talons (Small)

- **PRESIZEEQ:** S
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,1d3

### Talons (Medium)

- **PRESIZEEQ:** M
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,1d4

### Talons (Large)

- **PRESIZEEQ:** L
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,1d6

### Talons (Huge)

- **PRESIZEEQ:** H
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,1d8

### Talons (Gargantuan)

- **PRESIZEEQ:** G
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,2d6

### Talons (Colossal)

- **PRESIZEEQ:** C
- **NATURALATTACKS:** Talons,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Slashing,*2,2d8

### Hoof

- **ABILITY:** Internal|AUTOMATIC|Hoof (Diminutive)
- **ABILITY:** Internal|AUTOMATIC|Hoof (Tiny)
- **ABILITY:** Internal|AUTOMATIC|Hoof (Small)
- **ABILITY:** Internal|AUTOMATIC|Hoof (Medium)
- **ABILITY:** Internal|AUTOMATIC|Hoof (Large)
- **ABILITY:** Internal|AUTOMATIC|Hoof (Huge)
- **ABILITY:** Internal|AUTOMATIC|Hoof (Gargantuan)
- **ABILITY:** Internal|AUTOMATIC|Hoof (Colossal)

### Hoof (Diminutive)

- **PRESIZEEQ:** D
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1

### Hoof (Tiny)

- **PRESIZEEQ:** T
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d2

### Hoof (Small)

- **PRESIZEEQ:** S
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d3

### Hoof (Medium)

- **PRESIZEEQ:** M
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d4

### Hoof (Large)

- **PRESIZEEQ:** L
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d6

### Hoof (Huge)

- **PRESIZEEQ:** H
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d8

### Hoof (Gargantuan)

- **PRESIZEEQ:** G
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d6

### Hoof (Colossal)

- **PRESIZEEQ:** C
- **BONUS:** WEAPONPROF=Hoof|TOHIT|-5
- **BONUS:** WEAPONPROF=Hoof|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Hoof,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d8

### Tentacle

- **ABILITY:** Internal|AUTOMATIC|Tentacle (Diminutive)
- **ABILITY:** Internal|AUTOMATIC|Tentacle (Tiny)
- **ABILITY:** Internal|AUTOMATIC|Tentacle (Small)
- **ABILITY:** Internal|AUTOMATIC|Tentacle (Medium)
- **ABILITY:** Internal|AUTOMATIC|Tentacle (Large)
- **ABILITY:** Internal|AUTOMATIC|Tentacle (Huge)
- **ABILITY:** Internal|AUTOMATIC|Tentacle (Gargantuan)
- **ABILITY:** Internal|AUTOMATIC|Tentacle (Colossal)

### Tentacle (Diminutive)

- **PRESIZEEQ:** D
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1

### Tentacle (Tiny)

- **PRESIZEEQ:** T
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d2

### Tentacle (Small)

- **PRESIZEEQ:** S
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d3

### Tentacle (Medium)

- **PRESIZEEQ:** M
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d4

### Tentacle (Large)

- **PRESIZEEQ:** L
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d6

### Tentacle (Huge)

- **PRESIZEEQ:** H
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d8

### Tentacle (Gargantuan)

- **PRESIZEEQ:** G
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d6

### Tentacle (Colossal)

- **PRESIZEEQ:** C
- **BONUS:** WEAPONPROF=Tentacle|TOHIT|-5
- **BONUS:** WEAPONPROF=Tentacle|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Tentacle,Weapon.Natural.NaturalSecondary.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d8

### Wing (Diminutive)

- **PRESIZEEQ:** D
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,1

### Wing (Tiny)

- **PRESIZEEQ:** T
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,1d2

### Wing (Small)

- **PRESIZEEQ:** S
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,1d3

### Wing (Medium)

- **PRESIZEEQ:** M
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,1d4

### Wing (Large)

- **PRESIZEEQ:** L
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,1d6

### Wing (Huge)

- **PRESIZEEQ:** H
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,1d8

### Wing (Gargantuan)

- **PRESIZEEQ:** G
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,2d6

### Wing (Colossal)

- **PRESIZEEQ:** C
- **BONUS:** WEAPONPROF=Wing|TOHIT|-5
- **BONUS:** WEAPONPROF=Wing|DAMAGE|-(STR/2)
- **NATURALATTACKS:** Wing,Weapon.Natural.NaturalSecondary.Melee.Finesseable.Bludgeoning,*2,2d8

### Tail Sweep (Diminutive)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1

### Tail Sweep (Tiny)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d2

### Tail Sweep (Small)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d3

### Tail Sweep (Medium)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d4

### Tail Sweep (Large)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d6

### Tail Sweep (Huge)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d8

### Tail Sweep (Gargantuan)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d6

### Tail Sweep (Colossal)

- **BONUS:** WEAPONPROF=Tail Sweep|DAMAGE|(STR/2)
- **NATURALATTACKS:** Tail Sweep,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d8

### Crush (Diminutive)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d3

### Crush (Tiny)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d4

### Crush (Small)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d6

### Crush (Medium)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d8

### Crush (Large)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d6

### Crush (Huge)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d8

### Crush (Gargantuan)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,4d6

### Crush (Colossal)

- **BONUS:** WEAPONPROF=Crush|DAMAGE|(STR/2)
- **NATURALATTACKS:** Crush,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,4d8

### Immunity to Necromantic Effects


### Immunity to Sneak Attack


### Immunity to Fear


### -


### Sudden Strike

- **DEFINE:** SuddenStrikeDice|0
- **ASPECT:** NAME|Sudden Strike +%1d6|SuddenStrikeDice

If you can catch an opponent when they are unable to defend themself effectively from your attack, you can strike a vital spot for extra damage. Whenever a your target is denied their Dexterity bonus to Armor Class (if any) against your attack, you deal an extra %1d6 points of damage with your attack. You can't use sudden strike when flanking an opponent unless that opponent is denied its Dexterity bonus to AC. This damage also applies to ranged attacks against targets up to 30 feet away. Creatures with concealment, creatures without discernible anatomies, and creatures immune to extra damage from critical hits are all immune to sudden strikes. You can't make a sudden strike while striking the limbs of a creature whose vitals are out of reach. You can't use sudden strike to deliver nonlethal damage. Weapons capable of dealing only nonlethal damage don't deal extra damage when used as part of a sudden strike. The extra damage from the sudden strike ability stacks with the extra damage from sneak attack whenever both would apply to the same target.|SuddenStrikeDice

### Skirmish

- **DEFINE:** SkirmishDieSize|0
- **DEFINE:** SkirmishDice|0
- **DEFINE:** SkirmishACBonus|0
- **DEFINE:** SkirmishLVL|0
- **BONUS:** VAR|SkirmishDieSize|6|TYPE=Base
- **BONUS:** VAR|SkirmishDice|(SkirmishLVL+3)/4
- **BONUS:** VAR|SkirmishACBonus|(SkirmishLVL+1)/4
- **ASPECT:** NAME|Skirmish (+%1d%2)|SkirmishDice|SkirmishDieSize
- **ASPECT:** NAME|Skirmish (+%1d%3, +%2 AC)|SkirmishDice|SkirmishACBonus|SkirmishDieSize

### Fast Movement

- **DEFINE:** FastMovementBonus|0
- **BONUS:** MOVEADD|TYPE.Walk|FastMovementBonus
- **ASPECT:** NAME|Fast Movement +%1 ft|FastMovementBonus

### Slow Fall

- **DEFINE:** SlowFallDistance|0
- **ASPECT:** NAME|Slow Fall %1 ft.|SlowFallDistance

### Disease


### Fear


### Turn Resistance


### Trip


### Tongues


### Telepathy

- **DEFINE:** TelepathyRange|0

%1 ft. range|TelepathyRange

### Summon Demon


### Summon Devil


### Split


### Spider Climb


### Scent

- **DEFINE:** ScentRange|0

%1 ft. range|ScentRange

### Roar

- **DEFINE:** RoarDC|0
- **BONUS:** VAR|RoarDC|DefaultDCCha
- **BONUS:** VAR|RoarDC|2

DC %1|RoarDC

### Regenerate in Water


### Rejuvenation


### Rake


You gain extra natural attacks when you grapple or pounce your foe.

### Martial Weapons

- **AUTO:** WEAPONPROF|TYPE=Martial

0 HD Outsider gains all Martial Weapon Proficiencies

### Hide in Plain Sight


Use the Hide skill even while being observed (except in natural daylight, the area of a daylight spell, or a similar effect).

### Immunity to Acid

- **ASPECT:** Immunity|Acid

You never take Acid damage

### Immunity to Cold

- **ASPECT:** Immunity|Cold

You never take Cold damage

### Immunity to Fire

- **ASPECT:** Immunity|Fire

You never take Fire damage

### Immunity to Electricity

- **ASPECT:** Immunity|Electricity

You never take Electricity damage

### Immunity to Sonic

- **ASPECT:** Immunity|Sonic

You never take Sonic damage

### Immunities ~ Su


### Immunity to All Mind Affecting Effects

- **ASPECT:** Immunity|All Mind Affecting Effects

You are never subject to mind affecting effects

### Immunity to Banishment

- **ASPECT:** Immunity|Banishment

You can never be banished

### Immunity to Blindness

- **ASPECT:** Immunity|Blindness

You can never be blinded

### Immunity to Charm Effects

- **ASPECT:** Immunity|Charm Effects

You are never subject to charm effects

### Immunity to Critical Hits

- **ASPECT:** Immunity|Critical Hits

You are never subject to critical hits

### Immunity to Charm

- **ASPECT:** Immunity|Charm

You are never subject to charm effects

### Immunity to Compulsion

- **ASPECT:** Immunity|Compulsion

You are never subject to compulsion effects

### Immunity to Death Effects

- **ASPECT:** Immunity|Death Effects

You are never subject to death effects

### Immunity to Disease

- **ASPECT:** Immunity|Disease

You never take disease damage

### Immunity to Disintegration

- **ASPECT:** Immunity|Disintegration

You can never be disintegrated

### Immunity to Energy Drain

- **ASPECT:** Immunity|Energy Drain

You can never be energy drained

### Immunity to Flanking

- **ASPECT:** Immunity|Flanking

You can never be flanked

### Immunity to Force

- **ASPECT:** Immunity|Force

You are never subject to force effects

### Immunity to Heat

- **ASPECT:** Immunity|Heat

You never take damage from heat

### Immunity to Learned Spell

- **ASPECT:** Immunity|Learned Spell

### Immunity to Light

- **ASPECT:** Immunity|Light

### Immunity to Magic

- **ASPECT:** Immunity|Magic

You are never subject to magical effects

### Immunity to Mind-Affecting

- **ASPECT:** Immunity|Mind-Affecting

You are never subject to mind-affecting effects

### Immunity to Paralysis

- **ASPECT:** Immunity|Paralysis

You can never be paralysed

### Immunity to Petrification

- **ASPECT:** Immunity|Petrification

You can never be petrified

### Immunity to Phantasms

- **ASPECT:** Immunity|Phantasms

You are never fooled by phantasms

### Immunity to Poison

- **ASPECT:** Immunity|Poison

You never take poison damage

### Immunity to Polymorph

- **ASPECT:** Immunity|Polymorph

You can never be polymorphed

### Immunity to Psionics

- **ASPECT:** Immunity|Psionics

You are never subject to psionics effects

### Immunity to Sleep

- **ASPECT:** Immunity|Sleep

You are never subject to sleep effects

### Immunity to Stunning

- **ASPECT:** Immunity|Stunning

You can never be stunned

### Immunity to Transformation

- **ASPECT:** Immunity|Transformation

You can never be transformed

### Immunity to Transmutation

- **ASPECT:** Immunity|Transmutation

You can never be transmutated

### Oozelike Immunities


### Spell Immunities


### Immunity to Ability Damage

- **ASPECT:** Immunity|Ability Damage

You are never subject to Ability Damage

### Immunity to Ability Drain

- **ASPECT:** Immunity|Ability Drain

You are never subject to Ability Drain

### Resistance to Acid

- **DEFINE:** AcidResistanceBonus|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Acid Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Acid,Vulnerability to Acid

### Resistance to Cold

- **DEFINE:** ColdResistanceBonus|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Cold Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Cold,Vulnerability to Cold

### Resistance to Fire

- **DEFINE:** FireResistanceBonus|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Fire Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Fire,Vulnerability to Fire

### Resistance to Electricity

- **DEFINE:** ElectricityResistanceBonus|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Electricity Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Electricity,Vulnerability to Electricity

### Resistance to Sonic

- **DEFINE:** SonicResistanceBonus|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Sonic Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Sonic,Vulnerability to Sonic

### Resistance to Acid Output

- **ASPECT:** SaveBonus|Acid Resistance %1|AcidResistanceBonus
- **ASPECT:** Resistance|Acid
- **ASPECT:** Ability Benefit|%1|AcidResistanceBonus

You may ignore %1 points of Acid damage each time you take Acid damage|AcidResistanceBonus

### Resistance to Cold Output

- **ASPECT:** SaveBonus|Cold Resistance %1|ColdResistanceBonus
- **ASPECT:** Resistance|Cold
- **ASPECT:** Ability Benefit|%1|ColdResistanceBonus

You may ignore %1 points of Cold damage each time you take Cold damage|ColdResistanceBonus

### Resistance to Fire Output

- **ASPECT:** SaveBonus|Fire Resistance %1|FireResistanceBonus
- **ASPECT:** Resistance|Fire
- **ASPECT:** Ability Benefit|%1|FireResistanceBonus

You may ignore %1 points of Fire damage each time you take Fire damage|FireResistanceBonus

### Resistance to Electricity Output

- **ASPECT:** SaveBonus|Electricity Resistance %1|ElectricityResistanceBonus
- **ASPECT:** Resistance|Electricity
- **ASPECT:** Ability Benefit|%1|ElectricityResistanceBonus

You may ignore %1 points of Electricity damage each time you take Electricity damage|ElectricityResistanceBonus

### Resistance to Sonic Output

- **ASPECT:** SaveBonus|Sonic Resistance %1|SonicResistanceBonus
- **ASPECT:** Resistance|Sonic
- **ASPECT:** Ability Benefit|%1|SonicResistanceBonus

You may ignore %1 points of Sonic damage each time you take Sonic damage|SonicResistanceBonus

### Resistance to Charm

- **ASPECT:** Resistance|Charm

### Vulnerability to Acid


You take half again as much (+50%%) damage as normal from Acid, regardless of whether a saving throw is allowed, or if the save is a success or failure

### Vulnerability to Cold


You take half again as much (+50%%) damage as normal from Cold, regardless of whether a saving throw is allowed, or if the save is a success or failure

### Vulnerability to Fire


You take half again as much (+50%%) damage as normal from Fire, regardless of whether a saving throw is allowed, or if the save is a success or failure

### Vulnerability to Electricity


You take half again as much (+50%%) damage as normal from Electricity, regardless of whether a saving throw is allowed, or if the save is a success or failure

### Vulnerability to Sonic


You take half again as much (+50%%) damage as normal from Sonic, regardless of whether a saving throw is allowed, or if the save is a success or failure

### Vulnerability to Sunlight


### Vulnerability to Protection from Evil


### Telepathic Bond


### Resistance to Fear

- **DEFINE:** FearResistanceBonus|0
- **ABILITY:** Special Ability|VIRTUAL|Resistance to Fear Output|!PREABILITY:1,CATEGORY=Special Ability,Immunity to Fear,Vulnerability to Fear

### Resistance to Fear Output

- **ASPECT:** Resistance|Fear
- **ASPECT:** Ability Benefit|+%1|FearResistanceBonus

You add +%1 to save against Fear effects|FearResistanceBonus

### Weapon of the Deity


### Alarm (Sp)

- **DEFINE:** AlarmPerDay|0
- **DEFINE:** AlarmLVL|0
- **SPELLS:** Innate|TIMES=AlarmPerDay|CASTERLEVEL=AlarmLVL|Alarm,11+CHA

### Animate Dead


### Animate Dead (Sp/no component)

- **DEFINE:** AnimateDeadPerDay|0
- **DEFINE:** AnimateDeadLVL|0
- **SPELLS:** Innate|TIMES=AnimateDeadPerDay|CASTERLEVEL=AnimateDeadLVL|Animate Dead,14+CHA

no component

### Arcane Sight (Sp always active)


always active

### Arcane Sight (Sp)

- **DEFINE:** ArcaneSightPerDay|0
- **DEFINE:** ArcaneSightLVL|0
- **SPELLS:** Innate|TIMES=ArcaneSightPerDay|CASTERLEVEL=ArcaneSightLVL|Arcane Sight,13+WIS

%1/day|ArcaneSightPerDay

### Augury (Sp)

- **DEFINE:** AuguryTimes|0
- **DEFINE:** AuguryLVL|0
- **SPELLS:** Innate|TIMES=AuguryTimes|CASTERLEVEL=AuguryLVL|Augury,12

### Blasphemy (Sp)

- **DEFINE:** BlasphemyPerDay|0
- **DEFINE:** BlasphemyLVL|0
- **SPELLS:** Innate|TIMES=BlasphemyPerDay|CASTERLEVEL=BlasphemyLVL|Blasphemy,17+CHA

### Bless (Sp)

- **DEFINE:** BlessPerDay|0
- **DEFINE:** BlessLVL|0
- **SPELLS:** Innate|TIMES=BlessPerDay|CASTERLEVEL=BlessLVL|Bless,11+CHA

### Blink (Sp)


### Blur (Sp)


### Burning Hands (Sp)

- **DEFINE:** BurningHandsPerDay|0
- **DEFINE:** BurningHandsLVL|0
- **SPELLS:** Innate|TIMES=BurningHandsPerDay|CASTERLEVEL=BurningHandsLVL|Burning Hands,11+CHA

### Cause Fear (Sp)

- **DEFINE:** CauseFearPerDay|0
- **DEFINE:** CauseFearLVL|0
- **SPELLS:** Innate|TIMES=CauseFearPerDay|CASTERLEVEL=CauseFearLVL|Cause Fear,11+CHA

### Charm Monster (Mass/Sp)

- **DEFINE:** CharmMonsterMassPerDay|0
- **DEFINE:** CharmMonsterMassLVL|0
- **SPELLS:** Innate|TIMES=CharmMonsterMassPerDay|CASTERLEVEL=CharmMonsterMassLVL|Charm Monster (Mass),18+CHA

### Charm Monster (Sp)

- **DEFINE:** CharmMonsterPerDay|0
- **DEFINE:** CharmMonsterLVL|0
- **SPELLS:** Innate|TIMES=CharmMonsterPerDay|CASTERLEVEL=CharmMonsterLVL|Charm Monster,13+CHA

### Charm Person (Sp)

- **DEFINE:** CharmPersonPerDay|0
- **DEFINE:** CharmPersonLVL|0
- **SPELLS:** Innate|TIMES=CharmPersonPerDay|CASTERLEVEL=CharmPersonLVL|Charm Person,11+CHA

### Clairaudience (Sp)

- **DEFINE:** ClairaudiencePerDay|0
- **DEFINE:** ClairaudienceLVL|0
- **SPELLS:** Innate|TIMES=ClairaudiencePerDay|CASTERLEVEL=ClairaudienceLVL|Clairaudience/Clairvoyance,13+CHA

### Command (Sp)

- **DEFINE:** CommandPerDay|0
- **DEFINE:** CommandLVL|0
- **SPELLS:** Innate|TIMES=CommandPerDay|CASTERLEVEL=CommandLVL|Command,11+CHA

### Commune with Nature (Sp once month)

- **DEFINE:** CommuneWithNaturePerMonth|0

%1/month|CommuneWithNaturePerMonth

### Commune with Nature (Sp)

- **DEFINE:** CommuneWithNaturePerDay|0
- **DEFINE:** CommuneWithNatureLVL|0
- **SPELLS:** Innate|TIMES=CommuneWithNaturePerDay|CASTERLEVEL=CommuneWithNatureLVL|Commune with Nature,14+CHA

### Confusion


### Confusion (Sp)

- **DEFINE:** ConfusionPerDay|0
- **DEFINE:** ConfusionDC|0
- **BONUS:** VAR|ConfusionDC|10+INT
- **SPELLS:** Innate|TIMES=ConfusionPerDay|CASTERLEVEL=ConfusionLVL|Confusion,13+INT

%1/day (Will DC %2)|ConfusionPerDay|ConfusionDC

### Confusion (Sp/6 round)

- **DEFINE:** ConfusionLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=ConfusionLVL|Confusion,14+CHA

once every 1d6

### Confusion (Sp/CHA/at will)

- **DEFINE:** ConfusionLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=ConfusionLVL|Confusion,14+CHA

### Contagion (Sp)

- **DEFINE:** ContagionPerDay|0
- **DEFINE:** ContagionLVL|0
- **SPELLS:** Innate|TIMES=ContagionPerDay|CASTERLEVEL=ContagionLVL|Contagion,13+CHA

### Contagion (Sp/WIS)

- **DEFINE:** ContagionPerDay|0
- **DEFINE:** ContagionLVL|0
- **SPELLS:** Innate|TIMES=ContagionPerDay|CASTERLEVEL=ContagionLVL|Contagion,13+WIS

### Control Undead (Sp)


### Control Water (Sp)

- **DEFINE:** ControlWaterPerDay|0
- **DEFINE:** ControlWaterLVL|0
- **SPELLS:** Innate|TIMES=ControlWaterPerDay|CASTERLEVEL=ControlWaterLVL|Control Water,16+CHA

### Control Winds

- **DEFINE:** ControlWindsLVL|0
- **DEFINE:** ControlWindsTimes|0
- **SPELLS:** Control Winds|TIMES=ControlWindsTimes|CASTERLEVEL=ControlWindsLVL|Control Winds

### Create Greater Undead (Sp)

- **DEFINE:** CreateGreaterUndeadPerDay|0
- **DEFINE:** CreateGreaterUndeadLVL|0
- **SPELLS:** Innate|TIMES=CreateGreaterUndeadPerDay|CASTERLEVEL=CreateGreaterUndeadLVL|Create Greater Undead,18+CHA

### Create Undead (Sp)

- **DEFINE:** CreateUndeadPerDay|0
- **DEFINE:** CreateUndeadLVL|0
- **SPELLS:** Innate|TIMES=CreateUndeadPerDay|CASTERLEVEL=CreateUndeadLVL|Create Undead,16+CHA

### Creeping Doom (Sp)

- **DEFINE:** CreepingDoomPerDay|0
- **DEFINE:** CreepingDoomLVL|0
- **SPELLS:** Innate|TIMES=CreepingDoomPerDay|CASTERLEVEL=CreepingDoomLVL|Creeping Doom

### Crushing Despair (Sp)

- **DEFINE:** CrushingDespairPerDay|0
- **DEFINE:** CrushingDespairLVL|0
- **SPELLS:** Innate|TIMES=CrushingDespairPerDay|CASTERLEVEL=CrushingDespairLVL|Crushing Despair,14+CHA

### Darkness (Sp)

- **DEFINE:** DarknessPerDay|0
- **DEFINE:** DarknessLVL|0
- **SPELLS:** Innate|TIMES=DarknessPerDay|CASTERLEVEL=DarknessLVL|Darkness,12+CHA

### Daylight (Sp at will)

- **DEFINE:** DaylightLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DaylightLVL|Daylight,13+CHA

### Daylight (Sp)

- **DEFINE:** DaylightLVL|0
- **DEFINE:** DaylightPerDay|0
- **SPELLS:** Innate|TIMES=DaylightPerDay|CASTERLEVEL=DaylightLVL|Daylight,13+CHA

### Death Knell (Sp)

- **DEFINE:** DeathKnellPerDay|0
- **DEFINE:** DeathKnellLVL|0
- **SPELLS:** Innate|TIMES=DeathKnellPerDay|CASTERLEVEL=DeathKnellLVL|Death Knell,12+CHA

### Death Knell (Sp/At will)

- **DEFINE:** DeathKnellLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=DeathKnellLVL|Death Knell,12+CHA

### Death Knell (Sp/Wis)

- **DEFINE:** DeathKnellPerDay|0
- **DEFINE:** DeathKnellLVL|0
- **SPELLS:** Innate|TIMES=DeathKnellPerDay|CASTERLEVEL=DeathKnellLVL|Death Knell,12+WIS

### Death Touch (Sp)

- **DEFINE:** DeathTouchPerDay|0
- **DEFINE:** DeathTouchDC|0
- **BONUS:** VAR|DeathTouchDC|10+CHA

%1/day (Fort DC %2)|DeathTouchPerDay|DeathTouchDC

### Death Ward (Sp)

- **DEFINE:** DeathWardPerDay|0
- **DEFINE:** DeathWardLVL|0
- **SPELLS:** Innate|TIMES=DeathWardPerDay|CASTERLEVEL=DeathWardLVL|Death Ward,14+WIS

### Deathwatch (Sp always active)


always active

### Deeper Darkness (Sp)

- **DEFINE:** DeeperDarknessLVL|0
- **DEFINE:** DeeperDarknessTimes|0
- **SPELLS:** Innate|TIMES=DeeperDarknessTimes|CASTERLEVEL=DeeperDarknessLVL|Deeper Darkness,13+CHA

### Desecrate (Sp)

- **DEFINE:** DesecratePerDay|0
- **DEFINE:** DesecrateLVL|0
- **SPELLS:** Innate|TIMES=DesecratePerDay|CASTERLEVEL=DesecrateLVL|Desecrate,12+CHA

### Disintegrate (Sp)

- **DEFINE:** DisintegratePerDay|0
- **DEFINE:** DisintegrateLVL|0
- **SPELLS:** Innate|TIMES=DisintegratePerDay|CASTERLEVEL=DisintegrateLVL|Disintegrate,16+CHA

### Dismissal (Sp)

- **DEFINE:** DismissalPerDay|0
- **DEFINE:** DismissalLVL|0
- **SPELLS:** Innate|TIMES=DismissalPerDay|CASTERLEVEL=DismissalLVL|Dismissal,14+CHA

### Dispel Evil

- **DEFINE:** DispelEvilTimes|0

%1/week|DispelEvilTimes

### Dispel Magic

- **DEFINE:** DispelMagicTimes|0

+%1 (%2/day)|BlessingScriptureBonus|DispelMagicTimes

### Dispel Magic (Sp)

- **DEFINE:** DispelMagicPerDay|0
- **DEFINE:** DispelMagicLVL|0
- **SPELLS:** Innate|TIMES=DispelMagicPerDay|CASTERLEVEL=DispelMagicLVL|Dispel Magic,13+CHA

### Divination (Sp)

- **DEFINE:** DivinationPerDay|0
- **DEFINE:** DivinationLVL|0
- **SPELLS:** Innate|TIMES=DivinationPerDay|CASTERLEVEL=DivinationLVL|Divination,10+CHA

### Dominate (Sp)

- **DEFINE:** DominatePerDay|0

%1/day|DominatePerDay

### Earthquake (Sp)

- **DEFINE:** EarthquakePerDay|0
- **DEFINE:** EarthquakeLVL|0
- **SPELLS:** Innate|TIMES=EarthquakePerDay|CASTERLEVEL=EarthquakeLVL|Earthquake,19+CHA

### Energy Drain (Sp)

- **DEFINE:** EnergyDrainPerDay|0
- **DEFINE:** EnergyDrainLVL|0
- **SPELLS:** Innate|TIMES=EnergyDrainPerDay|CASTERLEVEL=EnergyDrainLVL|Energy Drain,19+CHA

### Enervation (Sp)

- **DEFINE:** EnervationPerDay|0
- **DEFINE:** EnervationLVL|0
- **SPELLS:** Innate|TIMES=EnervationPerDay|CASTERLEVEL=EnervationLVL|Enervation,14+CHA

### Ethereal Jaunt (Sp)

- **DEFINE:** EtherealJauntPerDay|0
- **DEFINE:** EtherealJauntLVL|0
- **SPELLS:** Innate|TIMES=EtherealJauntPerDay|CASTERLEVEL=EtherealJauntLVL|Ethereal Jaunt

### Etherealness (Sp)

- **DEFINE:** EtherealnessPerDay|0
- **DEFINE:** EtherealnessLVL|0
- **SPELLS:** Innate|TIMES=EtherealnessPerDay|CASTERLEVEL=EtherealnessLVL|Etherealness,19+WIS

### Fascinate (Sp)


### Fear (Sp)

- **DEFINE:** FearPerDay|0
- **DEFINE:** FearLVL|0
- **SPELLS:** Innate|TIMES=FearPerDay|CASTERLEVEL=FearLVL|Fear,13+CHA

### Feather Fall (Sp)

- **DEFINE:** FeatherFallPerDay|0
- **DEFINE:** FeatherFallLVL|0
- **SPELLS:** Innate|TIMES=FeatherFallPerDay|CASTERLEVEL=FeatherFallLVL|Feather Fall

### Feather Falls (Sp at will)

- **DEFINE:** FeatherFallLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=FeatherFallLVL|Feather Fall

### Fire Shield (Sp)

- **DEFINE:** FireShieldPerDay|0
- **DEFINE:** FireShieldLVL|0
- **SPELLS:** Innate|TIMES=FireShieldPerDay|CASTERLEVEL=FireShieldLVL|Fire Shield,14+CHA

### Fire Shield (Sp/at will)

- **DEFINE:** FireShieldLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=FireShieldLVL|Fire Shield

### Fireball (Sp/maximized)

- **DEFINE:** FireballPerDay|0
- **DEFINE:** FireballLVL|0
- **SPELLS:** Innate|TIMES=FireballPerDay|CASTERLEVEL=FireballLVL|Fireball,13+CHA

maximized

### Fog Cloud (Sp)

- **DEFINE:** FogCloudPerDay|0
- **DEFINE:** FogCloudLVL|0
- **SPELLS:** Innate|TIMES=FogCloudPerDay|CASTERLEVEL=FogCloudLVL|Fog Cloud

### Freedom of Movement (Sp always active)


always active

### Freedom of Movement (Sp)

- **DEFINE:** FreedomOfMovementTimes|0
- **DEFINE:** FreedomOfMovementLVL|0
- **SPELLS:** Innate|TIMES=FreedomOfMovementTimes|CASTERLEVEL=FreedomOfMovementLVL|Freedom of Movement,14+WIS

### Geas (Sp)

- **DEFINE:** GeasPerDay|0
- **DEFINE:** GeasLVL|0
- **SPELLS:** Innate|TIMES=GeasPerDay|CASTERLEVEL=GeasLVL|Geas/Quest

### Glyph of Warding (Sp)

- **DEFINE:** GlyphOfWardingLVL|0
- **DEFINE:** GlyphOfWardingPerDay|0
- **SPELLS:** Innate|TIMES=GlyphOfWardingPerDay|CASTERLEVEL=GlyphOfWardingLVL|Glyph of Warding,13+CHA

### Greater Dispelling (Sp at will)

- **DEFINE:** GreaterDispellingLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=GreaterDispellingLVL|Dispel Magic (Greater)

### Greater Teleport (Sp)

- **DEFINE:** GreaterTeleportPerDay|0
- **DEFINE:** GreaterTeleportLVL|0
- **SPELLS:** Innate|TIMES=GreaterTeleportPerDay|CASTERLEVEL=GreaterTeleportLVL|Teleport (Greater),17+CHA

### Growth (Sp)

- **DEFINE:** GrowthPerDay|0
- **DEFINE:** GrowthLVL|0
- **SPELLS:** Innate|TIMES=GrowthPerDay|CASTERLEVEL=GrowthLVL|Animal Growth,10

### Haste (Sp)

- **DEFINE:** HasteTimes|0
- **DEFINE:** HasteLVL|0
- **SPELLS:** Innate|TIMES=HasteTimes|CASTERLEVEL=HasteLVL|Haste,13+WIS

### Heal (Sp/self)

- **DEFINE:** HealPerDay|0
- **DEFINE:** HealLVL|0
- **SPELLS:** Innate|TIMES=HealPerDay|CASTERLEVEL=HealLVL|Heal,16+CHA

self only

### Heroes Feast (Sp)

- **DEFINE:** HeroesFeastTimes|0
- **DEFINE:** HeroesFeastLVL|0
- **SPELLS:** Innate|TIMES=HeroesFeastTimes|CASTERLEVEL=HeroesFeastLVL|Heroes' Feast,16+WIS

### Heroes Feast (Sp/week)

- **DEFINE:** HeroesFeastTimes|0
- **DEFINE:** HeroesFeastLVL|0
- **SPELLS:** Innate|TIMES=HeroesFeastTimes|TIMEUNIT=Week|CASTERLEVEL=HeroesFeastLVL|Heroes' Feast,16+WIS

### Hold Monster (Sp)

- **DEFINE:** HoldMonsterPerDay|0
- **DEFINE:** HoldMonsterLVL|0
- **SPELLS:** Innate|TIMES=HoldMonsterPerDay|CASTERLEVEL=HoldMonsterLVL|Hold Monster,14+CHA

### Hold Monster (Sp/3 rounds)

- **DEFINE:** HoldMonsterDC|0
- **BONUS:** VAR|HoldMonsterDC|15+CHA

1/3 rounds (Will DC %1)|HoldMonsterDC

### Holy Aura

- **DEFINE:** HolyAuraTimes|0

%1/day|HolyAuraTimes

### Holy Aura (Sp/wis)

- **DEFINE:** HolyAuraLVL|0
- **DEFINE:** HolyAuraTimes|0
- **SPELLS:** Innate|TIMES=HolyAuraTimes|CASTERLEVEL=HolyAuraLVL|Holy Aura,18+WIS

### Holy Smite (Sp at will)

- **DEFINE:** HolySmiteLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=HolySmiteLVL|Holy Smite,14+CHA

### Holy Smite (Sp)

- **DEFINE:** HolySmitePerDay|0
- **DEFINE:** HolySmiteLVL|0
- **SPELLS:** Innate|TIMES=HolySmitePerDay|CASTERLEVEL=HolySmiteLVL|Holy Smite,14+CHA

### Holy Smite (Sp/Wis)

- **DEFINE:** HolySmitePerDay|0
- **DEFINE:** HolySmiteLVL|0
- **SPELLS:** Innate|TIMES=HolySmitePerDay|CASTERLEVEL=HolySmiteLVL|Holy Smite,14+WIS

### Holy Sword (Sp)

- **DEFINE:** HolySwordTimes|0
- **DEFINE:** HolySwordLVL|0
- **SPELLS:** Innate|TIMES=HolySwordTimes|CASTERLEVEL=HolySwordLVL|Holy Sword,14+WIS

### Horrid Wilting (Sp)

- **DEFINE:** HorridWiltingPerDay|0
- **DEFINE:** HorridWiltingLVL|0
- **SPELLS:** Innate|TIMES=HorridWiltingPerDay|CASTERLEVEL=HorridWiltingLVL|Horrid Wilting,18+CHA

### Hypnosis (Sp)

- **DEFINE:** HypnosisPerDay|0
- **DEFINE:** HypnosisDC|0
- **BONUS:** VAR|HypnosisDC|10+CHA

%1/day (Will DC %2)|HypnosisPerDay|HypnosisDC

### Hypnotism (Sp)

- **DEFINE:** HypnotismPerDay|0
- **DEFINE:** HypnotismLVL|0
- **SPELLS:** Innate|TIMES=HypnotismPerDay|CASTERLEVEL=HypnotismLVL|Hypnotism,10+CHA

### Inflict Light Wounds (Sp)

- **DEFINE:** InflictLightWoundsPerDay|0
- **DEFINE:** InflictLightWoundsLVL|0
- **SPELLS:** Innate|TIMES=InflictLightWoundsPerDay|CASTERLEVEL=InflictLightWoundsLVL|Inflict Light Wounds,11+CHA

### Insanity (Sp)

- **DEFINE:** InsanityPerDay|0
- **DEFINE:** InsanityDC|0

%1/day (Will DC %2)|InsanityPerDay|InsanityDC

### Insect Plague (Sp)

- **DEFINE:** InsectPlaguePerDay|0
- **DEFINE:** InsectPlagueLVL|0
- **SPELLS:** Innate|TIMES=InsectPlaguePerDay|CASTERLEVEL=InsectPlagueLVL|Insect Plague

### Ironskin (Sp)

- **DEFINE:** IronskinPerDay|0
- **DEFINE:** IronskinLVL|0
- **SPELLS:** Innate|TIMES=IronskinPerDay|CASTERLEVEL=IronskinLVL|Stoneskin,14+CHA

### Limited wish (Sp once year)

- **DEFINE:** LimitedWishPerYear|0

%1/year|LimitedWishPerYear

### Locate Creature (Sp)

- **DEFINE:** LocateCreatureLVL|0
- **DEFINE:** LocateCreatureTimes|0
- **SPELLS:** Innate|TIMES=LocateCreatureTimes|CASTERLEVEL=LocateCreatureLVL|Locate Creature,14+CHA

### Locate Object (Sp)

- **DEFINE:** LocateObjectLVL|0
- **DEFINE:** LocateObjectTimes|0
- **SPELLS:** Innate|TIMES=LocateObjectTimes|CASTERLEVEL=LocateObjectLVL|Locate Object,13+WIS

### Magic Aura (Sp at will)

- **DEFINE:** MagicAuraLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=MagicAuraLVL|Magic Aura,11+CHA

### Magic Circle against Evil (Sp always active)


always active

### Magic Missile (Sp)


### Major Creation (Sp)

- **DEFINE:** MajorCreationPerDay|0
- **DEFINE:** MajorCreationLVL|0
- **SPELLS:** Innate|TIMES=MajorCreationPerDay|CASTERLEVEL=MajorCreationLVL|Major Creation

### Meld into Stone (Sp)

- **DEFINE:** MeldIntoStonePerDay|0
- **DEFINE:** MeldIntoStoneLVL|0
- **SPELLS:** Innate|TIMES=MeldIntoStonePerDay|CASTERLEVEL=MeldIntoStoneLVL|Meld into Stone,13+CHA

### Nondetection


constant nondetection.

### Passwall (Sp)

- **DEFINE:** PasswallTimes|0
- **DEFINE:** PasswallLVL|0
- **SPELLS:** Innate|TIMES=PasswallTimes|CASTERLEVEL=PasswallLVL|Passwall,15

### Plane Shift (Sp at will)

- **DEFINE:** PlaneShiftLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=PlaneShiftLVL|Plane Shift,15+CHA

### Plane Shift (Sp)

- **DEFINE:** PlaneShiftLVL|0
- **DEFINE:** PlaneShiftPerDay|0
- **SPELLS:** Innate|TIMES=PlaneShiftPerDay|CASTERLEVEL=PlaneShiftLVL|Plane Shift,15+CHA

### Poison (Sp at will/con)

- **DEFINE:** PoisonLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=PoisonLVL|Poison,13+CON

### Poison (Sp)

- **DEFINE:** PoisonPerDay|0
- **DEFINE:** PoisonLVL|0
- **SPELLS:** Innate|TIMES=PoisonPerDay|CASTERLEVEL=PoisonLVL|Poison,14+CHA

### Poison (Sp/WIS)

- **DEFINE:** PoisonPerDay|0
- **DEFINE:** PoisonLVL|0
- **SPELLS:** Innate|TIMES=PoisonPerDay|CASTERLEVEL=PoisonLVL|Poison,14+WIS

### Protection from Evil (Sp always active)


always active

### Protection from Evil (Sp at will)

- **DEFINE:** ProtectionFromEvilLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=ProtectionFromEvilLVL|Protection from Evil,11+CHA

### Quickened Call Lightning (Sp)

- **DEFINE:** QuickCallLightningPerDay|0
- **DEFINE:** QuickCallLightningLVL|0
- **SPELLS:** Innate|TIMES=QuickCallLightningPerDay|CASTERLEVEL=QuickCallLightningLVL|Call Lightning,13+CHA

### Quickened Call Lightning Storm (Sp)

- **DEFINE:** QuickCallLightningStormPerDay|0
- **DEFINE:** QuickCallLightningStormLVL|0
- **SPELLS:** Innate|TIMES=QuickCallLightningStormPerDay|CASTERLEVEL=QuickCallLightningStormLVL|Call Lightning Storm,15+CHA

### Reduce (Sp)

- **DEFINE:** ReducePersonTimes|0
- **DEFINE:** ReducePersonLVL|0
- **SPELLS:** Innate|TIMES=ReducePersonTimes|CASTERLEVEL=ReducePersonLVL|Reduce Person,11

### Sanctuary (Sp)


### Scrying (Sp)

- **DEFINE:** ScryingPerDay|0
- **DEFINE:** ScryingLVL|0
- **SPELLS:** Innate|TIMES=ScryingPerDay|CASTERLEVEL=ScryingLVL|Scrying,14+CHA

### See Invisibility (Sp at will)

- **DEFINE:** SeeInvisibilityLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=SeeInvisibilityLVL|See Invisibility

### Shield of Faith (Sp)

- **DEFINE:** ShieldOfFaithPerDay|0
- **DEFINE:** ShieldOfFaithLVL|0
- **SPELLS:** Innate|TIMES=ShieldOfFaithPerDay|CASTERLEVEL=ShieldOfFaithLVL|Shield of Faith,11+CHA

### Shield Other (Sp)

- **DEFINE:** ShieldOtherPerDay|0
- **DEFINE:** ShieldOtherLVL|0
- **SPELLS:** Innate|TIMES=ShieldOtherPerDay|CASTERLEVEL=ShieldOtherLVL|Shield Other,12+CHA

### Shocking Grasp (Sp)

- **DEFINE:** ShockingGraspPerDay|0
- **DEFINE:** ShockingGraspLVL|0
- **SPELLS:** Innate|TIMES=ShockingGraspPerDay|CASTERLEVEL=ShockingGraspLVL|Shocking Grasp

### Sleep (Sp)

- **DEFINE:** SleepPerDay|0
- **DEFINE:** SleepLVL|0
- **SPELLS:** Innate|TIMES=SleepPerDay|CASTERLEVEL=SleepLVL|Sleep,11+CHA

### Sleep (Sp/3 round)

- **DEFINE:** SleepLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=SleepLVL|Sleep,11+CHA

once every 1d3

### Speak with Animals (Sp at will)

- **DEFINE:** SpeakWithAnimalsLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=SpeakWithAnimalsLVL|Speak with Animals,11+CHA

### Speak with Animals (Sp)

- **DEFINE:** SpeakWithAnimalsTimes|0
- **DEFINE:** SpeakWithAnimalsLVL|0
- **SPELLS:** Innate|TIMES=SpeakWithAnimalsTimes|CASTERLEVEL=SpeakWithAnimalsLVL|Speak with Animals,11+CHA

### Speak with Dead (Sp)

- **DEFINE:** SpeakWithDeadTimes|0
- **DEFINE:** SpeakWithDeadLVL|0
- **SPELLS:** Innate|TIMES=SpeakWithDeadTimes|CASTERLEVEL=SpeakWithDeadLVL|Speak with Dead,13+CHA

### Speak with Plants (Sp at will)

- **DEFINE:** SpeakWithPlantsLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=SpeakWithPlantsLVL|Speak with Plants,12+CHA

### Spike Stones (Sp)

- **DEFINE:** SpikeStonesPerDay|0
- **DEFINE:** SpikeStonesLVL|0
- **SPELLS:** Innate|TIMES=SpikeStonesPerDay|CASTERLEVEL=SpikeStonesLVL|Spike Stones,14+CHA

### Stone Shape (Sp)

- **DEFINE:** StoneShapePerDay|0
- **DEFINE:** StoneShapeLVL|0
- **SPELLS:** Innate|TIMES=StoneShapePerDay|CASTERLEVEL=StoneShapeLVL|Stone Shape,14+CHA

### Stone Tell (Sp)

- **DEFINE:** StoneTellPerDay|0
- **DEFINE:** StoneTellLVL|0
- **SPELLS:** Innate|TIMES=StoneTellPerDay|CASTERLEVEL=StoneTellLVL|Stone Tell,16+CHA

### Stone to Flesh (Sp at will)

- **DEFINE:** StoneToFleshLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=StoneToFleshLVL|Stone to Flesh,16+CHA

### Suggestion (Sp)

- **DEFINE:** SuggestionPerDay|0
- **DEFINE:** SuggestionLVL|0
- **SPELLS:** Innate|TIMES=SuggestionPerDay|CASTERLEVEL=SuggestionLVL|Suggestion,13+CHA

### Tongues (Sp at will)

- **DEFINE:** TonguesLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=TonguesLVL|Tongues

### Touch of Fear (Sp)

- **DEFINE:** TouchOfFearPerDay|0
- **DEFINE:** TouchOfFearDC|0
- **BONUS:** VAR|TouchOfFearDC|10+CHA

%1/day (Will DC %2)|TouchOfFearPerDay|TouchOfFearDC

### Transmute Rock to Mud (Sp)

- **DEFINE:** TransmuteRokToMudPerDay|0
- **DEFINE:** TransmuteRokToMudLVL|0
- **SPELLS:** Innate|TIMES=TransmuteRokToMudPerDay|CASTERLEVEL=TransmuteRokToMudLVL|Transmute Rock to Mud,15+CHA

### True Strike (Sp/atwill)

- **DEFINE:** TrueStrikeLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=TrueStrikeLVL|True Strike

### True Strike (Sp/Dragons)

- **DEFINE:** TrueStrikeDragonsPerDay|0

%1/day against dragons|TrueStrikeDragonsPerDay

### Water Breathing (Sp)

- **DEFINE:** WaterBreathingPerDay|0
- **DEFINE:** WaterBreathingLVL|0
- **SPELLS:** Innate|TIMES=WaterBreathingPerDay|CASTERLEVEL=WaterBreathingLVL|Water Breathing,13+CHA

### Water Breathing (Sp/at will)

- **DEFINE:** WaterBreathingLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=WaterBreathingLVL|Water Breathing,13+CHA

### Wish (Sp)

- **DEFINE:** WishPerDay|0
- **DEFINE:** WishLVL|0
- **SPELLS:** Innate|TIMES=WishPerDay|CASTERLEVEL=WishLVL|Wish

### Word of Recall (Sp)

- **DEFINE:** WordOfRecallPerDay|0
- **DEFINE:** WordOfRecallLVL|0
- **SPELLS:** Innate|TIMES=WordOfRecallPerDay|CASTERLEVEL=WordOfRecallLVL|Word of Recall,16+CHA

### Shatter (Sp)

- **DEFINE:** ShatterPerDay|0
- **DEFINE:** ShatterLVL|0
- **SPELLS:** Innate|TIMES=ShatterPerDay|CASTERLEVEL=ShatterLVL|Shatter,12+CHA

### Endure Elements (Sp/atwill)

- **DEFINE:** EndureElementsLVL|0
- **SPELLS:** Innate|TIMES=ATWILL|CASTERLEVEL=EndureElementsLVL|Endure Elements,11+CHA

### Charming Gaze


### Constrict


### Corrupting Gaze


### Corrupting Touch


### Death Gaze


### Draining Touch


### Fists


### Frightful Moan


### Gaze


### Horrific Appearance


### Improved Grab


### Keening


### Malevolence


### Paralysis


### Paralyzing Touch


### Poison


### Pounce


### Ray


### Seduction


### Soul Portal


### Sound Imitation


### Stench


### Swallow Whole


### Telekinesis


### Trample


### Acid Spray


### Aversion


### Babble


### Bay


### Beard


### Black Cloud


### Charm Person


### Corporeal Instability


### Dance of Ruin


### Dancing Chains


### Distraction


### Energy Drain


### Enslave


### Entangle


### Eye Rays


### Fear Aura


### Fiddle


### Infernal Wound


### Mucus Cloud


### Paralytic Tentacles


### Petrification


### Petrifying Gaze


### Pixie Arrow


### Slime


### Slow


### Smite


### Smoke Claws


### Spit Acid


### Stampede


### Stun


### Stunning Screech


### Trap Essence


### Trumpet


### Unnerving Gaze


### Whirlwind Blast


### Acid


### Adhesive


### Blinding Beauty


### Burn


### Captivating Song


### Change Size


### Combustion


### Constitution Drain


### Crush Item


### Curse of Lycanthropy


### Death Throes


### Despair


### Dominate Monster


### Domination


### Drag


### Engulf


### Evil Eye


### Evil Gaze


### Fiery Aura


### Fists of Thunder and Lightning


### Gibbering


### Heat


### Howl


### Implant


### Ink Cloud


### Kiss


### Magic Drain


### Melt Weapons


### Mind Blast


### Mummy Rot


### Pipes


### Quills


### Rust


### Scare


### Shriek


### Slaad Fever


### Spittle


### Stunning Croak


### Stunning Glance


### Stunning Shock


### Trill


### Weakness


### Whirlwind


## Biosettings

### AGESET:0|Undefined


### RACENAME:Human%

- **SEX:** Male[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]Female[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]
- **BASEAGE:** 0
- **MAXAGE:** 7

### RACENAME:Dwarf%

- **SEX:** Male[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]Female[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]
- **BASEAGE:** 0
- **MAXAGE:** 19

### RACENAME:Elf%

- **SEX:** Male[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]Female[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]
- **BASEAGE:** 0
- **MAXAGE:** 54

### RACENAME:Gnome%

- **SEX:** Male[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]Female[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]
- **BASEAGE:** 0
- **MAXAGE:** 19

### RACENAME:Half-Elf%

- **SEX:** Male[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]Female[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]
- **BASEAGE:** 0
- **MAXAGE:** 9

### RACENAME:Half-Orc%

- **SEX:** Male[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]Female[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]
- **BASEAGE:** 0
- **MAXAGE:** 6

### RACENAME:Halfling%

- **SEX:** Male[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]Female[BASEHT:0|HTDIEROLL:0|BASEWT:0|WTDIEROLL:0|TOTALWT:0]
- **BASEAGE:** 0
- **MAXAGE:** 9

### AGESET:1|Youth


### AGESET:2|Adult


### AGESET:3|Middle-Aged


### AGESET:4|Old


### AGESET:5|Venerable


## Classes

### CLASS:Aberration

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Animal

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Animal (Will)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Construct

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Construct (Mindless)

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **LEVELSPERFEAT:** 0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Dragon

- **HD:** 12
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **DEFINE:** DragonLVL|0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** VAR|DragonLVL|CL
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Elemental

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Elemental (Air/Fire)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Elemental (Earth/Water)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Elemental (Mindless)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **LEVELSPERFEAT:** 0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Fey

- **HD:** 6
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Fey Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABPoor|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Giant

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Giant Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Humanoid

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Humanoid Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Humanoid (Fortitude)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Humanoid Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Humanoid (Will)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Humanoid Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Magical Beast

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Monstrous humanoid

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Monstrous Humanoid Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Ooze

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **LEVELSPERFEAT:** 0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Ooze (Intelligent)

- **HD:** 10
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Outsider

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Outsider Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")|TYPE=Base.REPLACE
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex,BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2

### CLASS:Plant

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Plant (Mindless)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **LEVELSPERFEAT:** 0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Undead

- **HD:** 12
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **ABILITY:** Special Ability|AUTOMATIC|Undead Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABPoor|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Undead (Mindless)

- **HD:** 12
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **LEVELSPERFEAT:** 0
- **ABILITY:** Special Ability|AUTOMATIC|Undead Proficiencies
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*1/2|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABPoor|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Will|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Fortitude,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Vermin

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **LEVELSPERFEAT:** 0
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Vermin (Intelligent)

- **HD:** 8
- **FACT:** ClassType|Monster
- **MAXLEVEL:** NOLIMIT
- **BONUS:** COMBAT|BASEAB|classlevel("APPLIEDAS=NONEPIC")*3/4|TYPE=Base.REPLACE
- **BONUS:** VAR|ClassBABModerate|classlevel("APPLIEDAS=NONEPIC")
- **BONUS:** SAVE|BASE.Fortitude|classlevel("APPLIEDAS=NONEPIC")/2+2
- **BONUS:** SAVE|BASE.Will,BASE.Reflex|classlevel("APPLIEDAS=NONEPIC")/3

### CLASS:Sorcerer/Cleric (Arcane)


### 1

- **CAST:** 5,3
- **KNOWN:** 4,2

### 2

- **CAST:** 6,4
- **KNOWN:** 5,2

### 3

- **CAST:** 6,5
- **KNOWN:** 5,3

### 4

- **CAST:** 6,6,3
- **KNOWN:** 6,3,1

### 5

- **CAST:** 6,6,4
- **KNOWN:** 6,4,2

### 6

- **CAST:** 6,6,5,3
- **KNOWN:** 7,4,2,1

### 7

- **CAST:** 6,6,6,4
- **KNOWN:** 7,5,3,2

### 8

- **CAST:** 6,6,6,5,3
- **KNOWN:** 8,5,3,2,1

### 9

- **CAST:** 6,6,6,6,4
- **KNOWN:** 8,5,4,3,2

### 10

- **CAST:** 6,6,6,6,5,3
- **KNOWN:** 9,5,4,3,2,1

### 11

- **CAST:** 6,6,6,6,6,4
- **KNOWN:** 9,5,5,4,3,2

### 12

- **CAST:** 6,6,6,6,6,5,3
- **KNOWN:** 9,5,5,4,3,2,1

### 13

- **CAST:** 6,6,6,6,6,6,4
- **KNOWN:** 9,5,5,4,4,3,2

### 14

- **CAST:** 6,6,6,6,6,6,5,3
- **KNOWN:** 9,5,5,4,4,3,2,1

### 15

- **CAST:** 6,6,6,6,6,6,6,4
- **KNOWN:** 9,5,5,4,4,4,3,2

### 16

- **CAST:** 6,6,6,6,6,6,6,5,3
- **KNOWN:** 9,5,5,4,4,4,3,2,1

### 17

- **CAST:** 6,6,6,6,6,6,6,6,4
- **KNOWN:** 9,5,5,4,4,4,3,3,2

### 18

- **CAST:** 6,6,6,6,6,6,6,6,5,3
- **KNOWN:** 9,5,5,4,4,4,3,3,2,1

### 19

- **CAST:** 6,6,6,6,6,6,6,6,6,4
- **KNOWN:** 9,5,5,4,4,4,3,3,3,2

### 20

- **CAST:** 6,6,6,6,6,6,6,6,6,6
- **KNOWN:** 9,5,5,4,4,4,3,3,3,3

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

### STARTPACK:Dragon Default Stat Array


### STAT:STR=11|DEX=10|CON=11|INT=10|WIS=11|CHA=10


### STARTPACK:Dragon Age 01 ~ Wyrmling

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### ABILITY:CATEGORY=Internal|Dragon Age Selected

- **FREE:** YES

### STARTPACK:Dragon Age 02 ~ Very Young

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### CLASS:Dragon

- **LEVEL:** 3

### STARTPACK:Dragon Age 03 ~ Young

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 04 ~ Juvenile

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 05 ~ Young Adult

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 06 ~ Adult

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 07 ~ Mature Adult

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 08 ~ Old

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 09 ~ Very Old

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 10 ~ Ancient

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 11 ~ Wyrm

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Dragon Age 12 ~ Great Wyrm

- **!PREABILITY:** 1,CATEGORY=Internal,Dragon Age Selected
- **PRERACE:** 1,RACETYPE=Dragon

### STARTPACK:Bronze Dragon Companion

- **PRERACE:** 1,Dragon (Bronze)

### STARTPACK:Familiar ~ Bat


### RACE:Companion ~ Bat

- **!PRERACE:** 1,%

### ALIGN:TN


### SKILL:Move Silently

- **RANK:** 4

### ABILITY:CATEGORY=FEAT|Alertness


### STAT:DEX=11|STR=10|CON=10|INT=10|WIS=10|CHA=10


### STARTPACK:Familiar ~ Cat


### RACE:Companion ~ Cat

- **!PRERACE:** 1,%

### SKILL:Listen

- **RANK:** 2

### SKILL:Spot

- **RANK:** 2

### ABILITY:CATEGORY=FEAT|Stealthy


### STAT:STR=11|DEX=11|CHA=11|CON=10|INT=10|WIS=10


### STARTPACK:Familiar ~ Hawk


### RACE:Companion ~ Hawk

- **!PRERACE:** 1,%

### STARTPACK:Familiar ~ Lizard


### RACE:Companion ~ Lizard

- **!PRERACE:** 1,%

### STAT:STR=11|DEX=11|CON=10|INT=10|WIS=10|CHA=10


### STARTPACK:Familiar ~ Owl


### RACE:Companion ~ Owl

- **!PRERACE:** 1,%

### STARTPACK:Familiar ~ Rat


### RACE:Companion ~ Rat

- **!PRERACE:** 1,%

### SKILL:Climb

- **RANK:** 2

### STARTPACK:Familiar ~ Raven


### RACE:Companion ~ Raven

- **!PRERACE:** 1,%

### STARTPACK:Familiar ~ Snake


### RACE:Companion ~ Snake (Viper/Tiny)

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Improved Initiative


### STAT:DEX=11|CON=11|STR=10|INT=10|WIS=10|CHA=10


### STARTPACK:Familiar ~ Toad


### RACE:Companion ~ Toad

- **!PRERACE:** 1,%

### SKILL:Hide

- **RANK:** 4

### STAT:CON=11|STR=10|DEX=10|INT=10|WIS=10|CHA=10


### STARTPACK:Familiar ~ Weasel


### RACE:Companion ~ Weasel

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Agile


### STARTPACK:Ape Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Ape]

### RACE:Companion ~ Ape

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Toughness


### STARTPACK:Badger Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Badger]

### RACE:Companion ~ Badger

- **!PRERACE:** 1,%

### STARTPACK:Bear (Black) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bear (Black)]

### RACE:Companion ~ Bear (Black)

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Endurance


### ABILITY:CATEGORY=FEAT|Run


### STAT:STR=11|DEX=11|CON=11|INT=10|WIS=10|CHA=10


### STARTPACK:Bear (Brown) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bear (Brown)]

### RACE:Companion ~ Bear (Brown)

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Track


### STARTPACK:Bear (Polar) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bear (Polar)]

### RACE:Companion ~ Bear (Polar)

- **!PRERACE:** 1,%

### STARTPACK:Bison Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Bison]

### RACE:Companion ~ Bison

- **!PRERACE:** 1,%

### STAT:WIS=11|STR=10|DEX=10|CON=10|INT=10|CHA=10


### STARTPACK:Boar Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Boar]

### RACE:Companion ~ Boar

- **!PRERACE:** 1,%

### STAT:STR=11|CON=11|WIS=11|DEX=10|INT=10|CHA=10


### STARTPACK:Camel Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Camel]

### RACE:Companion ~ Camel

- **!PRERACE:** 1,%

### STARTPACK:Cheetah Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Cheetah]

### RACE:Companion ~ Cheetah

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Weapon Finesse


### STARTPACK:Crocodile Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Crocodile]

### RACE:Companion ~ Crocodile

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Skill Focus(Hide)


### STAT:STR=11|CON=11|DEX=10|INT=10|WIS=10|CHA=10


### STARTPACK:Crocodile (Giant) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Crocodile (Giant)]

### RACE:Companion ~ Crocodile (Giant)

- **!PRERACE:** 1,%

### STARTPACK:Dog Companion

- **EQUIPBUY:** 0

### RACE:Companion ~ Dog

- **!PRERACE:** 1,%

### STARTPACK:Dog (Riding) Companion

- **EQUIPBUY:** 0

### RACE:Companion ~ Dog (Riding)

- **!PRERACE:** 1,%

### SKILL:Swim

- **RANK:** 1

### STARTPACK:Eagle Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Eagle]

### RACE:Companion ~ Eagle

- **!PRERACE:** 1,%

### STARTPACK:Elephant Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Elephant]

### RACE:Companion ~ Elephant

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Iron Will


### ABILITY:CATEGORY=FEAT|Skill Focus(Listen)


### STAT:CON=11|WIS=11|CHA=11|STR=10|DEX=10|INT=10


### STARTPACK:Hawk Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Hawk]

### STARTPACK:Horse (Heavy) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Horse (Heavy)]

### RACE:Companion ~ Horse (Heavy)

- **!PRERACE:** 1,%

### STARTPACK:Horse (Light) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Horse (Light)]

### RACE:Companion ~ Horse (Light)

- **!PRERACE:** 1,%

### STARTPACK:Leopard Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Leopard]

### RACE:Companion ~ Leopard

- **!PRERACE:** 1,%

### STARTPACK:Lion Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lion]

### RACE:Companion ~ Lion

- **!PRERACE:** 1,%

### STARTPACK:Lizard (Monitor) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Lizard (Monitor)]

### RACE:Companion ~ Lizard (Monitor)

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Great Fortitude


### STARTPACK:Octopus (Giant) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Octopus (Giant)]

### RACE:Companion ~ Octopus (Giant)

- **!PRERACE:** 1,%

### STAT:DEX=11|CON=11|CHA=11|STR=10|INT=10|WIS=10


### STARTPACK:Owl Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Owl]

### STARTPACK:Pony Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Pony]

### RACE:Companion ~ Pony

- **!PRERACE:** 1,%

### STAT:STR=11|DEX=11|WIS=11|CON=10|INT=10|CHA=10


### STARTPACK:Porpoise Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Porpoise]

### RACE:Companion ~ Porpoise

- **!PRERACE:** 1,%

### STARTPACK:Rhinoceros Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Rhinoceros]

### RACE:Companion ~ Rhinoceros

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Improved Natural Attack(Gore)


### STAT:CON=11|WIS=11|STR=10|DEX=10|INT=10|CHA=10


### STARTPACK:Shark (Huge) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shark (Huge)]

### RACE:Companion ~ Shark (Huge)

- **!PRERACE:** 1,%

### STARTPACK:Shark (Large) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shark (Large)]

### RACE:Companion ~ Shark (Large)

- **!PRERACE:** 1,%

### STARTPACK:Shark (Medium) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shark (Medium)]

### RACE:Companion ~ Shark (Medium)

- **!PRERACE:** 1,%

### STARTPACK:Snake (Constrictor) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Constrictor)]

### RACE:Companion ~ Snake (Constrictor)

- **!PRERACE:** 1,%

### STARTPACK:Snake (Constrictor/Giant) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Constrictor/Giant)]

### RACE:Companion ~ Snake (Constrictor/Giant)

- **!PRERACE:** 1,%

### STARTPACK:Snake (Viper/Small) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Small)]

### RACE:Companion ~ Snake (Viper/Small)

- **!PRERACE:** 1,%

### STARTPACK:Snake (Viper/Medium) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Medium)]

### RACE:Companion ~ Snake (Viper/Medium)

- **!PRERACE:** 1,%

### STARTPACK:Snake (Viper/Large) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Large)]

### RACE:Companion ~ Snake (Viper/Large)

- **!PRERACE:** 1,%

### STARTPACK:Snake (Viper/Huge) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Snake (Viper/Huge)]

### RACE:Companion ~ Snake (Viper/Huge)

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Weapon Focus(Bite)


### STARTPACK:Squid Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Squid]

### RACE:Companion ~ Squid

- **!PRERACE:** 1,%

### STARTPACK:Squid (Giant) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Squid (Giant)]

### RACE:Companion ~ Squid (Giant)

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Diehard


### STARTPACK:Tiger Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Tiger]

### RACE:Companion ~ Tiger

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Improved Natural Attack(Claw)


### ABILITY:CATEGORY=FEAT|Improved Natural Attack(Bite)


### STARTPACK:Whale (Orca) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Whale (Orca)]

### RACE:Companion ~ Whale (Orca)

- **!PRERACE:** 1,%

### STARTPACK:Wolf Companion

- **EQUIPBUY:** 0

### RACE:Companion ~ Wolf

- **!PRERACE:** 1,%

### STARTPACK:Wolverine Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Wolverine]

### RACE:Companion ~ Wolverine

- **!PRERACE:** 1,%

### STARTPACK:Awakened Animal

- **APPLY:** INSTANT

### STAT:INT=roll("3d6")+var("STAT.3.BASE")-var("STAT.3")|CHA=roll("1d3")+var("STAT.5.BASE")


### STARTPACK:Awakened Tree

- **APPLY:** INSTANT

### NAME:Awakened Tree


### STAT:INT=roll("3d6")|CHA=roll("3d6")|WIS=roll("3d6")


### STARTPACK:Vermin Intelligence

- **APPLY:** INSTANT

### STAT:INT=3


### STARTPACK:Demon (Quasit) Familiar

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Demon (Quasit)]

### RACE:Companion ~ Demon (Quasit)

- **!PRERACE:** 1,%

### ALIGN:CE


### SKILL:Bluff

- **RANK:** 6

### SKILL:Search

- **RANK:** 6

### SKILL:Spellcraft

- **RANK:** 6

### SKILL:TYPE=Knowledge

- **RANK:** 6

### STARTPACK:Devil (Imp) Familiar

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Devil (Imp)]

### RACE:Companion ~ Devil (Imp)

- **!PRERACE:** 1,%

### ALIGN:LE


### SKILL:Diplomacy

- **RANK:** 6

### ABILITY:CATEGORY=FEAT|Dodge


### STARTPACK:Shocker Lizard Familiar

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Shocker Lizard]

### RACE:Companion ~ Shocker Lizard

- **!PRERACE:** 1,%

### SKILL:Jump

- **RANK:** 1

### STARTPACK:Stirge Familiar

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Stirge]

### RACE:Companion ~ Stirge

- **!PRERACE:** 1,%

### STARTPACK:Formian (Worker) Familiar

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Formian (Worker)]

### RACE:Companion ~ Formian (Worker)

- **!PRERACE:** 1,%

### ALIGN:LN


### SKILL:TYPE=Craft

- **RANK:** 4

### ABILITY:CATEGORY=FEAT|Skill Focus


### STAT:STR=11|CON=11|CHA=11|DEX=10|INT=10|WIS=10


### STARTPACK:Pseudodragon Familiar

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Pseudodragon]

### RACE:Companion ~ Pseudodragon

- **!PRERACE:** 1,%

### ALIGN:NG


### SKILL:Sense Motive

- **RANK:** 5

### STARTPACK:Dinosaur (Deinonychus) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Deinonychus)]

### RACE:Companion ~ Dinosaur (Deinonychus)

- **!PRERACE:** 1,%

### SKILL:Survival

- **RANK:** 1

### STARTPACK:Dinosaur (Elasmosaurus) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Elasmosaurus)]

### RACE:Companion ~ Dinosaur (Elasmosaurus)

- **!PRERACE:** 1,%

### STAT:WIS=11|CHA=11|STR=10|DEX=10|CON=10|INT=10


### STARTPACK:Dinosaur (Megaraptor) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Megaraptor)]

### RACE:Companion ~ Dinosaur (Megaraptor)

- **!PRERACE:** 1,%

### STAT:STR=11|DEX=11|CON=11|WIS=11|INT=10|CHA=10


### STARTPACK:Dinosaur (Triceratops) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Triceratops)]

### RACE:Companion ~ Dinosaur (Triceratops)

- **!PRERACE:** 1,%

### STARTPACK:Dinosaur (Tyrannosaurus) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dinosaur (Tyrannosaurus)]

### RACE:Companion ~ Dinosaur (Tyrannosaurus)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Ape) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Ape)]

### RACE:Companion ~ Dire Animal (Dire Ape)

- **!PRERACE:** 1,%

### STAT:DEX=11|CHA=11|STR=10|CON=10|INT=10|WIS=10


### STARTPACK:Dire Animal (Dire Badger) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Badger)]

### RACE:Companion ~ Dire Animal (Dire Badger)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Bat) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Bat)]

### RACE:Companion ~ Dire Animal (Dire Bat)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Bear) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Bear)]

### RACE:Companion ~ Dire Animal (Dire Bear)

- **!PRERACE:** 1,%

### ABILITY:CATEGORY=FEAT|Weapon Focus(Claw)


### STARTPACK:Dire Animal (Dire Boar) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Boar)]

### RACE:Companion ~ Dire Animal (Dire Boar)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Lion) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Lion)]

### RACE:Companion ~ Dire Animal (Dire Lion)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Rat) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Dire Animal (Dire Rat)]

### RACE:Companion ~ Dire Animal (Dire Rat)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Shark) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Dire Animal (Dire Shark)]

### RACE:Companion ~ Dire Animal (Dire Shark)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Tiger) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Dire Animal (Dire Tiger)]

### RACE:Companion ~ Dire Animal (Dire Tiger)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Weasel) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Dire Animal (Dire Weasel)]

### RACE:Companion ~ Dire Animal (Dire Weasel)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Wolf) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Dire Animal (Dire Wolf)]

### RACE:Companion ~ Dire Animal (Dire Wolf)

- **!PRERACE:** 1,%

### STARTPACK:Dire Animal (Dire Wolverine) Companion

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Dire Animal (Dire Wolverine)]

### RACE:Companion ~ Dire Animal (Dire Wolverine)

- **!PRERACE:** 1,%

### STARTPACK:Companion ~ Dog (Riding) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Dog (Riding)]

### NAME:Riding Dog


### STARTPACK:Companion ~ Horse (Warhorse Heavy) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Horse (Warhorse Heavy)]

### RACE:Companion ~ Horse (Warhorse Heavy)

- **!PRERACE:** 1,%

### NAME:Heavy Warhorse


### STAT:DEX=11|CON=11|WIS=11|STR=10|INT=10|CHA=10


### STARTPACK:Companion ~ Pony (War) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Pony (War)]

### RACE:Companion ~ Pony (War)

- **!PRERACE:** 1,%

### NAME:War Pony


### STARTPACK:Companion ~ Shark (Large) Default

- **EQUIPBUY:** 0
- **PREMULT:** 1,[!PRERACE:1,%],[PRERACE:1,Companion ~ Shark (Large)]

### NAME:Large Shark


## Profs Weapons

### Lance (Light)


### Aspergillum (Heavy)


### Battle Gauntlet


### Blade Boot


### Blowgun


### Chakram


### Claw Bracer


### Cutlass


### Katana


### Khopesh


### Lasso


### Maul


### Pincer Staff


### Saber


### Scourge


### Wakizashi


### Claw


### Gore


### Bite


### Incorporeal Touch


## Templates

### Use Fractional BAB

- **DEFINE:** UseFractionalBAB|0
- **BONUS:** VAR|UseFractionalBAB|1|TYPE=NoStack
- **BONUS:** VAR|UseAlternateBABProgression|1

### REACH_0

- **REACH:** 0

### REACH_5

- **REACH:** 5

### REACH_10

- **REACH:** 10

### REACH_15

- **REACH:** 15

### REACH_20

- **REACH:** 20

### REACH_30

- **REACH:** 30

### FACE_0

- **FACE:** 0

### FACE_1

- **FACE:** 1

### FACE_2

- **FACE:** 2.5

### FACE_5

- **FACE:** 5

### FACE_10

- **FACE:** 10

### FACE_15

- **FACE:** 15

### FACE_20

- **FACE:** 20

### FACE_30

- **FACE:** 30

### SIZE_F

- **SIZE:** F

### SIZE_D

- **SIZE:** D

### SIZE_T

- **SIZE:** T

### SIZE_S

- **SIZE:** S

### SIZE_M

- **SIZE:** M

### SIZE_L

- **SIZE:** L

### SIZE_H

- **SIZE:** H

### SIZE_G

- **SIZE:** G

### SIZE_C

- **SIZE:** C

### SIZE_C+

- **SIZE:** C+

### LEVEL_ADJUSTMENT_1

- **LEVELADJUSTMENT:** 1

### LEVEL_ADJUSTMENT_2

- **LEVELADJUSTMENT:** 2

### LEVEL_ADJUSTMENT_3

- **LEVELADJUSTMENT:** 3

### LEVEL_ADJUSTMENT_4

- **LEVELADJUSTMENT:** 4

### LEVEL_ADJUSTMENT_5

- **LEVELADJUSTMENT:** 5

### LEVEL_ADJUSTMENT_6

- **LEVELADJUSTMENT:** 6

### LEVEL_ADJUSTMENT_7

- **LEVELADJUSTMENT:** 7

### LEVEL_ADJUSTMENT_8

- **LEVELADJUSTMENT:** 8

### LEVEL_ADJUSTMENT_9

- **LEVELADJUSTMENT:** 9

### Level Adjustment +1

- **LEVELADJUSTMENT:** 1

### Level Adjustment +2

- **LEVELADJUSTMENT:** 2

### Level Adjustment +3

- **LEVELADJUSTMENT:** 3

### Level Adjustment +4

- **LEVELADJUSTMENT:** 4

### Level Adjustment +5

- **LEVELADJUSTMENT:** 5

### Level Adjustment +6

- **LEVELADJUSTMENT:** 6

### Level Adjustment +7

- **LEVELADJUSTMENT:** 7

### Level Adjustment +8

- **LEVELADJUSTMENT:** 8

### Level Adjustment +9

- **LEVELADJUSTMENT:** 9

### Level Adjustment -1

- **LEVELADJUSTMENT:** -1

### Level Adjustment -2

- **LEVELADJUSTMENT:** -2

### Level Adjustment -3

- **LEVELADJUSTMENT:** -3

### Level Adjustment -4

- **LEVELADJUSTMENT:** -4

### Level Adjustment -5

- **LEVELADJUSTMENT:** -5

### Level Adjustment -6

- **LEVELADJUSTMENT:** -6

### Level Adjustment -7

- **LEVELADJUSTMENT:** -7

### Level Adjustment -8

- **LEVELADJUSTMENT:** -8

### Level Adjustment -9

- **LEVELADJUSTMENT:** -9

### Assign Race Type ~ Aberration

- **RACETYPE:** Aberration

### Assign Race Type ~ Animal

- **RACETYPE:** Animal

### Assign Race Type ~ Dragon

- **RACETYPE:** Dragon

### Assign Race Type ~ Elemental

- **RACETYPE:** Elemental

### Assign Race Type ~ Fey

- **RACETYPE:** Fey

### Assign Race Type ~ Giant

- **RACETYPE:** Giant

### Assign Race Type ~ Humanoid

- **RACETYPE:** Humanoid

### Assign Race Type ~ Magical Beast

- **RACETYPE:** Magical Beast

### Assign Race Type ~ Monstrous Humanoid

- **RACETYPE:** Monstrous Humanoid

### Assign Race Type ~ Outsider

- **RACETYPE:** Outsider

### Assign Race Type ~ Plant

- **RACETYPE:** Plant

### Assign Race Type ~ Vermin

- **RACETYPE:** Vermin

### Assign Race Subtype ~ Air

- **RACESUBTYPE:** Air

### Assign Race Subtype ~ Angel

- **RACESUBTYPE:** Angel

### Assign Race Subtype ~ Aquatic

- **RACESUBTYPE:** Aquatic

### Assign Race Subtype ~ Archon

- **RACESUBTYPE:** Archon

### Assign Race Subtype ~ Augmented

- **RACESUBTYPE:** Augmented

### Assign Race Subtype ~ Chaotic

- **RACESUBTYPE:** Chaotic

### Assign Race Subtype ~ Cold

- **RACESUBTYPE:** Cold

### Assign Race Subtype ~ Evil

- **RACESUBTYPE:** Evil

### Assign Race Subtype ~ Fire

- **RACESUBTYPE:** Fire

### Assign Race Subtype ~ Good

- **RACESUBTYPE:** Good

### Assign Race Subtype ~ Earth

- **RACESUBTYPE:** Earth

### Assign Race Subtype ~ Lawful

- **RACESUBTYPE:** Lawful

### Assign Race Subtype ~ Reptilian

- **RACESUBTYPE:** Reptilian

### Assign Race Subtype ~ Shapechanger

- **RACESUBTYPE:** Shapechanger

### Assign Race Subtype ~ Swarm

- **RACESUBTYPE:** Swarm

### Assign Race Subtype ~ Water

- **RACESUBTYPE:** Water

### Assign Race Subtype ~ Extraplanar

- **RACESUBTYPE:** Extraplanar

### Assign Race Subtype ~ Native

- **RACESUBTYPE:** Native

### Assign Race Type ~ Deathless

- **RACETYPE:** Deathless

### War Trained

- **BONUS:** VAR|AnimalWarTrained|1
- **DEFINE:** AnimalWarTrained|0

### Aberration


### Animal

- **PREALIGN:** TN
- **PREVARLTEQ:** INTSCORE,2

### Dragon


### Elemental


### Fey


### Giant


### Humanoid


### Magical Beast


### Monstrous Humanoid


### Outsider


### Plant


### Vermin


### Undead


### Air

- **RACESUBTYPE:** Air

### Angel

- **RACESUBTYPE:** Angel

### Aquatic

- **RACESUBTYPE:** Aquatic

### Archon

- **RACESUBTYPE:** Archon

### Augmented


### Chaotic

- **RACESUBTYPE:** Chaotic

### Cold

- **RACESUBTYPE:** Cold

### Evil

- **RACESUBTYPE:** Evil

### Fire

- **RACESUBTYPE:** Fire

### Good

- **RACESUBTYPE:** Good

### Earth

- **RACESUBTYPE:** Earth

### Lawful

- **RACESUBTYPE:** Lawful

### Reptilian

- **RACESUBTYPE:** Reptilian

### Shapechanger

- **RACESUBTYPE:** Shapechanger

### Swarm

- **RACESUBTYPE:** Swarm

### Water

- **RACESUBTYPE:** Water

### Extraplanar

- **RACESUBTYPE:** Extraplanar

### Native

- **PRERACE:** 1,RACETYPE=Outsider
- **RACESUBTYPE:** Native

### Mindless

- **ABILITY:** Special Ability|AUTOMATIC|Mindless

### Psionic

- **ABILITY:** Special Ability|AUTOMATIC|Psionic
- **SUBRACE:** Psionic
- **RACESUBTYPE:** Psionic

### Psionic Power Points Progression

- **DEFINE:** PsionML|0
- **BONUS:** VAR|BasePowerPoints|2
- **BONUS:** VAR|BasePowerPoints|4
- **BONUS:** VAR|BasePowerPoints|5
- **BONUS:** VAR|BasePowerPoints|6
- **BONUS:** VAR|BasePowerPoints|8
- **BONUS:** VAR|BasePowerPoints|10
- **BONUS:** VAR|BasePowerPoints|11
- **BONUS:** VAR|BasePowerPoints|12
- **BONUS:** VAR|BasePowerPoints|14
- **BONUS:** VAR|BasePowerPoints|16
- **BONUS:** VAR|BasePowerPoints|18
- **BONUS:** VAR|BasePowerPoints|20
- **BONUS:** VAR|BasePowerPoints|21
- **BONUS:** VAR|BasePowerPoints|23
- **BONUS:** VAR|BasePowerPoints|25
- **BONUS:** VAR|BasePowerPoints|26
- **BONUS:** VAR|BasePowerPoints|29
- **BONUS:** VAR|BasePowerPoints|30
- **BONUS:** VAR|BasePowerPoints|31
- **BONUS:** VAR|BasePowerPoints|32
- **BONUS:** VAR|BonusPowerPoints|(INT*PsionML)/2|TYPE=PsionBonusPP

### Base Dragon HD (3)

- **TEMPLATE:** Dragon Size HD (3)
- **HD:** 3-4:TEMPLATE:Wyrmling
- **HD:** 5-6:TEMPLATE:Very Young
- **HD:** 7-8:TEMPLATE:Young
- **HD:** 9-10:TEMPLATE:Juvenile
- **HD:** 11-12:TEMPLATE:Young Adult
- **HD:** 13-14:TEMPLATE:Adult
- **HD:** 15-16:TEMPLATE:Mature Adult
- **HD:** 17-18:TEMPLATE:Old
- **HD:** 19-20:TEMPLATE:Very Old
- **HD:** 21-22:TEMPLATE:Ancient
- **HD:** 23-24:TEMPLATE:Wyrm
- **HD:** 25+:TEMPLATE:Great Wyrm

### Base Dragon HD (4)

- **TEMPLATE:** Dragon Size HD (4)
- **HD:** 4-5:TEMPLATE:Wyrmling
- **HD:** 6-7:TEMPLATE:Very Young
- **HD:** 8-9:TEMPLATE:Young
- **HD:** 10-11:TEMPLATE:Juvenile
- **HD:** 12-13:TEMPLATE:Young Adult
- **HD:** 14-15:TEMPLATE:Adult
- **HD:** 16-17:TEMPLATE:Mature Adult
- **HD:** 18-19:TEMPLATE:Old
- **HD:** 20-21:TEMPLATE:Very Old
- **HD:** 22-23:TEMPLATE:Ancient
- **HD:** 24-25:TEMPLATE:Wyrm
- **HD:** 26+:TEMPLATE:Great Wyrm

### Base Dragon HD (5)

- **TEMPLATE:** Dragon Size HD (5)
- **HD:** 5-6:TEMPLATE:Wyrmling
- **HD:** 7-8:TEMPLATE:Very Young
- **HD:** 9-10:TEMPLATE:Young
- **HD:** 11-12:TEMPLATE:Juvenile
- **HD:** 13-14:TEMPLATE:Young Adult
- **HD:** 15-16:TEMPLATE:Adult
- **HD:** 17-18:TEMPLATE:Mature Adult
- **HD:** 19-20:TEMPLATE:Old
- **HD:** 21-22:TEMPLATE:Very Old
- **HD:** 23-24:TEMPLATE:Ancient
- **HD:** 25-26:TEMPLATE:Wyrm
- **HD:** 27+:TEMPLATE:Great Wyrm

### Base Dragon HD (6)

- **TEMPLATE:** Dragon Size HD (6)
- **HD:** 6-7:TEMPLATE:Wyrmling
- **HD:** 8-9:TEMPLATE:Very Young
- **HD:** 10-11:TEMPLATE:Young
- **HD:** 12-13:TEMPLATE:Juvenile
- **HD:** 14-15:TEMPLATE:Young Adult
- **HD:** 16-17:TEMPLATE:Adult
- **HD:** 18-19:TEMPLATE:Mature Adult
- **HD:** 20-21:TEMPLATE:Old
- **HD:** 22-23:TEMPLATE:Very Old
- **HD:** 24-25:TEMPLATE:Ancient
- **HD:** 26-27:TEMPLATE:Wyrm
- **HD:** 28+:TEMPLATE:Great Wyrm

### Base Dragon HD (7)

- **TEMPLATE:** Dragon Size HD (7)
- **HD:** 7-8:TEMPLATE:Wyrmling
- **HD:** 9-10:TEMPLATE:Very Young
- **HD:** 11-12:TEMPLATE:Young
- **HD:** 13-14:TEMPLATE:Juvenile
- **HD:** 15-16:TEMPLATE:Young Adult
- **HD:** 17-18:TEMPLATE:Adult
- **HD:** 19-20:TEMPLATE:Mature Adult
- **HD:** 21-22:TEMPLATE:Old
- **HD:** 23-24:TEMPLATE:Very Old
- **HD:** 25-26:TEMPLATE:Ancient
- **HD:** 27-28:TEMPLATE:Wyrm
- **HD:** 29+:TEMPLATE:Great Wyrm

### Base Dragon HD (8)

- **TEMPLATE:** Dragon Size HD (8)
- **HD:** 8-9:TEMPLATE:Wyrmling
- **HD:** 10-11:TEMPLATE:Very Young
- **HD:** 12-13:TEMPLATE:Young
- **HD:** 14-15:TEMPLATE:Juvenile
- **HD:** 16-17:TEMPLATE:Young Adult
- **HD:** 18-19:TEMPLATE:Adult
- **HD:** 20-21:TEMPLATE:Mature Adult
- **HD:** 22-23:TEMPLATE:Old
- **HD:** 24-25:TEMPLATE:Very Old
- **HD:** 26-27:TEMPLATE:Ancient
- **HD:** 28-29:TEMPLATE:Wyrm
- **HD:** 30+:TEMPLATE:Great Wyrm

### Dragon Size HD (3)

- **HD:** 3-4:TEMPLATE:Dragon (Tiny)
- **HD:** 5-6:TEMPLATE:Dragon (Small)
- **HD:** 7-10:TEMPLATE:Dragon (Medium)
- **HD:** 11-16:TEMPLATE:Dragon (Large)
- **HD:** 17-24:TEMPLATE:Dragon (Huge)
- **HD:** 25+:TEMPLATE:Dragon (Gargantuan)

### Dragon Size HD (4)

- **HD:** 4-5:TEMPLATE:Dragon (Tiny)
- **HD:** 6-7:TEMPLATE:Dragon (Small)
- **HD:** 8-11:TEMPLATE:Dragon (Medium)
- **HD:** 12-17:TEMPLATE:Dragon (Large)
- **HD:** 18-25:TEMPLATE:Dragon (Huge)
- **HD:** 26+:TEMPLATE:Dragon (Gargantuan)

### Dragon Size HD (5)

- **HD:** 5-6:TEMPLATE:Dragon (Small)
- **HD:** 7-8:TEMPLATE:Dragon (Medium)
- **HD:** 9-12:TEMPLATE:Dragon (Large)
- **HD:** 13-18:TEMPLATE:Dragon (Huge)
- **HD:** 19-26:TEMPLATE:Dragon (Gargantuan)
- **HD:** 27+:TEMPLATE:Dragon (Colossal)

### Dragon Size HD (6)

- **HD:** 6-7:TEMPLATE:Dragon (Small)
- **HD:** 8-9:TEMPLATE:Dragon (Medium)
- **HD:** 10-13:TEMPLATE:Dragon (Large)
- **HD:** 14-19:TEMPLATE:Dragon (Huge)
- **HD:** 20-27:TEMPLATE:Dragon (Gargantuan)
- **HD:** 28+:TEMPLATE:Dragon (Colossal)

### Dragon Size HD (7)

- **HD:** 7-8:TEMPLATE:Dragon (Small)
- **HD:** 9-10:TEMPLATE:Dragon (Medium)
- **HD:** 11-14:TEMPLATE:Dragon (Large)
- **HD:** 15-20:TEMPLATE:Dragon (Huge)
- **HD:** 21-28:TEMPLATE:Dragon (Gargantuan)
- **HD:** 29+:TEMPLATE:Dragon (Colossal)

### Dragon Size HD (8)

- **HD:** 8-9:TEMPLATE:Dragon (Small)
- **HD:** 10-11:TEMPLATE:Dragon (Medium)
- **HD:** 12-15:TEMPLATE:Dragon (Large)
- **HD:** 16-21:TEMPLATE:Dragon (Huge)
- **HD:** 22-29:TEMPLATE:Dragon (Gargantuan)
- **HD:** 30+:TEMPLATE:Dragon (Colossal)

### Dragon Attacks HD (3)

- **HD:** 3-4:TEMPLATE:Dragon Attacks (Tiny)
- **HD:** 5-6:TEMPLATE:Dragon Attacks (Small)
- **HD:** 7-10:TEMPLATE:Dragon Attacks (Medium)
- **HD:** 11-16:TEMPLATE:Dragon Attacks (Large)
- **HD:** 17-24:TEMPLATE:Dragon Attacks (Huge)
- **HD:** 25+:TEMPLATE:Dragon Attacks (Gargantuan)

### Dragon Attacks HD (4)

- **HD:** 4-5:TEMPLATE:Dragon Attacks (Tiny)
- **HD:** 6-7:TEMPLATE:Dragon Attacks (Small)
- **HD:** 8-11:TEMPLATE:Dragon Attacks (Medium)
- **HD:** 12-17:TEMPLATE:Dragon Attacks (Large)
- **HD:** 18-25:TEMPLATE:Dragon Attacks (Huge)
- **HD:** 26+:TEMPLATE:Dragon Attacks (Gargantuan)

### Dragon Attacks HD (5)

- **HD:** 5-6:TEMPLATE:Dragon Attacks (Small)
- **HD:** 7-8:TEMPLATE:Dragon Attacks (Medium)
- **HD:** 9-12:TEMPLATE:Dragon Attacks (Large)
- **HD:** 13-18:TEMPLATE:Dragon Attacks (Huge)
- **HD:** 19-26:TEMPLATE:Dragon Attacks (Gargantuan)
- **HD:** 27+:TEMPLATE:Dragon Attacks (Colossal)

### Dragon Attacks HD (6)

- **HD:** 6-7:TEMPLATE:Dragon Attacks (Small)
- **HD:** 8-9:TEMPLATE:Dragon Attacks (Medium)
- **HD:** 10-13:TEMPLATE:Dragon Attacks (Large)
- **HD:** 14-19:TEMPLATE:Dragon Attacks (Huge)
- **HD:** 20-27:TEMPLATE:Dragon Attacks (Gargantuan)
- **HD:** 28+:TEMPLATE:Dragon Attacks (Colossal)

### Dragon Attacks HD (7)

- **HD:** 7-8:TEMPLATE:Dragon Attacks (Small)
- **HD:** 9-10:TEMPLATE:Dragon Attacks (Medium)
- **HD:** 11-14:TEMPLATE:Dragon Attacks (Large)
- **HD:** 15-20:TEMPLATE:Dragon Attacks (Huge)
- **HD:** 21-28:TEMPLATE:Dragon Attacks (Gargantuan)
- **HD:** 29+:TEMPLATE:Dragon Attacks (Colossal)

### Dragon Attacks HD (8)

- **HD:** 8-9:TEMPLATE:Dragon Attacks (Small)
- **HD:** 10-11:TEMPLATE:Dragon Attacks (Medium)
- **HD:** 12-15:TEMPLATE:Dragon Attacks (Large)
- **HD:** 16-21:TEMPLATE:Dragon Attacks (Huge)
- **HD:** 22-29:TEMPLATE:Dragon Attacks (Gargantuan)
- **HD:** 30+:TEMPLATE:Dragon Attacks (Colossal)

### Dragon (Tiny)

- **FACE:** 2.5
- **REACH:** 0

### Dragon (Small)

- **FACE:** 5
- **REACH:** 5

### Dragon (Medium)

- **FACE:** 5
- **REACH:** 5

### Dragon (Large)

- **FACE:** 10
- **REACH:** 5

### Dragon (Huge)

- **FACE:** 15
- **REACH:** 10

### Dragon (Gargantuan)

- **FACE:** 20
- **REACH:** 15

### Dragon (Colossal)

- **FACE:** 30
- **REACH:** 20

### Dragon Attacks (Tiny)

- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d4
- **NATURALATTACKS:** Claws,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing.Slashing,*2,1d3

### Dragon Attacks (Small)

- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d6
- **NATURALATTACKS:** Claws,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing.Slashing,*2,1d4

### Dragon Attacks (Medium)

- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,1d8
- **NATURALATTACKS:** Claws,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing.Slashing,*2,1d6|Wings,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d4

### Dragon Attacks (Large)

- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d6
- **NATURALATTACKS:** Claws,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing.Slashing,*2,1d8|Wings,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d6|Tail Slap,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,1d8

### Dragon Attacks (Huge)

- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,2d8
- **NATURALATTACKS:** Claws,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing.Slashing,*2,2d6|Wings,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,1d8|Tail Slap,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d6

### Dragon Attacks (Gargantuan)

- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d6
- **NATURALATTACKS:** Claws,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing.Slashing,*2,2d8|Wings,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d6|Tail Slap,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,2d8

### Dragon Attacks (Colossal)

- **NATURALATTACKS:** Bite,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning.Piercing.Slashing,*1,4d8
- **NATURALATTACKS:** Claws,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Piercing.Slashing,*2,4d6|Wings,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*2,2d8|Tail Slap,Weapon.Natural.Weapon Group Natural.Melee.Finesseable.Bludgeoning,*1,4d6

### Assign Race Type ~ Construct

- **RACETYPE:** Construct

### Assign Race Type ~ Ooze

- **RACETYPE:** Ooze

### Assign Race Type ~ Undead

- **RACETYPE:** Undead

### Assign Subtype ~ Air

- **RACESUBTYPE:** Air

### Assign Subtype ~ Angel

- **RACESUBTYPE:** Angel

### Assign Subtype ~ Aquatic

- **RACESUBTYPE:** Aquatic

### Assign Subtype ~ Archon

- **RACESUBTYPE:** Archon

### Assign Subtype ~ Augmented

- **RACESUBTYPE:** Augmented

### Assign Subtype ~ Chaotic

- **RACESUBTYPE:** Chaotic

### Assign Subtype ~ Cold

- **RACESUBTYPE:** Cold

### Assign Subtype ~ Earth

- **RACESUBTYPE:** Earth

### Assign Subtype ~ Evil

- **RACESUBTYPE:** Evil

### Assign Subtype ~ Extraplanar

- **RACESUBTYPE:** Extraplanar

### Assign Subtype ~ Fire

- **RACESUBTYPE:** Fire

### Assign Subtype ~ Goblinoid

- **RACESUBTYPE:** Goblinoid

### Assign Subtype ~ Good

- **RACESUBTYPE:** Good

### Assign Subtype ~ Incorporeal

- **RACESUBTYPE:** Incorporeal

### Assign Subtype ~ Lawful

- **RACESUBTYPE:** Lawful

### Assign Subtype ~ Native

- **PRERACE:** 1,RACETYPE=Outsider
- **RACESUBTYPE:** Native

### Assign Subtype ~ Reptilian

- **RACESUBTYPE:** Reptilian

### Assign Subtype ~ Shapechanger

- **RACESUBTYPE:** Shapechanger

### Assign Subtype ~ Swarm

- **RACESUBTYPE:** Swarm

### Assign Subtype ~ Water

- **RACESUBTYPE:** Water

### Assign Subtype ~ Baatezu

- **RACESUBTYPE:** Baatezu

### Assign Subtype ~ Human

- **RACESUBTYPE:** Human

### Add Hit Die Level 1

- **TEMPLATE:** CHOOSE:Add 1 Levels of Aberration|Add 1 Levels of Animal|Add 1 Levels of Construct|Add 1 Levels of Dragon|Add 1 Levels of Elemental|Add 1 Levels of Fey|Add 1 Levels of Giant|Add 1 Levels of Humanoid|Add 1 Levels of Magical Beast|Add 1 Levels of Monstrous Humanoid|Add 1 Levels of Ooze|Add 1 Levels of Outsider|Add 1 Levels of Plant|Add 1 Levels of Undead|Add 1 Levels of Vermin

### Add Hit Die Level 2

- **TEMPLATE:** CHOOSE:Add 2 Levels of Aberration|Add 2 Levels of Animal|Add 2 Levels of Construct|Add 2 Levels of Dragon|Add 2 Levels of Elemental|Add 2 Levels of Fey|Add 2 Levels of Giant|Add 2 Levels of Humanoid|Add 2 Levels of Magical Beast|Add 2 Levels of Monstrous Humanoid|Add 2 Levels of Ooze|Add 2 Levels of Outsider|Add 2 Levels of Plant|Add 2 Levels of Undead|Add 2 Levels of Vermin

### Add Hit Die Level 3

- **TEMPLATE:** CHOOSE:Add 3 Levels of Aberration|Add 3 Levels of Animal|Add 3 Levels of Construct|Add 3 Levels of Dragon|Add 3 Levels of Elemental|Add 3 Levels of Fey|Add 3 Levels of Giant|Add 3 Levels of Humanoid|Add 3 Levels of Magical Beast|Add 3 Levels of Monstrous Humanoid|Add 3 Levels of Ooze|Add 3 Levels of Outsider|Add 3 Levels of Plant|Add 3 Levels of Undead|Add 3 Levels of Vermin

### Add Hit Die Level 4

- **TEMPLATE:** CHOOSE:Add 4 Levels of Aberration|Add 4 Levels of Animal|Add 4 Levels of Construct|Add 4 Levels of Dragon|Add 4 Levels of Elemental|Add 4 Levels of Fey|Add 4 Levels of Giant|Add 4 Levels of Humanoid|Add 4 Levels of Magical Beast|Add 4 Levels of Monstrous Humanoid|Add 4 Levels of Ooze|Add 4 Levels of Outsider|Add 4 Levels of Plant|Add 4 Levels of Undead|Add 4 Levels of Vermin

### Add Hit Die Level 5

- **TEMPLATE:** CHOOSE:Add 5 Levels of Aberration|Add 5 Levels of Animal|Add 5 Levels of Construct|Add 5 Levels of Dragon|Add 5 Levels of Elemental|Add 5 Levels of Fey|Add 5 Levels of Giant|Add 5 Levels of Humanoid|Add 5 Levels of Magical Beast|Add 5 Levels of Monstrous Humanoid|Add 5 Levels of Ooze|Add 5 Levels of Outsider|Add 5 Levels of Plant|Add 5 Levels of Undead|Add 5 Levels of Vermin

### Add Hit Die Level 6

- **TEMPLATE:** CHOOSE:Add 6 Levels of Aberration|Add 6 Levels of Animal|Add 6 Levels of Construct|Add 6 Levels of Dragon|Add 6 Levels of Elemental|Add 6 Levels of Fey|Add 6 Levels of Giant|Add 6 Levels of Humanoid|Add 6 Levels of Magical Beast|Add 6 Levels of Monstrous Humanoid|Add 6 Levels of Ooze|Add 6 Levels of Outsider|Add 6 Levels of Plant|Add 6 Levels of Undead|Add 6 Levels of Vermin

### Add 1 Levels of Aberration

- **PRERACE:** 1,RACETYPE=Aberration
- **ADDLEVEL:** Aberration|1

### Add 1 Levels of Animal

- **PRERACE:** 1,RACETYPE=Animal
- **ADDLEVEL:** Animal|1

### Add 1 Levels of Construct

- **PRERACE:** 1,RACETYPE=Construct
- **ADDLEVEL:** Construct|1

### Add 1 Levels of Dragon

- **PRERACE:** 1,RACETYPE=Dragon
- **ADDLEVEL:** Dragon|1

### Add 1 Levels of Elemental

- **PRERACE:** 1,RACETYPE=Elemental
- **ADDLEVEL:** Elemental|1

### Add 1 Levels of Fey

- **PRERACE:** 1,RACETYPE=Fey
- **ADDLEVEL:** Fey|1

### Add 1 Levels of Giant

- **PRERACE:** 1,RACETYPE=Giant
- **ADDLEVEL:** Giant|1

### Add 1 Levels of Humanoid

- **PRERACE:** 1,RACETYPE=Humanoid
- **ADDLEVEL:** Humanoid|1

### Add 1 Levels of Magical Beast

- **PRERACE:** 1,RACETYPE=Magical Beast
- **ADDLEVEL:** Magical Beast|1

### Add 1 Levels of Monstrous Humanoid

- **PRERACE:** 1,RACETYPE=Monstrous Humanoid
- **ADDLEVEL:** Monstrous Humanoid|1

### Add 1 Levels of Ooze

- **PRERACE:** 1,RACETYPE=Ooze
- **ADDLEVEL:** Ooze|1

### Add 1 Levels of Outsider

- **PRERACE:** 1,RACETYPE=Outsider
- **ADDLEVEL:** Outsider|1

### Add 1 Levels of Plant

- **PRERACE:** 1,RACETYPE=Plant
- **ADDLEVEL:** Plant|1

### Add 1 Levels of Undead

- **PRERACE:** 1,RACETYPE=Undead
- **ADDLEVEL:** Undead|1

### Add 1 Levels of Vermin

- **PRERACE:** 1,RACETYPE=Vermin
- **ADDLEVEL:** Vermin|1

### Add 2 Levels of Aberration

- **PRERACE:** 1,RACETYPE=Aberration
- **ADDLEVEL:** Aberration|2

### Add 2 Levels of Animal

- **PRERACE:** 1,RACETYPE=Animal
- **ADDLEVEL:** Animal|2

### Add 2 Levels of Construct

- **PRERACE:** 1,RACETYPE=Construct
- **ADDLEVEL:** Construct|2

### Add 2 Levels of Dragon

- **PRERACE:** 1,RACETYPE=Dragon
- **ADDLEVEL:** Dragon|2

### Add 2 Levels of Elemental

- **PRERACE:** 1,RACETYPE=Elemental
- **ADDLEVEL:** Elemental|2

### Add 2 Levels of Fey

- **PRERACE:** 1,RACETYPE=Fey
- **ADDLEVEL:** Fey|2

### Add 2 Levels of Giant

- **PRERACE:** 1,RACETYPE=Giant
- **ADDLEVEL:** Giant|2

### Add 2 Levels of Humanoid

- **PRERACE:** 1,RACETYPE=Humanoid
- **ADDLEVEL:** Humanoid|2

### Add 2 Levels of Magical Beast

- **PRERACE:** 1,RACETYPE=Magical Beast
- **ADDLEVEL:** Magical Beast|2

### Add 2 Levels of Monstrous Humanoid

- **PRERACE:** 1,RACETYPE=Monstrous Humanoid
- **ADDLEVEL:** Monstrous Humanoid|2

### Add 2 Levels of Ooze

- **PRERACE:** 1,RACETYPE=Ooze
- **ADDLEVEL:** Ooze|2

### Add 2 Levels of Outsider

- **PRERACE:** 1,RACETYPE=Outsider
- **ADDLEVEL:** Outsider|2

### Add 2 Levels of Plant

- **PRERACE:** 1,RACETYPE=Plant
- **ADDLEVEL:** Plant|2

### Add 2 Levels of Undead

- **PRERACE:** 1,RACETYPE=Undead
- **ADDLEVEL:** Undead|2

### Add 2 Levels of Vermin

- **PRERACE:** 1,RACETYPE=Vermin
- **ADDLEVEL:** Vermin|2

### Add 3 Levels of Aberration

- **PRERACE:** 1,RACETYPE=Aberration
- **ADDLEVEL:** Aberration|3

### Add 3 Levels of Animal

- **PRERACE:** 1,RACETYPE=Animal
- **ADDLEVEL:** Animal|3

### Add 3 Levels of Construct

- **PRERACE:** 1,RACETYPE=Construct
- **ADDLEVEL:** Construct|3

### Add 3 Levels of Dragon

- **PRERACE:** 1,RACETYPE=Dragon
- **ADDLEVEL:** Dragon|3

### Add 3 Levels of Elemental

- **PRERACE:** 1,RACETYPE=Elemental
- **ADDLEVEL:** Elemental|3

### Add 3 Levels of Fey

- **PRERACE:** 1,RACETYPE=Fey
- **ADDLEVEL:** Fey|3

### Add 3 Levels of Giant

- **PRERACE:** 1,RACETYPE=Giant
- **ADDLEVEL:** Giant|3

### Add 3 Levels of Humanoid

- **PRERACE:** 1,RACETYPE=Humanoid
- **ADDLEVEL:** Humanoid|3

### Add 3 Levels of Magical Beast

- **PRERACE:** 1,RACETYPE=Magical Beast
- **ADDLEVEL:** Magical Beast|3

### Add 3 Levels of Monstrous Humanoid

- **PRERACE:** 1,RACETYPE=Monstrous Humanoid
- **ADDLEVEL:** Monstrous Humanoid|3

### Add 3 Levels of Ooze

- **PRERACE:** 1,RACETYPE=Ooze
- **ADDLEVEL:** Ooze|3

### Add 3 Levels of Outsider

- **PRERACE:** 1,RACETYPE=Outsider
- **ADDLEVEL:** Outsider|3

### Add 3 Levels of Plant

- **PRERACE:** 1,RACETYPE=Plant
- **ADDLEVEL:** Plant|3

### Add 3 Levels of Undead

- **PRERACE:** 1,RACETYPE=Undead
- **ADDLEVEL:** Undead|3

### Add 3 Levels of Vermin

- **PRERACE:** 1,RACETYPE=Vermin
- **ADDLEVEL:** Vermin|3

### Add 4 Levels of Aberration

- **PRERACE:** 1,RACETYPE=Aberration
- **ADDLEVEL:** Aberration|4

### Add 4 Levels of Animal

- **PRERACE:** 1,RACETYPE=Animal
- **ADDLEVEL:** Animal|4

### Add 4 Levels of Construct

- **PRERACE:** 1,RACETYPE=Construct
- **ADDLEVEL:** Construct|4

### Add 4 Levels of Dragon

- **PRERACE:** 1,RACETYPE=Dragon
- **ADDLEVEL:** Dragon|4

### Add 4 Levels of Elemental

- **PRERACE:** 1,RACETYPE=Elemental
- **ADDLEVEL:** Elemental|4

### Add 4 Levels of Fey

- **PRERACE:** 1,RACETYPE=Fey
- **ADDLEVEL:** Fey|4

### Add 4 Levels of Giant

- **PRERACE:** 1,RACETYPE=Giant
- **ADDLEVEL:** Giant|4

### Add 4 Levels of Humanoid

- **PRERACE:** 1,RACETYPE=Humanoid
- **ADDLEVEL:** Humanoid|4

### Add 4 Levels of Magical Beast

- **PRERACE:** 1,RACETYPE=Magical Beast
- **ADDLEVEL:** Magical Beast|4

### Add 4 Levels of Monstrous Humanoid

- **PRERACE:** 1,RACETYPE=Monstrous Humanoid
- **ADDLEVEL:** Monstrous Humanoid|4

### Add 4 Levels of Ooze

- **PRERACE:** 1,RACETYPE=Ooze
- **ADDLEVEL:** Ooze|4

### Add 4 Levels of Outsider

- **PRERACE:** 1,RACETYPE=Outsider
- **ADDLEVEL:** Outsider|4

### Add 4 Levels of Plant

- **PRERACE:** 1,RACETYPE=Plant
- **ADDLEVEL:** Plant|4

### Add 4 Levels of Undead

- **PRERACE:** 1,RACETYPE=Undead
- **ADDLEVEL:** Undead|4

### Add 4 Levels of Vermin

- **PRERACE:** 1,RACETYPE=Vermin
- **ADDLEVEL:** Vermin|4

### Add 5 Levels of Aberration

- **PRERACE:** 1,RACETYPE=Aberration
- **ADDLEVEL:** Aberration|5

### Add 5 Levels of Animal

- **PRERACE:** 1,RACETYPE=Animal
- **ADDLEVEL:** Animal|5

### Add 5 Levels of Construct

- **PRERACE:** 1,RACETYPE=Construct
- **ADDLEVEL:** Construct|5

### Add 5 Levels of Dragon

- **PRERACE:** 1,RACETYPE=Dragon
- **ADDLEVEL:** Dragon|5

### Add 5 Levels of Elemental

- **PRERACE:** 1,RACETYPE=Elemental
- **ADDLEVEL:** Elemental|5

### Add 5 Levels of Fey

- **PRERACE:** 1,RACETYPE=Fey
- **ADDLEVEL:** Fey|5

### Add 5 Levels of Giant

- **PRERACE:** 1,RACETYPE=Giant
- **ADDLEVEL:** Giant|5

### Add 5 Levels of Humanoid

- **PRERACE:** 1,RACETYPE=Humanoid
- **ADDLEVEL:** Humanoid|5

### Add 5 Levels of Magical Beast

- **PRERACE:** 1,RACETYPE=Magical Beast
- **ADDLEVEL:** Magical Beast|5

### Add 5 Levels of Monstrous Humanoid

- **PRERACE:** 1,RACETYPE=Monstrous Humanoid
- **ADDLEVEL:** Monstrous Humanoid|5

### Add 5 Levels of Ooze

- **PRERACE:** 1,RACETYPE=Ooze
- **ADDLEVEL:** Ooze|5

### Add 5 Levels of Outsider

- **PRERACE:** 1,RACETYPE=Outsider
- **ADDLEVEL:** Outsider|5

### Add 5 Levels of Plant

- **PRERACE:** 1,RACETYPE=Plant
- **ADDLEVEL:** Plant|5

### Add 5 Levels of Undead

- **PRERACE:** 1,RACETYPE=Undead
- **ADDLEVEL:** Undead|5

### Add 5 Levels of Vermin

- **PRERACE:** 1,RACETYPE=Vermin
- **ADDLEVEL:** Vermin|5

### Add 6 Levels of Aberration

- **PRERACE:** 1,RACETYPE=Aberration
- **ADDLEVEL:** Aberration|6

### Add 6 Levels of Animal

- **PRERACE:** 1,RACETYPE=Animal
- **ADDLEVEL:** Animal|6

### Add 6 Levels of Construct

- **PRERACE:** 1,RACETYPE=Construct
- **ADDLEVEL:** Construct|6

### Add 6 Levels of Dragon

- **PRERACE:** 1,RACETYPE=Dragon
- **ADDLEVEL:** Dragon|6

### Add 6 Levels of Elemental

- **PRERACE:** 1,RACETYPE=Elemental
- **ADDLEVEL:** Elemental|6

### Add 6 Levels of Fey

- **PRERACE:** 1,RACETYPE=Fey
- **ADDLEVEL:** Fey|6

### Add 6 Levels of Giant

- **PRERACE:** 1,RACETYPE=Giant
- **ADDLEVEL:** Giant|6

### Add 6 Levels of Humanoid

- **PRERACE:** 1,RACETYPE=Humanoid
- **ADDLEVEL:** Humanoid|6

### Add 6 Levels of Magical Beast

- **PRERACE:** 1,RACETYPE=Magical Beast
- **ADDLEVEL:** Magical Beast|6

### Add 6 Levels of Monstrous Humanoid

- **PRERACE:** 1,RACETYPE=Monstrous Humanoid
- **ADDLEVEL:** Monstrous Humanoid|6

### Add 6 Levels of Ooze

- **PRERACE:** 1,RACETYPE=Ooze
- **ADDLEVEL:** Ooze|6

### Add 6 Levels of Outsider

- **PRERACE:** 1,RACETYPE=Outsider
- **ADDLEVEL:** Outsider|6

### Add 6 Levels of Plant

- **PRERACE:** 1,RACETYPE=Plant
- **ADDLEVEL:** Plant|6

### Add 6 Levels of Undead

- **PRERACE:** 1,RACETYPE=Undead
- **ADDLEVEL:** Undead|6

### Add 6 Levels of Vermin

- **PRERACE:** 1,RACETYPE=Vermin
- **ADDLEVEL:** Vermin|6

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


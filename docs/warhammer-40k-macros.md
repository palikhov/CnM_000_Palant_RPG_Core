## UNJAM
/me has angered his weapon's Machine Spirit!
/me @{selected|token_name}'s weapon is jammed! He scored [[(@{selected|ballisticskill} - 1d100)/10]] Degree(s) of Success to unjam it
## ALL OUT ATTACK
/me @{selected|token_name} makes an All Out Attack against @{target|token_name} and scores [[(@{selected|weaponskill} + 30 + ?{modifier|0} - 1d100)/10]] Degree(s) of Success! Until his next turn @{selected|token_name} cannot make any reactions.
## CHARGE ATTACK
/me @{selected|token_name} makes an All Out Attack against @{target|token_name} and scores [[(@{selected|weaponskill} + 30 + ?{modifier|0} - 1d100)/10]] Degree(s) of Success! Until his next turn @{selected|token_name} cannot make any reactions.
## FULL AUTO ATTACK
/me @{selected|token_name} makes a Full Auto Attack and scores [[floor((@{selected|BallisticSkill} - 10 + ?{modifier|0} - 1d100)/10)+1)]] Hit(s)! (The -10 penalty to Ballistic Skill is already accounted for)
## LIGHTNING ATTACK
/me @{selected|token_name} makes a Lightning Attack and scores [[floor((@{selected|weaponskill} - 10 + ?{modifier|0} - 1d100)/10)+1)]] Hit(s)! (The -10 penalty to Weapon Skill is already accounted for)
## SEMI AUTO ATTACK
/me @{selected|token_name} makes a Semi-Auto Attack [[floor(((@{selected|ballisticskill} + ?{modifier|0} - 1d100)/10)/2+1)]] Hit(s)
## SWIFT ATTACK
/me @{selected|token_name} makes a Swift Attack and scores [[floor(((@{selected|weaponskill} + ?{modifier|0} - 1d100)/10)/2+1)]] Hit(s)
## FLAME ATTACK
/me @{selected|token_name} is attacked with a fire weapon! [[(@{selected|agility} -1d100)/10]] Degrees of Success. On a failure take [[1d10]] points of Energy damage (ignoring armor and Toughness) to the [[1t[Hitzone]]] and 1 Level of Fatigue.
## TOXIC ATTACK
/me must test against the Toxic Quality
/me @{selected|character_name} scores [[floor((@{selected|Toughness} - 10-2d100dh1)/10+1)]] Degree(s) of Success. On a failure, take [[1d10]] points of Chemical damage, to the [[1t[Hitzone]]] bypassing armor (but not Toughness) (the re-roll from altered Space Marine physiology is already accounted for)
## ON FIRE
/me is on fire! He must pass an Agility Test to stop being on fire: [[(@{selected|agility} +?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success. If you fail this test, you take [[1d10]] Energy damage to the [[1t[Hitzone]]] (ignoring armor) and 1 Level of Fatigue, but may otherwise act normally this turn.
## PINNING
/me @{selected|token_name} is being pinned! [[(@{selected|willpower} + ?{modifier|-10} - 2d100dh1)/10]] Degree(s) of Success! If you fail this test, you take a -20 to Ballistic Skill Tests and may only take a half action each turn. The Marine's Nerves of Steel Talent is already accounted for.
## BOLTER ATTACK
/me @{selected|token_name} does [[2d10k1+9]] Explosive Damage (Pen 4) With his Bolter on @{target|token_name}'s [[1t[Hitzone]]]
## FORCE WEAPON (CLAYMORE)
/me @{selected|token_name} does [[1d10 + 11 + @{selected|PsyRating} + @{selected|strengthbonus}]] + [[(?{degrees of success?|0}d10)]] Rending damage (Pen [[3 + @{selected|PsyRating}]] with his Force Scythe on @{target|token_name}'s [[1t[Hitzone]]]. 
## POWER FIST/CLAW
/me @{selected|token_name} swings his power fist into @{target|token_name}'s [[1t[Hitzone]]], dealing [[2d10 + (@{selected|strengthbonus}*2)]] Energy Damage (Pen 9). Any weapon attempting to parry this weapon sunders on a roll of 75+:  [[1d100]]
/me @{selected|token_name} swipes his Lightning Claw and hits @{target|token_name}'s [[1t[Hitzone]]], dealing [[1d10r<3 + 6 + (@{selected|strengthbonus}*2)]] Energy Damage (Pen 8). Any weapon attempting to parry this weapon sunders on a roll of 75+:  [[1d100]]
## TWIN-LINKED/STORM
/me @{selected|token_name} does [[3d10+8]] and [[3d10+8]] Impact Damage (Pen 6) With his Twin-Linked Reaper Autocannon on @{target|token_name}'s [[1t[Hitzone]]] and [[1t[Hitzone]]]
## D10
/me rolls a [[?{amount of dice|1}d10 + ?{modifier?|0}]]
## D5
/me rolls a [[?{amount of dice|1}d5 + ?{modifier?|0}]]
## FOCUS POWER
?{Power Level|
Fettered, 
/me @{selected|token_name} uses a Fettered Psychic Power [[floor((@{selected|Willpower} + ((@{selected|PsyRating}*.5)*5) - 1d100)/10)]] Degree(s) of Success. You do not suffer Psychic Phenomena.|
Unfettered,
/me @{selected|token_name} uses an Unfettered Psychic Power [[floor((@{selected|Willpower} + (@{selected|PsyRating}*5) - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10)]] Degree(s) of Success. If your result is in red&#44; you suffer Psychic Phenomena |
Push,
/me @{selected|token_name} uses a Pushed Psychic Power&#44; pushing it by [[?{Push by&#124;3&#125;]].
/me [[floor((@{selected|Willpower} + ((@{selected|PsyRating}+?{Push by&#125;)*5) - 1d100)/10)]] Degree(s) of Success. You suffer Psychic Phenomena. |
}
## PLASMA:OVERHEATS
/desc Plasma Weapons overheat on a d100 roll of 91-100
?{which gun?|
Plasma Pistol,
/me @{selected|token_name}'s Plasma Pistol has overheated! He takes [[1d10+10]] Energy Damage (Pen 0) on whichever hand was holding it. Or he can choose to drop it. This weapon cannot be picked up or fired until it has spent 1 full turn cooling down. |
Plasma Gun,
/me @{selected|token_name}'s Plasma Gun has overheated! He takes [[1d10+12]] Energy Damage (Pen 0) on whichever hand was holding it. Or he can choose to drop it. This weapon cannot be picked up or fired until it has spent 1 full turn cooling down. |
Plasma Cannon,
/me @{selected|token_name}'s Plasma Pistol has overheated! He takes [[2d10+12]] Energy Damage (Pen 0) on one of the hands he was using to hold it. Or he can choose to drop it. This weapon cannot be picked up or fired until it has spent 2 full turns cooling down. |
}
## DAMAGE:GRENADES
?{Which Grenade?|
Frag,
/me The frag grenade explodes with a thunderous roar&#44; dealing [[2d10+2]] Explosive Damage (Pen 0) to everyone within 4 meters. |
Krak,
/me The krak grenade explodes with a sharp crack&#44; dealing [[3d10+6]] Explosive Damage (Pen 6) to the target. |
Plasma,
/me The plasma grenade explodes in a blinding flash&#44; dealing [[1d10+12]] Energy Damage (Pen 8) to everyone within 1 meter. This weapon utilizes a deliberate plasma containment failure technology and continues to do this damage to everyone in range of the grenade for [[1d5]] rounds. |
}
##  INITIATIVE
/roll 1d10+@{selected|Agility-Bonus} &{tracker}
CHARACTERISTIC TESTS
?{Which Characteristic?|
Strength,
/me @{selected|token_name} makes a Strength Test and scores [[(@{selected|strength} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Toughness,
/me @{selected|token_name} makes a Toughness Test and scores [[(@{selected|toughness} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Agility,
/me @{selected|token_name} makes an Agility Test and scores [[(@{selected|agility} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Intelligence,
/me @{selected|token_name} makes an Intelligence Test and scores [[(@{selected|intelligence} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Perception,
/me @{selected|token_name} makes a Perception Test and scores [[(@{selected|perception} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Willpower,
/me @{selected|token_name} makes a Willpower Test and scores [[(@{selected|willpower} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Fellowship,
/me @{selected|token_name} makes a Fellowship Test and scores [[(@{selected|fellowship} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
}
## OPPOSED TESTS
?{Which Characteristic?|
Weapon Skill,
/me @{selected|token_name} makes a Weapon Skill Test against @{target|token_name} and scores [[(@{selected|weaponskill} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success!| 
Strength,
/me @{selected|token_name} makes a Strength Test against @{target|token_name} and scores [[(@{selected|strength} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. | 
Toughness,
/me @{selected|token_name} makes a Toughness Test against @{target|token_name} and scores [[(@{selected|toughness} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Agility,
/me @{selected|token_name} makes an Agility Test against @{target|token_name} and scores [[(@{selected|agility} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Intelligence,
/me @{selected|token_name} makes an Intelligence Test against @{target|token_name} and scores [[(@{selected|intelligence} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Perception,
/me @{selected|token_name} makes a Perception Test against @{target|token_name} and scores [[(@{selected|perception} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Willpower,
/me @{selected|token_name} makes a Willpower Test against @{target|token_name} and scores [[(@{selected|willpower} + ?{modifiers&#124;0&#125; -1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success. |
Fellowship,
/me @{selected|token_name} makes a Fellowship Test against @{target|token_name} and scores [[(@{selected|fellowship} + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
} ?{Opposed By|
Weapon Skill,
/desc vs @{target|token_name}'s Weapon Skill Test: [[(@{target|weaponskill} + ?{opponent modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Strength,
/desc vs @{target|token_name}'s Strength Test: [[(@{target|strength} + ?{opponent modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Toughness,
/desc vs @{target|token_name}'s Toughness Test: [[(@{target|toughness} + ?{opponent modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Agility,
/desc vs @{target|token_name}'s Agility Test: [[(@{target|agility} + ?{opponent modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |  
Intelligence,
/desc vs @{target|token_name}'s Intelligence Test: [[(@{target|Intelligence} + ?{opponent modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Perception,
/desc vs @{target|token_name}'s Perception Test: [[(@{target|perception} + ?{opponent modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
Willpower,
/desc vs @{target|token_name}'s Willpower Test [[(@{target|willpower} + ?{opponent modifiers&#124;0&#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success. |
Fellowship,
/desc vs @{target|token_name}'s Fellowship Test [[(@{target|fellowship} + ?{opponent modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
}
## STANDARD ATTACK
?{What kind of attack?|
Melee,
/me @{selected|token_name} makes a standard melee attack [[(@{selected|weaponskill} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (the +10 bonus to Weapon Skill is already accounted for) |
Ranged,
/me @{selected|token_name} makes a standard ranged attack [[(@{selected|ballisticskill} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (the +10 bonus to Ballistic Skill is already accounted for) |
}
## WEAPON EFFECTS
?{Which Effect?|
On Fire,
/me @{selected|token_name} is on fire! 
/me @{selected|token_name} Willpower Test to act this turn: [[(@{selected|willpower} - 1d100)/10]] Degrees of Success. If you passed this test&#44; you may roll to stop being on fire.
/me @{selected|token_name} must pass an Agility Test to stop being on fire: [[(@{selected|agility} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success. If you fail this test&#44; you take [[1d10]] Energy damage to the [[1t[Hitzone]]] (ignoring armor ) and 1 Level of Fatigue. |
Toxic,
/me @{selected|token_name} must test against the Toxic ([[?{value&#124;0&#125;]]) Quality
/me @{selected|character_name} scores [[(@{selected|Toughness} - (?{value&#125; * 10) + ?{modifier?&#124;0&#125; - 1d100)/10]] Degree(s) of Success. On a failure&#44; take [[1d10]] points of Chemical damage&#44; to the [[1t[Hitzone]]] bypassing armor (but not Toughness) |
Pinning,
/me @{selected|token_name} is being pinned! [[(@{selected|willpower} + ?{modifier&#124;-10&#125; - 1d100)/10]] Degree(s) of Success! If you fail this test&#44; you take a -20 to Ballistic Skill Tests and may only take a half action each turn. If you have the Nerves of Steel Talent&#44; you may re-roll this test. |
Haywire,
/me [[1t[Haywire]]] |
Blood Loss,
/me @{selected|token_name} is suffering from Blood Loss! At the start your turn&#44; you suffer 1 Level of Fatigue. He also must roll to not bleed out: 
/me [[1d100<90]]: On a 1&#44; he survives. On a 0&#44; he bleeds to death. |
Fear,
/me @{selected|token_name} is affected by fear and must roll a Willpower Test! He scores: [[(@{selected|willpower} - ((?{value&#124;1&#125; * 10) -10) + ?{modifier?&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Shocking,
/me @{selected|token_name} is affected by a shocking weapon and must roll a Toughness Test. He scores: [[(@{selected|toughness} - 1d100)/10]] Degrees of Success! If you fail this test you take 1 Level of Fatigue and are Stunned for a number of rounds equal to half your Degrees of Failure (rounding down&#44; minimum 1). |
}
## STORM SHIELD
?{which action|
Force Field,
/me @{selected|token_name} is protected by the force field built into his Storm Shield. [[1d100cs<55cf1cf2cf3cf4cf5cf6cf7cf8cf9cf10]] If your result is in green&#44; @{target|token_name}'s attack deals no damage. If your result is in blue&#44; the shield overloads and ceases to function until repaired. |
Parry,
/me @{selected|token_name} attempts to parry @{target|token_name}'s attack with his Storm Shield. [[(@{selected|WeaponSkill} + 15 + ?{modifiers?&#124;0&#125; - 1d100)/10]] Degree(s) of Success (the +15 for the Defensive Quality has already been accounted for) |
Attack,
/me @{selected|token_name} makes an Attack against @{target|token_name} with his Storm Shield and scores [[(@{selected|weaponskill} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (the -20 for the unwieldy nature of the Storm Shield&#44; and +10 for a standard melee attack have all been accounted for) |
Damage,
/me @{selected|token_name} does [[1d10 + @{selected|strengthbonus}]] Impact damage (Pen 0) with his Storm Shield on @{target|token_name}'s [[1t[Hitzone]]] |
}
## ATTACK:MELEE
?{Which Melee Attack?|
Standard,
/me @{selected|token_name} makes a standard melee attack [[(@{selected|weaponskill} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (the +10 bonus to Weapon Skill is already accounted for) |
Charge, 
/me @{selected|token_name} makes a thunderous charge and scores [[(@{selected|weaponskill} + 20 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! You must move a minimum of 4 meters and a maximum of [[@{selected|agility-bonus}*3]] meters to make a charge. |
All-Out Attack,
/me @{selected|token_name} makes an All Out Attack and scores [[(@{selected|weaponskill} + 30 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! Until his next turn @{selected|token_name} cannot make any reactions. |
Swift Attack,
/me @{selected|token_name} makes a Swift Attack and scores [[floor(((@{selected|weaponskill} + ?{modifier&#124;0&#125; - 1d100)/10)/2+1)]] Hit(s) (You may score up to [[floor(@{selected|weaponskill}/10)]] hits with Swift Attack) |
Lightning Attack,
/me @{selected|token_name} makes a Lightning Attack and scores [[floor((@{selected|weaponskill} - 10 + ?{modifier&#124;0&#125; - 1d100)/10)+1)]] Hit(s)! (The -10 penalty to Weapon Skill is already accounted for) (You may score up to [[floor(@{selected|weaponskill}/10)]] hits with Lightning Attack) |
}
## ATTACK:RANGED
?{Which Ranged Attack?|
Standard,
/me @{selected|token_name} makes a standard ranged attack [[(@{selected|ballisticskill} + 10 + ?{modifier&#124;0&#125; - 1d100cf>96cf=100)/10]] Degree(s) of Success! (the +10 bonus to Ballistic Skill is already accounted for) 
/desc If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. |
Semi Auto,
/me @{selected|token_name} makes a Semi-Auto Attack [[floor(((@{selected|ballisticskill} + ?{modifier&#124;0&#125; - 1d100cf>95cf=100)/10)/2+1)]] Hit(s) 
/desc If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. |
Full Auto,
/me @{selected|token_name} makes a Full Auto Attack and scores [[floor((@{selected|BallisticSkill} - 10 + ?{modifier&#124;0&#125; - 1d100cf>94cf=100)/10)+1)]] Hit(s)! (The -10 penalty to Ballistic Skill is already accounted for)
/desc If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. |
Suppressing Fire,
/me @{selected|token_name} lays down Suppressing Fire and scores [[floor((@{selected|BallisticSkill} - 20 + ?{modifier&#124;0&#125; - 1d100cf>94cf=100)/10)+1)]] Hit(s)! (The -20 penalty to Ballistic Skill is already accounted for)&#44; regardless of whether you hit or not&#44; the target of your Suppression must make a -10 Pinning Test (if you fired on Semi-Auto) or a -20 Pinning Test (if you fired on Full-Auto).
/desc If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. 
}
DODGE

/me @{selected|token_name} attempt to dodge @{target|token_name}'s attack! [[(@{selected|dodge} + ?{modifiers|0} - 1d100)/10]] Degree(s) of Success. You may dodge up to [[@{selected|Agility-bonus}]] hits

			PARRY

/me @{selected|token_name} attempts to parry @{target|token_name}'s attack! [[(@{selected|WeaponSkill} + ?{modifiers|0} - 1d100)/10]] Degree(s) of Success.

			REACTIONS

?{Dodge or Parry? |
Dodge,
/me @{selected|token_name} attempt to dodge @{target|token_name}'s attack! [[(@{selected|agility} + ?{Dodge Bonus?&#124;0&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. You may dodge up to [[floor(@{selected|Agility}/10)]] hits or move up to [[floor(@{selected|Agility}/10)]] meters to avoid an area effect. |
Parry,
/me @{selected|token_name} attempts to parry @{target|token_name}'s attack! [[(@{selected|WeaponSkill} + ?{Parry Bonus?&#124;0&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success. |
}

			MOOK INITIATIVE

/roll [[1d10+?{Agility Bonus?|3}]] &{tracker}

			STEALTH

/me @{selected|token_name} attempts to sneak by @{target|token_name}. You score [[(@{selected|agility} + ?{modifiers|0} - 1d100)/10]] Degree(s) of success on your Stealth Test vs @{target|token_name}'s [[(@{target|perception} + ?{opponent modifiers|0} - 1d100)/10]] Degree(s) of Success on his Perception Test.

			MAGNI POWERS LIST

?{Which Power|
Inspire,
&{template:default&#125; {{name=Inspire&#125;&#125; {{Action=Half&#125;&#125; {{Sustained=Yes&#125;&#125; {{Range= PR x 5m Radius&#125;&#125; 
/desc The psyker can bolster his comrades by sending out waves of reassurance and calm. A number of targets equal to the psyker’s  PR immediately overcome the effects of Pinning and gain a +10 resistance against Fear. This effect lasts as long as the targets stay within range of the psyker, and the psyker maintains the power. |
Iron Arm,
/desc **Name:** Iron Arm **Action:** Half or Reaction **Sustained** Yes
/desc While this power is in effect&#44; the Librarian gains one additional Reaction each round that may only be used to parry&#44; with a bonus on the Weapon Skill Test to parry equal to his PR x 3. Note that this power prevents the Librarian from using his arm for any other purpose&#44; such as wielding a weapon&#44; climbing&#44; and so on. |
Storm Caller,
&{template:default&#125; {{name=Storm Caller&#125;&#125; {{Action=Full&#125;&#125; {{Sustained=Yes&#125;&#125; {{Range= PR x 5m Radius&#125;&#125;
/desc The Rune Priest invokes the ancient rites of ice and snow&#44; calling up a blizzard of psychic energy around himself and his allies. While this power is in effect the Rune Priest and all allies within the power’s radius become shrouded in ethereal mist. All ranged attacks they make&#44; or that are made against them&#44; suffer a penalty of –5 x PR. Any ally who moves outside the range of the power immediately loses its effects. |
Thunderclap,
&{template:default&#125; {{name=Thunderclap&#125;&#125; {{Action=Full&#125;&#125; {{Range= PR x 10m Radius&#125;&#125;
/desc With a word of power and a clap of his mighty hands&#44; the Rune Priest creates a deafening crack of thunder that rolls across the battlefield. All those within range of this power (friends or foes&#44; though not including the Rune Priest) suffer 1d5 x PR Impact damage. This damage is reduced by Toughness as normal. However&#44; only armor worn on the head protects against it. In addition&#44; anyone suffering damage from this attack must make a Toughness Test with a penalty of –5 x PR or be deafened for 1d10 rounds. Finally&#44; fragile objects such as mundane glass&#44; crystal or fine ceramics within the power’s range are shattered (though the GM has the final say on whether an object is affected). |
}

			RAVEN GUARD ABILITIES

?{Which Ability?|
Solo Mode,
&{template:default&#125; {{name=Master of the Shadows&#125;&#125; {{Type=Passive&#125;&#125; {{Effect= When the Battle-Brother is in solo mode&#44; he may re-roll any failed Concealment&#44; Shadowing and Silent Move Tests.&#125;&#125; |
Squad Attack,
&{template:default&#125; {{name=Exploit Weakness&#125;&#125; {{Action=Half&#125;&#125; {{Cohesion=4&#125;&#125; {{Sustained=No&#125;&#125; {{Effect= As a Half Action&#44; any Battle-Brother in Support Range may single out an enemy. Until the beginning of that Battle-Brother’s next turn&#44; all members of the Kill-team may re-roll damage rolls against that target (the second result must be taken). Only one target may be singled out at a time.&#125;&#125; |
Squad Defense,
&{template:default&#125; {{name=Evasive Maneuvers&#125;&#125; {{Action=Full&#125;&#125; {{Cohesion=3&#125;&#125; {{Sustained=Yes&#125;&#125; {{Effect= All Battle-Brothers in Support Range no longer trigger the effects of Overwatch from an enemy. In addition&#44; Battle-Brothers in Support Range gain a +20 bonus to all tests to avoid Pinning.&#125;&#125; |
}

			IRON HANDS ABILITIES

?{Which Ability?|
Solo Mode,
&{template:default&#125; {{name=Suffer no Weakness&#125;&#125; {{Type=Passive&#125;&#125; {{Effect= Once per combat&#44; the Battle-Brother may select a single enemy. For the duration of the combat&#44; the Battle-Brother gains the Hatred Talent against his chosen foe and gains a bonus to Damage equal to one-half (rounding up) of his unmodified Intelligence Bonus&#125;&#125; |
Squad Attack,
&{template:default&#125; {{name=Ruthless Advance&#125;&#125 {{Action=Half&#125;&#125 {{Cohesion=2&#125;&#125 {{Sustained=No&#125;&#125 {{Effect=The Battle-Brother and those within Support Range may spend their Reactions to make a Full Move. This movement must be made towards the nearest enemy. The Space Marines using this ability are immune to pinning until the beginning of their next Turn.&#125;&#125 |
Squad Defense,
&{template:default&#125; {{name=Strength of Iron&#125;&#125 {{Action=Half&#125;&#125 {{Cohesion=2&#125;&#125 {{Sustained=No&#125;&#125 {{Effect=The Battle-Brother and those in Support Range of him gain a +10 bonus to resist Fear and Cohesion Damage and add +2 to their Toughness Bonus when reducing Damage from ranged attacks.&#125;&#125 |
}

			BLACK TEMPLARS ABILITIES

?{Which Ability?|
Solo Mode,
&{template:default&#125; {{name=Righteous Zeal&#125;&#125; {{Effect= Once per combat&#44; a Battle-Brother of the Black Templars Chapter may call upon Righteous Zeal as a Free Action at the start of his Turn. While under the effects of the Righteous Zeal&#44; Damage inflicted by the Battle-Brother’s melee attacks against creatures with the Daemonic Trait is not reduced by Toughness Bonus. In addition&#44; the Battle Brother’s own Toughness Bonus is increased by +4 when reducing Damage from attacks by creatures with the Daemonic Trait or Damage from Psychic Powers and weapons. Righteous Zeal lasts for a number of Rounds equal to the Battle-Brother’s Rank.&#125;&#125; |
Squad Attack,
&{template:default&#125; {{name=Holy Vengeance&#125;&#125; {{Action=Half&#125;&#125; {{Cohesion=2&#125;&#125; {{Sustained=No&#125;&#125; {{Effect= Until the start of his next Turn&#44; whenever the Battle-Brother and those in Support Range of him make a successful Standard Attack with a melee weapon (whether or not Damage is inflicted) they may immediately make an additional Standard Attack with that same weapon&#44; against the same foe&#44; as a Free Action. If this blow also hits&#44; then they may make an additional Standard Attack and so on&#44; up to a total number of extra attacks equal to their Agility Bonus&#125;&#125; |
Squad Defense,
&{template:default&#125; {{name=Armor of Faith&#125;&#125; {{Action=Free&#125;&#125; {{Cohesion=2&#125;&#125; {{Sustained=Yes&#125;&#125; {{Effect= While this power is in effect&#44; the Battle-Brother and those in Support Range of him add +10 to all tests made to resist Psychic Powers and add +4 to their Toughness Bonus when reducing Damage from physical attacks from creatures with the Daemonic Trait and from Psychic Powers.&#125;&#125; |
}

			DAMAGE CALCULATOR

?{Location?|
Head,
/me @{selected|token_name} deals [[?{damage&#124;0&#125;]] damage (Penetration: [[?{penetration?&#124;0&#125]]) to @{target|token_name}'s head! 
/me @{selected|token_name} deals a total of [[({0d0&#44; ?{damage&#125; - ({0&#44; ((@{target|HArmour} + ?{cover?&#124;0&#125;) - ?{penetration?&#125;)&#125;kh1) - (@{target|ToughnessBonus})&#125;kh1)]] Damage to @{target|token_name}'s head! |
Body,
/me @{selected|token_name} deals [[?{damage&#124;0&#125;]] damage (Penetration: [[?{penetration?&#124;0&#125]]) to @{target|token_name}'s body! 
/me @{selected|token_name} deals a total of [[({0d0&#44; ?{damage&#125; - ({0&#44; ((@{target|BArmour} + ?{cover?&#124;0&#125;) - ?{penetration?&#125;)&#125;kh1) - (@{target|ToughnessBonus})&#125;kh1)]] Damage to @{target|token_name}'s body! |
Right Arm,
/me @{selected|token_name} deals [[?{damage&#124;0&#125;]] damage (Penetration: [[?{penetration?&#124;0&#125]]) to @{target|token_name}'s right arm! 
/me @{selected|token_name} deals a total of [[({0d0&#44; ?{damage&#125; - ({0&#44; ((@{target|ArArmour} + ?{cover?&#124;0&#125;) - ?{penetration?&#125;)&#125;kh1) - (@{target|ToughnessBonus})&#125;kh1)]] Damage to @{target|token_name}'s right arm! |
Left Arm,
/me @{selected|token_name} deals [[?{damage&#124;0&#125;]] damage (Penetration: [[?{penetration?&#124;0&#125]]) to @{target|token_name}'s left arm! 
/me @{selected|token_name} deals a total of [[({0d0&#44; ?{damage&#125; - ({0&#44; ((@{target|AlArmour} + ?{cover?&#124;0&#125;) - ?{penetration?&#125;)&#125;kh1) - (@{target|ToughnessBonus})&#125;kh1)]] Damage to @{target|token_name}'s left arm! |
Right Leg,
/me @{selected|token_name} deals [[?{damage&#124;0&#125;]] damage (Penetration: [[?{penetration?&#124;0&#125]]) to @{target|token_name}'s right leg! 
/me @{selected|token_name} deals a total of [[({0d0&#44; ?{damage&#125; - ({0&#44; ((@{target|LrArmour} + ?{cover?&#124;0&#125;) - ?{penetration?&#125;)&#125;kh1) - (@{target|ToughnessBonus})&#125;kh1)]] Damage to @{target|token_name}'s right leg! |
Left Leg,
/me @{selected|token_name} deals [[?{damage&#124;0&#125;]] damage (Penetration: [[?{penetration?&#124;0&#125]]) to @{target|token_name}'s left leg! 
/me @{selected|token_name} deals a total of [[({0d0&#44; ?{damage&#125; - ({0&#44; ((@{target|LlArmour} + ?{cover?&#124;0&#125;) - ?{penetration?&#125;)&#125;kh1) - (@{target|ToughnessBonus})&#125;kh1)]] damage to @{target|token_name}'s left leg! |
}

			CRITICAL HIT
/me @{selected|token_name} inflicts a critical hit on @{target|token_name}!
?{What Kind of Damage?|
Chemical, 
?{Where?&#124;
Head&#44; 
/roll 1t[CH-Ch-H] &#124;
Body&#44;
/roll 1t[CH-Ch-B] &#124;
Right Arm&#44;
/roll 1t[CH-Ch-A] &#124;
Left Arm&#44;
/roll 1t[CH-Ch-A] &#124;
Right Leg&#44;
/roll 1t[CH-Ch-L] &#124;
Left Leg &#44;
/roll 1t[CH-Ch-L] &#125; |
Energy, 
?{Where?&#124;
Head&#44; 
/roll 1t[CH-E-H] &#124;
Body&#44;
/roll 1t[CH-E-B] &#124;
Right Arm&#44;
/roll 1t[CH-E-A] &#124;
Left Arm&#44;
/roll 1t[CH-E-A] &#124;
Right Leg&#44;
/roll 1t[CH-E-L] &#124;
Left Leg &#44;
/roll 1t[CH-E-L] &#125; |
Explosive, 
?{Where?&#124;
Head&#44; 
/roll 1t[CH-Ex-H] &#124;
Body&#44;
/roll 1t[CH-Ex-B] &#124;
Right Arm&#44;
/roll 1t[CH-Ex-A] &#124;
Left Arm&#44;
/roll 1t[CH-Ex-A] &#124;
Right Leg&#44;
/roll 1t[CH-Ex-L] &#124;
Left Leg &#44;
/roll 1t[CH-Ex-L] &#125; |
Impact, 
?{Where?&#124;
Head&#44; 
/roll 1t[CH-I-H] &#124;
Body&#44;
/roll 1t[CH-I-B] &#124;
Right Arm&#44;
/roll 1t[CH-I-A] &#124;
Left Arm&#44;
/roll 1t[CH-I-A] &#124;
Right Leg&#44;
/roll 1t[CH-I-L] &#124;
Left Leg &#44;
/roll 1t[CH-I-L] &#125; |
Rending, 
?{Where?&#124;
Head&#44; 
/roll 1t[CH-R-H] &#124;
Body&#44;
/roll 1t[CH-R-B] &#124;
Right Arm&#44;
/roll 1t[CH-R-A] &#124;
Left Arm&#44;
/roll 1t[CH-R-A] &#124;
Right Leg&#44;
/roll 1t[CH-R-L] &#124;
Left Leg &#44;
/roll 1t[CH-R-L] &#125;
}

			DAMAGE:MACROBATTERIES
/me @{selected|token_name} scores [[?{# of hits|1}]] hits with its macrobatteries! It deals [[((?{# of hits}-@{target|shipshields1})*3) + ((?{# of hits}-@{target|shipshields1})d10) - (@{target|shiparmor})]] damage to @{target|token_name}
/desc @{target|token_name} reduced the amount of hits by [[@{target|shipshields1}]] with its void shields.

			VOIDCOMBAT:MANEUVER-ACTIONS
?{Which Action?|
Adjust Bearing,
/me @{target|Which Character?|token_name} attempts to Adjust the ship's Bearing and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success!
/me On a success&#44; the ship may turn after moving 1 VU less than its speed. For every Degree of Success&#44; it may turn after moving 1 less VU. A ship must move at least 1 VU before turning. Once it has turned&#44; it must move its remaining distance. |
All Ahead Full,
/me @{target|Which Character?|token_name} attempts to move faster and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may increase the number of VUs it moves by 1. All shipboard firing suffers a [[-20]] penalty this turn. |
Burn Retros,
/me @{target|Which Character?|token_name} attempts to slow down or come to a stop and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may  decrease the number of VUs it moves by 1. It may also turn after moving one VU less than its speed per Degree of Success. If it would come to a stop it may turn in place. The ship suffers [[-20]] to all shipboard shooting this turn. |
Come to New Heading,
/me @{target|Which Character?|token_name} attempts to Come to a New Heading and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me Success indicates that the ship may turn when it has moved half its speed&#44; then turn again once it has moved its full speed. This radical course correction imposes a [[-20]] penalty on Ballistic Skill Tests during this turn. |
Disengage,
/me @{target|Which Character?|token_name} attempts to Disengage and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success.
/me If the Degrees of Success are more than the amount of ships within 20 VUs&#44; the ship successfully disengages from combat&#44; and may not re-enter it. |
Evasive Maneuvers,
/me @{target|Which Character?|token_name} attempts Evasive Maneuvers and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success!
/me Each Degree of Success imposes a [[-10]] penalty to all shooting directed towards the @{selected|token_name}&#44; which suffers the same penalty until its next turn. |
}

			VOIDCOMBAT:EXTENDED-ACTIONS
?{Which Action?|
Active Augury,
/me @{selected|token_name} is attempting to scan the area around the @{target|token_name} with an Active Augury. He scores [[(@{selected|perception} + @{target|shipdetection} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Scrutiny Test.
/me On a success&#44; the scan reveals basic and important information about celestial bodies &#44; void phenomena&#44; and other ships with 20 VUs of the @{target|token_name}. If there is a vessel on Silent Running in this area&#44; it is automatically detected. For each Degree of Success&#44; the range of the scan is extended 5 VUs. |
Aid the Machine Spirit,
/me @{selected|token_name} attempts to Aid the Machine Spirit&#44; he scores [[(@{selected|intelligence} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; you may add +5 to your vessel's Maneuverability or Detection for the remainder of the turn. For every 2 Degrees of Success&#44; you may add an additional +5 to the same system. |
Disinformation,
/me @{selected|token_name} attempts to spread Disinformation to the crew&#44; misrepresenting the actual goings-on outside the ship. He scores  [[(@{selected|fellowship} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Deceive Test.
/me If he succeeds&#44; he can increase the Crew's Morale by 1d5 per Degree of Success&#44; up to its maximum. A failure indicates a loss of 1d10 Crew Morale. |
Emergency Repairs,
/me @{selected|token_name} attempts to organize and lead Emergency Repair Crews to damaged portions of the ships. He scores  [[(@{selected|intelligence} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a Success&#44; @{selected|token_name} and his repair crews restore one Unpowered&#44; Damaged&#44; or Depressurized component to working order. This repair take [[1d5]] turns&#44; minus 1 per Degree of Success. |
Fight Fires,
/me @{selected|token_name} attempts to organize and lead firefighting teams into the blaze. He scores  [[(@{selected|fellowship} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the firefighting teams successfully put out the fire within one turn. | 
Flank Speed, | 
Focused Augury, |
Hail the Enemy, |
Hit and Run, |
Hold Fast!, |
Jam Communications, | 
Lock on Target, |
Prepare to Repel Boarders!, |
Put Your Backs Into It!, |
Triage, |
}

			COMRADE:BASIC ORDERS
?{Which Order?|
Covering Fire!,
/me @{selected|token_name} orders @{target|Comrade|token_name} to cover him!
/desc You gain +5 to all Ballistic Skill Rolls this turn. |
Close Quarters!,
/me @{selected|token_name} orders @{target|Comrade|token_name} to join him in melee!
/desc You gain +10 to all Weapon Skill Rolls this turn. |
Take Cover!,
/me @{selected|token_name} orders @{target|Comrade|token_name} to take cover!
/desc All attacks against the comrade this turn must roll damage&#44; if the damage does not exceed 3+AP of the comrade's cover&#44; he is not wounded by the attack. |
}

			COMRADE:MEDIC
?{Which Order?|
Passive Ability,
&{template:default&#125; {{name=Assistant Medic&#125;&#125; {{Effect= The Comrade acts as a natural extension of the Medic on the battlefield. The Medic relays him complex medical instructions&#44; and the Comrade obeys with precision. As long as his Comrade is within range of communication&#44; the Medic may perform Treat Injury Tests on any character next to the Comrade at a  –10 penalty.&#125;&#125; |
Rapid Intervention,
&{template:default&#125; {{name=Rapid Intervention&#125;&#125; {{Action=Half&#125;&#125;{{Effect= The Medic sends his comrade to keep an individual stable until he can reach the patient. The Medic must make a +20 Treat Injury Test as part of this order. If he succeeds&#44; as long as his comrade remains with the patient and the patient does not move&#44; take any strenuous action&#44; or suffer further harm&#44; the patient need not roll for Blood Loss and his condition does not otherwise worsen. The Medic must be in communications range with his comrade for this ability to work. &#125;&#125; |
It's Not That Bad...,
&{template:default&#125; {{name=It's Not That Bad...&#125;&#125; {{Action=Full&#125;&#125; {{Effect= Working as a close team&#44; the medic and his comrade set about stitching up lacerations&#44; splinting broken bones&#44; and shoveling intestines back into their proper place. The Medic chooses one character currently suffering from Critical Damage and makes a +0 Treat Injury Test. If he succeeds the injured character gains a number of Temporary Wounds equal to the Medic’s Intelligence Bonus&#44; plus one additional temporary wound for every degree of success scored. These Temporary Wounds are lost first. This ability cannot be used on a patient again until he has removed all Critical Damage. The medic’s comrade must be in Cohesion for this ability to function. &#125;&#125; |

			SOLO/SQUAD:FFL
?{Which Ability?|
Solo Mode,
&{template:default&#125; {{name=Esprit de Corps&#125;&#125; {{Effect= Reroll any fellowship tests when dealing with friendly foreigners (this does not include members of your squad). You may also add 1 to your squad’s cohesion as long as you are the squad leader.&#125;&#125;  |
Squad Attack,
&{template:default&#125; {{name=Into the Fires of Battle&#125;&#125;  {{Action=Free&#125;&#125;  {{Cohesion=3&#125;&#125;  {{Sustained=No&#125;&#125' {{Effect= French Foreign Legionnaires are ruthless in the attack. When the Legionnaire uses this ability&#44; both he and those in support range may make an immediate half move action and two standard attacks with any ranged weapon.&#125;&#125;  |
Squad Defense,
&{template:default&#125; {{name=March or Die&#125;&#125; {{Action=Free&#125;&#125; {{Cohesion=2&#125;&#125; {{Sustained=Yes&#125;&#125; {{Effect= While this ability is in effect&#44; the Legionnaire and all within support range may ignore one level of fatigue per Rank and re-roll failed toughness tests. This ability lasts for a number of hours equal to the Legionnaire’s rank.&#125;&#125; &#124;
}
}

			SOLO/sQUAD:SEAL
?{Which Ability?|
Solo Mode,
&{template:default&#125; {{name=Silent Professional&#125;&#125; {{Effect= Reroll any fellowship tests when dealing with members of a military or any military professionals (this does not include members of your squad). You may also add 1 to your squad’s cohesion as long as you are the squad leader.&#125;&#125;  |
Squad Attack,
&{template:default&#125; {{name=Lead By Example&#125;&#125;  {{Action=Free&#125;&#125;  &#44{{Cohesion=2&#125;&#125;  {{Sustained=No&#125;&#125' {{Effect= While this ability is being utilized&#44; all operators within support range gain a bonus on all tests equal the SEAL’s Fellowship bonus times 5. Each round&#44; the SEAL may also single out one operator in his squad and grant him one re-roll of any one test&#44; this re-roll includes the bonus provided by his fellowship bonus.&#125;&#125;  |
Squad Defense,
&{template:default&#125; {{name=Rally Cry&#125;&#125; {{Action=Free&#125;&#125; {{Cohesion=0&#125;&#125; {{Sustained=No&#125;&#125; {{Effect=When an operator uses this ability&#44; it instantly restores a number of Cohesion equal to his Fellowship Bonus. This ability may only be used once per session.&#125;&#125; |
}

			SKILLS
?{Which Skill?|
Acrobatics (Agility),
/me @{selected|token_name} makes an Acrobatics Test: [[(@{selected|agility} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Athletics (Strength),
/me @{selected|token_name} makes an Athletics Test: [[(@{selected|strength} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Awareness (Perception),
/me @{selected|token_name} makes an Awareness Test: [[(@{selected|perception} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Charm (Fellowship),
/me @{selected|token_name} makes a Charm Test: [[(@{selected|fellowship} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Command (Fellowship),
/me @{selected|token_name} makes a Command Test: [[(@{selected|fellowship} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Deceive (Fellowship),
/me @{selected|token_name} makes a Deceive Test: [[(@{selected|fellowship} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Inquiry (Fellowship),
/me @{selected|token_name} makes an Inquiry Test: [[(@{selected|fellowship} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Interrogation (Willpower),
/me @{selected|token_name} makes an Interrogation Test: [[(@{selected|willpower} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Linguistics (Intelligence),
/me @{selected|token_name} makes a Linguistics (?{What Language?&#124;Low Gothic&#125;) Test: [[(@{selected|intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Logic (Intelligence),
/me @{selected|token_name} makes a Logic Test: [[(@{selected|intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Lore (Intelligence),
/me @{selected|token_name} makes a ?{What Kind?&#124;Common&#124;Scholastic&#124;Forbidden&#125; Lore (?{Which Lore?&#125;) Test: [[(@{selected|intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Medicae (Intelligence),
/me @{selected|token_name} makes a Medicae Test: [[(@{selected|intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Navigate (Intelligence),
/me @{selected|token_name} makes a Navigate (?{Which Navigate?&#124;Surface&#124;Stellar&#124;Warp&#125;) Test: [[(@{selected|intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Operate (Agility),
/me @{selected|token_name} makes an Operate (?{Which Operate?&#124;Surface&#124;Aeronautica&#124;Voidship&#125;) Test: [[(@{selected|agility} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Psyniscience (Perception),
/me @{selected|token_name} makes a Psyniscience Test: [[(@{selected|perception} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Scrutiny (Perception),
/me @{selected|token_name} makes a Scrutiny Test: [[(@{selected|perception} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Security (Intelligence),
/me @{selected|token_name} makes a Security Test: [[(@{selected|intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Sleight of Hand (Agility),
/me @{selected|token_name} makes a Sleight of Hand Test: [[(@{selected|agility} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Stealth (Agility),
/me @{selected|token_name} makes a Stealth Test: [[(@{selected|agility} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Survival (Perception),
/me @{selected|token_name} makes a Survival Test: [[(@{selected|perception} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Tech-Use (Intelligence),
/me @{selected|token_name} makes a Tech-Use Test: [[(@{selected|Intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Trade (Intelligence),
/me @{selected|token_name} makes a Trade (?{Which Trade?&#125;) Test: [[(@{selected|intelligence} + ?{Skill Bonus?&#124;0&#124;-20&#124;10&#124;20&#124;30&#125; + ?{modifiers&#124;0&#125; - 1d100)/10]] Degrees of Success! |
}

			ACTION:MELEE

?{Which Melee Action?|
Standard Attack (Half),
/me @{selected|token_name} makes a ``Standard Melee Attack`` on @{target|token_name} and scores [[(@{selected|weaponskill} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (including the normal +10 for Standard Attacks) |
Charge Attack (Full), 
/me @{selected|token_name} makes a thunderous ``Charge Attack`` at @{target|token_name} and scores [[(@{selected|weaponskill} + 20 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! You must move a minimum of 4 meters and a maximum of [[@{selected|agility-bonus}*3]] meters to make a charge. |
All-Out Attack (Full),
/me @{selected|token_name} makes an ``All Out Attack`` on @{target|token_name} and scores [[(@{selected|weaponskill} + 30 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! Until his next turn @{selected|token_name} cannot make any reactions. |
Swift Attack (Half),
/me @{selected|token_name} makes a ``Swift Attack`` on @{target|token_name} and scores [[floor(((@{selected|weaponskill} + ?{modifier&#124;0&#125; - 1d100)/10)/2+1)]] Hit(s) (You may score up to [[floor(@{selected|weaponskill}/10)]] hits with Swift Attack) |
Lightning Attack (Half),
/me @{selected|token_name} makes a ``Lightning Attack`` on @{target|token_name} and scores [[floor((@{selected|weaponskill} - 10 + ?{modifier&#124;0&#125; - 1d100)/10)+1)]] Hit(s)! (including the normal -10 for Lightning Attack) (You may score up to [[floor(@{selected|weaponskill}/10)]] hits with Lightning Attack) |
Aim (Half),
/me @{selected|token_name} makes a ``Half Action Aim`` in melee&#44; he gains +10 to his next Melee Attack against @{target|token_name}. | 
Aim (Full),
/me @{selected|token_name} makes a ``Full Action Aim`` in melee&#44; he gains +20 to his next Melee Attack against @{target|token_name}. |
Called Shot (Full),
/me @{selected|token_name} makes a ``Called Shot`` at @{target|token_name}'s ``?{Location?&#124;Head&#124;Body&#124;Right Arm&#124;Left Arm&#124;Right Leg&#124;Left Leg&#125;`` and scores [[(@{selected|weaponskill} - 20 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (including the normal -20 for Called Shots) |
Defensive Stance (Full)
/me @{selected|token_name} takes the ``Defensive Stance`` action. Until the start of his next turn&#44; @{selected|token_name} gains one additional Reaction&#44; and all opponents suffer -20 to WS Tests against him. |
Disengage (Full),
/me @{selected|token_name} takes the ``Disengage`` action. He may move up to [[floor(@{selected|agility}/10)]] meters away. Opponents do not get a free attack against him for this movement. |
Feint (Half), 
/me @{selected|token_name} makes a ``Feint`` against @{target|token_name} and scores [[(@{selected|weaponskill} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success vs @{target|token_name}'s [[(@{target|weaponskill} + ?{opponent modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on the Opposed Weapon Skill Test. On a success&#44; @{selected|token_name}'s next ``Standard Melee Attack`` cannot be evaded. |
Guarded Action (Half),
/me @{selected|token_name} makes a ``Guarded Action``: until the beginning of his next turn&#44; he suffers -10 to WS but gains a +10 bonus to Dodge or Parry. |
Knock Down (Half),
/me @{selected|token_name} attempts to ``Knock Down`` @{target|token_name} and scores [[(@{selected|strength} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success vs @{target|token_name}'s [[(@{target|strength} + ?{opponent modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on the Opposed Strength Test. If @{selected|token_name} is using this as part of a ``Charge`` or ``Half Move`` Action&#44; he gains a +10 bonus. If @{selected|token_name} wins&#44; @{target|token_name} is knocked prone. If @{selected|token_name} succeeds by 2 or more Degrees of Success&#44; @{target|token_name} takes [[1d5 - 3 + @{selected|strengthbonus}]] Impact Damage and 1 Level of Fatigue. If @{target|token_name} wins by 2 or more Degrees of Success&#44; @{selected|token_name} is knocked prone instead. |
Maneuver (Half),
/me @{selected|token_name} attempts to force @{target|token_name} to ``Maneuver`` and scores [[(@{selected|weaponskill} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success vs @{target|token_name}'s [[(@{target|weaponskill} + ?{opponent modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on the Opposed Weapon Skill Test. On a success&#44; @{selected|token_name} moves @{target|token_name} [[1]] Meter in the direction of his choice. |
Stun (Full),
/me @{selected|token_name} attempts to ``Stun`` @{target|token_name} and scores [[(@{selected|weaponskill} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on @{target|token_name}'s [[1t[Hitzone]]]! On a success&#44; compare [[1d10 + @{selected|strengthbonus}]] to [[@{target|toughnessbonus}]] + AP on the location hit. If it is equal or higher&#44; @{target|token_name} is stunned for a number of rounds equal to the difference and gains 1 Level of Fatigue.|
}

			ACTION:RANGED

?{Which Ranged Action?|
Standard,
/me @{selected|token_name} makes a ``Standard Ranged Attack`` on @{target|token_name} [[(@{selected|ballisticskill} + 10 + ?{modifier&#124;0&#125; - 1d100cf>96cf=100)/10]] Degree(s) of Success! (the +10 bonus to Ballistic Skill is already accounted for). If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. |
Semi Auto,
/me @{selected|token_name} makes a ``Semi-Auto Attack`` on @{target|token_name} [[floor(((@{selected|ballisticskill} + ?{modifier&#124;0&#125; - 1d100cf>95cf=100)/10)/2)+1)]] Hit(s). If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. |
Full Auto,
/me @{selected|token_name} makes a ``Full Auto Attack`` on @{target|token_name} and scores [[floor((@{selected|BallisticSkill} - 10 + ?{modifier&#124;0&#125; - 1d100cf>94cf=100)/10)+1)]] Hit(s)! (The -10 penalty to Ballistic Skill is already accounted for) If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. |
Suppressing Fire,
/me @{selected|token_name} lays down ``Suppressing Fire`` in a 30° arc (if Semi) or 45° arc (if Full) or other suitable area and makes a Semi or Full-Auto attack at -20&#44; regardless of whether you hit or not&#44; the target of your Suppression must make a -10 Pinning Test (if you fired on Semi-Auto) or a -20 Pinning Test (if you fired on Full-Auto). |
Aim (Half),
/me @{selected|token_name} makes a ``Half Action Aim``. He gains +10 to his next Ranged Attack against @{target|token_name}. | 
Aim (Full),
/me @{selected|token_name} makes a ``Full Action Aim``. He gains +20 to his next Ranged Attack against @{target|token_name}. |
Brace Weapon (Half),
/me @{selected|token_name} braces his heavy weapon. This weapon cannot be moved without losing the benefits of Bracing&#44; but it can pivot up to 45° (or more). Unbraced Heavy Weapons suffer a -30 to Ballistic Skill. |
Called Shot (Full),
/me @{selected|token_name} makes a ``Called Shot`` at @{target|token_name}'s ``?{Location?&#124;Head&#124;Body&#124;Right Arm&#124;Left Arm&#124;Right Leg&#124;Left Leg&#125;`` and scores [[(@{selected|ballisticskill} - 20 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (including the normal -20 for Called Shots) |
Overwatch (Full),
/me @{selected|token_name} establishes ``Overwatch`` in a 45° arc or other suitable area&#44; then specifies Single&#44; Semi&#44; or Full&#44; along with his chosen conditions. Each time the condition is met before the start of @{selected|token_name}'s next turn&#44; he may execute the specific attack. Even if this attack does not succeed&#44; the target(s) of the attack must make a +0 Pinning Test. If @{selected|token_name} performs any other actions&#44; his overwatch immediately ends. | 
Unjam (Full),
/me @{selected|token_name}'s weapon is jammed! He scored [[(@{selected|ballisticskill} - 1d100)/10]] Degree(s) of Success to unjam it. 
}

			TEST:FATIGUED
?{Which Characteristic?|
Weapon Skill,
/me @{selected|token_name} makes a Weapon Skill Test while fatigued and scores [[(floor(@{selected|Weaponskill}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Ballistic Skill,
/me @{selected|token_name} makes a Ballistic Skill Test while fatigued and scores [[(floor(@{selected|ballisticskill}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Strength,
/me @{selected|token_name} makes a Strength Test while fatigued and scores [[(floor(@{selected|strength}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Toughness,
/me @{selected|token_name} makes a Toughness Test while fatigued and scores [[(floor(@{selected|toughness}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Agility,
/me @{selected|token_name} makes an Agility Test while fatigued and scores [[(floor(@{selected|agility}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Intelligence,
/me @{selected|token_name} makes an Intelligence Test while fatigued and scores [[(floor(@{selected|intelligence}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Perception,
/me @{selected|token_name} makes a Perception Test while fatigued and scores [[(floor(@{selected|perception}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Willpower,
/me @{selected|token_name} makes a Willpower Test while fatigued and scores [[(floor(@{selected|willpower}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
Fellowship,
/me @{selected|token_name} makes a Fellowship Test while fatigued and scores [[(floor(@{selected|fellowship}/2) + ?{modifiers&#124;0&#125; - 1d100)/10]] Degree(s) of Success |
}
AE 100 MACROS

?{Which Ranged Action?|
Standard,
/me @{selected|token_name} makes a ``Standard Ranged Attack`` on @{target|token_name} [[(@{selected|ballisticskill} + 10 + ?{modifier&#124;0&#125; - 1d100cf>96cf=100)/10]] Degree(s) of Success! (the +10 bonus to Ballistic Skill is already accounted for). If your result is in red&#44; your weapon has jammed&#44; unless it is Reliable. |
Aim (Half),
/me @{selected|token_name} makes a ``Half Action Aim``. He gains +10 to his next Ranged Attack against @{target|token_name}. | 
Aim (Full),
/me @{selected|token_name} makes a ``Full Action Aim``. He gains +20 to his next Ranged Attack against @{target|token_name}. |
Called Shot (Full),
/me @{selected|token_name} makes a ``Called Shot`` at @{target|token_name}'s ``?{Location?&#124;Head&#124;Body&#124;Right Arm&#124;Left Arm&#124;Right Leg&#124;Left Leg&#125;`` and scores [[(@{selected|ballisticskill} - 20 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! (including the normal -20 for Called Shots) |
Overwatch (Full),
/me @{selected|token_name} establishes ``Overwatch`` in a 45° arc or other suitable area&#44; then specifies Single&#44; Semi&#44; or Full&#44; along with his chosen conditions. Each time the condition is met before the start of @{selected|token_name}'s next turn&#44; he may execute the specific attack. Even if this attack does not succeed&#44; the target(s) of the attack must make a +0 Pinning Test. If @{selected|token_name} performs any other actions&#44; his overwatch immediately ends. | 
}


			MAGICAL CHARACTERISTICS

?{Which Action? |
Normal Casting,
?{Which Characteristic? &#124;
Abjuration&#44;
/me @{selected|token_name} makes an Abjuration Spell Focus Test and scores [[(@{selected|abjuration} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; 
Conjuration&#44;
/me @{selected|token_name} makes a Conjuration Spell Focus Test and scores [[(@{selected|conjuration} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; 
Divination&#44;
/me @{selected|token_name} makes a Divination Spell Focus Test and scores [[(@{selected|divination} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; 
Enchantment&#44;
/me @{selected|token_name} makes an Enchantment Spell Focus Test and scores [[(@{selected|enchantment} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; 
Evocation&#44;
/me @{selected|token_name} makes an Evocation Spell Focus Test and scores [[(@{selected|evocation} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; 
Illusion&#44;
/me @{selected|token_name} makes an Illusion Spell Focus Test and scores [[(@{selected|illusion} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; 
Necromancy&#44;
/me @{selected|token_name} makes a Necromancy Spell Focus Test and scores [[(@{selected|necromancy} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; 
Transmutation&#44;
/me @{selected|token_name} makes a Transmutation Spell Focus Test and scores [[(@{selected|transmutation} + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has triggered Arcanophysical Feedback. &#124; &#125; |
Reckless Casting,
?{Which Characteristic? &#124;
Abjuration&#44;
/me @{selected|token_name} makes a Reckless Abjuration Spell Focus Test and scores [[(@{selected|abjuration} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124; 
Conjuration&#44;
/me @{selected|token_name} makes a Reckless Conjuration Spell Focus Test and scores [[(@{selected|conjuration} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124; 
Divination&#44;
/me @{selected|token_name} makes a Reckless Divination Spell Focus Test and scores [[(@{selected|divination} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124;  
Enchantment&#44;
/me @{selected|token_name} makes a Reckless Enchantment Spell Focus Test and scores [[(@{selected|enchantment} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124; 
Evocation&#44;
/me @{selected|token_name} makes a Reckless Evocation Spell Focus Test and scores [[(@{selected|evocation} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124;  
Illusion&#44;
/me @{selected|token_name} makes a Reckless Illusion Spell Focus Test and scores [[(@{selected|illusion} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124; 
Necromancy&#44;
/me @{selected|token_name} makes a Reckless Necromancy Spell Focus Test and scores [[(@{selected|necromancy} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124; 
Transmutation&#44;
/me @{selected|token_name} makes a Reckless Transmutation Spell Focus Test and scores [[(@{selected|transmutation} + (?{Caster Level Increase (Up to 2)&amp;#124;1&amp;#125; * 5) + ?{modifier&amp;#124;0&amp;#125; - 1d100cf=11cf=22cf=33cf=44cf=55cf=66cf=77cf=88cf=99)/10]] Degree(s) of Success! 
/me If the result is in red&amp;#44; @{selected|token_name} has avoided triggering Arcanophysical Feedback. &#124; &#125; |
}

MOUNTED ACTIONS

?{Which Action?|
Canter (H/F),
/me @{selected|token_name} moves up to [[@{selected|HalfMove}]] meters as a half action or up to [[@{selected|FullMove}]] meters as a full action.  |
Crushing Charge (F),
/me @{target|Riding Character?|token_name} spurs @{selected|token_name} into a sprint&#44; maneuvering @{selected|token_name} into a charge! @{selected|token_name} may move up to [[@{selected|ChargeMove}]] meters (the last [[4]] of which must be in a straight line) and angles to attack&#44; scoring [[(@{target|Riding Character?|weaponskill} + 20 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success!
/me On a success&#44; this attack cannot be parried and the target must make an Opposed Strength Test against [[(@{selected|strength} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success or be knocked prone. |
Evasive Riding (F),
/me @{target|Riding Character?|token_name} rides @{selected|token_name} erratically&#44; attempting to avoid incoming attacks. @{target|Riding Character?|token_name} scores [[(@{target|Riding Character?|agility} - 20 + (@{selected|agility}) + ?{Ride Bonus?&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ride Test and @{selected|token_name} moves [[@{selected|FullMove}]] meters.
/me On a Success&#44; enemies suffer a -5 penalty to Ballistic Skill per degree of success to hit @{selected|token_name} or @{target|Riding Character?|token_name}&#44; but @{target|Riding Character?|token_name} suffers the same penalty to his own Ballistic Skill.
/me If @{target|Riding Character?|token_name} suffers [[@{target|Riding Character?|agility-bonus}]] Degrees of Failuire or more&#44; he is thrown from the saddle. |
Gallop (F),
/me @{target|Riding Character?|token_name} pushes @{selected|token_name} to its full speed. @{target|Riding Character?|token_name} scores [[(@{target|Riding Character?|agility} - 10 + ?{Ride Bonus?&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ride Test and @{selected|token_name} makes a Run move&#44; moving up to [[@{selected|RunMove}]] meters (Which it can double if it has the Sprint Talent).
/me If @{target|Riding Character?|token_name} suffers [[@{target|Riding Character?|agility-bonus}]] Degrees of Failuire or more&#44; he is thrown from the saddle but @{selected|token_name} keeps on running. |
Mount/Dismount (F),
/me @{target|Riding Character?|token_name} attempts to mount or dismount @{selected|token_name}. This does not require a test unless it is during a stressful situation&#44; in which case&#44; @{target|Riding Character?|token_name} scores [[(@{target|Riding Character?|fellowship} + 20 + ?{Handle Animal Bonus?&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] degrees of success!
/me If @{target|Riding Character?|token_name} suffers [[@{target|Riding Character?|agility-bonus}]] Degrees of Failuire or more&#44; he is thrown from the saddle. |
Rearing Strike (H),
/me @{target|Riding Character?|token_name} incites @{selected|token_name} to attack! @{target|Riding Character?|token_name} scores [[(@{target|Riding Character?|agility} + 20 + (@{selected|weaponskill}) + ?{Ride Bonus?&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] degrees of success!
/me On a success&#44; @{Selected|Token_name} inflicts one hit upon the target. |
Sidestep (R),
/me @{target|Riding Character?|Token_name} attempts to avoid an attack against himself or @{selected|token_name}. @{target|Riding Character?|token_name} scores [[(@{target|Riding Character?|agility} - 40 + ?{Ride Bonus?&#124;0&#125; + (@{selected|agility}) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success!
/me On a success&#44; both @{target|Riding Character?|token_name} and @{selected|token_name} avoid [[1]] hit for every Degree of Success.
/me If @{target|Riding Character?|token_name} suffers [[@{target|Riding Character?|agility-bonus}]] Degrees of Failuire or more&#44; he is thrown from the saddle. |
Soaring Leap (F),
/me @{target|Riding Character?|token_name} motivates @{selected|token_name} to make a sailing leap. @{target|Riding Character?|token_name} scores  [[(@{target|Riding Character?|agility} - 20 + ?{Ride Bonus?&#124;0&#125; + (@{selected|agility}) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success!
/me On a success&#44; @{selected|token_name} moves [[@{selected|RunMove}]] meters towards the obstacle and leaps [[@{selected|strengthbonus}]] meters plus [[1]] for every degree of success&#44; @{selected|token_name} achieves a maximum height of one-quarter horizontal distance during this leap.
/me If @{target|Riding Character?|token_name} suffers [[@{target|Riding Character?|agility-bonus}]] Degrees of Failuire or more&#44; he is thrown from the saddle&#44; and @{selected|token_name} does not jump. |
Strike and Fade (F),
/me @{target|Riding Character?|token_name} and @{selected|token_name} swing close to an enemy to attack before peeling off. @{selected|token_name} moves up to [[@{selected|HalfMove}]] meters to an enemy and @{target|Riding Character?|token_name} scores [[(@{target|Riding Character?|weaponskill} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on the attack!
/me On a success&#44; @{target|Riding Character?|token_name} scores one hit with an appropriate melee weapon and @{selected|token_name} may move up to [[@{selected|HalfMove}]] meters away. If the attack hit&#44; the enemy does not get a free attack. |
Thrown From the Saddle,
/me If @{target|Riding Character?|token_name} is thrown from the saddle&#44; he suffers [[1d10+1d5]] damage that ignores armor but not toughness.
/me If @{target|Riding Character?|token_name} fell as a result of a failed Ride test&#44; he suffers [[1d10]] plus the Degrees of Failure damage that ignores armor but not toughness. |
Crushed,
/me If @{target|Riding Character?|token_name} is thrown from the saddle at the same time @{selected|token_name} collapses for any reason&#44; @{target|Riding Character?|token_name} must make an Agility Test to avoid being pinned underneath it. @{target|Riding Character?|token_name} scores [[(@{target|Riding Character?|agility} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success.
/me On a failure&#44; @{target|Riding Character?|token_name} suffers [[1d10]] plus Degrees of Failure Impact damage and gains [[1d5]] Levels of Fatigue. |
Free Yourself,
/me @{target|Riding Character?|token_name} is attempting to free himself from beneath @{selected|token_name}. He scores [[(@{target|Riding Character?|strength} - (@{selected|size}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success.
}
		FORMATION MACROS

		UNIT COMMANDS

?{Which Command? |
Volley Fire,
/me @{target|Which Unit|character_name} attacks the enemy at range. It scores [[(@{target|Which Unit|ballisticskill} + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; plus an extra hit per [[2]] degrees of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). |
Close Combat Attack,
/me @{target|Which Unit|character_name} attacks the enemy in melee. It scores [[(@{target|Which Unit|weaponskill} + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; plus an extra hit per [[2]] degrees of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). |
Charge!,
/me @{target|Which Unit|character_name} charges in to attack the enemy. It scores [[(@{target|Which Unit|weaponskill} + 10 + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}*3]] meters and hit once per degree of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). |
Suppressing Fire,
/me @{target|Which Unit|character_name} suppresses the enemy. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} forces a single enemy per degree of success to make a Pinning Test with a -[[?{Unit Size?&#125;*5]] penalty. For every three degrees of success&#44; it also inflicts one hit. |
Overwatch,
/me @{target|Which Unit|character_name} fires on an enemy in the kill-zone. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; inflicting one additional hit per [[2]] degrees of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). |
Scatter,
/me @{target|Which Unit|character_name} gets the hell out of the way. It scores [[(@{target|Which Unit|agility} + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Agility Test.
/me On a success&#44; each member of @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}]] meters. For every degree of success&#44; reduce the number of members of @{target|Which Unit|character_name} slain by attacks with the spray or blast quality.  |
(M) Break Test,
/me @{target|Which Unit|character_name} is wavering under fire after losing [[?{How many dead?&#124;1&#125;]] members of the squad! @{Selected|token_name} must hold them together! He scores [[(@{selected|fellowship} + 20 - (?{How many dead?&#125;*5) + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me If he fails&#44; each member of @{target|Which Unit|character_name} flees at top speed from the source of the danger. If they are unable&#44; they may only take half actions and suffer a -20 to all tests. |
(M) Get Back Here (Command),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|fellowship} -20 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me On a success&#44; he successfully reforms the unit with up to [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
(M) Get Back Here (Intimidate),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|strength} -20 + ?{Intimidate Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Intimidate Test.
/me On a success&#44; he successfully reforms the unit with up to [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
}

		UNIT MORALE

?{Which Test? |
Break Test,
/me @{target|Which Unit|character_name} is wavering under fire after losing ?{How many dead?&#125; members of the squad! @{Selected|token_name} must hold them together! He scores [[(@{selected|fellowship} + 20 - (?{How many dead?&#125;*5) + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me If he fails&#44; each member of @{target|Which Unit|character_name} flees at top speed from the source of the danger. If they are unable&#44; they may only take half actions and suffer a -20 to all tests. |
Get Back Here (Command),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|fellowship} -20 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
Get Back Here (Intimidate),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|strength} -20 + ?{Intimidate Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Intimidate Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
}


		COMBINED FORMATION ORDERS

?{Which Type? |
Regular Commands,
?{Which Command? &#124;
Volley Fire&#44;
/me @{target|Which Unit|character_name} attacks the enemy at range. It scores [[(@{target|Which Unit|ballisticskill} + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once per degree of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). &#124;
Close Combat Attack&#44;
/me @{target|Which Unit|character_name} attacks the enemy in melee. It scores [[(@{target|Which Unit|weaponskill} + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once per degree of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). &#124;
Charge!&#44;
/me @{target|Which Unit|character_name} charges in to attack the enemy. It scores [[(@{target|Which Unit|weaponskill} + 10 + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}*3]] meters and hit once per degree of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). &#124;
Suppressing Fire&#44;
/me @{target|Which Unit|character_name} suppresses the enemy. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} forces a single enemy per degree of success to make a Pinning Test with a -[[(@{target|Which Unit|unit|current}*5)]] penalty. For every three degrees of success&#44; it also inflicts one hit. &#124;
Overwatch&#44;
/me @{target|Which Unit|character_name} fires on an enemy in the kill-zone. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; inflicting one additional hit per [[2]] degrees of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). &#124;
Scatter&#44; 
/me @{target|Which Unit|character_name} gets the hell out of the way. It scores [[(@{target|Which Unit|agility} + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Agility Test.
/me On a success&#44; each member of @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}]] meters. For every degree of success&#44; reduce the number of members of @{target|Which Unit|character_name} slain by attacks with the spray or blast quality. &#124; &#125; |
}


Morale Commands,
?{Which Test? &#124;
Break Test&#44; 
/me @{target|Which Unit|character_name} is wavering under fire after losing ?{How many dead?&#125; members of the squad! @{Selected|token_name} must hold them together! He scores [[(@{selected|fellowship} + 20 - (?{How many dead?&#125;*5) + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me If he fails&#44; each member of @{target|Which Unit|character_name} flees at top speed from the source of the danger. If they are unable&#44; they may only take half actions and suffer a -20 to all tests. &#124;
Get Back Here (Command)&#44;
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|fellowship} -20 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! &#124;
Get Back Here (Intimidate)&#44;
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|strength} -20 + ?{Intimidate Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Intimidate Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! &#124; &#125; |
}
		FORMATION MACROS

		UNIT COMMANDS

?{Which Command? |
Volley Fire,
/me @{target|Which Unit|character_name} attacks the enemy at range. It scores [[(@{target|Which Unit|ballisticskill} + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; plus an extra hit per [[2]] degrees of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). |
Close Combat Attack,
/me @{target|Which Unit|character_name} attacks the enemy in melee. It scores [[(@{target|Which Unit|weaponskill} + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; plus an extra hit per [[2]] degrees of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). |
Charge!,
/me @{target|Which Unit|character_name} charges in to attack the enemy. It scores [[(@{target|Which Unit|weaponskill} + 10 + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}*3]] meters and hit once per degree of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). |
Suppressing Fire,
/me @{target|Which Unit|character_name} suppresses the enemy. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} forces a single enemy per degree of success to make a Pinning Test with a -[[?{Unit Size?&#125;*5]] penalty. For every three degrees of success&#44; it also inflicts one hit. |
Overwatch,
/me @{target|Which Unit|character_name} fires on an enemy in the kill-zone. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100cs=11cs=22cs=33cs=44cs=55cs=66cs=77cs=88cs=99)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; inflicting one additional hit per [[2]] degrees of success&#44; up to [[?{Unit Size?&#125;]] hits (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). |
Scatter,
/me @{target|Which Unit|character_name} gets the hell out of the way. It scores [[(@{target|Which Unit|agility} + (?{Unit Size?&#124;4&#125;*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Agility Test.
/me On a success&#44; each member of @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}]] meters. For every degree of success&#44; reduce the number of members of @{target|Which Unit|character_name} slain by attacks with the spray or blast quality.  |
(M) Break Test,
/me @{target|Which Unit|character_name} is wavering under fire after losing [[?{How many dead?&#124;1&#125;]] members of the squad! @{Selected|token_name} must hold them together! He scores [[(@{selected|fellowship} + 20 - (?{How many dead?&#125;*5) + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me If he fails&#44; each member of @{target|Which Unit|character_name} flees at top speed from the source of the danger. If they are unable&#44; they may only take half actions and suffer a -20 to all tests. |
(M) Get Back Here (Command),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|fellowship} -20 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me On a success&#44; he successfully reforms the unit with up to [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
(M) Get Back Here (Intimidate),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|strength} -20 + ?{Intimidate Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Intimidate Test.
/me On a success&#44; he successfully reforms the unit with up to [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
}

		UNIT MORALE

?{Which Test? |
Break Test,
/me @{target|Which Unit|character_name} is wavering under fire after losing ?{How many dead?&#125; members of the squad! @{Selected|token_name} must hold them together! He scores [[(@{selected|fellowship} + 20 - (?{How many dead?&#125;*5) + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me If he fails&#44; each member of @{target|Which Unit|character_name} flees at top speed from the source of the danger. If they are unable&#44; they may only take half actions and suffer a -20 to all tests. |
Get Back Here (Command),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|fellowship} -20 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
Get Back Here (Intimidate),
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|strength} -20 + ?{Intimidate Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Intimidate Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! |
}


		COMBINED FORMATION ORDERS

?{Which Type? |
Regular Commands,
?{Which Command? &#124;
Volley Fire&#44;
/me @{target|Which Unit|character_name} attacks the enemy at range. It scores [[(@{target|Which Unit|ballisticskill} + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once per degree of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). &#124;
Close Combat Attack&#44;
/me @{target|Which Unit|character_name} attacks the enemy in melee. It scores [[(@{target|Which Unit|weaponskill} + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once per degree of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). &#124;
Charge!&#44;
/me @{target|Which Unit|character_name} charges in to attack the enemy. It scores [[(@{target|Which Unit|weaponskill} + 10 + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Weapon Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}*3]] meters and hit once per degree of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are engaged in melee). &#124;
Suppressing Fire&#44;
/me @{target|Which Unit|character_name} suppresses the enemy. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} forces a single enemy per degree of success to make a Pinning Test with a -[[(@{target|Which Unit|unit|current}*5)]] penalty. For every three degrees of success&#44; it also inflicts one hit. &#124;
Overwatch&#44;
/me @{target|Which Unit|character_name} fires on an enemy in the kill-zone. It scores [[(@{target|Which Unit|ballisticskill} - 10 + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Ballistic Skill Test.
/me On a success&#44; @{target|Which Unit|character_name} hits once&#44; inflicting one additional hit per [[2]] degrees of success&#44; up to [[@{target|Which Unit|unit|current}]] hit (as long as enough members of @{target|Which Unit|character_name} are within range and line of sight). &#124;
Scatter&#44; 
/me @{target|Which Unit|character_name} gets the hell out of the way. It scores [[(@{target|Which Unit|agility} + (@{target|Which Unit|unit|current}*5) + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Agility Test.
/me On a success&#44; each member of @{target|Which Unit|character_name} may move up to [[@{target|Which Unit|agility-bonus}]] meters. For every degree of success&#44; reduce the number of members of @{target|Which Unit|character_name} slain by attacks with the spray or blast quality. &#124; &#125; |
}


Morale Commands,
?{Which Test? &#124;
Break Test&#44; 
/me @{target|Which Unit|character_name} is wavering under fire after losing ?{How many dead?&#125; members of the squad! @{Selected|token_name} must hold them together! He scores [[(@{selected|fellowship} + 20 - (?{How many dead?&#125;*5) + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me If he fails&#44; each member of @{target|Which Unit|character_name} flees at top speed from the source of the danger. If they are unable&#44; they may only take half actions and suffer a -20 to all tests. &#124;
Get Back Here (Command)&#44;
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|fellowship} -20 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Command Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! &#124;
Get Back Here (Intimidate)&#44;
/me @{selected|token_name} is trying to get his squad under control! He scores [[(@{selected|strength} -20 + ?{Intimidate Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success on this Intimidate Test.
/me On a success&#44; he successfully reforms the unit with [[floor(@{selected|fellowship}/10)]] members plus 1 per degree of success! &#124; &#125; |
}

VOIDCOMBAT:EXTENDED (PC) 

?{Which Action?|
Active Augury,
/me @{target|Which Character|token_name} is attempting to scan the area around the @{selected|token_name} with an Active Augury. He scores [[(@{target|Which Character|perception} + @{selected|shipdetection} + ?{Scrutiny Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Scrutiny Test.
/me On a success&#44; the scan reveals basic and important information about celestial bodies &#44; void phenomena&#44; and other ships with [[20]] VUs of the @{selected|token_name}. If there is a vessel on Silent Running in this area&#44; it is automatically detected. For each Degree of Success&#44; the range of the scan is extended [[5]] VUs. |
Aid the Machine Spirit,
/me @{target|Which Character|token_name} attempts to Aid the Machine Spirit&#44; he scores [[(@{target|Which Character|intelligence} + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; you may add +5 to your vessel's Maneuverability or Detection for the remainder of the turn. For every [[2]] Degrees of Success&#44; you may add an additional +5 to the same system. |
All power to Shields,
/me @{target|Which Character|token_name} attempts to reroute power to the void shields&#44; he scores [[(@{target|Which Character|intelligence} + ?{Tech-Use Modifier&#124;0&#125; - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} gains [[1]] extra void shield until the beginning of its next turn. For every [[3]] Degrees of Success, @{selected|token_name} gains [[1]] additional void shield&#44; up to a maximum of double its base.
/me Due to the taxing drain on the ship&#44; @{selected|token_name} suffers a [[-20]] penalty to all Augury&#44; Manuever&#44; and Shooting actions until the beginning of its next turn. |
Arm the Crew,
/me @{target|Which Character|token_name} organizes the arming of every crewmember on board. He scores [[(@{Target|Which Character|fellowship} - 10 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me Arming the crew takes [[1d5]] rounds&#44; minus 1 per degree of success and +1 per degree of failure. After the crew is armed&#44; the ship gains a +10 bonus on defending from boarders for the duration of the combat. However&#44; there is a reason the crew is not usually armed&#44; and the ship's mutiny threshhold is increased by 5. | 
Boarding Action,
/me @{target|Which Character|token_name} attempts to board an enemy vessel 1 VU. He scores [[(@{target|Which Character|Intelligence} - 20 + ?{Operate (Voidship)   Modifier&#124;0&#125; + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test. |
Boarding Action (Command Test),
/me The character has boarded the enemy vessel (or is defending his own!). He must make a Command test: [[(@{Target|Which Character|fellowship} + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. @{target|Which Character|token_name} gains a +10 bonus on this test for every 10 points of crew population he has over the enemy.|
Disinformation,
/me @{target|Which Character|token_name} attempts to spread Disinformation to the crew&#44; misrepresenting the actual goings-on outside the ship. He scores  [[(@{target|Which Character|fellowship} - 10 + ?{Deceive Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Deceive Test.
/me If he succeeds&#44; he can increase the Crew's Morale by 1d5 per Degree of Success&#44; up to its maximum for the duration of the combat. |
Divert Power,
/me @{target|Which Character|token_name} attempts to reroute nonessential power. He scores  [[(@{target|Which Character|Intelligence} + ?{Tech-Use  Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; unpower [[1]] component to provide power for [[1]] unpowered component. This new power lasts for [[1]] round&#44; plus [[1]] round for every [[3]] Degrees of Success. Failure by [[3]] or more degrees means that the target component overloads and becomes damaged&#44; or destroyed if it was already damaged. |
Emergency Repairs,
/me @{target|Which Character|token_name} attempts to organize and lead Emergency Repair Crews to damaged portions of the ships. He scores  [[(@{Target|Which Character|intelligence} - 10 + (@{selected|Combat Bridge}) + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a Success&#44; @{target|Which Character|token_name} and his repair crews restore one Unpowered&#44; Damaged&#44; or Depressurized component to working order. This repair take [[1d5]] turns&#44; minus 1 per Degree of Success. This action can remove only one condition at a time. |
Fight Fires,
/me @{target|Which Character|token_name} attempts to organize and lead firefighting teams into the blaze. He scores  [[(@{Target|Which Character|fellowship} - 10 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the firefighting teams successfully put out the fire within one turn. | 
Emergency Vent, 
/me @{target|Which Character|token_name} attempts to make an emergency venting action. He scores  [[(@{Target|Which Character|fellowship} - 10 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the crew of the component expose it to hard void. The ship suffers [[2d10]] Morale damage and the component is now depressurized. If the component was on fire&#44; the ship suffers [[1d5]] Crew Damage and the fire is now out. If the component was boarded&#44; the ship suffers [[1d5]] Crew Damage. If the component was neither&#44; the ship suffers [[1d10]] Crew Damage. | 
Flank Speed, 
/me @{target|Which Character|token_name} attempts to push the engines to their limit&#44; he scores [[(@{target|Which Character|intelligence} + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} may move [[1]] additional VU this turn&#44; plus [[1]] per degree of success.
/me Failure by [[2]] or more Degrees means the ship immediately suffers the Engines Crippled critical hit as the engines are strained too hard. | 
Focused Augury, 
/me @{target|Which Character|token_name} is attempting to scan a specific vessel. He scores [[(@{target|Which Character|perception} + @{selected|shipdetection} + ?{Scrutiny Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Scrutiny Test.
/me On a success&#44; the scan reveals all essential components except Augur Arrays and Void Shields on an enemy vessel. For each degree of success&#44; the character learns of more components. |
Hit and Run (Pilot),
/me @{target|Which Character|token_name} is attempting to hit and run! He scores [[(@{target|Which Character|Agility} + ?{Operate (Aeronautica) Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Aeronautica) Test. |
Hit and Run (Offense),
/me The character has boarded the enemy vessel. He must make a Command test: [[(@{Target|Which Character|fellowship} + 10 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (Defense),
/me The character is defending his vessel from boarders. He must make a Command test: [[(@{Target|Which Character|fellowship} + 10 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (damage),
/me The character has succeeded at a hit and run! He has his choice of doing [[1d5]] Crew Damage and [[1d5]] Morale damage&#44; [[1]] Hull Integrity per degree of success&#44; or his choice of two critical hits. |
Hold Fast!, 
/me @{target|Which Character|token_name} is attempting to inspire the crew! He scores [[(@{Target|Which Character|fellowship} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Fellowship Test. 
/me on a success&#44; he reverses the previous turn's damage to morale by [[1]]&#44; plus 1 for each degree of success. |
Jam Communications,
/me @{target|Which Character|token_name} attempts to jam enemy communications. He scores  [[(@{target|Which Character|Intelligence} + ?{Tech-Use  Modifier&#124;0&#125; -10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; an enemy ship within [[20]] VUs is unable to use communications for the next [[2d5]] turns. |
Lock on Target, 
/me @{target|Which Character|token_name} is attempting to Lock On Target. He scores [[(@{target|Which Character|perception} + @{selected|shipdetection} + ?{Scrutiny Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Scrutiny Test.
/me On a success&#44; the adds +5 to the Ballistic Skill of one component this turn. For every 2 degrees of success&#44; he may add an additional 5. |
Prepare to Maneuver,
/me @{target|Which Character|token_name} attempts to divert power to thrusters. He scores  [[(@{target|Which Character|Intelligence} + ?{Tech-Use  Modifier&#124;0&#125; - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; the ship gains +5 Maneuverability this turn. For every 2 Degrees of Success&#44; it gains an additional 5. This action cannot be combined with flank speed. |
Prepare to Repel Boarders!, 
/me @{target|Which Character|token_name} is organizing counter-boarders! He scores [[(@{Target|Which Character|fellowship} + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he adds +10 to any opposed Command Tests he performs against enemy boarders during subsequent turns. Each degree of success gives him a +5 bonus. The character must sacrifice his turn each round he wishes to maintain this bonus. |
Put Your Backs Into It! (Charm),
/me @{target|Which Character|token_name} is trying to get more out of the men! He scores [[(@{Target|Which Character|fellowship} + ?{Charm Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Charm Test.
/me On a success&#44; he may choose to add +5 to a Ballistic Skill Test&#44; an Emergency Repairs action&#44; or an attempt to put out a fire. For every 3 degrees of success&#44; he may add this bonus to another seperate action.  |
Put Your Backs Into It! (Intimidate),
/me @{target|Which Character|token_name} is trying to get more out of the men! He scores [[(@{Target|Which Character|strength} + ?{Intimidate Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Intimidate Test.
/me On a success&#44; he may choose to add +5 to a Ballistic Skill Test&#44; an Emergency Repairs action&#44; or an attempt to put out a fire. For every 3 degrees of success&#44; he may add this bonus to another seperate action.  |
Ramming Action, 
/me @{target|Which Character|token_name} attempts to Ram an enemy within 1 VU. He scores [[(@{target|Which Character|Intelligence} - 20 + ?{Operate (Voidship) Modifier&#124;0&#125; + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me If he succeeds&#44; the ships crash together. @{selected|token_name} does [[2d5+1d10+4+@{selected|shiparmor}]] damage. @{selected|token_name} suffers [[1d5]] damage plus the armor of the enemy ship.
/me On a failure&#44; the ramming ship suffers the same damage it did to the enemy. All damage dealt by ramming ignores armor.|
Ready Squadrons, 
/me @{target|Which Character|token_name} is attempting to scramble small craft! He scores [[(@{Target|Which Character|fellowship} + ?{Command Modifier&#124;0&#125; + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he automatically readies a number of small craft equal to the strength of the launch bay component being used. |
Reload Ordnance, 
/me @{target|Which Character|token_name} is attempting to reload ordnance! He scores [[(@{Target|Which Character|fellowship} + ?{Command Modifier&#124;0&#125; -10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he automatically rearms all empty launch tubes. They are ready to fire in the same turn. |
Silent Running, 
/me @{target|Which Character|token_name} attempts to maneuver while Silent Running. He scores [[(@{target|Which Character|Intelligence} + 10 + ?{Operate (Voidship) Modifier&#124;0&#125; + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me On a success&#44; the ship is not detected. |
Triage, 
/me @{target|Which Character|token_name} attempts to triage. He scores [[(@{target|Which Character|Intelligence} - 10 + (@{selected|Medicae Deck}) + ?{Medicae Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Medicae Test.
/me On a success&#44; he reverses 1 crew damage from the previous turn&#44; plus 1 per degree of success. |
}


EXTENDED:TYRANID

?{Which Action?|
Boarding Action,
/me @{target|Which Character|token_name} attempts to board an enemy vessel 1 VU. He scores [[(@{target|Which Character|Intelligence} - 20 + ?{Operate (Voidship) Modifier&#124;0&#125; + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success on this Operate (Voidship) Test. |
Emergency Repairs,
/me @{target|Which Character|token_name} attempts to organize and lead Emergency Repair Crews to damaged portions of the ships. He scores  [[(@{Target|Which Character|intelligence} - 10 + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a Success&#44; @{target|Which Character|token_name} and his repair crews restore one Unpowered&#44; Damaged&#44; or Depressurized component to working order. This repair take [[1d5]] turns&#44; minus 1 per Degree of Success. This action can remove only one condition at a time. |
Fight Fires,
/me @{target|Which Character|token_name} attempts to organize and lead firefighting teams into the blaze. He scores  [[(@{Target|Which Character|fellowship} - 10 + ?{Command Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the firefighting teams successfully put out the fire within one turn. | 
Flank Speed, 
/me @{target|Which Character|token_name} attempts to push the engines to their limit&#44; he scores [[(@{target|Which Character|intelligence} + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} may move [[1]] additional VU this turn&#44; plus [[1]] per degree of success.
/me Failure by [[2]] or more Degrees means the ship immediately suffers the Engines Crippled critical hit as the engines are strained too hard. | 
Hit and Run (Pilot),
/me @{target|Which Character|token_name} is attempting to hit and run! He scores [[(@{target|Which Character|Agility} + ?{Operate (Aeronautica) Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success on this Operate (Aeronautica) Test. |
Hit and Run (Command Test),
/me The character has boarded the enemy vessel (or is defending his own!). He must make a Command test: [[(@{Target|Which Character|fellowship} + 10 + ?{modifier&#124;0&#125; + @{selected|HAR-mod} - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (damage),
/me The character has succeeded at a hit and run! He has his choice of doing [[1d5]] Crew Damage and [[1d5]] Morale damage&#44; [[1]] Hull Integrity per degree of success&#44; or his choice of two critical hits. |
}

MANEUVER ACTIONS:TYRANID

?{Which Action?|
Adjust Bearing,
/me @{target|Which Character?|token_name} attempts to Adjust the ship's Bearing and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{Operate(Voidship) Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success!
/me On a success&#44; the ship may turn after moving 1 VU less than its speed. For every Degree of Success&#44; it may turn after moving 1 less VU. A ship must move at least 1 VU before turning. Once it has turned&#44; it must move its remaining distance. |
All Ahead Full,
/me @{target|Which Character?|token_name} attempts to move faster and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may increase the number of VUs it moves by 1. All shipboard firing suffers a [[-20]] penalty this turn. |
Burn Retros,
/me @{target|Which Character?|token_name} attempts to slow down or come to a stop and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{Operate(Voidship) Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 10 - (2d100kl1))/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may  decrease the number of VUs it moves by 1. It may also turn after moving one VU less than its speed per Degree of Success. If it would come to a stop it may turn in place. The ship suffers [[-20]] to all shipboard shooting this turn. |
Come to New Heading,
/me @{target|Which Character?|token_name} attempts to Come to a New Heading and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{Operate(Voidship) Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 10 - (2d100kl1))/10]] Degrees of Success! 
/me Success indicates that the ship may turn when it has moved half its speed&#44; then turn again once it has moved its full speed. This radical course correction imposes a [[-20]] penalty on Ballistic Skill Tests during this turn. |
Disengage,
/me @{target|Which Character?|token_name} attempts to Disengage and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{Operate(Voidship) Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success.
/me If the Degrees of Success are more than the amount of ships within 20 VUs&#44; the ship successfully disengages from combat&#44; and may not re-enter it. |
Evasive Maneuvers,
/me @{target|Which Character?|token_name} attempts Evasive Maneuvers and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} - 10 + ?{Operate(Voidship) Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success!
/me Each Degree of Success imposes a [[-10]] penalty to all shooting directed towards the @{selected|token_name}&#44; which suffers the same penalty until its next turn. |
}

EXTENDED:NECRON

?{Which Action?|
All power to Shields,
/me @{target|Which Character|token_name} attempts to reroute power to the void shields&#44; he scores [[(@{target|Which Character|intelligence} + ?{Tech-Use Modifier&#124;0&#125; - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} gains [[1]] extra void shield until the beginning of its next turn. For every [[3]] Degrees of Success, @{selected|token_name} gains [[1]] additional void shield&#44; up to a maximum of double its base.
/me Due to the taxing drain on the ship&#44; @{selected|token_name} suffers a [[-20]] penalty to all Augury&#44; Manuever&#44; and Shooting actions until the beginning of its next turn. |
Boarding Action,
/me @{target|Which Character|token_name} attempts to board an enemy vessel 1 VU. He scores [[(@{target|Which Character|Intelligence} - 20 + @{selected|Pilot-Mod} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test. |
Boarding Action (Command Test),
/me The character has boarded the enemy vessel (or is defending his own!). He must make a Command test: [[(@{Target|Which Character|fellowship} + @{selected|Command-Mod} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. @{target|Which Character|token_name} gains a +10 bonus on this test for every 10 points of crew population he has over the enemy.|
Divert Power,
/me @{target|Which Character|token_name} attempts to reroute nonessential power. He scores  [[(@{target|Which Character|Intelligence} + ?{Tech-Use  Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; unpower [[1]] component to provide power for [[1]] unpowered component. This new power lasts for [[1]] round&#44; plus [[1]] round for every [[3]] Degrees of Success. Failure by [[3]] or more degrees means that the target component overloads and becomes damaged&#44; or destroyed if it was already damaged. |
Flank Speed, 
/me @{target|Which Character|token_name} attempts to push the engines to their limit&#44; he scores [[(@{target|Which Character|intelligence} + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} may move [[1]] additional VU this turn&#44; plus [[1]] per degree of success.
/me Failure by [[2]] or more Degrees means the ship immediately suffers the Engines Crippled critical hit as the engines are strained too hard. | 
Hit and Run (Command Test),
/me The character has boarded the enemy vessel (or is defending his own!). He must make a Command test: [[(@{Target|Which Character|fellowship} + 10 + 30 + @{selected|Command-Mod} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (damage),
/me The character has succeeded at a hit and run! He has his choice of doing [[1d5]] Crew Damage and [[1d5]] Morale damage&#44; [[1]] Hull Integrity per degree of success&#44; or his choice of two critical hits. |
Jam Communications,
/me @{target|Which Character|token_name} attempts to jam enemy communications. He scores  [[(@{target|Which Character|Intelligence} + ?{Tech-Use  Modifier&#124;0&#125; -10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; an enemy ship within [[20]] VUs is unable to use communications for the next [[2d5]] turns. |
Lock on Target, 
/me @{target|Which Character|token_name} is attempting to Lock On Target. He scores [[(@{target|Which Character|perception} + @{selected|shipdetection} + ?{Scrutiny Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Scrutiny Test.
/me On a success&#44; the adds +5 to the Ballistic Skill of one component this turn. For every 2 degrees of success&#44; he may add an additional 5. |
Prepare to Maneuver,
/me @{target|Which Character|token_name} attempts to divert power to thrusters. He scores  [[(@{target|Which Character|Intelligence} + ?{Tech-Use  Modifier&#124;0&#125; - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; the ship gains +5 Maneuverability this turn. For every 2 Degrees of Success&#44; it gains an additional 5. This action cannot be combined with flank speed. |
Ramming Action, 
/me @{target|Which Character|token_name} attempts to Ram an enemy within 1 VU. He scores [[(@{target|Which Character|Intelligence} - 20 + @{selected|Pilot-Mod} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me If he succeeds&#44; the ships crash together. @{selected|token_name} does [[2d10+@{selected|shiparmor}]] damage. @{selected|token_name} suffers [[1d5]] damage plus the armor of the enemy ship.
/me On a failure&#44; the ramming ship suffers the same damage it did to the enemy. All damage dealt by ramming ignores armor.|
Silent Running, 
/me @{target|Which Character|token_name} attempts to maneuver while Silent Running. He scores [[(@{target|Which Character|Intelligence} + 10 + @{selected|Pilot-Mod} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me On a success&#44; the ship is not detected. |
}

MANEUVER:NECRON

?{Which Action?|
Adjust Bearing,
/me @{target|Which Character?|token_name} attempts to Adjust the ship's Bearing and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + @{Selected|Pilot-Mod} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success!
/me On a success&#44; the ship may turn after moving 1 VU less than its speed. For every Degree of Success&#44; it may turn after moving 1 less VU. A ship must move at least 1 VU before turning. Once it has turned&#44; it must move its remaining distance. |
All Ahead Full,
/me @{target|Which Character?|token_name} attempts to move faster and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may increase the number of VUs it moves by 1. All shipboard firing suffers a [[-20]] penalty this turn. |
Burn Retros,
/me @{target|Which Character?|token_name} attempts to slow down or come to a stop and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + @{Selected|Pilot-Mod} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may  decrease the number of VUs it moves by 1. It may also turn after moving one VU less than its speed per Degree of Success. If it would come to a stop it may turn in place. The ship suffers [[-20]] to all shipboard shooting this turn. |
Come to New Heading,
/me @{target|Which Character?|token_name} attempts to Come to a New Heading and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + @{Selected|Pilot-Mod} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me Success indicates that the ship may turn when it has moved half its speed&#44; then turn again once it has moved its full speed. This radical course correction imposes a [[-20]] penalty on Ballistic Skill Tests during this turn. |
Disengage,
/me @{target|Which Character?|token_name} attempts to Disengage and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} + @{Selected|Pilot-Mod} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success.
/me If the Degrees of Success are more than the amount of ships within 20 VUs&#44; the ship successfully disengages from combat&#44; and may not re-enter it. |
Evasive Maneuvers,
/me @{target|Which Character?|token_name} attempts Evasive Maneuvers and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} - 10 + @{Selected|Pilot-Mod} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success!
/me Each Degree of Success imposes a [[-10]] penalty to all shooting directed towards the @{selected|token_name}&#44; which suffers the same penalty until its next turn. |
Phase-Out,
/me @{target|Which Character?|token_name} attempts to move faster and scores [[(@{target|Which Character?|Intelligence} + @{selected|ShipManoeuvrability} - 20 + ?{Tech-Use Modifier&#124;0&#125; + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! 
/me On a success&#44; the Necron ship phases out and is gone. |
}
					VOID COMBAT WEAPON MACROS

		MACROBATTERY FORMULA

/me @{selected|token_name} scores [[?{# of hits|1}]] hits with its macrobatteries! It deals [[{(((?{# of hits}-?{# of enemy shields|1})*3) + ((?{# of hits}-?{# of enemy shields|1})d10) - (@{target|shiparmor})), 0d0}kh1]] damage to @{target|token_name}
/me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the damage by [[@{target|shiparmor}]] with its armor.
/me if this weapon dealt [[5]] or more hits, it scores a Critical Hit. It can hit a maximum of [[6]] times.


		MACROBATTERY SALVO FORMULA x2

/me @{selected|token_name} scores [[?{# of hits 1|1}]] hits with the first battery of macrocannons and [[?{# of hits 2|1}]] with the second! For [[{((((?{# of hits 1}+?{# of hits 2}-?{# of enemy shields|1})*4) + ((?{# of hits 1}+?{# of hits 2}-?{# of enemy shields|1})d10)) - (@{target|shiparmor})), 0d0}kh1]] damage!
/me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the amount of damage by [[@{target|shiparmor}]] with its armor.
/me if this weapon dealt [[4]] or more hits, it scores a Critical Hit. It can hit a maximum of [[8]] times and can only score one critical hit.

		MACROBATTERY SALVO FORMULA X3

/me @{selected|token_name} scores [[?{# of hits 1|1}]] hits with the first battery of macrocannons and [[?{# of hits 2|1}]] with the second and [[?{# of hits 3|1}]] with the third! For [[{((((?{# of hits 1}+?{# of hits 2}+?{# of hits 3}-?{# of enemy shields|1})*4) + ((?{# of hits 1}+?{# of hits 2}+?{# of hits 3}-?{# of enemy shields|1})d10)) - (@{target|shiparmor})), 0d0}kh1]] damage!
/me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the amount of damage by [[@{Target|shiparmor}]] with its armor.
/me if this weapon dealt [[4]] or more hits, it scores a Critical Hit. It can hit a maximum of [[12]] times and can only score one critical hit.

		LANCE FORMULA

/me @{selected|token_name} does [[1d10+4]] Damage to @{target|token_name}. This damage bypasses armor but not void shields.
/me If the attack roll with this weapon scored [[3]] or more Degrees of Success it deals a critical hit.


		NOVA CANNON

?{Which Action?|
Fire Nova Cannon,   
/me @{target|Firing Character|token_name} fires @{selected|token_name}'s Nova Cannon at a vessel at least 6 VU away and scores [[(@{target|Firing Character|ballisticskill} - 20 + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! 
/me For every degree of failure&#44; the Nova Cannon scatter 1 VU towards from the firer (if red) or away from the firer (if green). [[1d2]] 
/me On a Hit&#44; the Nova Cannon does [[1d5-?{target void shields?&#124;1&#125;]] hits. |
Nova Cannon Damage,
/me On a hit&#44; the Nova Cannon does [[(?{# of hits?&#125; * 5) + ((?{# of hits?&#125;)d5) + ((?{# of hits?&#125;)d5)]] Damage to all vessels within 1 VU. This damage ignores armor.
/me any die that is green scores a critical hit. |
}
			VOIDCOMBAT:NPC ACTIONS

		MANEUVER ACTIONS

?{Which Action?|
Maneuver Test,
/me @{selected|token_name} makes a maneuver test and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Adjust Bearing,
/me @{selected|token_name} attempts to Adjust the ship's Bearing and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success!
/me On a success&#44; the ship may turn after moving 1 VU less than its speed. For every Degree of Success&#44; it may turn after moving 1 less VU. A ship must move at least 1 VU before turning. Once it has turned&#44; it must move its remaining distance. |
All Ahead Full,
/me @{selected|token_name} attempts to move faster and scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may increase the number of VUs it moves by 1. All shipboard firing suffers a [[-20]] penalty this turn. |
Burn Retros,
/me @{selected|token_name} attempts to slow down or come to a stop and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may  decrease the number of VUs it moves by 1. It may also turn after moving one VU less than its speed per Degree of Success. If it would come to a stop it may turn in place. The ship suffers [[-20]] to all shipboard shooting this turn. |
Come to New Heading,
/me @{selected|token_name} attempts to Come to a New Heading and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me Success indicates that the ship may turn when it has moved half its speed&#44; then turn again once it has moved its full speed. This radical course correction imposes a [[-20]] penalty on Ballistic Skill Tests during this turn. |
Disengage,
/me @{selected|token_name} attempts to Disengage and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success.
/me If the Degrees of Success are more than the amount of ships within 20 VUs&#44; the ship successfully disengages from combat&#44; and may not re-enter it. |
Evasive Maneuvers,
/me @{selected|token_name} attempts Evasive Maneuvers and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success!
/me Each Degree of Success imposes a [[-10]] penalty to all shooting directed towards @{selected|token_name}&#44; which suffers the same penalty until its next turn. |
}		


		NPC COMBAT

?{Which Action?|
Initiative,
/me @{selected|token_name} rolls [[1d10+floor(@{selected|ShipDetection}/10) &{tracker&#125;]] for Initiative |
Fire Weapon,
/me @{selected|token_name} fires it's weapons at @{target|token_name}. [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! |
Turret Defense,
/me @{selected|token_name} defends with the turrets. [[(@{selected|shipcrewrating} + (@{selected|ShipTurretRating}*5) - (?{Enemy Fighters?&#124;0&#125;*10) - 1d100)/10)]] Degree(s) of Success! 
/me The turrets hit once&#44; plus once more for every [[2]] degrees of success. With each hit they take down [[1]] Torpedo or Squadron. |
Launch Voidcraft,
/me @{selected|token_name} launches its voidcraft. It can launch up to [[x]] total squadrons. |
Launch Torpedoes,
/me @{selected|token_name} launches torpedoes. It can launch up to [[x]] torpedoes. |
Critical Hit,
/me [[1t[VSCH]]] on @{target|token_name}'s [[1t[Random-Component]]] |
}


		VOIDCOMBAT:EXTENDED

?{Which Action?|
All power to Shields,
/me @{selected|token_name} attempts to reroute power to the void shields&#44; he scores [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} gains [[1]] extra void shield until the beginning of its next turn. For every [[3]] Degrees of Success, @{selected|token_name} gains [[1]] additional void shield&#44; up to a maximum of double its base.
/me Due to the taxing drain on the ship&#44; @{selected|token_name} suffers a [[-20]] penalty to all Augury&#44; Manuever&#44; and Shooting actions until the beginning of its next turn. |
Divert Power,
/me @{selected|token_name} attempts to reroute nonessential power. He scores  [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; unpower [[1]] component to provide power for [[1]] unpowered component. This new power lasts for [[1]] round&#44; plus [[1]] round for every [[3]] Degrees of Success. Failure by [[3]] or more degrees means that the target component overloads and becomes damaged&#44; or destroyed if it was already damaged. |
Emergency Repairs,
/me @{selected|token_name} attempts to organize and lead Emergency Repair Crews to damaged portions of the ships. He scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a Success&#44; @{selected|token_name} and his repair crews restore one Unpowered&#44; Damaged&#44; or Depressurized component to working order. This repair take [[1d5]] turns&#44; minus 1 per Degree of Success. This action can remove only one condition at a time. |
Fight Fires,
/me @{selected|token_name} attempts to organize and lead firefighting teams into the blaze. He scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the firefighting teams successfully put out the fire within one turn. | 
Emergency Vent, 
/me @{selected|token_name} attempts to make an emergency venting action. He scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the crew of the component expose it to hard void. The ship suffers [[2d10]] Morale damage and the component is now depressurized. If the component was on fire&#44; the ship suffers [[1d5]] Crew Damage and the fire is now out. If the component was boarded&#44; the ship suffers [[1d5]] Crew Damage. If the component was neither&#44; the ship suffers [[1d10]] Crew Damage. | 
Flank Speed, 
/me @{selected|token_name} attempts to push the engines to their limit&#44; he scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} may move [[1]] additional VU this turn&#44; plus [[1]] per degree of success.
/me Failure by [[2]] or more Degrees means the ship immediately suffers the Engines Crippled critical hit as the engines are strained too hard. | 
Hit and Run (Pilot),
/me @{selected|token_name} is attempting to hit and run! He scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Aeronautica) Test. |
Hit and Run (Attacking),
/me The character has boarded the enemy vessel. He must make a Command test: [[(@{selected|shipcrewrating} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (Defending),
/me The character is defending his vessel from boarders. He must make a Command test: [[(@{selected|shipcrewrating} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (damage),
/me The character has succeeded at a hit and run! He has his choice of doing [[1d5]] Crew Damage and [[1d5]] Morale damage&#44; [[1]] Hull Integrity per degree of success&#44; or his choice of two critical hits. |
Jam Communications,
/me @{selected|token_name} attempts to jam enemy communications. He scores  [[(@{selected|shipcrewrating} -10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; an enemy ship within [[20]] VUs is unable to use communications for the next [[2d5]] turns. |
Lock on Target, 
/me @{selected|token_name} is attempting to Lock On Target. He scores [[(@{selected|shipcrewrating} + @{selected|shipdetection} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Scrutiny Test.
/me On a success&#44; the adds +5 to the Ballistic Skill of one component this turn. For every 2 degrees of success&#44; he may add an additional 5. |
Prepare to Repel Boarders!, 
/me @{selected|token_name} is organizing counter-boarders! He scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he adds +10 to any opposed Command Tests he performs against enemy boarders during subsequent turns. Each degree of success gives him a +5 bonus. The character must sacrifice his turn each round he wishes to maintain this bonus. |
Ramming Action, 
/me @{selected|token_name} attempts to Ram an enemy within 1 VU. He scores [[(@{selected|shipcrewrating} - 20 + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me If he succeeds&#44; the ships crash together. Raiders or Transports do [[1d5+@{selected|shiparmor}]] damage. Cruisers do [[2d5+@{selected|shiparmor}]] damage. Larger ships do [[2d10+@{selected|shiparmor}]] damage. @{selected|token_name} suffers [[1d5]] damage plus the armor of the enemy ship.
/me On a failure&#44; the ramming ship suffers the same damage it did to the enemy. All damage dealt by ramming ignores armor.|
Ready Squadrons, 
/me @{selected|token_name} is attempting to scramble small craft! He scores [[(@{selected|shipcrewrating} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he automatically readies a number of small craft equal to the strength of the launch bay component being used. |
Reload Ordnance, 
/me @{selected|token_name} is attempting to reload ordnance! He scores [[(@{selected|shipcrewrating} -10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he automatically rearms all empty launch tubes. They are ready to fire in the same turn. |
Silent Running, 
/me @{selected|token_name} attempts to maneuver while Silent Running. He scores [[(@{selected|shipcrewrating} + 10 + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me On a success&#44; the ship is not detected. |
}
# TORPEDO MACROS
## TORPEDO GUIDANCE SYSTEM
    ```/me @{target|Firing Character|Token_Name} attempts to Guide the Torpedoes!  [[(@{target|Firing Character|Intelligence} + @{target|Firing Ship|ShipDetection} + ?{modifier|0} + ?{Tech-Use Modifier|0}- 1d100)/10]] Degree(s) of Success!```
    ```/me Success means the character can change the direction of the torpedoes by moving up to 45 degrees. For every degree of success, he can slow the Torpedoes by 1 VU.```		
## TORPEDO ATTACK
    `?{What Kind of Guidance System? |    Standard,    /me @{target|Firing Character|token_name} attempts to connect the Torpedoes. [[(@{target|Firing Character|ballisticskill} + @{selected|TorpedoStandard} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success!     /me On a success&#44; and for each degree of success&#44; a torpedo connects. |    Guided,    /me @{target|Firing Character|token_name} attempts to connect the Torpedoes. [[(@{target|Firing Character|ballisticskill} + @{selected|TorpedoGuided} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success!     /me On a success&#44; and for each degree of success&#44; a torpedo connects. |     Seeking,    /me @{target|Firing Character|token_name} attempts to connect the Torpedoes. [[(@{target|Firing Character|ballisticskill} + @{selected|TorpedoSeeking} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success!     /me On a success&#44; and for each degree of success&#44; a torpedo connects. |     Short-Burn,     /me @{target|Firing Character|token_name} attempts to connect the Torpedoes. [[(@{target|Firing Character|ballisticskill} + @{selected|TorpedoShort} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success!     /me On a success&#44; and for each degree of success&#44; a torpedo connects.    }`
## DAMAGE:TORPEDOES
    TORPEDO DAMAGE x6
    ```?{What Kind of Torpedo? |
    Plasma,
    /me The Torpedoes hit! they can deal up to an amount of hits equal to the Strength of the launcher that fired them.
    /me 1st Hit: [[{(((2d10r<3)+14) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 2nd Hit: [[{(((2d10r<3)+14) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 3rd Hit: [[{(((2d10r<3)+14) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 4th Hit: [[{(((2d10r<3)+14) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 5th Hit: [[{(((2d10r<3)+14) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 6th Hit: [[{(((2d10r<3)+14) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me if any of the hits are in green you have scored a critical hit. |
    Boarding,
    /me The Torpedoes hit! they can deal up to an amount of hits equal to the Strength of the launcher that fired them.
    /me 1st Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 2nd Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 3rd Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 4th Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 5th Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 6th Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me if any of the hits' damage exceeds the ship's armor (that is&#44; you deal at least 1 point of damage) it instead does no damage and immediately inflicts a Hit And Run attack.|
    Melta,
    /me The Torpedoes hit! they can deal up to an amount of hits equal to the Strength of the launcher that fired them.
    /me 1st Hit: [[{(((2d10r<4)+15) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 2nd Hit: [[{(((2d10r<4)+15) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 3rd Hit: [[{(((2d10r<4)+15) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 4th Hit: [[{(((2d10r<4)+15) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 5th Hit: [[{(((2d10r<4)+15) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me 6th Hit: [[{(((2d10r<4)+15) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
    /me if any of the hits deal damage&#44; it immediately begins a fire in addition to any other critical hits it may cause.|
    Virus,
    /me The Torpedoes hit! they can deal up to an amount of hits equal to the Strength of the launcher that fired them.
    /me 1st Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
    /me 2nd Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
    /me 3rd Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
    /me 4th Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
    /me 5th Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
    /me 6th Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
    /me if any of the hits' damage exceeds the ship's armor (that is&#44; you deal at least 1 point of damage) it instead does no damage and immediately inflicts Crew damage and Morale damage. A character aboard must make a -10 Command Test to halt the spread of the disease or the vessel will take this damage every turn.|
    Vortex,
    /me The Torpedoes hit! they can deal up to an amount of hits equal to the Strength of the launcher that fired them.
    /me 1st Hit: [[((2d10r<5)+5)]] damage plus [[1d5]] Morale Damage
    /me 2nd Hit: [[((2d10r<5)+5)]] damage plus [[1d5]] Morale Damage
    /me 3rd Hit: [[((2d10r<5)+5)]] damage plus [[1d5]] Morale Damage
    /me 4th Hit: [[((2d10r<5)+5)]] damage plus [[1d5]] Morale Damage
    /me 5th Hit: [[((2d10r<5)+5)]] damage plus [[1d5]] Morale Damage
    /me 6th Hit: [[((2d10r<5)+5)]] damage plus [[1d5]] Morale Damage
    /me if any of the hits are in green you have scored a critical hit. |
    Atomics,
    /me On a hit&#44; the Atomic weapons deal [[((?{# of hits?&#124;5&#125;) * 6) + ((?{# of hits?&#125;)d10)) - (@{target|shiparmor})]] damage to @{target|token_name}. @{target|token_name} also suffers [[1d10]] extra Crew Damage and [[1d10]] extra Morale damage.
    /me any die that is green scores a critical hit. |
    }```	
# TYRANID MACROS
## MANUEVER ACTIONS
        ```?{Which Action?|
        Adjust Bearing,
        /me @{selected|token_name} attempts to Adjust Bearing and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success!
        /me On a success&#44; the @{selected|token_name} may turn after moving 1 VU less than its speed. For every Degree of Success&#44; it may turn after moving 1 less VU. A ship must move at least 1 VU before turning. Once it has turned&#44; it must move its remaining distance. |
        All Ahead Full,
        /me @{selected|token_name} attempts to move faster and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success! 
        /me For each Degree of Success&#44; the ship may increase the number of VUs it moves by 1. All shipboard firing suffers a [[-20]] penalty this turn. |
        Burn Retros,
        /me @{selected|token_name} attempts to slow down or come to a stop and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - (2d100kl1))/10]] Degrees of Success! 
        /me For each Degree of Success&#44; the ship may  decrease the number of VUs it moves by 1. It may also turn after moving one VU less than its speed per Degree of Success. If it would come to a stop it may turn in place. The ship suffers [[-20]] to all shipboard shooting this turn. |
        Come to New Heading,
        /me @{selected|token_name} attempts to Come to a New Heading and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - (2d100kl1))/10]] Degrees of Success! 
        /me Success indicates that the ship may turn when it has moved half its speed&#44; then turn again once it has moved its full speed. This radical course correction imposes a [[-20]] penalty on Ballistic Skill Tests during this turn. |
        Evasive Maneuvers,
        /me @{selected|token_name} attempts Evasive Maneuvers and scores[[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - (2d100kl1))/10]] Degrees of Success!
        /me Each Degree of Success imposes a [[-10]] penalty to all shooting directed towards the @{selected|token_name}&#44; which suffers the same penalty until its next turn. |
        }```
## EXTENDED ACTIONS
    ```?{Which Action?|
    Boarding Action,
    /me @{selected|token_name} attempts to board an enemy vessel 1 VU. It scores [[(@{selected|shipcrewrating} - 20 + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - (2d100kl1))/10]] Degrees of Success. |
    Emergency Repairs,
    /me @{selected|token_name} attempts to heal itself. It scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success.
    /me On a Success&#44; @{selected|token_name} restore one Unpowered&#44; Damaged&#44; or Depressurized component to working order. This repair take [[1d5]] turns&#44; minus 1 per Degree of Success. This action can remove only one condition at a time. |
    Fight Fires,
    /me @{selected|token_name} attempts to put out one fire. It scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success.
    /me On a Success&#44; the firefighting teams successfully put out the fire within one turn. | 
    Flank Speed, 
    /me @{selected|token_name} attempts to push the engines to their limit&#44; he scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success
    /me On a success&#44; @{selected|token_name} may move [[1]] additional VU this turn&#44; plus [[1]] per degree of success.
    /me Failure by [[2]] or more Degrees means the ship immediately suffers the Engines Crippled critical hit as the engines are strained too hard. | 
    Hit and Run (Pilot),
    /me @{selected|token_name} is attempting to hit and run! He scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Aeronautica) Test. |
    Hit and Run (Attacking),
    /me The character has boarded the enemy vessel. He must make a Command test: [[(@{selected|shipcrewrating} + 10 + ?{modifier&#124;0&#125; + @{selected|HAR-mod} - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
    Hit and Run (Defending),
    /me The character is defending its vessel from boarders. He must make a Command test: [[(@{selected|shipcrewrating} + 10 + ?{modifier&#124;0&#125; + @{selected|HAR-mod} - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
    Hit and Run (damage),
    /me The character has succeeded at a hit and run! He has his choice of doing [[2d5]] Crew Damage and [[2d5]] Morale damage&#44; [[1]] Hull Integrity per degree of success&#44; or his choice of two critical hits. |
    }```
## COMBAT ACTIONS
    ```?{Which Action?|
    Initiative,
    /me @{selected|token_name} rolls [[1d10+floor(@{selected|ShipDetection}/10) &{tracker&#125;]] for Initiative |
    Fire Weapon,
    /me @{selected|token_name} fires its's weapons. [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! |
    Turret Defense,
    /me @{selected|token_name} defends with the turrets. [[(@{selected|shipcrewrating} + (@{selected|ShipTurretRating}*5) - (?{Enemy Fighters?&#124;0&#125;*10) - 1d100)/10)]] Degree(s) of Success! 
    /me The turrets hit once&#44; plus once more for every [[2]] degrees of success. With each hit they take down [[1]] Torpedo or Squadron. |
    Launch Voidcraft,
    /me @{selected|token_name} launches its voidcraft. It can launch up to [[x]] total squadrons. |
    Launch Torpedoes,
    /me @{selected|token_name} launches bio-torpedoes. It can launch up to [[x]] bio-torpedoes |
    Critical Hit,
    /me [[1t[VSCH]]] on @{target|token_name}'s [[1t[Random-Component]]] |
    }```
## DAMAGE:MASSIVE CLAWS
    ```/me @{selected|token_name} scores [[?{# of degrees of success|1}]] degrees of success with its Massive Claws! It deals [[((?{# of degrees of success})*3) + ((?{# of degrees of success})d5))]] damage to @{target|token_name}```
    ```/me if this weapon dealt [[4]] or more degrees of success, it scores a Critical Hit. It can attack up to [[4]] times. On a critical hit it does [[1d10]] damage, in addition to a critical effect.```
## DAMAGE:BIG MASSIVE CLAWS
    ```/me @{selected|token_name} scores [[?{# of degrees of success|1}]] degrees of success with its Massive Claws! It deals [[((?{# of degrees of success})*3) + ((?{# of degrees of success})d5))]] damage to @{target|token_name}```
    ```/me if this weapon dealt [[4]] or more degrees of success, it scores a Critical Hit. It can attack up to [[4]] times. On a critical hit it does [[1d10]] damage, in addition to a critical effect.```
## DAMAGE:PYRO-ACID BATTERY
    /me @{selected|token_name} scores [[?{# of hits|1}]] hits with its Pyro-Acidic Batteries! It deals [[{(((?{# of hits}-?{# of enemy shields|1})*3) + ((?{# of hits}-?{# of enemy shields|1})d10) - (@{target|shiparmor})), 0d0}kh1]] damage to @{target|token_name}
    /me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields.
    /me if this weapon dealt [[5]] or more hits, it scores a Critical Hit. It can hit a maximum of [[6]] times.
## DAMAGE:PYRO-ACID BATTERY SALVO - X2

    /me @{selected|token_name} scores [[?{# of hits 1|1}]] hits with the first battery of pyro-acidic batteries and [[?{# of hits 2|1}]] with the second! For [[{((((?{# of hits 1}+?{# of hits 2}-?{# of enemy shields|1})*3) + ((?{# of hits 1}+?{# of hits 2}-?{# of enemy shields|1})d10)) - (@{target|shiparmor})), 0d0}kh1]] damage!
    /me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the amount of damage by [[@{target|shiparmor}]] with its armor.
    /me if this weapon dealt [[5]] or more hits, it scores a Critical Hit. It can hit a maximum of [[12]] times and can only score one critical hit.
## DAMAGE:PYRO-ACID BATTERY SALVO X3
/me @{selected|token_name} scores [[?{# of hits 1|1}]] hits with the first battery of pyro-acidic batteries and [[?{# of hits 2|1}]] with the second and [[?{# of hits 3|1}]] with the third! For [[{((((?{# of hits 1}+?{# of hits 2}+?{# of hits 3}-?{# of enemy shields|1})*3) + ((?{# of hits 1}+?{# of hits 2}+?{# of hits 3}-?{# of enemy shields|1})d10)) - (@{target|shiparmor})), 0d0}kh1]] damage!
/me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the amount of damage by [[@{Target|shiparmor}]] with its armor.
/me if this weapon dealt [[5]] or more hits, it scores a Critical Hit. It can hit a maximum of [[18]] times and can only score one critical hit.
## DAMAGE:BIO-PLASMA SPINE
/me @{selected|token_name} does [[1d10+3]] Damage to @{target|token_name}. This damage bypasses armor and void shields.
/me If the attack roll with this weapon scored [[3]] or more Degrees of Success it deals a critical hit.
## DAMAGE:FEEDER TENTACLES
/me @{selected|token_name} has hit with its feeder tentacles! Resolve a Hit and Run action.
/me Feeder Tentacles can hit up to [[2]] times. If any of the attack rolls scored [[4]] or more degrees of success, it inflicts a critical hit and doubles crew and morale damage for that hit.
## TYRANID BIO TORPEDOES
?{What Kind of Torpedo? |
Boarding,
/me The Torpedoes hit! they can deal up to an amount of hits equal to the Strength of the launcher that fired them.
/me 1st Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
/me 2nd Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
/me 3rd Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
/me 4th Hit: [[{(((2d10r<2)+11) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage
/me if any of the hits' damage exceeds the ship's armor (that is&#44; you deal at least 1 point of damage) it instead does no damage and immediately inflicts a Hit And Run attack. |
Virus,
/me The Torpedoes hit! they can deal up to an amount of hits equal to the Strength of the launcher that fired them.
/me 1st Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
/me 2nd Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
/me 3rd Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
/me 4th Hit: [[{(((2d10r<1)+10) - (@{target|shiparmor}))&#44; 0d0&#125;kh1]] damage&#44; [[3d10]] Crew Damage and [[2d10]] Morale Damage.
/me if any of the hits' damage exceeds the ship's armor (that is&#44; you deal at least 1 point of damage) it instead does no damage and immediately inflicts Crew damage and Morale damage. A character aboard must make a -10 Command Test to halt the spread of the disease or the vessel will take this damage every turn. |
}
# TAU MACROS
## ANEUVER ACTIONS
?{Which Action?|
Maneuver Test,
/me @{selected|token_name} makes a maneuver test and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! |
Adjust Bearing,
/me @{selected|token_name} attempts to Adjust the ship's Bearing and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success!
/me On a success&#44; the ship may turn after moving 1 VU less than its speed. For every Degree of Success&#44; it may turn after moving 1 less VU. A ship must move at least 1 VU before turning. Once it has turned&#44; it must move its remaining distance. |
All Ahead Full,
/me @{selected|token_name} attempts to move faster and scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may increase the number of VUs it moves by 1. All shipboard firing suffers a [[-20]] penalty this turn. |
Burn Retros,
/me @{selected|token_name} attempts to slow down or come to a stop and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me For each Degree of Success&#44; the ship may  decrease the number of VUs it moves by 1. It may also turn after moving one VU less than its speed per Degree of Success. If it would come to a stop it may turn in place. The ship suffers [[-20]] to all shipboard shooting this turn. |
Come to New Heading,
/me @{selected|token_name} attempts to Come to a New Heading and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success! 
/me Success indicates that the ship may turn when it has moved half its speed&#44; then turn again once it has moved its full speed. This radical course correction imposes a [[-20]] penalty on Ballistic Skill Tests during this turn. |
Disengage,
/me @{selected|token_name} attempts to Disengage and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success.
/me If the Degrees of Success are more than the amount of ships within 20 VUs&#44; the ship successfully disengages from combat&#44; and may not re-enter it. |
Evasive Maneuvers,
/me @{selected|token_name} attempts Evasive Maneuvers and scores [[(@{selected|shipcrewrating} + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 10 - 1d100)/10]] Degrees of Success!
/me Each Degree of Success imposes a [[-10]] penalty to all shooting directed towards @{selected|token_name}&#44; which suffers the same penalty until its next turn. |
}	
## NPC COMBAT
?{Which Action?|
Initiative,
/me @{selected|token_name} rolls [[1d10+floor(@{selected|ShipDetection}/10) &{tracker&#125;]] for Initiative |
Fire Weapon,
/me @{selected|token_name} fires it's weapons at @{target|token_name}. [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degree(s) of Success! |
Turret Defense,
/me @{selected|token_name} defends with the turrets. [[(@{selected|shipcrewrating} + (@{selected|ShipTurretRating}*5) - (?{Enemy Fighters?&#124;0&#125;*10) - 1d100)/10)]] Degree(s) of Success! 
/me The turrets hit once&#44; plus once more for every [[2]] degrees of success. With each hit they take down [[1]] Torpedo or Squadron. |
Launch Voidcraft,
/me @{selected|token_name} launches its voidcraft. It can launch up to [[x]] total squadrons. |
Launch Torpedoes,
/me @{selected|token_name} launches torpedoes. It can launch up to [[x]] torpedoes. |
Critical Hit,
/me [[1t[VSCH]]] on @{target|token_name}'s [[1t[Random-Component]]] |
}
## VOIDCOMBAT:EXTENDED
?{Which Action?|
All power to Shields,
/me @{selected|token_name} attempts to reroute power to the void shields&#44; he scores [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} gains [[1]] extra void shield until the beginning of its next turn. For every [[3]] Degrees of Success, @{selected|token_name} gains [[1]] additional void shield&#44; up to a maximum of double its base.
/me Due to the taxing drain on the ship&#44; @{selected|token_name} suffers a [[-20]] penalty to all Augury&#44; Manuever&#44; and Shooting actions until the beginning of its next turn. |
Divert Power,
/me @{selected|token_name} attempts to reroute nonessential power. He scores  [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; unpower [[1]] component to provide power for [[1]] unpowered component. This new power lasts for [[1]] round&#44; plus [[1]] round for every [[3]] Degrees of Success. Failure by [[3]] or more degrees means that the target component overloads and becomes damaged&#44; or destroyed if it was already damaged. |
Emergency Repairs,
/me @{selected|token_name} attempts to organize and lead Emergency Repair Crews to damaged portions of the ships. He scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a Success&#44; @{selected|token_name} and his repair crews restore one Unpowered&#44; Damaged&#44; or Depressurized component to working order. This repair take [[1d5]] turns&#44; minus 1 per Degree of Success. This action can remove only one condition at a time. |
Fight Fires,
/me @{selected|token_name} attempts to organize and lead firefighting teams into the blaze. He scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the firefighting teams successfully put out the fire within one turn. | 
Emergency Vent, 
/me @{selected|token_name} attempts to make an emergency venting action. He scores  [[(@{selected|shipcrewrating} - 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a Success&#44; the crew of the component expose it to hard void. The ship suffers [[2d10]] Morale damage and the component is now depressurized. If the component was on fire&#44; the ship suffers [[1d5]] Crew Damage and the fire is now out. If the component was boarded&#44; the ship suffers [[1d5]] Crew Damage. If the component was neither&#44; the ship suffers [[1d10]] Crew Damage. | 
Flank Speed, 
/me @{selected|token_name} attempts to push the engines to their limit&#44; he scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me On a success&#44; @{selected|token_name} may move [[1]] additional VU this turn&#44; plus [[1]] per degree of success.
/me Failure by [[2]] or more Degrees means the ship immediately suffers the Engines Crippled critical hit as the engines are strained too hard. | 
Hit and Run (Pilot),
/me @{selected|token_name} is attempting to hit and run! He scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Aeronautica) Test. |
Hit and Run (Attacking),
/me The character has boarded the enemy vessel. He must make a Command test: [[(@{selected|shipcrewrating} + 10 - 30 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (Defending),
/me The character is defending his vessel from boarders. He must make a Command test: [[(@{selected|shipcrewrating} + 10 - 30 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test&#44; opposed by the enemy commander. |
Hit and Run (damage),
/me The character has succeeded at a hit and run! He has his choice of doing [[1d5]] Crew Damage and [[1d5]] Morale damage&#44; [[1]] Hull Integrity per degree of success&#44; or his choice of two critical hits. |
Jam Communications,
/me @{selected|token_name} attempts to jam enemy communications. He scores  [[(@{selected|shipcrewrating} -10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Tech-Use Test.
/me If he succeeds&#44; an enemy ship within [[20]] VUs is unable to use communications for the next [[2d5]] turns. |
Lock on Target, 
/me @{selected|token_name} is attempting to Lock On Target. He scores [[(@{selected|shipcrewrating} + @{selected|shipdetection} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Scrutiny Test.
/me On a success&#44; the adds +5 to the Ballistic Skill of one component this turn. For every 2 degrees of success&#44; he may add an additional 5. |
Prepare to Repel Boarders!, 
/me @{selected|token_name} is organizing counter-boarders! He scores [[(@{selected|shipcrewrating} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he adds +10 to any opposed Command Tests he performs against enemy boarders during subsequent turns. Each degree of success gives him a +5 bonus. The character must sacrifice his turn each round he wishes to maintain this bonus. |
Ramming Action, 
/me @{selected|token_name} attempts to Ram an enemy within 1 VU. He scores [[(@{selected|shipcrewrating} - 20 + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me If he succeeds&#44; the ships crash together. Raiders or Transports do [[1d5+@{selected|shiparmor}]] damage. Cruisers do [[2d5+@{selected|shiparmor}]] damage. Larger ships do [[2d10+@{selected|shiparmor}]] damage. @{selected|token_name} suffers [[1d5]] damage plus the armor of the enemy ship.
/me On a failure&#44; the ramming ship suffers the same damage it did to the enemy. All damage dealt by ramming ignores armor.|
Ready Squadrons, 
/me @{selected|token_name} is attempting to scramble small craft! He scores [[(@{selected|shipcrewrating} + 10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he automatically readies a number of small craft equal to the strength of the launch bay component being used. |
Reload Ordnance, 
/me @{selected|token_name} is attempting to reload ordnance! He scores [[(@{selected|shipcrewrating} -10 + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Command Test.
/me On a success&#44; he automatically rearms all empty launch tubes. They are ready to fire in the same turn. |
Silent Running, 
/me @{selected|token_name} attempts to maneuver while Silent Running. He scores [[(@{selected|shipcrewrating} + 10 + @{selected|ShipManoeuvrability} + ?{modifier&#124;0&#125; - 1d100)/10]] Degrees of Success on this Operate (Voidship) Test.
/me On a success&#44; the ship is not detected. |
}
DAMAGE:BOMBERS
/me @{selected|token_name} deals [[?{# DoS|1}]] hits on @{target|token_name} and deals [[{((?{# DoS}d10) + (4 * ?{# DoS}) - @{target|shiparmor}), 0d0}kh1]] total damage!
/me If the attack scored 4 or more Degrees of Success, it also inflicts a critical hit on @{target|token_name}!
ATTACK: BOMBERS
/me @{selected|token_name} makes a bombing run on @{target|enemy|token_name} and scores [[(@{target|Character|fellowship} + @{selected|craftrating} + ?{Command Modifier|0} + ?{modifier?|0} - 1d100)/10]] Degrees of Success!
/me The Bomber Squadron can score up to [[3]] hits, plus [[1]] per additional friendly squadron.
ATTACK: FIGHTERS
/me @{selected|token_name} attacks @{target|enemy|token_name} and scores [[(@{target|character|fellowship} + @{selected|CraftRating} + ?{Command Modifier|0} + ?{modifier?|0} - 1d100)/10]] Degrees of Success.
/me For each Degree of Success scored, one opposing Squadron or torpedo is eliminated.
/me @{target|enemy|token_name} must attack in response.
RAILGUN FORMULA
/me @{selected|token_name} scores [[?{# of hits|1}]] hits with its railguns! It deals [[{(((?{# of hits}-?{# of enemy shields|1})*4) + ((?{# of hits}-?{# of enemy shields|1})d10) - (@{target|shiparmor})), 0d0}kh1]] damage to @{target|token_name}
/me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the damage by [[@{target|shiparmor}]] with its armor.
/me if this weapon dealt [[4]] or more hits, it scores a Critical Hit. It can hit a maximum of [[4]] times.
RAILGUN SALVO FORMULA x2
/me @{selected|token_name} scores [[?{# of hits 1|1}]] hits with the first battery of railguns and [[?{# of hits 2|1}]] with the second! For [[{((((?{# of hits 1}+?{# of hits 2}-?{# of enemy shields|1})*4) + ((?{# of hits 1}+?{# of hits 2}-?{# of enemy shields|1})d10)) - (@{target|shiparmor})), 0d0}kh1]] damage!
/me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the amount of damage by [[@{target|shiparmor}]] with its armor.
/me if this weapon dealt [[4]] or more hits, it scores a Critical Hit. It can hit a maximum of [[8]] times and can only score one critical hit.
RAILGUN SALVO FORMULA X3
/me @{selected|token_name} scores [[?{# of hits 1|1}]] hits with the first battery of railguns and [[?{# of hits 2|1}]] with the second and [[?{# of hits 3|1}]] with the third! For [[{((((?{# of hits 1}+?{# of hits 2}+?{# of hits 3}-?{# of enemy shields|1})*4) + ((?{# of hits 1}+?{# of hits 2}+?{# of hits 3}-?{# of enemy shields|1})d10)) - (@{target|shiparmor})), 0d0}kh1]] damage!
/me @{target|token_name} reduced the amount of hits by [[?{# of enemy shields}]] with its void shields and the amount of damage by [[@{Target|shiparmor}]] with its armor.
/me if this weapon dealt [[4]] or more hits, it scores a Critical Hit. It can hit a maximum of [[12]] times and can only score one critical hit.
ION CANNON FORMULA
/me @{selected|token_name} does [[1d10+2]] Damage to @{target|token_name}. This damage bypasses armor but not void shields.
/me If the attack roll with this weapon scored [[3]] or more Degrees of Success it deals a critical hit.


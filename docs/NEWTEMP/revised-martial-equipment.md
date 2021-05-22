<style>
  .phb#p1{ text-align:center; }
  .phb#p1:after{ display:none; }
</style>

<div style='margin-top:650px;'></div>

# Revised Martial Equipment

<div style='margin-top:25px'></div>
<div class='wide'>
##### The Weapons and Armors of War
  <div style='margin-top:10px'></div>


A revised system of weapons and equipment for the ways of martial combat for 5th edition of Dungeons and Dragons.
</div>

<img 
  src='https://i.imgur.com/8SBq3qN.png' 
  style='position:absolute; top:0px; right:0px; width:1000px' />

<img 
  src='https://i.imgur.com/5NwjW0J.png' 
  style='position:absolute; bottom:0px; right:-10px; width:1000px' />
  

<div class='footnote'>Revision 1.7.2</div>


\page
<style>
  .toc a {
    color: inherit !important;	/*toc specifically wants black text. This resets the headers*/
  }

  .toc li span:nth-child(2){	/*Allow dot leaders to fill remaining space but not overlap*/
    width: auto;
    overflow: hidden;
    white-space: nowrap; 
    display: block;
  }

  .toc li span:nth-child(2):after{
    font-family		: BookSanity;	/*Remove any header styles from dot leaders*/
     font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    conte
nt:
      " ........................................"
      "........................................."
      "........................................."; 
  }
  
  .toc li span:first-child{
    float: right;
    font-family		: BookSanity;	/*Remove any header styles from page numbers*/
    font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    margin-left		: 1px;	/*Leaves a small space between page numbers and dot leaders*/
  }
  
/*Special cases for headings*/    
  .toc li h3 span:nth-child(2):after{
  	content: " ";						/*Remove dot leaders on h3*/
  }
  
  .toc li h3 {
    margin-bottom: 4px !important;		/*Special spacing for h3*/
    margin-top: 10px !important;
    line-height: initial !important;	/*For some reason Multi-line h3 line spacing changed*/
  }
  
  .toc li h3 span:first-child{
  	line-height: 1.8em !important;  	/*Line page numbers up with Multi-line h3 better*/
  }
  
  .toc ul ul {
  	margin-left: 10px !important;		/*Original lists intented too much*/
  }
  
  .toc>ul>li {
    margin-bottom: initial !important;	/*margin for list items needs to be removed or 0*/
  }
</style>

<div class='wide' style="text-align: center">
# Table of Contents
</div>

<div class='toc'>
- ##### [<span>3</span><span>Introduction and Feat Changes</span>](#p3)
- ### [<span></span><span>**Special Lists**</span>](#p2)
- #### [<span>4</span><span>Weapon Groups</span>](#p4)
- #### [<span>5</span><span>Special Lists</span>](#p5)
- #### [<span>5</span><span>Ammunition</span>](#p5)
- #### [<span>6</span><span>Special Notes and Best Practices</span>](#p6)
- #### [<span>7</span><span>Weapon DC and Properties</span>](#p7)
- ### [<span></span><span>**Groups**</span>](#p2)
- #### [<span>10</span><span>Armor</span>](#p10)
- #### [<span>12</span><span>Shields</span>](#p12)
- #### [<span>13</span><span>Ambush Weapons</span>](#p13)
- #### [<span>15</span><span>Axes</span>](#p15)
- #### [<span>17</span><span>Bludgeons</span>](#p17)
- #### [<span>19</span><span>Bows and Slings</span>](#p19)
- #### [<span>21</span><span>Combat Blades</span>](#p21)
- #### [<span>23</span><span>Crossbows</span>](#p23)
- #### [<span>25</span><span>Dueling Blades</span>](#p25)
- #### [<span>27</span><span>Firearms</span>](#p27)
- #### [<span>29</span><span>Flails and Whips</span>](#p29)
- #### [<span>31</span><span>Hammers and Picks</span>](#p31)
- #### [<span>33</span><span>Polearms</span>](#p33)
- #### [<span>35</span><span>Spears</span>](#p35)
- #### [<span>37</span><span>Throwing Weapons</span>](#p37)
- ### [<span>39</span><span>**Credits**</span>](#p39)


</div>

```
```
>### Everything is Important!
Please read this document in its entirety (and perhaps several times) before using it in your campaign! There are a lot of nuanced rules, special notes, and sidebars for clarity that can perhaps be easily missed if you skim this brew. 

<img 
  src='https://i.imgur.com/86MQ6zK.png' 
  style='position:absolute; bottom:-20px; right:-90px; width:850px' />

<div class='pageNumber auto'></div>
<div class='footnote'>CONTENTS</div>

\page

# Realistic Equipment with a Fantasy Flair

The RME Homebrew gives extra options, more damage, and greater flexibility to the equipment of martial classes. It is an attempt to make each weapon feel unique and interesting, and give the average fighter more to do on their turn, rather than simply attack, roll a couple of damage dice, then wait for the next turn. 

The equipment in this system is lifted from the core rules, with several dozen more added for fantasy concepts and to cover a wide range of cultures and time frames at home in a medieval fantasy setting. The weapons are no longer divided into  "simple" and "martial" categories, rather each weapon, shield, and armor is now part of a group of similar equipment, such as axes, bludgeons, or polearms. 

Two different shield types join the lineup, and armor has been made more in line with its historical weight and coverages. While some effort was made to reflect historical weapon and armor weight and usage, some effort was made to include fantasy concepts, such as boomerangs returning after striking the target or warhammers sending foes flying. 

**Each character now has three levels of training with all equipment; Simple, Martial, and Master.** With each level of training, the character gains more abilities and greater flexibility with the equipment, which can be improved with study and training to obtain mastery with any given weapon group, armor, or shields.  


### Translating to an RME Campaign

This system requires a bit of converting from the 5e core rules but don't worry, it's easy! 

Look at your race, class, subclass, and any feats you've taken; note any proficiencies with weapons, armor, and shields.

These proficiencies become Martial training. If your class gives martial weapon proficiency, you use all weapons with Martial training. If your class gives simple weapon proficiency, you use weapons in the list "Simple Weapons" with Martial training. If any specific weapon proficiency is listed, for example, high elves with longswords, shortswords, longbows, and shortbows, you use them with Martial training. Anything not listed as proficiency becomes Simple training. For example, a Sorcerer would use a greatsword with Simple training.

If any proficiencies are redundant, you instead have <br>Master training with that equipment. For example, a Drow has Martial training with hand crossbows, shortswords and rapiers, and a rogue has Martial training with those as well. So a Drow Rogue would have Master training with hand crossbows, shortswords and rapiers, and Martial training with the other weapons listed. The exception to this is with multiclassing. A Fighter multiclassed with Barbarian would not have Master training with all weapons, simply because both classes give martial weapon proficiency.

You may also increase your training with any equipment group. To train from Simple to Martial, you must find a capable teacher and train for 42 days. To train from Martial to Master, your teacher must train you for 250 days. Bear in mind most trainers must be paid for their work.

.

> ### Feat Changes for RME
>This system is best when previous feats related to weapon training are removed or changed to the following:
>
>- The following feats are disallowed: **Blade Master, Fell Handed, Flail Mastery, Great Weapon Master, Heavy Armor Master, Medium Armor Master, Polearm Master, Sharpshooter, Shield Master, Spear Mastery** and **Warhammer Master**
>
>- The feat **Weapon Master** allows you to gain master training with four weapons of your choice, regardless of your current proficiency.
>
>- The feat **Skilled** allows you to take any combination of three skills, tools, weapon, armor, or shield training levels.
>
>- Finally, with your DM's permission, you can substitute any tool proficiency for a single weapon or shield proficiency, even to stack to master training.



<img 
  src='https://i.imgur.com/hqJrAqK.png' 
  style='position:absolute; bottom:-80px; right:-110px; width:550px' />
  
  <div class='pageNumber auto'></div>
  <div class='footnote'>INTRODUCTION</div>



\page
## Weapon Group Summaries

#### Shields
Whether a target or tower, shields come in all shapes and sizes from kites to circles to teardrops to coffins. There are obvious benefits to the size and shape of your shield, and Masters learn offensive use of their shield and can even protect themselves from dragon's breath. 

#### Ambush Weapons
These weapons are not designed for combat, rather for close quarters or surprise attacks. They are easily hidden or mundane, and in the right hands can end a fight before it's even started. Masters of the ambush have learned to strike more critically, taking full advantage of a surprise attack in stealth or combat, and can strike so fast, they can turn an enemy's missed attack into an opening for their own. 

#### Axes
Axes easily chop through targets using weight instead of a honed edge. An axe’s beard, or the length of the head between the blade and haft, is just as effective in the hands of an expert as the edge is. Axe masters carry the weight of the head through soft targets and into others and by taking a woodcutter’s stance, which can fell even the stoutest of foes.

#### Bludgeons
Bludgeons are more simple weapons that rely on pure weight over control. However, they have additional uses in stunning, disabling and fatiguing the enemy with repeated and precise blows to the head or body.  A master with these brutish weapons more deftly causes stuns and exhaustion.

#### Bows and Slings
The bow is as ancient as civilization itself, the tool of the hunter, sniper, assassin and soldier alike. Bows require more training than crossbows, but reload faster, making them still hold relevance in the age of mechanical winding and gunpowder. A master archer places arrows as effortlessly as a master swordsman places their blade, and can even overdraw the shot to put more power into the arrow with decreased accuracy. 

#### Combat Blades
Combat blades are military weapons designed for soldiers at war. These weapons are long, powerful swords designed for maximum reach and damage. A master with combat blades takes full advantage of the guard, and takes the best advantage of the opportunity to rout an enemy. Few weapon are as damaging and versatile as Combat Blades.

#### Crossbows
Crossbows require less training to operate than a bow and are often more powerful, but their reload time keeps them from making the former obsolete. Each crossbow type has a different reload speed, requiring time spent reloading rather than being part of the attack, like a bow. Masters of the crossbows shoot in combat without distraction, and can accurately hit two targets with a single bolt.
```
```

#### Dueling Blades
Dueling blades are smaller, lighter weapons designed for civilian defense and duels. These weapons deal less damage but have more specialized uses, often used with finesse. A dueling blade master uses the weapon’s speed to take advantage of a distraction to unleash a flurry of combo attacks.

#### Firearms
These are late medieval to early renaissance period firearms which use some ignition, and optionally a projectile, to attack enemies at range. They are inaccurate, prone to jamming, require specialized training, and create loud sounds and smoke which can be to the detriment of the user. However, even combat blades struggle to have as much stopping power as the firearm. Master musketeers can quickly clear a jam, use the firearm as a melee weapon in close combat, and can fire more accurately with their shots.

#### Flails and Whips
These are weapons of misdirection, rather than straightforward blows. The weapon design may not always be optimal, but the reach and flexibility gives additional options in battle. Masters with the flail and whip can swing around shields, and use the binding property of their weapon to trip foes unready for the attack. 

#### Hammers and Picks
These weapons share an anti-armor design of concentrated force, either on the point of a pick or face of a hammer. Differing from bludgeons with specialization against armor and more refined technique, these weapons are staples for any warrior needing to open some cans. Masters knock foes to the ground and can even pierce or bludgeon a target through the armor that stops a hit. 

#### Polearms
These are weapons of reach, usually a weapon mounted on a lengthy pole. These weapons are often designed for use in standard infantries, and have natural capabilities against charging cavalry or massive targets. A master has developed such precision he can strike as a reaction even at reach and can strike with the butt of the weapon in close quarters. 

#### Spears
If a bow is as old as civilization, a spear is as old as the species. A feature in almost every military in history, spears have an efficiency unmatched in terms of production, training, and application.  Masters have acquired the lunge, and have such disciplined accuracy, they can make the smallest opportunity into a killing thrust.

#### Throwing Weapons
These weapons allow snap precision in combat at medium range. Often paired with special abilities, throwing is a very unique combat style. In addition to the weapons in this group, master training in the throwing weapons group allows master training with all weapons that have the thrown weapon feature, and a master can curve throws around corners or snap throw at any distracted enemy in an instant. 

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

<div class='pageNumber auto'></div>
<div class='footnote'>WEAPON GROUPS</div>
\page
## Special Lists
The following lists have been prepared to help with reference when the rules mention them. Additionally, some classes have gained Martial training with some weapons added in this system. 

<div class='wide'>

| Class | Lists |
|:--|:--|
|Bard Weapons| All simple weapons, Throwing Weapons group, Interceptor, Longsword, Rapier, Saber, Scimitar, Smallsword, Tomahawk.
| Druid Weapons|Bolas, Boomerang, Dagger, Dart, Flanged Mace, Gauntlet, Great Club, Harpoon, Heavy Club, Hook Sword, Javelin, Knuckle Axe, Kukri, Lance, Light Club, Mallet, Morningstar, Pike, Punch Dagger, Quarterstaff, Ravenbeak, Scimitar, Sickle, Sling, Tomahawk, Trident, War Scythe, War Spear, Wall Pick, Whip, Wrist Shot|
| Monk Weapons  | All Simple Weapons, Blowgun, Broadsword, Godendag, Katana, Knuckle Axe, Hook Sword, Interceptor, Lajatang, Meteor Hammer, Sai, Whip Dagger |
|Rogue Weapons| All Simple weapons, all weapons with the "Conceal" property, Rapier, Saber, Smallsword|

|Weapon | Lists|
|:--|:--|
| Finesse Weapons | Bladed Bow, Chain Sword, Chakram, Dagger, Dart, Glaive, Hidden Blade, Hook Sword, Interceptor, Katana, Lajatang, Light Club, Light Pick, Longsword, Meteor Hammer, Nunchaku, Punch Dagger, Rapier, Sai, Saber, Scimitar, Short Glaive, Shortsword, Smallsword, Stiletto, Throwing Star, Tomahawk, Unarmed Strike, War Spear, Whip, Whip Dagger |
| Simple Weapons | Bar Mace, Dagger, Dart, Flanged Mace, Gauntlet, Great Club, Guisarme, Hand Crossbow, Handaxe, Heavy Club, Heavy Crossbow, Javelin, Kukri, Light Club, Light Crossbow, Light Flail, Light Pick, Mallet, Morningstar, Nunchaku, Pike, Punch Dagger, Quarterstaff, Ravenbeak, Recurve, Shortbow, Shortsword, Sickle, Side Baton, Sling, Spinner, Stiletto, Throwing Knife, Throwing Star, War Scythe |
| Underwater Weapons | Blowgun, Dagger, Gauntlet, Godendag, Hand Crossbow, Heavy Crossbow, Harpoon, Hidden Blade, Hidden Crossbow, Lance, Light Crossbow, Javelin, Knuckle Axe, Mauler, Net, Pike, Punch Dagger, Ravenbeak, Sai, Shortsword, Spinner, Stiletto, Trident, Unarmed Strikes, War Spear, Wrist Shot, and any weapon with the thrown property used as a ranged attack |
  
</div>


<div class='wide'>
##### Ammunition Cost and Weight
| Type | Cost | Weight | For Use With
|:--:|:--|:--|--:
| Arrow  | 0.05 | 0.05 | Bladed Bow, Compound, Longbow, Shortbow, Recurve
| Great Arrow | 0.1 | 0.1| Greatbow
| Lead Ball | 0.06| 0.06| Arquebus, Hand Cannon
| Bolt | 0.05 | 0.025| Hand Crossbow, Heavy Crossbow, Light Crossbow, Mauler
| Bullet | 0.01 |0.05|Sling, Wrist Shot
| Needle | 0.01 | 0.01 | Blowgun, Hidden Crossbow
| Gun Powder| 0.5| 0.125|Arquebus, Blunderbuss, Firelance, Hand Cannon, Pepperbox
| Shot| 0.5| 0.03| Blunderbuss, Pepperbox
</div>

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

```
```

> ##### Remember Underwater Warfare!
> All weapons suffer disadvantage while attacking underwater or targeting underwater enemies, and all ranged weapons automatically miss enemies beyond their normal range. Underwater Weapons perform normally in these conditions
 


<img 
  src='https://i.imgur.com/JDdjJUm.png' 
  style='position:absolute; bottom:0px; right:-10px; width:900px' />
  
  <div class='pageNumber auto'></div>
  <div class='footnote'>SPECIAL LISTS</div>
  
  
  
\page


## Special Notes 

There are a few tweaks and adjustments to the core rules of the 5th Edition Dungeons and Dragons system to accommodate the Revised Martial Equipment system presented here, as well as some important things to note about the RME system itself while using it. 

### Master Feats and Perks
Each equipment group lists a feat that a character can take to gain unique abilities with the equipment of that group.


**When you take a Group Master Feat, you gain master training and master perks with all equipment in that group.** 

All Master feats apply to that group only. For example, if you have taken **Combat Blade Master**, which grants you advantage on opportunity attacks, you only have this advantage when using a Combat Blade to make the opportunity attack. 

All weapon perks apply to that weapon only. For example, if you have taken **Axe Master,** which grants you rerolls on damage with a battleaxe if you roll a 1 or 2, you cannot wield a battleaxe in one hand and reroll all damage rolls from other weapons or sources. The damage rerolls only apply to the battleaxe and its attachers only.

Finally, any perk which gives you +1 AC for wielding a certain weapon or combination of weapons doesn't stack. For example, a Master with Dueling Blades dual wielding a rapier and other light weapon gains +1 AC, and while wielding a sai in the off hand grants +1 AC. These do not stack to +2 AC if the Master wields a rapier and sai together. Further, this bonus doesn't stack with shields, as this is all considered Shield AC.


<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>


```
```
### Class and Subclass additions

Bard College of Swords, Fighter Arcane Archer, Fighter Gunsmith, Monk Way of the Kensei, and Warlock Pact of the Blade have Master training with their chosen weapons. Monk Way of the Open Hand has Master Training with Unarmed Strikes.



### Best Practice
These suggested house rules make the system more fun according to our playtesting. These are of course optional rules and not required for this system to work as intended. 
 
- Flanking an enemy adds +2 to attack rolls for two creatures flanking an enemy, and +5 if three or more creatures flank an enemy.
- Dual Wielding and Double Ended attacks count the off hand attack as part of your attack action, rather than using a Bonus Action. Optionally,  give this buff only to characters that take the feat **Dual Wielder**.
- If you have the **Grappler** or **Tavern Brawler** feat and Martial training with unarmed attacks, you can make unarmed deflect, trip, and disarm attempts.
- In this system, Martial training Unarmed Strikes deal d4 bludgeoning damage. To balance any race which grants natural weapons such as Tabaxi claws, Lizardfolk bite, or Dragonborn claws, they instead deal one size larger dice. A Tabaxi's claws would deal d6 slashing damage, for example. 
- When you score a critical hit, maximize your weapon's dice damage, then roll the bonus damage from a critical hit to prevent Critical Hits dealing less damage than normal. Do not maximize attachers such as Sneak Attack or Smite.
- During a grapple, Heavy or Two Handed weapons attack with disadvantage, while Light, Unarmed Strikes, and Bite attacks gain Advantage. This also has an added benefit of making weapons with Versatile more versatile!


<img 
  src='https://i.imgur.com/5K32CYo.png' 
  style='position:absolute; bottom:-35px; right:-10px; width:900px' />
  
  <div class='pageNumber auto'></div>
<div class='footnote'>SPECIAL LISTS</div>
\page
# Weapon DC and Properties


##### Weapon DC
When your enemy must make a Strength Constitution, or Dexterity Saving Throw to avoid the conditions given by these Weapon Properties, it is against your Weapon DC, which is calculated with the following equation:
___
**Weapon DC = 8 + your proficiency + your strength modifier.**
___
You can substitute Strength for Dexterity if the weapon has the finesse property. You may also substitute Strength for another ability used for a melee weapon attack as part of a class ability, such as Hexblade Warlock using Charisma instead of Strength. 

Any other effect, such as the modifier rolled with Deflect, or the modifier used to damage on a Disarm, Entangle, or Trip attempt is only ever Strength. If a weapon has any magical or craftsmanship attack bonus, this is added to your Weapon DC.

```
```
##### Awkward
This weapon requires additional training to use properly, but you still get limited use with it. You do not add your proficiency bonus while rolling an attack with this weapon.

##### Conceal
You gain advantage on Sleight of Hand Checks made to conceal the weapon on your person. If it is discovered, some Conceal weapons still require the searching party makes a successful Intelligence check to identify what it is.

##### Brace
As an Action you choose to Brace. On your turn, choose any targets you can see that are at least 20 feet away from you. If any of those targets move within your weapon’s reach before your next turn, you can make one melee attack against them with your weapon, which uses your reaction. If the attack hits, treat the attack as a critical hit. While bracing, you cannot use a reaction.

While bracing, if you move or are moved against your will, you forfeit the reaction until your next turn. A brace attack is not an Opportunity Attack. 


##### Deflect
If struck by a melee weapon attack, you can use your reaction to roll your weapon’s damage plus your strength modifier, then subtract that total from the damage dealt to you for one attack. If you are dual wielding deflect weapons, you gain an additional reaction which may only be used to deflect.


##### Disarm
You may only make a disarm attack with weapons that have the Disarm property, unless you have an ability that says otherwise. On a hit, you can choose to only deal damage equal to your Strength modifier, and force your enemy to roll their choice of a Strength or Dexterity Saving Throw. On a failure, it drops one held object of your choice, landing within 5ft of it. If the enemy is larger than you or is using a two-handed weapon, it gains advantage on this save. If it is smaller than you, it suffers disadvantage. Shields that are strapped to the arm are immune to Disarm.

##### Double Ended
 You make one additional attack as a bonus action (or part of the attack action, see: Best Practices) using the damage listed and your ability modifier, if you are within 5 ft of your target and wielding your weapon with two hands. Double Ended attacks do not benefit from Reach.
 

> ##### Disarm Mechanics
>- A disarm drops the item at the target's feet. On its turn, the target can pick up the item using its free object interaction, so be sure someone grabs the disarmed item before its turn! 
> - You can disarm something 5 ft in any direction, so if there is a nearby cliff or pool of lava, you should disarm the weapon into it to prevent your enemy from retrieving it on their turn!






<img 
  src='https://i.imgur.com/LI76MbU.png' 
  style='position:absolute; bottom:-20px; left:-120px; width:550px' />



 <div class='pageNumber auto'></div>
<div class='footnote'>WEAPON PROPERTIES</div>

\page




##### Entangle
On hit, you can choose to deal only your Strength modifier in damage and force the enemy to succeed on a Strength or Dexterity Saving Throw or be grappled. To escape, the entangled target must succeed a grapple check against your weapon DC, gaining advantage if it is larger than you. Creatures two size categories larger than you are immune to being entangled. 

While you are holding the weapon entangling your target, your attacks only damage equal to your Strength modifier. You may also interact with your target as if you were grappling it, for example, moving it or shoving it. You can release a foe from being entangled at any time. If you drop the weapon, the foe is automatically freed.

##### Finesse
When making an attack with a finesse weapon, you use your Strength or Dexterity modifier for the attack and damage rolls. You must use the same modifier for both rolls.

##### Firearm
Rolling a 1 on an Attack Roll causes this weapon to jam. It's still loaded, but a malfunction prevented ignition. As an action, you must clear the jam before it can make a ranged attack again. Firearm weapons can't make ranged attacks underwater, and if they are subjected to water such as from rain or a tidal wave spell, they jam on a 1-2 until you spend an action to dry them. All firearms create a sound which can be heard up to 300ft away.

Firearm weapons that have the Ranged property require gun powder and either lead ball, bullet, or shot loaded into it to make an attack. Ammunition is not recoverable from Firearm weapons. 

Firearm weapons that have the Launch property can be recovered if they fail to go off due to a jam (meaning the weapon was thrown, but did not explode when it landed)

##### Heavy
Category size Small creatures always suffer disadvantage to attack rolls with a heavy weapon. Tiny and smaller cannot wield this weapon.

##### Launch
If you miss, this weapon lands on the ground but still goes off within 5ft of the intended target, unless it misfires from being a Firearm. Roll a d8. The result is which square it lands in, starting with the square closest to you as 1, and counting clockwise until you reach the rolled number. 

##### Light
This weapon is light and easy to handle. While dual <br>wielding, unless you have the **Dual Wielder** feat, <br>both weapons must have this weapon property.<br> You can make an attack with your off-hand weapon <br>as a Bonus Action (or part of the Attack Action; see Best Practices). You don't add any ability modifier to damage with this attack unless you have the **Two Weapon Fighting Style**. 

##### Lunge
If you use an attack action, you attack a foe up to 5ft further than normal with all attacks for that turn, which can be combined with Reach. This ends with your turn and cannot be used as part of an Opportunity Attack. Performing a lunge uses your reaction.

##### Melee
Melee Weapons make a melee weapon attack at another creature up to 5ft away, and add strength modifier to attack and damage rolls. A Melee weapon cannot be thrown as an attack unless it has the Thrown weapon property.

##### One Handed
A one-handed weapon requires only one hand to wield, leaving the off-hand open to wield another weapon, shield, grapple, or be used for the somatic component of a spell. 

##### Penetrate
These weapons are designed to penetrate armor and deal more damage to those wearing it. While attacking an enemy using a shield or wearing heavy armor, you can roll total damage from your weapon twice and take the better result. 

##### Ranged
Ranged weapons make a ranged weapon attack using dexterity for attack and damage. Your ranged weapon must be loaded with ammunition in order to make an attack. Range always lists two numbers. The first is the weapon's normal range, and the second indicates its maximum range. When attacking enemies beyond the normal range or with an enemy within 5ft of you, you suffer disadvantage for that attack. A ranged weapon cannot attack targets beyond its maximum range. 







<img 
  src='https://i.imgur.com/ffhc0eR.png' 
  style='position:absolute; bottom:-95px; right:-70px; width:600px' />


 <div class='pageNumber auto'></div>
<div class='footnote'>WEAPON PROPERTIES</div>
\page



##### Reach
This weapon adds 5 feet to your reach when you make a melee weapon attack, as well as for determining your reach for Opportunity Attacks with it. Note that if there is a creature between you and your enemy within reach, your enemy has half cover. Reach cannot be used to extend the range of a Double Ended attack.





##### Reload
Some ranged weapons take a time to reload, though trained users can reload faster. Reload times are expressed in types of game actions. From fastest to slowest, these are; **part of attack, free object interaction, reaction, bonus, attack, action. **

The following rules apply to all Reload weapons:
```
```

- Reloading requires two hands unless otherwise stated. If dual wielding with a Reload weapon, the other item must be sheathed or dropped to Reload. Remember that sheathing a weapon takes an Object Interaction

- Reload as a free object interaction means you reload as an object interaction. This feels like a free reload, and in most cases it is, but for example, if you are attempting to reload and open a door, you will only be able to do one.

- Reloading with an attack means you take an attack action, and during the attack, one of your attacks is used to instead reload. If you have 3 attacks, you attack once, use an attack to reload, then attack again.

- You must always reload your weapon before using it for a ranged weapon attack again. If your weapon was empty at the end of your turn, it must be reloaded at the start of your next turn.

- Anything which grants an Action, such as Haste or Action Surge, can be used to reload. Furthermore, a Rogue's Fast Hands can shorten an Action reload to a Bonus action.

- You have the choice of reloading your weapon with any of the options that are slower. For example, a crossbow master using a light crossbow is able to reload using a free object interaction, but can reload with a reaction, a bonus action, an attack, or an action. Also remember that despite how many options you have to reload, you are still limited by the number of attacks you have in your attack action.

##### Thrown
Thrown weapons are used to make a ranged attack by throwing them at the enemy, dealing their melee damage at range. They use Strength for attack and damage, unless the weapon has the Finesse property. When attacking enemies beyond the normal range or with an enemy within 5ft of you, you suffer disadvantage for that attack. As part of the attack, after throwing a Thrown weapon, you may draw another weapon. 

##### Trip
If your attack is successful, you can choose to deal only your Strength modifier in damage and your enemy must succeed on a Strength or Dexterity Saving Throw or be knocked prone. Enemies 1 size category larger than you gain advantage on this save. Enemies two size categories larger than you are immune to being tripped in this way.

##### Two Handed
This weapon requires two hands to wield, meaning your off hand cannot be used to wield another weapon, shield, or grapple. However, you may still use your off hand for somatic spell components. You can't attack with a two handed weapon if you have only one hand to wield it.

##### Versatile
This weapon may be used with one or two hands. When used with two hands, the weapon will have a higher damage potential, as well as other benefits from wielding a weapon with two hands. You may switch from two hands to one hand wielding the weapon at any time, and for any reason.


<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>


<img 
  src='https://i.imgur.com/sSwxUB5.png' 
  style='position:absolute; bottom:-0px; left:-70px; width:500px' />


<div class='pageNumber auto'></div>
<div class='footnote'>WEAPON PROPERTIES</div>
\page
## Armor

**Simple Training** with armor represents wearing the armor for basic protection but not necessarily knowing how to wear it properly, or how to correct the fit if certain plates are not tied correctly, worn too loosely or tightly, or the armor itself gets in your way as you don't know how to move with its articulations. You have disadvantage on any ability check, saving throw, or attack roll that involves Strength or Dexterity, and you can't cast spells.

**Martial Training** with armor means you know how to wear it properly, how to move with its articulations, and how to correct the fit. This is akin to normal proficiency.

**Master training** with armor represents wearing armor so effortlessly, you become accostomed to its encumberance. With light and medium armor, worn armor does not add to your encumberance, and with heavy armor, you only count half the weight. 

<div class='class'>
##### Light Armor
| Type | Base AC | Stealth | Weight | Gold Cost |
|:---|--:|:--:|--:|--:| 
| Padded  | 11 | Disadvantage | 4 | 5
| Leather  | 11 | None | 5 | 10 |
| Studded  | 12 | None | 6 | 45
| Lacquered  | 13 | None | 6 | 150
##### Medium Armor
| Type | Base AC | Stealth  | Weight | Gold Cost |
|:---|--:|:--:|--:|--:| 
| Chain Shirt  | 13 | Disadvantage | 10 | 50
| Ring Mail  | 14 | None | 12 | 100 |
| Breastplate | 15 | None | 10 | 300
| Banded Mail | 16 | Disadvantage | 20 | 500
##### Heavy Armor
| Type | Base AC | Stealth  | Weight | Gold Cost |
|:---|--:|:--:|--:|--:| 
| Hauberk  | 15 | Disadvantage | 25 | 150
| Scale Mail  | 16 | Disadvantage | 30 | 300 |
| Splint | 17 | Disadvantage | 33 | 750
| Plate | 18 | Disadvantage | 40 | 1500
</div>

### Feat: Light Armor Master
You are able to nimbly duck and dodge, and use your armor's light protection to cover your mistakes, deflecting blows that would have only barely hit you.

- Increase Dexterity score by 1 to a maximum of 20

- While you are wearing Light Armor, if you are subjected to an effect that allows you to make a Dexterity saving throw to take only half damage, you may use your reaction to instead take no damage if you succeed on the save. You still take full damage if you fail.

- While wearing light armor, all opportunity attacks against you suffer disadvantage

```
```

#### Light Armor
Light armor is made from cloth, leather, or other animal products and is usually less protective than the other armors but also provides the most mobility and least weight. You add your Dexterity modifier to AC when you wear Light Armor. You can don and doff Light armor in 1 minute.

- **Padded**  Thick padding made of quilted fabrics or furs, this armor provides little more than slight protection from incidental contact, and restricts the wearer's movement 

- **Leather** This leather is of moderate thickness but is unhardened and offers similar protection to padded, but the thinner material no longer restricts the wearer

- **Studded Leather** This leather thicker hard hide has been studded with metal rivets or brackets to offer some increased protection. The increased time to stud the leather while not damaging its integrity adds to the manufacturing cost. 

- **Lacquered Leather** This leather has been boiled in wax or water and painted with lacquer to toughen it as hard as modern plastics. It offers superior protection to other light armors without increasing weight, but the required skill to boil or otherwise harden leather without ruining it  adds to the cost.

<img 
  src='https://i.imgur.com/plvdJy4.png' 
  style='position:absolute; bottom:-60px; right:-60px; width:500px' />


<div class='pageNumber auto'></div>
<div class='footnote'>ARMOR</div>
\page

#### Medium armor 
This armor is a combination of leather or animal products and metal. It covers less than Heavy armor using the same materials and usually costs less due to a lighter manufacturing process and less material. You add up to +2 from your Dexterity modifer to AC when you wear medium armor. You can don medium armor in 5 minutes, while you can doff it in 1 minute. 

- **Chain Shirt** This is a shirt of butted mail. It is easy to produce, due to less time simply twisting chain rings into place, rather than welding each link closed. As such, the chain shirt offers less protection than the hauberk but is lighter and more affordable. 

- **Ring Mail** A series of closed rings stitched to a thick leather backing. This armor takes about as long as a Chain shirt to make and is similar in cost, but due to the combined protection of the leather backing and metal rings, offers greater protection than either one separately. Unfortunately, this combined armor is more restrictive.

- **Breastplate** Wearing just the breastplate of a suit of plate armor, this armor provides the easiest mobility of the medium armors and more protection than the chain shirt or ring mail. However, plate is expensive to make and thus has a greatly increased cost. 

- **Banded Mail** The quintessential half-plate, also known as lorica, this armor is a series of metal ribbons banded together to form more complete protection. Banded mail is cheaper to produce than full plate, but is still quite a process, involving many steel plates and precise shaping. 

### Feat: Medium Armor Master
Combining the mobility of light armor and the protection of heavy armor, your mobility and toughness are unmatched while wearing medium armor. 

- Increase Dexterity or Strength score by 1 to a maximum of 20

- Wearing medium armor doesn't impose disadvantage on your Dexterity (stealth) checks

- In response to a critical hit, you use your reaction to attempt a Dexterity saving throw against a DC of 10 or half the damage taken, whichever is higher. On success, you are resistant to non-magical bludgeoning, piercing or slashing damage for that attack. 


<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

```
```

#### Heavy
Heavy armor weighs and costs the most, but is the most protective, and most restrictive armor available. Heavy armors are made almost entirely of metal and require extensive, professional manufacturing. All heavy armor requires a Strength score of 13 to wear. You do not add your Dexterity modifier to AC when wearing heavy armor. Donning Heavy armor takes 10 minutes, while doffing it takes 5. If you have help, these values are cut in half. 

- **Hauberk** This is a full suit of chain armor made with riveted or welded rings, making the suit incredibly durable. The Hauberk covers both sleeves and stops at the knee, offering near complete coverage. Unfortunately, it is not silent in the least.

- **Scale** Taking chainmail and adding a scale to each ring gives a substantial increase to protection without much increase in the manufacturing process but adds quite a bit of weight. Scale armor is just as noisy to move around in as the Hauberk.

- **Splint** Splint armor can be described as the poor man’s plate. Instead of steel shaped to fit the wearer, a series of small, palm-sized plates and finger sized “splints” of metal are tied together to form a coat. It is cheaper to produce but is not nearly as durable. 

- **Plate** The essential Knight’s armor. Plate is extremely difficult and costly to produce, is the heaviest and most restrictive of all armor. However, no other armor is more protective. All parts of the body are covered, even the wearer's joints. 

### Feat: Heavy Armor Master
You are so adept at using the thick padding and stopping power of your armor that you absorb damage that would kill a more lightly armored combatant.

- Increase Strength score by 1 to a maximum of 20

- All bludgeoning, piercing, and slashing damage you receive from non-magical sources is reduced by an amount equal to your Proficiency Bonus.

- When an attacker that you can see deals non-magical bludgeoning, piercing or slashing to you, you can use your reaction to halve that damage against you.


> ##### Variant Weight
> As an option, your DM can elect to have all armor and shields for small creatures, such as halflings and gnomes, weigh half the amount presented here, and for armor and shields for large creatures, such as ogres and or horses weigh 4 times the amount.

<img 
  src='https://i.imgur.com/OHyahk6.png' 
  style='position:absolute; bottom:-260px; right:0px; width:1025px' />

<div class='pageNumber auto'></div>
<div class='footnote'>ARMOR</div>
\page


# Shields

<div class='wide'>

| Type | AC Bonus |Strength  |Stealth |Donning Action (strapped)| Donning Action (held) | Weight |  Cost
|:----|:--:|:--:|--:|--:|--:|--:|--:
| Buckler | 1 |N/A|None|Action | Use Object| 3| 5|
| Skirmish  | 2 |N/A|None|Action| Bonus Action | 6| 10
| Tower | 3 |13|Disadvantage|Action| Action |20| 50

</div>

**Simple Training** with shields gains a flat +1 shield bonus to AC, but suffers disadvantage to all Attack rolls and to all Strength and Dexterity checks.

A shield strapped on cannot be disarmed, while a shield held in the hand can be disarmed. 

### Feat: Shield Master
- If you take an attack action on your turn, you can use a bonus action to perform a shove action with your shield.

- If you aren't incapacitated, you can add your shield AC bonus to any dexterity saving throw you make against a spell or other harmful effect that targets only you.

- If you are subjected to an effect that allows you to make a Dexterity saving throw to take only half damage, you can use your reaction to take no damage if you succeed on the save, interposing your shield between yourself and the source of the effect.

##### Buckler
A buckler, or target shield, is a small shield that can be passive as a forearm guard, or as an active deflection shield. While it is strapped to the arm, that hand is counted as open. The master's deflect sets them up for the perfect counter.

||
|:--|:--|
| Martial | If you wield a weapon in the same hand as the buckler, you suffer -2 to Attack rolls with it. If you are wielding only the buckler in your off hand, it has Deflect (d8)|
| Master | You only suffer -1 to attack for wielding a weapon with the buckler hand. You may add the deflect roll from the buckler to any deflect roll you make with your main hand, and if this roll reduces incoming damage to 0, you may immediately make an attack against your attacker as part of the same reaction. |

<img 
  src='https://i.imgur.com/l1K72us.png' 
  style='position:absolute; bottom:-40px; right:-0px; width:850px' />
  
  ```
  ```

##### Skirmish 
Skirmish shields come in a variety of shapes but are about the size of the user's torso. You strap the shield to your forearm and grip it with your hand, or grasp it with a center grip, occupying your off hand. A Skirmish shield is large enough to provide better passive protection than the buckler, while still providing the agility missing with a tower shield. The Master can extend this agility to even spell attacks. 

||
|:--|:--|
| Martial | You gain an additional +2AC bonus against ranged weapon attacks, adding +4AC in total. |
| Master | You gain an additional +2AC bonus against ranged spell attacks, adding +4 in total, and a successful shove deals d4 + Strength modifier in bludgeoning damage.  |



##### Tower
This massive shield is as tall as you and just as wide; you more fight around it like a door than moving it with your body, like carrying a piece of mobile cover. The master shieldman can take cover with his shield as quickly as a ranger uses trees, effectively giving the enemy no target. 

||
|:--|:--|
| Martial | You negate any flanking bonus an enemy might have on you. Additionally, you may use your reaction to gain half cover, possibly negating an attack, or granting you a bonus to your dexterity saving throw before you roll.|
| Master | While using the shield as cover, if you are subjected to an effect that allows you to make a dexterity saving throw, and you fail that save, you take only half damage. |

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>




<div class='pageNumber auto'></div>
<div class='footnote'>ARMOR</div>
\page


# Ambush Weapons
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
|Punch Dagger|Piercing or Slashing|d4|d4|d4|1|1
|Whip Dagger|Piercing|d4|d4|d4|3|15
|Gauntlet|Bludgeoning, Piercing, or Slashing|d2|d4|Damage Scales|1|10
|Hidden Blade|Piercing|d4|d4|d4|1|50
|Interceptor|N/A|N/A|N/A|N/A| 1|3
|Knuckle Axe|Slashing|d4|d6|d6|1|25
|Side Baton|Bludgeoning|d4|d6|d8|2|10
|Unarmed Strike|Bludgeoning|d1|d4|Damage Scales|0|0


</div>

### Feat: Ambush Weapons Master
- +1 to attack rolls with ambush weapons
- A successful hit to a creature that is surprised is a critical hit
- You may use your reaction to make a single attack against a creature that has missed you with a melee attack.

##### Punch Dagger
A punching blade is a small knife attached to a horizontal handle that projects out from the fist when held; but also includes wrist or fist mounted blades such as claws or daggers which extend out over the knuckles when equipped. A master takes any opening to attack with his main weapon and a quick punching stab at the same time.

||
|:--|:--|
| Simple | One Handed, Melee d4, Conceal, Finesse, Light |
| Martial | One Handed, Melee d4, Conceal, Finesse, Light, Penetrate |
| Master | One Handed, Melee d4, Conceal, Finesse, Light, Penetrate |
| Master Perk | You have advantage on opportunity attacks made with this weapon. Additionally, if this weapon is in your off hand, you may make an opportunity attack with your main hand and this weapon. |

```
```

##### Whip Dagger
A dagger with a ring pommel at the end of a silk ribbon. The weapon can be used like a dagger in hand to attack creatures up to 5ft away, or swung about the end of the ribbon to attack creatures up to 10ft away. A master has learned the Scorpion Pull, an ability to impale a target and pull them closer with the attached ribbon. 

||
|:--|:--|
| Simple | Two Handed, Melee d4, Conceal, Awkward, Finesse, Reach |
| Martial | Two Handed, Melee d4, Conceal, Entangle, Finesse, Reach |
| Master | One Handed, Melee d4, Conceal, Entangle, Finesse, Lunge, Reach |
| Master Perk | When your attack is successful, as a Bonus Action, you can choose to force the enemy to succeed on a Strength saving throw or be pulled up to 10ft toward you. |

<img 
  src='https://i.imgur.com/nKe2lWe.png' 
  style='position:absolute; bottom:0px; right:-50px; width:1000px' />

<div class='pageNumber auto'></div>
<div class='footnote'>AMBUSH WEAPONS</div>
\page




##### Gauntlet
A guantlet is spiked or weighted knuckles or claws worn as a glove, however, heavy armor hands are not weighted enough to count. Putting on or taking off your gauntlets is an action, and they cannot be disarmed. A master's damage scales like Unarmed Strike, and can catch the enemy’s weapon on a miss, even attempting to bind and disarm the weapon in response to being hit. 

||
|:--|:--|
| Simple | One Handed, Melee d2 |
| Martial | One Handed, Melee d4 |
| Master | One Handed, Melee (table), Light |
| Master Perk | When you are hit with a melee attack, as a reaction before the damage, you can attempt a disarm attack. If you are successful, you take no damage, but if you are unsuccessful, you take damage as normal|

##### Hidden Blade

This infamous weapon is a mechanical means to deploy a piercing dagger from under your wrist as part of an attack.  The hand this weapon is equipped to is open, allowing it to wield a weapon, shield, grapple, or perform somatic components for a spell. However, you can’t deploy a hidden blade into a hand that is holding something else. This weapon cannot be disarmed but takes an action to equip or remove. A hidden blade master has mastered the surprise attack with this assassin's weapon.

The master can take full advantage of a surprise attack, ending a life as quickly as the battle starts. 

||
|:--|:--|
| Simple | One Handed, Melee d4, Awkward, Conceal, Finesse, Light |
| Martial | One Handed, Melee d4, Conceal, Finesse, Light |
| Master | One Handed, Melee d4, Conceal, Finesse, Light |
| Master Perk | Any hit against a surprised creature takes maximum damage from this weapon and any attachers such as sneak attack, instead of rolling for the damage. |



##### Interceptor

Interceptor is a generic term for any article of clothing which is used to deflect or intercept attacks, such as a thick wool cloak, silk scarf, war fan or umbrella. These are not weapons in the traditional sense, just durable personal effects, but can be just as effective in a duel as steel. 

Wielding an interceptor gives you +1 AC in addition to the effects below. The master can use an interceptor to catch missile weapons in flight before they strike, even for an ally.

||
|:--|:--|
|Simple| You cannot wield an interceptor with simple training. 
|Martial| One Handed, Conceal, Deflect (d8), Finesse, Light|
|Master|One Handed, Conceal, Deflect (d8), Disarm, Entangle, Finesse, Light, Trip|
|Master Perk| You may use the Deflect property against flight weapons. When a creature you can see attacks a target that is within 5 feet of you, you can use your reaction to impose disadvantage on the attack roll.

```
```

##### Knuckle Axe
Designed much like brass knuckles, but with a blade that sweeps back toward the forearm, over the side of the fist. The knuckle axe resembles an axe head with no handle, and either 4 finger holes or a curved handle to rest inside a closed fist. Masters with knuckle axes learn to slash through soft targets much like a real axe, attacking two targets at once. 

||
|:--|:--|
| Simple | One Handed, Melee d4, Awkward, Light |
| Martial | One Handed, Melee d6, Deflect, Light |
| Master | One Handed, Melee d6, Deflect, Light |
| Master Perk | When you score a critical hit, make an additional melee attack to another creature adjacent to you as part of the same action. |

##### Side Baton
Often called a Tonfa, Riot Baton, or Arm Club, the Side Baton is a defensive weapon designed for deflecting attacks with one's own forearm. It is a stout club with a perpendicular handle attached a third of the way down the length, allowing it to be swing out for a swipe, or extend the reach of a thrust. A master may also flip the side baton and grab it by the long end to use the handle as a hook in combat.

||
|:--|:--|
| Simple | One Handed, Melee d4, Light |
| Martial | One Handed, Melee d6, Deflect, Light |
| Master | One Handed, Melee d8, Deflect, Light, Trip |
| Master Perk | Your deflect roll is 2d10, rather than d8, and you may add your proficiency to this roll |


<div class='pageNumber auto'></div>
<div class='footnote'>AMBUSH WEAPONS</div>

##### Unarmed Strikes
A creature with simple training can throw basic punches that are largely ineffective, while a creature with martial training can properly land punches and kicks, doing small amounts of damage. A master of unarmed strikes is as well trained as a traditional monk, though lacking the ki focus and mysticism the monk possesses. Your damage scales according to your proficiency bonus on to the table below. 

Your unarmed strikes do not count as weapon attacks until you have master training with them.

||
|:--|:--|
| Simple | One handed, Melee d1, Awkward |
| Martial | One handed, Melee d4, Finesse |
| Master | One handed, Melee Table, Deflect, Disarm, Finesse, Light, Trip |
| Master Perk | You may use your bonus action to perform a shove or disarm attack.

|Proficiency| Damage Die
|:--:|:--:|
| +2 | d4 |
| +3 | d6 |
| +5 | d8 |
| +6 | d10 |

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)
  </div>

```
```

<div class='pageNumber auto'></div>
<div class='footnote'>AMBUSH WEAPONS</div>

\page



# Axes
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
| Battle Axe | Slashing |d8|d8 (d10)|d10 (d12)|4|10
| Greataxe |Slashing|d10|d12|2d8|6|30
| Halberd |Piercing, Slashing|d10|2d6|3d4|7|35
| Handaxe |Slashing|d6|d6|d6|2|5
| Hook Sword| Slashing|d6|d6|d6|2| 60
| Khopesh | Slashing or Piercing| d8|2d4|2d4|3|10
| Poleaxe |Bludgeoning, Piercing, Slashing|d10|d10|2d6|7|40
| Tomahawk | Slashing, Piercing|d4|d4|d4|1|1
</div>

### Feat: Axe Master
- +1 to attack rolls with axes
- On your turn, when you score a critical hit or reduce a target to 0 hit points with an axe, you can make another attack as part of the same action. This effect can happen multiple times as long as the criteria are met. 
- Before you make a melee attack, you can choose to take a -5 penalty to the attack roll. If the attack hits, you add +10 to the attack's damage. 
- You count as one size category larger for the purpose of weapon properties, such as trip or disarm. 

##### Battle Axe 

This is an axe about 2ft-3ft in length, with a longer beard designed for a wider slashing wound. This weapon is large enough to use with two hands for more powerful strikes, yet nimble enough to be used in one hand. Masters with the battle axe get more reliable damage out of the weapon.

||
|:--|:--|
| Simple | Two Handed, Melee d8, Awkward |
| Martial | One Handed, Melee d8, Trip, Versatile d10|
| Master | One Handed, Melee d10,Trip, Versatile d12|
|Master Perk|Reroll a damage dice result of 1 or 2 for both weapon damage and any attachers such as Smite|

##### Greataxe
The greataxe is the classic barbarian axe but also includes more historical versions such as the bardiche, voulge, or Dane axe. The greataxe has incredible potential for damage, and the master greataxe wielder can fell even the stoutest of foes with reliability not seen in many other weapon styles.

||
|:--|:--|
| Simple | Two Handed, Melee d10, Awkward, Heavy |
| Martial | Two Handed, Melee d12, Disarm, Heavy, Trip |
| Master | Two Handed, Melee 2d8, Disarm, Heavy, Trip |
| Master Perk | When you roll at least 5 higher than the enemy's AC, you can roll all damage and any modifiers twice and take the better result.   |




```
```
<img 
  src='https://i.imgur.com/KvAA4b0.png' 
  style='position:absolute; bottom:-20px; right:-60px; width:500px' />

<div class='pageNumber auto'></div>
<div class='footnote'>AXES</div>
\page

##### Halberd
The halberd consists of an axe blade topped with a spike mounted on an 8ft long shaft. It has a hook on the back side of the axe blade for grappling mounted combatants. With at least martial proficiency, a halberd can be used to perform a trip against mounted foes to pull them from the saddle to a prone position, and the master has advantage on this maneuver. Additionally, a master can entangle, but not trip, a creature up to two category sizes larger than them.

||
|:--|:--|
| Simple | Two Handed , Melee d10, Awkward, Brace, Heavy |
| Martial | Two Handed, Melee 2d6, Brace, Heavy, Reach, Trip |
| Master | Two Handed, Melee 3d4, Brace, Entangle, Heavy, Reach, Trip |
| Master Perk | You gain advantage on trip attacks made to mounted enemies and Large creautres. If your trip is successful against a mounted foe, it is automatically pulled from its mount to a prone position. You gain advantage on entangle attacks made against enemies two size categories larger than you. |

##### Handaxe
An incredibly versatile weapon and tool, the hand axe can be thrown, or used in melee, and can be used to trip your foe. The master learns the ability to bind and disarm. 

||
|:--|:--|
| Simple | One Handed, Melee d6, Thrown (10/30) |
| Martial | One Handed, Melee d6, Thrown (20/60), Light, Trip |
| Master | One Handed, Melee d6, Thrown (20/60), Disarm, Light, Trip |
| Master Perk | You gain advantage on all disarm attacks. |

##### Hook Sword
The hook sword is an exotic weapon made famous by the northern Chinese masters. It is a shortsword length weapon in which the tip forms a prominent hook, and which the knuckle guard features a crescent shaped blade. A hook sword can easily catch weapons and limbs, giving it superior control over an enemy's movements.

The master can also hook with another hook sword for a unique means of trapping and binding enemies, as well as striking further by forming a makeshift flail; letting go of one hook sword and swinging it by the hook of the other sword you are currently holding. 

||
|:--|:--|
| Simple | One Handed, Melee d6, Awkward |
| Martial | One Handed, Melee d6, Deflect, Disarm, Finesse, Light, Trip |
| Master | One Handed, Melee d6, Deflect, Disarm, Finesse, Light, Entangle, Lunge, Trip|
| Master Perk | When you are hit with a melee weapon attack, as a reaction you can make a disarm or entangle attack against that enemy. While dual wielding two hook swords, you have reach and a lunge does not use your reaction. |


```
```

##### Khopesh
This axe sword hybrid was made famous by ancient Egyptians. It is a sword built with a large crescent shaped protrusion about one third from the tip, and a hooked tip, forming a sort of question mark shape. It acts similarly to a battle axe, but is lighter and can more reliably cut with a larger surface area. A Master with the Khopesh has learned to use the hooked point to drag or trip enemies to the ground with ease.

||
|:--|:--|
| Simple | One Handed, Melee d8, Awkward, Disarm |
| Martial | One Handed, Melee 2d4, Disarm, Light, Trip |
| Master | One Handed, Melee 2d4, Disarm, Light, Trip |
| Master Perk | When you make a trip attack, if you hit, even if they save against the attempt, your enemy's speed is reduced by 10ft until the end of their next turn. While they have this penalty, they have disadvantage saving throws against a trip attack. |


##### Poleaxe
A Poleaxe is an infantry weapon designed for use against armored foes. It is characterized by an axe on one side and a hammer on the other, while tipped with a dagger-like spike from the top. It is typically on a 6 ft haft, shod with iron to protect it from damage. Though not long enough for a reach weapon, its style resembles that of a quarterstaff and axe combined. A master learns to use the weapon's iron shodding more actively, blocking attacks that would normally chop through the wood shaft.

||
|:--|:--|
| Simple | Two Handed, Melee d10, Awkward, Heavy |
| Martial | Two Handed, Melee d10, Brace, Deflect, Heavy, Penetrate, Trip |
| Master | Two Handed, Melee 2d6, Brace, Deflect, Heavy, Penetrate, Trip |
| Master Perk | While wielding a poleaxe, you gain +1 AC and you may add your proficiency bonus to deflect rolls.|

##### Tomahawk
The Tomahawk was invented and made famous by indigenous North Americans, and featured a slimmer blade more balanced for throwing, and an opposing spike or small hammer so that even if the axe blade missed, there was still a chance the weapon could deal some damage. 

Tomahawks are balanced for throwing further distances than any other axe, and the master has learned to throw them with great force, using the hammer or spike's weight to drive the thinner axe head deeper into a target. 

||
|:--|:--|
| Simple | One Handed, Melee d4, Awkward, Thrown (10/30) |
| Martial | One Handed, Melee d4, Thrown (40/120), Finesse, Light, Trip |
| Master | One Handed, Melee d4, Thrown (40/120), Disarm, Finesse, Light, Trip |
| Master Perk | You can choose to take a -5 penalty to a ranged attack roll. If the attack hits, you add +10 to the attack's damage.


<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>




<div class='pageNumber auto'></div>
<div class='footnote'>AXES</div>


\page

# Bludgeons
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
| Greatclub | Bludgeoning |d8|d8|d10|8|0.2
| Heavy Club | Bludgeoning |d6|d6|d8 (d10)|3|0.1
| Light Club | Bludgeoning |d4|d4|d6|2|0.1
| Bar Mace | Bludgeoning, Piercing|d6|d8|d8|3|3
| Flanged Mace | Bludgeoning and Slashing |d6|d6|d8|4|5
| Mallet | Bludgeoning| d8|d8|d8|3|0.3
| Morningstar | Bludgeoning and Piercing |d8|d10|d12 [d4]|6|15
| Quarterstaff | Bludgeoning |d6|d8 [d6]|d8  [d8]|3|0.5|

</div>

### Feat: Bludgeon Master
- +1 to attack rolls made with bludgeons
- When you score a critical hit, your enemy must succeed on a Constitution Saving Throw or be stunned until the end of your next round
- If you deal more damage in a single attack than the enemy's AC, the enemy must succeed on a constitution saving throw or take a level of exhaustion. You may grant two levels of exhaustion per enemy in this way. 

##### Greatclub
The greatclub is simply a heavy, two-handed club, though it can be refined like the Japanese Tetsubo. A master of the greatclub can render a weapon nearly useless.

||
|:--|:--|
| Simple | Two Handed, Melee d8, Heavy |
| Martial | Two Handed, Melee d8, Disarm, Penetrate, Heavy |
| Master | Two Handed, Melee d10, Deflect, Disarm, Penetrate, Heavy |
| Master Perk | If you are successful in a disarm attempt, the enemy can no longer add proficiency to <br>attacks with that weapon. |

##### Heavy Club
A heavy club is a larger mass weapon, much <br>like a bat or ball mace. A master can target <br>the foe's head more easily, giving stuns<br> that the opponent can't shake off as quickly. 

||
|:--|:--|
| Simple | Two Handed, Melee d6|
| Martial | One Handed, Melee d6,<br> Thrown (10/30) |
| Master | One Handed, Melee d8, Versatile d10, Thrown (20/40) |
| Master Perk | When you score a critical hit, <br>your enemy is stunned for d4 <br>rounds. At the end of each of<br> its turns, your stunned enemy<br> can attempt a Constitution<br> saving throw, ending the<br> effect on a success. |







<img 
  src='https://i.imgur.com/1zzsXjn.png' 
  style='position:absolute; bottom:-0px; right:-140px; width:750px' />

<div class='pageNumber auto'></div>
<div class='footnote'>BLUDGEONS</div>
\page




##### Light Club
A light club might be a simple sap or a metal bar, and many clubs designed for combat are designed to be thrown. A master learns to be extremely accurate to a foe's head and knock them off balance. 

||
|:--|:--|
| Simple | One Handed, Melee d4, Conceal, Finesse, Light |
| Martial | One Handed, Melee d4, Conceal, Thrown (20/60), Finesse, Light |
| Master | One Handed, Melee d6, Conceal, Thrown (20/60), Finesse, Light |
| Master Perk | On hit, you can choose to deal only your Strength modifier in damage but your foe must succeed on a Constitution saving throw or suffer disadvantage to its Saving Throws until the end of your next turn.  |


##### Bar Mace
A bar mace is a stout iron bar lined with spikes or flanges to increase its damage and threat. Designed for low skilled military soldiers, a master with the bar mace has learned to use the weight and odd angles to pry weapons from their enemy's hands, or ruin them in the process.

||
|:--|:--|
| Simple | Two Handed, Melee d6, Disarm |
| Martial | One Handed, Melee d8, Disarm|
| Master | One Handed, Melee d8, Deflect, Disarm |
| Master Perk | If you successfully Disarm, your enemy has disadvantage on melee attacks. At the end of its turn, it can attempt a Constitution saving throw, ending this effect on a success. You can apply this effect to any creature on a success regardless of if it is wielding a weapon.



##### Flanged Mace
A mace is made up of a metal head with small bladed protrusions, attached to a simple wooden or metal shaft, designed specifically to hammer and shred armored enemies. This weapon deals slashing and bludgeoning damage at the same time, for the purpose of overcoming resistances or immunities. Masters with maces learn to punch through armor to damage those foes with ease.

||
|:--|:--|
| Simple | One Handed, Melee d6|
| Martial | One Handed, Melee d6, Light, Penetrate|
| Master | One Handed, Melee d8, Light, Penetrate|
| Master Perk | Your penetrate affects creatures in any armor. You may also add your strength modifier twice to Penetrate damage totals |

```
```

##### Mallet
A mallet is typically a crafter's tool, but can be repurposed for war. It consists of a wood haft inset within a large wooden cylinder. The wood construction means the mallet can be wide and soft, allowing for creative attacks in combat. A master can use the lightness of a mallet for a quick strike that sends the enemy reeling.

||
|:--|:--|
| Simple | One Handed, Melee d8, Light|
| Martial | One Handed, Melee d8, Thrown (20/60), Disarm, Light|
| Master | One Handed, Melee d8, Thrown (30/90), Disarm, Light  |
| Master Perk | As a bonus action, you can make a shove attempt which, if successful, deals bludgeoning damage equal to your strength modifier. 

##### Morningstar
This is an infantry weapon in the form of a thick wooden shaft up to 8 feet in length, slightly fluted toward the top, with a spiked head and topped with a stout iron spike. This weapon deals piercing  and bludgeoning damage at the same time, for the purpose of overcoming resistances or immunities. A master with a morning star can absolutely ruin armor, rendering it less effective for its wearer. 

||
|:--|:--|
| Simple | Two Handed, Melee d8|
| Martial | Two Handed, Melee d10, Brace, Penetrate, Reach |
| Master | Two Handed, Melee d12, Brace, Double Ended d4, Penetrate, Reach |
| Master Perk | Before you roll an attack, you can choose to take a -5 to the roll. On hit, you deal piercing damage equal to your strength modifier, but reduce the enemy's AC by the same amount.|


##### Quarterstaff
The simple staff is a useful Double Ended bludgeoning weapon, whether shod and weighted like the English quarterstaff, or simply made of strong bamboo, like the Japanese bo. A master learns to to strike with both ends as fast as a lesser trained combatant can with one end. 

||
|:--|:--|
| Simple | Two Handed, Melee d6|
| Martial | Two Handed, Melee d8, Double Ended d6 |
| Master | Two Handed, Melee d8, Double Ended d8 |
| Master Perk | You gain +1 AC while wielding this weapon. Additionally, you may use Double Ended when making an Opportunity Attack, making two attacks instead of one. |

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)
</div>

<div class='pageNumber auto'></div>

\page
# Bows and Slings
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost|
|:--|:--|:--:|:--:|:--:|--:|--:|--:
| Bladed Bow | Piercing or Slashing |d8|d6, d8| [d6], d8|5|100|
| Compound | Piercing | d10|d10|d12|3|500
| Greatbow | Piercing |d10|d10|d12|5|75|
| Longbow | Piercing |d8|d8|d10|2|50|
| Recurve | Piercing |d8|2d4|2d4|2|150|
| Shortbow | Piercing |d6|d6|d8|2|25|
| Sling | Bludgeoning |d4|d4|d6|0|0.1|
| Wrist Shot | Bludgeoning or Slashing |d4|d6|d6|1|5|

</div>

### Feat: Bow and Sling Master
- Attacking at long range doesn't impose disadvantage on your ranged weapon attack rolls.
- Your attacks ignore half and three quarters cover
- You can overdraw your shot, making the shot less accurate, but more powerful. Before you make a ranged attack with a ranged weapon with which you are proficient, you can choose to take a -5 penalty to the attack roll. If you do so and the attack hits, it deals +10 damage. 

##### Bladed Bow
A bladed bow has two curved blades affixed to its limbs. Though not nearly as stout as a quarterstaff due to the flexibility of the bow itself, it is nonetheless an easy way to protect yourself when the enemy closes. The bladed bow is very specialized and requires dedicated training to be anything but clumsy.  In the hands of a master, the bladed bow is as dangerous as a dual wielder. 

||
|:--|:--|
| Simple | Two Handed, Ranged d8 (100/500), Awkward, Heavy |
| Martial | Two Handed, Ranged d8 (120/600), Melee d6, Finesse, Heavy |
| Master | Two Handed, Ranged d8 (120/600), Melee d6, Double Ended d6, Finesse, Heavy |
| Master Perk | You may add your ability modifier to damage rolls made with Double Ended|

```
```
##### Compound Bow
A compound bow is about the size of a shortbow, but consists of two pulleys on its steel limbs which allow the user to load exponentially more force. Because of the added mechanical aspect, loading is a bit slower than loading a longbow. But, its stopping power punches like a Greatbow. A master with the Compound can overdraw the impressive power of the Compound for devastating effect.

||
|:--|:--|
| Simple | Two Handed, Ranged d10 (100/500), Awkward, Penetrate, Reload Reaction |
| Martial | Two Handed, Ranged d10 (200/800), Penetrate, Reload Free Object|
| Master | Two Handed, Ranged d12 (200/800), Penetrate, Reload Part of Attack|
| Master Perk | When you overdraw, you take the normal -5 to attack, but if you hit, you deal damage to your primary target, and one other target in a straight line from you that intersects your first target. |


<img 
  src='https://i.imgur.com/JQKowCl.png' 
  style='position:absolute; bottom:-270px; right:-120px; width:900px' />


<div class='pageNumber auto'></div>
<div class='footnote'>BOWS AND SLINGS</div>
\page

##### Greatbow
A greatbow is a bow much taller and stouter than the longbow, and fires specialized great arrows that are similar in size to a javelin. Due to its size, javelins and ballista bolts can be used as ammunition, but with disadvantage on the attack. Greatbow masters have learned to overdraw the stout poundage, sending enemies flying back. You must have a Strength score of at least 13 to wield a Greatbow.

||
|:--|:--|
| Simple | Two Handed, Ranged d10 (100/500), Awkward, Heavy |
| Martial | Two Handed, Ranged d10 (200/800), Heavy |
| Master | Two Handed, Ranged d12 (200/800), Heavy |
| Master Perk | When you score a critical hit, your enemy must succeed on a strength saving throw or be shoved 5ft in a straight line away from you and knocked prone. Large creatures have advantage on this save, and larger creatures are immune. Creatures that are flying have disadvantage on this save. |

##### Longbow
A longbow has a larger power stroke than a shortbow, meaning the arrow is drawn further and has a higher draw weight. This, combined with the larger size, usually 5ft-6ft long, mean the bow is much more powerful, but perhaps a bit more cumbersome in close combat and atop a mount. A master with a longbow has learned to steady his aim and ignore all distractions impeding accuracy.

||
|:--|:--|
| Simple | Two Handed, Ranged d8 (100/500), Awkward, Heavy |
| Martial | Two Handed, Ranged d8 (120/600), Heavy |
| Master | Two Handed, Ranged d10 (120/600), Heavy |
| Master Perk | If you suffer disadvantage for any reason, you can use your reaction to attempt a concentration check against DC10 or half your target's AC, whichever is higher. If you succeed, your disadvantage is negated. |


##### Recurve
A recurve bow is usually shorter, in the 3ft-4ft range, but has a greater power stroke than a bow of its size. Due to the shorter overall size but higher draw, the master can load an extra arrow into the recurve and attack two different targets, though with far less accuracy than one.

||
|:--|:--|
| Simple | Two Handed, Ranged d8 (100/500) |
| Martial | Two Handed, Ranged 2d4 (120/600)|
| Master | Two Handed, Ranged 2d4 (120/600)|
| Master Perk | You can loose two arrows at the same time. You must choose two targets within your normal range that are within 5 ft of one another, but may attack each target separately with the same attack. These attacks suffer disadvantage that cannot be removed.  |

```
```
##### Shortbow
A short bow is about 3 feet in length and usually very portable. It is more suited to close combat, as its smaller size lends itself to agile movement and quick targeting on either side of the body. 

||
|:--|:--|
| Simple | Two Handed, Ranged d6 (60/240) |
| Martial | Two Handed, Ranged d6 (80/320) |
| Master | Two Handed, Ranged d8 (80/320)|
| Master Perk | You threaten 5ft around you and can make a ranged opportunity attack when an enemy leaves your threatened space. You do not have disadvantage to ranged attacks if an enemy is within 5ft of you.  |


##### Sling
A sling is a simple leather cup with cords that allow the user to launch rounded bullets with circular momentum. One of the oldest ranged weapons known, it is both simple and effective at delivering a crushing blow at medium range. You can use rounded stones or small bits of anything that can fit into the leather cup, though these attacks are made with -1 to the attack roll. A master learns to over swing, instead of over drawing, and can disable and disorient an enemy with precise stones to the head.

||
|:--|:--|
| Simple | One Handed, Conceal, Ranged d4 (30/120) |
| Martial | One Handed, Conceal, Disarm, Ranged d4 (30/120) |
| Master | One Handed, Conceal, Disarm, Entangle, Melee d6, Ranged d6 (30/120), Light, Trip |
| Master Perk | You can take -5 to the attack roll to hurl with extra strength, and on hit, the target must succeed on a Constitution saving throw or have disadvantage to attacks until the end of its next turn.|


##### Wrist Shot
Using stretchable or spring loaded materials, the wrist shot shoots rounded bullets much like a sling, though uses the power of elasticity of the material rather than gathered circular momentum. Because of this added stability in flight, you may also use flat, bladed disks as ammunition. You can use debris or rounded stones as ammunition, but this causes a -1 penalty to your attack roll. Masters with wrist shots can bounce shots around corners and off hard surfaces to attack unseen enemies in cover. 

||
|:--|:--|
| Simple | Two Handed, Ranged d4 (40/160), Awkward |
| Martial | Two Handed, Ranged d4 (40/160) |
| Master | Two Handed, Ranged d6 (40/160) |
| Master Perk | You can measure distance from yourself to a single DM approved obstacle, and then to your target. If that range is within your long distance, you can ignore any cover the enemy has. You can bounce twice, but this attack is made with disadvantage. |

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

<div class='pageNumber auto'></div>
<div class='footnote'>BOWS AND SLINGS</div>



\page



# Combat Blades

<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
| Bastard Sword | Piercing or Slashing |d10|d12|d12 (2d6)|4|40
| Broadsword | Piercing or Slashing |d8|2d4|3d4|3|20
| Greatsword | Piercing or Slashing |2d6|2d8|2d10|5|50
| Katana | Piercing or Slashing |d6|d6(d8)|d8(d10)|2|10
| Longsword | Piercing or Slashing |d8|d8 (d10)|d10 (d12)|3|15
| Montante | Piercing or Slashing |2d6|2d6|3d6|5|75
| Scimitar | Slashing |d6|d6|d8|2.5|25
| Short Glaive | Piercing or Slashing |d8|2d4|2d4|4|45

</div>


### Feat: Combat Blade Master
- +1 to attack rolls with combat blades
- On your turn, you can use your reaction to assume a parrying stance. Until your next turn or until you are no longer holding a Combat Blade, you gain a +2 to your AC against melee weapon or melee spell attacks that target you.
- You have advantage on opportunity attacks


##### Bastard Sword
The Bastard Sword is the child of the Longsword and the Greatsword, a weapon in length between the two that uses techniques from either parent. A master of the Bastard Sword learns to deal greater damage against larger targets, using the weapon’s leverage to create more powerful strikes, and also some deft precision with the tip much like a Longsword. 

||
|:--|:--|
| Simple | Two Handed, Melee d10, Awkward, Heavy |
| Martial | Two Handed, Melee d12, Heavy |
| Master | One Handed, Melee d12, Heavy, Versatile 2d6 |
| Master Perk | Your Critical hit range is 19-20, unless it is 18-20. Against category size Large and larger enemies, your damage is 2d8(2d10) instead of d12(2d6).|


##### Broadsword
True broadswords have a wider, thicker blade to add power to the blow, and often have a single edge to give more weight to the blade, like the Falchion, Messer, Seax, or Chinese Dadao. Because of this the weapon performs much like an axe in the strike. A master learns to strike truer, dealing more damage to soft targets.

||
|:--|:--|
| Simple | One Handed, Melee d8, Awkward |
| Martial | One Handed, Melee, 2d4, Penetrate |
| Master | One Handed, Melee 3d4, Penetrate |
| Master Perk | When you score a critical hit, triple your Strength modifier to damage, and make one additional attack as part of the same action. This effect can only happen once during your turn.|



<img 
  src='https://i.imgur.com/BN1oMMB.png' 
  style='position:absolute; bottom:0px; right:-80px; width:550px' />

<div class='pageNumber auto'></div>
<div class='footnote'>COMBAT BLADES</div>
\page



##### Greatsword

The greatsword is often as tall as its wielder, spanning in the 5ft-6ft range with a 2ft handle. The long blade, wide handle, and added weight make the greatsword one of the most damaging melee weapons in use, and can easily dispatch larger monsters with ease.  A master finds the greatest weapon to use against a large enemy is the greatsword. 

||
|:--|:--|
| Simple | Two Handed, Melee 2d6, Awkward, Heavy |
| Martial | Two Handed, Melee 2d8, Heavy|
| Master | Two Handed, Melee 2d10, Heavy|
| Master Perk | Against category size Large and larger enemies, your damage is 2d12, instead of 2d10 |

##### Katana
The Katana, made famous by the Japanese, is a single edged, slightly curved sword with a minimal guard called a tsuba and a longer handle than western or middle eastern swords. The longer handle and curved edge provide different leverage and more effective deflections. A master can dual wield with a Katana deflecting two attacks, or with two hands to a single katana, deflect even powerful blows with ease.

||
|:--|:--|
| Simple | Two Handed, Melee d6, Awkward |
| Martial | One Handed, Melee d6, Finesse, Light, Versatile d8|
| Master | One Handed, Melee d8, Deflect, Finesse, Light, Versatile d10 |
| Master Perk | While wielding this weapon with two hands, your deflect dice becomes 2d10. With one hand, you may add your proficiency bonus to your deflect rolls|

##### Longsword
The longsword is a multipurpose cutting and thrusting weapon, with a wide guard for dueling, and includes the cruciform fencing sword, along with similar western european weapons. Generally, the blade is between 3ft-4ft, with a 10"-12" handle. Masters learn to become more rapier-like with the point, and with increased weight of this weapon, learn devestating blows at critical strikes. 

||
|:--|:--|
| Simple | Two Handed, Melee d8, Awkward |
| Martial | One Handed, Melee d8, Disarm, Versatile d10 |
| Master | One Handed, Melee d10, Disarm, Finesse, Versatile d12|
| Master Perk | Your Critical hit range is 18-20.|



```
```

##### Montante
The Montante was a type of greatsword made famous by western Europeans, prized for its reach and seen as the perfect weapon against multiple assailants. It is similar in length to a polearm, has similar reach and can even use similar techniques thanks to a smaller handle above the crossguard called a ricasso, just without the ability to brace as many polearms do. The Master has learned to use the parrying hooks to great effect, keeping themselves safe from attacks with clever use of the guard. 

||
|:--|:--|
| Simple | Two Handed, Melee 2d6, Awkward, Heavy |
| Martial | Two Handed, Melee 2d6, Heavy, Reach |
| Master | Two Handed, Melee 3d6, Heavy, Reach |
| Master Perk | You have +1 AC while wielding this weapon, and you negate any flanking bonus any enemy might have for flanking you or having the enemy's ally near you, such as pack tactics or sneak attack. |


##### Scimitar
A single-handed, curved sword, similar in dimension to the longsword.  Unfortunately, unlike the longsword, the scimitar is usually fitted with a handle too small to allow two-handed wielding, but the master learns to use the curve as a means to deflect and is an expert at using the curve while mounted.


||
|:--|:--|
| Simple | One Handed, Melee d6, Awkward |
| Martial | One Handed, Melee d6, Finesse, Light |
| Master | One Handed, Melee d8, Deflect, Finesse, Light |
| Master Perk | When you choose to deflect, you may roll twice and take the better result. Additionally, if you travel at least 20ft before you make an attack, your weapon deals an additional 2d8 slashing damage.|


##### Short Glaive
A short glaive is a glaive weapon with a shorter handle, usually in the range of length of a greatsword, but much lighter as the metal blade is smaller and most of the weapon is wooden haft. A short glaive is favored among elven armies as an effective long weapon that is both heavy hitting and light enough to use with finesse. Masters of the short glaive find the weapon can swing through soft targets, converting the momentum into another attack if they’re lucky. 

||
|:--|:--|
| Simple | Two Handed, Melee d8, Awkward |
| Martial | Two Handed, Melee 2d4, Finesse, Lunge |
| Master | Two Handed, Melee 2d4, Brace, Finesse, Lunge |
| Master Perk | If an enemy misses you with a melee attack, you can use your reaction to make a melee attack against that enemy.  |


<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)
</div>


<div class='pageNumber auto'></div>
<div class='footnote'>COMBAT BLADES</div>
\page


# Crossbows
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost|
|:--|:--|:--:|:--:|:--:|--:|--:|--:
| Blowgun | Piercing |d1|d2|d4|1|1|
| Hand Crossbow | Piercing |d6+1|d6+1|d6+1|2|75|
| Heavy Crossbow | Piercing |d10+3|d10+3|d10+3|8|50|
| Hidden Crossbow| Piercing|d4|d4|d4|1|150|
| Light Crossbow | Piercing |d8+2|d8+2|d8+2|5|50|
| Mauler | Piercing |3d4|3d4|3d4|6|100|
| Portable Ballista|Piercing|d12+4|d12+4|d12+4|15|1500|
| Spinner | Slashing | 2d4 | 2d4 | 2d4| 2| 100

</div>

### Feat: Crossbow Master
- If a target is within 10ft of you, you can choose another target within your crossbow's normal range in a straight line from you through your first target, and to the second. If you hit the closer target, you can also roll to attack the further target for free, hitting both targets with the same piece of ammunition.
- Being within 5ft of a hostile creature does not impose disadvantage on your ranged weapon attack rolls.
- When you have advantage on an attack, you may roll 3d20, instead of 2, and take the most favorable result.









> ##### Reload Times
> Remember that from fastest to slowest, reload times are: Part of Attack, Free Object, Reaction, Bonus, Attack, Action.
>
> Also remember you can reload with any action slower than what is listed, i.e. if you can reload with a Reaction, you can choose to instead reload with a Bonus Action

##### Blowgun
Blowguns are used to deliver <br>poison from a distance, as the <br>needle-like dart is often too small <br>to cause serious damage. They are <br>nearly silent when shot, and do not <br>reveal your location if you attack from stealth and miss. A blowgun can be shot with one hand but requires two to reload. A master uses the art of the flying viper, shooting two shots at once, and reloading with a single hand. 

||
|:--|:--|
| Simple | One Handed, Ranged d1 (25/40), Awkward. Reload Free Object |
| Martial | One Handed, Ranged d2 (25/100), Reload <br>Part of Attack, Light  |
| Master | One Handed, Ranged d4 (25/100), Light, Reload Part of Attack, Light  |
| Master Perk | You can load two darts. Roll two attacks <br>against the same target. Each dart <br>deals d2 damage and applies their<br> effect to the target, but you can <br>only do this at your normal range. |


##### Hand Crossbow
A hand crossbow is a hand drawn bow released with a pistol trigger. The limbs are weaker than most other crossbows, and can only launch the bolt a short distance, but being able to pull the drawstring back without mechanical assistance means it can be reloaded very quickly. A master can reload one-handed using hook points on the bolt case, enabling them to dual wield hand crossbows if they wished.

||
|:--|:--|
| Simple | One Handed, Ranged d6+1 (20/60), Light, Reload Reaction |
| Martial | One Handed, Ranged d6+1 (30/120) Light, Reload Free Object |
| Master | One Handed, Ranged d6+1 (30/120) Light, Reload Part of Attack |
| Master Perk | Can be reloaded with one hand. As a bonus action, you can make an attack with this weapon, even if you haven't taken the attack action |



<img 
  src='https://i.imgur.com/PHo0pqI.png' 
  style='position:absolute; bottom:-30px; right:-20px; width:700px' />

<div class='pageNumber auto'></div>
<div class='footnote'>CROSSBOWS</div>
\page
##### Heavy Crossbow
Heavy crossbows load over a thousand pounds of force, allowing it to punch targets like a knight's lance. Because of this power, you must draw a heavy crossbow by turning a winch to pull the drawstring back. A master arbalist uses the crossbow's power to knock hard targets prone or flying creatures from the sky.

||
|:--|:--|
| Simple | Two Handed, Ranged d10+3 (50/200), Heavy, Reload Action |
| Martial | Two Handed, Ranged d10+3 (100/400), Heavy, Reload attack, Trip|
| Master | Two Handed, Ranged d10+3 (100/400), Heavy, Reload Bonus, Trip |
| Master Perk | Before you roll an attack, you can choose to take -5 to the roll. If you hit, your enemy must succeed on a strength saving throw or be knocked prone. Category Large creatures gain advantage on this save, while larger creatures are immune. Flying creatures suffer disadvantage on this save while flying.  |

##### Hidden Crossbow
This mechanical, wrist-mounted crossbow, is similar to a hidden blade. The hand this weapon is equipped to is open, however, you can’t deploy a hidden crossbow from a hand that is holding something. This weapon cannot be disarmed, but takes 1 action to equip or remove. The master can launch a bolt in melee with the slightest distraction. 

||
|:--|:--|
|Simple| One Handed, Ranged d4 (10/30) Awkward, Conceal, Light, Reload Attack
|Martial| One Handed, Ranged d4 (20/40) Conceal, Light, Reload Bonus
|Master| One Handed, Ranged d4 (30/60) Conceal, Light, Reload Reaction
|Master Perk| If an enemy misses you with an attack, you can use your reaction to make a ranged attack against it. 

##### Light Crossbow
You draw a light crossbow back by pulling a lever. A master learns to move and shoot with the light crossbow so efficiently he can reactively shoot moving targets at melee range, threatening all squares near him as if he had a melee weapon. 

**Repeating Crossbow** holds 6 crossbow bolts. As long as it holds bolts, you can reload it by pulling the reloading lever (part of the attack action). Loading a new case of 6 bolts takes an action (regardless of your level of training) that provokes Opportunity Attacks. Only light crossbows can be made repeating. 

||
|:--|:--|
| Simple | Two Handed, Ranged d8+2 (40/200), Reload as an attack |
| Martial | Two Handed, Ranged d8+2 (80/320), Reload with reaction |
| Master | Two Handed, Ranged d8+2 (80/320), Reload Free Object |
| Master Perk | You threaten 5ft around you and can make a ranged opportunity attack if an enemy leaves your threatened space.  |

##### Mauler
A crossbow with two bows mounted in an X shape, the drawstring is attached to a triangle mechanism that holds 3 bolts at once, but adds to its reload time. Even with two bows, the three bolts fly with less power than a hand crossbow and don’t group well at distance, but up close has incredible stopping power. Masters group the bolts at weak points with devastating effect. 

As the bolts spread over distance, on medium or smaller size targets outside normal range the damage is only d4, as only the top bolt is on target. Large and larger size targets take all bolts at any range.

||
|:--|:--|
| Simple | Two Handed, Ranged 3d4 (20/50) Awkward, Reload Action |
| Martial | Two Handed, Ranged 3d4 (30/60) Reload Attack |
| Master | Two Handed, Ranged 3d4 (40/80) Reload Bonus |
| Master Perk |  When you score a critical within 30ft, roll 6d4 for your bonus critical damage.  |


##### Portable Ballista
This small siege weapon takes a while to reload but the damage is worth the wait. It provides several thousand pounds of force to a javelin which punches through even the toughest armor.  Masters use flanking surfaces to nail a target to walls and trees with ease.

A deployable stand can be purchased to mount the weapon. As an action, the weapon is mounted to the stand and can be reloaded as an object interaction. 

||
|:--|:--|
| Simple | Two Handed, Ranged d12+4 (150/400) Awkward, Heavy, Penetrate, Reload Action |
| Martial | Two Handed, Ranged d12+4 (150/600) Heavy, Penetrate, Reload Attack, Trip|
| Master | Two Handed, Ranged d12+4 (150/600)Heavy, Penetrate, Reload Bonus, Trip |
| Master Perk | The crossbow mastery two-target range is 50ft. If you choose a piece of terrain within 5ft of your target and which flanks your target with you, you can instead give the restrained condition to your target on that terrain. Escape DC is your weapon DC.|

##### Spinner
This gnomish invention launches discus blades with internal mechanisms instead of tension limbs. It holds 20 blades and reloading is part of the attack, though when depleted, it takes an Action to reload with 20 more. Range can be measured to an obstacle, then your target. If less than normal range, ignore any cover the creature has. Masters can richochet the blade off one target's weak spot into another nearby. 

||
|:--|:--|
| Simple | Two Handed, Ranged 2d4 (20/60) |
| Martial | One Handed, Ranged 2d4 (30/120), Light |
| Master | One Handed, Ranged 2d4 (30/120),  Light |
| Master Perk |On critical hit, the blade bounces off its target and hits another target of your choice within 10ft of the first target, dealing normal weapon damage. |

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>


<div class='pageNumber auto'></div>
<div class='footnote'>CROSSBOWS</div>

\page


# Dueling Blades

<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
| Dagger | Piercing or Slashing |d4|d4|d4|1|2
| Kukri | Slashing |d4|d6|d6|2|3
| Rapier | Piercing or Slashing |d6|d8|d8|2|25
| Saber | Piercing or Slashing |d6|d8|2d4|2|35
| Sai | Piercing | d4|d4|d4|1|5
| Shortsword | Piercing or Slashing|d6|d6|d8|2|10
| Sickle | Piercing or Slashing |d4|d4|d6|2|1
| Smallsword | Piercing |d6|d6|d6|1|30

</div>

### Feat: Dueling Blade Master
- +1 to attack rolls with dueling blades
- If a creature within 5ft of you takes an attack action against another creature other than you, you may use your reaction to attack that creature.
- On your turn, if you land a critical hit, you can use your reaction to take another attack action with your dueling blade. 

##### Dagger
Any blade about forearm length and smaller can be called a dagger, and there are as many styles of daggers as there are cultures in existence. Nearly all daggers are weapons of opportunity, but some devote their lives to the style. The master can make blinding fast attacks even while they <br>focus their attention elsewhere.

||
|:--|:--|
| Simple | One Handed, Melee d4, Finesse, Light |
| Martial | One Handed, Melee d4, Conceal, <br>Finesse, Light, Thrown (20/60) |
| Master | One Handed, Melee d4, Conceal, Finesse, Light, Thrown (20/60) |
| Master Perk | You can use a bonus action to make<br> an attack with a dagger, even if you <br>don't take the attack action |


##### Kukri
A wider, tip heavy blade which curves toward the cutting <br>edge like a sickle, rather than away from it like a scimitar. A kukri's weight and shape mean that it performs more like a handaxe than a dagger, and can be thrown similar to one as well. The kukri is unique in that it requires strength to wield over dexterity, but the weight and forward angled edge give devestating wounds in the hands of a master.  

||
|:--|:--|
| Simple | One Handed, Melee d4, Light, Thrown (20/60) |
| Martial | One Handed, Melee d6, Light, Thrown (40/80), Trip |
| Master | One Handed, Melee d6, Disarm, Light, Thrown (40/120), Trip |
| Master Perk | Reroll any damage die from this weapon or any abilities such as elemental damage that roll a 1. Additionally, when you trip, your target's speed is reduced by 10ft until the end of their next turn. |

<img 
  src='https://i.imgur.com/GwRoSzw.png' 
  style='position:absolute; bottom:-10px; right:-300px; width:900px' />

<div class='pageNumber auto'></div>
<div class='footnote'>DUELING BLADES</div>
\page





##### Rapier
The rapier is a long, thin sword designed with extra weight in the handle for maximum control with the tip. Prized as the pinnacle of finesse, masters learn how to properly strike forth in a lunge, learn expert parries, and use a rapier in the off hand.

||
|:--|:--|
| Simple | One Handed, Melee d6, Awkward |
| Martial | One Handed, Melee d8, Finesse, Light |
| Master | One Handed, Melee d8, Deflect, Finesse, Light, Lunge |
| Master Perk | If you are wielding a rapier and nothing in your off hand, you can add d4 to your damage roll. If you are wielding a light weapon, instead add +1 to AC.|


##### Saber
A saber describes a wide variety of weapons that all share a few properties in common; one-handed, single-edged, slight curve, and little or no counterweight to add cutting power to the blades. Examples are the cavalry saber, shamshir, and officer’s sword. The master finds the saber’s curve and hand protection give incredible defense.

||
|:--|:--|
| Simple | One Handed, Melee d6, Awkward |
| Martial | One Handed, Melee d8, Deflect, Finesse |
| Master | One Handed, Melee 2d4, Deflect, Finesse, Light |
| Master Perk | If an enemy hits you with a melee weapon attack, you can use your reaction to add your proficiency to your AC, possibly negating a successful hit. This added bonus to AC lasts for that enemy's turn only. |

##### Sai
A sai is a dagger sized weapon made famous in Okinawa, which consists of a sharpened metal rod with two forward swept, elongated prongs for a hand guard, making it easy to block and trap enemy weapons, but this template can be used for any parrying dagger designed primarily to block. Since only the tip is sharpened, the sai suffers from damage capability and versatility, but is easily the best light weapon for the duelist looking for a bit of protection. The master uses the parrying prongs to disarm blindingly fast, and even gains a passive protection from their stance.

||
|:--|:--|
| Simple | One Handed, Melee d4, Awkward, Light |
| Martial | One Handed, Melee d4, Conceal, Deflect, Finesse, Light |
| Master | One Handed, Melee d4, Conceal, Deflect, Disarm, Finesse, Light |
| Master Perk | You gain +1 AC if you are wielding a Sai in your off hand and you can perform a disarm attack as a reaction when an enemy misses you with a melee weapon attack. |

```
```


##### Shortsword
This category consists of any thrusting or chopping blade longer than a dagger, but shorter than a full-sized sword. Examples include a cutlass, wakizashi, or machete. The master learns to gain every bit of damage out of the shortsword.

||
|:--|:--|
| Simple | One Handed, Melee d6, Finesse, Light |
| Martial | One Handed, Melee d6, Finesse, Light |
| Master | One Handed, Melee d8, Finesse, Light |
| Master Perk | When you have advantage on the attack, you can roll damage twice and take the better result, including any attachers, such as elemental imbue damage or sneak attacks. |

##### Sickle
The sickle is a short, crescent-shaped blade with the cutting edge on the inside of the curve, derived from the farming tool designed to harvest plants. The crescent can be used to trip a target, and a master learns to use the curve of the weapon to grapple and bind enemies when the point sinks into a target. 

||
|:--|:--|
| Simple | One Handed, Melee d4, Light |
| Martial | One Handed, Melee d4, Light, Trip |
| Master | One Handed, Melee d6, Entangle, Light, Trip |
| Master Perk | Your entangle attacks deal full weapon damage on hit. When you hit with a trip attack, your enemy suffers -10 ft to its speed until the end of its next turn, regardless of if it succeeds on the save against the trip. |

##### Smallsword
The smallsword is a light weapon designed for thrusting which evolved out of the longer and heavier rapier. It has a triangular profile and often a pistol grip, giving the fullest control over the tip over any other weapon design. The master has such control over the thrusting tip, they can negate a detriment to their attack with focus. 

||
|:--|:--|
| Simple | One Handed, Melee d6, Awkward, Finesse |
| Martial | One Handed, Melee d6, Finesse, Light, Penetrate |
| Master | One Handed, Melee d6, Finesse, Light, Lunge, Penetrate |
| Master Perk | If you have advantage on your attack, you may add a d4 to your attack roll. If you have disadvantage on your attack, you may spend your bonus action to roll your choice of athletics or acrobatics to negate the disadvantage. The DC is equal to your target's AC.|
<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

<div class='pageNumber auto'></div>
<div class='footnote'>DUELING BLADES</div>



\page

# Firearms

<div class='wide'>
  
|  Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
| Arquebus | Piercing|2d10+5|2d10+5|2d12+5|10|750
| Blunderbuss | Piercing |2d8|2d8|2d10|5|300
| Firelance | Fire/Piercing |2d8|2d8|2d8|5|200
| Hand Cannon | Piercing |d10|d10|d12|3|250
| Pepperbox | Piercing |2d4|2d4|2d6|1|1500
| Firepot | Fire | 2d6 |2d6|2d6|2|25
| Flash Bomb | Radiant |d8|d8|d8|2|35
| Powder Charge | Piercing and Thunder |3d6|3d6|3d6|2|150


</div>

### Feat: Firearm Master
- You may spend a Bonus Action to clear a jam or dry a wet firearm 
- One Handed Firearms become Melee d4 weapons, while Two Handed Firearms become Melee d6 weapons. During a Reload, as a Bonus Action, you can make an attack with any weapon you are wielding, not just firearms. 
- You can roll damage twice and take the best result with any firearm.




##### Arquebus
The Arquebus a long barreled, 6 ft firearm. A lead ball is muzzle loaded and the trigger sparks or embers the charge. It has a monopod to steady a long ranged shot, which weighs 2 lbs, deployed as a Bonus Action to negate the disadvantage for attacking beyond normal range. The master can wield a bayonet attached to the weapon as well as a pike master.

||
|:--|:--|
| Simple | Two Handed, Ranged 2d10+5 (300/900) Awkward, Firearm, Heavy, Penetrate, Reload Attack |
| Martial | Two Handed, Ranged 2d10+5 (300/900), Heavy, Firearm, Penetrate, Reload Attack |
| Master | Two Handed, Ranged 2d12+5 (300/900), Heavy, Firearm, Penetrate, Reload  Attack |
| Master Perk | As a Bonus Action, you affix a bayonet to the arquebus, giving you a pike at Master training, including its Master Perk, but disadvantage on ranged attacks|

##### Hand Cannon
Hand Cannons are 2ft, short-ranged cannon that can be wielded in one hand. It uses lead ball like an Arquebus but holds a smaller amount of powder. This weapon doesn't suffer disadvantage when an enemy is within 5ft. A master learns to shoot from the hip, even while distracted. 

||
|:--|:--|
| Simple | One Handed, Ranged d10+5 (200/600) Awkward, Firearm, Light, Penetrate, Reload Attack |
| Martial | One Handed, Ranged d10+5 (200/600), Firearm, Light, Penetrate, Reload Attack |
| Master | One Handed, Ranged d12+5 (200/600), Firearm, Light, Penetrate, Reload Attack |
| Master Perk | You can make a ranged attack as a bonus action, even if you didn't take the attack action |


<img 
  src='https://i.imgur.com/AyMPWRu.png' 
  style='position:absolute; bottom:0px; right:-70px; width:550px' />


<div class='pageNumber auto'></div>
<div class='footnote'>FIREARMS</div>
\page

##### Blunderbuss
The Blunderbuss looks like a short Arquebus with a flared muzzle, and uses shot, a grouping of pellets instead of a single ball. It doesn't have disadvantage and gains Penetrate when an enemy is within 5ft, but can only attack one target at this range. A master overpacks his weapon to great effect. 

When you make an attack, you choose a target and up to 2 targets within 5ft of it. One shot rolls one attack against all three targets together. A blunderbuss does not have a long range.

||
|:--|:--|
| Simple | Two Handed, Ranged 2d8+5 (60ft) Awkward, Firearm, Reload Attack |
| Martial | Two Handed, Ranged 2d8+5 (60ft), Firearm, Reload Attack |
| Master | Two Handed, Ranged 2d10+5 (60ft), Firearm, Reload Attack |
| Master Perk | If a target is within 15ft, it must succeed on a Strength saving throw or be pushed back 5ft or knocked prone. |


##### Firelance
A hollow-tipped lance packed with gunpowder. The ranged fire attack spreads out in a 15ft cone from 10ft in front of you. Each target must succeed on a Dexterity save or suffer the fire damage plus your Dexterity modifier. You can also use a firelance as a melee weapon, even as a lance from horseback. A master sweeps the fire in an arc as it ejects burning gunpowder.

||
|:--|:--|
| Simple | Two Handed, Ranged 2d4 (15ft cone) Melee (d8), Awkward, Firearm, Reload Bonus Action |
| Martial | Two Handed, Ranged 2d4 (15ft cone), Melee (d8), Firearm, Reload Bonus Action |
| Master | Two Handed, Ranged 2d4 (15ft cone), Melee (d8), Firearm, Reload Bonus Action |
| Master Perk | While loaded, as an action, you sweep fire around you, forcing all targets within 10ft to succeed on a Dexterity saving throw or suffer 2d4 fire damage. |

##### Pepperbox

A concealable firearm that uses bullets packed into four barrels on a swivel, and fires four times before reloading. Pepperboxes with more barrels exist; a 5 barrel at 2000gp, and a 6 barrel at 2500gp. This weapon does not suffer disadvantage when an enemy is within 5ft. The master can turn and fire each barrel in seconds, unloading a hail of gunfire at close range.

After each shot, an object interaction is required to turn the barrels. As an action you only reload two barrels.

||
|:--|:--|
| Simple | One Handed, Ranged d4+5 (30/120) Awkward, Conceal, Firearm, Light, Reload Action |
| Martial | One Handed, Ranged d4+5 (30/120), Conceal, Firearm, Light, Reload Action |
| Master | One Handed, Ranged d6+5 (30/120), Conceal, Firearm, Light, Reload Action |
| Master Perk | As an action, you fire all barrels at once, rolling an attack for each loaded barrel against an enemy 10ft or less from you. After two shots, the weapon jams on 2-3, and is destroyed if you roll a 1. |

##### Firepot
A breakable pot filled with alchemist's fire. On a hit, the target continues to take 1d6 fire damage at the start of its turn. It can spend an Action to make a Dexterity Saving Throw, extinguishing the fire on success. A master can toss in a way the contents spill onto two targets with one pot.

Upon a miss, the fire burns for d6 rounds, and any creature that starts its turn, or enters the fire for the first time on its turn must succeed at a Dexterity Saving Throw or take d6 fire damage. 

||
|:--|:--|
| Simple | One Handed, Thrown 2d6 (20/80) Awkward, Firearm, Launch, Light|
| Martial | One Handed, Thrown 2d6 (20/80), Firearm, Launch, Light|
| Master | One Handed, Thrown 2d6 (20/80), Firearm, Launch, Light|
| Master Perk | You can attack two targets if they are within 5ft of each other. |

##### Flash Bomb
A breakable pot filled with bright white burning phosphorous. When hit, your target must succeed on a Dexterity saving throw or become blinded until the end of your next turn, and with sunlight sensitivity, it suffers disadvantage on this save. A master can toss the pots in melee range without detriment, or explode it right in the enemy's eyes without hitting them.

Upon a miss, any creature in the square the flash bomb lands takes no damage and gains advantage on the Dexterity save to avoid being blinded.

||
|:--|:--|
| Simple | One Handed, Thrown d8 (20/80) Awkward, Firearm, Launch, Light|
| Martial | One Handed, Thrown d8 (20/80), Firearm, Launch, Light |
| Master | One Handed, Thrown d8 (20/80), Firearm, Launch, Light |
| Master Perk | You don't suffer disadvantage if an is enemy within 5ft of you. You can choose to deal no damage, but give your target disadvantage on the save.|


##### Powder Charge
A breakable pot filled with gunpowder and capped with a short wick. The pot explodes into shrapnel when the lit wick touches the exposed powder as it breaks on impact.

On a hit, the target takes the Thrown damage. All other targets within 10ft must succeed on a Dexterity saving throw or take 2d6 piercing damage and 1d6 thunder damage. The sound it creates can be heard up to 600ft away.

||
|:--|:--|
| Simple | One Handed, Thrown 3d6 (20/80), Awkward, Firearm, Launch, Light, Penetrate |
| Martial | One Handed, Thrown 3d6 (20/80), Firearm, Launch, Light, Penetrate |
| Master | One Handed, Thrown 3d6 (20/80), Firearm, Launch, Light, Penetrate |
| Master Perk |You can choose to deal only d6 damage, but force all affected targets to succeed on a Strength saving throw or fall prone.|

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)
</div>

<div class='pageNumber auto'></div>
<div class='footnote'>FIREARMS</div>

\page

# Flails and Whips
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
| Double Flail | Bludgeoning and Piercing| 2d4 |2d4(2d6)|2d6(2d8)|7|20
| Light Flail | Bludgeoning and Piercing|d4|d6|d6|3|8
| Heavy Flail | Bludgeoning and Piercing|d8|d8 (d10)|d10 (d12)|5|10
| Pole Flail | Bludgeoning |d10|d10|d10|10|25
| Meteor Hammer | Bludgeoning |d4|d4|d4|3|5
| Nunchaku | Bludgeoning | d4| d4| d4|1|1
| Whip | Slashing |d2|d4|d6|1|2
| Chain Sword | Slashing |d6(d8)/d4|d8(d10)/d6|d8(d10)/d6|3|250

</div>

### Feat: Flail and Whip Master
- +1 to attack rolls with flails and whips
- As a bonus action, you add +2 to attack using your flail or whip against an enemy until the end of your next turn, as you sweep around the shield or guard to hit. 
- When you hit with an opportunity attack, the foe must succeed on a strength saving throw or be knocked prone
- You gain advantage on any attack made to attempt a Trip, Disarm, or Entangle, and if both dice rolls would have hit, the enemy takes full damage as if you attacked them normally in addition to needing to make the save. 

##### Double Flail
This flail has two flail heads, each with a separate chain attached to a single handle, whether they are attached at opposing ends, or attached at the same end. The Double flail is a difficult weapon to use effectively, and only the master really gets use out of individual heads, turning a potential miss into a new opportunity.

||
|:--|:--|
| Simple | Two Handed, Melee 2d4, Awkward, Heavy |
| Martial | One Handed, Melee 2d4, Heavy, Versatile 2d6 |
| Master | One Handed, Melee 2d6, Heavy, Trip, Versatile 2d8 |
| Master Perk | When you suffer disadvantage but one dice would have hit, you deal 1 of the weapon's damage dice plus your strength modfier, <br>even though this still counts <br>as a miss. If you <br>have advantage <br>and both dice hit, <br>add your Strength <br>modifier twice to the<br> damage total. |
```
```
##### Light Flail
The familiar handle with a spiked ball at the end of a chain which deals both bludgeoning and piercing damage at the same time for the purposes of overcoming resistances or immunities. Masters with the light flail learns to carry the weapons speed and momentum into another attack if they miss. 

||
|:--|:--|
| Simple | One Handed, Melee d4, Light, Trip  |
| Martial | One Handed, Melee d6, Disarm, Light, Trip |
| Master | One Handed, Melee d6, Disarm, Light, Trip |
| Master Perk | If you miss with an attack, you may use your reaction to make one extra attack as part of the same action. |





<img 
  src='https://i.imgur.com/JmtpbXP.png' 
  style='position:absolute; bottom:-50px; right:-180px; width:830px' />

<div class='pageNumber auto'></div>
<div class='footnote'>FLAILS AND WHIPS</div>
\page

##### Heavy Flail
A heavy flail consists of a long handle with a large spiked metal bar like the end of a morningstar, which is attached by means of chain or swivel. The heavy flail is an immense weapon, but the master learns to wield it one-handed, and can turn a failed trip or disarm attempt into a strike that still damages. 

||
|:--|:--|
| Simple | Two Handed, Melee d8, Awkward, Heavy, Penetrate |
| Martial | One Handed, Melee d8, Heavy, Penetrate, Trip, Versatile d10 |
| Master | One Handed, Melee d10, Disarm, Heavy, Penetrate, Trip, Versatile d12 |
| Master Perk | If your enemy succeeds on their save against your disarm, entangle, or trip attack, you can make an attack as part of the same action. |


##### Pole Flail
A weapon of hafted reach, though instead of an axe or blade, there is the spiked bar of the heavy flail, which deals bludgeoning and piercing damage at the same time. The pole flail is primarily designed for field warfare, thought the master learns to bind and damage knees and ankles just out of reach, causing massive damage to fleeing targets. 

||
|:--|:--|
| Simple | Two Handed, Melee d10, Awkward, Heavy, Reach |
| Martial | Two Handed, Melee d10, Heavy, Reach, Trip |
| Master | Two Handed, Melee d10, Entangle, Heavy, Reach, Trip |
| Master Perk | When you hit with an opportunity attack, that creature's speed is halved until the end of its next turn. |


##### Meteor Hammer
This weapon is a spherical or conical weight attached to a 15-foot rope. Used as a more brutal form of a rope dart, the meteor hammer is capable of using circular movement to strike or bind, and using explosive lunges to strike at a distance. A master can twirl the weapon around them with varying angles and speed to strike any foe who enters their reach from any direction. 

||
|:--|:--|
| Simple | Two Handed, Melee d4, Awkward, Finesse, Lunge, Reach |
| Martial | Two Handed, Melee d4, Entangle, Finesse, Lunge, Reach |
| Master | Two Handed, Melee d4, Disarm, Entangle, Finesse, Lunge, Reach, Trip |
| Master Perk | As an action, you begin twirling the hammer around you in a 10ft radius. Until the start of your next turn, any creature of your choice which starts its turn or which enters this space must succeed on a Dexterity save or be damaged as if you hit it with a melee attack.|

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)
</div>

```
```
##### Nunchaku
Made famous in Okinawa, the nunchaku is two rods bound by a rope or chain. By whipping around the body, it can make dizzyingly fast attacks, and despite being a one handed weapon, a master can wield it like a Double Ended weapon.  

||
|:--|:--|
| Simple | One Handed, Meleed d4, Conceal, Finesse |
| Martial | One Handed, Melee d4, Conceal, Entangle, Finesse, Light, Trip |
| Master | One Handed, Melee d4, Conceal, Double Ended d4, Entangle, Finesse, Light, Trip |
| Master Perk | You can treat this weapon as if it is Double Ended even while wielding it in one hand. If you dual wield nunchaku, you may make two Double Ended attacks with the same Bonus Action. If you wield only one, you gain Disarm. |


##### Whip
The whip is treated as a melee weapon with 15ft reach. You can use a whip to grasp unattended small objects, or any reasonable handhold within range and if possible, you can pull the object to you. A whip master has such control over his grasping whip, he can manipulate objects at will.  

||
|:--|:--|
| Simple | One Handed, Melee d2, Awkward, Finesse |
| Martial | One Handed, Melee d4, Disarm, Finesse, Reach (15ft) |
| Master | One Handed, Melee d6, Disarm, Entangle, Finesse, Light, Reach (15ft), Trip |
| Master Perk | When you disarm any creature, you choose to place the item anywhere in your reach, or catch it as a reaction. An item in your reach that can be grabbed with the whip can be placed anywhere else in your reach. |

##### Chain Sword
The most exotic weapon in the group, a chain sword can be both a sword or a bladed whip. As a bonus action, you change between the forms of your weapon. As a sword, it is similar in size and shape to a longsword. As a whip, it gains some reach and utility, and a target entangled by you takes your weapon's full damage. A master can quickly change between forms as needed and even attack targets adjacent to his entangled foe. 

||Sword Form|
|:--|:--|
| Simple |One Handed, Melee d6, Awkward, Versatile d8 |
| Martial | One Handed, Melee d8, Finesse, Versatile d10 |
| Master | One Handed, Melee d8, Lunge, Finesse, Versatile d10|
| Master Perk | You may change between weapon forms freely, which is how you get the lunge property. |

||Whip Form
|:--|:--|
| Simple | One Handed, Melee d4, Awkward, Reach |
| Martial | One Handed, Melee d6, Entangle, Reach |
| Master | One Handed, Melee d6, Entangle, Reach |
| Master Perk | While an enemy is entangled, you can still attack your entangled enemy, or any target within 5ft of it |


<div class='pageNumber auto'></div>
<div class='footnote'>FLAILS AND WHIPS</div>


\page

# Hammers and Picks
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
| Light Hammer | Bludgeoning |d6|d6|d6|2|2
| War Hammer | Bludgeoning |d8|d8 (d10)|d10 (d12)|3|15
| Maul | Bludgeoning |d12|2d6|2d8|12|10
| Lucerne | Bludgeoning or Piercing |2d6|2d6|2d6|8|25
| Light Pick | Piercing |d4|d4|d6|1|2
| Wall Pick | Piercing |d6|d6|d8|1|3
| War Pick | Piercing |d8|d8|d10|2|15
| Stiletto | Piercing|d4|d4|d4|1|10


</div>

### Feat: Hammer and Pick Master
- +1 to attack rolls made with hammers or picks
- Whenever you have advantage on attacks and both dice would hit, you knock the target prone or shove them 5ft
- Whenever you have disadvantage on attacks and at least one roll would have hit but the other misses, you can deal your strength modifier in weapon damage to the target. 

##### Light Hammer
The light hammer is a short-handled, blunt warhammer balanced for throwing. While a flanged mace may shred armor, a hammer is able to more precisely deliver blows that weaken the bearer of that armor, and a master can even weaken a user enough that movement seems impossible. 

||
|:--|:--|
| Simple | One Handed, Melee d6, Thrown (10/40) Awkward, Light |
| Martial | One Handed, Melee d6, Thrown (20/60) Light |
| Master | One Handed, Melee d6, Thrown (20/60) Light |
| Master Perk | If your attack is at least 5 higher than <br>the AC, your enemy's speed is reduced <br>by half until the start of your next turn.|

##### War Hammer
The historical warhammer was a lightweight, <br>long-handled weapon designed to damage <br>armored enemies. The small, pronged hammer <br>head is often backed with a military pick or <br>different style of face. A master of the warhammer <br>cares little for armor, blasting through it with ease.

||
|:--|:--|
| Simple | One Handed, Melee d8, Awkward, Penetrate |
| Martial | One Handed, Melee d8, Penetrate, Versatile d10|
| Master | One Handed, Melee d10, Penetrate, Versatile d12|
| Master Perk | You ignore resistance to non-magical <br>bludgeoning damage, and when you score a critical hit, your enemy becomes vulnerable to bludgeoning damage for that attack.|


<img 
  src='https://i.imgur.com/tlH5WtV.png' 
  style='position:absolute; bottom:-30px; right:-350px; width:900px' />

<div class='pageNumber auto'></div>
<div class='footnote'>HAMMERS AND PICKS</div>
\page



##### Maul
The maul is a massive weapon; a great hammer able to move the stoutest of foes. The weapon’s weight adds to its damage, and the master finds he can use the weapon’s mass to smash foes to the ground or send them flying. Additionally, a maul always has advantage on attack rolls to damage objects and deals Double Ended damage to them.

||
|:--|:--|
| Simple |Two Handed, Melee d12, Awkward, Heavy, Penetrate|
| Martial |Two Handed, Melee 2d6, Heavy, Penetrate, Trip|
| Master |Two Handed, Melee 2d8, Heavy, Penetrate, Trip|
| Master Perk |If you move at least 10 ft before making an attack, you gain +5 bonus to the attack's damage roll and your shove attacks knock foes 10 ft and prone instead of 5 ft or prone.|


##### Lucerne
This hammer polearm has a pronged hammer head for crushing blows on one side and a spiked hook head for piercing and peeling armor on the other. The long haft allows the wielder to put devastating force behind the blows of this weapon. Lucerne masters learn to destroy shields and armor with relative ease.

||
|:--|:--|
| Simple |Two Handed, Melee 2d6, Awkward, Brace, Heavy, Penetrate, Reach|
| Martial |Two Handed, Melee 2d6, Brace, Heavy, Penetrate, Reach, Trip|
| Master |Two Handed, Melee 2d6, Brace, Heavy, Penetrate, Reach, Trip|
| Master Perk |As an action, you roll an attack to destroy the shield or armor worn by the enemy. On a hit, your enemy must succeed on a Dexterity saving throw or their AC is reduced by 2. If they succeed on this save, they instead take damage. |


##### Light Pick
The light pick is a smaller version of the war pick, with a thinner point and shorter length for one handed wielding. Though not as stout and easily able to puncture armor like the war pick, the light pick allows more agile maneuvers, as well as balanced throwing. A master has learned to look for the perfect opening, placing the pick into soft targets in armor.

||
|:--|:--|
| Simple |One Handed, Melee d4, Thrown (10/40) Finesse, Light, Penetrate|
| Martial |One Handed, Melee d4, Thrown (20/60) Finesse, Light, Penetrate, Trip|
| Master |One Handed, Melee d6, Thrown (20/60), Finesse, Light, Penetrate, Trip|
| Master Perk |You have +2 to attacks against any enemy wearing armor.|

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

```
```

##### Wall Pick
A wall pick is also called a climbing pick, and has been repurposed for combat. It is similar in size to the light pick, though has a longer spike at a more hooked angle to aid in climbing. In combat, this can be used to great effect to grapple an opponent or disarm them quite easily. While using a wall pick, you have advantage on climb checks. The master can grapple a foe as easily as they latch onto a wall. While wielding a climbing pick, you can climb creatures two size categories bigger than you and hold onto them.

||
|:--|:--|
| Simple |One Handed, Melee d6, Thrown (10/40) Awkward, Penetrate|
| Martial |One Handed, Melee d6, Thrown (20/60) Entangle, Light, Penetrate, Trip|
| Master |One Handed, Melee d8, Finesse, Thrown (20/60) Entangle, Disarm, Light, Penetrate, Trip|
| Master Perk |You have advantage on attack rolls made to entangle, and if both dice would have hit, your enemy has the restrained and grappled condition|

##### War Pick
The war pick is a weapon derived from a miner's pick, famously manufactured by militant mountain dwarves, but has since been refined and used worldwide by militaries facing heavily armored combatants. The pick comes in many forms but is usually a battle axe sized weapon with a reinforced spike on one end, and a widened, sharpened scoop or hammer opposite the spike. A master learns to puncture in vital areas to bleed the foe over time with deep stab wounds. 

||
|:--|:--|
| Simple |One Handed, Melee d8, Awkward, Penetrate|
| Martial |One Handed, Melee d8, Trip, Penetrate|
| Master |One Handed, Melee d10, Trip, Penetrate|
| Master Perk |You can choose to take -5 to your attack roll, and if successful, your target takes piercing damage equal to your strength modifier at the start of each of their turns. A creature can attempt a Constitution saving throw at the end of their turn, ending the effect on a success. If the creature receives any healing, this also ends the effect.|

##### Stiletto
The stiletto is a long, thin, needle-like dagger made for puncturing armor with ease. Its thin point and narrow cross section make it perfect for fitting between armor plates, or outright puncturing through them so deeply it allows the user to stab and hold an enemy. A master has learned to use the needle-point with such accuracy that his foes may as well not even be wearing armor. 

||
|:--|:--|
| Simple | One Handed, Melee d4, Thrown (10/40) Finesse, Light, Penetrate |
| Martial | One Handed, Melee d4, Thrown (20/60) Conceal, Entangle, Finesse, Light, Penetrate |
| Master | One Handed, Melee d4, Thrown (20/60) Conceal, Entangle, Finesse, Light, Penetrate |
| Master Perk | When you successfully Entangle, as a bonus action you can attempt a shove. |


<div class='pageNumber auto'></div>
<div class='footnote'>HAMMERS AND PICKS</div>
\page

# Polearms
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
|Glaive|Slashing or Piercing|d10|2d6|2d6|5|20
|Guisarme|Slashing|d8|d10|d10|5|10
|Lajatang|Slashing or Piercing|d6|d8 [d8]|d10 [d10]|8|75
|Partisan|Slashing or Piercing|d10|2d6|2d6|6|25
|War Scythe|Piercing or Slashing|2d6|2d6|2d8|8|5

</div>


### Feat: Polearm Master
- +1 to attack rolls with polearms
- All Polearm weapons are treated as having the Double Ended property. Your normal attacks are made with the weapon's damage die, while your attack with Double Ended is made with d4. 
- While you are wielding the polearm, other creatures provoke an opportunity attack from you when they enter the reach of your weapon.

##### Glaive
Perhaps the simplest of the polearms, a glaive is a sword blade, usually about 36-40 inches mounted on a 4-6 foot pole, creating a 6-8 foot weapon. A Glaive can be used like a spear or like a greatsword, and the wide, sweeping slashes deal extra damage to creatures much bigger than the wielder. Sometimes referred to as a horse killer, the Glaive was originally designed to be used by infantry against cavalry, but in the hands of a master adventurer, can be used quite effectively as a giant Killer.

||
|:--|:--|
| Simple |Two Handed, Melee d10, Awkward, Brace, Finesse, Reach, Heavy|
| Martial |Two Handed, Melee 2d6, Brace,<br> Finesse, Reach, Heavy|
| Master |Two Handed, Melee 2d6, Brace, Finesse, Reach,<br> Lunge, Heavy|
| Master Perk |Against creatures of category size Large<br> and larger, your damage is 3d6 instead of<br> 2d6. Your Double Ended Attack is still d4.|



> ##### Additional Polearm Training
> If you take the Polearm Master feat, the following weapons also count as Polearms for you
>- Halberd
>- Lucerne
>- Morningstar
>- Pole flail
>- Short Glaive
>
>These weapons benefit from your Polearm Master feat and you may use them at their master level training.





<img 
  src='https://i.imgur.com/kGJMfr0.png' 
  style='position:absolute; bottom:0px; right:-50px; width:700px' />

<div class='pageNumber auto'></div>
<div class='footnote'>POLEARMS</div>

\page

##### Guisarme
A guisarme is a modified pruning hook, developed as a peasant weapon from modifying a farm tool. The curved hook of the blade allows the guisarme to be used as a tripping weapon or to pull foes from the saddle. With at least martial proficiency, a Guisarme can be used to perform a trip against mounted foes to pull them from the saddle to a prone position. Guisarme masters get advantage on trip maneuvers

||
|:--|:--|
| Simple |Two Handed, Melee d8, Brace, Reach, Trip, Heavy|
| Martial |Two Handed, Melee d10, Brace, Reach, Trip, Heavy|
| Master |Two handed, Melee d10, Brace, Reach, Trip, Heavy|
| Master Perk |You have advantage on trip attacks made to targets at 10ft away from you, and if you succeed against a mounted foe, it is automatically pulled from its mount to a prone position without making any additional saves. When you successfully hit with a trip attack, its speed is reduced by 10ft until the end of its next turn, regardless of whether it succeeded on the save.|


##### Lajatang
A lajatang is a rare and unusual Double Ended weapon. It consists of a three to five foot shaft with a crescent blade fitted at each end with the points away from the center of the weapon. The rare masters of the Lajatang are a whirling dervish of blade and crescent points and are dangerous from all sides.  

||
|:--|:--|
| Simple |Two Handed, Melee d6, Awkward, Brace, Reach|
| Martial |Two Handed, Melee d8, Double Ended d8, Brace, Finesse, Reach|
| Master |Two Handed, Melee d10, Double Ended d10, Brace, Finesse, Reach|
| Master Perk |You are so dangerous at front and back with your weapon, you negate any effect any enemy might gain from flanking or having the enemy's ally near you, including bonuses such as Pack Tactics or Sneak Attack. In addition, you make two attacks with Double Ended instead of the usual one.|


##### Partisan
A partisan is much like a Glaive in that the design is essentially a sword blade mounted to a long shaft. However, the partisan retains the sword's guard, and is very effective at protection from range, though the guard prevents it from making sweeping, cleaving cuts like the glaive. The Master Partisan uses the guard of his weapon with great effect at a distance. 

||
|:--|:--|
| Simple |Two Handed, Melee d10, Awkward, Brace, Reach, Heavy|
| Martial |Two Handed, Melee 2d6, Brace, Reach, Heavy|
| Master |Two Handed, Melee 2d6, Brace, Reach, Lunge, Heavy|
| Master Perk |You have +2AC against melee attacks from enemies that are 10ft away from you. When an enemy targets an ally within 5ft of you, you can use your reaction to <br>impose disadvantage <br>to that attack |



##### War Scythe
Whether mounted horizontally like a traditional farming implement, or mounted vertically like a glaive, a war scythe has its roots in a peasant militia looking to arm itself in times of war. A scythe in the right hands can be useful in combat, though it takes a practiced user to be truly effective. The master uses the scythe's reaping motion to deal horrible slashing wounds to the foes he trips in combat.

||
|:--|:--|
| Simple |Two Handed, Melee 2d6, Heavy, Penetrate, Reach, Trip |
| Martial |Two Handed, Melee 2d6, Heavy, Entangle, Penetrate, Reach, Trip|
| Master |Two handed, Melee 2d8, Heavy, Entangle, Penetrate, Reach, Trip|
| Master Perk |When you successfully trip an enemy, that enemy takes full weapon damage, and has its speed reduced to just 10ft until the end of its next turn. |


> ##### Mounted Combat Reminder
> Remember the following while fighting mounted combatants!
>- If an effect moves a mount against its will, the rider must succeed on a DC10 Dexterity saving throw, or fall off the mount, landing prone within 5ft of it
>- If the rider is knocked prone while in the saddle, it must also make this save
>- If the mount is knocked prone, the rider can use its reaction to land safely on its feet within 5ft of the prone mount, otherwise it too falls prone. 
>
> Therefore, when you attempt a trip attack against a mounted foe and succeed, the foe can still succeed on a different save and stay in the saddle while the mount whisks them away to safety! 
 
 <div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

<img 
  src='https://i.imgur.com/72an030.png' 
  style='position:absolute; bottom:0px; right:-50px; width:700px' />


<div class='pageNumber auto'></div>
<div class='footnote'>POLEARMS</div>
\page



# Spears
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
|Godendag|Piercing or Bludgeoning|d6|d6|d8|5|12
|Harpoon|Piercing|d6|d6|d8|1|1
|Javelin|Piercing|d6|d6|d8|1|1
|Lance|Piercing|d8|d12|2d8|6|10
|War Spear|Piercing|d8|d8 (d10) [d4]|d10 (d12) [d4]|3|25
|Pike|Piercing|d8|d12|2d8|8|5
|Ravenbeak|Piercing or Slashing|d8|d8|d8|3|15
|Trident|Piercing|d6|d8 (2d4)|d12 (3d4)|3|10
  

</div>

### Feat: Spear Master
- +1 to attacks rolls made with spears
- You may lunge with any spear, which does <br>not use your reaction
- Once per turn, if you have advantage on an <br>attack roll, you can forgo the advantage for that <br>roll to make an additional weapon attack against that target, as part of the same action. Any remaining attacks still have advantage.

##### Godendag
A godendag is a short spear from Western Europe with a thick socket holding the point, heavy enough to use as a bludgeon. The style of fighting with a godendag involves swinging and thrusting, both utilizing the spear's weighted head and pointed tip in combat. A master can stun his foe, and even uses the weapon's weight to trip or disarm.

||
|:--|:--|
| Simple |Two Handed, Melee d6, Thrown (10/40), Awkward, Penetrate|
| Martial |Two Handed, Melee d6, Thrown (20/60), Penetrate, Trip|
| Master |Two Handed, Melee d8, Disarm, Thrown (30/120), Penetrate, Trip|
| Master Perk | Before you attack, you can choose to take -5 to the roll. If you hit, your foe must succeed on a Constitution saving throw or be stunned until the end of your next turn. |


##### Javelin
The javelin is a light throwing spear built with low weight <br>and balance for throwing. It generally has a long spear point that can break off in a shield or armor, rendering the user much less agile, and the master has learned to do so reliably, targetting a shield to intentionally break the javelin off in it.

||
|:--|:--|
| Simple |One Handed, Melee d6, Thrown (20/60), Light|
| Martial |One Handed, Melee d6, Thrown (30/120), Light|
| Master |One Handed, Melee d8, Thrown (30/240), Light|
| Master Perk | Before the attack, you can take -5 to your attack roll. If you hit, your enemy can no longer use their shield until they use an action to pry the remnants of the javelin from the shield itself.|


<img 
  src='https://i.imgur.com/qtpqeVX.png' 
  style='position:absolute; bottom:15px; right:-110px; width:700px' />

<div class='pageNumber auto'></div>
<div class='footnote'>SPEARS</div>
\page





##### Harpoon
A barbed throwing spear with a welded ring, attached to a length of rope or chain so the target, or harpoon itself, can be retrieved. A master of the harpoon knows how to impale with ease and can reel in a harpooned prey swiftly. 

Each hit, your enemy must succeed on a strength saving throw or be impaled, while a critical hit always impales. 

||
|:--|:--|
| Simple |Two Handed, Melee d6, Thrown (10/40), Awkward, Light|
| Martial |Two Handed, Melee d6, Thrown (20/60), Light|
| Master |One Handed, Melee d8, Penetrate, Thrown (30/120), Light |
| Master Perk |You may drag an enemy back to you at twice your climbing speed, and enemies have disadvantage on the Strength saving throw. |

>##### Harpoon Retrieval
> When an enemy is impaled, you can spend a bonus action to pull it toward you at twice your climbing speed, if you win an Athletics contest with the enemy on your turn. On its turn, to move away from you, it must win an Athletics contest. 
>
> While impaled, your enemy takes damage from your weapon at the start of its turn.
>
> If you harpoon an enemy at least two size categories larger than you, you simply move with your target and climb the rope as normal.
>
> Your enemy can spend an action to repeat the save to pull the weapon free. If your harpoon is free or you miss, you can retrieve it at twice your climb speed on your turn as a bonus action.


##### Lance
Designed for use while mounted, a lance imposes disadvantage on attacks against targets within 5ft while on foot. While mounted, you gain Penetrate. Masters with the lance hold it steady, putting the mount's power into targets. 

||
|:--|:--|
| Simple |Two Handed Melee d8, Awkward, Brace, Reach|
| Martial |Two Handed Melee d12, Brace, Reach |
| Master |One Handed, Melee 2d8, Brace, Reach |
| Master Perk |While mounted, each successful attack is also a shove attempt, and you have advantage in the contest.|

##### Pike
The pike is an 8-12 ft spear designed for infantry in a phalanx formation against an opposing line. A master with the Pike learns to fight as a phalanx soldier, using his ally as cover, but deftly striking around him without detriment.

||
|:--|:--|
| Simple |Two Handed, Melee d8, Brace, Heavy, Reach|
| Martial |Two Handed, Melee d12, Brace, Heavy, Lunge, Reach|
| Master |Two Handed, Melee 2d8, Brace, Heavy, Lunge, Reach |
| Master Perk |No creature gives half cover to your enemy while at reach. Your allies still provide half cover to you.|

##### War Spear
A war spear is different from a simple spear in that it is designed to resist cutting its shaft, and has weight in the pommel, making it more balanced for martial techniques while paired with a shield. A war spear can be used as a throwing weapon, but not as effectively as a javelin.

||
|:--|:--|
| Simple |Two Handed, Melee d8, Awkward|
| Martial |One Handed, Melee d8, Thrown (20/60), Double Ended d4, Finesse, Versatile d10|
| Master |One Handed, Melee d10, Thrown (30/120), Double Ended d4, Finesse, Versatile d12|
| Master Perk |If you hit the same target twice in a row, your second hit deals an extra d6 damage. As long as you continue to hit the same target, even between turns, you deal the extra damage. If you ever miss or change targets you must start this process over. |

##### Ravenbeak
A ravenbeak is a spear that looks similar to a warspear but has a crescent shaped hook on one side of the tip, which can be used to hook or slash. The hook is often sharpened and can be devastating if used properly. A master is an expert at manipulating the enemy with the hook and tip.

||
|:--|:--|
| Simple |Two Handed, Melee d8, Brace, Heavy, Reach, Trip |
| Martial |Two Handed, Melee d8, Brace, Entangle, Heavy, Lunge, Reach, Trip |
| Master |Two Handed, Melee d8, Brace, Disarm, Entangle, Heavy, Lunge, Reach, Trip |
| Master Perk |While at reach, you ignore any shield AC. Additionally, your disarms deal full weapon damage on success.|

##### Trident
Traditionally a fishing tool, the trident can be repurposed for war with some modification. Three prongs deal more reliable damage than a simple spear, and can trap and bind weapons. The master trident user finds particularly devastating attacks while throwing it, and can disarm with ease.

||
|:--|:--|
| Simple |One Handed, Melee d6, Awkward|
| Martial |One Handed, Melee d8, Disarm, Thrown (20/60), Versatile 2d4|
| Master |One Handed, Melee d12, Deflect 3d4, Disarm, Thrown (30/120), Versatile 3d4|
| Master Perk |If you hit with a Thrown attack, the enemy must succeed on a Strength saving throw or their speed is reduced by half until they use an action to remove it. If an enemy misses you with a melee weapon attack, you may use your reaction to attempt a disarm. |






<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>


<div class='pageNumber auto'></div>
<div class='footnote'>SPEARS</div>
\page



# Throwing Weapons
<div class='wide'>

| Weapon | Damage Types |Simple Damage|Martial Damage|Master Damage| Weight|Gold Cost
|:--|:--|:--:|:--:|:--:|--:|--:
|Bolas|Bludgeoning|d4|d4|d4|2|1
|Boomerang|Bludgeoning or slashing|d6|d6|d6|1|3
|Chakram|Slashing|d4|d4|d8|0.1|0.1
|Dart|Piercing|d4|d4|d6|0.05|0.1
|Net|No Damage|0|0|0|3|1
|Orc Throwing Shot|Bludgeoning|d8|d10|d12|16|0.5|
|Throwing Star|Piercing|d4|d4|d4|0.05|0.1|
|Throwing Knife|bludgeoning, Piercing or Slashing|d4|d4|d4|0.05|0.1

</div>

### Feat: Throwing Weapon Master
- You may throw anything with proficiency. Additionally, you may throw with your off hand, and add your ability modifier to the damage roll. When you throw a weapon, you may draw a new one as part of your attack.
- Throwing a weapon ignores half cover.
- You threaten 10ft around you and can make a ranged Opportunity Attack if an enemy leaves your threatened space. 
- You do not suffer disadvantage to ranged attacks at long range and do not suffer disadvantage to ranged attacks made while an enemy is within 5ft of you.

##### Bolas
A bolas is a pair of weights, connected by a thin rope <br>or cord reinforced with metal links to prevent the <br>prey from simply biting or tearing the bolas to escape. <br>The master bolo learns to accurately target his prey,<br> bringing them down by binding the legs. 

A bolas has an AC of 15 and 2HP and is immune to bludgeoning damage. When your enemy succeeds at a<br> save to escape or reduces the bolas to 0hp, it is destroyed.

||
|:--|:--|
| Simple |One Handed, Thrown d4 (10/30) Awkward|
| Martial |One Handed, Thrown d4 (20/30), Entangle|
| Master |One Handed, Thrown d4 (40/60), Entangle, Trip. |
| Master Perk | On a hit, you deal your weapon's normal <br>damage and your enemy must succeed on a save against separately, an Entangle and Trip. |


##### Boomerang
 A hooked piece of hardwood or metal, curved in a way which provides lift. Every time you make a ranged attack the weapon returns to you. Additionally, the weapon is stout enough to use in melee, and the master can curve the weapon to hit more than one target at a time. 

||
|:--|:--|
| Simple |One Handed, Melee d6, Thrown (30/120), Awkward, Light|
| Martial |One Handed, Melee d6, Thrown (40/120), <br>Light|
| Master |One Handed, Melee d6, Thrown (80/240, Light|
| Master Perk |You ignore cover and can target two separate targets within your normal range with one attack.|

```
```


<img 
  src='https://i.imgur.com/Kl8vsRQ.png' 
  style='position:absolute; bottom:-60px; right:-50px; width:525px' />

<div class='pageNumber auto'></div>
<div class='footnote'>THROWING WEAPONS</div>
\page

##### Chakram
The chakram is an elegant and highly portable thrown weapon. It is a flat, open-centered metal discus with a sharpened edge.  This weapon returns to you like a boomerang if your target is within normal range. Dangerous from all angles, the master can react quickly, throwing or slashing as a reaction to someone missing the mark. 

||
|:--|:--|
| Simple |One Handed, Melee d4, Thrown (20/60), Awkward, Light|
| Martial |One Handed, Melee d6, Thrown (40/120), Finesse, Light|
| Master |One Handed, Melee d8, Thrown (80/500), Finesse, Light|
| Master Perk |If a creature misses you with a ranged or melee attack, you can use your reaction to make a ranged or melee attack against that creature. |


##### Dart
More similar to a lawn dart than a pub dart, this throwing weapon is smaller than a javelin, typically fletched like an arrow and weighted with lead. It’s superior piercing capability and weighted tip allow the master to pin targets to walls if the conditions are right.

||
|:--|:--|
| Simple |One Handed, Thrown d4, (20/60) Finesse, Light, Penetrate|
| Martial |One Handed, Thrown d4, (30/60) Finesse,  Light, Penetrate|
| Master |One Handed, Thrown d6, (60/120) Finesse, Light, Penetrate|
| Master Perk |When you land a hit, you can choose to deal no damage and instead pin the enemy to an adjacent wall or obstacle such as a tree or boulder. Your enemy is restrained, the escape DC is your weapon DC. |


##### Net
A net is used to entangle enemies. A large or smaller creature hit by a net is restrained until freed. Dealing 5 slashing damage to the net (AC10) also frees the creature without harming it, ending the effect and destroying the net. A normal net cannot be used against category size Huge or larger enemies, but larger nets can be made at four times the cost and weight which can target Huge targets, while a net for gargantuan targets may not be able to be made with normal materials or wielded by a medium creature.

||
|:--|:--|
| Simple |Two handed, Thrown, Awkward.|
| Martial |Two Handed, Thrown (10ft) Entangle|
| Master |One Handed, Thrown (15ft), Deflect d6, Entangle, Light, Trip|
| Master Perk |If you have advantage when you entangle your enemy, it has disadvantage on the check made to escape.|

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

```
```

##### Throwing Shot
An Orcish invention, the throwing Shot is a heavy iron ball used offensively as a thrown weapon. A creature must take time to wind up and throw the shot, and even aloft it cannot travel as far as other throwing weapons. However, such a heavy weapon in flight is fearsome; not many can stand up to the impact. A master is deadly accurate with the shot and is able to target an enemy's head to stun them with ease.  A creature with Strength less than 13 cannot wield a shot at all. 

||
|:--|:--|
| Simple |Two Handed, Thrown d8 (10ft) Awkward, Penetrate|
| Martial |Two Handed, Thrown d10 (20/60), Penetrate, Trip|
| Master |One Handed, Thrown d12 (30/90), Disarm, Penetrate, Trip|
| Master Perk |If you have advantage and both dice would have hit, or if you score a critical hit, your enemy is stunned until the end of its next turn. If you have disadvantage and one dice would have hit, deal your strength modifier in damage to the target, though this still counts as a miss. |



##### Throwing Star
These small pointed disks are constructed from thin, flat plates of metal derived from a variety of sources including coins, carpentry tools, washers or nail removers. They often have a hole in the center and sharpened tips in a concentric pattern. The flat, small design of these weapons allows many to be palmed at once and thrown all together.


||
|:--|:--|
| Simple |One Handed, Thrown d4 (10/30), Finesse, Light|
| Martial |One Handed, Thrown d4 (20/60) Finesse, Light|
| Master |One Handed, Thrown d4 (40/120) Finesse, Light|
| Master Perk |As an Action, you can force all targets of your choice in a 15ft cone to succeed on a Dexterity Saving Throw or suffer d4 plus your choice of Strength or Dexterity modifier in piercing damage. You throw as many stars as there are valid targets.|


##### Throwing Knife
These small pocket knives are much smaller than any dagger, and resemble more utility knives or paring knives than real weapons. However, they can be easily hidden, and offer more range when thrown due to slightly more weight in their handles. A throwing knife master has the capability to dance in a quick circle, throwing knives at all foes around him, though this leaves him open to attack.


||
|:--|:--|
| Simple |One Handed, Melee d4, Thrown (10/30), Awkward, Conceal, Finesse, Light|
| Martial |One Handed, Melee d4, Thrown (20/60) Conceal, Finesse, Light|
| Master |One Handed, Melee d4, Thrown (40/120) Conceal, Finesse, Light|
| Master Perk | As an action, you can force all targets of your choice within 10ft to succeed on a Dexterity Saving Throw or take d4 plus your choice of your Strength or Dexterity modifier in piercing damage. You throw as many knives as there are valid targets.|






<div class='pageNumber auto'></div>
<div class='footnote'>THROWING WEAPONS</div>
\page
### Credits

Homebrew by Commander Fayne, aka Veritoss43 on Reddit.

All rights reserved except which are copyright of their respective holders. All art used is credited without permission under "Fair Use." This material may not be sold, resold or profited from in any way, in accordance with Fair Use. 
##### Page Art Credit
- Cover Page Art - Wenjun Lin
- "Weapon Rack" by Leesha Hannigan, pg 2
- "The Second Labor of Heracles" Stepan Alekseev, pg 3
- Copyright Mortal Online, pg 5
- "20" Stepan Alekseev, pg 6
- "Thief" Daria Rashev, pg 7
- "Robin Hood" Stefan Kopinksi, pg 8
- "Ana" Daniel Kamarudin, pg 9
- "Sparticus" Wenjun Lin, pg 10
- Untitled Wenjun Lin, pg 11
- "Shield of Faith" Steve Goad, pg 12
- "A Dance for the Lord" by Gabriel Tan, pg 13 
- Kim Ha Yeong, pg 15
- "Priest" by Russell Dongjun Lu, pg 17
- "Wild Hunter" by Russell Dongjun Lu, pg 19
- "Brego" Manuel Castanon, pg 21
- "Demon Hunter" copyright Blizzard, pg 23
- "Assassin" by Russell Dongjun Lu, 25
- "Musket Knight" by Ariel Perez, pg 27
- "Penitent" Russell Dongjun Lu, pg 29
- "Dauntless Bodyguard" Manuel Castanon, pg 31
- "Baptism of Blood" by Xiaoyu Wang, pg 33
- "Barbarian Ranger" by Russell Dongjun Lu, pg 35
- "Bard Throwing Star" by Stefan Skellen, pg 37
- "Viking Weapon Arrangement" <br>Russell Dongjun Lu, pg 39

<div class='toc'>
- ##### [<span></span><span>Return to Top</span>](#p2)

</div>

```
```
>### Join the Discord!
> Have questions or comments to give to the development team of Revised Martial Equipment or any other Commander brew? Join our discord! All critique is welcome and we'll be glad to have your feedback. 
>
>https://discord.gg/Wemuw7j


<img 
  src='https://i.imgur.com/LbmwZwe.png' 
  style='position:absolute; bottom:-10px; right:-10px; width:830px' />

<div class='pageNumber auto'></div>
<div class='footnote'>CREDITS</div>





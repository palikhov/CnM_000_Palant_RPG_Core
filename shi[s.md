<style>
  .phb#p4:after { display:none; }
  .phb#p5:after { display:none; }

/* Background */
  .phb{ background-image: url('https://gmbinder.com/images/KN1O92T.png') }
  .phb{ background-size: cover }

/* Notes */
  .phb section blockquote {background-color: #f6e5d4}
  .phb hr + section blockquote tr:nth-child(odd) td {background-color: transparent;}

/* Tables */
  table tr:nth-child(odd) td {background-color: #cccccc}

/* Footer */
  .phb .pageNumber {color: rgba(0, 0, 0, 0.5)}
  .phb .footnote {color: rgba(0, 0, 0, 0.5)}
  .phb:nth-child(odd):after{ 
    content          : '';
    position         : absolute;
    bottom           : -3px;
    left             : 10px;
    z-index          : -1;
    height           : 336px;
    width            : 100%;
    background-image : url('https://gmbinder.com/images/p7wvb4z.png');
    background-size  : cover;
}

.phb:nth-child(even):after{ 
    content          : '';
    position         : absolute;
    bottom           : -3px;
    left             : -10px;
    z-index          : -1;
    height           : 336px;
    width            : 100%;
    background-image : url('https://gmbinder.com/images/p7wvb4z.png');
    background-size  : cover;
}

/* Page Number */
.phb .pageNumber{
    position   : absolute;
    bottom     : 30px;
    width      : 50px;
    text-align : center;
}
.phb:nth-child(even) .pageNumber{
    left      : 12px;
}
.phb:nth-child(odd) .pageNumber{
    right      : 12px;
}

.phb .pageNumber.auto{
    position   : absolute;
    bottom     : 41px;
    width      : 50px;
    text-align : center;
}
.phb:nth-child(even) .pageNumber.auto{
    left      : 12px;
}
.phb:nth-child(odd) .pageNumber.auto{
    right      : 12px;
}

</style>


# Ships, Airships and Sailing

There is nothing like the freedom of sailing the world on your own vessel with your trusted crew. These are rules to let own, upgrade and crew a ship. These rules apply to airships as much as water based ships; if a rule applies differently to an airship, it will be stated. These rules try to be as general as possible so that they can apply to any setting, any ship and any design you may desire.

### Owning a Ship
The first step to being able to sail the world is getting hold of a ship in the first place. Purchasing a ship is a fairly simply affair, provided you have the coin, favours or bargaining power. However, there are more costs required to keep the ship is good condition.

#### Renting and Salvaging
You may only need a ship for a short time, in which case, you can rent a ship instead of buying one. The price for renting a ship for a week is 10% of its total cost however this does not necessarily include the cost of the crew members.

You may find a wrecked ship and want to salvage it and restore it to it's former glory. the cost to restore a ship depends on the state of the wreck. For example, if roughly half of the ship needs to be replaced or repaired, the cost of repairing the ship would be 50% of the total purchase price.

#### Repairs
You ship is likely to become damaged through combat, harsh weather and other means and so it needs to be repaired. While the ship is docked at a port, you may spend 1% of the ship's purchase price to increase a durability die by 1.

You may try to repair the ship while docked in a place without a port or facilities that can perform repairs. You may still try to repair the ship if the DM allows it, although it may cost more or require time spent finding materials and carrying out the repairs yourself.

### Crew
Crew members are unskilled hirelings that are in your service; the cost for food, drink and other basic supplies is included in the cost for hiring them. Ships have required amounts of crew to be able to move, use weapons and repair the ship.

Crew members can be incapacitated through disease or injury. At the end of the round, roll 1d20. On a 10 or higher, the crew member is stabilised; on a 9 or lower, crew member dies. A stabilised crew member is still incapacitated but it not at risk of dying. 

At the end of a long rest, roll 1d20 for each stabilised crew member; on a 15, the crew member recovers and is no longer incapacitated.

\columnbreak

### Roles
There are certain roles on a ship which allow a ship to run smoothly and effectively. There a necessary roles and optional roles; necessary roles need to be filled or the ship will not be able to function; optional roles can improve the operation of the ship. Roles can be filled by a PC or a skilled NPC hireling and one person can fill multiple roles if the DM believes that it is reasonable that they should be able to. A person filling a role counts towards the required crew count.

#### Necessary Roles

##### Pilot
Pilots the ship and orders crew to enable the ship to move. The pilot makes Wisdom (Sea Vehicles) checks to maneuver the ship to prevent damage or other effects during dangerous scenarios such as storms or landing. The ship cannot move of there is no pilot.

##### First Mate
A first mate's job is to keep the crew in line and ensure that order is maintained. They must make Charisma (Morale) ability checks (using the morale modifier of the ship) to keep crew under control and maintain order after a hard hits or during gruelling circumstances. If there is no first mate, the crew automatically fail at Charisma (Morale) checks.

##### Gunner
A gunner manages and orders the use of weapons, declaring when to fire and teaching the crew how to effectively use the weapons. They make attack rolls to fire weapons using their proficiency in sea vehicles among other things. If there is no gunner, no weapons can be used.

##### Navigator
The navigator ensures that the ship is headed on the correct course and that it will not run into trouble. They make Intelligence (Navigator's Tools) ability checks to plot the correct course for the ship. Failure of these checks can result in getting lost, moving at half speed or crashing. The difficulty is determined by the DM and depends on the weather, familiarity with the area and possession of a map or chart. Checks made to navigate the ship automatically fail if there is no navigator.

##### Optional Roles

##### Boatswain
A boatswain oversees the repairing of the ship and can keep it afloat in dire circumstances. They make checks to repair aspects of the ship. When the ship is being repaired at a dock, the boatswain can make an appropriate ability check to reduce the cost of repairs by half. (See repair phase for more detail)

\pagebreak

##### Surgeon
A surgeon looks after the health of the crew and prevents deaths at sea. During combat, they can get crew back on their feet and they can aid the recovery of crew members. 

##### Cook
A cook prepares food and drink for sailors to improve morale. At the end of a long rest, the cook may make either a DC 12 Constitution (Cook's Utensils) or Constitution (Brewers supplies) check. The morale of the crew is raised by 1 for every 3 above the DC the check scores. (E.G. the cook rolls a 19. This is 7 above 12 so the crew gets a +2 to morale)

### Sailing
The rules for travelling in chapter 8 of the PHB mostly apply the same way to sailing. Travelling for longer than 8 hours can cause exhaustion, the ship moves at half speed in difficult terrain, the ship can move at different paces with the corresponding effects, threats are detected in the same way and other activities can be done during travel. However, the ship can only move stealthily at a slow pace and is obscured by something such as fog, terrain or night. Additionally, marching order only applies when there are multiple ships moving together.

##### Travel Pace
**Distance travelled in a hour with different ship speeds at different paces**
 Ship Speed | Slow Pace | Medium Pace | Fast Pace |
|:---:|:---:|:---:|:---:|
| 40 ft. | 3 miles | 4 miles | 6 miles |
| 60 ft. | 4 miles | 6 miles | 8 miles |
| 80 ft. | 6 miles | 8 miles | 10 miles |
| 100 ft. | 8 miles | 10 miles | 12 miles |
| 120 ft. | 9 miles | 12 miles | 15 miles |

### Health and Damage
The state of the hull and propulsion of a ship is measured by a durability die (1d4, 1d6, 1d12, etc). This acts as the ship's hit points so when the ship is fully repaired, the durability die is at the maximum value. The hull and the propulsion have separate durability dice and ACs. 

Whenever the hull or the propulsion takes damage, the durability die is reduced. If the hull's durability is reduced to 0, the ship sinks and cannot be repaired. If the propulsion's durability die is reduced to half its maximum value, the ship moves at half speed. If it is reduced to 0, the ship cannot move at all.

\columnbreak

### Combat Rules
Combat occurs in 1 minute rounds where all combatants follow these steps simultaneously:

1. **Assign Crew** - Crew members are assigned to the different tasks on the ship
2. **Ship Movement** - The pilot attempts to have the ship move towards or away from an enemy
3. **Fire Weapons** - The gunner has manned weapons on the ship fire or reload
4. **Treat Crew** - The surgeon can treat crew members to get them back on their feet
5. **Repairs** - The boatswain creates temporary repairs to keep the ship intact

#### Assigning Crew
At the start of a round, any active crew members can be assigned to help with different actions, providing a bonus to the action they are assigned to. Incapacitated crew members cannot help with actions. 

#### Ship Movement
The pilot decides where the ship is trying to move to in relation to one other enemy ship (Long, medium, short, boarding, flee). They then make a Wisdom (Sea Vehicles) check with a +1 bonus for every crew member assigned. If the ship is moving at half speed, the check has disadvantage. If the ship has a movement speed at least 40 ft. greater than their opponents, then they have advantage.

The result of the checks from each pilot is compared. The distance between the ships is set to what the pilot with the higher of the two checks wanted. If the checks are equal, the pilot with the higher modifier is successful.

This is repeated for each enemy ship.

At the end of this phase, if the ships are within boarding distance and the crew of at least one ship wants to board, the combat changes to normal character based combat. The fight is between the significant members of the ship (people who aren't ordinary crew) as it is assumed that the crew will fight each other.

>For example, Burdas wants his ship to be at a medium distance to allow for use of the cannons and Messla wants her ship to go into boarding range.
>
>Burdas makes a check using his wisdom mod of +2, proficiency in sea vehicles of +3 and another +1 from an assigned crew member and gets a total of 24. 
>
>Messla makes the check with a +4 from her wisdom, a +2 from proficiency and +4 from crew members assigned, as they really want to board, and gets a 15. 
>
>Burdas has the higher role so there is a medium distance between the ships.

\pagebreak

#### Fire Weapons
In order to fire a weapon, a number of crew members equal to the required crew of the weapon need to the allocated to the weapon in order for it to fire. The gunner then makes an attack roll using their proficiency in Sea Vehicles and the accuracy of the weapons as modifiers. For every crew member assigned above the required crew number, the check gains an additional +1. 

If a 20 is rolled on the die, the attack is a critical hit. On a critical hit, you incapacitate 1d4 crew members in addition to dealing damage.

Characters can also make attacks of their own as part of this phase however, they cannot act as part of any other role or contribute as a crew member.

An attack or spell can be used on a ship at a short distance of the range of the attack is at least 100 ft., ff the ship is at medium distance, the attack or spell needs a range of 300 ft. and if the attack is at a long distance, the attack or spell needs a range of at least 600 ft.

Attacks rolls are made against the ship's hull AC and damage crew members. For every successful attack roll, 1 crew member is incapacitated. 

Spells that require a Strength, Dexterity or Constitution saving throw are replaced by the pilot making a Wisdom (Sea Vehicles) and spells that require an Intelligence, Wisdom or Charisma saving throw are replaced by a Charisma (Morale) check by the first mate.

If a spell is an area of effect spell, it incapacitates a number of crew members equal to your spellcasting ability modifier.

#### Treat Crew
The surgeon can make a Wisdom (Medicine) to treat  one crew member. If the roll is 12 or greater, the crew member stabilised; if the roll is 20 or greater, the crew member is fully recovered. 

For every crew member assigned to the action, the surgeon can make 1 extra check to heal a crew member (E.G. 2 assigned crew members means that 3 incapacitated crew members can be treated). Multiple treatment rolls can be made on the same crew member.

#### Repairs
The boatswain can try to repair the hull or the propulsion. They make an appropriate tool proficiency check depending on the material they are repairing. The check also receives an additional +1 for every crew member assigned to the action. The DC for the check is equal to the AC of the part.

If successful, the durability die is increase by 1 plus 1 more for every 5 the check is above the DC. Additionally, if successful, any fires on the repaired part are extinguished.

However, the repairs made by the boatswain are temporary and the durability of the ship part returns to what it would have been if no repairs had been made unless the durability of a part would fall to 0, in which case, it falls to 1. For example, if the propulsion takes starts at 6 durability, takes 4 points of damage and is then repaired for 3, after the fight, the durability of the propulsion falls to 2, as if it had never been repaired.

It is possible to permanently repair the ship through spell casting or by having materials available on the ship, though this typically takes at least 10 minutes for 1 point of durability at a time. The specifics are up to the DM however, a guideline is that a second level spell is required to restore 1 point of durability.

Below is a table of abilities and tools required to fix certain materials. To fix arcane devices, a spellcaster must expend a spell slot and make a spellcasting check (spellcasting ability modifier + proficiency modifier); the ship's durability is increased by half the level of the spell slot expended.

| Material | Ability | Tool |
|:---:|:---:|:---:|
| Wood | Strength | Carpenter's tools |
| Metal | Strength | Smith's tools |
| Fabric | Dexterity | Weavers tools |
| Leather | Dexterity | Leatherworker's tools |
| Mechanical Devices | Intelligence | Tinker's tools |

### Distances

Distances are either boarding, short, medium or long. These are rough approximations as the distances in naval warfare are too large and varying to be measured accurately. Boarding distance is almost directly net to each other; a person could fairly easily get from one ship to the other. Short is just outside that range, from 10 metres to 30 metres or 30 feet to 100 feet away. Medium is between 30 metres and 100 meters or 100 feet and 300 feet. Long is between 100 meters and 200 meters or 300 feet and 650 feet.

A ship can move between short and medium range or between medium and long range as part of the movement on its turn but has to take the full speed action to move between long and short range unless your ship's speed is 80 ft. or greater.

<div class='descriptive'>
 
 ##### Design Thoughts
 These rules originally started out as rules for airships before I quickly realised that they could just as easily be used for normal water-based ships. This explains the somewhat vague language like "propulsion" instead of "sails". 
 
 I wanted to make the ships simple enough to be usable but detailed enough for the ships to feel personal and precious so that people enjoy using them and owning them and so they're not forgotten.
 
 Also things like the durability dice were inspired by Matt Colville's Strongholds and Followers and the way it handles the health of military units.
</div>

\pagebreak

<div class='classTable wide'>

##### Ballista
| Name  | Accuracy | Range | Damage | Required Crew | Additional Effects | Cost |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Ballista | +5 | Medium | 1 | 4 |  | 500 gp |
| Long range ballista | +5 | Long | 1 | 4 |  | 650 gp |
| Splintering ballista | +5 | Medium | 1 | 4 | Crits are scored on a 19-20 | 700 gp |
| Elven Ballista | +7 | Medium | 1 | 4 |  |  1000 gp |

##### Cannons
**Once fired, cannons require one turn to reload. This is done as part of the fire weapons action if enough crew members are assigned.**
| Name | Accuracy | Range | Damage | Required Crew | Additional Effects | Cost |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Cannon | +3 | Medium | 3 | 8 |  | 800 gp |
| Long Range Cannon | +2 | Long | 3 | 8 |  | 1000 gp |
| Explosive Cannon | +3 | Short | 3 | 8 | Crits are scored on a 19-20 | 1000 gp |
| Large Calibre Cannon | +2 | Medium | 4 | 8 |  | 1400 gp |
| Arcane Cannon | +5 | Medium | 3 | 4 |  | 2000 gp |
| Charged Arcane Cannon | +6 | Short | 4 | 4 | If the attack roll is below 15, deal a point of damage to your own hull | 2500 gp |

##### Other Weapons
| Name | Accuracy | Range | Damage | Required Crew | Additional Effects | Cost |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Flamethrower | +3 | Boarding | 0 | 2 | Sets the the target alight and deals 1 point of damage every turn until extinguished | 700 gp |
| Ram | +3 | Boarding | 3 | 0 |  | 800 gp |

##### Shot
| Name | Effect | Cost |
|:---:|:--:|:---:|
| Grape Shot | Can only be used to attack the hull; deals no damage but incapacitate a crew member plus one additional crew member for every 3 above the attack roll is above the hull AC.| 50 gp per round of shot |
| Incendiary Shot | On hit, deals no damage to ship but Sets the the target alight and deals 1 point of damage every turn **until** extinguished | 30 gp per round of shot |

</div>

\pagebreak

<div class='classTable wide'>

##### Armour Upgrades
**These can be applied to either the hull or the propulsion and act separately.**
| Name | Effect | Cost |
|:---:|:---:|:---:|
| Reinforcing Boards | Increase AC by 1 | 600 gp |
| Metal Reinforcement | Increases AC by 2 and incendiary attacks have disadvantage | 1000 gp |
| Metal Plating | Increase AC by 4, incendiary attacks have disadvantage and the ship's speed is reduced by 20 ft. | 200 gp |

##### Other Upgrades
| Name | Effect | Cost |
|:---:|:---:|:---:|
| Improved Propulsion | The ship's speed increases by 20 ft. | 600 gp |
| Arcane Propulsion | There are no penalties to having the propulsion's durability below half, however the effect of having durability reduced to 0 is the same | 1000 gp |

</div>

<div class='classTable wide'>

### Types of Ship
The cost of the ship doesn't include any weapons or other upgrades.

| Ship Type | Speed | Hull AC | Hull Die | Propulsion AC | Propulsion Die | Weapons Capacity | Crew Capacity | Cost |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Cog | 40 ft. | 10 | 1d6 | 12 | 1d4 | 0 | 5 | 2,000 gp |
| Caravel | 100 ft. | 11 | 1d6 | 13 | 1d4 | 1 | 10 | 5,000 gp |
| Carrack | 60 ft. | 15 | 1d8 | 16 | 1d6 | 2 | 20 | 10,000 gp |
| Voyager | 80 ft. | 14 | 1d8 | 14 | 1d4 | 1 | 15 | 10,000 gp |
| Barge | 40 ft. | 16 | 1d12 | 17 | 1d8 | 2 | 30 | 15,000 gp |
| Galley | 40 ft. | 18 | 1d10 | 19 | 1d8 | 3 | 30 | 20,000 gp |
| Balinger | 100 ft. | 16 | 1d8 | 17 | 1d6 | 2 | 30 | 20,000 gp |
| Galleon | 60 ft. | 19 | 1d12 | 21 | 1d8 | 3 | 40 |30,000 gp |

</div>

# Setup for the first Mission

Shuffle the Skirmish Deployment cards of all available heroes and draw 8 cards at random. These are the starting heroes. Place them aside into an area called "Troop pool". The player then chooses 3 of those heroes to field in the first mission of the campaign. Set the Hero Sheets of these heroes on the table.

Choose each hero to be equipped with one of the following weapons:  
![A280 Carbine](./Custom%20Cards/A280%20Carbine.png)  
![Glie-44](./Custom%20Cards/Glie-44.png)  
![Plasteel Staff](./Custom%20Cards/Plasteel%20Staff.png)  

Additionally, choose each hero to carry one of the following Accessories:  
![Medkit](./Custom%20Cards/Medkit.png)  
![Kinetic Detonator](./Custom%20Cards/Kinetic%20Detonator.png)  

The starting Mission is “The Logbook”. Jump to the [Story Mission document](./Story%20Missions.md) and set up the first mission accordingly.
# Campaign Setup (after the initial mission)

* Shuffle all available green and grey side missions into the Side Mission deck.
* If at any time the Side Mission Deck would be empty, shuffle the discarded Side Missions back into the deck.
* Set the Threat level to 1.
* Clone the [IA - Covert Operations Campaign Sheet](https://docs.google.com/spreadsheets/d/18BkZr6Z7Gd6banwmM_WRkf6pnBNkgX9nVi0hL4KxH2E/edit?usp=drive_link) and use it to track the campaign.

# Campaign Round Steps

* Transfer damage from Hero Sheets to the respective Deployment Cards or their section in the campaign sheet.
	* Add 2 damage per face down [Medkit](./New%20Items%20and%20Starting%20Weapons.md) to a hero. Then remove facedown Medkits.
* Draw 3 new Side Missions.
* Heroes recover Damage.
  * Roll 3 red dice for each wounded hero. Remove 2 damage for each Damage rolled from the deployment card of that hero.
* Spend XP on heroes to add Class Cards.
* Heroes cannot spend XP on cards that cost 4 or more XP unless the appropriate research "Commander Training" is completed.
* Facility functions
  * Dedicate each hero to a facility.
  * Roll the appropriate dice
  * Resolve any results
  * Place 1 Strain on each hero that resolved their function.
	  * If hero is dedicated to the "Train Troop" or "Infirmary bed" functions, place 2 Strain on their Deployment Card.
* Resolve special actions of facilities
* Spend credits to buy any unlocked items, facilities, upgrades, troops, …
* Remove Strain from hero Deployment Cards.
* Advance the Campaign Timer
* Pick a new mission.
	* Story Missions can only be played once unlocked. See [[Story Missions]] for details.
	* If the picked mission is a Side Mission, discard all other available Side Missions.
* Pick and amount of  heroes up to the shuttle capacity to join the mission.
  * Heroes with Damage or Strain can not be chosen for the squad.

# Side Mission rewards

Ignore all rewards from Side Missions. Heroes that complete a Side Mission (not all heroes are withdrawn) earn 1 XP and 100 credits (in total).

Additional, rewards are based on the color of the side Mission:
* Green Side Missions reward a new hero for the troop roster. After completing a Green Side Mission without all heroes being withdrawn, shuffle the hero deck and draw on hero. Add that hero to your troop roster.
* Grey Side Missions reward an additional 150 Credits after competing it without all heroes being withdrawn.
* Red Side Missions reward either 10 Research Points or 10 Engineering Points. Players choose which.

# Campaign Timer

To advance the Campaign Timer, roll 3 red dice and count Damage. Add all Damage as progress to the ODS Tracker. Imperial Units improve for all missions based on the tracker value:
  * ODS 10: +1 Health
  * ODS 20: +1 Evade
  * ODS 30: +1 Threat Level
  * ODS 40: +1 Damage, +1 Surge  — Tier-1 border —
  * ODS 50: TBD
  * ODS 60: TBD
  * ODS 70: TBD
  * ODS 80: TBD  — Tier-2 border —
  * ODS 90: TBD
  * ODS 100: TBD
  * ODS 110: TBD
  * ODS 120: TBD
Some effects can reduce the progress on the ODS Tracker. Points can not be reduced below a Tier border. For instance, once the tracker reaches 40 Points it can no longer be reduced below 40 points.

# Facilities and space on the Cruiser

## Free rooms for facilities

The [RSV Lance](https://starwars.fandom.com/wiki/Gozanti-class_cruiser) has a working engineering station, a research lab, and 8 unused rooms that the player can build additional facilities in. Some facilities may be required to advance the campaign story missions. Facilities (only if they are not mandatory for campaign progress) can be torn down to free up rooms. Tearing down a room does not cost resources or time but also doesn’t refund spent resources during construction of the facility.
## Standard Facilities

### Engineering
Buy starting and unlocked items.  
* Build new facilities:  
	* Heroes dedicated to Engineering roll their Tech test. Add resulting surges to the Engineering Progress of the current facility.  
	* Facilities can be bought without putting Engineering Progress on them. Engineering Progress can be split across multiple facilities.  
	* If a facility is completed in this step, special actions from facilities can be resolved in the same campaign round. “Overflow Engineering Progress” can be added to a new facility, provided the player has enough money to buy it or already bought it pior.  

### Research
* Conduct research.  
	* Dedicated heroes roll their Insight test. Add resulting surges to the Research Progress of any available project.  
	* Research Progress cannot be split across multiple projects.  
	* If a research project is completed in this step, the resulting buy options can be resolved in the same campaign round. “Overflow Research Progress” cannot be added to a new project.  
## Buildable Facilities

These facilities can be built into one of the free rooms on the RSV Lance. The Lance's Power Grid has a maximum load of 15 for all facilities.
### Rhydonium Converter
Cost
* 350 Credits
* 35 Engineering Progress

Power draw: 0  

Abilities
* Adds 5 to the maximum load of the RSV Lance Power Grid.  

Upgrades:
* Increase the maxmium load by an additional 5. Cost: 150 Credits

### Lab
Cost
* 350 Credits
* 35 Engineering Progress

Power draw: 3  

Abilities
* +2 Surges per dedicated troop member for research.

Upgrades:
* More work benches: Additional +2 Surges per dedicated troop member for research. Cost: 200 Credits
### Workshop
Cost:
* 150 Credits
* 15 Engineering Progress. 

Power draw: 6  

Abilities
* +1 Surge per dedicated troop member for building facilities or droids (droids are mechanized troops that do not get wound penalties and will be introduced with the [[README#Reworked Characters and Abilities ~Q4/26 - Rebel Reinforcements|Rebel Reinforcements]] Update).  
* Unlocks Heavy Weapons and Special Weapons research.  
* Unlocks Upgrades for other facilities.
### Troop Training
Cost:
* 250 Credits
* 25 Engineering Progress

Power draw: 5

Abilities
* Unlocks "Commander Training" Research to unlock Skills that cost 4XP or more.  
* Train troop: Dedicate a hero (becomes unavailable for the following 2 missions) to gain 1XP. The hero cannot be dedicated to other tasks during that time.
* Buy Training Upgrades:
  * Physical Conditioning
    * Heroes get +1 health per XP skill they earned. This resolves retroactively for skills purchased before this Training Upgrade.
    * Cost: 100 Credits
  * Boom
    * +1 damage with grenades for heroes equipped with the [Under Barrel Launcher](./New%20Items%20and%20Starting%20Weapons.md) attachment.
    * Cost: 100 Credits
  * Ping
    * +1 surge and +3 accuracy when using a weapon with the ["Long Rifle" trait](./New%20Items%20and%20Starting%20Weapons.md) trait if the Target is 4 or more spaces away.
    * Weapons with the ["Long Rifle" trait](./New%20Items%20and%20Starting%20Weapons.md) can reduce their Accuracy by 2 to gain +2 Damage.
    * Cost: 100 Credits
  * Dead Shot
    * +1 damage and +1 Surge when attacking with a weapon with the  [“Gun” trait](./New%20Items%20and%20Starting%20Weapons.md) while within 2 range of the target space.
    * Cost: 100 Credits
  * Woosh
    * +1 Evade when wearing the [any Armor](./New%20Items%20and%20Starting%20Weapons.md).
    * Cost: 50 Credits

Upgrades:
* Upgrade: +2 slots for training troops. Cost: 120 Credits

### Infirmary
Cost:
* 300 Credits
* 25 Engineering Progress

Power draw: 8

Abilities
* Infirmary bed: Dedicate troops (max. 2) to the amount healed by 2. Dedicated heroes are unavailable for the next mission.  

Upgrades:  
* Bacta Tank: Choose a hero. Reduce the amount of damage on that hero by 10. Limit once per Campaign Round.  Cost: 350 Credits
* More beds: Increase the troops that can be dedicated here to a maximum of 6. Cost: 200 Credits
* Upgrade: Another Bacta Tank. Choose up to 2 heroes. Cost: 450 Credits
### Comms station
Cost:
* 50 Credits
* 15 Engineering Progress.

Power draw: 8

Abilities
  * Intel: Spend 50 credits to reduce the ODS timer by 1.

## Research Projects

### Heavy Weapons Tier-1
Cost: 20 Research Progress  
Gives access to
* ZX-9 Scatter Blaster
* Krayt Fang V-3

See [[New Items and Starting Weapons]].
### Special Weapons Tier-1
Cost: 25 Research Progress  
Gives access to
* Corellian E-9X
* M-5 Rotary Emitter

See [[New Items and Starting Weapons]].
### Armors Tier-1
Cost: 15 Research Progress  
Gives access to
* Combat Coat
* Dura Breastplate

See [[New Items and Starting Weapons]].
### Attachments Tier-1
Cost: 10 Research Progress  
Gives access to
* Grants +1 Attachment Slot
* Energy Cell
* Optical Scope
* Double Blade
* Under Barrel Launcher


See [[New Items and Starting Weapons]].
### Accessories Tier-1
Cost: 10 Research Progress  
Gives access to
* Flash Grenade
* Adrenal Stim

See [[New Items and Starting Weapons]].
### Shuttle +1 Seat
Cost: 30 Research Progress  
Allows for one additional hero to join on missions.
### Decrypt the Message
Cost: 25 Research Progress  
Unlocks the Double Agent Story Mission.
### Commander Training
Cost: 25 Research Progress  
Heroes can choose to spend XP to acquire Class Cards with an XP value of 4 or more.

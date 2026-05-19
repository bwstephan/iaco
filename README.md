# Vision

This document should give an overview of the mod and the high level concepts behind the changes. The .md files are authored with [Obsidian](https://obsidian.md/) and are best viewed with it. Some references into files won't work without it.
This Total Conversion (TC) draws heavily of the games XCOM: Enemy Within and XCOM2. In general, missions should flow quicker. More missions should be played in a campaign. It should be feasable to set up and play a Side Mission within 2 hours. The Strategy Layer (SL) should pose tough choices on which direction to develop first.
## Playing

The TC assumes you have a solid grasp on the fundamentals of Imperial Assault. All basic rules of Imperial Assault are in effect, unless detailed otherwise by the mod. The [Engine Changes](./Engine%20Changes.md) document aims to centralize all changes to the core mission gameplay.  
The mod is intended to be played with the assistance of Imperial Commander 2 (IC2) and designed as a single-player experience. Rounds should resolve quicker. The aim is to accomplish this by reducing choices within hero activations and increasing reliance on positioning/movement and mission progress. Custom Story Missions for IC2 will be available in the repository.
Subsequent modifications to unit templates in IC2 might appear to better fit the style of play. A custom campaign might be available in IC2 to better track campaign progression. At first, campaign progression will be handled via a .gsheet.

If you want to jump in and are experienced with Imperial Assault, start here at the [setup for the first mission](./Campaign%20Progression%20and%20Strategy%20Layer.md).
## Strategy Layer (SL)

The SL is a system that replaces the “Campaign Upgrade Stage” of the base game and the core part of the mod. Instead of buying gear revealed of a tier deck, The resources go into upgrading a run-down [Gozanti-class cruiser](https://starwars.fandom.com/wiki/Gozanti-class_cruiser), the **RSV Lance**, and an old [Sheathipede shuttle](https://starwars.fandom.com/wiki/Sheathipede-class_transport_shuttle). The cruiser can be fitted out with specialized facilities that improved the heroes and their effectiveness in battle. A list of facilities can be found in [the Campaign Progression and Strategy Layer](./Campaign%20Progression%20and%20Strategy%20Layer.md) document.
Ideas for additional facilities are:

* Droid bay to construct and repair droid heroes that that need to be repaired instead of healed. Maybe this will be rolled into the workshop.  
* A communication room to better communicate with resistance cells and Rebel High Command in other systems.  
* Defenses (outside and inside?) to repel imperial attacks/raids?  
* Upgrades for the Shuttle like capacity, cloaking, bombarding capabilities, …  
## Troops and Troop Management

The player can’t bring every hero for every mission. Heroes suffer wounds, preventing them from joining subsequent missions unless healed/rested. For this purpose, the player chooses 8 initial heroes as a starting squad that can be extended by hiring (spending credits) or winning over (via a Side Mission) additional heroes.  
Unlike in XCOM, troop flavor should not be fully interchangeable. Heroes in IA: CO should remain an identity via their:
* HP (and HP growth?)  
* Speed  
* Innate defense or offense  
* Innate skills
In the first versions, this will be shown by running with default Imperial Assault heroes.
## Missions and Mission Types

Story Missions and Side Missions will retain the same flavor.  
Story Missions will advance the narrative and be longer and harder than Side Missions, incentivizing the player to “prepare” for them.

Side Missions reward may reward
* Additional heroes (no Allies).
* Credits
* Specialized bonuses for Cruiser operations
* Short term boosts for Cruiser operatons (generate Engineering/Workshop output)
Side Missions will (later on) also spawn negative effects, similar the Threat Missions from the Return to Hoth expansion.

In general, missions will not have timers anymore. Pressure will come from limited healing opportunities as well as many weapons having a reload/overheat mechanic.

To prevent players from lingering too long before the next Story Mission, a Campaign Timer will make missions more difficult over time. This timer never fully resets and also jumps ahead after certain Story Missions, so missions will become more difficult eventually. The timer will be visible and interactible for the play, to create difficult choices on where to spend ressources or attention.
## Narration and Story

The setting should be more gritty and portray a progression of the troops from “scrappy soldier” to “elite operative group”. Permanent death of troops should be possible. Redesigned enemies should reflect this progression. Fighting Security Guards with smaller blasters first then encountering Storm Troopers and seeing specialized Stormtroopers or Royal Guards at the end.

The story will take place between 0 ABY (A New Hope) and 4 ABY (Return of the Jedi). **“Many Bothans died to bring us this information.”** should be the mantra for what happens in the narrative.  
The story should kicks off with the heroes discovering the acronym “ODS”. Over Tier-1, heroes ultimately learn that it is the acronym for a new Imperial initiative.
# Design Concept and Phases

## Concept

* Players are expected to be well-versed with standard Imperial Assault rules.
* Original Material should be used as much as possible.
* The project assumes that players have access to play material of all expansions (power tokens, tokens from specific hero characters, map tiles, missions, models, …).
* Rules for movement, line of sight, attacks and round phases should be changed as little as possible.
## Phases

### Initial Release \~Q2/26 \- A New Threat

* Works with traditional Heroes and their skill trees.
* Reworks some parts of the engine. See a full list in [[Engine Changes]].
* Introduces new starting weapons and weapons to research.
* Introduces new Gear and systems to research/acquire gear.
* Introduces the SL, the new campaign progression and how to acquire weapons, armor and accessories.
* Introduces the new narrative goal - only resolved up until the end of tier 1 of the campaign progression (4 story missions)
### Reworked Characters and Abilities \~Q4/26 \- Rebel Reinforcements

* All IA Heroes reworked.
* Some allies reworked as heroes.
* Classes reworked and more freely assignable to Heroes.
* Changes to enemies to resolved too much movement in IC2.
* Campaign starts with 3 seats on the Lambda T4 shuttle (upgradeable to 5).
* Introduces better wound and fatigue systems.
* Expands the new narrative goal \- only resolved until the end of tier 2 of the campaign progression (additional 4 story missions).
### Reworked Missions \~Q3/27 \- Unveiling

* Reworks many missions to better fit the campaign progression and SL.  
* Threats for Side Missions.
* Retaliation Timer that triggers Forced Missions.
* (Random) Villains introduced. Maybe tied to Agendas. Sub-plot to defeat them?
* More changes to enemies.
* Droid heroes that don’t suffer wounds?
* Finalizes the new narrative goal \- up to tier 3 of the campaign progression (additional 4 story missions).
# Idea Storage

* Galactic map made up of sectors that can be “liberated”. Bonuses for the player based on which sectors are liberated. Sectors on the Outer Rim are more easily liberated.
* Fatigue for troops?
* Travel time between missions.
* Mission selection based on location of the cruiser in the galaxy.
* Using range values as proxy for accuracy, increasing or lowering damage.
* Facility adcency bonuses.
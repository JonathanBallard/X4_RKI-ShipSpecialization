# X4_RKI-ShipSpecialization  

### Author: Tax/Jonathan Ballard  
### Last Updated: 4/8/22  
### Current Mod Version: 0.01  
### Tested with Game Version: 5.10, Split Vendetta, Cradle of Humanity, and Tides of Avarice DLC's  

---

#### Short Description:  
A mod for the game __X4: Foundations__ by __Egosoft__. Intended to be used together with the incredible [__Variety and Rebalance Overhaul (VRO)__](https://www.nexusmods.com/x4foundations/mods/305) mod, which was created by _Shuul_. ShipSpecialization makes scouts and interceptors more useful by increasing their performance in their roles. This is achieved by increasing the statistics most associated with their roles, while still ensuring they're well balanced for VRO. 

#### Compatability:  
This mod should not have any compatability problems. It is intended to be used with VRO based on the balancing. If will edit ships from ATFUSC Ship Pack, Ship Variation Extender (SVE), and Bayamon Miner, if you have them installed.
_Make sure this mod is loaded __BEFORE__ whichever of the following mods you have installed: <span style="color: red;">VRO, ATFUSC Shippack, Ship Variation Extender (SVE), Bayamon Miner_</span>

#### Must come BEFORE:  
1. VRO  
2. ATFUSC_Shippack  
3. Bayamon Miner  
4. Ship Variation Expansion (SVE)  
5. Terran DLC  
6. 

#### Version History:  
> - 
> - 4/8/22, v0.01: Initial Upload

#### Long Desciption:  
ShipSpecialization is designed to make interceptors and scouts feel more useful by making them perform their roles more effectively. It starts by increasing the speed of both scouts and interceptors by a solid 5-10%. Scouts then get a decent radar distance boost, and interceptors get a boost in manueverability. A new ship class has been implemented, Advanced Scouts AKA Scanners. There are only a handful of them at the moment, but they receive an even greater increase to radar range (50% flat increase instead of the 25% that scouts get). One thing that must be kept in mind is that possibility that increasing ship radar too much can negatively affect performance. It's because of this that I'm being moderate in the increases to radar, and also increase the ship's speed, so that it can put that radar to better use.

The ships have been balanced against VRO ships, I do not currently have a Vanilla X4 version. All changes are made with the ship's minimum and maximum possible values in mind (in fact I spent more time building a spreadsheet to check balancing than I did writing the XML Diff-patches). I have also worked to include ship price into the balance equation. I found that scouts that cost $80k with 3 engines were about the same speed as ships that cost $213k with 1 engine - this didn't make sense to me. I generally went with the idea that 'more money faster ship, more engines faster ship' for base scouts and interceptors. That said, if I discover some sort of lore behind the ships that would indicate its suitability or lack thereof for its task, I would happily make use of that. 

Some ships that are classed as fighters and even a heavy-fighter or 2 have been classes as scouts, interceptors, or advanced scouts.

I have also included several other QoL changes. These include non-combat drone speed increases, spacesuit speed and manueverability increases, slightly increased speed of escape pods, increased tracking by 5% and cooling by 10% on Lasertower Mk.2. Increased the damage on the weapon used by Lasertower Mk.2 by 10%, but also increased the heat generated so the damage increase should only be felt on the Lasertower Mk.2.

This mod would not have been created without the fantastic [__X4 Editor__](https://forum.egosoft.com/viewtopic.php?f=181&t=421306). I spent many long evenings on the editor to learn the use of different attributes, and learned the ways of the diff-patch though it too. Many thanks to the author Max Bain for this tool!


##### Future Plans  
1. Increase the speed/manuever of Boarding Pods.  
2. 

##### Long Rant:  
I'm considering working ship mass into the max speed equation, perhaps comparing it with the number of engines. This would be helpful in creating a more meaningful difference between vanguard and sentinel variants, as sentinels are much heavier. That was something I was struggling to find a reason to do. My thoughts here are that mass increases the faster you go, so you will require more fuel to continue to accelerate to a higher speed. There wouldn't be any hard math in my implementation, I might just include a 1%-10% decrease/increase depending on how many engines you have for how much mass. Since engines are more fuel efficient at lower speeds (IDK if that's true in space too, but I would think it is), the more engines you have working on smaller mass amounts, the more fuel efficient and therefore the faster your max speed can be.

#### Fairly exhaustive list of changes made:  
- Scouts  
  - Organized so that their radar could be edited without affecting all small ships
  - Radar increased by 25% 
  - Speeds increased by 5-10%

- Interceptors  
  - Speed increased between 2-10% (usually around 4%)
  - Manueverability increased by a flat 5% across the board.

- Advanced Scouts AKA Scanners (think of them as solid ships that were outfitted with additional sensor packages):  
  - Organized so that their radar could be edited without affecting all small ships
  - Radar increased by 50%
  - Speeds increased by 5-15%
  - Nimcha
    - Hull increased by 10%

- Laser Tower Mk.2  
  - Tracking increased slightly
  - Damage increased by 5%

- Many Drones have had their speed increased slightly  
  - Building Drones
  - Repair Drones
  - Mining Drones (solid and liquid)

- All Spacesuit Engines have had their speed and manueverability increased greatly  

- The Spacesuit Repair Laser has had its repair rate and range increased to make it slightly less tedious  
  - 3x Repair Rate
  - 150m Range (needs testing)

##### Ship Groups:  
- Scouts  
  - Pegasus Vanguard
  - Pegasus Sentinel
  - Discoverer Vanguard
  - Discoverer Sentinel
  - Kestrel Vanguard
  - Kestrel Sentinel
  - Rapier
  - Kojin (Ship Variation Extension)
  - Jaguar (Ship Variation Extension)

- Interceptors  
  - Perseus Vanguard
  - Perseus Sentinel
  - Nova Vanguard
  - Nova Sentinel
  - Guillemot Vanguard
  - Guilletmot Sentinel
  - Elite Vanguard
  - Elite Sentinel
  - Asp
  - Asp Raider
  - Nodan Vanguard
  - Pulsar Vanguard
  - Lux
  - Kyd
  - Skua (Ship Variation Extension)

- Advanced Scouts/Scanners  
  - Nimcha
  - Moreya
  - Takoba
  - Paramerion (Ship Variation Extension)
  - Akuma (Ship Variation Extension)

##### Links  
- RKI-ShipSpecialization on Steam Workshop:  
- RKI-ShipSpecialization on Nexus Mods:  
- RKI-ShipSpecialization on GitHub: [X4_RKI-ShipSpecialization](https://github.com/JonathanBallard/X4_RKI-ShipSpecialization)  
- Tax on Egosoft Forums: [asgardschosen](https://forum.egosoft.com/memberlist.php?mode=viewprofile&u=462345)  

##### Legal:  
If anyone wishes to modify any portion of this mod, they may do so, so long as they credit me and the people I credited appropriately. I will include the people to credit directly below this heading.  

##### Credits:  
Tax/Jonathan Ballard - Ravenknight Industries Mods  
Special Thanks To:  
Max Bain - Egosoft Forum Member & Creator of X4 Editor  
DeadAirRT - Egosoft Forum Member & Creator of DeadAir Mods series  
theqmann - Egosoft Forum Member & Author of the XML Patch Guide tutorial  
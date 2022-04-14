

# Current Version: 0.02, Updated On: 04/14/22

---
</br></br></br>
<div style="width: 80%; color: white; background-color: #1a4a07; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="6">X4_RKI-ShipSpecialization  </font></div>


<div style="width: 80%; color: white; background-color: #1a4a07; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Mod Information  <br/>
Author: Tax/Jonathan Ballard  <br/>
Last Updated: 4/14/22  <br/>
Current Mod Version: 0.02  <br/>
Tested with Game Version: 5.10, Split Vendetta, Cradle of Humanity, and Tides of Avarice DLC's  </font></div>

</br></br></br>

---

</br></br></br>

<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Short Description:  </font></div>

A mod for the game __X4: Foundations__ by __Egosoft__. RKI-ShipSpecialization (RKI-SS) makes scouts and interceptors more useful by increasing their performance in their roles. This is achieved by increasing the statistics most associated with their roles, while still ensuring they're well balanced for VRO. is intended to be used together with the incredible [__Variety and Rebalance Overhaul (VRO)__](https://www.nexusmods.com/x4foundations/mods/305) mod, which was created by _Shuul_. ShipSpecialization changes will also be applied to appropriate ships from some/all/none of the recommended mods, based on whether you install that mod. No additional mods are required for RKI-ShipSpecialization.

<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Recommended Mods:  </font></div>

> - [Variety and Rebalance Overhaul (AKA VRO)](https://steamcommunity.com/sharedfiles/filedetails/?id=1696862840) <<< ___HIGHLY___ recommended (all changes are balanced against VRO)
> - [Bayamon Miner - VRO Version](https://steamcommunity.com/sharedfiles/filedetails/?id=2647877221)
> - [ATFUSC Shippack - VRO Version](https://steamcommunity.com/sharedfiles/filedetails/?id=2627959637)
> - [Ship Variation Expansion](https://steamcommunity.com/sharedfiles/filedetails/?id=2229061492) <<< Requires the VRO version below
> - [Ship Variation Expansion - VRO Version](https://steamcommunity.com/sharedfiles/filedetails/?id=2551053441) <<< Requires the Vanilla version above

<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Compatability (USERS):  </font></div>

This mod should not have any compatability problems. It is intended to be used with VRO based on the balancing. If will edit ships from ATFUSC Ship Pack, Ship Variation Extender (SVE), and Bayamon Miner, if you have them installed.
_ShipSpecialization will automatically load itself after the mods in the recommended list (if you have them installed) to ensure that the edits are properly applied: VRO, ATFUSC Shippack, Ship Variation Extender (SVE), Bayamon Miner_


<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Compatability (MOD CREATORS):  </font></div>

The mod should not cause any problems for any other mod. All changes are made through DIFF Patches. The only changes made were modifying existing values, except in the case of ship class. Ship class was defined in libraries/defaults.xml, some examples of Vanilla ship classes are ship_s, ship_m, ship_l, pretty straightforward right? Well the default radar range was based on these ship classes, formerly only based on ship size. To make it easier to manage radar ranges in future (so I wouldn't have to edit each ship's macro.xml file separately), and to ensure that I would only increase the radar range of the ships I wanted to (and avoid the performance hit that comes with too many ships with high radar range), I created 2 new classes (ship_scout, and ship_adv_scout). These are clones of the ship_s class, except for the radar ranges (there are 2 radar range attributes for each class - one for default, and one for max).

<div style="width: 80%; color: white; background-color: #701020; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Version History:  </font></div>

> - 04/14/22, v0.02: Re-organized file structure. (VRO changes applied to both VRO xml's and Vanilla xml's)
> - 04/08/22, v0.01: Initial Upload  


<div style="width: 80%; color: white; background-color: #0e013d; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Long Desciption:  </font></div>

ShipSpecialization is designed to make interceptors and scouts feel more useful by making them perform their roles more effectively. It starts by increasing the speed of both scouts and interceptors by a solid 5-10%. Scouts then get a decent radar distance boost, and interceptors get a boost in manueverability. A new ship class has been implemented, Advanced Scouts AKA Scanners. There are only a handful of them at the moment, but they receive an even greater increase to radar range (50% flat increase instead of the 25% that scouts get). One thing that must be kept in mind is that possibility that increasing ship radar too much can negatively affect performance. It's because of this that I'm being moderate in the increases to radar, and also increase the ship's speed, so that it can put that radar to better use.

The ships have been balanced against VRO ships, I do not currently have a Vanilla X4 version. All changes are made with the ship's minimum and maximum possible values in mind (in fact I spent more time building a spreadsheet to check balancing than I did writing the XML Diff-patches). I have also worked to include ship price into the balance equation. I found that scouts that cost $80k with 3 engines were about the same speed as ships that cost $213k with 1 engine - this didn't make sense to me. I generally went with the idea that 'more money faster ship, more engines faster ship' for base scouts and interceptors. That said, if I discover some sort of lore behind the ships that would indicate its suitability or lack thereof for its task, I would happily make use of that. 

Some ships that are classed as fighters and even a heavy-fighter or 2 have been classes as scouts, interceptors, or advanced scouts.

I have also included several other QoL changes. These include non-combat drone speed increases, spacesuit speed and manueverability increases, slightly increased speed of escape pods, increased tracking by 5% and cooling by 10% on Lasertower Mk.2. Increased the damage on the weapon used by Lasertower Mk.2 by 10%, but also increased the heat generated so the damage increase should only be felt on the Lasertower Mk.2.

This mod would not have been created without the fantastic [__X4 Editor__](https://forum.egosoft.com/viewtopic.php?f=181&t=421306). I spent many long evenings on the editor to learn the use of different attributes, and learned the ways of the diff-patch though it too. Many thanks to the author Max Bain for this tool!

<div style="width: 80%; color: white; background-color: #0e013d; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="4">Future Plans:  </font></div>

1. *DONE* Increase the speed/manuever of Boarding Pods.  
2. *DONE* Relocate macro.xml's into correct file structure  
3. *DONE* Increase the Hull / Marine Capacity of Boarding Pods? (Need to investigate secondary effects beforehand)  


<div style="width: 80%; color: white; background-color: #0e013d; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Fairly exhaustive list of changes made:</font></div>  

- Scouts
  - Organized so that their radar could be edited without affecting all small ships
  - Radar increased by 25% 
  - Speeds increased by 5%-10%  

- Interceptors  
  - Speed increased between 2%-10% (usually around 4%)
  - Manueverability increased by a flat 5% across the board.

- Advanced Scouts AKA Scanners (think of them as solid ships that were outfitted with additional sensor packages):  
  - Organized so that their radar could be edited without affecting all small ships
  - Radar increased by 25% or more
  - Speeds increased by 5%-15%
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


<div style="width: 80%; color: white; background-color: #4c4d4c; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Ship Groups:</font></div>  

<div style="width: 20%; color: white; background-color: #1295c4; font-weight: bold; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3">Scouts:  </font></div>

  - Pegasus Vanguard
  - Pegasus Sentinel
  - Discoverer Vanguard
  - Discoverer Sentinel
  - Kestrel Vanguard
  - Kestrel Sentinel
  - Rapier
  - Kojin (Ship Variation Extension)
  - Jaguar (Ship Variation Extension)  



<div style="width: 20%; color: white; background-color: #1295c4; font-weight: bold; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3">Interceptors:  </font></div>

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



<div style="width: 20%; color: white; background-color: #1295c4; font-weight: bold; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3">Advanced Scouts/Scanners:  </font></div>

  - Nimcha
  - Moreya
  - Takoba
  - Paramerion (Ship Variation Extension)
  - Akuma (Ship Variation Extension)  


<div style="width: 80%; color: white; background-color: #4c4d4c; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Links:  </font></div>

- RKI-ShipSpecialization on Steam Workshop:  
- RKI-ShipSpecialization on Nexus Mods:  
- RKI-ShipSpecialization on GitHub: [X4_RKI-ShipSpecialization](https://github.com/JonathanBallard/X4_RKI-ShipSpecialization)  
- Tax on Egosoft Forums: [asgardschosen](https://forum.egosoft.com/memberlist.php?mode=viewprofile&u=462345)  

<div style="width: 80%; color: white; background-color: #4c4d4c; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Legal:  </font></div>

If anyone wishes to modify any portion of this mod, they may do so, so long as they credit my work, and the work of others, where appropriate. I will include the people to credit directly below this heading.  

<div style="width: 80%; color: white; background-color: #4c4d4c; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Credits:  </font></div>

Tax/Jonathan Ballard - Ravenknight Industries (RKI) Mods  
_Thank you for being me. It's a dead-end job, and there's not a lot of perks - but somebody has to do it..._  

<div style="width: 80%; color: white; background-color: #4c4d4c; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Special Thanks To:  </font></div>

_Max Bain_ - Egosoft Forum Member & Creator of X4 Editor  
_Thanks for your help figuring out how to use the X4 Editor, and figuring out how you built. These 2 things are how I got my start in understanding the file system and structure of X4._  

_DeadAirRT_ - Egosoft Forum Member & Creator of DeadAir Mods series  
_Thanks for your advice and help on the Egosoft Forums_

_theqmann_ - Egosoft Forum Member & Author of the XML Patch Guide tutorial  
_Without your guide on XML DIFF's, this would have been a much harder task. Thank you._

_Shuul_ - Egosoft Forum Member & Author of VRO  
_Thanks for creating and continuing to maintain VRO, even in the face of adversity._



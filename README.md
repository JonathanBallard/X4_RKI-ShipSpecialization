
# <div style="width: 100%; color: white; text-align: center; background-color: #69024E; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="6">Ravenknight Industries Presents  </font></div>

---

<div style="width: 80%; color: white; background-color: #123405; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Ship Specialization and QoL changes  </font></div>

---
<div style="width: 80%; color: white; background-color: #1a4a07; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="4"><u>Mod Information</u>  <br/>
Name: RKI-ShipSpecialization  </br>
ID: RKI-ShipSpec  </br>
Author: Tax/Jonathan Ballard  <br/>
Last Updated: 5/01/22  <br/>
Current Mod Version: 0.05  <br/>
Tested with Game Version: 5.10, Split Vendetta, Cradle of Humanity, and Tides of Avarice DLC's  </font></div>

</br></br>

<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Short Description:  </font></div>

A mod for the game __X4: Foundations__ by __Egosoft__. RKI-ShipSpecialization (RKI-SS) organizes some hand-picked small ships into specialized classes, including 2 newly created classes of light reconnaissance ship: Vedettes and Scanners. These ships then receive enhancements ranging from moderate to superb, based on the designated roles of their new classification. Several QoL changes have been included as well. RKI-SS is intended to be used together with the incredible [__Variety and Rebalance Overhaul (VRO)__](https://www.nexusmods.com/x4foundations/mods/305) mod, which was created by _Shuul_. ShipSpecialization changes will also be applied to appropriate ships from some/all/none of the recommended mods, based on whether you install that mod. No additional mods are required. However, RKI-SS does REQUIRE all 3 Egosoft DLC's (Split Vendetta, Cradle of Humanity, and Tides of Avarice).  

<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Recommended Mods:  </font></div>

> - [Variety and Rebalance Overhaul (AKA VRO)](https://steamcommunity.com/sharedfiles/filedetails/?id=1696862840) <<< ___HIGHLY___ recommended (all changes are balanced against VRO)
> - [Bayamon Miner - VRO Version](https://steamcommunity.com/sharedfiles/filedetails/?id=2647877221)
> - [ATFUSC Shippack - VRO Version](https://steamcommunity.com/sharedfiles/filedetails/?id=2627959637)
> - [Ship Variation Expansion](https://steamcommunity.com/sharedfiles/filedetails/?id=2229061492) <<< Use with the VRO version below
> - [Ship Variation Expansion - VRO Version](https://steamcommunity.com/sharedfiles/filedetails/?id=2551053441) <<<br Requires the Vanilla version above

<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Compatability (USERS):  </font></div>

This mod should not have any compatability problems. It is intended to be used with VRO based on the balancing. If will edit ships from ATFUSC Ship Pack, Ship Variation Extender (SVE), and Bayamon Miner, if you have them installed.
_ShipSpecialization will automatically load itself after the mods in the recommended list (if you have them installed) to ensure that the edits are properly applied: VRO, ATFUSC Shippack, Ship Variation Extender (SVE), Bayamon Miner_  


<div style="width: 80%; color: white; background-color: #4a0707; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Compatability (MOD CREATORS):  </font></div>

The mod should not cause any problems for any other mod. All changes are made through DIFF Patches. The only changes made were modifying existing values, except in the case of ship class. Ship class was defined in libraries/defaults.xml, some examples of Vanilla ship classes are ship_s, ship_m, ship_l, pretty straightforward right? Well the default radar range was based on these ship classes, formerly only based on ship size. To make it easier to manage radar ranges in future (so I wouldn't have to edit each ship's macro.xml file separately), and to ensure that I would only increase the radar range of the ships I wanted to (and avoid the performance hit that comes with too many ships with high radar range), I created 3 new classes (ship_scout, ship_vedette, and ship_adv_scout). These are clones of the ship_s class, except for the radar range attributes (there are 2 radar range attributes for each class - one for default, and one for max).  

<div style="width: 80%; color: white; background-color: #701020; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Version History:  </font></div>

> - v0.05 (04/30/22) - Testing - Manually added Radar values to ships, tested all ships and shiptypes, current issue with Terran scout radars  
> - v0.04 (04/26/22) - Testing - Increased repair laser value, shortened content.xml  
> - v0.03 (04/22/22) - Initial upload to NexusMods  
> - v0.02 (04/14/22) - Re-organized file structure. (VRO changes applied to both VRO xml's and Vanilla xml's)  
> - v0.01 (04/08/22) - Initial Commit  


<div style="width: 80%; color: white; background-color: #010735; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Long Desciption:  </font></div>

ShipSpecialization is designed to make interceptors and scouts feel more useful by making them perform their roles more effectively. It starts by increasing the speed of both scouts and interceptors by a solid 5-10%. Scouts then get a minor radar distance boost, and interceptors get a boost in manueverability. I have created 3 new ship classes, all of which just re-classify existing vanilla/modified ships, and increases their radar ability. One of the new classes is just a way of differentiating scouts from other small ships so that I can slightly increase their default radar. The other 2 are only a little more involved. I have included some flavor text for the other 2 new classifications below. I don't currently have new identifying markers for them, but that's something I'd love to do, if, y'know, I was an artist. Since I'm not an artist, I'll probably leave them as they are (default ship_s icon).  

Note:  
One thing that must be kept in mind is that possibility that increasing ship radar too much can negatively affect performance. It's because of this that I'm being moderate in the increases to radar, and also increase the ship's speed, so that it can put that radar to better use.  

The ships have been balanced against VRO ships, I do not currently have a Vanilla X4 version of this mod. All changes are made with the ship's minimum and maximum possible values in mind (in fact I spent more time building a spreadsheet to check balancing than I did writing the XML Diff-patches). I have also worked to include ship price into the balance equation. I found that scouts that cost $80k with 3 engines were about the same speed as ships that cost $213k with 1 engine - this didn't make sense to me. I generally went with the idea that 'more money faster ship, more engines faster ship' for base scouts and interceptors. That said, if I discover some sort of lore behind the ships that would indicate its suitability or lack thereof for its task, I would happily make use of that.  

Some ships that are classed as fighters and even a heavy-fighter or 2 have been classes as scouts, interceptors, vedettes, or advanced scouts.  

I have also included several other QoL changes. These include non-combat drone speed increases, spacesuit speed and manueverability increases, slightly increased speed of escape pods, increased tracking by 5% and cooling by 10% on Lasertower Mk.2. Increased the damage on the weapon used by Lasertower Mk.2 by 10%, but also increased the heat generated so the damage increase should only be felt on the Lasertower Mk.2.  


<div style="width: 80%; color: white; background-color: #010735; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Flavor text for 2 of the new classes:  </font></div>



<div style="width: 40%; color: white; background-color: #024569; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="3">Vedette:  </font></div>

The Vedette is a ship class designed to effect deep space patrols on their own or in 2-ship groups. They patrol the edges of systems that contain military assets to ensure that adversaries don't try to sneak into the systems and sectors without using the Gates. They are particularly important in identifying Xenon staging areas. Upon locating an enemy, they speed back to communications range and inform system/sector command.  

> Ship Design: Vedettes are essentially scout ships that have been stripped of everything that could be removed while remaining space-worthy, and instead installed extra radar arrays and communications equipment. Their radar ranges receive a solid increase, but they suffer in other areas, such as cargo capacity and crew chairs.  



<div style="width: 40%; color: white; background-color: #024569; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="3">Advanced Scouts/Scanners:  </font></div>
Excerpt taken from a smuggled copy of <em>'Terran Manual of Warships: Advanced Scouts'</em>: "Advanced Scouts, AKA Scanners, are multi-role ships designed to both outperform Vedettes in combat roles and outperform fighters in their long-range detection. Due to their fragile nature, current doctrine dictates that a Vedette must disengage and flee upon contact with the enemy. With the increase in stealth technology, and the speed with which the Vedette must depart in order to deliver a warning with time to spare before the enemy arrives, often the Vedette fails to identify the precise nature of the incoming threat, its numbers, its direction of attack, or its formation. When we have the ships to spare, doctrine allows us to pair Vedettes where the first ship arrives with the initial warning and the second returns later with more specifics. Why use 2 ships when 1 would do? This is where the Advanced Scout comes in.  </br>

Vedettes have to sacrifice offensive and defensive power, and sometimes even the most basic amenities, in order to create space for their massive satellite arrays. Advanced Scouts/Scanners on the other hand are able to rely more heavily on complex target analysis and flight path prediction VI's (virtual intelligences - A lower performing but less risky variant of an AI). This allows the Advanced Scout/Scanner to sport weaponry and shielding comparable to fighters in performance, if not in price. VI's are expensive, and they're heavily taxed, so Advanced Scouts/Scanners are not cheap. They more than make up for their pricing. This extra cost buys us a ship that can stay until the last minute, gathering information and departing before the attackers can bring real substantial threats to bear on it. Fighting off the initial vanguard, which reliably consists first of drones, then of a combination of enemy scouts and light fighters. When it has gathered the necessary data, or its tactical situation has become untenable, it can simply broadcast the information from far further using the state of the art subspace communications feature built-in to every VI."  </br>

Currently only the Terran factions have been able to introduce VI's small enough to fit into small ship frames. Other races still rely on more traditional scouting methods or Vedettes, though there have been rumours of a blueprint for an early VI prototype that went missing from a Terran research station. Somehow this blueprint found its way onto the black market where it was sold at auction. Where it went from there, no-one has been able to say. It's probably just another myth...  </br>

Early implementations of VI technology were viewed with extreme suspicion by the Terran populace. It's believed that the Terrans chose the term 'Scanner' to replace 'VI' in part to appease any fears of another rogue AI event. Upon the re-opening of the gates, the first Argon to encounter the ships called them 'Advanced Scouts' when they struggled to understand how a fighter could spot, target, and engage Argon scouts before the scout even knew it had company.  </br>

> Ship Design: Advanced Scouts AKA Scanners are another new class of small ship. There are only a handful of them at the moment, but they receive an even greater increase to radar range than Vedettes. Performance is comparable to a fighter or heavy fighter, these ships can hold their own in a dogfight.  </br>


<div style="width: 80%; color: white; background-color: #26102B; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="4">Future Plans:  </font></div>

1. May change out ATFUSC Ship Pack's Mobile Mining Ship engines from Large to Extra-Large  
2. Specialize Medium-sized ships as well (???)  
3. Specialize L-sized ships as well (???)  
4. Specialize XL-sized ships as well (???)  
    - Create 'Command Carrier' ship class for XL to increase visibility slightly (???)  
5. Duplicate ships for the new classifications instead of upgrading originals  
    - Create 'Scanner' and 'Vedette' variants of ships  
    - Increase price of Advanced Scouts/Scanners  
6. Remove Advanced Scouts/Scanners from AI creation?  
7. Review Vedette frequencies of production by AI, and the effect that has on performance  


<div style="width: 80%; color: white; background-color: #26102B; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="5">Fairly exhaustive list of changes made:  </font></div>  


<div style="width: 40%; color: white; background-color: #268700; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3"> Scout Changes  </font></div>
<span style="font-weight: bold"><font size="2"><em><mark> Scouts are now able to move faster and have a small boost to radar range.  </mark></em></font></span> 
    <ul>
        <li> Speeds increased by 5%-10%  
        <li> Radar increased by 5%  
    </ul>

<div style="width: 40%; color: white; background-color: #268700; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3"> Interceptor Changes  </font></div>
<span style="font-weight: bold"><font size="2"><em><mark> Interceptors now have greater manueverability and a slight increase to their overall speed. This is to make them more effective in avoiding larger guns, requiring L and XL ships to bring escorts, while also giving carriers a greater advantage.  </mark></em></font></span>  
<ul>
    <li> Speed increased between 2%-10% (usually around 4%)  
    <li> Manueverability increased by a flat 5% across the board.  
</ul>

<div style="width: 40%; color: white; background-color: #268700; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3"> Vedette (New Class)  </font></div>
<span style="font-weight: bold"><font size="2"><em><mark> Definition:  'A mounted sentinel posted in advance of the outposts of an army'  </mark></em></font></span>  

<ul>
    <li> Class created so that their radar could be edited without affecting all small ships  
    <li> Speeds increased by 5%-10%  
    <li> Radar increased substantially  
</ul>

<div style="width: 40%; color: white; background-color: #268700; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3"> Advanced Scout (New Class)  </font></div>
<span style="font-weight: bold"><font size="2"><em><mark> Think of advanced scouts - AKA scanners - as fighters that were outfitted with additional sensor packages  </mark></em></font></span>  

<ul>
  <li> Class created so that their radar could be edited without affecting all small ships  
  <li> Radar increased by 25% or more  
  <li> Speeds increased by 5%-15%  
  <li> Nimcha  
    <ul>
        <li> Hull increased by 10%  
    </ul>
</ul>

<div style="width: 40%; color: white; background-color: #268700; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3"> XL Ship Changes  </font></div>
<span style="font-weight: bold"><font size="2"><em><mark> XL Ships have gotten a small boost to radar range.  </mark></em></font></span>
    <ul>
        <li> Radar increased by 10%  
    </ul>

<div style="width: 40%; color: white; background-color: #268700; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3"> Misc. Changes  </font></div>
<span style="font-weight: bold"><font size="2"><em><mark> Smaller changes and QoL improvements. </mark></em></font></span>  
<ul>
    <li> Laser Tower Mk.2  
    <ul>
        <li> Tracking increased slightly  
        <li> Damage increased by 5%  
    </ul>
</ul>
<ul>
    <li> Many Drones have had their speed increased slightly  
    <ul>
        <li> Building Drones  
        <li> Repair Drones  
        <li> Mining Drones (solid and liquid)  
    </ul>
</ul>

<ul>
    <li> All Spacesuit Engines have had their speed and manueverability increased greatly  
</ul>
<ul>
    <li> The Spacesuit Repair Laser has had its repair rate and range increased to make it slightly less tedious  
    <ul>
        <li> 3x Repair Rate  
        <li> 150m Range (needs testing)  
    </ul>
</ul>
<ul>
    <li> Boarding Pods are now faster, more manueverable, and more durable  
    <ul>
        <li>- Boarding Pods speed and manueverability by between 50% and 150%  
        <li>Boarding Pod Hull has been increased from 200 to 500  
    </ul>
</ul>

<div style="width: 80%; color: white; background-color: #4A0119; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Ship Groups:  </font></div>  

<div style="width: 30%; color: white; background-color: #1295c4; font-weight: bold; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3">Scouts:  </font></div>
<ul>
    <li> Pegasus Vanguard
    <li> Pegasus Sentinel
    <li> Discoverer Vanguard
    <li> Discoverer Sentinel
    <li> Kestrel Vanguard
    <li> Kestrel Sentinel
</ul>

<div style="width: 30%; color: white; background-color: #1295c4; font-weight: bold; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3">Interceptors:  </font></div>
<ul>
    <li> Perseus Vanguard
    <li> Perseus Sentinel
    <li> Nova Vanguard
    <li> Nova Sentinel
    <li> Guillemot Vanguard
    <li> Guilletmot Sentinel
    <li> Elite Vanguard
    <li> Elite Sentinel
    <li> Asp
    <li> Asp Raider
    <li> Nodan Vanguard
    <li> Pulsar Vanguard
    <li> Lux
    <li> Kyd
    <li> Skua (Ship Variation Extension)  
</ul>

<div style="width: 30%; color: white; background-color: #1295c4; font-weight: bold; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3">Vedettes:  </font></div>
<ul>
    <li> Kojin (Ship Variation Extension)
    <li> Jaguar (Split DLC: Split Vendetta)  
    <li> Rapier (Terran DLC: Cradle of Humanity)  
</ul>

<div style="width: 30%; color: white; background-color: #1295c4; font-weight: bold; padding: 12px 12px; margin: 20px,0px,0px,0px;"><font size="3">Advanced Scouts/Scanners:  </font></div>
<ul>
    <li> Nimcha (Terran DLC: Cradle of Humanity)  
    <li> Moreya (Terran DLC: Cradle of Humanity)  
    <li> Takoba (Terran DLC: Cradle of Humanity)  
    <li> Paramerion (Ship Variation Extension)  
    <li> Akuma (Ship Variation Extension)  
</ul>

<div style="width: 80%; color: white; background-color: #795A7F; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Links:  </font></div>
<ul>
    <li> RKI-ShipSpecialization on Steam Workshop:  
    <li> RKI-ShipSpecialization on Nexus Mods:  
    <li> RKI-ShipSpecialization on GitHub: <a href="https://github.com/JonathanBallard/X4_RKI-ShipSpecialization">X4_RKI-ShipSpecialization</a>
    <li> Tax on Egosoft Forums: <a href="https://forum.egosoft.com/memberlist.php?mode=viewprofile&u=462345">asgardschosen</a>
</ul>

<div style="width: 80%; color: white; background-color: #123405; font-weight: bold; padding: 12px 12px; margin: 30px,0px,5px,0px;"><font size="3">Nexus Mods Description:  </font></div>
RKI-SS organizes some hand-picked small ships into specialized classes, including 2 newly created classes of light reconnaissance ship: Vedettes and Scanners. These ships then receive enhancements ranging from moderate to superb, based on the designated roles of their new classification. Several QoL changes too. All enhancements are balanced for VRO.  

<div style="width: 80%; color: white; background-color: #795A7F; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Legal:  </font></div>

If anyone wishes to modify any portion of this mod, they may do so, so long as they credit my work, and the work of others, where appropriate. I will include the people to credit directly below this heading.  

<div style="width: 80%; color: white; background-color: #25010d; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Credits:  </font></div>

Tax/Jonathan Ballard - Ravenknight Industries (RKI) Mods  
_Thank you for being me. It's a dead-end job, and there's not a lot of perks - but somebody has to do it..._  
Note: For clarity's sake, I am Midnightclear/Einherjarin on Nexus, and Tax/Asgardschosen elsewhere  

<div style="width: 80%; color: white; background-color: #25010d; font-weight: bold; padding: 12px 12px; margin: 30px,0px,15px,0px;"><font size="4">Special Thanks To:  </font></div>

_Max Bain_ - Egosoft Forum Member & Creator of X4 Editor  
_Thanks for your help with how to use X4 Editor. It was by figuring out how it worked, and seeing the results, that I was able to learn to do DIFF patches._  

_DeadAirRT_ - Egosoft Forum Member & Creator of DeadAir Mods series  
_Thanks for your advice and help on the Egosoft Forums_  

_theqmann_ - Egosoft Forum Member & Author of the XML Patch Guide tutorial  
_Without your guide on XML DIFF's, this would have been a much harder task. Thank you._  

_Shuul_ - Egosoft Forum Member & Author of VRO  
_Thanks for creating and continuing to maintain VRO, even in the face of adversity._  

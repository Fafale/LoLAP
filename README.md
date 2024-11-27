# LoLAP
This is a modified version from the League of Legends Archipelago Multiworld implementation.

The original project can be found [in this repository](https://github.com/gaithernOrg/LoLAP).

---
## What's new?
This modified version adds a new requirement for achieving Goal in the game, and that's ***"Required Checks"***.

This was made in order to change LoL's goal condition, since most of the time you ended up finishing your slot just by receiving LP passively, without really playing that much.

Basically, you now have a new option in the .yaml to set a percentage of **Objective Checks** you need to complete in order to Goal your slot, together with receiving a certain LP amount (this remained unchanged).

Objective Checks refer to:
- Assist Taking Dragon
- Assist Taking Herald/Grubs
- Assist Taking Baron
- Assist Taking Tower
- Assist Taking Inhibitor

---

I didn't want to actively change the original LolAP implementation since I didn't really know what I was doing, just did some workarounds with checks/locations and it worked.

That's why this version appears as a different game on the multiworld (League of LegendsFAFLE), so you can still use the previous/original version without worrying this overwrites it. 

# LoLAP
This is a modified version from the League of Legends Archipelago Multiworld implementation.

The original project can be found [in this repository](https://github.com/gaithernOrg/LoLAP).

---
## What's new?
This modified version adds a new requirement for achieving Goal in the game, and that's ***"Required Checks"***.

This was made in order to change LoL's goal condition, since most of the time you ended up finishing your slot just by receiving LP from others, without really playing yourself.

Basically, you now have a new option in the .yaml to set a percentage of **Objective Checks** you need to complete in order to Goal your slot, together with receiving a certain LP amount (this remains unchanged).

Objective Checks refer to:
- Assist Taking Dragon
- Assist Taking Herald/Grubs
- Assist Taking Baron
- Assist Taking Atakhan
- Assist Taking Tower
- Assist Taking Inhibitor

---
## Install Instructions
You'll need **both** `lolFAFLE.apworld` and `lol.apworld` ([available here](https://github.com/gaithernOrg/LoLAP)) for it to work, since this apworld uses the original LOL Client.
1. Open your Archipelago Launcher and click `Install APWorld`, then select `lolFAFLE.apworld`
2. Once it's done, close the Archipelago Launcher
3. On your Archipelago Folder, place the `lol.apworld` inside `Archipelago\lib\worlds`
4. Open and close your Archipelago Launcher (not sure if this step is necessary, but do it just in case)
5. Move your `lolFAFLE.apworld` from `Archipelago\custom_worlds` to `Archipelago\lib\worlds`
Now it should be installed and working! Yiippee!

## Usage Instructions
1. Open your Archipelago Launcher and select `LOL Client` (from the column on the right)
2. On the Archipelago LOL Client, connect to your slot using the top bar or /connect
3. Open your `ConnectorFAFLE.exe`
    * You should receive your Starting Champions at this moment. If it doesn't happen, start a game in practice tool, that should do it!
4. Once you're inside a match, press `Check for Match`, it'll change to "In Match"!
    * Make sure to only check for match AFTER the loading screen, or else the connector might crash
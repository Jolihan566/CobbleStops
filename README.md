CobbleStops Datapack (for Cobblemon 1.7 Snapshots)
Instantly add functional, rewarding PokeStops to your Cobblemon test server! This datapack adds a new, custom PokéStop NPC that players can interact with to claim items.

It's designed to be incredibly easy for server owners to configure, allowing you to change all loot pools and cooldowns to fit your needs.

⚠️ **IMPORTANT WARNING** ⚠️

This datapack is built for the Cobblemon 1.7 Snapshot/Testing versions. 
It is NOT stable and is NOT intended for use on production servers. 
Use it at your own risk for testing and fun only. 
Features may break or change. Snapshot versions can be found [here](https://cobbledevbuild.vercel.app/) - Use at own risk.


![CobbleStop Model](https://cdn.modrinth.com/data/cached_images/0cf8da74685c3ce566500a5dde2ffd22f7b3d636_0.webp)

Features
- Adds a New NPC: Spawns a dedicated "PokeStop" NPC.
  
- Fully Customizable Loot: Easily configure every possible reward by editing the loot_pool.json file. No scripting knowledge required!
  
- 4 Rarity Tiers: Rewards are split into Common, Uncommon, Rare, and Ultra Rare pools. You decide what items go where.


```
Weighted Rarity: The script uses a 1-100 roll to determine which pool a player gets a reward from. The defaults are:

- Common: 60%

- Uncommon: 25%

- Rare: 10%

- Ultra Rare: 5%

```
  
- Configurable Cooldown: Set how long (in hours) a player must wait before using the PokeStop again.
  
- User-Friendly Feedback: Players receive a clean, colorful chat message telling them exactly what they found.
  
Installation
This datapack has two parts that MUST be installed correctly:

Server-Side (Host): Place the datapack .zip file into your server's world folder, inside the datapacks folder.

Client-Side (All Players): All players (including the host) MUST install the same .zip file in their resourcepacks folder and enable it in their settings. This is required for everyone to see the PokeStop model.

How to Use & Configure
1. Spawning the CobbleStop
Once the datapack and resource pack are installed, you can spawn the NPC in-game (you must have OP permissions).

Simply run the command:
/spawnnpc pokestop

2. Configuring the Loot
You can change every item reward without touching the main script.

By using ``/npcedit`` you can edit all values including loot for each loot pool in the npc. 

3. Configuring the Cooldown
You can set the wait time for the PokéStop directly in-game.

Make sure you are in Creative Mode or have admin permissions.

Use ``/npcedit`` on the PokeStop NPC to open the NPC Editor.

Find the "Cooldown" setting in the top the editor.

Change the value to your desired wait time (in hours).

Save and exit the editor. The new cooldown will apply from the next time a player uses the PokeStop. Each PokeStop will have its own independent cooldown.

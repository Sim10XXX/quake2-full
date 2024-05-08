## To Install
Clone this repository, open the solution game.sln in Visual Studios and build "game". This will build the modded gamex86.dll file. Also build "quake2" to create a new .exe file, since the steam exe runs the remastered version.

Place the created exe in the directory of Quake 2 (rename it first), make a mod folder and place the dll there. 
Then create a shortcut to the .exe, right click it, go to properties, and add at the end of the "target" text " +set game mod", mod being the name of the mod folder.

## Features of the Mod
#### 7 Call Of Duty weapons
- M1911 
    - Infinite ammo
    - Launches grenades when being Quick Revived
    - Uses the blaster skin
- MP40
    - 8 rps
    - Machinegun skin
- M14
    - semi-automatic
    - Shotgun skin
- Olympia
    - Double barrel
    - Super shotgun skin
- Ray Gun
    - Splash damage
    - Grenade launcher skin
- Thundergun
    - Instakills at close range
    - Deals hefty knockback at long range
    - BFG10K skin
- Ballistic Knife
    - Low ammo
    - Pickup knife after shooting
    - Railgun skin (hand grenade skin didn't work very well)

#### 3 Perks
- Quick Revive
    - Prevents death and gives invincibility for 10 seconds
- Juggernog
    - Halves all damage taken
- Mule Kick
    - Sets guns limit to 3 instead of 2 (not including M1911)

#### 2 Powerups
- Insta Kill
    - All outgoing damage oneshots zombies for 20 seconds
- Max Ammo
    - Refills all ammo

#### Zombies
- Each wave has scaling health and zombie count
- Shooting a zombie gives 10 score, killing a zombie gives 100 instead
    - Score is used to buy perks
- Killing a zombie has a chance to drop any weapon or powerup

## How to Play
When loading quake2, just mash "enter" to go into an easy mode singleplayer game (I haven't tested multiplayer and so it probably doesn't work there).

Open up the console with the ~ key, and typing in "spawner" will create a spawn point for the zombies at your location. Once you placed the spawn locations, "nextwave" will start wave 1, and every wave after will automatically start when every enemy is killed.

Use the "buy" command to view the perks and their score prices. To buy a perk, for example quick revive, type "buy 1", or "buy qr", or "buy quick revive"

This mod uses the COD loadout style, instead of the quake2 style. Hotkeys:
* 1- M1911 (the blaster in quake2 cannot be removed, you always have this weapon like you always have the knife in actual COD)
* 2- Primary weapon
* 3- Secondary weapon
* 4- Tertiary weapon
* '- Drop weapon
* x- View score
* f1- Help screen

The order of primary/secondary weapons is based on the order of the original quake2 weapons that were modded


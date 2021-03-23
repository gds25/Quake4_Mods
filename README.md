# Quake4_Mods
Modifications to the Quake 4 source code

QUAKE 4: ZOMBIE SURVIVAL MOD

Head to the zombieMod branch to view my changes.

Notable changes:

- Every time you kill a wave of zombie-like monsters, a larger, more powerful wave spawns in its place.
- Every 5 waves, a teleporting, rocket-weilding boss spawns together with a small group of monsters.
- There are 7 monster models in total, including the boss.
- Each enemy you kill has a chance of dropping one of five short-term boosts: extra health, extra armor, extra speed, extra damage or invisibility.
- The current wave is indicated by the number on the bottom of the screen, next to your health (however, if you pick up an armor powerup that number
will be replaced by the amount of armor you have, until it reaches 0. After that, the current level reappears).
** As of 3/23/21, I have not yet implemented the item shop that the user would be able to access between waves. **

In order to install the mod, make a new folder in Quake 4's home directory, and place the file called game000.pk4
inside the folder. When Quake loads, click the mods tab in the bottom left of the main menu, and select the name of
the folder you just created. Load into a map of your choosing (as long as the event scripts are disabled) and start to play.

I would recommend playing on one of the multiplayer maps using the '+map <name>' command, as they are larger and are pre-loaded with floor loot.

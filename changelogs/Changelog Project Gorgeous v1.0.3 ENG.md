### Project Gorgeous v1.0.3 Changelog (648 mods)

🟩 **Added**
+ Extended Bone Meal
+ Nothirium
+ RenderLib

⬆️ **Updated**
+ MixinBooter (*9.4* => **10.2**)
+ FermiumASM (*5.23* => **5.24**)
+ Forestry (*5.8.2.422* => **5.8.2.424**)
+ Had Enough Items (*4.26.0* => **4.26.2**)
+ JAOPCA (*2.3.11.27* => **2.3.12.29**)
+ Corail Tombstone (*4.7.0* => **4.7.3**)
+ Simple Voice Chat (*2.5.24* => **2.5.26**)

🟥 **Removed**
- Caliper
- JEI Hider
- Nether Portal Spread

⚙ **Configs**
+ Aqua Acrobatics: Disabled Crawling due to buggy hitbox management
+ Aqua Acrobatics: The air bar now refills gradually instead of instantly (matching 1.13+ behavior)
+ Cavern: Reduced the mob spawn multiplier for all caverns (to 50)
+ Creeper Confetti: Increased the chance of triggering Creeper Confetti (from 20% to 25%)
+ Custom Main Menu: Added a link to the modpack's GitHub when clicking on the version number in the top-right corner to view Changelogs
+ DimensionalDoors: Reduced the maximum size of Rifts (from a 3-block radius to a 2-block radius)
+ InGame Info XML: Removed the word "time" from the time display to save some space
+ Living Enchantment: Enabled dialogue display for items with the "Living" enchantment (minimum cooldown of 25 seconds between messages)
+ FermiumASM: Disabled the new Object2ObjectOpenHashMap feature due to excessive RAM usage
+ Matter Overdrive: Increased the occurrence rate of gravitational anomalies (from 0.005 to 0.006 per chunk)
+ Nyx: Increased the chance of a Blood Moon occurring (from 15% to 20% during a full moon)
+ Nyx: Increased the mob spawn multiplier during a Blood Moon (from 2 to 20)
+ Nyx: Reduced the probability of falling stars appearing (from 1% to 0.5% per player per second)
+ Nyx: Increased the chance of a Harvest Moon occurring (from 5% to 15% during a full moon)
+ Nyx: Disabled meteors
+ Railcraft: Enabled "Vanilla" recipes for rails/tracks
+ Simple Voice Chat: Updated the default port for the voice server to match the Minecraft server's port
+ JourneyMap: Reduced the minimap size (from 30% to 28%)
+ Trinkets and Baubles: Adjusted the mana bar position to align with the reduced minimap size in JourneyMap

ℹ️ **Informations**
- This update focuses on QoL improvements, optimization, and adjustments to the modpack.
- The loading time of the modpack has been significantly reduced following the removal of JEI Hider! You will notice a **reduction of about 45% in launch time**.
- The amount of RAM used by the modpack has been reduced, notably due to the removal of the debug mod Caliper! You will see a **reduction of around 1.2 GB in RAM usage**.
- After testing, Nothirium has been added to the modpack to replace OptiFine **if you are playing on Linux**. If you are playing on Windows, this addition has no impact, and installing OptiFine is still highly recommended!  
- Nether Portal Spread has been removed due to its negative impact on server performance.
- Nyx meteors have been disabled as they were hard to control in-game, destructive, and far too frequent. Additionally, meteors would massively accumulate in unloaded chunks, causing an endless meteor shower when players entered those chunks.
- For Simple Voice Chat, the default port has been changed to make the modpack server easier to set up and configure. However, if possible, it is recommended to change the port used by Simple Voice Chat (in the `voicechat-server.properties` file in the `config/voicechat` folder) to something other than the one used for the Minecraft server.
- The next major update to the modpack will focus on adding quests to the modpack.

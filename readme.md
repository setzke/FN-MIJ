This repository is my actively building a pack to practice/learn Github and packwiz.

Curseforge zip needs profile edited and added java argument `-javaagent=unsup.jar`

If this is not done before first run, presetting keybindings and some settings will not occur.

Zips:  
https://github.com/setzke/FN-MIJ-dev/releases/download/zip/FN-MIJ-dev.base.CurseForge.zip  
https://github.com/setzke/FN-MIJ-dev/releases/download/zip/FN-MIJ-dev.base.Prism.zip


<details>
<summary>My personal area:</summary>
**TODO:**
add CREATE

nogui server test  
does pack auto-update a change with nogui? (try to override OPs or something after changing it in game. also have 2 dummy files. With the update test, modify one, remove the other, and add a 3rd.)

*low priority:* 
distant friends names  
Look into resource-pack-overrides config  
Investigate config for traveler's titles. Add title for mindscape that isn't "???". Other biomes too if added later. PURPLE OFC.  
-example from the mod page:  
"travelerstitles.minecraft.the_nether": "The Nether",  
"travelerstitles.minecraft.the_nether.color": "ff0000",  
singleplayer or OP test:  
/biometitle <biome>  
/dimensiontitle <dimension>  
Work on unsup colors.  




*Backburner:*
Look into analytics mod in pack

Figure out how simple rpc works. Can January set it to STREAMING and have a link to his twitch on Discord? Not needed, but a cool feature.  
clean up server vs client files (options and servers.dat aren't needed in server)

garbage collection for DH for client if needed  
(server exists, but that was for java 25. Would other servers have java 17? Should it adapt to version? Can java handle just throwing each one at it? Look into garbage collection.)
Client is java 17 and needs shenandoah, if any

jei setting (investigate)  
TEST: get benchmark of FPS, disable Subtle Effects and rollback Forge version (47.4.8) to see if FPS affected

----
Failed fabric Homestead hexxy:\
cardinal components api\
hexcassettes\
hexical\
hextended\

</details>
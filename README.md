# stalker_cs_compass_fix
This will help you prevent the Compass Artifact from being permanently given to the Forester NPC

[DISCLAIMER]
This is a simple fix for those who want to keep the Compass artifact past the "find compass" forester npc's mission in the Red Forest.
This was tested on the Windows Steam version of S.T.A.L.K.E.R. Clear Sky, not the enhanced version, and entirely vanilla

[INSTRUCTIONS]
Simply open your game profile page on steam in your lirbary, rclick on the name STALKER Clear Sky, click on "Manage", then "Browse local files". 
You will have to drag and drop the gamedata and its subfolders that you downloaded from here in there, and it should be good for the "technical" part.

Now simply run the game, save right before interacting with the forester npc just in case, then complete the mission. 
It should be completed and continue to the npc's next dialog line, with him giving you his Vintar VC while not taking your Compass artifact
Enjoy playing the game!


[IF IT STILL DOESN'T WORK]
If it doesn't work, try changing the fsgame.ltx file in your root folder (where you dropped the gamedata folder) with a simple text editor.
Turn this line:
$game_data$             = false| true|  $fs_root$|            gamedata\
into this:
$game_data$             = true|  true|  $fs_root$|            gamedata\

It should not be necessary but if following the steps above didn't work, you can try again with this changed as well
If for some reason it still doesn't work, you can ask me and i'll anwser/help if i can

[NON IMPORTANT INFOS]
I'm not a stalker mod dev i just really hate the decision to give up one of the best artifact to complete an obligatory mission. 
The Compass can be found WAY before you are aware of it retrieval mission and by then one can have created an entire playstyle based on this radiation free infinite endurance buff, and i consider GSC's decision to reward curiosity and proactiveness (i found it 10+hrs before i knew of the forester compass retrieval mission and had to fight hard to get it)  with a unbalanced trade a complete joke of a game design choice. 
A subsonic upgraded Vintar VC isn't worth the Compass, so i found a simple way to bypass it, without downloading some heavy mod that will likely change other things

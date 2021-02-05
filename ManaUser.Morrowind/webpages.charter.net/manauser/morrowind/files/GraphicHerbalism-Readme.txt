
**********************************************************************

     The Elder Scrolls III
           MORROWIND: 
    Graphic Herbalism  v1.2

    Requires both expansions
	
**********************************************************************

Index:
1. Installation
2. Playing the Plugin
3. Save Games and Compatibility
4. Known Bugs
5. Credits & Permission


**********************************************************************
     1. INSTALLING THE PLUGIN
**********************************************************************

To install the plug-in, unzip all files into the Morrowind\Data Files 
directory, making sure to keep the directory structure intact. Then, 
from the Morrowind Launcher, select Data Files and check the box next 
to the files you wish to use.

Bloated Caves.esp
	Adds bloat spores to caves. (Works alone too.)
Graphic Herbalism.esp
	The main mod.
	Changes all plants, and kallops, egg sacks
Graphic Herbalism Extra.esp
	Requires Graphic Herbalism.esp
	Changes minerals and misc. other stuff. Less "purist".

Note, this load order is important. If you change and of the mods try
to keep them in this order.

**********************************************************************
     2. PLAYING THE PLUGIN
**********************************************************************

When you activate a plant, instead of opening like a container you 
will automatically try to harvest ingredients. A message (as well as a 
sound effect) will let you know whether you succeeded, and if so, how 
many ingredients you got. You have the same chance of getting 
ingredients as in the original game.

Also the plant will change so you can see that it's been picked over. 
For instance the berries on the comberry bush or the blossoms on a 
stoneflower will disappear. Some plants like marsh merrow and corkbulb 
are harvested whole so the entire plant will disappear.

Plants respawn in 30 days. Officially it took the months in the 
original game, but due to some strangeness with leveled lists it could 
actually be less. In any case you can adjust this by setting this 
global in the console: MU_GH_DaysToRegen

If you decide to use Graphic Herbalism Extra.esp a few other things 
will change. Minerals (glass, ebony, etc.) will require a pick to 
collect in quantity. They will also change to show when they're 
depleted, like plants do. Certain plants will require a tool of some 
kind to harvest effectively too.

**********************************************************************
     3. SAVE GAMES AND COMPATIBILITY
**********************************************************************

Incompatible with mods that put scripts on, or otherwise change 
pickable plants.

Most of the "picked" models use no new textures so they will not clash 
even if you use a texture replacer. However depleted ore and four 
plants (comberry, mucksponge, holly and spiny lloramor) could only be 
represented using a new texture and may not look good if you use a 
texture replacer that effects those plants.

It's safe to add this mod to an existing game.

If you previously used another "herbalism" mod, replacing it with this 
one should be safe, but I have not tested this with all such mods.

Unloading this mod from an existing save in problematic however as
picked plants will be left disabled. The only solution I can offer is 
to set MU_GH_DaysToRegen to 0 and visit every cell you've picked
plants in before unloading the mod.

**********************************************************************
     4. KNOWN BUGS
**********************************************************************

When you pick a plant, sometimes the new model won't be lit correctly.
I did what I could to minimize this. In any case it will go away as
soon as you leave the area and return, or when you move at all if the
light source is your torch/landern.

**********************************************************************
     5. CREDITS & PERMISSION
**********************************************************************

Syclonix
For creating Herbalism for Purists, which inspired this mod.

The NifTools team
For NifSkope, which I used to hack off bits of the plants.

Created by ManaUser
paul AT manauser DOT info

You may use anything from this mod, credit is appreciated but
optional. That means you can redistribute the whole thing too,
though in that case, I sure hope you give me credit. :)

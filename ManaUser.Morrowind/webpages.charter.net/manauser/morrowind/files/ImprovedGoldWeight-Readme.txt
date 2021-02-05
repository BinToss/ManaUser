*****************************************************************

                     The Elder Scrolls III
                           MORROWIND: 
                    Improved Gold Weight v1.1

         Needs either Tribunal or Bloodmoon for scripting.
	   		
*****************************************************************

This is my attempt at a gold weight mod. It doesn’t add weight
directly to the gold, so it won't cause encumbrance errors. Nor
does it add ugly "dead weight" objects. Instead it adds weight by
"removing" objects of negative weight. A little hackish, but it
works well. It also has a few globals for customization, see the
Playing The Plugin section.

Index:
1. What's New?
2. Installation
3. Playing the Plugin
4. Save Games and Compatibility
5. Known Bugs
6. Credits & Permission


*****************************************************************

     1. WHAT'S NEW?

*****************************************************************

New since version 1.0:
Fixed junk messages when recicing gold in a greeting.

*****************************************************************

     2. INSTALLING THE PLUGIN

*****************************************************************

To install the plug-in, unzip Improved Gold Weight.esp into the
Morrowind\Data Files directory. Then, from the Morrowind
Launcher, select Data Files and check the box next to that file.

*****************************************************************

     3. PLAYING THE PLUGIN

*****************************************************************

The mod is ready to play "out of the box", but there are a couple
things you can change if you like. The settings are stored in the
following globals:

MU_GW_Each
This is the weight of each coin. - Default 0.01

The default is good if you want gold weight to have a significant
impact on the game. If you just want gold to have *some* weight
for the sake of realism, you might want to reduce it to 0.001
instead. Anything higher than 0.01 would be sadistic, IMHO. And
yes, changing this setting mid-game would be considered a cheat.

MU_GW_MenuBlock
0 = Update in menus.
1 = Update in menus only if sneaking. - Default
2 = Never update in menus.

This controls whether gold weight will update while in menu mode.
It doesn't cause a noticeable slowdown (for me, at least) but
will result in unnecessary messages when you gain or lose gold
through dialog, such as paying a fine, or getting a cash reward
for a quest. But on the other hand, it's nice to see your
encumbrance "live" as you add and remove gold, especially if
you're close to your weight limit.

Set or check any of these from the console using this format:
set mu_gw_xxx to value
show mu_gw_xxx

Also of interest: MU_GW_Total
This is the current combined weight of all your gold. Don't set
this one, just show it, or you'll mess things up. You'll notice
that it's rounded down to a whole number for simplicity, and also
to cut down on message spaming if you have it set to remain
active during dialog.

*****************************************************************

     4. Save Games and Compatibility.

*****************************************************************

Safe to add to an existing game. When removing this mod from a
game, just remember to drop your gold first, so you won't be left
with the weight.

Incompatible with other gold weight mods. But that's obvious.

It's safe to upgrade the previous version of this mod. You will
see an error message concerning the variable count in a script
but this won't cause any problem.

*****************************************************************

     5. Known bugs.

*****************************************************************

Only the previously mentioned junk messages that will be seen if
you gain or lose gold in dialog with MU_GW_MenuBlock to 0.

*****************************************************************

     6. Credits & Permission

*****************************************************************

Created by ManaUser
paul AT manauser DOT info

You may use anything from this mod, credit is appreciated but
optional. That means you can redistribute the whole thing too,
though in that case, I sure hope you give me credit. :)
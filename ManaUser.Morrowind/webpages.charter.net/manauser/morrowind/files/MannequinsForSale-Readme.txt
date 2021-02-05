*****************************************************************

     The Elder Scrolls III
           MORROWIND 
    Mannequins for Sale v1.31
         Now with Wigs!

Requires Bloodmoon, but see below...
	   		
*****************************************************************

I wasn't impressed with any of the portable mannequin mods I
tried. Especially when it came to holding weapons. None of them
would keep holding the weapon when I left the area (even though
some claimed they would). So I made my own.

Index:
1. What's New
2. Installation
3. Playing the Plug-in
4. Save Games and Compatibility
5. Known Bugs
6. Credits & Usage

*****************************************************************
     1. WHAT'S NEW
*****************************************************************

New in v1.3

Added: Wigs, and an associated "quest", of sorts.
Fixed: Misc typos in dialog and such.

New in v1.2

Fixed: Handling of delivery for special mannequins.
Fixed: Mannequin "running" at you in battle pose.
Added: Redundant cell change check. (CellChanged is unreliable.)
Added: Warning before touching a mannequin you don't own.
Fixed: Useless topics in the PC's journal.
Added: Natural pose. Similar to "At Rest", but more natural...
       Basically it's a slightly wider stance.

*****************************************************************
     2. INSTALLING THE PLUGIN
*****************************************************************

To install the plug-in, unzip all files into Morrowind\Data Files
keeping the directory structure intact. Then, from the Morrowind
Launcher, select Data Files and check the box next to either:

Mannequins for Sale.esp
(Main mod, normally use this. Requires Bloodmoon.)
or
Mannequins Resource.esp
(Simple demo. Works with either or both expansion packs.)

*****************************************************************
     3. PLAYING THE PLUGIN
*****************************************************************

As mentioned above, there are two version of this mod:

Mannequins for Sale.esp
This is the normal version, in which a shop is added to Caldera.
It's near the Mages Guild, down a little alley between two other
buildings. So... You go there, talk to the shopkeeper and the
rest should be obvious.

To get the wigs you'll have to chat with him for a bit, he'll
bring it up if you ask about the right topic.

Mannequins Resource.esp
Modder's resource or quick demo. You'll have to use the console
to see anything with this one. Use one of these commands:

COC MU_Man_TestCell - Go to demo cell with one of each mannequin.
Player->AddItem MU_Man_W_M_it, 1 - Get a male wooden mannequin.
Player->AddItem MU_Man_W_F_it, 1 - Get a female wooden mannequin.
Player->AddItem MU_Man_S_M_it, 1 - Get a male stone mannequin.
Player->AddItem MU_Man_S_F_it, 1 - Get a female stone mannequin.

Or if that sounds too much like cheating, AddItem them to an NPC
that sells MISC items and then buy them.

GENEERAL INFO

The mannequins are, of course, actually NPCs. When you "talk" to
one of them, you can dress it using Companion Share or use one
of the special topics to pick it up or change its pose. Before
you can pick it up, you will have to remove any items you've put
on it. Picking it up it turns into a miscellaneous item. Just set
it down to turn it back into an NPC.

The following poses are available are:
At Rest - Default standing pose.
Battle - Weapon drawn or hands in fists.
Jumping - Actually the landing pose.
Stealth - Basic "sneaking" pose.
Stealth+W - Stealth/Battle hybrid.
More... has the following sub-options:
Reach for Weapon
Hand on Hip (female only)
Thoughtful (or maybe it's heartburn)
Hand on Head
Stretch
Natual

Tip: When equipping a mannequin with a bow or crossbow, give it
an arrow or bolt too. Otherwise an invisible one will be used.

*****************************************************************
     4. Save Games and Compatibility.
*****************************************************************

It's safe to upgrade from previous versions of this mod. Just
replace the old esp file with this one. If upgrading from 1.2
you shouldn't even see any errors. With earlier versions you will
see errors about the number of local variables in scripts and
missing dialog topics for various poses. These are both harmless.

However, to make upgrading this way possible, I had to hack the 
object index numbers. Unfortunately, they will change back if you 
edit this mod in the Construction Set. That doesn’t mean you 
can't do it, you just lose compatibility with old saves.

*****************************************************************
     5. Known bugs.
*****************************************************************

As far as I can tell it's not possible to actually keep them in
the same position when you leave (or reload) so instead they're
scripted to resume their poses when you return (or reload). This
means you may see them moving, and for weapon-drawn poses this
means they have to "start combat" with the PC for a moment.
(Complete with battle music.)  Annoying, but unavoidable.

Because of the above, you should avoid giving them items with
offensive "Cast On Use" enchantments if they will be in one of
the weapon-drawn poses, otherwise they just might use it on you.

Also you can be charged with assault for hitting them.

And wigs make your ears disappear, but they're really for the
mannequins, not you, so I figure that's acceptable.

*****************************************************************
     6. Credits & Usage
*****************************************************************

Created by ManaUser
paul AT manauser DOT info

You may use anything from this mod, credit is appreciated but
optional. That means you can redistribute the whole thing too,
though in that case, I sure hope you give me credit. :)

If you would like to re-use some part of this in your own mod I
would prefer you change all the IDs and file names, so your mod
will not be incompatible with mine. If you need any advice or
assistance doing that, I'll be happy to help.

And if someone wanted to reuse the scripts with fancier
mannequin bodies, that would be just fine with me. The script
could also be adapted to make good use of an animation file in
which the standard idle anims were replaced with something more
interesting and statuesque.
*****************************************************************

     The Elder Scrolls III
           MORROWIND: 
 Companion Role Play Plus v1.01

Requires Tribunal OR Bloodmoon, for scripting functions.
	   		
*****************************************************************

This mod adds a few special "topics" to any NPC with Companion
Share enabled (companions, presumably). You can ask your
Companion "How's your health?" which is handy, but the rest are
just an aid to role play; to make your companion seem a little
more like a separate person from your character.

In general, this is better for companions without much
personality of their own. But as long as you use a little common
sense, you can use it with more intelligent companions too. For
example, Constance (a neat compantion by Grumpy and Emma) tells
you right off she doesn't want a romantice relationship, so don't
be silly and ask her about it with this mod. On the other hand,
as far as I know, she has no pre-set opinion on Newtscale armor,
so it would be perfectly reasonable to ask her if she likes it.

Index:
1. Installation
2. Playing the Plugin
3. Save Games and Compatibility
4. Known Bugs
5. Credits & Usage

*****************************************************************

     1. INSTALLING THE PLUGIN

*****************************************************************

To install the plugin, unzip the file into the 
Morrowind/Data Files directory. From the Morrowind Launcher,
select Data Files and check the box next to Companion RPP.esp.

Comp RPP CoverUp Add-on.esp makes the loincloths and brassieres
from my Cover-Up plug-in the prefered attire when a companion is
told to dress for "Swiming" or "Bed". Only use this if you're
using Cover-Up. (And even if  you are, it's still optional.)

*****************************************************************

     2. PLAYING THE PLUGIN

*****************************************************************

There are three "topics":

<A Favor>

You can either ask a favor or do a favor. Strictly speaking this
is nothing but a semi-random way to modify your companion's
disposition, it has no other game effect. The idea though, is
that when you do something extra for your companion, like buying
them a new weapon or taking them somewhere nice to watch the
sunset, the game doesn't take this into account at all. So you
can let it know you've done a favor with this. Similarly if need
to borrow your companion's armor, or you leave them behind when
you know they would want to come, you can ask for a favor. In
this case they may refuse if their disposition isn't high enough
for the size of the favor. Use your own judgement how big each
favor is.

<A Question>

Many of these have some kind of "fill in the blank". I suggest
you imagine exactly what you're asking, before you click the
final menu option.

The following questions are available:

"How do you feel?"
Will tell you if they've caught a disease, or are very badly
wounded, otherwise gives random emotion.

"How's your health?"
Will give you more detail about their hitpoints. (Nine
different messages.)

"Do you think...?"
Random says whether they agree with a statment.

"Do you like it?"
Will randomly say how much they like something.

"Yes or No?"
All purpose yes/no (and sometimes maybe) answer.

"Something else." Gives the following extra options:

"What should we do?"
Random suggestion of how to spend some time.

"How shall we travel?"
Basically picks from Walk, Transport Service and Magic, with
a little flavor text.

"Do you like him/her?"
Will randomly say how much they like someone.

"When...?"
Randomly tells how soon they want to do something.

"Pick from a list."
You can further specifiy from 2 to 6 options and they will pick
one by number. (So be sure you decide what order you would be
giving the rela options in.)

With all of these (except health) feel free to assume they're
joking or being sarcastic if they say something wildly off
target.

And a little behinds the scenes note: The do you like/think
questions have a bias towards a positive response, since I
figure you wouldn't have asked unless you thought it was likely,
but "Yes or No?" is evenly balenced.

<Apparel>

This lets you change your companion's outfit without having to
actually add and remove items from their inventory. There are
three pages of styles. The "Something else" option takes you to
the second page and "Something more unusual" takes you to the
third. A few notes on how this works:

They can only *remove* equipped items, but this works well since
NPCs wear their best equipment be default. For example you may
not like to imagine your companion walking around town in full
plate or swimming in a robe and heavy boots. Just be sure they
have something else on underneath... they won't notice if not.

In fact they will *always* agree to the outfit you suggest, if
you think it could be considered a "favor" for some reason, ask
first with <A Favor>.

Most of the options should be obvious except "Custom outfit".

To save an outfit, you first manually dress your companion by
using Companion Share to make sure only the equipment they should
wear is in their inventory, then use select "Create Outfit". You
can then give the rest of their stuff back. Thereafter you can
recall the outfit you created at any time by selecting the
"Restore Outfit" option. Note that it remembers item types
(eg. Boots, Skirt, and Shirt), but not specific items. And it
only remembers one outfit, no matter how many companions you
have, unless the companions were specifically made to work with
this mod.

*****************************************************************

     3. Save Games and Compatibility.

*****************************************************************

If you clean this mod with TES Tool or similar, it will probably
notice some clothing items duplicated from Tribunal and
Bloodmoon. These can safely be removed, but it was necesary to
include them to avoid script errors for people who have only
one expansion.

Another compatibility problem is with clothing that uses
non-standard item types. (Eg. A left pauldron that actually looks
like a skirt.) There's no way this mod can detect that; it takes
all item types at face value.

My one nod to accomodating non-standard items is the
"comfortable, with a hat" option, for helmets that aren't
really intended to be armor.

Also if Companion Share is used on an NPC who isn't actually a
Companion, (like a manequin or something) these options will
still show up. But you can always just ignore them.

Note to mod authors: If you want to avoid the above, you can add 
"short NoRPP" to you NPC's script to disable this mod for them.
Or "short NoRPPStrip" to disable the <Apparel> topic, but not the
other two. You can also add "long RPPCustomOutfit" to allow an
NPC to remember a custom outfit seperate from other NPCs.

*****************************************************************

     4. Known bugs.

*****************************************************************

Well, it would be really easy to cheat with the <A Favor> topic,
but if you do, you've badly missed the point. I can't think
of any real bugs.

*****************************************************************

     5. Credits & Usage

*****************************************************************

Created by ManaUser
paul AT manauser DOT info

You may use anything from this mod, credit is appreciated but
optional. That means you can redistribute the whole thing too,
though in that case, I sure hope you give me credit. :)
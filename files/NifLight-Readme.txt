                        NifLight v1.1

WHAT IT IS:

A tool for editing the lighting properties of .NIF files for Morrowind,
and specifically, making them glow.

This is somewhat obsolete thanks to NIBLE and NifSkope, but may
be useful for cases where you want to change a large number of files
at once.

DETAILS:

NifLight is similar to GhostWheel's NifColor, in that it can adjust
several files at once. But it can also edit specific materials in a
file or even specific materials in a batch of files, provided the
materials at named the same in each file. And of course it can edit
the Illumination value as well as Ambient, Diffuse and Specular.
It also allows you to check the existing settings of a mesh's
materials.

INSTALATION:

Just extract to a folder of your choice. Since the open dialog defaults
to the exe's location, you may want to put it near your .NIF files.

Because this was made with Visual Basic .NET you may need to download
the .NET framework. If NifLight gives you an error when you run it,
chances are that's why. You can install the .NET framework through
Windows Update, or get it here:
http://www.microsoft.com/downloads/details.aspx?FamilyID=0856EACB-4362-4B0D-8EDD-AAB15C5E04F5&displaylang=en

BASIC USAGE:

Click Add Files and select one or more Nifs. Adjust Ambient, Diffuse,
Specular and Illumination either by typing in numbers from 0 to 255 or
by clicking the colored box and using the Color Picker.
Then just click "Make It So", and you're done.

OPTIONS:

Keep Current Files checkbox:
  If this is checked when you click Add Files, the files currently in
  the list will stay. This Allows you to adjust lighting on files from
  different directors At the same time.

Materials checkbox:
  Shows the Materials list. When the materials list is visible, click
  a file in the file list to show it's materials. 

  You then click a single material to show it's colors in the boxes
  marked ADSI (Ambient, Diffuse, Specular, Illumination). Clicking
  one of these boxes will copy that color to the appropriate box above.

Change Selected Materials Only checkbox:
(Only visible when Materials checkbox is checked)
  If checked, clicking Make It So will change only the materials
  matching the names of the materials you select in the Materials
  box. (You can select more than one). Not that it still effects
  all files as long as they have materials by those names.

TIPS:

* If you need an object in several solid colors, (glowing or not)
  you can make the texture in grayscale and just light the meshes
  differently to save space. I did this in my Chalk Mod.

* If you're making a glowing mesh, but sure to give it a bright
  texture too. A brightly illuminated black object is still black.

* Whenever you use the Color Picker the color you select is stored
  in the custom color palette (the bottom 2 rows of the picker).
  You can also right-click a color box (including the ADSI ones)
  to save that color to the custom palette.

CREDITS:

Thanks to GhostWheel for posting information about where the
colors are stored in a NIF. Without that, I couldn't have made
this.

"LICENSE":

Do whatever you want with it.
Please distribute this program.
If you'd like a copy of the VB.NET source code, just ask.
(It's not too prety though.)

CONTACT:

E-mail: paul AT manauser DOT info
# Criteria
Using **Will's Mod Creator** is fairly straightforward, but these criterion must be met to successfully package your mod:
- You must give your mod a title, exporting is not possible without doing so.
- You must require at the minimum, both CustomFiles and CustomText hacks via the Checked List Box.
- *Imported icons must be within a power of 2 in both height and width ranging up to 256x256. 
- *For story based mods with unique save games and statistics, enable the **is Mod?** checkbox.
- *For frameworks (core), enable the **is Framework?** checkbox.

        *An asterisk denotes optional criteria


# Short Tutorial
## Meta Information
Setting up your first mod is easy. We can start by specifying a name, for example: 

       Futurama: Hit & Run 
                     
We then need to specify an internal name. For example:

       FHAR

You can then enter your own description. Linebreaks are replaced with \n blocks in the meta.ini. An example of which being this:

       " Welcome to Futurama Hit & Run, play as Bender, Leela and Fry
       and defend New New York from the evil mom corporation! "

Being turned into this:
       
       " Welcome to Futurama Hit & Run, play as Bender, Leela and Fry\nand defend New New York from the evil mom corporation! "

## Hacks
Lastly, you can enable any hacks you are going to make use of, the majority of them come with pre-assembled templates which give you an understanding of how they work.

**Notes**
- 3DPhoneBoothPreviews will generate a commented template, make sure you read up on the documentation before uncommenting it.
- Some of the templates have commented code, edit them how you'd like. 
(For further information on hacks, go to https://donutteam.com and visit their documentation (thanks guys!))

## Exporting
Once your mod is all ready for packaging, hit the create mod button below the description box, you'll be prompted to export to a location of your choice. 

Your mod will be assembled in a folder which correlates to your mod's name. If your mod is in the **mods** folder used by ****Lucas' Simpsons Hit & Run Mod Launcher****, it will display in the mods list when you open that program, fully assembled. 

# Log
**V.1.0**
- First release, v.1.0
- Fully functional mod packager.
- Recoded from scratch and improved in C#
<img src="docs/img/tutpage1.png"/>

**V.0.1-V.0.9**
- Never released, began in 2017, stopped in mid 2018.
- Buggy, programmed in VB.NET till v.0.9.
- Lacked all 30+ hacks, very barebones.
<img src="docs/img/old1.PNG"/>
<img src="docs/img/old2.PNG"/>

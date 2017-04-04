Fast way to compile on windows, download mingw (make sure you have the makefile building programs), enter Command Prompt, cd to My-Angband-4.0.5-master\src. Type make -f makefile.win mingw=yes.

Note: After you create your character it will complain about a parse error in the graphics, but will load fine (except with the wrong terrain graphics in the town). This is because I added more monsters and a bookstore that the graphics do not support. Go to the Options menu, find the graphics sub-menu and change to none. This will fix the otherwise annoying graphics inconsistencies, and prevent future non-fatal parse error complaining. (Fatal parse errors shouldn't show up unless you mess with the gamedata files.)

I chose the name VarAngband or variety angband, because that is my main goal - to include as much variety as possible, in a game with non-Zelazny monsters ie. Morgoth (instead of Serpent of Chaos) etc. There is still a lot of progress to be made, before I will feel ready to create an official release.

------------------------------

To-do (so far, this branch (a reminder for myself)):


Finish uploading edit files with normal line endings: object.txt.

Add level 6 monsters from Unangband.

Add BR_CONF for Giant Bronze Dragon Flies.

-------------------------------------

Start adding player spells from FAangband that aren't easily made from existing effects.

(Mage Book #1) Fix Reduce Cuts and Poison - add a message for TIMED_DEC:CUT so it is clear that it has reduced cuts.

(Mage Book #1) Add/Fix Resist Magic - TIMED_INVULN has an entirely different effect in Vanilla.

(Mage Book #2) Add Telekinesis.

(Mage Book #2) Add Magical Throw.

Add Magic Book for Mages #3.

Add all the other books.

-------------------------------------

Figure out why new spellbooks don't display in inventory and shop lists, fix.

Find out how to fix monster invisibility spell, so the invisible monster can't be detected by detect monsters, displays 2nd message ({monster} disappears!), and reappears again.

Add sexes back in to birth choices.

Add framework for special abilities like Zangband-descended variants.

Start attempting to add terrain from Unangband.

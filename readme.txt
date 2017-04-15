Fast way to compile on windows, download mingw (make sure you have the makefile building programs), enter Command Prompt, change directory to varangbnad-master\src. Type make -f makefile.win.

Note, on windows: After you create your character it will complain about a parse error in the graphics, but will load fine (except with the wrong terrain graphics in the town). Go to the Options menu, find the graphics sub-menu and change to none. This will fix the otherwise annoying graphics inconsistencies, and prevent future non-fatal parse error complaining.

I chose the name VarAngband or variety angband, because that is my main goal - to include as much variety as possible, in a game with re-Tolkienized or at least non-Zelazny monsters ie. Morgoth (instead of Serpent of Chaos) etc. There is still a lot of progress to be made, before I will feel ready to create an official release.
------------------------------

Basic changes so far

Races added from Unangband (though without shapeshifts), EyAngband, FAangband, and some from PosChengband (though without special abilities, non-humanoid bodies (Centaur), or flags gained at a later level). 55 Total, I know some of them are very similar to each other or even just renamed.

Classes added from Oangband/FAangband. Druids/Necromancers are currently using Mage spells. Assassins currently have Rogue spells. (No ability framework, not sure what to do with that yet.)

Monsters added from Unangband up to level 8. (This does mean that non-friended monsters up to level 28, don't currently exist in gameplay because I haven't got there yet and they have duplicate numbers.)

Spellbooks added from FAangband, still with Vanilla Mage, Ranger, and Rogue spells. Nature and Necromancy books don't display names in inventory or shop lists.

Some other objects added from other variants (mostly weapons).

------------------------------

To-do (this branch):

Add player spells from FAangband that aren't easily made from existing effects.

(Mage Book #2) Add Telekinesis.

(Mage Book #2) Add Magical Throw.

(Mage Book #3) Add Detect Enchantment.

(Mage Book #4) Add Thrust Away.

(Mage Book #4) Add Tap Magical Energy.

(Mage Book #4) Add Rune of Magic Influence.

(Mage Book #4) Add Hold Monsters.

Add Magic Book for Mages #5.

Add all the other books' spells, right now all the Nature and Necromancy classes use the old Mage, Rogue, and Ranger spells.

-------------------------------------

Figure out why new spellbooks don't display in inventory and shop lists, fix.

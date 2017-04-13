Fast way to compile on windows, download mingw (make sure you have the makefile building programs), enter Command Prompt, change directory to varangbnad-master\src. Type make -f makefile.win.

Note, on windows: After you create your character it will complain about a parse error in the graphics, but will load fine (except with the wrong terrain graphics in the town). Go to the Options menu, find the graphics sub-menu and change to none. This will fix the otherwise annoying graphics inconsistencies, and prevent future non-fatal parse error complaining.

I chose the name VarAngband or variety angband, because that is my main goal - to include as much variety as possible, in a game with re-Tolkienized or at least non-Zelazny monsters ie. Morgoth (instead of Serpent of Chaos) etc. There is still a lot of progress to be made, before I will feel ready to create an official release.
------------------------------

Basic changes so far

Races added from Unangband (though without shapeshifts), EyAngband, FAangband, and some from PosChengband (though without special abilities, non-humanoid bodies (Centaur), or flags gained at a later level). 55 Total, I know some of them are very similar to each other or even just renamed.

Classes added from Oangband/FAangband. (No ability framework, not sure what to do with that yet.)

Monsters added from Unangband up to level 8. (This does mean that non-friended monsters up to level 28, don't currently exist in gameplay because I haven't got there yet and they have duplicate numbers.)

Spellbooks added from FAangband, still with Vanilla Mage, Ranger, and Rogue spells. Nature and Necromancy books don't display names in inventory or shop lists.

Some other objects added from other variants (mostly weapons).

------------------------------

To-do (a reminder for myself):

Add level 8 monsters from Unangband.

-------------------------------------

Finish player-spells branch, merge.

-------------------------------------

Figure out why new spellbooks don't display in inventory and shop lists, fix.

Find out how to fix monster invisibility spell, so the monster displays the 2nd message ({monster} disappears!), and reappears again.

Create a PosChengband-style race catagory birth menu.

Add PosChengband races, monster races, and classes.

Set up birth menu system: Choose gender, choose normal or monster race, choose race catagory, choose race, if normal races - choose between FAangband-based and PosChengband-based class/magic system, choose class, if PosChengband-based - choose magic realms.

Add sexes back in to birth choices.

Possibly (and probably controversially) add a birth option to use either the six gender system from ancient Judaism: Zachar (male), Nekeivah (female), Androgynos (both), Tumtum (indeterminate), Ay'lonit (trans->male), and Saris (trans->female); (http://www.sojourngsd.org/blog/sixgenders) or the old Native American gender system with 3-5 genders (more difficult because of different traditions/languages and is less clearly defined) basically: Female, Male, Masculine Female, Feminine Male, and Two-Spirit; (https://indiancountrymedianetwork.com/news/opinions/two-spirits-one-heart-five-genders/) instead of the semi-modern binary system.

Add framework for special abilities like Zangband-descended variants. Add Shapeshifts for Maiar, Vampires, Werewolves, Beornings, & spells.

Start attempting to add terrain from Unangband.

Add Pathfinder / D&D 3.5 races? Maybe even some Star Wars / Star Trek races? (Because I've always wanted to play a Twi'lek Rogue.)

Make it so monsters drop corpses, that can be cooked or salted to make food, or traded for bounties. (Unangband/PosChengband)

Super Firkraag Mod for BG2
	by: Rastor

-------------------------------------------------------------------------------
I.   Why?
II.  Installation Instructions
III. Known bugs
IV.  Support and Help
V.   Un-installation
VI.  Special Thanks
VII. Version History
-------------------------------------------------------------------------------

========
I. Why?
========

Before we begin this section, let me assure you that I am not now, nor have I ever been a masochist. The actual original reason for this mod was a comment made on the Sorcerer's Place boards. This particular poster in question thought that even Weimer's Improved Dragon AI scripts were too weak. As I was in the process of studying the AI in-game, I decided to take on the challenge of making a Firkraag so tough that even the hardcore tacticians would be screaming for mercy. This is the first of those experimental scripts.

I am constantly attempting to improve this script until I come up with one that simply cannot be beaten until the very end of the game, as dragons should be. For reference, I was able to beat the Tactics Improved Firkraag in Chapter 2 with my Cavalier. That is not very flattering for what is supposed to be one of the most powerful beasts in all of Faerun.

This mod should make Firkraag the incredibly powerful magic-user and dragon that he should be. I'm issuing a challenge for all you masters of cheese out there to come up with methods to beat this guy. I intend to remove them in future versions (yes, you'll get credit for the idea).


==============================
II. Installation Instructions
==============================

If you want to have Tactics mod installed (www.weidu.org- I heartily recommend it) then it must be installed before this mod. Generally, Super Firkraag needs to be installed last. It is compatible with every mod that I'm aware of.

Installation is simple. Run the executable that is included in the ZIP file. Simply select your favorite language and pick yes when asked to install.


================
III. Known Bugs
================

Seems to be deprecated since a while!!!
The only known bug is a PARSE_ERROR command on a .sto file in your override directory (possibly a mod?). Ignore this. I have no idea what causes this, but it doesn't seem to affect anything. This mod doesn't touch that file, regardless.


=====================
IV. Support and Help
=====================

Super Firkraag is a WeiDU mod, and therefore should be compatible with all WeiDU mods. However, we cannot test every single one. If you encounter any bugs, please report them on the forum! ( http://www.shsforums.net/topic/60737-super-firkraag-updated-to-v16-ee-compatible/ )

[DEPRECATED as of v1.6
I currently maintain a forum at rpgdungeon.myikonboard.com. You're welcome to post anything there about either the game itself or any mod. I check it daily, as do a few of the other prominent names in the modding community. I will help you come up with a method to beat this Firkraag if you ask nicely, but don't expect that exploit to work in future versions!]


===================
V. Un-installation
===================

Found Firkraag to be more than your cup of tea? No problem. Simply re-run setup-firkraag.exe. The program will give you the option to un-install. This will return the Firkaag to the "factory-fresh state." Note that I'm unsure whether this will affect anything if you've already visited him. If so and you're totally stumped, Ctrl-Y him.


===================
VI. Special Thanks
===================

- Strifestrike: For coming up with the idea for this mod and being one of my original testers.
- Beren: The first person that I know of to have beaten the Firkraag mod. He was my primary tester and a really swell guy!
- Community at SP: For supporting my modding hobby and providing a good environment.
- Weimer: I actually used his scripts as a basis for making this one. He also developed the WeiDU tool, which is what this mod uses.
- The BiG World Textpack German project Team: German translation.
- SoM (part of CoB Clan): Polish translation.
- A.E.R.I.E.ru Team: Russian translation.
- Mathrim Cauthon: French translation.


=====================
VII. Version History
=====================

Version 1.6

- Added firkraag.ini metadata file to support AL|EN's "Project Infinity".
- Renamed setup-Firkraag.tp2 -> firkraag.tp2 to support AL|EN's "Project Infinity".
- Replaced `AUTHOR` keyword with `SUPPORT`.
- Added `VERSION` flag.
- Replaced `AT_INTERACTIVE_EXIT` deprecated command with README.
- Added missing `REQUIRE_PREDICATE` process to avoid installing the mod in inaccurate games.
- Added component `DESIGNATED` number and "super_firkraag" `LABEL`.
- Added missing `HANDLE_CHARSETS` function to convert string entries for EE games.
- Added native BG2:EE and EET compatibilities.
- Set a new override script to firkra02.cre (fdragred.bcs) to avoid overwriting other red dragons scripts (dragred.bcs).
- Added missing amulet (fstalk.itm) giving protection from Wing buffet to Invisible Stalker (fstalke.cre).
- Added French, German and Polish WeiDU prompts.
- Proofread English and French translations.
- Added Polish translation (thanks to SoM, part of CoB Clan).
- Added German translation (from the BiG World Textpack German project).
- Wrote a new firkraag-readme-english.html readme file and moved it into new "readme" folder.
- Removed useless backup folder.
- Reorganized mod architecture tree: created folders to sort files according to their types and renamed top folder CScripts -> firkraag.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Updated WeiDU installer to v246.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

Version 1.5
- Added Russian translation (Thanks to the A.E.R.I.E. Team).
- Updated WeiDU installer to v231.

Version 1.4
- Added French translation (Once again, thanks to Mathrim Cauthon).

Version 1.3
- Fixed a bug that was causing the script to not compile correctly. Thanks Andrew!

Version 1.2
- File uses better compression, so downloading speed will be increased.

Version 1.1
- Firkraag now uses better spells, he'll no longer kill his own invisible stalker, and his death spell works now.

Version 1.0
- Initial release.

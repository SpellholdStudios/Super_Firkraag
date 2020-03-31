
![Latest Release](https://img.shields.io/github/v/release/SpellholdStudios/Super_Firkraag?include_prereleases&color=darkred)<a name="top" id="top"> </a>
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20Mac%20%7C%20linux&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20German%20%7C%20Polish%20%7C%20Russian&color=limegreen)

<div align="center"><h1>Super Firkraag (WIP)</h1>

<h3>A mod hosted by Spellhold Studios for Baldur's Gate II: SoA and ToB (classical and EE games),<br>
Baldur's Gate Trilogy and EET<h3>

</div><br />


**Author:** Rastor  
**Mod Website:** <a href="">Spellhold Studios</a>  
**Mod Forum:** <a href="">Super Firkraag</a>  


[Read the mod's readme](http://spellholdstudios.github.io/readmes/firkraag-readme-english.html).

[Download the mod at Spellhold Studios]().<br>


**Note:** This mod was first released at <a href="http://web.archive.org/web/20120414212350/http://www.rpgdungeon.net/content/view/30/44/">RPGDungeon.net</a>. As this site is no more available since many years, it was time to save it from disappearance. It is now hosted at Spellhold Studios with Rastor authorization.


&nbsp;

<div align="center">
<a href="#intro">Overview</a> &#8226; <a href="#compat">Compatibility</a> &#8226; <a href="#installation">Installation</a> &#8226; <a href="#components">Components</a> &#8226; <a href="#credits">Credits and Acknowledgements</a> &#8226; <a href="#versions">Version History</a></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This mod should make Firkraag the incredibly powerful magic-user and dragon that he should be. I'm issuing a challenge for all you masters of cheese out there to come up with methods to beat this guy.

<details><summary>Original note from the author</summary>
<p>

###### Let me assure you that I am not now, nor have I ever been a masochist. The actual original reason for this mod was a comment made on the Sorcerer's Place boards. This particular poster in question thought that even Weimer's Improved Dragon AI scripts were too weak. As I was in the process of studying the AI in-game, I decided to take on the challenge of making a Firkraag so tough that even the hardcore tacticians would be screaming for mercy. This is the first of those experimental scripts.

###### I am constantly attempting to improve this script until I come up with one that simply cannot be beaten until the very end of the game, as dragons should be. For reference, I was able to beat the Tactics Improved Firkraag in Chapter 2 with my Cavalier. That is not very flattering for what is supposed to be one of the most powerful beasts in all of Faerun.
</p>
</details><br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibility
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

**Author:** Rastor  

## 

#### Special Acknowledgements to:

- Strifestrike: For coming up with the idea for this mod and being one of my original testers.
- Beren: The first person that I know of to have beaten the Firkraag mod. He was my primary tester and a really swell guy!
- Community at SP: For supporting my modding hobby and providing a good environment.
- Weimer: I actually used his scripts as a basis for making this one. He also developed the WeiDU tool, which is what this mod uses.
- The BiG World Textpack German project Team: German translation.
- SoM (part of CoB Clan): Polish translation.
- A.E.R.I.E.ru Team: Russian translation.
- Mathrim Cauthon: French translation.

## 

#### Programs/tools used in creation:

- <a href="https://github.com/WeiDUorg/weidu/releases"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, the bigg and Wisp.
- <a href="http://notepad-plus-plus.org/">Notepad++</a>, by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters</a>, by Argent77.
- <a href="https://forums.beamdog.com/discussion/78364/infinity-auto-packager-automatically-generate-and-adds-mod-packages-to-release-when-you-publish-it">Infinity Auto Packager</a>, by AL|EN.

## 

#### Copyrights Information

###### Super Firkraag is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Rastor, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;Rastor.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Version History

#### Version 1.6

- Renamed *setup-Firkraag.tp2* -> *firkraag.tp2* to support AL|EN's "Project Infinity".
- Added missing `REQUIRE_PREDICATE` process to avoid installing the mod in inaccurate games.
- Added component `DESIGNATED` number and "*super_firkraag*" `LABEL`.
- Added missing `HANDLE_CHARSETS` function to convert string entries for EE games.

- Proofread English and French translations.
- Added Polish translation (thanks to SoM, part of CoB Clan).
- Added German translation (from the BiG World Textpack German project).

- Removed useless backup folder.
- Reorganized mod architecture tree: created folders to sort files according to their types and renamed top folder *CScripts* to *firkraag*.

- Updated WeiDU installer to v246.

## 

#### Version 1.5

- Added Russian translation (thanks to the A.E.R.I.E. Team).
- Updated WeiDU installer to v231.

## 

#### Version 1.4

- Added French translation (Once again, thanks to Mathrim Cauthon).

## 

#### Version 1.3

- Fixed a bug that was causing the script to not compile correctly. Thanks Andrew!

## 

#### Version 1.2

- File uses better compression, so downloading speed will be increased.

## 

#### Version 1.1

- Firkraag now uses better spells, he'll no longer kill his own invisible stalker, and his death spell works now.

## 

#### Version 1.0

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>

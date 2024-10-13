---
title: "Reverse Disk Rotation: Using CHDMAN to Enhance Gaming Archives"
date: 2024-10-06T01:40:51.002Z
updated: 2024-10-13T06:44:36.578Z
tags:
  - games
categories:
  - games
description: "This Article Describes Reverse Disk Rotation: Using CHDMAN to Enhance Gaming Archives"
excerpt: "This Article Describes Reverse Disk Rotation: Using CHDMAN to Enhance Gaming Archives"
keywords: Reverse Disk Rot,Disk Archiving,CHDMan Tools,Gaming Backups,Data Preservation,Game Archive,Disk Renovation
thumbnail: https://thmb.techidaily.com/fed92e9eb9a0a5e6e21c5bc280db28f15e68b19782ea8ac6138fc17b8fe856f7.jpg
---

## Reverse Disk Rotation: Using CHDMAN to Enhance Gaming Archives

 If you're collecting ROMs like Pokémon, you surely have noticed that the ones for newer platforms take up a significant chunk of your storage. A single game might require multiple gigabytes of storage. Keep over a dozen, and your ROM collection can quickly expand to many Terabytes. That's where the MAME project's CHDMAN tool can help.

 Does your ROM collection contain arcade games or titles for consoles with optical media, like Sony's PlayStation? CHDMAN can compress them to CHD files that take up a fraction of a ROM's original size.

 What's best is that many emulators support the CHD format. So, you can keep playing your ROMs without extracting or decompressing them. Let's see how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is CHDMAN?

 MAME's Compressed Hunks of Data (CHD) manager, or "CHDMAN" for short, allows you to store the files of a ROM in a single compressed archive. Apart from saving space, this can also simplify the management of multi-file ROMs, like optical media backups consisting of a game's data track and many more audio tracks for its music.

 A key difference compared to typical archives produced by tools like 7-Zip and WinRAR is that CHDMAN's CHD files can be used without requiring decompression.

 The two cons of the CHD format are that CHDMAN is a command line tool that you'll have to use by typing commands in the terminal and that not all emulators support the resulting CHD format. CHDMAN can only compress files with the following extensions:

* CUE & BIN.
* GDI.
* ISO.
* TOC.
* NRG.
* CDR.
* IMG.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100538/7443" target="_top" id="2100538">
  <img src="//a.impactradius-go.com/display-ad/7443-2100538" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Compress Your ISOs With CHDMAN

 CHDMAN is distributed with the MAME emulator. If you already use that, you'll find CHDMAN's executable in MAME's installation directory. If not, download[the latest version of MAME from its official site](https://www.mamedev.org/) and install it on your PC to also get CHDMAN.

 To avoid typing the full path to CHDMAN every time you want to compress a ROM, add MAME's folder to your System Path variable. You can do this by[using environment variables in Windows 10](https://www.makeuseof.com/how-to-use-environment-variables-in-windows-10/) .

 Open a**File Explorer** window (**Windows Key + E**) and, to keep things tidy, create a folder anywhere you wish, within which you'll do all CHDMAN-related file juggling.

 Move the files of the ROM you want to compress to that folder. For this article, we'll use an original PlayStation backup stored in a CUE & BIN file combination.

![A screenshot of a BIN and CUE ROM image from the File Explorer in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/bin-and-cue-in-windows-file-explorer.jpg)

 Run Windows CMD or PowerShell. Then, move to the folder with your game's files with the Change Directory (CD) command:

`cd PATH_TO_FOLDER`

Our command was:

`cd "H:\Emulation\ROMs\PS1\Compress-to-CHD"`

![A screenshot of the Change Directory command in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cd-command-in-cmd.jpg)

To compress your game with CHDMAN to CHD format, use the following:

`chdman.exe createcd -i "ROM_YOU_WANT_TO_COMPRESS.CUE" -o "FILENAME_OF_COMPRESSED.CHD"`

Our command was:

`chdman createcd -i "MUO_PSX.cue" -o "MUO_PSX.chd"  
`

![A screenshot of the command to compress a ROM into CHD format using CHDMAN](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/chdman-createcd-command-in-cmd.jpg)

 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118322/7443" target="_top" id="2118322">
  <img src="//a.impactradius-go.com/display-ad/7443-2118322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118322/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

![DuckStation File Selector set to MAME CHD images](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/duckstation-chd-file-selection-1.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're looking for a CHD-compatible emulator then, luckily some of the most popular emulators support them. Here are a few examples of emulators that allow you to play CHDs:

* MAME.
* DuckStation.
* Beetle PSX.
* PCSX.
* PCSX2.

* DEmul.
* lr-opera.
* Reicast.
* Flycast.
* Redream.
* Genesis Plus GX.
* PicoDrive.

 Because of[how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like[using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105863/7443" target="_top" id="2105863">
  <img src="//a.impactradius-go.com/display-ad/7443-2105863" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105863/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

## More Storage, More Gaming

 Compressing your emulators' ROMs with CHDMAN will give you back a significant amount of storage space. But there's also a major con.

 Freeing up storage space means you can expand your ROM collection further. And that, in turn, translates to even more games in your backlog. With so many games a click away, having a CHDMAN equivalent that could compress and multiply our free time would be great.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-activity-recording.techidaily.com/new-pro-level-screenshot-techniques-with-top-11-tools/"><u>[New] Pro-Level Screenshot Techniques with Top 11 Tools</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-campaign-tactics-for-enhancing-health-awareness-for-2024/"><u>[Updated] Campaign Tactics for Enhancing Health Awareness for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-exclusive-guide-choosing-among-top-9-free-logo-creators-for-2024/"><u>[Updated] Exclusive Guide Choosing Among Top 9 Free Logo Creators for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-fun-in-games-invest-in-high-quality-tech/"><u>Boosting Fun in Games: Invest in High-Quality Tech</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-white-hardware-choices-on-a-tight-budget/"><u>Essential White Hardware Choices on a Tight Budget</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-best-instant-windows-photograph-gazing-tool/"><u>In 2024, Best Instant Windows Photograph Gazing Tool</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-comprehensive-list-of-no-download-online-gif-to-video-converters/"><u>In 2024, Comprehensive List of No-Download Online GIF to Video Converters</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-from-components-to-creativity-designing-your-own-4k-editor-pc/"><u>In 2024, From Components to Creativity Designing Your Own 4K Editor PC</u></a></li>
<li><a href="https://games-able.techidaily.com/mechanical-masterpiece-revealed-razers-hot-swap-widow-v4/"><u>Mechanical Masterpiece Revealed - Razer's Hot-Swap Widow V4</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/snap-tastic-facebooks-fleeting-media/"><u>Snap-Tastic Facebook's Fleeting Media</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-decks-new-frontier-external-memory-expansion/"><u>Steam Deck's New Frontier: External Memory Expansion</u></a></li>
<li><a href="https://games-able.techidaily.com/step-by-step-using-steam-deck-for-pc-gaming-broadcasts/"><u>Step-By-Step: Using Steam Deck for PC Gaming Broadcasts</u></a></li>
<li><a href="https://win-solutions.techidaily.com/stop-the-disruption-solving-xcom-2-game-crash-issues-on-windows-systems/"><u>Stop the Disruption: Solving XCOM 2 Game Crash Issues on Windows Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-asus-rog-ally-docks-of-2024/"><u>The Best ASUS ROG Ally Docks of 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-steam-remote-link-failures/"><u>Troubleshooting Steam Remote Link Failures</u></a></li>
<li><a href="https://games-able.techidaily.com/what-to-check-before-buying-a-gamers-display/"><u>What to Check Before Buying a Gamers Display</u></a></li>
<li><a href="https://win-amazing.techidaily.com/aac-mp3-wav-movavi/"><u>무료 AAC 바이트를 온라인에서 신선한 MP3, WAV 형식으로 변환하는 기술: Movavi 자습광</u></a></li>
</ul></div>


---
title: "ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
date: 2024-07-03T12:02:54.940Z
updated: 2024-07-04T12:02:54.940Z
tags:
  - games
categories:
  - games
description: "This Article Describes ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
excerpt: "This Article Describes ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
keywords: Vintage Game Conservation,Classic Gaming Restoration,Heritage Video Game Storage,Retro Games Maintenance,Preserving Old Video Games,Accessing Antique Games,Saving Vintage Gaming Collections
thumbnail: https://thmb.techidaily.com/91b7cfb4d96e2456602f29985eb790b38dbd8c0fc22d4f4a877755c3058adea9.jpg
---

## ACHDMAN Strategies: Preserving and Accessing Your Vintage Games

 If you're collecting ROMs like Pokémon, you surely have noticed that the ones for newer platforms take up a significant chunk of your storage. A single game might require multiple gigabytes of storage. Keep over a dozen, and your ROM collection can quickly expand to many Terabytes. That's where the MAME project's CHDMAN tool can help.

 Does your ROM collection contain arcade games or titles for consoles with optical media, like Sony's PlayStation? CHDMAN can compress them to CHD files that take up a fraction of a ROM's original size.

 What's best is that many emulators support the CHD format. So, you can keep playing your ROMs without extracting or decompressing them. Let's see how.

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

## How to Compress Your ISOs With CHDMAN

 CHDMAN is distributed with the MAME emulator. If you already use that, you'll find CHDMAN's executable in MAME's installation directory. If not, download [the latest version of MAME from its official site](https://www.mamedev.org/) and install it on your PC to also get CHDMAN.

 To avoid typing the full path to CHDMAN every time you want to compress a ROM, add MAME's folder to your System Path variable. You can do this by [using environment variables in Windows 10](https://www.makeuseof.com/how-to-use-environment-variables-in-windows-10/) .

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

### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

![DuckStation File Selector set to MAME CHD images](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/duckstation-chd-file-selection-1.jpg)

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

 Because of [how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like [using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

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
<li><a href="https://games-able.techidaily.com/excellent-gamer-tracking-apps-review/"><u>Excellent Gamer Tracking Apps Review</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-view-on-gaming-computing-debunking-six-apple-misconceptions/"><u>A New View on Gaming Computing: Debunking Six Apple Misconceptions</u></a></li>
<li><a href="https://games-able.techidaily.com/eas-cost-increase-my-gaming-path-changed/"><u>EA's Cost Increase, My Gaming Path Changed</u></a></li>
<li><a href="https://games-able.techidaily.com/compact-and-sturdy-2024s-finest-holders-for-switch/"><u>Compact and Sturdy: 2024'S Finest Holders for Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-complete-game-displays-in-epics-library/"><u>Ensuring Complete Game Displays in Epic's Library</u></a></li>
<li><a href="https://games-able.techidaily.com/epic-games-unraveling-success-through-helldivers-2/"><u>Epic Games: Unraveling Success Through Helldivers 2</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-to-playnite-on-television/"><u>The Ultimate Guide to Playnite on Television</u></a></li>
<li><a href="https://games-able.techidaily.com/cutting-edge-displays-ifas-finest/"><u>Cutting-Edge Displays - IFA's Finest</u></a></li>
<li><a href="https://games-able.techidaily.com/mmx-200-evaluation-powerful-but-feature-limited/"><u>MMX 200 Evaluation: Powerful but Feature-Limited</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-infinix-smart-8-hd-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Infinix Smart 8 HD Wont Charge | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/new-easy-start-exploring-vectors-world-essentials-and-tools-for-2024/"><u>[New] Easy Start  Exploring Vectors' World - Essentials & Tools for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-quiet-your-screen-three-strategies-to-slow-youtube-videos-down-57-chars/"><u>In 2024, Quiet Your Screen  Three Strategies to Slow YouTube Videos Down (57 Chars)</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ull-vision-media-the-smart-mcn-selection-process/"><u>[New] Full Vision Media  The Smart MCN Selection Process</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-social-media-story-scooper/"><u>[New] Social Media Story Scooper</u></a></li>
<li><a href="https://extra-support.techidaily.com/photoshop-and-beyond-unlocking-visual-potential-with-luts-for-2024/"><u>Photoshop and Beyond  Unlocking Visual Potential with Luts for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/izing-your-youtube-stream-with-wirecast/"><u>Optimizing Your YouTube Stream with WireCast</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-top-rated-free-mpeg-video-joining-software-for-2024/"><u>Updated Top-Rated Free MPEG Video Joining Software for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-realme-10t-5g-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/leveraging-speech-recognition-in-googles-popular-docs-application-for-2024/"><u>Leveraging Speech Recognition in Google's Popular Docs Application for 2024</u></a></li>
</ul></div>

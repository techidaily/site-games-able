---
title: Enhanced Storage Solutions for Classic Gaming with CHDMAN's Wisdom
date: 2024-07-12T03:39:26.668Z
updated: 2024-07-13T03:39:26.668Z
tags:
  - games
categories:
  - games
description: This Article Describes Enhanced Storage Solutions for Classic Gaming with CHDMAN's Wisdom
excerpt: This Article Describes Enhanced Storage Solutions for Classic Gaming with CHDMAN's Wisdom
keywords: Classic Gaming Storage,Enhanced Game Saving,Wisdom in Gaming,CHDMAN Tech Upgrade,Modernized Retro Games,Optimized Digital Archives,CHDMAN's Secure Save
thumbnail: https://thmb.techidaily.com/5102f68d4f6f5865eb613c39e1e5be805ea96bcf031e721bf44a46da711c7234.jpg
---

## Enhanced Storage Solutions for Classic Gaming with CHDMAN's Wisdom

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
<li><a href="https://games-able.techidaily.com/the-role-of-endocannabinoids-in-modulating-immune-responses-and-disease-progression/"><u>The Role of Endocannabinoids in Modulating Immune Responses and Disease Progression</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-6s-apples-new-iphone-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 6s, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/unleash-potential-self-fix-your-xbox-controllers/"><u>Unleash Potential - Self-Fix Your Xbox Controllers</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166740000-jumpstart-savings-with-sonys-midyear-blowout/"><u>Jumpstart Savings with Sony's Midyear Blowout</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-excellence-the-ultimate-guide-to-apple-arcade-games/"><u>Unlock Excellence: The Ultimate Guide to Apple Arcade Games</u></a></li>
<li><a href="https://games-able.techidaily.com/a-critical-eye-on-manipulative-playtime-trailers/"><u>A Critical Eye on Manipulative Playtime Trailers</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-peak-performance-with-our-best-gamers-keyboard-lists/"><u>Unlock Peak Performance with Our Best Gamers' Keyboard Lists</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-apple-iphone-14-pro-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>Unlocking Apple iPhone 14 Pro Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/todays-gamers-meet-retro-classics/"><u>Today's Gamers Meet Retro Classics</u></a></li>
<li><a href="https://games-able.techidaily.com/balancing-act-when-to-invest-in-your-systems-cpugpu/"><u>Balancing Act: When to Invest in Your System's CPU/GPU</u></a></li>
<li><a href="https://games-able.techidaily.com/bridge-the-gap-between-xbox-and-steam-via-glossi/"><u>Bridge the Gap Between Xbox and Steam via GlosSI</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-palworld-everything-you-need-to-know/"><u>What Is Palworld? Everything You Need to Know</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-potential-on-twitch-tips-for-quality-content/"><u>Unlocking Potential on Twitch: Tips for Quality Content</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-mastering-your-tech-skills-unlock-macs-full-screen-recording-power-with-shortcuts/"><u>In 2024, Mastering Your Tech Skills  Unlock Mac's Full Screen Recording Power with Shortcuts</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-devices-into-virtual-arcade-machines-our-4p-emulators/"><u>Transform Your Devices Into Virtual Arcade Machines - Our 4P Emulators</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-editing-excellence-incorporating-timestamps-and-labels/"><u>[New] 2024 Approved  Editing Excellence  Incorporating Timestamps and Labels</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162755876-online-games-under-siege-security-alert/"><u>Online Games Under Siege: Security Alert</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-how-to-blur-a-still-or-moving-part-of-video/"><u>New In 2024, How to Blur a Still or Moving Part of Video</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-cropping-and-styling-tips-for-standout-instagram-videos/"><u>[Updated] In 2024, Cropping and Styling Tips for Standout Instagram Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/action-plan-when-to-fix-when-to-trade-in-your-switch/"><u>Action Plan: When to Fix, When to Trade-In Your Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/bg3-system-guide-specs-and-download-tips/"><u>BG3 System Guide - Specs & Download Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/controlling-snes-games-new-way/"><u>Controlling SNES Games, New Way</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-checklist-for-joining-notable-discords/"><u>The Ultimate Checklist for Joining Notable Discords</u></a></li>
<li><a href="https://games-able.techidaily.com/baffling-board-games-for-brainy-beings/"><u>Baffling Board Games for Brainy Beings</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-the-7-best-video-merging-tools-with-no-watermark-limitations-for-2024/"><u>Updated The 7 Best Video Merging Tools with No Watermark Limitations for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/the-simple-ways-to-prolong-your-nintendo-switchs-life/"><u>The Simple Ways to Prolong Your Nintendo Switch's Life</u></a></li>
<li><a href="https://games-able.techidaily.com/basking-under-blue-skies-ar-games-for-you/"><u>Basking Under Blue Skies - AR Games for You</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-home-entertainment-with-playnite-fullscreen-tv/"><u>Transform Home Entertainment with Playnite Fullscreen TV</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/deciphering-your-youtube-viewership-stats/"><u>Deciphering Your YouTube Viewership Stats</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/perfecting-the-blend-audio-and-visual-synchronization-in-videos/"><u>Perfecting the Blend  Audio and Visual Synchronization in Videos</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-demystifying-jazz-understanding-its-core-concepts-and-styles/"><u>Updated 2024 Approved Demystifying Jazz Understanding Its Core Concepts and Styles</u></a></li>
<li><a href="https://games-able.techidaily.com/connecting-modern-xbox-joysticks-to-windows-systems-140-chars/"><u>Connecting Modern Xbox Joysticks to Windows Systems (140 Chars)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-evaluating-the-storage-power-of-64128gb-units-for-vids/"><u>2024 Approved  Evaluating the Storage Power of 64/128GB Units for Vids</u></a></li>
<li><a href="https://games-able.techidaily.com/celebrate-togetherness-with-shared-steam-games/"><u>Celebrate Togetherness with Shared Steam Games</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-inside-the-craft-of-creating-vr-films/"><u>2024 Approved  Inside The Craft of Creating VR Films</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-streamlight-solutions-best-for-video-illumination/"><u>[New] Streamlight Solutions  Best for Video Illumination</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-guide-to-professional-xbox-recording-tools/"><u>Ultimate Guide to Professional Xbox Recording Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/a-gamers-paradise-top-rated-nintendo-switch-docks-for-the-future/"><u>A Gamer's Paradise: Top-Rated Nintendo Switch Docks for the Future</u></a></li>
</ul></div>

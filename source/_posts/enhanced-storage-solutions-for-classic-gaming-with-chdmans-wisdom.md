---
title: Enhanced Storage Solutions for Classic Gaming with CHDMAN's Wisdom
date: 2024-06-25T13:05:34.143Z
updated: 2024-06-26T13:05:34.143Z
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
<li><a href="https://games-able.techidaily.com/troubleshooting-non-functional-display-drivers-in-win10/"><u>Troubleshooting Non-Functional Display Drivers in Win10</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-the-ultimate-top-tier-nintendo-switch-docks-in-2e2024/"><u>Unveiling the Ultimate: Top-Tier Nintendo Switch Docks in 2E2024</u></a></li>
<li><a href="https://games-able.techidaily.com/4-ai-powered-online-murder-mystery-puzzles-and-games-to-play-detective/"><u>4 AI-Powered Online Murder Mystery Puzzles and Games to Play Detective</u></a></li>
<li><a href="https://games-able.techidaily.com/stop-erratic-scrolling-on-your-mouse/"><u>Stop Erratic Scrolling on Your Mouse</u></a></li>
<li><a href="https://games-able.techidaily.com/the-secret-to-maximum-fun-in-fortnite-on-your-mac/"><u>The Secret to Maximum Fun in Fortnite on Your Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/personalizing-your-ps5-gaming-access-structure/"><u>Personalizing Your PS5 Gaming Access Structure</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-game-with-top-10-pc-picks-google-play/"><u>Elevate Your Game with Top 10 PC Picks (Google Play)</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-the-go-sonys-ps-vita/"><u>Game on the Go: Sony's PS Vita</u></a></li>
<li><a href="https://games-able.techidaily.com/bridge-pc-and-steam-deck-remote-game-casting-basics/"><u>Bridge PC and Steam Deck: Remote Game Casting Basics</u></a></li>
<li><a href="https://screen-capture.techidaily.com/the-ultimate-guide-to-automated-mac-lecture-recording/"><u>The Ultimate Guide to Automated Mac Lecture Recording</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-apps-and-online-tools-to-track-poco-m6-pro-4g-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Poco M6 Pro 4G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-the-ultimate-plan-to-grow-your-subscriber-base/"><u>2024 Approved  The Ultimate Plan to Grow Your Subscriber Base</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-easycapture-pro-free-for-windows-10/"><u>In 2024, EasyCapture Pro - Free for Windows 10</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-samsung-galaxy-s23plus-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Samsung Galaxy S23+ to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/a-comprehensive-guide-to-producing-engaging-subtitles-and-captions-for-fb-for-2024/"><u>A Comprehensive Guide to Producing Engaging Subtitles and Captions for FB for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-essential-snapchat-filters-20-must-have-techniques-for-2024/"><u>[Updated] Essential Snapchat Filters  20 Must-Have Techniques for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-how-to-make-an-ootd-tiktok-video-on-mac/"><u>[Updated] How to Make an OOTD Tiktok Video on Mac</u></a></li>
<li><a href="https://change-location.techidaily.com/list-of-pokemon-go-joysticks-on-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>List of Pokémon Go Joysticks On Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-elite-software-selection-top-editors-for-webcams/"><u>In 2024, Elite Software Selection  Top Editors for Webcams</u></a></li>
</ul></div>

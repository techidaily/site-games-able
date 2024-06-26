---
title: "Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN"
date: 2024-06-25T13:03:14.474Z
updated: 2024-06-26T13:03:14.474Z
tags:
  - games
categories:
  - games
description: "This Article Describes Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN"
excerpt: "This Article Describes Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN"
keywords: Chdman Game Optimization,Retro Game ISO Cut,Reduce Video Game Size,Squeeze Game Performance,CHDMAN ISO Editing,Low-Memory Gaming Techniques,Efficient Retro Graphics
thumbnail: https://thmb.techidaily.com/4dbf33f37ff64fa1cd0b3b86eb483d2b61e4dcfaa2f3492f28ea818842097e14.jpg
---

## Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN

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
<li><a href="https://games-able.techidaily.com/ioss-gaming-extravaganza-why-i-subscribe-to-apple-arcade/"><u>IOS's Gaming Extravaganza: Why I Subscribe to Apple Arcade</u></a></li>
<li><a href="https://games-able.techidaily.com/uncovering-users-on-steam-efficiently/"><u>Uncovering Users on Steam Efficiently</u></a></li>
<li><a href="https://games-able.techidaily.com/keep-google-chromes-running-fb-game-troubleshooting-guide/"><u>Keep Google Chromes Running: FB Game Troubleshooting Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/boost-brag-and-beat-the-odds-essential-achievement-websites/"><u>Boost, Brag & Beat The Odds: Essential Achievement Websites</u></a></li>
<li><a href="https://games-able.techidaily.com/the-journey-to-reinventing-yourself-on-riot-games-platforms/"><u>The Journey to Reinventing Yourself on Riot Games Platforms</u></a></li>
<li><a href="https://games-able.techidaily.com/perfect-your-panel-management-u-ban-and-block-users-on-twitch/"><u>Perfect Your Panel Management: U-Ban & Block Users on Twitch</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-why-gamer-friendly-monitors-are-overrated/"><u>Exploring Why Gamer-Friendly Monitors Are Overrated</u></a></li>
<li><a href="https://games-able.techidaily.com/are-higher-rankings-truly-a-benchmark-for-success-on-steam/"><u>Are Higher Rankings Truly a Benchmark for Success on Steam?</u></a></li>
<li><a href="https://games-able.techidaily.com/assessing-the-importance-of-speedy-resume-on-xbox/"><u>Assessing the Importance of Speedy Resume on Xbox</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-clear-out-your-discord-server-pcandroid/"><u>In 2024, Clear Out Your Discord Server (PC/Android)</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-remove-youtube-commercials-in-a-click-techniques-for-every-browser/"><u>[New] Remove YouTube Commercials in a Click - Techniques for Every Browser</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-unleash-your-fame-potential-hot-screen-names-on-discord/"><u>[Updated] Unleash Your Fame Potential  Hot Screen Names on Discord</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-immerse-in-virtual-reality-top-10-youtube-videos/"><u>In 2024, Immerse in Virtual Reality  Top 10 YouTube Videos</u></a></li>
<li><a href="https://location-fake.techidaily.com/10-best-fake-gps-location-spoofers-for-realme-11-5g-drfone-by-drfone-virtual-android/"><u>10 Best Fake GPS Location Spoofers for Realme 11 5G | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-comprehensible-techniques-for-effective-classroom-recordings-on-mac/"><u>In 2024, Comprehensible Techniques for Effective Classroom Recordings on Mac</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-excellent-envoys-top-laptops-to-edit-videos-in-4k/"><u>In 2024, Excellent Envoys  Top Laptops to Edit Videos in 4K</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/mastering-your-content-on-facebook-after-algorithms-change/"><u>Mastering Your Content on Facebook After Algorithms Change</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-10-top-ranked-offline-ios-gaming-hacks-you-need/"><u>[Updated] 2024 Approved  10 Top-Ranked Offline iOS Gaming Hacks You Need</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-the-true-story-of-youtube-earnings-and-viewer-volume-requirements/"><u>[Updated] In 2024, The True Story of YouTube Earnings and Viewer Volume Requirements</u></a></li>
</ul></div>

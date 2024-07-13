---
title: "Preserving Games on Disk: Efficient CHDMAN ISO Compression Tips"
date: 2024-07-12T03:14:09.703Z
updated: 2024-07-13T03:14:09.703Z
tags:
  - games
categories:
  - games
description: "This Article Describes Preserving Games on Disk: Efficient CHDMAN ISO Compression Tips"
excerpt: "This Article Describes Preserving Games on Disk: Efficient CHDMAN ISO Compression Tips"
keywords: Game Disk Preservation,Efficient CHDMAN Compress,ISO Compression Techniques,Disk Space Saving Methods,Chdman ISO Optimization,Data Compression Tips,Games Disk Management
thumbnail: https://thmb.techidaily.com/c9771ef48189c5657c46cc55dbf30e5b22c5c13c4b41b02a192204985e15f302.jpg
---

## Preserving Games on Disk: Efficient CHDMAN ISO Compression Tips

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
<li><a href="https://games-able.techidaily.com/decoding-dxvk-and-its-benefits-for-wingaming-enthusiasts/"><u>Decoding DXVK and Its Benefits for WinGaming Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/the-xbox-series-ss-digital-media-focus/"><u>The Xbox Series S's Digital Media Focus</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-essential-specifications-for-gaming-devices/"><u>Discovering Essential Specifications for Gaming Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/soundproofing-your-in-game-chat-on-series-sx/"><u>Soundproofing Your In-Game Chat on Series S/X</u></a></li>
<li><a href="https://games-able.techidaily.com/unmasking-game-meta-interpretation-and-adherence/"><u>Unmasking Game 'Meta': Interpretation & Adherence</u></a></li>
<li><a href="https://games-able.techidaily.com/the-essential-guide-to-preventing-and-resolving-gaming-system-errors/"><u>The Essential Guide to Preventing and Resolving Gaming System Errors</u></a></li>
<li><a href="https://games-able.techidaily.com/the-reality-check-unraveling-six-fallacies-of-mac-gaming/"><u>The Reality Check: Unraveling Six Fallacies of Mac Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/the-journey-to-reinventing-yourself-on-riot-games-platforms/"><u>The Journey to Reinventing Yourself on Riot Games Platforms</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-precision-recording-perfecting-video-captures-on-your-android-phone/"><u>[New] 2024 Approved  Precision Recording  Perfecting Video Captures on Your Android Phone</u></a></li>
<li><a href="https://games-able.techidaily.com/synchronize-devices-maximize-potential-the-art-of-using-barriers-on-steam-decks/"><u>Synchronize Devices, Maximize Potential: The Art of Using Barriers on Steam Decks</u></a></li>
<li><a href="https://games-able.techidaily.com/safeguarding-games-how-to-activate-screen-lock-on-switch-console/"><u>Safeguarding Games: How to Activate Screen Lock on Switch Console</u></a></li>
<li><a href="https://games-able.techidaily.com/sonys-summer-offering-a-hitter-list-of-steals/"><u>Sony’s Summer Offering: A Hitter List of Steals</u></a></li>
<li><a href="https://games-able.techidaily.com/the-premier-7-in-mobile-mmo-world/"><u>The Premier 7 in Mobile MMO World</u></a></li>
<li><a href="https://games-able.techidaily.com/tech-evolved-tecnos-lighter-more-vibrant-gadgets-at-ifa/"><u>Tech Evolved: Tecno's Lighter, More Vibrant Gadgets at IFA</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-adhering-to-twitters-video-dimension-standards/"><u>[Updated] 2024 Approved  Adhering to Twitter's Video Dimension Standards</u></a></li>
<li><a href="https://games-able.techidaily.com/why-gamers-choose-edge-its-unmatched-browsing-skills/"><u>Why Gamers Choose Edge: Its Unmatched Browsing Skills</u></a></li>
<li><a href="https://games-able.techidaily.com/which-gpu-model-is-best-for-you-aib-vs-nvidia-fe-edition/"><u>Which GPU Model Is Best for You? AIB Vs Nvidia FE Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/cutting-cost-not-quality-in-your-ps5-gaming-package/"><u>Cutting Cost, Not Quality in Your PS5 Gaming Package</u></a></li>
<li><a href="https://games-able.techidaily.com/virtual-battles-increasing-hostility-online/"><u>Virtual Battles: Increasing Hostility Online</u></a></li>
<li><a href="https://games-able.techidaily.com/top-ranked-ps5-flash-drives/"><u>Top-Ranked PS5 Flash Drives</u></a></li>
<li><a href="https://games-able.techidaily.com/top-level-165hz-visuals-for-gamers/"><u>Top-Level 165Hz Visuals for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/simplified-pathways-to-restart-steam/"><u>Simplified Pathways to Restart Steam</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-create-stunning-video-invites-best-apps-for-ios-and-android/"><u>New In 2024, Create Stunning Video Invites Best Apps for iOS and Android</u></a></li>
<li><a href="https://games-able.techidaily.com/4-common-gpu-problems-and-how-to-troubleshoot-them/"><u>4 Common GPU Problems and How to Troubleshoot Them</u></a></li>
<li><a href="https://games-able.techidaily.com/best-picks-unbeatable-xbox-recording-gear/"><u>Best Picks: Unbeatable Xbox Recording Gear</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-the-frustration-of-game-freezes-by-overcoming-10-common-problems/"><u>Avoid the Frustration of Game Freezes by Overcoming 10 Common Problems</u></a></li>
<li><a href="https://games-able.techidaily.com/subscription-stack-up-xbox-vs-psplus-in-depth-comparison/"><u>Subscription Stack-Up: Xbox Vs. PS+ In-Depth Comparison</u></a></li>
<li><a href="https://howto.techidaily.com/why-is-my-oppo-f23-5g-offline-troubleshooting-guide-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Is My Oppo F23 5G Offline? Troubleshooting Guide | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-itel-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Itel FRP In 3 Different Ways</u></a></li>
<li><a href="https://games-able.techidaily.com/amd-vs-nvidia-does-fsr-3-edge-over-dlss-35-performance-gains/"><u>AMD Vs. NVIDIA: Does FSR 3 Edge Over DLSS 3.5 Performance Gains?</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-vs-gog-consumer-benefits-explored-in-depth/"><u>Steam vs GOG: Consumer Benefits Explored in Depth</u></a></li>
<li><a href="https://games-able.techidaily.com/strengthen-your-cognitive-muscles-with-nyts-exciting-new-brain-teaser-strands/"><u>Strengthen Your Cognitive Muscles With NYT’s Exciting, New Brain Teaser: Strands</u></a></li>
<li><a href="https://games-able.techidaily.com/why-xbox-series-s-ignores-traditional-game-formats/"><u>Why Xbox Series S Ignores Traditional Game Formats</u></a></li>
<li><a href="https://fox-http.techidaily.com/masterful-zoom-techniques-simple-iphone-solutions-for-2024/"><u>Masterful Zoom Techniques  Simple iPhone Solutions for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-eradicate-white-blankness/"><u>Quick Eradicate White Blankness</u></a></li>
<li><a href="https://games-able.techidaily.com/discover-the-ultimate-gaming-hacks-for-mac-enthusiasts-5-tips/"><u>Discover the Ultimate Gaming Hacks for Mac Enthusiasts (5 Tips)</u></a></li>
<li><a href="https://games-able.techidaily.com/create-a-vibrant-gaming-community-on-discord-through-xbox-streams/"><u>Create a Vibrant Gaming Community on Discord Through Xbox Streams</u></a></li>
<li><a href="https://games-able.techidaily.com/astral-architect-sifting-through-gaming-models/"><u>Astral Architect: Sifting Through Gaming Models</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-best-mobile-video-editing-for-tiktok-stars/"><u>[New] 2024 Approved  Best Mobile Video Editing for TikTok Stars</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/discovering-realistic-insectoid-noise-samples/"><u>Discovering Realistic Insectoid Noise Samples</u></a></li>
<li><a href="https://games-able.techidaily.com/setting-your-preferred-steam-language/"><u>Setting Your Preferred Steam Language</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/the-video-polisher-refine-your-clips-into-stunning-works-of-art-for-2024/"><u>The Video Polisher Refine Your Clips Into Stunning Works of Art for 2024</u></a></li>
</ul></div>

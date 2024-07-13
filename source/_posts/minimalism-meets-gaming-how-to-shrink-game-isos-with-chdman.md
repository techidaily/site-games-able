---
title: "Minimalism Meets Gaming: How to Shrink Game ISOs with CHDMAN"
date: 2024-07-12T03:29:27.509Z
updated: 2024-07-13T03:29:27.509Z
tags:
  - games
categories:
  - games
description: "This Article Describes Minimalism Meets Gaming: How to Shrink Game ISOs with CHDMAN"
excerpt: "This Article Describes Minimalism Meets Gaming: How to Shrink Game ISOs with CHDMAN"
keywords: Minimalistic Gaming Tips,Reduce Games ISO Size,CHDMAN for Games,Optimize Game Files,Shrink Game Archives,Efficient File Compression,Streamlined Gaming Experience
thumbnail: https://thmb.techidaily.com/8bc720ee0adbf09ae88a648a38e027832e102c5d3884a2078035ea55eb60772c.jpg
---

## Minimalism Meets Gaming: How to Shrink Game ISOs with CHDMAN

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-ultimate-unlimited-fb-photomovie-builder/"><u>[New] In 2024, Ultimate Unlimited FB Photo/Movie Builder</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-vivo-y78plus-frp-by-drfone-android/"><u>The Updated Method to Bypass Vivo Y78+ FRP</u></a></li>
<li><a href="https://games-able.techidaily.com/joining-playstation-and-windows-the-ps5-controller-tutorial/"><u>Joining PlayStation and Windows: The PS5 Controller Tutorial</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-revolutionize-your-content-10-top-rated-animated-text-tools/"><u>2024 Approved Revolutionize Your Content 10 Top-Rated Animated Text Tools</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-streamlining-post-production-mastering-the-green-screen-process-kinemaster/"><u>[Updated] Streamlining Post-Production  Mastering the Green Screen Process (KineMaster)</u></a></li>
<li><a href="https://games-able.techidaily.com/digital-puzzles-navigating-through-the-good-and-bad-aspects/"><u>Digital Puzzles: Navigating Through the Good & Bad Aspects</u></a></li>
<li><a href="https://games-able.techidaily.com/insights-into-xbox-casing/"><u>Insights Into Xbox Casing</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-top-10-windows-11-webcam-capturers-for-2024/"><u>[New] Top 10 Windows 11 Webcam Capturers for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-compelling-elements-in-game-design/"><u>Mastering Compelling Elements in Game Design</u></a></li>
<li><a href="https://extra-support.techidaily.com/make-every-podcast-session-count-with-these-15-powerful-activities-for-2024/"><u>Make Every Podcast Session Count with These 15 Powerful Activities for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-mobile-mmo-titles-your-gameplay-guide/"><u>Essential Mobile MMO Titles: Your Gameplay Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-the-latest-in-video-capturing-apeaksoft-2023-edition-analysis/"><u>[Updated] 2024 Approved  The Latest in Video Capturing  Apeaksoft 2023 Edition Analysis</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-reactivate-steams-inaccessible-network-servers/"><u>How To Reactivate Steam's Inaccessible Network Servers</u></a></li>
<li><a href="https://games-able.techidaily.com/diy-repair-the-ultimate-xbox-joystick-guide-for-gamers/"><u>DIY Repair - The Ultimate Xbox Joystick Guide for Gamers</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-the-easy-way-to-remove-vocals-from-an-audio-track-in-audacity/"><u>Updated 2024 Approved The Easy Way to Remove Vocals From an Audio Track in Audacity</u></a></li>
<li><a href="https://games-able.techidaily.com/visual-enhancements-for-gamers-top-144hz-widescreens/"><u>Visual Enhancements for Gamers: Top 144Hz Widescreens</u></a></li>
<li><a href="https://games-able.techidaily.com/join-the-fallout-saga-beyond-the-screen-adventures/"><u>Join the Fallout Saga Beyond The Screen Adventures</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-s-no-planned-discs-despite-patent/"><u>Xbox S: No Planned Discs Despite Patent?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfect-every-frame-windows-11-and-storyremix-combo-guide-to-video-editing-for-2024/"><u>Perfect Every Frame  Windows 11 & StoryRemix Combo Guide to Video Editing for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-xboxs-enforcement-strike-system/"><u>What Is Xbox’s Enforcement Strike System?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-playtime-to-profits-ryan-kajis-youtube-cash-crusade/"><u>In 2024, From Playtime to Profits  Ryan Kaji's YouTube Cash Crusade</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-new-gameplay-top-6-fresh-online-chess-adventures/"><u>Dive Into New Gameplay: Top 6 Fresh Online Chess Adventures</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-learn-to-keep-unwanted-suggestions-away-from-ig/"><u>[New] 2024 Approved  Learn to Keep Unwanted Suggestions Away From IG</u></a></li>
<li><a href="https://games-able.techidaily.com/bright-future-leading-leds-of-the-year/"><u>Bright Future: Leading LEDs of the Year</u></a></li>
<li><a href="https://games-able.techidaily.com/advantages-transitioning-console-players-to-pc-gaming/"><u>Advantages: Transitioning Console Players to PC Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-ps5-nine-key-innovations-to-explore/"><u>Boosting PS5: Nine Key Innovations to Explore</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-resolving-4-frequent-gpu-issues/"><u>Mastering the Art of Resolving 4 Frequent GPU Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/boost-your-phone-turn-it-into-an-all-in-one-game-system/"><u>Boost Your Phone: Turn It Into an All-in-One Game System</u></a></li>
<li><a href="https://games-able.techidaily.com/batocera-vs-retropie-the-best-rpi-game-platform-debated/"><u>Batocera Vs. RetroPie: The Best RPi Game Platform Debated</u></a></li>
<li><a href="https://games-able.techidaily.com/opera-gx-vs-edge-which-is-superior-in-the-online-gaming-arena/"><u>Opera GX vs Edge: Which Is Superior in the Online Gaming Arena?</u></a></li>
<li><a href="https://games-able.techidaily.com/invest-in-entertainment-smart-money-moves-with-xbox/"><u>Invest in Entertainment: Smart Money Moves with Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/get-ready-for-revolutionary-hardware-at-the-biggest-tech-event/"><u>Get Ready for Revolutionary Hardware at the Biggest Tech Event</u></a></li>
<li><a href="https://games-able.techidaily.com/considering-an-immediate-switch-from-gtx-to-the-next-gen-rtx/"><u>Considering an Immediate Switch: From GTX to the Next Gen RTX?</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-seamless-scratching-for-chrome-devices/"><u>[New] Seamless Scratching for Chrome Devices</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-top-10-roguelike-or-roguelite-games/"><u>[Updated] Top 10 Roguelike or Roguelite Games</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-special-features-virtual-location-on-samsung-galaxy-a15-5g-drfone-by-drfone-virtual-android/"><u>How To Use Special Features - Virtual Location On Samsung Galaxy A15 5G? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/fixes-for-the-droopy-effect-in-monitors/"><u>Fixes for the 'Droopy' Effect in Monitors</u></a></li>
<li><a href="https://games-able.techidaily.com/console-subscription-showdown-xbox-game-pass-vs-playstation-plus/"><u>Console Subscription Showdown: Xbox Game Pass Vs. PlayStation Plus</u></a></li>
<li><a href="https://games-able.techidaily.com/gamers-delight-keychron-meets-lemokey-l3/"><u>Gamer's Delight: Keychron Meets Lemokey L3</u></a></li>
</ul></div>

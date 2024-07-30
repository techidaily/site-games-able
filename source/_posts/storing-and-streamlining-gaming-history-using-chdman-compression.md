---
title: Storing and Streamlining Gaming History Using CHDMAN Compression
date: 2024-07-29T05:49:44.560Z
updated: 2024-07-30T05:49:44.560Z
tags:
  - games
categories:
  - games
description: This Article Describes Storing and Streamlining Gaming History Using CHDMAN Compression
excerpt: This Article Describes Storing and Streamlining Gaming History Using CHDMAN Compression
keywords: Gaming Archive Storage,CHDMAN Data Compression,Game History Streamlining,Digital Gaming Archives,CHDMAN Tech for Games,Efficient Game Archiving,Compressing Game Records
thumbnail: https://thmb.techidaily.com/13887af25c31ebc0af7fa01bee84ac625b343ea776763c2dea469f5e646eb4f7.png
---

## Storing and Streamlining Gaming History Using CHDMAN Compression

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

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot of a BIN and CUE ROM image from the File Explorer in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/bin-and-cue-in-windows-file-explorer.jpg)

 Run Windows CMD or PowerShell. Then, move to the folder with your game's files with the Change Directory (CD) command:

`cd PATH_TO_FOLDER`

Our command was:

`cd "H:\Emulation\ROMs\PS1\Compress-to-CHD"`

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-vanguards-choice-of-top-12-high-tech-action-cams-with-locators/"><u>[New] 2024 Approved  Vanguard's Choice of Top 12 High-Tech Action Cams With Locators</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-boosting-zoom-clarity-the-guide-to-using-filters-wisely-for-2024/"><u>[New] Boosting Zoom Clarity  The Guide to Using Filters Wisely for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-comprehensive-guide-to-youtube-video-captioning/"><u>[New] In 2024, Comprehensive Guide to YouTube Video Captioning</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-seamless-setup-swift-sharing-the-essential-guide-to-ifunny-apps/"><u>[New] In 2024, Seamless Setup, Swift Sharing  The Essential Guide to iFunny Apps</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-depth-analysis-the-essence-of-the-google-podcast-application/"><u>2024 Approved  In-Depth Analysis  The Essence of the Google Podcast Application</u></a></li>
<li><a href="https://games-able.techidaily.com/achieve-every-milestone-the-complete-guide-to-steam-awards/"><u>Achieve Every Milestone: The Complete Guide to Steam Awards</u></a></li>
<li><a href="https://games-able.techidaily.com/apples-impact-on-upcoming-pc-game-industry/"><u>Apple's Impact on Upcoming PC Game Industry?</u></a></li>
<li><a href="https://games-able.techidaily.com/ascertaining-maximum-vram-for-your-device/"><u>Ascertaining Maximum VRAM for Your Device</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cant-play-mp4-files-on-xiaomi-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can't play MP4 files on Xiaomi</u></a></li>
<li><a href="https://games-able.techidaily.com/chat-and-builds-top-5-ways-friends-can-join-forces-in-mc/"><u>Chat & Builds: Top 5 Ways Friends Can Join Forces in MC</u></a></li>
<li><a href="https://games-able.techidaily.com/console-countdown-who-wins-in-the-ps5-vs-xbox-series-x/"><u>Console Countdown: Who Wins in the PS5 Vs. Xbox Series X?</u></a></li>
<li><a href="https://games-able.techidaily.com/console-wars-psplus-versus-xbox-game-pass/"><u>Console Wars: PS+ Versus Xbox Game Pass</u></a></li>
<li><a href="https://games-able.techidaily.com/cross-platform-use-for-ps5-with-ps4/"><u>Cross-Platform Use for PS5 with PS4?</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-hidden-gems-indie-game-search-tips/"><u>Discovering Hidden Gems: Indie Game Search Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-ios-delights-join-apple-arcade-enthusiast-club/"><u>Dive Into iOS Delights: Join Apple Arcade Enthusiast Club</u></a></li>
<li><a href="https://location-social.techidaily.com/does-lava-blaze-2-pro-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Lava Blaze 2 Pro Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/engaging-kids-in-protected-steam-based-play/"><u>Engaging Kids in Protected Steam-Based Play</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-fun-practical-uses-for-games-trendy-tech/"><u>Enhancing Fun: Practical Uses for Games' Trendy Tech</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-typing-experience-on-steam-deck/"><u>Enhancing Typing Experience on Steam Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/expertly-designed-charging-hubs-compatible-with-sony-console/"><u>Expertly Designed Charging Hubs: Compatible with Sony Console</u></a></li>
<li><a href="https://extra-hints.techidaily.com/giggle-gang-exploring-the-best-memetic-apps/"><u>Giggle Gang  Exploring the Best Memetic Apps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-oppo-a59-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-decoding-sonys-screenshot-system-an-in-depth-look-at-ps4-recording/"><u>In 2024, Decoding Sony's Screenshot System  An In-Depth Look at PS4 Recording</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-picture-perfect-best-apps-for-framing-your-memories/"><u>In 2024, Picture Perfect  Best Apps for Framing Your Memories</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-tapping-into-traditional-hymns-downloads-and-editing-guide/"><u>In 2024, Tapping Into Traditional Hymns  Downloads & Editing Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-ultimate-guide-to-instagram-desktop-video-upload/"><u>In 2024, The Ultimate Guide to Instagram Desktop Video Upload</u></a></li>
<li><a href="https://games-able.techidaily.com/joint-adventures-await-uniting-your-epic-and-steam-life/"><u>Joint Adventures Await: Uniting Your Epic and Steam Life</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-consoles-capabilities-using-a-laptop-as-monitor/"><u>Maximize Your Console's Capabilities Using a Laptop as Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/reviving-your-dormant-xbox-controller-on-windows/"><u>Reviving Your Dormant Xbox Controller on Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/setting-up-facebook-live-your-roku-route/"><u>Setting Up Facebook LIVE  Your Roku Route</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-z50-ultra-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Z50 Ultra</u></a></li>
<li><a href="https://games-able.techidaily.com/smart-cooling-tech-top-choices-for-a-steam-deck-lover/"><u>Smart Cooling Tech: Top Choices for a Steam Deck Lover</u></a></li>
<li><a href="https://games-able.techidaily.com/steering-clear-of-signal-shadows-on-your-pokemon-go-quest/"><u>Steering Clear of Signal Shadows on Your Pokémon Go Quest</u></a></li>
<li><a href="https://games-able.techidaily.com/strategic-use-of-reset-button-on-sonys-ps5-remote/"><u>Strategic Use of Reset Button on Sony's PS5 Remote</u></a></li>
<li><a href="https://games-able.techidaily.com/taking-gameplay-to-the-next-level-with-tech/"><u>Taking Gameplay to the Next Level with Tech</u></a></li>
</ul></div>

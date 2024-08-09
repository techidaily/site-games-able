---
title: "Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN"
date: 2024-08-08T09:07:57.368Z
updated: 2024-08-09T09:07:57.368Z
tags:
  - games
categories:
  - games
description: "This Article Describes Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN"
excerpt: "This Article Describes Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN"
keywords: Game Preservation,Balancing Gamers' Needs,Authentic Gaming Experience,Efficient Game Storage,CHDMAN Methods,Original Games Retention,Efficiency in Gaming
thumbnail: https://thmb.techidaily.com/533486c883f0e15f79a205d8fe00d7b629c80c76eca7c3b378cb3f9eeb4c0bbe.jpg
---

## Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN

 If you're collecting ROMs like Pokémon, you surely have noticed that the ones for newer platforms take up a significant chunk of your storage. A single game might require multiple gigabytes of storage. Keep over a dozen, and your ROM collection can quickly expand to many Terabytes. That's where the MAME project's CHDMAN tool can help.

 Does your ROM collection contain arcade games or titles for consoles with optical media, like Sony's PlayStation? CHDMAN can compress them to CHD files that take up a fraction of a ROM's original size.

 What's best is that many emulators support the CHD format. So, you can keep playing your ROMs without extracting or decompressing them. Let's see how.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
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
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
![A screenshot of a BIN and CUE ROM image from the File Explorer in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/bin-and-cue-in-windows-file-explorer.jpg)

 Run Windows CMD or PowerShell. Then, move to the folder with your game's files with the Change Directory (CD) command:

`cd PATH_TO_FOLDER`

Our command was:

`cd "H:\Emulation\ROMs\PS1\Compress-to-CHD"`

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
![A screenshot of the Change Directory command in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cd-command-in-cmd.jpg)

To compress your game with CHDMAN to CHD format, use the following:

`chdman.exe createcd -i "ROM_YOU_WANT_TO_COMPRESS.CUE" -o "FILENAME_OF_COMPRESSED.CHD"`

Our command was:

`chdman createcd -i "MUO_PSX.cue" -o "MUO_PSX.chd"  
`

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot of the command to compress a ROM into CHD format using CHDMAN](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/chdman-createcd-command-in-cmd.jpg)

 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
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
<li><a href="https://screen-capture.techidaily.com/new-decoding-the-new-apeaksoft-screenscape-expert-analysis/"><u>[New] Decoding the New Apeaksoft Screenscape  Expert Analysis</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitters-mandated-video-dimensions-aspect-ratio-noted/"><u>[New] In 2024, Twitter's Mandated Video Dimensions (Aspect Ratio Noted)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-pixelpilot-video-snapshot/"><u>[New] PixelPilot Video Snapshot</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-step-into-the-spotlight-on-instagram-with-these-tricks/"><u>[New] Step Into the Spotlight on Instagram with These Tricks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-addressing-missing-image-display-in-youtubes-shorts/"><u>[Updated] 2024 Approved  Addressing Missing Image Display in YouTubes Shorts</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-achieve-peak-performance-enhancing-gameplay-using-switch-pro-controller-in-steam-for-2024/"><u>[Updated] Achieve Peak Performance  Enhancing Gameplay Using Switch Pro Controller in Steam for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-google-meet-for-non-paying-professionals-complete-insights-and-tips-for-2024/"><u>[Updated] Google Meet for Non-Paying Professionals  Complete Insights and Tips for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/480plus-fast-response-display-innocns-pick/"><u>$480+ Fast Response Display - InnoCN's Pick</u></a></li>
<li><a href="https://games-able.techidaily.com/10-tips-to-sharpen-your-monitor-buying-skills/"><u>10 Tips to Sharpen Your Monitor Buying Skills</u></a></li>
<li><a href="https://games-able.techidaily.com/20-rapid-and-simple-mobile-games-for-quick-entertainment-on-iosandroid/"><u>20 Rapid & Simple Mobile Games for Quick Entertainment on iOS/Android</u></a></li>
<li><a href="https://games-able.techidaily.com/20-ways-to-improve-gaming-performance-on-your-laptop/"><u>20 Ways to Improve Gaming Performance on Your Laptop</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-timing-your-insta-shots-for-maximum-impact/"><u>2024 Approved  Timing Your Insta Shots for Maximum Impact</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-transform-your-tech-for-successful-social-media-livestreams/"><u>2024 Approved  Transform Your Tech for Successful Social Media Livestreams</u></a></li>
<li><a href="https://games-able.techidaily.com/4-ways-to-play-adobe-flash-games-without-flash/"><u>4 Ways to Play Adobe Flash Games Without Flash</u></a></li>
<li><a href="https://games-able.techidaily.com/5-missteps-that-thwart-gamefi-adoption-by-enthusiasts/"><u>5 Missteps That Thwart GameFi Adoption by Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/5-reasons-why-gamefi-fails-to-win-gamers-trust/"><u>5 Reasons Why GameFi Fails to Win Gamers' Trust</u></a></li>
<li><a href="https://games-able.techidaily.com/5-tips-to-get-the-best-entertainment-experience-from-your-ps5/"><u>5 Tips to Get the Best Entertainment Experience From Your PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/a-lifeline-to-unparalleled-indie-gaming-experiences-on-itchio/"><u>A Lifeline to Unparalleled Indie Gaming Experiences on Itch.io</u></a></li>
<li><a href="https://games-able.techidaily.com/access-advantages-analysis-game-pass-versus-playstation-essentials/"><u>Access Advantages Analysis: Game Pass Versus PlayStation Essentials</u></a></li>
<li><a href="https://games-able.techidaily.com/accessing-high-end-graphics-for-fortnite-on-your-smartphone/"><u>Accessing High-End Graphics for Fortnite on Your Smartphone</u></a></li>
<li><a href="https://games-able.techidaily.com/achieving-optimal-ps5-security-through-passcode-settings/"><u>Achieving Optimal PS5 Security Through Passcode Settings</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-gamingview-pixeledge-display-27m2v/"><u>Affordable GamingView: PixelEdge Display 27M2V</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-high-refresh-rate-monitors-gaming-edition/"><u>Affordable High Refresh Rate Monitors: Gaming Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/are-customizable-rgb-keyboards-justified-for-players/"><u>Are Customizable RGB Keyboards Justified for Players?</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-crash-landings-fixing-windows-based-epic-games-problems/"><u>Avoid Crash Landings: Fixing Windows-Based Epic Games Problems</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-stability-issues-install-updated-nvidia-graphics-driver-today/"><u>Avoid Stability Issues - Install Updated Nvidia Graphics Driver Today.</u></a></li>
<li><a href="https://win-answers.techidaily.com/banishing-the-dark-your-guide-to-fixing-the-epic-games-launchers-black-screen/"><u>Banishing the Dark: Your Guide to Fixing the Epic Games Launcher's Black Screen</u></a></li>
<li><a href="https://games-able.techidaily.com/bargain-hunting-in-steam-finding-high-quality-games-for-zilch/"><u>Bargain Hunting in Steam: Finding High-Quality Games for Zilch</u></a></li>
<li><a href="https://games-able.techidaily.com/before-you-buy-think-these-6-things-through/"><u>Before You Buy, Think These 6 Things Through</u></a></li>
<li><a href="https://games-able.techidaily.com/best-5-gamers-buys-old-school-handheld-delights/"><u>Best 5 Gamers' Buys: Old-School Handheld Delights</u></a></li>
<li><a href="https://games-able.techidaily.com/best-mac-games-compatible-console-emulators/"><u>Best Mac Games: Compatible Console Emulators</u></a></li>
<li><a href="https://games-able.techidaily.com/best-practices-managing-gpu-thermal-output/"><u>Best Practices: Managing GPU Thermal Output</u></a></li>
<li><a href="https://extra-information.techidaily.com/capturing-photos-from-moving-frames-on-windows-11/"><u>Capturing Photos From Moving Frames on Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/complete-guide-installing-epson-v500-scanprint-utility-driver/"><u>Complete Guide: Installing Epson V500 Scan/Print Utility Driver</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-electronically-sign-a-dot-file-using-digisigner-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Electronically Sign a .dot file Using DigiSigner</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-vivo-t2-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Vivo T2 5G? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-xiaomi-redmi-k70-pro-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Xiaomi Redmi K70 Pro online without jailbreak</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-boosting-game-speed-optimizing-minecrafts-ram-usage/"><u>In 2024, Boosting Game Speed  Optimizing Minecraft's RAM Usage</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-complete-exploration-of-morphvox-technology-for-voice-transformation/"><u>In 2024, Complete Exploration of MorphVOX Technology for Voice Transformation</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-unmatched-12-apps-for-endless-screen-saving/"><u>In 2024, Unmatched 12 Apps for Endless Screen Saving</u></a></li>
<li><a href="https://screen-capture.techidaily.com/ioss-top-5-ps2-simulators/"><u>IOS's Top 5 PS2 Simulators</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170382520-nvidia-drivers-the-solution-to-your-computer-glitches/"><u>Nvidia Drivers: The Solution to Your Computer Glitches.</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/premier-no-cost-screen-recorder-tool-for-2024/"><u>Premier No-Cost Screen Recorder Tool for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-motorola-moto-g04-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Motorola Moto G04</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/supercharge-your-games-premium-top-10-drives/"><u>Supercharge Your Games  Premium Top 10 Drives</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-12-complimentary-keyboard-skill-courses-ideal-for-every-age-group/"><u>Top 12 Complimentary Keyboard Skill Courses: Ideal for Every Age Group</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169378228-ultimate-steam-deck-cool-tech-companions/"><u>Ultimate Steam Deck Cool Tech Companions!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/up-to-date-nvidia-quadro-rtx-8000-graphics-card-driver-support-for-win-11-8-and-7/"><u>Up-to-Date Nvidia Quadro RTX 8000 Graphics Card Driver Support for Win 11, 8 & 7</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161640910-valuepixeldesign-monitor-budget-gamers-choice/"><u>ValuePixelDesign Monitor, Budget Gamers' Choice!</u></a></li>
</ul></div>

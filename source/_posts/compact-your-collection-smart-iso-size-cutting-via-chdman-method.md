---
title: "Compact Your Collection: Smart ISO Size Cutting via CHDMAN Method"
date: 2024-07-29T05:58:52.002Z
updated: 2024-07-30T05:58:52.002Z
tags:
  - games
categories:
  - games
description: "This Article Describes Compact Your Collection: Smart ISO Size Cutting via CHDMAN Method"
excerpt: "This Article Describes Compact Your Collection: Smart ISO Size Cutting via CHDMAN Method"
keywords: Compact Collection,Chdman ISO Reduction,ISO Sizing Efficiency,Smart Size Cutting,CHDMAN Methodology,Collection Downsizing,Compact ISO Techniques
thumbnail: https://thmb.techidaily.com/fe142fc722967440c0a67173b1e546447bf0e801339eadf58291eb4451fb4b01.jpg
---

## Compact Your Collection: Smart ISO Size Cutting via CHDMAN Method

 If you're collecting ROMs like Pokémon, you surely have noticed that the ones for newer platforms take up a significant chunk of your storage. A single game might require multiple gigabytes of storage. Keep over a dozen, and your ROM collection can quickly expand to many Terabytes. That's where the MAME project's CHDMAN tool can help.

 Does your ROM collection contain arcade games or titles for consoles with optical media, like Sony's PlayStation? CHDMAN can compress them to CHD files that take up a fraction of a ROM's original size.

 What's best is that many emulators support the CHD format. So, you can keep playing your ROMs without extracting or decompressing them. Let's see how.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot of the Change Directory command in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cd-command-in-cmd.jpg)

To compress your game with CHDMAN to CHD format, use the following:

`chdman.exe createcd -i "ROM_YOU_WANT_TO_COMPRESS.CUE" -o "FILENAME_OF_COMPRESSED.CHD"`

Our command was:

`chdman createcd -i "MUO_PSX.cue" -o "MUO_PSX.chd"  
`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

 Because of[how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like[using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-how-to-perfectly-place-music-stickers-on-instagram-content/"><u>[New] 2024 Approved  How to Perfectly Place Music Stickers on Instagram Content</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-navigating-minecraft-recording-top-5-techniques-for-mac-users/"><u>[New] Navigating Minecraft Recording  Top 5 Techniques for Mac Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-professional-drone-selection-guide-top-5/"><u>[New] Professional Drone Selection Guide (Top 5)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-free-and-secure-3-ways-to-extract-youtube-music-content/"><u>[Updated] 2024 Approved  Free and Secure  3 Ways to Extract YouTube Music Content</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-beginners-handbook-to-igtv-mastery-for-2024/"><u>[Updated] The Beginner's Handbook to IGTV Mastery for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-revisiting-video-broadcast-choices-post-wirecast/"><u>2024 Approved  Revisiting Video Broadcast Choices Post-Wirecast</u></a></li>
<li><a href="https://games-able.techidaily.com/analyzing-input-techniques-polling-rates-role/"><u>Analyzing Input Techniques: Polling Rate's Role</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-game-performance-on-series-sx-through-expertly-setup-vrr-settings/"><u>Boosting Game Performance on Series S/X Through Expertly Setup VRR Settings</u></a></li>
<li><a href="https://games-able.techidaily.com/bring-back-childhood-fun-with-iphone-gaming-classics/"><u>Bring Back Childhood Fun with iPhone Gaming Classics</u></a></li>
<li><a href="https://games-able.techidaily.com/claiming-your-money-back-from-xbox-game-bets/"><u>Claiming Your Money Back From Xbox Game Bets</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168855962-enhance-performance-install-latest-nvidia-drivers-now/"><u>Enhance Performance! Install Latest Nvidia Drivers Now.</u></a></li>
<li><a href="https://games-able.techidaily.com/get-to-know-your-gpu-understanding-the-specs-of-amds-radeon-xt/"><u>Get to Know Your GPU: Understanding the Specs of AMD's Radeon XT</u></a></li>
<li><a href="https://games-able.techidaily.com/highlights-in-led-technology-year-2024/"><u>Highlights in LED Technology: Year 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-xiaomi-redmi-12-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Xiaomi Redmi 12 Quickly? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-on-apple-iphone-7-plus-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock on Apple iPhone 7 Plus</u></a></li>
<li><a href="https://games-able.techidaily.com/keep-your-switch-sharp-and-durable-with-easy-steps/"><u>Keep Your Switch Sharp & Durable with Easy Steps</u></a></li>
<li><a href="https://games-able.techidaily.com/level-up-challenge-the-best-terminal-games-on-linux/"><u>Level Up Challenge: The Best Terminal Games on Linux</u></a></li>
<li><a href="https://games-able.techidaily.com/master-lockdown-mode-implement-passcode-on-nintendo-switch-console/"><u>Master Lockdown Mode: Implement Passcode on Nintendo Switch Console</u></a></li>
<li><a href="https://games-able.techidaily.com/melody-maven-leading-audio-trivia-games-on-smartphones/"><u>Melody Maven: Leading Audio Trivia Games on Smartphones</u></a></li>
<li><a href="https://games-able.techidaily.com/navigate-the-virtual-world-offline-top-gaming-apps/"><u>Navigate the Virtual World Offline - Top Gaming Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/perfect-harmony-assembling-android-devices-and-controllers/"><u>Perfect Harmony: Assembling Android Devices and Controllers</u></a></li>
<li><a href="https://games-able.techidaily.com/perfecting-your-review-format-for-steam-games/"><u>Perfecting Your Review Format for Steam Games</u></a></li>
<li><a href="https://games-able.techidaily.com/re-launching-steam-a-triad-of-tips/"><u>Re-Launching Steam: A Triad of Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/remediation-techniques-for-low-end-display-effects/"><u>Remediation Techniques for Low-End Display Effects</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/revolutionizing-visuals-the-impact-of-usb-c-and-4k-on-hps-envy-27-for-2024/"><u>Revolutionizing Visuals  The Impact of USB-C & 4K on HP's Envy 27 for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/the-guide-to-outsmarting-ny-times-influence-daily/"><u>The Guide to Outsmarting NY Times Influence Daily</u></a></li>
<li><a href="https://games-able.techidaily.com/the-path-to-prosperous-steam-utilization/"><u>The Path to Prosperous Steam Utilization</u></a></li>
<li><a href="https://games-able.techidaily.com/the-top-4-imperatives-boosting-xbox-points-strategy/"><u>The Top 4 Imperatives: Boosting Xbox Points Strategy</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-windows-10-sound-engineers-manual/"><u>The Windows 10 Sound Engineer's Manual</u></a></li>
<li><a href="https://some-guidance.techidaily.com/tips-and-tricks-how-to-choose-a-winner-amongst-360-degree-cameras-for-2024/"><u>Tips & Tricks  How to Choose a Winner Amongst 360-Degree Cameras for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/transformative-tactics-for-gaming-via-steam-modding-mastery/"><u>Transformative Tactics for Gaming via Steam Modding Mastery</u></a></li>
<li><a href="https://games-able.techidaily.com/uncover-the-11-superb-free-word-puzzle-apps-today/"><u>Uncover the 11 Superb Free Word Puzzle Apps Today</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-and-executing-ps5-remote-reset/"><u>Understanding and Executing PS5 Remote Reset</u></a></li>
<li><a href="https://games-able.techidaily.com/why-microsoft-edge-holds-the-crown-in-gaming-browsers/"><u>Why Microsoft Edge Holds the Crown in Gaming Browsers</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Poco M6 Pro 4G | Dr.fone</u></a></li>
</ul></div>

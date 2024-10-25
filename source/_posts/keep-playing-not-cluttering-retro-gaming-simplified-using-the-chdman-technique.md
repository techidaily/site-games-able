---
title: "Keep Playing, Not Cluttering: Retro Gaming Simplified Using the ChDMan Technique"
date: 2024-10-18T04:06:54.707Z
updated: 2024-10-24T18:00:22.466Z
tags:
  - games
categories:
  - games
description: "This Article Describes Keep Playing, Not Cluttering: Retro Gaming Simplified Using the ChDMan Technique"
excerpt: "This Article Describes Keep Playing, Not Cluttering: Retro Gaming Simplified Using the ChDMan Technique"
keywords: Retro Gaming Tips,Simplify Gameplay,ChDMan Gaming,Clutter-Free Games,Playing Efficiently,Retro Simplicity,Gaming Techniques
thumbnail: https://thmb.techidaily.com/c5b0ebae4367079e280b487ce588fc466a9ede57f33408103ebb2dc34b6570fb.jpg
---

## Keep Playing, Not Cluttering: Retro Gaming Simplified Using the ChDMan Technique

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

## How to Compress Your ISOs With CHDMAN

 CHDMAN is distributed with the MAME emulator. If you already use that, you'll find CHDMAN's executable in MAME's installation directory. If not, download[the latest version of MAME from its official site](https://www.mamedev.org/) and install it on your PC to also get CHDMAN.

 To avoid typing the full path to CHDMAN every time you want to compress a ROM, add MAME's folder to your System Path variable. You can do this by[using environment variables in Windows 10](https://www.makeuseof.com/how-to-use-environment-variables-in-windows-10/) .

 Open a**File Explorer** window (**Windows Key + E**) and, to keep things tidy, create a folder anywhere you wish, within which you'll do all CHDMAN-related file juggling.

 Move the files of the ROM you want to compress to that folder. For this article, we'll use an original PlayStation backup stored in a CUE & BIN file combination.

![A screenshot of a BIN and CUE ROM image from the File Explorer in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/bin-and-cue-in-windows-file-explorer.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://unicoeye.pxf.io/c/5597632/2134230/18498" target="_top" id="2134230">
  <img src="//a.impactradius-go.com/display-ad/18498-2134230" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134230/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389">
  <img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-boost-your-online-presence-tips-and-techniques-for-exceptional-fb-profiles/"><u>[New] 2024 Approved Boost Your Online Presence Tips and Techniques for Exceptional FB Profiles</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-primepickings-top-twitters-and-top-viewers-favorites/"><u>[New] 2024 Approved PrimePickings Top Twitters & Top Viewers’ Favorites</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-seamless-gopro-broadcasts-tips-for-facebook-and-periscope-channeling/"><u>[New] In 2024, Seamless GoPro Broadcasts Tips for Facebook & Periscope Channeling</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-how-to-extract-and-convert-twitter-videos-hosted-on-youtube-to-mp3s/"><u>[Updated] How to Extract and Convert Twitter Videos Hosted on YouTube to MP3s</u></a></li>
<li><a href="https://games-able.techidaily.com/energys-evolution-power-and-more/"><u>Energy's Evolution: Power and More</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-neurological-function-with-marijuanas-endocannabinoids/"><u>Enhancing Neurological Function with Marijuana's Endocannabinoids</u></a></li>
<li><a href="https://games-able.techidaily.com/graphic-card-decision-time-founders-edition-or-vega-aib/"><u>Graphic Card Decision Time: Founders Edition Or Vega AIB?</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-lenovo-thinkphone-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Lenovo ThinkPhone If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-samsung-galaxy-f54-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Samsung Galaxy F54 5G Location | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/introducing-the-revolutionary-nvidia-gaming-app/"><u>Introducing the Revolutionary Nvidia Gaming App</u></a></li>
<li><a href="https://games-able.techidaily.com/prioritize-parts-a-complete-gaming-computer-list/"><u>Prioritize Parts: A Complete Gaming Computer List</u></a></li>
<li><a href="https://sound-issues.techidaily.com/restoring-audio-in-windows-media-player-effective-solutions-and-tips/"><u>Restoring Audio in Windows Media Player - Effective Solutions and Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/revamping-ps5-interface-colors/"><u>Revamping PS5 Interface Colors</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-game-consoles-emulated-on-macos/"><u>Top 5 Game Consoles Emulated on macOS</u></a></li>
<li><a href="https://sound-issues.techidaily.com/troubleshooting-and-repairing-your-logitech-g933-mic/"><u>Troubleshooting and Repairing Your Logitech G933 Mic</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-motorola-moto-g34-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Motorola Moto G34 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://games-able.techidaily.com/your-ps5-deserves-a-rest-why-shut-it-down/"><u>Your PS5 Deserves a Rest: Why Shut It Down?</u></a></li>
</ul></div>


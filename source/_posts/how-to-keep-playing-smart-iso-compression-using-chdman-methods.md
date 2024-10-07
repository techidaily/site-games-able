---
title: "How to Keep Playing: Smart ISO Compression Using ChDMan Methods"
date: 2024-10-04T19:00:56.122Z
updated: 2024-10-07T17:40:17.006Z
tags:
  - games
categories:
  - games
description: "This Article Describes How to Keep Playing: Smart ISO Compression Using ChDMan Methods"
excerpt: "This Article Describes How to Keep Playing: Smart ISO Compression Using ChDMan Methods"
keywords: Smart ISO Techniques,Advanced ChDMan Methods,Optimal Exposure Control,Effective ISO Compaction,Efficient Low-Light Photography,Noise Reduction Strategies,Dynamic ISO Adjustment
thumbnail: https://thmb.techidaily.com/e85743b34dfe1708fd7baeaabbf4be530a9d0acc972c34955c94cad23467f1e0.jpg
---

## How to Keep Playing: Smart ISO Compression Using ChDMan Methods

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

 Run Windows CMD or PowerShell. Then, move to the folder with your game's files with the Change Directory (CD) command:

`cd PATH_TO_FOLDER`

Our command was:

`cd "H:\Emulation\ROMs\PS1\Compress-to-CHD"`

![A screenshot of the Change Directory command in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cd-command-in-cmd.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://dhgate.sjv.io/c/5597632/1175223/12108" target="_top" id="1175223">
  <img src="//a.impactradius-go.com/display-ad/12108-1175223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1175223/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-explore-our-12-tycoon-classics-for-engrossing-experiences/"><u>[New] 2024 Approved Explore Our #12 Tycoon Classics for Engrossing Experiences</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-x-recorder-your-pcs-audio-capture-companion/"><u>[New] 2024 Approved X-Recorder Your PC's Audio Capture Companion</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-update-twitter-video-preview/"><u>[Updated] 2024 Approved Update Twitter Video Preview</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-cutting-and-compositing-for-youtube-videos-using-premiere-pro-for-2024/"><u>[Updated] Cutting and Compositing for YouTube Videos Using Premiere Pro for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/10-best-online-learning-sites-like-udemy-for-2024/"><u>10 Best Online Learning Sites Like Udemy for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-virtual-gaming-chesspoker-on-discord-networks/"><u>Discovering Virtual Gaming: Chess/Poker on Discord Networks</u></a></li>
<li><a href="https://games-able.techidaily.com/fortnite-on-your-flipboard-the-ios-experience-via-nvidia/"><u>Fortnite on Your Flipboard: The iOS Experience via Nvidia</u></a></li>
<li><a href="https://games-able.techidaily.com/free-range-from-realms-keep-your-realm-creations/"><u>Free-Range From Realms, Keep Your Realm Creations</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-unexpected-display-glitches-on-your-windows-10-computer/"><u>How To Stop Unexpected Display Glitches on Your Windows 10 Computer</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-vivo-y78t-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Vivo Y78t? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/keeping-a-cool-profile-gpus-in-games/"><u>Keeping a Cool Profile: GPUs in Games</u></a></li>
<li><a href="https://games-able.techidaily.com/methods-to-address-windows-oculus-integration-issues/"><u>Methods to Address Windows-Oculus Integration Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-7-strategies-to-enhance-pc-performance-swiftly/"><u>Top 7 Strategies to Enhance PC Performance Swiftly</u></a></li>
<li><a href="https://games-able.techidaily.com/upgrading-to-rtx-after-nvidias-gtx-demise/"><u>Upgrading to RTX After Nvidia's GTX Demise</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-arp-cache-explained-clears-and-management/"><u>Windows ARP Cache Explained: Clears & Management</u></a></li>
<li><a href="https://games-able.techidaily.com/your-guide-to-the-best-mobile-gaming-escapes/"><u>Your Guide to the Best Mobile Gaming Escapes</u></a></li>
</ul></div>


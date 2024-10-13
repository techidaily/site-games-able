---
title: "Compress Without Compromise: ChDMan's ISO Solution for Gamers"
date: 2024-10-11T06:51:46.275Z
updated: 2024-10-13T02:06:20.342Z
tags:
  - games
categories:
  - games
description: "This Article Describes Compress Without Compromise: ChDMan's ISO Solution for Gamers"
excerpt: "This Article Describes Compress Without Compromise: ChDMan's ISO Solution for Gamers"
keywords: Compression Tips,High-Quality Gaming,ISO Optimization,Image Compression,Video Quality Preserved,Gamers' Storage Solutions,Enhanced Game Files
thumbnail: https://thmb.techidaily.com/b926e430c3910450366f0c5eac6f2faf425580bfe11541a9628c11209d7640f5.jpg
---

## Compress Without Compromise: ChDMan's ISO Solution for Gamers

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Because of[how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like[using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948937/19272" target="_top" id="1948937">
  <img src="//a.impactradius-go.com/display-ad/19272-1948937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-channel-command-center-mastering-your-digital-domain/"><u>[New] 2024 Approved Channel Command Center Mastering Your Digital Domain</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-choreographing-newscast-endings-for-2024/"><u>[Updated] Choreographing Newscast Endings for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-instant-podcast-live-simple-strategies/"><u>[Updated] Instant Podcast Live Simple Strategies</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-comprehensive-laptop-screenrec-users-handbook/"><u>2024 Approved The Comprehensive Laptop ScreenRec User's Handbook</u></a></li>
<li><a href="https://games-able.techidaily.com/connect-bluetooth-audio-devices-successfully-to-xbox-series-xs-and-one-detailed-instructions-and-tips/"><u>Connect Bluetooth Audio Devices Successfully to Xbox Series X/S and One - Detailed Instructions & Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/get-a-discounted-rtx-3070-gpu-save-220-immediately-with-our-offer-power-your-gaming-today/"><u>Get a Discounted RTX 3070 GPU - Save $220 Immediately with Our Offer! Power Your Gaming Today!</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-samsung-galaxy-xcover-7-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Samsung Galaxy XCover 7 Phone | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/head-to-head-comparison-corsair-m65-rgb-ultra-vs-razer-flagship-an-in-depth-review-on-gizhack/"><u>Head-to-Head Comparison: Corsair M65 RGB Ultra Vs. Razer Flagship - An In-Depth Review on GizHack</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-itel-a70-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Itel A70? | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-maximizing-value-in-your-cloud-service-expenditure/"><u>In 2024, Maximizing Value in Your Cloud Service Expenditure</u></a></li>
<li><a href="https://fox-helps.techidaily.com/iphones-unlocked-smart-tips-for-saving-and-playing-gifs-for-2024/"><u>IPhones Unlocked Smart Tips for Saving & Playing GIFs for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/save-big-on-premium-55-roku-smart-led-tv-now-at-an-unbeatable-price-of-649-dont-miss-out-this-labor-day-sale/"><u>Save Big on Premium 55 Roku Smart LED TV: Now at an Unbeatable Price of $649! Don't Miss Out This Labor Day Sale!</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/understanding-the-various-categories-of-programs-on-microsofts-windows-marketplace/"><u>Understanding the Various Categories of Programs on Microsoft's Windows Marketplace</u></a></li>
<li><a href="https://games-able.techidaily.com/why-windows-11-takes-the-lead-over-windows-n-in-gaming-performance-insights-from-pc-players-zdnet/"><u>Why Windows 11 Takes the Lead Over Windows N in Gaming Performance: Insights From PC Players - ZDNet</u></a></li>
</ul></div>


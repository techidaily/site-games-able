---
title: "Maximizing Game Files: Mastering CHDMAN ISO Compression & Use"
date: 2024-10-01T18:39:37.041Z
updated: 2024-10-07T19:03:06.627Z
tags:
  - games
categories:
  - games
description: "This Article Describes Maximizing Game Files: Mastering CHDMAN ISO Compression & Use"
excerpt: "This Article Describes Maximizing Game Files: Mastering CHDMAN ISO Compression & Use"
keywords: Game File Optimization,CHDMAN ISO Tools,Digital Game Storage,ISO Compression Tips,Efficient Gaming Files,CHDMAN Compressor Guide,Space-Saving Game Formats
thumbnail: https://thmb.techidaily.com/680c73892fadaf0cd37020955286e78a6c2698cf86437727fe7a9aa1c7291d00.jpg
---

## Maximizing Game Files: Mastering CHDMAN ISO Compression & Use

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
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

![DuckStation File Selector set to MAME CHD images](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/duckstation-chd-file-selection-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-lessons.techidaily.com/updated-chucklechamber-endless-options-to-spread-smiles/"><u>[Updated] ChuckleChamber Endless Options to Spread Smiles</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-crafting-concentration-in-photos-with-insta-zoom-tricks/"><u>[Updated] In 2024, Crafting Concentration in Photos with Insta Zoom Tricks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/9-best-phone-monitoring-apps-for-tecno-phantom-v-fold-drfone-by-drfone-virtual-android/"><u>9 Best Phone Monitoring Apps for Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/beyond-ai-horizons-decoding-the-titles-and-responsibilities-of-tomorrows-job-roles-defined-by-tech-progress/"><u>Beyond AI Horizons: Decoding the Titles and Responsibilities of Tomorrow's Job Roles Defined by Tech Progress</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-gaming-a-step-by-step-controller-tear-down/"><u>Decoding Gaming: A Step-by-Step Controller Tear Down</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-edges-pro-gaming-features/"><u>Discovering Edge's Pro-Gaming Features</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-the-latest-dell-wd19-hard-drive-drivers-here/"><u>Get the Latest Dell WD19 Hard Drive Drivers Here!</u></a></li>
<li><a href="https://games-able.techidaily.com/high-end-gpus-why-i-overpaid-and-overlooked-alternatives/"><u>High-End GPUs: Why I Overpaid & Overlooked Alternatives</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-infinix-smart-8-plus-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Infinix Smart 8 Plus Android SIM Unlock APK</u></a></li>
<li><a href="https://games-able.techidaily.com/master-controller-emulation-for-nintendo/"><u>Master Controller Emulation for Nintendo</u></a></li>
<li><a href="https://games-able.techidaily.com/say-goodbye-to-unhappy-moments-resolving-the-top-10-reasons-games-freeze/"><u>Say Goodbye to Unhappy Moments: Resolving the Top 10 Reasons Games Freeze</u></a></li>
<li><a href="https://games-able.techidaily.com/the-top-ten-terrors-of-trial-and-tribulation-in-games/"><u>The Top Ten Terrors of Trial and Tribulation in Games</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-mouse-traits-to-ignite-a-winning-gaming-performance/"><u>Top 5 Mouse Traits to Ignite a Winning Gaming Performance</u></a></li>
<li><a href="https://technical-tips.techidaily.com/ultimate-comparison-of-2024s-leading-video-doorbells-features-prices-and-reviews-cnet/"><u>Ultimate Comparison of 2024'S Leading Video Doorbells - Features, Prices, and Reviews | CNET</u></a></li>
<li><a href="https://driver-download.techidaily.com/upgrade-your-windows-pc-with-official-xerox-printer-driver-software-free-downloads-available/"><u>Upgrade Your Windows PC with Official Xerox Printer Driver Software - Free Downloads Available</u></a></li>
</ul></div>


---
title: "Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size"
date: 2025-01-17T05:56:56.344Z
updated: 2025-01-22T18:36:22.911Z
tags:
  - games
categories:
  - games
description: "This Article Describes Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size"
excerpt: "This Article Describes Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size"
keywords: Space Saver Gaming,ISO Size Reduction,CHDMAN Method,Game Optimization,Memory Efficiency,Save Games Quickly,Tech Game Tips
thumbnail: https://thmb.techidaily.com/90ad0e184ba79f95e662dd6bac421c2714531f47a3dc9eccb9055a4b28f7166a.jpg
---

## Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

To compress your game with CHDMAN to CHD format, use the following:

`chdman.exe createcd -i "ROM_YOU_WANT_TO_COMPRESS.CUE" -o "FILENAME_OF_COMPRESSED.CHD"`

Our command was:

`chdman createcd -i "MUO_PSX.cue" -o "MUO_PSX.chd"  
`

![A screenshot of the command to compress a ROM into CHD format using CHDMAN](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/chdman-createcd-command-in-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OFDHJnZLwTA?si=WThcb2h76AnZDzcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

![DuckStation File Selector set to MAME CHD images](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/duckstation-chd-file-selection-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pGHmqD53gc8?si=ymgHIB6Aa7_MoUUf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-the-red-zones-best-unraveling-zombie-gaming-delights/"><u>[New] In 2024, The Red Zone's Best Unraveling Zombie Gaming Delights</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-photo-pinnacle-top-tripods-for-android-and-iphones-for-2024/"><u>[New] Photo Pinnacle Top Tripods for Android & iPhones for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-essential-tips-for-configuring-and-measuring-facebooks-in-stream-ads/"><u>[Updated] In 2024, Essential Tips for Configuring and Measuring Facebook's In-Stream Ads</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-mastering-the-craft-of-online-title-perfection/"><u>2024 Approved Mastering the Craft of Online Title Perfection</u></a></li>
<li><a href="https://games-able.techidaily.com/dynamic-cooling-curve-design-elevates-system-stability/"><u>Dynamic Cooling Curve Design Elevates System Stability</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-fixes-how-to-recover-forgotten-icloud-password-from-your-iphone-6-by-drfone-ios/"><u>Easy Fixes How To Recover Forgotten iCloud Password From your iPhone 6</u></a></li>
<li><a href="https://facebook.techidaily.com/enhance-your-weekend-with-fbs-live-purchasing-hours/"><u>Enhance Your Weekend with FB's Live Purchasing Hours</u></a></li>
<li><a href="https://games-able.techidaily.com/from-sony-portable-playback-to-dual-analog-simulation/"><u>From Sony Portable Playback to Dual Analog Simulation</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-systems-showdown-consoles-vs-personal-builds/"><u>Gaming Systems Showdown: Consoles Vs. Personal Builds</u></a></li>
<li><a href="https://fox-pages.techidaily.com/guida-esclusiva-come-risolvere-e-prevenire-la-sincronizzazione-problematica-nel-tuo-outlook-365/"><u>Guida Esclusiva: Come Risolvere E Prevenire La Sincronizzazione Problematica Nel Tuo Outlook 365</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-nova-y91-by-fonelab-android-recover-photos/"><u>How To Restore Missing Photos Files from Nova Y91.</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-pc-management-the-4-powerful-upgrades-in-corsairs-icue-link/"><u>Mastering PC Management: The 4 Powerful Upgrades in Corsair's iCUE Link</u></a></li>
<li><a href="https://tech-revival.techidaily.com/passo-a-passo-em-fazer-animacoes-stop-motion-conheca-as-melhores-dicas-tutorials-e-exemplos/"><u>Passo a Passo Em Fazer Animações Stop Motion - Conheça as Melhores Dicas, Tutorials E Exemplos!</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/prime-places-for-accessible-outstanding-vector-design-tools-for-2024/"><u>Prime Places for Accessible, Outstanding Vector Design Tools for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/pure-playstation-cleaning-without-risk/"><u>Pure PlayStation: Cleaning Without Risk</u></a></li>
<li><a href="https://games-able.techidaily.com/the-end-of-platform-locked-entertainment/"><u>The End of Platform-Locked Entertainment</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-console-experience-with-exceptional-panels/"><u>Transform Your Console Experience with Exceptional Panels</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-non-joy-con-link-problems-for-switch-users/"><u>Troubleshooting Non-Joy-Con Link Problems for Switch Users</u></a></li>
<li><a href="https://games-able.techidaily.com/unique-curve-design-balancing-thermal-management-and-performance/"><u>Unique Curve Design: Balancing Thermal Management and Performance</u></a></li>
</ul></div>


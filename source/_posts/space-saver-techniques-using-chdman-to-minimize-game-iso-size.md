---
title: "Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size"
date: 2024-12-15T21:34:38.069Z
updated: 2024-12-17T09:03:54.976Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-the-art-of-influencing-with-tiktok-marketing/"><u>[New] In 2024, The Art of Influencing with TikTok Marketing</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-top-picks-8-must-have-wallpapers-for-macos-users-for-2024/"><u>[New] Top Picks 8 Must-Have Wallpapers for MacOS Users for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-how-to-expertly-archive-your-favorite-streamed-shows-hulu/"><u>[Updated] In 2024, How To Expertly Archive Your Favorite Streamed Shows (Hulu)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-youtube-mastery-tips-for-producing-cutting-edge-videos/"><u>2024 Approved YouTube Mastery Tips for Producing Cutting-Edge Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/cost-analysis-of-subscribing-to-sony-online-entertainment/"><u>Cost Analysis of Subscribing to Sony Online Entertainment</u></a></li>
<li><a href="https://games-able.techidaily.com/effortlessly-linking-an-external-device-for-enhanced-play/"><u>Effortlessly Linking an External Device for Enhanced Play</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-proceed-with-a-digital-xbox-seriess-reimbursement/"><u>How to Proceed with a Digital Xbox Series/S Reimbursement</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-removing-stickers-with-precision-a-tiktok-specialists-guide/"><u>In 2024, Removing Stickers with Precision A TikTok Specialist's Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlocking-apple-iphone-xs-max-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>In 2024, Unlocking Apple iPhone XS Max Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-xbox-series-xands-gameplay-with-quick-resume/"><u>Maximizing Xbox Series X&S Gameplay with Quick Résumé</u></a></li>
<li><a href="https://games-able.techidaily.com/more-than-just-numbers-evaluating-steam-status/"><u>More Than Just Numbers - Evaluating Steam Status</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-your-steam-experience-fixes-for-windows-11/"><u>Streamline Your Steam Experience: Fixes for Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/the-evolution-of-smoother-gaming-introducing-nvidia-g-sync/"><u>The Evolution of Smoother Gaming: Introducing Nvidia G-Sync</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-truth-behind-chatgpts-content-an-insight-into-possible-plagiarism-concerns/"><u>The Truth Behind ChatGPT's Content: An Insight Into Possible Plagiarism Concerns</u></a></li>
<li><a href="https://fox-blue.techidaily.com/timeless-tales-of-summer-delight-top-10-kids-movies-for-2024/"><u>Timeless Tales of Summer Delight Top 10 Kid's Movies for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-handbrake-blockage-now/"><u>Unlock Windows HandBrake Blockage Now</u></a></li>
</ul></div>


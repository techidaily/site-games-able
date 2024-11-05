---
title: Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques
date: 2024-10-29T18:57:57.648Z
updated: 2024-11-05T21:16:54.231Z
tags:
  - games
categories:
  - games
description: This Article Describes Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques
excerpt: This Article Describes Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques
keywords: Arcades Miniature Storage,CHDMAN Archiving Tips,Efficient Archive Methods,Miniaturize Arcade Files,Archive Technique CHDMAN,Small-Scale Arcade Backup,Arcade Data Compression
thumbnail: https://thmb.techidaily.com/ad574335e648a7deda4261a3d60c02e5050876ad97d3a8d2551786ec91da20e4.jpg
---

## Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques

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
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
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

### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924297/11305" target="_top" id="924297">
  <img src="//a.impactradius-go.com/display-ad/11305-924297" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/924297/11305" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-craft-your-best-youtubing-exit-tips-from-industry-leaders/"><u>[New] 2024 Approved Craft Your Best YouTubing Exit - Tips From Industry Leaders</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-quick-steps-to-authenticate-your-youtube-login/"><u>[Updated] 2024 Approved Quick Steps to Authenticate Your YouTube Login</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-mastering-solo-podcast-production-for-top-spots/"><u>[Updated] In 2024, Mastering Solo Podcast Production for Top Spots</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-transform-engagement-crafted-queries-for-personalized-ig-stories-for-2024/"><u>[Updated] Transform Engagement Crafted Queries for Personalized IG Stories for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/corsair-keyboard-lighting-problem-heres-how-to-get-those-lights-back/"><u>Corsair Keyboard Lighting Problem? Here’s How to Get Those Lights Back!</u></a></li>
<li><a href="https://games-able.techidaily.com/crafting-the-perfect-visual-environment-using-xbox-lights/"><u>Crafting the Perfect Visual Environment Using Xbox Lights</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-dxvk-the-key-to-improved-wingaming/"><u>Dive Into DXVK: The Key to Improved WinGaming</u></a></li>
<li><a href="https://games-able.techidaily.com/elite-high-refresh-rate-gaming-displays/"><u>Elite High-Refresh Rate Gaming Displays</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-the-go-hints-of-switch-next-gen/"><u>Game on the Go! Hints of Switch Next Gen</u></a></li>
<li><a href="https://games-able.techidaily.com/investigating-the-accuracy-of-no-activity-tag-in-discord/"><u>Investigating the Accuracy of 'No Activity' Tag in Discord</u></a></li>
<li><a href="https://howto.techidaily.com/my-videos-arent-playing-on-vivo-y17s-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Vivo Y17s – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/summiting-top-tier-nintendo-switch-joypads/"><u>Summiting Top-Tier Nintendo Switch Joypads</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-10-tailored-gpt-variants-enhancing-chatgpts-capabilities/"><u>Top 10 Tailored GPT Variants Enhancing ChatGPT's Capabilities</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-to-the-most-secure-and-stylish-magsafe-wallets-of-2024-in-depth-analysis-and-ratings-zdnet/"><u>Ultimate Guide to the Most Secure & Stylish MagSafe Wallets of 2024: In-Depth Analysis and Ratings | ZDNet</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-windows-11-no-display-problem/"><u>Ultimate Guide: Resolving the Windows 11 No Display Problem</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-shared-games-for-ps5-users/"><u>Unlocking Shared Games for PS5 Users</u></a></li>
</ul></div>


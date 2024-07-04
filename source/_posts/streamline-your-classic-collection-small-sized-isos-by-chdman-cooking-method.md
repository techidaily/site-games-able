---
title: "Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method"
date: 2024-06-25T13:17:01.385Z
updated: 2024-06-26T13:17:01.385Z
tags:
  - games
categories:
  - games
description: "This Article Describes Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method"
excerpt: "This Article Describes Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method"
keywords: Streamlined Classics,ISO Sizes Mini,DMan Cooking Style,Classic Collection,Small-Sized ISOs,ChDMan' Techniques,Efficient ISO Methods
thumbnail: https://thmb.techidaily.com/04f98c03565f60c0b0ad3b1ba3f80966cc746c43e46cf7809dfb5c690e2c4abe.jpg
---

## Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method

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
<li><a href="https://games-able.techidaily.com/connecting-modern-xbox-joysticks-to-windows-systems-140-chars/"><u>Connecting Modern Xbox Joysticks to Windows Systems (140 Chars)</u></a></li>
<li><a href="https://games-able.techidaily.com/emulating-vintage-gaming-the-power-of-xemu-for-pc/"><u>Emulating Vintage Gaming: The Power of Xemu for PC</u></a></li>
<li><a href="https://games-able.techidaily.com/console-vs-computer-gaming-face-off/"><u>Console Vs. Computer: Gaming Face-Off</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168632590-18-engaging-duet-conversations-texting-fun-hits-two/"><u>18 Engaging Duet Conversations: Texting Fun Hits Two</u></a></li>
<li><a href="https://games-able.techidaily.com/innovative-play-on-ps5-beyond-gamepad-use/"><u>Innovative Play on PS5 Beyond Gamepad Use</u></a></li>
<li><a href="https://games-able.techidaily.com/should-premium-games-include-microtransactions/"><u>Should Premium Games Include Microtransactions?</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-mystery-how-to-activate-undisclosed-browser/"><u>PS5 Mystery: How to Activate Undisclosed Browser?</u></a></li>
<li><a href="https://games-able.techidaily.com/the-truth-about-free-to-play-why-premium-games-are-better/"><u>The Truth About 'Free-to-Play': Why Premium Games Are Better</u></a></li>
<li><a href="https://games-able.techidaily.com/the-duality-of-pimax-crystal-headset-sharpness-vs-stability/"><u>The Duality of Pimax Crystal Headset: Sharpness vs Stability</u></a></li>
<li><a href="https://games-able.techidaily.com/protect-your-kids-navigating-discords-risks/"><u>Protect Your Kids: Navigating Discord's Risks</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-electronically-sign-a-wps-file-using-digisigner-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to Electronically Sign a .wps file Using DigiSigner</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-break-free-from-format-restrictions-chromecast-streaming-for-all-videos/"><u>Updated In 2024, Break Free From Format Restrictions Chromecast Streaming for All Videos</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/unlocking-speech-from-melody-top-3-online-methods-for-mp3-to-text-conversion-for-2024/"><u>Unlocking Speech From Melody Top 3 Online Methods for MP3-to-Text Conversion for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/becoming-a-reaction-guru-a-complete-guidebook/"><u>Becoming a Reaction Guru  A Complete Guidebook</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-x6-pro-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Poco X6 Pro Phone with Broken Screen</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-nokia-c110-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Nokia C110 Quickly | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-the-ultimate-guide-to-free-wmv-video-splitters-for-2024/"><u>New The Ultimate Guide to Free WMV Video Splitters for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-unlock-the-full-potential-with-advanced-gopro-studio-edits/"><u>[Updated] Unlock the Full Potential with Advanced GoPro Studio Edits</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-close-up-confidence-navigating-google-meets-zoom-feature/"><u>[Updated] Close-Up Confidence  Navigating Google Meet's Zoom Feature</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-lava-yuva-2-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Lava Yuva 2? Heres A Full Solution | Dr.fone</u></a></li>
</ul></div>

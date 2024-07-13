---
title: "ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
date: 2024-07-12T04:21:29.311Z
updated: 2024-07-13T04:21:29.311Z
tags:
  - games
categories:
  - games
description: "This Article Describes ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
excerpt: "This Article Describes ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
keywords: Vintage Game Conservation,Classic Gaming Restoration,Heritage Video Game Storage,Retro Games Maintenance,Preserving Old Video Games,Accessing Antique Games,Saving Vintage Gaming Collections
thumbnail: https://thmb.techidaily.com/91b7cfb4d96e2456602f29985eb790b38dbd8c0fc22d4f4a877755c3058adea9.jpg
---

## ACHDMAN Strategies: Preserving and Accessing Your Vintage Games

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
<li><a href="https://ai-editing-video.techidaily.com/how-to-use-obs-chroma-key-withwithout-green-screen-easy-solutions-for-2024/"><u>How to Use OBS Chroma Key With/Without Green Screen Easy Solutions for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/advanced-data-transfers-ideal-cables-for-games/"><u>Advanced Data Transfers: Ideal Cables For Games</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168257558-step-into-the-fun-zone-engage-with-these-6-chatgpt-games/"><u>Step Into the Fun Zone: Engage With These 6 ChatGPT Games</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-preserve-your-animated-fun-discover-the-best-9-gif-recorder-apps-for-pc/"><u>[New] In 2024, Preserve Your Animated Fun  Discover the Best 9 GIF Recorder Apps for PC</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169517737-discover-and-join-youtubes-latest-minigame-testing/"><u>Discover & Join YouTube's Latest Minigame Testing!</u></a></li>
<li><a href="https://games-able.techidaily.com/adapt-and-thrive-enjoy-flash-games-without-flash-required/"><u>Adapt and Thrive: Enjoy Flash Games Without Flash Required</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-era-of-interoperability-for-gaming-hardware/"><u>A New Era of Interoperability for Gaming Hardware</u></a></li>
<li><a href="https://games-able.techidaily.com/6-quirky-and-fun-chess-apps-to-play-chess-variants-online-or-against-ai/"><u>6 Quirky and Fun Chess Apps to Play Chess Variants Online or Against AI</u></a></li>
<li><a href="https://games-able.techidaily.com/achieve-quick-installation-of-discord-for-mac-devices/"><u>Achieve Quick Installation of Discord for Mac Devices</u></a></li>
<li><a href="https://extra-skills.techidaily.com/premium-animated-design-kits-for-2024/"><u>Premium Animated Design Kits for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/5-unique-features-you-should-look-for-in-a-gaming-mouse/"><u>5 Unique Features You Should Look for in a Gaming Mouse</u></a></li>
<li><a href="https://games-able.techidaily.com/2023-ifa-unveiled-top-future-gaming-tech-awaits/"><u>2023 IFA Unveiled: Top Future Gaming Tech Awaits</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-chapter-valve-elevates-shared-gaming-with-updates/"><u>A New Chapter: Valve Elevates Shared Gaming with Updates</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-assemble-your-unique-google-cardboard-virtual-reality/"><u>[Updated] Assemble Your Unique Google Cardboard Virtual Reality</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-apps-and-online-tools-to-track-oppo-reno-11-pro-5g-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Oppo Reno 11 Pro 5G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://extra-support.techidaily.com/repairing-a-stand-alone-headphone-for-2024/"><u>Repairing a Stand-Alone Headphone for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/achieve-discord-mastery-mac-installation-tips/"><u>Achieve Discord Mastery: Mac Installation Tips</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-samsung-galaxy-a24-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Samsung Galaxy A24 Fingerprint Lock</u></a></li>
<li><a href="https://games-able.techidaily.com/ace-your-games-with-optimal-windows-fps-settings/"><u>Ace Your Games with Optimal Windows FPS Settings</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-luminance-levels-top-3-ways-to-revive-your-photos-vibrancy/"><u>[New] Luminance Levels  Top 3 Ways to Revive Your Photo's Vibrancy</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-craft-a-melody-filled-visual-narrative-at-zero-price-for-2024/"><u>New Craft a Melody-Filled Visual Narrative at Zero Price for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/achieving-optimal-lifespan-for-your-switch-gaming-device/"><u>Achieving Optimal Lifespan for Your Switch Gaming Device</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-pursuit-with-panasonics-hx-a1-wearable-cameras/"><u>In Pursuit with Panasonic’s HX-A1 Wearable Cameras</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-how-to-stream-on-mixer-macos/"><u>[New] How to Stream on Mixer MacOS</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-from-no-one-watching-to-huge-engagement-10-proven-ways-to-increase-video-popularity/"><u>In 2024, From No One Watching to Huge Engagement  10 Proven Ways to Increase Video Popularity</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171836864-unlock-every-steam-badge-in-minutes/"><u>Unlock Every Steam Badge in Minutes</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-apex-legends-crossplay-how-to-turn-it-off-and-platform-choosing-guide/"><u>[Updated] In 2024, Apex Legends Crossplay  How to Turn It Off & Platform Choosing Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/499-moza-r5-sim-racing-start-for-enthusiasts/"><u>$499 MOZA R5: Sim Racing Start for Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/6-subtle-steps-to-cut-costs-using-xbox/"><u>6 Subtle Steps to Cut Costs Using Xbox</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-experts-choice-top-10-best-free-lut-downloads-for-2024/"><u>[Updated] Expert's Choice - Top 10 Best Free LUT Downloads for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-enhance-instagram-video-streams-speedily/"><u>[Updated] In 2024, Enhance Instagram Video Streams Speedily</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-fostering-engagement-creating-budget-friendly-youtube-intros/"><u>2024 Approved  Fostering Engagement  Creating Budget-Friendly YouTube Intros</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-overview-of-the-best-realme-11-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>In 2024, Overview of the Best Realme 11 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172710145-maximize-arcade-fun-embrace-big-box-framing/"><u>Maximize Arcade Fun: Embrace Big Box Framing!</u></a></li>
<li><a href="https://games-able.techidaily.com/activating-ps5-multiplayer-connection/"><u>Activating PS5 Multiplayer Connection</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-ultimate-guide-sharing-youtube-videos-on-fb-for-2024/"><u>[Updated] The Ultimate Guide  Sharing YouTube Videos on FB for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-t-play-mp4-files-on-samsung-galaxy-f14-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Can't play MP4 files on Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-steam-software-file-recovery-problem/"><u>Addressing Steam Software File Recovery Problem</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-chromebook-screenshot-hacks-in-four-steps/"><u>[Updated] Chromebook Screenshot Hacks in Four Steps</u></a></li>
<li><a href="https://games-able.techidaily.com/accumulate-and-ace-3-power-up-websites-for-gamers/"><u>Accumulate and Ace: 3 Power-Up Websites for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/9-important-tips-for-traveling-gamers/"><u>9 Important Tips for Traveling Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-unauthorized-card-error-messages-in-ps5/"><u>Addressing Unauthorized Card Error Messages in PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/2024-ddr5-high-performance-selection/"><u>2024 DDR5 High-Performance Selection</u></a></li>
<li><a href="https://extra-tips.techidaily.com/harnessing-the-power-of-yis-4k-video-and-motion-controls/"><u>Harnessing the Power of Yi's 4K Video and Motion Controls</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-tecno-phantom-v-flip-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Tecno Phantom V Flip to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-the-art-of-influential-hashtags-on-ig/"><u>[Updated] Mastering the Art of Influential Hashtags on IG</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-wise-approach-to-reviving-your-ps5-remote/"><u>A Step-Wise Approach to Reviving Your PS5 Remote</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-steams-failed-game-validation-issue/"><u>Addressing Steam's Failed Game Validation Issue</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-overview-of-controller-techniques-in-ryujinx-emulation/"><u>A Comprehensive Overview of Controller Techniques in Ryujinx Emulation</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-minecraft-launcher-issue-fix-error-0x803f8001/"><u>Addressing Minecraft Launcher Issue: Fix Error 0X803F8001</u></a></li>
</ul></div>

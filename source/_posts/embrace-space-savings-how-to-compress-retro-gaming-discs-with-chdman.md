---
title: "Embrace Space Savings: How to Compress Retro Gaming Discs with ChDMan"
date: 2024-07-12T04:10:18.029Z
updated: 2024-07-13T04:10:18.029Z
tags:
  - games
categories:
  - games
description: "This Article Describes Embrace Space Savings: How to Compress Retro Gaming Discs with ChDMan"
excerpt: "This Article Describes Embrace Space Savings: How to Compress Retro Gaming Discs with ChDMan"
keywords: Retro Game Disc Compression,Gaming Disk Shrinkage,ChDMan Technique,Space-Saving Games,Deduplicate Gaming Discs,ChDMan Hacking,Optimize Retro Game Media
thumbnail: https://thmb.techidaily.com/f3b9ebc545f359ab98a545c4a62ebaee9fb8e9ec48b8af506bc5428bdf5f9d0e.jpg
---

## Embrace Space Savings: How to Compress Retro Gaming Discs with ChDMan

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
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-a-comprehensive-guide-on-vhs-technology-and-its-influence-on-video-editing/"><u>Updated In 2024, A Comprehensive Guide on VHS Technology and Its Influence on Video Editing</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-streamlining-your-podcast-for-apple-platform-access/"><u>2024 Approved  Streamlining Your Podcast for Apple Platform Access</u></a></li>
<li><a href="https://games-able.techidaily.com/uncover-the-true-cost-of-endless-playtime/"><u>Uncover the True Cost of Endless Playtime</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-a-network-locked-vivo-x-flip-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Vivo X Flip Phone?</u></a></li>
<li><a href="https://games-able.techidaily.com/why-every-gamer-needs-steam-in-their-arsenal-heres-why/"><u>Why Every Gamer Needs Steam in Their Arsenal (Here's Why)</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-controlling-ps4-possible-or-not/"><u>PS5 Controlling PS4: Possible or Not?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-to-vivo-g2-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Vivo G2 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-exquisite-compilation-of-hits-best-selling-pop-songs-to-accompany-videos/"><u>Updated 2024 Approved Exquisite Compilation of Hits Best-Selling Pop Songs to Accompany Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/pitch-perfect-excellent-audio-games-for-music-enthusiasts/"><u>Pitch Perfect: Excellent Audio Games for Music Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/chatgpt-and-dungeons-6-secrets-to-perfect-assistantship/"><u>ChatGPT & Dungeons: 6 Secrets to Perfect Assistantship</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-friendly-boards-next-gen-gaming-companions/"><u>Budget-Friendly Boards: Next Gen Gaming Companions</u></a></li>
<li><a href="https://games-able.techidaily.com/transitioning-times-set-regional-settings-for-sxs/"><u>Transitioning Times: Set Regional Settings for SX|S</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-global-tiktok-stars-the-top-15-influencers/"><u>[Updated] 2024 Approved  Global TikTok Stars  The Top 15 Influencers</u></a></li>
<li><a href="https://games-able.techidaily.com/top-6-cautions-why-not-choose-intels-newest-cores/"><u>Top 6 Cautions: Why Not Choose Intel's Newest Cores</u></a></li>
<li><a href="https://games-able.techidaily.com/play-again-4-solutions-for-flash-game-enthusiasts/"><u>Play Again: 4 Solutions for Flash Game Enthusiasts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/mastering-zooms-video-enhancements-filter-techniques/"><u>Mastering Zoom's Video Enhancements  Filter Techniques</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-high-quality-video-capture-for-beginner-creators/"><u>[Updated] High-Quality Video Capture for Beginner Creators</u></a></li>
<li><a href="https://games-able.techidaily.com/can-ps5s-dualsense-play-on-ps4-devices/"><u>Can PS5's DualSense Play on PS4 Devices?</u></a></li>
<li><a href="https://games-able.techidaily.com/the-unwanted-game-follow-this-guide-for-xbox-returns/"><u>The Unwanted Game? Follow This Guide for Xbox Returns</u></a></li>
<li><a href="https://games-able.techidaily.com/visual-beats-integrating-tablets-into-games/"><u>Visual Beats: Integrating Tablets Into Games</u></a></li>
<li><a href="https://games-able.techidaily.com/simplifying-pc-gaming-with-steam-deck-remote-streaming/"><u>Simplifying PC Gaming with Steam Deck Remote Streaming</u></a></li>
<li><a href="https://games-able.techidaily.com/2024s-ddr5-master-cards-ranked/"><u>2024'S DDR5 Master Cards Ranked</u></a></li>
<li><a href="https://games-able.techidaily.com/steering-vs-touchscreen-choosing-the-right-gear-for-racers/"><u>Steering Vs. Touchscreen: Choosing the Right Gear for Racers</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-fixes-for-joy-con-connection-issues-with-nintendo-switch/"><u>Quick Fixes for Joy-Con Connection Issues with Nintendo Switch</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-friendly-gaming-xbox-series-xs-edition/"><u>Budget-Friendly Gaming: Xbox Series X/S Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-gaming-with-epic-and-steam-integration/"><u>Streamline Gaming with Epic and Steam Integration</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-comprehensive-guide-to-capturing-perfect-instagram-covers/"><u>2024 Approved  The Comprehensive Guide to Capturing Perfect Instagram Covers</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-enhancing-visuals-on-tiktok-the-digit-editing-guide/"><u>[Updated] 2024 Approved  Enhancing Visuals on TikTok  The Digit Editing Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-the-essence-of-meta-in-video-games-compliance-matters/"><u>What Is the Essence of Meta in Video Games? Compliance Matters</u></a></li>
<li><a href="https://games-able.techidaily.com/seamlessly-connect-steam-and-xbox-game-pass-via-glossi/"><u>Seamlessly Connect Steam & Xbox Game Pass via GlosSI</u></a></li>
<li><a href="https://games-able.techidaily.com/pushing-limits-upgrade-pc-csgo-performance/"><u>Pushing Limits: Upgrade PC CS:GO Performance</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionize-your-arcade-with-expansive-front-ends/"><u>Revolutionize Your Arcade with Expansive Front Ends!</u></a></li>
<li><a href="https://games-able.techidaily.com/become-a-pokemon-expert-iphone-and-ipad-gameplay-secrets/"><u>Become a Pokémon Expert: IPhone & iPad Gameplay Secrets</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-professionals-guide-to-photo-watermarking-solutions/"><u>In 2024, Professional's Guide to Photo Watermarking Solutions</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169347852-from-binges-to-battles-game-play-on-netflix/"><u>From Binges to Battles: Game Play on Netflix!</u></a></li>
<li><a href="https://games-able.techidaily.com/channel-management-excellence-perfecting-blockunblock-techniques-on-twitch/"><u>Channel Management Excellence: Perfecting Block/Unblock Techniques on Twitch</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-game-access-launcher-setup-on-steam-devices/"><u>Streamlining Game Access: Launcher Setup on Steam Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-asus-rog-allys-top-docking-stations-24/"><u>Unveiling ASUS ROG Ally's Top Docking Stations '24</u></a></li>
<li><a href="https://games-able.techidaily.com/reactivating-purchased-games-on-ps5-console/"><u>Reactivating Purchased Games on PS5 Console</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-for-people-wanting-to-mock-gps-on-itel-p40-devices-drfone-by-drfone-virtual/"><u>In 2024, For People Wanting to Mock GPS on Itel P40 Devices | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/5-ways-you-can-maintain-your-xbox-series-x-hardware/"><u>5 Ways You Can Maintain Your Xbox Series X Hardware</u></a></li>
<li><a href="https://games-able.techidaily.com/sonys-portable-entertainment-revealed/"><u>Sony’s Portable Entertainment Revealed</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-your-gaming-budget-in-ps-store/"><u>Boosting Your Gaming Budget in PS Store</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-androids-finest-10-free-video-editing-apps-without-watermarks/"><u>New Androids Finest 10 Free Video Editing Apps Without Watermarks</u></a></li>
</ul></div>

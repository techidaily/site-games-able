---
title: "Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN"
date: 2024-07-12T03:36:48.458Z
updated: 2024-07-13T03:36:48.458Z
tags:
  - games
categories:
  - games
description: "This Article Describes Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN"
excerpt: "This Article Describes Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN"
keywords: Chdman Game Optimization,Retro Game ISO Cut,Reduce Video Game Size,Squeeze Game Performance,CHDMAN ISO Editing,Low-Memory Gaming Techniques,Efficient Retro Graphics
thumbnail: https://thmb.techidaily.com/4dbf33f37ff64fa1cd0b3b86eb483d2b61e4dcfaa2f3492f28ea818842097e14.jpg
---

## Squeeze Life Out of Your Games: Retro ISO Reduction with CHDMAN

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
<li><a href="https://games-able.techidaily.com/the-economic-impact-of-a-psplus-gaming-pass/"><u>The Economic Impact of a PS+ Gaming Pass</u></a></li>
<li><a href="https://games-able.techidaily.com/the-great-debate-continues-best-for-rpi-batocera-or-retropie/"><u>The Great Debate Continues: Best for RPi – Batocera or RetroPie?</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-solve-switch-internet-disconnects/"><u>Steps to Solve Switch Internet Disconnects</u></a></li>
<li><a href="https://games-able.techidaily.com/top-white-gadgets-cost-effective-pc-parts-of-the-year/"><u>Top White Gadgets: Cost-Effective PC Parts of the Year</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/harnessing-the-power-of-influencers-in-tiktok-marketing/"><u>Harnessing the Power of Influencers in TikTok Marketing</u></a></li>
<li><a href="https://games-able.techidaily.com/sonic-sleuths-find-your-melodic-match-with-mobile-gaming/"><u>Sonic Sleuths: Find Your Melodic Match with Mobile Gaming</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-introduction-for-2024/"><u>[New] Introduction for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/optimize-zoom-performance-top-three-tactical-approaches/"><u>Optimize Zoom Performance  Top Three Tactical Approaches</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-and-controlling-xbox-game-bar-activity/"><u>Understanding and Controlling Xbox Game Bar Activity</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-elevating-your-visual-narrative-smart-editing-on-snapchat/"><u>In 2024, Elevating Your Visual Narrative  Smart Editing on Snapchat</u></a></li>
<li><a href="https://facebook.techidaily.com/controversial-features-in-todays-websites/"><u>Controversial Features in Today's Websites</u></a></li>
<li><a href="https://games-able.techidaily.com/easy-steps-to-enjoy-games-anywhere-anytime/"><u>Easy Steps to Enjoy Games Anywhere, Anytime</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-top-10-farming-games-to-kill-time-and-play-with-friends/"><u>[Updated] Top 10 Farming Games to Kill Time and Play with Friends</u></a></li>
<li><a href="https://games-able.techidaily.com/5-simple-steps-to-extend-switchs-service-life/"><u>5 Simple Steps to Extend Switch's Service Life</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-incorporating-borders-in-your-next-video-post/"><u>[New] 2024 Approved  Incorporating Borders in Your Next Video Post</u></a></li>
<li><a href="https://games-able.techidaily.com/advances-in-imaging-techniques-for-monitoring-neurocannabinoid-dynamics-in-real-time/"><u>Advances in Imaging Techniques for Monitoring Neurocannabinoid Dynamics in Real-Time</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-a-comprehensive-guide-standing-out-in-reddit-discussions/"><u>In 2024, A Comprehensive Guide  Standing Out in Reddit Discussions</u></a></li>
<li><a href="https://games-able.techidaily.com/the-joy-of-new-controls-upgrading-switchs-joystick/"><u>The Joy of New Controls: Upgrading Switch's Joystick</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-ultimate-guide-to-steam-pro-controllers-on-switch/"><u>[Updated] The Ultimate Guide to Steam Pro Controllers on Switch</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/in-2024-social-media-savvy-how-to-resize-vertical-videos-like-a-pro/"><u>In 2024, Social Media Savvy How to Resize Vertical Videos Like a Pro</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-ultimate-guide-to-hyperlapse-storytelling/"><u>2024 Approved  The Ultimate Guide to Hyperlapse Storytelling</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-listicle-of-premier-app-store-games-by-genres/"><u>The Ultimate Listicle of Premier App Store Games by Genres</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-apple-iphone-15-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>In 2024, Unlock Apple iPhone 15 With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-to-counteract-sagging-monitor-panels/"><u>Strategies to Counteract Sagging Monitor Panels</u></a></li>
<li><a href="https://games-able.techidaily.com/stealthy-storage-of-virtual-gems/"><u>Stealthy Storage of Virtual Gems</u></a></li>
<li><a href="https://games-able.techidaily.com/ai-chips-that-will-shape-our-future-at-computex-2024/"><u>AI Chips That Will Shape Our Future at Computex 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/7-reasons-why-mobile-gaming-actually-sucks/"><u>7 Reasons Why Mobile Gaming Actually Sucks</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-exclusive-guide-turning-fb-videos-into-mp4-and-hd/"><u>[New] 2024 Approved  Exclusive Guide  Turning FB Videos Into MP4 & HD</u></a></li>
<li><a href="https://games-able.techidaily.com/size-matters-in-computing-mini-vs-desktop-decisions/"><u>Size Matters in Computing: Mini Vs. Desktop Decisions</u></a></li>
<li><a href="https://games-able.techidaily.com/block-party-top-5-multiplayer-methods-with-friends-in-mc/"><u>Block Party: Top 5 Multiplayer Methods with Friends in MC</u></a></li>
<li><a href="https://games-able.techidaily.com/unraveling-robloxs-error-code-262/"><u>Unraveling Roblox's Error Code 262</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168463782-the-ultimate-arcade-upgrade-wide-front-panels/"><u>The Ultimate Arcade Upgrade: Wide Front Panels!</u></a></li>
<li><a href="https://games-able.techidaily.com/boost-your-gaming-pleasure-learn-5-mac-optimizations/"><u>Boost Your Gaming Pleasure - Learn 5 Mac Optimizations</u></a></li>
<li><a href="https://games-able.techidaily.com/choosing-your-ideal-elgato-stream-deck/"><u>Choosing Your Ideal Elgato Stream Deck</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-easy-video-editing-how-to-reverse-clips-in-final-cut-pro-2023-tutorial/"><u>Updated 2024 Approved Easy Video Editing How to Reverse Clips in Final Cut Pro 2023 Tutorial</u></a></li>
<li><a href="https://some-tips.techidaily.com/the-art-of-adding-podcasts-in-instagram-stories-for-2024/"><u>The Art of Adding Podcasts in Instagram Stories for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-gaming-aesthetics-and-function/"><u>Budget Gaming: Aesthetics and Function</u></a></li>
<li><a href="https://games-able.techidaily.com/499-for-expertise-start-with-moza-r5-bundle-review/"><u>$499 for Expertise Start with MOZA R5 Bundle Review</u></a></li>
<li><a href="https://games-able.techidaily.com/sitting-on-success-at-desks/"><u>Sitting on Success at Desks</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-fix-iphone-6s-plus-storage-not-loadingshowing-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Fix iPhone 6s Plus Storage Not Loading/Showing | Stellar</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Tecno Pop 8? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-to-ps5-remote-recovery/"><u>The Ultimate Guide to PS5 Remote Recovery</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-distinguishing-yourself-with-ingenious-tiktok-profile-ideas/"><u>[Updated] In 2024, Distinguishing Yourself with Ingenious TikTok Profile Ideas</u></a></li>
<li><a href="https://audio-editing.techidaily.com/pursuit-of-playful-audio-elements-for-2024/"><u>Pursuit of Playful Audio Elements for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-gaming-winner-innocn-39g1-r/"><u>Budget Gaming Winner: InnoCN 39G1 R</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-lets-go-back-in-time-seventh-ranked-activision-titles/"><u>Xbox, Let's Go Back in Time: Seventh-Ranked Activision Titles</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-translate-live-video-making-it-possible-with-the-best-tool/"><u>Updated 2024 Approved Translate Live Video Making It Possible With The Best Tool</u></a></li>
<li><a href="https://games-able.techidaily.com/desk-dwelling-gamers-delight/"><u>Desk Dwelling: Gamers’ Delight</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-data-disruptions-with-steam-image-backups/"><u>Avoid Data Disruptions with Steam Image Backups</u></a></li>
<li><a href="https://games-able.techidaily.com/shine-a-brighter-spotlight-on-your-xbox-console/"><u>Shine a Brighter Spotlight on Your Xbox Console</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-tecno-pova-5-pro-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Tecno Pova 5 Pro to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-gamers-graphically-glorious-reviews/"><u>[New] GAMER'S GRAPHICALLY GLORIOUS REVIEWS</u></a></li>
<li><a href="https://games-able.techidaily.com/the-road-ahead-haptic-grip-or-digital-direct-control/"><u>The Road Ahead: Haptic Grip or Digital Direct Control</u></a></li>
<li><a href="https://games-able.techidaily.com/disappear-your-xbox-noise-quickly/"><u>Disappear Your Xbox Noise Quickly</u></a></li>
<li><a href="https://games-able.techidaily.com/simplifying-xbox-360-slim-disassembly-a-practical-approach/"><u>Simplifying Xbox 360 Slim Disassembly: A Practical Approach</u></a></li>
</ul></div>

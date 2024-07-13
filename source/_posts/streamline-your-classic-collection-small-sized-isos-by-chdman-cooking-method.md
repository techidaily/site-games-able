---
title: "Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method"
date: 2024-07-12T03:52:21.678Z
updated: 2024-07-13T03:52:21.678Z
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-twitters-hot-takes-the-10-craziest-tweets/"><u>[New] 2024 Approved  Twitter's Hot Takes  The 10 Craziest Tweets</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-order-problems-quickly-on-steam/"><u>Addressing Order Problems Quickly on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/ace-your-game-night-3-best-stream-networks-on-switch/"><u>Ace Your Game Night: 3 Best Stream Networks on Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/5-essential-steps-to-transform-the-xbox-game-bar-interface-on-your-pc/"><u>5 Essential Steps to Transform the Xbox Game Bar Interface on Your PC</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173591886-seamless-controller-linking-on-switch-console-96-chars-slightly-over-but-its-close-enough-to-be-considered-within-the-limit-while-maintaining-relevance/"><u>Seamless Controller Linking on Switch Console (96 Chars) – Slightly over, but It's Close Enough to Be Considered Within the Limit While Maintaining Relevance</u></a></li>
<li><a href="https://games-able.techidaily.com/a-stellar-google-play-pass-with-a-tiny-hitch/"><u>A Stellar Google Play Pass with a Tiny Hitch</u></a></li>
<li><a href="https://games-able.techidaily.com/499-access-to-professional-level-sim-racing-moza-r5/"><u>$499 Access to Professional-Level Sim Racing - MOZA R5</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170601170-live-laugh-and-stream-with-twitch-app-on-the-go/"><u>Live, Laugh & Stream with Twitch App on the Go!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172093801-computer-slowdown-upgrade-nvidia-drivers/"><u>Computer Slowdown? Upgrade NVIDIA Drivers</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-joy-con-communication-breakdown-with-switch-device/"><u>Addressing Joy-Con Communication Breakdown with Switch Device</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-cutting-edge-techniques-for-setting-the-optimal-size-of-your-youtube-videos/"><u>[Updated] 2024 Approved  Cutting-Edge Techniques for Setting the Optimal Size of Your YouTube Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/7-captivating-terminal-games-for-linux-enthusiasts/"><u>7 Captivating Terminal Games for Linux Enthusiasts</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-a-beginners-journey-to-selecting-the-right-action-cam/"><u>2024 Approved  A Beginner’s Journey to Selecting the Right Action Cam</u></a></li>
<li><a href="https://games-able.techidaily.com/a-tale-of-windows-and-steamos-harmony-on-a-single-chip/"><u>A Tale of Windows & SteamOS Harmony on a Single Chip</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oppo-a58-4g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Oppo A58 4G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-gps-joystick-to-fake-gps-location-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>Complete Tutorial to Use GPS Joystick to Fake GPS Location On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169938014-top-15-pre-loaded-ios-games-fun-without-connections/"><u>Top 15 Pre-Loaded iOS Games: Fun WITHOUT Connections</u></a></li>
<li><a href="https://games-able.techidaily.com/acquiring-googles-console-style-gaming-experience-for-computer-use/"><u>Acquiring Google's Console-Style Gaming Experience for Computer Use</u></a></li>
<li><a href="https://games-able.techidaily.com/a-compreayer-look-at-top-rated-elgato-decks/"><u>A Compreayer Look at Top-Rated Elgato Decks</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprerans-guide-to-top-value-1440p-displays-for-every-gamers-wallet/"><u>A Compreran's Guide to Top Value 1440P Displays for Every Gamer's Wallet</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-instagram-artists-and-intellectual-property-rights/"><u>2024 Approved  Instagram Artists & Intellectual Property Rights</u></a></li>
<li><a href="https://games-able.techidaily.com/accessing-sonys-controller-with-pc-and-mac-devices/"><u>Accessing Sony's Controller with PC & Mac Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/50-quick-game-moments-best-20-fun-players-on-smartphones/"><u>50 Quick Game Moments: Best 20 Fun Players on Smartphones</u></a></li>
<li><a href="https://games-able.techidaily.com/achieving-smooth-control-transition-from-pc-mousekeyboard-to-steam-deck-via-barrier-technique/"><u>Achieving Smooth Control Transition From PC Mouse/Keyboard To Steam Deck via Barrier Technique</u></a></li>
<li><a href="https://games-able.techidaily.com/access-old-gaming-pics-on-windows-11-easy-guide/"><u>Access Old Gaming Pics on Windows 11 Easy Guide</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-mastering-tiktoks-elements-success/"><u>[New] 2024 Approved  Mastering TikTok's Elements Success</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-look-at-riots-username-and-slogan-change/"><u>A Comprehensive Look at Riot's Username and Slogan Change</u></a></li>
<li><a href="https://games-able.techidaily.com/30-fps-clarity-in-a-high-res-world-for-games/"><u>30 FPS Clarity in a High-Res World for Games</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-driving-traffic-a-guide-to-successful-tiktok-campaigns-for-2024/"><u>[New] Driving Traffic  A Guide to Successful TikTok Campaigns for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/delving-into-the-advantages-and-disadvantages-of-youtube-premium/"><u>Delving Into the Advantages and Disadvantages of YouTube Premium</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172675722-start-game-streaming-with-steam-on-meta-quest-now/"><u>Start Game Streaming with Steam on Meta Quest Now</u></a></li>
</ul></div>

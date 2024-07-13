---
title: "Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN"
date: 2024-07-12T04:33:51.143Z
updated: 2024-07-13T04:33:51.143Z
tags:
  - games
categories:
  - games
description: "This Article Describes Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN"
excerpt: "This Article Describes Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN"
keywords: Game Preservation,Balancing Gamers' Needs,Authentic Gaming Experience,Efficient Game Storage,CHDMAN Methods,Original Games Retention,Efficiency in Gaming
thumbnail: https://thmb.techidaily.com/533486c883f0e15f79a205d8fe00d7b629c80c76eca7c3b378cb3f9eeb4c0bbe.jpg
---

## Balance Efficiency & Authenticity: Preserving Original Games with CHDMAN

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
<li><a href="https://games-able.techidaily.com/avoid-scams-smart-management-of-your-switch-id/"><u>Avoid Scams: Smart Management of Your Switch ID</u></a></li>
<li><a href="https://games-able.techidaily.com/battlegrounds-of-history-top-11-strategy-titles-reviewed/"><u>Battlegrounds of History: Top 11 Strategy Titles Reviewed</u></a></li>
<li><a href="https://games-able.techidaily.com/before-you-join-linkedin-games-heres-why-to-be-wary/"><u>Before You Join LinkedIn Games - Here's Why to Be Wary</u></a></li>
<li><a href="https://games-able.techidaily.com/balancing-subscriptions-the-smart-xbox-players-way/"><u>Balancing Subscriptions: The Smart Xbox Player's Way</u></a></li>
<li><a href="https://games-able.techidaily.com/atlasos-for-the-vintage-tech-enthusiast/"><u>AtlasOS for the Vintage Tech Enthusiast</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweet-to-facebook-video-sharing-a-2023-perspective/"><u>Tweet-to-Facebook Video Sharing  A 2023 Perspective</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-magic-6-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor Magic 6 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-linkedins-latest-game-feature-it-might-not-be-that-fun-after-all/"><u>Avoid LinkedIn's Latest Game Feature - It Might Not Be That Fun After All</u></a></li>
<li><a href="https://games-able.techidaily.com/balancing-acts-in-tech-which-component-to-boost-cpu-or-gpu/"><u>Balancing Acts in Tech: Which Component to Boost, CPU or GPU?</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-update-your-drivers-on-windows-11-by-drivereasy-guide/"><u>Use Device Manager to update your drivers on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/an-enthusiasts-guide-to-favorite-offbeat-indie-games/"><u>An Enthusiast's Guide to Favorite, Offbeat Indie Games</u></a></li>
<li><a href="https://games-able.techidaily.com/behind-the-score-curtain-unveiling-review-hurdles/"><u>Behind the Score Curtain: Unveiling Review Hurdles</u></a></li>
<li><a href="https://games-able.techidaily.com/ai-influence-on-gaming-graphics-examining-nvidias-dlss-35/"><u>AI Influence on Gaming Graphics: Examining Nvidia's DLSS 3.5</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-video-editing-on-mac-how-to-install-lumafusion-and-its-best-alternatives-for-2024/"><u>New Video Editing on Mac How to Install Lumafusion and Its Best Alternatives for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/apple-silicon-and-windows-games-mastery-with-crossover-tools/"><u>Apple Silicon and Windows Games: Mastery with CrossOver Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-animation-in-instagram-stories-a-step-by-step-guide/"><u>[New] Mastering Animation in Instagram Stories  A Step-by-Step Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/akko-mod007b-hall-effect-keyboard-review-for-serious-gamers/"><u>Akko MOD007B Hall Effect Keyboard Review: For Serious Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-game-over-top-10-reasons-games-crash-and-how-to-prevent-them/"><u>Avoid Game Over: Top 10 Reasons Games Crash and How to Prevent Them</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-ultimate-guide-the-leading-7-nft-conversion-services/"><u>In 2024, Ultimate Guide  The Leading 7 NFT Conversion Services</u></a></li>
<li><a href="https://games-able.techidaily.com/beat-the-heat-8-sizzling-ar-games/"><u>Beat the Heat - 8 Sizzling AR Games</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-incompatibility-in-your-next-pc-buy/"><u>Avoiding Incompatibility in Your Next PC Buy</u></a></li>
<li><a href="https://games-able.techidaily.com/best-practices-for-parents-about-discord-usage/"><u>Best Practices for Parents About Discord Usage</u></a></li>
<li><a href="https://games-able.techidaily.com/beatbox-battleground-pen-proves-precision-win/"><u>Beatbox Battleground: Pen Proves Precision Win</u></a></li>
<li><a href="https://extra-information.techidaily.com/lgs-ultrafine-vision-a-thorough-4k-screen-evaluation/"><u>LG's UltraFine Vision  A Thorough 4K Screen Evaluation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-linguistic-linkers-the-premier-list-for-offline-recognition-devices-for-2024/"><u>[Updated] Linguistic Linkers  The Premier List for Offline Recognition Devices for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/amplify-your-channels-impact-with-the-leading-7-twitch-bot-allies/"><u>Amplify Your Channel's Impact with the Leading 7 Twitch Bot Allies</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-step-by-step-iphone-screen-recording/"><u>[New] 2024 Approved  Step-by-Step Iphone Screen Recording</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-samsung-galaxy-m14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Samsung Galaxy M14 5G? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/are-gaming-chips-poised-for-higher-fees-soon/"><u>Are Gaming Chips Poised for Higher Fees Soon?</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-luxury-for-your-virtual-journey/"><u>Affordable Luxury for Your Virtual Journey</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-failures-restoring-java-on-windows-devices/"><u>Resolving Failures: Restoring Java on Windows Devices</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2023s-leading-browser-extensions-for-video-streaming/"><u>2023'S Leading Browser Extensions for Video Streaming</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-game-installation-oversight-by-steam/"><u>Avoiding Game Installation Oversight by Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/android-apps-on-linux-a-step-by-step-guide/"><u>Android Apps on Linux – A Step by Step Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-itel-a60s-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Itel A60s? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://games-able.techidaily.com/audio-control-a-guide-to-peaceful-gaming-experience/"><u>Audio Control: A Guide to Peaceful Gaming Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/become-a-premier-team-boss-playing-manager-cheaply-on-windows/"><u>Become a Premier Team Boss: Playing Manager Cheaply on Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/behind-the-scenes-repairing-your-own-xbox-sensors/"><u>Behind-the-Scenes: Repairing Your Own Xbox Sensors</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-ultimate-roguelike-rankings-the-best-10-games/"><u>2024 Approved  Ultimate Roguelike Rankings  The Best 10 Games</u></a></li>
<li><a href="https://games-able.techidaily.com/backtracking-xbox-series-xs-controller-update/"><u>Backtracking Xbox Series X/S Controller Update</u></a></li>
<li><a href="https://games-able.techidaily.com/best-gathering-titles-top-16-seated-players-games-on-xbox/"><u>Best Gathering Titles: Top 16 Seated Players' Games on Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/become-a-controller-gaming-connoisseur-androids-button-magic/"><u>Become a Controller Gaming Connoisseur: Android's Button Magic</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-perfect-slideshow-software-for-iphone-fi-and-pro-max/"><u>2024 Approved  Perfect Slideshow Software For iPhone Fi & Pro Max</u></a></li>
<li><a href="https://extra-resources.techidaily.com/hidden-gems-the-top-10-websites-offering-mystery-box-deals/"><u>Hidden Gems  The Top 10 Websites Offering Mystery Box Deals</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-best-cartoon-video-maker-apps-for-android-and-ios-devices/"><u>In 2024, Best Cartoon Video Maker Apps for Android and iOS Devices</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-drone-stability-guide-high-ranking-gimbals/"><u>2024 Approved  Drone Stability Guide  High-Ranking Gimbals</u></a></li>
<li><a href="https://games-able.techidaily.com/best-of-both-worlds-15-unique-mobile-dual-play-games/"><u>Best of Both Worlds: 15 Unique Mobile Dual Play Games</u></a></li>
</ul></div>

---
title: "ChDMan to the Rescue: Tailoring Old Games for Modern Storage"
date: 2024-07-12T03:33:11.620Z
updated: 2024-07-13T03:33:11.620Z
tags:
  - games
categories:
  - games
description: "This Article Describes ChDMan to the Rescue: Tailoring Old Games for Modern Storage"
excerpt: "This Article Describes ChDMan to the Rescue: Tailoring Old Games for Modern Storage"
keywords: Old Game Adaptation,Classic Games Update,Retro Gaming Revival,Nostalgic Game Refresh,Historical Games Preservation,Vintage Games Modernization,Storage-Friendly Games
thumbnail: https://thmb.techidaily.com/d021ea19d35ef3673abfe0bc9bdff457eb34791e55514d7bc0ce5bafaca00aee.jpg
---

## ChDMan to the Rescue: Tailoring Old Games for Modern Storage

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
<li><a href="https://games-able.techidaily.com/tackle-ps4-network-glitches-8-must-try-fixes-explored/"><u>Tackle PS4 Network Glitches: 8 Must-Try Fixes Explored</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/in-2024-time-lapse-made-easy-2-proven-methods-for-creating-breathtaking-videos/"><u>In 2024, Time Lapse Made Easy 2 Proven Methods for Creating Breathtaking Videos</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-top-digital-software-for-cleaning-audio-recordings/"><u>New 2024 Approved Top Digital Software for Cleaning Audio Recordings</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/tips-for-fixing-stalled-video-posts-on-the-social-media-platform-iosandroid/"><u>Tips for Fixing Stalled Video Posts on the Social Media Platform iOS/Android</u></a></li>
<li><a href="https://games-able.techidaily.com/sparkle-science-keeping-your-ps5-spotless/"><u>Sparkle Science: Keeping Your PS5 Spotless</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/explore-the-best-ios-options-to-simulate-your-favorite-psp-classics-for-2024/"><u>Explore the Best iOS Options to Simulate Your Favorite PSP Classics for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-lock-on-your-apple-iphone-11-and-ipad-by-drfone-ios/"><u>In 2024, How to Unlock iCloud lock on your Apple iPhone 11 and iPad?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-digital-rights-unexpected-content-take-downs/"><u>[Updated] 2024 Approved  Digital Rights  Unexpected Content Take-Downs</u></a></li>
<li><a href="https://games-able.techidaily.com/pros-in-the-making-investing-in-high-end-gear/"><u>Pros in the Making: Investing in High-End Gear</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-ps5-networking-your-wi-fi-problems-guide/"><u>Mastering PS5 Networking: Your Wi-Fi Problems Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-enriching-youtube-channels-amp-up-with-songs/"><u>[New] 2024 Approved  Enriching Youtube Channels  Amp up with Songs</u></a></li>
<li><a href="https://games-able.techidaily.com/procedural-patterns-shaping-video-game-universes/"><u>Procedural Patterns: Shaping Video Game Universes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-xiaomi-civi-3-lock-screen-password-by-drfone-android/"><u>How To Change Xiaomi Civi 3 Lock Screen Password?</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-crafting-a-balanced-narrative-with-b-roll-content/"><u>2024 Approved  Crafting a Balanced Narrative with B-Roll Content</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-xiaomi-redmi-note-12r-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Xiaomi Redmi Note 12R</u></a></li>
<li><a href="https://games-able.techidaily.com/silence-speakers-amplify-headphones-on-console/"><u>Silence Speakers, Amplify Headphones on Console</u></a></li>
<li><a href="https://games-able.techidaily.com/six-no-cost-gaming-experiences-worth-exploring/"><u>Six No-Cost Gaming Experiences Worth Exploring</u></a></li>
<li><a href="https://games-able.techidaily.com/from-solo-existence-to-group-adventures-fixing-minecraft-lan-disconnects/"><u>From Solo Existence to Group Adventures - Fixing Minecraft LAN Disconnects</u></a></li>
<li><a href="https://games-able.techidaily.com/ultra-low-price-caps-lock-and-scroll-options/"><u>Ultra-Low-Price Caps Lock & Scroll Options</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-nine-crucial-nintendo-switch-tips/"><u>The Ultimate Guide: Nine Crucial Nintendo Switch Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/fortnite-lovers-mac-users-uncover-the-restrictions/"><u>Fortnite Lovers, Mac Users! Uncover the Restrictions</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-takeaways-from-the-best-ogg-converter-for-2024/"><u>New Takeaways From the Best OGG Converter for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/optic-power-vs-mechanical-might-in-gaming/"><u>Optic Power Vs. Mechanical Might in Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/optimized-multi-port-adapters-for-playstation-5-users/"><u>Optimized Multi-Port Adapters for PlayStation 5 Users</u></a></li>
<li><a href="https://games-able.techidaily.com/online-games-unfolding-a-look-at-the-transformation/"><u>Online Games Unfolding: A Look at the Transformation</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-galaxy-f04-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Galaxy F04?</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-change-regions-on-your-nintendo-switch/"><u>How to Change Regions on Your Nintendo Switch</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-watermark-videos-without-breaking-the-bank-top-5-free-tools-for-2024/"><u>Updated Watermark Videos without Breaking the Bank Top 5 Free Tools for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/quicken-gameplay-quality-fixing-low-windows-fps/"><u>Quicken Gameplay Quality: Fixing Low Window's FPS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-gain-on-ig-unveiling-high-payoff-content-strategies/"><u>2024 Approved  Gain on IG  Unveiling High-Payoff Content Strategies</u></a></li>
<li><a href="https://games-able.techidaily.com/opera-users-guide-to-unlimited-discord-time/"><u>Opera Users' Guide to Unlimited Discord Time</u></a></li>
<li><a href="https://games-able.techidaily.com/this-app-lets-you-play-nintendo-classics-on-your-iphone-heres-how/"><u>This App Lets You Play Nintendo Classics on Your iPhone: Here's How</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-ultimate-guide-to-using-vlc-from-mpeg-4-to-all-media-types/"><u>The Ultimate Guide to Using VLC  From MPEG-4 to All Media Types</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-realme-narzo-60-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Realme Narzo 60 5G? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-sea-of-players-steams-secret/"><u>Navigating the Sea of Players: Steam's Secret</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-join-the-dance-of-success-top-10-crowning-challenges-in-tiktok/"><u>[New] In 2024, Join the Dance of Success  Top 10 Crowning Challenges in TikTok</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-quick-guide-applying-discord-spoiler-tags-right/"><u>[New] Quick Guide  Applying Discord Spoiler Tags Right</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-lava-blaze-2-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Lava Blaze 2? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/tactile-triumphs-phones-or-larger-screens-for-play/"><u>Tactile Triumphs: Phones or Larger Screens for Play</u></a></li>
<li><a href="https://games-able.techidaily.com/integration-challenge-switch-oled-and-past-docks/"><u>Integration Challenge: Switch OLED and Past Docks</u></a></li>
<li><a href="https://games-able.techidaily.com/protecting-personal-progress-implementing-passcode-on-your-switch/"><u>Protecting Personal Progress: Implementing Passcode on Your Switch</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-effortless-video-editing-how-to-change-aspect-ratios-quickly/"><u>Updated In 2024, Effortless Video Editing How to Change Aspect Ratios Quickly</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-play-the-nyt-relationship-chess-game/"><u>How to Play the NYT Relationship Chess Game</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-stock-stabilized-expecting-pricing-changes/"><u>PS5 Stock Stabilized: Expecting Pricing Changes</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-steams-content-conflux-on-mac/"><u>Overcoming Steam's Content Conflux on Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/rom-localization-made-simple-language-patch-guide/"><u>Rom Localization Made Simple: Language Patch Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/merging-and-editing-footage-on-iphone/"><u>Merging and Editing Footage on iPhone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-8-top-video-screen-grabbers/"><u>[New] In 2024, 8 Top Video Screen Grabbers</u></a></li>
<li><a href="https://games-able.techidaily.com/get-ready-to-play-chatgpt-introduces-its-6-intense-games/"><u>Get Ready To Play: ChatGPT Introduces Its 6 Intense Games</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-boredom-to-laughter-your-kinemaster-guide/"><u>[Updated] From Boredom to Laughter  Your KineMaster Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-xbox-golds-shift-to-game-pass-inclusion/"><u>Understanding Xbox Gold's Shift to Game Pass Inclusion</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-on-apple-iphone-15-plus-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID On Apple iPhone 15 Plus without Password?</u></a></li>
<li><a href="https://games-able.techidaily.com/the-intersection-of-hrtf-and-gameplay-precision-in-valorant/"><u>The Intersection of HRTF and Gameplay Precision in Valorant</u></a></li>
<li><a href="https://games-able.techidaily.com/metaquest-3-the-ultimate-virtual-adventure/"><u>MetaQuest 3: The Ultimate Virtual Adventure</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-the-best-ai-naming-assistants-for-podcast-innovation/"><u>[New] In 2024, The Best AI Naming Assistants for Podcast Innovation</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-comedy-chorus-satirical-song-selections/"><u>[New] Comedy Chorus  Satirical Song Selections</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-samsung-galaxy-a15-5g-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Samsung Galaxy A15 5G Phone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-streamline-your-writing-process-transcribing-with-microsoft-word/"><u>[Updated] Streamline Your Writing Process  Transcribing with Microsoft Word</u></a></li>
<li><a href="https://games-able.techidaily.com/high-stakes-for-virtual-worlds-four-driving-cost-factors/"><u>High Stakes for Virtual Worlds: Four Driving Cost Factors</u></a></li>
<li><a href="https://games-able.techidaily.com/meet-the-new-nvidia-application-amplifying-games/"><u>Meet the New Nvidia Application Amplifying Games</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-from-novice-to-expert-advanced-screencasting-steps/"><u>2024 Approved  From Novice to Expert  Advanced Screencasting Steps</u></a></li>
</ul></div>

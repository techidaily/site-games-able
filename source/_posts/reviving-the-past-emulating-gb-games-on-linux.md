---
title: "Reviving the Past: Emulating GB Games on Linux"
date: 2024-08-22T22:25:23.193Z
updated: 2024-08-23T22:25:23.193Z
tags:
  - games
categories:
  - games
description: "This Article Describes Reviving the Past: Emulating GB Games on Linux"
excerpt: "This Article Describes Reviving the Past: Emulating GB Games on Linux"
keywords: Revive Old Games,GBA Console Re-Create,Linux Game Porting,Retro PC Gaming,Legacy Game Emulation,Historical Game Launcher,Linux Emulator GB
thumbnail: https://thmb.techidaily.com/1e40e68e85695875cbdf7c309b6e95c0f93def47629f17026d118c0eda7b469c.png
---

## Reviving the Past: Emulating GB Games on Linux

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

## Why Emulate a Game Boy in the Terminal?

![pokemon red star splash screen in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/pokemon-red-star-splash-screen-in-the-linux-terminal.jpg)

 Nintendo's Game Boy is one of the most wildly successful game consoles ever created, and introduced generations of kids and adults to the joys of games such as Tetris, Pokemon, and the Super Mario Land series.

 With its 4MHz processor and 47x43mm display, the Game Boy could easily fit in your trouser pocket and offered around 15 hours of gameplay from four AA batteries. In the late 1980s and early 1990s, the Game Boy was a must-have accessory for any teenager, and utterly dominated the portable gaming market.

 The console's popularity and longevity meant that there were thousands of officially licensed Game Boy games, with many more hacked together by bedroom tinkerers.

 By running an emulator in your terminal, you can run every single one of these, transforming your terminal into an extensive library of playable games.

 As the name suggests, php-terminal-gameboy-emulator is written in PHP—a language[usually used to create websites](https://www.makeuseof.com/tag/build-simple-php-website/) —and although the project's readme only states that it supports PHP 5.6, PHP 7, and HHVM, we've had it running almost flawlessly on PHP versions up to 8.2.

 With php-terminal-gameboy-emulator, you're not limited to your computer either and can run sessions over[Secure Shell (SSH)](https://www.makeuseof.com/learn-how-to-manage-remote-access-via-ssh/) on remote machines.

 Because it's running in a terminal, your Game Boy games won't have any sound, but we're sure you can hum the Tetris theme tune.

 You also won't be able to save games. If these limitations are too restrictive, there are dozens of excellent emulators available on Linux.

 You should only use ROMS you legally own. You can find a huge variety of homebrew Game Boy ROMS at[Homebrew Hub](https://hh.gbdev.io/) .

## How to Install php-terminal-gameboy-emulator on Linux

 Before you install php-terminal-gameboy-emulator, you should first make sure you have PHP installed. To check this, open a terminal and enter:

`php -v`

 This command should return the version number of your installed PHP package. If it returns "php: command not found", you do not have PHP installed.

To install PHP on Arch and related distros, enter:

`sudo pacman -S php`

On Debian and its derivatives:

`sudo apt install php`

For the Fedora family, you first need to add the Remi PHP repository:

`sudo dnf -y install http://rpms.remirepo.net/fedora/remi-release-XX.rpm`

 ...where**XX** is your Fedora version number. Now enable the repository:

`sudo dnf module enable php:remi-8.1 -y`

Finally, you can install PHP with:

`sudo dnf install php -y`

 Now PHP is installed, use the**wget** tool to download php-terminal-gameboy-emulator:

`wget https://raw.githubusercontent.com/gabrielrcouto/php-terminal-gameboy-emulator/master/bin/php-gameboy.phar`

Make it executable with:

`sudo chmod +x php-gameboy.phar`

 Move the binary to your path so it's executable from anywhere on your system;

`sudo mv php-gameboy.phar /usr/local/bin/php-gameboy`

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
## Play Awesome Game Boy Games in Your Linux Terminal

 To start a game with php-terminal-gameboy-emulator, you need to pass the filename of the ROM file as an argument. For instance:

`php-gameboy ~/gbroms/tetris.gb`

 The ROM will load almost instantly, and you'll be faced with the familiar grayscale splash screen of whatever game you choose.

 In the video below you can see that the emulator is quite capable of running Street Fighter II and that this writer is just as handy with with the terminal version as he is with the genuine handheld—convincingly controlling Ryu to beat Guile in the first round.

 You'll also notice that while php-terminal-gameboy-emulator does a convincing job of recreating the Game Boy's dot matrix screen in your terminal, there are occasional visual artifacts. How often these appear, and their seriousness will depend on the game you're playing.

 The emulator controls are as follows, and unfortunately can't be remapped:

| Keyboard Controls | Console Controls |
| ----------------- | ---------------- |
| WASD              | D-Pad directions |
| Comma (,)         | A                |
| Dot (.)           | B                |
| N                 | Select           |
| M                 | Start            |

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Impress Your Friends With php-terminal-gameboy-emulator

 Playing action, fighting, and adventure games from within the Linux terminal is a technical feat that's sure to inspire your colleagues and relations, and can be an excellent way to convince them of Linux's pre-eminence as a gaming system.

 You can also use it as a way to relive your childhood in some idle downtime when you're working.


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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-download-facebook-videos-swiftly-discover-the-top-10-android-downloader-tools/"><u>[New] 2024 Approved  Download Facebook Videos Swiftly  Discover the Top 10 Android Downloader Tools</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-the-smart-way-to-store-video-meetings-on-devices/"><u>[New] In 2024, The Smart Way to Store Video Meetings on Devices</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-the-art-of-perfection-in-depth-tutorial-on-utilizing-photoshops-background-eraser-tool/"><u>[Updated] 2024 Approved  The Art of Perfection  In-Depth Tutorial on Utilizing Photoshop's Background Eraser Tool</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-5-next-level-editors-to-transcend-the-standard-youtube-videos/"><u>[Updated] 5 Next-Level Editors to Transcend the Standard Youtube Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-improve-your-videography-the-itunes-way/"><u>[Updated] Improve Your Videography  The iTunes Way</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-unparalleled-selection-of-8-android-multiparty-tools/"><u>[Updated] In 2024, Unparalleled Selection of 8 Android Multiparty Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-the-trap-of-tricksy-traffic-instagrams-hidden-hazard/"><u>[Updated] The Trap of Tricksy Traffic  Instagram's Hidden Hazard</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-thriving-financially-with-youtube-advertising-techniques/"><u>[Updated] Thriving Financially with YouTube Advertising Techniques</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-top-5-best-ps1-emulators-for-pc-for-2024/"><u>[Updated] Top 5 Best Ps1 Emulators for PC for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-10-igtv-talents-ready-to-take-off/"><u>2024 Approved  10 IGTV Talents Ready to Take Off</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-expert-tricks-instant-clearance-of-ssgnature-backdrops/"><u>2024 Approved  Expert Tricks  Instant Clearance of Ssgnature Backdrops</u></a></li>
<li><a href="https://games-able.techidaily.com/android-application-transition-to-linux-devices/"><u>Android Application Transition to Linux Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-big-picture-breakdown-in-steam-gaming/"><u>Avoiding Big Picture Breakdown in Steam Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/boost-your-skills-elevating-performance-and-resolving-valorants-fps-problems-windows-edition/"><u>Boost Your Skills: Elevating Performance & Resolving Valorant's FPS Problems, Windows Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/bridge-between-smartphones-and-pc-google-play-games-explained/"><u>Bridge Between Smartphones and PC: Google Play Games Explained</u></a></li>
<li><a href="https://games-able.techidaily.com/connect-xbox-to-laptop-monitor-for-enhanced-gaming/"><u>Connect Xbox to Laptop Monitor for Enhanced Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/connecting-controllers-perfectly-on-android-platforms/"><u>Connecting Controllers Perfectly on Android Platforms</u></a></li>
<li><a href="https://games-able.techidaily.com/deciphering-gamings-meta-meaning-and-adherence/"><u>Deciphering Gaming's Meta: Meaning & Adherence</u></a></li>
<li><a href="https://games-able.techidaily.com/digital-discounts-on-xbox-series-xs-unlocked/"><u>Digital Discounts on Xbox Series X|S Unlocked!</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-gameplay-and-monetization-top-7-bots-for-twitch-enthusiasts/"><u>Elevate Gameplay & Monetization - Top 7 Bots for Twitch Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172767277-enhance-csgo-on-pc-10-frames-up/"><u>Enhance CS:GO on PC - 10 Frames Up!</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-tips-for-steam-image-redundancy/"><u>Essential Tips for Steam Image Redundancy</u></a></li>
<li><a href="https://win-answers.techidaily.com/euro-truck-simulator-2-eliminating-your-system-crash-issues-on-the-desktop-computer/"><u>Euro Truck Simulator 2 - Eliminating Your System Crash Issues on the Desktop Computer'</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-the-future-of-gaming-with-amd-rdna-35/"><u>Exploring the Future of Gaming with AMD RDNA 3.5</u></a></li>
<li><a href="https://extra-information.techidaily.com/fiscal-flyers-top-5-low-cost-aerial-vehicles/"><u>Fiscal Flyers  Top 5 Low-Cost Aerial Vehicles</u></a></li>
<li><a href="https://games-able.techidaily.com/gifting-games-from-steam-a-guide-for-friends/"><u>Gifting Games From Steam: A Guide for Friends</u></a></li>
<li><a href="https://fox-helps.techidaily.com/high-def-gaming-gpu-recommendations/"><u>High-Def Gaming GPU Recommendations</u></a></li>
<li><a href="https://games-able.techidaily.com/high-speed-typing-and-the-quest-for-optimal-pace/"><u>High-Speed Typing and the Quest for Optimal Pace</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-deal-with-insufficient-ram-notice-roblox-on-iphone/"><u>How to Deal with Insufficient RAM Notice (Roblox) on iPhone</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-fix-error-4013-while-updating-or-restoring-your-iphone/"><u>How to Fix Error 4013 While Updating or Restoring Your iPhone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-a-damaged-video-file-of-realme-gt-5-pro-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair a Damaged video file of Realme GT 5 Pro using Video Repair Utility on Windows?</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-xs-max-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone XS Max Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ideal-accessories-for-optimal-gopro-photography/"><u>Ideal Accessories for Optimal GoPro Photography</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-get-rid-of-filmora-watermark-with-or-without-subscription/"><u>In 2024, Get Rid of Filmora Watermark With or Without Subscription</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-integrating-subtitles-into-your-online-social-videography-efforts/"><u>In 2024, Integrating Subtitles Into Your Online Social Videography Efforts</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-is-coqui-voice-cloning-worth-the-hype-a-comprehensive-review/"><u>In 2024, Is Coqui Voice Cloning Worth the Hype? A Comprehensive Review</u></a></li>
<li><a href="https://extra-information.techidaily.com/internet-laughter-fabricator/"><u>Internet Laughter Fabricator</u></a></li>
<li><a href="https://games-able.techidaily.com/is-ea-play-an-economically-sound-choice/"><u>Is EA Play an Economically Sound Choice?</u></a></li>
<li><a href="https://games-able.techidaily.com/linkedin-has-added-games-but-heres-why-you-shouldnt-play-them/"><u>LinkedIn Has Added Games, but Here's Why You Shouldn't Play Them</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-photo-background-removal-techniques-for-2024/"><u>Mastering Photo Background Removal Techniques for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/mastering-snapchat-photo-edits-a-step-by-step-guide/"><u>Mastering Snapchat Photo Edits  A Step-by-Step Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-headset-use-on-xbox-series-xs/"><u>Maximizing Headset Use on Xbox Series X/S</u></a></li>
<li><a href="https://games-able.techidaily.com/methods-for-mending-windows-oculus-app-issues/"><u>Methods for Mending Windows Oculus App Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-ps5-connectivity-wi-fi-troubleshooting-steps/"><u>Navigating PS5 Connectivity: Wi-Fi Troubleshooting Steps</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/netflix-picture-in-picture-how-to-use-the-netflix-floating-window-feature-for-2024/"><u>Netflix Picture-in-Picture - How to Use the Netflix Floating Window Feature for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-create-unforgettable-moments-best-online-collage-makers-for-2024/"><u>New Create Unforgettable Moments Best Online Collage Makers for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/no-spinning-discs-no-stress-on-your-series-x/"><u>No Spinning Discs, No Stress! On Your Series X</u></a></li>
<li><a href="https://games-able.techidaily.com/optimal-high-refresh-monitor-selection/"><u>Optimal High Refresh Monitor Selection</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-shortage-solved-will-prices-decrease-soon/"><u>PS5 Shortage Solved: Will Prices Decrease Soon?</u></a></li>
<li><a href="https://games-able.techidaily.com/rediscovering-the-magic-in-each-game-session/"><u>Rediscovering the Magic in Each Game Session</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-epics-launcher-stutterfreeze-woes-on-pc/"><u>Resolving Epic's Launcher Stutter/Freeze Woes on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/slash-steams-memory-usage-here-are-5-proven-methods/"><u>Slash Steam's Memory Usage - Here Are 5 Proven Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-quiet-voice-use-in-multiplayer-play/"><u>Strategies for Quiet Voice Use in Multiplayer Play</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-the-process-of-finding-steam-id/"><u>Streamlining the Process of Finding Steam ID</u></a></li>
<li><a href="https://games-able.techidaily.com/suitability-of-ps3-games-for-ps4-system/"><u>Suitability of PS3 Games for PS4 System</u></a></li>
<li><a href="https://games-able.techidaily.com/the-5-features-we-loved-on-the-new-lenovo-legion-go-at-ifa-2023/"><u>The 5 Features We Loved on the New Lenovo Legion Go at IFA 2023</u></a></li>
<li><a href="https://games-able.techidaily.com/the-complete-list-of-ps-vr2-accessories/"><u>The Complete List of PS VR2 Accessories</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-smart-approach-to-video-marketing-for-smbs-for-2024/"><u>The SMART Approach to Video Marketing for SMBs for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-game-mouse-checklist-a-focus-on-five-standout-qualities/"><u>The Ultimate Game Mouse Checklist: A Focus on Five Standout Qualities</u></a></li>
<li><a href="https://games-able.techidaily.com/to-subscribe-or-not-to-subscribe-the-price-dilemnium-of-ea-play/"><u>To Subscribe or Not to Subscribe: The Price Dilemnium of EA Play</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-steam-big-picture-and-solving-problems/"><u>Troubleshooting Steam Big Picture and Solving Problems</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-riots-user-name-revision-procedures/"><u>Understanding Riot's User Name Revision Procedures</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-xps-movie-magic-software-essentials-for-2024/"><u>Unlock XP's Movie Magic Software Essentials for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/unraveling-the-best-twitch-video-extraction-services-5/"><u>Unraveling the Best Twitch Video Extraction Services #5</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-5-best-online-tone-generators-free-and-simple-for-2024/"><u>Updated 5 Best Online Tone Generators Free & Simple for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/upgrade-your-mobile-gameplay-on-iphoneipad-with-these-leaders/"><u>Upgrade Your Mobile Gameplay on iPhone/iPad with These Leaders</u></a></li>
<li><a href="https://games-able.techidaily.com/why-video-game-delays-are-a-good-thing/"><u>Why Video Game Delays Are a Good Thing</u></a></li>
<li><a href="https://games-able.techidaily.com/win1111s-dxgierror-0x887a0006-unlock-your-device/"><u>Win11/11's DXGI_ERROR 0X887A0006: Unlock Your Device</u></a></li>
</ul></div>

---
title: Retro Gaming Revelations with Terminal Scripting
date: 2024-07-12T04:14:42.826Z
updated: 2024-07-13T04:14:42.826Z
tags:
  - games
categories:
  - games
description: This Article Describes Retro Gaming Revelations with Terminal Scripting
excerpt: This Article Describes Retro Gaming Revelations with Terminal Scripting
keywords: Retro Game Scripts,Terminal Gaming Guide,Gaming Terminals,Scripted Games Revival,Retro Gaming Techniques,Terminal Console Fun,Vintage Gaming Tips
thumbnail: https://thmb.techidaily.com/053654aac9195ea45d1f77852c408a3b2770cc6c802ff6728e9e3d8c452deddb.jpg
---

## Retro Gaming Revelations with Terminal Scripting

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

## Why Emulate a Game Boy in the Terminal?

![pokemon red star splash screen in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/pokemon-red-star-splash-screen-in-the-linux-terminal.jpg)

 Nintendo's Game Boy is one of the most wildly successful game consoles ever created, and introduced generations of kids and adults to the joys of games such as Tetris, Pokemon, and the Super Mario Land series.

 With its 4MHz processor and 47x43mm display, the Game Boy could easily fit in your trouser pocket and offered around 15 hours of gameplay from four AA batteries. In the late 1980s and early 1990s, the Game Boy was a must-have accessory for any teenager, and utterly dominated the portable gaming market.

 The console's popularity and longevity meant that there were thousands of officially licensed Game Boy games, with many more hacked together by bedroom tinkerers.

 By running an emulator in your terminal, you can run every single one of these, transforming your terminal into an extensive library of playable games.

 As the name suggests, php-terminal-gameboy-emulator is written in PHP—a language [usually used to create websites](https://www.makeuseof.com/tag/build-simple-php-website/) —and although the project's readme only states that it supports PHP 5.6, PHP 7, and HHVM, we've had it running almost flawlessly on PHP versions up to 8.2.

 With php-terminal-gameboy-emulator, you're not limited to your computer either and can run sessions over [Secure Shell (SSH)](https://www.makeuseof.com/learn-how-to-manage-remote-access-via-ssh/) on remote machines.

 Because it's running in a terminal, your Game Boy games won't have any sound, but we're sure you can hum the Tetris theme tune.

 You also won't be able to save games. If these limitations are too restrictive, there are dozens of excellent emulators available on Linux.

 You should only use ROMS you legally own. You can find a huge variety of homebrew Game Boy ROMS at [Homebrew Hub](https://hh.gbdev.io/) .

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
<li><a href="https://games-able.techidaily.com/top-10-free-online-fps-games-for-web-browsers/"><u>Top 10 Free Online FPS Games for Web Browsers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-echoes-in-motion-mac-for-sound-artists/"><u>[New] 2024 Approved  Echoes in Motion  Mac for Sound Artists</u></a></li>
<li><a href="https://games-able.techidaily.com/expert-guide-resolving-display-driver-failed-errors-on-windows-11/"><u>Expert Guide: Resolving Display Driver Failed Errors on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/demystifying-the-issue-windows-error-30005-file-failure/"><u>Demystifying the Issue: Windows' Error 30005 File Failure</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-unlocking-the-full-potential-of-screen-capture-techniques-for-2024/"><u>[New] Unlocking the Full Potential of Screen Capture Techniques for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/learn-from-my-oled-faux-pas-smart-screen-selection/"><u>Learn From My OLED Faux Pas: Smart Screen Selection</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-set-up-a-passcode-on-your-ps5/"><u>How to Set Up a Passcode on Your PS5</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-vivo-y36i-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Vivo Y36i Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/beginners-guide-to-pick-the-best-movie-maker-software-for-mac/"><u>Beginners Guide to Pick the Best Movie Maker Software for Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-universally-turn-off-controller-vibration-on-your-xbox-series-xs/"><u>How to Universally Turn Off Controller Vibration on Your Xbox Series X|S</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-gain-an-edge-in-views-with-these-5-youtube-thumbnail-creators/"><u>[Updated] 2024 Approved  Gain an Edge in Views with These 5 YouTube Thumbnail Creators</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-from-your-apple-iphone-xs-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud From your Apple iPhone XS</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-strategizing-with-snapshots-a-guide-to-instagram-video-marketing/"><u>[Updated] 2024 Approved  Strategizing with Snapshots  A Guide to Instagram Video Marketing</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-if-you-are-a-free-video-editor-being-a-windows-user-vsdc-free-video-editor-is-a-great-choice-but-is-it-the-best-video-editor-you-shoul/"><u>Updated 2024 Approved If You Are a Free Video Editor Being a Windows User, VSDC Free Video Editor Is a Great Choice. But Is It the Best Video Editor You Should Use? Find Out From Our VSDC Free Video Editor Review</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-shell-the-creme-de-la-creme-case-2024/"><u>Ultimate Shell: The Crème De La Crème Case, 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-ps5s-sparkle-the-ultimate-guide/"><u>Mastering PS5's Sparkle: The Ultimate Guide</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-the-seven-keys-to-auditory-mastery-for-fresh-audio-creation-techniques/"><u>New 2024 Approved The Seven Keys to Auditory Mastery for Fresh Audio Creation Techniques</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-opera-capabilities-unlocking-free-discord-time/"><u>Maximize Opera Capabilities - Unlocking Free Discord Time</u></a></li>
<li><a href="https://games-able.techidaily.com/ais-next-leap-unveiled-at-computex/"><u>AI's Next Leap: Unveiled at Computex</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/in-2024-mastering-sound-design-with-linux-a-deep-dive-into-top-audio-tools/"><u>In 2024, Mastering Sound Design with Linux A Deep Dive Into Top Audio Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/dropping-paywalls-5-reasons-to-keep-your-games-home/"><u>Dropping Paywalls: 5 Reasons to Keep Your Games Home</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-gameplay-with-best-240hz-panels/"><u>Elevate Your Gameplay with Best 240Hz Panels</u></a></li>
<li><a href="https://games-able.techidaily.com/high-quality-titles-should-mts-be-compulsory/"><u>High-Quality Titles: Should MTs Be Compulsory?</u></a></li>
<li><a href="https://games-able.techidaily.com/sync-up-smoothly-implementing-controller-updates-virtually/"><u>Sync Up: Smoothly Implementing Controller Updates Virtually</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-simple-method-for-great-insta-posts/"><u>[New] Simple Method for Great Insta Posts</u></a></li>
<li><a href="https://games-able.techidaily.com/a-tactical-approach-to-choosing-an-elgato-stream-deck/"><u>A Tactical Approach to Choosing an Elgato Stream Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/clouding-safety-store-steam-game-images/"><u>Clouding Safety: Store Steam Game Images</u></a></li>
<li><a href="https://games-able.techidaily.com/unbeatable-connectivity-choosing-top-ethernets/"><u>Unbeatable Connectivity: Choosing Top Ethernets</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-oppo-k11-5g-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Oppo K11 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-advanced-features-of-amds-rx-7800xt-7700xt/"><u>Navigating the Advanced Features of AMD's RX 7800XT, 7700XT</u></a></li>
<li><a href="https://games-able.techidaily.com/from-pc-to-phone-in-a-flash-play-steam-games-with-link/"><u>From PC to Phone in a Flash: Play Steam Games with Link</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173202710-2024s-ddr5-master-cards-ranked/"><u>2024'S DDR5 Master Cards Ranked!</u></a></li>
<li><a href="https://games-able.techidaily.com/bypassing-surveillance-on-steam/"><u>Bypassing Surveillance on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/minimizing-game-bars-operations-for-windows-11-privacy/"><u>Minimizing Game Bar's Operations for Windows 11 Privacy</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-synopsis-of-vllo-consumer-voices/"><u>[New] Synopsis of VLLO Consumer Voices</u></a></li>
<li><a href="https://games-able.techidaily.com/java-game-highlights-our-favorites-unveiled/"><u>Java Game Highlights: Our Favorites Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/inquiring-about-the-value-proposition-for-ea-play/"><u>Inquiring About the Value Proposition for EA Play</u></a></li>
<li><a href="https://games-able.techidaily.com/best-8-minimalist-emulators-android-gaming-pcmac/"><u>Best 8 Minimalist Emulators: Android Gaming Pc/Mac</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-practices-for-leveraging-b-roll-content-for-2024/"><u>Best Practices for Leveraging B-Roll Content for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-itel-p55-5g-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Itel P55 5G Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/high-end-graphics-on-a-minimalist-budget/"><u>High End Graphics on a Minimalist Budget</u></a></li>
<li><a href="https://games-able.techidaily.com/connectivity-wonders-switchs-usb-and-bluetooth-unveiled-100-chars/"><u>Connectivity Wonders: Switch's USB and Bluetooth Unveiled (100 Chars)</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-finder-ps5-ssds-rated/"><u>Ultimate Finder: PS5 SSDs Rated</u></a></li>
<li><a href="https://games-able.techidaily.com/the-pathway-to-your-steam-login-reference-code/"><u>The Pathway to Your Steam Login Reference Code</u></a></li>
<li><a href="https://games-able.techidaily.com/the-most-immersive-mobile-mmo-experiences/"><u>The Most Immersive Mobile MMO Experiences</u></a></li>
<li><a href="https://games-able.techidaily.com/the-evolution-of-smoother-gaming-introducing-nvidia-g-sync/"><u>The Evolution of Smoother Gaming: Introducing Nvidia G-Sync</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-no-watermark-video-cutting-7-best-free-tools-for-2024/"><u>New No-Watermark Video Cutting 7 Best Free Tools for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-gala-the-glory-of-game-guardianship/"><u>Gaming Gala: The Glory of Game Guardianship</u></a></li>
<li><a href="https://games-able.techidaily.com/cryptic-gamers-hiding-your-activities/"><u>Cryptic Gamers: Hiding Your Activities</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-apple-iphone-se-2020-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/"><u>Unlock Your Apple iPhone SE (2020) in Minutes with ICCID Code Everything You Need to Know</u></a></li>
<li><a href="https://games-able.techidaily.com/enter-the-battlefield-top-10-immersive-online-fps-browser-games/"><u>Enter the Battlefield: Top 10 Immersive Online FPS Browser Games</u></a></li>
</ul></div>

---
title: Game Boy Hacks for Linux Command Line Enthusiasts
date: 2024-08-31T19:20:24.258Z
updated: 2024-09-01T19:20:24.258Z
tags:
  - games
categories:
  - games
description: This Article Describes Game Boy Hacks for Linux Command Line Enthusiasts
excerpt: This Article Describes Game Boy Hacks for Linux Command Line Enthusiasts
keywords: GameBoyLinuxHacks,LinuxGBCookbook,HackGBConsole,LinuxGBCoder,GBCommandTools,ConsoleGameHacking,LinuxGBMods
thumbnail: https://thmb.techidaily.com/7c8eb4a6751ebbb720d8baa15eb6264cc6e760acb0b1ed4fef37387dcca189b5.jpg
---

## Game Boy Hacks for Linux Command Line Enthusiasts

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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
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
<li><a href="https://some-techniques.techidaily.com/new-filming-availability-pledge-downloading-rights/"><u>[New] Filming Availability Pledge  Downloading Rights</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-totv-multimedia-player-wmp-alternative/"><u>2024 Approved  TOTV Multimedia Player  WMP Alternative</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/a-step-by-step-guide-to-mastering-business-on-snap/"><u>A Step-by-Step Guide to Mastering Business on Snap</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-steam-errors-in-windows-rust-setup/"><u>Addressing Steam Errors in Windows-Rust Setup</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/alternate-escapades-where-the-gta-v-lives-are-missing/"><u>Alternate Escapades - Where the GTA V Lives Are Missing</u></a></li>
<li><a href="https://games-able.techidaily.com/beat-short-term-rise-in-game-pass-costs-quick-hacks/"><u>Beat Short-Term Rise in Game Pass Costs - Quick Hacks</u></a></li>
<li><a href="https://games-able.techidaily.com/contemplating-ps5-heres-why-not/"><u>Contemplating PS5? Here's Why Not</u></a></li>
<li><a href="https://extra-resources.techidaily.com/correcting-color-misalignment-in-online-videos/"><u>Correcting Color Misalignment in Online Videos</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-unforgettable-home-videos-top-dvd-authoring-software-for-2024/"><u>Create Unforgettable Home Videos Top DVD Authoring Software for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/deactivate-steam-auto-launch/"><u>Deactivate Steam Auto-Launch</u></a></li>
<li><a href="https://games-able.techidaily.com/detecting-digital-disconnectors-on-series-sx/"><u>Detecting Digital Disconnectors on Series S/X</u></a></li>
<li><a href="https://games-able.techidaily.com/discover-the-secrets-of-exceptional-ps5-gaming/"><u>Discover the Secrets of Exceptional PS5 Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/dissecting-the-implications-of-xboxs-controller-policy-limitations/"><u>Dissecting the Implications of Xbox's Controller Policy Limitations</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-ps5-with-best-in-class-addons/"><u>Enhancing PS5 with Best-in-Class Addons</u></a></li>
<li><a href="https://games-able.techidaily.com/explore-every-corner-of-baldurs-gate-3-on-m1m2-via-crossover/"><u>Explore Every Corner of Baldur's Gate 3 on M1/M2 via Crossover</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-graphics-card-vram-space/"><u>Exploring Graphics Card VRAM Space</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-on-the-move-perks-and-pitfalls/"><u>Gaming on the Move: Perks and Pitfalls</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/hrtf-impact-on-audiovisual-perception-in-valorant/"><u>HRTF Impact on Audiovisual Perception in Valorant</u></a></li>
<li><a href="https://games-able.techidaily.com/jumpstarting-the-legacy-psp-to-virtual-arcade-machine/"><u>Jumpstarting the Legacy: PSP to Virtual Arcade Machine</u></a></li>
<li><a href="https://games-able.techidaily.com/legacy-console-emulation-via-linux-command-line/"><u>Legacy Console Emulation via Linux Command Line</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160774357-make-a-statement-in-gaming-big-box-backdrops/"><u>Make a Statement in Gaming: Big Box Backdrops!</u></a></li>
<li><a href="https://games-able.techidaily.com/making-the-most-of-steams-offline-illusion/"><u>Making the Most of Steam's Offline Illusion</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-setting-up-your-xbox-series-x-refresh-rate/"><u>Mastering the Art of Setting Up Your Xbox Series X Refresh Rate</u></a></li>
<li><a href="https://games-able.techidaily.com/play-smart-why-you-shouldnt-use-mic-on-ps5-controller/"><u>Play Smart: Why You Shouldn't Use Mic on PS5 Controller</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-fixes-for-steam-authentication-failures-in-rust/"><u>Quick Fixes for Steam Authentication Failures in Rust</u></a></li>
<li><a href="https://games-able.techidaily.com/reclaim-your-games-sound-with-easy-fixes-on-console/"><u>Reclaim Your Game's Sound with Easy Fixes on Console</u></a></li>
<li><a href="https://games-able.techidaily.com/reducing-background-monitoring-by-game-bar-on-win-11/"><u>Reducing Background Monitoring by Game Bar on Win 11</u></a></li>
<li><a href="https://games-able.techidaily.com/reviving-video-game-classics-on-a-budget-a-pi-story/"><u>Reviving Video Game Classics on a Budget - A Pi Story</u></a></li>
<li><a href="https://games-able.techidaily.com/slim-tech-meets-colorful-fun-with-tecnos-new-releases/"><u>Slim Tech Meets Colorful Fun with Tecno's New Releases</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-versus-gog-marketplace-differences-highlighted/"><u>Steam Versus GOG: Marketplace Differences Highlighted</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-your-classic-collection-small-sized-isos-by-chdman-cooking-method/"><u>Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method</u></a></li>
<li><a href="https://games-able.techidaily.com/switch-to-smoothness-wi-fi-fixes-guide/"><u>Switch to Smoothness: Wi-Fi Fixes Guide</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-nubia-red-magic-9-pro-by-drfone-android/"><u>The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Nubia Red Magic 9 Pro</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-keeping-your-game-passes-in-check-on-xsx/"><u>Tips for Keeping Your Game Passes in Check on XS/X</u></a></li>
<li><a href="https://some-skills.techidaily.com/transform-every-moment-top-ideas-for-productive-podcast-sessions-for-2024/"><u>Transform Every Moment  Top Ideas for Productive Podcast Sessions for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/update-your-logitech-g403-controller-software-on-laptopdesktop/"><u>Update Your Logitech G403 Controller Software on Laptop/Desktop</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-designing-effective-lower-thirds-in-final-cut-pro-x-for-2024/"><u>Updated Designing Effective Lower Thirds in Final Cut Pro X for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/your-guide-to-exciting-paid-nothing-switch-games/"><u>Your Guide to Exciting, Paid-Nothing Switch Games</u></a></li>
</ul></div>

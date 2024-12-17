---
title: Game Boy Hacks for Linux Command Line Enthusiasts
date: 2024-12-11T16:45:42.296Z
updated: 2024-12-16T20:42:13.475Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Emulate a Game Boy in the Terminal?

![pokemon red star splash screen in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/pokemon-red-star-splash-screen-in-the-linux-terminal.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Nintendo's Game Boy is one of the most wildly successful game consoles ever created, and introduced generations of kids and adults to the joys of games such as Tetris, Pokemon, and the Super Mario Land series.

 With its 4MHz processor and 47x43mm display, the Game Boy could easily fit in your trouser pocket and offered around 15 hours of gameplay from four AA batteries. In the late 1980s and early 1990s, the Game Boy was a must-have accessory for any teenager, and utterly dominated the portable gaming market.

 The console's popularity and longevity meant that there were thousands of officially licensed Game Boy games, with many more hacked together by bedroom tinkerers.

 By running an emulator in your terminal, you can run every single one of these, transforming your terminal into an extensive library of playable games.

 As the name suggests, php-terminal-gameboy-emulator is written in PHP—a language[usually used to create websites](https://www.makeuseof.com/tag/build-simple-php-website/) —and although the project's readme only states that it supports PHP 5.6, PHP 7, and HHVM, we've had it running almost flawlessly on PHP versions up to 8.2.

 With php-terminal-gameboy-emulator, you're not limited to your computer either and can run sessions over[Secure Shell (SSH)](https://www.makeuseof.com/learn-how-to-manage-remote-access-via-ssh/) on remote machines.

 Because it's running in a terminal, your Game Boy games won't have any sound, but we're sure you can hum the Tetris theme tune.

 You also won't be able to save games. If these limitations are too restrictive, there are dozens of excellent emulators available on Linux.

 You should only use ROMS you legally own. You can find a huge variety of homebrew Game Boy ROMS at[Homebrew Hub](https://hh.gbdev.io/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-top-10-no-cost-image-servers-always-preserve-your-pics/"><u>[Updated] 2024 Approved Top 10 No-Cost Image Servers, Always Preserve Your Pics</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-climbing-the-social-ladder-6-precise-methods-for-gaining-instagram-verification-for-2024/"><u>[Updated] Climbing the Social Ladder 6 Precise Methods for Gaining Instagram Verification for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-seamless-blend-inserting-music-into-fb-video-posts/"><u>[Updated] In 2024, Seamless Blend Inserting Music Into FB Video Posts</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-narrative-artistry-accolades-1-8-distinguished-academies-for-2024/"><u>[Updated] Narrative Artistry Accolades #1-#8 Distinguished Academies for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-high-resolution-horizons-an-in-depth-look-at-the-asus-mg28uq/"><u>2024 Approved High-Resolution Horizons An In-Depth Look at the ASUS MG28UQ</u></a></li>
<li><a href="https://games-able.techidaily.com/8-revolutionary-features-of-edge-for-gamers/"><u>8 Revolutionary Features of Edge for Gamers</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-xiaomi-redmi-k70-pro-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Xiaomi Redmi K70 Pro? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/comprehensive-insight-into-the-ultra-clear-lg-monitor-for-2024/"><u>Comprehensive Insight Into the Ultra-Clear LG Monitor for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-dilemma-sonys-console-vs-inexpensive-pc/"><u>Gaming Dilemma: Sony's Console vs Inexpensive PC?</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-fun-uncover-the-5-advantages-of-investing-in-games/"><u>Maximize Fun: Uncover the 5 Advantages of Investing in Games</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/optimize-with-cookiebot-next-level-analytics-and-personalization-power/"><u>Optimize With Cookiebot: Next-Level Analytics and Personalization Power</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-down-to-size-whats-new/"><u>PS5 Down to Size: What's New?</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionary-gpd-win-4-for-gamers-and-pros/"><u>Revolutionary GPD Win 4 for Gamers & Pros</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-to-fix-unrecognized-games-by-steam-service/"><u>Strategies to Fix Unrecognized Games by Steam Service</u></a></li>
<li><a href="https://win-special.techidaily.com/unveiling-the-best-android-media-streamers-of-2019-our-top-5-picks-for-home-entertainment/"><u>Unveiling the Best Android Media Streamers of 2019: Our Top 5 Picks for Home Entertainment</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-the-secrets-of-smartphone-based-twitch-streams/"><u>Unveiling the Secrets of Smartphone-Based Twitch Streams</u></a></li>
<li><a href="https://games-able.techidaily.com/using-smart-technology-for-xbox-controller-free-use/"><u>Using Smart Technology for Xbox Controller-Free Use</u></a></li>
<li><a href="https://games-able.techidaily.com/why-tipping-devs-could-distort-creative-priorities/"><u>Why Tipping Devs Could Distort Creative Priorities</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/yl-software-reviews-how-to-boost-your-computers-speed-like-never-before/"><u>YL Software Reviews: How To Boost Your Computer’s Speed Like Never Before!</u></a></li>
</ul></div>


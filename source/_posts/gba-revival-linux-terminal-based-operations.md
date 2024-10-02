---
title: "GBA Revival: Linux Terminal-Based Operations"
date: 2024-09-29T01:11:14.502Z
updated: 2024-10-02T03:27:57.285Z
tags:
  - games
categories:
  - games
description: "This Article Describes GBA Revival: Linux Terminal-Based Operations"
excerpt: "This Article Describes GBA Revival: Linux Terminal-Based Operations"
keywords: GBA Linux OS,Terminal Linux,Operations Console,Linux Terminal,GBA Linux Replay,BIOS Revival,OpenSource Gaming
thumbnail: https://thmb.techidaily.com/42d888d9431637ab1388aeb276d6888b24b9d1d85a816656ff3b301d8b067e97.jpg
---

## GBA Revival: Linux Terminal-Based Operations

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151869/7443" target="_top" id="2151869">
  <img src="//a.impactradius-go.com/display-ad/7443-2151869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151869/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-approaches.techidaily.com/new-transforming-your-imagery-a-thorough-analysis-of-the-background-erase-tool-in-photoshop/"><u>[New] Transforming Your Imagery A Thorough Analysis of the Background Erase Tool in Photoshop</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-calculating-your-commercial-break-even-as-a-podcaster/"><u>[Updated] Calculating Your Commercial Break-Even as a Podcaster</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-latest-overhaul-sonys-s6500-hd-and-bd-player-review/"><u>2024 Approved Latest Overhaul Sony's S6500 HD & BD Player Review</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-low-cost-android-calls-highest-ranking-options/"><u>2024 Approved Low-Cost Android Calls Highest Ranking Options</u></a></li>
<li><a href="https://games-able.techidaily.com/discover-the-ultimate-pick-for-nintendo-switch-gaming-expert-picks-by-zdnet/"><u>Discover the Ultimate Pick for Nintendo Switch Gaming - Expert Picks by ZDNet</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/easy-guide-to-poco-m6-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Poco M6 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/experience-gaming-greatness-alienware-m18-laptop-offers-epic-deal-at-30er-below-after-labor-day-zdnet/"><u>Experience Gaming Greatness: Alienware M18 Laptop Offers Epic Deal at $30Er Below After Labor Day | ZDNET</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-the-complete-manual-for-instagram-selfies/"><u>In 2024, The Complete Manual for Instagram Selfies</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-and-easy-guide-upgrading-ps5-console-with-extra-storage-complete-within-10-minuteszdnet/"><u>Quick & Easy Guide: Upgrading PS5 Console with Extra Storage - Complete Within 10 Minutes![ZDNet]</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-motorola-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Motorola</u></a></li>
<li><a href="https://games-able.techidaily.com/zdnets-most-spectacular-4th-of-july-tv-discounts-dont-miss-out/"><u>ZDNet's Most Spectacular 4Th of July TV Discounts: Don’t Miss Out!</u></a></li>
</ul></div>


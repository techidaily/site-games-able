---
title: Navigating Legacy Gaming with Linux Terminal
date: 2024-10-04T17:18:01.685Z
updated: 2024-10-07T18:40:10.274Z
tags:
  - games
categories:
  - games
description: This Article Describes Navigating Legacy Gaming with Linux Terminal
excerpt: This Article Describes Navigating Legacy Gaming with Linux Terminal
keywords: Legacy Gaming Linux,Linux Gaming Setup,Terminal Emulator Games,Classic Games Linux,Gaming Terminal OS,Linux Game Navigation,Retro Gaming Terminal
thumbnail: https://thmb.techidaily.com/25e355cfe41e9e10950c631e4aa9da16590e30c123d991c0d3d8b6703e367f7f.png
---

## Navigating Legacy Gaming with Linux Terminal

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
<a href="https://aligracehair.sjv.io/c/5597632/1948895/19272" target="_top" id="1948895">
  <img src="//a.impactradius-go.com/display-ad/19272-1948895" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948895/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-secrets-to-successful-twitpicingvideo-edition/"><u>[New] 2024 Approved Secrets to Successful Twitpicing—Video Edition</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-best-budget-friendly-hd-cameras-for-adrenaline-junkies/"><u>[Updated] 2024 Approved Best Budget-Friendly HD Cameras for Adrenaline Junkies</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-giggle-genesis-creepy-clones-with-a-smile/"><u>2024 Approved Giggle Genesis Creepy Clones with a Smile</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-ultimate-upscaling-preferred-platforms-for-tapping-snapalert-rhythms/"><u>2024 Approved Ultimate Upscaling Preferred Platforms for Tapping SnapAlert Rhythms</u></a></li>
<li><a href="https://games-able.techidaily.com/breakthroughs-in-assessing-neuroinflammation-through-endocannabinoid-levels/"><u>Breakthroughs in Assessing Neuroinflammation Through Endocannabinoid Levels</u></a></li>
<li><a href="https://windows11.techidaily.com/debunking-top-reasons-win11-beats-macos/"><u>Debunking: Top Reasons Win11 Beats macOS</u></a></li>
<li><a href="https://facebook.techidaily.com/discreet-digital-denizens-on-fb/"><u>Discreet Digital Denizens on FB</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/iently-uploading-youtube-vids-to-insta-profile/"><u>Efficiently Uploading YouTube Vids to Insta Profile</u></a></li>
<li><a href="https://games-able.techidaily.com/from-screenshots-to-screens-iphone-meets-psp-gaming/"><u>From Screenshots to Screens: IPhone Meets PSP Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-a-trifecta-of-techniques-for-codes-success/"><u>Game On: A Trifecta of Techniques for Codes Success</u></a></li>
<li><a href="https://games-able.techidaily.com/graphics-prowess-the-directx-evolution-story/"><u>Graphics Prowess: The DirectX Evolution Story</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-sharpen-your-footage-the-essentials-of-video-enhance-22/"><u>In 2024, Sharpen Your Footage The Essentials of Video Enhance 2.2</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/music-service-migration-keeping-playlists-intact-for-2024/"><u>Music Service Migration Keeping Playlists Intact for 2024</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/photo-perfect-stellar-repair-app/"><u>Photo Perfect Stellar Repair App: すぐ届ける購入オプション!</u></a></li>
<li><a href="https://games-able.techidaily.com/sonys-subscription-service-assessing-its-monthly-cost/"><u>Sony's Subscription Service: Assessing Its Monthly Cost</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-game-mice-qualities-essential-specifications-to-check/"><u>Top 5 Game Mice Qualities: Essential Specifications to Check</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-big-time-savings-with-these-top-11-discounted-games-websites/"><u>Unlock Big-Time Savings with These Top 11 Discounted Games Websites</u></a></li>
<li><a href="https://games-able.techidaily.com/what-to-do-if-your-controller-wont-work-on-your-windows-pc/"><u>What to Do if Your Controller Won't Work on Your Windows PC</u></a></li>
<li><a href="https://games-able.techidaily.com/winning-the-race-addressing-low-fps-and-enhancing-valorant-performance/"><u>Winning the Race: Addressing Low FPS & Enhancing Valorant Performance</u></a></li>
</ul></div>


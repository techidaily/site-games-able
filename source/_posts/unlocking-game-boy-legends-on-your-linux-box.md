---
title: Unlocking Game Boy Legends on Your Linux Box
date: 2024-09-23T07:37:08.270Z
updated: 2024-09-27T07:11:58.884Z
tags:
  - games
categories:
  - games
description: This Article Describes Unlocking Game Boy Legends on Your Linux Box
excerpt: This Article Describes Unlocking Game Boy Legends on Your Linux Box
keywords: Linux GBC (Game Boy Console),Unlock Game Boy,Linux Emulation,Retro Games Linux,Game Boy Legends,Play GB on Linux,Game Boy OS
thumbnail: https://thmb.techidaily.com/59ebf54bbd2728b1cee67f80e126289c9f6737977aace37b8f0906719738cd6b.jpg
---

## Unlocking Game Boy Legends on Your Linux Box

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
<a href="https://laganoo.pxf.io/c/5597632/1528693/16446" target="_top" id="1528693">
  <img src="//a.impactradius-go.com/display-ad/16446-1528693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528693/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-win11s-ultimate-selection-of-free-screen-recording-software-1-5/"><u>[New] 2024 Approved Win11's Ultimate Selection of Free Screen Recording Software #1-5</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-a-thorough-examination-recmeisters-screen-capture-innovations/"><u>[New] A Thorough Examination Recmeister's Screen Capture Innovations</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-virtual-horizons-with-meaningful-metaverse-sentiments/"><u>[New] Exploring Virtual Horizons with Meaningful Metaverse Sentiments</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-final-cut-pros-top-effect-enhancers-the-essential-10/"><u>[New] Final Cut Pro's Top Effect Enhancers The Essential 10</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-screen-space-enlargement-on-youtube/"><u>[Updated] Navigating Screen Space Enlargement on YouTube</u></a></li>
<li><a href="https://extra-information.techidaily.com/assessing-effectiveness-of-reduced-shaking-in-adobe-photos/"><u>Assessing Effectiveness of Reduced Shaking in Adobe Photos</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-8-lite-android-simulators-for-pc-and-mac-gamers/"><u>Essential 8 Lite Android Simulators for PC and Mac Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-insights-for-gamers-6-reasons-to-ignore-high-res-monitors/"><u>Essential Insights for Gamers - 6 Reasons to Ignore High-Res Monitors</u></a></li>
<li><a href="https://tech-haven.techidaily.com/intelligent-engagement-siri-and-chatgpt-for-apple-users/"><u>Intelligent Engagement: Siri & ChatGPT for Apple Users</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-with-purpose-where-are-the-excellent-discs/"><u>Navigating with Purpose: Where Are the Excellent Discs?</u></a></li>
<li><a href="https://games-able.techidaily.com/quality-consistency-in-gaming-keys-review-of-keychron-and-lemokey-l3/"><u>Quality Consistency in Gaming Keys: Review of Keychron and Lemokey L3</u></a></li>
<li><a href="https://techtrends.techidaily.com/1722903690173-samsung-soundbar-woes-heres-how-to-bring-it-back-from-the-dead/"><u>Samsung Soundbar Woes? Here's How to Bring It Back From the Dead!</u></a></li>
<li><a href="https://games-able.techidaily.com/scaling-up-efficient-strategies-for-funding-steam-games/"><u>Scaling Up: Efficient Strategies for Funding Steam Games</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166855610-streamline-your-computing-experience-install-nvidia-driver-updates/"><u>Streamline Your Computing Experience – Install Nvidia Driver Updates.</u></a></li>
<li><a href="https://games-able.techidaily.com/uncovering-java-games-standout-characteristics/"><u>Uncovering Java Games’ Standout Characteristics</u></a></li>
<li><a href="https://games-able.techidaily.com/uncovering-users-on-steam-efficiently/"><u>Uncovering Users on Steam Efficiently</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/vital-upgrades-to-transform-chatgpt-plugins-store-dynamics/"><u>Vital Upgrades to Transform ChatGPT Plugins Store Dynamics</u></a></li>
</ul></div>


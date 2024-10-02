---
title: "Old Games, New Methods: Emulating GB in Linux Terminal"
date: 2024-09-27T00:21:35.843Z
updated: 2024-10-02T08:50:30.644Z
tags:
  - games
categories:
  - games
description: "This Article Describes Old Games, New Methods: Emulating GB in Linux Terminal"
excerpt: "This Article Describes Old Games, New Methods: Emulating GB in Linux Terminal"
keywords: Old Game Emulation (GB),Linux Terminal Emulator,GB Console Reincarnation,Retro Games on Linux,Legacy System Emulate,Vintage Gaming Revival,GB Emulation Techniques
thumbnail: https://thmb.techidaily.com/db3dbeacfdd5ea435b3f8eb406f01646288938a037fe9e28d65cbe9fbebcdbb0.png
---

## Old Games, New Methods: Emulating GB in Linux Terminal

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
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1902304/19272" target="_top" id="1902304">
  <img src="//a.impactradius-go.com/display-ad/19272-1902304" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902304/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/updated-achieve-seamless-retrieval-of-twitters-humor-gifs-on-your-system-for-2024/"><u>[Updated] Achieve Seamless Retrieval of Twitter's Humor (GIFs) on Your System for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-top-10-miniature-portable-dvd-systems-unveiled/"><u>2024 Approved Top 10 Miniature Portable DVD Systems Unveiled</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-change-location-on-facebook-marketplace-for-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>3 Ways to Change Location on Facebook Marketplace for Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-4k-graphics-at-the-consumer-level/"><u>Affordable 4K Graphics at the Consumer Level</u></a></li>
<li><a href="https://games-able.techidaily.com/demystifying-password-configuration-for-your-ps5-console/"><u>Demystifying Password Configuration for Your PS5 Console</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/discount-hunting-for-chinese-made-vr-devices/"><u>Discount Hunting for Chinese-Made VR Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-emulators-for-superior-steam-deck-gaming-experience/"><u>Essential Emulators for Superior Steam Deck Gaming Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-the-nintendo-switch-online-upgrade/"><u>Evaluating the Nintendo Switch Online Upgrade</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/future-appraisal-unconventional-thoughts-for-2024/"><u>Future Appraisal Unconventional Thoughts for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/gamble-less-save-more-the-prime-picks-from-top-11-game-dealers/"><u>Gamble Less, Save More - The Prime Picks From Top 11 Game Dealers</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-a-lost-apple-iphone-13-mini-for-free-drfone-by-drfone-virtual-ios/"><u>How to Track a Lost Apple iPhone 13 mini for Free? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-samsung-galaxy-s24plus-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Google Pixel 8 Pro | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/master-the-art-of-coding-redemption-xbox-edition/"><u>Master the Art of Coding Redemption: Xbox Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/psp-to-game-boy-coder-guide/"><u>PSP to Game Boy Coder Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-gameplay-use-steams-disk-manager/"><u>Streamlining Gameplay: Use Steam’s Disk Manager</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-smart-choice-essential-steps-in-upgrading-your-tech/"><u>The Smart Choice Essential Steps in Upgrading Your Tech</u></a></li>
<li><a href="https://some-skills.techidaily.com/upgraded-multitasking-with-microsofts-multi-display-feature-in-edge-for-2024/"><u>Upgraded Multitasking with Microsoft's Multi-Display Feature in Edge for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/why-do-vr-headsets-break-the-bank-here-are-4-pivotal-points/"><u>Why Do VR Headsets Break the Bank? Here Are 4 Pivotal Points</u></a></li>
</ul></div>


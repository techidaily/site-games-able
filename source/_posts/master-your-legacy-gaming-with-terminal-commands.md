---
title: Master Your Legacy Gaming with Terminal Commands
date: 2024-09-30T12:05:35.561Z
updated: 2024-10-02T11:06:51.684Z
tags:
  - games
categories:
  - games
description: This Article Describes Master Your Legacy Gaming with Terminal Commands
excerpt: This Article Describes Master Your Legacy Gaming with Terminal Commands
keywords: Legacy Game Commanding,Master Gamer Terminal,Terminal Gaming Techniques,Terminal Control Games,Advanced Gaming Commands,Gaming with Terminal Expertise,Command-Line Gaming Skills
thumbnail: https://thmb.techidaily.com/85034a62a15df819e619fec4e6d0909e5ab4845fbca98b126bdfe343d56fc596.jpg
---

## Master Your Legacy Gaming with Terminal Commands

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
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094476/7443" target="_top" id="2094476">
  <img src="//a.impactradius-go.com/display-ad/7443-2094476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094476/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-blue.techidaily.com/new-essential-guide-to-best-10-no-cost-srt-converters-for-2024/"><u>[New] Essential Guide to Best 10 No-Cost Srt Converters for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-elevate-video-content-with-proven-strategies-for-youtube-shorts-growth/"><u>[Updated] 2024 Approved Elevate Video Content with Proven Strategies for YouTube Shorts Growth</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-why-no-video-suggestions-pop-up-in-your-social-media-world/"><u>[Updated] 2024 Approved Why No Video Suggestions Pop Up in Your Social Media World?</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-navigating-the-igtv-landscape-a-beginners-roadmap/"><u>[Updated] In 2024, Navigating the IGTV Landscape A Beginner's Roadmap</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-art-of-attracting-more-youtube-admirers/"><u>2024 Approved Mastering the Art of Attracting More YouTube Admirers</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-step-by-step-to-emoji-stickers-a-complete-tutorial-for-telegram-and-beyond/"><u>2024 Approved Step-by-Step to Emoji Stickers A Complete Tutorial for Telegram and Beyond</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-thriving-in-zoom-chats-key-techniques-for-engaging-online-conversations/"><u>2024 Approved Thriving in Zoom Chats Key Techniques for Engaging Online Conversations</u></a></li>
<li><a href="https://games-able.techidaily.com/7-key-advantages-edge-for-gamers-unrivaled-experience/"><u>7 Key Advantages: Edge for Gamers' Unrivaled Experience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/bring-ai-talk-to-life-on-android-via-widgets/"><u>Bring AI Talk to Life on Android via Widgets</u></a></li>
<li><a href="https://games-able.techidaily.com/demystifying-steams-virtual-economy/"><u>Demystifying Steam's Virtual Economy</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-nintendo-switch-game-with-peripherals-90-chars/"><u>Elevate Your Nintendo Switch Game With Peripherals (90 Chars)</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-dungeon-crafting-six-chatgpt-approaches-to-perfect-game-guidance/"><u>Enhancing Dungeon Crafting: Six ChatGPT Approaches to Perfect Game Guidance</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-steam-deck-performance-with-coolers/"><u>Enhancing Steam Deck Performance with Coolers</u></a></li>
<li><a href="https://games-able.techidaily.com/five-pillars-of-a-secure-playstation-5-experience/"><u>Five Pillars of a Secure Playstation 5 Experience</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/powerhouses-for-captivating-youtube-thumbnails-for-2024/"><u>Font Powerhouses for Captivating YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-vivo-y17s-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Vivo Y17s To Phone | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-recovering-missing-pokemon-go-locations/"><u>Mastering the Art of Recovering Missing Pokémon GO Locations</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-win11-steam-network-failure/"><u>Overcoming Win11 Steam Network Failure</u></a></li>
<li><a href="https://games-able.techidaily.com/reverted-steps-to-retrace-controller-updates/"><u>Reverted: Steps to Retrace Controller Updates</u></a></li>
</ul></div>


---
title: "Game Boy Rediscovered: A Terminal Play Guide"
date: 2024-07-12T03:17:54.526Z
updated: 2024-07-13T03:17:54.526Z
tags:
  - games
categories:
  - games
description: "This Article Describes Game Boy Rediscovered: A Terminal Play Guide"
excerpt: "This Article Describes Game Boy Rediscovered: A Terminal Play Guide"
keywords: Gameboy Redeemed,GB Rediscovery,Retro Gamer Tips,Nintendo GB Guide,Terminal GB Basics,Classic GB Play,Vintage Game Boy
thumbnail: https://thmb.techidaily.com/b7fdec82e5e2a50f89b07a18bb64e205705f93d7819f0fe370579d848f9daaea.jpg
---

## Game Boy Rediscovered: A Terminal Play Guide

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





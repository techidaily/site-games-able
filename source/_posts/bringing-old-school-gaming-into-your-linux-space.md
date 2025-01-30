---
title: Bringing Old-School Gaming Into Your Linux Space
date: 2025-01-27T16:39:00.243Z
updated: 2025-01-30T16:57:15.296Z
tags:
  - games
categories:
  - games
description: This Article Describes Bringing Old-School Gaming Into Your Linux Space
excerpt: This Article Describes Bringing Old-School Gaming Into Your Linux Space
keywords: Linux Gaming Console,Retro Games on Linux,Linux Emulators,Classic PC Gaming,Linux Retro Arcade,Emulate Old-School Games,Gaming in Linux Environment
thumbnail: https://thmb.techidaily.com/a577227bca81f1377b01a00eba21acdee9d8dfcda26cad3482a8cc47d1c6fe1b.jpg
---

## Bringing Old-School Gaming Into Your Linux Space

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Emulate a Game Boy in the Terminal?

![pokemon red star splash screen in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/pokemon-red-star-splash-screen-in-the-linux-terminal.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/updated-the-art-of-title-design-in-after-effects-for-2024/"><u>[Updated] The Art of Title Design in After Effects for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-play-mkv-movies-on-htc-u23-pro-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How do I play MKV movies on HTC U23 Pro?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-apple-iphone-8-backup-password-never-set-but-still-asking-heres-the-fix-by-drfone-ios/"><u>In 2024, Apple iPhone 8 Backup Password Never Set But Still Asking? Heres the Fix</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-the-ultimate-list-of-ios-camera-apps-for-the-iphone-xplus-series/"><u>In 2024, The Ultimate List of iOS Camera Apps for the iPhone X+ Series</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-gpasswd-a-comprehensive-guide-to-managing-user-passwords-in-linux/"><u>Mastering Gpasswd: A Comprehensive Guide to Managing User Passwords in Linux</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/mastering-mention-triggers-for-detecting-deceptive-chatgpts/"><u>Mastering Mention Triggers for Detecting Deceptive ChatGPTs</u></a></li>
<li><a href="https://games-able.techidaily.com/proven-strategies-for-immediate-ps5-gamepad-recovery/"><u>Proven Strategies for Immediate PS5 Gamepad Recovery</u></a></li>
<li><a href="https://games-able.techidaily.com/seven-friendship-flirtations-a-textual-dance-of-words/"><u>Seven Friendship Flirtations: A Textual Dance of Words</u></a></li>
<li><a href="https://games-able.techidaily.com/step-into-security-configuring-a-password-lock-on-your-nintendo-console/"><u>Step Into Security: Configuring a Password Lock on Your Nintendo Console</u></a></li>
<li><a href="https://games-able.techidaily.com/switch-tactics-why-choose-pc-over-console-games/"><u>Switch Tactics: Why Choose PC Over Console Games</u></a></li>
<li><a href="https://games-able.techidaily.com/the-science-behind-xboxs-strike-process/"><u>The Science Behind Xbox's Strike Process</u></a></li>
<li><a href="https://some-guidance.techidaily.com/winxvideo-ai-ai/"><u>Winxvideo AI: 革新的なAIを用いた高精度フレーム埋め忘れ無料ツール</u></a></li>
</ul></div>


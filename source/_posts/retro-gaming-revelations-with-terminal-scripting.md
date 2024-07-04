---
title: Retro Gaming Revelations with Terminal Scripting
date: 2024-06-25T13:36:46.513Z
updated: 2024-06-26T13:36:46.513Z
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
<li><a href="https://games-able.techidaily.com/revealing-gaming-cost-chronicles-on-steam-service/"><u>Revealing Gaming Cost Chronicles on Steam Service</u></a></li>
<li><a href="https://games-able.techidaily.com/emulating-vintage-gaming-the-power-of-xemu-for-pc/"><u>Emulating Vintage Gaming: The Power of Xemu for PC</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-steams-bp-display-glitches/"><u>Overcoming Steam's BP Display Glitches</u></a></li>
<li><a href="https://games-able.techidaily.com/why-a-shift-in-strategy-is-crucial-for-microsofts-xbox-point-program/"><u>Why a Shift in Strategy Is Crucial for Microsoft's Xbox Point Program</u></a></li>
<li><a href="https://games-able.techidaily.com/joining-worlds-together-using-ps5-controller-on-windows-pc/"><u>Joining Worlds Together: Using PS5 Controller on Windows PC</u></a></li>
<li><a href="https://games-able.techidaily.com/constraining-background-observations-by-game-bar-on-os-11/"><u>Constraining Background Observations by Game Bar on OS 11</u></a></li>
<li><a href="https://games-able.techidaily.com/optimize-your-gaming-setup-mastering-game-pass-for-xs-and-x/"><u>Optimize Your Gaming Setup: Mastering Game Pass for XS and X</u></a></li>
<li><a href="https://games-able.techidaily.com/revitalize-your-console-fixing-broken-xbox-sandx/"><u>Revitalize Your Console: Fixing Broken Xbox S&X</u></a></li>
<li><a href="https://games-able.techidaily.com/unleashing-great-sound-from-mmx-200/"><u>Unleashing Great Sound From MMX 200</u></a></li>
<li><a href="https://games-able.techidaily.com/how-will-amds-new-anti-aliasing-solution-fsr-3-compete-with-nvidias-dlss-35/"><u>How Will AMD’s New Anti-Aliasing Solution, FSR 3 Compete with NVIDIA's DLSS 3.5?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-lava-blaze-pro-5g-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Lava Blaze Pro 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-twitter-account-launch-a-beginners-roadmap/"><u>[New] In 2024, Twitter Account Launch  A Beginner's Roadmap</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-stealthy-strategies-for-eliminating-hashtags/"><u>[New] Stealthy Strategies for Eliminating Hashtags</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-enable-usb-debugging-on-a-locked-vivo-y02t-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Vivo Y02T Phone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-the-archivists-collection-essential-retro-visual-hacks-for-video-editors/"><u>[New] 2024 Approved  The Archivist's Collection  Essential Retro Visual Hacks for Video Editors</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-monitor-magic-asuss-mg28uq-review-reveals-a-new-vision-era/"><u>[New] Monitor Magic – ASUS's MG28UQ Review Reveals a New Vision Era</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-graph-gems-2017s-statistical-youtube-surprises/"><u>[New] Graph Gems  2017'S Statistical YouTube Surprises</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-the-art-of-action-shots-with-gopro-for-2024/"><u>Mastering the Art of Action Shots with GoPro for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-exporting-snapchat-content-to-your-phones-gallery/"><u>[Updated] In 2024, Exporting SnapChat Content to Your Phone's Gallery</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Oppo Find N3 | Dr.fone</u></a></li>
</ul></div>

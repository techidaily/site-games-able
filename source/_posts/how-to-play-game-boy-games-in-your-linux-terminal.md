---
title: How to Play Game Boy Games in Your Linux Terminal
date: 2024-09-14T16:42:05.670Z
updated: 2024-09-20T18:42:06.882Z
tags:
  - games
categories:
  - games
description: This Article Describes How to Play Game Boy Games in Your Linux Terminal
excerpt: This Article Describes How to Play Game Boy Games in Your Linux Terminal
keywords: Linux GBA,Emulate Gameboy,Linux Terminal Games,Gameboy Play Linux,GB Advance Linux,Terminal Emulator,Linux Game Boy Console
thumbnail: https://thmb.techidaily.com/a0961ee471b397828689bb0499e11bd310468db6e686996103528a8e584f7f95.jpg
---

## How to Play Game Boy Games in Your Linux Terminal

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-join-the-social-scene-facebook-live-streams-on-roku-tv/"><u>[New] In 2024, Join The Social Scene Facebook Live Streams on Roku TV</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-beginners-blueprint-for-yourwebcamrecord-for-2024/"><u>[Updated] Beginner's Blueprint for YourWebcamRecord for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-transcending-reality-enlightening-metaverse-verses/"><u>2024 Approved Transcending Reality Enlightening Metaverse Verses</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/boost-your-gardens-vitality-how-this-advanced-ai-assistant-keeps-plants-thriving/"><u>Boost Your Garden's Vitality: How This Advanced AI Assistant Keeps Plants Thriving</u></a></li>
<li><a href="https://games-able.techidaily.com/enhance-performance-install-latest-nvidia-drivers-now/"><u>Enhance Performance! Install Latest Nvidia Drivers Now</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-streamlined-approaches-for-zoom-utility-on-chromebook/"><u>In 2024, Streamlined Approaches for Zoom Utility on Chromebook</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-itel-a60s-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Itel A60s | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/joystick-journey-from-xbox-to-computer-play-142-chars/"><u>Joystick Journey: From Xbox to Computer Play (142 Chars)</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-imaginary-device-issue-in-win-11-os/"><u>Resolving Imaginary Device Issue in Win 11 OS</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Oppo K11x? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-has-closed-a-refund-loophole-heres-how-it-will-affect-you/"><u>Steam Has Closed a Refund Loophole: Here's How It Will Affect You</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-eliminate-shaking-mouse-scroll/"><u>Steps to Eliminate Shaking Mouse Scroll</u></a></li>
<li><a href="https://games-able.techidaily.com/virtual-escapades-without-internet-choose-your-favorite-phone-games/"><u>Virtual Escapades Without Internet - Choose Your Favorite Phone Games</u></a></li>
<li><a href="https://games-able.techidaily.com/zen-gameplay-find-your-indolent-match/"><u>Zen Gameplay: Find Your Indolent Match</u></a></li>
</ul></div>


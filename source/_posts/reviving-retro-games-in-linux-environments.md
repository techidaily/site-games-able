---
title: Reviving Retro Games in Linux Environments
date: 2024-10-05T16:11:23.338Z
updated: 2024-10-07T19:23:56.525Z
tags:
  - games
categories:
  - games
description: This Article Describes Reviving Retro Games in Linux Environments
excerpt: This Article Describes Reviving Retro Games in Linux Environments
keywords: Linux Gaming Revival,Retro Game Linux,Linux Emulators,Re-Booting Classics,Retro Games Linux,Linux Gaming Patches,Retro Games OS
thumbnail: https://thmb.techidaily.com/154ba651f58f7b61c6d13ed51a3e08aab825faff32ad0111bfbaa0c8293dac8c.jpg
---

## Reviving Retro Games in Linux Environments

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2137412/7443" target="_top" id="2137412">
  <img src="//a.impactradius-go.com/display-ad/7443-2137412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137412/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-expedite-excitement-fast-video-on-android/"><u>[New] Expedite Excitement Fast Video on Android</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-top-qp-value-enhancing-gradual-movement-vids/"><u>[New] In 2024, Top QP Value Enhancing Gradual Movement Vids</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-user-friendly-steps-for-storing-google-voice-conversations/"><u>[Updated] 2024 Approved User-Friendly Steps for Storing Google Voice Conversations</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-by-step-guide-for-a-supercharged-ps4-experience/"><u>A Step-by-Step Guide for a Supercharged PS4 Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/combatting-ps5-intermittent-connection-issues/"><u>Combatting PS5 Intermittent Connection Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/diagnosing-and-solving-gpu-induced-image-droop/"><u>Diagnosing & Solving GPU-Induced Image Droop</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-motorola-moto-g14-device-sim-by-drfone-android/"><u>Easily Unlock Your Motorola Moto G14 Device SIM</u></a></li>
<li><a href="https://tech-revival.techidaily.com/free-instant-music-downloads-master-the-quick-guide-to-securing-every-track-on-hearthisat-now/"><u>Free Instant Music Downloads! Master the Quick Guide to Securing Every Track on Hearthis.at Now!</u></a></li>
<li><a href="https://games-able.techidaily.com/from-silver-to-core-xbox-live-gold-upgrade/"><u>From Silver to Core: Xbox Live Gold Upgrade</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-poco-x6-pro-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Poco X6 Pro Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-art-of-television-problem-solving-top-strategies-for-diy-repairs/"><u>Mastering the Art of Television Problem-Solving: Top Strategies for DIY Repairs</u></a></li>
<li><a href="https://games-able.techidaily.com/prime-xbox-video-capturing-solutions-reviewed/"><u>Prime Xbox Video Capturing Solutions Reviewed</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-installing-the-latest-ralink-network-adapters-on-your-windows-machine/"><u>Step-by-Step: Installing the Latest Ralink Network Adapters on Your Windows Machine</u></a></li>
<li><a href="https://games-able.techidaily.com/top-controller-enabled-phone-games-selection/"><u>Top Controller-Enabled Phone Games Selection</u></a></li>
</ul></div>


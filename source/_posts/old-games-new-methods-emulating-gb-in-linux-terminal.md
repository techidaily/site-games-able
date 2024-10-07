---
title: "Old Games, New Methods: Emulating GB in Linux Terminal"
date: 2024-10-02T16:44:58.169Z
updated: 2024-10-07T18:41:56.797Z
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
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1915805/19272" target="_top" id="1915805">
  <img src="//a.impactradius-go.com/display-ad/19272-1915805" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915805/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-bulk-buy-subscribers-cost-effective-growth-strategy/"><u>[New] 2024 Approved Bulk Buy Subscribers Cost-Effective Growth Strategy</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-capturing-ps4-gaming-magic-in-full-detail-using-obs/"><u>[New] Capturing PS4 Gaming Magic in Full Detail Using OBS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-framefraction-analysis/"><u>[New] FrameFraction Analysis</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-focus-on-the-details-with-videoleaps-zooming-feature/"><u>[Updated] In 2024, Focus on the Details with Videoleap's Zooming Feature</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-step-by-step-to-adobe-cloud-success-and-non-adobe-options/"><u>[Updated] Step-by-Step to Adobe Cloud Success & Non-Adobe Options</u></a></li>
<li><a href="https://games-able.techidaily.com/4-essential-steps-for-amplifying-xbox-point-advantages/"><u>4 Essential Steps for Amplifying Xbox Point Advantages</u></a></li>
<li><a href="https://games-able.techidaily.com/7-unrecognized-benefits-in-ignoring-ray-tracings-hype/"><u>7 Unrecognized Benefits in Ignoring Ray Tracing's Hype</u></a></li>
<li><a href="https://games-able.techidaily.com/apple-macos-sonoma-how-game-mode-enhances-gaming-experience/"><u>Apple MacOS Sonoma: How Game Mode Enhances Gaming Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-game-speakers-prioritize-headphones/"><u>Avoid Game Speakers, Prioritize Headphones</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effective-strategies-to-address-and-prevent-dpc-watchdog-failures-in-windows-11-systems/"><u>Effective Strategies to Address and Prevent DPC Watchdog Failures in Windows 11 Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/enhancing-your-gaming-experience-by-correcting-stutters-and-hangs-in-outriders-pc/"><u>Enhancing Your Gaming Experience by Correcting Stutters and Hangs in Outriders (PC)</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-asus-rog-phone-8-pro-by-drfone-android/"><u>In 2024, How to Bypass FRP from Asus ROG Phone 8 Pro?</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-level-up-your-video-editing-with-20-free-adobe-premiere-intro-templates/"><u>In 2024, Level Up Your Video Editing with 20 Free Adobe Premiere Intro Templates</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161039995-on-the-spot-web-game-selection-here/"><u>On the Spot Web Game Selection, Here!</u></a></li>
</ul></div>


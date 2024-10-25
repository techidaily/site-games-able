---
title: "Game Boy Reimagined: Linux Terminal Edition"
date: 2024-10-18T22:26:30.208Z
updated: 2024-10-24T17:37:06.576Z
tags:
  - games
categories:
  - games
description: "This Article Describes Game Boy Reimagined: Linux Terminal Edition"
excerpt: "This Article Describes Game Boy Reimagined: Linux Terminal Edition"
keywords: GameBoyLinuxLE,GBC_Terminal,LE_Gaming,LinuxGBRevise,PortableConsole,RetroGameOS,LEPortableDevice
thumbnail: https://thmb.techidaily.com/78af3078c80b8e3712553330740f219cdae8af451a75522402de746ab069fea1.jpg
---

## Game Boy Reimagined: Linux Terminal Edition

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
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425">
  <img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-going-from-frame-to-note-on-instagrams-mp3-route/"><u>[New] 2024 Approved Going From Frame-to-Note on Instagram's Mp3 Route</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-xiaomi-13t-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Xiaomi 13T without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/canvas-audio-guide-adding-tweaking-and-refining-sounds-for-2024/"><u>Canva's Audio Guide Adding, Tweaking, & Refining Sounds for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-deeper-5-ways-paying-for-mobile-games-improves-experience/"><u>Dive Deeper: 5 Ways Paying for Mobile Games Improves Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-guide-to-overcoming-file-creation-error-30005/"><u>Essential Guide to Overcoming File Creation Error 30005</u></a></li>
<li><a href="https://games-able.techidaily.com/guaranteeing-steams-seamless-data-transfer/"><u>Guaranteeing Steam’s Seamless Data Transfer</u></a></li>
<li><a href="https://discover-helper.techidaily.com/how-to-transfer-images-from-your-computer-to-your-iphone-without-using-itunes-or-losing-data/"><u>How to Transfer Images From Your Computer to Your iPhone Without Using iTunes or Losing Data</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-iphone-8-plus-lock-screen-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From iPhone 8 Plus Lock Screen</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-multiple-ps5-subscriptions-management/"><u>Mastering Multiple PS5 Subscriptions Management</u></a></li>
<li><a href="https://win11-tips.techidaily.com/optimize-image-size-on-windows-11-explore-the-best-techniques/"><u>Optimize Image Size on Windows 11: Explore the Best Techniques</u></a></li>
<li><a href="https://games-able.techidaily.com/resetting-joystick-settings-post-update-on-console/"><u>Resetting Joystick Settings Post-Update on Console</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/scrutinizing-splitcam-a-leader-in-video-tech/"><u>Scrutinizing SplitCam - A Leader in Video Tech?</u></a></li>
<li><a href="https://games-able.techidaily.com/the-insiders-guide-to-exclusive-free-steam-gaming-hits/"><u>The Insider's Guide to Exclusive, Free Steam Gaming Hits</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/the-ultimate-mp4-video-editing-tutorial-for-mac-and-windows-users-for-2024/"><u>The Ultimate MP4 Video Editing Tutorial for Mac and Windows Users for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/top-tous-les-livres-electroniques-gratuits-pour-lecteurs-en-2024/"><u>Top Tous Les Livres Électroniques Gratuits Pour Lecteurs en 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/virtual-realms-unleashed-best-ethernets-for-seamless-playing/"><u>Virtual Realms Unleashed: Best Ethernets for Seamless Playing</u></a></li>
</ul></div>


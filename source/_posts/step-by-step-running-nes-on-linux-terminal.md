---
title: "Step-by-Step: Running NES on Linux Terminal"
date: 2024-10-12T10:34:10.462Z
updated: 2024-10-13T02:23:06.322Z
tags:
  - games
categories:
  - games
description: "This Article Describes Step-by-Step: Running NES on Linux Terminal"
excerpt: "This Article Describes Step-by-Step: Running NES on Linux Terminal"
keywords: Linux NES Emulation,Run NES Linux,NES Terminal Tutorial,Emulate Nintendo Console,Linux Gaming Guide,Step-by-Step Terminal Execution,Old Games on Modern OS
thumbnail: https://thmb.techidaily.com/3dd5b17c533ab88ed9cc0f3b00c7a2aa3b7c864b4f9c2a1611133710cbbaabe1.jpg
---

## Step-by-Step: Running NES on Linux Terminal

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
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137976/21526" target="_top" id="2137976">
  <img src="//a.impactradius-go.com/display-ad/21526-2137976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137976/21526" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/new-snapshot-strategies-maintaining-consistent-snapstreaks-for-2024/"><u>[New] Snapshot Strategies Maintaining Consistent Snapstreaks for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-addressing-distorted-media-on-youtube-platform/"><u>[Updated] Addressing Distorted Media on YouTube Platform</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-for-efficient-use-of-movie-maker-in-windows-8/"><u>[Updated] Expert Tips for Efficient Use of Movie Maker in Windows 8</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-path-to-prominence-with-powerful-instagram-video-narratives/"><u>[Updated] In 2024, The Path to Prominence with Powerful Instagram Video Narratives</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-methodical-path-to-discovering-hidden-youtube-footage-for-2024/"><u>[Updated] The Methodical Path to Discovering Hidden YouTube Footage for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-repair-glitches-in-instagram-likescomments/"><u>2024 Approved Repair Glitches in Instagram Likes/Comments</u></a></li>
<li><a href="https://android-unlock.techidaily.com/6-proven-ways-to-unlock-samsung-galaxy-a05-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Samsung Galaxy A05 Phone When You Forget the Password</u></a></li>
<li><a href="https://games-able.techidaily.com/deep-dive-into-javas-most-loved-game-features/"><u>Deep Dive Into Java's Most Loved Game Features</u></a></li>
<li><a href="https://games-able.techidaily.com/filing-grievances-unacceptable-conduct-in-xbox-sandx/"><u>Filing Grievances: Unacceptable Conduct in Xbox S&X</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-at-60-vs-30-what-does-it-really-mean/"><u>Gaming at 60 Vs. 30: What Does It Really Mean?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/mastering-the-mechanics-an-introduction-to-gopro-time-lapse/"><u>Mastering the Mechanics An Introduction to GoPro Time-Lapse</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-steam-access-delays-on-rust-pcs/"><u>Navigating Steam Access Delays on Rust PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-display-driver-failed-error-in-windows-1111-update/"><u>Overcoming Display Driver Failed Error in Windows 11/11 Update</u></a></li>
<li><a href="https://games-able.techidaily.com/step-back-in-time-with-classic-psp-games-on-iphone/"><u>Step Back in Time with Classic PSP Games on iPhone</u></a></li>
<li><a href="https://games-able.techidaily.com/tailored-audio-settings-for-xbox-series-xs/"><u>Tailored Audio Settings for Xbox Series X/S</u></a></li>
<li><a href="https://vp-tips.techidaily.com/transformation-mp4-vers-mov-en-ligne-sans-frais-guide-complet/"><u>Transformation MP4 Vers MOV en Ligne Sans Frais - Guide Complet</u></a></li>
<li><a href="https://games-able.techidaily.com/uniting-retro-docks-and-new-switch-oled/"><u>Uniting Retro Docks and New Switch OLED</u></a></li>
</ul></div>


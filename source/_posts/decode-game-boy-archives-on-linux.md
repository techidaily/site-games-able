---
title: Decode Game Boy Archives on Linux
date: 2024-09-25T19:32:38.976Z
updated: 2024-10-01T16:42:22.998Z
tags:
  - games
categories:
  - games
description: This Article Describes Decode Game Boy Archives on Linux
excerpt: This Article Describes Decode Game Boy Archives on Linux
keywords: GameBoyLinuxArchives,DecodingGBOnLinux,GameBoyRetroLinux,LinuxGameBoyHacks,GBArchiveLinuxTools,RetroGameBoyLinux,GBLinuxDecoder
thumbnail: https://thmb.techidaily.com/d20fb0a2bb9049e2210bb23aa9225c390244059cedf35b9a34d45f9a041c8543.jpg
---

## Decode Game Boy Archives on Linux

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
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-the-best-practices-for-recording-apex-heroes/"><u>[Updated] In 2024, The Best Practices for Recording Apex Heroes</u></a></li>
<li><a href="https://fox-that.techidaily.com/dynamic-head-tracking-buzz-in-your-airpods-how-to-disable-it/"><u>Dynamic Head Tracking Buzz in Your AirPods? How to Disable It</u></a></li>
<li><a href="https://games-able.techidaily.com/elite-game-economies-place-for-microtransactions/"><u>Elite Game Economies: Place for Microtransactions?</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-gaming-experience-console-to-pc-transition/"><u>Enhancing Gaming Experience: Console to PC Transition</u></a></li>
<li><a href="https://games-able.techidaily.com/expertly-designed-multi-port-adapters-for-gaming/"><u>Expertly Designed Multi-Port Adapters for Gaming</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-ipogo-will-be-the-new-ispoofer-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>In 2024, iPogo will be the new iSpoofer On Apple iPhone 11? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-realme-narzo-60-pro-5g-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Realme Narzo 60 Pro 5G Phone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-virtual-sessions-a-compreayer-to-using-zoom-in-windows-10-for-2024/"><u>Mastering Virtual Sessions A Compreayer to Using Zoom in Windows 10 for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-sign-of-life-on-your-laptop-screen/"><u>No Sign of Life on Your Laptop Screen?</u></a></li>
<li><a href="https://games-able.techidaily.com/screen-size-strategies-for-gamers/"><u>Screen Size Strategies for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/the-nostalgia-factor-meets-todays-tech-edge/"><u>The Nostalgia Factor Meets Today's Tech Edge</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-itel-p55-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Itel P55 Phones</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlock-your-tunes-curated-list-of-websites-for-youtuberingtones-for-2024/"><u>Unlock Your Tunes Curated List of Websites For YouTubeRingtones for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/using-a-modern-dualsense-in-an-earlier-system/"><u>Using a Modern DualSense in an Earlier System?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/winx-dvd-ripper-platinum-quick-and-easy-5-minute-conversion-to-mp4-h264hevc/"><u>WinX DVD Ripper Platinum: Quick & Easy 5-Minute Conversion to MP4 (H.264/HEVC)</u></a></li>
</ul></div>


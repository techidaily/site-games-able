---
title: "Linux Terminal: Mastering Game Boy Classics"
date: 2024-10-14T21:58:46.986Z
updated: 2024-10-19T07:20:25.517Z
tags:
  - games
categories:
  - games
description: "This Article Describes Linux Terminal: Mastering Game Boy Classics"
excerpt: "This Article Describes Linux Terminal: Mastering Game Boy Classics"
keywords: Game Boy Revive,BASIC Game Play,Classic Gaming Terminal,Linux Retro Games,BASIC Console Game,Terminal Gaming Mastery,Game Boy Terminal Games
thumbnail: https://thmb.techidaily.com/1d7a3c5b577ddb7940a6a2457c0bee5c40f1807e21452ed2f6065cb51e5a9f16.jpg
---

## Linux Terminal: Mastering Game Boy Classics

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
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://games-able.techidaily.com/connect-your-realms-a-step-by-step-guide-to-epicplussteam/"><u>Connect Your Realms: A Step by Step Guide to Epic+Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/curtailing-surveillance-from-the-xbox-game-bar-on-windows/"><u>Curtailing Surveillance From the Xbox Game Bar on Windows</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/expert-analysis-of-the-playstation-4-pro-combining-console-gaming-with-ultra-hd-visuals/"><u>Expert Analysis of the PlayStation 4 Pro: Combining Console Gaming with Ultra HD Visuals</u></a></li>
<li><a href="https://technical-tips.techidaily.com/finding-and-purchasing-an-optimal-television-solution-tailored-to-your-home-environment/"><u>Finding and Purchasing an Optimal Television Solution Tailored to Your Home Environment</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-from-ordinary-to-stunning-a-guide-to-hdr-portraits/"><u>In 2024, From Ordinary to Stunning A Guide to HDR Portraits</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-apple-iphone-13-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Apple iPhone 13 Pro Max | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/master-the-art-of-checking-pc-component-compatibility/"><u>Master the Art of Checking PC Component Compatibility</u></a></li>
<li><a href="https://games-able.techidaily.com/reimagine-gaming-on-idevices-these-are-the-best-4-emulators/"><u>Reimagine Gaming on iDevices: These Are the Best 4 Emulators</u></a></li>
<li><a href="https://fox-making.techidaily.com/step-by-step-guide-recovering-your-emails-using-windows-live-mail-backups/"><u>Step-by-Step Guide: Recovering Your Emails Using Windows Live Mail Backups</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-undercover-guide-to-enhancing-your-window-11-experience-for-2024/"><u>The Undercover Guide to Enhancing Your WINDOW 11 Experience for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unpacking-the-sudden-urge-how-apples-affordable-usb-c-earpods-became-my-prime-day-must-have-insights/"><u>Unpacking the Sudden Urge: How Apple's Affordable USB-C EarPods Became My Prime Day Must-Have – Insights</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-top-rated-free-wmv-video-editing-tools-expert-recommendations/"><u>Updated In 2024, Top-Rated Free WMV Video Editing Tools Expert Recommendations</u></a></li>
<li><a href="https://games-able.techidaily.com/upgrading-dualsense-remotely-a-step-by-step-guide/"><u>Upgrading DualSense Remotely: A Step-by-Step Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-behind-xboxs-rule-enforcement/"><u>What Is Behind Xbox’s Rule Enforcement?</u></a></li>
</ul></div>


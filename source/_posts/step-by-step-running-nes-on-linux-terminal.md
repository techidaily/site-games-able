---
title: "Step-by-Step: Running NES on Linux Terminal"
date: 2024-10-02T16:15:46.498Z
updated: 2024-10-07T18:23:32.002Z
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
<a href="https://appsumo.8odi.net/c/5597632/2144281/7443" target="_top" id="2144281">
  <img src="//a.impactradius-go.com/display-ad/7443-2144281" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144281/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-unleash-creativity-on-instagram-mastering-bulk-image-and-video-additions/"><u>[New] 2024 Approved Unleash Creativity on Instagram Mastering Bulk Image & Video Additions</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-fostering-followers-with-flashy-instagram-puzzles-that-stand-out-for-2024/"><u>[New] Fostering Followers with Flashy Instagram Puzzles that Stand Out for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-step-by-step-recording-google-voice-conversations-for-2024/"><u>[New] Step-by-Step Recording Google Voice Conversations for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-achieving-virality-in-instagram-videos-practical-advice/"><u>[Updated] 2024 Approved Achieving Virality in Instagram Videos Practical Advice</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-increase-your-social-media-reach-with-these-top-30-tiktok-nicknames-for-2024/"><u>[Updated] Increase Your Social Media Reach with These Top 30 TikTok Nicknames for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/complete-game-count-in-epics-library-steps-to-overcome-errors/"><u>Complete Game Count in Epic’s Library - Steps to Overcome Errors</u></a></li>
<li><a href="https://games-able.techidaily.com/console-to-pc-discover-the-game-changing-reasons/"><u>Console to PC: Discover the Game-Changing Reasons</u></a></li>
<li><a href="https://games-able.techidaily.com/end-of-ps5-scarcity-anticipated-price-reduction/"><u>End of PS5 Scarcity: Anticipated Price Reduction</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-xiaomi-redmi-note-13-proplus-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Xiaomi Redmi Note 13 Pro+ 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-contacts-from-realme-by-fonelab-android-recover-contacts/"><u>How to recover deleted contacts from Realme .</u></a></li>
<li><a href="https://games-able.techidaily.com/ideal-portable-chargers-for-sony-console-gaming/"><u>Ideal Portable Chargers: For Sony Console Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/sky-high-performance-windows-for-the-steam-deck/"><u>Sky-High Performance: Windows for the Steam Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-for-integrating-your-modern-gamepad-into-windows-156-chars/"><u>The Ultimate Guide for Integrating Your Modern Gamepad Into Windows (156 Chars)</u></a></li>
<li><a href="https://os-tips.techidaily.com/top-ios-18-update-perks-every-android-fan-should-know/"><u>Top iOS 18 Update Perks Every Android Fan Should Know!</u></a></li>
<li><a href="https://games-able.techidaily.com/top-tier-tools-to-transform-your-gaming-world/"><u>Top-Tier Tools to Transform Your Gaming World</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-quicktime-video-editing-for-mac-users-a-step-by-step-tutorial/"><u>Updated In 2024, QuickTime Video Editing for Mac Users A Step-by-Step Tutorial</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-corsairs-icue-link-4-reasons-to-upgrade/"><u>What Is Corsair's iCUE LINK? 4 Reasons to Upgrade</u></a></li>
</ul></div>


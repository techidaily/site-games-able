---
title: Linux Emulator Techniques for Game Boy Titles
date: 2024-06-25T13:16:47.399Z
updated: 2024-06-26T13:16:47.399Z
tags:
  - games
categories:
  - games
description: This Article Describes Linux Emulator Techniques for Game Boy Titles
excerpt: This Article Describes Linux Emulator Techniques for Game Boy Titles
keywords: GameBoy Linux,EmulateGBTitles,LinuxGameBoy,GBGameConsole,TitleEmulation,LinuxGaming,EmulatorTechniques
thumbnail: https://thmb.techidaily.com/ac86b0aa564fee722115c20830e542db073002bfbdd584be2acd66419238b8a6.png
---

## Linux Emulator Techniques for Game Boy Titles

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
<li><a href="https://games-able.techidaily.com/steams-10-year-revamp-game-access-revolutionized-for-families/"><u>Steam's 10-Year Revamp: Game Access Revolutionized for Families</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-quest-from-download-to-dynamic-diversion/"><u>Quick Quest: From Download to Dynamic Diversion</u></a></li>
<li><a href="https://games-able.techidaily.com/unboxing-lenovos-best-legion-go-features-at-ifa-2-written-by-alex-johnson-mba/"><u>Unboxing Lenovo's Best Legion Go Features at IFA 2 Written by Alex Johnson, MBA</u></a></li>
<li><a href="https://games-able.techidaily.com/finding-independent-gaming-delights-on-itchio/"><u>Finding Independent Gaming Delights on Itch.io</u></a></li>
<li><a href="https://games-able.techidaily.com/linking-headphones-to-sony-gaming-system/"><u>Linking Headphones to Sony Gaming System</u></a></li>
<li><a href="https://games-able.techidaily.com/investing-in-style-reaping-gameplay-rewards/"><u>Investing in Style, Reaping Gameplay Rewards</u></a></li>
<li><a href="https://games-able.techidaily.com/eliminating-windows-1011-writable-device-stall-0x887a0006/"><u>Eliminating Windows 10/11' Writable Device Stall (0X887A0006)</u></a></li>
<li><a href="https://games-able.techidaily.com/tune-treasure-hunters-discovering-hidden-musical-gems/"><u>Tune Treasure Hunters: Discovering Hidden Musical Gems</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-techs-edge-series-x-vs-custom-pc/"><u>Exploring Tech's Edge: Series X VS. Custom PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-path-to-efficient-workflow-learning-voice-to-text-conversion-in-ms-word/"><u>[New] The Path to Efficient Workflow  Learning Voice-to-Text Conversion in MS Word</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/enhance-discord-conversations-a-recorders-insight/"><u>Enhance Discord Conversations  A Recorder's Insight</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-virtual-collaboration-share-your-screens-with-facebook-viewers/"><u>[New] Virtual Collaboration  Share Your Screens with Facebook Viewers</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-understanding-your-needs-for-a-precise-vimeo-subscription-level-for-2024/"><u>[Updated] Understanding Your Needs for a Precise Vimeo Subscription Level for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/unveiling-the-role-of-authenticity-in-online-self-portraits/"><u>Unveiling the Role of Authenticity in Online Self-Portraits</u></a></li>
<li><a href="https://animation-videos.techidaily.com/how-to-make-slideshow-in-linkedin/"><u>How to Make Slideshow in LinkedIn</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-securing-your-gameplay-on-windows-10-the-5-essentials-for-2024/"><u>[New] Securing Your Gameplay on Windows 10  The 5 Essentials for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-sonic-sleuths-den-acquire-and-scrutinize-audio-files-for-2024/"><u>[Updated] Sonic Sleuths' Den  Acquire & Scrutinize Audio Files for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-showdown-of-streamers-which-platform-rules-obs-or-twitch-studio/"><u>2024 Approved  Showdown of Streamers  Which Platform Rules, OBS or Twitch Studio?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/proven-strategies-for-successful-youtube-shorts-for-2024/"><u>Proven Strategies for Successful YouTube Shorts for 2024</u></a></li>
</ul></div>

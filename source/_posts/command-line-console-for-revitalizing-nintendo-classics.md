---
title: Command-Line Console for Revitalizing Nintendo Classics
date: 2024-06-25T13:16:20.794Z
updated: 2024-06-26T13:16:20.794Z
tags:
  - games
categories:
  - games
description: This Article Describes Command-Line Console for Revitalizing Nintendo Classics
excerpt: This Article Describes Command-Line Console for Revitalizing Nintendo Classics
keywords: Nintendo Classic Console,Retro Gaming Replay,Command-Line Fun,Revive Old Games,Cli Console Classic,Nostalgic Gaming Console,Reimagine Classics
thumbnail: https://thmb.techidaily.com/7dc1f793da1f2b9c448c995323e3532e944d0308246b622538179ed42958d614.jpg
---

## Command-Line Console for Revitalizing Nintendo Classics

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
<li><a href="https://games-able.techidaily.com/gameplay-exploration-older-titles-on-new-ps-console/"><u>Gameplay Exploration: Older Titles on New PS Console</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-sourcing-indie-games-online/"><u>Mastering the Art of Sourcing Indie Games Online</u></a></li>
<li><a href="https://games-able.techidaily.com/what-makes-a-great-steam-deck/"><u>What Makes a Great Steam Deck?</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-top-independent-games-on-itchio/"><u>Unveiling Top Independent Games on Itch.io</u></a></li>
<li><a href="https://games-able.techidaily.com/comprehensive-examination-of-console-time-tracking/"><u>Comprehensive Examination of Console Time Tracking</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-list-of-apples-pre-installed-offline-games/"><u>The Ultimate List of Apple's Pre-Installed, Offline Games</u></a></li>
<li><a href="https://games-able.techidaily.com/get-hooked-on-these-6-non-monetary-gaming-treasures/"><u>Get Hooked on These 6 Non-Monetary Gaming Treasures</u></a></li>
<li><a href="https://games-able.techidaily.com/live-laugh-and-stream-with-twitch-app-on-the-go/"><u>Live, Laugh & Stream with Twitch App on the Go</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionize-your-gaming-shift-from-console-to-pc/"><u>Revolutionize Your Gaming: Shift From Console to PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-show-wi-fi-password-on-oneplus-ace-2-by-drfone-android/"><u>How to Show Wi-Fi Password on OnePlus Ace 2</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-flip-content-sequence-android-video-workaround/"><u>[New] Flip Content Sequence  Android Video Workaround</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/the-ultimate-movie-making-blueprint-easy-and-fast-for-2024/"><u>The Ultimate Movie Making Blueprint Easy and Fast for 2024</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-tecno-phantom-v-flip-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-pinpointing-the-leading-10-invisible-story-enthusiasts/"><u>In 2024, Pinpointing the Leading 10 Invisible Story Enthusiasts</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-infinix-zero-5g-2023-turbo-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From Infinix Zero 5G 2023 Turbo to Apple TV | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-conquered-everlasting-deactivation-of-youtube-shorts/"><u>[Updated] 2024 Approved  Conquered  Everlasting Deactivation of YouTube Shorts</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-fix-oem-unlock-missing-on-nokia-c22-by-drfone-android/"><u>In 2024, How To Fix OEM Unlock Missing on Nokia C22?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-funnyframe-generator/"><u>In 2024, FunnyFrame Generator</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-best-meme-generator-app-downlaod/"><u>[Updated] In 2024, Best Meme Generator App Downlaod</u></a></li>
</ul></div>

---
title: Command-Line Console for Revitalizing Nintendo Classics
date: 2024-07-12T03:51:35.743Z
updated: 2024-07-13T03:51:35.743Z
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
<li><a href="https://games-able.techidaily.com/the-evolution-of-smoother-gaming-introducing-nvidia-g-sync/"><u>The Evolution of Smoother Gaming: Introducing Nvidia G-Sync</u></a></li>
<li><a href="https://games-able.techidaily.com/sony-psp-gaming-perks-reviewed/"><u>Sony PSP Gaming Perks, Reviewed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-a-guide-to-essential-asmr-video-facts/"><u>[Updated] In 2024, A Guide to Essential ASMR Video Facts</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-print-saturation-with-windows-11/"><u>Avoiding Print Saturation with Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/nvidias-rtx-4060-ti-unveiling-matching-gpus/"><u>Nvidia's RTX 4060 Ti: Unveiling Matching GPUs</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-finder-ps5-ssds-rated/"><u>Ultimate Finder: PS5 SSDs Rated</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-your-steam-experience-fixes-for-windows-11/"><u>Streamline Your Steam Experience: Fixes for Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionize-gaming-and-productivity-the-4-reasons-to-choose-corsairs-icue-link/"><u>Revolutionize Gaming and Productivity - The 4 Reasons to Choose Corsair’s iCUE Link</u></a></li>
<li><a href="https://games-able.techidaily.com/unbeatable-connectivity-choosing-top-ethernets/"><u>Unbeatable Connectivity: Choosing Top Ethernets</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-wireless-or-hardwired-optimal-gaming-connections/"><u>Superior Wireless or Hardwired? Optimal Gaming Connections</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-perfected-presence-the-art-of-blurring-conference-backdrops/"><u>In 2024, Perfected Presence  The Art of Blurring Conference Backdrops</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-artistry-in-your-pocket-the-bestiary-of-top-8-iphone-drawing-apps/"><u>2024 Approved  Artistry in Your Pocket  The Bestiary of Top 8 iPhone Drawing Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/top-10-free-online-fps-games-for-web-browsers/"><u>Top 10 Free Online FPS Games for Web Browsers</u></a></li>
<li><a href="https://games-able.techidaily.com/pure-endless-fun-awaits-with-the-best-mobile-games-free/"><u>Pure, Endless Fun Awaits with the Best Mobile Games (Free!)</u></a></li>
<li><a href="https://games-able.techidaily.com/supercharge-live-streams-select-best-7-bots-for-twitch-expertise/"><u>Supercharge Live Streams: Select Best 7 Bots For Twitch Expertise</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173202710-2024s-ddr5-master-cards-ranked/"><u>2024'S DDR5 Master Cards Ranked!</u></a></li>
<li><a href="https://games-able.techidaily.com/sync-up-smoothly-implementing-controller-updates-virtually/"><u>Sync Up: Smoothly Implementing Controller Updates Virtually</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-screensnipers-digest-the-ultimate-2023-software-roundup/"><u>[Updated] 2024 Approved  ScreenSniper's Digest  The Ultimate 2023 Software Roundup</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-ps5-dualsense-chargers-of-the-future/"><u>Superior PS5 DualSense Chargers of the Future</u></a></li>
<li><a href="https://games-able.techidaily.com/the-pathway-to-your-steam-login-reference-code/"><u>The Pathway to Your Steam Login Reference Code</u></a></li>
<li><a href="https://games-able.techidaily.com/a-tactical-approach-to-choosing-an-elgato-stream-deck/"><u>A Tactical Approach to Choosing an Elgato Stream Deck</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/in-2024-what-is-mov-format-and-how-to-edit-mov-video-creatively/"><u>In 2024, What Is MOV Format and How To Edit MOV Video Creatively?</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/best-voice-chat-apps-for-gamers-for-2024/"><u>Best Voice Chat Apps for Gamers for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-do-infinix-note-30i-screen-sharing-drfone-by-drfone-android/"><u>In 2024, How To Do Infinix Note 30i Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-easy-ways-to-merge-igtv-and-instagram-stories/"><u>[New] Easy Ways to Merge IGTV & Instagram Stories</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-complete-guide-to-tiktok-screen-size-and-aspect-ratio-for-2024/"><u>Updated The Complete Guide to TikTok Screen Size and Aspect Ratio for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-rippleringers-finding-the-happiest-online-rhythms/"><u>2024 Approved  RippleRingers  Finding the Happiest Online Rhythms</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/mobile-split-screen-mastery-top-video-apps-for-2024/"><u>Mobile Split Screen Mastery Top Video Apps for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-shell-the-creme-de-la-creme-case-2024/"><u>Ultimate Shell: The Crème De La Crème Case, 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/solving-the-vanishing-game-issue-on-egs-digital-shelf/"><u>Solving the Vanishing Game Issue on EG's Digital Shelf</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Motorola Razr 40? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/safeguarding-your-playstation-5-games-with-a-passcode/"><u>Safeguarding Your PlayStation 5 Games with a Passcode</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-s17-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Vivo S17? | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-perfect-your-macs-microphone-usage-with-this-guide-to-audacity/"><u>[New] 2024 Approved  Perfect Your Mac's Microphone Usage with This Guide to Audacity</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/download-free-sound-effects-for-youtubers/"><u>Download Free Sound Effects for YouTubers</u></a></li>
<li><a href="https://games-able.techidaily.com/the-most-immersive-mobile-mmo-experiences/"><u>The Most Immersive Mobile MMO Experiences</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-guaranteed-tiktok-footage-storage-phone-edition/"><u>[New] Guaranteed TikTok Footage Storage  Phone Edition</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-kid-friendly-drone-guide-for-first-flyers-for-2024/"><u>The Ultimate Kid-Friendly Drone Guide for First Flyers for 2024</u></a></li>
</ul></div>

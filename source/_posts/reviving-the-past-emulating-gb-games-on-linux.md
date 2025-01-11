---
title: "Reviving the Past: Emulating GB Games on Linux"
date: 2025-01-06T21:54:45.941Z
updated: 2025-01-10T21:47:14.834Z
tags:
  - games
categories:
  - games
description: "This Article Describes Reviving the Past: Emulating GB Games on Linux"
excerpt: "This Article Describes Reviving the Past: Emulating GB Games on Linux"
keywords: Revive Old Games,GBA Console Re-Create,Linux Game Porting,Retro PC Gaming,Legacy Game Emulation,Historical Game Launcher,Linux Emulator GB
thumbnail: https://thmb.techidaily.com/1e40e68e85695875cbdf7c309b6e95c0f93def47629f17026d118c0eda7b469c.png
---

## Reviving the Past: Emulating GB Games on Linux

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Emulate a Game Boy in the Terminal?

![pokemon red star splash screen in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/pokemon-red-star-splash-screen-in-the-linux-terminal.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/f-yPCh24EsA?si=3z8FAd_lMZeAjug7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-learn-to-cut-out-the-unwanted-a-guide-to-erasing-background/"><u>[New] 2024 Approved Learn to Cut Out the Unwanted A Guide to Erasing Background</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-guide-to-unparalleled-streaming-experience/"><u>[New] The Ultimate Guide to Unparalleled Streaming Experience</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-cut-out-facebook-stories-step-by-step-for-pc-and-phones/"><u>[Updated] Cut Out Facebook Stories Step-By-Step for PC & Phones</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-amplify-your-influence-the-ultimate-list-of-instagram-apps/"><u>[Updated] In 2024, Amplify Your Influence The Ultimate List of Instagram Apps</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/exploring-the-distinctive-features-in-each-version-of-aomei-backupper-software/"><u>Exploring the Distinctive Features in Each Version of AOMEI Backupper Software</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-itel-a05s-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Itel A05s Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-20-best-anime-opening-songs-of-all-time/"><u>In 2024, 20 Best Anime Opening Songs of All Time</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-apple-iphone-x-asking-for-passcode-after-ios-1714-update-what-to-do-drfone-by-drfone-ios/"><u>In 2024, Apple iPhone X Asking for Passcode after iOS 17/14 Update, What to Do? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-vrr-feature-for-smooth-gameplay-on-xbox-console/"><u>Mastering the VRR Feature for Smooth Gameplay on Xbox Console</u></a></li>
<li><a href="https://games-able.techidaily.com/preserve-steam-captures-step-by-step-guide/"><u>Preserve Steam Captures: Step-by-Step Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-fixes-for-cloud-synching-on-steam-devices/"><u>Quick Fixes for Cloud Synching on Steam Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/smart-and-efficient-charger-kits-for-ps5-dualsense/"><u>Smart & Efficient Charger Kits for PS5 DualSense</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-missing-opencl-dynamic-libraries/"><u>Tackling Missing OpenCL Dynamic Libraries</u></a></li>
<li><a href="https://games-able.techidaily.com/tetris-talent-showdowns-on-android-and-ios-devices/"><u>Tetris Talent Showdowns on Android and iOS Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-emulation-guide-for-the-best-steam-deck-gaming/"><u>The Ultimate Emulation Guide for the Best Steam Deck Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-the-mystery-of-virtual-realitys-exorbitant-pricing/"><u>Unlocking the Mystery of Virtual Reality's Exorbitant Pricing</u></a></li>
<li><a href="https://games-able.techidaily.com/what-makes-cozy-games-a-haven/"><u>What Makes Cozy Games a Haven?</u></a></li>
</ul></div>


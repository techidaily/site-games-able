---
title: "Linux Console Power: Playing Emulated Game Boys"
date: 2024-12-05T16:56:11.681Z
updated: 2024-12-11T07:18:14.142Z
tags:
  - games
categories:
  - games
description: "This Article Describes Linux Console Power: Playing Emulated Game Boys"
excerpt: "This Article Describes Linux Console Power: Playing Emulated Game Boys"
keywords: Emulated GBC,Linux Emulation,Console Games,Emulated Consoles,Linux Gaming,Retro Games Emulator,Game Boy Console Play
thumbnail: https://thmb.techidaily.com/c8cdb9a666b994c5df18bf9fb906f435b3e886e46b814d7626bddc0615133ba1.jpg
---

## Linux Console Power: Playing Emulated Game Boys

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Emulate a Game Boy in the Terminal?

![pokemon red star splash screen in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/pokemon-red-star-splash-screen-in-the-linux-terminal.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-direct.techidaily.com/updated-encompassing-understanding-the-essence-of-googles-podcasts-app/"><u>[Updated] Encompassing Understanding The Essence of Google's Podcasts App</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-your-guide-to-the-best-igtv-virtuosos/"><u>[Updated] In 2024, Your Guide to the Best IGTV Virtuosos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-silent-spectator-of-social-media-snippets/"><u>[Updated] Silent Spectator of Social Media Snippets</u></a></li>
<li><a href="https://games-able.techidaily.com/considering-ps5-delay-these-4-factors-matter/"><u>Considering PS5 Delay? These 4 Factors Matter</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-the-best-of-lenovo-legion-go-at-ifa/"><u>Exploring the Best of Lenovo Legion Go at IFA</u></a></li>
<li><a href="https://facebook.techidaily.com/facebooks-oversight-board-will-soon-announce-ruling-on-trumps-ban/"><u>Facebook's Oversight Board Will Soon Announce Ruling on Trump's Ban</u></a></li>
<li><a href="https://games-able.techidaily.com/gpd-win-4-portable-computing-redefined/"><u>GPD Win 4: Portable Computing Redefined</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/harmonious-journey-from-picture-to-playlist-for-2024/"><u>Harmonious Journey From Picture to Playlist for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-realme-narzo-60x-5g-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Realme Narzo 60x 5G Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-keep-playing-smart-iso-compression-using-chdman-methods/"><u>How to Keep Playing: Smart ISO Compression Using ChDMan Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-repair-and-sustain-your-xbox-sandx/"><u>How to Repair and Sustain Your Xbox S&X</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-xiaomi-14-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Xiaomi 14 to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-flick-flashback-an-old-school-take-on-the-goofys/"><u>In 2024, Flick Flashback An Old-School Take on The Goofys</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-bypass-iphone-xs-max-passcode-easily-video-inside-by-drfone-ios/"><u>In 2024, How to Bypass iPhone XS Max Passcode Easily Video Inside</u></a></li>
<li><a href="https://games-able.techidaily.com/innocns-budget-friendly-gamers-choice/"><u>InnoCN's Budget-Friendly Gamer's Choice</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-playtime-troubleshooting-valorants-frames-per-second-dips/"><u>Maximize Your Playtime: Troubleshooting Valorant's Frames Per Second Dips</u></a></li>
<li><a href="https://games-able.techidaily.com/pinnacle-gaming-experience-with-ea-play-ps5-games/"><u>Pinnacle Gaming Experience with EA Play PS5 Games</u></a></li>
<li><a href="https://games-able.techidaily.com/unfreezing-facebook-gaming-in-chrome-browser/"><u>Unfreezing Facebook Gaming in Chrome Browser</u></a></li>
</ul></div>


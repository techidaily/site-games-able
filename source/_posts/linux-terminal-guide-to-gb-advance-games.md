---
title: Linux Terminal Guide to GB Advance Games
date: 2024-06-25T13:09:29.511Z
updated: 2024-06-26T13:09:29.511Z
tags:
  - games
categories:
  - games
description: This Article Describes Linux Terminal Guide to GB Advance Games
excerpt: This Article Describes Linux Terminal Guide to GB Advance Games
keywords: GB Advanced Gaming Linux,Linux GB Game Tips,GB Games Terminal Command,Linux for GB Games,Terminal GUIGB Guide,GB Games Console Linux,Linux GB Gaming Help
thumbnail: https://thmb.techidaily.com/d28e7047daab181b2a6cda74108f4cb993066496eb332810c3bf1138a8452ea4.jpg
---

## Linux Terminal Guide to GB Advance Games

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
<li><a href="https://games-able.techidaily.com/gamble-less-save-more-the-prime-picks-from-top-11-game-dealers/"><u>Gamble Less, Save More - The Prime Picks From Top 11 Game Dealers</u></a></li>
<li><a href="https://games-able.techidaily.com/revive-retro-gaming-playing-psp-classics-on-iphone/"><u>Revive Retro Gaming: Playing PSP Classics on iPhone</u></a></li>
<li><a href="https://games-able.techidaily.com/nostalgia-at-a-swipe-ios-and-the-classics-of-psp/"><u>Nostalgia at a Swipe: IOS and the Classics of PSP!</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-unlinked-joy-con-with-switch-console/"><u>Troubleshooting Unlinked Joy-Con with Switch Console</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-efficiently-process-game-console-returns/"><u>How to Efficiently Process Game Console Returns</u></a></li>
<li><a href="https://games-able.techidaily.com/polling-pace-on-mice-vs-keyboards-a-comparative-analysis/"><u>Polling Pace on Mice vs Keyboards - A Comparative Analysis</u></a></li>
<li><a href="https://games-able.techidaily.com/conquer-virtual-realms-with-ease-streamlining-gameplay-of-popular-titles-in-steam-using-meta-quest-controllers/"><u>Conquer Virtual Realms with Ease: Streamlining Gameplay of Popular Titles in Steam Using Meta Quest Controllers</u></a></li>
<li><a href="https://games-able.techidaily.com/discover-palworld-inside-out/"><u>Discover PalWorld Inside Out</u></a></li>
<li><a href="https://games-able.techidaily.com/expertly-designed-charging-hubs-compatible-with-sony-console/"><u>Expertly Designed Charging Hubs: Compatible with Sony Console</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-correct-win-oculus-connectivity-problems/"><u>Steps to Correct Win-Oculus Connectivity Problems</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-pathway-to-prominence-on-social-media/"><u>[Updated] 2024 Approved  The Pathway to Prominence on Social Media</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/next-gen-fb-converter-transform-vids-to-premium-mp4-for-2024/"><u>Next-Gen FB Converter  Transform Vids to Premium MP4 for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-insta-stories-enhancing-background-blur-technique/"><u>2024 Approved  Insta Stories  Enhancing Background Blur Technique</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-breaking-down-itunes-video-recording-basics/"><u>[New] In 2024, Breaking Down iTunes Video Recording Basics</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-decoding-the-future-pivotal-changes-to-fb-advertising-post-2023/"><u>[New] In 2024, Decoding the Future  Pivotal Changes to FB Advertising Post-2023</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-rapid-rendering-of-fortnite-icons/"><u>In 2024, Rapid Rendering of Fortnite Icons</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-free-video-cutting-tools-for-windows-10-a-comprehensive-review/"><u>Updated In 2024, Free Video Cutting Tools for Windows 10 A Comprehensive Review</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-premium-picks-the-very-best-tripods-for-sharp-4k-videos/"><u>[New] Premium Picks  The Very Best Tripods for Sharp 4K Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/comprehensive-understanding-leveraging-adobe-cloud-and-finding-alternatives-for-2024/"><u>Comprehensive Understanding  Leveraging Adobe Cloud and Finding Alternatives for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-screen-recording-techniques-for-windows-8-users-for-2024/"><u>[New] Screen Recording Techniques for Windows 8 Users for 2024</u></a></li>
</ul></div>

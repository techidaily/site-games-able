---
title: Unlocking GBA Games in Your Linux Console
date: 2024-08-31T19:23:05.184Z
updated: 2024-09-01T19:23:05.184Z
tags:
  - games
categories:
  - games
description: This Article Describes Unlocking GBA Games in Your Linux Console
excerpt: This Article Describes Unlocking GBA Games in Your Linux Console
keywords: GBA Linux Games,Linux Game Unlocker,Play GBA on Linux,Linux Emulator for GBA,Accessing GBA Titles Linux,GBA Console Linux,Emulate GB Advance Linux
thumbnail: https://thmb.techidaily.com/962100c4bb1cf841eba9a73f110c7891af5a14d4cf3e7d146e6c0272a50f3335.jpg
---

## Unlocking GBA Games in Your Linux Console

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
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
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/new-google-meet-for-everyone-a-comprehensive-no-cost-strategy-booklet-for-2024/"><u>[New] Google Meet for Everyone  A Comprehensive, No-Cost Strategy Booklet for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-content-creators-revenue-gain-from-each-click/"><u>[Updated] In 2024, Content Creators' Revenue  Gain From Each Click</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-key-practices-for-amassing-picture-resources/"><u>[Updated] In 2024, Key Practices for Amassing Picture Resources</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-video-annotations-mastery-cutting-with-precision-and-style/"><u>[Updated] In 2024, Video Annotations Mastery  Cutting with Precision & Style</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-quick-tutorial-inverting-video-playback-in-vlc-media-player-for-2024/"><u>[Updated] Quick Tutorial  Inverting Video Playback in VLC Media Player for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-startup-steps-for-stream-money-in-periscope/"><u>[Updated] Startup Steps for Stream Money in Periscope</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-premium-zero-price-point-live-capture-app/"><u>2024 Approved  Premium Zero-Price Point Live Capture App</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Samsung Galaxy S24+ | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-nubia-z50-ultra-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/avoid-clutter-pro-tips-to-adhere-sticky-notes-on-w11w10/"><u>Avoid Clutter: Pro Tips to Adhere Sticky Notes on W11/W10</u></a></li>
<li><a href="https://games-able.techidaily.com/creating-a-unique-tv-watch-experience-with-xboxs-variable-refresh-tech/"><u>Creating a Unique TV Watch Experience with Xbox's Variable Refresh Tech</u></a></li>
<li><a href="https://games-able.techidaily.com/criteria-for-selecting-standout-discord-groups-today/"><u>Criteria for Selecting Standout Discord Groups Today</u></a></li>
<li><a href="https://games-able.techidaily.com/decode-the-language-labyrinth-with-nyts-latest-puzzle-thriller-strands/"><u>Decode the Language Labyrinth with NYT's Latest Puzzle Thriller - 'Strands'</u></a></li>
<li><a href="https://games-able.techidaily.com/directsound-utilization-in-series-s-console-gaming/"><u>DirectSound Utilization in Series S Console Gaming</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722968224813-download-zebra-gk420d-drivers-instantly-get-setup-today/"><u>Download Zebra GK420D Drivers Instantly - Get Setup Today!</u></a></li>
<li><a href="https://games-able.techidaily.com/effective-techniques-for-erasing-ps5-past-saves/"><u>Effective Techniques for Erasing PS5 Past Saves</u></a></li>
<li><a href="https://games-able.techidaily.com/expand-horizons-with-dual-booting-windows-and-ossteamos/"><u>Expand Horizons with Dual Booting - Windows & OS/SteamOS</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/expert-analysis-on-the-functionality-of-googles-voice-communication-tool/"><u>Expert Analysis on the Functionality of Google's Voice Communication Tool</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fix-your-pc-solutions-for-handling-missing-bootmgr-issues/"><u>Fix Your PC: Solutions for Handling Missing BOOTMGR Issues</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-infinix-note-30i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-malfunctioning-your-drivers-with-windows-device-manager-on-windows-11107-by-drivereasy-guide/"><u>How to identify malfunctioning your drivers with Windows Device Manager on Windows 11/10/7</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-resolve-oculus-setup-error-on-pc/"><u>How to Resolve Oculus Setup Error on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/journey-into-nvidia-g-sync-the-ultimate-smoother-gaming-tool/"><u>Journey Into Nvidia G-Sync: The Ultimate Smoother Gaming Tool</u></a></li>
<li><a href="https://games-able.techidaily.com/key-oversights-how-to-avoid-mistakes-in-purchasing-a-monitor/"><u>Key Oversights: How to Avoid Mistakes in Purchasing a Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-hidden-user-technique-for-steam/"><u>Mastering the Hidden User Technique for Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/personalizing-variable-refresh-rate-on-your-xbox-console/"><u>Personalizing Variable Refresh Rate on Your Xbox Console</u></a></li>
<li><a href="https://games-able.techidaily.com/pick-your-performance-the-battle-between-mini-and-desktop-pcs/"><u>Pick Your Performance: The Battle Between Mini & Desktop PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/premium-play-options-choosing-between-psplus-and-xbgplus/"><u>Premium Play Options: Choosing Between PS+ and XBG+</u></a></li>
<li><a href="https://games-able.techidaily.com/preventing-crashes-a-guide-to-steam-big-picture/"><u>Preventing Crashes: A Guide to Steam Big Picture</u></a></li>
<li><a href="https://games-able.techidaily.com/prime-5-why-traditional-handheld-devices-are-great/"><u>Prime 5: Why Traditional Handheld Devices Are Great</u></a></li>
<li><a href="https://games-able.techidaily.com/revive-classic-psp-titles-iphones-included/"><u>Revive Classic PSP Titles, iPhones Included</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-address-minecraft-launcher-failure-0x803f8001-error/"><u>Steps to Address Minecraft Launcher Failure: 0X803F8001 Error</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-steam-deck-ssd-replacement-procedures/"><u>Streamline Steam Deck SSD Replacement Procedures</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-refresh-rates-in-240hz-gamer-tech/"><u>Superior Refresh Rates in 240Hz Gamer Tech</u></a></li>
<li><a href="https://games-able.techidaily.com/sustaining-enthusiasm-for-long-playtimes/"><u>Sustaining Enthusiasm for Long Playtimes</u></a></li>
<li><a href="https://games-able.techidaily.com/tackle-turbulent-titles-transition-time/"><u>Tackle Turbulent Titles Transition Time</u></a></li>
<li><a href="https://games-able.techidaily.com/the-9-best-emulators-for-the-steam-deck/"><u>The 9 Best Emulators for the Steam Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/the-essential-list-of-affordable-switch-gaming/"><u>The Essential List of Affordable Switch Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/the-protocol-for-reporting-bad-players-in-xbox/"><u>The Protocol for Reporting Bad Players in Xbox</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-5-gaming-monitors-for-playstation-and-xbox/"><u>The Ultimate 5 Gaming Monitors for PlayStation & Xbox</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-persistent-restarts-in-windows-11-made-easy/"><u>Troubleshooting Persistent Restarts in Windows 11 Made Easy</u></a></li>
<li><a href="https://games-able.techidaily.com/uncover-apple-arcade-bests-with-these-tips/"><u>Uncover Apple Arcade Bests with These Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-every-epic-title-solving-egl-visibility-issues/"><u>Unlocking Every Epic Title: Solving EGL Visibility Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/whats-inside-the-switch-online-package/"><u>What's Inside the Switch Online Package?</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-honor-90-gt-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Honor 90 GT | Dr.fone</u></a></li>
</ul></div>

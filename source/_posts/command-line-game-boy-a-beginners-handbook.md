---
title: "Command Line Game Boy: A Beginner's Handbook"
date: 2024-07-29T05:57:59.322Z
updated: 2024-07-30T05:57:59.322Z
tags:
  - games
categories:
  - games
description: "This Article Describes Command Line Game Boy: A Beginner's Handbook"
excerpt: "This Article Describes Command Line Game Boy: A Beginner's Handbook"
keywords: Gamble Boy Console,CGB Handbook Start,Command Line GB,Play Game Boy CLI,Basic Game Boy Guide,CLI Games Boy Manual,Beginner's CGB Hands-On
thumbnail: https://thmb.techidaily.com/329d369e5db1c978f66185fe9a5482898ede3269e6a52b60eb890177d543e794.png
---

## Command Line Game Boy: A Beginner's Handbook

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Emulate a Game Boy in the Terminal?

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
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
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-engaging-cycles-perfecting-the-instagram-loop-craft/"><u>[New] 2024 Approved  Engaging Cycles  Perfecting the Instagram Loop Craft</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-photography-made-easy-beginners-guide-to-lunapic/"><u>[New] Photography Made Easy  Beginner’s Guide to LunaPic</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-engaging-followers-on-instagram-with-youtube-video-links-in-stories/"><u>[Updated] 2024 Approved  Engaging Followers on Instagram with YouTube Video Links in Stories</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-crafting-wealth-with-facebook-video-ads-a-comprehensive-guide/"><u>[Updated] Crafting Wealth with Facebook Video Ads  A Comprehensive Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-perfect-zooming-techniques-for-google-meet/"><u>[Updated] Perfect Zooming Techniques for Google Meet</u></a></li>
<li><a href="https://games-able.techidaily.com/11-cross-platform-mobile-multiplayer-games-to-play-with-friends/"><u>11 Cross-Platform Mobile Multiplayer Games to Play With Friends</u></a></li>
<li><a href="https://games-able.techidaily.com/20-must-try-mobile-duo-gaming-for-sociable-souls/"><u>20 Must-Try Mobile Duo Gaming for Sociable Souls</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-secrets-to-more-likes-on-your-tiktok-unpacks/"><u>2024 Approved  Secrets to More Likes on Your TikTok Unpacks</u></a></li>
<li><a href="https://games-able.techidaily.com/3-powerful-money-management-tips-for-xbox-players/"><u>3 Powerful Money Management Tips for Xbox Players</u></a></li>
<li><a href="https://games-able.techidaily.com/4-reasons-why-microsoft-reward-points-need-to-improve-on-xbox/"><u>4 Reasons Why Microsoft Reward Points Need to Improve on Xbox</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>6 Ways to Change Spotify Location On Your Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/access-google-play-games-your-pc-edition-journey/"><u>Access Google Play Games: Your PC Edition Journey</u></a></li>
<li><a href="https://games-able.techidaily.com/adding-funds-a-key-to-ps-store-success/"><u>Adding Funds: A Key to PS Store Success</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-roblox-error-262-anomaly/"><u>Addressing Roblox: Error 262 Anomaly</u></a></li>
<li><a href="https://games-able.techidaily.com/adraise-the-curtain-on-amd-rdna-35-when-to-expect/"><u>ADRaise the Curtain on AMD RDNA 3.5 - When to Expect?</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-white-motherboards-2023s-budget-hits/"><u>Affordable White Motherboards: 2023'S Budget Hits</u></a></li>
<li><a href="https://games-able.techidaily.com/alternative-methods-for-a-quick-ps5-startup/"><u>Alternative Methods for a Quick PS5 Startup</u></a></li>
<li><a href="https://games-able.techidaily.com/android-nostalgia-rewind-to-classic-pokemon-days/"><u>Android Nostalgia: Rewind to Classic Pokémon Days</u></a></li>
<li><a href="https://games-able.techidaily.com/assessing-repair-vs-exchange-for-broken-nintendo-switches/"><u>Assessing Repair Vs. Exchange for Broken Nintendo Switches</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172747292-banish-errors-and-enhance-your-pc-with-new-nvidia-drivers-update/"><u>Banish Errors and Enhance Your PC with New Nvidia Drivers Update</u></a></li>
<li><a href="https://games-able.techidaily.com/banish-the-blue-screen-fixing-crashes-in-epics-launcher/"><u>Banish the Blue Screen: Fixing Crashes in Epic's Launcher</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-android-data-recovery-retrieve-lost-photos-from-spark-20-pro-by-fonelab-android-recover-photos/"><u>Best Android Data Recovery - Retrieve Lost Photos from Spark 20 Pro.</u></a></li>
<li><a href="https://games-able.techidaily.com/best-buys-for-superior-xbox-video-capturing/"><u>Best Buys for Superior Xbox Video Capturing</u></a></li>
<li><a href="https://games-able.techidaily.com/best-online-deals-top-11-budget-friendly-gaming-purchases/"><u>Best Online Deals: Top 11 Budget-Friendly Gaming Purchases</u></a></li>
<li><a href="https://extra-hints.techidaily.com/discovering-the-treasure-trove-of-free-designs/"><u>Discovering the Treasure Trove of Free Designs</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/downloading-samfw-frp-tool-30-for-realme-12-pro-5g-by-drfone-android/"><u>Downloading SamFw FRP Tool 3.0 for Realme 12 Pro 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172771364-elevate-to-new-heights-with-big-box-cabinetry/"><u>Elevate to New Heights with Big Box Cabinetry!</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/elevate-your-profile-with-vimeo-on-instagram-for-2024/"><u>Elevate Your Profile with Vimeo on Instagram for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/ensuring-compatibility-windows-plus-nvidia/"><u>Ensuring Compatibility: Windows + NVIDIA</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166993933-pinnacle-game-boy-advance-simulation-apps-for-iphone/"><u>Pinnacle Game Boy Advance Simulation Apps for iPhone!</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/pro-grade-streaming-tools-best-software-and-hardware-reviewed-for-2024/"><u>Pro-Grade Streaming Tools  Best Software & Hardware Reviewed for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/swiftly-blur-your-iphone-shots-with-these-4-tricks/"><u>Swiftly Blur Your iPhone Shots with These 4 Tricks</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170858411-top-10-ps-summer-discount-extravaganza/"><u>Top 10 PS Summer Discount Extravaganza!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164560814-top-4-gba-simulation-apps-for-apple-fans-and-gamers/"><u>Top 4 GBA Simulation Apps for Apple Fans and Gamers!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172869632-upgrade-your-nvidia-driver-enhance-system-stability-and-speed/"><u>Upgrade Your Nvidia Driver - Enhance System Stability & Speed!</u></a></li>
</ul></div>

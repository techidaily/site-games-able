---
title: Bootlegging Game Boy Games Using Linux Tools
date: 2024-07-29T05:58:35.194Z
updated: 2024-07-30T05:58:35.194Z
tags:
  - games
categories:
  - games
description: This Article Describes Bootlegging Game Boy Games Using Linux Tools
excerpt: This Article Describes Bootlegging Game Boy Games Using Linux Tools
keywords: Bootleg Gaming,Legacy Console Games,Linux Emulation,Hacked Game Boy,Retro Pi Tools,Pirate Gaming Software,Old Gaming Systems
thumbnail: https://thmb.techidaily.com/e663bf23b6887cb8279b82d66477ecb71e4a937f5292de883673cace9e11db92.jpg
---

## Bootlegging Game Boy Games Using Linux Tools

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## Why Emulate a Game Boy in the Terminal?

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
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
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-ideal-screencasting-software-for-effective-teaching/"><u>[New] In 2024, Ideal Screencasting Software for Effective Teaching</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-the-fundamentals-of-income-for-t-series-on-youtube/"><u>[New] In 2024, The Fundamentals of Income for T-Series on YouTube</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-webcam-video-mastery-edit-enhance-and-distribute/"><u>[New] In 2024, Webcam Video Mastery  Edit, Enhance & Distribute</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-mastering-lol-recording-three-easy-techniques-for-2024/"><u>[New] Mastering LOL Recording  Three Easy Techniques for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-10-mock-musicals-that-bring-smiles/"><u>[Updated] 2024 Approved  10 Mock Musicals That Bring Smiles</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-navigating-discords-spoiler-system-easily-for-2024/"><u>[Updated] Navigating Discord's Spoiler System Easily for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-leveraging-advanced-techniques-in-360-video-on-fb-live/"><u>2024 Approved  Leveraging Advanced Techniques in 360 Video on FB Live</u></a></li>
<li><a href="https://games-able.techidaily.com/3-alternative-methods-for-enjoying-flash-games-post-adobe/"><u>3 Alternative Methods for Enjoying Flash Games Post-Adobe</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-motorola-edge-40-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Motorola Edge 40 Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-steam-disconnection-issue-on-pc/"><u>Addressing Steam Disconnection Issue on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/browsing-for-fun-the-9-intriguing-advantages-and-disadvantages-of-e-games/"><u>Browsing for Fun: The 9 Intriguing Advantages & Disadvantages of E-Games</u></a></li>
<li><a href="https://games-able.techidaily.com/building-a-robust-steam-wallet-investment-guide/"><u>Building a Robust Steam Wallet - Investment Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/comprehensive-bg3-gear-checklist-and-more/"><u>Comprehensive BG3 Gear Checklist & More</u></a></li>
<li><a href="https://games-able.techidaily.com/conquer-classic-ps3-titles-30-powerful-pc-emulators/"><u>Conquer Classic PS3 Titles: 30 Powerful PC Emulators</u></a></li>
<li><a href="https://games-able.techidaily.com/conquering-windows-11-steam-installation-errors/"><u>Conquering Windows 11 Steam Installation Errors</u></a></li>
<li><a href="https://games-able.techidaily.com/cosmic-crafter-navigating-novel-pc-choices/"><u>Cosmic Crafter: Navigating Novel PC Choices</u></a></li>
<li><a href="https://games-able.techidaily.com/cut-out-console-noise-with-ease-on-xbox/"><u>Cut Out Console Noise with Ease on Xbox</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-asus-rog-phone-8-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Asus ROG Phone 8 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-your-watchlist-experience-with-youtubes-av1-settings-for-2024/"><u>Elevate Your Watchlist Experience with YouTube's AV1 Settings for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-complete-game-displays-in-epics-library/"><u>Ensuring Complete Game Displays in Epic's Library</u></a></li>
<li><a href="https://extra-information.techidaily.com/essential-iphone-and-android-video-editor-choices/"><u>Essential iPhone & Android Video Editor Choices</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-key-factors-for-a-smart-ps5-buy/"><u>Evaluating Key Factors for a Smart PS5 Buy</u></a></li>
<li><a href="https://games-able.techidaily.com/excellent-gamer-tracking-apps-review/"><u>Excellent Gamer Tracking Apps Review</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-xboxs-golden-era-via-emulation-on-a-pc/"><u>Exploring Xbox's Golden Era via Emulation on a PC</u></a></li>
<li><a href="https://games-able.techidaily.com/fleeting-online-realms-a-reason-for-concern/"><u>Fleeting Online Realms – A Reason for Concern?</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-finally-get-rid-of-games-from-your-steam-account/"><u>How to Finally Get Rid of Games From Your Steam Account</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-htc-u23-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on HTC U23 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-lava-blaze-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Lava Blaze 2 Pro? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/is-discords-indolence-identifier-accurate/"><u>Is Discord's Indolence Identifier Accurate?</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-obstacles-for-opening-origins/"><u>Overcoming Obstacles for Opening Origins</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-steams-sync-shenanigans-on-pc/"><u>Overcoming Steam's Sync Shenanigans on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/perfecting-precision-mastering-cs2-on-a-mac-laptop/"><u>Perfecting Precision: Mastering CS2 on a Mac Laptop</u></a></li>
<li><a href="https://games-able.techidaily.com/pimax-crystal-review-the-best-looking-pcvr-headset-around-but-still-buggy/"><u>Pimax Crystal Review: The Best Looking PCVR Headset Around, but Still Buggy</u></a></li>
<li><a href="https://games-able.techidaily.com/pocketplay-retro-small-screen-large-memories/"><u>PocketPlay Retro: Small Screen, Large Memories</u></a></li>
<li><a href="https://games-able.techidaily.com/preserving-games-on-disk-efficient-chdman-iso-compression-tips/"><u>Preserving Games on Disk: Efficient CHDMAN ISO Compression Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/quests-and-triumphs-why-i-cherish-netflixs-gameplay/"><u>Quests & Triumphs: Why I Cherish Netflix's Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/re-establishing-win11-steam-connections/"><u>Re-Establishing Win11 Steam Connections</u></a></li>
<li><a href="https://games-able.techidaily.com/revive-your-consoles-controller-with-a-diy-fix/"><u>Revive Your Console's Controller with a DIY Fix</u></a></li>
<li><a href="https://games-able.techidaily.com/should-your-pc-get-an-original-founders-gpu-or-asus-branded-vega/"><u>Should Your PC Get an Original Founder's GPU or Asus-Branded Vega?</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168126928-space-saving-systems-vs-traditional-workstations-make-your-choice/"><u>Space-Saving Systems Vs. Traditional Workstations: Make Your Choice!</u></a></li>
<li><a href="https://games-able.techidaily.com/tailored-sound-output-for-headset-users/"><u>Tailored Sound Output for Headset Users</u></a></li>
<li><a href="https://games-able.techidaily.com/the-retro-gaming-revolution-six-reasons-to-choose-pi/"><u>The Retro Gaming Revolution: Six Reasons to Choose Pi</u></a></li>
<li><a href="https://games-able.techidaily.com/top-ranked-8-light-virtual-platforms-for-gameplay/"><u>Top-Ranked 8 Light Virtual Platforms for Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-playstation-5-with-best-add-ons/"><u>Transform Your PlayStation 5 With Best Add-Ons</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-pictures-from-samsung-galaxy-a05s-by-fonelab-android-recover-pictures/"><u>Undelete lost pictures from Samsung Galaxy A05s.</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-9-free-full-length-christmas-movies-on-youtube/"><u>Watch 9 Free Full Length Christmas Movies On Youtube</u></a></li>
<li><a href="https://games-able.techidaily.com/xboxs-quick-resume-an-essential-advantage/"><u>Xbox's Quick Résumé - An Essential Advantage?</u></a></li>
</ul></div>

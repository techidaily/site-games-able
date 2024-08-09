---
title: Terminal Techniques for Gaming on Outdated Systems
date: 2024-08-08T09:17:09.148Z
updated: 2024-08-09T09:17:09.148Z
tags:
  - games
categories:
  - games
description: This Article Describes Terminal Techniques for Gaming on Outdated Systems
excerpt: This Article Describes Terminal Techniques for Gaming on Outdated Systems
keywords: Old PC Gaming Tips,Retro System Play,Antique Gaming Guide,Legacy Console Strategies,Vintage Games Optimization,Outdated Tech Gameplay,Historical Console Mastery
thumbnail: https://thmb.techidaily.com/25bf753c78130a921149c781a28200c1963f284bc6d075e275272bdd4200ee96.jpg
---

## Terminal Techniques for Gaming on Outdated Systems

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Why Emulate a Game Boy in the Terminal?

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
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
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3727260&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-step-by-step-guide-to-create-engaging-thumbnails-for-your-videos-on-youtube/"><u>[New] 2024 Approved  Step-by-Step Guide to Create Engaging Thumbnails for Your Videos on YouTube</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-livestream-lifters-for-modern-audiences/"><u>[New] In 2024, Livestream Lifters for Modern Audiences</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-screencasting-guide-what-is-and-how-to-for-2024/"><u>[New] Screencasting Guide  What Is and How To for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-path-to-crafting-killer-podcast-names-plus-inspiration-sparks/"><u>[New] The Ultimate Path to Crafting Killer Podcast Names, Plus Inspiration Sparks</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-driving-engagement-and-visibility-effective-strategies-for-fb-video-marketing/"><u>[Updated] 2024 Approved  Driving Engagement and Visibility  Effective Strategies for FB Video Marketing</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-are-video-reviews-of-goods-paid-for-by-creators/"><u>[Updated] Are Video Reviews of Goods Paid For by Creators?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-screen-recording-essentials-and-competitive-analyses/"><u>[Updated] Screen Recording Essentials and Competitive Analyses</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-vivo-s17t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-optimizing-story-video-playback-rate-on-instagram-app/"><u>2024 Approved  Optimizing Story Video Playback Rate on Instagram App</u></a></li>
<li><a href="https://games-able.techidaily.com/4-ways-to-see-if-someone-is-appearing-offline-using-an-xbox-series-xs/"><u>4 Ways to See if Someone Is Appearing Offline Using an Xbox Series X|S</u></a></li>
<li><a href="https://games-able.techidaily.com/5-strategies-for-ultimate-ps5-gaming-bliss/"><u>5 Strategies for Ultimate PS5 Gaming Bliss</u></a></li>
<li><a href="https://games-able.techidaily.com/7-essential-edge-advantages-that-make-it-a-gamers-browser/"><u>7 Essential Edge Advantages that Make It a Gamer's Browser</u></a></li>
<li><a href="https://games-able.techidaily.com/8-factors-to-consider-before-buying-a-cpu-cooler/"><u>8 Factors to Consider Before Buying a CPU Cooler</u></a></li>
<li><a href="https://games-able.techidaily.com/9-strategies-to-tackle-windows-steam-folder-access/"><u>9 Strategies to Tackle Windows Steam Folder Access</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensible-route-for-sd-installation-in-steam-deck/"><u>A Comprehensible Route for SD Installation in Steam Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-overview-of-controller-techniques-in-ryujinx-emulation/"><u>A Comprehensive Overview of Controller Techniques in Ryujinx Emulation</u></a></li>
<li><a href="https://games-able.techidaily.com/a-deep-dive-into-dynamic-game-environments/"><u>A Deep Dive Into Dynamic Game Environments</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-chapter-valve-elevates-shared-gaming-with-updates/"><u>A New Chapter: Valve Elevates Shared Gaming with Updates</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-view-on-gaming-computing-debunking-six-apple-misconceptions/"><u>A New View on Gaming Computing: Debunking Six Apple Misconceptions</u></a></li>
<li><a href="https://games-able.techidaily.com/a-quick-guide-to-palworlds-core/"><u>A Quick Guide to PalWorld's Core</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-file-creation-unsuccessful-error-30005/"><u>Addressing File Creation Unsuccessful - Error 30005</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-high-performance-budget-friendly-motherboards-2023s-selection/"><u>Affordable, High-Performance Budget-Friendly Motherboards - 2023'S Selection</u></a></li>
<li><a href="https://games-able.techidaily.com/ai-and-adventure-the-best-6-ways-to-employ-chatgpt-for-dandd-excellence/"><u>AI & Adventure: The Best 6 Ways to Employ ChatGPT for D&D Excellence</u></a></li>
<li><a href="https://games-able.techidaily.com/aim-and-accuracy-boosted-by-the-ideal-mouse-setting/"><u>Aim and Accuracy Boosted by the Ideal Mouse Setting</u></a></li>
<li><a href="https://games-able.techidaily.com/akko-mod007b-board-insights-for-serious-gaming/"><u>Akko MOD007B Board Insights for Serious Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/akko-mod007b-pro-gaming-keyboard-unveiled/"><u>Akko MOD007B Pro-Gaming Keyboard Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/amplify-playtime-8-ways-to-upgrade-your-ps4/"><u>Amplify Playtime: 8 Ways to Upgrade Your PS4</u></a></li>
<li><a href="https://extra-resources.techidaily.com/apples-m1-performance-enhancing-video-editing-for-2024/"><u>Apple’s M1 Performance  Enhancing Video Editing for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/apples-silicon-powered-gaming-crossover-compatibility-unveiled/"><u>Apple's Silicon-Powered Gaming: CrossOver Compatibility Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/are-chip-powerhouses-about-to-skyrocket-prices/"><u>Are Chip Powerhouses About To Skyrocket Prices?</u></a></li>
<li><a href="https://games-able.techidaily.com/are-mac-devices-changing-gamers-landscape/"><u>Are Mac Devices Changing Gamers’ Landscape?</u></a></li>
<li><a href="https://games-able.techidaily.com/are-your-vintage-gamepads-power-sources-compatible-with-oled-switch/"><u>Are Your Vintage Gamepad's Power Sources Compatible with OLED Switch?</u></a></li>
<li><a href="https://games-able.techidaily.com/balancing-fun-and-frustration-in-gaming/"><u>Balancing Fun & Frustration in Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/barriers-to-gamefis-acceptance-by-true-gamers/"><u>Barriers to GameFi’s Acceptance by True Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/beginners-tips-for-twitch-live-streaming-via-mobile/"><u>Beginner's Tips for Twitch Live Streaming via Mobile</u></a></li>
<li><a href="https://games-able.techidaily.com/best-game-hits-without-an-internet-connection-ios/"><u>Best Game Hits Without an Internet Connection (iOS)</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171487913-bring-your-psp-experience-to-todays-technology/"><u>Bring Your PSP Experience to Today's Technology!</u></a></li>
<li><a href="https://techtrends.techidaily.com/bypassing-cables-and-phones-methods-to-get-internet-anywhere-anytime/"><u>Bypassing Cables and Phones: Methods to Get Internet Anywhere, Anytime</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171243140-chatgpt-now-available-dive-into-these-6-games/"><u>ChatGPT Now Available - Dive Into These 6 Games!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164401657-discover-iphones-best-video-game-emulators-now/"><u>Discover iPhone's Best Video Game Emulators Now</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/fundamentals-of-copywriting-for-engaging-fb-campaigns/"><u>Fundamentals of Copywriting for Engaging FB Campaigns</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-tips-for-capturing-clear-quality-sound-in-your-windows-11-pc/"><u>In 2024, Top Tips for Capturing Clear, Quality Sound in Your Windows 11 PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transform-every-moment-top-activities-to-do-while-listening-to-your-favorite-talk-shows/"><u>In 2024, Transform Every Moment  Top Activities to Do While Listening to Your Favorite Talk Shows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/masterful-stardew-upgrades-uncovered-the-seven-best-for-2024/"><u>Masterful Stardew Upgrades Uncovered  The Seven Best for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/mlb-the-show-19-stunning-visual-experience-and-unexpected-rpg-twist/"><u>MLB The Show 19 - Stunning Visual Experience and Unexpected RPG Twist</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-audiophiles-dream-upgrading-your-recording-space-sound/"><u>New In 2024, Audiophiles Dream Upgrading Your Recording Space Sound</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/professional-screencapture-for-windows-11/"><u>Professional ScreenCapture for Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169641614-strengthen-your-cognitive-muscles-with-nyts-exciting-new-brain-teaser-strands/"><u>Strengthen Your Cognitive Muscles With NYT’s Exciting, New Brain Teaser: Strands!</u></a></li>
<li><a href="https://extra-information.techidaily.com/top-15-timeless-classics-in-stop-motion-cinema-history/"><u>Top 15 Timeless Classics in Stop-Motion Cinema History</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168178529-top-4-ios-game-boy-advance-portals-to-classic-worlds/"><u>Top 4 iOS Game Boy Advance Portals to Classic Worlds!</u></a></li>
</ul></div>

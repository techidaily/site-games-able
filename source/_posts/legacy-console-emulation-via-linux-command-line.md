---
title: Legacy Console Emulation via Linux Command Line
date: 2024-09-09T09:32:22.671Z
updated: 2024-09-10T09:32:22.671Z
tags:
  - games
categories:
  - games
description: This Article Describes Legacy Console Emulation via Linux Command Line
excerpt: This Article Describes Legacy Console Emulation via Linux Command Line
keywords: Legacy Gaming on Linux,Console Emulation Linux,PC Console Playing,Linux Game Emulator,Retro Games Linux,Linux Emulated Consoles,Command-Line Console Emulation
thumbnail: https://thmb.techidaily.com/177db7c45381f8f94f304fef5764a3ae21d49762f0d50b119bc79b8987d4ee6b.jpg
---

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Legacy Console Emulation via Linux Command Line

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Emulate a Game Boy in the Terminal?

![pokemon red star splash screen in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/pokemon-red-star-splash-screen-in-the-linux-terminal.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123476/16836" target="_top" id="2123476">
  <img src="//a.impactradius-go.com/display-ad/16836-2123476" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123476/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Nintendo's Game Boy is one of the most wildly successful game consoles ever created, and introduced generations of kids and adults to the joys of games such as Tetris, Pokemon, and the Super Mario Land series.

 With its 4MHz processor and 47x43mm display, the Game Boy could easily fit in your trouser pocket and offered around 15 hours of gameplay from four AA batteries. In the late 1980s and early 1990s, the Game Boy was a must-have accessory for any teenager, and utterly dominated the portable gaming market.

 The console's popularity and longevity meant that there were thousands of officially licensed Game Boy games, with many more hacked together by bedroom tinkerers.

 By running an emulator in your terminal, you can run every single one of these, transforming your terminal into an extensive library of playable games.

 As the name suggests, php-terminal-gameboy-emulator is written in PHP—a language [usually used to create websites](https://www.makeuseof.com/tag/build-simple-php-website/) —and although the project's readme only states that it supports PHP 5.6, PHP 7, and HHVM, we've had it running almost flawlessly on PHP versions up to 8.2.

 With php-terminal-gameboy-emulator, you're not limited to your computer either and can run sessions over [Secure Shell (SSH)](https://www.makeuseof.com/learn-how-to-manage-remote-access-via-ssh/) on remote machines.

 Because it's running in a terminal, your Game Boy games won't have any sound, but we're sure you can hum the Tetris theme tune.

 You also won't be able to save games. If these limitations are too restrictive, there are dozens of excellent emulators available on Linux.

 You should only use ROMS you legally own. You can find a huge variety of homebrew Game Boy ROMS at [Homebrew Hub](https://hh.gbdev.io/) .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115936/19272" target="_top" id="2115936">
  <img src="//a.impactradius-go.com/display-ad/19272-2115936" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115936/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://tiktok-videos.techidaily.com/new-2024-approved-15-newest-tiktok-trends-you-need-to-pay-attention-to/"><u>[New] 2024 Approved 15 Newest TikTok Trends You Need to Pay Attention To</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-a-taste-of-film-home-cooks-visual-journey/"><u>[New] In 2024, A Taste of Film Home Cook's Visual Journey</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-mastering-gifs-snapchats-step-by-step-guide-for-effortless-sharing/"><u>[New] In 2024, Mastering Gifs Snapchat's Step-By-Step Guide for Effortless Sharing</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-perfecting-imovie-posts-on-vimeo-for-enhanced-viewership-for-2024/"><u>[Updated] Perfecting iMovie Posts on Vimeo for Enhanced Viewership for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-perpetual-display-documentation-firms/"><u>2024 Approved Perpetual Display Documentation Firms</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-the-top-11-supplements-for-dji-phantom-4-users/"><u>2024 Approved The Top 11 Supplements for DJI Phantom 4 Users</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-display-dilemmnas-why-you-shouldnt-splurge-on-hdr/"><u>Decoding Display Dilemmnas: Why You Shouldn't Splurge on HDR</u></a></li>
<li><a href="https://games-able.techidaily.com/elite-eyeglasses-for-pc-screen-safety/"><u>Elite Eyeglasses for PC Screen Safety</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-the-necessity-of-a-dual-capable-display/"><u>Evaluating the Necessity of a Dual-Capable Display?</u></a></li>
<li><a href="https://games-able.techidaily.com/examine-pimaxs-crystal-clarity-a-visual-treat-with-bugs/"><u>Examine Pimax's Crystal Clarity - A Visual Treat with Bugs</u></a></li>
<li><a href="https://games-able.techidaily.com/game-availability-ahead-of-time-pros-and-cons/"><u>Game Availability Ahead of Time - Pros and Cons</u></a></li>
<li><a href="https://some-approaches.techidaily.com/guide-comment-installer-la-lien-braque-sur-mac-et-windows-10-pour-deverrouiller-un-dvd-avec-libdvdcss/"><u>Guide : Comment Installer La Lien Braque Sur Mac Et Windows 10 Pour Déverrouiller Un DVD Avec Libdvdcss</u></a></li>
<li><a href="https://games-able.techidaily.com/harmony-hunters-top-8-audio-quiz-games-to-beat/"><u>Harmony Hunters: Top 8 Audio Quiz Games to Beat</u></a></li>
<li><a href="https://games-able.techidaily.com/having-playstation-4-wi-fi-issues-8-tips-and-fixes-worth-trying/"><u>Having PlayStation 4 Wi-Fi Issues? 8 Tips and Fixes Worth Trying</u></a></li>
<li><a href="https://games-able.techidaily.com/how-the-right-gaming-gear-can-help-you-get-good/"><u>How the Right Gaming Gear Can Help You Get Good</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-enable-game-sharing-on-playstation-5/"><u>How to Enable Game Sharing on PlayStation 5</u></a></li>
<li><a href="https://games-able.techidaily.com/ifa-2023s-innovative-devices-a-gamers-paradise/"><u>IFA 2023'S Innovative Devices – A Gamer's Paradise</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-google-pixel-7a-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Google Pixel 7a | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-vivo-s18-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-tecno-phantom-v-flip-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/is-switchs-connectivity-upgrade-worth-the-dollar/"><u>Is Switch's Connectivity Upgrade Worth the Dollar?</u></a></li>
<li><a href="https://games-able.techidaily.com/linking-up-with-fun-think-twice-about-it/"><u>Linking Up With Fun? Think Twice About It</u></a></li>
<li><a href="https://games-able.techidaily.com/masterful-hacks-extracting-xbox-perks-from-codes/"><u>Masterful Hacks: Extracting Xbox Perks From Codes</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-strategy-top-6-fresh-chess-app-innovations/"><u>Mastering Strategy: Top 6 Fresh Chess App Innovations</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-value-on-the-field-boosting-frame-rates-and-performance-of-valorant-windows-edition/"><u>Maximize Value on the Field: Boosting Frame Rates and Performance of Valorant Windows Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-virtual-world-of-ps5-sans-controller/"><u>Navigating the Virtual World of PS5 Sans Controller</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-the-challenge-error-code-262-on-roblox/"><u>Overcoming the Challenge: Error Code 262 on Roblox</u></a></li>
<li><a href="https://games-able.techidaily.com/premier-gamers-progress-recorders/"><u>Premier Gamers' Progress Recorders</u></a></li>
<li><a href="https://games-able.techidaily.com/reconsidering-the-rush-to-ps5-ownership/"><u>Reconsidering the Rush to PS5 Ownership</u></a></li>
<li><a href="https://games-able.techidaily.com/reinventing-identity-the-process-for-name-and-logo-change-on-riot-games/"><u>Reinventing Identity: The Process for Name and Logo Change on Riot Games</u></a></li>
<li><a href="https://games-able.techidaily.com/sony-playstation-plus-analyzing-the-monthly-fee-breakdown/"><u>Sony PlayStation Plus: Analyzing the Monthly Fee Breakdown</u></a></li>
<li><a href="https://games-able.techidaily.com/step-into-a-world-apart-from-the-fallout-show/"><u>Step Into a World Apart From the Fallout Show</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-remedy-errors-in-oculus-application-on-win-1011/"><u>Steps To Remedy Errors in Oculus Application on Win 10/11</u></a></li>
<li><a href="https://games-able.techidaily.com/unmatched-performance-and-precision-razers-basilisk-v3-pro-review/"><u>Unmatched Performance and Precision: Razer's Basilisk V3 Pro Review</u></a></li>
<li><a href="https://games-able.techidaily.com/what-constitutes-idle-participation-on-discord/"><u>What Constitutes Idle Participation on Discord?</u></a></li>
</ul></div>

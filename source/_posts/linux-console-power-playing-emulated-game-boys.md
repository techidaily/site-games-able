---
title: "Linux Console Power: Playing Emulated Game Boys"
date: 2024-09-04T21:49:18.628Z
updated: 2024-09-05T21:49:18.628Z
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
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-inside-tips-for-maximizing-your-creator-studio-potential/"><u>[New] 2024 Approved  Inside Tips for Maximizing Your Creator Studio Potential</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-skype-capture-manual-unveiling-the-best-free-and-paid-practices-windowsmac-for-2024/"><u>[New] Skype Capture Manual  Unveiling the Best Free and Paid Practices (Windows/Mac) for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-things-that-you-should-know-about-youtube-keyword-research/"><u>[Updated] 2024 Approved  Things That You Should Know About YouTube Keyword Research</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-cam-showdown-spectacle-ultimate-legendary-sj6-meets-yis-visionary-4k/"><u>[Updated] Cam Showdown Spectacle  Ultimate Legendary SJ6 Meets Yi's Visionary 4K</u></a></li>
<li><a href="https://games-able.techidaily.com/champion-mousepad-roundup-for-players/"><u>Champion Mousepad Roundup for Players</u></a></li>
<li><a href="https://games-able.techidaily.com/crafting-a-tailored-ps5-games-package-list/"><u>Crafting a Tailored PS5 Games Package List</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-twitch-platform-features-and-usage-tips/"><u>Decoding Twitch: Platform Features and Usage Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-playtime-finding-elite-free-steam-games/"><u>Elevate Your Playtime: Finding Elite Free Steam Games</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-steam-deck-with-powerful-game-launchers/"><u>Elevate Your Steam Deck with Powerful Game Launchers</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-your-switch-sees-the-world-online/"><u>Ensuring Your Switch Sees The World Online</u></a></li>
<li><a href="https://games-able.techidaily.com/entertain-yourself-with-these-quick-web-gaming-hits/"><u>Entertain Yourself with These Quick Web Gaming Hits</u></a></li>
<li><a href="https://games-able.techidaily.com/error-403-in-roblox-resolution-guide-for-pc/"><u>Error 403 in Roblox: Resolution Guide for PC</u></a></li>
<li><a href="https://games-able.techidaily.com/explore-non-commercial-intense-gaming-titles/"><u>Explore Non-Commercial, Intense Gaming Titles</u></a></li>
<li><a href="https://games-able.techidaily.com/flash-gaming-aftermath-secrets-to-playing-without-flash/"><u>Flash Gaming Aftermath: Secrets to Playing without Flash</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-at-lightning-speed-basilisk-v3-reviewed/"><u>Game On at Lightning Speed: Basilisk V3 Reviewed</u></a></li>
<li><a href="https://games-able.techidaily.com/ifa-2023-revolutionizing-your-viewing-experience/"><u>IFA 2023: Revolutionizing Your Viewing Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/improving-virtual-connectivity-speed-addressing-high-latency-issues/"><u>Improving Virtual Connectivity Speed: Addressing High Latency Issues</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Tecno Camon 30 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgotten-the-voicemail-password-of-vivo-y36-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Vivo Y36? Try These Fixes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-set-your-preferred-job-location-on-linkedin-app-of-your-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Set Your Preferred Job Location on LinkedIn App of your Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169077022-linking-up-with-fun-think-twice-about-it/"><u>Linking Up With Fun? Think Twice About It!</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-arcade-fun-embrace-big-box-framing/"><u>Maximize Arcade Fun: Embrace Big Box Framing</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-iphone-7-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your iPhone 7</u></a></li>
<li><a href="https://games-able.techidaily.com/playing-politics-with-nyt-relationships/"><u>Playing Politics with NYT Relationships</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-and-effective-steps-for-decks-sd-card-revamp/"><u>Quick & Effective Steps for Deck's SD Card Revamp</u></a></li>
<li><a href="https://games-able.techidaily.com/reconnecting-windows-11-steam-with-online-friends/"><u>Reconnecting Windows 11 Steam with Online Friends</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/seamless-backward-compatibility-the-answer-to-playing-ps4-games-on-a-ps5/"><u>Seamless Backward Compatibility: The Answer to Playing PS4 Games on a PS5?</u></a></li>
<li><a href="https://games-able.techidaily.com/secure-steam-selections-discreetly/"><u>Secure Steam Selections Discreetly</u></a></li>
<li><a href="https://games-able.techidaily.com/share-your-games-seamlessly-on-ps5/"><u>Share Your Games Seamlessly on PS5</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-chrome-the-ultimate-guide-for-self-launched-tab-control/"><u>Stop Chrome: The Ultimate Guide for Self-Launched Tab Control</u></a></li>
<li><a href="https://games-able.techidaily.com/switch-to-immersive-viewing-tv-and-playnite-fullscreen-mode/"><u>Switch to Immersive Viewing - TV & Playnite Fullscreen Mode</u></a></li>
<li><a href="https://games-able.techidaily.com/1719167756680-the-unmatched-performance-of-2-years-on-an-oled-monitor/"><u>The Unmatched Performance of 2 Years on an OLED Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-streamlining-gaming-setup-steams-external-options/"><u>Tips for Streamlining Gaming Setup: Steam's External Options</u></a></li>
<li><a href="https://data-wizards.techidaily.com/top-data-recovery-for-mac-a-comparative-analysis-of-top-8-tools/"><u>Top Data Recovery for Mac: A Comparative Analysis of Top 8 Tools</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-insights-on-linksys-velop-router-a-superior-choice-for-robust-wifi-expansion/"><u>Top Insights on Linksys Velop Router: A Superior Choice for Robust WiFi Expansion</u></a></li>
<li><a href="https://games-able.techidaily.com/1719167533097-transform-spaces-and-games-with-enhanced-cabinet-frames/"><u>Transform Spaces & Games with Enhanced Cabinet Frames</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-and-correcting-panel-deformation/"><u>Understanding and Correcting Panel Deformation</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-your-gaming-potential-controlling-with-xbox-on-pc-137-chars/"><u>Unlock Your Gaming Potential: Controlling with Xbox on PC (137 Chars)</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-game-enthusiasm-with-a-revamped-microsoft-xbox-points-system/"><u>Unlocking Game Enthusiasm with a Revamped Microsoft Xbox Points System</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-the-secrets-of-steam-errors-and-their-cures-in-win11/"><u>Unlocking the Secrets of Steam Errors and Their Cures in Win11</u></a></li>
<li><a href="https://games-able.techidaily.com/unwinding-through-play-six-burnout-remedies/"><u>Unwinding Through Play: Six Burnout Remedies</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-3gp-video-editing-cutting-and-trimming-made-easy/"><u>Updated 2024 Approved 3GP Video Editing Cutting and Trimming Made Easy</u></a></li>
<li><a href="https://games-able.techidaily.com/valve-cuts-off-abuse-avenues-in-gaming-refunds/"><u>Valve Cuts Off Abuse Avenues in Gaming Refunds</u></a></li>
<li><a href="https://games-able.techidaily.com/why-playing-monthly-cant-match-game-collection/"><u>Why Playing Monthly Can't Match Game Collection</u></a></li>
</ul></div>

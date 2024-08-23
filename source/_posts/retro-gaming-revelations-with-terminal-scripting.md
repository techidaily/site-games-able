---
title: Retro Gaming Revelations with Terminal Scripting
date: 2024-08-22T22:19:46.270Z
updated: 2024-08-23T22:19:46.270Z
tags:
  - games
categories:
  - games
description: This Article Describes Retro Gaming Revelations with Terminal Scripting
excerpt: This Article Describes Retro Gaming Revelations with Terminal Scripting
keywords: Retro Game Scripts,Terminal Gaming Guide,Gaming Terminals,Scripted Games Revival,Retro Gaming Techniques,Terminal Console Fun,Vintage Gaming Tips
thumbnail: https://thmb.techidaily.com/053654aac9195ea45d1f77852c408a3b2770cc6c802ff6728e9e3d8c452deddb.jpg
---

## Retro Gaming Revelations with Terminal Scripting

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

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-20-must-have-video-tools-for-new-creators-for-2024/"><u>[New] 20 Must-Have Video Tools For New Creators for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-laughter-loops-in-musical-landscape/"><u>[New] 2024 Approved  Laughter Loops in Musical Landscape</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-step-by-step-creation-of-gamers-channel-graphics/"><u>[New] In 2024, Step-By-Step Creation of Gamers' Channel Graphics</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-go-live-with-google-meet-youtube-broadcasting-steps-for-2024/"><u>[Updated] Go Live with Google Meet  YouTube Broadcasting Steps for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-online-marketplaces-for-partnering-with-youtube-content-makers/"><u>[Updated] Online Marketplaces for Partnering With YouTube Content Makers</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-persistent-display-transcription/"><u>[Updated] Persistent Display Transcription</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-prestige-choices-top-rated-sites-for-securing-snapalert-music-for-2024/"><u>[Updated] Prestige Choices  Top-Rated Sites for Securing SnapAlert Music for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-transform-your-zoom-presentations-with-stunning-visuals/"><u>2024 Approved  Transform Your Zoom Presentations with Stunning Visuals</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-itel-p55t-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Itel P55T | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/best-vr-ready-hdmi-enhanced-gaming-devices/"><u>Best VR Ready, HDMI Enhanced Gaming Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-buzzwords-a-closer-look-at-gaming-promos/"><u>Beyond Buzzwords: A Closer Look at Gaming Promos</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-rtx-4060-ti-top-competitive-graphics-cards/"><u>Beyond RTX 4060 Ti: Top Competitive Graphics Cards</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-the-screen-nintendos-next-step/"><u>Beyond the Screen - Nintendo's Next Step?</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-the-screen-the-value-of-game-possessions/"><u>Beyond the Screen: The Value of Game Possessions</u></a></li>
<li><a href="https://games-able.techidaily.com/blackwidow-v4-the-future-of-gaming-keyboards-unleashed/"><u>BlackWidow V4: The Future of Gaming Keyboards Unleashed</u></a></li>
<li><a href="https://games-able.techidaily.com/breaking-barriers-a-guide-to-dual-os-on-your-deck/"><u>Breaking Barriers - A Guide to Dual OS on Your Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/breath-of-fresh-access-on-your-ps5-console/"><u>Breath of Fresh Access on Your PS5 Console</u></a></li>
<li><a href="https://games-able.techidaily.com/breathe-deep-play-hard-top-8-ar-outdoors/"><u>Breathe Deep, Play Hard: Top 8 AR Outdoors</u></a></li>
<li><a href="https://games-able.techidaily.com/breathe-new-life-into-ps5-digital-access/"><u>Breathe New Life Into PS5 Digital Access</u></a></li>
<li><a href="https://games-able.techidaily.com/bypassing-steam-timeouts-tips-for-rust-users/"><u>Bypassing Steam Timeouts: Tips for Rust Users</u></a></li>
<li><a href="https://games-able.techidaily.com/can-am08-pro-assert-its-authenticity-in-magic-gaming/"><u>Can AM08 Pro Assert Its Authenticity in Magic Gaming?</u></a></li>
<li><a href="https://games-able.techidaily.com/can-the-classic-dock-adapt-to-switchs-oled-display/"><u>Can the Classic Dock Adapt to Switch's OLED Display?</u></a></li>
<li><a href="https://games-able.techidaily.com/can-the-price-of-playstation-5-go-down-after-supply-catches-up/"><u>Can the Price of PlayStation 5 Go Down After Supply Catches Up?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/capture-and-save-top-15-insta-downloader-apps/"><u>Capture and Save  Top 15 Insta Downloader Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/celebrating-indie-innovations-my-curated-collection/"><u>Celebrating Indie Innovations: My Curated Collection</u></a></li>
<li><a href="https://games-able.techidaily.com/chair-choice-office-or-game/"><u>Chair Choice: Office or Game?</u></a></li>
<li><a href="https://games-able.techidaily.com/champion-8-virtual-environments-playing-android-on-pcmac/"><u>Champion 8 Virtual Environments: Playing Android on PC/Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/chatgpt-the-future-of-gaming-scriptwriting/"><u>ChatGPT: The Future of Gaming Scriptwriting</u></a></li>
<li><a href="https://games-able.techidaily.com/child-protection-staying-vigilant-in-virtual-spaces/"><u>Child Protection: Staying Vigilant in Virtual Spaces</u></a></li>
<li><a href="https://games-able.techidaily.com/choosing-between-founder-series-and-asus-vega-graphics-cards/"><u>Choosing Between Founder Series and ASUS Vega Graphics Cards</u></a></li>
<li><a href="https://games-able.techidaily.com/circuit-visionaries-a-new-perspective/"><u>Circuit Visionaries: A New Perspective</u></a></li>
<li><a href="https://games-able.techidaily.com/claim-your-free-games-on-xbox-console/"><u>Claim Your Free Games on Xbox Console</u></a></li>
<li><a href="https://games-able.techidaily.com/clandestine-streaming-low-profile-tactics/"><u>Clandestine Streaming: Low Profile Tactics</u></a></li>
<li><a href="https://games-able.techidaily.com/clearing-old-ps5-saves-made-easy/"><u>Clearing Old PS5 Saves Made Easy</u></a></li>
<li><a href="https://games-able.techidaily.com/climb-the-charts-top-websites-to-elevate-your-gamerscore/"><u>Climb the Charts: Top Websites to Elevate Your Gamerscore</u></a></li>
<li><a href="https://games-able.techidaily.com/command-center-controls-essential-tuning-tips-for-fps-beginnings/"><u>Command Center Controls: Essential Tuning Tips for FPS Beginnings</u></a></li>
<li><a href="https://games-able.techidaily.com/commanders-of-victory-managing-soccer-without-paying-a-penny/"><u>Commanders of Victory: Managing Soccer Without Paying a Penny</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-top-gear-at-toms-computing-emporium-a-detailed-review/"><u>Exploring Top Gear at Tom's Computing Emporium - A Detailed Review</u></a></li>
<li><a href="https://android-frp.techidaily.com/full-guide-to-bypass-samsung-galaxy-a14-5g-frp-by-drfone-android/"><u>Full Guide to Bypass Samsung Galaxy A14 5G FRP</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-3-ways-of-how-to-get-someones-apple-id-off-apple-iphone-x-without-password-by-drfone-ios/"><u>In 2024, 3 Ways of How to Get Someones Apple ID Off Apple iPhone X without Password</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-show-wi-fi-password-on-samsung-galaxy-a23-5g-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Samsung Galaxy A23 5G</u></a></li>
<li><a href="https://some-guidance.techidaily.com/switching-on-windows-11-for-automatic-hdr-mode-for-2024/"><u>Switching On Windows 11 for Automatic HDR Mode for 2024</u></a></li>
</ul></div>

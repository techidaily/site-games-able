---
title: Bringing Old-School Gaming Into Your Linux Space
date: 2024-07-29T06:01:05.125Z
updated: 2024-07-30T06:01:05.125Z
tags:
  - games
categories:
  - games
description: This Article Describes Bringing Old-School Gaming Into Your Linux Space
excerpt: This Article Describes Bringing Old-School Gaming Into Your Linux Space
keywords: Linux Gaming Console,Retro Games on Linux,Linux Emulators,Classic PC Gaming,Linux Retro Arcade,Emulate Old-School Games,Gaming in Linux Environment
thumbnail: https://thmb.techidaily.com/a577227bca81f1377b01a00eba21acdee9d8dfcda26cad3482a8cc47d1c6fe1b.jpg
---

## Bringing Old-School Gaming Into Your Linux Space

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Emulate a Game Boy in the Terminal?

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
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
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-craft-your-online-identity-with-customized-youtube-urls/"><u>[New] 2024 Approved  Craft Your Online Identity with Customized YouTube URLs</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-ultimate-windows-11-screen-recorder-guide/"><u>[New] 2024 Approved  Ultimate Windows 11 Screen Recorder Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-dual-display-dominance-top-videographer-verdict-for-2024/"><u>[New] Dual Display Dominance  Top Videographer Verdict for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-effortlessly-connect-camera-roll-to-snapchat-sharing-platforms/"><u>[New] Effortlessly Connect Camera Roll to Snapchat Sharing Platforms</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-spectacular-8-cameras-for-professional-live-viewers/"><u>[Updated] 2024 Approved  Spectacular 8 Cameras for Professional Live Viewers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-the-future-of-social-media-innovating-with-facebook-reels/"><u>[Updated] 2024 Approved  The Future of Social Media  Innovating with Facebook Reels</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-androids-premier-choice-top-10-free-fb-video-extractor/"><u>[Updated] In 2024, Android's Premier Choice  Top 10 Free FB Video Extractor</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-audiopiece-recorder-guide-installation-and-test/"><u>2024 Approved  AudioPiece Recorder Guide  Installation & Test</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-cutting-edge-android-imagery-tweaker/"><u>2024 Approved  Cutting-Edge Android Imagery Tweaker</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-demystifying-screen-recording-how-bandicam-changes-the-game/"><u>2024 Approved  Demystifying Screen Recording  How Bandicam Changes the Game</u></a></li>
<li><a href="https://games-able.techidaily.com/clearing-false-payment-failures-on-playstation/"><u>Clearing False Payment Failures on PlayStation</u></a></li>
<li><a href="https://games-able.techidaily.com/critical-caveats-5-unexamined-aspects-of-game-scores/"><u>Critical Caveats: 5 Unexamined Aspects of Game Scores</u></a></li>
<li><a href="https://games-able.techidaily.com/disc-freeze-the-simple-eject-on-xbox-s/"><u>Disc Freeze? The Simple Eject on Xbox S</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-your-steam-experience-fixes-for-win11/"><u>Enhancing Your Steam Experience: Fixes for Win11</u></a></li>
<li><a href="https://games-able.techidaily.com/experience-next-level-games-with-nvidias-fresh-application/"><u>Experience Next-Level Games with Nvidia’s Fresh Application</u></a></li>
<li><a href="https://games-able.techidaily.com/expertly-chosen-8-java-environments-mobile-simulations/"><u>Expertly Chosen 8 Java Environments, Mobile Simulations</u></a></li>
<li><a href="https://games-able.techidaily.com/fixing-oss-components-required-mishap/"><u>Fixing OS's Components Required Mishap</u></a></li>
<li><a href="https://games-able.techidaily.com/fixing-robloxs-error-code-262-step-by-step/"><u>Fixing Roblox's Error Code 262 Step-by-Step</u></a></li>
<li><a href="https://games-able.techidaily.com/friendly-fire-top-cross-device-games-to-bond-over/"><u>Friendly Fire? Top Cross-Device Games to Bond Over</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-synergy-unpacking-keychron-and-lemokey/"><u>Gaming Synergy: Unpacking Keychron & Lemokey</u></a></li>
<li><a href="https://games-able.techidaily.com/guard-your-conversations-on-xbox-series-xs/"><u>Guard Your Conversations on Xbox Series X|S</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-nubia-red-magic-9-pro-location-is-wrong-drfone-by-drfone-virtual-android/"><u>How to Fix My Nubia Red Magic 9 Pro Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-iphone-14-pro-max-without-swiping-up-6-ways-by-drfone-ios/"><u>How To Unlock iPhone 14 Pro Max Without Swiping Up? 6 Ways</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-use-activities-on-discord-including-chess-and-poker/"><u>How to Use Activities on Discord (Including Chess and Poker)</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-full-guide-to-unlock-apple-iphone-8-plus-with-itunes-by-drfone-ios/"><u>In 2024, Full Guide to Unlock Apple iPhone 8 Plus with iTunes</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-unlock-pro-level-videos-top-free-online-video-editing-tools/"><u>In 2024, Unlock Pro-Level Videos Top Free Online Video Editing Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/insider-look-revolutionary-ai-hardware-at-computex/"><u>Insider Look: Revolutionary AI Hardware at Computex</u></a></li>
<li><a href="https://games-able.techidaily.com/key-considerations-8-steps-for-optimal-cpu-cooler-purchase/"><u>Key Considerations: 8 Steps for Optimal CPU Cooler Purchase</u></a></li>
<li><a href="https://games-able.techidaily.com/leveraging-sonys-controller-for-enhanced-pc-gameplay-experience/"><u>Leveraging Sony’s Controller for Enhanced PC Gameplay Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-switch-time-join-the-3-leading-stream-services/"><u>Maximize Your Switch Time: Join the 3 Leading Stream Services</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-your-discord-experience-with-top-servers/"><u>Maximizing Your Discord Experience with Top Servers</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-new-worlds-together-playing-minecraft-split-screen-on-switch/"><u>Navigating New Worlds Together: Playing Minecraft Split-Screen on Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/older-pcs-reimagined-with-atlasos/"><u>Older PCs Reimagined with AtlasOS</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-steams-content-conflux-on-mac/"><u>Overcoming Steam's Content Conflux on Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/pioneering-the-path-to-play-pre-starfield/"><u>Pioneering the Path to Play Pre-Starfield</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/playlist-power-instagrams-musical-edge-for-2024/"><u>Playlist Power  Instagram's Musical Edge for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/prime-choices-unmatched-tech-for-live-game-recording/"><u>Prime Choices: Unmatched Tech for Live Game Recording</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionize-your-system-with-4-key-features-of-icue-link-by-corsair/"><u>Revolutionize Your System with 4 Key Features of iCUE Link by Corsair</u></a></li>
<li><a href="https://games-able.techidaily.com/silence-speakers-amplify-headphones-on-console/"><u>Silence Speakers, Amplify Headphones on Console</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-windows-7-flicker-a-quick-guide/"><u>Solving Windows 7 Flicker: A Quick Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/synchronizing-online-interactions-minimizing-delay-in-data-transmission/"><u>Synchronizing Online Interactions: Minimizing Delay in Data Transmission</u></a></li>
<li><a href="https://games-able.techidaily.com/tackle-ps4-network-glitches-8-must-try-fixes-explored/"><u>Tackle PS4 Network Glitches: 8 Must-Try Fixes Explored</u></a></li>
<li><a href="https://games-able.techidaily.com/the-financially-smart-gamers-manual-for-series-x/"><u>The Financially-Smart Gamer's Manual for Series X</u></a></li>
<li><a href="https://games-able.techidaily.com/top-techniques-to-enhance-your-steam-decks-abilities-at-the-desk/"><u>Top Techniques to Enhance Your Steam Deck's Abilities at the Desk</u></a></li>
<li><a href="https://games-able.techidaily.com/tricks-and-tips-staying-incognito-on-steam/"><u>Tricks and Tips: Staying Incognito on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-unidentified-game-installations-on-steam/"><u>Troubleshooting Unidentified Game Installations on Steam</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/understanding-and-controlling-facebook-video-playback-for-2024/"><u>Understanding and Controlling Facebook Video Playback for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-excellence-with-nvidias-novel-gaming-app/"><u>Unlocking Excellence with Nvidia's Novel Gaming App</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-gbadvance-legends-on-your-idevice-with-leading-simulators/"><u>Unlocking GBAdvance Legends on Your iDevice with Leading Simulators</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-new-dimensions-in-your-steam-deck-gameplay/"><u>Unlocking New Dimensions in Your Steam Deck Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-your-pc-potential-through-component-match/"><u>Unlocking Your PC Potential Through Component Match</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-should-you-buy-videopad-video-editor-our-honest-review-and-verdict/"><u>Updated In 2024, Should You Buy Videopad Video Editor? Our Honest Review and Verdict</u></a></li>
<li><a href="https://games-able.techidaily.com/what-you-need-to-know-about-palworld-now/"><u>What You Need to Know About PalWorld Now</u></a></li>
</ul></div>

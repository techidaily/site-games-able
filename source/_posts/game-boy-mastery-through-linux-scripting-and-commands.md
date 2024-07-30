---
title: Game Boy Mastery Through Linux Scripting and Commands
date: 2024-07-29T05:53:46.818Z
updated: 2024-07-30T05:53:46.818Z
tags:
  - games
categories:
  - games
description: This Article Describes Game Boy Mastery Through Linux Scripting and Commands
excerpt: This Article Describes Game Boy Mastery Through Linux Scripting and Commands
keywords: Game Boy Linux,Linux Gaming Console,Emulate GB Games,GBLinux Programming,Scripted Game Boy,Command Line GB,Mastery in GB Scripts
thumbnail: https://thmb.techidaily.com/d4d65dffa6d108b05861c08e391929dff0db7f6ebc3e8d7f9915a07380165e20.jpg
---

## Game Boy Mastery Through Linux Scripting and Commands

 The Linux terminal, while certainly a fun place, isn't especially well known as a console gaming platform—largely thanks to its limited ASCII and Braille output. But its Spartan interface is almost perfect for replicating the display of an original 1989 Nintendo Game Boy. Here's how to play Game Boy games in your terminal.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Why Emulate a Game Boy in the Terminal?

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
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
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-snippets-to-stars-the-essence-of-video-musical-success/"><u>[New] 2024 Approved  From Snippets to Stars  The Essence of Video Musical Success</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-top-youtube-titles-crafted-by-ai/"><u>[New] In 2024, Top YouTube Titles Crafted by AI</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-iphone-time-travel-mastering-prolonged-photo-captures-for-2024/"><u>[New] IPhone Time Travel  Mastering Prolonged Photo Captures for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-capturing-moments-like-never-before-with-sj-cam-s6/"><u>[Updated] In 2024, Capturing Moments Like Never Before with SJ-CAM S6</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-streamlining-mov-recordings-in-windows/"><u>[Updated] In 2024, Streamlining MOV Recordings in Windows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-spotify-how-to-halt-default-podcast-additions/"><u>[Updated] Spotify  How to Halt Default Podcast Additions</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-30-list-of-no-cost-high-quality-online-film-effects-tools/"><u>[Updated] The Ultimate 30 List of No-Cost, High-Quality Online Film Effects Tools</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-verdict-on-vllo-performance/"><u>[Updated] The Verdict on VLLO Performance</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-best-14-text-animation-examples/"><u>2024 Approved  Best 14 Text Animation Examples</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-compiled-list-of-top-3ip-ipad-voice-recorders/"><u>2024 Approved  Compiled List of Top 3iP iPad Voice Recorders</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-mastering-instagram-reels-incorporating-music-and-voiceovers/"><u>2024 Approved  Mastering Instagram Reels  Incorporating Music & Voiceovers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-paving-the-way-to-success-with-professional-insights-into-youtube-banners/"><u>2024 Approved  Paving the Way to Success with Professional Insights Into YouTube Banners</u></a></li>
<li><a href="https://games-able.techidaily.com/7-key-advantages-edge-for-gamers-unrivaled-experience/"><u>7 Key Advantages: Edge for Gamers' Unrivaled Experience</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/9-powerful-methods-to-make-money-on-your-youtube-shorts/"><u>9 Powerful Methods to Make Money on Your YouTube Shorts</u></a></li>
<li><a href="https://games-able.techidaily.com/critical-caveats-5-unexamined-aspects-of-game-scores/"><u>Critical Caveats: 5 Unexamined Aspects of Game Scores</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-nintendo-switch-game-with-peripherals-90-chars/"><u>Elevate Your Nintendo Switch Game With Peripherals (90 Chars)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/enhanced-question-guide-for-engaging-audio-content/"><u>Enhanced Question Guide for Engaging Audio Content</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-dungeon-crafting-six-chatgpt-approaches-to-perfect-game-guidance/"><u>Enhancing Dungeon Crafting: Six ChatGPT Approaches to Perfect Game Guidance</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-steam-deck-performance-with-coolers/"><u>Enhancing Steam Deck Performance with Coolers</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-your-steam-experience-fixes-for-win11/"><u>Enhancing Your Steam Experience: Fixes for Win11</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-smooth-mouse-scrolling-action/"><u>Ensuring Smooth Mouse Scrolling Action</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-list-of-top-11-no-cost-words-games-androidios/"><u>Essential List of Top 11 No-Cost Words Games (Android/iOS)</u></a></li>
<li><a href="https://games-able.techidaily.com/examining-sonys-digital-game-access-for-gamers/"><u>Examining Sony’s Digital Game Access for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-non-alcoholic-pathways-for-endocannabinoid-delivery-to-the-brain/"><u>Exploring Non-Alcoholic Pathways for Endocannabinoid Delivery to the Brain</u></a></li>
<li><a href="https://games-able.techidaily.com/five-pillars-of-a-secure-playstation-5-experience/"><u>Five Pillars of a Secure Playstation 5 Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/fixing-robloxs-error-code-262-step-by-step/"><u>Fixing Roblox's Error Code 262 Step-by-Step</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-synergy-unpacking-keychron-and-lemokey/"><u>Gaming Synergy: Unpacking Keychron & Lemokey</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-oneplus-11r-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your OnePlus 11R to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-poco-m6-pro-5g-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Poco M6 Pro 5G Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/harness-the-power-of-insights-a-curated-list-of-instagram-performance-trackers-for-2024/"><u>Harness the Power of Insights  A Curated List of Instagram Performance Trackers for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-itel-a70-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Itel A70 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-vivo-x-fold-2-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Vivo X Fold 2 Phone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/how-to-convert-your-best-videography-into-melodic-mp3s-insta/"><u>How to Convert Your Best Videography Into Melodic MP3s (Insta)</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-honor-magic-5-pro-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Honor Magic 5 Pro Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-apple-iphone-se-2020ipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled Apple iPhone SE (2020)/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-apple-iphone-13-mini-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track WhatsApp Messages on Apple iPhone 13 mini Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-vivo-s17e-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Vivo S17e Phone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-premier-eco-cinema-tech-usage-and-mastery/"><u>In 2024, Premier Eco-Cinema Tech  Usage and Mastery</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-7-phone-number-locators-to-track-vivo-y78t-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Phone Number Locators To Track Vivo Y78t Location | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-unleashing-the-power-of-obs-macos-install-and-usage-tips/"><u>In 2024, Unleashing the Power of OBS  MacOS Install & Usage Tips</u></a></li>
<li><a href="https://some-techniques.techidaily.com/independent-evaluation-the-3dr-solo-experience-for-2024/"><u>Independent Evaluation  The '3DR' Solo Experience for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/integrate-xbox-game-pass-into-steam-link-using-glossi/"><u>Integrate Xbox Game Pass Into Steam Link Using GlosSI</u></a></li>
<li><a href="https://games-able.techidaily.com/is-bottlenecking-by-cpu-happening-to-your-pc-find-out/"><u>Is Bottlenecking by CPU Happening to Your PC? Find Out!</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-recovering-missing-pokemon-go-locations/"><u>Mastering the Art of Recovering Missing Pokémon GO Locations</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-visual-smoothness-with-custom-variable-refresh-rate-on-series-console/"><u>Mastering Visual Smoothness with Custom Variable Refresh Rate on Series Console</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-xbox-xs-track-your-gaming-hours/"><u>Mastering Xbox X/S: Track Your Gaming Hours</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-macs-gaming-capability-with-baldurs-gate-3/"><u>Maximize Your Mac's Gaming Capability with Baldur’s Gate 3</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-launcher-problem-code-0x803f8001-on-windows/"><u>Navigating Launcher Problem Code 0X803F8001 on Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-new-worlds-together-playing-minecraft-split-screen-on-switch/"><u>Navigating New Worlds Together: Playing Minecraft Split-Screen on Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/optical-vs-mechanical-switches-whats-best-for-gaming/"><u>Optical Vs. Mechanical Switches: What’s Best for Gaming?</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-win11-steam-network-failure/"><u>Overcoming Win11 Steam Network Failure</u></a></li>
<li><a href="https://games-able.techidaily.com/prime-choices-unmatched-tech-for-live-game-recording/"><u>Prime Choices: Unmatched Tech for Live Game Recording</u></a></li>
<li><a href="https://games-able.techidaily.com/ready-for-a-game-check-out-chatgpts-best-six-games/"><u>Ready for a Game? Check Out ChatGPT's Best Six Games!</u></a></li>
<li><a href="https://games-able.techidaily.com/reasons-xbox-series-s-lacks-a-disc-drive/"><u>Reasons Xbox Series S Lacks a Disc Drive</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-se-2020-data-from-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone SE (2020) Data From iTunes Backup | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/reminiscing-the-past-playing-xbox-games-in-modern-times-pc/"><u>Reminiscing the Past: Playing Xbox Games in Modern Times (PC)</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-disconnected-joy-cons-in-nintendo-switch/"><u>Resolving Disconnected Joy-Cons in Nintendo Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/reverted-steps-to-retrace-controller-updates/"><u>Reverted: Steps to Retrace Controller Updates</u></a></li>
<li><a href="https://extra-information.techidaily.com/srgb-standardization-the-next-step-beyond-traditional-rgb/"><u>Srgb Standardization  The Next Step Beyond Traditional Rgb</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-vivo-y100t-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Vivo Y100t FRP</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-user-engagement-with-smart-switch-management/"><u>Streamline User Engagement with Smart Switch Management</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-your-steam-screenshot-process/"><u>Streamline Your Steam Screenshot Process</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-budget-friendly-240hz-monitors-for-gaming/"><u>The Best Budget-Friendly 240Hz Monitors for Gaming</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-infinix-smart-8-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Infinix Smart 8 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/the-financially-smart-gamers-manual-for-series-x/"><u>The Financially-Smart Gamer's Manual for Series X</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-gaming-experience-with-a-dual-boot-system/"><u>Transform Your Gaming Experience with a Dual-Boot System</u></a></li>
<li><a href="https://games-able.techidaily.com/tricks-and-tips-staying-incognito-on-steam/"><u>Tricks and Tips: Staying Incognito on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-collection-10-free-ad-less-games-for-your-phone/"><u>Ultimate Collection: 10 Free, Ad-Less Games for Your Phone</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-samsung-galaxy-f14-5g-by-fonelab-android-recover-video/"><u>Undeleted lost videos from Samsung Galaxy F14 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-new-dimensions-in-your-steam-deck-gameplay/"><u>Unlocking New Dimensions in Your Steam Deck Gameplay</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/whats-encrypted-exploring-the-role-of-facebooks-blue-icon-in-2024/"><u>What's Encrypted  Exploring the Role of Facebook's Blue Icon, In 2024</u></a></li>
<li><a href="https://techidaily.com/will-mov-files-play-on-xiaomi-redmi-note-13-proplus-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Will MOV files play on Xiaomi Redmi Note 13 Pro+ 5G ?</u></a></li>
</ul></div>

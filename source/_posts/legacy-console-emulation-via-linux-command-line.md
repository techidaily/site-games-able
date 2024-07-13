---
title: Legacy Console Emulation via Linux Command Line
date: 2024-07-12T03:53:05.145Z
updated: 2024-07-13T03:53:05.145Z
tags:
  - games
categories:
  - games
description: This Article Describes Legacy Console Emulation via Linux Command Line
excerpt: This Article Describes Legacy Console Emulation via Linux Command Line
keywords: Legacy Gaming on Linux,Console Emulation Linux,PC Console Playing,Linux Game Emulator,Retro Games Linux,Linux Emulated Consoles,Command-Line Console Emulation
thumbnail: https://thmb.techidaily.com/177db7c45381f8f94f304fef5764a3ae21d49762f0d50b119bc79b8987d4ee6b.jpg
---

## Legacy Console Emulation via Linux Command Line

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
<li><a href="https://games-able.techidaily.com/experience-next-level-games-with-nvidias-fresh-application/"><u>Experience Next-Level Games with Nvidia’s Fresh Application</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-samsung-galaxy-m14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-list-of-top-11-no-cost-words-games-androidios/"><u>Essential List of Top 11 No-Cost Words Games (Android/iOS)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-simplified-video-posts-on-twitter-and-tumblr-for-2024/"><u>[Updated] Simplified Video Posts on Twitter and Tumblr for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/what-is-ai-generated-text-in-2024/"><u>What Is AI Generated Text, In 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-huawei-p60-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Huawei P60 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-smooth-mouse-scrolling-action/"><u>Ensuring Smooth Mouse Scrolling Action</u></a></li>
<li><a href="https://games-able.techidaily.com/insider-look-revolutionary-ai-hardware-at-computex/"><u>Insider Look: Revolutionary AI Hardware at Computex</u></a></li>
<li><a href="https://games-able.techidaily.com/friendly-fire-top-cross-device-games-to-bond-over/"><u>Friendly Fire? Top Cross-Device Games to Bond Over</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-use-activities-on-discord-including-chess-and-poker/"><u>How to Use Activities on Discord (Including Chess and Poker)</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-the-comprehensive-guide-to-crafting-great-documentary-narratives/"><u>[Updated] The Comprehensive Guide to Crafting Great Documentary Narratives</u></a></li>
<li><a href="https://games-able.techidaily.com/ready-for-a-game-check-out-chatgpts-best-six-games/"><u>Ready for a Game? Check Out ChatGPT's Best Six Games!</u></a></li>
<li><a href="https://games-able.techidaily.com/leveraging-sonys-controller-for-enhanced-pc-gameplay-experience/"><u>Leveraging Sony’s Controller for Enhanced PC Gameplay Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-xbox-xs-track-your-gaming-hours/"><u>Mastering Xbox X/S: Track Your Gaming Hours</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-cosmic-divides-metaverse-and-multiverse-explained/"><u>2024 Approved  Unveiling Cosmic Divides  Metaverse and Multiverse Explained</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-your-steam-experience-fixes-for-win11/"><u>Enhancing Your Steam Experience: Fixes for Win11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/a-complete-rundown-on-excellent-screen-recording-of-facetime-calls/"><u>A Complete Rundown on Excellent Screen-Recording of FaceTime Calls</u></a></li>
<li><a href="https://games-able.techidaily.com/reminiscing-the-past-playing-xbox-games-in-modern-times-pc/"><u>Reminiscing the Past: Playing Xbox Games in Modern Times (PC)</u></a></li>
<li><a href="https://games-able.techidaily.com/older-pcs-reimagined-with-atlasos/"><u>Older PCs Reimagined with AtlasOS</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-macs-gaming-capability-with-baldurs-gate-3/"><u>Maximize Your Mac's Gaming Capability with Baldur’s Gate 3</u></a></li>
<li><a href="https://games-able.techidaily.com/key-considerations-8-steps-for-optimal-cpu-cooler-purchase/"><u>Key Considerations: 8 Steps for Optimal CPU Cooler Purchase</u></a></li>
<li><a href="https://games-able.techidaily.com/reasons-xbox-series-s-lacks-a-disc-drive/"><u>Reasons Xbox Series S Lacks a Disc Drive</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-win11-steam-network-failure/"><u>Overcoming Win11 Steam Network Failure</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-money-saving-heavens-storage-service-big-file-batches/"><u>In 2024, Money-Saving Heavens Storage Service - Big File Batches</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-your-discord-experience-with-top-servers/"><u>Maximizing Your Discord Experience with Top Servers</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-steam-deck-performance-with-coolers/"><u>Enhancing Steam Deck Performance with Coolers</u></a></li>
<li><a href="https://games-able.techidaily.com/prime-choices-unmatched-tech-for-live-game-recording/"><u>Prime Choices: Unmatched Tech for Live Game Recording</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-launcher-problem-code-0x803f8001-on-windows/"><u>Navigating Launcher Problem Code 0X803F8001 on Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-new-worlds-together-playing-minecraft-split-screen-on-switch/"><u>Navigating New Worlds Together: Playing Minecraft Split-Screen on Switch</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-economic-approaches-to-online-educational-broadcasting/"><u>[Updated] Economic Approaches to Online Educational Broadcasting</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-synergy-unpacking-keychron-and-lemokey/"><u>Gaming Synergy: Unpacking Keychron & Lemokey</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-switch-time-join-the-3-leading-stream-services/"><u>Maximize Your Switch Time: Join the 3 Leading Stream Services</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-how-to-make-discord-gif-pfp/"><u>Updated 2024 Approved How to Make Discord GIF PFP</u></a></li>
<li><a href="https://games-able.techidaily.com/optical-vs-mechanical-switches-whats-best-for-gaming/"><u>Optical Vs. Mechanical Switches: What’s Best for Gaming?</u></a></li>
<li><a href="https://games-able.techidaily.com/guard-your-conversations-on-xbox-series-xs/"><u>Guard Your Conversations on Xbox Series X|S</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-quick-tips-eradicate-online-ads-from-your-feed/"><u>2024 Approved  Quick Tips  Eradicate Online Ads From Your Feed</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultimate-techniques-for-youtube-mp4-creation-for-2024/"><u>Ultimate Techniques for YouTube MP4 Creation for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/examining-sonys-digital-game-access-for-gamers/"><u>Examining Sony’s Digital Game Access for Gamers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-find-x6-pro-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo Find X6 Pro to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-dungeon-crafting-six-chatgpt-approaches-to-perfect-game-guidance/"><u>Enhancing Dungeon Crafting: Six ChatGPT Approaches to Perfect Game Guidance</u></a></li>
<li><a href="https://games-able.techidaily.com/pioneering-the-path-to-play-pre-starfield/"><u>Pioneering the Path to Play Pre-Starfield</u></a></li>
<li><a href="https://games-able.techidaily.com/is-bottlenecking-by-cpu-happening-to-your-pc-find-out/"><u>Is Bottlenecking by CPU Happening to Your PC? Find Out!</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-the-ultimate-cheatsheet-to-15-adobe-animate-alternatives/"><u>Updated In 2024, The Ultimate Cheatsheet to 15 Adobe Animate Alternatives</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-vivo-y200-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Vivo Y200 Phone</u></a></li>
<li><a href="https://games-able.techidaily.com/integrate-xbox-game-pass-into-steam-link-using-glossi/"><u>Integrate Xbox Game Pass Into Steam Link Using GlosSI</u></a></li>
<li><a href="https://games-able.techidaily.com/five-pillars-of-a-secure-playstation-5-experience/"><u>Five Pillars of a Secure Playstation 5 Experience</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-infinix-smart-8-plus-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Infinix Smart 8 Plus without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-nexus-development-summary-pinnacle-studio-audit-2023/"><u>In 2024, Nexus Development Summary  Pinnacle Studio Audit, 2023</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-disconnected-joy-cons-in-nintendo-switch/"><u>Resolving Disconnected Joy-Cons in Nintendo Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-non-alcoholic-pathways-for-endocannabinoid-delivery-to-the-brain/"><u>Exploring Non-Alcoholic Pathways for Endocannabinoid Delivery to the Brain</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-visual-smoothness-with-custom-variable-refresh-rate-on-series-console/"><u>Mastering Visual Smoothness with Custom Variable Refresh Rate on Series Console</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-the-complete-guide-to-muting-unwanted-audio-layers-in-audacity/"><u>New The Complete Guide to Muting Unwanted Audio Layers in Audacity</u></a></li>
<li><a href="https://games-able.techidaily.com/fixing-robloxs-error-code-262-step-by-step/"><u>Fixing Roblox's Error Code 262 Step-by-Step</u></a></li>
</ul></div>

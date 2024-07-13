---
title: Game Boy Mastery Through Linux Scripting and Commands
date: 2024-07-12T03:10:50.846Z
updated: 2024-07-13T03:10:50.846Z
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
<li><a href="https://games-able.techidaily.com/premature-play-gamers-perspective-unveiled/"><u>Premature Play: Gamers' Perspective Unveiled</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-choosing-your-perfect-match-leading-mac-based-audio-tagging-software-for-2024/"><u>Updated Choosing Your Perfect Match Leading Mac-Based Audio Tagging Software for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162755876-online-games-under-siege-security-alert/"><u>Online Games Under Siege: Security Alert</u></a></li>
<li><a href="https://games-able.techidaily.com/todays-gamers-meet-retro-classics/"><u>Today's Gamers Meet Retro Classics</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-effective-steam-value-exploitation/"><u>Strategies for Effective Steam Value Exploitation</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-potential-on-twitch-tips-for-quality-content/"><u>Unlocking Potential on Twitch: Tips for Quality Content</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-expert-approved-4k-video-editing-software-the-top-choices/"><u>New In 2024, Expert-Approved 4K Video Editing Software The Top Choices</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-8-best-youtube-video-promotion-services-real/"><u>[New] 8 Best YouTube Video Promotion Services (Real)</u></a></li>
<li><a href="https://games-able.techidaily.com/the-future-in-your-hands-ifa-2023-displays/"><u>The Future in Your Hands - IFA 2023 Displays</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-experts-guide-to-the-15-top-luts-for-gopro-films/"><u>[New] Expert's Guide to The 15 Top LUTs for GoPro Films</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-guide-to-professional-xbox-recording-tools/"><u>Ultimate Guide to Professional Xbox Recording Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/step-by-step-guide-to-fixing-robloxs-error-403-on-pc/"><u>Step-by-Step Guide to Fixing Roblox's Error 403 on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166740000-jumpstart-savings-with-sonys-midyear-blowout/"><u>Jumpstart Savings with Sony's Midyear Blowout</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-palworld-everything-you-need-to-know/"><u>What Is Palworld? Everything You Need to Know</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-the-dynamic-evolution-in-mmo-worlds/"><u>Exploring the Dynamic Evolution in MMO Worlds</u></a></li>
<li><a href="https://games-able.techidaily.com/fix-your-faulty-ps4-joystick-a-comprehensive-troubleshooting-guide/"><u>Fix Your Faulty Ps4 Joystick: A Comprehensive Troubleshooting Guide</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-building-blocks-for-successful-channel-branding-and-growth/"><u>[Updated] In 2024, Building Blocks for Successful Channel Branding and Growth</u></a></li>
<li><a href="https://games-able.techidaily.com/the-role-of-endocannabinoids-in-modulating-immune-responses-and-disease-progression/"><u>The Role of Endocannabinoids in Modulating Immune Responses and Disease Progression</u></a></li>
<li><a href="https://games-able.techidaily.com/expanding-horizons-different-switch-regions/"><u>Expanding Horizons: Different Switch Regions</u></a></li>
<li><a href="https://games-able.techidaily.com/rejuvenate-play-replacing-your-switchs-joystick/"><u>Rejuvenate Play: Replacing Your Switch's Joystick</u></a></li>
<li><a href="https://games-able.techidaily.com/opera-gx-versus-edge-top-gaming-browsers-ranked/"><u>Opera GX Versus Edge: Top Gaming Browsers Ranked</u></a></li>
<li><a href="https://games-able.techidaily.com/the-insiders-guide-to-exceptional-discord-communities/"><u>The Insider's Guide to Exceptional Discord Communities</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/leveraging-social-media-trends-for-fan-growth-on-igtv-for-2024/"><u>Leveraging Social Media Trends for Fan Growth on IGTV for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-vivo-y17s-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Vivo Y17s Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/secure-your-steam-deck-2024s-premium-cases-list/"><u>Secure Your Steam Deck: 2024'S Premium Cases List</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-an-authentic-evaluation-of-recordcast-services/"><u>2024 Approved  An Authentic Evaluation of RecordCast Services</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-ultimate-guide-to-decreasing-sounds-prominence-in-lumafusion/"><u>2024 Approved  The Ultimate Guide to Decreasing Sounds' Prominence in Lumafusion</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/mastering-gifs-a-step-by-step-snapchat-guide-for-2024/"><u>Mastering GIFs  A Step-by-Step Snapchat Guide for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-ultimate-fb-video-advertising-handbook-a-compreenas-guide/"><u>The Ultimate FB Video Advertising Handbook  A Compreenas Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-soundscapes-synopsis-a-guide-to-visual-tunes/"><u>[Updated] Soundscapes Synopsis  A Guide to Visual Tunes</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-essential-tiktok-raps-must-hear-modern-beats/"><u>[Updated] Essential TikTok Raps  Must-Hear Modern Beats</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-purchase-process-on-steam/"><u>Streamlining Purchase Process on Steam</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-comparing-youtube-and-dailymotion-notable-contrasts/"><u>[New] 2024 Approved  Comparing YouTube and Dailymotion  Notable Contrasts</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-steam-software-data-check-failure/"><u>Overcoming Steam Software Data Check Failure</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-nuances-of-xbox-control-panel-brightness-settings/"><u>Navigating the Nuances of Xbox Control Panel Brightness Settings</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-employing-google-trends-to-discover-compelling-video-themes/"><u>[Updated] 2024 Approved  Employing Google Trends to Discover Compelling Video Themes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-elite-list-of-best-videocall-services-without-cost-for-2024/"><u>[New] Elite List of Best Videocall Services Without Cost for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/reinstating-aps-restart-license-on-ps5/"><u>Reinstating Aps: Restart License on PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-peak-performance-with-our-best-gamers-keyboard-lists/"><u>Unlock Peak Performance with Our Best Gamers' Keyboard Lists</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-checklist-for-joining-notable-discords/"><u>The Ultimate Checklist for Joining Notable Discords</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-how-to-edit-video-for-tiktok-on-mac/"><u>2024 Approved  How to Edit Video for TikTok on Mac</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-one-to-another-mastering-playlists-pivoting/"><u>From One to Another  Mastering Playlists Pivoting</u></a></li>
<li><a href="https://games-able.techidaily.com/is-the-gaming-world-bracing-for-higher-chip-costs/"><u>Is the Gaming World Bracing for Higher Chip Costs?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-startup-success-on-youtubing-free-beginner-courses/"><u>[Updated] Startup Success on YouTubing  Free Beginner Courses</u></a></li>
<li><a href="https://games-able.techidaily.com/mac-gaming-enhanced-counter-strike-2-basics/"><u>Mac Gaming Enhanced: Counter-Strike 2 Basics</u></a></li>
<li><a href="https://games-able.techidaily.com/the-simple-ways-to-prolong-your-nintendo-switchs-life/"><u>The Simple Ways to Prolong Your Nintendo Switch's Life</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-devices-into-virtual-arcade-machines-our-4p-emulators/"><u>Transform Your Devices Into Virtual Arcade Machines - Our 4P Emulators</u></a></li>
<li><a href="https://games-able.techidaily.com/unleash-potential-self-fix-your-xbox-controllers/"><u>Unleash Potential - Self-Fix Your Xbox Controllers</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-value-of-switchs-online-service/"><u>Navigating the Value of Switch's Online Service</u></a></li>
<li><a href="https://games-able.techidaily.com/pitch-perfect-your-guide-to-the-best-mobile-sports-apps-iosandroid/"><u>Pitch Perfect: Your Guide to the Best Mobile Sports Apps (iOS/Android)</u></a></li>
<li><a href="https://games-able.techidaily.com/fixing-erratic-wireless-signals-on-ps5-console/"><u>Fixing Erratic Wireless Signals on PS5 Console</u></a></li>
<li><a href="https://games-able.techidaily.com/optimal-audio-enhancements-for-switch-gaming/"><u>Optimal Audio Enhancements for Switch Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-troubleshoot-unheard-sounds-on-xbox-console/"><u>How to Troubleshoot Unheard Sounds on Xbox Console</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-home-entertainment-with-playnite-fullscreen-tv/"><u>Transform Home Entertainment with Playnite Fullscreen TV</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-prime-guide-the-ten-best-budget-screen-share-software/"><u>[Updated] 2024 Approved  Prime Guide  The Ten Best Budget Screen Share Software</u></a></li>
<li><a href="https://games-able.techidaily.com/mac-users-enjoy-fortnite-except-for-not-everything/"><u>Mac Users: Enjoy Fortnite - Except For... Not Everything</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-excellence-the-ultimate-guide-to-apple-arcade-games/"><u>Unlock Excellence: The Ultimate Guide to Apple Arcade Games</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-step-by-step-tips-for-successful-snapchat-branding/"><u>[Updated] 2024 Approved  Step-by-Step Tips for Successful Snapchat Branding</u></a></li>
</ul></div>

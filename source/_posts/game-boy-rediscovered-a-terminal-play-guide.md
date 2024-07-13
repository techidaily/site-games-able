---
title: "Game Boy Rediscovered: A Terminal Play Guide"
date: 2024-07-12T03:17:54.526Z
updated: 2024-07-13T03:17:54.526Z
tags:
  - games
categories:
  - games
description: "This Article Describes Game Boy Rediscovered: A Terminal Play Guide"
excerpt: "This Article Describes Game Boy Rediscovered: A Terminal Play Guide"
keywords: Gameboy Redeemed,GB Rediscovery,Retro Gamer Tips,Nintendo GB Guide,Terminal GB Basics,Classic GB Play,Vintage Game Boy
thumbnail: https://thmb.techidaily.com/b7fdec82e5e2a50f89b07a18bb64e205705f93d7819f0fe370579d848f9daaea.jpg
---

## Game Boy Rediscovered: A Terminal Play Guide

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
<li><a href="https://ai-video-editing.techidaily.com/in-2024-make-a-countdown-video/"><u>In 2024, Make A Countdown Video</u></a></li>
<li><a href="https://games-able.techidaily.com/11-exciting-gaming-options-without-wifi/"><u>11 Exciting Gaming Options Without WiFi</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-software-to-fix-and-repair-corrupt-mp4-mov-avi-video-files-of-oppo-reno-11-pro-5g-by-stellar-video-repair-mobile-video-repair/"><u>Best software to Fix and Repair Corrupt MP4,MOV,AVI video files of Oppo Reno 11 Pro 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/11-captivating-phone-game-experiences-anytime-anyplace/"><u>11 Captivating Phone Game Experiences Anytime, Anyplace</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-guide-to-structuring-youtube-content-with-separate-chapters/"><u>[Updated] 2024 Approved  Guide to Structuring YouTube Content with Separate Chapters</u></a></li>
<li><a href="https://games-able.techidaily.com/10-mistakes-to-avoid-when-shopping-for-a-monitor/"><u>10 Mistakes to Avoid When Shopping for a Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/144hz-monitors-the-ultimate-gaming-visual-experience/"><u>144Hz Monitors: The Ultimate Gaming Visual Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/10-tips-to-sharpen-your-monitor-buying-skills/"><u>10 Tips to Sharpen Your Monitor Buying Skills</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160505091-4-premium-game-boy-advance-emulators-for-your-idevice/"><u>4 Premium Game Boy Advance Emulators for Your iDevice!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161005802-conquer-nyts-latest-word-obsession-mastery-of-strands-awaits/"><u>Conquer NYT's Latest Word Obsession: Mastery of 'Strands' Awaits</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164610715-enhance-experience-and-space-with-extra-large-front-ends/"><u>Enhance Experience & Space With Extra-Large Front Ends!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/optimize-sound-clarity-top-audio-interface-recommendations/"><u>Optimize Sound Clarity  Top Audio Interface Recommendations</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160130709-rewind-to-retro-play-psp-on-iphone-today/"><u>Rewind to Retro: Play PSP on iPhone Today</u></a></li>
<li><a href="https://games-able.techidaily.com/1719158002542-play-along-with-youtubes-newest-test-mini-games/"><u>Play Along with YouTube's Newest Test Mini-Games!</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-revolutionize-creative-tasks-with-proficiency-ai-voice-cloning/"><u>In 2024, Revolutionize Creative Tasks With Proficiency AI Voice Cloning</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-elevate-your-storytelling-on-snapchat-with-top-tips/"><u>[Updated] In 2024, Elevate Your Storytelling on Snapchat with Top Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166302664-top-9-affordable-switch-games-no-pay-required/"><u>Top 9 Affordable Switch Games: No Pay Required!</u></a></li>
<li><a href="https://extra-information.techidaily.com/optimal-podcast-duration-finding-your-perfect-speaking-span/"><u>Optimal Podcast Duration  Finding Your Perfect Speaking Span</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164823498-amp-up-arcade-vibes-with-enlarged-frontend-frames/"><u>Amp Up Arcade Vibes with Enlarged Frontend Frames</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-cutting-edge-sound-management-the-top-5-android-audio-editors-every-professional-should-own/"><u>New In 2024, Cutting Edge Sound Management The Top 5 Android Audio Editors Every Professional Should Own</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/elevate-your-stream-with-these-5-top-tier-cams-for-2024/"><u>Elevate Your Stream with These 5 Top-Tier Cams for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-motorola-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Motorola</u></a></li>
<li><a href="https://games-able.techidaily.com/10-key-perks-why-gamers-choose-steam-first/"><u>10 Key Perks: Why Gamers Choose Steam First</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/deciphering-the-art-of-personalized-playlist-curation-for-youtube/"><u>Deciphering the Art of Personalized Playlist Curation for YouTube</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163110616-nvidia-driver-updates-unlock-your-computers-potential-immediately/"><u>Nvidia Driver Updates: Unlock Your Computer's Potential Immediately</u></a></li>
<li><a href="https://games-able.techidaily.com/1440p-gaming-monitor-buying-guide-budget-friendly-options/"><u>1440P Gaming Monitor Buying Guide - Budget-Friendly Options</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163288986-unlock-footballs-secrets-fc-manager-game-free-edition/"><u>Unlock Football's Secrets: FC Manager Game, Free Edition!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162140368-enter-the-world-of-fun-with-chatgpts-6-best-games/"><u>Enter the World of Fun with ChatGPT's 6 Best Games</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-ultimate-guide-to-valheim-sowing-seeds/"><u>[New] In 2024, Ultimate Guide to Valheim Sowing Seeds</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/harness-the-full-power-of-google-photos/"><u>Harness the Full Power of Google Photos</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-video-editing-on-windows-best-imovie-substitutes/"><u>Updated 2024 Approved Video Editing on Windows Best iMovie Substitutes</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161422913-unlocking-gbadvance-legends-on-your-idevice-with-leading-simulators/"><u>Unlocking GBAdvance Legends on Your iDevice with Leading Simulators!</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-free-slo-mo-camera-apps-for-iphone-and-android-phones-for-2024/"><u>Best Free Slo-Mo Camera Apps for iPhone and Android Phones for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719159121499-upgrade-your-game-cabinet-with-broad-bold-framing/"><u>Upgrade Your Game Cabinet with Broad, Bold Framing</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164936464-the-importance-of-accessibility-and-inclusivity-in-map-design-including-the-use-of-tactile-maps-and-braille-labels/"><u>The Importance of Accessibility and Inclusivity in Map Design, Including the Use of Tactile Maps and Braille Labels</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/navigating-alternative-sound-editing-tools-top-7-on-mobile-platforms/"><u>Navigating Alternative Sound Editing Tools Top 7 on Mobile Platforms</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-symphony-of-screens-adding-music-to-online-chronicles-for-2024/"><u>[New] Symphony of Screens  Adding Music to Online Chronicles for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719158810853-experience-the-thrill-play-six-amazing-chatgpt-games/"><u>Experience the Thrill: Play Six Amazing ChatGPT Games</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164636469-challenges-associated-with-updating-outdated-or-incorrect-maps/"><u>Challenges Associated with Updating Outdated or Incorrect Maps</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-decoding-app-dynamics-an-in-depth-analysis-of-tiktok-and-snaps-similarities/"><u>[Updated] In 2024, Decoding App Dynamics  An In-Depth Analysis of TikTok & Snap's Similarities</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164865100-lighteconomonitor-27m2v-hd-gamers-choice/"><u>LightEconoMonitor: 27M2V HD Gamers Choice!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719158889811-new-nvidia-driver-release-improve-pc-performance-instantly/"><u>New Nvidia Driver Release – Improve PC Performance Instantly.</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164401657-discover-iphones-best-video-game-emulators-now/"><u>Discover iPhone's Best Video Game Emulators Now</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-prime-selector-20-twitters-animated-treasure-chest/"><u>[New] In 2024, Prime Selector 2.0  Twitter's Animated Treasure Chest</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163608201-nostalgia-at-a-swipe-ios-and-the-classics-of-psp/"><u>Nostalgia at a Swipe: IOS and the Classics of PSP</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/screen-to-air-comparison-who-wins-obs-or-twitch-studio-for-2024/"><u>Screen to Air Comparison  Who Wins, OBS or Twitch Studio for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-explore-the-top-5-alternative-video-streaming-for-ios-android/"><u>2024 Approved  Explore the Top 5 Alternative Video Streaming for iOS, Android</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164624136-top-ranked-gba-ios-simulators-unveiled/"><u>Top-Ranked GBA iOS Simulators Unveiled!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719165881041-ios-gba-mastery-discover-the-top-4-emulators/"><u>IOS GBA Mastery: Discover the Top 4 Emulators</u></a></li>
<li><a href="https://games-able.techidaily.com/1719158910114-transform-gaming-spaces-select-large-scale-cabinet-panels/"><u>Transform Gaming Spaces: Select Large-Scale Cabinet Panels!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162065608-top-4-ios-superior-game-boy-advance-emulators/"><u>Top 4 iOS: Superior Game Boy Advance Emulators</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-how-to-make-a-video-call-in-whatsapp-web-in-laptop-for-2024/"><u>[Updated] How to Make a Video Call in WhatsApp Web in Laptop for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-socialsnatcher-hd-extractor/"><u>[Updated] SocialSnatcher HD Extractor</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163487039-become-a-master-at-nyts-strands-play-and-win/"><u>Become a Master at NYT’s Strands: Play & Win!</u></a></li>
<li><a href="https://games-able.techidaily.com/11-must-try-free-word-game-apps-for-both-sides/"><u>11 Must-Try Free Word Game Apps for Both Sides</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/synchronized-screenscape-tv-loops-of-online-media/"><u>Synchronized Screenscape  TV Loops of Online Media</u></a></li>
<li><a href="https://games-able.techidaily.com/1719159039150-fan-the-flames-of-football-management-winning-soccer-coaching-free/"><u>Fan the Flames of Football Management: Winning Soccer Coaching, Free!</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-achieve-professional-results-access-to-10-basic-free-and-paid-luts-for-canon-cams/"><u>In 2024, Achieve Professional Results  Access to 10 Basic Free and Paid LUTs for Canon Cams</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-epicurean-escapades-worlds-favorite-meals-unveiled-for-2024/"><u>[Updated] Epicurean Escapades  World's Favorite Meals Unveiled for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163779461-how-different-cultures-have-developed-unique-approaches-to-map-design-and-symbolization/"><u>How Different Cultures Have Developed Unique Approaches to Map Design and Symbolization;</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2023-top-6-facebook-lite-video-downloaders/"><u>[New] 2023 | Top 6 Facebook Lite Video Downloaders</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166103892-top-4-ios-emulators-bring-classic-gbadvance-games-alive/"><u>Top 4 iOS Emulators: Bring Classic GBAdvance Games Alive</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-unlock-the-power-of-quick-scrolling-tips-for-tiktok-users-for-2024/"><u>[Updated] Unlock the Power of Quick Scrolling  Tips for TikTok Users for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-stepwise-discovery-of-covert-youtube-archives/"><u>[Updated] Stepwise Discovery of Covert YouTube Archives</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-perfecting-the-aesthetic-ootd-tiktok-on-a-mac/"><u>[Updated] Perfecting the Aesthetic  OOTD TikTok on a Mac</u></a></li>
<li><a href="https://audio-editing.techidaily.com/live-audio-capture-techniques-for-todays-streaming-platforms-for-2024/"><u>Live Audio Capture Techniques for Todays Streaming Platforms for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-unlock-potential-the-15-best-tools-for-transforming-fb-revenue/"><u>[Updated] 2024 Approved  Unlock Potential  The 15 Best Tools for Transforming FB Revenue</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164863987-gamers-discover-the-future-oled-monitors/"><u>Gamers, Discover the Future - OLED Monitors!</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/in-2024-portrait-perfection-crafting-engaging-vertical-experiences/"><u>In 2024, Portrait Perfection Crafting Engaging Vertical Experiences</u></a></li>
</ul></div>

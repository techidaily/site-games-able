---
title: Linux Terminal Guide to GB Advance Games
date: 2024-07-12T03:43:51.468Z
updated: 2024-07-13T03:43:51.468Z
tags:
  - games
categories:
  - games
description: This Article Describes Linux Terminal Guide to GB Advance Games
excerpt: This Article Describes Linux Terminal Guide to GB Advance Games
keywords: GB Advanced Gaming Linux,Linux GB Game Tips,GB Games Terminal Command,Linux for GB Games,Terminal GUIGB Guide,GB Games Console Linux,Linux GB Gaming Help
thumbnail: https://thmb.techidaily.com/d28e7047daab181b2a6cda74108f4cb993066496eb332810c3bf1138a8452ea4.jpg
---

## Linux Terminal Guide to GB Advance Games

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
<li><a href="https://games-able.techidaily.com/1719165321460-discover-the-best-idevice-gaming-without-internet-or-wi-fi/"><u>Discover the Best iDevice Gaming without Internet or Wi-Fi!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719159039150-fan-the-flames-of-football-management-winning-soccer-coaching-free/"><u>Fan the Flames of Football Management: Winning Soccer Coaching, Free!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164823498-amp-up-arcade-vibes-with-enlarged-frontend-frames/"><u>Amp Up Arcade Vibes with Enlarged Frontend Frames</u></a></li>
<li><a href="https://games-able.techidaily.com/1719165142774-overheat-no-more-top-accessories-listed/"><u>Overheat No More: Top Accessories Listed!</u></a></li>
<li><a href="https://games-able.techidaily.com/11-cross-platform-mobile-multiplayer-games-to-play-with-friends/"><u>11 Cross-Platform Mobile Multiplayer Games to Play With Friends</u></a></li>
<li><a href="https://games-able.techidaily.com/6-reasons-why-macs-arent-great-for-gaming/"><u>6 Reasons Why Macs Aren't Great for Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-towards-better-gameplay-replace-joy-con-joysticks/"><u>A Step Towards Better Gameplay: Replace Joy-Con Joysticks</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163462577-interactive-storytelling-at-your-fingertips/"><u>Interactive Storytelling at Your Fingertips</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-nokia-150-2023-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Nokia 150 (2023) Location on Viber | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162149427-unleash-a-superior-gameplay-experience-with-these-5-reasons-to-purchase/"><u>Unleash a Superior Gameplay Experience with These 5 Reasons to Purchase</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166201276-sneak-into-stats-world-manage-football-teams-forfree/"><u>Sneak Into Stats World: Manage Football Teams Forfree!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-change-honor-80-pro-straight-screen-edition-lock-screen-clock-in-seconds-by-drfone-android/"><u>How To Change Honor 80 Pro Straight Screen Edition Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-cultivating-connection-not-compulsion-in-subscriptions/"><u>2024 Approved  Cultivating Connection, Not Compulsion in Subscriptions</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164610715-enhance-experience-and-space-with-extra-large-front-ends/"><u>Enhance Experience & Space With Extra-Large Front Ends!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161112435-winning-at-soccer-management-playing-championship-manager-on-windows-no-cost/"><u>Winning at Soccer Management: Playing Championship Manager on Windows, No Cost!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166110964-optimize-performance-dont-delay-download-new-nvidia-drivers/"><u>Optimize Performance - Don’t Delay, Download New Nvidia Drivers!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719158614733-top-10-gaming-treasures-all-fun-and-free-no-ad-interrucion/"><u>Top 10 Gaming Treasures - All Fun and Free, No Ad Interrución!</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-a-concierge-guide-for-monitoring-facebook-livestreams/"><u>[Updated] 2024 Approved  A Concierge Guide for Monitoring Facebook Livestreams</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162665089-upgrade-for-peace-of-mind-new-nvidia-drivers-available/"><u>Upgrade for Peace of Mind – New NVIDIA Drivers Available.</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-any-realme-c33-2023-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Realme C33 2023 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://games-able.techidaily.com/1719165694207-the-history-and-evolution-of-street-mapping-techniques-and-tools/"><u>The History and Evolution of Street Mapping Techniques and Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161930368-steam-unlocked-discovering-top-notch-games-for-free/"><u>Steam Unlocked: Discovering Top-Notch Games for FREE!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161005802-conquer-nyts-latest-word-obsession-mastery-of-strands-awaits/"><u>Conquer NYT's Latest Word Obsession: Mastery of 'Strands' Awaits</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164100375-why-a-dedicated-oled-for-your-games-wins-every-time/"><u>Why a Dedicated OLED for Your Games Wins Every Time</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pro-level-text-wonders-discover-the-top-10-for-videos/"><u>[New] Pro-Level Text Wonders - Discover the Top 10 for Videos</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-realme-11-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163015057-ios-enthusiasts-4-best-gbadvance-emulator-choices/"><u>IOS Enthusiasts: 4 Best GBAdvance Emulator Choices</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-perceiving-beyond-understanding-ars-impact/"><u>[New] Perceiving Beyond  Understanding AR's Impact</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-integrating-spotify-and-discord-a-complete-guide/"><u>In 2024, Integrating Spotify & Discord  A Complete Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160472458-explore-ioss-finest-gba-emulation-tools/"><u>Explore iOS's Finest GBA Emulation Tools!</u></a></li>
<li><a href="https://games-able.techidaily.com/5-ways-to-play-your-favorite-games-on-a-mac/"><u>5 Ways to Play Your Favorite Games on a Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163288986-unlock-footballs-secrets-fc-manager-game-free-edition/"><u>Unlock Football's Secrets: FC Manager Game, Free Edition!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161758026-the-unparalleled-benefits-of-2-years-with-an-oled-monitor/"><u>The Unparalleled Benefits of 2 Years with an OLED Monitor!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161014715-unveiling-top-6-gamified-chatgpt-experiences/"><u>Unveiling: Top 6 Gamified ChatGPT Experiences</u></a></li>
<li><a href="https://games-able.techidaily.com/10-screensaver-secrets-what-not-to-do-when-shop-ping-a-monitor/"><u>10 Screensaver Secrets: What Not To Do When Shop-Ping a Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/1719165682129-discover-the-greatest-online-fps-browser-gaming-experiences/"><u>Discover the Greatest Online FPS Browser Gaming Experiences</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166175522-eliminate-glitches-with-the-latest-nvidia-graphics-update/"><u>Eliminate Glitches with the Latest Nvidia Graphics Update.</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160543511-early-access-wins-get-marvels-spider-man-2-on-ps5-now/"><u>Early Access Wins - Get Marvel’s Spider-Man 2 on PS5 Now!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-17-best-background-remover-apps-to-remove-image-background-easily/"><u>2024 Approved  17 Best Background Remover Apps to Remove Image Background Easily</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162480304-the-most-reliable-ios-gaming-tools-ranked-find-out-now/"><u>The Most Reliable iOS Gaming Tools Ranked: Find Out Now</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-understanding-the-edge-of-av1-in-video-encoding/"><u>[Updated] Understanding the Edge of AV1 in Video Encoding</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-era-of-gaming-ps5-or-xbox-series-x/"><u>A New Era of Gaming: PS5 or Xbox Series X?</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162743652-bring-your-childhood-back-ios-and-psp-games/"><u>Bring Your Childhood Back: IOS & PSP Games!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164936464-the-importance-of-accessibility-and-inclusivity-in-map-design-including-the-use-of-tactile-maps-and-braille-labels/"><u>The Importance of Accessibility and Inclusivity in Map Design, Including the Use of Tactile Maps and Braille Labels</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-mastering-the-art-of-evading-youtube-copyright-claims/"><u>In 2024, Mastering the Art of Evading YouTube Copyright Claims</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163779461-how-different-cultures-have-developed-unique-approaches-to-map-design-and-symbolization/"><u>How Different Cultures Have Developed Unique Approaches to Map Design and Symbolization;</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160580017-craftsmads-and-fun-try-larger-arcade-cabinet-framing/"><u>Craftsmads and Fun: Try Larger Arcade Cabinet Framing</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-to-other-iphone-13-pro-max-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 11 to other iPhone 13 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719165756739-discover-sonys-best-deals-summer-edition/"><u>Discover Sony's Best Deals: Summer Edition!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164655300-principles-for-creating-effective-directional-symbols-that-are-universally-understood/"><u>Principles for Creating Effective Directional Symbols that Are Universally Understood</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-apple-id-verification-code-not-working-from-apple-iphone-15-pro-max-by-drfone-ios/"><u>How To Fix Apple ID Verification Code Not Working From Apple iPhone 15 Pro Max</u></a></li>
<li><a href="https://games-able.techidaily.com/13-fun-games-to-improve-your-creative-design-skills/"><u>13 Fun Games to Improve Your Creative Design Skills</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164851824-champions-blueprint-managing-soccer-legends-at-no-cost/"><u>Champion's Blueprint: Managing Soccer Legends at No Cost</u></a></li>
</ul></div>

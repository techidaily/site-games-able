---
title: Decoding DXVK and Its Benefits for WinGaming Enthusiasts
date: 2024-07-12T03:49:38.162Z
updated: 2024-07-13T03:49:38.162Z
tags:
  - games
categories:
  - games
description: This Article Describes Decoding DXVK and Its Benefits for WinGaming Enthusiasts
excerpt: This Article Describes Decoding DXVK and Its Benefits for WinGaming Enthusiasts
keywords: DXVK,WinGaming Optimization,Open Source Video Decoder,Vulkan API for Gaming,DXVA Driver Alternative,Efficient Graphics Rendering in Windows,Gaming Performance Enhancement with DXVK
thumbnail: https://thmb.techidaily.com/6b564cfcc68d7fa9fa2ebcc8ac34b00c6e2d610d2ee82b6185002beb469144e3.jpg
---

## Decoding DXVK and Its Benefits for WinGaming Enthusiasts

 Direct3D has been a part of Windows gaming for decades, unifying the segmented PC hardware landscape under one 3D-enabled umbrella. However, an app created primarily for Linux, DXVK, is sometimes a much better option to use, even if you're on Windows.

 Would you like better compatibility and, more importantly, performance for your apps and games? Then you need to try out DXVK.

## The Problem With DirectX on Windows

 Microsoft created DirectX as a "unified solution" that helped programmers use any PC's hardware capabilities. Instead of writing different code for each hardware part, software developers could "target" DirectX's DirectDraw (2D graphics), Direct3D (hardware-accelerated 3D), and DirectSound (audio) libraries. Then, let Microsoft's solution "translate" their code to "the native language" of each hardware part.

 DirectX became an irreplaceable core technology in Windows and has been evolving since. However, there's a small catch with Direct3D: it's not 100% backward compatible.

 Microsoft, and the creators of GPUs that support the Direct3D API (as in "Nvidia, AMD, and Intel"), have occasionally dropped support for features introduced in past versions of Direct3D but which never gained traction. Thus, some older games might fail to run correctly on a modern GPU with the newest versions of Direct3D.

## What Is Vulkan?

 Supposedly a more "open" answer to Microsoft's closed-source Direct3D, OpenGL was a mutated version of the 3D graphics libraries used in Silicon Graphics' graphics workstations.

 OpenGL, though, always lagged, feature-wise, compared to Microsoft's Direct3D. Eventually, it seemed more rational to reboot the effort. That's why Vulkan, also known as "OpenGL Next", was created, offering better performance and increased control over hardware.

 Like OpenGL, and unlike Microsoft's Windows-bound Direct3D, Vulkan is "open" and cross-platform. You can use Vulkan on Windows, Linux, and even smartphones. Although not natively supported on Macs, it's usable there through MoltenVK.

 That was the short version. To learn more about Vulkan, check our article on [what Vulkan run time libraries are in Windows](https://www.makeuseof.com/tag/vulkan-run-time-libraries-windows/) .

## What Is DXVK?

 DXVK is a wrapper, "translating" Direct3D to Vulkan. In the human world, a translator can be a mediator between an English and a Japanese speaker, enabling them to understand one another. Similarly, "wrappers", or "translation layers", can "take" code written for a specific piece of hardware, platform, or API, and translate it to run on another.

 DXVK was originally developed for Linux with support from Valve, which also uses it on SteamOS and the Steam Deck. You can learn more about that in our article where we saw [what is Steam Proton and how it runs Windows games on Steam Deck](https://www.makeuseof.com/what-is-steam-proton-how-does-it-run-windows-games-on-steam-deck/) .

## Why Should You Use DXVK on Windows?

 If a game already runs fine on your hardware, there's no reason to use DXVK. But some games written for older versions of DirectX don't run "correctly" (if at all) on newer versions of DirectX and modern hardware.

 By "translating" old-and-buggy Direct3D code into the more modern Vulkan API, there's a minimal toll on performance (if any). At the same time, problematic games with broken graphics or missing features may become fully playable again.

 Since Vulkan is on par with Direct3D 12, and both are much better (and faster) than older versions of Direct3D (as we saw when [we compared DirectX 11 VS DirectX 12](https://www.makeuseof.com/directx-11-vs-directx-12-differences/) ), "translating" old Direct3D games to Vulkan can sometimes improve the game's performance.

 Intel's work on their Arc GPUs is proof of that. Intel could try to add support for every single older title in Arc GPU drivers. Instead, Intel decided to work on further improving DXVK. Initial results from Intel's "experiment" lead up to a 2x boost in performance for older titles, with dozens rendered playable "through" DXVK.

## How to Use DXVK on Windows

 Using DXVK on Windows is easy, since there is nothing to tweak or configure. You only have to download it, extract it into a game's correct folder, and it's ready to go.

 However, you have to use the correct DXVK version that matches the Direct3D version used by your game.

 It's probably easier if we go through the whole process together to see how you can download the latest version of DXVK, identify your game's "tech", and install the correct DLLs in the proper folder.

### How to Download DXVK

 DXVK is open-source software and free to use. You can find its latest version on GitHub.

1. Visit DXVK's [official GitHub page](https://GitHub.com/doitsujin/dxvk) and click on the**Latest** version link on the right of the page, under**Releases** .
2. Scroll down on the releases page and find the**Assets** section of the latest version. Click on the latest DXVK tar.gz archive to download it. At the time of writing, it was version 2.2.  
![DXVK Latest Release Asset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-latest-release-asset-1.jpg)
3. Store the downloaded archive somewhere, for you will need to extract its contents to the folder of every game you want to run with DXVK instead of Direct3D.

### How to Choose the Correct DXVK Version

 If you need to know which version of Direct3D your game is using, the PC Gaming Wiki website can help.

1. Visit [PC Gaming Wiki](https://pcgamingwiki.com/) with your browser, and use the search field on the top right to seek the game to which you want to add DXVK.
2. When you find your game, visit its page and scroll down to reach the**Other Information** section. Turn your attention to the API tables. There, on the**Technical Specs** and**Supported** columns, you will see the version of Direct3D your game is using. Underneath, the**Executable** ,**32-bit** , and**64-bit** columns will "tell" you which architecture you should choose.  
![PCGamingWiki Game API Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/pcgamingwiki-game-api-information-1.jpg)

### How to Add DXVK to Your Games

 Now that you know which Direct3D version and CPU architecture your game uses, you can add the correct version of DXVK to its folder.

1. Open the DXVK archive with your favorite archive manager (for this article, we're using WinRAR), and enter the single DXVK folder you'll see there.  
![DXVK Folder Within Archive 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-folder-within-archive-1.jpg)
2. Inside, you'll find two subfolders, one for each computer architecture. Enter the correct one for your game. Even if your OS is 64-bit, like most versions of Windows today, if your game is 32-bit, you should go for the 32-bit folder.  
![DXVK 32 bit and 64 bit folders within archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-32-bit-and-64-bit-folders-within-archive-1.jpg)
3. Select the**DXGI.DLL** plus the correct DLL for the version of**Direct3D** your game is using. As you will see, there are three more DLLs, one for each of the previous versions of Direct3D: 9, 10, and 11.  
![DXVK DLLs Within Archive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-dlls-within-archive-1.jpg)
4. Find the local folder where your game is installed and locate the subfolder with its executable ("the file from which the game runs"). Extract the DLLs from the previous step to this folder.  
![Extracting DXVK DLLs To Game Directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/extracting-dxvk-dlls-to-game-directory-1.jpg)

### How to Test and Benchmark Your Enhanced Game

 If you run your game now, it should use Vulkan instead of Direct3D and hopefully perform better.

 Even if you don't see any dramatic changes in frame rates, sometimes the improvements can be "felt" in other ways. For example, we tried DXVK with the classic Batman: Arkham City on a PC equipped with a Ryzen 5900x, 64GBs of RAM, and an Nvidia RTX 3070 GPU. Our hardware was already over this old game's top specs, achieving very high frame rates. Even if they got higher with Vulkan, the difference wouldn't be easily perceivable.

![Arkham-City-Instant-Transitions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/arkham-city-instant-transitions.jpg)

 However, the game's action felt smoother. Transitions between screens, loading levels, and pressing Alt + Tab were almost instant with DXVK.

## When You Should Not Use DXVK

 DXVK has many benefits and can bring the performance of older games into the modern era. Despite this, it's not a silver bullet for improved performance, and sometimes it's just not worth using it.

### 1\. DXVK Doesn't Improve the Game's Performance

 If you've added the DXVK DLLs to your game but saw no difference afterward, you can remove them again if you like. You can delete the DLLs you've added to a game's folder to do that.

### 2\. DXVK Causes Worse Performance or Introduces New Glitches

 Sometimes adding DXVK to a game might have the opposite effect. Unfortunately, there's no way for an end user to fix such issues.

 Did a game's performance tank or visual glitches appear after adding DXVK? Exit the game and delete the DXVK's DLLs from its directory.

### 3\. You Want to Play Your Game Online

 DXVK is a compatibility layer and only affects the graphic output of a game. Still, some companies are against any modification of their games to ensure a fair environment for everyone.

 DXVK might not be "cheating", but it's still a "game modification", and could get flagged as such.

### 4\. The Game Already Has Built-In Vulkan Support

 If a game already uses the Vulkan API, like Doom Eternal, there's no reason to set its output to Direct3D to then translate it to Vulkan.

### 5\. The Game Uses Direct3D 12

 Since Direct3D 12 is almost fully on par with Vulkan, there's nothing to gain by translating one ultra-modern graphics API to another one.

## Enhance Your Old Games With "Translated" 3D on Windows

 What started as a way to play more Windows-bound games on Linux, ended up becoming a useful compatibility solution and performance booster. So, keep a recent archive of DXVK's DLLs handy. Add them to any game where you'd like to eliminate glitches, improve its performance, get smoother in-game action, and improve its responsiveness.

 Even if it doesn't end up helping, trying it out will only take seconds, and more often than not, you might be surprised by the results.


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
<li><a href="https://desktop-recording.techidaily.com/new-iconic-building-blueprints-for-mc-players-for-2024/"><u>[New] Iconic Building Blueprints for MC Players for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-tweet-time-machine-capturing-the-essence-of-twitters-videos/"><u>[New] Tweet Time Machine  Capturing the Essence of Twitter's Videos</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-step-by-step-guide-to-rearranging-youtube-playlists/"><u>In 2024, Step-by-Step Guide to Rearranging YouTube Playlists</u></a></li>
<li><a href="https://games-able.techidaily.com/2-year-tale-why-i-prefer-an-oled-monitor/"><u>2-Year Tale: Why I Prefer an OLED Monitor</u></a></li>
<li><a href="https://techidaily.com/complete-guide-to-hard-reset-your-oneplus-ace-2-pro-drfone-by-drfone-reset-android-reset-android/"><u>Complete Guide to Hard Reset Your OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173054768-top-10-ad-free-and-no-cost-mobile-gaming-hits/"><u>Top 10 Ad-Free & No-Cost Mobile Gaming Hits!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-unveiling-instagram-reels-10-surprising-insights/"><u>[New] In 2024, Unveiling Instagram Reels  10 Surprising Insights</u></a></li>
<li><a href="https://extra-information.techidaily.com/digital-paintbrushes-at-your-fingertips-explore-11-color-correction-essentials/"><u>Digital Paintbrushes at Your Fingertips  Explore 11 Color Correction Essentials</u></a></li>
<li><a href="https://games-able.techidaily.com/a-guide-to-adding-memory-expansion-in-steam-deck/"><u>A Guide to Adding Memory Expansion in Steam Deck</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-y100t-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo Y100t Quickly | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Sony Xperia 1 V? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlock-hand-tracker-potential-guide/"><u>In 2024, Unlock Hand Tracker Potential Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-guide-to-old-hollywood-filmmaking-styles/"><u>[New] Step-by-Step Guide to Old Hollywood Filmmaking Styles</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-windows-1011-oculus-not-responding/"><u>Addressing Windows 10/11: Oculus Not Responding</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169060145-classic-console-play-on-your-modern-device/"><u>Classic Console Play on Your Modern Device</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-asus-rog-phone-7-ultimate-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Asus ROG Phone 7 Ultimate’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://games-able.techidaily.com/450plus-high-speed-budget-friendly-screen/"><u>$450+ High-Speed, Budget-Friendly Screen</u></a></li>
<li><a href="https://games-able.techidaily.com/6-unconventional-gaming-techniques-for-ps5/"><u>6 Unconventional Gaming Techniques for PS5</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-optimal-techniques-to-record-your-snapchat-stories-for-2024/"><u>[New] Optimal Techniques to Record Your Snapchat Stories for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/ace-the-online-setup-for-switch-games/"><u>Ace the Online Setup for Switch Games</u></a></li>
<li><a href="https://games-able.techidaily.com/a-buyers-guide-to-steam-decks/"><u>A Buyer's Guide to Steam Decks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-infinix-smart-8-hd-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Infinix Smart 8 HD to Roku | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/achieving-vip-levels-buying-v-bucks-on-ps5/"><u>Achieving VIP Levels: Buying V-Bucks on PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168178529-top-4-ios-game-boy-advance-portals-to-classic-worlds/"><u>Top 4 iOS Game Boy Advance Portals to Classic Worlds!</u></a></li>
<li><a href="https://games-able.techidaily.com/4-essential-steps-for-amplifying-xbox-point-advantages/"><u>4 Essential Steps for Amplifying Xbox Point Advantages</u></a></li>
<li><a href="https://games-able.techidaily.com/22-quick-web-games-to-play-online-when-youre-bored/"><u>22 Quick Web Games to Play Online When You're Bored</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reconfigure-display-mode-in-win10/"><u>Reconfigure Display Mode in Win10</u></a></li>
<li><a href="https://games-able.techidaily.com/a-review-that-reveals-beyerdynamic-mmx-200-strengths/"><u>A Review that Reveals Beyerdynamic MMX 200 Strengths</u></a></li>
<li><a href="https://games-able.techidaily.com/1719167954992-stop-computer-glitches-update-your-nvidia-driver/"><u>Stop Computer Glitches: Update Your Nvidia Driver.</u></a></li>
<li><a href="https://games-able.techidaily.com/8-ar-mobile-games-that-will-get-you-moving-outdoors/"><u>8 AR Mobile Games That Will Get You Moving Outdoors</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-xbox-controller-jerkiness-and-drifting/"><u>Addressing Xbox Controller Jerkiness and Drifting</u></a></li>
<li><a href="https://win11.techidaily.com/breath-of-fresh-air-reviving-outdated-microsoft-store-apps/"><u>Breath of Fresh Air: Reviving Outdated Microsoft Store Apps</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-discover-the-best-3d-animation-makers-for-stunning-videos/"><u>Updated 2024 Approved Discover the Best 3D Animation Makers for Stunning Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169318737-revolutionize-game-boy-handhents-on-your-mobile-device/"><u>Revolutionize Game Boy Handhents on Your Mobile Device!</u></a></li>
<li><a href="https://games-able.techidaily.com/8-ways-to-boost-the-performance-of-your-ps4/"><u>8 Ways to Boost the Performance of Your PS4</u></a></li>
<li><a href="https://extra-information.techidaily.com/inside-the-immersive-evolution-vrs-present-state-and-foreseen-obstacles/"><u>Inside the Immersive Evolution  VR's Present State and Foreseen Obstacles</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169754120-why-hold-off-on-your-next-ps5-discover-here/"><u>Why Hold Off on Your Next PS5? Discover Here</u></a></li>
<li><a href="https://games-able.techidaily.com/7-tips-for-preventing-big-picture-crashes/"><u>7 Tips for Preventing Big Picture Crashes</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/anniversary-1500-free-daily-knowledge-shares/"><u>Anniversary: 1,500 Free Daily Knowledge Shares</u></a></li>
<li><a href="https://screen-capture.techidaily.com/essential-tips-for-high-quality-discord-recordings/"><u>Essential Tips for High-Quality Discord Recordings</u></a></li>
<li><a href="https://games-able.techidaily.com/3-powerful-money-management-tips-for-xbox-players/"><u>3 Powerful Money Management Tips for Xbox Players</u></a></li>
<li><a href="https://games-able.techidaily.com/a-passionate-pursuit-uncovering-stunning-indie-titles/"><u>A Passionate Pursuit: Uncovering Stunning Indie Titles</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-art-of-incorporating-s2t-features-into-ppt/"><u>In 2024, The Art of Incorporating S2T Features Into PPT</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-vidma-screen-capture-a-thorough-examination-and-alternative-options/"><u>[Updated] Vidma Screen Capture - A Thorough Examination & Alternative Options</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/top-10-educator-approved-video-capture-apps/"><u>Top 10 Educator-Approved Video Capture Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/a-cooling-lesson-learned-graphics-failure/"><u>A Cooling Lesson Learned: Graphics Failure</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-top-10-video-screenshot-tools-reviewed/"><u>[Updated] In 2024, Top 10 Video Screenshot Tools Reviewed</u></a></li>
<li><a href="https://games-able.techidaily.com/2024s-most-stylish-and-functional-switch-accessories/"><u>2024'S Most Stylish and Functional Switch Accessories</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169753046-guide-enjoy-xbox-games-anyhow/"><u>Guide: Enjoy Xbox Games Anyhow!</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-and-dailymotion-unveiling-core-variations/"><u>2024 Approved  YouTube & Dailymotion  Unveiling Core Variations</u></a></li>
</ul></div>

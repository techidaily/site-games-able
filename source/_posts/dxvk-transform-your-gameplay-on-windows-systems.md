---
title: "DXVK: Transform Your Gameplay on Windows Systems"
date: 2024-07-12T03:40:30.698Z
updated: 2024-07-13T03:40:30.698Z
tags:
  - games
categories:
  - games
description: "This Article Describes DXVK: Transform Your Gameplay on Windows Systems"
excerpt: "This Article Describes DXVK: Transform Your Gameplay on Windows Systems"
keywords: DXVK Wrapper,Windows Gaming Performance,XNA Game Studio for Windows 10,Windows-Linux Gaming Bridge,DVDXK Overclocking Features,Linux to Windows Game Converter,Optimized Gaming Interface (OGI) Compatible with DXVK
thumbnail: https://thmb.techidaily.com/9929e26ad232462fb3012e528ec110b36cc8e34a7ab835cf659d05f21b4127d5.jpg
---

## DXVK: Transform Your Gameplay on Windows Systems

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
<li><a href="https://extra-support.techidaily.com/in-2024-navigating-new-realities-metaverse-meets-omniverse/"><u>In 2024, Navigating New Realities  Metaverse Meets Omniverse</u></a></li>
<li><a href="https://games-able.techidaily.com/managing-roblox-data-consumption-on-iphones/"><u>Managing Roblox Data Consumption on iPhones</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-harmonious-beginnings-inclusive-vocal-modification-software-options-for-novices-and-pros/"><u>Updated In 2024, Harmonious Beginnings Inclusive Vocal Modification Software Options for Novices & Pros</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-audio-capture-and-critical-examination/"><u>[New] 2024 Approved  Audio Capture & Critical Examination</u></a></li>
<li><a href="https://games-able.techidaily.com/reducing-risks-dont-tap-into-ps5s-microphone/"><u>Reducing Risks: Don't Tap Into PS5's Microphone</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-for-reconnecting-joy-cons-to-switch-system/"><u>Steps for Reconnecting Joy-Cons to Switch System</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-error-0x803f8001-on-minecraft-for-windows-pcs/"><u>Resolving Error 0X803F8001 on Minecraft for Windows PCs</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/speed-updown-videos-in-vlc/"><u>Speed Up/Down Videos in VLC</u></a></li>
<li><a href="https://games-able.techidaily.com/mending-the-inconsistencies-of-steams-data-exchange/"><u>Mending the Inconsistencies of Steam's Data Exchange</u></a></li>
<li><a href="https://games-able.techidaily.com/invest-in-fun-top-5-motivations-to-purchase-mobile-games/"><u>Invest in Fun: Top 5 Motivations to Purchase Mobile Games</u></a></li>
<li><a href="https://games-able.techidaily.com/switch-out-for-peak-performance/"><u>Switch Out for Peak Performance?</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-usb-hubs-tailored-for-playstation-5/"><u>Superior USB Hubs, Tailored for PlayStation 5</u></a></li>
<li><a href="https://games-able.techidaily.com/insider-advice-on-digital-xbox-seriess-returns/"><u>Insider Advice on Digital Xbox Series/S Returns</u></a></li>
<li><a href="https://games-able.techidaily.com/streams-money-back-promise-executing-a-perfect-refund/"><u>Stream's Money-Back Promise: Executing a Perfect Refund</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-full-console-experience-integrating-controllers-with-androids/"><u>Unlock Full Console Experience: Integrating Controllers with Androids</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-unlock-pro-quality-sound-top-10-audio-editing-software-tools-for-2024/"><u>New Unlock Pro-Quality Sound Top 10 Audio Editing Software Tools for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/dynamic-volume-interplay-using-sony-vegas-pro-tips/"><u>Dynamic Volume Interplay Using Sony Vegas Pro Tips</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tips-for-a-smooth-transition-into-vr-worlds/"><u>Tips for a Smooth Transition Into VR Worlds</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-captivating-displays-for-expert-image-processors-2024-guide/"><u>[Updated] Captivating Displays for Expert Image Processors, 2024 Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/why-serious-games-resist-the-allure-of-gamefi/"><u>Why Serious Games Resist the Allure of GameFi</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-gaming-analysis-on-steam-platform/"><u>Maximizing Gaming Analysis on Steam Platform</u></a></li>
<li><a href="https://games-able.techidaily.com/is-rtx-immediate-replacement-after-gtx-discontinuation/"><u>Is RTX Immediate Replacement After GTX Discontinuation?</u></a></li>
<li><a href="https://games-able.techidaily.com/the-pathway-to-pristine-gameplay-with-your-xbox-series-xs-high-res-mode/"><u>The Pathway to Pristine Gameplay with Your Xbox Series X's High Res Mode</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/top-5-realme-c55-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>Top 5 Realme C55 Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-wi-fi-refresh-on-sonys-dualsense/"><u>Mastering Wi-Fi Refresh on Sony's DualSense</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-best-practices-in-youtube-keyword-selection/"><u>2024 Approved  Best Practices in YouTube Keyword Selection</u></a></li>
<li><a href="https://games-able.techidaily.com/slowdown-simplicity-discover-idles/"><u>Slowdown Simplicity: Discover Idles</u></a></li>
<li><a href="https://games-able.techidaily.com/keep-your-playstation-fresh-remove-reinstall-games/"><u>Keep Your PlayStation Fresh: Remove, Reinstall Games</u></a></li>
<li><a href="https://games-able.techidaily.com/versatile-techniques-for-steam-revival/"><u>Versatile Techniques for Steam Revival</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-enhance-engagement-top-12-tactics-for-youtube-success-for-2024/"><u>[Updated] Enhance Engagement  Top 12 Tactics for YouTube Success for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/retro-controller-enhancing-classic-games/"><u>Retro Controller: Enhancing Classic Games</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-oppo-reno-8t-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Oppo Reno 8T 5G</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-palworld-essentials/"><u>Unlocking PalWorld Essentials</u></a></li>
<li><a href="https://games-able.techidaily.com/preventing-xbox-controller-gaming-malfunctions/"><u>Preventing Xbox Controller Gaming Malfunctions</u></a></li>
<li><a href="https://games-able.techidaily.com/win1111s-dxgierror-0x887a0006-resolution-guide/"><u>Win11/11's DXGI_ERROR 0X887A0006 Resolution Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/rolling-older-xbox-controllers-settings-forward/"><u>Rolling Older Xbox Controllers Settings Forward</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-delete-icloud-account-with-or-without-password-from-your-apple-iphone-15-prowindowsmac-by-drfone-ios/"><u>How to Delete iCloud Account with or without Password from your Apple iPhone 15 Pro/Windows/Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-earning-early-starfield-access-credits/"><u>Tips for Earning Early Starfield Access Credits</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/immersive-image-editing-online-cropping-essentials-for-2024/"><u>Immersive Image Editing  Online Cropping Essentials for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-tech-ultimate-gaming-mouse/"><u>Superior Tech, Ultimate Gaming Mouse</u></a></li>
<li><a href="https://games-able.techidaily.com/name-that-tune-the-8-best-mobile-music-trivia-games/"><u>Name That Tune! The 8 Best Mobile Music Trivia Games</u></a></li>
<li><a href="https://games-able.techidaily.com/pinnacle-headphones-for-switch-gamers/"><u>Pinnacle Headphones for Switch Gamers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-adding-media-instagrams-guide/"><u>2024 Approved  Adding Media  Instagram's Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/top-7-fps-configurations-for-optimal-play/"><u>Top 7 FPS Configurations for Optimal Play</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-fixing-roblox-error-code-403-on-windows-systems/"><u>Mastering the Art of Fixing Roblox Error Code 403 on Windows Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/navigate-the-digital-labyrinths-with-us/"><u>Navigate the Digital Labyrinths with Us!</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-windows-steams-bp-dilemmas/"><u>Overcoming Windows-Steam's BP Dilemmas</u></a></li>
<li><a href="https://games-able.techidaily.com/the-powerful-advantages-of-using-an-oled-screen-for-2-years/"><u>The Powerful Advantages of Using an OLED Screen for 2 Years</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionizing-tech-ai-innovations-at-computex/"><u>Revolutionizing Tech: AI Innovations at Computex</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-steam-deck-model-potentials/"><u>Unlocking Steam Deck Model Potentials</u></a></li>
<li><a href="https://games-able.techidaily.com/vintagevault-mini-retro-fun-fit-for-the-handheled/"><u>VintageVault Mini: Retro Fun Fit for the Handheled</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/bridging-app-dimensions-with-youtube-shorts/"><u>Bridging App Dimensions with YouTube Shorts</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-2024-approved-descript-ai-voice-enhancing-your-content-through-voice-replication/"><u>New 2024 Approved Descript AI Voice Enhancing Your Content Through Voice Replication</u></a></li>
<li><a href="https://games-able.techidaily.com/spark-innovation-with-these-9-themed-gaming-sessions/"><u>Spark Innovation with These 9 Themed Gaming Sessions</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-step-by-step-tutorial-crafting-photo-videos-in-pixiz/"><u>2024 Approved  Step-by-Step Tutorial  Crafting Photo Videos in Pixiz</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-enhance-igtv-engagement-with-diverse-subtitle-options/"><u>[Updated] Enhance IGTV Engagement with Diverse Subtitle Options</u></a></li>
</ul></div>

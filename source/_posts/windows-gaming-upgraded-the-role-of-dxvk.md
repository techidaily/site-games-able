---
title: "Windows Gaming Upgraded: The Role of DXVK"
date: 2024-07-12T03:22:43.542Z
updated: 2024-07-13T03:22:43.542Z
tags:
  - games
categories:
  - games
description: "This Article Describes Windows Gaming Upgraded: The Role of DXVK"
excerpt: "This Article Describes Windows Gaming Upgraded: The Role of DXVK"
keywords: Windows Gaming Performance Enhancement,DXVK Xbox Game Emulation,Linux to Windows Gaming Conversion,Cross-Platform Games with DXVK,Optimizing Gaming on Windows Using DXVK,High Fidelity Gaming on Windows,DXVK for Improved Xbox Gameplay
thumbnail: https://thmb.techidaily.com/01edaba53137429381532b08b94562d4a741359e1c28374d3f1b3c538848d74c.jpg
---

## Windows Gaming Upgraded: The Role of DXVK

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
<li><a href="https://games-able.techidaily.com/tactical-tuning-for-triumphant-fps-engagements/"><u>Tactical Tuning for Triumphant FPS Engagements</u></a></li>
<li><a href="https://games-able.techidaily.com/the-upside-of-staggered-game-drops/"><u>The Upside of Staggered Game Drops</u></a></li>
<li><a href="https://games-able.techidaily.com/dispelling-the-incompatibility-with-steam-files/"><u>Dispelling the Incompatibility with Steam Files</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-streamlining-steam-decks-cloud-function/"><u>Strategies for Streamlining Steam Deck’s Cloud Function</u></a></li>
<li><a href="https://games-able.techidaily.com/expert-strategies-for-managing-nintendo-console-logins/"><u>Expert Strategies for Managing Nintendo Console Logins</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-best-practices-8-steps-for-digital-sound-preservation-for-2024/"><u>[Updated] Best Practices  8 Steps for Digital Sound Preservation for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/game-changing-motherboards-at-reasonable-prices/"><u>Game-Changing Motherboards at Reasonable Prices</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-steam-data-coordination-errors/"><u>Resolving Steam Data Coordination Errors</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/avoiding-pitfalls-smart-strategies-for-acquiring-youtubes-for-2024/"><u>Avoiding Pitfalls  Smart Strategies for Acquiring Youtubes for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-unlock-your-creative-flow-sharing-hundreds-of-photos-and-vids-on-ig/"><u>2024 Approved  Unlock Your Creative Flow  Sharing Hundreds of Photos and Vids on IG</u></a></li>
<li><a href="https://games-able.techidaily.com/supercharge-your-gaming-system-with-ease/"><u>Supercharge Your Gaming System with Ease</u></a></li>
<li><a href="https://games-able.techidaily.com/master-the-art-of-nintendo-switch-area-switching/"><u>Master the Art of Nintendo Switch Area-Switching</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-digital-discovery-twitters-highest-viewed-video-hits/"><u>[New] 2024 Approved  Digital Discovery  Twitter's Highest-Viewed Video Hits</u></a></li>
<li><a href="https://games-able.techidaily.com/oled-gaming-monitors-my-2-year-experience/"><u>OLED Gaming Monitors: My 2-Year Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-experience-google-play-games-on-pc/"><u>How to Experience Google Play Games on PC</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-reversing-tiktok-videos-made-easy-a-step-by-step-tutorial-for-2024/"><u>New Reversing TikTok Videos Made Easy A Step-by-Step Tutorial for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/harmonizing-playstation-5-memberships-for-efficiency/"><u>Harmonizing PlayStation 5 Memberships for Efficiency</u></a></li>
<li><a href="https://games-able.techidaily.com/restoring-missing-gps-on-your-pokemon-journey/"><u>Restoring Missing GPS on Your Pokémon Journey</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-discover-10-budget-friendly-cloud-collaboration-platforms/"><u>In 2024, Discover 10 Budget-Friendly Cloud Collaboration Platforms</u></a></li>
<li><a href="https://games-able.techidaily.com/supercharge-your-playtime-with-elite-tech/"><u>Supercharge Your Playtime with Elite Tech</u></a></li>
<li><a href="https://games-able.techidaily.com/protect-your-playthroughs-duplicating-steam-captures/"><u>Protect Your Playthroughs: Duplicating Steam Captures</u></a></li>
<li><a href="https://games-able.techidaily.com/invest-smart-with-economy-led-monitor/"><u>Invest Smart with Economy LED Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/optimizing-storage-steam-deck-and-sd-card/"><u>Optimizing Storage: Steam Deck and SD Card</u></a></li>
<li><a href="https://games-able.techidaily.com/energize-innovation-dreams-for-tomorrow/"><u>Energize Innovation: Dreams for Tomorrow</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-iphone-se-without-apple-password-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Reset iPhone SE Without Apple Password? | Stellar</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-game-changing-strategies-for-effective-video-capture/"><u>[New] 2024 Approved  Game-Changing Strategies for Effective Video Capture</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/is-my-friends-account-invisible-potential-block/"><u>Is My Friend's Account Invisible? Potential Block</u></a></li>
<li><a href="https://games-able.techidaily.com/efficient-methods-to-delete-past-games-data-on-ps5-console/"><u>Efficient Methods to Delete Past Games' Data on PS5 Console</u></a></li>
<li><a href="https://games-able.techidaily.com/remedy-error-0x887a0006-a-step-by-step-approach-to-fixing-dxgi-devices/"><u>Remedy Error 0X887A0006: A Step-by-Step Approach to Fixing DXGI Devices</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Apple iPhone 14 Plus? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-rectify-silence-or-distortion-in-xbox-audio/"><u>How to Rectify Silence or Distortion in Xbox Audio</u></a></li>
<li><a href="https://games-able.techidaily.com/discover-why-mics-are-off-limits-for-ps5s/"><u>Discover Why Mics Are Off-Limits for PS5s</u></a></li>
<li><a href="https://games-able.techidaily.com/field-day-fun-unveiling-the-top-7-sporting-games-iosandroid/"><u>Field Day Fun: Unveiling the Top 7 Sporting Games (iOS/Android)</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-console-ambiance-with-premium-lights/"><u>Maximize Your Console Ambiance with Premium Lights</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-what-are-facebook-reels-and-how-to-make/"><u>[New] What Are Facebook Reels and How to Make</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ad-free-pro-android-screenshot-suite-for-2024/"><u>[Updated] Ad-Free Pro Android Screenshot Suite for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-disconnect-patterns-for-xbox-players/"><u>Decoding Disconnect Patterns for Xbox Players</u></a></li>
<li><a href="https://games-able.techidaily.com/ephemeral-online-adventures-should-we-ponder-their-legacy/"><u>Ephemeral Online Adventures – Should We Ponder Their Legacy?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-the-8-best-zombie-games/"><u>2024 Approved  The 8 Best Zombie Games</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-get-started-with-mp4-video-editing-a-quick-and-easy-tutorial-for-mac-and-windows-for-2024/"><u>Updated Get Started with MP4 Video Editing A Quick and Easy Tutorial for Mac and Windows for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-process-joining-controllers-to-android-gadgets/"><u>Navigating the Process: Joining Controllers to Android Gadgets</u></a></li>
<li><a href="https://network-issues.techidaily.com/error-eradicated-mh-worlds-monster-kingdom-revived/"><u>Error Eradicated: MH World's Monster Kingdom Revived</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-care-steps-preserving-xbox-x-power/"><u>Essential Care Steps: Preserving Xbox X Power</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-fix-the-0x887a0006-dxgierrordevicehung-error-in-windows-11-and-11/"><u>How to Fix the 0X887A0006: DXGI_ERROR_DEVICE_HUNG Error in Windows 11 & 11</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-your-windows-steam-setup-with-bp-mode/"><u>Streamlining Your Windows-Steam Setup with BP Mode</u></a></li>
<li><a href="https://games-able.techidaily.com/decade-old-changes-valves-latest-steam-family-sharing-update/"><u>Decade-Old Changes: Valve’s Latest Steam Family Sharing Update</u></a></li>
<li><a href="https://games-able.techidaily.com/top-ranked-gba-ios-simulators-unveiled/"><u>Top-Ranked GBA iOS Simulators Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/redefining-player-value-4-pivotal-enhancements-for-xbox-rewards/"><u>Redefining Player Value: 4 Pivotal Enhancements for Xbox Rewards</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-the-quest-for-the-best-framerate-balancing-speed-and-clarity/"><u>[New] The Quest for the Best Framerate - Balancing Speed & Clarity</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-cancelling-steam-membership-monthly/"><u>Tips for Cancelling Steam Membership Monthly</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-dual-screen-playback-recording-for-2024/"><u>[New] Dual-Screen Playback Recording for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-htc-u23-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your HTC U23 FRP Locks</u></a></li>
<li><a href="https://games-able.techidaily.com/identifying-the-chasm-between-steam-and-gog-models/"><u>Identifying the Chasm Between Steam and GOG Models</u></a></li>
<li><a href="https://games-able.techidaily.com/retro-gaming-setup-oled-switch-with-vintage-power-source/"><u>Retro Gaming Setup: OLED Switch with Vintage Power Source</u></a></li>
<li><a href="https://games-able.techidaily.com/the-playful-pause-balancing-screen-time-and-life/"><u>The Playful Pause: Balancing Screen Time and Life</u></a></li>
</ul></div>

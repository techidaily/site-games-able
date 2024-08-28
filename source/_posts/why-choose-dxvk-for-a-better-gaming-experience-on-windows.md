---
title: Why Choose DXVK for a Better Gaming Experience on Windows
date: 2024-08-27T17:05:01.331Z
updated: 2024-08-28T17:05:01.331Z
tags:
  - games
categories:
  - games
description: This Article Describes Why Choose DXVK for a Better Gaming Experience on Windows
excerpt: This Article Describes Why Choose DXVK for a Better Gaming Experience on Windows
keywords: DXVK Optimization,Windows Gaming with DXVK,WineDX Improvements,Linux Gaming Alternatives,Enhanced Windows Games,Cross-Platform Gaming Tools,Gaming Performance Boosters for Windows
thumbnail: https://thmb.techidaily.com/bc6e0c08f36b012f885710643ac64bca838b2cd03d9601b077f3603bbf1a3a0e.jpg
---

## Why Choose DXVK for a Better Gaming Experience on Windows

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

 That was the short version. To learn more about Vulkan, check our article on[what Vulkan run time libraries are in Windows](https://www.makeuseof.com/tag/vulkan-run-time-libraries-windows/) .

## What Is DXVK?

 DXVK is a wrapper, "translating" Direct3D to Vulkan. In the human world, a translator can be a mediator between an English and a Japanese speaker, enabling them to understand one another. Similarly, "wrappers", or "translation layers", can "take" code written for a specific piece of hardware, platform, or API, and translate it to run on another.

 DXVK was originally developed for Linux with support from Valve, which also uses it on SteamOS and the Steam Deck. You can learn more about that in our article where we saw[what is Steam Proton and how it runs Windows games on Steam Deck](https://www.makeuseof.com/what-is-steam-proton-how-does-it-run-windows-games-on-steam-deck/) .

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
## Why Should You Use DXVK on Windows?

 If a game already runs fine on your hardware, there's no reason to use DXVK. But some games written for older versions of DirectX don't run "correctly" (if at all) on newer versions of DirectX and modern hardware.

 By "translating" old-and-buggy Direct3D code into the more modern Vulkan API, there's a minimal toll on performance (if any). At the same time, problematic games with broken graphics or missing features may become fully playable again.

 Since Vulkan is on par with Direct3D 12, and both are much better (and faster) than older versions of Direct3D (as we saw when[we compared DirectX 11 VS DirectX 12](https://www.makeuseof.com/directx-11-vs-directx-12-differences/) ), "translating" old Direct3D games to Vulkan can sometimes improve the game's performance.

 Intel's work on their Arc GPUs is proof of that. Intel could try to add support for every single older title in Arc GPU drivers. Instead, Intel decided to work on further improving DXVK. Initial results from Intel's "experiment" lead up to a 2x boost in performance for older titles, with dozens rendered playable "through" DXVK.

## How to Use DXVK on Windows

 Using DXVK on Windows is easy, since there is nothing to tweak or configure. You only have to download it, extract it into a game's correct folder, and it's ready to go.

 However, you have to use the correct DXVK version that matches the Direct3D version used by your game.

 It's probably easier if we go through the whole process together to see how you can download the latest version of DXVK, identify your game's "tech", and install the correct DLLs in the proper folder.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How to Download DXVK

 DXVK is open-source software and free to use. You can find its latest version on GitHub.

1. Visit DXVK's[official GitHub page](https://GitHub.com/doitsujin/dxvk) and click on the**Latest** version link on the right of the page, under**Releases** .
2. Scroll down on the releases page and find the**Assets** section of the latest version. Click on the latest DXVK tar.gz archive to download it. At the time of writing, it was version 2.2.  
![DXVK Latest Release Asset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dxvk-latest-release-asset-1.jpg)
3. Store the downloaded archive somewhere, for you will need to extract its contents to the folder of every game you want to run with DXVK instead of Direct3D.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->

### How to Choose the Correct DXVK Version

 If you need to know which version of Direct3D your game is using, the PC Gaming Wiki website can help.

1. Visit[PC Gaming Wiki](https://pcgamingwiki.com/) with your browser, and use the search field on the top right to seek the game to which you want to add DXVK.
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
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![Extracting DXVK DLLs To Game Directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/extracting-dxvk-dlls-to-game-directory-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
### How to Test and Benchmark Your Enhanced Game

 If you run your game now, it should use Vulkan instead of Direct3D and hopefully perform better.

 Even if you don't see any dramatic changes in frame rates, sometimes the improvements can be "felt" in other ways. For example, we tried DXVK with the classic Batman: Arkham City on a PC equipped with a Ryzen 5900x, 64GBs of RAM, and an Nvidia RTX 3070 GPU. Our hardware was already over this old game's top specs, achieving very high frame rates. Even if they got higher with Vulkan, the difference wouldn't be easily perceivable.

![Arkham-City-Instant-Transitions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/arkham-city-instant-transitions.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 However, the game's action felt smoother. Transitions between screens, loading levels, and pressing Alt + Tab were almost instant with DXVK.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## When You Should Not Use DXVK

 DXVK has many benefits and can bring the performance of older games into the modern era. Despite this, it's not a silver bullet for improved performance, and sometimes it's just not worth using it.

### 1\. DXVK Doesn't Improve the Game's Performance

 If you've added the DXVK DLLs to your game but saw no difference afterward, you can remove them again if you like. You can delete the DLLs you've added to a game's folder to do that.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. DXVK Causes Worse Performance or Introduces New Glitches

 Sometimes adding DXVK to a game might have the opposite effect. Unfortunately, there's no way for an end user to fix such issues.

 Did a game's performance tank or visual glitches appear after adding DXVK? Exit the game and delete the DXVK's DLLs from its directory.

### 3\. You Want to Play Your Game Online

 DXVK is a compatibility layer and only affects the graphic output of a game. Still, some companies are against any modification of their games to ensure a fair environment for everyone.

 DXVK might not be "cheating", but it's still a "game modification", and could get flagged as such.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. The Game Already Has Built-In Vulkan Support

 If a game already uses the Vulkan API, like Doom Eternal, there's no reason to set its output to Direct3D to then translate it to Vulkan.

### 5\. The Game Uses Direct3D 12

 Since Direct3D 12 is almost fully on par with Vulkan, there's nothing to gain by translating one ultra-modern graphics API to another one.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://on-screen-recording.techidaily.com/new-webcam-setup-for-quick-recordings-on-chromebooks/"><u>[New] Webcam Setup for Quick Recordings on Chromebooks</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-dji-drone-prospectus-phantom-3-edition/"><u>[Updated] 2024 Approved  DJI Drone Prospectus  Phantom 3 Edition</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-raw-footage-to-final-cut-youtube-and-its-equivalents/"><u>[Updated] 2024 Approved  From Raw Footage to Final Cut  YouTube and Its Equivalents</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-key-methods-for-gathering-high-end-video-backdrops/"><u>[Updated] Key Methods for Gathering High-End Video Backdrops</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-simplifying-visual-transformations-utilizing-luts-for-obs-videos/"><u>2024 Approved  Simplifying Visual Transformations  Utilizing LUTs for OBS Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/conquer-new-horizons-with-windows-and-steamos-on-a-deck/"><u>Conquer New Horizons with Windows & SteamOS on a Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/conquering-the-ps5-playground-with-an-assist-controller/"><u>Conquering the PS5 Playground with an Assist Controller</u></a></li>
<li><a href="https://games-able.techidaily.com/counteracting-missing-elements-alert-on-pc/"><u>Counteracting Missing Elements Alert on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-the-complex-interactions-between-endocannabinoid-receptors-and-brain-functions/"><u>Decoding the Complex Interactions Between Endocannabinoid Receptors and Brain Functions</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-realme-11-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Realme 11 Pro | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/forming-a-play-group-on-xbox-nextgen/"><u>Forming a Play Group on Xbox NextGen</u></a></li>
<li><a href="https://games-able.techidaily.com/friendly-fights-across-phones-choice-of-mobile-matchups/"><u>Friendly Fights Across Phones: Choice of Mobile Matchups</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-find-and-install-the-latest-dell-wd19-driver-software/"><u>How to Find & Install the Latest Dell WD19 Driver Software</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-fix-steams-content-file-locked-error-in-windows/"><u>How to Fix Steam’s “Content File Locked” Error in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-play-counter-strike-2-on-your-mac/"><u>How to Play Counter-Strike 2 on Your Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/ideal-game-setup-to-captivate-a-broad-demographic/"><u>Ideal Game Setup to Captivate a Broad Demographic</u></a></li>
<li><a href="https://games-able.techidaily.com/identifying-key-elements-in-a-wireless-mouse/"><u>Identifying Key Elements in a Wireless Mouse</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-cutting-edge-mac-hd-screen-and-sound-mastery/"><u>In 2024, Cutting-Edge Mac HD Screen and Sound Mastery</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-prime-focus-best-photo-viewing-win11-app/"><u>In 2024, Prime Focus  Best Photo Viewing Win11 App</u></a></li>
<li><a href="https://games-able.techidaily.com/indie-discoveries-unveiling-selectively-chosen-games/"><u>Indie Discoveries: Unveiling Selectively Chosen Games</u></a></li>
<li><a href="https://games-able.techidaily.com/innovative-ways-to-assess-your-xbox-playtime/"><u>Innovative Ways to Assess Your Xbox Playtime</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-nyts-influence-labyrinth/"><u>Navigating NYT's Influence Labyrinth</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/1714925137654-new-alice-johnson-and-ethan-smith-phd-department-of-musicology-university-of-harmonia-open-access-copyright-2023-by-dr-johnson-and-prof-smith-this-work-is-l/"><u>New Alice Johnson and Ethan Smith, Ph.D., Department of Musicology, University of Harmonia (Open Access). Copyright © 2023 by Dr. Johnson and Prof. Smith. This Work Is Licensed Under a Creative Commons Attribution-Share Alike 4.0 License for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/pokemon-strategy-for-ios-devices-a-complete-walkthrough/"><u>Pokémon Strategy for iOS Devices - A Complete Walkthrough</u></a></li>
<li><a href="https://games-able.techidaily.com/prime-choice-8-best-news-and-reviews-for-gamers/"><u>Prime Choice: 8 Best News & Reviews for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-game-multisession-access-enablement/"><u>PS5 Game Multisession Access Enablement</u></a></li>
<li><a href="https://games-able.techidaily.com/seamless-integration-of-prime-and-twitch/"><u>Seamless Integration of Prime and Twitch</u></a></li>
<li><a href="https://games-able.techidaily.com/stellar-shaper-exploring-innovative-pc-brands/"><u>Stellar Shaper: Exploring Innovative PC Brands</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-gpu-troubleshooting-for-the-most-recurrent-cases/"><u>Streamlining GPU Troubleshooting for The Most Recurrent Cases</u></a></li>
<li><a href="https://games-able.techidaily.com/the-changing-landscape-of-online-multiplay-games/"><u>The Changing Landscape of Online Multiplay Games</u></a></li>
<li><a href="https://games-able.techidaily.com/the-essential-guide-to-choosing-a-premium-gaming-display/"><u>The Essential Guide to Choosing a Premium Gaming Display</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-essentials-for-a-powerful-metaverse-experience-top-7-for-2024/"><u>The Essentials for a Powerful Metaverse Experience (Top 7) for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ls-showdown-tech-titans-clashing-in-real-time-for-2024/"><u>The LS Showdown  Tech Titans Clashing in Real Time for 2024</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-loadlibrary-failed-fixing-the-problem-of-error-87-in-windows/"><u>Troubleshooting 'LoadLibrary Failed' - Fixing the Problem of Error 87 in Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-adventure-awaits-in-todays-mmos/"><u>Ultimate Adventure Awaits in Today's MMOs</u></a></li>
<li><a href="https://games-able.techidaily.com/uncovering-alternatives-7-arguments-against-ray-tracing-embrace/"><u>Uncovering Alternatives: 7 Arguments Against Ray Tracing Embrace</u></a></li>
<li><a href="https://games-able.techidaily.com/unleashing-visual-fidelity-on-series-x-blue-ray/"><u>Unleashing Visual Fidelity on Series X Blue-Ray</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-full-potential-navigating-switch-login/"><u>Unlocking Full Potential: Navigating Switch Login</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-the-cryptic-character-set-of-steam-ids/"><u>Unlocking the Cryptic Character Set of Steam IDs</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-the-7-most-advanced-bot-allies-for-twitch-stars/"><u>Unveiling the 7 Most Advanced Bot Allies for Twitch Stars</u></a></li>
</ul></div>

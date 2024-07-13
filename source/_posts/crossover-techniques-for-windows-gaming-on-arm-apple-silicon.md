---
title: CrossOver Techniques for Windows Gaming on ARM Apple Silicon
date: 2024-07-12T03:18:40.365Z
updated: 2024-07-13T03:18:40.365Z
tags:
  - games
categories:
  - games
description: This Article Describes CrossOver Techniques for Windows Gaming on ARM Apple Silicon
excerpt: This Article Describes CrossOver Techniques for Windows Gaming on ARM Apple Silicon
keywords: ARM Apple Silicon Gaming,Windows ARM Optimization,CrossOver Gaming Techniques,Silicon-Based Gaming Performance,ARM vs X86 Game Compatibility,Gaming on Apple Silicon with CrossOver,Windows Gaming ARM Techniques
thumbnail: https://thmb.techidaily.com/e7857315bad256fdc5741086fa363d0007b6f6fca6b50e61093052da5a00ac70.jpg
---

## CrossOver Techniques for Windows Gaming on ARM Apple Silicon

 Before Apple released its M-powered Macs, there was no issue running Windows on your Mac. However, Windows has not released a software architecture allowing you to run Windows naturally on an Apple silicon Mac. That means gamers who would like to play Windows games must use virtualization software.

 While Parallels is great, it only uses a fraction of your Mac’s power, giving for subpar gaming performance. That’s where CrossOver comes in; CrossOver will use as much of your Mac’s hardware as possible, and you can download and play Windows Steam games with it.

## Download, Install, and Set Up CrossOver

 The first step to begin your Apple silicon Mac Windows gaming journey is downloading and installing CrossOver.

 You can check if the game you wish to play is compatible with CrossOver by searching for it in the**App Compatibility** section of CrossOver’s website menu. It ranks how compatible a title is with a star rating system. We recommend you search for the games you would like to play there first.

Follow the steps below to get started:

1. Visit [CodeWeavers website](https://www.codeweavers.com/crossover#mac) to download CrossOver. The software isn’t free, but you can click the**Free Trial** button on the Mac category to get started with a 14-day trial.  
![CrossOver download link on its website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/crossover-download-link-on-its-website.jpeg)
2. Enter your name and email, and hit**Return** on your keyboard to begin the download.
3. Install the application from the crossover.zip file. If you run into any issues, you can read our guide on [how to install Mac software](https://www.makeuseof.com/tag/install-remove-mac-software-5-easy-methods/) for some guidance.
4. When you run the app, you’ll see a dialogue box asking you to buy or try CrossOver. Select**Try Now** .  
![CrossOver purchase dialogue popup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/crossover-purchase-dialogue-popup.jpeg)
5. You’ll find yourself in a window with an empty Home page.

 You’ll notice that the menu is divided into**Home** and**Bottles** . Essentially, the**Bottles** section is where all the environments you download and run Windows applications are sorted. The**Home** section, however, contains shortcuts to recently opened Bottles.

## Install Steam in CrossOver

 CrossOver actually makes installing Steam’s bottle very easy. And, of course, before installing Steam,[ensure you have a functioning Steam account](https://www.makeuseof.com/what-is-steam-how-to-install/) .

Here’s how to get Steam on CrossOver:

1. Click**Install** at the bottom of the CrossOver side menu. You may find Steam in the**Popular Applications** section, but you can also use the search window.  
![Install section of CrossOver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-section-of-crossover.jpeg)
2. Double-click**Steam** and choose**Install** .
3. Optional: You can choose which version of Steam you would like to install or what installer you would like to use in the**Details** section of Steam’s information page. Just click**Edit** .  
![Steam information page in CrossOver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/steam-information-page-in-crossover.jpeg)
4. Click**Yes** ,**Next** , or agree to any popups that appear on your screen while the installation continues.
5. Microsoft XML Parser Setup will ask you to fill in the User Name and Organization input boxes, but you can leave these sections blank and click**Next** .  
![Microsoft XML Parser Setup on CrossOver for macOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/microsoft-xml-parser-setup-on-crossover-for-macos.jpeg)
6. Follow the on-screen instructions for Steam’s setup and wait for the app to update. You’ll see Steam’s login screen as soon as it's finished.

 Return back to CrossOver’s window, and you’ll notice that you have Steam as one of your bottles. Leave Steam alone for now and download some dependencies you would need to run the games you get from Steam.

## Install DirectX and DXVK

 DXVK is a Direct3D translation layer for running 3D applications, while [DirectX is a Microsoft API for improving software access to hardware](https://www.makeuseof.com/what-is-directx-why-important-for-gaming/) . You’ll need them both to run your games fluidly.

Here’s how to install them to your Steam bottle:

1. **Control** \-click or secondary-click**Steam** on the side menu.
2. Select**Install software into ‘Steam’,** and CrossOver will take you back to the Install page.  
![Steam Bottle context menu on CrossOver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/steam-bottle-context-menu-on-crossover.jpeg)
3. Type**DirectX** into the search bar, select**DirectX for Modern Games** , and click**Install** .
4. Follow the on-screen instructions to finish the installation.
5. Once it’s finished, repeat the same method for DXVK. Download both**DXVOK (Builtin)** and**DXVK (Upstream)** .

 These two are very important because it lets Steam access your Mac’s GPU. If you try to install games without doing this, Steam will give you an error.

## Set Up Steam, Log In, and Play

 You can now return back to Steam and input your username and password. Go to your library, select the game you want to play and install it.

![Knights of Pen & Paper II on CrossOver Steam](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/knights-of-pen-paper-ii-on-crossover-steam.jpeg)

 Once the game is done installing, you’ll find it in your Steam bottle. You can launch it from there, or you can launch it directly from Steam if you like.

 If you run into any issues starting the game, you can try launching the game directly from its file by following the steps below:

1. Go to**Library** on Steam.
2. Secondary-click the game you want to play to open the context menu.
3. Navigate to**Manage > Browse local files** .  
![Knights of Pen and Paper 2 context menu on Steam](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/knights-of-pen-and-paper-2-context-menu-on-steam.jpeg)
4. Find and select the .exe file for the game and hit**Return** on your keyboard to run it directly from there.

 You can have both your Mac and CrossOver versions of Steam open at the same time. However, it can get a little confusing and easy to mix the two up. You can differentiate them by hovering over their icons on the Dock; CrossOver’s Steam will say**wine64** , while Mac’s Steam will simply say**Steam** .

 However, you don’t need to play only Steam games on CrossOver; most other popular gaming platforms will work. So, if you have your games on GOG or Epic Games Launcher, download those platforms instead of Steam and follow the instructions here all the same.

 Finally, watch out for your hardware. MacBook Airs are decent in processing power, but you could benefit a huge deal from using the extra memory from a MacBook Pro. We, therefore, recommend you use a MacBook Pro to run any serious AAA titles.

## CrossOver Offers More Power Than Parallels

 Parallels is more popular than CrossOver because it simulates the Windows OS and gives you the option to navigate it just like you would navigate a Windows-powered computer. While that’s great to offer some accessibility and familiarity, the tradeoff is power. Parallels uses about half of your computer’s resources since your Mac has to create a sandbox for it.

 CrossOver looks a lot more barebones and may be less accessible, but you get plenty of power to run games smoothly on a Mac. You can run games like The Witcher 3 and Skyrim with little to no problems at all.


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
<li><a href="https://games-able.techidaily.com/comprehensive-bg3-gear-checklist-and-more/"><u>Comprehensive BG3 Gear Checklist & More</u></a></li>
<li><a href="https://games-able.techidaily.com/diminish-xboxs-game-sounds-immediately/"><u>Diminish Xbox's Game Sounds Immediately</u></a></li>
<li><a href="https://games-able.techidaily.com/conquering-windows-11-steam-installation-errors/"><u>Conquering Windows 11 Steam Installation Errors</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-a-complete-look-at-hand-recognition-systems/"><u>2024 Approved  A Complete Look at Hand Recognition Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/conquer-classic-ps3-titles-30-powerful-pc-emulators/"><u>Conquer Classic PS3 Titles: 30 Powerful PC Emulators</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-complete-game-displays-in-epics-library/"><u>Ensuring Complete Game Displays in Epic's Library</u></a></li>
<li><a href="https://games-able.techidaily.com/disassembling-new-controller-firmware-on-series-xs/"><u>Disassembling New Controller Firmware on Series X/S</u></a></li>
<li><a href="https://games-able.techidaily.com/3-alternative-methods-for-enjoying-flash-games-post-adobe/"><u>3 Alternative Methods for Enjoying Flash Games Post-Adobe</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-steam-disconnection-issue-on-pc/"><u>Addressing Steam Disconnection Issue on PC</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/top-10-audio-reversal-tools-latest-edition-for-pcs-and-mobile-devices/"><u>Top 10 Audio Reversal Tools Latest Edition for PCs & Mobile Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/fleeting-online-realms-a-reason-for-concern/"><u>Fleeting Online Realms – A Reason for Concern?</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-motorola-moto-g-stylus-5g-2023-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Motorola Moto G Stylus 5G (2023)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-stellar-visuals-enhancing-google-meet-collaboration/"><u>[Updated] In 2024, Stellar Visuals  Enhancing Google Meet Collaboration</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pioneering-techniques-in-documentary-scripting/"><u>Pioneering Techniques in Documentary Scripting</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-bars-universal-game-accessibility/"><u>Beyond Bars: Universal Game Accessibility</u></a></li>
<li><a href="https://games-able.techidaily.com/duplicating-saved-games-securing-your-digital-artifacts/"><u>Duplicating Saved Games: Securing Your Digital Artifacts</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170370005-enriching-joy-con-gameplay-with-additional-inputs-96-chars-adjusted-for-relevancy-and-fitting-within-limits/"><u>Enriching Joy-Con Gameplay with Additional Inputs (96 Chars) - Adjusted for Relevancy and Fitting Within Limits.</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-key-factors-for-a-smart-ps5-buy/"><u>Evaluating Key Factors for a Smart PS5 Buy</u></a></li>
<li><a href="https://games-able.techidaily.com/gamers-hack-finding-the-epic-games-on-apple-arcade/"><u>Gamer's Hack: Finding the Epic Games on Apple Arcade</u></a></li>
<li><a href="https://games-able.techidaily.com/apc-handheld-reinvented-the-pdw4-story/"><u>APC Handheld Reinvented: The PDW4 Story</u></a></li>
<li><a href="https://games-able.techidaily.com/android-companion-emulating-your-favored-dreamcatcher-titles/"><u>Android Companion: Emulating Your Favored Dreamcatcher Titles</u></a></li>
<li><a href="https://games-able.techidaily.com/guide-to-remove-unwanted-game-data-on-ps5/"><u>Guide to Remove Unwanted Game Data on PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/excellent-gamer-tracking-apps-review/"><u>Excellent Gamer Tracking Apps Review</u></a></li>
<li><a href="https://games-able.techidaily.com/cut-out-console-noise-with-ease-on-xbox/"><u>Cut Out Console Noise with Ease on Xbox</u></a></li>
<li><a href="https://discord-videos.techidaily.com/unveiling-the-secrets-how-to-access-high-end-features-with-disconitro/"><u>Unveiling the Secrets  How to Access High-End Features with DiscoNitro</u></a></li>
<li><a href="https://games-able.techidaily.com/building-a-robust-steam-wallet-investment-guide/"><u>Building a Robust Steam Wallet - Investment Guide</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-best-guide-for-beginners-on-2d-animation-making-for-2024/"><u>New Best Guide for Beginners on 2D Animation Making for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-through-excellent-alternatives-to-gopro-cams-for-2024/"><u>Navigating Through Excellent Alternatives to GoPro Cams for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-xboxs-golden-era-via-emulation-on-a-pc/"><u>Exploring Xbox's Golden Era via Emulation on a PC</u></a></li>
<li><a href="https://games-able.techidaily.com/choose-your-battles-wisely-switches-in-gaming/"><u>Choose Your Battles Wisely: SWITCHES in Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/cosmic-crafter-navigating-novel-pc-choices/"><u>Cosmic Crafter: Navigating Novel PC Choices</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-toolkit-for-dominating-social-media-management-smm/"><u>[New] The Ultimate Toolkit for Dominating Social Media Management (SMM)</u></a></li>
<li><a href="https://games-able.techidaily.com/browsing-for-fun-the-9-intriguing-advantages-and-disadvantages-of-e-games/"><u>Browsing for Fun: The 9 Intriguing Advantages & Disadvantages of E-Games</u></a></li>
<li><a href="https://games-able.techidaily.com/acquiring-ps5-steamboat-to-fortnite-vip-points/"><u>Acquiring PS5: Steamboat to Fortnite VIP Points</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-the-25-most-high-performance-instant-vocal-change-apps-a-critical-perspective/"><u>Updated In 2024, The 25 Most High-Performance Instant Vocal Change Apps – A Critical Perspective</u></a></li>
</ul></div>

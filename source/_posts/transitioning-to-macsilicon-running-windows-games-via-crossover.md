---
title: "Transitioning to MacSilicon: Running Windows Games via CrossOver"
date: 2024-06-25T12:48:33.731Z
updated: 2024-06-26T12:48:33.731Z
tags:
  - games
categories:
  - games
description: "This Article Describes Transitioning to MacSilicon: Running Windows Games via CrossOver"
excerpt: "This Article Describes Transitioning to MacSilicon: Running Windows Games via CrossOver"
keywords: CrossOver Play,Windows Games for Mac,MacSilicon Gaming Software,CrossOver Compatibility,Virtualization for Mac Gaming,CrossOver Installation Guide,Native Windows Games on Mac
thumbnail: https://thmb.techidaily.com/b21b5439f80b1a102ace85a9da59aeae7943c3afff9ae70d9fb6a7745b13a600.jpg
---

## Transitioning to MacSilicon: Running Windows Games via CrossOver

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
<li><a href="https://games-able.techidaily.com/unlocking-potential-on-twitch-tips-for-quality-content/"><u>Unlocking Potential on Twitch: Tips for Quality Content</u></a></li>
<li><a href="https://games-able.techidaily.com/deciphering-gamings-meta-meaning-and-adherence/"><u>Deciphering Gaming's Meta: Meaning & Adherence</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-complete-game-inventory-recognition-by-steam/"><u>Ensuring Complete Game Inventory Recognition by Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-for-dealing-with-nonfunctional-switch-situations/"><u>Steps for Dealing with Nonfunctional Switch Situations</u></a></li>
<li><a href="https://games-able.techidaily.com/click-and-draw-showdown-best-for-beatboxing/"><u>Click & Draw Showdown: Best for Beatboxing</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-value-of-switchs-online-service/"><u>Navigating the Value of Switch's Online Service</u></a></li>
<li><a href="https://games-able.techidaily.com/step-into-the-mechanics-how-to-deconstruct-your-xbox-360s/"><u>Step Into the Mechanics: How to Deconstruct Your Xbox 360/S</u></a></li>
<li><a href="https://games-able.techidaily.com/advantages-and-pitfalls-of-early-access-titles/"><u>Advantages & Pitfalls of Early Access Titles</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionize-your-gaming-setup-psvr2-accessories/"><u>Revolutionize Your Gaming Setup: PSVR2 Accessories</u></a></li>
<li><a href="https://games-able.techidaily.com/best-8-minimalist-emulators-android-gaming-pcmac/"><u>Best 8 Minimalist Emulators: Android Gaming Pc/Mac</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-step-by-step-guide-to-basic-ps-color-correction-for-2024/"><u>[Updated] Step-by-Step Guide to Basic PS Color Correction for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-do-you-want-to-better-your-video-with-premiere-pro-try-transitions-this-article-will-give-you-10-best-premiere-pro-transitions-and-let-you-know-how-/"><u>Updated Do You Want to Better Your Video with Premiere Pro? Try Transitions. This Article Will Give You 10 Best Premiere Pro Transitions and Let You Know How to Add Transitions in Premiere. Check It Out</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-what-is-an-ai-tool-wondershare-virbo-glossary/"><u>New What Is an AI Tool? | Wondershare Virbo Glossary</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-reimagine-fuzzy-images-selecting-the-ultimate-10-internet-tools/"><u>2024 Approved  Reimagine Fuzzy Images  Selecting the Ultimate 10 Internet Tools</u></a></li>
<li><a href="https://extra-hints.techidaily.com/painting-with-light-an-experts-guide-to-color-grading/"><u>Painting with Light  An Expert's Guide to Color Grading</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-innovative-text-to-speech-solutions-dominating-the-market/"><u>In 2024, Innovative Text-to-Speech Solutions Dominating the Market</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-apple-id-activation-lock-from-iphone-7-plus-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID Activation Lock From iPhone 7 Plus?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exclusive-selection-top-gopro-adornments/"><u>[Updated] Exclusive Selection  Top Gopro Adornments</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-deleted-photos-on-motorola-razr-40-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Retrieve  deleted photos on Motorola Razr 40</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On OnePlus Ace 3 | Dr.fone</u></a></li>
</ul></div>

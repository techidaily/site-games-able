---
title: "Transitioning to MacSilicon: Running Windows Games via CrossOver"
date: 2024-07-12T03:04:28.709Z
updated: 2024-07-13T03:04:28.709Z
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
<li><a href="https://games-able.techidaily.com/elite-handheld-games-with-controller-support/"><u>Elite Handheld Games with Controller Support</u></a></li>
<li><a href="https://games-able.techidaily.com/crossover-instructions-full-bg3-experience-for-macos-users/"><u>CrossOver Instructions: Full BG3 Experience for macOS Users</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-premium-6-services-for-live-video-localization/"><u>2024 Approved  Premium 6 Services for Live Video Localization</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/accidental-tiktok-update-restore-or-reload-content/"><u>Accidental TikTok Update  Restore or Reload Content?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-nokia-c210-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Nokia C210 Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-your-game-repositorys-visibility-on-epic-labs/"><u>Enhancing Your Game Repository's Visibility on Epic Labs</u></a></li>
<li><a href="https://games-able.techidaily.com/battle-mastery-choosing-gaming-controls-wisely/"><u>Battle Mastery: Choosing Gaming Controls Wisely</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-smooth-transitions-in-games-through-nvidia-g-sync/"><u>Exploring Smooth Transitions in Games Through Nvidia G-Sync</u></a></li>
<li><a href="https://games-able.techidaily.com/your-mobile-gaming-adventure-begins-here-with-7-essentials/"><u>Your Mobile Gaming Adventure Begins Here, With 7 Essentials</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-beyond-cyberlink-hunt-for-the-ultimate-screen-recording-app/"><u>2024 Approved  Beyond Cyberlink  Hunt for the Ultimate Screen Recording App</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-beyond-the-box-a-list-of-non-gamebar-screen-recorders/"><u>[New] In 2024, Beyond the Box  A List of Non-GameBar Screen Recorders</u></a></li>
<li><a href="https://games-able.techidaily.com/bidding-adieu-to-ea-new-price-prohibitive-for-gaming/"><u>Bidding Adieu to EA: New Price Prohibitive for Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/cautionary-tales-for-paying-gamers-to-develop-games/"><u>Cautionary Tales for Paying Gamers to Develop Games</u></a></li>
<li><a href="https://games-able.techidaily.com/efficient-controller-utilization-a-ryujinx-emulation-blueprint/"><u>Efficient Controller Utilization: A Ryujinx Emulation Blueprint</u></a></li>
<li><a href="https://youtube-web.techidaily.com/hematic-wow-factor-designing-engaging-youtube-templates-for-2024/"><u>[New] Thematic Wow Factor  Designing Engaging YouTube Templates for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-premium-nitro-services/"><u>Evaluating Premium Nitro Services</u></a></li>
<li><a href="https://games-able.techidaily.com/best-community-grounds-for-game-masters/"><u>Best Community Grounds for Game Masters</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-a-secure-steam-environment-for-kids/"><u>Ensuring a Secure Steam Environment for Kids</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-pedagogic-pros-the-finest-lecture-recording-devices-for-instructors-for-2024/"><u>[New] Pedagogic Pros  The Finest Lecture Recording Devices for Instructors for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/5-text-based-adventure-games-you-can-play-in-your-browser/"><u>5 Text-Based Adventure Games You Can Play in Your Browser</u></a></li>
<li><a href="https://games-able.techidaily.com/cross-border-play-on-your-nintendo-switch-console/"><u>Cross-Border Play on Your Nintendo Switch Console</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161479393-transform-your-playtime-claim-deals/"><u>Transform Your Playtime, Claim Deals</u></a></li>
<li><a href="https://games-able.techidaily.com/achieving-perfection-a-complete-ps4-factory-reset/"><u>Achieving Perfection: A Complete PS4 Factory Reset</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-prime-editing-choosing-the-best-for-youtube/"><u>2024 Approved  Prime Editing  Choosing the Best For YouTube</u></a></li>
<li><a href="https://games-able.techidaily.com/does-the-birth-of-fsr-3-herald-a-new-era-beyond-nvidias-dlss-35/"><u>Does the Birth of FSR 3 Herald a New Era Beyond NVIDIA's DLSS 3.5?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/cutting-edge-techniques-for-enhanced-visuals-in-videoleap-for-2024/"><u>Cutting-Edge Techniques for Enhanced Visuals in Videoleap for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/the-ultimate-how-to-for-controlling-youtube-playback-speed/"><u>The Ultimate How-To for Controlling YouTube Playback Speed</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-simplifying-cinematography-best-film-cameras-for-newbies/"><u>[Updated] 2024 Approved  Simplifying Cinematography  Best Film Cameras for Newbies</u></a></li>
<li><a href="https://games-able.techidaily.com/does-the-nintendo-switch-oled-work-with-an-old-dock/"><u>Does the Nintendo Switch OLED Work With an Old Dock?</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-art-of-testimonials-techniques-for-persuasive-video-credibility/"><u>[Updated] The Art of Testimonials  Techniques for Persuasive Video Credibility</u></a></li>
<li><a href="https://games-able.techidaily.com/15-dynamic-duo-games-fun-with-companions-anytime-anywhere/"><u>15 Dynamic Duo Games: Fun with Companions Anytime, Anywhere</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-zte-nubia-flip-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from ZTE Nubia Flip 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-without-the-chair-cushion/"><u>Gaming Without the Chair Cushion</u></a></li>
<li><a href="https://games-able.techidaily.com/challenge-yourself-with-five-furious-fiddlers/"><u>Challenge Yourself With Five Furious Fiddlers</u></a></li>
<li><a href="https://games-able.techidaily.com/8-leading-websites-that-define-modern-gaming-news/"><u>8 Leading Websites That Define Modern Gaming News</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-evaluation-report-on-sound-forges-audio-editing-tools/"><u>Updated In 2024, Evaluation Report on Sound Forges Audio Editing Tools</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-new-gameplay-modes-on-ps5/"><u>Discovering New Gameplay Modes on PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-server-dynamics-integrating-strategy-based-games-discord/"><u>Boosting Server Dynamics: Integrating Strategy-Based Games (Discord)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/twitter-video-dimensions-aspect-ratio-standards/"><u>Twitter Video Dimensions  Aspect Ratio Standards</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-the-go-sonys-ps-vita/"><u>Game on the Go: Sony's PS Vita</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-windows-11-a-step-by-step-upgrade-guide/"><u>2024 Approved  Mastering Windows 11  A Step-by-Step Upgrade Guide</u></a></li>
</ul></div>

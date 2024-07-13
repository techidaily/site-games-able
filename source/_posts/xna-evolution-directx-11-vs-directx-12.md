---
title: "XNA Evolution: DirectX 11 Vs. DirectX 12"
date: 2024-07-12T03:05:28.953Z
updated: 2024-07-13T03:05:28.953Z
tags:
  - games
categories:
  - games
description: "This Article Describes XNA Evolution: DirectX 11 Vs. DirectX 12"
excerpt: "This Article Describes XNA Evolution: DirectX 11 Vs. DirectX 12"
keywords: XNA GameDev Evolution,DirectX 11 Analysis,DirectX 12 Overview,DX 12 VS. DX 11 Benefits,Enhanced Graphics,Performance in DirectX 12,XNA Evolution Graphics Tech
thumbnail: https://thmb.techidaily.com/88761ec66a00f0a48060e78f738a540e311f0a473b14b1614804e43117d93320.jpg
---

## XNA Evolution: DirectX 11 Vs. DirectX 12

 DirectX 12 was released alongside Windows 10 in 2015\. With its release, Microsoft's DirectX 12 ushered in a new era for gamers and game developers. Capable of reducing CPU overhead while boosting GPU performance, DirectX 12 quickly made a name for itself.

 However, is increasing your performance really as simple as switching from DirectX 11 to DirectX 12? Let's find out by looking at the differences between DirectX 11 and 12.

## What Is Microsoft's DirectX?

![DirectX logo imposed on a photo of a man coding](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-1.jpg)

 As explained in [our overview of Microsoft DirectX](https://www.makeuseof.com/tag/everything-need-know-directx-2016/) , DirectX is a collection of application programming interfaces (APIs) used for handling tasks related to multimedia. This includes game programming on Microsoft-based platforms like Windows and Xbox. To provide some context, let's briefly talk about APIs.

 An API makes it possible for two or more computer programs to communicate with each other, which we discuss in [our overview of APIs](https://www.makeuseof.com/what-is-api/) . Think of it like a telephone. If your mom texts you with a grocery list, your phone will receive that data and display it for you. That is basically an API.

## What Are the Differences Between DirectX 11 and DirectX 12?

 So, what are the differences between DirectX 11 and DirectX 12? Put simply, DirectX 12 is the latest version of DirectX. One of the most noticeable differences is how they interact with your hardware. Most games developed with DirectX 11 only utilize between two and four [CPU cores](https://www.makeuseof.com/cpu-vs-vcpu-threads-vs-cores/) . One of these cores usually tells the GPU what to do.

 The game then uses the remaining cores to handle various CPU-intensive settings like a game's particles or draw distance. On the other hand, DirectX 12 spreads a CPU's workload across multiple cores and allows every core to talk to the GPU simultaneously.

 DirectX 12 also comes with some fancy bells and whistles. This includes asynchronous computing and pipeline state objects (PSOs). Asynchronous computing increases GPU utilization by allowing multiple workloads to work in parallel. This essentially unlocks your GPU's full potential.

 Aside from graphics rendering, your GPU handles a wide range of other tasks, such as running machine learning algorithms. With DirectX 11, the GPU can only perform one of these tasks at a time and in a certain order. Performance takes a hit when this occurs because your GPU resources aren't being used efficiently.

 Think of it like a waiter at a restaurant. When a waiter takes your order, they ask you what you want to drink first. Once you receive your drinks, they ask you what you want for the main course. Your order is taken in steps. The waiter isn't going to ask you what you would like for dessert before you have had your main course. While this is effective, it isn't as efficient as it could be.

 In computing, a different GPU resource would handle each of the waiter's tasks. Until you receive your drink, the GPU resources needed to take your main course order will be idle. With DirectX 12's asynchronous computing, the waiter would be able to take your order all at once, like in a fast food chain. This maximizes GPU usage and improves your gaming performance.

 DirectX 12 also introduced pipeline state objects (PSOs). With DirectX 11, when a game's geometry is submitted to the GPU to be rendered, various hardware settings are responsible for interpreting and rendering this data. This is called the graphics pipeline and the flow of data inputs and outputs that occur as your GPU renders frames. However, DirectX 11's graphics pipeline isn't perfect.

 This pipeline contains a collection of different states, including rasterize state, blend state, and depth stencil state, among other components. In DirectX 11, there are dependencies between these different states. As a result, one state cannot be completed until the previous state is defined. This decreases GPU utilization and increases CPU overhead at the cost of performance.

 To get around this, DirectX 12 introduced PSOs, objects that describe the state of the entire graphics pipeline. PSOs are like a bottle that contains the various states and components needed to create an image. This allows the GPU to pre-process every dependent state instead of continually recomputing states based on the current graphics pipeline.

 This significantly reduces the CPU overhead found in DirectX 11 and improves performance. So, what does this difference look like? Well, according to Microsoft, DirectX 12 reduces CPU overhead by up to 50 percent and improves GPU performance by as much as 20 percent. While those are some substantial improvements, this doesn't mean you will see the same results.

## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read [our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

## Is DirectX 12 the Right Choice for You?

 All in all, switching from DirectX 11 to DirectX 12 isn't as black and white as it sounds. It depends on a variety of factors such as hardware, software, operating system, and whether a game supports both at all. All of these need to be considered before making a decision, and this will likely be true for future generations of DirectX as well.


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
<li><a href="https://games-able.techidaily.com/new-graphics-feature-amds-fsr-3-dlss-35-on-trial/"><u>New Graphics Feature, AMD's FSR 3: DLSS 3.5 on Trial?</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-excel-at-pokemon-a-guide-for-ios-gamers/"><u>How to Excel at Pokémon: A Guide for iOS Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/games-vanish-quickly-is-it-a-concern/"><u>Games Vanish Quickly: Is It a Concern?</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-how-to-download-tiktok-musically-videos-quickly/"><u>[Updated] 2024 Approved  How to Download TikTok (Musical.ly) Videos Quickly?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-oneplus-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For OnePlus Phones</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-gaming-iem-quality-an-overview/"><u>Exploring Gaming IEM Quality: An Overview</u></a></li>
<li><a href="https://audio-editing.techidaily.com/ideal-compilation-of-unobtrusive-instrumentals-for-comforting-background-noise-for-2024/"><u>Ideal Compilation of Unobtrusive Instrumentals for Comforting Background Noise for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/mending-steam-library-linking-issues/"><u>Mending Steam Library Linking Issues</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-the-art-of-eating-10-social-media-staples-for-2024/"><u>[Updated] The Art of Eating  10 Social Media Staples for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/optimized-network-interfaces-a-gamers-dream/"><u>Optimized Network Interfaces: A Gamer's Dream</u></a></li>
<li><a href="https://games-able.techidaily.com/ifa-2023-unleashing-the-future-of-game-hardware/"><u>IFA 2023: Unleashing the Future of Game Hardware</u></a></li>
<li><a href="https://games-able.techidaily.com/eliminate-automatic-subscriptions-from-steam/"><u>Eliminate Automatic Subscriptions From Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-ensure-audio-plays-only-through-your-headset-on-xbox-series-xs/"><u>How to Ensure Audio Plays Only Through Your Headset on Xbox Series X|S</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-samsung-ue590-masterclass-cutting-edge-gaming-display/"><u>In 2024, Samsung UE590 Masterclass  Cutting-Edge Gaming Display</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-office-seat-style/"><u>Game on, Office Seat Style</u></a></li>
<li><a href="https://games-able.techidaily.com/crafting-cost-effective-powerful-3d-games/"><u>Crafting Cost-Effective, Powerful 3D Games</u></a></li>
<li><a href="https://games-able.techidaily.com/guide-connect-ps5-wireless-controllers-on-phone/"><u>Guide: Connect PS5 Wireless Controllers on Phone</u></a></li>
<li><a href="https://games-able.techidaily.com/fixing-minecraft-launcher-error-0x803f8001-on-windows-devices/"><u>Fixing Minecraft Launcher Error 0X803F8001 on Windows Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/digital-goods-get-em-for-xbox/"><u>Digital Goods: Get 'Em for Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/leadership-in-gaming-secure-early-spiderman-2-edition/"><u>Leadership in Gaming: Secure Early SPIDERMAN 2 Edition</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/gain-smooth-play-solving-windows-based-epic-games-crashes/"><u>Gain Smooth Play: Solving Windows-Based Epic Games Crashes</u></a></li>
<li><a href="https://games-able.techidaily.com/makeuseofs-pinnacle-innovations-from-mwc-2024/"><u>MakeUseOf's Pinnacle Innovations From MWC 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-step-by-step-to-stunning-timelapses-a-comprehensive-guide-using-gopro/"><u>[New] Step-By-Step to Stunning Timelapses  A Comprehensive Guide Using GoPro</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-hero5-black-vs-yi-4k-the-latest-in-action-cam-showdown/"><u>2024 Approved  Hero5 Black Vs. Yi 4K  The Latest in Action Cam Showdown</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/bring-on-the-browsers-top-strategies-to-transform-your-unwatched-videos-for-2024/"><u>Bring on the Browsers  Top Strategies to Transform Your Unwatched Videos for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/emudeck-tips-for-optimal-emulation-on-steam-deck/"><u>EmuDeck Tips for Optimal Emulation on Steam Deck</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-snap-back-on-tiktok-after-accidental-loadout/"><u>[Updated] In 2024, Snap-Back on TikTok After Accidental Loadout</u></a></li>
<li><a href="https://extra-information.techidaily.com/blending-youtube-audio-features-into-video-projects/"><u>Blending YouTube Audio Features Into Video Projects</u></a></li>
<li><a href="https://games-able.techidaily.com/decreasing-digital-communication-time-techniques-for-lowering-response-times/"><u>Decreasing Digital Communication Time: Techniques for Lowering Response Times</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-step-by-step-cheatsheet-for-stunning-collage-art/"><u>2024 Approved  Step-by-Step Cheatsheet for Stunning Collage Art</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-ultimate-selection-elite-iphone-call-alerts/"><u>[New] Ultimate Selection  Elite iPhone Call Alerts</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-list-celebrating-the-best-8-gaming-sites/"><u>Essential List: Celebrating the Best 8 Gaming Sites</u></a></li>
<li><a href="https://games-able.techidaily.com/foremost-gaming-with-device-controllers/"><u>Foremost Gaming with Device Controllers</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-ps4-performance-a-comprehensive-guide/"><u>Boosting PS4 Performance: A Comprehensive Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/installation-made-simple-get-discord-running-on-mac/"><u>Installation Made Simple: Get Discord Running on Mac</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-from-jittery-to-jerky-free-video-stabilization-techniques-in-premiere-pro/"><u>Updated 2024 Approved From Jittery to Jerky-Free Video Stabilization Techniques in Premiere Pro</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-unleash-your-youtube-playlists-a-comprehensive-guide/"><u>2024 Approved  Unleash Your YouTube Playlists  A Comprehensive Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/conquer-the-visual-frontier-steps-to-setting-up-your-xbox-series-x-in-4k/"><u>Conquer the Visual Frontier: Steps to Setting Up Your Xbox Series X in 4K</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-gaming-fallout-counterparts-await/"><u>Dive Into Gaming: Fallout Counterparts Await!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-streaming-showdown-obs-and-shadowtoolkit/"><u>[New] In 2024, Streaming Showdown  OBS & ShadowToolkit</u></a></li>
<li><a href="https://games-able.techidaily.com/commanding-chaos-essential-tunings-for-first-person-shooters/"><u>Commanding Chaos: Essential Tunings for First-Person Shooters</u></a></li>
<li><a href="https://games-able.techidaily.com/comparing-asus-tuf-proart-and-prime-pc-brands-unveiled/"><u>Comparing Asus, Tuf, ProArt & Prime: PC Brands Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/resetting-ps5s-video-game-licenses/"><u>Resetting PS5's Video Game Licenses</u></a></li>
<li><a href="https://audio-editing.techidaily.com/the-ultimate-compilation-of-best-no-price-tag-podcast-recording-programs-for-2024/"><u>The Ultimate Compilation of Best No-Price-Tag Podcast Recording Programs for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/eliminating-windows-1011-writable-device-stall-0x887a0006/"><u>Eliminating Windows 10/11' Writable Device Stall (0X887A0006)</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-pacing-perfection-controlling-frame-rates-on-snapchat/"><u>[New] In 2024, Pacing Perfection  Controlling Frame Rates on Snapchat</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-9-superior-iphone-options-for-adding-water-marks-to-images-for-2024/"><u>[New] 9 Superior iPhone Options for Adding Water Marks to Images for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-unleash-the-magic-of-tiktok-a-macbook-users-guide/"><u>[Updated] Unleash the Magic of TikTok  A MacBook User's Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-steam-how-to-stop-auto-renewal/"><u>Mastering Steam: How to Stop Auto-Renewal</u></a></li>
<li><a href="https://games-able.techidaily.com/moza-r5-unlocking-the-future-of-simulated-driving/"><u>MOZA R5: Unlocking the Future of Simulated Driving</u></a></li>
<li><a href="https://games-able.techidaily.com/keeping-it-classic-chdman-guide-for-small-sized-retro-gaming-discs/"><u>Keeping It Classic: CHDMAN Guide for Small-Sized Retro Gaming Discs</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-graphics-power-the-secrets-of-amds-xt-series/"><u>Mastering Graphics Power: The Secrets of AMD's XT Series</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-in-2024-boosting-engagement-tactics-for-great-instagram-reels/"><u>[New] In 2024, Boosting Engagement  Tactics for Great Instagram Reels</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-nvidia-best-gpus-for-enthusiasts/"><u>Beyond Nvidia: Best GPUs for Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/expert-insights-choosing-the-right-joystick/"><u>Expert Insights: Choosing the Right Joystick</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Honor X9b? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-updated-method-to-bypass-poco-f5-pro-5g-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Poco F5 Pro 5G FRP</u></a></li>
<li><a href="https://games-able.techidaily.com/cross-platform-play-android-gaming-on-linux/"><u>Cross-Platform Play: Android Gaming on Linux</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-innovative-ways-to-boost-your-snapchat-engagement-for-2024/"><u>[New] Innovative Ways to Boost Your Snapchat Engagement for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-picsart-the-ultimate-2024-guide/"><u>[Updated] Exploring PicsArt  The Ultimate 2024 Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-unlocking-timer-power-with-zero-cost/"><u>[Updated] In 2024, Unlocking Timer Power with Zero Cost</u></a></li>
<li><a href="https://games-able.techidaily.com/interpretation-and-correction-of-error-code-30005/"><u>Interpretation and Correction of Error Code 30005</u></a></li>
<li><a href="https://games-able.techidaily.com/brand-showdown-asus-rog-tuf-proart-vs-prime-precision/"><u>Brand Showdown: Asus ROG, TUF, ProArt Vs. Prime Precision</u></a></li>
</ul></div>

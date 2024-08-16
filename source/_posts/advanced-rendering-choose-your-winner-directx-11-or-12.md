---
title: "Advanced Rendering: Choose Your Winner - DirectX 11 or 12?"
date: 2024-08-15T17:18:21.905Z
updated: 2024-08-16T17:18:21.905Z
tags:
  - games
categories:
  - games
description: "This Article Describes Advanced Rendering: Choose Your Winner - DirectX 11 or 12?"
excerpt: "This Article Describes Advanced Rendering: Choose Your Winner - DirectX 11 or 12?"
keywords: DirectX Comparison,DX11 vs DX12 Benefits,Advanced Graphics Tech,Rendering Technology Trends,Next-Gen Gaming APIs,High-End Visuals in Games,Optimal DirectX Choice
thumbnail: https://thmb.techidaily.com/40d4b8ee7a20cbf9725c025acb55ef566e92109bc4a0e7b50a621bf0e1ad49b5.jpg
---

## Advanced Rendering: Choose Your Winner - DirectX 11 or 12?

 DirectX 12 was released alongside Windows 10 in 2015\. With its release, Microsoft's DirectX 12 ushered in a new era for gamers and game developers. Capable of reducing CPU overhead while boosting GPU performance, DirectX 12 quickly made a name for itself.

 However, is increasing your performance really as simple as switching from DirectX 11 to DirectX 12? Let's find out by looking at the differences between DirectX 11 and 12.

## What Is Microsoft's DirectX?

![DirectX logo imposed on a photo of a man coding](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-1.jpg)

 As explained in [our overview of Microsoft DirectX](https://www.makeuseof.com/tag/everything-need-know-directx-2016/) , DirectX is a collection of application programming interfaces (APIs) used for handling tasks related to multimedia. This includes game programming on Microsoft-based platforms like Windows and Xbox. To provide some context, let's briefly talk about APIs.

 An API makes it possible for two or more computer programs to communicate with each other, which we discuss in [our overview of APIs](https://www.makeuseof.com/what-is-api/) . Think of it like a telephone. If your mom texts you with a grocery list, your phone will receive that data and display it for you. That is basically an API.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read [our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-expertly-mastering-file-imports-in-the-realm-of-windows-10/"><u>[New] 2024 Approved  Expertly Mastering File Imports in the Realm of Windows 10</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-fast-track-uncovering-erased-reddit-conversations/"><u>[New] Fast Track  Uncovering Erased Reddit Conversations</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-mastering-the-art-of-downloading-instagram-media-for-2024/"><u>[New] Mastering the Art of Downloading Instagram Media for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pickup-vs-competitors-an-incisive-review-of-androids-top-editor/"><u>[New] PickUp Vs. Competitors  An Incisive Review of Android's Top Editor</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-prime-engagement-hook-generator/"><u>[New] Prime Engagement Hook Generator</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-elevating-visual-engagement-transferring-twitter-videos-on-snapchat/"><u>[Updated] 2024 Approved  Elevating Visual Engagement  Transferring Twitter Videos on Snapchat</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-celebrating-matrimony-the-best-wedding-movies-from-youtube-to-vimeo-for-2024/"><u>[Updated] Celebrating Matrimony  The Best Wedding Movies From YouTube to Vimeo for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-the-art-of-crafting-exclusive-cover-photos-on-instagram-for-2024/"><u>[Updated] Mastering the Art of Crafting Exclusive Cover Photos on Instagram for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-best-laptops-for-video-editing-for-2024/"><u>[Updated] The Best Laptops for Video Editing for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-oneplus-12r-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/a-user-friendly-guide-to-efficiently-use-ez-grabber-for-2024/"><u>A User-Friendly Guide to Efficiently Use EZ Grabber for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/are-we-about-to-see-a-surge-in-video-card-expenses/"><u>Are We About to See a Surge in Video Card Expenses?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/can-i-bypass-a-forgotten-phone-password-of-asus-rog-phone-7-by-drfone-android/"><u>Can I Bypass a Forgotten Phone Password Of Asus ROG Phone 7?</u></a></li>
<li><a href="https://games-able.techidaily.com/conquer-ps5-space-odyssey-secure-marvels-limited-spidey/"><u>Conquer PS5 Space Odyssey - Secure Marvel's Limited Spidey</u></a></li>
<li><a href="https://games-able.techidaily.com/deciphering-the-mysteries-of-steams-gametime-metrics-a-comprehensive-guide/"><u>Deciphering the Mysteries of Steam's Gametime Metrics: A Comprehensive Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-the-world-of-video-gaming-youtubes-latest-minigames/"><u>Dive Into the World of Video Gaming: YouTube's Latest Minigames</u></a></li>
<li><a href="https://games-able.techidaily.com/enhance-winxp-games-the-power-of-dxvk-integration/"><u>Enhance WinXP Games: The Power of DXVK Integration</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-smooth-gameplay-with-regular-ps5-control-resets/"><u>Ensuring Smooth Gameplay with Regular PS5 Control Resets</u></a></li>
<li><a href="https://games-able.techidaily.com/everyday-tactics-for-circumventing-nyt-connections/"><u>Everyday Tactics for Circumventing NYT Connections</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/fb-live-integration-with-cable-tv-for-2024/"><u>FB Live Integration with Cable TV for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/fortnite-lovers-mac-users-uncover-the-restrictions/"><u>Fortnite Lovers, Mac Users! Uncover the Restrictions</u></a></li>
<li><a href="https://games-able.techidaily.com/from-solo-existence-to-group-adventures-fixing-minecraft-lan-disconnects/"><u>From Solo Existence to Group Adventures - Fixing Minecraft LAN Disconnects</u></a></li>
<li><a href="https://some-techniques.techidaily.com/haptic-feedback-and-vr-for-medicine-for-2024/"><u>Haptic Feedback and VR for Medicine for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-change-regions-on-your-nintendo-switch/"><u>How to Change Regions on Your Nintendo Switch</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-honor-magic-6-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-infinix-note-30-5g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Infinix Note 30 5G to iPod | Dr.fone</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/inside-the-directors-cut-a-complete-review-of-powerdirector-2024/"><u>Inside the Director’s Cut  A Complete Review of PowerDirector 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/meet-the-new-nvidia-application-amplifying-games/"><u>Meet the New Nvidia Application Amplifying Games</u></a></li>
<li><a href="https://games-able.techidaily.com/online-games-unfolding-a-look-at-the-transformation/"><u>Online Games Unfolding: A Look at the Transformation</u></a></li>
<li><a href="https://games-able.techidaily.com/opera-users-guide-to-unlimited-discord-time/"><u>Opera Users' Guide to Unlimited Discord Time</u></a></li>
<li><a href="https://games-able.techidaily.com/optimized-multi-port-adapters-for-playstation-5-users/"><u>Optimized Multi-Port Adapters for PlayStation 5 Users</u></a></li>
<li><a href="https://games-able.techidaily.com/procedural-patterns-shaping-video-game-universes/"><u>Procedural Patterns: Shaping Video Game Universes</u></a></li>
<li><a href="https://games-able.techidaily.com/protecting-personal-progress-implementing-passcode-on-your-switch/"><u>Protecting Personal Progress: Implementing Passcode on Your Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-stock-stabilized-expecting-pricing-changes/"><u>PS5 Stock Stabilized: Expecting Pricing Changes</u></a></li>
<li><a href="https://games-able.techidaily.com/rom-localization-made-simple-language-patch-guide/"><u>Rom Localization Made Simple: Language Patch Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/sparkle-science-keeping-your-ps5-spotless/"><u>Sparkle Science: Keeping Your PS5 Spotless</u></a></li>
<li><a href="https://games-able.techidaily.com/tactile-triumphs-phones-or-larger-screens-for-play/"><u>Tactile Triumphs: Phones or Larger Screens for Play</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-nine-crucial-nintendo-switch-tips/"><u>The Ultimate Guide: Nine Crucial Nintendo Switch Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/this-app-lets-you-play-nintendo-classics-on-your-iphone-heres-how/"><u>This App Lets You Play Nintendo Classics on Your iPhone: Here's How</u></a></li>
<li><a href="https://games-able.techidaily.com/ultra-low-price-caps-lock-and-scroll-options/"><u>Ultra-Low-Price Caps Lock & Scroll Options</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-xbox-golds-shift-to-game-pass-inclusion/"><u>Understanding Xbox Gold's Shift to Game Pass Inclusion</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-the-xbox-case-purpose/"><u>Unveiling The Xbox Case Purpose</u></a></li>
<li><a href="https://games-able.techidaily.com/why-gamers-need-to-upgrade-oleds-superiority-claim/"><u>Why Gamers Need to Upgrade - OLED's Superiority Claim.</u></a></li>
</ul></div>

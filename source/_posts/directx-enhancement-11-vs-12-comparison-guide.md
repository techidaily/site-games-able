---
title: "DirectX Enhancement: 11 Vs. 12 Comparison Guide"
date: 2024-08-08T09:17:29.122Z
updated: 2024-08-09T09:17:29.122Z
tags:
  - games
categories:
  - games
description: "This Article Describes DirectX Enhancement: 11 Vs. 12 Comparison Guide"
excerpt: "This Article Describes DirectX Enhancement: 11 Vs. 12 Comparison Guide"
keywords: DirectX11VS12Comparison,DXEnhancementGuide12,GraphicsAPIUpgrade,EnhancedDirectX12,AIOptionsInDX12,VisualTechAdvances,DirectXPerformanceBoost
thumbnail: https://thmb.techidaily.com/738343d11636524e97e883ecdfb55ee8c179338e8409002b7334f65b8debc634.jpg
---

## DirectX Enhancement: 11 Vs. 12 Comparison Guide

 DirectX 12 was released alongside Windows 10 in 2015\. With its release, Microsoft's DirectX 12 ushered in a new era for gamers and game developers. Capable of reducing CPU overhead while boosting GPU performance, DirectX 12 quickly made a name for itself.

 However, is increasing your performance really as simple as switching from DirectX 11 to DirectX 12? Let's find out by looking at the differences between DirectX 11 and 12.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is Microsoft's DirectX?

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![DirectX logo imposed on a photo of a man coding](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-1.jpg)

 As explained in[our overview of Microsoft DirectX](https://www.makeuseof.com/tag/everything-need-know-directx-2016/) , DirectX is a collection of application programming interfaces (APIs) used for handling tasks related to multimedia. This includes game programming on Microsoft-based platforms like Windows and Xbox. To provide some context, let's briefly talk about APIs.

 An API makes it possible for two or more computer programs to communicate with each other, which we discuss in[our overview of APIs](https://www.makeuseof.com/what-is-api/) . Think of it like a telephone. If your mom texts you with a grocery list, your phone will receive that data and display it for you. That is basically an API.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Are the Differences Between DirectX 11 and DirectX 12?

 So, what are the differences between DirectX 11 and DirectX 12? Put simply, DirectX 12 is the latest version of DirectX. One of the most noticeable differences is how they interact with your hardware. Most games developed with DirectX 11 only utilize between two and four[CPU cores](https://www.makeuseof.com/cpu-vs-vcpu-threads-vs-cores/) . One of these cores usually tells the GPU what to do.

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

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read[our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-charting-the-undisclosed-territories-of-youtube-videos/"><u>[New] 2024 Approved  Charting the Undisclosed Territories of YouTube Videos</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-top-10-tiktok-viral-videos-on-twitter/"><u>[New] 2024 Approved  Top 10 TikTok Viral Videos on Twitter</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ow-to-insert-youtube-playlists-seamlessly-into-a-website-for-2024/"><u>[New] How to Insert YouTube Playlists Seamlessly Into a Website for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-kiddie-koala-race-relays/"><u>[New] In 2024, Kiddie Koala Race Relays</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-learn-how-to-convert-audio-clips-into-written-text-with-microsoft-words-speech-recognition-features/"><u>[New] Learn How To Convert Audio Clips Into Written Text with Microsoft Word's Speech Recognition Features</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-secret-to-exceptional-instagram-reels/"><u>[New] The Secret to Exceptional Instagram Reels</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-gif-galore-converting-tweet-videos-at-zero-cost/"><u>[Updated] 2024 Approved  GIF Galore  Converting Tweet Videos at Zero Cost</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-a-step-by-step-guide-to-youtube-stats-analysis-via-social-blade-platform-for-2024/"><u>[Updated] A Step-by-Step Guide to YouTube Stats Analysis via Social Blade Platform for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-blueprint-for-producing-high-impact-youtube-videos/"><u>[Updated] The Blueprint for Producing High-Impact YouTube Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-guide-to-using-telegram-web-effectively/"><u>[Updated] The Ultimate Guide to Using Telegram Web Effectively</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-elite-uploader-mp4-files-directly-for-fb/"><u>2024 Approved  Elite Uploader  MP4 Files Directly for FB</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-leveraging-wirecast-technology-for-dynamic-youtube-live-experiences/"><u>2024 Approved  Leveraging WireCast Technology for Dynamic Youtube Live Experiences</u></a></li>
<li><a href="https://games-able.techidaily.com/3-quick-fixes-for-recognizing-unplugged-headsets-on-xbox/"><u>3 Quick Fixes for Recognizing Unplugged Headsets on Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/a-snapshot-of-fun-exploring-netflix-mobile-games/"><u>A Snapshot of Fun: Exploring Netflix Mobile Games</u></a></li>
<li><a href="https://games-able.techidaily.com/a-tale-of-windows-and-steamos-harmony-on-a-single-chip/"><u>A Tale of Windows & SteamOS Harmony on a Single Chip</u></a></li>
<li><a href="https://games-able.techidaily.com/accessing-xbox-features-without-a-cont/"><u>Accessing Xbox Features Without a Cont</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-and-solving-joy-con-connectivity-problems-on-switch/"><u>Addressing and Solving Joy-Con Connectivity Problems on Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-unresponsive-display-drivers-on-windows-11-systems/"><u>Addressing Unresponsive Display Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/ally-x-endgame-for-handheld-tech-predicaments/"><u>Ally X: Endgame for Handheld Tech Predicaments</u></a></li>
<li><a href="https://games-able.techidaily.com/analyzing-technical-specs-of-asus-rog-ally-and-steam-deck/"><u>Analyzing Technical Specs of ASUS ROG Ally and Steam Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/appreciating-google-play-pass-yet-its-flaw-remains/"><u>Appreciating Google Play Pass, Yet Its Flaw Remains</u></a></li>
<li><a href="https://games-able.techidaily.com/are-desktops-by-apple-outgrowing-traditional-pcs/"><u>Are Desktops by Apple Outgrowing Traditional PCs?</u></a></li>
<li><a href="https://games-able.techidaily.com/are-we-witnessing-the-onset-of-gpu-expensive-era/"><u>Are We Witnessing the Onset of GPU Expensive Era?</u></a></li>
<li><a href="https://games-able.techidaily.com/augment-gameplay-efficiency-unlocking-secrets-to-android-fps-measurement/"><u>Augment Gameplay Efficiency: Unlocking Secrets to Android FPS Measurement</u></a></li>
<li><a href="https://games-able.techidaily.com/awesome-google-play-pass-but-not-without-drawbacks/"><u>Awesome Google Play Pass, But Not Without Drawbacks</u></a></li>
<li><a href="https://games-able.techidaily.com/balancing-subscriptions-the-smart-xbox-players-way/"><u>Balancing Subscriptions: The Smart Xbox Player's Way</u></a></li>
<li><a href="https://games-able.techidaily.com/battle-of-the-giants-opera-gx-vs-microsofts-edge-browser/"><u>Battle of the Giants: Opera GX vs Microsoft's Edge Browser</u></a></li>
<li><a href="https://games-able.techidaily.com/behind-the-screen-finding-ps5s-silent-browser/"><u>Behind the Screen: Finding PS5's Silent Browser</u></a></li>
<li><a href="https://games-able.techidaily.com/best-practices-for-xbox-membership-juggling-on-x/"><u>Best Practices for Xbox Membership Juggling on X</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/cross-platform-chumming-discord-friend-guide/"><u>Cross-Platform Chumming  Discord Friend Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/1719165682129-discover-the-greatest-online-fps-browser-gaming-experiences/"><u>Discover the Greatest Online FPS Browser Gaming Experiences</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/discovering-the-best-in-class-9-microphone-recorders-reviewed-for-2024/"><u>Discovering the Best in Class  9 Microphone Recorders Reviewed for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-nokia-c12-s-lock-screen-pattern-pin-or-password-by-drfone-android-unlock-android-unlock/"><u>How to bypass Nokia C12’s lock screen pattern, PIN or password</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-8-apples-new-iphone-drfone-by-drfone-ios/"><u>How to Unlock iPhone 8, Apples New iPhone | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-oppo-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Oppo to Protect Your Individual Information</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-10-password-cracking-tools-for-samsung-galaxy-s24plus-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Samsung Galaxy S24+</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169318737-revolutionize-game-boy-handhents-on-your-mobile-device/"><u>Revolutionize Game Boy Handhents on Your Mobile Device!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168719205-sonys-summer-gaming-extravaganza-essential-picks/"><u>Sony’s Summer Gaming Extravaganza: Essential Picks</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170047754-the-premier-game-boy-simulators-for-iphone-and-ipad/"><u>The Premier Game Boy Simulators for iPhone & iPad</u></a></li>
</ul></div>

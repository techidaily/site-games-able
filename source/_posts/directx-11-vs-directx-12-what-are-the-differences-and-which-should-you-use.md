---
title: "DirectX 11 Vs. DirectX 12: What Are the Differences and Which Should You Use?"
date: 2024-08-31T19:26:31.111Z
updated: 2024-09-01T19:26:31.111Z
tags:
  - games
categories:
  - games
description: "This Article Describes DirectX 11 Vs. DirectX 12: What Are the Differences and Which Should You Use?"
excerpt: "This Article Describes DirectX 11 Vs. DirectX 12: What Are the Differences and Which Should You Use?"
keywords: DirectX 12 Vs. DirectX 11,DirectX Comparison,Gaming Graphics Upgrade,DirectX Latest Version,Graphics API Differences,Optimal DirectX Choice,High-Performance Rendering
thumbnail: https://thmb.techidaily.com/68fb059a648e909d234d3bab20298ad1bdfcbd57c7ecdd3b24dbb573f2037e37.jpg
---

## DirectX 11 Vs. DirectX 12: What Are the Differences and Which Should You Use?

 DirectX 12 was released alongside Windows 10 in 2015\. With its release, Microsoft's DirectX 12 ushered in a new era for gamers and game developers. Capable of reducing CPU overhead while boosting GPU performance, DirectX 12 quickly made a name for itself.

 However, is increasing your performance really as simple as switching from DirectX 11 to DirectX 12? Let's find out by looking at the differences between DirectX 11 and 12.

## What Is Microsoft's DirectX?

![DirectX logo imposed on a photo of a man coding](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-1.jpg)

 As explained in[our overview of Microsoft DirectX](https://www.makeuseof.com/tag/everything-need-know-directx-2016/) , DirectX is a collection of application programming interfaces (APIs) used for handling tasks related to multimedia. This includes game programming on Microsoft-based platforms like Windows and Xbox. To provide some context, let's briefly talk about APIs.

 An API makes it possible for two or more computer programs to communicate with each other, which we discuss in[our overview of APIs](https://www.makeuseof.com/what-is-api/) . Think of it like a telephone. If your mom texts you with a grocery list, your phone will receive that data and display it for you. That is basically an API.

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

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read[our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/updated-viral-visions-top-ig-story-filters-for-2024/"><u>[Updated] Viral Visions  Top IG Story Filters for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/439-refresh-monitor-innocn-39g1-r/"><u>$439 Refresh Monitor: InnoCN 39G1 R</u></a></li>
<li><a href="https://games-able.techidaily.com/2-year-tale-why-i-prefer-an-oled-monitor/"><u>2-Year Tale: Why I Prefer an OLED Monitor</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-the-ultimate-guide-to-fostering-viewer-commitment-in-youtube-videos/"><u>2024 Approved  The Ultimate Guide to Fostering Viewer Commitment in YouTube Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/6-factors-to-contemplate-when-comparing-mac-and-pc-games/"><u>6 Factors to Contemplate When Comparing Mac and PC Games</u></a></li>
<li><a href="https://games-able.techidaily.com/7-activision-blizzard-games-microsoft-should-revive/"><u>7 Activision Blizzard Games Microsoft Should Revive</u></a></li>
<li><a href="https://games-able.techidaily.com/7-steps-to-prevent-incompatibility-in-your-new-computer-buy/"><u>7 Steps to Prevent Incompatibility in Your New Computer Buy</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-look-at-riots-username-and-slogan-change/"><u>A Comprehensive Look at Riot's Username and Slogan Change</u></a></li>
<li><a href="https://games-able.techidaily.com/accelerating-games-optimal-3d-model-techniques/"><u>Accelerating Games: Optimal 3D Model Techniques</u></a></li>
<li><a href="https://games-able.techidaily.com/adapt-overcome-playing-fortnite-on-your-mac-wisely/"><u>Adapt, Overcome: Playing Fortnite on Your Mac Wisely</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-unauthorized-card-error-messages-in-ps5/"><u>Addressing Unauthorized Card Error Messages in PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-windows-1011-oculus-not-responding/"><u>Addressing Windows 10/11: Oculus Not Responding</u></a></li>
<li><a href="https://games-able.techidaily.com/adjusting-settings-for-superior-steam-deck-typing/"><u>Adjusting Settings for Superior Steam Deck Typing</u></a></li>
<li><a href="https://games-able.techidaily.com/advanced-uv-filtering-gamewear/"><u>Advanced UV Filtering Gamewear</u></a></li>
<li><a href="https://games-able.techidaily.com/alleviating-cross-platform-steam-errors/"><u>Alleviating Cross-Platform Steam Errors</u></a></li>
<li><a href="https://games-able.techidaily.com/amds-new-tech-fsr-3-in-the-ring-with-nvidias-advanced-dlss-35/"><u>AMD’s New Tech FSR 3 in the Ring with NVIDIA's Advanced DLSS 3.5?</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171377590-avoid-stability-issues-install-updated-nvidia-graphics-driver-today/"><u>Avoid Stability Issues - Install Updated Nvidia Graphics Driver Today</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-overheat-gaming-card-temperature-tips/"><u>Avoiding Overheat: Gaming Card Temperature Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/become-a-word-game-virtuoso-mastering-strands-new-york-times-edition/"><u>Become a Word Game Virtuoso: Mastering Strands, New York Times Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/bedrock-servers-joining-java-via-cross-server-gateway-geysermc/"><u>Bedrock Servers Joining Java via Cross-Server Gateway, GeyserMC</u></a></li>
<li><a href="https://games-able.techidaily.com/best-gaming-ears-for-nintendo-switch/"><u>Best Gaming Ears for Nintendo Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160580017-craftsmads-and-fun-try-larger-arcade-cabinet-framing/"><u>Craftsmads and Fun: Try Larger Arcade Cabinet Framing</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169904091-digital-discounts-on-xbox-series-xs-unlocked/"><u>Digital Discounts on Xbox Series X|S Unlocked</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170572779-download-platforms-for-bg3-unveiled/"><u>Download Platforms for BG3 Unveiled</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-fixes-how-to-recover-forgotten-icloud-password-on-your-iphone-7-by-drfone-ios/"><u>Easy Fixes How To Recover Forgotten iCloud Password On your iPhone 7</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169877451-embrace-free-football-fun-old-championship-manager-windows-edition/"><u>Embrace Free Football Fun: Old Championship Manager, Windows Edition!</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/enhancing-productivity-zoom-features-for-windows-users-win10-for-2024/"><u>Enhancing Productivity  Zoom Features for Windows Users (Win10) for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172752956-game-boy-advance-excellence-with-ioss-leading-emulators/"><u>Game Boy Advance Excellence with iOS's Leading Emulators!</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/how-to-broadcast-videos-on-twitter-without-the-retweet-step-for-2024/"><u>How To Broadcast Videos on Twitter without the 'Retweet' Step for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/how-to-download-and-install-broadcom-bluetooth-driver-on-windows-1087/"><u>How to Download and Install Broadcom Bluetooth Driver on Windows 10/8/7</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/issues-playing-h265-hevc-video-on-samsung-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Issues playing H.265 HEVC video on Samsung</u></a></li>
<li><a href="https://win-able.techidaily.com/master-your-chat-experience-ending-discord-lags/"><u>Master Your Chat Experience: Ending Discord Lags</u></a></li>
<li><a href="https://data-wizards.techidaily.com/proven-mysql-recovery-strategies-demonstrated-in-video-with-augusto/"><u>Proven MySql Recovery Strategies Demonstrated in Video with Augusto</u></a></li>
<li><a href="https://games-able.techidaily.com/1719165662348-revive-gbadvance-games-seamlessly-on-iphone-and-ipad/"><u>Revive GBAdvance Games Seamlessly on iPhone & iPad!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719160130709-rewind-to-retro-play-psp-on-iphone-today/"><u>Rewind to Retro: Play PSP on iPhone Today</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168257558-step-into-the-fun-zone-engage-with-these-6-chatgpt-games/"><u>Step Into the Fun Zone: Engage With These 6 ChatGPT Games</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/unlock-free-solutions-for-repairing-corrupted-photographic-files-easily/"><u>Unlock Free Solutions for Repairing Corrupted Photographic Files Easily</u></a></li>
</ul></div>

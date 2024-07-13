---
title: "Gaming Graphic Shift: XNA's Next-Gen Hurdle"
date: 2024-07-12T03:57:00.920Z
updated: 2024-07-13T03:57:00.920Z
tags:
  - games
categories:
  - games
description: "This Article Describes Gaming Graphic Shift: XNA's Next-Gen Hurdle"
excerpt: "This Article Describes Gaming Graphic Shift: XNA's Next-Gen Hurdle"
keywords: XNA Graphics Update,Gaming Visual Evolution,Next-Gen Game Challenges,Graphic Transition in Games,XNA Development Shift,New Gaming Graphics Trend,Navigating XNA's Upgrade
thumbnail: https://thmb.techidaily.com/73f237caff1293d1dd4178031db987cf4821ccb81a94a966ce0f48ea51b79037.jpg
---

## Gaming Graphic Shift: XNA's Next-Gen Hurdle

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
<li><a href="https://games-able.techidaily.com/steps-for-dealing-with-nonfunctional-switch-situations/"><u>Steps for Dealing with Nonfunctional Switch Situations</u></a></li>
<li><a href="https://games-able.techidaily.com/fight-game-interface-console-vs-arcade-joysticks/"><u>Fight Game Interface: Console Vs. Arcade Joysticks</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-the-ultimate-list-top-10-4k-video-converter-tools-free-and-paid/"><u>New The Ultimate List Top 10 4K Video Converter Tools (Free & Paid)</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-best-ios-slow-motion-apps-to-work-with/"><u>New 2024 Approved Best iOS Slow Motion Apps To Work With</u></a></li>
<li><a href="https://games-able.techidaily.com/from-silver-to-core-xbox-live-gold-upgrade/"><u>From Silver to Core: Xbox Live Gold Upgrade</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-infinix-hot-40-pro-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-3-ways-to-get-rid-of-echo-in-your-audio-recordings/"><u>Updated 3 Ways to Get Rid of Echo in Your Audio Recordings</u></a></li>
<li><a href="https://games-able.techidaily.com/diagnosing-and-solving-gpu-induced-image-droop/"><u>Diagnosing & Solving GPU-Induced Image Droop</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-recovery-addressing-common-series-sandx-problems/"><u>Xbox Recovery: Addressing Common Series S&X Problems</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-wrongful-oled-purchases-with-these-tips/"><u>Avoid Wrongful OLED Purchases with These Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/the-intricacies-of-twitch-from-basics-to-broadcasting/"><u>The Intricacies of Twitch: From Basics to Broadcasting</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-adding-frames-to-instagram-videos-3-procedures/"><u>2024 Approved  Adding Frames to Instagram Videos - 3 Procedures</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-the-ultimate-list-top-10-free-video-trimmers-for-windows-10-for-2024/"><u>New The Ultimate List Top 10 Free Video Trimmers for Windows 10 for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unlocking-rokus-potential-with-facebook-live-streaming-for-2024/"><u>[Updated] Unlocking Roku's Potential with Facebook Live Streaming for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/secure-access-to-more-gaming-with-xbox-ultimate/"><u>Secure Access to More Gaming with Xbox Ultimate</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-instagram-success-secrets-8-steps-to-becoming-a-top-poster/"><u>2024 Approved  Instagram Success Secrets  8 Steps to Becoming a Top Poster</u></a></li>
<li><a href="https://games-able.techidaily.com/the-art-of-curating-ps5-gaming-membership-benefits/"><u>The Art of Curating PS5 Gaming Membership Benefits</u></a></li>
<li><a href="https://games-able.techidaily.com/eliminating-steam-cloud-connectivity-fails/"><u>Eliminating Steam Cloud Connectivity Fails</u></a></li>
<li><a href="https://games-able.techidaily.com/combatting-ps5-intermittent-connection-issues/"><u>Combatting PS5 Intermittent Connection Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/xbox-to-steam-playing-game-pass-games-with-glossi-integration/"><u>Xbox to Steam: Playing Game Pass Games with GlosSI Integration</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-budget-drone-options-that-dont-sacrifice-quality-for-2024/"><u>[Updated] Budget Drone Options That Don't Sacrifice Quality for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/demystifying-steams-metrics-insights-on-playtime-and-points-earned/"><u>Demystifying Steam's Metrics: Insights on Playtime and Points Earned</u></a></li>
<li><a href="https://games-able.techidaily.com/combatting-absentee-gps-on-pokemon-adventure-paths/"><u>Combatting Absentee GPS on Pokémon Adventure Paths</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-choice-of-luminous-screen-shields/"><u>Ultimate Choice of Luminous Screen Shields</u></a></li>
<li><a href="https://games-able.techidaily.com/skillful-strokes-rhythm-games-on-tablets/"><u>Skillful Strokes: Rhythm Games on Tablets</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-by-step-guide-for-a-supercharged-ps4-experience/"><u>A Step-by-Step Guide for a Supercharged PS4 Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/the-next-generation-in-handheld-computing/"><u>The Next Generation in Handheld Computing</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-samsung-galaxy-a34-5g-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Samsung Galaxy A34 5G Location | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-to-choosing-a-budget-friendly-1440p-gaming-monitor/"><u>The Ultimate Guide to Choosing a Budget-Friendly 1440P Gaming Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/identifying-the-most-critical-gaming-mouse-qualities-with-ease/"><u>Identifying the Most Critical Gaming Mouse Qualities with Ease</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-boosting-social-impact-with-the-combined-force-of-youtube-and-instagram-stories/"><u>[Updated] Boosting Social Impact with the Combined Force of YouTube and Instagram Stories</u></a></li>
<li><a href="https://games-able.techidaily.com/the-top-ranked-gaming-chairs-for-heavyset-heroes/"><u>The Top-Ranked Gaming Chairs for Heavyset Heroes</u></a></li>
<li><a href="https://games-able.techidaily.com/discontinued-games-beyond-your-psp-network/"><u>Discontinued Games: Beyond Your PSP Network</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-fast-track-to-fandom-top-30-engaging-nicknames-for-discord/"><u>[New] 2024 Approved  Fast Track to Fandom  Top 30 Engaging Nicknames for Discord</u></a></li>
<li><a href="https://games-able.techidaily.com/high-fidelity-play-choosing-the-best-144hz-uwds/"><u>High-Fidelity Play: Choosing the Best 144Hz UWDs</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-nintendo-switch-cartridge-holders-of-2024/"><u>The Best Nintendo Switch Cartridge Holders of 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/storing-retro-games-in-windows-11-mypics/"><u>Storing Retro Games in Windows 11 MyPics</u></a></li>
<li><a href="https://games-able.techidaily.com/battle-royale-retrogaming-on-rpi-with-batocera-and-retropie/"><u>Battle Royale: RetroGaming on RPi with Batocera and RetroPie</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-rapid-share-tactics-for-youtube-lists/"><u>[New] 2024 Approved  Rapid Share Tactics for YouTube Lists</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-fix-the-0x887a0006-dxgierrordevicehung-error-in-windows-10-and-11/"><u>How to Fix the 0X887A0006: DXGI_ERROR_DEVICE_HUNG Error in Windows 10 & 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-creating-cinematic-experiences-a-guide-to-adding-and-tweaking-background-sounds-with-filmora-for-2024/"><u>New Creating Cinematic Experiences A Guide to Adding and Tweaking Background Sounds with Filmora for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/apples-game-mode-revolutionizing-mac-gaming-on-sonoma-os/"><u>Apple’s Game Mode – Revolutionizing Mac Gaming on Sonoma OS</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-to-game-changing-keyboards/"><u>The Ultimate Guide to Game-Changing Keyboards</u></a></li>
<li><a href="https://games-able.techidaily.com/analyzing-the-cost-dynamics-in-game-purchases-on-steam/"><u>Analyzing the Cost Dynamics in Game Purchases on Steam</u></a></li>
<li><a href="https://extra-tips.techidaily.com/amplify-iphone-film-and-photo-experience-with-extra-gear/"><u>Amplify iPhone Film & Photo Experience with Extra Gear</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-collect-and-leverage-steam-credits/"><u>How to Collect and Leverage Steam Credits</u></a></li>
<li><a href="https://games-able.techidaily.com/dealing-with-steams-erratic-content-loading/"><u>Dealing with Steam's Erratic Content Loading</u></a></li>
<li><a href="https://games-able.techidaily.com/step-by-step-adding-sd-to-steam-deck/"><u>Step-by-Step: Adding SD to Steam Deck</u></a></li>
<li><a href="https://fix-guide.techidaily.com/realme-11-proplus-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Realme 11 Pro+ Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ticklishtunes-your-guide-to-amusing-ringtone-downloads/"><u>2024 Approved  TicklishTunes  Your Guide to Amusing Ringtone Downloads</u></a></li>
<li><a href="https://games-able.techidaily.com/silence-the-chaos-3-solutions-for-clearer-xbox-audio/"><u>Silence the Chaos: 3 Solutions for Clearer Xbox Audio</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-xsplit-direct-insight-and-evaluation-guide/"><u>[Updated] 2024 Approved  XSplit Direct  Insight & Evaluation Guide</u></a></li>
</ul></div>

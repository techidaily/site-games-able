---
title: "DirectX Progress: XNA Series Edition"
date: 2024-07-12T03:48:37.988Z
updated: 2024-07-13T03:48:37.988Z
tags:
  - games
categories:
  - games
description: "This Article Describes DirectX Progress: XNA Series Edition"
excerpt: "This Article Describes DirectX Progress: XNA Series Edition"
keywords: DirectX Progess XNA,XNA Series Updates,XNA Game Development,Next-Gen Gaming Tools,XNA Platform Enhancements,XNA Game Libraries,Advanced Graphics in XNA
thumbnail: https://thmb.techidaily.com/3dae50570edf845253cb7d1a2a03642e6fd28847b0566a64ae5bae28165ba633.jpg
---

## DirectX Progress: XNA Series Edition

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
<li><a href="https://games-able.techidaily.com/unveiling-game-tech-that-really-counts/"><u>Unveiling Game Tech That Really Counts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-in-depth-tutorial-for-gameplay-recorders-on-win10/"><u>[New] 2024 Approved  In-Depth Tutorial for Gameplay Recorders on Win10</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-potential-a-guide-to-all-steam-awards/"><u>Unlocking Potential: A Guide to All Steam Awards</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-free-video-editing-software-round-up-choose-from-7-options/"><u>In 2024, Free Video Editing Software Round-Up  Choose From 7 Options</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-tecno-spark-20-pro-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Tecno Spark 20 Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://games-able.techidaily.com/workstations-for-work-consoles-for-games-a-look/"><u>Workstations for Work, Consoles for Games: A Look</u></a></li>
<li><a href="https://games-able.techidaily.com/restore-your-xbox-series-xands-repair-tips/"><u>Restore Your Xbox: Series X&S Repair Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/retroid-pocket-3plus-the-handbag-sized-retro-gaming-console/"><u>Retroid Pocket 3+: The Handbag-Sized Retro Gaming Console</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-the-compact-guide-to-the-hottest-tiktok-recommended-books/"><u>[New] The Compact Guide to the Hottest TikTok-Recommended Books</u></a></li>
<li><a href="https://games-able.techidaily.com/the-role-of-technology-in-modern-map-making-eg-gis-systems-digital-cartography/"><u>The Role of Technology in Modern Map-Making (E.g., GIS Systems, Digital Cartography);</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-keeping-your-game-passes-in-check-on-xsx/"><u>Tips for Keeping Your Game Passes in Check on XS/X</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-optimizing-youtube-and-twitch-with-obs-streaming-techniques/"><u>[New] Optimizing YouTube & Twitch with OBS Streaming Techniques</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-capturing-youtube-icons-browser-extension-command-line-and-software-trio/"><u>2024 Approved  Capturing Youtube Icons  Browser Extension, Command Line & Software Trio</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-splitcam-vs-competitors-top-tier-video-recording/"><u>[New] 2024 Approved  SplitCam Vs. Competitors  Top-Tier Video Recording?</u></a></li>
<li><a href="https://games-able.techidaily.com/valves-move-against-exploitative-game-returns/"><u>Valve's Move Against Exploitative Game Returns</u></a></li>
<li><a href="https://games-able.techidaily.com/your-guide-to-exciting-paid-nothing-switch-games/"><u>Your Guide to Exciting, Paid-Nothing Switch Games</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-versus-gog-marketplace-differences-highlighted/"><u>Steam Versus GOG: Marketplace Differences Highlighted</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-4-methods-how-to-make-a-recap-video-for-2024/"><u>New 4 Methods How To Make a Recap Video for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/reclaim-your-games-sound-with-easy-fixes-on-console/"><u>Reclaim Your Game's Sound with Easy Fixes on Console</u></a></li>
<li><a href="https://games-able.techidaily.com/switch-to-smoothness-wi-fi-fixes-guide/"><u>Switch to Smoothness: Wi-Fi Fixes Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-fixes-for-steam-authentication-failures-in-rust/"><u>Quick Fixes for Steam Authentication Failures in Rust</u></a></li>
<li><a href="https://games-able.techidaily.com/play-smart-why-you-shouldnt-use-mic-on-ps5-controller/"><u>Play Smart: Why You Shouldn't Use Mic on PS5 Controller</u></a></li>
<li><a href="https://games-able.techidaily.com/selecting-the-right-input-devices-for-gamers/"><u>Selecting the Right Input Devices for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/optimizing-your-streaming-experience-with-top-vod-tools/"><u>Optimizing Your Streaming Experience with Top VOD Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-experts-picks-the-best-10-photography-lenses/"><u>2024 Approved  Expert's Picks  The Best 10 Photography Lenses</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-picsart-guide-discreetly-mask-faces/"><u>[Updated] Picsart Guide  Discreetly Mask Faces</u></a></li>
<li><a href="https://games-able.techidaily.com/slim-tech-meets-colorful-fun-with-tecnos-new-releases/"><u>Slim Tech Meets Colorful Fun with Tecno's New Releases</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-is-your-apple-iphone-7-plus-in-security-lockout-proper-ways-to-unlock-drfone-by-drfone-ios/"><u>In 2024, Is Your Apple iPhone 7 Plus in Security Lockout? Proper Ways To Unlock | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-utilizing-continuous-lights-for-comfortable-filming/"><u>In 2024, Utilizing Continuous Lights for Comfortable Filming</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-uniting-platforms-post-videos-across-twitter-and-tumblr-for-2024/"><u>[New] Uniting Platforms  Post Videos Across Twitter & Tumblr for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719163479927-get-ready-for-youtubes-mini-games-a-call-to-gamers/"><u>Get Ready for YouTube’s Mini Games: A Call to Gamers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-insta-stats-spotlight-pinpointing-viewers-of-your-photos/"><u>[New] Insta Stats Spotlight  Pinpointing Viewers of Your Photos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-navigating-virtual-realms-the-finest-vr-technology/"><u>[New] Navigating Virtual Realms  The Finest VR Technology</u></a></li>
<li><a href="https://games-able.techidaily.com/refund-request-for-unwanted-fortnite-items-step-by-step-guide/"><u>Refund Request for Unwanted Fortnite Items - Step by Step Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/chill-bites-analysis-in-depth-review-of-ice-cream-recorder/"><u>Chill Bites Analysis  In-Depth Review of Ice Cream Recorder</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-revealed-the-best-videos-from-facebooks-pages/"><u>[New] 2024 Approved  Revealed  The Best Videos From Facebook’s Pages</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-issues-with-steams-payment-system/"><u>Resolving Issues with Steam's Payment System</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-top-10-budget-friendly-options-premium-free-podcast-players-for-modern-smartphones-for-2024/"><u>Updated Top 10 Budget-Friendly Options Premium-Free Podcast Players for Modern Smartphones for 2024</u></a></li>
</ul></div>

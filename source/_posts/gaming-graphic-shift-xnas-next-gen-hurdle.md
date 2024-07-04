---
title: "Gaming Graphic Shift: XNA's Next-Gen Hurdle"
date: 2024-06-25T13:21:09.472Z
updated: 2024-06-26T13:21:09.472Z
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
<li><a href="https://games-able.techidaily.com/uncovering-users-on-steam-efficiently/"><u>Uncovering Users on Steam Efficiently</u></a></li>
<li><a href="https://games-able.techidaily.com/flashs-legacy-continues-how-to-keep-playing-post-adobe/"><u>Flash's Legacy Continues: How to Keep Playing Post-Adobe</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-multiplayer-mobile-experiences-unite-friends-anywhere/"><u>Ultimate Multiplayer Mobile Experiences: Unite Friends Anywhere</u></a></li>
<li><a href="https://games-able.techidaily.com/is-amds-fsr-3-technology-a-match-for-dlss-35/"><u>Is AMD's FSR 3 Technology a Match for DLSS 3.5?</u></a></li>
<li><a href="https://games-able.techidaily.com/uncover-the-11-superb-free-word-puzzle-apps-today/"><u>Uncover the 11 Superb Free Word Puzzle Apps Today</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-nvidia-g-sync-for-peak-game-performance/"><u>Understanding Nvidia G-Sync for Peak Game Performance</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-efficiency-and-speed-unlocking-potential-in-your-docked-device/"><u>Boosting Efficiency and Speed: Unlocking Potential in Your Docked Device</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/2024-approved-top-5-mp3-cutters-online/"><u>2024 Approved Top 5 MP3 Cutters Online</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-unveiling-the-best-top-10-for-dating-in-discord/"><u>[Updated] In 2024, Unveiling the Best  Top 10 for Dating in Discord</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-unveiling-instagram-reels-10-surprising-insights/"><u>[New] In 2024, Unveiling Instagram Reels  10 Surprising Insights</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713961432900-updated-are-you-finding-it-challenging-to-upload-and-create-a-link-for-your-video-well-this-detailed-upload-video-to-link-guide-will-help-you-with-this-chec/"><u>Updated Are You Finding It Challenging to Upload and Create a Link for Your Video? Well, This Detailed Upload Video to Link Guide Will Help You with This. Check It Out Now for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/maximizing-sales-crafting-engaging-youtube-channel-trailers/"><u>Maximizing Sales  Crafting Engaging YouTube Channel Trailers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-cut-rate-video-upgrade-turning-fb-videos-into-mp4-hd1080p-for-2024/"><u>[Updated] Cut-Rate Video Upgrade  Turning FB Videos Into MP4 HD/1080P for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-a-comprehensive-guide-to-maximizing-channels-earnings-through-trailers-for-2024/"><u>[Updated] A Comprehensive Guide to Maximizing Channels' Earnings Through Trailers for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/a-comprehensive-guide-to-producing-videos-for-social-media-for-2024/"><u>A Comprehensive Guide to Producing Videos For Social Media for 2024</u></a></li>
</ul></div>

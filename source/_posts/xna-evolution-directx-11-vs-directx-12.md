---
title: "XNA Evolution: DirectX 11 Vs. DirectX 12"
date: 2024-06-25T10:38:30.775Z
updated: 2024-06-26T10:38:30.775Z
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

## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read[our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

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
<li><a href="https://games-able.techidaily.com/connecting-retro-nintendo-games/"><u>Connecting Retro Nintendo Games</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-button-controls-android-games-via-controller-mapping/"><u>Mastering Button Controls: Android Games via Controller Mapping</u></a></li>
<li><a href="https://games-able.techidaily.com/maintaining-talk-order-strategic-use-of-twitch-bansunbans/"><u>Maintaining Talk Order: Strategic Use of Twitch Bans/Unbans</u></a></li>
<li><a href="https://games-able.techidaily.com/retro-controller-enhancing-classic-games/"><u>Retro Controller: Enhancing Classic Games</u></a></li>
<li><a href="https://games-able.techidaily.com/pros-in-the-making-investing-in-high-end-gear/"><u>Pros in the Making: Investing in High-End Gear</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-ea-play-value-for-your-dollar/"><u>Decoding EA Play: Value for Your Dollar</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-1440p-monitors-the-ultimate-gaming-companion/"><u>Affordable 1440P Monitors: The Ultimate Gaming Companion</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-how-to-review-playtime-in-xbox-games/"><u>Unveiling How to Review Playtime in Xbox Games</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-smooth-gameplay-with-regular-ps5-control-resets/"><u>Ensuring Smooth Gameplay with Regular PS5 Control Resets</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-honor-magic-5-lite-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Honor Magic 5 Lite Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-secret-to-stability-overcoming-handheld-videography-challenges/"><u>The Secret to Stability  Overcoming Handheld Videography Challenges</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-nighttime-navigator-tips-for-effortless-evening-shots-for-2024/"><u>[Updated] The Nighttime Navigator  Tips for Effortless Evening Shots for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/the-ultimate-booktok-list-must-read-masterpieces/"><u>The Ultimate BookTok List  Must-Read Masterpieces</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-blazing-lanes-at-sochi-2022-games/"><u>2024 Approved  Blazing Lanes at Sochi 2022 Games</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-ultimate-guide-unpacking-the-secrets-of-du-recorder/"><u>[New] In 2024, Ultimate Guide  Unpacking the Secrets of Du Recorder</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-unlock-more-likes-and-shares-top-30-tiktok-usernames-for-success/"><u>[Updated] 2024 Approved  Unlock More Likes and Shares  Top 30 TikTok Usernames for Success</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-2024-want-to-make-a-meme-gif-heres-how-to-do/"><u>Updated In 2024, Want to Make a Meme GIF? Heres How to Do</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-transform-your-snapchat-soundtrack-easy-changes-in-just-two-steps-for-2024/"><u>[New] Transform Your Snapchat Soundtrack  Easy Changes in Just Two Steps for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-turn-your-twitter-videos-into-listenable-mp3s-for-2024/"><u>[New] Turn Your Twitter Videos Into Listenable MP3s for 2024</u></a></li>
</ul></div>

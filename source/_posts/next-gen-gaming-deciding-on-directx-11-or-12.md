---
title: "Next-Gen Gaming: Deciding on DirectX 11 or 12"
date: 2024-09-29T23:12:02.357Z
updated: 2024-10-02T10:57:12.748Z
tags:
  - games
categories:
  - games
description: "This Article Describes Next-Gen Gaming: Deciding on DirectX 11 or 12"
excerpt: "This Article Describes Next-Gen Gaming: Deciding on DirectX 11 or 12"
keywords: DirectX Choice Guide,Gaming DirectX Update,DX11 vs DX12 Gameplay,Next-Gen Gaming Advancements,Upgrading Graphics APIs,DirectX Development Trends,DX12/DX11 Comparison
thumbnail: https://thmb.techidaily.com/e9efae3ff791fb7b0dc6f1f4f1438b97e5574ba3442154b95456c4348b981cfa.jpg
---

## Next-Gen Gaming: Deciding on DirectX 11 or 12

 DirectX 12 was released alongside Windows 10 in 2015\. With its release, Microsoft's DirectX 12 ushered in a new era for gamers and game developers. Capable of reducing CPU overhead while boosting GPU performance, DirectX 12 quickly made a name for itself.

 However, is increasing your performance really as simple as switching from DirectX 11 to DirectX 12? Let's find out by looking at the differences between DirectX 11 and 12.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2049363/7443" target="_top" id="2049363">
  <img src="//a.impactradius-go.com/display-ad/7443-2049363" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049363/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948891/19272" target="_top" id="1948891">
  <img src="//a.impactradius-go.com/display-ad/19272-1948891" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948891/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886069/19272" target="_top" id="1886069">
  <img src="//a.impactradius-go.com/display-ad/19272-1886069" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886069/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read[our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144274/7443" target="_top" id="2144274">
  <img src="//a.impactradius-go.com/display-ad/7443-2144274" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144274/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-content.techidaily.com/updated-fb-easy-listen-no-pay-required/"><u>[Updated] FB Easy Listen No Pay Required</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-fixed-most-effective-4-solutions-for-iphone-hdr-video-washed-out-in-premiere-pro/"><u>[Updated] In 2024, [Fixed] Most-Effective 4 Solutions for iPhone HDR Video Washed-Out in Premiere Pro</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-sharpening-recording-quality-by-removing-borders/"><u>[Updated] In 2024, Sharpening Recording Quality by Removing Borders</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-motorola-moto-g23-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Motorola Moto G23 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discovering-the-best-value-in-vr-a-deep-dive-into-the-oculus-quest-2-review/"><u>Discovering the Best Value in VR: A Deep Dive Into the Oculus Quest 2 Review</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-discord-effective-installation-methods-for-mac/"><u>Dive Into Discord: Effective Installation Methods for Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/economical-wired-and-membrane-pc-keys/"><u>Economical Wired and Membrane PC Keys</u></a></li>
<li><a href="https://games-able.techidaily.com/engaging-screen-time-with-netflix-mobile-adventures/"><u>Engaging Screen Time with Netflix Mobile Adventures</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-tips-for-ps5-assist-controller-setup/"><u>Essential Tips for PS5 Assist Controller Setup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-advice-for-multi-monitor-setup-with-any-computer/"><u>Expert Advice for Multi-Monitor Setup with Any Computer</u></a></li>
<li><a href="https://games-able.techidaily.com/from-your-pc-to-the-cloud-play-with-xbox-anywhere/"><u>From Your PC to The Cloud – Play with Xbox Anywhere</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-infinix-hot-40-pro-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Infinix Hot 40 Pro to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/is-there-a-shift-towards-apple-computers-for-gamers/"><u>Is There a Shift Towards Apple Computers for Gamers?</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-lava-blaze-2-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Lava Blaze 2 Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/step-by-step-troubleshooting-making-the-rockstar-games-launcher-work-again/"><u>Step-by-Step Troubleshooting: Making the Rockstar Games Launcher Work Again</u></a></li>
<li><a href="https://games-able.techidaily.com/the-gamers-choice-redefined-with-razers-v4-innovation/"><u>The Gamer’s Choice Redefined with Razer's V4 Innovation</u></a></li>
</ul></div>


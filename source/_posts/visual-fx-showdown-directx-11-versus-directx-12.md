---
title: "Visual FX Showdown: DirectX 11 Versus DirectX 12"
date: 2024-09-30T00:49:31.239Z
updated: 2024-10-02T09:28:17.514Z
tags:
  - games
categories:
  - games
description: "This Article Describes Visual FX Showdown: DirectX 11 Versus DirectX 12"
excerpt: "This Article Describes Visual FX Showdown: DirectX 11 Versus DirectX 12"
keywords: DirectX VFX Comparison,XTech DirectShow,Next-Gen Rendering Tech,FX Graphics Evolution,DX12 vs DX11 Benchmarks,High Performance Graphics,Visual Effects Technology Update
thumbnail: https://thmb.techidaily.com/27d9679823f15c1f840af178653026beb0d15afa85251ef89317616bbcd9f8d8.jpg
---

## Visual FX Showdown: DirectX 11 Versus DirectX 12

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130886/7443" target="_top" id="2130886">
  <img src="//a.impactradius-go.com/display-ad/7443-2130886" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130886/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read[our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1030380/11832" target="_top" id="1030380">
  <img src="//a.impactradius-go.com/display-ad/11832-1030380" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1030380/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-discover-the-creme-de-la-creme-of-mac-snipers/"><u>[New] 2024 Approved Discover the Crème De La Crème of Mac Snipers</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-keep-your-snaps-alive-strategies-for-longevity/"><u>[New] 2024 Approved Keep Your Snaps Alive – Strategies for Longevity</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-from-airplay-to-download-apple-podcasts-simplified/"><u>[New] In 2024, From Airplay to Download Apple Podcasts Simplified</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-leading-the-charge-in-pc-livestreams-with-tiktok-features/"><u>2024 Approved Leading the Charge in PC Livestreams with TikTok Features</u></a></li>
<li><a href="https://fox-http.techidaily.com/augmenting-aerial-mastery-10-essential-drone-accessories-for-2024/"><u>Augmenting Aerial Mastery 10 Essential Drone Accessories for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/automated-marketing-solutions-empower-your-online-presence-with-cookiebot/"><u>Automated Marketing Solutions: Empower Your Online Presence with Cookiebot</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effective-techniques-to-secure-the-newest-radeon-hd-7850-graphic-card-drivers-for-your-windows-11-system/"><u>Effective Techniques to Secure the Newest Radeon HD 7850 Graphic Card Drivers for Your Windows 11 System</u></a></li>
<li><a href="https://games-able.techidaily.com/efficient-control-of-xbox-live-gold-on-xs/"><u>Efficient Control of Xbox Live Gold on XS</u></a></li>
<li><a href="https://games-able.techidaily.com/free-games-that-dont-cost-a-dime-our-top-6/"><u>Free Games That Don't Cost a Dime: Our Top 6</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-install-an-sd-card-on-your-steam-deck/"><u>How to Install an SD Card on Your Steam Deck</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/insta-personality-showcase-100-crafted-caption-ideas/"><u>Insta Personality Showcase - 100 Crafted Caption Ideas</u></a></li>
<li><a href="https://techidaily.com/repair-damaged-unplayable-video-files-of-samsung-galaxy-a05-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair damaged, unplayable video files of Samsung Galaxy A05 on Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/savvy-spending-on-inexpensive-gamer-tech-boards/"><u>Savvy Spending on Inexpensive Gamer Tech Boards</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-overcome-steam-content-unavailable-error/"><u>Steps to Overcome Steam Content Unavailable Error</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-file-sharing-in-steam-for-windows/"><u>Streamlining File Sharing in Steam for Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-audio-advantage-with-proficient-use-of-hrtf-in-valorant/"><u>Unlocking Audio Advantage with Proficient Use of HRTF in Valorant</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-xbox-cloud-gaming-and-how-does-it-work/"><u>What Is Xbox Cloud Gaming and How Does It Work?</u></a></li>
</ul></div>


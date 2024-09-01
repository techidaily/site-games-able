---
title: "Upgrading Games: From DirectX 11 to DirectX 12"
date: 2024-08-31T19:13:09.058Z
updated: 2024-09-01T19:13:09.058Z
tags:
  - games
categories:
  - games
description: "This Article Describes Upgrading Games: From DirectX 11 to DirectX 12"
excerpt: "This Article Describes Upgrading Games: From DirectX 11 to DirectX 12"
keywords: DirectX Shift,DX12 Upgrade,Gaming Performance Boost,Graphics API Evolution,Next-Gen Game Development,Enhanced Visuals DirectX,Graphics Rendering Advance
thumbnail: https://thmb.techidaily.com/a63a5a9ae6eb1efed5733d165b83ad90e6d4d9274b455dfd2cda566223079352.jpg
---

## Upgrading Games: From DirectX 11 to DirectX 12

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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read [our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
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
<li><a href="https://facebook-video-content.techidaily.com/updated-dial-up-dislikes-flip-the-script-with-square-content-creation-for-2024/"><u>[Updated] Dial Up Dislikes? Flip the Script with Square Content Creation for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-pro-tools-for-netflix-capture-a-mac-guide-of-six-strategies-for-2024/"><u>[Updated] Pro Tools for Netflix Capture  A Mac Guide of Six Strategies for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unpacking-the-advanced-capabilities-of-movavi-video-editor-2024plus/"><u>[Updated] Unpacking the Advanced Capabilities of Movavi Video Editor 2024+</u></a></li>
<li><a href="https://games-able.techidaily.com/easily-outsmart-xbox-game-pass-cost-climb-temporarily/"><u>Easily Outsmart Xbox Game Pass Cost Climb, Temporarily</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-to-new-heights-with-big-box-cabinetry/"><u>Elevate to New Heights with Big Box Cabinetry</u></a></li>
<li><a href="https://games-able.techidaily.com/escape-the-gaming-gridlock-minecraft-world-exportation/"><u>Escape the Gaming Gridlock: Minecraft World Exportation</u></a></li>
<li><a href="https://tech-revival.techidaily.com/freely-speaking-a-guide-to-gpt-without-boundaries/"><u>Freely Speaking: A Guide to GPT without Boundaries</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-on-the-go-nintendos-new-era/"><u>Gaming on the Go, Nintendo's New Era?</u></a></li>
<li><a href="https://games-able.techidaily.com/how-paying-players-for-dev-work-may-backfire-long-term/"><u>How Paying Players for Dev Work May Backfire Long Term</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-realme-c51-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Realme C51 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-vivo-v27-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Vivo V27 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-aesthetic-innovations-showcase/"><u>In 2024, Aesthetic Innovations Showcase</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-on-iphone-6s-plus-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock On iPhone 6s Plus - 4 Easy Ways</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-exploring-the-infinite-a-look-at-lgs-vr-technology/"><u>In 2024, Exploring the Infinite  A Look at LG's VR Technology</u></a></li>
<li><a href="https://games-able.techidaily.com/inside-javas-top-rated-games-and-their-features/"><u>Inside Java's Top-Rated Games and Their Features</u></a></li>
<li><a href="https://games-able.techidaily.com/is-it-more-important-to-upgrade-your-cpu-or-gpu-first/"><u>Is It More Important to Upgrade Your CPU or GPU First?</u></a></li>
<li><a href="https://games-able.techidaily.com/is-it-time-for-graphics-cards-to-get-more-expensive/"><u>Is It Time for Graphics Cards to Get More Expensive?</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/jotting-down-just-a-minute-movie/"><u>Jotting Down Just a Minute Movie</u></a></li>
<li><a href="https://games-able.techidaily.com/keychrons-pioneering-leap-introducing-lemokey-l3/"><u>Keychron's Pioneering Leap: Introducing Lemokey L3</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-best-of-the-best-10-free-whiteboard-animation-software-for-pc-and-mac-for-2024/"><u>New Best of the Best 10 Free Whiteboard Animation Software for PC and Mac for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/next-gen-frame-retrieval-techniques-for-any-graphics-card/"><u>Next-Gen Frame Retrieval Techniques for Any Graphics Card</u></a></li>
<li><a href="https://games-able.techidaily.com/nostalgia-unleashed-androids-dreamcatcher-adventures/"><u>Nostalgia Unleashed: Android's Dreamcatcher Adventures</u></a></li>
<li><a href="https://games-able.techidaily.com/nostalgiaport-compact-classic-console-experience/"><u>NostalgiaPort: Compact, Classic Console Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/origins-and-ownership-foddian-gaming/"><u>Origins and Ownership: Foddian Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-joy-con-jitter-on-xbox-one/"><u>Overcoming Joy-Con Jitter on Xbox One</u></a></li>
<li><a href="https://games-able.techidaily.com/pioneering-new-consoles-with-a-retro-sensibility/"><u>Pioneering New Consoles with a Retro Sensibility</u></a></li>
<li><a href="https://win11-tips.techidaily.com/recovering-d3dx939dll-error-on-win11/"><u>Recovering D3DX9_39.dll Error on Win11</u></a></li>
<li><a href="https://fox-blue.techidaily.com/speaking-with-flair-empowering-vocal-expression-with-no-cost-software-for-2024/"><u>Speaking with Flair  Empowering Vocal Expression with No-Cost Software for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/spine-support-ergonomic-gaming-chair-hacks/"><u>Spine Support: Ergonomic Gaming Chair Hacks</u></a></li>
<li><a href="https://games-able.techidaily.com/step-up-your-game-selecting-premium-accessories-for-steam-deck-users/"><u>Step Up Your Game: Selecting Premium Accessories for Steam Deck Users</u></a></li>
<li><a href="https://media-tips.techidaily.com/top-9-streaming-platforms-with-current-free-trial-options/"><u>Top 9 Streaming Platforms with Current Free Trial Options</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshooting-and-fixing-xbox-gaming-device-driver-errors-on-multiple-windows-versions/"><u>Troubleshooting and Fixing Xbox Gaming Device Driver Errors on Multiple Windows Versions</u></a></li>
<li><a href="https://games-able.techidaily.com/undisclosed-steam-game-library/"><u>Undisclosed Steam Game Library</u></a></li>
<li><a href="https://change-location.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-vivo-y36-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Vivo Y36? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/why-edge-stands-tall-in-the-browser-wars-gamer-style/"><u>Why Edge Stands Tall in the Browser Wars, Gamer-Style</u></a></li>
</ul></div>

---
title: "GPU's Best Friend: DirectX 11 or 12?"
date: 2024-07-12T03:53:00.717Z
updated: 2024-07-13T03:53:00.717Z
tags:
  - games
categories:
  - games
description: "This Article Describes GPU's Best Friend: DirectX 11 or 12?"
excerpt: "This Article Describes GPU's Best Friend: DirectX 11 or 12?"
keywords: GPU vs DirectX,Graphics API Comparison,DirectX for Gaming,DirectX 11 Pros,DirectX 12 Features,Optimizing Gpu Performance,Choosing Right DirectX
thumbnail: https://thmb.techidaily.com/d11ab69328de06b2bbe702807d8f8d332f02dd668667f50f1987a428d6465f16.jpg
---

## GPU's Best Friend: DirectX 11 or 12?

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
<li><a href="https://games-able.techidaily.com/choose-your-battles-wisely-switches-in-gaming/"><u>Choose Your Battles Wisely: SWITCHES in Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-xboxs-golden-era-via-emulation-on-a-pc/"><u>Exploring Xbox's Golden Era via Emulation on a PC</u></a></li>
<li><a href="https://games-able.techidaily.com/innovative-gaming-unboxing-the-30-top-switch-cartridge-holders-of-2024/"><u>Innovative Gaming - Unboxing the 30 Top Switch Cartridge Holders of 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/guide-to-remove-unwanted-game-data-on-ps5/"><u>Guide to Remove Unwanted Game Data on PS5</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-2024-approved-elevate-your-discord-experience-with-tts/"><u>[New] 2024 Approved  Elevate Your Discord Experience with TTS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-storytelling-success-planning-a-dynamic-marketing-strategy-for-2024/"><u>Instagram Storytelling Success  Planning a Dynamic Marketing Strategy for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-concept-to-completion-selecting-best-vector-editors/"><u>[Updated] From Concept to Completion  Selecting Best Vector Editors</u></a></li>
<li><a href="https://games-able.techidaily.com/building-a-robust-steam-wallet-investment-guide/"><u>Building a Robust Steam Wallet - Investment Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-steams-workshop-for-game-customization/"><u>Mastering Steam's Workshop for Game Customization</u></a></li>
<li><a href="https://games-able.techidaily.com/conquering-windows-11-steam-installation-errors/"><u>Conquering Windows 11 Steam Installation Errors</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-iphones-quintet-of-best-podcast-aides/"><u>[New] IPhone's Quintet of Best Podcast Aides</u></a></li>
<li><a href="https://games-able.techidaily.com/comprehensive-bg3-gear-checklist-and-more/"><u>Comprehensive BG3 Gear Checklist & More</u></a></li>
<li><a href="https://android-location-track.techidaily.com/best-anti-tracker-software-for-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>Best Anti Tracker Software For Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/professional-top-10-hd-webcams-and-buyers-advice-for-2024/"><u>Professional Top 10 HD Webcams & Buyer's Advice for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/ensuring-complete-game-displays-in-epics-library/"><u>Ensuring Complete Game Displays in Epic's Library</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-key-factors-for-a-smart-ps5-buy/"><u>Evaluating Key Factors for a Smart PS5 Buy</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-gaming-hits-with-powerful-hashtag-strategies/"><u>In 2024, Gaming Hits with Powerful Hashtag Strategies</u></a></li>
<li><a href="https://games-able.techidaily.com/cut-out-console-noise-with-ease-on-xbox/"><u>Cut Out Console Noise with Ease on Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/fleeting-online-realms-a-reason-for-concern/"><u>Fleeting Online Realms – A Reason for Concern?</u></a></li>
<li><a href="https://games-able.techidaily.com/duplicating-saved-games-securing-your-digital-artifacts/"><u>Duplicating Saved Games: Securing Your Digital Artifacts</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-from-concept-to-reality-top-7-gadgets-for-metaverse-success/"><u>2024 Approved  From Concept to Reality  Top 7 Gadgets for Metaverse Success</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-steams-sync-shenanigans-on-pc/"><u>Overcoming Steam's Sync Shenanigans on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/excellent-gamer-tracking-apps-review/"><u>Excellent Gamer Tracking Apps Review</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-bars-universal-game-accessibility/"><u>Beyond Bars: Universal Game Accessibility</u></a></li>
<li><a href="https://games-able.techidaily.com/apc-handheld-reinvented-the-pdw4-story/"><u>APC Handheld Reinvented: The PDW4 Story</u></a></li>
<li><a href="https://games-able.techidaily.com/harmonious-device-interaction-via-securely-shared-controls/"><u>Harmonious Device Interaction via Securely Shared Controls</u></a></li>
<li><a href="https://games-able.techidaily.com/conquer-classic-ps3-titles-30-powerful-pc-emulators/"><u>Conquer Classic PS3 Titles: 30 Powerful PC Emulators</u></a></li>
<li><a href="https://games-able.techidaily.com/managing-failed-transactions-on-steam/"><u>Managing Failed Transactions on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/android-companion-emulating-your-favored-dreamcatcher-titles/"><u>Android Companion: Emulating Your Favored Dreamcatcher Titles</u></a></li>
<li><a href="https://games-able.techidaily.com/browsing-for-fun-the-9-intriguing-advantages-and-disadvantages-of-e-games/"><u>Browsing for Fun: The 9 Intriguing Advantages & Disadvantages of E-Games</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-enhance-videos-on-tiktok-with-effective-captions/"><u>[Updated] 2024 Approved  Enhance Videos on TikTok with Effective Captions</u></a></li>
<li><a href="https://games-able.techidaily.com/diminish-xboxs-game-sounds-immediately/"><u>Diminish Xbox's Game Sounds Immediately</u></a></li>
<li><a href="https://some-approaches.techidaily.com/twitter-media-to-music-downloading-and-converting-process-for-2024/"><u>Twitter Media to Music  Downloading & Converting Process for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/cutting-edge-methods-for-recording-presentations/"><u>Cutting Edge Methods for Recording Presentations</u></a></li>
<li><a href="https://games-able.techidaily.com/disassembling-new-controller-firmware-on-series-xs/"><u>Disassembling New Controller Firmware on Series X/S</u></a></li>
<li><a href="https://video-capture.techidaily.com/leading-open-source-screen-recorder-apps-reviewed-for-2024/"><u>Leading Open-Source Screen Recorder Apps Reviewed for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/gamers-hack-finding-the-epic-games-on-apple-arcade/"><u>Gamer's Hack: Finding the Epic Games on Apple Arcade</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-steam-disconnection-issue-on-pc/"><u>Addressing Steam Disconnection Issue on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/cosmic-crafter-navigating-novel-pc-choices/"><u>Cosmic Crafter: Navigating Novel PC Choices</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-12plus-5g-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme 12+ 5G Device</u></a></li>
<li><a href="https://games-able.techidaily.com/is-discords-indolence-identifier-accurate/"><u>Is Discord's Indolence Identifier Accurate?</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-maximize-your-impact-strategic-approaches-to-facebook-bios/"><u>[New] In 2024, Maximize Your Impact  Strategic Approaches to Facebook Bios</u></a></li>
<li><a href="https://games-able.techidaily.com/perfecting-precision-mastering-cs2-on-a-mac-laptop/"><u>Perfecting Precision: Mastering CS2 on a Mac Laptop</u></a></li>
<li><a href="https://games-able.techidaily.com/locating-steam-screenshot-archives/"><u>Locating Steam Screenshot Archives</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-obstacles-for-opening-origins/"><u>Overcoming Obstacles for Opening Origins</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-finally-get-rid-of-games-from-your-steam-account/"><u>How to Finally Get Rid of Games From Your Steam Account</u></a></li>
</ul></div>

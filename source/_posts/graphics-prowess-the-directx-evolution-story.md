---
title: "Graphics Prowess: The DirectX Evolution Story"
date: 2024-07-12T04:05:12.072Z
updated: 2024-07-13T04:05:12.072Z
tags:
  - games
categories:
  - games
description: "This Article Describes Graphics Prowess: The DirectX Evolution Story"
excerpt: "This Article Describes Graphics Prowess: The DirectX Evolution Story"
keywords: DirectX History,Graphics Advancement,DX Tech Evolution,Visual Effects Progress,Rendering Software Update,Game Engine Development,Visual Computing Growth
thumbnail: https://thmb.techidaily.com/227bd0353ed763348ef514468bae7b22e2b22e0109d88910437782328b50ad10.jpg
---

## Graphics Prowess: The DirectX Evolution Story

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
<li><a href="https://screen-recording.techidaily.com/prime-routines-for-mobile-game-screening-for-2024/"><u>Prime Routines for Mobile Game Screening for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/enabling-remote-play-between-console-and-phone/"><u>Enabling Remote Play Between Console and Phone</u></a></li>
<li><a href="https://games-able.techidaily.com/nine-entertaining-text-battles-for-laughs-and-connection/"><u>Nine Entertaining Text Battles for Laughs & Connection</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-comprehensive-guide-to-samsung-photography-suite-2023/"><u>[New] Comprehensive Guide to Samsung Photography Suite, 2023</u></a></li>
<li><a href="https://games-able.techidaily.com/roblox-cheat-code-risks-and-mechanics-insight/"><u>Roblox Cheat Code: Risks and Mechanics Insight</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-sourcing-indie-games-online/"><u>Mastering the Art of Sourcing Indie Games Online</u></a></li>
<li><a href="https://games-able.techidaily.com/gamings-next-leap-directx-11-vs-directx-12/"><u>Gaming's Next Leap: DirectX 11 V/S DirectX 12</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-honor-play-7t-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Honor Play 7T Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-on-infinix-note-30-vip-racing-edition-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to recover deleted photos on Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/puzzle-yourself-through-pesky-gaming-plights/"><u>Puzzle Yourself Through Pesky Gaming Plights</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-tightens-grip-on-irregular-refund-practices/"><u>Steam Tightens Grip on Irregular Refund Practices</u></a></li>
<li><a href="https://games-able.techidaily.com/enhance-gaming-satisfaction-with-secure-switch-identity-controls/"><u>Enhance Gaming Satisfaction with Secure Switch Identity Controls</u></a></li>
<li><a href="https://games-able.techidaily.com/mending-your-ps4-remotes-abrupt-severance-from-pc/"><u>Mending Your PS4 Remote's Abrupt Severance From PC</u></a></li>
<li><a href="https://games-able.techidaily.com/free-games-just-a-click-away-on-series-xs/"><u>Free Games, Just a Click Away on Series X|S</u></a></li>
<li><a href="https://games-able.techidaily.com/n2o-switch-speculations-handheld-future-in-focus/"><u>N2O Switch Speculations - Handheld Future in Focus</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/free-games-galore-top-10-download-sites-for-pc-android-and-tablet/"><u>Free Games Galore Top 10 Download Sites for PC, Android, and Tablet</u></a></li>
<li><a href="https://games-able.techidaily.com/risks-to-game-quality-with-players-funding-dev-work/"><u>Risks to Game Quality with Players Funding Dev Work</u></a></li>
<li><a href="https://games-able.techidaily.com/shining-up-your-guide-to-cleaner-gaming-tech/"><u>Shining Up: Your Guide to Cleaner Gaming Tech</u></a></li>
<li><a href="https://games-able.techidaily.com/scrutinizing-discords-assumption-behind-idle-status/"><u>Scrutinizing Discord’s Assumption Behind Idle Status</u></a></li>
<li><a href="https://games-able.techidaily.com/multiplayer-mastery-the-shift-in-online-game-designs/"><u>Multiplayer Mastery: The Shift in Online Game Designs</u></a></li>
<li><a href="https://games-able.techidaily.com/flawless-facade-on-first-frame-fixing-freeze/"><u>Flawless Facade on First Frame: Fixing Freeze</u></a></li>
<li><a href="https://games-able.techidaily.com/is-focusing-on-steam-rank-important/"><u>Is Focusing on Steam Rank Important?</u></a></li>
<li><a href="https://games-able.techidaily.com/simplifying-steam-problem-solving-in-windows-11-os/"><u>Simplifying Steam Problem Solving in Windows 11 OS</u></a></li>
<li><a href="https://games-able.techidaily.com/historical-heartbeat-discovering-the-best-11-ww2-simulators/"><u>Historical Heartbeat: Discovering the Best 11 WW2 Simulators</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-fix-uneven-displays-caused-by-gpu-issues/"><u>How To Fix Uneven Displays Caused by GPU Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/msi-raider-ge78-gaming-throne-desktop-king/"><u>MSI Raider GE78 Gaming Throne - Desktop King</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-depth-look-at-auditory-cutting-techniques-for-2024/"><u>In-Depth Look at Auditory Cutting Techniques for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-through-error-403-on-roblox-tips-and-tricks-for-windows/"><u>Navigating Through Error 403 on Roblox: Tips and Tricks for Windows</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-ultimate-guide-to-recording-premium-quality-tiktok-footage/"><u>[Updated] Ultimate Guide to Recording Premium Quality TikTok Footage</u></a></li>
<li><a href="https://games-able.techidaily.com/meta-wisdom-in-games-meaning-necessity-and-obedience/"><u>Meta Wisdom in Games: Meaning, Necessity, and Obedience</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-tips-for-editing-your-videos-in-youtube-studio-for-2024/"><u>Essential Tips for Editing Your Videos in YouTube Studio for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/embark-on-epic-journeys-from-your-computer/"><u>Embark on Epic Journeys From Your Computer</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transform-everyday-alerts-into-signature-sounds-with-android-tips-for-2024/"><u>Transform Everyday Alerts Into Signature Sounds with Android Tips for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/save-money-upgrade-games-240hz-displays-specials/"><u>Save Money, Upgrade Games: 240Hz Displays Specials</u></a></li>
<li><a href="https://games-able.techidaily.com/sagittariuss-satisfaction-comfortable-gaming-support/"><u>Sagittarius’s Satisfaction: Comfortable Gaming Support</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-iphone-14-pro-unavailable-issue-with-ease-drfone-by-drfone-ios/"><u>In 2024, How To Fix iPhone 14 Pro Unavailable Issue With Ease | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/from-portable-to-powerhouse-installing-windows-on-steam-deck/"><u>From Portable to Powerhouse: Installing Windows on Steam Deck</u></a></li>
</ul></div>

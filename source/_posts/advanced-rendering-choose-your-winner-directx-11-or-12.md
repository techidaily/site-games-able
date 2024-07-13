---
title: "Advanced Rendering: Choose Your Winner - DirectX 11 or 12?"
date: 2024-07-12T04:23:38.644Z
updated: 2024-07-13T04:23:38.644Z
tags:
  - games
categories:
  - games
description: "This Article Describes Advanced Rendering: Choose Your Winner - DirectX 11 or 12?"
excerpt: "This Article Describes Advanced Rendering: Choose Your Winner - DirectX 11 or 12?"
keywords: DirectX Comparison,DX11 vs DX12 Benefits,Advanced Graphics Tech,Rendering Technology Trends,Next-Gen Gaming APIs,High-End Visuals in Games,Optimal DirectX Choice
thumbnail: https://thmb.techidaily.com/40d4b8ee7a20cbf9725c025acb55ef566e92109bc4a0e7b50a621bf0e1ad49b5.jpg
---

## Advanced Rendering: Choose Your Winner - DirectX 11 or 12?

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
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-tecno-spark-go-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Tecno Spark Go (2023) | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/click-and-draw-showdown-best-for-beatboxing/"><u>Click & Draw Showdown: Best for Beatboxing</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-performance-in-shooter-games-through-sensitivity-tweaks/"><u>Boosting Performance in Shooter Games Through Sensitivity Tweaks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-realme-11-5g-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Realme 11 5G PC | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171155782-gamers-delight-large-scale-arcade-framing/"><u>Gamer's Delight - Large-Scale Arcade Framing</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-three-easy-cost-free-strategies-to-improve-audio-quality-in-your-digital-projects/"><u>Updated In 2024, Three Easy, Cost-Free Strategies to Improve Audio Quality in Your Digital Projects</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-oppo-reno-11-pro-5g-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Oppo Reno 11 Pro 5G FRP Bypass With Best Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-creativity-9-games-for-aspiring-designers/"><u>Elevate Creativity: 9 Games for Aspiring Designers</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-error-0x803f8001-on-minecraft-for-windows-pcs/"><u>Resolving Error 0X803F8001 on Minecraft for Windows PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/is-rtx-immediate-replacement-after-gtx-discontinuation/"><u>Is RTX Immediate Replacement After GTX Discontinuation?</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173630427-invest-in-impact-choose-thick-broad-cabinet-frames/"><u>Invest in Impact: Choose Thick, Broad Cabinet Frames</u></a></li>
<li><a href="https://games-able.techidaily.com/claim-your-free-digital-content-today/"><u>Claim Your Free Digital Content Today</u></a></li>
<li><a href="https://games-able.techidaily.com/correcting-minecraft-launcher-malfunction-code-0x803f8001/"><u>Correcting Minecraft Launcher Malfunction: Code 0X803F8001</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-vimeos-revenue-revolution-strategies-for-sustainable-earnings/"><u>[New] 2024 Approved  Vimeo's Revenue Revolution  Strategies for Sustainable Earnings</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-apple-iphone-xs-activation-lock-by-drfone-ios/"><u>How to Remove Apple iPhone XS Activation Lock</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-wi-fi-refresh-on-sonys-dualsense/"><u>Mastering Wi-Fi Refresh on Sony's DualSense</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-fixing-roblox-error-code-403-on-windows-systems/"><u>Mastering the Art of Fixing Roblox Error Code 403 on Windows Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/retro-controller-enhancing-classic-games/"><u>Retro Controller: Enhancing Classic Games</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-videos-on-nokia-g310-by-fonelab-android-recover-video/"><u>How to restore wiped videos on Nokia G310</u></a></li>
<li><a href="https://games-able.techidaily.com/managing-roblox-data-consumption-on-iphones/"><u>Managing Roblox Data Consumption on iPhones</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionizing-tech-ai-innovations-at-computex/"><u>Revolutionizing Tech: AI Innovations at Computex</u></a></li>
<li><a href="https://extra-resources.techidaily.com/navigating-the-highest-rated-pixel-soundtracks-online/"><u>Navigating the Highest-Rated Pixel Soundtracks Online</u></a></li>
<li><a href="https://games-able.techidaily.com/preventing-xbox-controller-gaming-malfunctions/"><u>Preventing Xbox Controller Gaming Malfunctions</u></a></li>
<li><a href="https://games-able.techidaily.com/invest-in-fun-top-5-motivations-to-purchase-mobile-games/"><u>Invest in Fun: Top 5 Motivations to Purchase Mobile Games</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-next-gen-tvs-and-displays-ifa-2023-focus/"><u>Exploring Next-Gen TVs and Displays - IFA 2023 Focus</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/secure-hassle-free-passport-images-top-10-choices/"><u>Secure, Hassle-Free Passport Images - Top 10 Choices</u></a></li>
<li><a href="https://games-able.techidaily.com/insider-advice-on-digital-xbox-seriess-returns/"><u>Insider Advice on Digital Xbox Series/S Returns</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-gaming-analysis-on-steam-platform/"><u>Maximizing Gaming Analysis on Steam Platform</u></a></li>
<li><a href="https://games-able.techidaily.com/mending-the-inconsistencies-of-steams-data-exchange/"><u>Mending the Inconsistencies of Steam's Data Exchange</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-windows-steams-bp-dilemmas/"><u>Overcoming Windows-Steam's BP Dilemmas</u></a></li>
<li><a href="https://games-able.techidaily.com/name-that-tune-the-8-best-mobile-music-trivia-games/"><u>Name That Tune! The 8 Best Mobile Music Trivia Games</u></a></li>
<li><a href="https://games-able.techidaily.com/6-innovative-techniques-to-enjoy-ps5-games/"><u>6 Innovative Techniques to Enjoy PS5 Games</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-the-soundscape-seekers-manual-uncovering-the-best-sources-for-podcast-effects/"><u>New 2024 Approved The Soundscape Seekers Manual Uncovering the Best Sources for Podcast Effects</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-overcoming-social-media-roadblocks-fix-your-story-upload/"><u>[New] In 2024, Overcoming Social Media Roadblocks  Fix Your Story Upload</u></a></li>
<li><a href="https://games-able.techidaily.com/keep-your-playstation-fresh-remove-reinstall-games/"><u>Keep Your PlayStation Fresh: Remove, Reinstall Games</u></a></li>
<li><a href="https://games-able.techidaily.com/reducing-risks-dont-tap-into-ps5s-microphone/"><u>Reducing Risks: Don't Tap Into PS5's Microphone</u></a></li>
<li><a href="https://games-able.techidaily.com/navigate-the-digital-labyrinths-with-us/"><u>Navigate the Digital Labyrinths with Us!</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-melodic-minus-one-magic-a-gratuitous-converter-bringing-downbeats-of-mp3-track-to-harmony/"><u>New 2024 Approved Melodic Minus One Magic A Gratuitous Converter Bringing Downbeats of MP3 Track to Harmony.</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-nokia-g310-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/elevated-experience-premium-seating-for-the-taller-set/"><u>Elevated Experience: Premium Seating for the Taller Set</u></a></li>
<li><a href="https://games-able.techidaily.com/enrich-your-experience-explore-more-fallout-titles/"><u>Enrich Your Experience: Explore More Fallout Titles</u></a></li>
<li><a href="https://games-able.techidaily.com/commanding-the-dungeon-top-6-strategies-with-gpt-assisted-gameplay/"><u>Commanding the Dungeon: Top 6 Strategies with GPT-Assisted Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/epic-and-steam-account-synergy-tips/"><u>Epic & Steam Account Synergy Tips</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-evaluating-djis-phantom-3-features/"><u>2024 Approved  Evaluating DJI's Phantom 3 Features</u></a></li>
<li><a href="https://games-able.techidaily.com/all-inclusive-guide-to-choosing-top-1440p-monitors-without-breaking-the-bank/"><u>All-Inclusive Guide to Choosing Top 1440P Monitors Without Breaking the Bank</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-amr-audio-workshop-in-depth-tutorials-for-full-amr-file-transformation-for-2024/"><u>Updated AMR Audio Workshop In-Depth Tutorials for Full AMR File Transformation for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/choosing-between-ps5-and-xbox-xs-game-systems/"><u>Choosing Between PS5 & Xbox XS Game Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/pinnacle-headphones-for-switch-gamers/"><u>Pinnacle Headphones for Switch Gamers</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-virtual-artisans-haven-retreat/"><u>In 2024, Virtual Artisans' Haven Retreat</u></a></li>
</ul></div>

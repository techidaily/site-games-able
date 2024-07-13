---
title: "Upgrading Games: From DirectX 11 to DirectX 12"
date: 2024-07-12T04:05:46.444Z
updated: 2024-07-13T04:05:46.444Z
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
<li><a href="https://games-able.techidaily.com/outshining-nvidia-with-comparable-graphics-cards/"><u>Outshining Nvidia with Comparable Graphics Cards</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-intova-edge-x-action-camera-review/"><u>[Updated] Intova Edge X Action Camera Review</u></a></li>
<li><a href="https://games-able.techidaily.com/tailoring-display-and-illumination-for-optimal-gaming/"><u>Tailoring Display & Illumination for Optimal Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/unbearable-undertakings-the-best-of-frustrating-fiddles/"><u>Unbearable Undertakings: The Best of Frustrating Fiddles</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-maze-of-ps5-wireless-troubleshooting/"><u>Navigating the Maze of PS5 Wireless Troubleshooting</u></a></li>
<li><a href="https://games-able.techidaily.com/streamline-gaming-on-chrome-with-facebook-support/"><u>Streamline Gaming on Chrome with Facebook Support</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/chromecast-compatibility-how-to-stream-videos-in-any-format-for-2024/"><u>Chromecast Compatibility How to Stream Videos in Any Format for 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-iphone-11-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>Unlock iPhone 11 With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://ai-voice.techidaily.com/updated-authors-recommended-the-best-text-voice-generators-for-all-platforms/"><u>Updated Authors Recommended The Best Text Voice Generators for All Platforms</u></a></li>
<li><a href="https://games-able.techidaily.com/simple-steps-to-link-an-xbox-to-a-windows-machine-128-chars/"><u>Simple Steps to Link an Xbox to a Windows Machine (128 Chars)</u></a></li>
<li><a href="https://games-able.techidaily.com/smarter-monitor-shopping-good-vs-wrong-oled/"><u>Smarter Monitor Shopping: Good vs Wrong OLED</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-vertical-video-editing-in-the-cloud-best-web-based-options/"><u>New 2024 Approved Vertical Video Editing in the Cloud Best Web-Based Options</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-engaging-with-new-york-times-power/"><u>Strategies for Engaging with New York Times Power</u></a></li>
<li><a href="https://games-able.techidaily.com/tech-titans-at-computex-with-new-ai-hardware/"><u>Tech Titans at Computex with New AI Hardware</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-restarting-disrupted-streams-on-fb-fixes-for-todays-broadcasters/"><u>[New] 2024 Approved  Restarting Disrupted Streams on FB  Fixes for Today's Broadcasters</u></a></li>
<li><a href="https://games-able.techidaily.com/steams-gaming-cost-evolution-analysis/"><u>Steam's Gaming Cost Evolution Analysis</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-complete-guide-on-unlocking-apple-iphone-xs-with-a-broken-screen-by-drfone-ios/"><u>In 2024, Complete Guide on Unlocking Apple iPhone XS with a Broken Screen?</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionize-your-gaming-shift-from-console-to-pc/"><u>Revolutionize Your Gaming: Shift From Console to PC</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-integrating-slack-and-filmora-for-smooth-meeting-operations-for-2024/"><u>[New] Integrating Slack & Filmora for Smooth Meeting Operations for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-steam-decks-for-gaming-enthusiasts/"><u>Navigating Steam Decks for Gaming Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/reimagine-your-gaming-realm-with-improved-blue-ray-on-sx/"><u>Reimagine Your Gaming Realm with Improved Blue-Ray on SX</u></a></li>
<li><a href="https://games-able.techidaily.com/psp-into-virtual-game-boy-transition-tips/"><u>PSP Into Virtual Game Boy Transition Tips</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-unveiling-instagrams-videography-timeframe/"><u>[Updated] In 2024, Unveiling Instagram's Videography Timeframe</u></a></li>
<li><a href="https://extra-hints.techidaily.com/fostering-fun-with-metaverse-satirical-artifacts/"><u>Fostering Fun with Metaverse Satirical Artifacts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-what-does-jailbreaking-apple-iphone-se-2022-i-do-get-answers-here-drfone-by-drfone-ios/"><u>In 2024, What Does Jailbreaking Apple iPhone SE (2022) i Do? Get Answers here | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/tackling-device-lag-fix-for-error-code-0x887a0006-in-wins/"><u>Tackling Device Lag: Fix for Error Code 0X887A0006 in Wins</u></a></li>
<li><a href="https://games-able.techidaily.com/nest-egg-personalized-steam-picks/"><u>Nest Egg: Personalized Steam Picks</u></a></li>
<li><a href="https://games-able.techidaily.com/revitalize-your-console-fixing-broken-xbox-sandx/"><u>Revitalize Your Console: Fixing Broken Xbox S&X</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-top-picks-5-premier-mp3-mixing-programs-tailored-for-mac-systems-for-2024/"><u>New Top Picks 5 Premier MP3 Mixing Programs Tailored for Mac Systems for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/preventing-external-speakers-opt-for-headphones/"><u>Preventing External Speakers, Opt for Headphones</u></a></li>
<li><a href="https://games-able.techidaily.com/remedying-steams-content-not-loading-problem/"><u>Remedying Steam's Content Not Loading Problem</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713963535927-updated-how-to-reduce-the-size-of-video-files-online-in-this-article-well-share-the-top-10-free-online-video-compressors-that-you-can-use-anywhere-at-any-ti/"><u>Updated How to Reduce the Size of Video Files Online? In This Article, Well Share the Top 10 Free Online Video Compressors that You Can Use Anywhere at Any Time and on Any Device for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/optimizing-input-transfer-a-stepwise-guide-to-using-barriers-for-sharing/"><u>Optimizing Input Transfer: A Stepwise Guide to Using Barriers for Sharing</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-oppo-reno-8t-5g-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/transforming-your-gaming-identity-on-riot-platform/"><u>Transforming Your Gaming Identity on Riot Platform</u></a></li>
<li><a href="https://games-able.techidaily.com/seamless-setup-add-discord-to-your-mac-experience/"><u>Seamless Setup: Add Discord to Your Mac Experience</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-oppo-find-n3-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Oppo Find N3 for Streaming | Dr.fone</u></a></li>
</ul></div>

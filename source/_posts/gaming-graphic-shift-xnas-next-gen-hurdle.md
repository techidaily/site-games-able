---
title: "Gaming Graphic Shift: XNA's Next-Gen Hurdle"
date: 2024-09-04T21:47:42.684Z
updated: 2024-09-05T21:47:42.684Z
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

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938682/19272" target="_top" id="1938682">
  <img src="//a.impactradius-go.com/display-ad/19272-1938682" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938682/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read [our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972670/19272" target="_top" id="1972670">
  <img src="//a.impactradius-go.com/display-ad/19272-1972670" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972670/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/utting-edge-techniques-for-youtube-video-production-with-sony-vegas-for-2024/"><u>[New] Cutting-Edge Techniques for YouTube Video Production with Sony Vegas for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-exploring-panoramic-versus-full-immersion-visual-media-tech/"><u>[New] Exploring Panoramic Versus Full-Immersion Visual Media Tech</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-preparing-to-engage-in-googles-video-meetings-for-2024/"><u>[New] Preparing to Engage in Google's Video Meetings for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-the-edge-of-gaming-technology-samsung-ue590-monitor/"><u>[New] The Edge of Gaming Technology  Samsung UE590 Monitor</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-facebook-video-vanishing-act-heres-how-to-perform-the-counter-with-12-steps/"><u>[Updated] Facebook Video Vanishing Act? Here's How to Perform the Counter with 12 Steps</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-the-step-by-step-process-for-screening-web-tv-episodes/"><u>[Updated] The Step-by-Step Process for Screening Web TV Episodes</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-ultimate-list-of-serene-smartphone-games-for-2024/"><u>[Updated] The Ultimate List of Serene Smartphone Games for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-upgrading-your-playlists-for-seamless-integration-from-spotify-to-youtube-music/"><u>[Updated] Upgrading Your Playlists for Seamless Integration From Spotify to YouTube Music</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-explore-best-speech-recognition-software-on-your-mac/"><u>2024 Approved  Explore Best Speech Recognition Software on Your Mac</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovate-impress-and-captivate-in-solo-podcasting/"><u>2024 Approved  Innovate, Impress, and Captivate in Solo Podcasting</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-securing-your-snapshots-premium-and-budget-friendly-cloud-options/"><u>2024 Approved  Securing Your Snapshots  Premium and Budget-Friendly Cloud Options</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-for-implementing-look-up-tables-in-creative-suite/"><u>2024 Approved  The Ultimate Guide for Implementing Look-Up Tables in Creative Suite</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/5-quick-methods-to-bypass-vivo-v30-frp-by-drfone-android/"><u>5 Quick Methods to Bypass Vivo V30 FRP</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-honor-90-lite-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Honor 90 Lite FRP Bypass Instantly</u></a></li>
<li><a href="https://games-able.techidaily.com/crossover-guide-to-baldurs-gate-3-mac-play/"><u>CrossOver Guide to Baldur's Gate 3 Mac Play</u></a></li>
<li><a href="https://games-able.techidaily.com/crucial-aspects-of-selecting-a-powerful-monitor/"><u>Crucial Aspects of Selecting a Powerful Monitor</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-the-top-gaming-displays-at-144hz/"><u>Discovering the Top Gaming Displays at 144Hz</u></a></li>
<li><a href="https://games-able.techidaily.com/dive-into-virtual-racing-with-a-499-moza-bundle/"><u>Dive Into Virtual Racing with a $499 MOZA Bundle</u></a></li>
<li><a href="https://extra-information.techidaily.com/edit-efficiently-to-minimize-your-overflowing-drafter-points/"><u>Edit Efficiently to Minimize Your Overflowing Drafter' Points</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-four-key-methods-of-ai-regulation-by-authorities/"><u>Exploring Four Key Methods of AI Regulation by Authorities</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-boundaries-5-ways-chatgpt-may-not-be-ideal-for-crypto-investment-strategies/"><u>Exploring the Boundaries: 5 Ways ChatGPT May Not Be Ideal for Crypto Investment Strategies</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-tecno-spark-10-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Tecno Spark 10 5G Quickly | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/forget-the-fancy-why-standard-display-is-best-for-pc-gaming/"><u>Forget the Fancy: Why Standard Display Is Best for PC Gaming</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-video-hosting-10-top-options-for-personal-and-professional-use-for-2024/"><u>Free Video Hosting 10 Top Options for Personal and Professional Use for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/game-hardware-breakthroughs-set-to-unveil-at-ifa-2023/"><u>Game Hardware Breakthroughs Set to Unveil at IFA 2023</u></a></li>
<li><a href="https://games-able.techidaily.com/gamers-dream-setup-akko-mod007b-unpackaged/"><u>Gamer's Dream Setup: Akko MOD007B Unpackaged</u></a></li>
<li><a href="https://games-able.techidaily.com/how-ps5-enhances-older-ps4-gaming-experience/"><u>How PS5 Enhances Older PS4 Gaming Experience</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-infinix-note-30i-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Infinix Note 30i | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-lenovo-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Lenovo</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-y27-4g-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo Y27 4G</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-guide-to-windows-10-picture-and-media-importer/"><u>In 2024, The Ultimate Guide to Windows 10 Picture & Media Importer</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-nubia-red-magic-9-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Nubia Red Magic 9 Pro Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://games-able.techidaily.com/maintaining-gaming-enthusiasm-a-6-step-plan/"><u>Maintaining Gaming Enthusiasm: A 6-Step Plan</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-silent-gameplay-disabling-xbox-controller-shake/"><u>Mastering Silent Gameplay: Disabling Xbox Controller Shake</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-maintaining-steam-bp-mode/"><u>Mastering the Art of Maintaining Steam BP Mode</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-your-computer-potential-upgrade-to-corsairs-icue-link-and-see-the-difference/"><u>Maximize Your Computer Potential - Upgrade to Corsair's iCUE Link and See the Difference</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-vr-experience-with-ps-vr-2/"><u>Maximizing VR Experience with PS VR 2</u></a></li>
<li><a href="https://games-able.techidaily.com/multilingual-roms-made-easy-with-translation-patches/"><u>Multilingual Roms Made Easy with Translation Patches</u></a></li>
<li><a href="https://games-able.techidaily.com/next-level-play-ifas-premier-gaming-showcase/"><u>Next Level Play: IFA's Premier Gaming Showcase</u></a></li>
<li><a href="https://games-able.techidaily.com/play-hard-win-harder-the-ultimate-list-of-iosandroid-sports-titles/"><u>Play Hard, Win Harder: The Ultimate List of iOS/Android Sports Titles</u></a></li>
<li><a href="https://games-able.techidaily.com/preventative-measures-against-gpu-sag/"><u>Preventative Measures Against GPU Sag</u></a></li>
<li><a href="https://games-able.techidaily.com/quick-guide-connecting-switch-to-internet/"><u>Quick Guide: Connecting Switch to Internet</u></a></li>
<li><a href="https://games-able.techidaily.com/quickening-data-exchange-diminishing-pings-and-delay-duration/"><u>Quickening Data Exchange: Diminishing Pings and Delay Duration</u></a></li>
<li><a href="https://games-able.techidaily.com/reprogramming-the-psp-a-path-to-nessnes-dual-mode/"><u>Reprogramming the PSP: A Path to NES/SNES Dual Mode</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/seamlessly-stream-and-save-youtube-lives-from-every-device-for-2024/"><u>Seamlessly Stream and Save YouTube Lives From Every Device for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/securing-console-pc-connection-a-guide-for-stable-ps4-linking/"><u>Securing Console-PC Connection: A Guide for Stable PS4 Linking</u></a></li>
<li><a href="https://games-able.techidaily.com/simplify-your-pathway-for-xbox-return-claims/"><u>Simplify Your Pathway for Xbox Return Claims</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-microsofts-error-code-0x8007251d-for-users/"><u>Simplifying Microsoft's Error Code 0X8007251D for Users</u></a></li>
<li><a href="https://games-able.techidaily.com/size-matters-in-smartphone-and-tablet-games/"><u>Size Matters in Smartphone and Tablet Games</u></a></li>
<li><a href="https://games-able.techidaily.com/sleekgear-monitor-bargain-gaming-led/"><u>SleekGear Monitor - Bargain Gaming LED</u></a></li>
<li><a href="https://games-able.techidaily.com/step-beyond-conventional-embrace-size-in-gaming-frames/"><u>Step Beyond Conventional: Embrace Size in Gaming Frames!</u></a></li>
<li><a href="https://games-able.techidaily.com/step-into-the-world-of-gamers-with-these-top-8-outlets/"><u>Step Into the World of Gamers with These Top 8 Outlets</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-integrate-old-games-with-win11-mypictures/"><u>Steps to Integrate Old Games with Win11 MyPictures</u></a></li>
<li><a href="https://games-able.techidaily.com/swift-steps-securing-and-setting-up-mojang-maps/"><u>Swift Steps: Securing & Setting up Mojang Maps</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-3d-light-panels-for-your-gaming-setup/"><u>The Best 3D Light Panels for Your Gaming Setup</u></a></li>
<li><a href="https://games-able.techidaily.com/the-isolated-players-guide-to-winmc-network-fixes/"><u>The Isolated Player's Guide to WinMC Network Fixes</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-quiet-command-for-xbox-systems/"><u>The Ultimate Quiet Command for Xbox Systems</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-oppo-a58-4g-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Oppo A58 4G</u></a></li>
<li><a href="https://extra-hints.techidaily.com/timeless-tales-crafted-for-the-silver-frame/"><u>Timeless Tales Crafted for the Silver Frame</u></a></li>
<li><a href="https://games-able.techidaily.com/top-seated-partnerships-in-co-op-games-xbox-series-sx/"><u>Top Seated Partnerships in Co-Op Games - Xbox Series S/X</u></a></li>
<li><a href="https://games-able.techidaily.com/turbo-charge-your-win-chances-in-csgo/"><u>Turbo Charge Your Win Chances in CS:GO</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-the-impact-steams-revised-stance-on-ai-games/"><u>Understanding the Impact: Steam’s Revised Stance on AI Games</u></a></li>
<li><a href="https://games-able.techidaily.com/unleash-full-potential-steam-deck-with-windows/"><u>Unleash Full Potential: Steam Deck with Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-nycs-elite-connections-a-guide-to-winning-every-day/"><u>Unlocking NYC's Elite Connections: A Guide to Winning Every Day</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/voice-over-wifi-viber-out-evaluation-is-it-worth-switching/"><u>Voice over WiFi (Viber Out) Evaluation: Is It Worth Switching?</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Infinix Hot 30i? | Dr.fone</u></a></li>
</ul></div>

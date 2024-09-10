---
title: "GPU's Best Friend: DirectX 11 or 12?"
date: 2024-09-09T09:32:17.358Z
updated: 2024-09-10T09:32:17.358Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128843/7443" target="_top" id="2128843">
  <img src="//a.impactradius-go.com/display-ad/7443-2128843" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128843/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is Microsoft's DirectX?

![DirectX logo imposed on a photo of a man coding](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-1.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137227/26400" target="_top" id="2137227">
  <img src="//a.impactradius-go.com/display-ad/26400-2137227" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137227/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://aligracehair.sjv.io/c/5597632/2115925/19272" target="_top" id="2115925">
  <img src="//a.impactradius-go.com/display-ad/19272-2115925" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115925/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why Switching From DirectX 11 to DirectX 12 Isn't Straightforward

 DirectX 11 was first released for Windows Vista on October 27, 2009\. So, with DirectX 12 following in 2015, there's a six-year gap between DirectX 11 and DirectX 12\. During this time, thousands of games have been developed using DirectX 11\. Unfortunately, moving from DirectX 11 to DirectX 12 is anything but easy.

 DirectX 11 is what's called a high-level API. Simply put, high-level APIs are easier for developers to work with. The result is stable, polished, and playable games. On the other hand, DirectX 12 is a low-level API and a different beast than DirectX 11\. While it allows developers to fine-tune optimization at a granular level, it also demands extensive knowledge to use.

 That being said, a game developed in DirectX 12 could end up with worse performance depending on the developer's knowledge of the API. Some improvements come with DirectX 12, but it really comes down to how well a developer can implement it. For this reason, many developers choose to stick to high-level APIs like DirectX 11.

<!-- affiliate ads begin -->
<span id="701707">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/701707.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/7443-701707">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/701707.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fappsumo.8odi.net%2Fc%2F5597632%2F701707%2F7443'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/701707/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## DX 11 vs. DX 12: Which Should You Choose?

 The answer depends on a few things, like what game you are trying to run. For example, Guild Wars 2 runs on DirectX 11\. Even if your OS and hardware can use DirectX 12, you will not have the option to select DirectX 11 in Guild Wars 2 because the game does not support it. This is entirely the decision of the developer, ArenaNet.

![In-game image from Guild Wars 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/untitled-design-3.jpg)

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Image Credit: Martin Kerstein/[Guild Wars 2](https://www.guildwars2.com/en/news/guesting-is-coming/)

 Believe it or not, it took nine years for ArenaNet to make the switch from DirectX 9 to DirectX 11\. However, some games do support both DirectX 11 and DirectX 12, including Fortnite (read [our Fortnite cheat sheet](https://www.makeuseof.com/tag/fortnite-essentials-cheat-sheet-controls-tips-terms/) ), Battlefield 5, Shadow of the Tomb Raider, and more. Users can switch between DirectX 11 and DirectX 12 in the game settings.

 Now, the fact that some games support both DirectX 11 and 12 has probably got you wondering about in-game performance. Does choosing DX 11 or DX 12 deliver better in-game performance? The following video illustrates the differences between DirectX 11 and DirectX 12 in a range of games, showcasing vital specs such as average frames per second, CPU usage, GPU usage, and more, using an AMD Ryzen 3600, Nvidia GeForce RTX 3060 Ti, and 16GB DDR4 RAM.

 The results are surprising in many ways, with little visual difference at times between DX 11 and DX 12, despite the multiple years of difference between their launches. You may have also noted the differences in GPU and CPU loads between both DirectX versions, with the DX 12 versions of each game typically requiring fewer resources than the older DX 11.

 In addition to in-game support, choosing between DirectX 11 and DirectX 12 will also depend on your hardware. Just about any modern GPU will support DirectX 12, but the same can't be said for older GPUs like the Radeon HD 4870\. Released in 2008, this GPU only supports up to DirectX 10\. This means it would be incapable of running most modern games, which run using DirectX 11 and DirectX 12.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134503/19576" target="_top" id="2134503">
  <img src="//a.impactradius-go.com/display-ad/19576-2134503" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134503/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-inject-photos-with-focal-spread-outer-radius-adobe-psx/"><u>[New] 2024 Approved Inject Photos with Focal Spread Outer Radius Adobe PSX</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-acid-pro-evaluation-finding-reliable-counterparts-for-2024/"><u>[New] ACID Pro Evaluation Finding Reliable Counterparts for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-enhance-engagement-top-tools-and-tips-for-properly-tagged-videos-for-2024/"><u>[New] Enhance Engagement Top Tools and Tips for Properly Tagged Videos for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-narrative-artistry-accolades-1-8-distinguished-academies/"><u>[New] Narrative Artistry Accolades #1-#8 Distinguished Academies</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-operational-update-troubled-obs-camera-for-2024/"><u>[New] Operational Update Troubled OBS Camera for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-the-realm-of-ring-vs-reality-stream/"><u>[Updated] In 2024, The Realm of Ring vs Reality Stream</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-purchase-pitfalls-steering-clear-from-the-seduction-of-false-subscribers/"><u>[Updated] Purchase Pitfalls Steering Clear From the Seduction of False Subscribers</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-from-bland-to-breatited-the-ultimate-video-title-guide/"><u>2024 Approved From Bland to Breatited The Ultimate Video Title Guide</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/deciphering-instagram-highlights-the-stories-guide/"><u>Deciphering Instagram Highlights The Stories Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/directx-enabled-headset-use-on-series-xs/"><u>DirectX Enabled Headset Use on Series X/S</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-gameplay-pleasure-mastering-essential-techniques-5-tips-on-a-mac/"><u>Elevate Gameplay Pleasure: Mastering Essential Techniques (5 Tips) on a Mac</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-your-wallets-gaming-capacity-on-steam/"><u>Enhancing Your Wallet's Gaming Capacity on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/enjoy-full-adventure-of-baldurs-gate-3-easily-through-crossover-on-macos/"><u>Enjoy Full Adventure of Baldur’s Gate 3 Easily Through CrossOver on macOS</u></a></li>
<li><a href="https://games-able.techidaily.com/expert-roundup-of-ddr5-boards-2024/"><u>Expert Roundup of DDR5 Boards 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/game-ace-selecting-the-best-from-google-play-games-beta-pc/"><u>Game Ace: Selecting the Best From Google Play Games Beta PC</u></a></li>
<li><a href="https://games-able.techidaily.com/game-worlds-vanish-in-a-blink-but-do-they-matter/"><u>Game Worlds Vanish in a Blink, But Do They Matter?</u></a></li>
<li><a href="https://buynow-info.techidaily.com/getting-the-most-out-of-budget-cameras-an-insightful-review-on-rexing-v1-dash-cam/"><u>Getting the Most Out of Budget Cameras: An Insightful Review on Rexing V1 Dash Cam</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/global-french-speakers-distribution-and-leading-nations/"><u>Global French Speakers: Distribution & Leading Nations</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-check-out-how-much-vram-you-have/"><u>How to Check Out How Much VRAM You Have</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-on-iphone-12-by-drfone-ios/"><u>How to Fix Locked Apple ID on iPhone 12</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-rejuvenate-a-non-starting-display-driver-on-windows-11/"><u>How to Rejuvenate a Non-Starting Display Driver on Windows 11</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-correcting-iphone-camera-focusing-errors-effectively/"><u>In 2024, Correcting iPhone Camera Focusing Errors Effectively</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-craft-crisp-visuals-with-picart-background-sweep/"><u>In 2024, Craft Crisp Visuals with PicArt Background Sweep</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-fake-android-location-without-rooting-for-your-huawei-nova-y91-drfone-by-drfone-virtual/"><u>In 2024, Fake Android Location without Rooting For Your Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgotten-the-voicemail-password-of-xiaomi-13t-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Xiaomi 13T? Try These Fixes</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Xiaomi Redmi K70E? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-inside-the-tech-what-is-virtual-reality-gear/"><u>In 2024, Inside the Tech What Is Virtual Reality Gear?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-the-perfect-blend-of-sound-and-video-tips-to-capture-high-quality-zoom-recordings/"><u>In 2024, The Perfect Blend of Sound and Video Tips to Capture High-Quality Zoom Recordings</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-ultimate-guide-from-oppo-a58-4g-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Oppo A58 4G FRP Bypass</u></a></li>
<li><a href="https://games-able.techidaily.com/indulge-your-curiosity-why-i-love-netflix-gaming/"><u>Indulge Your Curiosity: Why I Love Netflix Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/leveraging-persuasive-techniques-for-impactful-steam-critiques/"><u>Leveraging Persuasive Techniques for Impactful Steam Critiques</u></a></li>
<li><a href="https://games-able.techidaily.com/oled-gaming-tech-why-i-made-the-switch-in-2-years/"><u>OLED Gaming Tech: Why I Made the Switch in 2 Years.</u></a></li>
<li><a href="https://games-able.techidaily.com/prepare-for-fun-dive-into-chatgpts-favorite-6-games/"><u>Prepare For Fun: Dive Into ChatGPT’s Favorite 6 Games</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5s-leap-from-bulky-to-compact-wonder/"><u>PS5's Leap From Bulky to Compact Wonder</u></a></li>
<li><a href="https://games-able.techidaily.com/quieting-down-your-consoles-vibrations/"><u>Quieting Down Your Console's Vibrations</u></a></li>
<li><a href="https://games-able.techidaily.com/resolving-steam-server-accessibility-problems/"><u>Resolving Steam Server Accessibility Problems</u></a></li>
<li><a href="https://games-able.techidaily.com/restore-ps4-joystick-functionality-expert-advice-for-gamers/"><u>Restore PS4 Joystick Functionality: Expert Advice for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/roblox-fps-unlockers-functionality-and-safety-concerns/"><u>Roblox FPS Unlockers: Functionality & Safety Concerns</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-vivo-s17-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Vivo S17</u></a></li>
<li><a href="https://games-able.techidaily.com/sky-high-gameplay-maximizing-your-pcs-fps-capability/"><u>Sky-High Gameplay: Maximizing Your PC's FPS Capability</u></a></li>
<li><a href="https://games-able.techidaily.com/tactical-triumphs-an-exclusive-guide-to-top-11-strategy-titles/"><u>Tactical Triumphs: An Exclusive Guide to Top 11 Strategy Titles</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-art-of-tall-videos-editing-vertical-media-for-impactful-insta-feeds/"><u>The Art of Tall Videos Editing Vertical Media for Impactful Insta Feeds</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-modern-retro-consoles/"><u>The Best Modern Retro Consoles</u></a></li>
<li><a href="https://games-able.techidaily.com/the-nostalgic-console-contemporary-and-timeless/"><u>The Nostalgic Console: Contemporary and Timeless</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-to-playing-counter-strike-2-on-apple-devices/"><u>The Ultimate Guide to Playing Counter-Strike 2 on Apple Devices</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-itel-a60-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Itel A60 Device</u></a></li>
<li><a href="https://apple-account.techidaily.com/troubleshooting-error-connecting-to-the-apple-id-server-from-apple-iphone-12-by-drfone-ios/"><u>Troubleshooting Error Connecting to the Apple ID Server From Apple iPhone 12</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-gaming-guide-ea-plays-ps5-favorites/"><u>Ultimate Gaming Guide: EA Play's PS5 Favorites</u></a></li>
<li><a href="https://games-able.techidaily.com/unleash-game-potential-5-proven-methods-to-enhance-favourite-games-on-a-mac/"><u>Unleash Game Potential: 5 Proven Methods to Enhance Favourite Games on a Mac</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/web-services-revolutionized-by-chatgpt-technology/"><u>Web Services Revolutionized by ChatGPT Technology</u></a></li>
<li><a href="https://games-able.techidaily.com/why-xbox-series-s-ditches-physical-game-discs/"><u>Why Xbox Series S Ditches Physical Game Discs</u></a></li>
</ul></div>

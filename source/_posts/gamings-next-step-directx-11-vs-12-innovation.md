---
title: "Gaming's Next Step: DirectX 11 Vs. 12 Innovation"
date: 2024-07-12T03:51:53.848Z
updated: 2024-07-13T03:51:53.848Z
tags:
  - games
categories:
  - games
description: "This Article Describes Gaming's Next Step: DirectX 11 Vs. 12 Innovation"
excerpt: "This Article Describes Gaming's Next Step: DirectX 11 Vs. 12 Innovation"
keywords: DirectX 11 Vs. 12,Gaming Innovations,Graphics API Upgrade,DirectX Evolution,Game Development Tech,Next-Gen Graphics,DirectX Comparison
thumbnail: https://thmb.techidaily.com/0d3d204f3859dff7eef251abf3745730eecca41037a408c561029879668d653a.jpg
---

## Gaming's Next Step: DirectX 11 Vs. 12 Innovation

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
<li><a href="https://discord-videos.techidaily.com/take-your-discord-chat-to-the-next-level-with-tts-for-2024/"><u>Take Your Discord Chat to the Next Level with TTS for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/the-essence-of-metagame-strategy-understanding-and-following/"><u>The Essence of Metagame Strategy - Understanding & Following</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtube-link-mastery-a-roadmap-to-content-marketing-success/"><u>2024 Approved  YouTube Link Mastery  A Roadmap to Content Marketing Success</u></a></li>
<li><a href="https://games-able.techidaily.com/mwc-unveiled-innovations-and-winners-by-makeuseof/"><u>MWC Unveiled: Innovations and Winners by MakeUseOf</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-exploring-the-premier-digital-recorder-applications-for-pc-operating-systems/"><u>New 2024 Approved Exploring the Premier Digital Recorder Applications for PC Operating Systems</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-transform-video-vendoring-into-virtual-ventures-and-valuables/"><u>2024 Approved  Transform Video Vendoring Into Virtual Ventures and Valuables</u></a></li>
<li><a href="https://games-able.techidaily.com/unwind-and-enjoy-netflixs-mobile-game-haven/"><u>Unwind and Enjoy: Netflix’s Mobile Game Haven</u></a></li>
<li><a href="https://games-able.techidaily.com/integrating-shared-games-in-ps5-settings/"><u>Integrating Shared Games in PS5 Settings</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-oneplus-12-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on OnePlus 12 Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-early-bird-winners-youtubes-quick-favorites/"><u>[Updated] 2024 Approved  Early Bird Winners  Youtube's Quick Favorites</u></a></li>
<li><a href="https://games-able.techidaily.com/linking-worlds-across-platforms-transition-from-bedrock-writes-to-java-geysermc-server/"><u>Linking Worlds Across Platforms: Transition From Bedrock' Writes to Java, GeyserMC Server</u></a></li>
<li><a href="https://games-able.techidaily.com/steams-10-year-revamp-game-access-revolutionized-for-families/"><u>Steam's 10-Year Revamp: Game Access Revolutionized for Families</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-5-methods-to-make-a-fake-facetime-call-video-for-2024/"><u>Updated 5 Methods to Make a Fake Facetime Call Video for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-nearby-nuggets-your-essential-locale-lens-for-a-smoother-journey/"><u>In 2024, Unlocking Nearby Nuggets  Your Essential Locale Lens for a Smoother Journey</u></a></li>
<li><a href="https://games-able.techidaily.com/hitchless-guide-to-gaming-consoles-refunds-xbox/"><u>Hitchless Guide to Gaming Consoles Refunds (Xbox)</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/busting-barriers-with-laughs-the-best-facebook-prisoner-wit-quotes/"><u>Busting Barriers with Laughs  The Best Facebook Prisoner-Wit Quotes</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-and-justifying-a-dual-capable-screen/"><u>Understanding and Justifying a Dual-Capable Screen?</u></a></li>
<li><a href="https://games-able.techidaily.com/surprise-your-squad-steams-game-tastic-presents/"><u>Surprise Your Squad: Steam's Game-Tastic Presents</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ideal-tactic-fusing-gopro-footage-into-a-unified-360-video-experience/"><u>Ideal Tactic  Fusing GoPro Footage Into a Unified 360 Video Experience</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-outperform-competitors-youtube-visibility-tactics/"><u>2024 Approved  Outperform Competitors  YouTube Visibility Tactics</u></a></li>
<li><a href="https://games-able.techidaily.com/my-2-years-in-high-definition-with-an-oled-monitor/"><u>My 2 Years in High Definition with an OLED Monitor!</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-choice-finding-a-top-tier-144hz-monitor/"><u>The Best Choice: Finding a Top-Tier 144Hz Monitor</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-the-pillars-of-jazz-music-essential-information-every-enthusiast-should-learn-for-2024/"><u>Updated The Pillars of Jazz Music Essential Information Every Enthusiast Should Learn for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/innovative-play-on-ps5-beyond-gamepad-use/"><u>Innovative Play on PS5 Beyond Gamepad Use</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-elevate-your-instagram-experience-with-screen-record-tips/"><u>[New] 2024 Approved  Elevate Your Instagram Experience with Screen Record Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-accoutrement-assortment-for-a-top-tier-steam-deck-experience/"><u>The Ultimate Accoutrement Assortment for a Top-Tier Steam Deck Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/master-guide-to-mending-broken-xbox-series-xs/"><u>Master Guide to Mending Broken Xbox Series X|S</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-fast-tracking-visual-storytelling-with-google-collages/"><u>2024 Approved  Fast-Tracking Visual Storytelling with Google Collages</u></a></li>
<li><a href="https://games-able.techidaily.com/reinstate-your-disappeared-wordle-streak-seamlessly/"><u>Reinstate Your Disappeared Wordle Streak Seamlessly</u></a></li>
<li><a href="https://games-able.techidaily.com/master-the-game-quality-gear-for-maximum-efficiency/"><u>Master the Game: Quality Gear for Maximum Efficiency</u></a></li>
<li><a href="https://games-able.techidaily.com/perfect-purchase-how-to-evade-monitor-shopping-fails/"><u>Perfect Purchase: How to Evade Monitor Shopping Fails</u></a></li>
<li><a href="https://games-able.techidaily.com/the-future-of-personalized-medicine-tailoring-endocannabinoid-treatments/"><u>The Future of Personalized Medicine: Tailoring Endocannabinoid Treatments</u></a></li>
<li><a href="https://games-able.techidaily.com/valuepixeldesign-monitor-budget-gamers-choice/"><u>ValuePixelDesign Monitor, Budget Gamers' Choice</u></a></li>
<li><a href="https://games-able.techidaily.com/get-thrilling-with-these-7-command-line-games/"><u>Get Thrilling with These 7 Command Line Games</u></a></li>
<li><a href="https://games-able.techidaily.com/upgrade-to-corsairs-icue-link-and-experience-unparalleled-pc-control/"><u>Upgrade to Corsair's iCUE Link & Experience Unparalleled PC Control</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-formula-for-youtube-money-decoding-revenue-and-cpm-rates/"><u>In 2024, The Formula for YouTube Money  Decoding Revenue and CPM Rates</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-best-mobile-animation-tools-free-3d-apps-for-android-and-ios-for-2024/"><u>Updated Best Mobile Animation Tools Free 3D Apps for Android and iOS for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/leaner-gaming-efficient-model-structuring/"><u>Leaner Gaming: Efficient Model Structuring</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-grip-challenge-steering-wheel-or-virtual-dashboard/"><u>The Ultimate Grip Challenge: Steering Wheel or Virtual Dashboard</u></a></li>
<li><a href="https://games-able.techidaily.com/mmx-200-evaluation-powerful-but-feature-limited/"><u>MMX 200 Evaluation: Powerful but Feature-Limited</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-2024-approved-never-miss-a-moment-with-free-world-cup-live-streaming/"><u>Updated 2024 Approved Never Miss a Moment With Free World Cup Live Streaming</u></a></li>
<li><a href="https://games-able.techidaily.com/old-ps5-and-slimmer-tech-differences-discussed/"><u>Old PS5 & Slimmer Tech: Differences Discussed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-seeking-outno-cost-clip-art-deposits/"><u>In 2024, Seeking Outno-Cost Clip Art Deposits</u></a></li>
<li><a href="https://facebook.techidaily.com/sharpen-your-brands-online-image-top-reasons-for-a-business-profile-on-fb/"><u>Sharpen Your Brand's Online Image: Top Reasons for a Business Profile on FB</u></a></li>
<li><a href="https://games-able.techidaily.com/prime-neighborhoods-titans-territories/"><u>Prime Neighborhoods: Titans’ Territories</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-zen-in-your-screen-time-exploring-the-most-calming-digital-spaces-for-2024/"><u>Updated Zen in Your Screen Time Exploring the Most Calming Digital Spaces for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-steams-bp-display-glitches/"><u>Overcoming Steam's BP Display Glitches</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-tightens-rules-to-prevent-refund-manipulation/"><u>Steam Tightens Rules to Prevent Refund Manipulation</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-release-reschedule-a-good-idea/"><u>Gaming Release Reschedule: A Good Idea?</u></a></li>
<li><a href="https://games-able.techidaily.com/rethinking-graphics-innovation-why-discount-ray-tracing/"><u>Rethinking Graphics Innovation: Why Discount Ray Tracing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-premium-timepieces-for-your-dream-wedding-on-smartphones/"><u>In 2024, Premium Timepieces for Your Dream Wedding on Smartphones</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-image-ink-best-captioning-apps-for-photo-enthusiasts-iosandroid/"><u>In 2024, Image Ink  Best Captioning Apps for Photo Enthusiasts (iOS/Android)</u></a></li>
<li><a href="https://games-able.techidaily.com/seamless-streaming-transform-xbox-playback-quality/"><u>Seamless Streaming: Transform XBox Playback Quality</u></a></li>
<li><a href="https://extra-hints.techidaily.com/step-by-step-video-enhancement-tutorial-for-gopro-studio-users/"><u>Step-by-Step Video Enhancement Tutorial for GoPro Studio Users</u></a></li>
<li><a href="https://games-able.techidaily.com/recognizing-and-responding-to-gaming-abuse-series-sx/"><u>Recognizing and Responding to Gaming Abuse (Series S/X)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/streamline-your-show-entry-on-apple-media/"><u>Streamline Your Show Entry on Apple Media</u></a></li>
<li><a href="https://games-able.techidaily.com/highlighting-java-games-with-unbeatable-design/"><u>Highlighting Java Games with Unbeatable Design</u></a></li>
<li><a href="https://games-able.techidaily.com/the-complete-guide-to-gaming-success-on-steam/"><u>The Complete Guide to Gaming Success on Steam</u></a></li>
</ul></div>

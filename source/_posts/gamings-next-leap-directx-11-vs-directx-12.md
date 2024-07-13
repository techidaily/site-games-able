---
title: "Gaming's Next Leap: DirectX 11 V/S DirectX 12"
date: 2024-07-12T03:33:25.355Z
updated: 2024-07-13T03:33:25.355Z
tags:
  - games
categories:
  - games
description: "This Article Describes Gaming's Next Leap: DirectX 11 V/S DirectX 12"
excerpt: "This Article Describes Gaming's Next Leap: DirectX 11 V/S DirectX 12"
keywords: DirectX 12 vs DirectX 11,Gaming Future Directions,Xbox Graphics Update,PC Game Optimization,New DirectX Features,VR and Gaming Advance,Next-Gen Technologies in Games
thumbnail: https://thmb.techidaily.com/8f0f7ad73a0fa3da9b0369f5be30ef87f2772c066879ac12a1f0a0dafbb254a9.png
---

## Gaming's Next Leap: DirectX 11 V/S DirectX 12

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
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-vids-for-cash-a-compreomed-analysis-of-monetization-plays/"><u>In 2024, Vids for Cash  A Compreomed Analysis of Monetization Plays</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168855962-enhance-performance-install-latest-nvidia-drivers-now/"><u>Enhance Performance! Install Latest Nvidia Drivers Now.</u></a></li>
<li><a href="https://extra-information.techidaily.com/complete-immersive-camera-review-for-2024/"><u>Complete Immersive Camera Review for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-windows-steams-bp-display-issues/"><u>Mastering Windows-Steam's BP Display Issues</u></a></li>
<li><a href="https://games-able.techidaily.com/top-4-ios-emulators-bring-classic-gbadvance-games-alive/"><u>Top 4 iOS Emulators: Bring Classic GBAdvance Games Alive!</u></a></li>
<li><a href="https://games-able.techidaily.com/harmonic-heroes-mobile-apps-for-music-trivia-greatness/"><u>Harmonic Heroes: Mobile Apps for Music Trivia Greatness</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-itel-p55plus-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Itel P55+ FRP Without Computer</u></a></li>
<li><a href="https://games-able.techidaily.com/seamlessly-merge-console-pasts-emulating-xbox-on-pcs/"><u>Seamlessly Merge Console Pasts: Emulating Xbox on PCs</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-for-security-reasons-on-apple-iphone-15-pro-find-the-best-solution-here-by-drfone-ios/"><u>In 2024, Apple ID Locked for Security Reasons On Apple iPhone 15 Pro? Find the Best Solution Here</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-master-the-art-of-youtube-visibility-two-steps/"><u>In 2024, Master the Art of YouTube Visibility (Two Steps)</u></a></li>
<li><a href="https://games-able.techidaily.com/bring-back-childhood-fun-with-iphone-gaming-classics/"><u>Bring Back Childhood Fun with iPhone Gaming Classics</u></a></li>
<li><a href="https://games-able.techidaily.com/8-tips-to-beat-the-nyts-connections-game-every-day/"><u>8 Tips to Beat the NYT's Connections Game Every Day</u></a></li>
<li><a href="https://animation-videos.techidaily.com/top-20plus-best-free-gif-makers-online-to-quickly-edit-gif/"><u>Top 20+ Best Free GIF Makers Online to Quickly Edit GIF</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pump-it-up-the-20-most-energizing-workout-playlists/"><u>In 2024, Pump It Up  The 20 Most Energizing Workout Playlists</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-about-motorola-defy-2-frp-bypass-by-drfone-android/"><u>In 2024, About Motorola Defy 2 FRP Bypass</u></a></li>
<li><a href="https://games-able.techidaily.com/analyzing-input-techniques-polling-rates-role/"><u>Analyzing Input Techniques: Polling Rate's Role</u></a></li>
<li><a href="https://games-able.techidaily.com/1719161846220-joy-con-plus-the-ultimate-guide-for-controller-extension-92-chars-this-title-slightly-exceeds-but-is-relevant-enough-to-be-considered-within-the-limit/"><u>Joy-Con Plus: The Ultimate Guide for Controller Extension (92 Chars) – This Title Slightly Exceeds but Is Relevant Enough to Be Considered Within the Limit</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-mastering-motion-blur-a-step-by-step-fcp-tutorial/"><u>New In 2024, Mastering Motion Blur A Step-by-Step FCP Tutorial</u></a></li>
<li><a href="https://games-able.techidaily.com/the-essentials-for-mastering-palworld/"><u>The Essentials for Mastering PalWorld</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-for-pre-buy-reflection-with-ps5/"><u>The Ultimate Guide for Pre-Buy Reflection with PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/making-steam-activities-child-approved-and-fun/"><u>Making Steam Activities Child-Approved and Fun</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-unravel-your-console-dismantling-an-xbox-series-controller/"><u>How to Unravel Your Console: Dismantling an Xbox Series Controller</u></a></li>
<li><a href="https://games-able.techidaily.com/what-steams-new-rules-on-ai-games-mean-for-gamers/"><u>What Steam's New Rules on AI Games Mean for Gamers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-honor-play-40c-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Honor Play 40C Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-crafting-colorful-snaps-embrace-snapchats-anime-filters/"><u>[New] In 2024, Crafting Colorful Snaps  Embrace Snapchat's Anime Filters</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-from-beginner-to-pro-final-cut-pro-2024-tutorial-collection/"><u>New From Beginner to Pro Final Cut Pro 2024 Tutorial Collection</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/indulge-in-pure-play-celebrating-the-top-10-offline-games-for-2024/"><u>Indulge in Pure Play - Celebrating the Top 10 Offline Games for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-cutting-edge-tools-the-leading-applications-for-discoemojis/"><u>[Updated] Cutting-Edge Tools  The Leading Applications for DiscoEmojis</u></a></li>
<li><a href="https://games-able.techidaily.com/nostalgia-at-a-swipe-ios-and-the-classics-of-psp/"><u>Nostalgia at a Swipe: IOS and the Classics of PSP!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-access-your-apple-iphone-14-pro-max-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>How to Access Your Apple iPhone 14 Pro Max When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-screen-lock-pin-on-poco-x5-like-a-pro-5-easy-ways-by-drfone-android/"><u>In 2024, How To Remove Screen Lock PIN On Poco X5 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://games-able.techidaily.com/titanium-links-choosing-the-ultimate-gaming-networks/"><u>Titanium Links - Choosing The Ultimate Gaming Networks</u></a></li>
<li><a href="https://games-able.techidaily.com/safe-operating-zones-navigating-gpu-temps/"><u>Safe Operating Zones: Navigating GPU Temps</u></a></li>
<li><a href="https://games-able.techidaily.com/optimal-companionship-in-couch-gaming-16-for-next-gen-xbox/"><u>Optimal Companionship in Couch Gaming: 16 for Next-Gen XBox</u></a></li>
<li><a href="https://games-able.techidaily.com/overcome-noisy-controller-revive-headset-connection/"><u>Overcome Noisy Controller: Revive Headset Connection</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-how-to-upload-horizontal-videos-to-igtv/"><u>[New] 2024 Approved  How to Upload Horizontal Videos to IGTV</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/um-viewership-the-ultimate-youtube-wealth/"><u>Premium Viewership  The Ultimate YouTube Wealth</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-game-performance-on-series-sx-through-expertly-setup-vrr-settings/"><u>Boosting Game Performance on Series S/X Through Expertly Setup VRR Settings</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-white-tech-for-maximum-performance/"><u>Affordable White Tech for Maximum Performance</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-record-breaking-content-top-youtube-videos-reaching-milestone-in-24/"><u>In 2024, Record-Breaking Content  Top YouTube Videos Reaching Milestone in '24</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/most-asked-questions-about-pokemon-go-battle-league-rewards-on-apple-iphone-11-drfone-by-drfone-virtual-ios/"><u>Most Asked Questions about Pokemon Go Battle League Rewards On Apple iPhone 11 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-asus-rog-phone-7-ultimate-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Asus ROG Phone 7 Ultimate? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pinterest-content-powered-free-high-speed-download-apps-reviewed-for-2024/"><u>Pinterest Content Powered  Free, High-Speed Download Apps Reviewed for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-from-your-apple-iphone-14-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID From Your Apple iPhone 14</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-boldness-masterful-frame-rate-strategies/"><u>Boosting Boldness: Masterful Frame Rate Strategies</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/trim-videos-for-free-7-watermark-free-editors/"><u>Trim Videos for Free 7 Watermark-Free Editors</u></a></li>
<li><a href="https://games-able.techidaily.com/the-powerhouse-platform-an-introduction-to-twitchs-offerings/"><u>The Powerhouse Platform: An Introduction to Twitch's Offerings</u></a></li>
<li><a href="https://games-able.techidaily.com/my-journey-with-an-oled-display-the-ultimate-gaming-setup/"><u>My Journey with an OLED Display - The Ultimate Gaming Setup</u></a></li>
<li><a href="https://games-able.techidaily.com/primes-pathway-to-premium-twitch-viewing/"><u>Prime's Pathway to Premium Twitch Viewing</u></a></li>
<li><a href="https://games-able.techidaily.com/move-up-or-down-switching-console-zones/"><u>Move Up or Down: Switching Console Zones</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-top-5-guitar-recording-software/"><u>Updated In 2024, Top 5 Guitar Recording Software</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-core-elements-for-exciting-mobile-gaming/"><u>Mastering Core Elements for Exciting Mobile Gaming</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>Life360 Circle Everything You Need to Know On Apple iPhone 6s Plus | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/unlock-facebook-potential-with-effective-engagement-strategies-for-2024/"><u>Unlock Facebook Potential with Effective Engagement Strategies for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/the-racers-question-physical-input-vs-digital-dashboard-dominance/"><u>The Racer's Question: Physical Input Vs. Digital Dashboard Dominance</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-snapshot-hits-must-have-filters-to-enhance-your-snap/"><u>[Updated] In 2024, Snapshot Hits  Must-Have Filters to Enhance Your Snap</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-audio-experience-for-switch/"><u>Superior Audio Experience for Switch</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-secure-your-content-free-windows-screenshot-tools/"><u>[New] Secure Your Content  Free Windows Screenshot Tools</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-premium-8k-vision-selecting-the-superior-cameras/"><u>[New] Premium 8K Vision  Selecting the Superior Cameras</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-fix-or-replace-a-broken-nintendo-switch/"><u>Troubleshooting: Fix or Replace a Broken Nintendo Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/bluetooth-headphones-for-playstation-5/"><u>Bluetooth Headphones for PlayStation 5</u></a></li>
<li><a href="https://games-able.techidaily.com/maximizing-playability-with-epic-games-on-steam-deck/"><u>Maximizing Playability with Epic Games on Steam Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-to-handle-xbox-gold-on-series-xs/"><u>Strategies to Handle Xbox Gold on Series X/S</u></a></li>
<li><a href="https://games-able.techidaily.com/the-art-of-choosing-prime-games-in-apples-marketplace/"><u>The Art of Choosing Prime Games in Apple's Marketplace</u></a></li>
<li><a href="https://games-able.techidaily.com/taking-your-games-home-taking-control/"><u>Taking Your Games Home, Taking Control</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-game-console-emulations-that-enhance-your-macgaming/"><u>Top 5 Game Console Emulations That Enhance Your macGaming</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/innovative-tactics-for-stellar-facebook-ad-videos-for-2024/"><u>Innovative Tactics for Stellar Facebook Ad Videos for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/tailoring-xbox-series-sxs-vrr-settings-a-step-by-step-guide/"><u>Tailoring Xbox Series S/X's VRR Settings: A Step-by-Step Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/peering-into-virtual-world-costs-4-detail-driven-insights/"><u>Peering Into Virtual World Costs: 4 Detail-Driven Insights</u></a></li>
<li><a href="https://games-able.techidaily.com/troubleshooting-steam-deck-overcoming-cloud-sync-issues/"><u>Troubleshooting Steam Deck: Overcoming Cloud Sync Issues</u></a></li>
</ul></div>

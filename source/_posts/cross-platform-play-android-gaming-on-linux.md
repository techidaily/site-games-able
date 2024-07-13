---
title: "Cross-Platform Play: Android Gaming on Linux"
date: 2024-07-12T03:38:21.939Z
updated: 2024-07-13T03:38:21.939Z
tags:
  - games
categories:
  - games
description: "This Article Describes Cross-Platform Play: Android Gaming on Linux"
excerpt: "This Article Describes Cross-Platform Play: Android Gaming on Linux"
keywords: Cross-Platform Mobile Gaming,Linux Gaming Community,Open Source Game Development,Unity for Linux Games,Mobile Game Interoperability,Multiplayer Games Across Platforms,Cross-OS Gaming Trends
thumbnail: https://thmb.techidaily.com/8902585d66f327811523945d1407154d052552e159a549922c8c259267eab9e9.png
---

## Cross-Platform Play: Android Gaming on Linux

### Key Takeaways

* Waydroid is the best option for running Android apps on Linux systems using Wayland display server, such as newer versions of Ubuntu, Fedora, Debian, or Arch.
* Creating an Android virtual machine using the open-source Android x86 project is a simple way to run Android apps on your Linux PC.
* Android Studio is primarily for developers but can be used to create a personal Android Virtual Device (AVD) for running Android apps on Linux.

 While you might not be able to install Bluestacks, there are a few fantastic methods you can use to run Android apps and games on your Linux PC. You can create an Android virtual machine, install Waydroid, emulate with Android Studio, or even purchase Genymotion and enjoy a highly supported emulation experience.

## What Is the Best Option for Running Android Apps on Linux?

 You have quite a few methods to choose from to run Android apps and games on Linux. As mentioned before, creating an Android virtual machine, using Android Studio, installing Waydroid, and purchasing Genymotion are just a few of your options.

 You’ll need to consider your own Linux setup and desired emulation experience to determine which option is best. Here’s a basic overview:

* **Waydroid:** This application is the best option for Linux systems using the Wayland display server. If you use a newer version of Ubuntu, Fedora, Debian, or Arch, you’re probably using Wayland.
* **Create an Android virtual machine:** If you want to run an extremely simple Android system, you can use the open-source Android x86 project by installing it as a virtual machine on your PC.
* **Use Android Studio:** Android Studio is primarily geared towards developers, but you can also use it to create a personal Android Virtual Device (AVD). This isn’t the best method due to the inherent learning curve, however.
* **Genymotion:** This pay-to-use application offers a convenient way to run Android virtual devices. It’s particularly good for developers, but you may also enjoy it if you want the level of support that a premium application offers.

 Many guides recommend installing Anbox—but unfortunately, this application was deprecated in February 2023\. You’ll need to find a supported alternative if you want to run Android apps.

## 1\. Use Waydroid to Play Android Games

 Overall, the best method to run Android games in light of the deprecation of Anbox is using Waydroid. Before you can start using Waydroid, though, it’s important to check whether you’re running the requisite display server: Wayland.

 You can check whether your system runs Wayland by opening the terminal and entering the following to print your session type:

`echo $XDG_SESSION_TYPE`

![checking system display server type in terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/checking-system-display-server-type-in-terminal.jpg)

 If your system runs the Xorg display server, you’ll need to switch from Xorg to Wayland before you can install Waydroid.

 On Ubuntu, you can switch to Wayland by logging out of your user account and clicking the**Gear** icon on the login screen. When the drop-down list of display options appears, click**Ubuntu** to switch out of the Ubuntu on Xorg configuration.

 Next, you should update your system’s package list. This will ensure that the software packages you install are all completely up-to-date. Enter the following to update the package list:

`sudo apt update`

 You’ll also need to follow the [Waydroid](https://docs.waydro.id/usage/install-on-desktops) installation instructions for your specific Linux distribution. On Ubuntu, Debian, and their derivatives, you can install Waydroid by entering the following in the terminal to install prerequisites, add the Waydroid repository to your system, and install Waydroid:

`sudo apt install curl ca-certificates -y  
curl https://repo.waydro.id | sudo bash  
sudo apt install waydroid -y`

 Once Waydroid is installed, you’ll need to take a few steps to initialize the program. You’ll need to start the Waydroid container and enable its GUI (Graphical User Interface). You can accomplish this by entering:

`sudo waydroid container start  
waydroid show-full-ui`

 Finally, you’re ready to install Android apps on your PC. You’ll need to [navigate to a reputable website like APKMirror or APKPure](https://www.makeuseof.com/tag/safe-android-apk-downloads/) to download the APK file for each app you want to install. Once you’ve downloaded your APKs, enter the following to install the app on your system:

`waydroid app install appname.apk`

 Wait for the app to install. Once the installation process is complete, you can run the Android app by selecting it through the Waydroid GUI, launching it through your desktop application menu, or launching it from the terminal with:

`waydroid app launch appname`

## 2\. Create an Android Virtual Machine

 If you’re comfortable creating a virtual machine, one of the best ways to run Android apps and games on your Linux PC is to virtualize an Android x86 system. To start, you’ll need to download the Android x86 ISO image.

 You’ll also need to download your virtualization software of choice—in this case, we’ll use VirtualBox. This software is suitable for Ubuntu, Debian, openSUSE, and derivative distributions.

**Download:** [Android x86](http://www.android-x86.org/)

**Download:** [VirtualBox](https://www.virtualbox.org/wiki/Linux%5FDownloads)

 Download the appropriate package for your Linux distribution, then install it from the terminal.

 On Ubuntu and Debian-based distros, right-click on the file and select**Open with another application** . Select**Software Install** from the dropdown list, and finally, click**Install** . Wait for VirtualBox to finish installing on your system.

 Once it’s finished installing, open VirtualBox. Click on the**New** button to create a new virtual machine, setting the following configurations:

* **Type:** Linux
* **Version:** Linux 2.6 / 3.x / 4.x (32-bit or 64-bit depends on which version of Android x86 you installed)
* **RAM:** 2GB (2048MB) minimum, more if possible
* **HDD file type:** VDI (VirtualBox Disk Image)
* **Storage:** Dynamically allocated
* **HDD:** 8GB (8192MB) minimum, more if possible

 After you’ve created the new virtual machine, you’ll still need to configure a few more settings. Select your new virtual machine from the list of VMs and click on**Settings** . In**System > Processor** , allocate two or more CPU cores.

 In**System > Acceleration** , select KVM as the paravirtualization interface. In the**Display > Screen** tab, you’ll need to change the Graphics Controller setting to**VBoxSVGA** .

![configuring graphics settings in virtualbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/configuring-graphics-settings-in-virtualbox.jpg)

 Last but not least, you’ll need to install the Android x86 image. Navigate to the**Storage** tab and select**Empty** from the list of storage devices. Next, click on the**blue disc** icon to the right of the**Optical Drive** setting and select**Choose a disk file** from the dropdown menu. Select your Android x86 ISO from the Files interface that appears. Finally, close the settings menu and click**Start** to boot your Android VM.

 As prompts appear on the new virtual machine, click**Advanced Options** , select**Auto\_Installation** from the advanced options list, and then click**Yes** to confirm the auto installation.

 Once the installation process is complete, you can configure and install apps on your new Android virtual machine.

## 3\. Use Android Studio for Seamless Gaming

 While Android Studio is primarily geared towards developers, it can be an excellent option for emulation if you aren’t interested in using Waydroid or an Android x86 virtual machine. After [installing Android Studio](https://www.makeuseof.com/install-android-studio-ubuntu/) , you’ll need to create an Android Virtual Device (AVD) using the official [Android](https://developer.android.com/studio/run/emulator#avd) Developer’s guide and then install your chosen APK on the [Android](https://developer.android.com/studio/run/emulator-install-add-files) Emulator.

## 4\. Run Android Apps on Linux With Genymotion

 It’s worth considering applications like Waydroid and even tried-and-true virtual machines before you purchase Genymotion. In most cases, it’s possible to accomplish anything you want on your Linux PC without purchasing proprietary applications.

 If you choose to purchase Genymotion, however, you’ll be enthused with the ease of use and convenience that this application offers.

![comparing the plans offered by genymotion](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/comparing-the-plans-offered-by-genymotion.jpg)

 To start, you’ll need to purchase the right Genymotion plan. Genymotion offers a free plan for personal use, but any technical support requests beyond issues with installation and first run will be rejected—and you won’t be able to use features like Android 13, camera and media widget features, and quick boot.

 If you’re a current student or teacher, you can use your school ID to purchase full-featured Genymotion for $49 per year.

 Once you’ve downloaded the Genymotion BIN file, you can install it with QEMU or VirtualBox using [Genymotion’s](https://docs.genymotion.com/desktop/Get%5Fstarted/013%5FLinux%5Finstall/) official installation guide.

## Enjoy Using Android Apps and Games on Your Linux System

 With the deprecation of Anbox, it’s easy to wonder if any easy methods to run Android apps on Linux systems remain. Luckily, Waydroid, Android x86, Android Studio, and Genymotion all offer distinct and easy ways to run Android apps.

 Once you’ve chosen which software to use, you’ll be amazed at just how convenient and seamless using these apps is.


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
<li><a href="https://games-able.techidaily.com/5-reasons-why-you-shouldnt-trust-game-reviews-or-review-scores/"><u>5 Reasons Why You Shouldn't Trust Game Reviews or Review Scores</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-creative-capture-of-sims-4-sagas-innovative-ways-to-record-your-journey/"><u>[New] 2024 Approved  Creative Capture of Sims 4 Sagas  Innovative Ways to Record Your Journey</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/unleash-your-creativity-top-rated-video-collage-apps-for-iphone-and-ipad-for-2024/"><u>Unleash Your Creativity Top-Rated Video Collage Apps for iPhone and iPad for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/a-tutorial-for-ps4ps5-to-nintendo-switch-connections/"><u>A Tutorial for PS4/PS5 to Nintendo Switch Connections</u></a></li>
<li><a href="https://extra-support.techidaily.com/step-by-step-guide-to-elevating-your-reddit-game-for-2024/"><u>Step-by-Step Guide to Elevating Your Reddit Game for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/2024-ddr5-board-excellence-guide/"><u>2024 DDR5 Board Excellence Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-boosting-engagement-a-guide-to-more-youtube-shorts-success/"><u>[New] Boosting Engagement  A Guide to More YouTube Shorts Success</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-error-0x803f8001-during-minecraft-startup/"><u>Addressing Error 0X803F8001 During Minecraft Startup</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-mastering-quick-video-pace-adjustments-on-youtube/"><u>[Updated] Mastering Quick Video Pace Adjustments on YouTube</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-comprehensive-tips-for-youtube-video-capture-for-2024/"><u>[Updated] Comprehensive Tips for YouTube Video Capture for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172049939-secure-your-ultimate-marvel-gaming-experience-now/"><u>Secure Your Ultimate Marvel Gaming Experience Now</u></a></li>
<li><a href="https://games-able.techidaily.com/6-insights-for-prospective-ps5-shoppers/"><u>6 Insights for Prospective PS5 Shoppers</u></a></li>
<li><a href="https://games-able.techidaily.com/7-unrecognized-benefits-in-ignoring-ray-tracings-hype/"><u>7 Unrecognized Benefits in Ignoring Ray Tracing's Hype</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-guide-to-using-ps5-assist-controller/"><u>A Comprehensive Guide to Using PS5 Assist Controller</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-find-three-best-alternatives-to-subtitle-edit-on-mac-all-are-free-and-include-the-same-exact-functions-as-subtitle-edit/"><u>2024 Approved Find Three Best Alternatives to Subtitle Edit on Mac - All Are Free and Include the Same Exact Functions as Subtitle Edit</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-oppo-a38-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Oppo A38? Look No Further | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensible-approach-to-locking-your-ps5-games/"><u>A Comprehensible Approach to Locking Your PS5 Games</u></a></li>
<li><a href="https://games-able.techidaily.com/6-ways-to-cope-with-gaming-burnout/"><u>6 Ways to Cope With Gaming Burnout</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-remove-icloud-on-iphone-15-pro-smoothly-by-drfone-ios/"><u>In 2024, How To Remove iCloud On iPhone 15 Pro Smoothly</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168136117-relive-your-favorite-xbox-moments-emulate-today/"><u>Relive Your Favorite Xbox Moments: Emulate Today!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168571839-champion-mousepads-reviewed/"><u>Champion Mousepads Reviewed!</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-immerse-in-windows-11s-photo-quality-filter-options-and-music-playlists/"><u>2024 Approved  Immerse in Windows 11'S Photo Quality  Filter Options and Music Playlists</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-strategies-for-finding-no-cost-art/"><u>[Updated] Expert Strategies for Finding No-Cost Art</u></a></li>
<li><a href="https://games-able.techidaily.com/8-superior-traits-of-microsoft-edge-in-games/"><u>8 Superior Traits of Microsoft Edge in Games</u></a></li>
<li><a href="https://games-able.techidaily.com/5-reasons-gamefi-will-never-take-off-or-attract-real-gamers/"><u>5 Reasons GameFi Will Never Take Off or Attract Real Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/acquiring-your-steam-identifier-without-hassle/"><u>Acquiring Your Steam Identifier Without Hassle</u></a></li>
<li><a href="https://games-able.techidaily.com/ace-the-game-mastering-frame-rate-improvement-techniques-for-windows-users/"><u>Ace the Game: Mastering Frame Rate Improvement Techniques for Windows Users</u></a></li>
<li><a href="https://games-able.techidaily.com/5-best-practices-for-extending-the-life-of-your-nintendo-switch/"><u>5 Best Practices for Extending the Life of Your Nintendo Switch</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-combine-power-tweeting-and-snapping-with-snapchat-for-2024/"><u>[Updated] Combine Power  Tweeting and Snapping with Snapchat for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/a-critical-perspective-on-portable-playing-pleasures/"><u>A Critical Perspective on Portable Playing Pleasures</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-apple-id-activation-lock-on-apple-iphone-15-by-drfone-ios/"><u>How to Unlock Apple ID Activation Lock On Apple iPhone 15?</u></a></li>
<li><a href="https://games-able.techidaily.com/a-compreenas-remove-old-ps5-saved-files-and-backups-quickly/"><u>A Compreenas Remove Old PS5 Saved Files and Backups Quickly</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-demystifying-creative-commons-and-its-legalities/"><u>[Updated] Demystifying Creative Commons and Its Legalities</u></a></li>
<li><a href="https://android-frp.techidaily.com/realme-12-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Realme 12 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://games-able.techidaily.com/a-beginners-guide-to-transforming-gaming-via-twitch-mobile/"><u>A Beginner's Guide to Transforming Gaming via Twitch (Mobile)</u></a></li>
<li><a href="https://games-able.techidaily.com/7-critical-considerations-against-incorporating-ray-tracing/"><u>7 Critical Considerations Against Incorporating Ray Tracing</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-instant-designing-techniques-for-fortnite-images/"><u>[New] In 2024, Instant Designing Techniques for Fortnite Images</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170517578-mastering-xbox-one-play-anyhow/"><u>Mastering Xbox One: Play Anyhow</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-transform-your-recording-experience-moving-past-fbx-methods/"><u>[Updated] 2024 Approved  Transform Your Recording Experience  Moving Past FBX Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-by-step-guide-to-complain-against-an-xbox-player/"><u>A Step by Step Guide to Complain Against an Xbox Player</u></a></li>
<li><a href="https://games-able.techidaily.com/5-ways-game-subscriptions-cant-replace-owning-your-games/"><u>5 Ways Game Subscriptions Can't Replace Owning Your Games</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-hitting-high-notes-enhance-your-youtube-content-with-music-edits-for-2024/"><u>[Updated] Hitting High Notes  Enhance Your YouTube Content with Music Edits for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-there-are-several-options-for-smoothing-and-stabilizing-motion-in-after-effects-stable-footage-the-three-most-important-methods-to-master-are-listed/"><u>Updated There Are Several Options for Smoothing and Stabilizing Motion in After Effects Stable Footage. The Three Most Important Methods to Master Are Listed Below</u></a></li>
<li><a href="https://games-able.techidaily.com/advanced-methods-for-recording-gameplay-on-xbox/"><u>Advanced Methods for Recording Gameplay on Xbox</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-sharexs-standards-met-by-others/"><u>[Updated] ShareX's Standards Met by Others</u></a></li>
<li><a href="https://games-able.techidaily.com/460plus-rapid-response-monitor-innocn-39g1-r/"><u>$460+ Rapid Response Monitor: InnoCN 39G1 R</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-10-mobile-relaxation-renders-idle-games/"><u>Top 10 Mobile Relaxation Renders (Idle Games)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/amplify-your-storytelling-seamlessly-insert-music-into-youtube-videos/"><u>Amplify Your Storytelling  Seamlessly Insert Music Into YouTube Videos</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170904655-explore-nvidias-innovation-for-gamers-worldwide/"><u>Explore Nvidia's Innovation for Gamers Worldwide</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/5-ways-to-track-apple-iphone-15-plus-without-app-drfone-by-drfone-virtual-ios/"><u>5 Ways to Track Apple iPhone 15 Plus without App | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/professional-grade-grid-tools-for-striking-instagram-posts/"><u>Professional-Grade Grid Tools for Striking Instagram Posts</u></a></li>
<li><a href="https://games-able.techidaily.com/7-engaging-virtual-experiences-to-fortify-design-expertise/"><u>7 Engaging Virtual Experiences to Fortify Design Expertise</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169021532-is-bottlenecking-by-cpu-happening-to-your-pc-find-out/"><u>Is Bottlenecking by CPU Happening to Your PC? Find Out</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-conquer-chrome-multitasking-learn-to-utilize-pip-effectively/"><u>In 2024, Conquer Chrome Multitasking  Learn to Utilize PIP Effectively</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-unleash-the-pro-in-you-turn-everyday-moments-into-breathtaking-films/"><u>2024 Approved Unleash the Pro in You Turn Everyday Moments Into Breathtaking Films</u></a></li>
<li><a href="https://games-able.techidaily.com/2023s-tech-showcase-pioneering-games-devices/"><u>2023'S Tech Showcase: Pioneering Games Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/5-shortcomings-hindering-gamefis-integration-with-gamers/"><u>5 Shortcomings Hindering GameFi’s Integration with Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/7-reasons-to-rethink-mobile-game-advantages/"><u>7 Reasons to Rethink Mobile Game Advantages</u></a></li>
</ul></div>

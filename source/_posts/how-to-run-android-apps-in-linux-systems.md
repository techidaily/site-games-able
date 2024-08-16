---
title: How to Run Android Apps in Linux Systems
date: 2024-08-15T17:23:35.860Z
updated: 2024-08-16T17:23:35.860Z
tags:
  - games
categories:
  - games
description: This Article Describes How to Run Android Apps in Linux Systems
excerpt: This Article Describes How to Run Android Apps in Linux Systems
keywords: Running Android Apps on Linux,Emulator Software for Android App Execution in Linux,Android App Compatibility with Linux Systems,Cross-Platform Development,Using BlueStacks to Run Android Apps on Linux,The Best Tools for Running Android Apps on Linux,How to Install and Use Android Terminal in Linux for App Execution
thumbnail: https://thmb.techidaily.com/a23ef58f3369824904efee9f97817b15b093c9dc4ea1ce81d7226560e11dda64.jpg
---

## How to Run Android Apps in Linux Systems

### Key Takeaways

* Waydroid is the best option for running Android apps on Linux systems using Wayland display server, such as newer versions of Ubuntu, Fedora, Debian, or Arch.
* Creating an Android virtual machine using the open-source Android x86 project is a simple way to run Android apps on your Linux PC.
* Android Studio is primarily for developers but can be used to create a personal Android Virtual Device (AVD) for running Android apps on Linux.

 While you might not be able to install Bluestacks, there are a few fantastic methods you can use to run Android apps and games on your Linux PC. You can create an Android virtual machine, install Waydroid, emulate with Android Studio, or even purchase Genymotion and enjoy a highly supported emulation experience.

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Is the Best Option for Running Android Apps on Linux?

 You have quite a few methods to choose from to run Android apps and games on Linux. As mentioned before, creating an Android virtual machine, using Android Studio, installing Waydroid, and purchasing Genymotion are just a few of your options.

 You’ll need to consider your own Linux setup and desired emulation experience to determine which option is best. Here’s a basic overview:

* **Waydroid:** This application is the best option for Linux systems using the Wayland display server. If you use a newer version of Ubuntu, Fedora, Debian, or Arch, you’re probably using Wayland.
* **Create an Android virtual machine:** If you want to run an extremely simple Android system, you can use the open-source Android x86 project by installing it as a virtual machine on your PC.
* **Use Android Studio:** Android Studio is primarily geared towards developers, but you can also use it to create a personal Android Virtual Device (AVD). This isn’t the best method due to the inherent learning curve, however.
* **Genymotion:** This pay-to-use application offers a convenient way to run Android virtual devices. It’s particularly good for developers, but you may also enjoy it if you want the level of support that a premium application offers.

 Many guides recommend installing Anbox—but unfortunately, this application was deprecated in February 2023\. You’ll need to find a supported alternative if you want to run Android apps.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 1\. Use Waydroid to Play Android Games

 Overall, the best method to run Android games in light of the deprecation of Anbox is using Waydroid. Before you can start using Waydroid, though, it’s important to check whether you’re running the requisite display server: Wayland.

 You can check whether your system runs Wayland by opening the terminal and entering the following to print your session type:

`echo $XDG_SESSION_TYPE`

![checking system display server type in terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/checking-system-display-server-type-in-terminal.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If your system runs the Xorg display server, you’ll need to switch from Xorg to Wayland before you can install Waydroid.

 On Ubuntu, you can switch to Wayland by logging out of your user account and clicking the**Gear** icon on the login screen. When the drop-down list of display options appears, click**Ubuntu** to switch out of the Ubuntu on Xorg configuration.

 Next, you should update your system’s package list. This will ensure that the software packages you install are all completely up-to-date. Enter the following to update the package list:

`sudo apt update`

 You’ll also need to follow the[Waydroid](https://docs.waydro.id/usage/install-on-desktops) installation instructions for your specific Linux distribution. On Ubuntu, Debian, and their derivatives, you can install Waydroid by entering the following in the terminal to install prerequisites, add the Waydroid repository to your system, and install Waydroid:

`sudo apt install curl ca-certificates -y  
curl https://repo.waydro.id | sudo bash  
sudo apt install waydroid -y`

 Once Waydroid is installed, you’ll need to take a few steps to initialize the program. You’ll need to start the Waydroid container and enable its GUI (Graphical User Interface). You can accomplish this by entering:

`sudo waydroid container start  
waydroid show-full-ui`

 Finally, you’re ready to install Android apps on your PC. You’ll need to[navigate to a reputable website like APKMirror or APKPure](https://www.makeuseof.com/tag/safe-android-apk-downloads/) to download the APK file for each app you want to install. Once you’ve downloaded your APKs, enter the following to install the app on your system:

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## 3\. Use Android Studio for Seamless Gaming

 While Android Studio is primarily geared towards developers, it can be an excellent option for emulation if you aren’t interested in using Waydroid or an Android x86 virtual machine. After[installing Android Studio](https://www.makeuseof.com/install-android-studio-ubuntu/) , you’ll need to create an Android Virtual Device (AVD) using the official[Android](https://developer.android.com/studio/run/emulator#avd) Developer’s guide and then install your chosen APK on the[Android](https://developer.android.com/studio/run/emulator-install-add-files) Emulator.

## 4\. Run Android Apps on Linux With Genymotion

 It’s worth considering applications like Waydroid and even tried-and-true virtual machines before you purchase Genymotion. In most cases, it’s possible to accomplish anything you want on your Linux PC without purchasing proprietary applications.

 If you choose to purchase Genymotion, however, you’ll be enthused with the ease of use and convenience that this application offers.

![comparing the plans offered by genymotion](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/comparing-the-plans-offered-by-genymotion.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->

 To start, you’ll need to purchase the right Genymotion plan. Genymotion offers a free plan for personal use, but any technical support requests beyond issues with installation and first run will be rejected—and you won’t be able to use features like Android 13, camera and media widget features, and quick boot.

 If you’re a current student or teacher, you can use your school ID to purchase full-featured Genymotion for $49 per year.

 Once you’ve downloaded the Genymotion BIN file, you can install it with QEMU or VirtualBox using[Genymotion’s](https://docs.genymotion.com/desktop/Get%5Fstarted/013%5FLinux%5Finstall/) official installation guide.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-step-by-step-privacy-adjustments-for-youtube/"><u>[New] 2024 Approved  Step-by-Step Privacy Adjustments for YouTube</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-youtube-tagging-101-for-better-engagement/"><u>[New] 2024 Approved  YouTube Tagging 101 for Better Engagement</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-a-pictures-worth-a-thousand-dollars-online-top-photo-cloud-services-reviewed/"><u>[New] A Picture's Worth a Thousand Dollars Online  Top Photo Cloud Services Reviewed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-free-online-solutions-for-instantaneous-gif-conversion/"><u>[New] Best Free Online Solutions For Instantaneous GIF Conversion</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-eclipsing-fears-in-your-first-10-videos-for-2024/"><u>[New] Eclipsing Fears in Your First 10 Videos for 2024</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-simple-process-for-preserving-tweets-imagesvideos/"><u>[New] In 2024, Simple Process for Preserving Tweets' Images/Videos</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-inter-device-image-sharing-expertise/"><u>[New] Inter-Device Image Sharing Expertise</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mastering-iphones-video-reduction-and-adjustment-tools/"><u>[New] Mastering iPhone's Video Reduction and Adjustment Tools</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-maximizing-content-impact-bypassing-virtual-onlookers/"><u>[New] Maximizing Content Impact  Bypassing Virtual Onlookers</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-comprehensive-guide-to-dji-phantom-3-testing/"><u>[New] The Comprehensive Guide to DJI Phantom 3 Testing</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-ultimate-night-photos-checklist-dos-and-donts/"><u>[New] The Ultimate Night Photos Checklist  Do's and Don'ts</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-5-premium-4k-displays-for-the-hardcore-gamer/"><u>[Updated] 5 Premium 4K Displays for the Hardcore Gamer</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-best-practices-in-updating-your-social-network-backdrop/"><u>[Updated] Best Practices in Updating Your Social Network Backdrop</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-documentary-script-artistry/"><u>2024 Approved  Mastering Documentary Script Artistry</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-methods-for-turning-vimeo-content-into-mp3/"><u>2024 Approved  Methods for Turning Vimeo Content Into MP3</u></a></li>
<li><a href="https://games-able.techidaily.com/advanced-techniques-for-steam-shot-collection/"><u>Advanced Techniques for Steam Shot Collection</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-overcharges-with-smart-game-management/"><u>Avoid Overcharges with Smart Game Management</u></a></li>
<li><a href="https://extra-information.techidaily.com/best-mobile-gif-apps-roundup-for-latest-phones-for-2024/"><u>Best Mobile GIF Apps Roundup for Latest Phones for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-brilliance-top-deals-on-cost-effective-mobo/"><u>Budget Brilliance: Top Deals on Cost-Effective Mobo</u></a></li>
<li><a href="https://games-able.techidaily.com/durability-and-design-selecting-the-perfect-casing-in-24/"><u>Durability & Design: Selecting the Perfect Casing in '24</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elite-selection-of-steadicams-for-drones-in-videography/"><u>Elite Selection of Steadicams for Drones in Videography</u></a></li>
<li><a href="https://games-able.techidaily.com/emulating-legends-pokemon-games-resurgence/"><u>Emulating Legends: Pokémon Games' Resurgence</u></a></li>
<li><a href="https://games-able.techidaily.com/escaping-realms-backup-your-buildings-bring-them-back/"><u>Escaping Realms: Backup Your Buildings, Bring Them Back</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-tips-for-resetting-ps5-gamepad/"><u>Essential Tips for Resetting PS5 Gamepad</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-the-benefits-of-switching-to-rtx-post-gtx-phase/"><u>Evaluating the Benefits of Switching to RTX Post-GTX Phase</u></a></li>
<li><a href="https://games-able.techidaily.com/examining-xbox-encasements/"><u>Examining Xbox Encasements</u></a></li>
<li><a href="https://games-able.techidaily.com/foremost-phone-titles-with-controller-integration/"><u>Foremost Phone Titles with Controller Integration</u></a></li>
<li><a href="https://games-able.techidaily.com/gamers-choice-selecting-the-best-audio-gear/"><u>Gamer’s Choice: Selecting the Best Audio Gear</u></a></li>
<li><a href="https://games-able.techidaily.com/hall-effect-keys-in-focus-review-of-modular-board-mod007b/"><u>Hall Effect Keys in Focus - Review of Modular Board MOD007B</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-halt-steam-initialization/"><u>How to Halt Steam Initialization</u></a></li>
<li><a href="https://games-able.techidaily.com/ifa-2023-gaming-innovation-showcase/"><u>IFA 2023 Gaming Innovation Showcase</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-easy-methods-to-unlock-icloud-locked-apple-iphone-13-miniipadipod-by-drfone-ios/"><u>In 2024, 3 Easy Methods to Unlock iCloud Locked Apple iPhone 13 mini/iPad/iPod</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-boost-engagement-on-youtube-by-adding-emojis/"><u>In 2024, Boost Engagement on YouTube by Adding Emojis</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-motorola-moto-g04-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Motorola Moto G04 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unraveling-the-mystery-of-online-broadcast-archiving/"><u>In 2024, Unraveling the Mystery of Online Broadcast Archiving</u></a></li>
<li><a href="https://games-able.techidaily.com/indulge-your-playstation-fondness-with-30-expertly-chosen-pc-emulators/"><u>Indulge Your PlayStation Fondness with 30 Expertly Chosen PC Emulators</u></a></li>
<li><a href="https://games-able.techidaily.com/international-gaming-exploration-via-region-change/"><u>International Gaming Exploration via Region Change</u></a></li>
<li><a href="https://games-able.techidaily.com/join-forces-in-these-20-cross-system-gaming-adventures/"><u>Join Forces in These 20 Cross-System Gaming Adventures</u></a></li>
<li><a href="https://games-able.techidaily.com/master-varied-strategies-check-out-the-best-6-unique-chess-apps/"><u>Master Varied Strategies: Check Out the Best 6 Unique Chess Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-volume-control-on-xbox-s-and-x-series-x/"><u>Mastering Volume Control on Xbox S & X Series X</u></a></li>
<li><a href="https://games-able.techidaily.com/offline-entertainment-11-in-app-phone-games/"><u>Offline Entertainment: 11 In-App Phone Games</u></a></li>
<li><a href="https://games-able.techidaily.com/overseas-playtime-alter-time-settings-on-sxxb1/"><u>Overseas Playtime: Alter Time Settings on SX/XB1</u></a></li>
<li><a href="https://games-able.techidaily.com/patching-for-purists-rom-linguistic-tweaks/"><u>Patching for Purists: ROM Linguistic Tweaks</u></a></li>
<li><a href="https://games-able.techidaily.com/post-gtx-era-assessing-the-need-for-an-immediate-rtx-shift/"><u>Post-GTX Era: Assessing the Need for an Immediate RTX Shift</u></a></li>
<li><a href="https://games-able.techidaily.com/reinstating-stable-wired-and-wireless-connections-in-ps5/"><u>Reinstating Stable Wired and Wireless Connections in PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/reversing-windows-gpu-hang-addressing-error-code-0x887a0006/"><u>Reversing Window's GPU Hang: Addressing Error Code 0X887A0006</u></a></li>
<li><a href="https://games-able.techidaily.com/secure-your-ultimate-marvel-gaming-experience-now/"><u>Secure Your Ultimate Marvel Gaming Experience Now!</u></a></li>
<li><a href="https://games-able.techidaily.com/shielding-your-digital-actions-from-watchful-eyes/"><u>Shielding Your Digital Actions From Watchful Eyes</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-samsung-galaxy-m34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/sony-playstation-handheld-demystified/"><u>Sony PlayStation Handheld Demystified</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-troubleshooting-correct-read-only-library-folder-issue/"><u>Steam Troubleshooting: Correct Read-Only Library Folder Issue</u></a></li>
<li><a href="https://games-able.techidaily.com/supreme-gamers-logitech-toolkit/"><u>Supreme Gamer's Logitech Toolkit</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-experts-pathway-to-purchasing-an-immaculate-4k-display-for-2024/"><u>The Expert's Pathway to Purchasing an Immaculate 4K Display for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/top-4-ios-emulation-apps-where-do-you-start/"><u>Top 4 iOS Emulation Apps: Where Do You Start?</u></a></li>
<li><a href="https://games-able.techidaily.com/top-notch-mouse-comforts-unveiled/"><u>Top-Notch Mouse Comforts Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/top-ranked-locales-gamers-trophies-turf/"><u>Top-Ranked Locales: Gamers' Trophies Turf</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-collection-of-nintendo-switch-cartridge-cases/"><u>Ultimate Collection of Nintendo Switch Cartridge Cases</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/ultimate-guide-convert-and-save-4k-videos-as-mp4-files-for-2024/"><u>Ultimate Guide Convert and Save 4K Videos as MP4 Files for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-discords-potential-mac-setup-guide/"><u>Unlocking Discord's Potential: Mac Setup Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-the-mystery-of-steams-bp-crashes/"><u>Unveiling the Mystery of Steam's BP Crashes</u></a></li>
<li><a href="https://games-able.techidaily.com/what-makes-a-great-steam-deck/"><u>What Makes a Great Steam Deck?</u></a></li>
<li><a href="https://games-able.techidaily.com/why-a-quick-reboot-can-save-your-gaming-experience/"><u>Why a Quick Reboot Can Save Your Gaming Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/xboxs-response-to-breaches-the-strike-mechanism/"><u>Xbox's Response to Breaches: The Strike Mechanism</u></a></li>
</ul></div>

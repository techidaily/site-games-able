---
title: Android Games on Linux Devices Explained
date: 2024-07-12T03:40:16.312Z
updated: 2024-07-13T03:40:16.312Z
tags:
  - games
categories:
  - games
description: This Article Describes Android Games on Linux Devices Explained
excerpt: This Article Describes Android Games on Linux Devices Explained
keywords: Android Gaming on Linux,Linux as a Platform for Android Games,Playing Android Games on Non-Windows OS,Cross-Platform Development,Mobile Gaming on Linux Devices with Android Apps,Expanding Android Game Reach to Linux Users,Accessibility of Android Games for Linux Enthusiasts
thumbnail: https://thmb.techidaily.com/38a10dded96ded9495ccb2173f240c20a69acb6b4b947c6dc175d30ce0f723b9.jpg
---

## Android Games on Linux Devices Explained

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
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-boost-your-snaps-to-new-heights-with-expert-snapchat-tips/"><u>[Updated] 2024 Approved  Boost Your Snaps to New Heights with Expert Snapchat Tips</u></a></li>
<li><a href="https://games-able.techidaily.com/optimizing-gaming-by-controlling-background-game-bar/"><u>Optimizing Gaming by Controlling Background Game Bar</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-universally-turn-off-controller-vibration-on-your-xbox-series-xs/"><u>How to Universally Turn Off Controller Vibration on Your Xbox Series X|S</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Tecno Spark Go (2024)? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/inquiring-about-the-value-proposition-for-ea-play/"><u>Inquiring About the Value Proposition for EA Play</u></a></li>
<li><a href="https://games-able.techidaily.com/from-pc-to-phone-in-a-flash-play-steam-games-with-link/"><u>From PC to Phone in a Flash: Play Steam Games with Link</u></a></li>
<li><a href="https://games-able.techidaily.com/learn-from-my-oled-faux-pas-smart-screen-selection/"><u>Learn From My OLED Faux Pas: Smart Screen Selection</u></a></li>
<li><a href="https://games-able.techidaily.com/optimize-xbox-s-x-with-best-blu-ray-practices/"><u>Optimize Xbox S X with Best Blu-Ray Practices</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-xiaomi-redmi-note-12-5g-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Xiaomi Redmi Note 12 5G Without PUK Codes</u></a></li>
<li><a href="https://games-able.techidaily.com/should-your-pc-make-an-instant-switch-to-rtx/"><u>Should Your PC Make an Instant Switch to RTX?</u></a></li>
<li><a href="https://games-able.techidaily.com/tech-showdown-finding-your-perfect-gaming-processor/"><u>Tech Showdown: Finding Your Perfect Gaming Processor?</u></a></li>
<li><a href="https://games-able.techidaily.com/superior-battery-solutions-the-premier-ps5-dualsense-controller-chargers/"><u>Superior Battery Solutions: The Premier PS5 DualSense Controller Chargers</u></a></li>
<li><a href="https://games-able.techidaily.com/no-data-only-fun-iphoneipads-top-15-offline-gaming-lists/"><u>No Data, Only Fun! IPhone/iPad's Top 15 Offline Gaming Lists</u></a></li>
<li><a href="https://games-able.techidaily.com/nvidia-driver-updates-unlock-your-computers-potential-immediately/"><u>Nvidia Driver Updates: Unlock Your Computer's Potential Immediately!</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-mending-or-swapping-faulty-nintendo-switches/"><u>Strategies for Mending or Swapping Faulty Nintendo Switches</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-unique-snap-configurations-in-win-os/"><u>Crafting Unique Snap Configurations in Win OS</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-vivo-x-fold-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-elevating-your-win11-capture-experience-with-top-tools/"><u>[New] 2024 Approved  Elevating Your Win11 Capture Experience with Top Tools</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-banned-from-omegle-in-2024-how-to-get-unbanned/"><u>New Banned From Omegle, In 2024 How to Get Unbanned?</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-advanced-features-of-amds-rx-7800xt-7700xt/"><u>Navigating the Advanced Features of AMD's RX 7800XT, 7700XT</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/create-engaging-whatsapp-videos-with-these-tools-for-2024/"><u>Create Engaging WhatsApp Videos with These Tools for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-simplified-installation-dive-into-ifunnys-meme-world/"><u>In 2024, Simplified Installation  Dive Into iFunny's Meme World</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-ps5-buying-process-wisely/"><u>Navigating the PS5 Buying Process Wisely</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-ps5s-sparkle-the-ultimate-guide/"><u>Mastering PS5's Sparkle: The Ultimate Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-data-to-drama-utilizing-google-trends-in-video-planning/"><u>[Updated] 2024 Approved  From Data to Drama  Utilizing Google Trends in Video Planning</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/walking-dead-top-picks-for-horror-gamers-for-2024/"><u>Walking Dead  Top Picks for Horror Gamers for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-adding-soundtracks-to-shareable-fb-moments-for-2024/"><u>[New] Adding Soundtracks to Shareable FB Moments for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/high-quality-titles-should-mts-be-compulsory/"><u>High-Quality Titles: Should MTs Be Compulsory?</u></a></li>
<li><a href="https://games-able.techidaily.com/java-game-highlights-our-favorites-unveiled/"><u>Java Game Highlights: Our Favorites Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-set-up-a-passcode-on-your-ps5/"><u>How to Set Up a Passcode on Your PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/expert-guide-resolving-display-driver-failed-errors-on-windows-11/"><u>Expert Guide: Resolving Display Driver Failed Errors on Windows 11</u></a></li>
<li><a href="https://games-able.techidaily.com/playstation-and-xbox-content-contenders/"><u>PlayStation and Xbox Content Contenders</u></a></li>
<li><a href="https://games-able.techidaily.com/stop-windows-interruptions-fixing-epic-games-launcher-crashes/"><u>Stop Windows Interruptions: Fixing Epic Games Launcher Crashes</u></a></li>
<li><a href="https://games-able.techidaily.com/maximize-opera-capabilities-unlocking-free-discord-time/"><u>Maximize Opera Capabilities - Unlocking Free Discord Time</u></a></li>
<li><a href="https://games-able.techidaily.com/next-gen-superior-hdi-display-mouse-lineup/"><u>Next-Gen, Superior HDI Display Mouse Lineup</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-best-practices-choosing-the-top-ios-video-downloaders-on-fb/"><u>[Updated] 2024 Approved  Best Practices  Choosing the Top iOS Video Downloaders on FB</u></a></li>
<li><a href="https://games-able.techidaily.com/retract-your-purchase-game-returns-on-series-xs-console/"><u>Retract Your Purchase: Game Returns on Series X/S Console</u></a></li>
<li><a href="https://games-able.techidaily.com/reverse-digital-gaming-purchases-on-console-xsx/"><u>Reverse Digital Gaming Purchases on Console XS/X</u></a></li>
<li><a href="https://games-able.techidaily.com/step-back-from-realms-step-forward-with-archives/"><u>Step Back From Realms, Step Forward with Archives</u></a></li>
<li><a href="https://win11.techidaily.com/make-windows-11-shine-a-holiday-system-guide/"><u>Make Windows 11 Shine: A Holiday System Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-gala-the-glory-of-game-guardianship/"><u>Gaming Gala: The Glory of Game Guardianship</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-vivo-y55s-5g-2023-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Vivo Y55s 5G (2023) to iPad | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/silent-sabotage-my-overclocked-nightmrange/"><u>Silent Sabotage: My Overclocked Nightmrange</u></a></li>
<li><a href="https://games-able.techidaily.com/high-end-graphics-on-a-minimalist-budget/"><u>High End Graphics on a Minimalist Budget</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-revenue-realization-strategies-for-successful-monetization-on-youtube-mobile/"><u>In 2024, Revenue Realization  Strategies for Successful Monetization on YouTube Mobile</u></a></li>
<li><a href="https://games-able.techidaily.com/minimizing-game-bars-operations-for-windows-11-privacy/"><u>Minimizing Game Bar's Operations for Windows 11 Privacy</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-navigating-the-needle-speed-of-videos-in-snapchat/"><u>[New] Navigating the Needle-Speed of Videos in Snapchat</u></a></li>
</ul></div>

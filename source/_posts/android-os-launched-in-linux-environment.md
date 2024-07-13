---
title: Android OS Launched in Linux Environment
date: 2024-07-12T04:29:07.105Z
updated: 2024-07-13T04:29:07.105Z
tags:
  - games
categories:
  - games
description: This Article Describes Android OS Launched in Linux Environment
excerpt: This Article Describes Android OS Launched in Linux Environment
keywords: Android OS,Linux Environment,Android Launch,Android Development,Linux-Based Android,Open Source Android,Embedded Systems with Android OS
thumbnail: https://thmb.techidaily.com/b89bc76dab2d2da8b94cbca20640b5005a7d287429d61f6d3112ce6c1768b0a9.jpg
---

## Android OS Launched in Linux Environment

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
<li><a href="https://games-able.techidaily.com/become-a-gaming-connoisseur-selecting-best-from-apples-selection/"><u>Become a Gaming Connoisseur: Selecting Best From Apple's Selection</u></a></li>
<li><a href="https://games-able.techidaily.com/beat-the-system-hush-your-xbox-series-xs-vibrations/"><u>Beat the System: Hush Your Xbox Series X's Vibrations</u></a></li>
<li><a href="https://games-able.techidaily.com/akkos-mod007b-board-the-ultimate-setup-for-gamers/"><u>Akko's MOD007B Board - The Ultimate Setup for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/becoming-the-master-storyteller-utilizing-chatgpt-for-text-based-adventures/"><u>Becoming the Master Storyteller: Utilizing ChatGPT for Text-Based Adventures</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-evaluation-of-viewing-seconds-in-a-20mb-videography/"><u>[New] In 2024, Evaluation of Viewing Seconds in a 20MB Videography</u></a></li>
<li><a href="https://games-able.techidaily.com/are-old-docks-suitable-for-nintendos-new-switch-oled/"><u>Are Old Docks Suitable for Nintendo's New Switch OLED?</u></a></li>
<li><a href="https://games-able.techidaily.com/advanced-techniques-for-managing-switch-gamer-profiles/"><u>Advanced Techniques for Managing Switch Gamer Profiles</u></a></li>
<li><a href="https://games-able.techidaily.com/benchmark-battle-asus-rog-ally-versus-steam-deck/"><u>Benchmark Battle: ASUS ROG Ally Versus Steam Deck</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/flip-the-narrative-ios-video-playback-upside-down-for-2024/"><u>Flip the Narrative  IOS Video Playback Upside-Down for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/atlasos-your-old-machines-future/"><u>AtlasOS: Your Old Machine's Future</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-5-gaming-monitors-for-playstation-and-xbox/"><u>The Ultimate 5 Gaming Monitors for PlayStation & Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/before-you-buy-think-these-6-things-through/"><u>Before You Buy, Think These 6 Things Through</u></a></li>
<li><a href="https://games-able.techidaily.com/best-online-shooters-a-comprehensive-list-of-browser-based-games/"><u>Best Online Shooters: A Comprehensive List of Browser-Based Games</u></a></li>
<li><a href="https://extra-resources.techidaily.com/balanced-flights-7-leading-gimbals-reviewed/"><u>Balanced Flights  7 Leading Gimbals Reviewed</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-revive-your-phone-top-tips-for-missing-iphone-x/"><u>[New] Revive Your Phone  Top Tips for Missing iPhone X</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-these-top-mistakes-for-perfect-screen-choice/"><u>Avoid These Top Mistakes for Perfect Screen Choice</u></a></li>
<li><a href="https://games-able.techidaily.com/asus-rog-allys-elite-dock-selection-2024-highlights/"><u>ASUS ROG Ally's Elite Dock Selection - 2024 Highlights</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-display-freeze-decoding-error-0x887a0006-on-windows/"><u>Avoiding Display Freeze - Decoding Error 0X887A0006 on Windows</u></a></li>
<li><a href="https://games-able.techidaily.com/best-competitors-to-geforce-rtx-4060-ti-graphics-card/"><u>Best Competitors to GeForce RTX 4060 Ti Graphics Card</u></a></li>
<li><a href="https://games-able.techidaily.com/adventures-at-hand-play-netflixs-exciting-gaming/"><u>Adventures at Hand – Play Netflix’s Exciting Gaming</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-you-cast-your-apple-iphone-12-pro-max-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>How Can You Cast Your Apple iPhone 12 Pro Max to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-from-long-to-short-a-beginners-guide-to-splitting-videos-in-windows-live-movie-maker/"><u>Updated 2024 Approved From Long to Short A Beginners Guide to Splitting Videos in Windows Live Movie Maker</u></a></li>
<li><a href="https://games-able.techidaily.com/best-practices-managing-gpu-thermal-output/"><u>Best Practices: Managing GPU Thermal Output</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-music-from-oppo-a38-by-fonelab-android-recover-music/"><u>How to retrieve erased music from Oppo A38</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/op-5-trimming-titles-tailored-to-your-youtube-needs/"><u>[New] Top 5 Trimming Titles Tailored to Your YouTube Needs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-google-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Google Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win11-tips.techidaily.com/preventing-leaks-auto-shutdown-at-low-activity-windows-11-style/"><u>Preventing Leaks: Auto-Shutdown at Low Activity, Windows 11 Style</u></a></li>
<li><a href="https://youtube-data.techidaily.com/o-make-a-cooking-video-in-steps-an-ultimate-guide/"><u>How to Make a Cooking Video in Steps - an Ultimate Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-tutorial-to-bypass-your-vivo-v29-pro-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Vivo V29 Pro Face Lock?</u></a></li>
<li><a href="https://games-able.techidaily.com/assessing-repair-vs-exchange-for-broken-nintendo-switches/"><u>Assessing Repair Vs. Exchange for Broken Nintendo Switches</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-educators-manual-for-integrating-video-in-classroom-instruction/"><u>2024 Approved  Educator's Manual for Integrating Video in Classroom Instruction</u></a></li>
<li><a href="https://animation-videos.techidaily.com/updated-in-depth-study-of-cartoon-painting-starts-from-learning-to-draw-it-for-2024/"><u>Updated In-Depth Study of Cartoon Painting Starts From Learning to Draw It for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/are-macs-the-future-of-pc-gaming/"><u>Are Macs the Future of PC Gaming?</u></a></li>
<li><a href="https://games-able.techidaily.com/androids-classic-pokemon-revival-guide/"><u>Android's Classic Pokémon Revival Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/how-to-import-photos-and-videos-in-windows-10-deepest-secret/"><u>How to Import Photos and Videos in Windows 10 (Deepest Secret)</u></a></li>
<li><a href="https://games-able.techidaily.com/best-buys-elite-selection-of-xbox-streaming-equipment/"><u>Best Buys: Elite Selection of Xbox Streaming Equipment</u></a></li>
<li><a href="https://games-able.techidaily.com/beat-the-boosted-game-pass-rate-strategies-to-save/"><u>Beat the Boosted Game Pass Rate: Strategies to Save!</u></a></li>
<li><a href="https://games-able.techidaily.com/aim-for-glory-the-ultimate-ranking-of-online-fps-browser-games/"><u>Aim for Glory: The Ultimate Ranking of Online FPS Browser Games</u></a></li>
<li><a href="https://games-able.techidaily.com/arcade-racings-legacy-do-wheels-outperform-touchpads-now/"><u>Arcade Racing's Legacy: Do Wheels Outperform Touchpads Now?</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-exploring-the-capabilities-of-logitechs-4k-pro-webcam/"><u>[New] 2024 Approved  Exploring the Capabilities of Logitech's 4K Pro Webcam</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-smilesketcher-easy-to-use-digital-comedy-tool/"><u>In 2024, SmileSketcher  Easy-to-Use Digital Comedy Tool</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-streamline-your-tweets-with-correct-videography-aspect-ratio/"><u>[Updated] In 2024, Streamline Your Tweets with Correct Videography (Aspect Ratio)</u></a></li>
<li><a href="https://games-able.techidaily.com/back-to-networked-bliss-fixing-your-windowed-mc-disconnects/"><u>Back to Networked Bliss: Fixing Your Windowed MC Disconnects</u></a></li>
<li><a href="https://games-able.techidaily.com/banish-device-lags-on-windows-fix-for-dxgierrordevicehunk/"><u>Banish Device Lags on Windows: Fix for DXGI_ERROR_DEVICE_HUNK</u></a></li>
<li><a href="https://games-able.techidaily.com/apples-silicon-powered-gaming-crossover-compatibility-unveiled/"><u>Apple's Silicon-Powered Gaming: CrossOver Compatibility Unveiled</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-xiaomi-redmi-note-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Xiaomi Redmi Note 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-achieving-asmr-bliss-selecting-the-right-mic/"><u>In 2024, Achieving ASMR Bliss  Selecting the Right Mic</u></a></li>
<li><a href="https://games-able.techidaily.com/androids-time-machine-playing-old-school-pokemon/"><u>Android's Time Machine: Playing Old-School Pokémon</u></a></li>
</ul></div>

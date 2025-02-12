---
title: "Boundaries Blurred: Windows and SteamOS Living Side By Side"
date: 2025-02-07T17:44:13.648Z
updated: 2025-02-11T17:51:54.023Z
tags:
  - games
categories:
  - games
description: "This Article Describes Boundaries Blurred: Windows and SteamOS Living Side By Side"
excerpt: "This Article Describes Boundaries Blurred: Windows and SteamOS Living Side By Side"
keywords: Windows & SteamOS Coexistence,Boundary-Blurring OSes,Gaming on Multiple Platforms,Windows/SteamOS Integration,Multiplatform Gaming Environment,Shared System Experience,SteamOS & Windows Compatibility
thumbnail: https://thmb.techidaily.com/d52ef143e5ac406fb5edcd5e28a24a2a1379f299efd751d4b382d0440e3e89ad.jpg
---

## Boundaries Blurred: Windows and SteamOS Living Side By Side

### Quick Links

* [What Is Dual Booting on Your Steam Deck?](#what-is-dual-booting-on-your-steam-deck)
* [How to Dual Boot Your Steam Deck](#how-to-dual-boot-your-steam-deck)
* [How to Set Up a Dual Boot Manager on Your Steam Deck](#how-to-set-up-a-dual-boot-manager-on-your-steam-deck)
* [Fixes for Dual Boot Issues on Your Steam Deck](#fixes-for-dual-boot-issues-on-your-steam-deck)

### Key Takeaways

* Steam Deck can dual boot with Windows, allowing users to have a familiar OS for productivity and access to Xbox Game Pass.
* Valve has not released an official dual boot wizard, so users currently have to choose the OS through the boot manager.
* Users can use a third-party dual boot manager to avoid constantly using button combinations to switch OSes.

 You don't have to sacrifice SteamOS to have Windows on your Steam Deck, since the Steam Deck is capable of dual booting either through the official method or a third-party dual boot manager. Here's what you need to know about dual-booting Windows and SteamOS on your Steam Deck.

## What Is Dual Booting on Your Steam Deck?

![Clover dual boot manager on Steam Deck near controllers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/clover-dual-boot-manager-on-steam-deck-near-controllers.JPG)

Jhet Borja / MakeUseOf

 Dual booting in its most basic definition is having two OSes on your device—in this case, your Steam Deck. You can also have more than two OSes on your Steam Deck, but you'd be multi-booting by then.

 While SteamOS is better for gaming, many people like to add Windows as another boot option for their Steam Deck. You can either dual boot it from the same SSD with each OS having its own partition or use an external source for Windows like an SD card.

 If you [install Windows on your Steam Deck](https://www.makeuseof.com/how-to-install-windows-on-steam-deck/), you'll have the advantage of having a familiar OS that can allow you to do real work with apps like Photoshop, Lightroom, Microsoft Office, and more.

 And since Xbox Game Pass isn't available on SteamOS yet, Windows is the best way to take your Game Pass subscription on the go.

![Steam Deck surrounded by peripherals](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/steam-deck-surrounded-by-peripherals.JPG)

Jhet Borja/MUO

 Valve states that the Steam Deck is perfectly capable of dual booting, so you'll have no problems having two or more OSes on your Steam Deck.

 However, Valve is yet to release the official dual boot wizard that's expected to ship with SteamOS 3.0 (according to the [Steam website](http://help.steampowered.com/en/faqs/view/6121-ECCD-D643-BAA8)), meaning you will have to choose your OS through the boot manager.

## How to Dual Boot Your Steam Deck

 The main and official way to dual boot your Steam Deck is by using the boot manager. It's quite easy, but having to do this every time you want to switch OSes can be frustrating over time.

 If you're here, it probably already means that you have two OSes on your Steam Deck. Now, here's how to switch between them...

![Volume down and power button to enter Steam Deck boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/volume-down-and-power-button-to-enter-steam-deck-boot-manager.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Jhet Borja/MUO

 With your Steam Deck shut off, hold down the volume down button and the power button until you hear a chime. When you hear the chime, let go of the power button but keep holding down the volume down button until the boot manager pops up.

 The boot manager lets you choose your boot options—in this case Windows and SteamOS on the same SSD in different partitions. If you use an SD card, you can select the SD card if it has Windows installed on it.

![SteamOS in boot manager again](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/steamos-in-boot-manager-again.jpg)

 If you hold down the power button after the chime, you will most likely end up shutting your Steam Deck down again, so make sure to let go after the chime.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y-k_3N-0OI?si=1J-aFBXLJl5b3x4h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Set Up a Dual Boot Manager on Your Steam Deck

 If you don't like seeing the boot manager every time you want to switch OSes, you can instead use a dual boot manager.

 A dual boot manager will make switching between OSes smoother as you don't need to hold down any button combinations and it will let you choose your OS on startup.

 In this guide, we'll be using Clover for Steam Deck by ryanrudolfoba on [GitHub](https://github.com/ryanrudolfoba/SteamDeck-Clover-dualboot?tab=readme-ov-file).

### Step 1: Getting Windows Ready for Clover Boot Manager

 Before you install Clover on Windows on your Steam Deck, you need to get it ready for a smoother experience.

 First, in Windows Search, search for **"Turn Windows features on or off**". Then, under the **Device Lockdown** folder, select the box that says **Unbranded Boot**. This will prevent Clover from displaying random boot brands.

![Selecting Unbranded Boot in Device Lockdown Windows Feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-unbranded-boot-in-device-lockdown-windows-feature.jpg)

 Next, you’ll have to run a few commands in Command Prompt. Search "CMD" in Windows Search and right-click to select **Run as administrator**.

![CMD commands for Clover on Steam Deck](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/cmd-commands-for-clover-on-steam-deck.jpg)

 In the Command Prompt, enter these commands one at a time:

* bcdedit.exe -set {globalsettings} bootuxdisabled on
* bcdedit.exe -set {bootmgr} noerrordisplay on

 In case those don't work, you can also add:

* bcdedit.exe -set {globalsettings} highestmode on

### Step 2: Setting up Clover on SteamOS on Your Steam Deck

 Now that Windows is ready, you’ll have to boot to SteamOS on your Steam Deck.

 Enter the boot manager by holding down the volume down button and the power button until you hear a chime. Let go of the power button, but keep holding the volume down button until the boot manager pops up.

![Volume down and power button to enter Steam Deck boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/volume-down-and-power-button-to-enter-steam-deck-boot-manager.JPG)

Jhet Borja/MUO

 Select SteamOS. Go to desktop mode by selecting Power after pressing the Steam button. Once you’re in desktop mode, make sure you have a sudo password set in SteamOS.

 Once your sudo password is set, search and open Konsole in the app launcher on the bottom left.

![First two Konsole commands for Clover Dual Boot Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/first-two-konsole-commands-for-clover-dual-boot-manager.jpg)

 By this point, we suggest having a browser open on your Steam Deck so that you can individually copy and paste these commands one by one on your Steam Deck.

1. cd ~/
2. git clone <https://github.com/ryanrudolfoba/SteamDeck-Clover-dualboot>
3. cd ~/SteamDeck-Clover-dualboot
4. chmod +x install-Clover.sh
5. ./install-Clover.sh

![Clover successfully installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/clover-successfully-installed.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After the last command, you’ll have to enter your sudo password to start installing Clover on your Steam Deck.

 You’ll also be greeted with the option to choose which OS you want it to default to—in my case, it’s SteamOS since I’ll be using that more often.

![Front facing Steam Deck wth Clover dual boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/front-facing-steam-deck-wth-clover-dual-boot.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Jhet Borja / MakeUseOf

 Once it’s installed, you can restart your Steam Deck to try it out. If it doesn’t look good to you, don’t worry, you can always add your own custom theme.

## Fixes for Dual Boot Issues on Your Steam Deck

 The Clover dual boot manager isn’t an official Steam dual boot wizard as Valve is still working on that. This means you might face a few issues. Here are a few fixes in case you run into these problems...

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. You Can’t Find SteamOS in the Boot Manager

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)

Jhet Borja/MUO

 SteamOS disappearing from the boot manager is a common occurrence, but don’t worry, it’s not actually gone from your Steam Deck. The boot manager just can’t find it.

 To find it, shut down your Steam Deck. This time, instead of holding the volume down button for the boot manager, hold the volume up button to open the BIOS instead.

![Boot from file Steam Deck BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/boot-from-file-steam-deck-bios.JPG)

 Once you’re in the BIOS, select **Boot from file > eps > efi > steamos > steamcl.efi**. This should boot you back into SteamOS.

![Selecting steamcl.efi in Steam Deck BIOS to boot into SteamOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steamcl-efi-in-steam-deck-bios-to-boot-into-steamos.JPG)

Jhet Borja/MakeUseOf

 To put SteamOS back on the boot manager, open up Konsole in desktop mode on your Steam Deck and enter this:

sudo efibootmgr -c -L "SteamOS" -l "\EFI\steamos\steamcl.efi" -d /dev/nvme0n1p1

![Konsole command to make SteamOS appear in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/konsole-command-to-make-steamos-appear-in-boot-manager.JPG)

 This should put it back on the boot manager so that you don’t have to boot from the file anymore.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Setting a Sudo Password

![Steam Deck user password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/steam-deck-user-password.jpg)

 To set your sudo password, open desktop mode and head to **Settings** in the app manager or on the task manager at the bottom of your screen.

 In settings, go to **Users** and enter a simple username and password. You now have a sudo account and you can access things that you couldn’t without one.

### 3\. Windows Keeps Taking Over the Bootloader

 If Windows takes over the bootloader and skips Clover, you should download the Clover dual boot manager for Windows on [the same GitHub page](https://github.com/ryanrudolfoba/SteamDeck-Clover-dualboot) you used for SteamOS.

![Download Clover ZIP on GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/download-clover-zip-on-github.jpg)

 Click on **<> Code** then **Download Zip**.

![Run CloverWindows.bat as administrator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/run-cloverwindows-bat-as-administrator.jpg)

 Extract the ZIP file into a folder and right-click **CloverWindows.bat** to **Run it as administrator**. It will tell you that Windows doesn’t recognize the app, just click **More Info > Run Anyway**.

![Windows protected your PC from CloverWindows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-protected-your-pc-from-cloverwindows.jpg)

 This will open up the Command Prompt. Once it’s done installing, just hit Enter.

![Properties on CloverTask in Task Scheduler Library](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/properties-on-clovertask-in-task-scheduler-library.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, you’ll have to open up Task Scheduler by searching it on Windows Search. In **Task Scheduler Library** search for **CloverTask**. Right-click on it and click **Properties**.

![Changed security options for CloverTask in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/changed-security-options-for-clovertask-in-task-scheduler.jpg)

 In the properties, head to the general tab and select **Run whether user is logged on or not** and check the two boxes below it (see image), then click **OK**.

![Run on CloverTask in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/run-on-clovertask-in-task-scheduler.jpg)

 Finally, right-click CloverTask once again and click **Run**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZeYbTVeaXg0?si=rwLL1DbBoX26BGjm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 4\. A SteamOS or Windows Update Broke Clover Dual Boot

 If an update on Windows or SteamOS broke Clover and the device says it can’t find any boot options, don’t panic, your Steam Deck is not bricked.

 Refer to the first fix above and boot SteamOS from its file. Open up the BIOS by holding volume up and the power button, letting go of the power button once you hear a chime.

![Boot from file Steam Deck BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/boot-from-file-steam-deck-bios.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’re in the BIOS, select **Boot from file > eps > efi > steamos > steamcl.efi**. This will open up SteamOS and fix Clover.

![Selecting steamcl.efi in Steam Deck BIOS to boot into SteamOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steamcl-efi-in-steam-deck-bios-to-boot-into-steamos.JPG)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Jhet Borja/MakeUseOf

 Those are some of the most common issues when dual booting your Steam Deck, but once you're past them, switching between SteamOS and Windows should now be as easy as restarting your Steam Deck and selecting your OS once Clover pops up.

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
<li><a href="https://fox-http.techidaily.com/new-mastering-camera-balance-gimbals-for-drones-explained/"><u>[New] Mastering Camera Balance Gimbals for Drones Explained</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722974274019-amd-rx-6700-xt-graphics-card-freshest-windows-compatible-drivers-ready/"><u>AMD RX 6700 XT Graphics Card: Freshest Windows-Compatible Drivers Ready</u></a></li>
<li><a href="https://games-able.techidaily.com/can-you-use-a-ps5-controller-on-a-ps4/"><u>Can You Use a PS5 Controller on a PS4?</u></a></li>
<li><a href="https://games-able.techidaily.com/chatgpt-scripting-mastery-for-gaming-worlds/"><u>ChatGPT Scripting Mastery for Gaming Worlds</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-ideal-iphone-location-tools-our-choice-of-top-5/"><u>Discover the Ideal iPhone Location Tools: Our Choice of Top 5</u></a></li>
<li><a href="https://games-able.techidaily.com/enhance-steam-deck-performance-installing-gaming-launchers/"><u>Enhance Steam Deck Performance: Installing Gaming Launchers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-se-2022-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone SE (2022)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-refurbished-apple-iphone-6s-everything-you-need-to-know-drfone-by-drfone-transfer-from-ios/"><u>In 2024, Refurbished Apple iPhone 6s Everything You Need to Know | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/innocn-39g1-r-your-budget-gaming-screen/"><u>InnoCN 39G1 R - Your Budget Gaming Screen</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/sipping-on-chatgpt-cocktail-quality-insight/"><u>Sipping on ChatGPT: Cocktail Quality Insight</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/unlocking-stills-from-videos-top-10-conversion-tools-for-2024/"><u>Unlocking Stills From Videos Top 10 Conversion Tools for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-the-power-of-beyerdynamics-mmx-200/"><u>Unlocking the Power of Beyerdynamic's MMX 200</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-xbox-titles-on-steam-using-glossi-magic/"><u>Unlocking Xbox Titles on Steam Using GlosSI Magic</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/why-paddle-controllers-enhance-my-gaming-experience-an-insider-look/"><u>Why Paddle Controllers Enhance My Gaming Experience - An Insider Look</u></a></li>
</ul></div>


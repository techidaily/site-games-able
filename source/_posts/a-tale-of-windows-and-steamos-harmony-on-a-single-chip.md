---
title: A Tale of Windows & SteamOS Harmony on a Single Chip
date: 2024-07-12T04:17:52.764Z
updated: 2024-07-13T04:17:52.764Z
tags:
  - games
categories:
  - games
description: This Article Describes A Tale of Windows & SteamOS Harmony on a Single Chip
excerpt: This Article Describes A Tale of Windows & SteamOS Harmony on a Single Chip
keywords: Windows-SteamOS Unity,Chip Integration Duo,Single-Chip OS Blend,WinOS & SteamOS Synergy,Dual Systems Harmony,UniPC Ecosystems,PC Fusion Platform
thumbnail: https://thmb.techidaily.com/8902585d66f327811523945d1407154d052552e159a549922c8c259267eab9e9.png
---

## A Tale of Windows & SteamOS Harmony on a Single Chip

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

Jhet Borja/MUO

 With your Steam Deck shut off, hold down the volume down button and the power button until you hear a chime. When you hear the chime, let go of the power button but keep holding down the volume down button until the boot manager pops up.

 The boot manager lets you choose your boot options—in this case Windows and SteamOS on the same SSD in different partitions. If you use an SD card, you can select the SD card if it has Windows installed on it.

![SteamOS in boot manager again](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/steamos-in-boot-manager-again.jpg)

 If you hold down the power button after the chime, you will most likely end up shutting your Steam Deck down again, so make sure to let go after the chime.

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

 After the last command, you’ll have to enter your sudo password to start installing Clover on your Steam Deck.

 You’ll also be greeted with the option to choose which OS you want it to default to—in my case, it’s SteamOS since I’ll be using that more often.

![Front facing Steam Deck wth Clover dual boot](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/front-facing-steam-deck-wth-clover-dual-boot.JPG)

Jhet Borja / MakeUseOf

 Once it’s installed, you can restart your Steam Deck to try it out. If it doesn’t look good to you, don’t worry, you can always add your own custom theme.

## Fixes for Dual Boot Issues on Your Steam Deck

 The Clover dual boot manager isn’t an official Steam dual boot wizard as Valve is still working on that. This means you might face a few issues. Here are a few fixes in case you run into these problems...

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

 Next, you’ll have to open up Task Scheduler by searching it on Windows Search. In **Task Scheduler Library** search for **CloverTask**. Right-click on it and click **Properties**.

![Changed security options for CloverTask in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/changed-security-options-for-clovertask-in-task-scheduler.jpg)

 In the properties, head to the general tab and select **Run whether user is logged on or not** and check the two boxes below it (see image), then click **OK**.

![Run on CloverTask in Task Scheduler](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/run-on-clovertask-in-task-scheduler.jpg)

 Finally, right-click CloverTask once again and click **Run**.

### 4\. A SteamOS or Windows Update Broke Clover Dual Boot

 If an update on Windows or SteamOS broke Clover and the device says it can’t find any boot options, don’t panic, your Steam Deck is not bricked.

 Refer to the first fix above and boot SteamOS from its file. Open up the BIOS by holding volume up and the power button, letting go of the power button once you hear a chime.

![Boot from file Steam Deck BIOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/boot-from-file-steam-deck-bios.JPG)

 Once you’re in the BIOS, select **Boot from file > eps > efi > steamos > steamcl.efi**. This will open up SteamOS and fix Clover.

![Selecting steamcl.efi in Steam Deck BIOS to boot into SteamOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steamcl-efi-in-steam-deck-bios-to-boot-into-steamos.JPG)

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
<li><a href="https://games-able.techidaily.com/unlocking-discords-potential-mac-setup-guide/"><u>Unlocking Discord's Potential: Mac Setup Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/motorola-edge-40-neo-won-t-play-mkv-movies-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Motorola Edge 40 Neo won’t play MKV movies</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/firefoxs-finest-leading-video-downloads-and-addons-for-facebook-for-2024/"><u>Firefox's Finest  Leading Video Downloads & Addons for Facebook for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-tweak-quick-twitter-video-preview/"><u>[Updated] 2024 Approved  Tweak Quick Twitter Video Preview</u></a></li>
<li><a href="https://games-able.techidaily.com/top-8-elements-for-choosing-an-effective-cpu-cooler/"><u>Top 8 Elements for Choosing an Effective CPU Cooler</u></a></li>
<li><a href="https://games-able.techidaily.com/join-forces-in-these-20-cross-system-gaming-adventures/"><u>Join Forces in These 20 Cross-System Gaming Adventures</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-connecting-twitter-videos-with-facebook-friends/"><u>[Updated] 2024 Approved  Connecting Twitter Videos with Facebook Friends</u></a></li>
<li><a href="https://games-able.techidaily.com/winning-the-race-addressing-low-fps-and-enhancing-valorant-performance/"><u>Winning the Race: Addressing Low FPS & Enhancing Valorant Performance</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-oppo-reno-11f-5g-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Oppo Reno 11F 5G Phone with Broken Screen</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-elevating-your-igtv-video-game-techniques-for-smartphones-and-dslrs/"><u>[Updated] Elevating Your IGTV Video Game  Techniques for Smartphones and DSLRs</u></a></li>
<li><a href="https://games-able.techidaily.com/examining-xbox-encasements/"><u>Examining Xbox Encasements</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-oneplus-open-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-reducing-sound-levels-gradually-with-easy-steps-in-lumafusion/"><u>[Updated] 2024 Approved  Reducing Sound Levels Gradually with Easy Steps in Lumafusion</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-top-fixes-to-resolve-issues-with-premiere-pro-slow-playback/"><u>Updated Top Fixes to Resolve Issues with Premiere Pro Slow Playback</u></a></li>
<li><a href="https://games-able.techidaily.com/hall-effect-keys-in-focus-review-of-modular-board-mod007b/"><u>Hall Effect Keys in Focus - Review of Modular Board MOD007B</u></a></li>
<li><a href="https://games-able.techidaily.com/joystick-journey-converting-console-commands-to-computer-controls-139-chars/"><u>Joystick Journey: Converting Console Commands to Computer Controls (139 Chars)</u></a></li>
<li><a href="https://games-able.techidaily.com/upgrading-games-from-directx-11-to-directx-12/"><u>Upgrading Games: From DirectX 11 to DirectX 12</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-big-time-savings-with-these-top-11-discounted-games-websites/"><u>Unlock Big-Time Savings with These Top 11 Discounted Games Websites</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-get-your-editing-mojo-back-with-this-final-cut-pro-overview/"><u>[New] Get Your Editing Mojo Back with This Final Cut Pro Overview</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-overcharges-with-smart-game-management/"><u>Avoid Overcharges with Smart Game Management</u></a></li>
<li><a href="https://games-able.techidaily.com/advanced-techniques-for-steam-shot-collection/"><u>Advanced Techniques for Steam Shot Collection</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-apps-and-online-tools-to-track-xiaomi-redmi-12-5g-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Xiaomi Redmi 12 5G Phone With/Without IMEI Number</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-halt-steam-initialization/"><u>How to Halt Steam Initialization</u></a></li>
<li><a href="https://games-able.techidaily.com/do-you-actually-need-a-mechanical-keyboard-for-gaming/"><u>Do You Actually Need a Mechanical Keyboard for Gaming?</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-windows-11s-hdr-capabilities/"><u>Mastering Windows 11'S HDR Capabilities</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-game-mice-qualities-essential-specifications-to-check/"><u>Top 5 Game Mice Qualities: Essential Specifications to Check</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-virtual-voyage-review-meta-quest-3/"><u>The Ultimate Virtual Voyage Review: Meta Quest 3</u></a></li>
<li><a href="https://games-able.techidaily.com/what-to-do-if-your-controller-wont-work-on-your-windows-pc/"><u>What to Do if Your Controller Won't Work on Your Windows PC</u></a></li>
<li><a href="https://games-able.techidaily.com/curating-my-collection-of-innovative-indie-games/"><u>Curating My Collection of Innovative Indie Games</u></a></li>
<li><a href="https://games-able.techidaily.com/bringing-pc-gaming-power-to-your-iphone-with-geforce-now/"><u>Bringing PC Gaming Power to Your iPhone with GeForce Now</u></a></li>
<li><a href="https://games-able.techidaily.com/what-makes-a-great-steam-deck/"><u>What Makes a Great Steam Deck?</u></a></li>
<li><a href="https://games-able.techidaily.com/the-significance-of-hrtf-in-valorant-sound-design/"><u>The Significance of HRTF in Valorant Sound Design</u></a></li>
<li><a href="https://games-able.techidaily.com/inside-the-world-of-professional-gaming-audio-tech/"><u>Inside the World of Professional Gaming Audio Tech</u></a></li>
<li><a href="https://games-able.techidaily.com/4-achievement-hunting-sites-to-improve-your-gamerscore/"><u>4 Achievement Hunting Sites to Improve Your Gamerscore</u></a></li>
<li><a href="https://games-able.techidaily.com/breaking-the-code-ps5s-internet-enigma/"><u>Breaking the Code: PS5's Internet Enigma</u></a></li>
<li><a href="https://games-able.techidaily.com/gameplay-exploration-older-titles-on-new-ps-console/"><u>Gameplay Exploration: Older Titles on New PS Console</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-intelligent-viewing-syncing-youtube-with-televisions/"><u>In 2024, Intelligent Viewing  Syncing YouTube with Televisions</u></a></li>
<li><a href="https://games-able.techidaily.com/beyond-screen-magic-unmasking-bogus-gameshows/"><u>Beyond Screen Magic: Unmasking Bogus Gameshows</u></a></li>
<li><a href="https://games-able.techidaily.com/custom-fan-curve-configuration-for-improved-graphics/"><u>Custom Fan Curve Configuration for Improved Graphics</u></a></li>
<li><a href="https://games-able.techidaily.com/emulating-legends-pokemon-games-resurgence/"><u>Emulating Legends: Pokémon Games' Resurgence</u></a></li>
<li><a href="https://games-able.techidaily.com/eliminating-low-memory-alerts-while-using-roblox-in-ios/"><u>Eliminating Low-Memory Alerts While Using Roblox in iOS</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-tips-for-resetting-ps5-gamepad/"><u>Essential Tips for Resetting PS5 Gamepad</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-brilliance-top-deals-on-cost-effective-mobo/"><u>Budget Brilliance: Top Deals on Cost-Effective Mobo</u></a></li>
<li><a href="https://games-able.techidaily.com/winning-strategies-for-pokemon-games-on-iphoneipad-gaming/"><u>Winning Strategies for Pokémon Games on iPhone/iPad Gaming</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/insta-snap-authenticity-guide-unveiling-selfies-truths/"><u>Insta Snap Authenticity Guide  Unveiling Selfies' Truths</u></a></li>
</ul></div>

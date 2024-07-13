---
title: "A New Chapter for Deck: Unleashing Power in Two Operating Systems"
date: 2024-07-12T04:20:41.221Z
updated: 2024-07-13T04:20:41.221Z
tags:
  - games
categories:
  - games
description: "This Article Describes A New Chapter for Deck: Unleashing Power in Two Operating Systems"
excerpt: "This Article Describes A New Chapter for Deck: Unleashing Power in Two Operating Systems"
keywords: Deck Power OS,Multi-OS Capability,System Enhancement,Power Boost Upgrade,OS Integration Ease,Software Expansion,Operating Systems Unleashed
thumbnail: https://thmb.techidaily.com/bfce4d332deea76d243f8439048cdd48e83f3f7bffbf49e41ff2d8a5b05d2343.jpg
---

## A New Chapter for Deck: Unleashing Power in Two Operating Systems

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
<li><a href="https://youtube-help.techidaily.com/in-2024-toddler-tycoon-turned-teen-titan-the-income-of-a-kid-star/"><u>In 2024, Toddler Tycoon Turned Teen Titan  The Income of a Kid Star</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-the-ultimate-roundup-post-vlc-media-players-for-2024/"><u>[Updated] The Ultimate Roundup  Post-VLC Media Players for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-the-past-play-retro-games-on-steam-deck-via-emudeck/"><u>Unlocking the Past: Play Retro Games on Steam Deck via EmuDeck</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-flv-editor-for-windows-11108187-easily-edit-flv-videos-on-pc/"><u>New 2024 Approved FLV Editor for Windows 11/10/8.1/8/7 Easily Edit FLV Videos on PC</u></a></li>
<li><a href="https://games-able.techidaily.com/top-9-gaming-hubs-champions-collectives/"><u>Top 9 Gaming Hubs: Champions' Collectives</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-a-comprehensive-manual-for-desktop-made-tiktok-hits/"><u>[New] A Comprehensive Manual for Desktop-Made TikTok Hits</u></a></li>
<li><a href="https://games-able.techidaily.com/all-inclusive-guide-to-choosing-top-1440p-monitors-without-breaking-the-bank/"><u>All-Inclusive Guide to Choosing Top 1440P Monitors Without Breaking the Bank</u></a></li>
<li><a href="https://games-able.techidaily.com/choosing-between-ps5-and-xbox-xs-game-systems/"><u>Choosing Between PS5 & Xbox XS Game Systems</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Apple iPhone 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/sprinkle-some-glitter-on-your-photos-ios-and-androids-prime-10-apps/"><u>Sprinkle Some Glitter on Your Photos  IOS & Android's Prime 10 Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/the-dirt-free-diary-weekly-console-care-routines/"><u>The Dirt-Free Diary: Weekly Console Care Routines</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-oneplus-ace-3-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track OnePlus Ace 3 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-realme-12plus-5g-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Realme 12+ 5G Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-top-10-websites-to-download-anime-subtitles-for-free-for-2024/"><u>New Top 10 Websites to Download Anime Subtitles for Free for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-the-ultimate-guide-for-streamlining-iphone-video-content/"><u>In 2024, The Ultimate Guide for Streamlining iPhone Video Content</u></a></li>
<li><a href="https://games-able.techidaily.com/zenith-of-leisure-experience-indolent-gameplay/"><u>Zenith of Leisure: Experience Indolent Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171155782-gamers-delight-large-scale-arcade-framing/"><u>Gamer's Delight - Large-Scale Arcade Framing</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-iphone-6s-plus-with-a-mask-on-drfone-by-drfone-ios/"><u>How to Unlock iPhone 6s Plus with a Mask On | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cultivating-connection-not-compulsion-in-subscriptions/"><u>Cultivating Connection, Not Compulsion in Subscriptions</u></a></li>
<li><a href="https://games-able.techidaily.com/what-is-the-new-nvidia-app-how-it-can-improve-your-gaming-experience/"><u>What Is the New Nvidia App? How It Can Improve Your Gaming Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173630427-invest-in-impact-choose-thick-broad-cabinet-frames/"><u>Invest in Impact: Choose Thick, Broad Cabinet Frames</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-ultimate-list-watching-nba-in-real-time-for-2024/"><u>The Ultimate List  Watching NBA in Real-Time for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-achieve-seamless-transitions-premiere-videos-on-youtube/"><u>[New] In 2024, Achieve Seamless Transitions  Premiere Videos on YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-cutting-edge-templates-for-memetic-art-for-2024/"><u>[New] Cutting-Edge Templates for Memetic Art for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/why-linkedin-games-may-be-more-harmful-than-helpful/"><u>Why LinkedIn Games May Be More Harmful Than Helpful</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-workspace-with-the-top-asus-rog-ally-laptop-docks-24/"><u>Transform Your Workspace with the Top ASUS ROG Ally Laptop Docks, '24</u></a></li>
<li><a href="https://games-able.techidaily.com/transforming-one-device-the-steam-decks-dual-boot-adventure/"><u>Transforming One Device: The Steam Deck's Dual-Boot Adventure</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-motorola-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Motorola Phone Hassle-Free</u></a></li>
<li><a href="https://games-able.techidaily.com/the-comprehensible-guide-to-game-stability-solve-your-10-main-issues/"><u>The Comprehensible Guide to Game Stability: Solve Your 10 Main Issues</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-leaders-engineering-digital-marvel-realms/"><u>[New] Leaders Engineering Digital Marvel Realms</u></a></li>
<li><a href="https://games-able.techidaily.com/the-role-of-strikes-in-upholdeating-xbox-fairness/"><u>The Role of Strikes in Upholdeating Xbox Fairness</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-the-finest-ea-play-games-for-sony-console/"><u>Unveiling the Finest EA Play Games for Sony Console</u></a></li>
<li><a href="https://games-able.techidaily.com/trouble-with-xbox-and-pc-reconnection-tips-inside/"><u>Trouble With Xbox & PC: Reconnection Tips Inside</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/simple-tricks-make-3d-gif-production-of-inspiration-pop-up/"><u>Simple Tricks Make 3D GIF Production of Inspiration Pop Up</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-performance-in-shooter-games-through-sensitivity-tweaks/"><u>Boosting Performance in Shooter Games Through Sensitivity Tweaks</u></a></li>
<li><a href="https://games-able.techidaily.com/6-innovative-techniques-to-enjoy-ps5-games/"><u>6 Innovative Techniques to Enjoy PS5 Games</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-safari-screens-freeze-heres-how-to-fix-black-screen-on-fb/"><u>[New] Safari Screens Freeze? Here's How to Fix Black Screen on FB</u></a></li>
<li><a href="https://games-able.techidaily.com/the-value-proposition-of-early-game-access/"><u>The Value Proposition of Early Game Access</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-vision-boosting-screen-protectors/"><u>Ultimate Vision-Boosting Screen Protectors</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-trailblazing-8-content-hubs-expanding-fastest/"><u>In 2024, Trailblazing 8 Content Hubs Expanding Fastest</u></a></li>
<li><a href="https://games-able.techidaily.com/unlock-potential-a-compreenas-five-tips-for-customizing-your-xbox-game-bar-experience/"><u>Unlock Potential: A Compreenas Five Tips for Customizing Your Xbox Game Bar Experience</u></a></li>
</ul></div>

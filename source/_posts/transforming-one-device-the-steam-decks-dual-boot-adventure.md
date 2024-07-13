---
title: "Transforming One Device: The Steam Deck's Dual-Boot Adventure"
date: 2024-07-12T04:02:37.269Z
updated: 2024-07-13T04:02:37.269Z
tags:
  - games
categories:
  - games
description: "This Article Describes Transforming One Device: The Steam Deck's Dual-Boot Adventure"
excerpt: "This Article Describes Transforming One Device: The Steam Deck's Dual-Boot Adventure"
keywords: Dual-Boot Steam Deck,Dual OS Steam Deck,Steam Console Gaming,Steam PC Conversion,Handheld MultiOS Device,Portable Steam Gameplay,Steam Deck Multitasking
thumbnail: https://thmb.techidaily.com/15f46f7d0d38e67cb89897b04873987b9a53cd33648d01ffc32ac08c2f0a2eb4.jpg
---

## Transforming One Device: The Steam Deck's Dual-Boot Adventure

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
5. ./install-Clover.sh ![Clover successfully installed](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/clover-successfully-installed.jpg)

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

sudo efibootmgr -c -L "SteamOS" -l "\EFI\steamos\steamcl.efi" -d /dev/nvme0n1p1 ![Konsole command to make SteamOS appear in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/konsole-command-to-make-steamos-appear-in-boot-manager.JPG)

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
<li><a href="https://some-guidance.techidaily.com/ultimate-guide-to-top-8-gold-text-in-3d-realms-for-2024/"><u>Ultimate Guide to Top 8 Gold Text in 3D Realms for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/game-pass-the-next-chapter-for-xbox-live-gold-users/"><u>Game Pass: The Next Chapter for Xbox Live Gold Users</u></a></li>
<li><a href="https://facebook.techidaily.com/the-ultimate-guide-to-enhancing-your-online-impression/"><u>The Ultimate Guide to Enhancing Your Online Impression</u></a></li>
<li><a href="https://games-able.techidaily.com/guarantee-secure-xbox-series-x-linking/"><u>Guarantee Secure Xbox Series X Linking</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-oppo-find-n3-flip-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Oppo Find N3 Flip? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/easy-steps-to-enjoy-games-anywhere-anytime/"><u>Easy Steps to Enjoy Games Anywhere, Anytime</u></a></li>
<li><a href="https://games-able.techidaily.com/evaluating-performance-nvidias-founder-vs-asus-branded-vega/"><u>Evaluating Performance: Nvidia's Founder VS Asus-Branded Vega</u></a></li>
<li><a href="https://games-able.techidaily.com/optimize-your-gaming-session-a-2-step-guide-to-detecting-android-fps/"><u>Optimize Your Gaming Session: A 2-Step Guide to Detecting Android FPS</u></a></li>
<li><a href="https://games-able.techidaily.com/mobile-operating-system-migration-tips-for-linux/"><u>Mobile Operating System Migration Tips for Linux</u></a></li>
<li><a href="https://games-able.techidaily.com/individualized-fan-settings-optimize-gpu-temperature-and-power/"><u>Individualized Fan Settings Optimize GPU Temperature & Power</u></a></li>
<li><a href="https://games-able.techidaily.com/galaxy-forger-unveiling-top-gaming-pcs/"><u>Galaxy Forger: Unveiling Top Gaming PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/keep-gaming-secure-dont-use-ps5-microphone/"><u>Keep Gaming Secure: Don't Use PS5 Microphone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-make-your-whatsapp-status-stand-out-with-these-essential-apps/"><u>In 2024, Make Your WhatsApp Status Stand Out with These Essential Apps</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-what-you-want-to-know-about-two-factor-authentication-for-icloud-on-your-iphone-11-pro-by-drfone-ios/"><u>In 2024, What You Want To Know About Two-Factor Authentication for iCloud On your iPhone 11 Pro</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-xbox-ones-drift-repair-techniques/"><u>Mastering Xbox One's Drift Repair Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/transforming-titles-best-ai-powered-podcast-name-makers-for-2024/"><u>Transforming Titles  Best AI-Powered Podcast Name Makers for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-terrain-of-xbox-sxs-high-res-mode/"><u>Navigating the Terrain of Xbox SX's High Res Mode</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-how-to-guide-on-bypassing-iphone-15-pro-max-icloud-activation-lock-by-drfone-ios/"><u>A How-To Guide on Bypassing iPhone 15 Pro Max iCloud Activation Lock</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-nightly-narratives-video-guide-and-critiques/"><u>[New] Nightly Narratives  Video Guide & Critiques</u></a></li>
<li><a href="https://games-able.techidaily.com/overcoming-bluetooth-disconnects-on-xbox-s/"><u>Overcoming Bluetooth Disconnects on Xbox S</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-how-to-survive-and-thrive-on-the-streak-frontier/"><u>In 2024, How to Survive and Thrive on the Streak Frontier</u></a></li>
<li><a href="https://games-able.techidaily.com/game-development-winner-directx-11-or-12/"><u>Game Development Winner: DirectX 11 or 12?</u></a></li>
<li><a href="https://network-issues.techidaily.com/bridging-the-gap-in-graphics-support-on-underpowered-pcs/"><u>Bridging the Gap in Graphics Support on Underpowered PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/office-environmentals-vs-playstation-specifications/"><u>Office Environmentals Vs. PlayStation Specifications</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unlocking-the-power-of-pages-top-10-social-media-optimization-tactics-for-2024/"><u>[New] Unlocking the Power of Pages  Top 10 Social Media Optimization Tactics for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-change-steams-default-language/"><u>How to Change Steam’s Default Language</u></a></li>
<li><a href="https://games-able.techidaily.com/minecraft-network-disconnect-on-windows-quick-tips/"><u>Minecraft Network Disconnect on Windows: Quick Tips</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-a-critical-look-at-irecorders-screenshot-tech/"><u>[New] In 2024, A Critical Look at iRecorder's Screenshot Tech</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-top-22-free-video-editing-software/"><u>Updated In 2024, Top 22 Free Video Editing Software</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-reigns-supreme-msi-raider-ge78-hx-reviewed/"><u>Gaming Reigns Supreme: MSI Raider GE78 HX Reviewed</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/unleash-your-creative-potential-with-these-top-apps/"><u>Unleash Your Creative Potential with These Top Apps</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-morph-your-face-the-best-face-swap-apps-for-mobile-phones/"><u>Updated Morph Your Face The Best Face Swap Apps for Mobile Phones</u></a></li>
<li><a href="https://games-able.techidaily.com/integration-tutorial-controller-phone-combo/"><u>Integration Tutorial: Controller, Phone Combo</u></a></li>
<li><a href="https://games-able.techidaily.com/lenovos-latest-tablet-a-deep-dive-into-the-legion-go/"><u>Lenovo's Latest Tablet: A Deep Dive Into the Legion Go</u></a></li>
</ul></div>

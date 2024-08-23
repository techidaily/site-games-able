---
title: "ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
date: 2024-08-22T22:13:02.452Z
updated: 2024-08-23T22:13:02.452Z
tags:
  - games
categories:
  - games
description: "This Article Describes ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
excerpt: "This Article Describes ACHDMAN Strategies: Preserving and Accessing Your Vintage Games"
keywords: Vintage Game Conservation,Classic Gaming Restoration,Heritage Video Game Storage,Retro Games Maintenance,Preserving Old Video Games,Accessing Antique Games,Saving Vintage Gaming Collections
thumbnail: https://thmb.techidaily.com/91b7cfb4d96e2456602f29985eb790b38dbd8c0fc22d4f4a877755c3058adea9.jpg
---

## ACHDMAN Strategies: Preserving and Accessing Your Vintage Games

 If you're collecting ROMs like Pokémon, you surely have noticed that the ones for newer platforms take up a significant chunk of your storage. A single game might require multiple gigabytes of storage. Keep over a dozen, and your ROM collection can quickly expand to many Terabytes. That's where the MAME project's CHDMAN tool can help.

 Does your ROM collection contain arcade games or titles for consoles with optical media, like Sony's PlayStation? CHDMAN can compress them to CHD files that take up a fraction of a ROM's original size.

 What's best is that many emulators support the CHD format. So, you can keep playing your ROMs without extracting or decompressing them. Let's see how.

## What Is CHDMAN?

 MAME's Compressed Hunks of Data (CHD) manager, or "CHDMAN" for short, allows you to store the files of a ROM in a single compressed archive. Apart from saving space, this can also simplify the management of multi-file ROMs, like optical media backups consisting of a game's data track and many more audio tracks for its music.

 A key difference compared to typical archives produced by tools like 7-Zip and WinRAR is that CHDMAN's CHD files can be used without requiring decompression.

 The two cons of the CHD format are that CHDMAN is a command line tool that you'll have to use by typing commands in the terminal and that not all emulators support the resulting CHD format. CHDMAN can only compress files with the following extensions:

* CUE & BIN.
* GDI.
* ISO.
* TOC.
* NRG.
* CDR.
* IMG.

## How to Compress Your ISOs With CHDMAN

 CHDMAN is distributed with the MAME emulator. If you already use that, you'll find CHDMAN's executable in MAME's installation directory. If not, download [the latest version of MAME from its official site](https://www.mamedev.org/) and install it on your PC to also get CHDMAN.

 To avoid typing the full path to CHDMAN every time you want to compress a ROM, add MAME's folder to your System Path variable. You can do this by [using environment variables in Windows 10](https://www.makeuseof.com/how-to-use-environment-variables-in-windows-10/) .

 Open a**File Explorer** window (**Windows Key + E**) and, to keep things tidy, create a folder anywhere you wish, within which you'll do all CHDMAN-related file juggling.

 Move the files of the ROM you want to compress to that folder. For this article, we'll use an original PlayStation backup stored in a CUE & BIN file combination.

![A screenshot of a BIN and CUE ROM image from the File Explorer in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/bin-and-cue-in-windows-file-explorer.jpg)

 Run Windows CMD or PowerShell. Then, move to the folder with your game's files with the Change Directory (CD) command:

`cd PATH_TO_FOLDER`

Our command was:

`cd "H:\Emulation\ROMs\PS1\Compress-to-CHD"`

![A screenshot of the Change Directory command in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/cd-command-in-cmd.jpg)

To compress your game with CHDMAN to CHD format, use the following:

`chdman.exe createcd -i "ROM_YOU_WANT_TO_COMPRESS.CUE" -o "FILENAME_OF_COMPRESSED.CHD"`

Our command was:

`chdman createcd -i "MUO_PSX.cue" -o "MUO_PSX.chd"  
`

![A screenshot of the command to compress a ROM into CHD format using CHDMAN](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/chdman-createcd-command-in-cmd.jpg)

 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

![DuckStation File Selector set to MAME CHD images](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/duckstation-chd-file-selection-1.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you're looking for a CHD-compatible emulator then, luckily some of the most popular emulators support them. Here are a few examples of emulators that allow you to play CHDs:

* MAME.
* DuckStation.
* Beetle PSX.
* PCSX.
* PCSX2.

* DEmul.
* lr-opera.
* Reicast.
* Flycast.
* Redream.
* Genesis Plus GX.
* PicoDrive.

 Because of [how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like [using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
## More Storage, More Gaming

 Compressing your emulators' ROMs with CHDMAN will give you back a significant amount of storage space. But there's also a major con.

 Freeing up storage space means you can expand your ROM collection further. And that, in turn, translates to even more games in your backlog. With so many games a click away, having a CHDMAN equivalent that could compress and multiply our free time would be great.


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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-fastest-8-tech-to-grab-screen-frames/"><u>[New] 2024 Approved  Fastest 8 Tech to Grab Screen Frames</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-infographics-boosting-buzz-through-social-videos/"><u>[New] 2024 Approved  Infographics  Boosting Buzz Through Social Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-step-by-step-record-your-powerpoint-presentation/"><u>[New] 2024 Approved  Step-by-Step  Record Your PowerPoint Presentation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-spectacular-8-ultimate-vr-play-tools-for-2024/"><u>[New] Spectacular 8 Ultimate VR Play Tools for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-art-of-movement-enhancing-your-photos-with-illustrators-motion-blur/"><u>[New] The Art of Movement  Enhancing Your Photos with Illustrator's Motion Blur</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-find-your-digital-companion-the-top-6-youtube-personality-puzzles/"><u>[Updated] 2024 Approved  Find Your Digital Companion  The Top 6 YouTube Personality Puzzles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-definitive-guide-to-audio-transitions/"><u>[Updated] The Definitive Guide to Audio Transitions</u></a></li>
<li><a href="https://screen-recording.techidaily.com/browsing-made-memorable-the-leading-screen-recorder-software-for-2024/"><u>Browsing Made Memorable  The Leading Screen Recorder Software for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/cutting-through-red-tape-on-digital-console-returns/"><u>Cutting Through Red Tape on Digital Console Returns</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-asus-vs-tuf-vs-proart-vs-prime-gear/"><u>Decoding Asus Vs. Tuf Vs. ProArt Vs. Prime Gear</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-mobile-gaming-what-to-look-out-for/"><u>Decoding Mobile Gaming: What to Look Out For</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-edges-pro-gaming-features/"><u>Discovering Edge's Pro-Gaming Features</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-mac-friendly-switch-titles/"><u>Discovering Mac-Friendly Switch Titles</u></a></li>
<li><a href="https://driver-download.techidaily.com/effortless-zebra-gkgk420dhttpssupportzebracomproductsbarcode-printerssoftware-drivers-driver-downloads-for-immediate-use/"><u>Effortless Zebra GK^[GK420d](https://support.zebra.com/products/barcode-printers/software-drivers) Driver Downloads for Immediate Use</u></a></li>
<li><a href="https://games-able.techidaily.com/embrace-vintage-psp-games-via-iphone/"><u>Embrace Vintage PSP Games via iPhone</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-graphics-performance-in-windows-gaming/"><u>Enhancing Graphics Performance in Windows Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/explore-creative-linux-terminals-7-game-ideas/"><u>Explore Creative Linux Terminals: 7 Game Ideas</u></a></li>
<li><a href="https://games-able.techidaily.com/explore-the-best-11-costless-word-games-on-phones/"><u>Explore the Best 11 Costless Word Games on Phones</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-honor-90-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-anywhere-phone-or-tablet-which/"><u>Game On Anywhere? Phone or Tablet, Which?</u></a></li>
<li><a href="https://games-able.techidaily.com/gamers-guide-to-switching-faultlessness/"><u>Gamer's Guide to Switching Faultlessness</u></a></li>
<li><a href="https://games-able.techidaily.com/gift-wrapped-adventures-presenting-games-through-steam/"><u>Gift-Wrapped Adventures: Presenting Games Through Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/high-pace-165hz-game-screens/"><u>High-Pace 165Hz Game Screens</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-control-gaming-interface-elements-in-discord/"><u>How to Control Gaming Interface Elements in Discord</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-tecno-camon-20-premier-5g-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Tecno Camon 20 Premier 5G Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-a-oneplus-nord-ce-3-lite-5g-easily-by-drfone-android/"><u>How To Unlock a OnePlus Nord CE 3 Lite 5G Easily?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-detect-and-stop-mspy-from-spying-on-your-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Stop mSpy from Spying on Your Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-optimizing-video-saving-a-guide-to-pc-mac-and-mobile-devices/"><u>In 2024, Optimizing Video Saving  A Guide to PC, Mac & Mobile Devices</u></a></li>
<li><a href="https://buynow-info.techidaily.com/inside-the-rugged-trails-expert-analysis-of-a-top-race-rc-rock-crawler/"><u>Inside the Rugged Trails: Expert Analysis of a Top Race RC Rock Crawler</u></a></li>
<li><a href="https://games-able.techidaily.com/inside-the-world-of-palworld/"><u>Inside the World of PalWorld</u></a></li>
<li><a href="https://games-able.techidaily.com/is-pursuing-higher-steam-rank-beneficial-in-the-long-run/"><u>Is Pursuing Higher Steam Rank Beneficial in the Long Run?</u></a></li>
<li><a href="https://games-able.techidaily.com/makeuseof-spotlight-mwcs-top-products/"><u>MakeUseOf Spotlight: MWC's Top Products</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-the-art-of-claiming-a-game-refund-on-steam/"><u>Mastering the Art of Claiming a Game Refund on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-xbox-s-x-controllers-bluetooth-linkage/"><u>Mastering Xbox S X Controller's Bluetooth Linkage</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-terrain-of-steam-playtime-tracking-and-awards/"><u>Navigating the Terrain of Steam Playtime Tracking and Awards</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-world-of-steam-points/"><u>Navigating the World of Steam Points</u></a></li>
<li><a href="https://games-able.techidaily.com/organizing-and-storing-your-steam-screens/"><u>Organizing and Storing Your Steam Screens</u></a></li>
<li><a href="https://games-able.techidaily.com/pro-gamers-guide-to-xbox-s-controller-dismantling/"><u>Pro Gamers' Guide to Xbox S Controller Dismantling</u></a></li>
<li><a href="https://games-able.techidaily.com/reaching-peak-performance-in-windows-gaming/"><u>Reaching Peak Performance in Windows Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/say-goodbye-to-unhappy-moments-resolving-the-top-10-reasons-games-freeze/"><u>Say Goodbye to Unhappy Moments: Resolving the Top 10 Reasons Games Freeze</u></a></li>
<li><a href="https://games-able.techidaily.com/secure-settings-the-guide-to-enabling-password-on-your-nintendo-switch/"><u>Secure Settings: The Guide to Enabling Password on Your Nintendo Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/sitting-smart-for-virtual-battles/"><u>Sitting Smart for Virtual Battles</u></a></li>
<li><a href="https://games-able.techidaily.com/steps-to-secure-a-fortnite-purchase-reimbursement/"><u>Steps to Secure a Fortnite Purchase Reimbursement</u></a></li>
<li><a href="https://games-able.techidaily.com/streamlining-your-steam-deck-typing-efficiency/"><u>Streamlining Your Steam Deck Typing Efficiency</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-led-strip-lights-of-2024/"><u>The Best LED Strip Lights of 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-to-switch-multi-streamers/"><u>The Ultimate Guide to Switch Multi-Streamers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-s17-pro-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo S17 Pro Phone Pattern Lock</u></a></li>
<li><a href="https://games-able.techidaily.com/transition-steam-interface-into-another-language/"><u>Transition Steam Interface Into Another Language</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-price-history-gaming-costs-on-steam/"><u>Unlocking Price History: Gaming Costs on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/when-to-reinitialize-your-playstation-5-controller/"><u>When to Reinitialize Your PlayStation 5 Controller</u></a></li>
</ul></div>

---
title: "ChDMan Technique: Optimizing Old Game ISOs Size & Performance"
date: 2024-07-29T05:58:57.272Z
updated: 2024-07-30T05:58:57.272Z
tags:
  - games
categories:
  - games
description: "This Article Describes ChDMan Technique: Optimizing Old Game ISOs Size & Performance"
excerpt: "This Article Describes ChDMan Technique: Optimizing Old Game ISOs Size & Performance"
keywords: ChDMan Tweak,GameISO Reduce,ISO Speedup,Performance Enhance,Low-Size Gaming,Optimized Games,Efficient ISOs
thumbnail: https://thmb.techidaily.com/9687aa834ae00807e9d2f77ee77a3ac9fdfd8db29a944a670186797d57bfaab8.jpg
---

## ChDMan Technique: Optimizing Old Game ISOs Size & Performance

 If you're collecting ROMs like Pokémon, you surely have noticed that the ones for newer platforms take up a significant chunk of your storage. A single game might require multiple gigabytes of storage. Keep over a dozen, and your ROM collection can quickly expand to many Terabytes. That's where the MAME project's CHDMAN tool can help.

 Does your ROM collection contain arcade games or titles for consoles with optical media, like Sony's PlayStation? CHDMAN can compress them to CHD files that take up a fraction of a ROM's original size.

 What's best is that many emulators support the CHD format. So, you can keep playing your ROMs without extracting or decompressing them. Let's see how.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
## How to Compress Your ISOs With CHDMAN

 CHDMAN is distributed with the MAME emulator. If you already use that, you'll find CHDMAN's executable in MAME's installation directory. If not, download[the latest version of MAME from its official site](https://www.mamedev.org/) and install it on your PC to also get CHDMAN.

 To avoid typing the full path to CHDMAN every time you want to compress a ROM, add MAME's folder to your System Path variable. You can do this by[using environment variables in Windows 10](https://www.makeuseof.com/how-to-use-environment-variables-in-windows-10/) .

 Open a**File Explorer** window (**Windows Key + E**) and, to keep things tidy, create a folder anywhere you wish, within which you'll do all CHDMAN-related file juggling.

 Move the files of the ROM you want to compress to that folder. For this article, we'll use an original PlayStation backup stored in a CUE & BIN file combination.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BPDF%2BUnlocker"><img src="https://www.systoolsgroup.com/box/pdf-unlocker.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A screenshot of the command to compress a ROM into CHD format using CHDMAN](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/chdman-createcd-command-in-cmd.jpg)

 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![DuckStation File Selector set to MAME CHD images](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/duckstation-chd-file-selection-1.jpg)

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

 Because of[how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like[using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-maintaining-meetings-in-google-recorder/"><u>[New] In 2024, Maintaining Meetings in Google Recorder</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-turbocharge-your-youtube-videos-swift-render-and-transfer-strategies/"><u>[New] In 2024, Turbocharge Your YouTube Videos  Swift Render & Transfer Strategies</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-survival-sagas-ultimate-10-roguely-games/"><u>[Updated] In 2024, Survival Sagas  Ultimate 10 Roguely Games</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-resource-list-of-3d-fonts-online/"><u>[Updated] Ultimate Resource List of 3D Fonts Online</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-capturing-movie-scenes-as-single-image-snapshots-windows-10/"><u>2024 Approved  Capturing Movie Scenes as Single Image Snapshots (Windows 10)</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-charting-growth-the-best-online-stock-yts/"><u>2024 Approved  Charting Growth  The Best Online Stock YTs</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unrivaled-handwear-elevate-your-vr-world/"><u>2024 Approved  Unrivaled Handwear  Elevate Your VR World</u></a></li>
<li><a href="https://games-able.techidaily.com/android-application-transition-to-linux-devices/"><u>Android Application Transition to Linux Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/connecting-controllers-perfectly-on-android-platforms/"><u>Connecting Controllers Perfectly on Android Platforms</u></a></li>
<li><a href="https://games-able.techidaily.com/diminishing-distractions-sound-management-on-xbox/"><u>Diminishing Distractions: Sound Management on Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/discontinuation-new-horizons-for-apsplus-gameplay/"><u>Discontinuation: New Horizons for APS+ Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/exploring-the-future-of-gaming-with-amd-rdna-35/"><u>Exploring the Future of Gaming with AMD RDNA 3.5</u></a></li>
<li><a href="https://games-able.techidaily.com/full-gameplay-experience-for-apple-m-devices-using-crossover/"><u>Full Gameplay Experience for Apple M Devices Using CrossOver</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-honor-90-lite-by-fonelab-android-recover-photos/"><u>How To  Restore Missing Photos Files from Honor 90 Lite.</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-deal-with-insufficient-ram-notice-roblox-on-iphone/"><u>How to Deal with Insufficient RAM Notice (Roblox) on iPhone</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-dominate-in-pokemon-games-on-your-ios-device/"><u>How to Dominate in Pokémon Games on Your iOS Device</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-to-apple-iphone-15-pro-drfone-by-drfone-ios/"><u>How to Mirror PC to Apple iPhone 15 Pro? | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-refund-a-game-on-steam-and-get-your-money-back/"><u>How to Refund a Game on Steam and Get Your Money Back</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 4 solution to get rid of pokemon fail to detect location On Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-simplified-pathway-facebook-vids-to-mp4-720p-and-1080p-hd-free/"><u>In 2024, Simplified Pathway  Facebook Vids to MP4, 720P & 1080P HD Free</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-step-by-step-guide-to-using-instagram-filters-and-icons/"><u>In 2024, Step-by-Step Guide to Using Instagram Filters and Icons</u></a></li>
<li><a href="https://games-able.techidaily.com/linkedin-has-added-games-but-heres-why-you-shouldnt-play-them/"><u>LinkedIn Has Added Games, but Here's Why You Shouldn't Play Them</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/mastering-sound-on-mac-navigating-through-the-top-5-audio-mixer-choices-for-2024/"><u>Mastering Sound on Mac Navigating Through The Top 5 Audio Mixer Choices for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/mobile-studio-kits-convenient-for-filmmakers-for-2024/"><u>Mobile Studio Kits  Convenient for Filmmakers for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/new-ps5-slim-understanding-its-impact/"><u>New PS5 Slim - Understanding Its Impact</u></a></li>
<li><a href="https://fix-guide.techidaily.com/oppo-a1x-5g-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo A1x 5G Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5-shortage-solved-will-prices-decrease-soon/"><u>PS5 Shortage Solved: Will Prices Decrease Soon?</u></a></li>
<li><a href="https://games-able.techidaily.com/raspberry-pi-gaming-face-off-batocera-or-retropie/"><u>Raspberry Pi Gaming Face-Off: Batocera or RetroPie?</u></a></li>
<li><a href="https://games-able.techidaily.com/rediscovering-the-magic-in-each-game-session/"><u>Rediscovering the Magic in Each Game Session</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/splicing-sounds-to-videos-on-w11-desktop/"><u>Splicing Sounds to Videos on W11 Desktop</u></a></li>
<li><a href="https://games-able.techidaily.com/strategies-for-quiet-voice-use-in-multiplayer-play/"><u>Strategies for Quiet Voice Use in Multiplayer Play</u></a></li>
<li><a href="https://games-able.techidaily.com/stunning-graphics-on-a-few-dollars/"><u>Stunning Graphics on a Few Dollars</u></a></li>
<li><a href="https://games-able.techidaily.com/the-rare-collectors-roadmap-scvs-elusive-treasures-76/"><u>The Rare Collector's Roadmap: SCV’s Elusive Treasures (76)</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-riots-user-name-revision-procedures/"><u>Understanding Riot's User Name Revision Procedures</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-secure-ps5-access-setting-up-custom-passwords/"><u>Unveiling Secure PS5 Access: Setting Up Custom Passwords</u></a></li>
<li><a href="https://facebook.techidaily.com/whistle-blowers-say-facebook-clamps-honesty-in-ads/"><u>Whistle-Blowers Say Facebook Clamps Honesty in Ads</u></a></li>
</ul></div>

---
title: "The Art of Condensing Classic Games: ChDMan's Approach Revealed"
date: 2024-08-15T17:20:36.062Z
updated: 2024-08-16T17:20:36.062Z
tags:
  - games
categories:
  - games
description: "This Article Describes The Art of Condensing Classic Games: ChDMan's Approach Revealed"
excerpt: "This Article Describes The Art of Condensing Classic Games: ChDMan's Approach Revealed"
keywords: Game Converting Techniques,Classic Games Revival,Detailed Gaming Guide,ChDMan Insights,Retro Game Transformation,Nostalgic Game Redux,Essential Gaming Tips
thumbnail: https://thmb.techidaily.com/efc3f590fc068b65cc8e4c4fda82884c66683db0be7b320fd391a90a34b6fb91.jpg
---

## The Art of Condensing Classic Games: ChDMan's Approach Revealed

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Compress Your ISOs With CHDMAN

 CHDMAN is distributed with the MAME emulator. If you already use that, you'll find CHDMAN's executable in MAME's installation directory. If not, download[the latest version of MAME from its official site](https://www.mamedev.org/) and install it on your PC to also get CHDMAN.

 To avoid typing the full path to CHDMAN every time you want to compress a ROM, add MAME's folder to your System Path variable. You can do this by[using environment variables in Windows 10](https://www.makeuseof.com/how-to-use-environment-variables-in-windows-10/) .

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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

![DuckStation File Selector set to MAME CHD images](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/duckstation-chd-file-selection-1.jpg)
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
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

 Because of[how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like[using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-clips.techidaily.com/new-bridging-platforms-from-tiktok-to-your-facebook-friends-for-2024/"><u>[New] Bridging Platforms  From TikTok to Your Facebook Friends for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-how-to-elevate-your-profile-on-discord-with-custom-emoji-stamps/"><u>[New] How to Elevate Your Profile on Discord with Custom Emoji Stamps</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-streamlining-social-media-facebook-video-auto-play-for-2024/"><u>[New] Streamlining Social Media  Facebook Video Auto-Play for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-optimizing-video-conference-set-ups-slack-and-filmora-guide/"><u>[Updated] In 2024, Optimizing Video Conference Set-Ups  Slack & Filmora Guide</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-6-superior-apps-for-effortless-mac-video-grabbing/"><u>2024 Approved  6 Superior Apps for Effortless Mac Video Grabbing</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-discerning-t-series-profit-mechanisms-from-youtube-views/"><u>2024 Approved  Discerning T-Series' Profit Mechanisms From Youtube Views</u></a></li>
<li><a href="https://games-able.techidaily.com/3-prime-video-music-and-game-services-on-switch/"><u>3 Prime Video, Music, and Game Services on Switch</u></a></li>
<li><a href="https://location-fake.techidaily.com/3utools-virtual-location-not-working-on-oppo-reno-11f-5g-fix-now-drfone-by-drfone-virtual-android/"><u>3uTools Virtual Location Not Working On Oppo Reno 11F 5G? Fix Now | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/4-digital-detectives-ai-infused-puzzles/"><u>4 Digital Detectives: AI-Infused Puzzles</u></a></li>
<li><a href="https://games-able.techidaily.com/5-ways-you-can-maintain-your-nintendo-switch-and-extend-its-lifespan/"><u>5 Ways You Can Maintain Your Nintendo Switch (and Extend Its Lifespan)</u></a></li>
<li><a href="https://games-able.techidaily.com/6-top-considerations-in-the-path-to-owning-ps5/"><u>6 Top Considerations in the Path to Owning PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/6-ways-to-cope-with-gaming-burnout/"><u>6 Ways to Cope With Gaming Burnout</u></a></li>
<li><a href="https://games-able.techidaily.com/6-ways-to-use-your-ps5-without-a-controller/"><u>6 Ways to Use Your PS5 Without a Controller</u></a></li>
<li><a href="https://games-able.techidaily.com/7-great-games-you-can-play-in-your-linux-terminal/"><u>7 Great Games You Can Play in Your Linux Terminal</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-list-of-things-to-evaluate-before-buying-your-next-handheld-videogame-console/"><u>A Comprehensive List of Things to Evaluate Before Buying Your Next Handheld Videogame Console</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensive-look-at-steam-decks-keyboard/"><u>A Comprehensive Look at Steam Deck's Keyboard</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-wave-of-vintage-gameplay/"><u>A New Wave of Vintage Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/a-quick-tutorial-clearing-old-ps5-saved-files/"><u>A Quick Tutorial: Clearing Old PS5 Saved Files</u></a></li>
<li><a href="https://games-able.techidaily.com/a-stellar-google-play-pass-with-a-tiny-hitch/"><u>A Stellar Google Play Pass with a Tiny Hitch</u></a></li>
<li><a href="https://games-able.techidaily.com/accelerate-fun-factors-essential-5-steps-to-better-games-on-macos/"><u>Accelerate Fun Factors: Essential 5 Steps to Better Games on macOS</u></a></li>
<li><a href="https://games-able.techidaily.com/achdman-strategies-preserving-and-accessing-your-vintage-games/"><u>ACHDMAN Strategies: Preserving and Accessing Your Vintage Games</u></a></li>
<li><a href="https://games-able.techidaily.com/achieve-peak-performance-with-optimal-mouse-settings-in-gaming/"><u>Achieve Peak Performance with Optimal Mouse Settings in Gaming</u></a></li>
<li><a href="https://extra-resources.techidaily.com/action-unleashed-the-latest-in-filmmaking-from-polaroids-xs-for-2024/"><u>Action Unleashed  The Latest in Filmmaking From Polaroid's XS for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-essential-items-lacking-windows-error/"><u>Addressing Essential Items Lacking Windows Error</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-joy-con-communication-breakdown-with-switch-device/"><u>Addressing Joy-Con Communication Breakdown with Switch Device</u></a></li>
<li><a href="https://games-able.techidaily.com/affordable-gaming-delights-for-your-switch-console/"><u>Affordable Gaming Delights for Your Switch Console</u></a></li>
<li><a href="https://games-able.techidaily.com/ai-innovation-showcase-at-computex-2024/"><u>AI Innovation Showcase at Computex 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/ai-transformation-in-nvidias-graphics-technology-dlss-35/"><u>AI Transformation in Nvidia's Graphics Technology - DLSS 3.5</u></a></li>
<li><a href="https://games-able.techidaily.com/aim-higher-identifying-top-specifications-in-gaming-screens/"><u>Aim Higher: Identifying Top Specifications in Gaming Screens</u></a></li>
<li><a href="https://games-able.techidaily.com/analyzing-content-policies-steam-and-gog-contrast-study/"><u>Analyzing Content Policies: Steam & GOG Contrast Study</u></a></li>
<li><a href="https://games-able.techidaily.com/analyzing-discords-nitro-benefits/"><u>Analyzing Discord's Nitro Benefits</u></a></li>
<li><a href="https://games-able.techidaily.com/andaseats-cheat-codes-a-limited-time-event/"><u>AndaSeat's 'Cheat Codes': A Limited-Time Event</u></a></li>
<li><a href="https://games-able.techidaily.com/asus-rog-ally-dock-showcase-top-picks-2024/"><u>ASUS ROG Ally Dock Showcase: Top Picks 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/audio-control-a-guide-to-peaceful-gaming-experience/"><u>Audio Control: A Guide to Peaceful Gaming Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/audiophiles-guide-to-in-ear-monitors-for-gamers/"><u>Audiophiles' Guide to In-Ear Monitors for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/auditory-enhancement-through-hrtf-for-competitive-players-in-valorant/"><u>Auditory Enhancement Through HRTF for Competitive Players in Valorant</u></a></li>
<li><a href="https://games-able.techidaily.com/automated-gpu-integration-for-gaming-snippets/"><u>Automated GPU Integration for Gaming Snippets</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-game-installation-oversight-by-steam/"><u>Avoiding Game Installation Oversight by Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171300843-beam-of-brilliance-choose-broad-bold-framing-for-games/"><u>Beam of Brilliance: Choose Broad, Bold Framing for Games!</u></a></li>
<li><a href="https://games-able.techidaily.com/before-you-join-the-linkedin-game-consider-these-points/"><u>Before You Join the LinkedIn Game, Consider These Points</u></a></li>
<li><a href="https://games-able.techidaily.com/best-of-the-best-select-nintendo-switch-dock-options/"><u>Best of the Best: Select Nintendo Switch Dock Options</u></a></li>
<li><a href="https://games-able.techidaily.com/best-seated-player-partnerships-top-16-on-xbox-series-sx/"><u>Best Seated Player Partnerships - Top 16 on Xbox Series S/X</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169813163-elevate-gbadvance-titles-on-your-ios-device/"><u>Elevate GBAdvance Titles on Your iOS Device!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-vivo-t2x-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Vivo T2x 5G Phones with/without a PC</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-vivo-y28-5g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Vivo Y28 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-text-artistry-in-ae-our-top-10-recommendations/"><u>In 2024, Text Artistry in AE  Our Top 10 Recommendations</u></a></li>
<li><a href="https://extra-resources.techidaily.com/mastering-the-art-of-webp-conversion-to-jpeg/"><u>Mastering the Art of WebP Conversion to JPEG</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-in-this-article-we-will-review-gopro-quik-for-desktop-and-recommend-alternatives-to-gopro-quik-pc/"><u>New In 2024, In This Article, We Will Review Gopro Quik for Desktop and Recommend Alternatives to Gopro Quik Pc</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170168370-overcome-system-errors-install-updated-nvidia-drivers/"><u>Overcome System Errors - Install Updated Nvidia Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-address-microsoft-store-monochrome-issue/"><u>Steps to Address Microsoft Store Monochrome Issue</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172148302-unlock-excitement-dive-into-netflix-gaming-world/"><u>Unlock Excitement - Dive Into Netflix Gaming World!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719162457406-youtube-reworking-its-arsenal-with-cutting-edge-mini-games/"><u>YouTube Reworking Its Arsenal with Cutting-Edge Mini Games</u></a></li>
</ul></div>

---
title: "Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method"
date: 2024-09-09T09:33:55.858Z
updated: 2024-09-10T09:33:55.858Z
tags:
  - games
categories:
  - games
description: "This Article Describes Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method"
excerpt: "This Article Describes Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method"
keywords: Streamlined Classics,ISO Sizes Mini,DMan Cooking Style,Classic Collection,Small-Sized ISOs,ChDMan' Techniques,Efficient ISO Methods
thumbnail: https://thmb.techidaily.com/04f98c03565f60c0b0ad3b1ba3f80966cc746c43e46cf7809dfb5c690e2c4abe.jpg
---

## Streamline Your Classic Collection: Small-Sized ISOs by ChDMan' Cooking Method

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
<a href="https://aligracehair.sjv.io/c/5597632/2115936/19272" target="_top" id="2115936">
  <img src="//a.impactradius-go.com/display-ad/19272-2115936" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115936/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123735/7443" target="_top" id="2123735">
  <img src="//a.impactradius-go.com/display-ad/7443-2123735" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123735/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This way, you can compress the ROMs of all the consoles that used optical media (CDs and DVDs) into the CHD format. However, there's a particular case we have to mention: hard disk images.

 CHDMAN and the CHD format can also be used to store compressed HDD backups. Those may share the same extension with optical backups saved as BIN and IMG, but you have to use a tweaked version of the above command to compress HDDs to CHDs:

`chdman createhd -i "OLDPCback.img" -o "OLDPCback.chd"`

 CHDMAN can also back up to the CHD format actual HDDs connected to the PC. That, though, should be rarely needed by the average user.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What Else Should You Know About CHDs?

 Knowing how to compress your large ROMs to leaner CHD files is our target in this article. Still, the following might be helpful if you decide to use that file format for your emulated games.

### Which Emulators Support CHDs?

 Although CHD files are now considered a standard for storing optical media and HDD backups in a compressed emulation-friendly format, not all emulators support them.

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

 Because of [how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like [using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123480/16836" target="_top" id="2123480">
  <img src="//a.impactradius-go.com/display-ad/16836-2123480" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123480/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-tackling-inaudible-portions-in-partially-muted-fb-media/"><u>[Updated] 2024 Approved Tackling Inaudible Portions in Partially Muted FB Media</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-exploring-the-world-of-aspect-ratios-in-youtube-content-for-2024/"><u>[Updated] Exploring the World of ASPECT RATIOS in YOUTUBE Content for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-fact-vs-fiction-decoding-the-world-of-instagram-reels/"><u>[Updated] In 2024, Fact vs Fiction Decoding the World of Instagram Reels</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-perfect-your-podcast-secrets-for-compelling-opening-videos/"><u>2024 Approved Perfect Your Podcast Secrets for Compelling Opening Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-smooth-visual-journeys-master-fades-in-a-flash/"><u>2024 Approved Smooth Visual Journeys Master Fades in a Flash</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/dynamic-broadcasting-with-manycam-your-go-to-live-streaming-virtual-camera-and-video-editing-tool/"><u>Dynamic Broadcasting with ManyCam: Your Go-To Live Streaming, Virtual Camera, and Video Editing Tool</u></a></li>
<li><a href="https://games-able.techidaily.com/enhancing-your-wallets-gaming-capacity-on-steam/"><u>Enhancing Your Wallet's Gaming Capacity on Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/enjoy-full-adventure-of-baldurs-gate-3-easily-through-crossover-on-macos/"><u>Enjoy Full Adventure of Baldur’s Gate 3 Easily Through CrossOver on macOS</u></a></li>
<li><a href="https://games-able.techidaily.com/excellent-visuals-best-monitors-at-240hz-for-gamers/"><u>Excellent Visuals: Best Monitors at 240Hz for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-check-out-how-much-vram-you-have/"><u>How to Check Out How Much VRAM You Have</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-efficiently-wipe-your-ps5s-history/"><u>How to Efficiently Wipe Your PS5's History</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-globalscreen-top-ranked-local-and-live-tv-streams/"><u>In 2024, GlobalScreen Top-Ranked Local & Live TV Streams</u></a></li>
<li><a href="https://games-able.techidaily.com/is-the-gaming-quality-of-am08-pro-validated/"><u>Is the Gaming Quality of AM08 Pro Validated?</u></a></li>
<li><a href="https://games-able.techidaily.com/late-launches-the-unseen-growth-catalyst/"><u>Late Launches: The Unseen Growth Catalyst</u></a></li>
<li><a href="https://games-able.techidaily.com/leveraging-persuasive-techniques-for-impactful-steam-critiques/"><u>Leveraging Persuasive Techniques for Impactful Steam Critiques</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/macmpegmpeg/"><u>Mac用無料MPEG動画変換ソフト：高解像度・低解像度ビデオの効率的なMPEG化</u></a></li>
<li><a href="https://games-able.techidaily.com/mastering-twitch-vod-extraction-with-our-best-picks/"><u>Mastering Twitch VOD Extraction with Our Best Picks</u></a></li>
<li><a href="https://games-able.techidaily.com/ps5s-leap-from-bulky-to-compact-wonder/"><u>PS5's Leap From Bulky to Compact Wonder</u></a></li>
<li><a href="https://games-able.techidaily.com/reduce-battery-drain-enhance-gameplay-with-xbox-techniques/"><u>Reduce Battery Drain, Enhance Gameplay with Xbox Techniques</u></a></li>
<li><a href="https://games-able.techidaily.com/roblox-fps-unlockers-functionality-and-safety-concerns/"><u>Roblox FPS Unlockers: Functionality & Safety Concerns</u></a></li>
<li><a href="https://games-able.techidaily.com/safe-speaking-hiding-your-voice-on-xbox/"><u>Safe Speaking: Hiding Your Voice on Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/shifting-from-bedrocks-world-to-java-via-geysermc-server/"><u>Shifting From Bedrock's World to Java via GeyserMC Server</u></a></li>
<li><a href="https://games-able.techidaily.com/sky-high-gameplay-maximizing-your-pcs-fps-capability/"><u>Sky-High Gameplay: Maximizing Your PC's FPS Capability</u></a></li>
<li><a href="https://games-able.techidaily.com/tactical-triumphs-an-exclusive-guide-to-top-11-strategy-titles/"><u>Tactical Triumphs: An Exclusive Guide to Top 11 Strategy Titles</u></a></li>
<li><a href="https://games-able.techidaily.com/the-best-modern-retro-consoles/"><u>The Best Modern Retro Consoles</u></a></li>
<li><a href="https://technical-tips.techidaily.com/the-ultimate-viewing-guide-watching-the-matrix-trilogy-sequentially/"><u>The Ultimate Viewing Guide: Watching The Matrix Trilogy Sequentially</u></a></li>
<li><a href="https://games-able.techidaily.com/top-quality-desk-matts-ready-for-modern-workspaces/"><u>Top Quality Desk Matts Ready for Modern Workspaces</u></a></li>
<li><a href="https://games-able.techidaily.com/transform-your-gaming-experience-with-ultimate-xbox/"><u>Transform Your Gaming Experience with Ultimate Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/ultimate-gaming-core-battle-who-will-prevail/"><u>Ultimate Gaming Core Battle: Who Will Prevail?</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-the-past-ios-and-classic-psp-games-combo/"><u>Unlocking the Past: IOS & Classic PSP Games Combo</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-in-2024-adding-audiovisual-elements-in-cinema-pro-step-by-step-guide/"><u>Updated In 2024, Adding Audiovisual Elements in Cinema Pro Step-by-Step Guide</u></a></li>
</ul></div>

---
title: Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques
date: 2024-09-09T09:47:16.116Z
updated: 2024-09-10T09:47:16.116Z
tags:
  - games
categories:
  - games
description: This Article Describes Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques
excerpt: This Article Describes Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques
keywords: Arcades Miniature Storage,CHDMAN Archiving Tips,Efficient Archive Methods,Miniaturize Arcade Files,Archive Technique CHDMAN,Small-Scale Arcade Backup,Arcade Data Compression
thumbnail: https://thmb.techidaily.com/ad574335e648a7deda4261a3d60c02e5050876ad97d3a8d2551786ec91da20e4.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Miniaturize Your Arcade Archive with Efficient CHDMAN Techniques

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
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

 Because of[how LaunchBox works](https://www.makeuseof.com/what-is-launchbox-how-it-works/) and other front-end services you can use for emulation, like[using RetroArch on Windows](https://www.makeuseof.com/windows-retroarch-setup/) , CHDs should work on these services too.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### How Can You Check Your CHDs?

 CHDMAN isn't only a compression solution but, as its name states, a manager for CHD files. So, you can also use it to...

* Get info about CHD files by using the**chdman info -i "FILENAME.chd"** prompt.
* Check CHD files by using the**chdman verify -i "FILENAME.chd"** prompt.

### Can You Decompress CHDs?

 Decompressing CHDs is almost the reverse of how you compress them. Since the format supports optical media and HDD backups, you must customize the command you'll use according to the media you're dealing with.

![A screenshot of the CHD Required category in the MAME emulator](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/mame-requires-chd-filter.jpg)

<!-- affiliate ads begin -->
<span id="1982485">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982485.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982485">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982485.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982485%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982485/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 CHDMAN can only extract optical media backups back to the CUE & BIN combination with:

`chdman.exe extractcd -i "INPUT.chd" -o "OUTPUT.cue"`

 You don't have to specify the BIN file; CHDMAN creates it automatically using the same name used for the CUE file. To extract compressed HDD backups, swap "extractcd" with "extracthd" as follows:

`chdman.exe extracthd -i "INPUT.chd" -o "OUTPUT.IMG"`

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-hints.techidaily.com/new-capturing-brilliance-essential-angles-in-iphone-photography/"><u>[New] Capturing Brilliance Essential Angles in iPhone Photography</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-cutting-edge-techniques-pushing-boundaries-in-youtube-cinematography-for-2024/"><u>[New] Cutting Edge Techniques Pushing Boundaries in YouTube Cinematography for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-from-compressed-to-captioned-zip-to-srt-effortlessly-for-2024/"><u>[New] From Compressed To Captioned Zip to .Srt Effortlessly for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-harnessing-your-youtube-content-for-financial-rewards/"><u>[New] In 2024, Harnessing Your YouTube Content for Financial Rewards</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-simplifying-video-workflows-with-showmores-top-recording-tool-for-2024/"><u>[New] Simplifying Video Workflows with ShowMore's Top Recording Tool for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-professional-rapid-thumbnail-artistry-for-valorant-games/"><u>[Updated] Professional Rapid Thumbnail Artistry for Valorant Games</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unleashing-creativity-making-photo-based-videos-using-pixiz/"><u>[Updated] Unleashing Creativity Making Photo-Based Videos Using Pixiz</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-essential-5-online-video-capture-apps/"><u>2024 Approved Essential 5 Online Video Capture Apps</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gratis-strategies-for-streaming-c-span-videos-online/"><u>2024 Approved Gratis Strategies for Streaming C-Span Videos Online</u></a></li>
<li><a href="https://games-able.techidaily.com/controller-android-synergy-a-practical-handbook-for-gamers/"><u>Controller-Android Synergy: A Practical Handbook for Gamers</u></a></li>
<li><a href="https://games-able.techidaily.com/deciphering-and-solving-error-code-403-in-roblox-windows-edition/"><u>Deciphering & Solving Error Code 403 in Roblox Windows Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/demystifying-steam-stats-understanding-time-logged-and-rewards-earned/"><u>Demystifying Steam Stats: Understanding Time Logged & Rewards Earned</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-gameplay-avoiding-fps-drops-in-valorant-windows-edition/"><u>Elevate Your Gameplay: Avoiding FPS Drops in Valorant Windows Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/explore-worldwide-with-your-nintendo-switch/"><u>Explore Worldwide with Your Nintendo Switch</u></a></li>
<li><a href="https://games-able.techidaily.com/from-basic-to-expert-utilizing-every-feature-of-ea-play-ps5-edition/"><u>From Basic to Expert: Utilizing Every Feature of EA Play PS5 Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/google-play-pass-is-great-except-for-this-one-thing/"><u>Google Play Pass Is Great, Except for This One Thing</u></a></li>
<li><a href="https://games-able.techidaily.com/grit-and-patience-top-5-obdurate-gaming-tests/"><u>Grit and Patience: Top 5 Obdurate Gaming Tests</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-block-steams-startup-routine/"><u>How to Block Steam's Startup Routine</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1723808218067-how-to-import-chrome-bookmarks-to-firefox-quickly-and-easily/"><u>How to Import Chrome Bookmarks to Firefox. Quickly & Easily!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-honor-100-frp-bypass-by-drfone-android/"><u>In 2024, About Honor 100 FRP Bypass</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-immersion-in-the-most-realistic-water-games/"><u>In 2024, Immersion in the Most Realistic Water Games</u></a></li>
<li><a href="https://games-able.techidaily.com/innovative-steps-forward-a-guide-to-steam-deck-enhancements/"><u>Innovative Steps Forward: A Guide to Steam Deck Enhancements</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/inspirational-homebuilds-for-snapshot-enthusiasts-for-2024/"><u>Inspirational Homebuilds for Snapshot Enthusiasts for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/is-enhancing-roblox-frame-rate-risky/"><u>Is Enhancing Roblox Frame Rate Risky?</u></a></li>
<li><a href="https://games-able.techidaily.com/light-up-your-room-optimal-panel-sets-for-thrilling-games/"><u>Light Up Your Room: Optimal Panel Sets for Thrilling Games</u></a></li>
<li><a href="https://games-able.techidaily.com/mastery-over-your-steam-account-eradicating-gaming-clutter/"><u>Mastery Over Your Steam Account: Eradicating Gaming Clutter</u></a></li>
<li><a href="https://games-able.techidaily.com/mini-pc-evaluation-is-it-right-for-you-over-desktops/"><u>Mini PC Evaluation: Is It Right for You Over Desktops?</u></a></li>
<li><a href="https://games-able.techidaily.com/msis-ultimate-warrior-raider-ge78-examined/"><u>MSI's Ultimate Warrior: Raider GE78 Examined</u></a></li>
<li><a href="https://win-solutions.techidaily.com/netflix-streaming-restored-addressing-common-xbox-one-hurdles/"><u>Netflix Streaming Restored: Addressing Common Xbox One Hurdles</u></a></li>
<li><a href="https://ai-topics.techidaily.com/new-what-is-an-ai-script-generator-in-2024/"><u>New What Is an AI Script Generator, In 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/power-up-your-playstation-pc-with-game-launchers/"><u>Power Up Your PlayStation PC with Game Launchers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-oneplus-12r-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For OnePlus 12R | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/refine-gaming-atmosphere-personalizing-the-xbox-game-bar-for-a-besposkexpenses-windows-pc/"><u>Refine Gaming Atmosphere: Personalizing the Xbox Game Bar for a Besposkexpenses Windows PC</u></a></li>
<li><a href="https://games-able.techidaily.com/rethinking-how-you-view-your-steam-points/"><u>Rethinking How You View Your Steam Points</u></a></li>
<li><a href="https://games-able.techidaily.com/revolutionize-your-ps5-games-effortlessly/"><u>Revolutionize Your PS5 Games, Effortlessly</u></a></li>
<li><a href="https://games-able.techidaily.com/scrutinizing-ea-plays-payment-requirements/"><u>Scrutinizing EA Play's Payment Requirements</u></a></li>
<li><a href="https://games-able.techidaily.com/seamless-transition-ps4-to-ps5-gameplay/"><u>Seamless Transition: PS4 to PS5 Gameplay</u></a></li>
<li><a href="https://games-able.techidaily.com/steam-a-history-of-video-games-pricing/"><u>Steam: A History of Video Games Pricing</u></a></li>
<li><a href="https://games-able.techidaily.com/the-complete-players-guide-to-navigating-ea-play-features-on-ps5/"><u>The Complete Player’s Guide to Navigating EA Play Features on PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/the-premier-asus-rog-ally-docks-for-laptop-users-2024/"><u>The Premier ASUS ROG Ally Docks for Laptop Users, 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-game-changer-installing-windows-on-a-steam-deck/"><u>The Ultimate Game Changer: Installing Windows on a Steam Deck</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-guide-to-retro-games-compression-by-chdman/"><u>The Ultimate Guide to Retro Games Compression by ChDMan</u></a></li>
<li><a href="https://games-able.techidaily.com/timecapsule-pocket-retro-console-redux/"><u>TimeCapsule Pocket: Retro Console Redux</u></a></li>
<li><a href="https://games-able.techidaily.com/unjamming-steams-content-stream-process/"><u>Unjamming Steam's Content Stream Process</u></a></li>
<li><a href="https://games-able.techidaily.com/unraveling-the-cause-of-error-30005-failed-files/"><u>Unraveling the Cause of Error 30005: Failed Files</u></a></li>
</ul></div>

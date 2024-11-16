---
title: "Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size"
date: 2024-11-13T16:54:30.751Z
updated: 2024-11-16T04:19:42.425Z
tags:
  - games
categories:
  - games
description: "This Article Describes Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size"
excerpt: "This Article Describes Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size"
keywords: Space Saver Gaming,ISO Size Reduction,CHDMAN Method,Game Optimization,Memory Efficiency,Save Games Quickly,Tech Game Tips
thumbnail: https://thmb.techidaily.com/90ad0e184ba79f95e662dd6bac421c2714531f47a3dc9eccb9055a4b28f7166a.jpg
---

## Space-Saver Techniques: Using CHDMAN to Minimize Game ISO Size

 If you're collecting ROMs like Pokémon, you surely have noticed that the ones for newer platforms take up a significant chunk of your storage. A single game might require multiple gigabytes of storage. Keep over a dozen, and your ROM collection can quickly expand to many Terabytes. That's where the MAME project's CHDMAN tool can help.

 Does your ROM collection contain arcade games or titles for consoles with optical media, like Sony's PlayStation? CHDMAN can compress them to CHD files that take up a fraction of a ROM's original size.

 What's best is that many emulators support the CHD format. So, you can keep playing your ROMs without extracting or decompressing them. Let's see how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1948932/19272" target="_top" id="1948932">
  <img src="//a.impactradius-go.com/display-ad/19272-1948932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

To compress your game with CHDMAN to CHD format, use the following:

`chdman.exe createcd -i "ROM_YOU_WANT_TO_COMPRESS.CUE" -o "FILENAME_OF_COMPRESSED.CHD"`

Our command was:

`chdman createcd -i "MUO_PSX.cue" -o "MUO_PSX.chd"  
`

![A screenshot of the command to compress a ROM into CHD format using CHDMAN](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/chdman-createcd-command-in-cmd.jpg)

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-flipping-fun-facts-into-memes-with-kinemaster/"><u>[New] Flipping Fun Facts Into Memes with KineMaster</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-perfected-panels-expert-recommended-photo-editing-screens/"><u>[New] In 2024, Perfected Panels Expert-Recommended Photo Editing Screens</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-explore-youtube-rankings-seo-tools-for-peak-performance/"><u>[Updated] 2024 Approved Explore YouTube Rankings SEO Tools for Peak Performance</u></a></li>
<li><a href="https://games-able.techidaily.com/ace-the-art-of-fps-with-counter-strike-tips/"><u>Ace the Art of FPS with Counter-Strike Tips</u></a></li>
<li><a href="https://network-issues.techidaily.com/adjusting-reverse-image-problem-on-windows-7-device/"><u>Adjusting Reverse Image Problem on Windows 7 Device</u></a></li>
<li><a href="https://howto.techidaily.com/asus-rog-phone-8-stuck-on-screen-finding-solutions-for-stuck-on-boot-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Asus ROG Phone 8 Stuck on Screen – Finding Solutions For Stuck on Boot | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/boost-your-teams-efficiency-discover-the-surprising-impact-of-ai-on-productivity-insights-and-strategies-from-zdnet/"><u>Boost Your Team's Efficiency: Discover the Surprising Impact of AI on Productivity – Insights and Strategies From ZDNet</u></a></li>
<li><a href="https://games-able.techidaily.com/disconnect-screen-games-in-discord/"><u>Disconnect Screen Games in Discord</u></a></li>
<li><a href="https://games-able.techidaily.com/eas-pricing-jab-i-retreat-from-subscription-life/"><u>EA’s Pricing Jab, I Retreat From Subscription Life</u></a></li>
<li><a href="https://games-able.techidaily.com/forgoing-a-game-a-refund-approach-for-xbox-users/"><u>Forgoing a Game - A Refund Approach for Xbox Users</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-samsung-galaxy-z-flip-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Samsung Galaxy Z Flip 5 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-nokia-g310-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Nokia G310 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-quantum-hdrs-role-in-modern-photography-trends/"><u>In 2024, Quantum HDR's Role in Modern Photography Trends</u></a></li>
<li><a href="https://games-able.techidaily.com/keeping-the-kingdom-secure-online-gaming-risks/"><u>Keeping the Kingdom Secure: Online Gaming Risks</u></a></li>
<li><a href="https://games-able.techidaily.com/size-shapes-strategy-the-impact-on-game-publishing-giants-strategic-analysis-report/"><u>Size Shapes Strategy: The Impact on Game Publishing Giants? [Strategic Analysis Report]</u></a></li>
<li><a href="https://games-able.techidaily.com/the-essence-of-modernizing-classics-six-stories-on-pi/"><u>The Essence of Modernizing Classics - Six Stories on Pi</u></a></li>
<li><a href="https://games-able.techidaily.com/the-microsoftblizzard-pact-could-it-be-a-win-win-or-a-risk/"><u>The Microsoft/Blizzard Pact: Could It Be a Win-Win or a Risk?</u></a></li>
<li><a href="https://games-able.techidaily.com/the-ultimate-list-10-exciting-free-to-play-games/"><u>The Ultimate List: 10 Exciting, Free-to-Play Games</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-steps-for-stabilizing-arcadegeddon-gameplay-on-computer-setups/"><u>Troubleshooting Steps for Stabilizing Arcadegeddon Gameplay on Computer Setups</u></a></li>
</ul></div>


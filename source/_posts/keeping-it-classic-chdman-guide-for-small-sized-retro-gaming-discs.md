---
title: "Keeping It Classic: CHDMAN Guide for Small-Sized Retro Gaming Discs"
date: 2024-07-12T03:38:45.741Z
updated: 2024-07-13T03:38:45.741Z
tags:
  - games
categories:
  - games
description: "This Article Describes Keeping It Classic: CHDMAN Guide for Small-Sized Retro Gaming Discs"
excerpt: "This Article Describes Keeping It Classic: CHDMAN Guide for Small-Sized Retro Gaming Discs"
keywords: Retro Gaming Guide,Small Retro Disc,CHDMAN Retro Guide,Classic Gaming Discs,Retro Console Guide,Small Sized Games,Nostalgic Gaming Tips
thumbnail: https://thmb.techidaily.com/dd8665fd574b8b8849bc905e8ab75258e662c1b7c7637037d5e86d15b1b9eaa1.png
---

## Keeping It Classic: CHDMAN Guide for Small-Sized Retro Gaming Discs

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
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-motorola-moto-g04-unlock-without-password-by-drfone-android/"><u>5 Solutions For Motorola Moto G04 Unlock Without Password</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-peering-into-popularity-twitters-top-videos/"><u>[Updated] Peering Into Popularity  Twitter’s Top Videos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-ad-dollars-boost-your-view-count-for-free-for-2024/"><u>Avoid Ad Dollars – Boost Your View Count for Free for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-use-playstation-4-on-your-windows-or-macos-device/"><u>How to Use PlayStation 4 on Your Windows or macOS Device</u></a></li>
<li><a href="https://games-able.techidaily.com/elevating-your-gaming-experience-with-counter-strike-2-on-a-mac/"><u>Elevating Your Gaming Experience with Counter-Strike 2 on a Mac</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-navigating-social-surveys-instagram-stories-edition/"><u>[New] 2024 Approved  Navigating Social Surveys  Instagram Stories Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/5-ways-you-can-maintain-your-xbox-series-x-hardware/"><u>5 Ways You Can Maintain Your Xbox Series X Hardware</u></a></li>
<li><a href="https://games-able.techidaily.com/game-on-slow-down-discover-idles/"><u>Game On, Slow Down: Discover Idles</u></a></li>
<li><a href="https://games-able.techidaily.com/become-a-pokemon-expert-iphone-and-ipad-gameplay-secrets/"><u>Become a Pokémon Expert: IPhone & iPad Gameplay Secrets</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-correct-mc-launcher-failure-error-0x803f8001-in-mcpc/"><u>How to Correct MC Launcher Failure: Error 0X803F8001 in MCPC</u></a></li>
<li><a href="https://games-able.techidaily.com/can-ps5s-dualsense-play-on-ps4-devices/"><u>Can PS5's DualSense Play on PS4 Devices?</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-friendly-gaming-xbox-series-xs-edition/"><u>Budget-Friendly Gaming: Xbox Series X/S Edition</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/superior-5-social-sites-redefining-connectivity-for-2024/"><u>Superior 5 Social Sites, Redefining Connectivity for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-new-ways-to-play-xbox-one/"><u>Discovering New Ways to Play Xbox One</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-capturing-motion-canon-camera-time-lapse-basics/"><u>2024 Approved  Capturing Motion  Canon Camera Time-Lapse Basics</u></a></li>
<li><a href="https://howto.techidaily.com/oppo-a38-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo A38 Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/essential-input-devices-for-switch-gaming-setup-90-chars/"><u>Essential Input Devices for Switch Gaming Setup (90 Chars)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-professional-video-capture-techniques-mastering-movs-on-win10/"><u>In 2024, Professional Video Capture Techniques  Mastering MOVs on Win10</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-booktoks-15-essential-titles-for-avid-readers/"><u>[Updated] BookTok's 15 Essential Titles for Avid Readers</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/captivate-viewers-earn-accolades-tips-for-staff-picks-on-vimeo-for-2024/"><u>Captivate Viewers, Earn Accolades  Tips for Staff Picks on Vimeo for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-download-and-relive-a-compreran-review-of-top-youtube-playlist-extractors/"><u>[Updated] Download and Relive  A Compreran Review of Top YouTube Playlist Extractors</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-nostalgia-revisited-a-curated-list-of-top-ps3-emulators-for-pc/"><u>Gaming Nostalgia Revisited: A Curated List of Top PS3 Emulators for PC</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-oppo-reno-11-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/channel-management-excellence-perfecting-blockunblock-techniques-on-twitch/"><u>Channel Management Excellence: Perfecting Block/Unblock Techniques on Twitch</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-hdr-potential-with-photo-hdr-techniques/"><u>2024 Approved  Unlocking HDR Potential with Photo-HDR Techniques</u></a></li>
<li><a href="https://games-able.techidaily.com/creative-game-writing-with-chatgpt/"><u>Creative Game Writing with ChatGPT</u></a></li>
<li><a href="https://games-able.techidaily.com/chatgpt-and-dungeons-6-secrets-to-perfect-assistantship/"><u>ChatGPT & Dungeons: 6 Secrets to Perfect Assistantship</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-how-to-record-a-twitch-gameplay-stream/"><u>2024 Approved  How to Record a Twitch Gameplay Stream</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-friendly-boards-next-gen-gaming-companions/"><u>Budget-Friendly Boards: Next Gen Gaming Companions</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-automated-audiences-into-authentic-engagement-for-2024/"><u>Trick Automated Audiences Into Authentic Engagement for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/intel-stream-assist-unraveled-a-game-changer-in-streaming/"><u>Intel Stream Assist Unraveled: A Game-Changer in Streaming?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expert-techniques-for-streamers-on-macos/"><u>2024 Approved  Expert Techniques for Streamers on macOS</u></a></li>
<li><a href="https://games-able.techidaily.com/eliminate-freezing-woes-securing-epic-game-launcher-stability/"><u>Eliminate Freezing Woes: Securing Epic Game Launcher Stability</u></a></li>
<li><a href="https://games-able.techidaily.com/boosting-your-gaming-budget-in-ps-store/"><u>Boosting Your Gaming Budget in PS Store</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/sculpt-your-shots-in-the-digital-realm-for-2024/"><u>Sculpt Your Shots in the Digital Realm for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/expecting-more-from-play-understanding-steams-ai-directive/"><u>Expecting More From Play: Understanding Steam's AI Directive</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-streamlining-communication-scheduling-monthly-meets/"><u>[New] Streamlining Communication  Scheduling Monthly Meets</u></a></li>
<li><a href="https://games-able.techidaily.com/convenience-meets-connectivity-mobile-twitch-streaming-101/"><u>Convenience Meets Connectivity: Mobile Twitch Streaming 101</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-open-your-apple-iphone-8-plus-without-a-home-button-by-drfone-ios/"><u>How To Open Your Apple iPhone 8 Plus Without a Home Button</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-web-add-on-fb-stories-repository-app/"><u>[New] Web Add-On  FB Stories Repository App</u></a></li>
<li><a href="https://games-able.techidaily.com/embark-on-bedrock-server-conversion-to-java/"><u>Embark on Bedrock Server Conversion to Java</u></a></li>
</ul></div>

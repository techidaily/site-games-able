---
title: "Fixing Windows 10/11: Driver Not Starting Error"
date: 2024-07-12T03:46:45.406Z
updated: 2024-07-13T03:46:45.406Z
tags:
  - games
categories:
  - games
description: "This Article Describes Fixing Windows 10/11: Driver Not Starting Error"
excerpt: "This Article Describes Fixing Windows 10/11: Driver Not Starting Error"
keywords: Windows 10/11 Troubleshooting,Drivers Not Starting Issue,Windows Error Code,Fix Driver Not Starting on Windows 10/11,Windows Error Fix,Driver Reinstallation Windows 10/11,Boot Configuration Editor for Windows Errors
thumbnail: https://thmb.techidaily.com/97bffd7aabaab6ce88cfb81baf09f210aa957590abbc17524d40c38c29898fc2.jpg
---

## Fixing Windows 10/11: Driver Not Starting Error

 The “display driver failed to start” error message usually appears when you try to launch a game on Windows. The error message appears in the form of a Windows notification above the system tray area. When this error occurs, it causes your screen to go completely black. Sometimes it will recover, but sometimes it will require a hard reset.

 When this error is at its worst, it can prevent you from playing your favorite games. As such, here is how you can fix the “display driver failed to start” error on a Windows 10 or 11 PC.

## 1\. Perform Some Display Driver-Related Fixes

 The error message points to your display driver as the main culprit. As such, before you try anything else, you can try these display driver-related fixes to see if they do the job.

### Roll Back the Latest Graphics Driver Update
![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/roll-back-driver-button.jpg)

 If your graphics card’s driver has recently been updated, try rolling back to the old GPU driver. A**Roll Back Driver** option is usually only available for a short time (typically a few days) after updating a driver. Check out our guide to [rolling back drivers in Windows](https://www.makeuseof.com/how-to-roll-back-a-driver-in-windows-10/) for further details about how to apply this potential resolution.

### Install the Latest Driver for Your PC’s Graphics Card

 People plagued with this error message have confirmed that updating your graphics drivers is a good solution for the “display driver failed to start” error. And while Windows usually handles driver updates through Windows Update, it sometimes won't update NVIDIA and AMD GPU drivers.

 You can update your graphics card’s driver yourself with the methods discussed in our guide to [updating GPU drivers on Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/) .

### Reinstall Your Graphics Driver

 If your PC’s GPU already has the newest graphics driver available, consider reinstalling the graphics driver. It's best to do a clean install to ensure your GPU's driver is back to its factory defaults.

 Check out [how to cleanly install and reinstall GPU drivers on Windows](https://www.makeuseof.com/how-to-cleanly-install-and-reinstall-gpu-drivers-on-windows/) for more information.

## 2\. Utilize the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that can help resolve the “display driver failed to start” error. This troubleshooting tool is no longer available within Settings or Control Panel, but it is still accessible via Command Prompt.

 You can access and run the Hardware and Devices troubleshooting utility like this:

1. First, locate the Command Prompt by pressing**Win + S** , typing "cmd," and clicking on**Command Prompt** .
2. Enter and execute the Hardware and Devices command:  
`msdt.exe -id DeviceDiagnostic`
3. Click**Next** to start the troubleshooting.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/hardware-and-devices-troubleshooter-troubleshooter-2.jpg)
4. Select**Apply this fix** to rectify any issues Windows finds.

## 3\. Lower the Windows Visual Effect Settings

 Windows has various visual effect settings that can affect performance. Having too many visual effects enabled can potentially cause issues on PCs with more limited GPUs.

 So, it’s recommended to select the "adjust for best performance" mode in the visual effect settings like this:

1. Right-click**Start** , select**Search** , and input "advanced system settings" in the text box.
2. Press the**Settings** button in the**Performance** category.  
![The Advanced tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/advanced-tab-2.jpg)
3. Click the**Adjust for best performance** radio button, which will deselect most if not all of the effect checkboxes.  
![The "adjust for best performance" button selected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adjust-for-best-performance-radio-button.jpg)
4. Select**Apply** to set the new performance settings.
5. Click the Performance Options window’s**OK** button.

## 4\. Edit the GraphicsDrivers Registry Key

 Some users have got the “display driver failed to start” error fixed by editing the GraphicsDriver registry key. This tweaking involves adding a new**TdrDelay** DWORD value to that key for extending Timeout Detection Delay.

You can edit the GraphicsDriver registry key like this:

1. Open the Run dialog with**Win + R** and enter "regedit".
2. Click**OK** or press**Enter** to open the Registry Editor window.
3. Then enter this GraphicsDrivers key location inside the registry address bar:  
`HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\GraphicsDrivers`
4. Right-click**GraphicsDrivers** and select the**New** context menu option.
5. Select**DWORD (32-bit) Value** to add a new entry.  
![The New > DWORD options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/dword-32-bit-value-2.jpg)
6. Type**TdrDelay** within the new DWORD’s text box.
7. Double-click the**TdrDelay** DWORD.
8. Input a value of**5** in the data box and select**OK** .  
![The Value data box the TdrDelay](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/value-data-box-2.jpg)
9. Now close the Registry Editor and reboot your PC.

## 5\. Roll Back Windows to a Previous Restore Point
![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-restore-window.jpg)

 If you have System Restore enabled, restoring Windows to an earlier date is worth a try if nothing else has worked so far. Rolling back Windows will undo every system change made after a selected date.

 As such, you can use System Restore to put your PC "back in time" to a moment when the error didn't occur. It does mean you may lose some apps or data, so be sure to back up anything you want to keep.

 Our guide to [utilizing System Restore on Windows](https://www.makeuseof.com/use-system-restore-windows/) provides step-by-step instructions for how to roll back Windows 10 and 11\. Select a restore point date created before you needed to fix the “display driver failed to start” error.

 If this fixes the problem, be careful when re-installing the apps and drivers that got wiped during the restore. If you do, keep tabs on what you reinstalled and when. If the "display driver failed to start" error resurfaces, uninstall everything you recently reinstalled.

## 6\. Perform a Windows Factory Reset

 If System Restore is not an option or it doesn't resolve the issue, you can try a factory reset as the last resort. Performing a factory reset will likely fix the “display driver failed to start” error. However, factory resetting a PC deletes all the apps that weren't pre-installed with Windows. So, be prepared to reinstall all third-party apps you installed yourself.

![The Keep my Files option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/keep-my-files-option.jpg)

 You can apply a factory reset with the Reset this PC utility. That tool includes a**Keep my files** option you can select to keep files in your user folders (Documents, Pictures, Videos, etc). Our guide for [factory resetting Windows 10 and 11](http://www.makeuseof.com/tag/4-ways-factory-reset-windows-computer) provides details on how to access and utilize that tool.

## Enjoy Your Windows Gaming Again

 Applying those potential solutions will almost certainly be enough to fix the “display driver failed to start” error in most cases. However, you may need to try applying more than one of them to find one that works on your PC. Then you can get back to playing all your favorite Windows games again without further issues.


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
<li><a href="https://games-able.techidaily.com/1719170557511-prioritize-these-five-game-changing-mouse-features-today/"><u>Prioritize These Five Game-Changing Mouse Features Today</u></a></li>
<li><a href="https://games-able.techidaily.com/7-engrossing-terminal-challenges-to-try-today/"><u>7 Engrossing Terminal Challenges to Try Today</u></a></li>
<li><a href="https://games-able.techidaily.com/6-vital-game-components-that-grab-users-attention/"><u>6 Vital Game Components that Grab Users’ Attention</u></a></li>
<li><a href="https://games-able.techidaily.com/3-quick-fixes-for-recognizing-unplugged-headsets-on-xbox/"><u>3 Quick Fixes for Recognizing Unplugged Headsets on Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/5-ways-to-stop-steam-web-helper-from-using-all-your-ram/"><u>5 Ways to Stop Steam Web Helper From Using All Your RAM</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-definitive-guide-ios-screenshots-and-recording-2inas-2023/"><u>[New] 2024 Approved  The Definitive Guide  IOS Screenshots & Recording (2Inas 2023)</u></a></li>
<li><a href="https://games-able.techidaily.com/a-word-of-caution-for-those-attracted-to-linkedins-game-feature/"><u>A Word of Caution for Those Attracted to LinkedIn's Game Feature</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-video-conversion-wizardry-from-youtube-to-igtv/"><u>[New] Video Conversion Wizardry  From Youtube to IGTV</u></a></li>
<li><a href="https://games-able.techidaily.com/8-secrets-to-dominate-the-new-york-social-chess-game/"><u>8 Secrets to Dominate the New York Social Chess Game</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173588793-switch-online-troubles-lets-fix-it/"><u>Switch Online Troubles? Let's Fix It</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-overcome-nvidia-cp-access-denied-in-win1110/"><u>How to Overcome NVidia CP Access Denied in Win11/10</u></a></li>
<li><a href="https://games-able.techidaily.com/accessory-upgrades-transform-your-playtime/"><u>Accessory Upgrades Transform Your Playtime</u></a></li>
<li><a href="https://games-able.techidaily.com/5-missteps-that-thwart-gamefi-adoption-by-enthusiasts/"><u>5 Missteps That Thwart GameFi Adoption by Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/18-engaging-duet-conversations-texting-fun-hits-two/"><u>18 Engaging Duet Conversations: Texting Fun Hits Two!</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-age-for-gaming-the-mmo-evolution-tale/"><u>A New Age for Gaming: The MMO Evolution Tale</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170010590-unleash-the-potential-of-big-box-arcade-cabinetry/"><u>Unleash the Potential of Big Box Arcade Cabinetry</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-editors-dream-becomes-reality-a-close-look-at-vida/"><u>2024 Approved  The Editor's Dream Becomes Reality  A Close Look at Vida</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-resolve-infinix-smart-8-pro-screen-not-working-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Resolve Infinix Smart 8 Pro Screen Not Working | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166384648-maximizing-your-budget-these-are-the-best-1440p-monitors/"><u>Maximizing Your Budget? These Are the Best 1440P Monitors!</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-read-on-to-learn-about-multi-object-tracking-its-types-and-requirements-youll-also-learn-about-the-different-approaches-toward-object-tracking/"><u>New Read on to Learn About Multi Object Tracking, Its Types, and Requirements. Youll Also Learn About the Different Approaches Toward Object Tracking</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-the-ultimate-guide-to-video-editors-for-windows-11-free-paid-and-in-between/"><u>Updated 2024 Approved The Ultimate Guide to Video Editors for Windows 11 Free, Paid, and In-Between</u></a></li>
<li><a href="https://games-able.techidaily.com/a-step-by-step-approach-to-identifying-excellent-discs/"><u>A Step-by-Step Approach to Identifying Excellent Discs</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-authoritative-picks-top-10-apps-to-watch-football-games-anytime-anywhere/"><u>[New] In 2024, Authoritative Picks  Top 10 Apps to Watch Football Games Anytime, Anywhere</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-view-on-gaming-computing-debunking-six-apple-misconceptions/"><u>A New View on Gaming Computing: Debunking Six Apple Misconceptions</u></a></li>
<li><a href="https://games-able.techidaily.com/1719173196069-bigger-frames-better-experiences-in-gaming/"><u>Bigger Frames, Better Experiences in Gaming!</u></a></li>
<li><a href="https://games-able.techidaily.com/achieving-optimal-ps5-security-through-passcode-settings/"><u>Achieving Optimal PS5 Security Through Passcode Settings</u></a></li>
<li><a href="https://games-able.techidaily.com/6-addictive-features-of-mobile-games-you-should-watch-out-for/"><u>6 Addictive Features of Mobile Games You Should Watch Out For</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-average-playback-period-in-high-res-20mb-content/"><u>2024 Approved  Average Playback Period in High-Res 20MB Content</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/mastering-facebook-live-your-complete-guide-to-successful-streaming/"><u>Mastering Facebook Live Your Complete Guide to Successful Streaming</u></a></li>
<li><a href="https://games-able.techidaily.com/8-features-that-make-microsoft-edge-the-best-gaming-browser/"><u>8 Features That Make Microsoft Edge the Best Gaming Browser</u></a></li>
<li><a href="https://games-able.techidaily.com/1719170311058-legal-aspects-related-to-copyright-licensing-and-intellectual-property-rights-concerning-street-maps-and-symbolic-representations/"><u>Legal Aspects Related to Copyright, Licensing, and Intellectual Property Rights Concerning Street Maps and Symbolic Representations;</u></a></li>
<li><a href="https://games-able.techidaily.com/achieving-persistent-ps5-network-links/"><u>Achieving Persistent PS5 Network Links</u></a></li>
<li><a href="https://games-able.techidaily.com/1719169813163-elevate-gbadvance-titles-on-your-ios-device/"><u>Elevate GBAdvance Titles on Your iOS Device!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-infinix-gt-10-pro-phone-with-broken-screen-by-drfone-android/"><u>In 2024, How to Unlock Infinix GT 10 Pro Phone with Broken Screen</u></a></li>
<li><a href="https://games-able.techidaily.com/20-ways-to-improve-gaming-performance-on-your-laptop/"><u>20 Ways to Improve Gaming Performance on Your Laptop</u></a></li>
<li><a href="https://games-able.techidaily.com/adaptive-thermal-control-curve-for-high-end-gpus/"><u>Adaptive Thermal Control Curve for High-End GPUs</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-7-key-strategies-for-perfect-macro-video-shooting/"><u>[New] 7 Key Strategies for Perfect Macro Video Shooting</u></a></li>
<li><a href="https://games-able.techidaily.com/1719171391975-optimize-arcade-excitement-choose-wide-front-panels/"><u>Optimize Arcade Excitement - Choose Wide Front Panels!</u></a></li>
<li><a href="https://games-able.techidaily.com/9-reasons-why-all-gamers-should-use-steam/"><u>9 Reasons Why All Gamers Should Use Steam</u></a></li>
<li><a href="https://games-able.techidaily.com/achieve-seamless-gaming-experience-on-steam-by-clearing-titles/"><u>Achieve Seamless Gaming Experience on Steam by Clearing Titles</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-xiaomi-13t-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Xiaomi 13T?</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-navigating-the-needle-speed-of-videos-in-snapchat-for-2024/"><u>[New] Navigating the Needle-Speed of Videos in Snapchat for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/1719167009807-google-play-pass-generally-fantastic-except/"><u>Google Play Pass: Generally Fantastic Except</u></a></li>
<li><a href="https://games-able.techidaily.com/addressing-display-hang-up-eradicating-dxgierror-0x887a0006-in-win1111/"><u>Addressing Display Hang-Up - Eradicating DXGI_ERROR 0X887A0006 in Win11/11</u></a></li>
<li><a href="https://games-able.techidaily.com/6-best-games-offering-fee-free-experience/"><u>6 Best Games Offering Fee-Free Experience</u></a></li>
<li><a href="https://games-able.techidaily.com/a-closer-look-at-mobilitys-flaws-in-playing/"><u>A Closer Look at Mobility's Flaws in Playing</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-xiaomi-13t-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Xiaomi 13T Bricked Devices | Dr.fone</u></a></li>
</ul></div>

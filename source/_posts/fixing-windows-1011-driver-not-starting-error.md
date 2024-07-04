---
title: "Fixing Windows 10/11: Driver Not Starting Error"
date: 2024-06-25T13:12:03.745Z
updated: 2024-06-26T13:12:03.745Z
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

### Roll Back the Latest Graphics Driver Update ![The Roll Back Driver option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/roll-back-driver-button.jpg)

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

## 5\. Roll Back Windows to a Previous Restore Point ![The System Restore window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/system-restore-window.jpg)

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
<li><a href="https://games-able.techidaily.com/overcome-noisy-controller-revive-headset-connection/"><u>Overcome Noisy Controller: Revive Headset Connection</u></a></li>
<li><a href="https://games-able.techidaily.com/tailor-your-tech-for-peak-performance-personalizing-series-sxs-refresh-rate/"><u>Tailor Your Tech for Peak Performance: Personalizing Series S/X's Refresh Rate</u></a></li>
<li><a href="https://games-able.techidaily.com/gaming-giants-collide-ps5-vs-xbox-series-x-battle/"><u>Gaming Giants Collide - PS5 V/S Xbox Series X Battle</u></a></li>
<li><a href="https://games-able.techidaily.com/fix-or-replace-xbox-sx-troubleshooting-guide/"><u>Fix or Replace? Xbox S/X Troubleshooting Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/decoding-ea-play-value-for-your-dollar/"><u>Decoding EA Play: Value for Your Dollar</u></a></li>
<li><a href="https://games-able.techidaily.com/discover-the-best-free-gaming-without-investments/"><u>Discover the Best Free Gaming without Investments</u></a></li>
<li><a href="https://games-able.techidaily.com/unleashing-superior-joy-cons-the-ultimate-guide-to-2024/"><u>Unleashing Superior Joy-Cons: The Ultimate Guide to 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-patchwork-pros-how-to-assemble-engaging-tiktoks/"><u>2024 Approved  Patchwork Pros  How to Assemble Engaging TikToks</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-a18-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from A18.</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-crafting-excellence-in-instagram-grids-with-these-elite-tools/"><u>[Updated] In 2024, Crafting Excellence in Instagram Grids with These Elite Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-how-to-safely-archive-chats-and-calls-from-whatsapp-for-2024/"><u>[New] How to Safely Archive Chats and Calls From WhatsApp for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-income-from-video-how-to-profit-on-vimeo-platform/"><u>[Updated] 2024 Approved  Income From Video  How to Profit on Vimeo Platform</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/about-xiaomi-frp-bypass-by-drfone-android/"><u>About Xiaomi FRP Bypass</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-best-5-animated-emblems-for-modern-social-networks/"><u>2024 Approved  Best 5 Animated Emblems for Modern Social Networks</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-brightening-filmmaking-ranking-the-17-best-lights/"><u>In 2024, Brightening Filmmaking  Ranking the 17 Best Lights</u></a></li>
</ul></div>

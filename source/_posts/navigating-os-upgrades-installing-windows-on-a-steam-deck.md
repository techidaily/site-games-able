---
title: "Navigating OS Upgrades: Installing Windows on a Steam Deck"
date: 2024-08-31T19:32:31.036Z
updated: 2024-09-01T19:32:31.036Z
tags:
  - games
categories:
  - games
description: "This Article Describes Navigating OS Upgrades: Installing Windows on a Steam Deck"
excerpt: "This Article Describes Navigating OS Upgrades: Installing Windows on a Steam Deck"
keywords: WinOS Steam Deck Update,Steam Deck Windows Instal,OS Upgrade Steam Gaming,Steam Deck XP Installation,Windows on Steam Handheld,Steam Deck Boot Windows,Upgrading to WinOS Steam
thumbnail: https://thmb.techidaily.com/91dc46c6cc6911e9915591791566cdaadd16613fc33817ba0857c51273b662cd.JPG
---

## Navigating OS Upgrades: Installing Windows on a Steam Deck

### Quick Links

* [Why You Should Install Windows on Your Steam Deck](#why-you-should-install-windows-on-your-steam-deck)
* [What You Need to Install Windows on Your Steam Deck](#what-you-need-to-install-windows-on-your-steam-deck)
* [How to Install Windows on Your Steam Deck](#how-to-install-windows-on-your-steam-deck)
* [Potential Issues and Solutions While Installing Windows on Your Steam Deck](#potential-issues-and-solutions-while-installing-windows-on-your-steam-deck)

### Key Takeaways

* Installing Windows on your Steam Deck allows you to access a familiar operating system and use the device as a work laptop or desktop replacement.
* To install Windows on your Steam Deck, you need a USB flash drive or SD card, Ventoy software, a GParted ISO, and a Windows 11 ISO.
* Follow our step-by-step guide to install Ventoy, partition your SSD, install Windows 11, and then install Windows drivers for proper functionality on your Steam Deck.

 Do you want to have a familiar operating system or Game Pass on your Steam Deck? You can dual-boot SteamOS with Windows on the device. Here’s a thorough guide on installing Windows 11 on your Steam Deck.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Why You Should Install Windows on Your Steam Deck

![Steam Deck surrounded by peripherals](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2024/01/steam-deck-surrounded-by-peripherals.JPG)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
Jhet Borja/MUO

 If you’re someone who owns a PC, the chances are very high that you’re running Windows on it. Windows is familiar to many and is fairly easy to use.

 While not having a mouse and keyboard on your Steam Deck will pose some navigation issues, having an operating system that’s familiar to you and that you know how to use might be worth that sacrifice.

 Having Windows on your Steam Deck can also make it a work laptop or desktop replacement. You can easily use Photoshop, Microsoft Office apps, Lightroom, and all the usual suspects on Windows—so long as you’re willing to bring around a mouse and keyboard. Thankfully, there are plenty of[Steam Deck accessories](https://www.makeuseof.com/essential-steam-deck-accessories/) that can make doing real work on it a breeze.

## What You Need to Install Windows on Your Steam Deck

 You only need a few things to install Windows on your Steam Deck, most of which are software. But you will need a few hardware accessories as well.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
### Hardware

 For hardware, you really only need a USB flash drive and a USB-C hub to plug it into your Steam Deck. You can also[install an SD card on your Steam Deck](https://www.makeuseof.com/how-to-install-steam-deck-sd-card/) as long as it's decently fast. A USB 3.0 or higher flash drive or a UHS-I or higher SD card would suffice, but we wouldn’t suggest anything slower.

 We also highly suggest using a separate PC as we've done in this guide, but you can also use your Steam Deck and follow similar steps using the Linux version of Ventoy.

### Ventoy

 The first piece of software is Ventoy, a program that allows you to boot multiple ISOs from one external storage device without needing to format it to add a different ISO. This will avoid the back-and-forth formatting of the storage device used, making it easier to go back in case you make a mistake along the way.

![Ventoy Windows zip file from GitHub](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-windows-zip-file-from-github.jpg)

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Head to[Ventoy’s GitHub page](https://github.com/ventoy/Ventoy/) and on the right side, click on**Releases** . Scroll down to**Assets** and click on the ZIP folder that says Windows on it. Extract the contents into a folder on your PC.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### GNOME Partition Editor (GParted) ISO

![downloading GParted amd64 version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-gparted-amd64-version.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
 GParted is an ISO used to create partitions on your internal SSD on your Steam Deck. The new partition will be where you’ll place the Windows installation. To download it, head to[GParted.org](https://gparted.org/download.php) and click on the**amd64.iso** download file.

### Windows 11 ISO

 To put Windows onto your Steam Deck, you’ll of course need the installer. You can easily find this on[Microsoft’s Windows 11 page](https://www.microsoft.com/en-ca/software-download/windows11) .

![Downloading Windows 11 ISO from Microsoft](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-11-iso-from-microsoft.jpg)

 Head to the**Download Windows 11 Disk Image (ISO)** option and on the dropdown menu, select**Windows 11 (multi-edition ISO)** . Click on**Download** , then select your language. It should then give you another download button to download the Windows ISO that is about 6GB to 7GB in size.

### Windows Drivers for Steam Deck

![Downloading Windows Drivers for Steam Deck](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/downloading-windows-drivers-for-steam-deck.jpg)

 Windows doesn’t support all the Steam Deck’s hardware straight from the get-go. Fortunately, Steam has provided Windows drivers so that your audio, Wi-Fi, Bluetooth, SD card reader, and APU are all working properly.

 You can find and download the Windows drivers for your Steam Deck on the[Steam Deck Windows Resources support page](https://help.steampowered.com/en/faqs/view/6121-ECCD-D643-BAA8) . Extract all of them into a single folder so that you can paste it onto your SD card or flash drive later.

## How to Install Windows on Your Steam Deck

 If you’ve got your flash drive or SD card ready with all the software downloaded, you can now start turning your Steam Deck into a Windows experience. In our case, we’ll be using an SD card so that we don’t need to deal with a USB hub or a dock.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
### 1\. Install Ventoy on Your Flash Drive or SD Card

 To be able to run both the GParted and the Windows 11 ISOs from one SD card without needing to format it multiple times, you’ll need to use Ventoy. This will make things way more convenient.

![Run Ventoy2Disk from extracted folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/run-ventoy2disk-from-extracted-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 To install Ventoy on your flash drive or SD card, you’ll want to plug it into your PC and open the Ventoy folder you extracted earlier. Then click on**Ventoy2Disk.exe** .

![Selected SD card to install Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selected-sd-card-to-install-ventoy.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
 You’ll then select the storage device you want to store Ventoy on. In our case, it’s the 32GB SD card. Click**Install** .

![Ventoy Drive with all ISOs and Windows Drivers inside](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/ventoy-drive-with-all-isos-and-windows-drivers-inside.jpg)

 Now that Ventoy is installed, copy over GParted, the Windows 11 ISO, and a folder containing the Windows drivers for the Steam Deck. You can now insert the SD card into the Steam Deck.

### 2\. Enter the Steam Deck Boot Manager

 Next, you’ll need to boot from the SD card or flash drive you’ve connected to the Steam Deck using the device's boot manager.

![Volume down and power button to enter Steam Deck boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/volume-down-and-power-button-to-enter-steam-deck-boot-manager.JPG)

Jhet Borja/MUO

 To do this, shut down your Steam Deck first. Once it’s off, hold down the volume down button and power button until you hear a chime. Once you hear the chime, let go of the power button, but keep holding down the volume down button until the boot manager shows, like in the image below.

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Jhet Borja/MUO

 If you hold down the power button after the chime, you’ll most likely end up turning your Steam Deck off again.

 Once you’re in the boot manager, select the SD card or flash drive. This should show Ventoy and both the Windows and GParted ISOs.

### 3\. Use GParted to Partition Your Internal SSD

 You'll now need to partition your Steam Deck's SSD. If you don't, you most likely won't be able to install Windows 11 on the /home partition, and you'll also end up wiping SteamOS from your drive.

 If you want just Windows on your Steam Deck, you can also use Ventoy to wipe all partitions and either leave the combined partition as unallocated or format it as NTFS. We don't suggest this, however, as SteamOS really is the best way to experience the Steam Deck. It's better to have the option to switch between the two than be stuck with just Windows.

![GParted ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/gparted-iso-on-ventoy.JPG)

Jhet Borja/MUO

 On Ventoy, select GParted to run it. You can run it in normal mode, but if that doesn’t work, grub2 might do it.

![Enter GParted Live first option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enter-gparted-live-first-option.JPG)

Jhet Borja/MUO

 Once GParted is open, you’ll be greeted with a few things before you can get to partitioning. Firstly, you’ll need to select the settings. Pick the first one—**GParted Live (Default Settings)** .

![GParted Don't touch keymap option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/gparted-don-t-touch-keymap-option.JPG)

 Next, select**Don’t touch keymap** and then select your language. If you’re just going to use English, we suggest just pressing A on the Steam Deck until you reach the main screen.

![Selecting Steam Deck SSD in GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steam-deck-ssd-in-gparted.JPG)

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Jhet Borja/MUO

 Finally, you’re ready to partition your SSD. By this point, you can plug in your mouse and keyboard to make it easier to navigate. If your SD card or flash drive is the only thing you can see, switch it to your SSD on the upper right drop-down menu.

![Resizing home partition on Steam Deck SSD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/resizing-home-partition-on-steam-deck-ssd.JPG)

Jhet Borja/MUO

 To partition your SSD, right-click (left trigger) on the**/home** partition or the largest partition on the SSD. Click on**Resize/Move** and move the right wall to the left, leaving the empty space as a new unallocated partition.

 In our case, we’re leaving around 250 GB or about 250,000 MiB for Windows 11\. Click on the**Resize/Move** button on the bottom right to make your changes.

![Unallocated partition on GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/unallocated-partition-on-gparted.JPG)

Jhet Borja/MUO

 Finally, click on the**green check mark** in the toolbar. Forgetting to do this will not apply your partition changes.

 The software will then process the new partition sizes, which may take a few minutes depending on how big your SSD is. Once it’s done, you can now press the power button to exit GParted and power down.

<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 4\. Windows 11 Setup on the Steam Deck

 Now you're ready to install Windows on your Steam Deck. Before you go to the boot manager though, unplug any other USB devices you used earlier except the flash drive. This prevents the ISOs or Ventoy from malfunctioning.

![Windows 11 ISO on Ventoy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-11-iso-on-ventoy.JPG)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
Jhet Borja/MUO

 Go back to the boot manager (with the volume down button and the power button) and select the SD card or flash drive once again. With Ventoy open, this time select the Windows 11 ISO.

![I don't have a product key option during Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/i-don-t-have-a-product-key-windows-11-setup.JPG)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
Jhet Borja/MUO

 Just follow the setup by choosing the right language and keyboard layout until you reach the Windows key section. There, you can safely choose**I don’t have a product key** if you don’t have one.

![Entering partition size Windows 11 setup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/entering-partition-size-windows-11-setup.JPG)

Jhet Borja/MUO

 Proceed until you reach the**Where do you want to install Windows?** screen. You’ll want to scroll to the very bottom and click the drive that says**Unallocated space** . Next, click**New,** and it’ll automatically add the right size for you. So just click**Apply** .

 It will then start installing Windows onto that partition. Once Windows 11 is installed, you’ll have to go through another setup process.

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
### 5\. Install the Windows Drivers for the Steam Deck

 Once you’ve installed Windows, you can now install the drivers for your Steam Deck.

![Windows Drivers from Steam](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-drivers-from-steam.png)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
 To do this, open up your File Explorer and click on the Ventoy drive. Open the folder we told you to place the Steam Deck drivers inside and start with any one of them.

 If you’re prompted to restart, don’t do it yet. You can restart once you’ve installed all the drivers to make it easier.

![Installing Steam Deck audio driver part 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/installing-steam-deck-audio-driver-part-1.png)

 Proceed to click on**Install** for the other drivers, but you may find that the audio drivers do not have an executable. To install the two audio drivers, simply right-click (left trigger) on the file that says**Setup information** and click**Install** .

 Once they’re all installed, you can now restart your Steam Deck. If things didn’t go so smoothly, you can refer to the section below to find your issue and the solution for it.

## Potential Issues and Solutions While Installing Windows on Your Steam Deck

 We’ve compiled a few issues that we came across during our installation and found solutions to them so that you don’t have to scour the internet to find fixes.

### ISOs Show a Black Screen or Don't Boot Up

 If the ISOs aren’t working properly, just press the power button once to exit and shut down. This is most likely due to other USB devices plugged into your Steam Deck like a keyboard and mouse. This is why we used an SD card in our installation. Remove all USB devices except your flash drive or use a USB-C flash drive if possible.

 If this doesn’t work, you may also try to delete the other ISO from the SD card or flash drive. You may also try reinstalling Ventoy as a last resort, but this will format the drive so make sure you have everything in a folder that you can easily paste onto the drive.

### The Windows 0x80300001 Error

![Selecting partition created in GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-partition-created-in-gparted.JPG)

Jhet Borja/MUO

 This error will most likely pop up because the partition you want to install Windows on isn’t in NTFS format or a blank unallocated partition.

![Wrong ext4 partition format for Windows on GParted](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/wrong-ext4-partition-format-for-windows-on-gparted.JPG)

Jhet Borja/MUO

 You may have created a new partition as ext4 in GParted instead of leaving the unallocated partition as it is. If you insist on creating a new partition in GParted, make sure it’s in NTFS format and not ext4.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Windows Cannot Install Drivers

![Windows cannot install required files error](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/windows-cannot-install-required-files-error.JPG)

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
Jhet Borja/MUO

 If you’re near the end of your Windows installation and it suddenly says it cannot install drivers, other USB devices may be interfering with the installation.

 Shut down your Steam Deck by holding down the power button and unplug any USB devices except your flash drive or SD card. Don’t plug in any USB devices during the installation to avoid this issue.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
### You Can’t Find SteamOS in the Boot Manager

![No SteamOS option in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/no-steamos-option-in-boot-manager.JPG)

Jhet Borja/MUO

 If you want to go back to SteamOS and can’t find it in the boot manager, you should shut down your Steam Deck and go to the BIOS instead.

 To enter the BIOS, hold down the volume up button and the power button until you hear the chime. Let go of the power button but hold down the volume up button until you enter the BIOS.

![Selecting steamcl.efi in Steam Deck BIOS to boot into SteamOS](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/selecting-steamcl-efi-in-steam-deck-bios-to-boot-into-steamos.JPG)

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Jhet Borja/MakeUseOf

 Once you’re in the BIOS, select **Boot from file > eps > efi > steamos > steamcl.efi** . This should boot you back into SteamOS.

 Now that you’re in SteamOS, you can put it back onto the boot manager by entering desktop mode.

![Konsole command to make SteamOS appear in boot manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/konsole-command-to-make-steamos-appear-in-boot-manager-1.JPG)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 On desktop mode, click on the Steam Deck icon on the bottom left and open Konsole. You can search for it by bringing up the keyboard by clicking on the text box and pressing on the Steam button + X.

Then type:

`sudo efibootmgr -c -L "SteamOS" -l "\EFI\steamos\steamcl.efi" -d /dev/nvme0n1p1`

![Steam Deck user password](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/steam-deck-user-password.jpg)

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In case you don’t have a sudo account and can’t add the command, go to**Settings > Users** then assign a username and password. You can then try adding the same command in Konsole and adding your password after pressing Enter. It will then show your boot options.

 If you can see steamcl.efi with an asterisk next to its boot order number, it means that it’s in your boot manager now. You can verify it by shutting your Steam Deck down and entering the boot manager.

### Steam Deck Navigation and Controls on Windows

 If you’re having a hard time with the Steam Deck controls on Windows and want to use the controls like on SteamOS, download Steam and have it open.

![Enabling Steam Input for Xbox Controllers](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2024/01/enabling-steam-input-for-xbox-controllers.jpg)

 Then go to **Steam > Settings > Controller > Enable Steam Input for Xbox Controllers** . You should then be able to use both trackpads like on SteamOS. You may also configure it by scrolling down and editing it on the**Non-game controller layouts** .

 The Steam Deck is a very versatile device as it’s not just a full-on gaming device, but also a full-on PC. Installing Windows on it will allow you to use it similarly to your desktop PC for regular writing work, but also for more intensive work like video and photo editing.

 We hope this guide has helped you figure out how to install Windows on your Steam Deck and fix some of the issues you might face while doing so.


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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-new-best-facebook-story-savers-for-free-extensiononlinemobile-apps/"><u>[New] 2024 Approved  NEW Best Facebook Story Savers for FREE [Extension/Online/Mobile Apps]</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-premium-chromebook-capture-app/"><u>[New] 2024 Approved  Premium Chromebook Capture App</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-revolutionize-your-social-media-game-personalizing-twitter-video-images/"><u>[New] In 2024, Revolutionize Your Social Media Game  Personalizing Twitter Video Images</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-wallet-friendly-microphones-for-social-media-stars/"><u>[Updated] Wallet-Friendly Microphones for Social Media Stars</u></a></li>
<li><a href="https://games-able.techidaily.com/499-for-virtual-thrills-mozas-full-package/"><u>$499 for Virtual Thrills - MOZA's Full Package</u></a></li>
<li><a href="https://games-able.techidaily.com/499-moza-r5-your-gateway-to-realistic-racing/"><u>$499 MOZA R5 - Your Gateway to Realistic Racing</u></a></li>
<li><a href="https://games-able.techidaily.com/11-must-try-free-word-game-apps-for-both-sides/"><u>11 Must-Try Free Word Game Apps for Both Sides</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-boosting-your-videos-chance-on-vimeo-staff-list/"><u>2024 Approved  Boosting Your Video's Chance on Vimeo Staff List</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-enhance-your-video-impact-with-slow-motion-on-ig/"><u>2024 Approved  Enhance Your Video Impact with Slow Motion on IG</u></a></li>
<li><a href="https://games-able.techidaily.com/6-subtle-steps-to-cut-costs-using-xbox/"><u>6 Subtle Steps to Cut Costs Using Xbox</u></a></li>
<li><a href="https://games-able.techidaily.com/a-comprehensible-guide-for-itchios-great-gaming-finds/"><u>A Comprehensible Guide for Itch.io’s Great Gaming Finds</u></a></li>
<li><a href="https://games-able.techidaily.com/a-guide-to-buying-fortnite-coins-on-ps5/"><u>A Guide to Buying Fortnite Coins on PS5</u></a></li>
<li><a href="https://games-able.techidaily.com/a-new-era-of-gaming-ps5-or-xbox-series-x/"><u>A New Era of Gaming: PS5 or Xbox Series X?</u></a></li>
<li><a href="https://games-able.techidaily.com/achievement-arenas-champion-clusters/"><u>Achievement Arenas: Champion Clusters</u></a></li>
<li><a href="https://games-able.techidaily.com/acquiring-googles-console-style-gaming-experience-for-computer-use/"><u>Acquiring Google's Console-Style Gaming Experience for Computer Use</u></a></li>
<li><a href="https://games-able.techidaily.com/adapting-sonys-console-to-pc-gaming-with-ease/"><u>Adapting Sony's Console to PC Gaming with Ease</u></a></li>
<li><a href="https://games-able.techidaily.com/advantages-to-late-game-debuts/"><u>Advantages to Late Game Debuts</u></a></li>
<li><a href="https://games-able.techidaily.com/akkos-mod007b-keyboard-elevating-gaming-performance/"><u>Akko's MOD007B Keyboard - Elevating Gaming Performance</u></a></li>
<li><a href="https://games-able.techidaily.com/algorithmic-realities-in-the-world-of-gaming/"><u>Algorithmic Realities in the World of Gaming</u></a></li>
<li><a href="https://games-able.techidaily.com/apex-of-pc-gaming-raider-ge78-review-highlights/"><u>Apex of PC Gaming: Raider GE78 Review Highlights</u></a></li>
<li><a href="https://games-able.techidaily.com/are-macs-the-future-of-pc-gaming/"><u>Are Macs the Future of PC Gaming?</u></a></li>
<li><a href="https://games-able.techidaily.com/avoid-closing-outdated-windows-fix-load-errors/"><u>Avoid Closing Outdated Windows - Fix Load Errors</u></a></li>
<li><a href="https://games-able.techidaily.com/avoiding-robloxs-low-memory-warnings-tips-for-iphones/"><u>Avoiding Roblox's Low-Memory Warnings: Tips for iPhones</u></a></li>
<li><a href="https://games-able.techidaily.com/1719167760189-baldurs-gate-3-download-path-unveiled/"><u>Baldur's Gate 3: Download Path Unveiled</u></a></li>
<li><a href="https://games-able.techidaily.com/bargain-hunting-done-right-affordable-mothers-for-gaming-enthusiasts/"><u>Bargain Hunting Done Right: Affordable Mothers for Gaming Enthusiasts</u></a></li>
<li><a href="https://games-able.techidaily.com/beat-steam-web-helpers-ram-habits-with-these-five-methods/"><u>Beat Steam Web Helper's RAM Habits with These Five Methods</u></a></li>
<li><a href="https://games-able.techidaily.com/become-a-pro-at-mobile-gaming-learn-button-controls/"><u>Become a Pro at Mobile Gaming: Learn Button Controls</u></a></li>
<li><a href="https://games-able.techidaily.com/before-launch-gamers-dilemma-explored/"><u>Before Launch: Gamers' Dilemma Explored</u></a></li>
<li><a href="https://games-able.techidaily.com/best-online-shooters-a-comprehensive-list-of-browser-based-games/"><u>Best Online Shooters: A Comprehensive List of Browser-Based Games</u></a></li>
<li><a href="https://games-able.techidaily.com/1719168571839-champion-mousepads-reviewed/"><u>Champion Mousepads Reviewed!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164851824-champions-blueprint-managing-soccer-legends-at-no-cost/"><u>Champion's Blueprint: Managing Soccer Legends at No Cost</u></a></li>
<li><a href="https://techtrends.techidaily.com/explore-the-elite-rankings-of-ups-units-for-enhanced-reliability-in-2-the-best-ups-systems-to-secure-your-devices/"><u>Explore the Elite Rankings of UPS Units for Enhanced Reliability in 2 # The Best UPS Systems to Secure Your Devices</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/free-msnbc-live-online-stream-for-the-latest-shows-for-all-devices/"><u>Free MSNBC Live Online Stream for the Latest Shows for All Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/1719164863987-gamers-discover-the-future-oled-monitors/"><u>Gamers, Discover the Future - OLED Monitors!</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-iphone-xs-max-by-drfone-ios/"><u>How Do You Remove Restricted Mode on iPhone XS Max</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-a05s-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy A05s If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-overcome-stutter-and-freezes-during-your-playthrough-of-phoenix-point/"><u>How to Overcome Stutter and Freezes During Your Playthrough of Phoenix Point?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-inside-the-score-understanding-aspect-ratios-for-video-success/"><u>In 2024, Inside The Score  Understanding ASPECT RATIOS for Video Success</u></a></li>
<li><a href="https://games-able.techidaily.com/1719157494661-score-big-on-ps-games-during-summer-clearance/"><u>Score Big on PS Games During Summer Clearance!</u></a></li>
<li><a href="https://games-able.techidaily.com/1719172605573-step-up-your-game-designs-with-wide-cabinetry-options/"><u>Step Up Your Game Designs with Wide Cabinetry Options</u></a></li>
<li><a href="https://win11.techidaily.com/the-stealth-attacker-uncovered-defending-windows-against-wacatacbml/"><u>The Stealth Attacker Uncovered: Defending Windows Against Wacatac.B!ml</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/ultimate-selection-the-finest-raspberry-pi-cases-for-2n45s/"><u>Ultimate Selection: The Finest Raspberry Pi Cases for 2N45s</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-avi-video-rotation-made-easy-16-best-free-solutions-for-all-devices/"><u>Updated In 2024, AVI Video Rotation Made Easy 16 Best Free Solutions for All Devices</u></a></li>
</ul></div>

---
title: Determining Hardware's Graphic Memory
date: 2024-09-12T16:20:17.110Z
updated: 2024-09-15T16:09:45.271Z
tags:
  - games
categories:
  - games
description: This Article Describes Determining Hardware's Graphic Memory
excerpt: This Article Describes Determining Hardware's Graphic Memory
keywords: Hardware Graphics RAM,GPU Memory Evaluation,PC Visual Storage Size,Graphics Card Memory Capacity,Rendering Device Memory,System Pixel Cache Size,Graphics Memory Assessment
thumbnail: https://thmb.techidaily.com/9333e7c75e292a0b83b1e16b6df5d6742dede6cee3e1ad9fc6da9c95dfc95571.jpg
---

## Determining Hardware's Graphic Memory

 With plenty of options, buying a computer can be quite a task these days. There are multiple configurations for pretty much every computer you come across, so knowing what specs you want or currently have can save you a buck when you decide to get a new computer or upgrade your existing one.

 If you're a gamer or content creator, having the right amount of VRAM will make a huge difference to your experience. Thankfully, regardless of your operating system, there are plenty of options to find out how much VRAM you have.

## How to Check VRAM on Windows

 Since just about every gamer and a number of content creators prefer using Windows, there are several tools that can give you varying amounts of information on how much VRAM your computer has.

### Using Windows Settings

 The simplest way of finding out how much VRAM you have is to go through your Windows Settings.

1. Open Windows Settings and click the**Display** heading under the**System** tab.
2. Click**Advanced Display** under**Related settings** .  
![Windows Settings screenshot showing advanced options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-settings-check-vram-1.jpg)
3. Finally, click**Display adapter properties for Display 1** .  
![Screenshot showing VRAM in Windows settings.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-settings-check-vram-2.jpg)

 If you've got more than one GPU in your system (one discrete and one integrated) or multiple displays, you might want to check the others as well to make sure you're seeing the right type of VRAM.

 Also, remember that while this is one of the simplest methods of looking up your VRAM, it doesn't give you a lot of information, and if you're using a laptop, it will only show the integrated GPU's VRAM here. If you'd like to know more about your computer's VRAM without downloading an external tool, the DirectX Diagnostic Tool is a better option.

### Using the DirectX Diagnostic Tool

 As the name suggests, the DirectX Diagnostic Tool gives you information about your system and the GPUs installed in more detail so you can try and figure out what's wrong with your computer.

 However, that's not all you can use it for. The tool is also handy if you need to look up a computer's specifications, especially VRAM. Here's how.

1. Press**Windows key + R** to open the**Run** prompt. Type**dxdiag** and press Enter.
2. Head over to the**Display** tab, and you'll see your GPU's name, the amount of VRAM, and other basic information.  
![Screenshot of the dxdiag tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/dxdiag-screenshot.jpg)

 Once again, remember that if you have multiple GPUs or displays, you'll see multiple Display tabs here. This is especially true in the case of laptops, where you might see an additional**Render** tab that will show you the VRAM and other information of your dedicated GPU.

### Using Third-Party Tools

 Last but not least, if the in-built Windows tools don't give you enough information or don't work for whatever reason, you can always default to third-party tools that are readily available, safe to use, and will give you a host of information on just about every component of your computer, including GPU and VRAM.

![Screenshot showing OpenHardwareMonitor tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/openhardwaremonitor-screenshot.jpg)

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Tools like [GPU-Z](https://www.techpowerup.com/gpuz/) ,[CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) , and [OpenHardwareMonitor](https://openhardwaremonitor.org/downloads/) are your best friends here. These are lightweight utilities that won't stress your system when running in the background while also providing a lot of information on how specific components function.

## How to Check VRAM on Linux

 If you're on Linux, there are a bunch of command-line tools you can use to quickly look up what GPU and how much VRAM your computer has. A quick way of doing this is by using the`lshw` command as follows.

`sudo lshw -C display  
  
`

![Linux lshw tool showing GPU information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/linux-vram-screenshot.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135394/19272" target="_top" id="2135394">
  <img src="//a.impactradius-go.com/display-ad/19272-2135394" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135394/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Alternatively, you can also use the`nvtop` or`radeontop` tools for Nvidia and AMD GPUs, respectively, if you'd like more information. These also include graphs of how your GPU is being used in real time. You can install these tools by using the following commands:

`## For installing nvtop  
sudo apt-get install nvtop  
  
## For installing radeontop  

sudo apt-get install radeontop`

 Once the installation is complete, you can run the tools by typing`sudo nvtop` or`sudo radeontop` depending on which one you installed.

<!-- affiliate ads begin -->
<span id="1977004">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977004.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977004">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977004.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977004%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977004/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Check VRAM on macOS

 Just like the two aforementioned operating systems, macOS also has tools that you can use to find out how much VRAM your computer has. Just follow these steps.

1. Click the Apple logo in the top left of your screen, followed by the**About This Mac** option.
2. In the**Overview** tab, you should see how much VRAM your Mac has next to**Graphics** .

 Do keep in mind that this method only works on Intel-based Macs. If your Mac is powered by an M1 or M2 chip, it's not possible to see how much VRAM you have, as both the CPU and GPU are baked onto one chip.

## Why Is Knowing Your VRAM Important?

 As mentioned before, if you're a gamer or content creator, having enough VRAM on hand is very important. Without enough VRAM, you might struggle to run games at anything above the minimum quality settings, and in the case of some modern games, you might not be able to run them at all.

 The same applies to photo and video editors. While photo editing generally doesn't require nearly as much VRAM as video editing, the requirement is still more than what your computer needs when browsing the internet or typing up documents.

![asus graphics card on granite surface](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/gpu-card-1.jpg)

 As a general rule of thumb, you should have at least 4GB of VRAM for gaming and 8GB of VRAM for video editing. This requirement can vary based on what games you're playing or the resolution of the video you're editing, but the more, the better. We've already covered [how much VRAM you need for modern games](https://www.makeuseof.com/how-much-vram-do-you-need-modern-games/) in case you need some help.

 There are, of course, other factors that affect these requirements as well. The architecture and generation of your GPU, the type of VRAM, GPU, CPU clock speeds, and even the rest of your computer's hardware can all affect how much VRAM you actually need. If you're building a PC, knowing the [difference between RAM and VRAM](https://www.makeuseof.com/ram-vs-vram-differences/) is also important.

## Knowing Your PC Specs Is Important

 Knowing your PC specs can help you save massively when buying a new computer or upgrading your existing one. If you know your specs, you can make informed decisions based on how you plan to use your computer, which means you'll be able to allocate more of your budget to the components that matter instead of spending all your money on the parts with the most RGB lighting.

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




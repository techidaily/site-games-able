---
title: Innovative Game Ideas for Your Linux Terminal
date: 2024-09-08T16:42:49.823Z
updated: 2024-09-15T16:38:27.532Z
tags:
  - games
categories:
  - games
description: This Article Describes Innovative Game Ideas for Your Linux Terminal
excerpt: This Article Describes Innovative Game Ideas for Your Linux Terminal
keywords: Linux Terminal Games,Unique Linux Console Gaming,Creative Terminal Game Concepts,Linux Terminal Inspirational Ideas,Open Source Terminal Games,Linux Command Line Gaming,DIY Linux Terminal Entertainment
thumbnail: https://thmb.techidaily.com/3826690fad2bdad4d7aa62bd8a31b6771b07791104399fd4c0b5ca08b831fc4c.jpg
---

## Innovative Game Ideas for Your Linux Terminal

 It's often said that Linux isn't a platform for gamers. It's not true of course, and Linux gamers have access to the best AAA games available.

 And if you have some spare time, but don't want to fire up the latest open-world, immersive gore-fest, you can open a terminal and have fun with these command-line games for Linux.

## 1\. doom-ascii
![playing Doom in the Linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/playing-doom-in-the-linux-terminal.jpg)

 Doom is possibly the best-known first-person shooter ever created, and was insanely popular at schools and campuses throughout the 1990s.

 Playing as an unnamed space marine, you must fight through hordes of demons on the moons of Mars and in hell.

 doom-ascii makes it easy to [play Doom in your Linux terminal](https://www.makeuseof.com/how-to-play-doom-in-linux-terminal/) , with ASCII characters standing in for individual pixels. You'll need to have some original**WAD** files from either Doom or Doom II to play.

## 2\. solitaire-tui
![playing solitaire in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/playing-solitaire-in-the-linux-terminal.jpg)

 Solitaire is the perfect way to waste some time on your own while you wait for binaries to [compile from the source](https://www.makeuseof.com/compile-install-software-from-source-linux/) .

 If you don't have a deck of cards handy, a virtual game in your terminal is just as good.

[solitaire-tui is a sophisticated and modern implementation](http://www.makeuseof.com/play-solitaire-in-linux-terminal/) of the classic card game, written using Google's Go language. You can expect to see a clean interface and can move cards from one stack to another using your mouse, rather than relying on the keyboard.

If you have Go installed, you can easily grab solitaire-tui with:

`go install github.com/brianstrauch/solitaire-tui@latest`

Then create a symbolic link:

`sudo ln -s ~/go/bin/solitaire-tui /usr/bin/solitaire`

You can now launch solitaire-tui by typing:

`solitaire`

## 3\. Conway's Game of Life
![conway game of life in progress](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/conway-game-in-progress.jpg)

[Conway's Game of Life](https://www.makeuseof.com/play-conways-game-of-life-in-linux-terminal/) isn't actually a game as such. Rather it's a virtual evolution simulator.

 After setting the initial conditions by arranging individual cells on screen, you can sit back and watch, as the cells live, die, reproduce, and interact according to mathematical rules to create new and interesting configurations.

 Possibilities are endless, and given enough time, Conway's game of life will reveal to you the infinite secrets and mysteries of the universe.

## 4\. nInvaders
![ninvaders in linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/ninvaders-in-linux-terminal.jpg)

 nInvaders is a reimagining of the classic Space Invaders arcade games—one of the first and most successful video games ever.

 With nInvaders, you get a ncurses interface where you use left and right arrow keys to control a ship and destroy alien invaders before they reach you.

 One of the great things about this tribute is that even using an ASCII character set, the graphics are on par with the 1978 original. The gameplay is also faster as you're not limited by 1970s hardware.

You can install nInvaders on Debian-based systems with:

`sudo apt install ninvaders`

 Alternatively, you can clone the nInvaders [GitHub](https://github.com/doctorfree/ninvaders) repository and build from the source.

## 5\. Gambit
![gambit chessboard with checkmate imminent](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gambit-chessboard-with-checkmate-imminent.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Chess is one of the greatest adversarial games ever invented and pits strategic thinkers against each other in a battle of wits.

 Gambit is an implementation of the classic game written using Go, and makes it super-easy to set up a terminal-based game of chess with a human opponent over a Secure Shell (SSH) connection.

 Pieces are rendered beautifully in your terminal, and you can move them either by using the keyboard or clicking on them with your mouse.

 It's easy to [install Gambit on Linux](https://www.makeuseof.com/play-chess-linux-terminal-multiplayer-over-ssh/) , and you can have a game set up in mere minutes.

## 6\. Clidle
![clidle in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/clidle-in-the-linux-terminal.jpg)

 Wordle is a guessing game where you try to guess a five-letter word, by inputting your word and seeing how many letters they have in common. You're limited to six guesses in total, so the stakes are high, and there are dozens of [tricks and strategies to help you improve your Wordle score](https://www.makeuseof.com/wordle-tips-hints-tricks/) .

 While the original Wordle game was purchased by the New York Times in 2022, imitators have flourished.

 Clidle is a Wordle clone you play over SSH. To start, simply open a terminal and enter:

`ssh clidle.duckdns.org -p 3000`

Type a five-letter word to begin and see how good your score is!

 A green highlighted letter shows that you have the right letter in the right space, while a yellow highlight indicates the letter is present, but in a different slot.

<!-- affiliate ads begin -->
<span id="1983446">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983446.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983446">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983446.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983446%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983446/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Tetris
![tetris in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tetris-in-the-linux-terminal.jpg)

 Tetris is a quick time-killer that has been around since 1985 and holds the record for the most ported game ever, having been adapted for 65 different platforms.

 With different-shaped puzzle pieces falling from the top of the screen, you must rotate them as they fall to create solid lines, which then disappear. If your pieces reach the top of the screen, you lose.

 While it sounds simple, working out the optimum rotation can be difficult at higher difficulty levels.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## There’s No Shortage of Terminal Games on Linux

 This selection of games for your Linux terminal is great if you just want to waste some time. But if you're playing command-line games because your Linux PC has poor performance, there are a variety of ways to increase the framerate and your gaming experience.

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
<li><a href="https://youtube-sure.techidaily.com/n-2024-creative-command-center-studio-for-youtubers/"><u>[New] In 2024, Creative Command Center Studio for YouTubers</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-timeless-tones-a-compendium-of-quality-sound-sites/"><u>2024 Approved Timeless Tones A Compendium of Quality Sound Sites</u></a></li>
<li><a href="https://tech-hub.techidaily.com/apple-store-finding-genuine-chatgpt-apps/"><u>Apple Store: Finding Genuine ChatGPT Apps</u></a></li>
<li><a href="https://games-able.techidaily.com/exquisite-office-mat-selection-guide-2024/"><u>Exquisite Office Mat Selection Guide 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/from-classics-to-cutting-edge-mmo-game-advancements/"><u>From Classics to Cutting-Edge: MMO Game Advancements</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-zte-nubia-z60-ultra-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My ZTE Nubia Z60 Ultra | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-motorola-edge-40-pro-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Motorola Edge 40 Pro Phone FRP Lock</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-webcams-for-professional-sound-recording/"><u>In 2024, Premium Webcams for Professional Sound Recording</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-xiaomi-redmi-a2-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Xiaomi Redmi A2</u></a></li>
<li><a href="https://games-able.techidaily.com/steady-gameplay-for-xbox-s-controller/"><u>Steady Gameplay for Xbox S Controller</u></a></li>
<li><a href="https://games-able.techidaily.com/understanding-the-impact-of-rdna-35-amds-future-tech/"><u>Understanding the Impact of RDNA 3.5 - AMD's Future Tech</u></a></li>
<li><a href="https://ai-topics.techidaily.com/what-is-an-ai-tool-in-2024/"><u>What Is an AI Tool, In 2024</u></a></li>
</ul></div>


---
title: "The Ultimate Playlist: 7 Terminal Games on Linux"
date: 2024-09-14T18:33:53.383Z
updated: 2024-09-21T00:07:15.928Z
tags:
  - games
categories:
  - games
description: "This Article Describes The Ultimate Playlist: 7 Terminal Games on Linux"
excerpt: "This Article Describes The Ultimate Playlist: 7 Terminal Games on Linux"
keywords: Linux Gaming,Ultimate Terminal Games List,Top Linux Gaming Picks,Linux Game Recommendations,Terminal Games Compilation,Linux Terminal Gaming Experience,Explore Linux Games Playlist
thumbnail: https://thmb.techidaily.com/0b2657385f18cc859d59520b24816f771e8e749f151532892ba053a97dc454cb.jpg
---

## The Ultimate Playlist: 7 Terminal Games on Linux

 It's often said that Linux isn't a platform for gamers. It's not true of course, and Linux gamers have access to the best AAA games available.

 And if you have some spare time, but don't want to fire up the latest open-world, immersive gore-fest, you can open a terminal and have fun with these command-line games for Linux.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. doom-ascii

![playing Doom in the Linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/playing-doom-in-the-linux-terminal.jpg)

 Doom is possibly the best-known first-person shooter ever created, and was insanely popular at schools and campuses throughout the 1990s.

 Playing as an unnamed space marine, you must fight through hordes of demons on the moons of Mars and in hell.

 doom-ascii makes it easy to[play Doom in your Linux terminal](https://www.makeuseof.com/how-to-play-doom-in-linux-terminal/) , with ASCII characters standing in for individual pixels. You'll need to have some original**WAD** files from either Doom or Doom II to play.

## 2\. solitaire-tui

![playing solitaire in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/playing-solitaire-in-the-linux-terminal.jpg)

 Solitaire is the perfect way to waste some time on your own while you wait for binaries to[compile from the source](https://www.makeuseof.com/compile-install-software-from-source-linux/) .

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. nInvaders

![ninvaders in linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/ninvaders-in-linux-terminal.jpg)

 nInvaders is a reimagining of the classic Space Invaders arcade games—one of the first and most successful video games ever.

 With nInvaders, you get a ncurses interface where you use left and right arrow keys to control a ship and destroy alien invaders before they reach you.

 One of the great things about this tribute is that even using an ASCII character set, the graphics are on par with the 1978 original. The gameplay is also faster as you're not limited by 1970s hardware.

You can install nInvaders on Debian-based systems with:

`sudo apt install ninvaders`

 Alternatively, you can clone the nInvaders[GitHub](https://github.com/doctorfree/ninvaders) repository and build from the source.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Gambit

![gambit chessboard with checkmate imminent](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/gambit-chessboard-with-checkmate-imminent.jpg)

 Chess is one of the greatest adversarial games ever invented and pits strategic thinkers against each other in a battle of wits.

 Gambit is an implementation of the classic game written using Go, and makes it super-easy to set up a terminal-based game of chess with a human opponent over a Secure Shell (SSH) connection.

 Pieces are rendered beautifully in your terminal, and you can move them either by using the keyboard or clicking on them with your mouse.

 It's easy to[install Gambit on Linux](https://www.makeuseof.com/play-chess-linux-terminal-multiplayer-over-ssh/) , and you can have a game set up in mere minutes.

## 6\. Clidle

![clidle in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/clidle-in-the-linux-terminal.jpg)

 Wordle is a guessing game where you try to guess a five-letter word, by inputting your word and seeing how many letters they have in common. You're limited to six guesses in total, so the stakes are high, and there are dozens of[tricks and strategies to help you improve your Wordle score](https://www.makeuseof.com/wordle-tips-hints-tricks/) .

 While the original Wordle game was purchased by the New York Times in 2022, imitators have flourished.

 Clidle is a Wordle clone you play over SSH. To start, simply open a terminal and enter:

`ssh clidle.duckdns.org -p 3000`

Type a five-letter word to begin and see how good your score is!

 A green highlighted letter shows that you have the right letter in the right space, while a yellow highlight indicates the letter is present, but in a different slot.

## 7\. Tetris

![tetris in the linux terminal](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tetris-in-the-linux-terminal.jpg)

 Tetris is a quick time-killer that has been around since 1985 and holds the record for the most ported game ever, having been adapted for 65 different platforms.

 With different-shaped puzzle pieces falling from the top of the screen, you must rotate them as they fall to create solid lines, which then disappear. If your pieces reach the top of the screen, you lose.

 While it sounds simple, working out the optimum rotation can be difficult at higher difficulty levels.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://extra-support.techidaily.com/new-screens-that-make-a-statement-the-ultimate-4k-displays-for-macs/"><u>[New] Screens That Make a Statement The Ultimate 4K Displays for Macs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/android-call-history-recovery-recover-deleted-call-logs-from-narzo-60x-5g-by-fonelab-android-recover-call-logs/"><u>Android Call History Recovery - recover deleted call logs from Narzo 60x 5G</u></a></li>
<li><a href="https://video-capture.techidaily.com/capture-the-best-sound-quality-your-ultimate-guidebook-to-recording-podcasts-via-zoom/"><u>Capture the Best Sound Quality Your Ultimate Guidebook to Recording Podcasts via Zoom</u></a></li>
<li><a href="https://games-able.techidaily.com/elevate-your-media-experience-fullscreen-playnite-tv/"><u>Elevate Your Media Experience - Fullscreen Playnite TV</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-apple-id-verification-code-not-working-from-iphone-se-2022-by-drfone-ios/"><u>How To Fix Apple ID Verification Code Not Working From iPhone SE (2022)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-4-ways-to-trace-vivo-s17-pro-location-drfone-by-drfone-virtual-android/"><u>In 2024, Top 4 Ways to Trace Vivo S17 Pro Location | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/navigating-the-best-budget-hd-tabs-a-thorough-review-of-lenovo-tab-m10-fhd-plus/"><u>Navigating the Best Budget HD Tabs: A Thorough Review of Lenovo Tab M10 FHD Plus</u></a></li>
<li><a href="https://games-able.techidaily.com/reprogramming-steam-language-default/"><u>Reprogramming Steam Language Default</u></a></li>
<li><a href="https://games-able.techidaily.com/restart-your-ps5-controller-techniques-and-timings/"><u>Restart Your PS5 Controller: Techniques and Timings</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-essential-guide-to-8-premium-free-roku-channels-2024-edition/"><u>The Essential Guide to 8 Premium Free Roku Channels - 2024 Edition</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unleashing-your-iphone-the-top-techniques-for-skyline-pics/"><u>Unleashing Your iPhone The Top Techniques for Skyline Pics</u></a></li>
<li><a href="https://vp-tips.techidaily.com/unlocking-the-power-of-amd-gpus-the-ultimate-guide-to-using-h264h265-video-transcoding/"><u>Unlocking the Power of AMD GPUs: The Ultimate Guide to Using H.264/H.265 Video Transcoding</u></a></li>
</ul></div>


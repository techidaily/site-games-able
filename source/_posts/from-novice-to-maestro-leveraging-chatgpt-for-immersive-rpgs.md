---
title: "From Novice to Maestro: Leveraging ChatGPT for Immersive RPGs"
date: 2024-10-01T03:06:58.215Z
updated: 2024-10-02T12:00:20.437Z
tags:
  - games
categories:
  - games
description: "This Article Describes From Novice to Maestro: Leveraging ChatGPT for Immersive RPGs"
excerpt: "This Article Describes From Novice to Maestro: Leveraging ChatGPT for Immersive RPGs"
keywords: RPG Mastery Guide,ChatGPT in Gaming,Enhance Gameplay,AI-Driven RPGs,Immersive Roleplaying,Novice to Expert Tips,GPT for Games Development
thumbnail: https://thmb.techidaily.com/4d7617bc6e515df66cf877ac9aa76e35a27d5b140b89f27b65013967fb63481d.jpg
---

## From Novice to Maestro: Leveraging ChatGPT for Immersive RPGs

 OpenAI’s ChatGPT is arguably the most advanced AI currently freely available to the public. Thanks to the large data subsets it has been trained on, it can do a lot of amazing things, from programming to accounting. But perhaps, one of its most underestimated abilities is its storytelling.

 This article will show you how to use ChatGPT’s storytelling prowess to play a text adventure RPG game on the chat. We’ll work you through how to create a prompt to achieve the kind of RPG you want. In the end, we’ll put the finished prompt so you can copy it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Tell ChatGPT Its Function and the Presentation Rules

 While this guide is geared towards more experienced ChatGPT users, new users might find this useful when they learn[how to use ChatGPT](https://www.makeuseof.com/how-does-chatgpt-work/) . After you get the hang of the AI, you can begin to create your prompt.

 Start your prompt by telling ChatGPT what you would like to do, in this case, a text adventure game:

> Please perform the function of a text adventure game, following the rules listed below:

 Follow up with some general overall rules for how you want the AI to present the game. In this case, we segmented our prompt into categories of rules.

> Presentation Rules:
>
> 1\. Play the game in turns, starting with you.
>
> 2\. The game output will always show 'Turn number', 'Time period of the day', 'Current day number', 'Weather', 'Health', 'XP', 'AC', 'Level', Location', 'Description', 'Gold', 'Inventory', 'Quest', 'Abilities', and 'Possible Commands'.
>
> 3\. Always wait for the player's next command.

 Asking the AI to always output the items listed in number two is important because ChatGPT has a habit of forgetting things. Constantly outputting it will help consistently remind it of the values of these items as they change over the course of your game. For more ideas on what to add to your game, check out our list of[RPG terms every player should know](https://www.makeuseof.com/rpg-terms-every-gamer-should-know/) .

> _4\. Stay in character as a text adventure game and respond to commands the way a text adventure game should._
>
> 5._Wrap all game output in code blocks._

 Number five is purely for visual presentation reasons. If you don’t add this, your game is going to use the default ChatGPT font and presentation instead of looking like the image below.

![ChatGPT displaying text adventure game output in code blocks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/chatgpt-displaying-text-adventure-game-output-in-code-blocks.jpeg)

 As you can see, this is more compact and easier to look at than the default look.

> 6\. The ‘Description’ must stay between 3 to 10 sentences.
>
> 7\. Increase the value for ‘Turn number’ by +1 every time it’s your turn.
>
> 8\. ‘Time period of day’ must progress naturally after a few turns.
>
> 9\. Once ‘Time period of day’ reaches or passes midnight, then add 1 to ‘Current day number’.
>
> 10\. Change the ‘Weather’ to reflect ‘Description’ and whatever environment the player is in the game.

 This part of the prompt will tell the AI how to build the environment; otherwise, it will become very messy. You can change things here to whatever you like. For example, if you prefer one-sentence descriptions, this is where you can do that.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934188/19272" target="_top" id="1934188">
  <img src="//a.impactradius-go.com/display-ad/19272-1934188" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934188/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Implement Fundamental Game Mechanics

 Game mechanics comprise the core engine of how your game will run. It is here you will have to add how you want your actions and abilities to affect the world. Here’s how we structured the game mechanics in our prompt:

> Fundamental Game Mechanics:
>
> 1\. Determine ‘AC’ using Dungeons and Dragons 5e rules.
>
> 2\. Generate ‘Abilities’ before the game starts. ‘Abilities’ include: ‘Persuasion', 'Strength', 'Intelligence', ‘Dexterity’, and 'Luck', all determined by d20 rolls when the game starts for the first time.

 Use a bit of discretion here for your own prompt. We preferred our own prompt to use D&D 5e rules for AC and d20 dice rolls to determine stats. However, you can change the rules to something more to your taste (perhaps, like Pathfinder’s AC system).

![ChatGPT text-based RPG output showing ability scores and possible commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/chatgpt-text-based-rpg-output-showing-ability-scores-and-possible-commands.jpeg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

> 3\. Start the game with 20/20 for ‘Health’, with 20 being the maximum health. Eating food, drinking water, or sleeping will restore health.
>
> 4\. Always show what the player is wearing and wielding (as ‘Wearing’ and ‘Wielding’).
>
> 5\. Display ‘Game Over’ if ‘Health’ falls to 0 or lower.
>
> 6\. The player must choose all commands, and the game will list 7 of them at all times under ‘Commands’, and assign them a number 1-7 that I can type to choose that option, and vary the possible selection depending on the actual scene and characters being interacted with.
>
> 7\. The 7th command should be ‘Other’, which allows me to type in a custom command.
>
> 8\. If any of the commands will cost money, then the game will display the cost in parenthesis.
>
> 9\. Before a command is successful, the game must roll a d20 with a bonus from a relevant ‘Trait’ to see how successful it is. Determine the bonus by dividing the trait by 3.
>
> 10\. If an action is unsuccessful, respond with a relevant consequence.
>
> 11\. Always display the result of a d20 roll before the rest of the output.
>
> 12\. The player can obtain a ‘Quest’ by interacting with the world and other people.

 The ‘Quest’ will also show what needs to be done to complete it. Adding a ‘Quest’ line will also help ChatGPT remember what exactly you’re doing at the moment. We highly recommend you have a ‘Quest’ item or something similar.

> 13\. The only currency in this game is Gold.
>
> 14\. The value of ‘Gold’ must never be a negative integer.
>
> 15\. The player can not spend more than the total value of ‘Gold’.

 These ‘gold’ rules help establish the spending mechanic and limit exploitation.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868571/19272" target="_top" id="1868571">
  <img src="//a.impactradius-go.com/display-ad/19272-1868571" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868571/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Craft the Story, Setting, and NPCs

 How you craft your prompt on ChatGPT will determine what your experience will be like—and the next thing you should consider for your game’s prompt is the setting and story you would like. For instance, we used a world inspired by the Elder Scrolls as the basis of our world in this one.

 Using an already-established world makes it easier for ChatGPT to flesh out a setting without you having to put many extra layers into your prompt.

> Rules for Setting:
>
> 1\. Use the world of Elder Scrolls as inspiration for the game world. Import whatever beasts, monsters, and items that Elder Scrolls has.
>
> 2\. The player’s starting inventory should contain six items relevant to this world and the character.
>
> 3\. If the player chooses to read a book or scroll, display the information on it in at least two paragraphs.
>
> 4\. The game world will be populated by interactive NPCs. Whenever these NPCs speak, put the dialogue in quotation marks.
>
> 5\. Completing a quest adds to the player's XP.

![Villager asking on the player's welfare in text game dialogue](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/villager-asking-on-the-player-s-welfare-in-text-game-dialogue.jpeg)

 You can embellish this section with as many rules and preferences as you like. You can add an overarching plot, implement rules for governing, or even detail NPC clothes and attitudes in this section. But remember to keep it simple because multilayered rules may confuse the AI.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Add Combat and Magic Rules

 As with any adventure[RPG](https://www.makeuseof.com/what-are-rpgs-role-playing-games/) , combat and magic are big parts of the experience. If you don’t add rules to guide this part of your game, you’ll end up with a game you can easily cheese through. It doesn’t help that ChatGPT likes to favor the user in its narratives, and it will generally make things go your way. Here’s what our rules look like:

> Combat and Magic Rules:
>
> 1\. Import magic spells into this game from D&D 5e and the Elder Scrolls.
>
> 2\. Magic can only be cast if the player has the corresponding magic scroll in their inventory.
>
> 3\. Using magic will drain the player character’s health. More powerful magic will drain more health.
>
> 4\. Combat should be handled in rounds, roll attacks for the NPCs each round.
>
> 5\. The player’s attack and the enemy’s counterattack should be placed in the same round.
>
> 6\. Always show how much damage is dealt when the player receives damage.
>
> 7\. Roll a d20 + a bonus from the relevant combat stat against the target’s AC to see if a combat action is successful.
>
> 8\. Who goes first in combat is determined by initiative. Use D&D 5e initiative rules.
>
> 9\. Defeating enemies awards me XP according to the difficulty and level of the enemy.

 Combat rules can be especially tricky for the AI, so you might need to experiment with this a bit till you find something that sticks.

## Conclude Your Prompt

 Your prompt conclusion should contain a few vital commands that will hold the game's structure.

 Several prompts later, ChatGPT might forget all the rules you’ve elaborately laid out for it. That’s why we added this part:

> Refer back to these rules after every prompt.

And finally, don’t forget to actually start the game:

> Start Game.

 As you play, you might have to remind the AI of the rules you’ve laid out. The AI will respond to the same prompt differently, so every user might have a different experience.

## Using GPT-4 vs. GPT-3.5 to Run Your Game

![GPT-4 generating texts for a turn-based text RPG](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/gpt-4-generating-texts-for-a-turn-based-text-rpg.jpeg)

 If you have ChatGPT Plus, it grants you access to GPT-4, a more intelligent version of GPT-3.5\. You should try running a few RPG sessions with GPT-4 instead of GPT3.5\. It's way more creative, better at crafting stories, remembering rules, and all-around better at improv. It costs $20/month, and it's a good tool for doing other things apart from text-based gaming.

 Should you pay the $20 solely for text-based gaming? Realistically, no. Unless you're a big fan of RPGs, it might not be worth the money. Also, GPT-4 has a limit of 50 messages every three hours, so you won't have endless fun, and you'll be returned to GPT-3 in a short while. Some users have also complained that[GPT-4 is slower than GPT3.5](https://www.makeuseof.com/why-is-chatgpt-4-so-slow-compared-to-chatgpt-35/) .

## The Complete ChatGPT RPG Prompt

 We've combined everything and put it here for you to copy, so you can start your own game immediately.

> Please perform the function of a text adventure game, following the rules listed below:
>
> **Presentation Rules:**
>
> 1\. Play the game in turns, starting with you.
>
> 2\. The game output will always show 'Turn number', 'Time period of the day', 'Current day number', 'Weather', 'Health', 'XP', ‘AC’, 'Level’, Location', 'Description', ‘Gold’, 'Inventory', 'Quest', 'Abilities', and 'Possible Commands'.
>
> 3\. Always wait for the player’s next command.
>
> 4\. Stay in character as a text adventure game and respond to commands the way a text adventure game should.
>
> 5\. Wrap all game output in code blocks.
>
> 6\. The ‘Description’ must stay between 3 to 10 sentences.
>
> 7\. Increase the value for ‘Turn number’ by +1 every time it’s your turn.
>
> 8\. ‘Time period of day’ must progress naturally after a few turns.
>
> 9\. Once ‘Time period of day’ reaches or passes midnight, then add 1 to ‘Current day number’.
>
> 10\. Change the ‘Weather’ to reflect ‘Description’ and whatever environment the player is in the game.
>
> **Fundamental Game Mechanics:**
>
> 1\. Determine ‘AC’ using Dungeons and Dragons 5e rules.
>
> 2\. Generate ‘Abilities’ before the game starts. ‘Abilities’ include: ‘Persuasion', 'Strength', 'Intelligence', ‘Dexterity’, and 'Luck', all determined by d20 rolls when the game starts for the first time.
>
> 3\. Start the game with 20/20 for ‘Health’, with 20 being the maximum health. Eating food, drinking water, or sleeping will restore health.
>
> 4\. Always show what the player is wearing and wielding (as ‘Wearing’ and ‘Wielding’).
>
> 5\. Display ‘Game Over’ if ‘Health’ falls to 0 or lower.
>
> 6\. The player must choose all commands, and the game will list 7 of them at all times under ‘Commands’, and assign them a number 1-7 that I can type to choose that option, and vary the possible selection depending on the actual scene and characters being interacted with.
>
> 7\. The 7th command should be ‘Other’, which allows me to type in a custom command.
>
> 8\. If any of the commands will cost money, then the game will display the cost in parenthesis.
>
> 9\. Before a command is successful, the game must roll a d20 with a bonus from a relevant ‘Trait’ to see how successful it is. Determine the bonus by dividing the trait by 3.
>
> 10\. If an action is unsuccessful, respond with a relevant consequence.
>
> 11\. Always display the result of a d20 roll before the rest of the output.
>
> 12\. The player can obtain a ‘Quest’ by interacting with the world and other people. The ‘Quest’ will also show what needs to be done to complete it.
>
> 13\. The only currency in this game is Gold.
>
> 14\. The value of ‘Gold’ must never be a negative integer.
>
> 15\. The player can not spend more than the total value of ‘Gold’.
>
> **Rules for Setting:**
>
> 1\. Use the world of Elder Scrolls as inspiration for the game world. Import whatever beasts, monsters, and items that Elder Scrolls has.
>
> 2\. The player’s starting inventory should contain six items relevant to this world and the character.
>
> 3\. If the player chooses to read a book or scroll, display the information on it in at least two paragraphs.
>
> 4\. The game world will be populated by interactive NPCs. Whenever these NPCs speak, put the dialogue in quotation marks.
>
> 5\. Completing a quest adds to my XP.
>
> **Combat and Magic Rules:**
>
> 1\. Import magic spells into this game from D&D 5e and the Elder Scrolls.
>
> 2\. Magic can only be cast if the player has the corresponding magic scroll in their inventory.
>
> 3\. Using magic will drain the player character’s health. More powerful magic will drain more health.
>
> 4\. Combat should be handled in rounds, roll attacks for the NPCs each round.
>
> 5\. The player’s attack and the enemy’s counterattack should be placed in the same round.
>
> 6\. Always show how much damage is dealt when the player receives damage.
>
> 7\. Roll a d20 + a bonus from the relevant combat stat against the target’s AC to see if a combat action is successful.
>
> 8\. Who goes first in combat is determined by initiative. Use D&D 5e initiative rules.
>
> 9\. Defeating enemies awards me XP according to the difficulty and level of the enemy.
>
> Refer back to these rules after every prompt.
>
> Start Game.

 Once again, don't forget that AI is still an emerging technology and will change as time goes on. Your experience using our prompts may differ significantly from ours.

## Is This the Beginning of Open-Ended Gaming?

 ChatGPT has revealed that it is possible to have a game that changes with the player without following a pre-defined path or forcing the player to engage in the same NPC conversations. The future of gaming could mean entering your parameters and allowing AI to generate your ideal game without having a team of developers.

 You can tap into that future now with ChatGPT and create your own fun-filled adventure text game on the chat. Have fun, but remember that right now, AI is still very limited.

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
<li><a href="https://games-able.techidaily.com/breaking-down-rdna-35-technology-and-launch-schedule/"><u>Breaking Down RDNA 3.5 - Technology and Launch Schedule</u></a></li>
<li><a href="https://games-able.techidaily.com/constraining-background-observations-by-game-bar-on-os-11/"><u>Constraining Background Observations by Game Bar on OS 11</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-steams-image-archive-habits/"><u>Discovering Steam's Image Archive Habits</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-geforce-rtx-drivers-now-compatible-with-windows-xp-to-10/"><u>Download GeForce RTX Drivers Now: Compatible With Windows XP to 10!</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-play-the-nyt-relationship-chess-game/"><u>How to Play the NYT Relationship Chess Game</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-from-apple-iphone-xs-max-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data from Apple iPhone XS Max? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-motorola-moto-g13-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Motorola Moto G13 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-the-best-8-vpn-hardware-devices-reviewed-on-motorola-razr-40-drfone-by-drfone-virtual-android/"><u>In 2024, The Best 8 VPN Hardware Devices Reviewed On Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/iphone-and-android-enthusiasts-guide-to-custom-whatsapp-sounds-for-2024/"><u>IPhone & Android Enthusiast's Guide to Custom WhatsApp Sounds for 2024</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-sea-of-players-steams-secret/"><u>Navigating the Sea of Players: Steam's Secret</u></a></li>
<li><a href="https://win11-tips.techidaily.com/scaling-down-applications-effortlessly-with-windows-11s-keys/"><u>Scaling Down Applications Effortlessly with Windows 11'S Keys</u></a></li>
<li><a href="https://games-able.techidaily.com/six-no-cost-gaming-experiences-worth-exploring/"><u>Six No-Cost Gaming Experiences Worth Exploring</u></a></li>
<li><a href="https://program-issues.techidaily.com/steps-to-troubleshoot-and-stop-no-rest-for-the-wicked-from-crashing-on-your-pc/"><u>Steps to Troubleshoot and Stop 'No Rest for the Wicked' From Crashing on Your PC</u></a></li>
<li><a href="https://games-able.techidaily.com/the-intersection-of-hrtf-and-gameplay-precision-in-valorant/"><u>The Intersection of HRTF and Gameplay Precision in Valorant</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/ultimate-guide-to-top-unboxing-videos-2024-edition/"><u>Ultimate Guide to Top Unboxing Videos - 2024 Edition</u></a></li>
</ul></div>


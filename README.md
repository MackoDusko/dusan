# Macko Duško
Userscript BOT The-West, Reworked Dobby2

> ## Install Script
> Works with Tampermonkey / Violentmonkey
>
> <a href="https://mackodusko.github.io/dusan/script.user.js" target="_blank"><button>Install UserScript</button></a>

## FEATURES:

- Feature load best XP or best money jobs preset or save your own jobs for later use or for automatic silver job swap when new day starts
- Automatically change silver jobs when new day starts allowing script to effectively work 24/7 without human interaction
- Script can calculate most optimal travel path between all added jobs to maximize profits
- Delayed start and stop feature
- Automatically attend Fort Battles. Stop refilling energy before battle, equip battle set, refill health before battle. After fort battle recover and automatically start working jobs again.
- Enganced consumable use: Intelligent calculation of best possible consumable to use in any given situation
- Automatically use best consumable every 10 minutes cooldown to refill energy in specified range
- Ability to travel to any job even if is locked and player has not enough LP or level to start the job
- Ability to work some jobs that are locked otherwise
- Automatically deposit set amount of money in bank when player is not duel protected
- Ability to automatically use buffs for speed, xp, money, luck, product
- Feature to automatically build town
- Ability to save custom gear for each job
- Auto login / auto refresh
- Script will continue to work even after short internet cutoffs
- Script will automatically handle player KO or other unexpected events and will always work
- Automatically send event currency to friends (eggs, hearths etc.)
- Automatically open all important bags exactly every 23 hours like Magic Nugget Bag and all Event bags with event currency (eggs, hearths etc.)
- Ability to auto-open / auto-use items and feature to auto-buy multiple items from town merchants
- Enhanced Statistics GUI
- Ability to Export and Import script data
- Sofisticated Sleep / regeneration feature
- Skip tutorial for new accounts
- Skip animations for valentine wheel of fortune
- Disable annoying premium notifications
- Farming assistant feature: Tools to effectively use up all job motivation under level 10 eg. Automatically unequip gear for specific jobs that unlocks before level 10, Automatically find silver job when motivation reaches 0
- Improved Sets GUI. Sets are saved by name. Ability to automatically calculate set and ability to use sets from TW-Calc wardrobe
- Script remember all used consumables - how many consumables have been used and last used consumables
- Alert system and Nofitification system when something important happen


<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_1.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_2.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_3.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_4.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_5.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_6.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_7.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_8.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_9.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_10.png" style="max-width: 600px;">

<img src="https://mackodusko.github.io/dusan/docs/screenshots/Screenshot_11.png" style="max-width: 600px;">


## Ensuring Script Performance in the Background

When a browser tab is inactive or minimized (including when running on a VPS), the script may slow down significantly. To prevent this, use the following trick:

1. Right-click the browser shortcut and select <b>'Properties'</b>.
2. In the <b>'Target'</b> field, add the following flag at the end of the existing text: <b>--disable-background-timer-throttling</b>
<br>(Ensure there's a space between the existing text and the new flag.)
3. Launch the browser using this modified shortcut.

<b>Note:</b> This method only works for Chromium-based browsers!

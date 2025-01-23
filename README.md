# Macko Duško
Userscript BOT The-West, Reworked Dobby2

## Install Script
Works with Tampermonkey / Violentmonkey

<a href="https://mackodusko.github.io/dusan/script.user.js" target="_blank">
  <button>Install Userscript</button>
</a>

### Ensuring script works in background
When browser tab is not active or browser is minimized (happens also when running in VPS), the script will slow down significantly. To counter this there is simple trick:

In order for the script to work in the background (minimized browser / in another browser tab / VPS):
1. Open 'Properties' of the browser shortcut.
2. In the 'Target' field, add flag <b>--disable-background-timer-throttling</b> at the end of the line after existing text.
3. Ensure there's a space between the existing text and the new flag.: <b>--disable-background-timer-throttling</b>
4. Run the browser only from this modified shortcut.
(Only works on chromium based browsers!)

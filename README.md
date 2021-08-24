# ConsoleHelper
Hides PC runs from the GTAV Speedrun.com Leaderboard

This Tampermonkey/Grease Monkey script will add a button to your Speedrun.com page that will Hide all runs done on PC

![](https://i.imgur.com/R2bv2EU.png)

Once hidden, the original full leaderboard rank will show, but also in parenthesis, the console-only rank will show now too

![](https://i.imgur.com/buXOH9C.png)

You can press the button again to again show PC runs. The text of the button will change while it is working - it may take a few seconds, espcially on Trevor%. It will also reset to showing PC runs upon leaving or refreshing the page - also meaning no data is stored by the script.

For non-programmers, every single line of the code is commented explaining what it does.

Note that upon hiding PC runs, it will turn on the "Show Obsolete Runs" option, which may take a moment to load. This is done because it lets us find runs done by people who used to play on Console, but now play on PC, and still see their fastest console runs. It will show a '-' next to their normal rank if it is one of these runs.

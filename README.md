
# How 




# How to Force a Game to Launch on a Specific-Monitor


Move Any Window Between Monitors
Use these shortcuts to move a focused window (including fullscreen games) between monitors:

Win + Shift + Left Arrow → Move to the left monitor.

Win + Shift + Right Arrow → Move to the right monitor.

For Steam Games
Open Steam → Go to your Library.

Right-click the game → Click Properties.

In Launch Options, add: -adapter 1 (This forces the game to open on your second monitor.)

-adapter 0 → Primary Monitor

-adapter 1 → Secondary Monitor

-adapter 2 → Third Monitor (if available)

For Any Game
Create a Shortcut for the game’s .exe file (right-click the .exe → Create Shortcut).

Edit the Shortcut Target:

Right-click the shortcut → Properties.

In Target, add:

-adapter 0 → Primary Monitor

-adapter 1 → Secondary Monitor

-adapter 2 → Third Monitor (if available)

Example: "C:\Games\Steam\steamapps\common\The Forest\TheForest.exe" -adapter 1

Click Apply and OK, then use this shortcut to launch the game.

If -adapter 1 doesn’t work, try using -monitor 1 instead:

If It Still Doesn’t Work
Try these free tools:

Borderless Gaming

Dual Monitor Tools

For advanced control, DisplayFusion offers a paid version, but its free version may still be helpful for basic tasks.

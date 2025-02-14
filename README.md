# LethalTracker v1.2 by Artemis64

This program is meant to be an all-in-one scrap tracker for Lethal Company!
While the spreadsheets that exist are pretty nice and do give a bit more detail, i think they are generally rough on the eyes and don't have a great way to be displayed on stream. I figured making this would both simplify usage and also be easy to capture in OBS. (Improved in 1.2!)

This is also my first time making a full program like this! Let me know if you like it through [Twitter](https://twitter.com/artemis6425) or Discord (both artemis6425)

3270font (aka the Lethal Company font) was created by [Ricardo Bánffy](https://github.com/rbanffy) and others, please read `Font License.txt` and view the fonts [github page](https://github.com/rbanffy/3270font/tree/main)!

![screenshot of LethalTracker](https://i.imgur.com/l4pmPTK.png)

## Features

- All-inclusive LethalTracker.exe file so you don't have to deal with my messy code!
- Built-in overtime calculator
- Ability to estimate future quotas
- ...and more!

## Download 

[**Download the latest release**](https://github.com/Artemis6425/LethalTracker/releases/latest). No need to download the source code!

## How to Use

Once you open `LethalTracker.exe`, you'll be greeted by the credits screen. Click the `Credits` button at the top to close it and get to the main menu of it.
If you plan to go for high score runs, make sure "HIGH SCORE RUN" is selected on the top right. From there, you can start tracking your daily scrap on the left side of the screen, and watch your stats change in real time!

If you plan on going for specific quota runs, make sure "QUOTA # RUN" is selected, and fill out the box with the goal quota. By default, this sets itself to 10. From there, you will have a few extra stats on the right side, but otherwise usage is the same! Please note that if you do skip any days, put "0" in those days so the program can continue doing math correctly for you.

If you want to show the stats in OBS as well, click the OBS button on the credits screen. This will open up a dedicated window to just show the stats in a higher quality, as well as having the ability to change the font color and background color for easier chroma-keying!

## Known issues

- Using this program on a 4k monitor causes the scaling to be completely messed up. 1080p and 1440p monitors are just fine though.
- My code is fairly messy, but I've never made something like this before so just pretend its ok!

## Future ideas

- Pull the data straight from the LethalCompany.exe itself during the game, removing the need to type this in. (Would be banned from the Lethal Company speedrun.com board if I were to do this. Considering alternatives)

## Changelog

### v1.0 "Initial Release"

- Initial Release!
- Includes the Overtime Calculator, along with tracking of many stats

### v1.1

- Added the "Reset Confirmation" Dialog Box. Thank you for the feedback!

### v1.2 "Better for OBS"

- Added a button on the Credits screen that opens a `LethalTracker OBS` window. This shows the stats that the main window would, but in a bigger font size, and with the ability to change the text and background color. Thank you for the feedback!
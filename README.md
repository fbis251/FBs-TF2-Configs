FB's Team Fortress 2 Configurations
===========

These config files define how I play TF2. I have taken some snippets of code from the TF2 Wiki and from some of my friends, namely crespi, BLADE and Tornado of Sharks, and combined them into my own configuration files. There are customizations for everything, but by far the Spy config is the one with the most changes.

Notable Configurations
----------------------
**All Classes**
All classes share the following configurations, class specific configurations are listed below these.

- Primary and secondary weapon viewmodels hide on mouse1 click
- F1-F4 keys are used for changing loadouts
- Null movement is enabled, making it harder for those snipers to hit you
- Using shift to use voice in-game lowers your mic volume to 5% and restores it to 33% when you let go of shift. TF2's game volume is too loud, so 33% is a good level.
- Hit sounds (dingaling) will change pitch based on damage done

**Heavy/Pyro Configuration**

- The damage text batches, which means that you will see a sum total of the damage you've done over the past few seconds. This is different from all the other classes which show you damage per hit

**Engineer Configuration**

- Pressing Shift + 1 - 4 will build/destroy that particular building. Example: Shift + 1 will build/destroy the sentry

**Spy Configuration**
This requires a huge learning curve, but stick with it and your spy skills will improve!

*Main changes:*

- The keypad is now used for changing disguises. Example: Keypad 1 changes the disguise to scout, keypad 4 to demoman, etc.
- Keypad 0 will change disguise teams. If your disguises are BLU, pressing 0 will change the disguises to RED
- Pressing F will pull out your sapper and start spamming it
- Q switches between knife and revolver only
- R will toggle "zoom" by switching the FOV. This makes it easier to snipe with the ambassador (Thanks BLADE!)
- L will now drop the intelligence, cloak you and use lastdisguise
- Cloaking will always use lastdisguise
- Mousewheel will cycle between four disguises: pyro, engineer, demoman, sniper
- Numbers 1 and 4 now switch to Heavy and Soldier disguises, respectively
- Number 2 switches to revolver
- Number 3 switches to knife

Installation Instructions
-------------------------
1. Download the config's ZIP file by pressing "Download ZIP" or [clicking here](https://github.com/fbis251/tf2-configs/archive/master.zip)
2. Open your TF2 custom configuration directory (by default it will Steam\steamapps\common\Team Fortress 2\tf\custom)
3. Unzip the directory there (The unzipped folder should be under Steam\steamapps\common\Team Fortress 2\tf\custom\FBs-TF2-Configs-master
4. Load up TF2 and try out my configs. If you open the console directly after launching the game you should see "Default config loaded"

The final directory structure should look like this:

    Team Fortress 2
    └── tf
        └── custom
            └── FBs-TF2-Configs-master
                ├── cfg
                │   ├── autoexec.cfg
                │   ├── comanglia_fps_high.cfg
                │   ├── comanglia_fps_low.cfg
                │   ├── comanglia_fps_medium.cfg
                │   ├── demoman.cfg
                │   ├── engineer.cfg
                │   ├── fb.cfg
                │   ├── heavyweapons.cfg
                │   ├── medic.cfg
                │   ├── pyro.cfg
                │   ├── scout.cfg
                │   ├── sniper.cfg
                │   ├── soldier.cfg
                │   └── spy.cfg
                ├── README.md
                ├── scripts
                │   └── surfaceproperties.txt
                └── sound
                    └── ui
                        └── hitsound.wav

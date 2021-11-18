# CS:GO config

## How to use
put it here :

*...\Steam\userdata\<YOURSTEAMTRADEID>\730\local\cfg\autoexec.cfg*

## Startoptions
CS:GO startoptions :

*-novid +exec autoexec -threads 4 -high -noforcemaccel -noforcemspd -noforcemparms -32bp -tickrate 128*

## How it works
CS:GO automatically executes config.cfg on startup. All the settings you change in the game's UI will be written to *config.cfg*. As we do not want the *config.cfg* to be overwritten from any ingame settings, the file is read-only. Therefore, if you want to change any settings, do not change them ingame but rather put them in the config files provided.

*config.cfg* executes autoexec.cfg, which then executes all the other configs.

## Mouse settings
- 1600 dpi
- 6/11 windows
- in game sensitivity : 1.5
- usb refreshrate 1000hz


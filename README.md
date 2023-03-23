# CS:GO config

## How to use
create a file at this location : ``` ... / Steam / userdata / <YOURSTEAMTRADEID> / 730 / local / cfg / autoexec.cfg ```


## Start options
> `Steam Library` → `Game Properties` → `Set Launch Options`

`+exec autoexec.cfg -novid -threads 4 -high -noforcemaccel -tickrate 128 -nojoy -forcenovsync`

| paramaters        | *meaning* |
|---------------------|:---------|
| `exec autoexec.cfg` | execute this **actual config** *when starting the game*|
| `-novid`            | **skip** the useless intro *that takes few seconds to get you in the menu*|
| `-threads 4`        | **sets** the amount of *processor threads* that CS:GO will use while running|
| `-high`             | **force** the users system into running CS:GO on **high priority**, this means that running CS:GO will take priority over other system processes|
| `-noforcemaccel`    | **disables** *mouse acceleration*|
| `-tickrate 128`     | **sets any offline server** that a user runs *at* **tickrate 128** |
| `-nojoy`            | **disables** the *joystick support* and free up some resources like less load on the RAM |
| `-forcenovsync`     | **disables** the *VSync function* for CS:GO *which is known to cause problems like limiting the FPS* |

## How it works
CS:GO automatically executes `config.cfg` on startup. 

All the settings you change in the game's UI will be written to *config.cfg*.

As we do not want the `config.cfg` to be overwritten from any ingame settings,
the file is read-only. 

Therefore, if you want to change any settings, do not change them ingame but rather put them in the config files provided.

`config.cfg` executes `autoexec.cfg`, which then executes all the other configs.

## Mouse settings
- 1000 dpi
- 6/11 windows
- in game sensitivity : 1
- usb refreshrate 1000hz


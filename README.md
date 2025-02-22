# Tomb Raider IV - VI Remastered - Wine/Box64
This is a wine/box64 launchscript and wrapper structure for Tomb Raider IV - VI Remastered. Only the [GOG release](https://www.gog.com/en/game/tomb_raider_iv_vi_remastered) has been tested. To install, download the zip and put it in your `ports` folder, then add your game data to `ports/tombraider4-6/data`. Your basic file tree should be as follows.

```
├───tombraider4-6
│   ├───data/
│   │   ├───4
│   │   ├───5
│   │   ├───6
│   │   ├───tomb456.exe
│   ├───config/
│   ├───splash
│   ├───splash.png
```

To maintain gamepad glyphs, GPToKeyB is not used. Please exit the game using ingame menus.

#### Why not just use OpenLara?
OpenLara only supports Tomb Raider 1 at time of writing and while it can load levels from the other games, it can't play them sequentially (as far as I know). Plus, remastered modern version.
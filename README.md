# WWE '13 for PS5

**WWE '13 (Xbox 360) running natively on a jailbroken PS5**, at up to 1440p with matches at 60 fps.

> ### Built on WWE '13 Recomp by PromethenDev
> This port is based on **[WWE '13 Recomp](https://github.com/PromethenDev/wwe13-recomp)**, PromethenDev's native recompilation of WWE '13 for PC, and its game fixes. Their work is the backbone of this project: this release takes it to the PS5. Go check out and support the original project.

## Get it on RecompStore
The easiest way to play is **[RecompStore](https://recompstore.com)**. It installs the app, sets the game up from your own disc image and title update, and keeps it up to date.

[![Get it on RecompStore](https://recompstore.com/assets/press/badge-dark.svg)](https://recompstore.com/game/PPSA92013)

## What's in it
- 720p, 1080p or 1440p, matches at 60 fps (entrances and cutscenes at 30, as on the Xbox 360) or a 30 fps lock, 4x or 2x anti-aliasing and anisotropic filtering
- PlayStation button prompts throughout the game and a DualSense on the controller select screen (or the Xbox originals, if you prefer)
- The game's achievements as trophies: a popup when you earn one, and your progress on the hub's Trophies page
- A hub made for the DualSense: start the game, change settings, back up your saves, install DLC
- DLC and saves

## What you need
- A jailbroken PS5 that runs homebrew apps from `/data/homebrew/`
- Your **own** copy of WWE '13 for Xbox 360 and its title update 2.0.1.0. No game files are included.

## Install by hand
1. Download `PPSA92013.zip` from [Releases](../../releases) and copy the `PPSA92013` folder to `/data/homebrew/` on your PS5.
2. Copy your game's files and the title update into its `Assets` folder (the same game folder WWE '13 Recomp uses on PC):

```
/data/homebrew/PPSA92013/Assets/default.xex
/data/homebrew/PPSA92013/Assets/default.xexp
/data/homebrew/PPSA92013/Assets/pac/...
```

3. DLC packages go in `/data/homebrew/PPSA92013/UserData/DLC/` (or on a USB drive): install them from the hub's DLC page.

Launch it from your homebrew launcher. The hub opens first: press START GAME.

## Credits
- **[PromethenDev](https://github.com/PromethenDev)**: [WWE '13 Recomp](https://github.com/PromethenDev/wwe13-recomp), the recompilation and game fixes this port is built on
- **[elripalda](https://github.com/elripalda)**: the PS5 port, the hub, the PlayStation buttons and the trophies
- **[ReXGlue](https://github.com/rexglue/rexglue-sdk)**: the static recompiler and runtime; **[Xenia](https://github.com/xenia-project/xenia)**: the emulator its code comes from

*An unofficial fan project, not affiliated with or endorsed by WWE, THQ, Yuke's, Microsoft or Sony. No game files are included.*

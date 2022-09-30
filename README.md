# Electrobots

Electrobots by [0xC0DE](https://twitter.com/0xC0DE6502), an 8-bit game for Acorn Electron, BBC Micro and BBC Master. Can also be played on a PC (Windows or Linux+Wine) with the self-contained EXE.

Download and play for free. Please donate to support me: [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/S6S33YYQ7)

![Electrobots Intro Screen](https://github.com/0xC0DE6502/electrobots-releases/blob/main/res/electrobots-intro-screen.jpg?raw=true)

![Electrobots Screenshot 1](https://github.com/0xC0DE6502/electrobots-releases/blob/main/res/screenshot1.png?raw=true)
![Electrobots Screenshot 2](https://github.com/0xC0DE6502/electrobots-releases/blob/main/res/screenshot2.png?raw=true)
![Electrobots Screenshot 3](https://github.com/0xC0DE6502/electrobots-releases/blob/main/res/screenshot3.png?raw=true)
![Electrobots Screenshot 4](https://github.com/0xC0DE6502/electrobots-releases/blob/main/res/screenshot4.png?raw=true)

## Aim of the game
The year is 4096. 3 Electrobots are searching Terranova for ancient objects. Avoid the aliens and collect all 10 objects. Guide the bots to the exit portal. Good luck!

## How to play
There are 3 main ways to play the game:
1. Use the [tape image](https://github.com/0xC0DE6502/electrobots-releases/raw/main/electrobots.uef) on real hardware or an emulator
2. Use the [disk image](https://github.com/0xC0DE6502/electrobots-releases/raw/main/electrobots.ssd) on real hardware or an emulator
3. Play the [self-contained EXE](https://github.com/0xC0DE6502/electrobots-releases/raw/main/electrobots.exe) on a PC

### Linux+Wine
The self-contained Windows EXE works on Linux as well if you use Wine: `wine electrobots.exe`. You need a 64-bit `WINEPREFIX` and enough video memory configured (`winetricks videomemorysize=1024`). I have played the game successfully on Ubuntu 22.04 using Wine 7.18. Known issue: toggling full-screen play (`ALT+ENTER`) may cause the game to lose keyboard focus. Fix: use `ALT+TAB` to select the game window again.

## Controls (redefinable)

```
Z      - Left
X      - Right
:      - Up
/      - Down
RETURN - Jump / Activate portal
SPACE  - Fire (when gun is held)
```

### Other keys

```
1/2/3 - Switch zone (Land, Water, Space)
P     - Pause / Unpause
Q     - Quiet
S     - Sound
R     - Redefine controls
```

---

Electrobots - Copyright (C) 2021 [0xC0DE](https://twitter.com/0xC0DE6502)

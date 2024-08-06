# Custom ZMK build for 48Key keyboard
![IMG_20240806_154132166](https://github.com/user-attachments/assets/330eb5f4-8b73-4350-888e-b4442a6cc6bc)


Find 3D printer files for this board at this (repo)[https://github.com/Glitch860/48Key/]

Repo setup to deploy firmware onto [Nice!Nano V2](https://nicekeyboards.com/nice-nano/)

This is the [ZMK](https://zmk.dev/docs) firmware

Pushing changes will build all the keyboards. You need to be signed in to a GitHub account to push changes and build the firmware.

To build the firmware:

- Fork this repo on GitHub
- Clone your fork locally
- Trigger a build:
  - Make a trivial change to ./build.yaml (or any non *.md file)
  - Push that change
- Look in the [Actions](https://github.com/mmccoyd/zmk-config/actions) tab
     for the build triggered by that change. 
- Wait for the build to finish
- Click on the build link next to the green checkbox
- Download the artifact file with the firmware
- See [Installing The Firmware](https://zmk.dev/docs/user-setup#installing-the-firmware)
  for more details from there.

Layers:

DEFAULT 0

| ROW 0 | ROW 1 | ROW 2 | ROW 3 | ROW 4 | ROW 5 | ROW 6 | ROW 7 | ROW 8 | ROW 9 | ROW 10 | ROW 11 |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------ |
|  TAB  |   Q   |   W   |   E   |   R   |   T   |   Y   |  U    |   I   |   O   |    P   |   \    |
|  CTL  |   A   |   S   |   D   |   F   |   G   |   H   |  J    |   K   |   L   |    ;   |    '   |
| SHIFT |   Z   |   X   |   C   |   V   |   B   |   N   |   M   |   ,   |   .   |    /   | SHIFT  |
|  WIN  |  ALT  |   -   |  ENT  | SPACE | BKSP  |  BKSP | SPACE |  ENT  |   =   |   ALT  |   APP  |

FUNCTION 1

| ROW 0 | ROW 1 | ROW 2 | ROW 3 | ROW 4 | ROW 5 | ROW 6 | ROW 7 | ROW 8 | ROW 9 | ROW 10 | ROW 11 |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------ |
|  ESC  |       |  HOME |   UP  |  END  | PSCRN | VOL_UP| PG_UP |  UP   | PG_DN |   BR+  |   DEL  |
| CTRL  |  CAPS | LEFT  |  DOWN | RIGHT | FIND  | VOL_DN|  LEFT |  DOWN | RIGHT |   BR-  |  LOCK  |
| SHIFT |       | CUT   |  COPY | Paste |       | MUTE  |       |       |       |        | SHIFT  |
|  WIN  | ALT   |   [   |  ENT  | SPACE | BKSP  |  BKSP | SPACE |  ENT  |    ]  |   ALT  |   APP  |

NUMBERS 2

| ROW 0 | ROW 1 | ROW 2 | ROW 3 | ROW 4 | ROW 5 | ROW 6 | ROW 7 | ROW 8 | ROW 9 | ROW 10 | ROW 11 |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------ |
|  `    |    !  |    @  |    #  |   $   |    %  |   ^   |   &   |    *  |  (    |   )    |  DEL   |
| CTRL  |   1   |   2   |   3   |   4   |   5   |   6   |   7   |    8  |    9  |    0   | SHIFT  |
| F1    |   F2  |   F3  |   F4  |   F5  |   F6  |   F7  |   F8  |   F9  |  F10  |   F11  |   F12  |
|  WIN  |   ALT |   -   |   ENT | SPACE | BKSP  |  BKSP | SPACE |  ENT  |   +   |   ALT  |   APP  |

SETTINGS 3

| ROW 0  | ROW 1 | ROW 2 | ROW 3 | ROW 4 | ROW 5 | ROW 6 | ROW 7 | ROW 8 | ROW 9 | ROW 10 | ROW 11     |
| -----  | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------     |
|BT SL 0 |BT SL 1|BT SL 2|BT SL 3|BT SL 4|       |       |       |       |       |        | BT_CLR     |
|BT DC 0 |BT DC 1|BT DC 2|BT DC 3|BT DC 4|       |       |       |       |       |        |            |
|        |       |       |       |       |  to4  |  to4  |       |       |       |        |            |
|BootLoad|       |       |       |       | BT PRV| BT NXT|       |       |       |        | BT_CLR_ALL |

NUMPAD 4

| ROW 0 | ROW 1 | ROW 2 | ROW 3 | ROW 4 | ROW 5 | ROW 6 | ROW 7 | ROW 8 | ROW 9 | ROW 10 | ROW 11 |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------ |
| to 0  |  Num+ |       | Num7  | Num8  |  Num9 |  Num7 | Num8  |  Num9 |       |  Num+  | NumLck |
|       |  Num- |       | Num4  | Num5  |  Num6 |  Num4 | Num5  |  Num6 |       |  Num-  | NumEnt |
|       |  Num* |       | Num1  | Num2  |  Num3 |  Num1 | Num2  |  Num3 |       |  Num*  |        |
|  Num/ |  Num. |  Num0 | E nt  | space | BCKSP | BCKSP | space |  Ent  |  Num0 |  Num.  |  Num/  |

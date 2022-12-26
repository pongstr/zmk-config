Lily58 ZMK
---

Getting Started
---

Do this step for both sides of the keyboard:

1. Download the lates firmware build, extract the contents, there are three files:
  - `lily58_left-nice_nano_v2-zmk.uf2`: firmware for the left board
  - `lily58_right-nice_nano_v2-zmk.uf2`: firmware for the right board
  - `settings_reset-nice_nano_v2-zmk.uf2`: [firmware that will reset pairing issues](https://zmk.dev/docs/troubleshooting#split-keyboard-halves-unable-to-pair)
1. Plug in your Left Lily58 board, the OS will detect the keyboard as a flash drive
1. Double tap the reset button to set nice!nano to DFU mode and this is where you will
   have to copy+paste the file:
  - `lily58_left-nice_nano_v2-zmk.uf2`
  - when the transfer completes, unplug the left keyboard
1. Follow the same step as you did with the left keyboard but this time, copy+paste
   the file:
  - `lily58_right-nice_nano_v2-zmk.uf2`
  - when the transfer completes, unplug the right keyboard
1. Press the reset button on the left and right board
1. Start pairing to a host machine

Keymap
---

### Layer 1

```
  QWERTY
  ,-----------------------------------------.                    ,-----------------------------------------.
  | ESC `|   1  |   2  |   3  |   4  |   5  |                    |   6  |   7  |   8  |   9  |   0  | BSPC |
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  | Tab  |   Q  |   W  |   E  |   R  |   T  |                    |   Y  |   U  |   I  |   O  |   P  |  -   |
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  |LShift|   A  |   S  |   D  |   F  |   G  |-------.    ,-------|   H  |   J  |   K  |   L  |   ;  |  '   |
  |------+------+------+------+------+------|   [   |    |    ]  |------+------+------+------+------+------|
  | GRAVE|   Z  |   X  |   C  |   V  |   B  |-------|    |-------|   N  |   M  |   ,  |   .  |   /  |RShift|
  `-----------------------------------------/       /     \      \-----------------------------------------'
                    | LCTRL| LALT | CMD  | /Space  /       \Enter \  | MO1  | MO2  |  MO3 |
                    |      |      |      |/       /         \      \ |      |      |      |
                    `-------------------''-------'           '------''--------------------'
```

### Layer 2

```
  LOWER
  ,-----------------------------------------.                    ,-----------------------------------------.
  |      |      |      |      | HOM  |  END |                    |      |      |      |   -  |   =  | DEL  |
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  |      |      |   ↑  |      | PG_UP| PG_DN|                    |      |      |      |   [  |  ]   |  \   |
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  |      |   ←  |   ↓  |   →  |      |      |-------.    ,-------|  F1  |  F2  |  F3  |  F4  |  F5  |  F6  |
  |------+------+------+------+------+------|   [   |    |    ]  |------+------+------+------+------+------|
  |      | MUTE | VOL- | VOL+ | PAUS | PLY  |-------|    |-------|  F7  |  F8  |  F9  |  F10 | F11  | F12  |
  `-----------------------------------------/       /     \      \-----------------------------------------'
                    |      |      |      | /       /       \      \  |      |      |      |
                    |      |      |      |/       /         \      \ |      |      |      |
                    `-------------------''-------'           '------''--------------------'

```


### Layer 3

```
  RAISE
  ,-----------------------------------------.                    ,-----------------------------------------.
  |      |  BT0 |  BT1 |  BT2 |  BT3 | BT4  |                    |      |      |      |      |      |BTCLR |
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  |  TOG |  ON |  OFF  |      |      |      |                    |      |      |      |      |      |      |
  |------+------+------+------+------+------|                    |------+------+------+------+------+------|
  |  USB | BLE  | U/B  |      |      |      |-------.    ,-------|      |      |      |      |      |      |
  |------+------+------+------+------+------|       |    |       |------+------+------+------+------+------|
  |      |      |      |      |      |      |-------|    |-------|      |      |      |      |      |      |
  `-----------------------------------------/       /     \      \-----------------------------------------'
                    |      |      |      | /       /       \      \  |      |      |      |
                    |      |      |      |/       /         \      \ |      |      |      |
                    `-------------------''-------'           '------''--------------------'
```

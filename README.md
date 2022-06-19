# qmk-neutrino-handwired

*A short description of the keyboard/project*

* Keyboard Maintainer: [Lewys Martin](https://github.com/CountParadox)
* Hardware Supported: Handwired OLKB Neutrino
* Hardware Availability: Legacy / Forgotten tech :(

QMK example for this keyboard (after setting up your build environment):

    qmk compile -kb neutrino -km default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `RESET` if it is available

col:   0    1    2    3   4    5   6   7    8    9   10 11  12  13 14

pin: B7 D0 D1 D2 D3 C6 C7 D5 D4 D6 D7 B4 B5 B6  F7

row:  0  1   2   3   4

pin: F6 F5 F4 F1 F0

    "matrix_pins": {
        "cols": ["B7", "D0", "D1", "D2", "D3", "C6", "C7", "D5", "D4", "D6", "D7", "B4", "B5", "B6", "F7"],
        "rows": ["F6", "F5", "F4", "F1", "F0"]
    },


"bootloader": "halfkay"

Photos of someone elses:

https://imgur.com/a/KhP62

Photos of mine:

https://imgur.com/a/j48tA#qd5nz1B

Matrix:

<img width="791" alt="image" src="https://user-images.githubusercontent.com/6279380/174485454-6bedd84a-1281-4e92-b992-cc3e40cc4a0d.png">

default keymap:

<img width="742" alt="image" src="https://user-images.githubusercontent.com/6279380/174485475-97bfa90d-5b42-4c09-ad00-68d07b13b957.png">


Old problem with stabs:

https://www.reddit.com/r/olkb/comments/4kkopf/neutrino_cherry_stabilizers/

Original blog post:

http://blog.lewys.eu/?p=244

Wiring photos:

https://imgur.com/a/8Ztiw#siNrN25

More photos:

https://imgur.com/a/i5Ba2#Mw1gy4a

kle:

http://www.keyboard-layout-editor.com/#/gists/6227b23302a27248a72a8734696cbd60

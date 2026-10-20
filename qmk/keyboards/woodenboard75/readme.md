# miraculix50/woodenkeys75

*A wooden ISO-DE 75 % keyboard with an EC11 Rotary Encoder.*

* Keyboard Maintainer: [Miraculix50](https://github.com/Miraculix50)
* Hardware Supported: *Custom PCB with 0xcb Helios Microcontroller*
* Hardware Availability: https://github.com/miraculix50/woodenboard75

Make example for this keyboard (after setting up your build environment):

    make miraculix50/woodenboard75:default

Flashing example for this keyboard:

    make miraculix50/woodenboard75:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button under the CapsLock key
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available

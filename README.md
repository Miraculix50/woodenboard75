# Wooden Keyboard
An ISO-DE 75 % keyboard with a wooden case and knob.

![Wooden keyboard](/assets/top_rgb.jpeg)

It's definitely not perfect and I'm sure it could be optimized, but for me it's working great.
Feel free to [build it yourself](#parts).

## Parts
### PCB
* [0xcb Helios with MillMax pins and IC-Sockets (MCU) x1](https://keeb.supply/products/0xcb-helios?variant=f57eeaae-cae7-4b2d-b5ac-bef47a280a65)
* [Hotswap sockets x83](https://keeb.supply/products/kailh-hotswap-sockets)
* [THT diodes x84](https://keeb.supply/products/tht-diodes)
* [Reset button x1](https://keeb.supply/products/2-pin-reset-button)
* [EC11 rotary encoder x1](https://keeb.supply/products/pec11r-4220f-s0024)

**Base version:**
* Base-version PCB (when ordering, upload the [gerber files](/pcb/kicad/woodenboard75/production/keyboard.zip))

**RGB version:**
* RGB-version PCB (when ordering, upload the [gerber files](/pcb/kicad/woodenboard75_rgb/production/keyboard.zip))
* SK6812 MINI-E LEDs x83
* 330 Ω resistor x1
* 100 nF capacitor (SMD 0603) x83
* 22 µF capacitor (SMD 1206) x1

### Keys
* [Switches x83](https://keeb.supply/products/invokeys-matcha-reserve-switches)
* [Keycaps for 75%-layout](https://monacokeys.de/products/monacokeys-mk-retro-beige-pbt-keycap-set)

### Wooden case & knob

CAD files are available in the `/cad` folder (`.step` and `.shapr` format).
Pay attention to the different versions, since the RGB-version of the PCB is not compatible with the base version of the bottom case.

* Bar magnets (4mm diameter + 8mm height) x8
* Top case
* Bottom case
* Knob

> All links are just examples.

## Firmware

This keyboard uses the [QMK Firmware](https://qmk.fm). To get started see the [QMK docs](https://docs.qmk.fm/).

Note that you have to copy the contents of `qmk/keyboards/` to your local qmk clone / fork.

## Images

<img src="/assets/top.png" width="45%"></img> <img src="/assets/pcb_back.jpeg" width="45%"></img> <img src="/assets/arrow_keys.jpeg" width="45%"></img> <img src="/assets/back.jpeg" width="45%"></img> <img src="/assets/top_rgb.jpeg" width="45%"></img> <img src="/assets/top_open_rgb.jpeg" width="45%"></img> <img src="/assets/side_rgb.jpeg" width="45%"></img> <img src="/assets/front_rgb.jpeg" width="45%"></img>

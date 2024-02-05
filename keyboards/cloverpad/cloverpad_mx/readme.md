# cloverpad/cloverpad_mx

![cloverpad/cloverpad_mx](imgur.com image replace me!)

An open source 3-key keypad themed after [MORE MORE JUMP!](https://www.sekaipedia.org/wiki/MORE_MORE_JUMP!) from Project Sekai.

* Keyboard Maintainer: [Jon Pacheco](https://github.com/Ace4896)
* Hardware Supported: Cloverpad MX (rev. 1)
* Hardware Availability: [Cloverpad/cloverpad-hardware](https://github.com/Cloverpad/cloverpad-hardware)

Make example for this keyboard (after setting up your build environment):

    make cloverpad/cloverpad_mx:default

Flashing example for this keyboard:

    make cloverpad/cloverpad_mx:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic Reset**: Hold down the key at (0,0) in the matrix (leftmost key, default is 'Z') and plug in the keypad
* **Physical Reset Button**: Double press the `RST` button on the back of the PCB
* **Physical Boot Select Button**: Hold the `SEL` button on the back of the PCB and plug in the keypad

## VIA Firmware

When compiling, use the `via` keymap instead of `default`.

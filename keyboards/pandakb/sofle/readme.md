# PandaKB Sofle RGB MX Keyboard

![SofleKeyboard version 1](https://raw.githubusercontent.com/josefadamcik/SofleKeyboard/master/Images/IMG_20200126_114622.jpg)

Sofle is 6×4+5 keys column-staggered split keyboard. Based on Lily58, Corne and Helix keyboards.

More details about the keyboard on my blog: [Let me introduce you SofleKeyboard - a split keyboard based on Lily58 and Crkbd](https://josef-adamcik.cz/electronics/let-me-introduce-you-sofle-keyboard-split-keyboard-based-on-lily58.html)

PandaKB is a Chinese manufacturer of Sofle v. 1 keyboard build kits. Their main feature is the microcontroller promicro rp2040.

Build guide: [PandaKB Sofle RGB MX build guide](https://pandakb.com/build-guides/sofle-rgb-mx-build-guide/)

* Hardware Supported: Sofle RGB, ProMicro RP2040
* Hardware Availability: [pandakb.com](https://pandakb.com/product-category/pcb-kit/)

# Compiling

Make example for this keyboard (after setting up your build environment):

    make pandakb/sofle:default

## Flashing

The following steps describe the flushing procedure of the RP2040 microcontroller:

1. Unplug the USB cable.
2. Unplug the TRRS cable.
3. Plug the left half.
4. Double press the reset button to enter bootloader mode. A new disk drive will appear.
5. Simply drag the uf2 file on the drive and wait a few seconds until the board is flashed. Once the flashing is done, the board will reboot into the new firmware.
6. Repeat steps 3-5 for the right side. Use the same ud2 for both sides.


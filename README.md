# Neutrino-8

A super tiny SD card image for the TRIMUI Smart handheld, solely dedicated to running PICO-8 and nothing else.

Booting with this image will drop you right into Splore, no questions asked. Exiting Splore will drop you into the stock MainUI interface with no emulators, which can be used to configure Wi-Fi for connecting to the PICO-8 BBS

## Installation

You'll need a TRIMUI Smart device running firmware version 1.0.0 (older firmwares are untested!) as described in the Quark getting started guide [here](https://quark.cobaltonline.net/getting-started/install/firmware/).

Assuming you have this set up already, just drag and drop this repo into the root of your microSD card, along with your PICO-8 Raspberry Pi binaries (`pico8.dat` and `pico8_dyn`) which can be purchased [here](https://www.lexaloffle.com/pico-8.php?#getpico8).

## Credits

* sagotch: [SDL2 build for PICO-8](https://github.com/sagotch/SDL2-TG2040).
* [spruceUI team](https://github.com/spruceUI): original idea that served as the basis of this project - a stripped down version of spruce that would only run PICO-8.

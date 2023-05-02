LWIP PPP ESPHOME
================

This is a copy of LwIP https://savannah.nongnu.org/projects/lwip/, containing just the ppp part.

This is is needed to make PPP work on RP2040 with earlephilhower's [arduino-pico](https://github.com/earlephilhower/arduino-pico).   
While the base [pico-sdk](https://github.com/raspberrypi/pico-sdk) from the Raspberry Pi foundation does contain lwIP, earlephilhower's core uses a pre-compiled version of it, in the file [lib/libpico.a](https://github.com/earlephilhower/arduino-pico/blob/master/lib/libpico.a). Since PPP is rarely used, it is not included.

This library fixes that by including the PPP source code into your platformio build.

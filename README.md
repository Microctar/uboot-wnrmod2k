This is modified u-boot source for selected Netgear routers based on Atheros SoC and Wifi chips.

I have collected GPL sources from Netgear website, extracted u-boot part from them and compiled into one tree.
I also did a cleanup: there are no compilation errors, warnings, ambigous assignments, unnecessary redundancy.

Following ar71xx/ar724x devices are supported:

* WNR2000v3
* WNR612v2
* WNR1000v2 (v2h2)
* WNR2200
* WNDR3700v1 (u)
* WNDR3700v2 (v1h2)

Compilation requires MIPS toolchain when cross-building on Linux running Intel/AMD CPU. 
Personally I use docker image Slackware 13.37 64-bit and old u-boot recommended MIPS GCC 4.8 compiler/linker.

This source supports building images for 4, 8 and 16 MB flash sizes so all above devices can be modded and equipped with more flash storage than in original model. 
Please restore ART.bin to new flash before you flash this uboot 



See README.netgear for build instructions.

Loader flashing from u-boot prompt (console access required) is described in README.flash.

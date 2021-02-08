<center> <h1> U-BOOT For Selected Netgear Routers </h1> </center>



**[realmicu]** >> *"This is modified u-boot source for selected Netgear routers based on Atheros SoC and Wifi chips."*



### *Rewrite Information*



### Support Devices

| Model             | SoC            | CPU Cores | CPU MHZ | Comments network ports |
| ----------------- | -------------- | --------- | ------- | ---------------------- |
| WNR612V2          | Atheros AR7240 | 1         | 400     | 1 WAN + 2x LAN         |
| WNR1000V2 (v2h2)  | Atheros AR7240 | 1         | 400     | 1 WAN + 4x LAN         |
| WNR2000V3         | Atheros AR7241 | 1         | 400     | 1 WAN + 4x LAN         |
| WNR2200           | Atheros AR7241 | 1         | 360     | 1 WAN + 4x LAN         |
| WNDR3700V1 (u)    | Atheros AR7161 | 1         | 680     | 1 WAN + 4x LAN         |
| WNDR3700V2 (v1h2) | Atheros AR7161 | 1         | 680     | 1 WAN + 4x LAN         |



### Build Environment

| Operating System | Toolchains                                                   |
| ---------------- | ------------------------------------------------------------ |
| Ubuntu Focal     | [OpenWrt SDK for AR71xx MIPS (Chaos Calmer release)](https://downloads.openwrt.org/chaos_calmer/15.05.1/ar71xx/generic/OpenWrt-SDK-15.05.1-ar71xx-generic_gcc-4.8-linaro_uClibc-0.9.33.2.Linux-x86_64.tar.bz2) |



### Notice

**Please restore ART.bin to new flash before you flash this uboot !!!**

**See README.netgear for build instructions.**

**Loader flashing from u-boot prompt (console access required) is described in README.flash.**
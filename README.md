<center> <h1> U-BOOT For Selected Netgear Routers </h1> </center>



**[realmicu]** >> *"This is modified u-boot source for selected Netgear routers based on Atheros SoC and Wifi chips."*



### *Rewrite Information*



### Support Devices

| Model             | SoC            | CPU Cores | CPU MHZ | Comments network ports | Official Firmware                                            | Openwrt Firmware                                             |
| ----------------- | -------------- | --------- | ------- | ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| WNR612V2          | Atheros AR7240 | 1         | 400     | 1 WAN + 2x LAN         | [1.0.0.3](https://www.downloads.netgear.com/files/GDC/WNR612v2/wnr612v2-V1.0.0.3_1.0.2.zip) | [17.01.7](http://downloads.openwrt.org/releases/17.01.7/targets/ar71xx/generic/lede-17.01.7-ar71xx-generic-wnr612v2-squashfs-factory.img) |
| WNR1000V2 (v2h2)  | Atheros AR7240 | 1         | 400     | 1 WAN + 4x LAN         | [1.1.2.60](https://www.downloads.netgear.com/files/GDC/WNR1000V2/WNR1000v2-V1.1.2.60.zip) | [17.01.7](http://downloads.openwrt.org/releases/17.01.7/targets/ar71xx/generic/lede-17.01.7-ar71xx-generic-wnr1000v2-squashfs-factory.img) |
| WNR2000V3         | Atheros AR7241 | 1         | 400     | 1 WAN + 4x LAN         | [1.1.2.18](https://www.downloads.netgear.com/files/GDC/WNR2000v3/wnr2000v3-V1.1.2.18.zip) | [19.07.6](http://downloads.openwrt.org/releases/19.07.6/targets/ar71xx/tiny/openwrt-19.07.6-ar71xx-tiny-wnr2000v3-squashfs-factory.img) |
| WNR2200           | Atheros AR7241 | 1         | 360     | 1 WAN + 4x LAN         | [1.0.1.102](https://www.downloads.netgear.com/files/GDC/WNR2200/WNR2200-V1.0.1.102.zip) | [19.07.6 8Mbytes](http://downloads.openwrt.org/releases/19.07.6/targets/ar71xx/generic/openwrt-19.07.6-ar71xx-generic-wnr2200-squashfs-factory.img)                                                            [snapshot 16Mbytes](http://downloads.openwrt.org/snapshots/targets/ath79/generic/openwrt-ath79-generic-netgear_wnr2200-16m-squashfs-factory.img) |
| WNDR3700V1 (u)    | Atheros AR7161 | 1         | 680     | 1 WAN + 4x LAN         | [1.0.16.98](https://www.downloads.netgear.com/files/GDC/WNDR3700V1/WNDR3700-V1.0.16.98.zip) | [19.07.6](http://downloads.openwrt.org/releases/19.07.6/targets/ath79/generic/openwrt-19.07.6-ath79-generic-netgear_wndr3700-squashfs-factory.img) |
| WNDR3700V2 (v1h2) | Atheros AR7161 | 1         | 680     | 1 WAN + 4x LAN         | [1.0.1.14](https://www.downloads.netgear.com/files/GDC/WNDR3700V2/WNDR3700v2_WNDR37AVv2-V1.0.1.14.zip) | N/A                                                          |



### Build Environment

| Operating System | Toolchains                                                   |
| ---------------- | ------------------------------------------------------------ |
| Ubuntu Focal     | [OpenWrt SDK for AR71xx MIPS (Chaos Calmer release)](https://downloads.openwrt.org/chaos_calmer/15.05.1/ar71xx/generic/OpenWrt-SDK-15.05.1-ar71xx-generic_gcc-4.8-linaro_uClibc-0.9.33.2.Linux-x86_64.tar.bz2) |



### Notice

**Please restore ART.bin to new flash before you flash this uboot !!!**

**See README.netgear for build instructions.**

**Loader flashing from u-boot prompt (console access required) is described in README.flash.**
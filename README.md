# TL-MR3420 v5
Router openwrt mod collection, Model and hardware version availability varies by region. Please refer to your TP-Link regional website to determine product availability.
Vx.0=Vx.6/Vx.8/Vx.9(eg:V1.0=V1.6/V1.8/V1.9)
Vx.x0=Vx.x6/Vx.x8/Vx.x9 (eg:V1.20=V1.26/V1.28/V1.29)
Vx.30=Vx.32/Vx.33 (eg:V3.30=V3.32/V3.33)
```
Mediatek MT7628AN
mipsel_24kc
ramips/mt7628/mt76x8
```
## Raw
```
https://archive.openwrt.org/chaos_calmer/15.05.1/ramips/mt7628
```
# Latest Firmware
## Original
```
https://static.tp-link.com/2018/201808/20180817/TL-MR3420(EU)_V5_180712.zip

https://static.tp-link.com/2018/201801/20180117/TL-MR3420(EU)_v5_170908.zip

https://emulator.tp-link.com/MR3420_V5-2-22/index.htm
```
## OpenWrt
```
https://firmware-selector.openwrt.org/
```
## GoldenOrb
```
http://www.aturnofthenut.com/builds/GoldenOrb

http://www.aturnofthenut.com/builds/GoldenOrb/TP-Link-MR3420v5-GO2023-09-01.zip
```
## Gargoyle
```
https://lantisproject.com/downloads/gargoylebuilds

https://lantisproject.com/storage/gargoylebuilds/1.15.x_20241113/ramips/gargoyle_1.15.x-ramips-mt76x8-tplink_tl-mr3420-v5-squashfs-sysupgrade.bin
https://lantisproject.com/storage/gargoylebuilds/1.15.x_20241113/ramips/gargoyle_1.15.x-ramips-mt76x8-tplink_tl-mr3420-v5-squashfs-tftp-recovery.bin
```
## X-Wrt
```
https://downloads.x-wrt.com/rom

https://downloads.x-wrt.com/rom/x-wrt-24.04-b202411262136-ramips-mt76x8-tplink_tl-mr3420-v5-squashfs-sysupgrade.bin
https://downloads.x-wrt.com/rom/x-wrt-24.04-b202411262136-ramips-mt76x8-tplink_tl-mr3420-v5-squashfs-tftp-recovery.bin
```
SSID : X-WRT_XXXX， Password ：88888888\
Host ：http://192.168.15.1/ \
user : admin\
pass : admin\
SSH : root@192.168.15.1 port:22 pass:admin
## Experimental
```
https://github.com/aimacintyre/gargoyle/releases/tag/ramips-mt76x8-20220925
```
## Extra Opkg
```
https://dl.eko.one.pl/gargoyle-pl/1.14/packages/mipsel_24kc/base

https://dl.eko.one.pl/gargoyle-pl/1.14/packages/mipsel_24kc/luci

https://dl.eko.one.pl/gargoyle-pl/1.14/packages/mipsel_24kc/packages

https://dl.eko.one.pl/gargoyle-pl/1.14/packages/mipsel_24kc/routing

https://dl.eko.one.pl/gargoyle-pl/1.14/packages/mipsel_24kc/telephony
```
## TFTP Server
```
https://www.ofmodemsandmen.com/download/tftpd32.zip

https://www.ofmodemsandmen.com/download/pxesrv.zip
```
Cara Flash : Rename Firmware ke tp_recovery.bin, Ganti IP ke static 192.168.0.225, Buka tftp -> sesuaikan folder & server, cabut charger router tplink, tekan & tahan tombol power & reset kemudian masukkan charger -> tahan tombol selama 6 detik hingga logo kunci nyala, kemudian lepaskan tombol & tunggu proses. selesai.
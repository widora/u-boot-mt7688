# u-boot-mt7688
#### uboot for Widora NEO and BIT module(with simple web)
***
# How to use
* 1.make menuconfig
* 2.select MT7628 board
* 3.make clean;make

### Note
* note:compile need java such as 1.7.0_79
* ntoe:We can also use the "curl" command instead of the browser, Upload the file in the uboot state
```sh
// upload uboot to flash
  $ curl -F uboot=@./uboot.bin -F press="Update U-Boot" 192.168.1.111 > /dev/null 
// upload openwrt to flash
  $ curl -F firmware=@./openwrt.bin -F press="Update firmware" 192.168.1.111 > /dev/null
```

***
* mail: widora@qq.com
* twitter:https://twitter.com/mangopi_sbc
## Thanks to Manfeel、cleanwrt、Piotr Dymac、Adam Dunkels。

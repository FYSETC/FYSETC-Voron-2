# Firmware&OS

## 1. Firmware

There is pre-build firmware named `firmware.bin`, please flash it to Spider board flash address `0x08008000`. You can follow Spider firmware upload instruction here ([github](https://github.com/FYSETC/FYSETC-SPIDER#44--firmware-upload) [gitee](https://github.com/FYSETC/FYSETC-SPIDER#44--firmware-upload)).

And the menuconfig of this pre-build firmware is below.

![](klipper-32k-UART.png)

## 2. Octopi OS

In the kit, you should find an sdcard pre-flashed Octopi system if your kit version is rev1.1 or later. We also provide you this Octopi system image for you. If your kit version is rev1.0 or rev1.1, your Spider board version is 1.x, you can get the responding Octopi system here([1.Dropbox](https://www.dropbox.com/s/vtbbxu55y27kbl7/VORON2.4-Octoprint-Klipper.img?dl=0) [2.百度云盘](https://pan.baidu.com/s/1aeOkN2ZxQb99EaApOWNglw) 提取码：1357) . If your kit version is rev1.2, then your Spider board version is 2.2, and you can get the responding Octopi system here([1.Dropbox](https://www.dropbox.com/s/mn1kvcndi1gpb9v/VORON2.4-Spider2.x-Octoprint-Klipper.img?dl=0) [2.百度云盘](https://pan.baidu.com/s/1OZLoSdPNHbxYGWpk1KwKzA ) 提取码：YYDS). 

### 2.1 how to flash

Before flash, you need an SD card , minimum requirement of SD card capacity is 8G. Please prepare that first. And then you can use this software [here](https://www.balena.io/etcher/) to install. Well that are so many OS flash tool that you can use. And there are a lot of tutorial if you google `how to flash os image`.

### 2.2 OctoPi

You can login in with the following account and password.

```
Account: FYSETC
Password: 12345678
```

OS SSH login account and password

```
Account: pi
Password: raspberry
```

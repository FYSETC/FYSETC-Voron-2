# Firmware&OS

## 1. Firmware

There is pre-build firmware named `firmware.bin`, please flash it to Spider board flash address `0x08008000`. You can follow Spider firmware upload instruction here ([github](https://github.com/FYSETC/FYSETC-SPIDER#44--firmware-upload) [gitee](https://github.com/FYSETC/FYSETC-SPIDER#44--firmware-upload)).

And the menuconfig of this pre-build firmware is below.

![](klipper-32k-UART.png)

## 2. OS

We provide you two OS images choices: Mainsail OS and Octopi OS.

### 2.1 Mainsail OS

You can get the corresponding Mainsail OS here ([1.Dropbox](https://www.dropbox.com/s/y8eb1giik5p6n1d/VORON2.4R2-Spider2.x-Mainsail.zip?dl=0)).

### 2.2 Octopi OS

If your kit version is rev1.0 or rev1.1, your Spider board version is 1.x, you can get the responding Octopi system here([1.Dropbox](https://www.dropbox.com/s/vtbbxu55y27kbl7/VORON2.4-Octoprint-Klipper.img?dl=0) [2.百度云盘](https://pan.baidu.com/s/1aeOkN2ZxQb99EaApOWNglw) 提取码：1357) . If your kit version is rev1.2, then your Spider board version is 2.2, and you can get the responding Octopi system here([1.Dropbox](https://www.dropbox.com/s/mn1kvcndi1gpb9v/VORON2.4-Spider2.x-Octoprint-Klipper.img?dl=0) [2.百度云盘](https://pan.baidu.com/s/1OZLoSdPNHbxYGWpk1KwKzA) 提取码：YYDS).

You can login in Octoprint with the following account and password.

```
Account: FYSETC
Password: 12345678
```

### 2.3 How to flash OS image

Before flash, you need an SD card , minimum requirement of SD card capacity is 8G. Please prepare that first. And then you can use this software [here](https://www.balena.io/etcher/) to install. Well that are so many OS flash tool that you can use. And there are a lot of tutorial if you google `how to flash os image`.

### 2.4 SSH account and password

OS SSH account and password

```
Account: pi
Password: raspberry
```

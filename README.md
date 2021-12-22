# FYSETC-VORON-2.4

![](VORON2.JPG)

## 1. Project

This is FYSETC's project database for VORON 2.4 kit, which is convenient for you to find information. Thanks for VORON Team's great work, they always design fantastic printers.

Official website:：https://vorondesign.com/voron2.4
Official Github：https://github.com/VoronDesign/Voron-2

In folder `Voron-2-Voron2.4` beside this README file, we make some small changes base on the VORON official material. Like change the board to Spider and others. 

## 2. BOM

Please check [here](https://github.com/FYSETC/FYSETC-Voron-2/blob/main/BOM.md).

## 3. Extra parts

Besides the parts in Voron sourcing guide, we offer extra useful parts for you.

### Wire connector

![](Connector.jpg)



This is for fans wire connection, with this connector you can wire two or more fans to one side of the connector, and the other side  to Spider board. Then you can control the two or more fans with one control pin in Spider.

## 4. Printed parts:

You can find all printed parts in VORON [website](https://vorondesign.com/voron2.4), VORON [github](https://github.com/VoronDesign/Voron-2).

Printed parts are not included in our VORON 2.4 kit, in some particular section of the machine, VORON provide you options. Like the plug panel at the back of VORON machine, you can choose [plug_panel](https://github.com/VoronDesign/Voron-2/blob/Voron2.4/STLs/VORON2.4/Electronics_Compartment/Plug_Panel/plug_panel.stl) or [plug_panel_filtered_mains](https://github.com/VoronDesign/Voron-2/blob/Voron2.4/STLs/VORON2.4/Electronics_Compartment/Plug_Panel/plug_panel_filtered_mains.stl). So in our kit, we also need to choose too, below is our choice.

plug panel: we choose this [one](https://github.com/VoronDesign/Voron-2/blob/Voron2.4/STLs/VORON2.4/Electronics_Compartment/Plug_Panel/plug_panel.stl).

Microswitch edge pod : this [one](https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/randell/Microswitch_Endstop/Microswitch_Edge_Pod.stl).

Z Chain mount: our rev1.0 and rev1.1 Chain size is 1011 ,it is different from VORON sourcing size 1015, so we use our own printed part [1](https://github.com/FYSETC/FYSETC-Voron-2/blob/main/Z_Chain_Lower_Mount.STL) and [2](https://github.com/FYSETC/FYSETC-Voron-2/blob/main/Z_Chain_Upper_Mount.STL). 

Spider board mount: search 'Spider' [here](https://faked.org/voronmods/).

## 5. Wiring

### 5.1 Spider 1.x wiring

There is wiring from VORON community [here](https://github.com/shiftingtech/Voron-Documentation/blob/Spider/build/electrical/v2_spider_wiring.md). Also you can refer Spider wiring [here](https://github.com/FYSETC/FYSETC-SPIDER#3-hardware-guide).

***Note: Check your fan voltage before you set the fan jumpers, the jumpers for fan in below diagram are all set to 24v.***

![](v2_spider_wiring.png)

### 5.2 Spider v2.2 wiring

If you use Spider v2.2, follow the wiring below

![](VORON2.4_SPIDER_V22_WIRING.jpg)

### 5.3 XY endstop

![](XY_endstop.jpg)

## 6. Firmware&OS

You can find example Klipper printer.cfg file on VORON github [here](https://github.com/VoronDesign/Voron-2/tree/Voron2.4/firmware/klipper_configurations/Spider) or our Spider github [here](https://github.com/FYSETC/FYSETC-SPIDER/blob/main/firmware/Klipper/printer.cfg). And you can get our pre-build firmware in the `firmware&OS` folder next to this README file. 

### 6.1 OctoPi

We provide a SD card with OctoPi installed after rev1.1. You can login in with the following account and password.

```
Account: FYSETC
Password: 12345678
```

Also we provide you Octopi OS system image for you, please check the README in `firmware&OS` folder.

OS SSH login account and password

```
Account: pi
Password: raspberry
```

## 7. Where to buy the kit

[Aliexpress](https://www.aliexpress.com/item/1005002782065110.html)

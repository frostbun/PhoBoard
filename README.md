# Phở Bòard

![QMK](image/qmk.png)
![VIA](image/via.png)
![Vial](image/vial.png)

## Case & Plate

Updating ...

## Materials

Material | Quantity
---|---
SparkFun Pro Micro 5V/16MHz | 1
Any MX Style Switch | 62
2U Stabilizer | 4
1N4148 Diode | 62
SSD1306 OLED 128x32 | 1

## Wiring

[KLE](http://www.keyboard-layout-editor.com/#/gists/4cfd5da9ece87a8a6bd2f5c80a84bed2)
Updating ...

## Firmware & Flashing

Clone my fork of [Vial](https://github.com/frostbun/vial-qmk)
```bash
git clone https://github.com/frostbun/vial-qmk.git
```

Cd into the directory
```bash
cd vial-qmk
```

Clone the submodules
```bash
make git-submodule
```

Put the Pro Micro into bootloader mode by connecting GND and RST pins together 2 times

Build & flash the firmware
```bash
make frostbun/phoboard:vial:flash
```

## Keymap

[Download Vial](https://get.vial.today/download/) or [Start Vial Web](https://vial.rocks/)

**Enjoy!**

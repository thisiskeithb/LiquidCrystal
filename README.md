# Liquid Crystal OLED Library for Arduino

Winstar WEH002004 20x4 OLED LCD fix for Marlin `2.0.7.2` or newer on LPC1768/9

## Installation

Locate `MarlinFirmware/ini/lpc176x.ini` and replace the following:

```ini
custom_marlin.USES_LIQUIDCRYSTAL = LiquidCrystal=[some url here]
```

with:

```ini
custom_marlin.USES_LIQUIDCRYSTAL = LiquidCrystal=https://github.com/thisiskeithb/LiquidCrystalOLED/archive/1.0.8.zip
```

## About

This library allows an Arduino board to control LiquidCrystal displays (LCDs) based on the Hitachi HD44780 (or a compatible) chipset, which is found on most text-based LCDs.

For more information about this library please visit us at
http://www.arduino.cc/en/Reference/LiquidCrystal

## License

Copyright (C) 2006-2008 Hans-Christoph Steiner. All rights reserved.
Copyright (c) 2010 Arduino LLC. All right reserved.

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA 02110-1301 USA

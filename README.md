# Arduino Core for SAMD21 and SAMD51 CPU (+SAME51 Fork)

This fork contains files for running a SAME51 processor using Adafruit/Arduino SAMD BSP files

Bossa does not support SAME51 CPUs, modified source here...
https://github.com/deezums/BOSSA

Arduino CMSIS-Atmel files do not contain SAME51 data, modified source here...
https://github.com/deezums/ArduinoModule-CMSIS-Atmel


This repository contains the source code and configuration files of the Arduino Core
for Atmel's SAMD21 and SAMD51 processor (used on the Arduino/Genuino Zero, MKR1000 and MKRZero boards).

In particular, this adds support for the Adafruit SAMD Boards such as the Feather M0

## Bugs or Issues

* AREF must be tied to 3.3V for dac to work. This is a bug in the SAMD51 silicon.
* USB host mode doesn't work yet

If you find a bug you can submit an issue here on github:

https://github.com/adafruit/ArduinoCore-samd

or if it is an issue with the upstream:

https://github.com/arduino/ArduinoCore-samd/issues

Before posting a new issue, please check if the same problem has been already reported by someone else
to avoid duplicates.

## License and credits

This core has been developed by Arduino LLC in collaboration with Atmel.

```
  Copyright (c) 2015 Arduino LLC.  All right reserved.

  This library is free software; you can redistribute it and/or
  modify it under the terms of the GNU Lesser General Public
  License as published by the Free Software Foundation; either
  version 2.1 of the License, or (at your option) any later version.

  This library is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
  See the GNU Lesser General Public License for more details.

  You should have received a copy of the GNU Lesser General Public
  License along with this library; if not, write to the Free Software
  Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
```

# Arduino Core for ArancinoV Boards

This repository contains the source code and configuration files of the Arancino V12 Board
for ST's STM32H743 processor.

## Installation on Arduino IDE

This core is available as a package in the Arduino IDE cores manager. If you want to install it:

  1. Open the **Preferences** of the Arduino IDE.
  2. Add this URL `https://raw.githubusercontent.com/smartmeio/arancino-boards/dev/package_smartmeio_index.json` in the **Additional Boards Manager URLs** field, and click OK.
  3. Open the **Boards Manager** (menu Tools->Board->Board Manager...)
  4. Install **Arancino V Boards**
  5. Select one of the boards under **Arancino Boards** in Tools->Board menu
  6. Compile/Upload as usual

## Configuration of the board
Before upload make sure if this options are enabled.

  1. On **tools** of the Arduino IDE,check if the **U(S)ART support** is set to **ENABLED(generic 'Serial')**
  2. On **tools** of the Arduino IDE,check if the **USB support** is set to **CDC(generic 'Serial' supersede U(S)ART)**

## Installation on Platform.IO and Visual Studio Code

_Work in progress_


## License and credits

This core has been developed by STM32Duino(`https://github.com/stm32duino`), 
and customized by smartme.IO s.r.l.

```
  Copyright (c) 2019 smartme.IO.  All right reserved.

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



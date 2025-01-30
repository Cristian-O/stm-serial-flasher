<img src='https://raw.githubusercontent.com/Gamadril/stm-serial-flasher/master/public/res/logo_128.png' width='40px' height='40px' /> Web STM Flasher (serial)
==================

STM serial flasher is a [Web App](https://cristian-o.github.io/stm-serial-flasher/)  for programming the STM controllers using the embedded ROM bootloader over a serial port. It uses Chrome's Web Serial API and works only with browsers based on Chromium like Chrome, Edge and Opera.
The app supports STM8 and STM32 microcontrollers. 

Requirements
------------
Latest Chromium based Browsers (Chrome, Opera, Edge). Current code base was tested on Chrome v93.

Open the [Web App](https://gamadril.github.io/stm-serial-flasher/)


Device connection
-----------------
## Connection of tested boards
### stm32f4-discovery
| Device | Host |
| ------ | ---- |
| GND    | GND  |
| PB10   | RX   |
| PB11   | TX   |
| NRST   | DTR  |
| BOOT0  | RTS  |



3rd party components
--------------------
Icons:
[SMD 64 pin Icon](http://www.iconarchive.com/show/electronics-icons-by-double-j-design/SMD-64-pin-icon.html) by [Double-J Design](http://www.doublejdesign.co.uk/) is licensed under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/)

Bulma:
[License](https://github.com/jgthms/bulma/blob/master/LICENSE)

Svelte:
[License](https://github.com/sveltejs/svelte/blob/master/LICENSE)

Font Awesome:
[License](https://github.com/FortAwesome/Font-Awesome/blob/master/LICENSE.txt)

Erase_Write_Routines for STM8:
are taken from STM's Flash loader demonstrator (UM0462/STSW-MCU005)

License
-------
MIT license, see [LICENSE](./LICENSE)

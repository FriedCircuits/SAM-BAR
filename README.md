# SAM-BAR
SAM-BAR (**S**mart **A**tmel **M**icrocontroller **B**oot **A**ssistant **R**eloaded) is a bootloader for Atmel/Microchip SAMD21 devices.
It is based on the following bootloaders:
* [SAM-BA (AppNote AT07175) by Atmel/Microchip (www.atmel.com)](http://www.atmel.com/images/Atmel-42366-SAM-BA-Bootloader-for-SAM-D21_ApplicationNote_AT07175.zip)
* [Arduino Zero Bootloader by Arduino LLC (www.arduino.cc)](https://github.com/arduino/ArduinoCore-samd/tree/master/bootloaders/zero)
* [SAMD-MSD-Bootloader by Justin Mattair (www.mattairtech.com)](https://github.com/mattairtech/SAMD-MSD-Bootloader)


## Features
* Compatible with Atmel/Microchip SAM-BA Bootloader and Arduino Zero/MKR1000 Bootloader (USB CDC)
* Mass-Storage-Device Bootloader (USB MSD/MSC)
* Fits in 16KB (user program start at 0x4000)


## Software
* [Bootloader Source Code](https://github.com/watterott/SAM-BAR/tree/master/software/bootloader)
* [Board Support Package for Arduino IDE](https://github.com/watterott/SAM-BAR/tree/master/software/arduino)

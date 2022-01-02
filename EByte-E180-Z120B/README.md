# EByte E180-Z120B and E180-ZG120B-TB

**[E180-ZG120B](http://www.ebyte.com/en/product-view-news.aspx?id=842)** SMD module and **[E180-ZG120B-TB](http://www.ebyte.com/en/product-view-news.aspx?id=896)** evaluation board from **EByte** are both shipped with a proprietary firmware. 

To update them with an standard EZSP NCP application based firmware you have to first use a JTAG/SWD debug probe adapter and SWD flasher software at least once to upload a new standard bootloader. When uploading the bootloader for the very first time, recommend use the _combined.s37_ image from this project.

How-to program the bootloader is out-of-scope for this readme file, however seperate how-to guides are welcome. As an example, you could use https://github.com/myelin/arduino-cmsis-dap and [Open On-Chip Debugger](http://openocd.org/) to SWD flash.


## efr32mg1b-bootloader
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- PB12/UART_BUTTON_RESET is bootloader activiation pin/button
- Version 1.10.3
- DCDC

## efr32mg1b-v8-676-57600
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.7.6
- DCDC

## efr32mg1b-v8-678-57600
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.7.8
- DCDC


## efr32mg1b-v8-6910-57600
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.9.1.0
- DCDC

## efr32mg1b-v8-6910-115200
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.9.1.0
- DCDC

## efr32mg1b-latest-57600
- EmberZNet 6.8.2.0
- Everything else is same as above


## efr32mg1b-latest-115200
- EmberZNet 6.8.2.0
- Everything else is same as above


Configuration Parameter | Value
----------------------- | ------
Address Table Size | 16
Child Table Size | 32
Source Routes | 200

The remaining parameters are at the default values.


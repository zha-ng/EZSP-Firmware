# EByte-E180-Z120B

**EByte-E180-Z120B** comes with a proprietary firmware. To update it with an EZSP based firmware you have to use a SWD Flasher at least once to upload the bootloader.
When uploading the bootloader for the very 1st time, use the _combined.s37_ image.
How to program the bootloader is out of the scope, however how-to updates are welcome. See https://github.com/myelin/arduino-cmsis-dap and [Open On-Chip Debugger](http://openocd.org/)


## efr32mg1b-bootloader
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- Version 1.10.3
- DCDC

## efr32mg1b-v8-676-57600
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.7.6
- DCDC

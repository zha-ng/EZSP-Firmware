# EZSP Development Firmwares

## Usage

 * Install [elelabs-zigbee-ezsp-utility](https://github.com/Elelabs/elelabs-zigbee-ezsp-utility)
 * Download firmware
 * `python Elelabs_EzspFwUtility.py flash -p /dev/select/correct/tty-device -f 'path/to/firmware.gbl'`

## Boards

### Elelabs-ELU013 and ELR023
#### efr32mg1b-bootloader

- EFR32MG13P target
- Standalone Bootloader
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- Version: 1.10.3
- no DCDC


#### efr32mg13p-v8-676-sw-115200

- EFR32MG13P target
- NCP Software flow control, 115200 baudrate
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.7.6
- no DCDC


#### efr32mg13p-v8-676-sw-57600
- EFR32MG13P target
- NCP Software flow control, 57600 baudrate
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.7.6
- no DCDC


### EByte-E180-Z120B

#### efr32mg1b-bootloader
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- PB12/UART_BUTTON_RESET is bootloader activiation pin/button
- Version 1.10.3
- DCDC

#### efr32mg1b-v8-676-57600
- EFR32MG1B target
- NCP UART TX --> PA0
- NCP UART RC <-- PA1
- EZSP Version 8
- EmberZNet 6.7.6
- DCDC

# Wheelbase

## Components

### BLDC driver

https://www.mouser.ee/ProductDetail/Texas-Instruments/DRV8353FSRTAR?qs=hd1VzrDQEGj9xu7LrY%252BpOw%3D%3D

#### Mosfets

 DI025N06PT-AQ 
 https://www.mouser.ee/ProductDetail/Diotec-Semiconductor/DI025N06PT-AQ?qs=Y0Uzf4wQF3lNF%252Ba3rVyVBQ%3D%3D

### Oscillator

830205889709
https://www.mouser.ee/ProductDetail/Wurth-Elektronik/830205889709?qs=hWgE7mdIu5QkPZnGbsg1Rg%3D%3D

### USB C connector

https://www.mouser.ee/ProductDetail/Amphenol-FCI/10155435-00011LF?qs=vHuUswq2%252BswoQuNbiiIX%2FQ%3D%3D

### LDO Voltage Regulator
https://www.mouser.ee/ProductDetail/onsemi/NCP164CSN330T1G?qs=xZ%2FP%252Ba9zWqbi%2FAyy5UtoRw%3D%3D


### MCU STM32U575CIT6Q

https://www.mouser.ee/ProductDetail/STMicroelectronics/STM32U575CIT6Q?qs=DRkmTr78QAT0UsRl49Wtdg%3D%3D



## Pins

* SPI pins for data
* 3x2xGPIO pin for drivers
* 3xPWM for drivers


TOTAL NEEDED FROM STM32: 9(drivers)+ 3CS + SPI =13

### Encoders

* +5V
* DATA
* CLOCK
* GND
* CS


## TODO

* ST-link-i jaoks 4 pini või hackida midagi kokku läbi usb ühenduse?
* USB connection

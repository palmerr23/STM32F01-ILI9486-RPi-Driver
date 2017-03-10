A driver for the STM31F1xx series boards, to enable 3.5" TFT displays sold as "Raspberry Pi" due to having a customised RPi GPIO connector.

The interface is 16 bit serial, with 2 x 8 bit shift registers feeding a 16 bit parallel display module.

Most of the ones I have seen also have XPT2046 touch controllers, which share most of the SPI pins in the ususal way.

minime found that the most up to date SPI drivers are needed (10 March 2017). They were available at that time from 
https://github.com/stevstrong/Arduino_STM32/tree/master/STM32F1/libraries/SPI
and are most likely mainstream at a later date.

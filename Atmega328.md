# Introduction #

Inputs used by this project


# Details #

Add your content here.  Format your content with:
  * Serial: 0 (RX) and 1 (TX). Used to receive (RX) and transmit (TX) TTL serial data. These pins are connected to the corresponding pins of the FTDI USB-to-TTL Serial chip.
  * PWM: 3, 5, 6, 9, (10, and 11). Provide 8-bit PWM output with the analogWrite() function.
  * LED: 13. There is a built-in LED connected to digital pin 13. When the pin is HIGH value, the LED is on, when the pin is LOW, it's off
  * SPI: 10 (SS), 11 (MOSI), 12 (MISO), 13 (SCK). These pins support SPI communication, which, although provided by the underlying hardware, is not currently included in the Arduino language.

Ditial I/O pin usage:
  * 00 RX
  * 01 TX
  * 02 LED 01
  * 03 LED 02
  * 04 LED 03
  * 05 LED 04
  * 06 LED 05
  * 07 LED 06
  * 08 LED 07
  * 09 LED 08
  * 10 SPI - SS
  * 11 SPI - MOSI
  * 12 SPI - MISO
  * 13 SPI - SCK

Analog input pin usage:
  * 00 input 1 - 4
  * 01 input 5 - 8
  * 02 free ( temp sensor ? )
  * 03 free ( light sensor - pir sensor ? )
  * 04 free - I2C - SDA
  * 05 free - I2C -  SCL
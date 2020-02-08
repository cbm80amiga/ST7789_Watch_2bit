# ST7789_Watch_2bit
Analog Watch/Clock with Arduino and and ST7789 IPS

YouTube videos: 

https://youtu.be/jFGDFuLhdMc 

https://youtu.be/35Z0enhEYqM 

## BOM
- ST7789 IPS display
- Arduino Pro Mini
- DS1307 or DS3231 RTC module
- a button 

# Features
- watch dial bitmap is reduced to 2 bits per pixel (4 colors) to fit in Arduino Pro Mini flash memory
- the bitmap in 240x240x2 bits uses only 14400 bytes, full project uses 30700 bytes
- a few alternative 2-bit dials
- watch hands are are vector based
- no floating-point arithmetic and slow trigonometric functions were used

## Connections:

|LCD pin|LCD pin name|Arduino|
|--|--|--|
 |#01| GND| GND|
 |#02| VCC |VCC (3.3V only!)|
 |#03| SCL |D13/SCK|
 |#04| SDA|D11/MOSI|
 |#05| RES|D9 or any digital|
 |#06| DC|D10 or any digital|
 |#07| BLK | NC|

If you find it useful and you want to buy me a coffee or a beer:

https://www.paypal.me/cbm80amiga

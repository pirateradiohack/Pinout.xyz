<!--
---
name: transistor
class: board
type: audio
manufacturer: PirateRadio
description: DIY open source web radio receiver
github: https://github.com/pirateradiohack/Transistor
image: 'transistor.png'
pincount: 40
eeprom: no
power:
  '1':
    name: OOS / AZ
  '2':
    name: OOS / PA
ground:
  '6':
    name: OOS / AZ
  '9':
    name: OOS / AZ
  '14':
    name: AZ
  '20':
    name: AZ
  '25':
    name: AZ / PA
  '30':
    name: AZ
  '34':
    name: AZ
  '39':
    name: AZ / PA
pin:
  '7':
    name: Shutdown OOS
    mode: output
    active: low
  '11':
    name: Power Button OOS
    mode: input
    active: low
  '12':
    name: I2S PA
  '18':
    name: Volume Down
    mode: output
    active: high
  '19':
    name: spi AZ / LCD MOSI PA
    mode: spi
  '21':
    name: spi AZ / LCD DATA PA
    mode: spi
  '22':
    name: Amp Enable PA
  '23':
    name: spi AZ / LCD SCLK PA
    mode: spi
  '24':
    name: spi AZ
    mode: spi
  '26':
    name: LCD SPI PA
    mode: spi
  '29':
    name: Previous
    mode: input
    active: low
  '31':
    name: Play/Pause
    mode: input
    active: low
  '33':
    name: LCD Backlight PA
    mode: input
    active: low
  '35':
    name: I2S PA
  '36':
    name: Volume Up
    mode: input
    active: low
  '37':
    name: Next
    mode: input
    active: low
  '40':
    name: I2S PA
install:
  'devices':
  - 'i2s'
  - 'spi'
-->
# Transistor

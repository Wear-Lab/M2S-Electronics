# M2S-Electronics
Electronics for the M2S Armband

## Details

This are the EAGLE files used to manufacture the four channel amplifier board
for the M2S Armband.

## JLCPCB manufacturing files

Files used to manufacture the PCB, including Gerber files, BOM, and PnP are
located in the JLCPCB folder.

## 2.5mm TRS Connectors

This board uses 2.5mm Right Angle TRS Connectors, commonly used with audio, 
for receiving analog signals. An example part compatible with this board is the
[SJ1-2503A by Same Sky](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices/SJ1-2503A/738680)

## I2C Addresses

This board should have its I2C address set prior to use. To do this, short
one of the jumpers located near the STEMMA QT connectors to select an I2C
Address.

Up to four devices can be hooked up to the same I2C bus.

## I2C Fast Mode

To utilize the full potential of this board, make sure that I2C Fast Mode is
enabled. This ensures that the analog signals are recorded at its designed
maximum speed.

## Electrodes

Electrodes used in the M2S project are based on [DFRobot Gravity Analog EMG
Sensor by OYMotion](https://www.dfrobot.com/product-1661.html).
Eight of these Electrodes are used in the project.

[Wiki page](https://wiki.dfrobot.com/analog_emg_sensor_by_oymotion_sku_sen0240)

## License

This project is licensed under CC BY-NC-SA 4.0. To view a copy of this license,
visit https://creativecommons.org/licenses/by-nc-sa/4.0/

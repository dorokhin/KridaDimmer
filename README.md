# KridaDimmer

Simple python software for manipulate 4 channel i2c Krida Electronics dimmer
for Banana Pro board, may also work with Raspberry Pi


![alt text][img_dimmer]


___
**LightWare** lamp management system ;)


![alt text][img_lightware]

___

**REQUIREMENTS**

smbus

`pip install smbus`
___

**USAGE:**

$chmod +x ./dimmer.py

$./dimmer.py channel_num dimming_value

**Example**

`./dimmer.py 1 50  # set 1-st channel 50 % of power`


[img_dimmer]: https://github.com/andrewnsk/KridaDimmer/blob/master/img/dimmer.jpg?raw=true "Krida dimmer"

[img_lightware]: https://github.com/andrewnsk/KridaDimmer/blob/master/img/lightware.jpg?raw=true "lightware"



___
**Copyright (c) 2016 Andrew Dorokhin**

**MIT License**

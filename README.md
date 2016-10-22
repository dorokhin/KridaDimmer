# KridaDimmer

Simple python software for manipulate 4 channel i2c Krida Electronics dimmer
for Banana Pro board, may also work with Raspberry Pi

**REQUIREMENTS**

smbus

`pip install smbus`
___

**USAGE:**

$chmod +x ./dimmer.py

$./dimmer.py channel_num dimming_value

**Example**

`./dimmer.py 1 50  # set 1-st channel 50 % of power`

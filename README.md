Servo Shield for the WeMos D1 Mini
==================================

Copyright 2016 SuperHouse Automation Pty Ltd  
SuperHouse site:  www.superhouse.tv  
SuperHouse email: info@superhouse.tv  

A 16-channel servo controller shield for the [WeMos D1 Mini][1] 
and other compatible boards based on the same header format.

Features:

 * 16 PWM output channels at 3.3V.
 * I2C interface with pull-up resistors.
 * Configurable I2C address to allow stacking. Default address 0x40.
 * PCA9685 PWM controller IC.
 * SDA: D5. SCL: D4.
 * External power terminals for powering servos at 6V.
 * Power jumper to link D1 Mini 5V rail to servo power.
 * OE (active low Output Enable) broken out for manual connection if required.
 * Power LED to show when servo power is available.

![Oblique view](https://raw.githubusercontent.com/SuperHouse/D1MSERVO/master/images/D1MSERVO-oblique-v1_0.png)

![Top view](https://raw.githubusercontent.com/SuperHouse/D1MSERVO/master/images/D1MSERVO-top-v1_0.png)

![Bottom view](https://raw.githubusercontent.com/SuperHouse/D1MSERVO/master/images/D1MSERVO-bottom-v1_0.png)

More information is available at:

  http://www.superhouse.tv/d1mservo


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.


[1]: http://www.wemos.cc/wiki/doku.php?id=en:d1_mini


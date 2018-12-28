# servoDuino
An Arduino sketch to serve as an USB-I2C-bridge for PCA9685 servo shields

This is mainly intended to control marble runs standalone (then with a dedicated sketch) or to serve in conjunction with [startIDE](https://github.com/PeterDHabermehl/startIDE) on a [TX-Pi](https://github.com/harbaum/tx-pi).

![servoDuino](https://github.com/PeterDHabermehl/servoDuino/blob/master/Bilder/DSC_1339.JPG)

[stl-files to print the case available here!](https://github.com/PeterDHabermehl/servoDuino/tree/master/stl)

Parts and wiring:
![wiring](https://github.com/PeterDHabermehl/servoDuino/blob/master/Bilder/DSC_1334_Wiring.jpg)


a) The diode I used was a 1N4004


b) Adjust the output voltage of the step down converter to ~5V **before** connecting


c) You might adjust the voltage to slightly above 5V, so that the voltage drop at the diode will be compensated for the arduino and the servo shield power terminals are still below 6V


d) You'll need 2 "Bundhülsen" (flush sleeves) 8,4mm long for the power input. If you just get longer ones, carefully shorten them to fit.

Good luck!

BTW, have a look at the [LEDs](https://github.com/PeterDHabermehl/servoDuino/blob/master/Doku/LEDs.pdf)




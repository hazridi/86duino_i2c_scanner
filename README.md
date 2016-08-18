# Notes #

This sketch is just a one line change from the default arduino I2C scanner sketch because 86Duino systems scanning addresses under 8 will cause the sketch to lock up the board.

86Duino also uses 3.3V native I2C and while using 5V I2C devices, you may need to connect 1.8K or 4.7K ohm (1K8/4K7) pullup resistors between both SCL/SDL and 5V. 

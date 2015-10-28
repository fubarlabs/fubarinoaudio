# PWMAudio with the Fubarino Mini
How to convert wav files to c header files that can play as sound on the chipKIT board the Fubarino Mini

The Fubarino Mini and Fubarino SD are chipKIT boards and information for the can be found on the chipKIT Wiki. http://chipkit.net/wiki.

For this tutorial we will be using chipKIT-core. This a downloadable module for the Arduino IDE. To get started you'll need the following:

* Arduino IDE 1.6.5 or greater
 * http://arduino.cc
* chipKIT-core for your operate operating system
 * http://chipkit.net/wiki/index.php?title=ChipKIT_core
* The obtain the libray PWMAudio 
 * https://github.com/MajenkoLibraries/PWMAudio 

Then you'll need to locate wave files from the web. You can also create them from Puredata, Audacity, and/or Sox.

Once you have you wave file you will need to convert it to a c header file.
* https://github.com/ricklon/wav2c

Inside your ~/Documents/Arduino folder:
Put chipKIT-core into ~/Documents/Arduino/hardware

Put PWMAudio into ~/Documents/Arduino/libraries



# Arduino-mk-Digispark
Hi bro, i'm just edited Arduino-Makefile from https://github.com/sudar/Arduino-Makefile (Arduino.mk file)
Yaap, this is Digispark support!<br>
See different about Arduino.mk ori and Arduino.mk edited <https://github.com/pymobile/Arduino-mk-Digispark/commits/master/Arduino.mk><br>
<br>
# First steps
* Make sure you have installed following packages: build-essential libusb++-dev libusb-dev avr-gcc avr-libc
* Build micronucleus commandline, just type 'make;make install' in commandline folder <https://github.com/micronucleus/micronucleus> and chmod 0755 to /usr/local/bin/micronucleus
* Download this repo <https://github.com/pymobile/Arduino-mk-Digispark/archive/master.zip>
* Download Digispark with board.txt here <https://github.com/digistump/DigistumpArduino/releases/download/1.6.5a/digistump-avr.zip> or <https://github.com/digistump/DigistumpArduino/releases/download/1.6.5a/digistump-sam.zip>, then extract it to this repo folder. rename 1.6.5a into 'digispark'

# How to use
  Please reffer to https://github.com/sudar/Arduino-Makefile for more info, i just give you Makefile example for Digispark (ATTiny85). see example folder, cd it and type 'make upload'
# Run on Android, why not?
  Make sure your phone is support USB Host. Install <https://play.google.com/store/apps/details?id=ru.meefik.linuxdeploy> and install the distro



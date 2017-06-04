# MiCa788_ArduinoBootloader

 
avrdude -v -patmega328p -cstk500v1 -P/dev/ttyACM3 -b19200 -U flash:w:optiboot_atmega328.hex -Ulock:w:0x0F:m



avrdude -v -patmega328p -cstk500v1 -P/dev/ttyACM3 -b19200 -U flash:w:optiboot_atmega328.hex -Ulock:w:0x0F:m

# MiCa788_ArduinoBootloader

avrdude >= 6.3 

avrdude -v -patmega328p -cstk500v1 -P/dev/ttyACM0 -b19200 -e -Ulock:w:0x3F:m -Uefuse:w:0xFD:m -Uhfuse:w:0xDE:m -Ulfuse:w:0xFF:m



avrdude -v -patmega328p -cstk500v1 -P/dev/ttyACM0 -b19200 -U flash:w:optiboot_atmega328.hex -Ulock:w:0x0F:m

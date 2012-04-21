PORT=/dev/ttyUSB0
BOARD = atmega328

UPLOAD_PROTOCOL = avrispmkII
UPLOAD_SPEED    = 115200
# fuses: avrdude -c avrispmkII -P usb -p m328p -U lfuse:w:0xf7:m -U hfuse:w:0xd1:m -U efuse:w:0xff:m

# GLFAG = 
# OFLAG = -Os
AVRDUDECONFIG = -D -C /etc/avrdude.conf
SKETCHBOOK    = .
ARDUINO       = $(SKETCHBOOK)
HARDWARE_DIR  = $(SKETCHBOOK)/arduino
#BUILDROOT     = ./build

include $(SKETCHBOOK)/arduino/Arduino.mk

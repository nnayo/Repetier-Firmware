ARDUINO_DIR   = /usr/share/arduino
#ARDMK_DIR     = /usr/share/arduino
ARDMK_DIR     = ~/TRoll/projets/arduino_makefile/arduino-mk
ARDMK_PATH    = ~/TRoll/projets/arduino_makefile/bin
AVR_TOOLS_DIR = /usr


BOARD_TAG = mega2560
#BOARD_TAG = atmega1280
MONITOR_PORT = /dev/ttyUSB0
MONITOR_BAUDRATE = 115200
ARDUINO_LIBS = 

CPPFLAGS += -Wextra -g
#CPPFLAGS += -Wextra -Werror

LDFLAGS += -Wl,--undefined=_mmcu,--section-start=.mmcu=0x800000

include $(ARDMK_DIR)/Arduino.mk

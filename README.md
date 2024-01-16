Currently generates the following errors:
```
 *  Executing task: platformio run 

Processing digispark-tiny (platform: atmelavr; board: digispark-tiny; framework: arduino)
--------------------------------------------------------------------------------------------------------------------------------------------------------
Verbose mode can be enabled via `-v, --verbose` option
CONFIGURATION: https://docs.platformio.org/page/boards/atmelavr/digispark-tiny.html
PLATFORM: Atmel AVR (3.3.0) > Digispark USB
HARDWARE: ATTINY85 16MHz, 512B RAM, 5.87KB Flash
DEBUG: Current (simavr) On-board (simavr)
PACKAGES: 
 - framework-arduino-avr-digistump @ 1.7.2 
 - toolchain-atmelavr @ 1.70300.191015 (7.3.0)
LDF: Library Dependency Finder -> https://bit.ly/configure-pio-ldf
LDF Modes: Finder ~ chain, Compatibility ~ soft
Found 26 compatible libraries
Scanning dependencies...
Dependency Graph
|-- AceRoutine @ 1.5.1
Building in release mode
Compiling .pio/build/digispark-tiny/src/main.cpp.o
Archiving .pio/build/digispark-tiny/lib2ec/libAceCommon.a
Compiling .pio/build/digispark-tiny/libfea/AceRoutine/ace_routine/Coroutine.cpp.o
Indexing .pio/build/digispark-tiny/lib2ec/libAceCommon.a
Compiling .pio/build/digispark-tiny/libfea/AceRoutine/ace_routine/LogBinProfiler.cpp.o
Compiling .pio/build/digispark-tiny/libfea/AceRoutine/ace_routine/LogBinTableRenderer.cpp.o
In file included from .pio/libdeps/digispark-tiny/AceCommon/src/AceCommon.h:55:0,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/ace_routine/Coroutine.h:30,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/AceRoutine.h:49,
                 from src/main.cpp:8:
.pio/libdeps/digispark-tiny/AceCommon/src/print_str/PrintStr.h:130:10: error: 'void ace_common::PrintStrBase::flush()' marked 'override', but does not override
     void flush() override {
          ^~~~~
In file included from .pio/libdeps/digispark-tiny/AceCommon/src/AceCommon.h:55:0,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/ace_routine/Coroutine.h:30,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/ace_routine/Coroutine.cpp:25:
.pio/libdeps/digispark-tiny/AceCommon/src/print_str/PrintStr.h:130:10: error: 'void ace_common::PrintStrBase::flush()' marked 'override', but does not override
     void flush() override {
          ^~~~~
Compiling .pio/build/digispark-tiny/libfea/AceRoutine/ace_routine/testing/TestableClockInterface.cpp.o
Compiling .pio/build/digispark-tiny/FrameworkArduinoVariant/pins_arduino.c.o
In file included from .pio/libdeps/digispark-tiny/AceCommon/src/AceCommon.h:55:0,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/ace_routine/Coroutine.h:30,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/ace_routine/LogBinProfiler.h:30,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/ace_routine/LogBinProfiler.cpp:25:
.pio/libdeps/digispark-tiny/AceCommon/src/print_str/PrintStr.h:130:10: error: 'void ace_common::PrintStrBase::flush()' marked 'override', but does not override
     void flush() override {
          ^~~~~
In file included from .pio/libdeps/digispark-tiny/AceCommon/src/AceCommon.h:55:0,
                 from .pio/libdeps/digispark-tiny/AceRoutine/src/ace_routine/LogBinTableRenderer.cpp:26:
.pio/libdeps/digispark-tiny/AceCommon/src/print_str/PrintStr.h:130:10: error: 'void ace_common::PrintStrBase::flush()' marked 'override', but does not override
     void flush() override {
          ^~~~~
Compiling .pio/build/digispark-tiny/FrameworkArduino/HardwareSerial.cpp.o
*** [.pio/build/digispark-tiny/libfea/AceRoutine/ace_routine/Coroutine.cpp.o] Error 1
*** [.pio/build/digispark-tiny/src/main.cpp.o] Error 1
*** [.pio/build/digispark-tiny/libfea/AceRoutine/ace_routine/LogBinProfiler.cpp.o] Error 1
*** [.pio/build/digispark-tiny/libfea/AceRoutine/ace_routine/LogBinTableRenderer.cpp.o] Error 1
============================================================== [FAILED] Took 1.90 seconds ============================================

```

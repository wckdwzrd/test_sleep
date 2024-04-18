# Simple test of WFI and data reading
This is test firmware to show how data read via STLink is corrupted when MCU is in WFI mode.

To build use CMake commands:
```bash
cmake -S . -B build -G "Unix Makefiles"
cmake --build build
```

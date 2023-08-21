# Hello World Example

Starts a FreeRTOS task to print "Hello World"

See the README.md file in the upper level 'examples' directory for more information about examples.

build process:
make menuconfig
    set ESP-IDF configuration (primarily COM port #)
make flash
    build and flash ESP32
make monitor
    launch IDF monitor to confirm application is running
    ctrl+] to exit
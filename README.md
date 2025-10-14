# FRC ESP32 DevKit Lite
This is a lite version of the ESP32 FRC DevKit forked from IronMaple's original design: https://oshwlab.com/sikaxn/seal-v2-dev-board.

Original Lite design is incomplete and temporarily not being worked on, while the FeatherLite design is almost practically complete.
The only difference is that the Lite design is one board with everything on it while the FeatherLite is a FeatherWing that requires a [ESP32 Feather board]([url](https://www.pishop.ca/product/adafruit-esp32-feather-v2-with-headers-8mb-flash-2-mb-psram-stemma-qt/)) (or [third party compatible]([url](https://www.sparkfun.com/sparkfun-thing-plus-esp32-wroom-usb-c.html))) to work.

Contributions are welcome!

Features:

- Unnecessary and redundant features are removed, making this ~40% smaller.
- Added IO ports for connecting a variety of COTS sensors and encoders
- STEMMA compatible connector for connecting COTS I2C devices
- NeoPixel connector for connecting to NeoPixel-compatible addressable LED products (strips, bars??, etc.)
- Updated with latest ESP32 module (ESP32-WROOM-32E) as previous one was discontinued
- RFID battery tracking over SPI (RC522, more controllers may be supported in the future)
- CP2102N USB-Serial chip (faster and not obsolete compared to CP2104)
- JTAG connector for advanced programming and debugging (note: only on Original Lite design)
- WAGO connector for CAN bus
- more to come!

ESP32 Wireless Communication Disclaimer:

The wireless functions on the ESP32 (must be disabled in the competition area in order to be compliant with the rules presented in the FRC Game Manual (please check the game manual as rules may be changed).
Current firmware doesn't use any wireless functionality, but if future updates/third party firmware enable this, usage must remain in compliance with all rules and regulations.

Licensed under GPLv3

Note: Not affiliated with IronMaple, FIRST HQ, or any other companies mentioned here in any way. All trademarks are properties of their respective owners.
This is an unofficial community project made by a member of a FRC team.

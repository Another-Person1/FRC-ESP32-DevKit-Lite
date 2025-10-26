# ESP32 CAN DevKit Lite
<img width="1217" height="903" alt="image" src="https://github.com/user-attachments/assets/06749114-c077-40aa-bb25-27e72733f775" />

This is a lite version of the ESP32 FRC DevKit forked from IronMaple's original design: https://oshwlab.com/sikaxn/seal-v2-dev-board.

Original Lite design is incomplete and temporarily not being worked on, while the FeatherLite design is almost practically complete.
The only difference is that the Lite design is one board with everything on it while the FeatherLite is a FeatherWing that requires a [ESP32 Feather board]([url](https://www.pishop.ca/product/adafruit-esp32-feather-v2-with-headers-8mb-flash-2-mb-psram-stemma-qt/)) (or [third party compatible]([url](https://www.sparkfun.com/sparkfun-thing-plus-esp32-wroom-usb-c.html))) to work.

This board is designed to be used on FRC robots as an easy way to connect COTS sensors and devices to the roboRIO or Systemcore.

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

Images:

Current version:
<img width="1217" height="903" alt="image" src="https://github.com/user-attachments/assets/e2ed16b8-55e1-4113-98e8-f8e19bcb3f00" />
<img width="1022" height="967" alt="image" src="https://github.com/user-attachments/assets/bf0b8461-417b-406a-9097-ef32be139141" />
Older versions:
<img width="1190" height="918" alt="Screenshot 2025-10-16 143512" src="https://github.com/user-attachments/assets/54167d5f-30e5-414c-9b37-44e80ea0b9e0" />
<img width="1202" height="878" alt="Screenshot 2025-10-14 142027" src=<img width="745" height="478" alt="Screenshot 2025-10-09 141735" src="https://github.com/user-attachments/assets/fa76f11c-d7ac-4cd2-bbde-e754d3706722" />
<img width="762" height="752" alt="Screenshot 2025-10-21 103705" src="https://github.com/user-attachments/assets/8bb56435-0473-402c-a1a6-29104f048e51" />
"https://github.com/user-attachments/assets/a613beeb-bef2-44ba-b6b5-15edc63835d9" />
<img width="977" height="980" alt="Screenshot 2025-10-14 141830" src="https://github.com/user-attachments/assets/92ed4460-b143-47d0-a67c-65b120262d71" />

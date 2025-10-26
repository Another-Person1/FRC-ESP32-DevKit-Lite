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
- Adafruit Feather style microcontroller development board connector so that you can connect ESP32 Feathers (or Feather compatibles)
- RFID battery tracking over SPI (RC522, more controllers may be supported in the future)
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
<img width="1190" height="918" alt="Screenshot 2025-10-16 143512" src="https://github.com/user-attachments/assets/b29ffcb3-bd00-4fda-98e8-5c3ea5cf885a" />
<img width="1202" height="878" alt="Screenshot 2025-10-14 142027" src="https://github.com/user-attachments/assets/6de99b01-b0de-4ca7-8fe1-4bc9f0f4efad" />
<img width="977" height="980" alt="Screenshot 2025-10-14 141830" src="https://github.com/user-attachments/assets/038a739b-0e1b-43f0-8798-ec85cf8680da" />
<img width="745" height="478" alt="Screenshot 2025-10-09 141735" src="https://github.com/user-attachments/assets/1012e505-b7f7-4b5e-979b-eaa82975cea2" />
<img width="762" height="752" alt="Screenshot 2025-10-21 103705" src="https://github.com/user-attachments/assets/a31e0bbb-9a39-401e-bce0-10b1a43d956e" />

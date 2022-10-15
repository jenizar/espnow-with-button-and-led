# espnow-with-button-and-led
Communication between ESP32 (Two or more ESP32) with ESP-NOW Protocol

materials:

esp32 38 pin, led 5mm, tactile button, cable jumper, breadboard.


The protocol is similar to the low-power 2.4 GHz wireless connectivity that is often deployed in wireless mouses. So, the pairing between device is needed prior to their

communication. After the pairing is done, the connection is secure and peer-to-peer, with no handshake being required.

To be able to communicate via the ESP-NOW protocol, the MAC Address of the ESP32 module board as the "receiver" must be known.

In the Arduino code for ESP32 A, enter the MAC Address of ESP32 B, because ESP32 B is the destination for sending data from ESP32 A.

In the Arduino code for ESP32 B, enter the MAC Address of ESP32 A, because ESP32 A is the destination for sending data from ESP32 B.





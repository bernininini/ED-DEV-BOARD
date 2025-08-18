# ED-DEV-BOARD
The Ed Dev Board is a custom dev board featuring a Qwiic port and powered by the ESP32-S3 WROOM 1. A custom PCB to provide an easy access and accessible dev board for prototyping and electronics projects that minimize the wiring.

*Qwiic is a type of connecting system that uses the I2C protocol, that only uses 4 pins (VCC, GND, SDA, SCL)
<img width="277" height="384" alt="image" src="https://github.com/user-attachments/assets/25e2e4a8-da91-4f24-9f47-abae235736e1" />
<img width="613" height="460" alt="image" src="https://github.com/user-attachments/assets/2054f1b9-c00a-4438-bd0d-b1dde3260c87" />
Reference: 
https://www.sparkfun.com/qwiic 

BOM:
| Reference                      | Qty | Value            | Part Name                     |
| ------------------------------ | --- | ---------------- | ----------------------------- |
| QWIIC1, QWIIC2, QWIIC3, QWIIC4 | 4   | port1            | Qwiic Port                    |
| R1, R2                         | 2   | 5.1k             | Resistor 0805                 |
| R3, R4, R5, R6                 | 4   | 10k              | Resistor 0805                 |
| SW1, SW2                       | 2   | SW\_Push         | Push Button 6mm               |
| U1                             | 1   | ESP32-S3-WROOM-1 | ESP32-S3-WROOM-1 Module       |
| U2                             | 1   | AMS1117-3.3      | Voltage Regulator AMS1117-3.3 |
| U3                             | 1   | \~               | USB-C Connector               |



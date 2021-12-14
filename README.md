# Altimeter
Touchscreen Altimeter
This is a practice altimeter created by Ken Burrell, edited to work on a ELEGOO UNO R3 2.8 Inches TFT Touch Screen with a
BMP280 pressure sensor and an Arduino Uno, though a mega will work too.

Wiring. 
Sensor      ISCP (6 pins on edge of Uno)                       As you look at the 6 pins from the edge of the UNO
VCC         VCC                                               Not used      SCL (PIN D13)       SDO (PIN D12)
GRD         GRD                                                 GRD         SDA (PIN D11)       VCC
SCL         SCL (PIN D13)
SDA         SDA (PIN D11)
CSB         UNO PIN 19 (Last pin on the long pin header past pin 13)
SDO         SDO (PIN D12)

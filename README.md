# vigilant-octo-potato
Arduino UNO, HC-SR04 ultrasonic distance sensor, TAL220 10kg Load cell with HX711 signal amplifier and ESP8266.
Send Data to Thinkspeak.

Wiring:

UNO D0 (RX) --------> TX ESP8266

UNO D1 (TX) --------> RX ESP8266

UNO D4 -------------> TX HX711

UNO D5 -------------> RX HX711

UNO D6 -------------> TRIGGER HCSR04

UNO D7 -------------> ECHO HCSR04

UNO, HX711 and HCSR04 to 5V and Negative

ESP8266 VCC to 3.3V and CH_EN to Pull-Up 4.7kΩ resistor.


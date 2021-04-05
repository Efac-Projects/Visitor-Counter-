# Visitor-Counter-
Bi-directional visitor counter using Atmega 328p micro-controller and IR sensor. ESP 8266 wifi module is used to store real time visitor count in thingspeak public channel. This stored data can be analyzed through things speak matlab visualization features

Thingspeak channel - https://thingspeak.com/channels/1344229

Proteus simulation Diagram

![](https://github.com/Efac-Projects/Visitor-Counter-/blob/main/PROTUES.PNG)


References - https://www.electronicwings.com/avr-atmega/atmega16-interface-with-esp8266-module
Note - In this article atmega16 is used, here we have used atmega 328p. To obtain working functionality in 328p we have to change registers and interupt service routine rest of the code is working smoothly. 

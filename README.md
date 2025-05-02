<h1 align="center">
Display Temperature and Humidity on LCD

## **1. Introduction**  
### **1.1 Purpose**
This document is used for design an embedded system to monitor temperature and display it on an LCD screen. The system will measure the ambient temperature using a sensor, process the data, and display it on the LCD screen. If the temperature exceeds the allowed threshold, the system will trigger an alert.

### 🧩 Components

- This project requires below coponents:

| Components | Quantity | Feature |
| ---------- | :------: | ------- |
| `nRF24L01+` RF module | 2 | <ul> <li> Work at 2.4 GHz frequency </li> <li> Communicate with MCU via SPI protocol </li> <li> Auto acknowlegdenment when transmitting </li> <li> Controlable transmitting power </li>  <li> Great range </li> <li> Wide operating voltage </li> <li> Ultra low power down consumption </li> </ul> |
| `ATMEGA328P` MCU | 2 | <ul> <li> Wide availibility </li> <li> Support several communication protocol: UART, SPI, I2C </li> <li> Have a good amount of GPIO pin (2 pins for buttons, 3 pins for indicating LEDs, and 6 pins for comminucation with RF module) </li> <li> Have lots of documentation and a large community </li> <li> Simple to configure and program </li> <li> Ultra low power consumption </li> <li> Operate under a wide voltage range </li> |
| `CR2450` battery | 1 | <ul> <li> Small size </li> <li> Geat voltage consistency (3V) </li> <li> Discharge voltage of 2V </li> <li> Good capacity of 600 mAh </li> </ul> |
| Push button | 2 | <ul> <li> Alway off push button </li> </ul> |
| Relay | 2 | <ul> <li> Able to handle high power </li> </ul> |
| RGB LED | 2 | <ul> <li> Simple to implement and program </li> <li> Wide available </li> </ul> |

Others electric components like resistors, conductors, capacitors, etc would be added later
at the end of this project.

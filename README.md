## Water-level-indicator-
- ** Name: Manoshi kar
- ** Company: CODTECH IT SOLUTIONS
- ** ID: CITS2557
- ** Domain: EMBEDED SYSTEMS
- ** Internship Duration: June 12, 2026 – July 10, 2026
  
 ## Title
 
Automatic Water Level Indicator Using Arduino 

## Introduction

Water is one of the most important resources in our daily life. In homes, industries, and agricultural fields, it is necessary to monitor the water level in tanks and reservoirs. A Water Level Indicator is an electronic device that detects and displays the water level in a tank. This project helps prevent water wastage, tank overflow, and dry running of water pumps. 

## Objective

To monitor the water level in a water tank.
To indicate Low, Medium, and Full water levels.
To reduce water wastage.
To automate water management systems.

## Components Required

- Arduino Uno
- Water Level Sensor
- Red LED
- Yellow LED
- Green LED
- 220Ω Resistors
- Breadboard
- Jumper Wires
- USB Cable
- Water Tank (for testing)
  
## Working Principle

The water level sensor measures the amount of water present in the tank. The sensor sends analog signals to the Arduino. Based on the received value, Arduino determines the water level and turns on the corresponding LED.

- Red LED → Low Water Level
- Yellow LED → Medium Water Level
- Green LED → Full Water Level
  
When the water level increases, the sensor output also increases. Arduino continuously monitors the sensor value and updates the indication accordingly.

## Circuit Connections

- Water Sensor VCC → Arduino 5V
- Water Sensor GND → Arduino GND
- Water Sensor Signal → A0
- Red LED → Pin D8
- int sensorPin = A0;
- int redLED = 8;
- int yellowLED = 9;
- int greenLED = 10;



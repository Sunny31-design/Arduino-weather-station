 # Arduino Weather Station

My first Arduino project that measures **temperature and humidity** using a DHT11 sensor and displays the readings on a **16×2 I²C LCD**.

## Project Overview

This is my first embedded systems project. The system continuously reads temperature and humidity from the DHT11 sensor and displays the real-time values on the LCD.

The same sensor readings are also printed to the Arduino Serial Monitor for debugging and monitoring.

## Components Used

- Arduino Uno R3
- DHT11 Temperature & Humidity Sensor
- 16×2 LCD with I²C module
- Breadboard
- Jumper wires
- USB cable

## Circuit Connections

## [I2C LCD -> Arduino uno]
   GND = GND
   VCC = 5V
   SDA = A4
   SCL = A5

 ## [DHT11 -> Arduino Uno]
   Data = D2
   VCC  = 5V
   GND  = GND

   ## How It Works
The DHT11 sensor measures:
- Temperature
- Relative humidity

The Arduino reads these values every 2 seconds and sends them to:

1. The 16×2 I²C LCD
2. The Serial Monitor

## Software & Libraries

- Arduino IDE
- Arduino C/C++
- Wire library
- LiquidCrystal_I2C library
- DHT sensor library

 ## Output
The LCD displays information similar to:
->text
Temp: 31.7°C
Humidity: 58%

 ## Project Photos

![Project photo](./IMG_20261014_193234_448.jpg)

### Photo 1
![Arduino weather station photo 1](./IMG_20261014_193234_448.jpg)

### Photo 2
![Arduino weather station photo 2](./IMG_20261014_193247_028.jpg)

### Photo 3
![Arduino weather station photo 3](./IMG_20261014_193401_962.jpg)
 

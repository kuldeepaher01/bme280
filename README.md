# I2C BME280 Temperature Read

This project (main.c) demonstrates how to read temperature from an I2C BME280 sensor using ESP32.

### Build and Flash

1. Set up ESP-IDF sample-project.
2. Clone this repository inside the main folder.
3. Build the project.
4. Select the correct serial port and target board.
6. Flash the firmware to ESP32.
7. Open the monitor to see the readings

### Hardware Connections

Make the following connections between ESP32 and BME280 sensor:

| ESP32 Pin | BME280 Pin |
| --------- | ---------- |
| GPIO 21   | SDA        |
| GPIO 22   | SCL        |
| GND       | GND        |
| 3.3V      | VCC        |

If you want use 2nd i2c port make the necessary changes in helper.c

## Tutorial

A detailed tutorial explaining the steps to set up and use the I2C BME280 sensor with ESP32 can be found [here](https://esp32tutorials.com/esp32-mqtt-publish-bme280-node-red-esp-idf/#more-2125).

## Original Example

The original example code for this project can be found [here](https://github.com/ESP32Tutorials/esp32-esp-idf-mqtt-bme280/blob/main/main/main.c).

## Disclaimer
The code in this repository is a revised version of the original example, simplified and optimized for ESP32. It provides an easy way to read temperature data from the BME280 sensor.









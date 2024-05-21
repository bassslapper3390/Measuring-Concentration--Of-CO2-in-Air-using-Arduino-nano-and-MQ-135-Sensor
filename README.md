Here's the revised README with corrected grammar and adjusted image placement:

---

# Interfacing MQ135 Gas Sensor with Arduino

## Description
This project demonstrates how to interface the MQ135 Gas Sensor with Arduino to measure CO2 levels in parts per million (ppm). When the CO2 level exceeds a threshold (650 ppm), the display will flash a warning message prompting the user to open a window for ventilation.

## Components Used
- Arduino Nano
- MQ135 Gas Sensor
- 128x64 OLED Display (SSD1306)
- Jumper Wires

## Pinout
- **OLED Display**:
  - VCC to 5V
  - GND to GND
  - SDA to A4 (SDA on Arduino Nano)
  - SCL to A5 (SCL on Arduino Nano)

- **MQ-135 Sensor**:
  - VCC to 5V
  - GND to GND
  - A0 to A0 on Arduino Nano

![Pinout](https://github.com/bassslapper3390/Measuring-Concentration--Of-CO2-in-Air-using-Arduino-nano-and-MQ-135-Sensor/assets/75876257/a8241749-35c6-43bd-8a16-4e8729917369)

## Installation
1. Connect the components according to the pinout provided.
2. Upload the provided [Arduino code](/code/co2-detector.ino) to your Arduino Nano board.
3. Open the serial monitor or connect display to view the CO2 readings and warnings when CO2 levels are high.

![OLED Display](https://github.com/bassslapper3390/Measuring-Concentration--Of-CO2-in-Air-using-Arduino-nano-and-MQ-135-Sensor/assets/75876257/7ba68326-7083-43fa-a41d-b6000bd8105f)
![MQ135 Sensor](https://github.com/bassslapper3390/Measuring-Concentration--Of-CO2-in-Air-using-Arduino-nano-and-MQ-135-Sensor/assets/75876257/8aeac45c-619d-4e6c-84d4-50bfdc007083)

## Future Scope
Integrate the system with home automation platforms like Home Assistant to monitor CO2 levels in closed rooms. Automatically trigger actions such as opening windows or activating ventilation systems when CO2 levels exceed a predefined threshold. (Will probably use an ESP32)

---

The README is now more polished and includes the images in a more presentable format.

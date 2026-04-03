# Smart Temperature & Humidity Monitor (ESP32 + DHT11)

## Overview

This project is a simple IoT-based monitoring system that measures environmental temperature and humidity using a DHT11 sensor connected to an ESP32. The system reads real-time data and displays it via the serial monitor.

This project serves as a foundational step toward building more advanced IoT data pipelines and real-time monitoring systems.

---

## Objectives

* Collect real-time environmental data (temperature & humidity)
* Understand basic sensor integration with ESP32
* Build a simple and structured IoT project with proper documentation
* Prepare for advanced implementations such as cloud integration and analytics

---

## Components

* ESP32 Development Board
* DHT11 Temperature & Humidity Sensor
* Jumper Wires
* (Optional) 10kΩ Resistor

---

## Wiring Configuration

| DHT11 Pin | ESP32 Connection |
| --------- | ---------------- |
| VCC       | 3.3V             |
| GND       | GND              |
| DATA      | GPIO 4           |

See wiring diagram in `/wiring/wiring.png`

---

## Code Implementation

Main code is available in:

```
/code/main.ino
```

Libraries used:

* DHT sensor library
* Adafruit Unified Sensor

---

## Example Output

```
Temperature: 28.5 °C  |  Humidity: 72 %
```

---

## Project Preview

(Add your actual project photo here)

---

## Key Learnings

* Sensor data acquisition using ESP32
* Handling real-time data from hardware
* Structuring IoT projects for scalability
* Writing clean and readable documentation

---

## Future Improvements

* Send data to MQTT broker for real-time communication
* Store data in database or cloud platform
* Build a web dashboard for visualization
* Apply anomaly detection using machine learning

---

## Project Structure

```
smart-temp-monitor/
├── README.md
├── code/
│   └── main.ino
├── wiring/
│   └── wiring.png
├── images/
│   └── result.png
```

---

## How to Run

1. Connect the DHT11 sensor to ESP32 according to the wiring diagram
2. Install required libraries in Arduino IDE
3. Upload the code to ESP32
4. Open Serial Monitor (baud rate: 115200)
5. Observe temperature and humidity readings

---

## Notes

The simulation uses a DHT22 sensor in Wokwi due to component availability, while the actual hardware implementation uses a DHT11 sensor. Both sensors share similar functionality and wiring configuration.

---

## Author

Sassa

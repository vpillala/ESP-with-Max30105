# ESP-with-Max30105
Uploading the MAX 30105 Spo2 sensor data to Thingspeak cloud using ESP32
# ESP32 with MAX30105 and Thingspeak Integration

This project demonstrates how to use an ESP32 microcontroller to read heart rate and SpO2 data from the MAX30105 sensor and upload it to the Thingspeak cloud.

## Hardware Requirements
- ESP32 Development Board
- MAX30105 Sensor
- Jumper Wires
- Breadboard (optional)

## Wiring
| MAX30105 Pin | ESP32 Pin |
|--------------|-----------|
| VIN          | 3.3V      |
| GND          | GND       |
| SDA          | GPIO 21   |
| SCL          | GPIO 22   |

## Software Requirements
- Arduino IDE
- ESP32 Board Package (installed via Arduino IDE Board Manager)
- Libraries:
  - `SparkFun MAX3010x` (for MAX30105)
  - `WiFi` (built-in)
  - `ThingSpeak` (by MathWorks)

## Setup
1. Clone this repository.
2. Open the `ESP32_MAX30105_Thingspeak.ino` file in the Arduino IDE.
3. Replace `YOUR_WIFI_SSID`, `YOUR_WIFI_PASSWORD`, and `YOUR_THINGSPEAK_API_KEY` with your credentials.
4. Upload the code to your ESP32.
5. Open the Serial Monitor to view sensor data and upload status.

## Thingspeak Integration
- Create a Thingspeak account and set up a new channel.
- Note your API key and channel ID.
- Update the `ThingSpeak` library configuration in the code.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

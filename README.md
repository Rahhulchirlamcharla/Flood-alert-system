# Arduino-Based Flood Alert System

## Project Overview
This project is an **IoT-based Flood Alert System** that monitors water levels and sends real-time alerts to a user’s mobile device via **SMS** and **phone call** when a flood condition is detected. It is designed to prevent property damage and ensure safety in flood-prone areas or water tanks.

---

## Domain
- IoT / Embedded Systems / Environmental Monitoring

---

## Components Used

### Hardware:
- Arduino Uno
- GSM SIM800C Module
- Water Level Sensor
- Connecting Cables
- 12V Adapter

### Software / Libraries:
- Arduino IDE
- SoftwareSerial library
- Adafruit FONA library

---

## How It Works
1. The **water level sensor** continuously measures water level.  
2. Arduino reads the sensor data via an analog pin.  
3. If the water level exceeds a predefined **threshold**, the system:  
   - Sends an **SMS alert** to the user.  
   - Makes a **phone call** to notify about the flood.  
4. The user is alerted in real-time to take preventive action.

---

## Usage
1. Connect the hardware components according to the circuit diagram.  
2. Open the Arduino IDE and upload `arduinocode.ino` to the Arduino Uno.  
3. Power the system using a 12V adapter.  
4. Ensure the GSM module has a working SIM card.  
5. The system is now active and will alert you when water levels are high.

---

## Project Files
- `arduinocode.ino` – Main Arduino code  
- `requirement.txt` – Dependencies (if any for external libraries)

---

## Future Improvements
- Support for **multiple phone numbers** for alerts.  
- Use **non-blocking code** with `millis()` instead of `delay()` for better performance.  
- Integrate **cloud monitoring** for remote visualization.  

---

## Author
**Rahhul Chirlamcharla**

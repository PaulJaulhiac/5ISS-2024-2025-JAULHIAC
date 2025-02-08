# 5ISS-2024-2025-JAULHIAC

This repository contains work I conducted as a part of the courses around the fabrication of a nano-particles based gas sensor and the processing of its data.

## Description

This project integrates:
1. **Datasheet for a gas sensor** to measure gases like Ammonia (NH3), Nitrogen Dioxide (NO2), and Ethanol (C2H6O).
2. **A mobile application** for control and display, using a Bluetooth connection to a microcontroller (ESP32).
3. **An Arduino system**, on an ESP32 board to manage sensor data by processing and allowing communication with the mobile app.

### Objectives of the project:
- Make a nano-particles based gas sensor in lab.
- Implement an adaptation system for a PCB, to recover measurements from the sensor.
- Monitor gas concentrations and trigger alerts when necessary, from a µC.
- Remotely control features via the app.

---

## 📂 Project Structure

- **/software:**
  - `BT_App.ino`: Bluetooth communication between Arduino and the mobile app.
  - `Gas_Sensor-OLED_Screen-W.ino`: Gas sensor data processing with OLED display.
- **/appinventor:**
  - `HomeScreenApp.png` and `MainControlScreenApp.png`: Mobile app previews.
  - `Screen1BlockDiagram.png` and `Screen2BlockDiagram.png`: Application block diagrams for the code behind the app's UI.
- **/hardware:**
  - Full report on simulation and design: `Rapport Elec Gas sensor - JAULHIAC.pdf`.
  - Spice simulations: `./hardware/gas sensor simu`
- **/datasheet:**
  - Sensor datasheet: `JUMIN_JAULHIAC_GAUCHE_MARIN-MULLER_BOUJON_Datasheet_AIME.pdf`.

---

## Installation and Usage

### 🔹 Required Hardware:
- WS2024 gas sensor.
- Arduino microcontroller (ESP32 or equivalent, might imply code adaptating).
- Bluetooth module.
- Android smartphone with the MITappinventor app installed.

### 🔹 Code Installation:
1. **Arduino:**
   - Upload the `.ino` files to the Arduino using the IDE.
   - Connect the sensor and Bluetooth module following the provided schematic.
2. **Mobile Application:**
   - Install the generated APK for Android.
   - Enable Bluetooth and connect the app to the µC.

### 🔹 Usage:
- Launch the mobile app.
- Connect to the Bluetooth module.
- Use buttons or voice commands to interact.

---

## Roadmap

### Planned Improvements:
- Use LoRa communication, implemented with my fellow group members, to transmit the data 
- Implement additional features to the android app and improve it.
- Integrate a database to log measurements.

---

## Contact information

For more information or any question about this project, please, do not hesitate to contact me:

- **Name:** Paul JAULHIAC
- **Email:** jaulhiac@insa-toulouse.fr
- **GitHub:** [@PaulJaulhiac](https://github.com/PaulJaulhiac/)

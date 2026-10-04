# Smart OBD Assistant (AI-Driven Diagnostic Guide) 🚗💻

Standard OBD-II scanners provide raw, confusing Data Trouble Codes (DTCs) like "P0102" or "DF072", leaving standard drivers helpless. **Smart OBD Assistant** is an open-source hardware and software framework designed to read vehicle data and translate it into **actionable, step-by-step DIY repair instructions** powered by logical heuristics.

## 📌 Project Vision
Instead of just clearing codes, this system:
1. **Reads Ham Data:** Interfaces with the vehicle's ECU via ELM327/CAN-Bus and Arduino/HC-05 telemetry.
2. **Analyzes the Fault:** Matches the code with a community-driven JSON database specific to the car model (e.g., Renault Megane 2 1.6 16V).
3. **Provides Actionable Solutions:** Guides the user with steps like *"Unplug the MAF sensor, use contact cleaner on pins"* rather than just saying *"Circuit Open"*.
4. **Smart Video Routing:** Automatically searches and links the exact YouTube DIY repair video for that specific car model and fault.

## 🛠️ System Architecture
* **Hardware:** Arduino Uno / ESP32, HC-05 Bluetooth Module, OBD-II Interface.
* **Software:** C/C++ (Telemetry), JSON (Fault Matrix Database), Python/App (User Interface).

## 📂 Current Database
Check the `dtc_solutions.json` file for the initial test matrix built for the notorious chronic issues of the Renault Megane 2 (Ignition coils, VVT Dephaser, Airbag socket issues).

---
*Developed by Tunahan Aycan - Bridging Industrial Automation & Automotive Electronics.*

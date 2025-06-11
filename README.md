## Overview
The **Centralized ATM Security System** is an innovative IoT-based project designed to enhance the security of Automated Teller Machines (ATMs) using advanced technologies. The system integrates sensors, microcontrollers, and cloud services to offer real-time monitoring, remote control, and security breach notifications.

## Features
- **IoT Integration**: Utilizes ESP8266 and SinricPro for seamless connectivity.
- **Real-Time Security Alerts**: Immediate notifications in case of unauthorized access.
- **Google Assistant Integration**: Enables voice commands to control and monitor the system.
- **Cost-Effective Design**: Leverages affordable hardware and open-source tools.
- **Scalability**: Easily extendable to include additional sensors and devices.

## Technologies Used
- **Hardware**: ESP8266 microcontroller, Hall-effect sensor, buzzer/alarm, and LEDs.
- **Software**: Arduino IDE, SinricPro cloud service, Google Actions Console.
- **Programming Language**: C++ (Arduino framework).

## Architecture

The system architecture includes the following components:
1. **Microcontroller Board**: ESP8266 serves as the central processor.
2. **Sensors**: Hall-effect sensors monitor ATM door activities.
3. **Cloud Integration**: SinricPro manages real-time data exchange and integration with Google Assistant.
4. **User Interface**: Google Assistant-enabled devices provide voice control and remote management.

## Setup Instructions
1. **Hardware Setup**:
   - Connect the ESP8266 microcontroller with the Hall-effect sensor and alarm.
   - Ensure proper wiring for the Wi-Fi module and other components.
2. **Software Configuration**:
   - Install the Arduino IDE and required libraries:
     - `ESP8266WiFi`
     - `SinricPro`
   - Configure the SinricPro account and Google Assistant integration.
   - Upload the provided code to the ESP8266 board.
3. **Test the System**:
   - Arm and disarm the system using voice commands.
   - Simulate door activities to test the sensor and alarm functionality.

## Usage
- **Voice Commands**:
  - "Arm the system" to enable security monitoring.
  - "Disarm the system" to deactivate the alarm.
  - "Check system status" for a current update.
- **Real-Time Alerts**:
  - Notifications sent to mobile devices upon detecting a breach.


## Future Enhancements
- Integration of additional sensors, such as motion detectors and cameras.
- Advanced analytics using machine learning for predictive security.
- Multi-factor authentication for improved user access control.
- Power management enhancements, including solar power options.



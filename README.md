# Bluetooth-Based Home Automation System

## Introduction

This project focuses on creating a low-cost automated home system designed primarily for bachelors or small families. Leveraging the Internet of Things (IoT), it aims to provide an easy-to-use and budget-friendly solution for home automation, enhancing convenience, reducing power consumption, and improving security.

## Features

- **Remote Device Control:** Control home appliances remotely using an Android-based application.
- **Automation:** Automate devices to reduce power consumption.
- **Security:** A keypad-based security system for door access.
- **Sensors:** Utilizes various sensors such as LDR, temperature sensor (LM-35), and smoke sensor for automated responses.
- **Connectivity:** Uses Bluetooth for device communication.

## Components

- **Arduino Uno Microcontroller:** The brain of the system, handling all operations.
- **Bluetooth Module:** Enables communication between the Android app and Arduino.
- **Wi-Fi Module:** For future enhancements and extended connectivity.
- **LDR (Light Dependent Resistor):** Detects ambient light levels to automate lighting.
- **Temperature Sensor (LM-35):** Monitors room temperature for climate control.
- **Smoke Sensor:** Detects smoke to enhance safety.
- **Keypad:** Provides a secure method for door access.

## Requirements

- Arduino Uno Microcontroller
- HC-05 Bluetooth Module
- ESP8266 Wi-Fi Module (optional for future enhancements)
- LDR Sensor
- LM-35 Temperature Sensor
- Smoke Sensor
- 4x4 Keypad
- Android Device with Bluetooth support
- Arduino IDE
- Android Studio (for developing the Android application)

## Setup and Installation

### Hardware Setup

1. **Arduino Uno**: Connect the Bluetooth module, sensors, and keypad to the Arduino Uno.
2. **Bluetooth Module (HC-05)**: Connect VCC to 5V, GND to GND, TX to RX, and RX to TX on the Arduino.
3. **LDR Sensor**: Connect one end to 5V, the other to GND through a 10kΩ resistor, and the junction to an analog input pin on the Arduino.
4. **Temperature Sensor (LM-35)**: Connect VCC to 5V, GND to GND, and output to an analog input pin.
5. **Smoke Sensor**: Connect according to the sensor's datasheet.
6. **Keypad**: Connect rows and columns to digital pins on the Arduino.

### Software Setup

1. **Arduino IDE**: Install the Arduino IDE from the [Arduino website](https://www.arduino.cc/en/software).
2. **Arduino Code**: Upload the provided Arduino code to the Arduino Uno.
3. **Android Application**:
   - Install Android Studio from the [Android Studio website](https://developer.android.com/studio).
   - Develop the Android application or use the provided APK to control the home automation system via Bluetooth.

## Usage

1. **Power On**: Ensure the Arduino and connected modules are powered.
2. **Pair Bluetooth**: Pair your Android device with the HC-05 Bluetooth module.
3. **Open App**: Open the Android application and connect to the Bluetooth module.
4. **Control Devices**: Use the app to control connected home appliances.
5. **Security**: Use the keypad to enter the code and unlock the door.

## Future Enhancements

- Integration with Wi-Fi for remote access over the internet.
- Adding more sensors for enhanced automation and security.
- Developing a web-based control panel.

## Conclusion

This Bluetooth-based home automation system provides an efficient, low-cost solution for smart home control and security. Designed with bachelors and small families in mind, it enhances convenience and safety while being budget-friendly.

## Acknowledgements

- Arduino
- Android Studio
- Open-source libraries and resources

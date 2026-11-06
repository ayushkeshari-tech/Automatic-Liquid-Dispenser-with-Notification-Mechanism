# Automatic Liquid Dispenser with Notification Mechanism

An IoT-based automatic liquid dispensing system using ESP32, sensors, and the Blynk IoT platform for water-level monitoring and low-water-level notifications.

## 📌 Project Overview

The **Automatic Liquid Dispenser with Notification Mechanism** is an individual IoT project developed as part of the Introduction to IoT Systems Lab.

The prototype automates liquid dispensing using an ESP32 microcontroller, an ultrasonic sensor, an IR proximity sensor, and a relay-controlled DC water pump. It also monitors the liquid level and provides notifications to the water supplier when the water level becomes low through the Blynk IoT platform.

## ✨ Key Features

- Automatic liquid dispensing.
- Liquid-level monitoring using an ultrasonic sensor.
- Glass detection using an IR proximity sensor.
- Relay-based water pump control.
- Real-time monitoring through the Blynk IoT platform.
- Low-water-level notification at 30% or below.
- LED status indicators and buzzer alerts.

## 🛠️ Hardware Components

| Component | Purpose |
|---|---|
| ESP32 | Main controller and Wi-Fi connectivity |
| HC-SR04 Ultrasonic Sensor | Liquid-level measurement |
| IR Proximity Sensor | Glass detection |
| Relay Module | Water pump control |
| 5V DC Water Pump | Liquid dispensing |
| LEDs | System status indication |
| Buzzer | Alert indication |
| Liquid Container | Liquid storage |

## 💻 Software & Technologies

- Arduino IDE
- Embedded C++ (Arduino)
- Blynk IoT Platform
- Wi-Fi Communication

## ⚙️ Working Principle

1. The HC-SR04 ultrasonic sensor measures the distance between the sensor and the liquid surface.
2. The ESP32 calculates the approximate liquid level.
3. The IR proximity sensor detects the presence of a glass.
4. When a glass is detected and sufficient liquid is available, the relay activates the DC pump.
5. The system sends liquid-level information to the Blynk dashboard.
6. When the liquid level reaches 30% or below, the system activates an alert and sends a Blynk notification.

## 📊 Prototype Specifications

| Parameter | Value |
|---|---|
| Container Capacity | 2 Litres |
| Empty Tank Distance | 20 cm |
| Full Tank Distance | 4 cm |
| Low-Level Alert | 30% |

## 📷 Project Demonstration

The project prototype photograph is available in the `images` directory.

## 📄 Project Documentation

The complete academic project report is available below:

**[View / Download Project Report (PDF)](docs/Automatic_Liquid_Dispenser_Project_Report.pdf)**

The report includes:

- Abstract
- Introduction
- Problem Background
- Proposed Solution
- Technical Support
- Results
- References

## 📁 Repository Structure

```text
Automatic-Liquid-Dispenser-with-Notification-Mechanism/
│
├── README.md
├── LICENSE
│
├── src/
│   └── Automatic_Liquid_Dispenser.ino
│
├── docs/
│   └── Automatic_Liquid_Dispenser_Project_Report.pdf
│
├── images/
│   └── project-prototype.jpg
│
└── .gitignore
```

## 🚀 Setup & Installation

1. Install Arduino IDE.
2. Install the ESP32 board package.
3. Install the required Blynk library.
4. Connect the hardware components.
5. Configure Wi-Fi and Blynk credentials privately.
6. Upload the Arduino sketch to the ESP32.
7. Configure the Blynk dashboard.

**Security Note:** Never upload your actual Wi-Fi password or Blynk Auth Token to a public repository.

## 🔮 Future Enhancements

- GSM-based notification system.
- Flow sensor integration.
- Improved liquid-level monitoring.
- Intelligent monitoring and predictive analysis.

## 🎓 Academic Project Information

- **Project Type:** Individual Project
- **Academic Year:** 2025–2026
- **Semester:** 3rd Semester
- **Subject:** Introduction to IoT Systems Lab
- **Department:** Computer Science and Engineering (Internet of Things)
- **Institution:** Noida Institute of Engineering and Technology (NIET), Greater Noida.

## 👨‍💻 Author

**Ayush Keshari**

B.Tech – Computer Science and Engineering (IoT)

[GitHub Profile](https://github.com/ayushkeshari-tech)

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

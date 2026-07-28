
# 🌱 Web-Based Waste Segregator with SMS Notification and Real-Time Monitoring

## 📖 Overview
An IoT-based smart waste management system that automatically segregates waste, monitors bin status in real time through a web dashboard, and sends SMS notifications when maintenance or collection is required. The system is powered by a solar panel with a rechargeable battery, enabling continuous 24/7 operation.

## ✨ Features
- Automatic waste segregation
- Real-time web dashboard
- SMS notifications
- Solar-powered operation
- Battery backup for 24/7 operation
- Remote monitoring
- Energy-efficient design

## 🛠 Technologies Used

### Hardware
- ESP32 / Arduino
- Ultrasonic Sensor
- Waste Detection Sensors
- GSM Module (SIM800L/SIM900)
- Solar Panel
- Rechargeable Battery
- Solar Charge Controller

### Software
- HTML5
- CSS3
- JavaScript
- PHP (backend language)
- MySQL / Firebase (depending on implementation)
- Arduino IDE

### Communication
- Wi-Fi
- GSM/SMS

## 🏗️ System Architecture
1. Sensors identify waste and monitor bin level.
2. Microcontroller processes sensor data.
3. Data is transmitted to the web application over Wi-Fi.
4. GSM module sends SMS notifications.
5. Solar panel charges the battery.
6. Battery powers the system continuously.

## 🚀 Installation
```bash
git clone https://github.com/your-username/web-based-waste-segregator.git
cd web-based-waste-segregator
```
Install dependencies, configure the database, upload the firmware, and start the web server.

## 📂 Project Structure
```text
.
├── firmware/
├── web/
├── database/
├── docs/
├── images/
└── README.md
```

## ⚙️ Usage
1. Power on the device.
2. Connect to Wi-Fi.
3. Open the web dashboard.
4. Dispose of waste normally.
5. Monitor status and receive SMS alerts.

## 🌍 Environmental Impact
- Promotes proper waste segregation
- Reduces landfill waste
- Lowers carbon emissions
- Conserves electrical energy
- Prevents overflowing bins
- Encourages sustainable waste management

## 🤝 Contributing
Fork the repository, create a feature branch, commit your changes, and submit a Pull Request.

## 📄 License
MIT License (recommended)

## 👥 Authors
Conan Camposano and Project Team

## 📬 Contact
Email: conancamposano12@gmail.com


---

# README Installation Supplement

## Overall Installation and Deployment Procedure

### Hardware Assembly
1. Assemble the frame and waste bins.
2. Install waste detection sensors and ultrasonic sensor.
3. Mount the ESP32/Arduino.
4. Connect the GSM module.
5. Install the solar panel, charge controller, and battery.
6. Verify all wiring.

### Firmware Installation
1. Install Arduino IDE.
2. Install required libraries.
3. Configure Wi-Fi credentials, SMS number, and server URL.
4. Upload the firmware.

### Web Application Installation
1. Install the web server.
2. Install the database.
3. Import the SQL database.
4. Configure the application.
5. Launch the web dashboard.

### Initial Configuration
1. Connect the device to Wi-Fi.
2. Register the device.
3. Configure SMS notifications.
4. Set bin thresholds.

### Testing
- Verify sensors.
- Verify automatic segregation.
- Verify dashboard updates.
- Verify SMS alerts.
- Verify battery operation.
- Verify solar charging.

### Normal Operation
1. Power on the system.
2. Solar charges the battery.
3. Battery powers the system continuously.
4. Waste is automatically segregated.
5. Dashboard updates in real time.
6. SMS alerts are sent when needed.

### Maintenance
- Clean sensors.
- Clean solar panel.
- Check battery.
- Update firmware and web app.
- Backup the database.

# Smart Transit System
### Enhancing Bus Safety and Attendance Through IoT and Mobile Integration

## Project Overview
Smart Transit System is a Flutter-based application designed to improve college bus transportation through real-time tracking, attendance management, and safety monitoring. It integrates mobile application technology with IoT hardware to support safer and smarter transportation.

## Key Features
- **Live Bus Tracking:** View bus location on an interactive map.
- **Route and ETA:** Display bus routes, stops, and estimated arrival times.
- **Smart Stop Alerts:** Receive voice notifications as the bus approaches selected stops.
- **Digital Attendance:** Support fingerprint-based student attendance through IoT hardware.
- **Accident Detection:** Use an MPU6050 motion sensor to detect potential accidents and trigger alerts.
- **Attendance History:** View recorded attendance information.
- **Role-Based Access:** Separate Student and Bus In-Charge experiences.

## 🛠️ Technologies Used
- **Mobile App:** Flutter, Dart
- **Backend and Services:** Firebase
- **Maps:** Google Maps integration
- **IoT Hardware:** ESP32, GPS module, R307S fingerprint sensor, MPU6050
- **Hardware Communication:** Sensor integration and HTTP-based communication

## System Components
1. Flutter mobile application
2. Firebase authentication and application data services
3. GPS-based bus location tracking
4. Fingerprint-based attendance hardware
5. Motion-sensor-based accident detection and alerting

## Getting Started

### Prerequisites
- Flutter SDK
- Dart SDK
- Android Studio or Visual Studio Code
- A configured Firebase project
- Google Maps API configuration, if required

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Genesisdoss/smart_bus_tracking.git
   ```
2. Open the project directory:
   ```bash
   cd smart_bus_tracking
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Configure the required Firebase and Google Maps settings.
5. Run the application:
   ```bash
   flutter run
   ```

## Configuration and Security
Do not commit Firebase service-account private keys, passwords, or other secrets. Configure credentials securely before running the application.

## Project Objective
To combine mobile application development and IoT technology to improve college transportation visibility, attendance management, and passenger safety.

## 👨‍💻 Author
**Genesisdoss**

---

*Academic project developed using Flutter and IoT technologies.*

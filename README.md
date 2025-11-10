# FlowGuardian - Water Leakage Detection System

FlowGuardian is an innovative IoT-based water leakage detection system designed to minimize water wastage, reduce costs, and prevent structural damage caused by undetected leaks in pipelines and distribution systems. The system employs real-time monitoring, leveraging sensors and an efficient tech stack to provide alerts and actionable insights.

---

## Features
- **Real-time Leak Detection**: Monitors water flow and pressure to identify leaks promptly.
- **Automated Alerts**: Sends SMS, email, or WhatsApp notifications when leaks are detected.
- **Dashboard Visualization**: Offers an easy-to-use web interface for monitoring historical data and real-time leak detection.
- **Cost Optimization**: Helps minimize maintenance costs by addressing leaks proactively.

---

## Tech Stack
### Backend:
- **Express**: For building the backend RESTful API.
- **Websockets**: For real-time communication.

### Frontend:
- **React**: For building a dynamic, user-friendly web interface.
- **Tailwind CSS**: For designing a responsive and attractive UI.

### Tools:
- **Nodemailer**: For email notifications.
- **Arduino IDE**: For programming the ESP32 microcontroller.
- **VSCode**: As the primary development environment.

### Hardware Components:
- **ESP32**: A low-cost, low-power microcontroller with Wi-Fi and Bluetooth capabilities.
- **Flow Sensor**: For monitoring water flow rates.

---

## System Architecture
### Component Selection:
1. **Sensors**: Flow and pressure sensors selected based on accuracy, cost, and compatibility.
2. **Microcontroller**: ESP32 processes sensor data and triggers alerts.
3. **Communication Modules**: For real-time data transmission to the backend.

### Implementation:
1. Assemble and integrate the ESP32 with sensors.
2. Program the ESP32 to process data and manage alerts.
3. Connect the microcontroller to the backend server for data transmission and visualization.

---

## Installation and Usage

### Prerequisites:
1. **Hardware**: ESP32 microcontroller, flow sensor, necessary connectors, and power supply.
2. **Software**:
   - Arduino IDE for ESP32 programming.
   - Node.js for running the backend server.
   - A modern browser for accessing the React dashboard.

### Steps:
1. **Set up the Hardware**:
   - Connect the flow sensor to the ESP32 microcontroller.
   - Power the setup and ensure connectivity.

2. **Deploy the Backend**:
   - Install dependencies using `npm install`.
   - Start the server using `npm start`.

3. **Run the Frontend**:
   - Navigate to the frontend directory.
   - Install dependencies using `npm install`.
   - Start the development server using `npm start`.

4. **Program the ESP32**:
   - Use the Arduino IDE to upload the provided code to the ESP32.

5. **Access the Dashboard**:
   - Open the React app in your browser and log in to monitor water flow and receive alerts.

---

## Results
The FlowGuardian system enables real-time leak detection and provides users with timely alerts and an easy-to-use dashboard. This proactive approach significantly reduces water wastage and associated costs, contributing to sustainable water management practices.

---

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License.

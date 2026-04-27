# Automation_using_arduino_with_GSM_Module
A low-cost wireless automation system built using Arduino Uno and SIM900A GSM module that allows remote control of electrical devices via SMS.Designed to work without internet connectivity, ensuring reliable operation through GSM networks.

# 📡 GSM-Based Wireless Automation System

## 🔍 Overview
Designed and developed a low-cost GSM-based automation system using Arduino Uno and SIM900A to remotely control electrical devices via SMS. The system operates without internet connectivity, making it reliable for remote and low-infrastructure environments.

---

## 💡 Key Highlights
- 📶 Internet-free remote control using GSM (SMS commands)
- ⚡ Control of multiple devices using a 4-channel relay module
- 🌡️ Integrated sensors for real-time monitoring:
  - ACS712 – Current sensing
  - DHT11 – Temperature & Humidity
  - PIR – Motion detection
- 📟 16x2 LCD for local system status display
- 🔄 Bidirectional communication (control + feedback via SMS)
- 🔌 Safe interfacing between low-voltage control and high-voltage loads

---

## 🧠 System Architecture
1. User sends SMS command from a mobile phone  
2. GSM module (SIM900A) receives the message  
3. Arduino Uno reads and processes the command  
4. Corresponding relay is triggered (ON/OFF control)  
5. Sensors continuously monitor environmental parameters  
6. LCD displays real-time status  
7. System sends feedback/status back via SMS  

---

## 🛠️ Tech Stack & Tools
- **Microcontroller:** Arduino Uno  
- **Communication:** GSM (SIM900A, AT Commands)  
- **Sensors:** ACS712, DHT11, PIR  
- **Actuation:** 4-Channel Relay Module  
- **Display:** 16x2 LCD  
- **Programming:** Embedded C (Arduino IDE)

---

## ⚙️ Core Functionality
- SMS-based command parsing (e.g., `D1 ON`, `D1 OFF`)
- Multi-device control using relays  
- Real-time sensor monitoring  
- Remote status updates via SMS  
- Standalone operation without internet  

---

## 📊 Engineering Considerations
- Reliable UART communication between GSM module and Arduino  
- Noise handling in GSM signal transmission  
- Safe power isolation between 5V control and 220V AC loads  
- Modular and scalable system design  
- Efficient command parsing and execution  

---

## 📦 Components Used
- Arduino Uno  
- SIM900A GSM Module  
- 4-Channel Relay Module  
- ACS712 Current Sensor  
- DHT11 Temperature & Humidity Sensor  
- PIR Motion Sensor  
- 16x2 LCD Display  
- Power Supply (5V DC & 220V AC)

---

## 📩 Example SMS Commands

| Command | Action |
|--------|--------|
| D1 ON  | Turn ON Device 1 |
| D1 OFF | Turn OFF Device 1 |
| D2 ON  | Turn ON Device 2 |
| D2 OFF | Turn OFF Device 2 |
| STATUS | Get system status |

---

## 🎯 Applications
- Home Automation  
- Industrial Device Control  
- Remote Monitoring Systems  
- Energy Management  

---

## 🚀 Why This Project Stands Out
- Solves real-world problem (no internet dependency)  
- Demonstrates embedded systems + communication integration  
- Combines hardware interfacing, sensors, and control logic  
- Suitable for scalable IoT-based extensions  

---

## 📷 Block Diagram
![Block Diagram](./block_diagram.png)

---

## 🔮 Future Improvements
- Mobile App / IoT (Wi-Fi) integration  
- Cloud data logging  
- Voice control system  
- Enhanced security (authentication for SMS commands)



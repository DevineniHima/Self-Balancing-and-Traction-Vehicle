 #  Self-Balancing and Traction Vehicle

##  Overview
A self-balancing and traction-controlled vehicle built using **Arduino** and **MPU6050** sensors.  
The project aims to maintain balance automatically while moving smoothly on different surfaces using a **PID control system** and **real-time sensor feedback**.

---

## Components
- **Arduino Mega / ESP32** – Main controller  
- **MPU6050** – Gyroscope + Accelerometer for balance detection  
- **L298N / L293D** – Motor driver  
- **DC Geared Motors & Servo Motor (MG995)** – Movement and steering  
- **ESP8266** – Wireless control via web interface  
- **Battery, Frame, Wheels, Buzzers** – Power and structure  

---

## Working Principle
1. The **MPU6050** senses tilt and motion.  
2. The **PID controller** processes sensor data and adjusts motor speed to maintain balance.  
3. **Traction control** prevents wheel slip on slippery or uneven terrain.  
4. The **ESP8266 module** provides wireless control through a web interface.  

---

## Features
- Automatic self-balancing using PID control  
- Real-time tilt correction and traction management  
- Wireless control via ESP8266 web server  
- Buzzer alert for unsafe tilt angles  
- Compact and modular mechanical design  

---

## Tools & Skills
**Tools:** Arduino IDE, CAD software  
**Technologies:** C/C++, PID Control, Embedded Systems, ESP8266 Web Server  

---

##  Applications
- Self-balancing scooters and robots  
- Smart wheelchairs and mobility aids  
- Autonomous material-handling trolleys  

---

##  Conclusion
This project integrates **sensors, control algorithms, and mechanical design** to achieve a stable and responsive self-balancing vehicle.  
It provided hands-on experience in **PID tuning, sensor interfacing, and real-time system control**.

---





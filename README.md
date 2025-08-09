# WiFi-Robot-Remote-Control-ESP8266-
 This project allows you to control a 2WD robot using an ESP8266 board (NodeMCU) via WiFi. It supports both **STA mode** (connect to your router) and **AP mode** (robot creates its own hotspot). You can control the robot through a web interface with buttons for Forward, Backward, Left, Right, and Stop.

# WiFi Robot Remote Control (ESP8266)

This project allows you to control a 2WD robot using an ESP8266 board (NodeMCU) via WiFi.
It supports both **STA mode** (connect to your router) and **AP mode** (robot creates its own hotspot).
You can control the robot through a web interface with buttons for Forward, Backward, Left, Right, and Stop.

---

## 📦 Features
- Connects to existing WiFi or starts its own hotspot
- Web-based control panel
- OTA firmware update support
- Motor speed control via PWM
- Buzzer and LED indicators

---

## 🛠 Hardware Required
- ESP8266 NodeMCU board
- L298N or similar motor driver
- 2 DC motors
- Active buzzer
- LEDs

---

## 📌 Pin Connections
| Function       | Pin |
|----------------|-----|
| Motor A PWM    | D1  |
| Motor B PWM    | D2  |
| Motor A DIR    | D3  |
| Motor B DIR    | D4  |
| Buzzer         | D5  |
| LED            | D8  |
| WiFi Status LED| D0  |

---

## 🚀 Setup
1. Clone this repository
2. Open `src/wifi_robot_control.ino` in Arduino IDE
3. Install **ESP8266 board support** in Arduino IDE
4. Update `sta_ssid` and `sta_password` with your WiFi credentials
5. Upload code to your NodeMCU
6. Access the robot’s IP in your browser and use the control panel

---

## 📜 License
MIT License – feel free to use and modify this project.

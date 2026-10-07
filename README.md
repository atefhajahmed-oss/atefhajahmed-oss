<!-- ========================================================= -->
<!--                    PROFILE HEADER                         -->
<!-- ========================================================= -->

<div align="center">

# 👋 Hi, I'm Atef Haj Ahmed

### Embedded Systems Engineering Student
### IoT • Robotics • Intelligent Systems • Embedded Software

<p>
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="YOUR_PORTFOLIO_URL">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <a href="mailto:atef.hajahmed@etudiant-isi.utm.tn">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=atefhajahmed-oss&style=flat-square&color=blue" alt="Profile views"/>

</div>

---

# 🚀 About Me

I'm an **Embedded Systems Engineering student** passionate about designing
and developing intelligent hardware-software systems.

My main interests are:

- 🔧 Embedded Systems & Firmware Development
- 🤖 Robotics & Automation
- 🌐 Internet of Things (IoT)
- 🧠 Intelligent Systems & Computer Vision
- 📡 Communication Protocols
- ⚡ Real-Time Embedded Systems
- 🔌 Hardware–Software Integration

I enjoy working at the intersection of **electronics, software and intelligent
systems**, from low-level microcontroller programming to connected applications
and robotic systems.

🎯 **Currently looking for PFE / Internship opportunities in Embedded Systems,
IoT, Robotics and Intelligent Systems.**

---

# 🧑‍💻 Technical Skills

## 🔧 Embedded Systems

<p>
<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
<img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
<img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
</p>

- STM32F4 / STM32G0 / STM32L4
- ESP32
- Arduino
- Raspberry Pi
- Embedded C / C++
- HAL / STM32CubeMX / STM32CubeIDE
- GPIO / Timers / Interrupts
- PWM / ADC
- UART / SPI / I2C
- CAN Bus
- USB CDC
- Bluetooth / Wi-Fi
- RTOS concepts

---

## 💻 Programming

<p>
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white"/>
</p>

- C
- C++
- Python
- Bash
- Object-Oriented Programming
- Data processing
- Automation scripts

---

## 🌐 IoT & Communication

<p>
<img src="https://img.shields.io/badge/Wi--Fi-FF6F00?style=for-the-badge&logo=wifi&logoColor=white"/>
<img src="https://img.shields.io/badge/Bluetooth-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white"/>
<img src="https://img.shields.io/badge/CAN%20Bus-333333?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white"/>
</p>

- CAN Bus
- UART
- SPI
- I2C
- Wi-Fi
- Bluetooth
- NRF24L01
- MQTT
- ThingSpeak
- OTA

---

## 🤖 Robotics & AI

- Robotic systems
- Mobile robots
- Robotic arm control
- PID control
- Computer Vision
- OpenCV
- ArUco marker detection
- Sensor integration
- Motor control
- Automation

---

## 🛠️ Development Tools

<p>
<img src="https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
<img src="https://img.shields.io/badge/PlatformIO-FF7F00?style=for-the-badge&logo=platformio&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

- STM32CubeMX
- STM32CubeIDE
- VS Code
- PlatformIO
- Git / GitHub
- Linux
- Qt
- Serial terminals
- Debugging & testing tools

---

# 🚀 Featured Projects

## 🔋 1. STM32 CAN Gateway & BMS Emulator

> Real-time embedded communication system based on STM32,
> CAN Bus and UART.

### 🏗️ Architecture

```text
                 ┌─────────────────────┐
                 │    Qt Application   │
                 │   Monitoring / GUI   │
                 └──────────┬──────────┘
                            │
                         UART2
                            │
                     CP2102 USB-UART
                            │
                            ▼
                 ┌─────────────────────┐
                 │    STM32 Gateway    │
                 │                     │
                 │ UART ↔ CAN          │
                 └──────────┬──────────┘
                            │
                         CAN Bus
                       500 kbit/s
                            │
                            ▼
                 ┌─────────────────────┐
                 │  STM32 BMS Emulator │
                 │                     │
                 │ BMS Data Generator  │
                 └─────────────────────┘

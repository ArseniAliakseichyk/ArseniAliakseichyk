<div align="center">
  <h1>Arseni Aliakseichyk</h1>
  <h3>Embedded & Systems Engineer</h3>
  <p>
    C firmware · STM32 · ESP32-S3 · FreeRTOS · IoT · Edge ML · Linux Infrastructure
  </p>
  <p>
    <a href="https://cv.arseni-aliakseichyk.com"><img src="https://img.shields.io/badge/CV-Website-2d5016?style=for-the-badge" alt="CV"/></a>
    <a href="https://www.linkedin.com/in/arseni-aliakseichyk/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
    <a href="mailto:arseni.aliakseichyk@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  </p>
</div>

---

Currently building **CyberGlove** — an IoT smart glove with 9-DoF IMU, fiber optic sensors, and real-time WebSocket telemetry. Interned at **GlobalLogic Poland** building a robotic platform on Raspberry Pi 5. Self-hosting **13+ Docker services** on Linux VPS across 4 domains.

---

### 🛠️ Tech Stack

<p>
  <strong>Firmware & Embedded</strong><br>
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C"/>
  <img src="https://img.shields.io/badge/ESP--IDF-E7332A?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP-IDF"/>
  <img src="https://img.shields.io/badge/FreeRTOS-78C557?style=for-the-badge" alt="FreeRTOS"/>
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" alt="STM32"/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi"/>
</p>
<p>
  <strong>Protocols & Interfaces</strong><br>
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" alt="MQTT"/>
  <img src="https://img.shields.io/badge/WebSocket-010101?style=for-the-badge" alt="WebSocket"/>
  <img src="https://img.shields.io/badge/BLE%20(NimBLE)-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white" alt="BLE"/>
  <img src="https://img.shields.io/badge/SPI%20/%20I²C%20/%20UART-444?style=for-the-badge" alt="SPI/I2C/UART"/>
</p>
<p>
  <strong>ML / Computer Vision</strong><br>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white" alt="ONNX"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
</p>
<p>
  <strong>Mobile (System-Level)</strong><br>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
</p>
<p>
  <strong>Infrastructure & DevOps</strong><br>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white" alt="WireGuard"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>
<p>
  <strong>Also</strong><br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C++17-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++17"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/GStreamer-2D2D2D?style=for-the-badge" alt="GStreamer"/>
  <img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white" alt="CMake"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
</p>

---

### 🚀 Featured Projects

<details>
<summary><strong>🔧 CyberGlove — IoT Smart Glove Platform</strong>&ensp;<code>C</code> <code>ESP-IDF</code> <code>FreeRTOS</code> <code>SPI</code> <code>WebSocket</code>&ensp;🟡 In Development</summary>
<br>

IoT wearable for gesture control built on ESP32-S3. Reads ICM-20948 9-DoF IMU over SPI (4 MHz), custom fiber optic bend sensor via 12-bit ADC, and streams telemetry at 50 Hz over WebSocket to a web dashboard. Wi-Fi STA with automatic reconnection, FreeRTOS task management.

**Highlights:**
- 9-DoF IMU (accelerometer + gyroscope + magnetometer) via SPI at 4 MHz
- Custom fiber optic bend sensor — analog ADC reading, calibration routine
- Real-time WebSocket server on ESP32-S3 — 50 Hz telemetry to browser
- Wi-Fi auto-reconnect with exponential backoff
- FreeRTOS tasks: sensor polling, WebSocket TX, Wi-Fi watchdog

</details>

<details>
<summary><strong>🤖 Robotic Platform — GlobalLogic Internship</strong>&ensp;<code>C++17</code> <code>RPi 5</code> <code>GStreamer</code> <code>MQTT</code> <code>Hailo AI</code>&ensp;✅ Complete</summary>
<br>

Modular robotic platform on Raspberry Pi 5, developed in a 4-person Agile/SCRUM team at GlobalLogic Poland. Features multithreaded C++17 motion control, real-time FPV video streaming, ultrasonic obstacle detection, and AI-powered human tracking.

**Highlights:**
- C++17 multithreaded motion control — 5 concurrent threads (motor PWM, sensor polling, MQTT listener, video pipeline, API server)
- GStreamer FPV streaming — MJPEG over UDP, runtime-configurable up to 1080p@60fps
- HC-SR04 ultrasonic obstacle detection — 20 cm threshold, hysteresis for noise rejection
- FastAPI REST API — JWT auth, containerized with Docker Compose (FastAPI + Mosquitto + Redis)
- Hailo AI neural processor — real-time human skeleton detection for autonomous obstacle avoidance

</details>

<details>
<summary><strong>⚙️ STM32 Peripheral Firmware</strong>&ensp;<code>C</code> <code>STM32F4</code> <code>HAL/CMSIS</code> <code>SPI</code> <code>I²C</code> <code>UART</code>&ensp;✅ Complete</summary>
<br>

Bare-metal and HAL firmware on STM32F407VGT6 (ARM Cortex-M4, Discovery board). Both register-level and HAL-abstracted implementations for peripheral communication and signal processing.

**Highlights:**
- GPIO configuration, timer-based PWM generation
- NVIC interrupt handling with priority management
- SPI, I²C, UART peripheral communication
- ADC/DAC analog signal processing
- Debugging with LA1010 logic analyzer and oscilloscope via JTAG/GDB

</details>

<details>
<summary><strong>🧠 Real-Time Shape & Symbol Classifier</strong>&ensp;<code>PyTorch</code> <code>ONNX</code> <code>OpenCV</code> <code>RPi 5</code> <code>SPI</code>&ensp;✅ Complete</summary>
<br>

Full ML pipeline from training to edge deployment. Classifies 80 classes (5 shapes × 16 hex symbols) in real-time on Raspberry Pi 5.

**Highlights:**
- PyTorch training — MobileNetV3-Large, transfer learning (2-phase), mixed precision (CUDA)
- ONNX export & edge inference — 25–30 FPS at 640×480 on RPi 5
- Custom SPI LCD driver — ST7735S TFT (160×128, RGB565) via spidev + gpiod v2
- HTTP dashboard — real-time classification stats, detection history
- Synthetic dataset generation — 2M images, 12 augmentation types

</details>

<details>
<summary><strong>📡 ESP32 IoT Embedded Suite</strong>&ensp;<code>C</code> <code>ESP-IDF</code> <code>FreeRTOS</code> <code>BLE</code> <code>NimBLE</code>&ensp;✅ Complete</summary>
<br>

Three standalone IoT projects on ESP32 using ESP-IDF and FreeRTOS.

| Project | Description | Key Tech |
|---------|-------------|----------|
| **BLE Gamepad Monitor** | Dual analog joysticks → BLE GATT service + SPI LCD display + Python desktop visualizer | NimBLE, SPI, ADC, Bleak |
| **Firebase LCD** | Wi-Fi → Firebase REST API → message display on SPI LCD | HTTPS, cJSON, SNTP |
| **NTP Deep Sleep Clock** | Time sync via SNTP, display on LCD, deep sleep power management | Deep Sleep, RTC, SPI |

</details>

<details>
<summary><strong>📱 ChillMove — Fitness Platform</strong>&ensp;<code>Kotlin</code> <code>Swift</code> <code>Flutter</code> <code>Docker</code> <code>Firebase</code>&ensp;📦 Production</summary>
<br>

Cross-platform fitness app with system-level native monitoring. Freelance project (Oct 2025 – Feb 2026).

**Highlights:**
- **Android** — Kill-resistant monitoring in native Kotlin: Device Owner API with Foreground Service (OOM adj 200), native Firestore sync without Flutter runtime, 9-layer protection architecture. Tested on Xiaomi MIUI, Samsung One UI
- **iOS** — Native Screen Time monitoring using Swift (Family Controls / DeviceActivityMonitor framework)
- **Backend** — Self-hosted notification worker (Node.js 18, Docker) processing 10 event types with exponential retry logic
- **App** — Flutter (BLoC, 17 cubits), Firebase Auth, Firestore, GoRouter, bilingual (EN/UK)

</details>

<details>
<summary><strong>🖥️ Production VPS Infrastructure</strong>&ensp;<code>Docker</code> <code>Nginx</code> <code>WireGuard</code> <code>Linux</code>&ensp;📦 Production (2+ years)</summary>
<br>

Ubuntu VPS hosting 13+ containerized services across 4 domains with 2+ years of continuous uptime.

**Stack:** Docker Compose, Nginx reverse proxy, WireGuard VPN, Certbot (SSL/TLS auto-renewal), UFW firewall, automated backups.

</details>

<details>
<summary><strong>🎵 AstraBot — Discord Bot</strong>&ensp;<code>Python</code> <code>discord.py</code> <code>yt-dlp</code> <code>FFmpeg</code>&ensp;📦 Production</summary>
<br>

Music & management Discord bot with async architecture. Queue-based music player (yt-dlp + FFmpeg), interactive embed builder with Modals/Views, persistent ticket system, scheduled announcements. Deployed in production.

</details>

---

<div align="center">
  <sub>B.Eng. Computer Science — Pomeranian University in Słupsk (2023–2027) · GPA 4.5 / 5.0</sub>
</div>

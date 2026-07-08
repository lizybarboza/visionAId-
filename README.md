<div align="center">

<h1>
  <img src="assets/blinking-eye.gif" width="42" alt="VisionAId Logo">
  Vision<strong>AI</strong>d
</h1>

<h3>AI-Powered Wearable Assistive Device for Visually Impaired Individuals</h3>

<p><em>Guiding Every Step with AI.</em></p>

<img src="assets/banner.png" width="100%">

</div>

<p align="center">
VisionAId is an intelligent wearable assistive system that combines
<strong>Computer Vision</strong>,
<strong>Embedded Systems</strong>,
<strong>Artificial Intelligence</strong>, and
<strong>Speech Technologies</strong>
to provide real-time object recognition, obstacle detection, voice-guided navigation, and emergency communication for visually impaired individuals.
</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-3.x-blue">
<img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green">
<img src="https://img.shields.io/badge/YOLOv3-Tiny-red">
<img src="https://img.shields.io/badge/Arduino-Nano-teal">
<img src="https://img.shields.io/badge/Status-Prototype-success">
<img src="https://img.shields.io/badge/AI-Assistive%20Technology-purple">
</p>

---

# 📖 Overview

VisionAId is an AI-powered wearable assistive device developed to improve the safety, mobility, and independence of visually impaired individuals.

Traditional mobility aids such as white canes and guide dogs provide limited environmental awareness and lack contextual understanding of surroundings. VisionAId addresses these limitations by integrating Artificial Intelligence, Computer Vision, and IoT technologies into a single assistive system.

The system enables users to:

- Detect nearby obstacles
- Recognize surrounding objects
- Receive voice-guided feedback
- Send emergency messages through voice commands
- Navigate independently and safely

---

# 🎯 Objectives

- Develop an intelligent wearable navigation system for visually impaired users.
- Implement real-time object detection using YOLOv3-Tiny.
- Detect obstacles using ultrasonic sensing.
- Provide speech-based interaction through Text-to-Speech and Speech-to-Text technologies.
- Enable emergency communication through GSM messaging.

---

# ✨ Key Features

✅ Real-Time Object Detection

✅ Obstacle Detection and Voice Alerts

✅ Speech Command Recognition

✅ Emergency SMS Communication

✅ Bluetooth-Based Wireless Communication

✅ Offline Functionality

✅ Bone-Conduction Audio Support

✅ Lightweight and Cost-Effective Prototype

---

# 🏗️ System Architecture

<p align="center">
<img src="assets/architecture.png" width="90%">
</p>

The system consists of four major stages:

1. **Input Acquisition**
   - Camera captures surroundings.
   - Ultrasonic sensor measures obstacle distance.

2. **Processing**
   - YOLOv3-Tiny performs object detection.
   - Arduino Nano processes sensor data.

3. **Communication**
   - Bluetooth transmits information to the Android application.
   - GSM module sends emergency messages.

4. **Feedback**
   - Text-to-Speech provides voice guidance.
   - Bone-conduction headphones deliver audio alerts.

---

# 🔄 System Workflow

```text
Real World Environment
        ↓
 Camera + Ultrasonic Sensor
        ↓
 YOLOv3-Tiny + Arduino Nano
        ↓
 Bluetooth Communication
        ↓
 Android Application
        ↓
 Text-to-Speech Alerts
        ↓
 Bone-Conduction Headphones
```

---

# 🛠 Hardware Components

| Component | Purpose |
|------------|----------|
| Arduino Nano | Central controller and communication hub |
| HC-SR04 Ultrasonic Sensor | Obstacle detection |
| HC-05 Bluetooth Module | Wireless communication |
| SIM800L GSM Module | Emergency messaging |
| Laptop + Camera | AI object detection processing |
| Buck Converter | Voltage regulation |
| Regulated Power Supply | Stable power management |
| Android Smartphone | Speech processing and user interaction |

---

# 💻 Software Stack

- Python
- OpenCV
- YOLOv3-Tiny
- Arduino IDE
- Android Studio
- Text-to-Speech (TTS)
- Speech-to-Text (STT)
- Bluetooth Communication
- Serial Communication

---

# 🤖 AI Model

### Model
- YOLOv3-Tiny

### Dataset
Custom dataset consisting of **19 object classes**.

### Detected Objects

- Person
- Car
- Bus
- Truck
- Motorcycle
- Bicycle
- Dog
- Cat
- Cow
- Chair
- Cup
- Laptop
- Mobile Phone
- Book
- Traffic Light
- Stop Sign
- Fire Hydrant
- Elephant
- Bottle

---

# 📊 Project Outcomes

### 🎯 Real-Time Object Recognition
Successfully detected and classified 19 object categories and generated voice feedback.

### 🚶 Reliable Obstacle Detection
Provided immediate voice alerts for obstacles within the safety threshold.

### 📱 Emergency Communication
Enabled speech-driven emergency SMS transmission without requiring internet connectivity.

---

# 📈 Results

- Real-time object recognition using YOLOv3-Tiny.
- Reliable obstacle detection using ultrasonic sensing.
- Stable Bluetooth communication.
- Prioritized safety alerts.
- Successful GSM-based emergency messaging.

---

# 🚀 Future Enhancements

- Raspberry Pi deployment
- Standalone wearable device
- GPS-based navigation
- OCR-based text reading
- Currency recognition
- Face recognition
- Cloud synchronization
- Battery optimization
- Miniaturized hardware design

---

# 📂 Repository Structure

```text
VisionAId
│
├── assets/
├── AI_Model/
├── Arduino/
├── Android_App/
├── Dataset/
├── Hardware/
├── Documentation/
├── Demo/
└── README.md
```

---

# 👩‍💻 My Contributions

- System Architecture Design
- Hardware-Software Integration
- AI Model Integration
- Dataset Preparation
- Prototype Development
- Literature Review
- System Testing and Validation
- Technical Documentation
- Project Presentation

---

# 📚 Research Contributions

This project demonstrates practical applications of:

- Artificial Intelligence
- Computer Vision
- Embedded Systems
- IoT
- Human-Centered Assistive Technology
- Real-Time Systems

---

# 📌 Project Status

**Prototype V1 Completed**

The current version has been validated in controlled indoor and outdoor environments and serves as the foundation for future standalone wearable implementations.

---

# 📜 License

Developed for academic and research purposes.

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a star!

</div>

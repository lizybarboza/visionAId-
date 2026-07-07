<div align="center">

<h1>
  <img src="assets/blinking-eye.gif" width="42" alt="VisionAId Logo">
  Vision<strong>AI</strong>d
</h1>
<h3>AI-Powered Wearable Assistive Device for Visually Impaired Individuals</h3>

<p><em>Guiding Every Step with AI.</em></p>

</div>
<p align="center">
VisionAId is an intelligent wearable assistive system that leverages
<strong>Computer Vision</strong>,
<strong>Embedded Systems</strong>, and
<strong>Artificial Intelligence</strong>
to deliver real-time object detection, obstacle awareness, voice-guided navigation, and emergency communication for visually impaired individuals.
</p>

<p align="center">

<img src="https://img.shields.io/badge/Python-3.x-blue">
<img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green">
<img src="https://img.shields.io/badge/YOLOv3-Tiny-red">
<img src="https://img.shields.io/badge/Arduino-Nano-teal">
<img src="https://img.shields.io/badge/Status-Prototype-success">
<img src="https://img.shields.io/badge/AI-Assistive%20Technology-purple">

</p>
<hr>


# Overview

VisionAId is an AI-powered wearable assistive device designed to improve the safety, mobility, and independence of visually impaired individuals.

The system combines **real-time object detection**, **obstacle sensing**, **speech technologies**, and **wireless communication** to provide users with intelligent environmental awareness and emergency support.

Unlike traditional white canes that only detect nearby obstacles, VisionAId provides semantic understanding of the surroundings by identifying everyday objects and converting the information into spoken guidance.

---

# Motivation

Navigating unfamiliar environments remains a major challenge for visually impaired individuals.

Traditional assistive devices have limitations such as:

- Limited obstacle detection
- No contextual understanding
- Lack of emergency communication
- Dependence on internet connectivity

VisionAId addresses these challenges through an affordable AI-based wearable solution capable of understanding the user's surroundings in real time.

---

# Key Features

- Real-time AI Object Detection
- Obstacle Detection using Ultrasonic Sensor
- Voice Guidance (Text-to-Speech)
- Speech Command Recognition
- Emergency SMS Alerts
- Bluetooth Communication
- Offline Functionality
- Lightweight Prototype

---

# Hardware Components

| Component | Purpose |
|------------|---------|
| Arduino Nano | Controls sensors and communication modules |
| Ultrasonic Sensor | Detects nearby obstacles |
| Bluetooth Module | Wireless communication with Android application |
| GSM Module | Sends emergency SMS alerts |
| Buck Converter | Voltage regulation |
| Regulated Power Supply | Stable power management |
| Laptop | Runs AI object detection model |
| Android Application | Speech processing and user interaction |

---

# Software Stack

- Python
- OpenCV
- YOLOv3-Tiny
- Arduino IDE
- Android Studio
- Speech-to-Text
- Text-to-Speech
- Serial Communication
- Bluetooth Communication

---

# System Architecture

```
                Camera
                   │
                   ▼
          YOLOv3-Tiny Model
                   │
                   ▼
          Laptop AI Processing
                   │
             Bluetooth Module
                   │
                   ▼
        Android Application
        (TTS / STT Engine)
                   │
                   ▼
      Bone Conduction Headphones

────────────────────────────────────

Ultrasonic Sensor
        │
        ▼
   Arduino Nano
        │
        ▼
 Bluetooth Module
        │
        ▼
 Android Application

────────────────────────────────────

 Voice Command
        │
        ▼
 Speech-to-Text
        │
        ▼
 Arduino Nano
        │
        ▼
 GSM Module
        │
        ▼
 Emergency SMS
```

---

# Workflow

1. The camera continuously captures the user's surroundings.

2. The YOLOv3-Tiny model detects and classifies nearby objects.

3. The ultrasonic sensor measures the distance to obstacles.

4. Arduino Nano processes obstacle information and prioritizes safety alerts.

5. Detection results are transmitted to the Android application via Bluetooth.

6. The Android application converts text into speech and provides real-time voice guidance.

7. Users can issue voice commands which are converted into text.

8. Emergency commands are sent to the GSM module to deliver SMS alerts to registered contacts.

---

# AI Model

Model Used:

- YOLOv3-Tiny

Dataset:

- Custom dataset consisting of **19 object classes**

Detected Objects include:

- Person
- Car
- Bus
- Truck
- Bicycle
- Motorcycle
- Dog
- Cat
- Cow
- Chair
- Cup
- Laptop
- Mobile Phone
- Book
- Fire Hydrant
- Stop Sign
- Elephant
- Traffic Light
- Bottle

---

# Results

The prototype successfully demonstrated:

- Real-time object detection with voice feedback
- Reliable obstacle detection within a safety range
- Prioritized safety alerts for obstacle avoidance
- Offline emergency SMS transmission
- Stable Bluetooth communication between hardware and Android application

---

# Future Improvements

- Raspberry Pi deployment
- Lightweight wearable design
- GPS Navigation
- OCR for text reading
- Currency Detection
- Face Recognition
- Cloud synchronization
- Battery optimization

---

# Repository Structure

```
VisionAId
│
├── AI Model
│   ├── YOLOv3-Tiny
│   ├── Weights
│   └── Detection Code
│
├── Arduino
│   ├── Obstacle Detection
│   └── GSM Communication
│
├── Android App
│   ├── Text-to-Speech
│   └── Speech-to-Text
│
├── Hardware
│   ├── Circuit Diagram
│   ├── Components
│   └── Prototype Images
│
├── Dataset
│
├── Documentation
│
├── Demo
│
└── README.md
```

---

# My Contributions

As part of this project, I was responsible for:

- Hardware architecture planning
- Embedded system integration
- AI model integration
- Dataset collection and preparation
- Literature review and technical research
- Prototype design
- System documentation
- Testing and validation
- Project presentation

---

# Project Status

Current Version:

**Prototype V1**

The prototype has been successfully developed and validated under controlled indoor and outdoor environments. Future versions will focus on hardware miniaturization, standalone deployment, and enhanced AI capabilities.

---

# References

This project was inspired by contemporary research in Assistive Technology, Computer Vision, Artificial Intelligence, Embedded Systems, and IoT, while implementing a customized architecture tailored for affordable real-world assistive navigation.

---

# License

This project was developed for academic and research purposes.

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a star!

</div>

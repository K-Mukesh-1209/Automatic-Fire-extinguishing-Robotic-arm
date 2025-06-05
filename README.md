# 🔥 Nirva Agni - AI-Based Fire Extinguishing Robotic Arm 🤖🔥

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![Status](https://img.shields.io/badge/status-Prototype-blueviolet)](#)

---

## 🚀 About Nirva Agni

**Nirva Agni** is an innovative AI-powered robotic arm designed to detect and extinguish fire automatically with precision and speed.  
Combining **computer vision**, **deep learning**, and advanced robotics, it enhances fire safety in industries, hospitals, and public spaces.

---

## 🎯 Key Features

- 🔍 Real-time fire detection using **YOLOv5** and thermal cameras  
- 🤖 Automated robotic arm control for targeted fire suppression  
- 💨 Sprays a **water + CO₂ foam mixture** for efficient extinguishing  
- 📡 24/7 CCTV surveillance & alert system  
- 🚨 Instant mobile alerts with fire location and images  
- 🔄 Dynamic & static robotic arm versions available  

---

## 🛠️ Technologies Used

| Technology            | Purpose                          |
| --------------------- | -------------------------------|
| Python                | Core AI & automation logic      |
| TensorFlow / PyTorch  | Fire detection deep learning    |
| OpenCV                | Image processing & camera control|
| Arduino / Raspberry Pi| Hardware interface               |

---

## 🎥 Demo Video

[![Watch the demo](https://img.youtube.com/vi/ppQ95qvBmH8/0.jpg)](https://www.youtube.com/watch?v=ppQ95qvBmH8)

Click the image to watch the full **Nirva Agni demo** on YouTube!

---

## 📊 System Architecture

```mermaid
flowchart TD
    A[Fire Detection Camera] --> B[AI Fire Detection Model]
    B --> C{Fire Detected?}
    C -->|Yes| D[Robotic Arm Control]
    D --> E[Spray Extinguishing Agent]
    C -->|No| F[Monitoring Continues]
    E --> G[Alert System & CCTV]

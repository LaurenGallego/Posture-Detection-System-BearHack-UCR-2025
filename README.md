# Posture Detection System – BearHack UCR 2025 🐻

A real-time posture detection system using **Computer Vision (Mediapipe)** and an **Arduino-powered feedback mechanism**, developed during **BearHack 2025** at the University of California, Riverside.  
🏆 **Awarded 3rd Place** among 30+ competing teams.

---

## 🧠 Project Overview

Poor posture is a common and often overlooked contributor to long-term health issues such as chronic back pain and muscle fatigue. Our system aims to tackle this problem by providing users with immediate feedback on their posture.

We developed a lightweight, low-cost solution that:
- Uses **Mediapipe** to analyze the user’s posture in real-time via webcam.
- Applies **custom posture metrics** to assess alignment.
- Sends a **vibration or sound alert via Arduino** when bad posture is detected.

---

## 💡 Features

- Real-time body landmark detection (Mediapipe)
- Custom posture evaluation logic
- Arduino-based feedback loop (vibration module or buzzer)
- Simple and portable hardware setup
- Ideal for desk workers, students, and remote professionals

---

## 🔧 Tech Stack

- **Python** (OpenCV, Mediapipe)
- **Arduino UNO**
- **PySerial** (for Python–Arduino communication)
- **Buzzer / Vibration motor**

---

## 🖥️ How It Works

1. The system captures live video input using a webcam.
2. Mediapipe extracts body landmarks (e.g., shoulders, hips, spine).
3. Posture metrics are computed to determine whether the user is slouching.
4. If poor posture is detected, a signal is sent to the Arduino.
5. The Arduino triggers an alert (e.g., buzz or vibration).

---

## 🔗 References
The project was inspired by [mecatronic/posture-monitor](https://github.com/mecantronic/posture-monitor).


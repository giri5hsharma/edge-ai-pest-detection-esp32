# 🐛 Edge AI Pest Detection System using ESP32-CAM

An Edge AI based pest detection system that is capable of performing real-time image classification using **TensorFlow Lite Micro** deployed on an **ESP32-CAM**.

This project was developed as part of the Robotics & Automation Tinker Programme to demonstrate how Machine Learning models can be deployed on resource-constrained embedded hardware for agricultural applications.

---

## 🚀 Features

- Real-time pest detection on ESP32-CAM
- TensorFlow Lite Micro inference
- On-device image classification
- Camera-based pest recognition
- IR sensor based object detection
- OLED display for user feedback
- Buzzer alert system
- Edge AI deployment without cloud connectivity

- ---

# 🛠 Hardware Components

- ESP32-CAM
- Arduino Uno (Functionality Demonstration)
- IR Sensor
- OLED Display (I2C)
- Active Buzzer
- Breadboard & Jumper Wires

---

# 💻 Software & Technologies

- Python
- TensorFlow
- TensorFlow Lite
- TensorFlow Lite Micro
- Arduino IDE
- Embedded C++
- ESP32 Camera Library
- Edge AI
- Computer Vision

---

# 🧠 Project Workflow

```text
Pest Image Dataset
        │
        ▼
Train CNN Model (TensorFlow)
        │
        ▼
Convert to TensorFlow Lite (.tflite)
        │
        ▼
Convert Model to C Header (.h)
        │
        ▼
Deploy on ESP32-CAM
        │
        ▼
Capture Live Image
        │
        ▼
Run On-device Inference
        │
        ▼
Pest Detected?
      ┌──────┴──────┐
      ▼             ▼
 OLED Display    Buzzer Alert
```

---

# 📸 Hardware Setup

### ESP32-CAM Prototype

![ESP32-CAM Setup](ESP32-CAM%20setup.jpeg)

### Arduino + OLED Demonstration

![Arduino Prototype](Arduino%20%2B%20OLED%20setup.jpeg)

---

# 📊 Results

- Successfully trained a lightweight pest detection model using TensorFlow.
- Converted the trained model into TensorFlow Lite format for embedded deployment.
- Deployed the model on an ESP32-CAM using TensorFlow Lite Micro.
- Demonstrated real-time on-device inference without cloud connectivity.
- Built a proof-of-concept object detection system using an IR sensor, OLED display, and buzzer.

---

# 🚀 Future Improvements

- Improve model accuracy using a larger dataset.
- Add support for additional pest classes.
- Optimize inference speed on edge devices.
- Integrate wireless notifications and cloud logging.
- Design a compact PCB for field deployment.

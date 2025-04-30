# STM32 Ultrasonic Distance-Based Servo Control

## 📌 Overview
This project demonstrates real-time distance measurement using an **ultrasonic sensor** with an **STM32 microcontroller**. When an object is detected within **20 cm**, a **servo motor** rotates from **0° to 90°**, simulating a basic proximity-based actuation system. The measured distance is also displayed on a **16x2 LCD screen** in real-time.

---

## 🧰 Hardware Components
- STM32F401RE (Nucleo)
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- 16x2 LCD Display (I2C)
- Breadboard and jumper wires
- 5V power supply (USB or external)

---

## 💡 Features
- Real-time object detection and measurement using ultrasonic sensing
- Servo motor reacts to nearby objects (within 20 cm)
- LCD shows live distance readings in centimeters
- Efficient polling with STM32 HAL libraries

---

## 💻 Software & Tools
- STM32CubeIDE
- STM32 HAL Drivers
- C Programming
- I2C communication

---

## 🚀 How It Works
1. The HC-SR04 sensor sends out an ultrasonic pulse and listens for the echo.
2. The time taken for the echo to return is used to calculate distance.
3. If the distance is less than 20 cm:
   - The servo rotates to 90°
4. If the distance is greater than or equal to 20 cm:
   - The servo remains at 0°
5. The 2x16 LCD updates the current distance in real-time.

---

## 🎓 What I Learned

This project was a great opportunity to practice and improve my embedded systems skills:

- 📐 **Ultrasonic sensor integration**: Learned how to trigger and read echo times to calculate distances using precise timer input capture in STM32.
- 🔧 **Servo motor control**: Gained hands-on experience generating PWM signals using STM32 timers to control servo angles.
- 🧾 **LCD interfacing**: Practiced displaying dynamic sensor data on an LCD in real-time using I2C.
- 📚 **STM32 HAL library usage**: Became more confident with HAL-based development and debugging within STM32CubeIDE.
- 🧠 **Real-time systems logic**: Understood how to structure polling-based systems to respond to real-time events efficiently.
- 📈 **Project documentation**: Improved my ability to document and structure code for readability and sharing with others.

---

## 📸 Demo
found on my linkedin profile :
---






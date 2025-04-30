# STM32 Ultrasonic Distance-Based Servo Control

## 📌 Overview
This project uses an STM32 microcontroller to measure distance using an ultrasonic sensor (HC-SR04). When an object is detected within 20 cm, a servo motor rotates from 0° to 90°. The distance is displayed in real-time on a 2x16 LCD.

## 🧰 Hardware Components
- STM32F103C8T6 (Blue Pill)
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- 16x2 LCD Display (with I2C or parallel interface)
- Breadboard & Jumper Wires
- 5V Power Supply

## 🔌 Wiring Diagram
*(You can add a hand-drawn image, Fritzing diagram, or schematic here)*

## 🧠 Features
- Real-time distance measurement
- LCD live display of the measured distance
- Servo control based on object proximity

## 💻 Code
Written in C using STM32CubeIDE or STM32 HAL libraries. The main logic checks the distance and updates the servo angle and LCD display accordingly.

## 🚀 How It Works
1. The ultrasonic sensor measures the distance to an object.
2. If distance < 20 cm:
   - Servo rotates to 90°
3. Else:
   - Servo stays at 0°
4. LCD shows the distance in cm.

## 📸 Demo
*(Insert a short video or image GIF here of it working, or link to a YouTube demo)*

## 📂 File Structure

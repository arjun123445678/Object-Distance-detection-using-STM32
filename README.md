# 🚀 Object Detection using STM32 and Ultrasonic Sensor (Displayed on LCD)

This project implements a basic **object detection system** using an **ultrasonic sensor** (like HC-SR04) with an **STM32 microcontroller**. The detected distance is displayed in real-time on a **16x2 I2C LCD**. It’s useful for proximity alerts, obstacle detection, or DIY automation systems.

---

## 📦 Features

- Real-time object distance measurement
- Visual output on 16x2 I2C LCD
- Threshold-based object detection alert
- Easy to extend for buzzer/LED alerts or WiFi transmission

---

## 🔧 Hardware Used

| Component         | Description                         |
|------------------|-------------------------------------|
| STM32 MCU        |  STM32L4BL475EIOT1A                 |
| Ultrasonic Sensor| HC-SR04                             |
| LCD Display      | 16x2 I2C LCD                        |
| Jumper Wires     | For connections                     |
| Breadboard       | For prototyping                     |

---

## 🔌 Wiring Diagram

| Ultrasonic Sensor | STM32 Pin        |
|-------------------|------------------|
| VCC               | 5V / 3.3V         |
| GND               | GND               |
| Trig              | PD6               |
| Echo              | PD7               |

| I2C LCD | STM32 Pin         |
|---------|-------------------|
| SDA     | PD13              |
| SCL     | PD14              |
https://github.com/arjun123445678/Object-Distance-detection-using-STM32/blob/main/WhatsApp%20Image%202025-04-23%20at%2008.41.18_1f68e507.jpg



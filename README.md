# 🛒 Smart Trolley System with RFID – Inventory Management

## 🔍 Overview

This project implements a Smart Trolley System using RFID technology for real-time inventory tracking and improved shopping experiences. It minimizes manual checkout processes, enhances customer satisfaction, and offers insights into consumer behavior through RFID-based object tracking.

---

## 📌 Features

- RFID-based item detection and identification
- Battery-efficient operation using sleep modes
- Arduino Uno integration
- Real-time serial output of scanned RFID tags
- LCD, buzzer, and LED-based user feedback
- Support for multiple RFID frequencies (LF, HF, UHF)

---

## 📦 Hardware Components

- Arduino Uno
- MFRC522 RFID Module
- RFID Tags/Cards
- LCD Display
- Buzzer
- LEDs
- Potentiometer
- Power Supply or Battery
- PCB Board or Breadboard
- Connecting Wires

---

## ⚙️ Circuit & Working

Each time an RFID-tagged item is placed in the trolley, the tag UID is read and displayed on the serial monitor. The microcontroller processes this data and provides visual and audio feedback. LCD can show product info and cost.

---

## 💡 Code Description

The Arduino sketch initializes SPI communication and the MFRC522 module. It continuously scans for new RFID cards and prints the UID of any detected tag to the serial monitor.

---

## 🧪 Results & Discussions

- **Low power consumption** via optimized sleep modes
- **Accurate tag reading** under dynamic conditions
- **Increased battery life** through power management strategies
- **User-friendly feedback** with LCD and buzzer

---

## 🧾 Conclusion

This smart trolley prototype demonstrates how RFID technology can enhance traditional inventory systems. By combining efficient hardware with thoughtful power-saving design, it offers a scalable and user-centric solution for retail automation.

---




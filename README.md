# 2-Axis Arduino Ultrasonic SCANNER 📡

A DIY **2-axis ultrasonic scanning system** built with an Arduino Uno, two SG90 servo motors, an HC-SR04 ultrasonic sensor, and an ST7735 1.8" TFT display.

The system creates a visual representation of the area being scanned and displays detected objects as red markers on the TFT.

---

## ✨ Features

- 🔄 2-axis scanning
- ↔️ Horizontal left/right servo scanning
- ↕️ Vertical up/center movement
- 📡 HC-SR04 ultrasonic distance detection
- 🖥️ ST7735 1.8" TFT graphical display
- 🟡 Yellow live scan line
- 🔴 Red object detection line
- 📏 Real-time distance display
- 🔁 Automatic continuous scanning
- ⚡ Only one servo moves at a time
- 🎯 Two separate semicircular scan areas

---

## 🧠 How It Works

The scanner uses two SG90 servos.

### Horizontal Axis

The first servo controls the left/right direction.

```text
0°                 90°                180°
LEFT  <-------------|---------------> RIGHT
